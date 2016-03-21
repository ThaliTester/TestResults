#### Test 62548124bd1cdb6_thali08_samsung-SM-A300FU Logs


```
--------- beginning of main
03-21 07:32:35.396  1181  1181 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
03-21 07:32:35.416   339  3060 D QC-time-services: Updating the TOD offset
03-21 07:32:35.416   339  3060 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1436214204262 to memory
03-21 07:32:35.416   339  3060 D QC-time-services: Daemon:Opening File: /data/time/ats_1
03-21 07:32:35.416   339  3060 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
03-21 07:32:35.436   339  3060 E QC-time-services: Daemon:Update to modem bit set
03-21 07:32:35.436   339  3060 D QC-time-services: Daemon:genoff_send_modem: Sending data to MODEM !
03-21 07:32:35.436   339  3060 D QC-time-services: Daemon: Base = 2, Value being sent to MODEM = 1120249404262
03-21 07:32:35.436  3040  3040 E QC-time-services: Receive Passed == base = 2, unit = 1, operation = 0, result = 0
03-21 07:32:35.436   339   421 E QC-time-services: Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
03-21 07:32:35.436   339   427 E QC-time-services: Daemon: Time-services: Waiting to acceptconnection
--------- beginning of system
03-21 07:32:35.446  1019  1531 I ActivityManager: Killing 2407:com.sec.modem.settings/1000 (adj 15): empty #31
03-21 07:32:35.456  1662  1697 I art     : Explicit concurrent mark sweep GC freed 8158(392KB) AllocSpace objects, 0(0B) LOS objects, 47% free, 4MB/8MB, paused 1.119ms total 46.090ms
03-21 07:32:35.486  1019  1283 I ActivityManager: Killing 2439:com.sec.tcpdumpservice/1000 (adj 15): empty #31
,03-21 07:32:35.506  1999  1999 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
03-21 07:32:35.526  1999  3019 I GCM     : GCM config loaded
03-21 07:32:35.556  3027  3027 W art     : Verification of void com.sec.android.app.clockpackage.alarm.Alarm.InitAlarmList() took 162.433ms
03-21 07:32:35.556  1019  1805 I ActivityManager: Killing 2448:com.sec.android.app.sbrowser/u0a127 (adj 15): empty #31
03-21 07:32:35.576  1019  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_2407/cgroup.procs: No such file or directory
03-21 07:32:35.576  1019  1283 W ActivityManager: userId = 0, bbcId = -10000
03-21 07:32:35.576  1019  1283 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
03-21 07:32:35.576  1019  1283 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
03-21 07:32:35.616  1019  1564 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-21 07:32:35.616  1019  1564 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4317, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-21 07:32:35.616  1019  1564 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-21 07:32:35.616  1019  1019 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-21 07:32:35.616  1019  1019 I MotionRecognitionService: Plugged
03-21 07:32:35.616  1019  1019 I MotionRecognitionService: mGripSensorEnabled= false
03-21 07:32:35.616  1181  1181 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-21 07:32:35.616  1181  1181 D KeyguardUpdateMonitor: handleBatteryUpdate
03-21 07:32:35.626  1181  1181 D PowerUI : Cable  true --> true mBootCompleted : false
03-21 07:32:35.626  1181  1181 D PowerUI : Sending cableIntent : Intent { act=com.samsung.systemui.power.action.ACTION_CABLE_CONNECTED }
03-21 07:32:35.626  1443  1443 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-21 07:32:35.626  1443  1443 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
03-21 07:32:35.626  1181  1181 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 07:32:35.636  1019  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_2439/cgroup.procs: No such file or directory
03-21 07:32:35.636  1019  1043 W libprocessgroup: failed to open /acct/uid_10127/pid_2448/cgroup.procs: No such file or directory
03-21 07:32:35.646  1019  1571 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:35.646  1019  1571 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:35.646  1019  1571 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:35.646  1019  1571 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:35.646  1181  1181 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 07:32:35.646  1181  1181 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 07:32:35.646  1181  1181 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-21 07:32:35.646  1181  1181 D SViewCoverView: level :100 plugged : 2
03-21 07:32:35.656  3078  3078 E Zygote  : MountEmulatedStorage()
03-21 07:32:35.656  3078  3078 I libpersona: KNOX_SDCARD checking this for 10090
03-21 07:32:35.656  3078  3078 E Zygote  : v2
03-21 07:32:35.656  3078  3078 I libpersona: KNOX_SDCARD not a persona
03-21 07:32:35.656  3078  3078 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-21 07:32:35.656  1019  1571 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=3078 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
03-21 07:32:35.666  3078  3078 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-21 07:32:35.666  3078  3078 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-21 07:32:35.696  3078  3078 D TimaKeyStoreProvider: TimaSignature is unavailable
03-21 07:32:35.696  3078  3078 D ActivityThread: Added TimaKeyStore provider
03-21 07:32:35.706  1999  3019 W art     : Suspending all threads took: 17.635ms
03-21 07:32:35.726  1999  3019 I art     : Explicit concurrent mark sweep GC freed 20215(1299KB) AllocSpace objects, 20(320KB) LOS objects, 40% free, 8MB/14MB, paused 24.436ms total 158.335ms
03-21 07:32:35.726  1019  1044 I ActivityManager: Waited long enough for: ServiceRecord{5fc41b6 u0 com.samsung.hs20settings/.WifiHs20UtilityService}
03-21 07:32:35.726  3078  3078 D elm:15121: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver }
03-21 07:32:35.726  3078  3078 D elm:15121: ELMEngine.ELMEngine( context ).
03-21 07:32:35.726  3078  3078 D elm:15121: MDMBridge.setEnterpriseBridge()
03-21 07:32:35.726  1019  1395 I ActivityManager: Killing 2471:com.sec.android.app.SecSetupWizard/1000 (adj 15): empty #31
03-21 07:32:35.736  1019  1630 W ActivityManager: userId = 0, bbcId = -10000
03-21 07:32:35.736  1019  1630 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-21 07:32:35.736  1019  1630 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
03-21 07:32:35.736  3078  3078 D elm:15121: ELMAbstractReceiver : Receive Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService } END.
03-21 07:32:35.736  1019  1564 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:35.736  1019  1564 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:35.736  1019  1564 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:35.736  1019  1564 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:35.746  3078  3078 D elm:15121: ElmAgentService : onCreate()
03-21 07:32:35.746  3078  3093 D elm:15121: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService }
03-21 07:32:35.756  3078  3093 D elm:15121: ELMAgentService.listeningToTimeDateChanges( context, intent ).
03-21 07:32:35.756  3078  3078 D elm:15121: ELMEngine.ServiceHandler.handleMessage( ALARM_MODIFY ). 
03-21 07:32:35.756  3078  3078 D elm:15121: ModuleBase.ModifySetAlarm()
03-21 07:32:35.756  3078  3078 D elm:15121: MDMBridge.getInstance()
03-21 07:32:35.756  3078  3078 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
03-21 07:32:35.766  3095  3095 E Zygote  : MountEmulatedStorage()
03-21 07:32:35.766  3095  3095 E Zygote  : v2
03-21 07:32:35.766  3095  3095 I libpersona: KNOX_SDCARD checking this for 10130
03-21 07:32:35.766  3095  3095 I libpersona: KNOX_SDCARD not a persona
03-21 07:32:35.766  3095  3095 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-21 07:32:35.766  1019  1564 I ActivityManager: Start proc com.sec.android.widgetapp.SPlannerAppWidget for broadcast com.sec.android.widgetapp.SPlannerAppWidget/.EasyWidget.EasyCalendarAppWidgetProvider: pid=3095 uid=10130 gids={50130, 9997} abi=armeabi-v7a
03-21 07:32:35.766  3095  3095 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-21 07:32:35.776  3095  3095 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
03-21 07:32:35.786  1019  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_2471/cgroup.procs: No such file or directory
03-21 07:32:35.796  3078  3078 D elm:15121: ElmAgentService : onDestroy().
03-21 07:32:35.806  3095  3095 D TimaKeyStoreProvider: TimaSignature is unavailable
03-21 07:32:35.806  3095  3095 D ActivityThread: Added TimaKeyStore provider
03-21 07:32:35.806  1019  1283 I ActivityManager: Killing 2508:com.wsomacp/u0a23 (adj 15): empty #31
03-21 07:32:35.816  3095  3095 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-21 07:32:35.816  3095  3095 W ResourcesManager: Asset path '/system/framework/sws.jar' does not exist or contains no resources.
03-21 07:32:35.826  1019  1283 W ActivityManager: userId = 0, bbcId = -10000
03-21 07:32:35.826  1019  1283 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-21 07:32:35.826  1019  1283 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-21 07:32:35.846  2826  2851 I SA      : [RC New] [v2liruge] api execute + 727
03-21 07:32:35.846  2826  2851 I SA      : [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
03-21 07:32:35.846  2826  2851 I System.out: AsyncTask #1 calls detatch()
03-21 07:32:35.856  2826  2851 I SA      : [ODM] saveOpenData( GEO_IP, PL )
03-21 07:32:35.866  2826  2851 I SA      : [OCP] update openData : PL
03-21 07:32:35.866  2826  2851 I SA      : [TPMU] getNetworkMcc : 
03-21 07:32:35.876  2826  2851 I SA      : [SCU] saveMccToPreferece Start
03-21 07:32:35.876  2826  2851 I SA      : [SCU] RegionMCC : 260
03-21 07:32:35.876  2826  2851 I SA      : [SSP] query invoked
03-21 07:32:35.876  2826  2851 I SA      : [TPMU] GetMccFromDB : null
03-21 07:32:35.876  2826  2851 I SA      : [SCU] getMccFromPreferece mcc = 260
03-21 07:32:35.876  2826  2851 I SA      : [SCU] saveMccToPreferece End
03-21 07:32:35.876  2826  2851 I SA      : [RC New] executeRequest [v2liruge] end. 911
03-21 07:32:35.876  2826  2851 I SA      : [RC New] Execute end
03-21 07:32:35.876  2826  2826 I SA      : [OR] GetMyCountryZoneTask mcc = 260
03-21 07:32:35.876  2826  2826 I SA      : [OR] GetMyCountryZoneTask Success
03-21 07:32:35.886  1019  1561 I splitIntent: Queue : backgroundsplit_0 intent android.intent.action.TIME_SET is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
03-21 07:32:35.886  1019  1561 I ActivityManager: Killing 2531:com.sec.android.gallery3d/u0a39 (adj 15): empty #31
03-21 07:32:35.896  1019  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:35.896  1019  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:35.896  1019  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:35.896  1019  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:35.906  3112  3112 E Zygote  : MountEmulatedStorage()
03-21 07:32:35.906  1019  1044 I ActivityManager: Start proc com.sec.factory for broadcast com.sec.factory/.entry.FactoryTestBroadcastReceiver: pid=3112 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-21 07:32:35.906  3112  3112 E Zygote  : v2
03-21 07:32:35.906  3112  3112 I libpersona: KNOX_SDCARD checking this for 1000
03-21 07:32:35.906  3112  3112 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-21 07:32:35.906  3112  3112 I libpersona: KNOX_SDCARD not a persona
03-21 07:32:35.916  3112  3112 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-21 07:32:35.916  3112  3112 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-21 07:32:35.926  1019  1043 W libprocessgroup: failed to open /acct/uid_10023/pid_2508/cgroup.procs: No such file or directory
03-21 07:32:35.936  3112  3112 D TimaKeyStoreProvider: TimaSignature is unavailable
03-21 07:32:35.936  3112  3112 D ActivityThread: Added TimaKeyStore provider
03-21 07:32:35.946  3112  3112 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
03-21 07:32:36.006  3074  3074 D AndroidRuntime: 
03-21 07:32:36.006  3074  3074 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
03-21 07:32:36.006  3074  3074 D AndroidRuntime: CheckJNI is OFF
03-21 07:32:36.006  3074  3074 D AndroidRuntime: readGMSProperty: start
03-21 07:32:36.006  3074  3074 D AndroidRuntime: readGMSProperty: already setted!!
03-21 07:32:36.006  3074  3074 D AndroidRuntime: propertySet: couldn't set property (it is from app)
03-21 07:32:36.006  3074  3074 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
03-21 07:32:36.006  3074  3074 D AndroidRuntime: readGMSProperty: end
03-21 07:32:36.006  3074  3074 D AndroidRuntime: addProductProperty: start
03-21 07:32:36.026  1019  1283 W ActivityManager: userId = 0, bbcId = -10000
03-21 07:32:36.026  1019  1283 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-21 07:32:36.026  1019  1283 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
03-21 07:32:36.036  1019  1043 W libprocessgroup: failed to open /acct/uid_10039/pid_2531/cgroup.procs: No such file or directory
03-21 07:32:36.046  3112  3112 D FactoryTestApp: [FactoryTestBroadcastReceiver$onReceive](3112) onReceive action=android.intent.action.BOOT_COMPLETED
03-21 07:32:36.066   336   336 I ServiceManager: Waiting for service AtCmdFwd...
03-21 07:32:36.086  3112  3112 W ActivityThread: ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
03-21 07:32:36.096  3112  3112 D FactoryTestApp: [XMLDataStorage$parseXML](3112) is Live Demo : false
03-21 07:32:36.096  3112  3112 D FactoryTestApp: [XMLDataStorage$parseXML](3112) modelXML=sm-a300fu.dat
03-21 07:32:36.096  3112  3112 D FactoryTestApp: [XMLDataStorage$parseXML](3112) deviceXML=a3ulte.dat
03-21 07:32:36.096  3112  3112 D FactoryTestApp: [XMLDataStorage$parseXML](3112) nameXML=a3ultexx.dat
03-21 07:32:36.096  3112  3112 D FactoryTestApp: [XMLDataStorage$parseAsset](3112) parseAsset Is Started
03-21 07:32:36.096  2760  2783 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
03-21 07:32:36.106   305   305 E USB_UICC: Timeout! No signal received. Retry num = 30
03-21 07:32:36.106  3112  3112 I FactoryTestApp: [XMLDataStorage$parseAsset](3112) Convert dat file: sm-a300fu.dat
03-21 07:32:36.126  2760  2783 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
03-21 07:32:36.126  2760  2783 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
03-21 07:32:36.126  2760  2783 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
03-21 07:32:36.126  2760  2783 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
03-21 07:32:36.136  2760  2783 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
03-21 07:32:36.136  2760  2783 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
03-21 07:32:36.136  2760  2783 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
03-21 07:32:36.136  3112  3112 D FactoryTestApp: [XMLDataStorage$parseAsset](3112) Decode base file: factory.dat
03-21 07:32:36.146  2760  2783 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(275/xdmExecResumeCase)] Start resumecase for INIT
03-21 07:32:36.146  1019  1499 I ActivityManager: Killing 2552:com.sec.android.widgetapp.activeapplicationwidget/u0a139 (adj 15): empty #31
03-21 07:32:36.146  2760  2783 I DBG_POLICYDM: [com.policydm.db.XDB(2211/xdbIsAlreadyAgree)] bAgree : true
03-21 07:32:36.156  2760  2783 E DBG_POLICYDM: [com.policydm.db.XDBSpdAdp(36/xdbGetSpdDeviceRegister)] Device is Registered
03-21 07:32:36.176  2760  2783 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
03-21 07:32:36.176  2760  2783 I DBG_POLICYDM: [com.policydm.db.XDB(2176/xdbGetWaitWifiFlag)] bWaitWifi : false
03-21 07:32:36.186  2636  2636 I PCWCLIENTTRACE_SYSTEMReceiver: mConnectivityHandler : connected
03-21 07:32:36.196  2636  3140 W PCWCLIENTTRACE_AccountUtil: [hasSamungAccount] - No Samsung Account
03-21 07:32:36.206   305   305 E USB_UICC: Timeout! No signal received. Reach maximum retries!
03-21 07:32:36.206   305   305 E USB_UICC: usb_uicc_init_qmi failed ! 
03-21 07:32:36.206   305   305 I USB_UICC: usb_uicc_cleanup, signal received: 0x3 
03-21 07:32:36.206   305   305 I USB_UICC: usb_uicc_cleanup, Issuing QMI deinit ... 
03-21 07:32:36.216  1019  1043 W libprocessgroup: failed to open /acct/uid_10139/pid_2552/cgroup.procs: No such file or directory
03-21 07:32:36.256  1019  1531 W ActivityManager: userId = 0, bbcId = -10000
03-21 07:32:36.256  1019  1531 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-21 07:32:36.256  1019  1531 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
03-21 07:32:36.266  3112  3112 D FactoryTestApp: [XMLDataStorage$redefinitionById](3112) id=FACTORY_TEST_APP
03-21 07:32:36.266  3112  3112 D FactoryTestApp: [XMLDataStorage$redefinitionById](3112) id=FACTORY_TEST_COMMAND
03-21 07:32:36.266  3112  3112 D FactoryTestApp: [XMLDataStorage$redefinitionById](3112) id=FAILHIST_VERSION
03-21 07:32:36.266  3112  3112 D FactoryTestApp: [XMLDataStorage$redefinitionById](3112) id=MODEL_NAME
03-21 07:32:36.266  3112  3112 D FactoryTestApp: [XMLDataStorage$redefinitionById](3112) id=MODEL_NUMBER
03-21 07:32:36.266  3112  3112 D FactoryTestApp: [XMLDataStorage$redefinitionById](3112) id=MODEL_HARDWARE_REVISION
03-21 07:32:36.266  3112  3112 D FactoryTestApp: [XMLDataStorage$redefinitionById](3112) id=MODEL_COMMUNICATION_MODE
03-21 07:32:36.266  3112  3112 D FactoryTestApp: [XMLDataStorage$redefinitionById](3112) id=CHIPSET_MANUFACTURE
03-21 07:32:36.266  3112  3112 D FactoryTestApp: [XMLDataStorage$redefinitionById](3112) id=CHIPSET_NAME
03-21 07:32:36.266  3112  3112 D FactoryTestApp: [XMLDataStorage$redefinitionById](3112) id=DEVICE_TYPE
03-21 07:32:36.266  3112  3112 D FactoryTestApp: [XMLDataStorage$redefinitionById](3112) id=BATT_TYPE
03-21 07:32:36.266  3112  3112 D FactoryTestApp: [XMLDataStorage$redefinitionById](3112) id=PANEL_TYPE
03-21 07:32:36.266  3112  3112 D FactoryTestApp: [XMLDataStorage$redefinitionById](3112) id=SENSOR_NAME_ACCELEROMETER
03-21 07:32:36.266  3112  3112 D FactoryTestApp: [XMLDataStorage$redefinitionById](3112) id=SENSOR_NAME_MAGNETIC
03-21 07:32:36.266  3112  3112 D FactoryTestApp: [XMLDataStorage$redefinitionById](3112) id=SENSOR_NAME_GYROSCOPE
03-21 07:32:36.266  3112  3112 D FactoryTestApp: [XMLDataStorage$redefinitionById](3112) id=REAR_CAMERA_TYPE
03-21 07:32:36.266  3112  3112 D FactoryTestApp: [XMLDataStorage$redefinitionById](3112) id=FRONT_CAMERA_TYPE
03-21 07:32:36.266  3112  3112 D FactoryTestApp: [XMLDataStorage$redefinitionById](3112) id=ISP_FLASH_TEST_SMD
03-21 07:32:36.266  3112  3112 D FactoryTestApp: [XMLDataStorage$redefinitionById](3112) id=SPEAKER_COUNT
03-21 07:32:36.266  3112  3112 D FactoryTestApp: [XMLDataStorage$redefinitionById](3112) id=MIC_COUNT
03-21 07:32:36.266  3112  3112 D FactoryTestApp: [XMLDataStorage$redefinitionById](3112) id=TORCH_MODE_FLASH_ON_CURRENT
03-21 07:32:36.266  3112  3112 D FactoryTestApp: [XMLDataStorage$redefinitionById](3112) id=SUPPORT_VIBRATOR
03-21 07:32:36.266  3112  3112 D FactoryTestApp: [XMLDataStorage$redefinitionById](3112) id=SUPPORT_LTE
03-21 07:32:36.266  3112  3112 D FactoryTestApp: [XMLDataStorage$redefinitionById](3112) id=SUPPORT_QWERTY_KEY
03-21 07:32:36.266  3112  3112 D FactoryTestApp: [XMLDataStorage$redefinitionById](3112) id=SUPPORT_FRONT_CAMERA
03-21 07:32:36.266  3112  3112 D FactoryTestApp: [XMLDataStorage$redefinitionById](3112) id=SUPPORT_RCV
03-21 07:32:36.276  3112  3112 D FactoryTestApp: [XMLDataStorage$redefinitionById](3112) id=FACTORY_TEST_APO
03-21 07:32:36.276  3112  3112 D FactoryTestApp: [XMLDataStorage$redefinitionById](3112) id=SUPPORT_BOOST_MEDIASCAN
03-21 07:32:36.276  3112  3112 D FactoryTestApp: [XMLDataStorage$redefinitionById](3112) id=SUPPORT_NVBACKUP_CMD
03-21 07:32:36.276  3112  3112 D FactoryTestApp: [XMLDataStorage$redefinitionById](3112) id=SUPPORT_EPEN
03-21 07:32:36.276  3112  3112 D FactoryTestApp: [XMLDataStorage$redefinitionById](3112) id=SUPPORT_SENSORHUB
03-21 07:32:36.276  3112  3112 D FactoryTestApp: [XMLDataStorage$redefinitionById](3112) id=SUPPORT_CAM_ISP
03-21 07:32:36.276  3112  3112 D FactoryTestApp: [XMLDataStorage$redefinitionById](3112) id=SUPPORT_CAM_FRONT_NOT_ISP
03-21 07:32:36.276  3112  3112 D FactoryTestApp: [XMLDataStorage$redefinitionById](3112) id=SUPPORT_SECOND_MIC_TEST
03-21 07:32:36.276  3112  3112 D FactoryTestApp: [XMLDataStorage$redefinitionById](3112) id=HW_VER_EFS
03-21 07:32:36.276  3112  3112 D FactoryTestApp: [XMLDataStorage$redefinitionById](3112) id=SUPPORT_BOOK_COVER
03-21 07:32:36.276  3112  3112 D FactoryTestApp: [XMLDataStorage$redefinitionById](3112) id=SUPPORT_HOVER_HIGHTLIGHT
03-21 07:32:36.276  3112  3112 D FactoryTestApp: [XMLDataStorage$redefinitionById](3112) id=FACTOLOG_SYSTEM_INFO_UPDATE
03-21 07:32:36.276  3112  3112 D FactoryTestApp: [XMLDataStorage$redefinitionById](3112) id=SUPPORT_AUTO_WAKELOCK
03-21 07:32:36.276  3112  3112 D FactoryTestApp: [XMLDataStorage$redefinitionById](3112) id=SUPPORT_AP_EX_THERM_ADC
03-21 07:32:36.276  3112  3112 D FactoryTestApp: [XMLDataStorage$redefinitionById](3112) id=IS_MULTI_SIM_FRAMEWORK
03-21 07:32:36.276  3112  3112 D FactoryTestApp: [XMLDataStorage$redefinitionById](3112) id=SUPPORT_DSDS_MSIMM_CHECK
03-21 07:32:36.276  3112  3112 D FactoryTestApp: [XMLDataStorage$redefinitionById](3112) id=SUPPORT_DUAL_STANBY_ONE_CP
03-21 07:32:36.276  3112  3112 D FactoryTestApp: [XMLDataStorage$redefinitionById](3112) id=SUPPORT_RUN_REF
03-21 07:32:36.276  3112  3112 D FactoryTestApp: [XMLDataStorage$redefinitionById](3112) id=FONT_SIZE
03-21 07:32:36.276  3112  3112 D FactoryTestApp: [XMLDataStorage$redefinitionById](3112) id=RAM_SIZE_IF
03-21 07:32:36.276  3112  3112 D FactoryTestApp: [XMLDataStorage$redefinitionById](3112) id=MULTI_TSK_THD
03-21 07:32:36.276  3112  3112 D FactoryTestApp: [XMLDataStorage$redefinitionById](3112) id=SEMI_FUNCTION_FONT_SIZE
03-21 07:32:36.276  3112  3112 D FactoryTestApp: [XMLDataStorage$redefinitionById](3112) id=NEED_LPA_MODE_SET
03-21 07:32:36.276  3112  3112 D FactoryTestApp: [XMLDataStorage$redefinitionById](3112) id=SUPPORT_SEMI_FUNCTION_TEST
03-21 07:32:36.286  3112  3112 D FactoryTestApp: [XMLDataStorage$redefinitionById](3112) id=SEMI_FUNCTION_TEST_UI_ORIENTATION
03-21 07:32:36.286  3112  3112 D FactoryTestApp: [XMLDataStorage$redefinitionById](3112) id=SUPPORT_SEMI_NV_RESET
03-21 07:32:36.286  2636  3140 I PCWCLIENTTRACE_SecurePreferencesJNI: [GetString-S]
03-21 07:32:36.286  3112  3112 D FactoryTestApp: [XMLDataStorage$redefinitionById](3112) id=BOOT_CHECK_TOUCHKEY_WO_SVCLED
03-21 07:32:36.286  3112  3112 D FactoryTestApp: [XMLDataStorage$redefinitionById](3112) id=SUPPORT_SELFTEST_DISPLAY_DELAY
03-21 07:32:36.286  3112  3112 D FactoryTestApp: [XMLDataStorage$redefinitionById](3112) id=KEY_TEST_VOLUME_UP
03-21 07:32:36.286  2636  3140 I ReactiveServiceManager: Supported : 1
03-21 07:32:36.296  3112  3112 D FactoryTestApp: [XMLDataStorage$redefinitionById](3112) id=KEY_TEST_VOLUME_DOWN
03-21 07:32:36.306  3112  3112 D FactoryTestApp: [XMLDataStorage$redefinitionById](3112) id=KEY_TEST_POWER
03-21 07:32:36.316  1019  1804 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x2040
03-21 07:32:36.316  1019  1804 D QSEECOMAPI: : App is not loaded in QSEE
03-21 07:32:36.316  3112  3112 D FactoryTestApp: [XMLDataStorage$redefinitionById](3112) id=KEY_TEST_APP_RECENT
03-21 07:32:36.316  3112  3112 D FactoryTestApp: [XMLDataStorage$redefinitionById](3112) id=KEY_TEST_HOME
03-21 07:32:36.326  3112  3112 D FactoryTestApp: [XMLDataStorage$redefinitionById](3112) id=KEY_TEST_BACK
03-21 07:32:36.326  1019  1804 D QSEECOMAPI: : Loaded image: APP id = 9
03-21 07:32:36.336  3112  3112 D FactoryTestApp: [XMLDataStorage$redefinitionById](3112) id=KEY_TEST_TOUCH_KEY_ODER
03-21 07:32:36.336  3112  3112 D FactoryTestApp: [XMLDataStorage$redefinitionById](3112) id=KEY_TEST_VIEW_TABLE
03-21 07:32:36.336  1019  1804 D QSEECOMAPI: : QSEECom_dealloc_memory 
03-21 07:32:36.336  1019  1804 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 9
03-21 07:32:36.336  1019  1804 E terrier : handleString: Failed to handle string(-4)
03-21 07:32:36.336  1019  1804 E terrier : Java_com_android_server_ReactiveService_GetString: error code = [-4]
03-21 07:32:36.336  2636  3140 D PCWCLIENTTRACE_SecurePreferencesJNI: getString is null
03-21 07:32:36.336  2636  3140 I PCWCLIENTTRACE_SecurePreferencesJNI: [GetString-E]
03-21 07:32:36.336  2636  3140 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
03-21 07:32:36.346  2636  3140 I PCWCLIENTTRACE_PushUtil: sales region : global
03-21 07:32:36.346  3112  3112 D FactoryTestApp: [XMLDataStorage$redefinitionById](3112) id=SEMI_KEY_TEST_VOLUME_UP
03-21 07:32:36.346  2636  3140 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
03-21 07:32:36.346  2636  3140 E PCWCLIENTTRACE_PCWHandler: [ensureRegistration] - No Samsung account
03-21 07:32:36.356  3112  3112 D FactoryTestApp: [XMLDataStorage$redefinitionById](3112) id=SEMI_KEY_TEST_VOLUME_DOWN
03-21 07:32:36.356  3112  3112 D FactoryTestApp: [XMLDataStorage$redefinitionById](3112) id=SEMI_KEY_TEST_HOME
03-21 07:32:36.376  3112  3112 D FactoryTestApp: [XMLDataStorage$redefinitionById](3112) id=IS_KEY_TEST_THRESHOLD
03-21 07:32:36.376  3112  3112 D FactoryTestApp: [XMLDataStorage$redefinitionById](3112) id=IS_TSP_STANDARD_CHANNEL
03-21 07:32:36.376  3112  3112 D FactoryTestApp: [XMLDataStorage$redefinitionById](3112) id=IS_SENSOR_TEST_ACC_REVERSE
03-21 07:32:36.376  3112  3112 D FactoryTestApp: [XMLDataStorage$redefinitionById](3112) id=IS_PROXIMITY_TEST_MOTOR_FEEDBACK
03-21 07:32:36.386  3112  3112 D FactoryTestApp: [XMLDataStorage$redefinitionById](3112) id=SUPPORT_GEOMAGNETIC_ALPS_CAL
03-21 07:32:36.386  3112  3112 D FactoryTestApp: [XMLDataStorage$redefinitionById](3112) id=GEOMAGNETIC_IC_POINT
03-21 07:32:36.386  3112  3112 D FactoryTestApp: [XMLDataStorage$redefinitionById](3112) id=SENSOR_TEST_ACC_BIT
03-21 07:32:36.386  3112  3112 D FactoryTestApp: [XMLDataStorage$redefinitionById](3112) id=G_VECTOR_SUM_ACC_BIT
03-21 07:32:36.396  3112  3112 D FactoryTestApp: [XMLDataStorage$redefinitionById](3112) id=IS_VIBETONZ_UNSUPPORTED
03-21 07:32:36.396  3112  3112 D FactoryTestApp: [XMLDataStorage$redefinitionById](3112) id=AT_GPSSTEST
03-21 07:32:36.396  3112  3112 D FactoryTestApp: [XMLDataStorage$redefinitionById](3112) id=AT_BATTEST_RESET_WHEN_READ
03-21 07:32:36.396  3112  3112 D FactoryTestApp: [XMLDataStorage$redefinitionById](3112) id=SUPPORT_CHARGE_COUNT
03-21 07:32:36.406  3112  3112 D FactoryTestApp: [XMLDataStorage$redefinitionById](3112) id=PA0_TEMP_ADC
03-21 07:32:36.406  3112  3112 D FactoryTestApp: [XMLDataStorage$redefinitionById](3112) id=PA1_TEMP_ADC
03-21 07:32:36.406  3112  3112 D FactoryTestApp: [XMLDataStorage$redefinitionById](3112) id=NEED_ACK_FOR_CAMERA_STOP
03-21 07:32:36.406  3112  3112 D FactoryTestApp: [XMLDataStorage$redefinitionById](3112) id=HALL_IC_TEST
03-21 07:32:36.416  3074  3074 E AffinityControl: AffinityControl: registerfunction enter
03-21 07:32:36.416  3112  3112 D FactoryTestApp: [XMLDataStorage$redefinitionById](3112) id=IS_NEW_TSP_SELFTEST_SYNAPTICS
03-21 07:32:36.416  3112  3112 D FactoryTestApp: [XMLDataStorage$redefinitionById](3112) id=IS_TSP_HOVERING_TEST_SET_EDGE_DEADLOCK
03-21 07:32:36.426  3112  3112 D FactoryTestApp: [XMLDataStorage$redefinitionById](3112) id=READ_TARGET_GEOMAGNETIC
03-21 07:32:36.426  3112  3112 D FactoryTestApp: [XMLDataStorage$redefinitionById](3112) id=SYS_INFO_FONT_SIZE
03-21 07:32:36.426  3112  3112 D FactoryTestApp: [XMLDataStorage$redefinitionById](3112) id=SYS_INFO_MEMORY_SIZE
03-21 07:32:36.426  3112  3112 D FactoryTestApp: [XMLDataStorage$redefinitionById](3112) id=SYS_INFO_MODEL_NAME
03-21 07:32:36.436  3112  3112 D FactoryTestApp: [XMLDataStorage$redefinitionById](3112) id=TSP_NODE_COUNT_WIDTH
03-21 07:32:36.436  3112  3112 D FactoryTestApp: [XMLDataStorage$redefinitionById](3112) id=TSP_NODE_COUNT_HEIGHT
03-21 07:32:36.436  3112  3112 D FactoryTestApp: [XMLDataStorage$redefinitionById](3112) id=TSP_SELFTEST_SPEC_MAX_MINUS_MIN
03-21 07:32:36.436  3112  3112 D FactoryTestApp: [XMLDataStorage$redefinitionById](3112) id=TSP_SELFTEST_MIN_ZINITIX
03-21 07:32:36.436  3112  3112 D FactoryTestApp: [XMLDataStorage$redefinitionById](3112) id=TSP_SELFTEST_MAX_ZINITIX
03-21 07:32:36.446  3112  3112 D FactoryTestApp: [XMLDataStorage$redefinitionById](3112) id=TOUCH_KEY_SPEC_MIN
03-21 07:32:36.446  3112  3112 D FactoryTestApp: [XMLDataStorage$redefinitionById](3112) id=TOUCH_KEY_SPEC_MAX
03-21 07:32:36.446  3112  3112 D FactoryTestApp: [XMLDataStorage$redefinitionById](3112) id=BOOTLOADER_VERSION
03-21 07:32:36.456  3112  3112 D FactoryTestApp: [XMLDataStorage$redefinitionById](3112) id=BATTERY_TEST_MODE
03-21 07:32:36.456  3074  3074 D AndroidRuntime: Calling main entry com.android.commands.am.Am
03-21 07:32:36.456  3112  3112 D FactoryTestApp: [XMLDataStorage$redefinitionById](3112) id=BATTERY_VOLT_AVER
03-21 07:32:36.456  3112  3112 D FactoryTestApp: [XMLDataStorage$redefinitionById](3112) id=BATTERY_VF_OCV
03-21 07:32:36.466  3112  3112 D FactoryTestApp: [XMLDataStorage$redefinitionById](3112) id=PA0_THERMISTER_CELCIUS
03-21 07:32:36.466  3112  3112 D FactoryTestApp: [XMLDataStorage$redefinitionById](3112) id=SEC_EXT_THERMISTER_TEMP
03-21 07:32:36.466  3112  3112 D FactoryTestApp: [XMLDataStorage$redefinitionById](3112) id=PA0_THERMISTER_ADC
03-21 07:32:36.476  1019  1561 E PersonaManagerService: inState():  stateMachine is null !!
03-21 07:32:36.476  1019  1561 I PersonaManagerService: PersonaId don't exist
03-21 07:32:36.476  1019  1561 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
03-21 07:32:36.476  3112  3112 D FactoryTestApp: [XMLDataStorage$redefinitionById](3112) id=PA1_THERMISTER_ADC
03-21 07:32:36.476  1019  1561 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-21 07:32:36.476  3112  3112 D FactoryTestApp: [XMLDataStorage$redefinitionById](3112) id=PA0_THERMISTER_CELCIUS
03-21 07:32:36.486  3112  3112 D FactoryTestApp: [XMLDataStorage$redefinitionById](3112) id=TSP_COMMAND_CMD
03-21 07:32:36.486  3112  3112 D FactoryTestApp: [XMLDataStorage$redefinitionById](3112) id=TSP_COMMAND_STATUS
03-21 07:32:36.486  1019  1561 W ActivityManager: mDVFSHelper.acquire()
03-21 07:32:36.496  3112  3112 D FactoryTestApp: [XMLDataStorage$redefinitionById](3112) id=TSP_COMMAND_RESULT
03-21 07:32:36.496  1019  1561 D FocusedStackFrame: Set to : 0
03-21 07:32:36.496  3112  3112 D FactoryTestApp: [XMLDataStorage$redefinitionById](3112) id=PATH_HALLIC_STATE
03-21 07:32:36.496  1019  1561 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
03-21 07:32:36.496  1019  1561 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-21 07:32:36.496  1019  1561 D InputDispatcher: Focused application set to: xxxx
03-21 07:32:36.496  1019  1561 D InputDispatcher: Focus left window: 1507
03-21 07:32:36.496  3074  3074 D AndroidRuntime: Shutting down VM
03-21 07:32:36.496  3112  3112 D FactoryTestApp: [XMLDataStorage$redefinitionById](3112) id=KEY_PRESSED_POWER
03-21 07:32:36.496  1019  1049 D PhoneWindow: *FMB* installDecor mIsFloating : false
03-21 07:32:36.496  1019  1049 D PhoneWindow: *FMB* installDecor flags : -2122120936
03-21 07:32:36.506  1507  1507 D Launcher.HomeView: onPause
03-21 07:32:36.506  1507  1507 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
03-21 07:32:36.506  1019  1049 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-21 07:32:36.506  1019  1049 D PointerIcon: setMouseCustomIcon IconType is same.101
03-21 07:32:36.516  1019  1049 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
03-21 07:32:36.516  1019  1049 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
03-21 07:32:36.516  3112  3112 D FactoryTestApp: [XMLDataStorage$redefinitionById](3112) id=APCHIP_TEMP_ADC
03-21 07:32:36.516   259   259 I SurfaceFlinger: id=11 createSurf (1x1),1 flag=404, uhalitest
03-21 07:32:36.516  1019  1809 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:36.516  1019  1809 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:36.516  1019  1809 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:36.516  1019  1809 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:36.516  3112  3112 D FactoryTestApp: [XMLDataStorage$redefinitionById](3112) id=HUMITEMP_THERMISTER_PAM
03-21 07:32:36.516  3112  3112 D FactoryTestApp: [XMLDataStorage$redefinitionById](3112) id=HUMITEMP_THERMISTER_BATT
03-21 07:32:36.526  3112  3112 D FactoryTestApp: [XMLDataStorage$redefinitionById](3112) id=HUMITEMP_THERMISTER_BATT_CELCIUS
03-21 07:32:36.526  3112  3112 D FactoryTestApp: [XMLDataStorage$redefinitionById](3112) id=HUMITEMP_THERMISTER_S_HUB_BATT
03-21 07:32:36.526  3112  3112 D FactoryTestApp: [XMLDataStorage$redefinitionById](3112) id=HUMITEMP_THERMISTER_S_HUB_BATT_CELCIUS
03-21 07:32:36.536  3153  3153 E Zygote  : MountEmulatedStorage()
03-21 07:32:36.536  3153  3153 E Zygote  : v2
03-21 07:32:36.536  3153  3153 I libpersona: KNOX_SDCARD checking this for 10167
03-21 07:32:36.536  3153  3153 I libpersona: KNOX_SDCARD not a persona
03-21 07:32:36.536  3112  3112 D FactoryTestApp: [XMLDataStorage$redefinitionById](3112) id=LPA_MODE_SET
03-21 07:32:36.536  3153  3153 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-21 07:32:36.536  1019  1809 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3153 uid=10167 gids={50167, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
03-21 07:32:36.536  3153  3153 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-21 07:32:36.536  3112  3112 D FactoryTestApp: [XMLDataStorage$redefinitionById](3112) id=GEOMAGNETIC_SENSOR_ADC
03-21 07:32:36.536  3153  3153 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
03-21 07:32:36.546  3112  3112 D FactoryTestApp: [XMLDataStorage$redefinitionById](3112) id=GEOMAGNETIC_SENSOR_POWER
03-21 07:32:36.546  3112  3112 D FactoryTestApp: [XMLDataStorage$parseAsset](3112) SemiFunctionMenu
03-21 07:32:36.556  3112  3112 D FactoryTestApp: [XMLDataStorage$parseAsset](3112) parseAsset Is Completed
03-21 07:32:36.566  3112  3112 D FactoryTestApp: [Support$Values.getString](3112) id=EFS_FACTORYAPP_ROOT_PATH, path=/efs/FactoryApp/
03-21 07:32:36.566  3153  3153 D TimaKeyStoreProvider: TimaSignature is unavailable
03-21 07:32:36.566  1507  1507 V ActivityThread: updateVisibility : ActivityRecord{3354a8cf token=android.os.BinderProxy@35ba7ed1 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
03-21 07:32:36.566  3153  3153 D ActivityThread: Added TimaKeyStore provider
03-21 07:32:36.566  3112  3112 D FactoryTestApp: [Support$Values.getString](3112) id=CHIPSET_MANUFACTURE, value=Qualcomm
03-21 07:32:36.566  3112  3112 I FactoryTestApp: [ModuleCommon$ModuleCommon](3112) Create ModuleCommon
03-21 07:32:36.566  1019  1531 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
03-21 07:32:36.566  1019  1531 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
03-21 07:32:36.566  1019  1531 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
03-21 07:32:36.576  3112  3112 D FactoryTestApp: [Support$Values.getString](3112) id=FACTORY_MODE, path=/efs/FactoryApp/factorymode
03-21 07:32:36.576  1507  1507 D Launcher.HomeView: onStop
03-21 07:32:36.576  1507  1507 V ActivityThread: updateVisibility : ActivityRecord{3354a8cf token=android.os.BinderProxy@35ba7ed1 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
03-21 07:32:36.576  3112  3112 D FactoryTestApp: [Support$Kernel.read](3112) path=/efs/FactoryApp/factorymode, value=ON
03-21 07:32:36.576  3112  3112 I FactoryTestApp: [ModuleCommon$readFactoryMode](3112) mode: ON
03-21 07:32:36.576  3112  3112 D FactoryTestApp: [Support$Values.getString](3112) id=KEYSTRING_BLOCK, path=/efs/FactoryApp/keystr
03-21 07:32:36.576  3112  3112 D FactoryTestApp: [FactoryTestBroadcastReceiver$onReceive](3112) KEYSTRING_BLOCK is already existed...
03-21 07:32:36.576  3112  3112 D FactoryTestApp: [Support$Values.getString](3112) id=KEYSTRING_BLOCK, path=/efs/FactoryApp/keystr
03-21 07:32:36.576  3112  3112 D FactoryTestApp: [Support$Values.getBoolean](3112) id=INBATT_SAVE_SOC, value=false
03-21 07:32:36.576  1019  1047 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
03-21 07:32:36.586  3112  3112 D FactoryTestApp: [Support$Values.getString](3112) id=BINARY_TYPE, key=ro.factory.factory_binary
03-21 07:32:36.586  3112  3112 D FactoryTestApp: [Support$Properties.get](3112) property=ro.factory.factory_binary
03-21 07:32:36.586  3112  3112 D FactoryTestApp: [FactoryTestBroadcastReceiver$onReceive](3112) Boot completed, IS_FACTORY_BINARY = USER MODE
03-21 07:32:36.586  1019  1531 D PersonaManager: isKioskContainerExistOnDevice
03-21 07:32:36.586  3112  3112 I FactoryTestApp: [ModuleCommon$getFtClientEnableState](3112) result : false
03-21 07:32:36.586  3112  3112 I FactoryTestApp: [ModuleCommon$connectedJIG](3112) ...
03-21 07:32:36.586  3112  3112 D FactoryTestApp: [Support$Values.getString](3112) id=ANYWAY_JIG_CABLE_TYPE, value=ANYWAY_JIG
03-21 07:32:36.586  3112  3112 I FactoryTestApp: [ModuleCommon$connectedJIG](3112) cable_type = ANYWAY_JIG
03-21 07:32:36.596  3112  3112 D FactoryTestApp: [Support$Values.getString](3112) id=ANYWAY_JIG, path=/sys/class/sec/switch/adc
03-21 07:32:36.596  3112  3112 D FactoryTestApp: [Support$Values.getString](3112) id=ANYWAY_JIG, path=/sys/class/sec/switch/adc
03-21 07:32:36.596  3112  3112 D FactoryTestApp: [Support$Kernel.read](3112) path=/sys/class/sec/switch/adc, value=1f
03-21 07:32:36.596  3112  3112 I FactoryTestApp: [ModuleCommon$connectedJIG](3112) value = 1f, JIG_ON = 1C
03-21 07:32:36.596  3112  3112 D FactoryTestApp: [Support$Values.getString](3112) id=MODEL_COMMUNICATION_MODE, value=gsm
03-21 07:32:36.596  3112  3112 I FactoryTestApp: [ModuleCommon$isConnectionModeNone](3112) mConnectionMode = gsm
03-21 07:32:36.596  3112  3112 I FactoryTestApp: [ModuleCommon$isRunningFtClient](3112) RUNNING_FTCLIENT : false
03-21 07:32:36.596  3112  3112 I FactoryTestApp: [FactoryTestBroadcastReceiver$startDummyFtClientForBootCompleted](3112) start DummyFtClient service for APO
03-21 07:32:36.596  3112  3112 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.factory.entry.FactoryTestBroadcastReceiver.startDummyFtClientForBootCompleted:345 com.sec.factory.entry.FactoryTestBroadcastReceiver.onReceive:192 
03-21 07:32:36.606  1019  1804 W ActivityManager: userId = 0, bbcId = -10000
03-21 07:32:36.606  1019  1804 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-21 07:32:36.606  1019  1804 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.factory, destAppInfo.processName = com.sec.factory
03-21 07:32:36.606  3112  3112 D FactoryTest: User mode
03-21 07:32:36.606  3112  3112 I FactoryTestApp: [ModuleCommon$disableFtClient](3112) ...
03-21 07:32:36.616  3112  3112 D FactoryTestApp: [DummyFtClient$onCreate](3112) Create DummyFtClient service
03-21 07:32:36.616  3112  3112 I FactoryTestApp: [XMLDataStorage$parsingXML](3112) FtClient => data parsing was completed.
03-21 07:32:36.616  3112  3112 D FactoryTestApp: [DummyFtClient$onReceive](3112) ACTION_SIM_STATE_CHANGED => XML data parsing was failed.
03-21 07:32:36.616  3112  3112 D FactoryTestApp: [Support$Values.getString](3112) id=MODEL_COMMUNICATION_MODE, value=gsm
03-21 07:32:36.616  3112  3112 I FactoryTestApp: [ModuleCommon$isConnectionModeNone](3112) mConnectionMode = gsm
03-21 07:32:36.616  1507  1507 D Launcher: onTrimMemory. Level: 20
03-21 07:32:36.626  3112  3112 D FactoryTestApp: [Support$Values.getBoolean](3112) id=SUPPORT_AUTO_WAKELOCK, value=false
03-21 07:32:36.626  3112  3112 D FactoryTestApp: [DummyFtClient$onStartCommand](3112) ...
03-21 07:32:36.636  1019  1048 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
03-21 07:32:36.636  1019  1048 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
03-21 07:32:36.636  1019  1048 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:36.636  1019  1048 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:36.636  1019  1048 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:36.636  1019  1048 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:36.646  3170  3170 E Zygote  : MountEmulatedStorage()
03-21 07:32:36.646  3170  3170 E Zygote  : v2
03-21 07:32:36.646  3170  3170 I libpersona: KNOX_SDCARD checking this for 1002
03-21 07:32:36.646  3170  3170 I libpersona: KNOX_SDCARD not a persona
03-21 07:32:36.656  3170  3170 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-21 07:32:36.656  1019  1048 I ActivityManager: Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=3170 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
03-21 07:32:36.656  3170  3170 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-21 07:32:36.656  3170  3170 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-21 07:32:36.666  1019  1019 I WifiService: android.intent.action.BOOT_COMPLETED
03-21 07:32:36.666  1019  3169 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:36.666  1019  3169 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:36.666  1019  3169 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:36.666  1019  3169 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:36.686  3184  3184 E Zygote  : MountEmulatedStorage()
03-21 07:32:36.686  3184  3184 E Zygote  : v2
03-21 07:32:36.686  3184  3184 I libpersona: KNOX_SDCARD checking this for 1000
03-21 07:32:36.686  3184  3184 I libpersona: KNOX_SDCARD not a persona
03-21 07:32:36.686  3184  3184 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-21 07:32:36.686  1019  3169 I ActivityManager: Start proc com.android.keychain for service com.android.keychain/.KeyChainService: pid=3184 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-21 07:32:36.686  3184  3184 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-21 07:32:36.686  3184  3184 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-21 07:32:36.696  1019  1019 D UsbDeviceManager: boot completed
03-21 07:32:36.696  1019  1046 D UsbDeviceManager: handleMessage -> MSG_BOOT_COMPLETED
03-21 07:32:36.696  1019  1046 D UsbDeviceManager: sending intent : ACTION_USB_CABLE_STATE : connected = true
03-21 07:32:36.696  1019  1046 D UsbDeviceManager: broadcasting Intent { act=android.hardware.usb.action.USB_STATE flg=0x20000000 (has extras) } connected: true configured: true
03-21 07:32:36.696  1019  1046 D UsbDeviceManager: sending intent : ACTION_USB_STATE : connected = true, configured = true, functions = mtp,adb
03-21 07:32:36.716  3074  3074 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
03-21 07:32:36.716  3170  3170 D TimaKeyStoreProvider: TimaSignature is unavailable
03-21 07:32:36.716  3170  3170 D ActivityThread: Added TimaKeyStore provider
03-21 07:32:36.716  1181  1181 I KeyguardEffectViewUtil: set resource id
03-21 07:32:36.726  1019  1561 D SettingsProvider: name = keyguard_default_wallpaper_res_id
03-21 07:32:36.726  1019  1561 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-21 07:32:36.726  1019  1561 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-21 07:32:36.726  1019  1561 D SettingsProvider: selectionArgs: false
03-21 07:32:36.726  1019  1561 D SettingsProvider: selectionArgs: 10049
03-21 07:32:36.726  1019  1561 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-21 07:32:36.726  1019  1561 D SettingsProvider: ret = -1
03-21 07:32:36.726  1019  1019 I PalmMotion: [PALM] 2014 - SURFACE_MOTION_ENGINE: 1 MOTION_MERGED_MUTE_PAUSE & SURFACE_PALM_TOUCH: 1
03-21 07:32:36.726  1019  1019 I PalmMotion: [PALM] SURFACE_PALM_SWIPE: 1
03-21 07:32:36.726  1019  1019 D PalmMotion: [PALM] SETTINGS : [TOUCH: true] [SWEEP: true]
03-21 07:32:36.726  1019  1019 E MotionRecognitionService:   mReceiver.onReceive : ACTION_USER_PRESENT  :: UNLOCK SCREEN
03-21 07:32:36.726  1019  1019 D PalmMotion: [PALM] ACCEPTED : [a3ulte_common] PALM_CNT : 2, M_TOUCH : 1000.0, M_SWEEP : 100.0, E_SWEEP : 2.0, IGNORE_M_SWEEP : false
03-21 07:32:36.726  1019  1019 D LightsService: [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 1019) 
03-21 07:32:36.726  1181  1181 D KeyguardUpdateMonitor: received broadcast android.intent.action.BOOT_COMPLETED
03-21 07:32:36.726  1019  1019 D LightsService: [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
03-21 07:32:36.726  1181  1181 D KeyguardUpdateMonitor: handleBootCompleted()
03-21 07:32:36.726  1181  1181 D KeyguardUpdateMonitor: handleBootCompleted()
03-21 07:32:36.726  1019  1078 D LightsService: [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
03-21 07:32:36.726  1019  1078 D LightsService: [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
03-21 07:32:36.726  3184  3184 D TimaKeyStoreProvider: TimaSignature is unavailable
03-21 07:32:36.736  3184  3184 D ActivityThread: Added TimaKeyStore provider
,03-21 07:32:36.736  1019  1283 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
,03-21 07:32:36.746  1019  3191 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-21 07:32:36.746  1019  3191 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-21 07:32:36.746  1859  1859 D SamsungIME: showDlgMsgBox : false true true
,03-21 07:32:36.756  1468  3204 D NfcService: call the applyRouting
,03-21 07:32:36.756  3153  3153 I WebViewFactory: Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,03-21 07:32:36.766  3170  3170 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
03-21 07:32:36.766  3170  3170 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,03-21 07:32:36.776  3153  3153 I LibraryLoader: Loading: webviewchromium
,03-21 07:32:36.776  1019  3191 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-21 07:32:36.776  3153  3153 I LibraryLoader: Time to load native libraries: 6 ms (timestamps 6919-6925)
,03-21 07:32:36.776  3153  3153 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-21 07:32:36.776  1019  3191 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-21 07:32:36.826  3153  3153 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {19a598a0}
,03-21 07:32:36.826  3153  3153 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-21 07:32:36.826  3153  3153 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,03-21 07:32:36.836  3170  3170 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,03-21 07:32:36.836  3184  3196 E File    : fail readDirectory() errno=2
,03-21 07:32:36.856  1019  1561 W ActivityManager: userId = 0, bbcId = -10000
,03-21 07:32:36.856  1019  1561 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-21 07:32:36.856  1019  1561 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.contacts, destAppInfo.processName = com.android.contacts
,03-21 07:32:36.856  1019  3208 I RecoverySystem: !@RecoverySystem handleAftermath
,03-21 07:32:36.856  1019  3208 I RecoverySystem: No recovery log file
,03-21 07:32:36.866  3153  3153 I BrowserStartupController: Initializing chromium process, renderers=0
,03-21 07:32:36.866  3153  3153 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-21 07:32:36.866  1019  3208 E RecoverySystem: Error copy recovery logs : /cache/recovery/last_last_kernel: open failed: ENOENT (No such file or directory)
,03-21 07:32:36.866  1019  3208 E RecoverySystem: Error copy recovery logs : /cache/recovery/last_recovery_contents: open failed: ENOENT (No such file or directory)
03-21 07:32:36.876  1019  3208 E RecoverySystem: Error copy recovery logs : /cache/recovery/last_history: open failed: ENOENT (No such file or directory)
,03-21 07:32:36.876  3170  3170 D BtSettings.ProfileConfig: Adding GattService
,03-21 07:32:36.886  3170  3170 D BtSettings.ProfileConfig: Adding HeadsetService
,03-21 07:32:36.886  3170  3170 D BtSettings.ProfileConfig: Adding A2dpService
03-21 07:32:36.886  3170  3170 D BtSettings.ProfileConfig: Adding HidService
03-21 07:32:36.886  3170  3170 D BtSettings.ProfileConfig: Adding HealthService
03-21 07:32:36.886  3170  3170 D BtSettings.ProfileConfig: Adding PanService
03-21 07:32:36.886  3170  3170 D BtSettings.ProfileConfig: Adding BluetoothMapService
,03-21 07:32:36.886  3170  3170 D BtSettings.ProfileConfig: Adding SapService
03-21 07:32:36.886  3170  3170 D BtSettings.ProfileConfig: Adding HeadsetClientService
03-21 07:32:36.886  3170  3170 D BtSettings.ProfileConfig: Adding A2dpSinkService
03-21 07:32:36.886  3170  3170 D BtSettings.ProfileConfig: Adding SapClientService
,03-21 07:32:36.886  3170  3170 D BtSettings.ProfileConfig: Adding HidDevService
03-21 07:32:36.886  3170  3170 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,03-21 07:32:36.886  1488  1488 V OtaStartupReceiver: onOtaspChanged: mOtaspMode=1
,03-21 07:32:36.886  1019  1804 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
03-21 07:32:36.886  1019  1804 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-21 07:32:36.886  1019  1804 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-21 07:32:36.886  1019  1804 D SettingsProvider: selectionArgs: false
03-21 07:32:36.886  1019  1804 D SettingsProvider: selectionArgs: 1002
03-21 07:32:36.886  1019  1804 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-21 07:32:36.886  1019  1804 D SettingsProvider: ret = -1
,03-21 07:32:36.896  1019  1571 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:36.896  1019  1571 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:36.896  1019  1571 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:36.896  1019  1571 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 07:32:36.906  3217  3217 E Zygote  : MountEmulatedStorage(),
03-21 07:32:36.906  3217  3217 E Zygote  : v2
03-21 07:32:36.906  3217  3217 I libpersona: KNOX_SDCARD checking this for 1001,
03-21 07:32:36.906  3217  3217 I libpersona: KNOX_SDCARD not a persona,
03-21 07:32:36.906  3217  3217 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-21 07:32:36.916  3153  3153 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty(),
,03-21 07:32:36.916  3153  3153 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=36 off=46768 len=2953,
,03-21 07:32:36.916  3217  3217 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-21 07:32:36.916  1019  1804 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=1002
03-21 07:32:36.916  3153  3153 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:37 off:229524 len:643667
03-21 07:32:36.916  3217  3217 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-21 07:32:36.916  1019  3191 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,03-21 07:32:36.926  1019  1571 I ActivityManager: Start proc com.sec.phone for broadcast com.sec.phone/.BootCompleteReceiver: pid=3217 uid=1001 gids={41001, 9997, 1007, 1028, 1015, 3002, 3001, 3003, 1035, 1023, 3006} abi=armeabi-v7a
,03-21 07:32:36.926  1019  1031 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
03-21 07:32:36.926  1019  1031 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-21 07:32:36.926  1019  1031 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-21 07:32:36.926  1019  1031 D SettingsProvider: selectionArgs: false
03-21 07:32:36.926  1019  1031 D SettingsProvider: selectionArgs: 1002
03-21 07:32:36.926  1019  1031 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-21 07:32:36.926  1019  1031 D SettingsProvider: ret = -1
,03-21 07:32:36.926  1019  3191 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-21 07:32:36.936  1019  3191 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-21 07:32:36.936  1019  1031 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,03-21 07:32:36.936  1019  1804 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
03-21 07:32:36.936  1019  1804 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-21 07:32:36.936  1019  1804 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-21 07:32:36.936  1019  1804 D SettingsProvider: selectionArgs: false
03-21 07:32:36.936  1019  1804 D SettingsProvider: selectionArgs: 1002
03-21 07:32:36.936  1019  1804 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-21 07:32:36.936  1019  1804 D SettingsProvider: ret = -1
,03-21 07:32:36.936  3153  3216 D BluetoothAdapter: 197323865: getState() :  mService = null. Returning STATE_OFF
,03-21 07:32:36.946  1181  1181 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-21 07:32:36.946  1019  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:36.946  1019  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:36.946  1019  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:36.946  1019  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 07:32:36.946  1019  1804 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,03-21 07:32:36.966  3153  3153 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
03-21 07:32:36.966  3153  3153 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
03-21 07:32:36.966  3153  3153 I Adreno-EGL: Build Date: 04/06/15 Mon
03-21 07:32:36.966  3153  3153 I Adreno-EGL: Local Branch: 
03-21 07:32:36.966  3153  3153 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
03-21 07:32:36.966  3153  3153 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
,03-21 07:32:36.966  3153  3153 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,03-21 07:32:36.966  3238  3238 E Zygote  : MountEmulatedStorage(),
03-21 07:32:36.966  3238  3238 I libpersona: KNOX_SDCARD checking this for 10039
03-21 07:32:36.966  3238  3238 E Zygote  : v2
03-21 07:32:36.966  3238  3238 I libpersona: KNOX_SDCARD not a persona,
03-21 07:32:36.966  3238  3238 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-21 07:32:36.966  3238  3238 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-21 07:32:36.966  3238  3238 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-21 07:32:36.986  1019  1043 I ActivityManager: Start proc com.sec.android.gallery3d for service com.sec.android.gallery3d/.remote.picasa.PicasaService: pid=3238 uid=10039 gids={50039, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
03-21 07:32:36.986  3217  3217 D TimaKeyStoreProvider: TimaSignature is unavailable
03-21 07:32:36.986  3217  3217 D ActivityThread: Added TimaKeyStore provider
03-21 07:32:36.986  1019  1283 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
03-21 07:32:36.986  1019  1283 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-21 07:32:36.986  1019  1283 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-21 07:32:36.986  1019  1283 D SettingsProvider: selectionArgs: false
03-21 07:32:36.986  1019  1283 D SettingsProvider: selectionArgs: 1002
03-21 07:32:36.986  1019  1283 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-21 07:32:36.986  1019  1283 D SettingsProvider: ret = -1
,03-21 07:32:36.996  1181  1181 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-21 07:32:37.006  1019  1283 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,03-21 07:32:37.006  1181  1181 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-21 07:32:37.006  3238  3238 D TimaKeyStoreProvider: TimaSignature is unavailable
03-21 07:32:37.016  3238  3238 D ActivityThread: Added TimaKeyStore provider
,03-21 07:32:37.026  2993  2993 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,03-21 07:32:37.026  1019  3208 D Reset_Reason: resetString = NPON
,03-21 07:32:37.026   259   452 I SurfaceFlinger: id=9 Removed Mauncher (5/8)
,03-21 07:32:37.036   259  1156 I SurfaceFlinger: id=9 Removed Mauncher (-2/8)
,03-21 07:32:37.036  1019  1531 W ActivityManager: userId = 0, bbcId = -10000
03-21 07:32:37.036  1019  1531 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-21 07:32:37.036  1019  1531 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,03-21 07:32:37.046  1019  3191 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-21 07:32:37.046  3238  3238 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-21 07:32:37.046  3238  3238 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-21 07:32:37.046  3238  3238 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-21 07:32:37.046  3238  3238 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,03-21 07:32:37.046  3238  3238 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
03-21 07:32:37.046  3238  3238 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
03-21 07:32:37.046  3238  3238 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,03-21 07:32:37.056   290   290 E SMD     : DCD OFF
,03-21 07:32:37.066  2169  3263 E ActivityThread: Failed to find provider info for com.android.contacts.metadata
,03-21 07:32:37.066  2711  3262 D DelayedSyncController: Delaying sync.
,03-21 07:32:37.076   336   336 I ServiceManager: Waiting for service AtCmdFwd...,
03-21 07:32:37.076  1019  3208 I BootReceiver: Copying audit failures to DropBox
03-21 07:32:37.076  1019  3208 I BootReceiver: Checking for fsck errors
,03-21 07:32:37.076  1019  3208 I BootReceiver: Copying /data/tombstones/tombstone_00 to DropBox (SYSTEM_TOMBSTONE)
,03-21 07:32:37.076  3217  3217 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,03-21 07:32:37.086  1019  3265 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
,03-21 07:32:37.106  3153  3235 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,03-21 07:32:37.136  1019  1043 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 24941, reason: UserStart, SyncResult: databaseError: true stats []
,03-21 07:32:37.136  1019  1043 D SyncManager: not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 68261, reason: UserStart
,03-21 07:32:37.146  3153  3153 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,03-21 07:32:37.146  1019  3265 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
03-21 07:32:37.146  1019  3208 I BootReceiver: Copying /data/tombstones/tombstone_01 to DropBox (SYSTEM_TOMBSTONE)
,03-21 07:32:37.206  3153  3153 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-21 07:32:37.206  1019  3191 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,03-21 07:32:37.206  1019  3191 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-21 07:32:37.206  1019  3191 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-21 07:32:37.206  1019  1019 D CrashAnrDetector: Build: samsung/a3ultexx/a3ulte:5.0.2/LRX22G/A300FUXXU1BOEC:user/release-keys
03-21 07:32:37.206  1019  1019 D CrashAnrDetector: Hardware: MSM8916
03-21 07:32:37.206  1019  1019 D CrashAnrDetector: Revision: 1
03-21 07:32:37.206  1019  1019 D CrashAnrDetector: Bootloader: A300FUXXU1BOEC
03-21 07:32:37.206  1019  1019 D CrashAnrDetector: Radio: unknown
03-21 07:32:37.206  1019  1019 D CrashAnrDetector: Kernel: Linux version 3.10.49-4866174 (dpi@SWDD6204) (gcc version 4.8 (GCC) ) #1 SMP PREEMPT Fri May 29 20:06:40 KST 2015
03-21 07:32:37.206  1019  1019 D CrashAnrDetector: 
03-21 07:32:37.206  1019  1019 D CrashAnrDetector: *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
03-21 07:32:37.206  1019  1019 D CrashAnrDetector: Build fingerprint: 'samsung/a3ultexx/a3ulte:5.0.2/LRX22G/A300FUXXU1BOEC:user/release-keys'
03-21 07:32:37.206  1019  1019 D CrashAnrDetector: Revision: '1'
03-21 07:32:37.206  1019  1019 D CrashAnrDetector: ABI: 'arm'
03-21 07:32:37.206  1019  1019 D CrashAnrDetector: pid: 3299, tid: 3630, name: Thread-458  >>> com.test.thalitest <<<
03-21 07:32:37.206  1019  1019 D CrashAnrDetector: signal 11 (SIGSEGV), code 1 (SEGV_MAPERR), fault addr 0x0
03-21 07:32:37.206  1019  1019 D CrashAnrDetector:     r0 00000000  r1 9eaf4734  r2 00000002  r3 00000000
03-21 07:32:37.206  1019  1019 D CrashAnrDetector:     r4 b8f0ab70  r5 00000000  r6 b8f0a400  r7 b9e05d98
03-21 07:32:37.206  1019  1019 D CrashAnrDetector:     r8 b8f41fec  r9 b8f0ab70  sl b8f0a3d8  fp 9eaf472c
03-21 07:32:37.206  1019  1019 D CrashAnrDetector:     ip ffffffff  sp 9eaf471c  lr 9efcfb30  pc 9efcfa34  cpsr 60000010
03-21 07:32:37.206  1019  1019 D CrashAnrDetector:     d0  0000000000000000  d1  0000000000000000
03-21 07:32:37.206  1019  1019 D CrashAnrDetector:     d2  0000000000000000  d3  0000000000000000
03-21 07:32:37.206  1019  1019 D CrashAnrDetector:     d4  0000000000000000  d5  0000000000000000
03-21 07:32:37.206  1019  1019 D CrashAnrDetector:     d6  0000000000000000  d7  0000000000000000
03-21 07:32:37.206  1019  1019 D CrashAnrDetector:     d8  0000000000000000  d9  0000000000000000
03-21 07:32:37.206  1019  1019 D CrashAnrDetector:     d10 0000000000000000  d11 0000000000000000
03-21 07:32:37.206  1019  1019 D CrashAnrDetector:     d12 0000000000000000  d13 0000000000000000
03-21 07:32:37.206  1019  1019 D CrashAnrDetector:     d14 0000000000000000  d15 0000000000000000
03-21 07:32:37.206  1019  1019 D CrashAnrDetector:     d16 000027b7000027b7  d17 000027b700000000
03-21 07:32:37.206  1019  1019 D CrashAnrDetector:     d18 0001000100010001  d19 0001000100010001
03-21 07:32:37.206  1019  1019 D CrashAnrDetector:     d20 0000000100010001  d21 0000000000000000
03-21 07:32:37.206  1019  1019 D CrashAnrDetector:     d22 0000000000000000  d23 0000000000000000
03-21 07:32:37.206  1019  1019 D CrashAnrDetector:     d24 0000000000000000  d25 0000000000000000
03-21 07:32:37.206  1019  1019 D CrashAnrDetector:     d26 0002000100010001  d27 0002000200020002
03-21 07:32:37.206  1019  1019 D CrashAnrDetector:     d28 0080008000800080  d29 0080008000800080
03-21 07:32:37.206  1019  1019 D CrashAnrDetector:     d30 0800080008000800  d31 0800080008000800
03-21 07:32:37.206  1019  1019 D CrashAnrDetector:     scr 20000017
03-21 07:32:37.206  1019  1019 D CrashAnrDetector: 
03-21 07:32:37.206  1019  1019 D CrashAnrDetector: backtrace:
03-21 07:32:37.206  1019  1019 D CrashAnrDetector:     #00 pc 003d1a34  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (bool ThingIsPermanentAtom<JS::Symbol>(JS::Symbol*)+4)
03-21 07:32:37.206  1019  1019 D CrashAnrDetector:     #01 pc 003d1b2c  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so
03-21 07:32:37.206  1019  1019 D CrashAnrDetector:     #02 pc e5943000  <unknown>
03-21 07:32:37.206  1019  1019 D CrashAnrDetector: 
03-21 07:32:37.206  1019  1019 D CrashAnrDetector: stack:
03-21 07:32:37.206  1019  1019 D CrashAnrDetector:          9eaf469c  00000000  
03-21 07:32:37.206  1019  1019 D CrashAnrDetector,:          9eaf46a0  b9259cb0  [heap]
03-21 07:32:37.206  1019  1019 D CrashAnrDetector:          9eaf46a4  b8f0ab70  [heap]
03-21 07:32:37.206  1019  1019 D CrashAnrDetector:          9eaf46a8  0000000b  
03-21 07:32:37.206  1019  1019 D CrashAnrDetector:          9eaf46ac  b9259670  [heap]
03-21 07:32:37.206  1019  1019 D CrashAnrDetector:          9eaf46b0  9eaf46cc  [stack:3630]
03-21 07:32:37.206  1019  1019 D CrashAnrDetector:          9eaf46b4  9f043904  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (js::jit::BaselineScript::trace(JSTracer*)+120)
03-21 07:32:37.206  1019  1019 D CrashAnrDetector:          9eaf46b8  00000001  
03-21 07:32:37.206  1019  1019 D CrashAnrDetector:          9eaf46bc  00000000  
03-21 07:32:37.206  1019  1019 D CrashAnrDetector:          9eaf46c0  b8f0b6a0  [heap]
03-21 07:32:37.206  1019  1019 D CrashAnrDetector:          9eaf46c4  00000000  
03-21 07:32:37.206  1019  1019 D CrashAnrDetector:          9eaf46c8  00000000  
03-21 07:32:37.206  1019  1019 D CrashAnrDetector:          9eaf46cc  b8f0ab70  [heap]
03-21 07:32:37.206  1019  1019 D CrashAnrDetector:          9eaf46d0  b8f0b6a0  [heap]
03-21 07:32:37.206  1019  1019 D CrashAnrDetector:          9eaf46d4  9f65bb60  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so
03-21 07:32:37.206  1019  1019 D CrashAnrDetector:          9eaf46d8  9eaf4744  [stack:3630]
03-21 07:32:37.206  1019  1019 D CrashAnrDetector:          9eaf46dc  9efd6514  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (js::gc::GCRuntime::markConservativeStackRoots(JSTracer*, bool)+1308)
03-21 07:32:37.206  1019  1019 D CrashAnrDetector:          9eaf46e0  b8f0ab70  [heap]
03-21 07:32:37.206  1019  1019 D CrashAnrDetector:          9eaf46e4  b8f0a3d8  [heap]
03-21 07:32:37.206  1019  1019 D CrashAnrDetector:          9eaf46e8  9eafa000  
03-21 07:32:37.206  1019  1019 D CrashAnrDetector:          9eaf46ec  9eaf4710  [stack:3630]
03-21 07:32:37.206  1019  1019 D CrashAnrDetector:          9eaf46f0  9eaf4708  [stack:3630]
03-21 07:32:37.206  1019  1019 D CrashAnrDetector:          9eaf46f4  9eaf4714  [stack:3630]
03-21 07:32:37.206  1019  1019 D CrashAnrDetector:          9eaf46f8  9f5826d4  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so
03-21 07:32:37.206  1019  1019 D CrashAnrDetector:          9eaf46fc  9eaf4718  [stack:3630]
03-21 07:32:37.206  1019  1019 D CrashAnrDetector:          9eaf4700  00000004  
03-21 07:32:37.206  1019  1019 D CrashAnrDetector:          9eaf4704  00000000  
03-21 07:32:37.206  1019  1019 D CrashAnrDetector:          9eaf4708  00000001  
03-21 07:32:37.206  1019  1019 D CrashAnrDetector:          9eaf470c  b8f0ab70  [heap]
03-21 07:32:37.206  1019  1019 D CrashAnrDetector:          9eaf4710  9252f640  [anon:js-gc-heap]
03-21 07:32:37.206  1019  1019 D CrashAnrDetector:          9eaf4714  b8f0a400  [heap]
03-21 07:32:37.206  1019  1019 D CrashAnrDetector:          9eaf4718  9eaf472c  [stack:3630]
03-21 07:32:37.206  1019  1019 D CrashAnrDetector:     #00  9eaf471c  9eaf472c  [stack:3630]
03-21 07:32:37.206  1019  1019 D CrashAnrDetector:          9eaf4720  9eaf9838  [stack:3630]
03-21 07:32:37.206  1019  1019 D CrashAnrDetector:          9eaf4724  b9e01490  [heap]
03-21 07:32:37.206  1019  1019 D CrashAnrDetector:          9eaf4728  9eaf4744  [stack:3630]
03-21 07:32:37.206  1019  1019 D CrashAnrDetector:          9eaf472c  9efd306c  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (js::gc::MarkValueRoot(JSTracer*, JS::Value*, char const*)+80)
03-21 07:32:37.206  1019  1019 D CrashAnrDetector:     #01  9eaf4730  b8f41fec  [heap]
03-21 07:32:37.206  1019  1019 D CrashAnrDetector:          9eaf4734  00000000  
03-21 07:32:37.206  1019  1019 D CrashAnrDetector:          9eaf4738  b8f0a3fc  [heap]
03-21 07:32:37.206  1019  1019 D CrashAnrDetector:          9eaf473c  9f503cd8  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so
03-21 07:32:37.206  1019  1019 D CrashAnrDetector:          9eaf4740  9eaf479c  [stack:3630]
03-21 07:32:37.206  1019  1019 D CrashAnrDetector:          9eaf4744 , 9efd7dcc  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (js::gc::GCRuntime::markRuntime(JSTracer*, js::gc::GCRuntime::TraceOrMarkRuntime, js::gc::GCRuntime::TraceRootsOrUsedSaved)+1452)
03-21 07:32:37.206  1019  1019 D CrashAnrDetector:          9eaf4748  00000000  
03-21 07:32:37.206  1019  1019 D CrashAnrDetector:          
03-21 07:32:37.206  1019  1019 D CrashAnrDetector: processName:com.test.thalitest
03-21 07:32:37.206  1019  1019 D CrashAnrDetector: broadcastEvent : com.test.thalitest SYSTEM_TOMBSTONE
03-21 07:32:37.206  3153  3153 W AwContents: onDetachedFromWindow called when already detached. Ignoring
03-21 07:32:37.216  1019  1499 W ActivityManager: userId = 0, bbcId = -10000
03-21 07:32:37.216  1019  1499 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-21 07:32:37.216  1019  1499 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.phone, destAppInfo.processName = com.sec.phone
03-21 07:32:37.216  1019  1564 I art     : Explicit concurrent mark sweep GC freed 41433(2040KB) AllocSpace objects, 7(896KB) LOS objects, 33% free, 23MB/35MB, paused 19.646ms total 269.042ms
03-21 07:32:37.226  1019  1571 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
03-21 07:32:37.226  1019  1571 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-21 07:32:37.226  1019  1571 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-21 07:32:37.226  1019  1571 D SettingsProvider: selectionArgs: false
03-21 07:32:37.226  1019  1571 D SettingsProvider: selectionArgs: 1002
03-21 07:32:37.226  1019  1571 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-21 07:32:37.226  1019  1571 D SettingsProvider: ret = -1
03-21 07:32:37.226  3153  3153 D PhoneWindow: *FMB* installDecor mIsFloating : false
03-21 07:32:37.226  3153  3153 D PhoneWindow: *FMB* installDecor flags : -2139027200
03-21 07:32:37.226  1019  1019 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 com.android.server.analytics.data.collection.application.CrashAnrDetector.broadcastEvent:296 com.android.server.analytics.data.collection.application.CrashAnrDetector.processDropBoxEntry:254 com.android.server.analytics.data.collection.application.CrashAnrDetector.access$100:60 com.android.server.analytics.data.collection.application.CrashAnrDetector$1.onReceive:102 
03-21 07:32:37.236  3153  3153 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
03-21 07:32:37.236  1019  1571 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=1002
03-21 07:32:37.246  1019  3208 I BootReceiver: Copying /data/tombstones/tombstone_02 to DropBox (SYSTEM_TOMBSTONE)
03-21 07:32:37.246  1019  3265 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
03-21 07:32:37.246  1019  1531 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
03-21 07:32:37.246  1019  1531 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-21 07:32:37.246  1019  1531 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-21 07:32:37.246  1019  1531 D SettingsProvider: selectionArgs: false
03-21 07:32:37.246  1019  1531 D SettingsProvider: selectionArgs: 1002
03-21 07:32:37.246  1019  1531 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-21 07:32:37.246  1019  1531 D SettingsProvider: ret = -1
03-21 07:32:37.246  1019  1044 W ActivityManager: userId = 0, bbcId = -10000
03-21 07:32:37.246  1019  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-21 07:32:37.246  1019  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.phone, destAppInfo.processName = com.sec.factory
,03-21 07:32:37.246  1181  1181 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-21 07:32:37.256  1019  3191 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-21 07:32:37.256  2423  2423 D Mms/NotificationReceiver: MMS NotificationReceiver onReceive: android.intent.action.BOOT_COMPLETED
,03-21 07:32:37.256  2423  2423 D Mms/NotificationReceiver: handleBootCompleted
,03-21 07:32:37.256  3153  3153 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-21 07:32:37.256  3112  3112 D FactoryTestApp: [ProtectedFactoryTestBroadcastReceiver$onReceive](3112) onReceive action=com.samsung.intent.action.SECPHONE_READY
03-21 07:32:37.256  3112  3112 I FactoryTestApp: [ProtectedFactoryTestBroadcastReceiver$onReceive](3112) com.samsung.intent.action.SECPHONE_READY
,03-21 07:32:37.266  2423  2423 D Mms/RcsOwnCapsManager: queue Uri = content://im/queue-messages?box=pending
,03-21 07:32:37.266  3153  3153 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-21 07:32:37.266  3112  3112 D FactoryTest: User mode
,03-21 07:32:37.276  1019  1531 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,03-21 07:32:37.276  1019  1502 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
03-21 07:32:37.276  1019  1502 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-21 07:32:37.276  1019  1502 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-21 07:32:37.276  1019  1502 D SettingsProvider: selectionArgs: false
03-21 07:32:37.276  1019  1502 D SettingsProvider: selectionArgs: 1002
03-21 07:32:37.276  1019  1502 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-21 07:32:37.276  1019  1502 D SettingsProvider: ret = -1
,03-21 07:32:37.276  1019  1502 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,03-21 07:32:37.286  1488  1901 D TP/ImProvider: im query match24
03-21 07:32:37.286  1488  1901 D TP/ImProvider: URI_IM_QUEUED_MESSAGES
03-21 07:32:37.286  1488  1901 D TP/ImProvider: ftSesstionId must be a long.
,03-21 07:32:37.286  1488  1901 D TP/ImProvider: getQueuedImMessages
03-21 07:32:37.286  1488  1901 D TP/ImProvider: uriString = SELECT ft._id as _id, ft.session_id as session_id, ft.chat_session_id as chat_session_id, thread_id, 'ft' as transport_type, address as recipients, ft.type as type, ft.status as status, ft.service_type as service_type, ft.ext_info as ext_info FROM ft LEFT JOIN im_threads ON ft.thread_id=im_threads.normal_thread_id WHERE ft.hidden=0 AND type=1 AND (status=1 or status=2) UNION SELECT ft._id as _id, ft.session_id as session_id, ft.chat_session_id as chat_session_id, thread_id, 'ft' as transport_type, address as recipients, ft.type as type, ft.status as status, ft.service_type as service_type, ft.ext_info as ext_info FROM ft LEFT JOIN im_threads ON ft.thread_id=im_threads.normal_thread_id WHERE ft.hidden=0 AND type=4 AND (status!=4 AND status!=12) UNION SELECT ft._id as _id, ft.session_id as session_id, ft.chat_session_id as chat_session_id, thread_id, 'ft' as transport_type, address as recipients, ft.type as type, ft.status as status, ft.service_type as service_type, ft.ext_info as ext_info FROM ft LEFT JOIN im_threads ON ft.thread_id=im_threads.normal_thread_id WHERE ft.hidden=0 AND type=6 UNION SELECT im._id as _id, im.session_id as session_id, null as chat_session_id, thread_id, 'chat' as transport_type, address as recipients, im.type as type, im.status as status, im.service_type as service_type, im.ext_info as ext_info FROM im LEFT JOIN im_threads ON im.thread_id=im_threads.normal_thread_id WHERE im.hidden=0 AND type=4 UNION SELECT im._id as _id, im.session_id as session_id, null as chat_session_id, thread_id, 'chat' as transport_type, address as recipients, im.type as type, im.status as status, im.service_type as service_type, im.ext_info as ext_info FROM im LEFT JOIN im_threads ON im.thread_id=im_threads.normal_thread_id WHERE im.hidden=0 AND type=6
,03-21 07:32:37.286  1488  1901 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-21 07:32:37.286  1488  1901 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-21 07:32:37.286  1488  1901 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-21 07:32:37.286  1488  1901 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-21 07:32:37.286  1488  1901 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
,03-21 07:32:37.286  1019  1805 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
,03-21 07:32:37.286  1019  1805 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-21 07:32:37.286  1019  1805 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-21 07:32:37.286  1019  1805 D SettingsProvider: selectionArgs: false
03-21 07:32:37.286  1019  1805 D SettingsProvider: selectionArgs: 1002
03-21 07:32:37.286  1019  1805 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-21 07:32:37.286  1019  1805 D SettingsProvider: ret = -1
,03-21 07:32:37.296  1181  1181 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
03-21 07:32:37.296  1181  1181 D StatusBar.NetworkController: refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-21 07:32:37.296  1181  1181 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-21 07:32:37.296  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-21 07:32:37.296  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-21 07:32:37.296  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-21 07:32:37.296  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-21 07:32:37.306  1019  1805 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,03-21 07:32:37.306  1181  1181 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-21 07:32:37.306  1019  1499 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
,03-21 07:32:37.316  1019  1561 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
03-21 07:32:37.316  1019  1561 D SecContentProvider2: mCursor = null
,03-21 07:32:37.316  1019  1499 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,03-21 07:32:37.316  1019  1499 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,03-21 07:32:37.316  1019  1499 D SettingsProvider: selectionArgs: false
03-21 07:32:37.316  1019  1499 D SettingsProvider: selectionArgs: 1002
,03-21 07:32:37.316  3238  3238 D NearbySource: Nearby Source Create!
,03-21 07:32:37.316  3238  3238 D NearbyContext: Nearby Context Create!
03-21 07:32:37.316  1019  1499 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-21 07:32:37.316  1019  1499 D SettingsProvider: ret = -1
,03-21 07:32:37.326  1019  1564 I ActivityManager: Killing 2580:com.sec.android.app.camera/u0a135 (adj 15): empty #31
,03-21 07:32:37.326  1181  1181 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-21 07:32:37.326  1019  1499 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,03-21 07:32:37.336  1019  1032 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
03-21 07:32:37.336  1019  1032 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-21 07:32:37.336  1019  1032 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-21 07:32:37.336  1019  1032 D SettingsProvider: selectionArgs: false
03-21 07:32:37.336  1019  1032 D SettingsProvider: selectionArgs: 1002
03-21 07:32:37.336  1019  1032 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-21 07:32:37.336  1019  1032 D SettingsProvider: ret = -1
,03-21 07:32:37.336  1019  1019 D CrashAnrDetector: Build: samsung/a3ultexx/a3ulte:5.0.2/LRX22G/A300FUXXU1BOEC:user/release-keys
03-21 07:32:37.336  1019  1019 D CrashAnrDetector: Hardware: MSM8916
03-21 07:32:37.336  1019  1019 D CrashAnrDetector: Revision: 1
03-21 07:32:37.336  1019  1019 D CrashAnrDetector: Bootloader: A300FUXXU1BOEC
03-21 07:32:37.336  1019  1019 D CrashAnrDetector: Radio: unknown
03-21 07:32:37.336  1019  1019 D CrashAnrDetector: Kernel: Linux version 3.10.49-4866174 (dpi@SWDD6204) (gcc version 4.8 (GCC) ) #1 SMP PREEMPT Fri May 29 20:06:40 KST 2015
03-21 07:32:37.336  1019  1019 D CrashAnrDetector: 
03-21 07:32:37.336  1019  1019 D CrashAnrDetector: *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
03-21 07:32:37.336  1019  1019 D CrashAnrDetector: Build fingerprint: 'samsung/a3ultexx/a3ulte:5.0.2/LRX22G/A300FUXXU1BOEC:user/release-keys'
03-21 07:32:37.336  1019  1019 D CrashAnrDetector: Revision: '1'
03-21 07:32:37.336  1019  1019 D CrashAnrDetector: ABI: 'arm'
03-21 07:32:37.336  1019  1019 D CrashAnrDetector: pid: 3116, tid: 3436, name: Thread-417  >>> com.test.thalitest <<<
03-21 07:32:37.336  1019  1019 D CrashAnrDetector: signal 11 (SIGSEGV), code 1 (SEGV_MAPERR), fault addr 0x0
03-21 07:32:37.336  1019  1019 D CrashAnrDetector:     r0 00000000  r1 92659c6c  r2 00000002  r3 00000000
03-21 07:32:37.336  1019  1019 D CrashAnrDetector:     r4 b79c5bd0  r5 00000000  r6 92659d08  r7 ba323270
03-21 07:32:37.336  1019  1019 D CrashAnrDetector:     r8 b7a5b7ec  r9 b79c5bd0  sl b79c5438  fp 92659c64
03-21 07:32:37.336  1019  1019 D CrashAnrDetector:     ip 00000000  sp 92659c54  lr 92c20820  pc 92c20724  cpsr 60000010
03-21 07:32:37.336  1019  1019 D CrashAnrDetector:     d0  0000000000000000  d1  0000000000000000
03-21 07:32:37.336  1019  1019 D CrashAnrDetector:     d2  0000000000000000  d3  0000000000000000
03-21 07:32:37.336  1019  1019 D CrashAnrDetector:     d4  0000000000000000  d5  0000000000000000
03-21 07:32:37.336  1019  1019 D CrashAnrDetector:     d6  0000000000000000  d7  0000000000000000
03-21 07:32:37.336  1019  1019 D CrashAnrDetector:     d8  0000000000000000  d9  0000000000000000
03-21 07:32:37.336  1019  1019 D CrashAnrDetector:     d10 0000000000000000  d11 0000000000000000
03-21 07:32:37.336  1019  1019 D CrashAnrDetector:     d12 0000000000000000  d13 0000000000000000
03-21 07:32:37.336  1019  1019 D CrashAnrDetector:     d14 0000000000000000  d15 0000000000000000
03-21 07:32:37.336  1019  1019 D CrashAnrDetector:     d16 000027b7000027b7  d17 000027b700000000
03-21 07:32:37.336  1019  1019 D CrashAnrDetector:     d18 0001000100010001  d19 0001000100010001
03-21 07:32:37.336  1019  1019 D CrashAnrDetector:     d20 0000000100010001  d21 0000000000000000
03-21 07:32:37.336  1019  1019 D CrashAnrDetector:     d22 0000000000000000  d23 0000000000000000
03-21 07:32:37.336  1019  1019 D CrashAnrDetector:     d24 0000000000000000  d25 0000000000000000
03-21 07:32:37.336  1019  1019 D CrashAnrDetector:     d26 0002000100010001  d27 0002000200020002
03-21 07:32:37.336  1019  1019 D CrashAnrDetector:     d28 0080008000800080  d29 0080008000800080
03-21 07:32:37.336  1019  1019 D CrashAnrDetector:     d30 0800080008000800  d31 0800080008000800
03-21 07:32:37.336  1019  1019 D CrashAnrDetector:     scr 20000017
03-21 07:32:37.336  1019  1019 D CrashAnrDetector: 
03-21 07:32:37.336  1019  1019 D CrashAnrDetector: backtrace:
03-21 07:32:37.336  1019  1019 D CrashAnrDetector:     #00 pc 003cb724  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (bool ThingIsPermanentAtom<JS::Symbol>(JS::Symbol*)+4)
03-21 07:32:37.336  1019  1019 D CrashAnrDetector:     #01 pc 003cb81c  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so
03-21 07:32:37.336  1019  1019 D CrashAnrDetector:     #02 pc e5943000  <unknown>
03-21 07:32:37.336  1019  1019 D CrashAnrDetector: 
03-21 07:32:37.336  1019  1019 D CrashAnrDetector: stack:
03-21 07:32:37.336  1019  1019 D CrashAnrDetector:          92659bd4  00000000  
03-21 07:32:37.336  1019  1019 D CrashAnrDetector,:          92659bd8  90efc0a0  [anon:js-gc-heap]
03-21 07:32:37.336  1019  1019 D CrashAnrDetector:          92659bdc  b79c5bd0  [heap]
03-21 07:32:37.336  1019  1019 D CrashAnrDetector:          92659be0  b79c5bd0  [heap]
03-21 07:32:37.336  1019  1019 D CrashAnrDetector:          92659be4  00000001  
03-21 07:32:37.336  1019  1019 D CrashAnrDetector:          92659be8  92659c04  [stack:3436]
03-21 07:32:37.336  1019  1019 D CrashAnrDetector:          92659bec  92c1fe40  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so
03-21 07:32:37.336  1019  1019 D CrashAnrDetector:          92659bf0  00000001  
03-21 07:32:37.336  1019  1019 D CrashAnrDetector:          92659bf4  b79c52d0  [heap]
03-21 07:32:37.336  1019  1019 D CrashAnrDetector:          92659bf8  b79c6700  [heap]
03-21 07:32:37.336  1019  1019 D CrashAnrDetector:          92659bfc  00000000  
03-21 07:32:37.336  1019  1019 D CrashAnrDetector:          92659c00  00000000  
03-21 07:32:37.336  1019  1019 D CrashAnrDetector:          92659c04  b79c5bd0  [heap]
03-21 07:32:37.336  1019  1019 D CrashAnrDetector:          92659c08  b79c6700  [heap]
03-21 07:32:37.336  1019  1019 D CrashAnrDetector:          92659c0c  932adb58  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so
03-21 07:32:37.336  1019  1019 D CrashAnrDetector:          92659c10  92659c7c  [stack:3436]
03-21 07:32:37.336  1019  1019 D CrashAnrDetector:          92659c14  92c2826c  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (js::gc::GCRuntime::markConservativeStackRoots(JSTracer*, bool)+1308)
03-21 07:32:37.336  1019  1019 D CrashAnrDetector:          92659c18  b79c5bd0  [heap]
03-21 07:32:37.336  1019  1019 D CrashAnrDetector:          92659c1c  b79c5438  [heap]
03-21 07:32:37.336  1019  1019 D CrashAnrDetector:          92659c20  92660000  /dev/kgsl-3d0
03-21 07:32:37.336  1019  1019 D CrashAnrDetector:          92659c24  92659c48  [stack:3436]
03-21 07:32:37.336  1019  1019 D CrashAnrDetector:          92659c28  92659c40  [stack:3436]
03-21 07:32:37.336  1019  1019 D CrashAnrDetector:          92659c2c  92659c4c  [stack:3436]
03-21 07:32:37.336  1019  1019 D CrashAnrDetector:          92659c30  931d2e14  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so
03-21 07:32:37.336  1019  1019 D CrashAnrDetector:          92659c34  92659c50  [stack:3436]
03-21 07:32:37.336  1019  1019 D CrashAnrDetector:          92659c38  00000004  
03-21 07:32:37.336  1019  1019 D CrashAnrDetector:          92659c3c  00000000  
03-21 07:32:37.336  1019  1019 D CrashAnrDetector:          92659c40  00000001  
03-21 07:32:37.336  1019  1019 D CrashAnrDetector:          92659c44  b79c5bd0  [heap]
03-21 07:32:37.336  1019  1019 D CrashAnrDetector:          92659c48  8f836c70  [anon:js-gc-heap]
03-21 07:32:37.336  1019  1019 D CrashAnrDetector:          92659c4c  92659d08  [stack:3436]
03-21 07:32:37.336  1019  1019 D CrashAnrDetector:          92659c50  92659c64  [stack:3436]
03-21 07:32:37.336  1019  1019 D CrashAnrDetector:     #00  92659c54  92659c64  [stack:3436]
03-21 07:32:37.336  1019  1019 D CrashAnrDetector:          92659c58  9265f838  [stack:3436]
03-21 07:32:37.336  1019  1019 D CrashAnrDetector:          92659c5c  ba3217a0  [heap]
03-21 07:32:37.336  1019  1019 D CrashAnrDetector:          92659c60  92659c7c  [stack:3436]
03-21 07:32:37.336  1019  1019 D CrashAnrDetector:          92659c64  92c24da0  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (js::gc::MarkValueRoot(JSTracer*, JS::Value*, char const*)+80)
03-21 07:32:37.336  1019  1019 D CrashAnrDetector:     #01  92659c68  b7a5b7ec  [heap]
03-21 07:32:37.336  1019  1019 D CrashAnrDetector:          92659c6c  00000000  
03-21 07:32:37.336  1019  1019 D CrashAnrDetector:          92659c70  b79c545c  [heap]
03-21 07:32:37.336  1019  1019 D CrashAnrDetector:          92659c74  93154334  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so
03-21 07:32:37.336  1019  1019 D CrashAnrDetector:          92659c78  92659cd4  [stack:3436]
03-21 07:32:37.336  1019  1019 D CrashAnrDetector:          92659c7c  92c29b1c  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (js::gc::GCRuntime::markRuntime(JSTracer*, js::gc::GCRuntime::TraceOrMarkRuntime, js::gc::GCRuntime::TraceRootsOrUsedSaved)+1456)
03-21 07:32:37.336  1019  1019 D CrashAnrDetector:          92659c80  00000000  
03-21 07:32:37.336  1019  1019 D CrashAnrDetector:          92659c84  92
03-21 07:32:37.336  1019  1019 D CrashAnrDetector: processName:com.test.thalitest
03-21 07:32:37.336  1019  1019 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 com.android.server.analytics.data.collection.application.CrashAnrDetector.broadcastEvent:296 com.android.server.analytics.data.collection.application.CrashAnrDetector.processDropBoxEntry:254 com.android.server.analytics.data.collection.application.CrashAnrDetector.access$100:60 com.android.server.analytics.data.collection.application.CrashAnrDetector$1.onReceive:102 
03-21 07:32:37.336  1019  1019 D CrashAnrDetector: broadcastEvent : com.test.thalitest SYSTEM_TOMBSTONE
03-21 07:32:37.336  1019  3208 I BootReceiver: Copying /data/tombstones/tombstone_03 to DropBox (SYSTEM_TOMBSTONE)
03-21 07:32:37.336  1019  3265 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
03-21 07:32:37.336  1019  1032 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=1002
03-21 07:32:37.346  2423  2423 D Mms/NotificationReceiver:  getPendingMessageIds: no pending messages.
03-21 07:32:37.346  2423  2423 D Mms/ActionsFactory: Call to GET_LAST_MESSAGES_SENT
03-21 07:32:37.346  1019  1805 W ActivityManager: Unable to start service Intent { act=com.samsung.rcs.framework.instantmessaging.action.GET_LAST_MESSAGES_SENT cat=[com.samsung.rcs.framework.instantmessaging.category.ACTION] pkg=com.sec.ims.android (has extras) } U=0: not found
03-21 07:32:37.346  1019  1395 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
03-21 07:32:37.346  1019  1395 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-21 07:32:37.346  1019  1395 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-21 07:32:37.346  1019  1395 D SettingsProvider: selectionArgs: false
03-21 07:32:37.346  1019  1395 D SettingsProvider: selectionArgs: 1002
03-21 07:32:37.346  1019  1395 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-21 07:32:37.346  1019  1395 D SettingsProvider: ret = -1
03-21 07:32:37.346  1181  1181 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
03-21 07:32:37.346   258   519 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
03-21 07:32:37.346   258   519 W Vold    : Returning OperationFailed - no handler for errno 0
03-21 07:32:37.346  3153  3279 D OpenGLRenderer: Render dirty regions requested: true
03-21 07:32:37.356  3238  3238 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
03-21 07:32:37.356  1019  1395 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=1002
03-21 07:32:37.356  3238  3238 D SLinkSource: Samsung link source created
03-21 07:32:37.356  1019  1032 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
03-21 07:32:37.356  1019  1032 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-21 07:32:37.356  1019  1032 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-21 07:32:37.356  1019  1032 D SettingsProvider: selectionArgs: false
03-21 07:32:37.356  1019  1032 D SettingsProvider: selectionArgs: 1002
03-21 07:32:37.356  1019  1032 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-21 07:32:37.356  1019  1032 D SettingsProvider: ret = -1
03-21 07:32:37.356  1019  1630 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
03-21 07:32:37.356  1019  1630 D KnoxTimeoutHandler: postActiveUserChange for user 0
03-21 07:32:37.356  1019  1630 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
03-21 07:32:37.366  3153  3153 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
03-21 07:32:37.366  3153  3153 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
03-21 07:32:37.366  1019  1032 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,03-21 07:32:37.376  1019  1019 D CrashAnrDetector: Build: samsung/a3ultexx/a3ulte:5.0.2/LRX22G/A300FUXXU1BOEC:user/release-keys
03-21 07:32:37.376  1019  1019 D CrashAnrDetector: Hardware: MSM8916
03-21 07:32:37.376  1019  1019 D CrashAnrDetector: Revision: 1
03-21 07:32:37.376  1019  1019 D CrashAnrDetector: Bootloader: A300FUXXU1BOEC
03-21 07:32:37.376  1019  1019 D CrashAnrDetector: Radio: unknown
03-21 07:32:37.376  1019  1019 D CrashAnrDetector: Kernel: Linux version 3.10.49-4866174 (dpi@SWDD6204) (gcc version 4.8 (GCC) ) #1 SMP PREEMPT Fri May 29 20:06:40 KST 2015
03-21 07:32:37.376  1019  1019 D CrashAnrDetector: 
03-21 07:32:37.376  1019  1019 D CrashAnrDetector: *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
03-21 07:32:37.376  1019  1019 D CrashAnrDetector: Build fingerprint: 'samsung/a3ultexx/a3ulte:5.0.2/LRX22G/A300FUXXU1BOEC:user/release-keys'
03-21 07:32:37.376  1019  1019 D CrashAnrDetector: Revision: '1'
03-21 07:32:37.376  1019  1019 D CrashAnrDetector: ABI: 'arm'
03-21 07:32:37.376  1019  1019 D CrashAnrDetector: pid: 3310, tid: 3589, name: Thread-447  >>> com.test.thalitest <<<
03-21 07:32:37.376  1019  1019 D CrashAnrDetector: signal 11 (SIGSEGV), code 1 (SEGV_MAPERR), fault addr 0x0
03-21 07:32:37.376  1019  1019 D CrashAnrDetector:     r0 00000000  r1 9eff4b94  r2 00000002  r3 00000000
03-21 07:32:37.376  1019  1019 D CrashAnrDetector:     r4 b87aac78  r5 00000000  r6 9eff4c30  r7 b919c940
03-21 07:32:37.376  1019  1019 D CrashAnrDetector:     r8 b88334b4  r9 b87aac78  sl b87aa4e0  fp 9eff4b8c
03-21 07:32:37.376  1019  1019 D CrashAnrDetector:     ip 00000000  sp 9eff4b7c  lr 9f4cc820  pc 9f4cc724  cpsr 60000010
03-21 07:32:37.376  1019  1019 D CrashAnrDetector:     d0  0000000000000000  d1  0000000000000000
03-21 07:32:37.376  1019  1019 D CrashAnrDetector:     d2  0000000000000000  d3  0000000000000000
03-21 07:32:37.376  1019  1019 D CrashAnrDetector:     d4  0000000000000000  d5  0000000000000000
03-21 07:32:37.376  1019  1019 D CrashAnrDetector:     d6  0000000000000000  d7  0000000000000000
03-21 07:32:37.376  1019  1019 D CrashAnrDetector:     d8  0000000000000000  d9  0000000000000000
03-21 07:32:37.376  1019  1019 D CrashAnrDetector:     d10 0000000000000000  d11 0000000000000000
03-21 07:32:37.376  1019  1019 D CrashAnrDetector:     d12 0000000000000000  d13 0000000000000000
03-21 07:32:37.376  1019  1019 D CrashAnrDetector:     d14 0000000000000000  d15 0000000000000000
03-21 07:32:37.376  1019  1019 D CrashAnrDetector:     d16 000027b7000027b7  d17 000027b700000000
03-21 07:32:37.376  1019  1019 D CrashAnrDetector:     d18 0001000100010001  d19 0001000100010001
03-21 07:32:37.376  1019  1019 D CrashAnrDetector:     d20 0000000100010001  d21 0000000000000000
03-21 07:32:37.376  1019  1019 D CrashAnrDetector:     d22 0000000000000000  d23 0000000000000000
03-21 07:32:37.376  1019  1019 D CrashAnrDetector:     d24 0000000000000000  d25 0000000000000000
03-21 07:32:37.376  1019  1019 D CrashAnrDetector:     d26 0002000100010001  d27 0002000200020002
03-21 07:32:37.376  1019  1019 D CrashAnrDetector:     d28 0080008000800080  d29 0080008000800080
03-21 07:32:37.376  1019  1019 D CrashAnrDetector:     d30 0800080008000800  d31 0800080008000800
03-21 07:32:37.376  1019  1019 D CrashAnrDetector:     scr 20000013
03-21 07:32:37.376  1019  1019 D CrashAnrDetector: 
03-21 07:32:37.376  1019  1019 D CrashAnrDetector: backtrace:
03-21 07:32:37.376  1019  1019 D CrashAnrDetector:     #00 pc 003cb724  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (bool ThingIsPermanentAtom<JS::Symbol>(JS::Symbol*)+4)
03-21 07:32:37.376  1019  1019 D CrashAnrDetector:     #01 pc 003cb81c  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so
03-21 07:32:37.376  1019  1019 D CrashAnrDetector:     #02 pc e5943000  <unknown>
03-21 07:32:37.376  1019  1019 D CrashAnrDetector: 
03-21 07:32:37.376  1019  1019 D CrashAnrDetector: stack:
03-21 07:32:37.376  1019  1019 D CrashAnrDetector:          9eff4afc  00000000  
03-21 07:32:37.376  1019  1019 D CrashAnrDetector:          9eff4b00  912fc0a0  [anon:js-gc-heap]
03-21 07:32:37.376  1019  1019 D CrashAnrDetector:          9eff4b04  b87aac78  [heap]
03-21 07:32:37.376  1019  1019 D CrashAnrDetector:          9eff4b08  b87aac78  [heap]
03-21 07:32:37.376  1019  1019 D CrashAnrDetector:          9eff4b0c  00000001  
03-21 07:32:37.376  1019  1019 D CrashAnrDetector:          9eff4b10  9eff4b2c  [stack:3589]
03-21 07:32:37.376  1019  1019 D CrashAnrDetector:          9eff4b14  9f4cbe40  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so
03-21 07:32:37.376  1019  1019 D CrashAnrDetector:          9eff4b18  00000001  
03-21 07:32:37.376  1019  1019 D CrashAnrDetector:          9eff4b1c  b87aa378  [heap]
03-21 07:32:37.376  1019  1019 D CrashAnrDetector:          9eff4b20  b87ab7a8  [heap]
03-21 07:32:37.376  1019  1019 D CrashAnrDetector:          9eff4b24  00000000  
03-21 07:32:37.376  1019  1019 D CrashAnrDetector:          9eff4b28  00000000  
03-21 07:32:37.376  1019  1019 D CrashAnrDetector:          9eff4b2c  b87aac78  [heap]
03-21 07:32:37.376  1019  1019 D CrashAnrDetector:          9eff4b30  b87ab7a8  [heap]
03-21 07:32:37.376  1019  1019 D CrashAnrDetector:          9eff4b34  9fb59b58  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so
03-21 07:32:37.376  1019  1019 D CrashAnrDetector:          9eff4b38  9eff4ba4  [stack:3589]
03-21 07:32:37.376  1019  1019 D CrashAnrDetector:          9eff4b3c  9f4d426c  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (js::gc::GCRuntime::markConservativeStackRoots(JSTracer*, bool)+1308)
03-21 07:32:37.376  1019  1019 D CrashAnrDetector:          9eff4b40  b87aac78  [heap]
03-21 07:32:37.376  1019  1019 D CrashAnrDetector:          9eff4b44  b87aa4e0  [heap]
03-21 07:32:37.376  1019  1019 D CrashAnrDetector:          9eff4b48  9effd000  
03-21 07:32:37.376  1019  1019 D CrashAnrDetector:          9eff4b4c  9eff4b70  [stack:3589]
03-21 07:32:37.376  1019  1019 D CrashAnrDetector:          9eff4b50  9eff4b68  [stack:3589]
03-21 07:32:37.376  1019  1019 D CrashAnrDetector:          9eff4b54  9eff4b74  [stack:3589]
03-21 07:32:37.376  1019  1019 D CrashAnrDetector:          9eff4b58  9fa7ee14  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so
03-21 07:32:37.376  1019  1019 D CrashAnrDetector:          9eff4b5c  9eff4b78  [stack:3589]
03-21 07:32:37.376  1019  1019 D CrashAnrDetector:          9eff4b60  00000004  
03-21 07:32:37.376  1019  1019 D CrashAnrDetector:          9eff4b64  00000000  
03-21 07:32:37.376  1019  1019 D CrashAnrDetector:          9eff4b68  00000001  
03-21 07:32:37.376  1019  1019 D CrashAnrDetector:          9eff4b6c  b87aac78  [heap]
03-21 07:32:37.376  1019  1019 D CrashAnrDetector:          9eff4b70  9262a430  [anon:js-gc-heap]
03-21 07:32:37.376  1019  1019 D CrashAnrDetector:          9eff4b74  9eff4c30  [stack:3589]
03-21 07:32:37.376  1019  1019 D CrashAnrDetector:          9eff4b78  9eff4b8c  [stack:3589]
03-21 07:32:37.376  1019  1019 D CrashAnrDetector:     #00  9eff4b7c  9eff4b8c  [stack:3589]
03-21 07:32:37.376  1019  1019 D CrashAnrDetector:          9eff4b80  9effc838  [stack:3589]
03-21 07:32:37.376  1019  1019 D CrashAnrDetector:          9eff4b84  b9197240  [heap]
03-21 07:32:37.376  1019  1019 D CrashAnrDetector:          9eff4b88  9eff4ba4  [stack:3589]
03-21 07:32:37.376  1019  1019 D CrashAnrDetector:          9eff4b8c  9f4d0da0  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (js::gc::MarkValueRoot(JSTracer*, JS::Value*, char const*)+80)
03-21 07:32:37.376  1019  1019 D CrashAnrDetector:     #01  9eff4b90  b88334b4  [heap]
03-21 07:32:37.376  1019  1019 D CrashAnrDetector:          9eff4b94  00000000  
03-21 07:32:37.376  1019  1019 D CrashAnrDetector:          9eff4b98  b87aa504  [heap]
03-21 07:32:37.376  1019  1019 D CrashAnrDetector:          9eff4b9c  9fa00334  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so
03-21 07:32:37.376  1019  1019 D CrashAnrDetector:          9eff4ba0  9eff4bfc  [stack:3589]
03-21 07:32:37.376  1019  1019 D CrashAnrDetector:          9eff4ba4  9f4d5b1c  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (js::gc::GCRuntime::markRuntime(JSTracer*, js::gc::GCRuntime::TraceOrMarkRuntime, js::gc::GCRuntime::TraceRootsOrUsedSaved)+1456)
03-21 07:32:37.376  1019  1019 D CrashAnrDetector:          9eff4ba8  00000000  
03-21 07:32:37.376  1019  1019 D CrashAnrDetector:          9eff4bac  9eff4bc4  [stac
03-21 07:32:37.376  1019  1019 D CrashAnrDetector: processName:com.test.thalitest
03-21 07:32:37.376  1019  1019 D CrashAnrDetector: broadcastEvent : com.test.thalitest SYSTEM_TOMBSTONE
03-21 07:32:37.376  1181  1181 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
03-21 07:32:37.376  1019  1019 D KnoxTimeoutHandler: handleActiveUserChange for user 0
03-21 07:32:37.376  1019  1019 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 com.android.server.analytics.data.collection.application.CrashAnrDetector.broadcastEvent:296 com.android.server.analytics.data.collection.application.CrashAnrDetector.processDropBoxEntry:254 com.android.server.analytics.data.collection.application.CrashAnrDetector.access$100:60 com.android.server.analytics.data.collection.application.CrashAnrDetector$1.onReceive:102 
03-21 07:32:37.376  1019  1019 D PersonaManagerService: getPersonasForUser(): returning null!
03-21 07:32:37.386  1181  1181 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
03-21 07:32:37.396  1019  1043 W libprocessgroup: failed to open /acct/uid_10135/pid_2580/cgroup.procs: No such file or directory
03-21 07:32:37.396  1181  1181 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
03-21 07:32:37.396  1181  1181 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-21 07:32:37.416  1019  1032 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
03-21 07:32:37.416  1019  3208 I BootReceiver: Copying /data/tombstones/tombstone_04 to DropBox (SYSTEM_TOMBSTONE)
03-21 07:32:37.426  1019  3265 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
03-21 07:32:37.426  3238  3280 D ContactProvider: getAllContactInfoList Start
03-21 07:32:37.426  1019  1630 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
03-21 07:32:37.436   259   259 I SurfaceFlinger: id=12 createSurf (1x1),1 flag=404, NainActivit
,03-21 07:32:37.456  1019  1019 D CrashAnrDetector: Build: samsung/a3ultexx/a3ulte:5.0.2/LRX22G/A300FUXXU1BOEC:user/release-keys
03-21 07:32:37.456  1019  1019 D CrashAnrDetector: Hardware: MSM8916
03-21 07:32:37.456  1019  1019 D CrashAnrDetector: Revision: 1
03-21 07:32:37.456  1019  1019 D CrashAnrDetector: Bootloader: A300FUXXU1BOEC
03-21 07:32:37.456  1019  1019 D CrashAnrDetector: Radio: unknown
03-21 07:32:37.456  1019  1019 D CrashAnrDetector: Kernel: Linux version 3.10.49-4866174 (dpi@SWDD6204) (gcc version 4.8 (GCC) ) #1 SMP PREEMPT Fri May 29 20:06:40 KST 2015
03-21 07:32:37.456  1019  1019 D CrashAnrDetector: 
03-21 07:32:37.456  1019  1019 D CrashAnrDetector: *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
03-21 07:32:37.456  1019  1019 D CrashAnrDetector: Build fingerprint: 'samsung/a3ultexx/a3ulte:5.0.2/LRX22G/A300FUXXU1BOEC:user/release-keys'
03-21 07:32:37.456  1019  1019 D CrashAnrDetector: Revision: '1'
03-21 07:32:37.456  1019  1019 D CrashAnrDetector: ABI: 'arm'
03-21 07:32:37.456  1019  1019 D CrashAnrDetector: pid: 3041, tid: 3372, name: Thread-383  >>> com.example.hello <<<
03-21 07:32:37.456  1019  1019 D CrashAnrDetector: signal 11 (SIGSEGV), code 1 (SEGV_MAPERR), fault addr 0x0
03-21 07:32:37.456  1019  1019 D CrashAnrDetector:     r0 00000000  r1 00000000  r2 00000000  r3 00000000
03-21 07:32:37.456  1019  1019 D CrashAnrDetector:     r4 9e1a7e78  r5 9e1a7e38  r6 b7dca130  r7 9e1a7e38
03-21 07:32:37.456  1019  1019 D CrashAnrDetector:     r8 00000000  r9 9e1a7e74  sl 9e1a93d0  fp 9e1a7e1c
03-21 07:32:37.456  1019  1019 D CrashAnrDetector:     ip 9ec7dba0  sp 9e1a7e00  lr 9e984308  pc b6ee9468  cpsr 600d0030
03-21 07:32:37.456  1019  1019 D CrashAnrDetector:     d0  00000035020000d5  d1  513802003a373ef1
03-21 07:32:37.456  1019  1019 D CrashAnrDetector:     d2  0000b80c0300009d  d3  88000000560a1060
03-21 07:32:37.456  1019  1019 D CrashAnrDetector:     d4  07490c0000003d01  d5  0000008849000000
03-21 07:32:37.456  1019  1019 D CrashAnrDetector:     d6  0a0e000000b80c0c  d7  01003a0f0000003d
03-21 07:32:37.456  1019  1019 D CrashAnrDetector:     d8  0000000000000000  d9  0000000000000000
03-21 07:32:37.456  1019  1019 D CrashAnrDetector:     d10 0000000000000000  d11 0000000000000000
03-21 07:32:37.456  1019  1019 D CrashAnrDetector:     d12 0000000000000000  d13 0000000000000000
03-21 07:32:37.456  1019  1019 D CrashAnrDetector:     d14 0000000000000000  d15 0000000000000000
03-21 07:32:37.456  1019  1019 D CrashAnrDetector:     d16 0000000000000000  d17 ffffffffffffffff
03-21 07:32:37.456  1019  1019 D CrashAnrDetector:     d18 0001000100010001  d19 0001000100010001
03-21 07:32:37.456  1019  1019 D CrashAnrDetector:     d20 0000000000000001  d21 0000000000000000
03-21 07:32:37.456  1019  1019 D CrashAnrDetector:     d22 0000000000000000  d23 0000000000000000
03-21 07:32:37.456  1019  1019 D CrashAnrDetector:     d24 0000000000000000  d25 0000000000000000
03-21 07:32:37.456  1019  1019 D CrashAnrDetector:     d26 0002000200020001  d27 0002000200020002
03-21 07:32:37.456  1019  1019 D CrashAnrDetector:     d28 0080008000800080  d29 0080008000800080
03-21 07:32:37.456  1019  1019 D CrashAnrDetector:     d30 0800080008000800  d31 0800080008000800
03-21 07:32:37.456  1019  1019 D CrashAnrDetector:     scr 20000012
03-21 07:32:37.456  1019  1019 D CrashAnrDetector: 
03-21 07:32:37.456  1019  1019 D CrashAnrDetector: backtrace:
03-21 07:32:37.456  1019  1019 D CrashAnrDetector:     #00 pc 00010468  /system/lib/libc.so (strlen+83)
03-21 07:32:37.456  1019  1019 D CrashAnrDetector:     #01 pc 007da304  /data/app/com.example.hello-1/lib/arm/libjxcore.so (MozJS::String::FromUTF8(JSContext*, char const*, int)+40)
03-21 07:32:37.456  1019  1019 D CrashAnrDetector: 
03-21 07:32:37.456  1019  1019 D CrashAnrDetector: stack:
03-21 07:32:37.456  1019  1019 D CrashAnrDetector:          9e1a7d80  00000000  
03-21 07:32:37.456  1019  1019 D CrashAnrDetector:          9e1a7d84  00000000  
03-21 07:32:37.456  1019  1019 D CrashAnrDetector:          9e1a7d88  9de2b820  [anon:js-gc-heap]
03-21 07:32:37.456  1019  1019 D CrashAnrDetector:          9e1a7d8c  f5cf96b7  
03-21 07:32:37.456  1019  1019 D CrashAnrDetector:          9e1a7d90  9e1a7dbc  [stack:3372]
03-21 07:32:37.456  1019  1019 D CrashAnrDetector:          9e1a7d94  9e1a7e64  [stack:3372]
03-21 07:32:37.456  1019  1019 D CrashAnrDetector:          9e1a7d98  b7dca130  [heap]
03-21 07:32:37.456  1019  1019 D CrashAnrDetector:          9e1a7d9c  00000003  
03-21 07:32:37.456  1019  1019 D CrashAnrDetector:          9e1a7da0  9e1a7ddc  [stack:3372]
03-21 07:32:37.456  1019  1019 D CrashAnrDetector:          9e1a7da4  b7ebd960  [heap]
03-21 07:32:37.456  1019  1019 D CrashAnrDetector:          9e1a7da8  9de53b00  [anon:js-gc-heap]
03-21 07:32:37.456  1019  1019 D CrashAnrDetector:          9e1a7dac  9df11b30  [anon:js-gc-heap]
03-21 07:32:37.456  1019  1019 D CrashAnrDetector:          9e1a7db0  00000000  
03-21 07:32:37.456  1019  1019 D CrashAnrDetector:          9e1a7db4  ffffff82  
03-21 07:32:37.456  1019  1019 D CrashAnrDetector:          9e1a7db8  00000000  
03-21 07:32:37.456  1019  1019 D CrashAnrDetector:          9e1a7dbc  ffffff82  
03-21 07:32:37.456  1019  1019 D CrashAnrDetector:          9e1a7dc0  9de2b040  [anon:js-gc-heap]
03-21 07:32:37.456  1019  1019 D CrashAnrDetector:          9e1a7dc4  b7eba960  [heap]
03-21 07:32:37.456  1019  1019 D CrashAnrDetector:          9e1a7dc8  b7f16b48  [heap]
03-21 07:32:37.456  1019  1019 D CrashAnrDetector:          9e1a7dcc  00000001  
03-21 07:32:37.456  1019  1019 D CrashAnrDetector:          9e1a7dd0  9de49160  [anon:js-gc-heap]
03-21 07:32:37.456  1019  1019 D CrashAnrDetector:          9e1a7dd4  b7dca130  [heap]
03-21 07:32:37.456  1019  1019 D CrashAnrDetector:          9e1a7dd8  9de4f1c0  [anon:js-gc-heap]
03-21 07:32:37.456  1019  1019 D CrashAnrDetector:          9e1a7ddc  00000000  
03-21 07:32:37.456  1019  1019 D CrashAnrDetector:          9e1a7de0  00000000  
03-21 07:32:37.456  1019  1019 D CrashAnrDetector:          9e1a7de4  00000000  
03-21 07:32:37.456  1019  1019 D CrashAnrDetector:          9e1a7de8  00000003  
03-21 07:32:37.456  1019  1019 D CrashAnrDetector:          9e1a7dec  000000aa  
03-21 07:32:37.456  1019  1019 D CrashAnrDetector:          9e1a7df0  0000006b  
03-21 07:32:37.456  1019  1019 D CrashAnrDetector:          9e1a7df4  0001416e  
03-21 07:32:37.456  1019  1019 D CrashAnrDetector:          9e1a7df8  00000000  
03-21 07:32:37.456  1019  1019 D CrashAnrDetector:          9e1a7dfc  9e1a7e30  [stack:3372]
03-21 07:32:37.456  1019  1019 D CrashAnrDetector:     #00  9e1a7e00  9e1a7e78  [stack:3372]
03-21 07:32:37.456  1019  1019 D CrashAnrDetector:          ........  ........
03-21 07:32:37.456  1019  1019 D CrashAnrDetector:     #01  9e1a7e00  9e1a7e78  [stack:3372]
03-21 07:32:37.456  1019  1019 D CrashAnrDetector:          9e1a7e04  00000000  
03-21 07:32:37.456  1019  1019 D CrashAnrDetector:          9e1a7e08  9e1a7e78  [stack:3372]
03-21 07:32:37.456  1019  1019 D CrashAnrDetector:          9e1a7e0c  9e1a7e5c  [stack:3372]
03-21 07:32:37.456  1019  1019 D CrashAnrDetector:          9e1a7e10  9e1a7e48  [stack:3372]
03-21 07:32:37.456  1019  1019 D CrashAnrDetector:          9e1a7e14  00000000  
03-21 07:32:37.456  1019  1019 D CrashAnrDetector:          9e1a7e18  9e1a8e94  [stack:3372]
03-21 07:32:37.456  1019  1019 D CrashAnrDetector:          9e1a7e1c  9e95b3f0  /data/app/com.example.hello-1/lib/arm/libjxcore.so
03-21 07:32:37.456  1019  1019 D CrashAnrDetector:          9e1a7e20  9e1a7e50  [stack:3372]
03-21 07:32:37.456  1019  1019 D CrashAnrDetector:          9e1a7e24  00000000  
03-21 07:32:37.456  1019  1019 D CrashAnrDetector:          9e1a7e28  9e1a7e44  [stack:3372]
03-21 07:32:37.456  1019  1019 D CrashAnrDetector:          9e1a7e2c  9e78d184  /data/app/com.example.hello-1/lib/arm/libjxcore.so (js_fun_call(JSContext*, unsigned int, JS::Value*)+172)
03-21 07:32:37.456  1019  1019 D CrashAnrDetector:          9e1a7e30  00000000  
03-21 07:32:37.456  1019  1019 D CrashAnrDet,ector:          9e1a7e34  00000000  
03-21 07:32:37.456  1019  1019 D CrashAnrDetector:          9e1a7e38  b6f2fde4  
03-21 07:32:37.456  1019  1019 D CrashAnrDetector:          9e1a7e3c  00000000  
03-21 07:32:37.456  1019  1019 D CrashAnrDetector:          9e1a7e40  9e1a81cc  [stack:3372]
03-21 07:32:37.456  1019  1019 D CrashAnrDetector:          9e1a7e44  9e869b34  /data/app/com.example.hello-1/lib/arm/libjxcore.so (js::Invoke(JSContext*, JS::CallArgs, js::MaybeConstruct)+340)
03-21 07:32:37.456  1019  1019 D CrashAnrDetector:          9e1a7e48  b7dca130  [heap]
03-21 07:32:37.456  1019  1019 D CrashAnrDetector:          9e1a7e4c  b7dca130  [heap]
03-21 07:32:37.456  1019  1019 D CrashAnrDetector:          9e1a7e50  b7f16b48  [heap]
03-21 07:32:37.456  1019  1019 D CrashAnrDetector:          9e1a7e54  00000001  
03-21 07:32:37.456  1019  1019 D CrashAnrDetector:          9e1a7e58  9
03-21 07:32:37.456  1019  1019 D CrashAnrDetector: processName:com.example.hello
03-21 07:32:37.456  1019  1019 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 com.android.server.analytics.data.collection.application.CrashAnrDetector.broadcastEvent:296 com.android.server.analytics.data.collection.application.CrashAnrDetector.processDropBoxEntry:254 com.android.server.analytics.data.collection.application.CrashAnrDetector.access$100:60 com.android.server.analytics.data.collection.application.CrashAnrDetector$1.onReceive:102 
03-21 07:32:37.456  1019  1019 D CrashAnrDetector: broadcastEvent : null SYSTEM_TOMBSTONE
03-21 07:32:37.456  1019  1031 D InputDispatcher: Focus entered window: 3153
03-21 07:32:37.466  1019  1049 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-21 07:32:37.466  1019  1049 D PointerIcon: setMouseCustomIcon IconType is same.101
03-21 07:32:37.466  3153  3153 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
03-21 07:32:37.466  3153  3279 I OpenGLRenderer: Initialized EGL, version 1.4
03-21 07:32:37.476  3238  3280 D ContactProvider: getAllContactInfoList End
03-21 07:32:37.476  3238  3280 I syncContacts: thread: 433, sync time = 66
03-21 07:32:37.476  1019  3191 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-21 07:32:37.486  3153  3279 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
03-21 07:32:37.486  3153  3279 D OpenGLRenderer: Enabling debug mode 0
03-21 07:32:37.486  1019  3208 I BootReceiver: Copying /data/tombstones/tombstone_05 to DropBox (SYSTEM_TOMBSTONE)
03-21 07:32:37.486  1019  3265 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
03-21 07:32:37.486  1019  3191 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-21 07:32:37.496  1019  3191 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-21 07:32:37.496  1019  3191 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,03-21 07:32:37.496  1019  3191 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-21 07:32:37.496  1019  3191 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-21 07:32:37.496  1019  3191 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,03-21 07:32:37.506  1019  1019 D CrashAnrDetector: Build: samsung/a3ultexx/a3ulte:5.0.2/LRX22G/A300FUXXU1BOEC:user/release-keys
03-21 07:32:37.506  1019  1019 D CrashAnrDetector: Hardware: MSM8916
03-21 07:32:37.506  1019  1019 D CrashAnrDetector: Revision: 1
03-21 07:32:37.506  1019  1019 D CrashAnrDetector: Bootloader: A300FUXXU1BOEC
03-21 07:32:37.506  1019  1019 D CrashAnrDetector: Radio: unknown
03-21 07:32:37.506  1019  1019 D CrashAnrDetector: Kernel: Linux version 3.10.49-4866174 (dpi@SWDD6204) (gcc version 4.8 (GCC) ) #1 SMP PREEMPT Fri May 29 20:06:40 KST 2015
03-21 07:32:37.506  1019  1019 D CrashAnrDetector: 
03-21 07:32:37.506  1019  1019 D CrashAnrDetector: *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
03-21 07:32:37.506  1019  1019 D CrashAnrDetector: Build fingerprint: 'samsung/a3ultexx/a3ulte:5.0.2/LRX22G/A300FUXXU1BOEC:user/release-keys'
03-21 07:32:37.506  1019  1019 D CrashAnrDetector: Revision: '1'
03-21 07:32:37.506  1019  1019 D CrashAnrDetector: ABI: 'arm'
03-21 07:32:37.506  1019  1019 D CrashAnrDetector: pid: 4387, tid: 4703, name: Thread-677  >>> com.test.thalitest <<<
03-21 07:32:37.506  1019  1019 D CrashAnrDetector: signal 11 (SIGSEGV), code 1 (SEGV_MAPERR), fault addr 0x0
03-21 07:32:37.506  1019  1019 D CrashAnrDetector:     r0 00000000  r1 9dbf6494  r2 00000002  r3 00000000
03-21 07:32:37.506  1019  1019 D CrashAnrDetector:     r4 b8d43750  r5 00000000  r6 b8d42fe0  r7 bb70b440
03-21 07:32:37.506  1019  1019 D CrashAnrDetector:     r8 b8d2beb4  r9 b8d43750  sl b8d42fb8  fp 9dbf648c
03-21 07:32:37.506  1019  1019 D CrashAnrDetector:     ip ffffffff  sp 9dbf647c  lr 9e0d1b30  pc 9e0d1a34  cpsr 60000010
03-21 07:32:37.506  1019  1019 D CrashAnrDetector:     d0  0000000000000000  d1  0000000000000000
03-21 07:32:37.506  1019  1019 D CrashAnrDetector:     d2  0000000000000000  d3  0000000000000000
03-21 07:32:37.506  1019  1019 D CrashAnrDetector:     d4  0000000000000000  d5  0000000000000000
03-21 07:32:37.506  1019  1019 D CrashAnrDetector:     d6  0000000000000000  d7  0000000000000000
03-21 07:32:37.506  1019  1019 D CrashAnrDetector:     d8  0000000000000000  d9  0000000000000000
03-21 07:32:37.506  1019  1019 D CrashAnrDetector:     d10 0000000000000000  d11 0000000000000000
03-21 07:32:37.506  1019  1019 D CrashAnrDetector:     d12 0000000000000000  d13 0000000000000000
03-21 07:32:37.506  1019  1019 D CrashAnrDetector:     d14 0000000000000000  d15 0000000000000000
03-21 07:32:37.506  1019  1019 D CrashAnrDetector:     d16 000027b7000027b7  d17 000027b700000000
03-21 07:32:37.506  1019  1019 D CrashAnrDetector:     d18 0001000100010001  d19 0001000100010001
03-21 07:32:37.506  1019  1019 D CrashAnrDetector:     d20 0000000100010001  d21 0000000000000000
03-21 07:32:37.506  1019  1019 D CrashAnrDetector:     d22 0000000000000000  d23 0000000000000000
03-21 07:32:37.506  1019  1019 D CrashAnrDetector:     d24 0000000000000000  d25 0000000000000000
03-21 07:32:37.506  1019  1019 D CrashAnrDetector:     d26 0002000100010001  d27 0002000200020002
03-21 07:32:37.506  1019  1019 D CrashAnrDetector:     d28 0080008000800080  d29 0080008000800080
03-21 07:32:37.506  1019  1019 D CrashAnrDetector:     d30 0800080008000800  d31 0800080008000800
03-21 07:32:37.506  1019  1019 D CrashAnrDetector:     scr 20000012
03-21 07:32:37.506  1019  1019 D CrashAnrDetector: 
03-21 07:32:37.506  1019  1019 D CrashAnrDetector: backtrace:
03-21 07:32:37.506  1019  1019 D CrashAnrDetector:     #00 pc 003d1a34  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (bool ThingIsPermanentAtom<JS::Symbol>(JS::Symbol*)+4)
03-21 07:32:37.506  1019  1019 D CrashAnrDetector:     #01 pc 003d1b2c  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so
03-21 07:32:37.506  1019  1019 D CrashAnrDetector:     #02 pc e5943000  <unknown>
03-21 07:32:37.506  1019  1019 D CrashAnrDetector: 
03-21 07:32:37.506  1019  1019 D CrashAnrDetector: stack:
03-21 07:32:37.506  1019  1019 D CrashAnrDetector:          9dbf63fc  00000006  
03-21 07:32:37.506  1019  1019 D CrashAnrDetector,:          9dbf6400  8fd92780  [anon:js-gc-heap]
03-21 07:32:37.506  1019  1019 D CrashAnrDetector:          9dbf6404  b8d43750  [heap]
03-21 07:32:37.506  1019  1019 D CrashAnrDetector:          9dbf6408  9e611b34  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so
03-21 07:32:37.506  1019  1019 D CrashAnrDetector:          9dbf640c  b8d43750  [heap]
03-21 07:32:37.506  1019  1019 D CrashAnrDetector:          9dbf6410  9dbf642c  [stack:4703]
03-21 07:32:37.506  1019  1019 D CrashAnrDetector:          9dbf6414  9e2f2258  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (JSScript::markChildren(JSTracer*)+404)
03-21 07:32:37.506  1019  1019 D CrashAnrDetector:          9dbf6418  00000001  
03-21 07:32:37.506  1019  1019 D CrashAnrDetector:          9dbf641c  00000000  
03-21 07:32:37.506  1019  1019 D CrashAnrDetector:          9dbf6420  b8d44280  [heap]
03-21 07:32:37.506  1019  1019 D CrashAnrDetector:          9dbf6424  00000000  
03-21 07:32:37.506  1019  1019 D CrashAnrDetector:          9dbf6428  00000000  
03-21 07:32:37.506  1019  1019 D CrashAnrDetector:          9dbf642c  b8d43750  [heap]
03-21 07:32:37.506  1019  1019 D CrashAnrDetector:          9dbf6430  b8d44280  [heap]
03-21 07:32:37.506  1019  1019 D CrashAnrDetector:          9dbf6434  9e75db60  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so
03-21 07:32:37.506  1019  1019 D CrashAnrDetector:          9dbf6438  9dbf64a4  [stack:4703]
03-21 07:32:37.506  1019  1019 D CrashAnrDetector:          9dbf643c  9e0d8514  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (js::gc::GCRuntime::markConservativeStackRoots(JSTracer*, bool)+1308)
03-21 07:32:37.506  1019  1019 D CrashAnrDetector:          9dbf6440  b8d43750  [heap]
03-21 07:32:37.506  1019  1019 D CrashAnrDetector:          9dbf6444  b8d42fb8  [heap]
03-21 07:32:37.506  1019  1019 D CrashAnrDetector:          9dbf6448  9dbfc000  
03-21 07:32:37.506  1019  1019 D CrashAnrDetector:          9dbf644c  9dbf6470  [stack:4703]
03-21 07:32:37.506  1019  1019 D CrashAnrDetector:          9dbf6450  9dbf6468  [stack:4703]
03-21 07:32:37.506  1019  1019 D CrashAnrDetector:          9dbf6454  9dbf6474  [stack:4703]
03-21 07:32:37.506  1019  1019 D CrashAnrDetector:          9dbf6458  9e6846d4  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so
03-21 07:32:37.506  1019  1019 D CrashAnrDetector:          9dbf645c  9dbf6478  [stack:4703]
03-21 07:32:37.506  1019  1019 D CrashAnrDetector:          9dbf6460  00000004  
03-21 07:32:37.506  1019  1019 D CrashAnrDetector:          9dbf6464  00000000  
03-21 07:32:37.506  1019  1019 D CrashAnrDetector:          9dbf6468  00000001  
03-21 07:32:37.506  1019  1019 D CrashAnrDetector:          9dbf646c  b8d43750  [heap]
03-21 07:32:37.506  1019  1019 D CrashAnrDetector:          9dbf6470  8fdcd3a0  [anon:js-gc-heap]
03-21 07:32:37.506  1019  1019 D CrashAnrDetector:          9dbf6474  b8d42fe0  [heap]
03-21 07:32:37.506  1019  1019 D CrashAnrDetector:          9dbf6478  9dbf648c  [stack:4703]
03-21 07:32:37.506  1019  1019 D CrashAnrDetector:     #00  9dbf647c  9dbf648c  [stack:4703]
03-21 07:32:37.506  1019  1019 D CrashAnrDetector:          9dbf6480  9dbfb838  [stack:4703]
03-21 07:32:37.506  1019  1019 D CrashAnrDetector:          9dbf6484  bb701888  [heap]
03-21 07:32:37.506  1019  1019 D CrashAnrDetector:          9dbf6488  9dbf64a4  [stack:4703]
03-21 07:32:37.506  1019  1019 D CrashAnrDetector:          9dbf648c  9e0d506c  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (js::gc::MarkValueRoot(JSTracer*, JS::Value*, char const*)+80)
03-21 07:32:37.506  1019  1019 D CrashAnrDetector:     #01  9dbf6490  b8d2beb4  [heap]
03-21 07:32:37.506  1019  1019 D CrashAnrDetector:          9dbf6494  00000000  
03-21 07:32:37.506  1019  1019 D CrashAnrDetector:          9dbf6498  b8d42fdc  [heap]
03-21 07:32:37.506  1019  1019 D CrashAnrDetector:          9dbf649c  9e605cd8  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so
03-21 07:32:37.506  1019  1019 D CrashAnrDetector:          9dbf64a0  9dbf64fc  [stack:4703]
03-21 07:32:37.506  1019  1019 D CrashAnrDetector:          9dbf64a4  9e0d9dcc  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (js::gc::GCRuntime::markRuntime(JSTracer*, js::gc::GCRuntime::TraceOrMarkRuntime, js::gc::GCRuntime::TraceRootsOrUs
03-21 07:32:37.506  1019  1019 D CrashAnrDetector: processName:com.test.thalitest
03-21 07:32:37.506  1019  3191 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-21 07:32:37.506  1019  1019 D CrashAnrDetector: broadcastEvent : com.test.thalitest SYSTEM_TOMBSTONE
03-21 07:32:37.506  1019  3191 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
03-21 07:32:37.506  1019  1019 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 com.android.server.analytics.data.collection.application.CrashAnrDetector.broadcastEvent:296 com.android.server.analytics.data.collection.application.CrashAnrDetector.processDropBoxEntry:254 com.android.server.analytics.data.collection.application.CrashAnrDetector.access$100:60 com.android.server.analytics.data.collection.application.CrashAnrDetector$1.onReceive:102 
03-21 07:32:37.506  1019  3191 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-21 07:32:37.536  3170  3170 D BluetoothAdapterState: make
,03-21 07:32:37.536  3170  3170 I bluedroid: init
03-21 07:32:37.536  3170  3288 I BluetoothAdapterState: Entering OffState
03-21 07:32:37.546  1999  1999 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
03-21 07:32:37.546  1019  1564 D SettingsProvider: name = db_smartlock_supported
03-21 07:32:37.556  3170  3170 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
03-21 07:32:37.556  3170  3170 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
03-21 07:32:37.556  3170  3170 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
03-21 07:32:37.556  3170  3170 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
03-21 07:32:37.556  3170  3170 E bt-btif : btif_fetch_local_ble_random_bdaddr
03-21 07:32:37.556  3170  3170 I bluedroid: get_profile_interface socket
03-21 07:32:37.556  3170  3170 I bluedroid: get_profile_interface map_client
03-21 07:32:37.566  1019  1032 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
03-21 07:32:37.566  3170  3170 D BluetoothAdapterService: checkAddrForIOP: Loading from conf
03-21 07:32:37.566  1019  3292 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
03-21 07:32:37.566  1019  3208 I BootReceiver: Copying /data/tombstones/tombstone_06 to DropBox (SYSTEM_TOMBSTONE)
03-21 07:32:37.576  1019  3265 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
03-21 07:32:37.576  1181  1181 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-21 07:32:37.586  3170  3291 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
03-21 07:32:37.586  3170  3291 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
03-21 07:32:37.586  3170  3291 E BluetoothServiceJni: populateRssiValuesNative
03-21 07:32:37.586  3170  3291 I bluedroid: getModelRssiValues
,03-21 07:32:37.586  3170  3291 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
03-21 07:32:37.586  3170  3291 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,03-21 07:32:37.586  1181  1181 I StatusBar: Icon Only
03-21 07:32:37.586  1181  1181 D PanelView: There is/are notification(s) 
,03-21 07:32:37.586  1019  3293 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-21 07:32:37.596  3153  3153 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@fea52fc time:37745
,03-21 07:32:37.596  3170  3291 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3)
,03-21 07:32:37.606  1019  1630 W ActivityManager: userId = 0, bbcId = -10000
03-21 07:32:37.606  1019  1630 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-21 07:32:37.606  1019  1630 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,03-21 07:32:37.606  1019  1049 I ActivityManager: Displayed Component not be shown by security: +1s95ms
,03-21 07:32:37.606  1019  1049 W ActivityManager: mDVFSHelper.release()
03-21 07:32:37.606  1019  1049 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{1c02f8aa u0 com.test.thalitest/.MainActivity t11} time:37755
,03-21 07:32:37.606  1019  1019 D CrashAnrDetector: Build: samsung/a3ultexx/a3ulte:5.0.2/LRX22G/A300FUXXU1BOEC:user/release-keys
03-21 07:32:37.606  1019  1019 D CrashAnrDetector: Hardware: MSM8916
03-21 07:32:37.606  1019  1019 D CrashAnrDetector: Revision: 1
03-21 07:32:37.606  1019  1019 D CrashAnrDetector: Bootloader: A300FUXXU1BOEC
03-21 07:32:37.606  1019  1019 D CrashAnrDetector: Radio: unknown
03-21 07:32:37.606  1019  1019 D CrashAnrDetector: Kernel: Linux version 3.10.49-4866174 (dpi@SWDD6204) (gcc version 4.8 (GCC) ) #1 SMP PREEMPT Fri May 29 20:06:40 KST 2015
03-21 07:32:37.606  1019  1019 D CrashAnrDetector: 
03-21 07:32:37.606  1019  1019 D CrashAnrDetector: *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
03-21 07:32:37.606  1019  1019 D CrashAnrDetector: Build fingerprint: 'samsung/a3ultexx/a3ulte:5.0.2/LRX22G/A300FUXXU1BOEC:user/release-keys'
03-21 07:32:37.606  1019  1019 D CrashAnrDetector: Revision: '1'
03-21 07:32:37.606  1019  1019 D CrashAnrDetector: ABI: 'arm'
03-21 07:32:37.606  1019  1019 D CrashAnrDetector: pid: 3807, tid: 4175, name: Thread-562  >>> com.test.thalitest <<<
03-21 07:32:37.606  1019  1019 D CrashAnrDetector: signal 11 (SIGSEGV), code 1 (SEGV_MAPERR), fault addr 0x0
03-21 07:32:37.606  1019  1019 D CrashAnrDetector:     r0 00000000  r1 9368b424  r2 00000002  r3 00000000
03-21 07:32:37.606  1019  1019 D CrashAnrDetector:     r4 b7a20c80  r5 00000000  r6 b7a20510  r7 b9bb7a70
03-21 07:32:37.606  1019  1019 D CrashAnrDetector:     r8 b7a7363c  r9 b7a20c80  sl b7a204e8  fp 9368b41c
03-21 07:32:37.606  1019  1019 D CrashAnrDetector:     ip ffffffff  sp 9368b40c  lr 93d81b30  pc 93d81a34  cpsr 60000010
03-21 07:32:37.606  1019  1019 D CrashAnrDetector:     d0  0000000000000000  d1  0000000000000000
03-21 07:32:37.606  1019  1019 D CrashAnrDetector:     d2  0000000000000000  d3  0000000000000000
03-21 07:32:37.606  1019  1019 D CrashAnrDetector:     d4  0000000000000000  d5  0000000000000000
03-21 07:32:37.606  1019  1019 D CrashAnrDetector:     d6  0000000000000000  d7  0000000000000000
03-21 07:32:37.606  1019  1019 D CrashAnrDetector:     d8  0000000000000000  d9  0000000000000000
03-21 07:32:37.606  1019  1019 D CrashAnrDetector:     d10 0000000000000000  d11 0000000000000000
03-21 07:32:37.606  1019  1019 D CrashAnrDetector:     d12 0000000000000000  d13 0000000000000000
03-21 07:32:37.606  1019  1019 D CrashAnrDetector:     d14 0000000000000000  d15 0000000000000000
03-21 07:32:37.606  1019  1019 D CrashAnrDetector:     d16 000027b7000027b7  d17 000027b700000000
03-21 07:32:37.606  1019  1019 D CrashAnrDetector:     d18 0001000100010001  d19 0001000100010001
03-21 07:32:37.606  1019  1019 D CrashAnrDetector:     d20 0000000100010001  d21 0000000000000000
03-21 07:32:37.606  1019  1019 D CrashAnrDetector:     d22 0000000000000000  d23 0000000000000000
03-21 07:32:37.606  1019  1019 D CrashAnrDetector:     d24 0000000000000000  d25 0000000000000000
03-21 07:32:37.606  1019  1019 D CrashAnrDetector:     d26 0002000100010001  d27 0002000200020002
03-21 07:32:37.606  1019  1019 D CrashAnrDetector:     d28 0080008000800080  d29 0080008000800080
03-21 07:32:37.606  1019  1019 D CrashAnrDetector:     d30 0800080008000800  d31 0800080008000800
03-21 07:32:37.606  1019  1019 D CrashAnrDetector:     scr 20000012
03-21 07:32:37.606  1019  1019 D CrashAnrDetector: 
03-21 07:32:37.606  1019  1019 D CrashAnrDetector: backtrace:
03-21 07:32:37.606  1019  1019 D CrashAnrDetector:     #00 pc 003d1a34  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (bool ThingIsPermanentAtom<JS::Symbol>(JS::Symbol*)+4)
03-21 07:32:37.606  1019  1019 D CrashAnrDetector:     #01 pc 003d1b2c  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so
03-21 07:32:37.606  1019  1019 D CrashAnrDetector:     #02 pc e5943000  <unknown>
03-21 07:32:37.606  1019  1019 D CrashAnrDetector: 
03-21 07:32:37.606  1019  1019 D CrashAnrDetector: stack:
03-21 07:32:37.606  1019  1019 D CrashAnrDetector:          9368b38c  00000006  
03-21 07:32:37.606  1019  1019 D CrashAnrDetector,:          9368b390  90f5e780  [anon:js-gc-heap]
03-21 07:32:37.606  1019  1019 D CrashAnrDetector:          9368b394  b7a20c80  [heap]
03-21 07:32:37.606  1019  1019 D CrashAnrDetector:          9368b398  942c1b34  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so
03-21 07:32:37.606  1019  1019 D CrashAnrDetector:          9368b39c  b7a20c80  [heap]
03-21 07:32:37.606  1019  1019 D CrashAnrDetector:          9368b3a0  9368b3bc  [stack:4175]
03-21 07:32:37.606  1019  1019 D CrashAnrDetector:          9368b3a4  93fa2258  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (JSScript::markChildren(JSTracer*)+404)
03-21 07:32:37.606  1019  1019 D CrashAnrDetector:          9368b3a8  00000001  
03-21 07:32:37.606  1019  1019 D CrashAnrDetector:          9368b3ac  00000000  
03-21 07:32:37.606  1019  1019 D CrashAnrDetector:          9368b3b0  b7a217b0  [heap]
03-21 07:32:37.606  1019  1019 D CrashAnrDetector:          9368b3b4  00000000  
03-21 07:32:37.606  1019  1019 D CrashAnrDetector:          9368b3b8  00000000  
03-21 07:32:37.606  1019  1019 D CrashAnrDetector:          9368b3bc  b7a20c80  [heap]
03-21 07:32:37.606  1019  1019 D CrashAnrDetector:          9368b3c0  b7a217b0  [heap]
03-21 07:32:37.606  1019  1019 D CrashAnrDetector:          9368b3c4  9440db60  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so
03-21 07:32:37.606  1019  1019 D CrashAnrDetector:          9368b3c8  9368b434  [stack:4175]
03-21 07:32:37.606  1019  1019 D CrashAnrDetector:          9368b3cc  93d88514  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (js::gc::GCRuntime::markConservativeStackRoots(JSTracer*, bool)+1308)
03-21 07:32:37.606  1019  1019 D CrashAnrDetector:          9368b3d0  b7a20c80  [heap]
03-21 07:32:37.606  1019  1019 D CrashAnrDetector:          9368b3d4  b7a204e8  [heap]
03-21 07:32:37.606  1019  1019 D CrashAnrDetector:          9368b3d8  93693000  
03-21 07:32:37.606  1019  1019 D CrashAnrDetector:          9368b3dc  9368b400  [stack:4175]
03-21 07:32:37.606  1019  1019 D CrashAnrDetector:          9368b3e0  9368b3f8  [stack:4175]
03-21 07:32:37.606  1019  1019 D CrashAnrDetector:          9368b3e4  9368b404  [stack:4175]
03-21 07:32:37.606  1019  1019 D CrashAnrDetector:          9368b3e8  943346d4  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so
03-21 07:32:37.606  1019  1019 D CrashAnrDetector:          9368b3ec  9368b408  [stack:4175]
03-21 07:32:37.606  1019  1019 D CrashAnrDetector:          9368b3f0  00000004  
03-21 07:32:37.606  1019  1019 D CrashAnrDetector:          9368b3f4  00000000  
03-21 07:32:37.606  1019  1019 D CrashAnrDetector:          9368b3f8  00000001  
03-21 07:32:37.606  1019  1019 D CrashAnrDetector:          9368b3fc  b7a20c80  [heap]
03-21 07:32:37.606  1019  1019 D CrashAnrDetector:          9368b400  b7a20c80  [heap]
03-21 07:32:37.606  1019  1019 D CrashAnrDetector:          9368b404  929401e0  [anon:js-gc-heap]
03-21 07:32:37.606  1019  1019 D CrashAnrDetector:          9368b408  9368b41c  [stack:4175]
03-21 07:32:37.606  1019  1019 D CrashAnrDetector:     #00  9368b40c  9368b41c  [stack:4175]
03-21 07:32:37.606  1019  1019 D CrashAnrDetector:          9368b410  93692838  [stack:4175]
03-21 07:32:37.606  1019  1019 D CrashAnrDetector:          9368b414  b9bb3cd8  [heap]
03-21 07:32:37.606  1019  1019 D CrashAnrDetector:          9368b418  9368b434  [stack:4175]
03-21 07:32:37.606  1019  1019 D CrashAnrDetector:          9368b41c  93d8506c  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (js::gc::MarkValueRoot(JSTracer*, JS::Value*, char const*)+80)
03-21 07:32:37.606  1019  1019 D CrashAnrDetector:     #01  9368b420  b7a7363c  [heap]
03-21 07:32:37.606  1019  1019 D CrashAnrDetector:          9368b424  00000000  
03-21 07:32:37.606  1019  1019 D CrashAnrDetector:          9368b428  b7a2050c  [heap]
03-21 07:32:37.606  1019  1019 D CrashAnrDetector:          9368b42c  942b5cd8  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so
03-21 07:32:37.606  1019  1019 D CrashAnrDetector:          9368b430  9368b48c  [stack:4175]
03-21 07:32:37.,606  1019  1019 D CrashAnrDetector:          9368b434  93d89dcc  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (js::gc::GCRuntime::markRuntime(JSTracer*, js::gc::GCRuntime::TraceOrMarkRuntime, js::gc::GCRuntime::TraceRootsOrUs
03-21 07:32:37.606  1019  1019 D CrashAnrDetector: processName:com.test.thalitest
03-21 07:32:37.606  1019  1019 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 com.android.server.analytics.data.collection.application.CrashAnrDetector.broadcastEvent:296 com.android.server.analytics.data.collection.application.CrashAnrDetector.processDropBoxEntry:254 com.android.server.analytics.data.collection.application.CrashAnrDetector.access$100:60 com.android.server.analytics.data.collection.application.CrashAnrDetector$1.onReceive:102 
03-21 07:32:37.606  1019  1019 D CrashAnrDetector: broadcastEvent : com.test.thalitest SYSTEM_TOMBSTONE
03-21 07:32:37.606  1019  1032 I ActivityManager: Killing 2392:com.sec.android.app.mt/1000 (adj 15): empty #31
03-21 07:32:37.616  1019  1019 D SettingsProvider: name = bluetooth_name
03-21 07:32:37.616  1019  3208 I BootReceiver: Copying /data/tombstones/tombstone_07 to DropBox (SYSTEM_TOMBSTONE)
03-21 07:32:37.616  1019  3265 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
03-21 07:32:37.636  1019  1019 D CrashAnrDetector: Build: samsung/a3ultexx/a3ulte:5.0.2/LRX22G/A300FUXXU1BOEC:user/release-keys
03-21 07:32:37.636  1019  1019 D CrashAnrDetector: Hardware: MSM8916
03-21 07:32:37.636  1019  1019 D CrashAnrDetector: Revision: 1
03-21 07:32:37.636  1019  1019 D CrashAnrDetector: Bootloader: A300FUXXU1BOEC
03-21 07:32:37.636  1019  1019 D CrashAnrDetector: Radio: unknown
03-21 07:32:37.636  1019  1019 D CrashAnrDetector: Kernel: Linux version 3.10.49-4866174 (dpi@SWDD6204) (gcc version 4.8 (GCC) ) #1 SMP PREEMPT Fri May 29 20:06:40 KST 2015
03-21 07:32:37.636  1019  1019 D CrashAnrDetector: 
03-21 07:32:37.636  1019  1019 D CrashAnrDetector: *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
03-21 07:32:37.636  1019  1019 D CrashAnrDetector: Build fingerprint: 'samsung/a3ultexx/a3ulte:5.0.2/LRX22G/A300FUXXU1BOEC:user/release-keys'
03-21 07:32:37.636  1019  1019 D CrashAnrDetector: Revision: '1'
03-21 07:32:37.636  1019  1019 D CrashAnrDetector: ABI: 'arm'
03-21 07:32:37.636  1019  1019 D CrashAnrDetector: pid: 3548, tid: 4067, name: Thread-502  >>> com.test.thalitest <<<
03-21 07:32:37.636  1019  1019 D CrashAnrDetector: signal 11 (SIGSEGV), code 1 (SEGV_MAPERR), fault addr 0x0
03-21 07:32:37.636  1019  1019 D CrashAnrDetector:     r0 00000000  r1 9372793c  r2 00000002  r3 00000000
03-21 07:32:37.636  1019  1019 D CrashAnrDetector:     r4 b8aef3c8  r5 00000000  r6 b8aeec58  r7 b8cc7760
03-21 07:32:37.636  1019  1019 D CrashAnrDetector:     r8 b8b7cde4  r9 b8aef3c8  sl b8aeec30  fp 93727934
03-21 07:32:37.636  1019  1019 D CrashAnrDetector:     ip ffffffff  sp 93727924  lr 93c02234  pc 93c02138  cpsr 60000010
03-21 07:32:37.636  1019  1019 D CrashAnrDetector:     d0  0000000000000000  d1  0000000000000000
03-21 07:32:37.636  1019  1019 D CrashAnrDetector:     d2  0000000000000000  d3  0000000000000000
03-21 07:32:37.636  1019  1019 D CrashAnrDetector:     d4  0000000000000000  d5  0000000000000000
03-21 07:32:37.636  1019  1019 D CrashAnrDetector:     d6  0000000000000000  d7  0000000000000000
03-21 07:32:37.636  1019  1019 D CrashAnrDetector:     d8  0000000000000000  d9  0000000000000000
03-21 07:32:37.636  1019  1019 D CrashAnrDetector:     d10 0000000000000000  d11 0000000000000000
03-21 07:32:37.636  1019  1019 D CrashAnrDetector:     d12 0000000000000000  d13 0000000000000000
03-21 07:32:37.636  1019  1019 D CrashAnrDetector:     d14 0000000000000000  d15 0000000000000000
03-21 07:32:37.636  1019  1019 D CrashAnrDetector:     d16 000027b7000027b7  d17 000027b700000000
03-21 07:32:37.636  1019  1019 D CrashAnrDetector:     d18 0001000100010001  d19 0001000100010001
03-21 07:32:37.636  1019  1019 D CrashAnrDetector:     d20 0000000100010001  d21 0000000000000000
03-21 07:32:37.636  1019  1019 D CrashAnrDetector:     d22 0000000000000000  d23 0000000000000000
03-21 07:32:37.636  1019  1019 D CrashAnrDetector:     d24 0000000000000000  d25 0000000000000000
03-21 07:32:37.636  1019  1019 D CrashAnrDetector:     d26 0002000100010001  d27 0002000200020002
03-21 07:32:37.636  1019  1019 D CrashAnrDetector:     d28 0080008000800080  d29 0080008000800080
03-21 07:32:37.636  1019  1019 D CrashAnrDetector:     d30 0800080008000800  d31 0800080008000800
03-21 07:32:37.636  1019  1019 D CrashAnrDetector:     scr 20000013
03-21 07:32:37.636  1019  1019 D CrashAnrDetector: 
03-21 07:32:37.636  1019  1019 D CrashAnrDetector: backtrace:
03-21 07:32:37.636  1019  1019 D CrashAnrDetector:     #00 pc 003d1138  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (bool ThingIsPermanentAtom<JS::Symbol>(JS::Symbol*)+4)
03-21 07:32:37.636  1019  1019 D CrashAnrDetector:     #01 pc 003d1230  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so
03-21 07:32:37.636  1019  1019 D CrashAnrDetector:     #02 pc e5943000  <unknown>
03-21 07:32:37.636  1019  1019 D CrashAnrDetector: 
03-21 07:32:37.636  1019  1019 D CrashAnrDetector: stack:
03-21 07:32:37.636  1019  1019 D CrashAnrDetector:          937278a4  00000000  
03-21 07:32:37.636  1019  1019 D CrashAnrDetector:          937278a8  916fc0a0  [anon:js-gc-heap]
03-21 07:32:37.636  1019  1019 D CrashAnrDetector:          937278ac  b8aef3c8  [heap]
03-21 07:32:37.636  1019  1019 D CrashAnrDetector:          937278b0  b8aef3c8  [heap]
03-21 07:32:37.636  1019  1019 D CrashAnrDetector:          937278b4  00000001  
03-21 07:32:37.636  1019  1019 D CrashAnrDetector:          937278b8  937278d4  [stack:4067]
03-21 07:32:37.636  1019  1019 D CrashAnrDetector:          937278bc  93c01854  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so
03-21 07:32:37.636  1019  1019 D CrashAnrDetector:          937278c0  00000001  
03-21 07:32:37.636  1019  1019 D CrashAnrDetector:          937278c4  00000000  
03-21 07:32:37.636  1019  1019 D CrashAnrDetector:          937278c8  b8aefef8  [heap]
03-21 07:32:37.636  1019  1019 D CrashAnrDetector:          937278cc  00000000  
03-21 07:32:37.636  1019  1019 D CrashAnrDetector:          937278d0  00000000  
03-21 07:32:37.636  1019  1019 D CrashAnrDetector:          937278d4  b8aef3c8  [heap]
03-21 07:32:37.636  1019  1019 D CrashAnrDetector:          937278d8  b8aefef8  [heap]
03-21 07:32:37.636  1019  1019 D CrashAnrDetector:          937278dc  9428db60  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so
03-21 07:32:37.636  1019  1019 D CrashAnrDetector:          937278e0  9372794c  [stack:4067]
03-21 07:32:37.636  1019  1019 D CrashAnrDetector:          937278e4  93c08c18  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (js::gc::GCRuntime::markConservativeStackRoots(JSTracer*, bool)+1308)
03-21 07:32:37.636  1019  1019 D CrashAnrDetector:          937278e8  b8aef3c8  [heap]
03-21 07:32:37.636  1019  1019 D CrashAnrDetector:          937278ec  b8aeec30  [heap]
03-21 07:32:37.636  1019  1019 D CrashAnrDetector:          937278f0  9372d000  
03-21 07:32:37.636  1019  1019 D CrashAnrDetector:          937278f4  93727918  [stack:4067]
03-21 07:32:37.636  1019  1019 D CrashAnrDetector:          937278f8  93727910  [stack:4067]
03-21 07:32:37.636  1019  1019 D CrashAnrDetector:          937278fc  9372791c  [stack:4067]
03-21 07:32:37.636  1019  1019 D CrashAnrDetector:          93727900  941b4dcc  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so
03-21 07:32:37.636  1019  1019 D CrashAnrDetector:          93727904  93727920  [stack:4067]
03-21 07:32:37.636  1019  1019 D CrashAnrDetector:          93727908  00000004  
03-21 07:32:37.636  1019  1019 D CrashAnrDetector:          9372790c  00000000  
03-21 07:32:37.636  1019  1019 D CrashAnrDetector:          93727910  00000001  
03-21 07:32:37.636  1019  1019 D CrashAnrDetector:          93727914  b8aef3c8  [heap]
03-21 07:32:37.636  1019  1019 D CrashAnrDetector:          93727918  908b3a60  [anon:js-gc-heap]
03-21 07:32:37.636  1019  1019 D CrashAnrDetector:          9372791c  b8aeec58  [heap]
03-21 07:32:37.636  1019  1019 D CrashAnrDetector:          93727920  93727934  [stack:4067]
03-21 07:32:37.636  1019  1019 D CrashAnrDetector:     #00  93727924  93727934  [stack:4067]
03-21 07:32:37.636  1019  1019 D CrashAnrDetector:          93727928  9372c838  [stack:4067]
03-21 07:32:37.636  1019  1019 D CrashAnrDetector:          9372792c  b8cc6890  [heap]
03-21 07:32:37.636  1019  1019 D CrashAnrDetector:          93727930  9372794c  [stack:4067]
03-21 07:32:37.636  1019  1019 D CrashAnrDetector:          93727934  93c05770  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (js::gc::MarkValueRoot(JSTracer*, JS::Value*, char const*)+80)
03-21 07:32:37.636  1019  1019 D CrashAnrDetector:     #01  93727938  b8b7cde4  [heap]
03-21 07:32:37.636  1019  1019 D CrashAnrDetector:          9372793c  00000000  
03-21 07:32:37.636  1019  1019 D CrashAnrDetector:          93727940  b8aeec54  [heap]
03-21 07:32:37.636  1019  1019 D CrashAnrDetector:          93727944  941363d0  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so
03-21 07:32:37.636  1019  1019 D CrashAnrDetector:          93727948  937279a4  [stack:4067]
03-21 07:32:37.636  1019  1019 D CrashAnrDetector:          9372794c  93c0a4d0  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (js::gc::GCRuntime::markRuntime(JSTracer*, js::gc::GCRuntime::TraceOrMarkRuntime, js::gc::GCRuntime::TraceRootsOrUsedSaved)+1452)
03-21 07:32:37.636  1019  1019 D CrashAnrDetector:          93727950  00000000  
03-21 07:32:37.636  1019  1019 D CrashAnrDetector:          93727954  9372796c  [stack:4067]
03-21 07:32:37.636  1019  1019 D CrashAnrDetector:     
03-21 07:32:37.636  1019  1019 D CrashAnrDetector: processName:com.test.thalitest
03-21 07:32:37.636  1019  1019 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 com.android.server.analytics.data.collection.application.CrashAnrDetector.broadcastEvent:296 com.android.server.analytics.data.collection.application.CrashAnrDetector.processDropBoxEntry:254 com.android.server.analytics.data.collection.application.CrashAnrDetector.access$100:60 com.android.server.analytics.data.collection.application.CrashAnrDetector$1.onReceive:102 
03-21 07:32:37.636  1019  1019 D CrashAnrDetector: broadcastEvent : com.test.thalitest SYSTEM_TOMBSTONE
03-21 07:32:37.646  3170  3193 I bluedroid: config_hci_snoop_log
03-21 07:32:37.646  1019  1048 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
,03-21 07:32:37.656  1019  3208 I BootReceiver: Copying /data/tombstones/tombstone_08 to DropBox (SYSTEM_TOMBSTONE)
03-21 07:32:37.656  1019  3265 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
03-21 07:32:37.666  1019  1048 D BluetoothManagerService: Ble is always on enable gatt
03-21 07:32:37.666  1019  1531 I AccessibilityManagerService: setmDNIeNegative (false)
03-21 07:32:37.676  1019  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_2392/cgroup.procs: No such file or directory
03-21 07:32:37.676  1019  1019 D CrashAnrDetector: Build: samsung/a3ultexx/a3ulte:5.0.2/LRX22G/A300FUXXU1BOEC:user/release-keys
03-21 07:32:37.676  1019  1019 D CrashAnrDetector: Hardware: MSM8916
03-21 07:32:37.676  1019  1019 D CrashAnrDetector: Revision: 1
03-21 07:32:37.676  1019  1019 D CrashAnrDetector: Bootloader: A300FUXXU1BOEC
03-21 07:32:37.676  1019  1019 D CrashAnrDetector: Radio: unknown
03-21 07:32:37.676  1019  1019 D CrashAnrDetector: Kernel: Linux version 3.10.49-4866174 (dpi@SWDD6204) (gcc version 4.8 (GCC) ) #1 SMP PREEMPT Fri May 29 20:06:40 KST 2015
03-21 07:32:37.676  1019  1019 D CrashAnrDetector: 
03-21 07:32:37.676  1019  1019 D CrashAnrDetector: *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
03-21 07:32:37.676  1019  1019 D CrashAnrDetector: Build fingerprint: 'samsung/a3ultexx/a3ulte:5.0.2/LRX22G/A300FUXXU1BOEC:user/release-keys'
03-21 07:32:37.676  1019  1019 D CrashAnrDetector: Revision: '1'
03-21 07:32:37.676  1019  1019 D CrashAnrDetector: ABI: 'arm'
03-21 07:32:37.676  1019  1019 D CrashAnrDetector: pid: 4389, tid: 4508, name: Thread-702  >>> com.test.thalitest <<<
03-21 07:32:37.676  1019  1019 D CrashAnrDetector: signal 11 (SIGSEGV), code 1 (SEGV_MAPERR), fault addr 0x0
03-21 07:32:37.676  1019  1019 D CrashAnrDetector:     r0 00000000  r1 9ede682c  r2 00000002  r3 00000000
03-21 07:32:37.676  1019  1019 D CrashAnrDetector:     r4 b7f0c840  r5 00000000  r6 b7f0c0d0  r7 b986b2f8
03-21 07:32:37.676  1019  1019 D CrashAnrDetector:     r8 b7de4664  r9 b7f0c840  sl b7f0c0a8  fp 9ede6824
03-21 07:32:37.676  1019  1019 D CrashAnrDetector:     ip ffffffff  sp 9ede6814  lr 9f2cfb30  pc 9f2cfa34  cpsr 600f0010
03-21 07:32:37.676  1019  1019 D CrashAnrDetector:     d0  0000000000000000  d1  0000000000000000
03-21 07:32:37.676  1019  1019 D CrashAnrDetector:     d2  0000000000000000  d3  0000000000000000
03-21 07:32:37.676  1019  1019 D CrashAnrDetector:     d4  0000000000000000  d5  0000000000000000
03-21 07:32:37.676  1019  1019 D CrashAnrDetector:     d6  0000000000000000  d7  0000000000000000
03-21 07:32:37.676  1019  1019 D CrashAnrDetector:     d8  0000000000000000  d9  0000000000000000
03-21 07:32:37.676  1019  1019 D CrashAnrDetector:     d10 0000000000000000  d11 0000000000000000
03-21 07:32:37.676  1019  1019 D CrashAnrDetector:     d12 0000000000000000  d13 0000000000000000
03-21 07:32:37.676  1019  1019 D CrashAnrDetector:     d14 0000000000000000  d15 0000000000000000
03-21 07:32:37.676  1019  1019 D CrashAnrDetector:     d16 0000000000000000  d17 000027b700000000
03-21 07:32:37.676  1019  1019 D CrashAnrDetector:     d18 0001000100010001  d19 0001000100010001
03-21 07:32:37.676  1019  1019 D CrashAnrDetector:     d20 0000000100010001  d21 0000000000000000
03-21 07:32:37.676  1019  1019 D CrashAnrDetector:     d22 0000000000000000  d23 0000000000000000
03-21 07:32:37.676  1019  1019 D CrashAnrDetector:     d24 0000000000000000  d25 0000000000000000
03-21 07:32:37.676  1019  1019 D CrashAnrDetector:     d26 0002000100010001  d27 0002000200020002
03-21 07:32:37.676  1019  1019 D CrashAnrDetector:     d28 0080008000800080  d29 0080008000800080
03-21 07:32:37.676  1019  1019 D CrashAnrDetector:     d30 0800080008000800  d31 0800080008000800
03-21 07:32:37.676  1019  1019 D CrashAnrDetector:     scr 20000013
03-21 07:32:37.676  1019  1019 D CrashAnrDetector: 
03-21 07:32:37.676  1019  1019 D CrashAnrDetector: backtrace:
03-21 07:32:37.676  1019  1019 D CrashAnrDetector:     #00 pc 003d1a34  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (bool ThingIsPermanentAtom<JS::Symbol>(JS::Symbol*)+4)
03-21 07:32:37.676  1019  1019 D CrashAnrDetector:     #01 pc 003d1b2c  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so
03-21 07:32:37.676  1019  1019 D CrashAnrDetector:     #02 pc e5943000  <unknown>
03-21 07:32:37.676  1019  1019 D CrashAnrDetector: 
03-21 07:32:37.676  1019  1019 D CrashAnrDetector: stack:
03-21 07:32:37.676  1019  1019 D CrashAnrDetector:          9ede6794  00000000  
03-21 07:32:37.676  1019  1019 D CrashAnrDetector:          9ede6798  90dfc0a0  [anon:js-gc-heap]
03-21 07:32:37.676  1019  1019 D CrashAnrDetector:          9ede679c  b7f0c840  [heap]
03-21 07:32:37.676  1019  1019 D CrashAnrDetector:          9ede67a0  00000001  
03-21 07:32:37.676  1019  1019 D CrashAnrDetector:          9ede67a4  90d6d0d0  [anon:js-gc-heap]
03-21 07:32:37.676  1019  1019 D CrashAnrDetector:          9ede67a8  9ede67c4  [stack:4508]
03-21 07:32:37.676  1019  1019 D CrashAnrDetector:          9ede67ac  9f2cf12c  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so
03-21 07:32:37.676  1019  1019 D CrashAnrDetector:          9ede67b0  00000001  
03-21 07:32:37.676  1019  1019 D CrashAnrDetector:          9ede67b4  00000000  
03-21 07:32:37.676  1019  1019 D CrashAnrDetector:          9ede67b8  b7f0d370  [heap]
03-21 07:32:37.676  1019  1019 D CrashAnrDetector:          9ede67bc  00000000  
03-21 07:32:37.676  1019  1019 D CrashAnrDetector:          9ede67c0  00000000  
03-21 07:32:37.676  1019  1019 D CrashAnrDetector:          9ede67c4  b7f0c840  [heap]
03-21 07:32:37.676  1019  1019 D CrashAnrDetector:          9ede67c8  b7f0d370  [heap]
03-21 07:32:37.676  1019  1019 D CrashAnrDetector:          9ede67cc  9f95bb60  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so
03-21 07:32:37.676  1019  1019 D CrashAnrDetector:          9ede67d0  9ede683c  [stack:4508]
03-21 07:32:37.676  1019  1019 D CrashAnrDetector:          9ede67d4  9f2d6514  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (js::gc::GCRuntime::markConservativeStackRoots(JSTracer*, bool)+1308)
03-21 07:32:37.676  1019  1019 D CrashAnrDetector:          9ede67d8  b7f0c840  [heap]
03-21 07:32:37.676  1019  1019 D CrashAnrDetector:          9ede67dc  b7f0c0a8  [heap]
03-21 07:32:37.676  1019  1019 D CrashAnrDetector:          9ede67e0  9edfa000  
03-21 07:32:37.676  1019  1019 D CrashAnrDetector:          9ede67e4  9ede6808  [stack:4508]
03-21 07:32:37.676  1019  1019 D CrashAnrDetector:          9ede67e8  9ede6800  [stack:4508]
03-21 07:32:37.676  1019  1019 D CrashAnrDetector:          9ede67ec  9ede680c  [stack:4508]
03-21 07:32:37.676  1019  1019 D CrashAnrDetector:          9ede67f0  9f8826d4  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so
03-21 07:32:37.676  1019  1019 D CrashAnrDetector:          9ede67f4  9ede6810  [stack:4508]
03-21 07:32:37.676  1019  1019 D CrashAnrDetector:          9ede67f8  00000004  
03-21 07:32:37.676  1019  1019 D CrashAnrDetector:          9ede67fc  00000000  
03-21 07:32:37.676  1019  1019 D CrashAnrDetector:          9ede6800  00000001  
03-21 07:32:37.676  1019  1019 D CrashAnrDetector:          9ede6804  b7f0c840  [heap]
03-21 07:32:37.676  1019  1019 D CrashAnrDetector:          9ede6808  91951af0  [anon:js-gc-heap]
03-21 07:32:37.676  1019  1019 D CrashAnrDetector:          9ede680c  b7f0c0d0  [heap]
03-21 07:32:37.676  1019  1019 D CrashAnrDetector:          9ede6810  9ede6824  [stack:4508]
03-21 07:32:37.676  1019  1019 D CrashAnrDetector:     #00  9ede6814  9ede6824  [stack:4508]
03-21 07:32:37.676  1019  1019 D CrashAnrDetector:          9ede6818  9edf9838  [stack:4508]
03-21 07:32:37.676  1019  1019 D CrashAnrDetector:          9ede681c  b9866048  [heap]
03-21 07:32:37.676  1019  1019 D CrashAnrDetector:          9ede6820  9ede683c  [stack:4508]
03-21 07:32:37.676  1019  1019 D CrashAnrDetector:          9ede6824  9f2d306c  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (js::gc::MarkValueRoot(JSTracer*, JS::Value*, char const*)+80)
03-21 07:32:37.676  1019  1019 D CrashAnrDetector:     #01  9ede6828  b7de4664  [heap]
03-21 07:32:37.676  1019  1019 D CrashAnrDetector:          9ede682c  00000000  
03-21 07:32:37.676  1019  1019 D CrashAnrDetector:          9ede6830  b7f0c0cc  [heap]
03-21 07:32:37.676  1019  1019 D CrashAnrDetector:          9ede6834  9f803cd8  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so
03-21 07:32:37.676  1019  1019 D CrashAnrDetector:          9ede6838  9ede6894  [stack:4508]
03-21 07:32:37.676  1019  1019 D CrashAnrDetector:          9ede683c  9f2d7dcc  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (js::gc::GCRuntime::markRuntime(JSTracer*, js::gc::GCRuntime::TraceOrMarkRuntime, js::gc::GCRuntime::TraceRootsOrUsedSaved)+1452)
03-21 07:32:37.676  1019  1019 D CrashAnrDetector:          9ede6840  00000000  
03-21 07:32:37.676  1019  1019 D CrashAnrDetector:          9ede6844  9ede685c  [stack
03-21 07:32:37.686  1019  1019 D CrashAnrDetector: processName:com.test.thalitest
03-21 07:32:37.686  1019  1019 D CrashAnrDetector: broadcastEvent : com.test.thalitest SYSTEM_TOMBSTONE
03-21 07:32:37.686  1019  1019 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 com.android.server.analytics.data.collection.application.CrashAnrDetector.broadcastEvent:296 com.android.server.analytics.data.collection.application.CrashAnrDetector.processDropBoxEntry:254 com.android.server.analytics.data.collection.application.CrashAnrDetector.access$100:60 com.android.server.analytics.data.collection.application.CrashAnrDetector$1.onReceive:102 
03-21 07:32:37.686  1859  1859 I SamsungIME: getCurrentCandidateView
,03-21 07:32:37.686  1019  1048 I BluetoothManagerService: enableGattForLeMode, doBind called
,03-21 07:32:37.696  1019  1048 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
03-21 07:32:37.696  1019  1048 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,03-21 07:32:37.696  3170  3170 I BtGatt.JNI: classInitNative(L900): classInitNative: Success!
,03-21 07:32:37.706  1019  3208 I BootReceiver: Copying /data/tombstones/tombstone_09 to DropBox (SYSTEM_TOMBSTONE)
,03-21 07:32:37.706  1019  1048 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,03-21 07:32:37.706  1019  3265 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
,03-21 07:32:37.716  3170  3288 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,03-21 07:32:37.716  1019  1019 D CrashAnrDetector: Build: samsung/a3ultexx/a3ulte:5.0.2/LRX22G/A300FUXXU1BOEC:user/release-keys
03-21 07:32:37.716  1019  1019 D CrashAnrDetector: Hardware: MSM8916
03-21 07:32:37.716  1019  1019 D CrashAnrDetector: Revision: 1
03-21 07:32:37.716  1019  1019 D CrashAnrDetector: Bootloader: A300FUXXU1BOEC
03-21 07:32:37.716  1019  1019 D CrashAnrDetector: Radio: unknown
03-21 07:32:37.716  1019  1019 D CrashAnrDetector: Kernel: Linux version 3.10.49-4866174 (dpi@SWDD6204) (gcc version 4.8 (GCC) ) #1 SMP PREEMPT Fri May 29 20:06:40 KST 2015
03-21 07:32:37.716  1019  1019 D CrashAnrDetector: 
03-21 07:32:37.716  1019  1019 D CrashAnrDetector: *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
03-21 07:32:37.716  1019  1019 D CrashAnrDetector: Build fingerprint: 'samsung/a3ultexx/a3ulte:5.0.2/LRX22G/A300FUXXU1BOEC:user/release-keys'
03-21 07:32:37.716  1019  1019 D CrashAnrDetector: Revision: '1'
03-21 07:32:37.716  1019  1019 D CrashAnrDetector: ABI: 'arm'
03-21 07:32:37.716  1019  1019 D CrashAnrDetector: pid: 4273, tid: 4624, name: Thread-667  >>> com.test.thalitest <<<
03-21 07:32:37.716  1019  1019 D CrashAnrDetector: signal 11 (SIGSEGV), code 1 (SEGV_MAPERR), fault addr 0x0
03-21 07:32:37.716  1019  1019 D CrashAnrDetector:     r0 00000000  r1 920d54e4  r2 00000002  r3 00000000
03-21 07:32:37.716  1019  1019 D CrashAnrDetector:     r4 b84d6800  r5 00000000  r6 b84d6090  r7 ba6fdeb8
03-21 07:32:37.716  1019  1019 D CrashAnrDetector:     r8 b8196a74  r9 b84d6800  sl b84d6068  fp 920d54dc
03-21 07:32:37.716  1019  1019 D CrashAnrDetector:     ip ffffffff  sp 920d54cc  lr 925b1b30  pc 925b1a34  cpsr 60000010
03-21 07:32:37.716  1019  1019 D CrashAnrDetector:     d0  0000000000000000  d1  0000000000000000
03-21 07:32:37.716  1019  1019 D CrashAnrDetector:     d2  0000000000000000  d3  0000000000000000
03-21 07:32:37.716  1019  1019 D CrashAnrDetector:     d4  0000000000000000  d5  0000000000000000
03-21 07:32:37.716  1019  1019 D CrashAnrDetector:     d6  0000000000000000  d7  0000000000000000
03-21 07:32:37.716  1019  1019 D CrashAnrDetector:     d8  0000000000000000  d9  0000000000000000
03-21 07:32:37.716  1019  1019 D CrashAnrDetector:     d10 0000000000000000  d11 0000000000000000
03-21 07:32:37.716  1019  1019 D CrashAnrDetector:     d12 0000000000000000  d13 0000000000000000
03-21 07:32:37.716  1019  1019 D CrashAnrDetector:     d14 0000000000000000  d15 0000000000000000
03-21 07:32:37.716  1019  1019 D CrashAnrDetector:     d16 000027b7000027b7  d17 000027b700000000
03-21 07:32:37.716  1019  1019 D CrashAnrDetector:     d18 0001000100010001  d19 0001000100010001
03-21 07:32:37.716  1019  1019 D CrashAnrDetector:     d20 0000000100010001  d21 0000000000000000
03-21 07:32:37.716  1019  1019 D CrashAnrDetector:     d22 0000000000000000  d23 0000000000000000
03-21 07:32:37.716  1019  1019 D CrashAnrDetector:     d24 0000000000000000  d25 0000000000000000
03-21 07:32:37.716  1019  1019 D CrashAnrDetector:     d26 0002000100010001  d27 0002000200020002
03-21 07:32:37.716  1019  1019 D CrashAnrDetector:     d28 0080008000800080  d29 0080008000800080
03-21 07:32:37.716  1019  1019 D CrashAnrDetector:     d30 0800080008000800  d31 0800080008000800
03-21 07:32:37.716  1019  1019 D CrashAnrDetector:     scr 20000013
03-21 07:32:37.716  1019  1019 D CrashAnrDetector: 
03-21 07:32:37.716  1019  1019 D CrashAnrDetector: backtrace:
03-21 07:32:37.716  1019  1019 D CrashAnrDetector:     #00 pc 003d1a34  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (bool ThingIsPermanentAtom<JS::Symbol>(JS::Symbol*)+4)
03-21 07:32:37.716  1019  1019 D CrashAnrDetector:     #01 pc 003d1b2c  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so
03-21 07:32:37.716  1019  1019 D CrashAnrDetector:     #02 pc e5943000  <unknown>
03-21 07:32:37.716  1019  1019 D CrashAnrDetector: 
03-21 07:32:37.716  1019  1019 D CrashAnrDetector: stack:
03-21 07:32:37.716  1019  1019 D CrashAnrDetector:          920d544c  00000000  
03-21 07:32:37.716  1019  1019 D CrashAnrDetector,:          920d5450  8fcfc0a0  [anon:js-gc-heap]
03-21 07:32:37.716  1019  1019 D CrashAnrDetector:          920d5454  b84d6800  [heap]
03-21 07:32:37.716  1019  1019 D CrashAnrDetector:          920d5458  00000001  
03-21 07:32:37.716  1019  1019 D CrashAnrDetector:          920d545c  8fced280  [anon:js-gc-heap]
03-21 07:32:37.716  1019  1019 D CrashAnrDetector:          920d5460  920d547c  [stack:4624]
03-21 07:32:37.716  1019  1019 D CrashAnrDetector:          920d5464  925b112c  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so
03-21 07:32:37.716  1019  1019 D CrashAnrDetector:          920d5468  00000001  
03-21 07:32:37.716  1019  1019 D CrashAnrDetector:          920d546c  00000000  
03-21 07:32:37.716  1019  1019 D CrashAnrDetector:          920d5470  b84d7330  [heap]
03-21 07:32:37.716  1019  1019 D CrashAnrDetector:          920d5474  00000000  
03-21 07:32:37.716  1019  1019 D CrashAnrDetector:          920d5478  00000000  
03-21 07:32:37.716  1019  1019 D CrashAnrDetector:          920d547c  b84d6800  [heap]
03-21 07:32:37.716  1019  1019 D CrashAnrDetector:          920d5480  b84d7330  [heap]
03-21 07:32:37.716  1019  1019 D CrashAnrDetector:          920d5484  92c3db60  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so
03-21 07:32:37.716  1019  1019 D CrashAnrDetector:          920d5488  920d54f4  [stack:4624]
03-21 07:32:37.716  1019  1019 D CrashAnrDetector:          920d548c  925b8514  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (js::gc::GCRuntime::markConservativeStackRoots(JSTracer*, bool)+1308)
03-21 07:32:37.716  1019  1019 D CrashAnrDetector:          920d5490  b84d6800  [heap]
03-21 07:32:37.716  1019  1019 D CrashAnrDetector:          920d5494  b84d6068  [heap]
03-21 07:32:37.716  1019  1019 D CrashAnrDetector:          920d5498  920dc000  
03-21 07:32:37.716  1019  1019 D CrashAnrDetector:          920d549c  920d54c0  [stack:4624]
03-21 07:32:37.716  1019  1019 D CrashAnrDetector:          920d54a0  920d54b8  [stack:4624]
03-21 07:32:37.716  1019  1019 D CrashAnrDetector:          920d54a4  920d54c4  [stack:4624]
03-21 07:32:37.716  1019  1019 D CrashAnrDetector:          920d54a8  92b646d4  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so
03-21 07:32:37.716  1019  1019 D CrashAnrDetector:          920d54ac  920d54c8  [stack:4624]
03-21 07:32:37.716  1019  1019 D CrashAnrDetector:          920d54b0  00000004  
03-21 07:32:37.716  1019  1019 D CrashAnrDetector:          920d54b4  00000000  
03-21 07:32:37.716  1019  1019 D CrashAnrDetector:          920d54b8  00000001  
03-21 07:32:37.716  1019  1019 D CrashAnrDetector:          920d54bc  b84d6800  [heap]
03-21 07:32:37.716  1019  1019 D CrashAnrDetector:          920d54c0  901e6eb0  [anon:js-gc-heap]
03-21 07:32:37.716  1019  1019 D CrashAnrDetector:          920d54c4  b84d6090  [heap]
03-21 07:32:37.716  1019  1019 D CrashAnrDetector:          920d54c8  920d54dc  [stack:4624]
03-21 07:32:37.716  1019  1019 D CrashAnrDetector:     #00  920d54cc  920d54dc  [stack:4624]
03-21 07:32:37.716  1019  1019 D CrashAnrDetector:          920d54d0  920db838  [stack:4624]
03-21 07:32:37.716  1019  1019 D CrashAnrDetector:          920d54d4  ba6fb020  [heap]
03-21 07:32:37.716  1019  1019 D CrashAnrDetector:          920d54d8  920d54f4  [stack:4624]
03-21 07:32:37.716  1019  1019 D CrashAnrDetector:          920d54dc  925b506c  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (js::gc::MarkValueRoot(JSTracer*, JS::Value*, char const*)+80)
03-21 07:32:37.716  1019  1019 D CrashAnrDetector:     #01  920d54e0  b8196a74  [heap]
03-21 07:32:37.716  1019  1019 D CrashAnrDetector:          920d54e4  00000000  
03-21 07:32:37.716  1019  1019 D CrashAnrDetector:          920d54e8  b84d608c  [heap]
03-21 07:32:37.716  1019  1019 D CrashAnrDetector:          920d54ec  92ae5cd8  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so
03-21 07:32:37.716  1019  1019 D CrashAnrDetector:          920d54f0  920d554c  [stack:4624]
03-21 07:32:37.716  1019  1019 D CrashAnrDetector:          920d54f4  925b9dcc  /data/app/com.t,est.thalitest-1/lib/arm/libjxcore.so (js::gc::GCRuntime::markRuntime(JSTracer*, js::gc::GCRuntime::TraceOrMarkRuntime, js::gc::GCRuntime::TraceRootsOrUsedSaved)+1452)
03-21 07:32:37.716  1019  1019 D CrashAnrDetector:          920d54f8  00000000  
03-21 07:32:37.716  1019  1019 D CrashAnrDetector:          920d54fc  920d5514  [stack
03-21 07:32:37.716  1019  1019 D CrashAnrDetector: processName:com.test.thalitest
03-21 07:32:37.716  1019  1019 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 com.android.server.analytics.data.collection.application.CrashAnrDetector.broadcastEvent:296 com.android.server.analytics.data.collection.application.CrashAnrDetector.processDropBoxEntry:254 com.android.server.analytics.data.collection.application.CrashAnrDetector.access$100:60 com.android.server.analytics.data.collection.application.CrashAnrDetector$1.onReceive:102 
03-21 07:32:37.716  1019  1019 D CrashAnrDetector: broadcastEvent : com.test.thalitest SYSTEM_TOMBSTONE
03-21 07:32:37.716  3170  3288 D BluetoothAdapterProperties: Setting state to 11
03-21 07:32:37.716  3170  3288 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
03-21 07:32:37.716  3170  3288 D BluetoothAdapterService: Bluetooth PBAP supproted is true
03-21 07:32:37.716  3170  3288 D BluetoothAdapterService: updateAdapterState state is 11
03-21 07:32:37.736  3170  3288 D BluetoothAdapterService: Autoconnection is available 
03-21 07:32:37.736  3170  3288 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
03-21 07:32:37.736  3170  3288 D BluetoothSecureManager: getInstant: null
03-21 07:32:37.736  3170  3288 D BluetoothSecureManager: calling getMethod for getService
03-21 07:32:37.736  3170  3288 D BluetoothSecureManager: calling getService
03-21 07:32:37.736  3170  3288 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@1cf4cd91
03-21 07:32:37.746  1019  1048 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
03-21 07:32:37.746  1019  1138 D BluetoothSecureManagerService: isSecureModeEnabled
03-21 07:32:37.746  1019  1138 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
03-21 07:32:37.746  3170  3288 D BtConfig.SecureMode: isSecureModeOn:false
03-21 07:32:37.746  3170  3288 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
03-21 07:32:37.746  1019  1019 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
03-21 07:32:37.746  1019  1019 I InputMethodManagerService: [BT Setting State] State =11
03-21 07:32:37.756  3170  3288 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
03-21 07:32:37.756  3170  3288 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
03-21 07:32:37.756  3170  3288 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
03-21 07:32:37.756  3170  3288 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
03-21 07:32:37.756  3170  3288 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
03-21 07:32:37.756  3170  3288 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,03-21 07:32:37.756  1181  1181 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,03-21 07:32:37.766  3170  3288 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
03-21 07:32:37.766  3170  3288 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,03-21 07:32:37.766  3170  3288 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
,03-21 07:32:37.766  3170  3288 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,03-21 07:32:37.766  1019  1030 I art     : Background sticky concurrent mark sweep GC freed 35935(3MB) AllocSpace objects, 127(10MB) LOS objects, 32% free, 23MB/35MB, paused 5.968ms total 104.243ms
,03-21 07:32:37.766  3170  3288 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
,03-21 07:32:37.766  3170  3288 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,03-21 07:32:37.776  3170  3288 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
03-21 07:32:37.776  3170  3288 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,03-21 07:32:37.776  3170  3288 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
,03-21 07:32:37.776  3170  3288 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,03-21 07:32:37.776  1181  1181 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
03-21 07:32:37.776  1181  1181 D BluetoothTile:  getBluetoothState : 11
,03-21 07:32:37.776  1181  1627 D BluetoothTile:  handleUpdatestate:false name:null
03-21 07:32:37.776  1181  1627 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,03-21 07:32:37.786  3170  3288 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
03-21 07:32:37.786  3170  3288 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,03-21 07:32:37.786  3170  3288 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
03-21 07:32:37.786  3170  3288 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,03-21 07:32:37.786  3170  3288 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
03-21 07:32:37.786  3170  3288 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,03-21 07:32:37.786  3170  3288 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
,03-21 07:32:37.786  3170  3288 D BluetoothBondStateMachine: make
,03-21 07:32:37.786  1019  1805 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,03-21 07:32:37.796  3170  3288 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
03-21 07:32:37.796  3170  3288 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
03-21 07:32:37.796  3170  3288 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,03-21 07:32:37.796  3170  3299 I BluetoothBondStateMachine: StableState(): Entering Off State
,03-21 07:32:37.796  1019  1138 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,03-21 07:32:37.806  1337  1337 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,03-21 07:32:37.806  1181  1181 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,03-21 07:32:37.806  1019  1502 W ActivityManager: userId = 0, bbcId = -10000
,03-21 07:32:37.816  1019  1502 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-21 07:32:37.816  1019  1502 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,03-21 07:32:37.816   259   452 I SurfaceFlinger: id=11 Removed uhalitest (7/8)
,03-21 07:32:37.816   259   715 I SurfaceFlinger: id=11 Removed uhalitest (-2/8)
03-21 07:32:37.816  1019  1019 D CrashAnrDetector: Build: samsung/a3ultexx/a3ulte:5.0.2/LRX22G/A300FUXXU1BOEC:user/release-keys
03-21 07:32:37.816  1019  1019 D CrashAnrDetector: Hardware: MSM8916
03-21 07:32:37.816  1019  1019 D CrashAnrDetector: Revision: 1
03-21 07:32:37.816  1019  1019 D CrashAnrDetector: Bootloader: A300FUXXU1BOEC
03-21 07:32:37.816  1019  1019 D CrashAnrDetector: Radio: unknown
03-21 07:32:37.816  1019  1019 D CrashAnrDetector: Kernel: Linux version 3.10.49-4866174 (dpi@SWDD6204) (gcc version 4.8 (GCC) ) #1 SMP PREEMPT Fri May 29 20:06:40 KST 2015
03-21 07:32:37.816  1019  1019 D CrashAnrDetector: 
03-21 07:32:37.816  1019  1019 D CrashAnrDetector: *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
03-21 07:32:37.816  1019  1019 D CrashAnrDetector: Build fingerprint: 'samsung/a3ultexx/a3ulte:5.0.2/LRX22G/A300FUXXU1BOEC:user/release-keys'
03-21 07:32:37.816  1019  1019 D CrashAnrDetector: Revision: '1'
03-21 07:32:37.816  1019  1019 D CrashAnrDetector: ABI: 'arm'
03-21 07:32:37.816  1019  1019 D CrashAnrDetector: pid: 4085, tid: 4524, name: Thread-617  >>> com.test.thalitest <<<
03-21 07:32:37.816  1019  1019 D CrashAnrDetector: signal 11 (SIGSEGV), code 1 (SEGV_MAPERR), fault addr 0x0
03-21 07:32:37.816  1019  1019 D CrashAnrDetector:     r0 00000000  r1 9358a7dc  r2 00000002  r3 00000000
03-21 07:32:37.816  1019  1019 D CrashAnrDetector:     r4 b8b4ae28  r5 00000000  r6 b8b4a6b8  r7 ba8998a0
03-21 07:32:37.816  1019  1019 D CrashAnrDetector:     r8 b872115c  r9 b8b4ae28  sl b8b4a690  fp 9358a7d4
03-21 07:32:37.816  1019  1019 D CrashAnrDetector:     ip ffffffff  sp 9358a7c4  lr 9e9e1b30  pc 9e9e1a34  cpsr 60000010
03-21 07:32:37.816  1019  1019 D CrashAnrDetector:     d0  0000000000000000  d1  0000000000000000
03-21 07:32:37.816  1019  1019 D CrashAnrDetector:     d2  0000000000000000  d3  0000000000000000
03-21 07:32:37.816  1019  1019 D CrashAnrDetector:     d4  0000000000000000  d5  0000000000000000
03-21 07:32:37.816  1019  1019 D CrashAnrDetector:     d6  0000000000000000  d7  0000000000000000
03-21 07:32:37.816  1019  1019 D CrashAnrDetector:     d8  0000000000000000  d9  0000000000000000
03-21 07:32:37.816  1019  1019 D CrashAnrDetector:     d10 0000000000000000  d11 0000000000000000
03-21 07:32:37.816  1019  1019 D CrashAnrDetector:     d12 0000000000000000  d13 0000000000000000
03-21 07:32:37.816  1019  1019 D CrashAnrDetector:     d14 0000000000000000  d15 0000000000000000
03-21 07:32:37.816  1019  1019 D CrashAnrDetector:     d16 000027b7000027b7  d17 000027b700000000
03-21 07:32:37.816  1019  1019 D CrashAnrDetector:     d18 0001000100010001  d19 0001000100010001
03-21 07:32:37.816  1019  1019 D CrashAnrDetector:     d20 0000000000010001  d21 0000000000000000
03-21 07:32:37.816  1019  1019 D CrashAnrDetector:     d22 0000000000000000  d23 0000000000000000
03-21 07:32:37.816  1019  1019 D CrashAnrDetector:     d24 0000000000000000  d25 0000000000000000
03-21 07:32:37.816  1019  1019 D CrashAnrDetector:     d26 0002000200010001  d27 0002000200020002
03-21 07:32:37.816  1019  1019 D CrashAnrDetector:     d28 0080008000800080  d29 0080008000800080
03-21 07:32:37.816  1019  1019 D CrashAnrDetector:     d30 0800080008000800  d31 0800080008000800
03-21 07:32:37.816  1019  1019 D CrashAnrDetector:     scr 20000013
03-21 07:32:37.816  1019  1019 D CrashAnrDetector: 
03-21 07:32:37.816  1019  1019 D CrashAnrDetector: backtrace:
03-21 07:32:37.816  1019  1019 D CrashAnrDetector:     #00 pc 003d1a34  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (bool ThingIsPermanentAtom<JS::Symbol>(JS::Symbol*)+4)
03-21 07:32:37.816  1019  1019 D CrashAnrDetector:     #01 pc 003d1b2c  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so
03-21 07:32:37.816  1019  1019 D CrashAnrDetector:     #02 pc e5943000  <unknown>
03-21 07:32:37.816  1019  1019 D CrashAnrDetector: 
03-21 07:32:37.816  1019  1019 D CrashAnrDetector: stack:
03-21 07:32:37.816  1019  1019 D CrashAnrDetector:,          9358a744  00000000  
03-21 07:32:37.816  1019  1019 D CrashAnrDetector:          9358a748  8fffc0a0  [anon:js-gc-heap]
03-21 07:32:37.816  1019  1019 D CrashAnrDetector:          9358a74c  b8b4ae28  [heap]
03-21 07:32:37.816  1019  1019 D CrashAnrDetector:          9358a750  b8b4ae28  [heap]
03-21 07:32:37.816  1019  1019 D CrashAnrDetector:          9358a754  00000001  
03-21 07:32:37.816  1019  1019 D CrashAnrDetector:          9358a758  9358a774  [stack:4524]
03-21 07:32:37.816  1019  1019 D CrashAnrDetector:          9358a75c  9e9e1150  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so
03-21 07:32:37.816  1019  1019 D CrashAnrDetector:          9358a760  00000001  
03-21 07:32:37.816  1019  1019 D CrashAnrDetector:          9358a764  00000000  
03-21 07:32:37.816  1019  1019 D CrashAnrDetector:          9358a768  b8b4b958  [heap]
03-21 07:32:37.816  1019  1019 D CrashAnrDetector:          9358a76c  00000000  
03-21 07:32:37.816  1019  1019 D CrashAnrDetector:          9358a770  00000000  
03-21 07:32:37.816  1019  1019 D CrashAnrDetector:          9358a774  b8b4ae28  [heap]
03-21 07:32:37.816  1019  1019 D CrashAnrDetector:          9358a778  b8b4b958  [heap]
03-21 07:32:37.816  1019  1019 D CrashAnrDetector:          9358a77c  9f06db60  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so
03-21 07:32:37.816  1019  1019 D CrashAnrDetector:          9358a780  9358a7ec  [stack:4524]
03-21 07:32:37.816  1019  1019 D CrashAnrDetector:          9358a784  9e9e8514  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (js::gc::GCRuntime::markConservativeStackRoots(JSTracer*, bool)+1308)
03-21 07:32:37.816  1019  1019 D CrashAnrDetector:          9358a788  b8b4ae28  [heap]
03-21 07:32:37.816  1019  1019 D CrashAnrDetector:          9358a78c  b8b4a690  [heap]
03-21 07:32:37.816  1019  1019 D CrashAnrDetector:          9358a790  93590000  /dev/kgsl-3d0
03-21 07:32:37.816  1019  1019 D CrashAnrDetector:          9358a794  9358a7b8  [stack:4524]
03-21 07:32:37.816  1019  1019 D CrashAnrDetector:          9358a798  9358a7b0  [stack:4524]
03-21 07:32:37.816  1019  1019 D CrashAnrDetector:          9358a79c  9358a7bc  [stack:4524]
03-21 07:32:37.816  1019  1019 D CrashAnrDetector:          9358a7a0  9ef946d4  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so
03-21 07:32:37.816  1019  1019 D CrashAnrDetector:          9358a7a4  9358a7c0  [stack:4524]
03-21 07:32:37.816  1019  1019 D CrashAnrDetector:          9358a7a8  00000012  
03-21 07:32:37.816  1019  1019 D CrashAnrDetector:          9358a7ac  00000000  
03-21 07:32:37.816  1019  1019 D CrashAnrDetector:          9358a7b0  00000001  
03-21 07:32:37.816  1019  1019 D CrashAnrDetector:          9358a7b4  b8b4ae28  [heap]
03-21 07:32:37.816  1019  1019 D CrashAnrDetector:          9358a7b8  91e462b0  [anon:js-gc-heap]
03-21 07:32:37.816  1019  1019 D CrashAnrDetector:          9358a7bc  b8b4a6b8  [heap]
03-21 07:32:37.816  1019  1019 D CrashAnrDetector:          9358a7c0  9358a7d4  [stack:4524]
03-21 07:32:37.816  1019  1019 D CrashAnrDetector:     #00  9358a7c4  9358a7d4  [stack:4524]
03-21 07:32:37.816  1019  1019 D CrashAnrDetector:          9358a7c8  9358f838  [stack:4524]
03-21 07:32:37.816  1019  1019 D CrashAnrDetector:          9358a7cc  ba897cf8  [heap]
03-21 07:32:37.816  1019  1019 D CrashAnrDetector:          9358a7d0  9358a7ec  [stack:4524]
03-21 07:32:37.816  1019  1019 D CrashAnrDetector:          9358a7d4  9e9e506c  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (js::gc::MarkValueRoot(JSTracer*, JS::Value*, char const*)+80)
03-21 07:32:37.816  1019  1019 D CrashAnrDetector:     #01  9358a7d8  b872115c  [heap]
03-21 07:32:37.816  1019  1019 D CrashAnrDetector:          9358a7dc  00000000  
03-21 07:32:37.816  1019  1019 D CrashAnrDetector:          9358a7e0  b8b4a6b4  [heap]
03-21 07:32:37.816  1019  1019 D CrashAnrDetector:          9358a7e4  9ef15cd8  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so
03-21 07:32:37.816  1019  1019 D CrashAnrDetector:          9358a7e8  9358a844  [stack:4524]
03-21 07:32:37.816  1019  1019 D CrashAnrDetector:          9358a7ec  9e9e9dcc  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (js::gc::GCRuntime::markRuntime(JSTracer*, js::gc::GCRuntime::TraceOrMarkRuntime, js::gc::GCRuntime::TraceRootsOrUsedSaved)+1452)
03-21 07:32:37.816  1019  1019 D CrashAnrDetector:          9358a7f0  00000000  
03-21 07:32:37.816  1019  1019 D CrashAnrDetector:          9358a7f4  9358a80c  [sta
03-21 07:32:37.816  1019  1019 D CrashAnrDetector: processName:com.test.thalitest
03-21 07:32:37.816  1019  1019 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 com.android.server.analytics.data.collection.application.CrashAnrDetector.broadcastEvent:296 com.android.server.analytics.data.collection.application.CrashAnrDetector.processDropBoxEntry:254 com.android.server.analytics.data.collection.application.CrashAnrDetector.access$100:60 com.android.server.analytics.data.collection.application.CrashAnrDetector$1.onReceive:102 
03-21 07:32:37.816  1019  1019 D CrashAnrDetector: broadcastEvent : com.test.thalitest SYSTEM_TOMBSTONE
03-21 07:32:37.816  3170  3288 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
03-21 07:32:37.816  3170  3288 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
03-21 07:32:37.816  3170  3288 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
03-21 07:32:37.816  1019  1805 D SettingsProvider: name = block_emergency_message
03-21 07:32:37.816  3170  3170 D BtGatt.DebugUtils: handleDebugAction() action=null
03-21 07:32:37.826  3170  3170 D BtGatt.GattService: Received start request. Starting profile...
03-21 07:32:37.826  3170  3170 D BtGatt.GattService: start()
03-21 07:32:37.826  3170  3170 D BtGatt.GattService: start()
03-21 07:32:37.826  3170  3170 I bluedroid: get_profile_interface gatt
03-21 07:32:37.826  3170  3170 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@19a598a0
03-21 07:32:37.826  3170  3170 D BtGatt.AdvertiseManager: advertise manager created
03-21 07:32:37.826  1019  1283 W ActivityManager: userId = 0, bbcId = -10000
03-21 07:32:37.826  1019  1283 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-21 07:32:37.826  1019  1283 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
03-21 07:32:37.826  3170  3288 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
03-21 07:32:37.826  3170  3288 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
03-21 07:32:37.826  3170  3288 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
03-21 07:32:37.836  1019  1804 D SettingsProvider: name = safetycare_geolookout_registering
03-21 07:32:37.836  1019  1138 W ActivityManager: userId = 0, bbcId = -10000
03-21 07:32:37.836  1019  1138 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-21 07:32:37.836  1019  1138 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
03-21 07:32:37.846  3170  3288 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
03-21 07:32:37.846  3170  3288 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
03-21 07:32:37.846  3170  3170 D BtGatt.GattService: mStartError = false
03-21 07:32:37.846  3170  3170 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@19a598a0
03-21 07:32:37.846  3170  3288 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,03-21 07:32:37.846  1181  1181 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
03-21 07:32:37.856  1859  1859 D SamsungIME: Dismiss ExpandCandiate
03-21 07:32:37.856  3170  3170 D HeadsetService: Received start request. Starting profile...
03-21 07:32:37.856  3170  3170 D HeadsetService: start()
03-21 07:32:37.856  3170  3170 I BluetoothHeadsetServiceJni: classInitNative: succeeds
03-21 07:32:37.856  3170  3170 D HeadsetStateMachine: make
03-21 07:32:37.866  1019  1564 W ActivityManager: userId = 0, bbcId = -10000
03-21 07:32:37.866  1019  1564 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-21 07:32:37.866  1019  1564 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
03-21 07:32:37.866  3170  3288 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
03-21 07:32:37.866  3170  3288 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
03-21 07:32:37.866  3170  3288 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
03-21 07:32:37.866  3170  3170 E HeadsetStateMachine: # of Max HF connection is 2
03-21 07:32:37.866  1181  1181 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
03-21 07:32:37.866  1019  1502 W ActivityManager: userId = 0, bbcId = -10000
03-21 07:32:37.866  1019  1502 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-21 07:32:37.866  1019  1502 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
03-21 07:32:37.876  3170  3288 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
03-21 07:32:37.876  1019  1283 W ActivityManager: userId = 0, bbcId = -10000
03-21 07:32:37.876  3170  3288 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
03-21 07:32:37.876  1019  1283 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-21 07:32:37.876  1019  1283 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
03-21 07:32:37.876  3170  3288 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
03-21 07:32:37.876  1019  1138 W ActivityManager: userId = 0, bbcId = -10000
03-21 07:32:37.876  1019  1138 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-21 07:32:37.886  1019  1138 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
03-21 07:32:37.886  3170  3288 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
03-21 07:32:37.886  3170  3288 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
03-21 07:32:37.886  3170  3288 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
03-21 07:32:37.886  1019  1571 W ActivityManager: userId = 0, bbcId = -10000
03-21 07:32:37.886  1019  1571 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-21 07:32:37.886  1019  1571 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
03-21 07:32:37.886  3170  3170 I bluedroid: get_profile_interface handsfree
03-21 07:32:37.886  1019  1564 W ActivityManager: userId = 0, bbcId = -10000
03-21 07:32:37.886  1019  1564 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-21 07:32:37.886  1019  1564 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,03-21 07:32:37.886  3170  3288 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
03-21 07:32:37.886  3170  3288 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
03-21 07:32:37.886  3170  3288 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
03-21 07:32:37.896  1019  1561 W ActivityManager: userId = 0, bbcId = -10000
03-21 07:32:37.896  1019  1561 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-21 07:32:37.896  1019  1561 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
03-21 07:32:37.896  3170  3288 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
03-21 07:32:37.896  3170  3288 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
03-21 07:32:37.896  3170  3170 I DualScoManager: Instantiating Dual Sco Manager
03-21 07:32:37.896  3170  3170 I DualScoManager: Set HeadsetServiceHelper
03-21 07:32:37.896  3170  3288 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
03-21 07:32:37.896  3170  3170 D BluetoothAtMessage: createCMTIContentObservers
03-21 07:32:37.896  3170  3288 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
03-21 07:32:37.896  3170  3288 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,03-21 07:32:37.896  1019  1032 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
03-21 07:32:37.896  1019  1032 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-21 07:32:37.896  1019  1032 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-21 07:32:37.896  1019  1032 D SettingsProvider: selectionArgs: false
03-21 07:32:37.896  1019  1032 D SettingsProvider: selectionArgs: 1002
03-21 07:32:37.896  1019  1032 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-21 07:32:37.896  1019  1032 D SettingsProvider: ret = -1
03-21 07:32:37.896  3170  3288 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
03-21 07:32:37.896  3153  3153 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
03-21 07:32:37.906  3170  3288 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
03-21 07:32:37.906  3170  3288 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
03-21 07:32:37.906  3170  3288 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
03-21 07:32:37.906  3170  3288 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
03-21 07:32:37.906  3170  3288 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
03-21 07:32:37.906  3170  3288 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
03-21 07:32:37.906  3170  3288 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
03-21 07:32:37.906  1019  1032 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,03-21 07:32:37.906  1019  1531 I ActivityManager: Killing 2636:com.sec.pcw.device/1000 (adj 15): empty #31
,03-21 07:32:37.916  3170  3304 D HeadsetStateMachine: Enter Disconnected: -2
,03-21 07:32:37.916  3170  3170 D HeadsetService: mStartError = false
03-21 07:32:37.916  3170  3170 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@19a598a0
,03-21 07:32:37.916  3170  3304 D HeadsetStateMachine: Clear mHeadsetBrsf
03-21 07:32:37.916  3170  3304 D HeadsetStateMachine: map size, before remove : 0
03-21 07:32:37.916  3170  3304 D HeadsetStateMachine: map size, after remove: 0
,03-21 07:32:37.926  3170  3170 D A2dpService: Received start request. Starting profile...
03-21 07:32:37.926  3170  3170 D A2dpService: start()
,03-21 07:32:37.926  1181  1181 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-21 07:32:37.926  3170  3170 I BluetoothAvrcpServiceJni: classInitNative: succeeds
03-21 07:32:37.926  3170  3170 I bluedroid: get_profile_interface avrcp
,03-21 07:32:37.936  3170  3170 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,03-21 07:32:37.956  1859  1859 I SamsungIME: getDebugLevel  : 0x4f4c
,03-21 07:32:37.956  3170  3170 I Avrcp   :  Updating now playing list upon AVRCP Start
,03-21 07:32:37.956  3170  3305 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,03-21 07:32:37.966  3170  3170 I BluetoothA2dpServiceJni: classInitNative: succeeds
03-21 07:32:37.966  3170  3170 D A2dpStateMachine: make
,03-21 07:32:37.966  3170  3170 I bluedroid: get_profile_interface a2dp
,03-21 07:32:37.966  2169  3268 D ConnectivityManager: CallingUid : 10011, CallingPid : 2169
,03-21 07:32:37.976  3170  3308 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,03-21 07:32:37.976  3170  3170 E bt-btif : warning : media task started media_task_refcnt 1 
,03-21 07:32:37.976  3170  3170 D A2dpService: mStartError = false
03-21 07:32:37.976  3170  3170 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@19a598a0
,03-21 07:32:37.976  3170  3170 E BluetoothAdapterService(430282912): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
,03-21 07:32:37.976  3170  3307 D A2dpStateMachine: Enter Disconnected: -2
,03-21 07:32:37.976  3153  3295 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
03-21 07:32:37.976  3153  3295 I chromium: 
03-21 07:32:37.976  1019  1502 D ConnectivityService: listenForNetwork for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,03-21 07:32:37.976  1019  1132 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI_P2P () - 501]
,03-21 07:32:37.976  1019  1132 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 502]
03-21 07:32:37.976  1019  1132 D ConnectivityService: apparently satisfied.  currentScore=60
,03-21 07:32:37.976  2169  3309 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,03-21 07:32:37.986  3170  3305 D BluetoothMediaBrowser: no now playing list
03-21 07:32:37.986  3170  3305 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,03-21 07:32:37.996  3170  3170 I BluetoothHidServiceJni: classInitNative: succeeds
,03-21 07:32:38.016  3170  3170 D HidService: Received start request. Starting profile...
03-21 07:32:38.016  3170  3170 D HidService: start()
03-21 07:32:38.016  3170  3170 I bluedroid: get_profile_interface hidhost
03-21 07:32:38.016  3170  3170 D HidService: setHidService(): set to: null
03-21 07:32:38.016  3170  3170 D HidService: mStartError = false
03-21 07:32:38.016  3170  3170 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@19a598a0
,03-21 07:32:38.016  3170  3170 I BluetoothHealthServiceJni: classInitNative: succeeds
,03-21 07:32:38.016  3170  3170 D HealthService: Received start request. Starting profile...
03-21 07:32:38.016  3170  3170 D HealthService: start()
,03-21 07:32:38.016  3170  3170 I bluedroid: get_profile_interface health
03-21 07:32:38.016  3170  3170 D HealthService: mStartError = false
03-21 07:32:38.016  3170  3170 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@19a598a0
,03-21 07:32:38.016  3170  3170 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,03-21 07:32:38.026  1019  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_2636/cgroup.procs: No such file or directory
,03-21 07:32:38.026  3170  3170 D PanService: Received start request. Starting profile...
,03-21 07:32:38.026  3170  3170 D PanService: start()
03-21 07:32:38.026  3170  3170 D BluetoothPanServiceJni: initializeNative(L110): pan
03-21 07:32:38.026  3170  3170 I bluedroid: get_profile_interface pan
,03-21 07:32:38.026  3170  3170 D PanService: mStartError = false
,03-21 07:32:38.026  3170  3170 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@19a598a0
03-21 07:32:38.026  3170  3170 D HeadsetStateMachine: Try to query the phonestate on bind
,03-21 07:32:38.036  1459  1467 I Telecom : BluetoothPhoneService: queryPhoneState
,03-21 07:32:38.036  1459  1459 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
,03-21 07:32:38.036  1459  1459 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,03-21 07:32:38.036  1859  1859 I SamsungIME: getDebugLevel  : 0x4f4c
,03-21 07:32:38.036  1459  1459 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
,03-21 07:32:38.036  1459  1459 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
,03-21 07:32:38.046  1859  1859 I SamsungIME: KeybaordView init() : load resources
03-21 07:32:38.046  1019  1093 E SmartFaceService: onReceive: android.intent.action.BOOT_COMPLETED
03-21 07:32:38.046  1019  1093 D SmartFaceIndicator: no icon
03-21 07:32:38.046  1019  1093 E SmartFaceService: mActiveServiceType: 0
03-21 07:32:38.046  1019  1093 E SmartFaceService: mLightIntensityEnough: true mLux: 0.0
03-21 07:32:38.046  1019  1093 D Stay/Rotation Worker: updateClientsDone. def. do nothing.
03-21 07:32:38.046  1019  1093 E SmartFaceService: Service Type to Worker: 0
03-21 07:32:38.046  1019  1093 E SmartFaceService: Last Active clients:0 Current Active clients: 0
03-21 07:32:38.046  1019  1093 E SmartFaceService: Last Smart Pause clients: 0 Current Smart Pause clients: 0
,03-21 07:32:38.046  1019  1019 D BluetoothA2dp: Proxy object connected
,03-21 07:32:38.056  1019  1019 D BluetoothPan: BluetoothPAN Proxy object connected
,03-21 07:32:38.066  1459  1459 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,03-21 07:32:38.066  1459  1459 W BluetoothHeadset: Proxy not attached to service
,03-21 07:32:38.066  1459  1467 I Telecom : BluetoothPhoneService: Result of Message : true
03-21 07:32:38.066  3170  3170 D HeadsetStateMachine: Proxy object connected
,03-21 07:32:38.066  1019  1019 D RCPManagerService: ACTION_BOOT_COMPLETED
,03-21 07:32:38.066  1019  1019 E RCPManagerService:  BootReceiver : calling scanAndStartRCPProxy ACTION_BOOT_COMPLETED 
,03-21 07:32:38.066  1019  1019 D PersonaManagerService: getPersonasForUser(): returning null!
03-21 07:32:38.066  1019  1019 D RCPManagerService: BootReceiver.onReceive(): Starting RCP Proxy for user = null
03-21 07:32:38.076  1019  1019 E RCPManagerService:  BootReceiver : Exception while scanAndStartRCPProxy() Attempt to get length of null array
,03-21 07:32:38.076  3170  3170 D BluetoothMapService: Received start request. Starting profile...
03-21 07:32:38.076  3170  3170 D BluetoothMapService: start()
,03-21 07:32:38.076   336   336 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,03-21 07:32:38.076  3170  3170 D BluetoothMapService: mStartError = false
03-21 07:32:38.076  3170  3170 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@19a598a0
03-21 07:32:38.076  1019  1019 D MotionRecognitionService:   mReceiver.onReceive : ACTION_BOOT_COMPLETED
,03-21 07:32:38.076  3170  3170 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
03-21 07:32:38.076  3170  3170 D HeadsetPhoneState: sendDeviceDataStateChanged
03-21 07:32:38.076  3170  3304 D HeadsetStateMachine: Disconnected process message: 11
03-21 07:32:38.076  3170  3170 D HeadsetPhoneState: Signal level : previous=0 curr=0
03-21 07:32:38.076  3170  3304 D HeadsetStateMachine: Disconnected process message: 18
,03-21 07:32:38.076  3170  3170 I BluetoothSAPServiceJni: classInitNative(L204): succeeds
,03-21 07:32:38.076  3170  3170 D SapService: Received start request. Starting profile...
03-21 07:32:38.076  3170  3170 D SapService: start()
03-21 07:32:38.076  3170  3170 D BluetoothSAPServiceJni: initializeNative(L209): sap
03-21 07:32:38.076  3170  3170 I bluedroid: get_profile_interface sap
03-21 07:32:38.076  3170  3170 D SapService: mStartError = false
03-21 07:32:38.076  3170  3170 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@19a598a0
03-21 07:32:38.076  3170  3170 E BluetoothAdapterService(430282912): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
03-21 07:32:38.076  3170  3170 D BluetoothA2dp: Proxy object connected
03-21 07:32:38.076  3170  3170 D BluetoothAdapterService: Bluetooth A2dp source service connected
03-21 07:32:38.076  3170  3170 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-21 07:32:38.076  3170  3304 D HeadsetStateMachine: Disconnected process message: 10
03-21 07:32:38.076  3170  3170 E BluetoothAdapterService(430282912): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
,03-21 07:32:38.076  3170  3304 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
03-21 07:32:38.076  3170  3304 D HeadsetStateMachine: Disconnected process message: 11
,03-21 07:32:38.086  3170  3170 E BluetoothAdapterService(430282912): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
03-21 07:32:38.086  3170  3170 E BluetoothAdapterService(430282912): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
03-21 07:32:38.086  3170  3170 E BluetoothAdapterService(430282912): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,03-21 07:32:38.096  1859  1859 I SamsungIME: getCurrentKeyboard
03-21 07:32:38.096  1859  1859 I SamsungIME: getTextKeyboard
,03-21 07:32:38.096  1019  3306 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 n.aB.ff:-1 n.t.a:-1 n.t.b:-1 com.android.server.ssrm.ad.c:-1 
,03-21 07:32:38.126  1859  1859 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,03-21 07:32:38.126  1859  1859 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,03-21 07:32:38.156  3153  3315 D jxcore_app_log: JniHelper::setJavaVM(0xb7d97448), pthread_self() = -1202880352,
,03-21 07:32:38.176  3170  3170 E BluetoothAdapterService(430282912): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true,
03-21 07:32:38.176  3170  3170 E BluetoothAdapterService(430282912): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,03-21 07:32:38.176  3153  3315 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
03-21 07:32:38.176  3153  3315 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
03-21 07:32:38.176  3153  3315 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
03-21 07:32:38.176  3153  3315 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
03-21 07:32:38.176  3153  3315 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
03-21 07:32:38.176  3153  3315 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a03e5fb added. We now have 1 listener(s)
,03-21 07:32:38.186  1019  1019 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
,03-21 07:32:38.186  3170  3288 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
03-21 07:32:38.186  3170  3288 I bluedroid: enable
,03-21 07:32:38.196  1019  1019 D SensorService: [SO] activate (ident=0xb84b5208, enabled=0)
03-21 07:32:38.196  1019  1019 I Sensors : AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,03-21 07:32:38.196  3170  3288 I bt_hci_bdroid: init
,03-21 07:32:38.196  3170  3288 I bt_vendor: bt-vendor : init
03-21 07:32:38.196  3170  3288 I bt_vendor: bt-vendor : get_bt_soc_type
03-21 07:32:38.196  3170  3288 E bt_vendor: get_bt_soc_type: Failed to get soc type
03-21 07:32:38.196  3170  3288 I bt_vendor: init: Local BD Address : 27:76:50:a9:ec:08
03-21 07:32:38.196  3170  3288 D bt_userial_mct: userial_init
,03-21 07:32:38.196  3153  3315 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:76:27
,03-21 07:32:38.196  3153  3315 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,03-21 07:32:38.196  3153  3315 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,03-21 07:32:38.196  3153  3315 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,03-21 07:32:38.196  3170  3326 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
03-21 07:32:38.196  1019  1019 D SensorManager: unregisterListener ::   
,03-21 07:32:38.196  1019  1019 I Sensors : AccelerometerSensor(0) setDelay : 200000000(ns)
03-21 07:32:38.196  3170  3288 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
,03-21 07:32:38.196  3170  3288 I bt_vendor: Starting hciattach daemon
03-21 07:32:38.196  3170  3288 I bt_vendor: try to set false
03-21 07:32:38.206  1019  1019 D SensorService: [SO] changed settle time [0]
03-21 07:32:38.206  1019  1019 D SensorService: [SO] setDelay [200000000]
03-21 07:32:38.206  1019  1019 D SensorService: [SO] activate (ident=0xb8591098, enabled=1)
03-21 07:32:38.206  1019  1019 D SensorService: [SO] AR_init
03-21 07:32:38.206  1019  1019 I Sensors : AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,03-21 07:32:38.206  3170  3288 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
03-21 07:32:38.206  3170  3288 I bt_vendor: Starting hciattach daemon
03-21 07:32:38.206  3170  3288 I bt_vendor: try to set true
,03-21 07:32:38.206  3153  3315 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
03-21 07:32:38.206  3153  3315 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
03-21 07:32:38.206  3153  3315 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
03-21 07:32:38.206  3153  3315 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:76:27
03-21 07:32:38.206  3153  3315 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
03-21 07:32:38.206  3153  3315 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
03-21 07:32:38.206  3153  3315 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
03-21 07:32:38.206  3153  3315 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
03-21 07:32:38.206  3153  3315 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
03-21 07:32:38.206  3153  3315 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
03-21 07:32:38.206  3153  3315 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
03-21 07:32:38.206  3153  3315 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24391656 added. We now have 1 listener(s)
,03-21 07:32:38.206  3153  3315 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,03-21 07:32:38.206  1019  1019 D SensorManager: registerListener :: 1600221811, Screen Orientation Sensor, 200000, 0,  
,03-21 07:32:38.206  1019  1019 V AlarmManagerEXT: mGmsLocationBundling: false
03-21 07:32:38.206  1019  1019 D EnterpriseDeviceManagerService: android.intent.action.BOOT_COMPLETED
,03-21 07:32:38.216  1019  1019 V ApplicationPolicy: boot completed - refreshWidgetStatus
03-21 07:32:38.216  1019  1019 V ApplicationPolicy: refresh widget status for user 0
,03-21 07:32:38.216  3153  3315 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
,03-21 07:32:38.216  1019  1019 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.google.android.googlequicksearchbox
03-21 07:32:38.216  1019  1019 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.activeapplicationwidget
03-21 07:32:38.216  1019  1019 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.mms
03-21 07:32:38.216  1019  1019 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.email
03-21 07:32:38.216  1019  1019 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.digitalclockeasy
03-21 07:32:38.216  1019  1019 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.digitalclock
03-21 07:32:38.216  1019  1019 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.ap.hero.accuweather
03-21 07:32:38.216  1019  1019 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.google.android.apps.plus
03-21 07:32:38.216  1019  1019 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.google.android.googlequicksearchbox
03-21 07:32:38.216  1019  1019 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.google.android.music
03-21 07:32:38.216  1019  1019 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.clockpackage
03-21 07:32:38.216  1019  1019 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
03-21 07:32:38.216  1019  1019 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.tapandpay
03-21 07:32:38.216  1019  1019 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
03-21 07:32:38.216  1019  1019 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.vending
03-21 07:32:38.216  1019  1019 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.google.android.gm
03-21 07:32:38.216  1019  1019 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.google.android.apps.docs
03-21 07:32:38.216  1019  1019 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.gallery3d
03-21 07:32:38.216  1019  1019 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.SPlannerAppWidget
03-21 07:32:38.216  1019  1019 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.sbrowser
03-21 07:32:38.216  1019  1019 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.google.android.apps.plus
03-21 07:32:38.216  1019  1019 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.google.android.talk
03-21 07:32:38.216  1019  1019 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.ap.hero.accuweather
03-21 07:32:38.216  1019  1019 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.chrome
03-21 07:32:38.216  1019  1019 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.google.android.music
03-21 07:32:38.216  1019  1019 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.dualclockdigital
03-21 07:32:38.216  1019  1019 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.music
03-21 07:32:38.216  1019  1019 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.samsungapps
03-21 07:32:38.216  1019  1019 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.vending
03-21 07:32:38.216  1019  1019 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.samsung.android.app.memo
03-21 07:32:38.216  1019  1019 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.gallery3d
03-21 07:32:38.216  1019  1019 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.vending
03-21 07:32:38.216  1019  1019 V ApplicationPolicy: ,isApplicationStateBlocked userId 0 pkgname com.google.android.apps.books
03-21 07:32:38.216  1019  1019 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname flipboard.app
03-21 07:32:38.216  1019  1019 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.fm
03-21 07:32:38.216  1019  1019 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.easymodecontactswidget
03-21 07:32:38.216  1019  1019 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.videoplayer
03-21 07:32:38.216  1019  1019 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.google.android.apps.magazines
03-21 07:32:38.216  1019  1019 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.ap.hero.accuweather
03-21 07:32:38.216  1019  1019 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.SPlannerAppWidget
03-21 07:32:38.226  3153  3315 W org.thaliproject.p2p.btconnectorlib.DiscoveryManager: isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
,03-21 07:32:38.226  1019  3306 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.ssrm.aL.onChange:-1 com.android.server.ssrm.aL.<init>:-1 com.android.server.ssrm.aJ.<init>:-1 com.android.server.ssrm.ad.onBootCompleted:-1 
03-21 07:32:38.226  1019  1151 D EnterpriseDeviceManagerService: runAdminUpdate
,03-21 07:32:38.226  1019  1151 D EnterpriseUtils: File Not Found : /data/system/selfUpdateAdmin.conf
03-21 07:32:38.226  3153  3315 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
03-21 07:32:38.226  3153  3315 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
03-21 07:32:38.226  3153  3315 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
03-21 07:32:38.226  3153  3315 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,03-21 07:32:38.226  1019  1151 D EnterpriseDeviceManagerService: nothing to selfUpdate
,03-21 07:32:38.236  3153  3315 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-21 07:32:38.236  1019  3306 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.ssrm.aJ.eq:-1 com.android.server.ssrm.aJ.<init>:-1 com.android.server.ssrm.ad.onBootCompleted:-1 com.android.server.ssrm.ad.c:-1 
,03-21 07:32:38.236  1019  1019 W PhoneRestrictionPolicy: Message received - msg { when=-9ms what=2 target=com.android.server.enterprise.restriction.PhoneRestrictionPolicy$SmsMmsDeliveryHandler }
,03-21 07:32:38.246  3331  3331 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  ,
,03-21 07:32:38.246  1019  3306 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendStickyBroadcast:1865 com.android.server.ssrm.ad.b:-1 com.android.server.ssrm.ad.onBootCompleted:-1 com.android.server.ssrm.ad.c:-1 com.android.server.ssrm.ae.handleMessage:-1 ,
03-21 07:32:38.246  3153  3315 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:76:27
,03-21 07:32:38.256  1019  1019 D KnoxMUMContainerPolicy: mContainerReceiver : action - android.intent.action.BOOT_COMPLETED
,03-21 07:32:38.256  1019  3333 W PhoneRestrictionPolicy:  >>>> deliveryBlockedMsgs
,03-21 07:32:38.266  1019  1019 I KnoxMUMContainerPolicy: MSG_REMOVE_ORPHANED_CONTAINERS received
,03-21 07:32:38.266  1019  3333 W PhoneRestrictionPolicy: cvList size 0
,03-21 07:32:38.266  1019  3333 W PhoneRestrictionPolicy:  >>>> deliveryBlockedMsgs
,03-21 07:32:38.266  1019  3333 W PhoneRestrictionPolicy: cvList size 0
,03-21 07:32:38.276  3153  3315 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
03-21 07:32:38.276  3153  3315 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-21 07:32:38.276  3153  3315 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-21 07:32:38.276  3153  3315 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
03-21 07:32:38.276  3153  3315 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-21 07:32:38.276  3153  3315 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
03-21 07:32:38.276  3153  3315 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-21 07:32:38.276  3153  3315 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-21 07:32:38.276  3153  3315 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
03-21 07:32:38.276  3153  3315 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,03-21 07:32:38.276  3153  3315 D io.jxcore.node.ConnectivityMonitor: start: OK
03-21 07:32:38.276  3153  3315 I io.jxcore.node.LifeCycleMonitor: start: OK
,03-21 07:32:38.286  3153  3153 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-21 07:32:38.286  3153  3153 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-21 07:32:38.296  1019  1129 D WifiP2pService: InactiveState{ what=143415 }
,03-21 07:32:38.296  1019  1129 D WifiP2pService: P2pEnabledState{ what=143415 }
03-21 07:32:38.296  1019  1129 D WifiP2pService: DefaultState{ what=143415 }
,03-21 07:32:38.296  1019  3306 I i       : No model
03-21 07:32:38.296  1019  1132 D ConnectivityService: Got NetworkFactory Messenger for WIFI_P2P
03-21 07:32:38.296  1019  1129 D WIFI_P2P: got request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] with score 60
03-21 07:32:38.296  1019  1129 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,03-21 07:32:38.306  1019  1132 D ConnectivityService: Got NetworkFactory Messenger for WIFI
,03-21 07:32:38.306  1019  1019 D Tethering: Boot complete.
,03-21 07:32:38.306  1019  1130 E WifiStateMachine: Blacklist file delete
,03-21 07:32:38.306  3341  3341 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,03-21 07:32:38.316  3342  3342 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,03-21 07:32:38.316  3153  3153 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,03-21 07:32:38.326  1019  1019 V EnterpriseBillingEngine: ACTION_BOOT_COMPLETED
,03-21 07:32:38.326  1019  1019 V EnterpriseBillingEngine: handleAllprofiles - start
03-21 07:32:38.326  1019  1019 V EnterpriseBillingPolicyStorage: getCurrentActiveProfiles - start - 
,03-21 07:32:38.326  1019  1019 V EnterpriseBillingPolicyStorage: getCurrentActiveProfiles - end - null
03-21 07:32:38.326  1019  1019 V EnterpriseBillingEngine: handleAllprofiles - end
,03-21 07:32:38.336  3345  3345 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,03-21 07:32:38.336  1019  3306 D FactoryTest: Not factory mode
03-21 07:32:38.336  1019  3306 D w       : isUserBuild = true
03-21 07:32:38.336  1019  3306 D FactoryTest: Not factory mode. isFactoryMode() returend false
,03-21 07:32:38.346  1019  1019 D UsbHostNotification: boot completed
,03-21 07:32:38.346  1019  1019 D UsbHostRestrictor: mBootCompletedReceiver onReceive
03-21 07:32:38.346  1019  1019 D UsbHostRestrictor: initSetUsbBlock STARTED
,03-21 07:32:38.356  3346  3346 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,03-21 07:32:38.366  3347  3347 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,03-21 07:32:38.376  3348  3348 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,03-21 07:32:38.386  1019  1019 D UsbHostRestrictor: SIM was never inserted
,03-21 07:32:38.386  1019  1019 D UsbHostRestrictor: writableHostSysNode[false]
03-21 07:32:38.386  1019  1019 D UsbHostRestrictor: Can NOT Write Disable Sys Node to [ON]
,03-21 07:32:38.396  1019  1130 D WIFI    : got request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] with score 60
03-21 07:32:38.396  1019  1130 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,03-21 07:32:38.406  1019  1041 D SensorService: [SO] Reset Rotation Old [100], Init [1]
,03-21 07:32:38.406  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
03-21 07:32:38.406  1019  1032 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-21 07:32:38.406  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.gms
,03-21 07:32:38.416  2806  2870 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,03-21 07:32:38.426  1019  1019 D PersonaManagerService: ACTION_BOOT_COMPLETED
,03-21 07:32:38.426  1019  1063 E PersonaManagerServiceHandler:  MSG_BOOT_COMPLETE_RECEIVED : soft start personas 
,03-21 07:32:38.426  1019  3306 D SSRM:n  : SIOP:: AP = 400
,03-21 07:32:38.426  1019  1019 D UsbStorageNotification: boot completed,
,03-21 07:32:38.426  1181  1181 D StorageNotification: boot completed
,03-21 07:32:38.436  1019  1063 D KnoxKeyguardUpdateMonitor: onBootComplete
,03-21 07:32:38.436  1019  1043 D GpsLocationProvider: receive broadcast intent, action: android.intent.action.BOOT_COMPLETED
,03-21 07:32:38.436  1019  1019 I KnoxKeyguardUpdateMonitor: onTrustManagedChanged user 0, managed:false
03-21 07:32:38.436  1019  1019 I KnoxKeyguardUpdateMonitor: onTrustChanged user:0, enable:false
,03-21 07:32:38.436  1019  1043 D GpsLocationProvider_ex: BOOT_COMPLETED native_init 
,03-21 07:32:38.446  1019  3306 D SSRM:a  : DeviceInfo:: 000000000000
03-21 07:32:38.446  1019  3306 D SSRM:a  : SettingsAirViewInfo:: 000000000
,03-21 07:32:38.446  1181  1181 D KeyguardViewMediator: onTrustChanged( Showing = false , userId = 0 )
,03-21 07:32:38.476  1019  1043 D GpsLocationProvider: set_capabilities_callback: 55u
,03-21 07:32:38.476  1019  1063 D PersonaManagerService: getPersonasForUser(): returning null!
,03-21 07:32:38.486  1019  1019 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
,03-21 07:32:38.486  1019  1019 D SensorService: [SO] activate (ident=0xb8591098, enabled=0)
03-21 07:32:38.486  1019  1019 I Sensors : AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,03-21 07:32:38.496  1019  1019 D SensorManager: unregisterListener ::   
,03-21 07:32:38.496  1019  1019 I Sensors : AccelerometerSensor(0) setDelay : 66000000(ns)
,03-21 07:32:38.496  1019  1019 D SensorService: [SO] changed settle time [1]
03-21 07:32:38.496  1019  1019 D SensorService: [SO] setDelay [66000000]
03-21 07:32:38.496  1019  1019 D SensorService: [SO] activate (ident=0xb8591098, enabled=1)
03-21 07:32:38.496  1019  1019 D SensorService: [SO] AR_init
03-21 07:32:38.496  1019  1019 I Sensors : AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,03-21 07:32:38.496  1019  1019 D SensorManager: registerListener :: 1600221811, Screen Orientation Sensor, 66000, 0,  
,03-21 07:32:38.506  1019  3357 E LocSvc_api_v02: I/locClientOpen:2279]: Service instance id is -1
,03-21 07:32:38.506  1019  1043 E Geofence_Adapter: I/===> void GeofenceAdapter::addGfClients(GeoFencer*) line 65 
03-21 07:32:38.506  1019  1043 E Geofence_Adapter: I/===> void GeofenceAdapter::updateRegisteredEvents() line 81 
,03-21 07:32:38.516  1019  1043 D GpsLocationProvider_ex: BOOT_COMPLETED native_cleanup 
,03-21 07:32:38.526  1019  1031 D StatusBarManagerService: setIcon slot=volume index=23 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02042a level=0 visible=true num=0 )
,03-21 07:32:38.526  1181  1181 D PhoneStatusBar: updateIcon slot=volume index=23 viewIndex=5 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02042a level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02042a level=0 visible=true num=0 )
,03-21 07:32:38.536  1019  1138 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 07:32:38.536  1019  1138 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:38.536  1019  1138 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:38.536  1019  1138 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 07:32:38.556  1019  1138 I ActivityManager: Start proc com.mobeam.barcodeService for broadcast com.mobeam.barcodeService/.system.AppBroadcastReceiver: pid=3361 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-21 07:32:38.556  3361  3361 E Zygote  : MountEmulatedStorage()
03-21 07:32:38.556  3361  3361 E Zygote  : v2
03-21 07:32:38.556  3361  3361 I libpersona: KNOX_SDCARD checking this for 1000
03-21 07:32:38.556  3361  3361 I libpersona: KNOX_SDCARD not a persona
,03-21 07:32:38.556  3361  3361 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-21 07:32:38.556  3361  3361 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-21 07:32:38.556  3361  3361 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,03-21 07:32:38.566  1019  1041 D SensorService: [SO] currT = 38711063000, prevT = 38311119000, diff = 399944000, [-0.479 0.211 9.902]
,03-21 07:32:38.566  1019  1041 D SensorService: [SO] Reset Rotation Old [100], Init [1]
,03-21 07:32:38.576  2169  3268 W DriveInitializer: Awaiting to be initialized
,03-21 07:32:38.586  3361  3361 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-21 07:32:38.586  2169  3376 W DriveInitializer: Background init thread started
,03-21 07:32:38.586  3361  3361 D ActivityThread: Added TimaKeyStore provider
,03-21 07:32:38.596  3377  3377 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 08:ec:a9:50:76:27 
,03-21 07:32:38.606  3378  3378 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,03-21 07:32:38.626   258   519 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.gms/files/
03-21 07:32:38.626   258   519 W Vold    : Returning OperationFailed - no handler for errno 0
,03-21 07:32:38.626  2169  3376 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.gms/files
,03-21 07:32:38.636  1019  1041 D SensorService: [SO] currT = 38781086000, prevT = 38311119000, diff = 469967000, [-0.479 0.211 9.864]
03-21 07:32:38.636  1019  1041 D SensorService: [SO] -0.479 0.211 9.864
03-21 07:32:38.636  1019  1041 D SensorService: [SO] [100 -> 255]
,03-21 07:32:38.636  1019  3360 E LocSvc_ApiV02: I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PREMIUM_SERVICES_CONFIG_REQ_V02
,03-21 07:32:38.646  1019  3360 E LocSvc_ApiV02: I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PREMIUM_SERVICES_CONFIG_REQ_V02,
,03-21 07:32:38.646  1019  3357 D qmi_secgps_clnt: qmi_secgps_client_init()
,03-21 07:32:38.666  3170  3288 I bt_vendor: bluetooth satus is on
,03-21 07:32:38.666  3170  3328 D bt_userial_mct: userial_open(port:0)
03-21 07:32:38.666  3170  3328 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,03-21 07:32:38.666  3170  3328 I bt_vendor: Done intiailizing UART
,03-21 07:32:38.676  3170  3328 I bt_vendor: Done intiailizing UART
03-21 07:32:38.676  3170  3328 I bt_userial_mct: CMD=65, EVT=65, ACL_Out=66, ACL_In=66
03-21 07:32:38.676  3170  3328 I bt_vendor: Bluetooth Firmware and transport layer are initialized
,03-21 07:32:38.676  3170  3384 D bt_userial_mct: Entering userial_read_thread()
,03-21 07:32:38.676  1019  3357 D qmi_secgps_clnt: SECGPS: qmi_client_get_service_list() returned 0 num_services = 2
,03-21 07:32:38.676  1019  3357 D qmi_secgps_clnt: SECGPS: qmi_client_get_service_list() returned 0 num_entries = 0 num_services = 2
,03-21 07:32:38.676  1019  3357 D qmi_secgps_clnt: SECGPS: qmi_client_get_service_list() returned 0 num_entries = 2 num_services = 2
,03-21 07:32:38.696  3170  3326 I         : BTE_InitTraceLevels -- TRC_HCI
03-21 07:32:38.696  3170  3326 I         : BTE_InitTraceLevels -- TRC_L2CAP
03-21 07:32:38.696  3170  3326 I         : BTE_InitTraceLevels -- TRC_RFCOMM
03-21 07:32:38.696  3170  3326 I         : BTE_InitTraceLevels -- TRC_AVDT
03-21 07:32:38.696  3170  3326 I         : BTE_InitTraceLevels -- TRC_AVRC
03-21 07:32:38.696  3170  3326 I         : BTE_InitTraceLevels -- TRC_A2D
03-21 07:32:38.696  3170  3326 I         : BTE_InitTraceLevels -- TRC_BNEP
03-21 07:32:38.696  3170  3326 I         : BTE_InitTraceLevels -- TRC_BTM
03-21 07:32:38.696  3170  3326 I         : BTE_InitTraceLevels -- TRC_GAP
03-21 07:32:38.696  3170  3326 I         : BTE_InitTraceLevels -- TRC_PAN
03-21 07:32:38.696  3170  3326 I         : BTE_InitTraceLevels -- TRC_SAP
03-21 07:32:38.696  3170  3326 I         : BTE_InitTraceLevels -- TRC_SDP
03-21 07:32:38.696  3170  3326 I         : BTE_InitTraceLevels -- TRC_GATT
03-21 07:32:38.696  3170  3326 I         : BTE_InitTraceLevels -- TRC_SMP
03-21 07:32:38.696  3170  3326 I         : BTE_InitTraceLevels -- TRC_BTAPP
03-21 07:32:38.696  3170  3326 I         : BTE_InitTraceLevels -- TRC_BTIF
03-21 07:32:38.696  3170  3326 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
,03-21 07:32:38.706  3361  3361 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.mobeam.barcodeService.system.AppBroadcastReceiver.onReceive:-1 android.app.ActivityThread.handleReceiver:3125 
,03-21 07:32:38.716  1019  1804 W ActivityManager: userId = 0, bbcId = -10000
03-21 07:32:38.716  1019  1804 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-21 07:32:38.716  1019  1804 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.mobeam.barcodeService, destAppInfo.processName = com.mobeam.barcodeService
,03-21 07:32:38.716  1019  1630 I splitIntent: Split this intent : android.intent.action.BOOT_COMPLETED, mSplitNum[0]=87, mSplitNum[1]=126, mSplitNum[2]=164, mBgSplitQueueNum=3 divideNum= 37 r.nextReceiver= 50 receivers.size=201
03-21 07:32:38.716  1019  1630 I splitIntent: finish to split intent : android.intent.action.BOOT_COMPLETED !! Enqueue -> schedule it!!
,03-21 07:32:38.726  1019  1630 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 07:32:38.726  1019  1630 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:38.726  1019  1630 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:38.726  1019  1630 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 07:32:38.746  3391  3391 E Zygote  : MountEmulatedStorage()
03-21 07:32:38.746  3391  3391 E Zygote  : v2
03-21 07:32:38.746  3391  3391 I libpersona: KNOX_SDCARD checking this for 10097
03-21 07:32:38.746  3391  3391 I libpersona: KNOX_SDCARD not a persona
,03-21 07:32:38.746  3391  3391 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-21 07:32:38.746  1019  1630 I ActivityManager: Start proc flipboard.boxer.app for broadcast flipboard.boxer.app/flipboard.boxer.receiver.BootCompleted: pid=3391 uid=10097 gids={50097, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-21 07:32:38.746  3391  3391 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-21 07:32:38.756  3391  3391 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
03-21 07:32:38.756  1019  3357 E LocSvc_utils_cfg: W/loc_read_sec_gps_conf: no secgps conf file, using defaults
03-21 07:32:38.756  1019  3360 E LocSvc_ApiV02: I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_ENGINE_LOCK_REQ_V02
03-21 07:32:38.766  1019  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:38.766  1019  3360 E LocSvc_ApiV02: I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_ENGINE_LOCK_REQ_V02
03-21 07:32:38.766  1019  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:38.766  1019  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:38.766  1019  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:38.776  1019  3360 E LocSvc_ApiV02: I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_SERVER_REQ_V02
03-21 07:32:38.776  1019  3357 I qmi_secgps_clnt: SECGPS: Set AGPS Mode : 7
03-21 07:32:38.776  1019  3357 D qmi_secgps_clnt: SECGPS: send a qmi message to secgps_server OK
03-21 07:32:38.786  1019  3360 E LocSvc_ApiV02: I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PROTOCOL_CONFIG_PARAMETERS_REQ_V02
03-21 07:32:38.786  1019  3357 E LocSvc_ApiV02: I/virtual loc_api_adapter_err LocApiV02::setSUPLVersion(uint32_t):1558]: supl version = 131072
,03-21 07:32:38.786  3401  3401 E Zygote  : MountEmulatedStorage()
,03-21 07:32:38.786  3401  3401 I libpersona: KNOX_SDCARD checking this for 1101
03-21 07:32:38.786  3401  3401 E Zygote  : v2
03-21 07:32:38.786  3401  3401 I libpersona: KNOX_SDCARD not a persona
03-21 07:32:38.786  3401  3401 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-21 07:32:38.786  1019  1044 I ActivityManager: Start proc org.simalliance.openmobileapi.service for broadcast org.simalliance.openmobileapi.service/.SmartcardServiceBootCompletedBroadcastReceiver: pid=3401 uid=1101 gids={41101, 9997} abi=armeabi-v7a
,03-21 07:32:38.796  1019  3360 E LocSvc_ApiV02: I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PROTOCOL_CONFIG_PARAMETERS_REQ_V02,
,03-21 07:32:38.796  1019  3357 E LocSvc_ApiV02: I/virtual loc_api_adapter_err LocApiV02::setAGLONASSProtocol(long unsigned int):1881]: aGlonassProtocolMask = 0x0
03-21 07:32:38.796  3401  3401 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-21 07:32:38.796  3401  3401 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-21 07:32:38.806  1019  3360 E LocSvc_ApiV02: I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PROTOCOL_CONFIG_PARAMETERS_REQ_V02
,03-21 07:32:38.806  1019  3357 I qmi_secgps_clnt: SECGPS: Set XTRA enable : 1
,03-21 07:32:38.806  1019  3357 D qmi_secgps_clnt: SECGPS: send a qmi message to secgps_server OK
03-21 07:32:38.806  1019  3357 I qmi_secgps_clnt: SECGPS: Set GNSS RF CONFIG : 1
,03-21 07:32:38.806  1019  3357 D qmi_secgps_clnt: SECGPS: send a qmi message to secgps_server OK
03-21 07:32:38.806  1019  3357 I qmi_secgps_clnt: SECGPS: Set CERT TYPE : 15
,03-21 07:32:38.806  1019  3357 D qmi_secgps_clnt: SECGPS: send a qmi message to secgps_server OK
03-21 07:32:38.806  1019  3357 E LocSvc_ApiV02: I/virtual loc_api_adapter_err LocApiV02::setLPPConfig(uint32_t):1605]: lpp profile = 0
,03-21 07:32:38.816  3391  3391 D TimaKeyStoreProvider: TimaSignature is unavailable
03-21 07:32:38.816  3391  3391 D ActivityThread: Added TimaKeyStore provider
,03-21 07:32:38.826   322   322 I art     : Explicit concurrent mark sweep GC freed 8699(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 599us total 31.971ms
,03-21 07:32:38.826  3170  3326 W bt-l2cap: l2c_link_processs_ble_num_bufs 16
,03-21 07:32:38.826  3170  3326 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa443bead 
03-21 07:32:38.826  3170  3326 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa443bead 
,03-21 07:32:38.846  3401  3401 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-21 07:32:38.846   322   322 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 649us total 21.620ms
,03-21 07:32:38.846  3401  3401 D ActivityThread: Added TimaKeyStore provider
03-21 07:32:38.856  2169  3376 W DriveInitializer: Background init thread ended
03-21 07:32:38.856  3170  3291 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
03-21 07:32:38.856  3170  3291 E bt-btif : Calling BTA_HhEnable
03-21 07:32:38.856  3170  3291 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
03-21 07:32:38.856  3170  3291 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
03-21 07:32:38.856  3170  3291 E BluetoothServiceJni: populateRssiValuesNative
03-21 07:32:38.856  3170  3291 I bluedroid: getModelRssiValues
03-21 07:32:38.856  3170  3291 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
03-21 07:32:38.856  3170  3291 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,03-21 07:32:38.866  1019  3360 E LocSvc_ApiV02: I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PROTOCOL_CONFIG_PARAMETERS_REQ_V02
03-21 07:32:38.866  1019  3357 E LocSvc_ApiV02: I/virtual loc_api_adapter_err LocApiV02::setSensorControlConfig(int, int):1644]: sensors disabled = 1
,03-21 07:32:38.866  1019  3360 E LocSvc_ApiV02: I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_SENSOR_CONTROL_CONFIG_REQ_V02
,03-21 07:32:38.866  1019  3360 E LocSvc_ApiV02: I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_SENSOR_PERFORMANCE_CONTROL_CONFIGURATION_REQ_V02
03-21 07:32:38.866  1019  3357 E LocSvc_ApiV02: E/virtual loc_api_adapter_err LocApiV02::setXtraVersionCheck(loc_core::xtra_version_check):3316]: Set xtra version check failed. status: eLOC_CLIENT_FAILURE_INTERNAL, ind status:eQMI_LOC_SUCCESS_V02
,03-21 07:32:38.866   322   322 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 1.863ms total 20.701ms
,03-21 07:32:38.876  3170  3291 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3)
,03-21 07:32:38.876  3170  3291 D BluetoothAdapterProperties: Scan Mode:20
03-21 07:32:38.876  3170  3291 D BluetoothAdapterProperties: Discoverable Timeout:120
,03-21 07:32:38.886  3170  3291 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EC:4E
03-21 07:32:38.886  3170  3291 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
03-21 07:32:38.886  3170  3291 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
,03-21 07:32:38.886  3170  3291 E bt-btif : btif_sock_init: !radio_req && !rfc_init
03-21 07:32:38.886  3170  3291 E bt-btif : btif_sock_init: !vhci_init
03-21 07:32:38.886  3170  3291 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
,03-21 07:32:38.886  3170  3291 D IOP_DB_BT: db_open: db_open : handle 2961367056l, read 13894 bytes onto local cache
03-21 07:32:38.886  3170  3291 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
,03-21 07:32:38.886  3170  3291 D IOP_DB_BT: db_query: result 1
03-21 07:32:38.886  3170  3291 I         : iop_db_open: iop_db_open status 0
,03-21 07:32:38.886  3170  3291 D bte_conf: Device ID record 1 : primary,
03-21 07:32:38.886  3170  3291 D bte_conf:   vendorId            = 0075
03-21 07:32:38.886  3170  3291 D bte_conf:   vendorIdSource      = 0001
03-21 07:32:38.886  3170  3291 D bte_conf:   product             = 0100
,03-21 07:32:38.886  3170  3291 D bte_conf:   version             = 0200
03-21 07:32:38.886  3170  3291 D bte_conf:   clientExecutableURL = 
03-21 07:32:38.886  3170  3291 D bte_conf:   serviceDescription  = 
03-21 07:32:38.886  3170  3291 D bte_conf:   documentationURL    = 
03-21 07:32:38.886  3170  3291 D bte_conf: bte_load_did_conf no section named DID2.
,03-21 07:32:38.886  3170  3384 E bt_mct  : hci lib postload completed
03-21 07:32:38.886  3170  3291 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,03-21 07:32:38.886  1019  1283 D SettingsProvider: name = next_alarm_formatted
03-21 07:32:38.886  1019  1283 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-21 07:32:38.886  1019  1283 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-21 07:32:38.886  1019  1283 D SettingsProvider: selectionArgs: false
03-21 07:32:38.886  1019  1283 D SettingsProvider: selectionArgs: 10081
03-21 07:32:38.886  1019  1283 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-21 07:32:38.886  1019  1283 D SettingsProvider: ret = -1
,03-21 07:32:38.896  1019  1019 D SettingsProvider: name = bluetooth_name
,03-21 07:32:38.906  1019  1031 W ActivityManager: userId = 0, bbcId = -10000
,03-21 07:32:38.906  1019  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-21 07:32:38.906  1019  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,03-21 07:32:38.906  3170  3288 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
03-21 07:32:38.906  3170  3288 D BluetoothAdapterProperties: ScanMode =  20
03-21 07:32:38.906  3170  3288 D BluetoothAdapterProperties: State =  11
,03-21 07:32:38.906  1019  1032 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,03-21 07:32:38.916  3170  3288 D BluetoothAdapterProperties: Setting state to 12
,03-21 07:32:38.916  3401  3401 W ResourcesManager: Asset path '/system/framework/org.simalliance.openmobileapi.jar' does not exist or contains no resources.
,03-21 07:32:38.916  3170  3288 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,03-21 07:32:38.926  3170  3291 D BluetoothAdapterProperties: Scan Mode:21
,03-21 07:32:38.926  3170  3291 D BluetoothAdapterProperties: Discoverable Timeout:120
,03-21 07:32:38.926  1019  1531 D SettingsProvider: name = bluetooth_a2dp_sink_mode
,03-21 07:32:38.926  1019  1531 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-21 07:32:38.926  1019  1531 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-21 07:32:38.926  1019  1531 D SettingsProvider: selectionArgs: false
03-21 07:32:38.926  1019  1531 D SettingsProvider: selectionArgs: 1002
03-21 07:32:38.926  1019  1531 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-21 07:32:38.926  1019  1531 D SettingsProvider: ret = -1
,03-21 07:32:38.936  3401  3401 V SmartcardService: main Received broadcast
03-21 07:32:38.936  3401  3401 V SmartcardService: Starting smartcard service after boot completed
,03-21 07:32:38.946  1019  1502 W ActivityManager: userId = 0, bbcId = -10000
,03-21 07:32:38.946  1019  1502 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-21 07:32:38.946  1019  1502 W ActivityManager: NORMAL SET : srcAppInfo.processName = org.simalliance.openmobileapi.service, destAppInfo.processName = org.simalliance.openmobileapi.service
,03-21 07:32:38.966  1019  1804 I ActivityManager: Killing 2732:com.sec.android.soagent/u0a31 (adj 15): empty #31
,03-21 07:32:38.976  1238  1238 V DownloadManager: onReceive intent + android.intent.action.BOOT_COMPLETED
,03-21 07:32:38.976  1019  1630 W ActivityManager: userId = 0, bbcId = -10000
,03-21 07:32:38.976  1019  1630 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-21 07:32:38.976  1019  1630 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
,03-21 07:32:38.976  3153  3153 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
03-21 07:32:38.976  3153  3153 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
03-21 07:32:38.976  3153  3153 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-21 07:32:38.976  3153  3153 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-21 07:32:38.976  3153  3153 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-21 07:32:38.976  3153  3153 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-21 07:32:38.976  3153  3153 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-21 07:32:38.976  3153  3153 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-21 07:32:38.976  3153  3153 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
03-21 07:32:38.976  3153  3153 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
03-21 07:32:38.976  1019  1571 W ActivityManager: userId = 0, bbcId = -10000
03-21 07:32:38.976  1019  1571 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-21 07:32:38.986  1019  1571 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,03-21 07:32:38.986  1019  1499 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 07:32:38.986  1019  1499 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:38.986  1019  1499 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:38.986  1019  1499 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 07:32:38.986  3153  3153 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-21 07:32:38.996  3432  3432 E Zygote  : MountEmulatedStorage()
03-21 07:32:38.996  3432  3432 E Zygote  : v2
03-21 07:32:38.996  3432  3432 I libpersona: KNOX_SDCARD checking this for 1000
03-21 07:32:38.996  3432  3432 I libpersona: KNOX_SDCARD not a persona
,03-21 07:32:39.006  3432  3432 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-21 07:32:39.006  1019  1499 I ActivityManager: Start proc com.sec.android.app.sysscope for broadcast com.sec.android.app.sysscope/.receiver.BootCompleteReceiver: pid=3432 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,03-21 07:32:39.006  3432  3432 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-21 07:32:39.006  3432  3432 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-21 07:32:39.006  1019  1531 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,03-21 07:32:39.016  1019  1571 D SecContentProvider2: uri = 15 selection = getAppBlockDownloadState
03-21 07:32:39.016  1019  1571 D SecContentProvider2: mCursor = null
03-21 07:32:39.016  3170  3288 D BluetoothAdapterService: Bluetooth PBAP supproted is true
03-21 07:32:39.016  3170  3288 D BluetoothAdapterService: updateAdapterState state is 12
,03-21 07:32:39.016  1019  1395 W ActivityManager: userId = 0, bbcId = -10000
03-21 07:32:39.016  1019  1395 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-21 07:32:39.016  1019  1395 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,03-21 07:32:39.026  3170  3288 D BluetoothAdapterService: Autoconnection is available ,
,03-21 07:32:39.026  3170  3288 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12,
03-21 07:32:39.026  3170  3288 D BluetoothAdapterService: starting service from this receiver
03-21 07:32:39.026  1238  1238 D MediaScannerReceiver: action: android.intent.action.BOOT_COMPLETED
03-21 07:32:39.026  3170  3183 D BluetoothA2dp: onBluetoothStateChange: up=true
03-21 07:32:39.026  3170  3193 D BluetoothAdapter: onBluetoothStateChange: up=true
03-21 07:32:39.026  3170  3193 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
03-21 07:32:39.026  1019  1048 D BluetoothA2dp: onBluetoothStateChange: up=true
03-21 07:32:39.026  1019  1531 W ActivityManager: userId = 0, bbcId = -10000
03-21 07:32:39.026  3153  3161 D BluetoothAdapter: onBluetoothStateChange: up=true
03-21 07:32:39.026  1019  1531 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-21 07:32:39.026  3153  3161 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,03-21 07:32:39.026  1019  1531 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
03-21 07:32:39.026  1019  1048 D BluetoothAdapter: onBluetoothStateChange: up=true
03-21 07:32:39.026  1019  1048 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
03-21 07:32:39.026  1181  3278 D BluetoothAdapter: onBluetoothStateChange: up=true
03-21 07:32:39.026  1181  3278 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,03-21 07:32:39.036  3170  3288 I BluetoothAdapterState: Entering On State from state = 11
,03-21 07:32:39.036  1459  1467 D BluetoothAdapter: onBluetoothStateChange: up=true
,03-21 07:32:39.036  1459  1467 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,03-21 07:32:39.046  1999  2198 D BluetoothAdapter: onBluetoothStateChange: up=true
03-21 07:32:39.046  1999  2198 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
03-21 07:32:39.046  1468  1483 D BluetoothAdapter: onBluetoothStateChange: up=true
03-21 07:32:39.046  1468  1483 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,03-21 07:32:39.046  1488  1500 D BluetoothAdapter: onBluetoothStateChange: up=true
03-21 07:32:39.046  1488  1500 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,03-21 07:32:39.046  1181  1181 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-21 07:32:39.056  1019  1019 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED,
03-21 07:32:39.056  1019  1019 I InputMethodManagerService: [BT Setting State] State =12
03-21 07:32:39.056  1019  1019 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,03-21 07:32:39.056  3432  3432 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-21 07:32:39.056  3432  3432 D ActivityThread: Added TimaKeyStore provider
,03-21 07:32:39.066  1181  1181 D BluetoothTile:  onBluetoothStateChange:
,03-21 07:32:39.066  1181  1181 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
03-21 07:32:39.066  1181  1181 D BluetoothTile:  onBluetoothPairedDevicesChanged:
03-21 07:32:39.066  1181  1181 D BluetoothTile:  getBluetoothState : 12
,03-21 07:32:39.066  1859  1859 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,03-21 07:32:39.066  1181  1627 D BluetoothTile:  handleUpdatestate:false name:null
,03-21 07:32:39.076  1019  1138 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,03-21 07:32:39.076  1019  1031 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,03-21 07:32:39.086  1181  1627 D BluetoothTile:  handleUpdatestate:false name:null
03-21 07:32:39.086  1181  1181 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,03-21 07:32:39.086  1459  1459 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@a03e5fb, true
,03-21 07:32:39.086  1459  1459 D BluetoothHeadset: registerMessageListener
,03-21 07:32:39.086  3170  3170 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,03-21 07:32:39.086  1181  1627 D BluetoothTile:  handleUpdatestate:false name:null
,03-21 07:32:39.096  3170  3183 D HeadsetService: registerMessageListener
,03-21 07:32:39.096  3170  3183 D HeadsetService: registerMessageListener
,03-21 07:32:39.096  3170  3304 D HeadsetStateMachine: Disconnected process message: 70
03-21 07:32:39.096  3170  3304 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@3ba31973
,03-21 07:32:39.096  1459  1459 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
,03-21 07:32:39.096  1459  1459 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,03-21 07:32:39.096  1019  1043 W libprocessgroup: failed to open /acct/uid_10031/pid_2732/cgroup.procs: No such file or directory
,03-21 07:32:39.106  1459  1459 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
03-21 07:32:39.106  1459  1459 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
,03-21 07:32:39.106  1459  1459 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,03-21 07:32:39.116  3153  3338 W jxcore-log: Initializing JXcore engine
03-21 07:32:39.116  3153  3338 W jxcore-log: JXcore engine is ready
,03-21 07:32:39.116  3170  3304 D HeadsetStateMachine: Disconnected process message: 9
,03-21 07:32:39.116  3170  3304 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,03-21 07:32:39.126  3170  3170 I BluetoothPbapService: Handler(): got msg=1
,03-21 07:32:39.126  1019  1531 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,03-21 07:32:39.136   285   285 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
,03-21 07:32:39.136   285   285 V voice   : voice_set_parameters: enter: A2dpSuspended=false
03-21 07:32:39.136   285   285 V voice   : voice_set_parameters: exit with code(-2)
,03-21 07:32:39.136   285   285 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
03-21 07:32:39.136   285   285 V msm8974_platform: platform_set_parameters: exit with code(-2)
,03-21 07:32:39.136   285   285 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
03-21 07:32:39.136   285   285 V audio_hw_primary: adev_set_parameters: exit
,03-21 07:32:39.136  3170  3304 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,03-21 07:32:39.146  1019  1395 W ActivityManager: userId = 0, bbcId = -10000
03-21 07:32:39.146  1019  1395 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-21 07:32:39.146  1019  1395 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-21 07:32:39.156  1019  1564 I ActivityManager: Killing 2336:com.google.android.apps.magazines/u0a110 (adj 15): empty #31
,03-21 07:32:39.156  3432  3432 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.app.sysscope.receiver.BootCompleteReceiver.onReceive:-1 android.app.ActivityThread.handleReceiver:3125 
,03-21 07:32:39.166  1019  1138 W ActivityManager: userId = 0, bbcId = -10000
03-21 07:32:39.166  1019  1138 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-21 07:32:39.166  1019  1138 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.sysscope, destAppInfo.processName = com.sec.android.app.sysscope
,03-21 07:32:39.166  1019  1804 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 07:32:39.166  1019  1804 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:39.166  1019  1804 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:39.166  1019  1804 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 07:32:39.186  3453  3453 E Zygote  : MountEmulatedStorage()
03-21 07:32:39.186  3453  3453 E Zygote  : v2
03-21 07:32:39.186  3453  3453 I libpersona: KNOX_SDCARD checking this for 1000
03-21 07:32:39.186  3453  3453 I libpersona: KNOX_SDCARD not a persona
,03-21 07:32:39.186  3453  3453 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-21 07:32:39.186  3453  3453 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
03-21 07:32:39.186  1019  1804 I ActivityManager: Start proc com.sec.usbsettings for broadcast com.sec.usbsettings/.UltraKeyStringBroadcastReceiver: pid=3453 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-21 07:32:39.186  3453  3453 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,03-21 07:32:39.196  1019  3306 D SSRM:a  : DeviceInfo:: 000000000000
03-21 07:32:39.196  1019  3306 D SSRM:a  : SettingsAirViewInfo:: 000000000
,03-21 07:32:39.196  1939  1939 E audit   : type=1400 msg=audit(1458541959.196:205): avc:  denied  { ioctl } for  pid=3338 comm="Thread-431" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,03-21 07:32:39.196  1939  1939 E audit   :  SEPF_SM-A300FU_5.0.2_0027
03-21 07:32:39.196  1939  1939 E audit   : type=1300 msg=audit(1458541959.196:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=a a1=5451 a2=4 a3=921df8f8 items=0 ppid=322 ppcomm=main pid=3338 auid=4294967295 uid=10167 gid=10167 euid=10167 suid=10167 fsuid=10167 egid=10167 sgid=10167 fsgid=10167 ses=4294967295 tty=(none) comm="Thread-431" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
03-21 07:32:39.196  1939  1939 E audit   : type=1320 msg=audit(1458541959.196:205): 
,03-21 07:32:39.206  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
,03-21 07:32:39.206  1019  1032 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-21 07:32:39.206  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,03-21 07:32:39.206  3170  3463 V BluetoothPbapService: PBAP Service initSocket try: 0
,03-21 07:32:39.216  1019  1805 W ActivityManager: userId = 0, bbcId = -10000
03-21 07:32:39.216  1019  1805 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-21 07:32:39.216  1019  1805 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
03-21 07:32:39.216  3153  3338 W jxcore-log: Starting JXcore engine
,03-21 07:32:39.216  3170  3465 D BluetoothMapMasInstance: set MAP SDP message type : 1
,03-21 07:32:39.216  1019  1561 W ActivityManager: userId = 0, bbcId = -10000
03-21 07:32:39.216  1019  1561 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-21 07:32:39.216  1019  1561 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-21 07:32:39.226  3170  3463 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-21 07:32:39.226  3453  3453 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-21 07:32:39.226  3453  3453 D ActivityThread: Added TimaKeyStore provider
,03-21 07:32:39.236  3170  3465 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-21 07:32:39.236  1019  1032 I ActivityManager: Killing 1612:com.sec.android.provider.badge/u0a68 (adj 15): empty #31
,03-21 07:32:39.236  1019  1395 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:39.236  1019  1395 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:39.236  1019  1395 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:39.236  1019  1395 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 07:32:39.256  3473  3473 E Zygote  : MountEmulatedStorage(),
03-21 07:32:39.256  3473  3473 I libpersona: KNOX_SDCARD checking this for 1000
03-21 07:32:39.256  3473  3473 E Zygote  : v2
03-21 07:32:39.256  3473  3473 I libpersona: KNOX_SDCARD not a persona
03-21 07:32:39.256  3473  3473 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,03-21 07:32:39.256  3473  3473 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
03-21 07:32:39.256  1019  1395 I ActivityManager: Start proc com.samsung.android.app.colorblind for broadcast com.samsung.android.app.colorblind/.ColorBlindBootReceiver: pid=3473 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-21 07:32:39.256  3473  3473 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-21 07:32:39.256  3170  3463 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[74]}
,03-21 07:32:39.256  3170  3463 D BluetoothSocket: bindListen(), new LocalSocket 
03-21 07:32:39.256  3170  3463 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
03-21 07:32:39.266  3170  3463 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2fec2b3a
03-21 07:32:39.266  3170  3463 D BluetoothSocket: channel: 19
03-21 07:32:39.266  1019  1630 W ActivityManager: userId = 0, bbcId = -10000
03-21 07:32:39.266  3170  3463 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
03-21 07:32:39.266  1019  1630 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-21 07:32:39.266  1019  1630 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-21 07:32:39.266  3170  3465 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[76]}
03-21 07:32:39.266  3170  3465 D BluetoothSocket: bindListen(), new LocalSocket 
03-21 07:32:39.266  3170  3465 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
03-21 07:32:39.266  3170  3465 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@59643eb
,03-21 07:32:39.266  3170  3465 D BluetoothSocket: channel: 5
,03-21 07:32:39.286  3473  3473 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-21 07:32:39.286  3473  3473 D ActivityThread: Added TimaKeyStore provider
,03-21 07:32:39.296  3391  3391 E ActivityThread: Failed to find provider info for flipboard.auth.internal.debug
,03-21 07:32:39.296  3391  3391 E ActivityThread: Failed to find provider info for flipboard.auth.internal
,03-21 07:32:39.296  1019  1395 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 07:32:39.296  1019  1395 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:39.296  1019  1395 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:39.296  1019  1395 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 07:32:39.306  3473  3473 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,03-21 07:32:39.316  3488  3488 E Zygote  : MountEmulatedStorage(),
03-21 07:32:39.316  3488  3488 E Zygote  : v2
,03-21 07:32:39.316  3488  3488 I libpersona: KNOX_SDCARD checking this for 10096
03-21 07:32:39.316  3488  3488 I libpersona: KNOX_SDCARD not a persona
,03-21 07:32:39.326  1019  1395 I ActivityManager: Start proc flipboard.app for content provider flipboard.app/flipboard.remoteservice.UserContentProvider: pid=3488 uid=10096 gids={50096, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,03-21 07:32:39.326  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:39.326  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:39.326  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:39.326  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 07:32:39.336  1238  3472 D MediaScannerService: !@start scanning volume internal: [/system/media, /oem/media]
,03-21 07:32:39.336  3488  3488 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-21 07:32:39.336  3488  3488 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,03-21 07:32:39.336  3488  3488 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,03-21 07:32:39.346  3495  3495 E Zygote  : MountEmulatedStorage()
03-21 07:32:39.346  3495  3495 E Zygote  : v2
03-21 07:32:39.346  3495  3495 I libpersona: KNOX_SDCARD checking this for 10155
03-21 07:32:39.346  3495  3495 I libpersona: KNOX_SDCARD not a persona
,03-21 07:32:39.346  3495  3495 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-21 07:32:39.346  3153  3338 W jxcore-log: Platform android,
03-21 07:32:39.346  3153  3338 W jxcore-log: 
03-21 07:32:39.346  3153  3338 W jxcore-log: Process ARCH arm
03-21 07:32:39.346  3153  3338 W jxcore-log: 
,03-21 07:32:39.346  3495  3495 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-21 07:32:39.346  3495  3495 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-21 07:32:39.346  1019  1031 I ActivityManager: Start proc com.sec.enterprise.knox.cloudmdm.smdms for broadcast com.sec.enterprise.knox.cloudmdm.smdms/.core.CoreReceiver: pid=3495 uid=10155 gids={50155, 9997, 3003, 3002, 1028, 1015, 3001} abi=armeabi-v7a
,03-21 07:32:39.356  1019  1031 I ActivityManager: Killing 2652:com.google.android.music:main/u0a108 (adj 15): empty #31
,03-21 07:32:39.366  1019  1531 W ActivityManager: userId = 0, bbcId = -10000
03-21 07:32:39.366  1019  1531 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-21 07:32:39.366  1019  1531 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,03-21 07:32:39.366  3488  3488 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-21 07:32:39.366  3488  3488 D ActivityThread: Added TimaKeyStore provider
,03-21 07:32:39.396  1238  1238 D MtpService: updating state; isCurrentUser=true, mMtpLocked=false
03-21 07:32:39.396  1488  1785 D TP/MmsProvider: Update uri=content://mms, match=0
,03-21 07:32:39.396  1488  1785 D TP/MmsProvider: update , handleReadChangedBroadcast
03-21 07:32:39.396  1488  1785 D TP/MmsSmsProvider: need read changed broadcast:false
,03-21 07:32:39.406  3495  3495 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-21 07:32:39.406  1019  1043 W libprocessgroup: failed to open /acct/uid_10110/pid_2336/cgroup.procs: No such file or directory
,03-21 07:32:39.406  3495  3495 D ActivityThread: Added TimaKeyStore provider
,03-21 07:32:39.406  2423  2423 I Mms:transaction: [MmsSystemEventReceiver] restorePduNotificationStatus count=0
,03-21 07:32:39.406  2423  2423 D Mms/MessagingNotification: [start]    nonBlockingUpdateMessageIndicator() consume time = 8797.655257
03-21 07:32:39.406  2423  2423 I Mms/ReservationManager: resetAfterConnected()
,03-21 07:32:39.406  2423  3518 D Mms/MessagingNotification: sDisableVibrateForCamera = false
,03-21 07:32:39.406  2423  3518 D Mms/TelephonyPermission: isDefault true
,03-21 07:32:39.416  1019  1809 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:39.416  1019  1809 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:39.416  1019  1809 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:39.416  1019  1809 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 07:32:39.416  1488  1498 D TP/MmsProvider: Query uri=content://mms, match=0, calling pid = 2423
,03-21 07:32:39.426  3519  3519 E Zygote  : MountEmulatedStorage()
03-21 07:32:39.426  3519  3519 E Zygote  : v2
03-21 07:32:39.426  3519  3519 I libpersona: KNOX_SDCARD checking this for 10082
03-21 07:32:39.426  3519  3519 I libpersona: KNOX_SDCARD not a persona
,03-21 07:32:39.426  3519  3519 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-21 07:32:39.426  3495  3495 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
03-21 07:32:39.426  3519  3519 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-21 07:32:39.436  3519  3519 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-21 07:32:39.436  1019  1809 I ActivityManager: Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=3519 uid=10082 gids={50082, 9997, 3003} abi=armeabi-v7a
,03-21 07:32:39.436  1019  1809 I ActivityManager: Killing 2871:com.sec.android.cloudagent/u0a1 (adj 15): empty #31
,03-21 07:32:39.446  1488  1901 D TP/MmsSmsProvider: query,matched:7, calling pid = 2423
,03-21 07:32:39.446  1488  1901 D TP/MmsSmsProvider: match 7:Elapsed time : 2.906 ms
,03-21 07:32:39.446  3519  3519 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-21 07:32:39.446  3519  3519 D ActivityThread: Added TimaKeyStore provider
,03-21 07:32:39.466  1488  1498 D TP/MmsSmsProvider: query,matched:200, calling pid = 2423
,03-21 07:32:39.466  1238  3472 E SQLiteLog: (283) recovered 405 frames from WAL file /data/data/com.android.providers.media/databases/internal.db-wal
,03-21 07:32:39.466  1488  1498 D TP/MmsSmsProvider: match 200:Elapsed time : 0.967 ms
,03-21 07:32:39.466  2423  2423 I Mms/ReservationManager: getReservedSendMessageCount(): retMessageCount=0
,03-21 07:32:39.476  1019  1564 W ActivityManager: userId = 0, bbcId = -10000
03-21 07:32:39.476  1019  1564 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-21 07:32:39.476  1019  1564 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
,03-21 07:32:39.476  1019  1138 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:39.476  1019  1138 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:39.476  1019  1138 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:39.476  1019  1138 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 07:32:39.486  3534  3534 E Zygote  : MountEmulatedStorage()
03-21 07:32:39.486  3534  3534 E Zygote  : v2
03-21 07:32:39.496  3534  3534 I libpersona: KNOX_SDCARD checking this for 10043
03-21 07:32:39.496  3534  3534 I libpersona: KNOX_SDCARD not a persona
,03-21 07:32:39.496  3534  3534 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-21 07:32:39.496  3534  3534 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-21 07:32:39.496  3534  3534 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-21 07:32:39.496  1019  1138 I ActivityManager: Start proc com.sec.android.app.safetyassurance for broadcast com.sec.android.app.safetyassurance/.SafetyAssuranceReceiver: pid=3534 uid=10043 gids={50043, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,03-21 07:32:39.516  1019  1043 W libprocessgroup: failed to open /acct/uid_10068/pid_1612/cgroup.procs: No such file or directory
,03-21 07:32:39.516  1488  1500 D TP/SmsProvider: query,matched:0, calling pid = 2423
,03-21 07:32:39.526  1488  1500 D TP/SmsProvider: match 0:Elapsed time : 3.292 ms
,03-21 07:32:39.526  2423  2423 D Mms/SmsReceiverService: onStart: #1, mResultCode: 0 = Unknown error code, action = android.intent.action.BOOT_COMPLETED
,03-21 07:32:39.526  3534  3534 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-21 07:32:39.526  3534  3534 D ActivityThread: Added TimaKeyStore provider
,03-21 07:32:39.536  2423  3543 D Mms/TelephonyPermission: isDefault true
03-21 07:32:39.536  2423  3543 D Mms/SmsReceiverService: [SMS]Receiver handleMessage : Action =android.intent.action.BOOT_COMPLETED
,03-21 07:32:39.536  2423  3543 D Mms/SmsReceiverService: [start]    handleBootCompleted() consume time = 124.984479
,03-21 07:32:39.546  3488  3488 I MultiDex: VM with version 2.1.0 has multidex support
03-21 07:32:39.546  3488  3488 I MultiDex: install
03-21 07:32:39.546  3488  3488 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,03-21 07:32:39.546  1019  1043 W libprocessgroup: failed to open /acct/uid_10108/pid_2652/cgroup.procs: No such file or directory
,03-21 07:32:39.546  1019  1043 W libprocessgroup: failed to open /acct/uid_10001/pid_2871/cgroup.procs: No such file or directory
,03-21 07:32:39.556  3534  3534 W ResourcesManager: Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
03-21 07:32:39.556  3534  3534 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-21 07:32:39.556  3534  3534 W ResourcesManager: Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
,03-21 07:32:39.566  1019  1283 I ActivityManager: Killing 2930:com.samsung.android.sconnect/u0a121 (adj 15): empty #31
,03-21 07:32:39.566  1019  1283 I ActivityManager: Killing 2896:com.sec.android.diagmonagent/1000 (adj 15): empty #32
,03-21 07:32:39.566  1019  1019 I DrmEventReceiver: DrmEventReceiver : onReceive
03-21 07:32:39.566  1019  1019 I DrmEventReceiver: DrmEventReceiver : onReceiveWithPrivilege intent.getTypenull
,03-21 07:32:39.566  1019  1019 I DrmEventReceiver: DrmEventReceiver : beginStartingService
03-21 07:32:39.566  1019  1019 I System.out: start Service
,03-21 07:32:39.576  1019  1019 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.server.DrmEventReceiver.beginStartingService:59 com.android.server.DrmEventReceiver.onReceiveWithPrivilege:47 
,03-21 07:32:39.616  3153  3338 I jxcore-log: JXcore Cordova bridge is ready!
03-21 07:32:39.616  3153  3338 I jxcore-log: 
,03-21 07:32:39.616  3153  3338 W jxcore-log: JXcore engine is started
,03-21 07:32:39.626  3153  3315 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,03-21 07:32:39.626  3153  3153 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,03-21 07:32:39.636  1019  1531 D SettingsProvider: name = block_emergency_message
,03-21 07:32:39.636  1019  1531 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-21 07:32:39.636  1019  1531 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-21 07:32:39.636  1019  1531 D SettingsProvider: selectionArgs: false
03-21 07:32:39.636  1019  1531 D SettingsProvider: selectionArgs: 10043
03-21 07:32:39.636  1019  1531 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-21 07:32:39.636  1019  1531 D SettingsProvider: ret = -1
,03-21 07:32:39.636  1019  1809 W ActivityManager: getTasks: caller 10043 is using old GET_TASKS but privileged; allowing
,03-21 07:32:39.636  3153  3338 E jxcore  : Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
03-21 07:32:39.636  3153  3338 E jxcore  : Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,03-21 07:32:39.646  3153  3153 I chromium: [INFO:CONSOLE(57)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (57)
03-21 07:32:39.646  3153  3153 I chromium: [INFO:CONSOLE(62)] "****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****", source: file:///android_asset/www/js/thali_main.js (62)
,03-21 07:32:39.646  3495  3495 D [0]UMC:Core: onCreate(): 
03-21 07:32:39.666  3519  3519 E UpdateRequestReceiver: ignoring update request
,03-21 07:32:39.676  1019  1031 D FocusedStackFrame: Set to : 0
,03-21 07:32:39.676  1019  1031 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-21 07:32:39.676  1019  1031 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
03-21 07:32:39.676  1019  1031 D InputDispatcher: Focused application set to: xxxx
,03-21 07:32:39.676  1019  1031 D InputDispatcher: Focus left window: 3153
,03-21 07:32:39.686  1019  1049 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-21 07:32:39.686  1019  1049 D PointerIcon: setMouseCustomIcon IconType is same.101
,03-21 07:32:39.686   259  1156 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (154 us)
,03-21 07:32:39.696  1488  1785 D TP/MmsSmsProvider: getThreadUnReadCount unreadCount=0 imUnreadCount=0
03-21 07:32:39.696  1488  1785 D TP/MmsSmsProvider: deleteConversation threadId: 9223372036854775806
,03-21 07:32:39.696  1488  1785 D TP/MmsSmsProvider: delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
03-21 07:32:39.696  1488  1785 V TP/MmsSmsDatabaseHelper: updateThread(), thread_id = 9223372036854775806
,03-21 07:32:39.696  1488  1785 V TP/MmsSmsDatabaseHelper: sUpgradeVersion = 0, db.getVersion() = 81
,03-21 07:32:39.696  1488  1785 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-21 07:32:39.696  1488  1785 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-21 07:32:39.696  1488  1785 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-21 07:32:39.696  1488  1785 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-21 07:32:39.696  1488  1785 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-21 07:32:39.696  1488  1785 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
,03-21 07:32:39.706  1488  1785 D TP/MmsSmsProvider: delete threadId: 9223372036854775806
03-21 07:32:39.706  1488  1785 D TP/MmsSmsProvider: need read changed broadcast:false
,03-21 07:32:39.716   284   511 D WVMDrmPlugIn: WVMDrmPlugin::onInitialize : 463
,03-21 07:32:39.716   284   511 D WVMDrmPlugIn: WVMDrmPlugin::onSetOnInfoListener : add 463
,03-21 07:32:39.716  3153  3153 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,03-21 07:32:39.716  3153  3153 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,03-21 07:32:39.716  3153  3315 W PluginManager: THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 70ms. Plugin should use CordovaInterface.getThreadPool().
,03-21 07:32:39.726  1488  1500 I art     : Explicit concurrent mark sweep GC freed 34833(2MB) AllocSpace objects, 5(80KB) LOS objects, 45% free, 4MB/8MB, paused 976us total 193.504ms
,03-21 07:32:39.726  1019  1043 W libprocessgroup: failed to open /acct/uid_10121/pid_2930/cgroup.procs: No such file or directory
03-21 07:32:39.726  1019  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_2896/cgroup.procs: No such file or directory
,03-21 07:32:39.736  1238  3472 D MediaScanner: Prescan. DB items number : 138 DB_FILES_NUMBER_CACHING_LIMITATION : 7000  Caching mode : true
,03-21 07:32:39.736  1019  1032 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1019  pkgName : ACTIVITY_RESUME_BOOSTER@7
,03-21 07:32:39.746  1019  1032 W ActivityManager: mDVFSHelper.acquire()
,03-21 07:32:39.746  2423  3543 D Mms/Conversation: deleteTempConversation(),deleted=0,
,03-21 07:32:39.746  3495  3495 D [0]UMC:DeviceInfo: USA==US==
,03-21 07:32:39.756  1019  1032 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
,03-21 07:32:39.756  1019  1032 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
03-21 07:32:39.756  1019  1032 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,03-21 07:32:39.756  3519  3519 E UpdateRequestReceiver: ignoring update request
,03-21 07:32:39.766  1019  1630 W ActivityManager: userId = 0, bbcId = -10000
,03-21 07:32:39.766  1019  1630 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-21 07:32:39.766  1019  1630 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,03-21 07:32:39.776  1507  1507 D Launcher: onRestart, Launcher: 81501900
,03-21 07:32:39.776  1019  1019 I TimaServiceEventReceiver: TimaServiceEventReceiver : onReceive
,03-21 07:32:39.776  1019  3562 I DrmEventService: action event :android.intent.action.BOOT_COMPLETED
,03-21 07:32:39.776  1507  1507 D Launcher: onStart, Launcher: 81501900
,03-21 07:32:39.776  1507  1507 D Launcher.HomeView: onStart
,03-21 07:32:39.786  1507  1507 D Launcher: onResume, Launcher: 81501900
,03-21 07:32:39.786  1019  1805 D SettingsProvider: name = kids_home_mode
,03-21 07:32:39.786  1019  1805 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-21 07:32:39.786  1019  1805 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-21 07:32:39.786  1019  1805 D SettingsProvider: selectionArgs: false
,03-21 07:32:39.786  1019  1805 D SettingsProvider: selectionArgs: 10006
03-21 07:32:39.786  1019  1805 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,03-21 07:32:39.786  1019  1805 D SettingsProvider: ret = -1
03-21 07:32:39.786  1337  1337 I WifiCredService: onCreate
,03-21 07:32:39.786  1507  1507 D Launcher.HomeView: onResume
,03-21 07:32:39.786  1019  1019 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
03-21 07:32:39.786  1019  1019 D SensorService: [SO] activate (ident=0xb8591098, enabled=0)
03-21 07:32:39.786  1019  1019 I Sensors : AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,03-21 07:32:39.796  1488  1901 D TP/SmsProvider: query,matched:51, calling pid = 2423
,03-21 07:32:39.796  1488  1901 D TP/SmsProvider: match 51:Elapsed time : 1.016 ms
,03-21 07:32:39.806  3519  3519 E UpdateRequestReceiver: ignoring update request
,03-21 07:32:39.806  1507  1507 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,03-21 07:32:39.816  1019  1019 D SensorManager: unregisterListener ::   
,03-21 07:32:39.816  1019  1019 I Sensors : AccelerometerSensor(0) setDelay : 200000000(ns)
,03-21 07:32:39.826  1019  1019 D SensorService: [SO] changed settle time [0]
03-21 07:32:39.826  1019  1019 D SensorService: [SO] setDelay [200000000]
03-21 07:32:39.826  1019  1019 D SensorService: [SO] activate (ident=0xb8591098, enabled=1)
03-21 07:32:39.826  1019  1019 D SensorService: [SO] AR_init
03-21 07:32:39.826  1019  1019 I Sensors : AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,03-21 07:32:39.826  3519  3519 E UpdateRequestReceiver: ignoring update request
,03-21 07:32:39.826  1019  1019 D SensorManager: registerListener :: 1600221811, Screen Orientation Sensor, 200000, 0,  
,03-21 07:32:39.836  1337  1337 D WifiTimerReceiver: action: android.intent.action.BOOT_COMPLETED
03-21 07:32:39.836  1337  1337 D WifiTimerReceiver: extra: Bundle[mParcelledData.dataSize=84]
03-21 07:32:39.836  1337  1337 D MY_TAG  : Action boot completed received
,03-21 07:32:39.836  1488  1500 D SmsProvider: Update uri=content://sms/outbox, match=8
,03-21 07:32:39.836  1507  1507 D MenuAppsGridFragment: onResume
,03-21 07:32:39.846  2423  3518 D Mms/MessagingNotification: isBlockingModeEnabled() = false, Zen mode = 0
,03-21 07:32:39.846  1019  1571 D ActivityManager: handle home activity for 0
03-21 07:32:39.846  1019  1571 I WallpaperManagerService: switchPersonaWallpaper is called for personaId-0
03-21 07:32:39.846  1019  1571 D KnoxTimeoutHandler: post home show event for user 0
03-21 07:32:39.846  1019  1571 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
03-21 07:32:39.846  1019  1571 D KnoxTimeoutHandler: postActiveUserChange for user 0
03-21 07:32:39.846  1019  1571 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,03-21 07:32:39.846   284   284 I ANDROID_DRM_FRWORKS_DrmManager: DrmManager::acquireDrmInfo::No decrypt session open not need to handle TV out or HDMI
,03-21 07:32:39.846  1019  1019 D WallpaperManagerService:  force update = false; persona id = 0; current user =0; current persona = 0
03-21 07:32:39.846  1019  1019 D KnoxTimeoutHandler: handleHomeShow for 0 and current 0
03-21 07:32:39.846  1019  1019 D PersonaManagerService: getPersonasForUser(): returning null!
03-21 07:32:39.846  1019  1019 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,03-21 07:32:39.846  3519  3519 E UpdateRequestReceiver: ignoring update request
,03-21 07:32:39.856   259   259 I SurfaceFlinger: id=13 createSurf (540x960),1 flag=4, Mauncher
,03-21 07:32:39.856  1488  1500 D TP/MmsSmsProvider: need read changed broadcast:false
,03-21 07:32:39.856  1337  1337 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,03-21 07:32:39.856  3495  3495 D USER_AGENT: UMC/1.3.23 (SM-A300FU) SAFE-5.3 KNOX-2.3 en_US
,03-21 07:32:39.856  1019  1047 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,03-21 07:32:39.866  3495  3495 D [0]UMC:AdminManager: init - start
,03-21 07:32:39.866  1488  1488 E CscReceiver: onReceive android.intent.action.BOOT_COMPLETED
,03-21 07:32:39.866  3495  3495 D [0]UMC:AdminManager: loadAdmins
,03-21 07:32:39.876  1019  1047 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,03-21 07:32:39.876  1019  1130 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
,03-21 07:32:39.876  1019  1130 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
03-21 07:32:39.876  1019  1130 E WifiNative-wlan0: invaild command id : 215
,03-21 07:32:39.896   258   519 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/flipboard.app/files/cache/
03-21 07:32:39.896   258   519 W Vold    : Returning OperationFailed - no handler for errno 0
,03-21 07:32:39.906  3495  3495 D [0]UMC:AdminManager: init - end
,03-21 07:32:39.906  3495  3495 D GSLBManager: migrateStoredUrlFromOldPref
,03-21 07:32:39.906  1019  1564 D InputDispatcher: Focus entered window: 1507
,03-21 07:32:39.906  3488  3488 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/flipboard.app/files/cache
,03-21 07:32:39.906  1507  1507 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,03-21 07:32:39.916  1019  1049 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-21 07:32:39.916  1019  1049 D PointerIcon: setMouseCustomIcon IconType is same.101
,03-21 07:32:39.916  3519  3519 E UpdateRequestReceiver: ignoring update request
,03-21 07:32:39.926  2423  3543 D Mms/SmsReceiverService: moveOutboxMessagesToFailedBox messageCount: 0
03-21 07:32:39.926  2423  3543 D Mms/SmsReceiverService: handle boot completed, sendFirstQueuedMessage()
03-21 07:32:39.926  2423  3543 D Mms/SmsReceiverService: [SIM-1]sendFirstQueuedMessage()
,03-21 07:32:39.936  1507  1507 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0,
,03-21 07:32:39.936  1337  1337 D NearbySettings: MountReceiver.onReceive - ACTION: android.intent.action.BOOT_COMPLETED
03-21 07:32:39.936  1019  1561 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false,
03-21 07:32:39.936  1019  1571 D SettingsProvider: name = com.samsung.android.nearby.mediaserver.NEARBY_SERVER_STARTED
03-21 07:32:39.936  3559  3559 D AndroidRuntime: 
03-21 07:32:39.936  3559  3559 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<,
03-21 07:32:39.936  1337  2219 V NearbySettings: MountReceiver.mPrefHandler - 7002
,03-21 07:32:39.946  1181  1181 I StatusBar: Icon Only
,03-21 07:32:39.946  1181  1181 D PanelView: There is/are notification(s) 
03-21 07:32:39.946  3559  3559 D AndroidRuntime: CheckJNI is OFF
03-21 07:32:39.946  3559  3559 D AndroidRuntime: readGMSProperty: start
,03-21 07:32:39.946  3559  3559 D AndroidRuntime: readGMSProperty: already setted!!
03-21 07:32:39.946  3559  3559 D AndroidRuntime: propertySet: couldn't set property (it is from app)
03-21 07:32:39.946  3559  3559 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
,03-21 07:32:39.946  3559  3559 D AndroidRuntime: readGMSProperty: end
03-21 07:32:39.946  3559  3559 D AndroidRuntime: addProductProperty: start
,03-21 07:32:39.946  1019  1630 W ActivityManager: userId = 0, bbcId = -10000
03-21 07:32:39.946  1019  1630 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-21 07:32:39.946  1019  1630 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
,03-21 07:32:39.956  1019  3592 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-21 07:32:39.956  3153  3153 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,03-21 07:32:39.966  1488  1488 D CscUpdateService: onStart,
,03-21 07:32:39.966  1019  1502 E ActivityManager: checkUser: useridlist=null, currentuser=0,
03-21 07:32:39.966  1488  1488 E CscUpdateService: costomer file is exists : it has been preconfiged.
03-21 07:32:39.966  1019  1502 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 07:32:39.966  1488  1488 I CscUpdateService: set_CSC_version
03-21 07:32:39.966  1019  1502 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:39.966  1488  1488 E CscParser: update(): xml file exist,
03-21 07:32:39.966  1019  1502 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 07:32:39.976  1859  1859 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false,
,03-21 07:32:39.996   258   519 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/flipboard.app/files/cache/
03-21 07:32:39.996   258   519 W Vold    : Returning OperationFailed - no handler for errno 0
,03-21 07:32:39.996  3598  3598 E Zygote  : MountEmulatedStorage()
,03-21 07:32:40.006  3598  3598 E Zygote  : v2
03-21 07:32:40.006  3598  3598 I libpersona: KNOX_SDCARD checking this for 10088
03-21 07:32:40.006  3598  3598 I libpersona: KNOX_SDCARD not a persona
03-21 07:32:40.006  3488  3578 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/flipboard.app/files/cache
,03-21 07:32:40.006  3598  3598 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-21 07:32:40.006  1507  1507 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@35ba7ed1 time:40154
,03-21 07:32:40.016  3598  3598 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-21 07:32:40.016  1019  1049 D PersonaManager: isKioskContainerExistOnDevice
03-21 07:32:40.016  3598  3598 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,03-21 07:32:40.016  1019  1502 I ActivityManager: Start proc com.dropbox.android for broadcast com.dropbox.android/.service.WakeupReceiver: pid=3598 uid=10088 gids={50088, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-21 07:32:40.016  1019  1502 I ActivityManager: Killing 2760:com.policydm/1000 (adj 15): empty #31
,03-21 07:32:40.026  1019  1041 D SensorService: [SO] Reset Rotation Old [100], Init [1]
,03-21 07:32:40.026  1019  1502 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:40.026  1019  1502 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:40.026  1019  1502 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:40.026  1019  1502 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 07:32:40.056  3598  3598 D TimaKeyStoreProvider: TimaSignature is unavailable
03-21 07:32:40.056  3598  3598 D ActivityThread: Added TimaKeyStore provider
,03-21 07:32:40.056   290   290 E SMD     : DCD OFF,
03-21 07:32:40.056  3621  3621 I libpersona: KNOX_SDCARD checking this for 10002
03-21 07:32:40.056  3621  3621 E Zygote  : MountEmulatedStorage()
03-21 07:32:40.056  3621  3621 I libpersona: KNOX_SDCARD not a persona
03-21 07:32:40.056  3621  3621 E Zygote  : v2
,03-21 07:32:40.066  1019  1502 I ActivityManager: Start proc com.samsung.android.providers.context for broadcast com.samsung.android.providers.context/.ContextSystemBroadcastReceiver: pid=3621 uid=10002 gids={50002, 9997, 3002, 3003, 1028} abi=armeabi-v7a,
,03-21 07:32:40.076  3621  3621 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
03-21 07:32:40.076  1019  1499 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:40.076  1019  1499 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:40.076  1019  1499 E ActivityManager: checkUser: useridlist=null, currentuser=0,
,03-21 07:32:40.076  1019  1499 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 07:32:40.076  3621  3621 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,03-21 07:32:40.096  3621  3621 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-21 07:32:40.096  3628  3628 E Zygote  : MountEmulatedStorage(),
03-21 07:32:40.096  3628  3628 E Zygote  : v2,
03-21 07:32:40.096  3628  3628 I libpersona: KNOX_SDCARD checking this for 10068
,03-21 07:32:40.096  3628  3628 I libpersona: KNOX_SDCARD not a persona
,03-21 07:32:40.106  1019  1499 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=3628 uid=10068 gids={50068, 9997} abi=armeabi-v7a,
,03-21 07:32:40.106  3628  3628 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,03-21 07:32:40.106  1019  1283 I art     : Explicit concurrent mark sweep GC freed 48639(2MB) AllocSpace objects, 44(2MB) LOS objects, 33% free, 24MB/36MB, paused 2.926ms total 304.637ms,
,03-21 07:32:40.116  3628  3628 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
03-21 07:32:40.116  3488  3488 I System.out: Reading bundled version for config.json
,03-21 07:32:40.116  3628  3628 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL,
03-21 07:32:40.116  1019  1049 I ActivityManager: Displayed Component not be shown by security: +370ms
03-21 07:32:40.116  1181  1181 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-21 07:32:40.126  1488  1901 D TP/SmsProvider: query,matched:26, calling pid = 2423
,03-21 07:32:40.136  1488  1901 D TP/SmsProvider: match 26:Elapsed time : 3.118 ms
,03-21 07:32:40.136  3559  3559 E AffinityControl: AffinityControl: registerfunction enter,
,03-21 07:32:40.146  3495  3495 D GSLBManager: migrateStoredUrlFromOldPref : Migration Not Needed,
,03-21 07:32:40.146  3621  3621 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-21 07:32:40.146  3621  3621 D ActivityThread: Added TimaKeyStore provider
03-21 07:32:40.146  3495  3495 D [0]UMC:UMCAdmin: deactivateUMCAdminIfNotRequired : -1
03-21 07:32:40.146  3495  3495 E [0]UMC:Utils: Admin not found in package com.samsung.knoxpb.mdm
,03-21 07:32:40.146  3495  3495 E [0]UMC:Utils: Admin not found in package com.sec.enterprise.knox.cloudmdm.smdms.agent.myknox
03-21 07:32:40.146  3495  3495 D [0]UMC:UMCAdmin: deactivateUMCAdmin : -1
03-21 07:32:40.146  3495  3495 D [0]UMC:UMCAdmin: isContainer : 0,
03-21 07:32:40.146  1337  1337 I NearbySettings: MountReceiver.onReceive - Path: (systemPath)/storage/emulated/0/Download, (internalPath)/storage/emulated/0/Download, (externalPath)/storage/extSdCard/Download
03-21 07:32:40.146  1337  1337 I NearbySettings: MountReceiver.onReceive - Internal Path
,03-21 07:32:40.156  1488  1488 I CscUtil : isWifiOnly = false
,03-21 07:32:40.156  1488  1488 I System.out: HandDataNode = null
03-21 07:32:40.156  1488  1488 I CscUpdateService: PATH_CSCNAME =CustomerDataSet.CSCName
,03-21 07:32:40.156  1488  1488 I CscUpdateService: This is normal boot : CSC not updated
,03-21 07:32:40.166  3628  3628 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-21 07:32:40.166  3027  3048 W art     : Suspending all threads took: 18.600ms
03-21 07:32:40.166  3628  3628 D ActivityThread: Added TimaKeyStore provider
,03-21 07:32:40.166  3559  3559 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,03-21 07:32:40.176  1488  1488 I CscUpdateService: same CSC Version
03-21 07:32:40.176  1488  1488 D CscUtil : Set Build Fingerprint to samsung/a3ultexx/a3ulte:5.0.2/LRX22G/A300FUXXU1BOEC:user/release-keys
,03-21 07:32:40.176  1488  3648 E CscParser: update(): xml file exist
,03-21 07:32:40.186  1238  3472 V MediaScanner: processDirectory :  /system/media
,03-21 07:32:40.186  1488  3648 D CscGPS  : CSCGPS.updateParameters
03-21 07:32:40.186  1488  3648 D CscGPS  : supl host : null
03-21 07:32:40.186  1488  3648 D CscGPS  : SUPL Host is null or invalid
03-21 07:32:40.186  1488  3648 D CscGPS  : supl_ver : null
03-21 07:32:40.186  1488  3648 D CscGPS  : SUPL Ver is null or invalid
03-21 07:32:40.186  1488  3648 D CscGPS  : supl port : null
03-21 07:32:40.186  1488  3648 D CscGPS  : SUPL PORT is null or invalid
03-21 07:32:40.186  1488  3648 D CscGPS  : LPP : null
03-21 07:32:40.186  1488  3648 D CscGPS  : LPP is null or invalid
03-21 07:32:40.186  1488  3648 D CscGPS  : CSC don't have any AGPS value.
,03-21 07:32:40.196  2423  3543 D Mms/SmsReceiver: unregisterForServiceStateChanges, already unregistered
03-21 07:32:40.196  2423  3543 D Mms/MessagingNotification: sDisableVibrateForCamera = false
03-21 07:32:40.196  2423  3543 D Mms/TelephonyPermission: isDefault true
,03-21 07:32:40.206  1019  1630 D SettingsProvider: name = personal_mode_enabled
,03-21 07:32:40.216  1019  1531 D PackageManager: START PACKAGE DELETE: observer{135662194}
03-21 07:32:40.216  1019  1531 D PackageManager: pkg{<packageName>}
03-21 07:32:40.216  1019  1531 D PackageManager: user{0}
03-21 07:32:40.216  1019  1531 D PackageManager: caller{2000}
03-21 07:32:40.216  1019  1531 D PackageManager: flags{2}
03-21 07:32:40.216  1019  1531 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
03-21 07:32:40.216  1019  1531 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
03-21 07:32:40.216  1019  1531 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
03-21 07:32:40.216  1019  1531 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
03-21 07:32:40.216  1019  1531 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,03-21 07:32:40.216  1019  1809 D EnterpriseDeviceManagerService: isManagedProfileUser(): userId = 0
,03-21 07:32:40.216  1019  1059 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
03-21 07:32:40.216  1019  1059 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
03-21 07:32:40.216  1019  1059 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
03-21 07:32:40.216  1019  1059 D ApplicationPolicy: getApplicationUninstallationEnabled
03-21 07:32:40.216  1019  1059 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,03-21 07:32:40.216  1488  1785 D TP/MmsProvider: Query uri=content://mms, match=0, calling pid = 2423
,03-21 07:32:40.226  1019  1041 D SensorService: [SO] currT = 40371092000, prevT = 39901054000, diff = 470038000, [-0.460 0.211 9.883]
,03-21 07:32:40.226  1019  1041 D SensorService: [SO] -0.460 0.211 9.883
03-21 07:32:40.226  1019  1041 D SensorService: [SO] [100 -> 255]
,03-21 07:32:40.226  3628  3628 D BadgeProvider: onCreate
03-21 07:32:40.226  3628  3628 D BadgeProvider: DatabaseHelper
,03-21 07:32:40.236  3495  3495 E [0]UMC:UMCAdmin: No active admin owned by uid 10155
03-21 07:32:40.236  3495  3495 D [0]UMC:UMCAdmin: isContainer : 0
,03-21 07:32:40.236  3495  3495 D [0]UMC:UMCAdmin: deactivateUMCAdmin - UMC App Admin deactivated
03-21 07:32:40.236  1019  1059 D PackageManager: !@killApplicatoin: 10167, uninstall pkg
03-21 07:32:40.236  1019  1044 I ActivityManager: Force stopping com.test.thalitest appid=10167 user=-1: uninstall pkg
03-21 07:32:40.236  1019  1044 I ActivityManager: Killing 3153:com.test.thalitest/u0a167 (adj 1): stop com.test.thalitest cause uninstall pkg
,03-21 07:32:40.246  3495  3495 D [0]UMC:CoreReceiver: Intent : android.intent.action.BOOT_COMPLETED
03-21 07:32:40.246  3495  3495 D [0]UMC:CoreReceiver:  check PreETag 
,03-21 07:32:40.256  1019  1044 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1019  tag : ACTIVITY_RESUME_BOOSTER@7
,03-21 07:32:40.266  1019  1044 W ActivityManager: mDVFSHelper.release()
,03-21 07:32:40.266  1019  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_2760/cgroup.procs: No such file or directory
,03-21 07:32:40.266  1019  1044 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1019  pkgName : ACTIVITY_RESUME_BOOSTER@11
,03-21 07:32:40.266  1488  1488 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
03-21 07:32:40.266  1488  1488 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
03-21 07:32:40.266  1488  1488 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,03-21 07:32:40.266  1488  1488 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-21 07:32:40.266  1488  1488 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-21 07:32:40.266  1488  1488 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,03-21 07:32:40.296  3488  3488 I System.out: Reading bundled version for services.json
,03-21 07:32:40.316  3495  3495 D [0]UMC:ByodSetupStarter: Container ID : 0
,03-21 07:32:40.336  3488  3488 I System.out: Reading bundled version for dynamicStrings.json
,03-21 07:32:40.336  1238  3472 V MediaScanner:  prescan time: 715ms (DB items: 138)
,03-21 07:32:40.336  1238  3472 V MediaScanner:     scan time: 219ms (Caching mode: true), (makeEntry time: 44ms ~20%),  (parsing time: 0ms ~0%),  (bitmapDecoding time: 0ms ~0%), (exifExtracting time : 0ms ~0%), (sefExtracting time : 0ms ~0%), (bulkInserter time : 0ms ~0%)
03-21 07:32:40.336  1238  3472 V MediaScanner: postscan time: 0ms (bulkDeleter : 0), (delete DeadThumbnail time : 0ms)
03-21 07:32:40.336  1238  3472 V MediaScanner:    total time: 934ms
03-21 07:32:40.346  1238  3472 V MediaScanner: checked files: 130  directories : 6  (I: 0, U: 0)
,03-21 07:32:40.346  1238  3472 D MediaScanner: checkDefaultSounds
03-21 07:32:40.346  1238  3472 D MediaScanner: system alarm_alert  : Vwiurug_etwofi5wgg
,03-21 07:32:40.356  1019  1571 I WindowState: WIN DEATH: Window{161370be u0 com.test.thalitest/com.test.thalitest.MainActivity EXITING}
,03-21 07:32:40.366  1019  1059 W PackageSettings: Skipping PackageSetting{3a3115e com.example.hello/10168} due to missing metadata
,03-21 07:32:40.376  3488  3488 E flip    : [ERROR:4] Removing local copy of remote dynamicStrings.json: exception=java.io.IOException: invalid JSON, unexpected EOF in string
03-21 07:32:40.376  3488  3488 E flip    :     flipboard.json.JSONParserBase.b(JSONParserBase.java:549)
03-21 07:32:40.376  3488  3488 E flip    :     flipboard.json.JSONParserBase.a(JSONParserBase.java:338)
03-21 07:32:40.376  3488  3488 E flip    :     flipboard.json.JSONParser.a(JSONParser.java:284)
03-21 07:32:40.376  3488  3488 E flip    :     flipboard.json.JSONParserBase.R(JSONParserBase.java:618)
03-21 07:32:40.376  3488  3488 E flip    :     flipboard.json.JSONParserBase.Q(JSONParserBase.java:559)
03-21 07:32:40.376  3488  3488 E flip    :     flipboard.service.FlipboardManager$29.a(FlipboardManager.java:2502)
03-21 07:32:40.376  3488  3488 E flip    :     flipboard.service.FlipboardManager.a(FlipboardManager.java:1589)
03-21 07:32:40.376  3488  3488 E flip    :     flipboard.service.FlipboardManager.<init>(FlipboardManager.java:781)
03-21 07:32:40.376  3488  3488 E flip    :     flipboard.app.FlipboardApplication.onCreate(FlipboardApplication.java:212)
03-21 07:32:40.376  3488  3488 E flip    :     ...
,03-21 07:32:40.386  3488  3488 I System.out: Parsed section Cover Stories, private: false
,03-21 07:32:40.426  3628  3650 D BadgeProvider: query, [selection] : package='com.android.mms' AND class='com.android.mms.ui.ConversationComposer' AND extraData='base_extra_badge'
,03-21 07:32:40.426  3495  3495 V [0]UMC:Utils: checkAppScreen() : com.sec.android.app.launcher
03-21 07:32:40.426  3495  3495 I [0]UMC:Core: shutdown
,03-21 07:32:40.436  3495  3495 I art     : System.exit called, status: 0
03-21 07:32:40.436  1488  1901 D TP/MmsSmsProvider: query,matched:200, calling pid = 2423
,03-21 07:32:40.436  3495  3495 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,03-21 07:32:40.436  1488  1901 D TP/MmsSmsProvider: match 200:Elapsed time : 1.469 ms
,03-21 07:32:40.436  1238  3472 D MediaScanner: OK. alarm_alert is already exist in setting DB.
,03-21 07:32:40.436  1238  3472 D MediaScanner: system notification_sound  : K_Oprkltf5wgg
,03-21 07:32:40.436  1337  1337 I SmartcardBootCompleteReceiver: SmartcardBootCompleteReceiver - onReceive() 
,03-21 07:32:40.436  1337  1337 I SmartcardBootCompleteReceiver: Received intent with action - android.intent.action.BOOT_COMPLETED
,03-21 07:32:40.446  1238  3472 D MediaScanner: OK. notification_sound is already exist in setting DB.
,03-21 07:32:40.446  1019  1059 I ActivityManager: Force stopping com.test.thalitest appid=10167 user=0: pkg removed
,03-21 07:32:40.456  1238  3472 D MediaScanner: system ringtone  : Wmfi_lpf_pwirywu5wgg
,03-21 07:32:40.456  1507  1507 D Launcher.Model: reloadBadges entered.
,03-21 07:32:40.456  3628  3650 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/2
03-21 07:32:40.456  3628  3650 D BadgeProvider: sendNotify, [notify] : null
03-21 07:32:40.456  3628  3650 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/2
03-21 07:32:40.456  3628  3650 D BadgeProvider: update, [BadgeCount] : badgecount=0
03-21 07:32:40.456  3628  3650 D BadgeProvider: update, [UpdateCount] : 1
,03-21 07:32:40.456  1238  3472 D MediaScanner: OK. ringtone is already exist in setting DB.
,03-21 07:32:40.456   259  1156 I SurfaceFlinger: id=12 Removed NainActivit (7/8)
03-21 07:32:40.456   259   715 I SurfaceFlinger: id=12 Removed NainActivit (-2/8)
,03-21 07:32:40.486  1019  1059 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,03-21 07:32:40.496  1019  1059 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,03-21 07:32:40.506  1337  1337 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 android.content.ContextWrapper.sendBroadcast:391 com.android.settings.SmartcardBootCompleteReceiver.onReceive:43 android.app.ActivityThread.handleReceiver:3125 
,03-21 07:32:40.506  1337  1337 I SmartcardBootCompleteReceiver: Broadcast sent with current lockscreen type
,03-21 07:32:40.506  1019  1049 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{1b6fefd6 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t10} time:40654
,03-21 07:32:40.506  1238  3472 D MediaScannerService: !@done scanning volume internal
,03-21 07:32:40.516  1019  1283 W ActivityManager: userId = 0, bbcId = -10000
03-21 07:32:40.516  1019  1283 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-21 07:32:40.516  1019  1283 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.samsung.android.providers.context
,03-21 07:32:40.526  2423  3518 D Mms/MessagingNotification: setBadgeCount(), count=0
,03-21 07:32:40.536  2698  2698 I art     : Explicit concurrent mark sweep GC freed 18388(1004KB) AllocSpace objects, 2(32KB) LOS objects, 50% free, 3MB/7MB, paused 742us total 35.148ms
,03-21 07:32:40.536  2423  3518 D Mms/MessagingNotification: remove alarm
,03-21 07:32:40.556  1019  1019 D RCPManagerService: PackageReceiver onReceive()
03-21 07:32:40.556  1019  1019 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,03-21 07:32:40.556  1019  1019 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
03-21 07:32:40.556  1859  1859 E SamsungIME: mOCRHelper is null
,03-21 07:32:40.556  1999  2204 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,03-21 07:32:40.566  1488  1488 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-21 07:32:40.566  3112  3112 D FactoryTestApp: [DummyFtClient$mBroadcastReceiver](3112) action= = android.intent.action.MEDIA_SCANNER_FINISHED
,03-21 07:32:40.566  1019  1499 I ActivityManager: Process com.sec.enterprise.knox.cloudmdm.smdms (pid 3495)(adj 0) has died(64,650)
,03-21 07:32:40.576  3112  3112 D FactoryTestApp: [DummyFtClient$mBroadcastReceiver](3112) ACTION_MEDIA_SCANNER_FINISHED = /system/media
03-21 07:32:40.576  3112  3112 D FactoryTestApp: [DummyFtClient$mBroadcastReceiver](3112) ACTION_MEDIA_SCANNER_FINISHED = Ignored
,03-21 07:32:40.576  1019  1805 W ActivityManager: userId = 0, bbcId = -10000
,03-21 07:32:40.576  1019  1805 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-21 07:32:40.576  1019  1805 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.samsung.android.providers.context
,03-21 07:32:40.586  1019  1100 I InputReader: Reconfiguring input devices.  changes=0x00000010
,03-21 07:32:40.606  1238  3472 D MediaScannerService: !@start scanning volume external: [/storage/emulated/0, /storage/extSdCard, /storage/Private]
,03-21 07:32:40.606  1488  1500 D TP/SmsProvider: query,matched:0, calling pid = 2423
,03-21 07:32:40.616  1488  1500 D TP/SmsProvider: match 0:Elapsed time : 4.875 ms
,03-21 07:32:40.616  1488  1785 D TP/SmsProvider: query,matched:0, calling pid = 2423
,03-21 07:32:40.616  1488  1785 D TP/SmsProvider: match 0:Elapsed time : 1.476 ms
,03-21 07:32:40.616  1019  1283 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 07:32:40.626  1019  1283 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:40.626  1019  1283 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:40.626  1019  1283 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 07:32:40.626  1019  1127 V NetworkStats: removeUidsLocked() for UIDs [10167]
03-21 07:32:40.626  1019  1127 D NtpTrustedTime: currentTimeMillis() cache hit
03-21 07:32:40.626  1019  1127 V NetworkStats: performPollLocked(flags=0x3)
,03-21 07:32:40.636  1019  1127 D NetworkStatsFactory: UpdateStatsForKnox updated,
,03-21 07:32:40.636  1019  1127 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,03-21 07:32:40.636  3669  3669 E Zygote  : MountEmulatedStorage()
03-21 07:32:40.636  3669  3669 E Zygote  : v2
03-21 07:32:40.636  1019  1127 V NetworkStats: performPollLocked() took 12ms
03-21 07:32:40.636  1019  1127 D NtpTrustedTime: currentTimeMillis() cache hit
03-21 07:32:40.636  3669  3669 I libpersona: KNOX_SDCARD checking this for 1000
03-21 07:32:40.636  3669  3669 I libpersona: KNOX_SDCARD not a persona
,03-21 07:32:40.636  3669  3669 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-21 07:32:40.636  3669  3669 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
03-21 07:32:40.646  1019  1283 I ActivityManager: Start proc com.sec.dsm.system for broadcast com.sec.dsm.system/.DSMReceiver: pid=3669 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,03-21 07:32:40.646  3669  3669 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-21 07:32:40.646  1019  1395 I ActivityManager: Killing 1254:com.android.defcontainer/u0a3 (adj 15): empty #31
,03-21 07:32:40.666   322   322 I art     : Explicit concurrent mark sweep GC freed 8713(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 603us total 23.268ms
,03-21 07:32:40.666  1337  1337 D [SBeam] : SBeamEnabler.initPreferenceForSbeam : 0
,03-21 07:32:40.676  3669  3669 D TimaKeyStoreProvider: TimaSignature is unavailable
03-21 07:32:40.676  3669  3669 D ActivityThread: Added TimaKeyStore provider
,03-21 07:32:40.686   322   322 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 576us total 19.504ms,
,03-21 07:32:40.686  1019  1128 D NtpTrustedTime: currentTimeMillis() cache hit,
03-21 07:32:40.686  1019  1128 D NtpTrustedTime: currentTimeMillis() cache hit
,03-21 07:32:40.706   322   322 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 586us total 21.962ms
,03-21 07:32:40.716  1019  1019 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,03-21 07:32:40.716  1019  1019 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
03-21 07:32:40.716  1019  1019 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
03-21 07:32:40.716  1019  1019 V EnterpriseBillingPolicy: uID is 10167
03-21 07:32:40.716  1019  1019 V EnterpriseBillingPolicy: Removed Packageuid is0
03-21 07:32:40.716  1019  1019 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,03-21 07:32:40.716  1019  1019 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
03-21 07:32:40.716  1019  1019 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
,03-21 07:32:40.716  1019  1019 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
03-21 07:32:40.716  1019  1019 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
03-21 07:32:40.716  1812  1812 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
03-21 07:32:40.716  1019  1019 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
03-21 07:32:40.716  1812  1812 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
03-21 07:32:40.716  1812  1812 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,03-21 07:32:40.726  1019  1043 D EnterpriseDeviceManagerService: Package has changed for user 0
03-21 07:32:40.726  1019  1043 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
03-21 07:32:40.726  1019  1043 W TextServicesManagerService: no available spell checker services found
,03-21 07:32:40.726  2423  3518 D Mms/MessagingNotification: [end]    nonBlockingUpdateMessageIndicator() consume time = 1198.821041
,03-21 07:32:40.746  1812  1812 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,03-21 07:32:40.746  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-21 07:32:40.746  1238  3472 D MediaProvider: savePlaylistTableInBulkDeleter started
,03-21 07:32:40.746  1238  3472 D MediaProvider: savePlaylistTableInBulkDeleter started - audio_playlists_map_cache existed
,03-21 07:32:40.746  1812  1812 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,03-21 07:32:40.756  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-21 07:32:40.756  1812  1812 D daemonapp: [MSC_Daemon]>>> WDSM:54 [0:0] Act : androidintentactionBOOT_COMPLETED, run:true
,03-21 07:32:40.756  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-21 07:32:40.756  1019  1031 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
,03-21 07:32:40.756  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-21 07:32:40.766  1019  1031 D SecContentProvider2: mCursor = null
,03-21 07:32:40.776  2423  3666 D Mms/MessagingNotification: updateAllHistoryAsRead()
,03-21 07:32:40.776  1812  1812 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
03-21 07:32:40.776  1812  1812 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
03-21 07:32:40.776  1812  1812 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
03-21 07:32:40.776  1812  1812 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
03-21 07:32:40.776  1812  1812 D daemonapp: [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
,03-21 07:32:40.776  1812  1812 D daemonapp: [MSC_Daemon]>>> WDSM:97 [0:0] ABOOTCOPLD
,03-21 07:32:40.776  1337  1337 I SettingSearch/SearchIntentReceiver: action : android.intent.action.BOOT_COMPLETED
03-21 07:32:40.776  1337  1337 I SettingSearch/SearchIntentReceiver: search setting db init!!
,03-21 07:32:40.776  1238  3472 D MediaProvider: savePlaylistTableInBulkDeleter started - audio_playlists_map_cache is empty
03-21 07:32:40.776  1019  1805 W ActivityManager: userId = 0, bbcId = -10000
03-21 07:32:40.776  1019  1805 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-21 07:32:40.776  1019  1805 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,03-21 07:32:40.786  1337  1337 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver.restoredb:41 com.android.settings.settingssearch.SettingsSearchIntentReceiver.onReceive:61 
,03-21 07:32:40.786  1019  1019 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,03-21 07:32:40.796  1019  1019 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
,03-21 07:32:40.796  1019  1019 V EnterpriseBillingPolicy: uID is 10167
,03-21 07:32:40.796  1019  1163 D TaskPersister: removeObsoleteFile: deleting file=11_task.xml
,03-21 07:32:40.796  1019  1019 V EnterpriseBillingPolicy: Removed Packageuid is0
03-21 07:32:40.796  1019  3306 D SSRM:aZ : MSG_TYPE_APP_REMOVED::
,03-21 07:32:40.796  1019  1019 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,03-21 07:32:40.796  1019  1163 D TaskPersister: removeObsoleteFile: deleting file=11_task_thumbnail.png
,03-21 07:32:40.806  1019  1032 D SettingsProvider: name = aw_daemon_service_key_version_check
03-21 07:32:40.806  1019  1032 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-21 07:32:40.806  1019  1032 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-21 07:32:40.806  1019  1032 D SettingsProvider: selectionArgs: false
03-21 07:32:40.806  1019  1032 D SettingsProvider: selectionArgs: 10157
03-21 07:32:40.806  1468  1468 D RegisteredServicesCache: empty dynamic service
,03-21 07:32:40.806  1019  1032 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-21 07:32:40.806  1019  1032 D SettingsProvider: ret = -1
,03-21 07:32:40.816  1238  3472 D MediaProvider: savePlaylistTableInBulkDeleter finished
03-21 07:32:40.816  1238  3472 D MediaProvider: savePlaylistTableInBulkDeleter started
,03-21 07:32:40.816  1019  1019 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
,03-21 07:32:40.816  1019  1019 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
,03-21 07:32:40.816  1019  1019 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
,03-21 07:32:40.816  1019  1019 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,03-21 07:32:40.816  1337  3685 I SettingSearch/SearchIntentReceiver: BOOT_COMPLETED call InitSerachDBThread thread start!
,03-21 07:32:40.826  1019  1019 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,03-21 07:32:40.836  1019  1019 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1019  tag : ACTIVITY_RESUME_BOOSTER@11
,03-21 07:32:40.846  1238  3472 D MediaProvider: savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache existed
,03-21 07:32:40.846  1019  1032 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10157
,03-21 07:32:40.846  1019  1531 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:40.846  1019  1531 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:40.846  1019  1531 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:40.846  1019  1531 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 07:32:40.846  1238  3472 D MediaProvider: savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache is empty
,03-21 07:32:40.856  1488  1901 D TP/SmsProvider: query,matched:51, calling pid = 2423
,03-21 07:32:40.856  1812  1812 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,03-21 07:32:40.856  1812  1812 D daemonapp: [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
,03-21 07:32:40.866  3687  3687 E Zygote  : MountEmulatedStorage()
03-21 07:32:40.866  3687  3687 E Zygote  : v2
03-21 07:32:40.866  3687  3687 I libpersona: KNOX_SDCARD checking this for 10146
03-21 07:32:40.866  3687  3687 I libpersona: KNOX_SDCARD not a persona
,03-21 07:32:40.866  3687  3687 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-21 07:32:40.866  3687  3687 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-21 07:32:40.866  3687  3687 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,03-21 07:32:40.876  1019  1531 I ActivityManager: Start proc com.sec.providers.settingsearch for content provider com.sec.providers.settingsearch/.SettingSearchProvider: pid=3687 uid=10146 gids={50146, 9997} abi=armeabi-v7a
,03-21 07:32:40.876  1238  3472 D MediaProvider: savePlaylistTableInBulkDeleter finished
,03-21 07:32:40.876  3669  3669 E SQLiteLog: (283) recovered 8 frames from WAL file /data/data/com.sec.dsm.system/databases/profile.db-wal
,03-21 07:32:40.886  1812  1812 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,03-21 07:32:40.886  1812  1812 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
03-21 07:32:40.886  1812  1812 D daemonapp: [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
,03-21 07:32:40.896  1488  1901 D TP/SmsProvider: match 51:Elapsed time : 35.461 ms
,03-21 07:32:40.896  1019  1395 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:40.896  1019  1043 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,03-21 07:32:40.896  1238  3472 D MediaScanner: Prescan. DB items number : 26 DB_FILES_NUMBER_CACHING_LIMITATION : 7000  Caching mode : true
,03-21 07:32:40.896  1019  1395 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 07:32:40.906  1812  1812 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
03-21 07:32:40.906  1019  1395 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 07:32:40.906  1019  1395 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 07:32:40.906  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-21 07:32:40.906  1181  1181 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-21 07:32:40.906  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-21 07:32:40.916  1812  1812 E daemonapp: [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
,03-21 07:32:40.916  1812  1812 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,03-21 07:32:40.916  3687  3687 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-21 07:32:40.916  3669  3669 D DSM     : [Lines:107] Normal booted
03-21 07:32:40.916  1812  1812 D daemonapp: [MSC_Daemon]>>> WU:2118 [0:0] [boot]now           :1458541960925
03-21 07:32:40.916  3669  3669 D DSM     : [Lines:114] Boot completed
03-21 07:32:40.916  3687  3687 D ActivityThread: Added TimaKeyStore provider
03-21 07:32:40.916  1812  1812 D daemonapp: [MSC_Daemon]>>> WU:2119 [0:0] [boot]NUT :1458563520000
03-21 07:32:40.916  1812  1812 D daemonapp: [MSC_Daemon]>>> WU:2120 [0:0] [boot]interval       :3 (21600000 ms)
03-21 07:32:40.916  1812  1812 D daemonapp: [MSC_Daemon]>>> WU:2121 [0:0] [boot]NUT - now :true
,03-21 07:32:40.926  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-21 07:32:40.926  3702  3702 E Zygote  : MountEmulatedStorage()
03-21 07:32:40.926  3702  3702 E Zygote  : v2
03-21 07:32:40.926  3702  3702 I libpersona: KNOX_SDCARD checking this for 1000
03-21 07:32:40.926  3702  3702 I libpersona: KNOX_SDCARD not a persona
,03-21 07:32:40.926  3702  3702 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-21 07:32:40.926  1019  1059 I art     : Explicit concurrent mark sweep GC freed 30992(2MB) AllocSpace objects, 9(144KB) LOS objects, 33% free, 24MB/36MB, paused 2.979ms total 334.117ms
,03-21 07:32:40.926  3702  3702 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-21 07:32:40.926  3702  3702 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-21 07:32:40.926  1019  1395 I ActivityManager: Start proc com.wssyncmldm for broadcast com.wssyncmldm/.XDMBroadcastReceiver: pid=3702 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,03-21 07:32:40.936  1238  3472 V MediaScanner: processDirectory :  /storage/emulated/0
,03-21 07:32:40.936  1019  1043 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-21 07:32:40.936  1019  1043 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-21 07:32:40.936  1019  1043 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-21 07:32:40.946  1238  3472 D MediaScanner: Skipping:
03-21 07:32:40.946  1238  3472 D MediaScanner: 7klwibgf7fvntblfd7(75ebcf7
,03-21 07:32:40.946  1019  1059 D PackageManager: delete codoeFile: 
,03-21 07:32:40.956  1019  1395 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 07:32:40.956  1019  1059 D AASAuninstall: userId = 0, info.removedAppID = 10167, info.uid = 10167, packageName = com.test.thalitest
,03-21 07:32:40.956  1019  1395 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:40.956  1019  1395 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:40.956  1019  1395 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 07:32:40.966  3702  3702 D TimaKeyStoreProvider: TimaSignature is unavailable
03-21 07:32:40.966  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-21 07:32:40.966  1019  1059 I AASA_removePackage: UID=10167 Target=com.test.thalitest
03-21 07:32:40.966  3702  3702 D ActivityThread: Added TimaKeyStore provider
,03-21 07:32:40.966  1019  1059 D PackageManager: result of delete: 1{135662194}
,03-21 07:32:40.966  1238  3472 D MediaScanner: Skipping:
03-21 07:32:40.966  1238  3472 D MediaScanner: 7klwibgf7fvntblfd7(7Budiwrd7dblb7
,03-21 07:32:40.966  1238  3472 V MediaScanner: processDirectory :  /storage/extSdCard
03-21 07:32:40.966  1238  3472 W MediaScanner: Error opening directory, reason : Permission denied.
03-21 07:32:40.966  1238  3472 W MediaScanner: 7klwibgf7fxlKdCbid7
03-21 07:32:40.966  3559  3559 D AndroidRuntime: Shutting down VM
,03-21 07:32:40.976  3717  3717 E Zygote  : MountEmulatedStorage()
03-21 07:32:40.976  3717  3717 I libpersona: KNOX_SDCARD checking this for 1000
03-21 07:32:40.976  3717  3717 E Zygote  : v2
03-21 07:32:40.976  3717  3717 I libpersona: KNOX_SDCARD not a persona
03-21 07:32:40.976  3717  3717 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-21 07:32:40.976  1019  1395 I ActivityManager: Start proc com.sec.android.app.factorykeystring for broadcast com.sec.android.app.factorykeystring/com.sec.android.app.entry.FactoryKeyStringBroadcastReceiver: pid=3717 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-21 07:32:40.976  3717  3717 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-21 07:32:40.986  1238  3472 V MediaScanner:  prescan time: 57ms (DB items: 26)
03-21 07:32:40.976  3717  3717 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-21 07:32:40.986  1238  3472 V MediaScanner:     scan time: 31ms (Caching mode: true), (makeEntry time: 17ms ~54%),  (parsing time: 0ms ~0%),  (bitmapDecoding time: 0ms ~0%), (exifExtracting time : 0ms ~0%), (sefExtracting time : 0ms ~0%), (bulkInserter time : 0ms ~0%)
03-21 07:32:40.986  1238  3472 V MediaScanner: postscan time: 17ms (bulkDeleter : 0), (delete DeadThumbnail time : 0ms)
03-21 07:32:40.986  1238  3472 V MediaScanner:    total time: 105ms
03-21 07:32:40.986  1238  3472 V MediaScanner: checked files: 10  directories : 16  (I: 0, U: 0)
,03-21 07:32:40.986  1019  1283 W ActivityManager: userId = 0, bbcId = -10000
03-21 07:32:40.986  1019  1283 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
03-21 07:32:40.986  1019  1283 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.dropbox.android, destAppInfo.processName = com.dropbox.android
,03-21 07:32:40.986  1019  1283 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:40.986  1019  1283 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:40.986  1019  1283 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:40.986  1019  1283 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 07:32:41.006  3726  3726 E Zygote  : MountEmulatedStorage(),
03-21 07:32:41.006  3726  3726 E Zygote  : v2
03-21 07:32:41.006  3726  3726 I libpersona: KNOX_SDCARD checking this for 10088
03-21 07:32:41.006  3726  3726 I libpersona: KNOX_SDCARD not a persona
03-21 07:32:41.006  3726  3726 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-21 07:32:41.016  1019  1283 I ActivityManager: Start proc com.dropbox.android:crash_uploader for service com.dropbox.android/.exception.CrashUploaderService: pid=3726 uid=10088 gids={50088, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-21 07:32:41.016  3726  3726 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-21 07:32:41.016  3726  3726 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,03-21 07:32:41.016  1238  3472 D MediaScannerService: !@done scanning volume external
,03-21 07:32:41.026  3717  3717 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-21 07:32:41.026  3717  3717 D ActivityThread: Added TimaKeyStore provider
,03-21 07:32:41.026  1812  1812 D daemonapp: [MSC_Daemon]>>> WDBH:2249 [0:0] ud NT1458563520000
,03-21 07:32:41.026  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-21 07:32:41.036  1812  1812 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 8
03-21 07:32:41.036  1812  1812 D daemonapp: [MSC_Daemon]>>> WU:2131 [0:0] Boot set AR_nexttime :1458563520000
03-21 07:32:41.036  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-21 07:32:41.036  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-21 07:32:41.036  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,03-21 07:32:41.046  3112  3112 D FactoryTestApp: [DummyFtClient$mBroadcastReceiver](3112) action= = android.intent.action.MEDIA_SCANNER_FINISHED
03-21 07:32:41.046  3112  3112 D FactoryTestApp: [DummyFtClient$mBroadcastReceiver](3112) ACTION_MEDIA_SCANNER_FINISHED = /storage/emulated/0
,03-21 07:32:41.046  3112  3112 D FactoryTestApp: [DummyFtClient$sendBootCompletedAndFinish](3112) ...
03-21 07:32:41.046  3112  3112 D FactoryTestApp: [Support$Values.getString](3112) id=MODEL_COMMUNICATION_MODE, value=gsm
03-21 07:32:41.046  3112  3112 I FactoryTestApp: [ModuleCommon$isConnectionModeNone](3112) mConnectionMode = gsm
03-21 07:32:41.046  3112  3112 D FactoryTestApp: [IPCWriterToSecPhoneService$ResponseWriter](3112) Create IPCWriterToSecPhoneService
03-21 07:32:41.046  3112  3112 I FactoryTestApp: [IPCWriterToSecPhoneService$connectToSecPhoneService](3112)  
03-21 07:32:41.046  3726  3726 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-21 07:32:41.046  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-21 07:32:41.046  3726  3726 D ActivityThread: Added TimaKeyStore provider
,03-21 07:32:41.046  3112  3112 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.sec.factory.aporiented.IPCWriterToSecPhoneService.connectToSecPhoneService:97 com.sec.factory.aporiented.IPCWriterToSecPhoneService.<init>:64 com.sec.factory.aporiented.DummyFtClient.sendBootCompletedAndFinish:147 
,03-21 07:32:41.046  1812  1812 D comdaemonstockapp: [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] onReceive: androidintentactionBOOT_COMPLETED
,03-21 07:32:41.046  1812  1812 D comdaemonstockapp: [Daemon_Stock]>>> StockclockDaemonService.java:62 [0:0] appServiceStatus: 0
,03-21 07:32:41.056  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-21 07:32:41.056  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,03-21 07:32:41.056  3702  3702 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-21 07:32:41.056  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-21 07:32:41.056  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,03-21 07:32:41.056  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-21 07:32:41.066  1019  1043 D UsbSettingsManager: clearDefaults: com.test.thalitest
,03-21 07:32:41.066  1019  1043 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
,03-21 07:32:41.066  2423  3543 D Mms/MessagingNotification: isBlockingModeEnabled() = false, Zen mode = 0
,03-21 07:32:41.076  3717  3717 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,03-21 07:32:41.076  1019  1499 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:41.076  1019  1499 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:41.076  1019  1499 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:41.076  1019  1499 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 07:32:41.086  3749  3749 E Zygote  : MountEmulatedStorage()
03-21 07:32:41.086  3749  3749 E Zygote  : v2
03-21 07:32:41.086  3749  3749 I libpersona: KNOX_SDCARD checking this for 10161
03-21 07:32:41.086  3749  3749 I libpersona: KNOX_SDCARD not a persona
,03-21 07:32:41.086  3749  3749 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-21 07:32:41.096  1019  1499 I ActivityManager: Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService$BootReceiver: pid=3749 uid=10161 gids={50161, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-21 07:32:41.096  3749  3749 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-21 07:32:41.096  3749  3749 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
03-21 07:32:41.096  1019  1561 W ActivityManager: userId = 0, bbcId = -10000
03-21 07:32:41.096  1019  1561 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-21 07:32:41.096  1019  1561 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.factory, destAppInfo.processName = com.sec.phone
,03-21 07:32:41.116  3628  3646 D BadgeProvider: query, [selection] : package='com.android.mms' AND class='com.android.mms.ui.ConversationComposer' AND extraData='base_extra_badge'
,03-21 07:32:41.126  3749  3749 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-21 07:32:41.126  3749  3749 D ActivityThread: Added TimaKeyStore provider
,03-21 07:32:41.146  1019  1043 W libprocessgroup: failed to open /acct/uid_10003/pid_1254/cgroup.procs: No such file or directory
,03-21 07:32:41.146  3112  3112 I FactoryTestApp: [IPCWriterToSecPhoneService$onServiceConnected](3112) connected done
03-21 07:32:41.146  3112  3112 D FactoryTestApp: [IPCWriterToSecPhoneService$write](3112) Send Response Message to SecPhone
03-21 07:32:41.146  3112  3112 D FactoryTestApp: [IPCWriterToSecPhoneService$write](3112) Response ��
,03-21 07:32:41.156   330  1075 D AT_Distributor: Send Msg [RIL > ATD] 19 bytes <BOOTING COMPLETED(\r)(\n)>,
,03-21 07:32:41.166  3112  3112 D FactoryTestApp: [IPCWriterToSecPhoneService$handleMessage](3112) Send BOOTING COMPLETED done
,03-21 07:32:41.176  3559  3559 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,03-21 07:32:41.186  3717  3717 W ActivityThread: ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,03-21 07:32:41.196  1019  1059 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
03-21 07:32:41.196  1019  1059 D PackageManager: userId{-1}
03-21 07:32:41.196  1019  1059 D PackageManager: andCode{true}
,03-21 07:32:41.196  1019  1059 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:41.196  1019  1059 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:41.196  1019  1059 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:41.196  1019  1059 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 07:32:41.206  3770  3770 E Zygote  : MountEmulatedStorage(),
03-21 07:32:41.206  3770  3770 I libpersona: KNOX_SDCARD checking this for 10003
03-21 07:32:41.206  3770  3770 E Zygote  : v2
03-21 07:32:41.206  3770  3770 I libpersona: KNOX_SDCARD not a persona
,03-21 07:32:41.216  1019  1059 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=3770 uid=10003 gids={50003, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,03-21 07:32:41.226  3702  3702 I FOTA    : [com.wssyncmldm.db.sql.XDMDbContentProvider(95/onCreate)] 
,03-21 07:32:41.226  3628  3646 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/2
,03-21 07:32:41.226  3628  3646 D BadgeProvider: sendNotify, [notify] : null
03-21 07:32:41.226  3628  3646 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/2
03-21 07:32:41.226  3628  3646 D BadgeProvider: update, [BadgeCount] : badgecount=0
03-21 07:32:41.226  3628  3646 D BadgeProvider: update, [UpdateCount] : 1
,03-21 07:32:41.226  2423  3543 D Mms/MessagingNotification: setBadgeCount(), count=0
,03-21 07:32:41.236  3170  3305 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,03-21 07:32:41.246  2423  3543 D Mms/MessagingNotification: remove alarm
,03-21 07:32:41.246  3717  3717 D LcdtestApp: [Class]XMLDataStorage, [Method]parseXML, [Message]modelXML=sm-a300fu.dat
03-21 07:32:41.246  3717  3717 D LcdtestApp: [Class]XMLDataStorage, [Method]parseXML, [Message]deviceXML=a3ulte.dat
,03-21 07:32:41.246  3717  3717 I LcdtestApp: [Class]XMLDataStorage, [Method]parseAsset, [Message]Convert enc file to xml file: sm-a300fu.dat
,03-21 07:32:41.246  2423  3776 D Mms/MessagingNotification: updateAllHistoryAsRead()
,03-21 07:32:41.246  3170  3305 D BluetoothMediaBrowser: no now playing list
,03-21 07:32:41.246  3170  3305 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,03-21 07:32:41.256   330  1075 D AT_Distributor: SetAtdStatus(), 1_1_0
03-21 07:32:41.256   330  1075 D AT_Distributor: Send Msg [ATD > UART] 19 bytes <BOOTING COMPLETED(\r)(\n)>
,03-21 07:32:41.256  1488  1498 D TP/SmsProvider: query,matched:0, calling pid = 2423
,03-21 07:32:41.266  3717  3717 D LcdtestApp: [Class]XMLDataStorage, [Method]parseAsset, [Message]Decode base xml file: lcdtest.dat
,03-21 07:32:41.266  1488  1498 D TP/SmsProvider: match 0:Elapsed time : 4.223 ms
,03-21 07:32:41.266  1181  1181 D StatusBar.NetworkController: refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,03-21 07:32:41.266  1181  1181 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-21 07:32:41.266  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-21 07:32:41.276  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-21 07:32:41.276  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-21 07:32:41.276  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-21 07:32:41.276  2423  3543 D Mms/SmsReceiverService: [end]    handleBootCompleted() consume time = 546.154584
,03-21 07:32:41.286  1019  1032 I ActivityManager: Killing 2914:com.sec.android.app.samsungapps/u0a9 (adj 15): empty #31
,03-21 07:32:41.296  3717  3717 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MODEL_NAME
03-21 07:32:41.296  3717  3717 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_ACCELEROMETER
03-21 07:32:41.296  3717  3717 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_MAGNETIC
03-21 07:32:41.296  3717  3717 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_GYROSCOPE
03-21 07:32:41.296  3717  3717 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MAGNETIC_ROTATE_DEGREE
03-21 07:32:41.296  3717  3717 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LCD_TYPE
03-21 07:32:41.296  3717  3717 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MODEL_COMMUNICATION_MODE
03-21 07:32:41.296  3717  3717 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=DEVICE_TYPE
03-21 07:32:41.296  3717  3717 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_TOUCHKEY_GRAPH
,03-21 07:32:41.296  3717  3717 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_TSP_SUPPORT_CONFIG_VERSION
03-21 07:32:41.296  3717  3717 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SUPPORT_TSK_FW_UPDATE_INTERNAL
03-21 07:32:41.296  3717  3717 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=FAILHIST_VERSION
03-21 07:32:41.296  3717  3717 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SUPPORT_RUN_REF
03-21 07:32:41.296  3717  3717 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_SIMPLE_TEST_ACC_SYSFS
,03-21 07:32:41.296  3717  3717 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_SENSOR_TEST_ACC_REVERSE
03-21 07:32:41.296  3717  3717 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_TEST_ACC_BIT
,03-21 07:32:41.296  3717  3717 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_DISPLAY_LUX_ADC
03-21 07:32:41.296  3717  3717 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_PROXIMITY_TEST_MOTOR_FEEDBACK
,03-21 07:32:41.296  3717  3717 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=KEY_TEST_APP_RECENT
,03-21 07:32:41.306  1019  1571 D PowerManagerService: [api] release WakeLock flags=0x10000006 tag=PowerUI.Notification uid=10049 pid=1181 (0x0)
03-21 07:32:41.306  3717  3717 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=KEY_TEST_BACK
,03-21 07:32:41.306  3717  3717 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SUPPORT_CHARGE_COUNT
,03-21 07:32:41.306  3717  3717 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=NO_RGBSENSOR_SUPPORT_REV
03-21 07:32:41.306  3717  3717 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=TSP_X_AXIS_CHANNEL
,03-21 07:32:41.306  3717  3717 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=TSP_Y_AXIS_CHANNEL
03-21 07:32:41.306  3717  3717 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_LEVEL_2_MAX
,03-21 07:32:41.306  3717  3717 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_1
,03-21 07:32:41.306  3717  3717 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_2
,03-21 07:32:41.306  3717  3717 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_3
03-21 07:32:41.306  3717  3717 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_4
,03-21 07:32:41.306  3717  3717 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_5
,03-21 07:32:41.306  3717  3717 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_2
03-21 07:32:41.306  3717  3717 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_3
,03-21 07:32:41.306  3717  3717 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_4
,03-21 07:32:41.306  3717  3717 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_5
,03-21 07:32:41.306  3717  3717 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=PATH_NOISE_TSK_BACK_RAWDATA
,03-21 07:32:41.306  3717  3717 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=PATH_NOISE_TSK_RECENT_RAWDATA
,03-21 07:32:41.316  3717  3717 I LcdtestApp: [Class]FactoryKeyStringBroadcastReceiver, [Method]onReceive, , [Message]pref_hardReset : N
,03-21 07:32:41.316  1019  1804 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 07:32:41.316  1019  1804 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:41.316  1019  1804 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:41.316  1019  1804 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 07:32:41.316  1507  1507 D Launcher.Model: reloadBadges entered.
,03-21 07:32:41.326  1507  1507 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,03-21 07:32:41.326  1507  1507 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,03-21 07:32:41.326  3770  3770 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-21 07:32:41.326  3770  3770 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-21 07:32:41.326  3770  3770 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-21 07:32:41.346  3783  3783 E Zygote  : MountEmulatedStorage()
,03-21 07:32:41.346  3783  3783 E Zygote  : v2
03-21 07:32:41.346  3783  3783 I libpersona: KNOX_SDCARD checking this for 1000,
03-21 07:32:41.346  3783  3783 I libpersona: KNOX_SDCARD not a persona
03-21 07:32:41.346  3783  3783 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-21 07:32:41.356  3783  3783 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
03-21 07:32:41.356  3783  3783 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-21 07:32:41.356  1019  1804 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonBootCompletedReceiver: pid=3783 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-21 07:32:41.356  1019  1804 I ActivityManager: Killing 2951:com.sec.android.fotaclient/u0a8 (adj 15): empty #31
,03-21 07:32:41.366  3770  3770 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-21 07:32:41.366  3770  3770 D ActivityThread: Added TimaKeyStore provider
,03-21 07:32:41.386  3783  3783 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-21 07:32:41.386  3783  3783 D ActivityThread: Added TimaKeyStore provider
,03-21 07:32:41.396  1019  1395 I ActivityManager: Killing 2972:com.samsung.android.scloud.sync/u0a58 (adj 15): empty #31
,03-21 07:32:41.436  3598  3598 I com.dropbox.android.service.DropboxNetworkReceiver: Setting receiver enabled: false
,03-21 07:32:41.436  3783  3783 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,03-21 07:32:41.446  3598  3598 E ActivityThread: Failed to find provider info for com.dropbox.carousel.CuOwnerCheckProvider
,03-21 07:32:41.466  1019  1630 I ActivityManager: Killing 2826:com.osp.app.signin/u0a36 (adj 15): empty #31
,03-21 07:32:41.486  3749  3802 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,03-21 07:32:41.486  3749  3802 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-21 07:32:41.486  1019  1043 W libprocessgroup: failed to open /acct/uid_10009/pid_2914/cgroup.procs: No such file or directory
,03-21 07:32:41.486  1019  1043 W libprocessgroup: failed to open /acct/uid_10008/pid_2951/cgroup.procs: No such file or directory
03-21 07:32:41.486  1019  1043 W libprocessgroup: failed to open /acct/uid_10058/pid_2972/cgroup.procs: No such file or directory
,03-21 07:32:41.516  3702  3702 I DBG_DM  : [llIIlIIlIllIllIlllII(316/llIlIIIIlIIIIIlIlIII)] Voice : true
,03-21 07:32:41.516  3749  3802 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,03-21 07:32:41.526  3598  3598 I dbxyzptlk.db240408.D.h: Loading /data/data/com.dropbox.android/files/extracted_libs/lib_breakpadinstaller_1dc04d6d96cbb2962385ec13f5f77649aec85e95_arm
,03-21 07:32:41.536  3702  3702 I DBG_DM  : [llIIlIIlIllIllIlllII(317/llIlIIIIlIIIIIlIlIII)] SMS : true
,03-21 07:32:41.536  3702  3702 I DBG_DM  : [llIIlIIlIllIllIlllII(318/llIlIIIIlIIIIIlIlIII)] isDataOnly : false
,03-21 07:32:41.536  3598  3598 I dbxyzptlk.db240408.D.h: Loading /data/data/com.dropbox.android/files/extracted_libs/lib_dbxfileobserver_59d9546785d1f42b870763ef906fd65c59b55c56_arm
,03-21 07:32:41.536  3598  3598 I dbxyzptlk.db240408.D.h: Loading /data/data/com.dropbox.android/files/extracted_libs/lib_dropboxsync_cf9d7b2df44b0b78b581431109195f96d492fc70_arm
,03-21 07:32:41.546  1019  1043 W libprocessgroup: failed to open /acct/uid_10036/pid_2826/cgroup.procs: No such file or directory
,03-21 07:32:41.576  3783  3783 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,03-21 07:32:41.586  3783  3783 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,03-21 07:32:41.586  3783  3783 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.intent.action.BOOT_COMPLETED
,03-21 07:32:41.586  3783  3783 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
03-21 07:32:41.586  3783  3783 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(68/lllIlIlIIIllIIlIllIl)] Running with BootCompletedReceiver adapter
03-21 07:32:41.586  3783  3783 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,03-21 07:32:41.586  3598  3598 I dbxyzptlk.db240408.D.h: Loading /data/data/com.dropbox.android/files/extracted_libs/lib_mupdf_391432aaa92f053af59645394b5734622378199a_arm
,03-21 07:32:41.596  3749  3802 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,03-21 07:32:41.596  3749  3802 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@31de0078: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
03-21 07:32:41.596  3749  3802 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,03-21 07:32:41.626   258   519 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/cache/
03-21 07:32:41.626   258   519 W Vold    : Returning OperationFailed - no handler for errno 0
,03-21 07:32:41.626  3749  3749 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
,03-21 07:32:41.636  3598  3598 D breakpad: breakpad loaded; target path "/data/data/com.dropbox.android/app_crashdumps"
,03-21 07:32:41.636  3702  3702 I DBG_DM  : [com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI(2693/lllIlIlIIIllIIlIllIl)] xdbsqlGetFUMOStatus : 220
,03-21 07:32:41.636  3702  3702 I DBG_DM  : [com.wssyncmldm.XDMApplication(80/onCreate)] XDMApplication Start ! - Fumo State
,03-21 07:32:41.636  3702  3702 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 com.wssyncmldm.XDMApplication.onCreate:81 android.app.Instrumentation.callApplicationOnCreate:1020 android.app.ActivityThread.handleBindApplication:5256 
,03-21 07:32:41.636  1019  1630 W ActivityManager: userId = 0, bbcId = -10000
03-21 07:32:41.646  1019  1630 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-21 07:32:41.646  1019  1630 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.wssyncmldm, destAppInfo.processName = com.wssyncmldm
,03-21 07:32:41.646  3702  3702 I DBG_DM  : [com.wssyncmldm.XDMBroadcastReceiver(152/onReceive)] android.intent.action.BOOT_COMPLETED
,03-21 07:32:41.646  3702  3702 I DBG_DM  : [com.wssyncmldm.XDMService(1598/IlIlllIIlIlIIIlIlIll)] 
,03-21 07:32:41.646  3702  3702 I DBG_DM  : [com.wssyncmldm.XDMService(1603/IlIlllIIlIlIIIlIlIll)] m_WakeLock is acquire!!
,03-21 07:32:41.656  3702  3702 I DBG_DM  : [com.wssyncmldm.XDMService(1420/lllIlIlIIIllIIlIllIl)] 0
,03-21 07:32:41.656  1181  1181 D OverheatReceiver: onReceive() getAction : android.intent.action.BOOT_COMPLETED
,03-21 07:32:41.656  3702  3702 I DBG_DM  : [IIlIIIlllllIIlIIIlII(232/llllIllIIIIIlIIllIII)] Default - NO_ROOTING_CHECK : false
03-21 07:32:41.656  3598  3598 I com.dropbox.sync.android.a: Prepared cache dir '/data/data/com.dropbox.android/app_DropboxSyncCache/hizqkiq3952astb'.
,03-21 07:32:41.656  3702  3702 I DBG_DM  : [com.wssyncmldm.XDMService(1463/llIlIIIIlIIIIIlIlIII)] 0
,03-21 07:32:41.656  3702  3702 I DBG_DM  : [IIlIIIlllllIIlIIIlII(261/IIllIlIIIIlIIIllIllI)] Roaming Check : true
,03-21 07:32:41.666  3702  3702 I DBG_DM  : [com.wssyncmldm.XDMService(1548/llIIllllIIlllIIIIlll)] 0
,03-21 07:32:41.666  1019  1283 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:41.666  1019  1283 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:41.666  1019  1283 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:41.666  1019  1283 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:41.666  3702  3702 I DBG_DM  : [IIlIIIlllllIIlIIIlII(293/llIIlIlIlIlIIIIIIlIl)] validation Check On
,03-21 07:32:41.666  3702  3702 I DBG_DM  : [com.wssyncmldm.XDMService(1505/IllIlIIIIlIIlIIIllIl)] 0
,03-21 07:32:41.666  3702  3702 I DBG_DM  : [IIlIIIlllllIIlIIIlII(274/lllllllIlllIIlllIlIl)] SSL Check On
,03-21 07:32:41.666  3702  3702 I DBG_DM  : [llIIlIIlIllIllIlllII(109/llllIIIllIlIIIIllllI)] 
03-21 07:32:41.666  3702  3811 I DBG_DM  : [IlIIlIIlIllllIlllIII(181/llIIIIlllllIIllIIllI)] XEVENT_OS_INITIALIZED
,03-21 07:32:41.666  1181  1181 D OverheatReceiver: into the SAFE_MODE_ACTION
03-21 07:32:41.666  1181  1181 D OverheatReceiver: VZW on -> change to Global UX [safe mode]
,03-21 07:32:41.676  1181  1181 D OverheatReceiver: isSafeMode = false
,03-21 07:32:41.676  3823  3823 E Zygote  : MountEmulatedStorage()
03-21 07:32:41.676  3823  3823 E Zygote  : v2
03-21 07:32:41.676  3823  3823 I libpersona: KNOX_SDCARD checking this for 1000
03-21 07:32:41.676  3823  3823 I libpersona: KNOX_SDCARD not a persona
03-21 07:32:41.676  3823  3823 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-21 07:32:41.676  3702  3702 I DBG_DM  : [llIIlIIlIllIllIlllII(397/llIIIIlllllIIllIIllI)] External SD Card Path : /storage/extSdCard
,03-21 07:32:41.676  3823  3823 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-21 07:32:41.686  3823  3823 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-21 07:32:41.686  1019  1283 I ActivityManager: Start proc com.policydm for content provider com.policydm/com.sec.android.policydm.log.MasterLogProvider: pid=3823 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,03-21 07:32:41.686  3702  3811 I DBG_DM  : [llIlIIIIlllIlllllIll(142/llIIIIlllllIIllIIllI)] nSync = 0
,03-21 07:32:41.686  3702  3811 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.wssyncmldm.ui.lIlIIlIlIlIllllllIII.lllIlIlIIIllIIlIllIl:72 com.wssyncmldm.ui.lIlIIlIlIlIllllllIII.llIIIIlllllIIllIIllI:112 IlIIlIIlIllllIlllIII.llIIIIlllllIIllIIllI:185 
03-21 07:32:41.686  1019  1809 W ActivityManager: userId = 0, bbcId = -10000
03-21 07:32:41.686  1019  1809 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-21 07:32:41.686  1019  1809 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.wssyncmldm, destAppInfo.processName = com.wssyncmldm
03-21 07:32:41.686  3702  3702 I DBG_DM  : [llIIlIIlIllIllIlllII(166/llllIIIllIlIIIIllllI)] bExternalStorageAvailable [true]
03-21 07:32:41.686  3702  3702 I DBG_DM  : [llIIlIIlIllIllIlllII(167/llllIIIllIlIIIIllllI)] bExternalSDStorageAvailable [false]
,03-21 07:32:41.686  3702  3702 I DBG_DM  : [com.wssyncmldm.XDMService(1624/IIlIlIIlIlIIlIlllIIl)] 
,03-21 07:32:41.696  3702  3702 I DBG_DM  : [com.wssyncmldm.XDMService(1629/IIlIlIIlIlIIlIlllIIl)] m_WakeLock is release!!
,03-21 07:32:41.696  3702  3702 I DBG_DM  : [com.wssyncmldm.XDMService(155/onStartCommand)] 
,03-21 07:32:41.706  1488  1488 D BootupListener: intent.getAction() = android.intent.action.BOOT_COMPLETED,
,03-21 07:32:41.706  1019  1502 D SettingsProvider: name = internet_call_settings_visibility
03-21 07:32:41.706  1019  1502 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-21 07:32:41.706  1019  1502 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-21 07:32:41.706  1019  1502 D SettingsProvider: selectionArgs: false
03-21 07:32:41.706  1019  1502 D SettingsProvider: selectionArgs: 1001
03-21 07:32:41.706  1019  1502 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-21 07:32:41.706  1019  1502 D SettingsProvider: ret = -1
03-21 07:32:41.716  1488  1488 D PhoneUtilsCommon: isSupportVoLTE is false.
,03-21 07:32:41.716  3702  3702 I DBG_DM  : [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
03-21 07:32:41.716  3702  3702 I DBG_DM  : [com.wssyncmldm.ui.IIllIllllIIlIlIIlIII(49/onServiceConnected)] 
,03-21 07:32:41.726  3823  3823 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-21 07:32:41.736  3823  3823 D ActivityThread: Added TimaKeyStore provider
,03-21 07:32:41.736  1459  1459 I Telecom : InCallController: Attempting to bind to InCall com.android.incallui, is dupe? false 
,03-21 07:32:41.736  1019  1138 W ActivityManager: userId = 0, bbcId = -10000
,03-21 07:32:41.736  1019  1138 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-21 07:32:41.736  1019  1138 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.incallui
,03-21 07:32:41.746  1019  1561 W ActivityManager: userId = 0, bbcId = -10000
,03-21 07:32:41.746  1019  1561 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-21 07:32:41.746  1019  1561 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.incallui
,03-21 07:32:41.746  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:41.746  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:41.746  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:41.746  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 07:32:41.766  3841  3841 E Zygote  : MountEmulatedStorage(),
03-21 07:32:41.766  3841  3841 E Zygote  : v2
03-21 07:32:41.766  3841  3841 I libpersona: KNOX_SDCARD checking this for 10052
03-21 07:32:41.766  1019  1032 I ActivityManager: Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.StartUpReceiver: pid=3841 uid=10052 gids={50052, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a
03-21 07:32:41.766  3841  3841 I libpersona: KNOX_SDCARD not a persona
,03-21 07:32:41.766  3841  3841 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-21 07:32:41.766  3841  3841 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,03-21 07:32:41.776  3841  3841 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-21 07:32:41.776  3702  3811 I DBG_DM  : [com.wssyncmldm.db.file.XDB(1976/llIlIIIIlIIIIIlIlIII)] xdbDMffs_Init
,03-21 07:32:41.786  3823  3823 I DBG_POLICYDM: [com.policydm.XDMApplication(554/xdmWakeLockAcquire)] 
,03-21 07:32:41.796  3823  3823 I DBG_POLICYDM: [com.policydm.XDMApplication(559/xdmWakeLockAcquire)] m_WakeLock is acquire!!
,03-21 07:32:41.796  3823  3823 I DBG_POLICYDM: [com.policydm.eng.core.XDMMsg(70/xdmSendMessage)] waiting for DM_TaskHandler create
,03-21 07:32:41.796  3841  3841 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-21 07:32:41.806  3841  3841 D ActivityThread: Added TimaKeyStore provider
,03-21 07:32:41.806  1019  1804 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:41.806  1019  1804 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:41.806  1019  1804 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:41.806  1019  1804 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 07:32:41.826  3864  3864 E Zygote  : MountEmulatedStorage()
03-21 07:32:41.826  3864  3864 E Zygote  : v2
03-21 07:32:41.826  3864  3864 I libpersona: KNOX_SDCARD checking this for 10008
03-21 07:32:41.826  3864  3864 I libpersona: KNOX_SDCARD not a persona
,03-21 07:32:41.826  3864  3864 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,03-21 07:32:41.826  3864  3864 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-21 07:32:41.826  1019  1804 I ActivityManager: Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=3864 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-21 07:32:41.826  3864  3864 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,03-21 07:32:41.836  1459  1459 I Telecom : InCallController: onConnected to ComponentInfo{com.android.incallui/com.android.incallui.InCallServiceImpl},
03-21 07:32:41.836  1019  1809 W ActivityManager: userId = 0, bbcId = -10000
03-21 07:32:41.836  1019  1809 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-21 07:32:41.836  1019  1809 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,03-21 07:32:41.856  3864  3864 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-21 07:32:41.856  3864  3864 D ActivityThread: Added TimaKeyStore provider
,03-21 07:32:41.886  3702  3811 I DBG_DM  : [IlIIlIIlIllllIlllIII(191/llIIIIlllllIIllIIllI)] XEVENT_PHONEBOOK_INITIALIZED
,03-21 07:32:41.926  3702  3811 I DBG_DM  : [com.wssyncmldm.db.file.XDB(3660/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,03-21 07:32:41.936  3702  3811 I DBG_DM  : [com.wssyncmldm.XDMService(1377/llllIIIllIlIIIIllllI)] wssGetUpdateReport : 0
03-21 07:32:41.936  1019  1499 W ActivityManager: userId = 0, bbcId = -10000
03-21 07:32:41.936  1019  1499 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-21 07:32:41.936  1019  1499 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,03-21 07:32:41.936  3702  3811 I DBG_DM  : [IlIIlIIlIllllIlllIII(217/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT
,03-21 07:32:41.966   285   699 V audio_hw_primary: adev_get_parameters: enter: keys - call_forwarding
03-21 07:32:41.966   285   699 D audio_hw_extn: audio_extn_get_parameters: returns 
03-21 07:32:41.966   285   699 V msm8974_platform: platform_get_parameters: exit: returns - 
03-21 07:32:41.966   285   699 V audio_hw_primary: adev_get_parameters: exit: returns - call_forwarding=false
03-21 07:32:41.966   285   699 I str_params: key: 'call_forwarding' value: ''
03-21 07:32:41.966  2044  2044 V InCall  : ProximitySensor -  - screenonImmediately: false
03-21 07:32:41.966  2044  2044 V InCall  : ProximitySensor -  - mFromRcsShare: false
03-21 07:32:41.966  2044  2044 I InCall  : ProximitySensor -  - ProximitySensor{keybrd=0, dpad=0, offhook=0, hor=0, ui=0, aud=EARPIECE}
,03-21 07:32:41.966  2044  2044 D ScoverManager: serviceVersion : 16908288
03-21 07:32:41.966  1019  1499 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
,03-21 07:32:41.966  2044  2044 D InCall  : InCallUtils - isCoverClosed : TYPE_FLIP_COVER 
,03-21 07:32:41.976  1459  1459 I Telecom : ProximitySensorManager: Proximity wake lock already released
,03-21 07:32:41.976  1019  1630 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
,03-21 07:32:41.976  2044  2044 D InCall  : InCallUtils - isCoverClosed : TYPE_FLIP_COVER 
03-21 07:32:41.976  2044  2044 I InCall  : InCallPresenter -  - InCallState = NO_CALLS
,03-21 07:32:41.976  2044  2044 I InCall  : InCallPresenter -  - Phone switching state: NO_CALLS -> NO_CALLS
,03-21 07:32:41.976  2044  2044 D InCall  : InCallPresenter -  - dismissCoverDialog()...
,03-21 07:32:41.976  2044  2044 I InCall  : CallSContextMotion - stopPutDownListening
,03-21 07:32:41.986  2044  2044 D InCall  : StatusBarNotifier - updateInCallNotification(allowFullScreenIntent = false)...
,03-21 07:32:41.986  3749  3749 E YouTube MDX: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,03-21 07:32:41.986  1019  1630 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
,03-21 07:32:41.986  2044  2044 D InCall  : InCallUtils - isCoverClosed : TYPE_FLIP_COVER 
03-21 07:32:41.986  1181  1181 D PhoneStatusBarView: setCallBackground:0
,03-21 07:32:42.016  2044  2044 D VideoCallManager: Instantiating VideoCallManager
03-21 07:32:42.016  3823  3833 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,03-21 07:32:42.026  3823  3833 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,03-21 07:32:42.026  3823  3833 I DBG_POLICYDM: [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,03-21 07:32:42.026  3823  3832 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,03-21 07:32:42.036  3823  3832 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,03-21 07:32:42.036  2044  2044 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
,03-21 07:32:42.036  3823  3832 I DBG_POLICYDM: [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
03-21 07:32:42.036  2044  2044 I GFX construct_block_size_descriptor_2d second part: took 2.490625ms for 0*0 texture 0
,03-21 07:32:42.046  1019  1138 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,03-21 07:32:42.046  2044  2044 I GFX generate_partition_tables: took 5.328281ms for 0*0 texture 0
,03-21 07:32:42.046  2044  2044 I GFX raster: took 11.800468ms for 176*144 texture 0
03-21 07:32:42.046  1019  1283 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
03-21 07:32:42.046  2044  2044 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8142330 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b0, Counterpart=0xb8142228 counterpartCT=4 counterpartW=176 counterparth=144
,03-21 07:32:42.046  1019  1502 I AudioService: getStreamVolume 3 index 0
,03-21 07:32:42.056  2044  2044 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 320x240
,03-21 07:32:42.056  2044  2044 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
03-21 07:32:42.056  2044  2044 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
03-21 07:32:42.056  2044  2044 I Adreno-EGL: Build Date: 04/06/15 Mon
03-21 07:32:42.056  2044  2044 I Adreno-EGL: Local Branch: 
03-21 07:32:42.056  2044  2044 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
03-21 07:32:42.056  2044  2044 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
03-21 07:32:42.056  2044  2044 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,03-21 07:32:42.056  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 07:32:42.056  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:42.056  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 07:32:42.056  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 07:32:42.076  3899  3899 E Zygote  : MountEmulatedStorage()
03-21 07:32:42.076  3899  3899 E Zygote  : v2
03-21 07:32:42.076  3899  3899 I libpersona: KNOX_SDCARD checking this for 1000
03-21 07:32:42.076  3899  3899 I libpersona: KNOX_SDCARD not a persona
,03-21 07:32:42.076  3899  3899 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-21 07:32:42.076  3899  3899 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-21 07:32:42.086  3899  3899 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-21 07:32:42.086  1019  1032 I ActivityManager: Start proc com.fmm.dm for broadcast com.fmm.dm/.XDMBroadcastReceiver: pid=3899 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,03-21 07:32:42.086  1019  1032 I ActivityManager: Killing 1751:com.samsung.android.securitylogagent/1000 (adj 15): empty #31
,03-21 07:32:42.106  1019  1395 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 07:32:42.106  1019  1395 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:42.106  1019  1395 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:42.106  1019  1395 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 07:32:42.106   322   322 I art     : Explicit concurrent mark sweep GC freed 8749(372KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 615us total 25.987ms
,03-21 07:32:42.116  3899  3899 D TimaKeyStoreProvider: TimaSignature is unavailable
03-21 07:32:42.116  3899  3899 D ActivityThread: Added TimaKeyStore provider
03-21 07:32:42.116  2044  2044 I GFX GPU raster: eglCreateImageKHR: EGL_SUCCESS
,03-21 07:32:42.126   322   322 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 617us total 17.619ms
,03-21 07:32:42.126  2044  2044 I glCompressedTexImage2D: took 0.244271ms for 320*61440 texture 37809
,03-21 07:32:42.136  2044  2044 I draw setup: took 11.129114ms for 320*240 texture 37809,
03-21 07:32:42.136  2044  2044 E GFX GPU raster: drawn
,03-21 07:32:42.146  2044  2044 I GFX GPU raster ASTC: took 43.236355ms for 320*240 texture 12
03-21 07:32:42.146  2044  2044 I GFX raster: took 43.314532ms for 320*240 texture 0
03-21 07:32:42.146  2044  2044 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb81420f0 bitmapCt=12 bitmapW=320 bitmapH=240 BitmapInternalFormat=93b1, Counterpart=0xb8142278 counterpartCT=4 counterpartW=320 counterparth=240
,03-21 07:32:42.146   322   322 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 573us total 16.845ms,
,03-21 07:32:42.156  3923  3923 E Zygote  : MountEmulatedStorage(),
03-21 07:32:42.156  3923  3923 E Zygote  : v2
03-21 07:32:42.156  3923  3923 I libpersona: KNOX_SDCARD checking this for 10014,
03-21 07:32:42.156  3923  3923 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-21 07:32:42.156  3923  3923 I libpersona: KNOX_SDCARD not a persona,
03-21 07:32:42.156  2044  2044 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 480x640
,03-21 07:32:42.166  2044  2044 I GFX GPU raster: eglCreateImageKHR: EGL_SUCCESS
,03-21 07:32:42.166  3923  3923 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
03-21 07:32:42.166  2044  2044 I glCompressedTexImage2D: took 0.325572ms for 480*122880 texture 37813
03-21 07:32:42.166  1019  1395 I ActivityManager: Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=3923 uid=10014 gids={50014, 9997, 3003} abi=armeabi-v7a
03-21 07:32:42.166  2044  2044 I draw setup: took 0.643959ms for 480*640 texture 37813
03-21 07:32:42.166  2044  2044 E GFX GPU raster: drawn
03-21 07:32:42.166  3923  3923 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-21 07:32:42.166  2044  2044 I GFX GPU raster ASTC: took 7.480312ms for 480*640 texture 12
03-21 07:32:42.166  2044  2044 I GFX raster: took 7.565886ms for 480*640 texture 0
,03-21 07:32:42.166  2044  2044 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb83836d8 bitmapCt=12 bitmapW=480 bitmapH=640 BitmapInternalFormat=93b5, Counterpart=0xb8383988 counterpartCT=4 counterpartW=480 counterparth=640
,03-21 07:32:42.186  3923  3923 D TimaKeyStoreProvider: TimaSignature is unavailable
03-21 07:32:42.186  3923  3923 D ActivityThread: Added TimaKeyStore provider
,03-21 07:32:42.196  1019  1502 W ActivityManager: userId = 0, bbcId = -10000
03-21 07:32:42.196  1019  1502 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-21 07:32:42.196  1019  1502 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,03-21 07:32:42.196  1019  1804 D LocationManagerService: getProviders()=[passive]
,03-21 07:32:42.206   258   519 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/cache/
03-21 07:32:42.206   258   519 W Vold    : Returning OperationFailed - no handler for errno 0
,03-21 07:32:42.206  1019  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_1751/cgroup.procs: No such file or directory
,03-21 07:32:42.206  3749  3749 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
,03-21 07:32:42.206   258   519 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/files/
03-21 07:32:42.206   258   519 W Vold    : Returning OperationFailed - no handler for errno 0
03-21 07:32:42.206  3749  3749 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
,03-21 07:32:42.206   258   519 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/files/
03-21 07:32:42.206   258   519 W Vold    : Returning OperationFailed - no handler for errno 0
,03-21 07:32:42.206  3749  3749 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
,03-21 07:32:42.216  3598  3598 I com.dropbox.sync.android.ad: Dropbox initialized for application: hizqkiq3952astb (com.dropbox.android/240408 DropboxSync/2.0.2 (Android; 5.0.2; samsung SM-A300FU armeabi-v7a; en_US))
,03-21 07:32:42.216  1019  1499 W ActivityManager: userId = 0, bbcId = -10000
03-21 07:32:42.216  1019  1499 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-21 07:32:42.216  1019  1499 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,03-21 07:32:42.236  2044  2044 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 440x330
,03-21 07:32:42.236  2044  2044 I GFX GPU raster: eglCreateImageKHR: EGL_SUCCESS
,03-21 07:32:42.236  2044  2044 I glCompressedTexImage2D: took 0.334948ms for 440*116864 texture 37809
03-21 07:32:42.236  2044  2044 I draw setup: took 0.892083ms for 440*330 texture 37809
03-21 07:32:42.236  2044  2044 E GFX GPU raster: drawn
,03-21 07:32:42.246  2044  2044 I GFX GPU raster ASTC: took 5.077031ms for 440*330 texture 12
03-21 07:32:42.246  2044  2044 I GFX raster: took 5.170260ms for 440*330 texture 0
03-21 07:32:42.246  2044  2044 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8383988 bitmapCt=12 bitmapW=440 bitmapH=330 BitmapInternalFormat=93b1, Counterpart=0xb8398520 counterpartCT=4 counterpartW=440 counterparth=330
,03-21 07:32:42.286  3841  3945 I Velvet.VelvetFactory: refreshing internal icing corpora
,03-21 07:32:42.286  3841  3945 I ContactAccountLoggerTas: canRun() : Opted Out
,03-21 07:32:42.296  1019  1809 W ActivityManager: userId = 0, bbcId = -10000
,03-21 07:32:42.296  1019  1809 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-21 07:32:42.296  1019  1809 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,03-21 07:32:42.296  3823  3823 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(191/xdmInitExternalStorageState)] 
,03-21 07:32:42.296  2044  2044 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 480x640
,03-21 07:32:42.296  2044  2044 I GFX GPU raster: eglCreateImageKHR: EGL_SUCCESS
03-21 07:32:42.306  2044  2044 I glCompressedTexImage2D: took 0.501302ms for 480*163840 texture 37811
03-21 07:32:42.306  2044  2044 I draw setup: took 0.919584ms for 480*640 texture 37811
03-21 07:32:42.306  2044  2044 E GFX GPU raster: drawn
03-21 07:32:42.306  3823  3849 I DBG_POLICYDM: [com.policydm.agent.XDMTask(163/xdmAgentTaskHandler)] XEVENT_OS_INITIALIZED
,03-21 07:32:42.306  2044  2044 I GFX GPU raster ASTC: took 6.480001ms for 480*640 texture 12
03-21 07:32:42.306  2044  2044 I GFX raster: took 6.564011ms for 480*640 texture 0
03-21 07:32:42.306  2044  2044 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8383560 bitmapCt=12 bitmapW=480 bitmapH=640 BitmapInternalFormat=93b3, Counterpart=0xb8397808 counterpartCT=4 counterpartW=480 counterparth=640
,03-21 07:32:42.316  3823  3849 I DBG_POLICYDM: [com.policydm.agent.XDMAgent(156/xdmAgentSetSyncMode)] nSync = 0
,03-21 07:32:42.316  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
03-21 07:32:42.316  1019  1032 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-21 07:32:42.316  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,03-21 07:32:42.326  3823  3823 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(390/xdmGetExternalSDCardPath)] External SD Card Path : /storage/extSdCard
,03-21 07:32:42.326  3823  3823 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(248/xdmInitExternalStorageState)] DATA_DIR_PATH [/data]
,03-21 07:32:42.326  3823  3823 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(249/xdmInitExternalStorageState)] EXTERNAL_DIR_PATH [/storage/emulated/0]
,03-21 07:32:42.326  3823  3823 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(250/xdmInitExternalStorageState)] EXTERNAL_SD_DIR_PATH [/storage/extSdCard]
,03-21 07:32:42.336  3823  3823 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(251/xdmInitExternalStorageState)] POLICY_DIR_PATH [/data/user/0/com.policydm/cache]
,03-21 07:32:42.336  3823  3823 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(253/xdmInitExternalStorageState)] bExternalStorageAvailable [true]
,03-21 07:32:42.346  3841  3945 I Velvet.VelvetFactory: refreshing search history.
,03-21 07:32:42.346  3823  3823 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(254/xdmInitExternalStorageState)] bExternalSDStorageAvailable [false]
,03-21 07:32:42.346  3823  3823 I DBG_POLICYDM: [com.policydm.XDMApplication(580/xdmWakeLockRelease)] 
,03-21 07:32:42.346  3823  3823 I DBG_POLICYDM: [com.policydm.XDMApplication(585/xdmWakeLockRelease)] m_WakeLock is release!!
,03-21 07:32:42.346  3823  3823 I DBG_POLICYDM: [com.policydm.XDMApplication(179/onCreate)] DMApplication Start !
,03-21 07:32:42.356  2044  2044 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
,03-21 07:32:42.356  2044  2044 I GFX construct_block_size_descriptor_2d second part: took 2.338125ms for 0*0 texture 0
,03-21 07:32:42.366  3823  3849 I DBG_POLICYDM: [com.policydm.db.XDB(1531/xdbDMffs_Init)] xdbDMffs_Init
,03-21 07:32:42.366  3078  3078 D elm:15121: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
03-21 07:32:42.366  2044  2044 I GFX generate_partition_tables: took 7.491042ms for 0*0 texture 0
03-21 07:32:42.366  1019  1571 W ActivityManager: userId = 0, bbcId = -10000
03-21 07:32:42.366  1019  1571 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-21 07:32:42.366  1019  1571 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
03-21 07:32:42.366  2044  2044 I GFX raster: took 11.837708ms for 176*144 texture 0
03-21 07:32:42.366  2044  2044 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8397808 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b2, Counterpart=0xb83984c8 counterpartCT=4 counterpartW=176 counterparth=144
03-21 07:32:42.376  3078  3078 D elm:15121: ELMAbstractReceiver : Receive Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,03-21 07:32:42.376  3899  3899 I DBG_FMMDM: [50.20.150420][Line:608][xdmGetCheckWifiOnlyModel] isWifiOnly : false
,03-21 07:32:42.376  3078  3078 D elm:15121: ElmAgentService : onCreate()
,03-21 07:32:42.376  3078  3959 D elm:15121: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,03-21 07:32:42.386  3078  3078 D elm:15121: ELMEngine.ServiceHandler.handleMessage( BOOT_COMPLETED ). 
,03-21 07:32:42.386  3078  3078 D elm:15121: BootCompletedState : startBootCompleted() call
,03-21 07:32:42.386  3078  3078 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,03-21 07:32:42.386  3078  3078 I elm:15121: Get License : 0
,03-21 07:32:42.386  3078  3078 D elm:15121: ElmAgentService : onDestroy().
,03-21 07:32:42.386  1019  1395 I ActivityManager: Killing 3040:com.qualcomm.timeservice/1000 (adj 15): empty #31
,03-21 07:32:42.386  1443  1443 V EmergencyMode: [EmergencyReceiver] EmergencyReceiver [android.intent.action.BOOT_COMPLETED]
,03-21 07:32:42.396  2044  2044 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
,03-21 07:32:42.406  2044  2044 I GFX construct_block_size_descriptor_2d second part: took 2.600781ms for 0*0 texture 0
,03-21 07:32:42.416  2044  2044 I GFX generate_partition_tables: took 6.227448ms for 0*0 texture 0
,03-21 07:32:42.416  2044  2044 I GFX raster: took 11.088593ms for 176*144 texture 0
03-21 07:32:42.416  2044  2044 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb83984c8 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b1, Counterpart=0xb83839c0 counterpartCT=4 counterpartW=176 counterparth=144
,03-21 07:32:42.416  2044  2044 D ScoverManager: registerListener
,03-21 07:32:42.416  1019  1499 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
,03-21 07:32:42.416  1019  1805 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
,03-21 07:32:42.416  1019  1805 D CoverManager.StateNotifier: registerListenerCallback : binder = android.os.BinderProxy@50e1a5b, pid : 2044, uid : 1001, type : 1
,03-21 07:32:42.426  3899  3899 I DBG_FMMDM: [50.20.150420][Line:27][xdmInitialize] AgVOOqV7UpXFblBk29Ld3aZrOQhtHCYbjdszx6nYrjFYzeVOvvlPUzE67GnQVups
,03-21 07:32:42.426  3899  3899 I DBG_FMMDM: [50.20.150420][Line:28][xdmInitialize] c8aaBoNX+zCI65M7gVNTej45+K/MzxjqVpKd5x0FMtd3o63nokSujfTEanrHiU41
,03-21 07:32:42.426  3899  3899 I DBG_FMMDM: [50.20.150420][Line:29][xdmInitialize] X2Nl5mgTWVn0/a90MNBgtYshxOiQq2MqI4oMf2Nwz6I=
,03-21 07:32:42.426  1019  1531 W ActivityManager: userId = 0, bbcId = -10000
03-21 07:32:42.426  1019  1531 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-21 07:32:42.426  1019  1531 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,03-21 07:32:42.436  2044  2044 D InCall  : InCallPresenter -  - Finished InCallPresenter.setUp
,03-21 07:32:42.436  1019  1564 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 07:32:42.436  1019  1564 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 07:32:42.436  1019  1564 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 07:32:42.446  1019  1564 E ActivityManager: checkUser: useridlist=null, currentuser=0,
,03-21 07:32:42.466  3969  3969 E Zygote  : MountEmulatedStorage()
,03-21 07:32:42.466  3969  3969 E Zygote  : v2
03-21 07:32:42.466  3969  3969 I libpersona: KNOX_SDCARD checking this for 1000
03-21 07:32:42.466  3969  3969 I libpersona: KNOX_SDCARD not a persona
,03-21 07:32:42.466  3969  3969 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-21 07:32:42.476  3969  3969 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
03-21 07:32:42.476  3969  3969 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-21 07:32:42.476  3823  3849 I DBG_POLICYDM: [com.policydm.agent.XDMTask(171/xdmAgentTaskHandler)] XEVENT_DM_INIT
03-21 07:32:42.476  1019  1564 I ActivityManager: Start proc com.sec.pcw.device for content provider com.sec.pcw.device/.contentprovider.DMProvider: pid=3969 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-21 07:32:42.476  3823  3849 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
03-21 07:32:42.476  1019  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_3040/cgroup.procs: No such file or directory
,03-21 07:32:42.486  1019  1031 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,03-21 07:32:42.486  3823  3849 I DBG_POLICYDM: [com.policydm.XDMApplication(619/xdmGetNotibarState)] get NotibarState : 7
,03-21 07:32:42.486  3823  3849 I DBG_POLICYDM: [com.policydm.ui.XUINotificationManager(48/xuiSetIndicator)] Indicator id : 7
,03-21 07:32:42.486  3823  3849 I DBG_POLICYDM: [com.policydm.XDMApplication(611/xdmSetNotibarState)] set NotibarState : 7
,03-21 07:32:42.496  1019  1804 I ActivityManager: Killing 2788:com.sec.spp.push/u0a32 (adj 15): empty #31
,03-21 07:32:42.496  3598  3958 I System.out: Thread-494(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
03-21 07:32:42.496  3598  3958 I System.out: Thread-494(ApacheHTTPLog):isSBSettingEnabled false
03-21 07:32:42.496  3598  3958 I System.out: Thread-494(ApacheHTTPLog):isShipBuild true
03-21 07:32:42.496  3598  3958 I System.out: Thread-494(ApacheHTTPLog):SMARTBONDING_ENABLED is false
03-21 07:32:42.496  3598  3958 I System.out: Thread-494(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,03-21 07:32:42.496   280  1006 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
03-21 07:32:42.496   280  1006 D Netd    : getNetworkForDns: using netid 502 for uid 10088
,03-21 07:32:42.506  3823  3849 I DBG_POLICYDM: [com.policydm.db.XDBAESCrypt(217/xdbGetCryptionkey)] try read dbString
,03-21 07:32:42.506  3969  3969 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-21 07:32:42.506  3969  3969 D ActivityThread: Added TimaKeyStore provider
,03-21 07:32:42.516  3823  3849 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(428/xdbGetFUMOStatus)] xdbGetFUMOStatus : 0
,03-21 07:32:42.526  3823  3849 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(587/xdbGetFUMOInitiatedType)] Initiated Type: 0
,03-21 07:32:42.526  3823  3849 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(72/xpollingCheckVersionInfo)] 
,03-21 07:32:42.526  3823  3849 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(271/xpollingCheckTimer)] 
,03-21 07:32:42.526  3823  3850 I DBG_POLICYDM: [com.policydm.agent.XDMUITask(191/xdmUIEvent)] XUI_DM_IDLE_STATE :true
,03-21 07:32:42.536  1019  1805 W ActivityManager: userId = 0, bbcId = -10000
03-21 07:32:42.536  1019  1805 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-21 07:32:42.536  1019  1805 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
03-21 07:32:42.536  3823  3850 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,03-21 07:32:42.536  1019  1031 W ActivityManager: userId = 0, bbcId = -10000
03-21 07:32:42.536  1019  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-21 07:32:42.536  1019  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,03-21 07:32:42.546  3823  3849 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(285/xpollingCheckTimer)] savedpollingtime : 2016/03/27/17:27:56
,03-21 07:32:42.546  3823  3849 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(286/xpollingCheckTimer)] currentTime : 2016/03/21/07:32:42
,03-21 07:32:42.546  3823  3849 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(290/xpollingCheckTimer)] Restart Timer..
,03-21 07:32:42.546  3823  3849 I DBG_POLICYDM: [com.policydm.XDMApplication(626/xdmStartAlarm)] Alarm ID: 0
,03-21 07:32:42.546  1019  1809 I ActivityManager: Killing 3095:com.sec.android.widgetapp.SPlannerAppWidget/u0a130 (adj 15): empty #31
,03-21 07:32:42.556  3823  3850 I DBG_POLICYDM: [com.policydm.db.XDBProfileListAdp(258/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,03-21 07:32:42.556  1019  1043 W libprocessgroup: failed to open /acct/uid_10032/pid_2788/cgroup.procs: No such file or directory
03-21 07:32:42.556  3823  3850 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(399/xnotiPushAdpExcuteResumeNoti)] nSessionSaveState:0
03-21 07:32:42.556  3823  3850 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(400/xnotiPushAdpExcuteResumeNoti)] nNotiUiEvent:0
03-21 07:32:42.556  3823  3850 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(401/xnotiPushAdpExcuteResumeNoti)] nNotiRetryCount:0
03-21 07:32:42.556  3823  3850 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(441/xnotiPushAdpExcuteResumeNoti)] Current NOTI NOT SAVED State. EXIT.
03-21 07:32:42.556  3823  3850 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(267/xnotiPushAdpClearSessionStatus)] 
,03-21 07:32:42.566  3823  3850 I DBG_POLICYDM: [com.policydm.ui.XUIAdapter(39/xuiAdpSetUiMode)] nDmUiMode : 0,
03-21 07:32:42.566  1019  1283 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,03-21 07:32:42.566  3823  3850 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(439/xdbSetFUMOStatus)] xdbSetFUMOStatus : 0
,03-21 07:32:42.576  3969  3969 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
03-21 07:32:42.576  3969  3969 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
03-21 07:32:42.576  3969  3969 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,03-21 07:32:42.576  3823  3849 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(312/xPollingReportReStartAlarm)] 
,03-21 07:32:42.576  1019  1804 W ActivityManager: userId = 0, bbcId = -10000
03-21 07:32:42.576  1019  1804 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-21 07:32:42.576  1019  1804 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,03-21 07:32:42.576  1019  1531 W ActivityManager: userId = 0, bbcId = -10000
03-21 07:32:42.576  1019  1531 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-21 07:32:42.576  1019  1531 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,03-21 07:32:42.586  3749  4000 W MessageQueue: Handler (android.os.Handler) {2fc73c8f} sending message to a Handler on a dead thread
03-21 07:32:42.586  3749  4000 W MessageQueue: java.lang.IllegalStateException: Handler (android.os.Handler) {2fc73c8f} sending message to a Handler on a dead thread
03-21 07:32:42.586  3749  4000 W MessageQueue: 	at android.os.MessageQueue.enqueueMessage(MessageQueue.java:325)
03-21 07:32:42.586  3749  4000 W MessageQueue: 	at android.os.Handler.enqueueMessage(Handler.java:631)
03-21 07:32:42.586  3749  4000 W MessageQueue: 	at android.os.Handler.sendMessageAtTime(Handler.java:600)
03-21 07:32:42.586  3749  4000 W MessageQueue: 	at android.os.Handler.sendMessageDelayed(Handler.java:570)
03-21 07:32:42.586  3749  4000 W MessageQueue: 	at android.os.Handler.post(Handler.java:326)
03-21 07:32:42.586  3749  4000 W MessageQueue: 	at ffw.a(SourceFile:327)
03-21 07:32:42.586  3749  4000 W MessageQueue: 	at guw.a(SourceFile:120)
03-21 07:32:42.586  3749  4000 W MessageQueue: 	at guf.c(SourceFile:26)
03-21 07:32:42.586  3749  4000 W MessageQueue: 	at gui.run(SourceFile:297)
03-21 07:32:42.586  3749  4000 W MessageQueue: 	at android.os.Handler.handleCallback(Handler.java:739)
03-21 07:32:42.586  3749  4000 W MessageQueue: 	at android.os.Handler.dispatchMessage(Handler.java:95)
03-21 07:32:42.586  3749  4000 W MessageQueue: 	at android.os.Looper.loop(Looper.java:145)
03-21 07:32:42.586  3749  4000 W MessageQueue: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-21 07:32:42.586  3969  3996 D PCWCLIENTTRACE_DMContentProvider: [URIMatcher] - result : 2
,03-21 07:32:42.596  3899  3899 I DBG_FMMDM: [50.20.150420][Line:40][onCreate] FMMApplication NOT Start !
03-21 07:32:42.596  3899  3899 I DBG_FMMDM: [50.20.150420][Line:67][onReceive] android.intent.action.BOOT_COMPLETED
03-21 07:32:42.596  3899  3899 I DBG_FMMDM: [50.20.150420][Line:309][onReceive] android.intent.action.BOOT_COMPLETED
,03-21 07:32:42.596  1019  1395 E ActivityManager: checkUser: useridlist=null, currentuser=0,
03-21 07:32:42.596  1019  1395 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:42.596  1019  1395 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:42.596  1019  1395 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 07:32:42.606  4002  4002 E Zygote  : MountEmulatedStorage(),
03-21 07:32:42.606  4002  4002 I libpersona: KNOX_SDCARD checking this for 1000
03-21 07:32:42.606  4002  4002 E Zygote  : v2
03-21 07:32:42.606  4002  4002 I libpersona: KNOX_SDCARD not a persona
,03-21 07:32:42.616  1019  1395 I ActivityManager: Start proc com.fmm.ds for broadcast com.fmm.ds/.XDSBroadcastReceiver: pid=4002 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-21 07:32:42.616  1019  1395 I ActivityManager: Killing 2615:com.android.calendar/u0a131 (adj 15): empty #31
03-21 07:32:42.616  1019  1395 I ActivityManager: Killing 2993:com.android.providers.calendar/u0a37 (adj 15): empty #32
,03-21 07:32:42.616  2021  2021 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.qualcomm.qti.services.secureui.BootReceiver.onReceive:30 android.app.ActivityThread.handleReceiver:3125 
,03-21 07:32:42.626  1019  1499 W ActivityManager: userId = 0, bbcId = -10000
03-21 07:32:42.626  1019  1499 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-21 07:32:42.626  1019  1499 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.qualcomm.qti.services.secureui:sui_service, destAppInfo.processName = com.qualcomm.qti.services.secureui:sui_service
,03-21 07:32:42.626  2021  2021 D SecUISvc: Service started flags 0 startId 1
,03-21 07:32:42.626  1019  1571 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:42.626  1019  1571 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:42.636  2021  4008 D SecUISvc: Thread created.
03-21 07:32:42.626  1019  1571 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:42.626  1019  1571 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 07:32:42.636  4002  4002 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-21 07:32:42.646  4002  4002 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-21 07:32:42.646  4002  4002 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-21 07:32:42.656  4014  4014 E Zygote  : MountEmulatedStorage(),
,03-21 07:32:42.656  3823  3850 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(565/xdbSetFUMOInitiatedType)] Initiated Type: 0
03-21 07:32:42.656  1443  1443 V EmergencyMode: [EmergencyBase] setBootTime
03-21 07:32:42.656  1443  1443 V EmergencyMode: [EmergencyFactory] No Recovery State, kill my self.
03-21 07:32:42.666  1019  1571 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=4014 uid=10026 gids={50026, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-21 07:32:42.666  4014  4014 E Zygote  : v2
03-21 07:32:42.666  4014  4014 I libpersona: KNOX_SDCARD checking this for 10026
03-21 07:32:42.666  4014  4014 I libpersona: KNOX_SDCARD not a persona
,03-21 07:32:42.666  4014  4014 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-21 07:32:42.666  4014  4014 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-21 07:32:42.666  1019  1561 I ActivityManager: Killing 3184:com.android.keychain/1000 (adj 15): empty #31
03-21 07:32:42.666  4014  4014 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-21 07:32:42.676  1019  1571 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:42.676  1019  1571 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:42.676  1019  1571 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:42.676  1019  1571 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 07:32:42.676  1019  1043 W libprocessgroup: failed to open /acct/uid_10130/pid_3095/cgroup.procs: No such file or directory
,03-21 07:32:42.686  4002  4002 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-21 07:32:42.686  4002  4002 D ActivityThread: Added TimaKeyStore provider
,03-21 07:32:42.696  4034  4034 E Zygote  : MountEmulatedStorage(),
03-21 07:32:42.696  4034  4034 E Zygote  : v2
03-21 07:32:42.696  4034  4034 I libpersona: KNOX_SDCARD checking this for 1000
03-21 07:32:42.696  4034  4034 I libpersona: KNOX_SDCARD not a persona
03-21 07:32:42.696  4034  4034 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
03-21 07:32:42.696  1019  1571 I ActivityManager: Start proc com.sec.factory.camera for broadcast com.sec.factory.camera/com.sec.android.app.camerafirmware.CameraFirmwareBroadCastReceiver: pid=4034 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,03-21 07:32:42.696  4034  4034 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-21 07:32:42.696  4034  4034 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-21 07:32:42.706  4014  4014 D TimaKeyStoreProvider: TimaSignature is unavailable
03-21 07:32:42.706  4014  4014 D ActivityThread: Added TimaKeyStore provider
03-21 07:32:42.706  3823  3850 I DBG_POLICYDM: [com.policydm.db.XDB(1825/xdbSetBackUpServerUrl)] 
,03-21 07:32:42.706  1019  1531 W ActivityManager: userId = 0, bbcId = -10000
03-21 07:32:42.706  1019  1531 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-21 07:32:42.706  1019  1531 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,03-21 07:32:42.716  1019  1138 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,03-21 07:32:42.726  4034  4034 D TimaKeyStoreProvider: TimaSignature is unavailable
03-21 07:32:42.726  4034  4034 D ActivityThread: Added TimaKeyStore provider
03-21 07:32:42.726  1019  1531 I AudioService: getStreamVolume 3 index 0
03-21 07:32:42.726  3841  3841 I MediaRouter: Found default route: MediaRouter.RouteInfo{ uniqueId=android/mo:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,03-21 07:32:42.746  3841  3957 I ContactAccountLoggerTas: canRun() : Opted Out
03-21 07:32:42.746  3841  3957 I ContactAccountLoggerTas: canRun() : Opted Out
,03-21 07:32:42.746  3823  3849 I DBG_POLICYDM: [com.policydm.XDMApplication(626/xdmStartAlarm)] Alarm ID: 1
,03-21 07:32:42.756  3841  3945 I WebViewFactory: Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,03-21 07:32:42.756  3841  3957 I ContactAccountLoggerTas: canRun() : Opted Out
,03-21 07:32:42.766  3841  3945 I LibraryLoader: Loading: webviewchromium
,03-21 07:32:42.766  3841  3945 I LibraryLoader: Time to load native libraries: 5 ms (timestamps 2912-2917)
03-21 07:32:42.766  3841  3945 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-21 07:32:42.776  3841  3841 I FavoriteContactNamesSup: get() : Execute runnable (UI thread)
,03-21 07:32:42.776  3841  3841 I ContactLabelSupplier: get() : Execute runnable (UI thread)
,03-21 07:32:42.786  1019  1043 W libprocessgroup: failed to open /acct/uid_10037/pid_2993/cgroup.procs: No such file or directory
03-21 07:32:42.786  1019  1043 W libprocessgroup: failed to open /acct/uid_10131/pid_2615/cgroup.procs: No such file or directory
03-21 07:32:42.786  1019  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_3184/cgroup.procs: No such file or directory
,03-21 07:32:42.806  4002  4002 I DBG_FMMDS: [50.18.150420][Line:56][onCreate] FMMDS Application Start
,03-21 07:32:42.806  4034  4034 I CameraApp: CameraApp.onCreate()... mFeature : null
03-21 07:32:42.806  4034  4034 I testFeature: Feature.Feature(context)
03-21 07:32:42.806  4034  4034 I testFeature: Feature.readInternalDefaultXml()
03-21 07:32:42.806  4034  4034 I testFeature: ResetFeatureValue
,03-21 07:32:42.806  4002  4002 I DBG_FMMDS: [50.18.150420][Line:28][<init>] XDBHelper First Call!!!
,03-21 07:32:42.816  4034  4034 I CameraFirmware_broadcast: CameraFirmwareBroadCastReceiver...
03-21 07:32:42.816  4034  4034 I CameraApp: CameraApp.getAppFeature()...
,03-21 07:32:42.816  1019  1561 W ActivityManager: userId = 0, bbcId = -10000
03-21 07:32:42.816  1019  1561 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-21 07:32:42.816  1019  1561 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
,03-21 07:32:42.816  1999  1999 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 07:32:42.826  1019  1138 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 07:32:42.826  1019  1138 E ActivityManager: checkUser: useridlist=null, currentuser=0,
03-21 07:32:42.826  1999  1999 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
03-21 07:32:42.826  1019  1138 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:42.826  1019  1138 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 07:32:42.836  4053  4053 E Zygote  : MountEmulatedStorage()
03-21 07:32:42.836  4053  4053 I libpersona: KNOX_SDCARD checking this for 10095
03-21 07:32:42.836  4053  4053 E Zygote  : v2
03-21 07:32:42.836  4053  4053 I libpersona: KNOX_SDCARD not a persona
,03-21 07:32:42.836  4053  4053 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,03-21 07:32:42.846  4053  4053 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-21 07:32:42.846  4053  4053 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-21 07:32:42.856  1019  1138 I ActivityManager: Start proc com.samsung.android.provider.filterprovider for broadcast com.samsung.android.provider.filterprovider/.FilterProviderReceiver: pid=4053 uid=10095 gids={50095, 9997, 1023} abi=armeabi-v7a
,03-21 07:32:42.856  3969  3996 D PCWCLIENTTRACE_DMContentProvider: [URIMatcher] - result : 2
,03-21 07:32:42.866  4002  4002 E DBG_FMMDS: Warning!!! [50.18.150420][Line:36][xdsDevAdpGetDeviceID] DeviceID read fail!!!!!!!!
,03-21 07:32:42.876  4053  4053 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-21 07:32:42.886  4053  4053 D ActivityThread: Added TimaKeyStore provider
,03-21 07:32:42.886  4002  4002 I DBG_FMMDS: [50.18.150420][Line:43][xdbDBInit] 
,03-21 07:32:42.896  3749  3990 D AndroidHttpClient: [NALSECURITY] isMmsRequest() : CoreProtocolPNames.USER_AGENT = Dalvik/2.1.0 (Linux; U; Android 5.0.2; SM-A300FU Build/LRX22G)
,03-21 07:32:42.896  3749  3990 D AndroidHttpClient: [NALSECURITY] checkMmsSendPermission() : isMmsRequest() = false method = GET
03-21 07:32:42.896  3841  3945 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-21 07:32:42.896  3749  3990 I System.out: Thread-579(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,03-21 07:32:42.906  3749  3990 I System.out: Thread-579(ApacheHTTPLog):isSBSettingEnabled false
,03-21 07:32:42.906  1019  1804 I art     : Explicit concurrent mark sweep GC freed 28322(1470KB) AllocSpace objects, 4(985KB) LOS objects, 33% free, 23MB/35MB, paused 2.638ms total 147.905ms
,03-21 07:32:42.906  3749  3990 I System.out: Thread-579(ApacheHTTPLog):isShipBuild true
03-21 07:32:42.906  3749  3990 I System.out: Thread-579(ApacheHTTPLog):SMARTBONDING_ENABLED is false
,03-21 07:32:42.906  3749  3990 I System.out: Thread-579(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,03-21 07:32:42.916   280  1006 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
03-21 07:32:42.916   280  1006 D Netd    : getNetworkForDns: using netid 502 for uid 10161
,03-21 07:32:42.916  3823  3849 I DBG_POLICYDM: [com.policydm.agent.XDMTask(203/xdmAgentTaskHandler)] XEVENT_DM_INIT : Initialized
,03-21 07:32:42.916  1019  1564 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 07:32:42.916  1019  1564 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 07:32:42.916  1019  1564 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 07:32:42.916  1019  1564 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 07:32:42.926  4074  4074 E Zygote  : MountEmulatedStorage()
03-21 07:32:42.926  4074  4074 E Zygote  : v2
03-21 07:32:42.926  4074  4074 I libpersona: KNOX_SDCARD checking this for 10055
03-21 07:32:42.926  4074  4074 I libpersona: KNOX_SDCARD not a persona
,03-21 07:32:42.936  4074  4074 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-21 07:32:42.936  4074  4074 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,03-21 07:32:42.936  4074  4074 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-21 07:32:42.936  1019  1564 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=4074 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
,03-21 07:32:42.956  3702  3811 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 0 sec
,03-21 07:32:42.956  4074  4074 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-21 07:32:42.956  4074  4074 D ActivityThread: Added TimaKeyStore provider
,03-21 07:32:42.956  3841  4085 I UpdateIcingCorporaServi: Updating corpora: APPS=MAYBE, CONTACTS=MAYBE
03-21 07:32:42.966  1019  1809 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,03-21 07:32:42.966  3823  3850 I DBG_POLICYDM: [com.policydm.db.XDBProfileAdp(207/xdbSetChangedProtocol)] xdbSetChangedProtocol : false
,03-21 07:32:42.976  4053  4053 D PreloadFilterInstaller: uses FILTER_DB_VER_1
,03-21 07:32:42.986  1019  1032 E Tethering: No numeric data
,03-21 07:32:42.986  4014  4014 I Finsky  : [1] com.google.android.finsky.FinskyApp.onCreate(358): Initializing network with DFE https://android.clients.google.com/fdfe/
,03-21 07:32:43.006  1019  1499 W ActivityManager: userId = 0, bbcId = -10000
,03-21 07:32:43.006  1019  1499 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-21 07:32:43.006  1019  1499 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-21 07:32:43.006  1019  1805 E Tethering: No numeric data
,03-21 07:32:43.016  1019  1502 E Tethering: No numeric data
,03-21 07:32:43.016  1019  1630 E Tethering: No numeric data
,03-21 07:32:43.016  1019  1809 W ActivityManager: userId = 0, bbcId = -10000
,03-21 07:32:43.016  1019  1809 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-21 07:32:43.016  1019  1809 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
,03-21 07:32:43.016  1019  1283 E Tethering: No numeric data
,03-21 07:32:43.016  4002  4002 I DBG_FMMDS: [50.18.150420][Line:63][onCreate] onCreate Db Initialized
,03-21 07:32:43.026  1019  1805 E Tethering: No numeric data
,03-21 07:32:43.046  3823  3850 I DBG_POLICYDM: [com.policydm.db.XDBProfileListAdp(258/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,03-21 07:32:43.046  4002  4002 I DBG_FMMDS: [50.18.150420][Line:363][xdsGetAccount] UZnlD2ITkPmcCbh9srjpN/1auPpXZ1U0673eFrlr5G7ujCmOnoTUvn8Wy3q3+o8W
,03-21 07:32:43.046  4002  4002 I DBG_FMMDS: [50.18.150420][Line:279][xdsDefaultProfileCheckServerID] VG44Fy9kdMk+/k3D4uP4d3do/3rw5AoymvTy0wXAnzc=
,03-21 07:32:43.056  4002  4002 I DBG_FMMDS: [50.18.150420][Line:363][xdsGetAccount] UZnlD2ITkPmcCbh9srjpN/1auPpXZ1U0673eFrlr5G7ujCmOnoTUvn8Wy3q3+o8W
,03-21 07:32:43.056  4002  4002 I DBG_FMMDS: [50.18.150420][Line:376][xdsCheckSamsungAccountForChina] VG44Fy9kdMk+/k3D4uP4d3do/3rw5AoymvTy0wXAnzc=
,03-21 07:32:43.056  4002  4002 I DBG_FMMDS: [50.18.150420][Line:89][onReceive] Receive Intent : android.intent.action.BOOT_COMPLETED
,03-21 07:32:43.056  4053  4053 E SQLiteLog: (284) automatic index on titles(filter_id)
,03-21 07:32:43.056  4002  4002 I DBG_FMMDS: [50.18.150420][Line:248][onReceive] XCOMMON_INTENT_NOTI_CALLLOG_CLICK
,03-21 07:32:43.056   290   290 E SMD     : DCD OFF
,03-21 07:32:43.066  3823  3850 I DBG_POLICYDM: [com.policydm.db.XDBNotiAdp(38/xdbNotiExistInfo)] Noti Exist : false
,03-21 07:32:43.076  1337  3685 D [SBeam] : SBeamEnabler.isSBeamSupported : [-1]
,03-21 07:32:43.076  1337  3685 D [SBeam] : SBeamEnabler.isSBeamSupported : EXIST
,03-21 07:32:43.076  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
03-21 07:32:43.076  1019  1032 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-21 07:32:43.076  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-21 07:32:43.086  4053  4053 I FilterProviderReceiver: onReceive in FilterProviderReceiver
03-21 07:32:43.086  4053  4053 I FilterProviderReceiver: onReceive in FilterProviderReceiver when ACTION_BOOT_COMPLETED
,03-21 07:32:43.086  1019  1395 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:43.086  1019  1395 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:43.086  1019  1395 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:43.086  1019  1395 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 07:32:43.106  4106  4106 E Zygote  : MountEmulatedStorage()
03-21 07:32:43.106  4106  4106 E Zygote  : v2
03-21 07:32:43.106  4106  4106 I libpersona: KNOX_SDCARD checking this for 10098
03-21 07:32:43.106  4106  4106 I libpersona: KNOX_SDCARD not a persona
,03-21 07:32:43.106  4106  4106 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-21 07:32:43.106  4074  4074 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,03-21 07:32:43.106  4106  4106 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-21 07:32:43.106  4106  4106 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-21 07:32:43.116  1019  1395 I ActivityManager: Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=4106 uid=10098 gids={50098, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,03-21 07:32:43.116  1019  1499 I ActivityManager: Killing 3238:com.sec.android.gallery3d/u0a39 (adj 15): empty #31
03-21 07:32:43.116  1019  1499 I ActivityManager: Killing 2711:com.android.chrome/u0a77 (adj 15): empty #32
,03-21 07:32:43.146  1019  1564 E Tethering: No numeric data
,03-21 07:32:43.146  4106  4106 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-21 07:32:43.146  3864  3864 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
03-21 07:32:43.146  4106  4106 D ActivityThread: Added TimaKeyStore provider
,03-21 07:32:43.156  1019  1804 E Tethering: No numeric data
,03-21 07:32:43.156  3864  3864 I FOTA_Client: [com.sec.android.fotaclient.FotaUpdaterReceiver(93/onReceive)] Auto update settings is activated
,03-21 07:32:43.156  1019  1032 E Tethering: No numeric data
,03-21 07:32:43.156  3864  3864 I FOTA_Client: [IlIlIIllllIllIIIIIll(81/llllIIIllIlIIIIllllI)] Polling time is vaild
,03-21 07:32:43.166  1019  1395 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
,03-21 07:32:43.166  1019  1395 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,03-21 07:32:43.176  3864  3864 W FOTA_Client: [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,03-21 07:32:43.176  1019  1395 F AccountManagerService: Account Manager Crash
03-21 07:32:43.176  1019  1395 F AccountManagerService: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
03-21 07:32:43.176  1019  1395 F AccountManagerService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
03-21 07:32:43.176  1019  1395 F AccountManagerService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:725)
03-21 07:32:43.176  1019  1395 F AccountManagerService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
03-21 07:32:43.176  1019  1395 F AccountManagerService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
03-21 07:32:43.176  1019  1395 F AccountManagerService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:510)
03-21 07:32:43.176  1019  1395 F AccountManagerService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:421)
03-21 07:32:43.176  1019  1395 F AccountManagerService: 	at com.android.server.accounts.AccountManagerService.invalidateAuthToken(AccountManagerService.java:1400)
03-21 07:32:43.176  1019  1395 F AccountManagerService: 	at android.accounts.IAccountManager$Stub.onTransact(IAccountManager.java:233)
03-21 07:32:43.176  1019  1395 F AccountManagerService: 	at com.android.server.accounts.AccountManagerService.onTransact(AccountManagerService.java:322)
03-21 07:32:43.176  1019  1395 F AccountManagerService: 	at android.os.Binder.execTransact(Binder.java:461)
,03-21 07:32:43.176  1019  1395 E JavaBinder: *** Uncaught remote exception!  (Exceptions are not yet supported across processes.)
03-21 07:32:43.176  1019  1395 E JavaBinder: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
03-21 07:32:43.176  1019  1395 E JavaBinder: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
03-21 07:32:43.176  1019  1395 E JavaBinder: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:725)
03-21 07:32:43.176  1019  1395 E JavaBinder: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
03-21 07:32:43.176  1019  1395 E JavaBinder: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
03-21 07:32:43.176  1019  1395 E JavaBinder: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:510)
03-21 07:32:43.176  1019  1395 E JavaBinder: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:421)
03-21 07:32:43.176  1019  1395 E JavaBinder: 	at com.android.server.accounts.AccountManagerService.invalidateAuthToken(AccountManagerService.java:1400)
03-21 07:32:43.176  1019  1395 E JavaBinder: 	at android.accounts.IAccountManager$Stub.onTransact(IAccountManager.java:233)
03-21 07:32:43.176  1019  1395 E JavaBinder: 	at com.android.server.accounts.AccountManagerService.onTransact(AccountManagerService.java:322)
03-21 07:32:43.176  1019  1395 E JavaBinder: 	at android.os.Binder.execTransact(Binder.java:461)
,03-21 07:32:43.176  1019  1561 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:43.176  1019  1561 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:43.176  1019  1561 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:32:43.176  1019  1561 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 07:32:43.196  4121  4121 E Zygote  : MountEmulatedStorage()
03-21 07:32:43.196  4121  4121 E Zygote  : v2
03-21 07:32:43.196  4121  4121 I libpersona: KNOX_SDCARD checking this for 10013
03-21 07:32:43.196  4121  4121 I libpersona: KNOX_SDCARD not a persona
,03-21 07:32:43.196  4121  4121 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,03-21 07:32:43.196  4121  4121 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
03-21 07:32:43.196  1019  1561 I ActivityManager: Start proc com.google.android.onetimeinitializer for broadcast com.google.android.onetimeinitializer/.OneTimeInitializerReceiver: pid=4121 uid=10013 gids={50013, 9997} abi=armeabi-v7a,
03-21 07:32:43.196  1019  1044 E DropBoxManagerService: Can't write: system_server_wtf,
03-21 07:32:43.196  1019  1044 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop29.tmp: open failed: EROFS (Read-only file system)
03-21 07:32:43.196  1019  1044 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
03-21 07:32:43.196  1019  1044 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
03-21 07:32:43.196  1019  1044 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72),
03-21 07:32:43.196  1019  1044 E DropBoxManagerService: ,	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
03-21 07:32:43.196  1019  1044 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269),
03-21 07:32:43.196  1019  1044 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$25.run(ActivityManagerService.java:15884)
03-21 07:32:43.196  1019  1044 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:15891)
03-21 07:32:43.196  1019  1044 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:15704)
03-21 07:32:43.196  1019  1044 E DropBoxManagerService: 	,at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15676)
03-21 07:32:43.196  1019  1044 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
03-21 07:32:43.196  1019  1044 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
03-21 07:32:43.196  1019  1044 E DropBoxManagerService: ,	at android.os.Looper.loop(Looper.java:145)
03-21 07:32:43.196  1019  1044 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-21 07:32:43.196  1019  1044 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
03-21 07:32:43.196  1019  1044 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
03-21 07:32:43.196  1019  1044 E DropBoxManagerService: 	,at libcore.io.Posix.open(Native Method)
03-21 07:32:43.196  1019  1044 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
03-21 07:32:43.196  1019  1044 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
03-21 07:32:43.196  1019  1044 E DropBoxManagerService: 	... 13 more
03-21 07:32:43.196  4121  4121 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
03-21 07:32:43.196  1019  1804 W ActivityManager: userId = 0, bbcId = -10000
03-21 07:32:43.196  1019  1804 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-21 07:32:43.196  1019  1804 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms,
,03-21 07:32:43.206  1999  1999 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 07:32:43.206  4074  4074 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,03-21 07:32:43.206  4074  4074 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
03-21 07:32:43.216  4074  4074 D UserAnalysis: Create SecureDbHelper
,03-21 07:32:43.216  4121  4121 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-21 07:32:43.216  4121  4121 D ActivityThread: Added TimaKeyStore provider
,03-21 07:32:43.216  1999  1999 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
03-21 07:32:43.216  1019  1561 E Tethering: No numeric data
,03-21 07:32:43.246  3841  4137 E Search.SharedPreferencesProto: Failed to rename to backup file /data/data/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
,03-21 07:32:43.276  1181  1181 D StatusBar.NetworkController: refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth

```
