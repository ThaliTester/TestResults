#### Test 63036995fb62ea7_thali08_samsung-SM-A300FU Logs


```
--------- beginning of main
03-17 07:10:32.845   317  3059 D QC-time-services: Updating the TOD offset
03-17 07:10:32.845   317  3059 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1436214201803 to memory
03-17 07:10:32.845   317  3059 D QC-time-services: Daemon:Opening File: /data/time/ats_1
03-17 07:10:32.845   317  3059 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
03-17 07:10:32.855   317  3059 E QC-time-services: Daemon:Update to modem bit set
03-17 07:10:32.855   317  3059 D QC-time-services: Daemon:genoff_send_modem: Sending data to MODEM !
03-17 07:10:32.855   317  3059 D QC-time-services: Daemon: Base = 2, Value being sent to MODEM = 1120249401803
03-17 07:10:32.855  3027  3027 E QC-time-services: Receive Passed == base = 2, unit = 1, operation = 0, result = 0
03-17 07:10:32.855   317   554 E QC-time-services: Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
03-17 07:10:32.855   317   556 E QC-time-services: Daemon: Time-services: Waiting to acceptconnection
--------- beginning of system
03-17 07:10:32.855  1022  1321 I ActivityManager: Killing 2409:com.sec.modem.settings/1000 (adj 15): empty #31
03-17 07:10:32.855  1022  1321 I ActivityManager: Killing 2439:com.sec.tcpdumpservice/1000 (adj 15): empty #31
,03-17 07:10:32.955  1022  1046 W libprocessgroup: failed to open /acct/uid_1000/pid_2409/cgroup.procs: No such file or directory
03-17 07:10:32.955  1022  1046 W libprocessgroup: failed to open /acct/uid_1000/pid_2439/cgroup.procs: No such file or directory
03-17 07:10:32.965  1022  1520 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:32.965  1022  1520 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 07:10:32.965  1022  1520 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-17 07:10:32.995  1022  1902 D SettingsProvider: name = next_alarm_formatted
03-17 07:10:32.995  1022  1902 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-17 07:10:32.995  1022  1902 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-17 07:10:32.995  1022  1902 D SettingsProvider: selectionArgs: false
03-17 07:10:32.995  1022  1902 D SettingsProvider: selectionArgs: 10081
03-17 07:10:32.995  1022  1902 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-17 07:10:32.995  1022  1902 D SettingsProvider: ret = -1
03-17 07:10:33.045  1022  1902 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10081
03-17 07:10:33.075  1206  1206 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
03-17 07:10:33.095  1022  1667 I ActivityManager: Killing 2456:com.sec.android.app.sbrowser/u0a127 (adj 15): empty #31
03-17 07:10:33.105   296   296 E USB_UICC: Timeout! No signal received. Retry num = 29
03-17 07:10:33.115   315   315 I ServiceManager: Waiting for service AtCmdFwd...
03-17 07:10:33.155  1022  1597 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:33.155  1022  1597 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 07:10:33.155  1022  1597 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
03-17 07:10:33.195  3043  3043 W art     : Verification of void com.sec.android.app.clockpackage.alarm.Alarm.InitAlarmList() took 131.908ms
03-17 07:10:33.215  1022  1046 W libprocessgroup: failed to open /acct/uid_10127/pid_2456/cgroup.procs: No such file or directory
03-17 07:10:33.245  1022  1520 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:33.245  1022  1520 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:33.245  1022  1520 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:33.245  1022  1520 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:33.255  3081  3081 E Zygote  : MountEmulatedStorage()
03-17 07:10:33.255  3081  3081 E Zygote  : v2
03-17 07:10:33.265  3081  3081 I libpersona: KNOX_SDCARD checking this for 10090
03-17 07:10:33.265  3081  3081 I libpersona: KNOX_SDCARD not a persona
03-17 07:10:33.265  1022  1520 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=3081 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
03-17 07:10:33.265  1022  1520 I ActivityManager: Killing 2473:com.sec.android.app.SecSetupWizard/1000 (adj 15): empty #31
03-17 07:10:33.265  3081  3081 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 07:10:33.265  3081  3081 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 07:10:33.275  3081  3081 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 07:10:33.305  3081  3081 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 07:10:33.305  3081  3081 D ActivityThread: Added TimaKeyStore provider
03-17 07:10:33.335  3081  3081 D elm:15121: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver }
03-17 07:10:33.345  3081  3081 D elm:15121: ELMEngine.ELMEngine( context ).
03-17 07:10:33.345  3081  3081 D elm:15121: MDMBridge.setEnterpriseBridge()
03-17 07:10:33.345  1022  1392 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:33.345  1022  1392 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:33.345  1022  1392 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
03-17 07:10:33.345  3081  3081 D elm:15121: ELMAbstractReceiver : Receive Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService } END.
03-17 07:10:33.345  3081  3081 D elm:15121: ElmAgentService : onCreate()
03-17 07:10:33.345  3081  3096 D elm:15121: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService }
03-17 07:10:33.345  1022  1659 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:33.345  1022  1659 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:33.345  1022  1659 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:33.345  1022  1659 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:33.355  3081  3096 D elm:15121: ELMAgentService.listeningToTimeDateChanges( context, intent ).
03-17 07:10:33.355  3081  3081 D elm:15121: ELMEngine.ServiceHandler.handleMessage( ALARM_MODIFY ). 
03-17 07:10:33.355  3081  3081 D elm:15121: ModuleBase.ModifySetAlarm()
03-17 07:10:33.355  3081  3081 D elm:15121: MDMBridge.getInstance()
03-17 07:10:33.355  3081  3081 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
03-17 07:10:33.365  3099  3099 E Zygote  : MountEmulatedStorage()
03-17 07:10:33.365  3099  3099 E Zygote  : v2
03-17 07:10:33.365  3099  3099 I libpersona: KNOX_SDCARD checking this for 10130
03-17 07:10:33.365  3099  3099 I libpersona: KNOX_SDCARD not a persona
03-17 07:10:33.365  3099  3099 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 07:10:33.365  3099  3099 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 07:10:33.365  1022  1659 I ActivityManager: Start proc com.sec.android.widgetapp.SPlannerAppWidget for broadcast com.sec.android.widgetapp.SPlannerAppWidget/.EasyWidget.EasyCalendarAppWidgetProvider: pid=3099 uid=10130 gids={50130, 9997} abi=armeabi-v7a
03-17 07:10:33.365  3099  3099 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
03-17 07:10:33.375  1022  1046 W libprocessgroup: failed to open /acct/uid_1000/pid_2473/cgroup.procs: No such file or directory
03-17 07:10:33.385  1022  1520 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:33.385  1022  1520 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
03-17 07:10:33.385  1022  1520 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
03-17 07:10:33.385  3081  3081 D elm:15121: ElmAgentService : onDestroy().
03-17 07:10:33.395  3099  3099 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 07:10:33.395  3099  3099 D ActivityThread: Added TimaKeyStore provider
03-17 07:10:33.405  1022  1520 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:33.405  1022  1520 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:33.405  1022  1520 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
03-17 07:10:33.415  3099  3099 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 07:10:33.415  3099  3099 W ResourcesManager: Asset path '/system/framework/sws.jar' does not exist or contains no resources.
03-17 07:10:33.435  3075  3075 D AndroidRuntime: 
03-17 07:10:33.435  3075  3075 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
03-17 07:10:33.435  3075  3075 D AndroidRuntime: CheckJNI is OFF
03-17 07:10:33.435  3075  3075 D AndroidRuntime: readGMSProperty: start
03-17 07:10:33.435  3075  3075 D AndroidRuntime: readGMSProperty: already setted!!
03-17 07:10:33.435  3075  3075 D AndroidRuntime: propertySet: couldn't set property (it is from app)
03-17 07:10:33.435  3075  3075 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
03-17 07:10:33.435  3075  3075 D AndroidRuntime: readGMSProperty: end
03-17 07:10:33.435  3075  3075 D AndroidRuntime: addProductProperty: start
03-17 07:10:33.475  1022  1034 I ActivityManager: Killing 2516:com.wsomacp/u0a23 (adj 15): empty #31
03-17 07:10:33.485  1022  1404 I splitIntent: Queue : backgroundsplit_0 intent android.intent.action.TIME_SET is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
03-17 07:10:33.495  1022  1404 I ActivityManager: Killing 2534:com.sec.android.gallery3d/u0a39 (adj 15): empty #31
03-17 07:10:33.495  1022  1047 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:33.495  1022  1047 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:33.495  1022  1047 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:33.495  1022  1047 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:33.495  2837  2887 I SA      : [RC New] [v2liruge] api execute + 935
03-17 07:10:33.495  2837  2887 I SA      : [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
03-17 07:10:33.505  2631  2631 I PCWCLIENTTRACE_SYSTEMReceiver: mConnectivityHandler : connected
03-17 07:10:33.505  2837  2887 I System.out: AsyncTask #1 calls detatch()
03-17 07:10:33.515  3120  3120 E Zygote  : MountEmulatedStorage()
03-17 07:10:33.515  3120  3120 I libpersona: KNOX_SDCARD checking this for 1000
03-17 07:10:33.515  3120  3120 E Zygote  : v2
03-17 07:10:33.515  3120  3120 I libpersona: KNOX_SDCARD not a persona
03-17 07:10:33.515  3120  3120 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 07:10:33.515  2837  2887 I SA      : [ODM] saveOpenData( GEO_IP, PL )
03-17 07:10:33.515  1022  1047 I ActivityManager: Start proc com.sec.factory for broadcast com.sec.factory/.entry.FactoryTestBroadcastReceiver: pid=3120 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-17 07:10:33.515  3120  3120 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 07:10:33.515  3120  3120 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 07:10:33.525  2631  3119 W PCWCLIENTTRACE_AccountUtil: [hasSamungAccount] - No Samsung Account
03-17 07:10:33.535  2837  2887 I SA      : [OCP] update openData : PL
03-17 07:10:33.535  1022  1321 I ActivityManager: Killing 2560:com.sec.android.widgetapp.activeapplicationwidget/u0a139 (adj 15): empty #31
03-17 07:10:33.545  2837  2887 I SA      : [TPMU] getNetworkMcc : 
03-17 07:10:33.545  2837  2887 I SA      : [SCU] saveMccToPreferece Start
03-17 07:10:33.545  2837  2887 I SA      : [SCU] RegionMCC : 260
03-17 07:10:33.545  2837  2887 I SA      : [SSP] query invoked
03-17 07:10:33.545  2837  2887 I SA      : [TPMU] GetMccFromDB : null
03-17 07:10:33.545  2837  2887 I SA      : [SCU] getMccFromPreferece mcc = 260
03-17 07:10:33.545  2837  2887 I SA      : [SCU] saveMccToPreferece End
03-17 07:10:33.545  2837  2887 I SA      : [RC New] executeRequest [v2liruge] end. 1053
03-17 07:10:33.545  2837  2887 I SA      : [RC New] Execute end
03-17 07:10:33.545  2837  2837 I SA      : [OR] GetMyCountryZoneTask mcc = 260
03-17 07:10:33.545  2837  2837 I SA      : [OR] GetMyCountryZoneTask Success
03-17 07:10:33.555  3120  3120 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 07:10:33.555  3120  3120 D ActivityThread: Added TimaKeyStore provider
03-17 07:10:33.565  3120  3120 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
03-17 07:10:33.585  1022  1046 W libprocessgroup: failed to open /acct/uid_10039/pid_2534/cgroup.procs: No such file or directory
03-17 07:10:33.595  1022  1046 W libprocessgroup: failed to open /acct/uid_10023/pid_2516/cgroup.procs: No such file or directory
03-17 07:10:33.595  1022  1046 W libprocessgroup: failed to open /acct/uid_10139/pid_2560/cgroup.procs: No such file or directory
03-17 07:10:33.645  3120  3120 D FactoryTestApp: [FactoryTestBroadcastReceiver$onReceive](3120) onReceive action=android.intent.action.BOOT_COMPLETED
03-17 07:10:33.655  3120  3120 W ActivityThread: ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
03-17 07:10:33.655  3120  3120 D FactoryTestApp: [XMLDataStorage$parseXML](3120) is Live Demo : false
03-17 07:10:33.665  3120  3120 D FactoryTestApp: [XMLDataStorage$parseXML](3120) modelXML=sm-a300fu.dat
03-17 07:10:33.665  2631  3119 I PCWCLIENTTRACE_SecurePreferencesJNI: [GetString-S]
03-17 07:10:33.665  3120  3120 D FactoryTestApp: [XMLDataStorage$parseXML](3120) deviceXML=a3ulte.dat
03-17 07:10:33.665  3120  3120 D FactoryTestApp: [XMLDataStorage$parseXML](3120) nameXML=a3ultexx.dat
03-17 07:10:33.665  3120  3120 D FactoryTestApp: [XMLDataStorage$parseAsset](3120) parseAsset Is Started
03-17 07:10:33.725  1022  1520 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-17 07:10:33.725  1022  1520 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4307, temperature: 246, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-17 07:10:33.725  1022  1520 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-17 07:10:33.725  1022  1022 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-17 07:10:33.725  1022  1022 I MotionRecognitionService: Plugged
03-17 07:10:33.725  1022  1022 I MotionRecognitionService: mGripSensorEnabled= false
03-17 07:10:33.735  1206  1206 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-17 07:10:33.735  1206  1206 D KeyguardUpdateMonitor: handleBatteryUpdate
03-17 07:10:33.735  1206  1206 D PowerUI : Cable  true --> true mBootCompleted : false
03-17 07:10:33.735  1206  1206 D PowerUI : Sending cableIntent : Intent { act=com.samsung.systemui.power.action.ACTION_CABLE_CONNECTED }
03-17 07:10:33.735  1445  1445 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-17 07:10:33.735  1445  1445 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
03-17 07:10:33.745  1206  1206 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-17 07:10:33.745  2631  3119 I ReactiveServiceManager: Supported : 1
03-17 07:10:33.745  3120  3120 I FactoryTestApp: [XMLDataStorage$parseAsset](3120) Convert dat file: sm-a300fu.dat
03-17 07:10:33.755  1206  1206 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-17 07:10:33.755  1206  1206 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-17 07:10:33.755  1206  1206 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-17 07:10:33.755  1206  1206 D SViewCoverView: level :100 plugged : 2
03-17 07:10:33.775  1022  1667 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x2040
03-17 07:10:33.775  1022  1667 D QSEECOMAPI: : App is not loaded in QSEE
03-17 07:10:33.775  3120  3120 D FactoryTestApp: [XMLDataStorage$parseAsset](3120) Decode base file: factory.dat
03-17 07:10:33.795  1022  1667 D QSEECOMAPI: : Loaded image: APP id = 9
03-17 07:10:33.795  1022  1667 D QSEECOMAPI: : QSEECom_dealloc_memory 
03-17 07:10:33.795  1022  1667 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 9
03-17 07:10:33.795  1022  1667 E terrier : handleString: Failed to handle string(-4)
03-17 07:10:33.795  1022  1667 E terrier : Java_com_android_server_ReactiveService_GetString: error code = [-4]
03-17 07:10:33.795  2631  3119 D PCWCLIENTTRACE_SecurePreferencesJNI: getString is null
03-17 07:10:33.795  2631  3119 I PCWCLIENTTRACE_SecurePreferencesJNI: [GetString-E]
03-17 07:10:33.805  2631  3119 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
03-17 07:10:33.805  2631  3119 I PCWCLIENTTRACE_PushUtil: sales region : global
03-17 07:10:33.805  2631  3119 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
03-17 07:10:33.805  2631  3119 E PCWCLIENTTRACE_PCWHandler: [ensureRegistration] - No Samsung account
03-17 07:10:33.855  3120  3120 D FactoryTestApp: [XMLDataStorage$redefinitionById](3120) id=FACTORY_TEST_APP
03-17 07:10:33.855  3120  3120 D FactoryTestApp: [XMLDataStorage$redefinitionById](3120) id=FACTORY_TEST_COMMAND
03-17 07:10:33.855  3120  3120 D FactoryTestApp: [XMLDataStorage$redefinitionById](3120) id=FAILHIST_VERSION
03-17 07:10:33.855  3120  3120 D FactoryTestApp: [XMLDataStorage$redefinitionById](3120) id=MODEL_NAME
03-17 07:10:33.855  3120  3120 D FactoryTestApp: [XMLDataStorage$redefinitionById](3120) id=MODEL_NUMBER
03-17 07:10:33.855  3120  3120 D FactoryTestApp: [XMLDataStorage$redefinitionById](3120) id=MODEL_HARDWARE_REVISION
03-17 07:10:33.855  3120  3120 D FactoryTestApp: [XMLDataStorage$redefinitionById](3120) id=MODEL_COMMUNICATION_MODE
03-17 07:10:33.855  3120  3120 D FactoryTestApp: [XMLDataStorage$redefinitionById](3120) id=CHIPSET_MANUFACTURE
03-17 07:10:33.855  3120  3120 D FactoryTestApp: [XMLDataStorage$redefinitionById](3120) id=CHIPSET_NAME
03-17 07:10:33.855  3120  3120 D FactoryTestApp: [XMLDataStorage$redefinitionById](3120) id=DEVICE_TYPE
03-17 07:10:33.855  3120  3120 D FactoryTestApp: [XMLDataStorage$redefinitionById](3120) id=BATT_TYPE
03-17 07:10:33.855  3120  3120 D FactoryTestApp: [XMLDataStorage$redefinitionById](3120) id=PANEL_TYPE
03-17 07:10:33.855  3120  3120 D FactoryTestApp: [XMLDataStorage$redefinitionById](3120) id=SENSOR_NAME_ACCELEROMETER
03-17 07:10:33.855  3120  3120 D FactoryTestApp: [XMLDataStorage$redefinitionById](3120) id=SENSOR_NAME_MAGNETIC
03-17 07:10:33.855  3120  3120 D FactoryTestApp: [XMLDataStorage$redefinitionById](3120) id=SENSOR_NAME_GYROSCOPE
03-17 07:10:33.855  3120  3120 D FactoryTestApp: [XMLDataStorage$redefinitionById](3120) id=REAR_CAMERA_TYPE
03-17 07:10:33.855  3120  3120 D FactoryTestApp: [XMLDataStorage$redefinitionById](3120) id=FRONT_CAMERA_TYPE
03-17 07:10:33.855  3120  3120 D FactoryTestApp: [XMLDataStorage$redefinitionById](3120) id=ISP_FLASH_TEST_SMD
03-17 07:10:33.855  3120  3120 D FactoryTestApp: [XMLDataStorage$redefinitionById](3120) id=SPEAKER_COUNT
03-17 07:10:33.855  3120  3120 D FactoryTestApp: [XMLDataStorage$redefinitionById](3120) id=MIC_COUNT
03-17 07:10:33.855  3120  3120 D FactoryTestApp: [XMLDataStorage$redefinitionById](3120) id=TORCH_MODE_FLASH_ON_CURRENT
03-17 07:10:33.855  3120  3120 D FactoryTestApp: [XMLDataStorage$redefinitionById](3120) id=SUPPORT_VIBRATOR
03-17 07:10:33.855  3120  3120 D FactoryTestApp: [XMLDataStorage$redefinitionById](3120) id=SUPPORT_LTE
03-17 07:10:33.855  3120  3120 D FactoryTestApp: [XMLDataStorage$redefinitionById](3120) id=SUPPORT_QWERTY_KEY
03-17 07:10:33.855  3120  3120 D FactoryTestApp: [XMLDataStorage$redefinitionById](3120) id=SUPPORT_FRONT_CAMERA
03-17 07:10:33.855  3120  3120 D FactoryTestApp: [XMLDataStorage$redefinitionById](3120) id=SUPPORT_RCV
03-17 07:10:33.855  3120  3120 D FactoryTestApp: [XMLDataStorage$redefinitionById](3120) id=FACTORY_TEST_APO
03-17 07:10:33.855  3120  3120 D FactoryTestApp: [XMLDataStorage$redefinitionById](3120) id=SUPPORT_BOOST_MEDIASCAN
03-17 07:10:33.855  3120  3120 D FactoryTestApp: [XMLDataStorage$redefinitionById](3120) id=SUPPORT_NVBACKUP_CMD
03-17 07:10:33.855  3120  3120 D FactoryTestApp: [XMLDataStorage$redefinitionById](3120) id=SUPPORT_EPEN
03-17 07:10:33.855  3120  3120 D FactoryTestApp: [XMLDataStorage$redefinitionById](3120) id=SUPPORT_SENSORHUB
03-17 07:10:33.855  3120  3120 D FactoryTestApp: [XMLDataStorage$redefinitionById](3120) id=SUPPORT_CAM_ISP
03-17 07:10:33.865  3120  3120 D FactoryTestApp: [XMLDataStorage$redefinitionById](3120) id=SUPPORT_CAM_FRONT_NOT_ISP
03-17 07:10:33.865  3120  3120 D FactoryTestApp: [XMLDataStorage$redefinitionById](3120) id=SUPPORT_SECOND_MIC_TEST
03-17 07:10:33.865  3120  3120 D FactoryTestApp: [XMLDataStorage$redefinitionById](3120) id=HW_VER_EFS
03-17 07:10:33.865  3120  3120 D FactoryTestApp: [XMLDataStorage$redefinitionById](3120) id=SUPPORT_BOOK_COVER
03-17 07:10:33.865  3120  3120 D FactoryTestApp: [XMLDataStorage$redefinitionById](3120) id=SUPPORT_HOVER_HIGHTLIGHT
03-17 07:10:33.865  3120  3120 D FactoryTestApp: [XMLDataStorage$redefinitionById](3120) id=FACTOLOG_SYSTEM_INFO_UPDATE
03-17 07:10:33.865  3120  3120 D FactoryTestApp: [XMLDataStorage$redefinitionById](3120) id=SUPPORT_AUTO_WAKELOCK
03-17 07:10:33.865  3120  3120 D FactoryTestApp: [XMLDataStorage$redefinitionById](3120) id=SUPPORT_AP_EX_THERM_ADC
03-17 07:10:33.865  3120  3120 D FactoryTestApp: [XMLDataStorage$redefinitionById](3120) id=IS_MULTI_SIM_FRAMEWORK
03-17 07:10:33.865  3120  3120 D FactoryTestApp: [XMLDataStorage$redefinitionById](3120) id=SUPPORT_DSDS_MSIMM_CHECK
03-17 07:10:33.865  3120  3120 D FactoryTestApp: [XMLDataStorage$redefinitionById](3120) id=SUPPORT_DUAL_STANBY_ONE_CP
03-17 07:10:33.865  3120  3120 D FactoryTestApp: [XMLDataStorage$redefinitionById](3120) id=SUPPORT_RUN_REF
03-17 07:10:33.865  3120  3120 D FactoryTestApp: [XMLDataStorage$redefinitionById](3120) id=FONT_SIZE
03-17 07:10:33.865  3120  3120 D FactoryTestApp: [XMLDataStorage$redefinitionById](3120) id=RAM_SIZE_IF
03-17 07:10:33.865  3075  3075 E AffinityControl: AffinityControl: registerfunction enter
03-17 07:10:33.865  3120  3120 D FactoryTestApp: [XMLDataStorage$redefinitionById](3120) id=MULTI_TSK_THD
03-17 07:10:33.865  3120  3120 D FactoryTestApp: [XMLDataStorage$redefinitionById](3120) id=SEMI_FUNCTION_FONT_SIZE
03-17 07:10:33.865  3120  3120 D FactoryTestApp: [XMLDataStorage$redefinitionById](3120) id=NEED_LPA_MODE_SET
03-17 07:10:33.865  3120  3120 D FactoryTestApp: [XMLDataStorage$redefinitionById](3120) id=SUPPORT_SEMI_FUNCTION_TEST
03-17 07:10:33.865  3120  3120 D FactoryTestApp: [XMLDataStorage$redefinitionById](3120) id=SEMI_FUNCTION_TEST_UI_ORIENTATION
03-17 07:10:33.865  3120  3120 D FactoryTestApp: [XMLDataStorage$redefinitionById](3120) id=SUPPORT_SEMI_NV_RESET
03-17 07:10:33.865  3120  3120 D FactoryTestApp: [XMLDataStorage$redefinitionById](3120) id=BOOT_CHECK_TOUCHKEY_WO_SVCLED
03-17 07:10:33.865  3120  3120 D FactoryTestApp: [XMLDataStorage$redefinitionById](3120) id=SUPPORT_SELFTEST_DISPLAY_DELAY
03-17 07:10:33.875  3120  3120 D FactoryTestApp: [XMLDataStorage$redefinitionById](3120) id=KEY_TEST_VOLUME_UP
03-17 07:10:33.875  3120  3120 D FactoryTestApp: [XMLDataStorage$redefinitionById](3120) id=KEY_TEST_VOLUME_DOWN
03-17 07:10:33.885  3120  3120 D FactoryTestApp: [XMLDataStorage$redefinitionById](3120) id=KEY_TEST_POWER
03-17 07:10:33.885  3120  3120 D FactoryTestApp: [XMLDataStorage$redefinitionById](3120) id=KEY_TEST_APP_RECENT
03-17 07:10:33.895  3075  3075 D AndroidRuntime: Calling main entry com.android.commands.am.Am
03-17 07:10:33.895  3120  3120 D FactoryTestApp: [XMLDataStorage$redefinitionById](3120) id=KEY_TEST_HOME
03-17 07:10:33.905  3120  3120 D FactoryTestApp: [XMLDataStorage$redefinitionById](3120) id=KEY_TEST_BACK
03-17 07:10:33.905  3120  3120 D FactoryTestApp: [XMLDataStorage$redefinitionById](3120) id=KEY_TEST_TOUCH_KEY_ODER
03-17 07:10:33.905  3120  3120 D FactoryTestApp: [XMLDataStorage$redefinitionById](3120) id=KEY_TEST_VIEW_TABLE
03-17 07:10:33.915  1022  1034 E PersonaManagerService: inState():  stateMachine is null !!
03-17 07:10:33.915  1022  1034 I PersonaManagerService: PersonaId don't exist
03-17 07:10:33.915  1022  1034 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
03-17 07:10:33.915  3120  3120 D FactoryTestApp: [XMLDataStorage$redefinitionById](3120) id=SEMI_KEY_TEST_VOLUME_UP
03-17 07:10:33.915  1022  1034 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-17 07:10:33.915  3120  3120 D FactoryTestApp: [XMLDataStorage$redefinitionById](3120) id=SEMI_KEY_TEST_VOLUME_DOWN
03-17 07:10:33.925  3120  3120 D FactoryTestApp: [XMLDataStorage$redefinitionById](3120) id=SEMI_KEY_TEST_HOME
03-17 07:10:33.925  1022  1034 W ActivityManager: mDVFSHelper.acquire()
03-17 07:10:33.935  1022  1034 D FocusedStackFrame: Set to : 0
03-17 07:10:33.935  3120  3120 D FactoryTestApp: [XMLDataStorage$redefinitionById](3120) id=IS_KEY_TEST_THRESHOLD
03-17 07:10:33.935  3120  3120 D FactoryTestApp: [XMLDataStorage$redefinitionById](3120) id=IS_TSP_STANDARD_CHANNEL
03-17 07:10:33.935  3120  3120 D FactoryTestApp: [XMLDataStorage$redefinitionById](3120) id=IS_SENSOR_TEST_ACC_REVERSE
03-17 07:10:33.935  3120  3120 D FactoryTestApp: [XMLDataStorage$redefinitionById](3120) id=IS_PROXIMITY_TEST_MOTOR_FEEDBACK
03-17 07:10:33.935  1022  1034 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
03-17 07:10:33.935  1022  1034 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-17 07:10:33.935  1022  1034 D InputDispatcher: Focused application set to: xxxx
03-17 07:10:33.935  1022  1034 D InputDispatcher: Focus left window: 1508
03-17 07:10:33.935  1022  1052 D PhoneWindow: *FMB* installDecor mIsFloating : false
03-17 07:10:33.935  1022  1052 D PhoneWindow: *FMB* installDecor flags : -2122120936
03-17 07:10:33.945  3120  3120 D FactoryTestApp: [XMLDataStorage$redefinitionById](3120) id=SUPPORT_GEOMAGNETIC_ALPS_CAL
03-17 07:10:33.945  3075  3075 D AndroidRuntime: Shutting down VM
03-17 07:10:33.945  3120  3120 D FactoryTestApp: [XMLDataStorage$redefinitionById](3120) id=GEOMAGNETIC_IC_POINT
03-17 07:10:33.945  1508  1508 D Launcher.HomeView: onPause
03-17 07:10:33.945  1508  1508 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
03-17 07:10:33.945  1022  1052 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-17 07:10:33.945  1022  1052 D PointerIcon: setMouseCustomIcon IconType is same.101
03-17 07:10:33.945  3120  3120 D FactoryTestApp: [XMLDataStorage$redefinitionById](3120) id=SENSOR_TEST_ACC_BIT
03-17 07:10:33.945  1022  1902 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:33.945  1022  1902 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:33.945  1022  1902 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:33.945  1022  1902 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:33.955  1022  1052 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
03-17 07:10:33.955  1022  1052 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
03-17 07:10:33.955  3120  3120 D FactoryTestApp: [XMLDataStorage$redefinitionById](3120) id=G_VECTOR_SUM_ACC_BIT
03-17 07:10:33.955   257   257 I SurfaceFlinger: id=11 createSurf (1x1),1 flag=404, uhalitest
03-17 07:10:33.955  3120  3120 D FactoryTestApp: [XMLDataStorage$redefinitionById](3120) id=IS_VIBETONZ_UNSUPPORTED
03-17 07:10:33.955  3120  3120 D FactoryTestApp: [XMLDataStorage$redefinitionById](3120) id=AT_GPSSTEST
03-17 07:10:33.955  3120  3120 D FactoryTestApp: [XMLDataStorage$redefinitionById](3120) id=AT_BATTEST_RESET_WHEN_READ
03-17 07:10:33.965  3120  3120 D FactoryTestApp: [XMLDataStorage$redefinitionById](3120) id=SUPPORT_CHARGE_COUNT
03-17 07:10:33.965  3146  3146 I libpersona: KNOX_SDCARD checking this for 10167
03-17 07:10:33.965  3146  3146 E Zygote  : MountEmulatedStorage()
03-17 07:10:33.965  3146  3146 I libpersona: KNOX_SDCARD not a persona
03-17 07:10:33.965  3146  3146 E Zygote  : v2
03-17 07:10:33.965  3146  3146 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 07:10:33.965  3120  3120 D FactoryTestApp: [XMLDataStorage$redefinitionById](3120) id=PA0_TEMP_ADC
03-17 07:10:33.965  1022  1902 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3146 uid=10167 gids={50167, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
03-17 07:10:33.965  3120  3120 D FactoryTestApp: [XMLDataStorage$redefinitionById](3120) id=PA1_TEMP_ADC
03-17 07:10:33.965  3120  3120 D FactoryTestApp: [XMLDataStorage$redefinitionById](3120) id=NEED_ACK_FOR_CAMERA_STOP
03-17 07:10:33.965  3146  3146 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 07:10:33.965  3146  3146 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
03-17 07:10:33.965  3120  3120 D FactoryTestApp: [XMLDataStorage$redefinitionById](3120) id=HALL_IC_TEST
03-17 07:10:33.975  3120  3120 D FactoryTestApp: [XMLDataStorage$redefinitionById](3120) id=IS_NEW_TSP_SELFTEST_SYNAPTICS
03-17 07:10:33.975  3120  3120 D FactoryTestApp: [XMLDataStorage$redefinitionById](3120) id=IS_TSP_HOVERING_TEST_SET_EDGE_DEADLOCK
03-17 07:10:33.985  3120  3120 D FactoryTestApp: [XMLDataStorage$redefinitionById](3120) id=READ_TARGET_GEOMAGNETIC
03-17 07:10:33.985  3120  3120 D FactoryTestApp: [XMLDataStorage$redefinitionById](3120) id=SYS_INFO_FONT_SIZE
03-17 07:10:33.985  3120  3120 D FactoryTestApp: [XMLDataStorage$redefinitionById](3120) id=SYS_INFO_MEMORY_SIZE
03-17 07:10:33.985  3120  3120 D FactoryTestApp: [XMLDataStorage$redefinitionById](3120) id=SYS_INFO_MODEL_NAME
03-17 07:10:33.995  3120  3120 D FactoryTestApp: [XMLDataStorage$redefinitionById](3120) id=TSP_NODE_COUNT_WIDTH
03-17 07:10:33.995  2766  2806 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
03-17 07:10:33.995  3120  3120 D FactoryTestApp: [XMLDataStorage$redefinitionById](3120) id=TSP_NODE_COUNT_HEIGHT
03-17 07:10:33.995  1508  1508 V ActivityThread: updateVisibility : ActivityRecord{2264d9c7 token=android.os.BinderProxy@182e1036 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
03-17 07:10:33.995  3120  3120 D FactoryTestApp: [XMLDataStorage$redefinitionById](3120) id=TSP_SELFTEST_SPEC_MAX_MINUS_MIN
03-17 07:10:34.005  3120  3120 D FactoryTestApp: [XMLDataStorage$redefinitionById](3120) id=TSP_SELFTEST_MIN_ZINITIX
03-17 07:10:34.005  3120  3120 D FactoryTestApp: [XMLDataStorage$redefinitionById](3120) id=TSP_SELFTEST_MAX_ZINITIX
03-17 07:10:34.005  3120  3120 D FactoryTestApp: [XMLDataStorage$redefinitionById](3120) id=TOUCH_KEY_SPEC_MIN
03-17 07:10:34.005  3120  3120 D FactoryTestApp: [XMLDataStorage$redefinitionById](3120) id=TOUCH_KEY_SPEC_MAX
03-17 07:10:34.015  3146  3146 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 07:10:34.015  3146  3146 D ActivityThread: Added TimaKeyStore provider
03-17 07:10:34.015  3120  3120 D FactoryTestApp: [XMLDataStorage$redefinitionById](3120) id=BOOTLOADER_VERSION
03-17 07:10:34.015  1022  1507 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
03-17 07:10:34.015  1022  1507 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
03-17 07:10:34.015  3120  3120 D FactoryTestApp: [XMLDataStorage$redefinitionById](3120) id=BATTERY_TEST_MODE
03-17 07:10:34.015  1022  1507 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
03-17 07:10:34.015  2766  2806 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
03-17 07:10:34.015  3120  3120 D FactoryTestApp: [XMLDataStorage$redefinitionById](3120) id=BATTERY_VOLT_AVER
03-17 07:10:34.015  2766  2806 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
03-17 07:10:34.025  1508  1508 D Launcher.HomeView: onStop
03-17 07:10:34.025  2766  2806 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
03-17 07:10:34.025  1508  1508 V ActivityThread: updateVisibility : ActivityRecord{2264d9c7 token=android.os.BinderProxy@182e1036 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
03-17 07:10:34.025  3120  3120 D FactoryTestApp: [XMLDataStorage$redefinitionById](3120) id=BATTERY_VF_OCV
03-17 07:10:34.025  2766  2806 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
03-17 07:10:34.025  2766  2806 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
03-17 07:10:34.025  2766  2806 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
03-17 07:10:34.025  3120  3120 D FactoryTestApp: [XMLDataStorage$redefinitionById](3120) id=PA0_THERMISTER_CELCIUS
03-17 07:10:34.025  2766  2806 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
03-17 07:10:34.025  2766  2806 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(275/xdmExecResumeCase)] Start resumecase for INIT
03-17 07:10:34.025  3120  3120 D FactoryTestApp: [XMLDataStorage$redefinitionById](3120) id=SEC_EXT_THERMISTER_TEMP
03-17 07:10:34.035  2766  2806 I DBG_POLICYDM: [com.policydm.db.XDB(2211/xdbIsAlreadyAgree)] bAgree : true
03-17 07:10:34.035  1022  1050 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
03-17 07:10:34.035  3120  3120 D FactoryTestApp: [XMLDataStorage$redefinitionById](3120) id=PA0_THERMISTER_ADC
03-17 07:10:34.035  1022  1507 D PersonaManager: isKioskContainerExistOnDevice
03-17 07:10:34.035  3120  3120 D FactoryTestApp: [XMLDataStorage$redefinitionById](3120) id=PA1_THERMISTER_ADC
03-17 07:10:34.045  2766  2806 E DBG_POLICYDM: [com.policydm.db.XDBSpdAdp(36/xdbGetSpdDeviceRegister)] Device is Registered
03-17 07:10:34.045  3120  3120 D FactoryTestApp: [XMLDataStorage$redefinitionById](3120) id=PA0_THERMISTER_CELCIUS
03-17 07:10:34.045  3120  3120 D FactoryTestApp: [XMLDataStorage$redefinitionById](3120) id=TSP_COMMAND_CMD
03-17 07:10:34.045  3120  3120 D FactoryTestApp: [XMLDataStorage$redefinitionById](3120) id=TSP_COMMAND_STATUS
03-17 07:10:34.055  3120  3120 D FactoryTestApp: [XMLDataStorage$redefinitionById](3120) id=TSP_COMMAND_RESULT
03-17 07:10:34.055  2766  2806 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
03-17 07:10:34.065  3120  3120 D FactoryTestApp: [XMLDataStorage$redefinitionById](3120) id=PATH_HALLIC_STATE
03-17 07:10:34.065  2766  2806 I DBG_POLICYDM: [com.policydm.db.XDB(2176/xdbGetWaitWifiFlag)] bWaitWifi : false
03-17 07:10:34.065  3120  3120 D FactoryTestApp: [XMLDataStorage$redefinitionById](3120) id=KEY_PRESSED_POWER
03-17 07:10:34.075  3120  3120 D FactoryTestApp: [XMLDataStorage$redefinitionById](3120) id=APCHIP_TEMP_ADC
03-17 07:10:34.075  3120  3120 D FactoryTestApp: [XMLDataStorage$redefinitionById](3120) id=HUMITEMP_THERMISTER_PAM
03-17 07:10:34.075  1508  1508 D Launcher: onTrimMemory. Level: 20
03-17 07:10:34.075  3120  3120 D FactoryTestApp: [XMLDataStorage$redefinitionById](3120) id=HUMITEMP_THERMISTER_BATT
03-17 07:10:34.085  3120  3120 D FactoryTestApp: [XMLDataStorage$redefinitionById](3120) id=HUMITEMP_THERMISTER_BATT_CELCIUS
03-17 07:10:34.085  3120  3120 D FactoryTestApp: [XMLDataStorage$redefinitionById](3120) id=HUMITEMP_THERMISTER_S_HUB_BATT
03-17 07:10:34.085  3120  3120 D FactoryTestApp: [XMLDataStorage$redefinitionById](3120) id=HUMITEMP_THERMISTER_S_HUB_BATT_CELCIUS
03-17 07:10:34.095  3120  3120 D FactoryTestApp: [XMLDataStorage$redefinitionById](3120) id=LPA_MODE_SET
03-17 07:10:34.095  3120  3120 D FactoryTestApp: [XMLDataStorage$redefinitionById](3120) id=GEOMAGNETIC_SENSOR_ADC
03-17 07:10:34.105  3120  3120 D FactoryTestApp: [XMLDataStorage$redefinitionById](3120) id=GEOMAGNETIC_SENSOR_POWER
03-17 07:10:34.105   296   296 E USB_UICC: Timeout! No signal received. Retry num = 30
03-17 07:10:34.105  3120  3120 D FactoryTestApp: [XMLDataStorage$parseAsset](3120) SemiFunctionMenu
03-17 07:10:34.115  3120  3120 D FactoryTestApp: [XMLDataStorage$parseAsset](3120) parseAsset Is Completed
03-17 07:10:34.115   315   315 I ServiceManager: Waiting for service AtCmdFwd...
03-17 07:10:34.115  3120  3120 D FactoryTestApp: [Support$Values.getString](3120) id=EFS_FACTORYAPP_ROOT_PATH, path=/efs/FactoryApp/
03-17 07:10:34.125  3120  3120 D FactoryTestApp: [Support$Values.getString](3120) id=CHIPSET_MANUFACTURE, value=Qualcomm
,03-17 07:10:34.125  3120  3120 I FactoryTestApp: [ModuleCommon$ModuleCommon](3120) Create ModuleCommon
03-17 07:10:34.125  3120  3120 D FactoryTestApp: [Support$Values.getString](3120) id=FACTORY_MODE, path=/efs/FactoryApp/factorymode
03-17 07:10:34.125  3120  3120 D FactoryTestApp: [Support$Kernel.read](3120) path=/efs/FactoryApp/factorymode, value=ON
03-17 07:10:34.125  3120  3120 I FactoryTestApp: [ModuleCommon$readFactoryMode](3120) mode: ON
03-17 07:10:34.135  3120  3120 D FactoryTestApp: [Support$Values.getString](3120) id=KEYSTRING_BLOCK, path=/efs/FactoryApp/keystr
03-17 07:10:34.135  3120  3120 D FactoryTestApp: [FactoryTestBroadcastReceiver$onReceive](3120) KEYSTRING_BLOCK is already existed...
03-17 07:10:34.135  3120  3120 D FactoryTestApp: [Support$Values.getString](3120) id=KEYSTRING_BLOCK, path=/efs/FactoryApp/keystr
03-17 07:10:34.135  3120  3120 D FactoryTestApp: [Support$Values.getBoolean](3120) id=INBATT_SAVE_SOC, value=false
03-17 07:10:34.135  3120  3120 D FactoryTestApp: [Support$Values.getString](3120) id=BINARY_TYPE, key=ro.factory.factory_binary
03-17 07:10:34.135  3120  3120 D FactoryTestApp: [Support$Properties.get](3120) property=ro.factory.factory_binary
03-17 07:10:34.135  3120  3120 D FactoryTestApp: [FactoryTestBroadcastReceiver$onReceive](3120) Boot completed, IS_FACTORY_BINARY = USER MODE
03-17 07:10:34.145  3120  3120 I FactoryTestApp: [ModuleCommon$getFtClientEnableState](3120) result : false
03-17 07:10:34.145  3120  3120 I FactoryTestApp: [ModuleCommon$connectedJIG](3120) ...
03-17 07:10:34.145  3120  3120 D FactoryTestApp: [Support$Values.getString](3120) id=ANYWAY_JIG_CABLE_TYPE, value=ANYWAY_JIG
03-17 07:10:34.145  3120  3120 I FactoryTestApp: [ModuleCommon$connectedJIG](3120) cable_type = ANYWAY_JIG
03-17 07:10:34.145  3120  3120 D FactoryTestApp: [Support$Values.getString](3120) id=ANYWAY_JIG, path=/sys/class/sec/switch/adc
03-17 07:10:34.145  3120  3120 D FactoryTestApp: [Support$Values.getString](3120) id=ANYWAY_JIG, path=/sys/class/sec/switch/adc
03-17 07:10:34.145  3120  3120 D FactoryTestApp: [Support$Kernel.read](3120) path=/sys/class/sec/switch/adc, value=1f
03-17 07:10:34.145  3120  3120 I FactoryTestApp: [ModuleCommon$connectedJIG](3120) value = 1f, JIG_ON = 1C
03-17 07:10:34.145  3120  3120 D FactoryTestApp: [Support$Values.getString](3120) id=MODEL_COMMUNICATION_MODE, value=gsm
03-17 07:10:34.145  3120  3120 I FactoryTestApp: [ModuleCommon$isConnectionModeNone](3120) mConnectionMode = gsm
03-17 07:10:34.145  3120  3120 I FactoryTestApp: [ModuleCommon$isRunningFtClient](3120) RUNNING_FTCLIENT : false
03-17 07:10:34.145  3120  3120 I FactoryTestApp: [FactoryTestBroadcastReceiver$startDummyFtClientForBootCompleted](3120) start DummyFtClient service for APO
03-17 07:10:34.155  3075  3075 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
03-17 07:10:34.155  1022  1520 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:34.155  3120  3120 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.factory.entry.FactoryTestBroadcastReceiver.startDummyFtClientForBootCompleted:345 com.sec.factory.entry.FactoryTestBroadcastReceiver.onReceive:192 
03-17 07:10:34.155  1022  1520 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:34.155  1022  1520 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.factory, destAppInfo.processName = com.sec.factory
03-17 07:10:34.165  3120  3120 D FactoryTest: User mode
03-17 07:10:34.165  3120  3120 I FactoryTestApp: [ModuleCommon$disableFtClient](3120) ...
03-17 07:10:34.175  3120  3120 D FactoryTestApp: [DummyFtClient$onCreate](3120) Create DummyFtClient service
03-17 07:10:34.175  3120  3120 I FactoryTestApp: [XMLDataStorage$parsingXML](3120) FtClient => data parsing was completed.
03-17 07:10:34.175  3120  3120 D FactoryTestApp: [DummyFtClient$onReceive](3120) ACTION_SIM_STATE_CHANGED => XML data parsing was failed.
,03-17 07:10:34.175  3120  3120 D FactoryTestApp: [Support$Values.getString](3120) id=MODEL_COMMUNICATION_MODE, value=gsm
03-17 07:10:34.175  3120  3120 I FactoryTestApp: [ModuleCommon$isConnectionModeNone](3120) mConnectionMode = gsm
,03-17 07:10:34.185  3120  3120 D FactoryTestApp: [Support$Values.getBoolean](3120) id=SUPPORT_AUTO_WAKELOCK, value=false
,03-17 07:10:34.185  3120  3120 D FactoryTestApp: [DummyFtClient$onStartCommand](3120) ...
,03-17 07:10:34.185  1022  1051 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,03-17 07:10:34.185  1022  1051 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,03-17 07:10:34.185  1022  1051 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:34.185  1022  1051 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:34.185  1022  1051 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:34.185  1022  1051 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:34.205  3165  3165 E Zygote  : MountEmulatedStorage(),
03-17 07:10:34.205  3165  3165 I libpersona: KNOX_SDCARD checking this for 1002
03-17 07:10:34.205  3165  3165 E Zygote  : v2
03-17 07:10:34.205  3165  3165 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:34.205  1022  1051 I ActivityManager: Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=3165 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,03-17 07:10:34.205  3165  3165 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 07:10:34.205  3146  3146 I WebViewFactory: Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,03-17 07:10:34.205  3165  3165 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 07:10:34.205  1022  1022 I WifiService: android.intent.action.BOOT_COMPLETED
,03-17 07:10:34.215  3165  3165 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 07:10:34.215  1022  1022 D UsbDeviceManager: boot completed
03-17 07:10:34.215  1022  1049 D UsbDeviceManager: handleMessage -> MSG_BOOT_COMPLETED
03-17 07:10:34.215  3146  3146 I LibraryLoader: Loading: webviewchromium
,03-17 07:10:34.215  1022  1049 D UsbDeviceManager: sending intent : ACTION_USB_CABLE_STATE : connected = true
,03-17 07:10:34.215   296   296 E USB_UICC: Timeout! No signal received. Reach maximum retries!
03-17 07:10:34.215  1022  1049 D UsbDeviceManager: broadcasting Intent { act=android.hardware.usb.action.USB_STATE flg=0x20000000 (has extras) } connected: true configured: true
03-17 07:10:34.215   296   296 E USB_UICC: usb_uicc_init_qmi failed ! 
03-17 07:10:34.215   296   296 I USB_UICC: usb_uicc_cleanup, signal received: 0x3 
03-17 07:10:34.215   296   296 I USB_UICC: usb_uicc_cleanup, Issuing QMI deinit ... 
,03-17 07:10:34.225  3146  3146 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 6345-6349)
03-17 07:10:34.225  3146  3146 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-17 07:10:34.235  1022  3164 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:34.235  1022  3164 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:34.235  1022  3164 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:34.235  1022  3164 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:34.255  3185  3185 E Zygote  : MountEmulatedStorage(),
03-17 07:10:34.255  3185  3185 I libpersona: KNOX_SDCARD checking this for 1000
03-17 07:10:34.255  3185  3185 E Zygote  : v2
03-17 07:10:34.255  3185  3185 I libpersona: KNOX_SDCARD not a persona
03-17 07:10:34.255  3185  3185 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
03-17 07:10:34.255  1022  3164 I ActivityManager: Start proc com.android.keychain for service com.android.keychain/.KeyChainService: pid=3185 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,03-17 07:10:34.255  3185  3185 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
03-17 07:10:34.255  1022  1049 D UsbDeviceManager: sending intent : ACTION_USB_STATE : connected = true, configured = true, functions = mtp,adb
,03-17 07:10:34.265  1206  1206 I KeyguardEffectViewUtil: set resource id
03-17 07:10:34.265  3146  3146 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {f4bc31e}
,03-17 07:10:34.265  3146  3146 I LibraryLoader: Expected native library version number "",actual native library version number ""
03-17 07:10:34.265  3146  3146 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
03-17 07:10:34.265  1022  1035 D SettingsProvider: name = keyguard_default_wallpaper_res_id
03-17 07:10:34.265  1022  1035 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-17 07:10:34.265  1022  1035 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,03-17 07:10:34.265  1022  1035 D SettingsProvider: selectionArgs: false
03-17 07:10:34.265  1022  1035 D SettingsProvider: selectionArgs: 10049
03-17 07:10:34.265  1022  1035 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-17 07:10:34.265  1022  1035 D SettingsProvider: ret = -1
03-17 07:10:34.265  1206  1206 D KeyguardUpdateMonitor: received broadcast android.intent.action.BOOT_COMPLETED
,03-17 07:10:34.265  1206  1206 D KeyguardUpdateMonitor: handleBootCompleted()
03-17 07:10:34.265  1206  1206 D KeyguardUpdateMonitor: handleBootCompleted()
,03-17 07:10:34.265  3165  3165 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:34.265  3165  3165 D ActivityThread: Added TimaKeyStore provider
03-17 07:10:34.275  3185  3185 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 07:10:34.275  1022  1022 I PalmMotion: [PALM] 2014 - SURFACE_MOTION_ENGINE: 1 MOTION_MERGED_MUTE_PAUSE & SURFACE_PALM_TOUCH: 1,
03-17 07:10:34.275  1022  1022 E MotionRecognitionService:   mReceiver.onReceive : ACTION_USER_PRESENT  :: UNLOCK SCREEN
03-17 07:10:34.275  1022  1022 I PalmMotion: [PALM] SURFACE_PALM_SWIPE: 1
03-17 07:10:34.275  1022  1022 D LightsService: [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 1022) 
03-17 07:10:34.275  1022  1022 D PalmMotion: [PALM] SETTINGS : [TOUCH: true] [SWEEP: true]
03-17 07:10:34.275  1022  1022 D LightsService: [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
03-17 07:10:34.275  1022  1022 D PalmMotion: [PALM] ACCEPTED : [a3ulte_common] PALM_CNT : 2, M_TOUCH : 1000.0, M_SWEEP : 100.0, E_SWEEP : 2.0, IGNORE_M_SWEEP : false
,03-17 07:10:34.275  1022  1081 D LightsService: [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
03-17 07:10:34.275  1022  1081 D LightsService: [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,03-17 07:10:34.285  1022  1507 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
,03-17 07:10:34.295  1022  3171 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 07:10:34.295  1022  3171 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 07:10:34.305  3146  3146 I BrowserStartupController: Initializing chromium process, renderers=0
,03-17 07:10:34.305  1471  3199 D NfcService: call the applyRouting
03-17 07:10:34.305  3146  3146 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-17 07:10:34.315  1827  1827 D SamsungIME: showDlgMsgBox : false true true
03-17 07:10:34.315  3185  3185 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:34.315  3185  3185 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:34.325  1022  3171 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 07:10:34.325  1022  3171 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 07:10:34.325  3146  3146 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,03-17 07:10:34.325  3146  3146 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
03-17 07:10:34.325  3165  3165 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
03-17 07:10:34.325  3146  3146 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
03-17 07:10:34.325  3165  3165 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,03-17 07:10:34.335  3146  3210 D BluetoothAdapter: 535390207: getState() :  mService = null. Returning STATE_OFF
,03-17 07:10:34.355  3146  3146 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
03-17 07:10:34.355  3146  3146 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
03-17 07:10:34.355  3146  3146 I Adreno-EGL: Build Date: 04/06/15 Mon
03-17 07:10:34.355  3146  3146 I Adreno-EGL: Local Branch: 
03-17 07:10:34.355  3146  3146 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
03-17 07:10:34.355  3146  3146 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
03-17 07:10:34.355  3146  3146 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,03-17 07:10:34.365  1022  1392 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:34.365  1022  1392 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:34.365  1022  1392 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.contacts, destAppInfo.processName = com.android.contacts
,03-17 07:10:34.375  3185  3200 E File    : fail readDirectory() errno=2
,03-17 07:10:34.375  1022  3213 I RecoverySystem: !@RecoverySystem handleAftermath
,03-17 07:10:34.385  1485  1485 V OtaStartupReceiver: onOtaspChanged: mOtaspMode=1
,03-17 07:10:34.385  3165  3165 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,03-17 07:10:34.385  1022  3213 I RecoverySystem: No recovery log file
,03-17 07:10:34.385  1022  1667 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:34.385  1022  1667 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:34.385  1022  1667 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:34.385  1022  1667 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:34.405  3222  3222 E Zygote  : MountEmulatedStorage()
03-17 07:10:34.405  3222  3222 I libpersona: KNOX_SDCARD checking this for 1001
03-17 07:10:34.405  3222  3222 E Zygote  : v2
03-17 07:10:34.405  3222  3222 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:34.405  3222  3222 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 07:10:34.405  1022  3213 E RecoverySystem: Error copy recovery logs : /cache/recovery/last_last_kernel: open failed: ENOENT (No such file or directory)
03-17 07:10:34.405  1022  3213 E RecoverySystem: Error copy recovery logs : /cache/recovery/last_recovery_contents: open failed: ENOENT (No such file or directory)
03-17 07:10:34.405  1022  3213 E RecoverySystem: Error copy recovery logs : /cache/recovery/last_history: open failed: ENOENT (No such file or directory)
03-17 07:10:34.405  1022  1667 I ActivityManager: Start proc com.sec.phone for broadcast com.sec.phone/.BootCompleteReceiver: pid=3222 uid=1001 gids={41001, 9997, 1007, 1028, 1015, 3002, 3001, 3003, 1035, 1023, 3006} abi=armeabi-v7a
,03-17 07:10:34.405  3222  3222 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 07:10:34.405  3222  3222 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 07:10:34.415  2995  2995 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
03-17 07:10:34.425  3165  3165 D BtSettings.ProfileConfig: Adding GattService
03-17 07:10:34.435  3165  3165 D BtSettings.ProfileConfig: Adding HeadsetService
03-17 07:10:34.435  3165  3165 D BtSettings.ProfileConfig: Adding A2dpService
03-17 07:10:34.435  3165  3165 D BtSettings.ProfileConfig: Adding HidService
03-17 07:10:34.435  3165  3165 D BtSettings.ProfileConfig: Adding HealthService
03-17 07:10:34.435  3165  3165 D BtSettings.ProfileConfig: Adding PanService
03-17 07:10:34.435  3165  3165 D BtSettings.ProfileConfig: Adding BluetoothMapService
03-17 07:10:34.435  3165  3165 D BtSettings.ProfileConfig: Adding SapService
03-17 07:10:34.435  3165  3165 D BtSettings.ProfileConfig: Adding HeadsetClientService
03-17 07:10:34.435  3165  3165 D BtSettings.ProfileConfig: Adding A2dpSinkService
03-17 07:10:34.435  3165  3165 D BtSettings.ProfileConfig: Adding SapClientService
03-17 07:10:34.435  3165  3165 D BtSettings.ProfileConfig: Adding HidDevService
,03-17 07:10:34.435  3165  3165 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,03-17 07:10:34.445  1022  1902 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:34.445  1022  1902 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:34.445  1022  1902 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,03-17 07:10:34.445  1022  1520 I ActivityManager: Killing 2580:com.sec.android.app.camera/u0a135 (adj 15): empty #31
,03-17 07:10:34.455  1022  1659 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
03-17 07:10:34.455  1022  1659 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-17 07:10:34.455  1022  1659 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-17 07:10:34.455  1022  1659 D SettingsProvider: selectionArgs: false
03-17 07:10:34.455  1022  1659 D SettingsProvider: selectionArgs: 1002
03-17 07:10:34.455  1022  1659 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-17 07:10:34.455  1022  1659 D SettingsProvider: ret = -1
,03-17 07:10:34.485  1022  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:34.485  1022  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:34.485  1022  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:34.485  1022  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:34.495  1022  1659 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,03-17 07:10:34.495  3243  3243 E Zygote  : MountEmulatedStorage()
,03-17 07:10:34.495  3243  3243 E Zygote  : v2
03-17 07:10:34.495  3243  3243 I libpersona: KNOX_SDCARD checking this for 10039
03-17 07:10:34.495  3222  3222 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 07:10:34.495  3243  3243 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:34.495  3243  3243 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 07:10:34.495  3222  3222 D ActivityThread: Added TimaKeyStore provider
03-17 07:10:34.505  1022  1520 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
03-17 07:10:34.505  1022  1520 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-17 07:10:34.505  1022  1520 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-17 07:10:34.505  1022  1520 D SettingsProvider: selectionArgs: false
03-17 07:10:34.505  1022  1520 D SettingsProvider: selectionArgs: 1002
03-17 07:10:34.505  1022  1520 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-17 07:10:34.505  1022  1520 D SettingsProvider: ret = -1
,03-17 07:10:34.505  3243  3243 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 07:10:34.505  3243  3243 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 07:10:34.505   257   450 I SurfaceFlinger: id=9 Removed Mauncher (5/8),
03-17 07:10:34.505   257  3162 I SurfaceFlinger: id=9 Removed Mauncher (-2/8)
,03-17 07:10:34.515  1022  1046 I ActivityManager: Start proc com.sec.android.gallery3d for service com.sec.android.gallery3d/.remote.picasa.PicasaService: pid=3243 uid=10039 gids={50039, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,03-17 07:10:34.515  1022  1520 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,03-17 07:10:34.525  1022  1034 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
,03-17 07:10:34.525  1022  1034 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,03-17 07:10:34.525  1022  1034 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-17 07:10:34.525  1022  1034 D SettingsProvider: selectionArgs: false
03-17 07:10:34.525  1022  1034 D SettingsProvider: selectionArgs: 1002
03-17 07:10:34.525  1022  1034 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-17 07:10:34.525  1022  1034 D SettingsProvider: ret = -1
,03-17 07:10:34.535  1206  1206 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 07:10:34.555  1022  1034 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,03-17 07:10:34.555  1022  1902 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
03-17 07:10:34.555  1022  1902 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-17 07:10:34.555  1022  1902 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-17 07:10:34.555  1022  1902 D SettingsProvider: selectionArgs: false
03-17 07:10:34.555  1022  1902 D SettingsProvider: selectionArgs: 1002
03-17 07:10:34.555  1022  1902 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-17 07:10:34.555  1022  1902 D SettingsProvider: ret = -1
03-17 07:10:34.555  3243  3243 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:34.555  1206  1206 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
03-17 07:10:34.555  3243  3243 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:34.565  1022  3171 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,03-17 07:10:34.565  1022  1902 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,03-17 07:10:34.575  3146  3218 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,03-17 07:10:34.575  3222  3222 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,03-17 07:10:34.575  1022  3171 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 07:10:34.575  1206  1206 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 07:10:34.585  3146  3146 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,03-17 07:10:34.585  1022  1034 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
03-17 07:10:34.585  1022  1034 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-17 07:10:34.585  1022  1034 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,03-17 07:10:34.585  1022  1034 D SettingsProvider: selectionArgs: false
03-17 07:10:34.585  1022  1034 D SettingsProvider: selectionArgs: 1002
03-17 07:10:34.585  1022  1034 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-17 07:10:34.585  1022  1034 D SettingsProvider: ret = -1
,03-17 07:10:34.585  1022  3171 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 07:10:34.585  1206  1206 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 07:10:34.595  1022  3213 D Reset_Reason: resetString = NPON
,03-17 07:10:34.595  1022  1034 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,03-17 07:10:34.595  3243  3243 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,03-17 07:10:34.595  3243  3243 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-17 07:10:34.595  3243  3243 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 07:10:34.595  3243  3243 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,03-17 07:10:34.595  3243  3243 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
03-17 07:10:34.595  3243  3243 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
03-17 07:10:34.595  3243  3243 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,03-17 07:10:34.605  1206  1206 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 07:10:34.605  1022  1034 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
03-17 07:10:34.605  1022  1034 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-17 07:10:34.605  1022  1034 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-17 07:10:34.605  1022  1034 D SettingsProvider: selectionArgs: false
03-17 07:10:34.605  1022  1034 D SettingsProvider: selectionArgs: 1002
03-17 07:10:34.605  1022  1034 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-17 07:10:34.605  1022  1034 D SettingsProvider: ret = -1
,03-17 07:10:34.615  1022  3213 I BootReceiver: Copying audit failures to DropBox
,03-17 07:10:34.625  1022  3213 I BootReceiver: Checking for fsck errors
,03-17 07:10:34.635  1022  1034 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,03-17 07:10:34.635  1022  3213 I BootReceiver: Copying /data/tombstones/tombstone_00 to DropBox (SYSTEM_TOMBSTONE)
,03-17 07:10:34.645  3146  3146 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-17 07:10:34.655  3146  3146 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,03-17 07:10:34.655  1022  1597 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
03-17 07:10:34.655  1022  1597 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,03-17 07:10:34.655  1022  1597 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-17 07:10:34.655  1022  3263 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
,03-17 07:10:34.655  1022  1597 D SettingsProvider: selectionArgs: false
03-17 07:10:34.655  1022  1597 D SettingsProvider: selectionArgs: 1002
03-17 07:10:34.655  1022  1597 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-17 07:10:34.655  1022  1597 D SettingsProvider: ret = -1
,03-17 07:10:34.665  1206  1206 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 07:10:34.665  1022  1597 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,03-17 07:10:34.665  1022  1404 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
,03-17 07:10:34.665  1022  1404 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-17 07:10:34.665  1022  1404 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-17 07:10:34.665  1022  1404 D SettingsProvider: selectionArgs: false
03-17 07:10:34.665  1022  1404 D SettingsProvider: selectionArgs: 1002
03-17 07:10:34.665  1022  1404 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,03-17 07:10:34.665  1022  1404 D SettingsProvider: ret = -1
,03-17 07:10:34.675  1022  1404 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,03-17 07:10:34.675  1206  1206 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 07:10:34.685  2697  3265 D DelayedSyncController: Delaying sync.
,03-17 07:10:34.685  1022  3171 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 07:10:34.685  3146  3146 D PhoneWindow: *FMB* installDecor mIsFloating : false
03-17 07:10:34.685  3146  3146 D PhoneWindow: *FMB* installDecor flags : -2139027200
,03-17 07:10:34.685  1206  1206 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 07:10:34.685  1022  1902 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
03-17 07:10:34.685  1022  1046 W libprocessgroup: failed to open /acct/uid_10135/pid_2580/cgroup.procs: No such file or directory
,03-17 07:10:34.695  1022  1902 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-17 07:10:34.695  1022  1902 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-17 07:10:34.695  1022  1902 D SettingsProvider: selectionArgs: false
03-17 07:10:34.695  1022  1902 D SettingsProvider: selectionArgs: 1002
03-17 07:10:34.695  1022  1902 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-17 07:10:34.695  1022  1902 D SettingsProvider: ret = -1
,03-17 07:10:34.695  3146  3146 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,03-17 07:10:34.705  1022  1902 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,03-17 07:10:34.705  1022  1597 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
03-17 07:10:34.705  1022  1597 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-17 07:10:34.705  1022  1597 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-17 07:10:34.705  1022  1597 D SettingsProvider: selectionArgs: false
03-17 07:10:34.705  1022  1597 D SettingsProvider: selectionArgs: 1002
03-17 07:10:34.705  1022  1597 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-17 07:10:34.705  1022  1597 D SettingsProvider: ret = -1
,03-17 07:10:34.715  1022  1597 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=1002
03-17 07:10:34.715  1022  1404 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
03-17 07:10:34.715  1022  1404 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-17 07:10:34.715  1022  1404 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-17 07:10:34.715  1022  1404 D SettingsProvider: selectionArgs: false
03-17 07:10:34.715  1022  1404 D SettingsProvider: selectionArgs: 1002
03-17 07:10:34.715  1022  1404 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-17 07:10:34.715  1022  1404 D SettingsProvider: ret = -1
03-17 07:10:34.715  1022  1392 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:34.715  1022  1392 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:34.715  1022  1392 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.phone, destAppInfo.processName = com.sec.phone
,03-17 07:10:34.725  1206  1206 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 07:10:34.725  1022  1404 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=1002
03-17 07:10:34.725  3146  3146 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-17 07:10:34.725  3146  3146 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-17 07:10:34.735  1022  3171 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-17 07:10:34.735  1022  3171 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-17 07:10:34.735  1022  3171 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-17 07:10:34.745  1022  1321 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
,03-17 07:10:34.745  1022  1321 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-17 07:10:34.745  1022  1321 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-17 07:10:34.745  1022  1321 D SettingsProvider: selectionArgs: false
03-17 07:10:34.745  1022  1321 D SettingsProvider: selectionArgs: 1002
03-17 07:10:34.745  1022  1321 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-17 07:10:34.745  1022  1321 D SettingsProvider: ret = -1
,03-17 07:10:34.745  1022  3263 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
,03-17 07:10:34.745  1022  1321 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,03-17 07:10:34.745  1022  3213 I BootReceiver: Copying /data/tombstones/tombstone_01 to DropBox (SYSTEM_TOMBSTONE)
03-17 07:10:34.745  1022  1035 I art     : Explicit concurrent mark sweep GC freed 29675(1539KB) AllocSpace objects, 6(592KB) LOS objects, 33% free, 22MB/33MB, paused 6.747ms total 292.444ms
,03-17 07:10:34.745  1206  1206 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 07:10:34.775  1206  1206 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 07:10:34.775  1022  3171 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 07:10:34.785  1206  1206 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 07:10:34.805  2141  3277 E ActivityThread: Failed to find provider info for com.android.contacts.metadata
03-17 07:10:34.805  1022  1022 D CrashAnrDetector: Build: samsung/a3ultexx/a3ulte:5.0.2/LRX22G/A300FUXXU1BOEC:user/release-keys
03-17 07:10:34.805  1022  1022 D CrashAnrDetector: Hardware: MSM8916
03-17 07:10:34.805  1022  1022 D CrashAnrDetector: Revision: 1
03-17 07:10:34.805  1022  1022 D CrashAnrDetector: Bootloader: A300FUXXU1BOEC
03-17 07:10:34.805  1022  1022 D CrashAnrDetector: Radio: unknown
03-17 07:10:34.805  1022  1022 D CrashAnrDetector: Kernel: Linux version 3.10.49-4866174 (dpi@SWDD6204) (gcc version 4.8 (GCC) ) #1 SMP PREEMPT Fri May 29 20:06:40 KST 2015
03-17 07:10:34.805  1022  1022 D CrashAnrDetector: 
03-17 07:10:34.805  1022  1022 D CrashAnrDetector: *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
03-17 07:10:34.805  1022  1022 D CrashAnrDetector: Build fingerprint: 'samsung/a3ultexx/a3ulte:5.0.2/LRX22G/A300FUXXU1BOEC:user/release-keys'
03-17 07:10:34.805  1022  1022 D CrashAnrDetector: Revision: '1'
03-17 07:10:34.805  1022  1022 D CrashAnrDetector: ABI: 'arm'
03-17 07:10:34.805  1022  1022 D CrashAnrDetector: pid: 3299, tid: 3630, name: Thread-458  >>> com.test.thalitest <<<
03-17 07:10:34.805  1022  1022 D CrashAnrDetector: signal 11 (SIGSEGV), code 1 (SEGV_MAPERR), fault addr 0x0
03-17 07:10:34.805  1022  1022 D CrashAnrDetector:     r0 00000000  r1 9eaf4734  r2 00000002  r3 00000000
03-17 07:10:34.805  1022  1022 D CrashAnrDetector:     r4 b8f0ab70  r5 00000000  r6 b8f0a400  r7 b9e05d98
03-17 07:10:34.805  1022  1022 D CrashAnrDetector:     r8 b8f41fec  r9 b8f0ab70  sl b8f0a3d8  fp 9eaf472c
03-17 07:10:34.805  1022  1022 D CrashAnrDetector:     ip ffffffff  sp 9eaf471c  lr 9efcfb30  pc 9efcfa34  cpsr 60000010
03-17 07:10:34.805  1022  1022 D CrashAnrDetector:     d0  0000000000000000  d1  0000000000000000
03-17 07:10:34.805  1022  1022 D CrashAnrDetector:     d2  0000000000000000  d3  0000000000000000
03-17 07:10:34.805  1022  1022 D CrashAnrDetector:     d4  0000000000000000  d5  0000000000000000
03-17 07:10:34.805  1022  1022 D CrashAnrDetector:     d6  0000000000000000  d7  0000000000000000
03-17 07:10:34.805  1022  1022 D CrashAnrDetector:     d8  0000000000000000  d9  0000000000000000
03-17 07:10:34.805  1022  1022 D CrashAnrDetector:     d10 0000000000000000  d11 0000000000000000
03-17 07:10:34.805  1022  1022 D CrashAnrDetector:     d12 0000000000000000  d13 0000000000000000
03-17 07:10:34.805  1022  1022 D CrashAnrDetector:     d14 0000000000000000  d15 0000000000000000
03-17 07:10:34.805  1022  1022 D CrashAnrDetector:     d16 000027b7000027b7  d17 000027b700000000
03-17 07:10:34.805  1022  1022 D CrashAnrDetector:     d18 0001000100010001  d19 0001000100010001
03-17 07:10:34.805  1022  1022 D CrashAnrDetector:     d20 0000000100010001  d21 0000000000000000
03-17 07:10:34.805  1022  1022 D CrashAnrDetector:     d22 0000000000000000  d23 0000000000000000
03-17 07:10:34.805  1022  1022 D CrashAnrDetector:     d24 0000000000000000  d25 0000000000000000
03-17 07:10:34.805  1022  1022 D CrashAnrDetector:     d26 0002000100010001  d27 0002000200020002
03-17 07:10:34.805  1022  1022 D CrashAnrDetector:     d28 0080008000800080  d29 0080008000800080
03-17 07:10:34.805  1022  1022 D CrashAnrDetector:     d30 0800080008000800  d31 0800080008000800
03-17 07:10:34.805  1022  1022 D CrashAnrDetector:     scr 20000017
03-17 07:10:34.805  1022  1022 D CrashAnrDetector: 
03-17 07:10:34.805  1022  1022 D CrashAnrDetector: backtrace:
03-17 07:10:34.805  1022  1022 D CrashAnrDetector:     #00 pc 003d1a34  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (bool ThingIsPermanentAtom<JS::Symbol>(JS::Symbol*)+4)
03-17 07:10:34.805  1022  1022 D CrashAnrDetector:     #01 pc 003d1b2c  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so
03-17 07:10:34.805  1022  1022 D CrashAnrDetector:     #02 pc e5943000  <unknown>
03-17 07:10:34.805  1022  1022 D CrashAnrDetector: 
03-17 07:10:34.805  1022  1022 D CrashAnrDetector: stack:
03-17 07:10:34.805,  1022  1022 D CrashAnrDetector:          9eaf469c  00000000  
03-17 07:10:34.805  1022  1022 D CrashAnrDetector:          9eaf46a0  b9259cb0  [heap]
03-17 07:10:34.805  1022  1022 D CrashAnrDetector:          9eaf46a4  b8f0ab70  [heap]
03-17 07:10:34.805  1022  1022 D CrashAnrDetector:          9eaf46a8  0000000b  
03-17 07:10:34.805  1022  1022 D CrashAnrDetector:          9eaf46ac  b9259670  [heap]
03-17 07:10:34.805  1022  1022 D CrashAnrDetector:          9eaf46b0  9eaf46cc  [stack:3630]
03-17 07:10:34.805  1022  1022 D CrashAnrDetector:          9eaf46b4  9f043904  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (js::jit::BaselineScript::trace(JSTracer*)+120)
03-17 07:10:34.805  1022  1022 D CrashAnrDetector:          9eaf46b8  00000001  
03-17 07:10:34.805  1022  1022 D CrashAnrDetector:          9eaf46bc  00000000  
03-17 07:10:34.805  1022  1022 D CrashAnrDetector:          9eaf46c0  b8f0b6a0  [heap]
03-17 07:10:34.805  1022  1022 D CrashAnrDetector:          9eaf46c4  00000000  
03-17 07:10:34.805  1022  1022 D CrashAnrDetector:          9eaf46c8  00000000  
03-17 07:10:34.805  1022  1022 D CrashAnrDetector:          9eaf46cc  b8f0ab70  [heap]
03-17 07:10:34.805  1022  1022 D CrashAnrDetector:          9eaf46d0  b8f0b6a0  [heap]
03-17 07:10:34.805  1022  1022 D CrashAnrDetector:          9eaf46d4  9f65bb60  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so
03-17 07:10:34.805  1022  1022 D CrashAnrDetector:          9eaf46d8  9eaf4744  [stack:3630]
03-17 07:10:34.805  1022  1022 D CrashAnrDetector:          9eaf46dc  9efd6514  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (js::gc::GCRuntime::markConservativeStackRoots(JSTracer*, bool)+1308)
03-17 07:10:34.805  1022  1022 D CrashAnrDetector:          9eaf46e0  b8f0ab70  [heap]
03-17 07:10:34.805  1022  1022 D CrashAnrDetector:          9eaf46e4  b8f0a3d8  [heap]
03-17 07:10:34.805  1022  1022 D CrashAnrDetector:          9eaf46e8  9eafa000  
03-17 07:10:34.805  1022  1022 D CrashAnrDetector:          9eaf46ec  9eaf4710  [stack:3630]
03-17 07:10:34.805  1022  1022 D CrashAnrDetector:          9eaf46f0  9eaf4708  [stack:3630]
03-17 07:10:34.805  1022  1022 D CrashAnrDetector:          9eaf46f4  9eaf4714  [stack:3630]
03-17 07:10:34.805  1022  1022 D CrashAnrDetector:          9eaf46f8  9f5826d4  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so
03-17 07:10:34.805  1022  1022 D CrashAnrDetector:          9eaf46fc  9eaf4718  [stack:3630]
03-17 07:10:34.805  1022  1022 D CrashAnrDetector:          9eaf4700  00000004  
03-17 07:10:34.805  1022  1022 D CrashAnrDetector:          9eaf4704  00000000  
03-17 07:10:34.805  1022  1022 D CrashAnrDetector:          9eaf4708  00000001  
03-17 07:10:34.805  1022  1022 D CrashAnrDetector:          9eaf470c  b8f0ab70  [heap]
03-17 07:10:34.805  1022  1022 D CrashAnrDetector:          9eaf4710  9252f640  [anon:js-gc-heap]
03-17 07:10:34.805  1022  1022 D CrashAnrDetector:          9eaf4714  b8f0a400  [heap]
03-17 07:10:34.805  1022  1022 D CrashAnrDetector:          9eaf4718  9eaf472c  [stack:3630]
03-17 07:10:34.805  1022  1022 D CrashAnrDetector:     #00  9eaf471c  9eaf472c  [stack:3630]
03-17 07:10:34.805  1022  1022 D CrashAnrDetector:          9eaf4720  9eaf9838  [stack:3630]
03-17 07:10:34.805  1022  1022 D CrashAnrDetector:          9eaf4724  b9e01490  [heap]
03-17 07:10:34.805  1022  1022 D CrashAnrDetector:          9eaf4728  9eaf4744  [stack:3630]
03-17 07:10:34.805  1022  1022 D CrashAnrDetector:          9eaf472c  9efd306c  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (js::gc::MarkValueRoot(JSTracer*, JS::Value*, char const*)+80)
03-17 07:10:34.805  1022  1022 D CrashAnrDetector:     #01  9eaf4730  b8f41fec  [heap]
03-17 07:10:34.805  1022  1022 D CrashAnrDetector:          9eaf4734  00000000  
03-17 07:10:34.805  1022  1022 D CrashAnrDetector:          9eaf4738  b8f0a3fc  [heap]
03-17 07:10:34.805  1022  1022 D CrashAnrDetector:          9eaf473c  9f503cd8  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so
03-17 07:10:34.805  1022  1022 D CrashAnrDetector:          9eaf4740  9eaf479c  [stack:3630]
03-17 07:10:34.805  1022  1022 D CrashAnrDetector:          9eaf4744  9efd7dcc  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (js::gc::GCRuntime::markRuntime(JSTracer*, js::gc::GCRuntime::TraceOrMarkRuntime, js::gc::GCRuntime::TraceRootsOrUsedSaved)+1452)
03-17 07:10:34.805  1022  1022 D CrashAnrDetector:          9eaf4748  00000000  
03-17 07:10:34.805  1022  1022 D CrashAnrDetector:          
03-17 07:10:34.805  1022  1022 D CrashAnrDetector: processName:com.test.thalitest
03-17 07:10:34.805  1022  1022 D CrashAnrDetector: broadcastEvent : com.test.thalitest SYSTEM_TOMBSTONE
03-17 07:10:34.805  1022  1047 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:34.805  1022  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:34.805  1022  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.phone, destAppInfo.processName = com.sec.factory
03-17 07:10:34.805  3120  3120 D FactoryTestApp: [ProtectedFactoryTestBroadcastReceiver$onReceive](3120) onReceive action=com.samsung.intent.action.SECPHONE_READY
03-17 07:10:34.805  3120  3120 I FactoryTestApp: [ProtectedFactoryTestBroadcastReceiver$onReceive](3120) com.samsung.intent.action.SECPHONE_READY
03-17 07:10:34.815  3120  3120 D FactoryTest: User mode
03-17 07:10:34.815  1022  1046 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 24945, reason: UserStart, SyncResult: databaseError: true stats []
03-17 07:10:34.815  1022  1046 D SyncManager: not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 69283, reason: UserStart
03-17 07:10:34.825  3146  3278 D OpenGLRenderer: Render dirty regions requested: true
03-17 07:10:34.825  3243  3243 D NearbySource: Nearby Source Create!
03-17 07:10:34.825  3243  3243 D NearbyContext: Nearby Context Create!
03-17 07:10:34.835  1022  1659 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
03-17 07:10:34.835  1022  1659 D KnoxTimeoutHandler: postActiveUserChange for user 0
03-17 07:10:34.835  1022  1659 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
03-17 07:10:34.845  1022  1022 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 com.android.server.analytics.data.collection.application.CrashAnrDetector.broadcastEvent:296 com.android.server.analytics.data.collection.application.CrashAnrDetector.processDropBoxEntry:254 com.android.server.analytics.data.collection.application.CrashAnrDetector.access$100:60 com.android.server.analytics.data.collection.application.CrashAnrDetector$1.onReceive:102 
03-17 07:10:34.845  1022  1022 D KnoxTimeoutHandler: handleActiveUserChange for user 0
03-17 07:10:34.845  1022  1022 D PersonaManagerService: getPersonasForUser(): returning null!
03-17 07:10:34.845  3146  3146 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
03-17 07:10:34.845  3146  3146 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,03-17 07:10:34.855   256   518 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
03-17 07:10:34.855   256   518 W Vold    : Returning OperationFailed - no handler for errno 0
03-17 07:10:34.855  3243  3243 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
03-17 07:10:34.855  3243  3243 D SLinkSource: Samsung link source created
03-17 07:10:34.875  1206  1206 D StatusBar.NetworkController: refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-17 07:10:34.875  1206  1206 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-17 07:10:34.875  1206  1206 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 07:10:34.875  1206  1206 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 07:10:34.875  1206  1206 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 07:10:34.875  1206  1206 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 07:10:34.895  3243  3283 D ContactProvider: getAllContactInfoList Start
,03-17 07:10:34.895  1022  1507 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,03-17 07:10:34.895  1022  1392 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
03-17 07:10:34.895  1022  1392 D SecContentProvider2: mCursor = null
,03-17 07:10:34.905  1022  1597 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,03-17 07:10:34.925  3243  3283 D ContactProvider: getAllContactInfoList End
,03-17 07:10:34.925  3243  3283 I syncContacts: thread: 433, sync time = 46
,03-17 07:10:34.945  2424  2424 D Mms/NotificationReceiver: MMS NotificationReceiver onReceive: android.intent.action.BOOT_COMPLETED
,03-17 07:10:34.945  2424  2424 D Mms/NotificationReceiver: handleBootCompleted
,03-17 07:10:34.945  3165  3165 D BluetoothAdapterState: make
,03-17 07:10:34.945   257   257 I SurfaceFlinger: id=12 createSurf (1x1),1 flag=404, NainActivit
,03-17 07:10:34.955  2424  2424 D Mms/RcsOwnCapsManager: queue Uri = content://im/queue-messages?box=pending
,03-17 07:10:34.955  1022  3213 I BootReceiver: Copying /data/tombstones/tombstone_02 to DropBox (SYSTEM_TOMBSTONE)
,03-17 07:10:34.955  1022  3263 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
,03-17 07:10:34.955  1485  1505 D TP/ImProvider: im query match24
03-17 07:10:34.955  1485  1505 D TP/ImProvider: URI_IM_QUEUED_MESSAGES
03-17 07:10:34.955  1485  1505 D TP/ImProvider: ftSesstionId must be a long.
03-17 07:10:34.955  1485  1505 D TP/ImProvider: getQueuedImMessages
,03-17 07:10:34.955  1485  1505 D TP/ImProvider: uriString = SELECT ft._id as _id, ft.session_id as session_id, ft.chat_session_id as chat_session_id, thread_id, 'ft' as transport_type, address as recipients, ft.type as type, ft.status as status, ft.service_type as service_type, ft.ext_info as ext_info FROM ft LEFT JOIN im_threads ON ft.thread_id=im_threads.normal_thread_id WHERE ft.hidden=0 AND type=1 AND (status=1 or status=2) UNION SELECT ft._id as _id, ft.session_id as session_id, ft.chat_session_id as chat_session_id, thread_id, 'ft' as transport_type, address as recipients, ft.type as type, ft.status as status, ft.service_type as service_type, ft.ext_info as ext_info FROM ft LEFT JOIN im_threads ON ft.thread_id=im_threads.normal_thread_id WHERE ft.hidden=0 AND type=4 AND (status!=4 AND status!=12) UNION SELECT ft._id as _id, ft.session_id as session_id, ft.chat_session_id as chat_session_id, thread_id, 'ft' as transport_type, address as recipients, ft.type as type, ft.status as status, ft.service_type as service_type, ft.ext_info as ext_info FROM ft LEFT JOIN im_threads ON ft.thread_id=im_threads.normal_thread_id WHERE ft.hidden=0 AND type=6 UNION SELECT im._id as _id, im.session_id as session_id, null as chat_session_id, thread_id, 'chat' as transport_type, address as recipients, im.type as type, im.status as status, im.service_type as service_type, im.ext_info as ext_info FROM im LEFT JOIN im_threads ON im.thread_id=im_threads.normal_thread_id WHERE im.hidden=0 AND type=4 UNION SELECT im._id as _id, im.session_id as session_id, null as chat_session_id, thread_id, 'chat' as transport_type, address as recipients, im.type as type, im.status as status, im.service_type as service_type, im.ext_info as ext_info FROM im LEFT JOIN im_threads ON im.thread_id=im_threads.normal_thread_id WHERE im.hidden=0 AND type=6
,03-17 07:10:34.955  1485  1505 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-17 07:10:34.955  1485  1505 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-17 07:10:34.955  1485  1505 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-17 07:10:34.955  1485  1505 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-17 07:10:34.955  1485  1505 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
,03-17 07:10:34.955  3165  3165 I bluedroid: init
03-17 07:10:34.955  3165  3285 I BluetoothAdapterState: Entering OffState
,03-17 07:10:34.965  1022  1597 D InputDispatcher: Focus entered window: 3146
,03-17 07:10:34.965  3165  3165 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,03-17 07:10:34.965  3165  3165 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
03-17 07:10:34.965  3165  3165 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
03-17 07:10:34.965  3165  3165 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,03-17 07:10:34.975  1022  3171 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 07:10:34.975  1022  1052 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-17 07:10:34.975  1022  1052 D PointerIcon: setMouseCustomIcon IconType is same.101
,03-17 07:10:34.975  3146  3146 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
03-17 07:10:34.975  3146  3278 I OpenGLRenderer: Initialized EGL, version 1.4
,03-17 07:10:34.975  1022  3171 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 07:10:34.975  2424  2424 D Mms/NotificationReceiver:  getPendingMessageIds: no pending messages.
03-17 07:10:34.975  2424  2424 D Mms/ActionsFactory: Call to GET_LAST_MESSAGES_SENT
,03-17 07:10:34.975  1022  1321 W ActivityManager: Unable to start service Intent { act=com.samsung.rcs.framework.instantmessaging.action.GET_LAST_MESSAGES_SENT cat=[com.samsung.rcs.framework.instantmessaging.category.ACTION] pkg=com.sec.ims.android (has extras) } U=0: not found
,03-17 07:10:34.985  3146  3278 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
03-17 07:10:34.985  3146  3278 D OpenGLRenderer: Enabling debug mode 0
,03-17 07:10:34.995  3165  3165 E bt-btif : btif_fetch_local_ble_random_bdaddr
03-17 07:10:34.995  3165  3165 I bluedroid: get_profile_interface socket
03-17 07:10:34.995  3165  3165 I bluedroid: get_profile_interface map_client
,03-17 07:10:34.995  1022  1022 D CrashAnrDetector: Build: samsung/a3ultexx/a3ulte:5.0.2/LRX22G/A300FUXXU1BOEC:user/release-keys
03-17 07:10:34.995  1022  1022 D CrashAnrDetector: Hardware: MSM8916
03-17 07:10:34.995  1022  1022 D CrashAnrDetector: Revision: 1
03-17 07:10:34.995  1022  1022 D CrashAnrDetector: Bootloader: A300FUXXU1BOEC
03-17 07:10:34.995  1022  1022 D CrashAnrDetector: Radio: unknown
03-17 07:10:34.995  1022  1022 D CrashAnrDetector: Kernel: Linux version 3.10.49-4866174 (dpi@SWDD6204) (gcc version 4.8 (GCC) ) #1 SMP PREEMPT Fri May 29 20:06:40 KST 2015
03-17 07:10:34.995  1022  1022 D CrashAnrDetector: 
03-17 07:10:34.995  1022  1022 D CrashAnrDetector: *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
03-17 07:10:34.995  1022  1022 D CrashAnrDetector: Build fingerprint: 'samsung/a3ultexx/a3ulte:5.0.2/LRX22G/A300FUXXU1BOEC:user/release-keys'
03-17 07:10:34.995  1022  1022 D CrashAnrDetector: Revision: '1'
03-17 07:10:34.995  1022  1022 D CrashAnrDetector: ABI: 'arm'
03-17 07:10:34.995  1022  1022 D CrashAnrDetector: pid: 5627, tid: 6272, name: Thread-956  >>> com.test.thalitest <<<
03-17 07:10:34.995  1022  1022 D CrashAnrDetector: signal 11 (SIGSEGV), code 2 (SEGV_ACCERR), fault addr 0x9d40bff0
03-17 07:10:34.995  1022  1022 D CrashAnrDetector:     r0 703224a8  r1 728378f8  r2 12d40cc0  r3 134181a0
03-17 07:10:34.995  1022  1022 D CrashAnrDetector:     r4 000000c2  r5 703224a8  r6 728378f8  r7 134181a0
03-17 07:10:34.995  1022  1022 D CrashAnrDetector:     r8 728378a0  r9 ba06ac88  sl 12d40cc0  fp 9d50d8a8
03-17 07:10:34.995  1022  1022 D CrashAnrDetector:     ip 9d40bff0  sp 9d40dff0  lr 7541f389  pc 7541f30c  cpsr a00f0030
03-17 07:10:34.995  1022  1022 D CrashAnrDetector:     d0  12d40cc0728378a0  d1  0073002000650081
03-17 07:10:34.995  1022  1022 D CrashAnrDetector:     d2  c0c0c0c0c0c0c041  d3  0102020202020213
03-17 07:10:34.995  1022  1022 D CrashAnrDetector:     d4  0040404040404040  d5  0004000400040004
03-17 07:10:34.995  1022  1022 D CrashAnrDetector:     d6  0000000000000000  d7  0003000400040004
03-17 07:10:34.995  1022  1022 D CrashAnrDetector:     d8  0000000000000000  d9  0000000000000000
03-17 07:10:34.995  1022  1022 D CrashAnrDetector:     d10 0000000000000000  d11 0000000000000000
03-17 07:10:34.995  1022  1022 D CrashAnrDetector:     d12 0000000000000000  d13 0000000000000000
03-17 07:10:34.995  1022  1022 D CrashAnrDetector:     d14 0000000000000000  d15 0000000000000000
03-17 07:10:34.995  1022  1022 D CrashAnrDetector:     d16 0000000000000000  d17 7320656d69746e75
03-17 07:10:34.995  1022  1022 D CrashAnrDetector:     d18 0069007200750064  d19 007200200067006e
03-17 07:10:34.995  1022  1022 D CrashAnrDetector:     d20 0101010101010101  d21 0101010101010101
03-17 07:10:34.995  1022  1022 D CrashAnrDetector:     d22 8080808080808080  d23 8080808080808080
03-17 07:10:34.995  1022  1022 D CrashAnrDetector:     d24 4000404040404040  d25 0040404040404040
03-17 07:10:34.995  1022  1022 D CrashAnrDetector:     d26 0f0f0f0f0f0f0f0f  d27 0f0f0f0f0f0f0f0f
03-17 07:10:34.995  1022  1022 D CrashAnrDetector:     d28 0101010101010101  d29 0101010101010101
03-17 07:10:34.995  1022  1022 D CrashAnrDetector:     d30 0000000000000000  d31 0000000000000000
03-17 07:10:34.995  1022  1022 D CrashAnrDetector:     scr 20000013
03-17 07:10:34.995  1022  1022 D CrashAnrDetector: 
03-17 07:10:34.995  1022  1022 D CrashAnrDetector: backtrace:
03-17 07:10:34.995  1022  1022 D CrashAnrDetector:     #00 pc 0009230c  /system/framework/arm/boot.oat
03-17 07:10:34.995  1022  1022 D CrashAnrDetector:     #01 pc 00092387  /system/framework/arm/boot.oat
03-17 07:10:34.995  1022  1022 D CrashAnrDetector: 
03-17 07:10:34.995  1022  1022 D CrashAnrDetector: stack:
03-17 07:10:34.995  1022  1022 D CrashAnrDetector:          9d40df70  00000000  
03-17 07:10:34.995  1022  1022 D CrashAnrDetector:          9d40df74  00000000  
03-17 07:10:34.995  1022  1022 D CrashAnrDetector:          9d40df78  00000000  
03-17 07:10:34.995  1022  1022 D CrashAnrDetector:        ,  9d40df7c  00000000  
03-17 07:10:34.995  1022  1022 D CrashAnrDetector:          9d40df80  00000000  
03-17 07:10:34.995  1022  1022 D CrashAnrDetector:          9d40df84  00000000  
03-17 07:10:34.995  1022  1022 D CrashAnrDetector:          9d40df88  00000000  
03-17 07:10:34.995  1022  1022 D CrashAnrDetector:          9d40df8c  00000000  
03-17 07:10:34.995  1022  1022 D CrashAnrDetector:          9d40df90  00000000  
03-17 07:10:34.995  1022  1022 D CrashAnrDetector:          9d40df94  00000000  
03-17 07:10:34.995  1022  1022 D CrashAnrDetector:          9d40df98  00000000  
03-17 07:10:34.995  1022  1022 D CrashAnrDetector:          9d40df9c  00000000  
03-17 07:10:34.995  1022  1022 D CrashAnrDetector:          9d40dfa0  00000000  
03-17 07:10:34.995  1022  1022 D CrashAnrDetector:          9d40dfa4  00000000  
03-17 07:10:34.995  1022  1022 D CrashAnrDetector:          9d40dfa8  00000000  
03-17 07:10:34.995  1022  1022 D CrashAnrDetector:          9d40dfac  00000000  
03-17 07:10:34.995  1022  1022 D CrashAnrDetector:          9d40dfb0  00000000  
03-17 07:10:34.995  1022  1022 D CrashAnrDetector:          9d40dfb4  00000000  
03-17 07:10:34.995  1022  1022 D CrashAnrDetector:          9d40dfb8  00000000  
03-17 07:10:34.995  1022  1022 D CrashAnrDetector:          9d40dfbc  00000000  
03-17 07:10:34.995  1022  1022 D CrashAnrDetector:          9d40dfc0  00000000  
03-17 07:10:34.995  1022  1022 D CrashAnrDetector:          9d40dfc4  00000000  
03-17 07:10:34.995  1022  1022 D CrashAnrDetector:          9d40dfc8  00000000  
03-17 07:10:34.995  1022  1022 D CrashAnrDetector:          9d40dfcc  00000000  
03-17 07:10:34.995  1022  1022 D CrashAnrDetector:          9d40dfd0  7030fc38  /data/dalvik-cache/arm/system@framework@boot.art
03-17 07:10:34.995  1022  1022 D CrashAnrDetector:          9d40dfd4  00000000  
03-17 07:10:34.995  1022  1022 D CrashAnrDetector:          9d40dfd8  00000000  
03-17 07:10:34.995  1022  1022 D CrashAnrDetector:          9d40dfdc  00000000  
03-17 07:10:34.995  1022  1022 D CrashAnrDetector:          9d40dfe0  00000000  
03-17 07:10:34.995  1022  1022 D CrashAnrDetector:          9d40dfe4  703224a8  /data/dalvik-cache/arm/system@framework@boot.art
03-17 07:10:34.995  1022  1022 D CrashAnrDetector:          9d40dfe8  e3a070ad  
03-17 07:10:34.995  1022  1022 D CrashAnrDetector:          9d40dfec  ef9000ad  
03-17 07:10:34.995  1022  1022 D CrashAnrDetector:     #00  9d40dff0  703224a8  /data/dalvik-cache/arm/system@framework@boot.art
03-17 07:10:34.995  1022  1022 D CrashAnrDetector:          ........  ........
03-17 07:10:34.995  1022  1022 D CrashAnrDetector:     #01  9d40dff0  703224a8  /data/dalvik-cache/arm/system@framework@boot.art
03-17 07:10:34.995  1022  1022 D CrashAnrDetector:          9d40dff4  00000000  
03-17 07:10:34.995  1022  1022 D CrashAnrDetector:          9d40dff8  00000000  
03-17 07:10:34.995  1022  1022 D CrashAnrDetector:          9d40dffc  00000000  
03-17 07:10:34.995  1022  1022 D CrashAnrDetector:          9d40e000  00000000  
03-17 07:10:34.995  1022  1022 D CrashAnrDetector:          9d40e004  00000000  
03-17 07:10:34.995  1022  1022 D CrashAnrDetector:          9d40e008  703224a8  /data/dalvik-cache/arm/system@framework@boot.art
03-17 07:10:34.995  1022  1022 D CrashAnrDetector:          9d40e00c  728378a0  /data/dalvik-cache/arm/system@framework@boot.art
03-17 07:10:34.995  1022  1022 D CrashAnrDetector:          9d40e010  134181a0  /dev/ashmem/dalvik-main space (deleted)
03-17 07:10:34.995  1022  1022 D CrashAnrDetector:          9d40e014  728378f8  /data/dalvik-cache/arm/system@framework@boot.art
03-17 07:10:34.995  1022  1022 D CrashAnrDetector:          9d40e018  12d40cc0  /dev/ashmem/dalvik-main space (deleted)
03-17 07:10:34.995  1022  1022 D CrashAnrDetector:          9d40e01c  7541f33d  /system/framework/arm/boot.oat
03-17 07:10:34.995  1022  1022 D CrashAnrDetector:          9d40e020  703224a8  /data/dalvik-cache/arm/system@framework@boot.art
03-17 07:10:34.995  1022  1022 D CrashAnrDetector:      ,    9d40e024  00000000  
03-17 07:10:34.995  1022  1022 D CrashAnrDetector:          9d40e028  00000000  
03-17 07:10:34.995  1022  1022 D CrashAnrDetector:          9d40e02c  00000000  
03-17 07:10:34.995  1022  1022 D CrashAnrDetector:          9d40e030  7030fc38  /data/dalvik-cache/arm/system@framework@boot.art
03-17 07:10:34.995  1022  1022 D CrashAnrDetector:          9d40e034  00000000  
03-17 07:10:34.995  1022  1022 D CrashAnrDetector:          9d40e038  703224a8  /data/dalvik-cache/arm/system@framework@boot.art
03-17 07:10:34.995  1022  1022 D CrashAnrDetector:          9d40e03c  728378f8  /data/dalvik-cache/arm/system@framework@boot.art
03-17 07:10:34.995  1022  1022 D CrashAnrDetector:          9d40e040  134181a0  /dev/ashmem/dalvik-main space (deleted)
03-17 07:10:34.995  1022  1022 D CrashAnrDetector:          9d40e044  728
03-17 07:10:34.995  1022  1022 D CrashAnrDetector: processName:com.test.thalitest
03-17 07:10:34.995  1022  1022 D CrashAnrDetector: broadcastEvent : com.test.thalitest SYSTEM_TOMBSTONE
03-17 07:10:34.995  1022  1022 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 com.android.server.analytics.data.collection.application.CrashAnrDetector.broadcastEvent:296 com.android.server.analytics.data.collection.application.CrashAnrDetector.processDropBoxEntry:254 com.android.server.analytics.data.collection.application.CrashAnrDetector.access$100:60 com.android.server.analytics.data.collection.application.CrashAnrDetector$1.onReceive:102 
03-17 07:10:34.995  3165  3165 D BluetoothAdapterService: checkAddrForIOP: Loading from conf
03-17 07:10:34.995  1022  3171 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-17 07:10:34.995  1022  3171 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
03-17 07:10:34.995  1022  3171 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-17 07:10:34.995  1022  3213 I BootReceiver: Copying /data/tombstones/tombstone_03 to DropBox (SYSTEM_TOMBSTONE)
03-17 07:10:35.005  1022  3263 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
03-17 07:10:35.005  1022  3171 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-17 07:10:35.005  1022  3171 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
03-17 07:10:35.015  1022  1034 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:35.015  1022  1034 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:35.015  1022  1034 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
03-17 07:10:35.015  3165  3290 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
03-17 07:10:35.015  3165  3290 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
03-17 07:10:35.025  3165  3290 E BluetoothServiceJni: populateRssiValuesNative
03-17 07:10:35.025  3165  3290 I bluedroid: getModelRssiValues
03-17 07:10:35.025  3165  3290 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
,03-17 07:10:35.025  3165  3290 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,03-17 07:10:35.025  1880  1880 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 07:10:35.025  1022  1022 D CrashAnrDetector: Build: samsung/a3ultexx/a3ulte:5.0.2/LRX22G/A300FUXXU1BOEC:user/release-keys
03-17 07:10:35.025  1022  1022 D CrashAnrDetector: Hardware: MSM8916
03-17 07:10:35.025  1022  1022 D CrashAnrDetector: Revision: 1
03-17 07:10:35.025  1022  1022 D CrashAnrDetector: Bootloader: A300FUXXU1BOEC
03-17 07:10:35.025  1022  1022 D CrashAnrDetector: Radio: unknown
03-17 07:10:35.025  1022  1022 D CrashAnrDetector: Kernel: Linux version 3.10.49-4866174 (dpi@SWDD6204) (gcc version 4.8 (GCC) ) #1 SMP PREEMPT Fri May 29 20:06:40 KST 2015
03-17 07:10:35.025  1022  1022 D CrashAnrDetector: 
03-17 07:10:35.025  1022  1022 D CrashAnrDetector: *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
03-17 07:10:35.025  1022  1022 D CrashAnrDetector: Build fingerprint: 'samsung/a3ultexx/a3ulte:5.0.2/LRX22G/A300FUXXU1BOEC:user/release-keys'
03-17 07:10:35.025  1022  1022 D CrashAnrDetector: Revision: '1'
03-17 07:10:35.025  1022  1022 D CrashAnrDetector: ABI: 'arm'
03-17 07:10:35.025  1022  1022 D CrashAnrDetector: pid: 5655, tid: 6424, name: Thread-966  >>> com.test.thalitest <<<
03-17 07:10:35.025  1022  1022 D CrashAnrDetector: signal 11 (SIGSEGV), code 2 (SEGV_ACCERR), fault addr 0x9d209ff0
03-17 07:10:35.025  1022  1022 D CrashAnrDetector:     r0 703224a8  r1 728378f8  r2 12c0ba50  r3 133acf40
03-17 07:10:35.025  1022  1022 D CrashAnrDetector:     r4 000000c2  r5 703224a8  r6 728378f8  r7 133acf40
03-17 07:10:35.025  1022  1022 D CrashAnrDetector:     r8 728378a0  r9 b90e0430  sl 12c0ba50  fp 9d30b8a8
03-17 07:10:35.025  1022  1022 D CrashAnrDetector:     ip 9d209ff0  sp 9d20bff0  lr 7541f389  pc 7541f30c  cpsr a00f0030
03-17 07:10:35.025  1022  1022 D CrashAnrDetector:     d0  12c0ba5072837840  d1  00730020006500cf
03-17 07:10:35.025  1022  1022 D CrashAnrDetector:     d2  c0c0c0c0c0c0c03a  d3  0102020202020213
03-17 07:10:35.025  1022  1022 D CrashAnrDetector:     d4  0040404040404040  d5  0004000400040004
03-17 07:10:35.025  1022  1022 D CrashAnrDetector:     d6  0000000000000000  d7  0003000400040004
03-17 07:10:35.025  1022  1022 D CrashAnrDetector:     d8  0000000000000000  d9  0000000000000000
03-17 07:10:35.025  1022  1022 D CrashAnrDetector:     d10 0000000000000000  d11 0000000000000000
03-17 07:10:35.025  1022  1022 D CrashAnrDetector:     d12 0000000000000000  d13 0000000000000000
03-17 07:10:35.025  1022  1022 D CrashAnrDetector:     d14 0000000000000000  d15 0000000000000000
03-17 07:10:35.025  1022  1022 D CrashAnrDetector:     d16 0000000000000000  d17 7320656d69746e75
03-17 07:10:35.025  1022  1022 D CrashAnrDetector:     d18 0069007200750064  d19 007200200067006e
03-17 07:10:35.025  1022  1022 D CrashAnrDetector:     d20 0101010101010101  d21 0101010101010101
03-17 07:10:35.025  1022  1022 D CrashAnrDetector:     d22 8080808080808080  d23 8080808080808080
03-17 07:10:35.025  1022  1022 D CrashAnrDetector:     d24 4000404040404040  d25 0040404040404040
03-17 07:10:35.025  1022  1022 D CrashAnrDetector:     d26 0f0f0f0f0f0f0f0f  d27 0f0f0f0f0f0f0f0f
03-17 07:10:35.025  1022  1022 D CrashAnrDetector:     d28 0101010101010101  d29 0101010101010101
03-17 07:10:35.025  1022  1022 D CrashAnrDetector:     d30 0000000000000000  d31 0000000000000000
03-17 07:10:35.025  1022  1022 D CrashAnrDetector:     scr 20000013
03-17 07:10:35.025  1022  1022 D CrashAnrDetector: 
03-17 07:10:35.025  1022  1022 D CrashAnrDetector: backtrace:
03-17 07:10:35.025  1022  1022 D CrashAnrDetector:     #00 pc 0009230c  /system/framework/arm/boot.oat
03-17 07:10:35.025  1022  1022 D CrashAnrDetector:     #01 pc 00092387  /system/framework/arm/boot.oat
03-17 07:10:35.025  1022  1022 D CrashAnrDetector: 
03-17 07:10:35.025  1022  1022 D CrashAnrDetector: stack:
03-17 07:10:35.025  1022  1022 D CrashAnrDetector:          9d20bf70  00000000  
03-17 07:10:35.025  1022  1022 D CrashAnrDetector:          9d20bf74  00000000  
03-17 07:10:35.025  1022  1022 D CrashAnrDetector:          9d20bf78  00000000  
03-17 07:10:35.025  1022  1022 D CrashAnrDetector:        ,  9d20bf7c  00000000  
03-17 07:10:35.025  1022  1022 D CrashAnrDetector:          9d20bf80  00000000  
03-17 07:10:35.025  1022  1022 D CrashAnrDetector:          9d20bf84  00000000  
03-17 07:10:35.025  1022  1022 D CrashAnrDetector:          9d20bf88  00000000  
03-17 07:10:35.025  1022  1022 D CrashAnrDetector:          9d20bf8c  00000000  
03-17 07:10:35.025  1022  1022 D CrashAnrDetector:          9d20bf90  00000000  
03-17 07:10:35.025  1022  1022 D CrashAnrDetector:          9d20bf94  00000000  
03-17 07:10:35.025  1022  1022 D CrashAnrDetector:          9d20bf98  00000000  
03-17 07:10:35.025  1022  1022 D CrashAnrDetector:          9d20bf9c  00000000  
03-17 07:10:35.025  1022  1022 D CrashAnrDetector:          9d20bfa0  00000000  
03-17 07:10:35.025  1022  1022 D CrashAnrDetector:          9d20bfa4  00000000  
03-17 07:10:35.025  1022  1022 D CrashAnrDetector:          9d20bfa8  00000000  
03-17 07:10:35.025  1022  1022 D CrashAnrDetector:          9d20bfac  00000000  
03-17 07:10:35.025  1022  1022 D CrashAnrDetector:          9d20bfb0  00000000  
03-17 07:10:35.025  1022  1022 D CrashAnrDetector:          9d20bfb4  00000000  
03-17 07:10:35.025  1022  1022 D CrashAnrDetector:          9d20bfb8  00000000  
03-17 07:10:35.025  1022  1022 D CrashAnrDetector:          9d20bfbc  00000000  
03-17 07:10:35.025  1022  1022 D CrashAnrDetector:          9d20bfc0  00000000  
03-17 07:10:35.025  1022  1022 D CrashAnrDetector:          9d20bfc4  00000000  
03-17 07:10:35.025  1022  1022 D CrashAnrDetector:          9d20bfc8  00000000  
03-17 07:10:35.025  1022  1022 D CrashAnrDetector:          9d20bfcc  00000000  
03-17 07:10:35.025  1022  1022 D CrashAnrDetector:          9d20bfd0  7030fc38  /data/dalvik-cache/arm/system@framework@boot.art
03-17 07:10:35.025  1022  1022 D CrashAnrDetector:          9d20bfd4  00000000  
03-17 07:10:35.025  1022  1022 D CrashAnrDetector:          9d20bfd8  00000000  
03-17 07:10:35.025  1022  1022 D CrashAnrDetector:          9d20bfdc  00000000  
03-17 07:10:35.025  1022  1022 D CrashAnrDetector:          9d20bfe0  00000000  
03-17 07:10:35.025  1022  1022 D CrashAnrDetector:          9d20bfe4  703224a8  /data/dalvik-cache/arm/system@framework@boot.art
03-17 07:10:35.025  1022  1022 D CrashAnrDetector:          9d20bfe8  e3a070ad  
03-17 07:10:35.025  1022  1022 D CrashAnrDetector:          9d20bfec  ef9000ad  
03-17 07:10:35.025  1022  1022 D CrashAnrDetector:     #00  9d20bff0  703224a8  /data/dalvik-cache/arm/system@framework@boot.art
03-17 07:10:35.025  1022  1022 D CrashAnrDetector:          ........  ........
03-17 07:10:35.025  1022  1022 D CrashAnrDetector:     #01  9d20bff0  703224a8  /data/dalvik-cache/arm/system@framework@boot.art
03-17 07:10:35.025  1022  1022 D CrashAnrDetector:          9d20bff4  00000000  
03-17 07:10:35.025  1022  1022 D CrashAnrDetector:          9d20bff8  00000000  
03-17 07:10:35.025  1022  1022 D CrashAnrDetector:          9d20bffc  00000000  
03-17 07:10:35.025  1022  1022 D CrashAnrDetector:          9d20c000  00000000  
03-17 07:10:35.025  1022  1022 D CrashAnrDetector:          9d20c004  00000000  
03-17 07:10:35.025  1022  1022 D CrashAnrDetector:          9d20c008  703224a8  /data/dalvik-cache/arm/system@framework@boot.art
03-17 07:10:35.025  1022  1022 D CrashAnrDetector:          9d20c00c  728378a0  /data/dalvik-cache/arm/system@framework@boot.art
03-17 07:10:35.025  1022  1022 D CrashAnrDetector:          9d20c010  133acf40  /dev/ashmem/dalvik-main space (deleted)
03-17 07:10:35.025  1022  1022 D CrashAnrDetector:          9d20c014  728378f8  /data/dalvik-cache/arm/system@framework@boot.art
03-17 07:10:35.025  1022  1022 D CrashAnrDetector:          9d20c018  12c0ba50  /dev/ashmem/dalvik-main space (deleted)
03-17 07:10:35.025  1022  1022 D CrashAnrDetector:          9d20c01c  7541f33d  /system/framework/arm/boot.oat
03-17 07:10:35.025  1022  1022 D CrashAnrDetector:          9d20c020  703224a8  /data/dalvik-cache/arm/system@framework@boot.art
03-17 07:10:35.025  1022  1022 D CrashAnrDetector:          9d20c024  00000000  
03-17 07:10:35.025  1022  1022 D CrashAnrDetector:          9d20c028  00000000  
03-17 07:10:35.025  1022  1022 D CrashAnrDetector:          9d20c02c  00000000  
03-17 07:10:35.025  1022  1022 D CrashAnrDetector:          9d20c030  7030fc38  /data/dalvik-cache/arm/system@framework@boot.art
03-17 07:10:35.025  1022  1022 D CrashAnrDetector:          9d20c034  00000000  
03-17 07:10:35.025  1022  1022 D CrashAnrDetector:          9d20c038  703224a8  /data/dalvik-cache/arm/system@framework@boot.art
03-17 07:10:35.025  1022  1022 D CrashAnrDetector:          9d20c03c  728378f8  /data/dalvik-cache/arm/system@framework@boot.art
03-17 07:10:35.025  1022  1022 D CrashAnrDetector:          9d20c040  133acf40  /dev/ashmem/dalvik-main space (deleted)
03-17 07:10:35.025  1022  1022 D CrashAnrDetector:          9d20c044  728
03-17 07:10:35.025  1022  1022 D CrashAnrDetector: processName:com.test.thalitest
03-17 07:10:35.025  3165  3290 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3)
03-17 07:10:35.025  1022  1022 D CrashAnrDetector: broadcastEvent : com.test.thalitest SYSTEM_TOMBSTONE
03-17 07:10:35.035  1022  3171 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-17 07:10:35.035  1022  3171 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
03-17 07:10:35.035  1022  1022 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 com.android.server.analytics.data.collection.application.CrashAnrDetector.broadcastEvent:296 com.android.server.analytics.data.collection.application.CrashAnrDetector.processDropBoxEntry:254 com.android.server.analytics.data.collection.application.CrashAnrDetector.access$100:60 com.android.server.analytics.data.collection.application.CrashAnrDetector$1.onReceive:102 
03-17 07:10:35.035  1022  1022 D SettingsProvider: name = bluetooth_name
03-17 07:10:35.035  1022  3213 I BootReceiver: Copying /data/tombstones/tombstone_04 to DropBox (SYSTEM_TOMBSTONE)
03-17 07:10:35.035  1022  3263 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
03-17 07:10:35.035  1022  3171 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-17 07:10:35.045  1022  1520 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
03-17 07:10:35.045  3165  3194 I bluedroid: config_hci_snoop_log
03-17 07:10:35.045  1022  1051 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
03-17 07:10:35.045   288   288 E SMD     : DCD OFF
03-17 07:10:35.055  1022  1052 I ActivityManager: Displayed Component not be shown by security: +1s108ms
03-17 07:10:35.055  1022  1052 W ActivityManager: mDVFSHelper.release()
03-17 07:10:35.055  1022  1052 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{37e2acb4 u0 com.test.thalitest/.MainActivity t11} time:37186
03-17 07:10:35.055  1022  3292 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
03-17 07:10:35.065  1022  1051 D BluetoothManagerService: Ble is always on enable gatt
03-17 07:10:35.065  1022  1051 I BluetoothManagerService: enableGattForLeMode, doBind called
,03-17 07:10:35.065  1022  1051 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
03-17 07:10:35.065  1022  1051 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
03-17 07:10:35.075  3165  3165 I BtGatt.JNI: classInitNative(L900): classInitNative: Success!
03-17 07:10:35.075  1022  1022 D CrashAnrDetector: Build: samsung/a3ultexx/a3ulte:5.0.2/LRX22G/A300FUXXU1BOEC:user/release-keys
03-17 07:10:35.075  1022  1022 D CrashAnrDetector: Hardware: MSM8916
03-17 07:10:35.075  1022  1022 D CrashAnrDetector: Revision: 1
03-17 07:10:35.075  1022  1022 D CrashAnrDetector: Bootloader: A300FUXXU1BOEC
03-17 07:10:35.075  1022  1022 D CrashAnrDetector: Radio: unknown
03-17 07:10:35.075  1022  1022 D CrashAnrDetector: Kernel: Linux version 3.10.49-4866174 (dpi@SWDD6204) (gcc version 4.8 (GCC) ) #1 SMP PREEMPT Fri May 29 20:06:40 KST 2015
03-17 07:10:35.075  1022  1022 D CrashAnrDetector: 
03-17 07:10:35.075  1022  1022 D CrashAnrDetector: *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
03-17 07:10:35.075  1022  1022 D CrashAnrDetector: Build fingerprint: 'samsung/a3ultexx/a3ulte:5.0.2/LRX22G/A300FUXXU1BOEC:user/release-keys'
03-17 07:10:35.075  1022  1022 D CrashAnrDetector: Revision: '1'
03-17 07:10:35.075  1022  1022 D CrashAnrDetector: ABI: 'arm'
03-17 07:10:35.075  1022  1022 D CrashAnrDetector: pid: 3041, tid: 3372, name: Thread-383  >>> com.example.hello <<<
03-17 07:10:35.075  1022  1022 D CrashAnrDetector: signal 11 (SIGSEGV), code 1 (SEGV_MAPERR), fault addr 0x0
03-17 07:10:35.075  1022  1022 D CrashAnrDetector:     r0 00000000  r1 00000000  r2 00000000  r3 00000000
03-17 07:10:35.075  1022  1022 D CrashAnrDetector:     r4 9e1a7e78  r5 9e1a7e38  r6 b7dca130  r7 9e1a7e38
03-17 07:10:35.075  1022  1022 D CrashAnrDetector:     r8 00000000  r9 9e1a7e74  sl 9e1a93d0  fp 9e1a7e1c
03-17 07:10:35.075  1022  1022 D CrashAnrDetector:     ip 9ec7dba0  sp 9e1a7e00  lr 9e984308  pc b6ee9468  cpsr 600d0030
03-17 07:10:35.075  1022  1022 D CrashAnrDetector:     d0  00000035020000d5  d1  513802003a373ef1
03-17 07:10:35.075  1022  1022 D CrashAnrDetector:     d2  0000b80c0300009d  d3  88000000560a1060
03-17 07:10:35.075  1022  1022 D CrashAnrDetector:     d4  07490c0000003d01  d5  0000008849000000
03-17 07:10:35.075  1022  1022 D CrashAnrDetector:     d6  0a0e000000b80c0c  d7  01003a0f0000003d
03-17 07:10:35.075  1022  1022 D CrashAnrDetector:     d8  0000000000000000  d9  0000000000000000
03-17 07:10:35.075  1022  1022 D CrashAnrDetector:     d10 0000000000000000  d11 0000000000000000
03-17 07:10:35.075  1022  1022 D CrashAnrDetector:     d12 0000000000000000  d13 0000000000000000
03-17 07:10:35.075  1022  1022 D CrashAnrDetector:     d14 0000000000000000  d15 0000000000000000
03-17 07:10:35.075  1022  1022 D CrashAnrDetector:     d16 0000000000000000  d17 ffffffffffffffff
03-17 07:10:35.075  1022  1022 D CrashAnrDetector:     d18 0001000100010001  d19 0001000100010001
03-17 07:10:35.075  1022  1022 D CrashAnrDetector:     d20 0000000000000001  d21 0000000000000000
03-17 07:10:35.075  1022  1022 D CrashAnrDetector:     d22 0000000000000000  d23 0000000000000000
03-17 07:10:35.075  1022  1022 D CrashAnrDetector:     d24 0000000000000000  d25 0000000000000000
03-17 07:10:35.075  1022  1022 D CrashAnrDetector:     d26 0002000200020001  d27 0002000200020002
03-17 07:10:35.075  1022  1022 D CrashAnrDetector:     d28 0080008000800080  d29 0080008000800080
03-17 07:10:35.075  1022  1022 D CrashAnrDetector:     d30 0800080008000800  d31 0800080008000800
03-17 07:10:35.075  1022  1022 D CrashAnrDetector:     scr 20000012
03-17 07:10:35.075  1022  1022 D CrashAnrDetector: 
03-17 07:10:35.075  1022  1022 D CrashAnrDetector: backtrace:
03-17 07:10:35.075  1022  1022 D CrashAnrDetector:     #00 pc 00010468  /system/lib/libc.so (strlen+83)
03-17 07:10:35.075  1022  1022 D CrashAnrDetector:     #01 pc 007da304  /data/app/com.example.hello-1/lib/arm/libjxcore.so (MozJS::String::FromUTF8(JSContext*, char const*, int)+40)
03-17 07:10:35.075  1022  1022 D CrashAnrDetector: 
03-17 07:10:35.075  1022  1022 D CrashAnrDetector: stack:
03-17 07:10:35.075  1022  1022 D CrashAnrDetector:          9e1a7d80  00000000  
03-17 07:10:35.075  1022  1022 D CrashAnrDetector:          9e1a7d84  00000000  
03-17 07:10:35.075  1022  1022 D CrashAnrDetector:          9e1a7d88  9de2b820  [anon:js-gc-heap]
03-17 07:10:35.075  1022  1022 D CrashAnrDetector:          9e1a7d8c  f5cf96b7  
03-17 07:10:35.075  1022  1022 D CrashAnrDetector:          9e1a7d90  9e1a7dbc  [stack:3372]
03-17 07:10:35.075  1022  1022 D CrashAnrDetector:          9e1a7d94  9e1a7e64  [stack:3372]
03-17 07:10:35.075  1022  1022 D CrashAnrDetector:          9e1a7d98  b7dca130  [heap]
03-17 07:10:35.075  1022  1022 D CrashAnrDetector:          9e1a7d9c  00000003  
03-17 07:10:35.075  1022  1022 D CrashAnrDetector:          9e1a7da0  9e1a7ddc  [stack:3372]
03-17 07:10:35.075  1022  1022 D CrashAnrDetector:          9e1a7da4  b7ebd960  [heap]
03-17 07:10:35.075  1022  1022 D CrashAnrDetector:          9e1a7da8  9de53b00  [anon:js-gc-heap]
03-17 07:10:35.075  1022  1022 D CrashAnrDetector:          9e1a7dac  9df11b30  [anon:js-gc-heap]
03-17 07:10:35.075  1022  1022 D CrashAnrDetector:          9e1a7db0  00000000  
03-17 07:10:35.075  1022  1022 D CrashAnrDetector:          9e1a7db4  ffffff82  
03-17 07:10:35.075  1022  1022 D CrashAnrDetector:          9e1a7db8  00000000  
03-17 07:10:35.075  1022  1022 D CrashAnrDetector:          9e1a7dbc  ffffff82  
03-17 07:10:35.075  1022  1022 D CrashAnrDetector:          9e1a7dc0  9de2b040  [anon:js-gc-heap]
03-17 07:10:35.075  1022  1022 D CrashAnrDetector:          9e1a7dc4  b7eba960  [heap]
03-17 07:10:35.075  1022  1022 D CrashAnrDetector:          9e1a7dc8  b7f16b48  [heap]
03-17 07:10:35.075  1022  1022 D CrashAnrDetector:          9e1a7dcc  00000001  
03-17 07:10:35.075  1022  1022 D CrashAnrDetector:          9e1a7dd0  9de49160  [anon:js-gc-heap]
03-17 07:10:35.075  1022  1022 D CrashAnrDetector:          9e1a7dd4  b7dca130  [heap]
03-17 07:10:35.075  1022  1022 D CrashAnrDetector:          9e1a7dd8  9de4f1c0  [anon:js-gc-heap]
03-17 07:10:35.075  1022  1022 D CrashAnrDetector:          9e1a7ddc  00000000  
03-17 07:10:35.075  1022  1022 D CrashAnrDetector:          9e1a7de0  00000000  
03-17 07:10:35.075  1022  1022 D CrashAnrDetector:          9e1a7de4  00000000  
03-17 07:10:35.075  1022  1022 D CrashAnrDetector:          9e1a7de8  00000003  
03-17 07:10:35.075  1022  1022 D CrashAnrDetector:          9e1a7dec  000000aa  
03-17 07:10:35.075  1022  1022 D CrashAnrDetector:          9e1a7df0  0000006b  
03-17 07:10:35.075  1022  1022 D CrashAnrDetector:          9e1a7df4  0001416e  
03-17 07:10:35.075  1022  1022 D CrashAnrDetector:          9e1a7df8  00000000  
03-17 07:10:35.075  1022  1022 D CrashAnrDetector:          9e1a7dfc  9e1a7e30  [stack:3372]
03-17 07:10:35.075  1022  1022 D CrashAnrDetector:     #00  9e1a7e00  9e1a7e78  [stack:3372]
03-17 07:10:35.075  1022  1022 D CrashAnrDetector:          ........  ........
03-17 07:10:35.075  1022  1022 D CrashAnrDetector:     #01  9e1a7e00  9e1a7e78  [stack:3372]
03-17 07:10:35.075  1022  1022 D CrashAnrDetector:          9e1a7e04  00000000  
03-17 07:10:35.075  1022  1022 D CrashAnrDetector:          9e1a7e08  9e1a7e78  [stack:3372]
03-17 07:10:35.075  1022  1022 D CrashAnrDetector:          9e1a7e0c  9e1a7e5c  [stack:3372]
03-17 07:10:35.075  1022  1022 D CrashAnrDetector:          9e1a7e10  9e1a7e48  [stack:3372]
03-17 07:10:35.075  1022  1022 D CrashAnrDetector:          9e1a7e14  00000000  
03-17 07:10:35.075  1022  1022 D CrashAnrDetector:          9e1a7e18  9e1a8e94  [stack:3372]
03-17 07:10:35.075  1022  1022 D CrashAnrDetector:          9e1a7e1c  9e95b3f0  /data/app/com.example.hello-1/lib/arm/libjxcore.so
03-17 07:10:35.075  1022  1022 D CrashAnrDetector:          9e1a7e20  9e1a7e50  [stack:3372]
03-17 07:10:35.075  1022  1022 D CrashAnrDetector:          9e1a7e24  00000000  
03-17 07:10:35.075  1022  1022 D CrashAnrDetector:          9e1a7e28  9e1a7e44  [stack:3372]
03-17 07:10:35.075  1022  1022 D CrashAnrDetector:          9e1a7e2c  9e78d184  /data/app/com.example.hello-1/lib/arm/libjxcore.so (js_fun_call(JSContext*, unsigned int, JS::Value*)+172)
03-17 07:10:35.075  1022  1022 D CrashAnrDetector:          9e1a7e30  00000000  
03-17 07:10:35.075  1022  1022 D CrashAnrDetector:          9e1a7e34  00000000  
03-17 07:10:35.075  1022  1022 D CrashAnrDetector:          9e1a7e38  b6f2fde4  
03-17 07:10:35.075  1022  1022 D CrashAnrDetector:          9e1a7e3c  00000000  
03-17 07:10:35.075  1022  1022 D CrashAnrDetector:          9e1a7e40  9e1a81cc  [stack:3372]
03-17 07:10:35.075  1022  1022 D CrashAnrDetector:          9e1a7e44  9e869b34  /data/app/com.example.hello-1/lib/arm/libjxcore.so (js::Invoke(JSContext*, JS::CallArgs, js::MaybeConstruct)+340)
03-17 07:10:35.075  1022  1022 D CrashAnrDetector:          9e1a7e48  b7dca130  [heap]
03-17 07:10:35.075  1022  1022 D CrashAnrDetector:          9e1a7e4c  b7dca130  [heap]
03-17 07:10:35.075  1022  1022 D CrashAnrDetector:          9e1a7e50  b7f16b48  [heap]
03-17 07:10:35.075  1022  1022 D CrashAnrDetector:          9e1a7e54  00000001  
03-17 07:10:35.075  1022  1022 D CrashAnrDetector:          9e1a7e58  9
03-17 07:10:35.075  1022  1022 D CrashAnrDetector: processName:com.example.hello
03-17 07:10:35.075  1022  1022 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 com.android.server.analytics.data.collection.application.CrashAnrDetector.broadcastEvent:296 com.android.server.analytics.data.collection.application.CrashAnrDetector.processDropBoxEntry:254 com.android.server.analytics.data.collection.application.CrashAnrDetector.access$100:60 com.android.server.analytics.data.collection.application.CrashAnrDetector$1.onReceive:102 
03-17 07:10:35.075  1022  1022 D CrashAnrDetector: broadcastEvent : null SYSTEM_TOMBSTONE
03-17 07:10:35.075  1206  1206 I StatusBar: Icon Only
03-17 07:10:35.075  1022  1051 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
03-17 07:10:35.075  1206  1206 D PanelView: There is/are notification(s) 
03-17 07:10:35.085  3146  3146 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@1fc07ada time:37211
03-17 07:10:35.085  1022  1404 D SettingsProvider: name = db_smartlock_supported
03-17 07:10:35.085  1022  1659 I ActivityManager: Killing 2394:com.sec.android.app.mt/1000 (adj 15): empty #31
,03-17 07:10:35.105  3165  3285 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
03-17 07:10:35.105  3165  3285 D BluetoothAdapterProperties: Setting state to 11
03-17 07:10:35.115  3165  3285 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
03-17 07:10:35.115  3165  3285 D BluetoothAdapterService: Bluetooth PBAP supproted is true
03-17 07:10:35.115  3165  3285 D BluetoothAdapterService: updateAdapterState state is 11
03-17 07:10:35.115  3165  3285 D BluetoothAdapterService: Autoconnection is available 
03-17 07:10:35.115  3165  3285 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
03-17 07:10:35.115   315   315 I ServiceManager: Waiting for service AtCmdFwd...
03-17 07:10:35.125  3165  3285 D BluetoothSecureManager: getInstant: null
03-17 07:10:35.125  3165  3285 D BluetoothSecureManager: calling getMethod for getService
03-17 07:10:35.125  3165  3285 D BluetoothSecureManager: calling getService
03-17 07:10:35.125  3165  3285 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@37bf17f6
03-17 07:10:35.125  1022  3213 I BootReceiver: Copying /data/tombstones/tombstone_05 to DropBox (SYSTEM_TOMBSTONE)
03-17 07:10:35.125  1022  3263 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
03-17 07:10:35.135  1206  1206 D BluetoothTile:  onBluetoothPairedDevicesChanged:
03-17 07:10:35.135  1206  1206 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
03-17 07:10:35.135  1206  1206 D BluetoothTile:  getBluetoothState : 11
03-17 07:10:35.135  1206  1628 D BluetoothTile:  handleUpdatestate:false name:null
03-17 07:10:35.135  1206  1628 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
03-17 07:10:35.135  1022  1507 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
03-17 07:10:35.135  1022  1035 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
03-17 07:10:35.145  1022  1022 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
03-17 07:10:35.145  1022  1022 I InputMethodManagerService: [BT Setting State] State =11
03-17 07:10:35.145  1022  1902 D BluetoothSecureManagerService: isSecureModeEnabled
03-17 07:10:35.145  1206  1206 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
03-17 07:10:35.145  1022  1902 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
03-17 07:10:35.145  3165  3285 D BtConfig.SecureMode: isSecureModeOn:false
03-17 07:10:35.145  3165  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
03-17 07:10:35.145  3165  3285 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
03-17 07:10:35.145  3165  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,03-17 07:10:35.145  3165  3285 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
03-17 07:10:35.145  3165  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,03-17 07:10:35.145  1022  1051 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,03-17 07:10:35.145  3165  3285 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
,03-17 07:10:35.145  3165  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,03-17 07:10:35.155  3165  3285 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
03-17 07:10:35.155  3165  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,03-17 07:10:35.155  3165  3285 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
,03-17 07:10:35.155  3165  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
03-17 07:10:35.155  3165  3285 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
03-17 07:10:35.155  3165  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,03-17 07:10:35.155  3165  3285 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
03-17 07:10:35.155  3165  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
03-17 07:10:35.155  3165  3285 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
03-17 07:10:35.155  3165  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
03-17 07:10:35.155  1206  1206 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
03-17 07:10:35.155  3165  3285 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
03-17 07:10:35.155  3165  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
03-17 07:10:35.165  3165  3285 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
03-17 07:10:35.165  3165  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
03-17 07:10:35.165  3165  3285 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
03-17 07:10:35.165  3165  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
03-17 07:10:35.165  3165  3285 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
03-17 07:10:35.165  3165  3285 D BluetoothBondStateMachine: make
,03-17 07:10:35.165  1022  1022 D CrashAnrDetector: Build: samsung/a3ultexx/a3ulte:5.0.2/LRX22G/A300FUXXU1BOEC:user/release-keys
03-17 07:10:35.165  1022  1022 D CrashAnrDetector: Hardware: MSM8916
03-17 07:10:35.165  1022  1022 D CrashAnrDetector: Revision: 1
03-17 07:10:35.165  1022  1022 D CrashAnrDetector: Bootloader: A300FUXXU1BOEC
03-17 07:10:35.165  1022  1022 D CrashAnrDetector: Radio: unknown
03-17 07:10:35.165  1022  1022 D CrashAnrDetector: Kernel: Linux version 3.10.49-4866174 (dpi@SWDD6204) (gcc version 4.8 (GCC) ) #1 SMP PREEMPT Fri May 29 20:06:40 KST 2015
03-17 07:10:35.165  1022  1022 D CrashAnrDetector: 
03-17 07:10:35.165  1022  1022 D CrashAnrDetector: *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
03-17 07:10:35.165  1022  1022 D CrashAnrDetector: Build fingerprint: 'samsung/a3ultexx/a3ulte:5.0.2/LRX22G/A300FUXXU1BOEC:user/release-keys'
03-17 07:10:35.165  1022  1022 D CrashAnrDetector: Revision: '1'
03-17 07:10:35.165  1022  1022 D CrashAnrDetector: ABI: 'arm'
03-17 07:10:35.165  1022  1022 D CrashAnrDetector: pid: 4387, tid: 4703, name: Thread-677  >>> com.test.thalitest <<<
03-17 07:10:35.165  1022  1022 D CrashAnrDetector: signal 11 (SIGSEGV), code 1 (SEGV_MAPERR), fault addr 0x0
03-17 07:10:35.165  1022  1022 D CrashAnrDetector:     r0 00000000  r1 9dbf6494  r2 00000002  r3 00000000
03-17 07:10:35.165  1022  1022 D CrashAnrDetector:     r4 b8d43750  r5 00000000  r6 b8d42fe0  r7 bb70b440
03-17 07:10:35.165  1022  1022 D CrashAnrDetector:     r8 b8d2beb4  r9 b8d43750  sl b8d42fb8  fp 9dbf648c
03-17 07:10:35.165  1022  1022 D CrashAnrDetector:     ip ffffffff  sp 9dbf647c  lr 9e0d1b30  pc 9e0d1a34  cpsr 60000010
03-17 07:10:35.165  1022  1022 D CrashAnrDetector:     d0  0000000000000000  d1  0000000000000000
03-17 07:10:35.165  1022  1022 D CrashAnrDetector:     d2  0000000000000000  d3  0000000000000000
03-17 07:10:35.165  1022  1022 D CrashAnrDetector:     d4  0000000000000000  d5  0000000000000000
03-17 07:10:35.165  1022  1022 D CrashAnrDetector:     d6  0000000000000000  d7  0000000000000000
03-17 07:10:35.165  1022  1022 D CrashAnrDetector:     d8  0000000000000000  d9  0000000000000000
03-17 07:10:35.165  1022  1022 D CrashAnrDetector:     d10 0000000000000000  d11 0000000000000000
03-17 07:10:35.165  1022  1022 D CrashAnrDetector:     d12 0000000000000000  d13 0000000000000000
03-17 07:10:35.165  1022  1022 D CrashAnrDetector:     d14 0000000000000000  d15 0000000000000000
03-17 07:10:35.165  1022  1022 D CrashAnrDetector:     d16 000027b7000027b7  d17 000027b700000000
03-17 07:10:35.165  1022  1022 D CrashAnrDetector:     d18 0001000100010001  d19 0001000100010001
03-17 07:10:35.165  1022  1022 D CrashAnrDetector:     d20 0000000100010001  d21 0000000000000000
03-17 07:10:35.165  1022  1022 D CrashAnrDetector:     d22 0000000000000000  d23 0000000000000000
03-17 07:10:35.165  1022  1022 D CrashAnrDetector:     d24 0000000000000000  d25 0000000000000000
03-17 07:10:35.165  1022  1022 D CrashAnrDetector:     d26 0002000100010001  d27 0002000200020002
03-17 07:10:35.165  1022  1022 D CrashAnrDetector:     d28 0080008000800080  d29 0080008000800080
03-17 07:10:35.165  1022  1022 D CrashAnrDetector:     d30 0800080008000800  d31 0800080008000800
03-17 07:10:35.165  1022  1022 D CrashAnrDetector:     scr 20000012
03-17 07:10:35.165  1022  1022 D CrashAnrDetector: 
03-17 07:10:35.165  1022  1022 D CrashAnrDetector: backtrace:
03-17 07:10:35.165  1022  1022 D CrashAnrDetector:     #00 pc 003d1a34  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (bool ThingIsPermanentAtom<JS::Symbol>(JS::Symbol*)+4)
03-17 07:10:35.165  1022  1022 D CrashAnrDetector:     #01 pc 003d1b2c  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so
03-17 07:10:35.165  1022  1022 D CrashAnrDetector:     #02 pc e5943000  <unknown>
03-17 07:10:35.165  1022  1022 D CrashAnrDetector: 
03-17 07:10:35.165  1022  1022 D CrashAnrDetector: stack:
03-17 07:10:35.165  1022  1022 D CrashAnrDetector:          9dbf63fc  00000006  
03-17 07:10:35.165  1022  1022 D CrashAnrDetector:          9dbf6400  8fd92780  [anon:js-gc-heap]
03-17 07:10:35.165  1022  1022 D CrashAnrDetector:          9dbf6404  b8d43750  [heap]
03-17 07:10:35.165  1022  1022 D CrashAnrDetector:          9dbf6408  9e611b34  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so
03-17 07:10:35.165  1022  1022 D CrashAnrDetector:          9dbf640c  b8d43750  [heap]
03-17 07:10:35.165  1022  1022 D CrashAnrDetector:          9dbf6410  9dbf642c  [stack:4703]
03-17 07:10:35.165  1022  1022 D CrashAnrDetector:          9dbf6414  9e2f2258  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (JSScript::markChildren(JSTracer*)+404)
03-17 07:10:35.165  1022  1022 D CrashAnrDetector:          9dbf6418  00000001  
03-17 07:10:35.165  1022  1022 D CrashAnrDetector:          9dbf641c  00000000  
03-17 07:10:35.165  1022  1022 D CrashAnrDetector:          9dbf6420  b8d44280  [heap]
03-17 07:10:35.165  1022  1022 D CrashAnrDetector:          9dbf6424  00000000  
03-17 07:10:35.165  1022  1022 D CrashAnrDetector:          9dbf6428  00000000  
03-17 07:10:35.165  1022  1022 D CrashAnrDetector:          9dbf642c  b8d43750  [heap]
03-17 07:10:35.165  1022  1022 D CrashAnrDetector:          9dbf6430  b8d44280  [heap]
03-17 07:10:35.165  1022  1022 D CrashAnrDetector:          9dbf6434  9e75db60  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so
03-17 07:10:35.165  1022  1022 D CrashAnrDetector:          9dbf6438  9dbf64a4  [stack:4703]
03-17 07:10:35.165  1022  1022 D CrashAnrDetector:          9dbf643c  9e0d8514  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (js::gc::GCRuntime::markConservativeStackRoots(JSTracer*, bool)+1308)
03-17 07:10:35.165  1022  1022 D CrashAnrDetector:          9dbf6440  b8d43750  [heap]
03-17 07:10:35.165  1022  1022 D CrashAnrDetector:          9dbf6444  b8d42fb8  [heap]
03-17 07:10:35.165  1022  1022 D CrashAnrDetector:          9dbf6448  9dbfc000  
03-17 07:10:35.165  1022  1022 D CrashAnrDetector:          9dbf644c  9dbf6470  [stack:4703]
03-17 07:10:35.165  1022  1022 D CrashAnrDetector:          9dbf6450  9dbf6468  [stack:4703]
03-17 07:10:35.165  1022  1022 D CrashAnrDetector:          9dbf6454  9dbf6474  [stack:4703]
03-17 07:10:35.165  1022  1022 D CrashAnrDetector:          9dbf6458  9e6846d4  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so
03-17 07:10:35.165  1022  1022 D CrashAnrDetector:          9dbf645c  9dbf6478  [stack:4703]
03-17 07:10:35.165  1022  1022 D CrashAnrDetector:          9dbf6460  00000004  
03-17 07:10:35.165  1022  1022 D CrashAnrDetector:          9dbf6464  00000000  
03-17 07:10:35.165  1022  1022 D CrashAnrDetector:          9dbf6468  00000001  
03-17 07:10:35.165  1022  1022 D CrashAnrDetector:          9dbf646c  b8d43750  [heap]
03-17 07:10:35.165  1022  1022 D CrashAnrDetector:          9dbf6470  8fdcd3a0  [anon:js-gc-heap]
03-17 07:10:35.165  1022  1022 D CrashAnrDetector:          9dbf6474  b8d42fe0  [heap]
03-17 07:10:35.165  1022  1022 D CrashAnrDetector:          9dbf6478  9dbf648c  [stack:4703]
03-17 07:10:35.165  1022  1022 D CrashAnrDetector:     #00  9dbf647c  9dbf648c  [stack:4703]
03-17 07:10:35.165  1022  1022 D CrashAnrDetector:          9dbf6480  9dbfb838  [stack:4703]
03-17 07:10:35.165  1022  1022 D CrashAnrDetector:          9dbf6484  bb701888  [heap]
03-17 07:10:35.165  1022  1022 D CrashAnrDetector:          9dbf6488  9dbf64a4  [stack:4703]
03-17 07:10:35.165  1022  1022 D CrashAnrDetector:          9dbf648c  9e0d506c  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (js::gc::MarkValueRoot(JSTracer*, JS::Value*, char const*)+80)
03-17 07:10:35.165  1022  1022 D CrashAnrDetector:     #01  9dbf6490  b8d2beb4  [heap]
03-17 07:10:35.165  1022  1022 D CrashAnrDetector:          9dbf6494  00000000  
03-17 07:10:35.165  1022  1022 D CrashAnrDetector:          9dbf6498  b8d42fdc  [heap]
03-17 07:10:35.165  1022  1022 D CrashAnrDetector:          9dbf649c  9e605cd8  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so
03-17 07:10:35.165  1022  1022 D CrashAnrDetector:          9dbf64a0  9dbf64fc  [stack:4703]
03-17 07:10:35.,165  1022  1022 D CrashAnrDetector:          9dbf64a4  9e0d9dcc  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (js::gc::GCRuntime::markRuntime(JSTracer*, js::gc::GCRuntime::TraceOrMarkRuntime, js::gc::GCRuntime::TraceRootsOrUs
03-17 07:10:35.165  1022  1022 D CrashAnrDetector: processName:com.test.thalitest
03-17 07:10:35.165  1022  1022 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 com.android.server.analytics.data.collection.application.CrashAnrDetector.broadcastEvent:296 com.android.server.analytics.data.collection.application.CrashAnrDetector.processDropBoxEntry:254 com.android.server.analytics.data.collection.application.CrashAnrDetector.access$100:60 com.android.server.analytics.data.collection.application.CrashAnrDetector$1.onReceive:102 
03-17 07:10:35.165  1022  1022 D CrashAnrDetector: broadcastEvent : com.test.thalitest SYSTEM_TOMBSTONE
03-17 07:10:35.185  3165  3285 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
03-17 07:10:35.185  3165  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
03-17 07:10:35.185  3165  3285 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
03-17 07:10:35.185  1022  1507 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:35.185  1022  1507 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:35.185  1022  1507 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
03-17 07:10:35.185  3165  3285 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
03-17 07:10:35.185  3165  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
03-17 07:10:35.185  3165  3285 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
03-17 07:10:35.195  3165  3295 I BluetoothBondStateMachine: StableState(): Entering Off State
03-17 07:10:35.195  3165  3165 D BtGatt.DebugUtils: handleDebugAction() action=null
03-17 07:10:35.195  3165  3165 D BtGatt.GattService: Received start request. Starting profile...
03-17 07:10:35.195  3165  3165 D BtGatt.GattService: start()
03-17 07:10:35.195  3165  3165 D BtGatt.GattService: start()
03-17 07:10:35.195  3165  3165 I bluedroid: get_profile_interface gatt
03-17 07:10:35.195  3165  3165 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f4bc31e
03-17 07:10:35.195  3165  3165 D BtGatt.AdvertiseManager: advertise manager created
03-17 07:10:35.195  1022  1902 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:35.195  1022  1902 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:35.195  1022  1902 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
03-17 07:10:35.205  3165  3285 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
03-17 07:10:35.205  3165  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
03-17 07:10:35.205  3165  3285 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
03-17 07:10:35.205  1022  1507 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:35.205  1022  1507 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:35.205  1022  1507 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,03-17 07:10:35.205  1022  1046 W libprocessgroup: failed to open /acct/uid_1000/pid_2394/cgroup.procs: No such file or directory
,03-17 07:10:35.205  3165  3285 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
03-17 07:10:35.205  3165  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
03-17 07:10:35.205  3165  3285 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,03-17 07:10:35.205  3165  3165 D BtGatt.GattService: mStartError = false,
03-17 07:10:35.205  3165  3165 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f4bc31e
03-17 07:10:35.205  1022  1597 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:35.205  1022  1597 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:35.205  1022  1597 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,03-17 07:10:35.215  1022  3213 I BootReceiver: Copying /data/tombstones/tombstone_06 to DropBox (SYSTEM_TOMBSTONE)
,03-17 07:10:35.215  1022  1520 I AccessibilityManagerService: setmDNIeNegative (false)
03-17 07:10:35.215  1022  3263 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
,03-17 07:10:35.215  3165  3285 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
03-17 07:10:35.215  3165  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
03-17 07:10:35.215  3165  3285 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
03-17 07:10:35.225  1022  1667 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:35.225  1022  1667 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:35.225  1022  1667 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,03-17 07:10:35.225  3165  3285 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
03-17 07:10:35.225  3165  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
03-17 07:10:35.225  3165  3285 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
03-17 07:10:35.225  1022  1129 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:35.225  1022  1129 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:35.225  1022  1129 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,03-17 07:10:35.225  1827  1827 I SamsungIME: getCurrentCandidateView
,03-17 07:10:35.235  1022  1022 D CrashAnrDetector: Build: samsung/a3ultexx/a3ulte:5.0.2/LRX22G/A300FUXXU1BOEC:user/release-keys
03-17 07:10:35.235  1022  1022 D CrashAnrDetector: Hardware: MSM8916
03-17 07:10:35.235  1022  1022 D CrashAnrDetector: Revision: 1
03-17 07:10:35.235  1022  1022 D CrashAnrDetector: Bootloader: A300FUXXU1BOEC
03-17 07:10:35.235  1022  1022 D CrashAnrDetector: Radio: unknown
03-17 07:10:35.235  1022  1022 D CrashAnrDetector: Kernel: Linux version 3.10.49-4866174 (dpi@SWDD6204) (gcc version 4.8 (GCC) ) #1 SMP PREEMPT Fri May 29 20:06:40 KST 2015
03-17 07:10:35.235  1022  1022 D CrashAnrDetector: 
03-17 07:10:35.235  1022  1022 D CrashAnrDetector: *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
03-17 07:10:35.235  1022  1022 D CrashAnrDetector: Build fingerprint: 'samsung/a3ultexx/a3ulte:5.0.2/LRX22G/A300FUXXU1BOEC:user/release-keys'
03-17 07:10:35.235  1022  1022 D CrashAnrDetector: Revision: '1'
03-17 07:10:35.235  1022  1022 D CrashAnrDetector: ABI: 'arm'
03-17 07:10:35.235  1022  1022 D CrashAnrDetector: pid: 3807, tid: 4175, name: Thread-562  >>> com.test.thalitest <<<
03-17 07:10:35.235  1022  1022 D CrashAnrDetector: signal 11 (SIGSEGV), code 1 (SEGV_MAPERR), fault addr 0x0
03-17 07:10:35.235  1022  1022 D CrashAnrDetector:     r0 00000000  r1 9368b424  r2 00000002  r3 00000000
03-17 07:10:35.235  1022  1022 D CrashAnrDetector:     r4 b7a20c80  r5 00000000  r6 b7a20510  r7 b9bb7a70
03-17 07:10:35.235  1022  1022 D CrashAnrDetector:     r8 b7a7363c  r9 b7a20c80  sl b7a204e8  fp 9368b41c
03-17 07:10:35.235  1022  1022 D CrashAnrDetector:     ip ffffffff  sp 9368b40c  lr 93d81b30  pc 93d81a34  cpsr 60000010
03-17 07:10:35.235  1022  1022 D CrashAnrDetector:     d0  0000000000000000  d1  0000000000000000
03-17 07:10:35.235  1022  1022 D CrashAnrDetector:     d2  0000000000000000  d3  0000000000000000
03-17 07:10:35.235  1022  1022 D CrashAnrDetector:     d4  0000000000000000  d5  0000000000000000
03-17 07:10:35.235  1022  1022 D CrashAnrDetector:     d6  0000000000000000  d7  0000000000000000
03-17 07:10:35.235  1022  1022 D CrashAnrDetector:     d8  0000000000000000  d9  0000000000000000
03-17 07:10:35.235  1022  1022 D CrashAnrDetector:     d10 0000000000000000  d11 0000000000000000
03-17 07:10:35.235  1022  1022 D CrashAnrDetector:     d12 0000000000000000  d13 0000000000000000
03-17 07:10:35.235  1022  1022 D CrashAnrDetector:     d14 0000000000000000  d15 0000000000000000
03-17 07:10:35.235  1022  1022 D CrashAnrDetector:     d16 000027b7000027b7  d17 000027b700000000
03-17 07:10:35.235  1022  1022 D CrashAnrDetector:     d18 0001000100010001  d19 0001000100010001
03-17 07:10:35.235  1022  1022 D CrashAnrDetector:     d20 0000000100010001  d21 0000000000000000
03-17 07:10:35.235  1022  1022 D CrashAnrDetector:     d22 0000000000000000  d23 0000000000000000
03-17 07:10:35.235  1022  1022 D CrashAnrDetector:     d24 0000000000000000  d25 0000000000000000
03-17 07:10:35.235  1022  1022 D CrashAnrDetector:     d26 0002000100010001  d27 0002000200020002
03-17 07:10:35.235  1022  1022 D CrashAnrDetector:     d28 0080008000800080  d29 0080008000800080
03-17 07:10:35.235  1022  1022 D CrashAnrDetector:     d30 0800080008000800  d31 0800080008000800
03-17 07:10:35.235  1022  1022 D CrashAnrDetector:     scr 20000012
03-17 07:10:35.235  1022  1022 D CrashAnrDetector: 
03-17 07:10:35.235  1022  1022 D CrashAnrDetector: backtrace:
03-17 07:10:35.235  1022  1022 D CrashAnrDetector:     #00 pc 003d1a34  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (bool ThingIsPermanentAtom<JS::Symbol>(JS::Symbol*)+4)
03-17 07:10:35.235  1022  1022 D CrashAnrDetector:     #01 pc 003d1b2c  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so
03-17 07:10:35.235  1022  1022 D CrashAnrDetector:     #02 pc e5943000  <unknown>
03-17 07:10:35.235  1022  1022 D CrashAnrDetector: 
03-17 07:10:35.235  1022  1022 D CrashAnrDetector: stack:
03-17 07:10:35.235  1022  1022 D CrashAnrDetector:          9368b38c  00000006  
03-17 07:10:35.235  1022  1022 D CrashAnrDetector,:          9368b390  90f5e780  [anon:js-gc-heap]
03-17 07:10:35.235  1022  1022 D CrashAnrDetector:          9368b394  b7a20c80  [heap]
03-17 07:10:35.235  1022  1022 D CrashAnrDetector:          9368b398  942c1b34  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so
03-17 07:10:35.235  1022  1022 D CrashAnrDetector:          9368b39c  b7a20c80  [heap]
03-17 07:10:35.235  1022  1022 D CrashAnrDetector:          9368b3a0  9368b3bc  [stack:4175]
03-17 07:10:35.235  1022  1022 D CrashAnrDetector:          9368b3a4  93fa2258  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (JSScript::markChildren(JSTracer*)+404)
03-17 07:10:35.235  1022  1022 D CrashAnrDetector:          9368b3a8  00000001  
03-17 07:10:35.235  1022  1022 D CrashAnrDetector:          9368b3ac  00000000  
03-17 07:10:35.235  1022  1022 D CrashAnrDetector:          9368b3b0  b7a217b0  [heap]
03-17 07:10:35.235  1022  1022 D CrashAnrDetector:          9368b3b4  00000000  
03-17 07:10:35.235  1022  1022 D CrashAnrDetector:          9368b3b8  00000000  
03-17 07:10:35.235  1022  1022 D CrashAnrDetector:          9368b3bc  b7a20c80  [heap]
03-17 07:10:35.235  1022  1022 D CrashAnrDetector:          9368b3c0  b7a217b0  [heap]
03-17 07:10:35.235  1022  1022 D CrashAnrDetector:          9368b3c4  9440db60  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so
03-17 07:10:35.235  1022  1022 D CrashAnrDetector:          9368b3c8  9368b434  [stack:4175]
03-17 07:10:35.235  1022  1022 D CrashAnrDetector:          9368b3cc  93d88514  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (js::gc::GCRuntime::markConservativeStackRoots(JSTracer*, bool)+1308)
03-17 07:10:35.235  1022  1022 D CrashAnrDetector:          9368b3d0  b7a20c80  [heap]
03-17 07:10:35.235  1022  1022 D CrashAnrDetector:          9368b3d4  b7a204e8  [heap]
03-17 07:10:35.235  1022  1022 D CrashAnrDetector:          9368b3d8  93693000  
03-17 07:10:35.235  1022  1022 D CrashAnrDetector:          9368b3dc  9368b400  [stack:4175]
03-17 07:10:35.235  1022  1022 D CrashAnrDetector:          9368b3e0  9368b3f8  [stack:4175]
03-17 07:10:35.235  1022  1022 D CrashAnrDetector:          9368b3e4  9368b404  [stack:4175]
03-17 07:10:35.235  1022  1022 D CrashAnrDetector:          9368b3e8  943346d4  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so
03-17 07:10:35.235  1022  1022 D CrashAnrDetector:          9368b3ec  9368b408  [stack:4175]
03-17 07:10:35.235  1022  1022 D CrashAnrDetector:          9368b3f0  00000004  
03-17 07:10:35.235  1022  1022 D CrashAnrDetector:          9368b3f4  00000000  
03-17 07:10:35.235  1022  1022 D CrashAnrDetector:          9368b3f8  00000001  
03-17 07:10:35.235  1022  1022 D CrashAnrDetector:          9368b3fc  b7a20c80  [heap]
03-17 07:10:35.235  1022  1022 D CrashAnrDetector:          9368b400  b7a20c80  [heap]
03-17 07:10:35.235  1022  1022 D CrashAnrDetector:          9368b404  929401e0  [anon:js-gc-heap]
03-17 07:10:35.235  1022  1022 D CrashAnrDetector:          9368b408  9368b41c  [stack:4175]
03-17 07:10:35.235  1022  1022 D CrashAnrDetector:     #00  9368b40c  9368b41c  [stack:4175]
03-17 07:10:35.235  1022  1022 D CrashAnrDetector:          9368b410  93692838  [stack:4175]
03-17 07:10:35.235  1022  1022 D CrashAnrDetector:          9368b414  b9bb3cd8  [heap]
03-17 07:10:35.235  1022  1022 D CrashAnrDetector:          9368b418  9368b434  [stack:4175]
03-17 07:10:35.235  1022  1022 D CrashAnrDetector:          9368b41c  93d8506c  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (js::gc::MarkValueRoot(JSTracer*, JS::Value*, char const*)+80)
03-17 07:10:35.235  1022  1022 D CrashAnrDetector:     #01  9368b420  b7a7363c  [heap]
03-17 07:10:35.235  1022  1022 D CrashAnrDetector:          9368b424  00000000  
03-17 07:10:35.235  1022  1022 D CrashAnrDetector:          9368b428  b7a2050c  [heap]
03-17 07:10:35.235  1022  1022 D CrashAnrDetector:          9368b42c  942b5cd8  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so
03-17 07:10:35.235  1022  1022 D CrashAnrDetector:          9368b430  9368b48c  [stack:4175]
03-17 07:10:35.235  1022  1022 D CrashAnrDetector:          9368b434  93d89dcc  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (js::gc::GCRuntime::markRuntime(JSTracer*, js::gc::GCRuntime::TraceOrMarkRuntime, js::gc::GCRuntime::TraceRootsOrUs
03-17 07:10:35.235  1022  1022 D CrashAnrDetector: processName:com.test.thalitest
03-17 07:10:35.235  1022  1022 D CrashAnrDetector: broadcastEvent : com.test.thalitest SYSTEM_TOMBSTONE
03-17 07:10:35.235  1022  1022 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 com.android.server.analytics.data.collection.application.CrashAnrDetector.broadcastEvent:296 com.android.server.analytics.data.collection.application.CrashAnrDetector.processDropBoxEntry:254 com.android.server.analytics.data.collection.application.CrashAnrDetector.access$100:60 com.android.server.analytics.data.collection.application.CrashAnrDetector$1.onReceive:102 
03-17 07:10:35.235  3165  3285 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
03-17 07:10:35.235  3165  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
03-17 07:10:35.235  3165  3285 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
03-17 07:10:35.245  3165  3165 D HeadsetService: Received start request. Starting profile...
03-17 07:10:35.245  3165  3165 D HeadsetService: start()
03-17 07:10:35.245  3165  3165 I BluetoothHeadsetServiceJni: classInitNative: succeeds
03-17 07:10:35.245  1022  1392 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:35.245  1022  1392 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:35.245  1022  1392 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
03-17 07:10:35.245  3165  3285 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
03-17 07:10:35.245  3165  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
03-17 07:10:35.245  3165  3285 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
03-17 07:10:35.245  1022  1507 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:35.245  1022  1507 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:35.245  1022  1507 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
03-17 07:10:35.245  3165  3165 D HeadsetStateMachine: make
03-17 07:10:35.255  3165  3285 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
03-17 07:10:35.255  3165  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
03-17 07:10:35.255  3165  3285 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
03-17 07:10:35.255  3165  3285 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
03-17 07:10:35.255  3165  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
03-17 07:10:35.255  3165  3285 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
03-17 07:10:35.255  3165  3285 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
03-17 07:10:35.255  3165  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
03-17 07:10:35.255  3165  3285 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
03-17 07:10:35.255  3165  3285 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
03-17 07:10:35.255  3165  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
03-17 07:10:35.255  3165  3285 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
03-17 07:10:35.255  3165  3285 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
03-17 07:10:35.255  3165  3165 E HeadsetStateMachine: # of Max HF connection is 2
,03-17 07:10:35.265  1022  3263 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
03-17 07:10:35.275  1022  1129 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:35.275  1022  1129 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:35.275  1022  1129 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
03-17 07:10:35.275  1022  1034 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:35.275   257   450 I SurfaceFlinger: id=11 Removed uhalitest (7/8)
03-17 07:10:35.275  1022  1034 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:35.275  1022  1034 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
03-17 07:10:35.275   257   446 I SurfaceFlinger: id=11 Removed uhalitest (-2/8)
03-17 07:10:35.275  3165  3165 I bluedroid: get_profile_interface handsfree
03-17 07:10:35.275  1022  3213 I BootReceiver: Copying /data/tombstones/tombstone_07 to DropBox (SYSTEM_TOMBSTONE)
03-17 07:10:35.295  1022  1022 D CrashAnrDetector: Build: samsung/a3ultexx/a3ulte:5.0.2/LRX22G/A300FUXXU1BOEC:user/release-keys
03-17 07:10:35.295  1022  1022 D CrashAnrDetector: Hardware: MSM8916
03-17 07:10:35.295  1022  1022 D CrashAnrDetector: Revision: 1
03-17 07:10:35.295  1022  1022 D CrashAnrDetector: Bootloader: A300FUXXU1BOEC
03-17 07:10:35.295  1022  1022 D CrashAnrDetector: Radio: unknown
03-17 07:10:35.295  1022  1022 D CrashAnrDetector: Kernel: Linux version 3.10.49-4866174 (dpi@SWDD6204) (gcc version 4.8 (GCC) ) #1 SMP PREEMPT Fri May 29 20:06:40 KST 2015
03-17 07:10:35.295  1022  1022 D CrashAnrDetector: 
03-17 07:10:35.295  1022  1022 D CrashAnrDetector: *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
03-17 07:10:35.295  1022  1022 D CrashAnrDetector: Build fingerprint: 'samsung/a3ultexx/a3ulte:5.0.2/LRX22G/A300FUXXU1BOEC:user/release-keys'
03-17 07:10:35.295  1022  1022 D CrashAnrDetector: Revision: '1'
03-17 07:10:35.295  1022  1022 D CrashAnrDetector: ABI: 'arm'
03-17 07:10:35.295  1022  1022 D CrashAnrDetector: pid: 3548, tid: 4067, name: Thread-502  >>> com.test.thalitest <<<
03-17 07:10:35.295  1022  1022 D CrashAnrDetector: signal 11 (SIGSEGV), code 1 (SEGV_MAPERR), fault addr 0x0
03-17 07:10:35.295  1022  1022 D CrashAnrDetector:     r0 00000000  r1 9372793c  r2 00000002  r3 00000000
03-17 07:10:35.295  1022  1022 D CrashAnrDetector:     r4 b8aef3c8  r5 00000000  r6 b8aeec58  r7 b8cc7760
03-17 07:10:35.295  1022  1022 D CrashAnrDetector:     r8 b8b7cde4  r9 b8aef3c8  sl b8aeec30  fp 93727934
03-17 07:10:35.295  1022  1022 D CrashAnrDetector:     ip ffffffff  sp 93727924  lr 93c02234  pc 93c02138  cpsr 60000010
03-17 07:10:35.295  1022  1022 D CrashAnrDetector:     d0  0000000000000000  d1  0000000000000000
03-17 07:10:35.295  1022  1022 D CrashAnrDetector:     d2  0000000000000000  d3  0000000000000000
03-17 07:10:35.295  1022  1022 D CrashAnrDetector:     d4  0000000000000000  d5  0000000000000000
03-17 07:10:35.295  1022  1022 D CrashAnrDetector:     d6  0000000000000000  d7  0000000000000000
03-17 07:10:35.295  1022  1022 D CrashAnrDetector:     d8  0000000000000000  d9  0000000000000000
03-17 07:10:35.295  1022  1022 D CrashAnrDetector:     d10 0000000000000000  d11 0000000000000000
03-17 07:10:35.295  1022  1022 D CrashAnrDetector:     d12 0000000000000000  d13 0000000000000000
03-17 07:10:35.295  1022  1022 D CrashAnrDetector:     d14 0000000000000000  d15 0000000000000000
03-17 07:10:35.295  1022  1022 D CrashAnrDetector:     d16 000027b7000027b7  d17 000027b700000000
03-17 07:10:35.295  1022  1022 D CrashAnrDetector:     d18 0001000100010001  d19 0001000100010001
03-17 07:10:35.295  1022  1022 D CrashAnrDetector:     d20 0000000100010001  d21 0000000000000000
03-17 07:10:35.295  1022  1022 D CrashAnrDetector:     d22 0000000000000000  d23 0000000000000000
03-17 07:10:35.295  1022  1022 D CrashAnrDetector:     d24 0000000000000000  d25 0000000000000000
03-17 07:10:35.295  1022  1022 D CrashAnrDetector:     d26 0002000100010001  d27 0002000200020002
03-17 07:10:35.295  1022  1022 D CrashAnrDetector:     d28 0080008000800080  d29 0080008000800080
03-17 07:10:35.295  1022  1022 D CrashAnrDetector:     d30 0800080008000800  d31 0800080008000800
03-17 07:10:35.295  1022  1022 D CrashAnrDetector:     scr 20000013
03-17 07:10:35.295  1022  1022 D CrashAnrDetector: 
03-17 07:10:35.295  1022  1022 D CrashAnrDetector: backtrace:
03-17 07:10:35.295  1022  1022 D CrashAnrDetector:     #00 pc 003d1138  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (bool ThingIsPermanentAtom<JS::Symbol>(JS::Symbol*)+4)
03-17 07:10:35.295  1022  1022 D CrashAnrDetector:     #01 pc 003d1230  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so
03-17 07:10:35.295  1022  1022 D CrashAnrDetector:     #02 pc e5943000  <unknown>
03-17 07:10:35.295  1022  1022 D CrashAnrDetector: 
03-17 07:10:35.295  1022  1022 D CrashAnrDetector: stack:
03-17 07:10:35.295  1022  1022 D CrashAnrDetector:          937278a4  00000000  
03-17 07:10:35.295  1022  1022 D CrashAnrDetector:          937278a8  916fc0a0  [anon:js-gc-heap]
03-17 07:10:35.295  1022  1022 D CrashAnrDetector:          937278ac  b8aef3c8  [heap]
03-17 07:10:35.295  1022  1022 D CrashAnrDetector:          937278b0  b8aef3c8  [heap]
03-17 07:10:35.295  1022  1022 D CrashAnrDetector:          937278b4  00000001  
03-17 07:10:35.295  1022  1022 D CrashAnrDetector:          937278b8  937278d4  [stack:4067]
03-17 07:10:35.295  1022  1022 D CrashAnrDetector:          937278bc  93c01854  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so
03-17 07:10:35.295  1022  1022 D CrashAnrDetector:          937278c0  00000001  
03-17 07:10:35.295  1022  1022 D CrashAnrDetector:          937278c4  00000000  
03-17 07:10:35.295  1022  1022 D CrashAnrDetector:          937278c8  b8aefef8  [heap]
03-17 07:10:35.295  1022  1022 D CrashAnrDetector:          937278cc  00000000  
03-17 07:10:35.295  1022  1022 D CrashAnrDetector:          937278d0  00000000  
03-17 07:10:35.295  1022  1022 D CrashAnrDetector:          937278d4  b8aef3c8  [heap]
03-17 07:10:35.295  1022  1022 D CrashAnrDetector:          937278d8  b8aefef8  [heap]
03-17 07:10:35.295  1022  1022 D CrashAnrDetector:          937278dc  9428db60  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so
03-17 07:10:35.295  1022  1022 D CrashAnrDetector:          937278e0  9372794c  [stack:4067]
03-17 07:10:35.295  1022  1022 D CrashAnrDetector:          937278e4  93c08c18  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (js::gc::GCRuntime::markConservativeStackRoots(JSTracer*, bool)+1308)
03-17 07:10:35.295  1022  1022 D CrashAnrDetector:          937278e8  b8aef3c8  [heap]
03-17 07:10:35.295  1022  1022 D CrashAnrDetector:          937278ec  b8aeec30  [heap]
03-17 07:10:35.295  1022  1022 D CrashAnrDetector:          937278f0  9372d000  
03-17 07:10:35.295  1022  1022 D CrashAnrDetector:          937278f4  93727918  [stack:4067]
03-17 07:10:35.295  1022  1022 D CrashAnrDetector:          937278f8  93727910  [stack:4067]
03-17 07:10:35.295  1022  1022 D CrashAnrDetector:          937278fc  9372791c  [stack:4067]
03-17 07:10:35.295  1022  1022 D CrashAnrDetector:          93727900  941b4dcc  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so
03-17 07:10:35.295  1022  1022 D CrashAnrDetector:          93727904  93727920  [stack:4067]
03-17 07:10:35.295  1022  1022 D CrashAnrDetector:          93727908  00000004  
03-17 07:10:35.295  1022  1022 D CrashAnrDetector:          9372790c  00000000  
03-17 07:10:35.295  1022  1022 D CrashAnrDetector:          93727910  00000001  
03-17 07:10:35.295  1022  1022 D CrashAnrDetector:          93727914  b8aef3c8  [heap]
03-17 07:10:35.295  1022  1022 D CrashAnrDetector:          93727918  908b3a60  [anon:js-gc-heap]
03-17 07:10:35.295  1022  1022 D CrashAnrDetector:          9372791c  b8aeec58  [heap]
03-17 07:10:35.295  1022  1022 D CrashAnrDetector:          93727920  93727934  [stack:4067]
03-17 07:10:35.295  1022  1022 D CrashAnrDetector:     #00  93727924  93727934  [stack:4067]
03-17 07:10:35.295  1022  1022 D CrashAnrDetector:          93727928  9372c838  [stack:4067]
03-17 07:10:35.295  1022  1022 D CrashAnrDetector:          9372792c  b8cc6890  [heap]
03-17 07:10:35.295  1022  1022 D CrashAnrDetector:          93727930  9372794c  [stack:4067]
03-17 07:10:35.295  1022  1022 D CrashAnrDetector:          93727934  93c05770  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (js::gc::MarkValueRoot(JSTracer*, JS::Value*, char const*)+80)
03-17 07:10:35.295  1022  1022 D CrashAnrDetector:     #01  93727938  b8b7cde4  [heap]
03-17 07:10:35.295  1022  1022 D CrashAnrDetector:          9372793c  00000000  
03-17 07:10:35.295  1022  1022 D CrashAnrDetector:          93727940  b8aeec54  [heap]
03-17 07:10:35.295  1022  1022 D CrashAnrDetector:          93727944  941363d0  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so
03-17 07:10:35.295  1022  1022 D CrashAnrDetector:          93727948  937279a4  [stack:4067]
03-17 07:10:35.295  1022  1022 D CrashAnrDetector:          9372794c  93c0a4d0  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (js::gc::GCRuntime::markRuntime(JSTracer*, js::gc::GCRuntime::TraceOrMarkRuntime, js::gc::GCRuntime::TraceRootsOrUsedSaved)+1452)
03-17 07:10:35.295  1022  1022 D CrashAnrDetector:          93727950  00000000  
03-17 07:10:35.295  1022  1022 D CrashAnrDetector:          93727954  9372796c  [stack:4067]
03-17 07:10:35.295  1022  1022 D CrashAnrDetector:     
03-17 07:10:35.295  1022  1022 D CrashAnrDetector: processName:com.test.thalitest
03-17 07:10:35.295  1022  1022 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 com.android.server.analytics.data.collection.application.CrashAnrDetector.broadcastEvent:296 com.android.server.analytics.data.collection.application.CrashAnrDetector.processDropBoxEntry:254 com.android.server.analytics.data.collection.application.CrashAnrDetector.access$100:60 com.android.server.analytics.data.collection.application.CrashAnrDetector$1.onReceive:102 
03-17 07:10:35.295  1022  1022 D CrashAnrDetector: broadcastEvent : com.test.thalitest SYSTEM_TOMBSTONE
,03-17 07:10:35.305  1349  1349 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
03-17 07:10:35.325  1022  3213 I BootReceiver: Copying /data/tombstones/tombstone_08 to DropBox (SYSTEM_TOMBSTONE)
03-17 07:10:35.335  1022  3263 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
03-17 07:10:35.335  3165  3165 I DualScoManager: Instantiating Dual Sco Manager
03-17 07:10:35.335  3165  3165 I DualScoManager: Set HeadsetServiceHelper
03-17 07:10:35.335  3165  3165 D BluetoothAtMessage: createCMTIContentObservers
03-17 07:10:35.335  1022  1667 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
03-17 07:10:35.335  1022  1667 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-17 07:10:35.345  1022  1667 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-17 07:10:35.345  1022  1667 D SettingsProvider: selectionArgs: false
03-17 07:10:35.345  1022  1667 D SettingsProvider: selectionArgs: 1002
03-17 07:10:35.345  1022  1667 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-17 07:10:35.345  1022  1667 D SettingsProvider: ret = -1
,03-17 07:10:35.345  1022  1667 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,03-17 07:10:35.355  3165  3300 D HeadsetStateMachine: Enter Disconnected: -2
,03-17 07:10:35.355  3165  3165 D HeadsetService: mStartError = false
03-17 07:10:35.355  3165  3165 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f4bc31e
03-17 07:10:35.355  1022  1033 I art     : Background sticky concurrent mark sweep GC freed 34125(2MB) AllocSpace objects, 98(8MB) LOS objects, 25% free, 24MB/33MB, paused 2.739ms total 123.742ms
,03-17 07:10:35.355  3165  3300 D HeadsetStateMachine: Clear mHeadsetBrsf
03-17 07:10:35.355  3165  3300 D HeadsetStateMachine: map size, before remove : 0
03-17 07:10:35.355  3165  3300 D HeadsetStateMachine: map size, after remove: 0
,03-17 07:10:35.365  3165  3165 D A2dpService: Received start request. Starting profile...
03-17 07:10:35.365  3165  3165 D A2dpService: start()
,03-17 07:10:35.365  3165  3165 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,03-17 07:10:35.365  3165  3165 I bluedroid: get_profile_interface avrcp
03-17 07:10:35.365  1206  1206 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 07:10:35.365  1827  1827 D SamsungIME: Dismiss ExpandCandiate
,03-17 07:10:35.365  1022  1022 D CrashAnrDetector: Build: samsung/a3ultexx/a3ulte:5.0.2/LRX22G/A300FUXXU1BOEC:user/release-keys
03-17 07:10:35.365  1022  1022 D CrashAnrDetector: Hardware: MSM8916
03-17 07:10:35.365  1022  1022 D CrashAnrDetector: Revision: 1
03-17 07:10:35.365  1022  1022 D CrashAnrDetector: Bootloader: A300FUXXU1BOEC
03-17 07:10:35.365  1022  1022 D CrashAnrDetector: Radio: unknown
03-17 07:10:35.365  1022  1022 D CrashAnrDetector: Kernel: Linux version 3.10.49-4866174 (dpi@SWDD6204) (gcc version 4.8 (GCC) ) #1 SMP PREEMPT Fri May 29 20:06:40 KST 2015
03-17 07:10:35.365  1022  1022 D CrashAnrDetector: 
03-17 07:10:35.365  1022  1022 D CrashAnrDetector: *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
03-17 07:10:35.365  1022  1022 D CrashAnrDetector: Build fingerprint: 'samsung/a3ultexx/a3ulte:5.0.2/LRX22G/A300FUXXU1BOEC:user/release-keys'
03-17 07:10:35.365  1022  1022 D CrashAnrDetector: Revision: '1'
03-17 07:10:35.365  1022  1022 D CrashAnrDetector: ABI: 'arm'
03-17 07:10:35.365  1022  1022 D CrashAnrDetector: pid: 4389, tid: 4508, name: Thread-702  >>> com.test.thalitest <<<
03-17 07:10:35.365  1022  1022 D CrashAnrDetector: signal 11 (SIGSEGV), code 1 (SEGV_MAPERR), fault addr 0x0
03-17 07:10:35.365  1022  1022 D CrashAnrDetector:     r0 00000000  r1 9ede682c  r2 00000002  r3 00000000
03-17 07:10:35.365  1022  1022 D CrashAnrDetector:     r4 b7f0c840  r5 00000000  r6 b7f0c0d0  r7 b986b2f8
03-17 07:10:35.365  1022  1022 D CrashAnrDetector:     r8 b7de4664  r9 b7f0c840  sl b7f0c0a8  fp 9ede6824
03-17 07:10:35.365  1022  1022 D CrashAnrDetector:     ip ffffffff  sp 9ede6814  lr 9f2cfb30  pc 9f2cfa34  cpsr 600f0010
03-17 07:10:35.365  1022  1022 D CrashAnrDetector:     d0  0000000000000000  d1  0000000000000000
03-17 07:10:35.365  1022  1022 D CrashAnrDetector:     d2  0000000000000000  d3  0000000000000000
03-17 07:10:35.365  1022  1022 D CrashAnrDetector:     d4  0000000000000000  d5  0000000000000000
03-17 07:10:35.365  1022  1022 D CrashAnrDetector:     d6  0000000000000000  d7  0000000000000000
03-17 07:10:35.365  1022  1022 D CrashAnrDetector:     d8  0000000000000000  d9  0000000000000000
03-17 07:10:35.365  1022  1022 D CrashAnrDetector:     d10 0000000000000000  d11 0000000000000000
03-17 07:10:35.365  1022  1022 D CrashAnrDetector:     d12 0000000000000000  d13 0000000000000000
03-17 07:10:35.365  1022  1022 D CrashAnrDetector:     d14 0000000000000000  d15 0000000000000000
03-17 07:10:35.365  1022  1022 D CrashAnrDetector:     d16 0000000000000000  d17 000027b700000000
03-17 07:10:35.365  1022  1022 D CrashAnrDetector:     d18 0001000100010001  d19 0001000100010001
03-17 07:10:35.365  1022  1022 D CrashAnrDetector:     d20 0000000100010001  d21 0000000000000000
03-17 07:10:35.365  1022  1022 D CrashAnrDetector:     d22 0000000000000000  d23 0000000000000000
03-17 07:10:35.365  1022  1022 D CrashAnrDetector:     d24 0000000000000000  d25 0000000000000000
03-17 07:10:35.365  1022  1022 D CrashAnrDetector:     d26 0002000100010001  d27 0002000200020002
03-17 07:10:35.365  1022  1022 D CrashAnrDetector:     d28 0080008000800080  d29 0080008000800080
03-17 07:10:35.365  1022  1022 D CrashAnrDetector:     d30 0800080008000800  d31 0800080008000800
03-17 07:10:35.365  1022  1022 D CrashAnrDetector:     scr 20000013
03-17 07:10:35.365  1022  1022 D CrashAnrDetector: 
03-17 07:10:35.365  1022  1022 D CrashAnrDetector: backtrace:
03-17 07:10:35.365  1022  1022 D CrashAnrDetector:     #00 pc 003d1a34  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (bool ThingIsPermanentAtom<JS::Symbol>(JS::Symbol*)+4)
03-17 07:10:35.365  1022  1022 D CrashAnrDetector:     #01 pc 003d1b2c  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so
03-17 07:10:35.365  1022  1022 D CrashAnrDetector:     #02 pc e5943000  <unknown>
03-17 07:10:35.365  1022  1022 D CrashAnrDetector: 
03-17 07:10:35.365  1022  1022 D CrashAnrDetector: stack:
03-17 07:10:35.365  1022  1022 D CrashAnrDetector:          9ede6794  00000000  
03-17 07:10:35.365  1022  1022 D CrashAnrDetector,:          9ede6798  90dfc0a0  [anon:js-gc-heap]
03-17 07:10:35.365  1022  1022 D CrashAnrDetector:          9ede679c  b7f0c840  [heap]
03-17 07:10:35.365  1022  1022 D CrashAnrDetector:          9ede67a0  00000001  
03-17 07:10:35.365  1022  1022 D CrashAnrDetector:          9ede67a4  90d6d0d0  [anon:js-gc-heap]
03-17 07:10:35.365  1022  1022 D CrashAnrDetector:          9ede67a8  9ede67c4  [stack:4508]
03-17 07:10:35.365  1022  1022 D CrashAnrDetector:          9ede67ac  9f2cf12c  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so
03-17 07:10:35.365  1022  1022 D CrashAnrDetector:          9ede67b0  00000001  
03-17 07:10:35.365  1022  1022 D CrashAnrDetector:          9ede67b4  00000000  
03-17 07:10:35.365  1022  1022 D CrashAnrDetector:          9ede67b8  b7f0d370  [heap]
03-17 07:10:35.365  1022  1022 D CrashAnrDetector:          9ede67bc  00000000  
03-17 07:10:35.365  1022  1022 D CrashAnrDetector:          9ede67c0  00000000  
03-17 07:10:35.365  1022  1022 D CrashAnrDetector:          9ede67c4  b7f0c840  [heap]
03-17 07:10:35.365  1022  1022 D CrashAnrDetector:          9ede67c8  b7f0d370  [heap]
03-17 07:10:35.365  1022  1022 D CrashAnrDetector:          9ede67cc  9f95bb60  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so
03-17 07:10:35.365  1022  1022 D CrashAnrDetector:          9ede67d0  9ede683c  [stack:4508]
03-17 07:10:35.365  1022  1022 D CrashAnrDetector:          9ede67d4  9f2d6514  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (js::gc::GCRuntime::markConservativeStackRoots(JSTracer*, bool)+1308)
03-17 07:10:35.365  1022  1022 D CrashAnrDetector:          9ede67d8  b7f0c840  [heap]
03-17 07:10:35.365  1022  1022 D CrashAnrDetector:          9ede67dc  b7f0c0a8  [heap]
03-17 07:10:35.365  1022  1022 D CrashAnrDetector:          9ede67e0  9edfa000  
03-17 07:10:35.365  1022  1022 D CrashAnrDetector:          9ede67e4  9ede6808  [stack:4508]
03-17 07:10:35.365  1022  1022 D CrashAnrDetector:          9ede67e8  9ede6800  [stack:4508]
03-17 07:10:35.365  1022  1022 D CrashAnrDetector:          9ede67ec  9ede680c  [stack:4508]
03-17 07:10:35.365  1022  1022 D CrashAnrDetector:          9ede67f0  9f8826d4  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so
03-17 07:10:35.365  1022  1022 D CrashAnrDetector:          9ede67f4  9ede6810  [stack:4508]
03-17 07:10:35.365  1022  1022 D CrashAnrDetector:          9ede67f8  00000004  
03-17 07:10:35.365  1022  1022 D CrashAnrDetector:          9ede67fc  00000000  
03-17 07:10:35.365  1022  1022 D CrashAnrDetector:          9ede6800  00000001  
03-17 07:10:35.365  1022  1022 D CrashAnrDetector:          9ede6804  b7f0c840  [heap]
03-17 07:10:35.365  1022  1022 D CrashAnrDetector:          9ede6808  91951af0  [anon:js-gc-heap]
03-17 07:10:35.365  1022  1022 D CrashAnrDetector:          9ede680c  b7f0c0d0  [heap]
03-17 07:10:35.365  1022  1022 D CrashAnrDetector:          9ede6810  9ede6824  [stack:4508]
03-17 07:10:35.365  1022  1022 D CrashAnrDetector:     #00  9ede6814  9ede6824  [stack:4508]
03-17 07:10:35.365  1022  1022 D CrashAnrDetector:          9ede6818  9edf9838  [stack:4508]
03-17 07:10:35.365  1022  1022 D CrashAnrDetector:          9ede681c  b9866048  [heap]
03-17 07:10:35.365  1022  1022 D CrashAnrDetector:          9ede6820  9ede683c  [stack:4508]
03-17 07:10:35.365  1022  1022 D CrashAnrDetector:          9ede6824  9f2d306c  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (js::gc::MarkValueRoot(JSTracer*, JS::Value*, char const*)+80)
03-17 07:10:35.365  1022  1022 D CrashAnrDetector:     #01  9ede6828  b7de4664  [heap]
03-17 07:10:35.365  1022  1022 D CrashAnrDetector:          9ede682c  00000000  
03-17 07:10:35.365  1022  1022 D CrashAnrDetector:          9ede6830  b7f0c0cc  [heap]
03-17 07:10:35.365  1022  1022 D CrashAnrDetector:          9ede6834  9f803cd8  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so
03-17 07:10:35.365  1022  1022 D CrashAnrDetector:          9ede6838  9ede6894  [stack:4508]
03-17 07:10:35.365  1022  1022 D CrashAnrDetector:          9ede683c  9f2d7dcc  /data/app/com.t,est.thalitest-1/lib/arm/libjxcore.so (js::gc::GCRuntime::markRuntime(JSTracer*, js::gc::GCRuntime::TraceOrMarkRuntime, js::gc::GCRuntime::TraceRootsOrUsedSaved)+1452)
03-17 07:10:35.365  1022  1022 D CrashAnrDetector:          9ede6840  00000000  
03-17 07:10:35.365  1022  1022 D CrashAnrDetector:          9ede6844  9ede685c  [stack
03-17 07:10:35.365  1022  1022 D CrashAnrDetector: processName:com.test.thalitest
03-17 07:10:35.365  1022  1022 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 com.android.server.analytics.data.collection.application.CrashAnrDetector.broadcastEvent:296 com.android.server.analytics.data.collection.application.CrashAnrDetector.processDropBoxEntry:254 com.android.server.analytics.data.collection.application.CrashAnrDetector.access$100:60 com.android.server.analytics.data.collection.application.CrashAnrDetector$1.onReceive:102 
03-17 07:10:35.365  1022  1022 D CrashAnrDetector: broadcastEvent : com.test.thalitest SYSTEM_TOMBSTONE
03-17 07:10:35.375  1022  1022 D BluetoothA2dp: Proxy object connected
03-17 07:10:35.375  1022  1902 D SettingsProvider: name = block_emergency_message
03-17 07:10:35.385  3165  3165 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
03-17 07:10:35.385  3146  3146 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
03-17 07:10:35.405  1022  1392 D SettingsProvider: name = safetycare_geolookout_registering
,03-17 07:10:35.405  1022  3213 I BootReceiver: Copying /data/tombstones/tombstone_09 to DropBox (SYSTEM_TOMBSTONE)
,03-17 07:10:35.405  1022  3263 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
,03-17 07:10:35.415  3165  3165 I Avrcp   :  Updating now playing list upon AVRCP Start
,03-17 07:10:35.415  3165  3305 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,03-17 07:10:35.415  3165  3165 I BluetoothA2dpServiceJni: classInitNative: succeeds
03-17 07:10:35.415  3165  3165 D A2dpStateMachine: make
,03-17 07:10:35.415  1206  1206 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 07:10:35.425  3165  3165 I bluedroid: get_profile_interface a2dp
,03-17 07:10:35.425  1022  1597 I ActivityManager: Killing 2631:com.sec.pcw.device/1000 (adj 15): empty #31
,03-17 07:10:35.425  1022  1022 D CrashAnrDetector: Build: samsung/a3ultexx/a3ulte:5.0.2/LRX22G/A300FUXXU1BOEC:user/release-keys
03-17 07:10:35.425  1022  1022 D CrashAnrDetector: Hardware: MSM8916
03-17 07:10:35.425  1022  1022 D CrashAnrDetector: Revision: 1
03-17 07:10:35.425  1022  1022 D CrashAnrDetector: Bootloader: A300FUXXU1BOEC
03-17 07:10:35.425  1022  1022 D CrashAnrDetector: Radio: unknown
03-17 07:10:35.425  1022  1022 D CrashAnrDetector: Kernel: Linux version 3.10.49-4866174 (dpi@SWDD6204) (gcc version 4.8 (GCC) ) #1 SMP PREEMPT Fri May 29 20:06:40 KST 2015
03-17 07:10:35.425  1022  1022 D CrashAnrDetector: 
03-17 07:10:35.425  1022  1022 D CrashAnrDetector: *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
03-17 07:10:35.425  1022  1022 D CrashAnrDetector: Build fingerprint: 'samsung/a3ultexx/a3ulte:5.0.2/LRX22G/A300FUXXU1BOEC:user/release-keys'
03-17 07:10:35.425  1022  1022 D CrashAnrDetector: Revision: '1'
03-17 07:10:35.425  1022  1022 D CrashAnrDetector: ABI: 'arm'
03-17 07:10:35.425  1022  1022 D CrashAnrDetector: pid: 4273, tid: 4624, name: Thread-667  >>> com.test.thalitest <<<
03-17 07:10:35.425  1022  1022 D CrashAnrDetector: signal 11 (SIGSEGV), code 1 (SEGV_MAPERR), fault addr 0x0
03-17 07:10:35.425  1022  1022 D CrashAnrDetector:     r0 00000000  r1 920d54e4  r2 00000002  r3 00000000
03-17 07:10:35.425  1022  1022 D CrashAnrDetector:     r4 b84d6800  r5 00000000  r6 b84d6090  r7 ba6fdeb8
03-17 07:10:35.425  1022  1022 D CrashAnrDetector:     r8 b8196a74  r9 b84d6800  sl b84d6068  fp 920d54dc
03-17 07:10:35.425  1022  1022 D CrashAnrDetector:     ip ffffffff  sp 920d54cc  lr 925b1b30  pc 925b1a34  cpsr 60000010
03-17 07:10:35.425  1022  1022 D CrashAnrDetector:     d0  0000000000000000  d1  0000000000000000
03-17 07:10:35.425  1022  1022 D CrashAnrDetector:     d2  0000000000000000  d3  0000000000000000
03-17 07:10:35.425  1022  1022 D CrashAnrDetector:     d4  0000000000000000  d5  0000000000000000
03-17 07:10:35.425  1022  1022 D CrashAnrDetector:     d6  0000000000000000  d7  0000000000000000
03-17 07:10:35.425  1022  1022 D CrashAnrDetector:     d8  0000000000000000  d9  0000000000000000
03-17 07:10:35.425  1022  1022 D CrashAnrDetector:     d10 0000000000000000  d11 0000000000000000
03-17 07:10:35.425  1022  1022 D CrashAnrDetector:     d12 0000000000000000  d13 0000000000000000
03-17 07:10:35.425  1022  1022 D CrashAnrDetector:     d14 0000000000000000  d15 0000000000000000
03-17 07:10:35.425  1022  1022 D CrashAnrDetector:     d16 000027b7000027b7  d17 000027b700000000
03-17 07:10:35.425  1022  1022 D CrashAnrDetector:     d18 0001000100010001  d19 0001000100010001
03-17 07:10:35.425  1022  1022 D CrashAnrDetector:     d20 0000000100010001  d21 0000000000000000
03-17 07:10:35.425  1022  1022 D CrashAnrDetector:     d22 0000000000000000  d23 0000000000000000
03-17 07:10:35.425  1022  1022 D CrashAnrDetector:     d24 0000000000000000  d25 0000000000000000
03-17 07:10:35.425  1022  1022 D CrashAnrDetector:     d26 0002000100010001  d27 0002000200020002
03-17 07:10:35.425  1022  1022 D CrashAnrDetector:     d28 0080008000800080  d29 0080008000800080
03-17 07:10:35.425  1022  1022 D CrashAnrDetector:     d30 0800080008000800  d31 0800080008000800
03-17 07:10:35.425  1022  1022 D CrashAnrDetector:     scr 20000013
03-17 07:10:35.425  1022  1022 D CrashAnrDetector: 
03-17 07:10:35.425  1022  1022 D CrashAnrDetector: backtrace:
03-17 07:10:35.425  1022  1022 D CrashAnrDetector:     #00 pc 003d1a34  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (bool ThingIsPermanentAtom<JS::Symbol>(JS::Symbol*)+4)
03-17 07:10:35.425  1022  1022 D CrashAnrDetector:     #01 pc 003d1b2c  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so
03-17 07:10:35.425  1022  1022 D CrashAnrDetector:     #02 pc e5943000  <unknown>
03-17 07:10:35.425  1022  1022 D CrashAnrDetector: 
03-17 07:10:35.425  1022  1022 D CrashAnrDetector: stack:
03-17 07:10:35.425  1022  1022 D CrashAnrDetector:          920d544c  00000000  
03-17 07:10:35.425  1022  1022 D CrashAnrDetector,:          920d5450  8fcfc0a0  [anon:js-gc-heap]
03-17 07:10:35.425  1022  1022 D CrashAnrDetector:          920d5454  b84d6800  [heap]
03-17 07:10:35.425  1022  1022 D CrashAnrDetector:          920d5458  00000001  
03-17 07:10:35.425  1022  1022 D CrashAnrDetector:          920d545c  8fced280  [anon:js-gc-heap]
03-17 07:10:35.425  1022  1022 D CrashAnrDetector:          920d5460  920d547c  [stack:4624]
03-17 07:10:35.425  1022  1022 D CrashAnrDetector:          920d5464  925b112c  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so
03-17 07:10:35.425  1022  1022 D CrashAnrDetector:          920d5468  00000001  
03-17 07:10:35.425  1022  1022 D CrashAnrDetector:          920d546c  00000000  
03-17 07:10:35.425  1022  1022 D CrashAnrDetector:          920d5470  b84d7330  [heap]
03-17 07:10:35.425  1022  1022 D CrashAnrDetector:          920d5474  00000000  
03-17 07:10:35.425  1022  1022 D CrashAnrDetector:          920d5478  00000000  
03-17 07:10:35.425  1022  1022 D CrashAnrDetector:          920d547c  b84d6800  [heap]
03-17 07:10:35.425  1022  1022 D CrashAnrDetector:          920d5480  b84d7330  [heap]
03-17 07:10:35.425  1022  1022 D CrashAnrDetector:          920d5484  92c3db60  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so
03-17 07:10:35.425  1022  1022 D CrashAnrDetector:          920d5488  920d54f4  [stack:4624]
03-17 07:10:35.425  1022  1022 D CrashAnrDetector:          920d548c  925b8514  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (js::gc::GCRuntime::markConservativeStackRoots(JSTracer*, bool)+1308)
03-17 07:10:35.425  1022  1022 D CrashAnrDetector:          920d5490  b84d6800  [heap]
03-17 07:10:35.425  1022  1022 D CrashAnrDetector:          920d5494  b84d6068  [heap]
03-17 07:10:35.425  1022  1022 D CrashAnrDetector:          920d5498  920dc000  
03-17 07:10:35.425  1022  1022 D CrashAnrDetector:          920d549c  920d54c0  [stack:4624]
03-17 07:10:35.425  1022  1022 D CrashAnrDetector:          920d54a0  920d54b8  [stack:4624]
03-17 07:10:35.425  1022  1022 D CrashAnrDetector:          920d54a4  920d54c4  [stack:4624]
03-17 07:10:35.425  1022  1022 D CrashAnrDetector:          920d54a8  92b646d4  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so
03-17 07:10:35.425  1022  1022 D CrashAnrDetector:          920d54ac  920d54c8  [stack:4624]
03-17 07:10:35.425  1022  1022 D CrashAnrDetector:          920d54b0  00000004  
03-17 07:10:35.425  1022  1022 D CrashAnrDetector:          920d54b4  00000000  
03-17 07:10:35.425  1022  1022 D CrashAnrDetector:          920d54b8  00000001  
03-17 07:10:35.425  1022  1022 D CrashAnrDetector:          920d54bc  b84d6800  [heap]
03-17 07:10:35.425  1022  1022 D CrashAnrDetector:          920d54c0  901e6eb0  [anon:js-gc-heap]
03-17 07:10:35.425  1022  1022 D CrashAnrDetector:          920d54c4  b84d6090  [heap]
03-17 07:10:35.425  1022  1022 D CrashAnrDetector:          920d54c8  920d54dc  [stack:4624]
03-17 07:10:35.425  1022  1022 D CrashAnrDetector:     #00  920d54cc  920d54dc  [stack:4624]
03-17 07:10:35.425  1022  1022 D CrashAnrDetector:          920d54d0  920db838  [stack:4624]
03-17 07:10:35.425  1022  1022 D CrashAnrDetector:          920d54d4  ba6fb020  [heap]
03-17 07:10:35.425  1022  1022 D CrashAnrDetector:          920d54d8  920d54f4  [stack:4624]
03-17 07:10:35.425  1022  1022 D CrashAnrDetector:          920d54dc  925b506c  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (js::gc::MarkValueRoot(JSTracer*, JS::Value*, char const*)+80)
03-17 07:10:35.425  1022  1022 D CrashAnrDetector:     #01  920d54e0  b8196a74  [heap]
03-17 07:10:35.425  1022  1022 D CrashAnrDetector:          920d54e4  00000000  
03-17 07:10:35.425  1022  1022 D CrashAnrDetector:          920d54e8  b84d608c  [heap]
03-17 07:10:35.425  1022  1022 D CrashAnrDetector:          920d54ec  92ae5cd8  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so
03-17 07:10:35.425  1022  1022 D CrashAnrDetector:          920d54f0  920d554c  [stack:4624]
03-17 07:10:35.425  1022  1022 D CrashAnrDetector:          920d54f4  925b9dcc  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (js::gc::GCRuntime::markRuntime(JSTracer*, js::gc::GCRuntime::TraceOrMarkRuntime, js::gc::GCRuntime::TraceRootsOrUsedSaved)+1452)
03-17 07:10:35.425  1022  1022 D CrashAnrDetector:          920d54f8  00000000  
03-17 07:10:35.425  1022  1022 D CrashAnrDetector:          920d54fc  920d5514  [stack
03-17 07:10:35.425  1022  1022 D CrashAnrDetector: processName:com.test.thalitest
03-17 07:10:35.425  1022  1022 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 com.android.server.analytics.data.collection.application.CrashAnrDetector.broadcastEvent:296 com.android.server.analytics.data.collection.application.CrashAnrDetector.processDropBoxEntry:254 com.android.server.analytics.data.collection.application.CrashAnrDetector.access$100:60 com.android.server.analytics.data.collection.application.CrashAnrDetector$1.onReceive:102 
03-17 07:10:35.425  1022  1022 D CrashAnrDetector: broadcastEvent : com.test.thalitest SYSTEM_TOMBSTONE
03-17 07:10:35.425  3165  3307 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
03-17 07:10:35.425  3165  3165 E bt-btif : warning : media task started media_task_refcnt 1 
03-17 07:10:35.425  3165  3165 D A2dpService: mStartError = false
03-17 07:10:35.425  3165  3165 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f4bc31e
03-17 07:10:35.425  3165  3165 E BluetoothAdapterService(256623390): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
03-17 07:10:35.435  3165  3306 D A2dpStateMachine: Enter Disconnected: -2
03-17 07:10:35.435  2141  3272 D ConnectivityManager: CallingUid : 10011, CallingPid : 2141
03-17 07:10:35.435  1206  1206 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
03-17 07:10:35.435  1022  1902 D ConnectivityService: listenForNetwork for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
03-17 07:10:35.435  3165  3305 D BluetoothMediaBrowser: no now playing list
03-17 07:10:35.435  3165  3305 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
03-17 07:10:35.435  1022  1136 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 502]
03-17 07:10:35.435  1022  1136 D ConnectivityService: apparently satisfied.  currentScore=60
03-17 07:10:35.435  1022  1136 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI_P2P () - 501]
03-17 07:10:35.435  2141  3309 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,03-17 07:10:35.475  3165  3165 I BluetoothHidServiceJni: classInitNative: succeeds
03-17 07:10:35.475  3165  3165 D HidService: Received start request. Starting profile...
03-17 07:10:35.475  3165  3165 D HidService: start()
03-17 07:10:35.475  3165  3165 I bluedroid: get_profile_interface hidhost
03-17 07:10:35.475  3165  3165 D HidService: setHidService(): set to: null
03-17 07:10:35.475  3165  3165 D HidService: mStartError = false
03-17 07:10:35.475  3165  3165 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f4bc31e
03-17 07:10:35.475  3165  3165 I BluetoothHealthServiceJni: classInitNative: succeeds
03-17 07:10:35.485  3165  3165 D HealthService: Received start request. Starting profile...
03-17 07:10:35.485  3165  3165 D HealthService: start()
03-17 07:10:35.485  3165  3165 I bluedroid: get_profile_interface health
03-17 07:10:35.485  3165  3165 D HealthService: mStartError = false
03-17 07:10:35.485  3165  3165 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f4bc31e
03-17 07:10:35.485  3165  3165 I BluetoothPanServiceJni: classInitNative(L105): succeeds
03-17 07:10:35.495  3165  3165 D PanService: Received start request. Starting profile...
03-17 07:10:35.495  3165  3165 D PanService: start()
03-17 07:10:35.495  3165  3165 D BluetoothPanServiceJni: initializeNative(L110): pan
03-17 07:10:35.495  3165  3165 I bluedroid: get_profile_interface pan
03-17 07:10:35.495  3165  3165 D PanService: mStartError = false
03-17 07:10:35.495  3165  3165 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f4bc31e
03-17 07:10:35.495  3165  3165 D BluetoothMapService: Received start request. Starting profile...
03-17 07:10:35.495  3165  3165 D BluetoothMapService: start()
03-17 07:10:35.495  3165  3165 D BluetoothMapService: mStartError = false
03-17 07:10:35.495  3165  3165 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f4bc31e
03-17 07:10:35.495  3165  3165 I BluetoothSAPServiceJni: classInitNative(L204): succeeds
,03-17 07:10:35.505  3165  3165 D SapService: Received start request. Starting profile...
03-17 07:10:35.505  3165  3165 D SapService: start()
03-17 07:10:35.505  3165  3165 D BluetoothSAPServiceJni: initializeNative(L209): sap
03-17 07:10:35.505  3165  3165 I bluedroid: get_profile_interface sap
03-17 07:10:35.505  3165  3165 D SapService: mStartError = false
03-17 07:10:35.505  3165  3165 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f4bc31e
,03-17 07:10:35.505  3165  3165 D HeadsetStateMachine: Try to query the phonestate on bind
,03-17 07:10:35.505  3146  3294 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
03-17 07:10:35.505  3146  3294 I chromium: 
,03-17 07:10:35.515  1461  3299 I Telecom : BluetoothPhoneService: queryPhoneState
,03-17 07:10:35.515  1461  1461 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
,03-17 07:10:35.515  1461  1461 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,03-17 07:10:35.525  1461  1461 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
,03-17 07:10:35.525  1827  1827 I SamsungIME: getDebugLevel  : 0x4f4c
,03-17 07:10:35.525  1461  1461 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
,03-17 07:10:35.535  1461  1461 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,03-17 07:10:35.545  1461  1461 W BluetoothHeadset: Proxy not attached to service
,03-17 07:10:35.545  1461  3299 I Telecom : BluetoothPhoneService: Result of Message : true
,03-17 07:10:35.545  3165  3165 D HeadsetStateMachine: Proxy object connected
,03-17 07:10:35.545  3165  3165 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
03-17 07:10:35.545  3165  3165 D HeadsetPhoneState: sendDeviceDataStateChanged
03-17 07:10:35.545  3165  3300 D HeadsetStateMachine: Disconnected process message: 11
03-17 07:10:35.545  3165  3165 D HeadsetPhoneState: Signal level : previous=0 curr=0
03-17 07:10:35.545  3165  3300 D HeadsetStateMachine: Disconnected process message: 18
03-17 07:10:35.545  3165  3165 E BluetoothAdapterService(256623390): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
03-17 07:10:35.545  3165  3165 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-17 07:10:35.545  3165  3165 D BluetoothA2dp: Proxy object connected
03-17 07:10:35.545  3165  3300 D HeadsetStateMachine: Disconnected process message: 10
03-17 07:10:35.545  3165  3165 D BluetoothAdapterService: Bluetooth A2dp source service connected
03-17 07:10:35.555  3165  3165 E BluetoothAdapterService(256623390): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
03-17 07:10:35.555  3165  3300 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
03-17 07:10:35.555  3165  3300 D HeadsetStateMachine: Disconnected process message: 11
,03-17 07:10:35.555  1022  1046 W libprocessgroup: failed to open /acct/uid_1000/pid_2631/cgroup.procs: No such file or directory
,03-17 07:10:35.555  3165  3165 E BluetoothAdapterService(256623390): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
03-17 07:10:35.555  3165  3165 E BluetoothAdapterService(256623390): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
03-17 07:10:35.555  3165  3165 E BluetoothAdapterService(256623390): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,03-17 07:10:35.605  3165  3165 E BluetoothAdapterService(256623390): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
03-17 07:10:35.605  3165  3165 E BluetoothAdapterService(256623390): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,03-17 07:10:35.615  3165  3285 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
03-17 07:10:35.615  3165  3285 I bluedroid: enable
,03-17 07:10:35.625  3165  3285 I bt_hci_bdroid: init
,03-17 07:10:35.625  3165  3315 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
,03-17 07:10:35.625  3165  3285 I bt_vendor: bt-vendor : init
,03-17 07:10:35.625  3165  3285 I bt_vendor: bt-vendor : get_bt_soc_type
03-17 07:10:35.625  3165  3285 E bt_vendor: get_bt_soc_type: Failed to get soc type
03-17 07:10:35.625  3165  3285 I bt_vendor: init: Local BD Address : 27:76:50:a9:ec:08
03-17 07:10:35.625  3165  3285 D bt_userial_mct: userial_init
,03-17 07:10:35.635  3165  3285 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
03-17 07:10:35.635  3165  3285 I bt_vendor: Starting hciattach daemon
03-17 07:10:35.635  3165  3285 I bt_vendor: try to set false
,03-17 07:10:35.635  3165  3285 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
,03-17 07:10:35.635  3165  3285 I bt_vendor: Starting hciattach daemon
,03-17 07:10:35.635  3165  3285 I bt_vendor: try to set true
,03-17 07:10:35.645  1827  1827 I SamsungIME: getDebugLevel  : 0x4f4c
,03-17 07:10:35.665  3319  3319 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,03-17 07:10:35.665  1022  1022 D BluetoothPan: BluetoothPAN Proxy object connected,
03-17 07:10:35.665  1022  1096 E SmartFaceService: onReceive: android.intent.action.BOOT_COMPLETED
03-17 07:10:35.665  1022  1096 D SmartFaceIndicator: no icon
03-17 07:10:35.665  1022  1096 E SmartFaceService: mActiveServiceType: 0
03-17 07:10:35.665  1022  1096 E SmartFaceService: mLightIntensityEnough: true mLux: 0.0
,03-17 07:10:35.665  1022  1096 D Stay/Rotation Worker: updateClientsDone. def. do nothing.
03-17 07:10:35.665  1022  1096 E SmartFaceService: Service Type to Worker: 0
03-17 07:10:35.665  1022  1096 E SmartFaceService: Last Active clients:0 Current Active clients: 0
03-17 07:10:35.665  1022  1096 E SmartFaceService: Last Smart Pause clients: 0 Current Smart Pause clients: 0
,03-17 07:10:35.665  1022  3313 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 n.aB.ff:-1 n.t.a:-1 n.t.b:-1 com.android.server.ssrm.ad.c:-1 
03-17 07:10:35.675  3146  3314 D jxcore_app_log: JniHelper::setJavaVM(0xb71d0448), pthread_self() = -1215117880
,03-17 07:10:35.675  1827  1827 I SamsungIME: KeybaordView init() : load resources
,03-17 07:10:35.685  1022  1022 D CrashAnrDetector: Build: samsung/a3ultexx/a3ulte:5.0.2/LRX22G/A300FUXXU1BOEC:user/release-keys
03-17 07:10:35.685  1022  1022 D CrashAnrDetector: Hardware: MSM8916
03-17 07:10:35.685  1022  1022 D CrashAnrDetector: Revision: 1
03-17 07:10:35.685  1022  1022 D CrashAnrDetector: Bootloader: A300FUXXU1BOEC
03-17 07:10:35.685  1022  1022 D CrashAnrDetector: Radio: unknown
03-17 07:10:35.685  1022  1022 D CrashAnrDetector: Kernel: Linux version 3.10.49-4866174 (dpi@SWDD6204) (gcc version 4.8 (GCC) ) #1 SMP PREEMPT Fri May 29 20:06:40 KST 2015
03-17 07:10:35.685  1022  1022 D CrashAnrDetector: 
03-17 07:10:35.685  1022  1022 D CrashAnrDetector: *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
03-17 07:10:35.685  1022  1022 D CrashAnrDetector: Build fingerprint: 'samsung/a3ultexx/a3ulte:5.0.2/LRX22G/A300FUXXU1BOEC:user/release-keys'
03-17 07:10:35.685  1022  1022 D CrashAnrDetector: Revision: '1'
03-17 07:10:35.685  1022  1022 D CrashAnrDetector: ABI: 'arm'
03-17 07:10:35.685  1022  1022 D CrashAnrDetector: pid: 4085, tid: 4524, name: Thread-617  >>> com.test.thalitest <<<
03-17 07:10:35.685  1022  1022 D CrashAnrDetector: signal 11 (SIGSEGV), code 1 (SEGV_MAPERR), fault addr 0x0
03-17 07:10:35.685  1022  1022 D CrashAnrDetector:     r0 00000000  r1 9358a7dc  r2 00000002  r3 00000000
03-17 07:10:35.685  1022  1022 D CrashAnrDetector:     r4 b8b4ae28  r5 00000000  r6 b8b4a6b8  r7 ba8998a0
03-17 07:10:35.685  1022  1022 D CrashAnrDetector:     r8 b872115c  r9 b8b4ae28  sl b8b4a690  fp 9358a7d4
03-17 07:10:35.685  1022  1022 D CrashAnrDetector:     ip ffffffff  sp 9358a7c4  lr 9e9e1b30  pc 9e9e1a34  cpsr 60000010
03-17 07:10:35.685  1022  1022 D CrashAnrDetector:     d0  0000000000000000  d1  0000000000000000
03-17 07:10:35.685  1022  1022 D CrashAnrDetector:     d2  0000000000000000  d3  0000000000000000
03-17 07:10:35.685  1022  1022 D CrashAnrDetector:     d4  0000000000000000  d5  0000000000000000
03-17 07:10:35.685  1022  1022 D CrashAnrDetector:     d6  0000000000000000  d7  0000000000000000
03-17 07:10:35.685  1022  1022 D CrashAnrDetector:     d8  0000000000000000  d9  0000000000000000
03-17 07:10:35.685  1022  1022 D CrashAnrDetector:     d10 0000000000000000  d11 0000000000000000
03-17 07:10:35.685  1022  1022 D CrashAnrDetector:     d12 0000000000000000  d13 0000000000000000
03-17 07:10:35.685  1022  1022 D CrashAnrDetector:     d14 0000000000000000  d15 0000000000000000
03-17 07:10:35.685  1022  1022 D CrashAnrDetector:     d16 000027b7000027b7  d17 000027b700000000
03-17 07:10:35.685  1022  1022 D CrashAnrDetector:     d18 0001000100010001  d19 0001000100010001
03-17 07:10:35.685  1022  1022 D CrashAnrDetector:     d20 0000000000010001  d21 0000000000000000
03-17 07:10:35.685  1022  1022 D CrashAnrDetector:     d22 0000000000000000  d23 0000000000000000
03-17 07:10:35.685  1022  1022 D CrashAnrDetector:     d24 0000000000000000  d25 0000000000000000
03-17 07:10:35.685  1022  1022 D CrashAnrDetector:     d26 0002000200010001  d27 0002000200020002
03-17 07:10:35.685  1022  1022 D CrashAnrDetector:     d28 0080008000800080  d29 0080008000800080
03-17 07:10:35.685  1022  1022 D CrashAnrDetector:     d30 0800080008000800  d31 0800080008000800
03-17 07:10:35.685  1022  1022 D CrashAnrDetector:     scr 20000013
03-17 07:10:35.685  1022  1022 D CrashAnrDetector: 
03-17 07:10:35.685  1022  1022 D CrashAnrDetector: backtrace:
03-17 07:10:35.685  1022  1022 D CrashAnrDetector:     #00 pc 003d1a34  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (bool ThingIsPermanentAtom<JS::Symbol>(JS::Symbol*)+4)
03-17 07:10:35.685  1022  1022 D CrashAnrDetector:     #01 pc 003d1b2c  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so
03-17 07:10:35.685  1022  1022 D CrashAnrDetector:     #02 pc e5943000  <unknown>
03-17 07:10:35.685  1022  1022 D CrashAnrDetector: 
03-17 07:10:35.685  1022  1022 D CrashAnrDetector: stack:
03-17 07:10:35.685  1022  1022 D CrashAnrDetector:          9358a744  00000000  
03-17 07:10:35.685  1022  1022 D CrashAnrDetector,:          9358a748  8fffc0a0  [anon:js-gc-heap]
03-17 07:10:35.685  1022  1022 D CrashAnrDetector:          9358a74c  b8b4ae28  [heap]
03-17 07:10:35.685  1022  1022 D CrashAnrDetector:          9358a750  b8b4ae28  [heap]
03-17 07:10:35.685  1022  1022 D CrashAnrDetector:          9358a754  00000001  
03-17 07:10:35.685  1022  1022 D CrashAnrDetector:          9358a758  9358a774  [stack:4524]
03-17 07:10:35.685  1022  1022 D CrashAnrDetector:          9358a75c  9e9e1150  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so
03-17 07:10:35.685  1022  1022 D CrashAnrDetector:          9358a760  00000001  
03-17 07:10:35.685  1022  1022 D CrashAnrDetector:          9358a764  00000000  
03-17 07:10:35.685  1022  1022 D CrashAnrDetector:          9358a768  b8b4b958  [heap]
03-17 07:10:35.685  1022  1022 D CrashAnrDetector:          9358a76c  00000000  
03-17 07:10:35.685  1022  1022 D CrashAnrDetector:          9358a770  00000000  
03-17 07:10:35.685  1022  1022 D CrashAnrDetector:          9358a774  b8b4ae28  [heap]
03-17 07:10:35.685  1022  1022 D CrashAnrDetector:          9358a778  b8b4b958  [heap]
03-17 07:10:35.685  1022  1022 D CrashAnrDetector:          9358a77c  9f06db60  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so
03-17 07:10:35.685  1022  1022 D CrashAnrDetector:          9358a780  9358a7ec  [stack:4524]
03-17 07:10:35.685  1022  1022 D CrashAnrDetector:          9358a784  9e9e8514  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (js::gc::GCRuntime::markConservativeStackRoots(JSTracer*, bool)+1308)
03-17 07:10:35.685  1022  1022 D CrashAnrDetector:          9358a788  b8b4ae28  [heap]
03-17 07:10:35.685  1022  1022 D CrashAnrDetector:          9358a78c  b8b4a690  [heap]
03-17 07:10:35.685  1022  1022 D CrashAnrDetector:          9358a790  93590000  /dev/kgsl-3d0
03-17 07:10:35.685  1022  1022 D CrashAnrDetector:          9358a794  9358a7b8  [stack:4524]
03-17 07:10:35.685  1022  1022 D CrashAnrDetector:          9358a798  9358a7b0  [stack:4524]
03-17 07:10:35.685  1022  1022 D CrashAnrDetector:          9358a79c  9358a7bc  [stack:4524]
03-17 07:10:35.685  1022  1022 D CrashAnrDetector:          9358a7a0  9ef946d4  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so
03-17 07:10:35.685  1022  1022 D CrashAnrDetector:          9358a7a4  9358a7c0  [stack:4524]
03-17 07:10:35.685  1022  1022 D CrashAnrDetector:          9358a7a8  00000012  
03-17 07:10:35.685  1022  1022 D CrashAnrDetector:          9358a7ac  00000000  
03-17 07:10:35.685  1022  1022 D CrashAnrDetector:          9358a7b0  00000001  
03-17 07:10:35.685  1022  1022 D CrashAnrDetector:          9358a7b4  b8b4ae28  [heap]
03-17 07:10:35.685  1022  1022 D CrashAnrDetector:          9358a7b8  91e462b0  [anon:js-gc-heap]
03-17 07:10:35.685  1022  1022 D CrashAnrDetector:          9358a7bc  b8b4a6b8  [heap]
03-17 07:10:35.685  1022  1022 D CrashAnrDetector:          9358a7c0  9358a7d4  [stack:4524]
03-17 07:10:35.685  1022  1022 D CrashAnrDetector:     #00  9358a7c4  9358a7d4  [stack:4524]
03-17 07:10:35.685  1022  1022 D CrashAnrDetector:          9358a7c8  9358f838  [stack:4524]
03-17 07:10:35.685  1022  1022 D CrashAnrDetector:          9358a7cc  ba897cf8  [heap]
03-17 07:10:35.685  1022  1022 D CrashAnrDetector:          9358a7d0  9358a7ec  [stack:4524]
03-17 07:10:35.685  1022  1022 D CrashAnrDetector:          9358a7d4  9e9e506c  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (js::gc::MarkValueRoot(JSTracer*, JS::Value*, char const*)+80)
03-17 07:10:35.685  1022  1022 D CrashAnrDetector:     #01  9358a7d8  b872115c  [heap]
03-17 07:10:35.685  1022  1022 D CrashAnrDetector:          9358a7dc  00000000  
03-17 07:10:35.685  1022  1022 D CrashAnrDetector:          9358a7e0  b8b4a6b4  [heap]
03-17 07:10:35.685  1022  1022 D CrashAnrDetector:          9358a7e4  9ef15cd8  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so
03-17 07:10:35.685  1022  1022 D CrashAnrDetector:          9358a7e8  9358a844  [stack:4524]
03-17 07:10:35.685  1022  1022 D CrashAnrDetector:          9358a7ec  9e9e9dcc  /data/app/com,.test.thalitest-1/lib/arm/libjxcore.so (js::gc::GCRuntime::markRuntime(JSTracer*, js::gc::GCRuntime::TraceOrMarkRuntime, js::gc::GCRuntime::TraceRootsOrUsedSaved)+1452)
03-17 07:10:35.685  1022  1022 D CrashAnrDetector:          9358a7f0  00000000  
03-17 07:10:35.685  1022  1022 D CrashAnrDetector:          9358a7f4  9358a80c  [sta
03-17 07:10:35.685  1022  1022 D CrashAnrDetector: processName:com.test.thalitest
03-17 07:10:35.685  1022  1022 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 com.android.server.analytics.data.collection.application.CrashAnrDetector.broadcastEvent:296 com.android.server.analytics.data.collection.application.CrashAnrDetector.processDropBoxEntry:254 com.android.server.analytics.data.collection.application.CrashAnrDetector.access$100:60 com.android.server.analytics.data.collection.application.CrashAnrDetector$1.onReceive:102 
03-17 07:10:35.685  1022  1022 D CrashAnrDetector: broadcastEvent : com.test.thalitest SYSTEM_TOMBSTONE
03-17 07:10:35.695  1022  1022 V AlarmManagerEXT: mGmsLocationBundling: false
03-17 07:10:35.695  1022  1507 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:35.695  1022  1507 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 07:10:35.695  1022  1507 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.gms
03-17 07:10:35.705  1022  1022 D RCPManagerService: ACTION_BOOT_COMPLETED
03-17 07:10:35.705  1022  1022 E RCPManagerService:  BootReceiver : calling scanAndStartRCPProxy ACTION_BOOT_COMPLETED 
03-17 07:10:35.705  1022  1022 D RCPManagerService: BootReceiver.onReceive(): Starting RCP Proxy for user = null
03-17 07:10:35.705  1022  1022 D PersonaManagerService: getPersonasForUser(): returning null!
03-17 07:10:35.705  1022  1022 E RCPManagerService:  BootReceiver : Exception while scanAndStartRCPProxy() Attempt to get length of null array
03-17 07:10:35.705  1022  1022 D MotionRecognitionService:   mReceiver.onReceive : ACTION_BOOT_COMPLETED
03-17 07:10:35.705  3146  3314 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
03-17 07:10:35.705  3146  3314 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
03-17 07:10:35.705  3146  3314 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
03-17 07:10:35.705  3146  3314 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
03-17 07:10:35.705  3146  3314 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
03-17 07:10:35.705  3146  3314 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@989c956 added. We now have 1 listener(s)
03-17 07:10:35.705  2783  2864 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,03-17 07:10:35.725  3328  3328 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,03-17 07:10:35.735  3146  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:76:27
03-17 07:10:35.735  1827  1827 I SamsungIME: getCurrentKeyboard
03-17 07:10:35.735  1827  1827 I SamsungIME: getTextKeyboard
03-17 07:10:35.735  3146  3314 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"08:EC:A9:50:76:27"}
03-17 07:10:35.735  3146  3314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"name":"<no peer name>","address":"08:EC:A9:50:76:27"}
03-17 07:10:35.735  3146  3314 D org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setHandshakeRequired: true -> false
03-17 07:10:35.735  3146  3314 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setHandshakeRequired: true -> false
,03-17 07:10:35.735  3146  3314 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: ,
03-17 07:10:35.735  3146  3314 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
03-17 07:10:35.735  3146  3314 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
03-17 07:10:35.735  3146  3314 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:76:27
03-17 07:10:35.735  3146  3314 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
03-17 07:10:35.735  3146  3314 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
03-17 07:10:35.735  3146  3314 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
03-17 07:10:35.735  3146  3314 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
03-17 07:10:35.735  3146  3314 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
03-17 07:10:35.735  3146  3314 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
03-17 07:10:35.735  3146  3314 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2448a9ad added. We now have 1 listener(s)
03-17 07:10:35.735  3146  3314 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
03-17 07:10:35.735  3331  3331 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,03-17 07:10:35.745  3146  3314 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
03-17 07:10:35.745  3146  3314 W org.thaliproject.p2p.btconnectorlib.DiscoveryManager: isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
,03-17 07:10:35.745  3146  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
03-17 07:10:35.745  3146  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
03-17 07:10:35.745  3146  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
03-17 07:10:35.745  3146  3314 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,03-17 07:10:35.765  3146  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-17 07:10:35.765  3337  3337 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,03-17 07:10:35.765  1827  1827 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,03-17 07:10:35.765  1827  1827 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,03-17 07:10:35.775  3338  3338 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,03-17 07:10:35.785  3341  3341 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,03-17 07:10:35.795  3342  3342 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,03-17 07:10:35.795  3146  3314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:76:27
,03-17 07:10:35.805  1022  1022 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
,03-17 07:10:35.805  1022  1022 D SensorService: [SO] activate (ident=0xb79cd1c0, enabled=0)
03-17 07:10:35.805  1022  1022 I Sensors : AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,03-17 07:10:35.805  3146  3314 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
03-17 07:10:35.805  3146  3314 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-17 07:10:35.805  3146  3314 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-17 07:10:35.805  3146  3314 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
03-17 07:10:35.805  3146  3314 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-17 07:10:35.805  3146  3314 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
03-17 07:10:35.805  3146  3314 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-17 07:10:35.805  3146  3314 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-17 07:10:35.805  3146  3314 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
03-17 07:10:35.805  3146  3314 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
03-17 07:10:35.805  3146  3314 D io.jxcore.node.ConnectivityMonitor: start: OK
,03-17 07:10:35.805  3146  3146 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-17 07:10:35.815  3146  3146 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-17 07:10:35.815  1022  1022 D SensorManager: unregisterListener ::   
,03-17 07:10:35.815  1022  1022 I Sensors : AccelerometerSensor(0) setDelay : 200000000(ns)
,03-17 07:10:35.825  1022  1022 D SensorService: [SO] changed settle time [0]
,03-17 07:10:35.825  1022  1022 D SensorService: [SO] setDelay [200000000]
03-17 07:10:35.825  1022  1022 D SensorService: [SO] activate (ident=0xb7a45730, enabled=1)
03-17 07:10:35.825  1022  1022 D SensorService: [SO] AR_init
03-17 07:10:35.825  1022  1022 I Sensors : AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,03-17 07:10:35.825  1022  1022 D SensorManager: registerListener :: 1600221811, Screen Orientation Sensor, 200000, 0,  ,
03-17 07:10:35.825  1022  1022 D EnterpriseDeviceManagerService: android.intent.action.BOOT_COMPLETED
,03-17 07:10:35.825  1022  1155 D EnterpriseDeviceManagerService: runAdminUpdate
03-17 07:10:35.825  1022  1155 D EnterpriseUtils: File Not Found : /data/system/selfUpdateAdmin.conf
03-17 07:10:35.825  1022  1155 D EnterpriseDeviceManagerService: nothing to selfUpdate
,03-17 07:10:35.835  1022  1022 V ApplicationPolicy: boot completed - refreshWidgetStatus
03-17 07:10:35.835  1022  1022 V ApplicationPolicy: refresh widget status for user 0
,03-17 07:10:35.835  1022  1022 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.vending
03-17 07:10:35.835  1022  1022 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.tapandpay
03-17 07:10:35.835  1022  1022 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.chrome
03-17 07:10:35.835  1022  1022 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.gallery3d
03-17 07:10:35.835  1022  1022 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.vending
03-17 07:10:35.835  1022  1022 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.samsung.android.app.memo
03-17 07:10:35.835  1022  1022 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.google.android.apps.books
03-17 07:10:35.835  1022  1022 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.google.android.music
03-17 07:10:35.835  1022  1022 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.google.android.gm
03-17 07:10:35.835  1022  1022 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.gallery3d
03-17 07:10:35.835  1022  1022 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
03-17 07:10:35.835  1022  1022 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.digitalclock
03-17 07:10:35.835  1022  1022 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.activeapplicationwidget
03-17 07:10:35.835  1022  1022 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.videoplayer
03-17 07:10:35.835  1022  1022 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.music
03-17 07:10:35.835  1022  1022 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.digitalclockeasy
03-17 07:10:35.835  1022  1022 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.clockpackage
03-17 07:10:35.835  1022  1022 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.mms
03-17 07:10:35.835  1022  1022 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname flipboard.app
03-17 07:10:35.835  1022  1022 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.dualclockdigital
03-17 07:10:35.835  1022  1022 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.google.android.googlequicksearchbox
03-17 07:10:35.835  1022  1022 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.email
03-17 07:10:35.835  1022  1022 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.samsungapps
03-17 07:10:35.835  1022  1022 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
03-17 07:10:35.835  1022  1022 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.google.android.talk
03-17 07:10:35.835  1022  1022 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.sbrowser
03-17 07:10:35.835  1022  1022 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.ap.hero.accuweather
03-17 07:10:35.835  1022  1022 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.easymodecontactswidget
03-17 07:10:35.835  1022  1022 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.google.android.apps.magazines
03-17 07:10:35.835  1022  1022 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.fm
03-17 07:10:35.835  1022  1022 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.vending
03-17 07:10:35.835  1022  1022 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.ap.hero.accuweather
03-17 07:10:35.835  1022  1022 V ApplicationPolicy: isApplicationS,tateBlocked userId 0 pkgname com.google.android.music
03-17 07:10:35.835  1022  1022 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.SPlannerAppWidget
03-17 07:10:35.835  1022  1022 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.google.android.apps.plus
03-17 07:10:35.835  1022  1022 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.google.android.apps.docs
03-17 07:10:35.835  1022  1022 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.google.android.apps.plus
03-17 07:10:35.835  1022  1022 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.google.android.googlequicksearchbox
03-17 07:10:35.835  1022  1022 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.ap.hero.accuweather
03-17 07:10:35.835  1022  1022 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.SPlannerAppWidget
03-17 07:10:35.845  1022  1022 W PhoneRestrictionPolicy: Message received - msg { when=-2ms what=2 target=com.android.server.enterprise.restriction.PhoneRestrictionPolicy$SmsMmsDeliveryHandler }
03-17 07:10:35.855  1022  1022 D KnoxMUMContainerPolicy: mContainerReceiver : action - android.intent.action.BOOT_COMPLETED
03-17 07:10:35.855  3146  3146 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
03-17 07:10:35.855  1022  3348 W PhoneRestrictionPolicy:  >>>> deliveryBlockedMsgs
03-17 07:10:35.855  1022  1022 I KnoxMUMContainerPolicy: MSG_REMOVE_ORPHANED_CONTAINERS received
03-17 07:10:35.865  1022  3313 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.ssrm.aL.onChange:-1 com.android.server.ssrm.aL.<init>:-1 com.android.server.ssrm.aJ.<init>:-1 com.android.server.ssrm.ad.onBootCompleted:-1 
03-17 07:10:35.865  1022  3313 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.ssrm.aJ.eq:-1 com.android.server.ssrm.aJ.<init>:-1 com.android.server.ssrm.ad.onBootCompleted:-1 com.android.server.ssrm.ad.c:-1 
03-17 07:10:35.865  1022  1133 D WifiP2pService: InactiveState{ what=143415 }
03-17 07:10:35.865  1022  1133 D WifiP2pService: P2pEnabledState{ what=143415 }
03-17 07:10:35.865  2141  3272 W DriveInitializer: Awaiting to be initialized
03-17 07:10:35.865  1022  1133 D WifiP2pService: DefaultState{ what=143415 }
03-17 07:10:35.865  2141  3350 W DriveInitializer: Background init thread started
03-17 07:10:35.875  1022  1136 D ConnectivityService: Got NetworkFactory Messenger for WIFI
03-17 07:10:35.875  1022  1022 D Tethering: Boot complete.
,03-17 07:10:35.875  1022  3348 W PhoneRestrictionPolicy: cvList size 0
03-17 07:10:35.875  1022  3348 W PhoneRestrictionPolicy:  >>>> deliveryBlockedMsgs
,03-17 07:10:35.875  1022  3348 W PhoneRestrictionPolicy: cvList size 0
,03-17 07:10:35.875  1022  1136 D ConnectivityService: Got NetworkFactory Messenger for WIFI_P2P
,03-17 07:10:35.875  1022  1133 D WIFI_P2P: got request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] with score 60
,03-17 07:10:35.885  1022  1134 E WifiStateMachine: Blacklist file delete
,03-17 07:10:35.885  1022  1133 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,03-17 07:10:35.915  1022  3313 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendStickyBroadcast:1865 com.android.server.ssrm.ad.b:-1 com.android.server.ssrm.ad.onBootCompleted:-1 com.android.server.ssrm.ad.c:-1 com.android.server.ssrm.ae.handleMessage:-1 
,03-17 07:10:35.915  1022  1022 V EnterpriseBillingEngine: ACTION_BOOT_COMPLETED
03-17 07:10:35.915  1206  1206 D StatusBar.NetworkController: refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-17 07:10:35.915  1206  1206 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-17 07:10:35.915  1206  1206 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 07:10:35.915  1206  1206 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 07:10:35.915  1206  1206 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 07:10:35.915  1206  1206 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 07:10:35.915  1022  1022 V EnterpriseBillingEngine: handleAllprofiles - start
03-17 07:10:35.915  1022  1022 V EnterpriseBillingPolicyStorage: getCurrentActiveProfiles - start - 
,03-17 07:10:35.915  1022  1022 V EnterpriseBillingPolicyStorage: getCurrentActiveProfiles - end - null
03-17 07:10:35.915  1022  1022 V EnterpriseBillingEngine: handleAllprofiles - end
,03-17 07:10:35.925  1022  1022 D UsbHostNotification: boot completed
,03-17 07:10:35.925  1022  1022 D UsbHostRestrictor: mBootCompletedReceiver onReceive
03-17 07:10:35.925  1022  1022 D UsbHostRestrictor: initSetUsbBlock STARTED
,03-17 07:10:35.945   256   518 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.gms/files/
03-17 07:10:35.945   256   518 W Vold    : Returning OperationFailed - no handler for errno 0
,03-17 07:10:35.945  2141  3350 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.gms/files
,03-17 07:10:35.965  1022  1022 D UsbHostRestrictor: SIM was never inserted
,03-17 07:10:35.965  1022  1022 D UsbHostRestrictor: writableHostSysNode[false]
03-17 07:10:35.965  1022  1022 D UsbHostRestrictor: Can NOT Write Disable Sys Node to [ON]
,03-17 07:10:35.975  1022  1022 D PersonaManagerService: ACTION_BOOT_COMPLETED
,03-17 07:10:35.975  1022  3313 I i       : No model
03-17 07:10:35.975  1022  1134 D WIFI    : got request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] with score 60
03-17 07:10:35.975  1022  1134 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,03-17 07:10:35.985  1022  1068 E PersonaManagerServiceHandler:  MSG_BOOT_COMPLETE_RECEIVED : soft start personas 
03-17 07:10:35.985  1022  1022 D UsbStorageNotification: boot completed
,03-17 07:10:35.985  1022  1068 D KnoxKeyguardUpdateMonitor: onBootComplete
,03-17 07:10:35.985  1022  3313 D FactoryTest: Not factory mode
03-17 07:10:35.985  1022  3313 D FactoryTest: Not factory mode. isFactoryMode() returend false
03-17 07:10:35.985  1022  3313 D w       : isUserBuild = true
,03-17 07:10:35.985  1206  1206 D StorageNotification: boot completed
,03-17 07:10:35.995  1022  1022 I KnoxKeyguardUpdateMonitor: onTrustManagedChanged user 0, managed:false
,03-17 07:10:35.995  1022  1022 I KnoxKeyguardUpdateMonitor: onTrustChanged user:0, enable:false
,03-17 07:10:36.005  1022  1046 D GpsLocationProvider: receive broadcast intent, action: android.intent.action.BOOT_COMPLETED
,03-17 07:10:36.005  1206  1206 D KeyguardViewMediator: onTrustChanged( Showing = false , userId = 0 )
,03-17 07:10:36.005  1022  1068 D PersonaManagerService: getPersonasForUser(): returning null!
,03-17 07:10:36.005  1022  1046 D GpsLocationProvider_ex: BOOT_COMPLETED native_init 
,03-17 07:10:36.005  1022  1046 D GpsLocationProvider: set_capabilities_callback: 55u
,03-17 07:10:36.025  1022  1044 D SensorService: [SO] Reset Rotation Old [100], Init [1]
,03-17 07:10:36.025  1022  1035 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:36.025  1022  1035 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-17 07:10:36.025  1022  1035 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,03-17 07:10:36.035  1022  3357 E LocSvc_api_v02: I/locClientOpen:2279]: Service instance id is -1
,03-17 07:10:36.045  1022  3313 D SSRM:n  : SIOP:: AP = 400
,03-17 07:10:36.045  3364  3364 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 08:ec:a9:50:76:27 
,03-17 07:10:36.055  3365  3365 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,03-17 07:10:36.065  1022  1046 E Geofence_Adapter: I/===> void GeofenceAdapter::addGfClients(GeoFencer*) line 65 ,
03-17 07:10:36.065  1022  1046 E Geofence_Adapter: I/===> void GeofenceAdapter::updateRegisteredEvents() line 81 
,03-17 07:10:36.065  1022  1046 D GpsLocationProvider_ex: BOOT_COMPLETED native_cleanup 
,03-17 07:10:36.075  1022  1129 I ActivityManager: Killing 2736:com.sec.android.soagent/u0a31 (adj 15): empty #31,
,03-17 07:10:36.085  1022  1035 D StatusBarManagerService: setIcon slot=volume index=23 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02042a level=0 visible=true num=0 )
,03-17 07:10:36.085  1206  1206 D PhoneStatusBar: updateIcon slot=volume index=23 viewIndex=5 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02042a level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02042a level=0 visible=true num=0 )
,03-17 07:10:36.085  3165  3285 I bt_vendor: bluetooth satus is on
03-17 07:10:36.085  3165  3317 D bt_userial_mct: userial_open(port:0)
03-17 07:10:36.085  3165  3317 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,03-17 07:10:36.095  3165  3317 I bt_vendor: Done intiailizing UART
,03-17 07:10:36.095  1022  1321 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:36.095  1022  1321 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:36.095  1022  1321 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:36.095  1022  1321 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:36.095  2141  3350 W DriveInitializer: Background init thread ended
,03-17 07:10:36.095  3165  3317 I bt_vendor: Done intiailizing UART
03-17 07:10:36.095  3165  3317 I bt_userial_mct: CMD=65, EVT=65, ACL_Out=66, ACL_In=66
03-17 07:10:36.095  3165  3317 I bt_vendor: Bluetooth Firmware and transport layer are initialized
,03-17 07:10:36.105  3165  3371 D bt_userial_mct: Entering userial_read_thread(),
,03-17 07:10:36.115  3374  3374 E Zygote  : MountEmulatedStorage()
03-17 07:10:36.115  3374  3374 I libpersona: KNOX_SDCARD checking this for 1000,
03-17 07:10:36.115  3374  3374 E Zygote  : v2
,03-17 07:10:36.115  3374  3374 I libpersona: KNOX_SDCARD not a persona
03-17 07:10:36.115  3374  3374 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,03-17 07:10:36.115  3165  3315 I         : BTE_InitTraceLevels -- TRC_HCI
03-17 07:10:36.115  3165  3315 I         : BTE_InitTraceLevels -- TRC_L2CAP,
03-17 07:10:36.115  3165  3315 I         : BTE_InitTraceLevels -- TRC_RFCOMM
03-17 07:10:36.115  3165  3315 I         : BTE_InitTraceLevels -- TRC_AVDT
03-17 07:10:36.115  3165  3315 I         : BTE_InitTraceLevels -- TRC_AVRC
,03-17 07:10:36.115  3165  3315 I         : BTE_InitTraceLevels -- TRC_A2D
03-17 07:10:36.115  3165  3315 I         : BTE_InitTraceLevels -- TRC_BNEP,
03-17 07:10:36.115  3165  3315 I         : BTE_InitTraceLevels -- TRC_BTM
03-17 07:10:36.115  3165  3315 I         : BTE_InitTraceLevels -- TRC_GAP,
03-17 07:10:36.115  3165  3315 I         : BTE_InitTraceLevels -- TRC_PAN
03-17 07:10:36.115  3165  3315 I         : BTE_InitTraceLevels -- TRC_SAP
,03-17 07:10:36.115  3165  3315 I         : BTE_InitTraceLevels -- TRC_SDP
,03-17 07:10:36.115  3165  3315 I         : BTE_InitTraceLevels -- TRC_GATT
03-17 07:10:36.115  3165  3315 I         : BTE_InitTraceLevels -- TRC_SMP
03-17 07:10:36.115  3165  3315 I         : BTE_InitTraceLevels -- TRC_BTAPP
03-17 07:10:36.115  3165  3315 I         : BTE_InitTraceLevels -- TRC_BTIF
03-17 07:10:36.115  3165  3315 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
03-17 07:10:36.115  3374  3374 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 07:10:36.115  3374  3374 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 07:10:36.115   315   315 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,03-17 07:10:36.125  1022  1321 I ActivityManager: Start proc com.mobeam.barcodeService for broadcast com.mobeam.barcodeService/.system.AppBroadcastReceiver: pid=3374 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,03-17 07:10:36.135  1022  3313 D SSRM:a  : DeviceInfo:: 000000000000
,03-17 07:10:36.135  1022  3313 D SSRM:a  : SettingsAirViewInfo:: 000000000
,03-17 07:10:36.165  1022  1022 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
,03-17 07:10:36.165  1022  1022 D SensorService: [SO] activate (ident=0xb7a45730, enabled=0)
03-17 07:10:36.165  1022  1022 I Sensors : AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,03-17 07:10:36.165  3374  3374 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:36.175  3374  3374 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:36.175  1022  1046 W libprocessgroup: failed to open /acct/uid_10031/pid_2736/cgroup.procs: No such file or directory
,03-17 07:10:36.175  1022  1022 D SensorManager: unregisterListener ::   
,03-17 07:10:36.175  1022  1022 I Sensors : AccelerometerSensor(0) setDelay : 66000000(ns)
,03-17 07:10:36.185  1022  1022 D SensorService: [SO] changed settle time [1]
03-17 07:10:36.185  1022  1022 D SensorService: [SO] setDelay [66000000]
03-17 07:10:36.185  1022  1022 D SensorService: [SO] activate (ident=0xb7a45730, enabled=1)
03-17 07:10:36.185  1022  1022 D SensorService: [SO] AR_init
03-17 07:10:36.185  1022  1022 I Sensors : AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,03-17 07:10:36.195  1022  1022 D SensorManager: registerListener :: 1600221811, Screen Orientation Sensor, 66000, 0,  
,03-17 07:10:36.205  3165  3315 W bt-l2cap: l2c_link_processs_ble_num_bufs 16
,03-17 07:10:36.205  3165  3315 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa453eead 
,03-17 07:10:36.205  3165  3315 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa453eead 
,03-17 07:10:36.215  1022  3372 E LocSvc_ApiV02: I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PREMIUM_SERVICES_CONFIG_REQ_V02
,03-17 07:10:36.215  1022  3372 E LocSvc_ApiV02: I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PREMIUM_SERVICES_CONFIG_REQ_V02
,03-17 07:10:36.225  1022  3357 D qmi_secgps_clnt: qmi_secgps_client_init()
,03-17 07:10:36.225  3165  3290 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
,03-17 07:10:36.235  3165  3290 E bt-btif :                : sec
,03-17 07:10:36.235  3165  3290 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
03-17 07:10:36.235  3165  3290 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
03-17 07:10:36.235  3165  3290 E BluetoothServiceJni: populateRssiValuesNative
03-17 07:10:36.235  3165  3290 I bluedroid: getModelRssiValues
03-17 07:10:36.235  3165  3290 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
03-17 07:10:36.235  3165  3290 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,03-17 07:10:36.235  1022  3357 D qmi_secgps_clnt: SECGPS: qmi_client_get_service_list() returned 0 num_services = 2
,03-17 07:10:36.245  1022  3357 D qmi_secgps_clnt: SECGPS: qmi_client_get_service_list() returned 0 num_entries = 0 num_services = 2
,03-17 07:10:36.245  3165  3290 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3)
,03-17 07:10:36.245  1022  1022 D SettingsProvider: name = bluetooth_name
,03-17 07:10:36.245  3165  3290 D BluetoothAdapterProperties: Scan Mode:20
03-17 07:10:36.245  3165  3290 D BluetoothAdapterProperties: Discoverable Timeout:120
03-17 07:10:36.245  3165  3290 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EC:4E
03-17 07:10:36.245  3165  3290 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
03-17 07:10:36.245  3165  3290 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
,03-17 07:10:36.245  3165  3290 E bt-btif : btif_sock_init: !radio_req && !rfc_init
03-17 07:10:36.245  3165  3290 E bt-btif : btif_sock_init: !vhci_init
,03-17 07:10:36.245  3165  3290 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
03-17 07:10:36.245  1022  3357 D qmi_secgps_clnt: SECGPS: qmi_client_get_service_list() returned 0 num_entries = 2 num_services = 2
,03-17 07:10:36.255  3165  3371 E bt_mct  : hci lib postload completed
,03-17 07:10:36.265  3165  3290 D IOP_DB_BT: db_open: db_open : handle 2961571856l, read 13894 bytes onto local cache
,03-17 07:10:36.265  3165  3290 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
03-17 07:10:36.265  1022  1044 D SensorService: [SO] currT = 38391153000, prevT = 37912194000, diff = 478959000, [-0.479 0.192 9.883]
03-17 07:10:36.265  1022  1044 D SensorService: [SO] Reset Rotation Old [100], Init [1]
03-17 07:10:36.265  3165  3290 D IOP_DB_BT: db_query: result 1
03-17 07:10:36.265  3165  3290 I         : iop_db_open: iop_db_open status 0
03-17 07:10:36.265  3165  3290 D bte_conf: Device ID record 1 : primary
,03-17 07:10:36.265  3165  3290 D bte_conf:   vendorId            = 0075
03-17 07:10:36.265  3165  3290 D bte_conf:   vendorIdSource      = 0001
03-17 07:10:36.265  3165  3290 D bte_conf:   product             = 0100
03-17 07:10:36.265  3165  3290 D bte_conf:   version             = 0200
03-17 07:10:36.265  3165  3290 D bte_conf:   clientExecutableURL = 
03-17 07:10:36.265  3165  3290 D bte_conf:   serviceDescription  = 
03-17 07:10:36.265  3165  3290 D bte_conf:   documentationURL    = 
03-17 07:10:36.265  3165  3290 D bte_conf: bte_load_did_conf no section named DID2.
03-17 07:10:36.265  3165  3290 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,03-17 07:10:36.265  1022  1902 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:36.265  1022  1902 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 07:10:36.265  1022  1902 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:36.275  3146  3146 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-17 07:10:36.275  3165  3285 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
03-17 07:10:36.275  3165  3285 D BluetoothAdapterProperties: ScanMode =  20
03-17 07:10:36.275  3165  3285 D BluetoothAdapterProperties: State =  11
03-17 07:10:36.275  1022  1667 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
03-17 07:10:36.275  3165  3285 D BluetoothAdapterProperties: Setting state to 12
03-17 07:10:36.275  3165  3285 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,03-17 07:10:36.285  3165  3290 D BluetoothAdapterProperties: Scan Mode:21
03-17 07:10:36.285  3165  3290 D BluetoothAdapterProperties: Discoverable Timeout:120
03-17 07:10:36.285  1022  1404 D SettingsProvider: name = bluetooth_a2dp_sink_mode
03-17 07:10:36.285  1022  1404 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-17 07:10:36.285  1022  1404 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-17 07:10:36.285  1022  1404 D SettingsProvider: selectionArgs: false
03-17 07:10:36.285  1022  1404 D SettingsProvider: selectionArgs: 1002
03-17 07:10:36.285  1022  1404 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-17 07:10:36.285  1022  1404 D SettingsProvider: ret = -1
03-17 07:10:36.285  1022  1404 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=1002
03-17 07:10:36.295  3165  3285 D BluetoothAdapterService: Bluetooth PBAP supproted is true
03-17 07:10:36.295  3165  3285 D BluetoothAdapterService: updateAdapterState state is 12
03-17 07:10:36.305  1022  1321 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:36.305  1022  1321 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:36.305  1022  1321 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
03-17 07:10:36.305  3374  3374 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.mobeam.barcodeService.system.AppBroadcastReceiver.onReceive:-1 android.app.ActivityThread.handleReceiver:3125 
03-17 07:10:36.305  3165  3285 D BluetoothAdapterService: Autoconnection is available 
03-17 07:10:36.305  3165  3285 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
03-17 07:10:36.305  3165  3285 D BluetoothAdapterService: starting service from this receiver
03-17 07:10:36.305  1485  1500 D BluetoothAdapter: onBluetoothStateChange: up=true
03-17 07:10:36.305  1485  1500 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
03-17 07:10:36.305  1206  3078 D BluetoothAdapter: onBluetoothStateChange: up=true
03-17 07:10:36.305  1206  3078 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
03-17 07:10:36.305  1461  1483 D BluetoothAdapter: onBluetoothStateChange: up=true
03-17 07:10:36.305  1461  1483 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
03-17 07:10:36.315  3165  3194 D BluetoothA2dp: onBluetoothStateChange: up=true
03-17 07:10:36.315  1022  1520 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:36.315  1022  1520 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:36.315  1022  1520 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
03-17 07:10:36.315  3165  3181 D BluetoothAdapter: onBluetoothStateChange: up=true
03-17 07:10:36.315  3165  3181 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,03-17 07:10:36.315  3165  3285 I BluetoothAdapterState: Entering On State from state = 11
,03-17 07:10:36.315  1880  2293 D BluetoothAdapter: onBluetoothStateChange: up=true
03-17 07:10:36.315  1022  1659 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:36.315  1022  1659 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:36.315  1022  1659 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.mobeam.barcodeService, destAppInfo.processName = com.mobeam.barcodeService
,03-17 07:10:36.315  1880  2293 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,03-17 07:10:36.325  1471  1493 D BluetoothAdapter: onBluetoothStateChange: up=true
03-17 07:10:36.325  1471  1493 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,03-17 07:10:36.325  1022  1051 D BluetoothA2dp: onBluetoothStateChange: up=true
,03-17 07:10:36.325  3146  3158 D BluetoothAdapter: onBluetoothStateChange: up=true
03-17 07:10:36.325  3146  3158 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
03-17 07:10:36.325  3165  3165 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
03-17 07:10:36.325  1022  1051 D BluetoothAdapter: onBluetoothStateChange: up=true
03-17 07:10:36.325  1022  1051 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
03-17 07:10:36.325  3146  3146 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
,03-17 07:10:36.325  1206  1206 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
03-17 07:10:36.325  1022  1022 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
03-17 07:10:36.325  1022  1022 I InputMethodManagerService: [BT Setting State] State =12
,03-17 07:10:36.325  1022  1022 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,03-17 07:10:36.335  1022  1044 D SensorService: [SO] currT = 38461080000, prevT = 37912194000, diff = 548886000, [-0.460 0.192 9.864]
,03-17 07:10:36.335  1022  1044 D SensorService: [SO] -0.460 0.192 9.864
,03-17 07:10:36.335  1022  1044 D SensorService: [SO] [100 -> 255]
,03-17 07:10:36.345  1461  1461 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@2ecc0771, true
,03-17 07:10:36.345  1206  1206 D BluetoothTile:  onBluetoothStateChange:
,03-17 07:10:36.345  3146  3146 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
03-17 07:10:36.345  3146  3146 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-17 07:10:36.345  3146  3146 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-17 07:10:36.345  3146  3146 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-17 07:10:36.345  3146  3146 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-17 07:10:36.345  3146  3146 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-17 07:10:36.345  3146  3146 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-17 07:10:36.345  3146  3146 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
03-17 07:10:36.345  3146  3146 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,03-17 07:10:36.355  1022  1321 I splitIntent: Split this intent : android.intent.action.BOOT_COMPLETED, mSplitNum[0]=87, mSplitNum[1]=126, mSplitNum[2]=164, mBgSplitQueueNum=3 divideNum= 37 r.nextReceiver= 50 receivers.size=201
,03-17 07:10:36.355  1461  1461 D BluetoothHeadset: registerMessageListener
03-17 07:10:36.355  1022  1321 I splitIntent: finish to split intent : android.intent.action.BOOT_COMPLETED !! Enqueue -> schedule it!!
,03-17 07:10:36.365  1206  1206 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,03-17 07:10:36.365  1827  1827 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,03-17 07:10:36.365  1206  1206 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
03-17 07:10:36.365  1206  1206 D BluetoothTile:  getBluetoothState : 12
,03-17 07:10:36.375  1206  1628 D BluetoothTile:  handleUpdatestate:false name:null
,03-17 07:10:36.375  1022  1321 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:36.375  1022  1321 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:36.375  1206  1628 D BluetoothTile:  handleUpdatestate:false name:null
03-17 07:10:36.375  1022  1321 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:36.375  1022  1321 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:36.385  1022  1034 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,03-17 07:10:36.385  1022  1035 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,03-17 07:10:36.385  1206  1206 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,03-17 07:10:36.385  3403  3403 E Zygote  : MountEmulatedStorage()
03-17 07:10:36.385  3403  3403 I libpersona: KNOX_SDCARD checking this for 10097
03-17 07:10:36.385  3403  3403 E Zygote  : v2
03-17 07:10:36.385  3403  3403 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:36.385  3403  3403 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 07:10:36.385  1206  1628 D BluetoothTile:  handleUpdatestate:false name:null
,03-17 07:10:36.395  3403  3403 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 07:10:36.395  3403  3403 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
03-17 07:10:36.395  1022  1321 I ActivityManager: Start proc flipboard.boxer.app for broadcast flipboard.boxer.app/flipboard.boxer.receiver.BootCompleted: pid=3403 uid=10097 gids={50097, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-17 07:10:36.395  1022  3357 E LocSvc_utils_cfg: W/loc_read_sec_gps_conf: no secgps conf file, using defaults
,03-17 07:10:36.395  1022  3372 E LocSvc_ApiV02: I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_ENGINE_LOCK_REQ_V02
,03-17 07:10:36.405  1022  3372 E LocSvc_ApiV02: I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_ENGINE_LOCK_REQ_V02
,03-17 07:10:36.415  1022  1047 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:36.415  1022  1047 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:36.415  1022  1047 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:36.415  1022  1047 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:36.415  1022  3372 E LocSvc_ApiV02: I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_SERVER_REQ_V02
,03-17 07:10:36.415  1022  3357 I qmi_secgps_clnt: SECGPS: Set AGPS Mode : 7
,03-17 07:10:36.415  1022  3357 D qmi_secgps_clnt: SECGPS: send a qmi message to secgps_server OK
,03-17 07:10:36.425  1022  3372 E LocSvc_ApiV02: I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PROTOCOL_CONFIG_PARAMETERS_REQ_V02
,03-17 07:10:36.425  1022  3357 E LocSvc_ApiV02: I/virtual loc_api_adapter_err LocApiV02::setSUPLVersion(uint32_t):1558]: supl version = 131072
,03-17 07:10:36.435  3413  3413 E Zygote  : MountEmulatedStorage()
03-17 07:10:36.435  3413  3413 E Zygote  : v2
03-17 07:10:36.435  3413  3413 I libpersona: KNOX_SDCARD checking this for 1101
03-17 07:10:36.435  3413  3413 I libpersona: KNOX_SDCARD not a persona
03-17 07:10:36.435  3413  3413 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
03-17 07:10:36.435  1022  1047 I ActivityManager: Start proc org.simalliance.openmobileapi.service for broadcast org.simalliance.openmobileapi.service/.SmartcardServiceBootCompletedBroadcastReceiver: pid=3413 uid=1101 gids={41101, 9997} abi=armeabi-v7a
03-17 07:10:36.435  3413  3413 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 07:10:36.435  3413  3413 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 07:10:36.435  1022  1667 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:36.435  1022  1667 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 07:10:36.435  1022  1667 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:36.445  1022  3372 E LocSvc_ApiV02: I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PROTOCOL_CONFIG_PARAMETERS_REQ_V02
,03-17 07:10:36.445  1022  1667 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:36.445  1022  3357 E LocSvc_ApiV02: I/virtual loc_api_adapter_err LocApiV02::setAGLONASSProtocol(long unsigned int):1881]: aGlonassProtocolMask = 0x0
,03-17 07:10:36.445  1022  1667 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 07:10:36.445  1022  1667 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:36.455  3165  3194 D HeadsetService: registerMessageListener
03-17 07:10:36.455  1022  3372 E LocSvc_ApiV02: I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PROTOCOL_CONFIG_PARAMETERS_REQ_V02
,03-17 07:10:36.455  1022  3357 I qmi_secgps_clnt: SECGPS: Set XTRA enable : 1
,03-17 07:10:36.455  1022  3357 D qmi_secgps_clnt: SECGPS: send a qmi message to secgps_server OK
03-17 07:10:36.455  1022  3357 I qmi_secgps_clnt: SECGPS: Set GNSS RF CONFIG : 1
03-17 07:10:36.455  1022  3357 D qmi_secgps_clnt: SECGPS: send a qmi message to secgps_server OK
03-17 07:10:36.455  1022  3357 I qmi_secgps_clnt: SECGPS: Set CERT TYPE : 15
03-17 07:10:36.455   304   304 I art     : Explicit concurrent mark sweep GC freed 8710(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 595us total 25.232ms
,03-17 07:10:36.455  1022  3357 D qmi_secgps_clnt: SECGPS: send a qmi message to secgps_server OK
03-17 07:10:36.455  1022  3357 E LocSvc_ApiV02: I/virtual loc_api_adapter_err LocApiV02::setLPPConfig(uint32_t):1605]: lpp profile = 0
,03-17 07:10:36.465  3165  3194 D HeadsetService: registerMessageListener
03-17 07:10:36.465  3165  3300 D HeadsetStateMachine: Disconnected process message: 70
03-17 07:10:36.465  3165  3300 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@23a26165
,03-17 07:10:36.475  1461  1461 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
03-17 07:10:36.475  1461  1461 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,03-17 07:10:36.475   304   304 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 591us total 16.518ms
,03-17 07:10:36.485  3413  3413 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 07:10:36.485  3413  3413 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:36.485  3403  3403 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 07:10:36.485  3403  3403 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:36.495   304   304 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 585us total 16.537ms
03-17 07:10:36.495  1461  1461 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
03-17 07:10:36.495  1461  1461 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
03-17 07:10:36.495  1461  1461 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,03-17 07:10:36.505  1022  3372 E LocSvc_ApiV02: I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PROTOCOL_CONFIG_PARAMETERS_REQ_V02
03-17 07:10:36.505  1022  3357 E LocSvc_ApiV02: I/virtual loc_api_adapter_err LocApiV02::setSensorControlConfig(int, int):1644]: sensors disabled = 1
,03-17 07:10:36.515  1022  3372 E LocSvc_ApiV02: I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_SENSOR_CONTROL_CONFIG_REQ_V02
,03-17 07:10:36.515  1022  3372 E LocSvc_ApiV02: I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_SENSOR_PERFORMANCE_CONTROL_CONFIGURATION_REQ_V02
,03-17 07:10:36.515  1022  3357 E LocSvc_ApiV02: E/virtual loc_api_adapter_err LocApiV02::setXtraVersionCheck(loc_core::xtra_version_check):3316]: Set xtra version check failed. status: eLOC_CLIENT_FAILURE_INTERNAL, ind status:eQMI_LOC_SUCCESS_V02
,03-17 07:10:36.515  1022  1902 D SettingsProvider: name = next_alarm_formatted
03-17 07:10:36.515  1022  1902 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-17 07:10:36.515  1022  1902 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-17 07:10:36.515  1022  1902 D SettingsProvider: selectionArgs: false
03-17 07:10:36.515  1022  1902 D SettingsProvider: selectionArgs: 10081
03-17 07:10:36.515  1022  1902 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-17 07:10:36.515  1022  1902 D SettingsProvider: ret = -1
03-17 07:10:36.515  3165  3300 D HeadsetStateMachine: Disconnected process message: 9
,03-17 07:10:36.515  3165  3300 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
03-17 07:10:36.515  3165  3165 I BluetoothPbapService: Handler(): got msg=1
,03-17 07:10:36.515  1022  1667 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,03-17 07:10:36.535   283   711 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
03-17 07:10:36.535   283   711 V voice   : voice_set_parameters: enter: A2dpSuspended=false
03-17 07:10:36.535   283   711 V voice   : voice_set_parameters: exit with code(-2)
03-17 07:10:36.535   283   711 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
03-17 07:10:36.535   283   711 V msm8974_platform: platform_set_parameters: exit with code(-2)
03-17 07:10:36.535   283   711 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
03-17 07:10:36.535   283   711 V audio_hw_primary: adev_set_parameters: exit
,03-17 07:10:36.535  3165  3300 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,03-17 07:10:36.535  3413  3413 W ResourcesManager: Asset path '/system/framework/org.simalliance.openmobileapi.jar' does not exist or contains no resources.
,03-17 07:10:36.545  3165  3435 V BluetoothPbapService: PBAP Service initSocket try: 0
,03-17 07:10:36.555  3165  3437 D BluetoothMapMasInstance: set MAP SDP message type : 1
,03-17 07:10:36.555  3165  3435 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-17 07:10:36.555  3165  3437 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-17 07:10:36.555  3165  3435 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[74]}
03-17 07:10:36.555  3165  3435 D BluetoothSocket: bindListen(), new LocalSocket 
03-17 07:10:36.555  3165  3435 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
03-17 07:10:36.555  3165  3435 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@26aa3048
03-17 07:10:36.555  3165  3435 D BluetoothSocket: channel: 19
03-17 07:10:36.555  3165  3435 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,03-17 07:10:36.555  3165  3437 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[76]}
03-17 07:10:36.555  3165  3437 D BluetoothSocket: bindListen(), new LocalSocket 
03-17 07:10:36.555  3165  3437 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
03-17 07:10:36.555  3165  3437 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@30dcaee1
03-17 07:10:36.555  3165  3437 D BluetoothSocket: channel: 5
,03-17 07:10:36.565  1022  1034 I ActivityManager: Killing 2338:com.google.android.apps.magazines/u0a110 (adj 15): empty #31
,03-17 07:10:36.575  1256  1256 V DownloadManager: onReceive intent + android.intent.action.BOOT_COMPLETED
,03-17 07:10:36.575  1022  1392 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:36.575  1022  1392 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-17 07:10:36.575  1022  1392 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,03-17 07:10:36.595  3413  3413 V SmartcardService: main Received broadcast
03-17 07:10:36.595  3413  3413 V SmartcardService: Starting smartcard service after boot completed
,03-17 07:10:36.595  1022  1321 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:36.595  1022  1321 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:36.595  1022  1321 W ActivityManager: NORMAL SET : srcAppInfo.processName = org.simalliance.openmobileapi.service, destAppInfo.processName = org.simalliance.openmobileapi.service
,03-17 07:10:36.595  1022  1392 D SecContentProvider2: uri = 15 selection = getAppBlockDownloadState
,03-17 07:10:36.595  1022  1392 D SecContentProvider2: mCursor = null
03-17 07:10:36.595  1022  1404 I ActivityManager: Killing 1608:com.sec.android.provider.badge/u0a68 (adj 15): empty #31
,03-17 07:10:36.625  1022  1507 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:36.625  1022  1507 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:36.625  1022  1507 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
,03-17 07:10:36.625  1256  1256 D MediaScannerReceiver: action: android.intent.action.BOOT_COMPLETED
,03-17 07:10:36.625  1022  1597 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:36.625  1022  1597 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:36.625  1022  1597 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:36.625  1022  1597 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:36.645  3441  3441 E Zygote  : MountEmulatedStorage()
03-17 07:10:36.645  3441  3441 E Zygote  : v2
03-17 07:10:36.645  3441  3441 I libpersona: KNOX_SDCARD checking this for 1000
03-17 07:10:36.645  3441  3441 I libpersona: KNOX_SDCARD not a persona
03-17 07:10:36.645  3441  3441 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,03-17 07:10:36.645  1022  1597 I ActivityManager: Start proc com.sec.android.app.sysscope for broadcast com.sec.android.app.sysscope/.receiver.BootCompleteReceiver: pid=3441 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
,03-17 07:10:36.645  3441  3441 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,03-17 07:10:36.655  3441  3441 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 07:10:36.675  1022  1404 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:36.675  1022  1404 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:36.675  1022  1404 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,03-17 07:10:36.685  3441  3441 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:36.685  3441  3441 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:36.695  1022  1392 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:36.695  1022  1392 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:36.695  1022  1392 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,03-17 07:10:36.745  3441  3441 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.app.sysscope.receiver.BootCompleteReceiver.onReceive:-1 android.app.ActivityThread.handleReceiver:3125 
,03-17 07:10:36.745  1022  1321 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:36.745  1022  1321 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:36.745  1022  1321 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.sysscope, destAppInfo.processName = com.sec.android.app.sysscope
,03-17 07:10:36.755  1022  1659 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:36.755  1022  1659 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:36.755  1022  1659 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:36.755  1022  1659 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:36.765  3459  3459 E Zygote  : MountEmulatedStorage()
03-17 07:10:36.765  3459  3459 E Zygote  : v2
03-17 07:10:36.765  3459  3459 I libpersona: KNOX_SDCARD checking this for 1000
03-17 07:10:36.765  3459  3459 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:36.765  3459  3459 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 07:10:36.775  3459  3459 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
03-17 07:10:36.775  1022  1659 I ActivityManager: Start proc com.sec.usbsettings for broadcast com.sec.usbsettings/.UltraKeyStringBroadcastReceiver: pid=3459 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,03-17 07:10:36.775  3459  3459 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 07:10:36.775  1022  1046 W libprocessgroup: failed to open /acct/uid_10068/pid_1608/cgroup.procs: No such file or directory
03-17 07:10:36.775  1022  1046 W libprocessgroup: failed to open /acct/uid_10110/pid_2338/cgroup.procs: No such file or directory
,03-17 07:10:36.775  1022  1659 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:36.775  1022  1659 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:36.775  1022  1659 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:36.775  1022  1659 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:36.795  3459  3459 D TimaKeyStoreProvider: TimaSignature is unavailable,
03-17 07:10:36.795  3459  3459 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:36.795  1256  3456 D MediaScannerService: !@start scanning volume internal: [/system/media, /oem/media]
,03-17 07:10:36.795  3472  3472 E Zygote  : MountEmulatedStorage()
03-17 07:10:36.795  3472  3472 I libpersona: KNOX_SDCARD checking this for 1000
03-17 07:10:36.795  3472  3472 E Zygote  : v2
03-17 07:10:36.795  3472  3472 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:36.805  3472  3472 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 07:10:36.805  3472  3472 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 07:10:36.805  3472  3472 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 07:10:36.805  1022  1659 I ActivityManager: Start proc com.samsung.android.app.colorblind for broadcast com.samsung.android.app.colorblind/.ColorBlindBootReceiver: pid=3472 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,03-17 07:10:36.805  1022  3313 D SSRM:a  : DeviceInfo:: 000000000000
03-17 07:10:36.805  1022  3313 D SSRM:a  : SettingsAirViewInfo:: 000000000
,03-17 07:10:36.815  1022  1659 I ActivityManager: Killing 2651:com.google.android.music:main/u0a108 (adj 15): empty #31
,03-17 07:10:36.815  3403  3403 E ActivityThread: Failed to find provider info for flipboard.auth.internal.debug
,03-17 07:10:36.825  3146  3347 W jxcore-log: Initializing JXcore engine
,03-17 07:10:36.825  3146  3347 W jxcore-log: JXcore engine is ready
,03-17 07:10:36.825  1022  1035 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:36.825  1022  1035 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:36.825  1022  1035 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,03-17 07:10:36.825  3472  3472 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:36.825  3472  3472 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:36.825  3403  3403 E ActivityThread: Failed to find provider info for flipboard.auth.internal
,03-17 07:10:36.835  1022  1597 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:36.835  1022  1597 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:36.835  1022  1597 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:36.835  1022  1597 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:36.845  3489  3489 E Zygote  : MountEmulatedStorage()
,03-17 07:10:36.845  3489  3489 E Zygote  : v2
03-17 07:10:36.845  3489  3489 I libpersona: KNOX_SDCARD checking this for 10096,
03-17 07:10:36.845  3489  3489 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 07:10:36.845  3489  3489 I libpersona: KNOX_SDCARD not a persona,
,03-17 07:10:36.845  3489  3489 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 07:10:36.845  1022  1597 I ActivityManager: Start proc flipboard.app for content provider flipboard.app/flipboard.remoteservice.UserContentProvider: pid=3489 uid=10096 gids={50096, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-17 07:10:36.845  3489  3489 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,03-17 07:10:36.865  1256  1256 D MtpService: updating state; isCurrentUser=true, mMtpLocked=false
,03-17 07:10:36.865  1485  1716 D TP/MmsProvider: Update uri=content://mms, match=0
,03-17 07:10:36.875  1485  1716 D TP/MmsProvider: update , handleReadChangedBroadcast
,03-17 07:10:36.875  1485  1716 D TP/MmsSmsProvider: need read changed broadcast:false
,03-17 07:10:36.875  2424  2424 I Mms:transaction: [MmsSystemEventReceiver] restorePduNotificationStatus count=0
03-17 07:10:36.875  2424  2424 D Mms/MessagingNotification: [start]    nonBlockingUpdateMessageIndicator() consume time = 8424.526611
03-17 07:10:36.875  2424  2424 I Mms/ReservationManager: resetAfterConnected()
,03-17 07:10:36.885  3472  3472 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,03-17 07:10:36.885  1022  1035 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:36.885  1022  1035 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:36.885  1022  1035 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:36.885  1022  1035 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:36.885  1485  1807 D TP/MmsSmsProvider: query,matched:7, calling pid = 2424
,03-17 07:10:36.895  2424  3501 D Mms/MessagingNotification: sDisableVibrateForCamera = false
,03-17 07:10:36.895  2424  3501 D Mms/TelephonyPermission: isDefault true
,03-17 07:10:36.895  1485  1807 D TP/MmsSmsProvider: match 7:Elapsed time : 5.087 ms
,03-17 07:10:36.895  1485  1505 D TP/MmsProvider: Query uri=content://mms, match=0, calling pid = 2424
03-17 07:10:36.895  3489  3489 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 07:10:36.895  1877  1877 E audit   : type=1400 msg=audit(1458195036.895:205): avc:  denied  { ioctl } for  pid=3347 comm="Thread-432" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
03-17 07:10:36.895  1877  1877 E audit   :  SEPF_SM-A300FU_5.0.2_0027
03-17 07:10:36.895  1877  1877 E audit   : type=1300 msg=audit(1458195036.895:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=4 a3=924408f8 items=0 ppid=304 ppcomm=main pid=3347 auid=4294967295 uid=10167 gid=10167 euid=10167 suid=10167 fsuid=10167 egid=10167 sgid=10167 fsgid=10167 ses=4294967295 tty=(none) comm="Thread-432" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
03-17 07:10:36.895  1877  1877 E audit   : type=1320 msg=audit(1458195036.895:205): 
03-17 07:10:36.895  3489  3489 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:36.905  3505  3505 E Zygote  : MountEmulatedStorage(),
03-17 07:10:36.905  3505  3505 E Zygote  : v2
03-17 07:10:36.905  3505  3505 I libpersona: KNOX_SDCARD checking this for 10155
03-17 07:10:36.905  3505  3505 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:36.905  3505  3505 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 07:10:36.905  3505  3505 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
03-17 07:10:36.905  3505  3505 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 07:10:36.905  1022  1035 I ActivityManager: Start proc com.sec.enterprise.knox.cloudmdm.smdms for broadcast com.sec.enterprise.knox.cloudmdm.smdms/.core.CoreReceiver: pid=3505 uid=10155 gids={50155, 9997, 3003, 3002, 1028, 1015, 3001} abi=armeabi-v7a
,03-17 07:10:36.915  3146  3347 W jxcore-log: Starting JXcore engine
,03-17 07:10:36.915  1256  3456 E SQLiteLog: (283) recovered 356 frames from WAL file /data/data/com.android.providers.media/databases/internal.db-wal
,03-17 07:10:36.925  1206  1206 D StatusBar.NetworkController: refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-17 07:10:36.925  1206  1206 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-17 07:10:36.925  1206  1206 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 07:10:36.925  1206  1206 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 07:10:36.925  1206  1206 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 07:10:36.925  1206  1206 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 07:10:36.935  2424  2424 I Mms/ReservationManager: getReservedSendMessageCount(): retMessageCount=0
,03-17 07:10:36.945  1022  1404 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:36.945  1022  1404 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:36.945  1022  1404 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
,03-17 07:10:36.945  3505  3505 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:36.945  3505  3505 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:36.955  1022  1034 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:36.955  1022  1034 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:36.955  1022  1034 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:36.955  1022  1034 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:36.955  1485  1505 D TP/MmsSmsProvider: query,matched:200, calling pid = 2424
,03-17 07:10:36.965  1485  1505 D TP/MmsSmsProvider: match 200:Elapsed time : 5.216 ms
,03-17 07:10:36.975  1256  3456 D MediaScanner: Prescan. DB items number : 138 DB_FILES_NUMBER_CACHING_LIMITATION : 7000  Caching mode : true
,03-17 07:10:36.975  3505  3505 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,03-17 07:10:36.975  3521  3521 E Zygote  : MountEmulatedStorage(),
,03-17 07:10:36.975  3521  3521 I libpersona: KNOX_SDCARD checking this for 10043,
,03-17 07:10:36.975  3521  3521 E Zygote  : v2
,03-17 07:10:36.975  3521  3521 I libpersona: KNOX_SDCARD not a persona
03-17 07:10:36.975  3521  3521 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 07:10:36.985  3521  3521 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 07:10:36.985  3521  3521 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 07:10:36.985  1022  1034 I ActivityManager: Start proc com.sec.android.app.safetyassurance for broadcast com.sec.android.app.safetyassurance/.SafetyAssuranceReceiver: pid=3521 uid=10043 gids={50043, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,03-17 07:10:36.985  2424  2424 D Mms/SmsReceiverService: onStart: #1, mResultCode: 0 = Unknown error code, action = android.intent.action.BOOT_COMPLETED
,03-17 07:10:36.995  2424  3520 D Mms/TelephonyPermission: isDefault true
03-17 07:10:36.995  2424  3520 D Mms/SmsReceiverService: [SMS]Receiver handleMessage : Action =android.intent.action.BOOT_COMPLETED
03-17 07:10:36.995  2424  3520 D Mms/SmsReceiverService: [start]    handleBootCompleted() consume time = 113.786979
,03-17 07:10:37.005  1485  1807 D TP/SmsProvider: query,matched:0, calling pid = 2424
,03-17 07:10:37.005  1485  1716 D TP/MmsSmsProvider: getThreadUnReadCount unreadCount=0 imUnreadCount=0
03-17 07:10:37.005  1485  1716 D TP/MmsSmsProvider: deleteConversation threadId: 9223372036854775806
,03-17 07:10:37.005  1485  1807 D TP/SmsProvider: match 0:Elapsed time : 2.630 ms
,03-17 07:10:37.015  3521  3521 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:37.015  3521  3521 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:37.035  3146  3347 W jxcore-log: Platform android
03-17 07:10:37.035  3146  3347 W jxcore-log: 
,03-17 07:10:37.035  3146  3347 W jxcore-log: Process ARCH arm
03-17 07:10:37.035  3146  3347 W jxcore-log: 
,03-17 07:10:37.045  3521  3521 W ResourcesManager: Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,03-17 07:10:37.045  3521  3521 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 07:10:37.045  3521  3521 W ResourcesManager: Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
,03-17 07:10:37.055  1022  1902 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:37.055  1022  1902 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:37.055  1022  1902 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:37.055  1022  1902 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:37.075  3536  3536 E Zygote  : MountEmulatedStorage()
03-17 07:10:37.075  3536  3536 E Zygote  : v2
03-17 07:10:37.075  3536  3536 I libpersona: KNOX_SDCARD checking this for 10082
03-17 07:10:37.075  3536  3536 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:37.075  3536  3536 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,03-17 07:10:37.075  3536  3536 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 07:10:37.075  1022  1902 I ActivityManager: Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=3536 uid=10082 gids={50082, 9997, 3003} abi=armeabi-v7a
,03-17 07:10:37.075  3536  3536 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-17 07:10:37.085  1022  1902 I ActivityManager: Killing 2874:com.sec.android.cloudagent/u0a1 (adj 15): empty #31
,03-17 07:10:37.095  3536  3536 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:37.095  3536  3536 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:37.115  1022  1046 W libprocessgroup: failed to open /acct/uid_10108/pid_2651/cgroup.procs: No such file or directory
,03-17 07:10:37.115  3489  3489 I MultiDex: VM with version 2.1.0 has multidex support
03-17 07:10:37.115  3489  3489 I MultiDex: install
03-17 07:10:37.115  3489  3489 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,03-17 07:10:37.125  1022  1404 I ActivityManager: Killing 2914:com.samsung.android.sconnect/u0a121 (adj 15): empty #31
,03-17 07:10:37.125  1022  1404 I ActivityManager: Killing 2899:com.sec.android.diagmonagent/1000 (adj 15): empty #32
,03-17 07:10:37.125  1022  1022 I DrmEventReceiver: DrmEventReceiver : onReceive
,03-17 07:10:37.125  1022  1022 I DrmEventReceiver: DrmEventReceiver : onReceiveWithPrivilege intent.getTypenull
,03-17 07:10:37.135  1022  1022 I DrmEventReceiver: DrmEventReceiver : beginStartingService
03-17 07:10:37.135  1022  1022 I System.out: start Service
,03-17 07:10:37.165  1022  1022 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.server.DrmEventReceiver.beginStartingService:59 com.android.server.DrmEventReceiver.onReceiveWithPrivilege:47 
,03-17 07:10:37.175  3505  3505 D [0]UMC:Core: onCreate(): 
,03-17 07:10:37.205  1022  1046 W libprocessgroup: failed to open /acct/uid_10001/pid_2874/cgroup.procs: No such file or directory
,03-17 07:10:37.205  1022  1046 W libprocessgroup: failed to open /acct/uid_10121/pid_2914/cgroup.procs: No such file or directory
03-17 07:10:37.205  1022  1046 W libprocessgroup: failed to open /acct/uid_1000/pid_2899/cgroup.procs: No such file or directory
,03-17 07:10:37.205  1022  1392 D SettingsProvider: name = block_emergency_message
,03-17 07:10:37.205  1022  1392 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-17 07:10:37.205  1022  1392 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-17 07:10:37.205  1022  1392 D SettingsProvider: selectionArgs: false
03-17 07:10:37.205  1022  1392 D SettingsProvider: selectionArgs: 10043
03-17 07:10:37.205  1022  1392 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-17 07:10:37.205  1022  1392 D SettingsProvider: ret = -1
,03-17 07:10:37.205  1022  1667 W ActivityManager: getTasks: caller 10043 is using old GET_TASKS but privileged; allowing
,03-17 07:10:37.245  3505  3505 D [0]UMC:DeviceInfo: USA==US==
,03-17 07:10:37.255   256   518 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/flipboard.app/files/cache/
03-17 07:10:37.255   256   518 W Vold    : Returning OperationFailed - no handler for errno 0
,03-17 07:10:37.265  3489  3489 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/flipboard.app/files/cache
,03-17 07:10:37.285  1022  1392 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:37.285  1022  1392 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:37.285  3146  3347 I jxcore-log: JXcore Cordova bridge is ready!
03-17 07:10:37.285  3146  3347 I jxcore-log: 
,03-17 07:10:37.285  3146  3347 W jxcore-log: JXcore engine is started
03-17 07:10:37.285  1022  1392 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,03-17 07:10:37.295  1349  1349 I WifiCredService: onCreate
,03-17 07:10:37.295  3146  3314 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,03-17 07:10:37.295   282   506 D WVMDrmPlugIn: WVMDrmPlugin::onInitialize : 935
03-17 07:10:37.295   282   506 D WVMDrmPlugIn: WVMDrmPlugin::onSetOnInfoListener : add 935
,03-17 07:10:37.305  1349  1349 D WifiTimerReceiver: action: android.intent.action.BOOT_COMPLETED
03-17 07:10:37.305  1349  1349 D WifiTimerReceiver: extra: Bundle[mParcelledData.dataSize=84]
03-17 07:10:37.305  1349  1349 D MY_TAG  : Action boot completed received
,03-17 07:10:37.305  3505  3505 D USER_AGENT: UMC/1.3.23 (SM-A300FU) SAFE-5.3 KNOX-2.3 en_US
,03-17 07:10:37.305   256   518 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/flipboard.app/files/cache/
03-17 07:10:37.305   256   518 W Vold    : Returning OperationFailed - no handler for errno 0
,03-17 07:10:37.305  3146  3347 E jxcore  : Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js,
03-17 07:10:37.305  3146  3347 E jxcore  : Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
03-17 07:10:37.305  3489  3560 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/flipboard.app/files/cache
03-17 07:10:37.305  1349  1349 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED,
,03-17 07:10:37.305  1022  1134 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
,03-17 07:10:37.315  1022  1134 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
03-17 07:10:37.315  1022  1134 E WifiNative-wlan0: invaild command id : 215
,03-17 07:10:37.315  3505  3505 D [0]UMC:AdminManager: init - start
,03-17 07:10:37.315  3146  3146 I chromium: [INFO:CONSOLE(54)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (54)
,03-17 07:10:37.325  3505  3505 D [0]UMC:AdminManager: loadAdmins
,03-17 07:10:37.335  3505  3505 D [0]UMC:AdminManager: init - end
03-17 07:10:37.335  3505  3505 D GSLBManager: migrateStoredUrlFromOldPref
,03-17 07:10:37.335  3536  3536 E UpdateRequestReceiver: ignoring update request
,03-17 07:10:37.335  3489  3489 I System.out: Reading bundled version for config.json
,03-17 07:10:37.345  1022  1321 D FocusedStackFrame: Set to : 0
,03-17 07:10:37.345  1022  1321 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-17 07:10:37.345  1022  1321 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
03-17 07:10:37.345  1256  3456 V MediaScanner: processDirectory :  /system/media
,03-17 07:10:37.345  1022  1321 D InputDispatcher: Focused application set to: xxxx
,03-17 07:10:37.345  1022  1321 D InputDispatcher: Focus left window: 3146
,03-17 07:10:37.345  3505  3505 D GSLBManager: migrateStoredUrlFromOldPref : Migration Not Needed
,03-17 07:10:37.345  3505  3505 D [0]UMC:UMCAdmin: deactivateUMCAdminIfNotRequired : -1
,03-17 07:10:37.345  3505  3505 E [0]UMC:Utils: Admin not found in package com.samsung.knoxpb.mdm
,03-17 07:10:37.345  3505  3505 E [0]UMC:Utils: Admin not found in package com.sec.enterprise.knox.cloudmdm.smdms.agent.myknox
03-17 07:10:37.355  3505  3505 D [0]UMC:UMCAdmin: deactivateUMCAdmin : -1
03-17 07:10:37.355  3505  3505 D [0]UMC:UMCAdmin: isContainer : 0
,03-17 07:10:37.355  1022  1052 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-17 07:10:37.355  1022  1052 D PointerIcon: setMouseCustomIcon IconType is same.101
,03-17 07:10:37.355   257   785 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (148 us)
,03-17 07:10:37.365  1485  1716 D TP/MmsSmsProvider: delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
03-17 07:10:37.365  1485  1716 V TP/MmsSmsDatabaseHelper: updateThread(), thread_id = 9223372036854775806
,03-17 07:10:37.365  1485  1716 V TP/MmsSmsDatabaseHelper: sUpgradeVersion = 0, db.getVersion() = 81
,03-17 07:10:37.365  1485  1716 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-17 07:10:37.365  1485  1716 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-17 07:10:37.365  1485  1716 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-17 07:10:37.365  1485  1716 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-17 07:10:37.365  1485  1716 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-17 07:10:37.365  1485  1716 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
,03-17 07:10:37.375  1022  1034 D EnterpriseDeviceManagerService: isManagedProfileUser(): userId = 0
,03-17 07:10:37.375  1485  1716 D TP/MmsSmsProvider: delete threadId: 9223372036854775806
,03-17 07:10:37.375  1485  1716 D TP/MmsSmsProvider: need read changed broadcast:false
,03-17 07:10:37.385  3505  3505 E [0]UMC:UMCAdmin: No active admin owned by uid 10155
,03-17 07:10:37.385  3505  3505 D [0]UMC:UMCAdmin: isContainer : 0
,03-17 07:10:37.395  3146  3314 W PluginManager: THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 73ms. Plugin should use CordovaInterface.getThreadPool().
,03-17 07:10:37.395  3505  3505 D [0]UMC:UMCAdmin: deactivateUMCAdmin - UMC App Admin deactivated
,03-17 07:10:37.395  3505  3505 D [0]UMC:CoreReceiver: Intent : android.intent.action.BOOT_COMPLETED
,03-17 07:10:37.395  3505  3505 D [0]UMC:CoreReceiver:  check PreETag 
,03-17 07:10:37.395  1485  1807 I art     : Explicit concurrent mark sweep GC freed 35082(2MB) AllocSpace objects, 5(80KB) LOS objects, 45% free, 4MB/8MB, paused 948us total 374.530ms
,03-17 07:10:37.405  1022  3582 I DrmEventService: action event :android.intent.action.BOOT_COMPLETED
,03-17 07:10:37.415  2424  3520 D Mms/Conversation: deleteTempConversation(),deleted=0
03-17 07:10:37.415  1022  1404 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1022  pkgName : ACTIVITY_RESUME_BOOSTER@7
,03-17 07:10:37.415  1349  1349 D NearbySettings: MountReceiver.onReceive - ACTION: android.intent.action.BOOT_COMPLETED
,03-17 07:10:37.415  1349  2220 V NearbySettings: MountReceiver.mPrefHandler - 7002
,03-17 07:10:37.415  1022  1404 W ActivityManager: mDVFSHelper.acquire()
,03-17 07:10:37.415  1022  1034 D SettingsProvider: name = com.samsung.android.nearby.mediaserver.NEARBY_SERVER_STARTED
,03-17 07:10:37.415  3536  3536 E UpdateRequestReceiver: ignoring update request
,03-17 07:10:37.425  1022  1404 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
,03-17 07:10:37.425  1022  1404 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
03-17 07:10:37.425  1022  1404 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
,03-17 07:10:37.435  1256  3456 V MediaScanner:  prescan time: 466ms (DB items: 138)
03-17 07:10:37.435  1256  3456 V MediaScanner:     scan time: 127ms (Caching mode: true), (makeEntry time: 31ms ~24%),  (parsing time: 0ms ~0%),  (bitmapDecoding time: 0ms ~0%), (exifExtracting time : 0ms ~0%), (sefExtracting time : 0ms ~0%), (bulkInserter time : 0ms ~0%)
03-17 07:10:37.435  1256  3456 V MediaScanner: postscan time: 0ms (bulkDeleter : 0), (delete DeadThumbnail time : 0ms)
03-17 07:10:37.435  1256  3456 V MediaScanner:    total time: 593ms
03-17 07:10:37.435  1256  3456 V MediaScanner: checked files: 130  directories : 6  (I: 0, U: 0)
,03-17 07:10:37.435  1256  3456 D MediaScanner: checkDefaultSounds
,03-17 07:10:37.435  1256  3456 D MediaScanner: system alarm_alert  : Vwiurug_etwofi5wgg
,03-17 07:10:37.445  1206  1206 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 07:10:37.445  1508  1508 D Launcher: onRestart, Launcher: 653062954
,03-17 07:10:37.445  1349  1349 I NearbySettings: MountReceiver.onReceive - Path: (systemPath)/storage/emulated/0/Download, (internalPath)/storage/emulated/0/Download, (externalPath)/storage/extSdCard/Download
,03-17 07:10:37.445  1349  1349 I NearbySettings: MountReceiver.onReceive - Internal Path
,03-17 07:10:37.455  1508  1508 D Launcher: onStart, Launcher: 653062954
03-17 07:10:37.455  1508  1508 D Launcher.HomeView: onStart
03-17 07:10:37.455  3505  3505 D [0]UMC:ByodSetupStarter: Container ID : 0
03-17 07:10:37.455  1508  1508 D Launcher: onResume, Launcher: 653062954
,03-17 07:10:37.455  1022  1392 D SettingsProvider: name = kids_home_mode
,03-17 07:10:37.455  1022  1392 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,03-17 07:10:37.455  1022  1392 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-17 07:10:37.455  1022  1392 D SettingsProvider: selectionArgs: false
03-17 07:10:37.455  1022  1392 D SettingsProvider: selectionArgs: 10006
03-17 07:10:37.455  1022  1392 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-17 07:10:37.455  1022  1392 D SettingsProvider: ret = -1
,03-17 07:10:37.455  1508  1508 D Launcher.HomeView: onResume
,03-17 07:10:37.465  1022  1022 I TimaServiceEventReceiver: TimaServiceEventReceiver : onReceive
,03-17 07:10:37.465  3505  3505 V [0]UMC:Utils: checkAppScreen() : com.sec.android.app.launcher
03-17 07:10:37.465  3505  3505 I [0]UMC:Core: shutdown
,03-17 07:10:37.465  1022  1022 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
,03-17 07:10:37.465  1022  1022 D SensorService: [SO] activate (ident=0xb7a45730, enabled=0)
03-17 07:10:37.465  1022  1022 I Sensors : AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,03-17 07:10:37.475  3489  3489 I System.out: Reading bundled version for services.json
,03-17 07:10:37.475  1485  1716 D TP/SmsProvider: query,matched:51, calling pid = 2424
,03-17 07:10:37.475  1508  1508 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,03-17 07:10:37.475  1022  1035 D SettingsProvider: name = personal_mode_enabled
,03-17 07:10:37.475  1485  1716 D TP/SmsProvider: match 51:Elapsed time : 1.464 ms
,03-17 07:10:37.475  1022  1022 D SensorManager: unregisterListener ::   
,03-17 07:10:37.475  1022  1022 I Sensors : AccelerometerSensor(0) setDelay : 200000000(ns)
03-17 07:10:37.475  1508  1508 D MenuAppsGridFragment: onResume
,03-17 07:10:37.475  1022  1507 D ActivityManager: handle home activity for 0
03-17 07:10:37.475  1022  1507 I WallpaperManagerService: switchPersonaWallpaper is called for personaId-0
,03-17 07:10:37.475  1022  1022 D SensorService: [SO] changed settle time [0]
03-17 07:10:37.475  1022  1022 D SensorService: [SO] setDelay [200000000]
03-17 07:10:37.475  1022  1022 D SensorService: [SO] activate (ident=0xb7a45730, enabled=1)
03-17 07:10:37.475  1022  1022 D SensorService: [SO] AR_init
03-17 07:10:37.475  1022  1022 I Sensors : AccelerometerSensor enable: mEnabled 0, handle 0, en 1
03-17 07:10:37.475  1022  1507 D KnoxTimeoutHandler: post home show event for user 0
,03-17 07:10:37.475  1022  1507 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
03-17 07:10:37.475  1022  1507 D KnoxTimeoutHandler: postActiveUserChange for user 0
03-17 07:10:37.475  1022  1507 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,03-17 07:10:37.485  3505  3505 I art     : System.exit called, status: 0
,03-17 07:10:37.485  3505  3505 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,03-17 07:10:37.485   257   257 I SurfaceFlinger: id=13 createSurf (540x960),1 flag=4, Mauncher
,03-17 07:10:37.485  1022  1022 D SensorManager: registerListener :: 1600221811, Screen Orientation Sensor, 200000, 0,  
,03-17 07:10:37.485   282   282 I ANDROID_DRM_FRWORKS_DrmManager: DrmManager::acquireDrmInfo::No decrypt session open not need to handle TV out or HDMI
,03-17 07:10:37.485  3536  3536 E UpdateRequestReceiver: ignoring update request
,03-17 07:10:37.485  1022  1050 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,03-17 07:10:37.495  1022  1022 D WallpaperManagerService:  force update = false; persona id = 0; current user =0; current persona = 0
,03-17 07:10:37.495  1022  1050 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,03-17 07:10:37.495  1022  1022 D KnoxTimeoutHandler: handleHomeShow for 0 and current 0
,03-17 07:10:37.505  1022  1022 D KnoxTimeoutHandler: handleActiveUserChange for user 0,
03-17 07:10:37.505  1022  1022 D PersonaManagerService: getPersonasForUser(): returning null!
,03-17 07:10:37.505  3489  3489 I System.out: Reading bundled version for dynamicStrings.json
,03-17 07:10:37.525  1022  1902 D InputDispatcher: Focus entered window: 1508,
,03-17 07:10:37.525  3536  3536 E UpdateRequestReceiver: ignoring update request
,03-17 07:10:37.525  3489  3489 E flip    : [ERROR:4] Removing local copy of remote dynamicStrings.json: exception=java.io.IOException: invalid JSON, unexpected EOF in string
03-17 07:10:37.525  3489  3489 E flip    :     flipboard.json.JSONParserBase.b(JSONParserBase.java:549)
03-17 07:10:37.525  3489  3489 E flip    :     flipboard.json.JSONParserBase.a(JSONParserBase.java:338)
03-17 07:10:37.525  3489  3489 E flip    :     flipboard.json.JSONParser.a(JSONParser.java:284)
03-17 07:10:37.525  3489  3489 E flip    :     flipboard.json.JSONParserBase.R(JSONParserBase.java:618)
03-17 07:10:37.525  3489  3489 E flip    :     flipboard.json.JSONParserBase.Q(JSONParserBase.java:559)
03-17 07:10:37.525  3489  3489 E flip    :     flipboard.service.FlipboardManager$29.a(FlipboardManager.java:2502)
03-17 07:10:37.525  3489  3489 E flip    :     flipboard.service.FlipboardManager.a(FlipboardManager.java:1589)
03-17 07:10:37.525  3489  3489 E flip    :     flipboard.service.FlipboardManager.<init>(FlipboardManager.java:781)
03-17 07:10:37.525  3489  3489 E flip    :     flipboard.app.FlipboardApplication.onCreate(FlipboardApplication.java:212)
03-17 07:10:37.525  3489  3489 E flip    :     ...
,03-17 07:10:37.525  1022  1052 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,03-17 07:10:37.525  1022  1052 D PointerIcon: setMouseCustomIcon IconType is same.101
,03-17 07:10:37.525  1508  1508 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,03-17 07:10:37.525  1485  1485 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
03-17 07:10:37.525  1485  1485 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,03-17 07:10:37.535  1485  1485 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-17 07:10:37.535  1485  1485 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-17 07:10:37.535  1485  1485 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 07:10:37.535  1485  1485 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,03-17 07:10:37.535  2424  3501 D Mms/MessagingNotification: isBlockingModeEnabled() = false, Zen mode = 0
,03-17 07:10:37.535  1485  1505 D SmsProvider: Update uri=content://sms/outbox, match=8
,03-17 07:10:37.535  3489  3489 I System.out: Parsed section Cover Stories, private: false
,03-17 07:10:37.535  3536  3536 E UpdateRequestReceiver: ignoring update request
,03-17 07:10:37.545  1485  1505 D TP/MmsSmsProvider: need read changed broadcast:false
,03-17 07:10:37.545  1022  1392 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:37.545  1022  1392 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:37.555  1022  1392 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:37.555  1022  1392 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:37.555  3536  3536 E UpdateRequestReceiver: ignoring update request
,03-17 07:10:37.565  1508  1508 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,03-17 07:10:37.565  1022  1520 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,03-17 07:10:37.575  1022  3605 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-17 07:10:37.575  1206  1206 I StatusBar: Icon Only
,03-17 07:10:37.575  1206  1206 D PanelView: There is/are notification(s) 
,03-17 07:10:37.585  3146  3146 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,03-17 07:10:37.585  1827  1827 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false,
,03-17 07:10:37.585  1022  1392 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=3607 uid=10068 gids={50068, 9997} abi=armeabi-v7a
,03-17 07:10:37.585  3607  3607 E Zygote  : MountEmulatedStorage()
03-17 07:10:37.595  3607  3607 I libpersona: KNOX_SDCARD checking this for 10068
03-17 07:10:37.585  3607  3607 E Zygote  : v2
03-17 07:10:37.595  3607  3607 I libpersona: KNOX_SDCARD not a persona
03-17 07:10:37.595  1485  1485 E CscReceiver: onReceive android.intent.action.BOOT_COMPLETED
03-17 07:10:37.595  2424  3520 D Mms/SmsReceiverService: moveOutboxMessagesToFailedBox messageCount: 0
03-17 07:10:37.595  2424  3520 D Mms/SmsReceiverService: handle boot completed, sendFirstQueuedMessage()
03-17 07:10:37.595  2424  3520 D Mms/SmsReceiverService: [SIM-1]sendFirstQueuedMessage()
,03-17 07:10:37.595  1022  1033 I art     : Background partial concurrent mark sweep GC freed 52727(3MB) AllocSpace objects, 75(5MB) LOS objects, 33% free, 24MB/36MB, paused 3.758ms total 174.550ms
,03-17 07:10:37.595  3607  3607 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 07:10:37.595  3607  3607 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 07:10:37.595  3607  3607 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,03-17 07:10:37.615  1256  3456 D MediaScanner: OK. alarm_alert is already exist in setting DB.
,03-17 07:10:37.625  1256  3456 D MediaScanner: system notification_sound  : K_Oprkltf5wgg
,03-17 07:10:37.645  1256  3456 D MediaScanner: OK. notification_sound is already exist in setting DB.
,03-17 07:10:37.645  1256  3456 D MediaScanner: system ringtone  : Wmfi_lpf_pwirywu5wgg
,03-17 07:10:37.655  1022  1902 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:37.655  1022  1902 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:37.655  1022  1902 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:37.655  1022  1902 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:37.655  1508  1508 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@182e1036 time:39788
,03-17 07:10:37.655  1485  1807 D TP/SmsProvider: query,matched:26, calling pid = 2424
,03-17 07:10:37.665  1256  3456 D MediaScanner: OK. ringtone is already exist in setting DB.
,03-17 07:10:37.665  1485  1807 D TP/SmsProvider: match 26:Elapsed time : 4.104 ms
,03-17 07:10:37.665  3607  3607 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:37.665  3607  3607 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:37.665  3622  3622 E Zygote  : MountEmulatedStorage()
03-17 07:10:37.665  3622  3622 E Zygote  : v2
03-17 07:10:37.665  3622  3622 I libpersona: KNOX_SDCARD checking this for 10088
03-17 07:10:37.665  3622  3622 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:37.675  3622  3622 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 07:10:37.675  3622  3622 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 07:10:37.675  1022  1902 I ActivityManager: Start proc com.dropbox.android for broadcast com.dropbox.android/.service.WakeupReceiver: pid=3622 uid=10088 gids={50088, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-17 07:10:37.675  3622  3622 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
03-17 07:10:37.675  1022  1902 I ActivityManager: Killing 2766:com.policydm/1000 (adj 15): empty #31
03-17 07:10:37.675  1022  1047 I ActivityManager: Waited long enough for: ServiceRecord{12a1426e u0 com.samsung.hs20settings/.WifiHs20UtilityService}
03-17 07:10:37.675  1022  1052 D PersonaManager: isKioskContainerExistOnDevice
,03-17 07:10:37.675  1022  1404 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:37.685  1022  1404 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:37.685  1022  1404 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
,03-17 07:10:37.685  1022  1044 D SensorService: [SO] Reset Rotation Old [100], Init [1]
,03-17 07:10:37.685  1022  1507 I ActivityManager: Process com.sec.enterprise.knox.cloudmdm.smdms (pid 3505)(adj 0) has died(33,649)
,03-17 07:10:37.695  1256  3456 D MediaScannerService: !@done scanning volume internal
,03-17 07:10:37.695  1485  1485 D CscUpdateService: onStart
,03-17 07:10:37.695  1485  1485 E CscUpdateService: costomer file is exists : it has been preconfiged.
03-17 07:10:37.695  1485  1485 I CscUpdateService: set_CSC_version
03-17 07:10:37.695  1485  1485 E CscParser: update(): xml file exist
,03-17 07:10:37.705  3120  3120 D FactoryTestApp: [DummyFtClient$mBroadcastReceiver](3120) action= = android.intent.action.MEDIA_SCANNER_FINISHED,
03-17 07:10:37.705  3120  3120 D FactoryTestApp: [DummyFtClient$mBroadcastReceiver](3120) ACTION_MEDIA_SCANNER_FINISHED = /system/media
03-17 07:10:37.705  3120  3120 D FactoryTestApp: [DummyFtClient$mBroadcastReceiver](3120) ACTION_MEDIA_SCANNER_FINISHED = Ignored
,03-17 07:10:37.705  1256  3456 D MediaScannerService: !@start scanning volume external: [/storage/emulated/0, /storage/extSdCard, /storage/Private],
,03-17 07:10:37.705  1022  1902 E ActivityManager: checkUser: useridlist=null, currentuser=0,
03-17 07:10:37.705  1022  1902 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:37.705  1022  1902 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:37.705  1022  1902 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:37.715  3622  3622 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:37.715  3622  3622 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:37.725  3637  3637 E Zygote  : MountEmulatedStorage()
,03-17 07:10:37.725  3637  3637 E Zygote  : v2,
03-17 07:10:37.725  3637  3637 I libpersona: KNOX_SDCARD checking this for 10002
03-17 07:10:37.735  3637  3637 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:37.735  3637  3637 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 07:10:37.735  1022  1902 I ActivityManager: Start proc com.samsung.android.providers.context for broadcast com.samsung.android.providers.context/.ContextSystemBroadcastReceiver: pid=3637 uid=10002 gids={50002, 9997, 3002, 3003, 1028} abi=armeabi-v7a
,03-17 07:10:37.735  3637  3637 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 07:10:37.735  3607  3607 D BadgeProvider: onCreate
03-17 07:10:37.735  3637  3637 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 07:10:37.735  3607  3607 D BadgeProvider: DatabaseHelper
,03-17 07:10:37.745  1485  1485 I CscUtil : isWifiOnly = false
,03-17 07:10:37.745  1022  1052 I ActivityManager: Displayed Component not be shown by security: +326ms
,03-17 07:10:37.745  1485  1485 I System.out: HandDataNode = null
03-17 07:10:37.745  1485  1485 I CscUpdateService: PATH_CSCNAME =CustomerDataSet.CSCName
,03-17 07:10:37.745  1485  1485 I CscUpdateService: This is normal boot : CSC not updated
03-17 07:10:37.745  1349  1349 I SmartcardBootCompleteReceiver: SmartcardBootCompleteReceiver - onReceive() 
03-17 07:10:37.745  1349  1349 I SmartcardBootCompleteReceiver: Received intent with action - android.intent.action.BOOT_COMPLETED
,03-17 07:10:37.755  1485  3647 E CscParser: update(): xml file exist
,03-17 07:10:37.765  1485  3647 D CscGPS  : CSCGPS.updateParameters
03-17 07:10:37.765  1485  3647 D CscGPS  : supl host : null
03-17 07:10:37.765  1485  3647 D CscGPS  : SUPL Host is null or invalid
03-17 07:10:37.765  1485  3647 D CscGPS  : supl_ver : null
03-17 07:10:37.765  1485  3647 D CscGPS  : SUPL Ver is null or invalid
03-17 07:10:37.765  1485  3647 D CscGPS  : supl port : null
03-17 07:10:37.765  1485  3647 D CscGPS  : SUPL PORT is null or invalid
03-17 07:10:37.765  1485  3647 D CscGPS  : LPP : null
03-17 07:10:37.765  1485  3647 D CscGPS  : LPP is null or invalid
03-17 07:10:37.765  1485  3647 D CscGPS  : CSC don't have any AGPS value.
,03-17 07:10:37.775  3637  3637 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:37.775  3637  3637 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:37.775  1256  3456 D MediaProvider: savePlaylistTableInBulkDeleter started
,03-17 07:10:37.775  1022  1404 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:37.775  1256  3456 D MediaProvider: savePlaylistTableInBulkDeleter started - audio_playlists_map_cache existed
,03-17 07:10:37.775  1022  1404 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 07:10:37.775  1022  1404 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,03-17 07:10:37.785  1788  1788 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,03-17 07:10:37.785  1788  1788 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,03-17 07:10:37.785  1788  1788 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,03-17 07:10:37.785  1022  1046 W libprocessgroup: failed to open /acct/uid_1000/pid_2766/cgroup.procs: No such file or directory
,03-17 07:10:37.805  1788  1788 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,03-17 07:10:37.805  1485  1485 I CscUpdateService: same CSC Version
,03-17 07:10:37.805  1485  1485 D CscUtil : Set Build Fingerprint to samsung/a3ultexx/a3ulte:5.0.2/LRX22G/A300FUXXU1BOEC:user/release-keys
,03-17 07:10:37.805  1349  1349 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 android.content.ContextWrapper.sendBroadcast:391 com.android.settings.SmartcardBootCompleteReceiver.onReceive:43 android.app.ActivityThread.handleReceiver:3125 
,03-17 07:10:37.805  1788  1788 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,03-17 07:10:37.815  2424  3520 D Mms/SmsReceiver: unregisterForServiceStateChanges, already unregistered
03-17 07:10:37.815  2424  3520 D Mms/MessagingNotification: sDisableVibrateForCamera = false
03-17 07:10:37.815  2424  3520 D Mms/TelephonyPermission: isDefault true
,03-17 07:10:37.815  1256  3456 D MediaProvider: savePlaylistTableInBulkDeleter started - audio_playlists_map_cache is empty
,03-17 07:10:37.825  1349  1349 I SmartcardBootCompleteReceiver: Broadcast sent with current lockscreen type
03-17 07:10:37.825  1788  1788 D daemonapp: [MSC_Daemon]>>> WDSM:54 [0:0] Act : androidintentactionBOOT_COMPLETED, run:true
,03-17 07:10:37.825  1788  1788 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
03-17 07:10:37.825  1788  1788 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
03-17 07:10:37.825  1788  1788 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
03-17 07:10:37.825  1788  1788 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
,03-17 07:10:37.825  1788  1788 D daemonapp: [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
03-17 07:10:37.825  1788  1788 D daemonapp: [MSC_Daemon]>>> WDSM:97 [0:0] ABOOTCOPLD
,03-17 07:10:37.845  3607  3621 D BadgeProvider: query, [selection] : package='com.android.mms' AND class='com.android.mms.ui.ConversationComposer' AND extraData='base_extra_badge'
,03-17 07:10:37.845  1022  1404 D SettingsProvider: name = aw_daemon_service_key_version_check
03-17 07:10:37.845  1022  1404 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-17 07:10:37.845  1022  1404 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-17 07:10:37.845  1022  1404 D SettingsProvider: selectionArgs: false
03-17 07:10:37.845  1022  1404 D SettingsProvider: selectionArgs: 10157
03-17 07:10:37.845  1022  1404 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-17 07:10:37.845  1022  1404 D SettingsProvider: ret = -1
,03-17 07:10:37.855  1485  1500 D TP/MmsProvider: Query uri=content://mms, match=0, calling pid = 2424
,03-17 07:10:37.865  1508  1508 D Launcher.Model: reloadBadges entered.
,03-17 07:10:37.865  3607  3621 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/2
03-17 07:10:37.865  3607  3621 D BadgeProvider: sendNotify, [notify] : null
03-17 07:10:37.865  3607  3621 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/2
03-17 07:10:37.865  3607  3621 D BadgeProvider: update, [BadgeCount] : badgecount=0
03-17 07:10:37.865  3607  3621 D BadgeProvider: update, [UpdateCount] : 1
,03-17 07:10:37.865  2424  3501 D Mms/MessagingNotification: setBadgeCount(), count=0
,03-17 07:10:37.875  2424  3501 D Mms/MessagingNotification: remove alarm
,03-17 07:10:37.885  1022  1044 D SensorService: [SO] currT = 40011072000, prevT = 39581113000, diff = 429959000, [-0.460 0.192 9.883],
03-17 07:10:37.885  1022  1044 D SensorService: [SO] -0.460 0.192 9.883
03-17 07:10:37.885  1022  1044 D SensorService: [SO] [100 -> 255]
,03-17 07:10:37.895  1485  1500 D TP/MmsSmsProvider: query,matched:200, calling pid = 2424
,03-17 07:10:37.895  2424  3658 D Mms/MessagingNotification: updateAllHistoryAsRead()
,03-17 07:10:37.895  1485  1500 D TP/MmsSmsProvider: match 200:Elapsed time : 3.510 ms
03-17 07:10:37.895  1485  1807 D TP/SmsProvider: query,matched:0, calling pid = 2424
,03-17 07:10:37.895  1485  1807 D TP/SmsProvider: match 0:Elapsed time : 0.930 ms
,03-17 07:10:37.905  2424  3501 D Mms/MessagingNotification: [end]    nonBlockingUpdateMessageIndicator() consume time = 917.826823
,03-17 07:10:37.915  1022  1047 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1022  tag : ACTIVITY_RESUME_BOOSTER@7
,03-17 07:10:37.915  1022  1047 W ActivityManager: mDVFSHelper.release()
03-17 07:10:37.915  1022  1047 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1022  pkgName : ACTIVITY_RESUME_BOOSTER@11
,03-17 07:10:37.925  1485  1807 D TP/SmsProvider: query,matched:0, calling pid = 2424,
,03-17 07:10:37.925  1485  1807 D TP/SmsProvider: match 0:Elapsed time : 1.615 ms
,03-17 07:10:37.925  1256  3456 D MediaProvider: savePlaylistTableInBulkDeleter finished
03-17 07:10:37.925  1256  3456 D MediaProvider: savePlaylistTableInBulkDeleter started
,03-17 07:10:37.925  1256  3456 D MediaProvider: savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache existed
,03-17 07:10:37.935  1022  1404 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10157
,03-17 07:10:37.945  1788  1788 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,03-17 07:10:37.945  1256  3456 D MediaProvider: savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache is empty
,03-17 07:10:37.945  1206  1206 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 07:10:37.945  1256  3456 D MediaProvider: savePlaylistTableInBulkDeleter finished
,03-17 07:10:37.945  1022  1597 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:37.945  1022  1597 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:37.945  1022  1597 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.samsung.android.providers.context
,03-17 07:10:37.955  1485  1716 D TP/SmsProvider: query,matched:51, calling pid = 2424
,03-17 07:10:37.955  1788  1788 D daemonapp: [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
,03-17 07:10:37.955  1022  1659 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:37.955  1022  1659 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:37.955  1022  1659 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.samsung.android.providers.context
,03-17 07:10:37.955  1485  1716 D TP/SmsProvider: match 51:Elapsed time : 5.633 ms
,03-17 07:10:37.955  1022  1392 I ActivityManager: Killing 1174:com.android.defcontainer/u0a3 (adj 15): empty #31
,03-17 07:10:37.965  1788  1788 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,03-17 07:10:37.965  1788  1788 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,03-17 07:10:37.965  1788  1788 D daemonapp: [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
,03-17 07:10:37.965  1256  3456 D MediaScanner: Prescan. DB items number : 26 DB_FILES_NUMBER_CACHING_LIMITATION : 7000  Caching mode : true
,03-17 07:10:37.965  1788  1788 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,03-17 07:10:37.965  1022  1392 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:37.965  1022  1392 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:37.965  1022  1392 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:37.965  1022  1392 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:37.965  1788  1788 E daemonapp: [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
,03-17 07:10:37.975  1349  1349 D [SBeam] : SBeamEnabler.initPreferenceForSbeam : 0
,03-17 07:10:37.975  1788  1788 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,03-17 07:10:37.975  1788  1788 D daemonapp: [MSC_Daemon]>>> WU:2118 [0:0] [boot]now           :1458195037981
,03-17 07:10:37.975  1788  1788 D daemonapp: [MSC_Daemon]>>> WU:2119 [0:0] [boot]NUT :1458216600000
03-17 07:10:37.975  1788  1788 D daemonapp: [MSC_Daemon]>>> WU:2120 [0:0] [boot]interval       :3 (21600000 ms)
03-17 07:10:37.975  1788  1788 D daemonapp: [MSC_Daemon]>>> WU:2121 [0:0] [boot]NUT - now :true
,03-17 07:10:37.985  3663  3663 E Zygote  : MountEmulatedStorage()
,03-17 07:10:37.985  3663  3663 E Zygote  : v2
03-17 07:10:37.985  3663  3663 I libpersona: KNOX_SDCARD checking this for 1000
,03-17 07:10:37.985  3663  3663 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:37.985  3663  3663 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,03-17 07:10:37.985  3663  3663 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
03-17 07:10:37.985  1022  1392 I ActivityManager: Start proc com.sec.dsm.system for broadcast com.sec.dsm.system/.DSMReceiver: pid=3663 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,03-17 07:10:37.985  3663  3663 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 07:10:37.995  1256  3456 V MediaScanner: processDirectory :  /storage/emulated/0
,03-17 07:10:37.995  1788  1788 D daemonapp: [MSC_Daemon]>>> WDBH:2249 [0:0] ud NT1458216600000
,03-17 07:10:38.005  1256  3456 D MediaScanner: Skipping:
03-17 07:10:38.005  1256  3456 D MediaScanner: 7klwibgf7fvntblfd7(75ebcf7
,03-17 07:10:38.005  1349  1349 I SettingSearch/SearchIntentReceiver: action : android.intent.action.BOOT_COMPLETED
03-17 07:10:38.005  1349  1349 I SettingSearch/SearchIntentReceiver: search setting db init!!
,03-17 07:10:38.005  1788  1788 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 9
03-17 07:10:38.005  1788  1788 D daemonapp: [MSC_Daemon]>>> WU:2131 [0:0] Boot set AR_nexttime :1458216600000
,03-17 07:10:38.015   304   304 I art     : Explicit concurrent mark sweep GC freed 8716(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 606us total 24.083ms
,03-17 07:10:38.015  1022  1046 W libprocessgroup: failed to open /acct/uid_10003/pid_1174/cgroup.procs: No such file or directory
,03-17 07:10:38.015  1256  3456 D MediaScanner: Skipping:
03-17 07:10:38.015  1256  3456 D MediaScanner: 7klwibgf7fvntblfd7(7Budiwrd7dblb7
03-17 07:10:38.015  1256  3456 V MediaScanner: processDirectory :  /storage/extSdCard
03-17 07:10:38.015  1349  1349 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver.restoredb:41 com.android.settings.settingssearch.SettingsSearchIntentReceiver.onReceive:61 
03-17 07:10:38.015  1256  3456 W MediaScanner: Error opening directory, reason : Permission denied.
03-17 07:10:38.015  1256  3456 W MediaScanner: 7klwibgf7fxlKdCbid7
,03-17 07:10:38.025  1256  3456 V MediaScanner:  prescan time: 47ms (DB items: 26)
03-17 07:10:38.025  1256  3456 V MediaScanner:     scan time: 24ms (Caching mode: true), (makeEntry time: 14ms ~58%),  (parsing time: 0ms ~0%),  (bitmapDecoding time: 0ms ~0%), (exifExtracting time : 0ms ~0%), (sefExtracting time : 0ms ~0%), (bulkInserter time : 0ms ~0%)
03-17 07:10:38.025  1256  3456 V MediaScanner: postscan time: 4ms (bulkDeleter : 0), (delete DeadThumbnail time : 0ms)
03-17 07:10:38.025  1256  3456 V MediaScanner:    total time: 75ms
03-17 07:10:38.025  1256  3456 V MediaScanner: checked files: 10  directories : 16  (I: 0, U: 0)
,03-17 07:10:38.025   304   304 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 589us total 16.711ms
,03-17 07:10:38.025  3663  3663 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:38.035  3663  3663 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:38.045   304   304 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 564us total 16.181ms
,03-17 07:10:38.055   288   288 E SMD     : DCD OFF
,03-17 07:10:38.145  1022  1052 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{122629b9 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t10} time:40272
,03-17 07:10:38.145  1788  1788 D comdaemonstockapp: [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] onReceive: androidintentactionBOOT_COMPLETED
,03-17 07:10:38.145  1256  3456 D MediaScannerService: !@done scanning volume external
,03-17 07:10:38.145  1788  1788 D comdaemonstockapp: [Daemon_Stock]>>> StockclockDaemonService.java:62 [0:0] appServiceStatus: 0
,03-17 07:10:38.145  1349  3678 I SettingSearch/SearchIntentReceiver: BOOT_COMPLETED call InitSerachDBThread thread start!
,03-17 07:10:38.155   257   446 I SurfaceFlinger: id=12 Removed NainActivit (7/8)
03-17 07:10:38.155   257  3162 I SurfaceFlinger: id=12 Removed NainActivit (-2/8)
,03-17 07:10:38.155  1022  1047 I ActivityManager: Killing 2929:com.sec.android.app.samsungapps/u0a9 (adj 15): empty #31
,03-17 07:10:38.155  3120  3120 D FactoryTestApp: [DummyFtClient$mBroadcastReceiver](3120) action= = android.intent.action.MEDIA_SCANNER_FINISHED
,03-17 07:10:38.155  3120  3120 D FactoryTestApp: [DummyFtClient$mBroadcastReceiver](3120) ACTION_MEDIA_SCANNER_FINISHED = /storage/emulated/0
,03-17 07:10:38.165  3120  3120 D FactoryTestApp: [DummyFtClient$sendBootCompletedAndFinish](3120) ...
03-17 07:10:38.165  3120  3120 D FactoryTestApp: [Support$Values.getString](3120) id=MODEL_COMMUNICATION_MODE, value=gsm
03-17 07:10:38.165  3120  3120 I FactoryTestApp: [ModuleCommon$isConnectionModeNone](3120) mConnectionMode = gsm
,03-17 07:10:38.165  3120  3120 D FactoryTestApp: [IPCWriterToSecPhoneService$ResponseWriter](3120) Create IPCWriterToSecPhoneService
03-17 07:10:38.165  3120  3120 I FactoryTestApp: [IPCWriterToSecPhoneService$connectToSecPhoneService](3120)  
,03-17 07:10:38.165  2424  3520 D Mms/MessagingNotification: isBlockingModeEnabled() = false, Zen mode = 0
,03-17 07:10:38.165  3120  3120 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.sec.factory.aporiented.IPCWriterToSecPhoneService.connectToSecPhoneService:97 com.sec.factory.aporiented.IPCWriterToSecPhoneService.<init>:64 com.sec.factory.aporiented.DummyFtClient.sendBootCompletedAndFinish:147 
,03-17 07:10:38.175  1022  1520 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:38.175  1022  1520 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:38.175  1022  1520 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:38.175  1022  1520 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:38.185  3679  3679 E Zygote  : MountEmulatedStorage()
03-17 07:10:38.185  3679  3679 E Zygote  : v2
03-17 07:10:38.185  3679  3679 I libpersona: KNOX_SDCARD checking this for 10161
03-17 07:10:38.185  3679  3679 I libpersona: KNOX_SDCARD not a persona
03-17 07:10:38.185  3679  3679 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 07:10:38.185  1022  1520 I ActivityManager: Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService$BootReceiver: pid=3679 uid=10161 gids={50161, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-17 07:10:38.185  3679  3679 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 07:10:38.185  3679  3679 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-17 07:10:38.195  1022  1520 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:38.195  1022  1520 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:38.195  1022  1520 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:38.195  1022  1520 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:38.205  3693  3693 E Zygote  : MountEmulatedStorage()
03-17 07:10:38.205  3693  3693 I libpersona: KNOX_SDCARD checking this for 1000
03-17 07:10:38.205  3693  3693 E Zygote  : v2
,03-17 07:10:38.205  3693  3693 I libpersona: KNOX_SDCARD not a persona
03-17 07:10:38.205  3693  3693 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 07:10:38.205  1022  1520 I ActivityManager: Start proc com.wssyncmldm for broadcast com.wssyncmldm/.XDMBroadcastReceiver: pid=3693 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,03-17 07:10:38.205  3693  3693 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 07:10:38.205  3693  3693 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 07:10:38.215  1022  1597 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:38.215  1022  1022 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1022  tag : ACTIVITY_RESUME_BOOSTER@11
03-17 07:10:38.215  1022  1597 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:38.215  1022  1597 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.factory, destAppInfo.processName = com.sec.phone
,03-17 07:10:38.215  1022  1129 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:38.215  1022  1129 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:38.215  1022  1129 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:38.215  1022  1129 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:38.225  3679  3679 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 07:10:38.225  3679  3679 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:38.235  3709  3709 E Zygote  : MountEmulatedStorage()
03-17 07:10:38.235  3709  3709 E Zygote  : v2
03-17 07:10:38.235  3709  3709 I libpersona: KNOX_SDCARD checking this for 10146
03-17 07:10:38.235  3709  3709 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:38.235  3709  3709 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 07:10:38.235  3607  3620 D BadgeProvider: query, [selection] : package='com.android.mms' AND class='com.android.mms.ui.ConversationComposer' AND extraData='base_extra_badge'
,03-17 07:10:38.235  3709  3709 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 07:10:38.235  3709  3709 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,03-17 07:10:38.235  1022  1129 I ActivityManager: Start proc com.sec.providers.settingsearch for content provider com.sec.providers.settingsearch/.SettingSearchProvider: pid=3709 uid=10146 gids={50146, 9997} abi=armeabi-v7a
,03-17 07:10:38.245  3693  3693 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:38.245  3693  3693 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:38.265  3709  3709 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:38.265  3709  3709 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:38.275  3165  3305 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,03-17 07:10:38.285  3693  3693 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-17 07:10:38.295  3146  3146 W ScreenOrientationListener: Removing an inexistent observer!
,03-17 07:10:38.295  3120  3120 I FactoryTestApp: [IPCWriterToSecPhoneService$onServiceConnected](3120) connected done
03-17 07:10:38.295  3120  3120 D FactoryTestApp: [IPCWriterToSecPhoneService$write](3120) Send Response Message to SecPhone
03-17 07:10:38.295  3120  3120 D FactoryTestApp: [IPCWriterToSecPhoneService$write](3120) Response ��
,03-17 07:10:38.295  1022  1046 W libprocessgroup: failed to open /acct/uid_10009/pid_2929/cgroup.procs: No such file or directory
,03-17 07:10:38.295  1508  1508 D Launcher.Model: reloadBadges entered.
03-17 07:10:38.295  3607  3621 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/2
03-17 07:10:38.295  3607  3621 D BadgeProvider: sendNotify, [notify] : null
03-17 07:10:38.295  3607  3621 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/2
03-17 07:10:38.295  3607  3621 D BadgeProvider: update, [BadgeCount] : badgecount=0
03-17 07:10:38.295  3607  3621 D BadgeProvider: update, [UpdateCount] : 1
,03-17 07:10:38.305   311  1078 D AT_Distributor: Send Msg [RIL > ATD] 19 bytes <BOOTING COMPLETED(\r)(\n)>
,03-17 07:10:38.305  3165  3305 D BluetoothMediaBrowser: no now playing list
03-17 07:10:38.305  3165  3305 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
03-17 07:10:38.305  2424  3520 D Mms/MessagingNotification: setBadgeCount(), count=0
,03-17 07:10:38.315  2424  3520 D Mms/MessagingNotification: remove alarm
03-17 07:10:38.315  3120  3120 D FactoryTestApp: [IPCWriterToSecPhoneService$handleMessage](3120) Send BOOTING COMPLETED done
,03-17 07:10:38.385  2424  3728 D Mms/MessagingNotification: updateAllHistoryAsRead()
,03-17 07:10:38.395  1485  1807 D TP/SmsProvider: query,matched:0, calling pid = 2424
,03-17 07:10:38.395  1485  1807 D TP/SmsProvider: match 0:Elapsed time : 1.577 ms
,03-17 07:10:38.395  2424  3520 D Mms/SmsReceiverService: [end]    handleBootCompleted() consume time = 490.042187
,03-17 07:10:38.405   311  1078 D AT_Distributor: SetAtdStatus(), 1_1_0
03-17 07:10:38.405   311  1078 D AT_Distributor: Send Msg [ATD > UART] 19 bytes <BOOTING COMPLETED(\r)(\n)>
,03-17 07:10:38.415  3146  3146 E ActivityThread: Activity com.test.thalitest.MainActivity has leaked IntentReceiver org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager$BluetoothModeBroadcastReceiver@2535c073 that was originally registered here. Are you missing a call to unregisterReceiver()?
03-17 07:10:38.415  3146  3146 E ActivityThread: android.app.IntentReceiverLeaked: Activity com.test.thalitest.MainActivity has leaked IntentReceiver org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager$BluetoothModeBroadcastReceiver@2535c073 that was originally registered here. Are you missing a call to unregisterReceiver()?
03-17 07:10:38.415  3146  3146 E ActivityThread: 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:970)
03-17 07:10:38.415  3146  3146 E ActivityThread: 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:771)
03-17 07:10:38.415  3146  3146 E ActivityThread: 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:2014)
03-17 07:10:38.415  3146  3146 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1994)
03-17 07:10:38.415  3146  3146 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1988)
03-17 07:10:38.415  3146  3146 E ActivityThread: 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.initialize(BluetoothManager.java:275)
03-17 07:10:38.415  3146  3146 E ActivityThread: 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.bind(BluetoothManager.java:103)
03-17 07:10:38.415  3146  3146 E ActivityThread: 	at io.jxcore.node.ConnectivityMonitor.start(ConnectivityMonitor.java:75)
03-17 07:10:38.415  3146  3146 E ActivityThread: 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:90)
03-17 07:10:38.415  3146  3146 E ActivityThread: 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
03-17 07:10:38.415  3146  3146 E ActivityThread: 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
03-17 07:10:38.415  3146  3146 E ActivityThread: 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
03-17 07:10:38.415  3146  3146 E ActivityThread: 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
03-17 07:10:38.415  3146  3146 E ActivityThread: 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
03-17 07:10:38.415  3146  3146 E ActivityThread: 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
03-17 07:10:38.415  3146  3146 E ActivityThread: 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
03-17 07:10:38.415  3146  3146 E ActivityThread: 	at com.android.org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
03-17 07:10:38.415  3146  3146 E ActivityThread: 	at com.android.org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:28)
03-17 07:10:38.415  3146  3146 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 07:10:38.415  3146  3146 E ActivityThread: 	at android.os.Looper.loop(Looper.java:145)
03-17 07:10:38.415  3146  3146 E ActivityThread: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-17 07:10:38.415  3146  3146 E ActivityThread: Activity com.test.thalitest.MainActivity has leaked IntentReceiver io.jxcore.node.ConnectivityMonitor$WifiStateChangedAndConnectivityActionBroadcastReceiver@3f7124e2 that was originally registered here. Are you missing a call to unregisterReceiver()?
03-17 07:10:38.415  3146  3146 E ActivityThread: android.app.IntentReceiverLeaked: Activity com.test.thalitest.MainActivity has leaked IntentReceiver io.jxcore.node.ConnectivityMonitor$WifiStateChangedAndConnectivityActionBroadcastReceiver@3f7124e2 that was originally registered here. Are you missing a call to unregisterReceiver()?
03-17 07:10:38.415  3146  3146 E ActivityThread: 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:970)
03-17 07:10:38.415  3146  3146 E ActivityThread: 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:771)
03-17 07:10:38.415  3146  3146 E ActivityThread: 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:2014)
03-17 07:10:38.415  3146  3146 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1994)
03-17 07:10:38.415  3146  3146 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1988)
03-17 07:10:38.415  3146  3146 E ActivityThread: 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:503)
03-17 07:10:38.415  3146  3146 E ActivityThread: 	at io.jxcore.node.ConnectivityMonitor.start(ConnectivityMonitor.java:67)
03-17 07:10:38.415  3146  3146 E ActivityThread: 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:90)
03-17 07:10:38.415  3146  3146 E ActivityThread: 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
03-17 07:10:38.415  3146  3146 E ActivityThread: 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
03-17 07:10:38.415  3146  3146 E ActivityThread: 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
03-17 07:10:38.415  3146  3146 E ActivityThread: 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
03-17 07:10:38.415  3146  3146 E ActivityThread: 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
03-17 07:10:38.415  3146  3146 E ActivityThread: 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
03-17 07:10:38.415  3146  3146 E ActivityThread: 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
03-17 07:10:38.415  3146  3146 E ActivityThread: 	at com.android.org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
03-17 07:10:38.415  3146  3146 E ActivityThread: 	at com.android.org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:28)
03-17 07:10:38.415  3146  3146 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 07:10:38.415  3146  3146 E ActivityThread: 	at android.os.Looper.loop(Looper.java:145)
03-17 07:10:38.415  3146  3146 E ActivityThread: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-17 07:10:38.485  3679  3729 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-17 07:10:38.485  3679  3729 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-17 07:10:38.555  3663  3663 E SQLiteLog: (283) recovered 8 frames from WAL file /data/data/com.sec.dsm.system/databases/profile.db-wal
,03-17 07:10:38.575  3693  3693 I FOTA    : [com.wssyncmldm.db.sql.XDMDbContentProvider(95/onCreate)] 
,03-17 07:10:38.575  3679  3729 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,03-17 07:10:38.595  1022  1321 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:38.595  1022  1321 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
03-17 07:10:38.595  1022  1321 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.dropbox.android, destAppInfo.processName = com.dropbox.android
,03-17 07:10:38.595  1022  1321 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:38.595  1022  1321 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:38.595  1022  1321 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:38.595  1022  1321 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:38.615  3733  3733 E Zygote  : MountEmulatedStorage(),
03-17 07:10:38.615  3733  3733 E Zygote  : v2
03-17 07:10:38.615  3663  3663 D DSM     : [Lines:107] Normal booted
03-17 07:10:38.615  3663  3663 D DSM     : [Lines:114] Boot completed
03-17 07:10:38.615  1022  1321 I ActivityManager: Start proc com.dropbox.android:crash_uploader for service com.dropbox.android/.exception.CrashUploaderService: pid=3733 uid=10088 gids={50088, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-17 07:10:38.615  3733  3733 I libpersona: KNOX_SDCARD checking this for 10088
03-17 07:10:38.615  3733  3733 I libpersona: KNOX_SDCARD not a persona,
,03-17 07:10:38.615  3733  3733 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 07:10:38.625  3733  3733 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 07:10:38.625  3733  3733 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,03-17 07:10:38.625  1022  1520 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:38.625  1022  1520 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:38.625  1022  1520 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:38.625  1022  1520 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:38.635  3746  3746 E Zygote  : MountEmulatedStorage()
03-17 07:10:38.635  3746  3746 E Zygote  : v2
03-17 07:10:38.635  3746  3746 I libpersona: KNOX_SDCARD checking this for 1000
03-17 07:10:38.635  3746  3746 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:38.645  3746  3746 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 07:10:38.645  1022  1520 I ActivityManager: Start proc com.sec.android.app.factorykeystring for broadcast com.sec.android.app.factorykeystring/com.sec.android.app.entry.FactoryKeyStringBroadcastReceiver: pid=3746 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,03-17 07:10:38.645  3693  3693 I DBG_DM  : [llIIlIIlIllIllIlllII(316/llIlIIIIlIIIIIlIlIII)] Voice : true
03-17 07:10:38.645  3746  3746 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 07:10:38.645  3746  3746 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 07:10:38.665  3746  3746 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 07:10:38.665  3693  3693 I DBG_DM  : [llIIlIIlIllIllIlllII(317/llIlIIIIlIIIIIlIlIII)] SMS : true
,03-17 07:10:38.665  3746  3746 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:38.665  3733  3733 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:38.675  3733  3733 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:38.675  3693  3693 I DBG_DM  : [llIIlIIlIllIllIlllII(318/llIlIIIIlIIIIIlIlIII)] isDataOnly : false
,03-17 07:10:38.675  3746  3746 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,03-17 07:10:38.695  3622  3622 I com.dropbox.android.service.DropboxNetworkReceiver: Setting receiver enabled: false
,03-17 07:10:38.705  3679  3729 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,03-17 07:10:38.705  3679  3729 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@15c8aab6: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
03-17 07:10:38.705  3679  3729 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,03-17 07:10:38.715  3746  3746 W ActivityThread: ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,03-17 07:10:38.735  3746  3746 D LcdtestApp: [Class]XMLDataStorage, [Method]parseXML, [Message]modelXML=sm-a300fu.dat
03-17 07:10:38.735  3746  3746 D LcdtestApp: [Class]XMLDataStorage, [Method]parseXML, [Message]deviceXML=a3ulte.dat
,03-17 07:10:38.735  3746  3746 I LcdtestApp: [Class]XMLDataStorage, [Method]parseAsset, [Message]Convert enc file to xml file: sm-a300fu.dat
,03-17 07:10:38.755  3746  3746 D LcdtestApp: [Class]XMLDataStorage, [Method]parseAsset, [Message]Decode base xml file: lcdtest.dat
,03-17 07:10:38.765  1022  1667 I ActivityManager: Killing 2952:com.sec.android.fotaclient/u0a8 (adj 15): empty #31
,03-17 07:10:38.775  3746  3746 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MODEL_NAME
,03-17 07:10:38.775  3746  3746 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_ACCELEROMETER
03-17 07:10:38.775  3746  3746 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_MAGNETIC
03-17 07:10:38.775  3746  3746 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_GYROSCOPE
03-17 07:10:38.775  3746  3746 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MAGNETIC_ROTATE_DEGREE
03-17 07:10:38.775  3746  3746 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LCD_TYPE
03-17 07:10:38.775  3746  3746 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MODEL_COMMUNICATION_MODE
03-17 07:10:38.775  3746  3746 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=DEVICE_TYPE
03-17 07:10:38.775  3746  3746 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_TOUCHKEY_GRAPH
03-17 07:10:38.775  3746  3746 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_TSP_SUPPORT_CONFIG_VERSION
03-17 07:10:38.775  3746  3746 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SUPPORT_TSK_FW_UPDATE_INTERNAL
03-17 07:10:38.775  3746  3746 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=FAILHIST_VERSION
03-17 07:10:38.775  3746  3746 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SUPPORT_RUN_REF
,03-17 07:10:38.775  3746  3746 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_SIMPLE_TEST_ACC_SYSFS
03-17 07:10:38.775  3746  3746 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_SENSOR_TEST_ACC_REVERSE
,03-17 07:10:38.775  3746  3746 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_TEST_ACC_BIT
03-17 07:10:38.775  3746  3746 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_DISPLAY_LUX_ADC
,03-17 07:10:38.775  3746  3746 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_PROXIMITY_TEST_MOTOR_FEEDBACK
03-17 07:10:38.775  3746  3746 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=KEY_TEST_APP_RECENT
,03-17 07:10:38.785  3746  3746 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=KEY_TEST_BACK
,03-17 07:10:38.785  3746  3746 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SUPPORT_CHARGE_COUNT,
03-17 07:10:38.785  3746  3746 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=NO_RGBSENSOR_SUPPORT_REV
03-17 07:10:38.785  3746  3746 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=TSP_X_AXIS_CHANNEL
,03-17 07:10:38.785  3746  3746 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=TSP_Y_AXIS_CHANNEL
03-17 07:10:38.785  3746  3746 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_LEVEL_2_MAX
03-17 07:10:38.785  3746  3746 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_1,
,03-17 07:10:38.785  3746  3746 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_2
03-17 07:10:38.785  3746  3746 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_3
,03-17 07:10:38.785  3746  3746 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_4
03-17 07:10:38.785  3746  3746 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_5
,03-17 07:10:38.785  3746  3746 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_2
,03-17 07:10:38.785  3746  3746 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_3
03-17 07:10:38.785  3746  3746 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_4
,03-17 07:10:38.785  3746  3746 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_5
,03-17 07:10:38.785  3746  3746 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=PATH_NOISE_TSK_BACK_RAWDATA
,03-17 07:10:38.785  3746  3746 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=PATH_NOISE_TSK_RECENT_RAWDATA
,03-17 07:10:38.785  3622  3622 E ActivityThread: Failed to find provider info for com.dropbox.carousel.CuOwnerCheckProvider
03-17 07:10:38.795  3746  3746 I LcdtestApp: [Class]FactoryKeyStringBroadcastReceiver, [Method]onReceive, , [Message]pref_hardReset : N
,03-17 07:10:38.795  1022  1597 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:38.795  1022  1597 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:38.795  1022  1597 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:38.795  1022  1597 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:38.795  3622  3622 I dbxyzptlk.db240408.D.h: Loading /data/data/com.dropbox.android/files/extracted_libs/lib_breakpadinstaller_1dc04d6d96cbb2962385ec13f5f77649aec85e95_arm
,03-17 07:10:38.805  3693  3693 I DBG_DM  : [com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI(2693/lllIlIlIIIllIIlIllIl)] xdbsqlGetFUMOStatus : 220
,03-17 07:10:38.805  3693  3693 I DBG_DM  : [com.wssyncmldm.XDMApplication(80/onCreate)] XDMApplication Start ! - Fumo State
,03-17 07:10:38.805  3622  3622 I dbxyzptlk.db240408.D.h: Loading /data/data/com.dropbox.android/files/extracted_libs/lib_dbxfileobserver_59d9546785d1f42b870763ef906fd65c59b55c56_arm
,03-17 07:10:38.805  3693  3693 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 com.wssyncmldm.XDMApplication.onCreate:81 android.app.Instrumentation.callApplicationOnCreate:1020 android.app.ActivityThread.handleBindApplication:5256 
,03-17 07:10:38.815  3622  3622 I dbxyzptlk.db240408.D.h: Loading /data/data/com.dropbox.android/files/extracted_libs/lib_dropboxsync_cf9d7b2df44b0b78b581431109195f96d492fc70_arm
,03-17 07:10:38.815  3774  3774 E Zygote  : MountEmulatedStorage()
,03-17 07:10:38.815  3774  3774 I libpersona: KNOX_SDCARD checking this for 1000
03-17 07:10:38.815  3774  3774 E Zygote  : v2
03-17 07:10:38.815  3774  3774 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:38.825  3774  3774 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 07:10:38.825  1022  1597 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonBootCompletedReceiver: pid=3774 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,03-17 07:10:38.825  3774  3774 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 07:10:38.825  3774  3774 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 07:10:38.825  3622  3622 I dbxyzptlk.db240408.D.h: Loading /data/data/com.dropbox.android/files/extracted_libs/lib_mupdf_391432aaa92f053af59645394b5734622378199a_arm
,03-17 07:10:38.825  1022  1597 I ActivityManager: Killing 2972:com.samsung.android.scloud.sync/u0a58 (adj 15): empty #31
,03-17 07:10:38.835  1022  1129 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:38.835  1022  1129 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-17 07:10:38.835  1022  1129 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.wssyncmldm, destAppInfo.processName = com.wssyncmldm
,03-17 07:10:38.845  3693  3693 I DBG_DM  : [com.wssyncmldm.XDMBroadcastReceiver(152/onReceive)] android.intent.action.BOOT_COMPLETED
,03-17 07:10:38.845  3693  3693 I DBG_DM  : [com.wssyncmldm.XDMService(1598/IlIlllIIlIlIIIlIlIll)] 
,03-17 07:10:38.845  3693  3693 I DBG_DM  : [com.wssyncmldm.XDMService(1603/IlIlllIIlIlIIIlIlIll)] m_WakeLock is acquire!!
,03-17 07:10:38.845  3693  3693 I DBG_DM  : [com.wssyncmldm.XDMService(1420/lllIlIlIIIllIIlIllIl)] 0
,03-17 07:10:38.855  3693  3693 I DBG_DM  : [IIlIIIlllllIIlIIIlII(232/llllIllIIIIIlIIllIII)] Default - NO_ROOTING_CHECK : false
,03-17 07:10:38.855  3622  3622 D breakpad: breakpad loaded; target path "/data/data/com.dropbox.android/app_crashdumps"
,03-17 07:10:38.855  3693  3693 I DBG_DM  : [com.wssyncmldm.XDMService(1463/llIlIIIIlIIIIIlIlIII)] 0,
,03-17 07:10:38.855  3693  3693 I DBG_DM  : [IIlIIIlllllIIlIIIlII(261/IIllIlIIIIlIIIllIllI)] Roaming Check : true
03-17 07:10:38.855  3693  3693 I DBG_DM  : [com.wssyncmldm.XDMService(1548/llIIllllIIlllIIIIlll)] 0
,03-17 07:10:38.855  3693  3693 I DBG_DM  : [IIlIIIlllllIIlIIIlII(293/llIIlIlIlIlIIIIIIlIl)] validation Check On
,03-17 07:10:38.855  3693  3693 I DBG_DM  : [com.wssyncmldm.XDMService(1505/IllIlIIIIlIIlIIIllIl)] 0
,03-17 07:10:38.855  1206  1206 D OverheatReceiver: onReceive() getAction : android.intent.action.BOOT_COMPLETED
,03-17 07:10:38.865  3693  3693 I DBG_DM  : [IIlIIIlllllIIlIIIlII(274/lllllllIlllIIlllIlIl)] SSL Check On
,03-17 07:10:38.865  3693  3693 I DBG_DM  : [llIIlIIlIllIllIlllII(109/llllIIIllIlIIIIllllI)] 
03-17 07:10:38.865  3693  3744 I DBG_DM  : [IlIIlIIlIllllIlllIII(181/llIIIIlllllIIllIIllI)] XEVENT_OS_INITIALIZED
,03-17 07:10:38.865  3774  3774 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:38.865  3774  3774 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:38.865  3693  3744 I DBG_DM  : [llIlIIIIlllIlllllIll(142/llIIIIlllllIIllIIllI)] nSync = 0
,03-17 07:10:38.865  3693  3693 I DBG_DM  : [llIIlIIlIllIllIlllII(397/llIIIIlllllIIllIIllI)] External SD Card Path : /storage/extSdCard
03-17 07:10:38.865  3693  3744 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.wssyncmldm.ui.lIlIIlIlIlIllllllIII.lllIlIlIIIllIIlIllIl:72 com.wssyncmldm.ui.lIlIIlIlIlIllllllIII.llIIIIlllllIIllIIllI:112 IlIIlIIlIllllIlllIII.llIIIIlllllIIllIIllI:185 
,03-17 07:10:38.875  1022  1659 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:38.875  1022  1659 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:38.875  1022  1659 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.wssyncmldm, destAppInfo.processName = com.wssyncmldm
,03-17 07:10:38.875  3693  3693 I DBG_DM  : [llIIlIIlIllIllIlllII(166/llllIIIllIlIIIIllllI)] bExternalStorageAvailable [true]
,03-17 07:10:38.875  3693  3693 I DBG_DM  : [llIIlIIlIllIllIlllII(167/llllIIIllIlIIIIllllI)] bExternalSDStorageAvailable [false]
,03-17 07:10:38.875  3693  3693 I DBG_DM  : [com.wssyncmldm.XDMService(1624/IIlIlIIlIlIIlIlllIIl)] 
,03-17 07:10:38.885  3693  3693 I DBG_DM  : [com.wssyncmldm.XDMService(1629/IIlIlIIlIlIIlIlllIIl)] m_WakeLock is release!!
,03-17 07:10:38.885  1206  1206 D OverheatReceiver: into the SAFE_MODE_ACTION
03-17 07:10:38.885  1206  1206 D OverheatReceiver: VZW on -> change to Global UX [safe mode]
03-17 07:10:38.885  3693  3693 I DBG_DM  : [com.wssyncmldm.XDMService(155/onStartCommand)] 
,03-17 07:10:38.885  1206  1206 D OverheatReceiver: isSafeMode = false
,03-17 07:10:38.885  3622  3622 I com.dropbox.sync.android.a: Prepared cache dir '/data/data/com.dropbox.android/app_DropboxSyncCache/hizqkiq3952astb'.
,03-17 07:10:38.895  1485  1485 D BootupListener: intent.getAction() = android.intent.action.BOOT_COMPLETED
,03-17 07:10:38.895  1022  1659 D SettingsProvider: name = internet_call_settings_visibility
03-17 07:10:38.895   256   518 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/cache/
03-17 07:10:38.895  1022  1659 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-17 07:10:38.895   256   518 W Vold    : Returning OperationFailed - no handler for errno 0
03-17 07:10:38.895  1022  1659 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-17 07:10:38.895  1022  1659 D SettingsProvider: selectionArgs: false
03-17 07:10:38.895  1022  1659 D SettingsProvider: selectionArgs: 1001
03-17 07:10:38.895  1022  1659 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-17 07:10:38.895  1022  1659 D SettingsProvider: ret = -1
03-17 07:10:38.895  1485  1485 D PhoneUtilsCommon: isSupportVoLTE is false.
03-17 07:10:38.895  3679  3679 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
,03-17 07:10:38.895  1022  1034 I ActivityManager: Killing 2837:com.osp.app.signin/u0a36 (adj 15): empty #31
,03-17 07:10:38.905  3693  3693 I DBG_DM  : [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,03-17 07:10:38.915  3693  3693 I DBG_DM  : [com.wssyncmldm.ui.IIllIllllIIlIlIIlIII(49/onServiceConnected)] 
,03-17 07:10:38.915  3693  3744 I DBG_DM  : [com.wssyncmldm.db.file.XDB(1976/llIlIIIIlIIIIIlIlIII)] xdbDMffs_Init
,03-17 07:10:38.925  3774  3774 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,03-17 07:10:38.925  1206  1206 D StatusBar.NetworkController: refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-17 07:10:38.925  1206  1206 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-17 07:10:38.925  1206  1206 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 07:10:38.925  1206  1206 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 07:10:38.925  1206  1206 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 07:10:38.925  1206  1206 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 07:10:38.945  1022  1046 W libprocessgroup: failed to open /acct/uid_10008/pid_2952/cgroup.procs: No such file or directory
,03-17 07:10:38.965  1022  1046 W libprocessgroup: failed to open /acct/uid_10058/pid_2972/cgroup.procs: No such file or directory
03-17 07:10:38.965  1022  1046 W libprocessgroup: failed to open /acct/uid_10036/pid_2837/cgroup.procs: No such file or directory
,03-17 07:10:38.985  1461  1461 I Telecom : InCallController: Attempting to bind to InCall com.android.incallui, is dupe? false 
,03-17 07:10:38.995  1022  1321 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:38.995  1022  1321 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:38.995  1022  1321 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.incallui
,03-17 07:10:38.995  1022  1520 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:38.995  1022  1520 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-17 07:10:38.995  1022  1520 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.incallui
,03-17 07:10:39.005  1022  1902 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:39.005  1022  1902 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:39.005  1022  1902 E ActivityManager: checkUser: useridlist=null, currentuser=0,
03-17 07:10:39.005  1022  1902 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:39.015  3693  3744 I DBG_DM  : [IlIIlIIlIllllIlllIII(191/llIIIIlllllIIllIIllI)] XEVENT_PHONEBOOK_INITIALIZED,
,03-17 07:10:39.025  3800  3800 E Zygote  : MountEmulatedStorage()
03-17 07:10:39.025  3800  3800 I libpersona: KNOX_SDCARD checking this for 10052
03-17 07:10:39.025  3800  3800 E Zygote  : v2
03-17 07:10:39.025  3800  3800 I libpersona: KNOX_SDCARD not a persona
03-17 07:10:39.025  3800  3800 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 07:10:39.025  1022  1902 I ActivityManager: Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.StartUpReceiver: pid=3800 uid=10052 gids={50052, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a,
,03-17 07:10:39.035  3800  3800 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 07:10:39.035  1461  1461 I Telecom : InCallController: onConnected to ComponentInfo{com.android.incallui/com.android.incallui.InCallServiceImpl}
,03-17 07:10:39.035  3800  3800 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-17 07:10:39.045  3774  3774 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,03-17 07:10:39.055  3774  3774 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,03-17 07:10:39.055  3774  3774 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.intent.action.BOOT_COMPLETED
,03-17 07:10:39.065  3774  3774 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
03-17 07:10:39.065  3774  3774 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(68/lllIlIlIIIllIIlIllIl)] Running with BootCompletedReceiver adapter
03-17 07:10:39.065  3774  3774 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,03-17 07:10:39.075  3693  3744 I DBG_DM  : [com.wssyncmldm.db.file.XDB(3660/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,03-17 07:10:39.085  3693  3744 I DBG_DM  : [com.wssyncmldm.XDMService(1377/llllIIIllIlIIIIllllI)] wssGetUpdateReport : 0
,03-17 07:10:39.085  3693  3744 I DBG_DM  : [IlIIlIIlIllllIlllIII(217/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT
,03-17 07:10:39.095  3622  3622 I com.dropbox.sync.android.ad: Dropbox initialized for application: hizqkiq3952astb (com.dropbox.android/240408 DropboxSync/2.0.2 (Android; 5.0.2; samsung SM-A300FU armeabi-v7a; en_US))
,03-17 07:10:39.095  3800  3800 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 07:10:39.095  3800  3800 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:39.185  1022  1667 I art     : Explicit concurrent mark sweep GC freed 15572(813KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 2.371ms total 142.172ms
,03-17 07:10:39.185  1022  1667 E Tethering: No numeric data
,03-17 07:10:39.195  1022  1507 E Tethering: No numeric data
,03-17 07:10:39.195  1022  1404 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:39.195  1022  1404 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:39.195  1022  1404 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:39.195  1022  1404 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:39.195  1022  1520 E Tethering: No numeric data
,03-17 07:10:39.195  1022  1035 E Tethering: No numeric data
,03-17 07:10:39.205  1022  1659 E Tethering: No numeric data
,03-17 07:10:39.205  1022  1034 E Tethering: No numeric data
,03-17 07:10:39.205  3820  3820 E Zygote  : MountEmulatedStorage()
,03-17 07:10:39.215  3820  3820 E Zygote  : v2
03-17 07:10:39.215  3820  3820 I libpersona: KNOX_SDCARD checking this for 1000
03-17 07:10:39.215  3820  3820 I libpersona: KNOX_SDCARD not a persona
03-17 07:10:39.215  3820  3820 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 07:10:39.215  3820  3820 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,03-17 07:10:39.215  3820  3820 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 07:10:39.215  1022  1404 I ActivityManager: Start proc com.policydm for content provider com.policydm/com.sec.android.policydm.log.MasterLogProvider: pid=3820 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,03-17 07:10:39.255  3081  3081 D elm:15121: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,03-17 07:10:39.255  1022  1507 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:39.255  1022  1507 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:39.255  1022  1507 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,03-17 07:10:39.265  3081  3081 D elm:15121: ELMAbstractReceiver : Receive Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,03-17 07:10:39.265   283  1017 V audio_hw_primary: adev_get_parameters: enter: keys - call_forwarding
03-17 07:10:39.265   283  1017 D audio_hw_extn: audio_extn_get_parameters: returns 
03-17 07:10:39.265   283  1017 V msm8974_platform: platform_get_parameters: exit: returns - 
03-17 07:10:39.265   283  1017 V audio_hw_primary: adev_get_parameters: exit: returns - call_forwarding=false
03-17 07:10:39.265   283  1017 I str_params: key: 'call_forwarding' value: ''
03-17 07:10:39.265  1922  1922 V InCall  : ProximitySensor -  - screenonImmediately: false
,03-17 07:10:39.275  1922  1922 V InCall  : ProximitySensor -  - mFromRcsShare: false,
03-17 07:10:39.275  1922  1922 I InCall  : ProximitySensor -  - ProximitySensor{keybrd=0, dpad=0, offhook=0, hor=0, ui=0, aud=EARPIECE},
03-17 07:10:39.275  1349  3678 D [SBeam] : SBeamEnabler.isSBeamSupported : [-1]
,03-17 07:10:39.275  1349  3678 D [SBeam] : SBeamEnabler.isSBeamSupported : EXIST
,03-17 07:10:39.275  1922  1922 D ScoverManager: serviceVersion : 16908288
,03-17 07:10:39.275  1022  1507 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
,03-17 07:10:39.285  3820  3820 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:39.285  3820  3820 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:39.285  1445  1445 V EmergencyMode: [EmergencyReceiver] EmergencyReceiver [android.intent.action.BOOT_COMPLETED]
,03-17 07:10:39.285  1022  1520 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:39.285  1022  1520 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 07:10:39.285  1022  1520 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,03-17 07:10:39.295  1922  1922 D InCall  : InCallUtils - isCoverClosed : TYPE_FLIP_COVER 
03-17 07:10:39.295  3081  3081 D elm:15121: ElmAgentService : onCreate()
,03-17 07:10:39.295  1461  1461 I Telecom : ProximitySensorManager: Proximity wake lock already released
,03-17 07:10:39.295  1022  1597 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
03-17 07:10:39.295  1922  1922 D InCall  : InCallUtils - isCoverClosed : TYPE_FLIP_COVER 
,03-17 07:10:39.295  1922  1922 I InCall  : InCallPresenter -  - InCallState = NO_CALLS
,03-17 07:10:39.295  1922  1922 I InCall  : InCallPresenter -  - Phone switching state: NO_CALLS -> NO_CALLS
,03-17 07:10:39.295  1922  1922 D InCall  : InCallPresenter -  - dismissCoverDialog()...
,03-17 07:10:39.305  3081  3840 D elm:15121: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,03-17 07:10:39.305  3081  3081 D elm:15121: ELMEngine.ServiceHandler.handleMessage( BOOT_COMPLETED ). 
03-17 07:10:39.305  3081  3081 D elm:15121: BootCompletedState : startBootCompleted() call
03-17 07:10:39.305  3081  3081 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,03-17 07:10:39.305  3081  3081 I elm:15121: Get License : 0
,03-17 07:10:39.305  3081  3081 D elm:15121: ElmAgentService : onDestroy().
,03-17 07:10:39.315  1922  1922 I InCall  : CallSContextMotion - stopPutDownListening,
,03-17 07:10:39.315  1022  1392 E Tethering: No numeric data
,03-17 07:10:39.315  1922  1922 D InCall  : StatusBarNotifier - updateInCallNotification(allowFullScreenIntent = false)...
,03-17 07:10:39.325  1022  1392 E Tethering: No numeric data
,03-17 07:10:39.325  1022  1034 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
,03-17 07:10:39.325  1922  1922 D InCall  : InCallUtils - isCoverClosed : TYPE_FLIP_COVER 
03-17 07:10:39.325  1206  1206 D PhoneStatusBarView: setCallBackground:0
,03-17 07:10:39.325  1022  1520 E Tethering: No numeric data
,03-17 07:10:39.345  1022  1902 E Tethering: No numeric data
,03-17 07:10:39.355  1022  1034 D PowerManagerService: [api] release WakeLock flags=0x10000006 tag=PowerUI.Notification uid=10049 pid=1206 (0x0),
03-17 07:10:39.355  1445  1445 V EmergencyMode: [EmergencyBase] setBootTime
03-17 07:10:39.355  1445  1445 V EmergencyMode: [EmergencyFactory] No Recovery State, kill my self.
,03-17 07:10:39.355  1022  1129 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:39.355  1022  1129 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:39.355  1022  1129 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:39.355  1022  1129 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:39.365  1922  1922 D VideoCallManager: Instantiating VideoCallManager
,03-17 07:10:39.375  1022  1129 I ActivityManager: Start proc com.sec.factory.camera for broadcast com.sec.factory.camera/com.sec.android.app.camerafirmware.CameraFirmwareBroadCastReceiver: pid=3843 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-17 07:10:39.375  3843  3843 E Zygote  : MountEmulatedStorage(),
03-17 07:10:39.375  3843  3843 E Zygote  : v2
,03-17 07:10:39.375  3843  3843 I libpersona: KNOX_SDCARD checking this for 1000
,03-17 07:10:39.375  3843  3843 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:39.385  3843  3843 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 07:10:39.385  1922  1922 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144,
,03-17 07:10:39.385  1922  1922 I GFX construct_block_size_descriptor_2d second part: took 2.718073ms for 0*0 texture 0,
,03-17 07:10:39.385  3843  3843 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,03-17 07:10:39.395  3843  3843 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 07:10:39.395  1922  1922 I GFX generate_partition_tables: took 5.441719ms for 0*0 texture 0
,03-17 07:10:39.405  1922  1922 I GFX raster: took 12.394740ms for 176*144 texture 0
03-17 07:10:39.405  1922  1922 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb757c988 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b0, Counterpart=0xb757c258 counterpartCT=4 counterpartW=176 counterparth=144
,03-17 07:10:39.415  3843  3843 D TimaKeyStoreProvider: TimaSignature is unavailable,
03-17 07:10:39.415  3843  3843 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:39.415  1922  1922 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 320x240,
03-17 07:10:39.425  1922  1922 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
03-17 07:10:39.425  1922  1922 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
03-17 07:10:39.425  1922  1922 I Adreno-EGL: Build Date: 04/06/15 Mon
03-17 07:10:39.425  1922  1922 I Adreno-EGL: Local Branch: 
03-17 07:10:39.425  1922  1922 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
03-17 07:10:39.425  1922  1922 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
03-17 07:10:39.425  1922  1922 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,03-17 07:10:39.435  3622  3833 I System.out: Thread-499(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
03-17 07:10:39.435  1022  1129 V VibratorService: hasVibrator - useVibetonz: true
03-17 07:10:39.435  3622  3833 I System.out: Thread-499(ApacheHTTPLog):isSBSettingEnabled false
03-17 07:10:39.435  3622  3833 I System.out: Thread-499(ApacheHTTPLog):isShipBuild true
03-17 07:10:39.435  3622  3833 I System.out: Thread-499(ApacheHTTPLog):SMARTBONDING_ENABLED is false
03-17 07:10:39.435  3622  3833 I System.out: Thread-499(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,03-17 07:10:39.435   277  1011 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
03-17 07:10:39.435   277  1011 D Netd    : getNetworkForDns: using netid 502 for uid 10088
,03-17 07:10:39.435  1022  1520 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:39.435  1022  1520 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 07:10:39.435  1022  1520 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,03-17 07:10:39.445  3820  3820 I DBG_POLICYDM: [com.policydm.XDMApplication(554/xdmWakeLockAcquire)] 
,03-17 07:10:39.445  1022  1597 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:39.445  1022  1597 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:39.445  1022  1597 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:39.445  1022  1597 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:39.455  3820  3820 I DBG_POLICYDM: [com.policydm.XDMApplication(559/xdmWakeLockAcquire)] m_WakeLock is acquire!!
,03-17 07:10:39.455  1922  1922 I GFX GPU raster: eglCreateImageKHR: EGL_SUCCESS
,03-17 07:10:39.465  3870  3870 E Zygote  : MountEmulatedStorage()
,03-17 07:10:39.465  3870  3870 E Zygote  : v2
03-17 07:10:39.465  3870  3870 I libpersona: KNOX_SDCARD checking this for 10008
,03-17 07:10:39.465  3870  3870 I libpersona: KNOX_SDCARD not a persona
03-17 07:10:39.465  1922  1922 I glCompressedTexImage2D: took 0.265000ms for 320*61440 texture 37809
,03-17 07:10:39.465  3870  3870 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 07:10:39.475  3870  3870 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 07:10:39.475  1022  1597 I ActivityManager: Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=3870 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-17 07:10:39.475  3870  3870 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,03-17 07:10:39.475  1349  3678 W NotificationAccessSettings: Skipping notification listener service com.android.settings/com.android.settings.accessibility.notificationreminder.NotificationReminderService: it does not require the permission android.permission.BIND_NOTIFICATION_LISTENER_SERVICE
03-17 07:10:39.475  1922  1922 I draw setup: took 10.881875ms for 320*240 texture 37809
03-17 07:10:39.475  1922  1922 E GFX GPU raster: drawn
,03-17 07:10:39.475  1022  1129 V VibratorService: hasVibrator - useVibetonz: true
,03-17 07:10:39.485  1922  1922 I GFX GPU raster ASTC: took 44.264427ms for 320*240 texture 12
03-17 07:10:39.485  3820  3863 I DBG_POLICYDM: [com.policydm.agent.XDMTask(163/xdmAgentTaskHandler)] XEVENT_OS_INITIALIZED
03-17 07:10:39.485  1922  1922 I GFX raster: took 44.349271ms for 320*240 texture 0
03-17 07:10:39.485  1922  1922 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb757c908 bitmapCt=12 bitmapW=320 bitmapH=240 BitmapInternalFormat=93b1, Counterpart=0xb757c470 counterpartCT=4 counterpartW=320 counterparth=240
,03-17 07:10:39.485  3820  3863 I DBG_POLICYDM: [com.policydm.agent.XDMAgent(156/xdmAgentSetSyncMode)] nSync = 0
,03-17 07:10:39.495  1022  1902 V VibratorService: hasVibrator - useVibetonz: true
,03-17 07:10:39.495  1922  1922 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 480x640
,03-17 07:10:39.495  1922  1922 I GFX GPU raster: eglCreateImageKHR: EGL_SUCCESS
,03-17 07:10:39.495  1922  1922 I glCompressedTexImage2D: took 0.386771ms for 480*122880 texture 37813
03-17 07:10:39.495  1922  1922 I draw setup: took 0.748437ms for 480*640 texture 37813
03-17 07:10:39.495  1922  1922 E GFX GPU raster: drawn
,03-17 07:10:39.505  1922  1922 I GFX GPU raster ASTC: took 7.655000ms for 480*640 texture 12
03-17 07:10:39.505  1922  1922 I GFX raster: took 7.749219ms for 480*640 texture 0
03-17 07:10:39.505  1922  1922 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb757c470 bitmapCt=12 bitmapW=480 bitmapH=640 BitmapInternalFormat=93b5, Counterpart=0xb77bdec8 counterpartCT=4 counterpartW=480 counterparth=640
,03-17 07:10:39.505  3870  3870 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:39.505  3870  3870 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:39.505  3820  3863 I DBG_POLICYDM: [com.policydm.db.XDB(1531/xdbDMffs_Init)] xdbDMffs_Init
,03-17 07:10:39.525  3843  3843 I CameraApp: CameraApp.onCreate()... mFeature : null
03-17 07:10:39.525  3843  3843 I testFeature: Feature.Feature(context)
03-17 07:10:39.525  3843  3843 I testFeature: Feature.readInternalDefaultXml()
03-17 07:10:39.525  3843  3843 I testFeature: ResetFeatureValue
,03-17 07:10:39.535  3843  3843 I CameraFirmware_broadcast: CameraFirmwareBroadCastReceiver...
03-17 07:10:39.535  3843  3843 I CameraApp: CameraApp.getAppFeature()...
,03-17 07:10:39.535  1022  1404 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:39.535  1022  1404 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:39.535  1022  1404 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:39.535  1022  1404 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:39.545  1922  1922 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 440x330,
,03-17 07:10:39.545  1922  1922 I GFX GPU raster: eglCreateImageKHR: EGL_SUCCESS
03-17 07:10:39.545  1922  1922 I glCompressedTexImage2D: took 0.429428ms for 440*116864 texture 37809
03-17 07:10:39.545  1922  1922 I draw setup: took 1.095781ms for 440*330 texture 37809,
03-17 07:10:39.545  1922  1922 E GFX GPU raster: drawn
,03-17 07:10:39.555  1922  1922 I GFX GPU raster ASTC: took 5.208594ms for 440*330 texture 12
03-17 07:10:39.555  1922  1922 I GFX raster: took 5.291563ms for 440*330 texture 0
03-17 07:10:39.555  1922  1922 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb77bdea8 bitmapCt=12 bitmapW=440 bitmapH=330 BitmapInternalFormat=93b1, Counterpart=0xb77be278 counterpartCT=4 counterpartW=440 counterparth=330
03-17 07:10:39.555  3887  3887 E Zygote  : MountEmulatedStorage()
03-17 07:10:39.555  3887  3887 E Zygote  : v2
03-17 07:10:39.555  3887  3887 I libpersona: KNOX_SDCARD checking this for 10095
03-17 07:10:39.555  3887  3887 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:39.555  3887  3887 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 07:10:39.555  1022  1404 I ActivityManager: Start proc com.samsung.android.provider.filterprovider for broadcast com.samsung.android.provider.filterprovider/.FilterProviderReceiver: pid=3887 uid=10095 gids={50095, 9997, 1023} abi=armeabi-v7a
03-17 07:10:39.555  1022  1404 I ActivityManager: Killing 2199:com.samsung.android.securitylogagent/1000 (adj 15): empty #31
,03-17 07:10:39.565  3887  3887 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 07:10:39.565  3887  3887 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 07:10:39.595  3820  3820 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(191/xdmInitExternalStorageState)] 
,03-17 07:10:39.595  1349  3678 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-17 07:10:39.605  3887  3887 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:39.605  3887  3887 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:39.605  3820  3820 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(390/xdmGetExternalSDCardPath)] External SD Card Path : /storage/extSdCard
,03-17 07:10:39.615   304   304 I art     : Explicit concurrent mark sweep GC freed 8739(372KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 1.146ms total 57.212ms
,03-17 07:10:39.615  3820  3820 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(248/xdmInitExternalStorageState)] DATA_DIR_PATH [/data]
,03-17 07:10:39.615  3820  3820 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(249/xdmInitExternalStorageState)] EXTERNAL_DIR_PATH [/storage/emulated/0]
,03-17 07:10:39.625  3820  3863 I DBG_POLICYDM: [com.policydm.agent.XDMTask(171/xdmAgentTaskHandler)] XEVENT_DM_INIT
,03-17 07:10:39.625  1922  1922 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 480x640
,03-17 07:10:39.625  1922  1922 I GFX GPU raster: eglCreateImageKHR: EGL_SUCCESS
,03-17 07:10:39.625  3820  3820 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(250/xdmInitExternalStorageState)] EXTERNAL_SD_DIR_PATH [/storage/extSdCard]
03-17 07:10:39.625  1922  1922 I glCompressedTexImage2D: took 0.471198ms for 480*163840 texture 37811
,03-17 07:10:39.625  1922  1922 I draw setup: took 0.892239ms for 480*640 texture 37811
03-17 07:10:39.625  1922  1922 E GFX GPU raster: drawn
,03-17 07:10:39.635  3820  3863 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
03-17 07:10:39.635   304   304 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 656us total 18.754ms
03-17 07:10:39.635  3820  3820 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(251/xdmInitExternalStorageState)] POLICY_DIR_PATH [/data/user/0/com.policydm/cache]
03-17 07:10:39.635  1922  1922 I GFX GPU raster ASTC: took 6.183333ms for 480*640 texture 12
03-17 07:10:39.635  1922  1922 I GFX raster: took 6.235365ms for 480*640 texture 0
03-17 07:10:39.635  1922  1922 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb77bdce8 bitmapCt=12 bitmapW=480 bitmapH=640 BitmapInternalFormat=93b3, Counterpart=0xb77d0d10 counterpartCT=4 counterpartW=480 counterparth=640
,03-17 07:10:39.635  3820  3820 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(253/xdmInitExternalStorageState)] bExternalStorageAvailable [true]
,03-17 07:10:39.635  3820  3820 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(254/xdmInitExternalStorageState)] bExternalSDStorageAvailable [false]
03-17 07:10:39.645  3820  3820 I DBG_POLICYDM: [com.policydm.XDMApplication(580/xdmWakeLockRelease)] 
03-17 07:10:39.645  3820  3820 I DBG_POLICYDM: [com.policydm.XDMApplication(585/xdmWakeLockRelease)] m_WakeLock is release!!
,03-17 07:10:39.655  3820  3863 I DBG_POLICYDM: [com.policydm.XDMApplication(619/xdmGetNotibarState)] get NotibarState : 7
,03-17 07:10:39.655   304   304 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 596us total 18.907ms
,03-17 07:10:39.655  3820  3863 I DBG_POLICYDM: [com.policydm.ui.XUINotificationManager(48/xuiSetIndicator)] Indicator id : 7
,03-17 07:10:39.655  3820  3820 I DBG_POLICYDM: [com.policydm.XDMApplication(179/onCreate)] DMApplication Start !
,03-17 07:10:39.675  3820  3863 I DBG_POLICYDM: [com.policydm.XDMApplication(611/xdmSetNotibarState)] set NotibarState : 7
03-17 07:10:39.675  3679  3679 E YouTube MDX: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,03-17 07:10:39.685  3820  3863 I DBG_POLICYDM: [com.policydm.db.XDBAESCrypt(217/xdbGetCryptionkey)] try read dbString
,03-17 07:10:39.705  1922  1922 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
,03-17 07:10:39.705  1922  1922 I GFX construct_block_size_descriptor_2d second part: took 2.221042ms for 0*0 texture 0,
,03-17 07:10:39.705  1022  1046 W libprocessgroup: failed to open /acct/uid_1000/pid_2199/cgroup.procs: No such file or directory
,03-17 07:10:39.715  1922  1922 I GFX generate_partition_tables: took 7.611510ms for 0*0 texture 0
,03-17 07:10:39.715  1922  1922 I GFX raster: took 11.820885ms for 176*144 texture 0
,03-17 07:10:39.715  1922  1922 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb77addf8 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b2, Counterpart=0xb77d0d30 counterpartCT=4 counterpartW=176 counterparth=144
,03-17 07:10:39.725  3820  3863 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(428/xdbGetFUMOStatus)] xdbGetFUMOStatus : 0
,03-17 07:10:39.725  3820  3863 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(587/xdbGetFUMOInitiatedType)] Initiated Type: 0
,03-17 07:10:39.735  3887  3887 D PreloadFilterInstaller: uses FILTER_DB_VER_1,
03-17 07:10:39.735  3820  3863 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(72/xpollingCheckVersionInfo)] 
,03-17 07:10:39.735  3820  3864 I DBG_POLICYDM: [com.policydm.agent.XDMUITask(191/xdmUIEvent)] XUI_DM_IDLE_STATE :true
03-17 07:10:39.735  1922  1922 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
03-17 07:10:39.735  1349  3678 D ScoverManager: serviceVersion : 16908288
,03-17 07:10:39.735  1922  1922 I GFX construct_block_size_descriptor_2d second part: took 2.475521ms for 0*0 texture 0
,03-17 07:10:39.745  1922  1922 I GFX generate_partition_tables: took 6.301406ms for 0*0 texture 0
,03-17 07:10:39.745  1922  1922 I GFX raster: took 10.900937ms for 176*144 texture 0
03-17 07:10:39.745  1922  1922 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb77be358 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b1, Counterpart=0xb77d2a20 counterpartCT=4 counterpartW=176 counterparth=144
,03-17 07:10:39.755  1922  1922 D ScoverManager: registerListener
,03-17 07:10:39.755  3887  3887 E SQLiteLog: (284) automatic index on titles(filter_id)
,03-17 07:10:39.755  1022  1597 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
03-17 07:10:39.755  1022  1129 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:39.755  1022  1129 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:39.755  1022  1129 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:39.755  1022  1129 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:39.755  1022  1507 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
,03-17 07:10:39.755  1022  1507 D CoverManager.StateNotifier: registerListenerCallback : binder = android.os.BinderProxy@5e675e2, pid : 1922, uid : 1001, type : 1
,03-17 07:10:39.765  3820  3863 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(271/xpollingCheckTimer)] 
,03-17 07:10:39.775  3820  3864 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
03-17 07:10:39.775  1022  1321 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,03-17 07:10:39.775  3919  3919 E Zygote  : MountEmulatedStorage()
,03-17 07:10:39.775  3919  3919 E Zygote  : v2
03-17 07:10:39.775  3919  3919 I libpersona: KNOX_SDCARD checking this for 10014
,03-17 07:10:39.775  3919  3919 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:39.775  3919  3919 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 07:10:39.775  1022  1129 I ActivityManager: Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=3919 uid=10014 gids={50014, 9997, 3003} abi=armeabi-v7a
,03-17 07:10:39.775  3820  3863 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(285/xpollingCheckTimer)] savedpollingtime : 2016/03/20/16:34:31
03-17 07:10:39.775  3919  3919 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 07:10:39.775  3820  3863 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(286/xpollingCheckTimer)] currentTime : 2016/03/17/07:10:39
,03-17 07:10:39.785  3919  3919 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-17 07:10:39.785  1922  1922 D InCall  : InCallPresenter -  - Finished InCallPresenter.setUp
,03-17 07:10:39.785  3820  3864 I DBG_POLICYDM: [com.policydm.db.XDBProfileListAdp(258/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,03-17 07:10:39.795  3820  3863 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(290/xpollingCheckTimer)] Restart Timer..
,03-17 07:10:39.795  3820  3863 I DBG_POLICYDM: [com.policydm.XDMApplication(626/xdmStartAlarm)] Alarm ID: 0
,03-17 07:10:39.795  3887  3887 I FilterProviderReceiver: onReceive in FilterProviderReceiver
03-17 07:10:39.795  3887  3887 I FilterProviderReceiver: onReceive in FilterProviderReceiver when ACTION_BOOT_COMPLETED
,03-17 07:10:39.795  3820  3838 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,03-17 07:10:39.795  3820  3838 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,03-17 07:10:39.805  3820  3864 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(399/xnotiPushAdpExcuteResumeNoti)] nSessionSaveState:0
03-17 07:10:39.805  1022  1035 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,03-17 07:10:39.805  3820  3838 I DBG_POLICYDM: [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
03-17 07:10:39.805  3820  3864 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(400/xnotiPushAdpExcuteResumeNoti)] nNotiUiEvent:0
,03-17 07:10:39.805  1022  1520 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:39.805  3919  3919 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 07:10:39.805  3820  3864 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(401/xnotiPushAdpExcuteResumeNoti)] nNotiRetryCount:0
03-17 07:10:39.805  3919  3919 D ActivityThread: Added TimaKeyStore provider
03-17 07:10:39.805  1022  1392 I AudioService: getStreamVolume 3 index 0
03-17 07:10:39.805  3820  3864 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(441/xnotiPushAdpExcuteResumeNoti)] Current NOTI NOT SAVED State. EXIT.
03-17 07:10:39.805  1022  1520 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:39.805  1022  1520 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:39.805  1022  1520 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:39.805  3820  3864 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(267/xnotiPushAdpClearSessionStatus)] 
03-17 07:10:39.805  1022  1404 D LocationManagerService: getProviders()=[passive]
03-17 07:10:39.805  3820  3864 I DBG_POLICYDM: [com.policydm.ui.XUIAdapter(39/xuiAdpSetUiMode)] nDmUiMode : 0
,03-17 07:10:39.815  3820  3864 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(439/xdbSetFUMOStatus)] xdbSetFUMOStatus : 0
,03-17 07:10:39.825  3936  3936 E Zygote  : MountEmulatedStorage()
,03-17 07:10:39.825  3936  3936 E Zygote  : v2
03-17 07:10:39.825  3936  3936 I libpersona: KNOX_SDCARD checking this for 10098
03-17 07:10:39.825  3936  3936 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:39.825  3936  3936 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 07:10:39.825  1022  1520 I ActivityManager: Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=3936 uid=10098 gids={50098, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,03-17 07:10:39.825  1022  1520 I ActivityManager: Killing 3027:com.qualcomm.timeservice/1000 (adj 15): empty #31
,03-17 07:10:39.825  3936  3936 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 07:10:39.825  3936  3936 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 07:10:39.835  3820  3837 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,03-17 07:10:39.845  3820  3837 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,03-17 07:10:39.845  3820  3837 I DBG_POLICYDM: [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,03-17 07:10:39.845  3936  3936 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 07:10:39.845  3936  3936 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:39.865  3820  3864 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(565/xdbSetFUMOInitiatedType)] Initiated Type: 0
,03-17 07:10:39.875  1022  1035 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:39.875  1022  1035 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:39.875  1022  1035 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:39.875  1022  1035 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:39.885  3936  3936 D PackageIntentReceiver: ACTION_BOOT_COMPLETED
,03-17 07:10:39.885  3956  3956 E Zygote  : MountEmulatedStorage()
03-17 07:10:39.885  3956  3956 I libpersona: KNOX_SDCARD checking this for 1000
03-17 07:10:39.885  3956  3956 E Zygote  : v2
03-17 07:10:39.885  3956  3956 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:39.885  3936  3936 D PackageIntentReceiver: jangil::ACTION_BOOT_COMPLETED::do not need pkg remove..
,03-17 07:10:39.885  3956  3956 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 07:10:39.895  1022  1035 I ActivityManager: Start proc com.fmm.dm for broadcast com.fmm.dm/.XDMBroadcastReceiver: pid=3956 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,03-17 07:10:39.895  3956  3956 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 07:10:39.895  3956  3956 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 07:10:39.895  1022  1035 I ActivityManager: Killing 2995:com.android.providers.calendar/u0a37 (adj 15): empty #31
03-17 07:10:39.895  1022  1035 I ActivityManager: Killing 3099:com.sec.android.widgetapp.SPlannerAppWidget/u0a130 (adj 15): empty #32
,03-17 07:10:39.895  1022  1035 I ActivityManager: Killing 2812:com.sec.spp.push/u0a32 (adj 15): empty #33
,03-17 07:10:39.895  3820  3863 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(312/xPollingReportReStartAlarm)] 
,03-17 07:10:39.905  1022  1035 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:39.905  1022  1035 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:39.905  1022  1035 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:39.905  1022  1035 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:39.925  3976  3976 E Zygote  : MountEmulatedStorage()
03-17 07:10:39.925  3976  3976 I libpersona: KNOX_SDCARD checking this for 10099
03-17 07:10:39.925  3976  3976 E Zygote  : v2
03-17 07:10:39.925  3976  3976 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:39.925  1022  1035 I ActivityManager: Start proc com.google.android.gm for broadcast com.google.android.gm/.GoogleMailDeviceStartupReceiver: pid=3976 uid=10099 gids={50099, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-17 07:10:39.935  3956  3956 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:39.935  1022  1035 I ActivityManager: Killing 2614:com.android.calendar/u0a131 (adj 15): empty #31
03-17 07:10:39.935  3956  3956 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:39.935  3976  3976 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 07:10:39.935  3976  3976 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 07:10:39.935  1206  1206 D StatusBar.NetworkController: refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-17 07:10:39.935  1206  1206 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-17 07:10:39.935  1206  1206 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 07:10:39.945  3976  3976 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-17 07:10:39.945  1206  1206 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 07:10:39.945  1206  1206 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 07:10:39.945  1206  1206 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 07:10:39.955  3800  3974 I ContactAccountLoggerTas: canRun() : Opted Out
,03-17 07:10:39.965  3820  3864 I DBG_POLICYDM: [com.policydm.db.XDB(1825/xdbSetBackUpServerUrl)] 
,03-17 07:10:39.965  1022  1902 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:39.965  1022  1902 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 07:10:39.965  1022  1902 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,03-17 07:10:39.965  3976  3976 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:39.965  3976  3976 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:39.975  1022  1404 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:39.975  1022  1404 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 07:10:39.975  1022  1404 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,03-17 07:10:39.985  1022  1392 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:39.985  1022  1392 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 07:10:39.985  1022  1392 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,03-17 07:10:39.985   256   518 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/cache/
03-17 07:10:39.985   256   518 W Vold    : Returning OperationFailed - no handler for errno 0
,03-17 07:10:39.985  3679  3679 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
,03-17 07:10:39.985   256   518 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/files/
03-17 07:10:39.985   256   518 W Vold    : Returning OperationFailed - no handler for errno 0
,03-17 07:10:39.995  3679  3679 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
,03-17 07:10:39.995   256   518 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/files/
03-17 07:10:39.995   256   518 W Vold    : Returning OperationFailed - no handler for errno 0
,03-17 07:10:39.995  3679  3679 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
,03-17 07:10:40.005  1022  1520 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:40.005  1022  1520 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 07:10:40.005  1022  1520 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,03-17 07:10:40.025  1022  1046 W libprocessgroup: failed to open /acct/uid_1000/pid_3027/cgroup.procs: No such file or directory
,03-17 07:10:40.025  1022  1046 W libprocessgroup: failed to open /acct/uid_10130/pid_3099/cgroup.procs: No such file or directory
,03-17 07:10:40.025  1022  1046 W libprocessgroup: failed to open /acct/uid_10037/pid_2995/cgroup.procs: No such file or directory
03-17 07:10:40.025  1022  1046 W libprocessgroup: failed to open /acct/uid_10032/pid_2812/cgroup.procs: No such file or directory
03-17 07:10:40.025  1022  1046 W libprocessgroup: failed to open /acct/uid_10131/pid_2614/cgroup.procs: No such file or directory
,03-17 07:10:40.035  3820  3863 I DBG_POLICYDM: [com.policydm.XDMApplication(626/xdmStartAlarm)] Alarm ID: 1
,03-17 07:10:40.045  3820  3863 I DBG_POLICYDM: [com.policydm.agent.XDMTask(203/xdmAgentTaskHandler)] XEVENT_DM_INIT : Initialized
,03-17 07:10:40.045  1022  1035 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:40.045  1022  1035 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-17 07:10:40.045  1022  1035 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,03-17 07:10:40.055  1022  1392 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,03-17 07:10:40.065  1022  1404 I ActivityManager: Killing 3185:com.android.keychain/1000 (adj 15): empty #31
,03-17 07:10:40.105  1349  3678 I LockPatternUtils: isSmartCardAuthenticationAvailable: false
,03-17 07:10:40.105  3956  3956 I DBG_FMMDM: [50.20.150420][Line:608][xdmGetCheckWifiOnlyModel] isWifiOnly : false
,03-17 07:10:40.115  3693  3744 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 0 sec
,03-17 07:10:40.115  1349  3678 D Settings_Utils: isSupportVNFestival SM-A300FU XEO
,03-17 07:10:40.115  3800  3975 W GAV2    : Thread[Background Non-Blocking-1,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,03-17 07:10:40.135  3820  3864 I DBG_POLICYDM: [com.policydm.db.XDBProfileAdp(207/xdbSetChangedProtocol)] xdbSetChangedProtocol : false
,03-17 07:10:40.135  3956  3956 I DBG_FMMDM: [50.20.150420][Line:27][xdmInitialize] AgVOOqV7UpXFblBk29Ld3aZrOQhtHCYbjdszx6nYrjFYzeVOvvlPUzE67GnQVups
,03-17 07:10:40.145  3956  3956 I DBG_FMMDM: [50.20.150420][Line:28][xdmInitialize] c8aaBoNX+zCI65M7gVNTej45+K/MzxjqVpKd5x0FMtd3o63nokSujfTEanrHiU41
,03-17 07:10:40.145  3956  3956 I DBG_FMMDM: [50.20.150420][Line:29][xdmInitialize] X2Nl5mgTWVn0/a90MNBgtYshxOiQq2MqI4oMf2Nwz6I=
,03-17 07:10:40.145  1022  1667 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:40.145  1022  1667 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 07:10:40.145  1022  1667 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,03-17 07:10:40.145  1022  1404 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:40.145  1022  1404 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 07:10:40.145  1022  1404 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,03-17 07:10:40.155  1022  1597 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:40.155  1022  1597 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:40.155  1022  1597 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:40.155  1022  1597 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:40.175  4022  4022 E Zygote  : MountEmulatedStorage()
03-17 07:10:40.175  4022  4022 E Zygote  : v2
03-17 07:10:40.175  4022  4022 I libpersona: KNOX_SDCARD checking this for 1000
03-17 07:10:40.175  4022  4022 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:40.175  1022  1597 I ActivityManager: Start proc com.sec.pcw.device for content provider com.sec.pcw.device/.contentprovider.DMProvider: pid=4022 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-17 07:10:40.185  4022  4022 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 07:10:40.185  4022  4022 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 07:10:40.185  4022  4022 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 07:10:40.195  1022  1659 I ActivityManager: Killing 2697:com.android.chrome/u0a77 (adj 15): empty #31
,03-17 07:10:40.215  4022  4022 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:40.215  4022  4022 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:40.225  1022  1046 W libprocessgroup: failed to open /acct/uid_1000/pid_3185/cgroup.procs: No such file or directory
,03-17 07:10:40.235  1022  1321 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:40.235  1022  1321 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 07:10:40.235  1022  1321 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,03-17 07:10:40.235  1022  1034 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:40.235  1022  1034 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 07:10:40.235  1022  1034 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,03-17 07:10:40.235  3679  4020 W MessageQueue: Handler (android.os.Handler) {2cb6a869} sending message to a Handler on a dead thread
03-17 07:10:40.235  3679  4020 W MessageQueue: java.lang.IllegalStateException: Handler (android.os.Handler) {2cb6a869} sending message to a Handler on a dead thread
03-17 07:10:40.235  3679  4020 W MessageQueue: 	at android.os.MessageQueue.enqueueMessage(MessageQueue.java:325)
03-17 07:10:40.235  3679  4020 W MessageQueue: 	at android.os.Handler.enqueueMessage(Handler.java:631)
03-17 07:10:40.235  3679  4020 W MessageQueue: 	at android.os.Handler.sendMessageAtTime(Handler.java:600)
03-17 07:10:40.235  3679  4020 W MessageQueue: 	at android.os.Handler.sendMessageDelayed(Handler.java:570)
03-17 07:10:40.235  3679  4020 W MessageQueue: 	at android.os.Handler.post(Handler.java:326)
03-17 07:10:40.235  3679  4020 W MessageQueue: 	at ffw.a(SourceFile:327)
03-17 07:10:40.235  3679  4020 W MessageQueue: 	at guw.a(SourceFile:120)
03-17 07:10:40.235  3679  4020 W MessageQueue: 	at guf.c(SourceFile:26)
03-17 07:10:40.235  3679  4020 W MessageQueue: 	at gui.run(SourceFile:297)
03-17 07:10:40.235  3679  4020 W MessageQueue: 	at android.os.Handler.handleCallback(Handler.java:739)
03-17 07:10:40.235  3679  4020 W MessageQueue: 	at android.os.Handler.dispatchMessage(Handler.java:95)
03-17 07:10:40.235  3679  4020 W MessageQueue: 	at android.os.Looper.loop(Looper.java:145)
03-17 07:10:40.235  3679  4020 W MessageQueue: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-17 07:10:40.265  4022  4022 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
,03-17 07:10:40.275  4022  4022 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
,03-17 07:10:40.275  4022  4022 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,03-17 07:10:40.285  4022  4035 D PCWCLIENTTRACE_DMContentProvider: [URIMatcher] - result : 2,
,03-17 07:10:40.295  3956  3956 I DBG_FMMDM: [50.20.150420][Line:40][onCreate] FMMApplication NOT Start !
,03-17 07:10:40.295  3956  3956 I DBG_FMMDM: [50.20.150420][Line:67][onReceive] android.intent.action.BOOT_COMPLETED
,03-17 07:10:40.295  3956  3956 I DBG_FMMDM: [50.20.150420][Line:309][onReceive] android.intent.action.BOOT_COMPLETED
,03-17 07:10:40.295  1022  1507 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:40.295  1022  1507 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:40.295  1022  1507 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:40.295  1022  1507 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:40.305  1349  3678 W ResourceType: Failure getting entry for 0x7f0202b4 (t=1 e=692) (error -75)
,03-17 07:10:40.305  3820  3864 I DBG_POLICYDM: [com.policydm.db.XDBProfileListAdp(258/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,03-17 07:10:40.305  4038  4038 E Zygote  : MountEmulatedStorage()
03-17 07:10:40.305  4038  4038 E Zygote  : v2
03-17 07:10:40.305  4038  4038 I libpersona: KNOX_SDCARD checking this for 1000
03-17 07:10:40.305  4038  4038 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:40.315  4038  4038 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 07:10:40.315  1022  1507 I ActivityManager: Start proc com.fmm.ds for broadcast com.fmm.ds/.XDSBroadcastReceiver: pid=4038 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,03-17 07:10:40.315  1909  1909 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.qualcomm.qti.services.secureui.BootReceiver.onReceive:30 android.app.ActivityThread.handleReceiver:3125 
03-17 07:10:40.315  3800  3975 W GAV2    : Thread[Background Non-Blocking-1,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().,
,03-17 07:10:40.315  4038  4038 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 07:10:40.315  1022  1507 I ActivityManager: Killing 2682:com.android.email/u0a141 (adj 15): empty #31
,03-17 07:10:40.315  1022  1507 I ActivityManager: Killing 3243:com.sec.android.gallery3d/u0a39 (adj 15): empty #32
03-17 07:10:40.315  4038  4038 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 07:10:40.315  1349  3678 W ResourceType: Failure getting entry for 0x7f020510 (t=1 e=1296) (error -75)
,03-17 07:10:40.325  3800  3995 I ContactAccountLoggerTas: canRun() : Opted Out
,03-17 07:10:40.325  1022  1035 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:40.325  1022  1035 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-17 07:10:40.325  1022  1035 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.qualcomm.qti.services.secureui:sui_service, destAppInfo.processName = com.qualcomm.qti.services.secureui:sui_service
,03-17 07:10:40.335  3820  3864 I DBG_POLICYDM: [com.policydm.db.XDBNotiAdp(38/xdbNotiExistInfo)] Noti Exist : false
,03-17 07:10:40.335  1909  1909 D SecUISvc: Service started flags 0 startId 1
03-17 07:10:40.335  1909  4049 D SecUISvc: Thread created.
,03-17 07:10:40.335  4038  4038 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:40.335  1022  1667 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:40.335  1022  1667 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:40.335  1022  1667 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:40.335  1022  1667 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:40.335  4038  4038 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:40.355  4058  4058 E Zygote  : MountEmulatedStorage()
,03-17 07:10:40.355  4058  4058 E Zygote  : v2
03-17 07:10:40.355  4058  4058 I libpersona: KNOX_SDCARD checking this for 10026
03-17 07:10:40.355  4058  4058 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:40.355  4058  4058 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 07:10:40.355  1022  1667 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=4058 uid=10026 gids={50026, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-17 07:10:40.365  4058  4058 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 07:10:40.365  4058  4058 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-17 07:10:40.385  4058  4058 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:40.385  4058  4058 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:40.415  1022  1046 W libprocessgroup: failed to open /acct/uid_10077/pid_2697/cgroup.procs: No such file or directory
,03-17 07:10:40.415  1022  1046 W libprocessgroup: failed to open /acct/uid_10141/pid_2682/cgroup.procs: No such file or directory
03-17 07:10:40.415  1022  1046 W libprocessgroup: failed to open /acct/uid_10039/pid_3243/cgroup.procs: No such file or directory
,03-17 07:10:40.425  4038  4038 I DBG_FMMDS: [50.18.150420][Line:56][onCreate] FMMDS Application Start
,03-17 07:10:40.485  1022  1321 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,03-17 07:10:40.495  4038  4038 I DBG_FMMDS: [50.18.150420][Line:28][<init>] XDBHelper First Call!!!
,03-17 07:10:40.495  1022  1404 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,03-17 07:10:40.495  1022  1034 I AudioService: getStreamVolume 3 index 0
,03-17 07:10:40.495  3800  3800 I MediaRouter: Found default route: MediaRouter.RouteInfo{ uniqueId=android/mo:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,03-17 07:10:40.525  4022  4035 D PCWCLIENTTRACE_DMContentProvider: [URIMatcher] - result : 2
,03-17 07:10:40.525  3800  3800 I FavoriteContactNamesSup: get() : Execute runnable (UI thread)
03-17 07:10:40.525  3800  3800 I ContactLabelSupplier: get() : Execute runnable (UI thread)
,03-17 07:10:40.525  3800  3974 I ContactLabelSupplier: get() : OptedIn = false
,03-17 07:10:40.535  4038  4038 E DBG_FMMDS: Warning!!! [50.18.150420][Line:36][xdsDevAdpGetDeviceID] DeviceID read fail!!!!!!!!
,03-17 07:10:40.535  4038  4038 I DBG_FMMDS: [50.18.150420][Line:43][xdbDBInit] 
,03-17 07:10:40.545  3679  4016 D AndroidHttpClient: [NALSECURITY] isMmsRequest() : CoreProtocolPNames.USER_AGENT = Dalvik/2.1.0 (Linux; U; Android 5.0.2; SM-A300FU Build/LRX22G)
03-17 07:10:40.545  3679  4016 D AndroidHttpClient: [NALSECURITY] checkMmsSendPermission() : isMmsRequest() = false method = GET
,03-17 07:10:40.545  3679  4016 I System.out: Thread-559(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,03-17 07:10:40.545  3679  4016 I System.out: Thread-559(ApacheHTTPLog):isSBSettingEnabled false
,03-17 07:10:40.545  3679  4016 I System.out: Thread-559(ApacheHTTPLog):isShipBuild true
03-17 07:10:40.545  3679  4016 I System.out: Thread-559(ApacheHTTPLog):SMARTBONDING_ENABLED is false
03-17 07:10:40.545  3679  4016 I System.out: Thread-559(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,03-17 07:10:40.545   277  1011 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
03-17 07:10:40.545   277  1011 D Netd    : getNetworkForDns: using netid 502 for uid 10161
,03-17 07:10:40.575  1022  1507 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,03-17 07:10:40.585  1022  1035 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:40.585  1022  1035 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:40.585  1022  1035 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:40.585  1022  1035 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:40.595  1022  1597 V VibratorService: hasVibrator - useVibetonz: true
,03-17 07:10:40.605  4084  4084 E Zygote  : MountEmulatedStorage()
03-17 07:10:40.605  4084  4084 E Zygote  : v2
03-17 07:10:40.605  4084  4084 I libpersona: KNOX_SDCARD checking this for 10055
03-17 07:10:40.605  4084  4084 I libpersona: KNOX_SDCARD not a persona
03-17 07:10:40.605  4084  4084 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,03-17 07:10:40.605  4084  4084 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
03-17 07:10:40.605  4084  4084 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
03-17 07:10:40.605  1022  1035 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=4084 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
03-17 07:10:40.615  1022  1392 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,03-17 07:10:40.625  4084  4084 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:40.625  4084  4084 D ActivityThread: Added TimaKeyStore provider,
,03-17 07:10:40.625  4038  4038 I DBG_FMMDS: [50.18.150420][Line:63][onCreate] onCreate Db Initialized
,03-17 07:10:40.725  4084  4084 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,03-17 07:10:40.735  4058  4058 I Finsky  : [1] com.google.android.finsky.FinskyApp.onCreate(358): Initializing network with DFE https://android.clients.google.com/fdfe/
,03-17 07:10:40.735  4038  4038 I DBG_FMMDS: [50.18.150420][Line:363][xdsGetAccount] UZnlD2ITkPmcCbh9srjpN/1auPpXZ1U0673eFrlr5G7ujCmOnoTUvn8Wy3q3+o8W
,03-17 07:10:40.745  4038  4038 I DBG_FMMDS: [50.18.150420][Line:279][xdsDefaultProfileCheckServerID] VG44Fy9kdMk+/k3D4uP4d3do/3rw5AoymvTy0wXAnzc=
,03-17 07:10:40.745  3622  3833 I System.out: pool-10-thread-1 calls detatch()
,03-17 07:10:40.745  4038  4038 I DBG_FMMDS: [50.18.150420][Line:363][xdsGetAccount] UZnlD2ITkPmcCbh9srjpN/1auPpXZ1U0673eFrlr5G7ujCmOnoTUvn8Wy3q3+o8W
,03-17 07:10:40.745  4038  4038 I DBG_FMMDS: [50.18.150420][Line:376][xdsCheckSamsungAccountForChina] VG44Fy9kdMk+/k3D4uP4d3do/3rw5AoymvTy0wXAnzc=
,03-17 07:10:40.745  4038  4038 I DBG_FMMDS: [50.18.150420][Line:89][onReceive] Receive Intent : android.intent.action.BOOT_COMPLETED
,03-17 07:10:40.755  4038  4038 I DBG_FMMDS: [50.18.150420][Line:248][onReceive] XCOMMON_INTENT_NOTI_CALLLOG_CLICK
,03-17 07:10:40.765  4084  4084 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,03-17 07:10:40.765  4084  4084 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
03-17 07:10:40.765  4084  4084 D UserAnalysis: Create SecureDbHelper
,03-17 07:10:40.785  1022  1129 W ActivityManager: Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,03-17 07:10:40.785  1022  1035 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,03-17 07:10:40.795  3870  3870 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,03-17 07:10:40.795  3870  3870 I FOTA_Client: [com.sec.android.fotaclient.FotaUpdaterReceiver(93/onReceive)] Auto update settings is activated
,03-17 07:10:40.795  3870  3870 I FOTA_Client: [IlIlIIllllIllIIIIIll(81/llllIIIllIlIIIIllllI)] Polling time is vaild
,03-17 07:10:40.815  1022  1659 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:40.815  1022  1659 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-17 07:10:40.815  1022  1659 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,03-17 07:10:40.815  3870  3870 W FOTA_Client: [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,03-17 07:10:40.815  1880  1880 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 07:10:40.825  1880  1880 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 07:10:40.825  1022  1667 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:40.825  1022  1667 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:40.825  1022  1667 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:40.825  1022  1667 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:40.835  3976  4114 I Gmail   : Observing account changes for notifications
,03-17 07:10:40.835  4118  4118 E Zygote  : MountEmulatedStorage()
03-17 07:10:40.835  4118  4118 E Zygote  : v2
03-17 07:10:40.835  4118  4118 I libpersona: KNOX_SDCARD checking this for 10013
03-17 07:10:40.835  4118  4118 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:40.835  4118  4118 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 07:10:40.835  4118  4118 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 07:10:40.835  4118  4118 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-17 07:10:40.835  1022  1667 I ActivityManager: Start proc com.google.android.onetimeinitializer for broadcast com.google.android.onetimeinitializer/.OneTimeInitializerReceiver: pid=4118 uid=10013 gids={50013, 9997} abi=armeabi-v7a
,03-17 07:10:40.845  1022  1667 I ActivityManager: Killing 3374:com.mobeam.barcodeService/1000 (adj 15): empty #31
,03-17 07:10:40.845  3976  4116 I Gmail   : getAccountsCursor
,03-17 07:10:40.855  4084  4084 D IntelligenceServiceApplication: onCreate()
,03-17 07:10:40.855  4084  4084 D UserAnalysis.UserAnalysisBroadcastReceiver: Intent(action: android.intent.action.BOOT_COMPLETED) is received.
,03-17 07:10:40.865  1022  1667 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:40.865  1022  1667 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:40.865  1022  1667 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:40.865  1022  1667 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:40.875  4118  4118 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:40.875  4118  4118 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:40.875  4134  4134 E Zygote  : MountEmulatedStorage(),
03-17 07:10:40.875  4134  4134 E Zygote  : v2
03-17 07:10:40.875  4134  4134 I libpersona: KNOX_SDCARD checking this for 10056
,03-17 07:10:40.875  4134  4134 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:40.875  4134  4134 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 07:10:40.885  1022  1667 I ActivityManager: Start proc com.samsung.android.scloud.backup for broadcast com.samsung.android.scloud.backup/.SCloudBackupReceiver: pid=4134 uid=10056 gids={50056, 9997, 1028, 1015, 3003} abi=armeabi-v7a
03-17 07:10:40.885  1022  1667 I ActivityManager: Killing 3413:org.simalliance.openmobileapi.service/1101 (adj 15): empty #31
,03-17 07:10:40.885  1022  3349 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-17 07:10:40.885  4134  4134 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 07:10:40.885  4134  4134 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 07:10:40.895  1880  1880 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 07:10:40.905  4084  4084 D IntelligenceServiceApplication: no applications having user consent for prediction
,03-17 07:10:40.905  4134  4134 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:40.905  4134  4134 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:40.915  4084  4084 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,03-17 07:10:40.915  3976  3976 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,03-17 07:10:40.935  1022  3313 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 com.android.server.ssrm.ad.ec:-1 com.android.server.ssrm.ae.handleMessage:-1 android.os.Handler.dispatchMessage:102 android.os.Looper.loop:145 
,03-17 07:10:40.945  1349  3678 I LockPatternUtils: isSmartCardAuthenticationAvailable: false
,03-17 07:10:40.975  4058  4058 I Finsky  : [1] com.google.android.finsky.services.DailyHygiene.a(122): No need to run daily hygiene.
,03-17 07:10:40.975  4118  4118 V OneTimeInitializerReceiver: OneTimeInitializerReceiver.onReceive
,03-17 07:10:40.975  1022  1035 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:40.975  1022  1035 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 07:10:40.975  1022  1035 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.onetimeinitializer, destAppInfo.processName = com.google.android.onetimeinitializer
,03-17 07:10:40.985  1022  1046 W libprocessgroup: failed to open /acct/uid_1101/pid_3413/cgroup.procs: No such file or directory
,03-17 07:10:40.985  1022  1046 W libprocessgroup: failed to open /acct/uid_1000/pid_3374/cgroup.procs: No such file or directory
,03-17 07:10:40.985  1022  1392 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:40.985  1022  1392 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 07:10:40.985  1022  1392 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
03-17 07:10:40.985  4058  4058 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,03-17 07:10:40.985  4058  4058 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,03-17 07:10:40.985  4118  4163 V OneTimeService: OneTimeService.onHandleIntent
,03-17 07:10:40.995  4084  4084 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,03-17 07:10:40.995  4084  4084 D UserAnalysis.MyPlaceDbPreference: Constructor Preference
,03-17 07:10:40.995  1022  1507 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:40.995  1022  1507 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 07:10:40.995  1022  1507 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,03-17 07:10:41.005  1022  1597 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:41.005  1022  1597 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 07:10:41.005  1022  1597 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,03-17 07:10:41.005  1022  1404 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,03-17 07:10:41.015  1022  1902 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:41.015  1022  1902 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 07:10:41.015  1022  1902 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,03-17 07:10:41.015  1022  1520 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:41.015  1022  1520 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 07:10:41.015  1022  1520 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,03-17 07:10:41.055  3679  4016 I System.out: Thread-559 calls detatch()
,03-17 07:10:41.055   288   288 E SMD     : DCD OFF
,03-17 07:10:41.085  3976  4168 E Gmail   : Error finding the version of the Email provider.....
03-17 07:10:41.085  3976  4168 E Gmail   : android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
03-17 07:10:41.085  3976  4168 E Gmail   : 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:165)
03-17 07:10:41.085  3976  4168 E Gmail   : 	at com.google.android.gm.EmailMigrationService.aU(SourceFile:1236)
03-17 07:10:41.085  3976  4168 E Gmail   : 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:188)
03-17 07:10:41.085  3976  4168 E Gmail   : 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-17 07:10:41.085  3976  4168 E Gmail   : 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 07:10:41.085  3976  4168 E Gmail   : 	at android.os.Looper.loop(Looper.java:145)
03-17 07:10:41.085  3976  4168 E Gmail   : 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-17 07:10:41.085  3976  4168 W EmailMigration: We do not support migrating this version of the Email provider.
,03-17 07:10:41.115  3693  3744 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 1 sec
,03-17 07:10:41.215  1022  1507 I art     : Explicit concurrent mark sweep GC freed 21070(1252KB) AllocSpace objects, 3(54KB) LOS objects, 33% free, 24MB/36MB, paused 2.386ms total 197.523ms
,03-17 07:10:41.225  1022  1507 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:41.225  1022  1507 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 07:10:41.225  1022  1507 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:41.225  1022  1902 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:41.235  1022  1902 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-17 07:10:41.235  1022  1902 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,03-17 07:10:41.235  3976  4082 I Gmail   : getAccountsCursor
,03-17 07:10:41.235  1022  1597 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:41.235  1022  1597 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 07:10:41.235  1022  1597 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,03-17 07:10:41.245  1880  1880 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 07:10:41.255  1022  1597 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:41.255  1022  1597 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 07:10:41.255  1022  1597 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,03-17 07:10:41.285  4134  4134 I sCloudBackupApp: sCloudBackupApp Version Info : 4.04.7.KK_APP
,03-17 07:10:41.295  1022  1667 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:41.295  1022  1667 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:41.295  1022  1667 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:41.295  1022  1667 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:41.295  3120  3727 I FactoryTestApp: [IPCWriterToSecPhoneService$disConnectSecPhoneService](3727)  
,03-17 07:10:41.305  4179  4179 E Zygote  : MountEmulatedStorage()
03-17 07:10:41.305  4179  4179 E Zygote  : v2
03-17 07:10:41.305  4179  4179 I libpersona: KNOX_SDCARD checking this for 10058
03-17 07:10:41.305  4179  4179 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:41.305  4179  4179 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 07:10:41.315  1022  1667 I ActivityManager: Start proc com.samsung.android.scloud.sync for broadcast com.samsung.android.scloud.sync/com.sec.android.sCloudSync.Receivers.TimeChangedReceiver: pid=4179 uid=10058 gids={50058, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-17 07:10:41.315  4179  4179 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 07:10:41.315  4179  4179 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 07:10:41.315  1022  1520 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:41.315  1022  1520 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 07:10:41.315  1022  1520 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,03-17 07:10:41.335   304   304 I art     : Explicit concurrent mark sweep GC freed 8718(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 624us total 21.181ms
,03-17 07:10:41.335  4058  4154 D Volley  : [601] g.b: Cache cleared.
,03-17 07:10:41.335  4058  4109 D Volley  : [595] g.b: Cache cleared.
,03-17 07:10:41.335  1880  1880 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 07:10:41.335  1022  1034 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:41.335  4179  4179 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:41.335  1022  1034 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 07:10:41.335  1022  1034 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
03-17 07:10:41.335  4179  4179 D ActivityThread: Added TimaKeyStore provider
03-17 07:10:41.335  1880  1880 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 07:10:41.345  1022  1035 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:41.345  1022  1035 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 07:10:41.345  1022  1035 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.process.gapps
,03-17 07:10:41.345  1022  1321 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
03-17 07:10:41.345   304   304 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 593us total 16.650ms
,03-17 07:10:41.345  1022  1129 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:41.345  1022  1129 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 07:10:41.345  1022  1129 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,03-17 07:10:41.355  1022  1392 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,03-17 07:10:41.365  1022  1667 I ActivityManager: Killing 3403:flipboard.boxer.app/u0a97 (adj 15): empty #31
,03-17 07:10:41.365   304   304 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 591us total 16.636ms
,03-17 07:10:41.375  1022  1597 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:41.375  1022  1597 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:41.375  3976  3976 E ActivityThread: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.J@2448a9ad that was originally bound here
03-17 07:10:41.375  3976  3976 E ActivityThread: android.app.ServiceConnectionLeaked: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.J@2448a9ad that was originally bound here
03-17 07:10:41.375  3976  3976 E ActivityThread: 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1144)
03-17 07:10:41.375  3976  3976 E ActivityThread: 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1038)
03-17 07:10:41.375  3976  3976 E ActivityThread: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2154)
03-17 07:10:41.375  3976  3976 E ActivityThread: 	at android.app.ContextImpl.bindService(ContextImpl.java:2137)
03-17 07:10:41.375  3976  3976 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
03-17 07:10:41.375  3976  3976 E ActivityThread: 	at com.android.emailcommon.service.H.a(SourceFile:181)
03-17 07:10:41.375  3976  3976 E ActivityThread: 	at com.android.emailcommon.service.H.mb(SourceFile:224)
03-17 07:10:41.375  3976  3976 E ActivityThread: 	at com.android.email.service.n.j(SourceFile:160)
03-17 07:10:41.375  3976  3976 E ActivityThread: 	at com.android.email.provider.b.a(SourceFile:171)
03-17 07:10:41.375  3976  3976 E ActivityThread: 	at com.android.email.provider.b.F(SourceFile:115)
03-17 07:10:41.375  3976  3976 E ActivityThread: 	at com.android.email.service.EmailBroadcastProcessorService.kD(SourceFile:305)
03-17 07:10:41.375  3976  3976 E ActivityThread: 	at com.android.email.service.EmailBroadcastProcessorService.onHandleIntent(SourceFile:130)
03-17 07:10:41.375  3976  3976 E ActivityThread: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-17 07:10:41.375  3976  3976 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 07:10:41.375  3976  3976 E ActivityThread: 	at android.os.Looper.loop(Looper.java:145)
03-17 07:10:41.375  3976  3976 E ActivityThread: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-17 07:10:41.375  1022  1597 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,03-17 07:10:41.375  1022  1597 W ActivityManager: Unbind failed: could not find connection for android.os.BinderProxy@176fe3ae
,03-17 07:10:41.375  4058  4058 I Finsky  : [1] com.google.android.finsky.receivers.h.a(1107): Installer kick - no action, not running yet
,03-17 07:10:41.385  4058  4199 D Ads     : Skipping gmscore version check
03-17 07:10:41.385  4058  4058 I Finsky  : [1] com.google.android.finsky.g.j.run(208): Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
03-17 07:10:41.385  4058  4058 I Finsky  : [1] com.google.android.finsky.g.j.run(214): Finished loading 1 libraries.
,03-17 07:10:41.385  2173  2173 I Hs20UtilService: Starting #7
,03-17 07:10:41.385  1022  1667 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:41.385  2173  2196 I Hs20UtilService: Message received 5003
03-17 07:10:41.385  1022  1667 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:41.385  1022  1667 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:41.385  1651  4198 I GoogleHttpClient: GMS http client unavailable, use old client
03-17 07:10:41.385  1022  1667 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:41.395  3976  4171 E SQLiteLog: (283) recovered 78 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,03-17 07:10:41.405  4201  4201 E Zygote  : MountEmulatedStorage()
,03-17 07:10:41.405  4201  4201 E Zygote  : v2
03-17 07:10:41.405  4201  4201 I libpersona: KNOX_SDCARD checking this for 10102
03-17 07:10:41.405  4201  4201 I libpersona: KNOX_SDCARD not a persona
03-17 07:10:41.405  4201  4201 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 07:10:41.405  1022  1667 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.BootReceiver: pid=4201 uid=10102 gids={50102, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,03-17 07:10:41.405  4201  4201 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 07:10:41.405  4201  4201 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
03-17 07:10:41.405  1022  1392 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:41.405  1022  1392 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 07:10:41.405  1022  1392 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:41.415  1349  3678 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver$InitSerachDBThread.run:130 <bottom of call stack> 
,03-17 07:10:41.415  1022  1129 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:41.415  1022  1129 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 07:10:41.415  1022  1129 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,03-17 07:10:41.425  1022  1321 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:41.425  1022  1321 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 07:10:41.425  1022  1321 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,03-17 07:10:41.435  1349  3678 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver$InitSerachDBThread.run:131 <bottom of call stack> 
,03-17 07:10:41.435  1349  3678 I SettingSearch/SearchIntentReceiver: InitSerachDBThread thread end!
,03-17 07:10:41.445  4179  4179 I ExternalOEMControlProvider: onCreate
,03-17 07:10:41.445  4201  4201 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:41.445  4201  4201 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:41.455  2661  2661 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Thu Mar 17 07:10:41 GMT+01:00 2016
,03-17 07:10:41.455  1022  1404 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:41.455  1022  1404 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:41.455  1022  1404 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,03-17 07:10:41.465  2661  2661 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,03-17 07:10:41.465  1022  1667 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:41.465  1022  1667 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:41.465  1022  1667 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:41.465  1022  1667 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:41.465  2141  4211 D FileApkUtils: Optimizing (staging complete)
,03-17 07:10:41.475  2141  4211 D FileApkUtils: Optimizing: DynamiteModules-prod.apk [1dad65bca29c108ad7dad5d3707435ff0555d8adf974340225c102890df71a23]
,03-17 07:10:41.475  2661  2661 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,03-17 07:10:41.475  2141  4211 I art     : DexFile_isDexOptNeeded failed to open oat file '/data/dalvik-cache/arm/data@data@com.google.android.gms@app_chimera@m@00000000@DynamiteModules-prod.apk@classes.dex' for file location '/data/data/com.google.android.gms/app_chimera/m/00000000/DynamiteModules-prod.apk': Failed to open oat filename for reading: No such file or directory
,03-17 07:10:41.475  4201  4201 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-17 07:10:41.475  1022  1046 W libprocessgroup: failed to open /acct/uid_10097/pid_3403/cgroup.procs: No such file or directory
,03-17 07:10:41.475  1022  1392 D SettingsProvider: name = PREVIOUS_SYS_TIME
03-17 07:10:41.475  1022  1392 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-17 07:10:41.475  1022  1392 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-17 07:10:41.475  1022  1392 D SettingsProvider: selectionArgs: false
03-17 07:10:41.475  1022  1392 D SettingsProvider: selectionArgs: 10058
03-17 07:10:41.475  1022  1392 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-17 07:10:41.475  1022  1392 D SettingsProvider: ret = -1
,03-17 07:10:41.475  2661  2661 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,03-17 07:10:41.485  2661  2661 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,03-17 07:10:41.485  4219  4219 E Zygote  : MountEmulatedStorage()
03-17 07:10:41.485  4219  4219 I libpersona: KNOX_SDCARD checking this for 1000
03-17 07:10:41.485  4219  4219 E Zygote  : v2
03-17 07:10:41.485  4219  4219 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:41.485  2661  4218 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
03-17 07:10:41.485  4219  4219 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 07:10:41.485  4219  4219 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 07:10:41.485  4219  4219 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 07:10:41.485  1022  1667 I ActivityManager: Start proc com.sec.android.app.servicemodeapp for broadcast com.sec.android.app.servicemodeapp/.ServiceModeAppBroadcastReceiver: pid=4219 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,03-17 07:10:41.495  1022  1667 I ActivityManager: Killing 3043:com.sec.android.app.clockpackage/u0a81 (adj 15): empty #31
,03-17 07:10:41.495  2661  4218 I KLMS-2.5.123: : KLMSIntentService(): BOOT_COMPLETED
,03-17 07:10:41.495  1022  1667 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:41.495  1022  1667 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:41.495  1022  1667 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:41.495  1022  1667 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:41.515  4232  4232 E Zygote  : MountEmulatedStorage()
,03-17 07:10:41.515  4232  4232 E Zygote  : v2,
03-17 07:10:41.515  4232  4232 I libpersona: KNOX_SDCARD checking this for 10020
03-17 07:10:41.515  4232  4232 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 07:10:41.515  4232  4232 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:41.515  1022  1667 I ActivityManager: Start proc com.android.managedprovisioning for broadcast com.android.managedprovisioning/.BootReminder: pid=4232 uid=10020 gids={50020, 9997, 1028, 3003} abi=armeabi-v7a
03-17 07:10:41.515  4232  4232 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 07:10:41.515  4232  4232 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 07:10:41.525  1022  1520 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:41.525  1022  1520 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 07:10:41.525  1022  1520 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,03-17 07:10:41.535  4219  4219 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:41.535  4219  4219 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:41.545  1022  1046 W libprocessgroup: failed to open /acct/uid_10081/pid_3043/cgroup.procs: No such file or directory
,03-17 07:10:41.545  4232  4232 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:41.545  4232  4232 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:41.555  3919  3919 I RlzPingService: Setting next ping for 1458799841559
,03-17 07:10:41.565  4058  4058 I Finsky  : [1] com.google.android.finsky.b.j.a(273): result=false type=4
03-17 07:10:41.565  1022  1392 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10058
03-17 07:10:41.565  2141  4211 D DexOptUtils: Module /data/data/com.google.android.gms/app_chimera/m/00000000/DynamiteModules-prod.apk is already optimized. Bailing.
,03-17 07:10:41.575  1022  1659 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:41.575  1022  1659 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 07:10:41.575  1022  1659 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
03-17 07:10:41.575  1022  1902 D SettingsProvider: name = PREVIOUS_ELAPSED_TIME
03-17 07:10:41.575  1022  1902 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-17 07:10:41.575  1022  1902 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-17 07:10:41.575  1022  1902 D SettingsProvider: selectionArgs: false
03-17 07:10:41.575  1022  1902 D SettingsProvider: selectionArgs: 10058
03-17 07:10:41.575  1022  1902 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-17 07:10:41.575  1022  1902 D SettingsProvider: ret = -1
,03-17 07:10:41.585  1206  1206 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 07:10:41.585  1022  1902 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10058
,03-17 07:10:41.585  1206  1206 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 07:10:41.595  1022  1659 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:41.595  1022  1659 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 07:10:41.595  1022  1659 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:41.605  4058  4058 I Finsky  : [1] com.google.android.finsky.services.ar.a(1049): Restore complete with 0 success and 0 failed.
,03-17 07:10:41.605  4219  4219 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,03-17 07:10:41.605  1022  1597 I ActivityManager: Killing 3010:com.sec.android.app.taskmanager/u0a153 (adj 15): empty #31
,03-17 07:10:41.615  2661  2661 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,03-17 07:10:41.645  1022  1129 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:41.645  1022  1129 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:41.645  1022  1129 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:41.645  1022  1129 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:41.655  1022  1129 I ActivityManager: Start proc com.samsung.android.MtpApplication for broadcast com.samsung.android.MtpApplication/.MtpReceiver: pid=4257 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,03-17 07:10:41.665  1022  1129 I ActivityManager: Killing 3459:com.sec.usbsettings/1000 (adj 15): empty #31
,03-17 07:10:41.665  4257  4257 E Zygote  : MountEmulatedStorage()
03-17 07:10:41.665  4257  4257 E Zygote  : v2
,03-17 07:10:41.665  4257  4257 I libpersona: KNOX_SDCARD checking this for 1000
03-17 07:10:41.665  4257  4257 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:41.665  4219  4219 I ServiceMode: received = ACTION_BOOT_COMPLETED
03-17 07:10:41.665  4219  4219 I ServiceMode: setReferenceIsDumpState : 0
,03-17 07:10:41.675  1022  1321 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:41.675  1022  1321 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:41.675  1022  1321 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:41.675  1022  1321 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:41.695  4264  4264 E Zygote  : MountEmulatedStorage()
,03-17 07:10:41.695  4264  4264 E Zygote  : v2
03-17 07:10:41.695  4264  4264 I libpersona: KNOX_SDCARD checking this for 1000
03-17 07:10:41.695  4264  4264 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:41.705  1022  1321 I ActivityManager: Start proc com.wssnps for broadcast com.wssnps/.smlNpsReceiverDefault: pid=4264 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,03-17 07:10:41.705  1022  1321 I ActivityManager: Killing 3472:com.samsung.android.app.colorblind/1000 (adj 15): empty #31
,03-17 07:10:41.745  1022  1046 W libprocessgroup: failed to open /acct/uid_10153/pid_3010/cgroup.procs: No such file or directory
,03-17 07:10:41.745  1022  1046 W libprocessgroup: failed to open /acct/uid_1000/pid_3459/cgroup.procs: No such file or directory
03-17 07:10:41.745  1022  1046 W libprocessgroup: failed to open /acct/uid_1000/pid_3472/cgroup.procs: No such file or directory
,03-17 07:10:41.795  4257  4257 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
03-17 07:10:41.795  4264  4264 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 07:10:41.795  4257  4257 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 07:10:41.795  4264  4264 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 07:10:41.795  4257  4257 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 07:10:41.795  4264  4264 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 07:10:41.815  3976  4171 E File    : fail readDirectory() errno=2
,03-17 07:10:41.825  3976  4185 I Gmail   : notifyAccountChanged
,03-17 07:10:41.825  3976  4083 I Gmail   : getAccountsCursor
,03-17 07:10:41.835  3976  4185 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,03-17 07:10:41.835  4264  4264 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:41.835  4264  4264 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:41.845  4257  4257 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:41.845  4257  4257 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:41.845  3976  4185 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,03-17 07:10:41.855  3976  4185 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
,03-17 07:10:41.855  3976  4185 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
,03-17 07:10:41.875  1022  1035 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:41.875  1022  1035 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 07:10:41.875  1022  1035 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:41.875  1022  1129 I ActivityManager: Killing 3489:flipboard.app/u0a96 (adj 15): empty #31
,03-17 07:10:41.915  3976  4117 I Gmail   : getAccountsCursor
,03-17 07:10:41.925  4264  4264 D NPS_WSSNPS: [] android.intent.action.BOOT_COMPLETED
,03-17 07:10:41.925  4264  4264 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.wssnps.smlNpsReceiverDefault.onReceive:35 android.app.ActivityThread.handleReceiver:3125 
,03-17 07:10:41.925  1022  1659 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:41.925  1022  1659 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:41.925  4257  4257 E MTPRx   : In MtpReceiverandroid.intent.action.BOOT_COMPLETED
,03-17 07:10:41.925  1022  1659 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.wssnps, destAppInfo.processName = com.wssnps
,03-17 07:10:41.935  4264  4264 D NPS_WSSNPS: [] Service onCreate!!
,03-17 07:10:41.935  1022  1404 D SecContentProvider2: uri = 14 selection = getSealedState
03-17 07:10:41.935  1022  1404 D SecContentProvider2: mCursor = null
,03-17 07:10:41.935  1022  1392 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:41.935  1022  1392 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:41.935  1022  1392 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:41.935  1022  1392 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:41.935  1022  1902 D SecContentProvider2: uri = 14 selection = getSealedUsbMassStorageState
03-17 07:10:41.935  1022  1902 D SecContentProvider2: mCursor = null
,03-17 07:10:41.935  4257  4257 V MTPRx   : sealedState: false
,03-17 07:10:41.935  4257  4257 V MTPRx   : sealedUsbMassStorageState: false
,03-17 07:10:41.945  4293  4293 E Zygote  : MountEmulatedStorage()
03-17 07:10:41.945  4293  4293 E Zygote  : v2
03-17 07:10:41.945  4293  4293 I libpersona: KNOX_SDCARD checking this for 1000
03-17 07:10:41.945  4293  4293 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:41.955  4293  4293 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 07:10:41.955  1022  1392 I ActivityManager: Start proc com.samsung.android.app.accesscontrol for broadcast com.samsung.android.app.accesscontrol/.AccessControlReceiver: pid=4293 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,03-17 07:10:41.955  4293  4293 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 07:10:41.955  4293  4293 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 07:10:41.965  1022  1321 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:41.965  1022  1321 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 07:10:41.965  1022  1321 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-17 07:10:41.965  1022  1520 D SettingsProvider: name = mtp_usb_connection_status
,03-17 07:10:41.975  1880  1880 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 07:10:41.975  1022  1902 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:41.975  1022  1902 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 07:10:41.975  1022  1902 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:41.975  1022  1507 D SettingsProvider: name = media_player_mode
,03-17 07:10:41.975  4264  4300 D NPS_WSSNPS: [50.150321] NpsServiceTask Start
,03-17 07:10:41.975  1206  1206 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 07:10:41.975  4293  4293 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 07:10:41.985  4293  4293 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:41.995  1022  1046 W libprocessgroup: failed to open /acct/uid_10096/pid_3489/cgroup.procs: No such file or directory
,03-17 07:10:42.045  1022  1034 D SettingsProvider: name = access_control_enabled
,03-17 07:10:42.045  1022  1404 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:42.045  1022  1404 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:42.045  1022  1404 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:42.045  1022  1404 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:42.055  4317  4317 E Zygote  : MountEmulatedStorage()
03-17 07:10:42.055  4317  4317 E Zygote  : v2
03-17 07:10:42.055  4317  4317 I libpersona: KNOX_SDCARD checking this for 10065
03-17 07:10:42.055  4317  4317 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:42.055  4317  4317 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 07:10:42.055  1022  1404 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=4317 uid=10065 gids={50065, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-17 07:10:42.065  1022  1404 I ActivityManager: Killing 2424:com.android.mms/u0a41 (adj 15): empty #31
,03-17 07:10:42.065  4317  4317 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 07:10:42.065  4317  4317 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 07:10:42.065  4264  4264 D NPS_WSSNPS: [50.150321] smlDBHelper
,03-17 07:10:42.075  1022  1392 D SettingsProvider: name = mtp_usb_conditions_met
,03-17 07:10:42.085  1022  1321 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:42.085  1022  1321 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 07:10:42.085  1022  1321 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:42.085  1206  1206 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 07:10:42.095  1022  1667 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:42.095  1022  1667 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 07:10:42.095  1022  1667 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:42.095  1022  1035 D SettingsProvider: name = mtp_running_status
,03-17 07:10:42.095  4317  4317 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:42.095  4317  4317 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:42.105  2141  4254 I Icing   : Storage manager: low false usage 2.11MB avail 9.94GB capacity 11.63GB
,03-17 07:10:42.115  4264  4264 I NPS_WSSNPS: [50.150321] AsyncBulkFlagCheck
,03-17 07:10:42.115  4201  4336 I Babel   : MmsConfig: mnc/mcc: 0/0
03-17 07:10:42.115  4201  4336 I Babel   : MmsConfig.loadMmsSettings
,03-17 07:10:42.115  4201  4336 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
03-17 07:10:42.115  4201  4336 I Babel   : MmsConfig.loadFromDatabase
,03-17 07:10:42.115  3693  3744 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 2 sec
,03-17 07:10:42.125  1206  1206 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 07:10:42.125  1022  1321 D CountryDetector: No listener is left
,03-17 07:10:42.135  1022  1507 D SettingsProvider: name = media_mount_count
,03-17 07:10:42.135  4264  4337 I NPS_WSSNPS: [50.150321] IsRemain_AsyncBulkCheck
,03-17 07:10:42.145  1206  1206 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 07:10:42.145  4264  4337 I NPS_WSSNPS: [50.150321] IsRemain_Asyncing nothing
,03-17 07:10:42.145  4264  4337 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:2069 android.content.ContextWrapper.stopService:538 com.wssnps.h.run:107 java.util.Timer$TimerImpl.run:284 <bottom of call stack> 
,03-17 07:10:42.155  1022  1321 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:42.155  1022  1321 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:42.155  1022  1321 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.wssnps, destAppInfo.processName = com.wssnps
,03-17 07:10:42.155  4264  4264 D NPS_WSSNPS: [50.150321] Service onDestroy
,03-17 07:10:42.185  4317  4317 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.intent.action.BOOT_COMPLETED // null
,03-17 07:10:42.195  4264  4264 I NPS_WSSNPS: [50.150321] smlBRConfigurationDelete
,03-17 07:10:42.195  4264  4264 I NPS_WSSNPS: [50.150321] smlBRMessageDelete
,03-17 07:10:42.205  4264  4264 I NPS_WSSNPS: [50.150321] smlBREmailDelete
,03-17 07:10:42.205  4264  4264 I NPS_WSSNPS: [50.150321] smlBRNetworkDelete
,03-17 07:10:42.205  4201  4336 E Babel   : canonicalizeMccMnc: invalid mccmnc 
03-17 07:10:42.205  4201  4336 I Babel   : MmsConfig.loadFromResources
,03-17 07:10:42.205  4264  4264 I NPS_WSSNPS: [50.150321] smlBRCallLogDelete
,03-17 07:10:42.205  4201  4336 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
03-17 07:10:42.205  4201  4336 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
,03-17 07:10:42.205  4264  4264 I NPS_WSSNPS: [50.150321] smlBRMiniDiaryDelete
,03-17 07:10:42.215  4264  4264 I NPS_WSSNPS: [50.150321] smlBRPenMemoMDelete
,03-17 07:10:42.215  4264  4264 I NPS_WSSNPS: [50.150321] smlBRSMemoDelete
,03-17 07:10:42.215  4264  4264 I NPS_WSSNPS: [50.150321] cpuBooster release : false
,03-17 07:10:42.215  4264  4264 D NPS_WSSNPS: [50.150321] dsServerSocket close
,03-17 07:10:42.225  1022  1392 I ActivityManager: Killing 3521:com.sec.android.app.safetyassurance/u0a43 (adj 15): empty #31
,03-17 07:10:42.225  1880  1880 D ChimeraCfgMgr: Reading stored module config
,03-17 07:10:42.235  1022  1035 D SettingsProvider: name = mtp_sync_alive
,03-17 07:10:42.235  1022  1046 W libprocessgroup: failed to open /acct/uid_10041/pid_2424/cgroup.procs: No such file or directory
,03-17 07:10:42.245  1206  1206 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 07:10:42.245  1022  1392 D SettingsProvider: name = sdcard_launch
,03-17 07:10:42.245  1022  1035 I ActivityManager: Killing 3536:com.google.android.configupdater/u0a82 (adj 15): empty #31
,03-17 07:10:42.255  4201  4329 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,03-17 07:10:42.255  1206  1206 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 07:10:42.265  4201  4329 W AudioCapabilities: Unsupported mime audio/evrc
,03-17 07:10:42.265  4201  4329 W AudioCapabilities: Unsupported mime audio/qcelp
,03-17 07:10:42.275  1022  1034 D SettingsProvider: name = boot_time_connected
,03-17 07:10:42.285  1206  1206 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 07:10:42.285  4201  4329 W AudioCapabilities: Unsupported mime audio/mpeg-L1
,03-17 07:10:42.295  1022  1047 I ActivityManager: Waited long enough for: ServiceRecord{329a04b0 u0 com.sec.android.daemonapp/.ap.accuweather.WeatherClockService}
,03-17 07:10:42.295  4201  4329 W AudioCapabilities: Unsupported mime audio/mpeg-L2
,03-17 07:10:42.295  1022  1520 D SettingsProvider: name = mtp_open_session
,03-17 07:10:42.295  1880  1880 D WearableService: callingUid 10011, callindPid: 1880
,03-17 07:10:42.305  2141  2141 W InstanceID/Rpc: Found 10011
,03-17 07:10:42.315  1022  1046 W libprocessgroup: failed to open /acct/uid_10043/pid_3521/cgroup.procs: No such file or directory
03-17 07:10:42.315  1022  1046 W libprocessgroup: failed to open /acct/uid_10082/pid_3536/cgroup.procs: No such file or directory
,03-17 07:10:42.315  3165  3286 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,03-17 07:10:42.315  1206  1206 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 07:10:42.325  4201  4215 W art     : Suspending all threads took: 25.684ms
,03-17 07:10:42.325  4201  4201 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,03-17 07:10:42.325  1880  1880 E GmsWearableNodeHelper: GoogleApiClient connection failed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,03-17 07:10:42.325  4201  4329 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,03-17 07:10:42.335  4201  4329 W AudioCapabilities: Unsupported mime audio/x-ima
,03-17 07:10:42.335  4201  4329 W AudioCapabilities: Unsupported mime audio/qcelp
,03-17 07:10:42.335  4201  4329 W AudioCapabilities: Unsupported mime audio/evrc
,03-17 07:10:42.345  4022  4022 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
03-17 07:10:42.345  4022  4022 I PCWCLIENTTRACE_PushUtil: sales region : global
03-17 07:10:42.345  4022  4022 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
03-17 07:10:42.345  4022  4022 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.intent.action.BOOT_COMPLETED
,03-17 07:10:42.345  4201  4329 W VideoCapabilities: Unsupported mime video/wvc1
,03-17 07:10:42.355  4201  4329 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,03-17 07:10:42.355  4022  4022 D PCWCLIENTTRACE_SYSTEMReceiver: ACTION_BOOTUP - Version: 4.82
03-17 07:10:42.355  4022  4022 D PCWCLIENTTRACE_SYSTEMReceiver: ACTION_BOOTUP - Push type: [SPP, GCM]
,03-17 07:10:42.365  1022  1902 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:42.365  1022  1902 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 07:10:42.365  1022  1902 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:42.365  4201  4329 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
,03-17 07:10:42.365  4201  4329 W VideoCapabilities: Unsupported mime video/wvc1
,03-17 07:10:42.365  4201  4329 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,03-17 07:10:42.375  4022  4022 W PCWCLIENTTRACE_AccountUtil: [hasSamungAccount] - No Samsung Account
,03-17 07:10:42.385  1022  1597 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:42.385  1022  1597 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 07:10:42.385  1022  1597 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:42.395  4201  4329 W VideoCapabilities: Unsupported mime video/x-ms-wmv7
,03-17 07:10:42.405  1022  1392 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:42.405  1022  1392 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 07:10:42.405  1022  1392 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:42.405  4022  4022 I PCWCLIENTTRACE_SecurePreferencesJNI: [GetString-S]
,03-17 07:10:42.405  1022  1321 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:42.405  1022  1321 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 07:10:42.405  1022  1321 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:42.415  4022  4022 I ReactiveServiceManager: Supported : 1
,03-17 07:10:42.415  1022  1520 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x2040
,03-17 07:10:42.415  1022  1520 D QSEECOMAPI: : App is not loaded in QSEE
,03-17 07:10:42.415  4201  4215 W art     : Suspending all threads took: 19.525ms
,03-17 07:10:42.425  4201  4329 W VideoCapabilities: Unsupported mime video/x-ms-wmv8
,03-17 07:10:42.425  4201  4329 W VideoCapabilities: Unsupported mime video/mp43
,03-17 07:10:42.425  1022  1520 D QSEECOMAPI: : Loaded image: APP id = 10
,03-17 07:10:42.435  1022  1404 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:42.435  1022  1404 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 07:10:42.435  1022  1404 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-17 07:10:42.435  1022  1520 D QSEECOMAPI: : QSEECom_dealloc_memory 
03-17 07:10:42.435  1022  1520 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 10
,03-17 07:10:42.435  1022  1520 E terrier : handleString: Failed to handle string(-4)
03-17 07:10:42.435  1022  1520 E terrier : Java_com_android_server_ReactiveService_GetString: error code = [-4]
03-17 07:10:42.435  4022  4022 D PCWCLIENTTRACE_SecurePreferencesJNI: getString is null
,03-17 07:10:42.435  4022  4022 I PCWCLIENTTRACE_SecurePreferencesJNI: [GetString-E]
,03-17 07:10:42.445  2141  4347 D GCM     : COMPAT: Multi user not supported
,03-17 07:10:42.445  1022  1507 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:42.445  1022  1507 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 07:10:42.445  1022  1507 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-17 07:10:42.445  4201  4329 W VideoCapabilities: Unsupported mime video/sorenson
,03-17 07:10:42.445  4022  4022 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
03-17 07:10:42.445  4022  4022 I PCWCLIENTTRACE_PushUtil: sales region : global
03-17 07:10:42.445  4022  4022 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
03-17 07:10:42.445  4022  4022 E PCWCLIENTTRACE_PCWHandler: [ensureRegistration] - No Samsung account
,03-17 07:10:42.455  1022  1659 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:42.455  1022  1659 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 07:10:42.455  1022  1659 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:42.455  4201  4329 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,03-17 07:10:42.455  1022  1902 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:42.455  1022  1902 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:42.455  1022  1902 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:42.455  1022  1902 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:42.465  4350  4350 E Zygote  : MountEmulatedStorage()
03-17 07:10:42.465  4350  4350 I libpersona: KNOX_SDCARD checking this for 10028
03-17 07:10:42.465  4350  4350 E Zygote  : v2
03-17 07:10:42.465  4350  4350 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:42.475  4350  4350 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 07:10:42.475  1022  1902 I ActivityManager: Start proc com.vlingo.midas for broadcast com.vlingo.midas/com.vlingo.core.facade.lmtt.LmttReceiver: pid=4350 uid=10028 gids={50028, 9997, 1028, 1015, 3003, 3002, 3001} abi=armeabi-v7a
,03-17 07:10:42.475  4350  4350 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 07:10:42.475  4350  4350 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
03-17 07:10:42.475  1022  1902 I ActivityManager: Killing 3622:com.dropbox.android/u0a88 (adj 15): empty #31
,03-17 07:10:42.475  1022  1321 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:42.475  1022  1321 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-17 07:10:42.475  1022  1321 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:42.495  1022  1902 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:42.495  1022  1902 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 07:10:42.495  1022  1902 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:42.495  1022  1392 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:42.495  1022  1392 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 07:10:42.495  1022  1392 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:42.505  4201  4329 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,03-17 07:10:42.515  4350  4350 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:42.515  4350  4350 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:42.515  1880  4366 D GCM     : GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED
,03-17 07:10:42.535  1022  1520 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:42.535  1022  1520 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 07:10:42.535  1022  1520 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:42.545  2141  4347 I GCoreUlr: Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}]
,03-17 07:10:42.555  1022  1035 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:42.555  1022  1046 W libprocessgroup: failed to open /acct/uid_10088/pid_3622/cgroup.procs: No such file or directory
03-17 07:10:42.555  1022  1035 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 07:10:42.555  1022  1035 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:42.555  4201  4201 V Babel   : babel boot account: SMS
,03-17 07:10:42.555  4201  4201 V Babel   : babel boot account: thalitester@gmail.com
,03-17 07:10:42.555  1022  1129 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:42.555  1022  1129 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:42.555  1022  1129 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:42.555  1022  1129 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:42.565  4372  4372 E Zygote  : MountEmulatedStorage()
,03-17 07:10:42.575  4372  4372 E Zygote  : v2
03-17 07:10:42.575  4372  4372 I libpersona: KNOX_SDCARD checking this for 1000
03-17 07:10:42.575  4372  4372 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:42.575  4372  4372 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 07:10:42.575  4372  4372 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 07:10:42.575  1022  1129 I ActivityManager: Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.BootBroadcastReceiver: pid=4372 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,03-17 07:10:42.575  4372  4372 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 07:10:42.575  1022  1129 I ActivityManager: Killing 2783:com.google.android.apps.plus/u0a117 (adj 15): empty #31
,03-17 07:10:42.605  1022  1392 I ActivityManager: Killing 3146:com.test.thalitest/u0a167 (adj 15): empty #31
,03-17 07:10:42.625  4372  4372 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:42.625  4372  4372 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:42.625  1880  1880 I GCoreUlr: DispatchingService.onCreate()
,03-17 07:10:42.635  1022  1022 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.dsi.ant.server.AntService.startService:135 com.dsi.ant.server.startup.BootCompletedReceiver.onReceive:41 
,03-17 07:10:42.635  1022  1022 W ContextImpl: Implicit intents with startService are not safe: Intent { act=com.dsi.ant.server.IAntHal } android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.dsi.ant.server.AntService.startService:135 
,03-17 07:10:42.635  1022  1022 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:42.635  1022  1022 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:42.635  1022  1022 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:42.635  1022  1022 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:42.655  4388  4388 E Zygote  : MountEmulatedStorage()
03-17 07:10:42.655  4388  4388 E Zygote  : v2
03-17 07:10:42.655  4388  4388 I libpersona: KNOX_SDCARD checking this for 1000
03-17 07:10:42.655  4388  4388 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:42.655  4388  4388 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 07:10:42.655  4388  4388 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 07:10:42.655  4388  4388 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 07:10:42.655  1022  1022 I ActivityManager: Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=4388 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,03-17 07:10:42.685  4388  4388 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:42.685  4388  4388 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:42.685  1651  1744 I art     : Explicit concurrent mark sweep GC freed 3894(165KB) AllocSpace objects, 0(0B) LOS objects, 47% free, 4MB/8MB, paused 754us total 28.343ms
,03-17 07:10:42.695  1651  1663 W SQLiteConnectionPool: A SQLiteConnection object for database '+data+user+0+com_google_android_gsf+databases+gservices_db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,03-17 07:10:42.775  1022  1129 I art     : Explicit concurrent mark sweep GC freed 22211(1134KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 24MB/36MB, paused 2.612ms total 159.486ms
,03-17 07:10:42.775  1022  1100 V AlarmManager: waitForAlarm result :4
,03-17 07:10:42.855  1022  1100 V AlarmManager: waitForAlarm result :4
,03-17 07:10:42.875  1022  1046 W libprocessgroup: failed to open /acct/uid_10167/pid_3146/cgroup.procs: No such file or directory
03-17 07:10:42.875  1022  1046 W libprocessgroup: failed to open /acct/uid_10117/pid_2783/cgroup.procs: No such file or directory
,03-17 07:10:42.915  4350  4350 I System.out: Inside onCreate() of WakeupTriggerProvide
,03-17 07:10:42.915  4350  4350 I System.out: Inside WakeupProvider
,03-17 07:10:42.935  1022  1392 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:42.935  1022  1392 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 07:10:42.935  1022  1392 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,03-17 07:10:42.965  2141  4405 I CheckinService: Disabling old GoogleServicesFramework version
,03-17 07:10:42.995  4350  4350 I VlingoApplication: VlingoApplication appVersion ='11.7.0.1.40139', coreVersion = '2.6.1.16800', ro.csc.sales_code=XEO
,03-17 07:10:43.005  1880  4408 I GCoreUlr: WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED
,03-17 07:10:43.025  4388  4388 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:53 android.app.ActivityThread.handleReceiver:3125 
,03-17 07:10:43.025  1022  1321 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:43.025  1022  1321 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:43.025  1022  1321 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,03-17 07:10:43.035  1022  1129 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:43.035  1022  1129 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:43.035  1022  1129 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:43.035  1022  1129 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:43.045  1022  1129 I ActivityManager: Start proc com.sec.bcservice for broadcast com.sec.bcservice/.BCServiceReceiver: pid=4411 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,03-17 07:10:43.045  4411  4411 E Zygote  : MountEmulatedStorage()
03-17 07:10:43.045  4411  4411 E Zygote  : v2
03-17 07:10:43.045  4411  4411 I libpersona: KNOX_SDCARD checking this for 1000
03-17 07:10:43.045  4411  4411 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:43.045  4411  4411 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 07:10:43.045  4411  4411 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 07:10:43.055  4411  4411 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 07:10:43.065   304   304 I art     : Explicit concurrent mark sweep GC freed 8751(372KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 601us total 20.117ms
,03-17 07:10:43.075  3820  3863 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,03-17 07:10:43.075  4411  4411 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:43.075  4411  4411 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:43.085  1022  1404 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:43.085  1022  1404 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:43.085   304   304 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 588us total 17.210ms
03-17 07:10:43.085  1022  1404 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:43.085  1022  1404 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:43.095  4411  4411 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,03-17 07:10:43.105   304   304 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 577us total 16.771ms
,03-17 07:10:43.115  3820  3863 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,03-17 07:10:43.115  4428  4428 E Zygote  : MountEmulatedStorage()
03-17 07:10:43.115  4428  4428 I libpersona: KNOX_SDCARD checking this for 1000,
03-17 07:10:43.115  4428  4428 E Zygote  : v2
03-17 07:10:43.115  4428  4428 I libpersona: KNOX_SDCARD not a persona
03-17 07:10:43.115  4428  4428 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 07:10:43.115  4428  4428 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 07:10:43.115  4428  4428 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 07:10:43.125  1022  1404 I ActivityManager: Start proc com.sec.knox.knoxsetupwizardclient for broadcast com.sec.knox.knoxsetupwizardclient/.detector.SetupWizardDetectorReceiver: pid=4428 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-17 07:10:43.125  3693  3744 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 3 sec
,03-17 07:10:43.125  1022  1404 I ActivityManager: Killing 3709:com.sec.providers.settingsearch/u0a146 (adj 15): empty #31
,03-17 07:10:43.125  3820  3863 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/sepolicy,
03-17 07:10:43.125  3820  3863 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
03-17 07:10:43.125  3820  3863 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
03-17 07:10:43.125  3820  3863 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
03-17 07:10:43.125  3820  3863 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
03-17 07:10:43.135  2141  2155 W art     : Suspending all threads took: 28.925ms
03-17 07:10:43.135  3820  3863 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,03-17 07:10:43.145  4411  4411 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.bcservice.BCServiceReceiver.onReceive:18 android.app.ActivityThread.handleReceiver:3125 
,03-17 07:10:43.145  1022  1392 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:43.145  1022  1392 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:43.145  1022  1392 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.bcservice, destAppInfo.processName = com.sec.bcservice
03-17 07:10:43.145  4350  4350 I VlingoAndroidCore: AppName: SamsungTproject, Core: 2.6.1.16800, SDK: 2.0.2137, EDM:16800
,03-17 07:10:43.145  4428  4428 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:43.145  4428  4428 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:43.155  4411  4411 I F_PHONE : [[com.sec.bcservice]] bind SecPhone Service with FactoryPhone
,03-17 07:10:43.155  4411  4411 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.samsung.android.sec_platform_library.FactoryPhone.connectToRilService:95 com.samsung.android.sec_platform_library.FactoryPhone.<init>:61 com.sec.bcservice.BroadcastService.onCreate:146 
,03-17 07:10:43.155  1022  1597 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:43.155  1022  1597 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:43.155  1022  1597 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:43.155  1022  1597 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:43.175  2141  2152 W SQLiteConnectionPool: A SQLiteConnection object for database '+data+data+com_google_android_gms+databases+networkstatistics_sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,03-17 07:10:43.195  4444  4444 E Zygote  : MountEmulatedStorage()
03-17 07:10:43.195  4444  4444 I libpersona: KNOX_SDCARD checking this for 1000
03-17 07:10:43.195  4444  4444 E Zygote  : v2
03-17 07:10:43.195  4444  4444 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:43.195  4444  4444 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 07:10:43.195  1022  1597 I ActivityManager: Start proc com.sec.android.app.bluetoothtest for broadcast com.sec.android.app.bluetoothtest/.BluetoothBDAdrressReceiver: pid=4444 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,03-17 07:10:43.195  4444  4444 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 07:10:43.195  4444  4444 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 07:10:43.195  1022  1667 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:43.195  1022  1667 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-17 07:10:43.195  1022  1667 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.bcservice, destAppInfo.processName = com.sec.phone
,03-17 07:10:43.215  1022  1046 W libprocessgroup: failed to open /acct/uid_10146/pid_3709/cgroup.procs: No such file or directory
,03-17 07:10:43.215  1022  1597 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:43.215  1022  1597 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 07:10:43.215  1022  1597 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:43.225  2141  2141 D SystemUpdateService: onCreate
,03-17 07:10:43.225  4444  4444 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 07:10:43.225  4444  4444 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:43.225  3120  3120 D FactoryTestApp: [DummyFtClient$onDestroy](3120) Destroy DummyFtClient service
,03-17 07:10:43.235  3120  3120 D FactoryTestApp: [Support$Values.getString](3120) id=MODEL_COMMUNICATION_MODE, value=gsm
03-17 07:10:43.235  3120  3120 I FactoryTestApp: [ModuleCommon$isConnectionModeNone](3120) mConnectionMode = gsm
03-17 07:10:43.235  3120  3120 I FactoryTestApp: [ModuleCommon$isRunningFtClient](3120) RUNNING_FTCLIENT : false
03-17 07:10:43.235  3120  3120 D FactoryTestApp: [DummyFtClient$onDestroy](3120) kill process
03-17 07:10:43.235  3120  3120 I Process : Sending signal. PID: 3120 SIG: 9
,03-17 07:10:43.235  4411  4411 D F_PHONE : [[com.sec.bcservice]] onServiceConnected()
,03-17 07:10:43.245  4411  4411 I F_PHONE : default registerAction()
03-17 07:10:43.245  4411  4411 I F_PHONE : [[com.sec.bcservice]] sendPendingMessage()
,03-17 07:10:43.255  4444  4444 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,03-17 07:10:43.285  4444  4444 D BluetoothBDAdrressReceiver: onReceive(), action: android.intent.action.BOOT_COMPLETED
,03-17 07:10:43.285  4444  4444 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.app.bluetoothtest.BluetoothBDAdrressReceiver.onReceive:32 android.app.ActivityThread.handleReceiver:3125 
,03-17 07:10:43.285  1022  1667 I ActivityManager: Process com.sec.factory (pid 3120)(adj 0) has died(60,652)
,03-17 07:10:43.295  1022  1321 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:43.295  1022  1321 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:43.295  1022  1321 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.bluetoothtest, destAppInfo.processName = com.sec.android.app.bluetoothtest
,03-17 07:10:43.295  4428  4428 E KnoxSetupWizardClient: isShipMode : 1
03-17 07:10:43.295  4428  4428 I KnoxSetupWizardClient: onReceive : android.intent.action.BOOT_COMPLETED
,03-17 07:10:43.295  1022  1035 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:43.295  1022  1035 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:43.295  1022  1035 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:43.295  1022  1035 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:43.305  1485  1485 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,03-17 07:10:43.315  4470  4470 E Zygote  : MountEmulatedStorage()
03-17 07:10:43.315  4470  4470 E Zygote  : v2
03-17 07:10:43.315  4470  4470 I libpersona: KNOX_SDCARD checking this for 1000
03-17 07:10:43.315  4470  4470 I libpersona: KNOX_SDCARD not a persona
03-17 07:10:43.315  4470  4470 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 07:10:43.315  4470  4470 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 07:10:43.315  4470  4470 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 07:10:43.315  1485  1485 D BluetoothBDTestService: onCreate()
03-17 07:10:43.315  1485  1485 E BluetoothBDTestService: onStart(), extra_type: BOOT_COMPLETED
03-17 07:10:43.315  1485  1485 E BluetoothBDTestService: bd_address_path: /efs/bluetooth/bt_addr
,03-17 07:10:43.325  1485  1485 E BluetoothBDTestService: already exist!( /efs/bluetooth/bt_addr ), file length: 17
03-17 07:10:43.325  1022  1035 I ActivityManager: Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.receiver.ServiceStartReceiver: pid=4470 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,03-17 07:10:43.345  4470  4470 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:43.345  4470  4470 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:43.365  2141  2141 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,03-17 07:10:43.375  4470  4470 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-17 07:10:43.385  2141  4427 I CheckinService: Checking schedule, now: 1458195043384 next: 1458299986961
03-17 07:10:43.385  2141  4427 I CheckinService: active receiver: disabled
,03-17 07:10:43.395  4428  4428 D ShortcutReceiver:  ShortcutReceiver onReceive() intent: android.intent.action.BOOT_COMPLETED
,03-17 07:10:43.405  2141  4487 V AuthZen : Handling intent: android.intent.action.BOOT_COMPLETED
,03-17 07:10:43.415  4350  4350 D VlingoApplication: sac sec ensureCacheEmpty() car_iux_tts_cacheing_required set to false
,03-17 07:10:43.415  4350  4350 D VlingoApplication: sac sec ensureCacheEmpty() purged 0 historically cached TTS files
,03-17 07:10:43.425  2141  2141 D ChimeraCfgMgr: Reading stored module config
,03-17 07:10:43.425  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.SBrowserMainActivity
03-17 07:10:43.425  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.425  4388  4417 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
03-17 07:10:43.425  4388  4417 I AMMetaDataParserService: getResourcePackageName:assistantlist
03-17 07:10:43.425  4388  4417 I AMMetaDataParserService: Resource data:2131165186
,03-17 07:10:43.425  4388  4417 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
03-17 07:10:43.425  4388  4417 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-17 07:10:43.425  4388  4417 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
03-17 07:10:43.425  4388  4417 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,03-17 07:10:43.425  4388  4417 I AMMetaDataParserService: getResourceName:com.sec.android.app.sbrowser:xml/assistantlist
,03-17 07:10:43.425  4388  4417 I AMMetaDataParserService: getResourceTypeNamexml
,03-17 07:10:43.435  2141  4486 I SystemUpdateService: cancelUpdate (empty URL)
,03-17 07:10:43.435  2141  4486 I SystemUpdateService: active receiver: disabled
,03-17 07:10:43.435  1022  1667 D PersonaManagerService: getPersonasForUser(): returning null!
,03-17 07:10:43.435  4470  4470 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.intent.action.BOOT_COMPLETED myUserId=0
,03-17 07:10:43.445  1022  1520 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:43.445  1022  1520 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 07:10:43.445  1022  1520 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:43.445  4470  4491 I KnoxUsageLogPro: savePreference: key = previous_sys_time value = 1458195043451
,03-17 07:10:43.445  4428  4428 D KnoxShortcutUtil: getIsShortcutMigrationFor_2_3_0_Done true
,03-17 07:10:43.445  4428  4428 D ShortcutReceiver:  KnoxContainerVersion 2.3.0
03-17 07:10:43.445  4428  4428 D ShortcutReceiver:  shortcut migration not required 
,03-17 07:10:43.445  1880  1880 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
03-17 07:10:43.445  4470  4470 I KnoxUsageLogPro: premStatus:2
,03-17 07:10:43.445  4470  4470 I KnoxUsageLogPro: isEulaShown : false
03-17 07:10:43.445  4470  4470 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,03-17 07:10:43.455  1022  1520 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:43.455  1022  1520 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:43.455  1022  1520 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:43.455  1022  1520 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:43.455  1880  1880 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 07:10:43.465  4493  4493 E Zygote  : MountEmulatedStorage()
,03-17 07:10:43.465  4493  4493 E Zygote  : v2
03-17 07:10:43.465  4493  4493 I libpersona: KNOX_SDCARD checking this for 1000
03-17 07:10:43.465  4493  4493 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:43.465  4493  4493 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 07:10:43.465  1022  1520 I ActivityManager: Start proc com.sec.android.app.mt for broadcast com.sec.android.app.mt/.StatusChecker: pid=4493 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,03-17 07:10:43.465  1022  1520 I ActivityManager: Killing 3607:com.sec.android.provider.badge/u0a68 (adj 15): empty #31
03-17 07:10:43.465  4493  4493 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 07:10:43.475  4493  4493 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
03-17 07:10:43.475  1022  1520 I ActivityManager: Killing 3663:com.sec.dsm.system/1000 (adj 15): empty #31
03-17 07:10:43.475  2141  2141 D BootCompletedReceiver: Will schedule periodic tasks:android.intent.action.BOOT_COMPLETED.
03-17 07:10:43.475  2141  2141 D BootCompletedReceiver: Got an BootCompleted event.
,03-17 07:10:43.485  2141  2141 D BootCompletedReceiver: Will NOT schedule AdAttestation signal task because it's disabled.
,03-17 07:10:43.485  4428  4466 W System.err: java.lang.IllegalArgumentException: Unknown package: com.sec.knox.setupwizardstub
,03-17 07:10:43.485  4350  4350 D DialogFlow: initQueue()
,03-17 07:10:43.495  1022  1404 I ActivityManager: Killing 3746:com.sec.android.app.factorykeystring/1000 (adj 15): empty #31
,03-17 07:10:43.495  4428  4466 W System.err: 	at android.os.Parcel.readException(Parcel.java:1544)
03-17 07:10:43.495  4428  4466 W System.err: 	at android.os.Parcel.readException(Parcel.java:1493)
03-17 07:10:43.495  4428  4466 W System.err: 	at android.content.pm.IPackageManager$Stub$Proxy.setApplicationEnabledSetting(IPackageManager.java:4163)
03-17 07:10:43.495  4428  4466 W System.err: 	at android.app.ApplicationPackageManager.setApplicationEnabledSetting(ApplicationPackageManager.java:1925)
03-17 07:10:43.495  4428  4466 W System.err: 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.processInternal(StubPackageThread.java:88)
03-17 07:10:43.495  4428  4466 W System.err: 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.run(StubPackageThread.java:49)
,03-17 07:10:43.495  4493  4493 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:43.495  4493  4493 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:43.515  4388  4417 I AMMetaDataParserService: Icon data: ResourceEnter URL2131755287android.intent.action.doInputURL2130837509
,03-17 07:10:43.535  1022  1404 I ActivityManager: Killing 3733:com.dropbox.android:crash_uploader/u0a88 (adj 15): empty #31
,03-17 07:10:43.545  1022  1520 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:43.545  1022  1520 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:43.545  1022  1520 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:43.545  1022  1520 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:43.545  4493  4493 D StatusChecker: onReceive : android.intent.action.BOOT_COMPLETED
,03-17 07:10:43.545  4470  4491 I KnoxUsageLogPro: savePreference: key = previous_elapsed_time value = 45570
,03-17 07:10:43.555  4510  4510 E Zygote  : MountEmulatedStorage(),
03-17 07:10:43.555  4510  4510 I libpersona: KNOX_SDCARD checking this for 10030
03-17 07:10:43.555  4510  4510 E Zygote  : v2,
03-17 07:10:43.555  4510  4510 I libpersona: KNOX_SDCARD not a persona
03-17 07:10:43.555  4510  4510 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 07:10:43.565  4510  4510 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 07:10:43.565  4388  4417 I AMMetaDataParserService: Icon data: ResourceTabs2131755155android.intent.action.doWindowManager2130837511
03-17 07:10:43.565  1022  1520 I ActivityManager: Start proc com.sec.android.app.sns3 for broadcast com.sec.android.app.sns3/.SnsBroadcastReceiver: pid=4510 uid=10030 gids={50030, 9997, 1028, 1015, 3003} abi=armeabi-v7a
03-17 07:10:43.565  4510  4510 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,03-17 07:10:43.565  4493  4493 I StatusChecker: onReceive : net.mt.init : DONE
,03-17 07:10:43.575  1022  1129 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:43.575  1022  1129 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:43.575  1022  1129 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:43.575  1022  1129 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:43.595  4388  4417 I AMMetaDataParserService: Icon data: ResourceNew Tab2131755457android.intent.action.doNewWindow2130837510
03-17 07:10:43.595  4524  4524 E Zygote  : MountEmulatedStorage()
03-17 07:10:43.595  4524  4524 I libpersona: KNOX_SDCARD checking this for 10113
03-17 07:10:43.595  4524  4524 E Zygote  : v2
03-17 07:10:43.595  4524  4524 I libpersona: KNOX_SDCARD not a persona
03-17 07:10:43.595  4524  4524 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,03-17 07:10:43.595  2141  4487 D AuthZenEventHandler: Handling event: android.intent.action.BOOT_COMPLETED,
03-17 07:10:43.595  1022  1129 I ActivityManager: Start proc com.sec.android.pagebuddynotisvc for broadcast com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvcBRcvr: pid=4524 uid=10113 gids={50113, 9997} abi=armeabi-v7a
03-17 07:10:43.595  4510  4510 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 07:10:43.605  4510  4510 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:43.605  4524  4524 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 07:10:43.605  4524  4524 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 07:10:43.615  1022  1667 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:43.615  1022  1667 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 07:10:43.615  1022  1667 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:43.615  2141  2141 D SystemUpdateService: onDestroy
,03-17 07:10:43.615  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappManager
03-17 07:10:43.615  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity
03-17 07:10:43.615  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity0
03-17 07:10:43.615  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity1
03-17 07:10:43.615  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity2
03-17 07:10:43.615  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity3
03-17 07:10:43.615  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity4
03-17 07:10:43.615  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity5
03-17 07:10:43.615  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity6
03-17 07:10:43.615  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity7
03-17 07:10:43.615  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity8
03-17 07:10:43.615  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity9
03-17 07:10:43.615  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.history.ui.HistoryActivity
03-17 07:10:43.615  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.Settings
03-17 07:10:43.615  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.reader.ui.ReaderActivity
03-17 07:10:43.615  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.menuactivity.ui.AddWebPageMenuActivity
03-17 07:10:43.615  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.readinglist.activity.ReadingListActivity
03-17 07:10:43.615  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.readinglist.controller.ReadingListSearchActivity
03-17 07:10:43.615  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.sites.SitesActivity
03-17 07:10:43.615  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.common.DataChargingDialog
03-17 07:10:43.615  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.EditBookmarkFolderActivity
03-17 07:10:43.615  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.AddBookmarkActivity
03-17 07:10:43.615  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.ShowBookmarksActivity
03-17 07:10:43.615  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.SelectBookmarkFolderActivity
03-17 07:10:43.615  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.CreateBookmarkFolderActivity
03-17 07:10:43.615  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.SynctabActivity
03-17 07:10:43.615  4388  4417 I AMMetaDataP,arserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.SelectSyncAccountActivity
03-17 07:10:43.615  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.AutofillFormEdit
03-17 07:10:43.615  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.DeleteSyncTabActivity
03-17 07:10:43.615  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountGetStartedActivity
03-17 07:10:43.615  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountCreateAccountActivity
03-17 07:10:43.615  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountConfirmAccountActivity
03-17 07:10:43.615  4388  4417 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
03-17 07:10:43.615  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountSignInActivity
03-17 07:10:43.615  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountVerifiedAccountActivity
03-17 07:10:43.615  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountCreateAccountNotAllowedActivity
03-17 07:10:43.645  1022  1046 W libprocessgroup: failed to open /acct/uid_1000/pid_3663/cgroup.procs: No such file or directory
03-17 07:10:43.645  1022  1046 W libprocessgroup: failed to open /acct/uid_10088/pid_3733/cgroup.procs: No such file or directory
03-17 07:10:43.645  1022  1046 W libprocessgroup: failed to open /acct/uid_10068/pid_3607/cgroup.procs: No such file or directory
03-17 07:10:43.645  1022  1046 W libprocessgroup: failed to open /acct/uid_1000/pid_3746/cgroup.procs: No such file or directory
03-17 07:10:43.655  1022  1404 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:43.655  1022  1404 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-17 07:10:43.655  1022  1404 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:43.655  4524  4524 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:43.655  4524  4524 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:43.665  1880  4408 I GCoreUlr: WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,03-17 07:10:43.665  1022  1392 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:43.665  1022  1392 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 07:10:43.665  1022  1392 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:43.685  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.PeopleActivity
,03-17 07:10:43.685  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.685  4388  4417 I AMMetaDataParserService: getResourcePackageName:assistant
03-17 07:10:43.685  4388  4417 I AMMetaDataParserService: Resource data:2131034113
,03-17 07:10:43.705  1022  1507 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-17 07:10:43.705  1022  1507 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4310, temperature: 248, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-17 07:10:43.705  1022  1507 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-17 07:10:43.705  1022  1022 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-17 07:10:43.715  4388  4417 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,03-17 07:10:43.715  1022  1022 I MotionRecognitionService: Plugged
,03-17 07:10:43.715  1022  1022 I MotionRecognitionService: mGripSensorEnabled= false
03-17 07:10:43.715  4388  4417 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-17 07:10:43.715  4388  4417 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,03-17 07:10:43.715  1206  1206 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-17 07:10:43.715  1206  1206 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-17 07:10:43.715  1445  1445 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,03-17 07:10:43.715  1445  1445 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-17 07:10:43.715  1206  1206 D PowerUI : Cable  true --> true mBootCompleted : true
03-17 07:10:43.715  1206  1206 D PowerUI : Sending cableIntent : Intent { act=com.samsung.systemui.power.action.ACTION_CABLE_CONNECTED }
,03-17 07:10:43.725  3165  3165 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-17 07:10:43.725  3165  3300 D HeadsetStateMachine: Disconnected process message: 10
,03-17 07:10:43.725  2141  4487 W BaseAppContext: Using Auth Proxy for data requests.
,03-17 07:10:43.725  1880  4408 I GCoreUlr: Unbound from all location providers
03-17 07:10:43.725  1880  4408 I GCoreUlr: Place inference reporting - stopped
,03-17 07:10:43.735  1206  1206 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-17 07:10:43.735  1206  1206 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-17 07:10:43.735  1206  1206 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-17 07:10:43.735  1206  1206 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-17 07:10:43.735  1206  1206 D SViewCoverView: level :100 plugged : 2
,03-17 07:10:43.745  1880  1880 I GCoreUlr: DispatchingService.onDestroy()
03-17 07:10:43.745  1880  1880 I GCoreUlr: Stopping handler for UlrDispSvcFast
,03-17 07:10:43.755  1880  1880 I GCoreUlr: Unbound from all location providers
,03-17 07:10:43.755  1880  1880 I GCoreUlr: Place inference reporting - stopped
,03-17 07:10:43.785  1022  1129 I ActivityManager: Killing 3774:com.sec.android.diagmonagent/1000 (adj 15): empty #31
,03-17 07:10:43.795  4524  4524 I PageBuddyNotiSvc: Intent received : action=android.intent.action.BOOT_COMPLETED
,03-17 07:10:43.795  4388  4417 I AMMetaDataParserService: getResourceName:com.android.contacts:xml/assistant_main
03-17 07:10:43.795  4388  4417 I AMMetaDataParserService: getResourceTypeNamexml
,03-17 07:10:43.795  4388  4417 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 07:10:43.805  4388  4417 I GFX construct_block_size_descriptor_2d second part: took 2.836875ms for 0*0 texture 0
,03-17 07:10:43.805  4524  4524 W ContextImpl: Implicit intents with startService are not safe: Intent { act=com.sec.android.pagebuddynotisvc } android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.pagebuddynotisvc.PageBuddyNotiSvcBRcvr.onReceive:-1 
,03-17 07:10:43.815  1022  1404 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:43.815  1022  1404 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:43.815  1022  1404 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.pagebuddynotisvc, destAppInfo.processName = com.sec.android.pagebuddynotisvc
,03-17 07:10:43.815  4388  4417 I GFX generate_partition_tables: took 6.482704ms for 0*0 texture 0
,03-17 07:10:43.815  4524  4524 I PageBuddyNotiSvc: onCreate mCpBitFlag=0
,03-17 07:10:43.815  4388  4417 I GFX raster: took 10.852027ms for 96*96 texture 0
,03-17 07:10:43.815  4388  4417 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb756a268 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7566b70 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 07:10:43.815  1022  1129 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:43.815  1022  1129 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:43.815  1022  1129 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:43.815  1022  1129 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:43.825  4388  4417 I AMMetaDataParserService: Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
,03-17 07:10:43.835  4547  4547 E Zygote  : MountEmulatedStorage()
,03-17 07:10:43.835  4547  4547 E Zygote  : v2
03-17 07:10:43.835  4388  4417 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
03-17 07:10:43.835  4547  4547 I libpersona: KNOX_SDCARD checking this for 10121
03-17 07:10:43.835  4547  4547 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:43.835  4388  4417 I GFX raster: took 1.170989ms for 96*96 texture 0
,03-17 07:10:43.835  4388  4417 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb756a268 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7566b70 counterpartCT=4 counterpartW=96 counterparth=96
03-17 07:10:43.835  4547  4547 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 07:10:43.835  4547  4547 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 07:10:43.835  1022  1129 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=4547 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
03-17 07:10:43.835  4547  4547 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 07:10:43.855  4388  4417 I AMMetaDataParserService: Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,03-17 07:10:43.855  2141  4487 E BaseAppContext: Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,03-17 07:10:43.865  4547  4547 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:43.865  4547  4547 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:43.865  1022  1046 W libprocessgroup: failed to open /acct/uid_1000/pid_3774/cgroup.procs: No such file or directory
,03-17 07:10:43.875  1880  2157 W GCoreFlp: No location to return for getLastLocation()
,03-17 07:10:43.875  1880  1889 W FusedLocationProvider: location=null
,03-17 07:10:43.885  2141  4487 I AuthZen : Fetching signing key...
,03-17 07:10:43.885  4547  4547 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-17 07:10:43.885  4547  4547 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,03-17 07:10:43.885  4547  4547 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,03-17 07:10:43.895  1880  2157 W GCoreFlp: No location to return for getLastLocation()
,03-17 07:10:43.895  1880  2293 W FusedLocationProvider: location=null
,03-17 07:10:43.915  2141  4487 I AuthZen : Signing key fetched successfully!
,03-17 07:10:43.915  4388  4417 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 07:10:43.925  4388  4417 I GFX construct_block_size_descriptor_2d second part: took 2.388855ms for 0*0 texture 0
,03-17 07:10:43.925  4388  4417 I GFX generate_partition_tables: took 7.318594ms for 0*0 texture 0
,03-17 07:10:43.925  4388  4417 I GFX raster: took 10.695208ms for 96*96 texture 0
03-17 07:10:43.925  4388  4417 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb756a0f0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb756fff0 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 07:10:43.935  2141  4487 W BaseAppContext: Using Auth Proxy for data requests.
,03-17 07:10:43.935  4510  4510 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
03-17 07:10:43.935  4510  4510 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 07:10:43.935  4510  4510 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,03-17 07:10:43.935  1206  1206 D StatusBar.NetworkController: refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-17 07:10:43.935  1206  1206 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-17 07:10:43.935  1206  1206 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 07:10:43.935  1206  1206 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 07:10:43.935  1206  1206 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 07:10:43.935  1206  1206 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 07:10:43.945  4547  4547 D QuickConnect: PeriphStartReceiver.onReceive - android.intent.action.BOOT_COMPLETED
,03-17 07:10:43.945  4388  4417 I AMMetaDataParserService: Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,03-17 07:10:43.955  1022  1034 D SettingsProvider: name = scon_is_running
03-17 07:10:43.955  1022  1034 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-17 07:10:43.955  1022  1034 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-17 07:10:43.955  1022  1034 D SettingsProvider: selectionArgs: false
03-17 07:10:43.955  1022  1034 D SettingsProvider: selectionArgs: 10121
03-17 07:10:43.955  1022  1034 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-17 07:10:43.955  1022  1034 D SettingsProvider: ret = -1
,03-17 07:10:43.965  1022  1034 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10121
,03-17 07:10:43.965  4510  4510 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,03-17 07:10:43.965  4547  4547 D QuickConnect: Utils.setQCRunningSetting - set : 0
03-17 07:10:43.965  4510  4510 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-17 07:10:43.965  4510  4510 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.,
,03-17 07:10:43.975  4547  4547 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care ACTION_BOOT_COMPLETED. run P service
,03-17 07:10:43.975  4547  4547 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,03-17 07:10:43.985  1022  1404 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:43.985  1022  1404 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:43.985  1022  1404 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:43.985  1022  1404 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:43.985  1206  1206 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 07:10:43.995  2141  4487 D a       : Opening database auth.proximity.permit_store...,
,03-17 07:10:43.995  4569  4569 E Zygote  : MountEmulatedStorage()
03-17 07:10:43.995  4569  4569 I libpersona: KNOX_SDCARD checking this for 10127
03-17 07:10:43.995  4569  4569 E Zygote  : v2
03-17 07:10:43.995  4569  4569 I libpersona: KNOX_SDCARD not a persona
03-17 07:10:43.995  4569  4569 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 07:10:43.995  4569  4569 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
03-17 07:10:43.995  1022  1062 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
03-17 07:10:43.995  1022  1404 I ActivityManager: Start proc com.sec.android.app.sbrowser for broadcast com.sec.android.app.sbrowser/.net.NetworkSettingsReceiver: pid=4569 uid=10127 gids={50127, 9997, 1023, 3003, 1028, 1015, 1007, 3001, 3002} abi=armeabi-v7a
,03-17 07:10:44.005  4569  4569 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 07:10:44.005  2141  4487 D AuthZenTransactionCache: Initialized cache in: /data/data/com.google.android.gms/files
03-17 07:10:44.005  2141  4487 D AuthZenTransactionCache: Clearing transaction cache
,03-17 07:10:44.005  4388  4417 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 07:10:44.005  4388  4417 I GFX raster: took 0.764011ms for 96*96 texture 0
03-17 07:10:44.005  4388  4417 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7584738 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb758d218 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 07:10:44.015  4388  4417 I AMMetaDataParserService: Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,03-17 07:10:44.025  4569  4569 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:44.025  4569  4569 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:44.025  1022  1902 I ActivityManager: Killing 3081:com.sec.esdk.elm/u0a90 (adj 15): empty #31
,03-17 07:10:44.035  4388  4417 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 07:10:44.035  4388  4417 I GFX raster: took 1.169010ms for 96*96 texture 0
03-17 07:10:44.035  4388  4417 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb758c740 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7566b70 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 07:10:44.035  4510  4510 W ResourcesManager: Asset path '/system/framework/libvtmanagerjar.jar' does not exist or contains no resources.
03-17 07:10:44.035  4510  4510 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,03-17 07:10:44.035  4388  4417 I AMMetaDataParserService: Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,03-17 07:10:44.045  2141  4254 I Icing   : updateResources: need to parse f{com.google.android.gms}
,03-17 07:10:44.055  1022  1667 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:44.055  1022  1667 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 07:10:44.055  1022  1667 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:44.055   288   288 E SMD     : DCD OFF
,03-17 07:10:44.065  4388  4417 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 07:10:44.065  4388  4417 I GFX raster: took 0.630833ms for 96*96 texture 0
03-17 07:10:44.065  4388  4417 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb758d218 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb756fff0 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 07:10:44.065  4569  4569 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,03-17 07:10:44.075  4569  4569 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 07:10:44.075  4569  4569 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
03-17 07:10:44.075  4569  4569 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,03-17 07:10:44.085  4388  4417 I AMMetaDataParserService: Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,03-17 07:10:44.095  1880  1880 W Auth    : [FRP,FrpUpdateIntentService] Received invalid intent action: com.google.android.gms.auth.ACTION_INVALID
,03-17 07:10:44.105  1022  1404 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:44.105  1022  1404 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 07:10:44.105  1022  1404 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:44.115  4388  4417 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 07:10:44.115  4388  4417 I GFX raster: took 0.867239ms for 96*96 texture 0
03-17 07:10:44.115  4388  4417 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7566b70 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb756fff0 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 07:10:44.115  1022  1129 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:44.115  1022  1129 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 07:10:44.115  1022  1129 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:44.125  4388  4417 I AMMetaDataParserService: Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
,03-17 07:10:44.125  3693  3744 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 4 sec
,03-17 07:10:44.135  1880  1880 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 07:10:44.165  1880  1880 D PersistentNotificationBroadcastReceiver: Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
,03-17 07:10:44.275  4569  4569 D SBrowserFeatureFlag: initialized in static block : loadCscFeatureValue() succeed! 
,03-17 07:10:44.305  4569  4569 D ManifestProvider: onCreate()
,03-17 07:10:44.325  1022  1046 W libprocessgroup: failed to open /acct/uid_10090/pid_3081/cgroup.procs: No such file or directory
,03-17 07:10:44.325  4569  4569 E NetworkSettingsReceiver: onReceive: android.intent.action.BOOT_COMPLETED
,03-17 07:10:44.365  4569  4569 W System.err: java.lang.NoSuchMethodException: isEnabled []
,03-17 07:10:44.365  1022  1034 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:44.365  1022  1034 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 07:10:44.365  1022  1034 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:44.385  1022  1047 I ActivityManager: Waited long enough for: ServiceRecord{c6d09c5 u0 com.samsung.android.app.galaxyfinder/.tag.LocationTagReadyService}
,03-17 07:10:44.385  4569  4569 W System.err: 	at java.lang.Class.getMethod(Class.java:665)
,03-17 07:10:44.385  4569  4569 W System.err: 	at com.sec.android.app.sbrowser.common.SBrowserFeatureFlag.isCLipboardExsupported(SBrowserFeatureFlag.java:1217)
03-17 07:10:44.385  4569  4569 W System.err: 	at com.sec.android.app.sbrowser.common.SBrowserFeatureFlag.initSupportedPkg(SBrowserFeatureFlag.java:1197)
,03-17 07:10:44.385  4569  4569 W System.err: 	at com.sec.android.app.sbrowser.common.SBrowserFeatureFlag.initialize(SBrowserFeatureFlag.java:1114)
03-17 07:10:44.385  4569  4569 W System.err: 	at com.sec.android.app.sbrowser.preferences.SbrowserSettings.<init>(SbrowserSettings.java:221)
,03-17 07:10:44.385  4569  4569 W System.err: 	at com.sec.android.app.sbrowser.common.SBrowserMobileApplication.getSetting(SBrowserMobileApplication.java:111)
03-17 07:10:44.385  4569  4569 W System.err: 	at com.sec.android.app.sbrowser.net.NetworkSettingsReceiver.onReceive(NetworkSettingsReceiver.java:48)
03-17 07:10:44.385  4569  4569 W System.err: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
,03-17 07:10:44.385  4569  4569 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
03-17 07:10:44.385  4569  4569 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
03-17 07:10:44.385  4569  4569 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 07:10:44.385  4569  4569 W System.err: 	at android.os.Looper.loop(Looper.java:145)
03-17 07:10:44.385  4569  4569 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
03-17 07:10:44.385  4569  4569 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
03-17 07:10:44.385  4569  4569 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-17 07:10:44.385  4569  4569 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
03-17 07:10:44.385  4569  4569 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
03-17 07:10:44.385  1022  1129 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:44.385  1022  1129 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-17 07:10:44.385  1022  1129 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:44.385  4350  4469 I System.out: INFO:Resource not found:/Common.properties Using default values
,03-17 07:10:44.385  4569  4569 E SBrowserFeatureFlag: initSupportedPkg: checkExistService com.samsung.android.smartclip.SpenGestureManager@26ecf32a
,03-17 07:10:44.395  4569  4569 D SBrowserFeatureFlag: initialize : initSupportedPkg() succeed! 
03-17 07:10:44.395  4569  4569 I VerificationLog: SbrowserSettings- url content://com.sec.android.app.sbrowser/readinglist/pinned.mhtml
,03-17 07:10:44.395  4388  4417 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 07:10:44.395  4388  4417 I GFX raster: took 0.821823ms for 96*96 texture 0
03-17 07:10:44.395  4388  4417 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb756fff0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7300d50 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 07:10:44.405  1022  1035 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:44.405  1022  1035 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:44.405  1022  1035 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:44.405  1022  1035 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:44.405  4388  4417 I AMMetaDataParserService: Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,03-17 07:10:44.415  4598  4598 E Zygote  : MountEmulatedStorage()
03-17 07:10:44.415  4598  4598 E Zygote  : v2
03-17 07:10:44.415  4598  4598 I libpersona: KNOX_SDCARD checking this for 10131
03-17 07:10:44.415  4598  4598 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:44.415  4598  4598 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,03-17 07:10:44.415  4598  4598 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,03-17 07:10:44.415  4598  4598 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 07:10:44.415  1022  1035 I ActivityManager: Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=4598 uid=10131 gids={50131, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,03-17 07:10:44.425  1022  1035 I ActivityManager: Killing 3820:com.policydm/1000 (adj 15): empty #31
,03-17 07:10:44.425  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.dialer.DialtactsActivity
03-17 07:10:44.425  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:44.425  4388  4417 I AMMetaDataParserService: getResourcePackageName:assistant
03-17 07:10:44.425  4388  4417 I AMMetaDataParserService: Resource data:2131034113
,03-17 07:10:44.425  4388  4417 I AMMetaDataParserService: getResourceName:com.android.contacts:xml/assistant_main
03-17 07:10:44.425  4388  4417 I AMMetaDataParserService: getResourceTypeNamexml
03-17 07:10:44.425  4388  4417 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 07:10:44.425  4388  4417 I GFX raster: took 0.850208ms for 96*96 texture 0
03-17 07:10:44.425  4388  4417 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb756a268 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7300d50 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 07:10:44.435  4388  4417 I AMMetaDataParserService: Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
,03-17 07:10:44.445  4598  4598 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:44.445  4598  4598 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:44.465  4598  4598 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,03-17 07:10:44.465  4598  4598 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-17 07:10:44.465  4598  4598 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-17 07:10:44.465  4388  4417 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 07:10:44.465  4388  4417 I GFX raster: took 0.850679ms for 96*96 texture 0
,03-17 07:10:44.465  4388  4417 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb756a268 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7300d50 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 07:10:44.475  4350  4363 W art     : Suspending all threads took: 5.126ms
,03-17 07:10:44.475  4388  4417 I AMMetaDataParserService: Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,03-17 07:10:44.485  2141  2155 W art     : Suspending all threads took: 9.865ms
,03-17 07:10:44.565  4388  4417 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 07:10:44.565  4388  4417 I GFX raster: took 0.626094ms for 96*96 texture 0
,03-17 07:10:44.565  4388  4417 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb756a0f0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7300d50 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 07:10:44.575  4388  4417 I AMMetaDataParserService: Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,03-17 07:10:44.585  1788  3817 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,03-17 07:10:44.595  1022  1034 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:44.595  1022  1034 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:44.595  1022  1034 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,03-17 07:10:44.635  4510  4510 I Process : Sending signal. PID: 4510 SIG: 9
,03-17 07:10:44.645  1022  1597 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:44.645  1022  1597 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:44.645  1022  1597 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:44.645  1022  1597 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:44.645  4388  4417 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 07:10:44.645  4388  4417 I GFX raster: took 0.669895ms for 96*96 texture 0
03-17 07:10:44.645  4388  4417 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7584738 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7300d50 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 07:10:44.655  4628  4628 E Zygote  : MountEmulatedStorage(),
03-17 07:10:44.655  4628  4628 E Zygote  : v2
,03-17 07:10:44.655  4628  4628 I libpersona: KNOX_SDCARD checking this for 10037
03-17 07:10:44.655  4628  4628 I libpersona: KNOX_SDCARD not a persona,
03-17 07:10:44.655  4388  4417 I AMMetaDataParserService: Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,03-17 07:10:44.665  4628  4628 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,03-17 07:10:44.665  4628  4628 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 07:10:44.665  1022  1597 I ActivityManager: Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=4628 uid=10037 gids={50037, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-17 07:10:44.665  4628  4628 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
03-17 07:10:44.665  1022  1507 W ActivityManager: userId = 0, bbcId = -10000,
03-17 07:10:44.665  1022  1507 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:44.665  1022  1507 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar,
03-17 07:10:44.675  1022  1035 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:44.675  1022  1035 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:44.675  1022  1035 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:44.675  1022  1035 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:44.675  4388  4417 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 07:10:44.675  4388  4417 I GFX raster: took 0.844532ms for 96*96 texture 0
03-17 07:10:44.675  4388  4417 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb758c740 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7300d50 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 07:10:44.685  4388  4417 I AMMetaDataParserService: Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,03-17 07:10:44.695  4640  4640 E Zygote  : MountEmulatedStorage()
,03-17 07:10:44.695  4640  4640 E Zygote  : v2,
03-17 07:10:44.695  4628  4628 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 07:10:44.695  4640  4640 I libpersona: KNOX_SDCARD checking this for 10135
03-17 07:10:44.695  4640  4640 I libpersona: KNOX_SDCARD not a persona
03-17 07:10:44.695  4628  4628 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:44.695  4640  4640 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 07:10:44.695  4640  4640 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
03-17 07:10:44.695  1022  1035 I ActivityManager: Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.BootCamera: pid=4640 uid=10135 gids={50135, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a
,03-17 07:10:44.695  4640  4640 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 07:10:44.705  1022  1520 I ActivityManager: Process com.sec.android.app.sns3 (pid 4510)(adj 0) has died(25,675)
,03-17 07:10:44.715  4640  4640 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 07:10:44.715  4640  4640 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:44.725  4628  4628 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
03-17 07:10:44.725   304   304 I art     : Explicit concurrent mark sweep GC freed 8728(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 605us total 23.675ms
03-17 07:10:44.725  4388  4417 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 07:10:44.725  4388  4417 I GFX raster: took 0.656042ms for 96*96 texture 0
03-17 07:10:44.725  4388  4417 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb758d218 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7300d50 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 07:10:44.725  4388  4417 I AMMetaDataParserService: Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528,
,03-17 07:10:44.735  4388  4417 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
03-17 07:10:44.735  4388  4417 I GFX raster: took 0.686354ms for 96*96 texture 0
03-17 07:10:44.735  4388  4417 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7566b70 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7557b80 counterpartCT=4 counterpartW=96 counterparth=96
03-17 07:10:44.735   304   304 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 575us total 16.495ms
,03-17 07:10:44.745  1022  1047 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:44.745  1022  1047 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:44.745  1022  1047 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:44.745  1022  1047 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:44.755   304   304 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 587us total 16.948ms
03-17 07:10:44.755  1022  1046 W libprocessgroup: failed to open /acct/uid_1000/pid_3820/cgroup.procs: No such file or directory
03-17 07:10:44.755  4388  4417 I AMMetaDataParserService: Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
,03-17 07:10:44.765  4640  4640 W ResourcesManager: Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
03-17 07:10:44.765  4640  4640 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,03-17 07:10:44.765  4640  4640 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
03-17 07:10:44.765  4640  4640 W ResourcesManager: Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
03-17 07:10:44.765  4640  4640 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,03-17 07:10:44.775  4661  4661 E Zygote  : MountEmulatedStorage()
03-17 07:10:44.775  4661  4661 E Zygote  : v2
03-17 07:10:44.775  4661  4661 I libpersona: KNOX_SDCARD checking this for 10031
03-17 07:10:44.775  4661  4661 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:44.775  4661  4661 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 07:10:44.775  4661  4661 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 07:10:44.775  4628  4628 I CalendarProvider2: CalendarProvider2.onCreate() called
03-17 07:10:44.775  4661  4661 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 07:10:44.775  1022  1047 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=4661 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a
,03-17 07:10:44.795  4661  4661 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 07:10:44.805  4661  4661 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:44.825  4388  4417 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 07:10:44.825  4388  4417 I GFX raster: took 0.550364ms for 96*96 texture 0
,03-17 07:10:44.825  4388  4417 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb756fff0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7557b80 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 07:10:44.845  4388  4417 I AMMetaDataParserService: Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,03-17 07:10:44.865  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.samsung.android.multiuser.install_only_owner
03-17 07:10:44.865  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.ContactSelectionActivity
03-17 07:10:44.865  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionTabActivity
03-17 07:10:44.865  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionGroupSelectionActivity
03-17 07:10:44.865  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.DialtactsActivity
03-17 07:10:44.865  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.RecentCallsListActivity
03-17 07:10:44.865  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.CallLogActivity
03-17 07:10:44.865  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.ContactsListActivity
03-17 07:10:44.865  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.ContactsFrontDoor
03-17 07:10:44.865  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.DialtactsContactsEntryActivity
03-17 07:10:44.865  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.PeopleActivity
03-17 07:10:44.865  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.JoinContactActivity
03-17 07:10:44.865  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.preference.ContactsPreferenceActivity
03-17 07:10:44.865  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.common.list.AccountFilterActivity
03-17 07:10:44.865  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.common.list.CustomContactListFilterActivity
03-17 07:10:44.865  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.ShowOrCreateActivity
03-17 07:10:44.865  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.GroupDetailActivity
03-17 07:10:44.865  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.GroupEditorActivity
03-17 07:10:44.865  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.quickcontact.QuickContactActivity
03-17 07:10:44.865  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:44.865  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.sec.android.multiwindow.activity.STYLE
03-17 07:10:44.865  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.ContactShortcut
03-17 07:10:44.865  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activityalias.DialShortcut
03-17 07:10:44.865  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activityalias.MessageShortcut
03-17 07:10:44.865  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.dialer.CallDetailActivity
03-17 07:10:44.865  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDetailDeleteActivity
03-17 07:10:44.865  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.ContactDetailActivity
03-17 07:10:44.865  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:44.865  4388  4417 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
03-17 07:10:44.865  4388 , 4417 I AMMetaDataParserService: getResourcePackageName:assistant
03-17 07:10:44.865  4388  4417 I AMMetaDataParserService: Resource data:2131034112
03-17 07:10:44.865  4388  4417 I AMMetaDataParserService: getResourceName:com.android.contacts:xml/assistant_detail
03-17 07:10:44.865  4388  4417 I AMMetaDataParserService: getResourceTypeNamexml
03-17 07:10:44.865  4388  4417 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
03-17 07:10:44.875  4388  4417 I GFX raster: took 0.896563ms for 96*96 texture 0
03-17 07:10:44.875  4388  4417 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7584738 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb755b718 counterpartCT=4 counterpartW=96 counterparth=96
03-17 07:10:44.875  1022  1507 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:44.875  1022  1507 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:44.875  1022  1507 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:44.875  1022  1507 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:44.885  4388  4417 I AMMetaDataParserService: Icon data: ResourceAdd to Favourites2131690170android.intent.assistant.detail.favorite2130837530
03-17 07:10:44.885  4682  4682 E Zygote  : MountEmulatedStorage()
03-17 07:10:44.885  4682  4682 E Zygote  : v2
03-17 07:10:44.885  4682  4682 I libpersona: KNOX_SDCARD checking this for 1000
03-17 07:10:44.885  4682  4682 I libpersona: KNOX_SDCARD not a persona
03-17 07:10:44.885  4682  4682 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 07:10:44.895  4682  4682 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 07:10:44.895  4682  4682 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 07:10:44.895  1022  1507 I ActivityManager: Start proc com.policydm for broadcast com.policydm/.XDMBroadcastReceiver: pid=4682 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-17 07:10:44.895  1022  1507 I ActivityManager: Killing 3843:com.sec.factory.camera/1000 (adj 15): empty #31
03-17 07:10:44.905  1022  1520 I ActivityManager: Killing 3887:com.samsung.android.provider.filterprovider/u0a95 (adj 15): empty #31
,03-17 07:10:44.925  4682  4682 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 07:10:44.925  4682  4682 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:44.945  4388  4417 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 07:10:44.945  4388  4417 I GFX raster: took 0.602135ms for 96*96 texture 0
03-17 07:10:44.945  4388  4417 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7584738 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb755b718 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 07:10:44.955  4388  4417 I AMMetaDataParserService: Icon data: ResourceRemove from Favourites2131690212android.intent.assistant.detail.favorite2130837530
,03-17 07:10:44.965  1022  1046 W libprocessgroup: failed to open /acct/uid_1000/pid_3843/cgroup.procs: No such file or directory
03-17 07:10:44.965  1022  1046 W libprocessgroup: failed to open /acct/uid_10095/pid_3887/cgroup.procs: No such file or directory
,03-17 07:10:45.025  4388  4417 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 07:10:45.025  4388  4417 I GFX raster: took 1.531822ms for 96*96 texture 0
03-17 07:10:45.025  4388  4417 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb755b718 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7581540 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 07:10:45.045  4388  4417 I AMMetaDataParserService: Icon data: ResourceEdit2131690192android.intent.assistant.detail.edit2130837529
,03-17 07:10:45.055  4388  4417 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 07:10:45.055  4388  4417 I GFX raster: took 1.659842ms for 96*96 texture 0
,03-17 07:10:45.055  4388  4417 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7585358 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7581540 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 07:10:45.065  4388  4417 I AMMetaDataParserService: Icon data: ResourceDelete2131690186android.intent.assistant.detail.delete2130837528
,03-17 07:10:45.075  1022  1034 I art     : Explicit concurrent mark sweep GC freed 35185(2008KB) AllocSpace objects, 10(160KB) LOS objects, 33% free, 24MB/36MB, paused 2.656ms total 159.914ms
,03-17 07:10:45.085  1022  1129 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:45.085  1022  1129 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 07:10:45.085  1022  1129 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
,03-17 07:10:45.085  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.detail.SelectContactInfoActivity
03-17 07:10:45.085  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.ConfirmAddDetailActivity
03-17 07:10:45.085  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorAccountsChangedActivity
03-17 07:10:45.085  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorActivity
03-17 07:10:45.085  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.RingtoneRecommendationHelperActivity
03-17 07:10:45.085  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.editor.AddAnotherFieldDialogActivity
03-17 07:10:45.085  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.AttachPhotoActivity
03-17 07:10:45.085  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.PhotoSelectionActivity
03-17 07:10:45.085  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.common.vcard.ImportVCardActivity
03-17 07:10:45.085  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportVCardPreviewActivity
03-17 07:10:45.085  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.common.vcard.NfcImportVCardActivity
03-17 07:10:45.085  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.common.vcard.CancelActivity
03-17 07:10:45.085  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.common.vcard.SelectAccountActivity
03-17 07:10:45.085  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.common.vcard.ExportVCardActivity
03-17 07:10:45.085  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportFinishActivity
03-17 07:10:45.085  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.SIMContactSelectionActivity
03-17 07:10:45.085  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbers
03-17 07:10:45.085  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbersTabActivity
03-17 07:10:45.085  1022  1404 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:45.085  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.VerizonBackupAssistantActivity
03-17 07:10:45.085  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.widget.PinnedHeaderListDemoActivity
03-17 07:10:45.085  1022  1404 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:45.085  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.NonPhoneActivity
03-17 07:10:45.085  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.favorite.FavoriteSelectionActivity
03-17 07:10:45.085  1022  1404 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
03-17 07:10:45.085  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.detail.SetDefaultActivity
03-17 07:10:45.085  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.group.GroupChangeOrderActivity
03-17 07:10:45.085  4388  4417 I AMMetaDataParserService: R,esource data:Loop for running activitycom.samsung.contacts.editor.EditGroupSelectionActivity
03-17 07:10:45.085  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.group.GroupMultiSelectionActivity
03-17 07:10:45.085  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.emergency.InteractionEmergencyMessageActivity
03-17 07:10:45.085  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.emergency.EmergencyMessageContactCreateActivity
03-17 07:10:45.085  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.emergency.EmergencyContactListDialogActivity
03-17 07:10:45.085  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.group.SubGroupDetailActivity
03-17 07:10:45.085  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.GroupListActivity
03-17 07:10:45.085  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDurationActivity
03-17 07:10:45.085  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDurationTabActivity
03-17 07:10:45.085  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.detail.LinkedContactActivity
03-17 07:10:45.085  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.impl.DialerTutorialActivity
03-17 07:10:45.085  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.impl.HelpPeopleActivity
03-17 07:10:45.085  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyPeopleActivity
03-17 07:10:45.085  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.impl.HelpInteractionTabActivity
03-17 07:10:45.085  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyInteractionTabActivity
03-17 07:10:45.085  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.impl.HelpSpeedDialActivity
03-17 07:10:45.085  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactEditorActivity
03-17 07:10:45.085  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactSelectionActivity
03-17 07:10:45.085  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.EasyPeopleActivity
03-17 07:10:45.085  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:45.085  4388  4417 I AMMetaDataParserService: getResourcePackageName:assistant
03-17 07:10:45.085  4388  4417 I AMMetaDataParserService: Resource data:2131034113
03-17 07:10:45.085  4388  4417 I AMMetaDataParserService: getResourceName:com.android.contacts:xml/assistant_main
03-17 07:10:45.085  4388  4417 I AMMetaDataParserService: getResourceTypeNamexml
03-17 07:10:45.095  4388  4417 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
03-17 07:10:45.095  4388  4417 I GFX raster: took 0.808593ms for 96*96 texture 0
03-17 07:10:45.095  4388  4417 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb72ecc78 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb758b880 counterpartCT=4 counterpartW=96 counterparth=96
03-17 07:10:45.095  3800  4008 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
03-17 07:10:45.095  1022  1035 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:45.095  1022  1035 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:45.095  1022  1035 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:45.095  1022  1035 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:45.105  4388  4417 I AMMetaDataParserService: Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
03-17 07:10:45.115  4699  4699 E Zygote  : MountEmulatedStorage()
03-17 07:10:45.115  4699  4699 E Zygote  : v2
03-17 07:10:45.115  4699  4699 I libpersona: KNOX_SDCARD checking this for 10141
03-17 07:10:45.115  4699  4699 I libpersona: KNOX_SDCARD not a persona
03-17 07:10:45.115  4699  4699 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 07:10:45.115  4388  4417 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
03-17 07:10:45.115  1022  1035 I ActivityManager: Start proc com.android.email for broadcast com.android.email/.service.EmailBroadcastReceiver: pid=4699 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
03-17 07:10:45.115  4388  4417 I GFX raster: took 0.908594ms for 96*96 texture 0
03-17 07:10:45.115  4388  4417 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb72ecc78 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb758c740 counterpartCT=4 counterpartW=96 counterparth=96
03-17 07:10:45.115  4699  4699 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 07:10:45.115  4699  4699 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 07:10:45.125  4388  4417 I AMMetaDataParserService: Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
03-17 07:10:45.125  3693  3744 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 5 sec
03-17 07:10:45.145  4699  4699 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 07:10:45.145  4699  4699 D ActivityThread: Added TimaKeyStore provider
03-17 07:10:45.155  4388  4417 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
03-17 07:10:45.165  4388  4417 I GFX raster: took 0.619011ms for 96*96 texture 0
03-17 07:10:45.165  4388  4417 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb758b880 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb758d218 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 07:10:45.165  4699  4699 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,03-17 07:10:45.165  4699  4699 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-17 07:10:45.165  4699  4699 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 07:10:45.165  4699  4699 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,03-17 07:10:45.175  4388  4417 I AMMetaDataParserService: Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,03-17 07:10:45.185  4682  4682 I DBG_POLICYDM: [com.policydm.XDMApplication(554/xdmWakeLockAcquire)] 
,03-17 07:10:45.195  4682  4682 I DBG_POLICYDM: [com.policydm.XDMApplication(559/xdmWakeLockAcquire)] m_WakeLock is acquire!!
,03-17 07:10:45.195  4682  4715 I DBG_POLICYDM: [com.policydm.agent.XDMTask(163/xdmAgentTaskHandler)] XEVENT_OS_INITIALIZED
03-17 07:10:45.195  4682  4682 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(191/xdmInitExternalStorageState)] 
,03-17 07:10:45.195  1022  1902 I ActivityManager: Killing 3936:com.samsung.android.app.watchmanagerstub/u0a98 (adj 15): empty #31
,03-17 07:10:45.195  4388  4417 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 07:10:45.205  4682  4715 I DBG_POLICYDM: [com.policydm.agent.XDMAgent(156/xdmAgentSetSyncMode)] nSync = 0
,03-17 07:10:45.205  4388  4417 I GFX raster: took 0.915623ms for 96*96 texture 0
03-17 07:10:45.205  4388  4417 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7584738 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7566b70 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 07:10:45.205  4682  4682 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(390/xdmGetExternalSDCardPath)] External SD Card Path : /storage/extSdCard
,03-17 07:10:45.205  4682  4682 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(248/xdmInitExternalStorageState)] DATA_DIR_PATH [/data]
,03-17 07:10:45.215  4682  4715 I DBG_POLICYDM: [com.policydm.db.XDB(1531/xdbDMffs_Init)] xdbDMffs_Init
,03-17 07:10:45.215  4682  4682 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(249/xdmInitExternalStorageState)] EXTERNAL_DIR_PATH [/storage/emulated/0]
,03-17 07:10:45.215  4682  4682 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(250/xdmInitExternalStorageState)] EXTERNAL_SD_DIR_PATH [/storage/extSdCard]
,03-17 07:10:45.215  4682  4682 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(251/xdmInitExternalStorageState)] POLICY_DIR_PATH [/data/data/com.policydm/cache]
,03-17 07:10:45.225  4682  4682 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(253/xdmInitExternalStorageState)] bExternalStorageAvailable [true]
,03-17 07:10:45.225  4682  4682 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(254/xdmInitExternalStorageState)] bExternalSDStorageAvailable [false]
,03-17 07:10:45.225  4682  4682 I DBG_POLICYDM: [com.policydm.XDMApplication(580/xdmWakeLockRelease)] 
03-17 07:10:45.225  4682  4682 I DBG_POLICYDM: [com.policydm.XDMApplication(585/xdmWakeLockRelease)] m_WakeLock is release!!
,03-17 07:10:45.235  4682  4682 I DBG_POLICYDM: [com.policydm.XDMApplication(179/onCreate)] DMApplication Start !
,03-17 07:10:45.245  4682  4682 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(53/onReceive)] android.intent.action.BOOT_COMPLETED
,03-17 07:10:45.245  4388  4417 I AMMetaDataParserService: Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,03-17 07:10:45.245  4682  4682 I DBG_POLICYDM: [com.policydm.db.XDB(2211/xdbIsAlreadyAgree)] bAgree : true
,03-17 07:10:45.255  4022  4032 D PCWCLIENTTRACE_AccountAppFacade2_0: unregister AuthInfo UpdateReceiver v2.0
,03-17 07:10:45.255  4388  4417 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 07:10:45.255  4388  4417 I GFX raster: took 0.839427ms for 96*96 texture 0
03-17 07:10:45.255  4388  4417 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb758c740 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb756a0f0 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 07:10:45.255  1022  1597 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:45.255  1022  1597 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:45.255  1022  1597 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:45.255  1022  1597 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:45.265  4388  4417 I AMMetaDataParserService: Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532,
,03-17 07:10:45.285  4721  4721 E Zygote  : MountEmulatedStorage(),
,03-17 07:10:45.285  4721  4721 E Zygote  : v2
03-17 07:10:45.285  4721  4721 I libpersona: KNOX_SDCARD checking this for 10032
03-17 07:10:45.285  4721  4721 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:45.285  4721  4721 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
03-17 07:10:45.285  1022  1597 I ActivityManager: Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=4721 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-17 07:10:45.295  1022  1046 W libprocessgroup: failed to open /acct/uid_10098/pid_3936/cgroup.procs: No such file or directory
,03-17 07:10:45.295  4721  4721 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 07:10:45.295  4721  4721 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,03-17 07:10:45.305  4682  4715 I DBG_POLICYDM: [com.policydm.agent.XDMTask(171/xdmAgentTaskHandler)] XEVENT_DM_INIT
,03-17 07:10:45.305  2141  4254 I Icing   : Internal init done: storage state 0
,03-17 07:10:45.305  4682  4715 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,03-17 07:10:45.305  1022  1520 I ActivityManager: Killing 3956:com.fmm.dm/1000 (adj 15): empty #31
,03-17 07:10:45.315  4682  4715 I DBG_POLICYDM: [com.policydm.XDMApplication(619/xdmGetNotibarState)] get NotibarState : 7
,03-17 07:10:45.315  4721  4721 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:45.315  4721  4721 D ActivityThread: Added TimaKeyStore provider
03-17 07:10:45.315  4682  4715 I DBG_POLICYDM: [com.policydm.ui.XUINotificationManager(48/xuiSetIndicator)] Indicator id : 7
,03-17 07:10:45.325  4388  4417 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 07:10:45.325  4682  4715 I DBG_POLICYDM: [com.policydm.XDMApplication(611/xdmSetNotibarState)] set NotibarState : 7
,03-17 07:10:45.325  4388  4417 I GFX raster: took 0.656823ms for 96*96 texture 0
03-17 07:10:45.325  4388  4417 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7585358 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb756a268 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 07:10:45.325  1022  1129 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:45.325  4388  4417 I AMMetaDataParserService: Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
03-17 07:10:45.325  1022  1129 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 07:10:45.325  1022  1129 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:45.335  4682  4715 I DBG_POLICYDM: [com.policydm.db.XDBAESCrypt(217/xdbGetCryptionkey)] try read dbString
,03-17 07:10:45.345  2141  4254 I Icing   : Post-init done
,03-17 07:10:45.355  4682  4715 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(428/xdbGetFUMOStatus)] xdbGetFUMOStatus : 0
,03-17 07:10:45.355  1022  1034 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:45.355  1022  1034 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 07:10:45.355  1022  1034 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:45.355  1022  1321 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:45.355  1022  1321 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 07:10:45.355  1022  1321 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:45.365  4682  4715 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(587/xdbGetFUMOInitiatedType)] Initiated Type: 0
,03-17 07:10:45.365  4682  4715 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(72/xpollingCheckVersionInfo)] 
,03-17 07:10:45.365  4682  4715 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(271/xpollingCheckTimer)] 
,03-17 07:10:45.365  4682  4716 I DBG_POLICYDM: [com.policydm.agent.XDMUITask(191/xdmUIEvent)] XUI_DM_IDLE_STATE :true
,03-17 07:10:45.375  4682  4715 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(285/xpollingCheckTimer)] savedpollingtime : 2016/03/20/16:34:31
,03-17 07:10:45.375  4682  4715 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(286/xpollingCheckTimer)] currentTime : 2016/03/17/07:10:45
,03-17 07:10:45.375  4682  4715 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(290/xpollingCheckTimer)] Restart Timer..
,03-17 07:10:45.375  4682  4715 I DBG_POLICYDM: [com.policydm.XDMApplication(626/xdmStartAlarm)] Alarm ID: 0
,03-17 07:10:45.375  1022  1046 W libprocessgroup: failed to open /acct/uid_1000/pid_3956/cgroup.procs: No such file or directory
,03-17 07:10:45.385  4682  4716 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,03-17 07:10:45.395  4388  4417 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 07:10:45.395  4388  4417 I GFX raster: took 0.703073ms for 96*96 texture 0
03-17 07:10:45.395  4388  4417 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb758d218 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb756fff0 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 07:10:45.395  1022  1129 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:45.405  1022  1129 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 07:10:45.405  1022  1129 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:45.405  4388  4417 I AMMetaDataParserService: Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
,03-17 07:10:45.415  4682  4716 I DBG_POLICYDM: [com.policydm.db.XDBProfileListAdp(258/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,03-17 07:10:45.415  4682  4716 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(399/xnotiPushAdpExcuteResumeNoti)] nSessionSaveState:0
,03-17 07:10:45.415  4682  4716 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(400/xnotiPushAdpExcuteResumeNoti)] nNotiUiEvent:0
,03-17 07:10:45.415  4682  4716 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(401/xnotiPushAdpExcuteResumeNoti)] nNotiRetryCount:0
,03-17 07:10:45.415  4682  4716 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(441/xnotiPushAdpExcuteResumeNoti)] Current NOTI NOT SAVED State. EXIT.
,03-17 07:10:45.415  4682  4716 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(267/xnotiPushAdpClearSessionStatus)] 
,03-17 07:10:45.415  4682  4716 I DBG_POLICYDM: [com.policydm.ui.XUIAdapter(39/xuiAdpSetUiMode)] nDmUiMode : 0
,03-17 07:10:45.425  4682  4716 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(439/xdbSetFUMOStatus)] xdbSetFUMOStatus : 0
,03-17 07:10:45.425  4721  4740 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
,03-17 07:10:45.425  4721  4740 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,03-17 07:10:45.425  4721  4721 E SPPClientService: [[SystemStateMoniter]] ACTION_BOOT_COMPLETED
,03-17 07:10:45.435  1022  1034 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:45.435  1022  1034 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 07:10:45.435  1022  1034 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:45.445  4721  4740 D SPPClientService: PushLog.txt file is not deleted.
,03-17 07:10:45.445  4721  4740 D SPPClientService: PushLog.txt file is not deleted.
,03-17 07:10:45.445  4721  4740 D SPPClientService: ============PushLog. stop!
,03-17 07:10:45.445  4682  4715 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(312/xPollingReportReStartAlarm)] 
,03-17 07:10:45.445  1022  1902 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:45.445  1022  1902 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 07:10:45.445  1022  1902 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:45.455  1022  1404 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:45.455  1022  1404 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:45.455  1022  1404 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:45.455  1022  1404 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:45.465  1022  1404 I ActivityManager: Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.broadcastreceiver.StdBroadcastReceiver: pid=4742 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-17 07:10:45.475  1022  1404 I ActivityManager: Killing 4038:com.fmm.ds/1000 (adj 15): empty #31
,03-17 07:10:45.475  4742  4742 E Zygote  : MountEmulatedStorage()
03-17 07:10:45.475  4742  4742 E Zygote  : v2
03-17 07:10:45.475  4742  4742 I libpersona: KNOX_SDCARD checking this for 10036
03-17 07:10:45.475  4742  4742 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:45.475  4742  4742 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 07:10:45.475  4742  4742 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 07:10:45.475  4682  4716 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(565/xdbSetFUMOInitiatedType)] Initiated Type: 0
,03-17 07:10:45.475  4742  4742 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,03-17 07:10:45.495  4742  4742 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:45.505  4742  4742 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:45.505  4682  4716 I DBG_POLICYDM: [com.policydm.db.XDB(1825/xdbSetBackUpServerUrl)] 
,03-17 07:10:45.515  1022  1321 D RCPManagerService: exchangeData() failure , invalid userId
,03-17 07:10:45.535  4682  4715 I DBG_POLICYDM: [com.policydm.XDMApplication(626/xdmStartAlarm)] Alarm ID: 1
,03-17 07:10:45.535  1022  1129 D RCPManagerService: exchangeData() failure , invalid userId
,03-17 07:10:45.545  4682  4715 I DBG_POLICYDM: [com.policydm.agent.XDMTask(203/xdmAgentTaskHandler)] XEVENT_DM_INIT : Initialized
,03-17 07:10:45.555  4742  4742 I SA      : [SSP] onCreated
,03-17 07:10:45.565  4742  4742 I SA      : [TPM] There is no property file
,03-17 07:10:45.565  4742  4742 I SA      : [SCU] isHaveSA() - false
,03-17 07:10:45.565  4742  4742 I SA      : [TPM] getModelProperty : null,
03-17 07:10:45.565  4742  4742 I SA      : [TPM] getCSCProperty : null
,03-17 07:10:45.565  4742  4742 I SA      : [DM] FLOATING AMOLED FEATURE: true,
03-17 07:10:45.565  4742  4742 I SA      : [DM] PRODUCT AMOLED FEATURE: false
03-17 07:10:45.565  4742  4742 I SA      : [DM] TFT FEATURE: false
,03-17 07:10:45.575  4742  4742 I SA      : [SBR] StdBroadcastReceiver received Intent of  action_BOOT_COMPLETED extra.user_handle.:0
03-17 07:10:45.575  4742  4742 I SA      : [DM] init START
,03-17 07:10:45.575  4742  4742 I SA      : [DM] This device is not a Vodafone
,03-17 07:10:45.575  4742  4742 W ResourceType: Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
,03-17 07:10:45.575  4742  4742 W ResourceType: Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
03-17 07:10:45.575  4742  4742 W ResourceType: Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
,03-17 07:10:45.575  4742  4742 W ResourceType: Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
03-17 07:10:45.575  4742  4742 W ResourceType: Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
,03-17 07:10:45.585  4742  4742 W ResourceType: Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
,03-17 07:10:45.585  4742  4742 W ResourceType: Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
,03-17 07:10:45.585  1022  1046 W libprocessgroup: failed to open /acct/uid_1000/pid_4038/cgroup.procs: No such file or directory
,03-17 07:10:45.585  4742  4742 W ResourceType: No package identifier when getting value for resource number 0x00000000
,03-17 07:10:45.585  4742  4742 W ResourceType: Failure getting entry for 0x7f060026 (t=5 e=38) (error -75)
,03-17 07:10:45.585  4742  4742 W ResourceType: Failure getting entry for 0x7f060027 (t=5 e=39) (error -75)
,03-17 07:10:45.585  4742  4742 W ResourceType: Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
,03-17 07:10:45.585  4742  4742 W ResourceType: Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
03-17 07:10:45.585  4742  4742 W ResourceType: Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
,03-17 07:10:45.585  4742  4742 W ResourceType: Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
,03-17 07:10:45.585  4742  4742 W ResourceType: Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
03-17 07:10:45.585  4742  4742 W ResourceType: Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
,03-17 07:10:45.585  4742  4742 W ResourceType: Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
,03-17 07:10:45.585  4742  4742 W ResourceType: Failure getting entry for 0x7f06001d (t=5 e=29) (error -75)
,03-17 07:10:45.585  4742  4742 W ResourceType: Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
,03-17 07:10:45.585  4742  4742 W ResourceType: Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
,03-17 07:10:45.585  4742  4742 W ResourceType: Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
03-17 07:10:45.585  4742  4742 W ResourceType: Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
,03-17 07:10:45.595  4742  4742 W ResourceType: Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
,03-17 07:10:45.595  4742  4742 W ResourceType: Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
03-17 07:10:45.595  4742  4742 W ResourceType: Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
03-17 07:10:45.595  4742  4742 W ResourceType: Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
03-17 07:10:45.595  4742  4742 I SA      : [SCU] isHaveSA() - false
03-17 07:10:45.595  4742  4742 I SA      : support phone number id : false
03-17 07:10:45.595  4742  4742 I SA      : [DM] Supports Ref Jpn : true
03-17 07:10:45.595  4742  4742 I SA      : [DM] init END
,03-17 07:10:45.595  4742  4742 I SA      : [OR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
03-17 07:10:45.595  4742  4742 I SA      : [OR] onReceive Intent=[ action_BOOT_COMPLETED extra.user_handle.:0 ]
03-17 07:10:45.595  1022  1035 D RCPManagerService: exchangeData() failure , invalid userId
03-17 07:10:45.595  1022  1129 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:45.595  1022  1129 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
03-17 07:10:45.595  1022  1129 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.osp.app.signin, destAppInfo.processName = com.osp.app.signin
,03-17 07:10:45.605  4742  4742 I SA      : [OR] onReceive END
,03-17 07:10:45.615  1022  1902 D RCPManagerService: exchangeData() failure , invalid userId
,03-17 07:10:45.615  4742  4742 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,03-17 07:10:45.615  4742  4742 I SA      : [ODM] queryOpenData(key= GEO_IP )
,03-17 07:10:45.615  4742  4742 I SA      : getMccForGalaxyJpn step2 GEO_IP MCC : 260
03-17 07:10:45.615  4742  4742 I SA      : [LBE] REF_JPN : true
,03-17 07:10:45.615  4742  4742 I SA      : [BDC] create
,03-17 07:10:45.625  4682  4716 I DBG_POLICYDM: [com.policydm.db.XDBProfileAdp(207/xdbSetChangedProtocol)] xdbSetChangedProtocol : false
,03-17 07:10:45.635  4388  4417 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 07:10:45.635  4388  4417 I GFX raster: took 0.613021ms for 96*96 texture 0
,03-17 07:10:45.635  4388  4417 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7566b70 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb756a0f0 counterpartCT=4 counterpartW=96 counterparth=96
03-17 07:10:45.635  4742  4742 I SA      : [DBMV2] getEmailID
,03-17 07:10:45.635  4742  4742 I SA      : [DBMV2] getDataV02ForItems
,03-17 07:10:45.635  4742  4742 I SA      : [SSP] query invoked
,03-17 07:10:45.635  1022  1034 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:45.635  1022  1034 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-17 07:10:45.635  4742  4742 I SA      : [SCU] get signed id from samsung account2.0 DB.
,03-17 07:10:45.635  1022  1034 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:45.645  4742  4742 I SA      : [SCU] get signed id from samsung account1.0 DB.
,03-17 07:10:45.645  4742  4742 I SA      : [BDC] destroy
,03-17 07:10:45.645  1022  1659 I ActivityManager: Killing 4084:com.samsung.android.intelligenceservice/u0a55 (adj 15): empty #31
03-17 07:10:45.645  4388  4417 I AMMetaDataParserService: Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,03-17 07:10:45.655  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.interactions.EasyInteractionTabActivity
03-17 07:10:45.655  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.calllog.LogsFindoSearchResultsActivity
03-17 07:10:45.655  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:45.655  4388  4417 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
03-17 07:10:45.655  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.dialpad.RegularSearchActivity
03-17 07:10:45.655  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.interaction.InteractionRecentActivity
03-17 07:10:45.655  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.editor.SamsungAccountValidationCheckActivity
03-17 07:10:45.655  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.autolink.AutoLinkActivity
03-17 07:10:45.655  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.EmergencyPeopleActivity
03-17 07:10:45.655  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.speeddial.SpeedDialActivity
03-17 07:10:45.655  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.businesscard.BusinesscardListActivity
03-17 07:10:45.655  4388  4417 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
03-17 07:10:45.655  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.businesscard.BusinesscardViewer
03-17 07:10:45.655  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.callmessage.CallMessageActivity
03-17 07:10:45.655  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.callmessage.RecentCallMessageActivity
03-17 07:10:45.655  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.callmessage.PhrasesEditActivity
03-17 07:10:45.655  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.callmessage.PhrasesDeleteActivity
03-17 07:10:45.655  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.callmessage.CallMessageEditActivity
03-17 07:10:45.655  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.emergency.MyEmergencyInfoDetailActivity
03-17 07:10:45.655  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.emergency.MyEmergencyInfoEditorActivity
03-17 07:10:45.655  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.ScoverFavoritesActivity
03-17 07:10:45.655  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:45.655  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.sec.android.sdk.cover.MODE
03-17 07:10:45.655  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.ScoverSelectNumberActivity
03-17 07:10:45.655  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:45.655  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.sec.android.sdk.cover.MODE
03-17 07:10:45.655  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.detail.ShowMyProfileActivity
03-17 07:10:45.,655  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionProfileWhiteListActivity
,03-17 07:10:45.665  4682  4716 I DBG_POLICYDM: [com.policydm.db.XDBProfileListAdp(258/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,03-17 07:10:45.665  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.SSLCertValidationActivity
03-17 07:10:45.665  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.EmailUpgradeKeystoreActivity
03-17 07:10:45.665  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.SecurityCertificates
03-17 07:10:45.665  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.Welcome
03-17 07:10:45.665  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.UpgradeAccounts
03-17 07:10:45.665  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupWizard
03-17 07:10:45.665  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.snc.VZWSetupWizard
03-17 07:10:45.665  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncRestoreAccounts
03-17 07:10:45.665  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.snc.SncRestoreAccounts
03-17 07:10:45.665  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncRestoreOptions
03-17 07:10:45.665  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncNames
03-17 07:10:45.665  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncExchangeAccounts
03-17 07:10:45.665  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncAccountsLogin
03-17 07:10:45.665  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.LDAPClientSettings
03-17 07:10:45.665  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.LDAPAccountsList
03-17 07:10:45.665  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupBasics
03-17 07:10:45.665  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.DataConnection
03-17 07:10:45.665  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupAccountType
03-17 07:10:45.665  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupIncoming
03-17 07:10:45.665  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupOutgoing
03-17 07:10:45.665  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupExchange
03-17 07:10:45.665  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupOptions
03-17 07:10:45.665  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupNames
03-17 07:10:45.665  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsXL
03-17 07:10:45.665  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsAddRulesforFiltering
03-17 07:10:45.665  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AddPrioritySenderActivity
03-17 07:10:45.665  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.Ac,countSecurity
03-17 07:10:45.665  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountPreSetup
03-17 07:10:45.665  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.messageview.SaveasActivity
03-17 07:10:45.665  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.Debug
03-17 07:10:45.665  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.MessageListXL
03-17 07:10:45.665  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:45.665  4388  4417 I AMMetaDataParserService: getResourcePackageName:assistant
03-17 07:10:45.665  4388  4417 I AMMetaDataParserService: Resource data:2131165203
,03-17 07:10:45.675  4388  4417 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,03-17 07:10:45.675  4388  4417 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-17 07:10:45.675  4388  4417 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 07:10:45.675  4388  4417 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,03-17 07:10:45.675  4388  4417 I AMMetaDataParserService: getResourceName:com.android.email:xml/email_assistant_menu
03-17 07:10:45.675  4388  4417 I AMMetaDataParserService: getResourceTypeNamexml
,03-17 07:10:45.675  4388  4417 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 80x80
,03-17 07:10:45.675  4388  4417 I GFX construct_block_size_descriptor_2d second part: took 3.566145ms for 0*0 texture 0
,03-17 07:10:45.685  4682  4716 I DBG_POLICYDM: [com.policydm.db.XDBNotiAdp(38/xdbNotiExistInfo)] Noti Exist : false
,03-17 07:10:45.705  4388  4417 I GFX generate_partition_tables: took 17.125782ms for 0*0 texture 0
,03-17 07:10:45.705  4388  4417 I GFX raster: took 21.297656ms for 80*80 texture 0
03-17 07:10:45.705  4388  4417 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb774b4f0 bitmapCt=12 bitmapW=80 bitmapH=80 BitmapInternalFormat=93b7, Counterpart=0xb774b628 counterpartCT=4 counterpartW=80 counterparth=80
,03-17 07:10:45.705  1022  1046 W libprocessgroup: failed to open /acct/uid_10055/pid_4084/cgroup.procs: No such file or directory
,03-17 07:10:45.705  4388  4417 I AMMetaDataParserService: Icon data: ResourceDrawer menu2131363563com.android.email.intent.messagelistfragment.drawer2130837576
,03-17 07:10:45.715  1022  1520 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:45.715  1022  1520 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:45.715  1022  1520 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:45.715  1022  1520 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:45.735  4768  4768 E Zygote  : MountEmulatedStorage(),
03-17 07:10:45.735  4768  4768 E Zygote  : v2
03-17 07:10:45.735  4768  4768 I libpersona: KNOX_SDCARD checking this for 10068
03-17 07:10:45.735  4768  4768 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:45.735  4768  4768 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 07:10:45.735  4388  4417 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 80x80
,03-17 07:10:45.735  4388  4417 I GFX construct_block_size_descriptor_2d second part: took 2.541563ms for 0*0 texture 0
03-17 07:10:45.735  1022  1520 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=4768 uid=10068 gids={50068, 9997} abi=armeabi-v7a
03-17 07:10:45.735  4768  4768 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 07:10:45.735  4768  4768 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
03-17 07:10:45.745  1022  1321 D RCPManagerService: exchangeData() failure , invalid userId
03-17 07:10:45.745  4388  4417 I GFX generate_partition_tables: took 5.250729ms for 0*0 texture 0
03-17 07:10:45.745  1022  1667 D RCPManagerService: exchangeData() failure , invalid userId
03-17 07:10:45.745  4388  4417 I GFX raster: took 8.901303ms for 80*80 texture 0
03-17 07:10:45.745  4388  4417 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb78fc858 bitmapCt=12 bitmapW=80 bitmapH=80 BitmapInternalFormat=93b0, Counterpart=0xb78fc900 counterpartCT=4 counterpartW=80 counterparth=80
03-17 07:10:45.745  1022  1034 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:45.745  1022  1034 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:45.745  1022  1034 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.email, destAppInfo.processName = com.android.email
,03-17 07:10:45.755  4388  4417 I AMMetaDataParserService: Icon data: ResourceMessage marked as complete2131362386com.android.email.intent.messageviewfragment.favorite2130837575
,03-17 07:10:45.765  4768  4768 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:45.765  4768  4768 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:45.775  1022  1035 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:45.775  1022  1035 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:45.775  1022  1035 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:45.775  1022  1035 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:45.775  4388  4417 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 80x80
,03-17 07:10:45.775  4388  4417 I GFX raster: took 0.710000ms for 80*80 texture 0
03-17 07:10:45.775  4388  4417 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb78fc858 bitmapCt=12 bitmapW=80 bitmapH=80 BitmapInternalFormat=93b0, Counterpart=0xb774b628 counterpartCT=4 counterpartW=80 counterparth=80
,03-17 07:10:45.785  4388  4417 I AMMetaDataParserService: Icon data: ResourceFlagged message2131362384com.android.email.intent.messageviewfragment.favorite2130837575
,03-17 07:10:45.785  4768  4768 D BadgeProvider: onCreate
03-17 07:10:45.785  4768  4768 D BadgeProvider: DatabaseHelper
,03-17 07:10:45.785  4789  4789 E Zygote  : MountEmulatedStorage()
03-17 07:10:45.785  4789  4789 E Zygote  : v2
03-17 07:10:45.785  4789  4789 I libpersona: KNOX_SDCARD checking this for 10142
03-17 07:10:45.785  4789  4789 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:45.795  4789  4789 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 07:10:45.795  1022  1035 I ActivityManager: Start proc com.android.exchange for broadcast com.android.exchange/.service.ExchangeBroadcastReceiver: pid=4789 uid=10142 gids={50142, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
03-17 07:10:45.795  4789  4789 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 07:10:45.795  4789  4789 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 07:10:45.795  1022  1035 I ActivityManager: Killing 4134:com.samsung.android.scloud.backup/u0a56 (adj 15): empty #31
03-17 07:10:45.795  1022  1035 I ActivityManager: Killing 3870:com.sec.android.fotaclient/u0a8 (adj 15): empty #32
,03-17 07:10:45.815  4768  4780 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,03-17 07:10:45.815  4789  4789 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:45.815  4789  4789 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:45.825  4388  4417 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 80x80
,03-17 07:10:45.825  4388  4417 I GFX raster: took 0.682448ms for 80*80 texture 0
03-17 07:10:45.825  4388  4417 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb78fc858 bitmapCt=12 bitmapW=80 bitmapH=80 BitmapInternalFormat=93b0, Counterpart=0xb758b1e0 counterpartCT=4 counterpartW=80 counterparth=80
,03-17 07:10:45.835  4768  4780 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
03-17 07:10:45.835  4789  4789 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
03-17 07:10:45.835  4768  4780 D BadgeProvider: sendNotify, [notify] : null
03-17 07:10:45.835  4768  4780 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
03-17 07:10:45.835  4768  4780 D BadgeProvider: update, [BadgeCount] : badgecount=0
03-17 07:10:45.835  4768  4780 D BadgeProvider: update, [UpdateCount] : 1
03-17 07:10:45.835  1508  1508 D Launcher.Model: reloadBadges entered.
,03-17 07:10:45.845  4388  4417 I AMMetaDataParserService: Icon data: ResourceUnflagged message2131362385com.android.email.intent.messageviewfragment.favorite2130837575
,03-17 07:10:45.855  1022  1597 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:45.855  1022  1597 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 07:10:45.855  1022  1597 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,03-17 07:10:45.865  3976  4122 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,03-17 07:10:45.865  1022  1034 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,03-17 07:10:45.865  1022  1659 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,03-17 07:10:45.875  1022  1520 W ActivityManager: getTasks: caller 10141 does not hold GET_TASKS; limiting output
,03-17 07:10:45.875  4699  4787 I Process : Sending signal. PID: 4699 SIG: 9
,03-17 07:10:45.875  1022  1046 W libprocessgroup: failed to open /acct/uid_10056/pid_4134/cgroup.procs: No such file or directory
03-17 07:10:45.875  1022  1046 W libprocessgroup: failed to open /acct/uid_10008/pid_3870/cgroup.procs: No such file or directory
,03-17 07:10:45.885  1022  3349 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-17 07:10:45.895  1022  1659 D RCPManagerService: exchangeData() failure , invalid userId
,03-17 07:10:45.905  4388  4417 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 80x80
,03-17 07:10:45.905  4388  4417 I GFX raster: took 0.762604ms for 80*80 texture 0
,03-17 07:10:45.905  4388  4417 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb75887e8 bitmapCt=12 bitmapW=80 bitmapH=80 BitmapInternalFormat=93b0, Counterpart=0xb7588890 counterpartCT=4 counterpartW=80 counterparth=80
,03-17 07:10:45.915  1022  3313 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.ssrm.I.m:-1 com.android.server.ssrm.J.run:-1 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 
,03-17 07:10:45.915  4388  4417 I AMMetaDataParserService: Icon data: ResourceStarred message2131362389com.android.email.intent.messageviewfragment.favorite2130837577
,03-17 07:10:45.925  1022  1392 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:45.925  1022  1392 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:45.925  1022  1392 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.exchange, destAppInfo.processName = com.android.exchange
,03-17 07:10:45.925  1022  1321 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:45.925  1022  1321 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:45.925  1022  1321 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:45.925  1022  1321 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:45.945  4808  4808 E Zygote  : MountEmulatedStorage(),
03-17 07:10:45.945  4808  4808 E Zygote  : v2
03-17 07:10:45.945  4808  4808 I libpersona: KNOX_SDCARD checking this for 1000
03-17 07:10:45.945  4808  4808 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:45.945  4808  4808 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,03-17 07:10:45.945  4808  4808 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
03-17 07:10:45.945  4808  4808 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 07:10:45.945  1022  1321 I ActivityManager: Start proc com.sec.android.app.SecSetupWizard for broadcast com.sec.android.app.SecSetupWizard/.SetupIntentReceiver: pid=4808 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,03-17 07:10:45.955  4388  4417 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 80x80
03-17 07:10:45.955  4388  4417 I GFX raster: took 0.626042ms for 80*80 texture 0
,03-17 07:10:45.955  4388  4417 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb75887e8 bitmapCt=12 bitmapW=80 bitmapH=80 BitmapInternalFormat=93b0, Counterpart=0xb7589280 counterpartCT=4 counterpartW=80 counterparth=80,
,03-17 07:10:45.965  4388  4417 I AMMetaDataParserService: Icon data: ResourceUnstarred message2131362390com.android.email.intent.messageviewfragment.favorite2130837577
,03-17 07:10:45.965  1022  1520 I ActivityManager: Process com.android.email (pid 4699)(adj 9) has died(36,656)
,03-17 07:10:45.975  4808  4808 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:45.975  4808  4808 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:45.985  1022  1034 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:45.985  1022  1034 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:45.985  1022  1034 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:45.985  1022  1034 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:45.995  4824  4824 E Zygote  : MountEmulatedStorage()
,03-17 07:10:45.995  4824  4824 E Zygote  : v2
,03-17 07:10:45.995  4824  4824 I libpersona: KNOX_SDCARD checking this for 10141
03-17 07:10:45.995  4824  4824 I libpersona: KNOX_SDCARD not a persona
03-17 07:10:45.995  4824  4824 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 07:10:45.995  1022  1034 I ActivityManager: Start proc com.android.email for content provider com.android.email/.provider.EmailProvider: pid=4824 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a,
,03-17 07:10:46.005  4824  4824 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,03-17 07:10:46.005  4824  4824 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 07:10:46.005  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.MailboxSettings
03-17 07:10:46.005  4388  4417 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
03-17 07:10:46.005  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.messageview.SelectGroup
03-17 07:10:46.005  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.messageview.SavedEmail
03-17 07:10:46.005  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.messageview.MessageFileView
03-17 07:10:46.005  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsHtmlSignature
03-17 07:10:46.005  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.MessageCompose
03-17 07:10:46.005  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:46.005  4388  4417 I AMMetaDataParserService: getResourcePackageName:android.app.spellscroll
03-17 07:10:46.005  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.SelectMapActivity
03-17 07:10:46.005  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.CustomizeDate
03-17 07:10:46.005  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.QuickReplyActivity
03-17 07:10:46.005  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.SettingsReservationActivity
03-17 07:10:46.005  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.AttachmentChooserActivity
03-17 07:10:46.005  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.DebugActivity
03-17 07:10:46.005  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupBasicsChoiceProviderForKOR
03-17 07:10:46.005  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSoundNotiSetup
03-17 07:10:46.005  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSoundNotiGeneralPreference
03-17 07:10:46.005  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.SearchActivity
03-17 07:10:46.005  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:46.005  4388  4417 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
03-17 07:10:46.005  4388  4417 I AMMetaDataParserService: getResourcePackageName:android.app.default_searchable
03-17 07:10:46.005  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.MessageComposeDrawingModePopup
03-17 07:10:46.005  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.utils.airjump.EmailAirScrollTryActivity
03-17 07:10:46.005  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.SmartStayActivity
,03-17 07:10:46.025  1022  1597 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:46.025  1022  1597 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:46.025  1022  1597 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:46.025  1022  1597 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:46.025  4824  4824 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:46.035  4824  4824 D ActivityThread: Added TimaKeyStore provider,
,03-17 07:10:46.035  4840  4840 E Zygote  : MountEmulatedStorage()
,03-17 07:10:46.035  4840  4840 E Zygote  : v2
,03-17 07:10:46.045  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.rcs.RcsNewFeatureActivity
03-17 07:10:46.045  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.RoamingGuardPopupActivity
03-17 07:10:46.045  4840  4840 I libpersona: KNOX_SDCARD checking this for 1000
03-17 07:10:46.045  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.AutoRetrievePreferenceActivity
03-17 07:10:46.045  4840  4840 I libpersona: KNOX_SDCARD not a persona
03-17 07:10:46.045  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.AutoRetrieveTabActivity
03-17 07:10:46.045  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ConversationComposer
03-17 07:10:46.045  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-17 07:10:46.045  4388  4417 I AMMetaDataParserService: getResourcePackageName:android.app.spellscroll
,03-17 07:10:46.045  4388  4417 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
03-17 07:10:46.045  4388  4417 I AMMetaDataParserService: getResourcePackageName:android.app.default_searchable
03-17 07:10:46.045  4388  4417 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-17 07:10:46.045  4388  4417 I AMMetaDataParserService: getResourcePackageName:assistant
,03-17 07:10:46.045  4388  4417 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 07:10:46.045  4388  4417 I AMMetaDataParserService: Resource data:2131099648
03-17 07:10:46.045  4388  4417 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
03-17 07:10:46.045  4840  4840 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 07:10:46.045  4388  4417 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
03-17 07:10:46.045  4840  4840 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 07:10:46.045  4840  4840 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 07:10:46.045  4388  4417 I AMMetaDataParserService: getResourceName:com.android.mms:xml/assistant_messaging
03-17 07:10:46.045  4388  4417 I AMMetaDataParserService: getResourceTypeNamexml
,03-17 07:10:46.045  1022  1597 I ActivityManager: Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.BootReceiver: pid=4840 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-17 07:10:46.045  1022  1597 I ActivityManager: Killing 4118:com.google.android.onetimeinitializer/u0a13 (adj 15): empty #31
,03-17 07:10:46.055  4388  4417 I AMMetaDataParserService: Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
03-17 07:10:46.055  1022  1321 I ActivityManager: Killing 3976:com.google.android.gm/u0a99 (adj 15): empty #31
,03-17 07:10:46.065  4824  4824 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,03-17 07:10:46.065  4824  4824 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-17 07:10:46.065  4388  4417 I AMMetaDataParserService: Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
03-17 07:10:46.065  4824  4824 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 07:10:46.065  4824  4824 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,03-17 07:10:46.065  4840  4840 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:46.075  4840  4840 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:46.085  4388  4417 I AMMetaDataParserService: Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,03-17 07:10:46.095  4628  4628 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,03-17 07:10:46.095  1022  1404 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:46.095  1022  1404 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:46.095  1022  1404 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,03-17 07:10:46.105  1022  1902 I ActivityManager: Killing 4179:com.samsung.android.scloud.sync/u0a58 (adj 15): empty #31
,03-17 07:10:46.125  4840  4840 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,03-17 07:10:46.125  4840  4840 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
03-17 07:10:46.125  4840  4840 D SecurityLogAgent: StateMachine : Current State = 1
03-17 07:10:46.125  4840  4840 D SecurityLogAgent: BootReceiver : completed task. Failed to return wakelock . 
,03-17 07:10:46.125  1022  1659 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:46.125  1022  1659 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:46.125  1022  1659 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:46.125  1022  1659 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:46.135  3693  3744 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 6 sec
03-17 07:10:46.135  4388  4417 I AMMetaDataParserService: Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,03-17 07:10:46.135  4856  4856 E Zygote  : MountEmulatedStorage(),
03-17 07:10:46.135  4856  4856 E Zygote  : v2
03-17 07:10:46.135  4856  4856 I libpersona: KNOX_SDCARD checking this for 10148
03-17 07:10:46.135  4856  4856 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:46.145  4856  4856 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 07:10:46.145  4856  4856 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 07:10:46.145  1022  1659 I ActivityManager: Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=4856 uid=10148 gids={50148, 9997, 1023} abi=armeabi-v7a,
03-17 07:10:46.145  1022  1129 D RCPManagerService: exchangeData() failure , invalid userId
03-17 07:10:46.145  1022  1659 I ActivityManager: Killing 4201:com.google.android.talk/u0a102 (adj 15): empty #31
03-17 07:10:46.145  4856  4856 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 07:10:46.145  4388  4417 I AMMetaDataParserService: Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
03-17 07:10:46.145  1022  3313 D SSRM:n  : SIOP:: AP = 410
,03-17 07:10:46.155  1022  1667 D RCPManagerService: exchangeData() failure , invalid userId
,03-17 07:10:46.165  4388  4417 I AMMetaDataParserService: Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,03-17 07:10:46.165  4856  4856 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:46.165  4856  4856 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:46.175   304   304 I art     : Explicit concurrent mark sweep GC freed 8717(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 645us total 30.803ms
,03-17 07:10:46.175  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ComposeMessageActivityNoLockScreen
03-17 07:10:46.175  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ComposeMessageMms
03-17 07:10:46.175  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-17 07:10:46.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:assistant
03-17 07:10:46.185  4388  4417 I AMMetaDataParserService: Resource data:2131099648
,03-17 07:10:46.185  4388  4417 I AMMetaDataParserService: getResourceName:com.android.mms:xml/assistant_messaging
03-17 07:10:46.185  4388  4417 I AMMetaDataParserService: getResourceTypeNamexml
,03-17 07:10:46.185  1022  1902 D RCPManagerService: exchangeData() failure , invalid userId
03-17 07:10:46.185  4388  4417 I AMMetaDataParserService: Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,03-17 07:10:46.195  1022  1520 D RCPManagerService: exchangeData() failure , invalid userId
03-17 07:10:46.195   304   304 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 586us total 17.459ms
,03-17 07:10:46.205  4388  4417 I AMMetaDataParserService: Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,03-17 07:10:46.215   304   304 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 601us total 16.869ms
,03-17 07:10:46.225  1022  1046 W libprocessgroup: failed to open /acct/uid_10013/pid_4118/cgroup.procs: No such file or directory
03-17 07:10:46.225  1022  1046 W libprocessgroup: failed to open /acct/uid_10099/pid_3976/cgroup.procs: No such file or directory
,03-17 07:10:46.225  4856  4856 E SQLiteLog: (284) automatic index on shooting_modes(title_id)
,03-17 07:10:46.235  4388  4417 I AMMetaDataParserService: Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,03-17 07:10:46.235  1022  1667 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:46.245  1022  1667 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-17 07:10:46.245  1022  1667 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.provider.shootingmodeprovider, destAppInfo.processName = com.samsung.android.provider.shootingmodeprovider
03-17 07:10:46.245  1022  1046 W libprocessgroup: failed to open /acct/uid_10058/pid_4179/cgroup.procs: No such file or directory
03-17 07:10:46.245  1022  1046 W libprocessgroup: failed to open /acct/uid_10102/pid_4201/cgroup.procs: No such file or directory
,03-17 07:10:46.245  1022  1035 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:46.245  1022  1035 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:46.245  1022  1035 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:46.245  1022  1035 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:46.245  4388  4417 I AMMetaDataParserService: Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,03-17 07:10:46.255  4880  4880 E Zygote  : MountEmulatedStorage()
03-17 07:10:46.255  4880  4880 E Zygote  : v2
03-17 07:10:46.255  4880  4880 I libpersona: KNOX_SDCARD checking this for 1000
03-17 07:10:46.255  4880  4880 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:46.265  1022  1659 D RCPManagerService: exchangeData() failure , invalid userId
03-17 07:10:46.265  4880  4880 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 07:10:46.265  1022  1404 D RCPManagerService: exchangeData() failure , invalid userId
,03-17 07:10:46.265  4388  4417 I AMMetaDataParserService: Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
03-17 07:10:46.265  1022  1035 I ActivityManager: Start proc com.sec.modem.settings for broadcast com.sec.modem.settings/.cplogging.SilentLogReceiver: pid=4880 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,03-17 07:10:46.265  4880  4880 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 07:10:46.265  4880  4880 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 07:10:46.275  4768  4780 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
03-17 07:10:46.275  1022  1667 W ActivityManager: getTasks: caller 10142 does not hold GET_TASKS; limiting output
,03-17 07:10:46.275  1022  1404 I ActivityManager: Killing 3919:com.google.android.partnersetup/u0a14 (adj 15): empty #31
,03-17 07:10:46.285  4789  4823 I Process : Sending signal. PID: 4789 SIG: 9
,03-17 07:10:46.285  4388  4417 I AMMetaDataParserService: Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,03-17 07:10:46.285  1508  1508 D Launcher.Model: reloadBadges entered.
03-17 07:10:46.285  4768  4780 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
03-17 07:10:46.285  4768  4780 D BadgeProvider: sendNotify, [notify] : null
03-17 07:10:46.285  4768  4780 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
03-17 07:10:46.285  4768  4780 D BadgeProvider: update, [BadgeCount] : badgecount=0
03-17 07:10:46.285  4768  4780 D BadgeProvider: update, [UpdateCount] : 1
,03-17 07:10:46.295  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.TransferContentActivity
03-17 07:10:46.295  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.CbConfigPreferenceActivity
03-17 07:10:46.295  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.CbSettingTabActivity
03-17 07:10:46.295  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ComposeMessage
03-17 07:10:46.295  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:46.295  4388  4417 I AMMetaDataParserService: getResourcePackageName:assistant
03-17 07:10:46.295  4388  4417 I AMMetaDataParserService: Resource data:2131099648
,03-17 07:10:46.295  4388  4417 I AMMetaDataParserService: getResourceName:com.android.mms:xml/assistant_messaging
03-17 07:10:46.295  4388  4417 I AMMetaDataParserService: getResourceTypeNamexml
,03-17 07:10:46.295  4880  4880 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:46.295  4880  4880 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:46.295  4388  4417 I AMMetaDataParserService: Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,03-17 07:10:46.315  4388  4417 I AMMetaDataParserService: Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,03-17 07:10:46.325  1022  1902 I splitIntent: Queue : backgroundsplit_1 intent android.intent.action.BOOT_COMPLETED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,03-17 07:10:46.325   254   254 E lowmemorykiller: Error writing /proc/4789/oom_score_adj; errno=22
,03-17 07:10:46.335  1022  1902 I ActivityManager: Killing 4219:com.sec.android.app.servicemodeapp/1000 (adj 15): empty #31
,03-17 07:10:46.335   254   254 E lowmemorykiller: Error writing /proc/4789/oom_score_adj; errno=22
,03-17 07:10:46.335  4388  4417 I AMMetaDataParserService: Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,03-17 07:10:46.335  4840  4840 D SecurityLogAgent:  SeDenialReceiver : Intent received : samsung.intent.action.knox.DENIAL_NOTIFICATION
03-17 07:10:46.335  4840  4840 D SecurityLogAgent:  SeDenialReceiver : File path = /data/misc/audit/audit.old
,03-17 07:10:46.345  4840  4840 D SecurityLogAgent:  SeDenialReceiver : Start file Zipping Service 
,03-17 07:10:46.345  1022  1034 I ActivityManager: Process com.android.exchange (pid 4789)(adj 13) has died(52,657)
,03-17 07:10:46.345  4388  4417 I AMMetaDataParserService: Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,03-17 07:10:46.345  4840  4840 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 android.support.v4.a.c.a:-1 com.samsung.android.securitylogagent.receivers.SeDenialReceiver.onReceive:-1 
,03-17 07:10:46.355  1022  1129 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:46.355  1022  1129 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:46.355  1022  1129 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.securitylogagent, destAppInfo.processName = com.samsung.android.securitylogagent
,03-17 07:10:46.355  1022  1520 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:46.355  1022  1520 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:46.355  1022  1520 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.daemonapp
,03-17 07:10:46.355  4388  4417 I AMMetaDataParserService: Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,03-17 07:10:46.365  1788  1788 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,03-17 07:10:46.365  1788  1788 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,03-17 07:10:46.365  4840  4896 D SecurityLogAgent: FileZippingService : onHandleIntent 
,03-17 07:10:46.365  4840  4896 D SecurityLogAgent: FileZippingService : file path =  /data/misc/audit/audit.old
03-17 07:10:46.365  4388  4417 I AMMetaDataParserService: Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,03-17 07:10:46.375  4840  4896 D SecurityLogAgent: FileZippingService : onPremise disabled. Zipping..  
03-17 07:10:46.375  1788  1788 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,03-17 07:10:46.375  4840  4896 D SecurityLogAgent: DenialLogFileZipCreator : createZip
,03-17 07:10:46.375  4840  4896 D SecurityLogAgent: DenialLogFileZipCreator : Not empty 
,03-17 07:10:46.375  1788  1788 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,03-17 07:10:46.375  4840  4896 D SecurityLogAgent: DenialLogFileZipCreator : Files exceeded the max limit 
,03-17 07:10:46.375  1788  1788 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,03-17 07:10:46.385  1788  1788 D daemonapp: [MSC_Daemon]>>> WDSM:54 [0:0] Act : widgetappapaccuweatherdaemonactionCURRENT_LOCATION_WEATHER_DATA, run:true
,03-17 07:10:46.385  1788  1788 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================,
,03-17 07:10:46.385  1788  1788 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
,03-17 07:10:46.385  1788  1788 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
,03-17 07:10:46.385  1788  1788 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
,03-17 07:10:46.385  1788  1788 D daemonapp: [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
,03-17 07:10:46.385  1788  1788 D daemonapp: [MSC_Daemon]>>> WDSM:119 [0:0] start_app:true, packagename:widgetappapheroaccuweather, cp:Accuweather, aRS:false
,03-17 07:10:46.385  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ForwardMessageActivity
03-17 07:10:46.385  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:46.385  4388  4417 I AMMetaDataParserService: getResourcePackageName:assistant
03-17 07:10:46.385  4388  4417 I AMMetaDataParserService: Resource data:2131099648
,03-17 07:10:46.385  4388  4417 I AMMetaDataParserService: getResourceName:com.android.mms:xml/assistant_messaging
03-17 07:10:46.385  4388  4417 I AMMetaDataParserService: getResourceTypeNamexml
,03-17 07:10:46.395  4840  4896 D SecurityLogAgent: DenialLogFileZipCreator File existence : true audit.old file size 631
,03-17 07:10:46.395  4388  4417 I AMMetaDataParserService: Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,03-17 07:10:46.395  1788  1788 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,03-17 07:10:46.395  1788  1788 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,03-17 07:10:46.405  4840  4896 D SecurityLogAgent: DenialLogFileZipCreator : There is no denied message in audit.old . Dismisses zipping . 
,03-17 07:10:46.405  4388  4417 I AMMetaDataParserService: Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,03-17 07:10:46.405  4840  4896 D SecurityLogAgent: FileZippingService : completed task. Returning wakelock . 
,03-17 07:10:46.415  4388  4417 I AMMetaDataParserService: Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,03-17 07:10:46.425  4388  4417 I AMMetaDataParserService: Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,03-17 07:10:46.435  1788  1788 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,03-17 07:10:46.435  4388  4417 I AMMetaDataParserService: Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,03-17 07:10:46.435  1788  1788 D daemonapp: [MSC_Daemon]>>> WDSM:140 [0:0] Widget flag autoRefreshSet :  false
,03-17 07:10:46.435  1022  1129 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:46.435  1022  1129 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:46.435  1022  1129 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
,03-17 07:10:46.455  1022  1520 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:46.455  1022  1520 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:46.455  1022  1520 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-17 07:10:46.465  1022  1022 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:46.465  1022  1022 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:46.465  1022  1022 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-17 07:10:46.465  1022  1022 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:46.465  1022  1022 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:46.465  1022  1022 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-17 07:10:46.475  1022  1022 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:46.475  1022  1022 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-17 07:10:46.475  1022  1022 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-17 07:10:46.475  1022  1597 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,03-17 07:10:46.475  1022  1022 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:46.475  1022  1022 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:46.475  1022  1022 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-17 07:10:46.485  1485  4898 D SIP     : [SipSharedPreferences] isReceivingCallsEnabled, option not set; use default value, exception: android.provider.Settings$SettingNotFoundException: sip_receive_calls,
,03-17 07:10:46.485  1022  1022 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:46.485  1022  1022 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:46.485  1022  1022 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-17 07:10:46.485  1022  1022 W ActivityManager: userId = 0, bbcId = -10000,
03-17 07:10:46.485  1022  1022 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:46.485  1022  1022 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-17 07:10:46.485  1485  4898 E File    : fail readDirectory() errno=2,
,03-17 07:10:46.485  1022  1022 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:46.485  1022  1022 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-17 07:10:46.485  1022  1022 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-17 07:10:46.495  1022  1022 W ActivityManager: userId = 0, bbcId = -10000,
03-17 07:10:46.495  1022  1022 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-17 07:10:46.495  1022  1022 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-17 07:10:46.495  1022  1022 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:46.495  1022  1022 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:46.495  1022  1022 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-17 07:10:46.495  1022  1022 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:46.495  1022  1022 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:46.495  1022  1022 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-17 07:10:46.505  1022  1022 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:46.505  1022  1022 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:46.505  1022  1022 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-17 07:10:46.505  1022  1022 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:46.505  1022  1022 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:46.505  1022  1022 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-17 07:10:46.505  4388  4417 I AMMetaDataParserService: Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,03-17 07:10:46.505  1022  1022 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:46.505  1022  1022 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:46.505  1022  1022 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-17 07:10:46.505  1022  1022 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:46.505  1022  1022 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:46.505  1022  1022 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-17 07:10:46.515  1022  1022 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:46.515  1022  1022 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 07:10:46.515  1022  1022 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:46.515  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ReplyMessageActivity
,03-17 07:10:46.515  1022  1404 I splitIntent: intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
,03-17 07:10:46.515  1022  1404 I splitIntent: base  index=1, name=com.google.android.gms com.google.android.gms.wearable.service.AutoStarterReceiver
03-17 07:10:46.515  1022  1404 I splitIntent: other index=4, name=com.google.android.gms com.google.android.gms.init.InitializeGmsReceiver
03-17 07:10:46.515  1022  1404 I splitIntent: arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
03-17 07:10:46.515  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:46.515  4388  4417 I AMMetaDataParserService: getResourcePackageName:assistant
03-17 07:10:46.515  4388  4417 I AMMetaDataParserService: Resource data:2131099648
,03-17 07:10:46.515  4388  4417 I AMMetaDataParserService: getResourceName:com.android.mms:xml/assistant_messaging
03-17 07:10:46.515  4388  4417 I AMMetaDataParserService: getResourceTypeNamexml
,03-17 07:10:46.515  1022  1404 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:46.515  1022  1404 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-17 07:10:46.515  1022  1404 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:46.525  4388  4417 I AMMetaDataParserService: Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,03-17 07:10:46.535  1022  1129 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:46.535  1022  1129 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-17 07:10:46.535  1022  1129 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:46.535  4388  4417 I AMMetaDataParserService: Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,03-17 07:10:46.545  4388  4417 I AMMetaDataParserService: Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,03-17 07:10:46.555  1022  1392 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:46.555  1022  1392 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 07:10:46.555  1022  1392 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:46.555  4388  4417 I AMMetaDataParserService: Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,03-17 07:10:46.565  4388  4417 I AMMetaDataParserService: Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,03-17 07:10:46.575  1022  1902 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:46.575  1022  1902 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-17 07:10:46.575  1022  1902 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:46.575  4388  4417 I AMMetaDataParserService: Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,03-17 07:10:46.585  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ConversationList
03-17 07:10:46.585  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:46.585  4388  4417 I AMMetaDataParserService: getResourcePackageName:assistant
03-17 07:10:46.585  4388  4417 I AMMetaDataParserService: Resource data:2131099648
,03-17 07:10:46.585  4388  4417 I AMMetaDataParserService: getResourceName:com.android.mms:xml/assistant_messaging
03-17 07:10:46.585  4388  4417 I AMMetaDataParserService: getResourceTypeNamexml
,03-17 07:10:46.585  1022  1321 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:46.595  1022  1321 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-17 07:10:46.595  1022  1321 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:46.595  4388  4417 I AMMetaDataParserService: Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,03-17 07:10:46.595  1880  4900 E MDM     : [230] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,03-17 07:10:46.595  1022  1659 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:46.595  1022  1659 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 07:10:46.595  1022  1659 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:46.605  1022  1507 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:46.605  1022  1507 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 07:10:46.605  1022  1507 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:46.605  2141  4901 D LocationInitializer: Restart initialization of location
,03-17 07:10:46.605  4388  4417 I AMMetaDataParserService: Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,03-17 07:10:46.605  1022  1035 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:46.605  1022  1035 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 07:10:46.605  1022  1035 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:46.615  1022  1034 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:46.615  1022  1034 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-17 07:10:46.615  1022  1034 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:46.615  4388  4417 I AMMetaDataParserService: Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,03-17 07:10:46.625  1022  1902 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:46.625  1022  1902 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 07:10:46.625  1022  1902 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:46.635  4388  4417 I AMMetaDataParserService: Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,03-17 07:10:46.645  4388  4417 I AMMetaDataParserService: Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,03-17 07:10:46.645  1022  1659 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:46.645  1022  1659 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 07:10:46.645  1022  1659 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:46.655  1022  1046 W libprocessgroup: failed to open /acct/uid_10014/pid_3919/cgroup.procs: No such file or directory
,03-17 07:10:46.655  1022  1046 W libprocessgroup: failed to open /acct/uid_1000/pid_4219/cgroup.procs: No such file or directory
,03-17 07:10:46.655  4388  4417 I AMMetaDataParserService: Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,03-17 07:10:46.675  1022  1035 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:46.675  1022  1035 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 07:10:46.675  1022  1035 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:46.685  1485  1505 D TP/SmsProvider: query,matched:0, calling pid = 2141
,03-17 07:10:46.685  1485  1505 D TP/SmsProvider: match 0:Elapsed time : 1.509 ms
,03-17 07:10:46.685  1485  1807 D TP/MmsProvider: Query uri=content://mms, match=0, calling pid = 2141
,03-17 07:10:46.695  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.WarnOfStorageLimitsActivity
03-17 07:10:46.695  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.SlideshowActivity
03-17 07:10:46.695  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.MmsSinglePageActivity
03-17 07:10:46.695  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ClassZeroActivity
03-17 07:10:46.695  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.RetryActivity
03-17 07:10:46.695  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.MessagingPreferenceActivity
03-17 07:10:46.695  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.EntrancePrefActivity
03-17 07:10:46.695  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.DisplaySettings
03-17 07:10:46.695  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.CMASSettings
03-17 07:10:46.695  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.TextMessagesSettings
03-17 07:10:46.695  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.MultimediamessagesSettings
03-17 07:10:46.695  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.rcs.settings.RcsMessagesSettings
03-17 07:10:46.695  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.DeleteoldMessagesSettings
03-17 07:10:46.695  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.PushMessagesSettings
03-17 07:10:46.695  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.NotificationSettings
03-17 07:10:46.695  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.NotificationSettingsDS
03-17 07:10:46.695  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.SignatureSettings
03-17 07:10:46.695  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.SpamSettings
03-17 07:10:46.695  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.SafemodeSettings
03-17 07:10:46.695  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.DelaySendingSettings
03-17 07:10:46.695  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.smishing.PackageAuthorityActivity
03-17 07:10:46.695  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.smishing.PackageAuthorityDialog
03-17 07:10:46.695  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.MessageSmscActivityDS
03-17 07:10:46.695  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.SignatureEditActivity
03-17 07:10:46.695  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.CallbackNumberSettings
03-17 07:10:46.695  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.CallbackNumberEditActivity
03-17 07:10:46.695  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.BackgroundStyle
03-17 07:10:46.695  4388  4417 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.se,rviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
03-17 07:10:46.695  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.BubbleStyle
03-17 07:10:46.695  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.PushMessageDialog
03-17 07:10:46.695  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.saverestore.SaveThreadActivity
03-17 07:10:46.695  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.saverestore.SavedMsgsList
03-17 07:10:46.695  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.saverestore.RestorePreviewActivity
03-17 07:10:46.695  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.saverestore.ConversationListRestore
03-17 07:10:46.695  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ManageSimMessages
03-17 07:10:46.695  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.MmsRetryActivity
03-17 07:10:46.695  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ConfirmRateLimitActivity
03-17 07:10:46.695  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.SearchActivity
03-17 07:10:46.695  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:46.695  4388  4417 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
,03-17 07:10:46.695  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.SmsViewerActivity
03-17 07:10:46.695  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.MmsNotificationViewerActivity
03-17 07:10:46.695  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.DrmContentsActivity
03-17 07:10:46.695  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.CMASPreferenceActivity
03-17 07:10:46.695  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.CMASDialog
03-17 07:10:46.695  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.CMASDialog_single_top
03-17 07:10:46.695  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.PDPResetDialog
,03-17 07:10:46.695  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.CMASUserPromptDialog
03-17 07:10:46.695  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.LockedMessageManager
03-17 07:10:46.695  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.SpamMessageManager
03-17 07:10:46.695  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ReservationMessageManager
03-17 07:10:46.695  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.DraftMessageManager
,03-17 07:10:46.695  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.SafeMessageManager,
03-17 07:10:46.695  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.RecipientListActivity
03-17 07:10:46.695  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.GroupMessagingRecipientListActivity
03-17 07:10:46.695  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.SelectMapActivity
,03-17 07:10:46.695  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.location.LocationMapActivity
03-17 07:10:46.695  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:46.695  4388  4417 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
03-17 07:10:46.695  4388  4417 I AMMetaDataParserService: getResourcePackageName:android.app.default_searchable
,03-17 07:10:46.695  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.location.FavoritePlacesList
03-17 07:10:46.695  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.location.RecentPlacesList
03-17 07:10:46.695  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.BoxListViewActivity
03-17 07:10:46.695  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:46.695  4388  4417 I AMMetaDataParserService: getResourcePackageName:android.app.default_searchable
03-17 07:10:46.695  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.provisioning.MmsProvisionActivity
,03-17 07:10:46.695  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ManageSDMessages
03-17 07:10:46.695  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.spam.SetupSpamNumberList
03-17 07:10:46.695  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.spam.SetupSpamKeywordList
03-17 07:10:46.695  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.spam.SetupSpamNumberWriteForm
03-17 07:10:46.695  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.spam.SetupSpamKeywordWriteForm
03-17 07:10:46.695  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.SettingsReservationActivity
03-17 07:10:46.695  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.SettingsTransmitMessageActivity
,03-17 07:10:46.695  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.MessageDatabaseBackupActivity
03-17 07:10:46.695  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.widget.NoticeThreadContactSelector
03-17 07:10:46.695  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.widget.NoticeEditActivity
03-17 07:10:46.695  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.widget.NoticeDeleteActivity
03-17 07:10:46.695  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.export.MmsPartExportDialogActivity
03-17 07:10:46.695  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.export.MmsPartExportDialogActivityAlien
03-17 07:10:46.695  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.DirectCallTutorialActivity
03-17 07:10:46.695  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.FakeCallActivity
03-17 07:10:46.695  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.MmsPartExportActivity
03-17 07:10:46.695  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.template.TextTemplateListActivity
,03-17 07:10:46.695  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.template.TextTemplateEditActivity
03-17 07:10:46.695  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.help.AirViewMainActivity
03-17 07:10:46.695  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.help.AirButtonMainActivity
03-17 07:10:46.695  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.widget.WidgetPreferenceActivity
03-17 07:10:46.695  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.cover.MissedMsgActivity
03-17 07:10:46.695  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.oem.AutoSendingTestActivity
03-17 07:10:46.695  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.prioritysender.AddGlanceListActivity
,03-17 07:10:46.695  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.prioritysender.AddThreadListActivity
03-17 07:10:46.695  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.CheckDefaultSmsAppsActivity
03-17 07:10:46.695  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.accessory.ReadReportActivity
03-17 07:10:46.695  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.FileHistoryListActivity
03-17 07:10:46.695  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.FreeMessageSettings
03-17 07:10:46.695  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.prioritysenderpanel.CocktailPrioritySenderSettingActivity
,03-17 07:10:46.705  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.GalleryOpaqueActivity
03-17 07:10:46.705  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:46.705  4388  4417 I AMMetaDataParserService: getResourcePackageName:assistant
03-17 07:10:46.705  4388  4417 I AMMetaDataParserService: Resource data:2131165197
,03-17 07:10:46.705  1485  1505 D TP/SmsProvider: query,matched:0, calling pid = 2141
,03-17 07:10:46.705  1485  1505 D TP/SmsProvider: match 0:Elapsed time : 0.974 ms
,03-17 07:10:46.715  4388  4417 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,03-17 07:10:46.715  4388  4417 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-17 07:10:46.715  4388  4417 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 07:10:46.715  4388  4417 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,03-17 07:10:46.715  4388  4417 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
03-17 07:10:46.715  4388  4417 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
03-17 07:10:46.715  4388  4417 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,03-17 07:10:46.715  4388  4417 I AMMetaDataParserService: getResourceName:com.sec.android.gallery3d:xml/assistant
03-17 07:10:46.715  4388  4417 I AMMetaDataParserService: getResourceTypeNamexml
,03-17 07:10:46.715  1485  1807 D TP/MmsProvider: Query uri=content://mms, match=0, calling pid = 2141
,03-17 07:10:46.745  4388  4417 I AMMetaDataParserService: Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,03-17 07:10:46.755  1022  1343 E Watchdog: !@Sync 1
,03-17 07:10:46.755  4388  4417 I AMMetaDataParserService: Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
,03-17 07:10:46.755  1022  1100 V AlarmManager: waitForAlarm result :8
,03-17 07:10:46.775  1022  1141 D SettingsProvider: name = audio_safe_volume_state
,03-17 07:10:46.775  4388  4417 I AMMetaDataParserService: Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,03-17 07:10:46.785  4388  4417 I AMMetaDataParserService: Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,03-17 07:10:46.795  1022  1035 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:46.795  1022  1035 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-17 07:10:46.795  1022  1035 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:46.795  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.GalleryActivity
03-17 07:10:46.795  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:46.795  4388  4417 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
03-17 07:10:46.795  4388  4417 I AMMetaDataParserService: getResourcePackageName:assistant
03-17 07:10:46.795  4388  4417 I AMMetaDataParserService: Resource data:2131165197
,03-17 07:10:46.795  4388  4417 I AMMetaDataParserService: getResourceName:com.sec.android.gallery3d:xml/assistant
03-17 07:10:46.795  4388  4417 I AMMetaDataParserService: getResourceTypeNamexml
,03-17 07:10:46.815  1880  1880 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,03-17 07:10:46.815  1880  1880 D a       : Opening database auth.proximity.permit_store...
,03-17 07:10:46.825  4388  4417 I AMMetaDataParserService: Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,03-17 07:10:46.825  1022  1404 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:46.825  1022  1404 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-17 07:10:46.825  1022  1404 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:46.835  1022  1659 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:46.835  1022  1659 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-17 07:10:46.835  1022  1659 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:46.845  4388  4417 I AMMetaDataParserService: Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
,03-17 07:10:46.865  4388  4417 I AMMetaDataParserService: Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,03-17 07:10:46.875  1022  1520 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:46.875  1022  1520 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-17 07:10:46.875  1022  1520 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:46.885  4388  4417 I AMMetaDataParserService: Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,03-17 07:10:46.885  1022  1902 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:46.885  1022  1902 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 07:10:46.885  1022  1902 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:46.895  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.cooliris.media.Gallery
03-17 07:10:46.895  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.Gallery
03-17 07:10:46.895  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:46.895  4388  4417 I AMMetaDataParserService: getResourcePackageName:assistant
03-17 07:10:46.895  4388  4417 I AMMetaDataParserService: Resource data:2131165197
,03-17 07:10:46.895  4388  4417 I AMMetaDataParserService: getResourceName:com.sec.android.gallery3d:xml/assistant
03-17 07:10:46.895  4388  4417 I AMMetaDataParserService: getResourceTypeNamexml
,03-17 07:10:46.895  1022  1507 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:46.895  1022  1507 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 07:10:46.895  1022  1507 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:46.905  1022  1129 I art     : Explicit concurrent mark sweep GC freed 25125(1417KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 24MB/36MB, paused 2.629ms total 149.100ms
,03-17 07:10:46.915  1880  1880 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 07:10:46.915  4388  4417 I AMMetaDataParserService: Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,03-17 07:10:46.925  4388  4417 I AMMetaDataParserService: Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
,03-17 07:10:46.935  1022  1597 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:46.935  1022  1597 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 07:10:46.935  1022  1597 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:46.945  1022  1129 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:46.945  1022  1129 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 07:10:46.945  1022  1129 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:46.945  4388  4417 I AMMetaDataParserService: Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,03-17 07:10:46.955  1022  1667 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:46.955  1022  1667 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 07:10:46.955  1022  1667 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:46.955  2141  4905 W IcingInternalCorpora: getNumBytesRead when not calculated.
,03-17 07:10:46.955  4388  4417 I AMMetaDataParserService: Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,03-17 07:10:46.965  1880  2157 W GCoreFlp: No location to return for getLastLocation()
,03-17 07:10:46.965  1880  4911 W FusedLocationProvider: location=null
,03-17 07:10:46.965  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.UsbDeviceActivity
03-17 07:10:46.965  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:46.965  4388  4417 I AMMetaDataParserService: getResourcePackageName:android.hardware.usb.action.USB_DEVICE_ATTACHED
03-17 07:10:46.965  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.Wallpaper
03-17 07:10:46.965  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:46.965  4388  4417 I AMMetaDataParserService: getResourcePackageName:android.wallpaper.preview
03-17 07:10:46.965  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.LockScreen
03-17 07:10:46.965  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:46.965  4388  4417 I AMMetaDataParserService: getResourcePackageName:android.wallpaper.preview
03-17 07:10:46.965  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.BothScreen
03-17 07:10:46.965  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:46.965  4388  4417 I AMMetaDataParserService: getResourcePackageName:android.wallpaper.preview
03-17 07:10:46.965  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.CropImage
03-17 07:10:46.965  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.ContextualTagSetting
03-17 07:10:46.965  4388  4417 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
03-17 07:10:46.965  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.ContextualTagWeatherSetting
03-17 07:10:46.965  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.samsung.gallery.view.gallerysearch.DeleteHistoryForGallerySearchActivity
03-17 07:10:46.965  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.samsung.gallery.view.usertag.AddUserTagListActivity
03-17 07:10:46.965  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.samsung.gallery.view.detailview.moreinfo.MoreInfoLocationEditActivity
03-17 07:10:46.965  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:46.965  4388  4417 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
03-17 07:10:46.965  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.settings.GallerySettings
03-17 07:10:46.965  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetTypeChooser
03-17 07:10:46.965  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetClickHandler
03-17 07:10:46.965  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetConfigure
03-17 07:10:46.965  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.MagazineWidgetConfigure
03-17 07:10:46.965  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.EasyWidgetConfigure
03-17 07:10:46.965  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetPreferenceActivity
03-17 07:10:46.965  4388  4417 I AMMetaDataParserService: Resource data:Loop for running acti,vitycom.sec.android.gallery3d.gadget.MagazineWidgetPreferenceActivity
03-17 07:10:46.965  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.settings.AccountSettingActivity
03-17 07:10:46.965  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.settings.FilterbySettingActivity
03-17 07:10:46.965  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.sec.gallery2d.viewstate.MapView2dPage
03-17 07:10:46.965  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.samsung.gallery.app.imagenote.ImageNote
03-17 07:10:46.965  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.samsung.gallery.app.photonote.PhotoNote
03-17 07:10:46.965  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.samsung.gallery.controller.StartMmsSaveCmd$CallMmsSave
03-17 07:10:46.965  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.samsung.gallery.controller.GalleryChooserActivity
03-17 07:10:46.965  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.cloud.integrator.CloudIntegratorActivity
,03-17 07:10:46.965  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.camera.Camera
03-17 07:10:46.965  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:46.965  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.samsung.android.cocktail.subwindow.enable
03-17 07:10:46.965  1022  1520 I splitIntent: intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
03-17 07:10:46.965  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.sec.android.multiwindow.activity.STYLE
03-17 07:10:46.965  1022  1520 I splitIntent: base  index=1, name=com.google.android.gms com.google.android.gms.wearable.service.AutoStarterReceiver
03-17 07:10:46.965  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.keyguard.layout
03-17 07:10:46.965  1022  1520 I splitIntent: other index=4, name=com.google.android.gms com.google.android.gms.init.InitializeGmsReceiver
03-17 07:10:46.965  4388  4417 I AMMetaDataParserService: getResourcePackageName:assistant
03-17 07:10:46.965  4388  4417 I AMMetaDataParserService: Resource data:2131099648
,03-17 07:10:46.975  1022  1520 I splitIntent: arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,03-17 07:10:46.975  1022  1520 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:46.975  1022  1520 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 07:10:46.975  1022  1520 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:46.975  4388  4417 W ResourcesManager: Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
03-17 07:10:46.975  4388  4417 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-17 07:10:46.975  4388  4417 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
03-17 07:10:46.975  4388  4417 W ResourcesManager: Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
03-17 07:10:46.975  4388  4417 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,03-17 07:10:46.975  4388  4417 I AMMetaDataParserService: getResourceName:com.sec.android.app.camera:xml/assistant
03-17 07:10:46.975  4388  4417 I AMMetaDataParserService: getResourceTypeNamexml
,03-17 07:10:46.985  1022  1520 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:46.985  1022  1520 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 07:10:46.985  1022  1520 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:46.985  1022  1392 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:46.985  1022  1392 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 07:10:46.985  1022  1392 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:46.995  1022  1520 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:46.995  1022  1520 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 07:10:46.995  1022  1520 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:46.995  4388  4417 I AMMetaDataParserService: Icon data: ResourceSwitch camera2131559034android.intent.action.switchcamera2130837512
,03-17 07:10:46.995  1880  4923 E MDM     : [245] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,03-17 07:10:46.995  1022  1597 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:46.995  1022  1597 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 07:10:46.995  1022  1597 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:47.005  1022  1129 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:47.005  1022  1129 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 07:10:47.005  1022  1129 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:47.005  1022  1507 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:47.005  1022  1507 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 07:10:47.005  1022  1507 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:47.015  4388  4417 I AMMetaDataParserService: Icon data: ResourceGallery2131558741android.intent.action.switchgallery2130837511
,03-17 07:10:47.025  1022  1667 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:47.025  1022  1667 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 07:10:47.025  1022  1667 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:47.025  2141  4924 D LocationInitializer: Restart initialization of location
,03-17 07:10:47.025  1022  1507 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:47.025  1022  1507 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-17 07:10:47.025  1022  1507 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:47.025  1880  1880 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,03-17 07:10:47.025  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.camera.Camcorder
03-17 07:10:47.025  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.camera.DummyActivity
03-17 07:10:47.025  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.camera.CropImage
03-17 07:10:47.025  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.shootingmodemanager.ManageShootingModeActivity
,03-17 07:10:47.035  4388  4417 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
,03-17 07:10:47.035  1022  1507 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:47.035  1022  1507 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 07:10:47.035  1022  1507 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:47.045  1022  1392 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:47.045  1022  1392 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 07:10:47.045  1022  1392 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:47.045  1022  1404 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:47.045  1022  1404 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-17 07:10:47.055  1022  1404 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:47.055   288   288 E SMD     : DCD OFF,
,03-17 07:10:47.055  1022  1321 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:47.055  1022  1321 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 07:10:47.055  1022  1321 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:47.065  1880  1880 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 07:10:47.065  1022  1129 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:47.065  1022  1129 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 07:10:47.065  1022  1129 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:47.065  1022  1034 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:47.075  1022  1034 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 07:10:47.075  1022  1034 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:47.075  1022  1392 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:47.075  1022  1392 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:47.075  1022  1392 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.contacts, destAppInfo.processName = com.android.contacts
,03-17 07:10:47.115  1022  1667 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:47.115  1022  1667 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:47.115  1022  1667 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.contacts, destAppInfo.processName = com.android.contacts
,03-17 07:10:47.115  1022  1404 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:47.115  1022  1404 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:47.115  1022  1404 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:47.115  1022  1404 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:47.125  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.GridSettings
03-17 07:10:47.125  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.125  4388  4417 I AMMetaDataParserService: getResourcePackageName:assistant
03-17 07:10:47.125  4388  4417 I AMMetaDataParserService: Resource data:2131165220
,03-17 07:10:47.125  4388  4417 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
03-17 07:10:47.125  4388  4417 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
03-17 07:10:47.125  4388  4417 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-17 07:10:47.125  4388  4417 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-17 07:10:47.125  4388  4417 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 07:10:47.125  4388  4417 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,03-17 07:10:47.125  4928  4928 E Zygote  : MountEmulatedStorage()
03-17 07:10:47.125  4928  4928 E Zygote  : v2
03-17 07:10:47.125  4928  4928 I libpersona: KNOX_SDCARD checking this for 10041
03-17 07:10:47.125  4928  4928 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:47.135  4928  4928 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 07:10:47.135  4928  4928 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 07:10:47.135  1022  1404 I ActivityManager: Start proc com.android.mms for broadcast com.android.mms/.widget.MmsWidgetProvider: pid=4928 uid=10041 gids={50041, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
03-17 07:10:47.135  4928  4928 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
03-17 07:10:47.135  4388  4417 I AMMetaDataParserService: getResourceName:com.android.settings:xml/assistant
03-17 07:10:47.135  4388  4417 I AMMetaDataParserService: getResourceTypeNamexml
,03-17 07:10:47.135  3693  3744 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 7 sec
,03-17 07:10:47.145  4388  4417 I AMMetaDataParserService: Icon data: ResourceSearch2131363517com.android.settings.Search2130837580
,03-17 07:10:47.155  1880  2156 I art     : Explicit concurrent mark sweep GC freed 24901(1825KB) AllocSpace objects, 29(464KB) LOS objects, 39% free, 9MB/16MB, paused 1.362ms total 72.455ms
,03-17 07:10:47.165  4928  4928 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:47.165  4928  4928 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:47.165  4388  4417 I AMMetaDataParserService: Icon data: ResourceEdit quick settings2131361852com.android.settings.Favorite2130837579
,03-17 07:10:47.175  1880  2157 W GCoreFlp: No location to return for getLastLocation()
,03-17 07:10:47.175  1880  4925 W FusedLocationProvider: location=null
,03-17 07:10:47.185  4928  4928 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SubSettings
03-17 07:10:47.185  4928  4928 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.LabelName
03-17 07:10:47.185  4928  4928 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Password
03-17 07:10:47.185  4928  4928 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$EthernetSettingsActivity
03-17 07:10:47.185  4928  4928 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$WirelessSettingsActivity
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$WifiSettingsActivity
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiSettings
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiPickerActivity
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiSecPickerActivity
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiCaptiveActivity
,03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.FreeWifiScanPickerDialog
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiWarningDialog
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiOffloadDialog
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiAdvancedSecSetupActivity
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WificmccSetupActivity
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiSecSetupActivity
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiWarningDialog
,03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiSetupActivity
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.accessibility.smartscroll.app.sbrowsertry.SmartScreenActivity
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiPickerDialog
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiSettingsForSetupWizardXL
,03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AdvancedWifiSettingsActivity,
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SavedAccessPointsSettingsActivity
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$WifiShareProfileActivity
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiInfo
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiConfigInfo
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiAPITest
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiStatusTest
,03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApSettings
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApWarning
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApTestConfigure
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiPoorConnection
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiHiddenApListActivity
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiHiddenApDeleteActivity
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiDisconnectWeakApSettings
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ApnSettingsActivity
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$BluetoothSettingsActivity
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothSettings
,03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothScanDialog
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothErrorActivity
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.CheckBluetoothStateActivity
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.DevicePickerActivity
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothEnableActivity
,03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothEnablingActivity
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$MirrorLinkActivity
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$TetherSettingsActivity
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.samsung.android.multiuser.install_only_owner
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.TetherSettings
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.samsung.android.multiuser.install_only_owner
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$WifiP2pSettingsActivity
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
,03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.p2p.WifiP2pSettings
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$WifiP2pHelpActivity
,03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.p2p.WifiP2pDummyPickerActivity
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$NearbySettingsActivity
,03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.nearby.NearbySettings
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wfd.WfdHelpActivity
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wfd.WfdPickerDialog
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$VpnSettingsActivity
,03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DateTimeSettingsActivity
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.DateTimeSettingsSetupWizard
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.FeatureSettingsSetupWizard
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$LocalePickerActivity
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
,03-17 07:10:47.195  4388  4417 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$InputMethodAndLanguageSettingsActivity
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$VoiceInputSettingsActivity
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$HandwritingLanguageActivity
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.handwritingsearch.HandwritingLanguageTablet
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$KeyboardLayoutPickerActivity
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.LanguageSettings
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SpellCheckersSettingsActivity
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.inputmethod.InputMethodAndSubtypeEnablerActivity
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$UserDictionarySettingsActivity
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.inputmethod.UserDictionaryAddWordActivity
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.UserDictionarySettings
,03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ZenModeSettingsActivity
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ZenModeDNDSettingsActivity
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$HomeSettingsActivity
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.HomeSettings
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$LockScreenSettingsActivity
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DisplaySettingsActivity
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.DisplaySettings
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$LockscreenMenuActivity
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$BlockSettingsActivity
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$LedIndicatorSettingsActivity
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DockSettingsActivity
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.DockSettings
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ContextualPageSettings
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ContextualPageHelpActivity
,03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DeviceInfoSettingsActivity
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.DeviceNameDialog
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SettingsLicenseActivity
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
,03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.PrivacyAlertDialogActivity
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.PrivacyAlertProceedDialogActivity
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SettingsSafetyLegalActivity
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
,03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ManageApplicationsActivity
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.applications.ManageApplications
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ManageApplications
,03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.RunningServices
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.LaunchApplication
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.applications.StorageUse
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.applications.InstalledAppDetailsTop
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.accounts.ManageAccountsActivity
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.applications.InstalledAppDetails
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.applications.UninstallMultipleScreen
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$RunningServicesActivity
,03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$StorageUseActivity
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$NotificationStationActivity
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AppOpsDetailsActivity
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$LocationSettingsActivity
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SecuritySettingsActivity
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.MonitoringCertInfoActivity
,03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$TrustedCredentialsSettingsActivity
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SecuritySettings
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PrivacySettingsActivity
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SetFullBackupPassword
,03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.CredentialStorage
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DeviceAdminSettingsActivity
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.DeviceAdminSettings
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.DeviceAdminAdd
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$UsageAccessSettingsActivity
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:47.185  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SetProfileOwner
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.IccLockSettings
,03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SimPinLockSettings
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SimPersoLockSettings
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AccessibilitySettingsActivity
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AccessibilityDaltonizerSettingsActivity
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
,03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.settings.accessibility.AccessibilityWidgetDialogActivity
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$CaptioningSettingsActivity
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$MagnifierSettingsActivity
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AssistantMenuPreferenceFragmentActivity
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.AccessibilitySettingsSetupWizard
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$TextToSpeechSettingsActivity
,03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DrivingModeSettingsActivity
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AssistiveHepticSettingsActivity
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ConfirmDeviceCredentialActivity
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.notification.RedactionInterstitial
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.notification.RedactionSettingsStandalone
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ConfirmLockPattern
,03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ConfirmLockPassword
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ConfirmLockEnterpriseIdentity
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockEnterpriseIdentity
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ConfirmLockPattern$InternalActivity
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ConfirmLockPassword$InternalActivity
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.BluetoothPairingWithCac
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockGeneric
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockGeneric$InternalActivity
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.KnoxChooseLockTwoFactor
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.KnoxChooseLockBackupPin
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockPattern
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockBLock
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockPassword
,03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockMotion
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockAdditionalPin
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockSignature
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.EncryptionInterstitial
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.deviceinfo.Status
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$StorageSettingsActivity
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.deviceinfo.MiscFilesHandler
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.deviceinfo.DeviceInfoTabActivity
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ApnEditor
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.MediaFormat
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.MediaFormatSd
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$QuickLaunchSettingsActivity
,03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.quicklaunch.BookmarkPicker
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DevelopmentSettingsActivity
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PrintSettingsActivity
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PrintJobSettingsActivity
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.DevelopmentSettings
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.AppPicker
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$UsbSettingsActivity
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.UsbSettings
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothPairingDialog
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.RequestPermissionActivity
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiScanModeActivity
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.RequestPermissionHelperActivity
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothPermissionActivity
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ActivityPicker
,03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$NfcSettingsActivity
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.nfc.NfcAdvancedRoutingSetting
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AndroidBeamSettingsActivity
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
,03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SBeamSettingsActivity
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$WifiDisplaySettingsActivity
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.BatteryInfo
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Display
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.RadioInfo
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ProxySelector
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.BandMode
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.TestingSettings
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.fulllocalepickertest.FullLocalePickerTest
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.AppWidgetPickActivity
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.AllowBindAppWidgetActivity
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.UsageStatsActivity
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PowerUsageSummaryActivity
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.fuelgauge.PowerUsageSummary
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$BatterySaverSettingsActivity
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:47.195  4388  ,4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AccountMenuActivity
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AccountSettingsActivity
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AccountSyncSettingsActivity
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.accounts.AddAccountSettings
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.accounts.ChooseAccountActivity
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.CryptKeeper
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.CryptKeeper$FadeToBlack
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.CryptKeeperConfirm$Blank
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.CryptDecryptConfirm$Blank
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$CryptKeeperSettingsActivity
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$CryptDecryptSettingsActivity
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activ,itycom.android.settings.Settings$CryptSDCardSettingsActivity
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SimChangeAlertSettingsActivity
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DataUsageSummaryActivity
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DataUsageMeteredSettingsActivity
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DreamSettingsActivity
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$UserSettingsActivity
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PaymentSettingsActivity
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.nfc.PaymentDefaultDialog
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SmsDefaultDialog
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ActiveNetworkScorerDialog
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$NotificationAccessSettingsActivity
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ConditionProviderSettingsActivity
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$NotificationSettingsActivity
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SoundSettingsActivity
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SoundSettings
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$OtherSoundSettingsActivity
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$NotificationAppListActivity
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AppNotificationSettingsActivity
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SimSettingsActivity
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.FactoryResetDialog
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.LockScreenWallpaper
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$WallpaperSettingsActivity
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.GSensorSettings
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingModeSettingsActivity
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingMode2014Activity
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingModeSettings2014Activity
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$UltraPowerSavingModeActivity
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ModePreviewTablet
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ModePreviewDialog
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.InkeffectPreview
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.InkeffectPreviewTablet
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ModePreview
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.NewModePreview
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SViewColor
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SViewColor2014
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SViewStyleClock
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SViewMiniWallpaper
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SViewCoverEdgeSettingsActivity
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockFaceWarning
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PowerSettingsActivity
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.RecommendRingtoneDialog
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SelectInfoCoverSettingsActivity
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SelectItemDisplay
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.sec.android.sdk.cover.MODE
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$WeatherSettingsFragmentActivity
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SViewCoverPopup
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.sec.android.sdk.cover.MODE
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.WarrantyLegal
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SamsungLegalTablet
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.PenDetachmentOption
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PenDetachmentOptionActivity
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.NotificationPanelMenu
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$NotificationPanelMenuActivity
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.NotificationPanelSettings
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$MotionSettingsActivity
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AirMotionSettingActivity
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SMotionGuideHub2014Activity
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$FingerAirViewSettingActivity
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$FingerAirViewHelpSettingActivity
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PenAirViewHelpSettingActivity
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AirViewSettingActivity
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$MouseHoveringSettingsActivity
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SoftwareUpdateSettingActivity
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.PenHelpActivity
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PenHelpFragmentActivity
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DirectPenInputSettingsActivity
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PenAirViewSettingsMenuActivity
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PenSettingsMenuActivity
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.PhoneVibration
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.OneHandHelp
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.OneHandAdaptiveHelp
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$OneHandSideSoftKeyFragmentActivity
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalvibration.PersonalVibration
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalvibration.SelectPatternDialog
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.LockScreenShortcutSettings
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.AppList
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.ExpandAppList
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ReadingModeSettingsActivity
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.customizablekey.CustomizableKeySettings
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$CustomizableKeySettingsActivity
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.customizablekey.AppList
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DualClockSettingActivity
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$RecommendedAppsMenuActivity
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$RecommendedAppsListActivity
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SettingsReceiverActivity
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SelectPenDetachNotiDialog
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SecurityWarningDialog
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PersonalPageSettingsActivity
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageSettings
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.PersonalPageDisclaimer
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageAutoModeSwitchAlertDialogActivity
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorial
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialDisclaimerActivity
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialAppActivity
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialAddActivity
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockPattern
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockPassword
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockAdditionalPin
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageConfirmLockPattern
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageConfirmLockPassword
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$EasyModeSettingsActivity
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$EasyModeActivity
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$EasyModeAppActivity
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.,settings.TOP_LEVEL_HEADER_ID
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$MyPlaceSettingsActivity
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$MyPlaceProfileSettingsActivity
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PlaceSettingsActivity
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.myplace.SelectMapActivity
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$GlobalRoamingSettingsActivity
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$TRoamingSettingsActivity
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.flipfont.FontListActivity
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.flipfont.FontListProgressActivity
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$BackupAssistantPlusSettingsActivity
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.myprofile.MyProfileActivity
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.MagazineCard
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ClockWidgetActivity
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.myprofile.PersonalMessage
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$CloudSettingActivity
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ShortCameraMenu
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ClockMyprofileMenu
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ClockMyprofileMenuTablet
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$LaunchCameraSettingsActivity
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SmartScreenSettingsActivity
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SmartBondingSettingsActivity
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ToolboxMenuActivity
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ToolboxListActivity
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SmartScrollAdvancedSettingsActivity
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$MultiWindowSettingsActivity
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.MultiWindowSettings
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.settingssearch.SettingsSearchActivity
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SearchActivity
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ColorChipReportActivity
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DirectAccessActivity
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$NotificationReminderActivity
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$VoiceInputControlSettingsActivity
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.PreloadAppUpdate
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.PreloadAppUpdateList
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.activekey.ActiveKeySettings
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ActiveKeySettingsActivity
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.activekey.AppList
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DisplaySettingsTab
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.SETTING_HEADER_ID
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$InputAndControlSettingsTab
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.SETTING_HEADER_ID
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$GeneralSettingsTab
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.SETTING_HEADER_ID
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.DeviceHealthActivity
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SettingsEmergencyActivity
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareSettingsActivity
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareEmergencyModeActivity
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareDisasterActivity
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareDisclaimerActivity
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareDisasterDisclaimerActivity
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareCoverageDialog
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AirplaneModeSettingsActivity
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ToddlerModeSettingsActivity
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.favorite.FavoriteMenuList
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$FestivalEffectSettingsActivity
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.powersavingmode.PowerNotiDialog
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.powersavingmode.PowerNotiDataDialog
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.SetupWizardWifiScreen
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.CaptivePortalWebViewActivity
03-17 07:10:47.195  4388  4417 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.KnoxActiveProtectionEulaActivity
03-17 07:10:47.245  4928  4928 D Mms/MmsApp: [start]    onCreate() consume time = 0.0
03-17 07:10:47.295  1022  1022 I ValidateNoPeople: mEvictionCount: 0
,03-17 07:10:47.375  4928  4928 W art     : Verification of com.android.mms.ui.MsgSweepActionListView com.android.mms.ArtClassLoader.createMsgSweepActionList(android.content.Context) took 115.263ms
,03-17 07:10:47.445  4928  4944 D Mms/ArtClassLoader: init before art
03-17 07:10:47.445  4928  4928 D Mms/TelephonyPermission: start operation mode monitor
,03-17 07:10:47.455  4928  4928 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-17 07:10:47.465  4928  4928 D Mms/TelephonyPermission: DefaultSmsApp is com.android.mms
03-17 07:10:47.465  4928  4928 D Mms/TelephonyPermission: isDefault true
,03-17 07:10:47.465  4928  4928 D Mms/MmsApp: onCreate() com.android.mms
,03-17 07:10:47.485  4928  4928 D Mms/MmsApp: [start]    initCountryIso consume time = 234.304896
,03-17 07:10:47.485  1022  1667 D CountryDetector: The first listener is added
,03-17 07:10:47.495  4928  4928 D Mms/MmsApp: [end]    initCountryIso consume time = 7.576458
,03-17 07:10:47.495  4928  4928 D Mms/MmsConfig: [start]    MmsConfig.init() consume time = 0.440104
,03-17 07:10:47.495  4928  4928 D Mms/MmsConfig: before partial update
,03-17 07:10:47.515  4928  4928 D Mms/MmsConfig: Load Resize quality : 80
,03-17 07:10:47.515  4928  4928 D EasySignUpManager_1.0.1: serviceId : 1, features : -1
,03-17 07:10:47.515  4928  4928 D EasySignUpManager_1.0.1: isAuth is false
,03-17 07:10:47.515  4928  4928 D Mms/MmsConfig: setFreeMessageEnabled, getSupportedFeatures = -1 isAuth = false
,03-17 07:10:47.515  1485  1807 D TP/MmsSmsProvider: query,matched:2117, calling pid = 4928
,03-17 07:10:47.525  1485  1807 D TP/MmsSmsProvider: match 2117:Elapsed time : 1.632 ms
,03-17 07:10:47.525  4928  4928 D EasySignUpManager_1.0.1: isAuth is false
,03-17 07:10:47.525  4928  4928 D EasySignUpManager_1.0.1: getServiceStatus : serviceId (1) is OFF
,03-17 07:10:47.525  4928  4928 E CscParser: mps_code.dat does not exist
,03-17 07:10:47.525  4928  4928 E CscParser: customer_path =/system/csc/customer.xml
,03-17 07:10:47.525  4928  4928 E CscParser: fileName + /system/csc/customer.xml
,03-17 07:10:47.535  4928  4928 E CscParser: mps_code.dat does not exist
03-17 07:10:47.535  4928  4928 E CscParser: customer_path =/system/csc/customer.xml
03-17 07:10:47.535  4928  4928 E CscParser: fileName + /system/csc/customer.xml
,03-17 07:10:47.545  4928  4928 D CscParser: getInstance fileName =/system/csc/customer.xml
,03-17 07:10:47.545  4928  4928 D Mms/MmsConfig:  enable multiwindow = false
,03-17 07:10:47.555  4928  4928 E Mms/MessageUtils: setCountryDetector : update country detector info 
03-17 07:10:47.555  4928  4928 E Mms/MessageUtils: updateCountryIso : update country iso info 
,03-17 07:10:47.565  4928  4928 D Mms/MmsConfig: [end]    init() consume time = 71.969948
,03-17 07:10:47.565  4928  4928 D Mms/Contact: [start]    init() consume time = 0.811094
,03-17 07:10:47.575  1485  1716 D TP/MmsSmsProvider: query,matched:13, calling pid = 4928
,03-17 07:10:47.575  1485  1716 D TP/MmsSmsProvider: match 13:Elapsed time : 1.623 ms
,03-17 07:10:47.575  4928  4928 D Mms/Contact: [end]    init consume time = 12.42375
,03-17 07:10:47.585  4928  4928 D Mms/MethodReflector: getSubId is called
,03-17 07:10:47.585  4928  4928 D Mms/TelephonyUtils: getLongSubId from simSlot 0, return Value = -1
,03-17 07:10:47.585  4928  4928 D Mms/MethodReflector: getTelephonyProperty is called
,03-17 07:10:47.585  4928  4928 D Mms/DownloadManager: roaming -> false (slotId = 0)
,03-17 07:10:47.585  4928  4928 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 0
03-17 07:10:47.585  4928  4928 D Mms/DownloadManager: auto download without roaming -> true
03-17 07:10:47.585  4928  4928 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAuto : true, roaming : false
03-17 07:10:47.585  4928  4928 D Mms/MethodReflector: getSubId is called
,03-17 07:10:47.585  4928  4928 D Mms/MethodReflector: getDefaultSmsSubId is called
03-17 07:10:47.585  4928  4928 E Mms/TelephonyUtils: subID is null or 0 length, so get DefaultSubId!!
03-17 07:10:47.585  4928  4928 D Mms/TelephonyUtils: getLongSubId from simSlot 1, return Value = -1000
03-17 07:10:47.585  4928  4928 D Mms/MethodReflector: getTelephonyProperty is called
03-17 07:10:47.585  4928  4928 D Mms/DownloadManager: roaming -> false (slotId = 1)
03-17 07:10:47.585  4928  4928 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 1
03-17 07:10:47.585  4928  4928 D Mms/DownloadManager: auto download without roaming -> true
03-17 07:10:47.585  4928  4928 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
03-17 07:10:47.585  4928  4928 D Mms/DownloadManager: auto download during roaming secondary -> false
03-17 07:10:47.585  4928  4928 D Mms/DownloadManager: mAutoDownload ------> true
,03-17 07:10:47.605  4928  4950 D Mms/DraftCache: [start]    rebuildCache consume time = 24.710208
,03-17 07:10:47.615  1485  1505 D TP/MmsSmsProvider: query,matched:12, calling pid = 4928
,03-17 07:10:47.615  1485  1505 D TP/MmsSmsProvider: match 12:Elapsed time : 1.762 ms
03-17 07:10:47.615  4928  4928 D ComposerPerformance: 1458195047627 ms / [DONE] Composer constructor
,03-17 07:10:47.615  4928  4928 E CII     : CommonIMSInterface: VoLTE CSC feature disabled.
,03-17 07:10:47.625  4928  4928 I Mms/ReservationManager: ReservationManager()
03-17 07:10:47.625  4928  4928 I Mms/ReservationManager: resetAfterConnected()
,03-17 07:10:47.625  4928  4950 D Mms/DraftCache: [end]    rebuildCache consume time = 21.064323
,03-17 07:10:47.625  1485  1500 D TP/MmsSmsProvider: query,matched:7, calling pid = 4928
,03-17 07:10:47.625  1485  1500 D TP/MmsSmsProvider: match 7:Elapsed time : 3.172 ms
,03-17 07:10:47.635  4928  4952 D Mms/Conversation: [start]    init() consume time = 8.86224
,03-17 07:10:47.635  1485  1807 D TP/MmsSmsProvider: deleteConversation threadId: 9223372036854775807
03-17 07:10:47.635  4928  4928 I Mms/ReservationManager: getReservedSendMessageCount(): retMessageCount=0
,03-17 07:10:47.635  1485  1807 D TP/MmsSmsProvider: delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
,03-17 07:10:47.635  1485  1807 V TP/MmsSmsDatabaseHelper: updateThread(), thread_id = 9223372036854775807
,03-17 07:10:47.635  1485  1807 V TP/MmsSmsDatabaseHelper: sUpgradeVersion = 0, db.getVersion() = 81
,03-17 07:10:47.645  4928  4928 D Mms/MmsApp: [end]    onCreate() consume time = 10.544583
,03-17 07:10:47.645  1485  1807 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
,03-17 07:10:47.645  1485  1807 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
,03-17 07:10:47.645  1485  1807 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-17 07:10:47.645  1485  1807 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-17 07:10:47.645  1485  1807 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-17 07:10:47.645  1485  1807 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
,03-17 07:10:47.655  4928  4928 D Mms/DownloadManager: Service state changed: Bundle[mParcelledData.dataSize=744]
,03-17 07:10:47.655  4928  4928 D Mms/DownloadManager: roaming ------> false, mSimSlot = 0
,03-17 07:10:47.655  4928  4928 D Mms/MethodReflector: getSubId is called
03-17 07:10:47.655  4928  4928 D Mms/TelephonyUtils: getLongSubId from simSlot 0, return Value = -1
03-17 07:10:47.655  1485  1807 D TP/MmsSmsProvider: delete threadId: 9223372036854775807
03-17 07:10:47.655  1485  1807 D TP/MmsSmsProvider: need read changed broadcast:false
,03-17 07:10:47.655  4928  4928 D Mms/MethodReflector: getTelephonyProperty is called
03-17 07:10:47.655  4928  4928 D Mms/DownloadManager: roaming -> false (slotId = 0)
03-17 07:10:47.655  4928  4928 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 0
03-17 07:10:47.655  4928  4928 D Mms/DownloadManager: auto download without roaming -> true
03-17 07:10:47.655  4928  4928 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAuto : true, roaming : false
03-17 07:10:47.655  4928  4928 D Mms/DownloadManager: mAutoDownload ------> true
,03-17 07:10:47.655  1022  1520 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:47.655  1022  1520 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-17 07:10:47.655  1022  1520 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:47.655  1022  1520 I ActivityManager: Killing 4232:com.android.managedprovisioning/u0a20 (adj 15): empty #31
,03-17 07:10:47.675  4928  4952 D Mms/Conversation: [end]    init consume time = 32.62625
,03-17 07:10:47.675  4928  4952 D Mms/MessagingNotification: [start]    init() consume time = 1.249271
,03-17 07:10:47.675  4928  4952 D Mms/MessagingNotification: [end]    init consume time = 3.215781
,03-17 07:10:47.685  1022  1044 D SensorService: [SO] -0.479 0.192 9.902
,03-17 07:10:47.685  1485  1716 D TP/MmsSmsProvider: query,matched:0, calling pid = 4928
03-17 07:10:47.685  1485  1716 V TP/MmsSmsProvider: getSimpleConversations entered.
,03-17 07:10:47.685  1485  1716 D TP/MmsSmsProvider: match 0:Elapsed time : 1.213 ms
,03-17 07:10:47.685  4928  4953 D Mms/SpamFilter: [start]    SpamFilter fill() begin consume time = 7.149063
,03-17 07:10:47.725  1022  1046 W libprocessgroup: failed to open /acct/uid_10020/pid_4232/cgroup.procs: No such file or directory
,03-17 07:10:47.735  4928  4954 D Mms/Synchronizer: [start]    doSync consume time = 46.018125
,03-17 07:10:47.735  1471  1471 I HomeSyncInstallReceiver: This pkg do not need BT addr. Do nothing
,03-17 07:10:47.735  1022  1035 I splitIntent: Split this intent : android.intent.action.PACKAGE_ADDED, mSplitNum[0]=12, mSplitNum[1]=22, mSplitNum[2]=32, mBgSplitQueueNum=3 divideNum= 9 r.nextReceiver= 2 receivers.size=41
03-17 07:10:47.735  1022  1035 I splitIntent: finish to split intent : android.intent.action.PACKAGE_ADDED !! Enqueue -> schedule it!!
,03-17 07:10:47.735  1022  1035 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:47.735  1022  1035 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:47.735  1022  1035 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:47.735  1022  1035 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:47.735  1485  1505 D TP/MmsSmsProvider: update, matched:300, calling pid = 4928
03-17 07:10:47.735  1485  1505 V TP/MmsSmsProvider: syncDBData start
,03-17 07:10:47.745  1485  1505 V TP/MmsSmsProvider: syncDBData sms end
,03-17 07:10:47.745  1485  1505 V TP/MmsSmsProvider: syncDBData mms end
,03-17 07:10:47.745  1485  1505 V TP/MmsSmsProvider: syncDBData end
,03-17 07:10:47.745  1022  1100 V AlarmManager: waitForAlarm result :4
,03-17 07:10:47.745  4956  4956 E Zygote  : MountEmulatedStorage()
03-17 07:10:47.755  4956  4956 E Zygote  : v2
,03-17 07:10:47.755  4956  4956 I libpersona: KNOX_SDCARD checking this for 10014
,03-17 07:10:47.755  4956  4956 I libpersona: KNOX_SDCARD not a persona
03-17 07:10:47.755  4956  4956 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 07:10:47.755  4956  4956 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 07:10:47.755  4956  4956 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-17 07:10:47.765  1022  1035 I ActivityManager: Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver: pid=4956 uid=10014 gids={50014, 9997, 3003} abi=armeabi-v7a
,03-17 07:10:47.765  1022  1047 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:47.765  1022  1047 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:47.765  1022  1047 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:47.765  1022  1047 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:47.765  4928  4944 D Mms/ArtClassLoader: init [DONE] art
,03-17 07:10:47.775  4971  4971 E Zygote  : MountEmulatedStorage(),
03-17 07:10:47.775  4971  4971 E Zygote  : v2
03-17 07:10:47.785  4971  4971 I libpersona: KNOX_SDCARD checking this for 10039
03-17 07:10:47.785  4971  4971 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:47.785  4971  4971 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 07:10:47.785  4971  4971 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 07:10:47.785  4956  4956 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 07:10:47.785  4971  4971 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
03-17 07:10:47.785  4956  4956 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:47.785  1022  1047 I ActivityManager: Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=4971 uid=10039 gids={50039, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,03-17 07:10:47.805  1022  1047 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:47.805  1022  1047 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:47.805  1022  1047 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:47.805  1022  1047 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:47.815  4986  4986 E Zygote  : MountEmulatedStorage()
03-17 07:10:47.815  4986  4986 I libpersona: KNOX_SDCARD checking this for 10087
03-17 07:10:47.815  4986  4986 E Zygote  : v2
03-17 07:10:47.815  4986  4986 I libpersona: KNOX_SDCARD not a persona
03-17 07:10:47.815  4986  4986 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 07:10:47.815  1022  1047 I ActivityManager: Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4986 uid=10087 gids={50087, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-17 07:10:47.825  4986  4986 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 07:10:47.825  4986  4986 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-17 07:10:47.825  4971  4971 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:47.825  4971  4971 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:47.835  1022  1100 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:47.835  1022  1100 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:47.835  1022  1100 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:47.835  1022  1100 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:47.845  5000  5000 E Zygote  : MountEmulatedStorage(),
,03-17 07:10:47.845  5000  5000 I libpersona: KNOX_SDCARD checking this for 10117
03-17 07:10:47.845  5000  5000 E Zygote  : v2
03-17 07:10:47.845  5000  5000 I libpersona: KNOX_SDCARD not a persona
03-17 07:10:47.845  5000  5000 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 07:10:47.855  5000  5000 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
03-17 07:10:47.855  1022  1100 I ActivityManager: Start proc com.google.android.apps.plus for service com.google.android.apps.plus/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService: pid=5000 uid=10117 gids={50117, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
03-17 07:10:47.855  5000  5000 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-17 07:10:47.865  4986  4986 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 07:10:47.865  1485  1500 D TP/MmsSmsProvider: query,matched:400, calling pid = 4928
03-17 07:10:47.865  4986  4986 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:47.865  4928  4952 D Mms/MessagingNotification: checkBadgeCount unreadCount=0 badgeCount=0
,03-17 07:10:47.875  5000  5000 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:47.875  5000  5000 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:47.885  4928  4954 D Mms/Synchronizer: [end]    doSync consume time = 149.701197
,03-17 07:10:47.885  1485  1716 D TP/SmsProvider: query,matched:26, calling pid = 4928
,03-17 07:10:47.885  1485  1716 D TP/SmsProvider: match 26:Elapsed time : 1.260 ms
,03-17 07:10:47.895  1022  1404 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:47.895  1022  1404 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 07:10:47.895  1022  1404 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,03-17 07:10:47.895  4928  4953 D Mms/SpamFilter: [end]    SpamFilter fill() finished consume time = 13.530313
,03-17 07:10:47.895  4971  4971 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,03-17 07:10:47.895  4971  4971 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-17 07:10:47.895  5000  5000 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-17 07:10:47.895  4971  4971 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 07:10:47.895  4971  4971 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
03-17 07:10:47.895  4971  4971 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
03-17 07:10:47.895  4971  4971 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
03-17 07:10:47.895  4971  4971 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,03-17 07:10:47.905  1022  1507 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:47.905  1022  1507 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 07:10:47.905  1022  1507 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,03-17 07:10:47.915  1022  1321 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:47.915  1022  1321 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 07:10:47.915  1022  1321 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,03-17 07:10:47.925  1022  1507 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:47.925  1022  1507 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 07:10:47.925  1022  1507 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:47.935  4022  4022 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
03-17 07:10:47.935  4022  4022 I PCWCLIENTTRACE_PushUtil: sales region : global
03-17 07:10:47.935  4022  4022 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
03-17 07:10:47.935  4022  4022 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.intent.action.PACKAGE_ADDED
,03-17 07:10:47.955  1485  1500 D TP/MmsSmsProvider: query,matched:6, calling pid = 4928
,03-17 07:10:47.955  1022  1035 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:47.955  1022  1035 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:47.955  1022  1035 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:47.955  1022  1035 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:47.955  1485  1500 D TP/MmsSmsProvider: match 6:Elapsed time : 8.371 ms
,03-17 07:10:47.965  5021  5021 E Zygote  : MountEmulatedStorage()
03-17 07:10:47.965  5021  5021 E Zygote  : v2
03-17 07:10:47.965  5021  5021 I libpersona: KNOX_SDCARD checking this for 10029
03-17 07:10:47.965  5021  5021 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:47.965  5021  5021 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 07:10:47.975  4058  4058 I Finsky  : [1] com.google.android.finsky.utils.ExternalReferrer.a(4312): Package state data is missing for com.test.thalitest
03-17 07:10:47.975  5021  5021 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 07:10:47.975  5021  5021 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,03-17 07:10:47.975  1022  1035 I ActivityManager: Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=5021 uid=10029 gids={50029, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,03-17 07:10:48.005  5021  5021 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:48.005  5021  5021 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:48.075  2141  5020 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,03-17 07:10:48.075  1022  1507 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:48.075  1022  1507 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 07:10:48.075  1022  1507 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:48.085  1022  1659 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:48.085  1022  1659 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 07:10:48.085  1022  1659 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:48.085  1022  1520 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:48.085  1022  1520 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 07:10:48.085  1022  1520 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:48.095  1022  1035 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:48.095  1022  1035 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 07:10:48.095  1022  1035 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:48.095  2141  5020 D WearableController: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest,
,03-17 07:10:48.095  1022  1667 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:48.105  1022  1667 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-17 07:10:48.105  1022  1667 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:48.105  1022  1404 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:48.105  1022  1404 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 07:10:48.105  1022  1404 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:48.125  4971  4971 D NearbySource: Nearby Source Create!
,03-17 07:10:48.125  4971  4971 D NearbyContext: Nearby Context Create!
,03-17 07:10:48.145  3693  3744 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 8 sec
,03-17 07:10:48.145   256   518 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
03-17 07:10:48.145   256   518 W Vold    : Returning OperationFailed - no handler for errno 0
,03-17 07:10:48.145  4971  4971 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
,03-17 07:10:48.145  4971  4971 D SLinkSource: Samsung link source created
,03-17 07:10:48.185  4971  5040 D ContactProvider: getAllContactInfoList Start
,03-17 07:10:48.185  1022  1035 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,03-17 07:10:48.195  1022  1035 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,03-17 07:10:48.205  4971  5040 D ContactProvider: getAllContactInfoList End
,03-17 07:10:48.215  4971  5040 I syncContacts: thread: 798, sync time = 37
,03-17 07:10:48.265  4986  4986 D DocsApplication: Installing DEX configuration.,
,03-17 07:10:48.275  4986  4986 D DexInstaller: Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
,03-17 07:10:48.285  4986  4986 I PackageInfoHelper: Provided clientMode=RELEASE, packageInfo=PackageInfo{2a859f07 com.google.android.apps.docs}
,03-17 07:10:48.325  4986  4986 D TAG     : onCreate()
,03-17 07:10:48.375  4971  4971 I PackagesMonitor: PackagesMonitor onReceive :com.test.thalitest
,03-17 07:10:48.395  1022  1129 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:48.395  1022  1129 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:48.395  1022  1129 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:48.395  1022  1129 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:48.415  5044  5044 E Zygote  : MountEmulatedStorage()
,03-17 07:10:48.415  5044  5044 E Zygote  : v2
03-17 07:10:48.415  5044  5044 I libpersona: KNOX_SDCARD checking this for 10023
03-17 07:10:48.415  5044  5044 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:48.415  5044  5044 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,03-17 07:10:48.415  1022  1129 I ActivityManager: Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=5044 uid=10023 gids={50023, 9997} abi=armeabi-v7a
,03-17 07:10:48.425  4986  4986 D CrossAppStateProvider: Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer,
,03-17 07:10:48.425  5044  5044 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 07:10:48.425  5044  5044 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,03-17 07:10:48.455  5044  5044 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:48.455  5044  5044 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:48.455  5021  5051 I FeatureConfig: init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,03-17 07:10:48.465  1022  1659 I ActivityManager: Killing 4257:com.samsung.android.MtpApplication/1000 (adj 15): empty #31
,03-17 07:10:48.565  4682  4715 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,03-17 07:10:48.595  5044  5044 I OMACP   : [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
,03-17 07:10:48.665  4682  4682 I DBG_POLICYDM: [com.policydm.XSPPReceiver(53/onReceive)] ACTION_PACKAGE_ADDED. mPkgName:com.test.thalitest
,03-17 07:10:48.675  2141  2141 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.permission.PermissionUtils$1>
,03-17 07:10:48.675  1022  1046 W libprocessgroup: failed to open /acct/uid_1000/pid_4257/cgroup.procs: No such file or directory
,03-17 07:10:48.685  2141  2155 I art     : Background sticky concurrent mark sweep GC freed 14105(1121KB) AllocSpace objects, 21(336KB) LOS objects, 10% free, 10MB/11MB, paused 2.551ms total 293.742ms
,03-17 07:10:48.735  4682  4715 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] ,
03-17 07:10:48.735  4682  4715 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,03-17 07:10:48.745  4682  4715 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,03-17 07:10:48.745  4682  4715 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,03-17 07:10:48.745  4682  4715 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,03-17 07:10:48.755  1022  1034 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:48.755  1022  1034 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 07:10:48.755  1022  1034 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
03-17 07:10:48.755  4928  4952 D Mms/Omacp: checkOmacp()  old OmacpCount 0 current OmacpCount = 0
03-17 07:10:48.755  4682  4715 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,03-17 07:10:48.755  4682  4715 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,03-17 07:10:48.775  5021  5051 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,03-17 07:10:48.775  5021  5051 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-17 07:10:48.775  5021  5051 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 07:10:48.775  4742  4742 I SA      : [PMR] Received action : android.intent.action.PACKAGE_ADDED
03-17 07:10:48.775  5021  5051 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
03-17 07:10:48.775  5021  5051 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,03-17 07:10:48.775  5044  5044 I OMACP   : [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
,03-17 07:10:48.785  5044  5044 I OMACP   : [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
,03-17 07:10:48.785  5021  5051 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
03-17 07:10:48.785  5021  5051 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
03-17 07:10:48.785  5021  5051 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-17 07:10:48.785  5021  5051 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-17 07:10:48.785  5021  5051 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 07:10:48.785  5021  5051 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,03-17 07:10:48.785  5044  5044 I OMACP   : [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
,03-17 07:10:48.785  5044  5044 I OMACP   : [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
,03-17 07:10:48.785  5044  5044 I OMACP   : [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
,03-17 07:10:48.785  5044  5044 I OMACP   : [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
,03-17 07:10:48.785  5044  5044 I OMACP   : [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
,03-17 07:10:48.795  5044  5044 I OMACP   : [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
,03-17 07:10:48.795  5044  5044 I OMACP   : [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
,03-17 07:10:48.795  5044  5044 I OMACP   : [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
,03-17 07:10:48.795  5044  5044 I OMACP   : [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
,03-17 07:10:48.795  5044  5044 I OMACP   : [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
,03-17 07:10:48.795  5044  5044 I OMACP   : [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
,03-17 07:10:48.845  4742  4742 I SA      : [SUR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
,03-17 07:10:48.845  4742  4742 I SA      : [SUR] onReceive Intent=[ action.PACKAGE_ADDED. package extra.UID.:10167 extra.user_handle.:0 ]
,03-17 07:10:48.855  1022  1597 I ActivityManager: Killing 4264:com.wssnps/1000 (adj 15): empty #31
,03-17 07:10:48.865  5021  5051 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-17 07:10:48.865  5021  5051 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,03-17 07:10:48.865  5021  5051 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-17 07:10:48.875  5021  5051 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,03-17 07:10:48.875  5021  5051 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 07:10:48.875  5021  5051 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,03-17 07:10:48.885  5021  5051 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-17 07:10:48.885  5021  5051 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-17 07:10:48.885  5021  5051 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 07:10:48.885  5021  5051 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,03-17 07:10:48.885  5021  5051 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-17 07:10:48.885  5021  5051 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
03-17 07:10:48.885  5021  5051 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,03-17 07:10:48.885  5021  5051 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 07:10:48.885  5021  5051 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
03-17 07:10:48.885  5021  5051 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,03-17 07:10:48.905  5021  5051 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
03-17 07:10:48.905  5021  5051 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-17 07:10:48.905  5021  5051 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 07:10:48.905  5021  5051 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,03-17 07:10:48.915  5021  5051 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
03-17 07:10:48.915  5021  5051 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 07:10:48.915  5021  5051 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
03-17 07:10:48.915  5021  5051 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,03-17 07:10:48.925  1022  1046 W libprocessgroup: failed to open /acct/uid_1000/pid_4264/cgroup.procs: No such file or directory
,03-17 07:10:48.935  5021  5051 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
03-17 07:10:48.935  5021  5051 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-17 07:10:48.935  5021  5051 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 07:10:48.935  5021  5051 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,03-17 07:10:48.945  5021  5051 W ResourcesManager: Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,03-17 07:10:48.975  5021  5051 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
03-17 07:10:48.975  5021  5051 W ResourcesManager: Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
03-17 07:10:48.975  5021  5051 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-17 07:10:48.975  5021  5051 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 07:10:48.975  5021  5051 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,03-17 07:10:48.995  5021  5051 W ResourcesManager: Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
03-17 07:10:48.995  5021  5051 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-17 07:10:48.995  1022  1321 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:48.995  1022  1321 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-17 07:10:48.995  1022  1321 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:49.015  4928  4928 D Mms/FreeMessageStatusReceiver: onReceive, action : android.intent.action.PACKAGE_ADDED
,03-17 07:10:49.015  1022  1129 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:49.015  1022  1129 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-17 07:10:49.015  1022  1129 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
,03-17 07:10:49.025  1022  1667 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:49.025  1022  1667 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 07:10:49.025  1022  1667 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-17 07:10:49.025  5021  5051 W GalaxyFinderApplication: system/finder_cp/cpdata.xml file not found
,03-17 07:10:49.035  1022  1659 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:49.035  1022  1659 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:49.035  1022  1659 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:49.035  1022  1659 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:49.045  4928  5074 D Mms/FreeMessageReceiverService: onHandleIntent, action : android.intent.action.PACKAGE_ADDED
03-17 07:10:49.045  4928  5074 D Mms/FreeMessageReceiverService: onHandleIntent: ACTION_PACKAGE_ADDED
,03-17 07:10:49.045  5078  5078 E Zygote  : MountEmulatedStorage()
03-17 07:10:49.045  5078  5078 E Zygote  : v2
03-17 07:10:49.045  5078  5078 I libpersona: KNOX_SDCARD checking this for 10042
03-17 07:10:49.045  5078  5078 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:49.045  5078  5078 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
03-17 07:10:49.045  1022  1659 I ActivityManager: Start proc com.sec.android.app.myfiles for broadcast com.sec.android.app.myfiles/.receiver.MyFilesReceiver: pid=5078 uid=10042 gids={50042, 9997, 1028, 1015, 3003, 3002, 3001, 1023} abi=armeabi-v7a
,03-17 07:10:49.055  5078  5078 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 07:10:49.055  5078  5078 E SELinux : [DEBUG] get_category: variable seinfo: media sensitivity: NULL, cateogry: NULL
,03-17 07:10:49.055  1022  1321 I ActivityManager: Killing 4293:com.samsung.android.app.accesscontrol/1000 (adj 15): empty #31
,03-17 07:10:49.075  1022  1902 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:49.075  1022  1902 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 07:10:49.075  1022  1902 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:49.085  5078  5078 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:49.085  5078  5078 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:49.115  5078  5078 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 07:10:49.115  5078  5078 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
03-17 07:10:49.115  5078  5078 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,03-17 07:10:49.125  1022  1046 W libprocessgroup: failed to open /acct/uid_1000/pid_4293/cgroup.procs: No such file or directory
,03-17 07:10:49.145  1651  1717 I art     : Explicit concurrent mark sweep GC freed 3361(134KB) AllocSpace objects, 0(0B) LOS objects, 47% free, 4MB/8MB, paused 755us total 32.005ms
,03-17 07:10:49.155  3693  3744 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 9 sec
,03-17 07:10:49.195  2141  2141 D AsyncTaskServiceImpl: Submit a task: k
,03-17 07:10:49.195  1022  1520 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:49.195  1022  1520 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 07:10:49.195  1022  1520 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:49.215  2141  5096 D k       : Processing package: com.test.thalitest
,03-17 07:10:49.265  5078  5078 D MyFiles : MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
,03-17 07:10:49.265  1022  1129 I ActivityManager: Killing 4317:com.samsung.android.app.FileShareServer/u0a65 (adj 15): empty #31
,03-17 07:10:49.275  1022  1062 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:49.275  1022  1062 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:49.275  1022  1062 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:49.275  1022  1062 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:49.295  1022  1062 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=5098 uid=10003 gids={50003, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
03-17 07:10:49.295  5098  5098 E Zygote  : MountEmulatedStorage()
03-17 07:10:49.295  5098  5098 E Zygote  : v2
03-17 07:10:49.295  5098  5098 I libpersona: KNOX_SDCARD checking this for 10003
03-17 07:10:49.295  5098  5098 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:49.295  5098  5098 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 07:10:49.295  5098  5098 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 07:10:49.305  5098  5098 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 07:10:49.305  2141  5096 D GassUtils: Found app info for package com.test.thalitest:19. Hash: 3a6332e64e629141c2a938dcd325767951fafbc70df540f2afadc7f283ec0db2
03-17 07:10:49.305  2141  5096 D k       : Found info for package com.test.thalitest in db.
,03-17 07:10:49.315  2141  5093 W BaseAppContext: Using Auth Proxy for data requests.
03-17 07:10:49.315  2141  5093 W BaseAppContext: Using Auth Proxy for data requests.
,03-17 07:10:49.315  1022  1034 I TactileAssist: enable value -1
03-17 07:10:49.315  1022  1034 I TactileAssist: internal enable value -1
03-17 07:10:49.315  1022  1034 I TactileAssist: intensity value -1
03-17 07:10:49.315  1022  1034 I TactileAssist: saveAppList value true
,03-17 07:10:49.315  1022  1034 I TactileAssist: List of disabled apps :
,03-17 07:10:49.325  5098  5098 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:49.325  1022  1659 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:49.325  1022  1659 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 07:10:49.325  5098  5098 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:49.325  1022  1659 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:49.335  1022  1392 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:49.335  1022  1392 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:49.335  1022  1392 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,03-17 07:10:49.355  1022  1597 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:49.355  1022  1597 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 07:10:49.355  1022  1597 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:49.365  2141  5093 W BaseAppContext: Using Auth Proxy for data requests.
,03-17 07:10:49.365  1022  1321 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:49.365  1022  1321 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:49.365  1022  1321 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:49.365  1022  1321 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:49.375  5115  5115 E Zygote  : MountEmulatedStorage()
03-17 07:10:49.375  5115  5115 E Zygote  : v2
03-17 07:10:49.375  5115  5115 I libpersona: KNOX_SDCARD checking this for 10009
03-17 07:10:49.375  5115  5115 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:49.375  5115  5115 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,03-17 07:10:49.375  1022  1321 I ActivityManager: Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.MyPackageReplacedReceiver: pid=5115 uid=10009 gids={50009, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,03-17 07:10:49.385  5115  5115 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 07:10:49.385  5115  5115 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,03-17 07:10:49.385  1022  1659 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:49.385  1022  1659 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-17 07:10:49.385  1022  1659 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:49.395  2141  5093 W BaseAppContext: Using Auth Proxy for data requests.
,03-17 07:10:49.405   304   304 I art     : Explicit concurrent mark sweep GC freed 8691(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 616us total 30.891ms
,03-17 07:10:49.425   304   304 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 583us total 16.817ms,
,03-17 07:10:49.435  2141  5093 W BaseAppContext: Using Auth Proxy for data requests.
,03-17 07:10:49.445  1022  1046 W libprocessgroup: failed to open /acct/uid_10065/pid_4317/cgroup.procs: No such file or directory
,03-17 07:10:49.445  5115  5115 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:49.445  5115  5115 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:49.445   304   304 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 597us total 18.739ms
,03-17 07:10:49.475  4986  4999 I art     : WaitForGcToComplete blocked for 5.543ms for cause Background
,03-17 07:10:49.545  1022  1520 I art     : Explicit concurrent mark sweep GC freed 24575(1446KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 24MB/36MB, paused 2.771ms total 164.201ms
,03-17 07:10:49.545  1022  1520 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:49.545  1022  1520 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 07:10:49.545  1022  1520 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.gms
,03-17 07:10:49.555  1880  1880 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 07:10:49.555  1022  1321 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:49.555  1022  1321 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:49.555  1022  1321 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:49.555  1022  1321 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:49.555  1880  1880 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 07:10:49.565  5135  5135 E Zygote  : MountEmulatedStorage()
03-17 07:10:49.565  5135  5135 E Zygote  : v2
03-17 07:10:49.565  5135  5135 I libpersona: KNOX_SDCARD checking this for 10048
03-17 07:10:49.565  5135  5135 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:49.565  5135  5135 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 07:10:49.565  5135  5135 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 07:10:49.575  1022  1321 I ActivityManager: Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=5135 uid=10048 gids={50048, 9997, 3003, 3002} abi=armeabi-v7a
,03-17 07:10:49.575  5135  5135 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,03-17 07:10:49.575  1022  1520 I ActivityManager: Killing 4372:com.samsung.helphub/1000 (adj 15): empty #31
,03-17 07:10:49.585  1022  1659 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:49.585  1022  1659 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 07:10:49.585  1022  1659 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-17 07:10:49.585  1022  1667 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:49.585  1022  1667 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 07:10:49.585  1022  1667 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:49.595  5135  5135 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:49.595  5135  5135 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:49.595  1022  1404 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:49.595  1022  1404 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 07:10:49.595  1022  1404 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:49.605  1022  1034 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:49.605   284   284 E installd: system dir 0 : /system/app/
03-17 07:10:49.605   284   284 E installd: system dir 1 : /system/priv-app/,
03-17 07:10:49.605   284   284 E installd: system dir 2 : /vendor/app/
03-17 07:10:49.605   284   284 E installd: system dir 3 : /oem/app/
03-17 07:10:49.605  1022  1034 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 07:10:49.605  1022  1034 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:49.615  1022  1392 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:49.615  1022  1392 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 07:10:49.615  1022  1392 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:49.615  1022  1659 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:49.615  1022  1659 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-17 07:10:49.615  1022  1659 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:49.625  1022  1902 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:49.625  1022  1902 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 07:10:49.625  1022  1902 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:49.645  4928  4928 I Mms/MmsApp:  start initViewCache mms
,03-17 07:10:49.645  1022  1667 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:49.645  1022  1667 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 07:10:49.645  1022  1667 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:49.655  4928  4928 D Mms/ComposeMessageFragment: [start]    fillCache consume time = 1753.841405
,03-17 07:10:49.655  4928  4928 D Mms/ComposeMessageFragment: fillCache, easy = false
03-17 07:10:49.655  1022  1062 D PackageManager: remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
,03-17 07:10:49.655  1022  1404 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:49.655  1022  1404 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 07:10:49.655  1022  1404 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:49.665  1022  1597 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:49.665  1022  1597 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 07:10:49.665  1022  1597 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:49.675  1022  1321 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:49.675  1022  1321 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 07:10:49.675  1022  1321 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:49.715  5135  5135 D Compatibility: onReceive() it will make start service
,03-17 07:10:49.715  1022  1659 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:49.715  1022  1659 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:49.715  1022  1659 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
,03-17 07:10:49.735  5135  5159 D Compatibility: onHandleIntent()
,03-17 07:10:49.735  5135  5159 D Compatibility: intentservice saw: Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.UID=10167, android.intent.extra.user_handle=0}]
,03-17 07:10:49.735  1022  1046 W libprocessgroup: failed to open /acct/uid_1000/pid_4372/cgroup.procs: No such file or directory
,03-17 07:10:49.745  1022  1507 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:49.745  1022  1507 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 07:10:49.745  1022  1507 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,03-17 07:10:49.745  1022  1902 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:49.745  1022  1902 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 07:10:49.745  1022  1902 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:49.755  4388  4388 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:147 android.app.ActivityThread.handleReceiver:3125 
,03-17 07:10:49.765  5135  5159 D Compatibility: found: 2
,03-17 07:10:49.765  3800  5160 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,03-17 07:10:49.765  1022  1667 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:49.765  1022  1667 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:49.765  1022  1667 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,03-17 07:10:49.775  1022  1035 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:49.775  1022  1035 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 07:10:49.775  1022  1035 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:49.785  1022  1034 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:49.785  1022  1034 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-17 07:10:49.785  1022  1034 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:49.805  5135  5159 D Compatibility: saved default: com.sec.android.app.soundalive.SAControlPanelActivity
03-17 07:10:49.805  5135  5159 D Compatibility: skipping ResolveInfo{17c30834 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
03-17 07:10:49.805  5135  5159 D Compatibility: considering ResolveInfo{16c2865d com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
03-17 07:10:49.805  5135  5159 D Compatibility: default: com.sec.android.app.soundalive.SAControlPanelActivity
,03-17 07:10:49.805  5135  5159 D Compatibility: enabling receiver ResolveInfo{3eb1bbd2 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,03-17 07:10:49.815  5135  5159 D Compatibility: enabling receiver ResolveInfo{2f5324a3 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000},
,03-17 07:10:49.835  5135  5159 D Compatibility: enabling receiver ResolveInfo{34a273a0 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,03-17 07:10:49.835  5135  5159 D Compatibility: enabling receiver ResolveInfo{36262b59 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,03-17 07:10:49.845  5135  5159 D Compatibility: wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
,03-17 07:10:49.865  1022  1392 I ActivityManager: Killing 4444:com.sec.android.app.bluetoothtest/1000 (adj 15): empty #31
,03-17 07:10:49.875  1022  1404 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:49.875  1022  1404 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 07:10:49.875  1022  1404 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
,03-17 07:10:49.875  2141  5069 I PeopleDatabaseHelper: cleanUpNonGplusAccounts done.
,03-17 07:10:49.885  1022  1667 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:49.885  1022  1667 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 07:10:49.885  1022  1667 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:49.935  1022  1046 W libprocessgroup: failed to open /acct/uid_1000/pid_4444/cgroup.procs: No such file or directory
,03-17 07:10:49.935  4928  4928 D AbsListView: Get MotionRecognitionManager
,03-17 07:10:49.965  1022  1129 I ActivityManager: Killing 4428:com.sec.knox.knoxsetupwizardclient/1000 (adj 15): empty #31
,03-17 07:10:49.975  1022  1392 D MotionRecognitionService:  ssp status : false
,03-17 07:10:49.975  4928  4928 D Mms/ComposeMessageFragment: [end]    fillCache consume time = 325.999167
,03-17 07:10:50.055   288   288 E SMD     : DCD OFF
,03-17 07:10:50.055  1022  1046 W libprocessgroup: failed to open /acct/uid_1000/pid_4428/cgroup.procs: No such file or directory
,03-17 07:10:50.085  4928  4928 D Mms/BubbleViewCache: fillCache bubble = 1
,03-17 07:10:50.085  1022  1667 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:50.085  1022  1667 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 07:10:50.085  1022  1667 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,03-17 07:10:50.155  3693  3744 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 10 sec
,03-17 07:10:50.315  1022  1404 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:50.315  1022  1404 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 07:10:50.315  1022  1404 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:50.325  3800  5160 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 552 ms] updated apps [took 552 ms] 
,03-17 07:10:50.355  1022  1321 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:50.355  1022  1321 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:50.355  1022  1321 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:50.355  1022  1321 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:50.365  5175  5175 E Zygote  : MountEmulatedStorage(),
03-17 07:10:50.365  5175  5175 E Zygote  : v2
03-17 07:10:50.365  5175  5175 I libpersona: KNOX_SDCARD checking this for 1000,
03-17 07:10:50.365  5175  5175 I libpersona: KNOX_SDCARD not a persona
03-17 07:10:50.375  5175  5175 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 07:10:50.375  5175  5175 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,03-17 07:10:50.375  1022  1321 I ActivityManager: Start proc com.samsung.android.app.filterinstaller for broadcast com.samsung.android.app.filterinstaller/.PackageIntentReceiver: pid=5175 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-17 07:10:50.375  5175  5175 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 07:10:50.375  1022  1321 I ActivityManager: Killing 4470:com.sec.knox.bridge/1000 (adj 15): empty #31,
,03-17 07:10:50.385  1022  1597 W ActivityManager: userId = 0, bbcId = -10000,
03-17 07:10:50.385  1022  1597 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 07:10:50.385  1022  1597 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.docs, destAppInfo.processName = com.google.android.apps.docs
,03-17 07:10:50.385  4986  4986 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,03-17 07:10:50.395  5175  5175 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:50.395  5175  5175 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:50.455  5175  5175 D FilterInstaller: onReceive:android.intent.action.PACKAGE_ADDED, package:com.test.thalitest
,03-17 07:10:50.455  5175  5175 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:44 android.app.ActivityThread.handleReceiver:3125 
,03-17 07:10:50.455  1022  1667 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:50.455  1022  1667 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-17 07:10:50.455  1022  1667 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.filterinstaller, destAppInfo.processName = com.samsung.android.app.filterinstaller
,03-17 07:10:50.465  1022  1321 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:50.465  1022  1321 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:50.465  1022  1321 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:50.465  1022  1321 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:50.465  5175  5175 I FilterInstaller: FilterPackageService : ACTION_CHANGED
,03-17 07:10:50.475  5197  5197 E Zygote  : MountEmulatedStorage(),
03-17 07:10:50.475  1022  1321 I ActivityManager: Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=5197 uid=10098 gids={50098, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
03-17 07:10:50.475  5197  5197 E Zygote  : v2
03-17 07:10:50.475  5197  5197 I libpersona: KNOX_SDCARD checking this for 10098
03-17 07:10:50.475  5197  5197 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
03-17 07:10:50.475  5197  5197 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:50.475  5197  5197 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,03-17 07:10:50.485  5197  5197 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 07:10:50.485  5175  5196 E FilterInstaller: installFilters
03-17 07:10:50.485  5175  5196 E FilterInstaller: There is no requred permission
,03-17 07:10:50.495  1022  1046 W libprocessgroup: failed to open /acct/uid_1000/pid_4470/cgroup.procs: No such file or directory
,03-17 07:10:50.505  5197  5197 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:50.505  5197  5197 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:50.535  5197  5197 D PackageIntentReceiver: ACTION_PACKAGE_ADDED
,03-17 07:10:50.535  5197  5197 D PackageIntentReceiver: Not GearManger package! 
,03-17 07:10:50.535  1022  1507 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:50.535  1022  1507 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:50.535  1022  1507 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:50.535  1022  1507 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:50.555  1022  1507 I ActivityManager: Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver: pid=5212 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-17 07:10:50.555  5212  5212 E Zygote  : MountEmulatedStorage()
03-17 07:10:50.555  1022  1507 I ActivityManager: Killing 4493:com.sec.android.app.mt/1000 (adj 15): empty #31
03-17 07:10:50.555  5212  5212 E Zygote  : v2
03-17 07:10:50.555  5212  5212 I libpersona: KNOX_SDCARD checking this for 1000
03-17 07:10:50.555  5212  5212 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:50.555  5212  5212 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 07:10:50.555  5212  5212 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 07:10:50.555  5212  5212 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 07:10:50.575  5212  5212 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:50.575  5212  5212 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:50.615  1022  1100 V AlarmManager: waitForAlarm result :4
,03-17 07:10:50.625  1022  1597 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:50.625  1022  1597 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:50.625  1022  1597 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:50.625  1022  1597 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:50.645  5227  5227 E Zygote  : MountEmulatedStorage()
,03-17 07:10:50.645  5227  5227 E Zygote  : v2
03-17 07:10:50.645  5227  5227 I libpersona: KNOX_SDCARD checking this for 1000,
03-17 07:10:50.645  1022  1597 I ActivityManager: Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=5227 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-17 07:10:50.645  5227  5227 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:50.645  1022  1597 I ActivityManager: Killing 4350:com.vlingo.midas/u0a28 (adj 15): empty #31
,03-17 07:10:50.645  5227  5227 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 07:10:50.645  5227  5227 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 07:10:50.645  5227  5227 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 07:10:50.665  5227  5227 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:50.665  5227  5227 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:50.715  4986  4986 W GAV2    : Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,03-17 07:10:50.715  1022  1321 I ActivityManager: Killing 4547:com.samsung.android.sconnect/u0a121 (adj 15): empty #31
,03-17 07:10:50.745  1022  1034 I ActivityManager: Killing 4569:com.sec.android.app.sbrowser/u0a127 (adj 15): empty #31
,03-17 07:10:50.755  5227  5243 D AcmsPackageEventListener: Received: android.intent.action.PACKAGE_ADDED
,03-17 07:10:50.755  1022  1035 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:50.755  1022  1035 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 07:10:50.755  1022  1035 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,03-17 07:10:50.765  1022  1046 W libprocessgroup: failed to open /acct/uid_1000/pid_4493/cgroup.procs: No such file or directory
,03-17 07:10:50.765  1022  1046 W libprocessgroup: failed to open /acct/uid_10028/pid_4350/cgroup.procs: No such file or directory
,03-17 07:10:50.775  5227  5243 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:54 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:1 
,03-17 07:10:50.775  1022  1392 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:50.775  1022  1392 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:50.775  1022  1392 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.mirrorlink, destAppInfo.processName = com.samsung.android.app.mirrorlink
,03-17 07:10:50.795  5227  5227 D AcmsService: Enter Oncreate
,03-17 07:10:50.795  5227  5227 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
,03-17 07:10:50.795  5227  5227 D AcmsService: creating AcmsCore
,03-17 07:10:50.795  5227  5227 D AcmsCore: AcmsCore.getAcmsCore() - Enter
03-17 07:10:50.795  5227  5227 D AcmsCore: AcmsCore
,03-17 07:10:50.805  5227  5227 D AcmsCore: init
,03-17 07:10:50.805  5227  5227 D AcmsCore: Looper handler is not null
,03-17 07:10:50.805  5227  5227 D AcmsCore: Post to AcmsCoreHandler
,03-17 07:10:50.805  5227  5227 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
,03-17 07:10:50.805  5227  5227 D AcmsServiceMonitor: Incrementing - Counter value: 1
03-17 07:10:50.805  5227  5227 D AcmsCore: Incremented Counter Value: postToAcmsCoreHandler =>1
03-17 07:10:50.805  5227  5227 D AcmsService: onStartCommand,
03-17 07:10:50.805  5227  5227 D AcmsService: Action: android.intent.action.PACKAGE_ADDED
03-17 07:10:50.805  5227  5227 D AcmsServiceMonitor: Enter incrementSvcCounter with startId 1
03-17 07:10:50.805  5227  5227 D AcmsServiceMonitor: Incrementing - Counter value: 2
03-17 07:10:50.805  5227  5227 D AcmsService: Incremented Counter Value : onStartCommand
,03-17 07:10:50.805  5227  5245 D AcmsCertificateMngr: AcmsCertificateMngr
,03-17 07:10:50.805  5227  5245 D AcmsRevocationMngr: AcmsRevocationMngr
,03-17 07:10:50.815  5227  5227 D ActivityThread: Loading provider com.samsung.mirrorlink.acms.pkgnames: com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide
,03-17 07:10:50.835  1022  1404 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:50.835  1022  1404 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:50.835  1022  1404 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:50.835  1022  1404 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:50.835  2141  4254 I Icing   : Indexing F5F81CF6796F0674BFD4891EB30D9087E2AF40AA from com.google.android.gms
,03-17 07:10:50.845  5246  5246 E Zygote  : MountEmulatedStorage()
,03-17 07:10:50.845  5246  5246 E Zygote  : v2
03-17 07:10:50.845  5246  5246 I libpersona: KNOX_SDCARD checking this for 10152
03-17 07:10:50.845  5246  5246 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:50.845  5246  5246 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,03-17 07:10:50.855  5246  5246 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,03-17 07:10:50.855  5227  5227 D AcmsService: Inside handle Intent
03-17 07:10:50.855  5227  5227 D AcmsService: App added - package name: com.test.thalitest
03-17 07:10:50.855  1022  1404 I ActivityManager: Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TapandpayAppWidgetProvider: pid=5246 uid=10152 gids={50152, 9997} abi=armeabi-v7a
03-17 07:10:50.855  5227  5227 D AcmsCore: Post to AcmsCoreHandler
03-17 07:10:50.855  5227  5227 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
03-17 07:10:50.855  5227  5227 D AcmsServiceMonitor: Incrementing - Counter value: 3
03-17 07:10:50.855  5227  5227 D AcmsCore: Incremented Counter Value: postToAcmsCoreHandler =>2
03-17 07:10:50.855  5227  5227 D AcmsService: Decremented Counter Value : handleStartIntent
03-17 07:10:50.855  5227  5227 D AcmsServiceMonitor: Decrementing - Counter value: 2
,03-17 07:10:50.865  5246  5246 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,03-17 07:10:50.875  1022  1046 W libprocessgroup: failed to open /acct/uid_10121/pid_4547/cgroup.procs: No such file or directory
,03-17 07:10:50.875  1022  1046 W libprocessgroup: failed to open /acct/uid_10127/pid_4569/cgroup.procs: No such file or directory
,03-17 07:10:50.885  5246  5246 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:50.885  5246  5246 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:50.885  1022  3349 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-17 07:10:50.915  5246  5246 I TapandpayWidget:TapandpayAppWidgetProvider: onReceive()
03-17 07:10:50.915  5246  5246 D TapandpayWidget:TapandpayAppWidgetProvider: onReceive() - action : android.intent.action.PACKAGE_ADDED / mCurIndex :-10
,03-17 07:10:50.925  5246  5246 I TapandpayWidget:Utils: Clear T&P info.
,03-17 07:10:50.925  5246  5246 D TapandpayWidget:TapandpayAppWidgetProvider: Widget is not attached.
,03-17 07:10:50.925  1022  1667 I splitIntent: Queue : backgroundsplit_1 intent android.intent.action.PACKAGE_ADDED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,03-17 07:10:50.935  1022  1047 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:50.935  1022  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:50.935  1022  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
,03-17 07:10:50.935  1022  1047 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:50.935  1022  1047 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:50.935  1022  1047 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:50.935  1022  1047 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:50.945  2141  4254 D Icing   : Loaded CLD2 Version V2.0 - 20141016,
,03-17 07:10:50.945  2141  4254 I Icing   : Indexing done F5F81CF6796F0674BFD4891EB30D9087E2AF40AA,
,03-17 07:10:50.955  5262  5262 E Zygote  : MountEmulatedStorage(),
,03-17 07:10:50.955  5262  5262 E Zygote  : v2,
03-17 07:10:50.955  5262  5262 I libpersona: KNOX_SDCARD checking this for 10139
03-17 07:10:50.955  5262  5262 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:50.955  1022  1047 I ActivityManager: Start proc com.sec.android.widgetapp.activeapplicationwidget for broadcast com.sec.android.widgetapp.activeapplicationwidget/.ProgramMonitorProvider: pid=5262 uid=10139 gids={50139, 9997, 1028, 1015} abi=armeabi-v7a
03-17 07:10:50.955  5262  5262 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 07:10:50.955  5262  5262 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 07:10:50.965  5262  5262 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 07:10:50.975  5262  5262 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:50.975  5262  5262 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:51.005  5262  5262 V TaskCloserActivity: TaskCloserActivity enter()
,03-17 07:10:51.005  5262  5262 V TaskCloserActivity: TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
,03-17 07:10:51.015  1022  1034 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:51.015  1022  1034 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:51.015  1022  1034 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:51.015  1022  1034 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:51.025  5277  5277 E Zygote  : MountEmulatedStorage(),
03-17 07:10:51.025  5277  5277 E Zygote  : v2
03-17 07:10:51.025  5277  5277 I libpersona: KNOX_SDCARD checking this for 1000
03-17 07:10:51.025  5277  5277 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 07:10:51.025  5277  5277 I libpersona: KNOX_SDCARD not a persona
03-17 07:10:51.025  1022  1034 I ActivityManager: Start proc com.samsung.android.MtpApplication for broadcast com.samsung.android.MtpApplication/.MtpReceiver: pid=5277 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,03-17 07:10:51.025  1022  1034 I ActivityManager: Killing 4598:com.android.calendar/u0a131 (adj 15): empty #31
,03-17 07:10:51.035  5277  5277 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 07:10:51.035  5277  5277 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 07:10:51.055  5277  5277 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:51.055  5277  5277 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:51.075  5277  5277 E MTPRx   : In MtpReceiverandroid.hardware.usb.action.USB_STATE
,03-17 07:10:51.085  1022  1392 D SecContentProvider2: uri = 14 selection = getSealedState
,03-17 07:10:51.085  1022  1392 D SecContentProvider2: mCursor = null
,03-17 07:10:51.085  1022  1597 D SecContentProvider2: uri = 14 selection = getSealedUsbMassStorageState
03-17 07:10:51.085  1022  1597 D SecContentProvider2: mCursor = null
,03-17 07:10:51.085  5277  5277 V MTPRx   : sealedState: false
03-17 07:10:51.085  5277  5277 V MTPRx   : sealedUsbMassStorageState: false
03-17 07:10:51.085  5277  5277 E MTPRx   : check value of boot_completed is1
03-17 07:10:51.085  5277  5277 E MTPRx   : check booting is completed_sys.boot_completed
,03-17 07:10:51.085  5277  5277 E MTPRx   : Sd-Card path/storage/extSdCard
,03-17 07:10:51.085  5277  5277 E MTPRx   : Status for mount/Unmount :removed
03-17 07:10:51.085  5277  5277 E MTPRx   : SDcard is not available
,03-17 07:10:51.085  5277  5277 W MTPRx   : value of connected istrue
03-17 07:10:51.085  5277  5277 W MTPRx   : value of configured istrue
03-17 07:10:51.085  5277  5277 W MTPRx   : value of mtpEnabled istrue
03-17 07:10:51.085  5277  5277 W MTPRx   : value of ptpEnabled isfalse
,03-17 07:10:51.095  5277  5277 E MTPRx   : Received USB_STATE with sdCardLaunch = 0
,03-17 07:10:51.095  5277  5277 E MTPRx   : mFirstTime: false
,03-17 07:10:51.115  5277  5277 D         : MTP: reading debug level property
,03-17 07:10:51.115  3441  4918 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendStickyBroadcast:1865 android.content.ContextWrapper.sendStickyBroadcast:463 com.sec.android.app.sysscope.service.h.run:-1 java.lang.Thread.run:818 <bottom of call stack> 
,03-17 07:10:51.115  5277  5277 E MTPJNIInterface: Getting CryptionKey from JAVA
03-17 07:10:51.115  5277  5277 E MTPRx   : currentUserId is 0
,03-17 07:10:51.115  3693  3693 I DBG_DM  : [com.wssyncmldm.llIlIIIIlIIIIIlIlIII(352/onReceive)] com.sec.intent.action.SYSSCOPESTATUS
,03-17 07:10:51.125  3693  3693 I DBG_DM  : [com.wssyncmldm.llIlIIIIlIIIIIlIlIII(356/onReceive)] status  = 1
,03-17 07:10:51.125  3441  3441 I Process : Sending signal. PID: 3441 SIG: 9
,03-17 07:10:51.125   254   254 E lowmemorykiller: Error writing /proc/3441/oom_score_adj; errno=22
,03-17 07:10:51.125   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,03-17 07:10:51.125  3693  3693 E DBG_DM  : [com.wssyncmldm.llIlIIIIlIIIIIlIlIII(367/onReceive)] Device is ok
,03-17 07:10:51.125  3693  3693 I DBG_DM  : [com.wssyncmldm.XDMService(639/llllIIIllIlIIIIllllI)] TopActivity : com.android.launcher2.Launcher
,03-17 07:10:51.135  5277  5277 E MTPRx   : Start observing USB_STATE_MATCH 
,03-17 07:10:51.135  5277  5277 E MTPRx   : cannot open file : /sys/class/android_usb/android0/bcdUSB
03-17 07:10:51.135  5277  5277 E MTPRx   : is_Privatemode is NOT 1
,03-17 07:10:51.135  1022  1046 W libprocessgroup: failed to open /acct/uid_10131/pid_4598/cgroup.procs: No such file or directory
,03-17 07:10:51.135  1022  1507 D SettingsProvider: name = boot_time_connected
,03-17 07:10:51.145  5277  5277 E MTPRx   : Sending NORMAL_BOOT to stack
03-17 07:10:51.145  5277  5277 E MTPJNIInterface: noti = 17
,03-17 07:10:51.145  1022  1902 D SettingsProvider: name = mtp_usb_conditions_met
,03-17 07:10:51.145  1022  1034 D SecContentProvider: uri = 18 selection = isUsbMediaPlayerAvailable
,03-17 07:10:51.145  5277  5277 E MTPRx   : sending MTP_ICON_ENABLED to stack
,03-17 07:10:51.145  1022  1520 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:51.155  1022  1520 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:51.155  1022  1520 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.samsung.android.MtpApplication
,03-17 07:10:51.155  3693  3744 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 11 sec
,03-17 07:10:51.155  3693  3744 I DBG_DM  : [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,03-17 07:10:51.155  1022  1035 D SettingsProvider: name = mtp_running_status
,03-17 07:10:51.165  3693  3744 I DBG_DM  : [com.wssyncmldm.XDMService(639/llllIIIllIlIIIIllllI)] TopActivity : com.android.launcher2.Launcher
,03-17 07:10:51.165  3693  3744 I DBG_DM  : [IIlIIIlllllIIlIIIlII(91/llllIIIllIlIIIIllllI)] 
,03-17 07:10:51.165  1022  1321 D SettingsProvider: name = mtp_usb_conditions_met
,03-17 07:10:51.165  5277  5277 E MTPRx   : else part ... so first time!!!
,03-17 07:10:51.165  5277  5277 E MTPPlaObsrvr: inside setContext()
03-17 07:10:51.165  5277  5277 E MTPPlaObsrvr:  inside createplafiles
,03-17 07:10:51.175  5277  5277 E MTPPlaObsrvr: playlist count is0
03-17 07:10:51.175  5277  5277 E MTPPlaObsrvr:  inside try branch createplafiles
03-17 07:10:51.175  1206  1206 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
03-17 07:10:51.175  5277  5277 E MTPPlaObsrvr:  inside deleteing plas createplafiles
,03-17 07:10:51.175  3693  3744 I DBG_DM  : [com.wssyncmldm.db.file.XDB(3660/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,03-17 07:10:51.175  5277  5277 E MTPPlaObsrvr: Inside registerContentObserver
,03-17 07:10:51.175  5277  5277 E MtpAdbObserver: inside setContext()
,03-17 07:10:51.175  5277  5277 E MtpAdbObserver: Inside registerContentObserver
03-17 07:10:51.175  5277  5277 W Settings: Setting adb_enabled has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only global URI.
,03-17 07:10:51.185  1022  1129 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:51.185  1022  1129 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:51.185  1022  1129 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.samsung.android.MtpApplication
,03-17 07:10:51.185  1022  1035 D SettingsProvider: name = mtp_running_status
,03-17 07:10:51.185  1022  1667 D SettingsProvider: name = mtp_usb_conditions_met
,03-17 07:10:51.185  5277  5277 E MtpService: onCreate.
,03-17 07:10:51.185  1022  1321 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:51.185  1022  1321 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:51.185  1022  1321 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,03-17 07:10:51.195  3693  3744 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5479/llIlIIIIlllIlllllIll)] Download Postpone status : 0
,03-17 07:10:51.195  5277  5277 E MtpService: < MTP > Registering BroadCast receiver :::::
,03-17 07:10:51.205  5277  5294 V MtpMediaDBManager: inside deleteAllDB
,03-17 07:10:51.205  5277  5277 E MtpService: < MTP > Registering BroadCast registerBroadCastPolicyRec :::::
03-17 07:10:51.205  1256  1256 D MtpService: updating state; isCurrentUser=true, mMtpLocked=false
,03-17 07:10:51.205  1022  1321 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:51.205  1022  1321 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:51.205  1022  1321 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:51.205  3693  3744 I DBG_DM  : [com.wssyncmldm.db.file.XDB(6236/IlIIlIIlIllllIlllIII)] Initiated Type: 2
03-17 07:10:51.205  1022  1321 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:51.205  3693  3744 I DBG_DM  : [IlIlllIlllllIlIllllI(102/lllIlIlIIIllIIlIllIl)] nStatus [220]
,03-17 07:10:51.225  5296  5296 E Zygote  : MountEmulatedStorage()
03-17 07:10:51.225  5296  5296 I libpersona: KNOX_SDCARD checking this for 1000
03-17 07:10:51.225  5296  5296 E Zygote  : v2
03-17 07:10:51.225  5296  5296 I libpersona: KNOX_SDCARD not a persona
03-17 07:10:51.225  5277  5277 E MtpService: < MTP > Registering BroadCast registerBroadCastEmergencyRec :::::
03-17 07:10:51.225  1022  1321 I ActivityManager: Start proc com.samsung.android.app.mirrorlink for broadcast com.samsung.android.app.mirrorlink/.TMNetworkReceiver: pid=5296 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,03-17 07:10:51.225  5296  5296 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 07:10:51.225  3693  3744 I DBG_DM  : [IlIlllIlllllIlIllllI(251/lllIlIlIIIllIIlIllIl)] XDL_STATE_READY_TO_UPDATE
,03-17 07:10:51.225  5277  5277 E MtpService: onStartCommand.
,03-17 07:10:51.225  3693  3744 I DBG_DM  : [IlIIlIIlIllllIlllIII(274/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT : Initialized,
03-17 07:10:51.225  3693  3745 I DBG_DM  : [llllIIIllIllIlllIIlI(772/llIIIIlllllIIllIIllI)] XUI_DL_UPDATE_START
,03-17 07:10:51.225  5277  5277 W MTPRx   : calling native method
03-17 07:10:51.225  5277  5277 E MTPJNIInterface: < MTP > Registering BroadCast receiver :::::
03-17 07:10:51.225  5277  5295 E MtpService: handleMessage. msg= { when=-1ms what=0 arg1=1 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler },
03-17 07:10:51.225  5296  5296 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 07:10:51.225  5296  5296 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 07:10:51.225  3693  3744 I DBG_DM  : [IlIIlIIlIllllIlllIII(1901/llllIIIllIlIIIIllllI)] 
03-17 07:10:51.235  3693  3744 I DBG_DM  : [com.wssyncmldm.DMSecBroadcastReceiver(572/llIIIIlllllIIllIIllI)] m_IsSavedNfcMode : false
,03-17 07:10:51.235  3693  3745 I DBG_DM  : [llllIlllIIIlIlIlIIII(49/llIIIIlllllIIllIIllI)] 
,03-17 07:10:51.235  3693  3744 I DBG_DM  : [com.wssyncmldm.ui.llllIIIllIlIIIIllllI(503/lllIlIlIIIllIIlIllIl)] Get bUpdateReport = false
,03-17 07:10:51.235  1022  1035 I ActivityManager: Process com.sec.android.app.sysscope (pid 3441)(adj 0) has died(43,627)
,03-17 07:10:51.235  5277  5277 E MTPJNIInterface: < MTP > Registering BroadCast receiver :::::::
,03-17 07:10:51.235  5277  5277 E MTPJNIInterface: noti = 10
,03-17 07:10:51.245  5277  5277 E MtpService: onStartCommand.
03-17 07:10:51.245  5277  5294 V MtpMediaDBManager: inside Thread updateDB
,03-17 07:10:51.245  5277  5277 W MTPRx   : calling native method
03-17 07:10:51.245  5277  5277 E MTPRx   : Checking the driver time out
03-17 07:10:51.245  5277  5295 E MtpService: handleMessage. msg= { when=0 what=0 arg1=2 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
03-17 07:10:51.245  5277  5277 E MTPJNIInterface: noti = 2
03-17 07:10:51.245  5277  5277 D         : deleting sockets before message queue initialization
03-17 07:10:51.245  5277  5277 D         : event handler thread is created, so set the flag
,03-17 07:10:51.245  5277  5277 E MTPRx   : called native method
03-17 07:10:51.245  5277  5277 E MTPJNIInterface: setting Media scanner status0
03-17 07:10:51.245  5277  5277 E MTPJNIInterface: After setting Media scanner status0
,03-17 07:10:51.245  5277  5277 W MTPRx   : notification from stack 1
,03-17 07:10:51.245  5296  5296 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:51.255  5277  5307 E         : Unable to get Object Class and clearing cls 2 [int check_media_scanner_status() 594]
,03-17 07:10:51.255  5296  5296 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:51.255  5277  5307 E MTPJNIInterface: Getting media scanner status0
,03-17 07:10:51.255  3693  3745 I DBG_DM  : [IIllIIIIlIlIlIlIllII(49/IIIlIIllIlIIllIlllII)] FirmwareObjectSize:362673799
,03-17 07:10:51.255  3693  3745 I DBG_DM  : [IIllIIIIlIlIlIlIllII(1715/llllllIllIlIlllIIlIl)] 
,03-17 07:10:51.255  5277  5307 E MTPJNIInterface: DeviceName is Thali Test (Galaxy A3)
,03-17 07:10:51.265  5277  5294 E MtpMediaDBManager: count : 26
,03-17 07:10:51.265  3693  3745 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5178/IIIIlIllIlllIlIIIIlI)] Data Margin : 500
,03-17 07:10:51.275  3693  3745 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5298/IlIllIIIIllllllIlIIl)] Data App Weight : 0.0
,03-17 07:10:51.285  5277  5294 W MtpMediaDBManager: sending db update complete noti to stack
03-17 07:10:51.285  5277  5294 E MTPJNIInterface: noti = 29
,03-17 07:10:51.285  5277  5307 E SQLiteLog: (5) database is locked
03-17 07:10:51.285  3693  3745 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5258/llllIIlIlIIIIllIlIIl)] Delta Weight : 0.5
,03-17 07:10:51.285  3693  3745 I DBG_DM  : [com.wssyncmldm.db.file.llllIIIllIlIIIIllllI(194/llIIIIlllllIIllIIllI)] ### Data Margin only: 705624899
,03-17 07:10:51.295  3693  3693 I DBG_DM  : [com.wssyncmldm.llIIllllIIlllIIIIlll(1125/handleMessage)] event ->220
,03-17 07:10:51.295  3693  3693 I DBG_DM  : [com.wssyncmldm.XDMService(639/llllIIIllIlIIIIllllI)] TopActivity : com.android.launcher2.Launcher
,03-17 07:10:51.295  3693  3693 I DBG_DM  : [com.wssyncmldm.XDMService(712/lllIIIIllIlIlllllllI)] 
,03-17 07:10:51.305  5277  5307 E MTPJNIInterface: Status for mount/Unmount :removed
03-17 07:10:51.305  5277  5307 E MTPJNIInterface: SDcard is not available
,03-17 07:10:51.305  3693  3693 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5018/IIllIIllIIIlllIlIIll)] Get Autoinstall status : false
,03-17 07:10:51.325  3693  3745 I DBG_DM  : [llllIIIllIllIlllIIlI(726/llIIIIlllllIIllIIllI)] XUI_DL_UPDATE_CONFIRM
,03-17 07:10:51.325  3693  3693 I DBG_DM  : [com.wssyncmldm.XDMService(468/lIllIllllIIIlllIlllI)] 
,03-17 07:10:51.325  5277  5307 E         : [mtp_hidden_system_volume 189] Error opening file [error = Read-only file system] 
,03-17 07:10:51.325  3693  3745 I DBG_DM  : [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : true
,03-17 07:10:51.335  2141  4254 I Icing   : Indexing D2B2F813CD55909B17D100D9886DFA4C4B449F6E from com.google.android.googlequicksearchbox
,03-17 07:10:51.335  3693  3693 E DBG_DM  : [com.wssyncmldm.XDMService(476/lIllIllllIIIlllIlllI)] didn't register
,03-17 07:10:51.335  3693  3693 E DBG_DM  : [com.wssyncmldm.XDMService(477/lIllIllllIIIlllIlllI)] java.lang.IllegalArgumentException: Receiver not registered: com.wssyncmldm.llIIIIlllllIIllIIllI@3d235919
,03-17 07:10:51.335  3693  3693 I DBG_DM  : [com.wssyncmldm.XDMService(755/lllllIIlIIIlIlIIIllI)] UI_id:223
,03-17 07:10:51.335  5277  5307 E MTPJNIInterface: Status for mount/Unmount :removed
03-17 07:10:51.335  5277  5307 E MTPJNIInterface: SDcard is not available
03-17 07:10:51.335  5277  5307 E SQLiteLog: (21) API call with NULL database connection pointer
03-17 07:10:51.335  5277  5307 E SQLiteLog: (21) misuse at line 106108 of [9491ba7d73]
03-17 07:10:51.335  5277  5307 E SQLiteLog: (21) API call with NULL database connection pointer
03-17 07:10:51.335  3693  3693 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 com.wssyncmldm.XDMService.lllllIIlIIIlIlIIIllI:761 com.wssyncmldm.XDMService.llIIllllIIlllIIIIlll:82 com.wssyncmldm.llIIllllIIlllIIIIlll.handleMessage:1090 
03-17 07:10:51.335  5277  5307 E SQLiteLog: (21) misuse at line 100726 of [9491ba7d73]
03-17 07:10:51.335  5277  5307 E SQLiteLog: (21) API call with NULL database connection pointer
03-17 07:10:51.335  5277  5307 E SQLiteLog: (21) misuse at line 100726 of [9491ba7d73]
03-17 07:10:51.335  3693  3693 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 com.wssyncmldm.XDMService.lllllIIlIIIlIlIIIllI:761 com.wssyncmldm.XDMService.llIIllllIIlllIIIIlll:82 
,03-17 07:10:51.335  5277  5307 E SQLiteLog: (21) API call with NULL database connection pointer
03-17 07:10:51.335  5277  5307 E SQLiteLog: (21) misuse at line 106108 of [9491ba7d73]
03-17 07:10:51.335  5277  5277 W MTPRx   : notification from stack 2
,03-17 07:10:51.335  5277  5312 D         : [mtp_init_device] Library open with 32 bits.
03-17 07:10:51.335  5277  5312 D         : [mtp_init_device] Going to open(): /dev/usb_mtp_gadget
03-17 07:10:51.335  3693  3693 I Timeline: Timeline: Activity_launch_request id:com.wssyncmldm time:53469
,03-17 07:10:51.345  5277  5312 E         : [mtp_init_device 702]  After open the MTP fd = 32 and line = 702...
03-17 07:10:51.345  5277  5312 D         : [mtp_init_device] IOCTL SET_MTP_USER_PID Sucesss 
03-17 07:10:51.345  5277  5312 E         :  [sua_support_present:1287] returning false 
03-17 07:10:51.345  5277  5312 D         : [mtp_init_device] b4 calling MTP_ONLY_ENABLE  ioctl coneect to host
,03-17 07:10:51.345  1022  1902 E PersonaManagerService: inState():  stateMachine is null !!
,03-17 07:10:51.345  1022  1902 I PersonaManagerService: PersonaId don't exist
03-17 07:10:51.345  1022  1902 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
,03-17 07:10:51.345  1022  1902 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,03-17 07:10:51.345  1022  1902 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:51.345  1022  1902 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:51.345  1022  1902 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.wssyncmldm, destAppInfo.processName = com.wssyncmldm
,03-17 07:10:51.345  1022  1902 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.

```
