#### Test 50242285feafdeb_thali08_samsung-SM-A300FU Logs


```
--------- beginning of main
I/DBG_POLICYDM( 2931): [com.policydm.adapter.XDMTargetAdapter(191/xdmInitExternalStorageState)] 
I/DBG_POLICYDM( 2931): [com.policydm.agent.XDMTask(163/xdmAgentTaskHandler)] XEVENT_OS_INITIALIZED
D/TimaKeyStoreProvider( 2977): TimaSignature is unavailable
D/ActivityThread( 2977): Added TimaKeyStore provider
I/DBG_POLICYDM( 2931): [com.policydm.adapter.XDMTargetAdapter(390/xdmGetExternalSDCardPath)] External SD Card Path : /storage/extSdCard
I/DBG_POLICYDM( 2931): [com.policydm.adapter.XDMTargetAdapter(248/xdmInitExternalStorageState)] DATA_DIR_PATH [/data]
I/DBG_POLICYDM( 2931): [com.policydm.adapter.XDMTargetAdapter(249/xdmInitExternalStorageState)] EXTERNAL_DIR_PATH [/storage/emulated/0]
--------- beginning of system
W/libprocessgroup( 1020): failed to open /acct/uid_10045/pid_2068/cgroup.procs: No such file or directory
I/DBG_POLICYDM( 2931): [com.policydm.agent.XDMAgent(156/xdmAgentSetSyncMode)] nSync = 0
I/DBG_POLICYDM( 2931): [com.policydm.adapter.XDMTargetAdapter(250/xdmInitExternalStorageState)] EXTERNAL_SD_DIR_PATH [/storage/extSdCard]
I/DBG_POLICYDM( 2931): [com.policydm.adapter.XDMTargetAdapter(251/xdmInitExternalStorageState)] POLICY_DIR_PATH [/data/user/0/com.policydm/cache]
I/DBG_POLICYDM( 2931): [com.policydm.adapter.XDMTargetAdapter(253/xdmInitExternalStorageState)] bExternalStorageAvailable [true]
I/DBG_POLICYDM( 2931): [com.policydm.adapter.XDMTargetAdapter(254/xdmInitExternalStorageState)] bExternalSDStorageAvailable [false]
I/DBG_POLICYDM( 2931): [com.policydm.XDMApplication(580/xdmWakeLockRelease)] 
I/DBG_POLICYDM( 2931): [com.policydm.XDMApplication(585/xdmWakeLockRelease)] m_WakeLock is release!!
I/DBG_POLICYDM( 2931): [com.policydm.XDMApplication(179/onCreate)] DMApplication Start !
I/DBG_POLICYDM( 2931): [com.policydm.db.XDB(1531/xdbDMffs_Init)] xdbDMffs_Init
I/DBG_DM  ( 2894): [com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI(2693/lllIlIlIIIllIIlIllIl)] xdbsqlGetFUMOStatus : 220
I/DBG_DM  ( 2894): [com.wssyncmldm.XDMApplication(80/onCreate)] XDMApplication Start ! - Fumo State
W/ContextImpl( 2894): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 com.wssyncmldm.XDMApplication.onCreate:81 android.app.Instrumentation.callApplicationOnCreate:1020 android.app.ActivityThread.handleBindApplication:5256 
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.wssyncmldm, destAppInfo.processName = com.wssyncmldm
I/DBG_DM  ( 2894): [com.wssyncmldm.XDMBroadcastReceiver(152/onReceive)] android.intent.action.BOOT_COMPLETED
I/DBG_DM  ( 2894): [com.wssyncmldm.XDMService(1598/IlIlllIIlIlIIIlIlIll)] 
I/DBG_DM  ( 2894): [com.wssyncmldm.XDMService(1603/IlIlllIIlIlIIIlIlIll)] m_WakeLock is acquire!!
I/DBG_DM  ( 2894): [com.wssyncmldm.XDMService(1420/lllIlIlIIIllIIlIllIl)] 0
I/DBG_DM  ( 2894): [IIlIIIlllllIIlIIIlII(232/llllIllIIIIIlIIllIII)] Default - NO_ROOTING_CHECK : false
I/DBG_DM  ( 2894): [com.wssyncmldm.XDMService(1463/llIlIIIIlIIIIIlIlIII)] 0
I/DBG_DM  ( 2894): [IIlIIIlllllIIlIIIlII(261/IIllIlIIIIlIIIllIllI)] Roaming Check : true
I/DBG_DM  ( 2894): [com.wssyncmldm.XDMService(1548/llIIllllIIlllIIIIlll)] 0
I/DBG_DM  ( 2894): [IIlIIIlllllIIlIIIlII(293/llIIlIlIlIlIIIIIIlIl)] validation Check On
I/DBG_DM  ( 2894): [com.wssyncmldm.XDMService(1505/IllIlIIIIlIIlIIIllIl)] 0
I/DBG_DM  ( 2894): [IIlIIIlllllIIlIIIlII(274/lllllllIlllIIlllIlIl)] SSL Check On
I/DBG_DM  ( 2894): [llIIlIIlIllIllIlllII(109/llllIIIllIlIIIIllllI)] 
D/OverheatReceiver( 1177): onReceive() getAction : android.intent.action.BOOT_COMPLETED
I/DBG_DM  ( 2894): [IlIIlIIlIllllIlllIII(181/llIIIIlllllIIllIIllI)] XEVENT_OS_INITIALIZED
D/OverheatReceiver( 1177): into the SAFE_MODE_ACTION
D/OverheatReceiver( 1177): VZW on -> change to Global UX [safe mode]
D/OverheatReceiver( 1177): isSafeMode = false
I/DBG_DM  ( 2894): [llIIlIIlIllIllIlllII(397/llIIIIlllllIIllIIllI)] External SD Card Path : /storage/extSdCard
D/BootupListener( 1455): intent.getAction() = android.intent.action.BOOT_COMPLETED
I/DBG_DM  ( 2894): [llIlIIIIlllIlllllIll(142/llIIIIlllllIIllIIllI)] nSync = 0
D/SettingsProvider( 1020): name = internet_call_settings_visibility
D/SettingsProvider( 1020): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1020): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1020): selectionArgs: false
D/SettingsProvider( 1020): selectionArgs: 1001
D/SecContentProvider( 1020): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1020): ret = -1
D/PhoneUtilsCommon( 1455): isSupportVoLTE is false.
I/DBG_DM  ( 2894): [llIIlIIlIllIllIlllII(166/llllIIIllIlIIIIllllI)] bExternalStorageAvailable [true]
I/DBG_DM  ( 2894): [llIIlIIlIllIllIlllII(167/llllIIIllIlIIIIllllI)] bExternalSDStorageAvailable [false]
I/DBG_DM  ( 2894): [com.wssyncmldm.XDMService(1624/IIlIlIIlIlIIlIlllIIl)] 
I/DBG_DM  ( 2894): [com.wssyncmldm.XDMService(1629/IIlIlIIlIlIIlIlllIIl)] m_WakeLock is release!!
W/ContextImpl( 2894): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.wssyncmldm.ui.lIlIIlIlIlIllllllIII.lllIlIlIIIllIIlIllIl:72 com.wssyncmldm.ui.lIlIIlIlIlIllllllIII.llIIIIlllllIIllIIllI:112 IlIIlIIlIllllIlllIII.llIIIIlllllIIllIIllI:185 
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
I/DBG_DM  ( 2894): [com.wssyncmldm.XDMService(155/onStartCommand)] 
I/Telecom ( 1431): InCallController: Attempting to bind to InCall com.android.incallui, is dupe? false 
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.wssyncmldm, destAppInfo.processName = com.wssyncmldm
I/DBG_POLICYDM( 2931): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.incallui
I/DBG_POLICYDM( 2931): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.incallui
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.dropbox.android, destAppInfo.processName = com.dropbox.android
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
I/DBG_POLICYDM( 2931): [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
I/DBG_POLICYDM( 2931): [com.policydm.agent.XDMTask(171/xdmAgentTaskHandler)] XEVENT_DM_INIT
I/DBG_POLICYDM( 2931): [com.policydm.XDMApplication(463/xdmProtoIsWIFIConnected)] WiFi network Connected : false
I/DBG_POLICYDM( 2931): [com.policydm.XDMApplication(473/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
E/DBG_POLICYDM( 2931): [com.policydm.agent.XDMTask(174/xdmAgentTaskHandler)] Network Status is not ready. DM Not Initialized
E/Zygote  ( 3008): MountEmulatedStorage()
I/libpersona( 3008): KNOX_SDCARD checking this for 10088
E/Zygote  ( 3008): v2
I/libpersona( 3008): KNOX_SDCARD not a persona
I/SELinux ( 3008): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1020): Start proc com.dropbox.android:crash_uploader for service com.dropbox.android/.exception.CrashUploaderService: pid=3008 uid=10088 gids={50088, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 3008): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/Telecom ( 1431): InCallController: onConnected to ComponentInfo{com.android.incallui/com.android.incallui.InCallServiceImpl}
E/SELinux ( 3008): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
I/DBG_DM  ( 2894): [com.wssyncmldm.db.file.XDB(1976/llIlIIIIlIIIIIlIlIII)] xdbDMffs_Init
I/art     (  308): Explicit concurrent mark sweep GC freed 8727(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 609us total 23.127ms
D/TimaKeyStoreProvider( 3008): TimaSignature is unavailable
D/ActivityThread( 3008): Added TimaKeyStore provider
I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 571us total 16.573ms
I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 571us total 27.126ms
I/com.dropbox.android.service.DropboxNetworkReceiver( 2958): Setting receiver enabled: false
E/Zygote  ( 3025): MountEmulatedStorage()
E/Zygote  ( 3025): v2
I/libpersona( 3025): KNOX_SDCARD checking this for 10052
I/libpersona( 3025): KNOX_SDCARD not a persona
I/ActivityManager( 1020): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.StartUpReceiver: pid=3025 uid=10052 gids={50052, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a
I/DBG_DM  ( 2894): [IlIIlIIlIllllIlllIII(191/llIIIIlllllIIllIIllI)] XEVENT_PHONEBOOK_INITIALIZED
I/SELinux ( 3025): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/DBG_DM  ( 2894): [com.wssyncmldm.ui.IIllIllllIIlIlIIlIII(49/onServiceConnected)] 
I/SELinux ( 3025): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 3025): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/DBG_POLICYDM( 2931): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
I/DBG_POLICYDM( 2931): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
I/DBG_POLICYDM( 2931): [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
D/TimaKeyStoreProvider( 3025): TimaSignature is unavailable
D/ActivityThread( 3025): Added TimaKeyStore provider
E/ActivityThread( 2958): Failed to find provider info for com.dropbox.carousel.CuOwnerCheckProvider
I/DBG_DM  ( 2894): [com.wssyncmldm.db.file.XDB(3660/lllIIIIllIlIlllllllI)] FUMO_Status : 220
I/DBG_DM  ( 2894): [com.wssyncmldm.XDMService(1377/llllIIIllIlIIIIllllI)] wssGetUpdateReport : 0
I/DBG_DM  ( 2894): [IlIIlIIlIllllIlllIII(217/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT
V/audio_hw_primary(  286): adev_get_parameters: enter: keys - call_forwarding
D/audio_hw_extn(  286): audio_extn_get_parameters: returns 
V/msm8974_platform(  286): platform_get_parameters: exit: returns - 
V/audio_hw_primary(  286): adev_get_parameters: exit: returns - call_forwarding=false
I/str_params(  286): key: 'call_forwarding' value: ''
V/InCall  ( 1825): ProximitySensor -  - screenonImmediately: false
V/InCall  ( 1825): ProximitySensor -  - mFromRcsShare: false
I/dbxyzptlk.db240408.D.h( 2958): Loading /data/data/com.dropbox.android/files/extracted_libs/lib_breakpadinstaller_1dc04d6d96cbb2962385ec13f5f77649aec85e95_arm
I/InCall  ( 1825): ProximitySensor -  - ProximitySensor{keybrd=0, dpad=0, offhook=0, hor=0, ui=0, aud=EARPIECE}
D/ScoverManager( 1825): serviceVersion : 16908288
D/CoverManagerWhiteLists( 1020): isAllowedToUse : SIGNATURE_MATCH
I/dbxyzptlk.db240408.D.h( 2958): Loading /data/data/com.dropbox.android/files/extracted_libs/lib_dbxfileobserver_59d9546785d1f42b870763ef906fd65c59b55c56_arm
D/InCall  ( 1825): InCallUtils - isCoverClosed : TYPE_FLIP_COVER 
I/Telecom ( 1431): ProximitySensorManager: Proximity wake lock already released
D/CoverManagerWhiteLists( 1020): isAllowedToUse : SIGNATURE_MATCH
D/InCall  ( 1825): InCallUtils - isCoverClosed : TYPE_FLIP_COVER 
I/InCall  ( 1825): InCallPresenter -  - InCallState = NO_CALLS
E/USB_UICC(  299): Timeout! No signal received. Retry num = 26
I/InCall  ( 1825): InCallPresenter -  - Phone switching state: NO_CALLS -> NO_CALLS
D/InCall  ( 1825): InCallPresenter -  - dismissCoverDialog()...
I/dbxyzptlk.db240408.D.h( 2958): Loading /data/data/com.dropbox.android/files/extracted_libs/lib_dropboxsync_cf9d7b2df44b0b78b581431109195f96d492fc70_arm
I/InCall  ( 1825): CallSContextMotion - stopPutDownListening
D/InCall  ( 1825): StatusBarNotifier - updateInCallNotification(allowFullScreenIntent = false)...
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
D/CoverManagerWhiteLists( 1020): isAllowedToUse : SIGNATURE_MATCH
D/InCall  ( 1825): InCallUtils - isCoverClosed : TYPE_FLIP_COVER 
D/PhoneStatusBarView( 1177): setCallBackground:0
E/Zygote  ( 3049): MountEmulatedStorage()
E/Zygote  ( 3049): v2
I/libpersona( 3049): KNOX_SDCARD checking this for 1000
I/libpersona( 3049): KNOX_SDCARD not a persona
I/SELinux ( 3049): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1020): Start proc com.fmm.dm for broadcast com.fmm.dm/.XDMBroadcastReceiver: pid=3049 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/ActivityManager( 1020): Killing 1603:com.google.android.partnersetup/u0a14 (adj 15): empty #31
I/ActivityManager( 1020): Killing 1497:com.android.printspooler/u0a132 (adj 15): empty #32
I/ActivityManager( 1020): Killing 2131:com.google.android.apps.magazines/u0a110 (adj 15): empty #33
I/SELinux ( 3049): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 3049): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
D/TimaKeyStoreProvider( 3049): TimaSignature is unavailable
D/ActivityThread( 3049): Added TimaKeyStore provider
I/ActivityManager( 1020): Killing 2233:com.sec.modem.settings/1000 (adj 15): empty #31
I/dbxyzptlk.db240408.D.h( 2958): Loading /data/data/com.dropbox.android/files/extracted_libs/lib_mupdf_391432aaa92f053af59645394b5734622378199a_arm
D/breakpad( 2958): breakpad loaded; target path "/data/data/com.dropbox.android/app_crashdumps"
D/VideoCallManager( 1825): Instantiating VideoCallManager
E/lowmemorykiller(  256): Error writing /proc/1603/oom_score_adj; errno=22
W/ActivityManager( 1020): ProcessRecord{b545c61 1603:com.google.android.partnersetup/u0a14} is already killed
E/JavaBinder( 1020): !!! FAILED BINDER TRANSACTION !!!
I/DBG_FMMDM( 3049): [50.20.150420][Line:608][xdmGetCheckWifiOnlyModel] isWifiOnly : false
E/Tethering( 1020): No numeric data
E/Tethering( 1020): No numeric data
E/Tethering( 1020): No numeric data
E/Tethering( 1020): No numeric data
E/Tethering( 1020): No numeric data
I/DBG_FMMDM( 3049): [50.20.150420][Line:27][xdmInitialize] AgVOOqV7UpXFblBk29Ld3aZrOQhtHCYbjdszx6nYrjFYzeVOvvlPUzE67GnQVups
E/Tethering( 1020): No numeric data
I/DBG_FMMDM( 3049): [50.20.150420][Line:28][xdmInitialize] c8aaBoNX+zCI65M7gVNTej45+K/MzxjqVpKd5x0FMtd3o63nokSujfTEanrHiU41
I/DBG_FMMDM( 3049): [50.20.150420][Line:29][xdmInitialize] X2Nl5mgTWVn0/a90MNBgtYshxOiQq2MqI4oMf2Nwz6I=
I/ActivityManager( 1020): Existing provider com.google.android.partnersetup/.RlzAppProvider is crashing; detaching ProcessRecord{1b171386 3025:com.google.android.googlequicksearchbox:search/u0a52}
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/        ( 1825): GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
I/GFX construct_block_size_descriptor_2d second part( 1825): took 2.882448ms for 0*0 texture 0
W/libprocessgroup( 1020): failed to open /acct/uid_10132/pid_1497/cgroup.procs: No such file or directory
W/libprocessgroup( 1020): failed to open /acct/uid_10014/pid_1603/cgroup.procs: No such file or directory
I/GFX generate_partition_tables( 1825): took 5.476510ms for 0*0 texture 0
E/Zygote  ( 3071): MountEmulatedStorage()
E/Zygote  ( 3071): v2
I/libpersona( 3071): KNOX_SDCARD checking this for 10014
I/libpersona( 3071): KNOX_SDCARD not a persona
I/GFX raster( 1825): took 12.328229ms for 176*144 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1825): Bitmap=0xb78fb3e0 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b0, Counterpart=0xb78fb528 counterpartCT=4 counterpartW=176 counterparth=144
I/SELinux ( 3071): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1020): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=3071 uid=10014 gids={50014, 9997, 3003} abi=armeabi-v7a
W/libprocessgroup( 1020): failed to open /acct/uid_1000/pid_2233/cgroup.procs: No such file or directory
W/ActivityManager( 1020): Spurious death for ProcessRecord{b545c61 0:com.google.android.partnersetup/u0a14}, curProc for 1603: null
I/SELinux ( 3071): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 3071): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 3084): MountEmulatedStorage()
E/Zygote  ( 3084): v2
I/libpersona( 3084): KNOX_SDCARD checking this for 1000
I/libpersona( 3084): KNOX_SDCARD not a persona
I/SELinux ( 3084): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1020): Start proc com.sec.pcw.device for content provider com.sec.pcw.device/.contentprovider.DMProvider: pid=3084 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
W/libprocessgroup( 1020): failed to open /acct/uid_10110/pid_2131/cgroup.procs: No such file or directory
I/SELinux ( 3084): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 3084): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 3071): TimaSignature is unavailable
D/ActivityThread( 3071): Added TimaKeyStore provider
D/TimaKeyStoreProvider( 3084): TimaSignature is unavailable
D/ActivityThread( 3084): Added TimaKeyStore provider
D/LocationManagerService( 1020): getProviders()=[passive]
E/        ( 1825): GFX convertToRaster() in Bitmap.cpp for bitmap size 320x240
I/Adreno-EGL( 1825): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 1825): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 1825): Build Date: 04/06/15 Mon
I/Adreno-EGL( 1825): Local Branch: 
I/Adreno-EGL( 1825): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 1825): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 1825):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
I/PCWCLIENTTRACE_LOG( 3084): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG( 3084): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper( 3084): new DMDBOpenHelper instance
I/com.dropbox.sync.android.a( 2958): Prepared cache dir '/data/data/com.dropbox.android/app_DropboxSyncCache/hizqkiq3952astb'.
E/YouTube MDX( 2824): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
D/[SBeam] ( 1294): SBeamEnabler.isSBeamSupported : [-1]
D/[SBeam] ( 1294): SBeamEnabler.isSBeamSupported : EXIST
I/Velvet.VelvetFactory( 3025): refreshing internal icing corpora
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
E/Tethering( 1020): No numeric data
I/GFX GPU raster( 1825): eglCreateImageKHR: EGL_SUCCESS
E/Tethering( 1020): No numeric data
E/Tethering( 1020): No numeric data
,I/glCompressedTexImage2D( 1825): took 0.328646ms for 320*61440 texture 37809
I/draw setup( 1825): took 11.163542ms for 320*240 texture 37809
E/GFX GPU raster( 1825): drawn
I/GFX GPU raster ASTC( 1825): took 49.850779ms for 320*240 texture 12
I/GFX raster( 1825): took 49.943643ms for 320*240 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1825): Bitmap=0xb78f6768 bitmapCt=12 bitmapW=320 bitmapH=240 BitmapInternalFormat=93b1, Counterpart=0xb78fb590 counterpartCT=4 counterpartW=320 counterparth=240
I/ContactAccountLoggerTas( 3025): canRun() : Opted Out
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
D/PCWCLIENTTRACE_DMContentProvider( 3084): [URIMatcher] - result : 2
I/DBG_FMMDM( 3049): [50.20.150420][Line:40][onCreate] FMMApplication NOT Start !
E/        ( 1825): GFX convertToRaster() in Bitmap.cpp for bitmap size 480x640
I/DBG_FMMDM( 3049): [50.20.150420][Line:67][onReceive] android.intent.action.BOOT_COMPLETED
I/GFX GPU raster( 1825): eglCreateImageKHR: EGL_SUCCESS
I/DBG_FMMDM( 3049): [50.20.150420][Line:309][onReceive] android.intent.action.BOOT_COMPLETED
I/glCompressedTexImage2D( 1825): took 0.335520ms for 480*122880 texture 37813
I/draw setup( 1825): took 0.793958ms for 480*640 texture 37813
E/GFX GPU raster( 1825): drawn
D/WifiDisplayAdapter( 1020): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
I/GFX GPU raster ASTC( 1825): took 7.494740ms for 480*640 texture 12
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
I/GFX raster( 1825): took 7.552812ms for 480*640 texture 0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1825): Bitmap=0xb78fb590 bitmapCt=12 bitmapW=480 bitmapH=640 BitmapInternalFormat=93b5, Counterpart=0xb7b3cb20 counterpartCT=4 counterpartW=480 counterparth=640
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
D/WifiDisplayAdapter( 1020): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
E/Tethering( 1020): No numeric data
I/com.dropbox.sync.android.ad( 2958): Dropbox initialized for application: hizqkiq3952astb (com.dropbox.android/240408 DropboxSync/2.0.2 (Android; 5.0.2; samsung SM-A300FU armeabi-v7a; en_US))
E/Zygote  ( 3121): MountEmulatedStorage()
I/libpersona( 3121): KNOX_SDCARD checking this for 1000
E/Zygote  ( 3121): v2
I/libpersona( 3121): KNOX_SDCARD not a persona
I/SELinux ( 3121): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1020): Start proc com.fmm.ds for broadcast com.fmm.ds/.XDSBroadcastReceiver: pid=3121 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/SELinux ( 3121): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 3121): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1020): Killing 2267:com.sec.android.app.sbrowser/u0a127 (adj 15): empty #31
I/ActivityManager( 1020): Killing 2248:com.wsomacp/u0a23 (adj 15): empty #32
D/WifiDisplayAdapter( 1020): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
D/WifiDisplayAdapter( 1020): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
D/TimaKeyStoreProvider( 3121): TimaSignature is unavailable
V/VibratorService( 1020): hasVibrator - useVibetonz: true
E/        ( 1825): GFX convertToRaster() in Bitmap.cpp for bitmap size 440x330
D/ActivityThread( 3121): Added TimaKeyStore provider
I/GFX GPU raster( 1825): eglCreateImageKHR: EGL_SUCCESS
I/AudioService( 1020): getStreamVolume 3 index 70
I/glCompressedTexImage2D( 1825): took 0.476250ms for 440*116864 texture 37809
I/draw setup( 1825): took 1.098802ms for 440*330 texture 37809
E/GFX GPU raster( 1825): drawn
I/AudioService( 1020): getStreamVolume 3 index 70
I/MediaRouter( 3025): Found default route: MediaRouter.RouteInfo{ uniqueId=android/mo:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
I/GFX GPU raster ASTC( 1825): took 5.649063ms for 440*330 texture 12
I/GFX raster( 1825): took 5.730781ms for 440*330 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1825): Bitmap=0xb7b3cb20 bitmapCt=12 bitmapW=440 bitmapH=330 BitmapInternalFormat=93b1, Counterpart=0xb7b51638 counterpartCT=4 counterpartW=440 counterparth=330
I/FavoriteContactNamesSup( 3025): get() : Execute runnable (UI thread)
I/ContactLabelSupplier( 3025): get() : Execute runnable (UI thread)
W/libprocessgroup( 1020): failed to open /acct/uid_10127/pid_2267/cgroup.procs: No such file or directory
W/libprocessgroup( 1020): failed to open /acct/uid_10023/pid_2248/cgroup.procs: No such file or directory
I/ContactLabelSupplier( 3025): get() : OptedIn = false
I/DBG_FMMDS( 3121): [50.18.150420][Line:56][onCreate] FMMDS Application Start
I/DBG_FMMDS( 3121): [50.18.150420][Line:28][<init>] XDBHelper First Call!!!
W/NotificationAccessSettings( 1294): Skipping notification listener service com.android.settings/com.android.settings.accessibility.notificationreminder.NotificationReminderService: it does not require the permission android.permission.BIND_NOTIFICATION_LISTENER_SERVICE
V/VibratorService( 1020): hasVibrator - useVibetonz: true
E/        ( 1825): GFX convertToRaster() in Bitmap.cpp for bitmap size 480x640
I/GFX GPU raster( 1825): eglCreateImageKHR: EGL_SUCCESS
I/glCompressedTexImage2D( 1825): took 0.450000ms for 480*163840 texture 37811
I/draw setup( 1825): took 1.046927ms for 480*640 texture 37811
E/GFX GPU raster( 1825): drawn
V/VibratorService( 1020): hasVibrator - useVibetonz: true
I/GFX GPU raster ASTC( 1825): took 6.018072ms for 480*640 texture 12
I/GFX raster( 1825): took 6.114114ms for 480*640 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1825): Bitmap=0xb7b51638 bitmapCt=12 bitmapW=480 bitmapH=640 BitmapInternalFormat=93b3, Counterpart=0xb7b3c928 counterpartCT=4 counterpartW=480 counterparth=640
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
W/ResourcesManager( 1294): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
E/Zygote  ( 3146): MountEmulatedStorage()
I/libpersona( 3146): KNOX_SDCARD checking this for 10090
E/Zygote  ( 3146): v2
I/libpersona( 3146): KNOX_SDCARD not a persona
I/SELinux ( 3146): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1020): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=3146 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
I/SELinux ( 3146): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1020): Killing 2278:com.sec.tcpdumpservice/1000 (adj 15): empty #31
E/SELinux ( 3146): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 3162): MountEmulatedStorage()
I/libpersona( 3162): KNOX_SDCARD checking this for 10055
E/Zygote  ( 3162): v2
I/libpersona( 3162): KNOX_SDCARD not a persona
I/SELinux ( 3162): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 3162): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 3162): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1020): Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=3162 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
D/TimaKeyStoreProvider( 3146): TimaSignature is unavailable
E/        ( 1825): GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
D/ActivityThread( 3146): Added TimaKeyStore provider
I/GFX construct_block_size_descriptor_2d second part( 1825): took 2.591094ms for 0*0 texture 0
D/PCWCLIENTTRACE_DMContentProvider( 3084): [URIMatcher] - result : 2
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
I/GFX generate_partition_tables( 1825): took 7.684476ms for 0*0 texture 0
I/GFX raster( 1825): took 12.272236ms for 176*144 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1825): Bitmap=0xb7b248e0 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b2, Counterpart=0xb7b24a00 counterpartCT=4 counterpartW=176 counterparth=144
E/DBG_FMMDS( 3121): Warning!!! [50.18.150420][Line:36][xdsDevAdpGetDeviceID] DeviceID read fail!!!!!!!!
E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/cache/
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
E/        ( 1825): GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
I/GFX construct_block_size_descriptor_2d second part( 1825): took 2.139479ms for 0*0 texture 0
D/WifiDisplayAdapter( 1020): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
W/ContextImpl( 2824): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
I/GFX generate_partition_tables( 1825): took 6.184738ms for 0*0 texture 0
I/GFX raster( 1825): took 10.462499ms for 176*144 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1825): Bitmap=0xb7b24b38 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b1, Counterpart=0xb7b24e38 counterpartCT=4 counterpartW=176 counterparth=144
I/Velvet.VelvetFactory( 3025): refreshing search history.
D/TimaKeyStoreProvider( 3162): TimaSignature is unavailable
D/ScoverManager( 1825): registerListener
D/ActivityThread( 3162): Added TimaKeyStore provider
E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/files/
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 2824): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
W/libprocessgroup( 1020): failed to open /acct/uid_1000/pid_2278/cgroup.procs: No such file or directory
D/CoverManagerWhiteLists( 1020): isAllowedToUse : SIGNATURE_MATCH
E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/files/
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
D/CoverManagerWhiteLists( 1020): isAllowedToUse : SIGNATURE_MATCH
D/CoverManager.StateNotifier( 1020): registerListenerCallback : binder = android.os.BinderProxy@31faf9b3, pid : 1825, uid : 1001, type : 1
W/ContextImpl( 2824): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
I/DBG_FMMDS( 3121): [50.18.150420][Line:43][xdbDBInit] 
D/AndroidRuntime( 3131): 
D/AndroidRuntime( 3131): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
D/AndroidRuntime( 3131): CheckJNI is OFF
D/AndroidRuntime( 3131): readGMSProperty: start
D/AndroidRuntime( 3131): readGMSProperty: already setted!!
D/AndroidRuntime( 3131): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 3131): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 3131): readGMSProperty: end
D/AndroidRuntime( 3131): addProductProperty: start
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
D/WifiDisplayAdapter( 1020): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
I/ActivityManager( 1020): Killing 2300:com.sec.android.app.SecSetupWizard/1000 (adj 15): empty #31
I/ActivityManager( 1020): Killing 2335:com.sec.android.gallery3d/u0a39 (adj 15): empty #31
D/ScoverManager( 1294): serviceVersion : 16908288
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
D/InCall  ( 1825): InCallPresenter -  - Finished InCallPresenter.setUp
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
I/System.out( 2958): Thread-389(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
I/System.out( 2958): Thread-389(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 2958): Thread-389(ApacheHTTPLog):isShipBuild true
I/System.out( 2958): Thread-389(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 2958): Thread-389(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
D/EnterpriseController(  281): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  281): getNetworkForDns: using netid 0 for uid 10088
I/System.out( 2958): pool-10-thread-1 calls detatch()
I/DBG_DM  ( 2894): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 0 sec
D/UserAnalysis.PlaceProvider( 3162): PlaceProvider onCreate()
D/SensorService( 1020): [SO] -0.402 0.077 9.864
D/UserAnalysis.SecureDbManager( 3162): Key for secure DB is newly created
D/UserAnalysis.SecurePlaceDbHelper( 3162): SecurePlaceDbHelper() 
D/UserAnalysis( 3162): Create SecureDbHelper
E/USB_UICC(  299): Timeout! No signal received. Retry num = 27
W/libprocessgroup( 1020): failed to open /acct/uid_1000/pid_2300/cgroup.procs: No such file or directory
W/libprocessgroup( 1020): failed to open /acct/uid_10039/pid_2335/cgroup.procs: No such file or directory
W/ContextImpl( 1807): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.qualcomm.qti.services.secureui.BootReceiver.onReceive:30 android.app.ActivityThread.handleReceiver:3125 
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.qualcomm.qti.services.secureui:sui_service, destAppInfo.processName = com.qualcomm.qti.services.secureui:sui_service
D/SecUISvc( 1807): Service started flags 0 startId 1
I/ServiceManager(  318): Waiting for service AtCmdFwd...
D/SecUISvc( 1807): Thread created.
D/IntelligenceServiceApplication( 3162): onCreate()
D/UserAnalysis.UserAnalysisBroadcastReceiver( 3162): Intent(action: android.intent.action.BOOT_COMPLETED) is received.
W/ActivityManager( 1020): userId = 0, bbcId = -10000
I/DBG_FMMDS( 3121): [50.18.150420][Line:63][onCreate] onCreate Db Initialized
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/DBG_FMMDS( 3121): [50.18.150420][Line:363][xdsGetAccount] UZnlD2ITkPmcCbh9srjpN/1auPpXZ1U0673eFrlr5G7ujCmOnoTUvn8Wy3q3+o8W
I/DBG_FMMDS( 3121): [50.18.150420][Line:279][xdsDefaultProfileCheckServerID] VG44Fy9kdMk+/k3D4uP4d3do/3rw5AoymvTy0wXAnzc=
I/DBG_FMMDS( 3121): [50.18.150420][Line:363][xdsGetAccount] UZnlD2ITkPmcCbh9srjpN/1auPpXZ1U0673eFrlr5G7ujCmOnoTUvn8Wy3q3+o8W
I/DBG_FMMDS( 3121): [50.18.150420][Line:376][xdsCheckSamsungAccountForChina] VG44Fy9kdMk+/k3D4uP4d3do/3rw5AoymvTy0wXAnzc=
I/DBG_FMMDS( 3121): [50.18.150420][Line:89][onReceive] Receive Intent : android.intent.action.BOOT_COMPLETED
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
I/DBG_FMMDS( 3121): [50.18.150420][Line:248][onReceive] XCOMMON_INTENT_NOTI_CALLLOG_CLICK
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
D/IntelligenceServiceApplication( 3162): no applications having user consent for prediction
E/Zygote  ( 3224): MountEmulatedStorage()
I/ActivityManager( 1020): Start proc com.samsung.android.scloud.backup for broadcast com.samsung.android.scloud.backup/.SCloudBackupReceiver: pid=3224 uid=10056 gids={50056, 9997, 1028, 1015, 3003} abi=armeabi-v7a
E/Zygote  ( 3224): v2
I/SELinux ( 3224): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/libpersona( 3224): KNOX_SDCARD checking this for 10056
I/libpersona( 3224): KNOX_SDCARD not a persona
V/PlaceDetection v1.0.19 ( 3162): [PlaceDetection::stopService] Service stopped.
I/SELinux ( 3224): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 3224): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/elm:15121( 3146): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:15121( 3146): ELMEngine.ELMEngine( context ).
D/elm:15121( 3146): MDMBridge.setEnterpriseBridge()
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
D/elm:15121( 3146): ELMAbstractReceiver : Receive Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
D/elm:15121( 3146): ElmAgentService : onCreate()
D/elm:15121( 3146): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:15121( 3146): ELMEngine.ServiceHandler.handleMessage( BOOT_COMPLETED ). 
D/elm:15121( 3146): BootCompletedState : startBootCompleted() call
W/MessageQueue( 2824): Handler (android.os.Handler) {2288d5d2} sending message to a Handler on a dead thread
W/MessageQueue( 2824): java.lang.IllegalStateException: Handler (android.os.Handler) {2288d5d2} sending message to a Handler on a dead thread
W/MessageQueue( 2824): 	at android.os.MessageQueue.enqueueMessage(MessageQueue.java:325)
W/MessageQueue( 2824): 	at android.os.Handler.enqueueMessage(Handler.java:631)
W/MessageQueue( 2824): 	at android.os.Handler.sendMessageAtTime(Handler.java:600)
W/MessageQueue( 2824): 	at android.os.Handler.sendMessageDelayed(Handler.java:570)
W/MessageQueue( 2824): 	at android.os.Handler.post(Handler.java:326)
W/MessageQueue( 2824): 	at ffw.a(SourceFile:327)
W/MessageQueue( 2824): 	at guw.a(SourceFile:120)
W/MessageQueue( 2824): 	at guf.c(SourceFile:26)
W/MessageQueue( 2824): 	at gui.run(SourceFile:297)
W/MessageQueue( 2824): 	at android.os.Handler.handleCallback(Handler.java:739)
W/MessageQueue( 2824): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/MessageQueue( 2824): 	at android.os.Looper.loop(Looper.java:145)
W/MessageQueue( 2824): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/elm:15121( 3146): MDMBridge.getAllLicenseInfoFromSDK()
I/elm:15121( 3146): Get License : 0
D/elm:15121( 3146): ElmAgentService : onDestroy().
I/ActivityManager( 1020): Killing 2362:com.sec.android.widgetapp.activeapplicationwidget/u0a139 (adj 15): empty #31
V/EmergencyMode( 1416): [EmergencyReceiver] EmergencyReceiver [android.intent.action.BOOT_COMPLETED]
V/PlaceDetection v1.0.19 ( 3162): [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
D/UserAnalysis.MyPlaceDbPreference( 3162): Constructor Preference
D/TimaKeyStoreProvider( 3224): TimaSignature is unavailable
I/ActivityManager( 1020): Killing 2381:com.sec.android.app.camera/u0a135 (adj 15): empty #31
D/ActivityThread( 3224): Added TimaKeyStore provider
I/FOTA_Client( 2977): [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
I/art     ( 1020): Explicit concurrent mark sweep GC freed 28151(1490KB) AllocSpace objects, 2(38KB) LOS objects, 33% free, 22MB/33MB, paused 40.645ms total 269.816ms
I/FOTA_Client( 2977): [com.sec.android.fotaclient.FotaUpdaterReceiver(93/onReceive)] Auto update settings is activated
I/FOTA_Client( 2977): [IlIlIIllllIllIIIIIll(81/llllIIIllIlIIIIllllI)] Polling time is vaild
W/FOTA_Client( 2977): [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 3246): MountEmulatedStorage()
E/Zygote  ( 3246): v2
I/libpersona( 3246): KNOX_SDCARD checking this for 10013
I/libpersona( 3246): KNOX_SDCARD not a persona
I/ActivityManager( 1020): Start proc com.google.android.onetimeinitializer for broadcast com.google.android.onetimeinitializer/.OneTimeInitializerReceiver: pid=3246 uid=10013 gids={50013, 9997} abi=armeabi-v7a
I/SELinux ( 3246): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 3246): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 3246): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1020): Killing 2218:com.sec.android.app.mt/1000 (adj 15): empty #31
D/TimaKeyStoreProvider( 3246): TimaSignature is unavailable
D/ActivityThread( 3246): Added TimaKeyStore provider
W/libprocessgroup( 1020): failed to open /acct/uid_10139/pid_2362/cgroup.procs: No such file or directory
W/libprocessgroup( 1020): failed to open /acct/uid_10135/pid_2381/cgroup.procs: No such file or directory
W/libprocessgroup( 1020): failed to open /acct/uid_1000/pid_2218/cgroup.procs: No such file or directory
V/OneTimeInitializerReceiver( 3246): OneTimeInitializerReceiver.onReceive
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.onetimeinitializer, destAppInfo.processName = com.google.android.onetimeinitializer
I/LockPatternUtils( 1294): isSmartCardAuthenticationAvailable: false
E/AffinityControl( 3131): AffinityControl: registerfunction enter
I/sCloudBackupApp( 3224): sCloudBackupApp Version Info : 4.04.7.KK_APP
V/OneTimeService( 3246): OneTimeService.onHandleIntent
D/Settings_Utils( 1294): isSupportVNFestival SM-A300FU XEO
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
I/WebViewFactory( 3025): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
E/Zygote  ( 3264): MountEmulatedStorage()
E/Zygote  ( 3264): v2
I/libpersona( 3264): KNOX_SDCARD checking this for 10058
I/libpersona( 3264): KNOX_SDCARD not a persona
I/SELinux ( 3264): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 3264): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1020): Start proc com.samsung.android.scloud.sync for broadcast com.samsung.android.scloud.sync/com.sec.android.sCloudSync.Receivers.TimeChangedReceiver: pid=3264 uid=10058 gids={50058, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux ( 3264): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/ResourceType( 1294): Failure getting entry for 0x7f0202b4 (t=1 e=692) (error -75)
D/AndroidRuntime( 3131): Calling main entry com.android.commands.am.Am
W/ResourceType( 1294): Failure getting entry for 0x7f020510 (t=1 e=1296) (error -75)
I/LibraryLoader( 3025): Loading: webviewchromium
I/LibraryLoader( 3025): Time to load native libraries: 6 ms (timestamps 3589-3595)
I/LibraryLoader( 3025): Expected native library version number "",actual native library version number ""
E/PersonaManagerService( 1020): inState():  stateMachine is null !!
I/PersonaManagerService( 1020): PersonaId don't exist
I/ActivityManager( 1020): do not start freezing screen for locked container getKeyguardshowstate = false
D/TimaKeyStoreProvider( 3264): TimaSignature is unavailable
D/ActivityThread( 3264): Added TimaKeyStore provider
I/ActivityManager( 1020): Killing 2480:com.samsung.android.securitylogagent/1000 (adj 15): empty #31
V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.example.hello
D/CustomFrequencyManagerService( 1020): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1020  pkgName : ACTIVITY_RESUME_BOOSTER@7
W/ActivityManager( 1020): mDVFSHelper.acquire()
I/SurfaceFlinger(  259): id=8 createSurf (16x16),-1 flag=20004, EimLayer(Di
I/SurfaceFlinger(  259): id=9 createSurf (16x16),-1 flag=20004, EimLayer(An
W/art     ( 3025): Attempt to remove local handle scope entry from IRT, ignoring
D/FocusedStackFrame( 1020): Set to : 0
V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.example.hello
D/InputDispatcher( 1020): Focused application set to: xxxx
D/InputDispatcher( 1020): Focus left window: 1477
D/Launcher.HomeView( 1477): onPause
D/PhoneWindow( 1020): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 1020): *FMB* installDecor flags : 25362712
D/AndroidRuntime( 3131): Shutting down VM
D/Launcher( 1477): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
D/PointerIcon( 1020): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1020): setMouseCustomIcon IconType is same.101
D/PhoneWindow( 1020): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1020): *FMB* isFloatingMenuEnabled return false
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
I/SurfaceFlinger(  259): id=10 createSurf (540x960),1 flag=404, iello
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 3286): MountEmulatedStorage()
I/libpersona( 3286): KNOX_SDCARD checking this for 10334
E/Zygote  ( 3286): v2
I/libpersona( 3286): KNOX_SDCARD not a persona
I/SELinux ( 3286): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 3286): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1020): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=3286 uid=10334 gids={50334, 9997, 3003, 3001, 3002} abi=armeabi-v7a
E/SELinux ( 3286): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
I/art     (  308): Explicit concurrent mark sweep GC freed 8693(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 610us total 20.821ms
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
W/libprocessgroup( 1020): failed to open /acct/uid_1000/pid_2480/cgroup.procs: No such file or directory
I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 607us total 17.737ms
D/TimaKeyStoreProvider( 3286): TimaSignature is unavailable
D/ActivityThread( 3286): Added TimaKeyStore provider
V/WindowOrientationListener( 1020): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
V/WindowOrientationListener( 1020): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
V/WindowManager( 1020): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 586us total 16.874ms
D/StatusBarManagerService( 1020): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/ExternalOEMControlProvider( 3264): onCreate
D/PersonaManager( 1020): isKioskContainerExistOnDevice
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
V/ActivityThread( 1477): updateVisibility : ActivityRecord{205ed75b token=android.os.BinderProxy@b5e909a {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
D/Launcher.HomeView( 1477): onStop
V/ActivityThread( 1477): updateVisibility : ActivityRecord{205ed75b token=android.os.BinderProxy@b5e909a {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/Launcher( 1477): onTrimMemory. Level: 20
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 3309): MountEmulatedStorage()
E/Zygote  ( 3309): v2
I/libpersona( 3309): KNOX_SDCARD checking this for 1000
I/libpersona( 3309): KNOX_SDCARD not a persona
I/SELinux ( 3309): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1020): Start proc com.samsung.hs20settings for broadcast com.samsung.hs20settings/.WifiHs20BroadcastReceiver: pid=3309 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/SELinux ( 3309): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 3309): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
D/SettingsProvider( 1020): name = PREVIOUS_SYS_TIME
D/SettingsProvider( 1020): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1020): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1020): selectionArgs: false
D/SettingsProvider( 1020): selectionArgs: 10058
D/SecContentProvider( 1020): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1020): ret = -1
D/WindowOrientationListener( 1020):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
D/SensorService( 1020): [SO] activate (ident=0xb7e10578, enabled=0)
I/Sensors ( 1020): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
W/BackupManagerService( 1020): dataChanged but no participant pkg='com.android.providers.settings' uid=10058
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
D/SettingsProvider( 1020): name = PREVIOUS_ELAPSED_TIME
D/SettingsProvider( 1020): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1020): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1020): selectionArgs: false
D/SettingsProvider( 1020): selectionArgs: 10058
D/SecContentProvider( 1020): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1020): ret = -1
D/SensorManager( 1020): unregisterListener ::   
I/Sensors ( 1020): AccelerometerSensor(0) setDelay : 66000000(ns)
D/SensorService( 1020): [SO] changed settle time [1]
W/BackupManagerService( 1020): dataChanged but no participant pkg='com.android.providers.settings' uid=10058
I/ContactAccountLoggerTas( 3025): canRun() : Opted Out
I/libpersona( 3322): KNOX_SDCARD checking this for 1000
D/SensorService( 1020): [SO] setDelay [66000000]
I/libpersona( 3322): KNOX_SDCARD not a persona
D/SensorService( 1020): [SO] activate (ident=0xb7e10578, enabled=1)
D/SensorService( 1020): [SO] AR_init
I/Sensors ( 1020): AccelerometerSensor enable: mEnabled 0, handle 0, en 1
E/Zygote  ( 3322): MountEmulatedStorage()
E/Zygote  ( 3322): v2
I/SELinux ( 3322): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
W/art     ( 3131): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
I/SELinux ( 3322): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/SecKeyguardClockSingleView( 1177): Ignore. Because it is same clock text
E/SELinux ( 3322): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/SensorManager( 1020): registerListener :: 1600221811, Screen Orientation Sensor, 66000, 0,  
I/UpdateIcingCorporaServi( 3025): Updating corpora: APPS=MAYBE, CONTACTS=MAYBE
I/ActivityManager( 1020): Start proc com.sec.android.app.servicemodeapp for broadcast com.sec.android.app.servicemodeapp/.ServiceModeAppBroadcastReceiver: pid=3322 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/SecKeyguardClockSingleView( 1177): Ignore. Because it is same clock text
,V/VibratorService( 1020): hasVibrator - useVibetonz: true
,I/art     ( 1615): Explicit concurrent mark sweep GC freed 7294(355KB) AllocSpace objects, 0(0B) LOS objects, 31% free, 4MB/6MB, paused 5.418ms total 79.518ms
,D/TimaKeyStoreProvider( 3322): TimaSignature is unavailable
,D/ActivityThread( 3322): Added TimaKeyStore provider
,D/TimaKeyStoreProvider( 3309): TimaSignature is unavailable
,D/ActivityThread( 3309): Added TimaKeyStore provider
,D/SensorService( 1020): [SO] Reset Rotation Old [100], Init [1]
,W/ResourcesManager( 3322): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,I/ServiceMode( 3322): received = ACTION_BOOT_COMPLETED
,I/ServiceMode( 3322): setReferenceIsDumpState : 0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3343): MountEmulatedStorage()
E/Zygote  ( 3343): v2
I/libpersona( 3343): KNOX_SDCARD checking this for 1000
I/libpersona( 3343): KNOX_SDCARD not a persona
,I/SELinux ( 3343): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/WebViewFactory( 3286): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,I/SELinux ( 3343): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SELinux ( 3343): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
I/ActivityManager( 1020): Start proc com.wssnps for broadcast com.wssnps/.smlNpsReceiverDefault: pid=3343 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 1020): Killing 2465:com.android.calendar/u0a131 (adj 15): empty #31
,D/SensorService( 1020): [SO] -0.402 0.077 9.864
D/SensorService( 1020): [SO] [100 -> 255]
,I/FactoryTestApp( 2500): [IPCWriterToSecPhoneService$disConnectSecPhoneService](2865)  
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 com.android.server.ssrm.ad.ec:-1 com.android.server.ssrm.ae.handleMessage:-1 android.os.Handler.dispatchMessage:102 android.os.Looper.loop:145 
,I/LibraryLoader( 3286): Loading: webviewchromium
,I/ActivityManager( 1020): Killing 2527:com.android.keychain/1000 (adj 15): empty #31
,I/LibraryLoader( 3286): Time to load native libraries: 6 ms (timestamps 3995-4001)
I/LibraryLoader( 3286): Expected native library version number "",actual native library version number ""
,W/GAV2    ( 3025): Thread[Background Non-Blocking-0,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,D/TimaKeyStoreProvider( 3343): TimaSignature is unavailable
,D/ActivityThread( 3343): Added TimaKeyStore provider
,I/Hs20UtilService( 3309): onCreate
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
W/GAV2    ( 3025): Thread[Background Non-Blocking-0,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,I/ContactAccountLoggerTas( 3025): canRun() : Opted Out
I/ContactAccountLoggerTas( 3025): canRun() : Opted Out
,I/ContactAccountLoggerTas( 3025): canRun() : Opted Out
,E/Zygote  ( 3362): MountEmulatedStorage()
,E/Zygote  ( 3362): v2
I/libpersona( 3362): KNOX_SDCARD checking this for 10018
I/libpersona( 3362): KNOX_SDCARD not a persona
,I/SELinux ( 3362): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/Hs20UtilService( 3309): Starting #1
,I/SELinux ( 3362): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,I/Hs20UtilService( 3309): Message received 5003
,E/SELinux ( 3362): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1020): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=3362 uid=10018 gids={50018, 9997, 3003} abi=armeabi-v7a
,D/EnterpriseController(  281): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  281): getNetworkForDns: using netid 0 for uid 10052
W/NetworkUtils( 3025): OkHttp exception
D/TimaKeyStoreProvider( 3362): TimaSignature is unavailable
W/libprocessgroup( 1020): failed to open /acct/uid_1000/pid_2527/cgroup.procs: No such file or directory
W/libprocessgroup( 1020): failed to open /acct/uid_10131/pid_2465/cgroup.procs: No such file or directory
D/ActivityThread( 3362): Added TimaKeyStore provider
I/ContactAccountLoggerTas( 3025): canRun() : Opted Out
,V/WebViewChromiumFactoryProvider( 3286): Binding Chromium to main looper Looper (main, tid 1) {222e0be4}
,I/LibraryLoader( 3286): Expected native library version number "",actual native library version number ""
,I/chromium( 3286): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/LockPatternUtils( 1294): isSmartCardAuthenticationAvailable: false
,I/DBG_DM  ( 2894): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 1 sec
,I/KLMS-2.5.123: ( 3362): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Mon Jan 11 23:48:17 GMT+01:00 2016
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,I/BrowserStartupController( 3286): Initializing chromium process, renderers=0
,W/art     ( 3286): Attempt to remove local handle scope entry from IRT, ignoring
,D/NPS_WSSNPS( 3343): [] android.intent.action.BOOT_COMPLETED
,W/chromium( 3286): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
,W/ContextImpl( 3343): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.wssnps.smlNpsReceiverDefault.onReceive:35 android.app.ActivityThread.handleReceiver:3125 
,I/KLMS-2.5.123: ( 3362): KLMSAbstractReciever(): onReceive().END.
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.wssnps, destAppInfo.processName = com.wssnps
,V/EmergencyMode( 1416): [EmergencyBase] setBootTime
V/EmergencyMode( 1416): [EmergencyFactory] No Recovery State, kill my self.
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,D/NPS_WSSNPS( 3343): [] Service onCreate!!
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,W/chromium( 3286): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 3286): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
,I/chromium( 3286): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
,E/Zygote  ( 3391): MountEmulatedStorage()
E/Zygote  ( 3391): v2
I/libpersona( 3391): KNOX_SDCARD checking this for 10020
I/libpersona( 3391): KNOX_SDCARD not a persona
,I/SELinux ( 3391): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,E/USB_UICC(  299): Timeout! No signal received. Retry num = 28,
,I/SurfaceFlinger(  259): id=7 Removed Mauncher (5/8)
I/SELinux ( 3391): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SMD     (  291): DCD OFF
I/SurfaceFlinger(  259): id=7 Removed Mauncher (-2/8)
,I/KLMS-2.5.123: ( 3362): KLMSIntentService(): onCreate()
,E/SELinux ( 3391): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1020): Start proc com.android.managedprovisioning for broadcast com.android.managedprovisioning/.BootReminder: pid=3391 uid=10020 gids={50020, 9997, 1028, 3003} abi=armeabi-v7a
D/BluetoothAdapter( 3286): 731035725: getState() :  mService = null. Returning STATE_OFF
I/Adreno-EGL( 3286): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 3286): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 3286): Build Date: 04/06/15 Mon
I/Adreno-EGL( 3286): Local Branch: 
I/Adreno-EGL( 3286): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 3286): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 3286):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,I/KLMS-2.5.123: ( 3362): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
I/KLMS-2.5.123: ( 3362): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,D/NPS_WSSNPS( 3343): [50.150321] NpsServiceTask Start
,E/Zygote  ( 3408): MountEmulatedStorage(),
E/Zygote  ( 3408): v2
I/libpersona( 3408): KNOX_SDCARD checking this for 1000
I/libpersona( 3408): KNOX_SDCARD not a persona
I/SELinux ( 3408): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 3408): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 3408): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1020): Start proc com.samsung.android.app.accesscontrol for broadcast com.samsung.android.app.accesscontrol/.AccessControlReceiver: pid=3408 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/KLMS-2.5.123: ( 3362): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,I/KLMS-2.5.123: ( 3362): KLMSIntentService(): BOOT_COMPLETED
,D/NPS_WSSNPS( 3343): [50.150321] smlDBHelper
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 3391): TimaSignature is unavailable
,D/ActivityThread( 3391): Added TimaKeyStore provider
,D/TimaKeyStoreProvider( 3408): TimaSignature is unavailable
,D/ActivityThread( 3408): Added TimaKeyStore provider
,E/Zygote  ( 3430): MountEmulatedStorage()
I/libpersona( 3430): KNOX_SDCARD checking this for 1000
E/Zygote  ( 3430): v2
I/libpersona( 3430): KNOX_SDCARD not a persona
I/SELinux ( 3430): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 3430): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 3430): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1020): Start proc com.sec.factory.camera for broadcast com.sec.factory.camera/com.sec.android.app.camerafirmware.CameraFirmwareBroadCastReceiver: pid=3430 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 3430): TimaSignature is unavailable
,D/ActivityThread( 3430): Added TimaKeyStore provider
,I/KLMS-2.5.123: ( 3362): KLMSIntentService(): onDestroy()
,I/NPS_WSSNPS( 3343): [50.150321] AsyncBulkFlagCheck
,I/RlzPingService( 3071): Setting next ping for 1453157297250
,I/NPS_WSSNPS( 3343): [50.150321] IsRemain_AsyncBulkCheck
,I/NPS_WSSNPS( 3343): [50.150321] IsRemain_Asyncing nothing
,W/ContextImpl( 3343): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:2069 android.content.ContextWrapper.stopService:538 com.wssnps.h.run:107 java.util.Timer$TimerImpl.run:284 <bottom of call stack> 
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.wssnps, destAppInfo.processName = com.wssnps
,D/NPS_WSSNPS( 3343): [50.150321] Service onDestroy
,I/CameraApp( 3430): CameraApp.onCreate()... mFeature : null
,I/testFeature( 3430): Feature.Feature(context)
,I/testFeature( 3430): Feature.readInternalDefaultXml()
I/testFeature( 3430): ResetFeatureValue
,D/SettingsProvider( 1020): name = access_control_enabled
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,I/CameraFirmware_broadcast( 3430): CameraFirmwareBroadCastReceiver...
,I/CameraApp( 3430): CameraApp.getAppFeature()...
,E/Zygote  ( 3451): MountEmulatedStorage(),
E/Zygote  ( 3451): v2
I/libpersona( 3451): KNOX_SDCARD checking this for 10065
I/libpersona( 3451): KNOX_SDCARD not a persona
I/SELinux ( 3451): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,W/chromium( 3286): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,I/SELinux ( 3451): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3451): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1020): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=3451 uid=10065 gids={50065, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/NPS_WSSNPS( 3343): [50.150321] smlBRConfigurationDelete
,I/NPS_WSSNPS( 3343): [50.150321] smlBRMessageDelete
I/NPS_WSSNPS( 3343): [50.150321] smlBREmailDelete
,W/chromium( 3286): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,I/NPS_WSSNPS( 3343): [50.150321] smlBRNetworkDelete
,I/NPS_WSSNPS( 3343): [50.150321] smlBRCallLogDelete
I/NPS_WSSNPS( 3343): [50.150321] smlBRMiniDiaryDelete
,I/NPS_WSSNPS( 3343): [50.150321] smlBRPenMemoMDelete
I/NPS_WSSNPS( 3343): [50.150321] smlBRSMemoDelete
I/NPS_WSSNPS( 3343): [50.150321] cpuBooster release : false
,E/Zygote  ( 3467): MountEmulatedStorage()
E/Zygote  ( 3467): v2
I/libpersona( 3467): KNOX_SDCARD checking this for 10095
I/libpersona( 3467): KNOX_SDCARD not a persona
,I/SELinux ( 3467): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 3467): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 3467): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1020): Start proc com.samsung.android.provider.filterprovider for broadcast com.samsung.android.provider.filterprovider/.FilterProviderReceiver: pid=3467 uid=10095 gids={50095, 9997, 1023} abi=armeabi-v7a
I/ActivityManager( 1020): Killing 2584:com.mobeam.barcodeService/1000 (adj 15): empty #31
D/TimaKeyStoreProvider( 3451): TimaSignature is unavailable
D/ActivityThread( 3451): Added TimaKeyStore provider
,W/art     ( 3286): Attempt to remove local handle scope entry from IRT, ignoring
,D/NPS_WSSNPS( 3343): [50.150321] dsServerSocket close
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
W/AwContents( 3286): onDetachedFromWindow called when already detached. Ignoring
,E/Zygote  ( 3484): MountEmulatedStorage()
,E/Zygote  ( 3484): v2
I/libpersona( 3484): KNOX_SDCARD checking this for 1000
I/libpersona( 3484): KNOX_SDCARD not a persona
,I/SELinux ( 3484): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1020): Start proc com.samsung.android.MtpApplication for broadcast com.samsung.android.MtpApplication/.MtpReceiver: pid=3484 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 3484): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3484): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/PhoneWindow( 3286): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 3286): *FMB* installDecor flags : 8456448
,D/TimaKeyStoreProvider( 3467): TimaSignature is unavailable
D/ActivityThread( 3467): Added TimaKeyStore provider
,I/ActivityManager( 1020): Killing 2605:flipboard.boxer.app/u0a97 (adj 15): empty #31
,I/ActivityManager( 1020): Killing 2636:org.simalliance.openmobileapi.service/1101 (adj 15): empty #31
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/FileApkUtils( 1788): Spent 89ms computing apk sha1.
D/SystemWebViewEngine( 3286): CordovaWebView is running on device made by: samsung
,D/FileApkUtils( 1788): Module already staged or being staged:chimera-modules/MapsModule.apk
,I/art     ( 1788): DexFile_isDexOptNeeded failed to open oat file '/data/dalvik-cache/arm/data@data@com.google.android.gms@app_chimera@chimera-module-root@module-cf053f76526e84be2388d3f24ecde21377d895e5@MapsModule.apk@classes.dex' for file location '/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-cf053f76526e84be2388d3f24ecde21377d895e5/MapsModule.apk': Failed to open oat filename for reading: No such file or directory
,W/ContextImpl( 1294): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver$InitSerachDBThread.run:130 <bottom of call stack> 
,D/TimaKeyStoreProvider( 3484): TimaSignature is unavailable
,D/ActivityThread( 3484): Added TimaKeyStore provider
W/ContextImpl( 1294): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver$InitSerachDBThread.run:131 <bottom of call stack> 
,W/art     ( 3286): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3286): Attempt to remove local handle scope entry from IRT, ignoring
,I/ActivityManager( 1020): Killing 2672:com.sec.android.app.taskmanager/u0a153 (adj 15): empty #31
,I/ActivityManager( 1020): Killing 2687:com.sec.usbsettings/1000 (adj 15): empty #31
,I/SettingSearch/SearchIntentReceiver( 1294): InitSerachDBThread thread end!
I/ActivityManager( 1020): Killing 2085:flipboard.app/u0a96 (adj 15): empty #31
,D/FileShare-Server( 3451): ServerBroadcastReceiver.onReceive - action android.intent.action.BOOT_COMPLETED // null
,D/DexOptUtils( 1788): Module /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-cf053f76526e84be2388d3f24ecde21377d895e5/MapsModule.apk is already optimized. Bailing.
,D/FileApkUtils( 1788): Keeping up-to-date module: module-cf053f76526e84be2388d3f24ecde21377d895e5
,E/MTPRx   ( 3484): In MtpReceiverandroid.intent.action.BOOT_COMPLETED
,D/SecContentProvider2( 1020): uri = 14 selection = getSealedState
,D/SecContentProvider2( 1020): mCursor = null
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/SecContentProvider2( 1020): uri = 14 selection = getSealedUsbMassStorageState
,D/SecContentProvider2( 1020): mCursor = null
,V/MTPRx   ( 3484): sealedState: false,
V/MTPRx   ( 3484): sealedUsbMassStorageState: false
,D/SettingsProvider( 1020): name = mtp_usb_connection_status
,D/PreloadFilterInstaller( 3467): uses FILTER_DB_VER_1
,D/ChimeraCfgMgr( 1788): Reading stored module config
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/SQLiteLog( 3467): (284) automatic index on titles(filter_id)
,D/SettingsProvider( 1020): name = media_player_mode
,I/SecKeyguardClockSingleView( 1177): Ignore. Because it is same clock text
,I/FilterProviderReceiver( 3467): onReceive in FilterProviderReceiver
I/FilterProviderReceiver( 3467): onReceive in FilterProviderReceiver when ACTION_BOOT_COMPLETED
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,I/Icing   ( 1788): Storage manager: low false usage 2.11MB avail 9.99GB capacity 11.63GB
,E/Zygote  ( 3506): MountEmulatedStorage(),
I/libpersona( 3506): KNOX_SDCARD checking this for 10098
E/Zygote  ( 3506): v2
I/libpersona( 3506): KNOX_SDCARD not a persona
,I/SELinux ( 3506): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/ActivityManager( 1020): Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=3506 uid=10098 gids={50098, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
I/SELinux ( 3506): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3506): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/art     (  308): Explicit concurrent mark sweep GC freed 8744(372KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 603us total 23.674ms
,D/OpenGLRenderer( 3286): Render dirty regions requested: true
,D/TimaKeyStoreProvider( 3506): TimaSignature is unavailable,
D/ActivityThread( 3506): Added TimaKeyStore provider
I/ActivityManager( 1020): Killing 2188:com.android.mms/u0a41 (adj 15): empty #31,
,W/libprocessgroup( 1020): failed to open /acct/uid_10097/pid_2605/cgroup.procs: No such file or directory
,W/libprocessgroup( 1020): failed to open /acct/uid_1000/pid_2584/cgroup.procs: No such file or directory
W/libprocessgroup( 1020): failed to open /acct/uid_1101/pid_2636/cgroup.procs: No such file or directory
,W/libprocessgroup( 1020): failed to open /acct/uid_10153/pid_2672/cgroup.procs: No such file or directory
D/ActivityManager( 1020): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1020): postActiveUserChange for user 0
,I/KnoxTimeoutHandler( 1020): postActiveUserChange, showWhenLocked: false
D/KnoxTimeoutHandler( 1020): handleActiveUserChange for user 0
D/PersonaManagerService( 1020): getPersonasForUser(): returning null!
W/libprocessgroup( 1020): failed to open /acct/uid_1000/pid_2687/cgroup.procs: No such file or directory
W/libprocessgroup( 1020): failed to open /acct/uid_10096/pid_2085/cgroup.procs: No such file or directory
,D/PhoneWindow( 3286): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 3286): *FMB* isFloatingMenuEnabled return false
,D/GmsModuleFndr( 1788): Beginning GMS chimera module scan
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 591us total 26.603ms
,I/SurfaceFlinger(  259): id=11 createSurf (1x1),1 flag=404, NainActivit
,D/InputDispatcher( 1020): Focus entered window: 3286
,D/PointerIcon( 1020): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1020): setMouseCustomIcon IconType is same.101
D/SRIB_DCS( 3286): log_dcs ThreadedRenderer::initialize entered! 
I/OpenGLRenderer( 3286): Initialized EGL, version 1.4
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 564us total 16.829ms
,D/OpenGLRenderer( 3286): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
,D/OpenGLRenderer( 3286): Enabling debug mode 0
,D/PackageIntentReceiver( 3506): ACTION_BOOT_COMPLETED
,D/PackageIntentReceiver( 3506): jangil::ACTION_BOOT_COMPLETED::do not need pkg remove..
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3526): MountEmulatedStorage()
I/libpersona( 3526): KNOX_SDCARD checking this for 10099
E/Zygote  ( 3526): v2
I/libpersona( 3526): KNOX_SDCARD not a persona
I/ActivityManager( 1020): Start proc com.google.android.gm for broadcast com.google.android.gm/.GoogleMailDeviceStartupReceiver: pid=3526 uid=10099 gids={50099, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 3526): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 3526): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 3526): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 3526): TimaSignature is unavailable
,D/ActivityThread( 3526): Added TimaKeyStore provider
,D/InputMethodManagerService( 1020): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/PanelView( 1177): There is/are notification(s) 
,I/Timeline( 3286): Timeline: Activity_idle id: android.os.BinderProxy@ccf4ebd time:34853
,D/SettingsProvider( 1020): name = mtp_usb_conditions_met
,I/SecKeyguardClockSingleView( 1177): Ignore. Because it is same clock text
,D/CountryDetector( 1020): No listener is left
,D/GmsModuleFndr( 1788): Module pkg com.google.android.apps.kids.kidsetup not installed, skipping
,D/ChimeraCfgMgr( 1788): Beginning module configuration check
,I/ActivityManager( 1020): Displayed Component not be shown by security: +1s250ms
,D/CustomFrequencyManagerService( 1020): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1020  tag : ACTIVITY_RESUME_BOOSTER@7
,I/Timeline( 1020): Timeline: Activity_windows_visible id: ActivityRecord{27604032 u0 com.example.hello/.MainActivity t2} time:34916
W/ActivityManager( 1020): mDVFSHelper.release()
,D/CustomFrequencyManagerService( 1020): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1020  pkgName : ACTIVITY_RESUME_BOOSTER@11
,W/libprocessgroup( 1020): failed to open /acct/uid_10041/pid_2188/cgroup.procs: No such file or directory
,W/InstanceID/Rpc( 1788): Found 10011
,I/ActivityManager( 1020): Killing 2742:com.sec.android.app.safetyassurance/u0a43 (adj 15): empty #31
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/libprocessgroup( 1020): failed to open /acct/uid_10043/pid_2742/cgroup.procs: No such file or directory
,D/ChimeraCfgMgr( 1788): Module APKs unchanged, check complete
,D/SettingsProvider( 1020): name = mtp_running_status
,I/SecKeyguardClockSingleView( 1177): Ignore. Because it is same clock text
,I/SamsungIME( 1768): getCurrentCandidateView
,I/SurfaceFlinger(  259): id=10 Removed iello (7/8)
,I/SurfaceFlinger(  259): id=10 Removed iello (-2/8)
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/DBG_DM  ( 2894): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 2 sec
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/USB_UICC(  299): Timeout! No signal received. Retry num = 29
,D/SettingsProvider( 1020): name = media_mount_count
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/SecKeyguardClockSingleView( 1177): Ignore. Because it is same clock text
,D/SettingsProvider( 1020): name = mtp_sync_alive
I/ServiceManager(  318): Waiting for service AtCmdFwd...
,D/CustomFrequencyManagerService( 1020): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1020  tag : ACTIVITY_RESUME_BOOSTER@11
,I/SecKeyguardClockSingleView( 1177): Ignore. Because it is same clock text
,I/chromium( 3286): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,E/AndroidProtocolHandler( 3286): Unable to open asset URL: file:///android_asset/www/jxcore.js
,D/SettingsProvider( 1020): name = sdcard_launch
,I/SecKeyguardClockSingleView( 1177): Ignore. Because it is same clock text
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/SamsungIME( 1768): Dismiss ExpandCandiate
,W/ActivityManager( 1020): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/SamsungIME( 1768): getDebugLevel  : 0x4f4c
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,D/JsMessageQueue( 3286): Set native->JS mode to OnlineEventsBridgeMode
,I/Gmail   ( 3526): getAccountsCursor
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/SettingsProvider( 1020): name = boot_time_connected
,I/SecKeyguardClockSingleView( 1177): Ignore. Because it is same clock text
,D/GCM     ( 1788): COMPAT: Multi user not supported
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
V/GLSActivity( 1633): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1633): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/SettingsProvider( 1020): name = mtp_open_session
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/GAV2    ( 3526): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,V/GLSActivity( 1633): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/chromium( 3286): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 3286): 
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/GCM     ( 1633): COMPAT: Multi user not supported
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1020): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/ActivityManager( 1020): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,I/SamsungIME( 1768): getDebugLevel  : 0x4f4c
I/GCoreUlr( 1788): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}]
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/CheckinService( 1788): Checkin interval check for package: unspecified last checkin: 1452490772288 min interval config: 0 actual interval: 61726125
I/SamsungIME( 1768): KeybaordView init() : load resources
,I/SecKeyguardClockSingleView( 1177): Ignore. Because it is same clock text
,I/Gmail   ( 3526): Observing account changes for notifications
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,I/PCWCLIENTTRACE_PushUtil( 3084): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 3084): sales region : global
,I/PCWCLIENTTRACE_PushUtil( 3084): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 3084): [onReceive] - android.intent.action.BOOT_COMPLETED
,D/PCWCLIENTTRACE_SYSTEMReceiver( 3084): ACTION_BOOTUP - Version: 4.82
,D/PCWCLIENTTRACE_SYSTEMReceiver( 3084): ACTION_BOOTUP - Push type: [SPP, GCM]
,D/jxcore_app_log( 3286): JniHelper::setJavaVM(0xb754e448), pthread_self() = -1212414152
,I/SamsungIME( 1768): getCurrentKeyboard
I/SamsungIME( 1768): getTextKeyboard
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
I/CheckinService( 1788): Disabling old GoogleServicesFramework version
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,W/ActivityManager( 1020): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/PCWCLIENTTRACE_PCWHandler( 3084): [ensureRegistration] - netwrok is not available. action ignored
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.dsi.ant.server.AntService.startService:135 com.dsi.ant.server.startup.BootCompletedReceiver.onReceive:41 ,
W/ContextImpl( 1020): Implicit intents with startService are not safe: Intent { act=com.dsi.ant.server.IAntHal } android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.dsi.ant.server.AntService.startService:135 
,E/Zygote  ( 3588): MountEmulatedStorage()
,E/Zygote  ( 3588): v2
I/libpersona( 3588): KNOX_SDCARD checking this for 10028
I/libpersona( 3588): KNOX_SDCARD not a persona
,I/SELinux ( 3588): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 3588): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
E/SELinux ( 3588): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,W/jxcore-log( 3286): Initializing JXcore engine
W/jxcore-log( 3286): JXcore engine is ready
,I/ActivityManager( 1020): Start proc com.vlingo.midas for broadcast com.vlingo.midas/com.vlingo.core.facade.lmtt.LmttReceiver: pid=3588 uid=10028 gids={50028, 9997, 1028, 1015, 3003, 3002, 3001} abi=armeabi-v7a
,I/ActivityManager( 1020): Killing 2617:com.sec.android.app.clockpackage/u0a81 (adj 15): empty #31
,D/ChimeraCfgMgr( 1788): Loading module com.google.android.gms.gass from APK com.google.android.gms
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1020): level:100, scale:100, status:2, health:2, present:true, voltage: 4287, temperature: 249, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3602): MountEmulatedStorage()
E/Zygote  ( 3602): v2
I/libpersona( 3602): KNOX_SDCARD checking this for 1000
I/libpersona( 3602): KNOX_SDCARD not a persona
,I/SELinux ( 3602): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 3602): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,D/SamsungIME( 1768): [SwiftkeyWrapper] currentLangauge : 1701729619
E/SELinux ( 3602): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/BootCompletedReceiver( 1788): Will schedule periodic tasks:android.intent.action.BOOT_COMPLETED.,
D/BootCompletedReceiver( 1788): Got an BootCompleted event.
I/ActivityManager( 1020): Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=3602 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/TimaKeyStoreProvider( 3588): TimaSignature is unavailable
D/ActivityThread( 3588): Added TimaKeyStore provider
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,E/Gmail   ( 3526): Error finding the version of the Email provider.....
E/Gmail   ( 3526): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 3526): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:165)
E/Gmail   ( 3526): 	at com.google.android.gm.EmailMigrationService.aU(SourceFile:1236)
E/Gmail   ( 3526): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:188)
E/Gmail   ( 3526): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 3526): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 3526): 	at android.os.Looper.loop(Looper.java:145)
E/Gmail   ( 3526): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/EmailMigration( 3526): We do not support migrating this version of the Email provider.
,W/libprocessgroup( 1020): failed to open /acct/uid_10081/pid_2617/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 3602): TimaSignature is unavailable
,D/ActivityThread( 3602): Added TimaKeyStore provider,
E/audit   ( 1777): type=1400 msg=audit(1452552498.611:203): avc:  denied  { ioctl } for  pid=3585 comm="Thread-463" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
E/audit   ( 1777):  SEPF_SM-A300FU_5.0.2_0027
E/audit   ( 1777): type=1300 msg=audit(1452552498.611:203): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=4 a3=9e2808f8 items=0 ppid=308 ppcomm=main pid=3585 auid=4294967295 uid=10334 gid=10334 euid=10334 suid=10334 fsuid=10334 egid=10334 sgid=10334 fsgid=10334 ses=4294967295 tty=(none) comm="Thread-463" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1777): type=1320 msg=audit(1452552498.611:203): 
,I/MotionRecognitionService( 1020): Plugged
I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,W/jxcore-log( 3286): Starting JXcore engine
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,D/PowerUI ( 1177): Cable  true --> true mBootCompleted : true
,D/PowerUI ( 1177): Sending cableIntent : Intent { act=com.samsung.systemui.power.action.ACTION_CABLE_CONNECTED }
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,D/BootCompletedReceiver( 1788): Will NOT schedule AdAttestation signal task because it's disabled.
,I/Gmail   ( 3526): getAccountsCursor
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1177): level :100 plugged : 2
,I/System.out( 3588): Inside onCreate() of WakeupTriggerProvide
,I/System.out( 3588): Inside WakeupProvider
,I/CheckinService( 1788): Checking schedule, now: 1452552498729 next: 1453057699120
,I/CheckinService( 1788): active receiver: disabled
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,W/jxcore-log( 3286): Platform android
W/jxcore-log( 3286): 
,W/jxcore-log( 3286): Process ARCH arm
W/jxcore-log( 3286): 
,D/SystemUpdateService( 1788): onCreate
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.process.gapps
,I/VlingoApplication( 3588): VlingoApplication appVersion ='11.7.0.1.40139', coreVersion = '2.6.1.16800', ro.csc.sales_code=XEO
,I/jxcore-log( 3286): JXcore Cordova bridge is ready!
I/jxcore-log( 3286): 
,W/jxcore-log( 3286): JXcore engine is started
,I/GoogleHttpClient( 1615): GMS http client unavailable, use old client
,E/jxcore  ( 3286): Error!: No such native module /data/data/com.example.hello/files/www/jxcore/app.js
E/jxcore  ( 3286): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,D/FactoryTestApp( 2500): [DummyFtClient$onDestroy](2500) Destroy DummyFtClient service
,D/PhoneWindow( 3286): *FMB* installDecor mIsFloating : true
D/PhoneWindow( 3286): *FMB* installDecor flags : 8388610
,I/art     ( 1020): Explicit concurrent mark sweep GC freed 36981(2027KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 22MB/33MB, paused 4.945ms total 163.864ms
,D/InputDispatcher( 1020): Focus left window: 3286
D/InputDispatcher( 1020): Focus entered window: 3286
,D/PointerIcon( 1020): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1020): setMouseCustomIcon IconType is same.101
,D/BluetoothAdapter( 3588): 214912701: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothAdapter( 3588): 214912701: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 3588): 214912701: getState() :  mService = null. Returning STATE_OFF
I/VlingoAndroidCore( 3588): AppName: SamsungTproject, Core: 2.6.1.16800, SDK: 2.0.2137, EDM:16800
,D/PhoneWindow( 3286): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
,D/PhoneWindow( 3286): *FMB* isFloatingMenuEnabled return false
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3630): MountEmulatedStorage(),
E/Zygote  ( 3630): v2
,I/libpersona( 3630): KNOX_SDCARD checking this for 10102
I/libpersona( 3630): KNOX_SDCARD not a persona
,I/SELinux ( 3630): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 3630): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3630): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
,I/ActivityManager( 1020): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.BootReceiver: pid=3630 uid=10102 gids={50102, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,D/FactoryTestApp( 2500): [Support$Values.getString](2500) id=MODEL_COMMUNICATION_MODE, value=gsm
I/FactoryTestApp( 2500): [ModuleCommon$isConnectionModeNone](2500) mConnectionMode = gsm
I/FactoryTestApp( 2500): [ModuleCommon$isRunningFtClient](2500) RUNNING_FTCLIENT : false
D/FactoryTestApp( 2500): [DummyFtClient$onDestroy](2500) kill process
I/Process ( 2500): Sending signal. PID: 2500 SIG: 9
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,D/SystemUpdateService( 1788): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,W/ActivityManager( 1020): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/SurfaceFlinger(  259): id=12 createSurf (1x1),1 flag=4, NainActivit
,E/ActivityThread( 3526): Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.J@2c64ce61 that was originally bound here
E/ActivityThread( 3526): android.app.ServiceConnectionLeaked: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.J@2c64ce61 that was originally bound here
E/ActivityThread( 3526): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1144)
E/ActivityThread( 3526): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1038)
E/ActivityThread( 3526): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2154)
E/ActivityThread( 3526): 	at android.app.ContextImpl.bindService(ContextImpl.java:2137)
E/ActivityThread( 3526): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 3526): 	at com.android.emailcommon.service.H.a(SourceFile:181)
E/ActivityThread( 3526): 	at com.android.emailcommon.service.H.mb(SourceFile:224)
E/ActivityThread( 3526): 	at com.android.email.service.n.j(SourceFile:160)
E/ActivityThread( 3526): 	at com.android.email.provider.b.a(SourceFile:171)
E/ActivityThread( 3526): 	at com.android.email.provider.b.F(SourceFile:115)
E/ActivityThread( 3526): 	at com.android.email.service.EmailBroadcastProcessorService.kD(SourceFile:305)
E/ActivityThread( 3526): 	at com.android.email.service.EmailBroadcastProcessorService.onHandleIntent(SourceFile:130)
E/ActivityThread( 3526): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/ActivityThread( 3526): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3526): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread( 3526): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/ActivityManager( 1020): Unbind failed: could not find connection for android.os.BinderProxy@1e0eed75
D/TimaKeyStoreProvider( 3630): TimaSignature is unavailable
,D/ActivityThread( 3630): Added TimaKeyStore provider
I/DBG_DM  ( 2894): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 3 sec
W/ContextImpl( 3602): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:53 android.app.ActivityThread.handleReceiver:3125 
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
W/ResourcesManager( 3630): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
D/SRIB_DCS( 3286): log_dcs ThreadedRenderer::initialize entered! 
E/Zygote  ( 3648): MountEmulatedStorage()
E/Zygote  ( 3648): v2
I/libpersona( 3648): KNOX_SDCARD checking this for 1000
I/libpersona( 3648): KNOX_SDCARD not a persona
,I/SELinux ( 3648): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/SELinux ( 3648): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,I/ActivityManager( 1020): Start proc com.sec.bcservice for broadcast com.sec.bcservice/.BCServiceReceiver: pid=3648 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 1020): Process com.sec.factory (pid 2500)(adj 0) has died(25,706),
E/SELinux ( 3648): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/USB_UICC(  299): Timeout! No signal received. Retry num = 30
,D/TimaKeyStoreProvider( 3648): TimaSignature is unavailable
,D/ActivityThread( 3648): Added TimaKeyStore provider
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/SystemUpdateService( 1788): cancelUpdate (empty URL)
I/SystemUpdateService( 1788): active receiver: disabled
,W/ResourcesManager( 3648): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,V/AuthZen ( 1788): Handling intent: android.intent.action.BOOT_COMPLETED
,W/ContextImpl( 3648): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.bcservice.BCServiceReceiver.onReceive:18 android.app.ActivityThread.handleReceiver:3125 
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.sec.bcservice, destAppInfo.processName = com.sec.bcservice
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/USB_UICC(  299): Timeout! No signal received. Reach maximum retries!
E/USB_UICC(  299): usb_uicc_init_qmi failed ! 
I/USB_UICC(  299): usb_uicc_cleanup, signal received: 0x3 
I/USB_UICC(  299): usb_uicc_cleanup, Issuing QMI deinit ... 
,E/Zygote  ( 3665): MountEmulatedStorage()
,I/libpersona( 3665): KNOX_SDCARD checking this for 1000
E/Zygote  ( 3665): v2
I/libpersona( 3665): KNOX_SDCARD not a persona
I/ActivityManager( 1020): Start proc com.sec.android.app.bluetoothtest for broadcast com.sec.android.app.bluetoothtest/.BluetoothBDAdrressReceiver: pid=3665 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/F_PHONE ( 3648): [[com.sec.bcservice]] bind SecPhone Service with FactoryPhone,
W/ContextImpl( 3648): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.samsung.android.sec_platform_library.FactoryPhone.connectToRilService:95 com.samsung.android.sec_platform_library.FactoryPhone.<init>:61 com.sec.bcservice.BroadcastService.onCreate:146 
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.sec.bcservice, destAppInfo.processName = com.sec.phone
,D/F_PHONE ( 3648): [[com.sec.bcservice]] onServiceConnected(),
I/F_PHONE ( 3648): default registerAction()
I/F_PHONE ( 3648): [[com.sec.bcservice]] sendPendingMessage()
,I/SELinux ( 3665): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
I/SELinux ( 3665): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 3665): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/art     ( 1788): Suspending all threads took: 36.158ms
,D/TimaKeyStoreProvider( 3665): TimaSignature is unavailable
,D/ActivityThread( 3665): Added TimaKeyStore provider
,W/ResourcesManager( 3665): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/AuthZenEventHandler( 1788): Handling event: android.intent.action.BOOT_COMPLETED
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/BluetoothBDAdrressReceiver( 3665): onReceive(), action: android.intent.action.BOOT_COMPLETED
,W/ContextImpl( 3665): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.app.bluetoothtest.BluetoothBDAdrressReceiver.onReceive:32 android.app.ActivityThread.handleReceiver:3125 
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.sec.android.app.bluetoothtest, destAppInfo.processName = com.sec.android.app.bluetoothtest
,W/ResourcesManager( 1455): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,D/BluetoothBDTestService( 1455): onCreate()
,E/BluetoothBDTestService( 1455): onStart(), extra_type: BOOT_COMPLETED
E/BluetoothBDTestService( 1455): bd_address_path: /efs/bluetooth/bt_addr
,E/BluetoothBDTestService( 1455): already exist!( /efs/bluetooth/bt_addr ), file length: 17
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3693): MountEmulatedStorage()
E/Zygote  ( 3693): v2
I/libpersona( 3693): KNOX_SDCARD checking this for 1000
I/libpersona( 3693): KNOX_SDCARD not a persona
I/SELinux ( 3693): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 3693): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3693): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1020): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.receiver.ServiceStartReceiver: pid=3693 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/TimaKeyStoreProvider( 3693): TimaSignature is unavailable
,D/ActivityThread( 3693): Added TimaKeyStore provider
,W/BaseAppContext( 1788): Using Auth Proxy for data requests.
,W/ResourcesManager( 3693): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/GCM     ( 1633): GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED
,I/GCoreUlr( 1633): DispatchingService.onCreate()
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.sec.android.app.sbrowser.SBrowserMainActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3602): getResourcePackageName:assistantlist
I/AMMetaDataParserService( 3602): Resource data:2131165186
,D/SystemUpdateService( 1788): onDestroy
,W/ResourcesManager( 3602): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 3602): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3602): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 3602): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/EnterpriseController(  281): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  281): getNetworkForDns: using netid 0 for uid 10011
,D/PersonaManagerService( 1020): getPersonasForUser(): returning null!
,E/BaseAppContext( 1788): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,I/AMMetaDataParserService( 3602): getResourceName:com.sec.android.app.sbrowser:xml/assistantlist
I/AMMetaDataParserService( 3602): getResourceTypeNamexml
,I/art     ( 1615): Explicit concurrent mark sweep GC freed 5114(211KB) AllocSpace objects, 0(0B) LOS objects, 47% free, 4MB/8MB, paused 879us total 31.163ms
,W/SQLiteConnectionPool( 1615): A SQLiteConnection object for database '+data+user+0+com_google_android_gsf+databases+gservices_db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,I/EventLogService( 1788): Aggregate from 1452550264740 (log), 1452550264740 (data)
,I/KnoxUsageLogPro( 3693): KnoxUsageReceiver onReceive :android.intent.action.BOOT_COMPLETED myUserId=0
,I/KnoxUsageLogPro( 3693): premStatus:2
,I/AMMetaDataParserService( 3602): Icon data: ResourceEnter URL2131755287android.intent.action.doInputURL2130837509
,I/KnoxUsageLogPro( 3693): isEulaShown : false
I/KnoxUsageLogPro( 3693): KnoxUsageReceiver onReceive : not Processible, just return
,D/VlingoApplication( 3588): sac sec ensureCacheEmpty() car_iux_tts_cacheing_required set to false
,I/ActivityManager( 1020): Killing 2768:com.sec.dsm.system/1000 (adj 15): empty #31
,I/KnoxUsageLogPro( 3693): savePreference: key = previous_sys_time value = 1452552499725
,D/VlingoApplication( 3588): sac sec ensureCacheEmpty() purged 0 historically cached TTS files
,I/AMMetaDataParserService( 3602): Icon data: ResourceTabs2131755155android.intent.action.doWindowManager2130837511
,D/DialogFlow( 3588): initQueue()
,I/AuthZen ( 1788): Fetching signing key...
,I/Babel   ( 3630): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 3630): MmsConfig.loadMmsSettings
I/Babel   ( 3630): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
I/Babel   ( 3630): MmsConfig.loadFromDatabase
,W/libprocessgroup( 1020): failed to open /acct/uid_1000/pid_2768/cgroup.procs: No such file or directory
,E/Babel   ( 3630): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 3630): MmsConfig.loadFromResources
,E/Babel   ( 3630): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 3630): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
,I/AMMetaDataParserService( 3602): Icon data: ResourceNew Tab2131755457android.intent.action.doNewWindow2130837510
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappManager
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity0
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity1
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity2
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity3
,I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity4
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity5
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity6
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity7
,I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity8
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity9
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.sec.android.app.sbrowser.history.ui.HistoryActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.Settings
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.sec.android.app.sbrowser.reader.ui.ReaderActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.sec.android.app.sbrowser.menuactivity.ui.AddWebPageMenuActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.sec.android.app.sbrowser.readinglist.activity.ReadingListActivity
,I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.sec.android.app.sbrowser.readinglist.controller.ReadingListSearchActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.sec.android.app.sbrowser.sites.SitesActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.sec.android.app.sbrowser.common.DataChargingDialog,
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.EditBookmarkFolderActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.AddBookmarkActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.ShowBookmarksActivity
,I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.SelectBookmarkFolderActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.CreateBookmarkFolderActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.SynctabActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.SelectSyncAccountActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.AutofillFormEdit
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.DeleteSyncTabActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountGetStartedActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountCreateAccountActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountConfirmAccountActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountSignInActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountVerifiedAccountActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountCreateAccountNotAllowedActivity
,W/ContextImpl( 3602): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
,E/Zygote  ( 3737): MountEmulatedStorage()
E/Zygote  ( 3737): v2
I/libpersona( 3737): KNOX_SDCARD checking this for 10029
I/libpersona( 3737): KNOX_SDCARD not a persona
,I/ActivityManager( 1020): Start proc com.samsung.android.app.galaxyfinder:tagService for broadcast com.samsung.android.app.galaxyfinder/.tag.TagReadyReceiver: pid=3737 uid=10029 gids={50029, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,I/ActivityManager( 1020): Killing 2795:com.samsung.android.app.colorblind/1000 (adj 15): empty #31
I/SELinux ( 3737): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 3737): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3737): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/AuthZen ( 1788): Signing key fetched successfully!
,D/TimaKeyStoreProvider( 3737): TimaSignature is unavailable
D/ActivityThread( 3737): Added TimaKeyStore provider
,W/BaseAppContext( 1788): Using Auth Proxy for data requests.,
,W/Settings( 3630): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/VideoCapabilities( 3630): Unrecognized profile 2130706433 for video/avc
,I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.contacts.activities.PeopleActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:assistant
I/AMMetaDataParserService( 3602): Resource data:2131034113
,W/AudioCapabilities( 3630): Unsupported mime audio/evrc
,W/AudioCapabilities( 3630): Unsupported mime audio/qcelp
,W/libprocessgroup( 1020): failed to open /acct/uid_1000/pid_2795/cgroup.procs: No such file or directory
,W/ResourcesManager( 3602): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 3602): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3602): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/a       ( 1788): Opening database auth.proximity.permit_store...
,I/AMMetaDataParserService( 3602): getResourceName:com.android.contacts:xml/assistant_main
,I/AMMetaDataParserService( 3602): getResourceTypeNamexml
,D/AuthZenTransactionCache( 1788): Initialized cache in: /data/data/com.google.android.gms/files
,E/        ( 3602): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,D/AuthZenTransactionCache( 1788): Clearing transaction cache
,I/GFX construct_block_size_descriptor_2d second part( 3602): took 2.290314ms for 0*0 texture 0
,W/AudioCapabilities( 3630): Unsupported mime audio/mpeg-L1
,W/AudioCapabilities( 3630): Unsupported mime audio/mpeg-L2
,W/AudioCapabilities( 3630): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 3630): Unsupported mime audio/x-ima
,I/GFX generate_partition_tables( 3602): took 6.154635ms for 0*0 texture 0
,I/GFX raster( 3602): took 9.668908ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3602): Bitmap=0xb79214a0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7921460 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3602): Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
,W/AudioCapabilities( 3630): Unsupported mime audio/qcelp
,W/AudioCapabilities( 3630): Unsupported mime audio/evrc
,E/        ( 3602): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3602): took 0.814792ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3602): Bitmap=0xb79214a0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7921460 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3602): Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,W/VideoCapabilities( 3630): Unsupported mime video/wvc1
,W/VideoCapabilities( 3630): Unsupported mime video/x-ms-wmv
,V/Babel   ( 3630): babel boot account: SMS
,V/Babel   ( 3630): babel boot account: thalitester@gmail.com
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3757): MountEmulatedStorage()
,E/Zygote  ( 3757): v2
I/libpersona( 3757): KNOX_SDCARD checking this for 1000
I/libpersona( 3757): KNOX_SDCARD not a persona
,I/SELinux ( 3757): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1020): Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.BootBroadcastReceiver: pid=3757 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/ActivityManager( 1020): Killing 2814:com.sec.android.app.factorykeystring/1000 (adj 15): empty #31
I/SELinux ( 3757): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3757): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/DBG_DM  ( 2894): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 4 sec
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,I/KnoxUsageLogPro( 3693): savePreference: key = previous_elapsed_time value = 36825
,D/TimaKeyStoreProvider( 3757): TimaSignature is unavailable
,D/ActivityThread( 3757): Added TimaKeyStore provider
,E/Zygote  ( 3774): MountEmulatedStorage()
E/Zygote  ( 3774): v2
I/libpersona( 3774): KNOX_SDCARD checking this for 10030
I/libpersona( 3774): KNOX_SDCARD not a persona
,I/SELinux ( 3774): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 3774): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
I/ActivityManager( 1020): Start proc com.sec.android.app.sns3 for broadcast com.sec.android.app.sns3/.SnsBroadcastReceiver: pid=3774 uid=10030 gids={50030, 9997, 1028, 1015, 3003} abi=armeabi-v7a
I/ActivityManager( 1020): Killing 2868:com.sec.android.diagmonagent/1000 (adj 15): empty #31
,E/SELinux ( 3774): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,E/SMD     (  291): DCD OFF
,I/Icing   ( 1788): updateResources: need to parse f{com.google.android.gms}
,V/AlarmManager( 1020): waitForAlarm result :4
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/        ( 3602): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX construct_block_size_descriptor_2d second part( 3602): took 2.619375ms for 0*0 texture 0
,D/TimaKeyStoreProvider( 3774): TimaSignature is unavailable
,D/ActivityThread( 3774): Added TimaKeyStore provider
,W/VideoCapabilities( 3630): Unrecognized profile/level 32768/2 for video/mp4v-es
,V/AlarmManager( 1020): waitForAlarm result :4
,W/VideoCapabilities( 3630): Unsupported mime video/wvc1
,W/VideoCapabilities( 3630): Unsupported mime video/x-ms-wmv
,I/GFX generate_partition_tables( 3602): took 7.682499ms for 0*0 texture 0
,I/GFX raster( 3602): took 11.268541ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3602): Bitmap=0xb7921460 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7924948 counterpartCT=4 counterpartW=96 counterparth=96
W/libprocessgroup( 1020): failed to open /acct/uid_1000/pid_2868/cgroup.procs: No such file or directory
W/libprocessgroup( 1020): failed to open /acct/uid_1000/pid_2814/cgroup.procs: No such file or directory
,I/AMMetaDataParserService( 3602): Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,W/VideoCapabilities( 3630): Unsupported mime video/x-ms-wmv7
,W/VideoCapabilities( 3630): Unsupported mime video/x-ms-wmv8
,W/VideoCapabilities( 3630): Unsupported mime video/mp43
,V/GLSActivity( 1633): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/VideoCapabilities( 3630): Unsupported mime video/sorenson
,I/GCoreUlr( 1633): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED
,W/VideoCapabilities( 3630): Unsupported mime video/mp4v-esdp
,I/ActivityManager( 1020): Killing 1558:com.sec.android.provider.badge/u0a68 (adj 15): empty #31
,I/VideoCapabilities( 3630): Unsupported profile 4 for video/mp4v-es
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/SQLiteLog( 3526): (283) recovered 26 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,E/Zygote  ( 3795): MountEmulatedStorage()
E/Zygote  ( 3795): v2
I/libpersona( 3795): KNOX_SDCARD checking this for 1000
I/libpersona( 3795): KNOX_SDCARD not a persona
,D/PackageManager( 1020): [MSG] MCS_UNBIND
,I/ActivityManager( 1020): Start proc com.sec.knox.knoxsetupwizardclient for broadcast com.sec.knox.knoxsetupwizardclient/.detector.SetupWizardDetectorReceiver: pid=3795 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 3795): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 3795): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 3795): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/libprocessgroup( 1020): failed to open /acct/uid_10068/pid_1558/cgroup.procs: No such file or directory
,I/art     (  308): Explicit concurrent mark sweep GC freed 8743(372KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 610us total 31.134ms
,D/TimaKeyStoreProvider( 3795): TimaSignature is unavailable
,D/ActivityThread( 3795): Added TimaKeyStore provider
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 594us total 16.974ms
,I/ActivityManager( 1020): Killing 2911:com.sec.providers.settingsearch/u0a146 (adj 15): empty #31
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 616us total 17.257ms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,I/art     ( 1633): Explicit concurrent mark sweep GC freed 22720(1670KB) AllocSpace objects, 28(448KB) LOS objects, 40% free, 9MB/15MB, paused 1.287ms total 94.810ms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,E/KnoxSetupWizardClient( 3795): isShipMode : 1
,I/KnoxSetupWizardClient( 3795): onReceive : android.intent.action.BOOT_COMPLETED
,E/        ( 3602): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3602): took 0.584010ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3602): Bitmap=0xb7921750 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7924658 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3602): Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,D/ShortcutReceiver( 3795):  ShortcutReceiver onReceive() intent: android.intent.action.BOOT_COMPLETED
,D/KnoxShortcutUtil( 3795): getIsShortcutMigrationFor_2_3_0_Done true
,D/ShortcutReceiver( 3795):  KnoxContainerVersion 2.3.0
D/ShortcutReceiver( 3795):  shortcut migration not required 
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/        ( 3602): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,I/GFX raster( 3602): took 0.932341ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3602): Bitmap=0xb7929ac0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7929b78 counterpartCT=4 counterpartW=96 counterparth=96
,E/Zygote  ( 3817): MountEmulatedStorage()
I/ActivityManager( 1020): Start proc com.sec.android.app.mt for broadcast com.sec.android.app.mt/.StatusChecker: pid=3817 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/Zygote  ( 3817): v2
I/libpersona( 3817): KNOX_SDCARD checking this for 1000
I/SELinux ( 3817): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/libpersona( 3817): KNOX_SDCARD not a persona
I/ActivityManager( 1020): Killing 2845:com.google.android.configupdater/u0a82 (adj 15): empty #31
,I/SELinux ( 3817): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3817): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/AMMetaDataParserService( 3602): Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,W/System.err( 3795): java.lang.IllegalArgumentException: Unknown package: com.sec.knox.setupwizardstub
W/System.err( 3795): 	at android.os.Parcel.readException(Parcel.java:1544)
W/System.err( 3795): 	at android.os.Parcel.readException(Parcel.java:1493)
W/System.err( 3795): 	at android.content.pm.IPackageManager$Stub$Proxy.setApplicationEnabledSetting(IPackageManager.java:4163)
W/System.err( 3795): 	at android.app.ApplicationPackageManager.setApplicationEnabledSetting(ApplicationPackageManager.java:1925)
W/System.err( 3795): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.processInternal(StubPackageThread.java:88)
W/System.err( 3795): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.run(StubPackageThread.java:49)
,I/GCoreUlr( 1633): WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,E/File    ( 3526): fail readDirectory() errno=2
,I/Gmail   ( 3526): notifyAccountChanged
,D/TimaKeyStoreProvider( 3817): TimaSignature is unavailable
,D/ActivityThread( 3817): Added TimaKeyStore provider
,I/Gmail   ( 3526): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,W/ResourcesManager( 3774): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 3774): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 3774): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,I/GCoreUlr( 1633): Unbound from all location providers
I/GCoreUlr( 1633): Place inference reporting - stopped
,I/Gmail   ( 3526): getAccountsCursor
,E/        ( 3602): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,V/GLSActivity( 1633): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GFX raster( 3602): took 0.792135ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3602): Bitmap=0xb75bf230 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb78ec9e0 counterpartCT=4 counterpartW=96 counterparth=96
,W/ResourcesManager( 3774): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 3774): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3774): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
I/AMMetaDataParserService( 3602): Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,I/Gmail   ( 3526): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/GCoreUlr( 1633): DispatchingService.onDestroy()
I/GCoreUlr( 1633): Stopping handler for UlrDispSvcFast
I/Gmail   ( 3526): calculateUnknownSyncRationalesAndPurgeInBackground: running
,D/StatusChecker( 3817): onReceive : android.intent.action.BOOT_COMPLETED
,I/GCoreUlr( 1633): Unbound from all location providers
I/GCoreUlr( 1633): Place inference reporting - stopped
,I/Gmail   ( 3526): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/ActivityManager( 1020): Killing 2931:com.policydm/1000 (adj 15): empty #31
,I/StatusChecker( 3817): onReceive : net.mt.init : DONE
,W/libprocessgroup( 1020): failed to open /acct/uid_10146/pid_2911/cgroup.procs: No such file or directory
,W/libprocessgroup( 1020): failed to open /acct/uid_10082/pid_2845/cgroup.procs: No such file or directory
,E/        ( 3602): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3602): took 0.682448ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3602): Bitmap=0xb79093e8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7908528 counterpartCT=4 counterpartW=96 counterparth=96
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,I/AMMetaDataParserService( 3602): Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
W/ResourcesManager( 3774): Asset path '/system/framework/libvtmanagerjar.jar' does not exist or contains no resources.
W/ResourcesManager( 3774): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
E/Zygote  ( 3837): MountEmulatedStorage()
E/Zygote  ( 3837): v2
I/libpersona( 3837): KNOX_SDCARD checking this for 10113
I/libpersona( 3837): KNOX_SDCARD not a persona
I/SELinux ( 3837): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 3837): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
I/ActivityManager( 1020): Start proc com.sec.android.pagebuddynotisvc for broadcast com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvcBRcvr: pid=3837 uid=10113 gids={50113, 9997} abi=armeabi-v7a
,I/ActivityManager( 1020): Killing 2958:com.dropbox.android/u0a88 (adj 15): empty #31
,E/SELinux ( 3837): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/        ( 3602): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3602): took 0.676562ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3602): Bitmap=0xb78ec9e0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7647b90 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3602): Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,W/GCoreFlp( 1633): No location to return for getLastLocation()
,W/FusedLocationProvider( 1633): location=null
,I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.dialer.DialtactsActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:assistant
I/AMMetaDataParserService( 3602): Resource data:2131034113
,D/TimaKeyStoreProvider( 3837): TimaSignature is unavailable
,I/AMMetaDataParserService( 3602): getResourceName:com.android.contacts:xml/assistant_main
I/AMMetaDataParserService( 3602): getResourceTypeNamexml
,E/        ( 3602): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
D/ActivityThread( 3837): Added TimaKeyStore provider
,I/GFX raster( 3602): took 0.851250ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3602): Bitmap=0xb7908528 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7909ec0 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3602): Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
,W/GCoreFlp( 1633): No location to return for getLastLocation()
,W/FusedLocationProvider( 1633): location=null
,W/Auth    ( 1633): [FRP,FrpUpdateIntentService] Received invalid intent action: com.google.android.gms.auth.ACTION_INVALID
,I/ActivityManager( 1020): Killing 3008:com.dropbox.android:crash_uploader/u0a88 (adj 15): empty #31
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/libprocessgroup( 1020): failed to open /acct/uid_1000/pid_2931/cgroup.procs: No such file or directory
W/libprocessgroup( 1020): failed to open /acct/uid_10088/pid_2958/cgroup.procs: No such file or directory
,V/GLSActivity( 1633): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/PageBuddyNotiSvc( 3837): Intent received : action=android.intent.action.BOOT_COMPLETED
,E/        ( 3602): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3602): took 1.049531ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3602): Bitmap=0xb7908528 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7647b90 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3602): Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,W/ContextImpl( 3837): Implicit intents with startService are not safe: Intent { act=com.sec.android.pagebuddynotisvc } android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.pagebuddynotisvc.PageBuddyNotiSvcBRcvr.onReceive:-1 
,D/PersistentNotificationBroadcastReceiver( 1633): Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.sec.android.pagebuddynotisvc, destAppInfo.processName = com.sec.android.pagebuddynotisvc
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
I/PageBuddyNotiSvc( 3837): onCreate mCpBitFlag=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,W/libprocessgroup( 1020): failed to open /acct/uid_10088/pid_3008/cgroup.procs: No such file or directory,
,I/ActivityManager( 1020): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=3857 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,E/Zygote  ( 3857): MountEmulatedStorage()
I/libpersona( 3857): KNOX_SDCARD checking this for 10121
E/Zygote  ( 3857): v2
I/libpersona( 3857): KNOX_SDCARD not a persona
,I/SELinux ( 3857): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/SELinux ( 3857): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 3857): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 3857): TimaSignature is unavailable
,D/ActivityThread( 3857): Added TimaKeyStore provider
,I/Gmail   ( 3526): getAccountsCursor
,E/Zygote  ( 3874): MountEmulatedStorage()
E/Zygote  ( 3874): v2
I/libpersona( 3874): KNOX_SDCARD checking this for 10026
I/libpersona( 3874): KNOX_SDCARD not a persona
,I/SELinux ( 3874): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,E/        ( 3602): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96,
I/GFX raster( 3602): took 0.624427ms for 96*96 texture 0,
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3602): Bitmap=0xb7909ec0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7647b90 counterpartCT=4 counterpartW=96 counterparth=96
,I/SELinux ( 3874): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
E/SELinux ( 3874): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1020): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=3874 uid=10026 gids={50026, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/AMMetaDataParserService( 3602): Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,V/GLSActivity( 1633): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/TimaKeyStoreProvider( 3874): TimaSignature is unavailable
,D/ActivityThread( 3874): Added TimaKeyStore provider
,E/        ( 3602): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96,
I/GFX raster( 3602): took 0.639427ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3602): Bitmap=0xb7647b90 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7927d50 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3602): Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,W/ResourcesManager( 3857): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3857): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 3857): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,E/        ( 3602): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3602): took 0.825781ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3602): Bitmap=0xb7929ac0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb78eb540 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3602): Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,I/DBG_DM  ( 2894): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 5 sec
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 3
,D/QuickConnect( 3857): PeriphStartReceiver.onReceive - android.intent.action.BOOT_COMPLETED
,D/SettingsProvider( 1020): name = scon_is_running
,D/SettingsProvider( 1020): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1020): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1020): selectionArgs: false
,D/SettingsProvider( 1020): selectionArgs: 10121
D/SecContentProvider( 1020): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider( 1020): ret = -1
,W/BackupManagerService( 1020): dataChanged but no participant pkg='com.android.providers.settings' uid=10121
,D/QuickConnect( 3857): Utils.setQCRunningSetting - set : 0
,I/QuickConnect( 3857): PeriphStartReceiver.onReceive - USER_OWNER care ACTION_BOOT_COMPLETED. run P service
,I/SecKeyguardClockSingleView( 1177): Ignore. Because it is same clock text
,I/QuickConnect( 3857): PeriphStartReceiver.onReceive - no need to start
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3896): MountEmulatedStorage(),
,E/Zygote  ( 3896): v2
I/libpersona( 3896): KNOX_SDCARD checking this for 10127
I/libpersona( 3896): KNOX_SDCARD not a persona
,I/SELinux ( 3896): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1020): Start proc com.sec.android.app.sbrowser for broadcast com.sec.android.app.sbrowser/.net.NetworkSettingsReceiver: pid=3896 uid=10127 gids={50127, 9997, 1023, 3003, 1028, 1015, 1007, 3001, 3002} abi=armeabi-v7a
,I/SELinux ( 3896): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3896): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/System.out( 3588): INFO:Resource not found:/Common.properties Using default values
,D/TimaKeyStoreProvider( 3896): TimaSignature is unavailable
,D/ActivityThread( 3896): Added TimaKeyStore provider
,W/ResourcesManager( 3896): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 3896): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3896): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 3896): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ResourcesManager( 3737): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Process ( 3774): Sending signal. PID: 3774 SIG: 9
,D/SBrowserFeatureFlag( 3896): initialized in static block : loadCscFeatureValue() succeed! 
,E/        ( 3602): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3602): took 0.678230ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3602): Bitmap=0xb75bf230 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7924988 counterpartCT=4 counterpartW=96 counterparth=96
,I/ActivityManager( 1020): Process com.sec.android.app.sns3 (pid 3774)(adj 0) has died(23,687)
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,D/ManifestProvider( 3896): onCreate(),
,E/Zygote  ( 3921): MountEmulatedStorage()
E/Zygote  ( 3921): v2
I/libpersona( 3921): KNOX_SDCARD checking this for 10031
I/libpersona( 3921): KNOX_SDCARD not a persona
,I/SELinux ( 3921): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/AMMetaDataParserService( 3602): Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,I/ActivityManager( 1020): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=3921 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a
,I/SELinux ( 3921): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3921): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/        ( 3602): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3602): took 0.719323ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3602): Bitmap=0xb79093e8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7927d50 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3602): Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
,E/NetworkSettingsReceiver( 3896): onReceive: android.intent.action.BOOT_COMPLETED
,D/TimaKeyStoreProvider( 3921): TimaSignature is unavailable
,D/ActivityThread( 3921): Added TimaKeyStore provider
,D/Finsky  ( 3874): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,W/ResourcesManager( 3737): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 3737): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3737): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/System.err( 3896): java.lang.NoSuchMethodException: isEnabled []
,W/System.err( 3896): 	at java.lang.Class.getMethod(Class.java:665)
,E/        ( 3602): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
W/System.err( 3896): 	at com.sec.android.app.sbrowser.common.SBrowserFeatureFlag.isCLipboardExsupported(SBrowserFeatureFlag.java:1217)
,W/System.err( 3896): 	at com.sec.android.app.sbrowser.common.SBrowserFeatureFlag.initSupportedPkg(SBrowserFeatureFlag.java:1197)
W/System.err( 3896): 	at com.sec.android.app.sbrowser.common.SBrowserFeatureFlag.initialize(SBrowserFeatureFlag.java:1114)
W/System.err( 3896): 	at com.sec.android.app.sbrowser.preferences.SbrowserSettings.<init>(SbrowserSettings.java:221)
W/System.err( 3896): 	at com.sec.android.app.sbrowser.common.SBrowserMobileApplication.getSetting(SBrowserMobileApplication.java:111)
,W/System.err( 3896): 	at com.sec.android.app.sbrowser.net.NetworkSettingsReceiver.onReceive(NetworkSettingsReceiver.java:48)
,W/System.err( 3896): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
W/System.err( 3896): 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
W/System.err( 3896): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
W/System.err( 3896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3896): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
W/System.err( 3896): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 3896): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 3896): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 3896): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,E/SBrowserFeatureFlag( 3896): initSupportedPkg: checkExistService com.samsung.android.smartclip.SpenGestureManager@19a28a6f
,D/SBrowserFeatureFlag( 3896): initialize : initSupportedPkg() succeed! 
,I/VerificationLog( 3896): SbrowserSettings- url content://com.sec.android.app.sbrowser/readinglist/pinned.mhtml
,I/GFX raster( 3602): took 0.549687ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3602): Bitmap=0xb78ec9e0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb78eb540 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3602): Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3944): MountEmulatedStorage(),
E/Zygote  ( 3944): v2
,I/libpersona( 3944): KNOX_SDCARD checking this for 10131
I/libpersona( 3944): KNOX_SDCARD not a persona
,I/SELinux ( 3944): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/ActivityManager( 1020): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=3944 uid=10131 gids={50131, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a,
I/ActivityManager( 1020): Killing 3049:com.fmm.dm/1000 (adj 15): empty #31,
,I/SELinux ( 3944): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,I/AMMetaDataParserService( 3602): getResourcePackageName:com.samsung.android.multiuser.install_only_owner,
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.contacts.activities.ContactSelectionActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionTabActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionGroupSelectionActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.contacts.DialtactsActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.contacts.RecentCallsListActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.contacts.activities.CallLogActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.contacts.ContactsListActivity,
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.contacts.activities.ContactsFrontDoor
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.contacts.DialtactsContactsEntryActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.samsung.contacts.activities.PeopleActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.contacts.activities.JoinContactActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.contacts.preference.ContactsPreferenceActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.contacts.common.list.AccountFilterActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.contacts.common.list.CustomContactListFilterActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.contacts.activities.ShowOrCreateActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.contacts.activities.GroupDetailActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.contacts.activities.GroupEditorActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.contacts.quickcontact.QuickContactActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.sec.android.multiwindow.activity.STYLE
E/SELinux ( 3944): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.contacts.ContactShortcut
I/AMMetaDataParserService( 3602): Resource data:Loop for running activityalias.DialShortcut
I/AMMetaDataParserService( 3602): Resource data:Loop for running activityalias.MessageShortcut
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.dialer.CallDetailActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDetailDeleteActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.contacts.activities.ContactDetailActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3602): getResourcePackageName:assistant
I/AMMetaDataParserService( 3602): Resource data:2131034112
I/AMMetaDataParserService( 3602): getResourceName:com.android.contacts:xml/assistant_detail
I/AMMetaDataParserService( 3602): getResourceTypeNamexml
E/        ( 3602): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3602): took 0.654271ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3602): Bitmap=0xb7647b90 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb78eb540 counterpartCT=4 counterpartW=96 counterparth=96
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
D/TimaKeyStoreProvider( 3944): TimaSignature is unavailable
D/ActivityThread( 3944): Added TimaKeyStore provider
E/Zygote  ( 3960): MountEmulatedStorage()
E/Zygote  ( 3960): v2
I/libpersona( 3960): KNOX_SDCARD checking this for 1000
I/libpersona( 3960): KNOX_SDCARD not a persona
I/AMMetaDataParserService( 3602): Icon data: ResourceAdd to Favourites2131690170android.intent.assistant.detail.favorite2130837530
I/ActivityManager( 1020): Start proc com.policydm for broadcast com.policydm/.XDMBroadcastReceiver: pid=3960 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/ActivityManager( 1020): Killing 3121:com.fmm.ds/1000 (adj 15): empty #31
I/SELinux ( 3960): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 3960): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 3960): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ResourcesManager( 3944): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3944): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 3944): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/        ( 3602): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3602): took 0.619116ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3602): Bitmap=0xb7647b90 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7924988 counterpartCT=4 counterpartW=96 counterparth=96
,D/TimaKeyStoreProvider( 3960): TimaSignature is unavailable
,D/ActivityThread( 3960): Added TimaKeyStore provider
,I/AMMetaDataParserService( 3602): Icon data: ResourceRemove from Favourites2131690212android.intent.assistant.detail.favorite2130837530
,W/libprocessgroup( 1020): failed to open /acct/uid_1000/pid_3049/cgroup.procs: No such file or directory
,W/libprocessgroup( 1020): failed to open /acct/uid_1000/pid_3121/cgroup.procs: No such file or directory
,D/Finsky  ( 3874): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,D/daemonapp( 1737): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,W/Settings( 3874): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,I/DBG_POLICYDM( 3960): [com.policydm.XDMApplication(554/xdmWakeLockAcquire)] 
,W/Settings( 3874): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/DBG_POLICYDM( 3960): [com.policydm.XDMApplication(559/xdmWakeLockAcquire)] m_WakeLock is acquire!!
,I/DBG_POLICYDM( 3960): [com.policydm.adapter.XDMTargetAdapter(191/xdmInitExternalStorageState)] 
,I/DBG_POLICYDM( 3960): [com.policydm.agent.XDMTask(163/xdmAgentTaskHandler)] XEVENT_OS_INITIALIZED
,I/DBG_POLICYDM( 3960): [com.policydm.agent.XDMAgent(156/xdmAgentSetSyncMode)] nSync = 0
,E/        ( 3602): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3602): took 0.655520ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3602): Bitmap=0xb7927d50 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb78eb540 counterpartCT=4 counterpartW=96 counterparth=96
I/DBG_POLICYDM( 3960): [com.policydm.adapter.XDMTargetAdapter(390/xdmGetExternalSDCardPath)] External SD Card Path : /storage/extSdCard
,I/AMMetaDataParserService( 3602): Icon data: ResourceEdit2131690192android.intent.assistant.detail.edit2130837529
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/        ( 3602): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3602): took 0.629531ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3602): Bitmap=0xb75bf230 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7924988 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3602): Icon data: ResourceDelete2131690186android.intent.assistant.detail.delete2130837528
,I/DBG_POLICYDM( 3960): [com.policydm.adapter.XDMTargetAdapter(248/xdmInitExternalStorageState)] DATA_DIR_PATH [/data]
I/DBG_POLICYDM( 3960): [com.policydm.adapter.XDMTargetAdapter(249/xdmInitExternalStorageState)] EXTERNAL_DIR_PATH [/storage/emulated/0]
E/Zygote  ( 3995): MountEmulatedStorage()
E/Zygote  ( 3995): v2
I/libpersona( 3995): KNOX_SDCARD checking this for 10037
I/libpersona( 3995): KNOX_SDCARD not a persona
I/ActivityManager( 1020): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=3995 uid=10037 gids={50037, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 3995): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 3995): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
E/SELinux ( 3995): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/DBG_POLICYDM( 3960): [com.policydm.db.XDB(1531/xdbDMffs_Init)] xdbDMffs_Init
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
,I/DBG_POLICYDM( 3960): [com.policydm.adapter.XDMTargetAdapter(250/xdmInitExternalStorageState)] EXTERNAL_SD_DIR_PATH [/storage/extSdCard]
,I/DBG_POLICYDM( 3960): [com.policydm.adapter.XDMTargetAdapter(251/xdmInitExternalStorageState)] POLICY_DIR_PATH [/data/data/com.policydm/cache]
I/DBG_POLICYDM( 3960): [com.policydm.adapter.XDMTargetAdapter(253/xdmInitExternalStorageState)] bExternalStorageAvailable [true]
,I/GAV2    ( 3025): Thread[GAThread,5,main]: No campaign data found.
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,I/DBG_POLICYDM( 3960): [com.policydm.adapter.XDMTargetAdapter(254/xdmInitExternalStorageState)] bExternalSDStorageAvailable [false]
,I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.samsung.contacts.detail.SelectContactInfoActivity
,I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.contacts.activities.ConfirmAddDetailActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorAccountsChangedActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.samsung.contacts.activities.RingtoneRecommendationHelperActivity
,I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.samsung.contacts.editor.AddAnotherFieldDialogActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.contacts.activities.AttachPhotoActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.contacts.activities.PhotoSelectionActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.contacts.common.vcard.ImportVCardActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportVCardPreviewActivity
,I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.contacts.common.vcard.NfcImportVCardActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.contacts.common.vcard.CancelActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.contacts.common.vcard.SelectAccountActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.contacts.common.vcard.ExportVCardActivity
,I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportFinishActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.samsung.contacts.activities.SIMContactSelectionActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbers
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbersTabActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.samsung.contacts.activities.VerizonBackupAssistantActivity
,I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.contacts.widget.PinnedHeaderListDemoActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.contacts.NonPhoneActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.samsung.contacts.favorite.FavoriteSelectionActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.samsung.contacts.detail.SetDefaultActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.samsung.contacts.group.GroupChangeOrderActivity
,I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.samsung.contacts.editor.EditGroupSelectionActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.samsung.contacts.group.GroupMultiSelectionActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.samsung.contacts.emergency.InteractionEmergencyMessageActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.samsung.contacts.emergency.EmergencyMessageContactCreateActivity
,I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.samsung.contacts.emergency.EmergencyContactListDialogActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.samsung.contacts.group.SubGroupDetailActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.samsung.contacts.activities.GroupListActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDurationActivity
,I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDurationTabActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.samsung.contacts.detail.LinkedContactActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.samsung.dialer.impl.DialerTutorialActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpPeopleActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyPeopleActivity,
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpInteractionTabActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyInteractionTabActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpSpeedDialActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactEditorActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactSelectionActivity
,I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.samsung.contacts.activities.EasyPeopleActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:assistant
I/AMMetaDataParserService( 3602): Resource data:2131034113
I/AMMetaDataParserService( 3602): getResourceName:com.android.contacts:xml/assistant_main
,I/AMMetaDataParserService( 3602): getResourceTypeNamexml
E/        ( 3602): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3602): took 0.803594ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3602): Bitmap=0xb7908528 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb78eb540 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3602): Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
,E/Zygote  ( 4013): MountEmulatedStorage()
E/Zygote  ( 4013): v2
I/libpersona( 4013): KNOX_SDCARD checking this for 10135
I/SELinux ( 4013): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/libpersona( 4013): KNOX_SDCARD not a persona
I/DBG_POLICYDM( 3960): [com.policydm.XDMApplication(580/xdmWakeLockRelease)] 
I/ActivityManager( 1020): Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.BootCamera: pid=4013 uid=10135 gids={50135, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a
,I/SELinux ( 4013): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4013): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/TimaKeyStoreProvider( 3995): TimaSignature is unavailable
D/ActivityThread( 3995): Added TimaKeyStore provider
,I/DBG_POLICYDM( 3960): [com.policydm.XDMApplication(585/xdmWakeLockRelease)] m_WakeLock is release!!
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.ssrm.I.m:-1 com.android.server.ssrm.J.run:-1 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 
,D/TimaKeyStoreProvider( 4013): TimaSignature is unavailable
,D/ActivityThread( 4013): Added TimaKeyStore provider
,I/DBG_POLICYDM( 3960): [com.policydm.XDMApplication(179/onCreate)] DMApplication Start !
,I/DBG_POLICYDM( 3960): [com.policydm.XDMBroadcastReceiver(53/onReceive)] android.intent.action.BOOT_COMPLETED
,I/art     ( 1020): Explicit concurrent mark sweep GC freed 34797(2016KB) AllocSpace objects, 6(96KB) LOS objects, 33% free, 22MB/33MB, paused 2.578ms total 168.364ms
,E/        ( 3602): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3602): took 0.810469ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3602): Bitmap=0xb7908528 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7929d60 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3602): Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,E/        ( 3602): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3602): took 1.056926ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3602): Bitmap=0xb7909ec0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7929d60 counterpartCT=4 counterpartW=96 counterparth=96
,W/ResourcesManager( 4013): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 4013): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 4013): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 4013): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
W/ResourcesManager( 4013): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3602): Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,W/ResourcesManager( 3995): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/DBG_POLICYDM( 3960): [com.policydm.db.XDB(2211/xdbIsAlreadyAgree)] bAgree : true
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/        ( 3602): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3602): took 0.816146ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3602): Bitmap=0xb7929d60 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb79083b0 counterpartCT=4 counterpartW=96 counterparth=96
,E/Zygote  ( 4028): MountEmulatedStorage()
E/Zygote  ( 4028): v2
I/libpersona( 4028): KNOX_SDCARD checking this for 10032
I/libpersona( 4028): KNOX_SDCARD not a persona
,I/SELinux ( 4028): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4028): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4028): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1020): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=4028 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1020): Killing 3162:com.samsung.android.intelligenceservice/u0a55 (adj 15): empty #31
,I/AMMetaDataParserService( 3602): Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,I/DBG_POLICYDM( 3960): [com.policydm.agent.XDMTask(171/xdmAgentTaskHandler)] XEVENT_DM_INIT
D/TimaKeyStoreProvider( 4028): TimaSignature is unavailable
D/SSRM:n  ( 1020): SIOP:: AP = 400
D/ActivityThread( 4028): Added TimaKeyStore provider
I/art     (  308): Explicit concurrent mark sweep GC freed 8713(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 615us total 27.178ms
,E/        ( 3602): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96,
,I/GFX raster( 3602): took 1.071197ms for 96*96 texture 0,
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3602): Bitmap=0xb7ad12b8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb78ec9e0 counterpartCT=4 counterpartW=96 counterparth=96
,I/DBG_POLICYDM( 3960): [com.policydm.XDMApplication(463/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,I/DBG_POLICYDM( 3960): [com.policydm.XDMApplication(473/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 800us total 21.233ms
,I/ActivityManager( 1020): Killing 3146:com.sec.esdk.elm/u0a90 (adj 15): empty #31
,E/DBG_POLICYDM( 3960): [com.policydm.agent.XDMTask(174/xdmAgentTaskHandler)] Network Status is not ready. DM Not Initialized
,I/DBG_DM  ( 2894): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 6 sec
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 595us total 19.338ms
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,D/Volley  ( 3874): [588] DiskBasedCache.clear: Cache cleared.
,D/Volley  ( 3874): [581] DiskBasedCache.clear: Cache cleared.
,I/AMMetaDataParserService( 3602): Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,D/Ads     ( 3874): Skipping gmscore version check
,E/Zygote  ( 4046): MountEmulatedStorage()
I/libpersona( 4046): KNOX_SDCARD checking this for 10141
E/Zygote  ( 4046): v2
I/libpersona( 4046): KNOX_SDCARD not a persona
,I/SELinux ( 4046): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4046): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 4046): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1020): Start proc com.android.email for broadcast com.android.email/.service.EmailBroadcastReceiver: pid=4046 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1020): Killing 2977:com.sec.android.fotaclient/u0a8 (adj 15): empty #31
I/ActivityManager( 1020): Killing 3224:com.samsung.android.scloud.backup/u0a56 (adj 15): empty #32
,I/CalendarProvider2( 3995): CalendarProvider2.onCreate() called
,D/TimaKeyStoreProvider( 4046): TimaSignature is unavailable
,D/ActivityThread( 4046): Added TimaKeyStore provider
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/        ( 3602): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
W/ResourcesManager( 4046): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
I/GFX raster( 3602): took 0.632032ms for 96*96 texture 0
W/ResourcesManager( 4046): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4046): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4046): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3602): Bitmap=0xb79093e8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb75bf230 counterpartCT=4 counterpartW=96 counterparth=96
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/AMMetaDataParserService( 3602): Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,W/libprocessgroup( 1020): failed to open /acct/uid_10055/pid_3162/cgroup.procs: No such file or directory
W/libprocessgroup( 1020): failed to open /acct/uid_10090/pid_3146/cgroup.procs: No such file or directory
W/libprocessgroup( 1020): failed to open /acct/uid_10008/pid_2977/cgroup.procs: No such file or directory
,W/libprocessgroup( 1020): failed to open /acct/uid_10056/pid_3224/cgroup.procs: No such file or directory
,I/Icing   ( 1788): Internal init done: storage state 0
,I/Icing   ( 1788): Post-init done
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 3874): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 3874): [1] Libraries$2.run: Finished loading 1 libraries.
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 3874): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,D/Finsky  ( 3874): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,V/AlarmManager( 1020): waitForAlarm result :8
,E/        ( 3602): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3602): took 0.672084ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3602): Bitmap=0xb7647b90 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb79083b0 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3602): Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
,D/RCPManagerService( 1020): exchangeData() failure , invalid userId,
,D/RCPManagerService( 1020): exchangeData() failure , invalid userId
,E/SPPClientService( 4028): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService( 4028): [PushClientApplication] Push log off : This is Ship build version
,E/SPPClientService( 4028): [[SystemStateMoniter]] ACTION_BOOT_COMPLETED
,D/SPPClientService( 4028): PushLog.txt file is not deleted.
,D/SPPClientService( 4028): PushLog.txt file is not deleted.
,D/SPPClientService( 4028): ============PushLog. stop!
,D/RCPManagerService( 1020): exchangeData() failure , invalid userId
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4078): MountEmulatedStorage(),
E/Zygote  ( 4078): v2
,I/libpersona( 4078): KNOX_SDCARD checking this for 10036
I/libpersona( 4078): KNOX_SDCARD not a persona
,I/SELinux ( 4078): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1020): Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.broadcastreceiver.StdBroadcastReceiver: pid=4078 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
I/SELinux ( 4078): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1020): Killing 3246:com.google.android.onetimeinitializer/u0a13 (adj 15): empty #31
E/SELinux ( 4078): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,D/RCPManagerService( 1020): exchangeData() failure , invalid userId
,D/TimaKeyStoreProvider( 4078): TimaSignature is unavailable
,D/ActivityThread( 4078): Added TimaKeyStore provider
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,W/libprocessgroup( 1020): failed to open /acct/uid_10013/pid_3246/cgroup.procs: No such file or directory
,I/ActivityManager( 1020): Killing 3264:com.samsung.android.scloud.sync/u0a58 (adj 15): empty #31
,I/SA      ( 4078): [SSP] onCreated
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,W/libprocessgroup( 1020): failed to open /acct/uid_10058/pid_3264/cgroup.procs: No such file or directory
D/RCPManagerService( 1020): exchangeData() failure , invalid userId
,I/SA      ( 4078): [TPM] There is no property file
E/Zygote  ( 4100): MountEmulatedStorage(),
E/Zygote  ( 4100): v2
I/libpersona( 4100): KNOX_SDCARD checking this for 10068
I/libpersona( 4100): KNOX_SDCARD not a persona
,I/SELinux ( 4100): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4100): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,I/SA      ( 4078): [SCU] isHaveSA() - false
,I/ActivityManager( 1020): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=4100 uid=10068 gids={50068, 9997} abi=armeabi-v7a
E/SELinux ( 4100): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
I/SA      ( 4078): [TPM] getModelProperty : null
I/SA      ( 4078): [TPM] getCSCProperty : null
,I/SA      ( 4078): [DM] FLOATING AMOLED FEATURE: true,
I/SA      ( 4078): [DM] PRODUCT AMOLED FEATURE: false
I/SA      ( 4078): [DM] TFT FEATURE: false
,D/RCPManagerService( 1020): exchangeData() failure , invalid userId
,I/SA      ( 4078): [SBR] StdBroadcastReceiver received Intent of  action_BOOT_COMPLETED extra.user_handle.:0
,I/SA      ( 4078): [DM] init START
,I/SA      ( 4078): [DM] This device is not a Vodafone
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.email, destAppInfo.processName = com.android.email
,D/TimaKeyStoreProvider( 4100): TimaSignature is unavailable
,E/        ( 3602): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3602): took 0.521354ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3602): Bitmap=0xb78ec9e0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb75bf230 counterpartCT=4 counterpartW=96 counterparth=96
D/ActivityThread( 4100): Added TimaKeyStore provider
,I/AMMetaDataParserService( 3602): Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,W/ResourceType( 4078): Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
,W/ResourceType( 4078): Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
,W/ResourceType( 4078): Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
W/ResourceType( 4078): Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
,W/ResourceType( 4078): Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
,W/ResourceType( 4078): Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
,W/ResourceType( 4078): Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
,W/ResourceType( 4078): No package identifier when getting value for resource number 0x00000000
,W/ResourceType( 4078): Failure getting entry for 0x7f060026 (t=5 e=38) (error -75)
,W/ResourceType( 4078): Failure getting entry for 0x7f060027 (t=5 e=39) (error -75)
,W/ResourceType( 4078): Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
W/ResourceType( 4078): Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
W/ResourceType( 4078): Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
W/ResourceType( 4078): Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
W/ResourceType( 4078): Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
,W/ResourceType( 4078): Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
,W/ResourceType( 4078): Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.samsung.contacts.interactions.EasyInteractionTabActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.samsung.dialer.calllog.LogsFindoSearchResultsActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
W/ResourceType( 4078): Failure getting entry for 0x7f06001d (t=5 e=29) (error -75)
I/AMMetaDataParserService( 3602): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.samsung.dialer.dialpad.RegularSearchActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.samsung.dialer.interaction.InteractionRecentActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.samsung.contacts.editor.SamsungAccountValidationCheckActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.samsung.contacts.autolink.AutoLinkActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.samsung.contacts.activities.EmergencyPeopleActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.samsung.contacts.speeddial.SpeedDialActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.samsung.contacts.businesscard.BusinesscardListActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.samsung.contacts.businesscard.BusinesscardViewer
W/ContextImpl( 3602): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.samsung.dialer.callmessage.CallMessageActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.samsung.dialer.callmessage.RecentCallMessageActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.samsung.dialer.callmessage.PhrasesEditActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.samsung.dialer.callmessage.PhrasesDeleteActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.samsung.dialer.callmessage.CallMessageEditActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.samsung.contacts.emergency.MyEmergencyInfoDetailActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.samsung.contacts.emergency.MyEmergencyInfoEditorActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.samsung.contacts.activities.ScoverFavoritesActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.samsung.contacts.activities.ScoverSelectNumberActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3602): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.samsung.contacts.detail.ShowMyProfileActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionProfileWhiteListActivity
W/ResourceType( 4078): Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
W/ResourceType( 4078): Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
W/ResourceType( 4078): Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
W/ResourceType( 4078): Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
W/ResourceType( 4078): Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
W/ResourceType( 4078): Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
W/ResourceType( 4078): Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
W/ResourceType( 4078): Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
D/BadgeProvider( 4100): onCreate
D/BadgeProvider( 4100): DatabaseHelper
I/SA      ( 4078): [SCU] isHaveSA() - false
I/SA      ( 4078): support phone number id : false
I/SA      ( 4078): [DM] Supports Ref Jpn : true
I/SA      ( 4078): [DM] init END
E/Zygote  ( 4122): MountEmulatedStorage()
I/libpersona( 4122): KNOX_SDCARD checking this for 10142
E/Zygote  ( 4122): v2
I/libpersona( 4122): KNOX_SDCARD not a persona
I/SELinux ( 4122): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1020): Start proc com.android.exchange for broadcast com.android.exchange/.service.ExchangeBroadcastReceiver: pid=4122 uid=10142 gids={50142, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
I/ActivityManager( 1020): Killing 3343:com.wssnps/1000 (adj 15): empty #31
I/ActivityManager( 1020): Killing 3322:com.sec.android.app.servicemodeapp/1000 (adj 15): empty #32
I/SELinux ( 4122): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 4122): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/SA      ( 4078): [OR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
I/SA      ( 4078): [OR] onReceive Intent=[ action_BOOT_COMPLETED extra.user_handle.:0 ]
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.osp.app.signin, destAppInfo.processName = com.osp.app.signin
I/SA      ( 4078): [OR] onReceive END
,D/TimaKeyStoreProvider( 4122): TimaSignature is unavailable
D/ActivityThread( 4122): Added TimaKeyStore provider
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.email.activity.setup.SSLCertValidationActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.email.activity.EmailUpgradeKeystoreActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.email.activity.SecurityCertificates
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.email.activity.Welcome
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.email.activity.UpgradeAccounts
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupWizard
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.email.activity.setup.snc.VZWSetupWizard
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncRestoreAccounts
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.email.activity.setup.snc.SncRestoreAccounts
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncRestoreOptions
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncNames
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncExchangeAccounts
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncAccountsLogin
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.email.activity.setup.LDAPClientSettings
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.email.activity.LDAPAccountsList
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupBasics
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.email.DataConnection
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupAccountType
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupIncoming
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupOutgoing
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupExchange
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupOptions
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupNames
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsXL
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsAddRulesforFiltering
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.email.activity.setup.AddPrioritySenderActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSecurity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.email.activity.setup.AccountPreSetup
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.email.messageview.SaveasActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.email.activity.Debug
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.email.activity.MessageListXL
I/AMMetaDataParserService( 3602): Resource data:Inside, bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:assistant
I/AMMetaDataParserService( 3602): Resource data:2131165203
W/ResourcesManager( 3602): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 3602): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3602): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3602): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
I/AMMetaDataParserService( 3602): getResourceName:com.android.email:xml/email_assistant_menu
I/AMMetaDataParserService( 3602): getResourceTypeNamexml
W/ResourcesManager( 4122): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ActivityManager( 1020): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
W/ActivityManager( 1020): getTasks: caller 10141 does not hold GET_TASKS; limiting output
I/Process ( 4046): Sending signal. PID: 4046 SIG: 9
D/BadgeProvider( 4100): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,E/lowmemorykiller(  256): Error writing /proc/4046/oom_score_adj; errno=22
,E/        ( 3602): GFX convertToRaster() in Bitmap.cpp for bitmap size 80x80
,I/GFX construct_block_size_descriptor_2d second part( 3602): took 3.465104ms for 0*0 texture 0
,I/SA      ( 4078): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      ( 4078): [ODM] queryOpenData(key= GEO_IP )
,D/RCPManagerService( 1020): exchangeData() failure , invalid userId,
,I/SA      ( 4078): getMccForGalaxyJpn step2 GEO_IP MCC : 260
I/SA      ( 4078): [LBE] REF_JPN : true
I/SA      ( 4078): [BDC] create
,I/GFX generate_partition_tables( 3602): took 17.099063ms for 0*0 texture 0
,I/GFX raster( 3602): took 21.109480ms for 80*80 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3602): Bitmap=0xb7ad97b8 bitmapCt=12 bitmapW=80 bitmapH=80 BitmapInternalFormat=93b7, Counterpart=0xb7908560 counterpartCT=4 counterpartW=80 counterparth=80
,I/AMMetaDataParserService( 3602): Icon data: ResourceDrawer menu2131363563com.android.email.intent.messagelistfragment.drawer2130837576
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.exchange, destAppInfo.processName = com.android.exchange
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/        ( 3602): GFX convertToRaster() in Bitmap.cpp for bitmap size 80x80,
,I/GFX construct_block_size_descriptor_2d second part( 3602): took 2.332708ms for 0*0 texture 0
,I/SA      ( 4078): [DBMV2] getEmailID,
,I/GFX generate_partition_tables( 3602): took 5.198750ms for 0*0 texture 0
,I/SA      ( 4078): [DBMV2] getDataV02ForItems
I/SA      ( 4078): [SSP] query invoked
,I/GFX raster( 3602): took 8.623903ms for 80*80 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3602): Bitmap=0xb7908560 bitmapCt=12 bitmapW=80 bitmapH=80 BitmapInternalFormat=93b0, Counterpart=0xb78fcae0 counterpartCT=4 counterpartW=80 counterparth=80
,I/SA      ( 4078): [SCU] get signed id from samsung account2.0 DB.
E/Zygote  ( 4142): MountEmulatedStorage()
I/libpersona( 4142): KNOX_SDCARD checking this for 1000
E/Zygote  ( 4142): v2
I/libpersona( 4142): KNOX_SDCARD not a persona
,I/SELinux ( 4142): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/AMMetaDataParserService( 3602): Icon data: ResourceMessage marked as complete2131362386com.android.email.intent.messageviewfragment.favorite2130837575
I/SA      ( 4078): [SCU] get signed id from samsung account1.0 DB.,
I/DBG_DM  ( 2894): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 7 sec
I/ActivityManager( 1020): Start proc com.sec.android.app.SecSetupWizard for broadcast com.sec.android.app.SecSetupWizard/.SetupIntentReceiver: pid=4142 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 4142): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4142): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1020): Process com.android.email (pid 4046)(adj 11) has died(28,667)
,I/SA      ( 4078): [BDC] destroy
,I/ActivityManager( 1020): Killing 3071:com.google.android.partnersetup/u0a14 (adj 15): empty #31
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 4142): TimaSignature is unavailable
,D/ActivityThread( 4142): Added TimaKeyStore provider
,E/SMD     (  291): DCD OFF
,E/Zygote  ( 4158): MountEmulatedStorage(),
,E/Zygote  ( 4158): v2
,I/libpersona( 4158): KNOX_SDCARD checking this for 10141
I/libpersona( 4158): KNOX_SDCARD not a persona
,I/ActivityManager( 1020): Start proc com.android.email for content provider com.android.email/.provider.EmailProvider: pid=4158 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a,
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/libprocessgroup( 1020): failed to open /acct/uid_1000/pid_3322/cgroup.procs: No such file or directory
,W/libprocessgroup( 1020): failed to open /acct/uid_1000/pid_3343/cgroup.procs: No such file or directory
,I/SELinux ( 4158): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,E/        ( 3602): GFX convertToRaster() in Bitmap.cpp for bitmap size 80x80
I/GFX raster( 3602): took 0.719427ms for 80*80 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3602): Bitmap=0xb7908560 bitmapCt=12 bitmapW=80 bitmapH=80 BitmapInternalFormat=93b0, Counterpart=0xb78fcae0 counterpartCT=4 counterpartW=80 counterparth=80
I/SELinux ( 4158): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4158): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3602): Icon data: ResourceFlagged message2131362384com.android.email.intent.messageviewfragment.favorite2130837575
,D/TimaKeyStoreProvider( 4158): TimaSignature is unavailable
,D/ActivityThread( 4158): Added TimaKeyStore provider
,W/libprocessgroup( 1020): failed to open /acct/uid_10014/pid_3071/cgroup.procs: No such file or directory
,I/ActivityManager( 1020): Killing 3391:com.android.managedprovisioning/u0a20 (adj 15): empty #31
,E/        ( 3602): GFX convertToRaster() in Bitmap.cpp for bitmap size 80x80
,I/GFX raster( 3602): took 0.706667ms for 80*80 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3602): Bitmap=0xb7908560 bitmapCt=12 bitmapW=80 bitmapH=80 BitmapInternalFormat=93b0, Counterpart=0xb78fcae0 counterpartCT=4 counterpartW=80 counterparth=80
,I/AMMetaDataParserService( 3602): Icon data: ResourceUnflagged message2131362385com.android.email.intent.messageviewfragment.favorite2130837575
,W/ResourcesManager( 4158): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 4158): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4158): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4158): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4174): MountEmulatedStorage()
E/Zygote  ( 4174): v2
I/libpersona( 4174): KNOX_SDCARD checking this for 1000
I/libpersona( 4174): KNOX_SDCARD not a persona
,I/SELinux ( 4174): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,E/        ( 3602): GFX convertToRaster() in Bitmap.cpp for bitmap size 80x80
I/SELinux ( 4174): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4174): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/GFX raster( 3602): took 0.757290ms for 80*80 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3602): Bitmap=0xb78fcae0 bitmapCt=12 bitmapW=80 bitmapH=80 BitmapInternalFormat=93b0, Counterpart=0xb78f8000 counterpartCT=4 counterpartW=80 counterparth=80
,I/ActivityManager( 1020): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.BootReceiver: pid=4174 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 1020): Killing 3408:com.samsung.android.app.accesscontrol/1000 (adj 15): empty #31
,I/AMMetaDataParserService( 3602): Icon data: ResourceStarred message2131362389com.android.email.intent.messageviewfragment.favorite2130837577
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 4174): TimaSignature is unavailable
D/ActivityThread( 4174): Added TimaKeyStore provider
,E/        ( 3602): GFX convertToRaster() in Bitmap.cpp for bitmap size 80x80
,I/GFX raster( 3602): took 0.762083ms for 80*80 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3602): Bitmap=0xb78fcae0 bitmapCt=12 bitmapW=80 bitmapH=80 BitmapInternalFormat=93b0, Counterpart=0xb7ad63e0 counterpartCT=4 counterpartW=80 counterparth=80
,D/RCPManagerService( 1020): exchangeData() failure , invalid userId
,I/AMMetaDataParserService( 3602): Icon data: ResourceUnstarred message2131362390com.android.email.intent.messageviewfragment.favorite2130837577
,D/RCPManagerService( 1020): exchangeData() failure , invalid userId
,W/libprocessgroup( 1020): failed to open /acct/uid_10020/pid_3391/cgroup.procs: No such file or directory
W/libprocessgroup( 1020): failed to open /acct/uid_1000/pid_3408/cgroup.procs: No such file or directory
,D/RCPManagerService( 1020): exchangeData() failure , invalid userId
,D/RCPManagerService( 1020): exchangeData() failure , invalid userId
,I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.email.activity.setup.MailboxSettings
W/ContextImpl( 3602): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.email.messageview.SelectGroup
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.email.messageview.SavedEmail
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.email.messageview.MessageFileView
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsHtmlSignature
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.email.activity.MessageCompose
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:android.app.spellscroll
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.email.activity.SelectMapActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.email.activity.CustomizeDate
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.email.activity.QuickReplyActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.email.activity.SettingsReservationActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.email.activity.AttachmentChooserActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.email.activity.DebugActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupBasicsChoiceProviderForKOR
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSoundNotiSetup
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSoundNotiGeneralPreference
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.email.activity.SearchActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3602): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.email.activity.MessageComposeDrawingModePopup
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.email.activity.utils.airjump.EmailAirScrollTryActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.email.activity.SmartStayActivity
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/SecurityLogAgent( 4174): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 4174): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 4174): StateMachine : Current State = 1
D/SecurityLogAgent( 4174): BootReceiver : completed task. Failed to return wakelock . 
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.mms.rcs.RcsNewFeatureActivity
,I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.mms.ui.RoamingGuardPopupActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.mms.ui.AutoRetrievePreferenceActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.mms.ui.AutoRetrieveTabActivity
,I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.mms.ui.ConversationComposer
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:android.app.spellscroll
,I/AMMetaDataParserService( 3602): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 3602): getResourcePackageName:assistant
I/AMMetaDataParserService( 3602): Resource data:2131099648
,E/Zygote  ( 4196): MountEmulatedStorage()
E/Zygote  ( 4196): v2
I/libpersona( 4196): KNOX_SDCARD checking this for 10148
I/libpersona( 4196): KNOX_SDCARD not a persona
,I/SELinux ( 4196): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
W/ResourcesManager( 3602): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
I/AMMetaDataParserService( 3602): getResourceName:com.android.mms:xml/assistant_messaging
W/ResourcesManager( 3602): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/AMMetaDataParserService( 3602): getResourceTypeNamexml
,W/ResourcesManager( 3602): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3602): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 3602): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
I/ActivityManager( 1020): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=4196 uid=10148 gids={50148, 9997, 1023} abi=armeabi-v7a
,I/ActivityManager( 1020): Killing 3430:com.sec.factory.camera/1000 (adj 15): empty #31
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/SELinux ( 4196): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4196): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3602): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,D/RCPManagerService( 1020): exchangeData() failure , invalid userId
,W/ActivityManager( 1020): getTasks: caller 10142 does not hold GET_TASKS; limiting output
,D/BadgeProvider( 4100): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/RCPManagerService( 1020): exchangeData() failure , invalid userId
,I/Process ( 4122): Sending signal. PID: 4122 SIG: 9
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/Launcher.Model( 1477): reloadBadges entered.
D/BadgeProvider( 4100): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 4100): sendNotify, [notify] : null
D/BadgeProvider( 4100): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 4100): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 4100): update, [UpdateCount] : 1
,D/TimaKeyStoreProvider( 4196): TimaSignature is unavailable
,D/ActivityThread( 4196): Added TimaKeyStore provider
,I/GAV2    ( 3526): Thread[GAThread,5,main]: No campaign data found.
,I/AMMetaDataParserService( 3602): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,I/AMMetaDataParserService( 3602): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/SQLiteLog( 4196): (284) automatic index on shooting_modes(title_id)
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/libprocessgroup( 1020): failed to open /acct/uid_1000/pid_3430/cgroup.procs: No such file or directory
,I/ActivityManager( 1020): Process com.android.exchange (pid 4122)(adj 11) has died(22,665)
,I/AMMetaDataParserService( 3602): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.samsung.android.provider.shootingmodeprovider, destAppInfo.processName = com.samsung.android.provider.shootingmodeprovider
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/AMMetaDataParserService( 3602): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4218): MountEmulatedStorage(),
I/libpersona( 4218): KNOX_SDCARD checking this for 1000
E/Zygote  ( 4218): v2
I/libpersona( 4218): KNOX_SDCARD not a persona
,I/SELinux ( 4218): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4218): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1020): Start proc com.sec.modem.settings for broadcast com.sec.modem.settings/.cplogging.SilentLogReceiver: pid=4218 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/SELinux ( 4218): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3602): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessageActivityNoLockScreen
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessageMms
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:assistant
I/AMMetaDataParserService( 3602): Resource data:2131099648
,I/AMMetaDataParserService( 3602): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3602): getResourceTypeNamexml
,I/AMMetaDataParserService( 3602): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,D/TimaKeyStoreProvider( 4218): TimaSignature is unavailable
,D/ActivityThread( 4218): Added TimaKeyStore provider
,I/AMMetaDataParserService( 3602): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,I/AMMetaDataParserService( 3602): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,I/splitIntent( 1020): Queue : backgroundsplit_1 intent android.intent.action.BOOT_COMPLETED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/AMMetaDataParserService( 3602): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522,
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
I/ActivityManager( 1020): Killing 3451:com.samsung.android.app.FileShareServer/u0a65 (adj 15): empty #31,
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
I/AMMetaDataParserService( 3602): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,I/UpdateIcingCorporaServi( 3025): UpdateCorporaTask done [took 6557 ms] updated apps [took 6557 ms] 
,I/AMMetaDataParserService( 3602): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.mms.ui.TransferContentActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.mms.ui.CbConfigPreferenceActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.mms.ui.CbSettingTabActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessage
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:assistant
I/AMMetaDataParserService( 3602): Resource data:2131099648
,I/AMMetaDataParserService( 3602): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3602): getResourceTypeNamexml
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/AMMetaDataParserService( 3602): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,W/ActivityManager( 1020): userId = 0, bbcId = -10000,
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/AMMetaDataParserService( 3602): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/AMMetaDataParserService( 3602): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/AMMetaDataParserService( 3602): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/CalendarProvider2( 3995): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,I/AMMetaDataParserService( 3602): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/AMMetaDataParserService( 3602): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,V/AlarmManager( 1020): waitForAlarm result :4
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/ActivityManager( 1020): Killing 3467:com.samsung.android.provider.filterprovider/u0a95 (adj 15): empty #31
,I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.mms.ui.ForwardMessageActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:assistant
I/AMMetaDataParserService( 3602): Resource data:2131099648
,I/AMMetaDataParserService( 3602): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3602): getResourceTypeNamexml
,I/AMMetaDataParserService( 3602): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1020): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/SIP     ( 1455): [SipSharedPreferences] isReceivingCallsEnabled, option not set; use default value, exception: android.provider.Settings$SettingNotFoundException: sip_receive_calls
,I/splitIntent( 1020): intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
I/splitIntent( 1020): base  index=1, name=com.google.android.gms com.google.android.gms.wearable.service.AutoStarterReceiver
I/splitIntent( 1020): other index=4, name=com.google.android.gms com.google.android.gms.init.InitializeGmsReceiver
I/splitIntent( 1020): arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/File    ( 1455): fail readDirectory() errno=2
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/WearableService( 1633): callingUid 10011, callindPid: 1633
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3602): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/MDM     ( 1633): [208] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3602): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,D/AuthorizationBluetoothService( 1633): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1633): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/LocationInitializer( 1788): Restart initialization of location
,I/AMMetaDataParserService( 3602): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3602): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3602): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.mms.ui.ReplyMessageActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:assistant
I/AMMetaDataParserService( 3602): Resource data:2131099648
,I/AMMetaDataParserService( 3602): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3602): getResourceTypeNamexml
,W/libprocessgroup( 1020): failed to open /acct/uid_10065/pid_3451/cgroup.procs: No such file or directory
,W/libprocessgroup( 1020): failed to open /acct/uid_10095/pid_3467/cgroup.procs: No such file or directory
,I/AMMetaDataParserService( 3602): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,I/AMMetaDataParserService( 3602): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,I/AMMetaDataParserService( 3602): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,I/AMMetaDataParserService( 3602): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,I/AMMetaDataParserService( 3602): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,I/AMMetaDataParserService( 3602): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.mms.ui.ConversationList
,I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:assistant
,I/AMMetaDataParserService( 3602): Resource data:2131099648
,I/AMMetaDataParserService( 3602): getResourceName:com.android.mms:xml/assistant_messaging
,I/AMMetaDataParserService( 3602): getResourceTypeNamexml
,I/AMMetaDataParserService( 3602): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,I/AMMetaDataParserService( 3602): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,I/AMMetaDataParserService( 3602): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,I/AMMetaDataParserService( 3602): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,I/AMMetaDataParserService( 3602): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,I/art     ( 1020): Explicit concurrent mark sweep GC freed 23742(1372KB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 22MB/33MB, paused 2.143ms total 139.837ms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/AMMetaDataParserService( 3602): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.mms.ui.WarnOfStorageLimitsActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.mms.ui.SlideshowActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.mms.ui.MmsSinglePageActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.mms.ui.ClassZeroActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.mms.ui.RetryActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.mms.ui.MessagingPreferenceActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.mms.settings.EntrancePrefActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.mms.settings.DisplaySettings
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.mms.settings.CMASSettings
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.mms.settings.TextMessagesSettings
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.mms.settings.MultimediamessagesSettings
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.mms.rcs.settings.RcsMessagesSettings
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.mms.settings.DeleteoldMessagesSettings
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.mms.settings.PushMessagesSettings
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.mms.settings.NotificationSettings
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.mms.settings.NotificationSettingsDS
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.mms.settings.SignatureSettings
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.mms.settings.SpamSettings
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.mms.settings.SafemodeSettings
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.mms.settings.DelaySendingSettings
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.mms.smishing.PackageAuthorityActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.mms.smishing.PackageAuthorityDialog
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.mms.settings.MessageSmscActivityDS
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.mms.settings.SignatureEditActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.mms.settings.CallbackNumberSettings
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.mms.settings.CallbackNumberEditActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.mms.settings.BackgroundStyle
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.mms.settings.BubbleStyle
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.mms.ui.PushMessageDialog
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.mms.saverestore.SaveThreadActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.mms.saverestore.SavedMsgsList
W/ContextImpl( 3602): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3602): Resource data:Loop for ,running activitycom.android.mms.saverestore.RestorePreviewActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.mms.saverestore.ConversationListRestore
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.mms.ui.ManageSimMessages
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.mms.ui.MmsRetryActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.mms.ui.ConfirmRateLimitActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.mms.ui.SearchActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.mms.ui.SmsViewerActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.mms.ui.MmsNotificationViewerActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.mms.ui.DrmContentsActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.mms.ui.CMASPreferenceActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.mms.ui.CMASDialog
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.mms.ui.CMASDialog_single_top
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.mms.ui.PDPResetDialog
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.mms.ui.CMASUserPromptDialog
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.mms.ui.LockedMessageManager
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.mms.ui.SpamMessageManager
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.mms.ui.ReservationMessageManager
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.mms.ui.DraftMessageManager
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.mms.ui.SafeMessageManager
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.mms.ui.RecipientListActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.mms.ui.GroupMessagingRecipientListActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.mms.ui.SelectMapActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.mms.location.LocationMapActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3602): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.mms.location.FavoritePlacesList
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.mms.location.RecentPlacesList
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.mms.ui.BoxListViewActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.mms.provisioning.MmsProvisionActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.mms.ui.ManageSDMessages
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamNumberList
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamKeywordList
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamNumberWriteForm
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamKeywordWriteForm
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.mms.ui.SettingsReservationActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.mms.ui.SettingsTransmitMessageActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.mms.ui.MessageDatabaseBackupActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.mms.widget.NoticeThreadContactSelector
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.mms.widget.NoticeEditActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.mms.widget.NoticeDeleteActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.mms.export.MmsPartExportDialogActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.mms.export.MmsPartExportDialogActivityAlien
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.mms.ui.DirectCallTutorialActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.mms.ui.FakeCallActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.mms.ui.MmsPartExportActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.mms.template.TextTemplateListActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.mms.template.TextTemplateEditActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.mms.help.AirViewMainActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.mms.help.AirButtonMainActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.mms.widget.WidgetPreferenceActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.mms.cover.MissedMsgActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.mms.oem.AutoSendingTestActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.mms.prioritysender.AddGlanceListActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.mms.prioritysender.AddThreadListActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.mms.settings.CheckDefaultSmsAppsActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.mms.accessory.ReadReportActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.mms.ui.FileHistoryListActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.mms.settings.FreeMessageSettings
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.mms.prioritysenderpanel.CocktailPrioritySenderSettingActivity
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1020): userId = 0, bbcId = -10000
I/iu.UploadsManager( 1788): End new media; added: 0, uploading: 0, time: 301 ms
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.sec.android.gallery3d.app.GalleryOpaqueActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:assistant
W/GCoreFlp( 1633): No location to return for getLastLocation()
W/FusedLocationProvider( 1633): location=null
I/AMMetaDataParserService( 3602): Resource data:2131165197
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ResourcesManager( 3602): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3602): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3602): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3602): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 3602): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 3602): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 3602): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
I/AMMetaDataParserService( 3602): getResourceName:com.sec.android.gallery3d:xml/assistant
I/AMMetaDataParserService( 3602): getResourceTypeNamexml
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
I/DBG_DM  ( 2894): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 8 sec
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
I/AMMetaDataParserService( 3602): Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,I/AMMetaDataParserService( 3602): Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623,
,E/Zygote  ( 4244): MountEmulatedStorage(),
I/libpersona( 4244): KNOX_SDCARD checking this for 10041
E/Zygote  ( 4244): v2
I/libpersona( 4244): KNOX_SDCARD not a persona,
I/SELinux ( 4244): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4244): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4244): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/AMMetaDataParserService( 3602): Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,I/ActivityManager( 1020): Start proc com.android.mms for broadcast com.android.mms/.widget.MmsWidgetProvider: pid=4244 uid=10041 gids={50041, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
,D/TimaKeyStoreProvider( 4244): TimaSignature is unavailable
,D/ActivityThread( 4244): Added TimaKeyStore provider
,I/AMMetaDataParserService( 3602): Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.sec.android.gallery3d.app.GalleryActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3602): getResourcePackageName:assistant
I/AMMetaDataParserService( 3602): Resource data:2131165197
,I/AMMetaDataParserService( 3602): getResourceName:com.sec.android.gallery3d:xml/assistant
I/AMMetaDataParserService( 3602): getResourceTypeNamexml
,W/ResourcesManager( 4244): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 4244): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4244): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 4244): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 4244): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3602): Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,I/AMMetaDataParserService( 3602): Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
,I/AMMetaDataParserService( 3602): Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,I/AMMetaDataParserService( 3602): Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.cooliris.media.Gallery
,I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.sec.android.gallery3d.app.Gallery
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:assistant
I/AMMetaDataParserService( 3602): Resource data:2131165197
,I/AMMetaDataParserService( 3602): getResourceName:com.sec.android.gallery3d:xml/assistant
,I/AMMetaDataParserService( 3602): getResourceTypeNamexml
,I/AMMetaDataParserService( 3602): Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,D/Mms/MmsApp( 4244): [start]    onCreate() consume time = 0.0
,I/AMMetaDataParserService( 3602): Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
,I/AMMetaDataParserService( 3602): Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,I/AMMetaDataParserService( 3602): Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.sec.android.gallery3d.app.UsbDeviceActivity
,I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:android.hardware.usb.action.USB_DEVICE_ATTACHED
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.sec.android.gallery3d.app.Wallpaper
,I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:android.wallpaper.preview
,I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.sec.android.gallery3d.app.LockScreen
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:android.wallpaper.preview
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.sec.android.gallery3d.app.BothScreen
,I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:android.wallpaper.preview
,I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.sec.android.gallery3d.app.CropImage
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.sec.android.gallery3d.app.ContextualTagSetting
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.sec.android.gallery3d.app.ContextualTagWeatherSetting
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.sec.samsung.gallery.view.gallerysearch.DeleteHistoryForGallerySearchActivity
,I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.sec.samsung.gallery.view.usertag.AddUserTagListActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.sec.samsung.gallery.view.detailview.moreinfo.MoreInfoLocationEditActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:android.app.searchable
,I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.GallerySettings
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetTypeChooser
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetClickHandler
,I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetConfigure
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.MagazineWidgetConfigure
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.EasyWidgetConfigure
,I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetPreferenceActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.MagazineWidgetPreferenceActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.AccountSettingActivity
,I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.FilterbySettingActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.sec.gallery2d.viewstate.MapView2dPage
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.sec.samsung.gallery.app.imagenote.ImageNote
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.sec.samsung.gallery.app.photonote.PhotoNote
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.sec.samsung.gallery.controller.StartMmsSaveCmd$CallMmsSave
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.sec.samsung.gallery.controller.GalleryChooserActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.sec.android.cloud.integrator.CloudIntegratorActivity
W/ContextImpl( 3602): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
,I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.sec.android.app.camera.Camera
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.samsung.android.cocktail.subwindow.enable
I/AMMetaDataParserService( 3602): getResourcePackageName:com.sec.android.multiwindow.activity.STYLE
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.keyguard.layout
I/AMMetaDataParserService( 3602): getResourcePackageName:assistant
I/AMMetaDataParserService( 3602): Resource data:2131099648
,W/ResourcesManager( 3602): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,W/ResourcesManager( 3602): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3602): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 3602): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
,W/ResourcesManager( 3602): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3602): getResourceName:com.sec.android.app.camera:xml/assistant
I/AMMetaDataParserService( 3602): getResourceTypeNamexml
,I/AMMetaDataParserService( 3602): Icon data: ResourceSwitch camera2131559034android.intent.action.switchcamera2130837512
,I/AMMetaDataParserService( 3602): Icon data: ResourceGallery2131558741android.intent.action.switchgallery2130837511
,I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.sec.android.app.camera.Camcorder
,I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.sec.android.app.camera.DummyActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.sec.android.app.camera.CropImage
,I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.sec.android.app.shootingmodemanager.ManageShootingModeActivity
,W/ContextImpl( 3602): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
,W/art     ( 4244): Verification of com.android.mms.ui.MsgSweepActionListView com.android.mms.ArtClassLoader.createMsgSweepActionList(android.content.Context) took 122.150ms
,I/ActivityManager( 1020): Waited long enough for: ServiceRecord{26568bf5 u0 com.sec.android.daemonapp/.ap.accuweather.WeatherClockService}
,I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.GridSettings
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:assistant
I/AMMetaDataParserService( 3602): Resource data:2131165220
,W/ResourcesManager( 3602): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 3602): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 3602): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3602): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3602): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3602): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3602): getResourceName:com.android.settings:xml/assistant
I/AMMetaDataParserService( 3602): getResourceTypeNamexml
,I/AMMetaDataParserService( 3602): Icon data: ResourceSearch2131363517com.android.settings.Search2130837580
,D/Mms/ArtClassLoader( 4244): init before art
,D/Mms/TelephonyPermission( 4244): start operation mode monitor
,W/ResourcesManager( 4244): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3602): Icon data: ResourceEdit quick settings2131361852com.android.settings.Favorite2130837579
,D/Mms/TelephonyPermission( 4244): DefaultSmsApp is com.android.mms
,D/Mms/TelephonyPermission( 4244): isDefault true
,D/Mms/MmsApp( 4244): onCreate() com.android.mms
,I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.SubSettings
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.LabelName
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.Password
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.Settings$EthernetSettingsActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
,I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.Settings$WirelessSettingsActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3602): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.Settings$WifiSettingsActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.wifi.WifiSettings
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.wifi.WifiPickerActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.wifi.WifiSecPickerActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.wifi.WifiCaptiveActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.wifi.FreeWifiScanPickerDialog
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.wifi.WifiWarningDialog
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.wifi.WifiOffloadDialog
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.wifi.WifiAdvancedSecSetupActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.wifi.WificmccSetupActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.wifi.WifiSecSetupActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.wifi.WifiWarningDialog
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.wifi.WifiSetupActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.accessibility.smartscroll.app.sbrowsertry.SmartScreenActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.wifi.WifiPickerDialog
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.wifi.WifiSettingsForSetupWizardXL
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.Settings$AdvancedWifiSettingsActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.Settings$SavedAccessPointsSettingsActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.Settings$WifiShareProfileActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaD,ataParserService( 3602): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.wifi.WifiInfo
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.wifi.WifiConfigInfo
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.wifi.WifiAPITest
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.wifi.WifiStatusTest
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApSettings
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApWarning
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApTestConfigure
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.wifi.WifiPoorConnection
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.wifi.WifiHiddenApListActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.wifi.WifiHiddenApDeleteActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.wifi.WifiDisconnectWeakApSettings
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.Settings$ApnSettingsActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.Settings$BluetoothSettingsActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothSettings
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothScanDialog
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothErrorActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.bluetooth.CheckBluetoothStateActivity
,I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.bluetooth.DevicePickerActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothEnableActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothEnablingActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.Settings$MirrorLinkActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.Settings$TetherSettingsActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3602): getResourcePackageName:com.samsung.android.multiuser.install_only_owner
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.TetherSettings
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): getResourcePackageName:com.samsung.android.multiuser.install_only_owner
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.Settings$WifiP2pSettingsActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.wifi.p2p.WifiP2pSettings
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.Settings$WifiP2pHelpActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.wifi.p2p.WifiP2pDummyPickerActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.Settings$NearbySettingsActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.nearby.NearbySettings
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3602): Resource, data:Loop for running activitycom.android.settings.wfd.WfdHelpActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.wfd.WfdPickerDialog
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.Settings$VpnSettingsActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.Settings$DateTimeSettingsActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.DateTimeSettingsSetupWizard
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.FeatureSettingsSetupWizard
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.Settings$LocalePickerActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.Settings$InputMethodAndLanguageSettingsActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID,
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.Settings$VoiceInputSettingsActivity
,I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.Settings$HandwritingLanguageActivity
,I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.handwritingsearch.HandwritingLanguageTablet
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.Settings$KeyboardLayoutPickerActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.LanguageSettings
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS,
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.Settings$SpellCheckersSettingsActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.inputmethod.InputMethodAndSubtypeEnablerActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED,
I/AMMetaDataParserService( 3602): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.Settings$UserDictionarySettingsActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.inputmethod.UserDictionaryAddWordActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.UserDictionarySettings
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.Settings$ZenModeSettingsActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3602): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.Settings$ZenModeDNDSettingsActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
W/ContextImpl( 3602): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3602): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.Settings$HomeSettingsActivity
,I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.HomeSettings
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.Settings$LockScreenSettingsActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.Settings$DisplaySettingsActivity
,I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
,I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.DisplaySettings
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.Settings$LockscreenMenuActivity,
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.Settings$BlockSettingsActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.Settings$LedIndicatorSettingsActivity
,I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.Settings$DockSettingsActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.DockSettings
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.ContextualPageSettings
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/ActivityManager( 1020): Killing 3484:com.samsung.android.MtpApplication/1000 (adj 15): empty #31
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.Settings$ContextualPageHelpActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.Settings$DeviceInfoSettingsActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.DeviceNameDialog
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.SettingsLicenseActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3602): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.PrivacyAlertDialogActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.PrivacyAlertProceedDialogActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.SettingsSafetyLegalActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3602): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.Settings$ManageApplicationsActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.applications.ManageApplications
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserS,ervice( 3602): Resource data:Loop for running activitycom.android.settings.ManageApplications
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.RunningServices
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.LaunchApplication
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.applications.StorageUse
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.applications.InstalledAppDetailsTop
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.accounts.ManageAccountsActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.applications.InstalledAppDetails
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.applications.UninstallMultipleScreen
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.Settings$RunningServicesActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.Settings$StorageUseActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.Settings$NotificationStationActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.Settings$AppOpsDetailsActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.Settings$LocationSettingsActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.Settings$SecuritySettingsActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): getResourcePackageName:c,om.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.MonitoringCertInfoActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.Settings$TrustedCredentialsSettingsActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.SecuritySettings
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.Settings$PrivacySettingsActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.SetFullBackupPassword
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.CredentialStorage
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.Settings$DeviceAdminSettingsActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.DeviceAdminSettings
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.DeviceAdminAdd
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.Settings$UsageAccessSettingsActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.SetProfileOwner
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.IccLockSettings
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.SimPinLockSettings
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.SimPersoLockSettings
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.Settings$AccessibilitySettingsActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.Settings$AccessibilityDaltonizerSettingsActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.samsung.settings.accessibility.AccessibilityWidgetDialogActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.Settings$CaptioningSettingsActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.Settings$MagnifierSettingsActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.Settings$AssistantMenuPreferenceFragmentActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.AccessibilitySettingsSetupWizard
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.Settings$TextToSpeechSettingsActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.Settings$DrivingModeSettingsActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.Settings$AssistiveHepticSettingsActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.ConfirmDeviceCredentialActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.notification.RedactionInterstitial
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.notification.RedactionSettingsStandalone
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.ConfirmLockPattern
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.ConfirmLockPassword
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.ConfirmLockEnterpriseIdentity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.ChooseLockEnterpriseIdentity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.ConfirmLockPattern$InternalActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.ConfirmLockPassword$InternalActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.BluetoothPairingWithCac
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.ChooseLockGeneric
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.ChooseLockGeneric$InternalActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.KnoxChooseLockTwoFactor
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.KnoxChooseLockBackupPin
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.ChooseLockPattern
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.ChooseLockBLock
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.ChooseLockPassword
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.ChooseLockMotion
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.ChooseLockAdditionalPin
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.ChooseLockSignature
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.EncryptionInterstitial
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.deviceinfo.Status
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.Settings$StorageSettingsActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.deviceinfo.MiscFilesHandler
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.deviceinfo.DeviceInfoTabActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.ApnEditor
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.MediaFormat
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.MediaFormatSd
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.Settings$QuickLaunchSettingsActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.quicklaunch.BookmarkPicker
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.Settings$DevelopmentSettingsActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.Settings$PrintSettingsActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.Settings$PrintJobSettingsActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.DevelopmentSettings
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.AppPicker
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.Settings$UsbSettingsActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.UsbSettings
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothPairingDialog
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.bluetooth.RequestPermissionActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.wifi.WifiScanModeActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.bluetooth.RequestPermissionHelperActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothPermissionActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.ActivityPicker
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.Settings$NfcSettingsActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.nfc.NfcAdvancedRoutingSetting
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.Settings$AndroidBeamSettingsActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.Settings$SBeamSettingsActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.Settings$WifiDisplaySettingsActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.BatteryInfo
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.Display
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.RadioInfo
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.ProxySelector
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.BandMode
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.TestingSettings
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.fulllocalepickertest.FullLocalePickerTest
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.AppWidgetPickActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.AllowBindAppWidgetActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.UsageStatsActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.Settings$PowerUsageSummaryActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.fuelgauge.PowerUsageSummary
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.Settings$BatterySaverSettingsActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.Settings$AccountMenuActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.Settings$AccountSettingsActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.Settings$AccountSyncSettingsActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.accounts.AddAccountSettings
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.accounts.ChooseAccountActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.CryptKeeper
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.CryptKeeper$FadeToBlack
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.CryptKeeperConfirm$Blank
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.CryptDecryptConfirm$Blank
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.Settings$CryptKeeperSettingsActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.Settings$CryptDecryptSettingsActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.Settings$CryptSDCardSettingsActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.Settings$SimChangeAlertSettingsActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.Settings$DataUsageSummaryActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.Settings$DataUsageMeteredSettingsActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.Settings$DreamSettingsActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.Settings$UserSettingsActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.Settings$PaymentSettingsActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.nfc.PaymentDefaultDialog
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3602): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.SmsDefaultDialog
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.ActiveNetworkScorerDialog
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.Settings$NotificationAccessSettingsActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.Settings$ConditionProviderSettingsActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.Settings$NotificationSettingsActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.Settings$SoundSettingsActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.SoundSettings
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.Settings$OtherSoundSettingsActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.Settings$NotificationAppListActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.Settings$AppNotificationSettingsActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.Settings$SimSettingsActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.FactoryResetDialog
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.LockScreenWallpaper
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.Settings$WallpaperSettingsActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.GSensorSettings
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingModeSettingsActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingMode2014Activity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingModeSettings2014Activity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.Settings$UltraPowerSavingModeActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.ModePreviewTablet
W/libprocessgroup( 1020): failed to open /acct/uid_1000/pid_3484/cgroup.procs: No such file or directory
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.ModePreviewDialog
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.InkeffectPreview
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.InkeffectPreviewTablet
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.ModePreview
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.NewModePreview
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.SViewColor
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.SViewColor2014
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.SViewStyleClock
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.SViewMiniWallpaper
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.Settings$SViewCoverEdgeSettingsActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.ChooseLockFaceWarning
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.Settings$PowerSettingsActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.RecommendRingtoneDialog
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.Settings$SelectInfoCoverSettingsActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
D/CountryDetector( 1020): The first listener is added
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.SelectItemDisplay
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.Settings$WeatherSettingsFragmentActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.SViewCoverPopup
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.WarrantyLegal
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.SamsungLegalTablet
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.PenDetachmentOption
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.Settings$PenDetachmentOptionActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.NotificationPanelMenu
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.Settings$NotificationPanelMenuActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.NotificationPanelSettings
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.Settings$MotionSettingsActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.Settings$AirMotionSettingActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.Settings$SMotionGuideHub2014Activity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.Settings$FingerAirViewSettingActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.Settings$FingerAirViewHelpSettingActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.Settings$PenAirViewHelpSettingActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.Settings$AirViewSettingActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.Settings$MouseHoveringSettingsActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.Settings$SoftwareUpdateSettingActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.PenHelpActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.Settings$PenHelpFragmentActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.Settings$DirectPenInputSettingsActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.Settings$PenAirViewSettingsMenuActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.Settings$PenSettingsMenuActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.PhoneVibration
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.OneHandHelp
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.OneHandAdaptiveHelp
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.Settings$OneHandSideSoftKeyFragmentActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.personalvibration.PersonalVibration
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.personalvibration.SelectPatternDialog
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.LockScreenShortcutSettings
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.AppList
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.ExpandAppList
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.Settings$ReadingModeSettingsActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.customizablekey.CustomizableKeySettings
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.Settings$CustomizableKeySettingsActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.customizablekey.AppList
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.Settings$DualClockSettingActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.Settings$RecommendedAppsMenuActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.Settings$RecommendedAppsListActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.SettingsReceiverActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.SelectPenDetachNotiDialog
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.SecurityWarningDialog
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.Settings$PersonalPageSettingsActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageSettings
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.PersonalPageDisclaimer
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageAutoModeSwitchAlertDialogActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorial
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialDisclaimerActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialAppActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialAddActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockPattern
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockPassword
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockAdditionalPin
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageConfirmLockPattern
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageConfirmLockPassword
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.Settings$EasyModeSettingsActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.Settings$EasyModeActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.Settings$EasyModeAppActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.Settings$MyPlaceSettingsActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.Settings$MyPlaceProfileSettingsActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.Settings$PlaceSettingsActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.myplace.SelectMapActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.Settings$GlobalRoamingSettingsActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.Settings$TRoamingSettingsActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.flipfont.FontListActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.flipfont.FontListProgressActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.Settings$BackupAssistantPlusSettingsActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.myprofile.MyProfileActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.MagazineCard
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.Settings$ClockWidgetActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.myprofile.PersonalMessage
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.Settings$CloudSettingActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.ShortCameraMenu
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.ClockMyprofileMenu
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.ClockMyprofileMenuTablet
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.Settings$LaunchCameraSettingsActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.Settings$SmartScreenSettingsActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.Settings$SmartBondingSettingsActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.Settings$ToolboxMenuActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.Settings$ToolboxListActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.Settings$SmartScrollAdvancedSettingsActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.Settings$MultiWindowSettingsActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.MultiWindowSettings
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.settingssearch.SettingsSearchActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.SearchActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.Settings$ColorChipReportActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.Settings$DirectAccessActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.Settings$NotificationReminderActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.Settings$VoiceInputControlSettingsActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.PreloadAppUpdate
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.PreloadAppUpdateList
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.activekey.ActiveKeySettings
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.Settings$ActiveKeySettingsActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.activekey.AppList
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.Settings$DisplaySettingsTab
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.SETTING_HEADER_ID
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.Settings$InputAndControlSettingsTab
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.SETTING_HEADER_ID
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.Settings$GeneralSettingsTab
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.SETTING_HEADER_ID
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.DeviceHealthActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.Settings$SettingsEmergencyActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareSettingsActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 360,2): Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareEmergencyModeActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareDisasterActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareDisclaimerActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareDisasterDisclaimerActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareCoverageDialog
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.Settings$AirplaneModeSettingsActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.Settings$ToddlerModeSettingsActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.favorite.FavoriteMenuList
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.Settings$FestivalEffectSettingsActivity
I/AMMetaDataParserService( 3602): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3602): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.powersavingmode.PowerNotiDialog
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.powersavingmode.PowerNotiDataDialog
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.wifi.SetupWizardWifiScreen
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.wifi.CaptivePortalWebViewActivity
I/AMMetaDataParserService( 3602): Resource data:Loop for running activitycom.android.settings.KnoxActiveProtectionEulaActivity
D/Mms/MmsApp( 4244): [start]    initCountryIso consume time = 324.349895
D/Mms/MmsApp( 4244): [end]    initCountryIso consume time = 8.78224
D/Mms/MmsConfig( 4244): [start]    MmsConfig.init() consume time = 0.077448
D/Mms/MmsConfig( 4244): before partial update
,D/Mms/MmsConfig( 4244): Load Resize quality : 80
,D/EasySignUpManager_1.0.1( 4244): serviceId : 1, features : -1
,D/EasySignUpManager_1.0.1( 4244): isAuth is false
D/Mms/MmsConfig( 4244): setFreeMessageEnabled, getSupportedFeatures = -1 isAuth = false
,D/TP/MmsSmsProvider( 1455): query,matched:2117, calling pid = 4244,
D/TP/MmsSmsProvider( 1455): match 2117:Elapsed time : 0.941 ms
,D/EasySignUpManager_1.0.1( 4244): isAuth is false
,D/EasySignUpManager_1.0.1( 4244): getServiceStatus : serviceId (1) is OFF
,E/CscParser( 4244): mps_code.dat does not exist
E/CscParser( 4244): customer_path =/system/csc/customer.xml
E/CscParser( 4244): fileName + /system/csc/customer.xml
,E/CscParser( 4244): mps_code.dat does not exist
,E/CscParser( 4244): customer_path =/system/csc/customer.xml
E/CscParser( 4244): fileName + /system/csc/customer.xml
,D/CscParser( 4244): getInstance fileName =/system/csc/customer.xml
,D/Mms/MmsConfig( 4244):  enable multiwindow = false
,E/Mms/MessageUtils( 4244): setCountryDetector : update country detector info 
E/Mms/MessageUtils( 4244): updateCountryIso : update country iso info 
,D/Mms/MmsConfig( 4244): [end]    init() consume time = 97.581041
,D/Mms/Contact( 4244): [start]    init() consume time = 6.372917
,D/Mms/Contact( 4244): [end]    init consume time = 10.475156
D/TP/MmsSmsProvider( 1455): query,matched:13, calling pid = 4244
D/TP/MmsSmsProvider( 1455): match 13:Elapsed time : 0.955 ms
,D/Mms/DraftCache( 4244): [start]    rebuildCache consume time = 13.228959
,D/Mms/MethodReflector( 4244): getSubId is called
D/Mms/TelephonyUtils( 4244): getLongSubId from simSlot 0, return Value = -1
,D/Mms/MethodReflector( 4244): getTelephonyProperty is called
D/Mms/DownloadManager( 4244): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 4244): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 4244): auto download without roaming -> true
D/Mms/DownloadManager( 4244): [NotificationTransaction] getAutoDownloadState alwaysAuto : true, roaming : false
D/Mms/MethodReflector( 4244): getSubId is called
,D/TP/MmsSmsProvider( 1455): query,matched:12, calling pid = 4244
,D/Mms/MethodReflector( 4244): getDefaultSmsSubId is called
E/Mms/TelephonyUtils( 4244): subID is null or 0 length, so get DefaultSubId!!
D/Mms/TelephonyUtils( 4244): getLongSubId from simSlot 1, return Value = -1000
D/Mms/MethodReflector( 4244): getTelephonyProperty is called
D/Mms/DownloadManager( 4244): roaming -> false (slotId = 1)
D/Mms/DownloadManager( 4244): [NotificationTransaction] getAutoDownloadState simSlot : 1
D/Mms/DownloadManager( 4244): auto download without roaming -> true
D/Mms/DownloadManager( 4244): [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
D/Mms/DownloadManager( 4244): auto download during roaming secondary -> false
D/Mms/DownloadManager( 4244): mAutoDownload ------> true
,D/TP/MmsSmsProvider( 1455): match 12:Elapsed time : 3.486 ms
,D/Mms/DraftCache( 4244): [end]    rebuildCache consume time = 14.741979
,D/ComposerPerformance( 4244): 1452552504779 ms / [DONE] Composer constructor
,D/Mms/Conversation( 4244): [start]    init() consume time = 12.663437
,D/TP/MmsSmsProvider( 1455): deleteConversation threadId: 9223372036854775807
,D/TP/MmsSmsProvider( 1455): delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
D/Mms/ArtClassLoader( 4244): init [DONE] art
,V/TP/MmsSmsDatabaseHelper( 1455): updateThread(), thread_id = 9223372036854775807
E/CII     ( 4244): CommonIMSInterface: VoLTE CSC feature disabled.
,V/TP/MmsSmsDatabaseHelper( 1455): sUpgradeVersion = 0, db.getVersion() = 81
,E/SQLiteLog( 1455): (284) automatic index on im_threads(normal_thread_id)
,E/SQLiteLog( 1455): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1455): (284) automatic index on im_threads(normal_thread_id)
,E/SQLiteLog( 1455): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1455): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1455): (284) automatic index on im_threads(normal_thread_id)
,I/Mms/ReservationManager( 4244): ReservationManager()
I/Mms/ReservationManager( 4244): resetAfterConnected()
,D/TP/MmsSmsProvider( 1455): query,matched:7, calling pid = 4244
,D/TP/MmsSmsProvider( 1455): match 7:Elapsed time : 4.973 ms
,I/Mms/ReservationManager( 4244): getReservedSendMessageCount(): retMessageCount=0
,D/TP/MmsSmsProvider( 1455): delete threadId: 9223372036854775807
D/TP/MmsSmsProvider( 1455): need read changed broadcast:false
,D/Mms/Conversation( 4244): [end]    init consume time = 27.332136
,D/Mms/MmsApp( 4244): [end]    onCreate() consume time = 4.119895
,D/Mms/MessagingNotification( 4244): [start]    init() consume time = 0.724323
,D/Mms/MessagingNotification( 4244): [end]    init consume time = 2.410209
,D/TP/MmsSmsProvider( 1455): query,matched:0, calling pid = 4244
,V/TP/MmsSmsProvider( 1455): getSimpleConversations entered.
,D/TP/MmsSmsProvider( 1455): match 0:Elapsed time : 1.789 ms
,D/Mms/Synchronizer( 4244): [start]    doSync consume time = 8.114062
D/Mms/SpamFilter( 4244): [start]    SpamFilter fill() begin consume time = 5.465261
,D/TP/MmsSmsProvider( 1455): update, matched:300, calling pid = 4244
,V/TP/MmsSmsProvider( 1455): syncDBData start
,D/Mms/DownloadManager( 4244): Service state changed: Bundle[mParcelledData.dataSize=744]
V/TP/MmsSmsProvider( 1455): syncDBData sms end
,D/Mms/DownloadManager( 4244): roaming ------> false, mSimSlot = 0
,V/TP/MmsSmsProvider( 1455): syncDBData mms end
,V/TP/MmsSmsProvider( 1455): syncDBData end
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.contacts, destAppInfo.processName = com.android.contacts
,D/TP/MmsSmsProvider( 1455): query,matched:400, calling pid = 4244
,I/ActivityManager( 1020): Killing 3506:com.samsung.android.app.watchmanagerstub/u0a98 (adj 15): empty #31
,D/Mms/MethodReflector( 4244): getSubId is called
D/Mms/TelephonyUtils( 4244): getLongSubId from simSlot 0, return Value = -1
,D/Mms/MethodReflector( 4244): getTelephonyProperty is called
D/Mms/DownloadManager( 4244): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 4244): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 4244): auto download without roaming -> true
D/Mms/DownloadManager( 4244): [NotificationTransaction] getAutoDownloadState alwaysAuto : true, roaming : false
,D/Mms/DownloadManager( 4244): mAutoDownload ------> true
,D/Mms/Synchronizer( 4244): [end]    doSync consume time = 20.022083
,D/Mms/MessagingNotification( 4244): checkBadgeCount unreadCount=0 badgeCount=0
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
D/Mms/SpamFilter( 4244): [end]    SpamFilter fill() finished consume time = 6.748698
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.contacts, destAppInfo.processName = com.android.contacts
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/TP/SmsProvider( 1455): query,matched:26, calling pid = 4244
,D/TP/SmsProvider( 1455): match 26:Elapsed time : 1.287 ms
,D/TP/MmsSmsProvider( 1455): query,matched:6, calling pid = 4244
,D/TP/MmsSmsProvider( 1455): match 6:Elapsed time : 2.038 ms
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,W/libprocessgroup( 1020): failed to open /acct/uid_10098/pid_3506/cgroup.procs: No such file or directory
,E/Zygote  ( 4271): MountEmulatedStorage()
E/Zygote  ( 4271): v2
I/libpersona( 4271): KNOX_SDCARD checking this for 10023
I/libpersona( 4271): KNOX_SDCARD not a persona
I/SELinux ( 4271): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1020): Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=4271 uid=10023 gids={50023, 9997} abi=armeabi-v7a
,I/SELinux ( 4271): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4271): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 4271): TimaSignature is unavailable
,D/ActivityThread( 4271): Added TimaKeyStore provider
,I/art     (  308): Explicit concurrent mark sweep GC freed 8693(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 605us total 26.687ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 576us total 16.865ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 566us total 16.031ms
,E/Zygote  ( 4286): MountEmulatedStorage(),
E/Zygote  ( 4286): v2
I/libpersona( 4286): KNOX_SDCARD checking this for 1000
,I/ActivityManager( 1020): Start proc com.samsung.android.MtpApplication for broadcast com.samsung.android.MtpApplication/.MtpReceiver: pid=4286 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/libpersona( 4286): KNOX_SDCARD not a persona
,I/SELinux ( 4286): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4286): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 4286): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1020): Killing 3084:com.sec.pcw.device/1000 (adj 15): empty #31
,D/TimaKeyStoreProvider( 4286): TimaSignature is unavailable
,D/ActivityThread( 4286): Added TimaKeyStore provider
,I/DBG_DM  ( 2894): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 9 sec
,E/MTPRx   ( 4286): In MtpReceiverandroid.hardware.usb.action.USB_STATE
W/libprocessgroup( 1020): failed to open /acct/uid_1000/pid_3084/cgroup.procs: No such file or directory
,D/SecContentProvider2( 1020): uri = 14 selection = getSealedState
D/SecContentProvider2( 1020): mCursor = null
,D/SecContentProvider2( 1020): uri = 14 selection = getSealedUsbMassStorageState
,D/SecContentProvider2( 1020): mCursor = null
,V/MTPRx   ( 4286): sealedState: false
V/MTPRx   ( 4286): sealedUsbMassStorageState: false
E/MTPRx   ( 4286): check value of boot_completed is1
E/MTPRx   ( 4286): check booting is completed_sys.boot_completed
,I/OMACP   ( 4271): [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
,E/MTPRx   ( 4286): Sd-Card path/storage/extSdCard
,E/MTPRx   ( 4286): Status for mount/Unmount :removed
E/MTPRx   ( 4286): SDcard is not available
,W/MTPRx   ( 4286): value of connected istrue
W/MTPRx   ( 4286): value of configured istrue
W/MTPRx   ( 4286): value of mtpEnabled istrue
W/MTPRx   ( 4286): value of ptpEnabled isfalse
,D/Mms/Contact( 4244): sContactsObserver.onChange(),selfUpdate=false
,E/MTPRx   ( 4286): Received USB_STATE with sdCardLaunch = 0
,D/Mms/Contact( 4244): performUpdate:widgetCount=0
,E/MTPRx   ( 4286): mFirstTime: false
,D/Mms/ContactsCache( 4244): [start]    invalidate() consume time = 241.617396
D/Mms/ContactsCache( 4244): [end]    invalidate() consume time = 0.108229
,I/ValidateNoPeople( 1020): mEvictionCount: 0
,D/Mms/Omacp( 4244): checkOmacp()  old OmacpCount 0 current OmacpCount = 0
,D/        ( 4286): MTP: reading debug level property
,E/MTPJNIInterface( 4286): Getting CryptionKey from JAVA
E/MTPRx   ( 4286): currentUserId is 0
,E/MTPRx   ( 4286): Start observing USB_STATE_MATCH 
,E/MTPRx   ( 4286): cannot open file : /sys/class/android_usb/android0/bcdUSB
E/MTPRx   ( 4286): is_Privatemode is NOT 1
,I/OMACP   ( 4271): [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
,I/OMACP   ( 4271): [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
,I/OMACP   ( 4271): [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
,I/OMACP   ( 4271): [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
,D/SettingsProvider( 1020): name = boot_time_connected
I/OMACP   ( 4271): [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
,I/OMACP   ( 4271): [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
,I/OMACP   ( 4271): [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
,I/OMACP   ( 4271): [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false,
I/OMACP   ( 4271): [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
E/MTPRx   ( 4286): Sending NORMAL_BOOT to stack
E/MTPJNIInterface( 4286): noti = 17
,I/OMACP   ( 4271): [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
,I/OMACP   ( 4271): [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
,D/SettingsProvider( 1020): name = mtp_usb_conditions_met
,I/OMACP   ( 4271): [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
,I/OMACP   ( 4271): [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
,D/SecContentProvider( 1020): uri = 18 selection = isUsbMediaPlayerAvailable
,E/MTPRx   ( 4286): sending MTP_ICON_ENABLED to stack
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.samsung.android.MtpApplication
,D/SettingsProvider( 1020): name = mtp_running_status
,D/SettingsProvider( 1020): name = mtp_usb_conditions_met
,E/MTPRx   ( 4286): else part ... so first time!!!
,I/SecKeyguardClockSingleView( 1177): Ignore. Because it is same clock text
,E/MTPPlaObsrvr( 4286): inside setContext()
,E/MTPPlaObsrvr( 4286):  inside createplafiles
,E/MTPPlaObsrvr( 4286): playlist count is0
,E/MTPPlaObsrvr( 4286):  inside try branch createplafiles
,E/MTPPlaObsrvr( 4286):  inside deleteing plas createplafiles
,E/MTPPlaObsrvr( 4286): Inside registerContentObserver
,E/MtpAdbObserver( 4286): inside setContext()
,E/MtpAdbObserver( 4286): Inside registerContentObserver
,W/Settings( 4286): Setting adb_enabled has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only global URI.
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.samsung.android.MtpApplication
D/SettingsProvider( 1020): name = mtp_running_status
D/SettingsProvider( 1020): name = mtp_usb_conditions_met
,V/MtpMediaDBManager( 4286): inside deleteAllDB
,E/MtpService( 4286): onCreate.
,E/MtpService( 4286): < MTP > Registering BroadCast receiver :::::
,E/MtpService( 4286): < MTP > Registering BroadCast registerBroadCastPolicyRec :::::
,E/MtpService( 4286): < MTP > Registering BroadCast registerBroadCastEmergencyRec :::::
,E/MtpService( 4286): onStartCommand.
W/MTPRx   ( 4286): calling native method
E/MTPJNIInterface( 4286): < MTP > Registering BroadCast receiver :::::
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,E/MtpService( 4286): handleMessage. msg= { when=-3ms what=0 arg1=1 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
,E/MTPJNIInterface( 4286): < MTP > Registering BroadCast receiver :::::::
,E/MTPJNIInterface( 4286): noti = 10
,E/MtpService( 4286): onStartCommand.
,W/MTPRx   ( 4286): calling native method
E/MtpService( 4286): handleMessage. msg= { when=0 what=0 arg1=2 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
E/MTPRx   ( 4286): Checking the driver time out
E/MTPJNIInterface( 4286): noti = 2
D/        ( 4286): deleting sockets before message queue initialization
,D/        ( 4286): event handler thread is created, so set the flag
D/MtpService( 1230): updating state; isCurrentUser=true, mMtpLocked=false
,E/MTPRx   ( 4286): called native method
,E/MTPJNIInterface( 4286): setting Media scanner status0
E/MTPJNIInterface( 4286): After setting Media scanner status0
W/MTPRx   ( 4286): notification from stack 1
,E/        ( 4286): Unable to get Object Class and clearing cls 2 [int check_media_scanner_status() 594]
E/MTPJNIInterface( 4286): Getting media scanner status0
,E/MTPJNIInterface( 4286): DeviceName is Thali Test (Galaxy A3)
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,V/MtpMediaDBManager( 4286): inside Thread updateDB
,E/Zygote  ( 4308): MountEmulatedStorage(),
,E/Zygote  ( 4308): v2
,I/libpersona( 4308): KNOX_SDCARD checking this for 1000
I/libpersona( 4308): KNOX_SDCARD not a persona
,I/SELinux ( 4308): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1020): Start proc com.samsung.android.app.mirrorlink for broadcast com.samsung.android.app.mirrorlink/.TMNetworkReceiver: pid=4308 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 4308): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 4308): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/MtpMediaDBManager( 4286): count : 26
,D/TimaKeyStoreProvider( 4308): TimaSignature is unavailable
,D/ActivityThread( 4308): Added TimaKeyStore provider
,W/MtpMediaDBManager( 4286): sending db update complete noti to stack
E/MTPJNIInterface( 4286): noti = 29
,E/MTPJNIInterface( 4286): Status for mount/Unmount :removed
,E/MTPJNIInterface( 4286): SDcard is not available
,E/        ( 4286): [mtp_hidden_system_volume 189] Error opening file [error = Read-only file system] 
,E/MTPJNIInterface( 4286): Status for mount/Unmount :removed
,E/MTPJNIInterface( 4286): SDcard is not available
E/SQLiteLog( 4286): (21) API call with NULL database connection pointer
E/SQLiteLog( 4286): (21) misuse at line 106108 of [9491ba7d73]
E/SQLiteLog( 4286): (21) API call with NULL database connection pointer
E/SQLiteLog( 4286): (21) misuse at line 100726 of [9491ba7d73]
E/SQLiteLog( 4286): (21) API call with NULL database connection pointer
E/SQLiteLog( 4286): (21) misuse at line 100726 of [9491ba7d73]
E/SQLiteLog( 4286): (21) API call with NULL database connection pointer
E/SQLiteLog( 4286): (21) misuse at line 106108 of [9491ba7d73]
,W/MTPRx   ( 4286): notification from stack 2
,D/        ( 4286): [mtp_init_device] Library open with 32 bits.
,D/        ( 4286): [mtp_init_device] Going to open(): /dev/usb_mtp_gadget
,E/        ( 4286): [mtp_init_device 702]  After open the MTP fd = 33 and line = 702...
D/        ( 4286): [mtp_init_device] IOCTL SET_MTP_USER_PID Sucesss 
,E/        ( 4286):  [sua_support_present:1287] returning false 
D/        ( 4286): [mtp_init_device] b4 calling MTP_ONLY_ENABLE  ioctl coneect to host

```
