#### Test 50388019193a02f_thali01_samsung-SM-A500FU Logs


```
--------- beginning of main
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.dropbox.android, destAppInfo.processName = com.dropbox.android
--------- beginning of system
D/ActivityManager( 1018): startService callerProcessName:com.dropbox.android, calleePkgName: com.dropbox.android
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.dropbox.android/com.dropbox.android.exception.CrashUploaderService; callingUser = 0; userId(target) = 0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 3474): MountEmulatedStorage()
E/Zygote  ( 3474): v2
I/SELinux ( 3474): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 3474): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 3474): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1018): Start proc com.dropbox.android:crash_uploader for service com.dropbox.android/.exception.CrashUploaderService: pid=3474 uid=10092 gids={50092, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/libpersona( 3474): KNOX_SDCARD checking this for 10092
I/libpersona( 3474): KNOX_SDCARD not a persona
W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_2755/cgroup.procs: No such file or directory
E/        ( 1965): GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
I/GFX construct_block_size_descriptor_2d second part( 1965): took 2.384115ms for 0*0 texture 0
I/DBG_DM  ( 3176): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 0 sec
I/GFX generate_partition_tables( 1965): took 6.318386ms for 0*0 texture 0
I/GFX raster( 1965): took 11.330157ms for 176*144 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1965): Bitmap=0xb8229360 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b1, Counterpart=0xb8229300 counterpartCT=4 counterpartW=176 counterparth=144
D/ScoverManager( 1965): registerListener
D/CoverManagerWhiteLists( 1018): isAllowedToUse : SIGNATURE_MATCH
D/CoverManagerWhiteLists( 1018): isAllowedToUse : SIGNATURE_MATCH
D/CoverManager.StateNotifier( 1018): registerListenerCallback : binder = android.os.BinderProxy@5e12bf6, pid : 1965, uid : 1001, type : 1
D/TimaKeyStoreProvider( 3474): TimaSignature is unavailable
D/ActivityThread( 3474): Added TimaKeyStore provider
D/UserAnalysis.PlaceProvider( 3456): PlaceProvider onCreate()
D/InCall  ( 1965): InCallPresenter -  - Finished InCallPresenter.setUp
D/UserAnalysis.SecureDbManager( 3456): Key for secure DB is newly created
D/UserAnalysis.SecurePlaceDbHelper( 3456): SecurePlaceDbHelper() 
D/UserAnalysis( 3456): Create SecureDbHelper
D/IntelligenceServiceApplication( 3456): onCreate()
D/UserAnalysis.UserAnalysisBroadcastReceiver( 3456): Intent(action: android.intent.action.BOOT_COMPLETED) is received.
D/ActivityManager( 1018): startProcessLocked calleePkgName: com.samsung.android.scloud.backup, hostingType: broadcast
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 com.android.server.ssrm.ad.cB:-1 com.android.server.ssrm.ae.handleMessage:-1 android.os.Handler.dispatchMessage:102 android.os.Looper.loop:145 
D/IntelligenceServiceApplication( 3456): no applications having user consent for prediction
E/Zygote  ( 3496): MountEmulatedStorage()
I/libpersona( 3496): KNOX_SDCARD checking this for 10060
E/Zygote  ( 3496): v2
I/libpersona( 3496): KNOX_SDCARD not a persona
I/SELinux ( 3496): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1018): Start proc com.samsung.android.scloud.backup for broadcast com.samsung.android.scloud.backup/.SCloudBackupReceiver: pid=3496 uid=10060 gids={50060, 9997, 1028, 1015, 3003} abi=armeabi-v7a
I/ActivityManager( 1018): Killing 2838:flipboard.boxer.app/u0a99 (adj 15): empty #31
I/SELinux ( 3496): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 3496): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
I/com.dropbox.android.service.DropboxNetworkReceiver( 3375): Setting receiver enabled: false
V/PlaceDetection v1.0.19 ( 3456): [PlaceDetection::stopService] Service stopped.
I/DBG_FMMDS( 3432): [50.18.150420][Line:63][onCreate] onCreate Db Initialized
D/TimaKeyStoreProvider( 3496): TimaSignature is unavailable
D/ActivityThread( 3496): Added TimaKeyStore provider
I/DBG_FMMDS( 3432): [50.18.150420][Line:363][xdsGetAccount] UZnlD2ITkPmcCbh9srjpN/1auPpXZ1U0673eFrlr5G7ujCmOnoTUvn8Wy3q3+o8W
I/DBG_FMMDS( 3432): [50.18.150420][Line:279][xdsDefaultProfileCheckServerID] VG44Fy9kdMk+/k3D4uP4d3do/3rw5AoymvTy0wXAnzc=
I/DBG_FMMDS( 3432): [50.18.150420][Line:363][xdsGetAccount] UZnlD2ITkPmcCbh9srjpN/1auPpXZ1U0673eFrlr5G7ujCmOnoTUvn8Wy3q3+o8W
I/DBG_FMMDS( 3432): [50.18.150420][Line:376][xdsCheckSamsungAccountForChina] VG44Fy9kdMk+/k3D4uP4d3do/3rw5AoymvTy0wXAnzc=
I/DBG_FMMDS( 3432): [50.18.150420][Line:89][onReceive] Receive Intent : android.intent.action.BOOT_COMPLETED
I/DBG_FMMDS( 3432): [50.18.150420][Line:248][onReceive] XCOMMON_INTENT_NOTI_CALLLOG_CLICK
I/ActivityManager( 1018): Killing 2138:flipboard.app/u0a98 (adj 15): empty #31
I/FOTA_Client( 3241): [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
I/FOTA_Client( 3241): [com.sec.android.fotaclient.FotaUpdaterReceiver(93/onReceive)] Auto update settings is activated
I/FOTA_Client( 3241): [IlIlIIllllIllIIIIIll(81/llllIIIllIlIIIIllllI)] Polling time is vaild
W/FOTA_Client( 3241): [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
D/ActivityManager( 1018): startProcessLocked calleePkgName: com.google.android.onetimeinitializer, hostingType: broadcast
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 3520): MountEmulatedStorage()
E/Zygote  ( 3520): v2
I/libpersona( 3520): KNOX_SDCARD checking this for 10014
I/libpersona( 3520): KNOX_SDCARD not a persona
I/SELinux ( 3520): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 3520): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1018): Start proc com.google.android.onetimeinitializer for broadcast com.google.android.onetimeinitializer/.OneTimeInitializerReceiver: pid=3520 uid=10014 gids={50014, 9997} abi=armeabi-v7a
E/SELinux ( 3520): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1018): Killing 2264:com.sec.android.app.SecSetupWizard/1000 (adj 15): empty #31
W/ResourcesManager( 3307): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3307): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
V/PlaceDetection v1.0.19 ( 3456): [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
D/UserAnalysis.MyPlaceDbPreference( 3456): Constructor Preference
D/TimaKeyStoreProvider( 3520): TimaSignature is unavailable
D/ActivityThread( 3520): Added TimaKeyStore provider
I/sCloudBackupApp( 3496): sCloudBackupApp Version Info : 4.04.8.KK_APP
E/ActivityThread( 3375): Failed to find provider info for com.dropbox.carousel.CuOwnerCheckProvider
D/ActivityManager( 1018): startProcessLocked calleePkgName: com.samsung.android.scloud.sync, hostingType: broadcast
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 3537): MountEmulatedStorage()
E/Zygote  ( 3537): v2
I/libpersona( 3537): KNOX_SDCARD checking this for 10062
I/libpersona( 3537): KNOX_SDCARD not a persona
I/ActivityManager( 1018): Start proc com.samsung.android.scloud.sync for broadcast com.samsung.android.scloud.sync/com.sec.android.sCloudSync.Receivers.TimeChangedReceiver: pid=3537 uid=10062 gids={50062, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1018): Killing 2567:com.samsung.android.securitylogagent/1000 (adj 15): empty #31
I/LockPatternUtils( 1333): isSmartCardAuthenticationAvailable: false
V/OneTimeInitializerReceiver( 3520): OneTimeInitializerReceiver.onReceive
D/ActivityManager( 1018): startService callerProcessName:com.google.android.onetimeinitializer, calleePkgName: com.google.android.onetimeinitializer
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.onetimeinitializer/com.google.android.onetimeinitializer.OneTimeService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.onetimeinitializer, destAppInfo.processName = com.google.android.onetimeinitializer
W/libprocessgroup( 1018): failed to open /acct/uid_10099/pid_2838/cgroup.procs: No such file or directory
I/FactoryTestApp( 2617): [IPCWriterToSecPhoneService$disConnectSecPhoneService](3144)  
V/OneTimeService( 3520): OneTimeService.onHandleIntent
D/ActivityManager( 1018): startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.ClientIdService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
D/ActivityManager( 1018): startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.AppHiderService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
D/ActivityManager( 1018): startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.MccFallbackService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
D/ActivityManager( 1018): startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.MccOverrideService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
D/ActivityManager( 1018): startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.RlzPingIntentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
D/ActivityManager( 1018): startProcessLocked calleePkgName: com.samsung.hs20settings, hostingType: broadcast
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 3553): MountEmulatedStorage()
E/Zygote  ( 3553): v2
I/libpersona( 3553): KNOX_SDCARD checking this for 1000
I/libpersona( 3553): KNOX_SDCARD not a persona
W/libprocessgroup( 1018): failed to open /acct/uid_10098/pid_2138/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_2264/cgroup.procs: No such file or directory
I/ActivityManager( 1018): Start proc com.samsung.hs20settings for broadcast com.samsung.hs20settings/.WifiHs20BroadcastReceiver: pid=3553 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_2567/cgroup.procs: No such file or directory
I/SELinux ( 3537): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 3553): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 3553): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/SELinux ( 3537): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 3553): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
E/SELinux ( 3537): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 3553): TimaSignature is unavailable
D/ActivityThread( 3553): Added TimaKeyStore provider
D/TimaKeyStoreProvider( 3537): TimaSignature is unavailable
D/ActivityThread( 3537): Added TimaKeyStore provider
I/dbxyzptlk.db240408.D.h( 3375): Loading /data/data/com.dropbox.android/files/extracted_libs/lib_breakpadinstaller_1dc04d6d96cbb2962385ec13f5f77649aec85e95_arm
I/dbxyzptlk.db240408.D.h( 3375): Loading /data/data/com.dropbox.android/files/extracted_libs/lib_dbxfileobserver_59d9546785d1f42b870763ef906fd65c59b55c56_arm
I/dbxyzptlk.db240408.D.h( 3375): Loading /data/data/com.dropbox.android/files/extracted_libs/lib_dropboxsync_cf9d7b2df44b0b78b581431109195f96d492fc70_arm
D/ActivityManager( 1018): startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
I/Hs20UtilService( 3553): onCreate
D/ActivityManager( 1018): startProcessLocked calleePkgName: com.samsung.klmsagent, hostingType: broadcast
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 3584): MountEmulatedStorage()
I/libpersona( 3584): KNOX_SDCARD checking this for 10019
E/Zygote  ( 3584): v2
I/libpersona( 3584): KNOX_SDCARD not a persona
I/SELinux ( 3584): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
I/SELinux ( 3584): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 3584): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1018): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=3584 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
I/dbxyzptlk.db240408.D.h( 3375): Loading /data/data/com.dropbox.android/files/extracted_libs/lib_mupdf_391432aaa92f053af59645394b5734622378199a_arm
I/Hs20UtilService( 3553): Starting #1
I/art     (  306): Explicit concurrent mark sweep GC freed 8726(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 697us total 24.308ms
I/Hs20UtilService( 3553): Message received 5003
I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 625us total 17.835ms
E/SMD     (  289): DCD OFF
D/breakpad( 3375): breakpad loaded; target path "/data/data/com.dropbox.android/app_crashdumps"
I/ServiceManager(  317): Waiting for service AtCmdFwd...
D/TimaKeyStoreProvider( 3584): TimaSignature is unavailable
D/ActivityThread( 3584): Added TimaKeyStore provider
I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 640us total 19.212ms
D/StatusBar.NetworkController( 1180): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1180): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/ActivityManager( 1018): startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.RlzPingService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
I/KLMS-2.5.183: ( 3584): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Wed Dec 02 18:46:23 GMT+01:00 2015
D/ActivityManager( 1018): startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
I/dex2oat ( 3578): ----------------------------------------------------
I/dex2oat ( 3578): <SS>: S T A R T I N G . . .
I/dex2oat ( 3578): <SS>: Zip is absent. Canceled.
I/dex2oat ( 3578): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --compiler-filter=interpret-only --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads527446663.jar --oat-fd=31 --art-fd=-1 --oat-location=/data/data/com.google.android.youtube/cache/ads527446663.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
I/RlzPingService( 3403): Setting next ping for 1449683183961
W/System.err( 3307): YouTube MDX: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
I/KLMS-2.5.183: ( 3584): KLMSAbstractReciever(): onReceive().END.
D/ActivityManager( 1018): startProcessLocked calleePkgName: com.android.managedprovisioning, hostingType: broadcast
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
I/ExternalOEMControlProvider( 3537): onCreate
I/com.dropbox.sync.android.a( 3375): Prepared cache dir '/data/data/com.dropbox.android/app_DropboxSyncCache/hizqkiq3952astb'.
I/KLMS-2.5.183: ( 3584): KLMSIntentService(): onCreate()
I/KLMS-2.5.183: ( 3584): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
E/Zygote  ( 3611): MountEmulatedStorage()
I/libpersona( 3611): KNOX_SDCARD checking this for 10022
E/Zygote  ( 3611): v2
I/libpersona( 3611): KNOX_SDCARD not a persona
I/SELinux ( 3611): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 3611): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 3611): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1018): Start proc com.android.managedprovisioning for broadcast com.android.managedprovisioning/.BootReminder: pid=3611 uid=10022 gids={50022, 9997, 1028, 3003} abi=armeabi-v7a
I/KLMS-2.5.183: ( 3584): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
I/KLMS-2.5.183: ( 3584): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
D/ActivityManager( 1018): startProcessLocked calleePkgName: com.sec.android.app.servicemodeapp, hostingType: broadcast
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
I/KLMS-2.5.183: ( 3584): KLMSIntentService(): BOOT_COMPLETED
E/Zygote  ( 3628): MountEmulatedStorage()
E/Zygote  ( 3628): v2
I/libpersona( 3628): KNOX_SDCARD checking this for 1000
I/libpersona( 3628): KNOX_SDCARD not a persona
I/SELinux ( 3628): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1018): Start proc com.sec.android.app.servicemodeapp for broadcast com.sec.android.app.servicemodeapp/.ServiceModeAppBroadcastReceiver: pid=3628 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 3628): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 3628): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/SettingsProvider( 1018): name = PREVIOUS_SYS_TIME
D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 10062
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
D/TimaKeyStoreProvider( 3611): TimaSignature is unavailable
D/ActivityThread( 3611): Added TimaKeyStore provider
I/System.out( 3307): YouTube MDX: MDX video stage moved to NEW
I/System.out( 3307): YouTube MDX: MDX video player state moved to UNSTARTED
I/System.out( 3307): YouTube MDX: MDX ad player state moved to UNSTARTED
D/TimaKeyStoreProvider( 3628): TimaSignature is unavailable
W/BackupManagerService( 1018): dataChanged but no participant pkg='com.android.providers.settings' uid=10062
D/ActivityThread( 3628): Added TimaKeyStore provider
D/SettingsProvider( 1018): name = PREVIOUS_ELAPSED_TIME
D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 10062
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
I/SecKeyguardClockSingleView( 1180): Ignore. Because it is same clock text
I/KLMS-2.5.183: ( 3584): KLMSIntentService(): onDestroy()
W/ResourcesManager( 3628): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/BackupManagerService( 1018): dataChanged but no participant pkg='com.android.providers.settings' uid=10062
I/SecKeyguardClockSingleView( 1180): Ignore. Because it is same clock text
I/ServiceMode( 3628): received = ACTION_BOOT_COMPLETED
I/ServiceMode( 3628): setReferenceIsDumpState : 0
D/ActivityManager( 1018): startProcessLocked calleePkgName: com.wssnps, hostingType: broadcast
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 3654): MountEmulatedStorage()
E/Zygote  ( 3654): v2
I/libpersona( 3654): KNOX_SDCARD checking this for 1000
I/libpersona( 3654): KNOX_SDCARD not a persona
I/SELinux ( 3654): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 3654): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1018): Start proc com.wssnps for broadcast com.wssnps/.smlNpsReceiverDefault: pid=3654 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/dex2oat ( 3578): dex2oat took 177.008ms (threads: 4)
I/ActivityManager( 1018): Killing 2771:com.android.email/u0a145 (adj 15): empty #31
E/SELinux ( 3654): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/com.dropbox.sync.android.ad( 3375): Dropbox initialized for application: hizqkiq3952astb (com.dropbox.android/240408 DropboxSync/2.0.2 (Android; 5.0.2; samsung SM-A500FU armeabi-v7a; en_US))
D/ActivityManager( 1018): startProcessLocked calleePkgName: com.samsung.android.MtpApplication, hostingType: broadcast
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 3665): MountEmulatedStorage()
E/Zygote  ( 3665): v2
I/libpersona( 3665): KNOX_SDCARD checking this for 1000
I/libpersona( 3665): KNOX_SDCARD not a persona
I/SELinux ( 3665): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1018): Start proc com.samsung.android.MtpApplication for broadcast com.samsung.android.MtpApplication/.MtpReceiver: pid=3665 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 3665): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1018): Killing 2284:com.android.mms/u0a46 (adj 15): empty #31
E/SELinux ( 3665): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 3654): TimaSignature is unavailable
D/ActivityThread( 3654): Added TimaKeyStore provider
I/ActivityManager( 1018): Killing 2952:com.sec.android.app.safetyassurance/u0a48 (adj 15): empty #31
W/ContextImpl( 1333): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver$InitSerachDBThread.run:130 <bottom of call stack> 
W/ContextImpl( 1333): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver$InitSerachDBThread.run:131 <bottom of call stack> 
I/ActivityManager( 1018): Killing 2933:com.samsung.android.provider.shootingmodeprovider/u0a152 (adj 15): empty #31
I/DBG_DM  ( 3176): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 1 sec
I/SettingSearch/SearchIntentReceiver( 1333): InitSerachDBThread thread end!
D/TimaKeyStoreProvider( 3665): TimaSignature is unavailable
D/ActivityThread( 3665): Added TimaKeyStore provider
E/MTPRx   ( 3665): In MtpReceiverandroid.intent.action.BOOT_COMPLETED
D/SecContentProvider2( 1018): uri = 14 selection = getSealedState
D/SecContentProvider2( 1018): mCursor = null
I/dhcpcd  ( 2208): wlan0: sending IPv6 Router Solicitation
I/dhcpcd  ( 2208): wlan0: no IPv6 Routers available
D/SecContentProvider2( 1018): uri = 14 selection = getSealedUsbMassStorageState
D/SecContentProvider2( 1018): mCursor = null
V/MTPRx   ( 3665): sealedState: false
V/MTPRx   ( 3665): sealedUsbMassStorageState: false
D/SettingsProvider( 1018): name = mtp_usb_connection_status
D/SettingsProvider( 1018): name = media_player_mode
D/SettingsProvider( 1018): name = mtp_usb_conditions_met
I/SecKeyguardClockSingleView( 1180): Ignore. Because it is same clock text
D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
I/SecKeyguardClockSingleView( 1180): Ignore. Because it is same clock text
D/CountryDetector( 1018): No listener is left
D/SettingsProvider( 1018): name = mtp_running_status
D/SettingsProvider( 1018): name = media_mount_count
I/SecKeyguardClockSingleView( 1180): Ignore. Because it is same clock text
I/SecKeyguardClockSingleView( 1180): Ignore. Because it is same clock text
D/ActivityManager( 1018): startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
I/SecKeyguardClockSingleView( 1180): Ignore. Because it is same clock text
D/SettingsProvider( 1018): name = mtp_sync_alive
E/Zygote  ( 3689): MountEmulatedStorage()
E/Zygote  ( 3689): v2
I/libpersona( 3689): KNOX_SDCARD checking this for 10094
I/libpersona( 3689): KNOX_SDCARD not a persona
I/SELinux ( 3689): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1018): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=3689 uid=10094 gids={50094, 9997, 3003} abi=armeabi-v7a
I/ActivityManager( 1018): Killing 2873:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #31
I/SELinux ( 3689): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3689): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/NPS_WSSNPS( 3654): [] android.intent.action.BOOT_COMPLETED
W/ContextImpl( 3654): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.wssnps.smlNpsReceiverDefault.onReceive:35 android.app.ActivityThread.handleReceiver:3125 
D/ActivityManager( 1018): startService callerProcessName:com.wssnps, calleePkgName: com.wssnps
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.wssnps/com.wssnps.smlNpsService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.wssnps, destAppInfo.processName = com.wssnps
D/ActivityManager( 1018): startProcessLocked calleePkgName: com.samsung.android.sm, hostingType: broadcast
D/SettingsProvider( 1018): name = sdcard_launch
D/NPS_WSSNPS( 3654): [] Service onCreate!!
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
D/SettingsProvider( 1018): name = boot_time_connected
D/TimaKeyStoreProvider( 3689): TimaSignature is unavailable
D/ActivityThread( 3689): Added TimaKeyStore provider
E/Zygote  ( 3707): MountEmulatedStorage()
E/Zygote  ( 3707): v2
I/libpersona( 3707): KNOX_SDCARD checking this for 1000
I/libpersona( 3707): KNOX_SDCARD not a persona
I/ActivityManager( 1018): Start proc com.samsung.android.sm for broadcast com.samsung.android.sm/.common.SmartManagerReceiver: pid=3707 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
I/SELinux ( 3707): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SecKeyguardClockSingleView( 1180): Ignore. Because it is same clock text
I/SELinux ( 3707): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 3707): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/libprocessgroup( 1018): failed to open /acct/uid_10048/pid_2952/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_10152/pid_2933/cgroup.procs: No such file or directory
D/SettingsProvider( 1018): name = mtp_open_session
W/libprocessgroup( 1018): failed to open /acct/uid_10046/pid_2284/cgroup.procs: No such file or directory
I/SecKeyguardClockSingleView( 1180): Ignore. Because it is same clock text
D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
D/NPS_WSSNPS( 3654): [50.150621] NpsServiceTask Start
D/ActivityManager( 1018): bindService callerProcessName:com.google.android.youtube, calleePkgName: com.google.android.youtube, action: null
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.app.offline.transfer.OfflineTransferService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
D/NPS_WSSNPS( 3654): [50.150621] smlDBHelper
D/TimaKeyStoreProvider( 3707): TimaSignature is unavailable
D/ActivityThread( 3707): Added TimaKeyStore provider
D/elm:15183( 3689): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:15183( 3689): ELMEngine.ELMEngine( context ).
D/elm:15183( 3689): MDMBridge.setEnterpriseBridge()
D/ActivityManager( 1018): startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
D/elm:15183( 3689): ELMAbstractReceiver : Receive Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
V/EmergencyMode( 1417): [EmergencyReceiver] EmergencyReceiver [android.intent.action.BOOT_COMPLETED]
D/elm:15183( 3689): ElmAgentService : onCreate()
D/elm:15183( 3689): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/cache/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 3307): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
W/ResourcesManager( 3707): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
I/System.out( 3375): Thread-464(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
D/elm:15183( 3689): ELMEngine.ServiceHandler.handleMessage( BOOT_COMPLETED ). 
D/elm:15183( 3689): BootCompletedState : startBootCompleted() call
W/libprocessgroup( 1018): failed to open /acct/uid_10145/pid_2771/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_2873/cgroup.procs: No such file or directory
D/elm:15183( 3689): MDMBridge.getAllLicenseInfoFromSDK()
I/SecKeyguardClockSingleView( 1180): Ignore. Because it is same clock text
I/elm:15183( 3689): Get License : 0
D/elm:15183( 3689): ElmAgentService : onDestroy().
I/ActivityManager( 1018): Killing 2332:com.sec.modem.settings/1000 (adj 15): empty #31
I/System.out( 3375): Thread-464(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 3375): Thread-464(ApacheHTTPLog):isShipBuild true
I/System.out( 3375): Thread-464(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 3375): Thread-464(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
V/EmergencyMode( 1417): [EmergencyBase] setBootTime
V/EmergencyMode( 1417): [EmergencyFactory] No Recovery State, kill my self.
I/NPS_WSSNPS( 3654): [50.150621] AsyncBulkFlagCheck
D/EnterpriseController(  279): uids 10092
D/EnterpriseController(  279): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 502 for uid 10092
D/ActivityManager( 1018): startProcessLocked calleePkgName: com.sec.factory.camera, hostingType: broadcast
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
I/PCWCLIENTTRACE_PushUtil( 3369): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 3369): sales region : global
I/PCWCLIENTTRACE_PushUtil( 3369): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 3369): [onReceive] - android.intent.action.BOOT_COMPLETED
D/PCWCLIENTTRACE_SYSTEMReceiver( 3369): ACTION_BOOTUP - Version: 4.82
D/PCWCLIENTTRACE_SYSTEMReceiver( 3369): ACTION_BOOTUP - Push type: [SPP, GCM]
E/Zygote  ( 3732): MountEmulatedStorage()
E/Zygote  ( 3732): v2
I/libpersona( 3732): KNOX_SDCARD checking this for 1000
I/libpersona( 3732): KNOX_SDCARD not a persona
I/SELinux ( 3732): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1018): Start proc com.sec.factory.camera for broadcast com.sec.factory.camera/com.sec.android.app.camerafirmware.CameraFirmwareBroadCastReceiver: pid=3732 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 3732): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 3732): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_2332/cgroup.procs: No such file or directory
D/TimaKeyStoreProvider( 3732): TimaSignature is unavailable
D/ActivityThread( 3732): Added TimaKeyStore provider
I/NPS_WSSNPS( 3654): [50.150621] IsRemain_AsyncBulkCheck
I/NPS_WSSNPS( 3654): [50.150621] IsRemain_Asyncing nothing
W/ContextImpl( 3654): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:2069 android.content.ContextWrapper.stopService:538 com.wssnps.h.run:107 java.util.Timer$TimerImpl.run:284 <bottom of call stack> 
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.wssnps/com.wssnps.smlNpsService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.wssnps, destAppInfo.processName = com.wssnps
D/NPS_WSSNPS( 3654): [50.150621] Service onDestroy
W/PCWCLIENTTRACE_AccountUtil( 3369): [hasSamungAccount] - No Samsung Account
I/CameraApp( 3732): CameraApp.onCreate()... mFeature : null
I/testFeature( 3732): Feature.Feature(context)
I/testFeature( 3732): Feature.readInternalDefaultXml()
I/testFeature( 3732): ResetFeatureValue
I/PCWCLIENTTRACE_SecurePreferencesJNI( 3369): [GetString-S]
I/CameraFirmware_broadcast( 3732): CameraFirmwareBroadCastReceiver...
I/CameraApp( 3732): CameraApp.getAppFeature()...
I/ReactiveServiceManager( 3369): Supported : 1
I/NPS_WSSNPS( 3654): [50.150621] smlBRConfigurationDelete
D/QSEECOMAPI: ( 1018): QSEECom_get_handle sb_length = 0x2040
D/QSEECOMAPI: ( 1018): App is not loaded in QSEE
I/NPS_WSSNPS( 3654): [50.150621] smlBRMessageDelete
I/NPS_WSSNPS( 3654): [50.150621] smlBREmailDelete
I/NPS_WSSNPS( 3654): [50.150621] smlBRNetworkDelete
D/ActivityManager( 1018): startProcessLocked calleePkgName: com.samsung.android.app.watchmanagerstub, hostingType: broadcast
I/NPS_WSSNPS( 3654): [50.150621] smlBRCallLogDelete
I/NPS_WSSNPS( 3654): [50.150621] smlBRMiniDiaryDelete
I/NPS_WSSNPS( 3654): [50.150621] smlBRPenMemoMDelete
I/NPS_WSSNPS( 3654): [50.150621] smlBRSMemoDelete
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
I/NPS_WSSNPS( 3654): [50.150621] verifier installed? false
I/NPS_WSSNPS( 3654): [50.150621] cpuBooster release : false
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 3752): MountEmulatedStorage()
E/Zygote  ( 3752): v2
I/libpersona( 3752): KNOX_SDCARD checking this for 10100
I/libpersona( 3752): KNOX_SDCARD not a persona
I/SELinux ( 3752): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1018): Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=3752 uid=10100 gids={50100, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
I/ActivityManager( 1018): Killing 2997:org.simalliance.openmobileapi.service/1101 (adj 15): empty #31
I/SELinux ( 3752): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
D/QSEECOMAPI: ( 1018): Loaded image: APP id = 10
E/SELinux ( 3752): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/NPS_WSSNPS( 3654): [50.150621] dsServerSocket close
I/ActivityManager( 1018): Killing 3019:com.sec.android.app.bluetoothtest/1000 (adj 15): empty #31
D/QSEECOMAPI: ( 1018): QSEECom_dealloc_memory 
D/QSEECOMAPI: ( 1018): QSEECom_shutdown_app, app_id = 10
E/terrier ( 1018): handleString: Failed to handle string(-4)
E/terrier ( 1018): Java_com_android_server_ReactiveService_GetString: error code = [-4]
D/PCWCLIENTTRACE_SecurePreferencesJNI( 3369): getString is null
I/PCWCLIENTTRACE_SecurePreferencesJNI( 3369): [GetString-E]
I/PCWCLIENTTRACE_PushUtil( 3369): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 3369): sales region : global
I/PCWCLIENTTRACE_PushUtil( 3369): getPushTypeList : [SPP, GCM]
E/PCWCLIENTTRACE_PCWHandler( 3369): [ensureRegistration] - No Samsung account
D/ActivityManager( 1018): startProcessLocked calleePkgName: com.vlingo.midas, hostingType: broadcast
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
D/TimaKeyStoreProvider( 3752): TimaSignature is unavailable
D/ActivityThread( 3752): Added TimaKeyStore provider
E/Zygote  ( 3770): MountEmulatedStorage()
I/libpersona( 3770): KNOX_SDCARD checking this for 10031
E/Zygote  ( 3770): v2
I/libpersona( 3770): KNOX_SDCARD not a persona
I/SELinux ( 3770): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1018): Start proc com.vlingo.midas for broadcast com.vlingo.midas/com.vlingo.core.facade.lmtt.LmttReceiver: pid=3770 uid=10031 gids={50031, 9997, 1028, 1015, 3003, 3002, 3001} abi=armeabi-v7a
I/ActivityManager( 1018): Killing 2968:com.sec.dsm.system/1000 (adj 15): empty #31
I/SELinux ( 3770): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 3770): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 3770): TimaSignature is unavailable
D/ActivityManager( 1018): startProcessLocked calleePkgName: com.samsung.android.app.accesscontrol, hostingType: broadcast
D/ActivityThread( 3770): Added TimaKeyStore provider
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
D/PackageIntentReceiver( 3752): ACTION_BOOT_COMPLETED
D/PackageIntentReceiver( 3752): jangil::ACTION_BOOT_COMPLETED::do not need pkg remove..
E/Zygote  ( 3788): MountEmulatedStorage()
E/Zygote  ( 3788): v2
I/libpersona( 3788): KNOX_SDCARD checking this for 1000
I/libpersona( 3788): KNOX_SDCARD not a persona
I/SELinux ( 3788): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 3788): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1018): Start proc com.samsung.android.app.accesscontrol for broadcast com.samsung.android.app.accesscontrol/.AccessControlReceiver: pid=3788 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/ActivityManager( 1018): Killing 3042:com.sec.android.app.taskmanager/u0a157 (adj 15): empty #31
E/SELinux ( 3788): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1018): startProcessLocked calleePkgName: com.google.android.gm, hostingType: broadcast
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
D/TimaKeyStoreProvider( 3788): TimaSignature is unavailable
D/ActivityThread( 3788): Added TimaKeyStore provider
E/Zygote  ( 3803): MountEmulatedStorage()
E/Zygote  ( 3803): v2
I/libpersona( 3803): KNOX_SDCARD checking this for 10101
I/libpersona( 3803): KNOX_SDCARD not a persona
I/SELinux ( 3803): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1018): Start proc com.google.android.gm for broadcast com.google.android.gm/.GoogleMailDeviceStartupReceiver: pid=3803 uid=10101 gids={50101, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1018): Killing 3071:com.sec.android.app.factorykeystring/1000 (adj 15): empty #31
I/SELinux ( 3803): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
W/ResourcesManager( 3770): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
E/SELinux ( 3803): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/art     (  306): Explicit concurrent mark sweep GC freed 8792(374KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 649us total 25.512ms
D/TimaKeyStoreProvider( 3803): TimaSignature is unavailable
D/ActivityThread( 3803): Added TimaKeyStore provider
I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 619us total 18.618ms
I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 619us total 17.929ms
W/libprocessgroup( 1018): failed to open /acct/uid_1101/pid_2997/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_3019/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_2968/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_10157/pid_3042/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_3071/cgroup.procs: No such file or directory
W/Atfwd_Sendcmd(  317): AtCmdFwd service not published, waiting... retryCnt : 3
D/SettingsProvider( 1018): name = access_control_enabled
D/ActivityManager( 1018): startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
D/StatusBar.NetworkController( 1180): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1180): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
E/Zygote  ( 3820): MountEmulatedStorage()
E/Zygote  ( 3820): v2
I/libpersona( 3820): KNOX_SDCARD checking this for 10069
I/libpersona( 3820): KNOX_SDCARD not a persona
I/SELinux ( 3820): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
D/WifiDisplayAdapter( 1018): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
I/ActivityManager( 1018): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=3820 uid=10069 gids={50069, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1018): Killing 3092:com.samsung.android.service.travel/u0a159 (adj 15): empty #31
I/SELinux ( 3820): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 3820): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/WifiDisplayAdapter( 1018): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
D/TimaKeyStoreProvider( 3820): TimaSignature is unavailable
D/ActivityThread( 3820): Added TimaKeyStore provider
I/AudioService( 1018): getStreamVolume 3 index 0
D/FileShare-Server( 3820): ServerBroadcastReceiver.onReceive - action android.intent.action.BOOT_COMPLETED // null
I/VlingoApplication( 3770): VlingoApplication appVersion ='11.7.0.1.40254', coreVersion = '2.6.3.16956', ro.csc.sales_code=XEO
W/libprocessgroup( 1018): failed to open /acct/uid_10159/pid_3092/cgroup.procs: No such file or directory
I/VlingoAndroidCore( 3770): AppName: SamsungTproject, Core: 2.6.3.16956, SDK: 2.0.2173, EDM:16956
E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/cache/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 3307): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ContextImpl( 3307): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 3307): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
D/ActivityManager( 1018): startService callerProcessName:com.google.android.youtube, calleePkgName: com.google.android.youtube
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
I/DBG_POLICYDM( 3219): [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
I/DBG_POLICYDM( 3219): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
I/DBG_POLICYDM( 3219): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
I/DBG_POLICYDM( 3219): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
I/DBG_POLICYDM( 3219): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
I/DBG_POLICYDM( 3219): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
I/DBG_POLICYDM( 3219): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
D/ActivityManager( 1018): startService callerProcessName:com.google.android.youtube, calleePkgName: com.google.android.youtube
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.app.offline.transfer.OfflineTransferService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
D/VlingoApplication( 3770): sac sec ensureCacheEmpty() car_iux_tts_cacheing_required set to false
D/VlingoApplication( 3770): sac sec ensureCacheEmpty() purged 0 historically cached TTS files
I/DBG_DM  ( 3176): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 2 sec
D/DialogFlow( 3770): initQueue()
D/WifiDisplayAdapter( 1018): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
D/ActivityManager( 1018): startProcessLocked calleePkgName: com.samsung.android.app.galaxyfinder, hostingType: broadcast
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 3874): MountEmulatedStorage()
E/Zygote  ( 3874): v2
I/libpersona( 3874): KNOX_SDCARD checking this for 10032
I/libpersona( 3874): KNOX_SDCARD not a persona
I/SELinux ( 3874): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1018): Start proc com.samsung.android.app.galaxyfinder:tagService for broadcast com.samsung.android.app.galaxyfinder/.tag.TagReadyReceiver: pid=3874 uid=10032 gids={50032, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
I/ActivityManager( 1018): Killing 3058:com.sec.knox.bridge/1000 (adj 15): empty #31
I/SELinux ( 3874): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 3874): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 3874): TimaSignature is unavailable
D/ActivityThread( 3874): Added TimaKeyStore provider
D/ActivityManager( 1018): startService callerProcessName:com.google.android.youtube, calleePkgName: com.google.android.youtube
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
D/ActivityManager( 1018): startService callerProcessName:com.google.android.youtube, calleePkgName: com.google.android.youtube
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.app.offline.transfer.OfflineTransferService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
D/ActivityManager( 1018): startService callerProcessName:com.google.android.youtube, calleePkgName: com.google.android.youtube
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.core.player.preload.PreloadVideosTransferService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_3058/cgroup.procs: No such file or directory
D/ActivityManager( 1018): startService callerProcessName:com.google.android.youtube, calleePkgName: com.google.android.youtube
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.core.player.preload.PreloadVideosTransferService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ContextImpl( 1953): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.qualcomm.qti.services.secureui.BootReceiver.onReceive:30 android.app.ActivityThread.handleReceiver:3125 
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
D/ActivityManager( 1018): startService callerProcessName:com.qualcomm.qti.services.secureui, calleePkgName: com.qualcomm.qti.services.secureui
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.qualcomm.qti.services.secureui/com.qualcomm.qti.services.secureui.SecureUIService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.qualcomm.qti.services.secureui:sui_service, destAppInfo.processName = com.qualcomm.qti.services.secureui:sui_service
D/SecUISvc( 1953): Service started flags 0 startId 1
D/SecUISvc( 1953): Thread created.
D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/btif_config_util( 2643): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
I/Gmail   ( 3803): getAccountsCursor
D/ActivityManager( 1018): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
V/GLSActivity( 1637): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager( 1018): Killing 3128:com.sec.android.diagmonagent/1000 (adj 15): empty #31
W/GAV2    ( 3803): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
D/ActivityManager( 1018): startProcessLocked calleePkgName: com.sec.android.app.sns3, hostingType: broadcast
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
D/AndroidRuntime( 3896): 
D/AndroidRuntime( 3896): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3896): CheckJNI is OFF
D/AndroidRuntime( 3896): readGMSProperty: start
D/AndroidRuntime( 3896): readGMSProperty: already setted!!
D/AndroidRuntime( 3896): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 3896): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 3896): readGMSProperty: end
D/AndroidRuntime( 3896): addProductProperty: start
E/Zygote  ( 3906): MountEmulatedStorage()
E/Zygote  ( 3906): v2
I/libpersona( 3906): KNOX_SDCARD checking this for 10033
I/libpersona( 3906): KNOX_SDCARD not a persona
I/SELinux ( 3906): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_3128/cgroup.procs: No such file or directory
I/SELinux ( 3906): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 3906): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1018): Start proc com.sec.android.app.sns3 for broadcast com.sec.android.app.sns3/.SnsBroadcastReceiver: pid=3906 uid=10033 gids={50033, 9997, 1028, 1015, 3003} abi=armeabi-v7a
I/ActivityManager( 1018): Killing 3145:com.sec.usbsettings/1000 (adj 15): empty #31
D/FactoryTestApp( 2617): [DummyFtClient$onDestroy](2617) Destroy DummyFtClient service
D/FactoryTestApp( 2617): [Support$Values.getString](2617) id=MODEL_COMMUNICATION_MODE, value=gsm
I/FactoryTestApp( 2617): [ModuleCommon$isConnectionModeNone](2617) mConnectionMode = gsm
I/FactoryTestApp( 2617): [ModuleCommon$isRunningFtClient](2617) RUNNING_FTCLIENT : false
D/FactoryTestApp( 2617): [DummyFtClient$onDestroy](2617) kill process
I/Process ( 2617): Sending signal. PID: 2617 SIG: 9
D/TimaKeyStoreProvider( 3906): TimaSignature is unavailable
D/ActivityThread( 3906): Added TimaKeyStore provider
D/FileApkUtils( 2000): Spent 66ms computing apk sha1.
D/FileApkUtils( 2000): Module already staged or being staged:chimera-modules/MapsModule.apk
I/art     ( 2000): DexFile_isDexOptNeeded failed to open oat file '/data/dalvik-cache/arm/data@data@com.google.android.gms@app_chimera@chimera-module-root@module-d93aca1818df11c4cd5bccf493ad94e2b544d57a@MapsModule.apk@classes.dex' for file location '/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d93aca1818df11c4cd5bccf493ad94e2b544d57a/MapsModule.apk': Failed to open oat filename for reading: No such file or directory
I/System.out( 3375): pool-10-thread-1 calls detatch()
I/ActivityManager( 1018): Process com.sec.factory (pid 2617)(adj 0) has died(201,1057)
D/DexOptUtils( 2000): Module /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d93aca1818df11c4cd5bccf493ad94e2b544d57a/MapsModule.apk appears to be unoptimized.
D/DexOptUtils( 2000): Lollipop platform, using <isa> directory.
D/DexOptUtils( 2000): Instantiating DexClassLoader to force creation of odex.
D/DexOptUtils( 2000): Primary ABI of odexing process is armeabi-v7a
D/AndroidHttpClient( 3307): [NALSECURITY] isMmsRequest() : CoreProtocolPNames.USER_AGENT = Dalvik/2.1.0 (Linux; U; Android 5.0.2; SM-A500FU Build/LRX22G)
D/AndroidHttpClient( 3307): [NALSECURITY] checkMmsSendPermission() : isMmsRequest() = false method = GET
I/System.out( 3307): Thread-497(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
I/System.out( 3307): Thread-497(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 3307): Thread-497(ApacheHTTPLog):isShipBuild true
I/System.out( 3307): Thread-497(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 3307): Thread-497(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
D/EnterpriseController(  279): uids 10166
D/EnterpriseController(  279): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 502 for uid 10166
E/AffinityControl( 3896): AffinityControl: registerfunction enter
W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_3145/cgroup.procs: No such file or directory
D/AndroidRuntime( 3896): Calling main entry com.android.commands.am.Am
I/dex2oat ( 3932): ----------------------------------------------------
I/dex2oat ( 3932): <SS>: S T A R T I N G . . .
I/dex2oat ( 3932): <SS>: Zip is absent. Canceled.
I/dex2oat ( 3932): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --compiler-filter=interpret-only --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d93aca1818df11c4cd5bccf493ad94e2b544d57a/MapsModule.apk --oat-fd=44 --art-fd=-1 --oat-location=/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d93aca1818df11c4cd5bccf493ad94e2b544d57a/arm/MapsModule.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
E/PersonaManagerService( 1018): inState():  stateMachine is null !!
I/PersonaManagerService( 1018): PersonaId don't exist
I/ActivityManager( 1018): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.example.hello
D/CustomFrequencyManagerService( 1018): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  pkgName : ACTIVITY_RESUME_BOOSTER@7
W/ActivityManager( 1018): mDVFSHelper.acquire()
I/SurfaceFlinger(  258): id=8 createSurf (16x16),-1 flag=20004, EimLayer(Di
I/SurfaceFlinger(  258): id=9 createSurf (16x16),-1 flag=20004, EimLayer(An
D/FocusedStackFrame( 1018): Set to : 0
D/Launcher.HomeView( 1480): onPause
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.example.hello
D/InputDispatcher( 1018): Focused application set to: xxxx
D/InputDispatcher( 1018): Focus left window: 1480
D/AndroidRuntime( 3896): Shutting down VM
D/Launcher( 1480): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
D/PhoneWindow( 1018): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 1018): *FMB* installDecor flags : 25362712
D/ActivityManager( 1018): startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.app.service.BootCompletedBroadcastService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
D/PhoneWindow( 1018): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
D/PhoneWindow( 1018): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  258): id=10 createSurf (1x1),1 flag=404, iello
I/ActivityManager( 1018): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=3941 uid=10174 gids={50174, 9997, 3003, 3001, 3002} abi=armeabi-v7a
E/Zygote  ( 3941): MountEmulatedStorage()
E/Zygote  ( 3941): v2
I/libpersona( 3941): KNOX_SDCARD checking this for 10174
I/libpersona( 3941): KNOX_SDCARD not a persona
I/SELinux ( 3941): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 3941): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 3941): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/PointerIcon( 1018): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1018): setMouseCustomIcon IconType is same.101
D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.verifier.InternalApkUploadService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.checkin.CheckinService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
V/ActivityThread( 1480): updateVisibility : ActivityRecord{3f41a428 token=android.os.BinderProxy@2eb8d969 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
I/art     ( 1018): Explicit concurrent mark sweep GC freed 44448(2MB) AllocSpace objects, 2(38KB) LOS objects, 33% free, 26MB/40MB, paused 5.656ms total 218.492ms
D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.update.SystemUpdateService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/TimaKeyStoreProvider( 3941): TimaSignature is unavailable
D/ActivityThread( 3941): Added TimaKeyStore provider
V/WindowOrientationListener( 1018): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
V/WindowOrientationListener( 1018): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
V/WindowManager( 1018): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
D/GCM     ( 2000): COMPAT: Multi user not supported
D/Launcher.HomeView( 1480): onStop
D/StatusBarManagerService( 1018): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PersonaManager( 1018): isKioskContainerExistOnDevice
W/art     ( 3896): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
V/ActivityThread( 1480): updateVisibility : ActivityRecord{3f41a428 token=android.os.BinderProxy@2eb8d969 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/Launcher( 1480): onTrimMemory. Level: 20
I/ActivityManager( 1018): Killing 3189:com.sec.providers.settingsearch/u0a150 (adj 15): empty #31
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.recovery.AccountRecoveryBackgroundService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.dsi.ant.server.AntService.startService:135 com.dsi.ant.server.startup.BootCompletedReceiver.onReceive:41 
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.authzen.GcmReceiverService; callingUser = 0; userId(target) = 0
,W/ContextImpl( 1018): Implicit intents with startService are not safe: Intent { act=com.dsi.ant.server.IAntHal } android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.dsi.ant.server.AntService.startService:135 
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1018): startProcessLocked calleePkgName: com.samsung.android.app.assistantmenu, hostingType: broadcast
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3968): MountEmulatedStorage()
E/Zygote  ( 3968): v2
I/libpersona( 3968): KNOX_SDCARD checking this for 1000
I/libpersona( 3968): KNOX_SDCARD not a persona
I/SELinux ( 3968): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1018): Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=3968 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 3968): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 3968): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/CheckinService( 2000): Checkin interval check for package: unspecified last checkin: 1448876885175 min interval config: 0 actual interval: 201500966
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.location.internal.GoogleLocationManagerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/System.out( 3307): Thread-497 calls detatch()
D/WindowOrientationListener( 1018):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
D/SensorService( 1018): [SO] activate (ident=0xb84959c0, enabled=0)
I/Sensors ( 1018): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,I/GCoreUlr( 2000): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}]
,D/SensorManager( 1018): unregisterListener ::   
,I/Sensors ( 1018): AccelerometerSensor(0) setDelay : 66000000(ns)
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/SensorService( 1018): [SO] changed settle time [1]
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.location.reporting.service.DispatchingService; callingUser = 0; userId(target) = 0
D/SensorService( 1018): [SO] setDelay [66000000]
D/SensorService( 1018): [SO] activate (ident=0xb84959c0, enabled=1)
D/SensorService( 1018): [SO] AR_init
I/Sensors ( 1018): AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,W/ActivityManager( 1018): userId = 0, bbcId = -10000,
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/SensorManager( 1018): registerListener :: 1600221811, Screen Orientation Sensor, 66000, 0,  ,
,I/GCoreUlr( 1863): DispatchingService.onCreate()
,D/TimaKeyStoreProvider( 3968): TimaSignature is unavailable
,D/ActivityThread( 3968): Added TimaKeyStore provider
,I/CheckinService( 2000): Disabling old GoogleServicesFramework version
,D/GCM     ( 1637): GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED
,I/DBG_DM  ( 3176): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 3 sec
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.reminders.notification.NotificationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/WebViewFactory( 3941): Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
,D/SystemUpdateService( 2000): onCreate
,D/SensorService( 1018): [SO] Reset Rotation Old [100], Init [1]
,I/LibraryLoader( 3941): Time to load native libraries: 2 ms (timestamps 9926-9928)
I/LibraryLoader( 3941): Expected native library version number "",actual native library version number ""
,D/SystemUpdateService( 2000): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,D/SensorService( 1018): [SO] 0.192 0.115 10.151
,D/SensorService( 1018): [SO] [100 -> 255]
,V/AuthZen ( 2000): Handling intent: android.intent.action.BOOT_COMPLETED
,D/AuthZenEventHandler( 2000): Handling event: android.intent.action.BOOT_COMPLETED
,V/WebViewChromiumFactoryProvider( 3941): Binding Chromium to main looper Looper (main, tid 1) {3658903}
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
I/LibraryLoader( 3941): Expected native library version number "",actual native library version number ""
,I/chromium( 3941): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.EmailMigrationService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,I/art     ( 2000): Explicit concurrent mark sweep GC freed 25475(1963KB) AllocSpace objects, 32(512KB) LOS objects, 40% free, 10MB/18MB, paused 4.619ms total 150.038ms
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ResourcesManager( 3906): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,I/BrowserStartupController( 3941): Initializing chromium process, singleProcess=true
,W/art     ( 3941): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3941): ApplicationContext is null in ApplicationStatus
,W/ResourcesManager( 3906): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ResourcesManager( 3906): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.GoogleMailSwitchService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,I/SurfaceFlinger(  258): id=7 Removed Mauncher (5/8)
,W/ContextImpl( 3968): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:53 android.app.ActivityThread.handleReceiver:3125 
,D/ActivityManager( 1018): startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
,W/ResourcesManager( 3906): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 3906): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 3906): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,E/Gmail   ( 3803): Error finding the version of the Email provider.....
E/Gmail   ( 3803): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 3803): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:165)
E/Gmail   ( 3803): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1240)
E/Gmail   ( 3803): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:188)
E/Gmail   ( 3803): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 3803): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 3803): 	at android.os.Looper.loop(Looper.java:145)
E/Gmail   ( 3803): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 3803): We do not support migrating this version of the Email provider.
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.api.credentials.sync.CredentialSyncReceiverService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/chromium( 3941): [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,I/chromium( 3941): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50556 len=3379
,I/chromium( 3941): [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:7638088 len:1165478
I/Adreno-EGL( 3941): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 3941): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 3941): Build Date: 04/06/15 Mon
I/Adreno-EGL( 3941): Local Branch: 
I/Adreno-EGL( 3941): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 3941): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 3941):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.GmailIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,W/ResourcesManager( 3906): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 3906): Asset path '/system/framework/libvtmanagerjar.jar' does not exist or contains no resources.
W/ResourcesManager( 3906): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gm/com.android.email.service.AttachmentService; callingUser = 0; userId(target) = 0
W/libprocessgroup( 1018): failed to open /acct/uid_10150/pid_3189/cgroup.procs: No such file or directory
,W/ActivityManager( 1018): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,I/Gmail   ( 3803): getAccountsCursor
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/Gmail   ( 3803): Observing account changes for notifications
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gm/com.android.email.service.EmailBroadcastProcessorService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,D/ActivityManager( 1018): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1018): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,I/art     ( 1637): Explicit concurrent mark sweep GC freed 5624(283KB) AllocSpace objects, 4(64KB) LOS objects, 40% free, 10MB/17MB, paused 6.476ms total 207.362ms
,W/chromium( 3941): [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
,W/BaseAppContext( 2000): Using Auth Proxy for data requests.
,E/SMD     (  289): DCD OFF
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.tron.CollectionService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1637): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ChimeraCfgMgr( 2000): Loading module com.google.android.gms.kids from APK com.google.android.gms
,W/art     ( 3941): Attempt to remove local handle scope entry from IRT, ignoring
,I/CheckinService( 2000): Checking schedule, now: 1449078387024 next: 1449416148109
I/CheckinService( 2000): active receiver: disabled
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.syncadapters.contacts
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.syncadapters.contacts/com.google.android.syncadapters.contacts.ContactsSyncAdapterIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.process.gapps
,W/AwContents( 3941): onDetachedFromWindow called when already detached. Ignoring
,D/ActivityManager( 1018): startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
,D/PhoneWindow( 3941): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 3941): *FMB* installDecor flags : 8456448
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,D/SystemWebViewEngine( 3941): CordovaWebView is running on device made by: samsung
,I/ActivityManager( 1018): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.BootReceiver: pid=4045 uid=10104 gids={50104, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a,
,E/Zygote  ( 4045): MountEmulatedStorage()
,E/Zygote  ( 4045): v2
I/libpersona( 4045): KNOX_SDCARD checking this for 10104
I/libpersona( 4045): KNOX_SDCARD not a persona
,I/SELinux ( 4045): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 4045): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0,
,E/SELinux ( 4045): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/SystemUpdateService( 2000): cancelUpdate (empty URL)
,W/art     ( 3941): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 3941): Attempt to remove local handle scope entry from IRT, ignoring
,I/GoogleHttpClient( 1637): GMS http client unavailable, use old client
,I/SystemUpdateService( 2000): active receiver: disabled
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,I/DBG_DM  ( 3176): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 4 sec
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 4045): TimaSignature is unavailable
,D/ActivityThread( 4045): Added TimaKeyStore provider
,I/AuthZen ( 2000): Fetching signing key...
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/PowerManagerService( 1018): [api] release WakeLock flags=0x10000006 tag=PowerUI.Notification uid=10054 pid=1180 (0x0)
D/ChimeraCfgMgr( 2000): Loading module com.google.android.gms.kids from APK com.google.android.gms
D/OpenGLRenderer( 3941): Render dirty regions requested: true
,D/ActivityManager( 1018): post active user change for 0 fullscreen true record.isFloatingActivity() false
,D/KnoxTimeoutHandler( 1018): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1018): postActiveUserChange, showWhenLocked: false
,D/KnoxTimeoutHandler( 1018): handleActiveUserChange for user 0
D/PersonaManagerService( 1018): getPersonasForUser(): returning null!
,D/PhoneWindow( 3941): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 3941): *FMB* isFloatingMenuEnabled return false
,I/AuthZen ( 2000): Signing key fetched successfully!
,I/SurfaceFlinger(  258): id=11 createSurf (1x1),1 flag=404, NainActivit
,W/BaseAppContext( 2000): Using Auth Proxy for data requests.
,W/ResourcesManager( 4045): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/ActivityManager( 1018): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/InputDispatcher( 1018): Focus entered window: 3941
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,E/SQLiteLog( 3803): (283) recovered 39 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,D/PointerIcon( 1018): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/SRIB_DCS( 3941): log_dcs ThreadedRenderer::initialize entered! 
D/PointerIcon( 1018): setMouseCustomIcon IconType is same.101
,I/OpenGLRenderer( 3941): Initialized EGL, version 1.4
,V/GLSActivity( 1637): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ActivityThread( 3803): Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.aj@1a12f9f8 that was originally bound here
E/ActivityThread( 3803): android.app.ServiceConnectionLeaked: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.aj@1a12f9f8 that was originally bound here
E/ActivityThread( 3803): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1144)
E/ActivityThread( 3803): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1038)
E/ActivityThread( 3803): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2154)
E/ActivityThread( 3803): 	at android.app.ContextImpl.bindService(ContextImpl.java:2137)
E/ActivityThread( 3803): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 3803): 	at com.android.emailcommon.service.ah.a(SourceFile:181)
E/ActivityThread( 3803): 	at com.android.emailcommon.service.ah.e(SourceFile:224)
E/ActivityThread( 3803): 	at com.android.email.service.n.c(SourceFile:161)
E/ActivityThread( 3803): 	at com.android.email.provider.b.a(SourceFile:173)
E/ActivityThread( 3803): 	at com.android.email.provider.b.a(SourceFile:117)
E/ActivityThread( 3803): 	at com.android.email.service.EmailBroadcastProcessorService.c(SourceFile:318)
E/ActivityThread( 3803): 	at com.android.email.service.EmailBroadcastProcessorService.onHandleIntent(SourceFile:1308)
E/ActivityThread( 3803): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/ActivityThread( 3803): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3803): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread( 3803): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/ActivityManager( 1018): Unbind failed: could not find connection for android.os.BinderProxy@28130cbe
,D/a       ( 2000): Opening database auth.proximity.permit_store...
,D/OpenGLRenderer( 3941): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
D/OpenGLRenderer( 3941): Enabling debug mode 0
,W/ResourcesManager( 3874): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/dex2oat ( 3932): dex2oat took 1.665s (threads: 4)
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.playlog.service.MonitorService; callingUser = 0; userId(target) = 0
,W/Kids    ( 2000): [AbstractKidsOperation] Invalid device state 3
,D/DexOptUtils( 2000): Odex created at:/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d93aca1818df11c4cd5bccf493ad94e2b544d57a/arm/MapsModule.dex
,D/DexOptUtils( 2000): Set odex to world readable.
D/DexOptUtils( 2000): Renamed odex to /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d93aca1818df11c4cd5bccf493ad94e2b544d57a/arm/MapsModule.odex
,D/FileApkUtils( 2000): Keeping up-to-date module: module-d93aca1818df11c4cd5bccf493ad94e2b544d57a
,D/InputMethodManagerService( 1018): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/StatusBar( 1180): Icon Only
,D/PanelView( 1180): There is/are notification(s) 
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/GLSActivity( 1637): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Timeline( 3941): Timeline: Activity_idle id: android.os.BinderProxy@50a2029 time:41169
,W/GCoreFlp( 1863): No location to return for getLastLocation()
,D/AuthZenTransactionCache( 2000): Initialized cache in: /data/data/com.google.android.gms/files
D/AuthZenTransactionCache( 2000): Clearing transaction cache
,I/ActivityManager( 1018): Displayed Component not be shown by security: +1s658ms
,D/SystemUpdateService( 2000): onDestroy
,D/CustomFrequencyManagerService( 1018): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  tag : ACTIVITY_RESUME_BOOSTER@7
,W/ActivityManager( 1018): mDVFSHelper.release()
I/Timeline( 1018): Timeline: Activity_windows_visible id: ActivityRecord{1b13b37f u0 com.example.hello/.MainActivity t2} time:41190
D/CustomFrequencyManagerService( 1018): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  pkgName : ACTIVITY_RESUME_BOOSTER@11
,I/GCoreUlr( 1863): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED,
I/SamsungIME( 1838): getCurrentCandidateView
,V/GLSActivity( 1637): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/FusedLocationProvider( 2000): location=null
,D/GmsModuleFndr( 2000): Beginning GMS chimera module scan
,D/ActivityManager( 1018): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.content.SyncAdapter
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.api.credentials.sync.CredentialSyncService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/GCoreFlp( 1863): No location to return for getLastLocation()
,W/FusedLocationProvider( 2000): location=null
,W/ResourcesManager( 3874): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 3874): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3874): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.sec.android.app.sbrowser.SBrowserMainActivity
,I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3968): getResourcePackageName:android.app.searchable
,I/AMMetaDataParserService( 3968): getResourcePackageName:assistantlist
,I/AMMetaDataParserService( 3968): Resource data:2131165186
,W/ResourcesManager( 3968): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 3968): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3968): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 3968): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3968): getResourceName:com.sec.android.app.sbrowser:xml/assistantlist
I/AMMetaDataParserService( 3968): getResourceTypeNamexml
,W/Auth    ( 1637): [FRP,FrpUpdateIntentService] Received invalid intent action: com.google.android.gms.auth.ACTION_INVALID
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.change.LoginAccountsChangedIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1637): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/GmsModuleFndr( 2000): Module pkg com.google.android.apps.kids.kidsetup not installed, skipping
D/ChimeraCfgMgr( 2000): Beginning module configuration check
,V/GmsCoreStatsServiceLauncher( 2000): Received broadcast intent Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher (has extras) }
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
,D/ChimeraCfgMgr( 2000): Module APKs unchanged, check complete
,I/AMMetaDataParserService( 3968): Icon data: ResourceEnter URL2131755289android.intent.action.doInputURL2130837509
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/PCWCLIENTTRACE_AccountAppFacade2_0( 3369): unregister AuthInfo UpdateReceiver v2.0
,D/ActivityManager( 1018): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,E/File    ( 3803): fail readDirectory() errno=2
,V/GLSActivity( 1637): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1018): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,I/SurfaceFlinger(  258): id=10 Removed iello (7/8)
,I/SurfaceFlinger(  258): id=10 Removed iello (-2/8)
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,I/Gmail   ( 3803): notifyAccountChanged
,I/AMMetaDataParserService( 3968): Icon data: ResourceTabs2131755155android.intent.action.doWindowManager2130837511
,D/SamsungIME( 1838): Dismiss ExpandCandiate
,V/GLSActivity( 1637): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 3803): getAccountsCursor
,D/ActivityManager( 1018): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,D/CustomFrequencyManagerService( 1018): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  tag : ACTIVITY_RESUME_BOOSTER@11
,V/GLSActivity( 1637): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/AMMetaDataParserService( 3968): Icon data: ResourceNew Tab2131755460android.intent.action.doNewWindow2130837510
,I/Gmail   ( 3803): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/ActivityManager( 1018): Killing 1560:com.sec.android.provider.badge/u0a72 (adj 15): empty #31
,W/BindingManager( 3941): Cannot call determinedVisibility() - never saw a connection for the pid: 3941
,D/PersistentNotificationBroadcastReceiver( 1637): Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
,D/ActivityManager( 1018): startProcessLocked calleePkgName: com.android.vending, hostingType: broadcast
,D/StatusBar.NetworkController( 1180): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1180): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappManager
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity0
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity1
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity2
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity3
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity4
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity5
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity6
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity7
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity8
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity9
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.sec.android.app.sbrowser.history.ui.HistoryActivity
W/ContextImpl( 3968): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.Settings
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.sec.android.app.sbrowser.reader.ui.ReaderActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.sec.android.app.sbrowser.menuactivity.ui.AddWebPageMenuActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.sec.android.app.sbrowser.readinglist.activity.ReadingListActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.sec.android.app.sbrowser.readinglist.controller.ReadingListSearchActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.sec.android.app.sbrowser.sites.SitesActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.sec.android.app.sbrowser.common.DataChargingDialog
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.EditBookmarkFolderActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.AddBookmarkActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.ShowBookmarksActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.SelectBookmarkFolderActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.CreateBookmarkFolderActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.SynctabActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.SelectSyncAccountActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.AutofillFormEdit
I/AMMetaDataParserSer,vice( 3968): Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.DeleteSyncTabActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountGetStartedActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountCreateAccountActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountConfirmAccountActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountSignInActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountVerifiedAccountActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountCreateAccountNotAllowedActivity
I/Gmail   ( 3803): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
I/chromium( 3941): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,E/Zygote  ( 4098): MountEmulatedStorage(),
E/Zygote  ( 4098): v2
I/libpersona( 4098): KNOX_SDCARD checking this for 10028,
I/libpersona( 4098): KNOX_SDCARD not a persona
,I/SELinux ( 4098): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 4098): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4098): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1018): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=4098 uid=10028 gids={50028, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/Gmail   ( 3803): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 3803): calculateUnknownSyncRationalesAndPurgeInBackground: running
,D/JsMessageQueue( 3941): Set native->JS mode to OnlineEventsBridgeMode
,D/TimaKeyStoreProvider( 4098): TimaSignature is unavailable
,D/ActivityThread( 4098): Added TimaKeyStore provider
,E/AndroidProtocolHandler( 3941): Unable to open asset URL: file:///android_asset/www/jxcore.js
,I/art     ( 1018): Explicit concurrent mark sweep GC freed 31143(1841KB) AllocSpace objects, 6(96KB) LOS objects, 33% free, 26MB/40MB, paused 13.066ms total 183.526ms
,D/ActivityManager( 1018): bindService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gms, action: null
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,I/SamsungIME( 1838): getDebugLevel  : 0x4f4c
,I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.contacts.activities.PeopleActivity
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:assistant
I/AMMetaDataParserService( 3968): Resource data:2131034113
,W/ResourcesManager( 3968): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 3968): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3968): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3968): getResourceName:com.android.contacts:xml/assistant_main
I/AMMetaDataParserService( 3968): getResourceTypeNamexml
,E/        ( 3968): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX construct_block_size_descriptor_2d second part( 3968): took 2.676040ms for 0*0 texture 0
,I/GFX generate_partition_tables( 3968): took 6.268176ms for 0*0 texture 0
,I/GFX raster( 3968): took 10.340831ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3968): Bitmap=0xb7fede68 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7fee1f8 counterpartCT=4 counterpartW=96 counterparth=96
,I/DBG_DM  ( 3176): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 5 sec
,D/jxcore_app_log( 3941): JniHelper::setJavaVM(0xb7c19450), pthread_self() = -1206421192
D/JX-Cordova( 3941): jxcore cordova android initializing
,I/AMMetaDataParserService( 3968): Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
,I/Babel   ( 4045): MmsConfig: mnc/mcc: 0/0
I/Babel   ( 4045): MmsConfig.loadMmsSettings
I/Babel   ( 4045): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
I/Babel   ( 4045): MmsConfig.loadFromDatabase
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.ssrm.I.m:-1 com.android.server.ssrm.J.run:-1 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 
,I/SamsungIME( 1838): getDebugLevel  : 0x4f4c
,W/jxcore-log( 3941): Initializing JXcore engine
W/jxcore-log( 3941): JXcore engine is ready
,W/jxcore-log( 3941): Starting JXcore engine
,D/ActivityManager( 1018): bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,W/Settings( 4045): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,E/Babel   ( 4045): canonicalizeMccMnc: invalid mccmnc 
,I/SamsungIME( 1838): KeybaordView init() : load resources
,I/Babel   ( 4045): MmsConfig.loadFromResources
,E/Babel   ( 4045): canonicalizeMccMnc: invalid mccmnc nullnull
E/audit   ( 1935): type=1400 msg=audit(1449078388.370:205): avc:  denied  { ioctl } for  pid=3941 comm="m.example.hello" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2061 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,E/audit   ( 1935):  SEPF_SM-A500FU_5.0.2-1_0038
E/audit   ( 1935): type=1300 msg=audit(1449078388.370:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=4 a3=bef4bd58 items=0 ppid=306 ppcomm=main pid=3941 auid=4294967295 uid=10174 gid=10174 euid=10174 suid=10174 fsuid=10174 egid=10174 sgid=10174 fsgid=10174 ses=4294967295 tty=(none) comm="m.example.hello" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1935): type=1320 msg=audit(1449078388.370:205): 
,I/Babel   ( 4045): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
,W/libprocessgroup( 1018): failed to open /acct/uid_10072/pid_1560/cgroup.procs: No such file or directory
,E/        ( 3968): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3968): took 0.824323ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3968): Bitmap=0xb7fede68 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7ff6288 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3968): Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,W/art     ( 4045): Suspending all threads took: 47.881ms
,I/SamsungIME( 1838): getCurrentKeyboard
I/SamsungIME( 1838): getTextKeyboard
,D/SSRM:n  ( 1018): SIOP:: AP = 390
,D/SamsungIME( 1838): [SwiftkeyWrapper] currentLangauge : 1701729619
,W/jxcore-log( 3941): Platform android
W/jxcore-log( 3941): 
,W/jxcore-log( 3941): Process ARCH arm
W/jxcore-log( 3941): 
,E/        ( 3968): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX construct_block_size_descriptor_2d second part( 3968): took 2.099011ms for 0*0 texture 0
,I/GFX generate_partition_tables( 3968): took 7.544115ms for 0*0 texture 0
,I/GFX raster( 3968): took 10.605678ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3968): Bitmap=0xb7ff2a90 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7ff2bf8 counterpartCT=4 counterpartW=96 counterparth=96
,D/PackageManager( 1018): [MSG] MCS_UNBIND
,I/ActivityManager( 1018): Killing 3219:com.policydm/1000 (adj 15): empty #31
,I/Babel_StickerModule( 4045): App launched.
,I/jxcore-log( 3941): JXcore Cordova bridge is ready!
I/jxcore-log( 3941): 
,W/jxcore-log( 3941): JXcore engine is started
,I/AMMetaDataParserService( 3968): Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,W/art     ( 4045): Suspending all threads took: 9.714ms
,E/        ( 3968): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3968): took 0.618386ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3968): Bitmap=0xb7ff7460 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7ff75c8 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3968): Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,E/        ( 3968): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3968): took 0.980209ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3968): Bitmap=0xb7ff3f60 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7ff40c8 counterpartCT=4 counterpartW=96 counterparth=96
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,E/jxcore-log( 3941): >> samsung-SM-A500FU
E/jxcore-log( 3941): 
,I/jxcore-log( 3941): Total memory 1983791104
I/jxcore-log( 3941): 
,I/jxcore-log( 3941): Free memory 115793920
I/jxcore-log( 3941): 
I/jxcore-log( 3941): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3941): 
I/jxcore-log( 3941): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3941): 
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/jxcore-log( 3941): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log( 3941): 
,I/jxcore-log( 3941): Size 720 1280
I/jxcore-log( 3941): 
,I/jxcore-log( 3941): Screen Brightness 5
I/jxcore-log( 3941): 
,E/jxcore-log( 3941): Dummy Error Log.
E/jxcore-log( 3941): 
,I/GCoreUlr( 1863): WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,I/AMMetaDataParserService( 3968): Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,I/Process ( 3906): Sending signal. PID: 3906 SIG: 9
,E/        ( 3968): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3968): took 0.878593ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3968): Bitmap=0xb7ff3268 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7ff33d0 counterpartCT=4 counterpartW=96 counterparth=96
,I/GCoreUlr( 1863): Unbound from all location providers
,I/AMMetaDataParserService( 3968): Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,V/Babel   ( 4045): babel boot account: SMS
,W/Babel   ( 4045): EsDatabaseHelper.static should not be called on main thread [called on main thread]
,W/Babel   ( 4045): java.lang.Exception
W/Babel   ( 4045): 	at com.google.android.apps.hangouts.phone.EsApplication.a(SourceFile:1133)
W/Babel   ( 4045): 	at aes.<clinit>(SourceFile:95)
W/Babel   ( 4045): 	at ckh.<init>(SourceFile:103)
W/Babel   ( 4045): 	at ckh.a(SourceFile:67)
W/Babel   ( 4045): 	at com.google.android.apps.hangouts.phone.EsApplication.c(SourceFile:733)
W/Babel   ( 4045): 	at bhn.a(SourceFile:301)
W/Babel   ( 4045): 	at bhn.a(SourceFile:137)
W/Babel   ( 4045): 	at bhn.a(SourceFile:126)
W/Babel   ( 4045): 	at bhn.a(SourceFile:159)
W/Babel   ( 4045): 	at com.google.android.apps.hangouts.service.BootReceiver.onReceive(SourceFile:72)
W/Babel   ( 4045): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
W/Babel   ( 4045): 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
W/Babel   ( 4045): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
W/Babel   ( 4045): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Babel   ( 4045): 	at android.os.Looper.loop(Looper.java:145)
W/Babel   ( 4045): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
W/Babel   ( 4045): 	at java.lang.reflect.Method.invoke(Native Method)
W/Babel   ( 4045): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/Babel   ( 4045): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/Babel   ( 4045): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,W/Babel   ( 4045): EsDatabaseHelper.getDatabaseHelper() [called on main thread]
,W/Babel   ( 4045): java.lang.Exception
W/Babel   ( 4045): 	at com.google.android.apps.hangouts.phone.EsApplication.a(SourceFile:1133)
W/Babel   ( 4045): 	at aes.a(SourceFile:145)
W/Babel   ( 4045): 	at ckh.<init>(SourceFile:103)
W/Babel   ( 4045): 	at ckh.a(SourceFile:67)
W/Babel   ( 4045): 	at com.google.android.apps.hangouts.phone.EsApplication.c(SourceFile:733)
W/Babel   ( 4045): 	at bhn.a(SourceFile:301)
W/Babel   ( 4045): 	at bhn.a(SourceFile:137)
W/Babel   ( 4045): 	at bhn.a(SourceFile:126)
W/Babel   ( 4045): 	at bhn.a(SourceFile:159)
W/Babel   ( 4045): 	at com.google.android.apps.hangouts.service.BootReceiver.onReceive(SourceFile:72)
W/Babel   ( 4045): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
W/Babel   ( 4045): 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
W/Babel   ( 4045): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
W/Babel   ( 4045): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Babel   ( 4045): 	at android.os.Looper.loop(Looper.java:145)
W/Babel   ( 4045): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
W/Babel   ( 4045): 	at java.lang.reflect.Method.invoke(Native Method)
W/Babel   ( 4045): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/Babel   ( 4045): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/Babel   ( 4045): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,E/        ( 3968): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_3219/cgroup.procs: No such file or directory
,I/GFX raster( 3968): took 0.919219ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3968): Bitmap=0xb7ff28f8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7ff27a8 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3968): Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ActivityManager( 1018): Process com.sec.android.app.sns3 (pid 3906)(adj 0) has died(107,1109)
,D/ActivityManager( 1018): startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4139): MountEmulatedStorage()
I/libpersona( 4139): KNOX_SDCARD checking this for 10034
E/Zygote  ( 4139): v2
I/libpersona( 4139): KNOX_SDCARD not a persona
,I/SELinux ( 4139): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 4139): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1018): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=4139 uid=10034 gids={50034, 9997, 3003} abi=armeabi-v7a
E/SELinux ( 4139): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1018): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
,E/        ( 3968): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3968): took 0.517500ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3968): Bitmap=0xb7ff70b8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7ff1018 counterpartCT=4 counterpartW=96 counterparth=96
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,I/AMMetaDataParserService( 3968): Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.dialer.DialtactsActivity
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:assistant
I/AMMetaDataParserService( 3968): Resource data:2131034113
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
,D/TimaKeyStoreProvider( 4139): TimaSignature is unavailable
,D/ActivityThread( 4139): Added TimaKeyStore provider
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,I/AMMetaDataParserService( 3968): getResourceName:com.android.contacts:xml/assistant_main
,I/AMMetaDataParserService( 3968): getResourceTypeNamexml
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,E/        ( 3968): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,V/Babel   ( 4045): babel boot account: thalitester@gmail.com
,I/GFX raster( 3968): took 1.077761ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3968): Bitmap=0xb7fede68 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7ff3ee8 counterpartCT=4 counterpartW=96 counterparth=96
,D/StatusBar.NetworkController( 1180): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1180): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,W/Babel   ( 4045): EsDatabaseHelper.getDatabaseHelper() [called on main thread]
,W/Babel   ( 4045): java.lang.Exception
W/Babel   ( 4045): 	at com.google.android.apps.hangouts.phone.EsApplication.a(SourceFile:1133)
W/Babel   ( 4045): 	at aes.a(SourceFile:145)
W/Babel   ( 4045): 	at ckh.<init>(SourceFile:103)
W/Babel   ( 4045): 	at ckh.a(SourceFile:67)
W/Babel   ( 4045): 	at com.google.android.apps.hangouts.phone.EsApplication.c(SourceFile:733)
W/Babel   ( 4045): 	at bhn.a(SourceFile:301)
W/Babel   ( 4045): 	at bhn.a(SourceFile:137)
W/Babel   ( 4045): 	at bhn.a(SourceFile:126)
W/Babel   ( 4045): 	at bhn.a(SourceFile:159)
W/Babel   ( 4045): 	at com.google.android.apps.hangouts.service.BootReceiver.onReceive(SourceFile:72)
W/Babel   ( 4045): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
W/Babel   ( 4045): 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
W/Babel   ( 4045): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
W/Babel   ( 4045): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Babel   ( 4045): 	at android.os.Looper.loop(Looper.java:145)
W/Babel   ( 4045): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
W/Babel   ( 4045): 	at java.lang.reflect.Method.invoke(Native Method)
W/Babel   ( 4045): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/Babel   ( 4045): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/Babel   ( 4045): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,I/AMMetaDataParserService( 3968): Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
,D/Finsky  ( 4098): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/Gmail   ( 3803): getAccountsCursor
,D/ActivityManager( 1018): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1637): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/        ( 3968): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3968): took 0.813698ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3968): Bitmap=0xb7fede68 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7ff3be0 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3968): Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,I/GCoreUlr( 1863): DispatchingService.onDestroy()
,I/GCoreUlr( 1863): Stopping handler for UlrDispSvcFast
,I/GCoreUlr( 1863): Unbound from all location providers
,E/        ( 3968): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3968): took 0.608385ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3968): Bitmap=0xb7ff2a90 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7ff3be0 counterpartCT=4 counterpartW=96 counterparth=96
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
,I/AMMetaDataParserService( 3968): Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,D/ActivityManager( 1018): startProcessLocked calleePkgName: com.samsung.helphub, hostingType: broadcast
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1018): Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.BootBroadcastReceiver: pid=4161 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,E/Zygote  ( 4161): MountEmulatedStorage()
E/Zygote  ( 4161): v2
I/libpersona( 4161): KNOX_SDCARD checking this for 1000
I/libpersona( 4161): KNOX_SDCARD not a persona
,I/SELinux ( 4161): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4161): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
E/SELinux ( 4161): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1018): startProcessLocked calleePkgName: com.policydm, hostingType: broadcast,
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0,
E/        ( 3968): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/GFX raster( 3968): took 0.619166ms for 96*96 texture 0,
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3968): Bitmap=0xb7ff7460 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7ff3be0 counterpartCT=4 counterpartW=96 counterparth=96
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 4161): TimaSignature is unavailable,
W/QCamera2Factory(  284): getCameraInfo: E, camera_id = 0
W/QCamera2Factory(  284): getCameraInfo: X
D/ActivityThread( 4161): Added TimaKeyStore provider
W/QCamera2Factory(  284): getCameraInfo: E, camera_id = 1
W/QCamera2Factory(  284): getCameraInfo: X
,I/AMMetaDataParserService( 3968): Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,I/ActivityManager( 1018): Start proc com.policydm for broadcast com.policydm/.XDMBroadcastReceiver: pid=4177 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
I/ActivityManager( 1018): Killing 3111:com.sec.android.app.clockpackage/u0a85 (adj 15): empty #31,
,E/Zygote  ( 4177): MountEmulatedStorage()
E/Zygote  ( 4177): v2
I/libpersona( 4177): KNOX_SDCARD checking this for 1000
I/libpersona( 4177): KNOX_SDCARD not a persona
,I/SELinux ( 4177): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
E/        ( 3968): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96,
,I/GFX raster( 3968): took 1.664427ms for 96*96 texture 0,
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3968): Bitmap=0xb7ff3f60 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7ff3be0 counterpartCT=4 counterpartW=96 counterparth=96
,I/SELinux ( 4177): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 4177): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,W/VideoCapabilities( 4045): Unrecognized profile 2130706433 for video/avc
,I/AMMetaDataParserService( 3968): Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,W/AudioCapabilities( 4045): Unsupported mime audio/evrc
,D/TimaKeyStoreProvider( 4177): TimaSignature is unavailable
,D/ActivityThread( 4177): Added TimaKeyStore provider
,W/AudioCapabilities( 4045): Unsupported mime audio/qcelp
,W/AudioCapabilities( 4045): Unsupported mime audio/mpeg-L1
,W/AudioCapabilities( 4045): Unsupported mime audio/mpeg-L2
,I/DBG_DM  ( 3176): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 6 sec
,E/        ( 3968): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3968): took 0.727448ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3968): Bitmap=0xb7ff3be0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7c147a0 counterpartCT=4 counterpartW=96 counterparth=96
,I/jxcore-log( 3941): getBuffer is called!!!!
I/jxcore-log( 3941): 
,I/AMMetaDataParserService( 3968): Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,W/libprocessgroup( 1018): failed to open /acct/uid_10085/pid_3111/cgroup.procs: No such file or directory
,W/AudioCapabilities( 4045): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 4045): Unsupported mime audio/x-ima
,W/AudioCapabilities( 4045): Unsupported mime audio/qcelp
,W/AudioCapabilities( 4045): Unsupported mime audio/evrc
,D/Finsky  ( 4098): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,E/        ( 3968): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3968): took 0.849271ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3968): Bitmap=0xb7fb23f8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7fad388 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3968): Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
,D/ActivityManager( 1018): startProcessLocked calleePkgName: com.sec.knox.foldercontainer, hostingType: broadcast
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/System.out( 3770): INFO:Resource not found:/Common.properties Using default values,
,I/ActivityManager( 1018): Start proc com.sec.knox.foldercontainer for broadcast com.sec.knox.foldercontainer/.ShortcutReceiver: pid=4203 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
,I/ActivityManager( 1018): Killing 3267:com.samsung.android.app.colorblind/1000 (adj 15): empty #31
,W/Settings( 4098): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.,
,E/Zygote  ( 4203): MountEmulatedStorage(),
E/Zygote  ( 4203): v2
I/libpersona( 4203): KNOX_SDCARD checking this for 1000
I/libpersona( 4203): KNOX_SDCARD not a persona
,I/SELinux ( 4203): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4203): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 4203): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,W/Settings( 4098): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.,
,E/        ( 3968): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96,
I/GFX raster( 3968): took 0.524792ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3968): Bitmap=0xb7fd5e08 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7fabe70 counterpartCT=4 counterpartW=96 counterparth=96
D/TimaKeyStoreProvider( 4203): TimaSignature is unavailable
,D/ActivityThread( 4203): Added TimaKeyStore provider,
,W/VideoCapabilities( 4045): Unsupported mime video/wvc1,
,I/art     (  306): Explicit concurrent mark sweep GC freed 8746(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 1.159ms total 39.726ms
W/VideoCapabilities( 4045): Unsupported mime video/x-ms-wmv
I/AMMetaDataParserService( 3968): Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 597us total 19.657ms,
,I/AMMetaDataParserService( 3968): getResourcePackageName:com.samsung.android.multiuser.install_only_owner,
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.contacts.activities.ContactSelectionActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionTabActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionGroupSelectionActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.contacts.DialtactsActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.contacts.RecentCallsListActivity,
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.contacts.activities.CallLogActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.contacts.ContactsListActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.contacts.activities.ContactsFrontDoor
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.contacts.DialtactsContactsEntryActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.samsung.contacts.activities.PeopleActivity,
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.contacts.activities.JoinContactActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.contacts.preference.ContactsPreferenceActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.contacts.common.list.AccountFilterActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.contacts.common.list.CustomContactListFilterActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.contacts.activities.ShowOrCreateActivity,
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.contacts.activities.GroupDetailActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.contacts.activities.GroupEditorActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.contacts.quickcontact.QuickContactActivity
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.sec.android.multiwindow.activity.STYLE
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.contacts.ContactShortcut
I/AMMetaDataParserService( 3968): Resource data:Loop for running activityalias.DialShortcut
I/AMMetaDataParserService( 3968): Resource data:Loop for running activityalias.MessageShortcut
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.dialer.CallDetailActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDetailDeleteActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.contacts.activities.ContactDetailActivity
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3968): getResourcePackageName:assistant
I/AMMetaDataParserService( 3968): Resource data:2131034112
,I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 743us total 22.613ms,
,I/AMMetaDataParserService( 3968): getResourceName:com.android.contacts:xml/assistant_detail
I/AMMetaDataParserService( 3968): getResourceTypeNamexml
,E/        ( 3968): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3968): took 0.787812ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3968): Bitmap=0xb7ff7460 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7d22630 counterpartCT=4 counterpartW=96 counterparth=96
,I/DBG_POLICYDM( 4177): [com.policydm.XDMApplication(612/xdmWakeLockAcquire)] 
,I/DBG_POLICYDM( 4177): [com.policydm.XDMApplication(617/xdmWakeLockAcquire)] m_WakeLock is acquire!!
,I/System.out( 3375): Thread-463(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 3375): Thread-463(ApacheHTTPLog):isShipBuild true
I/System.out( 3375): Thread-463(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 3375): Thread-463(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,W/VideoCapabilities( 4045): Unrecognized profile/level 32768/2 for video/mp4v-es
,W/VideoCapabilities( 4045): Unsupported mime video/wvc1
,I/AMMetaDataParserService( 3968): Icon data: ResourceAdd to Favourites2131690170android.intent.assistant.detail.favorite2130837530
,W/VideoCapabilities( 4045): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 4045): Unsupported mime video/x-ms-wmv7
W/VideoCapabilities( 4045): Unsupported mime video/x-ms-wmv8
,I/DBG_POLICYDM( 4177): [com.policydm.agent.XDMTask(162/xdmAgentTaskHandler)] XEVENT_OS_INITIALIZED
,W/VideoCapabilities( 4045): Unsupported mime video/mp43
,I/DBG_POLICYDM( 4177): [com.policydm.agent.XDMAgent(155/xdmAgentSetSyncMode)] nSync = 0
,W/VideoCapabilities( 4045): Unsupported mime video/sorenson
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_3267/cgroup.procs: No such file or directory
,D/EnterpriseController(  279): uids 10092
D/EnterpriseController(  279): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 502 for uid 10092
,D/KnoxSetupWizardDbHelper( 4203): dbMigrationFlag : false
,W/VideoCapabilities( 4045): Unsupported mime video/mp4v-esdp
,E/        ( 3968): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3968): took 0.719479ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3968): Bitmap=0xb7ff7460 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7c147a0 counterpartCT=4 counterpartW=96 counterparth=96
,I/ActivityManager( 1018): Killing 3342:com.fmm.dm/1000 (adj 15): empty #31
,D/ShortcutReceiver( 4203):  ShortcutReceiver onReceive() intent: android.intent.action.BOOT_COMPLETED
,I/DBG_POLICYDM( 4177): [com.policydm.adapter.XDMTargetAdapter(201/xdmInitExternalStorageState)] 
,I/AMMetaDataParserService( 3968): Icon data: ResourceRemove from Favourites2131690212android.intent.assistant.detail.favorite2130837530
,D/Volley  ( 4098): [603] DiskBasedCache.clear: Cache cleared.
,D/Volley  ( 4098): [596] DiskBasedCache.clear: Cache cleared.
,I/DBG_POLICYDM( 4177): [com.policydm.adapter.XDMTargetAdapter(417/xdmGetExternalSDCardPath)] External SD Card Path : /storage/extSdCard
,D/Finsky  ( 4098): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4098): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Ads     ( 4098): Skipping gmscore version check
,E/        ( 3968): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3968): took 0.638282ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3968): Bitmap=0xb7fd4f20 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7fad388 counterpartCT=4 counterpartW=96 counterparth=96
,D/ActivityManager( 1018): startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.billing.iab.PendingNotificationsService; callingUser = 0; userId(target) = 0
,D/KnoxShortcutUtil( 4203): getIsShortcutMigrationFor_2_3_0_Done true
,D/ShortcutReceiver( 4203):  KnoxContainerVersion 2.4.0
D/ShortcutReceiver( 4203):  shortcut migration not required 
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,D/ActivityManager( 1018): startProcessLocked calleePkgName: com.sec.knox.knoxsetupwizardclient, hostingType: broadcast
,I/AMMetaDataParserService( 3968): Icon data: ResourceEdit2131690192android.intent.assistant.detail.edit2130837529
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/VideoCapabilities( 4045): Unsupported profile 4 for video/mp4v-es,
,D/SamsungIME( 1838): [SwiftkeyWrapper] currentLangauge : 1701729619
,E/Zygote  ( 4230): MountEmulatedStorage()
E/Zygote  ( 4230): v2
I/libpersona( 4230): KNOX_SDCARD checking this for 1000
I/libpersona( 4230): KNOX_SDCARD not a persona
,I/SELinux ( 4230): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4230): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1018): Start proc com.sec.knox.knoxsetupwizardclient for broadcast com.sec.knox.knoxsetupwizardclient/.detector.SetupWizardDetectorReceiver: pid=4230 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/SELinux ( 4230): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/DBG_POLICYDM( 4177): [com.policydm.db.XDB(1530/xdbDMffs_Init)] xdbDMffs_Init
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,E/        ( 3968): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3968): took 0.715104ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3968): Bitmap=0xb7ff3be0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7fabe70 counterpartCT=4 counterpartW=96 counterparth=96
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_3342/cgroup.procs: No such file or directory
,I/AMMetaDataParserService( 3968): Icon data: ResourceDelete2131690186android.intent.assistant.detail.delete2130837528
,D/GCMRegistrar( 3375): resetting backoff for com.dropbox.android
,V/GCMRegistrar( 3375): Registering app com.dropbox.android of senders 735665981150
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.dropbox.android, destAppInfo.processName = com.google.process.gapps
,D/TimaKeyStoreProvider( 4230): TimaSignature is unavailable
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,D/ActivityThread( 4230): Added TimaKeyStore provider
,I/DBG_POLICYDM( 4177): [com.policydm.adapter.XDMTargetAdapter(263/xdmInitExternalStorageState)] bExternalStorageAvailable [true]
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
I/DBG_POLICYDM( 4177): [com.policydm.adapter.XDMTargetAdapter(264/xdmInitExternalStorageState)] bExternalSDStorageAvailable [false]
,I/DBG_POLICYDM( 4177): [com.policydm.XDMApplication(638/xdmWakeLockRelease)] 
,I/DBG_POLICYDM( 4177): [com.policydm.XDMApplication(643/xdmWakeLockRelease)] m_WakeLock is release!!
,I/DBG_POLICYDM( 4177): [com.policydm.XDMApplication(219/onCreate)] DMApplication Start !
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0,
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms,
,I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.samsung.contacts.detail.SelectContactInfoActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.contacts.activities.ConfirmAddDetailActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorAccountsChangedActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.samsung.contacts.activities.RingtoneRecommendationHelperActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.samsung.contacts.editor.AddAnotherFieldDialogActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.contacts.activities.AttachPhotoActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.contacts.activities.PhotoSelectionActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.contacts.common.vcard.ImportVCardActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportVCardPreviewActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.contacts.common.vcard.NfcImportVCardActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.contacts.common.vcard.CancelActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.contacts.common.vcard.SelectAccountActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.contacts.common.vcard.ExportVCardActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportFinishActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.samsung.contacts.activities.SIMContactSelectionActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbers
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbersTabActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.samsung.contacts.activities.VerizonBackupAssistantActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.contacts.widget.PinnedHeaderListDemoActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.contacts.NonPhoneActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.samsung.contacts.favorite.FavoriteSelectionActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.samsung.contacts.detail.SetDefaultActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.samsung.contacts.group.GroupChangeOrderActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.samsung.contacts.editor.EditGroupSelectionActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.samsung.contacts.group.GroupMultiSelectionActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.samsung.contacts.emergency.InteractionEmergencyMessageActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.samsung.contacts.emergency.EmergencyMessageContactCreateActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.samsung.contacts.emergency.EmergencyContactListDialogActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.samsung.contacts.group.SubGroupDetailActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.samsung.contacts.activities.GroupListActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activit,ycom.samsung.dialer.calllog.CallDurationActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDurationTabActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.samsung.contacts.detail.LinkedContactActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.samsung.dialer.impl.DialerTutorialActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpPeopleActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyPeopleActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpInteractionTabActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyInteractionTabActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpSpeedDialActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactEditorActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactSelectionActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.samsung.contacts.activities.EasyPeopleActivity
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:assistant
I/AMMetaDataParserService( 3968): Resource data:2131034113
I/AMMetaDataParserService( 3968): getResourceName:com.android.contacts:xml/assistant_main
I/AMMetaDataParserService( 3968): getResourceTypeNamexml
E/        ( 3968): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3968): took 0.849635ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3968): Bitmap=0xb7d22630 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7ff72a0 counterpartCT=4 counterpartW=96 counterparth=96
D/GCM     ( 1637): GcmService start Intent { act=com.google.android.c2dm.intent.REGISTER pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.c2dm.intent.REGISTER
D/ActivityManager( 1018): startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
I/AMMetaDataParserService( 3968): Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
E/Zygote  ( 4249): MountEmulatedStorage()
E/Zygote  ( 4249): v2
I/libpersona( 4249): KNOX_SDCARD checking this for 10035
I/libpersona( 4249): KNOX_SDCARD not a persona
I/SELinux ( 4249): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 4249): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1018): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=4249 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux ( 4249): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1018): Killing 3293:com.google.android.configupdater/u0a86 (adj 15): empty #31
E/        ( 3968): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3968): took 0.866979ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3968): Bitmap=0xb7d22630 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7c147a0 counterpartCT=4 counterpartW=96 counterparth=96
,I/ActivityManager( 1018): Killing 3375:com.dropbox.android/u0a92 (adj 15): empty #31
,I/AMMetaDataParserService( 3968): Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
E/KnoxSetupWizardClient( 4230): isShipMode : 1
I/KnoxSetupWizardClient( 4230): onReceive : android.intent.action.BOOT_COMPLETED
D/TimaKeyStoreProvider( 4249): TimaSignature is unavailable
,D/ActivityThread( 4249): Added TimaKeyStore provider
,I/DBG_POLICYDM( 4177): [com.policydm.agent.XDMTask(170/xdmAgentTaskHandler)] XEVENT_DM_INIT
,I/DBG_POLICYDM( 4177): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,D/ActivityManager( 1018): startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0,
E/        ( 3968): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3968): took 0.608437ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3968): Bitmap=0xb7fad388 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7fabe70 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3968): Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,W/art     ( 3770): Suspending all threads took: 49.399ms
,I/DBG_POLICYDM( 4177): [com.policydm.XDMApplication(677/xdmGetNotibarState)] get NotibarState : 9,
,I/DBG_POLICYDM( 4177): [com.policydm.ui.XUINotificationManager(47/xuiSetIndicator)] Indicator id : 9
,I/DBG_POLICYDM( 4177): [com.policydm.XDMApplication(669/xdmSetNotibarState)] set NotibarState : 9
,E/Zygote  ( 4269): MountEmulatedStorage(),
E/Zygote  ( 4269): v2
I/libpersona( 4269): KNOX_SDCARD checking this for 10107
,I/libpersona( 4269): KNOX_SDCARD not a persona
,I/SELinux ( 4269): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4269): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4269): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1018): Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=4269 uid=10107 gids={50107, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
I/ActivityManager( 1018): Killing 3432:com.fmm.ds/1000 (adj 15): empty #31
,D/ActivityManager( 1018): bindService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms, action: null
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: com.google.android.talk.SOFT_BIND
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.VideoChatService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,E/        ( 3968): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3968): took 0.605000ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3968): Bitmap=0xb7ff7460 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7ff72a0 counterpartCT=4 counterpartW=96 counterparth=96
,W/System.err( 4230): java.lang.IllegalArgumentException: Unknown package: com.sec.knox.setupwizardstub
,E/SMD     (  289): DCD OFF
,I/AMMetaDataParserService( 3968): Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,I/DBG_POLICYDM( 4177): [com.policydm.db.XDBAESCrypt(216/xdbGetCryptionkey)] try read dbString
D/TimaKeyStoreProvider( 4269): TimaSignature is unavailable
,W/System.err( 4230): 	at android.os.Parcel.readException(Parcel.java:1544)
W/System.err( 4230): 	at android.os.Parcel.readException(Parcel.java:1493)
D/ActivityThread( 4269): Added TimaKeyStore provider
,W/System.err( 4230): 	at android.content.pm.IPackageManager$Stub$Proxy.setApplicationEnabledSetting(IPackageManager.java:4212)
W/System.err( 4230): 	at android.app.ApplicationPackageManager.setApplicationEnabledSetting(ApplicationPackageManager.java:1948)
,W/System.err( 4230): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.processInternal(StubPackageThread.java:88)
,W/System.err( 4230): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.run(StubPackageThread.java:49)
,E/        ( 3968): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3968): took 0.826041ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3968): Bitmap=0xb7ff3f60 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7c147a0 counterpartCT=4 counterpartW=96 counterparth=96
,I/DBG_POLICYDM( 4177): [com.policydm.db.XDBFumoAdp(427/xdbGetFUMOStatus)] xdbGetFUMOStatus : 0
,I/DBG_POLICYDM( 4177): [com.policydm.db.XDBFumoAdp(586/xdbGetFUMOInitiatedType)] Initiated Type: 0
,I/AMMetaDataParserService( 3968): Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,I/DBG_POLICYDM( 4177): [com.policydm.agent.XDMUITask(190/xdmUIEvent)] XUI_DM_IDLE_STATE :true
,I/DBG_POLICYDM( 4177): [com.policydm.polling.XPollingAgent(71/xpollingCheckVersionInfo)] 
,I/DBG_POLICYDM( 4177): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/DBG_POLICYDM( 4177): [com.policydm.db.XDBProfileListAdp(257/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,I/SecDataIO(  257): Write to block
,I/System.out( 1637): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 1637): (HTTPLog)-Static: isSBSettingEnabled false
,W/libprocessgroup( 1018): failed to open /acct/uid_10086/pid_3293/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_10092/pid_3375/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_3432/cgroup.procs: No such file or directory
,W/ContextImpl( 2583): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendStickyBroadcast:1865 android.content.ContextWrapper.sendStickyBroadcast:463 com.sec.android.app.sysscope.service.h.run:-1 java.lang.Thread.run:818 <bottom of call stack> 
,D/StatusBar.NetworkController( 1180): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1180): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/System.out( 1637): (HTTPLog)-Static: isShipBuild true
D/Finsky  ( 4098): [1] GmsCoreHelper.cleanupNlp: result=false type=4
I/System.out( 1637): (HTTPLog)-Thread-187-186059438: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 1637): (HTTPLog)-Static: isSBSettingEnabled false
,I/DBG_POLICYDM( 4177): [com.policydm.noti.XNOTIAdapter(398/xnotiPushAdpExcuteResumeNoti)] nSessionSaveState:0,
D/EnterpriseController(  279): uids 10012
D/EnterpriseController(  279): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 502 for uid 10012
,I/DBG_POLICYDM( 4177): [com.policydm.polling.XPollingAgent(270/xpollingCheckTimer)] 
D/ActivityManager( 1018): startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
I/DBG_POLICYDM( 4177): [com.policydm.noti.XNOTIAdapter(399/xnotiPushAdpExcuteResumeNoti)] nNotiUiEvent:0
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.RestoreService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,E/        ( 3968): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3968): took 0.635573ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3968): Bitmap=0xb7ff3be0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7fabe70 counterpartCT=4 counterpartW=96 counterparth=96
,I/DBG_POLICYDM( 4177): [com.policydm.noti.XNOTIAdapter(400/xnotiPushAdpExcuteResumeNoti)] nNotiRetryCount:0
,I/DBG_POLICYDM( 4177): [com.policydm.noti.XNOTIAdapter(440/xnotiPushAdpExcuteResumeNoti)] Current NOTI NOT SAVED State. EXIT.
,I/DBG_DM  ( 3176): [com.wssyncmldm.llIlIIIIlIIIIIlIlIII(352/onReceive)] com.sec.intent.action.SYSSCOPESTATUS
,I/AMMetaDataParserService( 3968): Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,I/DBG_DM  ( 3176): [com.wssyncmldm.llIlIIIIlIIIIIlIlIII(356/onReceive)] status  = 1
,E/DBG_DM  ( 3176): [com.wssyncmldm.llIlIIIIlIIIIIlIlIII(367/onReceive)] Device is ok
,I/Process ( 2583): Sending signal. PID: 2583 SIG: 9
I/DBG_POLICYDM( 4177): [com.policydm.noti.XNOTIAdapter(266/xnotiPushAdpClearSessionStatus)] 
,I/DBG_POLICYDM( 4177): [com.policydm.polling.XPollingAgent(284/xpollingCheckTimer)] savedpollingtime : 2015/12/07/13:43:02
,I/DBG_DM  ( 3176): [com.wssyncmldm.XDMService(639/llllIIIllIlIIIIllllI)] TopActivity : com.example.hello.MainActivity
,E/        ( 3968): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3968): took 0.704740ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3968): Bitmap=0xb7fb23f8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7ff72a0 counterpartCT=4 counterpartW=96 counterparth=96
,I/DBG_POLICYDM( 4177): [com.policydm.polling.XPollingAgent(285/xpollingCheckTimer)] currentTime : 2015/12/02/18:46:29
,I/DBG_POLICYDM( 4177): [com.policydm.ui.XUIAdapter(40/xuiAdpSetUiMode)] nDmUiMode : 0
I/System.out( 1637): KnoxVpnUidStorageknoxVpnSupported API value returned is false
I/DBG_POLICYDM( 4177): [com.policydm.polling.XPollingAgent(289/xpollingCheckTimer)] Restart Timer..
E/SPPClientService( 4249): ============PushLog. commonIsShipBuild. stop!
,E/SPPClientService( 4249): [PushClientApplication] Push log off : This is Ship build version
,I/DBG_POLICYDM( 4177): [com.policydm.XDMApplication(684/xdmStartAlarm)] Alarm ID: 0
I/AMMetaDataParserService( 3968): Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
,E/SPPClientService( 4249): [[SystemStateMoniter]] ACTION_BOOT_COMPLETED
,I/DBG_POLICYDM( 4177): [com.policydm.db.XDBFumoAdp(438/xdbSetFUMOStatus)] xdbSetFUMOStatus : 0
,D/Finsky  ( 4098): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,E/        ( 3968): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3968): took 0.665000ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3968): Bitmap=0xb7fd5e08 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7fabe70 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3968): Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,I/ActivityManager( 1018): Process com.sec.android.app.sysscope (pid 2583)(adj 0) has died(91,1119)
,D/SPPClientService( 4249): PushLog.txt file is not deleted.
,D/SPPClientService( 4249): PushLog.txt file is not deleted.
D/SPPClientService( 4249): ============PushLog. stop!
,I/DBG_POLICYDM( 4177): [com.policydm.polling.XPollingAgent(311/xPollingReportReStartAlarm)] 
,E/SQLiteLog( 4045): (284) automatic index on conversation_participants_view(conversation_id)
,I/DBG_POLICYDM( 4177): [com.policydm.db.XDBFumoAdp(564/xdbSetFUMOInitiatedType)] Initiated Type: 0
,D/ActivityManager( 1018): startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.samsung.contacts.interactions.EasyInteractionTabActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.samsung.dialer.calllog.LogsFindoSearchResultsActivity
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
I/AMMetaDataParserService( 3968): getResourcePackageName:android.app.searchable
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.samsung.dialer.dialpad.RegularSearchActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.samsung.dialer.interaction.InteractionRecentActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.samsung.contacts.editor.SamsungAccountValidationCheckActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.samsung.contacts.autolink.AutoLinkActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.samsung.contacts.activities.EmergencyPeopleActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.samsung.contacts.speeddial.SpeedDialActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.samsung.contacts.businesscard.BusinesscardListActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.samsung.contacts.businesscard.BusinesscardViewer
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.samsung.dialer.callmessage.CallMessageActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.samsung.dialer.callmessage.RecentCallMessageActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.samsung.dialer.callmessage.PhrasesEditActivity
W/ContextImpl( 3968): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.samsung.dialer.callmessage.PhrasesDeleteActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.samsung.dialer.callmessage.CallMessageEditActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.samsung.contacts.emergency.MyEmergencyInfoDetailActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.samsung.contacts.emergency.MyEmergencyInfoEditorActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.samsung.contacts.activities.ScoverFavoritesActivity
,I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3968): getResourcePackageName:com.sec.android.sdk.cover.MODE
,I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.samsung.contacts.activities.ScoverSelectNumberActivity
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.sec.android.sdk.cover.MODE
,I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.samsung.contacts.detail.ShowMyProfileActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionProfileWhiteListActivity
,E/SQLiteLog( 4045): (284) automatic index on conversation_participants_view(conversation_id),
,E/Zygote  ( 4297): MountEmulatedStorage()
,E/Zygote  ( 4297): v2
I/libpersona( 4297): KNOX_SDCARD checking this for 10041
I/libpersona( 4297): KNOX_SDCARD not a persona
,I/DBG_POLICYDM( 4177): [com.policydm.db.XDB(1824/xdbSetBackUpServerUrl)] 
,I/SELinux ( 4297): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4297): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1018): Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.broadcastreceiver.StdBroadcastReceiver: pid=4297 uid=10041 gids={50041, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux ( 4297): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1018): Killing 3325:com.google.android.googlequicksearchbox:search/u0a57 (adj 15): empty #31
,I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.email.activity.setup.SSLCertValidationActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.email.activity.EmailUpgradeKeystoreActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.email.activity.SecurityCertificates
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.email.activity.Welcome
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.email.activity.UpgradeAccounts
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupWizard
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.email.activity.setup.snc.VZWSetupWizard
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncRestoreAccounts
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.email.activity.setup.snc.SncRestoreAccounts
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncRestoreOptions
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncNames
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncExchangeAccounts
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncAccountsLogin
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.email.activity.setup.LDAPClientSettings
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.email.activity.LDAPAccountsList
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupBasics
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.email.DataConnection
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupAccountType
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupIncoming
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupOutgoing
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupExchange
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupOptions
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupNames
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsXL
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsAddRulesforFiltering
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.email.activity.setup.AddPrioritySenderActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSecurity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.email.activity.setup.AccountPreSetup
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.email.messageview.SaveasActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.email.activity.Debug
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.email.activity.MessageListXL
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:assistant
I/AMMetaDataParserService( 3968,): Resource data:2131165203
D/TimaKeyStoreProvider( 4297): TimaSignature is unavailable
I/DBG_POLICYDM( 4177): [com.policydm.XDMApplication(684/xdmStartAlarm)] Alarm ID: 1
D/ActivityThread( 4297): Added TimaKeyStore provider
W/ResourcesManager( 3968): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 3968): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3968): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 3968): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3968): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
E/SQLiteLog( 4045): (284) automatic index on conversation_participants_view(conversation_id)
I/AMMetaDataParserService( 3968): getResourceName:com.android.email:xml/email_assistant_menu
I/AMMetaDataParserService( 3968): getResourceTypeNamexml
I/DBG_POLICYDM( 4177): [com.policydm.agent.XDMTask(195/xdmAgentTaskHandler)] XEVENT_DM_INIT : Initialized
E/        ( 3968): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX construct_block_size_descriptor_2d second part( 3968): took 2.875469ms for 0*0 texture 0
,I/GFX generate_partition_tables( 3968): took 10.428490ms for 0*0 texture 0
,I/GFX raster( 3968): took 14.283594ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3968): Bitmap=0xb81a6228 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb7f95460 counterpartCT=4 counterpartW=96 counterparth=96
,E/SQLiteLog( 4045): (284) automatic index on conversation_participants_view(conversation_id)
,I/AMMetaDataParserService( 3968): Icon data: ResourceDrawer menu2131363563com.android.email.intent.messagelistfragment.drawer2130837576
,E/SQLiteLog( 4045): (284) automatic index on conversation_participants_view(conversation_id)
,E/        ( 3968): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3968): took 0.872083ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3968): Bitmap=0xb7f95460 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7c6fb78 counterpartCT=4 counterpartW=96 counterparth=96
,I/ActivityManager( 1018): Killing 3456:com.samsung.android.intelligenceservice/u0a3 (adj 15): empty #31
,I/AMMetaDataParserService( 3968): Icon data: ResourceMessage marked as complete2131362386com.android.email.intent.messageviewfragment.favorite2130837575
,E/        ( 3968): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3968): took 0.765469ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3968): Bitmap=0xb7f95460 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7c6fb78 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3968): Icon data: ResourceFlagged message2131362384com.android.email.intent.messageviewfragment.favorite2130837575
,I/DBG_DM  ( 3176): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 7 sec
,I/DBG_DM  ( 3176): [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,I/DBG_DM  ( 3176): [com.wssyncmldm.XDMService(639/llllIIIllIlIIIIllllI)] TopActivity : com.example.hello.MainActivity
,I/DBG_DM  ( 3176): [IIlIIIlllllIIlIIIlII(91/llllIIIllIlIIIIllllI)] 
,W/libprocessgroup( 1018): failed to open /acct/uid_10057/pid_3325/cgroup.procs: No such file or directory
,W/libprocessgroup( 1018): failed to open /acct/uid_10003/pid_3456/cgroup.procs: No such file or directory
,E/        ( 3968): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3968): took 0.791562ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3968): Bitmap=0xb7f95460 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7c6fb78 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3968): Icon data: ResourceUnflagged message2131362385com.android.email.intent.messageviewfragment.favorite2130837575
,I/SA      ( 4297): [SSP] onCreated
,D/ActivityManager( 1018): bindService callerProcessName:com.google.android.apps.maps, calleePkgName: com.google.android.gms, action: null
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,I/DBG_DM  ( 3176): [com.wssyncmldm.db.file.XDB(3660/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,E/        ( 3968): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3968): took 0.626719ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3968): Bitmap=0xb7c6fb78 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7fc9d88 counterpartCT=4 counterpartW=96 counterparth=96
,V/AlarmManager( 1018): waitForAlarm result :4
,I/AMMetaDataParserService( 3968): Icon data: ResourceStarred message2131362389com.android.email.intent.messageviewfragment.favorite2130837577
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService; callingUser = 0; userId(target) = 0
,I/DBG_DM  ( 3176): [com.wssyncmldm.db.file.XDB(5479/llIlIIIIlllIlllllIll)] Download Postpone status : 0
,I/SA      ( 4297): [TPM] There is no property file
,I/SA      ( 4297): [SCU] isHaveSA() - false
,D/StrictMode( 4269): StrictMode policy violation; ~duration=386 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4269): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4269): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 4269): 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
D/StrictMode( 4269): 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
D/StrictMode( 4269): 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
D/StrictMode( 4269): 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
D/StrictMode( 4269): 	at java.lang.System.loadLibrary(System.java:989)
D/StrictMode( 4269): 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:189)
D/StrictMode( 4269): 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:1060)
D/StrictMode( 4269): 	at com.google.android.apps.gmm.base.app.a.a(PG:82)
D/StrictMode( 4269): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4269): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4269): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4269): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4269): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4269): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4269): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4269): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4269): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4269): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4269): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4269): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4269): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,D/StrictMode( 4269): StrictMode policy violation; ~duration=376 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4269): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4269): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 4269): 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
D/StrictMode( 4269): 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
D/StrictMode( 4269): 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
D/StrictMode( 4269): 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
D/StrictMode( 4269): 	at java.lang.System.loadLibrary(System.java:989)
D/StrictMode( 4269): 	at com.google.android.apps.gmm.map.util.jni.NativeHelper.initialize(PG:48)
D/StrictMode( 4269): 	at com.google.android.apps.gmm.map.l.g.<clinit>(PG:92)
D/StrictMode( 4269): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4269): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4269): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4269): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4269): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4269): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4269): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4269): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4269): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4269): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4269): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4269): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4269): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4269): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4269): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 4269): StrictMode policy violation; ~duration=275 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4269): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4269): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 4269): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 4269): 	at java.io.File.exists(File.java:363)
D/StrictMode( 4269): 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
D/StrictMode( 4269): 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
D/StrictMode( 4269): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
D/StrictMode( 4269): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
D/StrictMode( 4269): 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
D/StrictMode( 4269): 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
D/StrictMode( 4269): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 4269): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 4269): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4269): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4269): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4269): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4269): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4269): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4269): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4269): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4269): 	at android.os.Hand,ler.dispatchMessage(Handler.java:102)
D/StrictMode( 4269): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4269): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4269): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4269): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4269): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4269): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
I/SA      ( 4297): [TPM] getModelProperty : null
D/StrictMode( 4269): StrictMode policy violation; ~duration=274 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4269): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4269): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 4269): 	at libcore.io.IoBridge.open(IoBridge.java:442)
D/StrictMode( 4269): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
D/StrictMode( 4269): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
D/StrictMode( 4269): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
D/StrictMode( 4269): 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
D/StrictMode( 4269): 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
D/StrictMode( 4269): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 4269): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 4269): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4269): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4269): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4269): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4269): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4269): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4269): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4269): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4269): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4269): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4269): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4269): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4269): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4269): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4269): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 4269): StrictMode policy violation; ~duration=274 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4269): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4269): 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
D/StrictMode( 4269): 	at libcore.io.IoBridge.open(IoBridge.java:445)
D/StrictMode( 4269): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
D/StrictMode( 4269): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
D/StrictMode( 4269): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
D/StrictMode( 4269): 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
D/StrictMode( 4269): 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
D/StrictMode( 4269): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 4269): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 4269): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4269): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4269): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4269): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4269): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4269): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4269): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4269): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4269): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4269): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4269): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4269): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4269): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4269): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4269): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
I/SA      ( 4297): [TPM] getCSCProperty : null
D/StrictMode( 4269): StrictMode policy violation; ~duration=272 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4269): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4269): 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
D/StrictMode( 4269): 	at libcore.io.IoBridge.read(IoBridge.java:472)
D/StrictMode( 4269): 	at java.io.FileInputStream.read(FileInputStream.java:177)
D/StrictMode( 4269): 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
D/StrictMode( 4269): 	at java.io.DataInputStream.read(DataInputStream.java:63)
D/StrictMode( 4269): 	at com.google.r.k.c(PG:1187)
D/StrictMode( 4269): 	at com.google.r.k.a(PG:2107)
D/StrictMode( 4269): 	at com.google.v.a.a.eq.<init>(PG:23)
D/StrictMode( 4269): 	at com.google.v.a.a.eq.a(PG:12397)
D/StrictMode( 4269): 	at com.google.r.v.a(PG:1206)
D/StrictMode( 4269): 	at com.google.r.y.a(PG:2233)
D/StrictMode( 4269): 	at com.google.r.e.b(PG:170)
D/StrictMode( 4269): 	at com.google.r.e.b(PG:13188)
D/StrictMode( 4269): 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
D/StrictMode( 4269): 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
D/StrictMode( 4269): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 4269): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 4269): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4269): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4269): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4269): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4269): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4269): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4269): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4269): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4269): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4269): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4269): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4269): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4269): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4269): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4269): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 4269): StrictMode policy violation; ~duration=267 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4269): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4269): 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
D/StrictMode( 4269): 	at libcore.io.IoBridge.read(IoBridge.java:472)
D/StrictMode( 4269): 	at java.io.FileInputStream.read(FileInputStream.java:177)
D/StrictMode( 4269): 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
D/StrictMode( 4269): 	at java.io.DataInputStream.read(DataInputStream.java:63)
D/StrictMode( 4269): 	at com.google.r.k.c(PG:1187)
D/StrictMode( 4269): 	at com.google.r.k.b(PG:14147)
D/StrictMode( 4269): 	at com.google.r.k.c(PG:583)
D/StrictMode( 4269): 	at com.google.v.a.a.eq.<init>(PG:40)
D/StrictMode( 4269): 	at com.google.v.a.a.eq.a(PG:12397)
D/StrictMode( 4269): 	at com.google.r.v.a(PG:1206)
D/StrictMode( 4269): 	at com.google.r.y.a(PG:2233)
D/StrictMode( 4269): 	at com.google.r.e.b(PG:170)
D/StrictMode( 4269): 	at com.google.r.e.b(PG:13188)
D/StrictMode( 4269): 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
D/StrictMode( 4269): 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
D/StrictMode( 4269): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 4269): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 4269): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4269): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4269): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4269): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4269): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4269): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4269): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4269): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4269): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4269): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4269): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4269): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4269): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4269): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4269): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 4269): StrictMode policy violation; ~duration=223 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4269): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4269): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 4269): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 4269): 	at java.io.File.exists(File.java:363)
D/StrictMode( 4269): 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
D/StrictMode( 4269): 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
D/StrictMode( 4269): 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
D/StrictMode( 4269): 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
D/StrictMode( 4269): 	at com.google.android.apps.gmm.map.l.s.a(PG:7690)
D/StrictMode( 4269): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 4269): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 4269): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4269): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4269): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4269): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4269): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4269): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4269): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4269): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4269): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4269): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4269): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4269): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4269): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4269): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4269): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 4269): StrictMode policy violation; ~duration=222 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4269): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4269): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 4269): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 4269): 	at java.io.File.exists(File.java:363)
D/StrictMode( 4269): 	at com.google.android.apps.gmm.map.l.s.a(PG:7692)
D/StrictMode( 4269): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 4269): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 4269): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4269): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4269): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4269): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4269): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4269): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4269): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4269): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4269): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4269): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4269): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4269): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4269): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4269): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4269): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/ActivityManager( 1018): startProcessLocked calleePkgName: com.sec.android.app.mt, hostingType: broadcast
I/SA      ( 4297): [DM] FLOATING AMOLED FEATURE: true
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
I/SA      ( 4297): [DM] PRODUCT AMOLED FEATURE: false
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
I/SA      ( 4297): [DM] TFT FEATURE: false
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/        ( 3968): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
I/GFX raster( 3968): took 0.601979ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3968): Bitmap=0xb7c6fb78 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7fc86b0 counterpartCT=4 counterpartW=96 counterparth=96
I/DBG_DM  ( 3176): [com.wssyncmldm.db.file.XDB(6236/IlIIlIIlIllllIlllIII)] Initiated Type: 2
I/DBG_DM  ( 3176): [IlIlllIlllllIlIllllI(102/lllIlIlIIIllIIlIllIl)] nStatus [220]
I/AMMetaDataParserService( 3968): Icon data: ResourceUnstarred message2131362390com.android.email.intent.messageviewfragment.favorite2130837577
I/libpersona( 4319): KNOX_SDCARD checking this for 1000
I/SA      ( 4297): [SBR] StdBroadcastReceiver received Intent of  action_BOOT_COMPLETED extra.user_handle.:0
I/libpersona( 4319): KNOX_SDCARD not a persona
I/SA      ( 4297): [DM] init START
I/ActivityManager( 1018): Start proc com.sec.android.app.mt for broadcast com.sec.android.app.mt/.StatusChecker: pid=4319 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SA      ( 4297): [DM] This device is not a Vodafone
I/ActivityManager( 1018): Killing 3474:com.dropbox.android:crash_uploader/u0a92 (adj 15): empty #31
I/DBG_DM  ( 3176): [IlIlllIlllllIlIllllI(251/lllIlIlIIIllIIlIllIl)] XDL_STATE_READY_TO_UPDATE
E/Zygote  ( 4319): MountEmulatedStorage()
E/Zygote  ( 4319): v2
I/SELinux ( 4319): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 4319): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 4319): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/DBG_DM  ( 3176): [llllIIIllIllIlllIIlI(772/llIIIIlllllIIllIIllI)] XUI_DL_UPDATE_START
,W/ResourceType( 4297): Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
W/ResourceType( 4297): Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
W/ResourceType( 4297): Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
I/DBG_POLICYDM( 4177): [com.policydm.db.XDBProfileListAdp(257/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
I/DBG_DM  ( 3176): [llllIlllIIIlIlIlIIII(49/llIIIIlllllIIllIIllI)] 
W/ResourceType( 4297): Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
W/ResourceType( 4297): Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
I/DBG_DM  ( 3176): [IlIIlIIlIllllIlllIII(274/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT : Initialized
W/ResourceType( 4297): Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
W/ResourceType( 4297): Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
I/DBG_DM  ( 3176): [IlIIlIIlIllllIlllIII(1901/llllIIIllIlIIIIllllI)] 
I/DBG_DM  ( 3176): [IIllIIIIlIlIlIlIllII(49/IIIlIIllIlIIllIlllII)] FirmwareObjectSize:308289685
I/DBG_DM  ( 3176): [com.wssyncmldm.DMSecBroadcastReceiver(572/llIIIIlllllIIllIIllI)] m_IsSavedNfcMode : false
I/DBG_DM  ( 3176): [IIllIIIIlIlIlIlIllII(1715/llllllIllIlIlllIIlIl)] 
W/ResourceType( 4297): No package identifier when getting value for resource number 0x00000000
W/ResourceType( 4297): Failure getting entry for 0x7f060027 (t=5 e=39) (error -75)
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.email.activity.setup.MailboxSettings
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.email.messageview.SelectGroup
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.email.messageview.SavedEmail
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.email.messageview.MessageFileView
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsHtmlSignature
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.email.activity.MessageCompose
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:android.app.spellscroll
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.email.activity.SelectMapActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.email.activity.CustomizeDate
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.email.activity.QuickReplyActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.email.activity.SettingsReservationActivity
W/ContextImpl( 3968): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.email.activity.AttachmentChooserActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.email.activity.DebugActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupBasicsChoiceProviderForKOR
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSoundNotiSetup
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSoundNotiGeneralPreference
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.email.activity.SearchActivity
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3968): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.email.activity.MessageComposeDrawingModePopup
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.email.activity.utils.airjump.EmailAirScrollTryActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.email.activity.SmartStayActivity
I/DBG_DM  ( 3176): [com.wssyncmldm.ui.llllIIIllIlIIIIllllI(503/lllIlIlIIIllIIlIllIl)] Get bUpdateReport = false
W/ResourceType( 4297): Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
W/ResourceType( 4297): Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
W/ResourceType( 4297): Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
W/ResourceType( 4297): Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
W/ResourceType( 4297): Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
W/ResourceType( 4297): Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
W/ResourceType( 4297): Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
W/ResourceType( 4297): Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
W/ResourceType( 4297): Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
W/ResourceType( 4297): Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
W/ResourceType( 4297): Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
W/ResourceType( 4297): Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
W/ResourceType( 4297): Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
W/ResourceType( 4297): Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
,I/DBG_POLICYDM( 4177): [com.policydm.db.XDBNotiAdp(37/xdbNotiExistInfo)] Noti Exist : false
,W/ResourceType( 4297): Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
,W/ResourceType( 4297): Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
,I/SA      ( 4297): [SCU] isHaveSA() - false
I/SA      ( 4297): support phone number id : false
I/SA      ( 4297): [DM] Supports Ref Jpn : true
I/SA      ( 4297): [DM] init END
,I/DBG_DM  ( 3176): [com.wssyncmldm.db.file.XDB(5178/IIIIlIllIlllIlIIIIlI)] Data Margin : 500
,I/iu.UploadsManager( 2000): End new media; added: 0, uploading: 0, time: 112 ms
,I/DBG_DM  ( 3176): [com.wssyncmldm.db.file.XDB(5298/IlIllIIIIllllllIlIIl)] Data App Weight : 0.0
,I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.mms.rcs.RcsNewFeatureActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.mms.ui.RoamingGuardPopupActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.mms.ui.AutoRetrievePreferenceActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.mms.ui.AutoRetrieveTabActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.mms.ui.ConversationComposer
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:android.app.spellscroll
I/AMMetaDataParserService( 3968): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 3968): getResourcePackageName:assistant
I/AMMetaDataParserService( 3968): Resource data:2131099648
,D/TimaKeyStoreProvider( 4319): TimaSignature is unavailable
,W/ResourcesManager( 3968): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 3968): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3968): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 3968): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3968): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 3968): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3968): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3968): getResourceTypeNamexml
I/SA      ( 4297): [OR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOH2 PSS = 4.978878039476607  ]
I/SA      ( 4297): [OR] onReceive Intent=[ action_BOOT_COMPLETED extra.user_handle.:0 ]
,E/        ( 3968): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3968): took 0.694583ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3968): Bitmap=0xb7fedbc0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7fd97e8 counterpartCT=4 counterpartW=96 counterparth=96
,D/ActivityManager( 1018): startService callerProcessName:com.osp.app.signin, calleePkgName: com.osp.app.signin
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.osp.app.signin/com.osp.app.signin.BootDbCheck; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.osp.app.signin, destAppInfo.processName = com.osp.app.signin
,D/ActivityThread( 4319): Added TimaKeyStore provider
,I/SA      ( 4297): [OR] onReceive END
,D/ActivityManager( 1018): startProcessLocked calleePkgName: com.android.providers.calendar, hostingType: broadcast
,I/AMMetaDataParserService( 3968): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/DBG_DM  ( 3176): [com.wssyncmldm.db.file.XDB(5258/llllIIlIlIIIIllIlIIl)] Delta Weight : 0.5
I/DBG_DM  ( 3176): [com.wssyncmldm.db.file.llllIIIllIlIIIIllllI(194/llIIIIlllllIIllIIllI)] ### Data Margin only: 678432842
I/DBG_DM  ( 3176): [com.wssyncmldm.llIIllllIIlllIIIIlll(1125/handleMessage)] event ->220
,E/        ( 3968): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96,
,I/GFX construct_block_size_descriptor_2d second part( 3968): took 2.394636ms for 0*0 texture 0,
I/SA      ( 4297): [TPMU]  strSIMState ,	:SIM_STATE_ABSENT,
I/SA      ( 4297): [ODM] queryOpenData(key= GEO_IP ),
,I/GFX generate_partition_tables( 3968): took 8.637500ms for 0*0 texture 0,
I/GFX raster( 3968): took 11.977918ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3968): Bitmap=0xb7fdcf50 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb7fdd088 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3968): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,I/SA      ( 4297): getMccForGalaxyJpn step2 GEO_IP MCC : 260,
I/SA      ( 4297): [LBE] REF_JPN : true,
I/SA      ( 4297): [BDC] create
,I/ActivityManager( 1018): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarReceiver: pid=4337 uid=10042 gids={50042, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,D/ActivityManager( 1018): bindService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gms, action: com.google.android.gms.analytics.service.START,
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023,
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,I/DBG_DM  ( 3176): [com.wssyncmldm.XDMService(639/llllIIIllIlIIIIllllI)] TopActivity : com.example.hello.MainActivity,
E/        ( 3968): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3968): took 0.627761ms for 96*96 texture 0,
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3968): Bitmap=0xb84fd1f8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb84fd330 counterpartCT=4 counterpartW=96 counterparth=96,
I/DBG_DM  ( 3176): [com.wssyncmldm.XDMService(712/lllIIIIllIlIlllllllI)] 
,E/Zygote  ( 4337): MountEmulatedStorage(),
E/Zygote  ( 4337): v2,
,I/GAV2    ( 3803): Thread[GAThread,5,main]: No campaign data found.
I/DBG_DM  ( 3176): [com.wssyncmldm.db.file.XDB(5018/IIllIIllIIIlllIlIIll)] Get Autoinstall status : false
,I/AMMetaDataParserService( 3968): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
W/libprocessgroup( 1018): failed to open /acct/uid_10092/pid_3474/cgroup.procs: No such file or directory,
I/art     ( 1637): Explicit concurrent mark sweep GC freed 11528(694KB) AllocSpace objects, 8(320KB) LOS objects, 40% free, 10MB/18MB, paused 1.135ms total 71.761ms
,I/DBG_DM  ( 3176): [llllIIIllIllIlllIIlI(726/llIIIIlllllIIllIIllI)] XUI_DL_UPDATE_CONFIRM
I/libpersona( 4337): KNOX_SDCARD checking this for 10042
I/libpersona( 4337): KNOX_SDCARD not a persona
I/SELinux ( 4337): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4337): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 4337): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,I/SA      ( 4297): [DBMV2] getEmailID
,W/ActivityManager( 1018): userId = 0, bbcId = -10000,
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/SA      ( 4297): [DBMV2] getDataV02ForItems
I/SA      ( 4297): [SSP] query invoked,
,I/DBG_DM  ( 3176): [com.wssyncmldm.XDMService(468/lIllIllllIIIlllIlllI)] ,
I/SA      ( 4297): [SCU] get signed id from samsung account2.0 DB.
,I/DBG_DM  ( 3176): [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : false,
,E/DBG_DM  ( 3176): [com.wssyncmldm.XDMService(476/lIllIllllIIIlllIlllI)] didn't register
,E/DBG_DM  ( 3176): [com.wssyncmldm.XDMService(477/lIllIllllIIIlllIlllI)] java.lang.IllegalArgumentException: Receiver not registered: com.wssyncmldm.llIIIIlllllIIllIIllI@3a5aa479
,E/        ( 3968): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/SA      ( 4297): [SCU] get signed id from samsung account1.0 DB.
,I/SA      ( 4297): [BDC] destroy
,D/TimaKeyStoreProvider( 4337): TimaSignature is unavailable
D/ActivityThread( 4337): Added TimaKeyStore provider
,I/GFX raster( 3968): took 0.754062ms for 96*96 texture 0
I/ActivityManager( 1018): Killing 3496:com.samsung.android.scloud.backup/u0a60 (adj 15): empty #31
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3968): Bitmap=0xb84ff378 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb84ff420 counterpartCT=4 counterpartW=96 counterparth=96
,I/DBG_DM  ( 3176): [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : false
,I/AMMetaDataParserService( 3968): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,I/DBG_DM  ( 3176): [com.wssyncmldm.ui.llllIIIllIlIIIIllllI(649/IIIIllIlIIlIIIIlllIl)] nWidgetStatus : 2
,W/ResourcesManager( 4337): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,W/ContextImpl( 3176): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.wssyncmldm.ui.llllIIIllIlIIIIllllI.IIIIllIlIIlIIIIlllIl:652 com.wssyncmldm.ui.lIlIIlIlIlIllllllIII.llIIIIlllllIIllIIllI:172 llllIIIllIllIlllIIlI.llIIIIlllllIIllIIllI:732 
,D/SettingsProvider( 1018): name = SOFTWARE_UPDATE_NOTIFICATION_STATUS
,E/        ( 3968): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3968): took 0.632917ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3968): Bitmap=0xb7fe22e8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7fd7cf8 counterpartCT=4 counterpartW=96 counterparth=96
,I/SecKeyguardClockSingleView( 1180): Ignore. Because it is same clock text
,I/AMMetaDataParserService( 3968): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,W/libprocessgroup( 1018): failed to open /acct/uid_10060/pid_3496/cgroup.procs: No such file or directory
,I/DBG_DM  ( 3176): [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(330/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,W/com.google.a.a.b.d.a( 4269): Application name is not set. Call Builder#setApplicationName.
,D/StatusChecker( 4319): onReceive : android.intent.action.BOOT_COMPLETED
,E/        ( 3968): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3968): took 0.726666ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3968): Bitmap=0xb7fd7cf8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7fd7150 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3968): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,I/DBG_DM  ( 3176): [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,I/StatusChecker( 4319): onReceive : net.mt.init : DONE
,D/ActivityManager( 1018): startProcessLocked calleePkgName: com.sec.android.pagebuddynotisvc, hostingType: broadcast
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4356): MountEmulatedStorage(),
I/libpersona( 4356): KNOX_SDCARD checking this for 10116
E/Zygote  ( 4356): v2
,I/libpersona( 4356): KNOX_SDCARD not a persona
I/SELinux ( 4356): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1018): Start proc com.sec.android.pagebuddynotisvc for broadcast com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvcBRcvr: pid=4356 uid=10116 gids={50116, 9997} abi=armeabi-v7a
I/SELinux ( 4356): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1018): Killing 3241:com.sec.android.fotaclient/u0a9 (adj 15): empty #31
E/SELinux ( 4356): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1018): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0,
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessageActivityNoLockScreen
,I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessageMms
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:assistant
I/AMMetaDataParserService( 3968): Resource data:2131099648
,I/AMMetaDataParserService( 3968): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3968): getResourceTypeNamexml
,D/SecContentProvider2( 1018): uri = 15 selection = getToastGravityEnabledState
E/        ( 3968): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
D/SecContentProvider2( 1018): mCursor = null
I/GFX raster( 3968): took 0.680677ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3968): Bitmap=0xb7fedbc0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb84ff668 counterpartCT=4 counterpartW=96 counterparth=96
,D/SecContentProvider2( 1018): uri = 15 selection = getToastGravity
D/SecContentProvider2( 1018): mCursor = null
I/DBG_DM  ( 3176): [com.wssyncmldm.ui.XUIFotaPostponeActivity(337/llIIIIlllllIIllIIllI)] 
D/WindowManager( 1018): showStatusBarByNotification() mOpenByNotification=false
W/NotificationService( 1018): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
D/SecContentProvider2( 1018): uri = 15 selection = getToastGravityXOffset
D/SecContentProvider2( 1018): mCursor = null
W/ResourcesManager( 1180): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
I/DBG_DM  ( 3176): [com.wssyncmldm.db.file.XDB(3660/lllIIIIllIlIlllllllI)] FUMO_Status : 220
I/AMMetaDataParserService( 3968): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,I/CalendarProvider2( 4337): CalendarProvider2.onCreate() called
,D/SecContentProvider2( 1018): uri = 15 selection = getToastGravityYOffset
D/SecContentProvider2( 1018): mCursor = null
,W/art     ( 3770): Suspending all threads took: 7.939ms
,D/TimaKeyStoreProvider( 4356): TimaSignature is unavailable
,D/ActivityThread( 4356): Added TimaKeyStore provider
,I/DBG_DM  ( 3176): [com.wssyncmldm.db.file.XDB(5457/lllIIIIllIlIlllllllI)] Set Download Postpone status : 8
,I/DBG_DM  ( 3176): [com.wssyncmldm.ui.XUIFotaPostponeActivity(386/llIIIIlllllIIllIIllI)] No idle Postpone
,E/        ( 3968): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3968): took 0.763958ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3968): Bitmap=0xb7fdcf50 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb8500788 counterpartCT=4 counterpartW=96 counterparth=96
,D/KnoxNotification( 1180): ----- inflateViews : modified publicViewLocal -----
,I/DBG_DM  ( 3176): [com.wssyncmldm.ui.XUIFotaPostponeActivity(474/llIIIIlllllIIllIIllI)] 
,D/SecContentProvider2( 1018): uri = 15 selection = getToastEnabledState
D/SecContentProvider2( 1018): mCursor = null
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,D/KnoxNotification( 1180): ----- inflateViews : modified KnoxViewLocal -----
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3968): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,D/PersonaManager( 1180): PersonaID is invalid or persona doesn't exists. : 0
,D/PersonaManager( 1180): isKioskContainerExistOnDevice
D/PersonaManager( 1180): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1180): Icon Only
,I/StatusBar( 1180): Icon Only
,D/PanelView( 1180): There is/are notification(s) 
D/PanelView( 1180): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1180): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1180): Icon Only
,I/StatusBar( 1180): Icon Only
D/PanelView( 1180): There is/are notification(s) 
D/PanelView( 1180): kidsfalse mQsExpansionEnabled:true
,I/PageBuddyNotiSvc( 4356): Intent received : action=android.intent.action.BOOT_COMPLETED
,E/        ( 3968): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3968): took 0.792396ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3968): Bitmap=0xb84fd1f8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb84fdec0 counterpartCT=4 counterpartW=96 counterparth=96
,W/ContextImpl( 4356): Implicit intents with startService are not safe: Intent { act=com.sec.android.pagebuddynotisvc } android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.pagebuddynotisvc.PageBuddyNotiSvcBRcvr.onReceive:-1 
,I/AMMetaDataParserService( 3968): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,W/libprocessgroup( 1018): failed to open /acct/uid_10009/pid_3241/cgroup.procs: No such file or directory
,E/        ( 3968): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3968): took 0.854010ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3968): Bitmap=0xb84ff378 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7fd8bc0 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3968): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,E/        ( 3968): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3968): took 0.625677ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3968): Bitmap=0xb7fe22e8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7fd7dd8 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3968): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,E/        ( 3968): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3968): took 0.718177ms for 96*96 texture 0,
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3968): Bitmap=0xb7fd7cf8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7fd9648 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3968): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,D/PanelView( 1180): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
,I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.mms.ui.TransferContentActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.mms.ui.CbConfigPreferenceActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.mms.ui.CbSettingTabActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessage
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:assistant
I/AMMetaDataParserService( 3968): Resource data:2131099648
,I/AMMetaDataParserService( 3968): getResourceName:com.android.mms:xml/assistant_messaging
,I/AMMetaDataParserService( 3968): getResourceTypeNamexml
,E/        ( 3968): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3968): took 0.679531ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3968): Bitmap=0xb7fedbc0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb85007f8 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3968): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,E/        ( 3968): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3968): took 0.716042ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3968): Bitmap=0xb7fdcf50 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb7fd7a08 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3968): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,E/        ( 3968): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3968): took 0.655052ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3968): Bitmap=0xb84fd1f8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb7fd7dd8 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3968): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,I/art     ( 1018): Explicit concurrent mark sweep GC freed 28791(1678KB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 26MB/40MB, paused 2.322ms total 160.182ms
,D/SecContentProvider2( 1018): uri = 15 selection = getToastShowPackageNameState
D/SecContentProvider2( 1018): mCursor = null
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.pagebuddynotisvc, destAppInfo.processName = com.sec.android.pagebuddynotisvc
,E/        ( 3968): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3968): took 0.690052ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3968): Bitmap=0xb84ff378 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb84fd330 counterpartCT=4 counterpartW=96 counterparth=96
,I/PageBuddyNotiSvc( 4356): onCreate mCpBitFlag=0
D/ActivityManager( 1018): startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/AMMetaDataParserService( 3968): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,D/OpenGLRenderer( 3176): Render dirty regions requested: true,
,E/        ( 3968): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3968): took 0.690312ms for 96*96 texture 0,
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3968): Bitmap=0xb7fe22e8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb84fd330 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3968): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
E/Zygote  ( 4376): MountEmulatedStorage()
I/libpersona( 4376): KNOX_SDCARD checking this for 10125
,E/Zygote  ( 4376): v2
I/libpersona( 4376): KNOX_SDCARD not a persona
,I/SELinux ( 4376): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/ActivityManager( 1018): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=4376 uid=10125 gids={50125, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,I/SELinux ( 4376): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4376): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,I/SurfaceFlinger(  258): id=12 createSurf (1x1),1 flag=4, Uoast
,D/ActivityManager( 1018): startService callerProcessName:com.android.providers.calendar, calleePkgName: com.android.providers.calendar
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,D/PowerManagerService( 1018): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1018
,D/TimaKeyStoreProvider( 4376): TimaSignature is unavailable
,D/ActivityThread( 4376): Added TimaKeyStore provider
D/SRIB_DCS( 3176): log_dcs ThreadedRenderer::initialize entered! 
,I/Adreno-EGL( 3176): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 3176): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 3176): Build Date: 04/06/15 Mon
I/Adreno-EGL( 3176): Local Branch: 
I/Adreno-EGL( 3176): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 3176): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 3176):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,I/OpenGLRenderer( 3176): Initialized EGL, version 1.4
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,E/        ( 3968): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3968): took 0.735937ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3968): Bitmap=0xb7fd7cf8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb84fd330 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3968): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,I/ActivityManager( 1018): Killing 3520:com.google.android.onetimeinitializer/u0a14 (adj 15): empty #31
,D/OpenGLRenderer( 3176): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
D/OpenGLRenderer( 3176): Enabling debug mode 0
,W/ResourcesManager( 4376): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4376): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 4376): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.mms.ui.ForwardMessageActivity
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:assistant
I/AMMetaDataParserService( 3968): Resource data:2131099648
,I/AMMetaDataParserService( 3968): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3968): getResourceTypeNamexml
,E/        ( 3968): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3968): took 0.718281ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3968): Bitmap=0xb7fedbc0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb84fd330 counterpartCT=4 counterpartW=96 counterparth=96
,W/art     ( 1863): Suspending all threads took: 5.085ms
,I/AMMetaDataParserService( 3968): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,I/art     ( 1863): Explicit concurrent mark sweep GC freed 15027(999KB) AllocSpace objects, 13(208KB) LOS objects, 40% free, 10MB/17MB, paused 7.284ms total 57.427ms
,E/        ( 3968): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3968): took 0.632604ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3968): Bitmap=0xb7fdcf50 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb7fb23c0 counterpartCT=4 counterpartW=96 counterparth=96
,D/QuickConnect( 4376): PeriphStartReceiver.onReceive - android.intent.action.BOOT_COMPLETED
,D/QuickConnect( 4376): Util.setSCRunningSetting - [value]0
,I/AMMetaDataParserService( 3968): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,D/SettingsProvider( 1018): name = scon_is_running
,D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 10125
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
,E/        ( 3968): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,W/BackupManagerService( 1018): dataChanged but no participant pkg='com.android.providers.settings' uid=10125
,I/GFX raster( 3968): took 0.687707ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3968): Bitmap=0xb84fd1f8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb84fd330 counterpartCT=4 counterpartW=96 counterparth=96
,I/QuickConnect( 4376): PeriphStartReceiver.onReceive - USER_OWNER care ACTION_BOOT_COMPLETED. run P service
,I/QuickConnect( 4376): PeriphStartReceiver.onReceive - no need to start
,I/SecKeyguardClockSingleView( 1180): Ignore. Because it is same clock text
,D/ActivityManager( 1018): startProcessLocked calleePkgName: com.sec.android.app.sbrowser, hostingType: broadcast
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
I/AMMetaDataParserService( 3968): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,W/libprocessgroup( 1018): failed to open /acct/uid_10014/pid_3520/cgroup.procs: No such file or directory
,E/Zygote  ( 4394): MountEmulatedStorage()
E/Zygote  ( 4394): v2
I/libpersona( 4394): KNOX_SDCARD checking this for 10131
I/libpersona( 4394): KNOX_SDCARD not a persona
,I/SELinux ( 4394): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4394): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 4394): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1018): Start proc com.sec.android.app.sbrowser for broadcast com.sec.android.app.sbrowser/.net.NetworkSettingsReceiver: pid=4394 uid=10131 gids={50131, 9997, 1023, 3003, 1028, 1015, 1007, 3001, 3002} abi=armeabi-v7a
,E/        ( 3968): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3968): took 0.721875ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3968): Bitmap=0xb84ff378 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7fb23c0 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3968): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,D/TimaKeyStoreProvider( 4394): TimaSignature is unavailable
,E/        ( 3968): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,D/ActivityThread( 4394): Added TimaKeyStore provider
,I/GFX raster( 3968): took 0.661823ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3968): Bitmap=0xb7fe22e8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb84fd330 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3968): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,W/ResourcesManager( 4394): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 4394): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4394): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 4394): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/SBrowserFeatureFlag( 4394): initialized in static block : loadCscFeatureValue() succeed! ,
,E/        ( 3968): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3968): took 0.782916ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3968): Bitmap=0xb7fb6928 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7fd54e0 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3968): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.mms.ui.ReplyMessageActivity
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:assistant
I/AMMetaDataParserService( 3968): Resource data:2131099648
,I/AMMetaDataParserService( 3968): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3968): getResourceTypeNamexml
,E/        ( 3968): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,D/ManifestProvider( 4394): onCreate()
,I/GFX raster( 3968): took 0.692499ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3968): Bitmap=0xb7fe8760 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7fd7cf8 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3968): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,E/NetworkSettingsReceiver( 4394): onReceive: android.intent.action.BOOT_COMPLETED
,E/        ( 3968): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3968): took 0.724115ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3968): Bitmap=0xb84ff328 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb7fd4e98 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3968): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,E/SBrowserFeatureFlag( 4394): initSupportedPkg: checkExistService com.samsung.android.smartclip.SpenGestureManager@29b4090a
,D/SBrowserFeatureFlag( 4394): initialize : initSupportedPkg() succeed! 
,I/VerificationLog( 4394): SbrowserSettings- url content://com.sec.android.app.sbrowser/readinglist/pinned.mhtml
,E/        ( 3968): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,D/ActivityManager( 1018): startProcessLocked calleePkgName: com.android.calendar, hostingType: broadcast
,I/GFX raster( 3968): took 0.782760ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3968): Bitmap=0xb7d22630 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb7fe83d0 counterpartCT=4 counterpartW=96 counterparth=96
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/AMMetaDataParserService( 3968): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,E/Zygote  ( 4413): MountEmulatedStorage()
E/Zygote  ( 4413): v2
I/libpersona( 4413): KNOX_SDCARD checking this for 10135
I/libpersona( 4413): KNOX_SDCARD not a persona
,I/SELinux ( 4413): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1018): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=4413 uid=10135 gids={50135, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,I/ActivityManager( 1018): Killing 3537:com.samsung.android.scloud.sync/u0a62 (adj 15): empty #31
,I/SELinux ( 4413): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4413): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/        ( 3968): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3968): took 0.667865ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3968): Bitmap=0xb7c6b270 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7ff0bc8 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3968): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,D/TimaKeyStoreProvider( 4413): TimaSignature is unavailable
,D/ActivityThread( 4413): Added TimaKeyStore provider
,E/        ( 3968): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3968): took 0.636094ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3968): Bitmap=0xb7fe22e8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7fc90f8 counterpartCT=4 counterpartW=96 counterparth=96
,W/ResourcesManager( 4413): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
I/AMMetaDataParserService( 3968): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,W/ResourcesManager( 4413): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 4413): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/        ( 3968): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3968): took 0.721302ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3968): Bitmap=0xb7fb6928 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7fabe70 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3968): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.mms.ui.ConversationList
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:assistant
I/AMMetaDataParserService( 3968): Resource data:2131099648
,I/AMMetaDataParserService( 3968): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3968): getResourceTypeNamexml
,E/        ( 3968): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3968): took 0.693386ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3968): Bitmap=0xb7fe8760 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7ff7dc8 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3968): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,D/daemonapp( 1299): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,E/        ( 3968): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3968): took 0.671094ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3968): Bitmap=0xb84ff328 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb7f95428 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3968): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,D/ActivityManager( 1018): startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
,E/        ( 3968): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3968): took 0.624896ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3968): Bitmap=0xb7d22630 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb7fedbc0 counterpartCT=4 counterpartW=96 counterparth=96
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,W/libprocessgroup( 1018): failed to open /acct/uid_10062/pid_3537/cgroup.procs: No such file or directory
,I/AMMetaDataParserService( 3968): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,E/        ( 3968): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3968): took 0.741771ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3968): Bitmap=0xb7c6b270 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7fe83d0 counterpartCT=4 counterpartW=96 counterparth=96
,D/ActivityManager( 1018): startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,I/AMMetaDataParserService( 3968): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
D/ActivityManager( 1018): startProcessLocked calleePkgName: com.sec.android.app.camera, hostingType: broadcast
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/        ( 3968): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3968): took 0.620885ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3968): Bitmap=0xb7fe22e8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7fd4e98 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3968): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,E/Zygote  ( 4434): MountEmulatedStorage()
,E/Zygote  ( 4434): v2
I/libpersona( 4434): KNOX_SDCARD checking this for 10139
I/libpersona( 4434): KNOX_SDCARD not a persona
,I/SELinux ( 4434): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4434): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4434): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
I/ActivityManager( 1018): Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.BootCamera: pid=4434 uid=10139 gids={50139, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a
,D/TimaKeyStoreProvider( 4434): TimaSignature is unavailable
,D/ActivityThread( 4434): Added TimaKeyStore provider
,I/art     (  306): Explicit concurrent mark sweep GC freed 8739(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 706us total 23.529ms
,E/        ( 3968): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3968): took 0.791094ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3968): Bitmap=0xb7fb6928 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7fc90f8 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3968): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,W/ResourcesManager( 4434): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 4434): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 4434): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,W/ResourcesManager( 4434): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
W/ResourcesManager( 4434): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 784us total 18.817ms
,I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.mms.ui.WarnOfStorageLimitsActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.mms.ui.SlideshowActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.mms.ui.MmsSinglePageActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.mms.ui.ClassZeroActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.mms.ui.RetryActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.mms.ui.MessagingPreferenceActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.mms.settings.EntrancePrefActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.mms.settings.DisplaySettings
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.mms.settings.CMASSettings
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.mms.settings.TextMessagesSettings
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.mms.settings.MultimediamessagesSettings
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.mms.rcs.settings.RcsMessagesSettings
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.mms.settings.DeleteoldMessagesSettings
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.mms.settings.PushMessagesSettings
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.mms.settings.NotificationSettings
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.mms.settings.NotificationSettingsDS
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.mms.settings.SignatureSettings
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.mms.settings.SpamSettings
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.mms.settings.SafemodeSettings
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.mms.settings.DelaySendingSettings
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.mms.smishing.PackageAuthorityActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.mms.smishing.PackageAuthorityDialog
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.mms.settings.MessageSmscActivityDS
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.mms.settings.SignatureEditActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.mms.settings.CallbackNumberSettings
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.mms.settings.CallbackNumberEditActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.mms.settings.BackgroundStyle
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.mms.settings.BubbleStyle
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.mms.ui.PushMessageDialog
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.mms.saverestore.SaveThreadActivity
,W/ContextImpl( 3968): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.mms.saverestore.SavedMsgsList
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.mms.saverestore.RestorePreviewActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.mms.saverestore.ConversationListRestore
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.mms.ui.ManageSimMessages
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.mms.ui.MmsRetryActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.mms.ui.ConfirmRateLimitActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.mms.ui.SearchActivity
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.mms.ui.SmsViewerActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.mms.ui.MmsNotificationViewerActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.mms.ui.DrmContentsActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.mms.ui.CMASPreferenceActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.mms.ui.CMASDialog,
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.mms.ui.CMASDialog_single_top
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.mms.ui.PDPResetDialog,
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.mms.ui.CMASUserPromptDialog
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.mms.ui.LockedMessageManager
,I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.mms.ui.SpamMessageManager
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.mms.ui.ReservationMessageManager
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.mms.ui.DraftMessageManager
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.mms.ui.SafeMessageManager
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.mms.ui.RecipientListActivity
,I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.mms.ui.GroupMessagingRecipientListActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.mms.ui.SelectMapActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.mms.location.LocationMapActivity
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3968): getResourcePackageName:android.app.default_searchable
,I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.mms.location.FavoritePlacesList
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.mms.location.RecentPlacesList
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.mms.ui.BoxListViewActivity
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.mms.provisioning.MmsProvisionActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.mms.ui.ManageSDMessages
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamNumberList
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamKeywordList
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamNumberWriteForm
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamKeywordWriteForm
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.mms.ui.SettingsReservationActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.mms.ui.SettingsTransmitMessageActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.mms.ui.MessageDatabaseBackupActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.mms.widget.NoticeThreadContactSelector
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.mms.widget.NoticeEditActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.mms.widget.NoticeDeleteActivity
,I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.mms.export.MmsPartExportDialogActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.mms.export.MmsPartExportDialogActivityAlien
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.mms.ui.DirectCallTutorialActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.mms.ui.FakeCallActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.mms.ui.MmsPartExportActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.mms.template.TextTemplateListActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.mms.template.TextTemplateEditActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.mms.help.AirViewMainActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.mms.help.AirButtonMainActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.mms.widget.WidgetPreferenceActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.mms.cover.MissedMsgActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.mms.oem.AutoSendingTestActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.mms.prioritysender.AddGlanceListActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.mms.prioritysender.AddThreadListActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.mms.settings.CheckDefaultSmsAppsActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.mms.accessory.ReadReportActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.mms.ui.FileHistoryListActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.mms.settings.FreeMessageSettings
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.mms.prioritysenderpanel.CocktailPrioritySenderSettingActivity
,I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.sec.android.gallery3d.app.GalleryOpaqueActivity
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 621us total 19.460ms
I/AMMetaDataParserService( 3968): getResourcePackageName:assistant
I/AMMetaDataParserService( 3968): Resource data:2131165197
,W/ResourcesManager( 3968): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3968): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3968): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 3968): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3968): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 3968): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 3968): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 3968): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3968): getResourceName:com.sec.android.gallery3d:xml/assistant
I/AMMetaDataParserService( 3968): getResourceTypeNamexml
,I/ActivityManager( 1018): Killing 3403:com.google.android.partnersetup/u0a15 (adj 15): empty #31
,I/ActivityManager( 1018): Killing 3611:com.android.managedprovisioning/u0a22 (adj 15): empty #31
,I/AMMetaDataParserService( 3968): Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,D/ActivityManager( 1018): startProcessLocked calleePkgName: com.android.email, hostingType: broadcast
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/AMMetaDataParserService( 3968): Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
E/Zygote  ( 4452): MountEmulatedStorage()
I/libpersona( 4452): KNOX_SDCARD checking this for 10145
E/Zygote  ( 4452): v2
I/libpersona( 4452): KNOX_SDCARD not a persona
I/SELinux ( 4452): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 4452): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4452): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
I/ActivityManager( 1018): Start proc com.android.email for broadcast com.android.email/.service.EmailBroadcastReceiver: pid=4452 uid=10145 gids={50145, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,I/AMMetaDataParserService( 3968): Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,W/libprocessgroup( 1018): failed to open /acct/uid_10022/pid_3611/cgroup.procs: No such file or directory
,W/libprocessgroup( 1018): failed to open /acct/uid_10015/pid_3403/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 4452): TimaSignature is unavailable
,D/ActivityThread( 4452): Added TimaKeyStore provider
I/AMMetaDataParserService( 3968): Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.sec.android.gallery3d.app.GalleryActivity
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3968): getResourcePackageName:assistant
I/AMMetaDataParserService( 3968): Resource data:2131165197
,I/AMMetaDataParserService( 3968): getResourceName:com.sec.android.gallery3d:xml/assistant
I/AMMetaDataParserService( 3968): getResourceTypeNamexml
,I/AMMetaDataParserService( 3968): Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,W/ResourcesManager( 4452): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 4452): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 4452): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 4452): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4452): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3968): Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
,I/AMMetaDataParserService( 3968): Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,I/AMMetaDataParserService( 3968): Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.cooliris.media.Gallery
,I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.sec.android.gallery3d.app.Gallery
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:assistant
I/AMMetaDataParserService( 3968): Resource data:2131165197
,I/AMMetaDataParserService( 3968): getResourceName:com.sec.android.gallery3d:xml/assistant
,I/AMMetaDataParserService( 3968): getResourceTypeNamexml
,I/AMMetaDataParserService( 3968): Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,I/AMMetaDataParserService( 3968): Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,I/AMMetaDataParserService( 3968): Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,I/AMMetaDataParserService( 3968): Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.sec.android.gallery3d.app.UsbDeviceActivity
,I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3968): getResourcePackageName:android.hardware.usb.action.USB_DEVICE_ATTACHED
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.sec.android.gallery3d.app.Wallpaper
,I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:android.wallpaper.preview
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.sec.android.gallery3d.app.LockScreen
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:android.wallpaper.preview
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.sec.android.gallery3d.app.BothScreen
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:android.wallpaper.preview
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.sec.android.gallery3d.app.CropImage
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.sec.android.gallery3d.app.ContextualTagSetting
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.sec.android.gallery3d.app.ContextualTagWeatherSetting
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.sec.samsung.gallery.view.gallerysearch.DeleteHistoryForGallerySearchActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.sec.samsung.gallery.view.usertag.AddUserTagListActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.sec.samsung.gallery.view.detailview.moreinfo.MoreInfoLocationEditActivity
W/ContextImpl( 3968): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.GallerySettings
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetTypeChooser
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetClickHandler
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetConfigure
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.MagazineWidgetConfigure
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.EasyWidgetConfigure
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetPreferenceActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.MagazineWidgetPreferenceActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.AccountSettingActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.FilterbySettingActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.sec.gallery2d.viewstate.MapView2dPage
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.sec.samsung.gallery.app.imagenote.ImageNote
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.sec.samsung.gallery.app.photonote.PhotoNote
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.sec.samsung.gallery.controller.StartMmsSaveCmd$CallMmsSave
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.sec.samsung.gallery.controller.GalleryChooserActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.sec.android.cloud.integrator.CloudIntegratorActivity
,I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.sec.android.app.camera.Camera
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.samsung.android.cocktail.subwindow.enable
I/AMMetaDataParserService( 3968): getResourcePackageName:com.sec.android.multiwindow.activity.STYLE
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.keyguard.layout
I/AMMetaDataParserService( 3968): getResourcePackageName:assistant
I/AMMetaDataParserService( 3968): Resource data:2131099648
,W/ResourcesManager( 3968): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 3968): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3968): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 3968): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
W/ResourcesManager( 3968): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3968): getResourceName:com.sec.android.app.camera:xml/assistant
I/AMMetaDataParserService( 3968): getResourceTypeNamexml
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,I/AMMetaDataParserService( 3968): Icon data: ResourceSwitch camera2131559034android.intent.action.switchcamera2130837512
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,I/AMMetaDataParserService( 3968): Icon data: ResourceGallery2131558741android.intent.action.switchgallery2130837511
,I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.sec.android.app.camera.Camcorder
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.sec.android.app.camera.DummyActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.sec.android.app.camera.CropImage
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.sec.android.app.shootingmodemanager.ManageShootingModeActivity
W/ContextImpl( 3968): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
,D/ActivityManager( 1018): getContentProviderImpl callerProcessName:com.android.email, calleePkgName: com.sec.android.provider.badge
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,I/ActivityManager( 1018): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=4475 uid=10072 gids={50072, 9997} abi=armeabi-v7a
,E/Zygote  ( 4475): MountEmulatedStorage(),
E/Zygote  ( 4475): v2
I/libpersona( 4475): KNOX_SDCARD checking this for 10072
I/libpersona( 4475): KNOX_SDCARD not a persona
,I/SELinux ( 4475): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 4475): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 4475): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.GridSettings
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:assistant
I/AMMetaDataParserService( 3968): Resource data:2131165220
,D/ActivityManager( 1018): startService callerProcessName:com.android.email, calleePkgName: com.android.email
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailBroadcastProcessorService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.email, destAppInfo.processName = com.android.email
,W/ResourcesManager( 3968): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.,
W/ResourcesManager( 3968): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3968): getResourceName:com.android.settings:xml/assistant,
,W/ResourcesManager( 3968): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3968): getResourceTypeNamexml
,W/ResourcesManager( 3968): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
E/        ( 3968): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96,
W/ResourcesManager( 3968): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/GFX raster( 3968): took 0.709739ms for 96*96 texture 0
W/ResourcesManager( 3968): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.,
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3968): Bitmap=0xb86f1908 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb86f1638 counterpartCT=4 counterpartW=96 counterparth=96
D/TimaKeyStoreProvider( 4475): TimaSignature is unavailable
,D/ActivityThread( 4475): Added TimaKeyStore provider
,I/AMMetaDataParserService( 3968): Icon data: ResourceSearch2131363521com.android.settings.Search2130837580
,E/        ( 3968): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3968): took 0.604167ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3968): Bitmap=0xb86f3850 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb86f3988 counterpartCT=4 counterpartW=96 counterparth=96
,D/BadgeProvider( 4475): onCreate
I/splitIntent( 1018): Queue : backgroundsplit_1 intent android.intent.action.BOOT_COMPLETED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,D/BadgeProvider( 4475): DatabaseHelper
,I/AMMetaDataParserService( 3968): Icon data: ResourceEdit quick settings2131361852com.android.settings.Favorite2130837579
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1018): Killing 3665:com.samsung.android.MtpApplication/1000 (adj 15): empty #31
,I/ActivityManager( 1018): Killing 3628:com.sec.android.app.servicemodeapp/1000 (adj 15): empty #32
,I/splitIntent( 1018): intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
I/splitIntent( 1018): base  index=1, name=com.google.android.gms com.google.android.gms.wearable.service.AutoStarterReceiver
I/splitIntent( 1018): other index=3, name=com.google.android.gms com.google.android.gms.photos.InitializePhotosIntentReceiver
I/splitIntent( 1018): arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.SubSettings
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.LabelName
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.Password
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.Settings$EthernetSettingsActivity
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.Settings$WirelessSettingsActivity
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.Settings$WifiSettingsActivity
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.wifi.WifiSettings
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
W/ActivityManager( 1018): userId = 0, bbcId = -10000
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.wifi.WifiPickerActivity
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.wifi.WifiSecPickerActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.wifi.WifiCaptiveActivity
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.wifi.FreeWifiScanPickerDialog
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.wifi.WifiWarningDialog
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.wifi.WifiOffloadDialog
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.wifi.WifiAdvancedSecSetupActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.wifi.WificmccSetupActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.wifi.WifiSecSetupActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.wifi.WifiWarningDialog
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.wifi.WifiSetupActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.accessibility.smartscroll.app.sbrowsertry.SmartScreenActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for, running activitycom.android.settings.wifi.WifiPickerDialog
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.wifi.WifiSettingsForSetupWizardXL
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.Settings$AdvancedWifiSettingsActivity
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.Settings$SavedAccessPointsSettingsActivity
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.Settings$WifiShareProfileActivity
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.wifi.WifiInfo
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.wifi.WifiConfigInfo
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.wifi.WifiAPITest
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.wifi.WifiStatusTest
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApSettings
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
,I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApWarning
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApTestConfigure
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.wifi.WifiPoorConnection
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.wifi.WifiHiddenApListActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.wifi.WifiHiddenApDeleteActivity
,I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.wifi.WifiDisconnectWeakApSettings
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.Settings$ApnSettingsActivity
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.Settings$BluetoothSettingsActivity
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothSettings
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothScanDialog
,I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothErrorActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.bluetooth.CheckBluetoothStateActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.bluetooth.DevicePickerActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothEnableActivity
,I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothEnablingActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.Settings$MirrorLinkActivity
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.Settings$TetherSettingsActivity
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3968): getResourcePackageName:com.samsung.android.multiuser.install_only_owner
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.TetherSettings
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): getResourcePackageName:com.samsung.android.multiuser.install_only_owner
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.Settings$WifiP2pSettingsActivity
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.wifi.p2p.WifiP2pSettings
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.Settings$WifiP2pHelpActivity
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
,I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.wifi.p2p.WifiP2pDummyPickerActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.Settings$NearbySettingsActivity
,I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.nearby.NearbySettings
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.wfd.WfdHelpActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.wfd.WfdPickerDialog
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.Settings$VpnSettingsActivity
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.Settings$DateTimeSettingsActivity
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.DateTimeSettingsSetupWizard
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.FeatureSettingsSetupWizard
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.Settings$LocalePickerActivity
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.Settings$InputMethodAndLanguageSettingsActivity
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.Settings$VoiceInputSettingsActivity
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.Settings$HandwritingLanguageActivity
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
W/ContextImpl( 3968): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.handwritingsearch.HandwritingLanguageTablet
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.Settings$KeyboardLayoutPickerActivity
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check,
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.LanguageSettings
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.Settings$SpellCheckersSettingsActivity,
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.inputmethod.InputMethodAndSubtypeEnablerActivity
,I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3968): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.Settings$UserDictionarySettingsActivity
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.inputmethod.UserDictionaryAddWordActivity
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.UserDictionarySettings
,I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.Settings$ZenModeSettingsActivity
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.Settings$ZenModeDNDSettingsActivity
,I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS,
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3968): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.Settings$HomeSettingsActivity
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
,I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.HomeSettings
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.Settings$LockScreenSettingsActivity
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.Settings$DisplaySettingsActivity
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.DisplaySettings
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.Settings$LockscreenMenuActivity
I/ActivityManager( 1018): Killing 3654:com.wssnps/1000 (adj 15): empty #31
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.Settings$BlockSettingsActivity
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.Settings$LedIndicatorSettingsActivity
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.Settings$DockSettingsActivity
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.DockSettings
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.ContextualPageSettings
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.Settings$ContextualPageHelpActivity
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.Settings$DeviceInfoSettingsActivity
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.DeviceNameDialog
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.SettingsLicenseActivity
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3968): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.PrivacyAlertDialogActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.PrivacyAlertProceedDialogActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.SettingsSafetyLegalActivity
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3968): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.Settings$ManageApplicationsActivity
,I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.applications.ManageApplications
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.ManageApplications
,I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.RunningServices
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.LaunchApplication
W/ActivityManager( 1018): userId = 0, bbcId = -10000,
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.applications.StorageUse
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.applications.InstalledAppDetailsTop
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.accounts.ManageAccountsActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.applications.InstalledAppDetails
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.applications.UninstallMultipleScreen
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.Settings$RunningServicesActivity
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.Settings$StorageUseActivity
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.Settings$NotificationStationActivity
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.Settings$AppOpsDetailsActivity
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.Settings$LocationSettingsActivity
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.Settings$SecuritySettingsActivity
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.MonitoringCertInfoActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.Settings$TrustedCredentialsSettingsActivity
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.SecuritySettings
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.Settings$PrivacySettingsActivity
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.SetFullBackupPassword
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.CredentialStorage
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.Settings$DeviceAdminSettingsActivity
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.DeviceAdminSettings
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.DeviceAdminAdd
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.Settings$UsageAccessSettingsActivity
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.SetProfileOwner
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.IccLockSettings
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.SimPinLockSettings
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.SimPersoLockSettings
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.Settings$AccessibilitySettingsActivity
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.Settings$AccessibilityDaltonizerSettingsActivity
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.samsung.settings.accessibility.AccessibilityWidgetDialogActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.Settings$CaptioningSettingsActivity
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.Settings$MagnifierSettingsActivity
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.Settings$AssistantMenuPreferenceFragmentActivity
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.AccessibilitySettingsSetupWizard
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.Settings$TextToSpeechSettingsActivity
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.Settings$DrivingModeSettingsActivity
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.Settings$AssistiveHepticSettingsActivity
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.ConfirmDeviceCredentialActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.notification.RedactionInterstitial
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.notification.RedactionSettingsStandalone
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.ConfirmLockPattern
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.ConfirmLockPassword
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.ConfirmLockEnterpriseIdentity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.ChooseLockEnterpriseIdentity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.ConfirmLockPattern$InternalActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.ConfirmLockPassword$InternalActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.BluetoothPairingWithCac
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.ChooseLockGeneric
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.ChooseLockGeneric$InternalActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.KnoxChooseLockTwoFactor
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.KnoxChooseLockBackupPin
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.ChooseLockPattern
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.ChooseLockBLock
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.ChooseLockPassword
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.ChooseLockMotion
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.ChooseLockAdditionalPin
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.ChooseLockSignature
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.EncryptionInterstitial
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.deviceinfo.Status
,I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.Settings$StorageSettingsActivity
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.deviceinfo.MiscFilesHandler
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.deviceinfo.DeviceInfoTabActivity
,I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.ApnEditor
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.MediaFormat
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.MediaFormatSd
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.Settings$QuickLaunchSettingsActivity
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.quicklaunch.BookmarkPicker
,I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.Settings$DevelopmentSettingsActivity
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.Settings$PrintSettingsActivity
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.Settings$PrintJobSettingsActivity
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.DevelopmentSettings
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.AppPicker
,I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.Settings$UsbSettingsActivity
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.UsbSettings
,I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothPairingDialog
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.bluetooth.RequestPermissionActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.wifi.WifiScanModeActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.bluetooth.RequestPermissionHelperActivity
,I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothPermissionActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.ActivityPicker
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.Settings$NfcSettingsActivity
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.nfc.NfcAdvancedRoutingSetting
,I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.Settings$AndroidBeamSettingsActivity
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.Settings$SBeamSettingsActivity
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.Settings$WifiDisplaySettingsActivity
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
,I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.BatteryInfo
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.Display
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.RadioInfo
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.ProxySelector
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.BandMode
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.TestingSettings
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.fulllocalepickertest.FullLocalePickerTest
,I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.AppWidgetPickActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.AllowBindAppWidgetActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.UsageStatsActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.Settings$PowerUsageSummaryActivity
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.fuelgauge.PowerUsageSummary
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.Settings$BatterySaverSettingsActivity
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
,I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.Settings$AccountMenuActivity
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.Settings$AccountSettingsActivity
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.Settings$AccountSyncSettingsActivity
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.accounts.AddAccountSettings
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.accounts.ChooseAccountActivity
,I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.CryptKeeper
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.CryptKeeper$FadeToBlack
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.CryptKeeperConfirm$Blank
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.CryptDecryptConfirm$Blank
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.Settings$CryptKeeperSettingsActivity
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.Settings$CryptDecryptSettingsActivity
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.Settings$CryptSDCardSettingsActivity
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.Settings$SimChangeAlertSettingsActivity
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.Settings$DataUsageSummaryActivity
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.Settings$DataUsageMeteredSettingsActivity
,I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.Settings$DreamSettingsActivity
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
,I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.Settings$UserSettingsActivity
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3968): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.Settings$PaymentSettingsActivity
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
,I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.nfc.PaymentDefaultDialog
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3968): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.SmsDefaultDialog
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.ActiveNetworkScorerDialog
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.Settings$NotificationAccessSettingsActivity
,I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.Settings$ConditionProviderSettingsActivity
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.Settings$NotificationSettingsActivity
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.Settings$SoundSettingsActivity
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
,I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.SoundSettings
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.Settings$OtherSoundSettingsActivity
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.Settings$NotificationAppListActivity
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.Settings$AppNotificationSettingsActivity
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.Settings$SimSettingsActivity
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.FactoryResetDialog
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.LockScreenWallpaper
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.Settings$WallpaperSettingsActivity
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.GSensorSettings
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingModeSettingsActivity
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingMode2014Activity
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingModeSettings2014Activity
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.Settings$UltraPowerSavingModeActivity
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.ModePreviewTablet
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.ModePreviewDialog
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.InkeffectPreview
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.InkeffectPreviewTablet
,I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.ModePreview
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.NewModePreview
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.SViewColor
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.SViewColor2014
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.SViewStyleClock
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.SViewMiniWallpaper
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.Settings$SViewCoverEdgeSettingsActivity
,I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.ChooseLockFaceWarning
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.Settings$PowerSettingsActivity
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.RecommendRingtoneDialog
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.Settings$SelectInfoCoverSettingsActivity
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.SelectItemDisplay
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3968): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.Settings$WeatherSettingsFragmentActivity
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.SViewCoverPopup
,I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.WarrantyLegal
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.SamsungLegalTablet
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.PenDetachmentOption
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.Settings$PenDetachmentOptionActivity
,I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.NotificationPanelMenu
,I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.Settings$NotificationPanelMenuActivity
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.NotificationPanelSettings
,I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.Settings$MotionSettingsActivity
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.Settings$AirMotionSettingActivity
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.Settings$SMotionGuideHub2014Activity
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.Settings$FingerAirViewSettingActivity
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.Settings$FingerAirViewHelpSettingActivity
,I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.Settings$PenAirViewHelpSettingActivity
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.Settings$AirViewSettingActivity
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.Settings$MouseHoveringSettingsActivity
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.Settings$SoftwareUpdateSettingActivity
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.PenHelpActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.Settings$PenHelpFragmentActivity
,I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.Settings$DirectPenInputSettingsActivity
,I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.Settings$PenAirViewSettingsMenuActivity
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.Settings$PenSettingsMenuActivity
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.PhoneVibration
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.OneHandHelp
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.OneHandAdaptiveHelp
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.Settings$OneHandSideSoftKeyFragmentActivity
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.personalvibration.PersonalVibration
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.personalvibration.SelectPatternDialog
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.LockScreenShortcutSettings
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.AppList
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.ExpandAppList
,I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.Settings$ReadingModeSettingsActivity
W/ActivityManager( 1018): userId = 0, bbcId = -10000
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.customizablekey.CustomizableKeySettings
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.Settings$CustomizableKeySettingsActivity
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.customizablekey.AppList
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.Settings$DualClockSettingActivity
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.Settings$RecommendedAppsMenuActivity
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.Settings$RecommendedAppsListActivity
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.SettingsReceiverActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.SelectPenDetachNotiDialog
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.SecurityWarningDialog
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.Settings$PersonalPageSettingsActivity
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageSettings
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.PersonalPageDisclaimer
,I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageAutoModeSwitchAlertDialogActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorial
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialDisclaimerActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialAppActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialAddActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockPattern
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockPassword
,I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockAdditionalPin
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageConfirmLockPattern
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageConfirmLockPassword
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.Settings$EasyModeSettingsActivity
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.Settings$EasyModeActivity
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.Settings$EasyModeAppActivity
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.Settings$MyPlaceSettingsActivity
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.Settings$MyPlaceProfileSettingsActivity
,I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.Settings$PlaceSettingsActivity
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.myplace.SelectMapActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.Settings$GlobalRoamingSettingsActivity
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.Settings$TRoamingSettingsActivity
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.flipfont.FontListActivity
,I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.flipfont.FontListProgressActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.Settings$BackupAssistantPlusSettingsActivity
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.myprofile.MyProfileActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.MagazineCard
,I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.Settings$ClockWidgetActivity
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.myprofile.PersonalMessage
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.Settings$CloudSettingActivity
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.ShortCameraMenu
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.ClockMyprofileMenu
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.ClockMyprofileMenuTablet
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.Settings$LaunchCameraSettingsActivity
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.Settings$SmartScreenSettingsActivity
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.Settings$SmartBondingSettingsActivity
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.Settings$ToolboxMenuActivity
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.Settings$ToolboxListActivity
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.Settings$SmartScrollAdvancedSettingsActivity
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.Settings$MultiWindowSettingsActivity
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.MultiWindowSettings
,I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.settingssearch.SettingsSearchActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.SearchActivity
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3968): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.Settings$ColorChipReportActivity
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.Settings$DirectAccessActivity
,I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.Settings$NotificationReminderActivity
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.Settings$VoiceInputControlSettingsActivity
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.PreloadAppUpdate
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.PreloadAppUpdateList
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.activekey.ActiveKeySettings
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.Settings$ActiveKeySettingsActivity
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.activekey.AppList
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.Settings$DisplaySettingsTab
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.SETTING_HEADER_ID
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.Settings$InputAndControlSettingsTab
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.SETTING_HEADER_ID
,I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.Settings$GeneralSettingsTab
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.SETTING_HEADER_ID
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.DeviceHealthActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.Settings$SettingsEmergencyActivity
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareSettingsActivity
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareEmergencyModeActivity
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareDisasterActivity
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareDisclaimerActivity
,I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareDisasterDisclaimerActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareCoverageDialog,
,I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.Settings$AirplaneModeSettingsActivity
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0,
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID,
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.Settings$ToddlerModeSettingsActivity
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.favorite.FavoriteMenuList
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.Settings$FestivalEffectSettingsActivity
I/AMMetaDataParserService( 3968): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3968): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.powersavingmode.PowerNotiDialog
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.powersavingmode.PowerNotiDataDialog
,I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.wifi.SetupWizardWifiScreen
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.wifi.CaptivePortalWebViewActivity
I/AMMetaDataParserService( 3968): Resource data:Loop for running activitycom.android.settings.KnoxActiveProtectionEulaActivity
D/StatusBar.NetworkController( 1180): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1180): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/WearableService( 1863): callingUid 10012, callindPid: 1863
E/MDM     ( 1863): [197] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/BadgeProvider( 4475): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/CalendarProvider2( 4337): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,D/BadgeProvider( 4475): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 4475): sendNotify, [notify] : null
D/BadgeProvider( 4475): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 4475): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 4475): update, [UpdateCount] : 1
,D/Launcher.Model( 1480): reloadBadges entered.
,I/ActivityManager( 1018): Killing 3689:com.sec.esdk.elm/u0a94 (adj 15): empty #31
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,D/LocationInitializer( 2000): Restart initialization of location
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,D/GCM     ( 1637): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4340, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,D/AuthorizationBluetoothService( 1637): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2643): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2643): Disconnected process message: 10
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): getTasks: caller 10145 does not hold GET_TASKS; limiting output
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.account.AccountStatusChecker$InitializeService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/Process ( 4452): Sending signal. PID: 4452 SIG: 9
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,V/GLSActivity( 1637): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.crypto.ChannelBindingStateService; callingUser = 0; userId(target) = 0
,W/GCoreFlp( 1863): No location to return for getLastLocation()
,W/FusedLocationProvider( 1637): location=null
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GmsCoreStatsServiceLauncher( 2000): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_3665/cgroup.procs: No such file or directory
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_3628/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_3654/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_10094/pid_3689/cgroup.procs: No such file or directory
,D/ActivityManager( 1018): startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 3553): Starting #2
I/Hs20UtilService( 3553): Message received 5011
,D/ActivityManager( 1018): startProcessLocked calleePkgName: com.samsung.android.securitylogagent, hostingType: broadcast
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4502): MountEmulatedStorage()
E/Zygote  ( 4502): v2
I/libpersona( 4502): KNOX_SDCARD checking this for 1000
I/libpersona( 4502): KNOX_SDCARD not a persona
,I/SELinux ( 4502): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1018): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=4502 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/SELinux ( 4502): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 4502): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 4502): TimaSignature is unavailable
,D/ActivityThread( 4502): Added TimaKeyStore provider
,I/ActivityManager( 1018): Process com.android.email (pid 4452)(adj 9) has died(68,1130)
,D/SecurityLogAgent( 4502): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 4502): KnoxConfiguration : Current State Mapping Found 
,D/SecurityLogAgent( 4502): StateMachine : Current State = 1
,D/SecurityLogAgent( 4502): StateMachine : Changed Current State = 1
,D/ActivityManager( 1018): startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 3553): Starting #3
,I/Hs20UtilService( 3553): Message received 5011
,D/SecurityLogAgent( 4502): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 4502): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 4502): StateMachine : Current State = 1
,D/SecurityLogAgent( 4502): StateMachine : Changed Current State = 1
,E/WifiStateMachine( 1018): DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
D/WifiNative-wlan0( 1018): callSECStringApiVoid - ID [215]
E/WifiNative-wlan0( 1018): invaild command id : 215
,D/NearbySettings( 1333): MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,V/NearbySettings( 1333): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1333): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 1333): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 1333): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1333): MountReceiver.onReceive - Keep current state
,D/ActivityManager( 1018): startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4518): MountEmulatedStorage()
,E/Zygote  ( 4518): v2
I/libpersona( 4518): KNOX_SDCARD checking this for 10068
I/libpersona( 4518): KNOX_SDCARD not a persona
,I/ActivityManager( 1018): Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=4518 uid=10068 gids={50068, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 4518): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4518): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 4518): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 4518): TimaSignature is unavailable
,D/ActivityThread( 4518): Added TimaKeyStore provider
,W/ResourcesManager( 4518): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/FileShare-Client( 4518): ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,D/FileShare-Client( 4518): ClientBroadcastReceiver.onReceive - disconnected
,D/FileShare-Client( 4518): Outbound.stopDelayTimer - 
D/FileShare-Server( 3820): ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,I/ActivityManager( 1018): Killing 3369:com.sec.pcw.device/1000 (adj 15): empty #31
,D/ActivityManager( 1018): startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 3553): Starting #4
I/Hs20UtilService( 3553): Message received 5007
,D/NearbySettings( 1333): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1333): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1333): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 1333): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1333): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1333): MountReceiver.onReceive - Keep current state
,D/ActivityManager( 1018): startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 3553): Starting #5
,I/Hs20UtilService( 3553): Message received 5007
,D/NearbySettings( 1333): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1333): MountReceiver.onReceive - Keep current state
,D/ActivityManager( 1018): startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 3553): Starting #6
,I/Hs20UtilService( 3553): Message received 5007
,D/NearbySettings( 1333): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1333): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1333): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 1333): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 1333): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1333): MountReceiver.onReceive - Keep current state
,D/ActivityManager( 1018): startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 3553): Starting #7
,I/Hs20UtilService( 3553): Message received 5007
,D/NearbySettings( 1333): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1333): MountReceiver.onReceive - Keep current state
,D/WifiStateMachine( 1018): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,D/SecContentProvider2( 1018): uri = 15 selection = getToastGravityEnabledState
,D/SecContentProvider2( 1018): mCursor = null
,D/SecContentProvider2( 1018): uri = 15 selection = getToastGravity
,D/SecContentProvider2( 1018): mCursor = null
,D/SecContentProvider2( 1018): uri = 15 selection = getToastGravityXOffset
D/SecContentProvider2( 1018): mCursor = null
,D/SecContentProvider2( 1018): uri = 15 selection = getToastGravityYOffset
,D/SecContentProvider2( 1018): mCursor = null
,D/SecContentProvider2( 1018): uri = 15 selection = getToastEnabledState
,D/SecContentProvider2( 1018): mCursor = null
,D/SecContentProvider2( 1018): uri = 15 selection = getToastShowPackageNameState
,D/SecContentProvider2( 1018): mCursor = null
,D/ActivityManager( 1018): startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast,
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4533): MountEmulatedStorage()
,E/Zygote  ( 4533): v2
I/libpersona( 4533): KNOX_SDCARD checking this for 1000
I/libpersona( 4533): KNOX_SDCARD not a persona
,I/SELinux ( 4533): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_3369/cgroup.procs: No such file or directory
,I/ActivityManager( 1018): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=4533 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
,I/SELinux ( 4533): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 4533): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 4533): TimaSignature is unavailable
,D/ActivityThread( 4533): Added TimaKeyStore provider
,I/PCWCLIENTTRACE_LOG( 4533): DEFAULT_LOGON : true
,I/PCWCLIENTTRACE_LOG( 4533): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper( 4533): new DMDBOpenHelper instance
,I/PCWCLIENTTRACE_PushUtil( 4533): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 4533): sales region : global
,I/PCWCLIENTTRACE_PushUtil( 4533): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 4533): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/splitIntent( 1018): Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=10, mSplitNum[1]=19, mSplitNum[2]=28, mBgSplitQueueNum=3 divideNum= 8 r.nextReceiver= 1 receivers.size=36
,I/splitIntent( 1018): finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
,D/ActivityManager( 1018): startProcessLocked calleePkgName: com.google.android.music, hostingType: broadcast
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4549): MountEmulatedStorage()
,E/Zygote  ( 4549): v2
I/libpersona( 4549): KNOX_SDCARD checking this for 10111
I/libpersona( 4549): KNOX_SDCARD not a persona
,I/SELinux ( 4549): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
I/ActivityManager( 1018): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=4549 uid=10111 gids={50111, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1018): Killing 3732:com.sec.factory.camera/1000 (adj 15): empty #31
,I/SELinux ( 4549): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4549): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1018): startProcessLocked calleePkgName: com.android.chrome, hostingType: broadcast
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
I/KLMS-2.5.183: ( 3584): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Wed Dec 02 18:46:32 GMT+01:00 2015
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4563): MountEmulatedStorage()
,I/libpersona( 4563): KNOX_SDCARD checking this for 10081
E/Zygote  ( 4563): v2
I/libpersona( 4563): KNOX_SDCARD not a persona
,I/SELinux ( 4563): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4563): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
I/ActivityManager( 1018): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=4563 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/SELinux ( 4563): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1018): startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent,
W/ActivityManager( 1018): userId = 0, bbcId = -10000
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,D/TimaKeyStoreProvider( 4549): TimaSignature is unavailable
,D/ActivityThread( 4549): Added TimaKeyStore provider
,I/KLMS-2.5.183: ( 3584): KLMSAbstractReciever(): onReceive().END.
,D/PowerManagerService( 1018): [s] UserActivityState : 1 -> 2
,I/KLMS-2.5.183: ( 3584): KLMSIntentService(): onCreate()
,I/KLMS-2.5.183: ( 3584): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.5.183: ( 3584): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,D/TimaKeyStoreProvider( 4563): TimaSignature is unavailable
,D/ActivityThread( 4563): Added TimaKeyStore provider
,I/KLMS-2.5.183: ( 3584): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.5.183: ( 3584): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,I/KLMS-2.5.183: ( 3584): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false| ETHERNET : false
,I/KLMS-2.5.183: ( 3584): StateImplV2(): networkChangeListener().START
,I/KLMS-2.5.183: ( 3584): NetworkChangeOperations(): uploadRequestLog().START 
,I/iu.SyncManager( 2000): SYNC; picasa accounts
,I/DBG_POLICYDM( 4177): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/DBG_POLICYDM( 4177): [com.policydm.XDMApplication(469/isNetworkChanged)] a previous network is 0, current network is 2
I/KLMS-2.5.183: ( 3584): NetworkChangeOperations(): uploadRequestLog().END 
,I/KLMS-2.5.183: ( 3584): StateImplV2(): networkChangeListener().END
,I/KLMS-2.5.183: ( 3584): KLMSIntentService(): onDestroy()
,E/DBG_POLICYDM( 4177): [com.policydm.XDMApplication(471/isNetworkChanged)] network changed.... 
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_3732/cgroup.procs: No such file or directory
,I/DBG_POLICYDM( 4177): [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] ,
,I/DBG_POLICYDM( 4177): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,I/DBG_POLICYDM( 4177): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,I/DBG_POLICYDM( 4177): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,I/DBG_POLICYDM( 4177): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,I/DBG_POLICYDM( 4177): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,I/DBG_POLICYDM( 4177): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,I/DBG_POLICYDM( 4177): [com.policydm.XDMBroadcastReceiver(275/xdmExecResumeCase)] Start resumecase for INIT
,E/DBG_POLICYDM( 4177): [com.policydm.db.XDBSpdAdp(35/xdbGetSpdDeviceRegister)] Device is Registered
,E/SPPClientService( 4249): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,I/SA      ( 4297): [OR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOH2 PSS = 4.978878039476607  ]
,I/SA      ( 4297): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      ( 4297): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/DBG_POLICYDM( 4177): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,D/NetworkLogImpl( 2000): Loaded NetworkSpeedPredictor
,I/iu.Environment( 2000): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/SA      ( 4297): [SLFUCHKMGR] constructor called
,E/SMD     (  289): DCD OFF
,I/iu.UploadsManager( 2000): num queued entries: 0
,I/iu.UploadsManager( 2000): num updated entries: 0
,I/iu.SyncManager( 2000): NEXT; no task
,I/SA      ( 4297): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      ( 4297): [OR] == isSIMCardReady false ==
,I/SA      ( 4297): [SCU] == networkStateCheck == true
,I/SA      ( 4297): [DM] getCountryCodeFromCSC : PL
I/SA      ( 4297): isChinaCountryCode : false
I/SA      ( 4297): [SCU] is ChinestModel Data Restricted   : false
I/SA      ( 4297): [OR] == networkStateCheck true ==
,I/SA      ( 4297): [OR] GetMyCountryZoneTask
,I/SA      ( 4297): [OR] onReceive END
,V/DownloadManager( 1228): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
I/MusicStore( 4549): Database version: 108
,D/ActivityManager( 1018): startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.downloads,
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.providers.downloads/com.android.providers.downloads.DownloadService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,I/SA      ( 4297): [SRS] prepareGetMyCountryZone
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.snet.SnetAlarmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/accuweather( 1733): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,I/SA      ( 4297): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      ( 4297): [SSP] query invoked
,D/ChimeraCfgMgr( 2000): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/SA      ( 4297): [TPMU] GetMccFromDB : null
I/SA      ( 4297): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 4297): [TPM] isNoProxy(default) : true
,D/daemonapp( 1299): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 5
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/SecContentProvider2( 1018): uri = 15 selection = getAppBlockDownloadState
,E/File    ( 4297): fail readDirectory() errno=2
D/SecContentProvider2( 1018): mCursor = null
,D/accuweather( 1733): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 1733): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
D/accuweather( 1733): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
,D/accuweather( 1733): [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,D/ChimeraCfgMgr( 2000): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/accuweather( 1733): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 1733): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/art     ( 2000): Explicit concurrent mark sweep GC freed 19036(1440KB) AllocSpace objects, 15(240KB) LOS objects, 40% free, 11MB/18MB, paused 1.351ms total 55.605ms
,I/DBG_POLICYDM( 4177): [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,I/DBG_POLICYDM( 4177): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,I/DBG_POLICYDM( 4177): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,I/DBG_POLICYDM( 4177): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,I/DBG_POLICYDM( 4177): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,I/DBG_POLICYDM( 4177): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,I/DBG_POLICYDM( 4177): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,I/art     ( 1018): Explicit concurrent mark sweep GC freed 27001(1637KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 26MB/40MB, paused 2.207ms total 142.724ms
,D/ActivityManager( 1018): startProcessLocked calleePkgName: com.sec.android.app.samsungapps, hostingType: broadcast
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4598): MountEmulatedStorage(),
E/Zygote  ( 4598): v2
I/libpersona( 4598): KNOX_SDCARD checking this for 10010
I/libpersona( 4598): KNOX_SDCARD not a persona
,I/SELinux ( 4598): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1018): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=4598 uid=10010 gids={50010, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/SELinux ( 4598): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,D/ActivityManager( 1018): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null,
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
I/ActivityManager( 1018): Killing 3707:com.samsung.android.sm/1000 (adj 15): empty #31
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,E/SELinux ( 4598): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1018): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): startProcessLocked calleePkgName: com.google.android.apps.magazines, hostingType: broadcast
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4613): MountEmulatedStorage(),
E/Zygote  ( 4613): v2
I/libpersona( 4613): KNOX_SDCARD checking this for 10113
I/libpersona( 4613): KNOX_SDCARD not a persona
,I/SELinux ( 4613): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
D/TimaKeyStoreProvider( 4598): TimaSignature is unavailable
,D/ActivityThread( 4598): Added TimaKeyStore provider
,I/SELinux ( 4613): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 4613): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1018): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4613 uid=10113 gids={50113, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_3707/cgroup.procs: No such file or directory
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,D/TimaKeyStoreProvider( 4613): TimaSignature is unavailable
D/ActivityThread( 4613): Added TimaKeyStore provider
,V/GLSActivity( 1637): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1018): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1637): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ResourcesManager( 4549): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 4549): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 4549): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,D/WaitQueueForNetworkActivate( 4598): notifyNetworkActivated
,W/ActivityThread( 4549): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());,
W/System  ( 4549): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@39f32472: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl,
I/ProviderInstaller( 4549): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 4549): GMSCore installation verified
,W/ContextImpl( 4598): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,D/ActivityManager( 1018): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.preferences.MusicPreferenceService$MusicPreferenceServiceBinder; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 4613): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,I/ConfigStore( 4549): Config Database version: 1
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 4613): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 4613): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 4613): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,D/BluetoothAdapter( 3941): disable()
,D/SettingsProvider( 1018): name = bluetooth_on
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 4549): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 4549): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 4549): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,D/SecContentProvider( 1018): uri = 18 selection = isWifiEnabled
,D/SecContentProvider2( 1018): uri = 20 selection = isWifiStateChangeAllowed
,D/SecContentProvider2( 1018): mCursor = null
,D/BluetoothAdapterState( 2643): CURRENT_STATE=ON, MSG = USER_TURN_OFF
,D/BluetoothAdapterProperties( 2643): Setting state to 13
,I/BluetoothAdapterState( 2643): Bluetooth adapter state changed: 12-> 13
D/BluetoothAdapterService( 2643): Bluetooth PBAP supproted is true
D/BluetoothAdapterService( 2643): updateAdapterState state is 13
,D/WifiService( 1018): setWifiEnabled: false pid=3941, uid=10174
D/ActivityManager( 1018): startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,D/SettingsProvider( 1018): name = wifi_on
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.StorageMigrationService; callingUser = 0; userId(target) = 0
,D/BluetoothAdapterService( 2643): Autoconnection is available 
D/BluetoothAdapterService( 2643): updateAdapterState prevState = 12newState = 13
D/BluetoothAdapterService( 2643): terminating service from this receiver
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
I/BluetoothPbapService( 2643): action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,D/BluetoothSocket( 2643): close() in, this: android.bluetooth.BluetoothSocket@5a7efe6, channel: 19, state: LISTENING
D/BluetoothSocket( 2643): close() this: android.bluetooth.BluetoothSocket@5a7efe6, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3334d128, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@57d6927mSocket: android.net.LocalSocket@799d7d4 impl:android.net.LocalSocketImpl@1e3bad7d fd:FileDescriptor[74]
,D/BluetoothSocket( 2643): Closing mSocket: android.net.LocalSocket@799d7d4 impl:android.net.LocalSocketImpl@1e3bad7d fd:FileDescriptor[74]
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,D/BluetoothAdapterProperties( 2643): onBluetoothDisable()
D/BluetoothAdapterProperties( 2643): mDiscovering is false
,D/SecContentProvider( 1018): uri = 3 selection = isDiscoverableEnabled
,E/WifiStateMachine( 1018): WifiStateMachine: Leaving Connected state
,I/wpa_supplicant( 2081): reset timer : RESET_TIMER 0
I/wpa_supplicant( 2081): wlan0: Setting scan request: 0 sec 0 usec
,I/wpa_supplicant( 2081): P2P: Current p2p state = IDLE
,I/wpa_supplicant( 2081): Scan requested (ret=0) - scan timeout 30 seconds
,I/jxcore-log( 3941): ****TEST TOOK:  5086  ms ****
I/jxcore-log( 3941): 
,I/jxcore-log( 3941): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3941): 
I/BluetoothAdapterState( 2643): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,E/WifiConfigStore( 1018): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/BluetoothUtils( 2643): getBtEnabledContainers(): btContainers = []
D/BluetoothAdapterProperties( 2643): Scan Mode:20
,D/BluetoothAdapterState( 2643): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,E/bt-btif ( 2643): btif_dm_generic_evtnup, sock_thread_handle:6, rfc_init:1, vhci_init:1
E/bt-btif ( 2643): btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
,E/bt-btif ( 2643): cmd socket is not created
,E/bt-btm  ( 2643): btm_ble_start_auto_conn start : 0, 0
W/bt-btif ( 2643): bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,D/btif_config_util( 2643): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-l2cap( 2643): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2643): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 2643): L2CAP - PSM: 0x001b not found for deregistration
,D/ActivityManager( 1018): startService callerProcessName:com.sec.android.app.samsungapps, calleePkgName: com.sec.android.app.samsungapps
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.sec.android.app.samsungapps/com.sec.android.app.samsungapps.autoupdateservice.AutoUpdateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,W/InputMethodManagerService( 1018): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,I/InputMethodManagerService( 1018): [BT Setting State] State =13
,D/hcjo    ( 4598): AutoUpdateManager:IDLE:execute
,D/BluetoothTile( 1180):  onBluetoothStateChange:
,D/InitializeManagerStateMachine( 4598): execute::IDLE:EXECUTE
,D/BluetoothTile( 1180):  onBluetoothPairedDevicesChanged:
D/BluetoothTile( 1180): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothTile( 1180):  getBluetoothState : 13
,D/InitializeManagerStateMachine( 4598): exit::IDLE
D/InitializeManagerStateMachine( 4598): entry::NETWORK_CHECK
,I/SamsungIME( 1838): STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,D/BluetoothSocket( 2643): close() in, this: android.bluetooth.BluetoothSocket@23cd70c3, channel: 5, state: LISTENING
D/BluetoothSocket( 2643): close() this: android.bluetooth.BluetoothSocket@23cd70c3, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@12276e41, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@10a69d40mSocket: android.net.LocalSocket@3a5aa479 impl:android.net.LocalSocketImpl@254b15be fd:FileDescriptor[76]
D/BluetoothSocket( 2643): Closing mSocket: android.net.LocalSocket@3a5aa479 impl:android.net.LocalSocketImpl@254b15be fd:FileDescriptor[76]
,D/InitializeManagerStateMachine( 4598): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 4598): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 4598): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 4598): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 4598): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 4598): entry::SUCCESS
D/hcjo    ( 4598): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/WifiP2pService( 1018): InactiveState{ what=143375 }
,D/WifiP2pService( 1018): P2pEnabledState{ what=143375 }
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/CommandListener(  279): Clearing all IP addresses on wlan0,
V/NativeCrypto( 1637): Read error: ssl=0xb81b5258: I/O error during system call, Connection timed out
,E/ConnectivityService( 1018): updateNetworkInfo()
,D/ConnectivityService( 1018): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService( 1018): updateNetworkInfo()
D/ConnectivityService( 1018): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
V/NativeCrypto( 1637): SSL shutdown failed: ssl=0xb81b5258: I/O error during system call, Broken pipe
D/WifiP2pService( 1018): InactiveState{ what=131204 }
D/WifiNetworkAgent( 1018): NetworkAgent: NetworkAgent channel lost
D/WifiP2pService( 1018): P2pEnabledState{ what=131204 }
,D/ConnectivityService( 1018): reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10012
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): ValidatedState{ when=0 what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): DefaultState{ when=0 what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
D/StatusBarManagerService( 1018): setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
I/System.out( 1018): (HTTPLog)-Static: isSBSettingEnabled false
,D/WifiP2pService( 1018): sending p2p connection changed broadcast: FAILED
I/qtaguid ( 1018): Tagging socket 361 with tag ffffffff00000000{4294967295,0} for uid 10012, pid: 1018, getuid(): 1000
I/qtaguid ( 1018): Untagging socket 361
,D/StatusBarManagerService( 1018): setIconVisibility slot=bluetooth visible=false
,I/WifiTrafficPoller( 1018): evaluateTrafficStatsPolling
,D/StatusBar.NetworkController( 1180): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/BluetoothTile( 1180):  handleUpdatestate:false name:null
D/STATUSBAR-WifiQuickSettingButton( 1180): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/PhoneStatusBar( 1180): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
D/hcjo    ( 4598): AutoUpdateTriggerManager:IDLE:setInterval:345600000
I/System.out( 1018): (HTTPLog)-Static: isSBSettingEnabled false
,D/BluetoothTile( 1180):  handleUpdatestate:false name:null
,D/STATUSBAR-QSTileView( 1180): onStateChanged: Bluetooth
,D/WifiScanningService( 1018): SCAN_AVAILABLE : 1
D/WifiScanningService( 1018): DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
,D/RttService( 1018): SCAN_AVAILABLE : 1
D/RttService( 1018): EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiDisplayController( 1018): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/WifiDisplayAdapter( 1018): onP2pDisconnected
,D/IpRemoteDisplayController( 1018): disconnectWfdBridgeServer
D/IpRemoteDisplayController( 1018): WfdBridgeServer is already null
,D/StatusBar.NetworkController( 1180): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1180): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/WifiP2pService( 1018): sending p2p connection changed broadcast: DISCONNECTED
D/ActivityManager( 1018): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.artwork.ArtDownloadService2; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,E/WifiStateMachine( 1018): BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,D/WifiDisplayController( 1018): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
,D/WifiDisplayController( 1018): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayController( 1018): disconnect
D/WifiDisplayController( 1018): updateConnection
D/WifiDisplayController( 1018): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayAdapter( 1018): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,D/hcjo    ( 4598): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 4598): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,D/AllShareCastTile( 1180): action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
D/WifiDisplayAdapter( 1018): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
D/AllShareCastTile( 1180): wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,D/WifiP2pService( 1018): P2pDisablingState
D/WifiP2pService( 1018): P2pDisablingState{ what=147458 }
D/WifiP2pService( 1018): p2p socket connection lost
D/WifiP2pService( 1018): P2pDisabledState
,D/WifiDisplayController( 1018): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
D/WifiDisplayAdapter( 1018): onP2pDisconnected
D/IpRemoteDisplayController( 1018): disconnectWfdBridgeServer
D/IpRemoteDisplayController( 1018): WfdBridgeServer is already null
,D/WifiP2pService( 1018): P2pDisabledState{ what=143375 }
D/WifiP2pService( 1018): DefaultState{ what=143375 }
,D/InitializeManagerStateMachine( 4598): exit::SUCCESS
D/InitializeManagerStateMachine( 4598): entry::IDLE
D/CommandListener(  279): Clearing all IP addresses on wlan0
D/EnterpriseController(  279): uids 1000
D/EnterpriseController(  279): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 0 for uid 1000
D/StatusBar.NetworkController( 1180): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1180): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): Validated
D/ConnectivityService( 1018): setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
D/ConnectivityService( 1018): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
,D/ConnectivityManager.CallbackHandler( 1180): CM callback handler got msg 524292
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1018): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/WIFI_P2P( 1018): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/ConnectivityManager.CallbackHandler( 2000): CM callback handler got msg 524292
D/TelephonyNetworkFactory( 1456): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/TelephonyNetworkFactory( 1456): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/EntConnectivity( 1018): Not allowed due to - mEnabled false - primarySimSlot false
D/CSLegacyTypeTracker( 1018): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.129/24,fe80::7ef9:eff:fe37:96ac/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
I/wpa_supplicant( 2081): p2p0: State: DISCONNECTED -> DISCONNECTED
D/CSLegacyTypeTracker( 1018): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
D/ConnectivityService( 1018): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,I/WifiTrafficPoller( 1018): evaluateTrafficStatsPolling
,D/StatusBar.NetworkController( 1180): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1180): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/ConnectivityService( 1018): nai.networkMonitor.doQuit()
,D/Tethering( 1018): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
D/Tethering( 1018): MasterInitialState.processMessage what=3
D/EntConnectivity( 1018): Not allowed due to - mEnabled false - primarySimSlot false
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): doQuit - quitNow()
D/ConnectivityService( 1018): NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService( 1018): updateNetworkInfo()
E/ConnectivityService( 1018): updateNetworkInfo()
,D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
V/NetworkStats( 1018): updateIfacesLocked()
D/NetworkStatsFactory( 1018): UpdateStatsForKnox updated
V/NetworkStats( 1018): performPollLocked(flags=0x1)
D/NetworkStatsFactory( 1018): UpdateStatsForKnox main else ---
,D/StatusBar.NetworkController( 1180): EthernetConnected: false
D/StatusBar.NetworkController( 1180): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1180): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1180): updateDataNetType()
D/StatusBar.NetworkController( 1180): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1180): updateLTEICONDataNetType:0
,V/NetworkStats( 1018): performPollLocked() took 7ms
,D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
V/NetworkStats( 1018): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 1180): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1180): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 -1 -1 -1 -1 -1 -1 99 2147483647 2147483647 2147483647 2147483647 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1180): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1180): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1180): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/WIFI    ( 1018): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/WifiDisplayAdapter( 1018): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
D/SecContentProvider2( 1018): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1018): mCursor = null
,I/WebViewFactory( 4613): Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
,D/StatusBar.NetworkController( 1180): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1180): onWifiSignalChanged enabled=false enabledDesc:null
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/STATUSBAR-WifiQuickSettingButton( 1180): onReceive : android.net.wifi.WIFI_STATE_CHANGED
,D/STATUSBAR-WifiQuickSettingButton( 1180): Wifi onReceive(0)
D/HotspotTile( 1180): onReceive : android.net.wifi.WIFI_STATE_CHANGED
,D/STATUSBAR-QSTileView( 1180): onStateChanged: Wi-Fi
,D/HotspotTile( 1180): onReceive : 0, 0
,D/WifiCredService( 1333): Action received :android.net.wifi.WIFI_STATE_CHANGED
,D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
,W/bt-l2cap( 2643): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2643): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 2643): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap( 2643): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2643): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 2643): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap( 2643): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2643): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 2643): L2CAP - PSM: 0x001b not found for deregistration
W/bt-btif ( 2643): ag scb idx 1 not allocated
W/bt-btif ( 2643): ag scb idx 2 not allocated
E/bt-btif ( 2643): BTA AG is already disabled, ignoring ...
I/bt_userial_mct( 2643): exiting userial_read_thread
D/bt_userial_mct( 2643): Leaving userial_evt_read_thread()
D/bt_userial_mct( 2643): userial_close_reader Joined userial reader thread: 0
I/bt_vendor( 2643): hw_epilog_process
D/bt_userial_mct( 2643): userial_close
I/bt_vendor( 2643): bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,I/ActivityManager( 1018): Killing 3752:com.samsung.android.app.watchmanagerstub/u0a100 (adj 15): empty #31
,D/WifiDisplayAdapter( 1018): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/wpa_supplicant( 2081): Blacklist: Clear (all) 
,I/AudioService( 1018): getStreamVolume 3 index 0
,I/MediaRouter( 4549): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,I/LibraryLoader( 4613): Time to load native libraries: 3 ms (timestamps 7665-7668)
,I/LibraryLoader( 4613): Expected native library version number "",actual native library version number ""
,V/MusicLeanback( 4549): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,V/WebViewChromiumFactoryProvider( 4613): Binding Chromium to main looper Looper (main, tid 1) {1b8769b1}
,I/LibraryLoader( 4613): Expected native library version number "",actual native library version number "",
I/chromium( 4613): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4613): Initializing chromium process, singleProcess=true
,W/art     ( 4613): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 4613): ApplicationContext is null in ApplicationStatus
,W/libprocessgroup( 1018): failed to open /acct/uid_10100/pid_3752/cgroup.procs: No such file or directory
,I/wpa_supplicant( 2081): p2p0: CTRL-EVENT-TERMINATING 
,I/Nat464Xlat( 1018): interfaceLinkStateChanged p2p0, false
,D/Tethering( 1018): interfaceLinkStateChanged p2p0, false
D/Tethering( 1018): interfaceStatusChanged p2p0, false
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
D/ActivityManager( 1018): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/PhoneApp( 1456): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/ActivityManager( 1018): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.ArtDownloadQueueService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/FileWriteThread_Telephony( 1456): FileWriteThread : threadType = 3
D/PhoneApp( 1456): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1456): FileWriteThread : threadType = 3
,D/PhoneApp( 1456): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/ActivityManager( 1018): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.ArtCacheService; callingUser = 0; userId(target) = 0
D/AndroidRuntime( 4659): 
D/AndroidRuntime( 4659): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/FileWriteThread_Telephony( 1456): FileWriteThread : threadType = 3
,D/PhoneApp( 1456): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
D/AndroidRuntime( 4659): CheckJNI is OFF
D/AndroidRuntime( 4659): readGMSProperty: start
D/AndroidRuntime( 4659): readGMSProperty: already setted!!
D/AndroidRuntime( 4659): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 4659): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 4659): readGMSProperty: end
D/AndroidRuntime( 4659): addProductProperty: start
D/FileWriteThread_Telephony( 1456): FileWriteThread : threadType = 3
D/PhoneApp( 1456): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/WifiDisplayAdapter( 1018): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/FileWriteThread_Telephony( 1456): FileWriteThread : threadType = 3
D/PhoneApp( 1456): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1456): FileWriteThread : threadType = 3
D/PhoneApp( 1456): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1456): FileWriteThread : threadType = 3
D/PhoneApp( 1456): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,I/wpa_supplicant( 2081): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.wifi.WifiStateMachine.insertLog:14952 com.android.server.wifi.WifiStateMachine.access$2700:217 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:6951 com.android.internal.util.StateMachine$SmHandler.processMsg:966 
I/wpa_supplicant( 2081): wlan0: State: COMPLETED -> DISCONNECTED
I/wpa_supplicant( 2081): Prev BSS - hexdump(len=6): c0 ff d4 d3 aa 48
I/wpa_supplicant( 2081): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 2081): wlan0: State: DISCONNECTED -> DISCONNECTED
I/Nat464Xlat( 1018): interfaceLinkStateChanged wlan0, false
D/Tethering( 1018): interfaceLinkStateChanged wlan0, false
D/Tethering( 1018): interfaceStatusChanged wlan0, false
D/Tethering( 1018): InitialState.processMessage what=4
,D/FileWriteThread_Telephony( 1456): FileWriteThread : threadType = 3
,E/Tethering( 1018): No numeric data
I/Nat464Xlat( 1018): interfaceLinkStateChanged wlan0, false
D/Tethering( 1018): interfaceLinkStateChanged wlan0, false
D/Tethering( 1018): interfaceStatusChanged wlan0, false
,D/PhoneApp( 1456): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
I/Nat464Xlat( 1018): interfaceLinkStateChanged wlan0, false
D/Tethering( 1018): interfaceLinkStateChanged wlan0, false
D/Tethering( 1018): interfaceStatusChanged wlan0, false
,I/Nat464Xlat( 1018): interfaceLinkStateChanged wlan0, false
D/Tethering( 1018): interfaceLinkStateChanged wlan0, false
D/Tethering( 1018): interfaceStatusChanged wlan0, false
D/ActivityManager( 1018): startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
D/FileWriteThread_Telephony( 1456): FileWriteThread : threadType = 3
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,D/PhoneApp( 1456): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1456): FileWriteThread : threadType = 3
D/PhoneApp( 1456): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1456): FileWriteThread : threadType = 3
D/PhoneApp( 1456): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1456): FileWriteThread : threadType = 3
D/PhoneApp( 1456): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,E/Zygote  ( 4688): MountEmulatedStorage()
I/libpersona( 4688): KNOX_SDCARD checking this for 10002
E/Zygote  ( 4688): v2
I/libpersona( 4688): KNOX_SDCARD not a persona
I/SELinux ( 4688): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,W/chromium( 4613): [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,I/SELinux ( 4688): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,I/chromium( 4613): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=44 off=50556 len=3379
,E/SELinux ( 4688): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/chromium( 4613): [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:45 off:7638088 len:1165478
D/FileWriteThread_Telephony( 1456): FileWriteThread : threadType = 3
D/PhoneApp( 1456): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,I/Adreno-EGL( 4613): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 4613): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 4613): Build Date: 04/06/15 Mon
I/Adreno-EGL( 4613): Local Branch: 
I/Adreno-EGL( 4613): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 4613): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 4613):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,D/FileWriteThread_Telephony( 1456): FileWriteThread : threadType = 3
D/PhoneApp( 1456): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,I/ActivityManager( 1018): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=4688 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/Tethering( 1018): sendTetherStateChangedBroadcast 0, 0, 0
D/Tethering( 1018): clearTetheredNotification()
,D/FileWriteThread_Telephony( 1456): FileWriteThread : threadType = 3
V/NetworkStats( 1018): performPollLocked(flags=0x1)
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
D/NetworkStatsFactory( 1018): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1018): UpdateStatsForKnox main else ---
,D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
D/HotspotTile( 1180): onReceive : android.net.conn.TETHER_STATE_CHANGED
D/HotspotTile( 1180): updateTetherState():false, false
V/NetworkStats( 1018): performPollLocked() took 4ms
,D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
I/bt_vendor( 2643): bt-vendor : BT_VND_OP_POWER_CTRL: Off
I/bt_vendor( 2643): bluetooth satus is on
I/bt_vendor( 2643): bt-vendor : resetting BT status
D/TimaKeyStoreProvider( 4688): TimaSignature is unavailable
I/bt_vendor( 2643): Starting hciattach daemon
I/bt_vendor( 2643): try to set false
D/ActivityThread( 4688): Added TimaKeyStore provider
,I/bt_vendor( 2643): Starting hciattach daemon
I/bt_vendor( 2643): try to set false
,I/bt_vendor( 2643): cleanup
I/GKI_LINUX( 2643): gki_task task_id=0 [BTU] terminating
I/GKI_LINUX( 2643): GKI_exit_task 0 done
I/GKI_LINUX( 2643): GKI_shutdown(): task [BTU] terminated
,D/BluetoothAdapterState( 2643): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
D/BtConfig.SecureMode( 2643): isSecureModeOn:false
,D/BluetoothAdapterService( 2643): mProfilesStarted : true supportedProfileServices.length : 12
W/BluetoothAdapterService( 2643): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
D/BtSettings.ProfileConfig( 2643): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,W/BluetoothAdapterService( 2643): Not skipping com.android.bluetooth.gatt.GattService
,D/ActivityManager( 1018): startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,D/BtGatt.DebugUtils( 2643): handleDebugAction() action=null,
W/BluetoothAdapterService( 2643): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService,
D/BtGatt.GattService( 2643): Received stop request...Stopping profile...,
D/ActivityManager( 1018): startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,D/BtSettings.ProfileConfig( 2643): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
D/BtGatt.GattService( 2643): stop()
,D/BtGatt.AdvertiseManager( 2643): advertise clients cleared
D/BluetoothAdapterService( 2643): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4e33afe
W/BluetoothAdapterService( 2643): Not skipping com.android.bluetooth.hfp.HeadsetService
W/ActivityManager( 1018): userId = 0, bbcId = -10000,
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/BluetoothAdapterService( 2643): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
,D/BtSettings.ProfileConfig( 2643): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,W/BluetoothAdapterService( 2643): Not skipping com.android.bluetooth.a2dp.A2dpService
,D/ActivityManager( 1018): startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/BluetoothAdapterService( 2643): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 2643): getProfileSaveSetting: com.android.bluetooth.hid.HidService
W/BluetoothAdapterService( 2643): Not skipping com.android.bluetooth.hid.HidService
D/ActivityManager( 1018): startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
W/ActivityManager( 1018): userId = 0, bbcId = -10000
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/BluetoothAdapterService( 2643): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig( 2643): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,W/BluetoothAdapterService( 2643): Not skipping com.android.bluetooth.hdp.HealthService
,D/ActivityManager( 1018): startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/BluetoothAdapterService( 2643): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig( 2643): getProfileSaveSetting: com.android.bluetooth.pan.PanService
W/BluetoothAdapterService( 2643): Not skipping com.android.bluetooth.pan.PanService
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
D/ActivityManager( 1018): startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,D/ActivityManager( 1018): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.gms, action: null
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,W/BluetoothAdapterService( 2643): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig( 2643): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
W/BluetoothAdapterService( 2643): Not skipping com.android.bluetooth.map.BluetoothMapService
D/ActivityManager( 1018): startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
W/BluetoothAdapterService( 2643): check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
D/BtSettings.ProfileConfig( 2643): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,W/BluetoothAdapterService( 2643): Not skipping com.broadcom.bt.service.sap.SapService
,D/ActivityManager( 1018): startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/BluetoothAdapterService( 2643): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
D/BtSettings.ProfileConfig( 2643): getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
W/BluetoothAdapterService( 2643): Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
W/BluetoothAdapterService( 2643): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
D/BtSettings.ProfileConfig( 2643): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
W/BluetoothAdapterService( 2643): Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
W/BluetoothAdapterService( 2643): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
D/BtSettings.ProfileConfig( 2643): getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
W/BluetoothAdapterService( 2643): Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
W/BluetoothAdapterService( 2643): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
D/BtSettings.ProfileConfig( 2643): getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
W/BluetoothAdapterService( 2643): Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
D/BluetoothAdapterState( 2643): Stopping profile services that were post enabled
E/BluetoothAdapterService(82000638)( 2643): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
D/HeadsetService( 2643): Received stop request...Stopping profile...
D/BluetoothAdapterService( 2643): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4e33afe
,D/AudioService( 1018): onServiceDisconnected: Bluetooth profile: 1
,W/ResourcesManager( 4549): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4549): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/A2dpService( 2643): Received stop request...Stopping profile...
,D/A2dpStateMachine( 2643): Exit Disconnected: -1
,D/BluetoothAdapterService( 2643): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4e33afe
,D/BluetoothA2dp( 1018): Proxy object disconnected
,D/BluetoothA2dp( 2911): Proxy object disconnected
D/AudioService( 1018): onServiceDisconnected: Bluetooth profile: 2
E/AffinityControl( 4659): AffinityControl: registerfunction enter
,D/HidService( 2643): Received stop request...Stopping profile...
D/HidService( 2643): Stopping Bluetooth HidService
W/BluetoothHidServiceJni( 2643): Cleaning up Bluetooth HID Interface...
W/bt-btif ( 2643): cleanup: HH disabling or disabled already, status = 0
W/BluetoothHidServiceJni( 2643): Cleaning up Bluetooth GID callback object
D/BluetoothAdapterService( 2643): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4e33afe
,D/HealthService( 2643): Received stop request...Stopping profile...
D/BluetoothAdapterService( 2643): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4e33afe
,I/GHttpClientFactory( 4549): Using the GMSCore's GoogleHttpClient
D/PanService( 2643): Received stop request...Stopping profile...
D/BluetoothAdapterService( 2643): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4e33afe
,D/BluetoothPan( 1018): BluetoothPAN Proxy object disconnected
D/ActivityManager( 1018): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,D/BluetoothMapService( 2643): Received stop request...Stopping profile...
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/BluetoothAdapterService( 2643): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4e33afe
,D/SapService( 2643): Received stop request...Stopping profile...
D/SapService( 2643): Stopping Bluetooth SapService
D/BluetoothAdapterService( 2643): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4e33afe
,E/BluetoothAdapterService(82000638)( 2643): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 2643): getProfileSaveSetting: com.android.bluetooth.hid.HidService
D/BluetoothAdapterService( 2643): Profile still running: com.android.bluetooth.hid.HidService
D/AndroidRuntime( 4659): Calling main entry com.android.commands.pm.Pm
,I/wpa_supplicant( 2081): Blacklist: Clear (all) ,
,W/BluetoothHeadsetServiceJni( 2643): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 2643): Cleaning up Bluetooth Handsfree callback object
E/BluetoothAdapterService(82000638)( 2643): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 2643): getProfileSaveSetting: com.android.bluetooth.hid.HidService
D/BluetoothAdapterService( 2643): Profile still running: com.android.bluetooth.hid.HidService
D/BluetoothA2dp( 2643): Proxy object disconnected
D/BluetoothAdapterService( 2643): Bluetooth A2dp source service disconnected
I/GKI_LINUX( 2643): gki_task task_id=2 [A2DP-MEDIA] terminating
,I/GKI_LINUX( 2643): GKI_exit_task 2 done
I/GKI_LINUX( 2643): GKI_shutdown(): task [A2DP-MEDIA] terminated
E/BluetoothAdapterService(82000638)( 2643): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 2643): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 2643): Profile still running: com.android.bluetooth.map.BluetoothMapService
E/BluetoothAdapterService(82000638)( 2643): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 2643): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 2643): Profile still running: com.android.bluetooth.map.BluetoothMapService
W/BluetoothHealthServiceJni( 2643): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 2643): Cleaning up Bluetooth Health object
E/BluetoothAdapterService(82000638)( 2643): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 2643): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 2643): Profile still running: com.android.bluetooth.map.BluetoothMapService
W/BluetoothPanServiceJni( 2643): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 2643): Cleaning up Bluetooth PAN callback object
D/PersonaManagerService( 1018): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager( 1018): START PACKAGE DELETE: observer{118616333}
D/PackageManager( 1018): pkg{<packageName>}
D/PackageManager( 1018): user{0}
D/PackageManager( 1018): caller{2000}
D/PackageManager( 1018): flags{3}
D/PersonaManagerService( 1018): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService( 1018): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 1018): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
D/PackageManager( 1018): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
D/PackageManager( 1018): [MSG] DELETE_PACKAGE_AS_USER
E/BluetoothAdapterService(82000638)( 2643): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 2643): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService( 2643): Profile still running: com.broadcom.bt.service.sap.SapService
E/BluetoothAdapterService(82000638)( 2643): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
W/BluetoothSAPServiceJni( 2643): ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
W/BluetoothSAPServiceJni( 2643): ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
D/PackageManagerService( 1018): deletePackage- pkg:com.example.hello, edmuserId:0
D/PackageManagerService( 1018): deletePackage- pkg:com.example.hello, edmuserId:-1
D/BluetoothAdapterState( 2643): CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
D/ApplicationPolicy( 1018): getApplicationUninstallationEnabled
D/BluetoothAdapterProperties( 2643): Setting state to 10
I/BluetoothAdapterState( 2643): Bluetooth adapter state changed: 13-> 10
D/BluetoothAdapterService( 2643): Bluetooth PBAP supproted is true
D/BluetoothAdapterService( 2643): updateAdapterState state is 10
D/ApplicationPolicy( 1018): getApplicationUninstallationEnabled :  enabled true
D/BluetoothAdapterService( 2643): Autoconnection is available 
D/BluetoothAdapterService( 2643): updateAdapterState prevState = 13newState = 10
I/BluetoothAdapterState( 2643): Entering OffState
D/BluetoothAdapter( 3770): onBluetoothStateChange: up=false
D/PackageManager( 1018): !@killApplicatoin: 10174, uninstall pkg
D/BluetoothAdapter( 3770): Bluetooth is turned off, stop adv and scan
I/ActivityManager( 1018): Force stopping com.example.hello appid=1,0174 user=-1: uninstall pkg
I/ActivityManager( 1018): Killing 3941:com.example.hello/u0a174 (adj 0): stop com.example.hello cause uninstall pkg
,I/wpa_supplicant( 2081): wlan0: CTRL-EVENT-TERMINATING 
,D/Tethering( 1018): interfaceLinkStateChanged wlan0, false
I/Nat464Xlat( 1018): interfaceLinkStateChanged wlan0, false
D/Tethering( 1018): interfaceStatusChanged wlan0, false
,I/WindowState( 1018): WIN DEATH: Window{c9bf07d u0 com.example.hello/com.example.hello.MainActivity}
,I/SurfaceFlinger(  258): id=11 Removed NainActivit (6/8)
,I/SurfaceFlinger(  258): id=11 Removed NainActivit (-2/8)
,D/InputDispatcher( 1018): Focus left window: 3941
,D/PointerIcon( 1018): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0,
D/PointerIcon( 1018): setMouseCustomIcon IconType is same.101
,I/SA      ( 4297): [RC New] Execute method=[GET] start,
,W/PackageSettings( 1018): Skipping PackageSetting{28b86042 com.test.thalitest/10175} due to missing metadata
,I/SA      ( 4297): [RC New] Security=[true]
,I/System.out( 4297): Thread-635(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 4297): Thread-635(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 4297): Thread-635(ApacheHTTPLog):isShipBuild true
I/System.out( 4297): Thread-635(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 4297): Thread-635(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController(  279): uids 10041
D/EnterpriseController(  279): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 0 for uid 10041
,I/System.out( 4297): AsyncTask #1 calls detatch()
,I/SA      ( 4297): [SRS] prepareGetMyCountryZone
,I/SA      ( 4297): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      ( 4297): [SSP] query invoked
,I/SA      ( 4297): [TPMU] GetMccFromDB : null
I/SA      ( 4297): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 4297): [TPM] isNoProxy(default) : true
I/SA      ( 4297): [RC New] Execute method=[GET] start
,W/ActivityManager( 1018): Force removing ActivityRecord{1b13b37f u0 com.example.hello/.MainActivity t2}: app died, no saved state
,D/FocusedStackFrame( 1018): Set to : 0
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.example.hello
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
,D/InputDispatcher( 1018): Focused application set to: xxxx
,D/ConnectivityService( 1018): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,W/AudioManagerAndroid( 4613): Requires BLUETOOTH permission
,D/CustomFrequencyManagerService( 1018): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  pkgName : ACTIVITY_RESUME_BOOSTER@7
,W/ActivityManager( 1018): mDVFSHelper.acquire()
,D/PowerManagerService( 1018): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 1018) eventTime = 48105
,D/PowerManagerService( 1018): [s] UserActivityState : 2 -> 1
D/PowerManagerService( 1018): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1018 (0x0)
,D/PowerManagerService( 1018): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=1018, ws=WorkSource{1000}) (elapsedTime=3453)
,V/WindowOrientationListener( 1018): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
V/WindowManager( 1018): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener( 1018): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
,D/BluetoothAdapter( 2643): onBluetoothStateChange: up=false
D/BluetoothAdapter( 2643): Bluetooth is turned off, stop adv and scan
,E/WifiStateMachine( 1018): skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
D/WifiNative-wlan0( 1018): callSECApiBoolean - ID [21]
,W/ActivityManager( 1018): Spurious death for ProcessRecord{19a9fd2f 3941:com.example.hello/u0a174}, curProc for 3941: null
E/WifiConfigStore( 1018): setLastSelectedConfiguration -1
,I/ActivityManager( 1018): Force stopping com.example.hello appid=10174 user=0: pkg removed
,D/BluetoothAdapter( 2911): onBluetoothStateChange: up=false
D/BluetoothAdapter( 2911): Bluetooth is turned off, stop adv and scan
,E/Watchdog( 1018): !@Sync 1
,I/SA      ( 4297): [RC New] Security=[true]
,I/System.out( 4297): Thread-635(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 4297): Thread-635(ApacheHTTPLog):isShipBuild true
I/System.out( 4297): Thread-635(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 4297): Thread-635(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/System.out( 4297): AsyncTask #1 calls detatch()
,W/System.err( 4297): java.net.UnknownHostException: Unable to resolve host "api.samsungosp.com": No address associated with hostname
,W/System.err( 4297): 	at java.net.InetAddress.lookupHostByName(InetAddress.java:427)
W/System.err( 4297): 	at java.net.InetAddress.getAllByNameImpl(InetAddress.java:252)
W/System.err( 4297): 	at java.net.InetAddress.getAllByName(InetAddress.java:215)
W/System.err( 4297): 	at org.apache.http.impl.conn.DefaultClientConnectionOperator.openConnection(DefaultClientConnectionOperator.java:180)
W/System.err( 4297): 	at org.apache.http.impl.conn.AbstractPoolEntry.open(AbstractPoolEntry.java:167)
W/System.err( 4297): 	at org.apache.http.impl.conn.AbstractPooledConnAdapter.open(AbstractPooledConnAdapter.java:125)
W/System.err( 4297): 	at org.apache.http.impl.client.DefaultRequestDirector.executeOriginal(DefaultRequestDirector.java:1312)
W/System.err( 4297): 	at org.apache.http.impl.client.DefaultRequestDirector.execute(DefaultRequestDirector.java:702)
W/System.err( 4297): 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:694)
W/System.err( 4297): 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:516)
W/System.err( 4297): 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:494)
W/System.err( 4297): 	at com.msc.b.d.a(HttpRestClient.java:378)
W/System.err( 4297): 	at com.msc.b.d.a(HttpRestClient.java:679)
W/System.err( 4297): 	at com.msc.b.i.a(TransactionManager.java:159)
W/System.err( 4297): 	at com.msc.c.g.a(HttpRequestSet.java:4909)
W/System.err( 4297): 	at com.osp.app.signin.gp.h(OspReceiver.java:827)
W/System.err( 4297): 	at com.osp.app.signin.gp.b(OspReceiver.java:805)
W/System.err( 4297): 	at com.msc.b.d.a(HttpRestClient.java:393)
W/System.err( 4297): 	at com.msc.b.d.a(HttpRestClient.java:679)
W/System.err( 4297): 	at com.msc.b.i.a(TransactionManager.java:159)
W/System.err( 4297): 	at com.msc.c.g.a(HttpRequestSet.java:4909)
W/System.err( 4297): 	at com.osp.app.signin.gp.h(OspReceiver.java:827)
W/System.err( 4297): 	at com.osp.app.signin.gp.a(OspReceiver.java:701)
W/System.err( 4297): 	at com.osp.app.signin.gp.doInBackground(OspReceiver.java:663)
W/System.err( 4297): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
W/System.err( 4297): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/System.err( 4297): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/System.err( 4297): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/System.err( 4297): 	at java.lang.Thread.run(Thread.java:818)
I/SA      ( 4297): [RC New] executeRequest [v2liruge] end. 46
I/SA      ( 4297): [RC New] Execute end
W/System.err( 4297): java.net.UnknownHostException: Unable to resolve host "api.samsungosp.com": No address associated with hostname
W/System.err( 4297): 	at java.net.InetAddress.lookupHostByName(InetAddress.java:457)
W/System.err( 4297): 	at java.net.InetAddress.getAllByNameImpl(InetAddress.java:252)
W/System.err( 4297): 	at java.net.InetAddress.getAllByName(InetAddress.java:215)
W/System.err( 4297): 	at org.apache.http.impl.conn.DefaultClientConnectionOperator.openConnection(DefaultClientConnectionOperator.java:180)
W/System.err( 4297): 	at org.apache.http.impl.conn.AbstractPoolEntry.open(AbstractPoolEntry.java:167)
W/System.err( 4297): 	at org.apache.http.impl.conn.AbstractPooledConnAdapter.open(AbstractPooledConnAdapter.java:125)
W/System.err( 4297): 	at org.apache.http.impl.client.DefaultRequestDirector.executeOriginal(DefaultRequestDirector.java:1312)
W/System.err( 4297): 	at org.apache.http.impl.client.DefaultRequestDirector.execute(DefaultRequestDirector.java:702)
W/System.err( 4297): 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:694)
W/System.err( 4297): 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:516)
W/System.err( 4297): 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:494)
W/System.err( 4297): 	at com.msc.b.d.a(HttpRestClient.java:378)
W/System.err( 4297): 	at com.msc.b.d.a(HttpRestClient.java:679)
W/System,.err( 4297): 	at com.msc.b.i.a(TransactionManager.java:159)
W/System.err( 4297): 	at com.msc.c.g.a(HttpRequestSet.java:4909)
W/System.err( 4297): 	at com.osp.app.signin.gp.h(OspReceiver.java:827)
W/System.err( 4297): 	at com.osp.app.signin.gp.a(OspReceiver.java:701)
W/System.err( 4297): 	at com.osp.app.signin.gp.doInBackground(OspReceiver.java:663)
W/System.err( 4297): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
W/System.err( 4297): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/System.err( 4297): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/System.err( 4297): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/System.err( 4297): 	at java.lang.Thread.run(Thread.java:818)
W/System.err( 4297): Caused by: android.system.GaiException: android_getaddrinfo failed: EAI_NODATA (No address associated with hostname)
W/System.err( 4297): 	at libcore.io.Posix.android_getaddrinfo(Native Method)
W/System.err( 4297): 	at libcore.io.ForwardingOs.android_getaddrinfo(ForwardingOs.java:55)
W/System.err( 4297): 	at java.net.InetAddress.lookupHostByName(InetAddress.java:438)
W/System.err( 4297): 	... 22 more
I/SA      ( 4297): [RC New] executeRequest [v2liruge] end. 91
I/SA      ( 4297): [RC New] Execute end
I/SA      ( 4297): [OR] GetMyCountryZoneTask mcc = null
I/SA      ( 4297): [OR] GetMyCountryZoneTask Fail
,W/ActivityManager( 1018): CustomStartingWindow se packge removed so remove capture also
,D/Launcher( 1480): onRestart, Launcher: 699664650
,D/SettingsProvider( 1018): name = audio_safe_volume_state
,D/BluetoothAdapter( 1863): onBluetoothStateChange: up=false
,D/Launcher( 1480): onStart, Launcher: 699664650
,D/Launcher.HomeView( 1480): onStart
,D/BluetoothAdapter( 1863): Bluetooth is turned off, stop adv and scan
,D/Launcher( 1480): onResume, Launcher: 699664650
,W/Settings( 4045): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/BluetoothA2dp( 1018): onBluetoothStateChange: up=false
,D/SettingsProvider( 1018): name = kids_home_mode
,D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 10007
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
,D/Launcher.HomeView( 1480): onResume
,D/Launcher( 1480): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,D/WifiCredService( 1333): Action received :android.net.wifi.WIFI_STATE_CHANGED
,D/StatusBar.NetworkController( 1180): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1180): onWifiSignalChanged enabled=false enabledDesc:null
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/STATUSBAR-WifiQuickSettingButton( 1180): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/STATUSBAR-WifiQuickSettingButton( 1180): Wifi onReceive(1)
,D/STATUSBAR-QSTileView( 1180): onStateChanged: Wi-Fi
D/HotspotTile( 1180): onReceive : android.net.wifi.WIFI_STATE_CHANGED,
,D/HotspotTile( 1180): onReceive : 1, 0
,I/SurfaceFlinger(  258): id=13 createSurf (1x1),1 flag=4, Uoast
,W/Settings( 1863): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/PowerManagerService( 1018): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1018
,D/SRIB_DCS( 1180): log_dcs ThreadedRenderer::initialize entered! 
,E/SamsungIME( 1838): mOCRHelper is null
,I/InputReader( 1018): Reconfiguring input devices.  changes=0x00000010
,W/GeofencerStateMachine( 1863): Ignoring removeGeofence because network location is disabled.
,D/EnterpriseDeviceManagerService( 1018): Package has changed for user 0
,D/EnterpriseDeviceManagerService( 1018): Admin package name: com.google.android.gms
,D/SensorService( 1018): [SO] 0.192 0.115 10.113
,W/TextServicesManagerService( 1018): no available spell checker services found
,I/DBG_DM  ( 3176): [com.wssyncmldm.XDMService(936/lIllIlllIIllllIlIlIl)] WiFi network Connected : false
,I/DBG_DM  ( 3176): [com.wssyncmldm.XDMService(952/llIlIllllllllllllllI)] Bluetooth Data Connected : false
,D/BluetoothAdapter( 1180): onBluetoothStateChange: up=false
,D/BluetoothAdapter( 1180): Bluetooth is turned off, stop adv and scan
,D/BluetoothAdapter( 1456): onBluetoothStateChange: up=false
D/BluetoothAdapter( 1456): Bluetooth is turned off, stop adv and scan
,D/MenuAppsGridFragment( 1480): onResume
,D/BluetoothA2dp( 2643): onBluetoothStateChange: up=false
,D/RegisteredComponentCache( 1442): Collect Tech packages for Knox
,I/NSApplication( 4613): Starting up...
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/ActivityManager( 1018): Killing 3788:com.samsung.android.app.accesscontrol/1000 (adj 15): empty #31,
,D/ActivityManager( 1018): startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,D/RCPManagerService( 1018): PackageReceiver onReceive()
,I/HarmonyEASService( 1018): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,E/Zygote  ( 4734): MountEmulatedStorage()
I/libpersona( 4734): KNOX_SDCARD checking this for 1000
E/Zygote  ( 4734): v2
I/libpersona( 4734): KNOX_SDCARD not a persona
I/SELinux ( 4734): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4734): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4734): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,I/ActivityManager( 1018): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=4734 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/art     ( 1018): Explicit concurrent mark sweep GC freed 44712(2MB) AllocSpace objects, 7(160KB) LOS objects, 33% free, 27MB/40MB, paused 3.327ms total 191.295ms
D/KnoxMUMContainerPolicy( 1018): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,D/SecContentProvider2( 1018): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1018): mCursor = null
,I/OTPFW   ( 1018): PackageRemovalReceiver::onReceive Enter
,I/art     (  306): Explicit concurrent mark sweep GC freed 8728(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 759us total 21.353ms
,D/OTPFW   ( 1018): OtpDbHelper::getInstance New instance created
,D/TimaKeyStoreProvider( 4734): TimaSignature is unavailable
,D/ActivityThread( 4734): Added TimaKeyStore provider
D/OTPFW   ( 1018): DBIntegrity::getInstance - New instance created
,D/PersonaManager( 1442): isKioskContainerExistOnDevice
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/OTPFW   ( 1018): PackageRemovalReceiver::onReceive deleting token for Pkg = com.example.hello uid = 10174 container id = 0
I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 796us total 20.772ms
,I/OTPFW   ( 1018): ProvisionData::getAllEntries Enter
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
E/OTPFW   ( 1018): ProvisionData::getAllEntries Table is empty
,D/PackageManager( 1018): delete codoeFile: 
,I/AASA_removePackage( 1018): UID=10174 Target=com.example.hello
D/AASAuninstall( 1018): userId = 0, info.removedAppID = -1, info.uid = 10174, packageName = com.example.hello
,D/BackupManagerService( 1018): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,D/JobSchedulerService( 1018): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1018): uID is 10174
V/EnterpriseBillingPolicy( 1018): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1018): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage( 1018): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1018): getBillingProfileForVpnEngine - start - com.example.hello
,D/PackageManager( 1018): result of delete: 1{118616333}
,V/EnterpriseBillingPolicyStorage( 1018): getBillingProfileForVpnEngine - end - null
,I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 628us total 19.864ms
D/AndroidRuntime( 4659): Shutting down VM
,D/ActivityManager( 1018): handle home activity for 0
I/WallpaperManagerService( 1018): switchPersonaWallpaper is called for personaId-0
D/KnoxTimeoutHandler( 1018): post home show event for user 0
D/ActivityManager( 1018): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1018): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1018): postActiveUserChange, showWhenLocked: false
,I/ActivityManager( 1018): Waited long enough for: ServiceRecord{1b238300 u0 com.samsung.android.providers.context/.ContextService}
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.example.hello
,V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
V/AlarmManagerEXT( 1018): com.example.hello(10174) is removed.
V/EnterpriseBillingPolicy( 1018): uID is 10174
V/EnterpriseBillingPolicy( 1018): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1018): getProfileForApplication - enter
,I/SurfaceFlinger(  258): id=14 createSurf (720x1280),1 flag=4, Mauncher
V/EnterpriseBillingPolicyStorage( 1018): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1018): getBillingProfileForVpnEngine - start - com.example.hello
,V/EnterpriseBillingPolicyStorage( 1018): getBillingProfileForVpnEngine - end - null
,D/StatusBarManagerService( 1018): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/BluetoothAdapter( 1018): onBluetoothStateChange: up=false
D/BluetoothAdapter( 1018): Bluetooth is turned off, stop adv and scan
D/TaskPersister( 1018): removeObsoleteFile: deleting file=2_task.xml
D/SensorService( 1018): [SO] activate (ident=0xb84959c0, enabled=0)
D/WindowOrientationListener( 1018):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
I/Sensors ( 1018): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
D/SSRM:aZ ( 1018): MSG_TYPE_APP_REMOVED::
D/StatusBarManagerService( 1018): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/InputDispatcher( 1018): Focus entered window: 1480
D/SRIB_DCS( 1480): log_dcs ThreadedRenderer::initialize entered! 
,I/ActivityManager( 1018): Killing 3770:com.vlingo.midas/u0a31 (adj 15): empty #31
,D/PointerIcon( 1018): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1018): setMouseCustomIcon IconType is same.101
,D/BluetoothAdapter( 4269): onBluetoothStateChange: up=false
,D/BluetoothAdapter( 4269): Bluetooth is turned off, stop adv and scan
,E/BluetoothManagerService( 1018): Unable to call onBluetoothStateChange() on callback #17
E/BluetoothManagerService( 1018): android.os.DeadObjectException
E/BluetoothManagerService( 1018): 	at android.os.BinderProxy.transactNative(Native Method)
E/BluetoothManagerService( 1018): 	at android.os.BinderProxy.transact(Binder.java:511)
E/BluetoothManagerService( 1018): 	at android.bluetooth.IBluetoothStateChangeCallback$Stub$Proxy.onBluetoothStateChange(IBluetoothStateChangeCallback.java:84)
E/BluetoothManagerService( 1018): 	at com.android.server.BluetoothManagerService.sendBluetoothStateCallback(BluetoothManagerService.java:1067)
E/BluetoothManagerService( 1018): 	at com.android.server.BluetoothManagerService.bluetoothStateChangeHandler(BluetoothManagerService.java:2021)
E/BluetoothManagerService( 1018): 	at com.android.server.BluetoothManagerService.access$3900(BluetoothManagerService.java:105)
E/BluetoothManagerService( 1018): 	at com.android.server.BluetoothManagerService$BluetoothHandler.handleMessage(BluetoothManagerService.java:1590)
E/BluetoothManagerService( 1018): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/BluetoothManagerService( 1018): 	at android.os.Looper.loop(Looper.java:145)
E/BluetoothManagerService( 1018): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/BluetoothManagerService( 1018): 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
D/SensorManager( 1018): unregisterListener ::   
D/BluetoothAdapter( 1432): onBluetoothStateChange: up=false
D/BluetoothAdapter( 1432): Bluetooth is turned off, stop adv and scan
,I/Sensors ( 1018): AccelerometerSensor(0) setDelay : 200000000(ns)
,D/SensorService( 1018): [SO] changed settle time [0]
D/SensorService( 1018): [SO] setDelay [200000000]
D/ActivityManager( 1018): startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
D/SensorService( 1018): [SO] activate (ident=0xb866f840, enabled=1)
D/SensorService( 1018): [SO] AR_init
I/Sensors ( 1018): AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,D/SensorManager( 1018): registerListener :: 1600221811, Screen Orientation Sensor, 200000, 0,  
,D/Launcher( 1480): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0,
,E/Zygote  ( 4750): MountEmulatedStorage()
E/Zygote  ( 4750): v2
I/libpersona( 4750): KNOX_SDCARD checking this for 10120
I/libpersona( 4750): KNOX_SDCARD not a persona
,I/SELinux ( 4750): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/ActivityManager( 1018): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=4750 uid=10120 gids={50120, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 4750): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4750): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/InputMethodManagerService( 1018): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,D/BluetoothA2dp( 2911): onBluetoothStateChange: up=false
,I/ActivityManager( 1018): Killing 3307:com.google.android.youtube/u0a166 (adj 15): empty #31
,W/InputMethodManagerService( 1018): Got RemoteException sending setActive(false) notification to pid 3941 uid 10174
,D/BluetoothAdapter( 1442): onBluetoothStateChange: up=false
D/BluetoothAdapter( 1442): Bluetooth is turned off, stop adv and scan
W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BluetoothAdapter( 1637): onBluetoothStateChange: up=false
D/BluetoothAdapter( 1637): Bluetooth is turned off, stop adv and scan
,D/BluetoothManagerService( 1018): Broadcasting onBluetoothServiceDown() to 11 receivers.
,I/DIAGMON_AGENT( 4734): [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,D/PersonaManager( 1442): isKioskContainerExistOnDevice
,D/RegisteredServicesCache( 1442): empty dynamic service
,D/PersonaManager( 1018): isKioskContainerExistOnDevice
,D/SamsungIME( 1838): onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,D/TimaKeyStoreProvider( 4750): TimaSignature is unavailable
,D/ActivityThread( 4750): Added TimaKeyStore provider
,E/BluetoothManagerService( 1018): Unable to call onBluetoothServiceDown() on callback #8
E/BluetoothManagerService( 1018): android.os.DeadObjectException
E/BluetoothManagerService( 1018): 	at android.os.BinderProxy.transactNative(Native Method)
E/BluetoothManagerService( 1018): 	at android.os.BinderProxy.transact(Binder.java:511)
E/BluetoothManagerService( 1018): 	at android.bluetooth.IBluetoothManagerCallback$Stub$Proxy.onBluetoothServiceDown(IBluetoothManagerCallback.java:105)
E/BluetoothManagerService( 1018): 	at com.android.server.BluetoothManagerService.sendBluetoothServiceDownCallback(BluetoothManagerService.java:1103)
E/BluetoothManagerService( 1018): 	at com.android.server.BluetoothManagerService.bluetoothStateChangeHandler(BluetoothManagerService.java:2043)
E/BluetoothManagerService( 1018): 	at com.android.server.BluetoothManagerService.access$3900(BluetoothManagerService.java:105)
E/BluetoothManagerService( 1018): 	at com.android.server.BluetoothManagerService$BluetoothHandler.handleMessage(BluetoothManagerService.java:1590)
E/BluetoothManagerService( 1018): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/BluetoothManagerService( 1018): 	at android.os.Looper.loop(Looper.java:145)
E/BluetoothManagerService( 1018): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/BluetoothManagerService( 1018): 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,W/ResourcesManager( 4750): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/BluetoothManagerService( 1018): Broadcasting onBluetoothServiceUp() to 0 receivers.
,W/ResourceType( 1018): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,D/CustomFrequencyManagerService( 1018): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  tag : ACTIVITY_RESUME_BOOSTER@7
,W/ActivityManager( 1018): mDVFSHelper.release()
,D/CustomFrequencyManagerService( 1018): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  pkgName : ACTIVITY_RESUME_BOOSTER@11
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/art     ( 4659): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/Tethering( 1018): interfaceRemoved wlan0
,E/Tethering( 1018): attempting to remove unknown iface (wlan0), ignoring
,W/ResourcesManager( 1018): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1018): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1018): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/ActivityManager( 1018): Displayed Component not be shown by security: +530ms
,D/SensorService( 1018): [SO] Reset Rotation Old [100], Init [1]
,D/WallpaperManagerService( 1018):  force update = false; persona id = 0; current user =0; current persona = 0
D/KnoxTimeoutHandler( 1018): handleHomeShow for 0 and current 0
D/PersonaManagerService( 1018): getPersonasForUser(): returning null!
D/KnoxTimeoutHandler( 1018): handleActiveUserChange for user 0
,I/ApplicationPolicy( 1018): updateDataUsageMap
,I/DIAGMON_AGENT( 4734): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,I/SurfaceFlinger(  258): id=12 Removed Uoast (8/9)
,I/SurfaceFlinger(  258): id=12 Removed Uoast (-2/9)
,I/DIAGMON_AGENT( 4734): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
I/DIAGMON_AGENT( 4734): [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 4734): [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:,
I/DIAGMON_AGENT( 4734): ./extraInfo: "NG700"
I/DIAGMON_AGENT( 4734): [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
D/BluetoothTile( 1180):  onBluetoothPairedDevicesChanged:
D/BluetoothAdapter( 1180): 555820671: getState() :  mService = null. Returning STATE_OFF,
D/BluetoothTile( 1180):  getBluetoothState : 10
,D/BluetoothTile( 1180): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothAdapter( 1180): 555820671: getState() :  mService = null. Returning STATE_OFF
I/SamsungIME( 1838): STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
D/BluetoothAdapter( 1180): 555820671: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1180): 555820671: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1180): 555820671: getState() :  mService = null. Returning STATE_OFF
D/StatusBarManagerService( 1018): setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
D/BluetoothAdapter( 1863): 589355732: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1863): 589355732: getState() :  mService = null. Returning STATE_OFF
D/StatusBarManagerService( 1018): setIconVisibility slot=bluetooth visible=false
,D/PhoneStatusBar( 1180): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,I/GKI_LINUX( 2643): gki_task task_id=1 [BTIF] terminating
I/GKI_LINUX( 2643): GKI_exit_task 1 done
I/GKI_LINUX( 2643): GKI_shutdown(): task [BTIF] terminated
,I/BluetoothServiceJni( 2643): cleanupNative: return from cleanup
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/art     ( 2643): System.exit called, status: 0
I/AndroidRuntime( 2643): VM exiting with result code 0, cleanup skipped.
,D/Tethering( 1018): interfaceRemoved p2p0
E/Tethering( 1018): attempting to remove unknown iface (p2p0), ignoring
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,I/ActivityManager( 1018): Waited long enough for: ServiceRecord{d2e878a u0 com.sec.bcservice/.BroadcastService}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/UsbSettingsManager( 1018): clearDefaults: com.example.hello
I/CrashAnrDetector( 1018): onPackageRemoved : com.example.hello
,D/GpsLocationProvider( 1018): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_3788/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_10031/pid_3770/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_10166/pid_3307/cgroup.procs: No such file or directory
,I/ActivityManager( 1018): Process com.android.bluetooth (pid 2643)(adj 0) has died(131,1135)
,I/ActivityManager( 1018): Waited long enough for: ServiceRecord{28d7f1fb u0 com.android.settings/.wifi.WifiCredService}
,D/ActivityManager( 1018): getContentProviderImpl callerProcessName:com.sec.android.diagmonagent, calleePkgName: com.sec.android.fotaclient
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4771): MountEmulatedStorage()
,E/Zygote  ( 4771): v2
I/libpersona( 4771): KNOX_SDCARD checking this for 10009
I/libpersona( 4771): KNOX_SDCARD not a persona,
,I/SELinux ( 4771): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4771): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4771): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1018): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=4771 uid=10009 gids={50009, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/SensorService( 1018): [SO] currT = 48840074198, prevT = 48390066958, diff = 450007240, [0.192 0.115 10.113]
D/SensorService( 1018): [SO] 0.192 0.115 10.113
D/SensorService( 1018): [SO] [100 -> 255]

```
