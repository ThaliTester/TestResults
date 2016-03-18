#### Test 62548124b8ccb9f_thali07_samsung-SM-A500FU Logs


```
--------- beginning of system
I/ActivityManager( 1018): Killing 1514:com.android.printspooler/u0a136 (adj 15): empty #31
--------- beginning of main
I/DBG_DM  ( 3102): [com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI(2693/lllIlIlIIIllIIlIllIl)] xdbsqlGetFUMOStatus : 220
I/DBG_DM  ( 3102): [com.wssyncmldm.XDMApplication(80/onCreate)] XDMApplication Start ! - Fumo State
D/elm:15183( 3158): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:15183( 3158): ELMEngine.ELMEngine( context ).
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.wssyncmldm, destAppInfo.processName = com.wssyncmldm
D/elm:15183( 3158): MDMBridge.setEnterpriseBridge()
W/libprocessgroup( 1018): failed to open /acct/uid_10113/pid_2186/cgroup.procs: No such file or directory
W/ContextImpl( 3102): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 com.wssyncmldm.XDMApplication.onCreate:81 android.app.Instrumentation.callApplicationOnCreate:1020 android.app.ActivityThread.handleBindApplication:5256 
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.wssyncmldm/com.wssyncmldm.XDMService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
I/DBG_DM  ( 3102): [com.wssyncmldm.XDMBroadcastReceiver(152/onReceive)] android.intent.action.BOOT_COMPLETED
D/elm:15183( 3158): ELMAbstractReceiver : Receive Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
I/DBG_DM  ( 3102): [com.wssyncmldm.XDMService(1598/IlIlllIIlIlIIIlIlIll)] 
I/DBG_DM  ( 3102): [com.wssyncmldm.XDMService(1603/IlIlllIIlIlIIIlIlIll)] m_WakeLock is acquire!!
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
I/DBG_DM  ( 3102): [com.wssyncmldm.XDMService(1420/lllIlIlIIIllIIlIllIl)] 0
D/elm:15183( 3158): ElmAgentService : onCreate()
I/DBG_DM  ( 3102): [IIlIIIlllllIIlIIIlII(232/llllIllIIIIIlIIllIII)] Default - NO_ROOTING_CHECK : false
I/DBG_DM  ( 3102): [com.wssyncmldm.XDMService(1463/llIlIIIIlIIIIIlIlIII)] 0
D/elm:15183( 3158): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
I/DBG_DM  ( 3102): [IIlIIIlllllIIlIIIlII(261/IIllIlIIIIlIIIllIllI)] Roaming Check : true
D/elm:15183( 3158): ELMEngine.ServiceHandler.handleMessage( BOOT_COMPLETED ). 
D/elm:15183( 3158): BootCompletedState : startBootCompleted() call
I/DBG_DM  ( 3102): [com.wssyncmldm.XDMService(1548/llIIllllIIlllIIIIlll)] 0
I/DBG_DM  ( 3102): [IIlIIIlllllIIlIIIlII(293/llIIlIlIlIlIIIIIIlIl)] validation Check On
D/OverheatReceiver( 1188): onReceive() getAction : android.intent.action.BOOT_COMPLETED
D/OverheatReceiver( 1188): into the SAFE_MODE_ACTION
D/OverheatReceiver( 1188): VZW on -> change to Global UX [safe mode]
V/EmergencyMode( 1428): [EmergencyReceiver] EmergencyReceiver [android.intent.action.BOOT_COMPLETED]
D/OverheatReceiver( 1188): isSafeMode = false
I/DBG_DM  ( 3102): [com.wssyncmldm.XDMService(1505/IllIlIIIIlIIlIIIllIl)] 0
D/elm:15183( 3158): MDMBridge.getAllLicenseInfoFromSDK()
I/DBG_DM  ( 3102): [IIlIIIlllllIIlIIIlII(274/lllllllIlllIIlllIlIl)] SSL Check On
I/elm:15183( 3158): Get License : 0
D/elm:15183( 3158): ElmAgentService : onDestroy().
I/DBG_DM  ( 3102): [llIIlIIlIllIllIlllII(109/llllIIIllIlIIIIllllI)] 
I/DBG_DM  ( 3102): [IlIIlIIlIllllIlllIII(181/llIIIIlllllIIllIIllI)] XEVENT_OS_INITIALIZED
I/ActivityManager( 1018): Killing 2398:com.sec.android.widgetapp.activeapplicationwidget/u0a142 (adj 15): empty #31
D/BootupListener( 1468): intent.getAction() = android.intent.action.BOOT_COMPLETED
D/SettingsProvider( 1018): name = internet_call_settings_visibility
D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 1001
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
D/PhoneUtilsCommon( 1468): isSupportVoLTE is false.
I/Telecom ( 1442): InCallController: Attempting to bind to InCall com.android.incallui, is dupe? false 
I/DBG_DM  ( 3102): [llIIlIIlIllIllIlllII(397/llIIIIlllllIIllIIllI)] External SD Card Path : /storage/extSdCard
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.incallui
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.incallui/com.android.incallui.InCallServiceImpl; callingUser = 0; userId(target) = -2
I/Telecom ( 1442): InCallController: Attempting to bind to InCall com.google.android.gms, is dupe? false 
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.car.InCallServiceImpl; callingUser = 0; userId(target) = -2
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.google.android.gms
I/DBG_DM  ( 3102): [llIIlIIlIllIllIlllII(166/llllIIIllIlIIIIllllI)] bExternalStorageAvailable [true]
I/DBG_DM  ( 3102): [llIIlIIlIllIllIlllII(167/llllIIIllIlIIIIllllI)] bExternalSDStorageAvailable [false]
I/DBG_DM  ( 3102): [com.wssyncmldm.XDMService(1624/IIlIlIIlIlIIlIlllIIl)] 
I/DBG_DM  ( 3102): [com.wssyncmldm.XDMService(1629/IIlIlIIlIlIIlIlllIIl)] m_WakeLock is release!!
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
I/DBG_DM  ( 3102): [com.wssyncmldm.XDMService(155/onStartCommand)] 
E/Zygote  ( 3196): MountEmulatedStorage()
E/Zygote  ( 3196): v2,
I/SELinux ( 3196): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/libpersona( 3196): KNOX_SDCARD checking this for 10012
I/libpersona( 3196): KNOX_SDCARD not a persona
I/ActivityManager( 1018): Start proc com.google.android.gms:car for service com.google.android.gms/.car.InCallServiceImpl: pid=3196 uid=10012 gids={50012, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
I/SELinux ( 3196): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 3196): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.incallui
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.incallui/com.android.incallui.SecInCallService; callingUser = 0; userId(target) = -2
I/Telecom ( 1442): InCallController: onConnected to ComponentInfo{com.android.incallui/com.android.incallui.InCallServiceImpl}
I/Telecom ( 1442): InCallController: Unbinding from InCallService unbind
I/DBG_DM  ( 3102): [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
I/art     (  323): Explicit concurrent mark sweep GC freed 8769(373KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 1.749ms total 24.491ms
W/libprocessgroup( 1018): failed to open /acct/uid_10142/pid_2398/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_10136/pid_1514/cgroup.procs: No such file or directory
D/TimaKeyStoreProvider( 3196): TimaSignature is unavailable
D/ActivityThread( 3196): Added TimaKeyStore provider
I/DBG_DM  ( 3102): [llIlIIIIlllIlllllIll(142/llIIIIlllllIIllIIllI)] nSync = 0
W/ContextImpl( 3102): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.wssyncmldm.ui.lIlIIlIlIlIllllllIII.lllIlIlIIIllIIlIllIl:72 com.wssyncmldm.ui.lIlIIlIlIlIllllllIII.llIIIIlllllIIllIIllI:112 IlIIlIIlIllllIlllIII.llIIIIlllllIIllIIllI:185 
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.wssyncmldm/com.wssyncmldm.XDMService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.wssyncmldm, destAppInfo.processName = com.wssyncmldm
I/art     (  323): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 900us total 18.704ms
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
W/ResourcesManager( 3196): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3196): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/DBG_POLICYDM( 3173): [com.policydm.XDMApplication(554/xdmWakeLockAcquire)] 
I/DBG_POLICYDM( 3173): [com.policydm.XDMApplication(559/xdmWakeLockAcquire)] m_WakeLock is acquire!!
I/art     (  323): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 628us total 17.342ms
I/DBG_POLICYDM( 3173): [com.policydm.adapter.XDMTargetAdapter(191/xdmInitExternalStorageState)] 
I/DBG_POLICYDM( 3173): [com.policydm.agent.XDMTask(163/xdmAgentTaskHandler)] XEVENT_OS_INITIALIZED
I/DBG_POLICYDM( 3173): [com.policydm.adapter.XDMTargetAdapter(390/xdmGetExternalSDCardPath)] External SD Card Path : /storage/extSdCard
I/DBG_POLICYDM( 3173): [com.policydm.adapter.XDMTargetAdapter(248/xdmInitExternalStorageState)] DATA_DIR_PATH [/data]
I/DBG_POLICYDM( 3173): [com.policydm.adapter.XDMTargetAdapter(249/xdmInitExternalStorageState)] EXTERNAL_DIR_PATH [/storage/emulated/0]
I/MultiDex( 3196): VM with version 2.1.0 has multidex support
I/MultiDex( 3196): install
I/MultiDex( 3196): VM has multidex support, MultiDex support library is disabled.
E/Zygote  ( 3219): MountEmulatedStorage()
E/Zygote  ( 3219): v2
I/DBG_POLICYDM( 3173): [com.policydm.adapter.XDMTargetAdapter(250/xdmInitExternalStorageState)] EXTERNAL_SD_DIR_PATH [/storage/extSdCard]
I/libpersona( 3219): KNOX_SDCARD checking this for 10009
I/libpersona( 3219): KNOX_SDCARD not a persona
I/SELinux ( 3219): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1018): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=3219 uid=10009 gids={50009, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/DBG_POLICYDM( 3173): [com.policydm.adapter.XDMTargetAdapter(251/xdmInitExternalStorageState)] POLICY_DIR_PATH [/data/user/0/com.policydm/cache]
I/DBG_POLICYDM( 3173): [com.policydm.adapter.XDMTargetAdapter(253/xdmInitExternalStorageState)] bExternalStorageAvailable [true]
I/DBG_POLICYDM( 3173): [com.policydm.adapter.XDMTargetAdapter(254/xdmInitExternalStorageState)] bExternalSDStorageAvailable [false]
I/DBG_POLICYDM( 3173): [com.policydm.XDMApplication(580/xdmWakeLockRelease)] 
I/DBG_POLICYDM( 3173): [com.policydm.XDMApplication(585/xdmWakeLockRelease)] m_WakeLock is release!!
I/DBG_POLICYDM( 3173): [com.policydm.agent.XDMAgent(156/xdmAgentSetSyncMode)] nSync = 0
I/SELinux ( 3219): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/DBG_POLICYDM( 3173): [com.policydm.XDMApplication(179/onCreate)] DMApplication Start !
E/SELinux ( 3219): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
V/JNIHelp ( 3196): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
D/TimaKeyStoreProvider( 3219): TimaSignature is unavailable
D/ActivityThread( 3219): Added TimaKeyStore provider
I/DBG_POLICYDM( 3173): [com.policydm.db.XDB(1531/xdbDMffs_Init)] xdbDMffs_Init
I/DBG_DM  ( 3102): [com.wssyncmldm.db.file.XDB(1976/llIlIIIIlIIIIIlIlIII)] xdbDMffs_Init
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
I/ServiceManager(  338): Waiting for service AtCmdFwd...
E/Zygote  ( 3237): MountEmulatedStorage()
E/Zygote  ( 3237): v2
I/libpersona( 3237): KNOX_SDCARD checking this for 10003
I/libpersona( 3237): KNOX_SDCARD not a persona
I/SELinux ( 3237): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
W/ActivityThread( 3196): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 3196): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@6eeeaeb: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3196): Installed default security provider GmsCore_OpenSSL
I/ActivityManager( 1018): Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=3237 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a
I/SELinux ( 3237): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 3237): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 3237): TimaSignature is unavailable
D/ActivityThread( 3237): Added TimaKeyStore provider
V/audio_hw_primary(  287): adev_get_parameters: enter: keys - call_forwarding
D/audio_hw_extn(  287): audio_extn_get_parameters: returns 
V/msm8974_platform(  287): platform_get_parameters: exit: returns - 
V/audio_hw_primary(  287): adev_get_parameters: exit: returns - call_forwarding=false
I/str_params(  287): key: 'call_forwarding' value: ''
V/InCall  ( 1942): ProximitySensor -  - screenonImmediately: false
V/InCall  ( 1942): ProximitySensor -  - mFromRcsShare: false
I/InCall  ( 1942): ProximitySensor -  - ProximitySensor{keybrd=0, dpad=0, offhook=0, hor=0, ui=0, aud=EARPIECE}
D/ScoverManager( 1942): serviceVersion : 16908288
D/CoverManagerWhiteLists( 1018): isAllowedToUse : SIGNATURE_MATCH
D/InCall  ( 1942): InCallUtils - isCoverClosed false
I/Telecom ( 1442): ProximitySensorManager: Proximity wake lock already released
D/CoverManagerWhiteLists( 1018): isAllowedToUse : SIGNATURE_MATCH
D/InCall  ( 1942): InCallUtils - isCoverClosed false
I/InCall  ( 1942): InCallPresenter -  - InCallState = NO_CALLS
I/InCall  ( 1942): InCallPresenter -  - Phone switching state: NO_CALLS -> NO_CALLS
D/InCall  ( 1942): InCallPresenter -  - dismissCoverDialog()...
I/ActivityManager( 1018): Killing 2415:com.sec.android.app.camera/u0a139 (adj 15): empty #31
I/InCall  ( 1942): CallSContextMotion - stopPutDownListening
D/InCall  ( 1942): StatusBarNotifier - updateInCallNotification(allowFullScreenIntent = false)...
D/PhoneStatusBarView( 1188): setCallBackground:0
D/CoverManagerWhiteLists( 1018): isAllowedToUse : SIGNATURE_MATCH
D/InCall  ( 1942): InCallUtils - isCoverClosed false
D/AndroidRuntime( 3217): 
D/AndroidRuntime( 3217): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3217): CheckJNI is OFF
D/AndroidRuntime( 3217): readGMSProperty: start
D/AndroidRuntime( 3217): readGMSProperty: already setted!!
D/AndroidRuntime( 3217): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 3217): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 3217): readGMSProperty: end
D/AndroidRuntime( 3217): addProductProperty: start
W/libprocessgroup( 1018): failed to open /acct/uid_10139/pid_2415/cgroup.procs: No such file or directory
D/VideoCallManager( 1942): Instantiating VideoCallManager
E/        ( 1942): GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
I/GFX construct_block_size_descriptor_2d second part( 1942): took 2.237604ms for 0*0 texture 0
I/GFX generate_partition_tables( 1942): took 5.239792ms for 0*0 texture 0
I/GFX raster( 1942): took 11.321302ms for 176*144 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1942): Bitmap=0xb82611c8 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b0, Counterpart=0xb8260c28 counterpartCT=4 counterpartW=176 counterparth=144
E/        ( 1942): GFX convertToRaster() in Bitmap.cpp for bitmap size 320x240
I/Adreno-EGL( 1942): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 1942): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 1942): Build Date: 04/06/15 Mon
I/Adreno-EGL( 1942): Local Branch: 
I/Adreno-EGL( 1942): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 1942): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 1942):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
I/GFX GPU raster( 1942): eglCreateImageKHR: EGL_SUCCESS
I/glCompressedTexImage2D( 1942): took 0.429114ms for 320*61440 texture 37809
I/DBG_DM  ( 3102): [com.wssyncmldm.ui.IIllIllllIIlIlIIlIII(49/onServiceConnected)] 
E/Tethering( 1018): No numeric data
I/draw setup( 1942): took 11.039843ms for 320*240 texture 37809
E/GFX GPU raster( 1942): drawn
I/GFX GPU raster ASTC( 1942): took 41.363126ms for 320*240 texture 12
I/GFX raster( 1942): took 41.461251ms for 320*240 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1942): Bitmap=0xb8260c28 bitmapCt=12 bitmapW=320 bitmapH=240 BitmapInternalFormat=93b1, Counterpart=0xb8261340 counterpartCT=4 counterpartW=320 counterparth=240
E/Tethering( 1018): No numeric data
E/        ( 1942): GFX convertToRaster() in Bitmap.cpp for bitmap size 480x640
I/GFX GPU raster( 1942): eglCreateImageKHR: EGL_SUCCESS
E/Tethering( 1018): No numeric data
I/glCompressedTexImage2D( 1942): took 0.352656ms for 480*122880 texture 37813
I/draw setup( 1942): took 0.864583ms for 480*640 texture 37813
E/GFX GPU raster( 1942): drawn
I/GFX GPU raster ASTC( 1942): took 7.730103ms for 480*640 texture 12
I/GFX raster( 1942): took 7.792655ms for 480*640 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1942): Bitmap=0xb8492828 bitmapCt=12 bitmapW=480 bitmapH=640 BitmapInternalFormat=93b5, Counterpart=0xb8492680 counterpartCT=4 counterpartW=480 counterparth=640
E/SMD     (  304): DCD OFF
E/Tethering( 1018): No numeric data
E/Tethering( 1018): No numeric data
D/UserAnalysis.PlaceProvider( 3237): PlaceProvider onCreate()
E/Tethering( 1018): No numeric data
E/        ( 1942): GFX convertToRaster() in Bitmap.cpp for bitmap size 440x330
I/GFX GPU raster( 1942): eglCreateImageKHR: EGL_SUCCESS
I/glCompressedTexImage2D( 1942): took 0.316563ms for 440*116864 texture 37809
I/draw setup( 1942): took 0.738542ms for 440*330 texture 37809
E/GFX GPU raster( 1942): drawn
I/GFX GPU raster ASTC( 1942): took 4.288958ms for 440*330 texture 12
I/GFX raster( 1942): took 4.353854ms for 440*330 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1942): Bitmap=0xb84a2c88 bitmapCt=12 bitmapW=440 bitmapH=330 BitmapInternalFormat=93b1, Counterpart=0xb84b7360 counterpartCT=4 counterpartW=440 counterparth=330
E/AffinityControl( 3217): AffinityControl: registerfunction enter
E/        ( 1942): GFX convertToRaster() in Bitmap.cpp for bitmap size 480x640
I/GFX GPU raster( 1942): eglCreateImageKHR: EGL_SUCCESS
D/AndroidRuntime( 3217): Calling main entry com.android.commands.am.Am
I/glCompressedTexImage2D( 1942): took 0.687969ms for 480*163840 texture 37811
I/draw setup( 1942): took 1.237083ms for 480*640 texture 37811
E/GFX GPU raster( 1942): drawn
E/PersonaManagerService( 1018): inState():  stateMachine is null !!
I/PersonaManagerService( 1018): PersonaId don't exist
I/ActivityManager( 1018): do not start freezing screen for locked container getKeyguardshowstate = false
I/GFX GPU raster ASTC( 1942): took 6.437554ms for 480*640 texture 12
I/GFX raster( 1942): took 6.504585ms for 480*640 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1942): Bitmap=0xb84a2c28 bitmapCt=12 bitmapW=480 bitmapH=640 BitmapInternalFormat=93b3, Counterpart=0xb848e3b8 counterpartCT=4 counterpartW=480 counterparth=640
D/UserAnalysis.SecureDbManager( 3237): Key for secure DB is newly created
D/UserAnalysis.SecurePlaceDbHelper( 3237): SecurePlaceDbHelper() 
D/UserAnalysis( 3237): Create SecureDbHelper
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/[SBeam] ( 1383): SBeamEnabler.isSBeamSupported : [-1]
D/[SBeam] ( 1383): SBeamEnabler.isSBeamSupported : EXIST
D/CustomFrequencyManagerService( 1018): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  pkgName : ACTIVITY_RESUME_BOOSTER@7
W/ActivityManager( 1018): mDVFSHelper.acquire()
D/FocusedStackFrame( 1018): Set to : 0
D/Launcher.HomeView( 1497): onPause
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/InputDispatcher( 1018): Focused application set to: xxxx
D/InputDispatcher( 1018): Focus left window: 1497
D/Launcher( 1497): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
D/AndroidRuntime( 3217): Shutting down VM
D/PhoneWindow( 1018): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 1018): *FMB* installDecor flags : -2122120936
D/IntelligenceServiceApplication( 3237): onCreate()
D/UserAnalysis.UserAnalysisBroadcastReceiver( 3237): Intent(action: android.intent.action.BOOT_COMPLETED) is received.
D/PointerIcon( 1018): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1018): setMouseCustomIcon IconType is same.101
D/PhoneWindow( 1018): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1018): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  258): id=10 createSurf (1x1),1 flag=404, uhalitest
E/Tethering( 1018): No numeric data
E/        ( 1942): GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
E/Tethering( 1018): No numeric data
I/GFX construct_block_size_descriptor_2d second part( 1942): took 2.040781ms for 0*0 texture 0
E/Tethering( 1018): No numeric data
I/GFX generate_partition_tables( 1942): took 7.442552ms for 0*0 texture 0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
I/GFX raster( 1942): took 11.450052ms for 176*144 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1942): Bitmap=0xb848e3b8 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b2, Counterpart=0xb8261340 counterpartCT=4 counterpartW=176 counterparth=144
E/Tethering( 1018): No numeric data
E/        ( 1942): GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
I/GFX construct_block_size_descriptor_2d second part( 1942): took 2.153906ms for 0*0 texture 0
E/Zygote  ( 3272): MountEmulatedStorage()
E/Zygote  ( 3272): v2
I/libpersona( 3272): KNOX_SDCARD checking this for 10174
I/libpersona( 3272): KNOX_SDCARD not a persona
I/SELinux ( 3272): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
V/EmergencyMode( 1428): [EmergencyBase] setBootTime
D/IntelligenceServiceApplication( 3237): no applications having user consent for prediction
V/EmergencyMode( 1428): [EmergencyFactory] No Recovery State, kill my self.
I/SELinux ( 3272): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 3272): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1018): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3272 uid=10174 gids={50174, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/GFX generate_partition_tables( 1942): took 6.109948ms for 0*0 texture 0
I/GFX raster( 1942): took 10.364323ms for 176*144 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1942): Bitmap=0xb8261340 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b1, Counterpart=0xb84b7390 counterpartCT=4 counterpartW=176 counterparth=144
D/ScoverManager( 1942): registerListener
D/CoverManagerWhiteLists( 1018): isAllowedToUse : SIGNATURE_MATCH
I/DBG_POLICYDM( 3173): [com.policydm.agent.XDMTask(171/xdmAgentTaskHandler)] XEVENT_DM_INIT
D/CoverManagerWhiteLists( 1018): isAllowedToUse : SIGNATURE_MATCH
D/CoverManager.StateNotifier( 1018): registerListenerCallback : binder = android.os.BinderProxy@2caf78c9, pid : 1942, uid : 1001, type : 1
I/DBG_POLICYDM( 3173): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
I/DBG_DM  ( 3102): [IlIIlIIlIllllIlllIII(191/llIIIIlllllIIllIIllI)] XEVENT_PHONEBOOK_INITIALIZED
V/ActivityThread( 1497): updateVisibility : ActivityRecord{2f02caa9 token=android.os.BinderProxy@10c264f8 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
E/Zygote  ( 3287): MountEmulatedStorage()
E/Zygote  ( 3287): v2
I/libpersona( 3287): KNOX_SDCARD checking this for 10060
I/libpersona( 3287): KNOX_SDCARD not a persona
I/SELinux ( 3287): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 3287): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/ActivityManager( 1018): Start proc com.samsung.android.scloud.backup for broadcast com.samsung.android.scloud.backup/.SCloudBackupReceiver: pid=3287 uid=10060 gids={50060, 9997, 1028, 1015, 3003} abi=armeabi-v7a
E/SELinux ( 3287): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/DBG_DM  ( 3102): [com.wssyncmldm.db.file.XDB(3660/lllIIIIllIlIlllllllI)] FUMO_Status : 220
I/ActivityManager( 1018): Killing 1718:com.google.android.partnersetup/u0a15 (adj 15): empty #31
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
V/PlaceDetection v1.0.19 ( 3237): [PlaceDetection::stopService] Service stopped.
D/InCall  ( 1942): InCallPresenter -  - Finished InCallPresenter.setUp
I/DBG_POLICYDM( 3173): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
I/DBG_POLICYDM( 3173): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
I/DBG_POLICYDM( 3173): [com.policydm.XDMApplication(619/xdmGetNotibarState)] get NotibarState : 7
I/DBG_DM  ( 3102): [com.wssyncmldm.XDMService(1377/llllIIIllIlIIIIllllI)] wssGetUpdateReport : 0
V/VibratorService( 1018): hasVibrator - useVibetonz: true
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
I/DBG_POLICYDM( 3173): [com.policydm.ui.XUINotificationManager(48/xuiSetIndicator)] Indicator id : 7
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
D/TimaKeyStoreProvider( 3272): TimaSignature is unavailable
I/DBG_DM  ( 3102): [IlIIlIIlIllllIlllIII(217/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT
D/ActivityThread( 3272): Added TimaKeyStore provider
I/DBG_POLICYDM( 3173): [com.policydm.XDMApplication(611/xdmSetNotibarState)] set NotibarState : 7
D/TimaKeyStoreProvider( 3287): TimaSignature is unavailable
E/Zygote  ( 3305): MountEmulatedStorage()
E/Zygote  ( 3305): v2
I/SELinux ( 3305): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/libpersona( 3305): KNOX_SDCARD checking this for 1000
I/libpersona( 3305): KNOX_SDCARD not a persona
I/ActivityManager( 1018): Start proc com.sec.factory.camera for broadcast com.sec.factory.camera/com.sec.android.app.camerafirmware.CameraFirmwareBroadCastReceiver: pid=3305 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
D/Finsky  ( 3137): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
I/SELinux ( 3305): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
D/ActivityThread( 3287): Added TimaKeyStore provider
E/SELinux ( 3305): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
V/PlaceDetection v1.0.19 ( 3237): [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
D/UserAnalysis.MyPlaceDbPreference( 3237): Constructor Preference
V/WindowOrientationListener( 1018): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
V/WindowManager( 1018): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener( 1018): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
D/Launcher.HomeView( 1497): onStop
V/ActivityThread( 1497): updateVisibility : ActivityRecord{2f02caa9 token=android.os.BinderProxy@10c264f8 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
I/DBG_POLICYDM( 3173): [com.policydm.db.XDBAESCrypt(217/xdbGetCryptionkey)] try read dbString
D/StatusBarManagerService( 1018): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/TimaKeyStoreProvider( 3305): TimaSignature is unavailable
D/PersonaManager( 1018): isKioskContainerExistOnDevice
D/ActivityThread( 3305): Added TimaKeyStore provider
I/DBG_POLICYDM( 3173): [com.policydm.db.XDBFumoAdp(428/xdbGetFUMOStatus)] xdbGetFUMOStatus : 0
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
W/art     ( 3217): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
I/DBG_POLICYDM( 3173): [com.policydm.db.XDBFumoAdp(587/xdbGetFUMOInitiatedType)] Initiated Type: 0
,W/libprocessgroup( 1018): failed to open /acct/uid_10015/pid_1718/cgroup.procs: No such file or directory
,I/GAV2    ( 2673): Thread[GAThread,5,main]: No campaign data found.
,W/NotificationAccessSettings( 1383): Skipping notification listener service com.android.settings/com.android.settings.accessibility.notificationreminder.NotificationReminderService: it does not require the permission android.permission.BIND_NOTIFICATION_LISTENER_SERVICE
,I/DBG_POLICYDM( 3173): [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,D/WindowOrientationListener( 1018):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
,D/SensorService( 1018): [SO] activate (ident=0xb8a0c9c0, enabled=0)
I/Sensors ( 1018): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,V/VibratorService( 1018): hasVibrator - useVibetonz: true
,D/SensorManager( 1018): unregisterListener ::   
D/Launcher( 1497): onTrimMemory. Level: 20
,I/Sensors ( 1018): AccelerometerSensor(0) setDelay : 66000000(ns)
,V/VibratorService( 1018): hasVibrator - useVibetonz: true
,D/SensorService( 1018): [SO] changed settle time [1]
I/DBG_POLICYDM( 3173): [com.policydm.polling.XPollingAgent(72/xpollingCheckVersionInfo)] 
I/DBG_POLICYDM( 3173): [com.policydm.agent.XDMUITask(191/xdmUIEvent)] XUI_DM_IDLE_STATE :true
D/SensorService( 1018): [SO] setDelay [66000000]
D/SensorService( 1018): [SO] activate (ident=0xb8a0c9c0, enabled=1)
I/GAv4-SVC( 1882): Google Analytics 7.8.99 is starting up.
,D/SensorService( 1018): [SO] AR_init
I/Sensors ( 1018): AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,D/SensorManager( 1018): registerListener :: 1600221811, Screen Orientation Sensor, 66000, 0,  
,I/DBG_POLICYDM( 3173): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 3173): [com.policydm.polling.XPollingAgent(271/xpollingCheckTimer)] 
,I/DBG_POLICYDM( 3173): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 3173): [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,I/DBG_POLICYDM( 3173): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,W/ResourcesManager( 1383): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/DBG_POLICYDM( 3173): [com.policydm.db.XDBProfileListAdp(258/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,I/DBG_POLICYDM( 3173): [com.policydm.noti.XNOTIAdapter(399/xnotiPushAdpExcuteResumeNoti)] nSessionSaveState:0
I/DBG_POLICYDM( 3173): [com.policydm.polling.XPollingAgent(285/xpollingCheckTimer)] savedpollingtime : 2016/03/25/13:36:09
,I/DBG_POLICYDM( 3173): [com.policydm.polling.XPollingAgent(286/xpollingCheckTimer)] currentTime : 2016/03/18/17:15:31
,I/DBG_POLICYDM( 3173): [com.policydm.noti.XNOTIAdapter(400/xnotiPushAdpExcuteResumeNoti)] nNotiUiEvent:0
,I/DBG_POLICYDM( 3173): [com.policydm.polling.XPollingAgent(290/xpollingCheckTimer)] Restart Timer..
,I/DBG_POLICYDM( 3173): [com.policydm.XDMApplication(626/xdmStartAlarm)] Alarm ID: 0
,D/SensorService( 1018): [SO] Reset Rotation Old [100], Init [1]
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/DBG_POLICYDM( 3173): [com.policydm.noti.XNOTIAdapter(401/xnotiPushAdpExcuteResumeNoti)] nNotiRetryCount:0
,I/DBG_POLICYDM( 3173): [com.policydm.noti.XNOTIAdapter(441/xnotiPushAdpExcuteResumeNoti)] Current NOTI NOT SAVED State. EXIT.
,I/DBG_POLICYDM( 3173): [com.policydm.noti.XNOTIAdapter(267/xnotiPushAdpClearSessionStatus)] 
I/DBG_POLICYDM( 3173): [com.policydm.ui.XUIAdapter(39/xuiAdpSetUiMode)] nDmUiMode : 0
I/WebViewFactory( 3272): Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
I/DBG_POLICYDM( 3173): [com.policydm.db.XDBFumoAdp(439/xdbSetFUMOStatus)] xdbSetFUMOStatus : 0
I/ActivityManager( 1018): Start proc com.fmm.dm for broadcast com.fmm.dm/.XDMBroadcastReceiver: pid=3332 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/Zygote  ( 3332): MountEmulatedStorage()
I/libpersona( 3332): KNOX_SDCARD checking this for 1000
E/Zygote  ( 3332): v2
I/libpersona( 3332): KNOX_SDCARD not a persona
I/SELinux ( 3332): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1018): Killing 2504:com.sec.android.omc/1000 (adj 15): empty #31
I/ActivityManager( 1018): Killing 2494:com.sec.modem.settings/1000 (adj 15): empty #32,
I/ActivityManager( 1018): Killing 2469:com.sec.android.app.SecSetupWizard/1000 (adj 15): empty #33,
,I/SELinux ( 3332): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3332): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/CameraApp( 3305): CameraApp.onCreate()... mFeature : null
I/testFeature( 3305): Feature.Feature(context)
I/testFeature( 3305): Feature.readInternalDefaultXml()
I/testFeature( 3305): ResetFeatureValue
,I/CameraFirmware_broadcast( 3305): CameraFirmwareBroadCastReceiver...
I/CameraApp( 3305): CameraApp.getAppFeature()...
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,D/SensorService( 1018): [SO] currT = 37581175000, prevT = 37241098000, diff = 340077000, [0.172 0.421 10.247]
,D/SensorService( 1018): [SO] 0.172 0.421 10.247
D/SensorService( 1018): [SO] [100 -> 255]
,I/DBG_POLICYDM( 3173): [com.policydm.polling.XPollingAgent(312/xPollingReportReStartAlarm)] 
,I/LibraryLoader( 3272): Time to load native libraries: 2 ms (timestamps 7592-7594)
I/LibraryLoader( 3272): Expected native library version number "",actual native library version number ""
,E/Zygote  ( 3347): MountEmulatedStorage()
I/libpersona( 3347): KNOX_SDCARD checking this for 10100
E/Zygote  ( 3347): v2
I/libpersona( 3347): KNOX_SDCARD not a persona
I/ActivityManager( 1018): Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=3347 uid=10100 gids={50100, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,I/SELinux ( 3347): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 3347): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3347): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 3332): TimaSignature is unavailable
,D/ActivityThread( 3332): Added TimaKeyStore provider
I/ActivityManager( 1018): Killing 2520:com.wsomacp/u0a25 (adj 15): empty #31
,I/DBG_POLICYDM( 3173): [com.policydm.db.XDBFumoAdp(565/xdbSetFUMOInitiatedType)] Initiated Type: 0
,D/ScoverManager( 1383): serviceVersion : 16908288
,V/WebViewChromiumFactoryProvider( 3272): Binding Chromium to main looper Looper (main, tid 1) {15bfbf07}
,D/TimaKeyStoreProvider( 3347): TimaSignature is unavailable
I/LibraryLoader( 3272): Expected native library version number "",actual native library version number ""
D/ActivityThread( 3347): Added TimaKeyStore provider
I/chromium( 3272): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3272): Initializing chromium process, singleProcess=true
,W/art     ( 3272): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3272): ApplicationContext is null in ApplicationStatus
,D/PackageIntentReceiver( 3347): ACTION_BOOT_COMPLETED
D/PackageIntentReceiver( 3347): jangil::ACTION_BOOT_COMPLETED::do not need pkg remove..
I/ActivityManager( 1018): Killing 2539:com.sec.android.app.sbrowser/u0a131 (adj 15): empty #31
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.syncadapters.contacts/com.google.android.syncadapters.contacts.ContactsSyncAdapterIntentService; callingUser = 0; userId(target) = 0
,W/chromium( 3272): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.process.gapps
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/GoogleHttpClient( 1681): GMS http client unavailable, use old client
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_2469/cgroup.procs: No such file or directory
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_2494/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_2504/cgroup.procs: No such file or directory
,E/libEGL  ( 3272): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3272): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 3272): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 3272): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 3272): Build Date: 04/06/15 Mon
I/Adreno-EGL( 3272): Local Branch: 
I/Adreno-EGL( 3272): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 3272): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 3272):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,E/Zygote  ( 3382): MountEmulatedStorage()
E/Zygote  ( 3382): v2
I/libpersona( 3382): KNOX_SDCARD checking this for 1000
I/libpersona( 3382): KNOX_SDCARD not a persona
,I/SELinux ( 3382): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/ActivityManager( 1018): Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.BootBroadcastReceiver: pid=3382 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/DBG_POLICYDM( 3173): [com.policydm.db.XDB(1825/xdbSetBackUpServerUrl)] ,
,I/SELinux ( 3382): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,E/SELinux ( 3382): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,I/DBG_FMMDM( 3332): [50.20.150420][Line:608][xdmGetCheckWifiOnlyModel] isWifiOnly : false
,I/DBG_POLICYDM( 3173): [com.policydm.XDMApplication(626/xdmStartAlarm)] Alarm ID: 1
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,I/DBG_POLICYDM( 3173): [com.policydm.agent.XDMTask(203/xdmAgentTaskHandler)] XEVENT_DM_INIT : Initialized
,D/Finsky  ( 3137): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,I/DBG_FMMDM( 3332): [50.20.150420][Line:27][xdmInitialize] AgVOOqV7UpXFblBk29Ld3aZrOQhtHCYbjdszx6nYrjFYzeVOvvlPUzE67GnQVups
,I/DBG_FMMDM( 3332): [50.20.150420][Line:28][xdmInitialize] c8aaBoNX+zCI65M7gVNTej45+K/MzxjqVpKd5x0FMtd3o63nokSujfTEanrHiU41
,I/DBG_FMMDM( 3332): [50.20.150420][Line:29][xdmInitialize] X2Nl5mgTWVn0/a90MNBgtYshxOiQq2MqI4oMf2Nwz6I=
,D/TimaKeyStoreProvider( 3382): TimaSignature is unavailable
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,D/ActivityThread( 3382): Added TimaKeyStore provider
,E/Zygote  ( 3407): MountEmulatedStorage()
,E/Zygote  ( 3407): v2
I/libpersona( 3407): KNOX_SDCARD checking this for 1000
I/libpersona( 3407): KNOX_SDCARD not a persona
,I/SELinux ( 3407): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,I/ActivityManager( 1018): Start proc com.sec.pcw.device for content provider com.sec.pcw.device/.contentprovider.DMProvider: pid=3407 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
I/SELinux ( 3407): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 3407): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/dhcpcd  ( 2203): wlan0: sending IPv6 Router Solicitation
I/dhcpcd  ( 2203): wlan0: no IPv6 Routers available
W/libprocessgroup( 1018): failed to open /acct/uid_10025/pid_2520/cgroup.procs: No such file or directory
,W/libprocessgroup( 1018): failed to open /acct/uid_10131/pid_2539/cgroup.procs: No such file or directory
,I/SurfaceFlinger(  258): id=8 Removed Mauncher (5/8)
I/SurfaceFlinger(  258): id=8 Removed Mauncher (-2/8)
,I/art     ( 1018): Explicit concurrent mark sweep GC freed 31933(1607KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 26MB/40MB, paused 3.603ms total 170.799ms
,D/TimaKeyStoreProvider( 3407): TimaSignature is unavailable
,D/ActivityThread( 3407): Added TimaKeyStore provider
,I/sCloudBackupApp( 3287): sCloudBackupApp Version Info : 4.04.8.KK_APP
,I/LockPatternUtils( 1383): isSmartCardAuthenticationAvailable: false
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/PCWCLIENTTRACE_LOG( 3407): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG( 3407): DEFAULT_LOGLEVEL : 3
,D/Settings_Utils( 1383): isSupportVNFestival SM-A500FU XEO
,E/Zygote  ( 3425): MountEmulatedStorage()
,E/Zygote  ( 3425): v2
I/libpersona( 3425): KNOX_SDCARD checking this for 10062
I/libpersona( 3425): KNOX_SDCARD not a persona
,I/SELinux ( 3425): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,I/SELinux ( 3425): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,I/ActivityManager( 1018): Start proc com.samsung.android.scloud.sync for broadcast com.samsung.android.scloud.sync/com.sec.android.sCloudSync.Receivers.TimeChangedReceiver: pid=3425 uid=10062 gids={50062, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1018): Killing 2552:com.sec.tcpdumpservice/1000 (adj 15): empty #31
,E/SELinux ( 3425): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 3425): TimaSignature is unavailable
,D/ActivityThread( 3425): Added TimaKeyStore provider
,I/PCWCLIENTTRACE_DMDBOpenHelper( 3407): new DMDBOpenHelper instance
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_2552/cgroup.procs: No such file or directory
,D/PCWCLIENTTRACE_DMContentProvider( 3407): [URIMatcher] - result : 2
,I/DBG_FMMDM( 3332): [50.20.150420][Line:40][onCreate] FMMApplication NOT Start !
,I/DBG_FMMDM( 3332): [50.20.150420][Line:67][onReceive] android.intent.action.BOOT_COMPLETED
,I/DBG_FMMDM( 3332): [50.20.150420][Line:309][onReceive] android.intent.action.BOOT_COMPLETED
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3446): MountEmulatedStorage()
,E/Zygote  ( 3446): v2
I/libpersona( 3446): KNOX_SDCARD checking this for 1000
I/libpersona( 3446): KNOX_SDCARD not a persona
I/ActivityManager( 1018): Start proc com.fmm.ds for broadcast com.fmm.ds/.XDSBroadcastReceiver: pid=3446 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/ActivityManager( 1018): Killing 2460:com.sec.android.app.mt/1000 (adj 15): empty #31
I/SELinux ( 3446): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 3446): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3446): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/art     ( 3272): Attempt to remove local handle scope entry from IRT, ignoring
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/art     (  323): Explicit concurrent mark sweep GC freed 8780(373KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 663us total 22.334ms
,D/TimaKeyStoreProvider( 3446): TimaSignature is unavailable
D/ActivityThread( 3446): Added TimaKeyStore provider
,I/ExternalOEMControlProvider( 3425): onCreate
,I/art     (  323): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 612us total 16.987ms
,W/AwContents( 3272): onDetachedFromWindow called when already detached. Ignoring
,I/art     (  323): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 622us total 16.753ms
,D/PhoneWindow( 3272): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 3272): *FMB* installDecor flags : -2139027200
,D/SystemWebViewEngine( 3272): CordovaWebView is running on device made by: samsung
,I/DBG_POLICYDM( 3173): [com.policydm.db.XDBProfileAdp(207/xdbSetChangedProtocol)] xdbSetChangedProtocol : false
,W/Settings( 3137): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/Zygote  ( 3462): MountEmulatedStorage()
E/Zygote  ( 3462): v2
I/libpersona( 3462): KNOX_SDCARD checking this for 1000
I/libpersona( 3462): KNOX_SDCARD not a persona
,I/SELinux ( 3462): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 3462): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3462): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1018): Start proc com.sec.knox.foldercontainer for broadcast com.sec.knox.foldercontainer/.ShortcutReceiver: pid=3462 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/ActivityManager( 1018): Killing 2602:com.samsung.android.securitylogagent/1000 (adj 15): empty #31
,W/Settings( 3137): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/art     ( 3272): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3272): Attempt to remove local handle scope entry from IRT, ignoring
,D/TimaKeyStoreProvider( 3462): TimaSignature is unavailable
,D/ActivityThread( 3462): Added TimaKeyStore provider
W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 com.android.server.ssrm.ad.ec:-1 com.android.server.ssrm.ae.handleMessage:-1 android.os.Handler.dispatchMessage:102 android.os.Looper.loop:145 
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/DBG_POLICYDM( 3173): [com.policydm.db.XDBProfileListAdp(258/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,E/Zygote  ( 3482): MountEmulatedStorage()
,I/DBG_POLICYDM( 3173): [com.policydm.db.XDBNotiAdp(38/xdbNotiExistInfo)] Noti Exist : false
E/Zygote  ( 3482): v2
I/libpersona( 3482): KNOX_SDCARD checking this for 1000
I/libpersona( 3482): KNOX_SDCARD not a persona
,I/SELinux ( 3482): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 3482): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3482): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1018): Start proc com.sec.android.app.servicemodeapp for broadcast com.sec.android.app.servicemodeapp/.ServiceModeAppBroadcastReceiver: pid=3482 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/ActivityManager( 1018): Killing 2617:com.android.calendar/u0a135 (adj 15): empty #31
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_2460/cgroup.procs: No such file or directory
,D/SettingsProvider( 1018): name = PREVIOUS_SYS_TIME
D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 10062
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
,D/TimaKeyStoreProvider( 3482): TimaSignature is unavailable
,D/ActivityThread( 3482): Added TimaKeyStore provider
,W/ResourcesManager( 3482): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,V/VibratorService( 1018): hasVibrator - useVibetonz: true
D/OpenGLRenderer( 3272): Render dirty regions requested: true
,D/ActivityManager( 1018): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1018): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1018): postActiveUserChange, showWhenLocked: false
,D/KnoxTimeoutHandler( 1018): handleActiveUserChange for user 0
D/PersonaManagerService( 1018): getPersonasForUser(): returning null!
,W/chromium( 3272): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,D/PhoneWindow( 3272): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
,D/PhoneWindow( 3272): *FMB* isFloatingMenuEnabled return false
,I/DBG_FMMDS( 3446): [50.18.150420][Line:56][onCreate] FMMDS Application Start
,I/DBG_FMMDS( 3446): [50.18.150420][Line:28][<init>] XDBHelper First Call!!!
,I/SurfaceFlinger(  258): id=11 createSurf (1x1),1 flag=404, NainActivit
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_2602/cgroup.procs: No such file or directory
,W/libprocessgroup( 1018): failed to open /acct/uid_10135/pid_2617/cgroup.procs: No such file or directory
,D/PCWCLIENTTRACE_DMContentProvider( 3407): [URIMatcher] - result : 2
,D/InputDispatcher( 1018): Focus entered window: 3272
,E/DBG_FMMDS( 3446): Warning!!! [50.18.150420][Line:36][xdsDevAdpGetDeviceID] DeviceID read fail!!!!!!!!
,D/StatusBar.NetworkController( 1188): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1188): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1188): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1188): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1188): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1188): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/DBG_FMMDS( 3446): [50.18.150420][Line:43][xdbDBInit] 
,D/PointerIcon( 1018): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1018): setMouseCustomIcon IconType is same.101
,D/SRIB_DCS( 3272): log_dcs ThreadedRenderer::initialize entered! 
,I/OpenGLRenderer( 3272): Initialized EGL, version 1.4
,I/ServiceMode( 3482): received = ACTION_BOOT_COMPLETED
,I/ServiceMode( 3482): setReferenceIsDumpState : 0
,D/KnoxSetupWizardDbHelper( 3462): dbMigrationFlag : false
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
D/OpenGLRenderer( 3272): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
D/OpenGLRenderer( 3272): Enabling debug mode 0
,I/DBG_DM  ( 3102): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 0 sec
,E/Zygote  ( 3502): MountEmulatedStorage()
E/Zygote  ( 3502): v2
I/libpersona( 3502): KNOX_SDCARD checking this for 1000
I/libpersona( 3502): KNOX_SDCARD not a persona
,I/SELinux ( 3502): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 3502): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3502): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1018): Start proc com.wssnps for broadcast com.wssnps/.smlNpsReceiverDefault: pid=3502 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/TimaKeyStoreProvider( 3502): TimaSignature is unavailable
,D/ActivityThread( 3502): Added TimaKeyStore provider
,D/Volley  ( 3137): [381] DiskBasedCache.clear: Cache cleared.
,D/Volley  ( 3137): [388] DiskBasedCache.clear: Cache cleared.
,I/ActivityManager( 1018): Killing 2693:com.android.keychain/1000 (adj 15): empty #31
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.playlog.service.MonitorService; callingUser = 0; userId(target) = 0
,D/InputMethodManagerService( 1018): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,V/GLSUser ( 1681): [LoginAccountsChangedWakefulBroadcastReceiver] recieved broadcast intent with action: android.intent.action.BOOT_COMPLETED
,D/PanelView( 1188): There is/are notification(s) 
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.change.LoginAccountsChangedIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1018): Displayed Component not be shown by security: +1s271ms
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/Timeline( 3272): Timeline: Activity_idle id: android.os.BinderProxy@3b0cbcc9 time:38467
,D/CustomFrequencyManagerService( 1018): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  tag : ACTIVITY_RESUME_BOOSTER@7
,W/ActivityManager( 1018): mDVFSHelper.release()
I/Timeline( 1018): Timeline: Activity_windows_visible id: ActivityRecord{10854891 u0 com.test.thalitest/.MainActivity t236} time:38475
,D/CustomFrequencyManagerService( 1018): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  pkgName : ACTIVITY_RESUME_BOOSTER@11
,V/GmsCoreStatsServiceLauncher( 1882): Received broadcast intent Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher (has extras) }
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,I/SamsungIME( 1796): getCurrentCandidateView
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_2693/cgroup.procs: No such file or directory
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/NPS_WSSNPS( 3502): [] android.intent.action.BOOT_COMPLETED
,W/ContextImpl( 3502): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.wssnps.smlNpsReceiverDefault.onReceive:35 android.app.ActivityThread.handleReceiver:3125 
,D/PersistentNotificationBroadcastReceiver( 1681): Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.wssnps/com.wssnps.smlNpsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.wssnps, destAppInfo.processName = com.wssnps
,D/NPS_WSSNPS( 3502): [] Service onCreate!!
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3526): MountEmulatedStorage()
,I/libpersona( 3526): KNOX_SDCARD checking this for 1000
E/Zygote  ( 3526): v2
I/libpersona( 3526): KNOX_SDCARD not a persona
,I/ActivityManager( 1018): Start proc com.samsung.android.app.accesscontrol for broadcast com.samsung.android.app.accesscontrol/.AccessControlReceiver: pid=3526 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/SELinux ( 3526): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 3526): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3526): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
W/BackupManagerService( 1018): dataChanged but no participant pkg='com.android.providers.settings' uid=10062
,D/SettingsProvider( 1018): name = PREVIOUS_ELAPSED_TIME
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.billing.iab.PendingNotificationsService; callingUser = 0; userId(target) = 0
D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 10062
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,D/ShortcutReceiver( 3462):  ShortcutReceiver onReceive() intent: android.intent.action.BOOT_COMPLETED
,I/SecKeyguardClockSingleView( 1188): Ignore. Because it is same clock text
,D/NPS_WSSNPS( 3502): [50.150321] NpsServiceTask Start
,D/KnoxShortcutUtil( 3462): getIsShortcutMigrationFor_2_3_0_Done true
,D/ShortcutReceiver( 3462):  KnoxContainerVersion 2.4.0
D/ShortcutReceiver( 3462):  shortcut migration not required 
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,D/NPS_WSSNPS( 3502): [50.150321] smlDBHelper
,D/TimaKeyStoreProvider( 3526): TimaSignature is unavailable
,D/ActivityThread( 3526): Added TimaKeyStore provider
,I/LockPatternUtils( 1383): isSmartCardAuthenticationAvailable: false
D/Finsky  ( 3137): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 3137): [1] 2.run: Finished loading 1 libraries.
,E/Zygote  ( 3545): MountEmulatedStorage()
E/Zygote  ( 3545): v2
I/libpersona( 3545): KNOX_SDCARD checking this for 1000
I/libpersona( 3545): KNOX_SDCARD not a persona
I/SELinux ( 3545): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 3545): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3545): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/BackupManagerService( 1018): dataChanged but no participant pkg='com.android.providers.settings' uid=10062
,I/ActivityManager( 1018): Start proc com.sec.knox.knoxsetupwizardclient for broadcast com.sec.knox.knoxsetupwizardclient/.detector.SetupWizardDetectorReceiver: pid=3545 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/SecKeyguardClockSingleView( 1188): Ignore. Because it is same clock text
,D/TimaKeyStoreProvider( 3545): TimaSignature is unavailable
,D/ActivityThread( 3545): Added TimaKeyStore provider
,I/NPS_WSSNPS( 3502): [50.150321] AsyncBulkFlagCheck
,I/NPS_WSSNPS( 3502): [50.150321] IsRemain_AsyncBulkCheck
,D/SamsungIME( 1796): Dismiss ExpandCandiate
,I/NPS_WSSNPS( 3502): [50.150321] IsRemain_Asyncing nothing
W/ContextImpl( 3502): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:2069 android.content.ContextWrapper.stopService:538 com.wssnps.h.run:107 java.util.Timer$TimerImpl.run:284 <bottom of call stack> 
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.wssnps/com.wssnps.smlNpsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.wssnps, destAppInfo.processName = com.wssnps
,D/NPS_WSSNPS( 3502): [50.150321] Service onDestroy
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/NPS_WSSNPS( 3502): [50.150321] smlBRConfigurationDelete
,I/NPS_WSSNPS( 3502): [50.150321] smlBRMessageDelete
I/NPS_WSSNPS( 3502): [50.150321] smlBREmailDelete
I/NPS_WSSNPS( 3502): [50.150321] smlBRNetworkDelete
I/NPS_WSSNPS( 3502): [50.150321] smlBRCallLogDelete
I/NPS_WSSNPS( 3502): [50.150321] smlBRMiniDiaryDelete
I/NPS_WSSNPS( 3502): [50.150321] smlBRPenMemoMDelete
I/NPS_WSSNPS( 3502): [50.150321] smlBRSMemoDelete
I/NPS_WSSNPS( 3502): [50.150321] cpuBooster release : false
,D/NPS_WSSNPS( 3502): [50.150321] dsServerSocket close
,I/ActivityManager( 1018): Killing 2776:com.android.email/u0a145 (adj 15): empty #31
,I/ActivityManager( 1018): Killing 2368:com.sec.android.gallery3d/u0a44 (adj 15): empty #31
,I/SurfaceFlinger(  258): id=10 Removed uhalitest (7/8)
,I/DBG_FMMDS( 3446): [50.18.150420][Line:63][onCreate] onCreate Db Initialized
,E/KnoxSetupWizardClient( 3545): isShipMode : 1
I/KnoxSetupWizardClient( 3545): onReceive : android.intent.action.BOOT_COMPLETED
,I/SamsungIME( 1796): getDebugLevel  : 0x4f4c,
,I/DBG_FMMDS( 3446): [50.18.150420][Line:363][xdsGetAccount] UZnlD2ITkPmcCbh9srjpN/1auPpXZ1U0673eFrlr5G7ujCmOnoTUvn8Wy3q3+o8W
,I/DBG_FMMDS( 3446): [50.18.150420][Line:279][xdsDefaultProfileCheckServerID] VG44Fy9kdMk+/k3D4uP4d3do/3rw5AoymvTy0wXAnzc=
,D/Finsky  ( 3137): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,W/Atfwd_Sendcmd(  338): AtCmdFwd service not published, waiting... retryCnt : 3
,I/DBG_FMMDS( 3446): [50.18.150420][Line:363][xdsGetAccount] UZnlD2ITkPmcCbh9srjpN/1auPpXZ1U0673eFrlr5G7ujCmOnoTUvn8Wy3q3+o8W
,I/DBG_FMMDS( 3446): [50.18.150420][Line:376][xdsCheckSamsungAccountForChina] VG44Fy9kdMk+/k3D4uP4d3do/3rw5AoymvTy0wXAnzc=
,I/DBG_FMMDS( 3446): [50.18.150420][Line:89][onReceive] Receive Intent : android.intent.action.BOOT_COMPLETED
D/CustomFrequencyManagerService( 1018): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  tag : ACTIVITY_RESUME_BOOSTER@11
,I/DBG_FMMDS( 3446): [50.18.150420][Line:248][onReceive] XCOMMON_INTENT_NOTI_CALLLOG_CLICK
,W/InstanceID/Rpc( 1882): Found 10012
,E/Zygote  ( 3574): MountEmulatedStorage()
E/Zygote  ( 3574): v2
I/libpersona( 3574): KNOX_SDCARD checking this for 1000
I/libpersona( 3574): KNOX_SDCARD not a persona
,I/SELinux ( 3574): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/ActivityManager( 1018): Start proc com.sec.android.app.mt for broadcast com.sec.android.app.mt/.StatusChecker: pid=3574 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,W/BindingManager( 3272): Cannot call determinedVisibility() - never saw a connection for the pid: 3272
,I/SELinux ( 3574): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,E/SELinux ( 3574): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1018): Killing 2848:flipboard.boxer.app/u0a99 (adj 15): empty #31
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.RestoreService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,D/TimaKeyStoreProvider( 3574): TimaSignature is unavailable
,D/ActivityThread( 3574): Added TimaKeyStore provider
,D/SettingsProvider( 1018): name = access_control_enabled
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3593): MountEmulatedStorage()
,E/Zygote  ( 3593): v2
I/libpersona( 3593): KNOX_SDCARD checking this for 10069
I/libpersona( 3593): KNOX_SDCARD not a persona
I/SELinux ( 3593): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/ActivityManager( 1018): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=3593 uid=10069 gids={50069, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,D/Finsky  ( 3137): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/SELinux ( 3593): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3593): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/System.err( 3545): java.lang.IllegalArgumentException: Unknown package: com.sec.knox.setupwizardstub
W/System.err( 3545): 	at android.os.Parcel.readException(Parcel.java:1544)
W/System.err( 3545): 	at android.os.Parcel.readException(Parcel.java:1493)
W/System.err( 3545): 	at android.content.pm.IPackageManager$Stub$Proxy.setApplicationEnabledSetting(IPackageManager.java:4163)
W/System.err( 3545): 	at android.app.ApplicationPackageManager.setApplicationEnabledSetting(ApplicationPackageManager.java:1925)
W/System.err( 3545): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.processInternal(StubPackageThread.java:88)
W/System.err( 3545): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.run(StubPackageThread.java:49)
,I/ActivityManager( 1018): Killing 2279:flipboard.app/u0a98 (adj 15): empty #31
I/SamsungIME( 1796): getDebugLevel  : 0x4f4c
,D/TimaKeyStoreProvider( 3593): TimaSignature is unavailable
D/ActivityThread( 3593): Added TimaKeyStore provider
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,I/SamsungIME( 1796): KeybaordView init() : load resources
,I/FOTA_Client( 3219): [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,E/libprocessgroup( 1018): failed to kill 1 processes for processgroup 2776
,W/libprocessgroup( 1018): failed to open /acct/uid_10044/pid_2368/cgroup.procs: No such file or directory
,W/libprocessgroup( 1018): failed to open /acct/uid_10099/pid_2848/cgroup.procs: No such file or directory
,I/ActivityManager( 1018): Killing 2882:com.sec.usbsettings/1000 (adj 15): empty #31
,W/FOTA_Client( 3219): [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3610): MountEmulatedStorage()
,E/Zygote  ( 3610): v2
I/libpersona( 3610): KNOX_SDCARD checking this for 10014
I/libpersona( 3610): KNOX_SDCARD not a persona
,I/SELinux ( 3610): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/ActivityManager( 1018): Start proc com.google.android.onetimeinitializer for broadcast com.google.android.onetimeinitializer/.OneTimeInitializerReceiver: pid=3610 uid=10014 gids={50014, 9997} abi=armeabi-v7a
,I/SELinux ( 3610): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3610): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/StatusChecker( 3574): onReceive : android.intent.action.BOOT_COMPLETED,
,I/FactoryTestApp( 2634): [IPCWriterToSecPhoneService$disConnectSecPhoneService](3101)  
,I/ActivityManager( 1018): Killing 2673:com.google.android.apps.books/u0a75 (adj 15): empty #31
,I/StatusChecker( 3574): onReceive : net.mt.init : DONE
,I/ActivityManager( 1018): Killing 2434:com.android.mms/u0a46 (adj 15): empty #31
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,D/FileApkUtils( 1882): Spent 39ms computing apk sha1.
D/FileApkUtils( 1882): Module already staged or being staged:chimera-modules/MapsModule.apk
I/art     ( 1882): DexFile_isDexOptNeeded failed to open oat file '/data/dalvik-cache/arm/data@data@com.google.android.gms@app_chimera@chimera-module-root@module-d5b20f1a6029cea405dc44dd827a138ee4ccf8cc@MapsModule.apk@classes.dex' for file location '/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d5b20f1a6029cea405dc44dd827a138ee4ccf8cc/MapsModule.apk': Failed to open oat filename for reading: No such file or directory
,D/TimaKeyStoreProvider( 3610): TimaSignature is unavailable
,D/DexOptUtils( 1882): Module /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d5b20f1a6029cea405dc44dd827a138ee4ccf8cc/MapsModule.apk appears to be unoptimized.
D/ActivityThread( 3610): Added TimaKeyStore provider
D/DexOptUtils( 1882): Lollipop platform, using <isa> directory.
D/DexOptUtils( 1882): Instantiating DexClassLoader to force creation of odex.
,D/DexOptUtils( 1882): Primary ABI of odexing process is armeabi-v7a
,E/Zygote  ( 3627): MountEmulatedStorage()
E/Zygote  ( 3627): v2
I/libpersona( 3627): KNOX_SDCARD checking this for 10116
I/libpersona( 3627): KNOX_SDCARD not a persona
,I/SELinux ( 3627): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,I/ActivityManager( 1018): Start proc com.sec.android.pagebuddynotisvc for broadcast com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvcBRcvr: pid=3627 uid=10116 gids={50116, 9997} abi=armeabi-v7a,
I/SELinux ( 3627): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/ActivityManager( 1018): Killing 2956:com.sec.android.app.safetyassurance/u0a48 (adj 15): empty #31
,E/SELinux ( 3627): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/FileShare-Server( 3593): ServerBroadcastReceiver.onReceive - action android.intent.action.BOOT_COMPLETED // null
,W/ContextImpl( 1383): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver$InitSerachDBThread.run:130 <bottom of call stack> ,
,W/ContextImpl( 1383): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver$InitSerachDBThread.run:131 <bottom of call stack> 
,I/ActivityManager( 1018): Killing 2977:com.sec.dsm.system/1000 (adj 15): empty #31
,I/SettingSearch/SearchIntentReceiver( 1383): InitSerachDBThread thread end!
,I/dex2oat ( 3634): ----------------------------------------------------
I/dex2oat ( 3634): <SS>: S T A R T I N G . . .
I/dex2oat ( 3634): <SS>: Zip is absent. Canceled.
,I/dex2oat ( 3634): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --compiler-filter=interpret-only --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d5b20f1a6029cea405dc44dd827a138ee4ccf8cc/MapsModule.apk --oat-fd=94 --art-fd=-1 --oat-location=/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d5b20f1a6029cea405dc44dd827a138ee4ccf8cc/arm/MapsModule.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.app.service.BootCompletedBroadcastService; callingUser = 0; userId(target) = 0
,D/TimaKeyStoreProvider( 3627): TimaSignature is unavailable
,I/SamsungIME( 1796): getCurrentKeyboard
I/SamsungIME( 1796): getTextKeyboard
,D/ActivityThread( 3627): Added TimaKeyStore provider
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,V/Finsky  ( 3137): [1] GearheadStateMonitor.onReady: sIsProjecting:false
,D/CountryDetector( 1018): No listener is left
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.verifier.InternalApkUploadService; callingUser = 0; userId(target) = 0,
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.checkin.CheckinService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.reminders.notification.NotificationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/SamsungIME( 1796): [SwiftkeyWrapper] currentLangauge : 1701729619
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.sharing.service.NearbySharingService; callingUser = 0; userId(target) = 0
,I/PageBuddyNotiSvc( 3627): Intent received : action=android.intent.action.BOOT_COMPLETED
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.update.SystemUpdateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000,
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.config.ConfigFetchService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/libprocessgroup( 1018): failed to kill pid 2956: No such process
,D/GCM     ( 1882): COMPAT: Multi user not supported
,I/CheckinService( 1882): Disabling old GoogleServicesFramework version
,W/ContextImpl( 3627): Implicit intents with startService are not safe: Intent { act=com.sec.android.pagebuddynotisvc } android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.pagebuddynotisvc.PageBuddyNotiSvcBRcvr.onReceive:-1 
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,V/OneTimeInitializerReceiver( 3610): OneTimeInitializerReceiver.onReceive
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_2882/cgroup.procs: No such file or directory
,W/libprocessgroup( 1018): failed to open /acct/uid_10098/pid_2279/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_10075/pid_2673/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_2977/cgroup.procs: No such file or directory
,W/ActivityManager( 1018): userId = 0, bbcId = -10000,
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.pagebuddynotisvc, destAppInfo.processName = com.sec.android.pagebuddynotisvc
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.onetimeinitializer/com.google.android.onetimeinitializer.OneTimeService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.onetimeinitializer, destAppInfo.processName = com.google.android.onetimeinitializer
,I/DBG_DM  ( 3102): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 1 sec
W/libprocessgroup( 1018): failed to open /acct/uid_10046/pid_2434/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_10048/pid_2956/cgroup.procs: No such file or directory
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.recovery.AccountRecoveryBackgroundService; callingUser = 0; userId(target) = 0
D/GCM     ( 1681): GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
V/OneTimeService( 3610): OneTimeService.onHandleIntent
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
I/PageBuddyNotiSvc( 3627): onCreate mCpBitFlag=0
,E/Zygote  ( 3662): MountEmulatedStorage()
E/Zygote  ( 3662): v2
I/libpersona( 3662): KNOX_SDCARD checking this for 10125
I/libpersona( 3662): KNOX_SDCARD not a persona
,I/SELinux ( 3662): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 3662): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3662): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1018): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=3662 uid=10125 gids={50125, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3678): MountEmulatedStorage()
I/libpersona( 3678): KNOX_SDCARD checking this for 10015
E/Zygote  ( 3678): v2
I/libpersona( 3678): KNOX_SDCARD not a persona
,I/SELinux ( 3678): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1018): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.GooglePartnerSetup: pid=3678 uid=10015 gids={50015, 9997, 3003} abi=armeabi-v7a
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.authzen.GcmReceiverService; callingUser = 0; userId(target) = 0
,I/SELinux ( 3678): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3678): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/art     (  323): Explicit concurrent mark sweep GC freed 8761(373KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 844us total 30.703ms
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.tron.CollectionService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 3662): TimaSignature is unavailable
D/ActivityThread( 3662): Added TimaKeyStore provider
,D/SystemUpdateService( 1882): onCreate
,I/art     (  323): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 622us total 26.248ms
,D/TimaKeyStoreProvider( 3678): TimaSignature is unavailable
D/ActivityThread( 3678): Added TimaKeyStore provider
,W/ResourcesManager( 3662): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3662): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 3662): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/art     (  323): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 643us total 19.198ms
,D/JsMessageQueue( 3272): Set native->JS mode to OnlineEventsBridgeMode
,D/SystemUpdateService( 1882): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ConfigService( 1681): onCreate
,I/ConfigFetchService( 1882): onStartCommand Intent { cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,V/AuthZen ( 1882): Handling intent: android.intent.action.BOOT_COMPLETED
,D/AuthZenEventHandler( 1882): Handling event: android.intent.action.BOOT_COMPLETED
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1018): Killing 2874:com.sec.android.app.clockpackage/u0a85 (adj 15): empty #31
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.dsi.ant.server.AntService.startService:135 com.dsi.ant.server.startup.BootCompletedReceiver.onReceive:41 
,I/ActivityManager( 1018): Killing 1591:com.sec.android.provider.badge/u0a72 (adj 15): empty #31
,W/ContextImpl( 1018): Implicit intents with startService are not safe: Intent { act=com.dsi.ant.server.IAntHal } android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.dsi.ant.server.AntService.startService:135 
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,W/libprocessgroup( 1018): failed to open /acct/uid_10085/pid_2874/cgroup.procs: No such file or directory
,E/Zygote  ( 3707): MountEmulatedStorage(),
W/ActivityManager( 1018): userId = 0, bbcId = -10000,
I/ActivityManager( 1018): Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=3707 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023,
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.location.internal.GoogleLocationManagerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms,
I/libpersona( 3707): KNOX_SDCARD checking this for 1000
E/Zygote  ( 3707): v2
,I/libpersona( 3707): KNOX_SDCARD not a persona
I/SELinux ( 3707): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 3707): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3707): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/GCoreUlr( 1882): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}]
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.location.reporting.service.DispatchingService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/QuickConnect( 3662): PeriphStartReceiver.onReceive - android.intent.action.BOOT_COMPLETED
,D/QuickConnect( 3662): Util.setSCRunningSetting - [value]0
,D/SettingsProvider( 1018): name = scon_is_running
D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 10125
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
,D/TimaKeyStoreProvider( 3707): TimaSignature is unavailable
,D/ActivityThread( 3707): Added TimaKeyStore provider
,W/BackupManagerService( 1018): dataChanged but no participant pkg='com.android.providers.settings' uid=10125
,D/ChimeraCfgMgr( 1882): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/SecKeyguardClockSingleView( 1188): Ignore. Because it is same clock text
,W/BaseAppContext( 1882): Using Auth Proxy for data requests.
,I/GLSUser ( 1882): [ChannelManager] Attempting to channel bind connection HttpClient.
,I/Kids    ( 1882): [GCoreUtils] Current gmscore version, 7899436 is smaller than the required version 8400000
,D/jxcore_app_log( 3272): JniHelper::setJavaVM(0xb7ebd450), pthread_self() = -1203576544
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1882): [ChannelManager] Checking whether channelId is enabled. isEnabledGmsCore? false, isEnabledSdk? true, isAtLeastKitKat? true
,I/ConfigFetchService( 1882): service connected
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.api.credentials.sync.CredentialSyncReceiverService; callingUser = 0; userId(target) = 0
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3272): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3272):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3272):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3272):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3272):     - Handshake required: true
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3272): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1e1b1e2c added. We now have 1 listener(s)
,I/QuickConnect( 3662): PeriphStartReceiver.onReceive - USER_OWNER care ACTION_BOOT_COMPLETED. run P service
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3272): setBluetoothMacAddress: 7C:F9:0E:51:18:22
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3272): verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"7C:F9:0E:51:18:22"}
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3272): setIdentityString: {"name":"<no peer name>","address":"7C:F9:0E:51:18:22"}
D/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3272): setHandshakeRequired: true -> false
I/QuickConnect( 3662): PeriphStartReceiver.onReceive - no need to start
V/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3272): setHandshakeRequired: true -> false
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3272): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3272):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3272):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3272):     - Bluetooth MAC address: 7C:F9:0E:51:18:22
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3272):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3272):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3272):     - Advertise mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3272):     - Advertise TX power level: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3272):     - Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3272):     - Scan report delay in milliseconds: 500
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3272): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@15d4ccfb added. We now have 1 listener(s)
,D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 3272): addListener: New listener added - the number of listeners is now 1
,D/ConfigFetchService( 1882): ConfigApi connection successful.
,I/GCoreUlr( 1691): DispatchingService.onCreate()
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3736): MountEmulatedStorage(),
I/libpersona( 3736): KNOX_SDCARD checking this for 10131
E/Zygote  ( 3736): v2
I/libpersona( 3736): KNOX_SDCARD not a persona
,I/SELinux ( 3736): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1018): Start proc com.sec.android.app.sbrowser for broadcast com.sec.android.app.sbrowser/.net.NetworkSettingsReceiver: pid=3736 uid=10131 gids={50131, 9997, 1023, 3003, 1028, 1015, 1007, 3001, 3002} abi=armeabi-v7a
I/ActivityManager( 1018): Killing 3004:com.sec.android.app.factorykeystring/1000 (adj 15): empty #31
I/SELinux ( 3736): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 3736): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/SMD     (  304): DCD OFF
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
V/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3272): isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3272): setDiscoveryMode: Discovery mode BLE is supported
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3272): setAdvertiseMode: 1 -> 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3272): setAdvertiseTxPowerLevel: 2 -> 3
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3272): setScanMode: 1 -> 2
,E/Zygote  ( 3753): MountEmulatedStorage(),
,I/libpersona( 3753): KNOX_SDCARD checking this for 10104
E/Zygote  ( 3753): v2
I/libpersona( 3753): KNOX_SDCARD not a persona
D/TimaKeyStoreProvider( 3736): TimaSignature is unavailable
I/SELinux ( 3753): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
D/ActivityThread( 3736): Added TimaKeyStore provider
,I/SELinux ( 3753): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3753): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1018): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.BootReceiver: pid=3753 uid=10104 gids={50104, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3272): bind: Binding a new listener
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AuthZen ( 1882): Fetching signing key...
,D/TimaKeyStoreProvider( 3753): TimaSignature is unavailable
,D/ActivityThread( 3753): Added TimaKeyStore provider
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3272): initialize: My bluetooth address is 7C:F9:0E:51:18:22
,V/io.jxcore.node.ConnectivityMonitor( 3272): updateConnectivityInfo: FORCED notification:
V/io.jxcore.node.ConnectivityMonitor( 3272):     - is Wi-Fi Direct supported: true
V/io.jxcore.node.ConnectivityMonitor( 3272):     - is Bluetooth LE multiple advertisement supported: SUPPORTED
V/io.jxcore.node.ConnectivityMonitor( 3272):     - is Wi-Fi enabled: true
V/io.jxcore.node.ConnectivityMonitor( 3272):     - is Bluetooth enabled: true
V/io.jxcore.node.ConnectivityMonitor( 3272):     - BSSID name: f4:f2:6d:22:99:3e
V/io.jxcore.node.ConnectivityMonitor( 3272):     - is connected/connecting to active network: true
V/io.jxcore.node.ConnectivityMonitor( 3272):     - active network type is Wi-Fi: true
D/io.jxcore.node.JXcoreExtension( 3272): notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
D/io.jxcore.node.ConnectivityMonitor( 3272): start: OK
,I/AuthZen ( 1882): Signing key fetched successfully!
,V/io.jxcore.node.ConnectivityMonitor( 3272): updateConnectivityInfo: No relevant state changes
,V/io.jxcore.node.ConnectivityMonitor( 3272): updateConnectivityInfo: No relevant state changes
,D/btif_config_util( 2656): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/BaseAppContext( 1882): Using Auth Proxy for data requests.
,I/chromium( 3272): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/AuthZen ( 1882): Starting Enrollment...
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.ClientIdService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,W/ContextImpl( 3707): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:53 android.app.ActivityThread.handleReceiver:3125 
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.AppHiderService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.MccFallbackService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.MccOverrideService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,I/DBG_DM  ( 3102): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 2 sec
,I/art     ( 1018): Explicit concurrent mark sweep GC freed 31043(1720KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 27MB/40MB, paused 2.627ms total 253.401ms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.RlzPingIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 3736): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 3736): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3736): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 3736): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,E/Zygote  ( 3777): MountEmulatedStorage()
E/Zygote  ( 3777): v2
I/libpersona( 3777): KNOX_SDCARD checking this for 1000
I/libpersona( 3777): KNOX_SDCARD not a persona
,I/SELinux ( 3777): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/ActivityManager( 1018): Start proc com.samsung.android.bbc.bbcagent for broadcast com.samsung.android.bbc.bbcagent/.bbccontroller.receiver.BootCompletedReceiver: pid=3777 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/SELinux ( 3777): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
E/SELinux ( 3777): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 3753): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3786): MountEmulatedStorage(),
E/Zygote  ( 3786): v2
I/libpersona( 3786): KNOX_SDCARD checking this for 1000
I/libpersona( 3786): KNOX_SDCARD not a persona
I/SELinux ( 3786): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 3786): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
E/SELinux ( 3786): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1018): Start proc com.samsung.hs20settings for broadcast com.samsung.hs20settings/.WifiHs20BroadcastReceiver: pid=3786 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,D/TimaKeyStoreProvider( 3777): TimaSignature is unavailable
,D/ActivityThread( 3777): Added TimaKeyStore provider
,I/art     ( 1882): Explicit concurrent mark sweep GC freed 35661(2MB) AllocSpace objects, 41(656KB) LOS objects, 40% free, 11MB/19MB, paused 1.824ms total 100.802ms
,I/CheckinService( 1882): Checking schedule, now: 1458317734058 next: 1458756694030
I/CheckinService( 1882): active receiver: disabled
,D/TimaKeyStoreProvider( 3786): TimaSignature is unavailable
,D/ActivityThread( 3786): Added TimaKeyStore provider
,W/ResourcesManager( 3777): Asset path '/system/framework/com.samsung.bbccommon.jar' does not exist or contains no resources.
,I/art     ( 1681): Explicit concurrent mark sweep GC freed 7333(428KB) AllocSpace objects, 4(64KB) LOS objects, 39% free, 10MB/17MB, paused 1.086ms total 100.783ms
,D/AuthZen ( 1882): getting auth token. Attempt 0
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1681): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cryptauth
,I/GLSUser ( 1681): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cryptauth without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1681): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1681): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1681): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/FactoryTestApp( 2634): [DummyFtClient$onDestroy](2634) Destroy DummyFtClient service
,D/FactoryTestApp( 2634): [Support$Values.getString](2634) id=MODEL_COMMUNICATION_MODE, value=gsm
,I/FactoryTestApp( 2634): [ModuleCommon$isConnectionModeNone](2634) mConnectionMode = gsm
I/FactoryTestApp( 2634): [ModuleCommon$isRunningFtClient](2634) RUNNING_FTCLIENT : false
,D/FactoryTestApp( 2634): [DummyFtClient$onDestroy](2634) kill process
,I/Process ( 2634): Sending signal. PID: 2634 SIG: 9
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 3786): onCreate
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/SystemUpdateService( 1882): cancelUpdate (empty URL)
I/SystemUpdateService( 1882): active receiver: disabled
,E/AuthZen ( 1882): Error getting auth token
E/AuthZen ( 1882): com.google.android.gms.auth.ad: BadAuthentication
E/AuthZen ( 1882): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/AuthZen ( 1882): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/AuthZen ( 1882): 	at com.google.android.gms.auth.p.a(SourceFile:318)
E/AuthZen ( 1882): 	at com.google.android.gms.auth.authzen.b.a.a(SourceFile:381)
E/AuthZen ( 1882): 	at com.google.android.gms.auth.authzen.b.a.a(SourceFile:132)
E/AuthZen ( 1882): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:200)
E/AuthZen ( 1882): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:153)
E/AuthZen ( 1882): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:103)
E/AuthZen ( 1882): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:256)
E/AuthZen ( 1882): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:207)
E/AuthZen ( 1882): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:200)
E/AuthZen ( 1882): 	at com.google.android.gms.auth.authzen.a.a(SourceFile:122)
E/AuthZen ( 1882): 	at com.google.android.gms.auth.authzen.GcmReceiverService.onHandleIntent(SourceFile:30)
E/AuthZen ( 1882): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AuthZen ( 1882): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AuthZen ( 1882): 	at android.os.Looper.loop(Looper.java:145)
E/AuthZen ( 1882): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/AuthZen ( 1882): Failed to do enrollment for account: thalitester@gmail.com
E/AuthZen ( 1882): com.google.android.gms.auth.authzen.b.b: Failed to get a token for authzen enrollment
E/AuthZen ( 1882): 	at com.google.android.gms.auth.authzen.b.a.a(SourceFile:139)
E/AuthZen ( 1882): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:200)
E/AuthZen ( 1882): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:153)
E/AuthZen ( 1882): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:103)
E/AuthZen ( 1882): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:256)
E/AuthZen ( 1882): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:207)
E/AuthZen ( 1882): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:200)
E/AuthZen ( 1882): 	at com.google.android.gms.auth.authzen.a.a(SourceFile:122)
E/AuthZen ( 1882): 	at com.google.android.gms.auth.authzen.GcmReceiverService.onHandleIntent(SourceFile:30)
E/AuthZen ( 1882): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AuthZen ( 1882): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AuthZen ( 1882): 	at android.os.Looper.loop(Looper.java:145)
E/AuthZen ( 1882): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/SBrowserFeatureFlag( 3736): initialized in static block : loadCscFeatureValue() succeed! ,
I/ActivityManager( 1018): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=3815 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,E/Zygote  ( 3815): MountEmulatedStorage()
I/libpersona( 3815): KNOX_SDCARD checking this for 10019
E/Zygote  ( 3815): v2
I/libpersona( 3815): KNOX_SDCARD not a persona
,I/Hs20UtilService( 3786): Starting #1
,I/Hs20UtilService( 3786): Message received 5003
,I/ActivityManager( 1018): Process com.sec.factory (pid 2634)(adj 0) has died(40,1124)
,I/SELinux ( 3815): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 3815): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,W/jxcore-log( 3272): Initializing JXcore engine
W/jxcore-log( 3272): JXcore engine is ready
,E/SELinux ( 3815): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/DBG_POLICYDM( 3173): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.RlzPingService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,D/TimaKeyStoreProvider( 3815): TimaSignature is unavailable
,D/ActivityThread( 3815): Added TimaKeyStore provider
,D/a       ( 1882): Opening database auth.proximity.permit_store...
,D/ManifestProvider( 3736): onCreate()
,D/AuthZenTransactionCache( 1882): Initialized cache in: /data/data/com.google.android.gms/files
D/AuthZenTransactionCache( 1882): Clearing transaction cache
,E/audit   ( 1869): type=1400 msg=audit(1458317734.643:205): avc:  denied  { ioctl } for  pid=3768 comm="Thread-429" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,E/audit   ( 1869):  SEPF_SM-A500FU_5.0.2_0027
E/audit   ( 1869): type=1300 msg=audit(1458317734.643:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=4 a3=9c41f8f8 items=0 ppid=323 ppcomm=main pid=3768 auid=4294967295 uid=10174 gid=10174 euid=10174 suid=10174 fsuid=10174 egid=10174 sgid=10174 fsgid=10174 ses=4294967295 tty=(none) comm="Thread-429" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1869): type=1320 msg=audit(1458317734.643:205): 
,E/NetworkSettingsReceiver( 3736): onReceive: android.intent.action.BOOT_COMPLETED
,W/jxcore-log( 3272): Starting JXcore engine
,D/SystemUpdateService( 1882): onDestroy
,I/DBG_POLICYDM( 3173): [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,I/dex2oat ( 3634): dex2oat took 1.990s (threads: 4)
,D/DexOptUtils( 1882): Odex created at:/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d5b20f1a6029cea405dc44dd827a138ee4ccf8cc/arm/MapsModule.dex
D/DexOptUtils( 1882): Set odex to world readable.
,D/DexOptUtils( 1882): Renamed odex to /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d5b20f1a6029cea405dc44dd827a138ee4ccf8cc/arm/MapsModule.odex
,D/FileApkUtils( 1882): Keeping up-to-date module: module-d5b20f1a6029cea405dc44dd827a138ee4ccf8cc
,I/RlzPingService( 3678): Setting next ping for 1458922534717
,D/GmsModuleFndr( 1882): Beginning GMS chimera module scan
,D/GmsModuleFndr( 1882): Module pkg com.google.android.apps.kids.familylink not installed, skipping
,D/ChimeraCfgMgr( 1882): Beginning module configuration check
,D/ChimeraCfgMgr( 1882): Module APKs unchanged, check complete
,W/art     ( 3173): Suspending all threads took: 47.019ms
,I/DBG_POLICYDM( 3173): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,I/DBG_POLICYDM( 3173): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,I/DBG_POLICYDM( 3173): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,E/SBrowserFeatureFlag( 3736): initSupportedPkg: checkExistService com.samsung.android.smartclip.SpenGestureManager@1e4a5bd2
,D/SBrowserFeatureFlag( 3736): initialize : initSupportedPkg() succeed! 
I/VerificationLog( 3736): SbrowserSettings- url content://com.sec.android.app.sbrowser/readinglist/pinned.mhtml
,I/DBG_POLICYDM( 3173): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,D/TimaService( 1018): TIMA: in getTimaVersion
,D/TimaService( 1018): TIMA3: KeyStore3_init
E/TLC_TZ_KEYSTORE: ( 1018): Inside TZ_KEYSTORE_initialize()
D/TimaService( 1018): TIMA: in getTimaVersion
I/TLC_TZ_KEYSTORE: ( 1018): creating new keystore context...
I/TLC_TZ_KEYSTORE: ( 1018): initializing ccm context...
I/TLC_TZ_KEYSTORE: ( 1018): root = /firmware/image, root_strlen = 15
I/TLC_TZ_KEYSTORE: ( 1018): process = tima_key, process_strlen = 8
I/TZ: qc_tlc_communication( 1018): root = /firmware/image, root_len = 15
I/TZ: qc_tlc_communication( 1018): process = tima_key, process_strlen = 8
I/TZ: qc_tlc_communication( 1018): aligned max_sendmsg_size = 1088 = 0x440
I/TZ: qc_tlc_communication( 1018): aligned max_recvmsg_size = 1088 = 0x440
I/TZ: qc_tlc_communication( 1018): max_message_size = 2176 = 0x880
D/QSEECOMAPI: ( 1018): QSEECom_get_handle sb_length = 0x880
D/QSEECOMAPI: ( 1018): App is not loaded in QSEE
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/art     ( 1691): Explicit concurrent mark sweep GC freed 13007(780KB) AllocSpace objects, 5(80KB) LOS objects, 40% free, 10MB/17MB, paused 12.527ms total 1.100s
,W/jxcore-log( 3272): Platform android
W/jxcore-log( 3272): 
,W/jxcore-log( 3272): Process ARCH arm
W/jxcore-log( 3272): 
E/Zygote  ( 3837): MountEmulatedStorage()
E/Zygote  ( 3837): v2
I/libpersona( 3837): KNOX_SDCARD checking this for 10135
I/libpersona( 3837): KNOX_SDCARD not a persona
,I/SELinux ( 3837): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 3837): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/ActivityManager( 1018): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=3837 uid=10135 gids={50135, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,I/ActivityManager( 1018): Killing 3025:com.samsung.android.app.colorblind/1000 (adj 15): empty #31
,D/QSEECOMAPI: ( 1018): Loaded image: APP id = 9
,E/SELinux ( 3837): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/TZ: qc_tlc_communication( 1018): TIMA: path = /firmware/image, fname = tima_key, tzapp is loaded
I/TLC_TZ_KEYSTORE: ( 1018): ctx = 0xb87a3000, comm = 0xb8527f30, sendmsg = 0xab003000, recvmsg = 0xab003440
,I/TZ_init: ( 1018): TZ_init: sending initialization request...
,E/TZ_init: ( 1018): TZ_init Process: Secure memory is not initialized!
E/TZ_init: ( 1018): trustlet initialization failed
I/TZ_init: ( 1018): TZ_init_START...
,I/TZ_init: ( 1018): TZ_init_with_data: sending initialization request...
,I/TZ_init: ( 1018): TZ_init: successful initialization
D/QSEECOMAPI: ( 1018): QSEECom_dealloc_memory 
D/QSEECOMAPI: ( 1018): QSEECom_shutdown_app, app_id = 9
,E/TLC_TZ_KEYSTORE: ( 1018): Count : 1, Ret : 0
,I/DBG_POLICYDM( 3173): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,I/DBG_POLICYDM( 3173): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,D/TimaKeyStoreProvider( 3837): TimaSignature is unavailable
,D/ActivityThread( 3837): Added TimaKeyStore provider
,D/StatusBar.NetworkController( 1188): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1188): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1188): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1188): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1188): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1188): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,W/ResourcesManager( 3837): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 3837): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3837): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3707): Resource data:Loop for running activitycom.sec.android.app.sbrowser.SBrowserMainActivity
I/AMMetaDataParserService( 3707): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3707): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3707): getResourcePackageName:assistantlist
I/AMMetaDataParserService( 3707): Resource data:2131165186
,I/DBG_DM  ( 3102): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 3 sec
,W/ResourcesManager( 3707): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 3707): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3707): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 3707): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
I/AMMetaDataParserService( 3707): getResourceName:com.sec.android.app.sbrowser:xml/assistantlist
I/AMMetaDataParserService( 3707): getResourceTypeNamexml
,I/KLMS-2.5.183: ( 3815): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Fri Mar 18 17:15:34 GMT+01:00 2016
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,I/ActivityManager( 1018): Killing 2049:com.google.android.gms.wearable/u0a12 (adj 15): empty #31
,I/KLMS-2.5.183: ( 3815): KLMSAbstractReciever(): onReceive().END.
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,W/ContextImpl( 3777): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.bbc.bbcagent.bbccontroller.BBCDataConsistency.checkDBConsistencyFromPM:220 com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BootCompletedReceiver.onReceive:50 
,E/Zygote  ( 3854): MountEmulatedStorage(),
E/Zygote  ( 3854): v2
I/libpersona( 3854): KNOX_SDCARD checking this for 10022
,I/libpersona( 3854): KNOX_SDCARD not a persona
I/SELinux ( 3854): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/AMMetaDataParserService( 3707): Icon data: ResourceEnter URL2131755287android.intent.action.doInputURL2130837509,
I/SELinux ( 3854): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3854): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1018): Start proc com.android.managedprovisioning for broadcast com.android.managedprovisioning/.BootReminder: pid=3854 uid=10022 gids={50022, 9997, 1028, 3003} abi=armeabi-v7a,
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.service.BBCAgentService; callingUser = 0; userId(target) = 0,
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.android.bbc.bbcagent, destAppInfo.processName = com.samsung.android.bbc.bbcagent
,I/KLMS-2.5.183: ( 3815): KLMSIntentService(): onCreate()
,I/KLMS-2.5.183: ( 3815): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.5.183: ( 3815): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/GCoreUlr( 1691): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED
,I/KLMS-2.5.183: ( 3815): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/jxcore-log( 3272): JXcore Cordova bridge is ready!
I/jxcore-log( 3272): 
,W/jxcore-log( 3272): JXcore engine is started
,E/Zygote  ( 3870): MountEmulatedStorage()
I/libpersona( 3870): KNOX_SDCARD checking this for 1000
E/Zygote  ( 3870): v2
I/libpersona( 3870): KNOX_SDCARD not a persona
,I/SELinux ( 3870): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/org.thaliproject.p2p.ThaliPermissions( 3272): execute: REQUEST_ACCESS_COARSE_LOCATION
,I/SELinux ( 3870): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 3870): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/chromium( 3272): [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
I/ActivityManager( 1018): Start proc com.sec.bcservice for broadcast com.sec.bcservice/.BCServiceReceiver: pid=3870 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,E/jxcore  ( 3272): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 3272): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/AMMetaDataParserService( 3707): Icon data: ResourceTabs2131755155android.intent.action.doWindowManager2130837511
,I/KLMS-2.5.183: ( 3815): KLMSIntentService(): BOOT_COMPLETED
,I/chromium( 3272): [INFO:CONSOLE(57)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (57)
,I/chromium( 3272): [INFO:CONSOLE(62)] "****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****", source: file:///android_asset/www/js/thali_main.js (62)
,D/FocusedStackFrame( 1018): Set to : 0
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
D/InputDispatcher( 1018): Focused application set to: xxxx
D/InputDispatcher( 1018): Focus left window: 3272
D/TimaKeyStoreProvider( 3870): TimaSignature is unavailable
D/ActivityThread( 3870): Added TimaKeyStore provider
D/TimaKeyStoreProvider( 3854): TimaSignature is unavailable
D/ActivityThread( 3854): Added TimaKeyStore provider
D/daemonapp( 1310): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
D/PointerIcon( 1018): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1018): setMouseCustomIcon IconType is same.101
,I/AMMetaDataParserService( 3707): Icon data: ResourceNew Tab2131755458android.intent.action.doNewWindow2130837510
,D/PermissionCache(  258): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (191 us)
,I/AMMetaDataParserService( 3707): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappManager
I/AMMetaDataParserService( 3707): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity
I/AMMetaDataParserService( 3707): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity0
I/AMMetaDataParserService( 3707): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity1
I/AMMetaDataParserService( 3707): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity2
I/AMMetaDataParserService( 3707): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity3
I/AMMetaDataParserService( 3707): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity4
I/AMMetaDataParserService( 3707): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity5
I/AMMetaDataParserService( 3707): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity6
I/AMMetaDataParserService( 3707): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity7
I/AMMetaDataParserService( 3707): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity8
I/AMMetaDataParserService( 3707): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity9
I/AMMetaDataParserService( 3707): Resource data:Loop for running activitycom.sec.android.app.sbrowser.history.ui.HistoryActivity
I/AMMetaDataParserService( 3707): Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.Settings
W/ContextImpl( 3707): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3707): Resource data:Loop for running activitycom.sec.android.app.sbrowser.reader.ui.ReaderActivity
I/AMMetaDataParserService( 3707): Resource data:Loop for running activitycom.sec.android.app.sbrowser.menuactivity.ui.AddWebPageMenuActivity
I/AMMetaDataParserService( 3707): Resource data:Loop for running activitycom.sec.android.app.sbrowser.readinglist.activity.ReadingListActivity
I/AMMetaDataParserService( 3707): Resource data:Loop for running activitycom.sec.android.app.sbrowser.readinglist.controller.ReadingListSearchActivity
I/AMMetaDataParserService( 3707): Resource data:Loop for running activitycom.sec.android.app.sbrowser.sites.SitesActivity
I/AMMetaDataParserService( 3707): Resource data:Loop for running activitycom.sec.android.app.sbrowser.common.DataChargingDialog
I/AMMetaDataParserService( 3707): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.EditBookmarkFolderActivity
I/AMMetaDataParserService( 3707): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.AddBookmarkActivity
I/AMMetaDataParserService( 3707): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.ShowBookmarksActivity
I/AMMetaDataParserService( 3707): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.SelectBookmarkFolderActivity
I/AMMetaDataParserService( 3707): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.CreateBookmarkFolderActivity
I/AMMetaDataParserService( 3707): Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.SynctabActivity
I/AMMetaDataParserService( 3707): Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.SelectSyncAccountActivity
,I/AMMetaDataParserService( 3707): Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.AutofillFormEdit
I/AMMetaDataParserService( 3707): Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.DeleteSyncTabActivity
I/AMMetaDataParserService( 3707): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountGetStartedActivity
I/AMMetaDataParserService( 3707): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountCreateAccountActivity
I/AMMetaDataParserService( 3707): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountConfirmAccountActivity
I/AMMetaDataParserService( 3707): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountSignInActivity
I/AMMetaDataParserService( 3707): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountVerifiedAccountActivity
,I/AMMetaDataParserService( 3707): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountCreateAccountNotAllowedActivity
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
,W/PluginManager( 3272): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 51ms. Plugin should use CordovaInterface.getThreadPool().
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,I/KLMS-2.5.183: ( 3815): KLMSIntentService(): onDestroy()
,W/SEAMService( 1018):  hashset_to_int_array returning null
,W/SEAMService( 1018):  hashset_to_int_array returning null
D/CustomFrequencyManagerService( 1018): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  pkgName : ACTIVITY_RESUME_BOOSTER@7
,E/SQLiteLog( 3777): (284) automatic index on seams_container_info(seams_container_id)
W/ActivityManager( 1018): mDVFSHelper.acquire()
,E/SQLiteLog( 3777): (284) automatic index on seams_container_info(sp_id)
,V/WindowOrientationListener( 1018): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
V/WindowOrientationListener( 1018): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
V/WindowManager( 1018): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
W/ResourcesManager( 3870): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/SEAMService( 1018):  hashset_to_int_array returning null
,I/AMMetaDataParserService( 3707): Resource data:Loop for running activitycom.android.contacts.activities.PeopleActivity
I/AMMetaDataParserService( 3707): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3707): getResourcePackageName:assistant
I/AMMetaDataParserService( 3707): Resource data:2131034113
,D/Launcher( 1497): onRestart, Launcher: 508189650
W/ResourcesManager( 3707): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
I/AMMetaDataParserService( 3707): getResourceName:com.android.contacts:xml/assistant_main
W/ResourcesManager( 3707): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
I/AMMetaDataParserService( 3707): getResourceTypeNamexml
W/ResourcesManager( 3707): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,I/ActivityManager( 1018): Killing 3048:com.sec.android.diagmonagent/1000 (adj 15): empty #31
,D/Launcher( 1497): onStart, Launcher: 508189650
D/Launcher.HomeView( 1497): onStart
D/Launcher( 1497): onResume, Launcher: 508189650
,D/SettingsProvider( 1018): name = kids_home_mode
D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
,D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 10007
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
D/Launcher.HomeView( 1497): onResume
,W/ContextImpl( 3870): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.bcservice.BCServiceReceiver.onReceive:18 android.app.ActivityThread.handleReceiver:3125 
,D/WindowOrientationListener( 1018):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
,D/SensorService( 1018): [SO] activate (ident=0xb8a0c9c0, enabled=0)
I/Sensors ( 1018): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.sec.bcservice/com.sec.bcservice.BroadcastService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.bcservice, destAppInfo.processName = com.sec.bcservice
,D/Launcher( 1497): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,D/MenuAppsGridFragment( 1497): onResume
,D/ActivityManager( 1018): handle home activity for 0
,I/WallpaperManagerService( 1018): switchPersonaWallpaper is called for personaId-0
,D/KnoxTimeoutHandler( 1018): post home show event for user 0
D/ActivityManager( 1018): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1018): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1018): postActiveUserChange, showWhenLocked: false
,D/SensorManager( 1018): unregisterListener ::   
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
I/SurfaceFlinger(  258): id=12 createSurf (720x1280),1 flag=4, Mauncher
,D/StatusBarManagerService( 1018): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,E/        ( 3707): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/Sensors ( 1018): AccelerometerSensor(0) setDelay : 200000000(ns)
,I/GFX construct_block_size_descriptor_2d second part( 3707): took 2.685520ms for 0*0 texture 0
,D/SensorService( 1018): [SO] changed settle time [0]
D/SensorService( 1018): [SO] setDelay [200000000]
D/SensorService( 1018): [SO] activate (ident=0xb8a0c9c0, enabled=1)
D/SensorService( 1018): [SO] AR_init
I/Sensors ( 1018): AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,D/StatusBarManagerService( 1018): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/SensorManager( 1018): registerListener :: 1600221811, Screen Orientation Sensor, 200000, 0,  
D/WallpaperManagerService( 1018):  force update = false; persona id = 0; current user =0; current persona = 0
D/KnoxTimeoutHandler( 1018): handleHomeShow for 0 and current 0
D/PersonaManagerService( 1018): getPersonasForUser(): returning null!
D/KnoxTimeoutHandler( 1018): handleActiveUserChange for user 0
I/libpersona( 3897): KNOX_SDCARD checking this for 1000
E/Zygote  ( 3897): MountEmulatedStorage()
I/libpersona( 3897): KNOX_SDCARD not a persona
E/Zygote  ( 3897): v2
,I/F_PHONE ( 3870): [[com.sec.bcservice]] bind SecPhone Service with FactoryPhone
I/SELinux ( 3897): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,W/ContextImpl( 3870): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.samsung.android.sec_platform_library.FactoryPhone.connectToRilService:95 com.samsung.android.sec_platform_library.FactoryPhone.<init>:61 com.sec.bcservice.BroadcastService.onCreate:146 
,I/ActivityManager( 1018): Start proc com.sec.android.app.bluetoothtest for broadcast com.sec.android.app.bluetoothtest/.BluetoothBDAdrressReceiver: pid=3897 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 3897): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3897): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/InputDispatcher( 1018): Focus entered window: 1497
,I/GFX generate_partition_tables( 3707): took 6.375886ms for 0*0 texture 0
,I/GFX raster( 3707): took 10.413490ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3707): Bitmap=0xb8276898 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb828edf0 counterpartCT=4 counterpartW=96 counterparth=96
,D/PointerIcon( 1018): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1018): setMouseCustomIcon IconType is same.101
D/SRIB_DCS( 1497): log_dcs ThreadedRenderer::initialize entered! 
,D/Launcher( 1497): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,D/InputMethodManagerService( 1018): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,I/AMMetaDataParserService( 3707): Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.sec.phone/com.sec.phone.SecPhoneService; callingUser = 0; userId(target) = 0
,D/PanelView( 1188): There is/are notification(s) 
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.bcservice, destAppInfo.processName = com.sec.phone
D/SamsungIME( 1796): onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
,W/IInputConnectionWrapper( 3272): showStatusIcon on inactive InputConnection
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
D/TimaKeyStoreProvider( 3897): TimaSignature is unavailable
D/ActivityThread( 3897): Added TimaKeyStore provider
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3920): MountEmulatedStorage()
E/Zygote  ( 3920): v2
I/libpersona( 3920): KNOX_SDCARD checking this for 10042
I/libpersona( 3920): KNOX_SDCARD not a persona
I/SELinux ( 3920): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 3920): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3920): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/Timeline( 1497): Timeline: Activity_idle id: android.os.BinderProxy@10c264f8 time:41881,
D/PersonaManager( 1018): isKioskContainerExistOnDevice
I/ActivityManager( 1018): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=3920 uid=10042 gids={50042, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  323): Explicit concurrent mark sweep GC freed 8768(373KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 647us total 24.068ms
,D/TimaKeyStoreProvider( 3920): TimaSignature is unavailable
,D/ActivityThread( 3920): Added TimaKeyStore provider
,D/F_PHONE ( 3870): [[com.sec.bcservice]] onServiceConnected()
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/F_PHONE ( 3870): default registerAction()
I/F_PHONE ( 3870): [[com.sec.bcservice]] sendPendingMessage()
,I/art     (  323): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 685us total 23.186ms
,E/        ( 3707): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3707): took 0.983438ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3707): Bitmap=0xb8276898 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8296f20 counterpartCT=4 counterpartW=96 counterparth=96
,I/art     (  323): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 639us total 17.379ms
,W/ResourcesManager( 3897): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/SensorService( 1018): [SO] Reset Rotation Old [100], Init [1]
W/ContextImpl( 3897): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.app.bluetoothtest.BluetoothBDAdrressReceiver.onReceive:32 android.app.ActivityThread.handleReceiver:3125 
D/BluetoothBDAdrressReceiver( 3897): onReceive(), action: android.intent.action.BOOT_COMPLETED
,I/AMMetaDataParserService( 3707): Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,E/Zygote  ( 3939): MountEmulatedStorage()
I/libpersona( 3939): KNOX_SDCARD checking this for 1000
E/Zygote  ( 3939): v2
I/libpersona( 3939): KNOX_SDCARD not a persona
I/SELinux ( 3939): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1018): Start proc com.samsung.android.MtpApplication for broadcast com.samsung.android.MtpApplication/.MtpReceiver: pid=3939 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/SELinux ( 3939): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/        ( 3707): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
E/SELinux ( 3939): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/GFX construct_block_size_descriptor_2d second part( 3707): took 2.468438ms for 0*0 texture 0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 3920): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
I/GFX generate_partition_tables( 3707): took 7.692915ms for 0*0 texture 0,
E/Zygote  ( 3949): MountEmulatedStorage()
I/GFX raster( 3707): took 11.077134ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3707): Bitmap=0xb82936b8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb82939d8 counterpartCT=4 counterpartW=96 counterparth=96
,E/Zygote  ( 3949): v2
I/libpersona( 3949): KNOX_SDCARD checking this for 10139
I/libpersona( 3949): KNOX_SDCARD not a persona
,I/SELinux ( 3949): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 3949): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 3949): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1018): Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.BootCamera: pid=3949 uid=10139 gids={50139, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a
,I/AMMetaDataParserService( 3707): Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.sec.android.app.bluetoothtest/com.sec.android.app.bluetoothtest.BluetoothBDTestService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.app.bluetoothtest, destAppInfo.processName = com.sec.android.app.bluetoothtest
,I/ActivityManager( 1018): Displayed Component not be shown by security: +352ms
,W/ResourcesManager( 1468): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/BluetoothBDTestService( 1468): onCreate()
,E/BluetoothBDTestService( 1468): onStart(), extra_type: BOOT_COMPLETED
E/BluetoothBDTestService( 1468): bd_address_path: /efs/bluetooth/bt_addr
,E/BluetoothBDTestService( 1468): already exist!( /efs/bluetooth/bt_addr ), file length: 17
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 3949): TimaSignature is unavailable
D/TimaKeyStoreProvider( 3939): TimaSignature is unavailable
D/ActivityThread( 3949): Added TimaKeyStore provider
D/ActivityThread( 3939): Added TimaKeyStore provider
E/Zygote  ( 3969): MountEmulatedStorage()
E/Zygote  ( 3969): v2
I/libpersona( 3969): KNOX_SDCARD checking this for 1000
I/libpersona( 3969): KNOX_SDCARD not a persona
,I/SELinux ( 3969): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
I/ActivityManager( 1018): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.receiver.ServiceStartReceiver: pid=3969 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/ActivityManager( 1018): Killing 1893:com.android.defcontainer/u0a4 (adj 15): empty #31
,I/SELinux ( 3969): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 3969): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
E/        ( 3707): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3707): took 0.623489ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3707): Bitmap=0xb8293820 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb828ef10 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3707): Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,W/ResourcesManager( 3949): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 3949): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3949): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 3949): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
W/ResourcesManager( 3949): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/TimaKeyStoreProvider( 3969): TimaSignature is unavailable
,D/ActivityThread( 3969): Added TimaKeyStore provider
,E/        ( 3707): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3707): took 0.829585ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3707): Bitmap=0xb8296388 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8296698 counterpartCT=4 counterpartW=96 counterparth=96
,E/MTPRx   ( 3939): In MtpReceiverandroid.intent.action.BOOT_COMPLETED
,D/SecContentProvider2( 1018): uri = 14 selection = getSealedState
D/SecContentProvider2( 1018): mCursor = null
,I/CalendarProvider2( 3920): CalendarProvider2.onCreate() called
,D/SecContentProvider2( 1018): uri = 14 selection = getSealedUsbMassStorageState
,D/SecContentProvider2( 1018): mCursor = null
,I/AMMetaDataParserService( 3707): Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,V/MTPRx   ( 3939): sealedState: false
V/MTPRx   ( 3939): sealedUsbMassStorageState: false
,D/SensorService( 1018): [SO] currT = 42161073000, prevT = 41711086000, diff = 449987000, [0.172 0.421 10.247]
,D/SensorService( 1018): [SO] 0.172 0.421 10.247
D/SensorService( 1018): [SO] [100 -> 255]
,D/SettingsProvider( 1018): name = mtp_usb_connection_status
,D/SettingsProvider( 1018): name = media_player_mode
,D/CustomFrequencyManagerService( 1018): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  tag : ACTIVITY_RESUME_BOOSTER@7
,W/ResourcesManager( 3969): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ActivityManager( 1018): mDVFSHelper.release()
,D/CustomFrequencyManagerService( 1018): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  pkgName : ACTIVITY_RESUME_BOOSTER@11
,I/ActivityManager( 1018): Killing 3083:com.sec.providers.settingsearch/u0a150 (adj 15): empty #31
,I/SecKeyguardClockSingleView( 1188): Ignore. Because it is same clock text
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3988): MountEmulatedStorage()
,I/libpersona( 3988): KNOX_SDCARD checking this for 10145
E/Zygote  ( 3988): v2
I/libpersona( 3988): KNOX_SDCARD not a persona
D/SettingsProvider( 1018): name = mtp_usb_conditions_met
I/SELinux ( 3988): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 3988): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3988): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1018): Start proc com.android.email for broadcast com.android.email/.service.EmailBroadcastReceiver: pid=3988 uid=10145 gids={50145, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a,
,W/libprocessgroup( 1018): failed to open /acct/uid_10072/pid_1591/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_3004/cgroup.procs: No such file or directory
,D/SettingsProvider( 1018): name = mtp_running_status
I/SecKeyguardClockSingleView( 1188): Ignore. Because it is same clock text
,I/SecKeyguardClockSingleView( 1188): Ignore. Because it is same clock text
,D/TimaKeyStoreProvider( 3988): TimaSignature is unavailable
,D/ActivityThread( 3988): Added TimaKeyStore provider
,D/PersonaManagerService( 1018): getPersonasForUser(): returning null!
,I/KnoxUsageLogPro( 3969): KnoxUsageReceiver onReceive :android.intent.action.BOOT_COMPLETED myUserId=0
D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/KnoxUsageLogPro( 3969): savePreference: key = previous_sys_time value = 1458317735789
,I/Babel_SMS( 3753): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 3753): MmsConfig.loadMmsSettings
,I/Babel_SMS( 3753): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
I/Babel_SMS( 3753): MmsConfig.loadFromDatabase
,I/KnoxUsageLogPro( 3969): premStatus:2
,I/KnoxUsageLogPro( 3969): isEulaShown : false
,I/KnoxUsageLogPro( 3969): KnoxUsageReceiver onReceive : not Processible, just return
,I/ActivityManager( 1018): Killing 3067:com.google.android.configupdater/u0a86 (adj 15): empty #31
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ResourcesManager( 3988): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 3988): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 3988): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 3988): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3988): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/SettingsProvider( 1018): name = media_mount_count
,D/SettingsProvider( 1018): name = mtp_sync_alive
,I/SecKeyguardClockSingleView( 1188): Ignore. Because it is same clock text
,I/SecKeyguardClockSingleView( 1188): Ignore. Because it is same clock text
,D/AndroidRuntime( 3890): 
D/AndroidRuntime( 3890): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/SettingsProvider( 1018): name = sdcard_launch
,D/AndroidRuntime( 3890): CheckJNI is OFF
I/SecKeyguardClockSingleView( 1188): Ignore. Because it is same clock text
D/AndroidRuntime( 3890): readGMSProperty: start
D/AndroidRuntime( 3890): readGMSProperty: already setted!!
D/AndroidRuntime( 3890): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 3890): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 3890): readGMSProperty: end
D/AndroidRuntime( 3890): addProductProperty: start
,D/SettingsProvider( 1018): name = boot_time_connected
,I/SecKeyguardClockSingleView( 1188): Ignore. Because it is same clock text
,E/Babel_SMS( 3753): canonicalizeMccMnc: invalid mccmnc 
,I/Babel_SMS( 3753): MmsConfig.loadFromResources
,E/Babel_SMS( 3753): canonicalizeMccMnc: invalid mccmnc nullnull
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,I/Babel_SMS( 3753): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,I/DBG_DM  ( 3102): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 4 sec,
D/SettingsProvider( 1018): name = mtp_open_session
,I/KnoxUsageLogPro( 3969): savePreference: key = previous_elapsed_time value = 42267
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
E/        ( 3707): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3707): took 0.732239ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3707): Bitmap=0xb82924e0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb82927a0 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3707): Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.api.credentials.sync.CredentialSyncService; callingUser = 0; userId(target) = 0
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,I/SecKeyguardClockSingleView( 1188): Ignore. Because it is same clock text
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_3025/cgroup.procs: No such file or directory
,W/libprocessgroup( 1018): failed to open /acct/uid_10012/pid_2049/cgroup.procs: No such file or directory
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_3048/cgroup.procs: No such file or directory
,W/libprocessgroup( 1018): failed to open /acct/uid_10004/pid_1893/cgroup.procs: No such file or directory
,I/Timeline( 1018): Timeline: Activity_windows_visible id: ActivityRecord{78e8e68 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t235} time:42467
W/libprocessgroup( 1018): failed to open /acct/uid_10150/pid_3083/cgroup.procs: No such file or directory
,W/libprocessgroup( 1018): failed to open /acct/uid_10086/pid_3067/cgroup.procs: No such file or directory
,I/SurfaceFlinger(  258): id=11 Removed NainActivit (7/8)
,I/SurfaceFlinger(  258): id=11 Removed NainActivit (-2/8)
,I/ActivityManager( 1018): Killing 3173:com.policydm/1000 (adj 15): empty #31
,E/        ( 3707): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
D/CustomFrequencyManagerService( 1018): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  tag : ACTIVITY_RESUME_BOOSTER@11
,I/GCoreUlr( 1691): WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=10, mName='AuthError'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,I/PCWCLIENTTRACE_PushUtil( 3407): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 3407): sales region : global
I/PCWCLIENTTRACE_PushUtil( 3407): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 3407): [onReceive] - android.intent.action.BOOT_COMPLETED
D/PCWCLIENTTRACE_SYSTEMReceiver( 3407): ACTION_BOOTUP - Version: 4.82
D/PCWCLIENTTRACE_SYSTEMReceiver( 3407): ACTION_BOOTUP - Push type: [SPP, GCM]
,I/GFX raster( 3707): took 0.675365ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3707): Bitmap=0xb82933c0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb828ef10 counterpartCT=4 counterpartW=96 counterparth=96
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/AffinityControl( 3890): AffinityControl: registerfunction enter
,I/AMMetaDataParserService( 3707): Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
E/ActivityThread( 3272): Activity com.test.thalitest.MainActivity has leaked IntentReceiver io.jxcore.node.ConnectivityMonitor$WifiStateChangedAndConnectivityActionBroadcastReceiver@2731f118 that was originally registered here. Are you missing a call to unregisterReceiver()?
,E/ActivityThread( 3272): android.app.IntentReceiverLeaked: Activity com.test.thalitest.MainActivity has leaked IntentReceiver io.jxcore.node.ConnectivityMonitor$WifiStateChangedAndConnectivityActionBroadcastReceiver@2731f118 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread( 3272): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:970)
E/ActivityThread( 3272): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:771)
E/ActivityThread( 3272): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:2014)
E/ActivityThread( 3272): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1994)
E/ActivityThread( 3272): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1988),
E/ActivityThread( 3272): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:503)
E/ActivityThread( 3272): 	at io.jxcore.node.ConnectivityMonitor.start(ConnectivityMonitor.java:67)
E/ActivityThread( 3272): 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:90)
E/ActivityThread( 3272): 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
E/ActivityThread( 3272): 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
E/ActivityThread( 3272): 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
E/ActivityThread( 3272): 	,at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
E/ActivityThread( 3272): 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
E/ActivityThread( 3272): 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
E/ActivityThread( 3272): 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
E/ActivityThread( 3272): 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
E/ActivityThread( 3272): 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
E/ActivityThread( 3272): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3272): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread( 3272): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/Zygote  ( 4029): MountEmulatedStorage(),
E/Zygote  ( 4029): v2
I/libpersona( 4029): KNOX_SDCARD checking this for 10072,
I/libpersona( 4029): KNOX_SDCARD not a persona
,I/SELinux ( 4029): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1018): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=4029 uid=10072 gids={50072, 9997} abi=armeabi-v7a
,I/SELinux ( 4029): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 4029): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailBroadcastProcessorService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000,
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.email, destAppInfo.processName = com.android.email
E/ActivityThread( 3272): Activity com.test.thalitest.MainActivity has leaked IntentReceiver org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager$BluetoothModeBroadcastReceiver@38492771 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread( 3272): android.app.IntentReceiverLeaked: Activity com.test.thalitest.MainActivity has leaked IntentReceiver org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager$BluetoothModeBroadcastReceiver@38492771 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread( 3272): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:970)
E/ActivityThread( 3272): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:771)
E/ActivityThread( 3272): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:2014)
E/ActivityThread( 3272): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1994)
E/ActivityThread( 3272): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1988)
E/ActivityThread( 3272): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.initialize(BluetoothManager.java:275)
E/ActivityThread( 3272): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.bind(BluetoothManager.java:103)
E/ActivityThread( 3272): 	at io.jxcore.node.ConnectivityMonitor.start(ConnectivityMonitor.java:75),
E/ActivityThread( 3272): 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:90)
E/ActivityThread( 3272): 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
E/ActivityThread( 3272): 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
E/ActivityThread( 3272): 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
E/ActivityThread( 3272): 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
E/ActivityThread( 3272): 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
E/ActivityThread( 3272): 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
E/ActivityThread( 3272): 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
E/ActivityThread( 3272): 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
E/ActivityThread( 3272): ,	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
E/ActivityThread( 3272): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3272): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread( 3272): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/AndroidRuntime( 3890): Calling main entry com.android.commands.pm.Pm,
W/QCamera2Factory(  287): getCameraInfo: E, camera_id = 0
W/QCamera2Factory(  287): getCameraInfo: X,
W/PCWCLIENTTRACE_AccountUtil( 3407): [hasSamungAccount] - No Samsung Account
W/QCamera2Factory(  287): getCameraInfo: E, camera_id = 1,
W/QCamera2Factory(  287): getCameraInfo: X
,D/PersonaManagerService( 1018): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
,D/PackageManager( 1018): START PACKAGE DELETE: observer{267971309}
D/PackageManager( 1018): pkg{<packageName>}
D/PackageManager( 1018): user{0}
D/PackageManager( 1018): caller{2000}
D/PackageManager( 1018): flags{2}
,D/PersonaManagerService( 1018): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService( 1018): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 1018): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
D/PackageManager( 1018): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,D/PackageManagerService( 1018): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManager( 1018): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManagerService( 1018): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy( 1018): getApplicationUninstallationEnabled
D/ApplicationPolicy( 1018): getApplicationUninstallationEnabled :  enabled true
,D/PackageManager( 1018): !@killApplicatoin: 10174, uninstall pkg
,I/ActivityManager( 1018): Force stopping com.test.thalitest appid=10174 user=-1: uninstall pkg
,I/ActivityManager( 1018): Killing 3272:com.test.thalitest/u0a174 (adj 9): stop com.test.thalitest cause uninstall pkg
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_3173/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 4029): TimaSignature is unavailable
D/ActivityThread( 4029): Added TimaKeyStore provider
,E/        ( 3707): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3707): took 0.523750ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3707): Bitmap=0xb8293af0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8293db0 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3707): Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,I/AMMetaDataParserService( 3707): Resource data:Loop for running activitycom.android.dialer.DialtactsActivity
,I/AMMetaDataParserService( 3707): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3707): getResourcePackageName:assistant
I/AMMetaDataParserService( 3707): Resource data:2131034113
,W/PackageSettings( 1018): Skipping PackageSetting{187135e0 com.example.hello/10175} due to missing metadata
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 3407): [GetString-S]
,I/AMMetaDataParserService( 3707): getResourceName:com.android.contacts:xml/assistant_main
I/AMMetaDataParserService( 3707): getResourceTypeNamexml
E/        ( 3707): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,I/GFX raster( 3707): took 0.820157ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3707): Bitmap=0xb8276898 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8291f80 counterpartCT=4 counterpartW=96 counterparth=96
,I/GCoreUlr( 1691): Unbound from all location providers
,I/ReactiveServiceManager( 3407): Supported : 1
,D/QSEECOMAPI: ( 1018): QSEECom_get_handle sb_length = 0x2040
,D/QSEECOMAPI: ( 1018): App is not loaded in QSEE
,I/AMMetaDataParserService( 3707): Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
,D/QSEECOMAPI: ( 1018): Loaded image: APP id = 10
,E/        ( 3707): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,D/QSEECOMAPI: ( 1018): QSEECom_dealloc_memory 
D/QSEECOMAPI: ( 1018): QSEECom_shutdown_app, app_id = 10
,E/terrier ( 1018): handleString: Failed to handle string(-4)
E/terrier ( 1018): Java_com_android_server_ReactiveService_GetString: error code = [-4]
D/PCWCLIENTTRACE_SecurePreferencesJNI( 3407): getString is null
I/PCWCLIENTTRACE_SecurePreferencesJNI( 3407): [GetString-E]
,I/GFX raster( 3707): took 1.048489ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3707): Bitmap=0xb8276898 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8293de0 counterpartCT=4 counterpartW=96 counterparth=96
,I/PCWCLIENTTRACE_PushUtil( 3407): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 3407): sales region : global
I/PCWCLIENTTRACE_PushUtil( 3407): getPushTypeList : [SPP, GCM]
,E/PCWCLIENTTRACE_PCWHandler( 3407): [ensureRegistration] - No Samsung account
,I/AMMetaDataParserService( 3707): Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,E/SQLiteLog( 1681): (10) POSIX Error : 11 SQLite Error : 3850
,E/        ( 3707): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3707): took 0.683646ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3707): Bitmap=0xb82936b8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb82772b8 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3707): Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,E/        ( 3707): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3707): took 1.242343ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3707): Bitmap=0xb8293820 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb82955b8 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3707): Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,E/        ( 3707): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3707): took 1.411875ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3707): Bitmap=0xb8296388 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8296698 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3707): Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,E/        ( 3707): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3707): took 0.643282ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3707): Bitmap=0xb82924e0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8296f30 counterpartCT=4 counterpartW=96 counterparth=96
,I/art     ( 1018): Explicit concurrent mark sweep GC freed 37562(2MB) AllocSpace objects, 9(144KB) LOS objects, 33% free, 30MB/45MB, paused 2.709ms total 172.518ms
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/AMMetaDataParserService( 3707): Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,D/SecurityLogAgent:SEDenialService( 1018): Got CLOSE_WRITE Event sk.log
,E/        ( 3707): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3707): took 0.735937ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3707): Bitmap=0xb82933c0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8293db0 counterpartCT=4 counterpartW=96 counterparth=96
E/Zygote  ( 4054): MountEmulatedStorage()
E/Zygote  ( 4054): v2
I/libpersona( 4054): KNOX_SDCARD checking this for 10146
I/libpersona( 4054): KNOX_SDCARD not a persona
I/SELinux ( 4054): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 4054): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/ActivityManager( 1018): Start proc com.android.exchange for broadcast com.android.exchange/.service.ExchangeBroadcastReceiver: pid=4054 uid=10146 gids={50146, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
E/SELinux ( 4054): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,I/ActivityManager( 1018): Killing 3158:com.sec.esdk.elm/u0a94 (adj 15): empty #31
,I/AMMetaDataParserService( 3707): Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,W/Settings( 3753): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/PCWCLIENTTRACE_AccountAppFacade2_0( 3407): unregister AuthInfo UpdateReceiver v2.0
,D/SecurityLogAgent:SEDenialService( 1018): Got CLOSE_WRITE Event sk.log
,I/Babel_Crash( 3753): startup - clean
,E/Zygote  ( 4071): MountEmulatedStorage()
E/Zygote  ( 4071): v2
I/libpersona( 4071): KNOX_SDCARD checking this for 10031
I/libpersona( 4071): KNOX_SDCARD not a persona
,I/SELinux ( 4071): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,I/SELinux ( 4071): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 4071): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
D/TimaKeyStoreProvider( 4054): TimaSignature is unavailable
D/ActivityThread( 4054): Added TimaKeyStore provider
,I/ActivityManager( 1018): Start proc com.vlingo.midas for broadcast com.vlingo.midas/com.vlingo.core.facade.lmtt.LmttReceiver: pid=4071 uid=10031 gids={50031, 9997, 1028, 1015, 3003, 3002, 3001} abi=armeabi-v7a
D/BadgeProvider( 4029): onCreate
D/BadgeProvider( 4029): DatabaseHelper
,I/ActivityManager( 1018): Killing 3237:com.samsung.android.intelligenceservice/u0a3 (adj 15): empty #31
,I/ActivityManager( 1018): Force stopping com.test.thalitest appid=10174 user=0: pkg removed
,E/        ( 3707): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3707): took 0.537812ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3707): Bitmap=0xb8293af0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8295460 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3707): Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,I/Babel   ( 3753): deleted: false for 0
,E/JavaBinder( 1018): !!! FAILED BINDER TRANSACTION !!!
,D/TimaKeyStoreProvider( 4071): TimaSignature is unavailable
,I/AMMetaDataParserService( 3707): getResourcePackageName:com.samsung.android.multiuser.install_only_owner
I/AMMetaDataParserService( 3707): Resource data:Loop for running activitycom.android.contacts.activities.ContactSelectionActivity
I/AMMetaDataParserService( 3707): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionTabActivity
I/AMMetaDataParserService( 3707): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionGroupSelectionActivity
I/AMMetaDataParserService( 3707): Resource data:Loop for running activitycom.android.contacts.DialtactsActivity
I/AMMetaDataParserService( 3707): Resource data:Loop for running activitycom.android.contacts.RecentCallsListActivity
I/AMMetaDataParserService( 3707): Resource data:Loop for running activitycom.android.contacts.activities.CallLogActivity
I/AMMetaDataParserService( 3707): Resource data:Loop for running activitycom.android.contacts.ContactsListActivity
I/AMMetaDataParserService( 3707): Resource data:Loop for running activitycom.android.contacts.activities.ContactsFrontDoor
I/AMMetaDataParserService( 3707): Resource data:Loop for running activitycom.android.contacts.DialtactsContactsEntryActivity
I/AMMetaDataParserService( 3707): Resource data:Loop for running activitycom.samsung.contacts.activities.PeopleActivity
I/AMMetaDataParserService( 3707): Resource data:Loop for running activitycom.android.contacts.activities.JoinContactActivity
I/AMMetaDataParserService( 3707): Resource data:Loop for running activitycom.android.contacts.preference.ContactsPreferenceActivity
I/AMMetaDataParserService( 3707): Resource data:Loop for running activitycom.android.contacts.common.list.AccountFilterActivity
I/AMMetaDataParserService( 3707): Resource data:Loop for running activitycom.android.contacts.common.list.CustomContactListFilterActivity
I/AMMetaDataParserService( 3707): Resource data:Loop for running activitycom.android.contacts.activities.ShowOrCreateActivity
I/AMMetaDataParserService( 3707): Resource data:Loop for running activitycom.android.contacts.activities.GroupDetailActivity
D/ActivityThread( 4071): Added TimaKeyStore provider
I/AMMetaDataParserService( 3707): Resource data:Loop for running activitycom.android.contacts.activities.GroupEditorActivity
I/AMMetaDataParserService( 3707): Resource data:Loop for running activitycom.android.contacts.quickcontact.QuickContactActivity
I/AMMetaDataParserService( 3707): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3707): getResourcePackageName:com.sec.android.multiwindow.activity.STYLE
I/AMMetaDataParserService( 3707): Resource data:Loop for running activitycom.android.contacts.ContactShortcut
I/AMMetaDataParserService( 3707): Resource data:Loop for running activityalias.DialShortcut
I/AMMetaDataParserService( 3707): Resource data:Loop for running activityalias.MessageShortcut
I/AMMetaDataParserService( 3707): Resource data:Loop for running activitycom.android.dialer.CallDetailActivity
I/AMMetaDataParserService( 3707): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDetailDeleteActivity
I/AMMetaDataParserService( 3707): Resource data:Loop for running activitycom.android.contacts.activities.ContactDetailActivity
I/AMMetaDataParserService( 3707): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3707): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3707): getResourcePackageName:assistant
I/AMMetaDataParserService( 3707): Resource data:2131034112
,I/AMMetaDataParserService( 3707): getResourceName:com.android.contacts:xml/assistant_detail
I/AMMetaDataParserService( 3707): getResourceTypeNamexml
E/        ( 3707): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3707): took 0.614583ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3707): Bitmap=0xb8293820 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8296f40 counterpartCT=4 counterpartW=96 counterparth=96
,W/ActivityManager( 1018): CustomStartingWindow se packge removed so remove capture also
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,I/AMMetaDataParserService( 3707): Icon data: ResourceAdd to Favourites2131690170android.intent.assistant.detail.favorite2130837530
,E/SMD     (  304): DCD OFF
,E/        ( 3707): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3707): took 0.599167ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3707): Bitmap=0xb8293820 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8291ce8 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3707): Icon data: ResourceRemove from Favourites2131690212android.intent.assistant.detail.favorite2130837530
,I/InputReader( 1018): Reconfiguring input devices.  changes=0x00000010
,E/SamsungIME( 1796): mOCRHelper is null
,W/GeofencerStateMachine( 1691): Ignoring removeGeofence because network location is disabled.
,E/        ( 3707): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3707): took 0.702031ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3707): Bitmap=0xb82963d0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb82988f8 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3707): Icon data: ResourceEdit2131690192android.intent.assistant.detail.edit2130837529
,W/ResourcesManager( 4071): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,W/ResourcesManager( 4054): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,D/RegisteredComponentCache( 1451): Collect Tech packages for Knox
,D/PersonaManager( 1451): isKioskContainerExistOnDevice
,D/BadgeProvider( 4029): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/SecContentProvider2( 1018): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1018): mCursor = null
,V/NetworkStats( 1018): removeUidsLocked() for UIDs [10174]
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
V/NetworkStats( 1018): performPollLocked(flags=0x3)
,D/NetworkStatsFactory( 1018): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1018): UpdateStatsForKnox main else ---
,W/ActivityManager( 1018): getTasks: caller 10145 does not hold GET_TASKS; limiting output
,V/NetworkStats( 1018): performPollLocked() took 15ms
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.ssrm.I.m:-1 com.android.server.ssrm.J.run:-1 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 
,I/Process ( 3988): Sending signal. PID: 3988 SIG: 9
,D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
E/        ( 3707): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3707): took 0.629219ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3707): Bitmap=0xb7ec3610 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7fb1498 counterpartCT=4 counterpartW=96 counterparth=96
,D/PersonaManager( 1451): isKioskContainerExistOnDevice
,D/RegisteredServicesCache( 1451): empty dynamic service
,I/ActivityManager( 1018): Process com.android.email (pid 3988)(adj 9) has died(88,1106)
,I/AMMetaDataParserService( 3707): Icon data: ResourceDelete2131690186android.intent.assistant.detail.delete2130837528
,D/RCPManagerService( 1018): PackageReceiver onReceive()
I/HarmonyEASService( 1018): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,D/KnoxMUMContainerPolicy( 1018): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
I/OTPFW   ( 1018): PackageRemovalReceiver::onReceive Enter
,D/OTPFW   ( 1018): OtpDbHelper::getInstance New instance created
,D/OTPFW   ( 1018): DBIntegrity::getInstance - New instance created
,D/SSRM:n  ( 1018): SIOP:: AP = 410
,I/GCoreUlr( 1691): DispatchingService.onDestroy()
,D/EnterpriseDeviceManagerService( 1018): Package has changed for user 0
D/EnterpriseDeviceManagerService( 1018): Admin package name: com.google.android.gms
W/TextServicesManagerService( 1018): no available spell checker services found
,I/GCoreUlr( 1691): Unbound from all location providers
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/OTPFW   ( 1018): PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10174 container id = 0
,I/OTPFW   ( 1018): ProvisionData::getAllEntries Enter
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,E/OTPFW   ( 1018): ProvisionData::getAllEntries Table is empty
,D/BackupManagerService( 1018): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,D/JobSchedulerService( 1018): Receieved: android.intent.action.PACKAGE_REMOVED
,V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1018): uID is 10174
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.exchange/com.android.exchange.service.ExchangeBroadcastProcessorService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,V/EnterpriseBillingPolicy( 1018): Removed Packageuid is0
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
V/EnterpriseBillingPolicyStorage( 1018): getProfileForApplication - enter
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.exchange, destAppInfo.processName = com.android.exchange
V/EnterpriseBillingPolicyStorage( 1018): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1018): getBillingProfileForVpnEngine - start - com.test.thalitest
,V/EnterpriseBillingPolicyStorage( 1018): getBillingProfileForVpnEngine - end - null
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4092): MountEmulatedStorage(),
,I/libpersona( 4092): KNOX_SDCARD checking this for 1000
E/Zygote  ( 4092): v2
I/libpersona( 4092): KNOX_SDCARD not a persona,
I/SELinux ( 4092): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,I/SELinux ( 4092): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 4092): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,I/ActivityManager( 1018): Start proc com.sec.android.app.SecSetupWizard for broadcast com.sec.android.app.SecSetupWizard/.SetupIntentReceiver: pid=4092 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
V/EnterpriseBillingPolicy( 1018): uID is 10174
V/EnterpriseBillingPolicy( 1018): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1018): getProfileForApplication - enter
D/SSRM:aZ ( 1018): MSG_TYPE_APP_REMOVED::
,V/EnterpriseBillingPolicyStorage( 1018): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1018): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage( 1018): getBillingProfileForVpnEngine - end - null
,I/DBG_DM  ( 3102): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 5 sec
,I/ActivityManager( 1018): Killing 3287:com.samsung.android.scloud.backup/u0a60 (adj 15): empty #31
,I/art     ( 1018): Explicit concurrent mark sweep GC freed 21622(1177KB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 30MB/45MB, paused 3.606ms total 289.754ms
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4108): MountEmulatedStorage()
E/Zygote  ( 4108): v2
I/libpersona( 4108): KNOX_SDCARD checking this for 10145
I/libpersona( 4108): KNOX_SDCARD not a persona
,D/TimaKeyStoreProvider( 4092): TimaSignature is unavailable
,D/ActivityThread( 4092): Added TimaKeyStore provider
,I/SELinux ( 4108): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,I/ActivityManager( 1018): Start proc com.android.email for content provider com.android.email/.provider.EmailProvider: pid=4108 uid=10145 gids={50145, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a,
,I/SELinux ( 4108): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 4108): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ResourceType( 1018): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,D/TimaKeyStoreProvider( 4108): TimaSignature is unavailable
,D/ActivityThread( 4108): Added TimaKeyStore provider
,W/VideoCapabilities( 3753): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager( 1018): Killing 3305:com.sec.factory.camera/1000 (adj 15): empty #31
,W/AudioCapabilities( 3753): Unsupported mime audio/evrc
,W/AudioCapabilities( 3753): Unsupported mime audio/qcelp
,W/ResourcesManager( 4108): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 4108): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4108): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 4108): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4108): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/PackageManager( 1018): delete codoeFile: 
,D/AASAuninstall( 1018): userId = 0, info.removedAppID = 10174, info.uid = 10174, packageName = com.test.thalitest
I/AASA_removePackage( 1018): UID=10174 Target=com.test.thalitest
,D/PackageManager( 1018): result of delete: 1{267971309}
,D/StatusBar.NetworkController( 1188): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1188): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1188): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1188): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1188): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1188): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/AndroidRuntime( 3890): Shutting down VM
,W/AudioCapabilities( 3753): Unsupported mime audio/mpeg-L1
,W/AudioCapabilities( 3753): Unsupported mime audio/mpeg-L2
,I/AMMetaDataParserService( 3707): Resource data:Loop for running activitycom.samsung.contacts.detail.SelectContactInfoActivity
I/AMMetaDataParserService( 3707): Resource data:Loop for running activitycom.android.contacts.activities.ConfirmAddDetailActivity
I/AMMetaDataParserService( 3707): Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorAccountsChangedActivity
I/AMMetaDataParserService( 3707): Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorActivity
I/AMMetaDataParserService( 3707): Resource data:Loop for running activitycom.samsung.contacts.activities.RingtoneRecommendationHelperActivity
I/AMMetaDataParserService( 3707): Resource data:Loop for running activitycom.samsung.contacts.editor.AddAnotherFieldDialogActivity
I/AMMetaDataParserService( 3707): Resource data:Loop for running activitycom.android.contacts.activities.AttachPhotoActivity
I/AMMetaDataParserService( 3707): Resource data:Loop for running activitycom.android.contacts.activities.PhotoSelectionActivity
I/AMMetaDataParserService( 3707): Resource data:Loop for running activitycom.android.contacts.common.vcard.ImportVCardActivity
I/AMMetaDataParserService( 3707): Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportVCardPreviewActivity
I/AMMetaDataParserService( 3707): Resource data:Loop for running activitycom.android.contacts.common.vcard.NfcImportVCardActivity
I/AMMetaDataParserService( 3707): Resource data:Loop for running activitycom.android.contacts.common.vcard.CancelActivity
I/AMMetaDataParserService( 3707): Resource data:Loop for running activitycom.android.contacts.common.vcard.SelectAccountActivity
I/AMMetaDataParserService( 3707): Resource data:Loop for running activitycom.android.contacts.common.vcard.ExportVCardActivity
I/AMMetaDataParserService( 3707): Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportFinishActivity
I/AMMetaDataParserService( 3707): Resource data:Loop for running activitycom.samsung.contacts.activities.SIMContactSelectionActivity
I/AMMetaDataParserService( 3707): Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbers
I/AMMetaDataParserService( 3707): Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbersTabActivity
I/AMMetaDataParserService( 3707): Resource data:Loop for running activitycom.samsung.contacts.activities.VerizonBackupAssistantActivity
I/AMMetaDataParserService( 3707): Resource data:Loop for running activitycom.android.contacts.widget.PinnedHeaderListDemoActivity
I/AMMetaDataParserService( 3707): Resource data:Loop for running activitycom.android.contacts.NonPhoneActivity
I/AMMetaDataParserService( 3707): Resource data:Loop for running activitycom.samsung.contacts.favorite.FavoriteSelectionActivity
I/AMMetaDataParserService( 3707): Resource data:Loop for running activitycom.samsung.contacts.detail.SetDefaultActivity
I/AMMetaDataParserService( 3707): Resource data:Loop for running activitycom.samsung.contacts.group.GroupChangeOrderActivity
I/AMMetaDataParserService( 3707): Resource data:Loop for running activitycom.samsung.contacts.editor.EditGroupSelectionActivity
I/AMMetaDataParserService( 3707): Resource data:Loop for running activitycom.samsung.contacts.group.GroupMultiSelectionActivity
I/AMMetaDataParserService( 3707): Resource data:Loop for running activitycom.samsung.contacts.emergency.InteractionEmergencyMessageActivity
I/AMMetaDataParserService( 3707): Resource data:Loop for running activitycom.samsung.contacts.emergency.EmergencyMessageContactCreateActivity
I/AMMetaDataParserService( 3707): Resource data:Loop for running activitycom.samsung.contacts.emergency.EmergencyContactListDialogActivity
I/AMMetaDataParserService( 3707): Resource data:Loop for running activitycom.samsung.contacts.group.SubGroupDetailActivity
I/AMMetaDataParserService( 3707): Resource data:Loop for running activitycom.samsung.contacts.activities.GroupListActivity
I/AMMetaDataParserService( 3707): Resource data:Loop for running activit,ycom.samsung.dialer.calllog.CallDurationActivity
I/AMMetaDataParserService( 3707): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDurationTabActivity
I/AMMetaDataParserService( 3707): Resource data:Loop for running activitycom.samsung.contacts.detail.LinkedContactActivity
I/AMMetaDataParserService( 3707): Resource data:Loop for running activitycom.samsung.dialer.impl.DialerTutorialActivity
I/AMMetaDataParserService( 3707): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpPeopleActivity
I/AMMetaDataParserService( 3707): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyPeopleActivity
I/AMMetaDataParserService( 3707): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpInteractionTabActivity
I/AMMetaDataParserService( 3707): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyInteractionTabActivity
I/AMMetaDataParserService( 3707): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpSpeedDialActivity
I/AMMetaDataParserService( 3707): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactEditorActivity
I/AMMetaDataParserService( 3707): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactSelectionActivity
I/AMMetaDataParserService( 3707): Resource data:Loop for running activitycom.samsung.contacts.activities.EasyPeopleActivity
I/AMMetaDataParserService( 3707): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3707): getResourcePackageName:assistant
I/AMMetaDataParserService( 3707): Resource data:2131034113
,W/AudioCapabilities( 3753): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 3753): Unsupported mime audio/x-ima
,W/AudioCapabilities( 3753): Unsupported mime audio/qcelp
,I/AMMetaDataParserService( 3707): getResourceName:com.android.contacts:xml/assistant_main
I/AMMetaDataParserService( 3707): getResourceTypeNamexml
,E/        ( 3707): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3707): took 0.857917ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3707): Bitmap=0xb8275a60 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8296388 counterpartCT=4 counterpartW=96 counterparth=96
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/AudioCapabilities( 3753): Unsupported mime audio/evrc
,I/ActivityManager( 1018): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.BootReceiver: pid=4124 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/ActivityManager( 1018): Killing 3332:com.fmm.dm/1000 (adj 15): empty #31
,E/Zygote  ( 4124): MountEmulatedStorage()
E/Zygote  ( 4124): v2
I/libpersona( 4124): KNOX_SDCARD checking this for 1000
I/libpersona( 4124): KNOX_SDCARD not a persona
,I/SELinux ( 4124): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/AMMetaDataParserService( 3707): Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
,I/SELinux ( 4124): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 4124): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/        ( 3707): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96,
,I/GFX raster( 3707): took 0.830677ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3707): Bitmap=0xb8275a60 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8276898 counterpartCT=4 counterpartW=96 counterparth=96
W/VideoCapabilities( 3753): Unsupported mime video/wvc1
W/VideoCapabilities( 3753): Unsupported mime video/x-ms-wmv
,D/PackageManager( 1018): [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest},
D/PackageManager( 1018): userId{-1}
D/PackageManager( 1018): andCode{true}
,I/AMMetaDataParserService( 3707): Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,W/VideoCapabilities( 3753): Unrecognized profile/level 32768/2 for video/mp4v-es
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/VideoCapabilities( 3753): Unsupported mime video/wvc1
,W/VideoCapabilities( 3753): Unsupported mime video/x-ms-wmv
,D/TimaKeyStoreProvider( 4124): TimaSignature is unavailable
,W/VideoCapabilities( 3753): Unsupported mime video/x-ms-wmv7
D/ActivityThread( 4124): Added TimaKeyStore provider
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/VideoCapabilities( 3753): Unsupported mime video/x-ms-wmv8
,W/VideoCapabilities( 3753): Unsupported mime video/mp43
,W/ResourcesManager( 1018): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1018): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1018): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/VideoCapabilities( 3753): Unsupported mime video/sorenson
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,W/VideoCapabilities( 3753): Unsupported mime video/mp4v-esdp
,E/Zygote  ( 4139): MountEmulatedStorage()
E/Zygote  ( 4139): v2
I/libpersona( 4139): KNOX_SDCARD checking this for 10004
I/libpersona( 4139): KNOX_SDCARD not a persona
,I/SELinux ( 4139): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 4139): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 4139): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/        ( 3707): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/ActivityManager( 1018): Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=4139 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,I/GFX raster( 3707): took 0.672135ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3707): Bitmap=0xb826e708 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7fb1498 counterpartCT=4 counterpartW=96 counterparth=96
,D/TaskPersister( 1018): removeObsoleteFile: deleting file=236_task.xml
,D/TaskPersister( 1018): removeObsoleteFile: deleting file=236_task_thumbnail.png
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,I/art     (  323): Explicit concurrent mark sweep GC freed 8747(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 656us total 23.260ms
,I/AMMetaDataParserService( 3707): Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,I/art     (  323): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 629us total 22.455ms
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,D/TimaKeyStoreProvider( 4139): TimaSignature is unavailable
,D/ActivityThread( 4139): Added TimaKeyStore provider
,D/WallpaperManager( 1497): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true,
,I/art     (  323): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 619us total 17.784ms
D/WallpaperManager( 1497): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,W/art     ( 3890): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/VlingoApplication( 4071): VlingoApplication appVersion ='11.7.0.1.40254', coreVersion = '2.6.3.16956', ro.csc.sales_code=XEO
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/VideoCapabilities( 3753): Unsupported profile 4 for video/mp4v-es
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,D/SecurityLogAgent( 4124): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 4124): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 4124): StateMachine : Current State = 1
D/SecurityLogAgent( 4124): BootReceiver : completed task. Failed to return wakelock . 
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/UsbSettingsManager( 1018): clearDefaults: com.test.thalitest
I/CrashAnrDetector( 1018): onPackageRemoved : com.test.thalitest
,W/libprocessgroup( 1018): failed to open /acct/uid_10003/pid_3237/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_10094/pid_3158/cgroup.procs: No such file or directory
,W/libprocessgroup( 1018): failed to open /acct/uid_10060/pid_3287/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_3305/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_3332/cgroup.procs: No such file or directory
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4162): MountEmulatedStorage()
I/libpersona( 4162): KNOX_SDCARD checking this for 10152
E/Zygote  ( 4162): v2
I/libpersona( 4162): KNOX_SDCARD not a persona
I/SELinux ( 4162): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 4162): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 4162): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,I/ActivityManager( 1018): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=4162 uid=10152 gids={50152, 9997, 1023} abi=armeabi-v7a
,I/ActivityManager( 1018): Killing 3347:com.samsung.android.app.watchmanagerstub/u0a100 (adj 15): empty #31
,I/ActivityManager( 1018): Killing 3382:com.samsung.helphub/1000 (adj 15): empty #31
,W/VideoCapabilities( 3753): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 3753): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 3753): Unrecognized profile 2130706433 for video/avc
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,D/TimaKeyStoreProvider( 4162): TimaSignature is unavailable
,D/ActivityThread( 4162): Added TimaKeyStore provider
,E/        ( 3707): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3707): took 0.615469ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3707): Bitmap=0xb8296388 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8276970 counterpartCT=4 counterpartW=96 counterparth=96
,I/VlingoAndroidCore( 4071): AppName: SamsungTproject, Core: 2.6.3.16956, SDK: 2.0.2173, EDM:16956
,W/VideoCapabilities( 3753): Unrecognized profile 2130706433 for video/avc
,I/AMMetaDataParserService( 3707): Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,E/        ( 3707): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3707): took 0.882812ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3707): Bitmap=0xb8276898 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7fb1498 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3707): Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,W/libprocessgroup( 1018): failed to open /acct/uid_10100/pid_3347/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_3382/cgroup.procs: No such file or directory
,I/vclib   ( 3753): onServiceConnected
,W/Babel   ( 3753): Attempted to change video mute state without an active call.
,D/BadgeProvider( 4029): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,E/SQLiteLog( 4162): (284) automatic index on shooting_modes(title_id)
E/        ( 3707): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3707): took 1.264792ms for 96*96 texture 0,
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3707): Bitmap=0xb7ec3610 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8276970 counterpartCT=4 counterpartW=96 counterparth=96
,E/Zygote  ( 4184): MountEmulatedStorage()
E/Zygote  ( 4184): v2
I/libpersona( 4184): KNOX_SDCARD checking this for 10035
I/libpersona( 4184): KNOX_SDCARD not a persona
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,I/AMMetaDataParserService( 3707): Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
I/SELinux ( 4184): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/ActivityManager( 1018): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=4184 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1018): Killing 3425:com.samsung.android.scloud.sync/u0a62 (adj 15): empty #31
,I/SELinux ( 4184): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 4184): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): getTasks: caller 10146 does not hold GET_TASKS; limiting output
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.ShootingModesService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.android.provider.shootingmodeprovider, destAppInfo.processName = com.samsung.android.provider.shootingmodeprovider
,E/        ( 3707): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3707): took 0.684896ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3707): Bitmap=0xb7fb1498 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8276970 counterpartCT=4 counterpartW=96 counterparth=96
,I/Process ( 4054): Sending signal. PID: 4054 SIG: 9
,D/Launcher.Model( 1497): reloadBadges entered.
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 4184): TimaSignature is unavailable
D/BadgeProvider( 4029): sendNotify entered. [uri] : content://com.sec.badge/apps/1
,D/BadgeProvider( 4029): sendNotify, [notify] : null
D/BadgeProvider( 4029): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 4029): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 4029): update, [UpdateCount] : 1
D/ActivityThread( 4184): Added TimaKeyStore provider,
,I/AMMetaDataParserService( 3707): Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
E/Zygote  ( 4203): MountEmulatedStorage()
E/Zygote  ( 4203): v2
I/libpersona( 4203): KNOX_SDCARD checking this for 1000
,I/libpersona( 4203): KNOX_SDCARD not a persona
,I/SELinux ( 4203): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
I/ActivityManager( 1018): Start proc com.sec.modem.settings for broadcast com.sec.modem.settings/.cplogging.SilentLogReceiver: pid=4203 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/SELinux ( 4203): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 4203): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/lowmemorykiller(  255): Error writing /proc/4054/oom_score_adj; errno=22
,D/TimaKeyStoreProvider( 4203): TimaSignature is unavailable
D/ActivityThread( 4203): Added TimaKeyStore provider
,I/ActivityManager( 1018): Killing 3446:com.fmm.ds/1000 (adj 15): empty #31
,D/VlingoApplication( 4071): sac sec ensureCacheEmpty() car_iux_tts_cacheing_required set to false
,D/VlingoApplication( 4071): sac sec ensureCacheEmpty() purged 0 historically cached TTS files
,W/libprocessgroup( 1018): failed to open /acct/uid_10062/pid_3425/cgroup.procs: No such file or directory
,I/ActivityManager( 1018): Process com.android.exchange (pid 4054)(adj 15) has died(82,1108)
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4218): MountEmulatedStorage(),
E/Zygote  ( 4218): v2
I/libpersona( 4218): KNOX_SDCARD checking this for 1101
I/libpersona( 4218): KNOX_SDCARD not a persona
,I/SELinux ( 4218): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/ActivityManager( 1018): Start proc org.simalliance.openmobileapi.service for broadcast org.simalliance.openmobileapi.service/.SmartcardServiceBootCompletedBroadcastReceiver: pid=4218 uid=1101 gids={41101, 9997} abi=armeabi-v7a,
I/SELinux ( 4218): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 4218): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
E/        ( 3707): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3707): took 0.767344ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3707): Bitmap=0xb8276970 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8258688 counterpartCT=4 counterpartW=96 counterparth=96
,D/DialogFlow( 4071): initQueue()
,I/AMMetaDataParserService( 3707): Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,D/TimaKeyStoreProvider( 4218): TimaSignature is unavailable
,D/ActivityThread( 4218): Added TimaKeyStore provider,
,I/AMMetaDataParserService( 3707): Resource data:Loop for running activitycom.samsung.contacts.interactions.EasyInteractionTabActivity
I/AMMetaDataParserService( 3707): Resource data:Loop for running activitycom.samsung.dialer.calllog.LogsFindoSearchResultsActivity
I/AMMetaDataParserService( 3707): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3707): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3707): Resource data:Loop for running activitycom.samsung.dialer.dialpad.RegularSearchActivity
I/AMMetaDataParserService( 3707): Resource data:Loop for running activitycom.samsung.dialer.interaction.InteractionRecentActivity
I/AMMetaDataParserService( 3707): Resource data:Loop for running activitycom.samsung.contacts.editor.SamsungAccountValidationCheckActivity
I/AMMetaDataParserService( 3707): Resource data:Loop for running activitycom.samsung.contacts.autolink.AutoLinkActivity
I/AMMetaDataParserService( 3707): Resource data:Loop for running activitycom.samsung.contacts.activities.EmergencyPeopleActivity
I/AMMetaDataParserService( 3707): Resource data:Loop for running activitycom.samsung.contacts.speeddial.SpeedDialActivity
I/AMMetaDataParserService( 3707): Resource data:Loop for running activitycom.samsung.contacts.businesscard.BusinesscardListActivity
I/AMMetaDataParserService( 3707): Resource data:Loop for running activitycom.samsung.contacts.businesscard.BusinesscardViewer
I/AMMetaDataParserService( 3707): Resource data:Loop for running activitycom.samsung.dialer.callmessage.CallMessageActivity
W/ContextImpl( 3707): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3707): Resource data:Loop for running activitycom.samsung.dialer.callmessage.RecentCallMessageActivity
I/AMMetaDataParserService( 3707): Resource data:Loop for running activitycom.samsung.dialer.callmessage.PhrasesEditActivity
I/AMMetaDataParserService( 3707): Resource data:Loop for running activitycom.samsung.dialer.callmessage.PhrasesDeleteActivity
I/AMMetaDataParserService( 3707): Resource data:Loop for running activitycom.samsung.dialer.callmessage.CallMessageEditActivity
I/AMMetaDataParserService( 3707): Resource data:Loop for running activitycom.samsung.contacts.emergency.MyEmergencyInfoDetailActivity
I/AMMetaDataParserService( 3707): Resource data:Loop for running activitycom.samsung.contacts.emergency.MyEmergencyInfoEditorActivity
I/AMMetaDataParserService( 3707): Resource data:Loop for running activitycom.samsung.contacts.activities.ScoverFavoritesActivity
I/AMMetaDataParserService( 3707): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3707): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 3707): Resource data:Loop for running activitycom.samsung.contacts.activities.ScoverSelectNumberActivity
I/AMMetaDataParserService( 3707): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3707): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 3707): Resource data:Loop for running activitycom.samsung.contacts.detail.ShowMyProfileActivity
I/AMMetaDataParserService( 3707): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionProfileWhiteListActivity
,E/SPPClientService( 4184): ============PushLog. commonIsShipBuild. stop!,
E/SPPClientService( 4184): [PushClientApplication] Push log off : This is Ship build version
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_3446/cgroup.procs: No such file or directory
,E/SPPClientService( 4184): [SystemStateMoniter] Action Name : android.intent.action.BOOT_COMPLETED
E/SPPClientService( 4184): [SystemStateMoniter] Current Time : 44143
,W/ResourcesManager( 4218): Asset path '/system/framework/org.simalliance.openmobileapi.jar' does not exist or contains no resources.
,I/CalendarProvider2( 3920): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,V/SmartcardService( 4218): main Received broadcast
V/SmartcardService( 4218): Starting smartcard service after boot completed
,D/ActivityManager( 1018): retrieveServiceLocked(): component = org.simalliance.openmobileapi.service/org.simalliance.openmobileapi.service.SmartcardService; callingUser = 0; userId(target) = 0
I/AMMetaDataParserService( 3707): Resource data:Loop for running activitycom.android.email.activity.setup.SSLCertValidationActivity
I/AMMetaDataParserService( 3707): Resource data:Loop for running activitycom.android.email.activity.EmailUpgradeKeystoreActivity
I/AMMetaDataParserService( 3707): Resource data:Loop for running activitycom.android.email.activity.SecurityCertificates
I/AMMetaDataParserService( 3707): Resource data:Loop for running activitycom.android.email.activity.Welcome
I/AMMetaDataParserService( 3707): Resource data:Loop for running activitycom.android.email.activity.UpgradeAccounts
I/AMMetaDataParserService( 3707): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupWizard
I/AMMetaDataParserService( 3707): Resource data:Loop for running activitycom.android.email.activity.setup.snc.VZWSetupWizard
I/AMMetaDataParserService( 3707): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncRestoreAccounts
I/AMMetaDataParserService( 3707): Resource data:Loop for running activitycom.android.email.activity.setup.snc.SncRestoreAccounts
I/AMMetaDataParserService( 3707): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncRestoreOptions
I/AMMetaDataParserService( 3707): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncNames
I/AMMetaDataParserService( 3707): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncExchangeAccounts
I/AMMetaDataParserService( 3707): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncAccountsLogin
I/AMMetaDataParserService( 3707): Resource data:Loop for running activitycom.android.email.activity.setup.LDAPClientSettings
I/AMMetaDataParserService( 3707): Resource data:Loop for running activitycom.android.email.activity.LDAPAccountsList
I/AMMetaDataParserService( 3707): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupBasics
I/AMMetaDataParserService( 3707): Resource data:Loop for running activitycom.android.email.DataConnection
I/AMMetaDataParserService( 3707): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupAccountType
I/AMMetaDataParserService( 3707): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupIncoming
I/AMMetaDataParserService( 3707): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupOutgoing
I/AMMetaDataParserService( 3707): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupExchange
I/AMMetaDataParserService( 3707): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupOptions
I/AMMetaDataParserService( 3707): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupNames
I/AMMetaDataParserService( 3707): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsXL
I/AMMetaDataParserService( 3707): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsAddRulesforFiltering
I/AMMetaDataParserService( 3707): Resource data:Loop for running activitycom.android.email.activity.setup.AddPrioritySenderActivity
I/AMMetaDataParserService( 3707): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSecurity
I/AMMetaDataParserService( 3707): Resource data:Loop for running activitycom.android.email.activity.setup.AccountPreSetup
I/AMMetaDataParserService( 3707): Resource data:Loop for running activitycom.android.email.messageview.SaveasActivity
I/AMMetaDataParserService( 3707): Resource data:Loop for running activitycom.android.email.activity.Debug
I/AMMetaDataParserService( 3707): Resource data:Loop for running activitycom.android.email,.activity.MessageListXL
I/AMMetaDataParserService( 3707): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3707): getResourcePackageName:assistant
I/AMMetaDataParserService( 3707): Resource data:2131165203
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ResourcesManager( 3707): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ResourcesManager( 3707): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = org.simalliance.openmobileapi.service, destAppInfo.processName = org.simalliance.openmobileapi.service
W/ResourcesManager( 3707): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 3707): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3707): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/ActivityManager( 1018): Killing 3462:com.sec.knox.foldercontainer/1000 (adj 15): empty #31,
,I/AMMetaDataParserService( 3707): getResourceName:com.android.email:xml/email_assistant_menu
I/AMMetaDataParserService( 3707): getResourceTypeNamexml
,I/ActivityManager( 1018): Killing 3482:com.sec.android.app.servicemodeapp/1000 (adj 15): empty #31
,E/        ( 3707): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.stk/com.android.stk.StkAppService; callingUser = 0; userId(target) = 0
,I/GFX construct_block_size_descriptor_2d second part( 3707): took 2.856772ms for 0*0 texture 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000,
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,D/SPPClientService( 4184): PushLog.txt file is not deleted.,
D/SPPClientService( 4184): PushLog.txt file is not deleted.
D/SPPClientService( 4184): ============PushLog. stop!
I/GFX generate_partition_tables( 3707): took 10.010783ms for 0*0 texture 0
,I/GFX raster( 3707): took 13.753075ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3707): Bitmap=0xb8294cd8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb8442280 counterpartCT=4 counterpartW=96 counterparth=96
,E/Zygote  ( 4236): MountEmulatedStorage()
E/Zygote  ( 4236): v2
I/libpersona( 4236): KNOX_SDCARD checking this for 10032
I/libpersona( 4236): KNOX_SDCARD not a persona
,I/SELinux ( 4236): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/AMMetaDataParserService( 3707): Icon data: ResourceDrawer menu2131363563com.android.email.intent.messagelistfragment.drawer2130837576,
,I/SELinux ( 4236): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SQLiteLog( 3707): (28) failed to open "/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase( 3707): Failed to open database '/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu'.
E/SQLiteDatabase( 3707): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3707): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3707): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 3707): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 3707): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 3707): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 3707): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 3707): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 3707): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 3707): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 3707): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 3707): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 3707): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 3707): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 3707): 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.addAMData(DatabaseHandler.java:63)
E/SQLiteDatabase( 3707): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.constructDBdata(AMMetaDataParserService.java:197)
E/SQLiteDatabase( 3707): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:87)
E/SQLiteDatabase( 3707): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 3707): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 3707): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 3707): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err( 3707): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/System.err( 3707): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/System.err( 3707): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
W/System.err( 3707): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
W/System.err( 3707): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
,W/System.err( 3707): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
W/System.err( 3707): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
W/System.err( 3707): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
W/System.err( 3707): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
W/System.err( 3707): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
W/System.err( 3707): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
W/System.err( 3707): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
W/System.err( 3707): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
W/System.err( 3707): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
W/System.err( 3707): 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.addAMData(DatabaseHandler.java:63)
W/System.err( 3707): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.constructDBdata(AMMetaDataParserService.java:197)
W/System.err( 3707): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:87)
,W/System.err( 3707): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/System.err( 3707): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3707): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3707): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ActivityManager( 1018): Start proc com.samsung.android.app.galaxyfinder:tagService for broadcast com.samsung.android.app.galaxyfinder/.tag.TagReadyReceiver: pid=4236 uid=10032 gids={50032, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,I/ActivityManager( 1018): Killing 3502:com.wssnps/1000 (adj 15): empty #31
,E/SELinux ( 4236): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL

```
