#### Test 627544039ea0a99_thali07_samsung-SM-A500FU Logs


```
--------- beginning of main
03-17 12:55:46.623  3214  3214 D elm:15183: ELMAbstractReceiver : Receive Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
03-17 12:55:46.623  3214  3214 D elm:15183: ElmAgentService : onCreate()
03-17 12:55:46.623  3214  3232 D elm:15183: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
03-17 12:55:46.623  3214  3214 D elm:15183: ELMEngine.ServiceHandler.handleMessage( BOOT_COMPLETED ). 
03-17 12:55:46.623  3214  3214 D elm:15183: BootCompletedState : startBootCompleted() call
03-17 12:55:46.623  3214  3214 D elm:15183: MDMBridge.getAllLicenseInfoFromSDK()
--------- beginning of system
03-17 12:55:46.623  1434  1434 V EmergencyMode: [EmergencyReceiver] EmergencyReceiver [android.intent.action.BOOT_COMPLETED]
03-17 12:55:46.633  3214  3214 I elm:15183: Get License : 0
03-17 12:55:46.633  3108  3108 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.intent.action.BOOT_COMPLETED
03-17 12:55:46.633  3214  3214 D elm:15183: ElmAgentService : onDestroy().
03-17 12:55:46.633  3108  3108 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
03-17 12:55:46.633  3108  3108 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(68/lllIlIlIIIllIIlIllIl)] Running with BootCompletedReceiver adapter
03-17 12:55:46.633  3108  3108 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
03-17 12:55:46.633  1022  1515 I ActivityManager: Killing 2356:com.sec.android.app.SecSetupWizard/1000 (adj 15): empty #31
03-17 12:55:46.683  1022  3133 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:46.683  1022  3133 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:46.683  1022  3133 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:46.683  1022  3133 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:46.703  3164  3164 I DBG_DM  : [com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI(2693/lllIlIlIIIllIIlIllIl)] xdbsqlGetFUMOStatus : 220
03-17 12:55:46.703  3239  3239 E Zygote  : MountEmulatedStorage()
03-17 12:55:46.703  3239  3239 E Zygote  : v2
03-17 12:55:46.703  3239  3239 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-17 12:55:46.703  3239  3239 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-17 12:55:46.703  3239  3239 I libpersona: KNOX_SDCARD checking this for 1000
03-17 12:55:46.703  3239  3239 I libpersona: KNOX_SDCARD not a persona
03-17 12:55:46.703  1022  3133 I ActivityManager: Start proc com.policydm for content provider com.policydm/com.sec.android.policydm.log.MasterLogProvider: pid=3239 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-17 12:55:46.713  3239  3239 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 12:55:46.713  3164  3164 I DBG_DM  : [com.wssyncmldm.XDMApplication(80/onCreate)] XDMApplication Start ! - Fumo State
03-17 12:55:46.713  1022  1034 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:55:46.713  1022  1034 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-17 12:55:46.713  1022  1034 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.wssyncmldm, destAppInfo.processName = com.wssyncmldm
03-17 12:55:46.713  1022  1046 W libprocessgroup: failed to open /acct/uid_1000/pid_2356/cgroup.procs: No such file or directory
03-17 12:55:46.713  3164  3164 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 com.wssyncmldm.XDMApplication.onCreate:81 android.app.Instrumentation.callApplicationOnCreate:1020 android.app.ActivityThread.handleBindApplication:5256 
03-17 12:55:46.713  1022  1034 D ActivityManager: retrieveServiceLocked(): component = com.wssyncmldm/com.wssyncmldm.XDMService; callingUser = 0; userId(target) = 0
03-17 12:55:46.723  3164  3164 I DBG_DM  : [com.wssyncmldm.XDMBroadcastReceiver(152/onReceive)] android.intent.action.BOOT_COMPLETED
03-17 12:55:46.723  3164  3164 I DBG_DM  : [com.wssyncmldm.XDMService(1598/IlIlllIIlIlIIIlIlIll)] 
03-17 12:55:46.733  3164  3164 I DBG_DM  : [com.wssyncmldm.XDMService(1603/IlIlllIIlIlIIIlIlIll)] m_WakeLock is acquire!!
03-17 12:55:46.733  1191  1191 D OverheatReceiver: onReceive() getAction : android.intent.action.BOOT_COMPLETED
03-17 12:55:46.733  1191  1191 D OverheatReceiver: into the SAFE_MODE_ACTION
03-17 12:55:46.733  1191  1191 D OverheatReceiver: VZW on -> change to Global UX [safe mode]
03-17 12:55:46.733  1191  1191 D OverheatReceiver: isSafeMode = false
03-17 12:55:46.733  1434  1434 V EmergencyMode: [EmergencyBase] setBootTime
03-17 12:55:46.733  1434  1434 V EmergencyMode: [EmergencyFactory] No Recovery State, kill my self.
03-17 12:55:46.743  3164  3164 I DBG_DM  : [com.wssyncmldm.XDMService(1420/lllIlIlIIIllIIlIllIl)] 0
03-17 12:55:46.743  1022  1361 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:46.743  1022  1361 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:46.743  1022  1361 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:46.743  1022  1361 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:46.743  3164  3164 I DBG_DM  : [IIlIIIlllllIIlIIIlII(232/llllIllIIIIIlIIllIII)] Default - NO_ROOTING_CHECK : false
03-17 12:55:46.743  3164  3164 I DBG_DM  : [com.wssyncmldm.XDMService(1463/llIlIIIIlIIIIIlIlIII)] 0
03-17 12:55:46.743  1494  1494 D BootupListener: intent.getAction() = android.intent.action.BOOT_COMPLETED
03-17 12:55:46.743  1022  1518 D SettingsProvider: name = internet_call_settings_visibility
03-17 12:55:46.743  3164  3164 I DBG_DM  : [IIlIIIlllllIIlIIIlII(261/IIllIlIIIIlIIIllIllI)] Roaming Check : true
03-17 12:55:46.743  1022  1518 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-17 12:55:46.743  1022  1518 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-17 12:55:46.743  1022  1518 D SettingsProvider: selectionArgs: false
03-17 12:55:46.743  1022  1518 D SettingsProvider: selectionArgs: 1001
03-17 12:55:46.743  1022  1518 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-17 12:55:46.743  1022  1518 D SettingsProvider: ret = -1
03-17 12:55:46.743  1494  1494 D PhoneUtilsCommon: isSupportVoLTE is false.
03-17 12:55:46.743  3239  3239 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 12:55:46.743  3164  3164 I DBG_DM  : [com.wssyncmldm.XDMService(1548/llIIllllIIlllIIIIlll)] 0
03-17 12:55:46.743  3239  3239 D ActivityThread: Added TimaKeyStore provider
03-17 12:55:46.743  3164  3164 I DBG_DM  : [IIlIIIlllllIIlIIIlII(293/llIIlIlIlIlIIIIIIlIl)] validation Check On
03-17 12:55:46.743  3164  3164 I DBG_DM  : [com.wssyncmldm.XDMService(1505/IllIlIIIIlIIlIIIllIl)] 0
03-17 12:55:46.753  3164  3164 I DBG_DM  : [IIlIIIlllllIIlIIIlII(274/lllllllIlllIIlllIlIl)] SSL Check On
03-17 12:55:46.753  3164  3164 I DBG_DM  : [llIIlIIlIllIllIlllII(109/llllIIIllIlIIIIllllI)] 
03-17 12:55:46.753  3164  3206 I DBG_DM  : [IlIIlIIlIllllIlllIII(181/llIIIIlllllIIllIIllI)] XEVENT_OS_INITIALIZED
03-17 12:55:46.753  3164  3164 I DBG_DM  : [llIIlIIlIllIllIlllII(397/llIIIIlllllIIllIIllI)] External SD Card Path : /storage/extSdCard
03-17 12:55:46.763  3164  3164 I DBG_DM  : [llIIlIIlIllIllIlllII(166/llllIIIllIlIIIIllllI)] bExternalStorageAvailable [true]
03-17 12:55:46.763  3164  3206 I DBG_DM  : [llIlIIIIlllIlllllIll(142/llIIIIlllllIIllIIllI)] nSync = 0
03-17 12:55:46.763  3164  3164 I DBG_DM  : [llIIlIIlIllIllIlllII(167/llllIIIllIlIIIIllllI)] bExternalSDStorageAvailable [false]
03-17 12:55:46.763  3164  3164 I DBG_DM  : [com.wssyncmldm.XDMService(1624/IIlIlIIlIlIIlIlllIIl)] 
03-17 12:55:46.763  3164  3164 I DBG_DM  : [com.wssyncmldm.XDMService(1629/IIlIlIIlIlIIlIlllIIl)] m_WakeLock is release!!
03-17 12:55:46.763  3164  3164 I DBG_DM  : [com.wssyncmldm.XDMService(155/onStartCommand)] 
03-17 12:55:46.773  3256  3256 E Zygote  : MountEmulatedStorage()
03-17 12:55:46.773  3164  3206 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.wssyncmldm.ui.lIlIIlIlIlIllllllIII.lllIlIlIIIllIIlIllIl:72 com.wssyncmldm.ui.lIlIIlIlIlIllllllIII.llIIIIlllllIIllIIllI:112 IlIIlIIlIllllIlllIII.llIIIIlllllIIllIIllI:185 
03-17 12:55:46.773  3256  3256 E Zygote  : v2
03-17 12:55:46.773  3256  3256 I libpersona: KNOX_SDCARD checking this for 1000
03-17 12:55:46.773  3256  3256 I libpersona: KNOX_SDCARD not a persona
03-17 12:55:46.773  3256  3256 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-17 12:55:46.773  3256  3256 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-17 12:55:46.773  1022  1361 I ActivityManager: Start proc com.sec.factory.camera for broadcast com.sec.factory.camera/com.sec.android.app.camerafirmware.CameraFirmwareBroadCastReceiver: pid=3256 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-17 12:55:46.773  3256  3256 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 12:55:46.773  1022  1034 D ActivityManager: retrieveServiceLocked(): component = com.wssyncmldm/com.wssyncmldm.XDMService; callingUser = 0; userId(target) = 0
03-17 12:55:46.783  1022  1034 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:55:46.783  1022  1034 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 12:55:46.783  1022  1034 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.wssyncmldm, destAppInfo.processName = com.wssyncmldm
03-17 12:55:46.803  1464  1464 I Telecom : InCallController: Attempting to bind to InCall com.android.incallui, is dupe? false 
03-17 12:55:46.803  1022  1234 D ActivityManager: retrieveServiceLocked(): component = com.android.incallui/com.android.incallui.InCallServiceImpl; callingUser = 0; userId(target) = -2
03-17 12:55:46.813  1022  1234 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:55:46.813  1022  1234 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 12:55:46.813  1022  1234 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.incallui
03-17 12:55:46.813  3256  3256 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 12:55:46.813  3256  3256 D ActivityThread: Added TimaKeyStore provider
03-17 12:55:46.813  3164  3164 I DBG_DM  : [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
03-17 12:55:46.823  1464  1464 I Telecom : InCallController: Attempting to bind to InCall com.google.android.gms, is dupe? false 
03-17 12:55:46.823  1022  1035 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.car.InCallServiceImpl; callingUser = 0; userId(target) = -2
03-17 12:55:46.823  1022  1035 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:55:46.823  1022  1035 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
03-17 12:55:46.823  1022  1035 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.google.android.gms
03-17 12:55:46.823  1022  1035 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:46.823  1022  1035 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:46.823  1022  1035 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:46.823  1022  1035 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:46.843  3273  3273 E Zygote  : MountEmulatedStorage()
03-17 12:55:46.843  3273  3273 E Zygote  : v2
03-17 12:55:46.843  3273  3273 I libpersona: KNOX_SDCARD checking this for 10012
03-17 12:55:46.843  3273  3273 I libpersona: KNOX_SDCARD not a persona
03-17 12:55:46.843  3273  3273 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-17 12:55:46.843  3179  3179 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
03-17 12:55:46.843  1022  1035 I ActivityManager: Start proc com.google.android.gms:car for service com.google.android.gms/.car.InCallServiceImpl: pid=3273 uid=10012 gids={50012, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
03-17 12:55:46.843  1022  1234 D ActivityManager: retrieveServiceLocked(): component = com.android.incallui/com.android.incallui.SecInCallService; callingUser = 0; userId(target) = -2
03-17 12:55:46.843  1022  1234 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:55:46.843  1022  1234 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 12:55:46.843  1022  1234 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.incallui
03-17 12:55:46.843  3273  3273 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-17 12:55:46.853  3273  3273 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
03-17 12:55:46.853  1464  1464 I Telecom : InCallController: onConnected to ComponentInfo{com.android.incallui/com.android.incallui.InCallServiceImpl}
03-17 12:55:46.853  1464  1464 I Telecom : InCallController: Unbinding from InCallService unbind
03-17 12:55:46.853  3164  3206 I DBG_DM  : [com.wssyncmldm.db.file.XDB(1976/llIlIIIIlIIIIIlIlIII)] xdbDMffs_Init
03-17 12:55:46.873  3273  3273 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 12:55:46.873  3273  3273 D ActivityThread: Added TimaKeyStore provider
03-17 12:55:46.893  3273  3273 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-17 12:55:46.893  3273  3273 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
03-17 12:55:46.913  3164  3164 I DBG_DM  : [com.wssyncmldm.ui.IIllIllllIIlIlIIlIII(49/onServiceConnected)] 
03-17 12:55:46.913  3273  3273 I MultiDex: VM with version 2.1.0 has multidex support
03-17 12:55:46.913  3273  3273 I MultiDex: install
03-17 12:55:46.913  3273  3273 I MultiDex: VM has multidex support, MultiDex support library is disabled.
03-17 12:55:46.913  1022  1022 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:46.913  1022  1022 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:46.913  1022  1022 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:46.913  1022  1022 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:46.933   289   289 E SMD     : DCD OFF
03-17 12:55:46.933  3256  3256 I CameraApp: CameraApp.onCreate()... mFeature : null
03-17 12:55:46.933  3256  3256 I testFeature: Feature.Feature(context)
03-17 12:55:46.933  3256  3256 I testFeature: Feature.readInternalDefaultXml()
03-17 12:55:46.933  3256  3256 I testFeature: ResetFeatureValue
03-17 12:55:46.933  3256  3256 I CameraFirmware_broadcast: CameraFirmwareBroadCastReceiver...
03-17 12:55:46.933  3256  3256 I CameraApp: CameraApp.getAppFeature()...
03-17 12:55:46.943  3294  3294 E Zygote  : MountEmulatedStorage()
03-17 12:55:46.943  3294  3294 E Zygote  : v2
03-17 12:55:46.943  3294  3294 I libpersona: KNOX_SDCARD checking this for 10003
03-17 12:55:46.943  3294  3294 I libpersona: KNOX_SDCARD not a persona
03-17 12:55:46.943  1022  1022 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=3294 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a
03-17 12:55:46.943  3294  3294 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-17 12:55:46.943  3294  3294 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-17 12:55:46.953  1022  1034 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:46.953  1022  1034 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:46.953  1022  1034 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:46.953  1022  1034 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:46.953  3294  3294 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 12:55:46.963   319   319 I ServiceManager: Waiting for service AtCmdFwd...
03-17 12:55:46.963  3303  3303 E Zygote  : MountEmulatedStorage()
03-17 12:55:46.963  3303  3303 E Zygote  : v2
03-17 12:55:46.963  3303  3303 I libpersona: KNOX_SDCARD checking this for 10100
03-17 12:55:46.963  3303  3303 I libpersona: KNOX_SDCARD not a persona
03-17 12:55:46.973  1022  1034 I ActivityManager: Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=3303 uid=10100 gids={50100, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
03-17 12:55:46.973  1022  1034 I ActivityManager: Killing 2396:com.sec.android.omc/1000 (adj 15): empty #31
03-17 12:55:46.973  3303  3303 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-17 12:55:46.973  3303  3303 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-17 12:55:46.973  3303  3303 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 12:55:46.983  1022  1515 I ActivityManager: Killing 2407:com.sec.modem.settings/1000 (adj 15): empty #31
03-17 12:55:46.993  3294  3294 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 12:55:46.993  3294  3294 D ActivityThread: Added TimaKeyStore provider
03-17 12:55:46.993  3273  3273 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
03-17 12:55:47.003  3265  3265 D AndroidRuntime: 
03-17 12:55:47.003  3265  3265 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
03-17 12:55:47.003  3265  3265 D AndroidRuntime: CheckJNI is OFF
03-17 12:55:47.003  3265  3265 D AndroidRuntime: readGMSProperty: start
03-17 12:55:47.003  3265  3265 D AndroidRuntime: readGMSProperty: already setted!!
03-17 12:55:47.003  3265  3265 D AndroidRuntime: propertySet: couldn't set property (it is from app)
03-17 12:55:47.003  3265  3265 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
03-17 12:55:47.003  3265  3265 D AndroidRuntime: readGMSProperty: end
03-17 12:55:47.003  3265  3265 D AndroidRuntime: addProductProperty: start
03-17 12:55:47.003  3303  3303 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 12:55:47.003   284   284 V audio_hw_primary: adev_get_parameters: enter: keys - call_forwarding
03-17 12:55:47.003   284   284 D audio_hw_extn: audio_extn_get_parameters: returns 
03-17 12:55:47.003   284   284 V msm8974_platform: platform_get_parameters: exit: returns - 
03-17 12:55:47.003   284   284 V audio_hw_primary: adev_get_parameters: exit: returns - call_forwarding=false
03-17 12:55:47.003   284   284 I str_params: key: 'call_forwarding' value: ''
03-17 12:55:47.003  2005  2005 V InCall  : ProximitySensor -  - screenonImmediately: false
03-17 12:55:47.003  2005  2005 V InCall  : ProximitySensor -  - mFromRcsShare: false
03-17 12:55:47.003  3303  3303 D ActivityThread: Added TimaKeyStore provider
03-17 12:55:47.003  2005  2005 I InCall  : ProximitySensor -  - ProximitySensor{keybrd=0, dpad=0, offhook=0, hor=0, ui=0, aud=EARPIECE}
03-17 12:55:47.013  2005  2005 D ScoverManager: serviceVersion : 16908288
03-17 12:55:47.013  1022  3133 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
03-17 12:55:47.013  2005  2005 D InCall  : InCallUtils - isCoverClosed false
03-17 12:55:47.023  1464  1464 I Telecom : ProximitySensorManager: Proximity wake lock already released
03-17 12:55:47.023  1022  3060 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
03-17 12:55:47.023  2005  2005 D InCall  : InCallUtils - isCoverClosed false
03-17 12:55:47.023  2005  2005 I InCall  : InCallPresenter -  - InCallState = NO_CALLS
03-17 12:55:47.023  2005  2005 I InCall  : InCallPresenter -  - Phone switching state: NO_CALLS -> NO_CALLS
03-17 12:55:47.023  2005  2005 D InCall  : InCallPresenter -  - dismissCoverDialog()...
03-17 12:55:47.053  2005  2005 I InCall  : CallSContextMotion - stopPutDownListening
03-17 12:55:47.053  3273  3273 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
03-17 12:55:47.053  2005  2005 D InCall  : StatusBarNotifier - updateInCallNotification(allowFullScreenIntent = false)...
03-17 12:55:47.053  3273  3273 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@35487134: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
03-17 12:55:47.053  3273  3273 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
03-17 12:55:47.063  1191  1191 D PhoneStatusBarView: setCallBackground:0
03-17 12:55:47.063  1022  1518 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
03-17 12:55:47.063  2005  2005 D InCall  : InCallUtils - isCoverClosed false
03-17 12:55:47.073  3179  3179 W art     : Verification of android.content.Intent com.google.android.finsky.utils.NotificationManager.createDefaultClickIntent(android.content.Context, java.lang.String, java.lang.String, java.lang.String, java.lang.String) took 112.468ms
03-17 12:55:47.073  1022  1046 W libprocessgroup: failed to open /acct/uid_1000/pid_2396/cgroup.procs: No such file or directory
03-17 12:55:47.083  1022  1046 W libprocessgroup: failed to open /acct/uid_1000/pid_2407/cgroup.procs: No such file or directory
03-17 12:55:47.083  1022  3133 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:47.083  1022  3133 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:47.083  1022  3133 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:47.083  1022  3133 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:47.103  3337  3337 E Zygote  : MountEmulatedStorage()
03-17 12:55:47.103  3337  3337 I libpersona: KNOX_SDCARD checking this for 10009
03-17 12:55:47.103  3337  3337 E Zygote  : v2
03-17 12:55:47.103  3337  3337 I libpersona: KNOX_SDCARD not a persona
03-17 12:55:47.103  1022  1482 E Tethering: No numeric data
03-17 12:55:47.103  3337  3337 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-17 12:55:47.103  3337  3337 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-17 12:55:47.103  3337  3337 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
03-17 12:55:47.103  1022  3133 I ActivityManager: Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=3337 uid=10009 gids={50009, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-17 12:55:47.103  1022  3083 E Tethering: No numeric data
03-17 12:55:47.113  1022  3083 E Tethering: No numeric data
03-17 12:55:47.113  1022  1234 E Tethering: No numeric data
03-17 12:55:47.123  1022  1035 E Tethering: No numeric data
03-17 12:55:47.123  1022  1518 E Tethering: No numeric data
03-17 12:55:47.123  1022  3059 I ActivityManager: Killing 2427:com.sec.tcpdumpservice/1000 (adj 15): empty #31
03-17 12:55:47.133  3337  3337 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 12:55:47.133  3337  3337 D ActivityThread: Added TimaKeyStore provider
03-17 12:55:47.143  2005  2005 D VideoCallManager: Instantiating VideoCallManager
03-17 12:55:47.143  2005  2005 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
03-17 12:55:47.143  2005  2005 I GFX construct_block_size_descriptor_2d second part: took 2.152292ms for 0*0 texture 0
03-17 12:55:47.153  2005  2005 I GFX generate_partition_tables: took 5.223906ms for 0*0 texture 0
03-17 12:55:47.153  2005  2005 I GFX raster: took 11.209323ms for 176*144 texture 0
03-17 12:55:47.153  2005  2005 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8663590 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b0, Counterpart=0xb86636d8 counterpartCT=4 counterpartW=176 counterparth=144
03-17 12:55:47.163  3265  3265 E AffinityControl: AffinityControl: registerfunction enter
03-17 12:55:47.163  2005  2005 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 320x240
03-17 12:55:47.163  2005  2005 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
03-17 12:55:47.163  2005  2005 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
03-17 12:55:47.163  2005  2005 I Adreno-EGL: Build Date: 04/06/15 Mon
03-17 12:55:47.163  2005  2005 I Adreno-EGL: Local Branch: 
03-17 12:55:47.163  2005  2005 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
03-17 12:55:47.163  2005  2005 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
03-17 12:55:47.163  2005  2005 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
03-17 12:55:47.183  3164  3206 I DBG_DM  : [IlIIlIIlIllllIlllIII(191/llIIIIlllllIIllIIllI)] XEVENT_PHONEBOOK_INITIALIZED
03-17 12:55:47.183  1335  3142 D [SBeam] : SBeamEnabler.isSBeamSupported : [-1]
03-17 12:55:47.183  1335  3142 D [SBeam] : SBeamEnabler.isSBeamSupported : EXIST
03-17 12:55:47.183  2005  2005 I GFX GPU raster: eglCreateImageKHR: EGL_SUCCESS
03-17 12:55:47.183  3265  3265 D AndroidRuntime: Calling main entry com.android.commands.am.Am
03-17 12:55:47.193  3239  3239 I DBG_POLICYDM: [com.policydm.XDMApplication(554/xdmWakeLockAcquire)] 
03-17 12:55:47.193  3239  3239 I DBG_POLICYDM: [com.policydm.XDMApplication(559/xdmWakeLockAcquire)] m_WakeLock is acquire!!
03-17 12:55:47.193  2005  2005 I glCompressedTexImage2D: took 0.458073ms for 320*61440 texture 37809
03-17 12:55:47.203  1022  1083 E PersonaManagerService: inState():  stateMachine is null !!
03-17 12:55:47.203  1022  1083 I PersonaManagerService: PersonaId don't exist
03-17 12:55:47.203  1022  1083 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
03-17 12:55:47.203  3239  3335 I DBG_POLICYDM: [com.policydm.agent.XDMTask(163/xdmAgentTaskHandler)] XEVENT_OS_INITIALIZED
03-17 12:55:47.203  3239  3239 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(191/xdmInitExternalStorageState)] 
03-17 12:55:47.203  2005  2005 I draw setup: took 10.646510ms for 320*240 texture 37809
03-17 12:55:47.203  3294  3294 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
03-17 12:55:47.203  1022  1083 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-17 12:55:47.203  2005  2005 E GFX GPU raster: drawn
03-17 12:55:47.203  2005  2005 I GFX GPU raster ASTC: took 41.970210ms for 320*240 texture 12
03-17 12:55:47.203  1022  1361 E Tethering: No numeric data
03-17 12:55:47.203  2005  2005 I GFX raster: took 42.054428ms for 320*240 texture 0
03-17 12:55:47.203  2005  2005 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb865f690 bitmapCt=12 bitmapW=320 bitmapH=240 BitmapInternalFormat=93b1, Counterpart=0xb8663740 counterpartCT=4 counterpartW=320 counterparth=240
03-17 12:55:47.213  3239  3239 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(390/xdmGetExternalSDCardPath)] External SD Card Path : /storage/extSdCard
03-17 12:55:47.213  3239  3239 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(248/xdmInitExternalStorageState)] DATA_DIR_PATH [/data]
03-17 12:55:47.213  1022  1083 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1022  pkgName : ACTIVITY_RESUME_BOOSTER@7
03-17 12:55:47.213  3239  3239 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(249/xdmInitExternalStorageState)] EXTERNAL_DIR_PATH [/storage/emulated/0]
03-17 12:55:47.213  3239  3239 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(250/xdmInitExternalStorageState)] EXTERNAL_SD_DIR_PATH [/storage/extSdCard]
03-17 12:55:47.213  3239  3239 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(251/xdmInitExternalStorageState)] POLICY_DIR_PATH [/data/user/0/com.policydm/cache]
03-17 12:55:47.213  3239  3239 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(253/xdmInitExternalStorageState)] bExternalStorageAvailable [true]
03-17 12:55:47.213  3239  3239 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(254/xdmInitExternalStorageState)] bExternalSDStorageAvailable [false]
03-17 12:55:47.223  3239  3239 I DBG_POLICYDM: [com.policydm.XDMApplication(580/xdmWakeLockRelease)] 
03-17 12:55:47.223  2005  2005 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 480x640
03-17 12:55:47.223  2005  2005 I GFX GPU raster: eglCreateImageKHR: EGL_SUCCESS
03-17 12:55:47.223  3239  3239 I DBG_POLICYDM: [com.policydm.XDMApplication(585/xdmWakeLockRelease)] m_WakeLock is release!!
03-17 12:55:47.223  2005  2005 I glCompressedTexImage2D: took 0.348333ms for 480*122880 texture 37813
03-17 12:55:47.223  2005  2005 I draw setup: took 0.903750ms for 480*640 texture 37813
03-17 12:55:47.223  2005  2005 E GFX GPU raster: drawn
03-17 12:55:47.223  3239  3239 I DBG_POLICYDM: [com.policydm.XDMApplication(179/onCreate)] DMApplication Start !
03-17 12:55:47.223  1022  1083 W ActivityManager: mDVFSHelper.acquire()
03-17 12:55:47.223  3303  3303 D PackageIntentReceiver: ACTION_BOOT_COMPLETED
03-17 12:55:47.233  2005  2005 I GFX GPU raster ASTC: took 7.225573ms for 480*640 texture 12
03-17 12:55:47.233  2005  2005 I GFX raster: took 7.305626ms for 480*640 texture 0
03-17 12:55:47.233  2005  2005 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8663740 bitmapCt=12 bitmapW=480 bitmapH=640 BitmapInternalFormat=93b5, Counterpart=0xb8890928 counterpartCT=4 counterpartW=480 counterparth=640
03-17 12:55:47.233  1022  1083 D FocusedStackFrame: Set to : 0
03-17 12:55:47.233  1022  1052 D PhoneWindow: *FMB* installDecor mIsFloating : false
03-17 12:55:47.233  1022  1052 D PhoneWindow: *FMB* installDecor flags : -2122120936
03-17 12:55:47.243  1519  1519 D Launcher.HomeView: onPause
03-17 12:55:47.243  1519  1519 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
03-17 12:55:47.243  3303  3303 D PackageIntentReceiver: jangil::ACTION_BOOT_COMPLETED::do not need pkg remove..
03-17 12:55:47.243  1022  1083 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
03-17 12:55:47.243  1022  1083 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-17 12:55:47.243  1022  1083 D InputDispatcher: Focused application set to: xxxx
03-17 12:55:47.243  1022  1083 D InputDispatcher: Focus left window: 1519
03-17 12:55:47.243  3265  3265 D AndroidRuntime: Shutting down VM
03-17 12:55:47.243  1022  1052 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
03-17 12:55:47.243  1022  1052 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
03-17 12:55:47.253   258   258 I SurfaceFlinger: id=10 createSurf (1x1),1 flag=404, uhalitest
03-17 12:55:47.253  1022  1518 I ActivityManager: Killing 2442:com.sec.android.app.sbrowser/u0a131 (adj 15): empty #31
03-17 12:55:47.253  1022  1361 E Tethering: No numeric data
03-17 12:55:47.263  1022  1515 D ActivityManager: retrieveServiceLocked(): component = com.google.android.syncadapters.contacts/com.google.android.syncadapters.contacts.ContactsSyncAdapterIntentService; callingUser = 0; userId(target) = 0
03-17 12:55:47.263  1022  1515 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:55:47.263  1022  1515 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:55:47.263  1022  1515 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.process.gapps
03-17 12:55:47.273  1022  1052 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-17 12:55:47.273  2005  2005 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 440x330
03-17 12:55:47.273  2005  2005 I GFX GPU raster: eglCreateImageKHR: EGL_SUCCESS
03-17 12:55:47.273  1022  1052 D PointerIcon: setMouseCustomIcon IconType is same.101
03-17 12:55:47.273  2005  2005 I glCompressedTexImage2D: took 0.383073ms for 440*116864 texture 37809
03-17 12:55:47.273  2005  2005 I draw setup: took 0.946614ms for 440*330 texture 37809
03-17 12:55:47.273  2005  2005 E GFX GPU raster: drawn
03-17 12:55:47.273  3239  3335 I DBG_POLICYDM: [com.policydm.agent.XDMAgent(156/xdmAgentSetSyncMode)] nSync = 0
03-17 12:55:47.273  1022  1482 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:47.273  2005  2005 I GFX GPU raster ASTC: took 5.069323ms for 440*330 texture 12
03-17 12:55:47.273  2005  2005 I GFX raster: took 5.145989ms for 440*330 texture 0
03-17 12:55:47.273  2005  2005 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8890928 bitmapCt=12 bitmapW=440 bitmapH=330 BitmapInternalFormat=93b1, Counterpart=0xb88a4d18 counterpartCT=4 counterpartW=440 counterparth=330
03-17 12:55:47.273  1022  1482 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:47.273  1022  1482 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:47.273  1022  1482 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:47.283  1022  1046 W libprocessgroup: failed to open /acct/uid_1000/pid_2427/cgroup.procs: No such file or directory
03-17 12:55:47.283  1022  1083 E Tethering: No numeric data
03-17 12:55:47.293  1696  3368 I GoogleHttpClient: GMS http client unavailable, use old client
03-17 12:55:47.303  3371  3371 E Zygote  : MountEmulatedStorage()
03-17 12:55:47.303  3371  3371 I libpersona: KNOX_SDCARD checking this for 10174
03-17 12:55:47.303  3371  3371 E Zygote  : v2
03-17 12:55:47.303  3371  3371 I libpersona: KNOX_SDCARD not a persona
03-17 12:55:47.303  2005  2005 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 480x640
03-17 12:55:47.303  1022  1482 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3371 uid=10174 gids={50174, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
03-17 12:55:47.303  2005  2005 I GFX GPU raster: eglCreateImageKHR: EGL_SUCCESS
03-17 12:55:47.303  3371  3371 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-17 12:55:47.303  2005  2005 I glCompressedTexImage2D: took 0.499844ms for 480*163840 texture 37811
03-17 12:55:47.303  2005  2005 I draw setup: took 1.099219ms for 480*640 texture 37811
03-17 12:55:47.303  2005  2005 E GFX GPU raster: drawn
03-17 12:55:47.313  2005  2005 I GFX GPU raster ASTC: took 5.882761ms for 480*640 texture 12
03-17 12:55:47.313  2005  2005 I GFX raster: took 5.967084ms for 480*640 texture 0
03-17 12:55:47.313  2005  2005 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8894b28 bitmapCt=12 bitmapW=480 bitmapH=640 BitmapInternalFormat=93b3, Counterpart=0xb865f6c8 counterpartCT=4 counterpartW=480 counterparth=640
03-17 12:55:47.313  3371  3371 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-17 12:55:47.313  3371  3371 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
03-17 12:55:47.323  1022  1506 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:47.323  1022  1506 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:47.323  1022  1506 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:47.323  1022  1506 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:47.323  3164  3206 I DBG_DM  : [com.wssyncmldm.db.file.XDB(3660/lllIIIIllIlIlllllllI)] FUMO_Status : 220
03-17 12:55:47.323  3239  3335 I DBG_POLICYDM: [com.policydm.db.XDB(1531/xdbDMffs_Init)] xdbDMffs_Init
03-17 12:55:47.333  3380  3380 E Zygote  : MountEmulatedStorage()
03-17 12:55:47.333  3380  3380 E Zygote  : v2
03-17 12:55:47.333  1022  1506 I ActivityManager: Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.BootBroadcastReceiver: pid=3380 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-17 12:55:47.343  3380  3380 I libpersona: KNOX_SDCARD checking this for 1000
03-17 12:55:47.343  3380  3380 I libpersona: KNOX_SDCARD not a persona
03-17 12:55:47.343  3380  3380 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-17 12:55:47.353  3380  3380 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-17 12:55:47.353  3380  3380 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 12:55:47.353  3371  3371 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 12:55:47.353  3371  3371 D ActivityThread: Added TimaKeyStore provider
03-17 12:55:47.363  1519  1519 V ActivityThread: updateVisibility : ActivityRecord{3730e788 token=android.os.BinderProxy@354edd49 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
03-17 12:55:47.363  1022  1482 E Tethering: No numeric data
03-17 12:55:47.363  2005  2005 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
03-17 12:55:47.373  2005  2005 I GFX construct_block_size_descriptor_2d second part: took 2.270573ms for 0*0 texture 0
03-17 12:55:47.383  2005  2005 I GFX generate_partition_tables: took 9.063542ms for 0*0 texture 0
03-17 12:55:47.383  2005  2005 I GFX raster: took 13.379791ms for 176*144 texture 0
03-17 12:55:47.383  2005  2005 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb888e1d0 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b2, Counterpart=0xb888e2e0 counterpartCT=4 counterpartW=176 counterparth=144
03-17 12:55:47.383  3164  3206 I DBG_DM  : [com.wssyncmldm.XDMService(1377/llllIIIllIlIIIIllllI)] wssGetUpdateReport : 0
03-17 12:55:47.383  1022  1046 W libprocessgroup: failed to open /acct/uid_10131/pid_2442/cgroup.procs: No such file or directory
03-17 12:55:47.383  3164  3206 I DBG_DM  : [IlIIlIIlIllllIlllIII(217/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT
03-17 12:55:47.393  1022  3060 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
03-17 12:55:47.393  1022  3060 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
03-17 12:55:47.393  1022  3060 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
03-17 12:55:47.393  2005  2005 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
03-17 12:55:47.393  1519  1519 D Launcher.HomeView: onStop
03-17 12:55:47.403  1519  1519 V ActivityThread: updateVisibility : ActivityRecord{3730e788 token=android.os.BinderProxy@354edd49 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
03-17 12:55:47.403  3380  3380 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 12:55:47.403  3179  3179 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
03-17 12:55:47.403  1022  1050 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
03-17 12:55:47.403  2005  2005 I GFX construct_block_size_descriptor_2d second part: took 2.558699ms for 0*0 texture 0
03-17 12:55:47.413  1022  3060 D PersonaManager: isKioskContainerExistOnDevice
03-17 12:55:47.413  3380  3380 D ActivityThread: Added TimaKeyStore provider
03-17 12:55:47.423  2005  2005 I GFX generate_partition_tables: took 6.236873ms for 0*0 texture 0
03-17 12:55:47.423  2005  2005 I GFX raster: took 10.932918ms for 176*144 texture 0
03-17 12:55:47.423  2005  2005 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb88b7b70 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b1, Counterpart=0xb88d4500 counterpartCT=4 counterpartW=176 counterparth=144
03-17 12:55:47.423  2005  2005 D ScoverManager: registerListener
03-17 12:55:47.423  1022  1534 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
03-17 12:55:47.433  1022  1234 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
03-17 12:55:47.433  1022  1234 D CoverManager.StateNotifier: registerListenerCallback : binder = android.os.BinderProxy@1094fa40, pid : 2005, uid : 1001, type : 1
03-17 12:55:47.443  3294  3294 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
03-17 12:55:47.443  3294  3294 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
03-17 12:55:47.443  3294  3294 D UserAnalysis: Create SecureDbHelper
03-17 12:55:47.453  1022  1022 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
03-17 12:55:47.453  1022  1022 D SensorService: [SO] activate (ident=0xb8b2eef8, enabled=0)
03-17 12:55:47.453  1022  1022 I Sensors : AccelerometerSensor enable: mEnabled 1, handle 0, en 0
03-17 12:55:47.473  3265  3265 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
03-17 12:55:47.473  1022  1022 D SensorManager: unregisterListener ::   
03-17 12:55:47.473  1022  1022 I Sensors : AccelerometerSensor(0) setDelay : 66000000(ns)
,03-17 12:55:47.473  1022  1022 D SensorService: [SO] changed settle time [1]
03-17 12:55:47.473  1022  1022 D SensorService: [SO] setDelay [66000000]
03-17 12:55:47.473  1022  1022 D SensorService: [SO] activate (ident=0xb8b2eef8, enabled=1)
03-17 12:55:47.473  1022  1022 D SensorService: [SO] AR_init
03-17 12:55:47.473  1022  1022 I Sensors : AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,03-17 12:55:47.483  1022  1022 D SensorManager: registerListener :: 1600221811, Screen Orientation Sensor, 66000, 0,  
,03-17 12:55:47.493  2005  2005 D InCall  : InCallPresenter -  - Finished InCallPresenter.setUp
,03-17 12:55:47.493  3294  3294 D IntelligenceServiceApplication: onCreate()
,03-17 12:55:47.503  3294  3294 D UserAnalysis.UserAnalysisBroadcastReceiver: Intent(action: android.intent.action.BOOT_COMPLETED) is received.
,03-17 12:55:47.513  1519  1519 D Launcher: onTrimMemory. Level: 20
,03-17 12:55:47.523  1022  1518 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:47.523  1022  1518 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:47.523  1022  1518 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:47.523  1022  1518 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:55:47.523  1191  1191 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-17 12:55:47.523  1191  1191 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-17 12:55:47.523  1191  1191 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 12:55:47.533  1191  1191 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 12:55:47.533  1191  1191 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 12:55:47.533  1191  1191 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 12:55:47.533  3294  3294 D IntelligenceServiceApplication: no applications having user consent for prediction
,03-17 12:55:47.533  3404  3404 E Zygote  : MountEmulatedStorage()
03-17 12:55:47.533  3404  3404 E Zygote  : v2
03-17 12:55:47.533  3404  3404 I libpersona: KNOX_SDCARD checking this for 10060
03-17 12:55:47.533  3404  3404 I libpersona: KNOX_SDCARD not a persona
,03-17 12:55:47.543  3404  3404 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 12:55:47.543  1022  1506 V VibratorService: hasVibrator - useVibetonz: true
,03-17 12:55:47.543  3404  3404 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 12:55:47.553  1022  1518 I ActivityManager: Start proc com.samsung.android.scloud.backup for broadcast com.samsung.android.scloud.backup/.SCloudBackupReceiver: pid=3404 uid=10060 gids={50060, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,03-17 12:55:47.553  1022  1044 D SensorService: [SO] Reset Rotation Old [100], Init [1]
03-17 12:55:47.553  1022  1518 I ActivityManager: Killing 2500:com.wsomacp/u0a25 (adj 15): empty #31
,03-17 12:55:47.553  3404  3404 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 12:55:47.553  1022  1234 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,03-17 12:55:47.553  3294  3294 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,03-17 12:55:47.593  3371  3371 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
,03-17 12:55:47.593  3294  3294 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,03-17 12:55:47.593  3294  3294 D UserAnalysis.MyPlaceDbPreference: Constructor Preference
,03-17 12:55:47.593  3404  3404 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:55:47.593  3404  3404 D ActivityThread: Added TimaKeyStore provider
,03-17 12:55:47.603  3239  3335 I DBG_POLICYDM: [com.policydm.agent.XDMTask(171/xdmAgentTaskHandler)] XEVENT_DM_INIT
,03-17 12:55:47.623  1022  1044 D SensorService: [SO] 0.172 0.402 10.247
,03-17 12:55:47.623  1022  1044 D SensorService: [SO] [100 -> 255]
,03-17 12:55:47.623  3239  3335 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,03-17 12:55:47.623  1335  3142 W NotificationAccessSettings: Skipping notification listener service com.android.settings/com.android.settings.accessibility.notificationreminder.NotificationReminderService: it does not require the permission android.permission.BIND_NOTIFICATION_LISTENER_SERVICE
03-17 12:55:47.623  1022  1046 W libprocessgroup: failed to open /acct/uid_10025/pid_2500/cgroup.procs: No such file or directory
,03-17 12:55:47.623  3371  3371 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 7947-7949)
03-17 12:55:47.633  3371  3371 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-17 12:55:47.633  1022  1083 V VibratorService: hasVibrator - useVibetonz: true
,03-17 12:55:47.643  1022  3083 V VibratorService: hasVibrator - useVibetonz: true
03-17 12:55:47.653  3239  3335 I DBG_POLICYDM: [com.policydm.XDMApplication(619/xdmGetNotibarState)] get NotibarState : 7
,03-17 12:55:47.653  1335  3142 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-17 12:55:47.663  3371  3371 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2e8cdfe0}
,03-17 12:55:47.663  3371  3371 I LibraryLoader: Expected native library version number "",actual native library version number ""
03-17 12:55:47.663  3371  3371 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,03-17 12:55:47.693  3239  3247 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,03-17 12:55:47.703  3371  3371 I BrowserStartupController: Initializing chromium process, singleProcess=true
,03-17 12:55:47.703  3371  3371 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-17 12:55:47.703  3371  3371 E SysUtils: ApplicationContext is null in ApplicationStatus
,03-17 12:55:47.703  3239  3335 I DBG_POLICYDM: [com.policydm.ui.XUINotificationManager(48/xuiSetIndicator)] Indicator id : 7
,03-17 12:55:47.713  3239  3247 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,03-17 12:55:47.723  1022  1034 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 12:55:47.723  3239  3335 I DBG_POLICYDM: [com.policydm.XDMApplication(611/xdmSetNotibarState)] set NotibarState : 7
,03-17 12:55:47.733  3371  3371 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,03-17 12:55:47.733  1022  1034 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:55:47.733  1022  1034 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:55:47.733  1022  1034 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,03-17 12:55:47.733  1022  3133 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
,03-17 12:55:47.733  1022  3133 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:55:47.733  3371  3371 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-17 12:55:47.733  3371  3371 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,03-17 12:55:47.733  1022  3133 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 12:55:47.743  3371  3371 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
03-17 12:55:47.743  3371  3371 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
03-17 12:55:47.743  3371  3371 I Adreno-EGL: Build Date: 04/06/15 Mon
03-17 12:55:47.743  3371  3371 I Adreno-EGL: Local Branch: 
03-17 12:55:47.743  3371  3371 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
03-17 12:55:47.743  3371  3371 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
03-17 12:55:47.743  3371  3371 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,03-17 12:55:47.743  1022  3133 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,03-17 12:55:47.743  3239  3247 I DBG_POLICYDM: [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,03-17 12:55:47.763  1022  1035 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:55:47.763  1022  1035 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:47.763  1022  1035 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:47.763  1022  1035 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:55:47.763  1335  3142 D ScoverManager: serviceVersion : 16908288
03-17 12:55:47.783  3439  3439 E Zygote  : MountEmulatedStorage()
03-17 12:55:47.783  3439  3439 E Zygote  : v2
03-17 12:55:47.783  3439  3439 I libpersona: KNOX_SDCARD checking this for 1000
03-17 12:55:47.783  3439  3439 I libpersona: KNOX_SDCARD not a persona
03-17 12:55:47.783  3439  3439 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-17 12:55:47.783  3439  3439 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-17 12:55:47.783  1022  1035 I ActivityManager: Start proc com.sec.knox.foldercontainer for broadcast com.sec.knox.foldercontainer/.ShortcutReceiver: pid=3439 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-17 12:55:47.783  3439  3439 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 12:55:47.793  2747  2791 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,03-17 12:55:47.793  3239  3335 I DBG_POLICYDM: [com.policydm.db.XDBAESCrypt(217/xdbGetCryptionkey)] try read dbString
,03-17 12:55:47.803  3239  3248 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,03-17 12:55:47.803  3239  3248 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,03-17 12:55:47.803  3239  3248 I DBG_POLICYDM: [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,03-17 12:55:47.813   310   310 I art     : Explicit concurrent mark sweep GC freed 8763(373KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 670us total 31.126ms
,03-17 12:55:47.823  3179  3179 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,03-17 12:55:47.823  3239  3335 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(428/xdbGetFUMOStatus)] xdbGetFUMOStatus : 0
,03-17 12:55:47.823  3179  3179 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,03-17 12:55:47.833  3439  3439 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:55:47.833  3439  3439 D ActivityThread: Added TimaKeyStore provider
,03-17 12:55:47.843   310   310 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 628us total 22.299ms
,03-17 12:55:47.863  1914  1914 I GAv4-SVC: Google Analytics 7.8.99 is starting up.
,03-17 12:55:47.863   310   310 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 649us total 20.353ms
,03-17 12:55:47.863  3239  3335 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(587/xdbGetFUMOInitiatedType)] Initiated Type: 0
,03-17 12:55:47.883   258  3394 I SurfaceFlinger: id=8 Removed Mauncher (5/8)
,03-17 12:55:47.893   258  1108 I SurfaceFlinger: id=8 Removed Mauncher (-2/8)
,03-17 12:55:47.903  3404  3404 I sCloudBackupApp: sCloudBackupApp Version Info : 4.04.8.KK_APP
,03-17 12:55:47.903  3239  3335 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(72/xpollingCheckVersionInfo)] 
,03-17 12:55:47.913  3239  3335 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(271/xpollingCheckTimer)] 
,03-17 12:55:47.913  3239  3336 I DBG_POLICYDM: [com.policydm.agent.XDMUITask(191/xdmUIEvent)] XUI_DM_IDLE_STATE :true
,03-17 12:55:47.913  3239  3335 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(285/xpollingCheckTimer)] savedpollingtime : 2016/03/18/13:15:33
,03-17 12:55:47.913  3239  3335 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(286/xpollingCheckTimer)] currentTime : 2016/03/17/12:55:47
,03-17 12:55:47.923  3439  3439 D KnoxSetupWizardDbHelper: dbMigrationFlag : false
,03-17 12:55:47.923  3239  3335 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(290/xpollingCheckTimer)] Restart Timer..
,03-17 12:55:47.923  3239  3335 I DBG_POLICYDM: [com.policydm.XDMApplication(626/xdmStartAlarm)] Alarm ID: 0
,03-17 12:55:47.923  1022  3059 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:47.923  1022  3059 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:47.923  1022  3059 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:47.923  1022  3059 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:55:47.933  3239  3336 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,03-17 12:55:47.943  3470  3470 E Zygote  : MountEmulatedStorage()
03-17 12:55:47.943  3470  3470 E Zygote  : v2
03-17 12:55:47.943  3470  3470 I libpersona: KNOX_SDCARD checking this for 1000
03-17 12:55:47.943  3470  3470 I libpersona: KNOX_SDCARD not a persona
,03-17 12:55:47.943  3470  3470 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 12:55:47.943  3439  3439 D ShortcutReceiver:  ShortcutReceiver onReceive() intent: android.intent.action.BOOT_COMPLETED,
,03-17 12:55:47.943  3470  3470 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 12:55:47.943  3470  3470 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 12:55:47.953  1022  3059 I ActivityManager: Start proc com.fmm.dm for broadcast com.fmm.dm/.XDMBroadcastReceiver: pid=3470 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-17 12:55:47.953  1022  3059 I ActivityManager: Killing 2347:com.sec.android.app.mt/1000 (adj 15): empty #31
,03-17 12:55:47.953  1022  3059 I ActivityManager: Killing 2587:com.sec.android.app.camera/u0a139 (adj 15): empty #32
,03-17 12:55:47.953  3239  3336 I DBG_POLICYDM: [com.policydm.db.XDBProfileListAdp(258/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,03-17 12:55:47.953  3239  3336 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(399/xnotiPushAdpExcuteResumeNoti)] nSessionSaveState:0
,03-17 12:55:47.963  1022  3059 I ActivityManager: Killing 2571:com.sec.android.widgetapp.activeapplicationwidget/u0a142 (adj 15): empty #33
,03-17 12:55:47.963  3239  3336 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(400/xnotiPushAdpExcuteResumeNoti)] nNotiUiEvent:0
,03-17 12:55:47.963  3439  3439 D KnoxShortcutUtil: getIsShortcutMigrationFor_2_3_0_Done true
,03-17 12:55:47.963   319   319 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,03-17 12:55:47.963  3239  3336 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(401/xnotiPushAdpExcuteResumeNoti)] nNotiRetryCount:0
,03-17 12:55:47.973  3239  3336 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(441/xnotiPushAdpExcuteResumeNoti)] Current NOTI NOT SAVED State. EXIT.
,03-17 12:55:47.983  3439  3439 D ShortcutReceiver:  KnoxContainerVersion 2.4.0
03-17 12:55:47.983  3439  3439 D ShortcutReceiver:  shortcut migration not required 
,03-17 12:55:47.983  1022  3059 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:47.983  1022  3059 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:47.983  1022  3059 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:47.983  1022  3059 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:55:47.993  3239  3336 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(267/xnotiPushAdpClearSessionStatus)] 
,03-17 12:55:47.993  3239  3336 I DBG_POLICYDM: [com.policydm.ui.XUIAdapter(39/xuiAdpSetUiMode)] nDmUiMode : 0
,03-17 12:55:47.993  3239  3336 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(439/xdbSetFUMOStatus)] xdbSetFUMOStatus : 0
,03-17 12:55:47.993  3470  3470 D TimaKeyStoreProvider: TimaSignature is unavailable,
03-17 12:55:48.003  3470  3470 D ActivityThread: Added TimaKeyStore provider
,03-17 12:55:48.003  3488  3488 E Zygote  : MountEmulatedStorage()
03-17 12:55:48.003  3488  3488 E Zygote  : v2
03-17 12:55:48.003  3488  3488 I libpersona: KNOX_SDCARD checking this for 10062
03-17 12:55:48.003  3488  3488 I libpersona: KNOX_SDCARD not a persona
,03-17 12:55:48.003  3488  3488 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 12:55:48.003  3488  3488 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 12:55:48.003  3488  3488 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 12:55:48.013  1022  3059 I ActivityManager: Start proc com.samsung.android.scloud.sync for broadcast com.samsung.android.scloud.sync/com.sec.android.sCloudSync.Receivers.TimeChangedReceiver: pid=3488 uid=10062 gids={50062, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-17 12:55:48.013  1022  3059 I ActivityManager: Killing 2612:com.samsung.android.app.FileShareClient/u0a68 (adj 15): empty #31
,03-17 12:55:48.013  1022  3059 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:55:48.013  1022  3059 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:48.013  1022  3059 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:48.013  1022  3059 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:55:48.023  3239  3336 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(565/xdbSetFUMOInitiatedType)] Initiated Type: 0
,03-17 12:55:48.033  3488  3488 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:55:48.033  3488  3488 D ActivityThread: Added TimaKeyStore provider
,03-17 12:55:48.043  3505  3505 E Zygote  : MountEmulatedStorage()
,03-17 12:55:48.043  3505  3505 E Zygote  : v2
03-17 12:55:48.043  3505  3505 I libpersona: KNOX_SDCARD checking this for 1000
03-17 12:55:48.043  3505  3505 I libpersona: KNOX_SDCARD not a persona
,03-17 12:55:48.053  3505  3505 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 12:55:48.053  3505  3505 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
03-17 12:55:48.053  3505  3505 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
03-17 12:55:48.053  1022  3059 I ActivityManager: Start proc com.sec.knox.knoxsetupwizardclient for broadcast com.sec.knox.knoxsetupwizardclient/.detector.SetupWizardDetectorReceiver: pid=3505 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-17 12:55:48.063  1022  3059 I ActivityManager: Killing 2628:com.samsung.android.app.FileShareServer/u0a69 (adj 15): empty #31
,03-17 12:55:48.073  3371  3371 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-17 12:55:48.073  3239  3336 I DBG_POLICYDM: [com.policydm.db.XDB(1825/xdbSetBackUpServerUrl)] 
,03-17 12:55:48.093  3505  3505 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:55:48.093  3505  3505 D ActivityThread: Added TimaKeyStore provider
,03-17 12:55:48.103  3371  3371 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,03-17 12:55:48.123  3371  3371 D PhoneWindow: *FMB* installDecor mIsFloating : false
03-17 12:55:48.123  3371  3371 D PhoneWindow: *FMB* installDecor flags : -2139027200
,03-17 12:55:48.133  3371  3371 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,03-17 12:55:48.143  1022  1034 I art     : Explicit concurrent mark sweep GC freed 29697(1435KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 26MB/40MB, paused 2.929ms total 183.173ms
03-17 12:55:48.143  3371  3371 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-17 12:55:48.143  3371  3371 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-17 12:55:48.183  3470  3470 I DBG_FMMDM: [50.20.150420][Line:608][xdmGetCheckWifiOnlyModel] isWifiOnly : false
,03-17 12:55:48.183  3179  3289 D Volley  : [396] DiskBasedCache.clear: Cache cleared.
,03-17 12:55:48.183  1022  1515 I ActivityManager: Killing 2491:com.samsung.android.securitylogagent/1000 (adj 15): empty #31
,03-17 12:55:48.193  3179  3363 D Volley  : [403] DiskBasedCache.clear: Cache cleared.
,03-17 12:55:48.193  1022  1534 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.playlog.service.MonitorService; callingUser = 0; userId(target) = 0
,03-17 12:55:48.193  1022  1534 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:55:48.193  1022  1534 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 12:55:48.193  1022  1534 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-17 12:55:48.193  3470  3470 I DBG_FMMDM: [50.20.150420][Line:27][xdmInitialize] AgVOOqV7UpXFblBk29Ld3aZrOQhtHCYbjdszx6nYrjFYzeVOvvlPUzE67GnQVups
,03-17 12:55:48.203  3470  3470 I DBG_FMMDM: [50.20.150420][Line:28][xdmInitialize] c8aaBoNX+zCI65M7gVNTej45+K/MzxjqVpKd5x0FMtd3o63nokSujfTEanrHiU41
,03-17 12:55:48.203  3470  3470 I DBG_FMMDM: [50.20.150420][Line:29][xdmInitialize] X2Nl5mgTWVn0/a90MNBgtYshxOiQq2MqI4oMf2Nwz6I=
,03-17 12:55:48.203  1696  1696 V GLSUser : [LoginAccountsChangedWakefulBroadcastReceiver] recieved broadcast intent with action: android.intent.action.BOOT_COMPLETED
,03-17 12:55:48.203  1022  1482 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.change.LoginAccountsChangedIntentService; callingUser = 0; userId(target) = 0
,03-17 12:55:48.203  1022  1482 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:55:48.203  1022  1482 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:55:48.203  1022  1482 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-17 12:55:48.223  1022  1234 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 12:55:48.223  3505  3505 E KnoxSetupWizardClient: isShipMode : 1
03-17 12:55:48.223  3505  3505 I KnoxSetupWizardClient: onReceive : android.intent.action.BOOT_COMPLETED
,03-17 12:55:48.223  1022  1234 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:55:48.223  1022  1234 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:55:48.223  1022  1234 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,03-17 12:55:48.223  1335  3142 I LockPatternUtils: isSmartCardAuthenticationAvailable: false
,03-17 12:55:48.233  1914  1914 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher (has extras) }
,03-17 12:55:48.233  1022  1035 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
,03-17 12:55:48.233  1022  1035 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:55:48.233  1022  1035 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:55:48.233  1022  1035 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 12:55:48.233  1022  3060 D ActivityManager: retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.billing.iab.PendingNotificationsService; callingUser = 0; userId(target) = 0
,03-17 12:55:48.233  1022  3060 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:55:48.233  1022  3060 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:55:48.233  1022  3060 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,03-17 12:55:48.243  1335  3142 D Settings_Utils: isSupportVNFestival SM-A500FU XEO
,03-17 12:55:48.253  1022  1046 W libprocessgroup: failed to open /acct/uid_10139/pid_2587/cgroup.procs: No such file or directory
03-17 12:55:48.253  1022  1046 W libprocessgroup: failed to open /acct/uid_1000/pid_2347/cgroup.procs: No such file or directory
03-17 12:55:48.253  1022  1046 W libprocessgroup: failed to open /acct/uid_10142/pid_2571/cgroup.procs: No such file or directory
03-17 12:55:48.253  1022  1046 W libprocessgroup: failed to open /acct/uid_10068/pid_2612/cgroup.procs: No such file or directory
,03-17 12:55:48.253  1022  1046 W libprocessgroup: failed to open /acct/uid_10069/pid_2628/cgroup.procs: No such file or directory
,03-17 12:55:48.263  1022  1046 W libprocessgroup: failed to open /acct/uid_1000/pid_2491/cgroup.procs: No such file or directory
,03-17 12:55:48.263  1022  1361 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 12:55:48.263  1022  1361 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:55:48.263  1022  1361 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:55:48.263  1022  1361 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-17 12:55:48.273  1022  1034 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:55:48.273  1022  1034 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:55:48.273  1022  1034 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:48.273  1022  1034 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:55:48.293  1022  1034 I ActivityManager: Start proc com.sec.android.app.mt for broadcast com.sec.android.app.mt/.StatusChecker: pid=3536 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-17 12:55:48.293  3536  3536 E Zygote  : MountEmulatedStorage()
03-17 12:55:48.293  3536  3536 E Zygote  : v2
03-17 12:55:48.293  3536  3536 I libpersona: KNOX_SDCARD checking this for 1000
03-17 12:55:48.293  3536  3536 I libpersona: KNOX_SDCARD not a persona
03-17 12:55:48.293  3536  3536 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 12:55:48.303  3536  3536 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 12:55:48.303  3536  3536 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 12:55:48.313  3371  3544 D OpenGLRenderer: Render dirty regions requested: true
,03-17 12:55:48.313  1696  1696 D PersistentNotificationBroadcastReceiver: Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
,03-17 12:55:48.323  1022  1534 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,03-17 12:55:48.323  1022  1534 D KnoxTimeoutHandler: postActiveUserChange for user 0
03-17 12:55:48.323  1022  1534 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,03-17 12:55:48.323  1022  1022 D KnoxTimeoutHandler: handleActiveUserChange for user 0
03-17 12:55:48.323  1022  1022 D PersonaManagerService: getPersonasForUser(): returning null!
03-17 12:55:48.323  3371  3461 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,03-17 12:55:48.323  1022  3083 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:55:48.323  1022  3083 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:48.323  1022  3083 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:48.323  3536  3536 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 12:55:48.323  1022  3083 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:55:48.323  3505  3529 W System.err: java.lang.IllegalArgumentException: Unknown package: com.sec.knox.setupwizardstub
03-17 12:55:48.323  3536  3536 D ActivityThread: Added TimaKeyStore provider
03-17 12:55:48.323  3505  3529 W System.err: 	at android.os.Parcel.readException(Parcel.java:1544)
03-17 12:55:48.323  3505  3529 W System.err: 	at android.os.Parcel.readException(Parcel.java:1493)
03-17 12:55:48.323  3505  3529 W System.err: 	at android.content.pm.IPackageManager$Stub$Proxy.setApplicationEnabledSetting(IPackageManager.java:4163)
03-17 12:55:48.323  3505  3529 W System.err: 	at android.app.ApplicationPackageManager.setApplicationEnabledSetting(ApplicationPackageManager.java:1925)
03-17 12:55:48.323  3505  3529 W System.err: 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.processInternal(StubPackageThread.java:88)
03-17 12:55:48.323  3505  3529 W System.err: 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.run(StubPackageThread.java:49)
,03-17 12:55:48.343  3554  3554 E Zygote  : MountEmulatedStorage()
03-17 12:55:48.343  3554  3554 I libpersona: KNOX_SDCARD checking this for 1000
03-17 12:55:48.343  3554  3554 E Zygote  : v2
03-17 12:55:48.343  3554  3554 I libpersona: KNOX_SDCARD not a persona
,03-17 12:55:48.353  1022  3083 I ActivityManager: Start proc com.sec.pcw.device for content provider com.sec.pcw.device/.contentprovider.DMProvider: pid=3554 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-17 12:55:48.363  1022  1083 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 12:55:48.363  3371  3371 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
03-17 12:55:48.363  3371  3371 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,03-17 12:55:48.363  1022  1083 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:55:48.363  1022  1083 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:55:48.363  1022  1083 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 12:55:48.383   258   258 I SurfaceFlinger: id=11 createSurf (1x1),1 flag=404, NainActivit
,03-17 12:55:48.393  3536  3536 D StatusChecker: onReceive : android.intent.action.BOOT_COMPLETED
,03-17 12:55:48.393  3536  3536 I StatusChecker: onReceive : net.mt.init : DONE
,03-17 12:55:48.393  1022  1234 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:55:48.393  1022  1234 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:48.393  1022  1234 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:48.393  1022  1234 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:48.403  1022  3059 D InputDispatcher: Focus entered window: 3371
,03-17 12:55:48.403  3371  3371 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
03-17 12:55:48.403  1022  1052 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-17 12:55:48.403  3371  3544 I OpenGLRenderer: Initialized EGL, version 1.4
03-17 12:55:48.403  1022  1052 D PointerIcon: setMouseCustomIcon IconType is same.101
,03-17 12:55:48.413  3563  3563 E Zygote  : MountEmulatedStorage()
03-17 12:55:48.413  3563  3563 E Zygote  : v2
,03-17 12:55:48.413  3554  3554 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-17 12:55:48.413  3563  3563 I libpersona: KNOX_SDCARD checking this for 10116
03-17 12:55:48.413  3563  3563 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-17 12:55:48.413  3563  3563 I libpersona: KNOX_SDCARD not a persona
03-17 12:55:48.413  3554  3554 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-17 12:55:48.413  1022  1234 I ActivityManager: Start proc com.sec.android.pagebuddynotisvc for broadcast com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvcBRcvr: pid=3563 uid=10116 gids={50116, 9997} abi=armeabi-v7a,
03-17 12:55:48.413  3563  3563 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-17 12:55:48.413  1022  1234 I ActivityManager: Killing 2689:com.android.calendar/u0a135 (adj 15): empty #31
03-17 12:55:48.413  3563  3563 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 12:55:48.423  3554  3554 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 12:55:48.423  3371  3544 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
03-17 12:55:48.423  3371  3544 D OpenGLRenderer: Enabling debug mode 0
,03-17 12:55:48.423  3239  3335 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(312/xPollingReportReStartAlarm)] 
03-17 12:55:48.423  3179  3179 D Finsky  : [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,03-17 12:55:48.423  3179  3179 D Finsky  : [1] 2.run: Finished loading 1 libraries.
,03-17 12:55:48.433  3488  3488 I ExternalOEMControlProvider: onCreate
,03-17 12:55:48.443  1022  1034 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:48.443  1022  1034 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:48.443  1022  1034 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:48.443  1022  1034 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:55:48.443  3179  3179 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,03-17 12:55:48.463  3585  3585 E Zygote  : MountEmulatedStorage()
,03-17 12:55:48.463  3585  3585 E Zygote  : v2
03-17 12:55:48.463  3585  3585 I libpersona: KNOX_SDCARD checking this for 1000
03-17 12:55:48.463  3585  3585 I libpersona: KNOX_SDCARD not a persona
,03-17 12:55:48.463  3585  3585 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-17 12:55:48.463  1022  1034 I ActivityManager: Start proc com.sec.android.app.servicemodeapp for broadcast com.sec.android.app.servicemodeapp/.ServiceModeAppBroadcastReceiver: pid=3585 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
03-17 12:55:48.463  1022  1034 I ActivityManager: Killing 2731:com.android.keychain/1000 (adj 15): empty #31
,03-17 12:55:48.473  3554  3554 D TimaKeyStoreProvider: TimaSignature is unavailable,
,03-17 12:55:48.473  3554  3554 D ActivityThread: Added TimaKeyStore provider
,03-17 12:55:48.473  3563  3563 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 12:55:48.473  3563  3563 D ActivityThread: Added TimaKeyStore provider
03-17 12:55:48.473  1022  1515 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
03-17 12:55:48.483  3585  3585 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 12:55:48.483  3585  3585 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 12:55:48.483  1022  3596 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-17 12:55:48.493  1022  1365 D SettingsProvider: name = PREVIOUS_SYS_TIME
03-17 12:55:48.493  1022  1365 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-17 12:55:48.493  1022  1365 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-17 12:55:48.493  1022  1365 D SettingsProvider: selectionArgs: false
03-17 12:55:48.493  1022  1365 D SettingsProvider: selectionArgs: 10062
03-17 12:55:48.493  1022  1365 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-17 12:55:48.493  1022  1365 D SettingsProvider: ret = -1
,03-17 12:55:48.493  1191  1191 I StatusBar: Icon Only
03-17 12:55:48.493  1191  1191 D PanelView: There is/are notification(s) 
,03-17 12:55:48.503  1022  2815 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 com.android.server.ssrm.ad.ec:-1 com.android.server.ssrm.ae.handleMessage:-1 android.os.Handler.dispatchMessage:102 android.os.Looper.loop:145 
,03-17 12:55:48.513  1022  1052 I ActivityManager: Displayed Component not be shown by security: +1s234ms
03-17 12:55:48.513  1022  1052 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1022  tag : ACTIVITY_RESUME_BOOSTER@7
,03-17 12:55:48.513  1022  1052 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{3ff24009 u0 com.test.thalitest/.MainActivity t236} time:38833
03-17 12:55:48.513  1022  1052 W ActivityManager: mDVFSHelper.release()
,03-17 12:55:48.513  3164  3206 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 0 sec
,03-17 12:55:48.513  3239  3336 I DBG_POLICYDM: [com.policydm.db.XDBProfileAdp(207/xdbSetChangedProtocol)] xdbSetChangedProtocol : false
03-17 12:55:48.513  1022  1047 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1022  pkgName : ACTIVITY_RESUME_BOOSTER@11
,03-17 12:55:48.523  1022  2863 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-17 12:55:48.523  1022  1365 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10062
,03-17 12:55:48.533  1022  3059 D SettingsProvider: name = PREVIOUS_ELAPSED_TIME
03-17 12:55:48.533  1022  3059 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-17 12:55:48.533  1022  3059 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-17 12:55:48.533  1022  3059 D SettingsProvider: selectionArgs: false
03-17 12:55:48.533  1022  3059 D SettingsProvider: selectionArgs: 10062
03-17 12:55:48.533  1022  3059 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-17 12:55:48.533  1022  3059 D SettingsProvider: ret = -1
,03-17 12:55:48.533  3371  3371 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@1e04951a time:38856
,03-17 12:55:48.543  3585  3585 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 12:55:48.543  1022  3059 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10062
,03-17 12:55:48.543  3585  3585 D ActivityThread: Added TimaKeyStore provider
,03-17 12:55:48.543  1191  1191 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 12:55:48.543  1191  1191 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,03-17 12:55:48.543  1822  1822 I SamsungIME: getCurrentCandidateView
,03-17 12:55:48.553  1191  1191 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,03-17 12:55:48.553  1191  1191 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 12:55:48.553  1022  1482 D ActivityManager: retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.RestoreService; callingUser = 0; userId(target) = 0
,03-17 12:55:48.553  1191  1191 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 12:55:48.553  1022  1482 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:55:48.553  1022  1482 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 12:55:48.553  1022  1482 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,03-17 12:55:48.553  1022  1034 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 12:55:48.563  1022  1034 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:55:48.563  1022  1034 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:55:48.563  1022  1034 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 12:55:48.563  1191  1191 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 12:55:48.563  1191  1191 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 12:55:48.573  1022  1046 W libprocessgroup: failed to open /acct/uid_10135/pid_2689/cgroup.procs: No such file or directory
03-17 12:55:48.573  1022  1046 W libprocessgroup: failed to open /acct/uid_1000/pid_2731/cgroup.procs: No such file or directory
,03-17 12:55:48.583  3239  3335 I DBG_POLICYDM: [com.policydm.XDMApplication(626/xdmStartAlarm)] Alarm ID: 1
,03-17 12:55:48.593  3239  3335 I DBG_POLICYDM: [com.policydm.agent.XDMTask(203/xdmAgentTaskHandler)] XEVENT_DM_INIT : Initialized
,03-17 12:55:48.593  1191  1191 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 12:55:48.613  1822  1822 D SamsungIME: Dismiss ExpandCandiate
03-17 12:55:48.613  3585  3585 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,03-17 12:55:48.623  3563  3563 I PageBuddyNotiSvc: Intent received : action=android.intent.action.BOOT_COMPLETED
,03-17 12:55:48.633  3554  3554 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
03-17 12:55:48.633  3554  3554 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
,03-17 12:55:48.643  3585  3585 I ServiceMode: received = ACTION_BOOT_COMPLETED
03-17 12:55:48.643  3585  3585 I ServiceMode: setReferenceIsDumpState : 0
,03-17 12:55:48.643  1022  1034 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:55:48.643  1022  1034 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:48.643  1022  1034 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:48.643  1022  1034 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:55:48.653  3612  3612 E Zygote  : MountEmulatedStorage()
,03-17 12:55:48.663  3612  3612 E Zygote  : v2,
03-17 12:55:48.663  3612  3612 I libpersona: KNOX_SDCARD checking this for 1000
03-17 12:55:48.663  3612  3612 I libpersona: KNOX_SDCARD not a persona
,03-17 12:55:48.663  3612  3612 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 12:55:48.663  1022  1034 I ActivityManager: Start proc com.wssnps for broadcast com.wssnps/.smlNpsReceiverDefault: pid=3612 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-17 12:55:48.663  3612  3612 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 12:55:48.663  3612  3612 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 12:55:48.663  1022  1034 I ActivityManager: Killing 2540:com.sec.android.gallery3d/u0a44 (adj 15): empty #31
,03-17 12:55:48.663  3563  3563 W ContextImpl: Implicit intents with startService are not safe: Intent { act=com.sec.android.pagebuddynotisvc } android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.pagebuddynotisvc.PageBuddyNotiSvcBRcvr.onReceive:-1 
,03-17 12:55:48.663  1022  3059 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
03-17 12:55:48.673  3554  3554 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
03-17 12:55:48.673  1022  3059 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:55:48.673  1022  3059 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 12:55:48.673  1022  3059 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.pagebuddynotisvc, destAppInfo.processName = com.sec.android.pagebuddynotisvc
,03-17 12:55:48.673  3563  3563 I PageBuddyNotiSvc: onCreate mCpBitFlag=0
,03-17 12:55:48.683  1022  1035 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:48.683  1022  1035 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:48.683  1022  1035 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:48.683  1022  1035 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:55:48.683  3612  3612 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:55:48.683  3612  3612 D ActivityThread: Added TimaKeyStore provider
,03-17 12:55:48.693  3627  3627 E Zygote  : MountEmulatedStorage()
,03-17 12:55:48.693  3627  3627 I libpersona: KNOX_SDCARD checking this for 10125
03-17 12:55:48.693  3627  3627 E Zygote  : v2
03-17 12:55:48.693  3627  3627 I libpersona: KNOX_SDCARD not a persona
03-17 12:55:48.703  3627  3627 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 12:55:48.703  1022  1035 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=3627 uid=10125 gids={50125, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
03-17 12:55:48.703  3627  3627 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-17 12:55:48.703  3627  3627 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 12:55:48.713  3239  3336 I DBG_POLICYDM: [com.policydm.db.XDBProfileListAdp(258/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,03-17 12:55:48.723  3179  3179 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,03-17 12:55:48.723  3554  3594 D PCWCLIENTTRACE_DMContentProvider: [URIMatcher] - result : 2
,03-17 12:55:48.733  1822  1822 I SamsungIME: getDebugLevel  : 0x4f4c
,03-17 12:55:48.733   258   439 I SurfaceFlinger: id=10 Removed uhalitest (7/8)
,03-17 12:55:48.733   258  3394 I SurfaceFlinger: id=10 Removed uhalitest (-2/8)
,03-17 12:55:48.733  3627  3627 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 12:55:48.733  3627  3627 D ActivityThread: Added TimaKeyStore provider
03-17 12:55:48.733  3239  3336 I DBG_POLICYDM: [com.policydm.db.XDBNotiAdp(38/xdbNotiExistInfo)] Noti Exist : false
,03-17 12:55:48.753  3470  3470 I DBG_FMMDM: [50.20.150420][Line:40][onCreate] FMMApplication NOT Start !
,03-17 12:55:48.753  3470  3470 I DBG_FMMDM: [50.20.150420][Line:67][onReceive] android.intent.action.BOOT_COMPLETED
03-17 12:55:48.753  3470  3470 I DBG_FMMDM: [50.20.150420][Line:309][onReceive] android.intent.action.BOOT_COMPLETED
,03-17 12:55:48.763  1022  1518 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:48.763  1022  1518 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:48.763  1022  1518 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:48.763  1022  1518 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:55:48.773  3627  3627 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-17 12:55:48.773  3627  3627 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
03-17 12:55:48.773  3627  3627 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,03-17 12:55:48.783  3645  3645 E Zygote  : MountEmulatedStorage()
03-17 12:55:48.783  3645  3645 I libpersona: KNOX_SDCARD checking this for 1000
03-17 12:55:48.783  3645  3645 E Zygote  : v2
03-17 12:55:48.783  3645  3645 I libpersona: KNOX_SDCARD not a persona
03-17 12:55:48.783  3645  3645 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 12:55:48.783  3645  3645 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-17 12:55:48.783  1022  1518 I ActivityManager: Start proc com.fmm.ds for broadcast com.fmm.ds/.XDSBroadcastReceiver: pid=3645 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-17 12:55:48.783  3645  3645 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 12:55:48.783  1022  1518 I ActivityManager: Killing 2875:flipboard.boxer.app/u0a99 (adj 15): empty #31
,03-17 12:55:48.783  1022  1518 I ActivityManager: Killing 2844:com.android.email/u0a145 (adj 15): empty #32
,03-17 12:55:48.793  1022  1046 W libprocessgroup: failed to open /acct/uid_10044/pid_2540/cgroup.procs: No such file or directory
,03-17 12:55:48.813  3645  3645 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:55:48.813  3645  3645 D ActivityThread: Added TimaKeyStore provider
,03-17 12:55:48.813  1022  1365 I ActivityManager: Killing 2924:com.sec.usbsettings/1000 (adj 15): empty #31
03-17 12:55:48.813  1022  1365 I ActivityManager: Killing 2278:flipboard.app/u0a98 (adj 15): empty #32
,03-17 12:55:48.813  1022  1022 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1022  tag : ACTIVITY_RESUME_BOOSTER@11
,03-17 12:55:48.833  3612  3612 D NPS_WSSNPS: [] android.intent.action.BOOT_COMPLETED
,03-17 12:55:48.833  3612  3612 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.wssnps.smlNpsReceiverDefault.onReceive:35 android.app.ActivityThread.handleReceiver:3125 
,03-17 12:55:48.833  1022  1083 D ActivityManager: retrieveServiceLocked(): component = com.wssnps/com.wssnps.smlNpsService; callingUser = 0; userId(target) = 0
,03-17 12:55:48.833  1022  1083 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:55:48.833  1022  1083 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 12:55:48.833  1022  1083 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.wssnps, destAppInfo.processName = com.wssnps
,03-17 12:55:48.843  1022  3083 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:48.843  1022  3083 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:48.843  1022  3083 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:48.843  1022  3083 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:55:48.843  3612  3612 D NPS_WSSNPS: [] Service onCreate!!
,03-17 12:55:48.853  3179  3179 V Finsky  : [1] GearheadStateMonitor.onReady: sIsProjecting:false
,03-17 12:55:48.853  3371  3371 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3371
,03-17 12:55:48.863  3662  3662 E Zygote  : MountEmulatedStorage()
03-17 12:55:48.863  3662  3662 I libpersona: KNOX_SDCARD checking this for 1000
03-17 12:55:48.863  3662  3662 E Zygote  : v2
03-17 12:55:48.863  3662  3662 I libpersona: KNOX_SDCARD not a persona
03-17 12:55:48.863  3662  3662 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 12:55:48.873  3662  3662 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 12:55:48.873  3662  3662 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 12:55:48.873  1022  3083 I ActivityManager: Start proc com.samsung.android.app.accesscontrol for broadcast com.samsung.android.app.accesscontrol/.AccessControlReceiver: pid=3662 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-17 12:55:48.893  3612  3669 D NPS_WSSNPS: [50.150321] NpsServiceTask Start
,03-17 12:55:48.893  1022  1482 V VibratorService: hasVibrator - useVibetonz: true
,03-17 12:55:48.893  1022  1046 W libprocessgroup: failed to open /acct/uid_1000/pid_2924/cgroup.procs: No such file or directory
03-17 12:55:48.893  1022  1046 W libprocessgroup: failed to open /acct/uid_10099/pid_2875/cgroup.procs: No such file or directory
,03-17 12:55:48.903  1022  1046 W libprocessgroup: failed to open /acct/uid_10145/pid_2844/cgroup.procs: No such file or directory
,03-17 12:55:48.903  1022  1046 W libprocessgroup: failed to open /acct/uid_10098/pid_2278/cgroup.procs: No such file or directory
,03-17 12:55:48.913   310   310 I art     : Explicit concurrent mark sweep GC freed 8800(375KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 706us total 38.757ms
,03-17 12:55:48.923  3612  3612 D NPS_WSSNPS: [50.150321] smlDBHelper
,03-17 12:55:48.933  1822  1822 I SamsungIME: getDebugLevel  : 0x4f4c
,03-17 12:55:48.933   310   310 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 636us total 18.839ms
,03-17 12:55:48.943  3662  3662 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 12:55:48.943  3662  3662 D ActivityThread: Added TimaKeyStore provider
,03-17 12:55:48.953   310   310 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 614us total 19.343ms
,03-17 12:55:49.003  3627  3627 D QuickConnect: PeriphStartReceiver.onReceive - android.intent.action.BOOT_COMPLETED
,03-17 12:55:49.003  3627  3627 D QuickConnect: Util.setSCRunningSetting - [value]0
,03-17 12:55:49.003  1022  1506 D SettingsProvider: name = scon_is_running
,03-17 12:55:49.003  1022  1506 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-17 12:55:49.003  1022  1506 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-17 12:55:49.003  1022  1506 D SettingsProvider: selectionArgs: false
03-17 12:55:49.003  1022  1506 D SettingsProvider: selectionArgs: 10125
03-17 12:55:49.003  1022  1506 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-17 12:55:49.003  1022  1506 D SettingsProvider: ret = -1
,03-17 12:55:49.013  1822  1822 I SamsungIME: KeybaordView init() : load resources
,03-17 12:55:49.023  1022  3059 D SettingsProvider: name = access_control_enabled
,03-17 12:55:49.023  1022  1518 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:55:49.023  1022  1518 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:49.023  1022  1518 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:55:49.023  1022  1518 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:55:49.033  3645  3645 I DBG_FMMDS: [50.18.150420][Line:56][onCreate] FMMDS Application Start
,03-17 12:55:49.033  3612  3612 I NPS_WSSNPS: [50.150321] AsyncBulkFlagCheck
,03-17 12:55:49.033  3645  3645 I DBG_FMMDS: [50.18.150420][Line:28][<init>] XDBHelper First Call!!!
,03-17 12:55:49.043  3682  3682 E Zygote  : MountEmulatedStorage()
,03-17 12:55:49.043  3682  3682 E Zygote  : v2
03-17 12:55:49.043  3682  3682 I libpersona: KNOX_SDCARD checking this for 10069
,03-17 12:55:49.043  3682  3682 I libpersona: KNOX_SDCARD not a persona
03-17 12:55:49.043  3682  3682 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 12:55:49.043  3612  3681 I NPS_WSSNPS: [50.150321] IsRemain_AsyncBulkCheck,
,03-17 12:55:49.043  3612  3681 I NPS_WSSNPS: [50.150321] IsRemain_Asyncing nothing
03-17 12:55:49.043  3612  3681 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:2069 android.content.ContextWrapper.stopService:538 com.wssnps.h.run:107 java.util.Timer$TimerImpl.run:284 <bottom of call stack> 
,03-17 12:55:49.043  3682  3682 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 12:55:49.053  1022  1518 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=3682 uid=10069 gids={50069, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-17 12:55:49.053  1022  1518 I ActivityManager: Killing 2378:com.android.mms/u0a46 (adj 15): empty #31,
03-17 12:55:49.053  3682  3682 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 12:55:49.053  1022  3133 D ActivityManager: retrieveServiceLocked(): component = com.wssnps/com.wssnps.smlNpsService; callingUser = 0; userId(target) = 0
,03-17 12:55:49.053  1022  3133 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:55:49.053  1022  3133 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 12:55:49.053  1022  3133 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.wssnps, destAppInfo.processName = com.wssnps
03-17 12:55:49.063  3612  3612 D NPS_WSSNPS: [50.150321] Service onDestroy
,03-17 12:55:49.073  3612  3612 I NPS_WSSNPS: [50.150321] smlBRConfigurationDelete
,03-17 12:55:49.073  3612  3612 I NPS_WSSNPS: [50.150321] smlBRMessageDelete
,03-17 12:55:49.073  3554  3594 D PCWCLIENTTRACE_DMContentProvider: [URIMatcher] - result : 2
03-17 12:55:49.073  3612  3612 I NPS_WSSNPS: [50.150321] smlBREmailDelete
03-17 12:55:49.073  3612  3612 I NPS_WSSNPS: [50.150321] smlBRNetworkDelete
03-17 12:55:49.073  3612  3612 I NPS_WSSNPS: [50.150321] smlBRCallLogDelete
03-17 12:55:49.073  3612  3612 I NPS_WSSNPS: [50.150321] smlBRMiniDiaryDelete
,03-17 12:55:49.073  3612  3612 I NPS_WSSNPS: [50.150321] smlBRPenMemoMDelete
03-17 12:55:49.073  3612  3612 I NPS_WSSNPS: [50.150321] smlBRSMemoDelete
,03-17 12:55:49.073  3645  3645 E DBG_FMMDS: Warning!!! [50.18.150420][Line:36][xdsDevAdpGetDeviceID] DeviceID read fail!!!!!!!!
,03-17 12:55:49.083  3682  3682 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 12:55:49.083  3612  3612 I NPS_WSSNPS: [50.150321] cpuBooster release : false
03-17 12:55:49.083  3682  3682 D ActivityThread: Added TimaKeyStore provider
03-17 12:55:49.083  1022  1506 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10125,
,03-17 12:55:49.103  3627  3627 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care ACTION_BOOT_COMPLETED. run P service
,03-17 12:55:49.103  3612  3612 D NPS_WSSNPS: [50.150321] dsServerSocket close
,03-17 12:55:49.103  1191  1191 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 12:55:49.113  1822  1822 I SamsungIME: getCurrentKeyboard
,03-17 12:55:49.113  3645  3645 I DBG_FMMDS: [50.18.150420][Line:43][xdbDBInit] 
03-17 12:55:49.113  1822  1822 I SamsungIME: getTextKeyboard
,03-17 12:55:49.113  1022  1506 D CountryDetector: No listener is left
,03-17 12:55:49.123  3627  3627 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,03-17 12:55:49.123  1022  1365 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:55:49.123  1022  1365 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:49.123  1022  1365 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:49.123  1022  1365 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:55:49.133  2674  3155 I FactoryTestApp: [IPCWriterToSecPhoneService$disConnectSecPhoneService](3155)  
,03-17 12:55:49.133  1022  1046 W libprocessgroup: failed to open /acct/uid_10046/pid_2378/cgroup.procs: No such file or directory,
,03-17 12:55:49.143  3697  3697 E Zygote  : MountEmulatedStorage(),
03-17 12:55:49.143  3697  3697 E Zygote  : v2
03-17 12:55:49.143  3697  3697 I libpersona: KNOX_SDCARD checking this for 10131,
03-17 12:55:49.143  3697  3697 I libpersona: KNOX_SDCARD not a persona
,03-17 12:55:49.143  3697  3697 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,03-17 12:55:49.143  1022  1365 I ActivityManager: Start proc com.sec.android.app.sbrowser for broadcast com.sec.android.app.sbrowser/.net.NetworkSettingsReceiver: pid=3697 uid=10131 gids={50131, 9997, 1023, 3003, 1028, 1015, 1007, 3001, 3002} abi=armeabi-v7a
03-17 12:55:49.143  1022  1365 I ActivityManager: Killing 2747:com.google.android.apps.books/u0a75 (adj 15): empty #31
,03-17 12:55:49.153  3697  3697 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,03-17 12:55:49.153  3697  3697 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 12:55:49.163  1022  3083 I ActivityManager: Killing 3005:com.sec.android.app.safetyassurance/u0a48 (adj 15): empty #31
,03-17 12:55:49.173  3371  3371 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,03-17 12:55:49.193  3697  3697 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:55:49.203  3697  3697 D ActivityThread: Added TimaKeyStore provider
,03-17 12:55:49.213  3682  3682 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.intent.action.BOOT_COMPLETED // null
,03-17 12:55:49.233  1822  1822 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,03-17 12:55:49.243  3697  3697 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
03-17 12:55:49.243  3697  3697 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-17 12:55:49.243  3697  3697 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
03-17 12:55:49.243  3697  3697 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,03-17 12:55:49.273  1335  3142 I LockPatternUtils: isSmartCardAuthenticationAvailable: false
,03-17 12:55:49.353  1914  3607 D FileApkUtils: Spent 58ms computing apk sha1.
,03-17 12:55:49.353  1914  3607 D FileApkUtils: Module already staged or being staged:chimera-modules/MapsModule.apk
,03-17 12:55:49.353  1914  3607 I art     : DexFile_isDexOptNeeded failed to open oat file '/data/dalvik-cache/arm/data@data@com.google.android.gms@app_chimera@chimera-module-root@module-d5b20f1a6029cea405dc44dd827a138ee4ccf8cc@MapsModule.apk@classes.dex' for file location '/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d5b20f1a6029cea405dc44dd827a138ee4ccf8cc/MapsModule.apk': Failed to open oat filename for reading: No such file or directory
,03-17 12:55:49.363  1914  3607 D DexOptUtils: Module /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d5b20f1a6029cea405dc44dd827a138ee4ccf8cc/MapsModule.apk appears to be unoptimized.,
03-17 12:55:49.363  1914  3607 D DexOptUtils: Lollipop platform, using <isa> directory.
03-17 12:55:49.363  1914  3607 D DexOptUtils: Instantiating DexClassLoader to force creation of odex.
03-17 12:55:49.363  1914  3607 D DexOptUtils: Primary ABI of odexing process is armeabi-v7a
,03-17 12:55:49.403  1914  1914 W InstanceID/Rpc: Found 10012
,03-17 12:55:49.443  3715  3715 I dex2oat : ----------------------------------------------------
,03-17 12:55:49.443  3697  3697 D SBrowserFeatureFlag: initialized in static block : loadCscFeatureValue() succeed! 
,03-17 12:55:49.453  3715  3715 I dex2oat : <SS>: S T A R T I N G . . .
03-17 12:55:49.453  3715  3715 I dex2oat : <SS>: Zip is absent. Canceled.
,03-17 12:55:49.453  3715  3715 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --compiler-filter=interpret-only --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d5b20f1a6029cea405dc44dd827a138ee4ccf8cc/MapsModule.apk --oat-fd=94 --art-fd=-1 --oat-location=/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d5b20f1a6029cea405dc44dd827a138ee4ccf8cc/arm/MapsModule.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,03-17 12:55:49.493  1022  3060 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.app.service.BootCompletedBroadcastService; callingUser = 0; userId(target) = 0
,03-17 12:55:49.493  1022  3060 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:55:49.493  1022  3060 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:55:49.493  1022  3060 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-17 12:55:49.523  1022  1534 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.verifier.InternalApkUploadService; callingUser = 0; userId(target) = 0
,03-17 12:55:49.523  1022  1534 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:55:49.523  1022  1534 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:55:49.523  1022  1534 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-17 12:55:49.523  3164  3206 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 1 sec
,03-17 12:55:49.543  1191  1191 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-17 12:55:49.543  1191  1191 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-17 12:55:49.543  1191  1191 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 12:55:49.543  1191  1191 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 12:55:49.543  1191  1191 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 12:55:49.543  1191  1191 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 12:55:49.553  3371  3606 D jxcore_app_log: JniHelper::setJavaVM(0xb82c0450), pthread_self() = -1199411624
,03-17 12:55:49.563  3645  3645 I DBG_FMMDS: [50.18.150420][Line:63][onCreate] onCreate Db Initialized
,03-17 12:55:49.563  3645  3645 I DBG_FMMDS: [50.18.150420][Line:363][xdsGetAccount] UZnlD2ITkPmcCbh9srjpN/1auPpXZ1U0673eFrlr5G7ujCmOnoTUvn8Wy3q3+o8W
,03-17 12:55:49.563  3645  3645 I DBG_FMMDS: [50.18.150420][Line:279][xdsDefaultProfileCheckServerID] VG44Fy9kdMk+/k3D4uP4d3do/3rw5AoymvTy0wXAnzc=
03-17 12:55:49.573  3645  3645 I DBG_FMMDS: [50.18.150420][Line:363][xdsGetAccount] UZnlD2ITkPmcCbh9srjpN/1auPpXZ1U0673eFrlr5G7ujCmOnoTUvn8Wy3q3+o8W
03-17 12:55:49.573  3645  3645 I DBG_FMMDS: [50.18.150420][Line:376][xdsCheckSamsungAccountForChina] VG44Fy9kdMk+/k3D4uP4d3do/3rw5AoymvTy0wXAnzc=
03-17 12:55:49.573  3645  3645 I DBG_FMMDS: [50.18.150420][Line:89][onReceive] Receive Intent : android.intent.action.BOOT_COMPLETED
,03-17 12:55:49.573  3645  3645 I DBG_FMMDS: [50.18.150420][Line:248][onReceive] XCOMMON_INTENT_NOTI_CALLLOG_CLICK
,03-17 12:55:49.583  1022  1518 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.reminders.notification.NotificationService; callingUser = 0; userId(target) = 0
,03-17 12:55:49.593  1022  1518 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:55:49.593  1022  1518 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:55:49.593  1022  1518 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-17 12:55:49.593  1022  3060 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.checkin.CheckinService; callingUser = 0; userId(target) = 0
03-17 12:55:49.593  1022  3060 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:55:49.593  1022  3060 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:55:49.593  1022  3060 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-17 12:55:49.603  3371  3606 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
03-17 12:55:49.603  3371  3606 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
03-17 12:55:49.603  3371  3606 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
03-17 12:55:49.603  3371  3606 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
03-17 12:55:49.603  3371  3606 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
03-17 12:55:49.603  3371  3606 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9be6b1 added. We now have 1 listener(s)
03-17 12:55:49.613  1022  1234 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.sharing.service.NearbySharingService; callingUser = 0; userId(target) = 0
,03-17 12:55:49.623  1022  1046 W libprocessgroup: failed to open /acct/uid_10048/pid_3005/cgroup.procs: No such file or directory
,03-17 12:55:49.633  1022  1046 W libprocessgroup: failed to open /acct/uid_10075/pid_2747/cgroup.procs: No such file or directory
,03-17 12:55:49.643  3371  3606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 7C:F9:0E:51:18:22
,03-17 12:55:49.643  3371  3606 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"7C:F9:0E:51:18:22"}
,03-17 12:55:49.643  3371  3606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"name":"<no peer name>","address":"7C:F9:0E:51:18:22"}
03-17 12:55:49.643  3371  3606 D org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setHandshakeRequired: true -> false
,03-17 12:55:49.643  3371  3606 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setHandshakeRequired: true -> false
03-17 12:55:49.653  3371  3606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
03-17 12:55:49.653  3371  3606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
03-17 12:55:49.653  3371  3606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
03-17 12:55:49.653  3371  3606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 7C:F9:0E:51:18:22
03-17 12:55:49.653  3371  3606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
03-17 12:55:49.653  3371  3606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
03-17 12:55:49.653  3371  3606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
03-17 12:55:49.653  3371  3606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
03-17 12:55:49.653  3371  3606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
03-17 12:55:49.653  3371  3606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
03-17 12:55:49.653  3371  3606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@37153f04 added. We now have 1 listener(s)
03-17 12:55:49.653  3371  3606 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,03-17 12:55:49.653  1022  1515 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.update.SystemUpdateService; callingUser = 0; userId(target) = 0
,03-17 12:55:49.653  1022  1515 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:55:49.653  1022  1515 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:55:49.653  1022  1515 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 12:55:49.663  1022  1083 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.config.ConfigFetchService; callingUser = 0; userId(target) = 0
,03-17 12:55:49.673  1022  1083 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:55:49.673  1022  1083 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:55:49.673  1022  1083 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 12:55:49.673  1914  3721 D GCM     : COMPAT: Multi user not supported
,03-17 12:55:49.683  3371  3606 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
,03-17 12:55:49.683  1022  1083 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,03-17 12:55:49.683  3371  3606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
03-17 12:55:49.683  3371  3606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
03-17 12:55:49.683  3371  3606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
03-17 12:55:49.683  3371  3606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,03-17 12:55:49.683  1022  1083 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:55:49.683  1022  1083 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 12:55:49.683  1022  1083 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 12:55:49.683  1022  1515 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.recovery.AccountRecoveryBackgroundService; callingUser = 0; userId(target) = 0
,03-17 12:55:49.693  3371  3606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-17 12:55:49.693  1022  1515 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:55:49.693  1022  1515 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:55:49.693  1022  1515 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 12:55:49.693  1022  1506 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.authzen.GcmReceiverService; callingUser = 0; userId(target) = 0
,03-17 12:55:49.693  3371  3606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 7C:F9:0E:51:18:22
,03-17 12:55:49.693  1022  1506 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:55:49.693  1022  1506 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 12:55:49.693  1022  1506 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 12:55:49.713  3371  3606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-17 12:55:49.713  3371  3606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-17 12:55:49.713  3371  3606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-17 12:55:49.713  3371  3606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-17 12:55:49.713  3371  3606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-17 12:55:49.713  3371  3606 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-17 12:55:49.713  3371  3606 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-17 12:55:49.713  3371  3606 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
03-17 12:55:49.713  3371  3606 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
03-17 12:55:49.713  3371  3606 D io.jxcore.node.ConnectivityMonitor: start: OK
,03-17 12:55:49.743  1696  3736 D GCM     : GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED
,03-17 12:55:49.753  1914  3743 I CheckinService: Disabling old GoogleServicesFramework version
,03-17 12:55:49.773  1022  1361 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,03-17 12:55:49.773  1022  1361 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:55:49.773  1022  1361 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:55:49.773  1022  1361 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 12:55:49.813  1022  1515 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.tron.CollectionService; callingUser = 0; userId(target) = 0
,03-17 12:55:49.813  3371  3371 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-17 12:55:49.813  1022  1515 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:55:49.813  1022  1515 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 12:55:49.823  3371  3371 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-17 12:55:49.823  1022  1515 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 12:55:49.823  1914  1914 D SystemUpdateService: onCreate
,03-17 12:55:49.833  1022  3060 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.location.internal.GoogleLocationManagerService; callingUser = 0; userId(target) = 0
,03-17 12:55:49.833  3371  3371 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,03-17 12:55:49.833  1022  3060 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:55:49.833  1022  3060 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:55:49.833  1022  3060 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 12:55:49.833  1022  1506 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,03-17 12:55:49.833  1022  1506 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:55:49.833  1022  1506 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 12:55:49.833  1022  1506 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 12:55:49.853  1914  3721 I GCoreUlr: Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}]
,03-17 12:55:49.853  1022  1534 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.location.reporting.service.DispatchingService; callingUser = 0; userId(target) = 0
,03-17 12:55:49.863  1022  1534 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:55:49.863  1022  1534 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 12:55:49.863  1022  1534 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 12:55:49.873  1914  1914 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,03-17 12:55:49.873  1335  3142 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver$InitSerachDBThread.run:130 <bottom of call stack> 
,03-17 12:55:49.893  1022  1534 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 12:55:49.893  1335  3142 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver$InitSerachDBThread.run:131 <bottom of call stack> 
,03-17 12:55:49.903  3697  3697 D ManifestProvider: onCreate()
,03-17 12:55:49.913  1022  1534 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:55:49.913  1022  1534 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:55:49.913  1022  1534 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 12:55:49.913  1696  1696 I ConfigService: onCreate
,03-17 12:55:49.923  1914  1914 I ConfigFetchService: onStartCommand Intent { cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,03-17 12:55:49.923  1022  3133 I ActivityManager: Killing 3025:com.sec.dsm.system/1000 (adj 15): empty #31
,03-17 12:55:49.933   289   289 E SMD     : DCD OFF
,03-17 12:55:49.933  1022  1234 I ActivityManager: Killing 1941:com.android.defcontainer/u0a4 (adj 15): empty #31
,03-17 12:55:49.933  1914  3752 V AuthZen : Handling intent: android.intent.action.BOOT_COMPLETED
,03-17 12:55:49.943  1022  1365 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 12:55:49.943  1914  3752 D AuthZenEventHandler: Handling event: android.intent.action.BOOT_COMPLETED
,03-17 12:55:49.943  1022  1365 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:55:49.943  1022  1365 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:55:49.943  1335  3142 I SettingSearch/SearchIntentReceiver: InitSerachDBThread thread end!
03-17 12:55:49.943  1022  1365 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 12:55:49.953  1022  1034 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,03-17 12:55:49.953  1022  1034 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:55:49.953  1022  1034 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:55:49.953  1022  1034 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 12:55:49.953  1022  1022 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.dsi.ant.server.AntService.startService:135 com.dsi.ant.server.startup.BootCompletedReceiver.onReceive:41 
,03-17 12:55:49.953  1022  1022 W ContextImpl: Implicit intents with startService are not safe: Intent { act=com.dsi.ant.server.IAntHal } android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.dsi.ant.server.AntService.startService:135 
03-17 12:55:49.953  1022  1022 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 12:55:49.953  3697  3697 E NetworkSettingsReceiver: onReceive: android.intent.action.BOOT_COMPLETED
,03-17 12:55:49.963  1022  1022 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:49.963  3337  3337 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
03-17 12:55:49.963  1022  1022 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:49.963  1022  1022 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:49.963  1022  1022 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:55:49.973  1022  1022 I ActivityManager: Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=3758 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-17 12:55:49.983  1022  1515 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 12:55:49.983  3758  3758 E Zygote  : MountEmulatedStorage()
03-17 12:55:49.983  3758  3758 I libpersona: KNOX_SDCARD checking this for 1000
03-17 12:55:49.983  3758  3758 E Zygote  : v2
03-17 12:55:49.983  3758  3758 I libpersona: KNOX_SDCARD not a persona
,03-17 12:55:49.983  3758  3758 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 12:55:49.983  3758  3758 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 12:55:49.983  3758  3758 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 12:55:49.993  1022  1515 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:55:49.993  1022  1515 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:55:49.993  1022  1515 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 12:55:50.013  3371  3390 I art     : Background sticky concurrent mark sweep GC freed 30663(1986KB) AllocSpace objects, 9(146KB) LOS objects, 8% free, 10MB/11MB, paused 1.468ms total 122.783ms
,03-17 12:55:50.023  1914  3752 W BaseAppContext: Using Auth Proxy for data requests.
,03-17 12:55:50.043  3758  3758 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:55:50.043  3758  3758 D ActivityThread: Added TimaKeyStore provider
,03-17 12:55:50.053  1914  1914 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,03-17 12:55:50.053  1914  3752 I GLSUser : [ChannelManager] Attempting to channel bind connection HttpClient.
,03-17 12:55:50.073  1914  1914 I Kids    : [GCoreUtils] Current gmscore version, 7899436 is smaller than the required version 8400000
,03-17 12:55:50.073  1914  3752 I GLSUser : [ChannelManager] Checking whether channelId is enabled. isEnabledGmsCore? false, isEnabledSdk? true, isAtLeastKitKat? true
,03-17 12:55:50.083  1914  1914 I ConfigFetchService: service connected
,03-17 12:55:50.083  1022  3083 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.api.credentials.sync.CredentialSyncReceiverService; callingUser = 0; userId(target) = 0
,03-17 12:55:50.113  1022  3083 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:55:50.113  1022  3083 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:55:50.113  1022  3083 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 12:55:50.113  3337  3337 W FOTA_Client: [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,03-17 12:55:50.123  1022  3059 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:50.123  1022  3059 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:50.123  1022  3059 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:50.123  1022  3059 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:55:50.153  3781  3781 E Zygote  : MountEmulatedStorage()
03-17 12:55:50.153  3781  3781 I libpersona: KNOX_SDCARD checking this for 10014
03-17 12:55:50.153  3781  3781 E Zygote  : v2
03-17 12:55:50.153  3781  3781 I libpersona: KNOX_SDCARD not a persona
,03-17 12:55:50.153  3781  3781 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-17 12:55:50.153  1022  3059 I ActivityManager: Start proc com.google.android.onetimeinitializer for broadcast com.google.android.onetimeinitializer/.OneTimeInitializerReceiver: pid=3781 uid=10014 gids={50014, 9997} abi=armeabi-v7a
,03-17 12:55:50.153  3781  3781 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-17 12:55:50.153  1022  3059 I ActivityManager: Killing 2907:com.sec.android.app.clockpackage/u0a85 (adj 15): empty #31
,03-17 12:55:50.153  3781  3781 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
,03-17 12:55:50.163  1022  1046 W libprocessgroup: failed to open /acct/uid_10004/pid_1941/cgroup.procs: No such file or directory
,03-17 12:55:50.213  1914  1914 D ConfigFetchService: ConfigApi connection successful.
,03-17 12:55:50.213  1022  3059 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:50.213  1022  3059 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:50.213  1022  3059 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:50.213  1022  3059 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:55:50.223  3697  3697 E SBrowserFeatureFlag: initSupportedPkg: checkExistService com.samsung.android.smartclip.SpenGestureManager@1566f13f
,03-17 12:55:50.223  1022  3059 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.BootReceiver: pid=3797 uid=10104 gids={50104, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,03-17 12:55:50.233  3797  3797 E Zygote  : MountEmulatedStorage()
03-17 12:55:50.233  3797  3797 E Zygote  : v2,
03-17 12:55:50.233  3697  3697 D SBrowserFeatureFlag: initialize : initSupportedPkg() succeed! 
03-17 12:55:50.233  1022  3133 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
03-17 12:55:50.233  3697  3697 I VerificationLog: SbrowserSettings- url content://com.sec.android.app.sbrowser/readinglist/pinned.mhtml
03-17 12:55:50.233  1022  3133 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:55:50.233  1022  3133 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:55:50.233  1022  3133 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-17 12:55:50.233  3797  3797 I libpersona: KNOX_SDCARD checking this for 10104
03-17 12:55:50.233  3797  3797 I libpersona: KNOX_SDCARD not a persona
,03-17 12:55:50.233  3797  3797 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 12:55:50.233  3781  3781 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 12:55:50.243  3781  3781 D ActivityThread: Added TimaKeyStore provider
,03-17 12:55:50.243  3797  3797 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 12:55:50.243  3797  3797 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-17 12:55:50.253  1763  1763 I GCoreUlr: DispatchingService.onCreate()
,03-17 12:55:50.273  1022  3059 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:50.273  1022  3059 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:50.273  1022  3059 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:50.273  1022  3059 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:55:50.273  1914  3752 I AuthZen : Fetching signing key...
,03-17 12:55:50.283  3813  3813 E Zygote  : MountEmulatedStorage()
03-17 12:55:50.283  3813  3813 I libpersona: KNOX_SDCARD checking this for 10135
03-17 12:55:50.283  3813  3813 E Zygote  : v2
03-17 12:55:50.283  3813  3813 I libpersona: KNOX_SDCARD not a persona
,03-17 12:55:50.293  3813  3813 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-17 12:55:50.293  3813  3813 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 12:55:50.293  3813  3813 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 12:55:50.293  1022  3059 I ActivityManager: Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=3813 uid=10135 gids={50135, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,03-17 12:55:50.293  1022  3059 I ActivityManager: Killing 3064:com.sec.android.app.factorykeystring/1000 (adj 15): empty #31
,03-17 12:55:50.303  1022  1046 W libprocessgroup: failed to open /acct/uid_1000/pid_3025/cgroup.procs: No such file or directory
03-17 12:55:50.303  1022  1046 W libprocessgroup: failed to open /acct/uid_10085/pid_2907/cgroup.procs: No such file or directory
,03-17 12:55:50.303  3797  3797 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:55:50.303  3797  3797 D ActivityThread: Added TimaKeyStore provider
,03-17 12:55:50.313  1914  3752 I AuthZen : Signing key fetched successfully!
,03-17 12:55:50.383  3813  3813 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:55:50.383  3813  3813 D ActivityThread: Added TimaKeyStore provider
,03-17 12:55:50.393  1914  3752 W BaseAppContext: Using Auth Proxy for data requests.
,03-17 12:55:50.413  1914  3752 I AuthZen : Starting Enrollment...
,03-17 12:55:50.503  1914  2165 I art     : Explicit concurrent mark sweep GC freed 35466(2MB) AllocSpace objects, 41(656KB) LOS objects, 40% free, 11MB/19MB, paused 1.675ms total 123.179ms
,03-17 12:55:50.523  3797  3797 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-17 12:55:50.543  1191  1191 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-17 12:55:50.543  1191  1191 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-17 12:55:50.543  1191  1191 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 12:55:50.543  1191  1191 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 12:55:50.543  1191  1191 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 12:55:50.543  1191  1191 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 12:55:50.583  1696  2809 I art     : Explicit concurrent mark sweep GC freed 11053(716KB) AllocSpace objects, 7(172KB) LOS objects, 40% free, 10MB/17MB, paused 960us total 64.543ms
,03-17 12:55:50.593  1914  3752 D AuthZen : getting auth token. Attempt 0
,03-17 12:55:50.593  1022  1234 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,03-17 12:55:50.603  1022  1234 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:55:50.603  1022  1234 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:55:50.603  1022  1234 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 12:55:50.633  1914  3749 I SystemUpdateService: cancelUpdate (empty URL)
,03-17 12:55:50.633  1914  3749 I SystemUpdateService: active receiver: disabled
,03-17 12:55:50.643  3164  3206 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 2 sec
,03-17 12:55:50.653  3813  3813 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,03-17 12:55:50.653  3813  3813 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-17 12:55:50.653  3813  3813 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-17 12:55:50.663  1022  1083 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 12:55:50.683  1022  1083 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:55:50.683  1022  1083 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:55:50.683  1022  1083 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-17 12:55:50.683  3758  3758 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:53 android.app.ActivityThread.handleReceiver:3125 
,03-17 12:55:50.683  1022  1534 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
,03-17 12:55:50.683  1022  1534 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:55:50.683  1022  1534 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 12:55:50.683  1022  1534 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,03-17 12:55:50.693  1022  3059 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:55:50.693  1022  3059 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:55:50.693  1022  3059 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:50.693  1022  3059 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:55:50.703  3830  3830 E Zygote  : MountEmulatedStorage()
03-17 12:55:50.703  3830  3830 E Zygote  : v2
03-17 12:55:50.703  3830  3830 I libpersona: KNOX_SDCARD checking this for 1000
03-17 12:55:50.703  3830  3830 I libpersona: KNOX_SDCARD not a persona
,03-17 12:55:50.703  3830  3830 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,03-17 12:55:50.713  1022  3059 I ActivityManager: Start proc com.samsung.android.bbc.bbcagent for broadcast com.samsung.android.bbc.bbcagent/.bbccontroller.receiver.BootCompletedReceiver: pid=3830 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
,03-17 12:55:50.713  3830  3830 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,03-17 12:55:50.713  3830  3830 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,03-17 12:55:50.733  3781  3781 V OneTimeInitializerReceiver: OneTimeInitializerReceiver.onReceive
,03-17 12:55:50.823  1022  1482 D ActivityManager: retrieveServiceLocked(): component = com.google.android.onetimeinitializer/com.google.android.onetimeinitializer.OneTimeService; callingUser = 0; userId(target) = 0
,03-17 12:55:50.823  1022  1046 W libprocessgroup: failed to open /acct/uid_1000/pid_3064/cgroup.procs: No such file or directory
,03-17 12:55:50.833  1022  1482 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:55:50.833  1022  1482 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:55:50.833  1022  1482 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.onetimeinitializer, destAppInfo.processName = com.google.android.onetimeinitializer
,03-17 12:55:50.853  3830  3830 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:55:50.853  3830  3830 D ActivityThread: Added TimaKeyStore provider
,03-17 12:55:50.883  1696  1829 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cryptauth
,03-17 12:55:50.883  1696  1829 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cryptauth without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-17 12:55:50.883  1696  1829 I GLSUser : [GLSUser] Extracting token using key: Auth
03-17 12:55:50.883  1696  1829 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-17 12:55:50.893  1696  1829 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 12:55:50.893  1022  1515 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,03-17 12:55:50.893  1022  1515 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:55:50.893  1022  1515 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:55:50.893  1022  1515 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-17 12:55:50.903  1914  3752 E AuthZen : Error getting auth token
03-17 12:55:50.903  1914  3752 E AuthZen : com.google.android.gms.auth.ad: BadAuthentication
03-17 12:55:50.903  1914  3752 E AuthZen : 	at com.google.android.gms.auth.p.b(SourceFile:442)
03-17 12:55:50.903  1914  3752 E AuthZen : 	at com.google.android.gms.auth.p.a(SourceFile:365)
03-17 12:55:50.903  1914  3752 E AuthZen : 	at com.google.android.gms.auth.p.a(SourceFile:318)
03-17 12:55:50.903  1914  3752 E AuthZen : 	at com.google.android.gms.auth.authzen.b.a.a(SourceFile:381)
03-17 12:55:50.903  1914  3752 E AuthZen : 	at com.google.android.gms.auth.authzen.b.a.a(SourceFile:132)
03-17 12:55:50.903  1914  3752 E AuthZen : 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:200)
03-17 12:55:50.903  1914  3752 E AuthZen : 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:153)
03-17 12:55:50.903  1914  3752 E AuthZen : 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:103)
03-17 12:55:50.903  1914  3752 E AuthZen : 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:256)
03-17 12:55:50.903  1914  3752 E AuthZen : 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:207)
03-17 12:55:50.903  1914  3752 E AuthZen : 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:200)
03-17 12:55:50.903  1914  3752 E AuthZen : 	at com.google.android.gms.auth.authzen.a.a(SourceFile:122)
03-17 12:55:50.903  1914  3752 E AuthZen : 	at com.google.android.gms.auth.authzen.GcmReceiverService.onHandleIntent(SourceFile:30)
03-17 12:55:50.903  1914  3752 E AuthZen : 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-17 12:55:50.903  1914  3752 E AuthZen : 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 12:55:50.903  1914  3752 E AuthZen : 	at android.os.Looper.loop(Looper.java:145)
03-17 12:55:50.903  1914  3752 E AuthZen : 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-17 12:55:50.913  1914  3752 E AuthZen : Failed to do enrollment for account: thalitester@gmail.com
03-17 12:55:50.913  1914  3752 E AuthZen : com.google.android.gms.auth.authzen.b.b: Failed to get a token for authzen enrollment
03-17 12:55:50.913  1914  3752 E AuthZen : 	at com.google.android.gms.auth.authzen.b.a.a(SourceFile:139)
03-17 12:55:50.913  1914  3752 E AuthZen : 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:200)
03-17 12:55:50.913  1914  3752 E AuthZen : 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:153)
03-17 12:55:50.913  1914  3752 E AuthZen : 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:103)
03-17 12:55:50.913  1914  3752 E AuthZen : 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:256)
03-17 12:55:50.913  1914  3752 E AuthZen : 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:207)
03-17 12:55:50.913  1914  3752 E AuthZen : 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:200)
03-17 12:55:50.913  1914  3752 E AuthZen : 	at com.google.android.gms.auth.authzen.a.a(SourceFile:122)
03-17 12:55:50.913  1914  3752 E AuthZen : 	at com.google.android.gms.auth.authzen.GcmReceiverService.onHandleIntent(SourceFile:30)
03-17 12:55:50.913  1914  3752 E AuthZen : 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-17 12:55:50.913  1914  3752 E AuthZen : 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 12:55:50.913  1914  3752 E AuthZen : 	at android.os.Looper.loop(Looper.java:145)
03-17 12:55:50.913  1914  3752 E AuthZen : 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-17 12:55:50.943  1022  3060 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:50.943  1022  3060 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:50.943  1022  3060 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:50.943  1022  3060 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:55:50.953  1022  3060 I ActivityManager: Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.GooglePartnerSetup: pid=3850 uid=10015 gids={50015, 9997, 3003} abi=armeabi-v7a
,03-17 12:55:50.953  3850  3850 E Zygote  : MountEmulatedStorage()
,03-17 12:55:50.953  3850  3850 E Zygote  : v2
03-17 12:55:50.963  3850  3850 I libpersona: KNOX_SDCARD checking this for 10015
03-17 12:55:50.963  3850  3850 I libpersona: KNOX_SDCARD not a persona
,03-17 12:55:50.963  3850  3850 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 12:55:50.963  3850  3850 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,03-17 12:55:50.963  3850  3850 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
,03-17 12:55:50.983  1914  3752 D a       : Opening database auth.proximity.permit_store...
,03-17 12:55:51.003  3781  3859 V OneTimeService: OneTimeService.onHandleIntent
,03-17 12:55:51.003  2710  2798 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,03-17 12:55:51.013  1914  3752 D AuthZenTransactionCache: Initialized cache in: /data/data/com.google.android.gms/files
,03-17 12:55:51.013  1914  3752 D AuthZenTransactionCache: Clearing transaction cache
,03-17 12:55:51.023  3371  3740 W jxcore-log: Initializing JXcore engine
03-17 12:55:51.023  3371  3740 W jxcore-log: JXcore engine is ready
,03-17 12:55:51.023  1022  1365 W art     : Suspending all threads took: 19.643ms
,03-17 12:55:51.063  1022  1365 I art     : Explicit concurrent mark sweep GC freed 32766(1834KB) AllocSpace objects, 6(96KB) LOS objects, 33% free, 27MB/40MB, paused 33.619ms total 344.345ms
,03-17 12:55:51.073  3850  3850 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:55:51.073  3850  3850 D ActivityThread: Added TimaKeyStore provider
,03-17 12:55:51.123  1891  1891 E audit   : type=1400 msg=audit(1458215751.113:205): avc:  denied  { ioctl } for  pid=3740 comm="Thread-455" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2061 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0,
03-17 12:55:51.123  1891  1891 E audit   :  SEPF_SM-A500FU_5.0.2_0027
03-17 12:55:51.123  1891  1891 E audit   : type=1300 msg=audit(1458215751.113:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=4 a3=9bd1f8f8 items=0 ppid=310 ppcomm=main pid=3740 auid=4294967295 uid=10174 gid=10174 euid=10174 suid=10174 fsuid=10174 egid=10174 sgid=10174 fsgid=10174 ses=4294967295 tty=(none) comm="Thread-455" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
,03-17 12:55:51.123  1891  1891 E audit   : type=1320 msg=audit(1458215751.113:205): 
03-17 12:55:51.133  3371  3740 W jxcore-log: Starting JXcore engine
,03-17 12:55:51.153  1914  3745 I CheckinService: Checking schedule, now: 1458215751162 next: 1458225725438
03-17 12:55:51.153  1914  3745 I CheckinService: active receiver: disabled
,03-17 12:55:51.163  3830  3830 W ResourcesManager: Asset path '/system/framework/com.samsung.bbccommon.jar' does not exist or contains no resources.
,03-17 12:55:51.193  1914  1914 D SystemUpdateService: onDestroy
,03-17 12:55:51.193  2674  2674 D FactoryTestApp: [DummyFtClient$onDestroy](2674) Destroy DummyFtClient service
,03-17 12:55:51.203  1022  3059 I ActivityManager: Killing 3086:com.samsung.android.app.colorblind/1000 (adj 15): empty #31
,03-17 12:55:51.203  1022  1046 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.api.credentials.sync.CredentialSyncService; callingUser = 0; userId(target) = 0
,03-17 12:55:51.253  2674  2674 D FactoryTestApp: [Support$Values.getString](2674) id=MODEL_COMMUNICATION_MODE, value=gsm
03-17 12:55:51.253  2674  2674 I FactoryTestApp: [ModuleCommon$isConnectionModeNone](2674) mConnectionMode = gsm
03-17 12:55:51.253  2674  2674 I FactoryTestApp: [ModuleCommon$isRunningFtClient](2674) RUNNING_FTCLIENT : false
03-17 12:55:51.253  2674  2674 D FactoryTestApp: [DummyFtClient$onDestroy](2674) kill process
03-17 12:55:51.253  2674  2674 I Process : Sending signal. PID: 2674 SIG: 9
,03-17 12:55:51.253  1311  1324 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,03-17 12:55:51.253  1022  3133 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
,03-17 12:55:51.253  1022  3133 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:55:51.253  1022  3133 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 12:55:51.253  1022  3133 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,03-17 12:55:51.293  3371  3740 W jxcore-log: Platform android
03-17 12:55:51.293  3371  3740 W jxcore-log: 
03-17 12:55:51.293  3371  3740 W jxcore-log: Process ARCH arm
03-17 12:55:51.293  3371  3740 W jxcore-log: 
,03-17 12:55:51.303  1022  3133 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:51.303  1022  3133 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:51.303  1022  3133 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:51.303  1022  3133 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:55:51.313  1022  1046 W libprocessgroup: failed to open /acct/uid_1000/pid_3086/cgroup.procs: No such file or directory
,03-17 12:55:51.323  3873  3873 E Zygote  : MountEmulatedStorage()
,03-17 12:55:51.323  3873  3873 E Zygote  : v2,
03-17 12:55:51.323  3873  3873 I libpersona: KNOX_SDCARD checking this for 10042
,03-17 12:55:51.323  3873  3873 I libpersona: KNOX_SDCARD not a persona
03-17 12:55:51.323  1022  3133 I ActivityManager: Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=3873 uid=10042 gids={50042, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-17 12:55:51.333  1022  3059 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
,03-17 12:55:51.333  3873  3873 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 12:55:51.333  1022  3059 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:55:51.333  1022  3059 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 12:55:51.333  1022  3059 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
03-17 12:55:51.333  3873  3873 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-17 12:55:51.333  3873  3873 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,03-17 12:55:51.333  1022  1482 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:55:51.333  1022  1482 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:51.333  1022  1482 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:51.333  1022  1482 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:55:51.343  3715  3715 I dex2oat : dex2oat took 1.889s (threads: 4)
,03-17 12:55:51.363  3887  3887 E Zygote  : MountEmulatedStorage()
03-17 12:55:51.363  3887  3887 E Zygote  : v2
,03-17 12:55:51.363  3887  3887 I libpersona: KNOX_SDCARD checking this for 10139
03-17 12:55:51.363  3887  3887 I libpersona: KNOX_SDCARD not a persona
,03-17 12:55:51.363  3887  3887 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 12:55:51.363  3887  3887 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,03-17 12:55:51.363  3887  3887 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 12:55:51.363  1022  1482 I ActivityManager: Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.BootCamera: pid=3887 uid=10139 gids={50139, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a
,03-17 12:55:51.373  1022  3083 I ActivityManager: Process com.sec.factory (pid 2674)(adj 0) has died(38,1125)
,03-17 12:55:51.373  3873  3873 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:55:51.373  3873  3873 D ActivityThread: Added TimaKeyStore provider
,03-17 12:55:51.393  1914  3607 D DexOptUtils: Odex created at:/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d5b20f1a6029cea405dc44dd827a138ee4ccf8cc/arm/MapsModule.dex
03-17 12:55:51.393  3887  3887 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 12:55:51.393  1914  3607 D DexOptUtils: Set odex to world readable.
,03-17 12:55:51.393  1914  3607 D DexOptUtils: Renamed odex to /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d5b20f1a6029cea405dc44dd827a138ee4ccf8cc/arm/MapsModule.odex
,03-17 12:55:51.393  3887  3887 D ActivityThread: Added TimaKeyStore provider
03-17 12:55:51.393  1914  3607 D FileApkUtils: Keeping up-to-date module: module-d5b20f1a6029cea405dc44dd827a138ee4ccf8cc
,03-17 12:55:51.403  3873  3873 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,03-17 12:55:51.403  1914  3607 D GmsModuleFndr: Beginning GMS chimera module scan
,03-17 12:55:51.433  3887  3887 W ResourcesManager: Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
03-17 12:55:51.433  3887  3887 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,03-17 12:55:51.433  3887  3887 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
03-17 12:55:51.433  3887  3887 W ResourcesManager: Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
03-17 12:55:51.433  3887  3887 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,03-17 12:55:51.453  1914  3607 D GmsModuleFndr: Module pkg com.google.android.apps.kids.familylink not installed, skipping
03-17 12:55:51.453  1914  3607 D ChimeraCfgMgr: Beginning module configuration check
,03-17 12:55:51.453  1914  3607 D ChimeraCfgMgr: Module APKs unchanged, check complete
,03-17 12:55:51.493  1022  1234 D ActivityManager: retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.ClientIdService; callingUser = 0; userId(target) = 0
,03-17 12:55:51.493  1022  1234 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:55:51.493  1022  1234 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:55:51.493  1022  1234 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,03-17 12:55:51.503  3873  3873 I CalendarProvider2: CalendarProvider2.onCreate() called
,03-17 12:55:51.503  1022  1515 D ActivityManager: retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.AppHiderService; callingUser = 0; userId(target) = 0
,03-17 12:55:51.503  1022  1515 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:55:51.503  1022  1515 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 12:55:51.503  1022  1515 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,03-17 12:55:51.513  1022  3059 D ActivityManager: retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.MccFallbackService; callingUser = 0; userId(target) = 0
,03-17 12:55:51.513  1022  3059 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:55:51.513  1022  3059 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:55:51.513  1022  3059 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,03-17 12:55:51.513  1022  3083 I ActivityManager: Killing 2119:com.google.android.gms.wearable/u0a12 (adj 15): empty #31
,03-17 12:55:51.523  1022  3060 D ActivityManager: retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.MccOverrideService; callingUser = 0; userId(target) = 0
,03-17 12:55:51.523  1022  3060 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:55:51.523  1022  3060 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:55:51.523  1763  3821 I GCoreUlr: WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED
,03-17 12:55:51.523  1022  3060 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,03-17 12:55:51.533  1022  1034 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:55:51.533  1022  1034 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:51.533  1022  1034 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:55:51.533  1022  1034 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:55:51.553  3908  3908 E Zygote  : MountEmulatedStorage(),
03-17 12:55:51.553  3908  3908 E Zygote  : v2
03-17 12:55:51.553  3908  3908 I libpersona: KNOX_SDCARD checking this for 10145
03-17 12:55:51.553  3908  3908 I libpersona: KNOX_SDCARD not a persona
,03-17 12:55:51.553  3908  3908 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 12:55:51.553  1022  1034 I ActivityManager: Start proc com.android.email for broadcast com.android.email/.service.EmailBroadcastReceiver: pid=3908 uid=10145 gids={50145, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a,
03-17 12:55:51.553  3908  3908 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 12:55:51.553  3908  3908 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 12:55:51.563  3371  3740 I jxcore-log: JXcore Cordova bridge is ready!,
,03-17 12:55:51.563  3371  3740 I jxcore-log: 
03-17 12:55:51.563  3371  3740 W jxcore-log: JXcore engine is started
,03-17 12:55:51.583  3371  3606 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,03-17 12:55:51.583  3908  3908 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 12:55:51.583  3908  3908 D ActivityThread: Added TimaKeyStore provider
03-17 12:55:51.583   310   310 I art     : Explicit concurrent mark sweep GC freed 8721(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 633us total 35.824ms
03-17 12:55:51.583  1022  1046 W libprocessgroup: failed to open /acct/uid_10012/pid_2119/cgroup.procs: No such file or directory
,03-17 12:55:51.603  3371  3740 E jxcore  : Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
03-17 12:55:51.603  3371  3740 E jxcore  : Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,03-17 12:55:51.613   310   310 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 713us total 19.380ms
,03-17 12:55:51.613  3371  3371 I chromium: [INFO:CONSOLE(54)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (54)
,03-17 12:55:51.633  1022  1234 D FocusedStackFrame: Set to : 0
,03-17 12:55:51.633  1022  1234 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-17 12:55:51.633  1022  1234 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
03-17 12:55:51.633  1022  1234 D InputDispatcher: Focused application set to: xxxx
,03-17 12:55:51.633  1022  1234 D InputDispatcher: Focus left window: 3371
,03-17 12:55:51.633   310   310 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 643us total 18.970ms
,03-17 12:55:51.643  3239  3335 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,03-17 12:55:51.663  1022  1052 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-17 12:55:51.663  1022  1052 D PointerIcon: setMouseCustomIcon IconType is same.101
,03-17 12:55:51.663   258   439 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (3153 us)
,03-17 12:55:51.673  1022  1361 D TimaService: TIMA: in getTimaVersion
,03-17 12:55:51.673  1022  3059 D TimaService: TIMA3: KeyStore3_init
03-17 12:55:51.673  1022  3059 E TLC_TZ_KEYSTORE: : Inside TZ_KEYSTORE_initialize()
03-17 12:55:51.673  1022  3059 D TimaService: TIMA: in getTimaVersion
03-17 12:55:51.673  1022  3059 I TLC_TZ_KEYSTORE: : creating new keystore context...
03-17 12:55:51.673  1022  3059 I TLC_TZ_KEYSTORE: : initializing ccm context...
03-17 12:55:51.673  1022  3059 I TLC_TZ_KEYSTORE: : root = /firmware/image, root_strlen = 15
03-17 12:55:51.673  1022  3059 I TLC_TZ_KEYSTORE: : process = tima_key, process_strlen = 8
03-17 12:55:51.673  1022  3059 I TZ: qc_tlc_communication: root = /firmware/image, root_len = 15
03-17 12:55:51.673  1022  3059 I TZ: qc_tlc_communication: process = tima_key, process_strlen = 8
03-17 12:55:51.673  1022  3059 I TZ: qc_tlc_communication: aligned max_sendmsg_size = 1088 = 0x440
03-17 12:55:51.673  1022  3059 I TZ: qc_tlc_communication: aligned max_recvmsg_size = 1088 = 0x440
03-17 12:55:51.673  1022  3059 I TZ: qc_tlc_communication: max_message_size = 2176 = 0x880
03-17 12:55:51.673  1022  3059 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x880
03-17 12:55:51.673  1022  3059 D QSEECOMAPI: : App is not loaded in QSEE
,03-17 12:55:51.673  3239  3335 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,03-17 12:55:51.683  3908  3908 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,03-17 12:55:51.683  3908  3908 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,03-17 12:55:51.683  3908  3908 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,03-17 12:55:51.693  3164  3206 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 3 sec
,03-17 12:55:51.693  3239  3335 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,03-17 12:55:51.693  3908  3908 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.,
03-17 12:55:51.693  3908  3908 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
03-17 12:55:51.703  3239  3335 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
03-17 12:55:51.703  3371  3606 W PluginManager: THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 84ms. Plugin should use CordovaInterface.getThreadPool().,
03-17 12:55:51.703  1022  1365 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1022  pkgName : ACTIVITY_RESUME_BOOSTER@7
03-17 12:55:51.703  3239  3335 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
03-17 12:55:51.703  1022  1365 W ActivityManager: mDVFSHelper.acquire()
03-17 12:55:51.703  1022  1365 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1,
03-17 12:55:51.703  1022  1365 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
03-17 12:55:51.703  1022  1365 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
03-17 12:55:51.703  3239  3335 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,03-17 12:55:51.743  1519  1519 D Launcher: onRestart, Launcher: 359067967
,03-17 12:55:51.753  1022  3059 D QSEECOMAPI: : Loaded image: APP id = 9
,03-17 12:55:51.753  1022  3059 I TZ: qc_tlc_communication: TIMA: path = /firmware/image, fname = tima_key, tzapp is loaded
03-17 12:55:51.753  1022  3059 I TLC_TZ_KEYSTORE: : ctx = 0xb8aca5b0, comm = 0xb8b01c28, sendmsg = 0xa080d000, recvmsg = 0xa080d440
03-17 12:55:51.753  1022  3059 I TZ_init: : TZ_init: sending initialization request...
,03-17 12:55:51.753  1022  1361 D ActivityManager: retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.RlzPingIntentService; callingUser = 0; userId(target) = 0
,03-17 12:55:51.753  1022  1361 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:55:51.753  1022  1361 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 12:55:51.753  1022  1361 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,03-17 12:55:51.763  1022  3059 E TZ_init: : TZ_init Process: Secure memory is not initialized!
,03-17 12:55:51.763  1022  3059 E TZ_init: : trustlet initialization failed
,03-17 12:55:51.763  1022  3059 I TZ_init: : TZ_init_START...
,03-17 12:55:51.763  3239  3335 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,03-17 12:55:51.773  1519  1519 D Launcher: onStart, Launcher: 359067967
03-17 12:55:51.773  1519  1519 D Launcher.HomeView: onStart
,03-17 12:55:51.773  1519  1519 D Launcher: onResume, Launcher: 359067967
03-17 12:55:51.773  1022  1034 D SettingsProvider: name = kids_home_mode
,03-17 12:55:51.773  1022  1034 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,03-17 12:55:51.773  1022  1034 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-17 12:55:51.773  1022  1034 D SettingsProvider: selectionArgs: false
03-17 12:55:51.773  1022  1034 D SettingsProvider: selectionArgs: 10007
03-17 12:55:51.773  1022  1034 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-17 12:55:51.773  1022  1034 D SettingsProvider: ret = -1
03-17 12:55:51.773  1519  1519 D Launcher.HomeView: onResume
,03-17 12:55:51.773  1022  3059 I TZ_init: : TZ_init_with_data: sending initialization request...
03-17 12:55:51.773  3239  3335 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,03-17 12:55:51.773  1022  3059 I TZ_init: : TZ_init: successful initialization
,03-17 12:55:51.773  1022  3059 D QSEECOMAPI: : QSEECom_dealloc_memory 
03-17 12:55:51.773  1022  3059 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 9
03-17 12:55:51.773  1022  3059 E TLC_TZ_KEYSTORE: : Count : 1, Ret : 0
,03-17 12:55:51.783  1022  1022 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
03-17 12:55:51.783  1022  1022 D SensorService: [SO] activate (ident=0xb8b2eef8, enabled=0)
03-17 12:55:51.783  1022  1022 I Sensors : AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,03-17 12:55:51.783  1022  1022 D SensorManager: unregisterListener ::   
,03-17 12:55:51.783  1022  1022 I Sensors : AccelerometerSensor(0) setDelay : 200000000(ns)
,03-17 12:55:51.783  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.SBrowserMainActivity
,03-17 12:55:51.793  1022  1022 D SensorService: [SO] changed settle time [0]
03-17 12:55:51.793  1022  1022 D SensorService: [SO] setDelay [200000000]
03-17 12:55:51.793  1022  1022 D SensorService: [SO] activate (ident=0xb8b2eef8, enabled=1)
,03-17 12:55:51.793  1022  1022 D SensorService: [SO] AR_init
03-17 12:55:51.793  1022  1022 I Sensors : AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,03-17 12:55:51.793  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:51.793  3758  3837 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
03-17 12:55:51.793  3758  3837 I AMMetaDataParserService: getResourcePackageName:assistantlist
03-17 12:55:51.793  3758  3837 I AMMetaDataParserService: Resource data:2131165186
,03-17 12:55:51.793  3758  3837 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
03-17 12:55:51.793  3758  3837 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 12:55:51.793  3758  3837 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,03-17 12:55:51.793  3758  3837 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,03-17 12:55:51.803  1022  1022 D SensorManager: registerListener :: 1600221811, Screen Orientation Sensor, 200000, 0,  
03-17 12:55:51.803  3758  3837 I AMMetaDataParserService: getResourceName:com.sec.android.app.sbrowser:xml/assistantlist
03-17 12:55:51.803  3758  3837 I AMMetaDataParserService: getResourceTypeNamexml
,03-17 12:55:51.803  1519  1519 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,03-17 12:55:51.803  1519  1519 D MenuAppsGridFragment: onResume
,03-17 12:55:51.813  1022  3060 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,03-17 12:55:51.813  3758  3837 I AMMetaDataParserService: Icon data: ResourceEnter URL2131755287android.intent.action.doInputURL2130837509
,03-17 12:55:51.823  1022  3060 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:55:51.823  1022  3060 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-17 12:55:51.823  1022  3060 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,03-17 12:55:51.823  2468  2468 I Hs20UtilService: Starting #3
,03-17 12:55:51.823  2468  2487 I Hs20UtilService: Message received 5003
,03-17 12:55:51.833  1022  1534 D ActivityManager: handle home activity for 0
,03-17 12:55:51.833  1022  1534 I WallpaperManagerService: switchPersonaWallpaper is called for personaId-0
,03-17 12:55:51.833  1022  1534 D KnoxTimeoutHandler: post home show event for user 0
03-17 12:55:51.833  1022  1022 D WallpaperManagerService:  force update = false; persona id = 0; current user =0; current persona = 0
,03-17 12:55:51.833  1022  1534 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
03-17 12:55:51.833  1022  1022 D KnoxTimeoutHandler: handleHomeShow for 0 and current 0
,03-17 12:55:51.833  1022  1534 D KnoxTimeoutHandler: postActiveUserChange for user 0
,03-17 12:55:51.833  1022  1534 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,03-17 12:55:51.833  1022  1022 D KnoxTimeoutHandler: handleActiveUserChange for user 0
03-17 12:55:51.833  1022  1022 D PersonaManagerService: getPersonasForUser(): returning null!
,03-17 12:55:51.843  1022  1482 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:51.843  1022  1482 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:51.843  1022  1482 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:51.843  1022  1482 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:55:51.843   258   258 I SurfaceFlinger: id=12 createSurf (720x1280),1 flag=4, Mauncher
,03-17 12:55:51.853  3239  3253 I art     : WaitForGcToComplete blocked for 65.868ms for cause HomogeneousSpaceCompact
,03-17 12:55:51.853  3936  3936 E Zygote  : MountEmulatedStorage()
03-17 12:55:51.853  3936  3936 E Zygote  : v2
,03-17 12:55:51.853  3936  3936 I libpersona: KNOX_SDCARD checking this for 10019
03-17 12:55:51.853  3936  3936 I libpersona: KNOX_SDCARD not a persona
,03-17 12:55:51.853  3936  3936 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 12:55:51.863  1022  1365 D RCPManagerService: exchangeData() failure , invalid userId
03-17 12:55:51.863  1022  1050 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,03-17 12:55:51.863  3936  3936 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 12:55:51.863  3936  3936 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 12:55:51.873  1022  3059 D InputDispatcher: Focus entered window: 1519
,03-17 12:55:51.873  1022  1050 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,03-17 12:55:51.873  1519  1519 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,03-17 12:55:51.873  1022  1482 I ActivityManager: Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=3936 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,03-17 12:55:51.883  1022  1052 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-17 12:55:51.883  1022  1052 D PointerIcon: setMouseCustomIcon IconType is same.101
03-17 12:55:51.883  1022  1534 D RCPManagerService: exchangeData() failure , invalid userId
,03-17 12:55:51.883  3758  3837 I AMMetaDataParserService: Icon data: ResourceTabs2131755155android.intent.action.doWindowManager2130837511
,03-17 12:55:51.883  1022  1034 D RCPManagerService: exchangeData() failure , invalid userId
,03-17 12:55:51.893  1519  1519 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0,
,03-17 12:55:51.903  1022  1035 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,03-17 12:55:51.903  1022  3956 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-17 12:55:51.913  1022  3083 D RCPManagerService: exchangeData() failure , invalid userId
,03-17 12:55:51.933  3371  3371 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,03-17 12:55:51.933  3936  3936 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:55:51.933  3936  3936 D ActivityThread: Added TimaKeyStore provider
03-17 12:55:51.933  1022  1515 D PowerManagerService: [api] release WakeLock flags=0x10000006 tag=PowerUI.Notification uid=10054 pid=1191 (0x0)
,03-17 12:55:51.933  1191  1191 I StatusBar: Icon Only
03-17 12:55:51.933  1191  1191 D PanelView: There is/are notification(s) 
,03-17 12:55:51.953  1822  1822 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,03-17 12:55:51.953  1022  3083 D ActivityManager: retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.RlzPingService; callingUser = 0; userId(target) = 0
,03-17 12:55:51.953  1022  3083 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:55:51.953  1022  3083 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:55:51.953  1022  3083 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,03-17 12:55:51.973  1519  1519 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@354edd49 time:42292
,03-17 12:55:51.973  1022  1052 D PersonaManager: isKioskContainerExistOnDevice
,03-17 12:55:51.983  1022  1052 I ActivityManager: Displayed Component not be shown by security: +284ms
,03-17 12:55:51.993  1022  1044 D SensorService: [SO] Reset Rotation Old [100], Init [1]
,03-17 12:55:51.993  3758  3837 I AMMetaDataParserService: Icon data: ResourceNew Tab2131755458android.intent.action.doNewWindow2130837510
,03-17 12:55:52.013  3830  3830 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.bbc.bbcagent.bbccontroller.BBCDataConsistency.checkDBConsistencyFromPM:220 com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BootCompletedReceiver.onReceive:50 
,03-17 12:55:52.013  1022  1035 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.service.BBCAgentService; callingUser = 0; userId(target) = 0
,03-17 12:55:52.013  1022  1035 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:55:52.013  1022  1035 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 12:55:52.013  1022  1035 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.bbc.bbcagent, destAppInfo.processName = com.samsung.android.bbc.bbcagent
,03-17 12:55:52.023  1763  1904 I art     : Explicit concurrent mark sweep GC freed 13583(850KB) AllocSpace objects, 5(80KB) LOS objects, 40% free, 10MB/18MB, paused 2.274ms total 101.592ms
,03-17 12:55:52.023  1022  1482 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 12:55:52.023  1022  1482 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:55:52.023  1022  1482 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:55:52.023  1022  1482 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 12:55:52.053  1022  1035 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:55:52.053  1022  1035 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:52.053  1022  1035 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:52.053  1022  1035 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:55:52.063  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappManager
03-17 12:55:52.063  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity
03-17 12:55:52.063  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity0
03-17 12:55:52.063  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity1
03-17 12:55:52.063  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity2
03-17 12:55:52.063  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity3
03-17 12:55:52.063  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity4
03-17 12:55:52.063  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity5
03-17 12:55:52.063  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity6
03-17 12:55:52.063  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity7
03-17 12:55:52.063  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity8
03-17 12:55:52.063  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity9
03-17 12:55:52.063  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.history.ui.HistoryActivity
03-17 12:55:52.063  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.Settings
03-17 12:55:52.063  3758  3837 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
03-17 12:55:52.063  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.reader.ui.ReaderActivity
03-17 12:55:52.063  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.menuactivity.ui.AddWebPageMenuActivity
03-17 12:55:52.063  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.readinglist.activity.ReadingListActivity
03-17 12:55:52.063  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.readinglist.controller.ReadingListSearchActivity
03-17 12:55:52.063  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.sites.SitesActivity
03-17 12:55:52.063  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.common.DataChargingDialog
03-17 12:55:52.063  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.EditBookmarkFolderActivity
03-17 12:55:52.063  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.AddBookmarkActivity
03-17 12:55:52.063  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.ShowBookmarksActivity
03-17 12:55:52.063  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.,SelectBookmarkFolderActivity
03-17 12:55:52.063  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.CreateBookmarkFolderActivity
03-17 12:55:52.063  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.SynctabActivity
03-17 12:55:52.063  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.SelectSyncAccountActivity
03-17 12:55:52.063  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.AutofillFormEdit
03-17 12:55:52.063  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.DeleteSyncTabActivity
03-17 12:55:52.063  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountGetStartedActivity
03-17 12:55:52.063  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountCreateAccountActivity
03-17 12:55:52.063  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountConfirmAccountActivity
03-17 12:55:52.063  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountSignInActivity
03-17 12:55:52.063  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountVerifiedAccountActivity
03-17 12:55:52.063  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountCreateAccountNotAllowedActivity
03-17 12:55:52.073  3966  3966 E Zygote  : MountEmulatedStorage()
03-17 12:55:52.073  3966  3966 E Zygote  : v2
03-17 12:55:52.073  3966  3966 I libpersona: KNOX_SDCARD checking this for 1000
03-17 12:55:52.073  3966  3966 I libpersona: KNOX_SDCARD not a persona
03-17 12:55:52.073  3966  3966 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-17 12:55:52.073  1022  1035 I ActivityManager: Start proc com.sec.bcservice for broadcast com.sec.bcservice/.BCServiceReceiver: pid=3966 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-17 12:55:52.073  3936  3936 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Thu Mar 17 12:55:52 GMT+01:00 2016
03-17 12:55:52.083  3966  3966 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-17 12:55:52.083  3966  3966 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 12:55:52.093  1022  1515 D RCPManagerService: exchangeData() failure , invalid userId
03-17 12:55:52.093  1022  1034 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
03-17 12:55:52.093  1022  3060 D RCPManagerService: exchangeData() failure , invalid userId
03-17 12:55:52.093  1022  1034 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:55:52.093  1022  1034 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 12:55:52.093  1022  1034 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
03-17 12:55:52.093  1022  1534 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailBroadcastProcessorService; callingUser = 0; userId(target) = 0
,03-17 12:55:52.103  1596  2992 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,03-17 12:55:52.123  1022  1534 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:55:52.123  3936  3936 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive().END.
,03-17 12:55:52.123  1022  1534 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 12:55:52.123  1022  1534 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.email, destAppInfo.processName = com.android.email
,03-17 12:55:52.133  3966  3966 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:55:52.133  3966  3966 D ActivityThread: Added TimaKeyStore provider
,03-17 12:55:52.133  3936  3936 I KLMS-2.5.183: : KLMSIntentService(): onCreate()
,03-17 12:55:52.143  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.PeopleActivity
03-17 12:55:52.143  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:52.143  3758  3837 I AMMetaDataParserService: getResourcePackageName:assistant
03-17 12:55:52.143  3758  3837 I AMMetaDataParserService: Resource data:2131034113
,03-17 12:55:52.163  1022  1482 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:52.163  1022  1482 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:52.163  1022  1482 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:52.163  1022  1482 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:55:52.163  1022  1515 W SEAMService:  hashset_to_int_array returning null
,03-17 12:55:52.163  3936  3936 I KLMS-2.5.183: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,03-17 12:55:52.163  3758  3837 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
03-17 12:55:52.163  3758  3837 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 12:55:52.163  3758  3837 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,03-17 12:55:52.173  3936  3936 I KLMS-2.5.183: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,03-17 12:55:52.173  1022  1234 W SEAMService:  hashset_to_int_array returning null
,03-17 12:55:52.173  3758  3837 I AMMetaDataParserService: getResourceName:com.android.contacts:xml/assistant_main
03-17 12:55:52.173  3830  3830 E SQLiteLog: (284) automatic index on seams_container_info(seams_container_id)
03-17 12:55:52.173  3758  3837 I AMMetaDataParserService: getResourceTypeNamexml
,03-17 12:55:52.173  3830  3830 E SQLiteLog: (284) automatic index on seams_container_info(sp_id)
,03-17 12:55:52.183  3758  3837 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
03-17 12:55:52.183  1022  1482 I ActivityManager: Start proc com.android.managedprovisioning for broadcast com.android.managedprovisioning/.BootReminder: pid=3986 uid=10022 gids={50022, 9997, 1028, 3003} abi=armeabi-v7a
03-17 12:55:52.183  3936  3982 I KLMS-2.5.183: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
03-17 12:55:52.183  3758  3837 I GFX construct_block_size_descriptor_2d second part: took 2.475156ms for 0*0 texture 0
,03-17 12:55:52.183  3986  3986 E Zygote  : MountEmulatedStorage()
03-17 12:55:52.183  3986  3986 I libpersona: KNOX_SDCARD checking this for 10022
03-17 12:55:52.183  3986  3986 E Zygote  : v2
03-17 12:55:52.183  3986  3986 I libpersona: KNOX_SDCARD not a persona
03-17 12:55:52.183  3986  3986 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 12:55:52.193  3936  3982 I KLMS-2.5.183: : KLMSIntentService(): BOOT_COMPLETED
03-17 12:55:52.193  1022  1506 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
03-17 12:55:52.193  1022  1044 D SensorService: [SO] currT = 42511574000, prevT = 42071123000, diff = 440451000, [0.192 0.421 10.266]
03-17 12:55:52.193  1022  1044 D SensorService: [SO] 0.192 0.421 10.266
03-17 12:55:52.193  1022  1044 D SensorService: [SO] [100 -> 255]
03-17 12:55:52.193  3986  3986 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 12:55:52.193  3986  3986 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 12:55:52.203  1022  1506 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:55:52.203  1022  1506 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:55:52.203  1022  1506 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 12:55:52.203  1022  1035 W SEAMService:  hashset_to_int_array returning null
,03-17 12:55:52.213  3966  3966 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,03-17 12:55:52.213  3986  3986 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:55:52.213  3986  3986 D ActivityThread: Added TimaKeyStore provider
,03-17 12:55:52.213  1022  1047 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1022  tag : ACTIVITY_RESUME_BOOSTER@7
,03-17 12:55:52.223  1022  1047 W ActivityManager: mDVFSHelper.release()
,03-17 12:55:52.223  1022  1047 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1022  pkgName : ACTIVITY_RESUME_BOOSTER@11
,03-17 12:55:52.233  1596  1611 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
,03-17 12:55:52.233  3758  3837 I GFX generate_partition_tables: took 6.523230ms for 0*0 texture 0
,03-17 12:55:52.233  3758  3837 I GFX raster: took 10.199792ms for 96*96 texture 0
03-17 12:55:52.233  3758  3837 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8692620 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb86929d8 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 12:55:52.233  1596  1611 D BadgeProvider: sendNotify, [notify] : null
,03-17 12:55:52.233  1596  1611 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
03-17 12:55:52.233  1596  1611 D BadgeProvider: update, [BadgeCount] : badgecount=0
03-17 12:55:52.233  1596  1611 D BadgeProvider: update, [UpdateCount] : 1
,03-17 12:55:52.233  1519  1519 D Launcher.Model: reloadBadges entered.
,03-17 12:55:52.233  1022  1361 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 12:55:52.243  1022  1361 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:55:52.243  1022  1361 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 12:55:52.243  1022  1361 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-17 12:55:52.253  3758  3837 I AMMetaDataParserService: Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
,03-17 12:55:52.283  1022  1482 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:52.283  1022  1482 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:52.283  1022  1482 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:52.283  1022  1482 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:55:52.283  3936  3936 I KLMS-2.5.183: : KLMSIntentService(): onDestroy()
,03-17 12:55:52.293  3966  3966 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.bcservice.BCServiceReceiver.onReceive:18 android.app.ActivityThread.handleReceiver:3125 
,03-17 12:55:52.293  4011  4011 E Zygote  : MountEmulatedStorage()
,03-17 12:55:52.293  4011  4011 I libpersona: KNOX_SDCARD checking this for 10146
03-17 12:55:52.293  4011  4011 E Zygote  : v2
03-17 12:55:52.293  4011  4011 I libpersona: KNOX_SDCARD not a persona
,03-17 12:55:52.293  4011  4011 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 12:55:52.303  1022  1482 I ActivityManager: Start proc com.android.exchange for broadcast com.android.exchange/.service.ExchangeBroadcastReceiver: pid=4011 uid=10146 gids={50146, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,03-17 12:55:52.303  4011  4011 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
03-17 12:55:52.303  4011  4011 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 12:55:52.303  1022  1482 I ActivityManager: Killing 3108:com.sec.android.diagmonagent/1000 (adj 15): empty #31
03-17 12:55:52.303  1022  1365 D ActivityManager: retrieveServiceLocked(): component = com.sec.bcservice/com.sec.bcservice.BroadcastService; callingUser = 0; userId(target) = 0
,03-17 12:55:52.303  3758  3837 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 12:55:52.303  3758  3837 I GFX raster: took 0.899167ms for 96*96 texture 0
03-17 12:55:52.303  3758  3837 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8692620 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb869aa70 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 12:55:52.313  1022  1365 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:55:52.313  1022  1365 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 12:55:52.313  1022  1365 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.bcservice, destAppInfo.processName = com.sec.bcservice
03-17 12:55:52.313  3758  3837 I AMMetaDataParserService: Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,03-17 12:55:52.323  1022  1534 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
,03-17 12:55:52.323  1022  1534 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:55:52.323  1022  1534 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 12:55:52.323  1022  1534 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,03-17 12:55:52.333  3966  3966 I F_PHONE : [[com.sec.bcservice]] bind SecPhone Service with FactoryPhone
,03-17 12:55:52.333  3966  3966 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.samsung.android.sec_platform_library.FactoryPhone.connectToRilService:95 com.samsung.android.sec_platform_library.FactoryPhone.<init>:61 com.sec.bcservice.BroadcastService.onCreate:146 
,03-17 12:55:52.343  4011  4011 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:55:52.343  4011  4011 D ActivityThread: Added TimaKeyStore provider
,03-17 12:55:52.343  1022  1482 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:55:52.343  1022  1482 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:52.343  1022  1482 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:55:52.343  1022  1482 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:55:52.353  4029  4029 E Zygote  : MountEmulatedStorage()
03-17 12:55:52.353  4029  4029 E Zygote  : v2
03-17 12:55:52.353  4029  4029 I libpersona: KNOX_SDCARD checking this for 1000
03-17 12:55:52.353  4029  4029 I libpersona: KNOX_SDCARD not a persona
,03-17 12:55:52.353  4029  4029 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 12:55:52.363  4029  4029 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 12:55:52.363  1022  1482 I ActivityManager: Start proc com.sec.android.app.bluetoothtest for broadcast com.sec.android.app.bluetoothtest/.BluetoothBDAdrressReceiver: pid=4029 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-17 12:55:52.363  4029  4029 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 12:55:52.363  1022  1518 D ActivityManager: retrieveServiceLocked(): component = com.sec.phone/com.sec.phone.SecPhoneService; callingUser = 0; userId(target) = 0
03-17 12:55:52.363  1022  1518 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:55:52.363  1022  1518 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 12:55:52.363  1022  1518 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.bcservice, destAppInfo.processName = com.sec.phone
,03-17 12:55:52.363  3758  3837 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 12:55:52.373  3758  3837 I GFX construct_block_size_descriptor_2d second part: took 2.697603ms for 0*0 texture 0
,03-17 12:55:52.383  3758  3837 I GFX generate_partition_tables: took 7.636302ms for 0*0 texture 0
,03-17 12:55:52.383  3758  3837 I GFX raster: took 11.405102ms for 96*96 texture 0
03-17 12:55:52.383  3758  3837 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8697700 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8697858 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 12:55:52.383  1022  1482 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:52.383  1022  1482 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:55:52.393  1022  1482 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:52.393  1022  1482 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:55:52.393  3797  4039 I Babel_SMS: MmsConfig: mnc/mcc: 0/0,
,03-17 12:55:52.403  3797  4039 I Babel_SMS: MmsConfig.loadMmsSettings
03-17 12:55:52.403  3797  4039 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
03-17 12:55:52.403  3797  4039 I Babel_SMS: MmsConfig.loadFromDatabase
,03-17 12:55:52.403  3758  3837 I AMMetaDataParserService: Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,03-17 12:55:52.423  4029  4029 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:55:52.423  1022  1482 I ActivityManager: Start proc com.samsung.android.MtpApplication for broadcast com.samsung.android.MtpApplication/.MtpReceiver: pid=4051 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-17 12:55:52.423  4029  4029 D ActivityThread: Added TimaKeyStore provider
,03-17 12:55:52.423  4051  4051 E Zygote  : MountEmulatedStorage()
03-17 12:55:52.423  4051  4051 E Zygote  : v2
03-17 12:55:52.423  4051  4051 I libpersona: KNOX_SDCARD checking this for 1000
03-17 12:55:52.423  4051  4051 I libpersona: KNOX_SDCARD not a persona
,03-17 12:55:52.433  4051  4051 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 12:55:52.433  1022  1482 I ActivityManager: Killing 3148:com.sec.providers.settingsearch/u0a150 (adj 15): empty #31
,03-17 12:55:52.433  4051  4051 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 12:55:52.433  4051  4051 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 12:55:52.453  3797  4039 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
03-17 12:55:52.453  3797  4039 I Babel_SMS: MmsConfig.loadFromResources
,03-17 12:55:52.463  4011  4011 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,03-17 12:55:52.463  3797  4039 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
03-17 12:55:52.463  3797  4039 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
,03-17 12:55:52.463  3966  3966 D F_PHONE : [[com.sec.bcservice]] onServiceConnected()
,03-17 12:55:52.463  1022  1052 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{1aef9f2 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t235} time:42785
,03-17 12:55:52.463  3850  3850 I RlzPingService: Setting next ping for 1458820552454
03-17 12:55:52.463  1022  1047 I ActivityManager: Killing 3119:com.google.android.configupdater/u0a86 (adj 15): empty #31
,03-17 12:55:52.473  3966  3966 I F_PHONE : default registerAction()
03-17 12:55:52.473  3966  3966 I F_PHONE : [[com.sec.bcservice]] sendPendingMessage()
,03-17 12:55:52.483   258  3394 I SurfaceFlinger: id=11 Removed NainActivit (7/8)
,03-17 12:55:52.483   258  1108 I SurfaceFlinger: id=11 Removed NainActivit (-2/8)
,03-17 12:55:52.503  4029  4029 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,03-17 12:55:52.503  4051  4051 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:55:52.503  4051  4051 D ActivityThread: Added TimaKeyStore provider
,03-17 12:55:52.523  3758  3837 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 12:55:52.523  3758  3837 I GFX raster: took 0.703802ms for 96*96 texture 0
03-17 12:55:52.523  3758  3837 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb869b670 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb869b7c8 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 12:55:52.523  1022  1022 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1022  tag : ACTIVITY_RESUME_BOOSTER@11
,03-17 12:55:52.543  1191  1191 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-17 12:55:52.543  1191  1191 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-17 12:55:52.543  1191  1191 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 12:55:52.543  4029  4029 D BluetoothBDAdrressReceiver: onReceive(), action: android.intent.action.BOOT_COMPLETED
,03-17 12:55:52.543  4029  4029 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.app.bluetoothtest.BluetoothBDAdrressReceiver.onReceive:32 android.app.ActivityThread.handleReceiver:3125 
,03-17 12:55:52.553  1191  1191 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 12:55:52.553  1191  1191 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 12:55:52.553  1191  1191 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 12:55:52.563  3758  3837 I AMMetaDataParserService: Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,03-17 12:55:52.603  1022  1046 W libprocessgroup: failed to open /acct/uid_1000/pid_3108/cgroup.procs: No such file or directory
03-17 12:55:52.603  1022  1046 W libprocessgroup: failed to open /acct/uid_10150/pid_3148/cgroup.procs: No such file or directory
03-17 12:55:52.603  1022  3133 I ActivityManager: Killing 3214:com.sec.esdk.elm/u0a94 (adj 15): empty #31
,03-17 12:55:52.603  3758  3837 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 12:55:52.603  3758  3837 I GFX raster: took 0.814062ms for 96*96 texture 0
,03-17 12:55:52.603  3758  3837 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb86992a0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb86993f8 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 12:55:52.613  1022  1361 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.app.bluetoothtest/com.sec.android.app.bluetoothtest.BluetoothBDTestService; callingUser = 0; userId(target) = 0
,03-17 12:55:52.613  1022  1361 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:55:52.613  1022  1361 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 12:55:52.613  1022  1361 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.bluetoothtest, destAppInfo.processName = com.sec.android.app.bluetoothtest
,03-17 12:55:52.633  4051  4051 E MTPRx   : In MtpReceiverandroid.intent.action.BOOT_COMPLETED
,03-17 12:55:52.633  1494  1494 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,03-17 12:55:52.643  3371  3371 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3371
03-17 12:55:52.643  1494  1494 D BluetoothBDTestService: onCreate()
,03-17 12:55:52.643  1494  1494 E BluetoothBDTestService: onStart(), extra_type: BOOT_COMPLETED
03-17 12:55:52.643  1494  1494 E BluetoothBDTestService: bd_address_path: /efs/bluetooth/bt_addr
,03-17 12:55:52.643  1494  1494 E BluetoothBDTestService: already exist!( /efs/bluetooth/bt_addr ), file length: 17
,03-17 12:55:52.643  1022  3133 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:52.643  1022  3133 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:52.643  1022  3133 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:52.643  1022  3133 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:55:52.653  3371  3371 E ActivityThread: Activity com.test.thalitest.MainActivity has leaked IntentReceiver org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager$BluetoothModeBroadcastReceiver@1c035722 that was originally registered here. Are you missing a call to unregisterReceiver()?
03-17 12:55:52.653  3371  3371 E ActivityThread: android.app.IntentReceiverLeaked: Activity com.test.thalitest.MainActivity has leaked IntentReceiver org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager$BluetoothModeBroadcastReceiver@1c035722 that was originally registered here. Are you missing a call to unregisterReceiver()?
03-17 12:55:52.653  3371  3371 E ActivityThread: 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:970)
03-17 12:55:52.653  3371  3371 E ActivityThread: 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:771)
03-17 12:55:52.653  3371  3371 E ActivityThread: 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:2014)
03-17 12:55:52.653  3371  3371 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1994)
03-17 12:55:52.653  3371  3371 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1988)
03-17 12:55:52.653  3371  3371 E ActivityThread: 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.initialize(BluetoothManager.java:275)
03-17 12:55:52.653  3371  3371 E ActivityThread: 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.bind(BluetoothManager.java:103)
03-17 12:55:52.653  3371  3371 E ActivityThread: 	at io.jxcore.node.ConnectivityMonitor.start(ConnectivityMonitor.java:75)
03-17 12:55:52.653  3371  3371 E ActivityThread: 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:90)
03-17 12:55:52.653  3371  3371 E ActivityThread: 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
03-17 12:55:52.653  3371  3371 E ActivityThread: 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
03-17 12:55:52.653  3371  3371 E ActivityThread: 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
03-17 12:55:52.653  3371  3371 E ActivityThread: 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
03-17 12:55:52.653  3371  3371 E ActivityThread: 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
03-17 12:55:52.653  3371  3371 E ActivityThread: 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
03-17 12:55:52.653  3371  3371 E ActivityThread: 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
03-17 12:55:52.653  3371  3371 E ActivityThread: 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
03-17 12:55:52.653  3371  3371 E ActivityThread: 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
03-17 12:55:52.653  3371  3371 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 12:55:52.653  3371  3371 E ActivityThread: 	at android.os.Looper.loop(Looper.java:145)
03-17 12:55:52.653  3371  3371 E ActivityThread: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-17 12:55:52.653  3758  3837 I AMMetaDataParserService: Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,03-17 12:55:52.663  1022  1534 D RCPManagerService: exchangeData() failure , invalid userId
,03-17 12:55:52.663  4069  4069 E Zygote  : MountEmulatedStorage()
03-17 12:55:52.663  4069  4069 E Zygote  : v2
03-17 12:55:52.663  4069  4069 I libpersona: KNOX_SDCARD checking this for 1000
03-17 12:55:52.663  4069  4069 I libpersona: KNOX_SDCARD not a persona
,03-17 12:55:52.673  4069  4069 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 12:55:52.673  4069  4069 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,03-17 12:55:52.673  4069  4069 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,03-17 12:55:52.673  1022  3133 I ActivityManager: Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.receiver.ServiceStartReceiver: pid=4069 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-17 12:55:52.683  1022  3133 I ActivityManager: Killing 3239:com.policydm/1000 (adj 15): empty #31
,03-17 12:55:52.683  1022  3083 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
03-17 12:55:52.683  1022  3083 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,03-17 12:55:52.683  1022  1365 D ActivityManager: retrieveServiceLocked(): component = com.android.exchange/com.android.exchange.service.ExchangeBroadcastProcessorService; callingUser = 0; userId(target) = 0
,03-17 12:55:52.683  1022  1365 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:55:52.683  1022  1365 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 12:55:52.683  1022  1365 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.exchange, destAppInfo.processName = com.android.exchange
,03-17 12:55:52.683  3371  3371 E ActivityThread: Activity com.test.thalitest.MainActivity has leaked IntentReceiver io.jxcore.node.ConnectivityMonitor$WifiStateChangedAndConnectivityActionBroadcastReceiver@2e573ced that was originally registered here. Are you missing a call to unregisterReceiver()?
03-17 12:55:52.683  3371  3371 E ActivityThread: android.app.IntentReceiverLeaked: Activity com.test.thalitest.MainActivity has leaked IntentReceiver io.jxcore.node.ConnectivityMonitor$WifiStateChangedAndConnectivityActionBroadcastReceiver@2e573ced that was originally registered here. Are you missing a call to unregisterReceiver()?
03-17 12:55:52.683  3371  3371 E ActivityThread: 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:970)
03-17 12:55:52.683  3371  3371 E ActivityThread: 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:771)
03-17 12:55:52.683  3371  3371 E ActivityThread: 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:2014)
03-17 12:55:52.683  3371  3371 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1994)
03-17 12:55:52.683  3371  3371 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1988)
03-17 12:55:52.683  3371  3371 E ActivityThread: 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:503)
03-17 12:55:52.683  3371  3371 E ActivityThread: 	at io.jxcore.node.ConnectivityMonitor.start(ConnectivityMonitor.java:67)
03-17 12:55:52.683  3371  3371 E ActivityThread: 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:90)
03-17 12:55:52.683  3371  3371 E ActivityThread: 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
03-17 12:55:52.683  3371  3371 E ActivityThread: 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
03-17 12:55:52.683  3371  3371 E ActivityThread: 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
03-17 12:55:52.683  3371  3371 E ActivityThread: 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
03-17 12:55:52.683  3371  3371 E ActivityThread: 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
03-17 12:55:52.683  3371  3371 E ActivityThread: 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
03-17 12:55:52.683  3371  3371 E ActivityThread: 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
03-17 12:55:52.683  3371  3371 E ActivityThread: 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
03-17 12:55:52.683  3371  3371 E ActivityThread: 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
03-17 12:55:52.683  3371  3371 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 12:55:52.683  3371  3371 E ActivityThread: 	at android.os.Looper.loop(Looper.java:145)
03-17 12:55:52.683  3371  3371 E ActivityThread: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-17 12:55:52.683   284   284 W QCamera2Factory: getCameraInfo: E, camera_id = 0
03-17 12:55:52.683   284   284 W QCamera2Factory: getCameraInfo: X
,03-17 12:55:52.693  3164  3206 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 4 sec
,03-17 12:55:52.693  1022  1506 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,03-17 12:55:52.693  1022  1506 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,03-17 12:55:52.703  1022  1515 D SecContentProvider2: uri = 14 selection = getSealedState
03-17 12:55:52.703  1022  1515 D SecContentProvider2: mCursor = null
,03-17 12:55:52.713  4069  4069 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 12:55:52.713  1022  1515 D SecContentProvider2: uri = 14 selection = getSealedUsbMassStorageState
03-17 12:55:52.713  1022  1515 D SecContentProvider2: mCursor = null
,03-17 12:55:52.713  4069  4069 D ActivityThread: Added TimaKeyStore provider
,03-17 12:55:52.713   284   812 W QCamera2Factory: getCameraInfo: E, camera_id = 1
03-17 12:55:52.713   284   812 W QCamera2Factory: getCameraInfo: X
,03-17 12:55:52.713  4051  4051 V MTPRx   : sealedState: false
03-17 12:55:52.713  4051  4051 V MTPRx   : sealedUsbMassStorageState: false
,03-17 12:55:52.713  1022  3083 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:52.713  3758  3837 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
03-17 12:55:52.713  1022  3083 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:52.713  1022  3083 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:55:52.713  1022  3083 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:55:52.723  3758  3837 I GFX raster: took 0.736354ms for 96*96 texture 0
03-17 12:55:52.723  3758  3837 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb869b360 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb86978e8 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 12:55:52.723  1022  1046 W libprocessgroup: failed to open /acct/uid_10086/pid_3119/cgroup.procs: No such file or directory
,03-17 12:55:52.733  3758  3837 I AMMetaDataParserService: Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,03-17 12:55:52.733  4087  4087 E Zygote  : MountEmulatedStorage()
03-17 12:55:52.733  4087  4087 I libpersona: KNOX_SDCARD checking this for 1000
03-17 12:55:52.733  4087  4087 E Zygote  : v2
03-17 12:55:52.733  4087  4087 I libpersona: KNOX_SDCARD not a persona
,03-17 12:55:52.733  4087  4087 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 12:55:52.743  1022  3083 I ActivityManager: Start proc com.sec.android.app.SecSetupWizard for broadcast com.sec.android.app.SecSetupWizard/.SetupIntentReceiver: pid=4087 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
,03-17 12:55:52.743  4087  4087 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 12:55:52.743  4087  4087 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 12:55:52.743  3758  3837 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
03-17 12:55:52.743  3758  3837 I GFX raster: took 0.721302ms for 96*96 texture 0
03-17 12:55:52.743  1022  3060 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
03-17 12:55:52.743  3758  3837 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8692a68 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb86978e8 counterpartCT=4 counterpartW=96 counterparth=96
03-17 12:55:52.743  1022  3060 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:55:52.743  1022  3060 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:55:52.743  1022  3060 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
03-17 12:55:52.753  1022  3133 W ActivityManager: getTasks: caller 10145 does not hold GET_TASKS; limiting output
,03-17 12:55:52.753  3758  3837 I AMMetaDataParserService: Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
,03-17 12:55:52.763  1022  1534 I ActivityManager: Killing 3256:com.sec.factory.camera/1000 (adj 15): empty #31
,03-17 12:55:52.763  3908  3985 I Process : Sending signal. PID: 3908 SIG: 9
,03-17 12:55:52.773  1022  3083 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
,03-17 12:55:52.773  1022  3083 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,03-17 12:55:52.783  1022  1534 D SettingsProvider: name = mtp_usb_connection_status
,03-17 12:55:52.793  1696  1696 E SQLiteLog: (10) POSIX Error : 11 SQLite Error : 3850
,03-17 12:55:52.793  4087  4087 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:55:52.793  4087  4087 D ActivityThread: Added TimaKeyStore provider
,03-17 12:55:52.803  3758  3837 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 12:55:52.803  3758  3837 I GFX raster: took 0.546979ms for 96*96 texture 0
03-17 12:55:52.803  3758  3837 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb86978e8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb869b580 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 12:55:52.813  3758  3837 I AMMetaDataParserService: Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,03-17 12:55:52.813  1022  1046 W libprocessgroup: failed to open /acct/uid_10094/pid_3214/cgroup.procs: No such file or directory
,03-17 12:55:52.813  1022  1046 W libprocessgroup: failed to open /acct/uid_1000/pid_3239/cgroup.procs: No such file or directory
03-17 12:55:52.813  1022  1046 W libprocessgroup: failed to open /acct/uid_1000/pid_3256/cgroup.procs: No such file or directory
,03-17 12:55:52.813  3797  3797 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,03-17 12:55:52.823  4069  4069 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-17 12:55:52.823  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.dialer.DialtactsActivity
03-17 12:55:52.823  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:52.823  3758  3837 I AMMetaDataParserService: getResourcePackageName:assistant
03-17 12:55:52.823  3758  3837 I AMMetaDataParserService: Resource data:2131034113
03-17 12:55:52.823  1022  3133 D SettingsProvider: name = media_player_mode
,03-17 12:55:52.823  3758  3837 I AMMetaDataParserService: getResourceName:com.android.contacts:xml/assistant_main
,03-17 12:55:52.823  3758  3837 I AMMetaDataParserService: getResourceTypeNamexml
03-17 12:55:52.823  1191  1191 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
03-17 12:55:52.823  3758  3837 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 12:55:52.823  3758  3837 I GFX raster: took 0.826146ms for 96*96 texture 0
03-17 12:55:52.823  3758  3837 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8692620 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb869be18 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 12:55:52.823  3797  3797 I Babel_Crash: startup - clean
,03-17 12:55:52.833  1022  1365 I ActivityManager: Killing 3294:com.samsung.android.intelligenceservice/u0a3 (adj 15): empty #31
,03-17 12:55:52.833  3758  3837 I AMMetaDataParserService: Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
,03-17 12:55:52.843  3797  4103 I Babel   : deleted: false for 0
,03-17 12:55:52.863  1022  1083 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:55:52.863  1022  1083 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:52.863  1022  1083 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:55:52.863  1022  1083 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:55:52.873  4106  4106 E Zygote  : MountEmulatedStorage()
03-17 12:55:52.873  4106  4106 E Zygote  : v2
03-17 12:55:52.873  4106  4106 I libpersona: KNOX_SDCARD checking this for 1000
03-17 12:55:52.873  4106  4106 I libpersona: KNOX_SDCARD not a persona
,03-17 12:55:52.883  4106  4106 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 12:55:52.883  1022  1083 I ActivityManager: Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.BootReceiver: pid=4106 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
,03-17 12:55:52.883  1022  1083 I ActivityManager: Killing 3303:com.samsung.android.app.watchmanagerstub/u0a100 (adj 15): empty #31
03-17 12:55:52.883  4106  4106 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 12:55:52.883  4106  4106 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 12:55:52.893  1022  1234 D PersonaManagerService: getPersonasForUser(): returning null!
,03-17 12:55:52.893  1022  1515 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 12:55:52.893  1022  1515 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:55:52.893  1022  1515 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:55:52.893  1022  1515 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.gms
,03-17 12:55:52.893  1022  3083 I ActivityManager: Process com.android.email (pid 3908)(adj 9) has died(77,1099)
,03-17 12:55:52.893  4011  4011 I ActivityThread: Removing dead content provider:android.content.ContentProviderProxy@1d47299d
03-17 12:55:52.893  4011  4011 I ActivityThread: Removing dead content provider:android.content.ContentProviderProxy@1d47299d
,03-17 12:55:52.903  4106  4106 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:55:52.903  4106  4106 D ActivityThread: Added TimaKeyStore provider
,03-17 12:55:52.903  4069  4069 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.intent.action.BOOT_COMPLETED myUserId=0
,03-17 12:55:52.913  4069  4121 I KnoxUsageLogPro: savePreference: key = previous_sys_time value = 1458215752920
,03-17 12:55:52.913  4069  4069 I KnoxUsageLogPro: premStatus:2
,03-17 12:55:52.913  4069  4069 I KnoxUsageLogPro: isEulaShown : false
,03-17 12:55:52.913  4069  4069 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,03-17 12:55:52.933  1022  1534 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:55:52.933  1022  1534 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:52.933  1022  1534 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:52.933  1022  1534 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:55:52.933   289   289 E SMD     : DCD OFF
03-17 12:55:52.933  4106  4106 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,03-17 12:55:52.933  4106  4106 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
03-17 12:55:52.933  4106  4106 D SecurityLogAgent: StateMachine : Current State = 1
03-17 12:55:52.933  4106  4106 D SecurityLogAgent: BootReceiver : completed task. Failed to return wakelock . 
,03-17 12:55:52.943  1022  1534 I ActivityManager: Start proc com.android.email for content provider com.android.email/.provider.EmailProvider: pid=4124 uid=10145 gids={50145, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,03-17 12:55:52.953  4124  4124 E Zygote  : MountEmulatedStorage()
03-17 12:55:52.953  4124  4124 E Zygote  : v2
03-17 12:55:52.953  4124  4124 I libpersona: KNOX_SDCARD checking this for 10145
03-17 12:55:52.953  4124  4124 I libpersona: KNOX_SDCARD not a persona
03-17 12:55:52.953  4124  4124 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 12:55:52.953  4124  4124 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-17 12:55:52.953  1022  3083 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:52.953  4124  4124 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 12:55:52.953  1022  3083 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:52.953  1022  3083 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:52.953  1022  3083 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:52.953  1022  1046 W libprocessgroup: failed to open /acct/uid_10003/pid_3294/cgroup.procs: No such file or directory
,03-17 12:55:52.953  1022  1482 D SettingsProvider: name = mtp_usb_conditions_met
,03-17 12:55:52.963  1191  1191 I SecKeyguardClockSingleView: Ignore. Because it is same clock text,
,03-17 12:55:52.963  1022  1518 D SettingsProvider: name = mtp_running_status
,03-17 12:55:52.973  4069  4121 I KnoxUsageLogPro: savePreference: key = previous_elapsed_time value = 43234
03-17 12:55:52.973  4133  4133 I libpersona: KNOX_SDCARD checking this for 10152
03-17 12:55:52.973  4133  4133 E Zygote  : MountEmulatedStorage()
03-17 12:55:52.973  4133  4133 I libpersona: KNOX_SDCARD not a persona
03-17 12:55:52.973  4133  4133 E Zygote  : v2
,03-17 12:55:52.973  4133  4133 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 12:55:52.973  1022  3133 D SettingsProvider: name = media_mount_count
03-17 12:55:52.973  1022  3083 I ActivityManager: Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=4133 uid=10152 gids={50152, 9997, 1023} abi=armeabi-v7a,
03-17 12:55:52.973  4133  4133 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-17 12:55:52.973  1022  3083 I ActivityManager: Killing 3380:com.samsung.helphub/1000 (adj 15): empty #31
,03-17 12:55:52.973  4133  4133 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 12:55:52.973  1191  1191 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 12:55:52.993   310   310 I art     : Explicit concurrent mark sweep GC freed 8776(374KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 652us total 21.429ms
,03-17 12:55:52.993  3758  3837 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 12:55:52.993  3758  3837 I GFX raster: took 0.815834ms for 96*96 texture 0
03-17 12:55:52.993  3758  3837 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8692620 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb86975b0 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 12:55:53.003  1191  1191 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 12:55:53.003  1022  1034 D SettingsProvider: name = mtp_sync_alive
03-17 12:55:53.003  3758  3837 I AMMetaDataParserService: Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,03-17 12:55:53.003  4124  4124 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:55:53.003  4124  4124 D ActivityThread: Added TimaKeyStore provider
,03-17 12:55:53.013   310   310 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 618us total 17.544ms
,03-17 12:55:53.013  1022  1083 I ActivityManager: Killing 3404:com.samsung.android.scloud.backup/u0a60 (adj 15): empty #31
,03-17 12:55:53.023  1022  1361 D SettingsProvider: name = sdcard_launch,
,03-17 12:55:53.023  4133  4133 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 12:55:53.023  1191  1191 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
03-17 12:55:53.023  4133  4133 D ActivityThread: Added TimaKeyStore provider
,03-17 12:55:53.033  1191  1191 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 12:55:53.033  1022  1365 D SettingsProvider: name = boot_time_connected
03-17 12:55:53.033   310   310 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 616us total 22.607ms
,03-17 12:55:53.043  1191  1191 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 12:55:53.043  1022  3060 D SettingsProvider: name = mtp_open_session
,03-17 12:55:53.053  1763  3821 I GCoreUlr: WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=10, mName='AuthError'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,03-17 12:55:53.063  1191  1191 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 12:55:53.063  3758  3837 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 12:55:53.063  3758  3837 I GFX raster: took 0.681927ms for 96*96 texture 0
,03-17 12:55:53.063  1022  1046 W libprocessgroup: failed to open /acct/uid_10100/pid_3303/cgroup.procs: No such file or directory
,03-17 12:55:53.063  3758  3837 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8697700 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb869ab00 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 12:55:53.073  3758  3837 I AMMetaDataParserService: Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,03-17 12:55:53.083  1022  1046 W libprocessgroup: failed to open /acct/uid_1000/pid_3380/cgroup.procs: No such file or directory
,03-17 12:55:53.083  1022  1046 W libprocessgroup: failed to open /acct/uid_10060/pid_3404/cgroup.procs: No such file or directory
,03-17 12:55:53.093  3797  3797 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,03-17 12:55:53.093  3797  3797 W AudioCapabilities: Unsupported mime audio/evrc
,03-17 12:55:53.093  3797  3797 W AudioCapabilities: Unsupported mime audio/qcelp
,03-17 12:55:53.093  3758  3837 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 12:55:53.093  3758  3837 I GFX raster: took 0.610417ms for 96*96 texture 0
03-17 12:55:53.093  3758  3837 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb869b670 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8695970 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 12:55:53.093  3797  3797 W AudioCapabilities: Unsupported mime audio/mpeg-L1
,03-17 12:55:53.103  3797  3797 W AudioCapabilities: Unsupported mime audio/mpeg-L2
,03-17 12:55:53.103  3797  3797 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,03-17 12:55:53.103  3797  3797 W AudioCapabilities: Unsupported mime audio/x-ima
,03-17 12:55:53.103  3758  3837 I AMMetaDataParserService: Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,03-17 12:55:53.103  3797  3797 W AudioCapabilities: Unsupported mime audio/qcelp
,03-17 12:55:53.103  3797  3797 W AudioCapabilities: Unsupported mime audio/evrc
,03-17 12:55:53.113  3758  3837 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 12:55:53.113  3758  3837 I GFX raster: took 0.980573ms for 96*96 texture 0
03-17 12:55:53.113  3758  3837 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb86992a0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8698e50 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 12:55:53.113  3797  3797 W VideoCapabilities: Unsupported mime video/wvc1
,03-17 12:55:53.113  3797  3797 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,03-17 12:55:53.123  3758  3837 I AMMetaDataParserService: Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,03-17 12:55:53.123  3797  3797 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
,03-17 12:55:53.133  3797  3797 W VideoCapabilities: Unsupported mime video/wvc1
,03-17 12:55:53.133  3758  3837 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 12:55:53.133  3758  3837 I GFX raster: took 0.622500ms for 96*96 texture 0
03-17 12:55:53.133  3758  3837 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb869b360 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8698e50 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 12:55:53.133  3797  3797 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,03-17 12:55:53.133  3797  3797 W VideoCapabilities: Unsupported mime video/x-ms-wmv7
,03-17 12:55:53.133  3797  3797 W VideoCapabilities: Unsupported mime video/x-ms-wmv8
,03-17 12:55:53.143  3758  3837 I AMMetaDataParserService: Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,03-17 12:55:53.143  3797  3797 W VideoCapabilities: Unsupported mime video/mp43
,03-17 12:55:53.143  3797  3797 W VideoCapabilities: Unsupported mime video/sorenson
,03-17 12:55:53.143  3758  3837 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 12:55:53.153  3758  3837 I GFX raster: took 0.858438ms for 96*96 texture 0
03-17 12:55:53.153  3758  3837 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8692a68 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8698e50 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 12:55:53.153  3797  3797 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,03-17 12:55:53.153  3758  3837 I AMMetaDataParserService: Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
,03-17 12:55:53.163  3797  3797 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,03-17 12:55:53.173  3758  3837 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 12:55:53.173  3758  3837 I GFX raster: took 0.523698ms for 96*96 texture 0
03-17 12:55:53.173  3758  3837 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb86978e8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8698e50 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 12:55:53.173  3758  3837 I AMMetaDataParserService: Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,03-17 12:55:53.183  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.samsung.android.multiuser.install_only_owner
,03-17 12:55:53.183  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.ContactSelectionActivity
,03-17 12:55:53.183  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionTabActivity
03-17 12:55:53.183  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionGroupSelectionActivity
,03-17 12:55:53.183  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.DialtactsActivity
03-17 12:55:53.183  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.RecentCallsListActivity
,03-17 12:55:53.183  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.CallLogActivity
03-17 12:55:53.183  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.ContactsListActivity
03-17 12:55:53.183  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.ContactsFrontDoor
,03-17 12:55:53.183  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.DialtactsContactsEntryActivity
,03-17 12:55:53.193  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.PeopleActivity
03-17 12:55:53.193  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.JoinContactActivity
03-17 12:55:53.193  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.preference.ContactsPreferenceActivity
03-17 12:55:53.193  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.common.list.AccountFilterActivity
03-17 12:55:53.193  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.common.list.CustomContactListFilterActivity
03-17 12:55:53.193  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.ShowOrCreateActivity
03-17 12:55:53.193  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.GroupDetailActivity
03-17 12:55:53.193  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.GroupEditorActivity
03-17 12:55:53.193  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.quickcontact.QuickContactActivity
03-17 12:55:53.193  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:53.193  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.sec.android.multiwindow.activity.STYLE
03-17 12:55:53.193  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.ContactShortcut
03-17 12:55:53.193  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activityalias.DialShortcut
03-17 12:55:53.193  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activityalias.MessageShortcut
03-17 12:55:53.193  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.dialer.CallDetailActivity
03-17 12:55:53.193  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDetailDeleteActivity
03-17 12:55:53.193  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.ContactDetailActivity
03-17 12:55:53.193  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:53.193  3758  3837 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
03-17 12:55:53.193  3758  3837 I AMMetaDataParserService: getResourcePackageName:assistant
03-17 12:55:53.193  3758  3837 I AMMetaDataParserService: Resource data:2131034112
03-17 12:55:53.193  1022  1515 I art     : Explicit concurrent mark sweep GC freed 31301(1840KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 30MB/45MB, paused 2.490ms total 165.366ms
03-17 12:55:53.193  3758  3837 I AMMetaDataParserService: getResourceName:com.android.contacts:xml/assistant_detail
03-17 12:55:53.193  3758  3837 I AMMetaDataParserService: getResourceTypeNamexml
,03-17 12:55:53.193  3758  3837 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 12:55:53.193  3758  3837 I GFX raster: took 0.599895ms for 96*96 texture 0
03-17 12:55:53.193  3758  3837 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb869b670 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8698e50 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 12:55:53.193  1022  1048 D SecurityLogAgent:SEDenialService: Got CLOSE_WRITE Event sk.log
03-17 12:55:53.193  1022  1048 D SecurityLogAgent:SEDenialService: Got CLOSE_WRITE Event sk.log
,03-17 12:55:53.203  3797  3797 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,03-17 12:55:53.203  3797  3797 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,03-17 12:55:53.203  1022  1048 D SecurityLogAgent:SEDenialService: Got CLOSE_WRITE Event sk.log
,03-17 12:55:53.203  3797  3797 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,03-17 12:55:53.203  3758  3837 I AMMetaDataParserService: Icon data: ResourceAdd to Favourites2131690170android.intent.assistant.detail.favorite2130837530
,03-17 12:55:53.213  3554  3554 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
03-17 12:55:53.213  3554  3554 I PCWCLIENTTRACE_PushUtil: sales region : global
03-17 12:55:53.213  3554  3554 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
03-17 12:55:53.213  3554  3554 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.intent.action.BOOT_COMPLETED
03-17 12:55:53.213  3554  3554 D PCWCLIENTTRACE_SYSTEMReceiver: ACTION_BOOTUP - Version: 4.82
03-17 12:55:53.213  3554  3554 D PCWCLIENTTRACE_SYSTEMReceiver: ACTION_BOOTUP - Push type: [SPP, GCM]
,03-17 12:55:53.213  3797  3797 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,03-17 12:55:53.213  4124  4124 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,03-17 12:55:53.213  4124  4124 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-17 12:55:53.213  4124  4124 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
03-17 12:55:53.213  4124  4124 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 12:55:53.213  4124  4124 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,03-17 12:55:53.213  1763  3821 I GCoreUlr: Unbound from all location providers
,03-17 12:55:53.233  3758  3837 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 12:55:53.233  3758  3837 I GFX raster: took 1.580208ms for 96*96 texture 0
03-17 12:55:53.233  3758  3837 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb869b670 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8698e50 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 12:55:53.233  3554  3554 W PCWCLIENTTRACE_AccountUtil: [hasSamungAccount] - No Samsung Account
,03-17 12:55:53.243  4133  4133 E SQLiteLog: (284) automatic index on shooting_modes(title_id)
,03-17 12:55:53.253  3758  3837 I AMMetaDataParserService: Icon data: ResourceRemove from Favourites2131690212android.intent.assistant.detail.favorite2130837530
,03-17 12:55:53.263  1022  3133 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.ShootingModesService; callingUser = 0; userId(target) = 0
,03-17 12:55:53.263  1022  3133 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:55:53.263  1022  3133 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 12:55:53.263  1022  3133 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.provider.shootingmodeprovider, destAppInfo.processName = com.samsung.android.provider.shootingmodeprovider
,03-17 12:55:53.263  1022  1518 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:55:53.273  1022  1518 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:55:53.273  1022  1518 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:53.273  1022  1518 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:55:53.273  3797  3797 I vclib   : onServiceConnected
,03-17 12:55:53.273  3797  3797 W Babel   : Attempted to change video mute state without an active call.
,03-17 12:55:53.273  3554  3554 I PCWCLIENTTRACE_SecurePreferencesJNI: [GetString-S]
,03-17 12:55:53.273  3758  3837 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
03-17 12:55:53.273  3758  3837 I GFX raster: took 0.638750ms for 96*96 texture 0
03-17 12:55:53.273  3758  3837 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb867a600 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb865de18 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 12:55:53.283  3554  3554 I ReactiveServiceManager: Supported : 1
,03-17 12:55:53.283  3758  3837 I AMMetaDataParserService: Icon data: ResourceEdit2131690192android.intent.assistant.detail.edit2130837529
,03-17 12:55:53.283  4159  4159 E Zygote  : MountEmulatedStorage()
,03-17 12:55:53.283  4159  4159 E Zygote  : v2
03-17 12:55:53.283  4159  4159 I libpersona: KNOX_SDCARD checking this for 1000
03-17 12:55:53.293  1022  1365 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x2040
03-17 12:55:53.293  4159  4159 I libpersona: KNOX_SDCARD not a persona
,03-17 12:55:53.293  1022  1365 D QSEECOMAPI: : App is not loaded in QSEE
03-17 12:55:53.293  1022  1518 I ActivityManager: Start proc com.sec.modem.settings for broadcast com.sec.modem.settings/.cplogging.SilentLogReceiver: pid=4159 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-17 12:55:53.293  4159  4159 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-17 12:55:53.293  4159  4159 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-17 12:55:53.293  4159  4159 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 12:55:53.293  1022  1518 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:53.293  3758  3837 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
03-17 12:55:53.293  1022  1518 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:53.293  1022  1518 E ActivityManager: checkUser: useridlist=null, currentuser=0,
03-17 12:55:53.293  1022  1234 D RCPManagerService: exchangeData() failure , invalid userId
03-17 12:55:53.293  1022  1518 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:53.293  3758  3837 I GFX raster: took 0.717137ms for 96*96 texture 0
03-17 12:55:53.293  3758  3837 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb83d72b8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8670738 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 12:55:53.303  3758  3837 I AMMetaDataParserService: Icon data: ResourceDelete2131690186android.intent.assistant.detail.delete2130837528
,03-17 12:55:53.303  4159  4159 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:55:53.313  4159  4159 D ActivityThread: Added TimaKeyStore provider
,03-17 12:55:53.313  1022  1365 D QSEECOMAPI: : Loaded image: APP id = 10
,03-17 12:55:53.323  1022  1365 D QSEECOMAPI: : QSEECom_dealloc_memory ,
03-17 12:55:53.323  1022  1365 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 10
03-17 12:55:53.323  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.detail.SelectContactInfoActivity
03-17 12:55:53.323  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.ConfirmAddDetailActivity
03-17 12:55:53.323  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorAccountsChangedActivity
03-17 12:55:53.323  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorActivity
,03-17 12:55:53.323  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.RingtoneRecommendationHelperActivity
03-17 12:55:53.323  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.editor.AddAnotherFieldDialogActivity
03-17 12:55:53.323  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.AttachPhotoActivity
03-17 12:55:53.323  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.PhotoSelectionActivity
,03-17 12:55:53.323  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.common.vcard.ImportVCardActivity
03-17 12:55:53.323  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportVCardPreviewActivity
03-17 12:55:53.323  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.common.vcard.NfcImportVCardActivity,
03-17 12:55:53.323  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.common.vcard.CancelActivity
03-17 12:55:53.323  4172  4172 I libpersona: KNOX_SDCARD checking this for 10035
03-17 12:55:53.323  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.common.vcard.SelectAccountActivity
03-17 12:55:53.323  4172  4172 I libpersona: KNOX_SDCARD not a persona,
03-17 12:55:53.323  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.common.vcard.ExportVCardActivity
03-17 12:55:53.323  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportFinishActivity
03-17 12:55:53.323  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.SIMContactSelectionActivity
03-17 12:55:53.323  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbers
,03-17 12:55:53.323  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbersTabActivity
03-17 12:55:53.323  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.VerizonBackupAssistantActivity
03-17 12:55:53.323  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.widget.PinnedHeaderListDemoActivity
03-17 12:55:53.323  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.NonPhoneActivity
03-17 12:55:53.323  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.favorite.FavoriteSelectionActivity
,03-17 12:55:53.323  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.detail.SetDefaultActivity
03-17 12:55:53.323  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.group.GroupChangeOrderActivity
03-17 12:55:53.323  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.editor.EditGroupSelectionActivity
03-17 12:55:53.323  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.group.GroupMultiSelectionActivity
03-17 12:55:53.323  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.emergency.InteractionEmergencyMessageActivity
,03-17 12:55:53.323  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.emergency.EmergencyMessageContactCreateActivity
03-17 12:55:53.323  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.emergency.EmergencyContactListDialogActivity
03-17 12:55:53.323  1022  1365 E terrier : handleString: Failed to handle string(-4)
03-17 12:55:53.323  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.group.SubGroupDetailActivity
03-17 12:55:53.323  1022  1365 E terrier : Java_com_android_server_ReactiveService_GetString: error code = [-4]
,03-17 12:55:53.323  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.GroupListActivity
03-17 12:55:53.323  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDurationActivity
03-17 12:55:53.323  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDurationTabActivity
03-17 12:55:53.323  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.detail.LinkedContactActivity
03-17 12:55:53.323  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.impl.DialerTutorialActivity
,03-17 12:55:53.323  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.impl.HelpPeopleActivity
03-17 12:55:53.323  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyPeopleActivity
03-17 12:55:53.323  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.impl.HelpInteractionTabActivity,
03-17 12:55:53.323  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyInteractionTabActivity
03-17 12:55:53.323  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.impl.HelpSpeedDialActivity
03-17 12:55:53.333  1022  1518 I ActivityManager: Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=4172 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-17 12:55:53.323  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactEditorActivity
03-17 12:55:53.323  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactSelectionActivity
03-17 12:55:53.323  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.EasyPeopleActivity
03-17 12:55:53.323  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:53.323  3758  3837 I AMMetaDataParserService: getResourcePackageName:assistant
03-17 12:55:53.323  3758  3837 I AMMetaDataParserService: Resource data:2131034113,
03-17 12:55:53.333  1022  1518 I ActivityManager: Killing 3439:com.sec.knox.foldercontainer/1000 (adj 15): empty #31
03-17 12:55:53.323  3554  3554 D PCWCLIENTTRACE_SecurePreferencesJNI: getString is null
03-17 12:55:53.323  3554  3554 I PCWCLIENTTRACE_SecurePreferencesJNI: [GetString-E]
03-17 12:55:53.323  3758  3837 I AMMetaDataParserService: getResourceName:com.android.contacts:xml/assistant_main
03-17 12:55:53.323  3758  3837 I AMMetaDataParserService: getResourceTypeNamexml
03-17 12:55:53.323  3554  3554 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
03-17 12:55:53.323  3554  3554 I PCWCLIENTTRACE_PushUtil: sales region : global
03-17 12:55:53.333  1022  1506 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
03-17 12:55:53.323  3554  3554 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
03-17 12:55:53.323  3554  3554 E PCWCLIENTTRACE_PCWHandler: [ensureRegistration] - No Samsung account
03-17 12:55:53.323  4172  4172 E Zygote  : MountEmulatedStorage()
03-17 12:55:53.323  4172  4172 E Zygote  : v2
03-17 12:55:53.323  3758  3837 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
03-17 12:55:53.323  4172  4172 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-17 12:55:53.323  3758  3837 I GFX raster: took 0.830104ms for 96*96 texture 0
03-17 12:55:53.323  3758  3837 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb865eb48 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8679740 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 12:55:53.333  4172  4172 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 12:55:53.333  3758  3837 I AMMetaDataParserService: Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
03-17 12:55:53.333  4172  4172 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
03-17 12:55:53.333  1022  1506 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:55:53.333  1022  1506 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:55:53.333  1022  1506 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-17 12:55:53.343  3758  3837 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 12:55:53.343  3758  3837 I GFX raster: took 0.910157ms for 96*96 texture 0
03-17 12:55:53.343  3758  3837 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb865eb48 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb865de18 counterpartCT=4 counterpartW=96 counterparth=96
03-17 12:55:53.343  1022  1518 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:53.343  1022  1518 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:53.343  1022  1518 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:53.343  1022  1518 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:55:53.343  3873  3873 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,03-17 12:55:53.353  3758  3837 I AMMetaDataParserService: Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,03-17 12:55:53.363  4186  4186 E Zygote  : MountEmulatedStorage()
03-17 12:55:53.363  4186  4186 E Zygote  : v2
03-17 12:55:53.363  4186  4186 I libpersona: KNOX_SDCARD checking this for 10031
03-17 12:55:53.363  4186  4186 I libpersona: KNOX_SDCARD not a persona
,03-17 12:55:53.363  4186  4186 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 12:55:53.363  4186  4186 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
03-17 12:55:53.363  4186  4186 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-17 12:55:53.363  1022  1518 I ActivityManager: Start proc com.vlingo.midas for broadcast com.vlingo.midas/com.vlingo.core.facade.lmtt.LmttReceiver: pid=4186 uid=10031 gids={50031, 9997, 1028, 1015, 3003, 3002, 3001} abi=armeabi-v7a
03-17 12:55:53.363  1022  1518 I ActivityManager: Killing 3470:com.fmm.dm/1000 (adj 15): empty #31
,03-17 12:55:53.373  3758  3837 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
03-17 12:55:53.373  3758  3837 I GFX raster: took 0.635990ms for 96*96 texture 0
03-17 12:55:53.373  3758  3837 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb82c8c48 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb865a760 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 12:55:53.373  4172  4172 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 12:55:53.373  4172  4172 D ActivityThread: Added TimaKeyStore provider
03-17 12:55:53.373  1022  1083 D RCPManagerService: exchangeData() failure , invalid userId
,03-17 12:55:53.383  1022  1035 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
,03-17 12:55:53.393  1022  1035 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:55:53.393  1022  1035 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-17 12:55:53.393  1022  1035 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,03-17 12:55:53.393  1022  1534 D RCPManagerService: exchangeData() failure , invalid userId
,03-17 12:55:53.393  1022  1506 I ActivityManager: Killing 3488:com.samsung.android.scloud.sync/u0a62 (adj 15): empty #31
,03-17 12:55:53.393  4186  4186 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:55:53.393  4186  4186 D ActivityThread: Added TimaKeyStore provider
,03-17 12:55:53.403  1022  1506 I ActivityManager: Killing 3505:com.sec.knox.knoxsetupwizardclient/1000 (adj 15): empty #31
,03-17 12:55:53.413  3758  3837 I AMMetaDataParserService: Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,03-17 12:55:53.413  1022  3060 D RCPManagerService: exchangeData() failure , invalid userId
,03-17 12:55:53.413  1022  1506 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:55:53.413  1022  1506 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:53.413  1022  1506 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:55:53.413  1022  1506 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:55:53.423  3758  3837 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96,
,03-17 12:55:53.423  3758  3837 I GFX raster: took 0.647812ms for 96*96 texture 0
03-17 12:55:53.423  3758  3837 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb869b670 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8698e50 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 12:55:53.433  3758  3837 I AMMetaDataParserService: Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,03-17 12:55:53.443  4186  4186 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,03-17 12:55:53.453  1022  2815 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.ssrm.I.m:-1 com.android.server.ssrm.J.run:-1 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 
,03-17 12:55:53.453  1022  1534 D RCPManagerService: exchangeData() failure , invalid userId
,03-17 12:55:53.453  4214  4214 E Zygote  : MountEmulatedStorage()
03-17 12:55:53.453  4214  4214 E Zygote  : v2
03-17 12:55:53.453  4214  4214 I libpersona: KNOX_SDCARD checking this for 1101
03-17 12:55:53.453  4214  4214 I libpersona: KNOX_SDCARD not a persona
,03-17 12:55:53.463  4214  4214 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 12:55:53.463  4214  4214 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 12:55:53.463  4214  4214 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 12:55:53.463  1022  3060 D RCPManagerService: exchangeData() failure , invalid userId
,03-17 12:55:53.473  1022  1506 I ActivityManager: Start proc org.simalliance.openmobileapi.service for broadcast org.simalliance.openmobileapi.service/.SmartcardServiceBootCompletedBroadcastReceiver: pid=4214 uid=1101 gids={41101, 9997} abi=armeabi-v7a
,03-17 12:55:53.473  1022  1506 I ActivityManager: Killing 3536:com.sec.android.app.mt/1000 (adj 15): empty #31
,03-17 12:55:53.493  1596  1611 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,03-17 12:55:53.493  1022  3060 W ActivityManager: getTasks: caller 10146 does not hold GET_TASKS; limiting output
,03-17 12:55:53.503  4214  4214 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:55:53.503  4214  4214 D ActivityThread: Added TimaKeyStore provider
,03-17 12:55:53.513  4011  4086 I Process : Sending signal. PID: 4011 SIG: 9
,03-17 12:55:53.513  1763  1763 I GCoreUlr: DispatchingService.onDestroy()
,03-17 12:55:53.513  1763  1763 I GCoreUlr: Unbound from all location providers
,03-17 12:55:53.523  3554  3580 D PCWCLIENTTRACE_AccountAppFacade2_0: unregister AuthInfo UpdateReceiver v2.0
,03-17 12:55:53.523  1022  2863 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-17 12:55:53.523  1596  2992 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
03-17 12:55:53.523  1596  2992 D BadgeProvider: sendNotify, [notify] : null
03-17 12:55:53.523  1596  2992 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
03-17 12:55:53.523  1596  2992 D BadgeProvider: update, [BadgeCount] : badgecount=0
03-17 12:55:53.523  1596  2992 D BadgeProvider: update, [UpdateCount] : 1
,03-17 12:55:53.523  1519  1519 D Launcher.Model: reloadBadges entered.
,03-17 12:55:53.533  3758  3837 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 12:55:53.533  3758  3837 I GFX raster: took 0.894428ms for 96*96 texture 0
03-17 12:55:53.533  3758  3837 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb865a760 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb867a580 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 12:55:53.543  4214  4214 W ResourcesManager: Asset path '/system/framework/org.simalliance.openmobileapi.jar' does not exist or contains no resources.
,03-17 12:55:53.543  4172  4230 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
,03-17 12:55:53.553  3758  3837 I AMMetaDataParserService: Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,03-17 12:55:53.553  4172  4230 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,03-17 12:55:53.553  4214  4214 V SmartcardService: main Received broadcast
03-17 12:55:53.553  4214  4214 V SmartcardService: Starting smartcard service after boot completed
,03-17 12:55:53.553  1022  1035 D ActivityManager: retrieveServiceLocked(): component = org.simalliance.openmobileapi.service/org.simalliance.openmobileapi.service.SmartcardService; callingUser = 0; userId(target) = 0
,03-17 12:55:53.553  1022  1035 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:55:53.553  1022  1035 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 12:55:53.553  1022  1035 W ActivityManager: NORMAL SET : srcAppInfo.processName = org.simalliance.openmobileapi.service, destAppInfo.processName = org.simalliance.openmobileapi.service
,03-17 12:55:53.563  1022  1506 I ActivityManager: Killing 3273:com.google.android.gms:car/u0a12 (adj 15): empty #31
,03-17 12:55:53.563  1022  1482 D ActivityManager: retrieveServiceLocked(): component = com.android.stk/com.android.stk.StkAppService; callingUser = 0; userId(target) = 0
,03-17 12:55:53.563  1022  1482 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:55:53.563  1022  1482 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-17 12:55:53.563  1022  1482 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
,03-17 12:55:53.573  1022  1518 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:55:53.573  1022  1518 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:55:53.573  1022  1518 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:53.573  1022  1518 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:55:53.573  4172  4172 E SPPClientService: [SystemStateMoniter] Action Name : android.intent.action.BOOT_COMPLETED
03-17 12:55:53.573  4172  4172 E SPPClientService: [SystemStateMoniter] Current Time : 43894
,03-17 12:55:53.583  4232  4232 E Zygote  : MountEmulatedStorage()
03-17 12:55:53.583  4232  4232 E Zygote  : v2
03-17 12:55:53.583  4232  4232 I libpersona: KNOX_SDCARD checking this for 1000
03-17 12:55:53.583  4232  4232 I libpersona: KNOX_SDCARD not a persona
,03-17 12:55:53.583  4232  4232 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-17 12:55:53.593  1022  1518 I ActivityManager: Start proc com.sec.android.app.sysscope for broadcast com.sec.android.app.sysscope/.receiver.BootCompleteReceiver: pid=4232 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-17 12:55:53.593  1022  1046 W libprocessgroup: failed to open /acct/uid_10062/pid_3488/cgroup.procs: No such file or directory
03-17 12:55:53.593  1022  1046 W libprocessgroup: failed to open /acct/uid_1000/pid_3470/cgroup.procs: No such file or directory
03-17 12:55:53.593  1022  1046 W libprocessgroup: failed to open /acct/uid_1000/pid_3439/cgroup.procs: No such file or directory
,03-17 12:55:53.593  1022  1046 W libprocessgroup: failed to open /acct/uid_1000/pid_3505/cgroup.procs: No such file or directory
03-17 12:55:53.593  4232  4232 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 12:55:53.593  1022  1046 W libprocessgroup: failed to open /acct/uid_1000/pid_3536/cgroup.procs: No such file or directory
03-17 12:55:53.593  4232  4232 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 12:55:53.593  4172  4230 D SPPClientService: PushLog.txt file is not deleted.
03-17 12:55:53.593  4172  4230 D SPPClientService: PushLog.txt file is not deleted.
03-17 12:55:53.593  4172  4230 D SPPClientService: ============PushLog. stop!
,03-17 12:55:53.613  1022  3083 I ActivityManager: Process com.android.exchange (pid 4011)(adj 15) has died(64,1108)
,03-17 12:55:53.623  4232  4232 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:55:53.623  4232  4232 D ActivityThread: Added TimaKeyStore provider
,03-17 12:55:53.643  4232  4232 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.app.sysscope.receiver.BootCompleteReceiver.onReceive:-1 android.app.ActivityThread.handleReceiver:3125 
,03-17 12:55:53.643  1022  3083 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.app.sysscope/com.sec.android.app.sysscope.service.SysScopeService; callingUser = 0; userId(target) = 0
,03-17 12:55:53.643  1022  3083 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:55:53.643  1022  3083 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 12:55:53.643  1022  3083 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.sysscope, destAppInfo.processName = com.sec.android.app.sysscope
,03-17 12:55:53.653  1022  1534 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:55:53.653  1022  1534 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:53.653  1022  1534 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:55:53.653  1022  1534 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:55:53.663  1022  2815 D SSRM:n  : SIOP:: AP = 410
,03-17 12:55:53.673  4249  4249 E Zygote  : MountEmulatedStorage()
03-17 12:55:53.673  4249  4249 E Zygote  : v2
03-17 12:55:53.673  4249  4249 I libpersona: KNOX_SDCARD checking this for 10157
03-17 12:55:53.673  4249  4249 I libpersona: KNOX_SDCARD not a persona
,03-17 12:55:53.673  4249  4249 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 12:55:53.673  1022  1534 I ActivityManager: Start proc com.sec.android.app.taskmanager for broadcast com.sec.android.app.taskmanager/.UnusedAppsIntentReceiver: pid=4249 uid=10157 gids={50157, 9997} abi=armeabi-v7a
03-17 12:55:53.673  4249  4249 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 12:55:53.673  4249  4249 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 12:55:53.673  1022  1046 W libprocessgroup: failed to open /acct/uid_10012/pid_3273/cgroup.procs: No such file or directory
03-17 12:55:53.673  1022  1506 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.car.InCallServiceImpl in 1000ms
03-17 12:55:53.673  1022  1506 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.car.CarService in 11000ms
,03-17 12:55:53.693  3758  3837 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 12:55:53.693  3758  3837 I GFX raster: took 0.629791ms for 96*96 texture 0
03-17 12:55:53.693  3758  3837 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb83d72b8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb869b360 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 12:55:53.703  4249  4249 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:55:53.703  4249  4249 D ActivityThread: Added TimaKeyStore provider
,03-17 12:55:53.703  3758  3837 I AMMetaDataParserService: Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,03-17 12:55:53.703  3164  3206 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 5 sec
,03-17 12:55:53.713  3758  3837 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 12:55:53.713  3758  3837 I GFX raster: took 0.888334ms for 96*96 texture 0
,03-17 12:55:53.713  3758  3837 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb865de18 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb82c6a70 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 12:55:53.713  4249  4249 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-17 12:55:53.723  1022  1365 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
,03-17 12:55:53.723  1022  1365 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,03-17 12:55:53.723  3758  3837 I AMMetaDataParserService: Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
,03-17 12:55:53.723  1022  1083 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:53.723  1022  1083 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:53.723  1022  1083 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:53.723  1022  1083 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:55:53.733  4267  4267 E Zygote  : MountEmulatedStorage()
03-17 12:55:53.733  4267  4267 E Zygote  : v2
03-17 12:55:53.733  4267  4267 I libpersona: KNOX_SDCARD checking this for 10166
,03-17 12:55:53.733  4267  4267 I libpersona: KNOX_SDCARD not a persona
03-17 12:55:53.733  4186  4186 I VlingoApplication: VlingoApplication appVersion ='11.7.0.1.40254', coreVersion = '2.6.3.16956', ro.csc.sales_code=XEO
,03-17 12:55:53.733  4267  4267 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-17 12:55:53.733  1022  1083 I ActivityManager: Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService$BootReceiver: pid=4267 uid=10166 gids={50166, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-17 12:55:53.743  1022  1515 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
03-17 12:55:53.743  4267  4267 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-17 12:55:53.743  1022  1234 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
03-17 12:55:53.743  4267  4267 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
03-17 12:55:53.743  3758  3837 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
03-17 12:55:53.743  3758  3837 I GFX raster: took 0.604011ms for 96*96 texture 0
03-17 12:55:53.743  3758  3837 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8672db0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb867a580 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 12:55:53.753  3758  3837 I AMMetaDataParserService: Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,03-17 12:55:53.753  1022  1518 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:53.753  1022  1518 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:53.753  1022  1518 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:53.753  1022  1518 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:55:53.763  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.interactions.EasyInteractionTabActivity
03-17 12:55:53.763  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.calllog.LogsFindoSearchResultsActivity
03-17 12:55:53.763  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:53.763  3758  3837 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
03-17 12:55:53.763  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.dialpad.RegularSearchActivity
03-17 12:55:53.763  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.interaction.InteractionRecentActivity
03-17 12:55:53.763  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.editor.SamsungAccountValidationCheckActivity
03-17 12:55:53.763  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.autolink.AutoLinkActivity
03-17 12:55:53.763  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.EmergencyPeopleActivity
03-17 12:55:53.763  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.speeddial.SpeedDialActivity
03-17 12:55:53.763  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.businesscard.BusinesscardListActivity
03-17 12:55:53.763  3758  3837 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
03-17 12:55:53.763  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.businesscard.BusinesscardViewer
03-17 12:55:53.763  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.callmessage.CallMessageActivity
03-17 12:55:53.763  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.callmessage.RecentCallMessageActivity
03-17 12:55:53.763  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.callmessage.PhrasesEditActivity
03-17 12:55:53.763  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.callmessage.PhrasesDeleteActivity
03-17 12:55:53.763  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.callmessage.CallMessageEditActivity
03-17 12:55:53.763  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.emergency.MyEmergencyInfoDetailActivity
03-17 12:55:53.763  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.emergency.MyEmergencyInfoEditorActivity
03-17 12:55:53.763  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.ScoverFavoritesActivity
03-17 12:55:53.763  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:53.763  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.sec.android.sdk.cover.MODE
03-17 12:55:53.763  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.ScoverSelectNumberActivity
03-17 12:55:53.763  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:53.763  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.sec.android.sdk.cover.MODE
03-17 12:55:53.763  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.detail.ShowMyProfileActivity
03-17 12:55:53.,763  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionProfileWhiteListActivity
03-17 12:55:53.773  4281  4281 E Zygote  : MountEmulatedStorage()
03-17 12:55:53.773  4281  4281 E Zygote  : v2
03-17 12:55:53.773  4281  4281 I libpersona: KNOX_SDCARD checking this for 10159
03-17 12:55:53.773  4281  4281 I libpersona: KNOX_SDCARD not a persona
03-17 12:55:53.773  4281  4281 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-17 12:55:53.773  1022  1518 I ActivityManager: Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=4281 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-17 12:55:53.773  4281  4281 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-17 12:55:53.773  1022  1518 I ActivityManager: Killing 3179:com.android.vending/u0a28 (adj 15): empty #31
03-17 12:55:53.783  4281  4281 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
03-17 12:55:53.783  4267  4267 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 12:55:53.783  4267  4267 D ActivityThread: Added TimaKeyStore provider
,03-17 12:55:53.803  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.SSLCertValidationActivity
03-17 12:55:53.803  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.EmailUpgradeKeystoreActivity
03-17 12:55:53.803  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.SecurityCertificates
03-17 12:55:53.803  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.Welcome
03-17 12:55:53.803  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.UpgradeAccounts
03-17 12:55:53.803  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupWizard
03-17 12:55:53.803  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.snc.VZWSetupWizard
03-17 12:55:53.803  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncRestoreAccounts
03-17 12:55:53.803  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.snc.SncRestoreAccounts
03-17 12:55:53.803  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncRestoreOptions
03-17 12:55:53.803  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncNames
03-17 12:55:53.803  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncExchangeAccounts
03-17 12:55:53.803  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncAccountsLogin
03-17 12:55:53.803  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.LDAPClientSettings
03-17 12:55:53.803  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.LDAPAccountsList
03-17 12:55:53.803  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupBasics
03-17 12:55:53.803  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.DataConnection
03-17 12:55:53.803  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupAccountType
03-17 12:55:53.803  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupIncoming
03-17 12:55:53.803  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupOutgoing
03-17 12:55:53.803  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupExchange
03-17 12:55:53.803  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupOptions
03-17 12:55:53.803  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupNames
03-17 12:55:53.803  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsXL
03-17 12:55:53.803  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsAddRulesforFiltering
03-17 12:55:53.803  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AddPrioritySenderActivity
03-17 12:55:53.803  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.Ac,countSecurity
03-17 12:55:53.803  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountPreSetup
03-17 12:55:53.803  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.messageview.SaveasActivity
03-17 12:55:53.803  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.Debug
03-17 12:55:53.803  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.MessageListXL
03-17 12:55:53.803  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:53.803  3758  3837 I AMMetaDataParserService: getResourcePackageName:assistant
03-17 12:55:53.803  3758  3837 I AMMetaDataParserService: Resource data:2131165203
03-17 12:55:53.803  4186  4186 I VlingoAndroidCore: AppName: SamsungTproject, Core: 2.6.3.16956, SDK: 2.0.2173, EDM:16956
03-17 12:55:53.803  4281  4281 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 12:55:53.803  4281  4281 D ActivityThread: Added TimaKeyStore provider
03-17 12:55:53.803  3758  3837 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
03-17 12:55:53.803  3758  3837 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-17 12:55:53.803  3758  3837 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
03-17 12:55:53.803  3758  3837 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 12:55:53.803  3758  3837 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
03-17 12:55:53.803  3758  3837 I AMMetaDataParserService: getResourceName:com.android.email:xml/email_assistant_menu
03-17 12:55:53.813  3758  3837 I AMMetaDataParserService: getResourceTypeNamexml
03-17 12:55:53.813  3758  3837 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
03-17 12:55:53.813  3758  3837 I GFX construct_block_size_descriptor_2d second part: took 3.061302ms for 0*0 texture 0
03-17 12:55:53.823  3758  3837 I GFX generate_partition_tables: took 10.517447ms for 0*0 texture 0
03-17 12:55:53.823  3758  3837 I GFX raster: took 14.410311ms for 96*96 texture 0
03-17 12:55:53.823  3758  3837 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb86768f8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb8677f18 counterpartCT=4 counterpartW=96 counterparth=96
03-17 12:55:53.833  3758  3837 I AMMetaDataParserService: Icon data: ResourceDrawer menu2131363563com.android.email.intent.messagelistfragment.drawer2130837576
03-17 12:55:53.833  4281  4281 I Intent to TravelDirActivity: inside TravelBroadcastReceiver
03-17 12:55:53.843  3758  3837 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
03-17 12:55:53.843  3758  3837 I GFX raster: took 1.105729ms for 96*96 texture 0
03-17 12:55:53.843  3758  3837 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8849e48 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8849ef0 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 12:55:53.853  3758  3837 I AMMetaDataParserService: Icon data: ResourceMessage marked as complete2131362386com.android.email.intent.messageviewfragment.favorite2130837575
,03-17 12:55:53.863  1696  1696 E SQLiteLog: (10) POSIX Error : 11 SQLite Error : 3850
,03-17 12:55:53.863  1022  1046 W libprocessgroup: failed to open /acct/uid_10028/pid_3179/cgroup.procs: No such file or directory
,03-17 12:55:53.863  4186  4186 D VlingoApplication: sac sec ensureCacheEmpty() car_iux_tts_cacheing_required set to false
,03-17 12:55:53.873  4186  4186 D VlingoApplication: sac sec ensureCacheEmpty() purged 0 historically cached TTS files
,03-17 12:55:53.873  1022  1506 I ActivityManager: Killing 3585:com.sec.android.app.servicemodeapp/1000 (adj 15): empty #31
,03-17 12:55:53.873  4186  4186 D DialogFlow: initQueue()
,03-17 12:55:53.903  1022  1365 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:55:53.903  1022  1365 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:55:53.903  1022  1365 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:53.903  1022  1365 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:55:53.913  4300  4300 E Zygote  : MountEmulatedStorage(),
,03-17 12:55:53.913  4300  4300 E Zygote  : v2
03-17 12:55:53.913  4300  4300 I libpersona: KNOX_SDCARD checking this for 10032
03-17 12:55:53.913  4300  4300 I libpersona: KNOX_SDCARD not a persona
,03-17 12:55:53.913  4300  4300 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 12:55:53.913  4300  4300 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-17 12:55:53.913  1022  1365 I ActivityManager: Start proc com.samsung.android.app.galaxyfinder:tagService for broadcast com.samsung.android.app.galaxyfinder/.tag.TagReadyReceiver: pid=4300 uid=10032 gids={50032, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
03-17 12:55:53.913  1022  1365 I ActivityManager: Killing 3627:com.samsung.android.sconnect/u0a125 (adj 15): empty #31
,03-17 12:55:53.923  4300  4300 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 12:55:53.943  4300  4300 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:55:53.943  4300  4300 D ActivityThread: Added TimaKeyStore provider
,03-17 12:55:53.973  3758  3837 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 12:55:53.973  3758  3837 I GFX raster: took 0.842083ms for 96*96 texture 0
,03-17 12:55:53.973  3758  3837 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8849e48 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8849430 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 12:55:53.983  3758  3837 I AMMetaDataParserService: Icon data: ResourceFlagged message2131362384com.android.email.intent.messageviewfragment.favorite2130837575
,03-17 12:55:54.013  3758  3837 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 12:55:54.013  3758  3837 I GFX raster: took 0.837500ms for 96*96 texture 0
,03-17 12:55:54.013  3758  3837 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8849e48 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8848f18 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 12:55:54.023  3758  3837 I AMMetaDataParserService: Icon data: ResourceUnflagged message2131362385com.android.email.intent.messageviewfragment.favorite2130837575
,03-17 12:55:54.033  1022  1046 W libprocessgroup: failed to open /acct/uid_1000/pid_3585/cgroup.procs: No such file or directory
,03-17 12:55:54.043  1022  1046 W libprocessgroup: failed to open /acct/uid_10125/pid_3627/cgroup.procs: No such file or directory
,03-17 12:55:54.093  3758  3837 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 12:55:54.093  3758  3837 I GFX raster: took 0.612240ms for 96*96 texture 0
03-17 12:55:54.093  3758  3837 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8848cf0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8848d98 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 12:55:54.093  4267  4315 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-17 12:55:54.093  4267  4315 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-17 12:55:54.103  3758  3837 I AMMetaDataParserService: Icon data: ResourceStarred message2131362389com.android.email.intent.messageviewfragment.favorite2130837577
,03-17 12:55:54.113  1022  1035 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:55:54.113  1022  1035 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:54.113  1022  1035 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:55:54.113  1022  1035 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:55:54.133  4322  4322 E Zygote  : MountEmulatedStorage(),
03-17 12:55:54.133  4322  4322 E Zygote  : v2
03-17 12:55:54.133  4322  4322 I libpersona: KNOX_SDCARD checking this for 10033
03-17 12:55:54.133  4322  4322 I libpersona: KNOX_SDCARD not a persona
,03-17 12:55:54.133  4322  4322 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-17 12:55:54.133  1022  1035 I ActivityManager: Start proc com.sec.android.app.sns3 for broadcast com.sec.android.app.sns3/.SnsBroadcastReceiver: pid=4322 uid=10033 gids={50033, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,03-17 12:55:54.133  4322  4322 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-17 12:55:54.133  1022  1035 I ActivityManager: Killing 3645:com.fmm.ds/1000 (adj 15): empty #31
,03-17 12:55:54.133  4322  4322 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
03-17 12:55:54.133  1022  1047 I ActivityManager: Waited long enough for: ServiceRecord{1028a931 u0 com.samsung.hs20settings/.WifiHs20UtilityService}
,03-17 12:55:54.153  4322  4322 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:55:54.153  4322  4322 D ActivityThread: Added TimaKeyStore provider
,03-17 12:55:54.163  4267  4315 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,03-17 12:55:54.213  4267  4315 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,03-17 12:55:54.213  4267  4315 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@18bde41e: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
03-17 12:55:54.213  4267  4315 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,03-17 12:55:54.253  1022  1046 W libprocessgroup: failed to open /acct/uid_1000/pid_3645/cgroup.procs: No such file or directory
,03-17 12:55:54.353  3758  3837 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 12:55:54.353  3758  3837 I GFX raster: took 0.680365ms for 96*96 texture 0
,03-17 12:55:54.353  3758  3837 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8848cf0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb866dc38 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 12:55:54.363  3758  3837 I AMMetaDataParserService: Icon data: ResourceUnstarred message2131362390com.android.email.intent.messageviewfragment.favorite2130837577
,03-17 12:55:54.373  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.MailboxSettings
,03-17 12:55:54.373  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.messageview.SelectGroup
03-17 12:55:54.373  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.messageview.SavedEmail
03-17 12:55:54.373  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.messageview.MessageFileView
03-17 12:55:54.373  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsHtmlSignature
03-17 12:55:54.373  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.MessageCompose
03-17 12:55:54.373  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:54.373  3758  3837 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
03-17 12:55:54.373  3758  3837 I AMMetaDataParserService: getResourcePackageName:android.app.spellscroll
03-17 12:55:54.373  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.SelectMapActivity
03-17 12:55:54.373  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.CustomizeDate
03-17 12:55:54.373  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.QuickReplyActivity
03-17 12:55:54.373  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.SettingsReservationActivity
03-17 12:55:54.373  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.AttachmentChooserActivity
03-17 12:55:54.373  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.DebugActivity
03-17 12:55:54.373  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupBasicsChoiceProviderForKOR
03-17 12:55:54.373  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSoundNotiSetup
03-17 12:55:54.373  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSoundNotiGeneralPreference
03-17 12:55:54.373  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.SearchActivity
03-17 12:55:54.373  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:54.373  3758  3837 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
03-17 12:55:54.373  3758  3837 I AMMetaDataParserService: getResourcePackageName:android.app.default_searchable
03-17 12:55:54.373  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.MessageComposeDrawingModePopup
03-17 12:55:54.373  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.utils.airjump.EmailAirScrollTryActivity
03-17 12:55:54.373  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.SmartStayActivity
,03-17 12:55:54.383  4322  4322 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
03-17 12:55:54.383  4322  4322 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 12:55:54.383  4322  4322 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,03-17 12:55:54.403  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.rcs.RcsNewFeatureActivity
03-17 12:55:54.403  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.RoamingGuardPopupActivity
03-17 12:55:54.403  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.AutoRetrievePreferenceActivity
03-17 12:55:54.403  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.AutoRetrieveTabActivity
03-17 12:55:54.403  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ConversationComposer
03-17 12:55:54.403  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:54.403  3758  3837 I AMMetaDataParserService: getResourcePackageName:android.app.spellscroll
03-17 12:55:54.403  3758  3837 I AMMetaDataParserService: getResourcePackageName:android.app.default_searchable
03-17 12:55:54.403  3758  3837 I AMMetaDataParserService: getResourcePackageName:assistant
03-17 12:55:54.403  3758  3837 I AMMetaDataParserService: Resource data:2131099648
,03-17 12:55:54.403  3758  3837 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,03-17 12:55:54.403  3758  3837 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-17 12:55:54.403  3758  3837 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,03-17 12:55:54.413  3758  3837 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 12:55:54.413  3758  3837 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,03-17 12:55:54.413  3758  3837 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,03-17 12:55:54.413  3758  3837 I AMMetaDataParserService: getResourceName:com.android.mms:xml/assistant_messaging
03-17 12:55:54.413  3758  3837 I AMMetaDataParserService: getResourceTypeNamexml
,03-17 12:55:54.413  3758  3837 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 12:55:54.413  3758  3837 I GFX raster: took 1.278073ms for 96*96 texture 0
03-17 12:55:54.413  3758  3837 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8b9bda0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8b9bdd8 counterpartCT=4 counterpartW=96 counterparth=96
03-17 12:55:54.413  4322  4322 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,03-17 12:55:54.413  4322  4322 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-17 12:55:54.413  4322  4322 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-17 12:55:54.423  3758  3837 I AMMetaDataParserService: Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,03-17 12:55:54.433  3758  3837 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 12:55:54.443  4322  4322 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,03-17 12:55:54.443  3758  3837 I GFX construct_block_size_descriptor_2d second part: took 2.460104ms for 0*0 texture 0
,03-17 12:55:54.443  4322  4322 W ResourcesManager: Asset path '/system/framework/libvtmanagerjar.jar' does not exist or contains no resources.
03-17 12:55:54.443  4322  4322 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,03-17 12:55:54.453  3758  3837 I GFX generate_partition_tables: took 8.874218ms for 0*0 texture 0
,03-17 12:55:54.453  3758  3837 I GFX raster: took 12.271614ms for 96*96 texture 0
03-17 12:55:54.453  3758  3837 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb869abf0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb8697078 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 12:55:54.463  3758  3837 I AMMetaDataParserService: Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,03-17 12:55:54.473  3758  3837 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 12:55:54.473  3758  3837 I GFX raster: took 0.618854ms for 96*96 texture 0
03-17 12:55:54.473  3758  3837 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb884a4a0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb8679740 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 12:55:54.473  3758  3837 I AMMetaDataParserService: Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,03-17 12:55:54.543  1191  1191 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-17 12:55:54.543  1191  1191 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-17 12:55:54.543  1191  1191 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 12:55:54.553  1191  1191 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 12:55:54.553  1191  1191 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 12:55:54.553  1191  1191 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 12:55:54.563  3758  3837 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 12:55:54.563  3758  3837 I GFX raster: took 0.645990ms for 96*96 texture 0
03-17 12:55:54.563  3758  3837 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8670738 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8652670 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 12:55:54.573  3758  3837 I AMMetaDataParserService: Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,03-17 12:55:54.583  3758  3837 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 12:55:54.583  3758  3837 I GFX raster: took 0.648333ms for 96*96 texture 0
03-17 12:55:54.583  3758  3837 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb865eb48 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb86796b8 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 12:55:54.583  3758  3837 I AMMetaDataParserService: Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,03-17 12:55:54.613  3758  3837 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 12:55:54.613  3758  3837 I GFX raster: took 0.738854ms for 96*96 texture 0
03-17 12:55:54.613  3758  3837 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb83d72b8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8678140 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 12:55:54.623  3758  3837 I AMMetaDataParserService: Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,03-17 12:55:54.623  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ComposeMessageActivityNoLockScreen
03-17 12:55:54.623  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ComposeMessageMms
03-17 12:55:54.623  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:54.623  3758  3837 I AMMetaDataParserService: getResourcePackageName:assistant
03-17 12:55:54.623  3758  3837 I AMMetaDataParserService: Resource data:2131099648
,03-17 12:55:54.623  3758  3837 I AMMetaDataParserService: getResourceName:com.android.mms:xml/assistant_messaging
03-17 12:55:54.623  3758  3837 I AMMetaDataParserService: getResourceTypeNamexml
,03-17 12:55:54.623  3758  3837 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
03-17 12:55:54.633  3758  3837 I GFX raster: took 0.770314ms for 96*96 texture 0
03-17 12:55:54.633  3758  3837 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8b9bda0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb868d128 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 12:55:54.643  3758  3837 I AMMetaDataParserService: Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,03-17 12:55:54.643  4341  4341 I dex2oat : ----------------------------------------------------
03-17 12:55:54.643  4341  4341 I dex2oat : <SS>: S T A R T I N G . . .
03-17 12:55:54.643  4341  4341 I dex2oat : <SS>: Zip is absent. Canceled.
,03-17 12:55:54.653  4341  4341 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --compiler-filter=interpret-only --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads1021118991.jar --oat-fd=26 --art-fd=-1 --oat-location=/data/data/com.google.android.youtube/cache/ads1021118991.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,03-17 12:55:54.663  1022  1234 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 12:55:54.673  1022  1234 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:55:54.673  1022  1234 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:55:54.673  1022  1234 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
03-17 12:55:54.673  3758  3837 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 12:55:54.673  3758  3837 I GFX raster: took 0.883750ms for 96*96 texture 0
03-17 12:55:54.673  3758  3837 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb869abf0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb8319198 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 12:55:54.683  1022  1047 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:54.683  1022  1047 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:54.683  1022  1047 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:54.683  1022  1047 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:55:54.683  3758  3837 I AMMetaDataParserService: Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,03-17 12:55:54.693  4357  4357 E Zygote  : MountEmulatedStorage()
,03-17 12:55:54.693  4357  4357 E Zygote  : v2
03-17 12:55:54.693  4357  4357 I libpersona: KNOX_SDCARD checking this for 10012
03-17 12:55:54.693  4357  4357 I libpersona: KNOX_SDCARD not a persona
,03-17 12:55:54.693  4357  4357 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 12:55:54.693  4357  4357 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 12:55:54.693  1022  1047 I ActivityManager: Start proc com.google.android.gms:car for service com.google.android.gms/.car.InCallServiceImpl: pid=4357 uid=10012 gids={50012, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,03-17 12:55:54.693  4357  4357 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-17 12:55:54.703  3758  3837 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96,
03-17 12:55:54.703  3758  3837 I GFX raster: took 0.663021ms for 96*96 texture 0
03-17 12:55:54.703  3758  3837 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb884a4a0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb884a530 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 12:55:54.713  3164  3206 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 6 sec
03-17 12:55:54.713  4357  4357 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 12:55:54.713  4357  4357 D ActivityThread: Added TimaKeyStore provider
,03-17 12:55:54.713  3758  3837 I AMMetaDataParserService: Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,03-17 12:55:54.723  4267  4267 E YouTube MDX: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,03-17 12:55:54.743   310   310 I art     : Explicit concurrent mark sweep GC freed 8691(370KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 632us total 45.190ms
,03-17 12:55:54.753  4357  4357 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-17 12:55:54.753  4357  4357 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-17 12:55:54.763   310   310 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 624us total 16.961ms
,03-17 12:55:54.773  4341  4341 I dex2oat : dex2oat took 117.005ms (threads: 4)
,03-17 12:55:54.783   310   310 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 635us total 17.436ms
,03-17 12:55:54.783  4322  4322 I Process : Sending signal. PID: 4322 SIG: 9
,03-17 12:55:54.783  3758  3837 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 12:55:54.783  3758  3837 I GFX raster: took 0.634844ms for 96*96 texture 0
03-17 12:55:54.783  3758  3837 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8670738 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8672db0 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 12:55:54.793  3758  3837 I AMMetaDataParserService: Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,03-17 12:55:54.803  3758  3837 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 12:55:54.803  3758  3837 I GFX raster: took 0.637031ms for 96*96 texture 0
03-17 12:55:54.803  3758  3837 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb865eb48 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8319198 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 12:55:54.803  3758  3837 I AMMetaDataParserService: Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,03-17 12:55:54.823  1022  1534 I ActivityManager: Process com.sec.android.app.sns3 (pid 4322)(adj 0) has died(44,1121)
,03-17 12:55:54.823  4357  4357 I MultiDex: VM with version 2.1.0 has multidex support
03-17 12:55:54.823  1022  1518 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 12:55:54.823  4357  4357 I MultiDex: install
03-17 12:55:54.823  4357  4357 I MultiDex: VM has multidex support, MultiDex support library is disabled.
03-17 12:55:54.823  1022  1518 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:55:54.823  1022  1518 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:55:54.823  1022  1518 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,03-17 12:55:54.823  1022  1047 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:55:54.833  1022  1047 E ActivityManager: checkUser: useridlist=null, currentuser=0,
03-17 12:55:54.833  1022  1047 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:54.833  1022  1047 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:55:54.833  3758  3837 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96,
,03-17 12:55:54.833  3758  3837 I GFX raster: took 0.725260ms for 96*96 texture 0
03-17 12:55:54.833  3758  3837 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb83d72b8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8672db0 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 12:55:54.843  3758  3837 I AMMetaDataParserService: Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524,
,03-17 12:55:54.853  1022  1047 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=4384 uid=10034 gids={50034, 9997, 3003} abi=armeabi-v7a,
,03-17 12:55:54.853  4384  4384 E Zygote  : MountEmulatedStorage(),
03-17 12:55:54.853  4384  4384 E Zygote  : v2,
03-17 12:55:54.853  4384  4384 I libpersona: KNOX_SDCARD checking this for 10034
03-17 12:55:54.853  4384  4384 I libpersona: KNOX_SDCARD not a persona,
,03-17 12:55:54.863  4384  4384 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,03-17 12:55:54.863  4384  4384 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,03-17 12:55:54.863  4384  4384 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 12:55:54.873  4357  4357 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,03-17 12:55:54.883  4384  4384 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:55:54.883  4384  4384 D ActivityThread: Added TimaKeyStore provider
,03-17 12:55:54.893   257   525 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/cache/
03-17 12:55:54.893   257   525 W Vold    : Returning OperationFailed - no handler for errno 0
,03-17 12:55:54.903  4267  4267 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
,03-17 12:55:54.923  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.TransferContentActivity
03-17 12:55:54.923  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.CbConfigPreferenceActivity
03-17 12:55:54.923  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.CbSettingTabActivity
03-17 12:55:54.923  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ComposeMessage
03-17 12:55:54.923  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:54.923  3758  3837 I AMMetaDataParserService: getResourcePackageName:assistant
03-17 12:55:54.923  3758  3837 I AMMetaDataParserService: Resource data:2131099648
,03-17 12:55:54.923  3758  3837 I AMMetaDataParserService: getResourceName:com.android.mms:xml/assistant_messaging
03-17 12:55:54.923  3758  3837 I AMMetaDataParserService: getResourceTypeNamexml
,03-17 12:55:54.923  3758  3837 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 12:55:54.923  3758  3837 I GFX raster: took 0.703593ms for 96*96 texture 0
03-17 12:55:54.923  3758  3837 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8b9bda0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb86577a0 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 12:55:54.933  3758  3837 I AMMetaDataParserService: Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,03-17 12:55:54.943  4357  4357 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,03-17 12:55:54.943  4357  4357 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@35487134: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,03-17 12:55:54.943  4357  4357 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,03-17 12:55:54.963  1022  3060 I ActivityManager: Killing 3612:com.wssnps/1000 (adj 15): empty #31
,03-17 12:55:55.003  1022  1361 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:55:55.003  1022  1361 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:55.003  1022  1361 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:55.003  1022  1361 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:55:55.013  3758  3837 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 12:55:55.013  3758  3837 I GFX raster: took 0.687397ms for 96*96 texture 0
,03-17 12:55:55.013  3758  3837 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb869abf0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb86768f8 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 12:55:55.023  4406  4406 E Zygote  : MountEmulatedStorage()
03-17 12:55:55.023  4406  4406 E Zygote  : v2
03-17 12:55:55.023  4406  4406 I libpersona: KNOX_SDCARD checking this for 1000
03-17 12:55:55.023  4406  4406 I libpersona: KNOX_SDCARD not a persona
,03-17 12:55:55.023  1022  1361 I ActivityManager: Start proc com.policydm for broadcast com.policydm/.XDMBroadcastReceiver: pid=4406 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-17 12:55:55.023  1022  1361 I ActivityManager: Killing 3662:com.samsung.android.app.accesscontrol/1000 (adj 15): empty #31
03-17 12:55:55.023  4406  4406 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 12:55:55.023  3758  3837 I AMMetaDataParserService: Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,03-17 12:55:55.023  4406  4406 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 12:55:55.023  4406  4406 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 12:55:55.053  4406  4406 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:55:55.053  4406  4406 D ActivityThread: Added TimaKeyStore provider
,03-17 12:55:55.093  1022  3060 D ActivityManager: retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.app.offline.transfer.OfflineTransferService; callingUser = 0; userId(target) = 0
,03-17 12:55:55.103  1022  3060 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:55:55.103  1022  3060 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:55:55.103  1022  3060 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,03-17 12:55:55.103  3758  3837 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 12:55:55.103  3758  3837 I GFX raster: took 0.791145ms for 96*96 texture 0
03-17 12:55:55.103  3758  3837 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb86577a0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb867a580 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 12:55:55.123  1022  1046 W libprocessgroup: failed to open /acct/uid_1000/pid_3612/cgroup.procs: No such file or directory
03-17 12:55:55.123  1022  1046 W libprocessgroup: failed to open /acct/uid_1000/pid_3662/cgroup.procs: No such file or directory
,03-17 12:55:55.123  4186  4299 I System.out: INFO:Resource not found:/Common.properties Using default values
,03-17 12:55:55.123  3758  3837 I AMMetaDataParserService: Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,03-17 12:55:55.123  4406  4406 I DBG_POLICYDM: [com.policydm.XDMApplication(554/xdmWakeLockAcquire)] 
,03-17 12:55:55.133  4406  4406 I DBG_POLICYDM: [com.policydm.XDMApplication(559/xdmWakeLockAcquire)] m_WakeLock is acquire!!
,03-17 12:55:55.133  4406  4425 I DBG_POLICYDM: [com.policydm.agent.XDMTask(163/xdmAgentTaskHandler)] XEVENT_OS_INITIALIZED
03-17 12:55:55.133  4406  4406 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(191/xdmInitExternalStorageState)] 
,03-17 12:55:55.143  4406  4406 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(390/xdmGetExternalSDCardPath)] External SD Card Path : /storage/extSdCard
,03-17 12:55:55.143  4406  4425 I DBG_POLICYDM: [com.policydm.agent.XDMAgent(156/xdmAgentSetSyncMode)] nSync = 0
,03-17 12:55:55.143  4406  4406 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(248/xdmInitExternalStorageState)] DATA_DIR_PATH [/data]
,03-17 12:55:55.153  4406  4406 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(249/xdmInitExternalStorageState)] EXTERNAL_DIR_PATH [/storage/emulated/0]
,03-17 12:55:55.153  4406  4406 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(250/xdmInitExternalStorageState)] EXTERNAL_SD_DIR_PATH [/storage/extSdCard]
,03-17 12:55:55.153  4406  4406 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(251/xdmInitExternalStorageState)] POLICY_DIR_PATH [/data/data/com.policydm/cache]
,03-17 12:55:55.153  4406  4406 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(253/xdmInitExternalStorageState)] bExternalStorageAvailable [true]
,03-17 12:55:55.153  4406  4406 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(254/xdmInitExternalStorageState)] bExternalSDStorageAvailable [false]
,03-17 12:55:55.163  4406  4425 I DBG_POLICYDM: [com.policydm.db.XDB(1531/xdbDMffs_Init)] xdbDMffs_Init
,03-17 12:55:55.163  4406  4406 I DBG_POLICYDM: [com.policydm.XDMApplication(580/xdmWakeLockRelease)] 
,03-17 12:55:55.163  4406  4406 I DBG_POLICYDM: [com.policydm.XDMApplication(585/xdmWakeLockRelease)] m_WakeLock is release!!
,03-17 12:55:55.173  4406  4406 I DBG_POLICYDM: [com.policydm.XDMApplication(179/onCreate)] DMApplication Start !
,03-17 12:55:55.173  4406  4406 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(53/onReceive)] android.intent.action.BOOT_COMPLETED
,03-17 12:55:55.173  4406  4406 I DBG_POLICYDM: [com.policydm.db.XDB(2211/xdbIsAlreadyAgree)] bAgree : true
,03-17 12:55:55.183  1022  1515 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:55:55.183  1022  1515 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:55.183  1022  1515 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:55.183  1022  1515 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:55:55.193  4430  4430 E Zygote  : MountEmulatedStorage()
03-17 12:55:55.193  4430  4430 E Zygote  : v2
03-17 12:55:55.193  4430  4430 I libpersona: KNOX_SDCARD checking this for 10041
03-17 12:55:55.193  4430  4430 I libpersona: KNOX_SDCARD not a persona
,03-17 12:55:55.193  4430  4430 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 12:55:55.203  1022  1515 I ActivityManager: Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.broadcastreceiver.StdBroadcastReceiver: pid=4430 uid=10041 gids={50041, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-17 12:55:55.203  1022  1515 I ActivityManager: Killing 3682:com.samsung.android.app.FileShareServer/u0a69 (adj 15): empty #31
03-17 12:55:55.203  4300  4316 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-17 12:55:55.203  4300  4316 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-17 12:55:55.203  4300  4316 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-17 12:55:55.203  4430  4430 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,03-17 12:55:55.213  4430  4430 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL,
,03-17 12:55:55.213  3758  3837 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 12:55:55.213  3758  3837 I GFX raster: took 0.845313ms for 96*96 texture 0
03-17 12:55:55.223  3758  3837 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb83d72b8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb86796b8 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 12:55:55.223  3758  3837 I AMMetaDataParserService: Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,03-17 12:55:55.233  4430  4430 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:55:55.233  4430  4430 D ActivityThread: Added TimaKeyStore provider
,03-17 12:55:55.263  4406  4425 I DBG_POLICYDM: [com.policydm.agent.XDMTask(171/xdmAgentTaskHandler)] XEVENT_DM_INIT
,03-17 12:55:55.263  4406  4425 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,03-17 12:55:55.283  4406  4425 I DBG_POLICYDM: [com.policydm.XDMApplication(619/xdmGetNotibarState)] get NotibarState : 7
,03-17 12:55:55.283  4406  4425 I DBG_POLICYDM: [com.policydm.ui.XUINotificationManager(48/xuiSetIndicator)] Indicator id : 7
,03-17 12:55:55.283  4406  4425 I DBG_POLICYDM: [com.policydm.XDMApplication(611/xdmSetNotibarState)] set NotibarState : 7
,03-17 12:55:55.293  1022  1046 W libprocessgroup: failed to open /acct/uid_10069/pid_3682/cgroup.procs: No such file or directory
,03-17 12:55:55.293  4300  4316 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-17 12:55:55.303  4406  4425 I DBG_POLICYDM: [com.policydm.db.XDBAESCrypt(217/xdbGetCryptionkey)] try read dbString
,03-17 12:55:55.313  4406  4425 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(428/xdbGetFUMOStatus)] xdbGetFUMOStatus : 0
,03-17 12:55:55.323  4406  4425 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(587/xdbGetFUMOInitiatedType)] Initiated Type: 0
,03-17 12:55:55.323  4406  4425 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(72/xpollingCheckVersionInfo)] 
,03-17 12:55:55.323  4406  4426 I DBG_POLICYDM: [com.policydm.agent.XDMUITask(191/xdmUIEvent)] XUI_DM_IDLE_STATE :true
,03-17 12:55:55.323  4406  4425 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(271/xpollingCheckTimer)] 
,03-17 12:55:55.333  4406  4426 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,03-17 12:55:55.333  3758  3837 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 12:55:55.333  3758  3837 I GFX raster: took 0.780938ms for 96*96 texture 0
03-17 12:55:55.333  3758  3837 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8319198 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb884a4a0 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 12:55:55.333  3758  3837 I AMMetaDataParserService: Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,03-17 12:55:55.333  4406  4426 I DBG_POLICYDM: [com.policydm.db.XDBProfileListAdp(258/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,03-17 12:55:55.343  4406  4426 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(399/xnotiPushAdpExcuteResumeNoti)] nSessionSaveState:0
,03-17 12:55:55.343  4406  4426 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(400/xnotiPushAdpExcuteResumeNoti)] nNotiUiEvent:0
,03-17 12:55:55.343  4406  4426 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(401/xnotiPushAdpExcuteResumeNoti)] nNotiRetryCount:0
,03-17 12:55:55.353  4406  4426 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(441/xnotiPushAdpExcuteResumeNoti)] Current NOTI NOT SAVED State. EXIT.
,03-17 12:55:55.353  4406  4426 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(267/xnotiPushAdpClearSessionStatus)] 
,03-17 12:55:55.353  4406  4425 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(285/xpollingCheckTimer)] savedpollingtime : 2016/03/18/13:15:33
,03-17 12:55:55.353  4406  4425 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(286/xpollingCheckTimer)] currentTime : 2016/03/17/12:55:55
,03-17 12:55:55.353  4406  4426 I DBG_POLICYDM: [com.policydm.ui.XUIAdapter(39/xuiAdpSetUiMode)] nDmUiMode : 0
,03-17 12:55:55.353  4406  4425 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(290/xpollingCheckTimer)] Restart Timer..
,03-17 12:55:55.363  4406  4425 I DBG_POLICYDM: [com.policydm.XDMApplication(626/xdmStartAlarm)] Alarm ID: 0,
,03-17 12:55:55.363  4406  4426 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(439/xdbSetFUMOStatus)] xdbSetFUMOStatus : 0,
,03-17 12:55:55.383   257   525 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/cache/
03-17 12:55:55.383   257   525 W Vold    : Returning OperationFailed - no handler for errno 0
,03-17 12:55:55.393  4267  4267 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
,03-17 12:55:55.393   257   525 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/files/
03-17 12:55:55.393   257   525 W Vold    : Returning OperationFailed - no handler for errno 0
,03-17 12:55:55.393  4267  4267 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
,03-17 12:55:55.393   257   525 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/files/
03-17 12:55:55.393   257   525 W Vold    : Returning OperationFailed - no handler for errno 0
,03-17 12:55:55.393  4267  4267 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
,03-17 12:55:55.403  4406  4425 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(312/xPollingReportReStartAlarm)] 
,03-17 12:55:55.423  4430  4430 I SA      : [SSP] onCreated
,03-17 12:55:55.423  4267  4267 W InstanceID/Rpc: Found 10012
,03-17 12:55:55.423  3758  3837 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 12:55:55.433  3758  3837 I GFX raster: took 1.007969ms for 96*96 texture 0
03-17 12:55:55.433  3758  3837 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8678300 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb86796b8 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 12:55:55.433  3758  3837 I AMMetaDataParserService: Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,03-17 12:55:55.443  1022  1365 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 12:55:55.443  1022  1365 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:55:55.443  1022  1365 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:55:55.443  1022  1365 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,03-17 12:55:55.453  4406  4426 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(565/xdbSetFUMOInitiatedType)] Initiated Type: 0
,03-17 12:55:55.463  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ForwardMessageActivity
03-17 12:55:55.463  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:55.463  3758  3837 I AMMetaDataParserService: getResourcePackageName:assistant
03-17 12:55:55.463  3758  3837 I AMMetaDataParserService: Resource data:2131099648
,03-17 12:55:55.463  3758  3837 I AMMetaDataParserService: getResourceName:com.android.mms:xml/assistant_messaging
03-17 12:55:55.463  3758  3837 I AMMetaDataParserService: getResourceTypeNamexml
,03-17 12:55:55.463  3758  3837 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 12:55:55.463  1022  3083 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 12:55:55.463  3758  3837 I GFX raster: took 0.836927ms for 96*96 texture 0
03-17 12:55:55.463  3758  3837 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb865eb48 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb865a760 counterpartCT=4 counterpartW=96 counterparth=96
03-17 12:55:55.463  1022  3083 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4303, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,03-17 12:55:55.463  1022  3083 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,03-17 12:55:55.463  1022  1022 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-17 12:55:55.473  1022  1022 I MotionRecognitionService: Plugged
,03-17 12:55:55.473  1022  1022 I MotionRecognitionService: mGripSensorEnabled= false
,03-17 12:55:55.473  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-17 12:55:55.473  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-17 12:55:55.473  1434  1434 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-17 12:55:55.473  1434  1434 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-17 12:55:55.493  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-17 12:55:55.493  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-17 12:55:55.493  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-17 12:55:55.493  4406  4426 I DBG_POLICYDM: [com.policydm.db.XDB(1825/xdbSetBackUpServerUrl)] 
,03-17 12:55:55.493  2710  2710 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-17 12:55:55.493  2710  2816 D HeadsetStateMachine: Disconnected process message: 10
,03-17 12:55:55.513  3758  3837 I AMMetaDataParserService: Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523,
,03-17 12:55:55.513  4430  4430 I SA      : [TPM] There is no property file,
,03-17 12:55:55.513  4430  4430 I SA      : [SCU] isHaveSA() - false
,03-17 12:55:55.513  4430  4430 I SA      : [TPM] getModelProperty : null,
03-17 12:55:55.513  4430  4430 I SA      : [TPM] getCSCProperty : null
03-17 12:55:55.513  4430  4430 I SA      : [DM] FLOATING AMOLED FEATURE: true
03-17 12:55:55.513  4430  4430 I SA      : [DM] PRODUCT AMOLED FEATURE: false
03-17 12:55:55.513  4430  4430 I SA      : [DM] TFT FEATURE: false,
,03-17 12:55:55.523  4430  4430 I SA      : [SBR] StdBroadcastReceiver received Intent of  action_BOOT_COMPLETED extra.user_handle.:0,
03-17 12:55:55.523  4430  4430 I SA      : [DM] init START
,03-17 12:55:55.523  4430  4430 I SA      : [DM] This device is not a Vodafone,
,03-17 12:55:55.533  4430  4430 W ResourceType: Failure getting entry for 0x7f060010 (t=5 e=16) (error -75),
03-17 12:55:55.533  4430  4430 W ResourceType: Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
03-17 12:55:55.533  4430  4430 W ResourceType: Failure getting entry for 0x7f060009 (t=5 e=9) (error -75),
03-17 12:55:55.533  4430  4430 W ResourceType: Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
,03-17 12:55:55.533  4430  4430 W ResourceType: Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
03-17 12:55:55.533  4430  4430 W ResourceType: Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
03-17 12:55:55.533  4430  4430 W ResourceType: Failure getting entry for 0x7f060014 (t=5 e=20) (error -75),
,03-17 12:55:55.533  4430  4430 W ResourceType: No package identifier when getting value for resource number 0x00000000,
,03-17 12:55:55.533  4430  4430 W ResourceType: Failure getting entry for 0x7f060027 (t=5 e=39) (error -75),
03-17 12:55:55.533  4430  4430 W ResourceType: Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
,03-17 12:55:55.533  4430  4430 W ResourceType: Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
03-17 12:55:55.533  4430  4430 W ResourceType: Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
,03-17 12:55:55.533  4430  4430 W ResourceType: Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
03-17 12:55:55.533  4430  4430 W ResourceType: Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
,03-17 12:55:55.533  4430  4430 W ResourceType: Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
03-17 12:55:55.543  4430  4430 W ResourceType: Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
,03-17 12:55:55.543  4430  4430 W ResourceType: Failure getting entry for 0x7f06002f (t=5 e=47) (error -75),
03-17 12:55:55.543   257   525 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/cache/
03-17 12:55:55.543  4430  4430 W ResourceType: Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
,03-17 12:55:55.543   257   525 W Vold    : Returning OperationFailed - no handler for errno 0
03-17 12:55:55.543  4430  4430 W ResourceType: Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
03-17 12:55:55.543  4430  4430 W ResourceType: Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
03-17 12:55:55.543  4430  4430 W ResourceType: Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
03-17 12:55:55.543  4430  4430 W ResourceType: Failure getting entry for 0x7f06000b (t=5 e=11) (error -75),
03-17 12:55:55.543  4430  4430 W ResourceType: Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
03-17 12:55:55.543  4430  4430 W ResourceType: Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
03-17 12:55:55.543  4430  4430 W ResourceType: Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
,03-17 12:55:55.543  4267  4267 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
,03-17 12:55:55.543  4406  4425 I DBG_POLICYDM: [com.policydm.XDMApplication(626/xdmStartAlarm)] Alarm ID: 1
,03-17 12:55:55.553  4430  4430 I SA      : [SCU] isHaveSA() - false
03-17 12:55:55.553  4430  4430 I SA      : support phone number id : false
03-17 12:55:55.553  4430  4430 I SA      : [DM] Supports Ref Jpn : true
,03-17 12:55:55.553  4430  4430 I SA      : [DM] init END
,03-17 12:55:55.553  4406  4425 I DBG_POLICYDM: [com.policydm.agent.XDMTask(203/xdmAgentTaskHandler)] XEVENT_DM_INIT : Initialized
,03-17 12:55:55.553  4430  4430 I SA      : [OR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOE6 PSS = 4.978878039476607  ]
03-17 12:55:55.553  4430  4430 I SA      : [OR] onReceive Intent=[ action_BOOT_COMPLETED extra.user_handle.:0 ]
,03-17 12:55:55.563  3758  3837 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 12:55:55.563  3758  3837 I GFX raster: took 0.964739ms for 96*96 texture 0
,03-17 12:55:55.563  1022  1515 D ActivityManager: retrieveServiceLocked(): component = com.osp.app.signin/com.osp.app.signin.BootDbCheck; callingUser = 0; userId(target) = 0
03-17 12:55:55.563  3758  3837 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb869abf0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb884a4a0 counterpartCT=4 counterpartW=96 counterparth=96
03-17 12:55:55.563  1022  1515 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:55:55.563  1022  1515 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
03-17 12:55:55.563  1022  1515 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.osp.app.signin, destAppInfo.processName = com.osp.app.signin
,03-17 12:55:55.563  4430  4430 I SA      : [OR] onReceive END
,03-17 12:55:55.573  3758  3837 I AMMetaDataParserService: Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,03-17 12:55:55.593  4430  4430 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,03-17 12:55:55.593  4430  4430 I SA      : [ODM] queryOpenData(key= GEO_IP )
,03-17 12:55:55.603  3758  3837 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 12:55:55.603  3758  3837 I GFX raster: took 0.801302ms for 96*96 texture 0
03-17 12:55:55.603  3758  3837 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb86577a0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb8675d20 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 12:55:55.603  4430  4430 I SA      : getMccForGalaxyJpn step2 GEO_IP MCC : 260
03-17 12:55:55.603  4430  4430 I SA      : [LBE] REF_JPN : true
03-17 12:55:55.603  4430  4430 I SA      : [BDC] create
,03-17 12:55:55.613  1022  1234 D ActivityManager: retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService; callingUser = 0; userId(target) = 0
,03-17 12:55:55.613  1022  1234 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:55:55.613  1022  1234 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:55:55.613  1022  1234 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,03-17 12:55:55.623  3758  3837 I AMMetaDataParserService: Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,03-17 12:55:55.623  4406  4426 I DBG_POLICYDM: [com.policydm.db.XDBProfileAdp(207/xdbSetChangedProtocol)] xdbSetChangedProtocol : false
,03-17 12:55:55.623  4430  4430 I SA      : [DBMV2] getEmailID
,03-17 12:55:55.633  4430  4430 I SA      : [DBMV2] getDataV02ForItems
,03-17 12:55:55.633  4430  4430 I SA      : [SSP] query invoked
,03-17 12:55:55.633  3758  3837 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 12:55:55.633  3758  3837 I GFX raster: took 0.642709ms for 96*96 texture 0
03-17 12:55:55.633  3758  3837 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb83d72b8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb86796b8 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 12:55:55.643  4430  4430 I SA      : [SCU] get signed id from samsung account2.0 DB.
,03-17 12:55:55.653  3758  3837 I AMMetaDataParserService: Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,03-17 12:55:55.653  4430  4430 I SA      : [SCU] get signed id from samsung account1.0 DB.
,03-17 12:55:55.653  4430  4430 I SA      : [BDC] destroy
,03-17 12:55:55.663  1022  1365 I ActivityManager: Killing 3697:com.sec.android.app.sbrowser/u0a131 (adj 15): empty #31
,03-17 12:55:55.663  4406  4426 I DBG_POLICYDM: [com.policydm.db.XDBProfileListAdp(258/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,03-17 12:55:55.663  3758  3837 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 12:55:55.663  3758  3837 I GFX raster: took 0.654167ms for 96*96 texture 0
03-17 12:55:55.663  3758  3837 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8319198 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb865de18 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 12:55:55.663  3758  3837 I AMMetaDataParserService: Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,03-17 12:55:55.673  4406  4426 I DBG_POLICYDM: [com.policydm.db.XDBNotiAdp(38/xdbNotiExistInfo)] Noti Exist : false
,03-17 12:55:55.693  1022  1034 D ActivityManager: retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.app.offline.transfer.OfflineTransferService; callingUser = 0; userId(target) = 0
,03-17 12:55:55.693  1022  1034 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:55:55.693  1022  1034 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 12:55:55.693  1022  1034 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,03-17 12:55:55.713  3758  3837 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 12:55:55.713  3758  3837 I GFX raster: took 0.743542ms for 96*96 texture 0
03-17 12:55:55.713  3758  3837 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8678300 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8675d20 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 12:55:55.713  3164  3206 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 7 sec
,03-17 12:55:55.713  3758  3837 I AMMetaDataParserService: Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,03-17 12:55:55.723  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ReplyMessageActivity
03-17 12:55:55.723  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:55.723  3758  3837 I AMMetaDataParserService: getResourcePackageName:assistant
03-17 12:55:55.723  3758  3837 I AMMetaDataParserService: Resource data:2131099648
,03-17 12:55:55.723  3758  3837 I AMMetaDataParserService: getResourceName:com.android.mms:xml/assistant_messaging
03-17 12:55:55.723  3758  3837 I AMMetaDataParserService: getResourceTypeNamexml
,03-17 12:55:55.723  3758  3837 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 12:55:55.723  3758  3837 I GFX raster: took 0.686458ms for 96*96 texture 0
03-17 12:55:55.723  3758  3837 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb865eb48 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb86796b8 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 12:55:55.733  3758  3837 I AMMetaDataParserService: Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,03-17 12:55:55.763  4267  4477 D AndroidHttpClient: [NALSECURITY] isMmsRequest() : CoreProtocolPNames.USER_AGENT = Dalvik/2.1.0 (Linux; U; Android 5.0.2; SM-A500FU Build/LRX22G)
,03-17 12:55:55.763  4267  4477 D AndroidHttpClient: [NALSECURITY] checkMmsSendPermission() : isMmsRequest() = false method = GET
,03-17 12:55:55.763  3758  3837 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 12:55:55.763  3758  3837 I GFX raster: took 0.668385ms for 96*96 texture 0
,03-17 12:55:55.763  3758  3837 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb869abf0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb8678140 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 12:55:55.763  1022  1518 D ActivityManager: retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService; callingUser = 0; userId(target) = 0
,03-17 12:55:55.773  1022  1518 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:55:55.773  1022  1518 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:55:55.773  1022  1518 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,03-17 12:55:55.773  1022  3059 D ActivityManager: retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.app.offline.transfer.OfflineTransferService; callingUser = 0; userId(target) = 0
,03-17 12:55:55.773  1022  3059 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:55:55.773  1022  3059 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:55:55.773  1022  3059 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,03-17 12:55:55.773  4267  4477 I System.out: Thread-702(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,03-17 12:55:55.773  1022  1046 W libprocessgroup: failed to open /acct/uid_10131/pid_3697/cgroup.procs: No such file or directory
,03-17 12:55:55.773  3758  3837 I AMMetaDataParserService: Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,03-17 12:55:55.773  1022  1103 V AlarmManager: waitForAlarm result :4
,03-17 12:55:55.783  1022  1103 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService; callingUser = 0; userId(target) = 0
,03-17 12:55:55.783  1022  1482 D ActivityManager: retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.core.player.preload.PreloadVideosTransferService; callingUser = 0; userId(target) = 0
,03-17 12:55:55.783  1022  1482 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:55:55.783  1022  1482 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 12:55:55.793  1022  1482 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,03-17 12:55:55.793  4267  4477 I System.out: Thread-702(ApacheHTTPLog):isSBSettingEnabled false
03-17 12:55:55.793  4267  4477 I System.out: Thread-702(ApacheHTTPLog):isShipBuild true
03-17 12:55:55.793  4267  4477 I System.out: Thread-702(ApacheHTTPLog):SMARTBONDING_ENABLED is false
03-17 12:55:55.793  4267  4477 I System.out: Thread-702(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,03-17 12:55:55.793   279   926 D EnterpriseController: uids 10166
03-17 12:55:55.793   279   926 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
03-17 12:55:55.793   279   926 D Netd    : getNetworkForDns: using netid 502 for uid 10166
,03-17 12:55:55.803  3758  3837 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 12:55:55.803  1022  1515 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:55.803  1022  1515 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:55.803  1022  1515 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:55.803  1022  1515 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:55:55.803  3758  3837 I GFX raster: took 0.731666ms for 96*96 texture 0
03-17 12:55:55.803  3758  3837 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb86577a0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb865c788 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 12:55:55.813  3758  3837 I AMMetaDataParserService: Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,03-17 12:55:55.813  4485  4485 E Zygote  : MountEmulatedStorage()
03-17 12:55:55.813  4485  4485 I libpersona: KNOX_SDCARD checking this for 10101
03-17 12:55:55.813  4485  4485 E Zygote  : v2
03-17 12:55:55.813  4485  4485 I libpersona: KNOX_SDCARD not a persona
03-17 12:55:55.823  1022  1515 I ActivityManager: Start proc com.google.android.gm for broadcast com.google.android.gm/.GoogleMailDeviceStartupReceiver: pid=4485 uid=10101 gids={50101, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-17 12:55:55.823  4485  4485 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 12:55:55.823  4485  4485 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 12:55:55.823  4485  4485 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-17 12:55:55.843  3758  3837 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 12:55:55.843  3758  3837 I GFX raster: took 0.664375ms for 96*96 texture 0
,03-17 12:55:55.843  3758  3837 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb83d72b8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb865de18 counterpartCT=4 counterpartW=96 counterparth=96
03-17 12:55:55.843  4485  4485 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:55:55.843  4485  4485 D ActivityThread: Added TimaKeyStore provider
,03-17 12:55:55.853  3758  3837 I AMMetaDataParserService: Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,03-17 12:55:55.853  3758  3837 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 12:55:55.853  3758  3837 I GFX raster: took 0.645886ms for 96*96 texture 0
03-17 12:55:55.863  3758  3837 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8319198 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb82c8c48 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 12:55:55.863  3758  3837 I AMMetaDataParserService: Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,03-17 12:55:55.873  3758  3837 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 12:55:55.873  3758  3837 I GFX raster: took 0.731719ms for 96*96 texture 0
03-17 12:55:55.873  3758  3837 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8678300 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8675d20 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 12:55:55.883  3758  3837 I AMMetaDataParserService: Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,03-17 12:55:55.893  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ConversationList
03-17 12:55:55.893  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:55.893  3758  3837 I AMMetaDataParserService: getResourcePackageName:assistant
03-17 12:55:55.893  3758  3837 I AMMetaDataParserService: Resource data:2131099648
,03-17 12:55:55.893  3758  3837 I AMMetaDataParserService: getResourceName:com.android.mms:xml/assistant_messaging
03-17 12:55:55.893  3758  3837 I AMMetaDataParserService: getResourceTypeNamexml
,03-17 12:55:55.893  3758  3837 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 12:55:55.893  3758  3837 I GFX raster: took 0.690417ms for 96*96 texture 0
,03-17 12:55:55.893  3758  3837 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb865eb48 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8696ec8 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 12:55:55.903  3758  3837 I AMMetaDataParserService: Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,03-17 12:55:55.913  3758  3837 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 12:55:55.913  3758  3837 I GFX raster: took 0.653334ms for 96*96 texture 0
,03-17 12:55:55.913  3758  3837 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb869abf0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb86796b8 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 12:55:55.923  3758  3837 I AMMetaDataParserService: Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,03-17 12:55:55.923  3758  3837 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 12:55:55.923  3758  3837 I GFX raster: took 0.634166ms for 96*96 texture 0
,03-17 12:55:55.923  3758  3837 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb86577a0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb865de18 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 12:55:55.933   289   289 E SMD     : DCD OFF,
03-17 12:55:55.933  3758  3837 I AMMetaDataParserService: Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,03-17 12:55:55.943  3758  3837 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 12:55:55.943  3758  3837 I GFX raster: took 0.641719ms for 96*96 texture 0
03-17 12:55:55.943  3758  3837 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb83d72b8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb82c8c48 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 12:55:55.953  3758  3837 I AMMetaDataParserService: Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,03-17 12:55:55.963  3758  3837 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 12:55:55.963  3758  3837 I GFX raster: took 0.643697ms for 96*96 texture 0
,03-17 12:55:55.963  3758  3837 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8319198 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8675d20 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 12:55:55.963  3758  3837 I AMMetaDataParserService: Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,03-17 12:55:55.973  3758  3837 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 12:55:55.973  3758  3837 I GFX raster: took 0.732187ms for 96*96 texture 0
,03-17 12:55:55.983  3758  3837 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8678300 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8696ec8 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 12:55:55.983  3758  3837 I AMMetaDataParserService: Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,03-17 12:55:55.993  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.WarnOfStorageLimitsActivity
,03-17 12:55:55.993  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.SlideshowActivity
03-17 12:55:55.993  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.MmsSinglePageActivity
,03-17 12:55:55.993  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ClassZeroActivity
03-17 12:55:55.993  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.RetryActivity
,03-17 12:55:55.993  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.MessagingPreferenceActivity
03-17 12:55:55.993  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.EntrancePrefActivity
03-17 12:55:55.993  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.DisplaySettings
,03-17 12:55:55.993  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.CMASSettings
03-17 12:55:55.993  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.TextMessagesSettings
,03-17 12:55:55.993  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.MultimediamessagesSettings
03-17 12:55:55.993  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.rcs.settings.RcsMessagesSettings
03-17 12:55:55.993  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.DeleteoldMessagesSettings
,03-17 12:55:55.993  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.PushMessagesSettings
03-17 12:55:55.993  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.NotificationSettings
03-17 12:55:55.993  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.NotificationSettingsDS
03-17 12:55:55.993  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.SignatureSettings
03-17 12:55:55.993  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.SpamSettings
03-17 12:55:55.993  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.SafemodeSettings
03-17 12:55:55.993  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.DelaySendingSettings
03-17 12:55:55.993  1022  1365 I art     : Explicit concurrent mark sweep GC freed 27175(1604KB) AllocSpace objects, 6(96KB) LOS objects, 33% free, 30MB/45MB, paused 2.771ms total 163.628ms
03-17 12:55:55.993  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.smishing.PackageAuthorityActivity
03-17 12:55:55.993  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.smishing.PackageAuthorityDialog
03-17 12:55:55.993  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.MessageSmscActivityDS
03-17 12:55:55.993  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.SignatureEditActivity
03-17 12:55:55.993  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.CallbackNumberSettings
03-17 12:55:55.993  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.CallbackNumberEditActivity
03-17 12:55:55.993  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.BackgroundStyle
03-17 12:55:55.993  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.BubbleStyle
03-17 12:55:55.993  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.PushMessageDialog
03-17 12:55:55.993  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.saverestore.SaveThreadActivity
03-17 12:55:55.993  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.saverestore.SavedMsgsList
03-17 12:55:55.993  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.saverestore.RestorePreviewActivity
03-17 12:55:55.993  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.saverestore.ConversationListRestore
03-17 12:55:55.993  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ManageSimMessages
03-17 12:55:55.993  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.MmsRetryActivity
03-17 12:55:55.993  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ConfirmRateLimitActivity
03-17 12:55:55.993  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.SearchActivity
03-17 12:55:55.993  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:55.993  3758  3837 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
03-17 12:55:55.993  3758  3837 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleInten,t:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
03-17 12:55:55.993  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.SmsViewerActivity
03-17 12:55:55.993  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.MmsNotificationViewerActivity
03-17 12:55:55.993  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.DrmContentsActivity
03-17 12:55:55.993  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.CMASPreferenceActivity
03-17 12:55:55.993  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.CMASDialog
03-17 12:55:55.993  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.CMASDialog_single_top
03-17 12:55:55.993  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.PDPResetDialog
03-17 12:55:55.993  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.CMASUserPromptDialog
03-17 12:55:55.993  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.LockedMessageManager
03-17 12:55:55.993  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.SpamMessageManager
03-17 12:55:55.993  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ReservationMessageManager
03-17 12:55:55.993  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.DraftMessageManager
03-17 12:55:55.993  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.SafeMessageManager
03-17 12:55:55.993  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.RecipientListActivity
03-17 12:55:55.993  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.GroupMessagingRecipientListActivity
03-17 12:55:55.993  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.SelectMapActivity
03-17 12:55:55.993  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.location.LocationMapActivity
03-17 12:55:55.993  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:55.993  3758  3837 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
03-17 12:55:55.993  3758  3837 I AMMetaDataParserService: getResourcePackageName:android.app.default_searchable
03-17 12:55:55.993  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.location.FavoritePlacesList
03-17 12:55:55.993  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.location.RecentPlacesList
03-17 12:55:55.993  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.BoxListViewActivity
03-17 12:55:55.993  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:55.993  3758  3837 I AMMetaDataParserService: getResourcePackageName:android.app.default_searchable
03-17 12:55:55.993  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.provisioning.MmsProvisionActivity
03-17 12:55:55.993  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ManageSDMessages
03-17 12:55:55.993  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.spam.SetupSpamNumberList
03-17 12:55:55.993  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.spam.SetupSpamKeywordList
03-17 12:55:55.993  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.spam.SetupSpamNumberWriteForm
03-17 12:55:55.993  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.spam.SetupSpamKeywordWriteForm
03-17 12:55:55.993  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.SettingsReservationActivity
03-17 12:55:55.993  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.SettingsTransmitMessageActivity
03-17 12:55:55.993  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.MessageDatabaseBackupActivity
03-17 12:55:55.993  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.widget.NoticeThreadContactSelector
03-17 12:55:55.993  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.widget.NoticeEditActivity
03-17 12:55:55.993  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.widget.NoticeDeleteActivity
03-17 12:55:55.993  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.export.MmsPartExportDialogActivity
03-17 12:55:55.993  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.export.MmsPartExportDialogActivityAlien
03-17 12:55:55.993  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.DirectCallTutorialActivity
03-17 12:55:55.993  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.FakeCallActivity
03-17 12:55:55.993  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.MmsPartExportActivity
03-17 12:55:55.993  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.template.TextTemplateListActivity
03-17 12:55:55.993  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.template.TextTemplateEditActivity
03-17 12:55:55.993  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.help.AirViewMainActivity
03-17 12:55:55.993  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.help.AirButtonMainActivity
03-17 12:55:55.993  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.widget.WidgetPreferenceActivity
03-17 12:55:55.993  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.cover.MissedMsgActivity
03-17 12:55:55.993  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.oem.AutoSendingTestActivity
03-17 12:55:55.993  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.prioritysender.AddGlanceListActivity
03-17 12:55:55.993  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.prioritysender.AddThreadListActivity
03-17 12:55:55.993  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.CheckDefaultSmsAppsActivity
03-17 12:55:55.993  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.accessory.ReadReportActivity
03-17 12:55:55.993  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.FileHistoryListActivity
03-17 12:55:55.993  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.FreeMessageSettings
03-17 12:55:55.993  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.prioritysenderpanel.CocktailPrioritySenderSettingActivity
03-17 12:55:56.013  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.GalleryOpaqueActivity
03-17 12:55:56.013  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.013  3758  3837 I AMMetaDataParserService: getResourcePackageName:assistant
03-17 12:55:56.013  3758  3837 I AMMetaDataParserService: Resource data:2131165197
03-17 12:55:56.013  1022  1034 D ActivityManager: retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.core.player.preload.PreloadVideosTransferService; callingUser = 0; userId(target) = 0
03-17 12:55:56.023  1022  1034 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:55:56.023  1022  1034 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:55:56.023  1022  1034 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
03-17 12:55:56.023  3758  3837 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-17 12:55:56.023  3758  3837 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-17 12:55:56.023  3758  3837 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
03-17 12:55:56.023  3758  3837 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 12:55:56.023  3758  3837 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
03-17 12:55:56.023  3758  3837 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
03-17 12:55:56.023  3758  3837 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
03-17 12:55:56.023  3758  3837 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,03-17 12:55:56.033  1914  4483 I iu.UploadsManager: End new media; added: 0, uploading: 0, time: 246 ms
03-17 12:55:56.053  1022  1534 I ActivityManager: Killing 3337:com.sec.android.fotaclient/u0a9 (adj 15): empty #31
,03-17 12:55:56.083  3758  3837 I AMMetaDataParserService: getResourceName:com.sec.android.gallery3d:xml/assistant
03-17 12:55:56.083  3758  3837 I AMMetaDataParserService: getResourceTypeNamexml
,03-17 12:55:56.103  3758  3837 I AMMetaDataParserService: Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,03-17 12:55:56.133  3758  3837 I AMMetaDataParserService: Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
,03-17 12:55:56.163  1022  1046 W libprocessgroup: failed to open /acct/uid_10009/pid_3337/cgroup.procs: No such file or directory
,03-17 12:55:56.173  3758  3837 I AMMetaDataParserService: Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,03-17 12:55:56.183  3758  3837 I AMMetaDataParserService: Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,03-17 12:55:56.193  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.GalleryActivity
03-17 12:55:56.193  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.193  3758  3837 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
03-17 12:55:56.193  3758  3837 I AMMetaDataParserService: getResourcePackageName:assistant
03-17 12:55:56.193  3758  3837 I AMMetaDataParserService: Resource data:2131165197
,03-17 12:55:56.203  3758  3837 I AMMetaDataParserService: getResourceName:com.sec.android.gallery3d:xml/assistant
03-17 12:55:56.203  3758  3837 I AMMetaDataParserService: getResourceTypeNamexml
,03-17 12:55:56.203  3758  3837 I AMMetaDataParserService: Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,03-17 12:55:56.223  3758  3837 I AMMetaDataParserService: Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
,03-17 12:55:56.233  3758  3837 I AMMetaDataParserService: Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,03-17 12:55:56.233  4267  4477 I System.out: Thread-702 calls detatch()
,03-17 12:55:56.253  1022  1482 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
03-17 12:55:56.253  3758  3837 I AMMetaDataParserService: Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,03-17 12:55:56.253  1022  1482 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,03-17 12:55:56.253  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.cooliris.media.Gallery
03-17 12:55:56.253  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.Gallery
03-17 12:55:56.253  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.253  3758  3837 I AMMetaDataParserService: getResourcePackageName:assistant
03-17 12:55:56.253  3758  3837 I AMMetaDataParserService: Resource data:2131165197
,03-17 12:55:56.253  3758  3837 I AMMetaDataParserService: getResourceName:com.sec.android.gallery3d:xml/assistant
03-17 12:55:56.253  3758  3837 I AMMetaDataParserService: getResourceTypeNamexml
,03-17 12:55:56.263  3758  3837 I AMMetaDataParserService: Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,03-17 12:55:56.273  3758  3837 I AMMetaDataParserService: Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
,03-17 12:55:56.293  3758  3837 I AMMetaDataParserService: Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,03-17 12:55:56.323  3758  3837 I AMMetaDataParserService: Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,03-17 12:55:56.333  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.UsbDeviceActivity
,03-17 12:55:56.333  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.333  3758  3837 I AMMetaDataParserService: getResourcePackageName:android.hardware.usb.action.USB_DEVICE_ATTACHED
,03-17 12:55:56.333  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.Wallpaper
03-17 12:55:56.333  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-17 12:55:56.333  3758  3837 I AMMetaDataParserService: getResourcePackageName:android.wallpaper.preview
03-17 12:55:56.333  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.LockScreen
03-17 12:55:56.333  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-17 12:55:56.333  3758  3837 I AMMetaDataParserService: getResourcePackageName:android.wallpaper.preview
03-17 12:55:56.333  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.BothScreen
03-17 12:55:56.333  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.333  3758  3837 I AMMetaDataParserService: getResourcePackageName:android.wallpaper.preview
03-17 12:55:56.333  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.CropImage
03-17 12:55:56.333  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.ContextualTagSetting
03-17 12:55:56.333  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.ContextualTagWeatherSetting
03-17 12:55:56.333  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.samsung.gallery.view.gallerysearch.DeleteHistoryForGallerySearchActivity
03-17 12:55:56.333  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.samsung.gallery.view.usertag.AddUserTagListActivity
03-17 12:55:56.333  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.samsung.gallery.view.detailview.moreinfo.MoreInfoLocationEditActivity
03-17 12:55:56.333  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.333  3758  3837 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
03-17 12:55:56.333  3758  3837 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
03-17 12:55:56.333  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.settings.GallerySettings
03-17 12:55:56.333  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetTypeChooser
03-17 12:55:56.333  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetClickHandler
03-17 12:55:56.333  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetConfigure
03-17 12:55:56.333  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.MagazineWidgetConfigure
03-17 12:55:56.333  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.EasyWidgetConfigure
03-17 12:55:56.333  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetPreferenceActivity
03-17 12:55:56.333  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.MagazineWidgetPreferenceActivity
03-17 12:55:56.333  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.settings.AccountSettingActivity
03-17 12:55:56.333  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.settings.FilterbySettingActivity
03-17 12:55:56.333  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.sec.gallery2d.viewstate.MapView2dPage
03-17 12:55:56.333  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.samsung.gallery.app.imagenote.ImageNote
03-17 12:55:56.333  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.samsung.gallery.app.photonote.PhotoNote
03-17 12:55:56.333  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.samsung.galler,y.controller.StartMmsSaveCmd$CallMmsSave
03-17 12:55:56.333  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.samsung.gallery.controller.GalleryChooserActivity
03-17 12:55:56.333  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.cloud.integrator.CloudIntegratorActivity
,03-17 12:55:56.333  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.camera.Camera
03-17 12:55:56.333  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.333  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.samsung.android.cocktail.subwindow.enable
03-17 12:55:56.333  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.sec.android.multiwindow.activity.STYLE
03-17 12:55:56.333  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.keyguard.layout
03-17 12:55:56.333  3758  3837 I AMMetaDataParserService: getResourcePackageName:assistant
03-17 12:55:56.333  3758  3837 I AMMetaDataParserService: Resource data:2131099648
,03-17 12:55:56.343  3758  3837 W ResourcesManager: Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
03-17 12:55:56.343  3758  3837 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-17 12:55:56.343  3758  3837 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
03-17 12:55:56.343  3758  3837 W ResourcesManager: Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
03-17 12:55:56.343  3758  3837 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,03-17 12:55:56.343  3758  3837 I AMMetaDataParserService: getResourceName:com.sec.android.app.camera:xml/assistant
03-17 12:55:56.343  3758  3837 I AMMetaDataParserService: getResourceTypeNamexml
,03-17 12:55:56.353  3758  3837 I AMMetaDataParserService: Icon data: ResourceSwitch camera2131559034android.intent.action.switchcamera2130837512
,03-17 12:55:56.363  4485  4504 I Gmail   : getAccountsCursor
,03-17 12:55:56.363  1022  1234 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,03-17 12:55:56.363  1696  1696 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 12:55:56.373  4485  4485 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,03-17 12:55:56.383  3758  3837 I AMMetaDataParserService: Icon data: ResourceGallery2131558741android.intent.action.switchgallery2130837511
,03-17 12:55:56.393  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.camera.Camcorder
03-17 12:55:56.393  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.camera.DummyActivity
03-17 12:55:56.393  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.camera.CropImage
03-17 12:55:56.393  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.shootingmodemanager.ManageShootingModeActivity
03-17 12:55:56.393  3758  3837 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
,03-17 12:55:56.413  1022  1234 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.EmailMigrationService; callingUser = 0; userId(target) = 0
,03-17 12:55:56.413  1022  1234 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:55:56.413  1022  1234 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 12:55:56.413  1022  1234 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,03-17 12:55:56.423  1022  3083 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gm/com.android.email.service.AttachmentService; callingUser = 0; userId(target) = 0
03-17 12:55:56.423  1022  3083 W ActivityManager: Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,03-17 12:55:56.433  1022  1482 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.GoogleMailSwitchService; callingUser = 0; userId(target) = 0
,03-17 12:55:56.433  1022  1482 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:55:56.433  1022  1482 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:55:56.433  1022  1482 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,03-17 12:55:56.433  1022  1515 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 12:55:56.433  1022  1515 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
03-17 12:55:56.433  4485  4513 I Gmail   : Observing account changes for notifications
,03-17 12:55:56.443  1022  1083 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 12:55:56.443  1022  1083 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,03-17 12:55:56.453  1022  3133 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.GmailIntentService; callingUser = 0; userId(target) = 0
,03-17 12:55:56.453  4485  4514 E Gmail   : Error finding the version of the Email provider.....
03-17 12:55:56.453  4485  4514 E Gmail   : android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
03-17 12:55:56.453  4485  4514 E Gmail   : 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:165)
03-17 12:55:56.453  4485  4514 E Gmail   : 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
03-17 12:55:56.453  4485  4514 E Gmail   : 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
03-17 12:55:56.453  4485  4514 E Gmail   : 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-17 12:55:56.453  4485  4514 E Gmail   : 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 12:55:56.453  4485  4514 E Gmail   : 	at android.os.Looper.loop(Looper.java:145)
03-17 12:55:56.453  4485  4514 E Gmail   : 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-17 12:55:56.453  4485  4514 W EmailMigration: We do not support migrating this version of the Email provider.
03-17 12:55:56.453  1022  3133 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:55:56.453  1022  3133 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:55:56.453  1022  3133 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,03-17 12:55:56.463  4485  4516 I Gmail   : getAccountsCursor
,03-17 12:55:56.463  1022  1234 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,03-17 12:55:56.463  1696  1696 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 12:55:56.473  1022  1482 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gm/com.android.email.service.EmailBroadcastProcessorService; callingUser = 0; userId(target) = 0
,03-17 12:55:56.473  1022  1482 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:55:56.473  1022  1482 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:55:56.473  1022  1482 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,03-17 12:55:56.473  1022  3133 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,03-17 12:55:56.483  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.GridSettings
03-17 12:55:56.483  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.483  3758  3837 I AMMetaDataParserService: getResourcePackageName:assistant
03-17 12:55:56.483  3758  3837 I AMMetaDataParserService: Resource data:2131165220
,03-17 12:55:56.483  1022  1083 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:55:56.483  1696  1696 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 12:55:56.483  1022  1083 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:56.483  1022  1083 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:56.483  1022  1083 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:55:56.483  3758  3837 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
03-17 12:55:56.483  3758  3837 I AMMetaDataParserService: getResourceName:com.android.settings:xml/assistant
03-17 12:55:56.483  3758  3837 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
03-17 12:55:56.483  3758  3837 I AMMetaDataParserService: getResourceTypeNamexml
03-17 12:55:56.483  3758  3837 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-17 12:55:56.483  3758  3837 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-17 12:55:56.483  3758  3837 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 12:55:56.483  3758  3837 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,03-17 12:55:56.493  3758  3837 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96,
03-17 12:55:56.493  3758  3837 I GFX raster: took 0.735417ms for 96*96 texture 0
03-17 12:55:56.503  4520  4520 I libpersona: KNOX_SDCARD checking this for 10092
03-17 12:55:56.493  3758  3837 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8d96660 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8d96390 counterpartCT=4 counterpartW=96 counterparth=96
03-17 12:55:56.503  4520  4520 I libpersona: KNOX_SDCARD not a persona
,03-17 12:55:56.503  4520  4520 E Zygote  : MountEmulatedStorage()
03-17 12:55:56.503  4520  4520 E Zygote  : v2
,03-17 12:55:56.503  4520  4520 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 12:55:56.503  4520  4520 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
03-17 12:55:56.503  4520  4520 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
03-17 12:55:56.503  1022  1083 I ActivityManager: Start proc com.dropbox.android for broadcast com.dropbox.android/.service.WakeupReceiver: pid=4520 uid=10092 gids={50092, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-17 12:55:56.503  3758  3837 I AMMetaDataParserService: Icon data: ResourceSearch2131363521com.android.settings.Search2130837580
,03-17 12:55:56.503  1022  3083 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
03-17 12:55:56.503  1022  3083 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,03-17 12:55:56.513  1022  1035 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
03-17 12:55:56.513  1022  1035 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,03-17 12:55:56.513  3758  3837 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 12:55:56.513  3758  3837 I GFX raster: took 0.613959ms for 96*96 texture 0
03-17 12:55:56.513  3758  3837 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8d964b0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8da8ed0 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 12:55:56.523  3758  3837 I AMMetaDataParserService: Icon data: ResourceEdit quick settings2131361852com.android.settings.Favorite2130837579
,03-17 12:55:56.523  1022  1034 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,03-17 12:55:56.533  4520  4520 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:55:56.533  4520  4520 D ActivityThread: Added TimaKeyStore provider
,03-17 12:55:56.533  4485  4485 E ActivityThread: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@aebc35 that was originally bound here
03-17 12:55:56.533  4485  4485 E ActivityThread: android.app.ServiceConnectionLeaked: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@aebc35 that was originally bound here
03-17 12:55:56.533  4485  4485 E ActivityThread: 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1144)
03-17 12:55:56.533  4485  4485 E ActivityThread: 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1038)
03-17 12:55:56.533  4485  4485 E ActivityThread: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2154)
03-17 12:55:56.533  4485  4485 E ActivityThread: 	at android.app.ContextImpl.bindService(ContextImpl.java:2137)
03-17 12:55:56.533  4485  4485 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
03-17 12:55:56.533  4485  4485 E ActivityThread: 	at com.android.emailcommon.service.ak.a(SourceFile:181)
03-17 12:55:56.533  4485  4485 E ActivityThread: 	at com.android.emailcommon.service.ak.e(SourceFile:224)
03-17 12:55:56.533  4485  4485 E ActivityThread: 	at com.android.email.service.n.c(SourceFile:177)
03-17 12:55:56.533  4485  4485 E ActivityThread: 	at com.android.email.provider.b.a(SourceFile:198)
03-17 12:55:56.533  4485  4485 E ActivityThread: 	at com.android.email.provider.b.a(SourceFile:142)
03-17 12:55:56.533  4485  4485 E ActivityThread: 	at com.android.email.service.EmailBroadcastProcessorService.c(SourceFile:349)
03-17 12:55:56.533  4485  4485 E ActivityThread: 	at com.android.email.service.EmailBroadcastProcessorService.onHandleIntent(SourceFile:1334)
03-17 12:55:56.533  4485  4485 E ActivityThread: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-17 12:55:56.533  4485  4485 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 12:55:56.533  4485  4485 E ActivityThread: 	at android.os.Looper.loop(Looper.java:145)
03-17 12:55:56.533  4485  4485 E ActivityThread: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-17 12:55:56.533  1022  1506 W ActivityManager: Unbind failed: could not find connection for android.os.BinderProxy@3a6021ad
,03-17 12:55:56.533  1696  1696 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SubSettings
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.LabelName
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Password
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$EthernetSettingsActivity
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
,03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$WirelessSettingsActivity
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$WifiSettingsActivity
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiSettings
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiPickerActivity
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiSecPickerActivity
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiCaptiveActivity
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.FreeWifiScanPickerDialog
03-17 12:55:56.553  1191  1191 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-17 12:55:56.553  1191  1191 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-17 12:55:56.553  1191  1191 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiWarningDialog
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiOffloadDialog
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiAdvancedSecSetupActivity
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WificmccSetupActivity
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiSecSetupActivity
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiWarningDialog
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiSetupActivity
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.accessibility.smartscroll.app.sbrowsertry.SmartScreenActivity
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiPickerDialog
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiSettingsForSetupWizardXL
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AdvancedWifiSettingsActivity
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SavedAccessPointsSettingsActivity
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$WifiShareProfileActivity
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiInfo
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiConfigInfo
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiAPITest
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiStatusTest
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Loop for runn,ing activitycom.android.settings.wifi.mobileap.WifiApSettings
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApWarning
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApTestConfigure
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiPoorConnection
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiHiddenApListActivity
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiHiddenApDeleteActivity
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiDisconnectWeakApSettings
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ApnSettingsActivity
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.553  1191  1191 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$BluetoothSettingsActivity
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothSettings
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothScanDialog
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothErrorActivity
,03-17 12:55:56.553  1191  1191 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.CheckBluetoothStateActivity
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.DevicePickerActivity
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothEnableActivity
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothEnablingActivity
,03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$MirrorLinkActivity
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.553  1191  1191 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$TetherSettingsActivity
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.samsung.android.multiuser.install_only_owner
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.TetherSettings
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.samsung.android.multiuser.install_only_owner
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$WifiP2pSettingsActivity
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.p2p.WifiP2pSettings
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
,03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$WifiP2pHelpActivity
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS,
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.p2p.WifiP2pDummyPickerActivity
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$NearbySettingsActivity
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.nearby.NearbySettings
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wfd.WfdHelpActivity
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wfd.WfdPickerDialog,
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$VpnSettingsActivity
,03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DateTimeSettingsActivity
,03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.DateTimeSettingsSetupWizard
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.FeatureSettingsSetupWizard
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$LocalePickerActivity
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$InputMethodAndLanguageSettingsActivity
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$VoiceInputSettingsActivity
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$HandwritingLanguageActivity
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.handwritingsearch.HandwritingLanguageTablet
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$KeyboardLayoutPickerActivity
,03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.LanguageSettings
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SpellCheckersSettingsActivity
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.563  3758  3837 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.inputmethod.InputMethodAndSubtypeEnablerActivity
,03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$UserDictionarySettingsActivity
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.inputmethod.UserDictionaryAddWordActivity
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.UserDictionarySettings
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ZenModeSettingsActivity
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
,03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ZenModeDNDSettingsActivity
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
,03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$HomeSettingsActivity
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.HomeSettings
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$LockScreenSettingsActivity
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.573  1022  1034 I ActivityManager: Killing 3758:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #31
,03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DisplaySettingsActivity
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.DisplaySettings
,03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$LockscreenMenuActivity
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$BlockSettingsActivity
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$LedIndicatorSettingsActivity
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DockSettingsActivity
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.DockSettings
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ContextualPageSettings
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
,03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ContextualPageHelpActivity
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DeviceInfoSettingsActivity
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
,03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.DeviceNameDialog
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SettingsLicenseActivity
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.PrivacyAlertDialogActivity
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.PrivacyAlertProceedDialogActivity
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SettingsSafetyLegalActivity
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
,03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ManageApplicationsActivity
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.applications.ManageApplications
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ManageApplications
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.RunningServices
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.LaunchApplication
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.applications.StorageUse
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.applications.InstalledAppDetailsTop
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.accounts.ManageAccountsActivity
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.applications.InstalledAppDetails
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.applications.UninstallMultipleScreen
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$RunningServicesActivity
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$StorageUseActivity
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$NotificationStationActivity
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AppOpsDetailsActivity
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$LocationSettingsActivity
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
,03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SecuritySettingsActivity
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.MonitoringCertInfoActivity
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$TrustedCredentialsSettingsActivity
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SecuritySettings
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PrivacySettingsActivity
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SetFullBackupPassword
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.CredentialStorage
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DeviceAdminSettingsActivity
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.DeviceAdminSettings
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.DeviceAdminAdd
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$UsageAccessSettingsActivity
,03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SetProfileOwner
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.IccLockSettings
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SimPinLockSettings
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SimPersoLockSettings
,03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AccessibilitySettingsActivity
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AccessibilityDaltonizerSettingsActivity
,03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.settings.accessibility.AccessibilityWidgetDialogActivity
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$CaptioningSettingsActivity
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$MagnifierSettingsActivity
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 12:55:56.553  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AssistantMenuPreferenceFragmentActivity
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.AccessibilitySettingsSetupWizard
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$TextToSpeechSettingsActivity
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DrivingModeSettingsActivity
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AssistiveHepticSettingsActivity
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ConfirmDeviceCredentialActivity
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.notification.RedactionInterstitial
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.notification.RedactionSettingsStandalone
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ConfirmLockPattern
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ConfirmLockPassword
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ConfirmLockEnterpriseIdentity
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockEnterpriseIdentity
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ConfirmLockPattern$InternalActivity
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ConfirmLockPassword$InternalActivity
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.BluetoothPairingWithCac
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockGeneric
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockGeneric$InternalActivity
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.KnoxChooseLockTwoFactor
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.KnoxChooseLockBackupPin
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockPattern
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockBLock
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockPassword
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockMotion
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockAdditionalPin
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockSignature
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.EncryptionInterstitial
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.deviceinfo.Status
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$StorageSettingsActivity
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.deviceinfo.MiscFilesHandler
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.deviceinfo.DeviceInfoTabActivity
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ApnEditor
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.MediaFormat
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.MediaFormatSd
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$QuickLaunchSettingsActivity
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.quicklaunch.BookmarkPicker
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DevelopmentSettingsActivity
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PrintSettingsActivity
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PrintJobSettingsActivity
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.DevelopmentSettings
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.AppPicker
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$UsbSettingsActivity,
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.UsbSettings
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothPairingDialog
,03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.RequestPermissionActivity
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiScanModeActivity
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.RequestPermissionHelperActivity
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothPermissionActivity
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ActivityPicker
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$NfcSettingsActivity
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.nfc.NfcAdvancedRoutingSetting
,03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AndroidBeamSettingsActivity
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SBeamSettingsActivity
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$WifiDisplaySettingsActivity
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.BatteryInfo
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Display
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.RadioInfo
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ProxySelector
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.BandMode
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.TestingSettings
,03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.fulllocalepickertest.FullLocalePickerTest
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.AppWidgetPickActivity
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.AllowBindAppWidgetActivity
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.UsageStatsActivity
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PowerUsageSummaryActivity
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.fuelgauge.PowerUsageSummary
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$BatterySaverSettingsActivity
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AccountMenuActivity
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AccountSettingsActivity
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AccountSyncSettingsActivity
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.accounts.AddAccountSettings
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.accounts.ChooseAccountActivity
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.CryptKeeper
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.CryptKeeper$FadeToBlack
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.CryptKeeperConfirm$Blank
,03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.CryptDecryptConfirm$Blank
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$CryptKeeperSettingsActivity
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$CryptDecryptSettingsActivity
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$CryptSDCardSettingsActivity
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SimChangeAlertSettingsActivity
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DataUsageSummaryActivity
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DataUsageMeteredSettingsActivity
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DreamSettingsActivity
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$UserSettingsActivity
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PaymentSettingsActivity
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
,03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.nfc.PaymentDefaultDialog
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SmsDefaultDialog
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ActiveNetworkScorerDialog
,03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$NotificationAccessSettingsActivity
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ConditionProviderSettingsActivity
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$NotificationSettingsActivity
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SoundSettingsActivity
,03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SoundSettings
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$OtherSoundSettingsActivity
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$NotificationAppListActivity
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AppNotificationSettingsActivity
,03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SimSettingsActivity
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.FactoryResetDialog
,03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.LockScreenWallpaper
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$WallpaperSettingsActivity
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.GSensorSettings
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingModeSettingsActivity
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingMode2014Activity
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingModeSettings2014Activity
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$UltraPowerSavingModeActivity
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ModePreviewTablet
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ModePreviewDialog
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.InkeffectPreview
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.InkeffectPreviewTablet
,03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ModePreview
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.NewModePreview
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SViewColor
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SViewColor2014
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SViewStyleClock
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SViewMiniWallpaper
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SViewCoverEdgeSettingsActivity
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockFaceWarning
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PowerSettingsActivity
,03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.RecommendRingtoneDialog
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SelectInfoCoverSettingsActivity
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:55:56.613  1022  1046 W libprocessgroup: failed to open /acct/uid_1000/pid_3758/cgroup.procs: No such file or directory
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SelectItemDisplay
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.sec.android.sdk.cover.MODE
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$WeatherSettingsFragmentActivity
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SViewCoverPopup
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.sec.android.sdk.cover.MODE
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.WarrantyLegal
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SamsungLegalTablet
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.PenDetachmentOption
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PenDetachmentOptionActivity
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.NotificationPanelMenu
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$NotificationPanelMenuActivity
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.563  3758  3,837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.NotificationPanelSettings
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$MotionSettingsActivity
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AirMotionSettingActivity
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SMotionGuideHub2014Activity
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$FingerAirViewSettingActivity
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$FingerAirViewHelpSettingActivity
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PenAirViewHelpSettingActivity
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AirViewSettingActivity
03-17 12:55:56.563  3758  3837 I AMMetaDataPar,serService: Resource data:Inside bundle  check
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$MouseHoveringSettingsActivity
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SoftwareUpdateSettingActivity
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.PenHelpActivity
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PenHelpFragmentActivity
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DirectPenInputSettingsActivity
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PenAirViewSettingsMenuActivity
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PenSettingsMenuActivity
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.PhoneVibration
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.OneHandHelp
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.OneHandAdaptiveHelp
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$OneHandSideSoftKeyFragmentActivity
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalvibration.PersonalVibration
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalvibration.SelectPatternDialog
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.LockScreenShortcutSettings
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.AppList
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.ExpandAppList
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ReadingModeSettingsActivity
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.customizablekey.CustomizableKeySettings
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$CustomizableKeySettingsActivity
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.customizablekey.AppList
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DualClockSettingActivity
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$RecommendedAppsMenuActivity
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$RecommendedAppsListActivity
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SettingsReceiverActivity
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SelectPenDetachNotiDialog
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SecurityWarningDialog
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PersonalPageSettingsActivity
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageSettings
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.PersonalPageDisclaimer
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageAutoModeSwitchAlertDialogActivity
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorial
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialDisclaimerActivity
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialAppActivity
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialAddActivity
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockPattern
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockPassword
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockAdditionalPin
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageConfirmLockPattern
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageConfirmLockPassword
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$EasyModeSettingsActivity
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$EasyModeActivity
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$EasyModeAppActivity
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$MyPlaceSettingsActivity
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$MyPlaceProfileSettingsActivity
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PlaceSettingsActivity
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.myplace.SelectMapActivity
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$GlobalRoamingSettingsActivity
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$TRoamingSettingsActivity
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.flipfont.FontListActivity
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.flipfont.FontListProgressActivity
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$BackupAssistantPlusSettingsActivity
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.myprofile.MyProfileActivity
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.MagazineCard
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ClockWidgetActivity
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.myprofile.PersonalMessage
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$CloudSettingActivity
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ShortCameraMenu
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ClockMyprofileMenu
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ClockMyprofileMenuTablet
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$LaunchCameraSettingsActivity
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SmartScreenSettingsActivity
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SmartBondingSettingsActivity
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ToolboxMenuActivity
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ToolboxListActivity
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SmartScrollAdvancedSettingsActivity
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$MultiWindowSettingsActivity
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.MultiWindowSettings
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.settingssearch.SettingsSearchActivity
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SearchActivity
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ColorChipReportActivity
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DirectAccessActivity
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$NotificationReminderActivity
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$VoiceInputControlSettingsActivity
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.PreloadAppUpdate
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.PreloadAppUpdateList
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.activekey.ActiveKeySettings
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ActiveKeySettingsActivity
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.activekey.AppList
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DisplaySettingsTab
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.SETTING_HEADER_ID
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$InputAndControlSettingsTab
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.SETTING_HEADER_ID
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$GeneralSettingsTab
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.SETTING_HEADER_ID
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.DeviceHealthActivity
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SettingsEmergencyActivity
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareSettingsActivity
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareEmergencyModeActivity
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareDisasterActivity
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareDisclaimerActivity
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareDisasterDisclaimerActivity
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareCoverageDialog
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AirplaneModeSettingsActivity
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ToddlerModeSettingsActivity
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.favorite.FavoriteMenuList
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$FestivalEffectSettingsActivity
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.powersavingmode.PowerNotiDialog
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.powersavingmode.PowerNotiDataDialog
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.SetupWizardWifiScreen
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.CaptivePortalWebViewActivity
03-17 12:55:56.563  3758  3837 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.KnoxActiveProtectionEulaActivity
03-17 12:55:56.593  4485  4517 E SQLiteLog: (283) recovered 74 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,03-17 12:55:56.713  3164  3206 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 8 sec
,03-17 12:55:56.773  4485  4517 E File    : fail readDirectory() errno=2
,03-17 12:55:56.783  4485  4535 I Gmail   : notifyAccountChanged
,03-17 12:55:56.783  4485  4541 I Gmail   : getAccountsCursor
,03-17 12:55:56.793  1022  1515 D ActivityManager: retrieveServiceLocked(): component = com.dropbox.android/com.dropbox.android.exception.CrashUploaderService; callingUser = 0; userId(target) = 0
,03-17 12:55:56.793  4485  4535 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,03-17 12:55:56.793  1022  1515 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:55:56.793  1022  1515 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
,03-17 12:55:56.793  1022  1515 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.dropbox.android, destAppInfo.processName = com.dropbox.android
,03-17 12:55:56.793  1022  1515 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:55:56.793  1022  1515 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:56.793  1022  1515 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:55:56.793  1022  1515 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:55:56.793  4485  4535 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,03-17 12:55:56.813  4542  4542 E Zygote  : MountEmulatedStorage(),
03-17 12:55:56.813  4542  4542 E Zygote  : v2
03-17 12:55:56.813  4542  4542 I libpersona: KNOX_SDCARD checking this for 10092
03-17 12:55:56.813  4542  4542 I libpersona: KNOX_SDCARD not a persona,
,03-17 12:55:56.813  4542  4542 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 12:55:56.813  4542  4542 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-17 12:55:56.813  1022  1515 I ActivityManager: Start proc com.dropbox.android:crash_uploader for service com.dropbox.android/.exception.CrashUploaderService: pid=4542 uid=10092 gids={50092, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-17 12:55:56.813  1022  3083 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,03-17 12:55:56.813  4542  4542 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,03-17 12:55:56.813  4485  4535 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
,03-17 12:55:56.823  4485  4535 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
03-17 12:55:56.823  1696  1696 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 12:55:56.833  4542  4542 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:55:56.843  4542  4542 D ActivityThread: Added TimaKeyStore provider
,03-17 12:55:56.843  1022  1234 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,03-17 12:55:56.843  1022  1234 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:55:56.843  1022  1234 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:55:56.843  1022  1234 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,03-17 12:55:56.843  1022  1054 D PowerManagerService: [s] UserActivityState : 1 -> 2
,03-17 12:55:56.843  1022  1054 D DisplayPowerController: getFinalBrightness : Summary is 19 -> 19
03-17 12:55:56.843  1022  1054 D DisplayPowerController: animation target = 19, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,03-17 12:55:56.843  1022  1054 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
,03-17 12:55:56.853  1022  1176 D lights  : lcd : 25 +
,03-17 12:55:56.853  4485  4517 I Gmail   : Sending provider changed intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://gmail-ls/unread/^sq_ig_i_promo (has extras) }
,03-17 12:55:56.863  1022  1035 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 12:55:56.863  1022  1054 D DisplayPowerController: getFinalBrightness : Summary is 19 -> 19
,03-17 12:55:56.863  1022  1054 D DisplayPowerController: animation target = 19, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
03-17 12:55:56.863  1022  1176 D lights  : lcd : 25 -
,03-17 12:55:56.863  1022  1176 D lights  : lcd : 19 +
03-17 12:55:56.863  1022  1035 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:55:56.863  1022  1035 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:55:56.863  1022  1035 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-17 12:55:56.873  4485  4517 I Gmail   : Sending provider changed intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://gmail-ls/unread/^sq_ig_i_social (has extras) }
,03-17 12:55:56.873  4485  4517 I Gmail   : Sending provider changed intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://gmail-ls/unread/^sq_ig_i_personal (has extras) }
,03-17 12:55:56.883  1022  1176 D lights  : lcd : 19 -
,03-17 12:55:56.883  1022  1054 D DisplayPowerController: getFinalBrightness : Summary is 19 -> 19
03-17 12:55:56.883  1022  1054 D DisplayPowerController: animation target = 19, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,03-17 12:55:56.883  1022  1035 I ActivityManager: Killing 3781:com.google.android.onetimeinitializer/u0a14 (adj 15): empty #31
,03-17 12:55:56.903  1022  3060 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 12:55:56.903  1022  3060 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:55:56.903  1022  3060 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:55:56.903  1022  3060 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-17 12:55:56.903  4520  4520 I com.dropbox.android.service.DropboxNetworkReceiver: Setting receiver enabled: false
,03-17 12:55:56.923  4520  4520 E ActivityThread: Failed to find provider info for com.dropbox.carousel.CuOwnerCheckProvider
,03-17 12:55:56.953  1022  3060 I ActivityManager: Killing 3813:com.android.calendar/u0a135 (adj 15): empty #31
,03-17 12:55:56.953  1696  1829 I art     : Explicit concurrent mark sweep GC freed 8412(442KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 10MB/17MB, paused 965us total 37.853ms
,03-17 12:55:56.973  4520  4520 I dbxyzptlk.db300200.aw.h: Loading /data/data/com.dropbox.android/files/extracted_libs/lib_breakpadinstaller_9807ade0d39f04306c7e28de04204d1f53ae2228_armv7a
,03-17 12:55:56.983  4520  4520 D breakpad: breakpad loaded; target path "/data/data/com.dropbox.android/app_crashdumps"
,03-17 12:55:56.983  4520  4520 I dbxyzptlk.db300200.aw.h: Loading /data/data/com.dropbox.android/files/extracted_libs/lib_dbxfileobserver_b492ffd532b8b6365d97439f842c164c3c90fd4e_armv7a
,03-17 12:55:56.983  4520  4520 I dbxyzptlk.db300200.aw.h: Loading /data/data/com.dropbox.android/files/extracted_libs/lib_dropboxsync_e16babc055b114839529ea959e1ce06f2a593b63_armv7a
,03-17 12:55:57.003  4485  4504 I Gmail   : getAccountsCursor
,03-17 12:55:57.003  1022  1234 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,03-17 12:55:57.013  1696  1696 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 12:55:57.033  1022  1046 W libprocessgroup: failed to open /acct/uid_10014/pid_3781/cgroup.procs: No such file or directory
,03-17 12:55:57.033  1022  1046 W libprocessgroup: failed to open /acct/uid_10135/pid_3813/cgroup.procs: No such file or directory
,03-17 12:55:57.073  4520  4520 I libDropboxSync.so: Setting global terminate handler.
,03-17 12:55:57.103  4520  4520 I dbxyzptlk.db300200.aw.h: Loading /data/data/com.dropbox.android/files/extracted_libs/lib_mupdf_aa417f8c60b792b71fc3cef90fc4bb8ddba4ea56_armv7a
,03-17 12:55:57.143  4520  4520 I com.dropbox.sync.android.L: Prepared cache dir '/data/data/com.dropbox.android/app_DropboxSyncCache/hizqkiq3952astb'.
,03-17 12:55:57.163  4520  4520 I com.dropbox.sync.android.L: Removing unclaimed file/directory in cache: "local-dbapp_noauth"
,03-17 12:55:57.183  4520  4520 I com.dropbox.sync.android.bf: Dropbox initialized for application: hizqkiq3952astb (com.dropbox.android/3.0.2 DropboxSync/3.1+dev (Android; 5.0.2; samsung SM-A500FU armeabi-v7a; en_US))
,03-17 12:55:57.203  4520  4520 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-17 12:55:57.203  4520  4520 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-17 12:55:57.223  4520  4520 I com.dropbox.sync.android.aS: Created NativeDbappNoAuthClientProvider
,03-17 12:55:57.223  1022  1534 D ActivityManager: retrieveServiceLocked(): component = com.dropbox.android/com.dropbox.sync.android.DbxSyncService; callingUser = 0; userId(target) = 0
,03-17 12:55:57.223  1022  1534 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:55:57.223  1022  1534 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
,03-17 12:55:57.233  1022  1534 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.dropbox.android, destAppInfo.processName = com.dropbox.android
,03-17 12:55:57.283  4520  4565 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
03-17 12:55:57.283  4520  4565 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
03-17 12:55:57.283  4520  4565 I System.out: (HTTPLog)-Static: isShipBuild true
03-17 12:55:57.283  4520  4565 I System.out: (HTTPLog)-Thread-697-831485183: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
03-17 12:55:57.283  4520  4565 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,03-17 12:55:57.283   279   926 D EnterpriseController: uids 10092
03-17 12:55:57.283   279   926 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
03-17 12:55:57.283   279   926 D Netd    : getNetworkForDns: using netid 502 for uid 10092
,03-17 12:55:57.323  1022  1063 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,03-17 12:55:57.343  4520  4565 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,03-17 12:55:57.373  4520  4520 I com.dropbox.sync.android.DbxSyncService: DbxSyncService starting.
,03-17 12:55:57.383  1022  1361 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:55:57.383  1022  1361 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:57.383  1022  1361 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:55:57.383  1022  1361 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:55:57.393  4577  4577 E Zygote  : MountEmulatedStorage(),
03-17 12:55:57.393  4577  4577 E Zygote  : v2
03-17 12:55:57.393  4577  4577 I libpersona: KNOX_SDCARD checking this for 10057,
03-17 12:55:57.393  4577  4577 I libpersona: KNOX_SDCARD not a persona
03-17 12:55:57.393  1022  1361 I ActivityManager: Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.StartUpReceiver: pid=4577 uid=10057 gids={50057, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a
,03-17 12:55:57.393  4577  4577 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 12:55:57.393  4577  4577 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 12:55:57.393  1022  1083 I ActivityManager: Killing 3887:com.sec.android.app.camera/u0a139 (adj 15): empty #31
,03-17 12:55:57.393  4577  4577 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-17 12:55:57.413  4577  4577 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:55:57.413  4577  4577 D ActivityThread: Added TimaKeyStore provider
,03-17 12:55:57.513  1022  1046 W libprocessgroup: failed to open /acct/uid_10139/pid_3887/cgroup.procs: No such file or directory
,03-17 12:55:57.563  4520  4565 I com.dropbox.sync.android.aF: Created new socket: SSL socket over Socket[address=api.dropbox.com/108.160.172.205,port=443,localPort=34883]
,03-17 12:55:57.613  1022  1482 D LocationManagerService: getProviders()=[passive]
,03-17 12:55:57.693  1022  1365 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.service.BroadcastListenerService; callingUser = 0; userId(target) = 0
,03-17 12:55:57.693  1022  1365 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:55:57.693  1022  1365 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:55:57.693  1022  1365 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,03-17 12:55:57.723  3164  3206 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 9 sec
,03-17 12:55:57.753  1022  1361 I splitIntent: Queue : backgroundsplit_2 intent android.intent.action.BOOT_COMPLETED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,03-17 12:55:57.753  1022  1361 I ActivityManager: Killing 3830:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #31
,03-17 12:55:57.763  1022  1506 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:55:57.763  1022  1506 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-17 12:55:57.763  1022  1506 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-17 12:55:57.773  1022  3083 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,03-17 12:55:57.773  1022  3083 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:55:57.773  1022  3083 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-17 12:55:57.773  1022  3083 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,03-17 12:55:57.773  1022  3059 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 12:55:57.773  1022  3059 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:55:57.773  1022  3059 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:55:57.773  1022  3059 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
,03-17 12:55:57.783  2468  2468 I Hs20UtilService: Starting #4
,03-17 12:55:57.783  2468  2487 I Hs20UtilService: Message received 5007
,03-17 12:55:57.783  1335  1335 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,03-17 12:55:57.793  1335  1335 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,03-17 12:55:57.793  1022  3133 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 12:55:57.793  1022  3133 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:55:57.793  1022  3133 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 12:55:57.793  1022  3133 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 12:55:57.803  1335  1335 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: CONNECTED
,03-17 12:55:57.803  1335  1335 I NearbySettings: DMSUtil.isNetworkConnected - P2P: IDLE
,03-17 12:55:57.803  1335  1335 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,03-17 12:55:57.803  1335  1335 I NearbySettings: MountReceiver.onReceive - Keep current state
,03-17 12:55:57.813  1022  1506 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:55:57.813  1022  1506 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 12:55:57.813  1022  1506 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-17 12:55:57.823  1022  1022 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:55:57.823  1022  1022 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
03-17 12:55:57.823  1022  1022 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-17 12:55:57.823  1022  1022 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:55:57.823  1022  1022 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 12:55:57.823  1022  1022 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-17 12:55:57.823  1022  1022 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:55:57.833  1022  1022 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 12:55:57.833  1022  1022 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-17 12:55:57.843  1022  1022 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:55:57.843  1022  1022 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 12:55:57.843  1022  1022 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-17 12:55:57.843  1022  1022 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:55:57.843  1022  1022 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-17 12:55:57.843  1022  1022 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-17 12:55:57.843  1022  1022 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:55:57.843  1022  1022 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 12:55:57.843  1022  1022 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-17 12:55:57.853  1022  1022 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:55:57.853  1022  1022 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 12:55:57.853  1022  1022 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-17 12:55:57.853  1022  1022 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:55:57.853  1022  1022 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 12:55:57.853  1022  1022 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-17 12:55:57.853  1022  1022 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:55:57.853  1022  1022 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 12:55:57.853  1022  1022 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-17 12:55:57.873  1022  1022 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:55:57.873  1022  1022 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 12:55:57.873  1022  1022 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-17 12:55:57.873  1022  1022 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:55:57.873  1022  1022 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-17 12:55:57.873  1022  1022 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-17 12:55:57.883  1022  1022 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:55:57.883  1022  1022 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-17 12:55:57.883  1022  1022 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-17 12:55:57.883  1022  1022 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:55:57.883  1022  1022 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-17 12:55:57.883  1022  1022 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-17 12:55:57.893  1022  1022 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:55:57.893  1022  1022 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:55:57.893  1022  1022 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 12:55:57.893  1022  1506 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,03-17 12:55:57.893  1022  1506 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:55:57.893  1022  1506 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:55:57.893  1022  1506 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-17 12:55:57.893  1022  1234 I splitIntent: intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
,03-17 12:55:57.893  1022  1234 I splitIntent: base  index=1, name=com.google.android.gms com.google.android.gms.subscribedfeeds.ConfigurationReceiver
03-17 12:55:57.893  1022  1234 I splitIntent: other index=4, name=com.google.android.gms com.google.android.gms.common.stats.GmsCoreStatsServiceLauncher
,03-17 12:55:57.903  1022  1234 I splitIntent: arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,03-17 12:55:57.903  1696  4613 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,03-17 12:55:57.903  1022  1234 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:55:57.903  1022  1234 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:55:57.903  1022  1234 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 12:55:57.903  1022  1234 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:55:57.913  1022  1234 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 12:55:57.913  1022  1234 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 12:55:57.913  1696  1696 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,03-17 12:55:57.913  1022  1234 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:55:57.913  1022  1234 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:55:57.913  1022  1234 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 12:55:57.923  1022  3060 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:55:57.923  1022  3060 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:55:57.923  1022  3060 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 12:55:57.923  1914  1914 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,03-17 12:55:57.923  1022  3133 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
,03-17 12:55:57.923  1022  3133 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:55:57.923  1022  3133 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 12:55:57.923  1022  3133 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 12:55:57.933  1022  3083 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:55:57.933  1022  3083 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:55:57.933  1022  3083 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 12:55:57.933  1022  3083 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:55:57.933  1022  3083 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:55:57.933  1022  3083 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 12:55:57.943  1022  3083 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:55:57.943  1022  3083 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:55:57.943  1022  3083 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 12:55:57.943  1022  1035 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:55:57.943  1022  1035 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:55:57.943  1022  1035 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 12:55:57.953  1022  1365 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0,
,03-17 12:55:57.953  1022  1365 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:55:57.953  1022  1365 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:55:57.953  1022  1365 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 12:55:57.953  1022  1365 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:55:57.953  1022  1365 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:57.953  1022  1365 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:55:57.953  1022  1365 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:55:57.973  4615  4615 E Zygote  : MountEmulatedStorage()
03-17 12:55:57.973  4615  4615 E Zygote  : v2
03-17 12:55:57.973  4615  4615 I libpersona: KNOX_SDCARD checking this for 10012
,03-17 12:55:57.973  4615  4615 I libpersona: KNOX_SDCARD not a persona
,03-17 12:55:57.973  1022  1365 I ActivityManager: Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableService: pid=4615 uid=10012 gids={50012, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,03-17 12:55:57.973  4615  4615 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 12:55:57.973  1022  1035 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:55:57.973  1022  1035 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:55:57.973  1022  1035 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-17 12:55:57.973  4615  4615 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
03-17 12:55:57.973  4615  4615 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-17 12:55:57.983  1022  1034 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:55:57.983  1022  1034 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:55:57.983  1022  1034 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 12:55:57.983  1022  3060 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 12:55:57.993  1022  3060 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:55:57.993  1022  3060 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:55:57.993  1022  3060 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 12:55:57.993  1022  3059 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:55:57.993  1022  3059 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:55:57.993  1022  3059 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 12:55:58.003  4615  4615 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:55:58.003  1022  3059 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:55:58.003  1022  3059 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:55:58.003  4615  4615 D ActivityThread: Added TimaKeyStore provider
03-17 12:55:58.003  1022  3059 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 12:55:58.003  1022  1515 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,03-17 12:55:58.003  1022  1515 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:55:58.003  1022  1515 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:55:58.003  1022  1515 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 12:55:58.003  1914  4626 D LocationInitializer: Restart initialization of location
,03-17 12:55:58.003  1022  3133 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
,03-17 12:55:58.003  1022  3133 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:55:58.003  1022  3133 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:55:58.003  1022  3133 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 12:55:58.023  1022  1035 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 12:55:58.023  1022  1035 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:55:58.023  1022  1035 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:55:58.023  1022  1035 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-17 12:55:58.033  1022  3133 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,03-17 12:55:58.033  1022  3133 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:55:58.033  1022  3133 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:55:58.033  1022  3133 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-17 12:55:58.033  1022  1046 W libprocessgroup: failed to open /acct/uid_1000/pid_3830/cgroup.procs: No such file or directory
,03-17 12:55:58.033  1022  3059 I splitIntent: intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
03-17 12:55:58.033  1022  3059 I splitIntent: base  index=1, name=com.google.android.gms com.google.android.gms.subscribedfeeds.ConfigurationReceiver
03-17 12:55:58.033  1022  3059 I splitIntent: other index=4, name=com.google.android.gms com.google.android.gms.common.stats.GmsCoreStatsServiceLauncher
03-17 12:55:58.033  1022  3059 I splitIntent: arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,03-17 12:55:58.043  4615  4615 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,03-17 12:55:58.043  4615  4615 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-17 12:55:58.043  1696  4633 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,03-17 12:55:58.043  1696  1696 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,03-17 12:55:58.053  1022  3060 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,03-17 12:55:58.053  1022  3060 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:55:58.053  1022  3060 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:55:58.053  1022  3060 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
,03-17 12:55:58.063  1914  1914 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,03-17 12:55:58.063  1022  1035 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
,03-17 12:55:58.063  4615  4615 I MultiDex: VM with version 2.1.0 has multidex support
03-17 12:55:58.063  4615  4615 I MultiDex: install
03-17 12:55:58.063  4615  4615 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,03-17 12:55:58.073  1022  1035 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:55:58.073  1022  1035 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:55:58.073  1022  1035 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 12:55:58.073  1022  3059 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 12:55:58.073  1022  3059 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:55:58.073  1022  3059 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:55:58.073  1022  3059 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-17 12:55:58.103  4615  4615 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,03-17 12:55:58.103  1022  1034 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 12:55:58.103  1022  1034 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:55:58.103  1022  1034 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:55:58.103  1022  1034 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 12:55:58.113  1022  1518 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,03-17 12:55:58.113  1022  1518 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:55:58.113  1022  1518 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:55:58.113  1022  1518 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 12:55:58.113  1914  4636 D LocationInitializer: Restart initialization of location
,03-17 12:55:58.113  1022  1234 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
,03-17 12:55:58.123  1022  1234 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:55:58.123  1022  1234 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:55:58.123  1022  1234 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 12:55:58.153  4615  4615 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,03-17 12:55:58.153  4615  4615 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@35487134: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,03-17 12:55:58.153  4615  4615 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,03-17 12:55:58.183  1022  1534 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,03-17 12:55:58.183  1022  1534 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:55:58.183  1022  1534 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-17 12:55:58.183  1022  1534 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,03-17 12:55:58.183  2468  2468 I Hs20UtilService: Starting #5
,03-17 12:55:58.183  1335  1335 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,03-17 12:55:58.193  2468  2487 I Hs20UtilService: Message received 5007
,03-17 12:55:58.193  4615  4615 D WearableService: callingUid 10012, callindPid: 4615
,03-17 12:55:58.193  1335  1335 I NearbySettings: MountReceiver.onReceive - Keep current state
,03-17 12:55:58.203  1696  1707 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.googlequicksearchbox, service: oauth2:https://www.googleapis.com/auth/googlenow
03-17 12:55:58.203  1696  1707 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/googlenow without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-17 12:55:58.203  1696  1707 I GLSUser : [GLSUser] Extracting token using key: Auth
03-17 12:55:58.203  1696  1707 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-17 12:55:58.213  1022  1506 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,03-17 12:55:58.213  1022  1506 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:55:58.213  1022  1506 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 12:55:58.213  1022  1506 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,03-17 12:55:58.213  1696  1707 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 12:55:58.213  2468  2468 I Hs20UtilService: Starting #6
,03-17 12:55:58.213  2468  2487 I Hs20UtilService: Message received 5007
,03-17 12:55:58.213  1022  3083 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,03-17 12:55:58.223  1022  3083 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:55:58.223  1022  3083 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:55:58.223  1022  3083 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-17 12:55:58.223  1335  1335 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,03-17 12:55:58.223  1335  1335 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,03-17 12:55:58.223  1335  1335 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: CONNECTED
,03-17 12:55:58.233  1335  1335 I NearbySettings: DMSUtil.isNetworkConnected - P2P: IDLE
,03-17 12:55:58.233  1335  1335 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
03-17 12:55:58.233  1335  1335 I NearbySettings: MountReceiver.onReceive - Keep current state
,03-17 12:55:58.233  1022  1083 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,03-17 12:55:58.243  1022  1083 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:55:58.243  1022  1083 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-17 12:55:58.243  1022  1083 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,03-17 12:55:58.243  2468  2468 I Hs20UtilService: Starting #7
,03-17 12:55:58.243  2468  2487 I Hs20UtilService: Message received 5007
,03-17 12:55:58.243  1335  1335 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,03-17 12:55:58.243  1335  1335 I NearbySettings: MountReceiver.onReceive - Keep current state
,03-17 12:55:58.253  1763  4614 E MDM     : [193] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,03-17 12:55:58.253  1022  1035 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,03-17 12:55:58.263  1022  1506 D SecContentProvider2: uri = 15 selection = getToastGravityEnabledState
,03-17 12:55:58.263  1022  1506 D SecContentProvider2: mCursor = null
,03-17 12:55:58.263  1022  1361 D SecContentProvider2: uri = 15 selection = getToastGravity
,03-17 12:55:58.263  1022  1361 D SecContentProvider2: mCursor = null
,03-17 12:55:58.263  1022  1534 D SecContentProvider2: uri = 15 selection = getToastGravityXOffset
,03-17 12:55:58.263  1022  1534 D SecContentProvider2: mCursor = null
,03-17 12:55:58.263  1022  3060 D SecContentProvider2: uri = 15 selection = getToastGravityYOffset
,03-17 12:55:58.263  1022  3060 D SecContentProvider2: mCursor = null
,03-17 12:55:58.263  1763  4639 E MDM     : [194] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,03-17 12:55:58.273  1022  3059 D SecContentProvider2: uri = 15 selection = getToastEnabledState
,03-17 12:55:58.273  1022  3059 D SecContentProvider2: mCursor = null
,03-17 12:55:58.273  1022  1365 D SecContentProvider2: uri = 15 selection = getToastShowPackageNameState
,03-17 12:55:58.273  1022  1365 D SecContentProvider2: mCursor = null
,03-17 12:55:58.283  3554  3554 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,03-17 12:55:58.283  3554  3554 I PCWCLIENTTRACE_PushUtil: sales region : global
,03-17 12:55:58.283  3554  3554 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
03-17 12:55:58.283  3554  3554 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,03-17 12:55:58.283  1022  3133 I splitIntent: intent=android.net.conn.CONNECTIVITY_CHANGE will be not split. because same process=com.google.android.gms is in other queue. index=22
03-17 12:55:58.283  1022  3133 I splitIntent: base  index=22, name=com.google.android.gms com.google.android.gms.gcm.gmsproc.GmsAutoStarter
03-17 12:55:58.283  1022  3133 I splitIntent: other index=24, name=com.google.android.gms com.google.android.gms.common.status.StatusServiceLauncherBroadcastReceiver
03-17 12:55:58.283  1022  3133 I splitIntent: arrangeSplitReceiver return false!! intent : android.net.conn.CONNECTIVITY_CHANGE !! do not split it!!
,03-17 12:55:58.283  1022  3133 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:55:58.283  1022  3133 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:55:58.283  1022  3133 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:58.293  1022  3133 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:55:58.303  4641  4641 E Zygote  : MountEmulatedStorage()
03-17 12:55:58.303  4641  4641 E Zygote  : v2
03-17 12:55:58.303  4641  4641 I libpersona: KNOX_SDCARD checking this for 10111
03-17 12:55:58.303  4641  4641 I libpersona: KNOX_SDCARD not a persona
,03-17 12:55:58.303  4641  4641 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 12:55:58.303   258   258 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=4, Uoast
,03-17 12:55:58.303  4641  4641 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 12:55:58.303  4641  4641 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-17 12:55:58.313  1022  3133 I ActivityManager: Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=4641 uid=10111 gids={50111, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-17 12:55:58.313  1022  1534 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1022
03-17 12:55:58.313  1022  1054 D DisplayPowerController: getFinalBrightness : Summary is 32 -> 32
03-17 12:55:58.313  1022  1054 D DisplayPowerController: animation target = 32, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
03-17 12:55:58.313  1022  1054 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
,03-17 12:55:58.333  4641  4641 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:55:58.333  4641  4641 D ActivityThread: Added TimaKeyStore provider
,03-17 12:55:58.333  1022  1176 D lights  : lcd : 32 +
03-17 12:55:58.333  1022  1054 D DisplayPowerController: getFinalBrightness : Summary is 32 -> 32
03-17 12:55:58.333  1191  1191 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
03-17 12:55:58.333  1022  1054 D DisplayPowerController: animation target = 32, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,03-17 12:55:58.353  1022  1176 D lights  : lcd : 32 -
,03-17 12:55:58.353  1022  1054 D DisplayPowerController: getFinalBrightness : Summary is 32 -> 32
,03-17 12:55:58.353  1022  1054 D DisplayPowerController: animation target = 32, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,03-17 12:55:58.503  1022  1083 I art     : Explicit concurrent mark sweep GC freed 28059(1756KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 30MB/45MB, paused 2.608ms total 163.198ms
,03-17 12:55:58.523  1022  1361 D ApplicationPolicy: isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
03-17 12:55:58.523  1022  1361 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,03-17 12:55:58.523  1022  1022 W NotificationService: Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,03-17 12:55:58.523  1022  2863 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-17 12:55:58.523  1191  1191 D StatusBar: ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,03-17 12:55:58.533  1191  1191 D PersonaManager: isKioskContainerExistOnDevice
,03-17 12:55:58.533  1191  1191 D PersonaManager: isKioskContainerExistOnDevice
,03-17 12:55:58.533  1191  1191 I PhoneStatusBar: Icon Only,
03-17 12:55:58.533  1191  1191 I StatusBar: Icon Only
,03-17 12:55:58.533  1191  1191 D PanelView: There is/are notification(s) 
,03-17 12:55:58.533  1191  1191 D PanelView: kidsfalse mQsExpansionEnabled:true
,03-17 12:55:58.533  1191  1191 D PersonaManager: isKioskContainerExistOnDevice
,03-17 12:55:58.533  1191  1191 I PhoneStatusBar: Icon Only
,03-17 12:55:58.533  1191  1191 I StatusBar: Icon Only
,03-17 12:55:58.543  1191  1191 D PanelView: There is/are notification(s) 
03-17 12:55:58.543  1191  1191 D PanelView: kidsfalse mQsExpansionEnabled:true
,03-17 12:55:58.543  4577  4607 W Search.LoginHelper: User recoverable exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
03-17 12:55:58.543  4577  4607 W Search.LoginHelper: com.google.android.gms.auth.e: User intervention required. Notification has been pushed.
03-17 12:55:58.543  4577  4607 W Search.LoginHelper: 	at com.google.android.gms.auth.b.c(Unknown Source)
03-17 12:55:58.543  4577  4607 W Search.LoginHelper: 	at com.google.android.gms.auth.b.a(Unknown Source)
03-17 12:55:58.543  4577  4607 W Search.LoginHelper: 	at com.google.android.gms.auth.b.a(Unknown Source)
03-17 12:55:58.543  4577  4607 W Search.LoginHelper: 	at com.google.android.apps.gsa.search.core.d.b.m.a(GoogleAuthAdapterImpl.java:29)
03-17 12:55:58.543  4577  4607 W Search.LoginHelper: 	at com.google.android.apps.gsa.search.core.d.b.k.a(FallingBackGoogleAuthAdapter.java:93)
03-17 12:55:58.543  4577  4607 W Search.LoginHelper: 	at com.google.android.apps.gsa.search.core.d.b.g.a(CachingGoogleAuthAdapter.java:72)
03-17 12:55:58.543  4577  4607 W Search.LoginHelper: 	at com.google.android.apps.gsa.search.core.d.b.n.b(LoginHelper.java:827)
03-17 12:55:58.543  4577  4607 W Search.LoginHelper: 	at com.google.android.apps.gsa.search.core.d.b.n$5.abo(LoginHelper.java:713)
03-17 12:55:58.543  4577  4607 W Search.LoginHelper: 	at com.google.android.apps.gsa.search.core.d.b.n$5.call(LoginHelper.java:710)
03-17 12:55:58.543  4577  4607 W Search.LoginHelper: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-17 12:55:58.543  4577  4607 W Search.LoginHelper: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-17 12:55:58.543  4577  4607 W Search.LoginHelper: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-17 12:55:58.543  4577  4607 W Search.LoginHelper: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-17 12:55:58.543  4577  4607 W Search.LoginHelper: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-17 12:55:58.543  4577  4607 W Search.LoginHelper: 	at java.lang.Thread.run(Thread.java:818)
03-17 12:55:58.543  4577  4607 W Search.LoginHelper: 	at com.google.android.apps.gsa.shared.util.c.a.m$1.run(GsaThreadFactory.java:99)
,03-17 12:55:58.543  4577  4603 E VelvetNetworkClient: Failed to get auth token
,03-17 12:55:58.563  4406  4425 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,03-17 12:55:58.583  4406  4425 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,03-17 12:55:58.583  4406  4425 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,03-17 12:55:58.583  4406  4425 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,03-17 12:55:58.593  4406  4425 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,03-17 12:55:58.593  4406  4425 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,03-17 12:55:58.593  4406  4425 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,03-17 12:55:58.593  4406  4425 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,03-17 12:55:58.603  4641  4641 I MusicStore: Database version: 120
,03-17 12:55:58.603  1191  1191 D PanelView: mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,03-17 12:55:58.673  1022  1361 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,03-17 12:55:58.673  1022  1361 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:55:58.673  1022  1361 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:55:58.673  1022  1361 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,03-17 12:55:58.713   257   525 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
03-17 12:55:58.713   257   525 W Vold    : Returning OperationFailed - no handler for errno 0
,03-17 12:55:58.713  4641  4641 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,03-17 12:55:58.723  3164  3206 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 10 sec
,03-17 12:55:58.743  1022  1506 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.preferences.MusicPreferenceService$MusicPreferenceServiceBinder; callingUser = 0; userId(target) = 0
,03-17 12:55:58.743  1022  1506 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:55:58.743  1022  1506 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:55:58.743  1022  1506 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,03-17 12:55:58.783   257   525 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
03-17 12:55:58.783   257   525 W Vold    : Returning OperationFailed - no handler for errno 0
,03-17 12:55:58.783  4641  4641 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,03-17 12:55:58.783   257   525 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
03-17 12:55:58.783   257   525 W Vold    : Returning OperationFailed - no handler for errno 0
,03-17 12:55:58.783  4641  4641 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,03-17 12:55:58.843  4641  4641 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,03-17 12:55:58.843  4641  4641 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-17 12:55:58.873  4641  4641 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,03-17 12:55:58.923  4641  4641 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,03-17 12:55:58.923  4641  4641 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@9d109fb: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
03-17 12:55:58.923  4641  4641 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
03-17 12:55:58.923  4641  4641 D AndroidMusic: GMSCore installation verified
,03-17 12:55:58.933  4641  4641 I ConfigStore: Config Database version: 1
,03-17 12:55:58.933   289   289 E SMD     : DCD OFF
,03-17 12:55:59.003  1022  1365 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.StorageMigrationService; callingUser = 0; userId(target) = 0
,03-17 12:55:59.003  1022  1365 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:55:59.003  1022  1365 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:55:59.003  1022  1365 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,03-17 12:55:59.013  1022  3133 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.artwork.ArtDownloadService2; callingUser = 0; userId(target) = 0
,03-17 12:55:59.013  1022  3133 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:55:59.023  1022  3133 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:55:59.023  1022  3133 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,03-17 12:55:59.023  1022  1355 E Watchdog: !@Sync 1
,03-17 12:55:59.023  1022  1145 D SettingsProvider: name = audio_safe_volume_state
,03-17 12:55:59.043  1022  1083 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,03-17 12:55:59.043  1022  1506 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,03-17 12:55:59.043  1022  1234 I AudioService: getStreamVolume 3 index 0
,03-17 12:55:59.053  4641  4641 I MediaRouter: Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,03-17 12:55:59.053  4641  4641 V MusicLeanback: onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,03-17 12:55:59.063  4641  4641 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,03-17 12:55:59.083  1022  1035 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,03-17 12:55:59.083  1022  1035 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:55:59.083  1022  1035 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:55:59.083  1022  1035 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,03-17 12:55:59.083  1022  1518 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.ArtDownloadQueueService; callingUser = 0; userId(target) = 0
,03-17 12:55:59.083  1022  1518 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:55:59.083  1022  1518 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:55:59.083  1022  1518 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,03-17 12:55:59.093  1022  3060 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.ArtCacheService; callingUser = 0; userId(target) = 0
,03-17 12:55:59.093  1022  3060 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:55:59.093  1022  3060 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:55:59.093  1022  3060 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,03-17 12:55:59.103  1022  1515 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,03-17 12:55:59.103  1022  1022 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:55:59.103  1022  1022 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:55:59.113  1022  1022 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:59.113  1022  1022 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:55:59.113  4641  4641 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,03-17 12:55:59.123  4668  4668 E Zygote  : MountEmulatedStorage()
,03-17 12:55:59.123  4668  4668 E Zygote  : v2
03-17 12:55:59.123  4668  4668 I libpersona: KNOX_SDCARD checking this for 10002,
,03-17 12:55:59.123  4668  4668 I libpersona: KNOX_SDCARD not a persona
,03-17 12:55:59.123  4668  4668 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-17 12:55:59.123  1022  1022 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=4668 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-17 12:55:59.123  4668  4668 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 12:55:59.133  4668  4668 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 12:55:59.143  4641  4641 I GHttpClientFactory: Using our fixed implementation of GMSCore's GoogleHttpClient
,03-17 12:55:59.143  1022  1515 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,03-17 12:55:59.143  1022  1515 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:55:59.143  1022  1515 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:55:59.143  1022  1515 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,03-17 12:55:59.153  4668  4668 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:55:59.153  4668  4668 D ActivityThread: Added TimaKeyStore provider
,03-17 12:55:59.153  4641  4641 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,03-17 12:55:59.163  1022  1361 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,03-17 12:55:59.163  1022  1361 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:55:59.163  1022  1361 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:55:59.163  1022  1361 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,03-17 12:55:59.163  1022  1515 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 12:55:59.163  1022  1515 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:55:59.163  1022  1515 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 12:55:59.173  1022  1515 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,03-17 12:55:59.193  1022  3133 I ActivityManager: Killing 3986:com.android.managedprovisioning/u0a22 (adj 15): empty #31
,03-17 12:55:59.223  1022  3083 I ActivityManager: Killing 4029:com.sec.android.app.bluetoothtest/1000 (adj 15): empty #31
,03-17 12:55:59.233  1022  1515 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:59.233  1022  1515 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:59.233  1022  1515 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:59.233  1022  1515 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:55:59.243  4687  4687 E Zygote  : MountEmulatedStorage(),
03-17 12:55:59.243  4687  4687 E Zygote  : v2
03-17 12:55:59.243  4687  4687 I libpersona: KNOX_SDCARD checking this for 1000
03-17 12:55:59.243  4687  4687 I libpersona: KNOX_SDCARD not a persona
,03-17 12:55:59.243  4687  4687 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 12:55:59.243  1022  1515 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=4687 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
,03-17 12:55:59.243  4687  4687 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 12:55:59.243  4687  4687 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 12:55:59.263  4687  4687 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:55:59.263  4687  4687 D ActivityThread: Added TimaKeyStore provider
,03-17 12:55:59.273   310   310 I art     : Explicit concurrent mark sweep GC freed 8713(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 717us total 26.913ms
,03-17 12:55:59.293   310   310 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 670us total 19.241ms,
,03-17 12:55:59.303  4687  4687 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,03-17 12:55:59.313   310   310 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 615us total 17.945ms
,03-17 12:55:59.323  1022  1046 W libprocessgroup: failed to open /acct/uid_10022/pid_3986/cgroup.procs: No such file or directory
,03-17 12:55:59.323  1022  1046 W libprocessgroup: failed to open /acct/uid_1000/pid_4029/cgroup.procs: No such file or directory
,03-17 12:55:59.403  4687  4687 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,03-17 12:55:59.413  4687  4687 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,03-17 12:55:59.413  4687  4687 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,03-17 12:55:59.413  4687  4687 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
03-17 12:55:59.413  4687  4687 I DIAGMON_AGENT: ./extraInfo: "NG700"
,03-17 12:55:59.413  4687  4687 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,03-17 12:55:59.473  4406  4415 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,03-17 12:55:59.483  4406  4415 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,03-17 12:55:59.483  4406  4415 I DBG_POLICYDM: [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,03-17 12:55:59.483  4406  4414 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,03-17 12:55:59.483  4406  4414 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,03-17 12:55:59.493  4406  4414 I DBG_POLICYDM: [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,03-17 12:55:59.493  1022  1482 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:55:59.493  1022  1482 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:59.493  1022  1482 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:59.493  1022  1482 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:55:59.503  4704  4704 E Zygote  : MountEmulatedStorage()
03-17 12:55:59.503  4704  4704 E Zygote  : v2
03-17 12:55:59.503  4704  4704 I libpersona: KNOX_SDCARD checking this for 10009
03-17 12:55:59.503  4704  4704 I libpersona: KNOX_SDCARD not a persona
03-17 12:55:59.503  4704  4704 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 12:55:59.513  4704  4704 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 12:55:59.513  4704  4704 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,03-17 12:55:59.513  1022  1482 I ActivityManager: Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=4704 uid=10009 gids={50009, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-17 12:55:59.523  4704  4704 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:55:59.523  4704  4704 D ActivityThread: Added TimaKeyStore provider
,03-17 12:55:59.563  1191  1191 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-17 12:55:59.563  1191  1191 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-17 12:55:59.563  1191  1191 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 12:55:59.563  1191  1191 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 12:55:59.563  1191  1191 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 12:55:59.563  1191  1191 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 12:55:59.593  1022  1518 I ActivityManager: Killing 3371:com.test.thalitest/u0a174 (adj 15): empty #31
,03-17 12:55:59.603  4704  4704 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,03-17 12:55:59.613  4704  4704 W FOTA_Client: [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,03-17 12:55:59.613  1022  1534 I ActivityManager: Killing 4051:com.samsung.android.MtpApplication/1000 (adj 15): empty #31
,03-17 12:55:59.623  3936  3936 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Thu Mar 17 12:55:59 GMT+01:00 2016,
03-17 12:55:59.623  1022  1361 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,03-17 12:55:59.623  1022  1361 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:55:59.623  1022  1361 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-17 12:55:59.623  1022  1361 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,03-17 12:55:59.633  3936  3936 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive().END.
,03-17 12:55:59.633  3936  3936 I KLMS-2.5.183: : KLMSIntentService(): onCreate()
,03-17 12:55:59.643  3936  3936 I KLMS-2.5.183: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,03-17 12:55:59.643  3936  3936 I KLMS-2.5.183: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,03-17 12:55:59.643  3936  4721 I KLMS-2.5.183: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,03-17 12:55:59.653  3936  4721 I KLMS-2.5.183: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,03-17 12:55:59.653  4406  4406 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(53/onReceive)] android.net.conn.CONNECTIVITY_CHANGE
,03-17 12:55:59.653  3936  4721 I KLMS-2.5.183: : KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false| ETHERNET : false
,03-17 12:55:59.653  3936  4721 I KLMS-2.5.183: : StateImplV2(): networkChangeListener().START
,03-17 12:55:59.663  3936  4721 I KLMS-2.5.183: : NetworkChangeOperations(): uploadRequestLog().START 
,03-17 12:55:59.663  4430  4430 I SA      : [OR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOE6 PSS = 4.978878039476607  ]
,03-17 12:55:59.663  4430  4430 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
03-17 12:55:59.663  4430  4430 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,03-17 12:55:59.663  4430  4430 I SA      : [SLFUCHKMGR] constructor called
,03-17 12:55:59.663  4406  4722 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,03-17 12:55:59.663  4406  4722 I DBG_POLICYDM: [com.policydm.XDMApplication(429/isNetworkChanged)] a previous network is 0, current network is 2
,03-17 12:55:59.663  4406  4722 E DBG_POLICYDM: [com.policydm.XDMApplication(431/isNetworkChanged)] network changed.... 
,03-17 12:55:59.673  4430  4430 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
03-17 12:55:59.673  4430  4430 I SA      : [OR] == isSIMCardReady false ==
,03-17 12:55:59.673  3936  4721 I KLMS-2.5.183: : NetworkChangeOperations(): uploadRequestLog().END 
,03-17 12:55:59.673  3936  4721 I KLMS-2.5.183: : StateImplV2(): networkChangeListener().END
,03-17 12:55:59.673  3936  3936 I KLMS-2.5.183: : KLMSIntentService(): onDestroy()
,03-17 12:55:59.683  4406  4722 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
03-17 12:55:59.683  4430  4430 I SA      : [SCU] == networkStateCheck == true
,03-17 12:55:59.683  4430  4430 I SA      : [DM] getCountryCodeFromCSC : PL
03-17 12:55:59.683  4430  4430 I SA      : isChinaCountryCode : false
03-17 12:55:59.683  4430  4430 I SA      : [SCU] is ChinestModel Data Restricted   : false
03-17 12:55:59.683  4430  4430 I SA      : [OR] == networkStateCheck true ==
,03-17 12:55:59.683  4430  4430 I SA      : [OR] GetMyCountryZoneTask
,03-17 12:55:59.683  4430  4430 I SA      : [OR] onReceive END
,03-17 12:55:59.693  1245  1245 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,03-17 12:55:59.693  4406  4722 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,03-17 12:55:59.693  4406  4722 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,03-17 12:55:59.693  1022  3060 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.downloads/com.android.providers.downloads.DownloadService; callingUser = 0; userId(target) = 0
,03-17 12:55:59.693  4406  4722 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,03-17 12:55:59.693  4406  4722 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,03-17 12:55:59.693  1022  3060 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:55:59.693  4406  4722 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,03-17 12:55:59.693  1022  3060 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 12:55:59.693  1022  3060 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,03-17 12:55:59.703  4406  4722 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,03-17 12:55:59.703  4406  4722 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,03-17 12:55:59.703  4406  4722 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(275/xdmExecResumeCase)] Start resumecase for INIT
,03-17 12:55:59.703  4406  4722 I DBG_POLICYDM: [com.policydm.db.XDB(2211/xdbIsAlreadyAgree)] bAgree : true
,03-17 12:55:59.703  4430  4724 I SA      : [SRS] prepareGetMyCountryZone
,03-17 12:55:59.703  1618  1618 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,03-17 12:55:59.713  4406  4722 E DBG_POLICYDM: [com.policydm.db.XDBSpdAdp(36/xdbGetSpdDeviceRegister)] Device is Registered
,03-17 12:55:59.713  4430  4724 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,03-17 12:55:59.713  4430  4724 I SA      : [SSP] query invoked
,03-17 12:55:59.713  1311  2764 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 2
,03-17 12:55:59.713  1618  1618 D accuweather: [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,03-17 12:55:59.713  4430  4724 I SA      : [TPMU] GetMccFromDB : null
,03-17 12:55:59.713  1618  1618 D accuweather: [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
03-17 12:55:59.713  1618  1618 D accuweather: [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
03-17 12:55:59.713  1618  1618 D accuweather: [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,03-17 12:55:59.723  1022  1361 D SecContentProvider2: uri = 15 selection = getAppBlockDownloadState
,03-17 12:55:59.723  1022  1361 D SecContentProvider2: mCursor = null
03-17 12:55:59.723  4430  4724 I SA      : [SCU] getMccFromPreferece mcc = 260
03-17 12:55:59.723  4430  4724 I SA      : [TPM] isNoProxy(default) : true
,03-17 12:55:59.723  4406  4722 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,03-17 12:55:59.723  1618  1618 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,03-17 12:55:59.723  1618  1618 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,03-17 12:55:59.723  4406  4722 I DBG_POLICYDM: [com.policydm.db.XDB(2176/xdbGetWaitWifiFlag)] bWaitWifi : false
,03-17 12:55:59.723  3164  3206 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 11 sec
,03-17 12:55:59.733  1022  1083 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:55:59.733  1022  1083 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:59.733  1022  1083 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:55:59.733  1022  1083 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:55:59.733  4430  4724 E File    : fail readDirectory() errno=2
,03-17 12:55:59.733  1022  1046 W libprocessgroup: failed to open /acct/uid_10174/pid_3371/cgroup.procs: No such file or directory
,03-17 12:55:59.743  4727  4727 E Zygote  : MountEmulatedStorage()
,03-17 12:55:59.743  4727  4727 I libpersona: KNOX_SDCARD checking this for 10125
03-17 12:55:59.743  4727  4727 E Zygote  : v2
03-17 12:55:59.743  4727  4727 I libpersona: KNOX_SDCARD not a persona
03-17 12:55:59.743  4727  4727 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 12:55:59.743  4727  4727 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 12:55:59.753  1022  1083 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=4727 uid=10125 gids={50125, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,03-17 12:55:59.753  4727  4727 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 12:55:59.753  1022  1046 W libprocessgroup: failed to open /acct/uid_1000/pid_4051/cgroup.procs: No such file or directory
,03-17 12:55:59.763  4727  4727 D TimaKeyStoreProvider: TimaSignature is unavailable,
03-17 12:55:59.763  4727  4727 D ActivityThread: Added TimaKeyStore provider
,03-17 12:55:59.783  4727  4727 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,03-17 12:55:59.783  4727  4727 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,03-17 12:55:59.783  4727  4727 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,03-17 12:55:59.813  4727  4727 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,03-17 12:55:59.813  4727  4727 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,03-17 12:55:59.813  4727  4727 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,03-17 12:55:59.823  1022  1518 D RCPManagerService: exchangeData() failure , invalid userId
,03-17 12:55:59.823  1022  3083 D RCPManagerService: exchangeData() failure , invalid userId
,03-17 12:55:59.833  4106  4106 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,03-17 12:55:59.833  4106  4106 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
03-17 12:55:59.833  4106  4106 D SecurityLogAgent: StateMachine : Current State = 1
,03-17 12:55:59.833  4106  4106 D SecurityLogAgent: StateMachine : Changed Current State = 1
,03-17 12:55:59.843  1022  1365 I ActivityManager: Killing 4087:com.sec.android.app.SecSetupWizard/1000 (adj 15): empty #31
,03-17 12:55:59.863  1022  1361 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,03-17 12:55:59.863  1022  1361 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:55:59.863  1022  1361 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 12:55:59.863  1022  1361 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-17 12:55:59.873  1022  1047 I ActivityManager: Waited long enough for: ServiceRecord{235d22b3 u0 com.samsung.android.providers.context/.ContextService}
,03-17 12:55:59.903  1914  4745 I iu.SyncManager: SYNC; picasa accounts
,03-17 12:55:59.933  1914  1914 D NetworkLogImpl: Loaded NetworkSpeedPredictor
,03-17 12:55:59.933  1914  1914 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,03-17 12:55:59.943  1914  4745 I iu.UploadsManager: num queued entries: 0
,03-17 12:55:59.943  1914  4745 I iu.UploadsManager: num updated entries: 0
,03-17 12:55:59.943  1914  4745 I iu.SyncManager: NEXT; no task
,03-17 12:55:59.953  1022  1046 W libprocessgroup: failed to open /acct/uid_1000/pid_4087/cgroup.procs: No such file or directory
,03-17 12:55:59.953  1022  1518 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.snet.SnetAlarmService; callingUser = 0; userId(target) = 0
,03-17 12:55:59.953  1022  1518 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:55:59.953  1022  1518 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 12:55:59.953  1022  1518 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 12:55:59.963  1914  1914 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms,
,03-17 12:55:59.963  1914  1914 I Kids    : [GCoreUtils] Current gmscore version, 7899436 is smaller than the required version 8400000
,03-17 12:55:59.973  1022  1482 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,03-17 12:55:59.973  1022  1482 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:55:59.973  1022  1482 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 12:55:59.973  1022  1482 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk,
,03-17 12:55:59.983  1022  1518 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,03-17 12:55:59.983  1022  1518 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:55:59.983  1022  1518 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:55:59.983  1022  1518 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,03-17 12:55:59.983  4172  4172 E SPPClientService: [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,03-17 12:55:59.983  4172  4172 E SPPClientService: [SystemStateMoniter] Current Time : 50308
,03-17 12:55:59.993  1022  1103 V AlarmManager: waitForAlarm result :8
,03-17 12:55:59.993  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,03-17 12:55:59.993  1191  1191 D KeyguardUpdateMonitor: handleTimeUpdate
,03-17 12:56:00.003  1191  1191 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,03-17 12:56:00.003  3797  4747 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,03-17 12:56:00.003  3797  4747 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
03-17 12:56:00.003  3797  4747 I System.out: (HTTPLog)-Static: isShipBuild true
03-17 12:56:00.003  3797  4747 I System.out: (HTTPLog)-Thread-536-27509614: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
03-17 12:56:00.003  3797  4747 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,03-17 12:56:00.003  1191  1191 D SecKeyguardClockView: HomeTimezone(): 1
,03-17 12:56:00.013   279   926 D EnterpriseController: uids 10104
03-17 12:56:00.013   279   926 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
03-17 12:56:00.013   279   926 D Netd    : getNetworkForDns: using netid 502 for uid 10104
,03-17 12:56:00.013  4172  4172 E SPPClientService: [SystemStateMoniter] No Connect : false
,03-17 12:56:00.013  1022  1234 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:56:00.013  1022  1234 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:56:00.013  1022  1234 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:56:00.013  1022  1234 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:56:00.013  1191  1191 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d,
03-17 12:56:00.013  1191  1191 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
03-17 12:56:00.013  1191  1191 I KeyguardEffectViewController: *** don't update sliding image ***
,03-17 12:56:00.033  4750  4750 E Zygote  : MountEmulatedStorage()
03-17 12:56:00.033  4750  4750 I libpersona: KNOX_SDCARD checking this for 10113
,03-17 12:56:00.033  4750  4750 E Zygote  : v2
03-17 12:56:00.033  4750  4750 I libpersona: KNOX_SDCARD not a persona
,03-17 12:56:00.033  4750  4750 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 12:56:00.033  1022  1234 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4750 uid=10113 gids={50113, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,03-17 12:56:00.033  1618  1618 D accuweather: [KK AccuPhone]>>> WCS:144 [0:0] action : androidintentactionTIME_TICK,
03-17 12:56:00.033  1618  1618 D accuweather: [KK AccuPhone]>>> UIM:119 [0:0] getInstance
03-17 12:56:00.033  1618  1618 D accuweather: [KK AccuPhone]>>> UIM:289 [0:0] direct update clock,
03-17 12:56:00.033  1618  1618 D accuweather: [KK AccuPhone]>>> UIM:158 [0:0] make widget 4x1 view!!! 
03-17 12:56:00.033  1618  1618 D accuweather: [KK AccuPhone]>>> UIM:160 [0:0] make widget 4x2 view!!! 
03-17 12:56:00.043  1618  1618 D accuweather: [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 141span x = 4, span y = 2,
03-17 12:56:00.043  1618  1618 D accuweather: [KK AccuPhone]>>> UIM:1448 [0:0] mc sy = 2
,03-17 12:56:00.043  1618  1618 D accuweather: [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 141span x = 4, span y = 2
03-17 12:56:00.043  1618  1618 D accuweather: [KK AccuPhone]>>> UIM:185 [0:0] get widget 4x2 view!!! wid = 2
03-17 12:56:00.043  4750  4750 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,03-17 12:56:00.043  1618  1618 E accuweather: [KK AccuPhone]>>> UIM:1488 [0:0] bTM 12 56
,03-17 12:56:00.043  4750  4750 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-17 12:56:00.063  4750  4750 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:56:00.063  4750  4750 D ActivityThread: Added TimaKeyStore provider
,03-17 12:56:00.083  3797  4747 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,03-17 12:56:00.083  1191  1191 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-17 12:56:00.083  1191  1191 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-17 12:56:00.093  1191  1191 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-17 12:56:00.093  1022  1047 I ActivityManager: Waited long enough for: ServiceRecord{1031339c u0 com.android.settings/.wifi.WifiCredService}
,03-17 12:56:00.103  1519  1760 W OpenGLRenderer: SFEffectCache::get: create texture(0xa0949724): name, size, mSize = 39, 145188, 317256
,03-17 12:56:00.113  1191  1191 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-17 12:56:00.123  1022  1063 D PackageManager: [MSG] SEND_PENDING_BROADCAST
,03-17 12:56:00.163  1022  1110 I InputReader: Reconfiguring input devices.  changes=0x00000010
,03-17 12:56:00.163  3563  3563 I PageBuddyNotiSvc: mCPBroadcastReceiver action=android.intent.action.PACKAGE_CHANGED mCpBitFlag=0
,03-17 12:56:00.163  1473  1473 D RegisteredComponentCache: Collect Tech packages for Knox
,03-17 12:56:00.173  1473  1473 D PersonaManager: isKioskContainerExistOnDevice
,03-17 12:56:00.173  1022  1046 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 12:56:00.173  1473  1473 D PersonaManager: isKioskContainerExistOnDevice
,03-17 12:56:00.183  1473  1473 D RegisteredServicesCache: empty dynamic service
,03-17 12:56:00.203  1022  1046 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 12:56:00.213  1022  1046 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 12:56:00.213  3797  4747 I Babel   : connection state changed from UNKNOWN to CONNECTED
,03-17 12:56:00.223  1022  1046 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 12:56:00.223  1022  1083 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
,03-17 12:56:00.223  1022  1083 D SecContentProvider2: mCursor = null
,03-17 12:56:00.303  1519  1519 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,03-17 12:56:00.303  1519  1519 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,03-17 12:56:00.343  1022  1046 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,03-17 12:56:00.343  1022  1046 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 12:56:00.343  1022  1046 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 12:56:00.353  1022  1046 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 12:56:00.353  1022  1046 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-17 12:56:00.353  1022  1046 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-17 12:56:00.353  1022  1046 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-17 12:56:00.353  1022  1046 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 12:56:00.373  1022  1022 W IntentResolver: resolveIntent: multiple matches, only some with CATEGORY_DEFAULT
,03-17 12:56:00.383  1022  1022 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,03-17 12:56:00.383  1022  1022 I BackupManagerService: Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,03-17 12:56:00.383  1022  1022 I BackupManagerService: Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
03-17 12:56:00.383  1022  1046 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-17 12:56:00.383  1022  1022 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.backup.BackupTransportService; callingUser = 0; userId(target) = 0
,03-17 12:56:00.383  1022  1046 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 12:56:00.383  1022  1046 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-17 12:56:00.383  1022  1046 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,03-17 12:56:00.383  1022  1046 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 12:56:00.393  1022  1046 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-17 12:56:00.393  1022  1046 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,03-17 12:56:00.393  1022  1046 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-17 12:56:00.393  1022  1022 V BackupManagerService: Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,03-17 12:56:00.393  1022  1022 V BackupManagerService: Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@219498fc
03-17 12:56:00.393  1022  1046 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,03-17 12:56:00.393  1022  1046 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 12:56:00.413  1022  1046 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = -2
,03-17 12:56:00.413  1022  1046 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = -2
,03-17 12:56:00.413  1022  1046 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = -2
,03-17 12:56:00.433  1022  1046 D LocationProviderProxy: applying state to connected service
,03-17 12:56:00.463  4750  4750 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
03-17 12:56:00.463  4750  4750 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
03-17 12:56:00.463  4750  4750 I GAv4    :   adb logcat -s GAv4
,03-17 12:56:00.483   257   525 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
03-17 12:56:00.483   257   525 W Vold    : Returning OperationFailed - no handler for errno 0
,03-17 12:56:00.483  4750  4770 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,03-17 12:56:00.483   257   525 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
03-17 12:56:00.483   257   525 W Vold    : Returning OperationFailed - no handler for errno 0
,03-17 12:56:00.483  4750  4770 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,03-17 12:56:00.483  4750  4750 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,03-17 12:56:00.503  4750  4750 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,03-17 12:56:00.513   257   525 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
03-17 12:56:00.513   257   525 W Vold    : Returning OperationFailed - no handler for errno 0
,03-17 12:56:00.513  4750  4772 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,03-17 12:56:00.513  4750  4773 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,03-17 12:56:00.513   257   525 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
03-17 12:56:00.513   257   525 W Vold    : Returning OperationFailed - no handler for errno 0
,03-17 12:56:00.523  4750  4772 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,03-17 12:56:00.563  1191  1191 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-17 12:56:00.563  1191  1191 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-17 12:56:00.563  1191  1191 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 12:56:00.563  1191  1191 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 12:56:00.563  1191  1191 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 12:56:00.563  1191  1191 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 12:56:00.563  4430  4724 I SA      : [RC New] Execute method=[GET] start
,03-17 12:56:00.573  1022  1103 V AlarmManager: waitForAlarm result :4
,03-17 12:56:00.593  4430  4724 I SA      : [RC New] Security=[true]
,03-17 12:56:00.593  4430  4724 I System.out: Thread-685(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,03-17 12:56:00.593  4430  4724 I System.out: Thread-685(ApacheHTTPLog):isSBSettingEnabled false
03-17 12:56:00.593  4430  4724 I System.out: Thread-685(ApacheHTTPLog):isShipBuild true
03-17 12:56:00.593  4430  4724 I System.out: Thread-685(ApacheHTTPLog):SMARTBONDING_ENABLED is false
03-17 12:56:00.593  4430  4724 I System.out: Thread-685(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,03-17 12:56:00.603   279   926 D EnterpriseController: uids 10041
03-17 12:56:00.603   279   926 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
03-17 12:56:00.603   279   926 D Netd    : getNetworkForDns: using netid 502 for uid 10041
,03-17 12:56:00.723  1022  3083 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 12:56:00.723  1022  3083 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:56:00.723  1022  3083 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 12:56:00.723  1022  3083 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,03-17 12:56:00.733  3164  3206 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 12 sec
,03-17 12:56:00.753  4750  4750 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
,03-17 12:56:00.763  4750  4750 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 1086-1088)
03-17 12:56:00.763  4750  4750 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-17 12:56:00.783  4750  4750 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {d783059}
,03-17 12:56:00.793  4750  4750 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-17 12:56:00.793  4750  4750 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,03-17 12:56:00.803  4750  4750 I BrowserStartupController: Initializing chromium process, singleProcess=true
,03-17 12:56:00.803  4750  4750 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-17 12:56:00.803  4750  4750 E SysUtils: ApplicationContext is null in ApplicationStatus
,03-17 12:56:00.823  4750  4750 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,03-17 12:56:00.823  4750  4750 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,03-17 12:56:00.823  4750  4750 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,03-17 12:56:00.833  4750  4750 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
03-17 12:56:00.833  4750  4750 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
03-17 12:56:00.833  4750  4750 I Adreno-EGL: Build Date: 04/06/15 Mon
03-17 12:56:00.833  4750  4750 I Adreno-EGL: Local Branch: 
03-17 12:56:00.833  4750  4750 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
03-17 12:56:00.833  4750  4750 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
03-17 12:56:00.833  4750  4750 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,03-17 12:56:00.883  4750  4804 W AudioManagerAndroid: Requires BLUETOOTH permission
,03-17 12:56:00.893  4750  4750 I NSApplication: Starting up...
,03-17 12:56:00.913  1022  1361 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:56:00.913  1022  1361 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:56:00.913  1022  1361 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:56:00.913  1022  1361 E ActivityManager: checkUser: useridlist=null, currentuser=0,
,03-17 12:56:00.923  4809  4809 E Zygote  : MountEmulatedStorage(),
03-17 12:56:00.923  4809  4809 E Zygote  : v2
03-17 12:56:00.923  4809  4809 I libpersona: KNOX_SDCARD checking this for 10081,
03-17 12:56:00.923  4809  4809 I libpersona: KNOX_SDCARD not a persona
,03-17 12:56:00.933  1022  1361 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=4809 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-17 12:56:00.933  4809  4809 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-17 12:56:00.933  1022  1361 I ActivityManager: Killing 4069:com.sec.knox.bridge/1000 (adj 15): empty #31
,03-17 12:56:00.933  4809  4809 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 12:56:00.933  4809  4809 E SELinux : [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,03-17 12:56:00.963  4809  4809 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:56:00.963  4809  4809 D ActivityThread: Added TimaKeyStore provider
,03-17 12:56:01.143  1022  1046 W libprocessgroup: failed to open /acct/uid_1000/pid_4069/cgroup.procs: No such file or directory
,03-17 12:56:01.163  1022  1506 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:56:01.163  1022  1506 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:56:01.163  1022  1506 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:56:01.163  1022  1506 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:56:01.173  4826  4826 E Zygote  : MountEmulatedStorage(),
03-17 12:56:01.173  4826  4826 E Zygote  : v2
,03-17 12:56:01.173  4826  4826 I libpersona: KNOX_SDCARD checking this for 10120
,03-17 12:56:01.173  4826  4826 I libpersona: KNOX_SDCARD not a persona
,03-17 12:56:01.183  4826  4826 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 12:56:01.183  4826  4826 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 12:56:01.183  1022  1506 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=4826 uid=10120 gids={50120, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,03-17 12:56:01.183  4826  4826 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-17 12:56:01.183  1022  1506 I ActivityManager: Killing 4133:com.samsung.android.provider.shootingmodeprovider/u0a152 (adj 15): empty #31
,03-17 12:56:01.203  4826  4826 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:56:01.213  4826  4826 D ActivityThread: Added TimaKeyStore provider
,03-17 12:56:01.223  4826  4826 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,03-17 12:56:01.293  1022  1046 W libprocessgroup: failed to open /acct/uid_10152/pid_4133/cgroup.procs: No such file or directory
,03-17 12:56:01.333  4430  4724 I SA      : [RC New] [v2liruge] api execute + 738
,03-17 12:56:01.333  4430  4724 I SA      : [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
03-17 12:56:01.333  4430  4724 I System.out: AsyncTask #1 calls detatch()
,03-17 12:56:01.373  1022  3060 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
,03-17 12:56:01.373  1022  3060 W ActivityManager: userId = 0, bbcId = -10000,
03-17 12:56:01.373  1022  3060 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:56:01.373  1022  3060 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,03-17 12:56:01.403  4485  4508 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,03-17 12:56:01.423  4430  4724 I SA      : [ODM] saveOpenData( GEO_IP, PL ),
,03-17 12:56:01.443  4430  4724 I SA      : [OCP] update openData : PL
,03-17 12:56:01.443  4430  4724 I SA      : [TPMU] getNetworkMcc : 
,03-17 12:56:01.443  4430  4724 I SA      : [SCU] saveMccToPreferece Start
,03-17 12:56:01.443  4430  4724 I SA      : [SCU] RegionMCC : 260
03-17 12:56:01.443  4430  4724 I SA      : [SSP] query invoked
,03-17 12:56:01.443  4430  4724 I SA      : [TPMU] GetMccFromDB : null
,03-17 12:56:01.443  4430  4724 I SA      : [SCU] getMccFromPreferece mcc = 260
03-17 12:56:01.443  4430  4724 I SA      : [SCU] saveMccToPreferece End
,03-17 12:56:01.443  4430  4724 I SA      : [RC New] executeRequest [v2liruge] end. 881
03-17 12:56:01.443  4430  4724 I SA      : [RC New] Execute end
,03-17 12:56:01.453  4430  4430 I SA      : [OR] GetMyCountryZoneTask mcc = 260
03-17 12:56:01.453  4430  4430 I SA      : [OR] GetMyCountryZoneTask Success
,03-17 12:56:01.633  1022  3059 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:56:01.633  1022  3059 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:56:01.633  1022  3059 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:56:01.633  1022  3059 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:56:01.643  4848  4848 E Zygote  : MountEmulatedStorage()
,03-17 12:56:01.643  4848  4848 E Zygote  : v2
03-17 12:56:01.643  4848  4848 I libpersona: KNOX_SDCARD checking this for 10010
03-17 12:56:01.643  4848  4848 I libpersona: KNOX_SDCARD not a persona
,03-17 12:56:01.643  4848  4848 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,03-17 12:56:01.643  4848  4848 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
03-17 12:56:01.643  1022  3059 I ActivityManager: Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=4848 uid=10010 gids={50010, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,03-17 12:56:01.653  4848  4848 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL,
03-17 12:56:01.653  1022  3059 I ActivityManager: Killing 4159:com.sec.modem.settings/1000 (adj 15): empty #31,
,03-17 12:56:01.673  4848  4848 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:56:01.673  4848  4848 D ActivityThread: Added TimaKeyStore provider
,03-17 12:56:01.733  3164  3206 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 13 sec
,03-17 12:56:01.753  1022  1046 W libprocessgroup: failed to open /acct/uid_1000/pid_4159/cgroup.procs: No such file or directory
,03-17 12:56:01.793  1022  3133 D PowerManagerService: [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 1022) eventTime = 52115,
03-17 12:56:01.793  1022  3133 D PowerManagerService: [s] UserActivityState : 2 -> 1
03-17 12:56:01.793  1022  3133 D PowerManagerService: [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1022 (0x0)
,03-17 12:56:01.793  1022  3133 D PowerManagerService: [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=1022, ws=WorkSource{10054}) (elapsedTime=3479)
,03-17 12:56:01.813  4848  4848 D WaitQueueForNetworkActivate: notifyNetworkActivated
,03-17 12:56:01.873  4848  4848 W ContextImpl: Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,03-17 12:56:01.873  1022  1482 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 12:56:01.873  1022  1482 W ActivityManager: Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,03-17 12:56:01.933   289   289 E SMD     : DCD OFF
,03-17 12:56:02.023  1022  3133 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.app.samsungapps/com.sec.android.app.samsungapps.autoupdateservice.AutoUpdateService; callingUser = 0; userId(target) = 0
,03-17 12:56:02.023  1022  3133 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:56:02.023  1022  3133 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
03-17 12:56:02.023  1022  3133 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,03-17 12:56:02.023  4848  4848 D hcjo    : AutoUpdateManager:IDLE:execute
,03-17 12:56:02.033  1022  1022 I splitIntent: Split this intent : android.intent.action.TIME_SET, mSplitNum[0]=7, mSplitNum[1]=12, mSplitNum[2]=17, mBgSplitQueueNum=3 divideNum= 5 r.nextReceiver= 1 receivers.size=23
,03-17 12:56:02.033  1022  1022 I splitIntent: finish to split intent : android.intent.action.TIME_SET !! Enqueue -> schedule it!!
,03-17 12:56:02.033  4848  4848 D InitializeManagerStateMachine: execute::IDLE:EXECUTE
,03-17 12:56:02.033  4848  4848 D InitializeManagerStateMachine: exit::IDLE
03-17 12:56:02.033  4848  4848 D InitializeManagerStateMachine: entry::NETWORK_CHECK
,03-17 12:56:02.043  1022  1047 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:56:02.043  1022  1047 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:56:02.043  1022  1047 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:56:02.043  1022  1047 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:56:02.043  4848  4848 D InitializeManagerStateMachine: execute::NETWORK_CHECK:NETWORK_STATE_OK
03-17 12:56:02.043  4848  4848 D InitializeManagerStateMachine: exit::NETWORK_CHECK
03-17 12:56:02.043  4848  4848 D InitializeManagerStateMachine: entry::CHECK_COUNTRY_INFO
03-17 12:56:02.043  4848  4848 D InitializeManagerStateMachine: execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
03-17 12:56:02.043  4848  4848 D InitializeManagerStateMachine: exit::CHECK_COUNTRY_INFO
03-17 12:56:02.043  4848  4848 D InitializeManagerStateMachine: entry::SUCCESS
03-17 12:56:02.043  4848  4848 D hcjo    : AutoUpdateManager:INITCHECK:onInitializeSuccess
,03-17 12:56:02.053  4868  4868 E Zygote  : MountEmulatedStorage()
,03-17 12:56:02.053  4868  4868 E Zygote  : v2
03-17 12:56:02.053  4868  4868 I libpersona: KNOX_SDCARD checking this for 10062
,03-17 12:56:02.053  4868  4868 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
03-17 12:56:02.053  4868  4868 I libpersona: KNOX_SDCARD not a persona
03-17 12:56:02.053  1022  1047 I ActivityManager: Start proc com.samsung.android.scloud.sync for broadcast com.samsung.android.scloud.sync/com.sec.android.sCloudSync.Receivers.TimeChangedReceiver: pid=4868 uid=10062 gids={50062, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-17 12:56:02.053  1022  1047 E ActivityManager: checkUser: useridlist=null, currentuser=0,
03-17 12:56:02.053  1022  1047 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:56:02.053  1022  1047 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:56:02.053  1022  1047 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:56:02.063  4868  4868 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 12:56:02.063  4868  4868 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,03-17 12:56:02.083  4877  4877 E Zygote  : MountEmulatedStorage()
,03-17 12:56:02.083  4877  4877 I libpersona: KNOX_SDCARD checking this for 10135
03-17 12:56:02.083  4877  4877 E Zygote  : v2
03-17 12:56:02.083  4877  4877 I libpersona: KNOX_SDCARD not a persona
03-17 12:56:02.083  4877  4877 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 12:56:02.093  4877  4877 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,03-17 12:56:02.093  4877  4877 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 12:56:02.093  1022  1047 I ActivityManager: Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=4877 uid=10135 gids={50135, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
03-17 12:56:02.093  4868  4868 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:56:02.093  4868  4868 D ActivityThread: Added TimaKeyStore provider
03-17 12:56:02.093  4848  4848 D hcjo    : AutoUpdateTriggerManager:IDLE:setInterval:345600000
,03-17 12:56:02.103  4704  4704 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,03-17 12:56:02.113  4848  4848 D hcjo    : AutoUpdateTriggerManager:IDLE:notifyNextTime
03-17 12:56:02.113  4848  4848 D hcjo    : AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,03-17 12:56:02.113  4848  4848 D InitializeManagerStateMachine: exit::SUCCESS
03-17 12:56:02.113  4848  4848 D InitializeManagerStateMachine: entry::IDLE
,03-17 12:56:02.113  1311  1311 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,03-17 12:56:02.113  1311  1311 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
03-17 12:56:02.113  1311  1311 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,03-17 12:56:02.123  1311  1311 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,03-17 12:56:02.123  4877  4877 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:56:02.123  4877  4877 D ActivityThread: Added TimaKeyStore provider
,03-17 12:56:02.123  1311  1311 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,03-17 12:56:02.133  1311  1311 D daemonapp: [MSC_Daemon]>>> WDSM:54 [0:0] Act : androidintentactionTIME_SET, run:true
,03-17 12:56:02.133  1311  1311 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
03-17 12:56:02.133  1311  1311 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
,03-17 12:56:02.133  1311  1311 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
03-17 12:56:02.133  1311  1311 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
03-17 12:56:02.133  1311  1311 D daemonapp: [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
,03-17 12:56:02.133  1311  1311 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,03-17 12:56:02.133  4704  4704 I FOTA_Client: [com.sec.android.fota.osp.time.ServerTimeReceiver(47/onReceive)] No action is available before server time settings
,03-17 12:56:02.133  1311  1311 D daemonapp: [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
,03-17 12:56:02.143  1022  1361 I ActivityManager: Killing 4214:org.simalliance.openmobileapi.service/1101 (adj 15): empty #31
,03-17 12:56:02.143  1311  1311 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
03-17 12:56:02.143  1311  1311 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,03-17 12:56:02.143  1311  1311 D daemonapp: [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
,03-17 12:56:02.143  3936  3936 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.samsung.klmsagent/.listner.MainReciver } | timestamp: Thu Mar 17 12:56:02 GMT+01:00 2016
03-17 12:56:02.143  1022  1506 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,03-17 12:56:02.143  1022  1506 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:56:02.143  1022  1506 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 12:56:02.143  1022  1506 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
03-17 12:56:02.143  1311  1311 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,03-17 12:56:02.153  3936  3936 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive().END.
,03-17 12:56:02.153  4877  4877 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-17 12:56:02.153  4877  4877 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-17 12:56:02.153  4877  4877 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-17 12:56:02.153  1311  1311 E daemonapp: [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
03-17 12:56:02.153  4430  4430 I SA      : [SBR] StdBroadcastReceiver received Intent of  action.TIME_SET.
,03-17 12:56:02.163  3936  3936 I KLMS-2.5.183: : KLMSIntentService(): onCreate()
,03-17 12:56:02.163  3936  3936 I KLMS-2.5.183: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,03-17 12:56:02.163  1311  1311 D comdaemonstockapp: [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] onReceive: androidintentactionTIME_SET
,03-17 12:56:02.163  1311  1311 D comdaemonstockapp: [Daemon_Stock]>>> StockclockDaemonService.java:62 [0:0] appServiceStatus: 0
,03-17 12:56:02.173  4868  4868 I ExternalOEMControlProvider: onCreate
,03-17 12:56:02.173  3936  3936 I KLMS-2.5.183: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,03-17 12:56:02.173  3936  4899 I KLMS-2.5.183: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService }
,03-17 12:56:02.183  1618  1618 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidintentactionTIME_SET
,03-17 12:56:02.183  1022  1234 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.checkin.CheckinService; callingUser = 0; userId(target) = 0
,03-17 12:56:02.183  1022  1234 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:56:02.183  1022  1234 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:56:02.183  1022  1234 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-17 12:56:02.183  1618  1618 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,03-17 12:56:02.183  3936  4899 I KLMS-2.5.183: : KLMSIntentService(): TIME_CHANGED
,03-17 12:56:02.193  1022  1035 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:56:02.193  1022  1035 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:56:02.193  1022  1035 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:56:02.193  1022  1035 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:56:02.193  3936  4899 I KLMS-2.5.183: : StateImplV2(): dateTimeChanged().START : Thu Mar 17 12:56:02 GMT+01:00 2016
,03-17 12:56:02.203  4901  4901 E Zygote  : MountEmulatedStorage()
,03-17 12:56:02.203  4901  4901 E Zygote  : v2
03-17 12:56:02.203  4901  4901 I libpersona: KNOX_SDCARD checking this for 10085
03-17 12:56:02.203  4901  4901 I libpersona: KNOX_SDCARD not a persona
,03-17 12:56:02.203  4901  4901 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 12:56:02.203  3936  4899 I KLMS-2.5.183: : StateImplV2(): dateTimeChanged().END,
03-17 12:56:02.213  1022  1035 I ActivityManager: Start proc com.sec.android.app.clockpackage for broadcast com.sec.android.app.clockpackage/.alarm.AlarmReceiver: pid=4901 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-17 12:56:02.213  4901  4901 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-17 12:56:02.213  4901  4901 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 12:56:02.213  3936  3936 I KLMS-2.5.183: : KLMSIntentService(): onDestroy()
,03-17 12:56:02.223  1022  1035 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:56:02.223  1022  1035 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:56:02.223  1022  1035 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:56:02.223  1022  1035 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:56:02.233  4915  4915 E Zygote  : MountEmulatedStorage(),
03-17 12:56:02.233  4915  4915 I libpersona: KNOX_SDCARD checking this for 10046
03-17 12:56:02.233  4915  4915 E Zygote  : v2
03-17 12:56:02.233  4915  4915 I libpersona: KNOX_SDCARD not a persona
03-17 12:56:02.233  4915  4915 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 12:56:02.233  1022  1035 I ActivityManager: Start proc com.android.mms for broadcast com.android.mms/.transaction.MessagingNotification: pid=4915 uid=10046 gids={50046, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
03-17 12:56:02.233  4915  4915 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 12:56:02.243  1022  1035 I ActivityManager: Killing 1596:com.sec.android.provider.badge/u0a72 (adj 15): empty #31,
03-17 12:56:02.243  4901  4901 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 12:56:02.243  4915  4915 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
03-17 12:56:02.243  4901  4901 D ActivityThread: Added TimaKeyStore provider
03-17 12:56:02.243  1022  3059 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
,03-17 12:56:02.253  1311  1327 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,03-17 12:56:02.253  1022  3059 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:56:02.253  1022  3059 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 12:56:02.253  1022  3059 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,03-17 12:56:02.273  4915  4915 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:56:02.273  4915  4915 D ActivityThread: Added TimaKeyStore provider
,03-17 12:56:02.283  4901  4901 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
03-17 12:56:02.283  4901  4901 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,03-17 12:56:02.283  4901  4901 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-17 12:56:02.283  4901  4901 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
03-17 12:56:02.283  4901  4901 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 12:56:02.283  4901  4901 W ResourcesManager: Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
,03-17 12:56:02.293  1022  1365 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
,03-17 12:56:02.293  1022  1365 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:56:02.293  1022  1365 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 12:56:02.293  1022  1365 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,03-17 12:56:02.313  4915  4915 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,03-17 12:56:02.313  4915  4915 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-17 12:56:02.313  4915  4915 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
03-17 12:56:02.313  4915  4915 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-17 12:56:02.313  4915  4915 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,03-17 12:56:02.313  4915  4915 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,03-17 12:56:02.323  4106  4106 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,03-17 12:56:02.323  1022  1482 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.reminders.notification.NotificationService; callingUser = 0; userId(target) = 0
,03-17 12:56:02.323  1022  1482 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:56:02.323  1022  1482 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:56:02.323  1022  1482 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 12:56:02.323  4106  4106 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
03-17 12:56:02.323  4106  4106 D SecurityLogAgent: StateMachine : Current State = 1
,03-17 12:56:02.343  1022  1046 W libprocessgroup: failed to open /acct/uid_1101/pid_4214/cgroup.procs: No such file or directory
,03-17 12:56:02.343  1022  1046 W libprocessgroup: failed to open /acct/uid_10072/pid_1596/cgroup.procs: No such file or directory
,03-17 12:56:02.373   258  1108 I SurfaceFlinger: id=13 Removed Uoast (8/8),
03-17 12:56:02.373   258   435 I SurfaceFlinger: id=13 Removed Uoast (-2/8)
,03-17 12:56:02.373  1022  1506 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:56:02.373  1022  1506 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:56:02.373  1022  1506 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:56:02.373  1022  1506 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:56:02.393  1022  1361 I art     : Explicit concurrent mark sweep GC freed 33722(1925KB) AllocSpace objects, 3(68KB) LOS objects, 33% free, 30MB/45MB, paused 3.856ms total 208.925ms
,03-17 12:56:02.393  4940  4940 E Zygote  : MountEmulatedStorage()
03-17 12:56:02.393  4940  4940 E Zygote  : v2
03-17 12:56:02.393  4940  4940 I libpersona: KNOX_SDCARD checking this for 1000
03-17 12:56:02.393  4940  4940 I libpersona: KNOX_SDCARD not a persona
,03-17 12:56:02.393  4940  4940 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 12:56:02.403  4940  4940 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,03-17 12:56:02.403  4940  4940 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 12:56:02.403  1022  1506 I ActivityManager: Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=4940 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-17 12:56:02.423   310   310 I art     : Explicit concurrent mark sweep GC freed 8697(370KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 643us total 21.715ms,
,03-17 12:56:02.433  4868  4900 I  Time Manager : Time Difference not stored. TIME_DIFFERENCE
,03-17 12:56:02.443   310   310 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 612us total 18.748ms
,03-17 12:56:02.443  4940  4940 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:56:02.443  4940  4940 D ActivityThread: Added TimaKeyStore provider
,03-17 12:56:02.453  1022  3060 D SettingsProvider: name = next_alarm_formatted
,03-17 12:56:02.453  1022  3060 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-17 12:56:02.453  1022  3060 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-17 12:56:02.453  1022  3060 D SettingsProvider: selectionArgs: false
03-17 12:56:02.453  1022  3060 D SettingsProvider: selectionArgs: 10085
03-17 12:56:02.453  1022  3060 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-17 12:56:02.453  1022  3060 D SettingsProvider: ret = -1
,03-17 12:56:02.463   310   310 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 633us total 20.350ms
,03-17 12:56:02.493  4520  4574 I System.out: Thread-705(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,03-17 12:56:02.493  4520  4574 I System.out: Thread-705(ApacheHTTPLog):isSBSettingEnabled false
03-17 12:56:02.493  4520  4574 I System.out: Thread-705(ApacheHTTPLog):isShipBuild true
03-17 12:56:02.493  4520  4574 I System.out: Thread-705(ApacheHTTPLog):SMARTBONDING_ENABLED is false
03-17 12:56:02.493  4520  4574 I System.out: Thread-705(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,03-17 12:56:02.493   279   926 D EnterpriseController: uids 10092
03-17 12:56:02.493   279   926 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
03-17 12:56:02.493   279   926 D Netd    : getNetworkForDns: using netid 502 for uid 10092
03-17 12:56:02.493  1022  3060 I ActivityManager: Killing 4186:com.vlingo.midas/u0a31 (adj 15): empty #31
,03-17 12:56:02.503  4915  4915 D Mms/MmsApp: [start]    onCreate() consume time = 0.0
,03-17 12:56:02.513  4940  4940 D TimeService: Receivedandroid.intent.action.TIME_SET intent. Current Time is 1458215762518
,03-17 12:56:02.513  4940  4940 D         : TimeServiceNative: User Time to be set is 1458215762518
03-17 12:56:02.513  4940  4940 D QC-time-services: Lib:time_genoff_operation: pargs->base = 2
,03-17 12:56:02.513  4940  4940 D QC-time-services: Lib:time_genoff_operation: pargs->operation = 0
03-17 12:56:02.513  4940  4940 D QC-time-services: Lib:time_genoff_operation: pargs->ts_val = 1458215762518
,03-17 12:56:02.513   321   425 D QC-time-services: Daemon: Connection accepted:time_genoff
,03-17 12:56:02.513   321  4958 D QC-time-services: Daemon:Received base = 2, unit = 1, operation = 0,value = 1458215762518
03-17 12:56:02.513   321  4958 D QC-time-services: Daemon:genoff_opr: Base = 2, val = 1458215762518, operation = 0,
03-17 12:56:02.513   321  4958 D QC-time-services: Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS8/8/70 3:9:38
03-17 12:56:02.513   321  4958 D QC-time-services: Daemon:Value read from RTC seconds = 21611378000,
03-17 12:56:02.513   321  4958 D QC-time-services: Daemon:new time 1458215762518 
03-17 12:56:02.513   321  4958 D QC-time-services: Daemon: delta 1436604384518 genoff 1436604384518 
03-17 12:56:02.513   321  4958 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1436604384518 to memory,
03-17 12:56:02.513   321  4958 D QC-time-services: Daemon:Opening File: /data/time/ats_2
03-17 12:56:02.513   321  4958 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
03-17 12:56:02.513  4940  4940 D QC-time-services: Lib:time_genoff_operation: Send to server  passed!!
,03-17 12:56:02.553   321  4958 D QC-time-services: Updating the TOD offset
03-17 12:56:02.553   321  4958 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1436604384518 to memory
03-17 12:56:02.553   321  4958 D QC-time-services: Daemon:Opening File: /data/time/ats_1
03-17 12:56:02.553   321  4958 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,03-17 12:56:02.563   321  4958 E QC-time-services: Daemon:Update to modem bit set
03-17 12:56:02.563   321  4958 D QC-time-services: Daemon:genoff_send_modem: Sending data to MODEM !
03-17 12:56:02.563   321  4958 D QC-time-services: Daemon: Base = 2, Value being sent to MODEM = 1120639584518
,03-17 12:56:02.573  4940  4940 E QC-time-services: Receive Passed == base = 2, unit = 1, operation = 0, result = 0,
03-17 12:56:02.573  1022  1518 I ActivityManager: Killing 4357:com.google.android.gms:car/u0a12 (adj 15): empty #31
,03-17 12:56:02.573   321   420 E QC-time-services: Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
03-17 12:56:02.573   321   425 E QC-time-services: Daemon: Time-services: Waiting to acceptconnection
,03-17 12:56:02.603  1022  1046 W libprocessgroup: failed to open /acct/uid_10031/pid_4186/cgroup.procs: No such file or directory
,03-17 12:56:02.643  4901  4901 W art     : Verification of void com.sec.android.app.clockpackage.alarm.Alarm.InitAlarmList() took 101.502ms
,03-17 12:56:02.683  1022  3083 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:56:02.683  1022  3083 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:56:02.683  1022  3083 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:56:02.683  1022  3083 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:56:02.693  4959  4959 E Zygote  : MountEmulatedStorage()
03-17 12:56:02.693  4959  4959 E Zygote  : v2
03-17 12:56:02.693  4959  4959 I libpersona: KNOX_SDCARD checking this for 10094
03-17 12:56:02.693  4959  4959 I libpersona: KNOX_SDCARD not a persona
03-17 12:56:02.693  4959  4959 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 12:56:02.693  4915  4915 D Mms/TelephonyPermission: start operation mode monitor,
03-17 12:56:02.693  1022  3083 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=4959 uid=10094 gids={50094, 9997, 3003} abi=armeabi-v7a
,03-17 12:56:02.693  1022  3083 I ActivityManager: Killing 4267:com.google.android.youtube/u0a166 (adj 15): empty #31
,03-17 12:56:02.703  4959  4959 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 12:56:02.703  4915  4962 D Mms/ArtClassLoader: init before art
,03-17 12:56:02.703  4959  4959 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 12:56:02.713  4915  4915 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-17 12:56:02.713  4915  4915 D Mms/TelephonyPermission: DefaultSmsApp is com.android.mms
03-17 12:56:02.713  4915  4915 D Mms/TelephonyPermission: isDefault true
03-17 12:56:02.713  1022  1518 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.car.InCallServiceImpl in 1000ms
,03-17 12:56:02.713  4959  4959 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:56:02.723  4915  4915 D Mms/MmsApp: onCreate() com.android.mms
,03-17 12:56:02.723  4959  4959 D ActivityThread: Added TimaKeyStore provider
,03-17 12:56:02.733  4915  4915 D Mms/MmsApp: [start]    initCountryIso consume time = 234.651823
,03-17 12:56:02.733  3164  3206 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 14 sec
,03-17 12:56:02.733  1022  1083 D CountryDetector: The first listener is added
,03-17 12:56:02.743  4915  4915 D Mms/MmsApp: [end]    initCountryIso consume time = 6.780729
03-17 12:56:02.743  4915  4915 D Mms/MmsConfig: [start]    MmsConfig.init() consume time = 0.101563
,03-17 12:56:02.743  4959  4959 D elm:15183: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver }
,03-17 12:56:02.753  4959  4959 D elm:15183: ELMEngine.ELMEngine( context ).
,03-17 12:56:02.753  4959  4959 D elm:15183: MDMBridge.setEnterpriseBridge()
03-17 12:56:02.753  4915  4915 D Mms/MmsConfig: before partial update
,03-17 12:56:02.753  1022  1234 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,03-17 12:56:02.753  1022  1234 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:56:02.753  1022  1234 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 12:56:02.753  1022  1234 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,03-17 12:56:02.753  4959  4959 D elm:15183: ELMAbstractReceiver : Receive Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService } END.
,03-17 12:56:02.763  1022  1034 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:56:02.763  1022  1034 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:56:02.763  1022  1034 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:56:02.763  1022  1034 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:56:02.763  4959  4959 D elm:15183: ElmAgentService : onCreate()
,03-17 12:56:02.763  4959  4977 D elm:15183: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService }
03-17 12:56:02.763  4959  4977 D elm:15183: ELMAgentService.listeningToTimeDateChanges( context, intent ).
03-17 12:56:02.763  4959  4959 D elm:15183: ELMEngine.ServiceHandler.handleMessage( ALARM_MODIFY ). 
03-17 12:56:02.763  4959  4959 D elm:15183: ModuleBase.ModifySetAlarm()
03-17 12:56:02.763  4959  4959 D elm:15183: MDMBridge.getInstance()
03-17 12:56:02.763  4959  4959 D elm:15183: MDMBridge.getAllLicenseInfoFromSDK()
,03-17 12:56:02.773  4915  4915 D Mms/MmsConfig: Load Resize quality : 80
,03-17 12:56:02.773  4979  4979 E Zygote  : MountEmulatedStorage()
03-17 12:56:02.773  4979  4979 E Zygote  : v2
,03-17 12:56:02.773  4979  4979 I libpersona: KNOX_SDCARD checking this for 10134
03-17 12:56:02.773  4979  4979 I libpersona: KNOX_SDCARD not a persona
03-17 12:56:02.773  1022  1034 I ActivityManager: Start proc com.sec.android.widgetapp.SPlannerAppWidget for broadcast com.sec.android.widgetapp.SPlannerAppWidget/.EasyWidget.EasyCalendarAppWidgetProvider: pid=4979 uid=10134 gids={50134, 9997} abi=armeabi-v7a
,03-17 12:56:02.773  4979  4979 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 12:56:02.773  4915  4915 D EasySignUpManager_1.0.1: serviceId : 1, features : -1
03-17 12:56:02.773  4959  4959 D elm:15183: ElmAgentService : onDestroy().,
03-17 12:56:02.783  4915  4915 D EasySignUpManager_1.0.1: isAuth is false
03-17 12:56:02.783  4915  4915 D Mms/MmsConfig: setFreeMessageEnabled, getSupportedFeatures = -1 isAuth = false
03-17 12:56:02.783  4979  4979 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 12:56:02.783  1022  1083 I ActivityManager: Killing 4485:com.google.android.gm/u0a101 (adj 15): empty #31
03-17 12:56:02.783  4979  4979 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,03-17 12:56:02.783  1494  1735 D TP/MmsSmsProvider: query,matched:2117, calling pid = 4915,
03-17 12:56:02.793  1494  1735 D TP/MmsSmsProvider: match 2117:Elapsed time : 1.114 ms
,03-17 12:56:02.793  1022  1044 D SensorService: [SO] 0.192 0.402 10.190
,03-17 12:56:02.793  4915  4915 D EasySignUpManager_1.0.1: isAuth is false
03-17 12:56:02.793  4915  4915 D EasySignUpManager_1.0.1: getServiceStatus : serviceId (1) is OFF
,03-17 12:56:02.793  4915  4915 E CscParser: mps_code.dat does not exist
03-17 12:56:02.793  4915  4915 E CscParser: customer_path =/system/csc/customer.xml
03-17 12:56:02.793  4915  4915 E CscParser: fileName + /system/csc/customer.xml
,03-17 12:56:02.803  4979  4979 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:56:02.803  4979  4979 D ActivityThread: Added TimaKeyStore provider
,03-17 12:56:02.813  4915  4915 E CscParser: mps_code.dat does not exist
03-17 12:56:02.813  4915  4915 E CscParser: customer_path =/system/csc/customer.xml
03-17 12:56:02.813  4915  4915 E CscParser: fileName + /system/csc/customer.xml
,03-17 12:56:02.823  4915  4915 D CscParser: getInstance fileName =/system/csc/customer.xml
,03-17 12:56:02.823  4915  4915 D Mms/MmsConfig:  enable multiwindow = true
,03-17 12:56:02.823  4979  4979 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-17 12:56:02.823  4979  4979 W ResourcesManager: Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,03-17 12:56:02.833  1022  1046 W libprocessgroup: failed to open /acct/uid_10012/pid_4357/cgroup.procs: No such file or directory
,03-17 12:56:02.833  4915  4915 E Mms/MessageUtils: setCountryDetector : update country detector info 
03-17 12:56:02.833  4915  4915 E Mms/MessageUtils: updateCountryIso : update country iso info 
,03-17 12:56:02.843  4915  4915 D Mms/MmsConfig: [end]    init() consume time = 102.151718
,03-17 12:56:02.843  4915  4915 D Mms/Contact: [start]    init() consume time = 1.487605
,03-17 12:56:02.853  1022  1046 W libprocessgroup: failed to open /acct/uid_10166/pid_4267/cgroup.procs: No such file or directory
,03-17 12:56:02.853  1494  1513 D TP/MmsSmsProvider: query,matched:13, calling pid = 4915
,03-17 12:56:02.853  1022  1515 I ActivityManager: Killing 4542:com.dropbox.android:crash_uploader/u0a92 (adj 15): empty #31
,03-17 12:56:02.863  1494  1513 D TP/MmsSmsProvider: match 13:Elapsed time : 3.962 ms
,03-17 12:56:02.863  1022  1046 W libprocessgroup: failed to open /acct/uid_10101/pid_4485/cgroup.procs: No such file or directory
,03-17 12:56:02.873  4915  4915 D Mms/Contact: [end]    init consume time = 25.656354
,03-17 12:56:02.873  4915  4998 D Mms/DraftCache: [start]    rebuildCache consume time = 2.434739
,03-17 12:56:02.873  4915  4915 D Mms/MethodReflector: getSubId is called
03-17 12:56:02.873  1494  1513 D TP/MmsSmsProvider: query,matched:12, calling pid = 4915
03-17 12:56:02.873  4915  4915 D Mms/TelephonyUtils: getLongSubId from simSlot 0, return Value = -1
,03-17 12:56:02.873  4915  4915 D Mms/MethodReflector: getTelephonyProperty is called
03-17 12:56:02.873  4915  4915 D Mms/DownloadManager: roaming -> false (slotId = 0)
03-17 12:56:02.873  4915  4915 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 0
03-17 12:56:02.873  4915  4915 D Mms/DownloadManager: auto download without roaming -> true
03-17 12:56:02.873  4915  4915 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
03-17 12:56:02.873  4915  4915 D Mms/MethodReflector: getSubId is called
,03-17 12:56:02.883  4915  4915 D Mms/MethodReflector: getDefaultSmsSubId is called
03-17 12:56:02.883  4915  4915 E Mms/TelephonyUtils: subID is null or 0 length, so get DefaultSubId!!
03-17 12:56:02.883  4915  4915 D Mms/TelephonyUtils: getLongSubId from simSlot 1, return Value = -1000
03-17 12:56:02.883  4915  4915 D Mms/MethodReflector: getTelephonyProperty is called
03-17 12:56:02.883  4915  4915 D Mms/DownloadManager: roaming -> false (slotId = 1)
03-17 12:56:02.883  4915  4915 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 1
03-17 12:56:02.883  4915  4915 D Mms/DownloadManager: auto download without roaming -> true
03-17 12:56:02.883  4915  4915 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
03-17 12:56:02.883  4915  4915 D Mms/DownloadManager: auto download during roaming secondary -> false
03-17 12:56:02.883  4915  4915 D Mms/DownloadManager: mAutoDownload ------> true
,03-17 12:56:02.883  1494  1513 D TP/MmsSmsProvider: match 12:Elapsed time : 3.413 ms
,03-17 12:56:02.883  4915  4998 D Mms/DraftCache: [end]    rebuildCache consume time = 11.46573
,03-17 12:56:02.883  4915  4915 D ComposerPerformance: 1458215762895 ms / [DONE] Composer constructor
,03-17 12:56:02.893  4915  4999 D Mms/Conversation: [start]    init() consume time = 6.857291
,03-17 12:56:02.893  4915  4915 E CII     : CommonIMSInterface: VoLTE CSC feature disabled.
,03-17 12:56:02.893  4915  4915 I Mms/ReservationManager: ReservationManager()
03-17 12:56:02.893  4915  4915 I Mms/ReservationManager: resetAfterConnected()
,03-17 12:56:02.893  1494  2486 D TP/MmsSmsProvider: deleteConversation threadId: 9223372036854775807
,03-17 12:56:02.893  1494  2486 D TP/MmsSmsProvider: delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
,03-17 12:56:02.903  1494  2486 V TP/MmsSmsDatabaseHelper: updateThread(), thread_id = 9223372036854775807
,03-17 12:56:02.903  1494  1735 D TP/MmsSmsProvider: query,matched:7, calling pid = 4915
,03-17 12:56:02.903  1494  2486 V TP/MmsSmsDatabaseHelper: sUpgradeVersion = 0, db.getVersion() = 81
,03-17 12:56:02.903  1494  2486 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
,03-17 12:56:02.903  1494  2486 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
,03-17 12:56:02.903  1494  2486 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
,03-17 12:56:02.903  1494  2486 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-17 12:56:02.903  1494  2486 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
,03-17 12:56:02.903  1494  1735 D TP/MmsSmsProvider: match 7:Elapsed time : 7.189 ms
,03-17 12:56:02.903  1494  2486 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
,03-17 12:56:02.913  4915  4915 I Mms/ReservationManager: getReservedSendMessageCount(): retMessageCount=0
,03-17 12:56:02.913  4915  4915 D Mms/MmsApp: [end]    onCreate() consume time = 21.776771
,03-17 12:56:02.913  4915  4915 D Mms/DownloadManager: Service state changed: Bundle[mParcelledData.dataSize=744]
,03-17 12:56:02.913  4915  4915 D Mms/DownloadManager: roaming ------> false, mSimSlot = 0
,03-17 12:56:02.913  1022  1083 I splitIntent: Queue : background intent android.intent.action.TIME_SET is finished at BG and BG split queue. set mSplitStart  false.
03-17 12:56:02.913  4915  4915 D Mms/MethodReflector: getSubId is called
03-17 12:56:02.913  4915  4915 D Mms/TelephonyUtils: getLongSubId from simSlot 0, return Value = -1,
,03-17 12:56:02.923  1022  1083 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:56:02.923  1022  1083 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 12:56:02.923  1022  1083 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.contacts, destAppInfo.processName = com.android.contacts
,03-17 12:56:02.923  1022  1083 I ActivityManager: Killing 4520:com.dropbox.android/u0a92 (adj 15): empty #31
,03-17 12:56:02.923  1494  2486 D TP/MmsSmsProvider: delete threadId: 9223372036854775807
03-17 12:56:02.923  1494  2486 D TP/MmsSmsProvider: need read changed broadcast:false
,03-17 12:56:02.923  4915  4999 D Mms/Conversation: [end]    init consume time = 12.257865
,03-17 12:56:02.923  4915  4999 D Mms/MessagingNotification: [start]    init() consume time = 0.48875
,03-17 12:56:02.923  4915  4999 D Mms/MessagingNotification: [end]    init consume time = 2.38625
,03-17 12:56:02.933  4915  5000 D Mms/SpamFilter: [start]    SpamFilter fill() begin consume time = 1.812812
,03-17 12:56:02.933  4915  4915 D Mms/MethodReflector: getTelephonyProperty is called
,03-17 12:56:02.933  4915  4915 D Mms/DownloadManager: roaming -> false (slotId = 0)
03-17 12:56:02.933  4915  4915 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 0
,03-17 12:56:02.933  4915  4915 D Mms/DownloadManager: auto download without roaming -> true
03-17 12:56:02.933  4915  4915 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
03-17 12:56:02.933  4915  4915 D Mms/DownloadManager: mAutoDownload ------> true
,03-17 12:56:02.933  1494  1513 D TP/MmsSmsProvider: query,matched:400, calling pid = 4915
03-17 12:56:02.933  1022  1234 D ActivityManager: retrieveServiceLocked(): component = com.android.contacts/com.samsung.contacts.sim.MakeSimDBService; callingUser = 0; userId(target) = 0
,03-17 12:56:02.933  1022  1234 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:56:02.933  1022  1234 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 12:56:02.933  1022  1234 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.contacts, destAppInfo.processName = com.android.contacts
,03-17 12:56:02.933  1494  1507 D TP/MmsSmsProvider: query,matched:0, calling pid = 4915
,03-17 12:56:02.943  1494  1507 V TP/MmsSmsProvider: getSimpleConversations entered.
,03-17 12:56:02.943  1494  1507 D TP/MmsSmsProvider: match 0:Elapsed time : 3.014 ms
,03-17 12:56:02.943  4915  4962 D Mms/ArtClassLoader: init [DONE] art
,03-17 12:56:02.943  4915  5001 D Mms/Synchronizer: [start]    doSync consume time = 12.974323
,03-17 12:56:02.943  1022  1034 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:56:02.943  1022  1034 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:56:02.943  1022  1034 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-17 12:56:02.943  1022  1365 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,03-17 12:56:02.943  1022  1365 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:56:02.943  1022  1365 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:56:02.943  1022  1365 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-17 12:56:02.943  4915  5000 D Mms/SpamFilter: [end]    SpamFilter fill() finished consume time = 5.216875
,03-17 12:56:02.953  1494  1735 D TP/MmsSmsProvider: update, matched:300, calling pid = 4915
03-17 12:56:02.953  1494  1735 V TP/MmsSmsProvider: syncDBData start
,03-17 12:56:02.953  1494  1735 V TP/MmsSmsProvider: syncDBData sms end
,03-17 12:56:02.953  1022  1534 I splitIntent: intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
03-17 12:56:02.953  1494  1735 V TP/MmsSmsProvider: syncDBData mms end
,03-17 12:56:02.953  1022  1534 I splitIntent: base  index=1, name=com.google.android.gms com.google.android.gms.subscribedfeeds.ConfigurationReceiver
03-17 12:56:02.953  1022  1534 I splitIntent: other index=4, name=com.google.android.gms com.google.android.gms.common.stats.GmsCoreStatsServiceLauncher
,03-17 12:56:02.953  1494  1735 V TP/MmsSmsProvider: syncDBData end
03-17 12:56:02.953  1022  1534 I splitIntent: arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,03-17 12:56:02.953  1696  5003 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,03-17 12:56:02.953  1022  1534 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:56:02.953  1022  1534 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:56:02.953  1022  1534 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-17 12:56:02.953  1022  1482 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:56:02.953  1022  1482 E ActivityManager: checkUser: useridlist=null, currentuser=0,
03-17 12:56:02.953  1022  1482 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:56:02.963  4915  5001 D Mms/Synchronizer: [end]    doSync consume time = 10.756667
03-17 12:56:02.953  1022  1482 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:56:02.963   319   319 I ServiceManager: Waiting for service AtCmdFwd...
,03-17 12:56:02.973  5004  5004 E Zygote  : MountEmulatedStorage()
03-17 12:56:02.973  5004  5004 E Zygote  : v2
03-17 12:56:02.973  5004  5004 I libpersona: KNOX_SDCARD checking this for 10072
03-17 12:56:02.973  5004  5004 I libpersona: KNOX_SDCARD not a persona
03-17 12:56:02.973  5004  5004 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 12:56:02.973  1022  1482 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=5004 uid=10072 gids={50072, 9997} abi=armeabi-v7a
,03-17 12:56:02.973  1022  1534 W ActivityManager: userId = 0, bbcId = -10000,
,03-17 12:56:02.973  1022  1534 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:56:02.973  1022  1534 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
03-17 12:56:02.973  5004  5004 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-17 12:56:02.983  5004  5004 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
03-17 12:56:02.983  1696  1696 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,03-17 12:56:02.983  1022  1361 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:56:02.983  1022  1361 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:56:02.983  1022  1361 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-17 12:56:02.993  1022  1365 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:56:02.993  1022  1365 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:56:02.993  1022  1365 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-17 12:56:02.993  1914  1914 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
03-17 12:56:02.993  1022  1518 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
,03-17 12:56:02.993  1022  1518 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:56:02.993  1022  1518 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:56:02.993  1022  1518 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 12:56:02.993  1022  1534 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:56:02.993  1022  1534 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:56:02.993  1022  1534 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-17 12:56:03.003  5004  5004 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:56:03.003  5004  5004 D ActivityThread: Added TimaKeyStore provider
,03-17 12:56:03.003  1022  1506 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:56:03.003  1022  1506 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:56:03.003  1022  1506 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-17 12:56:03.013  1022  1234 I ActivityManager: Killing 3850:com.google.android.partnersetup/u0a15 (adj 15): empty #31
,03-17 12:56:03.013  1022  1506 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:56:03.013  1022  1506 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 12:56:03.013  1022  1506 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-17 12:56:03.013  1022  1083 D ActivityManager: retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
,03-17 12:56:03.023  1022  1083 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:56:03.023  1022  1083 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
,03-17 12:56:03.023  1022  1083 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,03-17 12:56:03.023  1022  1518 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:56:03.023  1022  1518 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:56:03.023  1022  1518 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-17 12:56:03.033  1022  1518 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:56:03.033  1022  1518 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:56:03.033  1022  1518 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-17 12:56:03.033  1763  5019 E MDM     : [195] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,03-17 12:56:03.033  1022  1034 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:56:03.033  1022  1034 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 12:56:03.033  1022  1034 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-17 12:56:03.043  1022  1361 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 12:56:03.043  5004  5004 D BadgeProvider: onCreate
03-17 12:56:03.043  5004  5004 D BadgeProvider: DatabaseHelper
,03-17 12:56:03.043  1022  1361 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:56:03.043  1022  1361 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:56:03.043  1022  1361 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 12:56:03.053  1022  1482 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:56:03.053  1022  1482 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:56:03.053  1022  1482 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-17 12:56:03.053  1022  1034 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,03-17 12:56:03.053  1022  1034 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:56:03.053  1022  1034 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:56:03.053  1022  1034 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 12:56:03.053  1914  5021 D LocationInitializer: Restart initialization of location
,03-17 12:56:03.063  1022  1482 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:56:03.063  1022  1482 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 12:56:03.063  1022  1482 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-17 12:56:03.063  1022  1482 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:56:03.063  1022  1482 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:56:03.063  1022  1482 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-17 12:56:03.073  1022  1518 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
,03-17 12:56:03.073  1022  1518 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:56:03.073  1022  1518 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:56:03.073  1022  1518 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-17 12:56:03.073  1022  1046 W libprocessgroup: failed to open /acct/uid_10092/pid_4542/cgroup.procs: No such file or directory
,03-17 12:56:03.073  1022  1046 W libprocessgroup: failed to open /acct/uid_10015/pid_3850/cgroup.procs: No such file or directory
,03-17 12:56:03.073  1022  1046 W libprocessgroup: failed to open /acct/uid_10092/pid_4520/cgroup.procs: No such file or directory
,03-17 12:56:03.083  4915  4999 D Mms/MessagingNotification: checkBadgeCount unreadCount=0 badgeCount=0
,03-17 12:56:03.093  1494  1513 D TP/SmsProvider: query,matched:26, calling pid = 4915
,03-17 12:56:03.093  1494  1513 D TP/SmsProvider: match 26:Elapsed time : 1.729 ms
,03-17 12:56:03.093  1022  1518 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:56:03.093  1022  1518 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 12:56:03.093  1022  1518 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,03-17 12:56:03.113  1494  1507 D TP/MmsSmsProvider: query,matched:6, calling pid = 4915
,03-17 12:56:03.113  1494  1507 D TP/MmsSmsProvider: match 6:Elapsed time : 1.029 ms
,03-17 12:56:03.123  1022  3060 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:56:03.123  1022  3060 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:56:03.123  1022  3060 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:56:03.123  1022  3060 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:56:03.133  5024  5024 E Zygote  : MountEmulatedStorage()
,03-17 12:56:03.133  5024  5024 E Zygote  : v2
03-17 12:56:03.133  5024  5024 I libpersona: KNOX_SDCARD checking this for 10025
03-17 12:56:03.133  5024  5024 I libpersona: KNOX_SDCARD not a persona
,03-17 12:56:03.143  5024  5024 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 12:56:03.143  1022  3060 I ActivityManager: Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=5024 uid=10025 gids={50025, 9997} abi=armeabi-v7a
,03-17 12:56:03.143  5024  5024 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 12:56:03.143  5024  5024 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 12:56:03.153  1022  1022 I ValidateNoPeople: mEvictionCount: 0
,03-17 12:56:03.153  4915  4915 D Mms/Contact: sContactsObserver.onChange(),selfUpdate=false
,03-17 12:56:03.153  4915  4915 D Mms/Contact: performUpdate:widgetCount=0
,03-17 12:56:03.153  1022  1083 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:56:03.153  1022  1083 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:56:03.153  1022  1083 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:56:03.153  1022  1083 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:56:03.163  5024  5024 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:56:03.163  5024  5024 D ActivityThread: Added TimaKeyStore provider
,03-17 12:56:03.163  4915  5036 D Mms/ContactsCache: [start]    invalidate() consume time = 200.566562
,03-17 12:56:03.163  4915  5036 D Mms/ContactsCache: [end]    invalidate() consume time = 5.099948
,03-17 12:56:03.173  5041  5041 E Zygote  : MountEmulatedStorage()
,03-17 12:56:03.173  5041  5041 E Zygote  : v2
,03-17 12:56:03.173  5041  5041 I libpersona: KNOX_SDCARD checking this for 1000
03-17 12:56:03.173  5041  5041 I libpersona: KNOX_SDCARD not a persona
,03-17 12:56:03.173  5041  5041 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-17 12:56:03.173  1022  1083 I ActivityManager: Start proc com.samsung.android.MtpApplication for broadcast com.samsung.android.MtpApplication/.MtpReceiver: pid=5041 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-17 12:56:03.173  5041  5041 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-17 12:56:03.173  5041  5041 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 12:56:03.183  1022  3083 I ActivityManager: Killing 4577:com.google.android.googlequicksearchbox:search/u0a57 (adj 15): empty #31
,03-17 12:56:03.193  5024  5024 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,03-17 12:56:03.203  5041  5041 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:56:03.203  5041  5041 D ActivityThread: Added TimaKeyStore provider
,03-17 12:56:03.223  5041  5041 E MTPRx   : In MtpReceiverandroid.hardware.usb.action.USB_STATE
,03-17 12:56:03.233  1022  1083 D SecContentProvider2: uri = 14 selection = getSealedState
03-17 12:56:03.233  1022  1083 D SecContentProvider2: mCursor = null
,03-17 12:56:03.233  1022  1035 D SecContentProvider2: uri = 14 selection = getSealedUsbMassStorageState
,03-17 12:56:03.233  1022  1035 D SecContentProvider2: mCursor = null
,03-17 12:56:03.233  5041  5041 V MTPRx   : sealedState: false
03-17 12:56:03.233  5041  5041 V MTPRx   : sealedUsbMassStorageState: false
03-17 12:56:03.233  5041  5041 E MTPRx   : check value of boot_completed is1
03-17 12:56:03.233  5041  5041 E MTPRx   : check booting is completed_sys.boot_completed
03-17 12:56:03.233  5024  5024 I OMACP   : [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
,03-17 12:56:03.233  5041  5041 E MTPRx   : Sd-Card path/storage/extSdCard
,03-17 12:56:03.233  5041  5041 E MTPRx   : Status for mount/Unmount :removed
03-17 12:56:03.233  5041  5041 E MTPRx   : SDcard is not available
,03-17 12:56:03.243  5041  5041 W MTPRx   : value of connected istrue
03-17 12:56:03.243  5041  5041 W MTPRx   : value of configured istrue
03-17 12:56:03.243  5041  5041 W MTPRx   : value of mtpEnabled istrue
03-17 12:56:03.243  5041  5041 W MTPRx   : value of ptpEnabled isfalse
,03-17 12:56:03.243  5041  5041 E MTPRx   : Received USB_STATE with sdCardLaunch = 0
,03-17 12:56:03.243  5041  5041 E MTPRx   : mFirstTime: false
,03-17 12:56:03.253  5041  5041 D         : MTP: reading debug level property
,03-17 12:56:03.253  5041  5041 E MTPJNIInterface: Getting CryptionKey from JAVA
03-17 12:56:03.253  5041  5041 E MTPRx   : currentUserId is 0
,03-17 12:56:03.253  4915  4999 D Mms/Omacp: checkOmacp()  old OmacpCount 0 current OmacpCount = 0
,03-17 12:56:03.253  5041  5041 E MTPRx   : Start observing USB_STATE_MATCH 
,03-17 12:56:03.263  5041  5041 E MTPRx   : cannot open file : /sys/class/android_usb/android0/bcdUSB
,03-17 12:56:03.263  5041  5041 E MTPRx   : is_Privatemode is NOT 1
,03-17 12:56:03.263  1022  1034 D SettingsProvider: name = boot_time_connected
,03-17 12:56:03.263  5024  5024 I OMACP   : [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false,
,03-17 12:56:03.263  5024  5024 I OMACP   : [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
,03-17 12:56:03.273  5024  5024 I OMACP   : [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
,03-17 12:56:03.273  5041  5041 E MTPRx   : Sending NORMAL_BOOT to stack
03-17 12:56:03.273  5041  5041 E MTPJNIInterface: noti = 17
,03-17 12:56:03.273  5024  5024 I OMACP   : [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
,03-17 12:56:03.273  1022  1365 D SettingsProvider: name = mtp_usb_conditions_met
,03-17 12:56:03.273  5024  5024 I OMACP   : [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
,03-17 12:56:03.273  5024  5024 I OMACP   : [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
,03-17 12:56:03.273  5024  5024 I OMACP   : [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
,03-17 12:56:03.273  1022  3083 D SecContentProvider: uri = 18 selection = isUsbMediaPlayerAvailable
,03-17 12:56:03.273  5024  5024 I OMACP   : [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
,03-17 12:56:03.273  5041  5041 E MTPRx   : sending MTP_ICON_ENABLED to stack
,03-17 12:56:03.273  5024  5024 I OMACP   : [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
,03-17 12:56:03.273  5024  5024 I OMACP   : [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
,03-17 12:56:03.283  1022  1518 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.MtpService; callingUser = 0; userId(target) = 0
,03-17 12:56:03.283  1022  1518 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:56:03.283  1022  1518 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 12:56:03.283  1022  1518 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.samsung.android.MtpApplication
,03-17 12:56:03.283  5024  5024 I OMACP   : [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
,03-17 12:56:03.283  5024  5024 I OMACP   : [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
,03-17 12:56:03.283  5024  5024 I OMACP   : [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
,03-17 12:56:03.283  1022  3060 D SettingsProvider: name = mtp_running_status
,03-17 12:56:03.293  3554  3554 I PCWCLIENTTRACE_SYSTEMReceiver: mConnectivityHandler : connected
,03-17 12:56:03.293  1022  1361 D SettingsProvider: name = mtp_usb_conditions_met
03-17 12:56:03.293  5041  5041 E MTPRx   : else part ... so first time!!!
03-17 12:56:03.293  5041  5041 E MTPPlaObsrvr: inside setContext()
03-17 12:56:03.293  5041  5041 E MTPPlaObsrvr:  inside createplafiles
,03-17 12:56:03.293  3554  5058 W PCWCLIENTTRACE_AccountUtil: [hasSamungAccount] - No Samsung Account
,03-17 12:56:03.293  1191  1191 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 12:56:03.303  5041  5041 E MTPPlaObsrvr: playlist count is0
,03-17 12:56:03.303  5041  5041 E MTPPlaObsrvr:  inside try branch createplafiles,
,03-17 12:56:03.303  5041  5041 E MTPPlaObsrvr:  inside deleteing plas createplafiles,
,03-17 12:56:03.303  5041  5041 E MTPPlaObsrvr: Inside registerContentObserver
,03-17 12:56:03.303  5041  5041 E MtpAdbObserver: inside setContext()
03-17 12:56:03.303  5041  5041 E MtpAdbObserver: Inside registerContentObserver
03-17 12:56:03.303  5041  5041 W Settings: Setting adb_enabled has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only global URI.
,03-17 12:56:03.313  1022  1234 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.MtpService; callingUser = 0; userId(target) = 0
,03-17 12:56:03.313  5041  5059 V MtpMediaDBManager: inside deleteAllDB
,03-17 12:56:03.313  1022  1234 W ActivityManager: userId = 0, bbcId = -10000
03-17 12:56:03.313  1022  1234 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 12:56:03.313  1022  1234 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.samsung.android.MtpApplication
,03-17 12:56:03.313  1022  1534 D SettingsProvider: name = mtp_running_status
,03-17 12:56:03.313  1022  1515 D SettingsProvider: name = mtp_usb_conditions_met
,03-17 12:56:03.313  3554  5058 I PCWCLIENTTRACE_SecurePreferencesJNI: [GetString-S]
,03-17 12:56:03.313  5041  5041 E MtpService: onCreate.
03-17 12:56:03.313  3554  5058 I ReactiveServiceManager: Supported : 1
,03-17 12:56:03.313  1022  1482 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x2040
,03-17 12:56:03.313  1022  1482 D QSEECOMAPI: : App is not loaded in QSEE
,03-17 12:56:03.313  5041  5041 E MtpService: < MTP > Registering BroadCast receiver :::::
,03-17 12:56:03.323  1022  1361 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.media/com.android.providers.media.MtpService; callingUser = 0; userId(target) = 0
,03-17 12:56:03.323  1022  1361 W ActivityManager: userId = 0, bbcId = -10000
,03-17 12:56:03.323  1022  1361 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 12:56:03.323  1022  1361 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,03-17 12:56:03.323  1245  1245 D MtpService: updating state; isCurrentUser=true, mMtpLocked=false
,03-17 12:56:03.323  5041  5041 E MtpService: < MTP > Registering BroadCast registerBroadCastPolicyRec :::::
,03-17 12:56:03.333  5041  5041 E MtpService: < MTP > Registering BroadCast registerBroadCastEmergencyRec :::::
,03-17 12:56:03.333  5041  5041 E MtpService: onStartCommand.
,03-17 12:56:03.333  5041  5041 W MTPRx   : calling native method
03-17 12:56:03.333  5041  5041 E MTPJNIInterface: < MTP > Registering BroadCast receiver :::::
,03-17 12:56:03.333  5041  5060 E MtpService: handleMessage. msg= { when=-1ms what=0 arg1=1 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
03-17 12:56:03.333  1022  1482 D QSEECOMAPI: : Loaded image: APP id = 11
,03-17 12:56:03.333  1022  1515 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:56:03.333  1022  1515 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:56:03.333  1022  1515 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 12:56:03.333  1022  1515 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 12:56:03.343  1022  1482 D QSEECOMAPI: : QSEECom_dealloc_memory 
03-17 12:56:03.343  1022  1482 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 11
03-17 12:56:03.343  1022  1482 E terrier : handleString: Failed to handle string(-4)
03-17 12:56:03.343  1022  1482 E terrier : Java_com_android_server_ReactiveService_GetString: error code = [-4]
03-17 12:56:03.343  3554  5058 D PCWCLIENTTRACE_SecurePreferencesJNI: getString is null
03-17 12:56:03.343  3554  5058 I PCWCLIENTTRACE_SecurePreferencesJNI: [GetString-E]
,03-17 12:56:03.343  3554  5058 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
03-17 12:56:03.343  3554  5058 I PCWCLIENTTRACE_PushUtil: sales region : global
03-17 12:56:03.343  3554  5058 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
03-17 12:56:03.343  3554  5058 E PCWCLIENTTRACE_PCWHandler: [ensureRegistration] - No Samsung account
,03-17 12:56:03.353  5041  5059 V MtpMediaDBManager: inside Thread updateDB
03-17 12:56:03.353  5061  5061 I libpersona: KNOX_SDCARD checking this for 1000
03-17 12:56:03.353  5061  5061 E Zygote  : MountEmulatedStorage()
03-17 12:56:03.353  5061  5061 I libpersona: KNOX_SDCARD not a persona
03-17 12:56:03.353  5061  5061 E Zygote  : v2
03-17 12:56:03.353  5061  5061 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-17 12:56:03.353  5061  5061 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-17 12:56:03.353  5061  5061 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 12:56:03.353  1022  1515 I ActivityManager: Start proc com.samsung.android.app.mirrorlink for broadcast com.samsung.android.app.mirrorlink/.TMNetworkReceiver: pid=5061 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-17 12:56:03.363  5041  5041 E MTPJNIInterface: < MTP > Registering BroadCast receiver :::::::
,03-17 12:56:03.363  5041  5041 E MTPJNIInterface: noti = 10
03-17 12:56:03.363  5041  5059 E MtpMediaDBManager: count : 27
03-17 12:56:03.363  5041  5041 E MtpService: onStartCommand.
03-17 12:56:03.363  5041  5041 W MTPRx   : calling native method
03-17 12:56:03.363  5041  5041 E MTPRx   : Checking the driver time out
03-17 12:56:03.363  5041  5041 E MTPJNIInterface: noti = 2
03-17 12:56:03.363  5041  5041 D         : deleting sockets before message queue initialization
,03-17 12:56:03.363  5041  5041 D         : event handler thread is created, so set the flag
03-17 12:56:03.363  5041  5060 E MtpService: handleMessage. msg= { when=0 what=0 arg1=2 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
03-17 12:56:03.363  5041  5041 E MTPRx   : called native method
03-17 12:56:03.363  5041  5041 E MTPJNIInterface: setting Media scanner status0
03-17 12:56:03.363  5041  5041 E MTPJNIInterface: After setting Media scanner status0
,03-17 12:56:03.363  5041  5041 W MTPRx   : notification from stack 1
,03-17 12:56:03.363  5041  5070 E         : Unable to get Object Class and clearing cls 2 [int check_media_scanner_status() 594]
03-17 12:56:03.363  5041  5070 E MTPJNIInterface: Getting media scanner status0
,03-17 12:56:03.363  5041  5070 E MTPJNIInterface: DeviceName is Thali Test (Galaxy A5)
,03-17 12:56:03.383  5061  5061 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 12:56:03.383  5061  5061 D ActivityThread: Added TimaKeyStore provider
,03-17 12:56:03.393  5041  5059 W MtpMediaDBManager: sending db update complete noti to stack
03-17 12:56:03.393  5041  5059 E MTPJNIInterface: noti = 29
,03-17 12:56:03.393  1022  1046 W libprocessgroup: failed to open /acct/uid_10057/pid_4577/cgroup.procs: No such file or directory
,03-17 12:56:03.403  5041  5070 E MTPJNIInterface: Status for mount/Unmount :removed
03-17 12:56:03.403  5041  5070 E MTPJNIInterface: SDcard is not available
,03-17 12:56:03.413  5041  5070 E         : [mtp_hidden_system_volume 189] Error opening file [error = Read-only file system] 
,03-17 12:56:03.423  5041  5070 E MTPJNIInterface: Status for mount/Unmount :removed
03-17 12:56:03.423  5041  5070 E MTPJNIInterface: SDcard is not available
03-17 12:56:03.423  5041  5070 E SQLiteLog: (21) API call with NULL database connection pointer
03-17 12:56:03.423  5041  5070 E SQLiteLog: (21) misuse at line 106108 of [9491ba7d73]
03-17 12:56:03.423  5041  5070 E SQLiteLog: (21) API call with NULL database connection pointer
03-17 12:56:03.423  5041  5070 E SQLiteLog: (21) misuse at line 100726 of [9491ba7d73]
03-17 12:56:03.423  5041  5070 E SQLiteLog: (21) API call with NULL database connection pointer
03-17 12:56:03.423  5041  5070 E SQLiteLog: (21) misuse at line 100726 of [9491ba7d73]
03-17 12:56:03.423  5041  5070 E SQLiteLog: (21) API call with NULL database connection pointer
03-17 12:56:03.423  5041  5070 E SQLiteLog: (21) misuse at line 106108 of [9491ba7d73]
,03-17 12:56:03.423  5041  5041 W MTPRx   : notification from stack 2
,03-17 12:56:03.423  5041  5077 D         : [mtp_init_device] Library open with 32 bits.
,03-17 12:56:03.423  5041  5077 D         : [mtp_init_device] Going to open(): /dev/usb_mtp_gadget
03-17 12:56:03.423  5041  5077 E         : [mtp_init_device 702]  After open the MTP fd = 32 and line = 702...
03-17 12:56:03.423  5041  5077 D         : [mtp_init_device] IOCTL SET_MTP_USER_PID Sucesss 
03-17 12:56:03.423  5041  5077 E         :  [sua_support_present:1287] returning false 
03-17 12:56:03.423  5041  5077 D         : [mtp_init_device] b4 calling MTP_ONLY_ENABLE  ioctl coneect to host

```
