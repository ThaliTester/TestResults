#### Test 82914073856d1c8_thali03_samsung-SM-A300FU Logs


```
--------- beginning of main
08-26 19:45:08.160  1972  6606 W art     : Verification of void com.google.android.gms.games.broker.DataBroker.<init>(android.content.Context) took 124.977ms
08-26 19:45:08.170   323   323 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 592us total 23.501ms
08-26 19:45:08.180  6570  6570 D NearbySource: Nearby Source Create!
08-26 19:45:08.180  6570  6570 D NearbyContext: Nearby Context Create!
08-26 19:45:08.230  1972  6602 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
--------- beginning of system
08-26 19:45:08.240  1020  4358 D ActivityManager: startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
08-26 19:45:08.240  1020  4358 D ActivityManager: retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.RlzPingIntentService; callingUser = 0; userId(target) = 0
08-26 19:45:08.240  1020  4358 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:45:08.240  1020  4358 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 19:45:08.240  1020  4358 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
08-26 19:45:08.250  1020  1513 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
08-26 19:45:08.250  1020  1513 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
08-26 19:45:08.250  1020  1513 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:45:08.250  1020  1513 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 19:45:08.250  1020  1513 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 19:45:08.270  1020  1487 D ActivityManager: startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
08-26 19:45:08.270  1020  1487 D ActivityManager: retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.AppInstalledService; callingUser = 0; userId(target) = 0
08-26 19:45:08.270  1020  1487 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:45:08.270  1020  1487 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 19:45:08.270  1020  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
08-26 19:45:08.280   257   536 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
08-26 19:45:08.280   257   536 W Vold    : Returning OperationFailed - no handler for errno 0
08-26 19:45:08.280  6570  6570 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
08-26 19:45:08.280  6570  6570 D SLinkSource: Samsung link source created
08-26 19:45:08.280  1020  1032 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
08-26 19:45:08.290  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:45:08.290  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:45:08.290  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:45:08.290  1020  1471 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
08-26 19:45:08.290  1020  1471 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4242, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-26 19:45:08.290  1020  1471 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-26 19:45:08.290  1020  1471 D BatteryService: stay LED for charging
08-26 19:45:08.290  1020  1020 D BatteryService: Sending ACTION_BATTERY_CHANGED.
08-26 19:45:08.290  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:45:08.300  6656  6656 E Zygote  : MountEmulatedStorage()
08-26 19:45:08.300  6621  6621 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:147 android.app.ActivityThread.handleReceiver:3125 
08-26 19:45:08.300  6656  6656 E Zygote  : v2
08-26 19:45:08.300  6656  6656 I libpersona: KNOX_SDCARD checking this for 1000
08-26 19:45:08.300  6656  6656 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-26 19:45:08.300  6656  6656 I libpersona: KNOX_SDCARD not a persona
08-26 19:45:08.310  6656  6656 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 19:45:08.310  6656  6656 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-26 19:45:08.310  1020  1032 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=6656 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-26 19:45:08.310  1020  4358 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:45:08.310  1020  4358 D ActivityManager: startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
08-26 19:45:08.310  1020  4358 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:45:08.310  1020  4358 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
08-26 19:45:08.310  1020  4358 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
08-26 19:45:08.320  6391  6391 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
08-26 19:45:08.330  1020  1020 I MotionRecognitionService: Plugged
08-26 19:45:08.330  1020  1020 I MotionRecognitionService: mGripSensorEnabled= false
08-26 19:45:08.330  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-26 19:45:08.330  1177  1177 D KeyguardUpdateMonitor: handleBatteryUpdate
08-26 19:45:08.340  1425  1425 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-26 19:45:08.340  1425  1425 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
08-26 19:45:08.350  6656  6656 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 19:45:08.350  6656  6656 D ActivityThread: Added TimaKeyStore provider
08-26 19:45:08.350  3176  3176 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-26 19:45:08.350  3176  3314 D HeadsetStateMachine: Disconnected process message: 10
08-26 19:45:08.360  1177  1177 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
08-26 19:45:08.360  1177  1177 D SViewCoverView: level :100 plugged : 2
08-26 19:45:08.360  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-26 19:45:08.360  1020  4266 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
08-26 19:45:08.360  1020  4266 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:45:08.360  1020  4266 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:45:08.360  1020  4266 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
08-26 19:45:08.370  1020  1032 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.docs, hostingType: broadcast
08-26 19:45:08.370  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:45:08.370  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:45:08.370  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:45:08.370  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:45:08.380  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-26 19:45:08.380  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-26 19:45:08.390  1020  1032 I ActivityManager: Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=6676 uid=10087 gids={50087, 9997, 1028, 3003, 1015} abi=armeabi-v7a
08-26 19:45:08.400  6676  6676 E Zygote  : MountEmulatedStorage()
08-26 19:45:08.400  6676  6676 I libpersona: KNOX_SDCARD checking this for 10087
08-26 19:45:08.400  6676  6676 E Zygote  : v2
08-26 19:45:08.400  6676  6676 I libpersona: KNOX_SDCARD not a persona
08-26 19:45:08.400  6676  6676 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-26 19:45:08.400  6676  6676 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 19:45:08.400  1020  1491 I ActivityManager: Killing 6263:com.android.mms/u0a41 (adj 15): empty #21
08-26 19:45:08.400  6676  6676 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
08-26 19:45:08.430  1020  1468 D CountryDetector: No listener is left
08-26 19:45:08.450  1020  4266 I ActivityManager: Killing 6168:com.android.defcontainer/u0a3 (adj 15): empty #21
08-26 19:45:08.450  6656  6656 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
08-26 19:45:08.450  6656  6656 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
08-26 19:45:08.450  6676  6676 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 19:45:08.460  6676  6676 D ActivityThread: Added TimaKeyStore provider
08-26 19:45:08.460  6570  6675 D ContactProvider: getAllContactInfoList Start
08-26 19:45:08.460  6656  6656 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
08-26 19:45:08.510  1020  4267 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-26 19:45:08.510  6570  6675 D ContactProvider: getAllContactInfoList End
08-26 19:45:08.510  6570  6675 I syncContacts: thread: 1203, sync time = 82
08-26 19:45:08.520  6656  6656 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
08-26 19:45:08.520  1020  1471 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-26 19:45:08.520  6656  6656 I PCWCLIENTTRACE_PushUtil: sales region : global
08-26 19:45:08.520  6656  6656 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
08-26 19:45:08.520  6656  6656 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.intent.action.PACKAGE_ADDED
08-26 19:45:08.520  1020  4357 D ActivityManager: startProcessLocked calleePkgName: com.android.vending, hostingType: broadcast
08-26 19:45:08.520  1020  4357 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:45:08.520  1020  4357 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:45:08.520  1020  4357 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:45:08.520  1020  4357 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:45:08.520  6570  6570 I PackagesMonitor: PackagesMonitor onReceive :com.test.thalitest
08-26 19:45:08.530  6663  6663 D AndroidRuntime: 
08-26 19:45:08.530  6663  6663 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-26 19:45:08.530  6663  6663 D AndroidRuntime: CheckJNI is OFF
08-26 19:45:08.530  6663  6663 D AndroidRuntime: readGMSProperty: start
08-26 19:45:08.530  6663  6663 D AndroidRuntime: readGMSProperty: already setted!!
08-26 19:45:08.530  6663  6663 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-26 19:45:08.530  6663  6663 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-26 19:45:08.530  6663  6663 D AndroidRuntime: readGMSProperty: end
08-26 19:45:08.530  6663  6663 D AndroidRuntime: addProductProperty: start
08-26 19:45:08.540  1020  4357 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=6694 uid=10026 gids={50026, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-26 19:45:08.540  6694  6694 E Zygote  : MountEmulatedStorage()
08-26 19:45:08.540  1020  4357 I ActivityManager: Killing 6290:com.samsung.android.scloud.sync/u0a58 (adj 15): empty #21
08-26 19:45:08.540  6694  6694 E Zygote  : v2
08-26 19:45:08.540  6694  6694 I libpersona: KNOX_SDCARD checking this for 10026
08-26 19:45:08.540  6694  6694 I libpersona: KNOX_SDCARD not a persona
08-26 19:45:08.540  6694  6694 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-26 19:45:08.540  1020  1047 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:45:08.550  6694  6694 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 19:45:08.550  6694  6694 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
08-26 19:45:08.550  1020  1047 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:45:08.550  1020  1047 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:45:08.550  1020  1047 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:45:08.570  6694  6694 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 19:45:08.570  6705  6705 E Zygote  : MountEmulatedStorage()
08-26 19:45:08.570  6705  6705 I libpersona: KNOX_SDCARD checking this for 1000
08-26 19:45:08.570  6705  6705 E Zygote  : v2
08-26 19:45:08.570  6705  6705 I libpersona: KNOX_SDCARD not a persona
08-26 19:45:08.570  6705  6705 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-26 19:45:08.570  6694  6694 D ActivityThread: Added TimaKeyStore provider
08-26 19:45:08.580  1020  1047 I ActivityManager: Start proc com.samsung.aasaservice for service com.samsung.aasaservice/.AASAService: pid=6705 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-26 19:45:08.580  1020  4267 D ActivityManager: startProcessLocked calleePkgName: com.android.mms, hostingType: broadcast
08-26 19:45:08.580  1020  4267 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:45:08.580  1020  4267 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:45:08.580  1020  4267 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:45:08.580  1020  4267 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:45:08.580  6705  6705 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 19:45:08.580  6705  6705 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-26 19:45:08.600  6721  6721 E Zygote  : MountEmulatedStorage()
08-26 19:45:08.600  6721  6721 E Zygote  : v2
08-26 19:45:08.600  6721  6721 I libpersona: KNOX_SDCARD checking this for 10041
08-26 19:45:08.600  6721  6721 I libpersona: KNOX_SDCARD not a persona
08-26 19:45:08.600  6721  6721 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-26 19:45:08.600  1020  4267 I ActivityManager: Start proc com.android.mms for broadcast com.android.mms/.smishing.PackageInstallReceiver: pid=6721 uid=10041 gids={50041, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
08-26 19:45:08.600  6721  6721 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 19:45:08.610  1020  4267 I ActivityManager: Killing 6305:com.sec.android.provider.badge/u0a68 (adj 15): empty #21
08-26 19:45:08.610  6721  6721 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
08-26 19:45:08.610  1972  6602 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
08-26 19:45:08.610  1972  6602 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-26 19:45:08.610  1972  6602 I System.out: (HTTPLog)-Static: isShipBuild true
08-26 19:45:08.610  1972  6602 I System.out: (HTTPLog)-Thread-251-565224443: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
08-26 19:45:08.610  1972  6602 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-26 19:45:08.620  6705  6705 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 19:45:08.620  6705  6705 D ActivityThread: Added TimaKeyStore provider
08-26 19:45:08.620   278  1002 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-26 19:45:08.620   278  1002 D Netd    : getNetworkForDns: using netid 502 for uid 10011
08-26 19:45:08.650  6721  6721 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 19:45:08.650  6721  6721 D ActivityThread: Added TimaKeyStore provider
08-26 19:45:08.670  6721  6721 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
08-26 19:45:08.670  6721  6721 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-26 19:45:08.670  6721  6721 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-26 19:45:08.670  6721  6721 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
08-26 19:45:08.670  6721  6721 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
08-26 19:45:08.680  6705  6705 D AASAservice: onCreate()
08-26 19:45:08.680  6705  6705 E AASAservice: getConfirmRuleVersion() : Version File is not exist.
08-26 19:45:08.700  2728  2728 I DBG_POLICYDM: [com.sec.android.policydm.aasa.AASAUpdater$1(72/onServiceConnected)] AASA: onServiceConnected
08-26 19:45:08.720  6663  6663 E AffinityControl: AffinityControl: registerfunction enter
08-26 19:45:08.750  6663  6663 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-26 19:45:08.750  1020  1258 W ActivityManager: getRunningAppProcesses: caller 10087 does not hold REAL_GET_TASKS; limiting output
08-26 19:45:08.760  1972  6602 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
08-26 19:45:08.760  1972  6602 I qtaguid : Tagging socket 101 with tag 1000040b00000000{268436491,0} for uid -1, pid: 1972, getuid(): 10011
08-26 19:45:08.770  1020  1491 E EdmStorageProvider: Admin not in database, something went wrong
08-26 19:45:08.780  1020  4359 W ActivityManager: getRunningAppProcesses: caller 10087 does not hold REAL_GET_TASKS; limiting output
08-26 19:45:08.800  6721  6721 D Mms/MmsApp: [start]    onCreate() consume time = 0.0
08-26 19:45:08.810  6694  6694 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-26 19:45:08.830  6694  6694 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-26 19:45:08.830  1020  1471 E PersonaManagerService: inState():  stateMachine is null !!
08-26 19:45:08.830  1020  1471 I PersonaManagerService: PersonaId don't exist
08-26 19:45:08.830  1020  1471 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
08-26 19:45:08.840  1020  1471 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-26 19:45:08.870  1020  1471 W ActivityManager: mDVFSHelper.acquire()
08-26 19:45:08.880  1020  1471 D FocusedStackFrame: Set to : 0
08-26 19:45:08.900  1020  1052 D PhoneWindow: *FMB* installDecor mIsFloating : false
08-26 19:45:08.900  1020  1052 D PhoneWindow: *FMB* installDecor flags : -2122120936
08-26 19:45:08.900  1972  6602 I qtaguid : Tagging socket 105 with tag 1000040b00000000{268436491,0} for uid -1, pid: 1972, getuid(): 10011
08-26 19:45:08.910  1020  1471 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:45:08.910  1020  1471 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:45:08.910  1020  1471 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:45:08.910  1020  1471 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:45:08.930  6761  6761 E Zygote  : MountEmulatedStorage()
08-26 19:45:08.930  6761  6761 I libpersona: KNOX_SDCARD checking this for 10170
08-26 19:45:08.930  6761  6761 E Zygote  : v2
08-26 19:45:08.930  6761  6761 I libpersona: KNOX_SDCARD not a persona
08-26 19:45:08.930  6761  6761 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-26 19:45:08.930  6761  6761 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 19:45:08.930  6761  6761 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
08-26 19:45:08.930  1020  1052 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-26 19:45:08.930  1020  1052 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
08-26 19:45:08.940  1020  1471 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6761 uid=10170 gids={50170, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-26 19:45:08.940  1020  1471 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
08-26 19:45:08.940  1020  1471 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-26 19:45:08.940   258   258 I SurfaceFlinger: id=12 createSurf (1x1),1 flag=404, uhalitest
08-26 19:45:08.950  1020  1487 I art     : Explicit concurrent mark sweep GC freed 142756(7MB) AllocSpace objects, 3(1847KB) LOS objects, 33% free, 22MB/34MB, paused 4.105ms total 319.498ms
08-26 19:45:08.950  1020  1471 D InputDispatcher: Focused application set to: xxxx
08-26 19:45:08.950  1020  1471 D InputDispatcher: Focus left window: 1495
08-26 19:45:08.950  6663  6663 D AndroidRuntime: Shutting down VM
08-26 19:45:08.950  1020  1052 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-26 19:45:08.950  1020  1052 D PointerIcon: setMouseCustomIcon IconType is same.101
08-26 19:45:08.960  1020  4358 D LocationManagerService: getProviders()=[passive, gps]
08-26 19:45:08.970  6761  6761 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 19:45:08.970  6761  6761 D ActivityThread: Added TimaKeyStore provider
08-26 19:45:08.980  1020  1033 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
08-26 19:45:08.980  6694  6694 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
08-26 19:45:08.990  1020  1050 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-26 19:45:08.990  1020  1020 V ActivityManager: Display changed displayId=0
08-26 19:45:09.010  1020  1033 D PersonaManager: isKioskContainerExistOnDevice
08-26 19:45:09.020  6694  6694 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-26 19:45:09.030  1020  4357 D ActivityManager: startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
08-26 19:45:09.030  1020  4357 D ActivityManager: retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PackagesMediaMonitor$AsyncService; callingUser = 0; userId(target) = 0
08-26 19:45:09.030  1020  4357 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:45:09.030  1020  4357 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 19:45:09.030  1020  4357 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
08-26 19:45:09.060  1020  1020 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
08-26 19:45:09.060   258  6129 I SurfaceFlinger: id=8 Removed Mauncher (5/9)
08-26 19:45:09.070   258   427 I SurfaceFlinger: id=8 Removed Mauncher (-2/9)
08-26 19:45:09.070  1972  6606 W BaseAppContext: Using Auth Proxy for data requests.
08-26 19:45:09.080  1972  6606 W BaseAppContext: Using Auth Proxy for data requests.
08-26 19:45:09.090  1495  1495 V ActivityThread: updateVisibility : ActivityRecord{901ab01 token=android.os.BinderProxy@147df3e3 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
08-26 19:45:09.090  1495  1495 D Launcher: onTrimMemory. Level: 20
08-26 19:45:09.150  6537  6604 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
08-26 19:45:09.160  6761  6761 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
08-26 19:45:09.160  6663  6663 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,08-26 19:45:09.180  6761  6761 I cr.library_loader: Time to load native libraries: 2 ms (timestamps 6811-6813)
,08-26 19:45:09.180  6761  6761 I cr.library_loader: Expected native library version number "", actual native library version number ""
,08-26 19:45:09.200  6761  6761 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {33ea399c}
08-26 19:45:09.200  6761  6761 I cr.library_loader: Expected native library version number "", actual native library version number ""
,08-26 19:45:09.200  6761  6761 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
,08-26 19:45:09.210  1695  4202 I art     : Explicit concurrent mark sweep GC freed 13156(627KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 8MB/13MB, paused 1.448ms total 51.975ms
,08-26 19:45:09.230  1972  6602 I qtaguid : Untagging socket 101
,08-26 19:45:09.230  6721  6721 W art     : Verification of com.android.mms.ui.MsgSweepActionListView com.android.mms.ArtClassLoader.createMsgSweepActionList(android.content.Context) took 363.320ms
,08-26 19:45:09.230  1972  6606 W BaseAppContext: Using Auth Proxy for data requests.
,08-26 19:45:09.250  1972  1972 I ConfigFetchService: fetch service done; releasing wakelock
,08-26 19:45:09.250  1972  1972 I ConfigFetchService: stopping self
,08-26 19:45:09.250  1972  6606 W BaseAppContext: Using Auth Proxy for data requests.
,08-26 19:45:09.260  1972  6606 W BaseAppContext: Using Auth Proxy for data requests.
,08-26 19:45:09.260  6761  6761 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
,08-26 19:45:09.260  6761  6761 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-26 19:45:09.270  6761  6761 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-26 19:45:09.270  6694  6694 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-26 19:45:09.280  1020  1033 D ActivityManager: startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
,08-26 19:45:09.280  1020  1033 D ActivityManager: retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PhotosAppTransitionService; callingUser = 0; userId(target) = 0
,08-26 19:45:09.290  1972  6606 W BaseAppContext: Using Auth Proxy for data requests.
,08-26 19:45:09.290  1020  1033 W ActivityManager: userId = 0, bbcId = -10000
,08-26 19:45:09.290  1020  1033 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 19:45:09.290  1020  1033 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,08-26 19:45:09.290  6694  6694 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-26 19:45:09.310  6694  6694 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-26 19:45:09.310  6694  6694 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-26 19:45:09.340  6761  6761 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-26 19:45:09.340  6761  6761 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-26 19:45:09.340  6761  6761 I Adreno-EGL: Build Date: 04/06/15 Mon
08-26 19:45:09.340  6761  6761 I Adreno-EGL: Local Branch: 
08-26 19:45:09.340  6761  6761 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-26 19:45:09.340  6761  6761 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-26 19:45:09.340  6761  6761 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-26 19:45:09.340  6694  6694 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-26 19:45:09.350  6694  6694 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-26 19:45:09.360  6694  6694 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-26 19:45:09.360  6694  6694 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-26 19:45:09.360  6694  6694 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-26 19:45:09.360  6694  6694 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-26 19:45:09.360  6694  6694 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-26 19:45:09.370  6694  6694 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-26 19:45:09.370  6694  6694 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-26 19:45:09.370  6694  6694 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-26 19:45:09.370  6694  6694 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-26 19:45:09.370  6694  6694 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-26 19:45:09.370  6694  6694 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,08-26 19:45:09.430  6694  6694 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-26 19:45:09.430  1020  4266 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.provider.shootingmodeprovider, hostingType: broadcast
08-26 19:45:09.430  6694  6694 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-26 19:45:09.430  1020  4266 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:45:09.430  1020  4266 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:45:09.430  1020  4266 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:45:09.430  1020  4266 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 19:45:09.430  6761  6761 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-26 19:45:09.450  1020  4266 I ActivityManager: Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=6818 uid=10148 gids={50148, 9997, 1023} abi=armeabi-v7a
08-26 19:45:09.450  6721  6721 W art     : Verification of com.sec.android.touchwiz.animator.TwDndHorizontalListAnimator com.android.mms.ArtClassLoader.createTwDndHorizontalListAnimator(android.content.Context) took 220.236ms
,08-26 19:45:09.450  6818  6818 E Zygote  : MountEmulatedStorage()
08-26 19:45:09.450  6818  6818 E Zygote  : v2
08-26 19:45:09.450  6818  6818 I libpersona: KNOX_SDCARD checking this for 10148
08-26 19:45:09.450  6818  6818 I libpersona: KNOX_SDCARD not a persona
,08-26 19:45:09.450  6818  6818 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 19:45:09.460  6818  6818 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-26 19:45:09.460  6761  6761 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
08-26 19:45:09.460  6761  6761 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
,08-26 19:45:09.460  6818  6818 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,08-26 19:45:09.470  6761  6761 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
,08-26 19:45:09.470  6761  6761 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
,08-26 19:45:09.480  1020  4359 I ActivityManager: Killing 6324:com.sec.android.app.clockpackage/u0a81 (adj 15): empty #21
,08-26 19:45:09.490  6694  6694 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-26 19:45:09.500  6694  6694 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-26 19:45:09.500  6694  6694 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
,08-26 19:45:09.500  6721  6827 D Mms/ArtClassLoader: init before art
,08-26 19:45:09.510  6721  6721 D Mms/TelephonyPermission: start operation mode monitor
,08-26 19:45:09.520  1020  4266 D PowerManagerService: [api] handleWakeLockDeath : release WakeLock : PARTIAL_WAKE_LOCK              'AlarmReceiver' (uid=10081, pid=6324, ws=null) (elapsedTime=2826)
,08-26 19:45:09.520  6818  6818 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 19:45:09.520  6721  6721 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-26 19:45:09.530  1020  1047 W ActivityManager: Activity pause timeout for ActivityRecord{5850a69 u0 com.test.thalitest/.MainActivity t163}
,08-26 19:45:09.530  6818  6818 D ActivityThread: Added TimaKeyStore provider
,08-26 19:45:09.560  1020  1258 I ActivityManager: Killing 6339:com.wsomacp/u0a23 (adj 15): empty #21
,08-26 19:45:09.570  6721  6721 D Mms/TelephonyPermission: DefaultSmsApp is com.android.mms
08-26 19:45:09.570  6721  6721 D Mms/TelephonyPermission: isDefault true
,08-26 19:45:09.570  6721  6721 D Mms/MmsApp: onCreate() com.android.mms
,08-26 19:45:09.610  1020  4358 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 19:45:09.620  1020  4358 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:45:09.620  1020  4358 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 19:45:09.620  1020  4358 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
,08-26 19:45:09.620  1020  4359 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-26 19:45:09.620  1020  4359 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,08-26 19:45:09.630  1020  4359 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:45:09.630  1020  4359 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 19:45:09.630  1020  4359 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 19:45:09.640  6694  6694 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,08-26 19:45:09.640  1020  4359 D ActivityManager: startService callerProcessName:com.android.vending, calleePkgName: com.android.vending,
08-26 19:45:09.650  1020  4359 D ActivityManager: retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.RestoreService; callingUser = 0; userId(target) = 0
,08-26 19:45:09.650  1020  4359 W ActivityManager: userId = 0, bbcId = -10000
,08-26 19:45:09.650  1020  4359 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 19:45:09.650  1020  4359 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,08-26 19:45:09.660  6721  6721 D Mms/MmsApp: [start]    initCountryIso consume time = 865.045469
,08-26 19:45:09.670  6818  6818 E SQLiteLog: (284) automatic index on shooting_modes(title_id)
,08-26 19:45:09.670  1020  1513 D CountryDetector: The first listener is added
,08-26 19:45:09.680  6761  6761 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-26 19:45:09.680  6721  6721 D Mms/MmsApp: [end]    initCountryIso consume time = 12.795625
08-26 19:45:09.680  6721  6721 D Mms/MmsConfig: [start]    MmsConfig.init() consume time = 0.09375
,08-26 19:45:09.680   272   272 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb866a7c8
08-26 19:45:09.680   272   272 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: R/W request received
08-26 19:45:09.680   272   272 I rmt_storage: wakelock acquired: 1, error no: 42
08-26 19:45:09.680   272   305 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1201231736)
08-26 19:45:09.680  6721  6721 D Mms/MmsConfig: before partial update
,08-26 19:45:09.690  1020  4359 W ActivityManager: getRunningAppProcesses: caller 10087 does not hold REAL_GET_TASKS; limiting output
,08-26 19:45:09.690  6694  6694 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.,
,08-26 19:45:09.690  1020  1471 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0,
,08-26 19:45:09.700  6721  6721 D Mms/MmsConfig: Load Resize quality : 80
,08-26 19:45:09.720  1020  1471 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:45:09.720  1020  1471 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 19:45:09.720  1020  1471 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 19:45:09.720  1020  1258 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.bbc.bbcagent, hostingType: broadcast
,08-26 19:45:09.720  1020  1258 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 19:45:09.720  1020  1258 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:45:09.720  1020  1258 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:45:09.720  1020  1258 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 19:45:09.730  6721  6721 D EasySignUpManager_1.0.1: serviceId : 1, features : -1,
,08-26 19:45:09.730  6721  6721 D EasySignUpManager_1.0.1: isAuth is false
,08-26 19:45:09.730  6721  6721 D Mms/MmsConfig: setFreeMessageEnabled, getSupportedFeatures = -1 isAuth = false
,08-26 19:45:09.730  6761  6761 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-26 19:45:09.740  6694  6843 D Ads     : Skipping gmscore version check
08-26 19:45:09.740   272   305 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Bytes written = 917504,
08-26 19:45:09.740   272   305 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Send response: res=0 err=0
08-26 19:45:09.740   272   305 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1201231736) wakelock released: 1, error no: 0
08-26 19:45:09.740   272   305 I rmt_storage: 
08-26 19:45:09.750  1020  1258 I ActivityManager: Start proc com.samsung.android.bbc.bbcagent for broadcast com.samsung.android.bbc.bbcagent/.bbccontroller.receiver.PackageEventReceiver: pid=6844 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-26 19:45:09.750   272   272 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x5 conn_h=0xb866a7c8,
,08-26 19:45:09.750  6844  6844 E Zygote  : MountEmulatedStorage()
08-26 19:45:09.750  6844  6844 E Zygote  : v2
,08-26 19:45:09.750  6844  6844 I libpersona: KNOX_SDCARD checking this for 1000
08-26 19:45:09.750  6844  6844 I libpersona: KNOX_SDCARD not a persona
08-26 19:45:09.750  6844  6844 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 19:45:09.760  6844  6844 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-26 19:45:09.760  6844  6844 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 19:45:09.760  1020  4359 I ActivityManager: Killing 6355:com.sec.esdk.elm/u0a90 (adj 15): empty #21
,08-26 19:45:09.760  1020  4357 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-26 19:45:09.760  1020  4357 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,08-26 19:45:09.770  6761  6761 D PhoneWindow: *FMB* installDecor mIsFloating : false
08-26 19:45:09.770  6761  6761 D PhoneWindow: *FMB* installDecor flags : -2139027200
08-26 19:45:09.770  1020  4357 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:45:09.770  1020  4357 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 19:45:09.770  1020  4357 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-26 19:45:09.770  6761  6761 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,08-26 19:45:09.770  1020  1258 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 19:45:09.780  1020  1258 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:45:09.780  1020  1258 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 19:45:09.780  1020  1258 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,08-26 19:45:09.790  1472  1788 D TP/MmsSmsProvider: query,matched:2117, calling pid = 6721,
,08-26 19:45:09.790  6761  6761 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-26 19:45:09.800  6761  6761 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-26 19:45:09.800  1472  1788 D TP/MmsSmsProvider: match 2117:Elapsed time : 6.700 ms
,08-26 19:45:09.810  1020  1508 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0,
,08-26 19:45:09.810  6844  6844 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 19:45:09.820  1020  1508 W ActivityManager: userId = 0, bbcId = -10000
,08-26 19:45:09.820  1020  1508 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-26 19:45:09.820  1020  1508 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 19:45:09.820  6844  6844 D ActivityThread: Added TimaKeyStore provider
,08-26 19:45:09.850  6721  6721 D EasySignUpManager_1.0.1: isAuth is false
,08-26 19:45:09.850  6721  6721 D EasySignUpManager_1.0.1: getServiceStatus : serviceId (1) is OFF
,08-26 19:45:09.860  1020  1032 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 19:45:09.860  1020  1032 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:45:09.860  1020  1032 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 19:45:09.860  1020  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,08-26 19:45:09.860  6694  6694 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-26 19:45:09.870  6721  6721 E CscParser: mps_code.dat does not exist
08-26 19:45:09.870  6721  6721 E CscParser: customer_path =/system/csc/customer.xml
08-26 19:45:09.870  6721  6721 E CscParser: fileName + /system/csc/customer.xml
,08-26 19:45:09.870  6844  6844 W ResourcesManager: Asset path '/system/framework/com.samsung.bbccommon.jar' does not exist or contains no resources.
,08-26 19:45:09.890  6537  6604 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 736 ms] updated apps [took 736 ms] 
,08-26 19:45:09.890  6721  6721 E CscParser: mps_code.dat does not exist
08-26 19:45:09.890  6721  6721 E CscParser: customer_path =/system/csc/customer.xml
08-26 19:45:09.890  6721  6721 E CscParser: fileName + /system/csc/customer.xml
,08-26 19:45:09.900  1020  1257 I ActivityManager: Killing 6070:com.sec.android.widgetapp.SPlannerAppWidget/u0a130 (adj 15): empty #21
,08-26 19:45:09.910  6721  6721 D CscParser: getInstance fileName =/system/csc/customer.xml
,08-26 19:45:09.910  6721  6721 D Mms/MmsConfig:  enable multiwindow = false
,08-26 19:45:09.930  6721  6721 E Mms/MessageUtils: setCountryDetector : update country detector info 
,08-26 19:45:09.930  6721  6721 E Mms/MessageUtils: updateCountryIso : update country iso info 
,08-26 19:45:09.930  6721  6721 D Mms/MmsConfig: [end]    init() consume time = 254.834791
,08-26 19:45:09.930  6721  6721 D Mms/Contact: [start]    init() consume time = 1.017657
,08-26 19:45:09.940  1472  1788 D TP/MmsSmsProvider: query,matched:13, calling pid = 6721
,08-26 19:45:09.950  1472  1788 D TP/MmsSmsProvider: match 13:Elapsed time : 1.894 ms
,08-26 19:45:09.950  6761  6868 D OpenGLRenderer: Render dirty regions requested: true
,08-26 19:45:09.960  1020  1491 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
08-26 19:45:09.960  1020  1491 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-26 19:45:09.960  1020  1491 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
08-26 19:45:09.960  1020  1020 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-26 19:45:09.960  1020  1020 D PersonaManagerService: getPersonasForUser(): returning null!
,08-26 19:45:09.960  6761  6811 W chromium: [WARNING:data_reduction_proxy_config.cc(630)] SPDY proxy OFF at startup
,08-26 19:45:09.970  6761  6761 V ActivityThread: updateVisibility : ActivityRecord{194bc6ef token=android.os.BinderProxy@290a54c9 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,08-26 19:45:09.970  6721  6721 D Mms/Contact: [end]    init consume time = 33.534531
,08-26 19:45:09.970  6761  6761 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-26 19:45:09.970  6761  6761 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,08-26 19:45:09.970  6721  6871 D Mms/DraftCache: [start]    rebuildCache consume time = 7.719635
,08-26 19:45:09.990  1472  1486 D TP/MmsSmsProvider: query,matched:12, calling pid = 6721
,08-26 19:45:09.990  1472  1486 D TP/MmsSmsProvider: match 12:Elapsed time : 1.956 ms
,08-26 19:45:09.990   258   258 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, NainActivit
,08-26 19:45:10.000  6721  6871 D Mms/DraftCache: [end]    rebuildCache consume time = 22.214271
,08-26 19:45:10.000  1020  1468 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.tapandpay, hostingType: broadcast
,08-26 19:45:10.010  1020  1468 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 19:45:10.010  1020  1468 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 19:45:10.010  1020  1468 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:45:10.010  1020  1468 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 19:45:10.010  1020  1082 D InputDispatcher: Focus entered window: 6761
,08-26 19:45:10.030  6761  6761 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! ,
08-26 19:45:10.030  6761  6868 I OpenGLRenderer: Initialized EGL, version 1.4
08-26 19:45:10.030  1020  1052 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-26 19:45:10.030  1020  1052 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-26 19:45:10.030  6761  6868 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096,
08-26 19:45:10.030  6761  6868 D OpenGLRenderer: Enabling debug mode 0
,08-26 19:45:10.040  6873  6873 E Zygote  : MountEmulatedStorage(),
08-26 19:45:10.040  1020  1468 I ActivityManager: Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TapandpayAppWidgetProvider: pid=6873 uid=10152 gids={50152, 9997} abi=armeabi-v7a
08-26 19:45:10.040  6873  6873 E Zygote  : v2
08-26 19:45:10.040  1020  1468 I ActivityManager: Killing 6090:com.android.calendar/u0a131 (adj 15): empty #21
08-26 19:45:10.040  6873  6873 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
08-26 19:45:10.040  6873  6873 I libpersona: KNOX_SDCARD checking this for 10152
08-26 19:45:10.040  6873  6873 I libpersona: KNOX_SDCARD not a persona
,08-26 19:45:10.050  6873  6873 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 19:45:10.050  6873  6873 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 19:45:10.050  6721  6721 D Mms/MethodReflector: getSubId is called
08-26 19:45:10.050  6721  6721 D Mms/TelephonyUtils: getLongSubId from simSlot 0, return Value = -1
,08-26 19:45:10.050  6721  6721 D Mms/MethodReflector: getTelephonyProperty is called
08-26 19:45:10.050  6721  6721 D Mms/DownloadManager: roaming -> false (slotId = 0)
08-26 19:45:10.050  6721  6721 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 0,
08-26 19:45:10.050  6721  6721 D Mms/DownloadManager: auto download without roaming -> true
08-26 19:45:10.050  6721  6721 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAuto : true, roaming : false
08-26 19:45:10.050  6721  6721 D Mms/MethodReflector: getSubId is called
,08-26 19:45:10.060  6721  6721 D Mms/MethodReflector: getDefaultSmsSubId is called
08-26 19:45:10.060  6721  6721 E Mms/TelephonyUtils: subID is null or 0 length, so get DefaultSubId!!
08-26 19:45:10.060  6721  6721 D Mms/TelephonyUtils: getLongSubId from simSlot 1, return Value = -1000
08-26 19:45:10.060  6721  6721 D Mms/MethodReflector: getTelephonyProperty is called
08-26 19:45:10.060  6721  6721 D Mms/DownloadManager: roaming -> false (slotId = 1)
08-26 19:45:10.060  6721  6721 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 1
08-26 19:45:10.060  6721  6721 D Mms/DownloadManager: auto download without roaming -> true
08-26 19:45:10.060  6721  6721 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
08-26 19:45:10.060  6721  6721 D Mms/DownloadManager: auto download during roaming secondary -> false
08-26 19:45:10.060  6721  6721 D Mms/DownloadManager: mAutoDownload ------> true
,08-26 19:45:10.070  1020  1033 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-26 19:45:10.070  1177  1177 D PanelView: There is/are notification(s) 
,08-26 19:45:10.080  1020  6884 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-26 19:45:10.090  1020  1052 I ActivityManager: Displayed Component not be shown by security: +1s64ms (total +1s191ms)
,08-26 19:45:10.090  1020  1052 W ActivityManager: mDVFSHelper.release()
,08-26 19:45:10.090  1020  1052 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{5850a69 u0 com.test.thalitest/.MainActivity t163} time:97727
,08-26 19:45:10.100  6761  6761 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,08-26 19:45:10.100  6761  6761 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@290a54c9 time:97735
,08-26 19:45:10.100   258   433 I SurfaceFlinger: id=12 Removed uhalitest (7/9)
,08-26 19:45:10.100   258  1043 I SurfaceFlinger: id=12 Removed uhalitest (-2/9)
,08-26 19:45:10.100  6873  6873 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 19:45:10.110  6873  6873 D ActivityThread: Added TimaKeyStore provider
,08-26 19:45:10.130  1879  1879 I SamsungIME: getCurrentCandidateView
,08-26 19:45:10.140  6721  6827 D Mms/ArtClassLoader: init [DONE] art
,08-26 19:45:10.140  6873  6873 I TapandpayWidget:TapandpayAppWidgetProvider: onReceive()
,08-26 19:45:10.140  6873  6873 D TapandpayWidget:TapandpayAppWidgetProvider: onReceive() - action : android.intent.action.PACKAGE_ADDED / mCurIndex :-10
,08-26 19:45:10.160  1972  6606 W art     : Verification of void com.google.android.gms.games.broker.GameAgent.addGameBadgeOps(com.google.android.gms.common.internal.ClientContext, com.google.android.gms.games.server.api.MarketInstance, java.lang.String, java.util.ArrayList, int) took 182.146ms
,08-26 19:45:10.170  6721  6721 D ComposerPerformance: 1472233510179 ms / [DONE] Composer constructor
,08-26 19:45:10.170  6721  6721 E CII     : CommonIMSInterface: VoLTE CSC feature disabled.
,08-26 19:45:10.170  6721  6721 I Mms/ReservationManager: ReservationManager()
08-26 19:45:10.170  6721  6721 I Mms/ReservationManager: resetAfterConnected()
,08-26 19:45:10.170  1472  2676 D TP/MmsSmsProvider: query,matched:7, calling pid = 6721
,08-26 19:45:10.170  6721  6895 D Mms/Conversation: [start]    init() consume time = 175.971198
,08-26 19:45:10.170  1472  2676 D TP/MmsSmsProvider: match 7:Elapsed time : 2.367 ms
,08-26 19:45:10.170  1472  1788 D TP/MmsSmsProvider: deleteConversation threadId: 9223372036854775807
,08-26 19:45:10.170  1472  1788 D TP/MmsSmsProvider: delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
08-26 19:45:10.170  1472  1788 V TP/MmsSmsDatabaseHelper: updateThread(), thread_id = 9223372036854775807
,08-26 19:45:10.180  1472  1788 V TP/MmsSmsDatabaseHelper: sUpgradeVersion = 0, db.getVersion() = 81
,08-26 19:45:10.180  1472  1788 D TP/MmsSmsProvider: delete threadId: 9223372036854775807
08-26 19:45:10.180  1472  1788 D TP/MmsSmsProvider: need read changed broadcast:false
,08-26 19:45:10.180  6721  6895 D Mms/Conversation: [end]    init consume time = 12.165104
,08-26 19:45:10.190  1020  3338 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-26 19:45:10.190  6873  6873 I TapandpayWidget:Utils: Clear T&P info.
,08-26 19:45:10.190  6721  6721 I Mms/ReservationManager: getReservedSendMessageCount(): retMessageCount=0
,08-26 19:45:10.190  6721  6895 D Mms/MessagingNotification: [start]    init() consume time = 10.23724
,08-26 19:45:10.200  6721  6721 D Mms/MmsApp: [end]    onCreate() consume time = 1.77526
,08-26 19:45:10.200  6761  6761 W cr.BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6761
,08-26 19:45:10.200  6721  6895 D Mms/MessagingNotification: [end]    init consume time = 5.448229
,08-26 19:45:10.210  1472  1486 D TP/MmsSmsProvider: query,matched:0, calling pid = 6721
08-26 19:45:10.210  1472  1486 V TP/MmsSmsProvider: getSimpleConversations entered.
,08-26 19:45:10.210  1472  1486 D TP/MmsSmsProvider: match 0:Elapsed time : 1.046 ms
,08-26 19:45:10.210  6721  6897 D Mms/SpamFilter: [start]    SpamFilter fill() begin consume time = 9.13599
,08-26 19:45:10.210  6721  6898 D Mms/Synchronizer: [start]    doSync consume time = 3.512864
,08-26 19:45:10.220  1472  1788 D TP/MmsSmsProvider: update, matched:300, calling pid = 6721
08-26 19:45:10.220  1472  1788 V TP/MmsSmsProvider: syncDBData start
,08-26 19:45:10.220  1020  1491 D ActivityManager: getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.sec.android.provider.badge
,08-26 19:45:10.220  1472  1788 V TP/MmsSmsProvider: syncDBData sms end
08-26 19:45:10.220  1020  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:45:10.220  1020  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:45:10.220  1020  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:45:10.220  1020  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 19:45:10.220  1472  1788 V TP/MmsSmsProvider: syncDBData mms end
,08-26 19:45:10.220  1472  1788 V TP/MmsSmsProvider: syncDBData end
,08-26 19:45:10.230  6676  6755 I GAv4    : Google Analytics 7.8.95 is starting up. To enable debug logging on a device run:,
,08-26 19:45:10.230  6676  6755 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-26 19:45:10.230  6676  6755 I GAv4    :   adb logcat -s GAv4
,08-26 19:45:10.230  6901  6901 E Zygote  : MountEmulatedStorage()
,08-26 19:45:10.230  6901  6901 E Zygote  : v2
08-26 19:45:10.230  6901  6901 I libpersona: KNOX_SDCARD checking this for 10068
08-26 19:45:10.230  6901  6901 I libpersona: KNOX_SDCARD not a persona
08-26 19:45:10.240  6901  6901 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 19:45:10.240  1020  1491 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=6901 uid=10068 gids={50068, 9997} abi=armeabi-v7a
08-26 19:45:10.240  6901  6901 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 19:45:10.240  6901  6901 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,08-26 19:45:10.240  6721  6898 D Mms/Synchronizer: [end]    doSync consume time = 28.589063
,08-26 19:45:10.240  6873  6873 D TapandpayWidget:TapandpayAppWidgetProvider: Widget is not attached.
,08-26 19:45:10.240  1020  1487 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.samsungapps, hostingType: broadcast
,08-26 19:45:10.250  1472  1488 D TP/MmsSmsProvider: query,matched:400, calling pid = 6721
,08-26 19:45:10.250  1020  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 19:45:10.250  1020  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:45:10.250  6721  6721 D Mms/DownloadManager: Service state changed: Bundle[mParcelledData.dataSize=760]
08-26 19:45:10.250  1020  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:45:10.250  6721  6721 D Mms/DownloadManager: roaming ------> false, mSimSlot = 0
,08-26 19:45:10.250  6721  6721 D Mms/MethodReflector: getSubId is called
08-26 19:45:10.250  1020  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:45:10.250  6721  6721 D Mms/TelephonyUtils: getLongSubId from simSlot 0, return Value = -1
,08-26 19:45:10.250  6721  6721 D Mms/MethodReflector: getTelephonyProperty is called,
08-26 19:45:10.250  6721  6721 D Mms/DownloadManager: roaming -> false (slotId = 0)
08-26 19:45:10.250  6721  6721 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 0
08-26 19:45:10.250  6721  6721 D Mms/DownloadManager: auto download without roaming -> true,
08-26 19:45:10.250  6721  6721 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAuto : true, roaming : false
08-26 19:45:10.250  6721  6721 D Mms/DownloadManager: mAutoDownload ------> true
,08-26 19:45:10.270  6912  6912 E Zygote  : MountEmulatedStorage()
08-26 19:45:10.270  6912  6912 I libpersona: KNOX_SDCARD checking this for 10009
08-26 19:45:10.270  6912  6912 E Zygote  : v2
08-26 19:45:10.270  6912  6912 I libpersona: KNOX_SDCARD not a persona
08-26 19:45:10.270  6912  6912 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-26 19:45:10.280  6912  6912 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 19:45:10.280  1020  1487 I ActivityManager: Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.MyPackageReplacedReceiver: pid=6912 uid=10009 gids={50009, 9997, 1028, 1015, 3003} abi=armeabi-v7a
08-26 19:45:10.280  1020  1487 I ActivityManager: Killing 6378:com.samsung.android.securitylogagent/1000 (adj 15): empty #21
08-26 19:45:10.280  6912  6912 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
08-26 19:45:10.300  6901  6901 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 19:45:10.300  6901  6901 D ActivityThread: Added TimaKeyStore provider
08-26 19:45:10.310  6721  6721 D Mms/FreeMessageStatusReceiver: onReceive, action : android.intent.action.PACKAGE_ADDED
08-26 19:45:10.320   323   323 I art     : Explicit concurrent mark sweep GC freed 8724(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 620us total 36.565ms
08-26 19:45:10.330  6912  6912 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 19:45:10.330  1020  1508 D ActivityManager: startService callerProcessName:com.android.mms, calleePkgName: com.android.mms
08-26 19:45:10.330  6912  6912 D ActivityThread: Added TimaKeyStore provider
08-26 19:45:10.330  1020  1508 D ActivityManager: retrieveServiceLocked(): component = com.android.mms/com.android.mms.freemessage.FreeMessageReceiverService; callingUser = 0; userId(target) = 0
08-26 19:45:10.330  1020  1508 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:45:10.330  1020  1508 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:45:10.330  1020  1508 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
08-26 19:45:10.340   323   323 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 1.436ms total 18.935ms
08-26 19:45:10.350  1020  1032 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.myfiles, hostingType: broadcast
08-26 19:45:10.350  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:45:10.350  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:45:10.350  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:45:10.350  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:45:10.360  6721  6933 D Mms/FreeMessageReceiverService: onHandleIntent, action : android.intent.action.PACKAGE_ADDED
08-26 19:45:10.360  6721  6933 D Mms/FreeMessageReceiverService: onHandleIntent: ACTION_PACKAGE_ADDED
08-26 19:45:10.360   323   323 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 588us total 27.028ms
08-26 19:45:10.370  1879  1879 D SamsungIME: Dismiss ExpandCandiate
08-26 19:45:10.380   295   295 E SMD     : DCD OFF
08-26 19:45:10.380  6676  6755 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
08-26 19:45:10.380  6901  6901 D BadgeProvider: onCreate
08-26 19:45:10.380  1020  1487 W ActivityManager: getRunningAppProcesses: caller 10087 does not hold REAL_GET_TASKS; limiting output
08-26 19:45:10.380  6901  6901 D BadgeProvider: DatabaseHelper
08-26 19:45:10.390  6934  6934 E Zygote  : MountEmulatedStorage()
08-26 19:45:10.390  6934  6934 E Zygote  : v2
08-26 19:45:10.390  6934  6934 I libpersona: KNOX_SDCARD checking this for 10042
08-26 19:45:10.390  6934  6934 I libpersona: KNOX_SDCARD not a persona
08-26 19:45:10.390  6934  6934 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-26 19:45:10.390  1020  1032 I ActivityManager: Start proc com.sec.android.app.myfiles for broadcast com.sec.android.app.myfiles/.receiver.MyFilesReceiver: pid=6934 uid=10042 gids={50042, 9997, 1028, 1015, 3003, 3002, 3001, 1023} abi=armeabi-v7a
08-26 19:45:10.390  6934  6934 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 19:45:10.400  6721  6897 D Mms/SpamFilter: [end]    SpamFilter fill() finished consume time = 154.735104
08-26 19:45:10.400  6934  6934 E SELinux : [DEBUG] get_category: variable seinfo: media sensitivity: NULL, cateogry: NULL
08-26 19:45:10.400  1020  4267 I ActivityManager: Killing 6391:com.android.providers.calendar/u0a37 (adj 15): empty #21
08-26 19:45:10.400  1020  4267 I ActivityManager: Killing 6409:com.sec.android.app.taskmanager/u0a153 (adj 15): empty #22
08-26 19:45:10.430  6761  6761 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
08-26 19:45:10.430  6721  6895 D Mms/MessagingNotification: checkBadgeCount unreadCount=0 badgeCount=0
08-26 19:45:10.440  6934  6934 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 19:45:10.440  6934  6934 D ActivityThread: Added TimaKeyStore provider
08-26 19:45:10.440  1472  1486 D TP/SmsProvider: query,matched:26, calling pid = 6721
08-26 19:45:10.450  1472  1486 D TP/SmsProvider: match 26:Elapsed time : 4.406 ms
08-26 19:45:10.460  6934  6934 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-26 19:45:10.460  6934  6934 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-26 19:45:10.460  6934  6934 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
08-26 19:45:10.460  1472  1488 D TP/MmsSmsProvider: query,matched:6, calling pid = 6721
08-26 19:45:10.460  1472  1488 D TP/MmsSmsProvider: match 6:Elapsed time : 1.437 ms
08-26 19:45:10.490  1020  4359 D ActivityManager: getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.wsomacp
08-26 19:45:10.490  1020  4359 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:45:10.490  1020  4359 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:45:10.490  1020  4359 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:45:10.490  1020  4359 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:45:10.500  6676  6755 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
08-26 19:45:10.510  6950  6950 E Zygote  : MountEmulatedStorage()
08-26 19:45:10.510  6950  6950 E Zygote  : v2
08-26 19:45:10.510  6950  6950 I libpersona: KNOX_SDCARD checking this for 10023
08-26 19:45:10.510  6950  6950 I libpersona: KNOX_SDCARD not a persona
08-26 19:45:10.510  6950  6950 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-26 19:45:10.510  1020  4359 I ActivityManager: Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=6950 uid=10023 gids={50023, 9997} abi=armeabi-v7a
08-26 19:45:10.510  6950  6950 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 19:45:10.510  6950  6950 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-26 19:45:10.530  6676  6755 W AnalyticsTrackerProxyImpl: Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.357.23.33
08-26 19:45:10.540  6950  6950 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 19:45:10.540  6950  6950 D ActivityThread: Added TimaKeyStore provider
08-26 19:45:10.540  1020  1468 I ActivityManager: Killing 6426:com.qualcomm.timeservice/1000 (adj 15): empty #21
08-26 19:45:10.560  1020  4357 I ActivityManager: Killing 6469:com.samsung.android.app.watchmanagerstub/u0a98 (adj 15): empty #21
08-26 19:45:10.610  1972  2004 W art     : Suspending all threads took: 8.480ms
08-26 19:45:10.620  6676  6956 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
08-26 19:45:10.630  6950  6950 I OMACP   : [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
08-26 19:45:10.650  6721  6895 D Mms/Omacp: checkOmacp()  old OmacpCount 0 current OmacpCount = 0
08-26 19:45:10.650  6934  6934 D MyFiles : MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
08-26 19:45:10.650  6676  6690 W art     : Suspending all threads took: 25.240ms
08-26 19:45:10.670  1020  1061 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.defcontainer, action: null
08-26 19:45:10.670  1020  1061 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
08-26 19:45:10.670  1020  1061 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:45:10.670  1020  1061 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:45:10.670  1020  1061 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:45:10.670  1020  1061 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:45:10.690  6969  6969 E Zygote  : MountEmulatedStorage()
08-26 19:45:10.690  6969  6969 E Zygote  : v2
08-26 19:45:10.690  6969  6969 I libpersona: KNOX_SDCARD checking this for 10003
08-26 19:45:10.690  6969  6969 I libpersona: KNOX_SDCARD not a persona
08-26 19:45:10.690  6969  6969 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-26 19:45:10.690  1020  1061 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=6969 uid=10003 gids={50003, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
08-26 19:45:10.700  1020  1487 I ActivityManager: Killing 6455:com.samsung.android.app.galaxyfinder/u0a29 (adj 15): empty #21
08-26 19:45:10.700  6969  6969 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 19:45:10.700  6969  6969 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-26 19:45:10.720  6969  6969 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 19:45:10.720  6969  6969 D ActivityThread: Added TimaKeyStore provider
08-26 19:45:10.730  6761  6886 D jxcore_app_log: JniHelper::setJavaVM(0xb711b2b0), pthread_self() = -1217759640
08-26 19:45:10.730  6761  6886 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-26 19:45:10.730  6761  6886 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-26 19:45:10.730  6761  6886 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-26 19:45:10.730  6761  6886 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-26 19:45:10.730  6761  6886 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-26 19:45:10.730  6761  6886 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1e286332 added. We now have 1 listener(s)
08-26 19:45:10.740  6761  6886 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:75:41
08-26 19:45:10.740  6761  6886 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
08-26 19:45:10.740  6761  6886 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 19:45:10.740  6761  6886 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 19:45:10.750  6761  6886 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-26 19:45:10.750  6761  6886 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-26 19:45:10.750  6761  6886 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-26 19:45:10.750  6761  6886 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:75:41
08-26 19:45:10.750  6761  6886 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-26 19:45:10.750  6761  6886 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-26 19:45:10.750  6761  6886 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-26 19:45:10.750  6761  6886 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-26 19:45:10.750  6761  6886 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-26 19:45:10.750  6761  6886 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-26 19:45:10.750  6761  6886 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-26 19:45:10.750  6761  6886 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-26 19:45:10.750  6761  6886 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-26 19:45:10.750  6761  6886 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-26 19:45:10.750  6761  6886 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11d50239 added. We now have 1 listener(s)
08-26 19:45:10.750  6761  6886 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 19:45:10.750  6950  6950 I OMACP   : [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
08-26 19:45:10.750  6950  6950 I OMACP   : [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
08-26 19:45:10.750  6950  6950 I OMACP   : [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
08-26 19:45:10.750  6950  6950 I OMACP   : [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
08-26 19:45:10.750  6950  6950 I OMACP   : [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
08-26 19:45:10.750  6950  6950 I OMACP   : [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
08-26 19:45:10.760  6761  6886 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-26 19:45:10.760  6761  6886 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-26 19:45:10.760  6761  6886 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-26 19:45:10.760  6761  6886 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-26 19:45:10.760  6761  6886 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-26 19:45:10.760   284   284 E installd: system dir 0 : /system/app/
08-26 19:45:10.760   284   284 E installd: system dir 1 : /system/priv-app/
08-26 19:45:10.760   284   284 E installd: system dir 2 : /vendor/app/
08-26 19:45:10.760   284   284 E installd: system dir 3 : /oem/app/
08-26 19:45:10.760  6761  6886 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 19:45:10.770  6761  6886 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:75:41
08-26 19:45:10.770  6950  6950 I OMACP   : [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
08-26 19:45:10.770  6950  6950 I OMACP   : [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
08-26 19:45:10.780  6761  6886 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
08-26 19:45:10.780  6761  6886 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 19:45:10.780  6761  6886 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:45:10.780  6761  6886 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 19:45:10.780  6761  6886 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 19:45:10.780  6761  6886 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 19:45:10.780  6761  6886 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 19:45:10.780  6761  6886 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 19:45:10.780  6761  6886 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 19:45:10.780  6950  6950 I OMACP   : [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
08-26 19:45:10.780  6761  6886 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-26 19:45:10.780  6761  6886 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 19:45:10.780  6950  6950 I OMACP   : [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
08-26 19:45:10.780  6761  6886 I io.jxcore.node.LifeCycleMonitor: start: OK
08-26 19:45:10.780  6950  6950 I OMACP   : [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
08-26 19:45:10.780  6950  6950 I OMACP   : [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
08-26 19:45:10.780  6761  6761 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:45:10.780  6950  6950 I OMACP   : [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
08-26 19:45:10.790  6761  6761 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:45:10.800  1020  1033 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.filterinstaller, hostingType: broadcast
08-26 19:45:10.810  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:45:10.810  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:45:10.810  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:45:10.810  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:45:10.820  6761  6761 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
08-26 19:45:10.820  1020  1033 I ActivityManager: Start proc com.samsung.android.app.filterinstaller for broadcast com.samsung.android.app.filterinstaller/.PackageIntentReceiver: pid=6990 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-26 19:45:10.820  6990  6990 E Zygote  : MountEmulatedStorage()
08-26 19:45:10.820  6990  6990 E Zygote  : v2
08-26 19:45:10.820  6990  6990 I libpersona: KNOX_SDCARD checking this for 1000
08-26 19:45:10.820  6990  6990 I libpersona: KNOX_SDCARD not a persona
08-26 19:45:10.830  1020  1033 I ActivityManager: Killing 5020:com.google.android.gms.wearable/u0a11 (adj 15): empty #21
08-26 19:45:10.830  6990  6990 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-26 19:45:10.830  6990  6990 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 19:45:10.830  1020  1061 D PackageManager: remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
08-26 19:45:10.830  6990  6990 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-26 19:45:10.890  6990  6990 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 19:45:10.890  6990  6990 D ActivityThread: Added TimaKeyStore provider
08-26 19:45:10.920  6990  6990 D FilterInstaller: onReceive:android.intent.action.PACKAGE_ADDED, package:com.test.thalitest
08-26 19:45:10.930  6990  6990 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:44 android.app.ActivityThread.handleReceiver:3125 
08-26 19:45:10.930  1020  1487 D ActivityManager: startService callerProcessName:com.samsung.android.app.filterinstaller, calleePkgName: com.samsung.android.app.filterinstaller
08-26 19:45:10.930  1020  1487 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.filterinstaller/com.samsung.android.app.filterinstaller.FilterPackageService; callingUser = 0; userId(target) = 0
08-26 19:45:10.930  1020  1487 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:45:10.930  1020  1487 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:45:10.930  1020  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.filterinstaller, destAppInfo.processName = com.samsung.android.app.filterinstaller
08-26 19:45:10.940  1020  4358 I splitIntent: Queue : backgroundsplit_1 intent android.intent.action.PACKAGE_ADDED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
08-26 19:45:10.940  1020  1047 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.SPlannerAppWidget, hostingType: broadcast
08-26 19:45:10.950  1020  1047 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:45:10.950  1020  1047 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:45:10.950  1020  1047 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:45:10.950  1020  1047 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:45:10.950  1972  4264 I Icing   : Indexing D0AE1F45F393341DA3213A207506F1C2E721F1A9 from com.google.android.googlequicksearchbox
08-26 19:45:10.950  6990  6990 I FilterInstaller: FilterPackageService : ACTION_CHANGED
08-26 19:45:10.960  7008  7008 E Zygote  : MountEmulatedStorage()
08-26 19:45:10.960  7008  7008 E Zygote  : v2
08-26 19:45:10.960  7008  7008 I libpersona: KNOX_SDCARD checking this for 10130
08-26 19:45:10.960  7008  7008 I libpersona: KNOX_SDCARD not a persona
08-26 19:45:10.960  7008  7008 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-26 19:45:10.960  7008  7008 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 19:45:10.960  7008  7008 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
08-26 19:45:10.960  1020  1047 I ActivityManager: Start proc com.sec.android.widgetapp.SPlannerAppWidget for broadcast com.sec.android.widgetapp.SPlannerAppWidget/.EasyWidget.EasyCalendarAppWidgetProvider: pid=7008 uid=10130 gids={50130, 9997} abi=armeabi-v7a
08-26 19:45:10.980  1879  1879 I SamsungIME: getDebugLevel  : 0x4f4c
08-26 19:45:10.990  7008  7008 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 19:45:10.990  7008  7008 D ActivityThread: Added TimaKeyStore provider
08-26 19:45:10.990  6990  7007 E FilterInstaller: installFilters
08-26 19:45:11.000  6990  7007 E FilterInstaller: There is no requred permission
08-26 19:45:11.000  1020  1258 I ActivityManager: Killing 6504:com.samsung.helphub/1000 (adj 15): empty #21
08-26 19:45:11.010  6676  6988 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-26 19:45:11.010  6676  6988 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-26 19:45:11.030  7008  7008 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-26 19:45:11.030  7008  7008 W ResourcesManager: Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,08-26 19:45:11.060  1879  1879 I SamsungIME: getDebugLevel  : 0x4f4c
,08-26 19:45:11.080  1879  1879 I SamsungIME: KeybaordView init() : load resources
,08-26 19:45:11.080  1020  4357 D ActivityManager: startProcessLocked calleePkgName: com.android.calendar, hostingType: broadcast
,08-26 19:45:11.090  1020  4357 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:45:11.090  1020  4357 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:45:11.090  1020  4357 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:45:11.090  1020  4357 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 19:45:11.110  7024  7024 E Zygote  : MountEmulatedStorage()
08-26 19:45:11.110  1020  4357 I ActivityManager: Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=7024 uid=10131 gids={50131, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
08-26 19:45:11.110  7024  7024 E Zygote  : v2
08-26 19:45:11.110  7024  7024 I libpersona: KNOX_SDCARD checking this for 10131
08-26 19:45:11.110  7024  7024 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-26 19:45:11.110  7024  7024 I libpersona: KNOX_SDCARD not a persona
,08-26 19:45:11.110  1879  1879 I SamsungIME: getCurrentKeyboard
08-26 19:45:11.110  1879  1879 I SamsungIME: getTextKeyboard
,08-26 19:45:11.110  7024  7024 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 19:45:11.110  7024  7024 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 19:45:11.140  1879  1879 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,08-26 19:45:11.150  7024  7024 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 19:45:11.150  7024  7024 D ActivityThread: Added TimaKeyStore provider
,08-26 19:45:11.150  6676  6988 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
,08-26 19:45:11.170  7024  7024 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,08-26 19:45:11.180  7024  7024 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-26 19:45:11.180  7024  7024 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-26 19:45:11.220  1020  1487 I art     : Explicit concurrent mark sweep GC freed 18434(980KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 22MB/34MB, paused 2.502ms total 155.873ms
,08-26 19:45:11.270  1020  1491 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,08-26 19:45:11.270  1020  1491 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
,08-26 19:45:11.270  1747  1775 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,08-26 19:45:11.270  1020  1491 W ActivityManager: userId = 0, bbcId = -10000
,08-26 19:45:11.270  1020  1491 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:45:11.270  1020  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,08-26 19:45:11.290  1972  4264 D Icing   : Loaded CLD2 Version V2.0 - 20141016
,08-26 19:45:11.300  1020  4267 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,08-26 19:45:11.300  1020  4267 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
,08-26 19:45:11.310  1020  4267 W ActivityManager: userId = 0, bbcId = -10000
,08-26 19:45:11.310  1020  4267 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:45:11.310  1020  4267 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,08-26 19:45:11.320  1020  1258 I ActivityManager: Killing 6515:com.sec.spp.push/u0a32 (adj 15): empty #21
,08-26 19:45:11.330  1020  1033 I ActivityManager: Killing 6483:com.sec.android.app.soundalive/u0a48 (adj 15): empty #21
,08-26 19:45:11.340  6676  6988 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,08-26 19:45:11.340  6676  6988 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@140d91f2: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
08-26 19:45:11.340  6676  6988 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-26 19:45:11.380  1972  4264 I Icing   : Indexing done D0AE1F45F393341DA3213A207506F1C2E721F1A9
,08-26 19:45:11.400  1020  1257 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,08-26 19:45:11.400  1020  1257 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:45:11.400  1020  1257 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 19:45:11.400  1020  1257 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 19:45:11.540  6761  6987 W jxcore-log: Initializing JXcore engine
08-26 19:45:11.540  6761  6987 W jxcore-log: JXcore engine is ready
,08-26 19:45:11.570  1020  1513 I ActivityManager: Killing 6570:com.sec.android.gallery3d/u0a39 (adj 15): empty #21
,08-26 19:45:11.600  2056  2056 E audit   : type=1400 msg=audit(1472233511.600:205): avc:  denied  { ioctl } for  pid=6987 comm="Thread-1270" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2071 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-26 19:45:11.600  2056  2056 E audit   :  SEPF_SM-A300FU_5.0.2-1_0051
08-26 19:45:11.600  2056  2056 E audit   : type=1300 msg=audit(1472233511.600:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=b a1=5451 a2=3 a3=9d4338f8 items=0 ppid=323 ppcomm=main pid=6987 auid=4294967295 uid=10170 gid=10170 euid=10170 suid=10170 fsuid=10170 egid=10170 sgid=10170 fsgid=10170 ses=4294967295 tty=(none) comm="Thread-1270" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
08-26 19:45:11.600  2056  2056 E audit   : type=1320 msg=audit(1472233511.600:205): 
,08-26 19:45:11.610  6761  6987 W jxcore-log: Starting JXcore engine
,08-26 19:45:11.720  6761  6987 W jxcore-log: Platform android
08-26 19:45:11.720  6761  6987 W jxcore-log: 
08-26 19:45:11.720  6761  6987 W jxcore-log: Process ARCH arm
08-26 19:45:11.720  6761  6987 W jxcore-log: 
,08-26 19:45:11.920  6761  6987 I jxcore-log: JXcore Cordova bridge is ready!
08-26 19:45:11.920  6761  6987 I jxcore-log: 
,08-26 19:45:11.920  6761  6987 W jxcore-log: JXcore engine is started
,08-26 19:45:11.930  6761  6886 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-26 19:45:11.930  6761  6761 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-26 19:45:12.200  6721  6721 I Mms/MmsApp:  start initViewCache mms
,08-26 19:45:12.200  6721  6721 D Mms/ComposeMessageFragment: [start]    fillCache consume time = 1801.455728
,08-26 19:45:12.200  6721  6721 D Mms/ComposeMessageFragment: fillCache, easy = false
,08-26 19:45:12.300  6721  6721 D AbsListView: Get MotionRecognitionManager
,08-26 19:45:12.300  1020  4266 D MotionRecognitionService:  ssp status : false
,08-26 19:45:12.300  6721  6721 D Mms/ComposeMessageFragment: [end]    fillCache consume time = 104.186667
,08-26 19:45:12.390  6721  6721 D Mms/BubbleViewCache: fillCache bubble = 1
,08-26 19:45:13.290  6546  6598 D AcmsKeyStoreHelper:  getKeyStoreForApplication Enter
,08-26 19:45:13.300  6546  6598 I AcmsKeyStoreHelper: Key Store exist
08-26 19:45:13.300  6546  6598 I AcmsKeyStoreHelper: Hence loading the keystore file
,08-26 19:45:13.360  6546  6598 D AcmsKeyStoreHelper:  getKeyStoreForApplication Exit
08-26 19:45:13.360  6546  6598 I AcmsCertificateMngr: getKeyStoreForApplication success 
08-26 19:45:13.360  6546  6598 D AcmsCore: Decremented Counter Value : AcmsCoreHandler.handleMessage=>1
08-26 19:45:13.360  6546  6598 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
08-26 19:45:13.360  6546  6598 D AcmsServiceMonitor: Decrementing - Counter value: 1
08-26 19:45:13.360  6546  6598 D AcmsCore: AcmsCore: ACMS_APP_INSTALLED
,08-26 19:45:13.360  6546  6598 D AcmsCore: This is NOT a valid MirrorLink app
08-26 19:45:13.360  6546  6598 D AcmsCore: Decremented Counter Value : AcmsCoreHandler.handleMessage=>2
08-26 19:45:13.360  6546  6598 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
08-26 19:45:13.360  6546  6598 D AcmsServiceMonitor: Decrementing - Counter value: 0
08-26 19:45:13.360  6546  6598 D AcmsServiceMonitor: Counter value is 0: Stopping ACMS service
,08-26 19:45:13.360  6546  6546 D AcmsServiceMonitor: getSvcCounter - Counter value: 0
08-26 19:45:13.360  6546  6546 D AcmsService: Enter onDestroy
08-26 19:45:13.360  6546  6546 I AcmsService: cleanUp(): inside service clean up
08-26 19:45:13.360  6546  6546 D AcmsCore: AcmsCore: inside DeInit
08-26 19:45:13.360  6546  6546 D AcmsCore: AcmsCore: mLooperHandler is not null and making it null
08-26 19:45:13.360  6546  6546 D AcmsCertificateMngr: AcmsCertificateMngr: inside cleanup
08-26 19:45:13.360  6546  6546 D AcmsRevocationMngr: AcmsRevocationMngr: inside cleanup
08-26 19:45:13.360  6546  6546 D AcmsKeyStoreHelper: KeyStoreHelper: inside cleanup
08-26 19:45:13.360  6546  6546 D AcmsAppEntryInterface: AppEntryInterface: Inside CleanUp
,08-26 19:45:13.370  6546  6546 D AcmsServiceMonitor: getSvcCounter - Counter value: 0
,08-26 19:45:13.370  6546  6546 D AcmsService: killing acms process
,08-26 19:45:13.370  6546  6546 I Process : Sending signal. PID: 6546 SIG: 9
,08-26 19:45:13.380   295   295 E SMD     : DCD OFF
,08-26 19:45:13.460  1020  1471 I ActivityManager: Process ACMS.Process (pid 6546)(adj 0) has died(37,753)
,08-26 19:45:14.270  1695  1695 I ConfigService: onDestroy
,08-26 19:45:14.780  1020  3320 D SSRM:n  : SIOP:: AP = 420
,08-26 19:45:15.190  1020  3338 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-26 19:45:16.380   295   295 E SMD     : DCD OFF
,08-26 19:45:18.340  1020  4267 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 19:45:18.340  1020  4267 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4278, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,08-26 19:45:18.340  1020  4267 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,08-26 19:45:18.340  1020  4267 D BatteryService: stay LED for charging
08-26 19:45:18.340  1020  1020 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 19:45:18.340  1020  1020 I MotionRecognitionService: Plugged
08-26 19:45:18.340  1020  1020 I MotionRecognitionService: mGripSensorEnabled= false
,08-26 19:45:18.350  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-26 19:45:18.350  1177  1177 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-26 19:45:18.350  1425  1425 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-26 19:45:18.350  1425  1425 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-26 19:45:18.370  3176  3176 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 19:45:18.370  3176  3314 D HeadsetStateMachine: Disconnected process message: 10
,08-26 19:45:18.380  1177  1177 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-26 19:45:18.380  1177  1177 D SViewCoverView: level :100 plugged : 2
,08-26 19:45:18.380  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 19:45:18.380  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 19:45:18.380  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 19:45:18.940  1020  1061 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,08-26 19:45:19.380   295   295 E SMD     : DCD OFF
,08-26 19:45:20.770  1020  1333 E Watchdog: !@Sync 3
,08-26 19:45:20.840  1020  1061 D PackageManager: [MSG] MCS_UNBIND
,08-26 19:45:20.840  1020  1468 I ActivityManager: Killing 6537:com.google.android.googlequicksearchbox:search/u0a52 (adj 15): empty #21
,08-26 19:45:21.930   334   334 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
08-26 19:45:21.930   334   334 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,08-26 19:45:22.380   295   295 E SMD     : DCD OFF
,08-26 19:45:24.100  6761  6987 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native,
08-26 19:45:24.100  6761  6987 I jxcore-log: 
,08-26 19:45:24.100  6761  6987 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native,
08-26 19:45:24.100  6761  6987 I jxcore-log: 
,08-26 19:45:24.110  6761  6987 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
08-26 19:45:24.110  6761  6987 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:45:24.110  6761  6987 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 19:45:24.110  6761  6987 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 19:45:24.110  6761  6987 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 19:45:24.110  6761  6987 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 19:45:24.110  6761  6987 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 19:45:24.110  6761  6987 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 19:45:24.110  6761  6987 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 19:45:24.110  6761  6987 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-26 19:45:24.110  6761  6987 I jxcore-log: 
,08-26 19:45:24.110  6761  6987 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-26 19:45:24.110  6761  6987 I jxcore-log: 
,08-26 19:45:24.520  1020  1100 V AlarmManager: waitForAlarm result :4
,08-26 19:45:24.520  1020  1100 D ActivityManager: retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,08-26 19:45:24.750  6694  6805 D Finsky  : [1249] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,08-26 19:45:24.750  6694  6694 D Finsky  : [1] 5.onFinished: Installation state replication succeeded.
,08-26 19:45:24.790  1020  1054 I PowerManagerService: [PWL] Off : 50s ago
,08-26 19:45:24.810  1020  3320 D SSRM:n  : SIOP:: AP = 400,
,08-26 19:45:24.810  6761  6987 D executeNativeTests: Running unit tests,
,08-26 19:45:24.900  6761  6987 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 19:45:24.900  6761  6987 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@37f10982 added. We now have 2 listener(s)
,08-26 19:45:24.900  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,08-26 19:45:24.900  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 19:45:24.900  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 19:45:24.900  6761  6987 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 19:45:24.900  6761  6987 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f12d893 added. We now have 2 listener(s)
08-26 19:45:24.900  6761  6987 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 19:45:24.900  6761  6987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-26 19:45:24.900  6761  6987 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 19:45:24.910  6761  6987 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 19:45:24.910  6761  6987 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:45:24.910  6761  6987 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 19:45:24.910  6761  6987 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 19:45:24.910  6761  6987 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 19:45:24.910  6761  6987 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 19:45:24.910  6761  6987 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 19:45:24.910  6761  6987 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 19:45:24.910  6761  6987 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 19:45:24.910  6761  6987 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 19:45:24.910  6761  6761 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:45:24.910  6761  6987 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-26 19:45:24.910  6761  6987 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-26 19:45:24.910  6761  6987 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-26 19:45:24.910  6761  6987 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,08-26 19:45:24.910  6761  6987 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-26 19:45:24.910  6761  6987 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-26 19:45:24.910  6761  6987 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-26 19:45:24.910  6761  6987 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-26 19:45:24.910  6761  6987 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 19:45:24.910  6761  6987 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 19:45:24.910  6761  6987 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-26 19:45:24.910  6761  6987 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:45:24.910  6761  6987 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:24.910  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 19:45:24.910  6761  6987 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 19:45:24.910  6761  6987 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@37f10982 removed from the list
08-26 19:45:24.910  6761  6987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:45:24.910  6761  6987 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f12d893 removed from the list
,08-26 19:45:24.920  6761  6761 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 19:45:24.920  6761  6987 D io.jxcore.node.ConnectivityMonitor: stop
08-26 19:45:24.920  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 19:45:24.920  6761  6987 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:24.920  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 19:45:24.920  6761  6987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 19:45:24.920  6761  6987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:45:24.920  6761  6987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:45:24.920  6761  6987 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f12d893 not in the list
,08-26 19:45:24.920  6761  6987 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,08-26 19:45:24.920  6761  6987 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 19:45:24.920  6761  6987 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-26 19:45:24.930  6761  6987 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...,
08-26 19:45:24.930  6761  6987 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:45:24.930  6761  6987 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:24.930  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:24.930  6761  6987 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@37f10982 not in the list
,08-26 19:45:24.930  6761  6987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:45:24.930  6761  6987 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f12d893 not in the list
08-26 19:45:24.930  6761  6987 D io.jxcore.node.ConnectivityMonitor: stop
08-26 19:45:24.930  6761  6987 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:24.930  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 19:45:24.930  6761  6987 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:24.930  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:24.930  6761  6987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 19:45:24.930  6761  6987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:45:24.930  6761  6987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:45:24.930  6761  6987 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f12d893 not in the list,
,08-26 19:45:24.930  6761  6987 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55],
08-26 19:45:24.930  6761  6987 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-26 19:45:24.930  6761  6987 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-26 19:45:24.930  6761  6987 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-26 19:45:24.930  6761  6987 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,08-26 19:45:24.930  6761  6987 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-26 19:45:24.930  6761  6987 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,08-26 19:45:24.930  6761  6987 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-26 19:45:24.930  6761  6987 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-26 19:45:24.930  6761  6987 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,08-26 19:45:24.930  6761  6987 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-26 19:45:24.930  6761  6987 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-26 19:45:24.930  6761  6987 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-26 19:45:24.930  6761  6987 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-26 19:45:24.930  6761  6987 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
,08-26 19:45:24.930  6761  6987 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-26 19:45:24.930  6761  6987 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-26 19:45:24.930  6761  6987 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-26 19:45:24.930  6761  6987 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-26 19:45:24.930  6761  6987 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
,08-26 19:45:24.930  6761  6987 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-26 19:45:24.930  6761  6987 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-26 19:45:24.930  6761  6987 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-26 19:45:24.930  6761  6987 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
,08-26 19:45:24.930  6761  6987 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-26 19:45:24.930  6761  6987 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-26 19:45:24.930  6761  6987 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-26 19:45:24.930  6761  6987 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-26 19:45:24.930  6761  6987 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-26 19:45:24.930  6761  6987 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-26 19:45:24.930  6761  6987 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-26 19:45:24.930  6761  6987 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 19:45:24.930  6761  6987 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 19:45:24.930  6761  6987 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 19:45:24.930  6761  6987 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:45:24.930  6761  6987 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:24.930  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 19:45:24.930  6761  6987 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@37f10982 not in the list
08-26 19:45:24.930  6761  6987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:45:24.930  6761  6987 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f12d893 not in the list
,08-26 19:45:24.930  6761  6987 D io.jxcore.node.ConnectivityMonitor: stop
08-26 19:45:24.930  6761  6987 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:24.930  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:24.930  6761  6987 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:24.930  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 19:45:24.930  6761  6987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 19:45:24.930  6761  6987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:45:24.930  6761  6987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:45:24.930  6761  6987 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f12d893 not in the list
08-26 19:45:24.940  6761  6987 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-26 19:45:24.940  6761  6987 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 19:45:24.940  6761  6987 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 19:45:24.940  6761  6987 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:45:24.940  6761  6987 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
,08-26 19:45:24.940  6761  6987 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 19:45:24.940  6761  6987 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 19:45:24.940  6761  6987 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 19:45:24.940  6761  6987 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
,08-26 19:45:24.940  6761  6987 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 19:45:24.940  6761  6987 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 19:45:24.940  6761  6987 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 19:45:24.940  6761  6987 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 19:45:24.940  6761  6987 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 19:45:24.940  6761  6987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 19:45:24.940  6761  6987 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 19:45:24.940  6761  6987 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-26 19:45:24.950  6761  6761 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 19:45:24.950  6761  6761 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 19:45:24.950  6761  6987 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-26 19:45:24.950  6761  6987 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-26 19:45:24.960  6761  6987 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-26 19:45:24.960  6761  6987 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,08-26 19:45:24.960  6761  6987 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
08-26 19:45:24.960  6761  6987 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-26 19:45:24.960  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-26 19:45:24.960  6761  6987 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-26 19:45:24.970  3176  3309 D BtGatt.GattService: registerClient() - UUID=c8b24dba-4528-4b03-8b1a-4249a344edb1
,08-26 19:45:25.020  3176  3250 D BtGatt.GattService: onClientRegistered() - UUID=c8b24dba-4528-4b03-8b1a-4249a344edb1, clientIf=6
,08-26 19:45:25.020  6761  6776 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-26 19:45:25.020  3176  3184 D BtGatt.GattService: start scan with filters,
08-26 19:45:25.020  3176  3313 D BtGatt.ScanManager: handling starting scan
,08-26 19:45:25.020  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-26 19:45:25.020  6761  6987 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-26 19:45:25.020  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-26 19:45:25.020  6761  6987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-26 19:45:25.030  6761  6987 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 19:45:25.030  3176  3313 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@247e950f
,08-26 19:45:25.040  6761  6761 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 19:45:25.040  6761  6987 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-26 19:45:25.040  3176  3250 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-26 19:45:25.040  3176  3250 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 19:45:25.040  3176  3313 D BtGatt.ScanManager: allow scan with filters
,08-26 19:45:25.040  3176  3313 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,08-26 19:45:25.040  3176  3313 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
,08-26 19:45:25.050  6761  6987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-26 19:45:25.050  3176  3250 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-26 19:45:25.050  3176  3250 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 19:45:25.050  3176  3313 D BtGatt.ScanManager: Starting BLE batch scan
,08-26 19:45:25.050  3176  3313 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-26 19:45:25.050  6761  6987 I io.jxcore.node.ConnectionHelper: start: OK
,08-26 19:45:25.060  6761  6987 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 19:45:25.060  6761  6987 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-26 19:45:25.060  6761  6987 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-26 19:45:25.060  6761  6987 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-26 19:45:25.060  6761  6987 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:25.060  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-26 19:45:25.060  6761  6987 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-26 19:45:25.060  6761  6987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-26 19:45:25.060  6761  6987 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 19:45:25.060  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-26 19:45:25.060  6761  6987 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-26 19:45:25.060  6761  6987 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-26 19:45:25.060  3176  3309 D BtGatt.GattService: stopScan() - queue size =1
,08-26 19:45:25.060  3176  3184 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-26 19:45:25.060  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 19:45:25.060  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-26 19:45:25.060  6761  6987 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-26 19:45:25.060  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-26 19:45:25.060  6761  6987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-26 19:45:25.070  6761  6987 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 19:45:25.070  3176  3250 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
08-26 19:45:25.070  3176  3250 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 19:45:25.070  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-26 19:45:25.070  6761  6987 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-26 19:45:25.070  6761  6987 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-26 19:45:25.070  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 19:45:25.070  6761  6987 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:45:25.070  6761  6761 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 19:45:25.070  6761  6987 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:25.070  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 19:45:25.070  6761  6987 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@37f10982 not in the list
08-26 19:45:25.070  6761  6987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:45:25.070  6761  6987 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f12d893 not in the list
08-26 19:45:25.070  6761  6987 D io.jxcore.node.ConnectivityMonitor: stop
08-26 19:45:25.070  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 19:45:25.070  6761  6987 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-26 19:45:25.070  6761  6761 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 19:45:25.070  6761  6761 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 19:45:25.070  3176  3250 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
08-26 19:45:25.070  3176  3250 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 19:45:25.080  6761  6987 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 19:45:25.080  6761  6987 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 19:45:25.080  6761  6987 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:45:25.080  6761  6987 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 19:45:25.080  6761  6987 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 19:45:25.080  6761  6987 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 19:45:25.080  6761  6987 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 19:45:25.080  6761  6987 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 19:45:25.080  6761  6987 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 19:45:25.080  3176  3313 D BtGatt.ScanManager: filter size is 1
08-26 19:45:25.080  6761  6987 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 19:45:25.080  6761  6987 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 19:45:25.080  6761  6987 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 19:45:25.080  6761  6987 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 19:45:25.080  6761  6987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 19:45:25.080  6761  6987 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 19:45:25.080  6761  6987 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-26 19:45:25.080  3176  3313 D BtGatt.ScanManager: delete FilterIndex - 3
,08-26 19:45:25.090  6761  6761 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 19:45:25.090  3176  3250 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,08-26 19:45:25.090  3176  3250 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 19:45:25.090  6761  6987 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-26 19:45:25.090  3176  3313 D BtGatt.ScanManager: stopping BLe Batch
,08-26 19:45:25.090  6761  6761 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 19:45:25.100  3176  3250 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,08-26 19:45:25.100  3176  3250 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 19:45:25.100  3176  3313 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-26 19:45:25.100  6761  6987 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-26 19:45:25.100  6761  6987 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-26 19:45:25.110  3176  3250 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-26 19:45:25.110  6761  6987 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-26 19:45:25.110  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-26 19:45:25.110  6761  6987 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-26 19:45:25.110  3176  3250 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 19:45:25.110  3176  3184 D BtGatt.GattService: registerClient() - UUID=9a0c2bc3-08ec-4142-8587-0409a99f16ff
,08-26 19:45:25.160  3176  3250 D BtGatt.GattService: onClientRegistered() - UUID=9a0c2bc3-08ec-4142-8587-0409a99f16ff, clientIf=6
,08-26 19:45:25.160  6761  6776 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
08-26 19:45:25.160  3176  3310 D BtGatt.GattService: start scan with filters
,08-26 19:45:25.160  3176  3313 D BtGatt.ScanManager: handling starting scan
,08-26 19:45:25.160  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-26 19:45:25.160  6761  6987 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-26 19:45:25.160  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-26 19:45:25.160  6761  6987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-26 19:45:25.160  3176  3250 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-26 19:45:25.160  3176  3250 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 19:45:25.160  3176  3313 D BtGatt.ScanManager: allow scan with filters
,08-26 19:45:25.160  3176  3313 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,08-26 19:45:25.160  3176  3313 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
,08-26 19:45:25.160  6761  6987 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 19:45:25.160  6761  6761 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 19:45:25.170  6761  6987 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-26 19:45:25.170  3176  3250 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-26 19:45:25.170  3176  3250 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 19:45:25.170  3176  3313 D BtGatt.ScanManager: Starting BLE batch scan
,08-26 19:45:25.170  3176  3313 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-26 19:45:25.170  6761  6987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-26 19:45:25.180  6761  6987 I io.jxcore.node.ConnectionHelper: start: OK
,08-26 19:45:25.180  3176  3250 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-26 19:45:25.180  3176  3250 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 19:45:25.180  6761  6987 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 19:45:25.190  6761  6987 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-26 19:45:25.190  6761  6987 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-26 19:45:25.190  6761  6987 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-26 19:45:25.190  6761  6987 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 19:45:25.190  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-26 19:45:25.190  6761  6987 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-26 19:45:25.190  6761  6987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-26 19:45:25.190  6761  6987 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 19:45:25.190  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-26 19:45:25.190  6761  6987 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-26 19:45:25.190  6761  6987 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-26 19:45:25.190  3176  3250 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-26 19:45:25.190  3176  3250 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 19:45:25.190  3176  3309 D BtGatt.GattService: stopScan() - queue size =1
,08-26 19:45:25.190  3176  3313 D BtGatt.ScanManager: filter size is 1
,08-26 19:45:25.190  3176  3313 D BtGatt.ScanManager: delete FilterIndex - 4
,08-26 19:45:25.200  3176  3184 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-26 19:45:25.200  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-26 19:45:25.200  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-26 19:45:25.200  6761  6987 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-26 19:45:25.200  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-26 19:45:25.200  6761  6987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-26 19:45:25.200  6761  6987 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 19:45:25.200  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-26 19:45:25.200  6761  6987 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-26 19:45:25.200  6761  6987 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-26 19:45:25.200  3176  3250 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-26 19:45:25.200  3176  3250 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 19:45:25.200  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 19:45:25.200  3176  3313 D BtGatt.ScanManager: stopping BLe Batch
,08-26 19:45:25.200  6761  6761 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-26 19:45:25.200  6761  6761 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 19:45:25.210  6761  6987 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:45:25.210  6761  6987 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:25.210  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 19:45:25.210  6761  6987 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@37f10982 not in the list
08-26 19:45:25.210  6761  6987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:45:25.210  6761  6987 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f12d893 not in the list
08-26 19:45:25.210  6761  6987 D io.jxcore.node.ConnectivityMonitor: stop
08-26 19:45:25.210  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 19:45:25.210  6761  6761 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 19:45:25.210  6761  6987 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 19:45:25.210  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 19:45:25.210  6761  6987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-26 19:45:25.210  6761  6987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:45:25.210  6761  6987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 19:45:25.210  6761  6987 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f12d893 not in the list
,08-26 19:45:25.210  3176  3250 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,08-26 19:45:25.210  3176  3250 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 19:45:25.210  3176  3313 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-26 19:45:25.210  6761  6987 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-26 19:45:25.220  6761  6987 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 19:45:25.220  3176  3250 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,08-26 19:45:25.220  3176  3250 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 19:45:25.220  6761  6987 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 19:45:25.220  6761  6987 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:45:25.220  6761  6987 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 19:45:25.220  6761  6987 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 19:45:25.220  6761  6987 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 19:45:25.220  6761  6987 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 19:45:25.220  6761  6987 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 19:45:25.220  6761  6987 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 19:45:25.230  6761  6987 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 19:45:25.230  6761  6987 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 19:45:25.230  6761  6987 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 19:45:25.230  6761  6987 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 19:45:25.230  6761  6987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 19:45:25.230  6761  6987 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 19:45:25.230  6761  6987 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-26 19:45:25.230  6761  6761 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 19:45:25.230  6761  6987 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...,
,08-26 19:45:25.230  6761  6761 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 19:45:25.240  6761  6987 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-26 19:45:25.240  6761  6987 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-26 19:45:25.240  6761  6987 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-26 19:45:25.240  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-26 19:45:25.240  6761  6987 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-26 19:45:25.250  3176  3310 D BtGatt.GattService: registerClient() - UUID=cb8404e8-277e-4e99-bbe5-8825dcd5ef9e
,08-26 19:45:25.290  3176  3250 D BtGatt.GattService: onClientRegistered() - UUID=cb8404e8-277e-4e99-bbe5-8825dcd5ef9e, clientIf=6
,08-26 19:45:25.290  6761  6774 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-26 19:45:25.290  3176  3185 D BtGatt.GattService: start scan with filters
,08-26 19:45:25.290  3176  3313 D BtGatt.ScanManager: handling starting scan
,08-26 19:45:25.290  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-26 19:45:25.290  6761  6987 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-26 19:45:25.290  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-26 19:45:25.290  6761  6987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-26 19:45:25.290  6761  6987 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 19:45:25.300  6761  6761 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 19:45:25.300  3176  3250 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-26 19:45:25.300  3176  3250 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 19:45:25.300  3176  3313 D BtGatt.ScanManager: allow scan with filters
,08-26 19:45:25.300  3176  3313 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,08-26 19:45:25.300  3176  3313 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
,08-26 19:45:25.300  6761  6987 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-26 19:45:25.300  3176  3250 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-26 19:45:25.300  3176  3250 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 19:45:25.310  3176  3313 D BtGatt.ScanManager: Starting BLE batch scan
,08-26 19:45:25.310  3176  3313 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
08-26 19:45:25.310  6761  6987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-26 19:45:25.310  3176  3250 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-26 19:45:25.310  3176  3250 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 19:45:25.310  6761  6987 I io.jxcore.node.ConnectionHelper: start: OK
,08-26 19:45:25.310  6761  6987 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 19:45:25.310  6761  6987 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-26 19:45:25.320  6761  6987 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-26 19:45:25.320  6761  6987 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-26 19:45:25.320  6761  6987 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:25.320  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-26 19:45:25.320  6761  6987 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-26 19:45:25.320  6761  6987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-26 19:45:25.320  6761  6987 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 19:45:25.320  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-26 19:45:25.320  6761  6987 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-26 19:45:25.320  6761  6987 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-26 19:45:25.320  3176  3250 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-26 19:45:25.320  3176  3250 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 19:45:25.320  3176  3310 D BtGatt.GattService: stopScan() - queue size =1
,08-26 19:45:25.320  3176  3313 D BtGatt.ScanManager: filter size is 1
,08-26 19:45:25.320  3176  3313 D BtGatt.ScanManager: delete FilterIndex - 5
,08-26 19:45:25.330  3176  3185 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-26 19:45:25.330  3176  3250 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,08-26 19:45:25.330  3176  3250 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 19:45:25.330  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-26 19:45:25.330  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-26 19:45:25.330  6761  6987 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-26 19:45:25.330  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-26 19:45:25.330  6761  6987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-26 19:45:25.330  6761  6987 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 19:45:25.330  3176  3313 D BtGatt.ScanManager: stopping BLe Batch
,08-26 19:45:25.330  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-26 19:45:25.330  6761  6987 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-26 19:45:25.330  6761  6987 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-26 19:45:25.330  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 19:45:25.330  6761  6761 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-26 19:45:25.340  6761  6761 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 19:45:25.340  6761  6761 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 19:45:25.340  6761  6987 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 19:45:25.340  6761  6987 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-26 19:45:25.340  6761  6987 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 19:45:25.340  6761  6987 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 19:45:25.340  6761  6987 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:45:25.340  6761  6987 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:25.340  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 19:45:25.340  6761  6987 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@37f10982 not in the list
08-26 19:45:25.340  6761  6987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:45:25.340  6761  6987 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f12d893 not in the list
08-26 19:45:25.340  6761  6987 D io.jxcore.node.ConnectivityMonitor: stop
08-26 19:45:25.340  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:25.340  6761  6987 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:25.340  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 19:45:25.340  6761  6987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
08-26 19:45:25.340  6761  6987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-26 19:45:25.340  6761  6987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:45:25.340  6761  6987 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f12d893 not in the list
,08-26 19:45:25.340  6761  6987 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-26 19:45:25.340  6761  6987 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 19:45:25.340  6761  6987 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-26 19:45:25.340  6761  6987 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 19:45:25.340  6761  6987 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose,
08-26 19:45:25.340  6761  6987 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 19:45:25.340  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
08-26 19:45:25.340  6761  6987 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@37f10982 not in the list
,08-26 19:45:25.340  6761  6987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:45:25.340  6761  6987 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f12d893 not in the list
08-26 19:45:25.340  6761  6987 D io.jxcore.node.ConnectivityMonitor: stop
,08-26 19:45:25.340  6761  6987 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:25.340  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:25.340  6761  6987 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:25.340  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:25.340  3176  3250 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0,
,08-26 19:45:25.340  3176  3250 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 19:45:25.340  6761  6987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 19:45:25.340  6761  6987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:45:25.340  6761  6987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:45:25.340  6761  6987 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f12d893 not in the list
08-26 19:45:25.340  3176  3313 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
08-26 19:45:25.340  6761  6987 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-26 19:45:25.340  6761  6987 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 19:45:25.340  6761  6987 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 19:45:25.340  6761  6987 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-26 19:45:25.340  6761  6987 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:45:25.340  6761  6987 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:25.340  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 19:45:25.340  6761  6987 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@37f10982 not in the list
08-26 19:45:25.340  6761  6987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:45:25.340  6761  6987 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f12d893 not in the list
,08-26 19:45:25.340  6761  6987 D io.jxcore.node.ConnectivityMonitor: stop
08-26 19:45:25.340  6761  6987 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:25.340  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:25.340  6761  6987 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-26 19:45:25.340  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:25.350  6761  6987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 19:45:25.350  6761  6987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-26 19:45:25.350  6761  6987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:45:25.350  6761  6987 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f12d893 not in the list
08-26 19:45:25.350  6761  6987 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-26 19:45:25.350  6761  6987 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 19:45:25.350  6761  6987 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 19:45:25.350  6761  6987 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 19:45:25.350  6761  6987 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-26 19:45:25.350  6761  6987 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:25.350  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:25.350  6761  6987 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@37f10982 not in the list
08-26 19:45:25.350  6761  6987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 19:45:25.350  6761  6987 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f12d893 not in the list
08-26 19:45:25.350  6761  6987 D io.jxcore.node.ConnectivityMonitor: stop
08-26 19:45:25.350  6761  6987 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:25.350  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:25.350  6761  6987 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 19:45:25.350  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:25.350  3176  3250 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-26 19:45:25.350  3176  3250 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 19:45:25.350  6761  6987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 19:45:25.350  6761  6987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:45:25.350  6761  6987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 19:45:25.350  6761  6987 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f12d893 not in the list
08-26 19:45:25.350  6761  6987 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-26 19:45:25.350  6761  6987 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 19:45:25.350  6761  6987 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-26 19:45:25.350  6761  6987 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-26 19:45:25.350  6761  6987 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:45:25.350  6761  6987 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 19:45:25.350  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:25.350  6761  6987 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@37f10982 not in the list
,08-26 19:45:25.350  6761  6987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 19:45:25.350  6761  6987 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f12d893 not in the list
08-26 19:45:25.350  6761  6987 D io.jxcore.node.ConnectivityMonitor: stop
08-26 19:45:25.350  6761  6987 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:25.350  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 19:45:25.350  6761  6987 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:25.350  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:25.350  6761  6987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-26 19:45:25.350  6761  6987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:45:25.350  6761  6987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:45:25.350  6761  6987 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f12d893 not in the list
08-26 19:45:25.350  6761  6987 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-26 19:45:25.350  6761  6987 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-26 19:45:25.350  6761  6987 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-26 19:45:25.350  6761  6987 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-26 19:45:25.350  6761  6987 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-26 19:45:25.350  6761  6987 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-26 19:45:25.350  6761  6987 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 19:45:25.350  6761  6987 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 19:45:25.350  6761  6987 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 19:45:25.350  6761  6987 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-26 19:45:25.350  6761  6987 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:25.350  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:25.350  6761  6987 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@37f10982 not in the list
08-26 19:45:25.350  6761  6987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:45:25.350  6761  6987 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f12d893 not in the list
,08-26 19:45:25.350  6761  6987 D io.jxcore.node.ConnectivityMonitor: stop
08-26 19:45:25.350  6761  6987 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:25.350  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:25.350  6761  6987 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 19:45:25.360  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:25.360  6761  6987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 19:45:25.360  6761  6987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:45:25.360  6761  6987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:45:25.360  6761  6987 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f12d893 not in the list
,08-26 19:45:25.360  6761  6987 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 19:45:25.360  6761  6987 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55,
,08-26 19:45:25.360  6761  6987 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-26 19:45:25.360  6761  6987 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 19:45:25.360  6761  6987 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-26 19:45:25.360  6761  6987 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,08-26 19:45:25.360  6761  6987 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-26 19:45:25.360  6761  6987 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-26 19:45:25.360  6761  6987 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-26 19:45:25.360  6761  6987 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,08-26 19:45:25.360  6761  6987 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-26 19:45:25.360  6761  6987 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-26 19:45:25.360  6761  6987 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-26 19:45:25.360  6761  6987 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-26 19:45:25.360  6761  6987 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
,08-26 19:45:25.360  6761  6987 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-26 19:45:25.360  6761  6987 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-26 19:45:25.360  6761  6987 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-26 19:45:25.360  6761  6987 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-26 19:45:25.360  6761  6987 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
,08-26 19:45:25.360  6761  6987 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-26 19:45:25.360  6761  6987 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-26 19:45:25.360  6761  6987 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-26 19:45:25.360  6761  6987 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-26 19:45:25.360  6761  6987 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,08-26 19:45:25.360  6761  6987 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-26 19:45:25.360  6761  6987 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-26 19:45:25.360  6761  6987 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-26 19:45:25.360  6761  6987 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-26 19:45:25.360  6761  6987 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-26 19:45:25.360  6761  6987 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-26 19:45:25.360  6761  6987 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-26 19:45:25.360  6761  6987 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-26 19:45:25.360  6761  6987 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-26 19:45:25.360  6761  6987 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-26 19:45:25.360  6761  6987 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-26 19:45:25.360  6761  6987 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-26 19:45:25.360  6761  6987 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-26 19:45:25.360  6761  6987 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 19:45:25.360  6761  6987 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-26 19:45:25.360  6761  6987 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-26 19:45:25.360  6761  6987 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 19:45:25.360  6761  6987 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-26 19:45:25.370  6761  6987 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-26 19:45:25.370  6761  6987 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-26 19:45:25.370  6761  6987 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-26 19:45:25.370  6761  6987 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-26 19:45:25.370  6761  6987 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-26 19:45:25.370  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-26 19:45:25.370  6761  6987 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-26 19:45:25.370  6761  6987 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 19:45:25.370  6761  6987 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-26 19:45:25.370  6761  6987 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 19:45:25.370  6761  6987 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 19:45:25.370  6761  6987 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 19:45:25.370  6761  6987 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:45:25.370  6761  6987 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:25.370  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:25.370  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-26 19:45:25.370  6761  7055 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 1334)
08-26 19:45:25.370  6761  6987 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@37f10982 not in the list
08-26 19:45:25.370  6761  6987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:45:25.370  6761  6987 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f12d893 not in the list
08-26 19:45:25.370  6761  6987 D io.jxcore.node.ConnectivityMonitor: stop
08-26 19:45:25.370  6761  6987 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:25.370  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:25.370  6761  6987 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:25.370  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:25.370  6761  6987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 19:45:25.370  6761  6987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:45:25.370  6761  6987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:45:25.370  6761  6987 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f12d893 not in the list
08-26 19:45:25.370  6761  6987 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-26 19:45:25.380  6761  7056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 1334
08-26 19:45:25.380  6761  6987 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 19:45:25.380  6761  6987 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 19:45:25.380  6761  6987 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 19:45:25.380  6761  6987 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:45:25.380  6761  6987 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:25.380  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:25.380  6761  6987 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@37f10982 not in the list
08-26 19:45:25.380  6761  6987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:45:25.380  6761  6987 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f12d893 not in the list
08-26 19:45:25.380  6761  6987 D io.jxcore.node.ConnectivityMonitor: stop
08-26 19:45:25.380  6761  6987 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:25.380  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:25.380  6761  6987 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:25.380  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:25.380  6761  6987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 19:45:25.380  6761  6987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:45:25.380  6761  6987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:45:25.380  6761  6987 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f12d893 not in the list
08-26 19:45:25.380  6761  6987 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-26 19:45:25.380  6761  6987 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 19:45:25.380  6761  6987 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 19:45:25.380  6761  6987 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 19:45:25.380  6761  6987 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:45:25.380  6761  6987 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:25.380  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:25.380  6761  6987 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@37f10982 not in the list
08-26 19:45:25.380  6761  6987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:45:25.380  6761  6987 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f12d893 not in the list
08-26 19:45:25.380  6761  6987 D io.jxcore.node.ConnectivityMonitor: stop
08-26 19:45:25.380  6761  6987 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:25.380  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:25.380  6761  6987 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:25.380  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:25.380  6761  6987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 19:45:25.380  6761  6987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:45:25.380  6761  6987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:45:25.380  6761  6987 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f12d893 not in the list
08-26 19:45:25.380  6761  6987 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-26 19:45:25.380  6761  6987 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-26 19:45:25.380  6761  6987 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-26 19:45:25.380  6761  6987 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-26 19:45:25.380  6761  6987 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-26 19:45:25.380  6761  6987 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-26 19:45:25.380  6761  6987 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-26 19:45:25.380  6761  6987 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-26 19:45:25.380  6761  6987 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-26 19:45:25.380  6761  6987 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-26 19:45:25.380  6761  6987 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-26 19:45:25.380  6761  6987 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-26 19:45:25.380  6761  6987 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 19:45:25.380  6761  6987 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 19:45:25.380  6761  6987 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 19:45:25.380  6761  6987 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:45:25.380  6761  6987 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:25.380  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:25.380  6761  6987 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@37f10982 not in the list
08-26 19:45:25.380  6761  6987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:45:25.380  6761  6987 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f12d893 not in the list
08-26 19:45:25.380  6761  6987 D io.jxcore.node.ConnectivityMonitor: stop
08-26 19:45:25.380  6761  6987 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:25.380  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:25.380  6761  6987 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:25.380  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:25.380   295   295 E SMD     : DCD OFF
08-26 19:45:25.380  6761  6987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 19:45:25.380  6761  6987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:45:25.380  6761  6987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:45:25.380  6761  6987 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f12d893 not in the list
08-26 19:45:25.390  6761  6987 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:45:25.390  6761  6987 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:25.390  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:25.390  6761  6987 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@37f10982 not in the list
08-26 19:45:25.390  6761  6987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:45:25.390  6761  6987 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f12d893 not in the list
08-26 19:45:25.390  6761  6987 D io.jxcore.node.ConnectivityMonitor: stop
08-26 19:45:25.390  6761  6987 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:25.390  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:25.390  6761  7055 D BluetoothUtils: isSocketAllowedBySecurityPolicy start : device null
08-26 19:45:25.390  6761  6987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:45:25.390  6761  6987 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f12d893 not in the list
08-26 19:45:25.390  6761  6987 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:45:25.390  6761  6987 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:25.390  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:25.390  6761  6987 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@37f10982 not in the list
08-26 19:45:25.390  6761  6987 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 19:45:25.390  6761  6987 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 19:45:25.390  6761  6987 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 19:45:25.390  6761  6987 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:45:25.390  6761  6987 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:25.390  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:25.390  6761  6987 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@37f10982 not in the list
08-26 19:45:25.390  6761  6987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:45:25.390  6761  6987 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f12d893 not in the list
08-26 19:45:25.390  6761  6987 D io.jxcore.node.ConnectivityMonitor: stop
08-26 19:45:25.390  6761  6987 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:25.390  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:25.390  6761  6987 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:25.390  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:25.390  6761  6987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 19:45:25.390  6761  6987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:45:25.390  6761  6987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:45:25.390  6761  6987 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f12d893 not in the list
08-26 19:45:25.390  6761  7055 D BluetoothSocket: connect(): myUserId = 0
08-26 19:45:25.390  6761  6987 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-26 19:45:25.390  6761  7055 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 19:45:25.390  6761  6987 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 19:45:25.390  6761  6987 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-26 19:45:25.390  6761  6987 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-26 19:45:25.390  6761  6987 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-26 19:45:25.390  6761  6987 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-26 19:45:25.390  6761  6987 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-26 19:45:25.390  6761  6987 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:45:25.390  6761  6987 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-26 19:45:25.390  6761  6987 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-26 19:45:25.390  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-26 19:45:25.390  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:25.390  6761  6987 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-26 19:45:25.390  6761  6987 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@37f10982 not in the list
08-26 19:45:25.390  6761  6987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:45:25.390  6761  6761 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-26 19:45:25.390  6761  6987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-26 19:45:25.390  6761  6987 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 19:45:25.390  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-26 19:45:25.390  6761  6761 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-26 19:45:25.390  6761  6987 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:25.390  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:25.390  3176  3185 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 19:45:25.400  6761  7057 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-26 19:45:25.400  6761  7057 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-26 19:45:25.400  6761  7055 D BluetoothSocket: connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[104]}
08-26 19:45:25.400  6761  6987 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 19:45:25.400  6761  6761 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 19:45:25.400  6761  6761 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 19:45:25.400  6761  6761 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-26 19:45:25.400  6761  6761 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 19:45:25.400  6761  6987 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f12d893 not in the list
08-26 19:45:25.400  6761  6987 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 19:45:25.400  6761  6987 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 19:45:25.400  6761  6987 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 19:45:25.400  6761  6987 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:45:25.400  6761  6987 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:25.400  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:25.400  6761  6987 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@37f10982 not in the list
08-26 19:45:25.400  6761  6987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:45:25.400  6761  6987 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f12d893 not in the list
08-26 19:45:25.400  6761  6987 D io.jxcore.node.ConnectivityMonitor: stop
08-26 19:45:25.400  6761  6987 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:25.400  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:25.400  6761  6987 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:25.400  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:25.400  6761  6987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 19:45:25.400  6761  6987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:45:25.400  6761  6987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:45:25.400  6761  6987 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f12d893 not in the list
08-26 19:45:25.400  6761  6987 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-26 19:45:25.400  6761  6987 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-26 19:45:25.400  6761  6987 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-26 19:45:25.400  6761  6987 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-26 19:45:25.400  6761  6987 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 19:45:25.400  6761  6987 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 19:45:25.400  6761  6987 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 19:45:25.400  6761  6987 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:45:25.400  6761  6987 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:25.400  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:25.400  6761  6987 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@37f10982 not in the list
08-26 19:45:25.400  6761  6987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:45:25.400  6761  6987 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f12d893 not in the list
08-26 19:45:25.400  6761  6987 D io.jxcore.node.ConnectivityMonitor: stop
08-26 19:45:25.400  6761  6987 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:25.400  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:25.400  6761  6987 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:25.400  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:25.400  6761  6987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 19:45:25.400  6761  6987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:45:25.400  6761  6987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:45:25.400  6761  6987 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f12d893 not in the list
08-26 19:45:25.410  6761  6987 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 19:45:25.410  6761  6987 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 19:45:25.410  6761  6987 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 19:45:25.410  6761  6987 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:45:25.410  6761  6987 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:25.410  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:25.410  6761  6987 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@37f10982 not in the list
08-26 19:45:25.410  6761  6987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:45:25.410  6761  6987 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f12d893 not in the list
08-26 19:45:25.410  6761  6987 D io.jxcore.node.ConnectivityMonitor: stop
08-26 19:45:25.410  6761  6987 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:25.410  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:25.410  6761  6987 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:25.410  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 19:45:25.410  6761  6987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 19:45:25.410  6761  6987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:45:25.410  6761  6987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:45:25.410  6761  6987 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f12d893 not in the list
08-26 19:45:25.410  6761  6987 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 19:45:25.410  6761  6987 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 19:45:25.410  6761  6987 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 19:45:25.410  6761  6987 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:45:25.410  6761  6987 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:25.410  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:25.410  6761  6987 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@37f10982 not in the list
08-26 19:45:25.410  6761  6987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:45:25.410  6761  6987 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f12d893 not in the list
08-26 19:45:25.410  6761  6987 D io.jxcore.node.ConnectivityMonitor: stop
08-26 19:45:25.410  6761  6987 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:25.410  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:25.410  6761  6987 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:25.410  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:25.410  6761  6987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 19:45:25.410  6761  6987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:45:25.410  6761  6987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:45:25.410  6761  6987 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f12d893 not in the list
08-26 19:45:25.410  6761  6987 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-26 19:45:25.410  6761  6987 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-26 19:45:25.410  6761  6987 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-26 19:45:25.410  6761  6987 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-26 19:45:25.410  6761  6987 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-26 19:45:25.410  6761  6987 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-26 19:45:25.410  6761  6987 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-26 19:45:25.410  6761  6987 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-26 19:45:25.410  6761  6987 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-26 19:45:25.410  6761  6987 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-26 19:45:25.410  6761  6987 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-26 19:45:25.410  6761  6987 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-26 19:45:25.410  6761  6987 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-26 19:45:25.410  6761  6987 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-26 19:45:25.410  6761  6987 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-26 19:45:25.410  6761  6987 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-26 19:45:25.410  6761  6987 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-26 19:45:25.410  6761  6987 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-26 19:45:25.410  6761  6987 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-26 19:45:25.410  6761  6987 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-26 19:45:25.410  6761  6987 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 19:45:25.410  6761  6987 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3943733d added. We now have 2 listener(s)
08-26 19:45:25.410  6761  6987 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 19:45:25.420  6761  6987 D BluetoothAdapter: enable()
08-26 19:45:25.420  6761  6987 D BluetoothAdapter: enable(): BT is already enabled..!
08-26 19:45:25.420  1020  1513 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-26 19:45:25.420  1020  1513 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-26 19:45:25.420  1020  1513 D SecContentProvider2: mCursor = null
08-26 19:45:25.420  1020  1513 D WifiService: setWifiEnabled: true pid=6761, uid=10170
08-26 19:45:25.420  1020  1513 W ActivityManager: Permission Denial: getCurrentUser() from pid=6761, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
08-26 19:45:25.430  1020  1513 W WifiService: Failed getting userId using ActivityManagerNative
08-26 19:45:25.430  1020  1513 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6761, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
08-26 19:45:25.430  1020  1513 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-26 19:45:25.430  1020  1513 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-26 19:45:25.430  1020  1513 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-26 19:45:25.430  1020  1513 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-26 19:45:25.430  1020  1513 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
08-26 19:45:25.430  1020  1513 D SettingsProvider: name = wifi_on
08-26 19:45:25.430  6761  6987 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 19:45:25.430  6761  6987 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d02d732 added. We now have 3 listener(s)
08-26 19:45:25.430  6761  6987 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 19:45:25.430  6761  6987 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 19:45:25.430  6761  6987 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a730c83 added. We now have 4 listener(s)
08-26 19:45:25.430  6761  6987 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 19:45:25.430  6761  6987 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 19:45:25.430  6761  6987 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@311e6e00 added. We now have 5 listener(s)
08-26 19:45:25.430  6761  6987 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 19:45:25.430  1020  1032 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-26 19:45:25.430  1020  1032 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-26 19:45:25.430  1020  1032 D SecContentProvider2: mCursor = null
08-26 19:45:25.440  1020  1032 D WifiService: setWifiEnabled: false pid=6761, uid=10170
08-26 19:45:25.440  1020  1032 D SettingsProvider: name = wifi_on
08-26 19:45:25.440  6761  6987 D BluetoothAdapter: disable()
08-26 19:45:25.440  1020  1131 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-26 19:45:25.440  1020  1257 D SettingsProvider: name = bluetooth_on
08-26 19:45:25.440  1381  1381 I wpa_supplicant: reset timer : RESET_TIMER 0
08-26 19:45:25.440  1381  1381 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
08-26 19:45:25.440  1381  1381 I wpa_supplicant: P2P: Current p2p state = IDLE
08-26 19:45:25.450  1381  1381 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-26 19:45:25.450  6761  6987 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
08-26 19:45:25.450  3176  3247 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
08-26 19:45:25.450  3176  3247 D BluetoothAdapterProperties: Setting state to 13
08-26 19:45:25.450  3176  3247 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-26 19:45:25.450  3176  3247 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-26 19:45:25.450  3176  3247 D BluetoothAdapterService: updateAdapterState state is 13
,08-26 19:45:25.450  1020  1471 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 19:45:25.450  1020  1471 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-26 19:45:25.460  1020  1471 W ActivityManager: userId = 0, bbcId = -10000,
,08-26 19:45:25.460  1020  1471 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:45:25.460  1020  1487 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
08-26 19:45:25.460  1020  1471 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-26 19:45:25.460  3176  3176 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
08-26 19:45:25.460  3176  3247 D BluetoothAdapterService: Autoconnection is available 
08-26 19:45:25.460  3176  3247 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
08-26 19:45:25.460  3176  3247 D BluetoothAdapterService: terminating service from this receiver
08-26 19:45:25.460  1020  1131 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-26 19:45:25.460  6761  6987 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 19:45:25.460  6761  6987 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 19:45:25.460  6761  6987 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:45:25.460  6761  6987 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 19:45:25.460  6761  6987 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 19:45:25.460  6761  6987 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 19:45:25.460  6761  6987 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 19:45:25.460  6761  6987 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 19:45:25.460  6761  6987 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 19:45:25.460  3176  3176 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@12d768cf, channel: 19, state: LISTENING
08-26 19:45:25.460  3176  3176 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@12d768cf, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@17e595d7, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@6c0e25cmSocket: android.net.LocalSocket@14409965 impl:android.net.LocalSocketImpl@175c463a fd:FileDescriptor[80]
08-26 19:45:25.460  3176  3176 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@14409965 impl:android.net.LocalSocketImpl@175c463a fd:FileDescriptor[80]
08-26 19:45:25.460  1020  1487 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:45:25.460  1020  1487 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:45:25.460  1020  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 19:45:25.460  3176  3247 D BluetoothAdapterProperties: onBluetoothDisable()
08-26 19:45:25.460  3176  3247 D BluetoothAdapterProperties: mDiscovering is false
,08-26 19:45:25.460  1020  1033 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
08-26 19:45:25.460  6761  6987 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 19:45:25.470  3176  3247 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-26 19:45:25.470  6761  6987 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 19:45:25.470  6761  6987 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 19:45:25.470  1020  1020 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-26 19:45:25.470  1020  1020 I InputMethodManagerService: [BT Setting State] State =13
,08-26 19:45:25.470  6761  6761 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 19:45:25.470  1177  1177 D BluetoothTile:  onBluetoothStateChange:
,08-26 19:45:25.470  6761  6761 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 19:45:25.480  1177  1177 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-26 19:45:25.480  1177  1177 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-26 19:45:25.480  1177  1177 D BluetoothTile:  getBluetoothState : 13
,08-26 19:45:25.480  1177  1784 D BluetoothTile:  handleUpdatestate:false name:null
08-26 19:45:25.480  1879  1879 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
08-26 19:45:25.480  1381  1381 I wpa_supplicant: nl80211: Received scan results (8 BSSes)
,08-26 19:45:25.480  1020  1131 E WifiNative-wlan0: do suspend true
08-26 19:45:25.480  1020  1130 D WifiP2pService: InactiveState{ what=147461 }
08-26 19:45:25.480  1020  1130 D WifiP2pService: P2pEnabledState{ what=147461 }
08-26 19:45:25.480  1020  1130 D WifiP2pService: DefaultState{ what=147461 }
,08-26 19:45:25.480  4713  4713 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-26 19:45:25.490  1177  1784 D BluetoothTile:  handleUpdatestate:false name:null
,08-26 19:45:25.490  1177  1784 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-26 19:45:25.500  3176  3250 D BluetoothUtils: getBtEnabledContainers(): btContainers = [],
08-26 19:45:25.500  1020  1491 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-26 19:45:25.500  3176  3250 D BluetoothAdapterProperties: Scan Mode:20
08-26 19:45:25.500  6761  6761 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 19:45:25.500  1020  4267 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
08-26 19:45:25.500  3176  3247 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-26 19:45:25.500  6761  6761 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 19:45:25.500  6761  6761 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:45:25.500  6761  6761 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 19:45:25.500  6761  6761 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 19:45:25.500  6761  6761 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 19:45:25.500  6761  6761 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 19:45:25.500  6761  6761 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 19:45:25.500  6761  6761 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 19:45:25.500  3176  3247 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
08-26 19:45:25.500  3176  3247 E bt-btif : cmd socket is not created
08-26 19:45:25.500  3176  5269 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-26 19:45:25.500  6761  7055 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2383347e, channel: -1, state: INIT
08-26 19:45:25.500  6761  7055 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@2383347e, channel: -1, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@304feddf, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@5fc6a2cmSocket: android.net.LocalSocket@3edaccf5 impl:android.net.LocalSocketImpl@281a1a8a fd:FileDescriptor[104]
08-26 19:45:25.500  6761  7055 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@3edaccf5 impl:android.net.LocalSocketImpl@281a1a8a fd:FileDescriptor[104]
08-26 19:45:25.500  6761  7055 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 1334)
08-26 19:45:25.500  3176  3247 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-26 19:45:25.500  3176  3251 W bt-btif : bta_dm_disable_bt BTA_DISABLE_DELAY set to 200 ms
08-26 19:45:25.500  6761  6761 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 19:45:25.510  6761  6761 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 19:45:25.510  1177  1177 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-26 19:45:25.510  3176  3176 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1a8bc2eb, channel: 5, state: LISTENING
08-26 19:45:25.510  3176  3176 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@1a8bc2eb, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1bb27ec4, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@fa7c848mSocket: android.net.LocalSocket@392666e1 impl:android.net.LocalSocketImpl@3bb88c06 fd:FileDescriptor[82]
,08-26 19:45:25.510  3176  3176 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@392666e1 impl:android.net.LocalSocketImpl@3bb88c06 fd:FileDescriptor[82]
08-26 19:45:25.510  3176  3176 I BtOppRfcommListener: stopping Accept Thread
08-26 19:45:25.510  3176  3176 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3ae1a2c7, channel: 12, state: LISTENING
08-26 19:45:25.510  3176  3176 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@3ae1a2c7, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1841052e, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@3e9520f4mSocket: android.net.LocalSocket@641901d impl:android.net.LocalSocketImpl@37416292 fd:FileDescriptor[87]
08-26 19:45:25.510  3176  3176 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@641901d impl:android.net.LocalSocketImpl@37416292 fd:FileDescriptor[87]
08-26 19:45:25.510  3176  5269 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-26 19:45:25.510  6761  6761 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 19:45:25.510  3176  3176 V BluetoothOppManager: cleanUp...
,08-26 19:45:25.510  4713  4713 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-26 19:45:25.510  1020  1082 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-26 19:45:25.510  1020  1082 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-26 19:45:25.520  6761  6761 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 19:45:25.520  3176  3251 W bt-sdp  : SDP - Rcvd conn cnf with error: 0x2  CID 0x40
08-26 19:45:25.520  3176  3251 E bt-btif : DISCOVERY_COMP_EVT slot id:4, failed to find channle,                                       status:1, scn:0
,08-26 19:45:25.520  1020  1082 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:45:25.520  3176  3251 W bt-btif : invalid rfc slot id: 4
08-26 19:45:25.520  1020  1082 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:45:25.520  1020  1082 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-26 19:45:25.520  3176  3251 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 19:45:25.520  3176  3251 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 19:45:25.520  3176  3251 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-26 19:45:25.520  3176  3251 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 19:45:25.520  3176  3251 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 19:45:25.520  3176  3251 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-26 19:45:25.520  6761  6761 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 19:45:25.520  4713  4713 D BluetoothPbap: Proxy object disconnected
08-26 19:45:25.520  4713  4713 D PbapServerProfile: Bluetooth service disconnected
,08-26 19:45:25.520  1695  1695 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-26 19:45:25.530  4713  4713 D DockEventReceiver: finishStartingService: stopping service
,08-26 19:45:25.530  4713  4713 D BluetoothNotiBroadcastReceiver: onReceive
,08-26 19:45:25.530  1177  1177 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-26 19:45:25.530  1177  1177 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,08-26 19:45:25.540  1020  1491 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,08-26 19:45:25.540  1020  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:45:25.540  1020  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:45:25.540  1020  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:45:25.540  1020  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 19:45:25.540  1020  1130 D WifiP2pService: InactiveState{ what=143375 }
,08-26 19:45:25.540  1020  1130 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-26 19:45:25.550  7063  7063 E Zygote  : MountEmulatedStorage()
,08-26 19:45:25.550  1020  1491 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=7063 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
08-26 19:45:25.550  7063  7063 E Zygote  : v2
08-26 19:45:25.550  7063  7063 I libpersona: KNOX_SDCARD checking this for 10055
08-26 19:45:25.550  7063  7063 I libpersona: KNOX_SDCARD not a persona
08-26 19:45:25.560  7063  7063 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 19:45:25.560   278  1006 D CommandListener: Clearing all IP addresses on wlan0,
08-26 19:45:25.560  7063  7063 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 19:45:25.560  7063  7063 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-26 19:45:25.560  1695  2650 V NativeCrypto: Read error: ssl=0xb764dc20: I/O error during system call, Connection timed out
08-26 19:45:25.570  1695  2650 V NativeCrypto: SSL shutdown failed: ssl=0xb764dc20: I/O error during system call, Broken pipe
08-26 19:45:25.570  1177  1177 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 19:45:25.570  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-26 19:45:25.570  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:45:25.570  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:45:25.570  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:45:25.570  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 19:45:25.570  1020  1133 E ConnectivityService: updateNetworkInfo()
08-26 19:45:25.570  1020  1133 E ConnectivityService: updateNetworkInfo()
08-26 19:45:25.570  1020  1133 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-26 19:45:25.570  1020  1133 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 2
08-26 19:45:25.570  1020  1032 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10011
,08-26 19:45:25.570  1020  1770 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:45:25.570  1020  1130 D WifiP2pService: InactiveState{ what=131204 }
08-26 19:45:25.570  1020  1770 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:45:25.570  1020  1130 D WifiP2pService: P2pEnabledState{ what=131204 }
08-26 19:45:25.570  1020  1770 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-26 19:45:25.570  1020  1770 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:45:25.570  1020  1770 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
08-26 19:45:25.570  1020  1770 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-26 19:45:25.570  1020  1770 I qtaguid : Tagging socket 374 with tag ffffffff00000000{4294967295,0} for uid 10011, pid: 1020, getuid(): 1000
08-26 19:45:25.580  1020  1770 I qtaguid : Untagging socket 374
08-26 19:45:25.580  1020  1770 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-26 19:45:25.580  1020  1020 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-26 19:45:25.580  1020  1130 D WifiP2pService: sending p2p connection changed broadcast: FAILED
,08-26 19:45:25.600  1020  1020 D WifiScanningService: SCAN_AVAILABLE : 1
08-26 19:45:25.600  1020  1154 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
,08-26 19:45:25.600  1020  1020 D RttService: SCAN_AVAILABLE : 1,
,08-26 19:45:25.600  1020  1155 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:45:25.600  7063  7063 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 19:45:25.600  1020  1131 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-26 19:45:25.600  1177  1177 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-26 19:45:25.600  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 19:45:25.600  7063  7063 D ActivityThread: Added TimaKeyStore provider
,08-26 19:45:25.600  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-26 19:45:25.610  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 19:45:25.610  1020  1052 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 19:45:25.610  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:45:25.610  1020  1052 D WifiDisplayAdapter: onP2pDisconnected
,08-26 19:45:25.610  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 19:45:25.610  1020  1130 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
08-26 19:45:25.610  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:45:25.610  1020  1130 D WifiP2pService: P2pDisablingState
08-26 19:45:25.610  1020  1130 D WifiP2pService: P2pDisablingState{ what=147458 }
08-26 19:45:25.610  1020  1130 D WifiP2pService: p2p socket connection lost
08-26 19:45:25.610  1020  1052 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-26 19:45:25.610  1020  1052 D IpRemoteDisplayController: WfdBridgeServer is already null
08-26 19:45:25.610  1020  1131 E WifiNative-wlan0: do suspend true
,08-26 19:45:25.610  1020  1020 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
08-26 19:45:25.610  1020  1130 D WifiP2pService: P2pDisabledState
,08-26 19:45:25.610  1020  1052 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
08-26 19:45:25.610  1020  1052 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-26 19:45:25.610  1020  1052 D WifiDisplayController: disconnect
08-26 19:45:25.610  1020  1052 D WifiDisplayController: updateConnection
08-26 19:45:25.610  1020  1052 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-26 19:45:25.610  1020  1052 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-26 19:45:25.620  1020  1052 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-26 19:45:25.620  1020  1052 D WifiDisplayAdapter: onP2pDisconnected
08-26 19:45:25.620  1020  1052 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-26 19:45:25.620  1020  1052 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-26 19:45:25.630  1177  1177 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-26 19:45:25.630  1020  1468 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-26 19:45:25.630  1177  1177 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-26 19:45:25.640  7063  7063 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,08-26 19:45:25.640   278  1002 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-26 19:45:25.640   278  1002 D Netd    : getNetworkForDns: using netid 0 for uid 1000
08-26 19:45:25.640  1020  1130 D WifiP2pService: P2pDisabledState{ what=143375 }
,08-26 19:45:25.640  1020  1130 D WifiP2pService: DefaultState{ what=143375 }
,08-26 19:45:25.640  1020  1133 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 19:45:25.640  1020  1133 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
08-26 19:45:25.640  1020  1133 V NetworkStats: updateIfacesLocked()
08-26 19:45:25.650  1020  1133 D NetworkStatsFactory: UpdateStatsForKnox updated
08-26 19:45:25.640  1020  1133 V NetworkStats: performPollLocked(flags=0x1)
,08-26 19:45:25.650  1020  1133 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-26 19:45:25.650  1020  1770 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
08-26 19:45:25.650   278  1006 D CommandListener: Clearing all IP addresses on wlan0
08-26 19:45:25.650  1020  1770 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
,08-26 19:45:25.650  1177  1177 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-26 19:45:25.650  1020  1020 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-26 19:45:25.650  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 19:45:25.650  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-26 19:45:25.650  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 19:45:25.650  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 19:45:25.650  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:45:25.660  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:45:25.660  1381  1381 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
,08-26 19:45:25.660  1020  1133 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 19:45:25.660  1020  1133 V NetworkStats: performPollLocked() took 13ms
,08-26 19:45:25.660  1020  1129 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 19:45:25.660  1020  1129 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 19:45:25.660  1020  1133 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 502]
,08-26 19:45:25.660  1020  1770 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:45:25.660  1020  1133 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 19:45:25.660  1177  1763 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
,08-26 19:45:25.660  1020  1133 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,fe80::aec:a9ff:fe50:7542/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
08-26 19:45:25.660  1020  1133 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
08-26 19:45:25.660  1472  1472 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-26 19:45:25.660  1472  1472 D TelephonyNetworkFactory: Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 19:45:25.660  1020  1130 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-26 19:45:25.660  1020  1133 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-26 19:45:25.660  1020  1051 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
08-26 19:45:25.660  1020  1131 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-26 19:45:25.660  1020  1131 D SecContentProvider2: mCursor = null
,08-26 19:45:25.670  1177  1177 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-26 19:45:25.670  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 19:45:25.670  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-26 19:45:25.670  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:45:25.670  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:45:25.670  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:45:25.670  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 19:45:25.680  4713  4713 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-26 19:45:25.680  1020  1131 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,08-26 19:45:25.680  1177  1177 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-26 19:45:25.680  1177  1177 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-26 19:45:25.680  1177  1784 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-26 19:45:25.680  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 19:45:25.680  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-26 19:45:25.680  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:45:25.680  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 19:45:25.680  1020  1133 D ConnectivityService: nai.networkMonitor.doQuit()
08-26 19:45:25.680  1020  1133 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
08-26 19:45:25.680  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:45:25.680  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:45:25.680  1177  1177 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-26 19:45:25.680  1177  1177 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
08-26 19:45:25.680  1020  1051 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
,08-26 19:45:25.680  7063  7063 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
08-26 19:45:25.680  1020  1133 D ConnectivityService: NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-26 19:45:25.680  1020  1133 E ConnectivityService: updateNetworkInfo()
08-26 19:45:25.680  1020  1133 E ConnectivityService: updateNetworkInfo()
08-26 19:45:25.680  1020  1020 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
08-26 19:45:25.680  1020  1134 D Tethering: MasterInitialState.processMessage what=3
08-26 19:45:25.680  7063  7063 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
08-26 19:45:25.680  7063  7063 D UserAnalysis: Create SecureDbHelper
08-26 19:45:25.680  1177  1177 D HotspotTile: onReceive : 0, 0
,08-26 19:45:25.680  1020  1128 V NetworkStats: updateIfacesLocked()
,08-26 19:45:25.690  1020  1128 V NetworkStats: performPollLocked(flags=0x1)
,08-26 19:45:25.690  1020  1128 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 19:45:25.690  1020  1128 D NetworkStatsFactory: UpdateStatsForKnox updated
,08-26 19:45:25.690  1020  1128 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-26 19:45:25.690  6761  6761 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 19:45:25.690  6761  6761 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 19:45:25.690  6761  6761 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:45:25.690  6761  6761 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 19:45:25.690  6761  6761 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 19:45:25.690  6761  6761 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 19:45:25.690  6761  6761 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 19:45:25.690  6761  6761 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 19:45:25.690  6761  6761 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 19:45:25.690  1020  1128 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 19:45:25.690  1020  1128 V NetworkStats: performPollLocked() took 4ms
,08-26 19:45:25.690  1177  1177 D StatusBar.NetworkController: EthernetConnected: false,
08-26 19:45:25.690  1177  1177 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-26 19:45:25.690  1177  1177 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-26 19:45:25.690  6761  6761 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 19:45:25.690  1177  1177 D StatusBar.NetworkController: updateDataNetType()
08-26 19:45:25.690  6761  6761 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 19:45:25.690  1020  1129 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 19:45:25.700  6761  6761 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 19:45:25.700  6761  6761 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 19:45:25.700  6761  6761 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:45:25.700  6761  6761 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 19:45:25.700  6761  6761 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 19:45:25.700  6761  6761 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 19:45:25.700  6761  6761 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 19:45:25.700  6761  6761 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 19:45:25.700  6761  6761 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 19:45:25.700  6761  6761 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 19:45:25.700  6761  6761 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 19:45:25.700  7063  7063 D IntelligenceServiceApplication: onCreate()
08-26 19:45:25.700  1177  1177 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-26 19:45:25.700  1177  1177 E StatusBar.NetworkController: updateLTEICONDataNetType:0
08-26 19:45:25.700  1020  1129 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 19:45:25.700  1020  1129 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 19:45:25.700  1020  1129 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
08-26 19:45:25.700  1020  1129 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 19:45:25.700  1177  1177 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
08-26 19:45:25.700  1177  1177 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 20 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x4 gsm|lte
08-26 19:45:25.700  1177  1177 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=4
08-26 19:45:25.700  1177  1177 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_4 mContentDescriptionPhoneSignal = Full phone signal
,08-26 19:45:25.710  1020  1129 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 19:45:25.710  1020  1129 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 19:45:25.710  1020  1468 I ActivityManager: Killing 5976:com.samsung.android.sm/1000 (adj 15): empty #21
,08-26 19:45:25.710  1177  1177 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-26 19:45:25.710  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 19:45:25.710  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-26 19:45:25.710  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:45:25.710  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:45:25.710  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:45:25.710  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:45:25.710  7063  7063 D IntelligenceServiceApplication: no applications having user consent for prediction
,08-26 19:45:25.710  3176  3247 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-26 19:45:25.710  3176  3247 D BtConfig.SecureMode: isSecureModeOn:false
08-26 19:45:25.710  3176  3247 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
08-26 19:45:25.710  3176  3247 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.gatt.GattService
08-26 19:45:25.710  3176  3247 W BluetoothAdapterService: Skipping to stop Quiet mode profile com.android.bluetooth.gatt.GattService
08-26 19:45:25.710  3176  3247 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
08-26 19:45:25.710  3176  3247 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,08-26 19:45:25.710  3176  3247 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService,
,08-26 19:45:25.710  1020  1471 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
08-26 19:45:25.720  1020  4358 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 19:45:25.720  1020  4358 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-26 19:45:25.720  1020  4358 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:45:25.720  7063  7063 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,08-26 19:45:25.720  1020  4358 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:45:25.720  1020  4358 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 19:45:25.720  3176  3247 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
08-26 19:45:25.720  1020  1468 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,08-26 19:45:25.720  3176  3247 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,08-26 19:45:25.720  3176  3176 D HeadsetService: Received stop request...Stopping profile...
08-26 19:45:25.720  1020  1468 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:45:25.720  1020  1468 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:45:25.720  1020  1468 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:45:25.720  1020  1468 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 19:45:25.720  3176  3247 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-26 19:45:25.720  7063  7063 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,08-26 19:45:25.730  7085  7085 E Zygote  : MountEmulatedStorage()
08-26 19:45:25.730  7085  7085 E Zygote  : v2
08-26 19:45:25.730  7085  7085 I libpersona: KNOX_SDCARD checking this for 10105
08-26 19:45:25.730  7085  7085 I libpersona: KNOX_SDCARD not a persona
08-26 19:45:25.730  7085  7085 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-26 19:45:25.740  1381  1381 I wpa_supplicant: Blacklist: Clear (all) 
,08-26 19:45:25.740  1020  1468 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=7085 uid=10105 gids={50105, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,08-26 19:45:25.740  7085  7085 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 19:45:25.740  3176  3176 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@247e950f
08-26 19:45:25.740  1020  1257 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 19:45:25.740  7085  7085 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
08-26 19:45:25.740  1020  1257 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
08-26 19:45:25.740  1020  1257 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:45:25.740  1020  1257 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:45:25.740  1020  1257 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 19:45:25.740  3176  3247 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
08-26 19:45:25.740  3176  3247 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-26 19:45:25.740  1020  1020 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-26 19:45:25.740  3176  3247 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-26 19:45:25.740  4713  4713 D HeadsetProfile: Bluetooth service disconnected
,08-26 19:45:25.750  1020  4359 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 19:45:25.750  1020  4359 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-26 19:45:25.750  1020  4359 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:45:25.750  1020  4359 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:45:25.750  1020  4359 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-26 19:45:25.750  3176  3247 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
08-26 19:45:25.750  3176  3247 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,08-26 19:45:25.750  3176  3247 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
08-26 19:45:25.750  1020  1033 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 19:45:25.750  1020  1033 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-26 19:45:25.750  1020  1033 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:45:25.750  1020  1033 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:45:25.750  1020  1033 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 19:45:25.750  3176  3247 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
08-26 19:45:25.750  3176  3247 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,08-26 19:45:25.750  3176  3247 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-26 19:45:25.750  1020  1468 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 19:45:25.750  1020  1468 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-26 19:45:25.750  1020  1468 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:45:25.750  1020  1468 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:45:25.750  1020  1468 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-26 19:45:25.760  3176  3247 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
08-26 19:45:25.760  3176  3247 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-26 19:45:25.760  3176  3247 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-26 19:45:25.760  1020  1508 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-26 19:45:25.760  1020  1508 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:45:25.760  1020  1508 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
08-26 19:45:25.760  1020  1508 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:45:25.760  1020  1508 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-26 19:45:25.760  3176  3247 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
08-26 19:45:25.760  3176  3247 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,08-26 19:45:25.760  3176  3247 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-26 19:45:25.760  1020  1258 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth,
08-26 19:45:25.760  1020  1258 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-26 19:45:25.770  1020  1258 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:45:25.770  1020  1258 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:45:25.770  1020  1258 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-26 19:45:25.770  3176  3247 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-26 19:45:25.770  3176  3247 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-26 19:45:25.770  3176  3247 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-26 19:45:25.770  7085  7085 D TimaKeyStoreProvider: TimaSignature is unavailable,
08-26 19:45:25.770  3176  3247 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-26 19:45:25.770  3176  3247 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-26 19:45:25.770  3176  3247 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-26 19:45:25.770  3176  3247 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService,
08-26 19:45:25.770  3176  3247 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-26 19:45:25.770  7085  7085 D ActivityThread: Added TimaKeyStore provider
08-26 19:45:25.770  3176  3247 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-26 19:45:25.770  3176  3247 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
08-26 19:45:25.770  3176  3247 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-26 19:45:25.770  3176  3247 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-26 19:45:25.770  3176  3247 D BluetoothAdapterState: Stopping profile services that were post enabled
,08-26 19:45:25.770  3176  3176 E BluetoothAdapterService(612275471): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
08-26 19:45:25.770  3176  3176 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-26 19:45:25.770  3176  3176 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
08-26 19:45:25.770  3176  3176 D A2dpService: Received stop request...Stopping profile...
08-26 19:45:25.770  3176  3316 D A2dpStateMachine: Exit Disconnected: -1
,08-26 19:45:25.780  3176  3176 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@247e950f
,08-26 19:45:25.780  1020  1020 D BluetoothA2dp: Proxy object disconnected
,08-26 19:45:25.780  1020  1020 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-26 19:45:25.780  4713  4713 D BluetoothA2dp: Proxy object disconnected
08-26 19:45:25.780  4713  4713 D A2dpProfile: Bluetooth service disconnected
,08-26 19:45:25.790  3176  3176 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-26 19:45:25.790  3176  3176 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-26 19:45:25.790  3176  3176 D HidService: Received stop request...Stopping profile...
08-26 19:45:25.790  3176  3176 D HidService: Stopping Bluetooth HidService
,08-26 19:45:25.790  3176  3176 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-26 19:45:25.790  3176  3176 W bt-btif : cleanup: HH disabling or disabled already, status = 0
08-26 19:45:25.790  3176  3176 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-26 19:45:25.790  3176  3176 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@247e950f
,08-26 19:45:25.790  4713  4713 D BluetoothInputDevice: Proxy object disconnected
08-26 19:45:25.790  4713  4713 D HidProfile: Bluetooth service disconnected
,08-26 19:45:25.790  3176  3176 D HealthService: Received stop request...Stopping profile...
08-26 19:45:25.790  3176  3176 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@247e950f
,08-26 19:45:25.790  3176  3176 D PanService: Received stop request...Stopping profile...
,08-26 19:45:25.790  3176  3176 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@247e950f
08-26 19:45:25.800  1020  1020 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-26 19:45:25.800  3176  3176 D BluetoothMapService: Received stop request...Stopping profile...
,08-26 19:45:25.800  4713  4713 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-26 19:45:25.800  3176  3176 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@247e950f
,08-26 19:45:25.800  3176  3176 D SapService: Received stop request...Stopping profile...
,08-26 19:45:25.800  3176  3176 D SapService: Stopping Bluetooth SapService
08-26 19:45:25.800  3176  3176 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@247e950f
,08-26 19:45:25.800  3176  3176 E BluetoothAdapterService(612275471): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
,08-26 19:45:25.800  3176  3176 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-26 19:45:25.810  3176  3176 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService,
08-26 19:45:25.810  3176  3176 D BluetoothA2dp: Proxy object disconnected
08-26 19:45:25.810  3176  3176 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
08-26 19:45:25.810  4713  4713 D PanProfile: Bluetooth service disconnected
,08-26 19:45:25.810  3176  3317 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
,08-26 19:45:25.810  3176  3176 I GKI_LINUX: GKI_exit_task 2 done
08-26 19:45:25.810  3176  3176 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-26 19:45:25.810  3176  3176 E BluetoothAdapterService(612275471): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
08-26 19:45:25.810  3176  3176 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-26 19:45:25.810  3176  3176 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-26 19:45:25.810  3176  3176 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
,08-26 19:45:25.810  3176  3176 E BluetoothAdapterService(612275471): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
08-26 19:45:25.810  3176  3176 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-26 19:45:25.810  3176  3176 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-26 19:45:25.810  3176  3176 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-26 19:45:25.810  3176  3176 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-26 19:45:25.810  3176  3176 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-26 19:45:25.810  4713  4713 D BluetoothMap: Proxy object disconnected
08-26 19:45:25.810  4713  4713 D MapProfile: Bluetooth service disconnected
08-26 19:45:25.810  4713  4713 D Bluetoothsap: BluetoothSAP Proxy object disconnected
08-26 19:45:25.810  3176  3176 E BluetoothAdapterService(612275471): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
08-26 19:45:25.810  4713  4713 D SapProfile: Bluetooth service disconnected
08-26 19:45:25.810  3176  3176 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-26 19:45:25.810  3176  3176 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-26 19:45:25.810  3176  3176 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-26 19:45:25.810  3176  3176 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-26 19:45:25.810  3176  3176 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-26 19:45:25.810  3176  3176 E BluetoothAdapterService(612275471): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
08-26 19:45:25.810  3176  3176 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-26 19:45:25.810  3176  3176 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-26 19:45:25.810  3176  3176 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
08-26 19:45:25.810  3176  3176 E BluetoothAdapterService(612275471): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
08-26 19:45:25.810  3176  3176 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-26 19:45:25.810  3176  3176 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
08-26 19:45:25.810  3176  3176 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,08-26 19:45:25.810  3176  3247 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
08-26 19:45:25.810  3176  3247 D BluetoothAdapterProperties: Setting state to 10
08-26 19:45:25.810  3176  3247 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-26 19:45:25.810  3176  3247 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-26 19:45:25.810  3176  3247 D BluetoothAdapterService: updateAdapterState state is 10
,08-26 19:45:25.820  3176  3247 D BluetoothAdapterService: Autoconnection is available 
08-26 19:45:25.820  3176  3247 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
08-26 19:45:25.820  3176  3247 I BluetoothAdapterState: Entering OffState
,08-26 19:45:25.820  4713  7060 D BluetoothMap: onBluetoothStateChange: up=false,
,08-26 19:45:25.820  4713  4724 D Bluetoothsap: onBluetoothStateChange: up=false
,08-26 19:45:25.820  4713  4724 D Bluetoothsap: Unbinding service...
,08-26 19:45:25.830  1455  1793 D BluetoothAdapter: onBluetoothStateChange: up=false
08-26 19:45:25.830  1455  1793 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-26 19:45:25.830  1806  2237 D BluetoothAdapter: onBluetoothStateChange: up=false
08-26 19:45:25.830  1806  2237 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-26 19:45:25.830  1020  1051 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-26 19:45:25.830  1177  1838 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-26 19:45:25.830  1177  1838 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-26 19:45:25.830  4713  4733 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-26 19:45:25.830  4713  7060 D BluetoothPbap: onBluetoothStateChange: up=false
,08-26 19:45:25.830  1445  1454 D BluetoothAdapter: onBluetoothStateChange: up=false
08-26 19:45:25.830  1445  1454 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-26 19:45:25.840  1381  1381 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-26 19:45:25.840  1020  1049 D Tethering: interfaceLinkStateChanged p2p0, false
08-26 19:45:25.840  1020  1049 D Tethering: interfaceStatusChanged p2p0, false
,08-26 19:45:25.840  1020  1049 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-26 19:45:25.840  1472  1472 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-26 19:45:25.840  3176  3185 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-26 19:45:25.840  1020  1051 D BluetoothAdapter: onBluetoothStateChange: up=false
08-26 19:45:25.840  1020  1051 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-26 19:45:25.850  1472  1472 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-26 19:45:25.850  1472  1472 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-26 19:45:25.850  3176  3310 D BluetoothAdapter: onBluetoothStateChange: up=false
08-26 19:45:25.850  3176  3310 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-26 19:45:25.850  6761  6776 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-26 19:45:25.850  6761  6776 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-26 19:45:25.850  6761  6776 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
08-26 19:45:25.850  6761  6776 D BluetoothLeAdvertiser: Exit stop advertising
08-26 19:45:25.850  6761  6776 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
08-26 19:45:25.850  6761  6776 D BluetoothLeScanner: Exiting stopAllScan
08-26 19:45:25.850  1472  1788 D BluetoothAdapter: onBluetoothStateChange: up=false
08-26 19:45:25.850  1472  1788 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-26 19:45:25.850  4713  7060 D BluetoothAdapter: onBluetoothStateChange: up=false,
08-26 19:45:25.850  4713  7060 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-26 19:45:25.850  4713  4724 D BluetoothA2dp: onBluetoothStateChange: up=false
08-26 19:45:25.850  1472  1472 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-26 19:45:25.850  1695  2225 D BluetoothAdapter: onBluetoothStateChange: up=false
08-26 19:45:25.850  1695  2225 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-26 19:45:25.850  1472  1472 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-26 19:45:25.850  1020  1020 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-26 19:45:25.850  1020  1020 I InputMethodManagerService: [BT Setting State] State =10
08-26 19:45:25.850  1020  1020 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-26 19:45:25.860  1472  1472 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-26 19:45:25.860  1177  1177 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-26 19:45:25.860  1177  1177 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-26 19:45:25.860  1177  1177 D BluetoothTile:  getBluetoothState : 10
,08-26 19:45:25.860  1879  1879 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-26 19:45:25.860  1472  1472 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-26 19:45:25.860  1381  1381 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
,08-26 19:45:25.860  1381  1381 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
08-26 19:45:25.860  1381  1381 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
08-26 19:45:25.860  1020  1049 D Tethering: interfaceLinkStateChanged wlan0, false
08-26 19:45:25.860  1020  1049 D Tethering: interfaceStatusChanged wlan0, false
08-26 19:45:25.860  1381  1381 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
08-26 19:45:25.860  1381  1381 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,08-26 19:45:25.870  1020  1049 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-26 19:45:25.870  1020  1134 D Tethering: InitialState.processMessage what=4
,08-26 19:45:25.870  1020  1049 D Tethering: interfaceLinkStateChanged wlan0, false
08-26 19:45:25.870  1020  1049 D Tethering: interfaceStatusChanged wlan0, false
,08-26 19:45:25.870  4713  4713 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-26 19:45:25.870  1472  1472 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-26 19:45:25.870  1472  1472 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-26 19:45:25.870  1020  1134 E Tethering: No numeric data
,08-26 19:45:25.870  1020  1049 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-26 19:45:25.870  1020  1134 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-26 19:45:25.870  1020  1134 D Tethering: clearTetheredNotification()
,08-26 19:45:25.870  1020  1049 D Tethering: interfaceLinkStateChanged wlan0, false
08-26 19:45:25.880  1020  1487 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-26 19:45:25.880  1020  1049 D Tethering: interfaceStatusChanged wlan0, false
08-26 19:45:25.880  1020  1049 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-26 19:45:25.880  1472  1472 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-26 19:45:25.880  1472  1472 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-26 19:45:25.880  6761  6761 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 19:45:25.880  6761  6761 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 19:45:25.880  6761  6761 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:45:25.880  6761  6761 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 19:45:25.880  6761  6761 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 19:45:25.880  6761  6761 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 19:45:25.880  6761  6761 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 19:45:25.880  6761  6761 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 19:45:25.880  6761  6761 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 19:45:25.880  1020  1513 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-26 19:45:25.880  1177  1177 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-26 19:45:25.880  1020  1128 V NetworkStats: performPollLocked(flags=0x1)
08-26 19:45:25.880  1020  1128 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 19:45:25.880  1177  1177 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-26 19:45:25.880  1020  1128 D NetworkStatsFactory: UpdateStatsForKnox updated
08-26 19:45:25.880  1020  1128 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-26 19:45:25.880  6761  6761 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 19:45:25.880  1020  1128 V NetworkStats: performPollLocked() took 5ms
08-26 19:45:25.880  1020  1128 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 19:45:25.880  1472  1472 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-26 19:45:25.880  1472  1472 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-26 19:45:25.890  1472  1472 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-26 19:45:25.890  1472  1472 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-26 19:45:25.890  1020  1129 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 19:45:25.890  1020  1129 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 19:45:25.890  1472  1472 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-26 19:45:25.890  1472  1472 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-26 19:45:25.890  1472  1472 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-26 19:45:25.890  1472  1472 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-26 19:45:25.890  1472  1472 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-26 19:45:25.890  1472  1472 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-26 19:45:25.900  1472  1472 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-26 19:45:25.900  1472  1472 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-26 19:45:25.900  1177  1177 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-26 19:45:25.900  1472  1472 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-26 19:45:25.900  1177  1177 D HotspotTile: updateTetherState():false, false
08-26 19:45:25.900  1472  1472 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-26 19:45:25.900  6761  6761 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-26 19:45:25.900  1472  1472 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-26 19:45:25.900  1472  1472 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-26 19:45:25.900  1472  1472 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-26 19:45:25.900  1472  1472 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-26 19:45:25.910  1472  1472 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-26 19:45:25.920   257   536 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-26 19:45:25.920   257   536 W Vold    : Returning OperationFailed - no handler for errno 0
,08-26 19:45:25.920  7085  7122 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-26 19:45:25.930   257   536 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-26 19:45:25.930   257   536 W Vold    : Returning OperationFailed - no handler for errno 0
,08-26 19:45:25.930  7085  7122 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-26 19:45:26.070  1381  1381 I wpa_supplicant: Blacklist: Clear (all) 
,08-26 19:45:26.070  7085  7085 D StrictMode: StrictMode policy violation; ~duration=136 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-26 19:45:26.070  7085  7085 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at java.io.File.exists(File.java:363)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-26 19:45:26.070  7085  7085 D StrictMode: StrictMode policy violation; ~duration=135 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-26 19:45:26.070  7085  7085 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at com.google.android.app,s.gmm.map.m.q.a(PG:8690)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-26 19:45:26.070  7085  7085 D StrictMode: StrictMode policy violation; ~duration=135 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-26 19:45:26.070  7085  7085 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at ,android.os.Handler.dispatchMessage(Handler.java:102)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-26 19:45:26.070  7085  7085 D StrictMode: StrictMode policy violation; ~duration=133 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-26 19:45:26.070  7085  7085 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at com.google.q.k.a(PG:2107)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:23)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at com.google.q.e.b(PG:170)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-26 19:45:26.070  7085  7085 D StrictMode: StrictMode policy violation; ~duration=131 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-26 19:45:26.070  7085  7085 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at com.google.q.k.c(PG:18147)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at com.google.q.k.d(PG:583)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:40)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at com.google.q.e.b(PG:170)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-26 19:45:26.070  7085  7085 D StrictMode: StrictMode policy violation; ~duration=111 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-26 19:45:26.070  7085  7085 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at java.io.File.exists(File.java:363)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8698)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-26 19:45:26.070  7085  7085 D StrictMode: StrictMode policy violation; ~duration=110 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-26 19:45:26.070  7085  7085 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at java.io.File.exists(File.java:363)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8700)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-26 19:45:26.070  7085  7085 D StrictMode: StrictMode policy violation; ~duration=110 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-26 19:45:26.070  7085  7085 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at java.io.File.lastModified(File.java:571)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 19:45:26.070  7085  7085 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-26 19:45:26.080  1020  1258 I ActivityManager: Killing 6608:com.google.android.partnersetup/u0a14 (adj 15): empty #21
08-26 19:45:26.080  1020  4357 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-26 19:45:26.080  1020  4357 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-26 19:45:26.080  1020  4357 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:45:26.080  1020  4357 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:45:26.080  1020  4357 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-26 19:45:26.090  1627  1627 I Hs20UtilService: Starting #8
08-26 19:45:26.090  4713  4713 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-26 19:45:26.090  1627  1661 I Hs20UtilService: Message received 5007
08-26 19:45:26.090  4713  4713 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-26 19:45:26.100  4713  4713 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-26 19:45:26.100  4713  4713 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-26 19:45:26.100  4713  4713 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-26 19:45:26.100  4713  4713 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-26 19:45:26.100  4713  4794 V NearbySettings: MountReceiver.mPrefHandler - 7002
08-26 19:45:26.110  1020  4358 W ActivityManager: userId = 0, bbcId = -10000
,08-26 19:45:26.110  1020  4358 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 19:45:26.110  1020  4358 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
08-26 19:45:26.110  1020  4358 D ActivityManager: startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
08-26 19:45:26.110  1020  4358 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:45:26.110  1020  4358 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:45:26.110  1020  4358 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:45:26.110  1020  4358 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:45:26.120  7132  7132 E Zygote  : MountEmulatedStorage()
08-26 19:45:26.120  7132  7132 I libpersona: KNOX_SDCARD checking this for 10102
08-26 19:45:26.120  7132  7132 E Zygote  : v2
08-26 19:45:26.120  7132  7132 I libpersona: KNOX_SDCARD not a persona
08-26 19:45:26.120  7132  7132 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-26 19:45:26.130  1020  1049 D Tethering: interfaceLinkStateChanged wlan0, false
08-26 19:45:26.130  1020  1049 D Tethering: interfaceStatusChanged wlan0, false
08-26 19:45:26.130  1020  1049 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-26 19:45:26.130  7132  7132 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 19:45:26.130  7132  7132 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
08-26 19:45:26.130  1381  1381 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-26 19:45:26.140  7085  7131 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
08-26 19:45:26.140  1020  4358 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7132 uid=10102 gids={50102, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,08-26 19:45:26.150  7132  7132 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 19:45:26.160  7132  7132 D ActivityThread: Added TimaKeyStore provider
,08-26 19:45:26.170  7132  7132 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-26 19:45:26.180  1020  1487 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 19:45:26.180  1020  1487 W ActivityManager: userId = 0, bbcId = -10000
,08-26 19:45:26.180  1020  1487 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 19:45:26.180  1020  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,08-26 19:45:26.180  1020  1133 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-26 19:45:26.180  1020  1020 I ApplicationPolicy: updateDataUsageMap
,08-26 19:45:26.200  6761  6761 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 19:45:26.200  6761  6761 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 19:45:26.200  1020  1046 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-26 19:45:26.240  1020  1131 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
,08-26 19:45:26.240  1020  1131 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-26 19:45:26.250  1177  1177 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-26 19:45:26.250  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 19:45:26.250  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-26 19:45:26.250  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:45:26.250  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:45:26.250  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:45:26.250  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:45:26.250  1177  1177 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-26 19:45:26.250  1177  1177 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
,08-26 19:45:26.250  1177  1177 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-26 19:45:26.250  1177  1784 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-26 19:45:26.250  1177  1177 D HotspotTile: onReceive : 1, 0
,08-26 19:45:26.250  4713  4713 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-26 19:45:26.250  1806  2213 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-26 19:45:26.260  6761  6761 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 19:45:26.260  6761  6761 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 19:45:26.380  7132  7154 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
,08-26 19:45:26.380  7132  7154 I Babel_SMS: MmsConfig.loadMmsSettings
,08-26 19:45:26.380  7132  7154 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
,08-26 19:45:26.380  7132  7154 I Babel_SMS: MmsConfig.loadFromDatabase
,08-26 19:45:26.400  7132  7154 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
,08-26 19:45:26.400  7132  7154 I Babel_SMS: MmsConfig.loadFromResources
,08-26 19:45:26.420  7132  7154 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,08-26 19:45:26.420  7132  7154 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
,08-26 19:45:26.420  1020  4358 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
,08-26 19:45:26.420  1020  4358 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,08-26 19:45:26.420  1020  4358 W ActivityManager: userId = 0, bbcId = -10000
,08-26 19:45:26.420  1020  4358 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 19:45:26.420  1020  4358 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-26 19:45:26.440  7132  7132 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-26 19:45:26.450  7132  7132 I Babel_Crash: startup - clean
,08-26 19:45:26.480  4713  4713 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-26 19:45:26.480  4713  4713 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-26 19:45:26.480  4713  4713 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-26 19:45:26.490  4713  4713 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-26 19:45:26.490  4713  4713 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-26 19:45:26.490  4713  4713 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-26 19:45:26.490  4713  4794 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-26 19:45:26.490  1020  4357 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
,08-26 19:45:26.490  1020  4357 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 19:45:26.490  1020  4357 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:45:26.490  1020  4357 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:45:26.490  1020  4357 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 19:45:26.500  7157  7157 E Zygote  : MountEmulatedStorage()
08-26 19:45:26.500  7157  7157 E Zygote  : v2
08-26 19:45:26.500  7157  7157 I libpersona: KNOX_SDCARD checking this for 10064
08-26 19:45:26.500  7157  7157 I libpersona: KNOX_SDCARD not a persona
,08-26 19:45:26.500  7157  7157 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 19:45:26.510  1020  4357 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=7157 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
08-26 19:45:26.510  7157  7157 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 19:45:26.510  7157  7157 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 19:45:26.510  7132  7132 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
08-26 19:45:26.510  7132  7132 W AudioCapabilities: Unsupported mime audio/evrc
,08-26 19:45:26.520  7132  7132 W AudioCapabilities: Unsupported mime audio/qcelp
,08-26 19:45:26.520  7132  7132 W AudioCapabilities: Unsupported mime audio/mpeg-L1
,08-26 19:45:26.520  7132  7132 W AudioCapabilities: Unsupported mime audio/mpeg-L2,
,08-26 19:45:26.530  7132  7132 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,08-26 19:45:26.530  7132  7132 W AudioCapabilities: Unsupported mime audio/x-ima
,08-26 19:45:26.530  7157  7157 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 19:45:26.530  7132  7132 W AudioCapabilities: Unsupported mime audio/qcelp
,08-26 19:45:26.530  7157  7157 D ActivityThread: Added TimaKeyStore provider
,08-26 19:45:26.530  7132  7132 W AudioCapabilities: Unsupported mime audio/evrc
,08-26 19:45:26.540  7132  7132 W VideoCapabilities: Unsupported mime video/wvc1
,08-26 19:45:26.540  7132  7132 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-26 19:45:26.560  7157  7157 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,08-26 19:45:26.570  7157  7157 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-26 19:45:26.580  7157  7157 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected,
,08-26 19:45:26.590  7132  7132 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
,08-26 19:45:26.590  7132  7132 W VideoCapabilities: Unsupported mime video/wvc1
08-26 19:45:26.590  7132  7132 W VideoCapabilities: Unsupported mime video/x-ms-wmv
08-26 19:45:26.590  7132  7132 W VideoCapabilities: Unsupported mime video/x-ms-wmv7
,08-26 19:45:26.590  7132  7132 W VideoCapabilities: Unsupported mime video/x-ms-wmv8
,08-26 19:45:26.600  7132  7132 W VideoCapabilities: Unsupported mime video/mp43
,08-26 19:45:26.600  7132  7132 W VideoCapabilities: Unsupported mime video/sorenson
,08-26 19:45:26.610  7157  7157 D FileShare-Client: Outbound.stopDelayTimer - 
,08-26 19:45:26.610  1020  4357 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,08-26 19:45:26.610  7132  7132 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,08-26 19:45:26.610  1020  4357 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 19:45:26.610  1020  4357 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:45:26.610  1020  4357 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:45:26.610  1020  4357 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 19:45:26.630  7172  7172 E Zygote  : MountEmulatedStorage()
08-26 19:45:26.630  7172  7172 E Zygote  : v2
08-26 19:45:26.630  7172  7172 I libpersona: KNOX_SDCARD checking this for 10065
08-26 19:45:26.630  7172  7172 I libpersona: KNOX_SDCARD not a persona
08-26 19:45:26.630  7172  7172 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 19:45:26.630  7172  7172 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-26 19:45:26.630  1020  4357 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=7172 uid=10065 gids={50065, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-26 19:45:26.630  1020  4357 I ActivityManager: Killing 6621:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #21
08-26 19:45:26.630  7172  7172 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 19:45:26.650  7132  7132 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-26 19:45:26.660  7172  7172 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 19:45:26.660  7172  7172 D ActivityThread: Added TimaKeyStore provider
,08-26 19:45:26.670   323   323 I art     : Explicit concurrent mark sweep GC freed 8690(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 972us total 34.181ms
,08-26 19:45:26.680   323   323 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 595us total 16.638ms
,08-26 19:45:26.680  7132  7132 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-26 19:45:26.690  7132  7132 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-26 19:45:26.690  7132  7132 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-26 19:45:26.690  7172  7172 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-26 19:45:26.690  7132  7132 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-26 19:45:26.700   323   323 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 572us total 16.726ms
08-26 19:45:26.700  1020  1471 I ActivityManager: Killing 6656:com.sec.pcw.device/1000 (adj 15): empty #21
,08-26 19:45:26.700  1020  1513 I ActivityManager: Killing 6676:com.google.android.apps.docs/u0a87 (adj 15): empty #21
,08-26 19:45:26.700  1020  4267 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-26 19:45:26.700  7132  7132 I vclib   : onServiceConnected
08-26 19:45:26.700  1020  4267 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-26 19:45:26.710  1020  4267 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:45:26.710  1020  4267 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:45:26.710  1020  4267 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-26 19:45:26.710  1627  1627 I Hs20UtilService: Starting #9
,08-26 19:45:26.710  1627  1661 I Hs20UtilService: Message received 5007
,08-26 19:45:26.710  4713  4713 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-26 19:45:26.710  4713  4713 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-26 19:45:26.710  4713  4713 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-26 19:45:26.710  4713  4713 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-26 19:45:26.720  4713  4713 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-26 19:45:26.720  4713  4713 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-26 19:45:26.720  4713  4794 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-26 19:45:26.720  1020  1033 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-26 19:45:26.720  1020  1033 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-26 19:45:26.720  1020  1033 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:45:26.720  1020  1033 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:45:26.720  1020  1033 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-26 19:45:26.720  1627  1627 I Hs20UtilService: Starting #10
08-26 19:45:26.720  1020  1513 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.securitylogagent, hostingType: broadcast
08-26 19:45:26.720  1627  1661 I Hs20UtilService: Message received 5011
,08-26 19:45:26.730  1020  1513 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 19:45:26.730  1020  1513 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 19:45:26.730  1020  1513 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:45:26.730  1020  1513 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 19:45:26.740  7188  7188 E Zygote  : MountEmulatedStorage()
,08-26 19:45:26.740  7188  7188 E Zygote  : v2
08-26 19:45:26.740  7188  7188 I libpersona: KNOX_SDCARD checking this for 1000
08-26 19:45:26.740  7188  7188 I libpersona: KNOX_SDCARD not a persona
08-26 19:45:26.740  7188  7188 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 19:45:26.740  1020  1513 I ActivityManager: Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=7188 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-26 19:45:26.740  7188  7188 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-26 19:45:26.750  7188  7188 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,08-26 19:45:26.770  7188  7188 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 19:45:26.770  7188  7188 D ActivityThread: Added TimaKeyStore provider
,08-26 19:45:26.800  7188  7188 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-26 19:45:26.800  7188  7188 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-26 19:45:26.800  7188  7188 D SecurityLogAgent: StateMachine : Current State = 1
,08-26 19:45:26.800  7188  7188 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-26 19:45:26.800  1020  1049 D Tethering: interfaceRemoved wlan0
08-26 19:45:26.800  1020  1049 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,08-26 19:45:26.800  1020  4357 I ActivityManager: Killing 6580:com.google.android.apps.plus/u0a117 (adj 15): empty #21
,08-26 19:45:26.810  1020  1471 W ActivityManager: userId = 0, bbcId = -10000
,08-26 19:45:26.810  1020  1471 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:45:26.810  1020  1471 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 19:45:26.810  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
,08-26 19:45:26.810  1020  1020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:45:26.810  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 19:45:26.820  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
,08-26 19:45:26.820  1020  1020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:45:26.820  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 19:45:26.820  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:45:26.820  1020  1020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:45:26.820  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 19:45:26.820  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
,08-26 19:45:26.820  1020  1020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:45:26.820  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 19:45:26.830  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
,08-26 19:45:26.830  1020  1020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:45:26.830  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 19:45:26.830  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
,08-26 19:45:26.830  1020  1020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:45:26.830  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 19:45:26.830  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
,08-26 19:45:26.830  1020  1020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:45:26.830  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 19:45:26.840  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
,08-26 19:45:26.840  1020  1020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:45:26.840  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 19:45:26.840  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
,08-26 19:45:26.840  1020  1020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:45:26.840  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 19:45:26.840  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
,08-26 19:45:26.840  1020  1020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:45:26.840  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 19:45:26.850  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
,08-26 19:45:26.850  1020  1020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:45:26.850  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 19:45:26.850  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:45:26.850  1020  1020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:45:26.850  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 19:45:26.850  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:45:26.850  1020  1020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:45:26.850  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 19:45:26.850  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:45:26.850  1020  1020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:45:26.850  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 19:45:26.860  4713  4713 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-26 19:45:26.860  1020  1033 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-26 19:45:26.860  1020  1033 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-26 19:45:26.860  1020  1033 W ActivityManager: userId = 0, bbcId = -10000
,08-26 19:45:26.860  1020  1033 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:45:26.860  1020  1033 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-26 19:45:26.870  1695  1695 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-26 19:45:26.870  4713  4713 D DockEventReceiver: finishStartingService: stopping service
,08-26 19:45:26.870  4713  4713 D BluetoothNotiBroadcastReceiver: onReceive
,08-26 19:45:26.880  1177  1177 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-26 19:45:26.880  1177  1177 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,08-26 19:45:26.890  1020  4357 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,08-26 19:45:26.890  1020  4357 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 19:45:26.890  1020  4357 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:45:26.890  1020  4357 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:45:26.890  1020  4357 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 19:45:26.910  7206  7206 E Zygote  : MountEmulatedStorage()
,08-26 19:45:26.910  7206  7206 E Zygote  : v2
08-26 19:45:26.910  7206  7206 I libpersona: KNOX_SDCARD checking this for 1000
08-26 19:45:26.910  7206  7206 I libpersona: KNOX_SDCARD not a persona
,08-26 19:45:26.910  1020  4357 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7206 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-26 19:45:26.910  7206  7206 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 19:45:26.910  7206  7206 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-26 19:45:26.920  7206  7206 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 19:45:26.930   334   334 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 19:45:26.930  7206  7206 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 19:45:26.930  7206  7206 D ActivityThread: Added TimaKeyStore provider
,08-26 19:45:26.950  7206  7206 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
,08-26 19:45:26.950  7206  7206 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
08-26 19:45:26.950  7206  7206 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,08-26 19:45:26.970  7206  7206 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,08-26 19:45:26.970  7206  7206 I PCWCLIENTTRACE_PushUtil: sales region : global
,08-26 19:45:26.970  7206  7206 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
08-26 19:45:26.970  7206  7206 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,08-26 19:45:26.970  1020  4358 I splitIntent: intent=android.net.conn.CONNECTIVITY_CHANGE will be not split. because same process=com.google.android.gms is in other queue. index=7
,08-26 19:45:26.970  1020  4358 I splitIntent: base  index=7, name=com.google.android.gms com.google.android.gms.gcm.gmsproc.GmsAutoStarter
08-26 19:45:26.970  1020  4358 I splitIntent: other index=9, name=com.google.android.gms com.google.android.gms.wearable.service.AutoStarterReceiver
,08-26 19:45:26.970  7206  7221 I PCWCLIENTTRACE_SYSTEMReceiver: noConnectivity : true
08-26 19:45:26.970  1020  4358 I splitIntent: arrangeSplitReceiver return false!! intent : android.net.conn.CONNECTIVITY_CHANGE !! do not split it!!
,08-26 19:45:26.980  1020  4358 I ActivityManager: Killing 6818:com.samsung.android.provider.shootingmodeprovider/u0a148 (adj 15): empty #21
,08-26 19:45:26.980  1020  1020 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,08-26 19:45:26.980  1020  1020 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:45:26.980  1020  1020 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:45:26.980  1020  1020 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:45:26.980  1020  1020 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 19:45:26.990  1020  1049 D Tethering: interfaceRemoved p2p0,
08-26 19:45:26.990  1020  1049 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,08-26 19:45:27.000  7223  7223 E Zygote  : MountEmulatedStorage()
08-26 19:45:27.000  7223  7223 E Zygote  : v2
08-26 19:45:27.000  7223  7223 I libpersona: KNOX_SDCARD checking this for 10001
08-26 19:45:27.000  7223  7223 I libpersona: KNOX_SDCARD not a persona
,08-26 19:45:27.000  7223  7223 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 19:45:27.000  7223  7223 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 19:45:27.000  1020  1020 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7223 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-26 19:45:27.000  7223  7223 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 19:45:27.020  7223  7223 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 19:45:27.020  7223  7223 D ActivityThread: Added TimaKeyStore provider
,08-26 19:45:27.090  1020  1032 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,08-26 19:45:27.100  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 19:45:27.100  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:45:27.100  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 19:45:27.100  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 19:45:27.110  1020  1032 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7240 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-26 19:45:27.110  1020  1032 I ActivityManager: Killing 6844:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #21
,08-26 19:45:27.110  7240  7240 E Zygote  : MountEmulatedStorage()
08-26 19:45:27.110  7240  7240 I libpersona: KNOX_SDCARD checking this for 1000
08-26 19:45:27.110  7240  7240 E Zygote  : v2
08-26 19:45:27.110  7240  7240 I libpersona: KNOX_SDCARD not a persona
08-26 19:45:27.110  7240  7240 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 19:45:27.120  7240  7240 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 19:45:27.120  7240  7240 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 19:45:27.130  7240  7240 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 19:45:27.130  7240  7240 D ActivityThread: Added TimaKeyStore provider
,08-26 19:45:27.160  7240  7240 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,08-26 19:45:27.280  7240  7240 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,08-26 19:45:27.290  7240  7240 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,08-26 19:45:27.290  7240  7240 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,08-26 19:45:27.290  7240  7240 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:,
08-26 19:45:27.290  7240  7240 I DIAGMON_AGENT: ./extraInfo: <unknown ssid>
08-26 19:45:27.290  7240  7240 W DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(27/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,08-26 19:45:27.300  1020  1491 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.fotaclient, hostingType: broadcast
,08-26 19:45:27.300  1020  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 19:45:27.300  1020  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:45:27.300  1020  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 19:45:27.300  1020  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 19:45:27.310  1020  1491 I ActivityManager: Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=7255 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-26 19:45:27.310  7255  7255 E Zygote  : MountEmulatedStorage()
08-26 19:45:27.310  1020  1491 I ActivityManager: Killing 1972:com.google.android.gms/u0a11 (adj 15): empty #21
08-26 19:45:27.310  7255  7255 E Zygote  : v2
08-26 19:45:27.310  7255  7255 I libpersona: KNOX_SDCARD checking this for 10008
08-26 19:45:27.310  7255  7255 I libpersona: KNOX_SDCARD not a persona
,08-26 19:45:27.310  7255  7255 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 19:45:27.310  7255  7255 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 19:45:27.320  7255  7255 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,08-26 19:45:27.340  7255  7255 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 19:45:27.340  7255  7255 D ActivityThread: Added TimaKeyStore provider
,08-26 19:45:27.410  1020  1491 D ActivityManager: startProcessLocked calleePkgName: com.google.android.gms, hostingType: broadcast
,08-26 19:45:27.410  1020  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 19:45:27.410  1020  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:45:27.410  1020  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 19:45:27.410  1020  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 19:45:27.430  7270  7270 E Zygote  : MountEmulatedStorage(),
08-26 19:45:27.430  7270  7270 E Zygote  : v2
08-26 19:45:27.430  7270  7270 I libpersona: KNOX_SDCARD checking this for 10011
08-26 19:45:27.430  7270  7270 I libpersona: KNOX_SDCARD not a persona
,08-26 19:45:27.430  7270  7270 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 19:45:27.430  1020  1491 I ActivityManager: Start proc com.google.android.gms for broadcast com.google.android.gms/.gcm.gmsproc.GmsAutoStarter: pid=7270 uid=10011 gids={50011, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a,
08-26 19:45:27.430  1020  1491 I ActivityManager: Killing 6873:com.sec.android.widgetapp.tapandpay/u0a152 (adj 15): empty #21
,08-26 19:45:27.430  7270  7270 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 19:45:27.430  7270  7270 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-26 19:45:27.460  7270  7270 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 19:45:27.460  7270  7270 D ActivityThread: Added TimaKeyStore provider
,08-26 19:45:27.480  7270  7270 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,08-26 19:45:27.480  7270  7270 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-26 19:45:27.520  7270  7270 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>
,08-26 19:45:27.520  7270  7270 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>
,08-26 19:45:27.530  7270  7270 I MultiDex: VM with version 2.1.0 has multidex support
,08-26 19:45:27.530  7270  7270 I MultiDex: install
08-26 19:45:27.530  7270  7270 I MultiDex: VM has multidex support, MultiDex support library is disabled.,
,08-26 19:45:27.630  7270  7270 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
,08-26 19:45:27.680  7270  7270 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,08-26 19:45:27.680  7270  7270 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@b01d378: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
08-26 19:45:27.680  7270  7270 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-26 19:45:27.700  1020  1508 I ActivityManager: Killing 6901:com.sec.android.provider.badge/u0a68 (adj 15): empty #21
,08-26 19:45:27.700  1020  1513 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
,08-26 19:45:27.700  1020  1513 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,08-26 19:45:27.700  1020  1513 W ActivityManager: userId = 0, bbcId = -10000
,08-26 19:45:27.700  1020  1513 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 19:45:27.700  1020  1513 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,08-26 19:45:27.740  7270  7289 D NativeLibraryUtils: Install completed successfully. count=0 extracted=0
,08-26 19:45:27.790  7270  7293 I iu.SyncManager: SYNC; picasa accounts
,08-26 19:45:27.800  7270  7270 D NetworkLogImpl: Loaded NetworkSpeedPredictor
,08-26 19:45:27.830  1020  4267 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-26 19:45:27.830  1020  4267 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.snet.SnetAlarmService; callingUser = 0; userId(target) = 0
,08-26 19:45:27.830  1020  4267 W ActivityManager: userId = 0, bbcId = -10000
,08-26 19:45:27.830  1020  4267 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-26 19:45:27.830  1020  4267 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 19:45:27.860  1020  1131 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,08-26 19:45:27.870  7270  7270 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-26 19:45:27.900  7270  7270 I Kids    : [GCoreUtils] Current gmscore version, 8115234 is smaller than the required version 8400000
,08-26 19:45:27.900  2789  2789 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Fri Aug 26 19:45:27 GMT+02:00 2016
,08-26 19:45:27.910  1020  4357 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
08-26 19:45:27.910  1020  4357 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,08-26 19:45:27.910  1020  4357 W ActivityManager: userId = 0, bbcId = -10000
,08-26 19:45:27.910  1020  4357 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-26 19:45:27.910  1020  4357 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,08-26 19:45:27.910  2789  2789 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,08-26 19:45:27.920  1020  1487 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,08-26 19:45:27.920  1020  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 19:45:27.920  1020  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:45:27.920  1020  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:45:27.920  1020  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 19:45:27.920  2789  2789 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,08-26 19:45:27.930   334   334 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 19:45:27.930  7298  7298 E Zygote  : MountEmulatedStorage()
08-26 19:45:27.930  7298  7298 I libpersona: KNOX_SDCARD checking this for 10031
08-26 19:45:27.930  7298  7298 E Zygote  : v2
08-26 19:45:27.930  7298  7298 I libpersona: KNOX_SDCARD not a persona
08-26 19:45:27.930  2789  2789 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
08-26 19:45:27.930  1020  1487 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7298 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a
08-26 19:45:27.930  7298  7298 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 19:45:27.940  7298  7298 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-26 19:45:27.940  7298  7298 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,08-26 19:45:27.940  2789  2789 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
08-26 19:45:27.950  2789  7297 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,08-26 19:45:27.950  2789  7297 I KLMS-2.5.123: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,08-26 19:45:27.960  2789  7297 I KLMS-2.5.123: : KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false| ETHERNET : false
,08-26 19:45:27.960  7298  7298 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 19:45:27.960  7298  7298 D ActivityThread: Added TimaKeyStore provider
,08-26 19:45:27.960  2789  7297 I KLMS-2.5.123: : StateImplV2(): networkChangeListener().END
,08-26 19:45:27.970  2789  2789 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,08-26 19:45:28.000  7298  7298 I SO_AGENT: [com.sec.android.soagent.RegisterReceiver(95/onReceive)] Network is not available
,08-26 19:45:28.000  1020  1491 I ActivityManager: Killing 6721:com.android.mms/u0a41 (adj 15): empty #21
,08-26 19:45:28.010  1020  1468 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,08-26 19:45:28.010  1020  1468 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 19:45:28.010  2728  7313 I DBG_POLICYDM: [com.policydm.XDMService(515/xdmProtoIsWIFIConnected)] WiFi network Connected : false
08-26 19:45:28.010  1020  1468 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 19:45:28.010  1020  1468 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:45:28.020  1020  1468 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 19:45:28.020  2728  7313 I DBG_POLICYDM: [com.policydm.XDMService(525/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,08-26 19:45:28.020  2728  7313 E DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver$2(104/run)] network is unserviceable
,08-26 19:45:28.020  2728  7313 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 2, current network is 0
,08-26 19:45:28.020  2728  7313 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
,08-26 19:45:28.030  7314  7314 E Zygote  : MountEmulatedStorage()
,08-26 19:45:28.030  7314  7314 E Zygote  : v2
08-26 19:45:28.030  7314  7314 I libpersona: KNOX_SDCARD checking this for 10032
,08-26 19:45:28.030  7314  7314 I libpersona: KNOX_SDCARD not a persona
,08-26 19:45:28.030  7314  7314 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 19:45:28.030  1020  1468 I ActivityManager: Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=7314 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-26 19:45:28.030  7314  7314 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 19:45:28.030  7314  7314 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,08-26 19:45:28.060  7314  7314 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 19:45:28.060  7314  7314 D ActivityThread: Added TimaKeyStore provider,
,08-26 19:45:28.090  1020  4266 D CountryDetector: No listener is left
,08-26 19:45:28.140  7314  7329 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
,08-26 19:45:28.140  7314  7329 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,08-26 19:45:28.140  7314  7314 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,08-26 19:45:28.150  1020  4357 D ActivityManager: startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
,08-26 19:45:28.150  7314  7329 D SPPClientService: PushLog.txt file is not deleted.
08-26 19:45:28.150  7314  7329 D SPPClientService: PushLog.txt file is not deleted.
08-26 19:45:28.150  7314  7329 D SPPClientService: ============PushLog. stop!
,08-26 19:45:28.150  1020  4357 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:45:28.150  1020  4357 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 19:45:28.150  1020  4357 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:45:28.150  1020  4357 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 19:45:28.170  1020  4357 I ActivityManager: Start proc com.osp.app.signin for broadcast com.osp.app.signin/.OspReceiver: pid=7331 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-26 19:45:28.170  7331  7331 E Zygote  : MountEmulatedStorage()
08-26 19:45:28.170  7331  7331 E Zygote  : v2
08-26 19:45:28.170  7331  7331 I libpersona: KNOX_SDCARD checking this for 10036
08-26 19:45:28.170  7331  7331 I libpersona: KNOX_SDCARD not a persona
,08-26 19:45:28.170  7331  7331 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 19:45:28.170  1020  4357 I ActivityManager: Killing 6912:com.sec.android.app.samsungapps/u0a9 (adj 15): empty #21
,08-26 19:45:28.170  1020  4359 D ActivityManager: startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
08-26 19:45:28.170  1020  4359 D ActivityManager: retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
,08-26 19:45:28.170  7331  7331 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 19:45:28.170  1020  4359 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:45:28.170  1020  4359 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
08-26 19:45:28.170  1020  4359 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,08-26 19:45:28.170  7331  7331 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,08-26 19:45:28.190  7331  7331 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 19:45:28.190  7331  7331 D ActivityThread: Added TimaKeyStore provider
,08-26 19:45:28.200  7314  7338 E SPPClientService: [[SystemStateMonitorService]] No Active Internet
,08-26 19:45:28.240  7331  7331 I SA      : [[OCP] ] Database Name : openData.db, DATABASE_VERSION : 2, context : com.osp.app.signin.SamsungService@329d2e04
,08-26 19:45:28.250  7331  7331 I SA      : [SSP] onCreated
,08-26 19:45:28.260  7331  7331 I SA      : [TPM] There is no property file
,08-26 19:45:28.260  7331  7331 I SA      : [SCU] isHaveSA() - false
,08-26 19:45:28.270  7331  7331 I SA      : [TPM] getModelProperty : null
,08-26 19:45:28.270  7331  7331 I SA      : [TPM] getCSCProperty : null,
08-26 19:45:28.270  7331  7331 I SA      : [DM] FLOATING AMOLED FEATURE: true
08-26 19:45:28.270  7331  7331 I SA      : [DM] PRODUCT AMOLED FEATURE: false
,08-26 19:45:28.270  7331  7331 I SA      : [DM] TFT FEATURE: false
,08-26 19:45:28.270  7331  7331 I SA      : [DM] init START
,08-26 19:45:28.280  7331  7331 I SA      : [DM] This device is not a Vodafone
,08-26 19:45:28.290  7331  7331 W ResourceType: Failure getting entry for 0x7f060005 (t=5 e=5) (error -75)
,08-26 19:45:28.290  7331  7331 W ResourceType: Failure getting entry for 0x7f060006 (t=5 e=6) (error -75)
,08-26 19:45:28.290  7331  7331 W ResourceType: Failure getting entry for 0x7f060007 (t=5 e=7) (error -75)
,08-26 19:45:28.290  7331  7331 W ResourceType: Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
08-26 19:45:28.290  7331  7331 W ResourceType: Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
,08-26 19:45:28.290  7331  7331 W ResourceType: Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
,08-26 19:45:28.290  7331  7331 W ResourceType: Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
,08-26 19:45:28.290  7331  7331 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-26 19:45:28.290  7331  7331 W ResourceType: Failure getting entry for 0x7f060017 (t=5 e=23) (error -75)
,08-26 19:45:28.290  7331  7331 W ResourceType: Failure getting entry for 0x7f060018 (t=5 e=24) (error -75)
,08-26 19:45:28.290  7331  7331 W ResourceType: Failure getting entry for 0x7f06001a (t=5 e=26) (error -75),
,08-26 19:45:28.290  7331  7331 W ResourceType: Failure getting entry for 0x7f06001c (t=5 e=28) (error -75)
,08-26 19:45:28.290  7331  7331 W ResourceType: Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
08-26 19:45:28.290  7331  7331 W ResourceType: Failure getting entry for 0x7f060020 (t=5 e=32) (error -75)
,08-26 19:45:28.290  7331  7331 W ResourceType: Failure getting entry for 0x7f060021 (t=5 e=33) (error -75)
08-26 19:45:28.290  7331  7331 W ResourceType: Failure getting entry for 0x7f060022 (t=5 e=34) (error -75)
,08-26 19:45:28.300  7331  7331 W ResourceType: Failure getting entry for 0x7f060023 (t=5 e=35) (error -75)
08-26 19:45:28.300  7331  7331 W ResourceType: Failure getting entry for 0x7f060025 (t=5 e=37) (error -75)
08-26 19:45:28.300  7331  7331 W ResourceType: Failure getting entry for 0x7f060026 (t=5 e=38) (error -75)
,08-26 19:45:28.300  7331  7331 W ResourceType: Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
,08-26 19:45:28.300  7331  7331 W ResourceType: Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
08-26 19:45:28.300  7331  7331 W ResourceType: Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
,08-26 19:45:28.300  7331  7331 W ResourceType: Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
,08-26 19:45:28.300  7331  7331 W ResourceType: Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
08-26 19:45:28.300  7331  7331 W ResourceType: Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
,08-26 19:45:28.300  7331  7331 W ResourceType: Failure getting entry for 0x7f060030 (t=5 e=48) (error -75)
08-26 19:45:28.300  7331  7331 W ResourceType: Failure getting entry for 0x7f060032 (t=5 e=50) (error -75)
,08-26 19:45:28.300  7331  7331 W ResourceType: Failure getting entry for 0x7f060031 (t=5 e=49) (error -75)
,08-26 19:45:28.300  7331  7331 I SA      : [SCU] isHaveSA() - false,
08-26 19:45:28.300  7331  7331 I SA      : support phone number id : false
08-26 19:45:28.300  7331  7331 I SA      : [DM] Supports Ref Jpn : true,
08-26 19:45:28.300  7331  7331 I SA      : [DM] init END
08-26 19:45:28.300  7331  7331 I SA      : [OR] onReceive log=[SA = 2.1.0296 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXS1BPE1 PSS = 4.497050696380942  ]
,08-26 19:45:28.310  7331  7331 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ],
08-26 19:45:28.310  7331  7331 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==,
,08-26 19:45:28.320  7331  7331 I SA      : [SLFUCHKMGR] constructor called
,08-26 19:45:28.320  7331  7331 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,08-26 19:45:28.320  7331  7331 I SA      : [OR] == isSIMCardReady false ==
,08-26 19:45:28.320  7331  7331 I SA      : [SCU] == networkStateCheck == false
,08-26 19:45:28.320  7331  7331 I SA      : [OR] onReceive END
,08-26 19:45:28.330  1020  1487 I ActivityManager: Killing 6934:com.sec.android.app.myfiles/u0a42 (adj 15): empty #21
,08-26 19:45:28.330  1233  1233 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,08-26 19:45:28.350  1682  1682 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,08-26 19:45:28.360  1747  1764 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 5
,08-26 19:45:28.360  1682  1682 D accuweather: [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,08-26 19:45:28.360  1682  1682 D accuweather: [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
,08-26 19:45:28.360  1682  1682 D accuweather: [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
08-26 19:45:28.360  1682  1682 D accuweather: [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,08-26 19:45:28.370  1682  1682 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,08-26 19:45:28.370  1682  1682 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,08-26 19:45:28.370  1020  4359 D ActivityManager: startProcessLocked calleePkgName: com.android.chrome, hostingType: broadcast
,08-26 19:45:28.370  1020  4359 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 19:45:28.370  1020  4359 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:45:28.370  1020  4359 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 19:45:28.370  1020  4359 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 19:45:28.380   295   295 E SMD     : DCD OFF
,08-26 19:45:28.390  1020  1032 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 19:45:28.390  7353  7353 E Zygote  : MountEmulatedStorage()
,08-26 19:45:28.390  7353  7353 E Zygote  : v2
08-26 19:45:28.400  7353  7353 I libpersona: KNOX_SDCARD checking this for 10077,
,08-26 19:45:28.400  1020  1032 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4280, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-26 19:45:28.400  1020  1032 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-26 19:45:28.400  1020  1032 D BatteryService: stay LED for charging
08-26 19:45:28.400  1020  1020 D BatteryService: Sending ACTION_BATTERY_CHANGED.,
08-26 19:45:28.400  1020  4359 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7353 uid=10077 gids={50077, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,08-26 19:45:28.400  7353  7353 I libpersona: KNOX_SDCARD not a persona
,08-26 19:45:28.400  7353  7353 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-26 19:45:28.400  1020  1020 I MotionRecognitionService: Plugged
08-26 19:45:28.400  1020  1020 I MotionRecognitionService: mGripSensorEnabled= false
,08-26 19:45:28.410  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
08-26 19:45:28.410  1177  1177 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-26 19:45:28.410  7353  7353 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 19:45:28.410  1425  1425 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-26 19:45:28.410  1425  1425 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-26 19:45:28.410  7353  7353 E SELinux : [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,08-26 19:45:28.430  7353  7353 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 19:45:28.430  7353  7353 D ActivityThread: Added TimaKeyStore provider
,08-26 19:45:28.430  1177  1177 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-26 19:45:28.440  1177  1177 D SViewCoverView: level :100 plugged : 2
,08-26 19:45:28.440  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-26 19:45:28.440  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-26 19:45:28.440  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 19:45:28.470  1020  1468 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-26 19:45:28.470  1020  1468 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-26 19:45:28.470  1020  1468 D SecContentProvider2: mCursor = null
,08-26 19:45:28.470  1020  1468 D WifiService: setWifiEnabled: true pid=6761, uid=10170
08-26 19:45:28.470  1020  1468 W ActivityManager: Permission Denial: getCurrentUser() from pid=6761, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
,08-26 19:45:28.470  1020  1468 W WifiService: Failed getting userId using ActivityManagerNative
08-26 19:45:28.470  1020  1468 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6761, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
08-26 19:45:28.470  1020  1468 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-26 19:45:28.470  1020  1468 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-26 19:45:28.470  1020  1468 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-26 19:45:28.470  1020  1468 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-26 19:45:28.470  1020  1468 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
08-26 19:45:28.470  1020  1468 D SettingsProvider: name = wifi_on
,08-26 19:45:28.500  1020  1131 E WifiHW  : ##################### set firmware type 0 #####################
,08-26 19:45:28.680  1020  1487 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,08-26 19:45:28.690  1020  1487 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,08-26 19:45:28.690  1020  1487 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:45:28.690  1020  1487 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 19:45:28.690  1020  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-26 19:45:28.690  1020  4267 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.magazines, hostingType: broadcast
,08-26 19:45:28.690  1020  4267 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 19:45:28.690  1020  4267 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:45:28.690  1020  4267 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:45:28.690  1020  4267 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 19:45:28.710  7374  7374 E Zygote  : MountEmulatedStorage(),
08-26 19:45:28.710  7374  7374 E Zygote  : v2
08-26 19:45:28.710  7374  7374 I libpersona: KNOX_SDCARD checking this for 10110
08-26 19:45:28.710  7374  7374 I libpersona: KNOX_SDCARD not a persona
,08-26 19:45:28.710  7374  7374 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 19:45:28.720  1020  4267 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7374 uid=10110 gids={50110, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,08-26 19:45:28.720  1020  1257 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
08-26 19:45:28.720  1020  1257 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
08-26 19:45:28.720  1020  1257 W ActivityManager: userId = 0, bbcId = -10000,
08-26 19:45:28.720  1020  1257 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 19:45:28.720  1020  1257 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-26 19:45:28.720  7374  7374 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 19:45:28.720  7374  7374 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-26 19:45:28.730  7132  7373 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,08-26 19:45:28.740   323   323 I art     : Explicit concurrent mark sweep GC freed 8708(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 735us total 28.162ms
,08-26 19:45:28.750  1020  1258 I ActivityManager: Killing 6950:com.wsomacp/u0a23 (adj 15): empty #21
,08-26 19:45:28.750  7374  7374 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 19:45:28.750  7374  7374 D ActivityThread: Added TimaKeyStore provider
,08-26 19:45:28.760   323   323 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 586us total 19.367ms
,08-26 19:45:28.770  5705  5705 D FactoryTest: Not factory mode
08-26 19:45:28.770  5705  5705 D FactoryTest: Not factory mode. isFactoryMode() returend false
,08-26 19:45:28.770  5705  5705 D MTPRx   : DRIVER_TIME_OUT 60s lapsed
08-26 19:45:28.770  5705  5705 D MTPRx   : still no open session command from host, so toast
,08-26 19:45:28.770  5705  5705 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 
08-26 19:45:28.770  5705  5705 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
,08-26 19:45:28.770  5705  5705 I Timeline: Timeline: Activity_launch_request id:com.android.settings time:116407
08-26 19:45:28.770  1020  4266 E PersonaManagerService: inState():  stateMachine is null !!
08-26 19:45:28.770  1020  4266 I PersonaManagerService: PersonaId don't exist
08-26 19:45:28.770  1020  4266 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
,08-26 19:45:28.780  1020  4266 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings,
,08-26 19:45:28.780  1020  4266 W ActivityManager: userId = 0, bbcId = -10000,
08-26 19:45:28.780  1020  4266 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:45:28.780  1020  4266 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
,08-26 19:45:28.780   323   323 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 583us total 16.574ms,
,08-26 19:45:28.780  1020  4266 W ActivityManager: mDVFSHelper.acquire()
,08-26 19:45:28.790  1020  4266 D PersonaManager: isKioskContainerExistOnDevice
,08-26 19:45:28.810  1020  4266 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-26 19:45:28.810  1020  4266 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
08-26 19:45:28.810  1020  4266 D InputDispatcher: Focused application set to: xxxx
,08-26 19:45:28.810  1020  4266 D InputDispatcher: Focus left window: 6761
,08-26 19:45:28.810  5705  5705 E MTPRx   : started activity for popup
,08-26 19:45:28.810  1020  1052 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0,
08-26 19:45:28.810  1020  1052 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-26 19:45:28.830  5705  5705 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.,
08-26 19:45:28.830  5705  5705 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,08-26 19:45:28.840  5705  5705 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-26 19:45:28.840  5705  5705 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-26 19:45:28.840  5705  5705 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-26 19:45:28.840  5705  5705 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-26 19:45:28.870  1020  1049 D Tethering: interfaceAdded wlan0
,08-26 19:45:28.880  1020  1134 E Tethering: No numeric data
,08-26 19:45:28.880  1020  1134 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-26 19:45:28.880  1020  1128 D NtpTrustedTime: currentTimeMillis() cache hit,
08-26 19:45:28.880  1020  1128 V NetworkStats: performPollLocked(flags=0x1)
08-26 19:45:28.880  1020  1128 D NetworkStatsFactory: UpdateStatsForKnox updated
08-26 19:45:28.880  1020  1128 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-26 19:45:28.880  1020  1049 D Tethering: interfaceLinkStateChanged wlan0, false
08-26 19:45:28.880  1020  1049 D Tethering: interfaceStatusChanged wlan0, false
08-26 19:45:28.880  1020  1049 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-26 19:45:28.880  1020  1134 D Tethering: clearTetheredNotification()
08-26 19:45:28.890  1020  1134 D Tethering: InitialState.processMessage what=4
08-26 19:45:28.890  1177  1177 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-26 19:45:28.890  1177  1177 D HotspotTile: updateTetherState():false, false
,08-26 19:45:28.890  1020  1134 E Tethering: No numeric data
,08-26 19:45:28.890  1020  1134 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-26 19:45:28.890  1020  1134 D Tethering: clearTetheredNotification()
,08-26 19:45:28.890  1020  1128 V NetworkStats: performPollLocked() took 6ms
08-26 19:45:28.890  1020  1128 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 19:45:28.890  1020  1049 D Tethering: interfaceLinkStateChanged p2p0, false,
08-26 19:45:28.890  1020  1049 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-26 19:45:28.890  1020  1049 D Tethering: interfaceStatusChanged p2p0, false
08-26 19:45:28.890   278  1006 I WifiHW  : wifi_change_fw_path(): fwpath = sta
08-26 19:45:28.890   278  1006 D SoftapController: Softap fwReload - Ok
08-26 19:45:28.890  1020  1049 D Tethering: interfaceAdded p2p0
08-26 19:45:28.890  1020  1049 D Tethering: p2p0 is not a tetherable iface, ignoring
,08-26 19:45:28.900   278  1006 D CommandListener: Setting iface cfg
08-26 19:45:28.900   278  1006 D CommandListener: Trying to bring down wlan0
08-26 19:45:28.900  1177  1177 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-26 19:45:28.900  1020  1128 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 19:45:28.900  1177  1177 D HotspotTile: updateTetherState():false, false
08-26 19:45:28.900  1020  1128 V NetworkStats: performPollLocked(flags=0x1)
,08-26 19:45:28.900  1020  1129 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 19:45:28.900  1020  1129 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 19:45:28.900  1020  1128 D NetworkStatsFactory: UpdateStatsForKnox updated
08-26 19:45:28.900   278  1006 D CommandListener: Clearing all IP addresses on wlan0
08-26 19:45:28.900  1020  1128 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-26 19:45:28.900  1020  1128 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 19:45:28.900  1020  1128 V NetworkStats: performPollLocked() took 4ms
08-26 19:45:28.900  1020  1131 E WifiHW  : supplicant_name : p2p_supplicant
,08-26 19:45:28.900  1020  1129 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 19:45:28.900  1020  1129 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 19:45:28.920  5705  5705 E SettingsReceiverActivity: PREF_DONT_ASK_AGAIN : true,
,08-26 19:45:28.930   334   334 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 19:45:28.970  1020  1082 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
08-26 19:45:28.970  1020  1082 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-26 19:45:28.970  1020  1082 D InputDispatcher: Focused application set to: xxxx
,08-26 19:45:28.970  1020  1082 D InputDispatcher: Focus entered window: 6761
,08-26 19:45:28.970  1020  1052 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-26 19:45:28.970  1020  1052 D PointerIcon: setMouseCustomIcon IconType is same.101
08-26 19:45:28.970  1020  1082 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
08-26 19:45:28.970  1020  1082 W InputMethodManagerService: Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@303fce attribute=null, token = android.os.BinderProxy@47133d6
,08-26 19:45:28.990  7398  7398 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
08-26 19:45:28.990  7398  7398 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-26 19:45:28.990  7398  7398 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,08-26 19:45:28.990  1020  1033 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-26 19:45:29.000  1020  1131 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,08-26 19:45:29.020  7398  7398 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,08-26 19:45:29.020  4713  4713 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-26 19:45:29.020  5705  5705 D SettingsReceiverActivity: dev.kiessupport is : TRUE
08-26 19:45:29.020   411   411 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 7398
08-26 19:45:29.020   411   411 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x0000010C
08-26 19:45:29.020  7398  7398 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
08-26 19:45:29.020  7398  7398 I wpa_supplicant: ssSupport state is = 1
08-26 19:45:29.020  7398  7398 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
08-26 19:45:29.020  7398  7398 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
08-26 19:45:29.020   411   411 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 7398
08-26 19:45:29.020   411   411 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x00000106
08-26 19:45:29.020  1177  1177 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-26 19:45:29.020  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 19:45:29.020  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-26 19:45:29.020  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:45:29.020  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:45:29.020  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:45:29.020  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:45:29.020  1177  1177 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-26 19:45:29.020  1177  1177 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-26 19:45:29.020  1177  1177 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
,08-26 19:45:29.020  1177  1784 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-26 19:45:29.020  1177  1177 D HotspotTile: onReceive : 2, 0
,08-26 19:45:29.030  5705  5705 D PhoneWindow: *FMB* installDecor mIsFloating : true
08-26 19:45:29.030  5705  5705 D PhoneWindow: *FMB* installDecor flags : 8388610
,08-26 19:45:29.030  6761  6761 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 19:45:29.030  6761  6761 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 19:45:29.090  6761  6761 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-26 19:45:29.090  6761  6761 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STARTED
08-26 19:45:29.090  6761  6761 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
08-26 19:45:29.090  6761  6761 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: RESUMED
,08-26 19:45:29.090  1020  1082 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
08-26 19:45:29.090  1020  1082 D KnoxTimeoutHandler: postActiveUserChange for user 0
,08-26 19:45:29.090  1020  1082 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
08-26 19:45:29.090  1020  1020 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-26 19:45:29.090  1020  1020 D PersonaManagerService: getPersonasForUser(): returning null!
,08-26 19:45:29.110  6761  6761 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-26 19:45:29.110  6761  6761 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-26 19:45:29.120  6761  6761 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@290a54c9 time:116750,
08-26 19:45:29.120  6761  6761 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@16295c15 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@17ef88fb, 16908290=android.view.AbsSavedState$1@17ef88fb}, android:focusedViewId=100}]}]
08-26 19:45:29.120  6761  6761 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
,08-26 19:45:29.120  6761  6761 V ActivityThread: updateVisibility : ActivityRecord{194bc6ef token=android.os.BinderProxy@290a54c9 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
08-26 19:45:29.120  6761  6761 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-26 19:45:29.120  6761  6761 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-26 19:45:29.130  1020  4266 D PersonaManager: isKioskContainerExistOnDevice
,08-26 19:45:29.160   257   536 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
08-26 19:45:29.160   257   536 W Vold    : Returning OperationFailed - no handler for errno 0
,08-26 19:45:29.160  7374  7403 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,08-26 19:45:29.160   257   536 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
08-26 19:45:29.160   257   536 W Vold    : Returning OperationFailed - no handler for errno 0
,08-26 19:45:29.170  7374  7403 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,08-26 19:45:29.220   257   536 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/,
08-26 19:45:29.220   257   536 W Vold    : Returning OperationFailed - no handler for errno 0
,08-26 19:45:29.220  7374  7404 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,08-26 19:45:29.220   411   411 I SecureStorage: [INFO]: SPID(0x00000002)Secure Storage Daemon finished processing with result: 0
,08-26 19:45:29.220  7374  7374 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:,
08-26 19:45:29.220  7374  7374 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-26 19:45:29.220  7374  7374 I GAv4    :   adb logcat -s GAv4
,08-26 19:45:29.230   257   536 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
,08-26 19:45:29.230   257   536 W Vold    : Returning OperationFailed - no handler for errno 0
,08-26 19:45:29.230  7374  7404 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,08-26 19:45:29.230  7398  7398 I SecureStorage: [INFO]: SPID(0x00000002)Processing data has been completed
,08-26 19:45:29.240  7374  7374 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-26 19:45:29.240  1020  1033 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-26 19:45:29.260  7374  7374 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-26 19:45:29.260  7374  7406 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-26 19:45:29.280  7398  7398 I wpa_supplicant: Ctrl_iface: loading cred from phone
08-26 19:45:29.280  7398  7398 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,08-26 19:45:29.320  7398  7398 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage
,08-26 19:45:29.330   411   411 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7398
08-26 19:45:29.330   411   411 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C,
08-26 19:45:29.330  7398  7398 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
08-26 19:45:29.330  7398  7398 I wpa_supplicant: ssSupport state is = 1
,08-26 19:45:29.330  7398  7398 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,08-26 19:45:29.330  7398  7398 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-26 19:45:29.330  7398  7398 E wpa_supplicant: SIM READ ERROR
08-26 19:45:29.330  7398  7398 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-26 19:45:29.330  7398  7398 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory,
08-26 19:45:29.330  7398  7398 E wpa_supplicant: SIM READ ERROR
08-26 19:45:29.330  7398  7398 I wpa_supplicant: Blacklist: Clear (all) ,
,08-26 19:45:29.330  7398  7398 I wpa_supplicant: wpa_default_ap_write_once
08-26 19:45:29.330  7398  7398 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
,08-26 19:45:29.330  7398  7398 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-26 19:45:29.330  7398  7398 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
08-26 19:45:29.330  7398  7398 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-26 19:45:29.330  7398  7398 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory,
08-26 19:45:29.330  7398  7398 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-26 19:45:29.330  1020  1049 D Tethering: interfaceLinkStateChanged wlan0, false
08-26 19:45:29.330  1020  1049 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-26 19:45:29.330  1020  1049 D Tethering: interfaceStatusChanged wlan0, false
,08-26 19:45:29.390  7398  7398 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec
,08-26 19:45:29.480  1020  1491 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 19:45:29.480  1020  1491 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:45:29.480  1020  1491 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 19:45:29.480  1020  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,08-26 19:45:29.510  7398  7398 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED,
,08-26 19:45:29.510  7398  7398 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage,
,08-26 19:45:29.520  7398  7398 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage,
08-26 19:45:29.520   411   411 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7398
08-26 19:45:29.520   411   411 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
,08-26 19:45:29.530  7398  7398 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
08-26 19:45:29.530  7398  7398 I wpa_supplicant: ssSupport state is = 1
,08-26 19:45:29.530  7398  7398 I wpa_supplicant: Ctrl_iface: loading cred from phone,
08-26 19:45:29.530  7398  7398 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,08-26 19:45:29.530  7374  7374 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
,08-26 19:45:29.540  7398  7398 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage
,08-26 19:45:29.540   411   411 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7398
08-26 19:45:29.540   411   411 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
,08-26 19:45:29.540  7398  7398 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
08-26 19:45:29.540  7398  7398 I wpa_supplicant: ssSupport state is = 1
08-26 19:45:29.540  7398  7398 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-26 19:45:29.540  7398  7398 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-26 19:45:29.540  7398  7398 E wpa_supplicant: SIM READ ERROR
,08-26 19:45:29.540  7398  7398 I wpa_supplicant: wpa_default_ap_write_once
08-26 19:45:29.540  7398  7398 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-26 19:45:29.540  7398  7398 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-26 19:45:29.550  1020  1049 D Tethering: interfaceLinkStateChanged p2p0, false
08-26 19:45:29.550  1020  1049 D Tethering: interfaceStatusChanged p2p0, false
08-26 19:45:29.550  1020  1049 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-26 19:45:29.550  1020  1049 D Tethering: interfaceLinkStateChanged p2p0, false
08-26 19:45:29.550  1020  1049 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-26 19:45:29.550  1020  1049 D Tethering: interfaceStatusChanged p2p0, false
,08-26 19:45:29.550  7374  7374 I cr.library_loader: Time to load native libraries: 2 ms (timestamps 7186-7188)
08-26 19:45:29.550  7374  7374 I cr.library_loader: Expected native library version number "", actual native library version number ""
,08-26 19:45:29.570  7374  7374 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {12d768cf}
,08-26 19:45:29.570  7374  7374 I cr.library_loader: Expected native library version number "", actual native library version number ""
08-26 19:45:29.570  7374  7374 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
,08-26 19:45:29.580  7398  7398 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE
08-26 19:45:29.580  7398  7398 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,08-26 19:45:29.590  7374  7374 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
,08-26 19:45:29.590  7374  7374 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-26 19:45:29.590  7374  7374 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-26 19:45:29.610  1020  1047 W ProcessCpuTracker: Skipping unknown process pid 7424
,08-26 19:45:29.610  7374  7374 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-26 19:45:29.610  7374  7374 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-26 19:45:29.610  7374  7374 I Adreno-EGL: Build Date: 04/06/15 Mon
08-26 19:45:29.610  7374  7374 I Adreno-EGL: Local Branch: 
08-26 19:45:29.610  7374  7374 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-26 19:45:29.610  7374  7374 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-26 19:45:29.610  7374  7374 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-26 19:45:29.680  7374  7374 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-26 19:45:29.680  7374  7438 W cr.media: Requires BLUETOOTH permission
,08-26 19:45:29.690  7374  7374 I NSApplication: Starting up...
,08-26 19:45:29.690  1020  1468 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-26 19:45:29.690  1020  1082 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-26 19:45:29.700  1020  4357 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
,08-26 19:45:29.700  1020  4357 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 19:45:29.700  1020  4357 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:45:29.700  1020  4357 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:45:29.700  1020  4357 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 19:45:29.710  1020  4357 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7443 uid=10117 gids={50117, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a,
08-26 19:45:29.710  7443  7443 E Zygote  : MountEmulatedStorage(),
08-26 19:45:29.710  7443  7443 I libpersona: KNOX_SDCARD checking this for 10117
08-26 19:45:29.710  7443  7443 E Zygote  : v2
08-26 19:45:29.710  7443  7443 I libpersona: KNOX_SDCARD not a persona
,08-26 19:45:29.710  7443  7443 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-26 19:45:29.710  1020  4357 I ActivityManager: Killing 6990:com.samsung.android.app.filterinstaller/1000 (adj 15): empty #21
,08-26 19:45:29.720  7398  7398 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED
08-26 19:45:29.720  7398  7398 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
08-26 19:45:29.720  7398  7398 I wpa_supplicant: Skip scan - bUseNetwork false
08-26 19:45:29.720  7443  7443 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 19:45:29.720  7443  7443 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-26 19:45:29.720  1020  1131 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,08-26 19:45:29.730  1020  1131 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-26 19:45:29.730  7398  7398 I wpa_supplicant: HOTSPOT20_ENABLE called
08-26 19:45:29.730  7398  7398 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-26 19:45:29.730  7398  7398 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-26 19:45:29.730  7398  7398 E wpa_supplicant: SIM READ ERROR
,08-26 19:45:29.730  7398  7398 I wpa_supplicant: Blacklist: Clear (all) 
,08-26 19:45:29.740  7443  7443 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 19:45:29.740  7443  7443 D ActivityThread: Added TimaKeyStore provider
,08-26 19:45:29.750  7398  7398 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,08-26 19:45:29.760  7443  7443 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-26 19:45:29.770  7398  7398 I wpa_supplicant: Skip scan - bUseNetwork false
,08-26 19:45:29.770  1020  1131 D WifiConfigStore: Loading config and enabling all networks 
,08-26 19:45:29.780  1177  1177 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-26 19:45:29.780  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 19:45:29.780  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-26 19:45:29.780  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 19:45:29.780  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:45:29.780  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:45:29.780  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 19:45:29.780  1177  1177 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-26 19:45:29.780  1177  1177 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-26 19:45:29.780  1177  1177 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
08-26 19:45:29.780  4713  4713 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
08-26 19:45:29.780  1177  1177 D HotspotTile: onReceive : 3, 0
08-26 19:45:29.780  1177  1784 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-26 19:45:29.790  6761  6761 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 19:45:29.790  6761  6761 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 19:45:29.790  6761  6761 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:45:29.790  6761  6761 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 19:45:29.790  6761  6761 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 19:45:29.790  6761  6761 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 19:45:29.790  6761  6761 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 19:45:29.790  6761  6761 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 19:45:29.790  6761  6761 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 19:45:29.790  6761  6761 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 19:45:29.790  6761  6761 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-26 19:45:29.790  1020  1131 E WifiConfigStore: Not a HS20
,08-26 19:45:29.790  6761  6761 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 19:45:29.790  6761  6761 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 19:45:29.790  6761  6761 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:45:29.790  6761  6761 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 19:45:29.790  6761  6761 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 19:45:29.790  6761  6761 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 19:45:29.790  6761  6761 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 19:45:29.790  6761  6761 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 19:45:29.790  6761  6761 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 19:45:29.790  6761  6761 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 19:45:29.790  6761  6761 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-26 19:45:29.790  1020  1131 D WifiNative-wlan0: callSECApiInt - ID [65]
,08-26 19:45:29.800  1020  1131 D WifiNative-wlan0: callSECApiBoolean - ID [13]
08-26 19:45:29.800  7398  7398 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
08-26 19:45:29.800  7398  7398 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
08-26 19:45:29.800  7398  7398 I wpa_supplicant: reset timer : RESET_TIMER 0
08-26 19:45:29.800  7398  7398 I wpa_supplicant: P2P: Current p2p state = IDLE
08-26 19:45:29.800  7398  7398 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
08-26 19:45:29.800  7398  7398 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
,08-26 19:45:29.800  7398  7398 I wpa_supplicant: First Scan Start
08-26 19:45:29.800  7398  7398 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-26 19:45:29.800  1020  1131 D WifiNative-wlan0: Setting external_sim to 1
08-26 19:45:29.800  1020  1131 D WifiStateMachine: Setting OUI to DA-A1-19
08-26 19:45:29.800  1020  1131 I WifiNative-HAL: startHal
,08-26 19:45:29.800  1020  1131 E wifi    : getStaticLongField sWifiHalHandle 0x9ef7688c
08-26 19:45:29.800  1020  1131 I WifiNative-HAL: Could not start hal
,08-26 19:45:29.800  7132  7132 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-26 19:45:29.800  1020  1131 E WifiNative-wlan0: do suspend true
,08-26 19:45:29.810  1020  1130 D WifiP2pService: P2pDisabledState{ what=131203 }
,08-26 19:45:29.810  1020  1131 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,08-26 19:45:29.810  1020  1020 D WifiScanningService: SCAN_AVAILABLE : 3
08-26 19:45:29.810  1020  1020 D RttService: SCAN_AVAILABLE : 3,
08-26 19:45:29.810  1020  1154 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
,08-26 19:45:29.810  1020  1130 D WifiP2pService: P2pEnablingState
08-26 19:45:29.810  1020  1154 I WifiNative-HAL: startHal
08-26 19:45:29.810  1020  1130 D WifiP2pService: P2pEnablingState{ what=147457 }
,08-26 19:45:29.810  1020  1155 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:45:29.810  1020  1130 D WifiP2pService: P2p socket connection successful
08-26 19:45:29.810  1020  1154 E wifi    : getStaticLongField sWifiHalHandle 0x9df369bc
08-26 19:45:29.810  1020  1130 D WifiP2pService: P2pEnabledState
08-26 19:45:29.810  1020  1154 I WifiNative-HAL: Could not start hal
08-26 19:45:29.810  1020  1130 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
08-26 19:45:29.810  1020  1154 E WifiScanningService: could not start HAL
08-26 19:45:29.810   278  1006 D CommandListener: Setting iface cfg
08-26 19:45:29.810   278  1006 D CommandListener: Trying to bring up p2p0
08-26 19:45:29.810  1020  1130 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-26 19:45:29.810  1020  1131 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-26 19:45:29.810  1020  1131 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
,08-26 19:45:29.810  1020  1131 E WifiNative-wlan0: invaild command id : 215
08-26 19:45:29.810  7398  7398 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
08-26 19:45:29.810  7398  7398 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
08-26 19:45:29.810  1020  1133 E ConnectivityService: updateNetworkInfo()
,08-26 19:45:29.820  1020  1020 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,08-26 19:45:29.820  1020  1052 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
08-26 19:45:29.820  1020  1052 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-26 19:45:29.820  1020  1052 D WifiDisplayController: disconnect
08-26 19:45:29.820  1020  1052 D WifiDisplayController: updateConnection
08-26 19:45:29.820  1020  1052 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-26 19:45:29.820  1020  1052 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-26 19:45:29.820  1020  1130 D WifiNative-p2p0: p2pGetDeviceAddress
08-26 19:45:29.820  7398  7398 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands
,08-26 19:45:29.820  1020  1131 E WifiStateMachine: Failed to set frequency band 0
08-26 19:45:29.820  1020  1052 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 19:45:29.820  1020  1130 D WifiNative-p2p0: p2pGetDeviceAddress returning 0a:ec:a9:50:75:42
08-26 19:45:29.820  1020  1052 D WifiDisplayAdapter: onP2pDisconnected
08-26 19:45:29.820  1020  1131 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-26 19:45:29.820  1020  1052 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-26 19:45:29.820  1020  1131 D SecContentProvider2: mCursor = null
08-26 19:45:29.820  1020  1052 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-26 19:45:29.820  1177  1177 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-26 19:45:29.820  1020  1468 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-26 19:45:29.830  1020  1130 D WifiP2pService: DeviceAddress: 0a:75:42
,08-26 19:45:29.830  1020  1131 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-26 19:45:29.830  1177  1177 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-26 19:45:29.830  1020  1131 D SecContentProvider2: mCursor = null
08-26 19:45:29.830  1020  1052 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Galaxy A3
08-26 19:45:29.830  1020  1052 D WifiDisplayController:  deviceAddress: 0a:ec:a9:50:75:42
08-26 19:45:29.830  1020  1052 D WifiDisplayController:  primary type: 10-0050F204-5
08-26 19:45:29.830  1020  1052 D WifiDisplayController:  secondary type: null
08-26 19:45:29.830  1020  1052 D WifiDisplayController:  wps: 0
08-26 19:45:29.830  1020  1052 D WifiDisplayController:  grpcapab: 0
08-26 19:45:29.830  1020  1052 D WifiDisplayController:  devcapab: 0
08-26 19:45:29.830  1020  1052 D WifiDisplayController:  status: 3
08-26 19:45:29.830  1020  1052 D WifiDisplayController:  wfdInfo: null
08-26 19:45:29.830  1020  1052 D WifiDisplayController:  groupownerAddress: null
08-26 19:45:29.830  1020  1052 D WifiDisplayController:  GOdeviceName: null
08-26 19:45:29.830  1020  1052 D WifiDisplayController:  interfaceAddress: 
08-26 19:45:29.830  1020  1052 D WifiDisplayController:  SConnectInfo : null
,08-26 19:45:29.850  1020  1130 D WifiP2pService: sending p2p persistent groups changed broadcast
,08-26 19:45:29.850  1020  1130 D WifiP2pService: InactiveState
08-26 19:45:29.850  1020  1130 D WifiP2pService: InactiveState{ what=143376 }
,08-26 19:45:29.850  1020  1130 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-26 19:45:29.850  7398  7398 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-26 19:45:29.850  1020  1130 D WifiP2pService: InactiveState{ what=143376 }
08-26 19:45:29.850  1020  1130 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-26 19:45:29.880  1020  1049 D Tethering: interfaceLinkStateChanged p2p0, false
,08-26 19:45:29.880  1020  1049 D Tethering: interfaceStatusChanged p2p0, false
,08-26 19:45:29.880  1020  1049 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-26 19:45:29.930   334   334 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 19:45:30.120  1020  1257 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,08-26 19:45:30.120  1020  1257 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 19:45:30.120  1020  1257 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:45:30.120  1020  1257 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:45:30.120  1020  1257 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 19:45:30.140  7468  7468 E Zygote  : MountEmulatedStorage()
,08-26 19:45:30.140  7468  7468 E Zygote  : v2
08-26 19:45:30.140  7468  7468 I libpersona: KNOX_SDCARD checking this for 10121
08-26 19:45:30.140  7468  7468 I libpersona: KNOX_SDCARD not a persona,
,08-26 19:45:30.140  7468  7468 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
08-26 19:45:30.140  1020  1257 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7468 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
08-26 19:45:30.140  1020  1257 I ActivityManager: Killing 7008:com.sec.android.widgetapp.SPlannerAppWidget/u0a130 (adj 15): empty #21
,08-26 19:45:30.140  7468  7468 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 19:45:30.150  7468  7468 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 19:45:30.170  7468  7468 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 19:45:30.170  7468  7468 D ActivityThread: Added TimaKeyStore provider
,08-26 19:45:30.180  7468  7468 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-26 19:45:30.180  7468  7468 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,08-26 19:45:30.180  7468  7468 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-26 19:45:30.200  7468  7468 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,08-26 19:45:30.220  7468  7468 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,08-26 19:45:30.220  7468  7468 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,08-26 19:45:30.220  1020  4359 D ActivityManager: startProcessLocked calleePkgName: com.android.email, hostingType: broadcast,
,08-26 19:45:30.230  1020  4359 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:45:30.230  1020  4359 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:45:30.230  1020  4359 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:45:30.230  1020  4359 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 19:45:30.250  7486  7486 E Zygote  : MountEmulatedStorage()
,08-26 19:45:30.250  7486  7486 E Zygote  : v2
08-26 19:45:30.250  7486  7486 I libpersona: KNOX_SDCARD checking this for 10141
08-26 19:45:30.250  7486  7486 I libpersona: KNOX_SDCARD not a persona
,08-26 19:45:30.250  7486  7486 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 19:45:30.250  1020  4359 I ActivityManager: Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=7486 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,08-26 19:45:30.250  1020  4359 I ActivityManager: Killing 7024:com.android.calendar/u0a131 (adj 15): empty #21
,08-26 19:45:30.250  7486  7486 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 19:45:30.250  7486  7486 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 19:45:30.280  7486  7486 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 19:45:30.280  7486  7486 D ActivityThread: Added TimaKeyStore provider
,08-26 19:45:30.290  7486  7486 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,08-26 19:45:30.290  7486  7486 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-26 19:45:30.290  7486  7486 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-26 19:45:30.290  7486  7486 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,08-26 19:45:30.340  1020  1258 D RCPManagerService: exchangeData() failure , invalid userId
,08-26 19:45:30.350  1020  1468 D RCPManagerService: exchangeData() failure , invalid userId
,08-26 19:45:30.380  1020  1491 D RCPManagerService: exchangeData() failure , invalid userId
,08-26 19:45:30.380  1020  1487 D RCPManagerService: exchangeData() failure , invalid userId
,08-26 19:45:30.420  1020  1033 D ActivityManager: getContentProviderImpl callerProcessName:com.android.email, calleePkgName: com.sec.android.provider.badge
,08-26 19:45:30.420  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 19:45:30.420  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:45:30.420  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:45:30.420  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 19:45:30.430  1020  4359 D RCPManagerService: exchangeData() failure , invalid userId
,08-26 19:45:30.430  7508  7508 E Zygote  : MountEmulatedStorage()
,08-26 19:45:30.430  7508  7508 E Zygote  : v2
08-26 19:45:30.430  7508  7508 I libpersona: KNOX_SDCARD checking this for 10068
08-26 19:45:30.430  7508  7508 I libpersona: KNOX_SDCARD not a persona
,08-26 19:45:30.430  7508  7508 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 19:45:30.440  7508  7508 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-26 19:45:30.440  1020  1033 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7508 uid=10068 gids={50068, 9997} abi=armeabi-v7a,
08-26 19:45:30.440  7508  7508 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,08-26 19:45:30.440  1020  4357 D RCPManagerService: exchangeData() failure , invalid userId
,08-26 19:45:30.460  7508  7508 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 19:45:30.460  7508  7508 D ActivityThread: Added TimaKeyStore provider
,08-26 19:45:30.470  1020  1513 D RCPManagerService: exchangeData() failure , invalid userId
,08-26 19:45:30.470  1020  1508 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.samsungapps, hostingType: broadcast
,08-26 19:45:30.470  1020  1508 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 19:45:30.470  1020  1508 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:45:30.470  1020  1508 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:45:30.470  1020  1508 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 19:45:30.480  7508  7508 D BadgeProvider: onCreate,
08-26 19:45:30.480  7508  7508 D BadgeProvider: DatabaseHelper,
,08-26 19:45:30.490  7524  7524 E Zygote  : MountEmulatedStorage()
,08-26 19:45:30.490  7524  7524 E Zygote  : v2
08-26 19:45:30.490  7524  7524 I libpersona: KNOX_SDCARD checking this for 10009
08-26 19:45:30.490  7524  7524 I libpersona: KNOX_SDCARD not a persona
,08-26 19:45:30.490  7524  7524 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 19:45:30.490  7524  7524 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 19:45:30.490  1020  1508 I ActivityManager: Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=7524 uid=10009 gids={50009, 9997, 1028, 1015, 3003} abi=armeabi-v7a
08-26 19:45:30.490  1020  1508 I ActivityManager: Killing 6694:com.android.vending/u0a26 (adj 15): empty #21
08-26 19:45:30.490  7524  7524 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
08-26 19:45:30.490  1020  1508 I ActivityManager: Killing 6969:com.android.defcontainer/u0a3 (adj 15): empty #22
,08-26 19:45:30.520  7524  7524 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 19:45:30.520  7524  7524 D ActivityThread: Added TimaKeyStore provider
,08-26 19:45:30.590  1020  4357 I ActivityManager: Killing 7157:com.samsung.android.app.FileShareClient/u0a64 (adj 15): empty #21
,08-26 19:45:30.600  1020  1082 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-26 19:45:30.600  1020  1082 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-26 19:45:30.610  1020  1082 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:45:30.610  1020  1082 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:45:30.610  1020  1082 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-26 19:45:30.610  1627  1627 I Hs20UtilService: Starting #11
,08-26 19:45:30.610  1627  1661 I Hs20UtilService: Message received 5011
,08-26 19:45:30.610  7188  7188 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-26 19:45:30.610  7188  7188 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-26 19:45:30.610  7188  7188 D SecurityLogAgent: StateMachine : Current State = 1
08-26 19:45:30.610  7188  7188 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-26 19:45:30.620  1020  1491 W ActivityManager: userId = 0, bbcId = -10000
,08-26 19:45:30.620  1020  1491 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 19:45:30.620  1020  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 19:45:30.630  1020  1257 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
,08-26 19:45:30.630  1020  1257 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,08-26 19:45:30.630  1020  1257 W ActivityManager: userId = 0, bbcId = -10000
,08-26 19:45:30.630  1020  1257 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 19:45:30.630  1020  1257 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,08-26 19:45:30.630  1020  4266 I splitIntent: intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
,08-26 19:45:30.630  1020  4266 I splitIntent: base  index=1, name=com.google.android.gms com.google.android.gms.subscribedfeeds.ConfigurationReceiver
,08-26 19:45:30.630  1695  5017 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,08-26 19:45:30.630  1020  4266 I splitIntent: other index=5, name=com.google.android.gms com.google.android.gms.common.stats.GmsCoreStatsServiceLauncher
08-26 19:45:30.630  1020  4266 I splitIntent: arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,08-26 19:45:30.630  1020  4266 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:45:30.630  1020  4266 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 19:45:30.630  1020  4266 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 19:45:30.650  1020  1471 W ActivityManager: userId = 0, bbcId = -10000
,08-26 19:45:30.650  1020  1471 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 19:45:30.650  1020  1471 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 19:45:30.650  1695  1695 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,08-26 19:45:30.660  1020  1508 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:45:30.660  1020  1508 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 19:45:30.660  1020  1508 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 19:45:30.660  1020  1487 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
08-26 19:45:30.660  1020  1487 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.account.AccountStatusChecker$InitializeService; callingUser = 0; userId(target) = 0
,08-26 19:45:30.660  1020  1487 W ActivityManager: userId = 0, bbcId = -10000
,08-26 19:45:30.660  1020  1487 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 19:45:30.660  1020  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,08-26 19:45:30.670  1020  4357 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:45:30.670  1020  4357 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 19:45:30.670  1020  4357 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 19:45:30.670  1020  1033 I art     : Explicit concurrent mark sweep GC freed 74878(4MB) AllocSpace objects, 12(240KB) LOS objects, 33% free, 23MB/34MB, paused 2.731ms total 177.218ms
,08-26 19:45:30.680  1695  1695 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 19:45:30.680  1695  1695 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 19:45:30.680  1020  1468 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:45:30.680  1020  1468 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 19:45:30.680  1020  1468 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 19:45:30.690  7508  7518 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,08-26 19:45:30.690  1020  4357 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
08-26 19:45:30.690  1020  4357 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,08-26 19:45:30.690  1020  1257 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,08-26 19:45:30.690  7270  7270 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,08-26 19:45:30.690  1020  1513 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,08-26 19:45:30.700  1020  1487 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-26 19:45:30.700  1020  1487 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
,08-26 19:45:30.700  7508  7518 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
08-26 19:45:30.700  7508  7518 D BadgeProvider: sendNotify, [notify] : null
08-26 19:45:30.700  7508  7518 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
08-26 19:45:30.700  7508  7518 D BadgeProvider: update, [BadgeCount] : badgecount=0
08-26 19:45:30.700  7508  7518 D BadgeProvider: update, [UpdateCount] : 1
,08-26 19:45:30.700  1020  1487 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:45:30.700  1020  1487 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 19:45:30.700  1020  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 19:45:30.700  1495  1495 D Launcher.Model: reloadBadges entered.
,08-26 19:45:30.720  1020  1491 W ActivityManager: userId = 0, bbcId = -10000
,08-26 19:45:30.720  1020  1491 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 19:45:30.720  1020  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 19:45:30.720  1020  1082 W ActivityManager: userId = 0, bbcId = -10000
,08-26 19:45:30.720  1020  1082 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 19:45:30.720  1020  1082 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 19:45:30.730  1020  1471 W ActivityManager: userId = 0, bbcId = -10000
,08-26 19:45:30.730  1020  1471 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 19:45:30.730  1020  1471 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 19:45:30.730  1020  1468 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 19:45:30.730  1020  1468 W ActivityManager: userId = 0, bbcId = -10000
,08-26 19:45:30.730  1020  1468 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 19:45:30.730  1020  1468 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 19:45:30.730  1020  1468 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 19:45:30.730  1020  1468 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:45:30.730  1020  1468 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:45:30.730  1020  1468 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 19:45:30.750  7542  7542 E Zygote  : MountEmulatedStorage()
08-26 19:45:30.750  7542  7542 E Zygote  : v2
08-26 19:45:30.750  7542  7542 I libpersona: KNOX_SDCARD checking this for 10011
08-26 19:45:30.750  7542  7542 I libpersona: KNOX_SDCARD not a persona
,08-26 19:45:30.750  7542  7542 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 19:45:30.750  1020  1468 I ActivityManager: Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableService: pid=7542 uid=10011 gids={50011, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,08-26 19:45:30.750  7542  7542 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 19:45:30.750  1020  1471 W ActivityManager: userId = 0, bbcId = -10000,
08-26 19:45:30.750  1020  1471 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 19:45:30.750  1020  1471 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-26 19:45:30.750  7542  7542 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-26 19:45:30.760  1020  4357 W ActivityManager: userId = 0, bbcId = -10000
,08-26 19:45:30.760  1020  4357 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 19:45:30.760  1020  4357 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 19:45:30.770  7542  7542 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 19:45:30.770  7542  7542 D ActivityThread: Added TimaKeyStore provider
,08-26 19:45:30.780  7542  7542 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-26 19:45:30.780  7542  7542 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-26 19:45:30.810  7542  7542 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>
,08-26 19:45:30.810  7542  7542 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>
,08-26 19:45:30.820  7542  7542 I MultiDex: VM with version 2.1.0 has multidex support
08-26 19:45:30.820  7542  7542 I MultiDex: install
08-26 19:45:30.820  7542  7542 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-26 19:45:30.830  1472  1788 D TP/SmsProvider: query,matched:0, calling pid = 7270
,08-26 19:45:30.830  1472  1788 D TP/SmsProvider: match 0:Elapsed time : 1.863 ms
,08-26 19:45:30.840  1020  1487 W ActivityManager: userId = 0, bbcId = -10000
,08-26 19:45:30.840  1020  1487 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 19:45:30.840  1020  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 19:45:30.850  1020  1468 W ActivityManager: userId = 0, bbcId = -10000
,08-26 19:45:30.850  1020  1468 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 19:45:30.850  1020  1468 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 19:45:30.850  1020  4266 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 19:45:30.860  1020  4266 W ActivityManager: userId = 0, bbcId = -10000
,08-26 19:45:30.860  1020  4266 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 19:45:30.860  1020  4266 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 19:45:30.860  7542  7542 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
,08-26 19:45:30.860  1020  1033 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:45:30.860  1020  1033 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 19:45:30.860  1020  1033 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 19:45:30.860  1472  1488 D TP/MmsProvider: Query uri=content://mms, match=0, calling pid = 7270
,08-26 19:45:30.870  1020  4267 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-26 19:45:30.870  1020  4267 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-26 19:45:30.870  1020  4267 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:45:30.870  1020  4267 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:45:30.870  1020  4267 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-26 19:45:30.870  1627  1627 I Hs20UtilService: Starting #12
,08-26 19:45:30.870  1627  1661 I Hs20UtilService: Message received 5011
,08-26 19:45:30.880  1020  4359 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-26 19:45:30.880  1020  4359 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,08-26 19:45:30.880  1020  4359 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:45:30.880  1020  4359 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 19:45:30.880  1020  4359 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 19:45:30.880  7188  7188 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-26 19:45:30.880  7188  7188 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-26 19:45:30.880  7188  7188 D SecurityLogAgent: StateMachine : Current State = 1
08-26 19:45:30.880  7188  7188 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-26 19:45:30.880  7270  7561 D LocationInitializer: Restart initialization of location
,08-26 19:45:30.890  1020  1257 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-26 19:45:30.890  1020  1257 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
,08-26 19:45:30.890  1472  1788 D TP/SmsProvider: query,matched:0, calling pid = 7270
,08-26 19:45:30.890  1020  1257 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:45:30.890  1020  1257 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 19:45:30.890  1020  1257 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 19:45:30.890  1472  1788 D TP/SmsProvider: match 0:Elapsed time : 1.651 ms
08-26 19:45:30.900  1020  4358 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-26 19:45:30.900  1020  4358 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-26 19:45:30.900  1020  4358 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:45:30.900  1020  4358 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:45:30.900  1020  4358 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-26 19:45:30.900  1627  1627 I Hs20UtilService: Starting #13
,08-26 19:45:30.900  1627  1661 I Hs20UtilService: Message received 5011
,08-26 19:45:30.900  1020  1131 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-26 19:45:30.900  1020  1131 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-26 19:45:30.900  1020  1131 E WifiNative-wlan0: invaild command id : 215
,08-26 19:45:30.900  7188  7188 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-26 19:45:30.900  7188  7188 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-26 19:45:30.900  7188  7188 D SecurityLogAgent: StateMachine : Current State = 1
08-26 19:45:30.900  7188  7188 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-26 19:45:30.910  1020  1471 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 19:45:30.910  1020  1471 W ActivityManager: userId = 0, bbcId = -10000
,08-26 19:45:30.910  1020  1471 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 19:45:30.910  1020  1471 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,08-26 19:45:30.930  7542  7542 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,08-26 19:45:30.930  7542  7542 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@205be918: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
08-26 19:45:30.930  7542  7542 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-26 19:45:30.930   334   334 I ServiceManager: Waiting for service AtCmdFwd...
08-26 19:45:30.930  4713  4713 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-26 19:45:30.940  4713  4713 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-26 19:45:30.940  4713  4713 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-26 19:45:30.940  1472  1488 D TP/MmsProvider: Query uri=content://mms, match=0, calling pid = 7270
,08-26 19:45:30.940  4713  4713 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-26 19:45:30.940  4713  4713 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-26 19:45:30.940  4713  4713 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-26 19:45:30.940  4713  4794 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-26 19:45:30.940  1020  4359 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
,08-26 19:45:30.940  1020  4359 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:45:30.940  1020  4359 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:45:30.940  1020  4359 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:45:30.940  1020  4359 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 19:45:30.950  7563  7563 E Zygote  : MountEmulatedStorage(),
08-26 19:45:30.950  7563  7563 I libpersona: KNOX_SDCARD checking this for 10064
08-26 19:45:30.950  7563  7563 E Zygote  : v2
08-26 19:45:30.950  7563  7563 I libpersona: KNOX_SDCARD not a persona
08-26 19:45:30.950  7563  7563 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 19:45:30.950  1020  4359 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=7563 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-26 19:45:30.960  7563  7563 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-26 19:45:30.960  7563  7563 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 19:45:30.980  7542  7542 D WearableService: callingUid 10011, callindPid: 7542
,08-26 19:45:30.980  7563  7563 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 19:45:30.980  7563  7563 D ActivityThread: Added TimaKeyStore provider
,08-26 19:45:31.000  7542  7569 D NativeLibraryUtils: Install completed successfully. count=0 extracted=0
,08-26 19:45:31.010  7563  7563 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,08-26 19:45:31.020  7398  7398 I wpa_supplicant: nl80211: Received scan results (29 BSSes)
,08-26 19:45:31.020  7270  7283 I art     : Background partial concurrent mark sweep GC freed 3919(388KB) AllocSpace objects, 10(160KB) LOS objects, 39% free, 7MB/11MB, paused 6.855ms total 39.250ms
,08-26 19:45:31.020  7398  7398 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
08-26 19:45:31.020  7398  7398 I wpa_supplicant: Trying to associate with SSID '4E47373030'
08-26 19:45:31.020  7398  7398 I wpa_supplicant: Trying to associate with  'G700'
08-26 19:45:31.020  7398  7398 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
08-26 19:45:31.020  7398  7398 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
08-26 19:45:31.020  1020  7450 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
,08-26 19:45:31.030  7563  7563 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-26 19:45:31.030  1806  3103 E MDM     : [191] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,08-26 19:45:31.030  7563  7563 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-26 19:45:31.040  1020  1131 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-26 19:45:31.040  1020  1131 D SecContentProvider2: mCursor = null
,08-26 19:45:31.060  7563  7563 D FileShare-Client: Outbound.stopDelayTimer - 
,08-26 19:45:31.070  7172  7172 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-26 19:45:31.070  1020  4357 W ActivityManager: userId = 0, bbcId = -10000
,08-26 19:45:31.070  1020  4357 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 19:45:31.070  1020  4357 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 19:45:31.070  1020  1487 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
,08-26 19:45:31.070  1020  1487 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,08-26 19:45:31.070  1020  1487 W ActivityManager: userId = 0, bbcId = -10000
,08-26 19:45:31.070  1020  1487 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 19:45:31.070  1020  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,08-26 19:45:31.080  1020  1033 I splitIntent: intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
,08-26 19:45:31.080  1020  1033 I splitIntent: base  index=1, name=com.google.android.gms com.google.android.gms.subscribedfeeds.ConfigurationReceiver
08-26 19:45:31.080  1020  1033 I splitIntent: other index=5, name=com.google.android.gms com.google.android.gms.common.stats.GmsCoreStatsServiceLauncher
08-26 19:45:31.080  1020  1033 I splitIntent: arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,08-26 19:45:31.080  1020  1033 W ActivityManager: userId = 0, bbcId = -10000
,08-26 19:45:31.080  1020  1033 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 19:45:31.080  1020  1033 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 19:45:31.080  1695  5089 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,08-26 19:45:31.080  1020  4359 W ActivityManager: userId = 0, bbcId = -10000
,08-26 19:45:31.080  1020  4359 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-26 19:45:31.080  1020  4359 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 19:45:31.090  1695  1695 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,08-26 19:45:31.090  1020  4359 W ActivityManager: userId = 0, bbcId = -10000
,08-26 19:45:31.090  1020  4359 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 19:45:31.090  1020  4359 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 19:45:31.100  1020  1468 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
,08-26 19:45:31.100  1020  1468 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.account.AccountStatusChecker$InitializeService; callingUser = 0; userId(target) = 0
,08-26 19:45:31.100  1020  1468 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:45:31.100  1020  1468 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 19:45:31.100  1020  1468 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,08-26 19:45:31.100  1020  4359 W ActivityManager: userId = 0, bbcId = -10000
,08-26 19:45:31.100  1020  4359 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 19:45:31.100  1020  4359 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 19:45:31.100  1695  1695 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 19:45:31.110  1020  4267 W ActivityManager: userId = 0, bbcId = -10000
,08-26 19:45:31.110  1020  4267 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 19:45:31.110  1020  4267 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 19:45:31.110  7270  7270 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,08-26 19:45:31.110  1020  1513 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms,
08-26 19:45:31.110  1020  1513 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
08-26 19:45:31.110  1020  1513 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:45:31.110  1020  1513 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-26 19:45:31.110  1020  1513 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 19:45:31.110  1020  1487 W ActivityManager: userId = 0, bbcId = -10000
,08-26 19:45:31.120  1020  1487 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 19:45:31.120  1020  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 19:45:31.120  1020  4357 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:45:31.120  1020  4357 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 19:45:31.120  1020  4357 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 19:45:31.120  1020  1508 W ActivityManager: userId = 0, bbcId = -10000,
08-26 19:45:31.120  1020  1508 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 19:45:31.120  1020  1508 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 19:45:31.130  1020  1082 W ActivityManager: userId = 0, bbcId = -10000,
08-26 19:45:31.130  1020  1082 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 19:45:31.130  1020  1082 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 19:45:31.130  1020  4267 W ActivityManager: userId = 0, bbcId = -10000
,08-26 19:45:31.130  1020  4267 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-26 19:45:31.130  1020  4267 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 19:45:31.130  1806  5019 E MDM     : [196] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,08-26 19:45:31.140  1020  1513 W ActivityManager: userId = 0, bbcId = -10000
,08-26 19:45:31.140  1020  1513 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 19:45:31.140  1020  1513 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 19:45:31.150  1020  1487 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:45:31.150  1020  4357 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0,
,08-26 19:45:31.150  1020  1487 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 19:45:31.150  1020  1049 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-26 19:45:31.150  1020  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-26 19:45:31.150  1020  1049 D Tethering: interfaceLinkStateChanged wlan0, false
08-26 19:45:31.150  1020  1049 D Tethering: interfaceStatusChanged wlan0, false
08-26 19:45:31.150  7398  7398 E wpa_supplicant: Cmd 35605 not handled
08-26 19:45:31.150  1020  4357 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:45:31.150  1020  4357 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 19:45:31.150  1020  4357 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-26 19:45:31.150  7398  7398 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
08-26 19:45:31.150  1020  1049 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-26 19:45:31.150  7398  7398 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
08-26 19:45:31.150  1020  1049 D Tethering: interfaceLinkStateChanged wlan0, false
08-26 19:45:31.150  1020  1049 D Tethering: interfaceStatusChanged wlan0, false
08-26 19:45:31.150  7398  7398 I wpa_supplicant: Associated with F4.99.3E
08-26 19:45:31.150  7398  7398 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-26 19:45:31.150  7398  7398 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
08-26 19:45:31.150  7398  7398 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
,08-26 19:45:31.160  1020  1049 D Tethering: interfaceLinkStateChanged wlan0, false
,08-26 19:45:31.160  1020  1049 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-26 19:45:31.160  1020  1049 D Tethering: interfaceStatusChanged wlan0, false
08-26 19:45:31.160  1020  1049 D Tethering: interfaceLinkStateChanged wlan0, true
08-26 19:45:31.160  1020  1049 D Tethering: interfaceStatusChanged wlan0, true
,08-26 19:45:31.160  1020  1049 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-26 19:45:31.160  1020  1134 E Tethering: No numeric data,
,08-26 19:45:31.160  1020  1134 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-26 19:45:31.160  1020  1134 D Tethering: clearTetheredNotification()
08-26 19:45:31.160  1020  1131 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-26 19:45:31.160  1020  1131 D SecContentProvider2: mCursor = null
,08-26 19:45:31.160  7398  7398 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-26 19:45:31.160  1020  1128 V NetworkStats: performPollLocked(flags=0x1),
08-26 19:45:31.160  1020  1128 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 19:45:31.160  1177  1177 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-26 19:45:31.160  7398  7398 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
08-26 19:45:31.160  1177  1177 D HotspotTile: updateTetherState():false, false
08-26 19:45:31.160  7398  7398 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE,
08-26 19:45:31.160  7398  7398 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
08-26 19:45:31.170  7398  7398 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-26 19:45:31.170  7398  7398 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
08-26 19:45:31.170  7398  7398 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
08-26 19:45:31.170  7398  7398 I wpa_supplicant: Blacklist: Clear (temp) 
08-26 19:45:31.170  1020  1049 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-26 19:45:31.170  7398  7398 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
08-26 19:45:31.170  1020  1049 D Tethering: interfaceLinkStateChanged wlan0, true
08-26 19:45:31.170  1020  1049 D Tethering: interfaceStatusChanged wlan0, true
08-26 19:45:31.170  1020  1128 D NetworkStatsFactory: UpdateStatsForKnox updated,
08-26 19:45:31.170  1020  1128 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-26 19:45:31.170  1020  4359 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:45:31.170  1020  4359 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 19:45:31.170  1020  4359 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 19:45:31.170  1020  1128 V NetworkStats: performPollLocked() took 7ms
08-26 19:45:31.170  1020  1128 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 19:45:31.170  1020  1508 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-26 19:45:31.170  1020  1508 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
08-26 19:45:31.170  1020  1508 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:45:31.180  1020  1508 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 19:45:31.180  1020  1508 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 19:45:31.180  1020  1129 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 19:45:31.180  1020  1129 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 19:45:31.180  7270  7581 D LocationInitializer: Restart initialization of location
,08-26 19:45:31.180  1020  1491 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-26 19:45:31.180  1020  1131 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-26 19:45:31.180  1020  1491 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
08-26 19:45:31.180  1020  1131 D SecContentProvider2: mCursor = null
,08-26 19:45:31.180  1020  1491 W ActivityManager: userId = 0, bbcId = -10000,
08-26 19:45:31.180  1020  1491 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 19:45:31.180  1020  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 19:45:31.190  1020  1131 D WifiNative-wlan0: callSECApiVoid - ID [50],
,08-26 19:45:31.190  1020  1131 E WifiConfigStore: setLastSelectedConfiguration -1
,08-26 19:45:31.200  1020  1131 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
08-26 19:45:31.200  1020  1133 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
08-26 19:45:31.200  1020  1133 E ConnectivityService: updateNetworkInfo()
08-26 19:45:31.200  1020  1133 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-26 19:45:31.210  1020  1131 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-26 19:45:31.210  1177  1177 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-26 19:45:31.210  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 19:45:31.210  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-26 19:45:31.210  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:45:31.210  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:45:31.210  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:45:31.210  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 19:45:31.210  1020  1257 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-26 19:45:31.210  1020  1257 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-26 19:45:31.220  1020  1257 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:45:31.220  1020  1257 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-26 19:45:31.220  1020  1257 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-26 19:45:31.220  1020  1100 V AlarmManager: waitForAlarm result :4
,08-26 19:45:31.220  4713  4713 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-26 19:45:31.220  4713  4713 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-26 19:45:31.220  1627  1627 I Hs20UtilService: Starting #14
,08-26 19:45:31.220  4713  4713 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-26 19:45:31.220  4713  4713 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-26 19:45:31.230  1020  1131 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-26 19:45:31.230  4713  4713 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,08-26 19:45:31.230  4713  4713 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-26 19:45:31.230  4713  4794 V NearbySettings: MountReceiver.mPrefHandler - 7002
08-26 19:45:31.230  1627  1661 I Hs20UtilService: Message received 5007
,08-26 19:45:31.240   278  1006 D CommandListener: Setting iface cfg
,08-26 19:45:31.250  1020  1131 E WifiStateMachine: Start Dhcp Watchdog 2
,08-26 19:45:31.250  1020  1131 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-26 19:45:31.250  1020  1131 D SecContentProvider2: mCursor = null
,08-26 19:45:31.250   278  1002 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0,
08-26 19:45:31.250   278  1002 D Netd    : getNetworkForDns: using netid 0 for uid 10011
,08-26 19:45:31.260  1177  1177 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-26 19:45:31.260  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 19:45:31.260  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-26 19:45:31.260  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:45:31.260  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 19:45:31.260  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 19:45:31.260  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 19:45:31.270  1020  1131 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-26 19:45:31.270  1020  1131 D SecContentProvider2: mCursor = null
,08-26 19:45:31.270  1020  1047 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:45:31.270  1020  1047 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 19:45:31.270  1020  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,08-26 19:45:31.270  1020  1131 E WifiNative-wlan0: do suspend false
,08-26 19:45:31.280  1020  1130 D WifiP2pService: InactiveState{ what=143375 }
,08-26 19:45:31.280  1020  1130 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-26 19:45:31.390   295   295 E SMD     : DCD OFF,
,08-26 19:45:31.490  7587  7587 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,08-26 19:45:31.500  7587  7587 I dhcpcd  : version 5.5.6 starting,
,08-26 19:45:31.500  1020  4267 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-26 19:45:31.500  1020  4267 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-26 19:45:31.500  1020  4267 D SecContentProvider2: mCursor = null
08-26 19:45:31.500  1020  4267 D WifiService: setWifiEnabled: false pid=6761, uid=10170
08-26 19:45:31.500  1020  4267 D SettingsProvider: name = wifi_on
,08-26 19:45:31.510  7587  7587 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,08-26 19:45:31.510  1020  1131 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any,
,08-26 19:45:31.540  1020  1131 E WifiNative-wlan0: do suspend true
,08-26 19:45:31.560  1020  1130 D WifiP2pService: InactiveState{ what=143375 },
08-26 19:45:31.560  1020  1130 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-26 19:45:31.560   278  1006 D CommandListener: Clearing all IP addresses on wlan0
,08-26 19:45:31.570  1177  1177 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-26 19:45:31.570  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-26 19:45:31.570  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-26 19:45:31.570  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-26 19:45:31.570  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:45:31.570  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:45:31.570  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-26 19:45:31.570  1020  1133 E ConnectivityService: updateNetworkInfo()
08-26 19:45:31.570  1020  1133 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-26 19:45:31.570  1020  1133 E ConnectivityService: updateNetworkInfo()
,08-26 19:45:31.570  1020  1133 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] got DISCONNECTED, was satisfying 0
08-26 19:45:31.570   278  1006 E Netd    : no such netId 503
08-26 19:45:31.580  1020  1020 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-26 19:45:31.580  1020  1133 E ConnectivityService: Exception removing network: java.lang.IllegalStateException: command '79 network destroy 503' failed with '400 79 destroyNetwork() failed (Machine is not on the network)'
08-26 19:45:31.580  1020  1133 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
08-26 19:45:31.580  1020  1133 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 19:45:31.580  1020  1133 V NetworkStats: updateIfacesLocked()
08-26 19:45:31.580  1020  1133 V NetworkStats: performPollLocked(flags=0x1)
,08-26 19:45:31.580  1020  1133 D NetworkStatsFactory: UpdateStatsForKnox updated
08-26 19:45:31.580  1020  1133 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-26 19:45:31.580  1020  1130 D WifiP2pService: InactiveState{ what=131204 }
,08-26 19:45:31.580  1020  1130 D WifiP2pService: P2pEnabledState{ what=131204 }
08-26 19:45:31.580  1020  1131 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-26 19:45:31.590  1020  1130 D WifiP2pService: sending p2p connection changed broadcast: FAILED
08-26 19:45:31.590  1020  1020 D WifiScanningService: SCAN_AVAILABLE : 1
,08-26 19:45:31.590  1020  1154 D WifiScanningService: DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
,08-26 19:45:31.590  1020  1020 D RttService: SCAN_AVAILABLE : 1
08-26 19:45:31.590  1020  4357 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-26 19:45:31.590  1020  1155 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:45:31.590  1020  4357 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-26 19:45:31.590  1177  1177 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-26 19:45:31.590  1020  1133 V NetworkStats: performPollLocked() took 11ms
08-26 19:45:31.590  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-26 19:45:31.590  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-26 19:45:31.590  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:45:31.590  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:45:31.590  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:45:31.590  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:45:31.590  1020  1133 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 19:45:31.590  1020  4357 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:45:31.590  1020  4357 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-26 19:45:31.590  1020  4357 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-26 19:45:31.590  1627  1627 I Hs20UtilService: Starting #15
,08-26 19:45:31.590  1020  1133 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 503]
08-26 19:45:31.590  1020  7583 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,08-26 19:45:31.590  1020  1133 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
08-26 19:45:31.590  1020  1133 D ConnectivityService: nai.networkMonitor.doQuit()
08-26 19:45:31.590  1020  1133 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
08-26 19:45:31.590  1020  1133 E ConnectivityService: updateNetworkInfo()
08-26 19:45:31.590  1020  7583 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Disconnected - quitting
,08-26 19:45:31.600  1627  1661 I Hs20UtilService: Message received 5007
08-26 19:45:31.600  1020  1052 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 19:45:31.600  1020  1052 D WifiDisplayAdapter: onP2pDisconnected
08-26 19:45:31.600  1020  1052 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-26 19:45:31.600  1020  1052 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-26 19:45:31.600  1020  1129 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 19:45:31.600  1020  1129 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 19:45:31.600  7587  7587 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
08-26 19:45:31.600  7587  7587 E dhcpcd  : wlan0: sendmsg: Network is unreachable
08-26 19:45:31.600  7587  7587 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
,08-26 19:45:31.600  1020  1130 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
08-26 19:45:31.600  4713  4713 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-26 19:45:31.600  4713  4713 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-26 19:45:31.600  7587  7587 I dhcpcd  : bssid match
08-26 19:45:31.600  1020  1133 E ConnectivityService: updateNetworkInfo()
08-26 19:45:31.600  1020  1130 D WifiP2pService: P2pDisablingState
08-26 19:45:31.600  7587  7587 I dhcpcd  : wlan0: rebinding lease of 192.168.1.116
08-26 19:45:31.600  1020  1130 D WifiP2pService: P2pDisablingState{ what=147458 }
,08-26 19:45:31.600  1020  1130 D WifiP2pService: p2p socket connection lost
08-26 19:45:31.600  1020  1130 D WifiP2pService: P2pDisabledState
08-26 19:45:31.600  1020  1131 E WifiNative-wlan0: do suspend true
08-26 19:45:31.600  4713  4713 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-26 19:45:31.600  1020  1020 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,08-26 19:45:31.610  1020  1052 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
08-26 19:45:31.610  4713  4713 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-26 19:45:31.610  1020  1052 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-26 19:45:31.610  4713  4713 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-26 19:45:31.610  1020  1052 D WifiDisplayController: disconnect
08-26 19:45:31.610  4713  4713 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-26 19:45:31.610  1020  1052 D WifiDisplayController: updateConnection
08-26 19:45:31.610  4713  4794 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-26 19:45:31.610  1020  1052 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-26 19:45:31.610  1020  1052 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-26 19:45:31.610  1020  1052 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-26 19:45:31.610  1020  1052 D WifiDisplayAdapter: onP2pDisconnected
08-26 19:45:31.610  1020  1052 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-26 19:45:31.610  1020  1052 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-26 19:45:31.610  1177  1177 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
08-26 19:45:31.610  1020  4359 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-26 19:45:31.610  1177  1177 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-26 19:45:31.620  4713  4713 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-26 19:45:31.620  4713  4713 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-26 19:45:31.620  4713  4713 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-26 19:45:31.620  4713  4713 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-26 19:45:31.620  4713  4713 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-26 19:45:31.620  4713  4713 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-26 19:45:31.620  4713  4794 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-26 19:45:31.620  7563  7563 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-26 19:45:31.620  7563  7563 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
08-26 19:45:31.620  7563  7563 D FileShare-Client: Outbound.stopDelayTimer - 
,08-26 19:45:31.630  7172  7172 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-26 19:45:31.630  1020  1130 D WifiP2pService: P2pDisabledState{ what=143375 }
,08-26 19:45:31.630  1020  1130 D WifiP2pService: DefaultState{ what=143375 }
,08-26 19:45:31.640   278  1006 D CommandListener: Clearing all IP addresses on wlan0,
,08-26 19:45:31.640  1020  1020 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-26 19:45:31.640  7398  7398 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
08-26 19:45:31.640  1177  1177 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-26 19:45:31.640  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 19:45:31.640  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-26 19:45:31.640  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 19:45:31.640  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:45:31.650  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:45:31.650  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 19:45:31.650  1177  1177 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-26 19:45:31.650  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 19:45:31.650  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-26 19:45:31.650  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:45:31.650  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 19:45:31.650  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:45:31.650  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 19:45:31.660  1020  1131 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-26 19:45:31.660  1020  1131 D SecContentProvider2: mCursor = null
,08-26 19:45:31.660  1177  1177 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-26 19:45:31.660  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 19:45:31.660  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-26 19:45:31.660  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:45:31.660  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 19:45:31.660  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 19:45:31.660  4713  4713 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
08-26 19:45:31.660  1020  1471 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-26 19:45:31.660  1020  1471 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-26 19:45:31.660  1020  1471 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:45:31.660  1020  1471 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:45:31.660  1020  1471 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-26 19:45:31.660  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:45:31.660  1177  1177 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-26 19:45:31.660  1177  1177 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
,08-26 19:45:31.660  1177  1784 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-26 19:45:31.660  1177  1177 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-26 19:45:31.670  6761  6761 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 19:45:31.670  6761  6761 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 19:45:31.670  6761  6761 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:45:31.670  6761  6761 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 19:45:31.670  6761  6761 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 19:45:31.670  6761  6761 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 19:45:31.670  6761  6761 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 19:45:31.670  6761  6761 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 19:45:31.670  6761  6761 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 19:45:31.670  6761  6761 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 19:45:31.670  6761  6761 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 19:45:31.670  1177  1177 D HotspotTile: onReceive : 0, 0
,08-26 19:45:31.670  1627  1627 I Hs20UtilService: Starting #16
,08-26 19:45:31.670  6761  6761 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 19:45:31.670  6761  6761 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 19:45:31.670  6761  6761 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:45:31.670  6761  6761 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 19:45:31.670  6761  6761 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 19:45:31.670  6761  6761 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 19:45:31.670  6761  6761 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 19:45:31.670  6761  6761 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 19:45:31.670  6761  6761 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 19:45:31.670  1627  1661 I Hs20UtilService: Message received 5007
08-26 19:45:31.670  6761  6761 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 19:45:31.670  6761  6761 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 19:45:31.680  4713  4713 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-26 19:45:31.680  4713  4713 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-26 19:45:31.680  7587  7587 I dhcpcd  : wlan0: acknowledged 192.168.1.116 from 192.168.1.1
,08-26 19:45:31.680  4713  4713 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-26 19:45:31.690  4713  4713 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-26 19:45:31.690  4713  4713 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-26 19:45:31.690  4713  4713 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-26 19:45:31.690  4713  4794 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-26 19:45:31.690  1020  1487 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-26 19:45:31.690  1020  1487 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-26 19:45:31.700  1020  1487 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:45:31.700  1020  1487 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:45:31.700  1020  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-26 19:45:31.700  7188  7188 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-26 19:45:31.700  7188  7188 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-26 19:45:31.700  7188  7188 D SecurityLogAgent: StateMachine : Current State = 1
,08-26 19:45:31.700  7188  7188 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-26 19:45:31.700  1627  1627 I Hs20UtilService: Starting #17,
08-26 19:45:31.700  1627  1661 I Hs20UtilService: Message received 5011
,08-26 19:45:31.720  7587  7587 I dhcpcd  : wlan0: leased 192.168.1.116 for 172800 seconds,
,08-26 19:45:31.780  1020  1047 W ActivityManager: mDVFSHelper.release()
,08-26 19:45:31.860  7398  7398 I wpa_supplicant: Blacklist: Clear (all) 
,08-26 19:45:31.940   334   334 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1,
,08-26 19:45:32.000  1020  1049 D Tethering: interfaceLinkStateChanged p2p0, false,
08-26 19:45:32.000  1020  1049 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-26 19:45:32.000  1020  1049 D Tethering: interfaceStatusChanged p2p0, false
,08-26 19:45:32.000  7398  7398 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,08-26 19:45:32.030  7398  7398 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1,
08-26 19:45:32.030  7398  7398 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
08-26 19:45:32.030  7398  7398 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
,08-26 19:45:32.030  7398  7398 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
08-26 19:45:32.030  1020  1049 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-26 19:45:32.030  7398  7398 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
08-26 19:45:32.030  1020  1049 D Tethering: interfaceLinkStateChanged wlan0, false
08-26 19:45:32.030  1020  1049 D Tethering: interfaceStatusChanged wlan0, false
08-26 19:45:32.030  1020  1134 D Tethering: InitialState.processMessage what=4
08-26 19:45:32.030  1020  1049 D Tethering: interfaceLinkStateChanged wlan0, false
08-26 19:45:32.030  1020  1049 D Tethering: interfaceStatusChanged wlan0, false
,08-26 19:45:32.040  1020  1134 E Tethering: No numeric data
08-26 19:45:32.040  1020  1049 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-26 19:45:32.040  1020  1134 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-26 19:45:32.040  1020  1128 V NetworkStats: performPollLocked(flags=0x1)
08-26 19:45:32.040  1020  1134 D Tethering: clearTetheredNotification()
08-26 19:45:32.040  1020  1128 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 19:45:32.040  1020  1128 D NetworkStatsFactory: UpdateStatsForKnox updated
08-26 19:45:32.040  1020  1128 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-26 19:45:32.040  1020  1049 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-26 19:45:32.040  1020  1049 D Tethering: interfaceLinkStateChanged wlan0, false
08-26 19:45:32.040  1020  1049 D Tethering: interfaceStatusChanged wlan0, false
,08-26 19:45:32.050  1177  1177 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-26 19:45:32.050  1177  1177 D HotspotTile: updateTetherState():false, false
,08-26 19:45:32.050  1020  1128 V NetworkStats: performPollLocked() took 7ms
08-26 19:45:32.050  1020  1128 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 19:45:32.050  1020  1129 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 19:45:32.050  1020  1129 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 19:45:32.150  1020  1049 D Tethering: interfaceLinkStateChanged wlan0, false
,08-26 19:45:32.150  1020  1049 D Tethering: interfaceStatusChanged wlan0, false
,08-26 19:45:32.150  1020  1049 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-26 19:45:32.270  7398  7398 I wpa_supplicant: Blacklist: Clear (all) ,
,08-26 19:45:32.320  1020  1049 D Tethering: interfaceLinkStateChanged wlan0, false,
08-26 19:45:32.320  1020  1049 I Nat464Xlat: interfaceLinkStateChanged wlan0, false,
08-26 19:45:32.320  1020  1049 D Tethering: interfaceStatusChanged wlan0, false,
,08-26 19:45:32.320  7398  7398 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING ,
,08-26 19:45:32.430  1020  1131 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
08-26 19:45:32.430  1020  1131 D WifiNative-wlan0: callSECApiBoolean - ID [21]
08-26 19:45:32.430  7132  7132 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-26 19:45:32.440  1177  1177 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-26 19:45:32.440  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 19:45:32.440  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-26 19:45:32.440  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:45:32.440  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:45:32.440  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:45:32.440  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:45:32.450  1177  1177 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-26 19:45:32.450  1177  1177 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
08-26 19:45:32.450  1177  1177 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-26 19:45:32.450  1177  1784 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-26 19:45:32.450  1177  1177 D HotspotTile: onReceive : 1, 0
,08-26 19:45:32.450  1806  2213 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-26 19:45:32.450  4713  4713 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-26 19:45:32.460  6761  6761 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 19:45:32.460  6761  6761 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 19:45:32.460  1020  1508 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-26 19:45:32.460  1020  1508 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-26 19:45:32.470  1020  1508 W ActivityManager: userId = 0, bbcId = -10000
,08-26 19:45:32.470  1020  1508 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-26 19:45:32.470  1020  1508 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-26 19:45:32.470  7188  7188 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-26 19:45:32.470  7188  7188 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,08-26 19:45:32.470  7188  7188 D SecurityLogAgent: StateMachine : Current State = 1
08-26 19:45:32.480  7188  7188 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-26 19:45:32.480  1627  1627 I Hs20UtilService: Starting #18
,08-26 19:45:32.480  1627  1661 I Hs20UtilService: Message received 5011
,08-26 19:45:33.120   278  1000 E NetlinkEvent: Unknown ifindex 14 in RTM_DELADDR
,08-26 19:45:33.120  1020  1049 D Tethering: interfaceRemoved wlan0
,08-26 19:45:33.120  1020  1049 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,08-26 19:45:33.320  1020  1049 D Tethering: interfaceRemoved p2p0,
08-26 19:45:33.320  1020  1049 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,08-26 19:45:34.110  1020  1131 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,08-26 19:45:34.400   295   295 E SMD     : DCD OFF
,08-26 19:45:34.520  6761  6987 D BluetoothAdapter: enable(),
,08-26 19:45:34.520  1020  1513 W ActivityManager: Permission Denial: getCurrentUser() from pid=6761, uid=10170 requires android.permission.INTERACT_ACROSS_USERS,
,08-26 19:45:34.520  1020  1513 W BluetoothManagerService: Failed getting userId using ActivityManagerNative,
08-26 19:45:34.520  1020  1513 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6761, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
08-26 19:45:34.520  1020  1513 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-26 19:45:34.520  1020  1513 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2256)
08-26 19:45:34.520  1020  1513 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:688)
08-26 19:45:34.520  1020  1513 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
08-26 19:45:34.520  1020  1513 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
08-26 19:45:34.520  1020  1513 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-26 19:45:34.520  1020  1513 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2,
,08-26 19:45:34.530  1020  1513 D SettingsProvider: name = bluetooth_on,
,08-26 19:45:34.540  1020  1051 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-26 19:45:34.540  1020  1051 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-26 19:45:34.540  1020  1051 D SecContentProvider: uri = 3 selection = isBluetoothEnabled,
08-26 19:45:34.540  3176  3247 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
08-26 19:45:34.540  3176  3247 D BluetoothAdapterProperties: Setting state to 11
08-26 19:45:34.540  3176  3247 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-26 19:45:34.540  3176  3247 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-26 19:45:34.540  3176  3247 D BluetoothAdapterService: updateAdapterState state is 11
08-26 19:45:34.540  3176  3247 D BluetoothAdapterService: Autoconnection is available 
08-26 19:45:34.540  3176  3247 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
08-26 19:45:34.540  3176  3247 D BtConfig.SecureMode: isSecureModeOn:false
08-26 19:45:34.540  3176  3247 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-26 19:45:34.540  3176  3247 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.gatt.GattService, state= 12
08-26 19:45:34.540  3176  3247 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-26 19:45:34.540  3176  3247 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hfp.HeadsetService, state= 10
08-26 19:45:34.540  3176  3247 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-26 19:45:34.540  3176  3247 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.a2dp.A2dpService, state= 10
08-26 19:45:34.550  1020  4358 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 19:45:34.540  3176  3247 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-26 19:45:34.550  1020  4358 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-26 19:45:34.540  3176  3247 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hid.HidService, state= 10
08-26 19:45:34.540  3176  3247 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-26 19:45:34.540  3176  3247 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hdp.HealthService, state= 10
08-26 19:45:34.540  3176  3247 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-26 19:45:34.540  3176  3247 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.pan.PanService, state= 10
08-26 19:45:34.540  3176  3247 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-26 19:45:34.540  3176  3247 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.map.BluetoothMapService, state= 10
08-26 19:45:34.540  3176  3247 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-26 19:45:34.540  3176  3247 W BluetoothAdapterService: isProfileEnabled(): profile com.broadcom.bt.service.sap.SapService, state= 10
08-26 19:45:34.540  3176  3247 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-26 19:45:34.540  3176  3247 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
08-26 19:45:34.540  3176  3247 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-26 19:45:34.550  3176  3247 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
08-26 19:45:34.550  3176  3247 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-26 19:45:34.550  3176  3247 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
08-26 19:45:34.550  3176  3247 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-26 19:45:34.550  3176  3247 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
08-26 19:45:34.550  3176  3247 W BluetoothAdapterService: Unable to start service com.android.bluetooth.gatt.GattService. Invalid state: 12
08-26 19:45:34.550  3176  3247 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
08-26 19:45:34.550  3176  3247 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-26 19:45:34.550  3176  3247 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
08-26 19:45:34.550  1020  4358 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:45:34.550  1020  4358 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:45:34.550  1020  4358 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-26 19:45:34.550  3176  3247 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
08-26 19:45:34.550  3176  3247 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-26 19:45:34.550  3176  3247 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
08-26 19:45:34.550  1020  1468 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 19:45:34.550  1020  1468 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
08-26 19:45:34.550  1020  1468 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:45:34.550  1020  1468 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:45:34.550  1020  1468 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-26 19:45:34.560  3176  3247 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
08-26 19:45:34.560  3176  3247 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-26 19:45:34.560  3176  3247 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
08-26 19:45:34.560  3176  3176 D HeadsetService: Received start request. Starting profile...
08-26 19:45:34.560  3176  3176 D HeadsetService: start()
08-26 19:45:34.560  3176  3176 D HeadsetStateMachine: make
,08-26 19:45:34.560  1020  1020 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-26 19:45:34.560  1020  1020 I InputMethodManagerService: [BT Setting State] State =11
,08-26 19:45:34.560  3176  3176 E HeadsetStateMachine: # of Max HF connection is 2
,08-26 19:45:34.570  1177  1177 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-26 19:45:34.570  1177  1177 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-26 19:45:34.580  1177  1177 D BluetoothTile:  getBluetoothState : 11
,08-26 19:45:34.580  1879  1879 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
08-26 19:45:34.580  4713  4713 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-26 19:45:34.580  1177  1784 D BluetoothTile:  handleUpdatestate:false name:null
08-26 19:45:34.580  1177  1784 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-26 19:45:34.580  1020  1468 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-26 19:45:34.580  1020  4359 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-26 19:45:34.590  1177  1177 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-26 19:45:34.590  1020  1471 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 19:45:34.590  1020  1471 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-26 19:45:34.590  6761  6761 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 19:45:34.590  1020  1471 W ActivityManager: userId = 0, bbcId = -10000
,08-26 19:45:34.590  1020  1471 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:45:34.590  1020  1471 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 19:45:34.590  1020  4267 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
,08-26 19:45:34.590  1020  4267 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,08-26 19:45:34.600  6761  6761 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:45:34.600  3176  3247 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
08-26 19:45:34.600  3176  3247 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-26 19:45:34.600  3176  3247 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-26 19:45:34.600  1020  4267 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:45:34.600  1020  4267 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:45:34.600  1020  4267 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-26 19:45:34.600  1020  1257 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-26 19:45:34.600  1020  1257 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-26 19:45:34.600  1020  1257 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:45:34.600  1020  1257 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:45:34.600  1020  1257 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 19:45:34.600  3176  3247 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
,08-26 19:45:34.600  3176  3247 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-26 19:45:34.600  3176  3247 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-26 19:45:34.600  1695  1695 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-26 19:45:34.610  1020  4359 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-26 19:45:34.610  1020  4359 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-26 19:45:34.610  1020  4359 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:45:34.610  1020  4359 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:45:34.610  1020  4359 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 19:45:34.610  3176  3247 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
,08-26 19:45:34.610  3176  3247 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-26 19:45:34.610  3176  3247 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-26 19:45:34.610  1020  1032 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
08-26 19:45:34.610  1020  1032 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,08-26 19:45:34.610  1020  1032 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:45:34.610  1020  1032 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:45:34.610  1020  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-26 19:45:34.610  3176  3176 I bluedroid: get_profile_interface handsfree
,08-26 19:45:34.610  1020  1082 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-26 19:45:34.610  1020  1082 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-26 19:45:34.620  1020  1082 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:45:34.620  1020  1082 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-26 19:45:34.620  1020  1082 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 19:45:34.620  3176  3247 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
,08-26 19:45:34.620  3176  3247 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-26 19:45:34.620  3176  3247 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-26 19:45:34.620  1020  1491 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-26 19:45:34.620  1020  1491 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-26 19:45:34.620  1020  1491 W ActivityManager: userId = 0, bbcId = -10000
,08-26 19:45:34.620  1020  1491 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:45:34.620  1020  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 19:45:34.630  4713  4713 D BluetoothNotiBroadcastReceiver: onReceive
,08-26 19:45:34.630  3176  3247 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-26 19:45:34.630  3176  3247 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-26 19:45:34.630  3176  3247 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-26 19:45:34.630  3176  3247 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-26 19:45:34.630  3176  3247 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-26 19:45:34.630  3176  3247 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-26 19:45:34.630  3176  3247 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
08-26 19:45:34.630  3176  3247 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-26 19:45:34.630  3176  3247 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-26 19:45:34.630  3176  3247 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
08-26 19:45:34.630  3176  3247 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-26 19:45:34.630  3176  3247 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-26 19:45:34.630  3176  3247 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,08-26 19:45:34.630  3176  3176 E DualScoManager: Dual Sco Manager already instantiated
08-26 19:45:34.630  3176  3176 I DualScoManager: Set HeadsetServiceHelper
08-26 19:45:34.630  3176  3176 D BluetoothAtMessage: createCMTIContentObservers
,08-26 19:45:34.630  1020  1513 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
08-26 19:45:34.630  1020  1513 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 19:45:34.630  1020  1513 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 19:45:34.630  1020  1513 D SettingsProvider: selectionArgs: false
08-26 19:45:34.630  1020  1513 D SettingsProvider: selectionArgs: 1002
08-26 19:45:34.630  1020  1513 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 19:45:34.630  1020  1513 D SettingsProvider: ret = -1
,08-26 19:45:34.630  3176  7619 D HeadsetStateMachine: Enter Disconnected: -2
,08-26 19:45:34.640  3176  3176 D HeadsetService: mStartError = false
08-26 19:45:34.640  3176  3176 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@247e950f
,08-26 19:45:34.640  3176  3176 D A2dpService: Received start request. Starting profile...
08-26 19:45:34.640  3176  3176 D A2dpService: start()
08-26 19:45:34.640  3176  3176 I bluedroid: get_profile_interface avrcp
,08-26 19:45:34.640  1177  1177 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-26 19:45:34.640  1177  1177 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,08-26 19:45:34.640  3176  3176 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-26 19:45:34.640  3176  3176 D Avrcp   : Initialize Media Controller
,08-26 19:45:34.640  3176  3176 D Avrcp   : Get the Context Package Name: com.android.bluetooth
,08-26 19:45:34.640  3176  3176 E Avrcp   : getActiveSessions
08-26 19:45:34.650  3176  3176 D Avrcp   : pick active media Controller
08-26 19:45:34.650  3176  3176 D Avrcp   : Get the active Media Controller 
,08-26 19:45:34.650  3176  7619 D HeadsetStateMachine: Clear mHeadsetBrsf
,08-26 19:45:34.650  3176  7619 D HeadsetStateMachine: map size, before remove : 0
08-26 19:45:34.650  3176  7619 D HeadsetStateMachine: map size, after remove: 0
,08-26 19:45:34.650  3176  3176 I Avrcp   :  Updating now playing list upon AVRCP Start
,08-26 19:45:34.660  3176  7620 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
08-26 19:45:34.660  3176  3176 D A2dpStateMachine: make
,08-26 19:45:34.660  3176  3176 I bluedroid: get_profile_interface a2dp
08-26 19:45:34.660  3176  7622 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-26 19:45:34.660  3176  3176 E bt-btif : warning : media task started media_task_refcnt 1 
08-26 19:45:34.660  3176  3176 D A2dpService: mStartError = false
,08-26 19:45:34.660  3176  3176 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@247e950f
,08-26 19:45:34.660  3176  7621 D A2dpStateMachine: Enter Disconnected: -2
08-26 19:45:34.660  3176  3176 D HidService: Received start request. Starting profile...
08-26 19:45:34.660  3176  3176 D HidService: start()
08-26 19:45:34.660  3176  3176 I bluedroid: get_profile_interface hidhost
08-26 19:45:34.660  3176  3176 D HidService: setHidService(): set to: null
08-26 19:45:34.660  3176  3176 D HidService: mStartError = false
08-26 19:45:34.660  3176  3176 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@247e950f
08-26 19:45:34.660  3176  3176 D HeadsetStateMachine: Try to query the phonestate on bind
,08-26 19:45:34.660  1445  1454 I Telecom : BluetoothPhoneService: queryPhoneState
,08-26 19:45:34.660  1445  1445 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
,08-26 19:45:34.660  1445  1445 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
08-26 19:45:34.660  1445  1454 I Telecom : BluetoothPhoneService: Result of Message : true
,08-26 19:45:34.660  3176  3176 D HealthService: Received start request. Starting profile...
,08-26 19:45:34.660  3176  3176 D HealthService: start()
08-26 19:45:34.670  3176  3176 I bluedroid: get_profile_interface health
08-26 19:45:34.670  3176  3176 D HealthService: mStartError = false
08-26 19:45:34.670  3176  3176 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@247e950f
,08-26 19:45:34.670  3176  3176 D PanService: Received start request. Starting profile...
08-26 19:45:34.670  3176  3176 D PanService: start()
08-26 19:45:34.670  3176  3176 D BluetoothPanServiceJni: initializeNative(L110): pan
08-26 19:45:34.670  3176  3176 I bluedroid: get_profile_interface pan
08-26 19:45:34.670  3176  3176 D PanService: mStartError = false
08-26 19:45:34.670  3176  3176 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@247e950f
,08-26 19:45:34.670  3176  3176 D HeadsetStateMachine: Proxy object connected
08-26 19:45:34.670  3176  3176 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
08-26 19:45:34.670  3176  7619 D HeadsetStateMachine: Disconnected process message: 11
,08-26 19:45:34.670  3176  3176 D BluetoothMapService: Received start request. Starting profile...
08-26 19:45:34.670  3176  3176 D BluetoothMapService: start()
,08-26 19:45:34.670  3176  3176 D BluetoothMapService: mStartError = false
,08-26 19:45:34.670  3176  3176 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@247e950f
08-26 19:45:34.670  3176  3176 D HeadsetPhoneState: sendDeviceDataStateChanged
,08-26 19:45:34.670  3176  3176 D HeadsetPhoneState: Signal level : previous=0 curr=4
08-26 19:45:34.670  3176  7619 D HeadsetStateMachine: Disconnected process message: 18
,08-26 19:45:34.670  3176  3176 D SapService: Received start request. Starting profile...
08-26 19:45:34.670  3176  3176 D SapService: start()
08-26 19:45:34.670  3176  3176 D BluetoothSAPServiceJni: initializeNative(L209): sap
08-26 19:45:34.670  3176  3176 I bluedroid: get_profile_interface sap
08-26 19:45:34.670  3176  3176 D SapService: mStartError = false
,08-26 19:45:34.670  3176  3176 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@247e950f
08-26 19:45:34.670  3176  3176 E BluetoothAdapterService(612275471): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
08-26 19:45:34.670  3176  3176 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-26 19:45:34.670  3176  3176 E BluetoothAdapterService(612275471): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
08-26 19:45:34.670  3176  3176 E BluetoothAdapterService(612275471): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
08-26 19:45:34.670  3176  3176 E BluetoothAdapterService(612275471): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
08-26 19:45:34.670  3176  7619 D HeadsetStateMachine: Disconnected process message: 10
,08-26 19:45:34.670  3176  3176 E BluetoothAdapterService(612275471): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
08-26 19:45:34.670  3176  7619 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-26 19:45:34.680  3176  7619 D HeadsetStateMachine: Disconnected process message: 11
,08-26 19:45:34.680  3176  7620 D BluetoothMediaBrowser: no now playing list
08-26 19:45:34.680  3176  7620 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,08-26 19:45:34.690  3176  3176 E BluetoothAdapterService(612275471): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,08-26 19:45:34.690  3176  3176 E BluetoothAdapterService(612275471): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,08-26 19:45:34.690  3176  3247 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
08-26 19:45:34.690  3176  3247 I bluedroid: enable
,08-26 19:45:34.700  3176  3250 E bt-btif : Calling BTA_HhEnable
,08-26 19:45:34.700  3176  3250 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
,08-26 19:45:34.700  3176  3250 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
,08-26 19:45:34.700  3176  3250 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,08-26 19:45:34.700  3176  3250 D BluetoothAdapterProperties: Address is:08:EC:A9:50:75:41
,08-26 19:45:34.700  3176  3250 E BluetoothServiceJni: populateRssiValuesNative
08-26 19:45:34.700  3176  3250 I bluedroid: getModelRssiValues
08-26 19:45:34.710  3176  3250 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
,08-26 19:45:34.710  3176  3250 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-26 19:45:34.710  1020  1020 D SettingsProvider: name = bluetooth_name
,08-26 19:45:34.710  3176  3250 D BluetoothAdapterProperties: Name is: Galaxy A3
,08-26 19:45:34.710  3176  3250 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-26 19:45:34.710  3176  3250 D BluetoothAdapterProperties: Scan Mode:20
08-26 19:45:34.710  3176  3250 D BluetoothAdapterProperties: Discoverable Timeout:120
08-26 19:45:34.710  3176  3250 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EA:82
08-26 19:45:34.710  3176  3250 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:2
08-26 19:45:34.710  3176  3250 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:1
,08-26 19:45:34.710  3176  3250 E bt-btif : btif_sock_init: !radio_req && !rfc_init
08-26 19:45:34.710  3176  3250 E bt-btif : JVenable fails
,08-26 19:45:34.710  3176  3250 D bte_conf: Device ID record 1 : primary
08-26 19:45:34.710  6761  6761 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:45:34.710  3176  3250 D bte_conf:   vendorId            = 0075
08-26 19:45:34.710  3176  3250 D bte_conf:   vendorIdSource      = 0001
08-26 19:45:34.710  3176  3250 D bte_conf:   product             = 0100
08-26 19:45:34.710  3176  3250 D bte_conf:   version             = 0200
08-26 19:45:34.710  3176  3250 D bte_conf:   clientExecutableURL = 
08-26 19:45:34.710  3176  3250 D bte_conf:   serviceDescription  = 
08-26 19:45:34.710  3176  3250 D bte_conf:   documentationURL    = 
,08-26 19:45:34.720  3176  3250 D bte_conf: bte_load_did_conf no section named DID2.
08-26 19:45:34.720  3176  3250 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
08-26 19:45:34.720  3176  3250 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-26 19:45:34.720  3176  3247 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,08-26 19:45:34.720  3176  3247 D BluetoothAdapterProperties: ScanMode =  20
08-26 19:45:34.720  3176  3247 D BluetoothAdapterProperties: State =  11
,08-26 19:45:34.720  1020  1487 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-26 19:45:34.720  3176  3247 D BluetoothAdapterProperties: Setting state to 12
08-26 19:45:34.720  3176  3247 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-26 19:45:34.720  3176  3250 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-26 19:45:34.720  3176  3250 D BluetoothAdapterProperties: Scan Mode:21
08-26 19:45:34.720  3176  3250 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-26 19:45:34.720  6761  6761 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 19:45:34.720  6761  6761 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:45:34.720  6761  6761 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 19:45:34.720  6761  6761 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 19:45:34.720  6761  6761 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 19:45:34.720  6761  6761 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 19:45:34.720  6761  6761 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 19:45:34.720  6761  6761 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 19:45:34.730  1020  4358 D SettingsProvider: name = bluetooth_a2dp_sink_mode
08-26 19:45:34.730  1020  4358 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 19:45:34.730  1020  4358 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 19:45:34.730  1020  4358 D SettingsProvider: selectionArgs: false
08-26 19:45:34.730  1020  4358 D SettingsProvider: selectionArgs: 1002
08-26 19:45:34.730  1020  4358 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 19:45:34.730  1020  4358 D SettingsProvider: ret = -1
,08-26 19:45:34.730  3176  3247 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-26 19:45:34.730  3176  3247 D BluetoothAdapterService: updateAdapterState state is 12
,08-26 19:45:34.730  1020  1257 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 19:45:34.730  1020  1257 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-26 19:45:34.730  1020  1257 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:45:34.730  1020  1257 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:45:34.730  1020  1257 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 19:45:34.730  3176  3247 D BluetoothAdapterService: Autoconnection is available 
08-26 19:45:34.730  3176  3247 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
08-26 19:45:34.730  3176  3247 D BluetoothAdapterService: starting service from this receiver
,08-26 19:45:34.730  1020  1468 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-26 19:45:34.730  1020  1468 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-26 19:45:34.740  4713  4724 D BluetoothMap: onBluetoothStateChange: up=true
,08-26 19:45:34.740  6761  6761 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 19:45:34.740  1020  1468 W ActivityManager: userId = 0, bbcId = -10000
,08-26 19:45:34.740  1020  1468 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:45:34.740  1020  1468 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 19:45:34.740  3176  3176 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
08-26 19:45:34.740  3176  3176 I BluetoothPbapService: Handler(): got msg=1
,08-26 19:45:34.740  3176  3247 I BluetoothAdapterState: Entering On State from state = 11
,08-26 19:45:34.740  1020  1257 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-26 19:45:34.740  6761  6761 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 19:45:34.740  6761  6761 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:45:34.740  6761  6761 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 19:45:34.740  6761  6761 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 19:45:34.740  6761  6761 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 19:45:34.740  6761  6761 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 19:45:34.740  6761  6761 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 19:45:34.740  6761  6761 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 19:45:34.740  1020  1051 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
08-26 19:45:34.740  1020  1051 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-26 19:45:34.750  1020  1051 W ActivityManager: userId = 0, bbcId = -10000
,08-26 19:45:34.750  1020  1051 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:45:34.750  6761  6761 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 19:45:34.750  1020  1051 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-26 19:45:34.750  6761  6761 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 19:45:34.750  1020  1051 D BluetoothPan: Binding service...
,08-26 19:45:34.750  1020  1051 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-26 19:45:34.750  3176  7628 V BluetoothPbapService: PBAP Service initSocket try: 0
,08-26 19:45:34.750  1020  1051 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-26 19:45:34.750  1445  7102 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-26 19:45:34.750  1020  1051 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-26 19:45:34.750  1020  1051 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-26 19:45:34.750  1020  1051 W ActivityManager: userId = 0, bbcId = -10000
,08-26 19:45:34.750  1020  1051 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:45:34.750  1020  1051 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
08-26 19:45:34.750  3176  7628 D BluetoothSocket: bindListen(): myUserId = 0
08-26 19:45:34.750  3176  7628 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback,
08-26 19:45:34.750  1445  7102 E BluetoothHeadset: BluetoothHeadset service is binded
08-26 19:45:34.760  4713  4733 D Bluetoothsap: onBluetoothStateChange: up=true
08-26 19:45:34.760  4713  4733 D Bluetoothsap: Binding service...
,08-26 19:45:34.760  4713  4733 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,08-26 19:45:34.760  3176  7628 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[80]}
,08-26 19:45:34.760  1020  1020 D BluetoothPan: BluetoothPAN Proxy object connected
,08-26 19:45:34.760  3176  7628 D BluetoothSocket: bindListen(), new LocalSocket 
08-26 19:45:34.760  3176  7628 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-26 19:45:34.760  3176  7628 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3c2c6dd8
08-26 19:45:34.760  4713  4713 D BluetoothMap: Proxy object connected
08-26 19:45:34.760  4713  4713 D MapProfile: Bluetooth service connected
08-26 19:45:34.760  4713  4713 D BluetoothMap: getConnectedDevices()
08-26 19:45:34.760  1020  1051 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
08-26 19:45:34.760  1020  1051 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
08-26 19:45:34.760  3176  7628 D BluetoothSocket: channel: 19
08-26 19:45:34.760  3176  7628 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,08-26 19:45:34.760  1020  1051 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:45:34.760  1020  1051 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:45:34.760  1020  1051 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-26 19:45:34.760  4713  4733 D Bluetoothsap: bindService called to Bluetooth SAP Service
,08-26 19:45:34.770  1455  1793 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 19:45:34.770  1455  1793 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-26 19:45:34.770  1806  2237 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 19:45:34.770  1806  2237 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-26 19:45:34.770  4713  4713 D Bluetoothsap: BluetoothSAP Proxy object connected
08-26 19:45:34.770  1020  1051 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-26 19:45:34.770  1020  1051 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
08-26 19:45:34.770  4713  4713 D SapProfile: Bluetooth service connected
08-26 19:45:34.770  1020  1051 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-26 19:45:34.770  4713  4713 D Bluetoothsap: getConnectedDevices()
08-26 19:45:34.770  1020  1051 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-26 19:45:34.770  1177  2063 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-26 19:45:34.770  1177  2063 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-26 19:45:34.770  4713  7060 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-26 19:45:34.770  1020  1020 D BluetoothA2dp: Proxy object connected
,08-26 19:45:34.770  1020  1051 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
,08-26 19:45:34.770  1020  1051 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-26 19:45:34.770  1020  1051 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:45:34.770  1020  1051 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:45:34.770  1020  1051 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-26 19:45:34.770  4713  4733 D BluetoothPbap: onBluetoothStateChange: up=true
,08-26 19:45:34.770  4713  4713 D BluetoothInputDevice: Proxy object connected
08-26 19:45:34.770  4713  4713 D HidProfile: Bluetooth service connected
,08-26 19:45:34.770  1020  1051 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
08-26 19:45:34.770  1020  1051 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-26 19:45:34.780  1020  1051 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:45:34.780  1020  1051 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:45:34.780  1020  1051 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-26 19:45:34.780  1445  1454 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 19:45:34.780  1445  1454 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-26 19:45:34.780  1472  1788 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-26 19:45:34.780  1020  1051 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-26 19:45:34.780  1020  1051 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-26 19:45:34.780  1020  1051 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:45:34.780  1020  1051 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:45:34.780  1020  1051 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,08-26 19:45:34.780  1472  1788 E BluetoothHeadset: BluetoothHeadset service is binded
08-26 19:45:34.780  4713  4713 D BluetoothPbap: Proxy object connected
08-26 19:45:34.780  4713  4713 D PbapServerProfile: Bluetooth service connected
,08-26 19:45:34.780  4713  4724 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-26 19:45:34.780  1020  1051 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-26 19:45:34.780  1020  1051 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-26 19:45:34.780  1020  1051 W ActivityManager: userId = 0, bbcId = -10000
,08-26 19:45:34.780  1020  1051 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:45:34.780  1020  1051 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-26 19:45:34.790  4713  4713 D HeadsetProfile: Bluetooth service connected
08-26 19:45:34.790  4713  4724 E BluetoothHeadset: BluetoothHeadset service is binded
,08-26 19:45:34.790  1445  7102 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-26 19:45:34.790  1020  1051 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-26 19:45:34.790  1020  1051 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-26 19:45:34.790  1020  1051 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:45:34.790  1020  1051 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:45:34.790  1020  1051 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
08-26 19:45:34.790  1445  7102 E BluetoothHeadset: BluetoothHeadset service is binded
,08-26 19:45:34.790  1020  1051 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
08-26 19:45:34.790  1020  1051 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-26 19:45:34.790  1020  1051 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
08-26 19:45:34.790  1020  1051 E BluetoothHeadset: BluetoothHeadset service is binded
08-26 19:45:34.790  3176  3184 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-26 19:45:34.790  3176  3184 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-26 19:45:34.790  1020  1051 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-26 19:45:34.790  1020  1051 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-26 19:45:34.790  1020  1051 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:45:34.790  1020  1051 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-26 19:45:34.790  1020  1051 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 19:45:34.800  1020  1051 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 19:45:34.800  1020  1051 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-26 19:45:34.800  3176  3176 D BluetoothA2dp: Proxy object connected
08-26 19:45:34.800  3176  3176 D BluetoothAdapterService: Bluetooth A2dp source service connected
08-26 19:45:34.800  7085  7097 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 19:45:34.800  7085  7097 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-26 19:45:34.800  1445  7102 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-26 19:45:34.800  1020  1051 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-26 19:45:34.800  1020  1051 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-26 19:45:34.800  1020  1051 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:45:34.800  1020  1051 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:45:34.800  1020  1051 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-26 19:45:34.800  1445  7102 E BluetoothHeadset: BluetoothHeadset service is binded
,08-26 19:45:34.800  3176  3310 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 19:45:34.800  3176  3310 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-26 19:45:34.800  4713  7060 D BluetoothPan: Binding service...
,08-26 19:45:34.800  1020  1051 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
,08-26 19:45:34.800  1020  1051 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-26 19:45:34.800  1020  1051 W ActivityManager: userId = 0, bbcId = -10000
,08-26 19:45:34.800  1020  1051 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:45:34.800  1020  1051 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-26 19:45:34.800  4713  4713 D BluetoothPan: BluetoothPAN Proxy object connected
,08-26 19:45:34.800  6761  6774 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 19:45:34.800  6761  6774 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-26 19:45:34.800  1472  2676 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-26 19:45:34.800  1472  2676 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-26 19:45:34.800  4713  4713 D PanProfile: Bluetooth service connected
08-26 19:45:34.800  4713  4724 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 19:45:34.800  4713  4724 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-26 19:45:34.810  4713  4733 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-26 19:45:34.810  4713  4733 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-26 19:45:34.810  1020  1051 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-26 19:45:34.810  1020  1051 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-26 19:45:34.810  1020  1051 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:45:34.810  1020  1051 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:45:34.810  1020  1051 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-26 19:45:34.810  1695  2225 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 19:45:34.810  4713  4713 D BluetoothA2dp: Proxy object connected
08-26 19:45:34.810  4713  4713 D A2dpProfile: Bluetooth service connected
,08-26 19:45:34.810  1695  2225 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-26 19:45:34.810  1020  1051 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
08-26 19:45:34.810  1020  1051 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-26 19:45:34.810  1020  1020 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-26 19:45:34.810  1020  1020 I InputMethodManagerService: [BT Setting State] State =12
08-26 19:45:34.810  1020  1020 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-26 19:45:34.820  1445  1445 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@1e286332, true,
08-26 19:45:34.820  1177  1177 D BluetoothTile:  onBluetoothStateChange:
,08-26 19:45:34.820  1177  1177 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-26 19:45:34.820  1177  1177 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-26 19:45:34.820  1879  1879 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
08-26 19:45:34.820  1177  1177 D BluetoothTile:  getBluetoothState : 12
,08-26 19:45:34.820  1445  1445 D BluetoothHeadset: registerMessageListener
,08-26 19:45:34.830  4713  4713 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-26 19:45:34.830  1177  1784 D BluetoothTile:  handleUpdatestate:false name:null
,08-26 19:45:34.830  6761  6761 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 19:45:34.830  1020  3320 D SSRM:n  : SIOP:: AP = 390
,08-26 19:45:34.830  6761  6761 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 19:45:34.830  3176  3309 D HeadsetService: registerMessageListener
,08-26 19:45:34.830  4713  4713 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
08-26 19:45:34.830  4713  4713 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
08-26 19:45:34.830  4713  4713 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
08-26 19:45:34.830  4713  4713 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,08-26 19:45:34.840  1177  1784 D BluetoothTile:  handleUpdatestate:false name:null
,08-26 19:45:34.840  3176  3309 D HeadsetService: registerMessageListener
,08-26 19:45:34.840  1445  1445 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
08-26 19:45:34.840  1445  1445 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-26 19:45:34.840  3176  7619 D HeadsetStateMachine: Disconnected process message: 70
08-26 19:45:34.840  3176  7619 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@3572c531
,08-26 19:45:34.840  1445  1445 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
08-26 19:45:34.840  1445  1445 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
,08-26 19:45:34.840  1445  1445 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
08-26 19:45:34.840  3176  7629 D BluetoothMapMasInstance: set MAP SDP message type : 1
,08-26 19:45:34.840  1020  4267 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-26 19:45:34.840  1020  4266 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,08-26 19:45:34.850  1177  1784 D BluetoothTile:  handleUpdatestate:false name:null
,08-26 19:45:34.850  3176  7619 D HeadsetStateMachine: Disconnected process message: 9
08-26 19:45:34.850  3176  7619 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,08-26 19:45:34.850  1177  1177 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-26 19:45:34.850   283   693 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
,08-26 19:45:34.850   283   693 V voice   : voice_set_parameters: enter: A2dpSuspended=false
,08-26 19:45:34.850   283   693 V voice   : voice_set_parameters: exit with code(-2)
08-26 19:45:34.850  3176  7629 D BluetoothSocket: bindListen(): myUserId = 0
08-26 19:45:34.850  3176  7629 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 19:45:34.850   283   693 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
08-26 19:45:34.850   283   693 V msm8974_platform: platform_set_parameters: exit with code(-2)
08-26 19:45:34.850   283   693 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
08-26 19:45:34.850   283   693 V audio_hw_primary: adev_set_parameters: exit
,08-26 19:45:34.850  3176  7619 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
08-26 19:45:34.850  3176  7629 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[82]}
08-26 19:45:34.850  3176  7629 D BluetoothSocket: bindListen(), new LocalSocket 
08-26 19:45:34.850  3176  7629 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-26 19:45:34.850  3176  7629 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2ed91416
,08-26 19:45:34.850  3176  7629 D BluetoothSocket: channel: 5
,08-26 19:45:34.860  4713  4713 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-26 19:45:34.860  1020  1513 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-26 19:45:34.860  1020  1513 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-26 19:45:34.860  1020  1513 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:45:34.860  1020  1513 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-26 19:45:34.860  1020  1513 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-26 19:45:34.860  1695  1695 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-26 19:45:34.870  4713  4713 D DockEventReceiver: finishStartingService: stopping service
,08-26 19:45:34.870  4713  4713 D BluetoothNotiBroadcastReceiver: onReceive
,08-26 19:45:34.870  1177  1177 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-26 19:45:34.870  1177  1177 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,08-26 19:45:34.880  3176  3176 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@247e950f
08-26 19:45:34.880  3176  3176 D BtConfig.SecureMode: isSecureModeOn:false
,08-26 19:45:34.880  1020  1468 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-26 19:45:34.880  1020  1468 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,08-26 19:45:34.880  1020  1468 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:45:34.880  1020  1468 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:45:34.880  1020  1468 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 19:45:34.900  1020  1033 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-26 19:45:34.900  3176  7635 D BluetoothSocket: bindListen(): myUserId = 0
,08-26 19:45:34.900  3176  7635 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-26 19:45:34.910  3176  7635 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[86]}
08-26 19:45:34.910  3176  7635 D BluetoothSocket: bindListen(), new LocalSocket 
08-26 19:45:34.910  3176  7635 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-26 19:45:34.910  3176  7635 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@104a5ba2
,08-26 19:45:34.910  3176  7635 D BluetoothSocket: channel: 12
08-26 19:45:34.910  3176  7635 I BtOppRfcommListener: Accept thread started.
,08-26 19:45:35.190  1020  3338 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-26 19:45:36.140  1020  4266 I ActivityManager: Killing 7206:com.sec.pcw.device/1000 (adj 15): empty #21
,08-26 19:45:36.210  1020  4359 I ActivityManager: Killing 7223:com.sec.android.cloudagent/u0a1 (adj 15): empty #21
,08-26 19:45:36.940   334   334 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 19:45:37.400   295   295 E SMD     : DCD OFF
,08-26 19:45:37.540  6761  6987 D BluetoothAdapter: disable()
,08-26 19:45:37.540  1020  1513 D SettingsProvider: name = bluetooth_on
,08-26 19:45:37.540  3176  3247 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
,08-26 19:45:37.550  3176  3247 D BluetoothAdapterProperties: Setting state to 13
08-26 19:45:37.550  3176  3247 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-26 19:45:37.550  3176  3247 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-26 19:45:37.550  3176  3247 D BluetoothAdapterService: updateAdapterState state is 13
08-26 19:45:37.550  1020  1468 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 19:45:37.550  1020  1468 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-26 19:45:37.550  1020  1468 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:45:37.550  1020  1468 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:45:37.550  1020  1468 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 19:45:37.550  3176  3247 D BluetoothAdapterService: Autoconnection is available 
08-26 19:45:37.550  3176  3247 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
08-26 19:45:37.550  3176  3247 D BluetoothAdapterService: terminating service from this receiver
,08-26 19:45:37.550  1020  4359 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-26 19:45:37.550  3176  3176 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
08-26 19:45:37.550  1020  4359 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:45:37.550  1020  4359 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:45:37.550  1020  4359 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 19:45:37.550  3176  3176 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@18e09033, channel: 19, state: LISTENING
08-26 19:45:37.550  3176  3176 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@18e09033, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3c2c6dd8, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@3dff1ff0mSocket: android.net.LocalSocket@4fbe969 impl:android.net.LocalSocketImpl@10968fee fd:FileDescriptor[80]
08-26 19:45:37.550  3176  3176 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@4fbe969 impl:android.net.LocalSocketImpl@10968fee fd:FileDescriptor[80]
,08-26 19:45:37.550  3176  3247 D BluetoothAdapterProperties: onBluetoothDisable()
,08-26 19:45:37.550  3176  3247 D BluetoothAdapterProperties: mDiscovering is false
,08-26 19:45:37.560  1020  1508 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-26 19:45:37.560  3176  3247 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,08-26 19:45:37.560  4713  4713 D BluetoothPbap: Proxy object disconnected
08-26 19:45:37.560  4713  4713 D PbapServerProfile: Bluetooth service disconnected
,08-26 19:45:37.570  3176  3250 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,08-26 19:45:37.570  3176  3250 D BluetoothAdapterProperties: Scan Mode:20
,08-26 19:45:37.570  6761  6761 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 19:45:37.570  6761  6761 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 19:45:37.570  6761  6761 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:45:37.570  6761  6761 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 19:45:37.570  6761  6761 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 19:45:37.570  6761  6761 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 19:45:37.570  6761  6761 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
,08-26 19:45:37.570  6761  6761 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 19:45:37.570  6761  6761 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 19:45:37.570  3176  3247 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-26 19:45:37.570  3176  3247 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,08-26 19:45:37.570  3176  3247 E bt-btif : cmd socket is not created
08-26 19:45:37.570  3176  7635 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-26 19:45:37.570  6761  6761 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 19:45:37.570  6761  6761 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 19:45:37.570  3176  3247 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-26 19:45:37.570  3176  3251 W bt-btif : bta_dm_disable_bt BTA_DISABLE_DELAY set to 200 ms
,08-26 19:45:37.580  6761  6761 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 19:45:37.580  6761  6761 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 19:45:37.580  6761  6761 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:45:37.580  6761  6761 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 19:45:37.580  6761  6761 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 19:45:37.580  6761  6761 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 19:45:37.580  6761  6761 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 19:45:37.580  6761  6761 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 19:45:37.580  6761  6761 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 19:45:37.580  6761  6761 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 19:45:37.580  6761  6761 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 19:45:37.590  3176  3251 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 19:45:37.590  3176  3251 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 19:45:37.590  3176  3251 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-26 19:45:37.590  3176  3251 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 19:45:37.590  3176  3251 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 19:45:37.590  3176  3251 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-26 19:45:37.600  1020  1020 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-26 19:45:37.600  1020  1020 I InputMethodManagerService: [BT Setting State] State =13
,08-26 19:45:37.600  1177  1177 D BluetoothTile:  onBluetoothStateChange:
,08-26 19:45:37.610  1177  1177 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-26 19:45:37.610  1177  1784 D BluetoothTile:  handleUpdatestate:false name:null
,08-26 19:45:37.610  1177  1784 D BluetoothTile:  handleUpdatestate:false name:null
,08-26 19:45:37.610  1177  1177 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-26 19:45:37.610  1177  1177 D BluetoothTile:  getBluetoothState : 13
,08-26 19:45:37.610  1177  1784 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-26 19:45:37.620  1020  1491 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-26 19:45:37.620  1020  1508 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-26 19:45:37.620  1177  1177 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-26 19:45:37.620  4713  4713 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
08-26 19:45:37.620  1879  1879 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-26 19:45:37.630  3176  3176 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@24ce4b1c, channel: 5, state: LISTENING
08-26 19:45:37.630  3176  3176 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@24ce4b1c, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2ed91416, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@3a60b325mSocket: android.net.LocalSocket@55fbcfa impl:android.net.LocalSocketImpl@18b3d2ab fd:FileDescriptor[82]
08-26 19:45:37.630  3176  3176 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@55fbcfa impl:android.net.LocalSocketImpl@18b3d2ab fd:FileDescriptor[82]
,08-26 19:45:37.630  3176  3176 I BtOppRfcommListener: stopping Accept Thread
08-26 19:45:37.630  3176  3176 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2a02fd08, channel: 12, state: LISTENING
08-26 19:45:37.630  3176  3176 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@2a02fd08, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@104a5ba2, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@88e5ca1mSocket: android.net.LocalSocket@a5caec6 impl:android.net.LocalSocketImpl@19daee87 fd:FileDescriptor[86]
08-26 19:45:37.630  3176  3176 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@a5caec6 impl:android.net.LocalSocketImpl@19daee87 fd:FileDescriptor[86]
,08-26 19:45:37.630  3176  7635 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-26 19:45:37.630  6761  6761 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:45:37.630  3176  3176 V BluetoothOppManager: cleanUp...
,08-26 19:45:37.630  4713  4713 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-26 19:45:37.640  1020  4359 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-26 19:45:37.640  1020  4359 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-26 19:45:37.640  1020  4359 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:45:37.640  1020  4359 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:45:37.640  1020  4359 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-26 19:45:37.640  6761  6761 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 19:45:37.640  1695  1695 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-26 19:45:37.650  4713  4713 D DockEventReceiver: finishStartingService: stopping service
,08-26 19:45:37.650  4713  4713 D BluetoothNotiBroadcastReceiver: onReceive
,08-26 19:45:37.650  1177  1177 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-26 19:45:37.650  1177  1177 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,08-26 19:45:37.780  3176  3247 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,08-26 19:45:37.780  3176  3247 D BtConfig.SecureMode: isSecureModeOn:false
08-26 19:45:37.780  3176  3247 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
08-26 19:45:37.780  3176  3247 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.gatt.GattService
08-26 19:45:37.780  1020  1258 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-26 19:45:37.780  3176  3247 W BluetoothAdapterService: Skipping to stop Quiet mode profile com.android.bluetooth.gatt.GattService
08-26 19:45:37.780  1020  1258 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
08-26 19:45:37.780  3176  3247 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
,08-26 19:45:37.780  3176  3247 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-26 19:45:37.780  3176  3247 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
08-26 19:45:37.780  1020  1258 W ActivityManager: userId = 0, bbcId = -10000
,08-26 19:45:37.780  1020  1258 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-26 19:45:37.780  1020  1258 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 19:45:37.780  3176  3247 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService,
08-26 19:45:37.780  3176  3247 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,08-26 19:45:37.780  3176  3247 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-26 19:45:37.780  1020  4357 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 19:45:37.790  1020  4357 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-26 19:45:37.790  1020  4357 W ActivityManager: userId = 0, bbcId = -10000,
08-26 19:45:37.790  1020  4357 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-26 19:45:37.790  1020  4357 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-26 19:45:37.790  3176  3247 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
08-26 19:45:37.790  3176  3247 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-26 19:45:37.790  3176  3247 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-26 19:45:37.790  1020  1491 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 19:45:37.790  1020  1491 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-26 19:45:37.790  1020  1491 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:45:37.790  3176  3176 D HeadsetService: Received stop request...Stopping profile...
08-26 19:45:37.790  1020  1491 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-26 19:45:37.790  1020  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 19:45:37.790  3176  3247 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
,08-26 19:45:37.790  3176  3247 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService,
08-26 19:45:37.790  3176  3247 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
08-26 19:45:37.790  1020  1082 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth,
08-26 19:45:37.790  1020  1082 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-26 19:45:37.790  1020  1082 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:45:37.790  1020  1082 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-26 19:45:37.790  1020  1082 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 19:45:37.800  3176  3247 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
08-26 19:45:37.800  3176  3247 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-26 19:45:37.800  3176  3247 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-26 19:45:37.800  3176  3176 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@247e950f,
,08-26 19:45:37.800  1020  1020 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-26 19:45:37.800  4713  4713 D HeadsetProfile: Bluetooth service disconnected
,08-26 19:45:37.800  1020  4359 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-26 19:45:37.800  1020  4359 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-26 19:45:37.800  3176  3176 D A2dpService: Received stop request...Stopping profile...
08-26 19:45:37.800  1020  4359 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:45:37.800  1020  4359 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:45:37.800  1020  4359 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 19:45:37.800  3176  7621 D A2dpStateMachine: Exit Disconnected: -1
,08-26 19:45:37.810  3176  3247 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
08-26 19:45:37.810  3176  3247 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-26 19:45:37.810  3176  3247 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-26 19:45:37.810  1020  4358 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-26 19:45:37.810  1020  4358 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-26 19:45:37.810  3176  3176 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@247e950f
,08-26 19:45:37.810  1020  4358 W ActivityManager: userId = 0, bbcId = -10000
,08-26 19:45:37.810  1020  4358 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:45:37.810  1020  4358 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 19:45:37.810  1020  1020 D BluetoothA2dp: Proxy object disconnected
08-26 19:45:37.810  1020  1020 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,08-26 19:45:37.810  3176  3176 D HidService: Received stop request...Stopping profile...
08-26 19:45:37.810  3176  3247 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
08-26 19:45:37.810  3176  3176 D HidService: Stopping Bluetooth HidService
08-26 19:45:37.810  3176  3176 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-26 19:45:37.810  3176  3176 W bt-btif : cleanup: HH disabling or disabled already, status = 0
08-26 19:45:37.810  3176  3247 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-26 19:45:37.810  3176  3176 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-26 19:45:37.810  3176  3176 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@247e950f
08-26 19:45:37.810  3176  3247 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-26 19:45:37.810  1020  1508 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 19:45:37.810  1020  1508 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-26 19:45:37.820  4713  4713 D BluetoothA2dp: Proxy object disconnected
08-26 19:45:37.820  4713  4713 D A2dpProfile: Bluetooth service disconnected
08-26 19:45:37.820  3176  3176 D HealthService: Received stop request...Stopping profile...
,08-26 19:45:37.820  3176  3176 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@247e950f
08-26 19:45:37.820  1020  1508 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:45:37.820  1020  1508 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:45:37.820  1020  1508 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 19:45:37.820  3176  3247 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-26 19:45:37.820  3176  3247 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-26 19:45:37.820  3176  3247 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-26 19:45:37.820  3176  3247 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-26 19:45:37.820  3176  3247 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,08-26 19:45:37.820  4713  4713 D BluetoothInputDevice: Proxy object disconnected
08-26 19:45:37.820  4713  4713 D HidProfile: Bluetooth service disconnected
,08-26 19:45:37.820  3176  3247 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-26 19:45:37.820  3176  3247 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
08-26 19:45:37.820  3176  3247 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-26 19:45:37.820  3176  3247 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-26 19:45:37.820  3176  3247 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
08-26 19:45:37.820  3176  3247 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-26 19:45:37.820  3176  3247 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-26 19:45:37.820  3176  3247 D BluetoothAdapterState: Stopping profile services that were post enabled
,08-26 19:45:37.820  3176  3176 E BluetoothAdapterService(612275471): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
,08-26 19:45:37.820  3176  3176 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-26 19:45:37.820  3176  3176 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,08-26 19:45:37.820  3176  3176 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,08-26 19:45:37.820  3176  3176 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-26 19:45:37.830  3176  3176 D PanService: Received stop request...Stopping profile...
,08-26 19:45:37.830  3176  3176 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@247e950f
08-26 19:45:37.830  1020  1020 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-26 19:45:37.830  3176  3176 E BluetoothAdapterService(612275471): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
08-26 19:45:37.830  3176  3176 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-26 19:45:37.830  3176  3176 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,08-26 19:45:37.830  3176  3176 D BluetoothMapService: Received stop request...Stopping profile...
,08-26 19:45:37.830  3176  3176 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@247e950f
,08-26 19:45:37.830  3176  3176 D BluetoothA2dp: Proxy object disconnected
,08-26 19:45:37.830  3176  3176 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
,08-26 19:45:37.830  3176  7622 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating,
08-26 19:45:37.840  3176  3176 I GKI_LINUX: GKI_exit_task 2 done
08-26 19:45:37.840  3176  3176 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
,08-26 19:45:37.840  3176  3176 E BluetoothAdapterService(612275471): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
08-26 19:45:37.840  3176  3176 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-26 19:45:37.840  3176  3176 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-26 19:45:37.840  4713  4713 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-26 19:45:37.840  3176  3176 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-26 19:45:37.840  4713  4713 D PanProfile: Bluetooth service disconnected
,08-26 19:45:37.840  3176  3176 E BluetoothAdapterService(612275471): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
08-26 19:45:37.840  4713  4713 D BluetoothMap: Proxy object disconnected
08-26 19:45:37.840  4713  4713 D MapProfile: Bluetooth service disconnected
,08-26 19:45:37.840  3176  3176 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-26 19:45:37.840  3176  3176 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-26 19:45:37.840  3176  3176 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
,08-26 19:45:37.840  3176  3176 D SapService: Received stop request...Stopping profile...
08-26 19:45:37.840  3176  3176 D SapService: Stopping Bluetooth SapService
,08-26 19:45:37.840  3176  3176 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@247e950f
,08-26 19:45:37.840  3176  3176 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,08-26 19:45:37.840  3176  3176 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-26 19:45:37.840  4713  4713 D Bluetoothsap: BluetoothSAP Proxy object disconnected
,08-26 19:45:37.840  4713  4713 D SapProfile: Bluetooth service disconnected
,08-26 19:45:37.840  3176  3176 E BluetoothAdapterService(612275471): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
08-26 19:45:37.840  3176  3176 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-26 19:45:37.840  3176  3176 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-26 19:45:37.840  3176  3176 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
,08-26 19:45:37.840  3176  3176 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-26 19:45:37.840  3176  3176 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-26 19:45:37.840  3176  3176 E BluetoothAdapterService(612275471): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
08-26 19:45:37.840  3176  3176 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-26 19:45:37.840  3176  3176 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-26 19:45:37.840  3176  3176 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
08-26 19:45:37.840  3176  3176 E BluetoothAdapterService(612275471): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
08-26 19:45:37.840  3176  3176 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
,08-26 19:45:37.840  3176  3176 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
08-26 19:45:37.840  3176  3176 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,08-26 19:45:37.850  3176  3247 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
,08-26 19:45:37.850  3176  3247 D BluetoothAdapterProperties: Setting state to 10
08-26 19:45:37.850  3176  3247 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
,08-26 19:45:37.850  3176  3247 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-26 19:45:37.850  3176  3247 D BluetoothAdapterService: updateAdapterState state is 10
,08-26 19:45:37.850  4713  7060 D BluetoothMap: onBluetoothStateChange: up=false
,08-26 19:45:37.850  3176  3247 D BluetoothAdapterService: Autoconnection is available 
08-26 19:45:37.850  3176  3247 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
,08-26 19:45:37.850  3176  3247 I BluetoothAdapterState: Entering OffState
,08-26 19:45:37.850  4713  4733 D Bluetoothsap: onBluetoothStateChange: up=false
,08-26 19:45:37.850  4713  4733 D Bluetoothsap: Unbinding service...
,08-26 19:45:37.850  1455  1793 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-26 19:45:37.850  1455  1793 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-26 19:45:37.850  1806  1824 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-26 19:45:37.850  1806  1824 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-26 19:45:37.850  1020  1051 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-26 19:45:37.860  1177  1192 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-26 19:45:37.860  1177  1192 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-26 19:45:37.860  4713  4724 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-26 19:45:37.860  4713  7060 D BluetoothPbap: onBluetoothStateChange: up=false
,08-26 19:45:37.860  1445  1454 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-26 19:45:37.860  1445  1454 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-26 19:45:37.860  3176  3185 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-26 19:45:37.860  1020  1051 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-26 19:45:37.860  1020  1051 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-26 19:45:37.860  7085  7095 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-26 19:45:37.860  7085  7095 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-26 19:45:37.860  3176  7630 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-26 19:45:37.860  3176  7630 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-26 19:45:37.860  6761  6774 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-26 19:45:37.870  6761  6774 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-26 19:45:37.870  6761  6774 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
,08-26 19:45:37.870  6761  6774 D BluetoothLeAdvertiser: Exit stop advertising
08-26 19:45:37.870  6761  6774 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
,08-26 19:45:37.870  6761  6774 D BluetoothLeScanner: Exiting stopAllScan
,08-26 19:45:37.870  1472  1488 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-26 19:45:37.870  1472  1488 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-26 19:45:37.870  4713  7060 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-26 19:45:37.870  4713  7060 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-26 19:45:37.870  4713  4733 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-26 19:45:37.870  1695  1710 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-26 19:45:37.870  1695  1710 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-26 19:45:37.870  1020  1020 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED,
08-26 19:45:37.870  1020  1020 I InputMethodManagerService: [BT Setting State] State =10
08-26 19:45:37.870  1020  1020 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-26 19:45:37.880  1177  1177 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-26 19:45:37.880  1177  1177 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-26 19:45:37.880  1177  1177 D BluetoothTile:  getBluetoothState : 10
,08-26 19:45:37.880  1879  1879 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-26 19:45:37.880  1020  1257 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-26 19:45:37.880  1020  4359 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-26 19:45:37.890  1177  1177 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
08-26 19:45:37.890  4713  4713 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-26 19:45:37.890  6761  6761 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 19:45:37.890  6761  6761 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 19:45:37.890  4713  4713 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-26 19:45:37.890  1020  1468 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-26 19:45:37.890  1020  1468 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-26 19:45:37.890  1020  1468 W ActivityManager: userId = 0, bbcId = -10000
,08-26 19:45:37.890  1020  1468 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-26 19:45:37.890  1020  1468 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-26 19:45:37.900  1695  1695 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-26 19:45:37.900  4713  4713 D DockEventReceiver: finishStartingService: stopping service
,08-26 19:45:37.910  4713  4713 D BluetoothNotiBroadcastReceiver: onReceive
,08-26 19:45:37.910  1177  1177 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-26 19:45:37.910  1177  1177 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,08-26 19:45:37.940   334   334 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 19:45:38.450  1020  1487 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 19:45:38.450  1020  1487 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4290, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,08-26 19:45:38.450  1020  1487 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,08-26 19:45:38.450  1020  1487 D BatteryService: stay LED for charging
08-26 19:45:38.450  1020  1020 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 19:45:38.450  1020  1020 I MotionRecognitionService: Plugged
,08-26 19:45:38.450  1020  1020 I MotionRecognitionService: mGripSensorEnabled= false
,08-26 19:45:38.460  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
08-26 19:45:38.460  1425  1425 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-26 19:45:38.460  1177  1177 D KeyguardUpdateMonitor: handleBatteryUpdate
08-26 19:45:38.460  1425  1425 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-26 19:45:38.480  1177  1177 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-26 19:45:38.480  1177  1177 D SViewCoverView: level :100 plugged : 2
,08-26 19:45:38.490  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 19:45:38.490  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 19:45:38.490  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 19:45:38.940   334   334 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 19:45:39.940   334   334 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 19:45:40.390   295   295 E SMD     : DCD OFF
,08-26 19:45:40.550  6761  6987 D io.jxcore.node.ConnectivityMonitor: stop
,08-26 19:45:40.550  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 19:45:40.950   334   334 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 19:45:41.940   334   334 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,08-26 19:45:42.560  1020  1100 V AlarmManager: waitForAlarm result :4
,08-26 19:45:42.570   278  1002 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-26 19:45:42.570   278  1002 D Netd    : getNetworkForDns: using netid 0 for uid 10011
,08-26 19:45:42.600  1020  1047 W ActivityManager: userId = 0, bbcId = -10000
,08-26 19:45:42.600  1020  1047 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 19:45:42.600  1020  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,08-26 19:45:43.390   295   295 E SMD     : DCD OFF
,08-26 19:45:43.550  6761  6987 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-26 19:45:43.550  6761  6987 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@19dbfd18 added. We now have 6 listener(s)
08-26 19:45:43.550  6761  6987 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 19:45:43.550  6761  6987 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-26 19:45:43.550  6761  6987 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@22584371 added. We now have 7 listener(s)
08-26 19:45:43.550  6761  6987 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 19:45:43.550  6761  6987 I System.out: IsBluetoothEnabled
,08-26 19:45:43.550  6761  6987 D BluetoothAdapter: disable()
,08-26 19:45:43.560  1020  1491 E BluetoothManagerService: Bluetooth is already disabled. DO NOT disable again.
,08-26 19:45:43.560  6761  6987 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 19:45:43.560  6761  6987 D BluetoothAdapter: enable()
,08-26 19:45:43.560  1020  1468 W ActivityManager: Permission Denial: getCurrentUser() from pid=6761, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
,08-26 19:45:43.570  1020  1468 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
08-26 19:45:43.570  1020  1468 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6761, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
08-26 19:45:43.570  1020  1468 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-26 19:45:43.570  1020  1468 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2256)
08-26 19:45:43.570  1020  1468 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:688)
08-26 19:45:43.570  1020  1468 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
08-26 19:45:43.570  1020  1468 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-26 19:45:43.570  1020  1468 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-26 19:45:43.570  1020  1468 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-26 19:45:43.570  1020  1468 D SettingsProvider: name = bluetooth_on,
,08-26 19:45:43.580  1020  1051 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-26 19:45:43.580  1020  1051 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-26 19:45:43.590  1020  1051 D SecContentProvider: uri = 3 selection = isBluetoothEnabled,
,08-26 19:45:43.590  3176  3247 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
08-26 19:45:43.590  3176  3247 D BluetoothAdapterProperties: Setting state to 11
08-26 19:45:43.590  3176  3247 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-26 19:45:43.590  3176  3247 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,08-26 19:45:43.590  3176  3247 D BluetoothAdapterService: updateAdapterState state is 11
08-26 19:45:43.590  3176  3247 D BluetoothAdapterService: Autoconnection is available 
08-26 19:45:43.590  3176  3247 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
,08-26 19:45:43.590  3176  3247 D BtConfig.SecureMode: isSecureModeOn:false
08-26 19:45:43.590  3176  3247 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-26 19:45:43.590  3176  3247 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.gatt.GattService, state= 12
08-26 19:45:43.590  3176  3247 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-26 19:45:43.590  3176  3247 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hfp.HeadsetService, state= 10
08-26 19:45:43.590  3176  3247 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-26 19:45:43.590  3176  3247 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.a2dp.A2dpService, state= 10,
08-26 19:45:43.590  3176  3247 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-26 19:45:43.590  3176  3247 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hid.HidService, state= 10
08-26 19:45:43.590  3176  3247 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-26 19:45:43.590  3176  3247 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hdp.HealthService, state= 10
08-26 19:45:43.590  3176  3247 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,08-26 19:45:43.590  3176  3247 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.pan.PanService, state= 10
08-26 19:45:43.590  3176  3247 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-26 19:45:43.590  3176  3247 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.map.BluetoothMapService, state= 10
08-26 19:45:43.590  3176  3247 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,08-26 19:45:43.590  3176  3247 W BluetoothAdapterService: isProfileEnabled(): profile com.broadcom.bt.service.sap.SapService, state= 10
08-26 19:45:43.590  3176  3247 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-26 19:45:43.590  3176  3247 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
08-26 19:45:43.590  3176  3247 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-26 19:45:43.590  3176  3247 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
,08-26 19:45:43.590  3176  3247 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-26 19:45:43.600  1020  1020 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-26 19:45:43.590  3176  3247 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
08-26 19:45:43.600  1020  1020 I InputMethodManagerService: [BT Setting State] State =11
08-26 19:45:43.590  3176  3247 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-26 19:45:43.590  3176  3247 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService,
08-26 19:45:43.590  3176  3247 W BluetoothAdapterService: Unable to start service com.android.bluetooth.gatt.GattService. Invalid state: 12
08-26 19:45:43.590  3176  3247 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
08-26 19:45:43.590  3176  3247 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-26 19:45:43.590  3176  3247 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,08-26 19:45:43.600  1177  1177 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED,
08-26 19:45:43.600  1177  1177 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-26 19:45:43.600  1177  1177 D BluetoothTile:  getBluetoothState : 11
08-26 19:45:43.600  1177  1784 D BluetoothTile:  handleUpdatestate:false name:null
08-26 19:45:43.600  1177  1784 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-26 19:45:43.600  1879  1879 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0,
,08-26 19:45:43.610  4713  4713 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-26 19:45:43.610  1020  1258 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-26 19:45:43.610  1020  1032 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-26 19:45:43.610  6761  6761 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 19:45:43.610  1177  1177 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-26 19:45:43.610  1020  4267 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-26 19:45:43.610  1020  4267 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-26 19:45:43.610  1020  4267 W ActivityManager: userId = 0, bbcId = -10000
,08-26 19:45:43.620  1020  4267 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:45:43.620  1020  4267 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 19:45:43.620  3176  3247 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
08-26 19:45:43.620  3176  3247 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-26 19:45:43.620  3176  3247 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-26 19:45:43.620  3176  3176 D HeadsetService: Received start request. Starting profile...
08-26 19:45:43.620  3176  3176 D HeadsetService: start()
08-26 19:45:43.620  3176  3176 D HeadsetStateMachine: make
,08-26 19:45:43.620  3176  3176 E HeadsetStateMachine: # of Max HF connection is 2
,08-26 19:45:43.630  1695  1695 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-26 19:45:43.630  1020  1508 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-26 19:45:43.630  1020  1508 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-26 19:45:43.630  1020  1508 W ActivityManager: userId = 0, bbcId = -10000
,08-26 19:45:43.630  1020  1508 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:45:43.630  1020  1508 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 19:45:43.630  1020  4358 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
,08-26 19:45:43.630  1020  4358 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,08-26 19:45:43.630  3176  3247 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
,08-26 19:45:43.630  3176  3247 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-26 19:45:43.630  3176  3247 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-26 19:45:43.630  1020  4358 W ActivityManager: userId = 0, bbcId = -10000
,08-26 19:45:43.630  1020  4358 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:45:43.630  1020  4358 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-26 19:45:43.640  1020  1082 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 19:45:43.640  1020  1082 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-26 19:45:43.640  1020  1082 W ActivityManager: userId = 0, bbcId = -10000,
08-26 19:45:43.640  1020  1082 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:45:43.640  1020  1082 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 19:45:43.640  3176  3247 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
08-26 19:45:43.640  3176  3247 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-26 19:45:43.640  3176  3247 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-26 19:45:43.640  1020  4357 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-26 19:45:43.640  1020  4357 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-26 19:45:43.640  1020  4357 W ActivityManager: userId = 0, bbcId = -10000
,08-26 19:45:43.640  1020  4357 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:45:43.640  1020  4357 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 19:45:43.640  1020  1258 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
,08-26 19:45:43.650  1020  1258 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,08-26 19:45:43.650  3176  3247 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
,08-26 19:45:43.650  3176  3247 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-26 19:45:43.650  3176  3247 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-26 19:45:43.650  1020  1258 W ActivityManager: userId = 0, bbcId = -10000
,08-26 19:45:43.650  1020  1258 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:45:43.650  1020  1258 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-26 19:45:43.650  3176  3176 I bluedroid: get_profile_interface handsfree
,08-26 19:45:43.650  4713  4713 D BluetoothNotiBroadcastReceiver: onReceive
,08-26 19:45:43.650  1020  1491 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-26 19:45:43.650  1020  1491 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-26 19:45:43.660  1020  1491 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:45:43.660  1020  1491 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:45:43.660  1020  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 19:45:43.660  3176  3247 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService,
08-26 19:45:43.660  3176  3247 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-26 19:45:43.660  3176  3247 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-26 19:45:43.660  1177  1177 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-26 19:45:43.660  1177  1177 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,08-26 19:45:43.660  1020  4267 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 19:45:43.660  1020  4267 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-26 19:45:43.670  1020  4267 W ActivityManager: userId = 0, bbcId = -10000
,08-26 19:45:43.670  1020  4267 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:45:43.670  1020  4267 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 19:45:43.670  3176  3247 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
08-26 19:45:43.670  3176  3247 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-26 19:45:43.670  3176  3247 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-26 19:45:43.670  3176  3176 E DualScoManager: Dual Sco Manager already instantiated
08-26 19:45:43.670  1020  1257 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 19:45:43.670  1020  1257 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-26 19:45:43.670  3176  3176 I DualScoManager: Set HeadsetServiceHelper
08-26 19:45:43.670  3176  3176 D BluetoothAtMessage: createCMTIContentObservers
08-26 19:45:43.670  1020  1257 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:45:43.670  1020  1257 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:45:43.670  1020  1257 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 19:45:43.670  1020  1508 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
08-26 19:45:43.670  1020  1508 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 19:45:43.670  1020  1508 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 19:45:43.670  1020  1508 D SettingsProvider: selectionArgs: false
08-26 19:45:43.670  1020  1508 D SettingsProvider: selectionArgs: 1002
08-26 19:45:43.670  1020  1508 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 19:45:43.670  1020  1508 D SettingsProvider: ret = -1
,08-26 19:45:43.670  3176  7649 D HeadsetStateMachine: Enter Disconnected: -2
,08-26 19:45:43.680  3176  3247 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
,08-26 19:45:43.680  3176  3247 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-26 19:45:43.680  3176  3247 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
,08-26 19:45:43.680  3176  3247 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-26 19:45:43.680  3176  3247 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService,
08-26 19:45:43.680  3176  3247 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-26 19:45:43.680  3176  3247 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
08-26 19:45:43.680  3176  3247 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-26 19:45:43.680  3176  3247 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService,
08-26 19:45:43.680  3176  3247 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
08-26 19:45:43.680  3176  3247 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-26 19:45:43.680  3176  3247 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-26 19:45:43.680  3176  3247 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,08-26 19:45:43.680  3176  3176 D HeadsetService: mStartError = false
08-26 19:45:43.680  3176  3176 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@247e950f
08-26 19:45:43.680  3176  3176 D A2dpService: Received start request. Starting profile...
08-26 19:45:43.680  3176  3176 D A2dpService: start()
08-26 19:45:43.680  3176  3176 I bluedroid: get_profile_interface avrcp
,08-26 19:45:43.680  3176  7649 D HeadsetStateMachine: Clear mHeadsetBrsf
08-26 19:45:43.680  3176  7649 D HeadsetStateMachine: map size, before remove : 0
08-26 19:45:43.680  3176  7649 D HeadsetStateMachine: map size, after remove: 0
,08-26 19:45:43.680  3176  3176 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-26 19:45:43.680  3176  3176 D Avrcp   : Initialize Media Controller
08-26 19:45:43.680  3176  3176 D Avrcp   : Get the Context Package Name: com.android.bluetooth
,08-26 19:45:43.690  3176  3176 E Avrcp   : getActiveSessions
08-26 19:45:43.690  3176  3176 D Avrcp   : pick active media Controller
08-26 19:45:43.690  3176  3176 D Avrcp   : Get the active Media Controller 
,08-26 19:45:43.690  3176  3176 I Avrcp   :  Updating now playing list upon AVRCP Start
,08-26 19:45:43.690  3176  7650 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,08-26 19:45:43.690  3176  3176 D A2dpStateMachine: make
,08-26 19:45:43.700  3176  7650 D BluetoothMediaBrowser: no now playing list
,08-26 19:45:43.700  3176  7650 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,08-26 19:45:43.700  3176  3176 I bluedroid: get_profile_interface a2dp
,08-26 19:45:43.700  3176  7652 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-26 19:45:43.700  3176  3176 E bt-btif : warning : media task started media_task_refcnt 1 
,08-26 19:45:43.700  3176  3176 D A2dpService: mStartError = false
08-26 19:45:43.700  3176  3176 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@247e950f
,08-26 19:45:43.700  3176  3176 D HeadsetStateMachine: Try to query the phonestate on bind
08-26 19:45:43.700  3176  7651 D A2dpStateMachine: Enter Disconnected: -2
,08-26 19:45:43.700  1445  1462 I Telecom : BluetoothPhoneService: queryPhoneState
08-26 19:45:43.700  1445  1445 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
08-26 19:45:43.700  1445  1445 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
08-26 19:45:43.710  1445  1462 I Telecom : BluetoothPhoneService: Result of Message : true
,08-26 19:45:43.710  3176  3176 D HidService: Received start request. Starting profile...
,08-26 19:45:43.710  3176  3176 D HidService: start()
08-26 19:45:43.710  3176  3176 I bluedroid: get_profile_interface hidhost
08-26 19:45:43.710  3176  3176 D HidService: setHidService(): set to: null
08-26 19:45:43.710  3176  3176 D HidService: mStartError = false,
08-26 19:45:43.710  3176  3176 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@247e950f
08-26 19:45:43.710  3176  3176 D HeadsetStateMachine: Proxy object connected
,08-26 19:45:43.710  3176  3176 D HealthService: Received start request. Starting profile...
08-26 19:45:43.710  3176  3176 D HealthService: start()
,08-26 19:45:43.710  3176  3176 I bluedroid: get_profile_interface health
08-26 19:45:43.710  3176  3176 D HealthService: mStartError = false
08-26 19:45:43.710  3176  3176 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@247e950f
08-26 19:45:43.710  3176  3176 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0,
08-26 19:45:43.710  3176  7649 D HeadsetStateMachine: Disconnected process message: 11
,08-26 19:45:43.710  3176  3176 D PanService: Received start request. Starting profile...
08-26 19:45:43.710  3176  3176 D PanService: start()
08-26 19:45:43.710  3176  3176 D BluetoothPanServiceJni: initializeNative(L110): pan
08-26 19:45:43.710  3176  3176 I bluedroid: get_profile_interface pan
,08-26 19:45:43.710  3176  3176 D PanService: mStartError = false
08-26 19:45:43.710  3176  3176 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@247e950f
08-26 19:45:43.710  3176  3176 D HeadsetPhoneState: sendDeviceDataStateChanged
,08-26 19:45:43.710  3176  3176 D HeadsetPhoneState: Signal level : previous=0 curr=4
08-26 19:45:43.710  3176  7649 D HeadsetStateMachine: Disconnected process message: 18
,08-26 19:45:43.710  3176  3176 D BluetoothMapService: Received start request. Starting profile...
,08-26 19:45:43.710  3176  3176 D BluetoothMapService: start()
,08-26 19:45:43.720  3176  3176 D BluetoothMapService: mStartError = false
,08-26 19:45:43.720  3176  3176 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@247e950f
,08-26 19:45:43.720  3176  3176 D SapService: Received start request. Starting profile...
,08-26 19:45:43.720  3176  3176 D SapService: start()
08-26 19:45:43.720  3176  3176 D BluetoothSAPServiceJni: initializeNative(L209): sap
08-26 19:45:43.720  3176  3176 I bluedroid: get_profile_interface sap
,08-26 19:45:43.720  3176  3176 D SapService: mStartError = false
08-26 19:45:43.720  3176  3176 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@247e950f
,08-26 19:45:43.720  3176  3176 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
08-26 19:45:43.720  3176  3176 E BluetoothAdapterService(612275471): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
08-26 19:45:43.720  3176  7649 D HeadsetStateMachine: Disconnected process message: 10
08-26 19:45:43.720  3176  7649 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-26 19:45:43.720  3176  7649 D HeadsetStateMachine: Disconnected process message: 11
,08-26 19:45:43.720  3176  3176 E BluetoothAdapterService(612275471): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
08-26 19:45:43.720  3176  3176 E BluetoothAdapterService(612275471): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
08-26 19:45:43.720  3176  3176 E BluetoothAdapterService(612275471): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
08-26 19:45:43.720  3176  3176 E BluetoothAdapterService(612275471): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,08-26 19:45:43.740  3176  3176 E BluetoothAdapterService(612275471): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,08-26 19:45:43.740  3176  3176 E BluetoothAdapterService(612275471): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,08-26 19:45:43.740  3176  3247 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
08-26 19:45:43.740  3176  3247 I bluedroid: enable
,08-26 19:45:43.740  3176  3250 E bt-btif : Calling BTA_HhEnable
,08-26 19:45:43.750  3176  3250 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
08-26 19:45:43.750  3176  3250 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
08-26 19:45:43.750  3176  3250 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
08-26 19:45:43.750  3176  3250 D BluetoothAdapterProperties: Address is:08:EC:A9:50:75:41
08-26 19:45:43.750  3176  3250 E BluetoothServiceJni: populateRssiValuesNative
08-26 19:45:43.750  3176  3250 I bluedroid: getModelRssiValues
08-26 19:45:43.750  3176  3250 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
08-26 19:45:43.750  3176  3250 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-26 19:45:43.750  3176  3250 D BluetoothAdapterProperties: Name is: Galaxy A3
,08-26 19:45:43.750  1020  1020 D SettingsProvider: name = bluetooth_name
,08-26 19:45:43.750  3176  3250 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-26 19:45:43.750  3176  3250 D BluetoothAdapterProperties: Scan Mode:20
08-26 19:45:43.750  3176  3250 D BluetoothAdapterProperties: Discoverable Timeout:120
08-26 19:45:43.750  3176  3250 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EA:82
08-26 19:45:43.750  3176  3250 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:2
08-26 19:45:43.750  3176  3250 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:1
,08-26 19:45:43.750  3176  3250 E bt-btif : btif_sock_init: !radio_req && !rfc_init
08-26 19:45:43.750  3176  3250 E bt-btif : JVenable fails
,08-26 19:45:43.750  3176  3250 D bte_conf: Device ID record 1 : primary
08-26 19:45:43.750  3176  3250 D bte_conf:   vendorId            = 0075
08-26 19:45:43.750  3176  3250 D bte_conf:   vendorIdSource      = 0001
08-26 19:45:43.750  3176  3250 D bte_conf:   product             = 0100
08-26 19:45:43.750  3176  3250 D bte_conf:   version             = 0200
08-26 19:45:43.750  3176  3250 D bte_conf:   clientExecutableURL = 
08-26 19:45:43.750  3176  3250 D bte_conf:   serviceDescription  = 
08-26 19:45:43.750  3176  3250 D bte_conf:   documentationURL    = 
08-26 19:45:43.750  3176  3250 D bte_conf: bte_load_did_conf no section named DID2.
,08-26 19:45:43.750  3176  3250 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
08-26 19:45:43.760  6761  6761 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 19:45:43.760  3176  3247 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-26 19:45:43.760  3176  3247 D BluetoothAdapterProperties: ScanMode =  20
08-26 19:45:43.760  3176  3247 D BluetoothAdapterProperties: State =  11
,08-26 19:45:43.760  1020  1513 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-26 19:45:43.760  3176  3247 D BluetoothAdapterProperties: Setting state to 12
,08-26 19:45:43.760  3176  3247 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-26 19:45:43.760  1020  4266 D SettingsProvider: name = bluetooth_a2dp_sink_mode
,08-26 19:45:43.760  1020  4266 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 19:45:43.760  1020  4266 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 19:45:43.760  1020  4266 D SettingsProvider: selectionArgs: false
08-26 19:45:43.760  1020  4266 D SettingsProvider: selectionArgs: 1002
08-26 19:45:43.760  1020  4266 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 19:45:43.760  1020  4266 D SettingsProvider: ret = -1
,08-26 19:45:43.760  3176  3247 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-26 19:45:43.760  3176  3247 D BluetoothAdapterService: updateAdapterState state is 12
,08-26 19:45:43.760  1020  4359 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-26 19:45:43.760  1020  4359 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-26 19:45:43.770  1020  4359 W ActivityManager: userId = 0, bbcId = -10000
,08-26 19:45:43.770  1020  4359 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:45:43.770  1020  4359 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 19:45:43.770  3176  3250 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-26 19:45:43.770  3176  3250 D BluetoothAdapterProperties: Scan Mode:21
08-26 19:45:43.770  3176  3250 D BluetoothAdapterProperties: Discoverable Timeout:120
08-26 19:45:43.770  3176  3250 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-26 19:45:43.770  4713  4724 D BluetoothMap: onBluetoothStateChange: up=true
,08-26 19:45:43.770  3176  3247 D BluetoothAdapterService: Autoconnection is available 
,08-26 19:45:43.770  3176  3247 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
08-26 19:45:43.770  3176  3247 D BluetoothAdapterService: starting service from this receiver
08-26 19:45:43.770  1020  1468 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 19:45:43.770  1020  1468 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-26 19:45:43.780  3176  3176 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
08-26 19:45:43.780  3176  3176 I BluetoothPbapService: Handler(): got msg=1
,08-26 19:45:43.780  1020  1468 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:45:43.780  1020  1468 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-26 19:45:43.780  1020  1468 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 19:45:43.780  1020  1033 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-26 19:45:43.780  3176  3247 I BluetoothAdapterState: Entering On State from state = 11
,08-26 19:45:43.790  3176  7657 V BluetoothPbapService: PBAP Service initSocket try: 0
,08-26 19:45:43.800  6761  6761 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 19:45:43.800  6761  6761 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:45:43.800  6761  6761 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 19:45:43.800  6761  6761 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 19:45:43.800  6761  6761 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 19:45:43.800  6761  6761 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 19:45:43.800  6761  6761 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 19:45:43.800  6761  6761 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 19:45:43.800  6761  6761 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 19:45:43.810  3176  7657 D BluetoothSocket: bindListen(): myUserId = 0
,08-26 19:45:43.810  3176  7657 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-26 19:45:43.810  3176  7657 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[80]}
,08-26 19:45:43.810  3176  7657 D BluetoothSocket: bindListen(), new LocalSocket 
08-26 19:45:43.810  3176  7657 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-26 19:45:43.810  3176  7657 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@244c3803
,08-26 19:45:43.810  3176  7657 D BluetoothSocket: channel: 19
08-26 19:45:43.810  3176  7657 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,08-26 19:45:43.940  1020  1051 I art     : Explicit concurrent mark sweep GC freed 57478(3MB) AllocSpace objects, 7(113KB) LOS objects, 33% free, 22MB/34MB, paused 2.367ms total 155.107ms
08-26 19:45:43.940  1020  1051 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
08-26 19:45:43.940  1020  1051 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-26 19:45:43.940  1020  1051 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:45:43.940  1020  1051 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:45:43.940  1020  1051 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-26 19:45:43.940  1020  1051 D BluetoothPan: Binding service...
,08-26 19:45:43.940  1020  1051 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-26 19:45:43.940  1020  1051 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-26 19:45:43.940  1445  1454 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-26 19:45:43.940  1020  1051 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-26 19:45:43.940  1020  1051 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-26 19:45:43.940  1020  1051 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:45:43.940  1020  1051 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:45:43.940  1020  1051 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-26 19:45:43.940  1445  1454 E BluetoothHeadset: BluetoothHeadset service is binded
,08-26 19:45:43.950  4713  7060 D Bluetoothsap: onBluetoothStateChange: up=true
08-26 19:45:43.950  4713  7060 D Bluetoothsap: Binding service...
08-26 19:45:43.950  4713  4713 D BluetoothMap: Proxy object connected
08-26 19:45:43.950  4713  4713 D MapProfile: Bluetooth service connected
08-26 19:45:43.950  4713  4713 D BluetoothMap: getConnectedDevices()
,08-26 19:45:43.950  1020  1020 D BluetoothPan: BluetoothPAN Proxy object connected
,08-26 19:45:43.950  4713  7060 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,08-26 19:45:43.950  1020  1051 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
08-26 19:45:43.950  1020  1051 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-26 19:45:43.960  1020  1051 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:45:43.960  1020  1051 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:45:43.960  1020  1051 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-26 19:45:43.960  4713  7060 D Bluetoothsap: bindService called to Bluetooth SAP Service
,08-26 19:45:43.960  1455  1793 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-26 19:45:43.960  1455  1793 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-26 19:45:43.960  1806  2237 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 19:45:43.960  1806  2237 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-26 19:45:43.960  1020  1051 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-26 19:45:43.960  1020  1051 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
08-26 19:45:43.960  4713  4713 D Bluetoothsap: BluetoothSAP Proxy object connected
08-26 19:45:43.960  1020  1051 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-26 19:45:43.960  1020  1051 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-26 19:45:43.960  1177  1838 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-26 19:45:43.960  4713  4713 D SapProfile: Bluetooth service connected
,08-26 19:45:43.960  4713  4713 D Bluetoothsap: getConnectedDevices()
08-26 19:45:43.960  1020  1020 D BluetoothA2dp: Proxy object connected
,08-26 19:45:43.960  1177  1838 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-26 19:45:43.960  4713  4724 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-26 19:45:43.970  1020  1051 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
,08-26 19:45:43.970  1020  1051 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-26 19:45:43.970  1020  1051 W ActivityManager: userId = 0, bbcId = -10000
,08-26 19:45:43.970  1020  1051 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:45:43.970  1020  1051 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-26 19:45:43.970  4713  4713 D BluetoothInputDevice: Proxy object connected
,08-26 19:45:43.970  4713  4713 D HidProfile: Bluetooth service connected
08-26 19:45:43.970  4713  7060 D BluetoothPbap: onBluetoothStateChange: up=true
,08-26 19:45:43.970  1020  1051 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
,08-26 19:45:43.970  1020  1051 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-26 19:45:43.980  1020  1051 W ActivityManager: userId = 0, bbcId = -10000
,08-26 19:45:43.980  1020  1051 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:45:43.980  1020  1051 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-26 19:45:43.980  1445  1454 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-26 19:45:43.980  1445  1454 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-26 19:45:43.980  4713  4713 D BluetoothPbap: Proxy object connected
08-26 19:45:43.980  4713  4713 D PbapServerProfile: Bluetooth service connected
,08-26 19:45:43.980  1472  1486 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-26 19:45:43.980  1020  1051 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-26 19:45:43.980  1020  1051 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-26 19:45:43.980  1020  1051 W ActivityManager: userId = 0, bbcId = -10000
,08-26 19:45:43.980  1020  1051 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-26 19:45:43.980  1020  1051 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,08-26 19:45:43.990  1472  1486 E BluetoothHeadset: BluetoothHeadset service is binded
,08-26 19:45:43.990  4713  7658 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-26 19:45:43.990  1020  1051 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-26 19:45:43.990  1020  1051 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-26 19:45:43.990  1020  1051 W ActivityManager: userId = 0, bbcId = -10000
,08-26 19:45:43.990  1020  1051 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-26 19:45:43.990  1020  1051 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-26 19:45:43.990  4713  7658 E BluetoothHeadset: BluetoothHeadset service is binded
,08-26 19:45:43.990  4713  4713 D HeadsetProfile: Bluetooth service connected
,08-26 19:45:43.990  1445  7102 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-26 19:45:44.000  1020  1051 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-26 19:45:44.000  1020  1051 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-26 19:45:44.000  1020  1051 W ActivityManager: userId = 0, bbcId = -10000
,08-26 19:45:44.000  1020  1051 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:45:44.000  1020  1051 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
08-26 19:45:44.000  1445  7102 E BluetoothHeadset: BluetoothHeadset service is binded
,08-26 19:45:44.000  1020  1051 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-26 19:45:44.000  1020  1051 E BluetoothHeadset: BluetoothHeadset service is binded
08-26 19:45:44.000  1020  1051 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-26 19:45:44.000  3176  3309 D BluetoothA2dp: onBluetoothStateChange: up=true
08-26 19:45:44.000  1020  1051 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-26 19:45:44.000  3176  3309 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-26 19:45:44.000  1020  1051 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-26 19:45:44.000  1020  1051 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-26 19:45:44.010  1020  1051 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:45:44.010  1020  1051 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:45:44.010  1020  1051 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 19:45:44.010  3176  3176 D BluetoothA2dp: Proxy object connected
08-26 19:45:44.010  3176  3176 D BluetoothAdapterService: Bluetooth A2dp source service connected
,08-26 19:45:44.010  1020  1051 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 19:45:44.010  1020  1051 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-26 19:45:44.010  7085  7097 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 19:45:44.010  7085  7097 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-26 19:45:44.010  1445  1454 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
08-26 19:45:44.010  1020  1051 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-26 19:45:44.010  1020  1051 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-26 19:45:44.010  1020  1051 W ActivityManager: userId = 0, bbcId = -10000
,08-26 19:45:44.010  1020  1051 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:45:44.010  1020  1051 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-26 19:45:44.010  1445  1454 E BluetoothHeadset: BluetoothHeadset service is binded
,08-26 19:45:44.010  3176  3184 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-26 19:45:44.010  3176  3184 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-26 19:45:44.010  4713  7060 D BluetoothPan: Binding service...
,08-26 19:45:44.010  1020  1051 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
,08-26 19:45:44.010  1020  1051 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-26 19:45:44.010  1020  1051 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:45:44.010  1020  1051 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:45:44.010  1020  1051 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-26 19:45:44.020  4713  4713 D BluetoothPan: BluetoothPAN Proxy object connected
08-26 19:45:44.020  6761  6776 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-26 19:45:44.020  6761  6776 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-26 19:45:44.020  4713  4713 D PanProfile: Bluetooth service connected
,08-26 19:45:44.020  1472  1488 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 19:45:44.020  1472  1488 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-26 19:45:44.020  4713  4724 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 19:45:44.020  4713  4724 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-26 19:45:44.020  4713  7658 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-26 19:45:44.020  4713  7658 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-26 19:45:44.020  1020  1051 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-26 19:45:44.020  1020  1051 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-26 19:45:44.020  1020  1051 W ActivityManager: userId = 0, bbcId = -10000
,08-26 19:45:44.020  1020  1051 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:45:44.020  1020  1051 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-26 19:45:44.020  1695  1792 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 19:45:44.020  1695  1792 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-26 19:45:44.030  1020  1051 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
08-26 19:45:44.030  1020  1051 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-26 19:45:44.030  4713  4713 D BluetoothA2dp: Proxy object connected
08-26 19:45:44.030  4713  4713 D A2dpProfile: Bluetooth service connected
,08-26 19:45:44.030  1020  1020 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-26 19:45:44.030  1020  1020 I InputMethodManagerService: [BT Setting State] State =12
,08-26 19:45:44.030  1020  1020 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-26 19:45:44.030  1445  1445 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@1017a883, true
,08-26 19:45:44.040  1177  1177 D BluetoothTile:  onBluetoothStateChange:
,08-26 19:45:44.040  1177  1177 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-26 19:45:44.040  1177  1177 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-26 19:45:44.040  1445  1445 D BluetoothHeadset: registerMessageListener
,08-26 19:45:44.040  1177  1784 D BluetoothTile:  handleUpdatestate:false name:null
,08-26 19:45:44.040  1177  1177 D BluetoothTile:  getBluetoothState : 12
,08-26 19:45:44.040  1879  1879 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-26 19:45:44.040  1177  1784 D BluetoothTile:  handleUpdatestate:false name:null
,08-26 19:45:44.050  6761  6761 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 19:45:44.050  1020  1487 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-26 19:45:44.050  3176  3310 D HeadsetService: registerMessageListener
,08-26 19:45:44.050  3176  3310 D HeadsetService: registerMessageListener,
,08-26 19:45:44.050  1020  4357 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true,
08-26 19:45:44.050  3176  7649 D HeadsetStateMachine: Disconnected process message: 70
,08-26 19:45:44.050  1445  1445 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
08-26 19:45:44.050  3176  7649 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@1e77c7ac
08-26 19:45:44.050  1445  1445 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
08-26 19:45:44.050  1177  1177 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-26 19:45:44.050  4713  4713 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-26 19:45:44.060  1445  1445 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
08-26 19:45:44.050  3176  7660 D BluetoothMapMasInstance: set MAP SDP message type : 1,
08-26 19:45:44.060  1445  1445 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
08-26 19:45:44.060  4713  4713 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
,08-26 19:45:44.060  1445  1445 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
08-26 19:45:44.060  4713  4713 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.,
,08-26 19:45:44.060  1177  1784 D BluetoothTile:  handleUpdatestate:false name:null
08-26 19:45:44.060  4713  4713 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
08-26 19:45:44.060  4713  4713 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
08-26 19:45:44.060  3176  7649 D HeadsetStateMachine: Disconnected process message: 9
,08-26 19:45:44.060  3176  7649 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
08-26 19:45:44.060  3176  7660 D BluetoothSocket: bindListen(): myUserId = 0
08-26 19:45:44.060  3176  7660 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 19:45:44.060  3176  7660 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[82]}
08-26 19:45:44.060  3176  7660 D BluetoothSocket: bindListen(), new LocalSocket 
,08-26 19:45:44.060  3176  7660 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-26 19:45:44.060  3176  7660 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@12de9c75
08-26 19:45:44.060  3176  7660 D BluetoothSocket: channel: 5
08-26 19:45:44.060   283   283 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
08-26 19:45:44.060   283   283 V voice   : voice_set_parameters: enter: A2dpSuspended=false
08-26 19:45:44.060   283   283 V voice   : voice_set_parameters: exit with code(-2)
08-26 19:45:44.060   283   283 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
08-26 19:45:44.060   283   283 V msm8974_platform: platform_set_parameters: exit with code(-2)
,08-26 19:45:44.060   283   283 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
08-26 19:45:44.060   283   283 V audio_hw_primary: adev_set_parameters: exit
08-26 19:45:44.060  3176  7649 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
08-26 19:45:44.060  4713  4713 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-26 19:45:44.060  1020  1033 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-26 19:45:44.060  1020  1033 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-26 19:45:44.060  1020  1033 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:45:44.060  1020  1033 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:45:44.060  1020  1033 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-26 19:45:44.070  1695  1695 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-26 19:45:44.070  4713  4713 D DockEventReceiver: finishStartingService: stopping service
,08-26 19:45:44.080  4713  4713 D BluetoothNotiBroadcastReceiver: onReceive
,08-26 19:45:44.080  1177  1177 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-26 19:45:44.080  1177  1177 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,08-26 19:45:44.090  3176  3176 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@247e950f
,08-26 19:45:44.090  3176  3176 D BtConfig.SecureMode: isSecureModeOn:false
,08-26 19:45:44.090  1020  1508 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-26 19:45:44.090  1020  1508 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,08-26 19:45:44.090  1020  1508 W ActivityManager: userId = 0, bbcId = -10000
,08-26 19:45:44.090  1020  1508 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:45:44.090  1020  1508 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 19:45:44.100  1020  1257 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-26 19:45:44.110  3176  7665 D BluetoothSocket: bindListen(): myUserId = 0
,08-26 19:45:44.110  3176  7665 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-26 19:45:44.110  3176  7665 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[85]}
08-26 19:45:44.110  3176  7665 D BluetoothSocket: bindListen(), new LocalSocket 
08-26 19:45:44.110  3176  7665 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-26 19:45:44.110  3176  7665 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@37898af1
,08-26 19:45:44.120  3176  7665 D BluetoothSocket: channel: 12
08-26 19:45:44.120  3176  7665 I BtOppRfcommListener: Accept thread started.
,08-26 19:45:44.600  6761  6987 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 19:45:44.600  6761  6987 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:45:44.600  6761  6987 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 19:45:44.600  6761  6987 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 19:45:44.600  6761  6987 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 19:45:44.600  6761  6987 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 19:45:44.600  6761  6987 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 19:45:44.600  6761  6987 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 19:45:44.600  6761  6987 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 19:45:44.600  6761  6987 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 19:45:44.600  6761  6987 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1e875556 added. We now have 8 listener(s)
08-26 19:45:44.600  6761  6987 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 19:45:44.610  1020  1508 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-26 19:45:44.610  1020  1508 D WifiService: setWifiEnabled: false pid=6761, uid=10170
08-26 19:45:44.610  1020  1508 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-26 19:45:44.610  1020  1508 D SecContentProvider2: mCursor = null
08-26 19:45:44.610  1020  1508 D SettingsProvider: name = wifi_on
,08-26 19:45:44.610  6761  6987 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:45:44.610  1020  1513 D WifiService: setWifiEnabled: true pid=6761, uid=10170
08-26 19:45:44.610  1020  1513 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-26 19:45:44.610  1020  1513 W ActivityManager: Permission Denial: getCurrentUser() from pid=6761, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
08-26 19:45:44.610  1020  1513 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-26 19:45:44.610  1020  1513 D SecContentProvider2: mCursor = null
08-26 19:45:44.610  1020  1513 W WifiService: Failed getting userId using ActivityManagerNative
08-26 19:45:44.610  1020  1513 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6761, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
08-26 19:45:44.610  1020  1513 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-26 19:45:44.610  1020  1513 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-26 19:45:44.610  1020  1513 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-26 19:45:44.610  1020  1513 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-26 19:45:44.610  1020  1513 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
08-26 19:45:44.610  1020  1513 D SettingsProvider: name = wifi_on
,08-26 19:45:44.620  1020  1131 E WifiHW  : ##################### set firmware type 0 #####################
,08-26 19:45:44.860  1020  3320 D SSRM:n  : SIOP:: AP = 350
,08-26 19:45:44.960  1020  1049 D Tethering: interfaceLinkStateChanged wlan0, false
08-26 19:45:44.960  1020  1049 D Tethering: interfaceStatusChanged wlan0, false
,08-26 19:45:44.960  1020  1049 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-26 19:45:44.960  1020  1049 D Tethering: interfaceAdded wlan0,
,08-26 19:45:44.960  1020  1049 D Tethering: interfaceAdded p2p0
,08-26 19:45:44.970   278  1006 I WifiHW  : wifi_change_fw_path(): fwpath = sta
08-26 19:45:44.970   278  1006 D SoftapController: Softap fwReload - Ok
,08-26 19:45:44.970  1020  1134 E Tethering: No numeric data
08-26 19:45:44.970  1020  1134 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-26 19:45:44.970  1020  1134 D Tethering: clearTetheredNotification()
,08-26 19:45:44.970   278  1006 D CommandListener: Setting iface cfg
08-26 19:45:44.970   278  1006 D CommandListener: Trying to bring down wlan0
,08-26 19:45:44.970  1020  1128 V NetworkStats: performPollLocked(flags=0x1)
08-26 19:45:44.970  1020  1128 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 19:45:44.980   278  1006 D CommandListener: Clearing all IP addresses on wlan0,
08-26 19:45:44.980  1020  1128 D NetworkStatsFactory: UpdateStatsForKnox updated,
08-26 19:45:44.980  1020  1128 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-26 19:45:44.980  1020  1049 D Tethering: p2p0 is not a tetherable iface, ignoring,
08-26 19:45:44.980  1177  1177 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED,
,08-26 19:45:44.980  1177  1177 D HotspotTile: updateTetherState():false, false
,08-26 19:45:44.990  1020  1128 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 19:45:44.990  1020  1128 V NetworkStats: performPollLocked() took 11ms
08-26 19:45:44.990  1020  1049 D Tethering: interfaceLinkStateChanged p2p0, false
08-26 19:45:44.990  1020  1049 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-26 19:45:44.990  1020  1049 D Tethering: interfaceStatusChanged p2p0, false
08-26 19:45:44.990  1020  1129 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 19:45:44.990  1020  1129 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 19:45:44.990  1020  1131 E WifiHW  : supplicant_name : p2p_supplicant
08-26 19:45:45.000  1020  1131 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,08-26 19:45:45.020  1177  1177 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-26 19:45:45.020  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 19:45:45.020  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null,
08-26 19:45:45.020  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:45:45.020  1177  1177 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-26 19:45:45.020  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 19:45:45.020  1177  1784 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-26 19:45:45.020  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:45:45.020  1177  1177 D HotspotTile: onReceive : 2, 0
08-26 19:45:45.020  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 19:45:45.020  1177  1177 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-26 19:45:45.020  1177  1177 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
,08-26 19:45:45.020  4713  4713 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-26 19:45:45.030  6761  6761 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 19:45:45.030  1020  4359 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-26 19:45:45.030  1020  4359 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-26 19:45:45.040  1020  4359 W ActivityManager: userId = 0, bbcId = -10000
,08-26 19:45:45.040  1020  4359 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:45:45.040  1020  4359 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-26 19:45:45.040  7677  7677 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
08-26 19:45:45.040  7677  7677 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-26 19:45:45.040  7677  7677 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,08-26 19:45:45.040  1627  1627 I Hs20UtilService: Starting #19,
08-26 19:45:45.050  1627  1661 I Hs20UtilService: Message received 5011
,08-26 19:45:45.050  7188  7188 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-26 19:45:45.050  7188  7188 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-26 19:45:45.050  7188  7188 D SecurityLogAgent: StateMachine : Current State = 1
08-26 19:45:45.050  7188  7188 D SecurityLogAgent: StateMachine : Changed Current State = 1,
,08-26 19:45:45.060  7677  7677 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage,
,08-26 19:45:45.060   411   411 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7677,
08-26 19:45:45.060   411   411 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
08-26 19:45:45.060  7677  7677 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
08-26 19:45:45.060  7677  7677 I wpa_supplicant: ssSupport state is = 1,
08-26 19:45:45.060  7677  7677 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
08-26 19:45:45.060  7677  7677 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
,08-26 19:45:45.060   411   411 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7677
08-26 19:45:45.060   411   411 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x00000106
,08-26 19:45:45.210   411   411 I SecureStorage: [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0
,08-26 19:45:45.210  7677  7677 I SecureStorage: [INFO]: SPID(0x00000003)Processing data has been completed
,08-26 19:45:45.250  7677  7677 I wpa_supplicant: Ctrl_iface: loading cred from phone
08-26 19:45:45.250  7677  7677 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,08-26 19:45:45.260  7677  7677 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
,08-26 19:45:45.260   411   411 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7677
08-26 19:45:45.260   411   411 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
08-26 19:45:45.260  7677  7677 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
08-26 19:45:45.260  7677  7677 I wpa_supplicant: ssSupport state is = 1
08-26 19:45:45.260  7677  7677 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-26 19:45:45.260  7677  7677 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-26 19:45:45.270  7677  7677 E wpa_supplicant: SIM READ ERROR
08-26 19:45:45.270  7677  7677 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-26 19:45:45.270  7677  7677 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-26 19:45:45.270  7677  7677 E wpa_supplicant: SIM READ ERROR
08-26 19:45:45.270  7677  7677 I wpa_supplicant: Blacklist: Clear (all) 
08-26 19:45:45.270  7677  7677 I wpa_supplicant: wpa_default_ap_write_once
08-26 19:45:45.270  7677  7677 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-26 19:45:45.270  7677  7677 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-26 19:45:45.270  7677  7677 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
08-26 19:45:45.270  7677  7677 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,08-26 19:45:45.270  7677  7677 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,08-26 19:45:45.270  7677  7677 I wpa_supplicant: rfkill: Cannot open RFKILL control device,
,08-26 19:45:45.270  1020  1049 D Tethering: interfaceLinkStateChanged wlan0, false,
08-26 19:45:45.270  1020  1049 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-26 19:45:45.270  1020  1049 D Tethering: interfaceStatusChanged wlan0, false
08-26 19:45:45.270  1020  1134 D Tethering: InitialState.processMessage what=4
,08-26 19:45:45.270  1020  1134 E Tethering: No numeric data
08-26 19:45:45.270  1020  1134 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-26 19:45:45.270  1020  1134 D Tethering: clearTetheredNotification()
,08-26 19:45:45.280  1020  1128 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 19:45:45.280  1020  1128 V NetworkStats: performPollLocked(flags=0x1)
08-26 19:45:45.280  1020  1128 D NetworkStatsFactory: UpdateStatsForKnox updated
08-26 19:45:45.280  1177  1177 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,08-26 19:45:45.280  1020  1128 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-26 19:45:45.280  1177  1177 D HotspotTile: updateTetherState():false, false
08-26 19:45:45.280  1020  1128 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 19:45:45.280  1020  1128 V NetworkStats: performPollLocked() took 4ms
,08-26 19:45:45.280  1020  1129 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 19:45:45.280  1020  1129 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 19:45:45.440  7677  7677 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec
,08-26 19:45:45.570  7677  7677 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED,
,08-26 19:45:45.570  7677  7677 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage,
,08-26 19:45:45.580  7677  7677 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
08-26 19:45:45.580   411   411 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7677
08-26 19:45:45.580   411   411 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
,08-26 19:45:45.580  7677  7677 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
08-26 19:45:45.580  7677  7677 I wpa_supplicant: ssSupport state is = 1
08-26 19:45:45.590  7677  7677 I wpa_supplicant: Ctrl_iface: loading cred from phone,
08-26 19:45:45.590  7677  7677 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,08-26 19:45:45.600  7677  7677 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
08-26 19:45:45.600   411   411 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7677
08-26 19:45:45.600   411   411 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C,
08-26 19:45:45.600  7677  7677 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
08-26 19:45:45.600  7677  7677 I wpa_supplicant: ssSupport state is = 1
08-26 19:45:45.600  7677  7677 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-26 19:45:45.600  7677  7677 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory,
08-26 19:45:45.600  7677  7677 E wpa_supplicant: SIM READ ERROR
08-26 19:45:45.600  7677  7677 I wpa_supplicant: wpa_default_ap_write_once
08-26 19:45:45.600  7677  7677 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
,08-26 19:45:45.600  7677  7677 I wpa_supplicant: rfkill: Cannot open RFKILL control device,
08-26 19:45:45.610  1020  1049 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-26 19:45:45.610  1020  1049 D Tethering: interfaceLinkStateChanged p2p0, false
08-26 19:45:45.610  1020  1049 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-26 19:45:45.610  1020  1049 D Tethering: interfaceStatusChanged p2p0, false,
08-26 19:45:45.610  1020  1049 D Tethering: interfaceLinkStateChanged p2p0, false
08-26 19:45:45.610  1020  1049 D Tethering: interfaceStatusChanged p2p0, false
,08-26 19:45:45.710  7677  7677 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE,
08-26 19:45:45.710  7677  7677 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,08-26 19:45:45.770  7677  7677 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED
,08-26 19:45:45.770  7677  7677 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
08-26 19:45:45.770  7677  7677 I wpa_supplicant: Skip scan - bUseNetwork false
,08-26 19:45:45.780  1020  1131 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,08-26 19:45:45.780  1020  1131 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-26 19:45:45.780  7677  7677 I wpa_supplicant: HOTSPOT20_ENABLE called
08-26 19:45:45.780  7677  7677 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-26 19:45:45.780  7677  7677 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory,
08-26 19:45:45.780  7677  7677 E wpa_supplicant: SIM READ ERROR
08-26 19:45:45.780  7677  7677 I wpa_supplicant: Blacklist: Clear (all) 
,08-26 19:45:45.800  7677  7677 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec,
,08-26 19:45:45.810  7677  7677 I wpa_supplicant: Skip scan - bUseNetwork false
,08-26 19:45:45.820  1020  1131 D WifiConfigStore: Loading config and enabling all networks 
,08-26 19:45:45.820  4713  4713 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-26 19:45:45.820  1177  1177 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-26 19:45:45.830  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-26 19:45:45.830  1020  1258 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-26 19:45:45.830  1020  1258 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-26 19:45:45.830  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-26 19:45:45.830  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:45:45.830  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 19:45:45.830  1020  1258 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:45:45.830  1020  1258 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:45:45.830  1020  1258 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-26 19:45:45.830  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:45:45.830  1177  1177 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-26 19:45:45.830  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:45:45.830  1177  1784 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-26 19:45:45.830  1177  1177 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-26 19:45:45.830  1177  1177 D HotspotTile: onReceive : 3, 0
08-26 19:45:45.830  1177  1177 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
,08-26 19:45:45.830  6761  6761 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 19:45:45.830  6761  6761 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:45:45.830  6761  6761 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 19:45:45.830  6761  6761 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 19:45:45.830  6761  6761 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 19:45:45.830  6761  6761 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 19:45:45.830  6761  6761 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 19:45:45.830  6761  6761 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 19:45:45.830  1627  1627 I Hs20UtilService: Starting #20
,08-26 19:45:45.840  1627  1661 I Hs20UtilService: Message received 5011
,08-26 19:45:45.840  6761  6761 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-26 19:45:45.840  1020  1131 E WifiConfigStore: Not a HS20
,08-26 19:45:45.850  7188  7188 D SecurityLogAgent: KnoxConfiguration : Current State = 1,
08-26 19:45:45.850  7188  7188 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-26 19:45:45.850  7188  7188 D SecurityLogAgent: StateMachine : Current State = 1
08-26 19:45:45.850  7188  7188 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-26 19:45:45.850  1020  1131 D WifiNative-wlan0: callSECApiInt - ID [65]
,08-26 19:45:45.850  1020  1131 D WifiNative-wlan0: callSECApiBoolean - ID [13]
08-26 19:45:45.850  7677  7677 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
08-26 19:45:45.850  7677  7677 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,08-26 19:45:45.850  7677  7677 I wpa_supplicant: reset timer : RESET_TIMER 0,
08-26 19:45:45.850  7677  7677 I wpa_supplicant: P2P: Current p2p state = IDLE
08-26 19:45:45.850  7677  7677 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
08-26 19:45:45.850  7677  7677 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
,08-26 19:45:45.850  7677  7677 I wpa_supplicant: First Scan Start
08-26 19:45:45.850  7677  7677 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-26 19:45:45.860  1020  1131 D WifiNative-wlan0: Setting external_sim to 1,
08-26 19:45:45.860  1020  1131 D WifiStateMachine: Setting OUI to DA-A1-19
08-26 19:45:45.860  1020  1131 I WifiNative-HAL: startHal
08-26 19:45:45.860  1020  1131 E wifi    : getStaticLongField sWifiHalHandle 0x9ef7688c
08-26 19:45:45.860  1020  1131 I WifiNative-HAL: Could not start hal
,08-26 19:45:45.860  7132  7132 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-26 19:45:45.860  1020  1131 E WifiNative-wlan0: do suspend true
,08-26 19:45:45.860  1020  1130 D WifiP2pService: P2pDisabledState{ what=131203 }
,08-26 19:45:45.860  1020  1131 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,08-26 19:45:45.870   278  1006 D CommandListener: Setting iface cfg
08-26 19:45:45.870   278  1006 D CommandListener: Trying to bring up p2p0
,08-26 19:45:45.870  1020  1020 D WifiScanningService: SCAN_AVAILABLE : 3
08-26 19:45:45.870  1020  1154 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:45:45.870  1020  1154 I WifiNative-HAL: startHal
08-26 19:45:45.870  1020  1154 E wifi    : getStaticLongField sWifiHalHandle 0x9df369bc
08-26 19:45:45.870  1020  1154 I WifiNative-HAL: Could not start hal
08-26 19:45:45.870  1020  1154 E WifiScanningService: could not start HAL
,08-26 19:45:45.870  1020  1020 D RttService: SCAN_AVAILABLE : 3
08-26 19:45:45.870  1020  1130 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-26 19:45:45.870  1020  1155 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:45:45.870  1020  1130 D WifiP2pService: P2pEnablingState
08-26 19:45:45.870  1020  1130 D WifiP2pService: P2pEnablingState{ what=147457 }
08-26 19:45:45.870  1020  1130 D WifiP2pService: P2p socket connection successful
08-26 19:45:45.870  1020  1131 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-26 19:45:45.870  1020  1130 D WifiP2pService: P2pEnabledState
08-26 19:45:45.870  1020  1131 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-26 19:45:45.870  1020  1131 E WifiNative-wlan0: invaild command id : 215
,08-26 19:45:45.870  1020  1131 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-26 19:45:45.870  1020  1130 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
08-26 19:45:45.870  1020  1131 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
,08-26 19:45:45.870  1020  1131 E WifiNative-wlan0: invaild command id : 215
08-26 19:45:45.870  1020  1133 E ConnectivityService: updateNetworkInfo()
08-26 19:45:45.870  1020  1020 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
08-26 19:45:45.870  1020  1052 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
,08-26 19:45:45.870  1020  1052 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-26 19:45:45.870  1020  1052 D WifiDisplayController: disconnect,
08-26 19:45:45.870  1020  1052 D WifiDisplayController: updateConnection
08-26 19:45:45.870  1020  1052 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-26 19:45:45.870  1020  1052 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-26 19:45:45.870  1020  1052 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 19:45:45.870  1020  1052 D WifiDisplayAdapter: onP2pDisconnected
08-26 19:45:45.880  7677  7677 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
08-26 19:45:45.870  1020  1052 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-26 19:45:45.870  1020  1052 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-26 19:45:45.880  7677  7677 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-26 19:45:45.880  1177  1177 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-26 19:45:45.880  1020  1513 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-26 19:45:45.880  1020  1130 D WifiNative-p2p0: p2pGetDeviceAddress
08-26 19:45:45.880  7677  7677 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands
08-26 19:45:45.880  1177  1177 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
08-26 19:45:45.880  1020  1131 E WifiStateMachine: Failed to set frequency band 0
08-26 19:45:45.880  4713  4713 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-26 19:45:45.880  1020  1130 D WifiNative-p2p0: p2pGetDeviceAddress returning 0a:ec:a9:50:75:42
08-26 19:45:45.880  1020  1131 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-26 19:45:45.880  1020  1131 D SecContentProvider2: mCursor = null
,08-26 19:45:45.880  1020  1052 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Galaxy A3
08-26 19:45:45.880  1020  1052 D WifiDisplayController:  deviceAddress: 0a:ec:a9:50:75:42
08-26 19:45:45.880  1020  1052 D WifiDisplayController:  primary type: 10-0050F204-5
08-26 19:45:45.880  1020  1052 D WifiDisplayController:  secondary type: null
08-26 19:45:45.880  1020  1052 D WifiDisplayController:  wps: 0
08-26 19:45:45.880  1020  1052 D WifiDisplayController:  grpcapab: 0
08-26 19:45:45.880  1020  1052 D WifiDisplayController:  devcapab: 0
08-26 19:45:45.880  1020  1052 D WifiDisplayController:  status: 3
08-26 19:45:45.880  1020  1052 D WifiDisplayController:  wfdInfo: null
08-26 19:45:45.880  1020  1052 D WifiDisplayController:  groupownerAddress: null
08-26 19:45:45.880  1020  1052 D WifiDisplayController:  GOdeviceName: null
08-26 19:45:45.880  1020  1052 D WifiDisplayController:  interfaceAddress: 
08-26 19:45:45.880  1020  1052 D WifiDisplayController:  SConnectInfo : null
08-26 19:45:45.880  1020  1130 D WifiP2pService: DeviceAddress: 0a:75:42
,08-26 19:45:45.890  4713  4713 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-26 19:45:45.890  4713  4713 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-26 19:45:45.890  1020  1131 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-26 19:45:45.890  1020  1131 D SecContentProvider2: mCursor = null
,08-26 19:45:45.890  4713  4713 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-26 19:45:45.890  4713  4713 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-26 19:45:45.890  4713  4713 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-26 19:45:45.890  4713  4794 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-26 19:45:45.890  7563  7563 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-26 19:45:45.890  7563  7563 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-26 19:45:45.900  7563  7563 D FileShare-Client: Outbound.stopDelayTimer - 
,08-26 19:45:45.900  7172  7172 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-26 19:45:45.910  1020  1130 D WifiP2pService: sending p2p persistent groups changed broadcast
,08-26 19:45:45.910  1020  1130 D WifiP2pService: InactiveState
,08-26 19:45:45.910  1020  1130 D WifiP2pService: InactiveState{ what=143376 }
08-26 19:45:45.910  1020  1130 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-26 19:45:45.910  7677  7677 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-26 19:45:45.910  1020  1130 D WifiP2pService: InactiveState{ what=143376 }
,08-26 19:45:45.910  1020  1130 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-26 19:45:45.950  1020  1049 D Tethering: interfaceLinkStateChanged p2p0, false,
08-26 19:45:45.950  1020  1049 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-26 19:45:45.950  1020  1049 D Tethering: interfaceStatusChanged p2p0, false
,08-26 19:45:46.390   295   295 E SMD     : DCD OFF
,08-26 19:45:46.630  6761  6987 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:,
08-26 19:45:46.630  6761  6987 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:45:46.630  6761  6987 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 19:45:46.630  6761  6987 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 19:45:46.630  6761  6987 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 19:45:46.630  6761  6987 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null,
08-26 19:45:46.630  6761  6987 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 19:45:46.630  6761  6987 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 19:45:46.640  6761  6987 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-26 19:45:46.640  6761  6987 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-26 19:45:46.640  6761  6987 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
08-26 19:45:46.640  6761  6987 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@16295c15 Bundle[{}]
,08-26 19:45:46.640  6761  6987 I io.jxcore.node.LifeCycleMonitor: start: OK
08-26 19:45:46.640  6761  6987 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-26 19:45:46.640  6761  6987 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-26 19:45:46.640  6761  6987 D io.jxcore.node.LifeCycleMonitor: onActivityStopped,
08-26 19:45:46.640  6761  6987 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-26 19:45:46.640  6761  6987 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-26 19:45:46.650  6761  6987 I System.out: Running OutgoingSocketThread
,08-26 19:45:46.660  6761  7686 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 1364),
08-26 19:45:46.660  6761  7686 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 54856
08-26 19:45:46.660  6761  7686 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-26 19:45:47.100  7677  7677 I wpa_supplicant: nl80211: Received scan results (26 BSSes),
08-26 19:45:47.100  7677  7677 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
08-26 19:45:47.100  7677  7677 I wpa_supplicant: Trying to associate with SSID '4E47373030',
08-26 19:45:47.100  7677  7677 I wpa_supplicant: Trying to associate with  'G700'
08-26 19:45:47.100  7677  7677 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
08-26 19:45:47.100  7677  7677 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
,08-26 19:45:47.100  1020  7683 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
,08-26 19:45:47.110  1020  1131 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-26 19:45:47.110  1020  1131 D SecContentProvider2: mCursor = null
,08-26 19:45:47.210  7677  7677 E wpa_supplicant: Cmd 35605 not handled
,08-26 19:45:47.210  7677  7677 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-26 19:45:47.210  7677  7677 I wpa_supplicant: wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00)
,08-26 19:45:47.210  1020  1049 D Tethering: interfaceLinkStateChanged wlan0, false
08-26 19:45:47.210  1020  1049 D Tethering: interfaceStatusChanged wlan0, false
08-26 19:45:47.210  7677  7677 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
,08-26 19:45:47.210  7677  7677 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
08-26 19:45:47.210  7677  7677 I wpa_supplicant: Associated with F4.99.3E
08-26 19:45:47.210  7677  7677 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
,08-26 19:45:47.210  7677  7677 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
08-26 19:45:47.210  7677  7677 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
,08-26 19:45:47.210  1020  1049 D Tethering: interfaceLinkStateChanged wlan0, false
08-26 19:45:47.210  1020  1049 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-26 19:45:47.210  1020  1049 D Tethering: interfaceStatusChanged wlan0, false
,08-26 19:45:47.210  1020  1049 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-26 19:45:47.220  1020  1049 D Tethering: interfaceLinkStateChanged wlan0, false
08-26 19:45:47.220  1020  1049 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-26 19:45:47.220  1020  1049 D Tethering: interfaceStatusChanged wlan0, false
08-26 19:45:47.220  1020  1049 D Tethering: interfaceLinkStateChanged wlan0, true
08-26 19:45:47.220  1020  1049 D Tethering: interfaceStatusChanged wlan0, true
,08-26 19:45:47.220  7677  7677 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-26 19:45:47.220  1020  1049 I Nat464Xlat: interfaceLinkStateChanged wlan0, true,
08-26 19:45:47.220  7677  7677 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
08-26 19:45:47.220  1020  1134 E Tethering: No numeric data
08-26 19:45:47.220  7677  7677 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
08-26 19:45:47.220  1020  1134 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-26 19:45:47.220  1020  1134 D Tethering: clearTetheredNotification()
08-26 19:45:47.220  7677  7677 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
08-26 19:45:47.220  1020  1131 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-26 19:45:47.220  1020  1131 D SecContentProvider2: mCursor = null
08-26 19:45:47.230  7677  7677 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-26 19:45:47.230  7677  7677 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
,08-26 19:45:47.230  7677  7677 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
,08-26 19:45:47.230  7677  7677 I wpa_supplicant: Blacklist: Clear (temp) 
08-26 19:45:47.230  1020  1049 D Tethering: interfaceLinkStateChanged wlan0, true
08-26 19:45:47.230  1020  1049 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-26 19:45:47.230  1020  1049 D Tethering: interfaceStatusChanged wlan0, true
08-26 19:45:47.230  7677  7677 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
08-26 19:45:47.230  1020  1128 V NetworkStats: performPollLocked(flags=0x1)
08-26 19:45:47.230  1020  1128 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 19:45:47.230  1177  1177 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-26 19:45:47.230  1020  1128 D NetworkStatsFactory: UpdateStatsForKnox updated
08-26 19:45:47.230  1177  1177 D HotspotTile: updateTetherState():false, false
08-26 19:45:47.230  1020  1128 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-26 19:45:47.240  1020  1131 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-26 19:45:47.240  1020  1131 D SecContentProvider2: mCursor = null
08-26 19:45:47.240  1020  1128 V NetworkStats: performPollLocked() took 7ms
08-26 19:45:47.240  1020  1128 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 19:45:47.240  1020  1129 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 19:45:47.240  1020  1129 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 19:45:47.250  1020  1131 D WifiNative-wlan0: callSECApiVoid - ID [50]
,08-26 19:45:47.250  1020  1131 E WifiConfigStore: setLastSelectedConfiguration -1
,08-26 19:45:47.250  1020  1133 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
08-26 19:45:47.250  1020  1131 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
08-26 19:45:47.250  1020  1133 E ConnectivityService: updateNetworkInfo()
08-26 19:45:47.260  1020  1133 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-26 19:45:47.260  1020  1131 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-26 19:45:47.260  1020  4267 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-26 19:45:47.260  1020  4267 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:45:47.260  1020  4267 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-26 19:45:47.260  1020  4267 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:45:47.260  1020  4267 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-26 19:45:47.260  1627  1627 I Hs20UtilService: Starting #21
08-26 19:45:47.260  1177  1177 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-26 19:45:47.260  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
08-26 19:45:47.260  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-26 19:45:47.260  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:45:47.260  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:45:47.260  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:45:47.260  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:45:47.260  1627  1661 I Hs20UtilService: Message received 5007
,08-26 19:45:47.260  4713  4713 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-26 19:45:47.270  1020  1131 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-26 19:45:47.270  4713  4713 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null,
,08-26 19:45:47.270  4713  4713 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-26 19:45:47.270  4713  4713 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-26 19:45:47.270  4713  4713 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-26 19:45:47.270  4713  4713 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-26 19:45:47.270  4713  4794 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-26 19:45:47.280   278  1006 D CommandListener: Setting iface cfg
,08-26 19:45:47.280  1020  1131 E WifiStateMachine: Start Dhcp Watchdog 3
,08-26 19:45:47.290  1020  1131 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-26 19:45:47.290  1020  1131 D SecContentProvider2: mCursor = null
,08-26 19:45:47.300  1177  1177 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-26 19:45:47.300  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 19:45:47.300  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-26 19:45:47.300  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 19:45:47.300  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:45:47.300  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 19:45:47.300  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 19:45:47.300  1020  1131 E WifiNative-wlan0: do suspend false,
,08-26 19:45:47.300  1020  1131 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-26 19:45:47.300  1020  1131 D SecContentProvider2: mCursor = null
,08-26 19:45:47.300  1020  1130 D WifiP2pService: InactiveState{ what=143375 }
,08-26 19:45:47.300  1020  1130 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-26 19:45:47.520  7689  7689 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,08-26 19:45:47.520  7689  7689 I dhcpcd  : version 5.5.6 starting
,08-26 19:45:47.530  7689  7689 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,08-26 19:45:47.580  7689  7689 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
08-26 19:45:47.580  7689  7689 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address,
08-26 19:45:47.580  7689  7689 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
08-26 19:45:47.580  7689  7689 I dhcpcd  : bssid match
08-26 19:45:47.580  7689  7689 I dhcpcd  : wlan0: rebinding lease of 192.168.1.116
,08-26 19:45:47.630  7689  7689 I dhcpcd  : wlan0: acknowledged 192.168.1.116 from 192.168.1.1
,08-26 19:45:47.660  6761  6987 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 1365)
,08-26 19:45:47.660  6761  6987 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 1365)
,08-26 19:45:47.660  6761  6987 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1370)
,08-26 19:45:47.660  6761  6987 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,08-26 19:45:47.660  6761  6987 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1371)
,08-26 19:45:47.670  6761  6987 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-26 19:45:47.670  6761  6987 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1223b9d7 added. We now have 2 listener(s)
,08-26 19:45:47.670  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,08-26 19:45:47.670  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-26 19:45:47.680  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 19:45:47.680  6761  6987 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 19:45:47.680  6761  6987 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f1fd2c4 added. We now have 9 listener(s),
08-26 19:45:47.680  6761  6987 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 19:45:47.680  6761  6987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-26 19:45:47.680  6761  6987 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 19:45:47.680  7689  7689 I dhcpcd  : wlan0: leased 192.168.1.116 for 172800 seconds,
,08-26 19:45:47.690  6761  6987 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 19:45:47.690  6761  6987 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:45:47.690  6761  6987 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 19:45:47.690  6761  6987 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 19:45:47.690  6761  6987 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 19:45:47.690  6761  6987 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 19:45:47.690  6761  6987 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
,08-26 19:45:47.690  6761  6987 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 19:45:47.690  6761  6987 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null,
,08-26 19:45:47.690  6761  6987 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 19:45:47.690  6761  6987 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded,
,08-26 19:45:47.690  6761  6987 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34bb70e2 added. We now have 3 listener(s)
,08-26 19:45:47.700  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
08-26 19:45:47.700  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 19:45:47.700  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 19:45:47.700  6761  6987 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 19:45:47.700  6761  6987 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1001c73 added. We now have 10 listener(s)
08-26 19:45:47.700  6761  6761 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:45:47.700  6761  6987 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 19:45:47.700  6761  6987 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 19:45:47.700  6761  6987 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 19:45:47.700  6761  6987 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 19:45:47.700  6761  6987 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:45:47.700  6761  6987 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:47.700  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 19:45:47.700  6761  6987 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 19:45:47.700  6761  6987 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1223b9d7 removed from the list
08-26 19:45:47.700  6761  6987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:45:47.700  6761  6987 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f1fd2c4 removed from the list
08-26 19:45:47.700  6761  6761 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:45:47.700  6761  6987 D io.jxcore.node.ConnectivityMonitor: stop
08-26 19:45:47.700  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 19:45:47.700  6761  6987 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-26 19:45:47.700  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:47.700  6761  6987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-26 19:45:47.700  6761  6987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:45:47.700  6761  6987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:45:47.700  6761  6987 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f1fd2c4 not in the list
08-26 19:45:47.700  6761  6987 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:47.700  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 19:45:47.710  6761  6987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:45:47.710  6761  6987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 19:45:47.710  6761  6987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:45:47.710  6761  6987 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1001c73 removed from the list,
08-26 19:45:47.710  6761  6987 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:45:47.710  6761  6987 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:47.710  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:47.710  6761  6987 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 19:45:47.710  6761  6987 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34bb70e2 removed from the list
08-26 19:45:47.710  6761  6987 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 19:45:47.710  6761  6987 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@29a95730 added. We now have 2 listener(s)
08-26 19:45:47.710  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
08-26 19:45:47.710  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 19:45:47.710  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 19:45:47.710  6761  6987 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 19:45:47.710  6761  6987 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34caefa9 added. We now have 9 listener(s)
08-26 19:45:47.710  6761  6987 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 19:45:47.710  6761  6987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-26 19:45:47.710  6761  6987 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 19:45:47.720  6761  6987 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
08-26 19:45:47.720  6761  6987 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:45:47.720  6761  6987 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 19:45:47.720  6761  6987 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 19:45:47.720  6761  6987 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 19:45:47.720  6761  6987 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 19:45:47.720  6761  6987 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 19:45:47.720  6761  6987 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 19:45:47.730  6761  6987 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-26 19:45:47.730  6761  6987 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 19:45:47.730  6761  6987 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 19:45:47.730  6761  6987 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a360ccf added. We now have 3 listener(s)
08-26 19:45:47.730  6761  6761 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:45:47.730  6761  6761 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:45:47.730  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
08-26 19:45:47.730  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 19:45:47.730  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 19:45:47.730  6761  6987 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 19:45:47.730  6761  6987 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@804b65c added. We now have 10 listener(s)
08-26 19:45:47.730  6761  6987 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 19:45:47.730  6761  6987 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 19:45:47.730  6761  6987 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 19:45:47.730  6761  6987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 19:45:47.730  6761  6987 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 19:45:47.730  6761  6987 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-26 19:45:47.730  6761  6987 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-26 19:45:47.740  6761  6987 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-26 19:45:47.740  6761  6987 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-26 19:45:47.750  6761  6987 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-26 19:45:47.750  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-26 19:45:47.750  6761  6987 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-26 19:45:47.750  3176  7630 D BtGatt.GattService: registerClient() - UUID=3bc75cf6-c1d0-43d9-879c-377abc9a53e2
,08-26 19:45:47.790  3176  3250 D BtGatt.GattService: onClientRegistered() - UUID=3bc75cf6-c1d0-43d9-879c-377abc9a53e2, clientIf=6,
,08-26 19:45:47.800  6761  6776 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
08-26 19:45:47.800  3176  3184 D BtGatt.GattService: start scan with filters
08-26 19:45:47.800  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING,
08-26 19:45:47.800  6761  6987 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-26 19:45:47.800  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-26 19:45:47.800  6761  6987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-26 19:45:47.800  3176  3313 D BtGatt.ScanManager: handling starting scan
,08-26 19:45:47.800  3176  3250 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
08-26 19:45:47.800  3176  3250 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 19:45:47.800  3176  3313 D BtGatt.ScanManager: allow scan with filters
08-26 19:45:47.800  3176  3313 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-26 19:45:47.800  3176  3313 D BtGatt.ScanManager: set filter index= 6 for clientIf= 6
,08-26 19:45:47.800  6761  6987 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-26 19:45:47.800  6761  6987 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-26 19:45:47.800  6761  6761 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-26 19:45:47.810  3176  3250 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
08-26 19:45:47.810  3176  3250 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
08-26 19:45:47.810  3176  3313 D BtGatt.ScanManager: Starting BLE batch scan
08-26 19:45:47.810  3176  3313 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
08-26 19:45:47.810  6761  6987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK,
08-26 19:45:47.810  3176  3250 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
08-26 19:45:47.810  3176  3250 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 19:45:47.810  3176  3250 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1,
08-26 19:45:47.810  3176  3250 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 19:45:47.810  6761  6987 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-26 19:45:47.820  6761  6987 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-26 19:45:47.820  6761  6987 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-26 19:45:47.820  6761  6987 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 19:45:47.820  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-26 19:45:47.820  6761  6987 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-26 19:45:47.820  6761  6987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-26 19:45:47.820  6761  6987 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 19:45:47.820  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-26 19:45:47.820  6761  6987 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-26 19:45:47.820  6761  6987 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-26 19:45:47.820  3176  3185 D BtGatt.GattService: stopScan() - queue size =1
,08-26 19:45:47.820  3176  3313 D BtGatt.ScanManager: filter size is 1
,08-26 19:45:47.820  3176  3313 D BtGatt.ScanManager: delete FilterIndex - 6
,08-26 19:45:47.820  3176  7630 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-26 19:45:47.820  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-26 19:45:47.820  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-26 19:45:47.820  6761  6987 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-26 19:45:47.820  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-26 19:45:47.820  6761  6987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-26 19:45:47.820  3176  3250 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-26 19:45:47.820  3176  3250 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 19:45:47.820  3176  3313 D BtGatt.ScanManager: stopping BLe Batch
,08-26 19:45:47.820  6761  6987 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 19:45:47.820  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-26 19:45:47.820  6761  6987 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-26 19:45:47.820  6761  6987 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-26 19:45:47.830  3176  3250 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0,
08-26 19:45:47.830  3176  3250 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 19:45:47.830  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 19:45:47.830  3176  3313 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
08-26 19:45:47.830  6761  6761 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 19:45:47.830  6761  6761 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 19:45:47.830  6761  6761 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 19:45:47.840  3176  3250 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-26 19:45:47.840  3176  3250 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 19:45:47.840  6761  6987 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 19:45:47.840  6761  6987 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 19:45:47.840  6761  6987 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 19:45:47.840  6761  6987 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:45:47.840  6761  6987 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:47.840  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
08-26 19:45:47.840  6761  6987 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 19:45:47.840  6761  6987 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@29a95730 removed from the list
,08-26 19:45:47.840  6761  6987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:45:47.840  6761  6987 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34caefa9 removed from the list
08-26 19:45:47.840  6761  6987 D io.jxcore.node.ConnectivityMonitor: stop,
08-26 19:45:47.840  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:47.840  6761  6987 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:47.840  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
,08-26 19:45:47.850  6761  6987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 19:45:47.850  6761  6987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:45:47.850  6761  6987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:45:47.850  6761  6987 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34caefa9 not in the list
,08-26 19:45:47.850  6761  6987 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:47.850  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 19:45:47.850  6761  6987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:45:47.850  6761  6987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 19:45:47.850  6761  6987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
08-26 19:45:47.850  6761  6987 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@804b65c removed from the list
08-26 19:45:47.850  6761  6987 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:45:47.850  6761  6987 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:47.850  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 19:45:47.850  6761  6987 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 19:45:47.850  6761  6987 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a360ccf removed from the list
,08-26 19:45:47.850  6761  6987 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded,
08-26 19:45:47.850  6761  6987 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@354dc48 added. We now have 2 listener(s)
,08-26 19:45:47.860  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41",
08-26 19:45:47.860  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 19:45:47.860  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 19:45:47.860  6761  6987 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 19:45:47.860  6761  6987 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2defeae1 added. We now have 9 listener(s)
08-26 19:45:47.860  6761  6987 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 19:45:47.860  6761  6987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-26 19:45:47.860  6761  6987 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 19:45:47.870  6761  6987 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 19:45:47.870  6761  6987 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:45:47.870  6761  6987 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 19:45:47.870  6761  6987 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
,08-26 19:45:47.870  6761  6987 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 19:45:47.870  6761  6987 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 19:45:47.870  6761  6987 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 19:45:47.870  6761  6987 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 19:45:47.870  6761  6987 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-26 19:45:47.870  6761  6987 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 19:45:47.870  6761  6987 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 19:45:47.870  6761  6987 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@22f0c6c7 added. We now have 3 listener(s)
,08-26 19:45:47.870  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
08-26 19:45:47.870  6761  6761 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:45:47.870  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 19:45:47.870  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 19:45:47.870  6761  6987 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 19:45:47.870  6761  6987 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ff74f4 added. We now have 10 listener(s)
08-26 19:45:47.870  6761  6987 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 19:45:47.870  6761  6987 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 19:45:47.870  6761  6987 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-26 19:45:47.870  6761  6987 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 19:45:47.870  6761  6987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 19:45:47.870  6761  6987 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 19:45:47.870  6761  6987 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-26 19:45:47.880  6761  6761 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 19:45:47.880  6761  6987 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-26 19:45:47.880  6761  6987 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false,
,08-26 19:45:47.890  6761  6987 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-26 19:45:47.900  6761  6987 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-26 19:45:47.900  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-26 19:45:47.900  6761  6987 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-26 19:45:47.900  3176  3309 D BtGatt.GattService: registerClient() - UUID=2f4b73ef-0a84-4f57-8188-078145f51a08
,08-26 19:45:47.920  1020  1131 E WifiNative-wlan0: do suspend true
,08-26 19:45:47.950  1020  1130 D WifiP2pService: InactiveState{ what=143375 }
,08-26 19:45:47.950  1020  1130 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-26 19:45:47.950  3176  3250 D BtGatt.GattService: onClientRegistered() - UUID=2f4b73ef-0a84-4f57-8188-078145f51a08, clientIf=6
,08-26 19:45:47.950  6761  6776 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-26 19:45:47.950  1020  1131 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-26 19:45:47.950  1020  1131 E WifiStateMachine: VerifyingLinkState enter
08-26 19:45:47.950  3176  3310 D BtGatt.GattService: start scan with filters
,08-26 19:45:47.950  3176  3313 D BtGatt.ScanManager: handling starting scan
,08-26 19:45:47.950  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-26 19:45:47.950  6761  6987 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-26 19:45:47.950  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-26 19:45:47.950  6761  6987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-26 19:45:47.950  1177  1177 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-26 19:45:47.950  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 19:45:47.950  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-26 19:45:47.950  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:45:47.950  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:45:47.950  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:45:47.950  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 19:45:47.950  1020  1133 E ConnectivityService: updateNetworkInfo()
,08-26 19:45:47.960  1020  1133 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
08-26 19:45:47.960  1020  1133 D ConnectivityService: Adding iface wlan0 to network 504
,08-26 19:45:47.960  6761  6987 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-26 19:45:47.960  3176  3250 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
08-26 19:45:47.960  3176  3250 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 19:45:47.960  6761  6761 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-26 19:45:47.960  3176  3313 D BtGatt.ScanManager: allow scan with filters
,08-26 19:45:47.960  3176  3313 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-26 19:45:47.960  3176  3313 D BtGatt.ScanManager: set filter index= 7 for clientIf= 6
,08-26 19:45:47.960  6761  6987 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-26 19:45:47.960  3176  3250 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
08-26 19:45:47.960  3176  3250 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 19:45:47.970  3176  3313 D BtGatt.ScanManager: Starting BLE batch scan
08-26 19:45:47.970  3176  3313 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-26 19:45:47.970  6761  6987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-26 19:45:47.970  1020  1148 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter
,08-26 19:45:47.970  1020  1148 D WifiWatchdogStateMachine.DnsPinger: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-26 19:45:47.970  1020  1148 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-26 19:45:47.970  1020  1148 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-26 19:45:47.970  1020  1148 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,08-26 19:45:47.980  1020  1133 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 504
,08-26 19:45:47.980  1020  1133 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 504
,08-26 19:45:47.980  3176  3250 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
08-26 19:45:47.980  3176  3250 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 19:45:47.980  1177  1177 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-26 19:45:47.980  1020  1133 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 504
,08-26 19:45:47.980  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 19:45:47.980  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-26 19:45:47.980  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:45:47.980  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:45:47.980  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:45:47.980  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 19:45:47.980  1020  1131 E WifiStateMachine: VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,08-26 19:45:47.980  1020  1133 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-26 19:45:47.980  1020  1133 D ConnectivityService: Setting Dns servers for network 504 to [/192.168.1.1]
08-26 19:45:47.980  1020  1133 D ConnectivityService: LTETest block dns file not exists
,08-26 19:45:47.980  3176  3250 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
08-26 19:45:47.980  3176  3250 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 19:45:47.990  6761  6987 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 19:45:47.990  6761  6987 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
08-26 19:45:47.990  6761  6987 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 19:45:47.990  6761  6987 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 19:45:47.990  6761  6987 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 19:45:47.990  6761  6987 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:45:47.990  6761  6987 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:47.990  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-26 19:45:47.990  6761  6987 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 19:45:47.990  6761  6987 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@354dc48 removed from the list
08-26 19:45:47.990  6761  6987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:45:47.990  6761  6987 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2defeae1 removed from the list
08-26 19:45:47.990  6761  6987 D io.jxcore.node.ConnectivityMonitor: stop
08-26 19:45:47.990  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 19:45:47.990  6761  6987 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:47.990  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-26 19:45:47.990  1020  1508 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-26 19:45:47.990  6761  6987 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:47.990  1020  1508 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-26 19:45:47.990  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 19:45:47.990  1020  1508 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:45:47.990  1020  1508 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:45:47.990  1020  1508 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-26 19:45:47.990  1020  1133 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 19:45:47.990  1020  1133 V NetworkStats: updateIfacesLocked()
08-26 19:45:47.990  1020  1133 V NetworkStats: performPollLocked(flags=0x1)
,08-26 19:45:47.990  1020  1133 D NetworkStatsFactory: UpdateStatsForKnox updated
08-26 19:45:47.990  6761  6987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 19:45:47.990  6761  6987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:45:47.990  6761  6987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:45:47.990  6761  6987 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2defeae1 not in the list
08-26 19:45:47.990  6761  6987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-26 19:45:47.990  6761  6987 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 19:45:47.990  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-26 19:45:47.990  6761  6987 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-26 19:45:47.990  6761  6987 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-26 19:45:47.990  1020  1133 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-26 19:45:47.990  3176  3184 D BtGatt.GattService: stopScan() - queue size =1
,08-26 19:45:48.000  3176  3309 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-26 19:45:48.000  4713  4713 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-26 19:45:48.000  3176  3313 D BtGatt.ScanManager: filter size is 1
08-26 19:45:48.000  3176  3313 D BtGatt.ScanManager: delete FilterIndex - 7
,08-26 19:45:48.000  4713  4713 I NearbySettings: MountReceiver.onReceive - Keep current state
08-26 19:45:48.000  1627  1627 I Hs20UtilService: Starting #22
,08-26 19:45:48.000  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-26 19:45:48.000  3176  3250 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-26 19:45:48.000  3176  3250 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 19:45:48.000  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-26 19:45:48.000  6761  6987 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-26 19:45:48.000  1020  1133 V NetworkStats: performPollLocked() took 8ms
08-26 19:45:48.000  1020  1133 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 19:45:48.000  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-26 19:45:48.000  6761  6987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-26 19:45:48.000  3176  3313 D BtGatt.ScanManager: stopping BLe Batch
08-26 19:45:48.000  6761  6987 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 19:45:48.000  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-26 19:45:48.000  6761  6987 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-26 19:45:48.000  6761  6987 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-26 19:45:48.010  1627  1661 I Hs20UtilService: Message received 5007
,08-26 19:45:48.010  1020  1133 E ConnectivityService: updateNetworkInfo()
08-26 19:45:48.010  1020  1133 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
08-26 19:45:48.010  1020  1133 E ConnectivityService: updateNetworkInfo()
08-26 19:45:48.010  1020  1133 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-26 19:45:48.010  1020  1131 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-26 19:45:48.010  1020  1133 V NetworkStats: updateIfacesLocked()
08-26 19:45:48.010  1020  1133 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 19:45:48.010  1020  1133 V NetworkStats: performPollLocked(flags=0x1)
,08-26 19:45:48.010  3176  3250 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-26 19:45:48.010  3176  3250 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 19:45:48.010  3176  3313 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
08-26 19:45:48.010  1020  1131 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-26 19:45:48.010  1020  1133 D NetworkStatsFactory: UpdateStatsForKnox updated
08-26 19:45:48.010  1020  1133 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-26 19:45:48.010  1020  1020 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-26 19:45:48.010  1020  1133 V NetworkStats: performPollLocked() took 5ms
08-26 19:45:48.010  1020  1133 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 19:45:48.020  3176  3250 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=1
,08-26 19:45:48.020  3176  3250 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 19:45:48.020  3176  3250 D BtGatt.GattService: current time is 135652591926
08-26 19:45:48.020  3176  3250 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -71, 20, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,08-26 19:45:48.020  3176  3250 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84],
08-26 19:45:48.020  3176  3250 D ScanRecord: parseFromBytes
08-26 19:45:48.020  3176  3250 D ScanRecord: first manudata for manu ID
,08-26 19:45:48.030  1020  1020 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-26 19:45:48.030  1020  1020 I WifiTrafficPoller: mBoosterFLAG : 0
08-26 19:45:48.030  1020  1020 I WifiTrafficPoller: current booster mode : FullMode
,08-26 19:45:48.030  1177  1177 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-26 19:45:48.030  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 19:45:48.030  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-26 19:45:48.030  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:45:48.030  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:45:48.030  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:45:48.030  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 19:45:48.030  1177  1177 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-26 19:45:48.030  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,08-26 19:45:48.030  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 19:45:48.040  1020  1129 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 19:45:48.040  1020  1129 D NtpTrustedTime: currentTimeMillis() cache hit,
,08-26 19:45:48.040  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:45:48.040  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:45:48.040  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 19:45:48.040  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 19:45:48.040  1020  1129 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 19:45:48.040  1020  1129 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 19:45:48.040  1020  1133 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 504]
08-26 19:45:48.040  1020  1133 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
,08-26 19:45:48.040  1020  7687 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:45:48.040  1020  7687 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Connected
08-26 19:45:48.040  1020  7687 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:45:48.050  1020  7687 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on "NG700"
,08-26 19:45:48.050  6761  6987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:45:48.050  6761  6987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 19:45:48.050  6761  6987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:45:48.050  6761  6987 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ff74f4 removed from the list
08-26 19:45:48.050  6761  6987 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:45:48.050  6761  6987 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:48.050  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:48.050  6761  6987 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 19:45:48.050  6761  6987 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@22f0c6c7 removed from the list
,08-26 19:45:48.050  6761  6987 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 19:45:48.050  6761  6987 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@918ec60 added. We now have 2 listener(s)
,08-26 19:45:48.050  6761  6761 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 19:45:48.050  6761  6761 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 19:45:48.050  6761  6761 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 19:45:48.050  1020  7687 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-26 19:45:48.050  1020  1133 D ConnectivityService:    accepting network in place of null
,08-26 19:45:48.050  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
08-26 19:45:48.050  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 19:45:48.050  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 19:45:48.050  6761  6987 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 19:45:48.050  6761  6987 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@29e21519 added. We now have 9 listener(s)
08-26 19:45:48.050  6761  6987 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 19:45:48.050  1020  1131 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
,08-26 19:45:48.050  1020  1130 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,08-26 19:45:48.050  6761  6987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-26 19:45:48.050  1472  1472 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
,08-26 19:45:48.060  1472  1472 D TelephonyNetworkFactory: Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-26 19:45:48.060  6761  6987 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 19:45:48.060   278  1002 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-26 19:45:48.060   278  1002 D Netd    : getNetworkForDns: using netid 504 for uid 1000
,08-26 19:45:48.060  1020  1133 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-26 19:45:48.060  1020  1133 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 504] isDefaultNetwork=true
,08-26 19:45:48.060  1020  1133 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,08-26 19:45:48.060  1020  1513 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-26 19:45:48.060  1020  1513 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-26 19:45:48.060  1020  1513 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:45:48.060  1020  1513 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-26 19:45:48.060  1020  1513 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-26 19:45:48.070  1627  1627 I Hs20UtilService: Starting #23
,08-26 19:45:48.070  1020  1133 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,08-26 19:45:48.070  1020  1020 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
08-26 19:45:48.070  1020  1134 D Tethering: MasterInitialState.processMessage what=3
,08-26 19:45:48.070  1020  1133 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
,08-26 19:45:48.070  1627  1661 I Hs20UtilService: Message received 5007
08-26 19:45:48.070  1177  1763 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-26 19:45:48.070  1020  1128 V NetworkStats: updateIfacesLocked()
08-26 19:45:48.070  1020  1128 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 19:45:48.070  1020  1128 V NetworkStats: performPollLocked(flags=0x1)
,08-26 19:45:48.070  1020  1128 D NetworkStatsFactory: UpdateStatsForKnox updated
08-26 19:45:48.070  1020  1128 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-26 19:45:48.070  1177  1177 D StatusBar.NetworkController: EthernetConnected: false
08-26 19:45:48.070  1177  1177 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-26 19:45:48.070  1177  1177 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-26 19:45:48.070  1177  1177 D StatusBar.NetworkController: updateDataNetType()
,08-26 19:45:48.070  1020  1129 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 19:45:48.080  1020  1128 V NetworkStats: performPollLocked() took 6ms
,08-26 19:45:48.080  1020  1129 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 19:45:48.080  1020  1129 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
08-26 19:45:48.080  1020  1129 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 19:45:48.080  1020  1129 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 19:45:48.080  6761  6987 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 19:45:48.080  6761  6987 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:45:48.080  6761  6987 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 19:45:48.080  6761  6987 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 19:45:48.080  6761  6987 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 19:45:48.080  6761  6987 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 19:45:48.080  6761  6987 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 19:45:48.080  6761  6987 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 19:45:48.080  1020  1128 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 19:45:48.080  4713  4713 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-26 19:45:48.080  4713  4713 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-26 19:45:48.080  1177  1177 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-26 19:45:48.080  1177  1177 E StatusBar.NetworkController: updateLTEICONDataNetType:0
08-26 19:45:48.080  4713  4713 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: CONNECTED
,08-26 19:45:48.080  4713  4713 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-26 19:45:48.080  1177  1177 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
08-26 19:45:48.080  6761  6987 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 19:45:48.080  1177  1177 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 20 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x4 gsm|lte
08-26 19:45:48.080  6761  6987 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 19:45:48.080  1177  1177 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=4
08-26 19:45:48.080  6761  6987 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 19:45:48.080  6761  6987 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e19c7bf added. We now have 3 listener(s)
,08-26 19:45:48.080  1177  1177 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_4 mContentDescriptionPhoneSignal = Full phone signal
08-26 19:45:48.080  1177  1177 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 19:45:48.080  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-26 19:45:48.080  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:45:48.080  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 19:45:48.080  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:45:48.080  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:45:48.080  4713  4713 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
08-26 19:45:48.080  4713  4713 I NearbySettings: MountReceiver.onReceive - Keep current state
,08-26 19:45:48.080  1020  1129 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 19:45:48.080  1020  1129 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 19:45:48.090  6761  6761 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 19:45:48.090  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
08-26 19:45:48.090  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 19:45:48.090  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 19:45:48.090  6761  6987 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 19:45:48.090  6761  6987 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18906e8c added. We now have 10 listener(s)
08-26 19:45:48.090  6761  6987 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 19:45:48.090  6761  6987 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 19:45:48.090  6761  6987 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 19:45:48.090  6761  6987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 19:45:48.090  6761  6987 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 19:45:48.090  6761  6987 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-26 19:45:48.090  6761  6761 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 19:45:48.090  6761  6987 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-26 19:45:48.100  6761  6987 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-26 19:45:48.100  1020  1487 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-26 19:45:48.100  6761  6987 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-26 19:45:48.100  1020  1487 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-26 19:45:48.100  1020  1487 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:45:48.100  1020  1487 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-26 19:45:48.100  1020  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-26 19:45:48.110  1627  1627 I Hs20UtilService: Starting #24
,08-26 19:45:48.110  1627  1661 I Hs20UtilService: Message received 5007
,08-26 19:45:48.110  6761  6987 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-26 19:45:48.110  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-26 19:45:48.110  6761  6987 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-26 19:45:48.110  4713  4713 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-26 19:45:48.110  4713  4713 I NearbySettings: MountReceiver.onReceive - Keep current state
,08-26 19:45:48.120  3176  3309 D BtGatt.GattService: registerClient() - UUID=13b0c2c2-2f3e-426d-b692-8e114ac2b53d
,08-26 19:45:48.120  1020  1258 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,08-26 19:45:48.120  1020  1033 D SecContentProvider2: uri = 15 selection = getToastGravityEnabledState
,08-26 19:45:48.120  1020  1033 D SecContentProvider2: mCursor = null
,08-26 19:45:48.120  1020  1513 D SecContentProvider2: uri = 15 selection = getToastGravity
,08-26 19:45:48.120  1020  1513 D SecContentProvider2: mCursor = null
,08-26 19:45:48.120  1020  4358 D SecContentProvider2: uri = 15 selection = getToastGravityXOffset
08-26 19:45:48.120  1020  4358 D SecContentProvider2: mCursor = null
,08-26 19:45:48.130  1020  4267 D SecContentProvider2: uri = 15 selection = getToastGravityYOffset
,08-26 19:45:48.130  1020  4267 D SecContentProvider2: mCursor = null
,08-26 19:45:48.130  1020  4359 D SecContentProvider2: uri = 15 selection = getToastEnabledState
,08-26 19:45:48.130  1020  4359 D SecContentProvider2: mCursor = null
,08-26 19:45:48.130  1020  1508 D SecContentProvider2: uri = 15 selection = getToastShowPackageNameState
08-26 19:45:48.130  1020  1508 D SecContentProvider2: mCursor = null
,08-26 19:45:48.150  1020  7687 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-26 19:45:48.160   258   258 I SurfaceFlinger: id=14 createSurf (1x1),1 flag=4, Uoast
,08-26 19:45:48.160  3176  3250 D BtGatt.GattService: onClientRegistered() - UUID=13b0c2c2-2f3e-426d-b692-8e114ac2b53d, clientIf=6
,08-26 19:45:48.160  6761  6776 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-26 19:45:48.160  3176  3185 D BtGatt.GattService: start scan with filters
,08-26 19:45:48.160  3176  3313 D BtGatt.ScanManager: handling starting scan
,08-26 19:45:48.160  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-26 19:45:48.160  6761  6987 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-26 19:45:48.160  3176  3250 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-26 19:45:48.160  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-26 19:45:48.160  3176  3250 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 19:45:48.160  6761  6987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-26 19:45:48.160  3176  3313 D BtGatt.ScanManager: allow scan with filters
,08-26 19:45:48.160  3176  3313 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,08-26 19:45:48.170  3176  3313 D BtGatt.ScanManager: set filter index= 8 for clientIf= 6
,08-26 19:45:48.170  3176  3250 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
08-26 19:45:48.170  3176  3250 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 19:45:48.170  3176  3313 D BtGatt.ScanManager: Starting BLE batch scan
08-26 19:45:48.170  3176  3313 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-26 19:45:48.170  3176  3250 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
08-26 19:45:48.170  3176  3250 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 19:45:48.170  6761  6987 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 19:45:48.170  6761  6987 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-26 19:45:48.170  6761  6761 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 19:45:48.170  3176  3250 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
08-26 19:45:48.170  3176  3250 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 19:45:48.180  6761  6987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-26 19:45:48.180  1020  1468 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1020
,08-26 19:45:48.180  6761  6987 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 19:45:48.190  6761  6987 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 19:45:48.190  6761  6987 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 19:45:48.190  6761  6987 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:45:48.190  6761  6987 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:48.190  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-26 19:45:48.190  6761  6987 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 19:45:48.190  6761  6987 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@918ec60 removed from the list
08-26 19:45:48.190  6761  6987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:45:48.190  6761  6987 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@29e21519 removed from the list
08-26 19:45:48.190  6761  6987 D io.jxcore.node.ConnectivityMonitor: stop
08-26 19:45:48.190  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 19:45:48.190  6761  6987 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:48.190  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-26 19:45:48.190  6761  6987 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:48.190  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 19:45:48.190  6761  6987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 19:45:48.190  6761  6987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:45:48.190  6761  6987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:45:48.190  6761  6987 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@29e21519 not in the list
08-26 19:45:48.190  6761  6987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-26 19:45:48.190  6761  6987 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 19:45:48.190  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-26 19:45:48.190  6761  6987 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-26 19:45:48.190  6761  6987 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-26 19:45:48.190  3176  3310 D BtGatt.GattService: stopScan() - queue size =1
,08-26 19:45:48.190  1177  1177 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,08-26 19:45:48.190  3176  3313 D BtGatt.ScanManager: filter size is 1
,08-26 19:45:48.190  3176  3313 D BtGatt.ScanManager: delete FilterIndex - 8
,08-26 19:45:48.190  3176  3184 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-26 19:45:48.190  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 19:45:48.190  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-26 19:45:48.190  6761  6987 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-26 19:45:48.190  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-26 19:45:48.190  6761  6987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-26 19:45:48.190  3176  3250 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-26 19:45:48.190  3176  3250 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
08-26 19:45:48.200  3176  3313 D BtGatt.ScanManager: stopping BLe Batch
08-26 19:45:48.200  6761  6987 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 19:45:48.200  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped,
08-26 19:45:48.200  6761  6987 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-26 19:45:48.200  6761  6987 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-26 19:45:48.200  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:48.200  3176  3250 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-26 19:45:48.200  3176  3250 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 19:45:48.200  3176  3313 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
08-26 19:45:48.200  6761  6761 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-26 19:45:48.200  6761  6761 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 19:45:48.200  6761  6761 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 19:45:48.200  6761  6987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:45:48.200  6761  6987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-26 19:45:48.200  6761  6987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:45:48.200  6761  6987 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18906e8c removed from the list
,08-26 19:45:48.200  6761  6987 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-26 19:45:48.200  6761  6987 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:48.200  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:48.200  6761  6987 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 19:45:48.200  6761  6987 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e19c7bf removed from the list
,08-26 19:45:48.200  6761  6987 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 19:45:48.200  6761  6987 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1e1be778 added. We now have 2 listener(s)
,08-26 19:45:48.210  3176  3250 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-26 19:45:48.210  3176  3250 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 19:45:48.210  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
08-26 19:45:48.210  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 19:45:48.210  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 19:45:48.210  6761  6987 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 19:45:48.210  6761  6987 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11384e51 added. We now have 9 listener(s)
08-26 19:45:48.210  6761  6987 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 19:45:48.210  6761  6987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-26 19:45:48.210  6761  6987 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 19:45:48.220  1020  7687 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 26 Aug 2016 17:45:48 GMT], X-Android-Received-Millis=[1472233548229], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472233548191]}
,08-26 19:45:48.220  1020  7687 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-26 19:45:48.220  1020  7687 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
08-26 19:45:48.220  1020  1133 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 504]
,08-26 19:45:48.220  1020  1133 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
08-26 19:45:48.220  1177  1763 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-26 19:45:48.220  1020  1133 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 504] was already satisfying request 1. No change.
08-26 19:45:48.220  1020  1133 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
08-26 19:45:48.220  1020  1133 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-26 19:45:48.220  6761  6987 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 19:45:48.220  6761  6987 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:45:48.220  6761  6987 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 19:45:48.220  6761  6987 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 19:45:48.220  6761  6987 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 19:45:48.220  6761  6987 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 19:45:48.220  6761  6987 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 19:45:48.220  6761  6987 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 19:45:48.220  6761  6987 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 19:45:48.220  6761  6987 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 19:45:48.220  6761  6987 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded,
08-26 19:45:48.220  6761  6987 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3452efb7 added. We now have 3 listener(s)
,08-26 19:45:48.220  6761  6761 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 19:45:48.230  6761  6761 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,08-26 19:45:48.230  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41",
08-26 19:45:48.230  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 19:45:48.230  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 19:45:48.230  6761  6987 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 19:45:48.230  6761  6987 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ae40324 added. We now have 10 listener(s)
08-26 19:45:48.230  6761  6987 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 19:45:48.230  6761  6987 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 19:45:48.230  6761  6987 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 19:45:48.230  6761  6987 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 19:45:48.230  6761  6987 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-26 19:45:48.230  6761  6987 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:48.230  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 19:45:48.230  6761  6987 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 19:45:48.230  6761  6987 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1e1be778 removed from the list
08-26 19:45:48.230  6761  6987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:45:48.230  6761  6987 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11384e51 removed from the list
08-26 19:45:48.230  6761  6987 D io.jxcore.node.ConnectivityMonitor: stop
08-26 19:45:48.230  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 19:45:48.230  6761  6987 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:48.230  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 19:45:48.230  6761  6987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 19:45:48.230  6761  6987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:45:48.230  6761  6987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:45:48.230  6761  6987 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11384e51 not in the list
08-26 19:45:48.230  6761  6987 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:48.230  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 19:45:48.230  1177  1177 D StatusBar.NetworkController: EthernetConnected: false
08-26 19:45:48.230  1177  1177 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-26 19:45:48.230  1177  1177 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-26 19:45:48.230  1177  1177 D StatusBar.NetworkController: updateDataNetType()
,08-26 19:45:48.230  6761  6987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:45:48.230  6761  6987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 19:45:48.230  6761  6987 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:45:48.230  6761  6987 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ae40324 removed from the list
08-26 19:45:48.230  6761  6987 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:45:48.230  6761  6987 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:48.230  6761  6987 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:48.230  6761  6987 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 19:45:48.230  6761  6987 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3452efb7 removed from the list
,08-26 19:45:48.240  6761  6987 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,08-26 19:45:48.240  6761  6987 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-26 19:45:48.240  6761  6987 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-26 19:45:48.240  6761  6987 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 19:45:48.240  6761  6987 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-26 19:45:48.240  6761  6987 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-26 19:45:48.240  1177  1177 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-26 19:45:48.240  1177  1177 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,08-26 19:45:48.240  1177  1177 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,08-26 19:45:48.240  1177  1177 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 20 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x4 gsm|lte
,08-26 19:45:48.240  1177  1177 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=4
08-26 19:45:48.240  1177  1177 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_4 mContentDescriptionPhoneSignal = Full phone signal
,08-26 19:45:48.240  1177  1177 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-26 19:45:48.240  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,08-26 19:45:48.250  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 19:45:48.250  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:45:48.250  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 19:45:48.250  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 19:45:48.260  6761  7726 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1378, name: My test thread name)
08-26 19:45:48.260  6761  7726 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1378, thread name: My test thread name)
08-26 19:45:48.260  6761  7726 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1378, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-26 19:45:48.280  6761  7727 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1380, name: My test thread name)
,08-26 19:45:48.280  6761  7727 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1380, thread name: My test thread name)
08-26 19:45:48.280  6761  7727 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1380, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-26 19:45:48.280  6761  6987 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-26 19:45:48.280  6761  6987 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-26 19:45:48.280  6761  6987 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-26 19:45:48.280  6761  6987 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-26 19:45:48.280  6761  6987 D com.test.thalitest.ThaliTestRunner: Total duration: 23383 ms
,08-26 19:45:48.280  6761  6987 I jxcore-log: *Native tests were executed*
08-26 19:45:48.280  6761  6987 I jxcore-log: 
,08-26 19:45:48.280  6761  6987 I jxcore-log: Total number of executed tests:  80
08-26 19:45:48.280  6761  6987 I jxcore-log: 
08-26 19:45:48.280  6761  6987 I jxcore-log: Number of passed tests:  80
08-26 19:45:48.280  6761  6987 I jxcore-log: 
08-26 19:45:48.280  6761  6987 I jxcore-log: Number of failed tests:  0
08-26 19:45:48.280  6761  6987 I jxcore-log: 
08-26 19:45:48.280  6761  6987 I jxcore-log: Number of ignored tests:  0
08-26 19:45:48.280  6761  6987 I jxcore-log: 
,08-26 19:45:48.280  6761  6987 I jxcore-log: Total duration:  23383
08-26 19:45:48.280  6761  6987 I jxcore-log: 
08-26 19:45:48.280  6761  6987 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-26 19:45:48.280  6761  6987 I jxcore-log: 
,08-26 19:45:48.280  6761  6987 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 19:45:48.280  6761  6987 I jxcore-log: 
08-26 19:45:48.290  6761  6761 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-26 19:45:48.290  6761  6987 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 19:45:48.290  6761  6987 I jxcore-log: 
08-26 19:45:48.290  6761  6987 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 19:45:48.290  6761  6987 I jxcore-log: 
08-26 19:45:48.290  6761  6987 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 19:45:48.290  6761  6987 I jxcore-log: 
08-26 19:45:48.290  6761  6987 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 19:45:48.290  6761  6987 I jxcore-log: 
08-26 19:45:48.300  6761  6987 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 19:45:48.300  6761  6987 I jxcore-log: 
,08-26 19:45:48.300  6761  6770 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2383347e, channel: -1, state: CLOSED
,08-26 19:45:48.300  6761  6987 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 19:45:48.300  6761  6987 I jxcore-log: 
,08-26 19:45:48.300  6761  6987 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 19:45:48.300  6761  6987 I jxcore-log: 
,08-26 19:45:48.300  6761  6987 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 19:45:48.300  6761  6987 I jxcore-log: 
,08-26 19:45:48.310  6761  6987 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-26 19:45:48.310  6761  6987 I jxcore-log: 
,08-26 19:45:48.310  6761  6987 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-26 19:45:48.310  6761  6987 I jxcore-log: 
,08-26 19:45:48.310  6761  6987 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-26 19:45:48.310  6761  6987 I jxcore-log: 
,08-26 19:45:48.310  6761  6987 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 19:45:48.310  6761  6987 I jxcore-log: 
,08-26 19:45:48.310  6761  6987 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"},
08-26 19:45:48.310  6761  6987 I jxcore-log: 
,08-26 19:45:48.310  6761  6987 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-26 19:45:48.310  6761  6987 I jxcore-log: 
,08-26 19:45:48.310  6761  6987 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-26 19:45:48.310  6761  6987 I jxcore-log: 
,08-26 19:45:48.310  6761  6987 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 19:45:48.310  6761  6987 I jxcore-log: 
,08-26 19:45:48.310  6761  6987 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
,08-26 19:45:48.310  6761  6987 I jxcore-log: 
,08-26 19:45:48.310  6761  6987 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
,08-26 19:45:48.310  6761  6987 I jxcore-log: 
08-26 19:45:48.320  6761  6987 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"},
08-26 19:45:48.320  6761  6987 I jxcore-log: 
08-26 19:45:48.320  6761  6987 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"},
08-26 19:45:48.320  6761  6987 I jxcore-log: 
,08-26 19:45:48.320  6761  6987 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-26 19:45:48.320  6761  6987 I jxcore-log: 
,08-26 19:45:48.320  6761  6987 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-26 19:45:48.320  6761  6987 I jxcore-log: 
,08-26 19:45:48.320  6761  6987 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-26 19:45:48.320  6761  6987 I jxcore-log: 
,08-26 19:45:48.320  6761  6987 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-26 19:45:48.320  6761  6987 I jxcore-log: ,
,08-26 19:45:48.320  6761  6987 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 19:45:48.320  6761  6987 I jxcore-log: 
,08-26 19:45:48.320  6761  6987 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 19:45:48.320  6761  6987 I jxcore-log: 
,08-26 19:45:48.330  6761  6761 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-26 19:45:48.330  6761  6987 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false},
08-26 19:45:48.330  6761  6987 I jxcore-log: 
,08-26 19:45:48.490  1020  4357 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
08-26 19:45:48.490  1020  4357 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4292, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-26 19:45:48.490  1020  4357 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-26 19:45:48.490  1020  4357 D BatteryService: stay LED for charging
08-26 19:45:48.490  1020  1020 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 19:45:48.500  1020  1020 I MotionRecognitionService: Plugged
08-26 19:45:48.500  1020  1020 I MotionRecognitionService: mGripSensorEnabled= false
,08-26 19:45:48.500  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-26 19:45:48.500  1177  1177 D KeyguardUpdateMonitor: handleBatteryUpdate
08-26 19:45:48.500  1425  1425 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-26 19:45:48.500  1425  1425 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-26 19:45:48.510  3176  3176 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 19:45:48.510  3176  7649 D HeadsetStateMachine: Disconnected process message: 10
,08-26 19:45:48.520  1177  1177 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-26 19:45:48.520  1177  1177 D SViewCoverView: level :100 plugged : 2
,08-26 19:45:48.520  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 19:45:48.520  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 19:45:48.520  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 19:45:48.550  6761  6761 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-26 19:45:48.550  6761  6987 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-26 19:45:48.550  6761  6987 I jxcore-log: 
,08-26 19:45:48.570  1020  1133 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-26 19:45:48.570  7728  7728 D AndroidRuntime: 
08-26 19:45:48.570  7728  7728 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-26 19:45:48.570  7728  7728 D AndroidRuntime: CheckJNI is OFF
,08-26 19:45:48.570  7728  7728 D AndroidRuntime: readGMSProperty: start
08-26 19:45:48.570  7728  7728 D AndroidRuntime: readGMSProperty: already setted!!
08-26 19:45:48.570  7728  7728 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-26 19:45:48.570  7728  7728 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-26 19:45:48.570  7728  7728 D AndroidRuntime: readGMSProperty: end
08-26 19:45:48.570  7728  7728 D AndroidRuntime: addProductProperty: start
,08-26 19:45:48.580  1020  1046 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-26 19:45:48.590  1020  1047 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,08-26 19:45:48.590  1020  1047 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:45:48.590  1020  1047 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:45:48.590  1020  1047 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:45:48.590  1020  1047 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 19:45:48.600  6761  6761 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 19:45:48.600  6761  6761 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:45:48.600  6761  6761 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 19:45:48.600  6761  6761 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 19:45:48.600  6761  6761 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 19:45:48.600  6761  6761 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 19:45:48.600  6761  6761 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 19:45:48.600  6761  6761 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 19:45:48.600  6761  6761 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 19:45:48.600  6761  6987 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 19:45:48.600  6761  6987 I jxcore-log: 
,08-26 19:45:48.600  7730  7730 E Zygote  : MountEmulatedStorage()
,08-26 19:45:48.600  7730  7730 E Zygote  : v2
08-26 19:45:48.600  7730  7730 I libpersona: KNOX_SDCARD checking this for 1000
08-26 19:45:48.600  7730  7730 I libpersona: KNOX_SDCARD not a persona
,08-26 19:45:48.600  1020  1047 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7730 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-26 19:45:48.610  7730  7730 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 19:45:48.610  7730  7730 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-26 19:45:48.610  7730  7730 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,08-26 19:45:48.630  7730  7730 D TimaKeyStoreProvider: TimaSignature is unavailable,
08-26 19:45:48.630  7730  7730 D ActivityThread: Added TimaKeyStore provider
,08-26 19:45:48.670  7730  7730 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
,08-26 19:45:48.670  7730  7730 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
08-26 19:45:48.670  7730  7730 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,08-26 19:45:48.690  7730  7730 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
08-26 19:45:48.690  7730  7730 I PCWCLIENTTRACE_PushUtil: sales region : global
08-26 19:45:48.690  7730  7730 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
08-26 19:45:48.690  7730  7730 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,08-26 19:45:48.690  1020  1471 I splitIntent: intent=android.net.conn.CONNECTIVITY_CHANGE will be not split. because same process=com.google.android.gms is in other queue. index=7
,08-26 19:45:48.690  1020  1471 I splitIntent: base  index=7, name=com.google.android.gms com.google.android.gms.gcm.gmsproc.GmsAutoStarter
08-26 19:45:48.690  1020  1471 I splitIntent: other index=9, name=com.google.android.gms com.google.android.gms.wearable.service.AutoStarterReceiver
08-26 19:45:48.690  1020  1471 I splitIntent: arrangeSplitReceiver return false!! intent : android.net.conn.CONNECTIVITY_CHANGE !! do not split it!!
08-26 19:45:48.690  1020  1471 I ActivityManager: Killing 7240:com.sec.android.diagmonagent/1000 (adj 15): empty #21
,08-26 19:45:48.700  6761  6761 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-26 19:45:48.700  6761  6987 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-26 19:45:48.700  6761  6987 I jxcore-log: 
,08-26 19:45:48.700  1020  1020 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,08-26 19:45:48.700  1020  1020 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:45:48.700  1020  1020 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:45:48.700  1020  1020 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:45:48.700  1020  1020 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 19:45:48.710  7728  7728 E AffinityControl: AffinityControl: registerfunction enter
08-26 19:45:48.720  7752  7752 E Zygote  : MountEmulatedStorage()
08-26 19:45:48.720  7752  7752 E Zygote  : v2
08-26 19:45:48.720  7752  7752 I libpersona: KNOX_SDCARD checking this for 10001
08-26 19:45:48.720  7752  7752 I libpersona: KNOX_SDCARD not a persona
08-26 19:45:48.720  7752  7752 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-26 19:45:48.720  7752  7752 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 19:45:48.720  1020  1020 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7752 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-26 19:45:48.720  7752  7752 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 19:45:48.740  7728  7728 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-26 19:45:48.750  7752  7752 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 19:45:48.750  7752  7752 D ActivityThread: Added TimaKeyStore provider,
,08-26 19:45:48.770  1020  4266 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
08-26 19:45:48.770  1020  4266 D PackageManager: START PACKAGE DELETE: observer{283646819}
08-26 19:45:48.770  1020  4266 D PackageManager: pkg{<packageName>}
08-26 19:45:48.770  1020  4266 D PackageManager: user{0}
08-26 19:45:48.770  1020  4266 D PackageManager: caller{2000}
08-26 19:45:48.770  1020  4266 D PackageManager: flags{2}
,08-26 19:45:48.770  1020  4266 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
08-26 19:45:48.780  1020  1061 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
08-26 19:45:48.770  1020  4266 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
08-26 19:45:48.770  1020  4266 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-26 19:45:48.770  1020  4266 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-26 19:45:48.780  1020  1061 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
,08-26 19:45:48.780  1020  1061 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
08-26 19:45:48.780  1020  1061 D ApplicationPolicy: getApplicationUninstallationEnabled
08-26 19:45:48.780  1020  1061 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,08-26 19:45:48.780  1020  1061 D PackageManager: !@killApplicatoin: 10170, uninstall pkg
,08-26 19:45:48.790  1020  1047 I ActivityManager: Force stopping com.test.thalitest appid=10170 user=-1: uninstall pkg
,08-26 19:45:48.790  1020  1047 I ActivityManager: Killing 6761:com.test.thalitest/u0a170 (adj 0): stop com.test.thalitest cause uninstall pkg
,08-26 19:45:48.790  1020  1047 I ActivityManager:   Force finishing activity ActivityRecord{5850a69 u0 com.test.thalitest/.MainActivity t163}
,08-26 19:45:48.800  1020  1047 D InputDispatcher: Focus left window: 6761
,08-26 19:45:48.800   258   427 I SurfaceFlinger: id=13 Removed NainActivit (6/9)
,08-26 19:45:48.800   258  6129 I SurfaceFlinger: id=13 Removed NainActivit (-2/9)
,08-26 19:45:48.820  1020  1047 D InputDispatcher: Focused application released
,08-26 19:45:48.820  1020  1052 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-26 19:45:48.820  1020  1052 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-26 19:45:48.900  1020  1061 I ActivityManager: Force stopping com.test.thalitest appid=10170 user=0: pkg removed
,08-26 19:45:48.910  1020  1061 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,08-26 19:45:48.940  2805  2805 I art     : Explicit concurrent mark sweep GC freed 24342(1319KB) AllocSpace objects, 4(64KB) LOS objects, 49% free, 4MB/8MB, paused 859us total 31.339ms
,08-26 19:45:48.940  1806  2046 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-26 19:45:48.940  1879  1879 E SamsungIME: mOCRHelper is null
,08-26 19:45:48.950  1020  1103 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-26 19:45:48.970  1455  1455 D PersonaManager: isKioskContainerExistOnDevice
,08-26 19:45:48.980  1020  1046 D EnterpriseDeviceManagerService: Package has changed for user 0
08-26 19:45:48.980  1020  1046 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
08-26 19:45:48.980  1020  1046 W TextServicesManagerService: no available spell checker services found
,08-26 19:45:48.980  1020  1046 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-26 19:45:48.990  1020  1046 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-26 19:45:49.010  1020  1128 V NetworkStats: removeUidsLocked() for UIDs [10170]
08-26 19:45:49.010  1020  1128 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 19:45:49.010  1020  1128 V NetworkStats: performPollLocked(flags=0x3)
,08-26 19:45:49.010  1020  1128 D NetworkStatsFactory: UpdateStatsForKnox updated
,08-26 19:45:49.010  1455  1455 D RegisteredServicesCache: empty dynamic service
08-26 19:45:49.010  1020  1128 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-26 19:45:49.010  1020  1020 D RCPManagerService: PackageReceiver onReceive()
,08-26 19:45:49.010  1020  1128 V NetworkStats: performPollLocked() took 6ms
08-26 19:45:49.010  1020  1128 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 19:45:49.020  1020  1020 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,08-26 19:45:49.020  1020  1471 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,08-26 19:45:49.020  1020  1471 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 19:45:49.020  1020  1471 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:45:49.020  1020  1471 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 19:45:49.020  1020  1471 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 19:45:49.030  1020  1020 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
08-26 19:45:49.030  1020  1020 I OTPFW   : PackageRemovalReceiver::onReceive Enter
08-26 19:45:49.030  1020  1046 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-26 19:45:49.030  1020  1020 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10170 container id = 0
,08-26 19:45:49.040  1020  1046 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
,08-26 19:45:49.040  1020  1129 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 19:45:49.040  1020  1129 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 19:45:49.040  7773  7773 E Zygote  : MountEmulatedStorage()
08-26 19:45:49.040  7773  7773 E Zygote  : v2
08-26 19:45:49.040  7773  7773 I libpersona: KNOX_SDCARD checking this for 1000
08-26 19:45:49.040  7773  7773 I libpersona: KNOX_SDCARD not a persona
,08-26 19:45:49.040  7773  7773 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 19:45:49.040  1020  1020 I OTPFW   : ProvisionData::getAllEntries Enter,
08-26 19:45:49.050  1020  1471 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7773 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-26 19:45:49.050  7773  7773 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-26 19:45:49.050  1020  1471 I ActivityManager: Killing 7255:com.sec.android.fotaclient/u0a8 (adj 15): empty #21
,08-26 19:45:49.050  7773  7773 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 19:45:49.050  1455  1455 D RegisteredComponentCache: Collect Tech packages for Knox
08-26 19:45:49.050  1455  1455 D PersonaManager: isKioskContainerExistOnDevice
,08-26 19:45:49.070  1020  1133 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
08-26 19:45:49.070  1020  1020 E OTPFW   : ProvisionData::getAllEntries Table is empty
,08-26 19:45:49.080  1020  4357 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
08-26 19:45:49.080  1020  4357 D SecContentProvider2: mCursor = null
,08-26 19:45:49.110  7773  7773 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 19:45:49.110  7773  7773 D ActivityThread: Added TimaKeyStore provider
,08-26 19:45:49.160  1020  1046 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,08-26 19:45:49.160  1020  1046 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-26 19:45:49.160  1020  1046 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-26 19:45:49.170  1020  1046 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-26 19:45:49.180  1020  1061 I art     : Explicit concurrent mark sweep GC freed 70896(4MB) AllocSpace objects, 10(160KB) LOS objects, 33% free, 23MB/34MB, paused 2.851ms total 216.417ms
,08-26 19:45:49.180  7773  7773 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,08-26 19:45:49.200  1020  1046 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-26 19:45:49.200  1020  1046 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-26 19:45:49.200  1020  1046 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-26 19:45:49.200  1020  1046 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-26 19:45:49.250  1020  1046 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-26 19:45:49.260  1020  1046 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-26 19:45:49.260  1020  1046 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-26 19:45:49.260  1020  1046 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-26 19:45:49.260  1020  1046 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-26 19:45:49.280  1020  1020 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,08-26 19:45:49.280  1020  1020 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-26 19:45:49.280  1020  1020 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
08-26 19:45:49.280  1020  1020 V EnterpriseBillingPolicy: uID is 10170
08-26 19:45:49.280  1020  1020 V EnterpriseBillingPolicy: Removed Packageuid is0
08-26 19:45:49.280  1020  1020 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,08-26 19:45:49.290  1020  1061 D PackageManager: delete codoeFile: 
,08-26 19:45:49.290  1020  1020 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-26 19:45:49.290  1020  1020 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-26 19:45:49.290  1020  1020 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-26 19:45:49.290  1020  1020 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,08-26 19:45:49.290  1020  1020 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,08-26 19:45:49.290  1020  1046 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-26 19:45:49.290  1020  1046 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-26 19:45:49.290  1020  1020 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,08-26 19:45:49.290  1020  1020 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
,08-26 19:45:49.290  1020  1046 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-26 19:45:49.290  1020  1046 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-26 19:45:49.290  1020  1046 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-26 19:45:49.300  1020  1165 D TaskPersister: removeObsoleteFile: deleting file=163_task.xml
08-26 19:45:49.300  1020  1061 D AASAuninstall: userId = 0, info.removedAppID = 10170, info.uid = 10170, packageName = com.test.thalitest
08-26 19:45:49.300  1020  1046 D UsbSettingsManager: clearDefaults: com.test.thalitest
08-26 19:45:49.300  1020  1046 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
08-26 19:45:49.300  1020  1061 I AASA_removePackage: UID=10170 Target=com.test.thalitest
,08-26 19:45:49.300  1020  3320 D SSRM:bc : MSG_TYPE_APP_REMOVED::
,08-26 19:45:49.300  1020  1061 D PackageManager: result of delete: 1{283646819}
,08-26 19:45:49.300  1020  1020 V EnterpriseBillingPolicy: uID is 10170
08-26 19:45:49.300  1020  1020 V EnterpriseBillingPolicy: Removed Packageuid is0
08-26 19:45:49.300  1020  1020 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,08-26 19:45:49.310  1020  1020 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-26 19:45:49.310  1020  1020 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-26 19:45:49.310  1020  1020 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-26 19:45:49.310  1020  1020 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
08-26 19:45:49.310  1020  1020 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
08-26 19:45:49.310  7728  7728 D AndroidRuntime: Shutting down VM
08-26 19:45:49.310  1020  1020 V AlarmManagerEXT: com.test.thalitest(10170) is removed.
,08-26 19:45:49.340  7773  7773 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,08-26 19:45:49.350  7773  7773 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,08-26 19:45:49.350  7773  7773 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,08-26 19:45:49.350  7773  7773 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
08-26 19:45:49.350  7773  7773 I DIAGMON_AGENT: ./extraInfo: "NG700"
,08-26 19:45:49.350  7773  7773 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,08-26 19:45:49.400   295   295 E SMD     : DCD OFF,
,08-26 19:45:49.430  1020  1491 D ActivityManager: getContentProviderImpl callerProcessName:com.sec.android.diagmonagent, calleePkgName: com.sec.android.fotaclient
,08-26 19:45:49.430  1020  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 19:45:49.430  1020  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:45:49.430  1020  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 19:45:49.430  1020  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 19:45:49.440  7790  7790 E Zygote  : MountEmulatedStorage(),
,08-26 19:45:49.450  7790  7790 E Zygote  : v2
,08-26 19:45:49.450  7790  7790 I libpersona: KNOX_SDCARD checking this for 10008
08-26 19:45:49.450  7790  7790 I libpersona: KNOX_SDCARD not a persona
,08-26 19:45:49.450  7790  7790 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 19:45:49.450  1020  1491 I ActivityManager: Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=7790 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-26 19:45:49.450  7790  7790 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 19:45:49.450  7790  7790 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,08-26 19:45:49.470  7790  7790 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 19:45:49.470  7790  7790 D ActivityThread: Added TimaKeyStore provider
,08-26 19:45:49.480   323   323 I art     : Explicit concurrent mark sweep GC freed 8702(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 719us total 26.926ms
,08-26 19:45:49.500   323   323 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 762us total 19.596ms
,08-26 19:45:49.510  7728  7728 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.,
,08-26 19:45:49.520   323   323 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 834us total 21.873ms
,08-26 19:45:49.530  1020  1061 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
08-26 19:45:49.530  1020  1061 D PackageManager: userId{-1}
08-26 19:45:49.530  1020  1061 D PackageManager: andCode{true}
,08-26 19:45:49.530  1020  1061 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,08-26 19:45:49.530  1020  1061 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 19:45:49.530  1020  1061 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:45:49.530  1020  1061 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 19:45:49.530  1020  1061 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 19:45:49.550  7805  7805 E Zygote  : MountEmulatedStorage()
,08-26 19:45:49.550  7805  7805 E Zygote  : v2
,08-26 19:45:49.550  7805  7805 I libpersona: KNOX_SDCARD checking this for 10003
08-26 19:45:49.550  7805  7805 I libpersona: KNOX_SDCARD not a persona
,08-26 19:45:49.550  7805  7805 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-26 19:45:49.560  1020  1061 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=7805 uid=10003 gids={50003, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,08-26 19:45:49.570  7805  7805 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-26 19:45:49.570  7805  7805 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 19:45:49.580  1020  1082 I ActivityManager: Killing 7298:com.sec.android.soagent/u0a31 (adj 15): empty #21
,08-26 19:45:49.590  7790  7790 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,08-26 19:45:49.600  7790  7790 I FOTA_Client: [com.sec.android.fotaclient.FotaUpdaterReceiver(93/onReceive)] Auto update settings is activated
,08-26 19:45:49.600  7790  7790 I FOTA_Client: [IlIlIIllllIllIIIIIll(81/llllIIIllIlIIIIllllI)] Polling time is vaild
,08-26 19:45:49.610  7790  7790 W FOTA_Client: [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,08-26 19:45:49.610  7805  7805 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 19:45:49.610  7805  7805 D ActivityThread: Added TimaKeyStore provider
,08-26 19:45:49.660  1020  1468 I ActivityManager: Killing 7314:com.sec.spp.push/u0a32 (adj 15): empty #21
,08-26 19:45:49.660  1020  4358 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
08-26 19:45:49.660  1020  4358 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,08-26 19:45:49.660  1020  4358 W ActivityManager: userId = 0, bbcId = -10000
,08-26 19:45:49.660  1020  4358 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 19:45:49.660  1020  4358 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,08-26 19:45:49.680   278  1002 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-26 19:45:49.680   278  1002 D Netd    : getNetworkForDns: using netid 504 for uid 10011

```
