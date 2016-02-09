#### Test 58741471ee11130_thali06_HTC-HTC One M8s Logs


```
--------- beginning of main
V/JNIHelp ( 6312): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
W/System  ( 6312): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3dfeaa0b: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6312): Installed default security provider GmsCore_OpenSSL
--------- beginning of system
W/ActivityThread( 6312): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
D/GCM     ( 1961): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
D/AuthorizationBluetoothService( 1961): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/GmsCoreStatsServiceLauncher( 4433): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/WearableService( 5683): callingUid 10024, callindPid: 5683
E/MDM     ( 1815): [125] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
I/HtcModeClient( 3262): handler message = 4011
E/HtcModeClient( 3262): Check connection and retry 11 times.
I/PackageManager(  937):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=4433, uid=10024, userID:0
I/WVCdm   (  405): CdmEngine::OpenSession
I/WVCdm   (  405): Level3 Library Sep 25 2014 17:10:03
W/WVCdm   (  405): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
D/DrmWidevineDash(  405): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x15
D/DrmWidevineDash(  405): Service_Initialize: starts!
D/QSEECOMAPI: (  405): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  405): App is not loaded in QSEE
E/QSEECOMAPI: (  405): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  405): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  405): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  405): App is not loaded in QSEE
D/LocationInitializer( 4433): Restart initialization of location
D/QSEECOMAPI: (  405): Loaded image: APP id = 8
D/DrmWidevineDash(  405): Service_Initialize: ends! returns 0
D/QSAPPSVER(  405): qsapps_get_capabilities: Capability from secure side: 0x0
D/QSAPPSVER(  405): qsapps_get_capabilities: returns 0
D/DrmWidevineDash(  405): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf4528000
E/DrmWidevineDash(  405): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf4528000
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/DrmLibTime(  515): got the req here! ret=0
D/DrmLibTime(  515): command id, time_cmd_id = 770
D/DrmLibTime(  515): time_getutcsec starts!
D/DrmLibTime(  515): QSEE Time Listener: time_getutcsec
D/DrmLibTime(  515): QSEE Time Listener: get_utc_seconds
D/DrmLibTime(  515): QSEE Time Listener: time_get_modem_time
D/DrmLibTime(  515): QSEE Time Listener: Checking if ATS_MODEM is set or not.
E/QC-time-services(  515): Receive Passed == base = 13, unit = 1, operation = 2, result = 0
D/DrmLibTime(  515): QSEE Time Listener: ATS_MODEM is not set. Fallback to Android system time.
D/DrmLibTime(  515): QSEE Time Listener: Retrieved Android system time: 1455023204
D/DrmLibTime(  515): time_getutcsec returns 0, sec = 1455023204; nsec = 0
D/DrmLibTime(  515): time_getutcsec finished! 
D/DrmLibTime(  515): iotcl_continue_command finished! and return 0 
D/DrmLibTime(  515): before calling ioctl to read the next time_cmd
E/QC-time-services(  468): Daemon: Time-services: Waiting to acceptconnection
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  405): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  405): OEMCrypto_APIVersion: starts!
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  405): hlos api version =  9
D/DrmWidevineDash(  405): tz api version =  9
D/DrmWidevineDash(  405): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  405): OEMCrypto_IsKeyboxValid: starts!
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  405): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  405): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  405): OEMCrypto_OpenSession: starts! SID=0xf4852928
D/DrmWidevineDash(  405): OEMCrypto_OpenSession Session ID = 0
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  405): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  405): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  405): OEMCrypto_GetRandom: starts! randomData=0xaba45618, dataLength=8
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  405): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  405): OEMCrypto_LoadDeviceRSAKey: starts! SID=1, wrapped_rsa_key=0xab9b6d38, wrapped_rsa_key_length=1280
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  405): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  405): CdmEngine::QueryKeyControlInfo
W/WVCdm   (  405): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  405): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  405): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  405): OEMCrypto_GetDeviceID: starts! deviceID=0xab9dfbe0, idLength=0xf46526f8
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  405): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  405): OEMCrypto_SupportsUsageTable: starts!
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  405): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  405): OEMCrypto_SupportsUsageTable: wv_app_version = 24
D/DrmWidevineDash(  405): OEMCrypto_SupportsUsageTable: ends! returns 0
D/DrmWidevineDash(  405): OEMCrypto_GetHDCPCapability: starts!, current = 0xf465270e, maximum = 0xf465270f
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  405): OEMCrypto_GetHDCPCapability: ends! returns 0
D/DrmWidevineDash(  405): OEMCrypto_APIVersion: starts!
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  405): hlos api version =  9
D/DrmWidevineDash(  405): tz api version =  9
D/DrmWidevineDash(  405): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  405): OEMCrypto_GenerateNonce: starts! SID=1, nonce=0xf465277c
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  405): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  405): PrepareKeyRequest: nonce=582267197
D/DrmWidevineDash(  405): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xabad7650
D/DrmWidevineDash(  405): message_length=1611, signature=0xaba093c8, signature_length=0xf46526dc
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
E/cutils-trace( 6340): Error opening trace file: Permission denied (13)
E/WifiTrafficPoller(  937): TRAFFIC_STATS_POLL true Token 11 num clients 6
D/WIFI_ICON( 1214): WifiActivity: 1
E/WifiTrafficPoller(  937):  packet count Tx=144 Rx=216
D/StatusBar.NetworkController( 1214): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
E/WifiTrafficPoller(  937): notifying of data activity 1
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  405): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  405): CdmEngine::CloseSession
D/DrmWidevineDash(  405): OEMCrypto_CloseSession: starts! SID=1
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  405): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  405): L3 Terminate.
D/DrmWidevineDash(  405): OEMCrypto_Terminate: starts!
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  405): Service_Uninitialize: starts!
D/QSEECOMAPI: (  405): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  405): QSEECom_shutdown_app, app_id = 8
D/DrmWidevineDash(  405): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  405): OEMCrypto_Terminate: ends! returns 0
D/CustomizationManager( 6340): ====startRecUseTime====
D/htc.customization.log.level( 6340):  is 
W/CustomizationLogLevel( 6340): Level value is invalid, use default level 2
I/WVCdm   (  405): CdmEngine::OpenSession
I/WVCdm   (  405): Level3 Library Sep 25 2014 17:10:03
W/WVCdm   (  405): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
D/DrmWidevineDash(  405): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x15
D/DrmWidevineDash(  405): Service_Initialize: starts!
D/QSEECOMAPI: (  405): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  405): App is not loaded in QSEE
E/QSEECOMAPI: (  405): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  405): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  405): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  405): App is not loaded in QSEE
D/QSEECOMAPI: (  405): Loaded image: APP id = 9
D/DrmWidevineDash(  405): Service_Initialize: ends! returns 0
D/QSAPPSVER(  405): qsapps_get_capabilities: Capability from secure side: 0x0
D/QSAPPSVER(  405): qsapps_get_capabilities: returns 0
D/DrmWidevineDash(  405): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf4528000
E/DrmWidevineDash(  405): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf4528000
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/DrmLibTime(  515): got the req here! ret=0
D/DrmLibTime(  515): command id, time_cmd_id = 770
D/DrmLibTime(  515): time_getutcsec starts!
D/DrmLibTime(  515): QSEE Time Listener: time_getutcsec
D/DrmLibTime(  515): QSEE Time Listener: get_utc_seconds
D/DrmLibTime(  515): QSEE Time Listener: time_get_modem_time
D/DrmLibTime(  515): QSEE Time Listener: Checking if ATS_MODEM is set or not.
E/QC-time-services(  515): Receive Passed == base = 13, unit = 1, operation = 2, result = 0
D/DrmLibTime(  515): QSEE Time Listener: ATS_MODEM is not set. Fallback to Android system time.
D/DrmLibTime(  515): QSEE Time Listener: Retrieved Android system time: 1455023205
D/DrmLibTime(  515): time_getutcsec returns 0, sec = 1455023205; nsec = 0
D/DrmLibTime(  515): time_getutcsec finished! 
D/DrmLibTime(  515): iotcl_continue_command finished! and return 0 
D/DrmLibTime(  515): before calling ioctl to read the next time_cmd
E/QC-time-services(  468): Daemon: Time-services: Waiting to acceptconnection
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  405): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  405): OEMCrypto_APIVersion: starts!
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  405): hlos api version =  9
D/DrmWidevineDash(  405): tz api version =  9
D/DrmWidevineDash(  405): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  405): OEMCrypto_IsKeyboxValid: starts!
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/CustomizationManager( 6340):  Read ACC file spent 0.052 (s)
D/CIDMapFileReader( 6340): Parsing tag item name = HTC__001
D/CIDMapFileReader( 6340): Parsing tag item name = HTC__102
D/CIDMapFileReader( 6340): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 6340): Parsing tag item name = HTC__032
D/CIDMapFileReader( 6340): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 6340): Parsing tag item name = HTC__002
D/CIDMapFileReader( 6340): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 6340): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 6340): Parsing tag category name = system
I/CustomizationCIDLoader( 6340): Parsing tag category name = application
I/CustomizationCIDLoader( 6340): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 6340): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 6340): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 6340): Parsing tag category name = Settings
I/CustomizationCIDLoader( 6340): Parsing tag category name = ACC
I/CustomizationCIDLoader( 6340): add string-array item, value = 42507
I/CustomizationCIDLoader( 6340): add string-array item, value = 21902
I/CustomizationCIDLoader( 6340): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 6340): add string-array item, value = 23420
I/CustomizationCIDLoader( 6340): add string-array item, value = 22299
I/CustomizationCIDLoader( 6340): add string-array item, value = 24002
I/CustomizationCIDLoader( 6340): add string-array item, value = 23210
I/CustomizationCIDLoader( 6340): add string-array item, value = 23205
I/CustomizationCIDLoader( 6340): add string-array item, value = 23806
I/CustomizationCIDLoader( 6340): add string-array item, value = 23430
I/CustomizationCIDLoader( 6340): add string-array item, value = 23408
I/CustomizationCIDLoader( 6340): add string-array item, value = 27205
I/CustomizationCIDLoader( 6340): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 6340): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 6340): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 6340): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 6340): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 6340): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 6340): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 6340): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 6340): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 6340): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 6340): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 6340): add string-array item, value = 27205:C:1:0
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/CustomizationManager( 6340):  Read CID file spent 0.092 (s)
D/DrmWidevineDash(  405): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  405): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  405): OEMCrypto_OpenSession: starts! SID=0xf4852928
D/DrmWidevineDash(  405): OEMCrypto_OpenSession Session ID = 0
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/CustomizationManager( 6340):  All configurations done spent 0.092 (s)
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  405): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  405): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  405): OEMCrypto_GetRandom: starts! randomData=0xaba09408, dataLength=8
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  405): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  405): OEMCrypto_LoadDeviceRSAKey: starts! SID=1, wrapped_rsa_key=0xab9b6d38, wrapped_rsa_key_length=1280
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  405): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  405): CdmEngine::QueryKeyControlInfo
W/WVCdm   (  405): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  405): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  405): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  405): OEMCrypto_GetDeviceID: starts! deviceID=0xab9dfc00, idLength=0xf47526f8
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  405): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  405): OEMCrypto_SupportsUsageTable: starts!
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  405): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  405): OEMCrypto_SupportsUsageTable: wv_app_version = 24
D/DrmWidevineDash(  405): OEMCrypto_SupportsUsageTable: ends! returns 0
D/DrmWidevineDash(  405): OEMCrypto_GetHDCPCapability: starts!, current = 0xf475270e, maximum = 0xf475270f
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  405): OEMCrypto_GetHDCPCapability: ends! returns 0
D/DrmWidevineDash(  405): OEMCrypto_APIVersion: starts!
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  405): hlos api version =  9
D/DrmWidevineDash(  405): tz api version =  9
D/DrmWidevineDash(  405): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  405): OEMCrypto_GenerateNonce: starts! SID=1, nonce=0xf475277c
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  405): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  405): PrepareKeyRequest: nonce=3134478921
D/DrmWidevineDash(  405): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xabad7650
D/DrmWidevineDash(  405): message_length=1646, signature=0xab9b7320, signature_length=0xf47526dc
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
I/ActivityManager(  937): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 pid 6340 on display 0
W/asset   (  937): Copying FileAsset 0x55995bc2c0 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
D/PMS     (  937): acquireHCC(994e00c): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 937 1000 null
D/PMS     (  937): acquireHCC(5ef3d55): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 937 1000 null
D/PMS     (  937): acquireWL(27ab605b): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 937 1000 null
I/FeedHostManager( 1625): [onPause]
I/FeedProviderManager( 1625): onPause
I/FeedHostManager( 1625): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@fb5d643
I/SocialFeedProvider( 1625): +onPause
I/SocialFeedProvider( 1625): -onPause
I/AnimationUtil(  937): isHTCRecent(ThaliTest/Recent screens.)/6
W/HtcSystemUPManager(  937): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
I/ActivityManager(  937): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6366 uid=10366 gids={50366, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/art     (  446): Explicit concurrent mark sweep GC freed 8673(369KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 240us total 18.056ms
I/art     (  446): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 270us total 15.284ms
I/art     (  446): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 396us total 16.948ms
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  405): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  405): CdmEngine::CloseSession
D/DrmWidevineDash(  405): OEMCrypto_CloseSession: starts! SID=1
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
W/asset   ( 6366): Copying FileAsset 0xac760718 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  405): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  405): L3 Terminate.
D/DrmWidevineDash(  405): OEMCrypto_Terminate: starts!
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  405): Service_Uninitialize: starts!
D/QSEECOMAPI: (  405): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  405): QSEECom_shutdown_app, app_id = 9
D/DrmWidevineDash(  405): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  405): OEMCrypto_Terminate: ends! returns 0
D/StatusBarManagerService(  937): setSystemUiVisibility(0x0)
D/StatusBarManagerService(  937): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  937): hiding MENU key
I/TrimMemoryManager( 1625): [trimMemory] 20
E/cutils-trace( 6388): Error opening trace file: Permission denied (13)
I/dex2oat ( 6388): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm64 --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=42 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
I/dex2oat ( 6388): dex2oat: override thread count:4
E/WifiStateMachine(  937): handleMessage: E msg.what=131155
E/WifiStateMachine(  937): processMsg: ConnectedState
E/WifiStateMachine(  937):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:1346] from screen [on:0 period:-970708059] gl hn u24 rssi=-58 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  937): processMsg: L2ConnectedState
E/WifiStateMachine(  937):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-970708057] gl hn u24 rssi=-58 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  937):  get link layer stats 0
W/WifiHW  (  937): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1331): wlan0: Control interface command 'SIGNAL_POLL'
I/wpa_supplicant( 1331): environment dirty rate=0 [0][0][0]
E/WifiStateMachine(  937): fetchRssiLinkSpeedAndFrequencyNative RSSI = -63 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  937): fetchRssiLinkSpeedAndFrequencyNative rssi=-63 linkspeed=72
E/WifiConfigStore(  937): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-63 "NG700"WPA_PSK
E/WifiStateMachine(  937): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=0.26 txretriesrate=0.00 rxrate=1.01 userTriggerdPenalty0
E/WifiStateMachine(  937):  good link -> stuck count =0
E/WifiStateMachine(  937):  badRSSI count0 lowRSSI count0 --> score 56
E/WifiStateMachine(  937):  isHighRSSI       ---> score=61
D/WifiWatchdogStateMachine(  937): RSSI current: 3 new: -63, 3
E/WifiStateMachine(  937): handleMessage: X
D/WIFI_ICON( 1214): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1214): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/WebViewFactory( 6366): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
,I/dex2oat ( 6388): dex2oat took 84.822ms (threads: 4)
,I/Adreno-EGL( 6312): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 6312): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6312): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6312): Local Branch: 
I/Adreno-EGL( 6312): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6312): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6312):                  d74aa161a12b9c6fc6332151
,I/LibraryLoader( 6366): Time to load native libraries: 16 ms (timestamps 6066-6082)
,I/LibraryLoader( 6366): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6366): Binding Chromium to main looper Looper (main, tid 1) {3d753379}
,I/LibraryLoader( 6366): Expected native library version number "",actual native library version number ""
,I/chromium( 6366): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/Adreno-EGL( 6312): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 6312): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6312): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6312): Local Branch: 
I/Adreno-EGL( 6312): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6312): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6312):                  d74aa161a12b9c6fc6332151
,I/BrowserStartupController( 6366): Initializing chromium process, singleProcess=true
,W/art     ( 6366): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6366): ApplicationContext is null in ApplicationStatus
,W/chromium( 6366): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6366): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6366): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6366): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 6366): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6366): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6366): Local Branch: 
I/Adreno-EGL( 6366): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6366): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6366):                  d74aa161a12b9c6fc6332151
,W/System.err(  937): java.lang.Throwable: stack dump
,D/BluetoothManagerService(  937): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  937): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2c038828:true
W/System.err(  937): 	at java.lang.Thread.dumpStack(Thread.java:490)
,W/System.err(  937): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  937): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  937): 	at android.os.Binder.execTransact(Binder.java:454)
,D/BluetoothAdapter( 6366): 42765877: getState(). Returning 12
,I/CheckinRequestBuilder( 4433): Classify the device as Phone.
,W/art     ( 6366): Attempt to remove local handle scope entry from IRT, ignoring
,D/libc    ( 4433): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
D/libc    ( 4433): [NET] android_getaddrinfofornet-, err=8,
D/libc    ( 4433): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
D/libc    ( 4433): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 4433): [NET] android_getaddrinfo_proxy+
D/libc    ( 4433): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  399): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
D/libc    (  399): [NET] _dns_getaddrinfo+, netid:100, mark:917604
D/libc    (  399): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  399): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 4433): [NET] android_getaddrinfo_proxy-, success
,W/AwContents( 6366): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 6366): CordovaWebView is running on device made by: HTC
W/art     ( 6366): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6366): Attempt to remove local handle scope entry from IRT, ignoring
D/libc    ( 4433): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
D/libc    ( 4433): [NET] android_getaddrinfofornet-, err=8
W/chromium( 6366): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
D/libc    ( 4433): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
D/libc    ( 4433): [NET] android_getaddrinfofornet-, err=8
D/FindExtension( 6366): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
D/libc    ( 4433): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
D/libc    ( 4433): [NET] android_getaddrinfofornet-, err=8
I/CheckinTask( 4433): Sending checkin request (8408 bytes)
I/InputMethodManager( 6366): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@ba9927a, mServedView=org.apache.cordova.engine.SystemWebView{2630ba2b VFEDH.C. .F....I. 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@3ba8e88
I/InputMethodManagerService(  937): Disable input method client, pid=1625
D/StatusBarManagerService(  937): swetImeWindowStatus vis=0 backDisposition=0
I/InputMethodManagerService(  937): Enable input method client, pid=6366
E/WifiTrafficPoller(  937): TRAFFIC_STATS_POLL true Token 11 num clients 6
D/WIFI_ICON( 1214): WifiActivity: 3
E/WifiTrafficPoller(  937):  packet count Tx=161 Rx=227
D/StatusBar.NetworkController( 1214): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
E/WifiTrafficPoller(  937): notifying of data activity 3
D/PMS     (  937): releaseWL(27ab605b): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
I/PhoneStatusBar( 1214): setImeWindowStatus(false,false)
I/ActivityManager(  937): Displayed com.test.thalitest/.MainActivity: +848ms
W/BindingManager( 6366): Cannot call determinedVisibility() - never saw a connection for the pid: 6366
W/XT9_C   ( 1402): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1402): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1402): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1402): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
D/JsMessageQueue( 6366): Set native->JS mode to OnlineEventsBridgeMode
I/CheckinRequestBuilder( 4433): Checkin reason type: 11 attempt count: 1
I/ActivityManager(  937): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 4433): Failed to find provider info for com.google.android.wearable.settings
D/jxcore_app_log( 6366): JniHelper::setJavaVM(0xab5f48f8), pthread_self() = -1399722488
I/chromium( 6366): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
I/GLSUser ( 1961): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
I/GLSUser ( 1961): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1961): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1961): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1961): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/CheckinRequestBuilder( 4433): awaiting user notification for token
D/DotMatrix( 1310): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1310): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
I/RemoteViews( 1214): reapply : com.google.android.gms 1 40
,I/CheckinRequestBuilder( 4433): Classify the device as Phone.
I/CheckinTask( 4433): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
I/CheckinService( 4433): Checking schedule, now: 1455023206452 next: 1455560038444
I/PackageManager(  937):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=4433, uid=10024, userID:0
I/CheckinService( 4433): active receiver: disabled
D/PMS     (  937): releaseWL(15423444): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10024 com.google.android.gms}
I/ActivityManager(  937): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=6433 uid=10077 gids={50077, 9997, 3003} abi=arm64-v8a
D/PhoneMonitor( 6433): Register our PhoneStateListener
V/SetupWizard( 6433): Connected to Gservices successfully
D/ChimeraCfgMgr( 4433): Loading module com.google.android.gms.kids from APK com.google.android.gms
I/Kids    ( 4433): [GCoreUtils] Current gmscore version, 7899448 is smaller than the required version 8400000
D/PhoneMonitor( 6433): onServiceStateChanged state="3 3 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1EriInd= -1EriMode= -1RadioPowerSv: false EmergOnly=false PhoneType: 1 VoiceRoaming: false DataRoaming: false IMSRegState: -1" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_POWER_OFF(3) D:STATE_POWER_OFF(3) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
D/PhoneMonitor( 6433): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_POWER_OFF(3) D:STATE_POWER_OFF(3) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
D/GCM     ( 1961): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
E/WifiTrafficPoller(  937): TRAFFIC_STATS_POLL true Token 11 num clients 6
E/WifiTrafficPoller(  937):  packet count Tx=163 Rx=230
D/PMS     (  937): releaseHCC(994e00c): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null
D/PMS     (  937): releaseHCC(5ef3d55): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,W/jxcore-log( 6366): Initializing JXcore engine,
W/jxcore-log( 6366): JXcore engine is ready
,W/jxcore-log( 6366): Starting JXcore engine,
,W/jxcore-log( 6366): Platform android,
W/jxcore-log( 6366): 
W/jxcore-log( 6366): Process ARCH arm
W/jxcore-log( 6366): 
,E/WifiDataStallTracker(  937): DATA_MONITOR_POLL true Token 1,
,D/WifiDataStallTracker(  937): updateDataStallInfo: mDataStallTxRxSum={txSum=145 rxSum=120} preTxRxSum={txSum=126 rxSum=106}
D/WifiDataStallTracker(  937): updateDataStallInfo: IN/OUT,
D/WifiDataStallTracker(  937): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,I/jxcore-log( 6366): JXcore Cordova bridge is ready!,
I/jxcore-log( 6366): 
W/jxcore-log( 6366): JXcore engine is started
,E/jxcore  ( 6366): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js,
E/jxcore  ( 6366): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 6366): [INFO:CONSOLE(37)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (37),
,E/WifiTrafficPoller(  937): TRAFFIC_STATS_POLL true Token 11 num clients 6
,E/WifiTrafficPoller(  937):  packet count Tx=163 Rx=230
,E/WifiTrafficPoller(  937): notifying of data activity 0
D/WIFI_ICON( 1214): WifiActivity: 0
D/StatusBar.NetworkController( 1214): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,W/PluginManager( 6366): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 61ms. Plugin should use CordovaInterface.getThreadPool().
D/PMS     (  937): acquireWL(14b242d2): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 937 1000 null
W/HtcSystemUPManager(  937): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
,I/FeedHostManager( 1625): [onResume],
I/FeedProviderManager( 1625): onResume
I/SocialFeedProvider( 1625): +onResume
I/SocialFeedProvider( 1625): updateAccounts - Accounts is no change
I/SocialFeedProvider( 1625): -onResume
,D/StatusBarManagerService(  937): setSystemUiVisibility(0x700),
D/StatusBarManagerService(  937): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  937): hiding MENU key
D/FindExtension( 1625): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
,I/ThreadedRenderer( 1625): Defer allocateBuffers to drawing time
,I/InputMethodManagerService(  937): Disable input method client, pid=6366
D/StatusBarManagerService(  937): swetImeWindowStatus vis=0 backDisposition=0
I/InputMethodManagerService(  937): Enable input method client, pid=1625
I/PhoneStatusBar( 1214): setImeWindowStatus(false,false)
W/IInputConnectionWrapper( 6366): reportFullscreenMode on inactive InputConnection
,D/PMS     (  937): releaseWL(14b242d2): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/StatusBarManagerService(  937): setSystemUiVisibility(0xc0000700)
D/StatusBarManagerService(  937): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  937): hiding MENU key
,E/WifiStateMachine(  937): handleMessage: E msg.what=131155,
E/WifiStateMachine(  937): processMsg: ConnectedState
,E/WifiStateMachine(  937):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-970705037] gl hn u24 rssi=-58 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  937): processMsg: L2ConnectedState
E/WifiStateMachine(  937):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-970705035] gl hn u24 rssi=-58 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  937):  get link layer stats 0
,W/WifiHW  (  937): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1331): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1331): environment dirty rate=10 [19][2][0],
E/WifiStateMachine(  937): fetchRssiLinkSpeedAndFrequencyNative RSSI = -63 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  937): fetchRssiLinkSpeedAndFrequencyNative rssi=-63 linkspeed=72
E/WifiConfigStore(  937): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-63 "NG700"WPA_PSK
,E/WifiStateMachine(  937): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=9.63 txretriesrate=0.00 rxrate=7.50 userTriggerdPenalty0
E/WifiStateMachine(  937):  good link -> stuck count =0
,D/WIFI_ICON( 1214): updateWifiState: RSSI_CHANGED 3 -> 3
E/WifiStateMachine(  937):  badRSSI count0 lowRSSI count0 --> score 60
D/StatusBar.NetworkController( 1214): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/WifiStateMachine(  937):  isHighRSSI       ---> score=65
D/WifiWatchdogStateMachine(  937): RSSI current: 3 new: -63, 3
E/WifiStateMachine(  937): handleMessage: X
,W/OpenGLRenderer( 1625): Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...,
,E/WifiTrafficPoller(  937): TRAFFIC_STATS_POLL true Token 11 num clients 6,
E/WifiTrafficPoller(  937):  packet count Tx=163 Rx=230
,W/ContextImpl(  937): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 
,D/Process (  937): killProcessQuiet, pid=5498
I/ActivityManager(  937): Killing 5498:com.google.android.music:main/u0a159 (adj 15): empty #17
D/Process (  937): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/HtcModeClient( 3262): handler message = 4011,
E/HtcModeClient( 3262): Check connection and retry 12 times.
,I/ActivityManager(  937): Recipient 5498
,D/MediaRouterService(  937): Client com.google.android.music (pid 5498): Died!
,D/Process (  937): killProcessQuiet, pid=5775
I/ActivityManager(  937): Killing 5775:com.google.android.talk/u0a112 (adj 15): empty #17
D/Process (  937): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  937): Recipient 5775
,D/Process (  937): killProcessQuiet, pid=5808
I/ActivityManager(  937): Killing 5808:com.google.android.gm/u0a106 (adj 15): empty #18
D/Process (  937): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,E/WifiTrafficPoller(  937): TRAFFIC_STATS_POLL true Token 11 num clients 6,
E/WifiTrafficPoller(  937):  packet count Tx=165 Rx=231
E/WifiTrafficPoller(  937): notifying of data activity 3
,D/WIFI_ICON( 1214): WifiActivity: 3
D/StatusBar.NetworkController( 1214): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,I/ActivityManager(  937): Recipient 5808
,E/WifiTrafficPoller(  937): TRAFFIC_STATS_POLL true Token 11 num clients 6,
D/WIFI_ICON( 1214): WifiActivity: 1
E/WifiTrafficPoller(  937):  packet count Tx=165 Rx=232
D/StatusBar.NetworkController( 1214): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
E/WifiTrafficPoller(  937): notifying of data activity 1,
,E/WifiStateMachine(  937): handleMessage: E msg.what=131155,
E/WifiStateMachine(  937): processMsg: ConnectedState
E/WifiStateMachine(  937):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=9.6, 0.0, 0.0  rx=7.5 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-970702015] gl hn u24 rssi=-58 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  937): processMsg: L2ConnectedState
E/WifiStateMachine(  937):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=9.6, 0.0, 0.0  rx=7.5 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-970702014] gl hn u24 rssi=-58 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  937):  get link layer stats 0
W/WifiHW  (  937): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1331): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1331): environment dirty rate=0 [2][0][0]
D/WIFI_ICON( 1214): updateWifiState: RSSI_CHANGED 3 -> 3
,E/WifiStateMachine(  937): fetchRssiLinkSpeedAndFrequencyNative RSSI = -63 abnormalRssiCnt = 0 newLinkSpeed = 72
D/StatusBar.NetworkController( 1214): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
E/WifiStateMachine(  937): fetchRssiLinkSpeedAndFrequencyNative rssi=-63 linkspeed=72
E/WifiConfigStore(  937): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-63 "NG700"WPA_PSK
E/WifiStateMachine(  937): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=5.81 txretriesrate=0.00 rxrate=4.75 userTriggerdPenalty0
E/WifiStateMachine(  937):  good link -> stuck count =0
E/WifiStateMachine(  937):  badRSSI count0 lowRSSI count0 --> score 60,
E/WifiStateMachine(  937):  isHighRSSI       ---> score=65
E/WifiStateMachine(  937): handleMessage: X
D/WifiWatchdogStateMachine(  937): RSSI current: 3 new: -63, 3
,E/WifiTrafficPoller(  937): TRAFFIC_STATS_POLL true Token 11 num clients 6,
D/WIFI_ICON( 1214): WifiActivity: 0
E/WifiTrafficPoller(  937):  packet count Tx=165 Rx=232
D/StatusBar.NetworkController( 1214): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/WifiTrafficPoller(  937): notifying of data activity 0,
,E/WifiDataStallTracker(  937): DATA_MONITOR_POLL true Token 1,
D/WifiDataStallTracker(  937): updateDataStallInfo: mDataStallTxRxSum={txSum=147 rxSum=121} preTxRxSum={txSum=145 rxSum=120}
D/WifiDataStallTracker(  937): updateDataStallInfo: IN/OUT
D/WifiDataStallTracker(  937): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,E/WifiTrafficPoller(  937): TRAFFIC_STATS_POLL true Token 11 num clients 6,
E/WifiTrafficPoller(  937):  packet count Tx=165 Rx=232
,E/WifiTrafficPoller(  937): TRAFFIC_STATS_POLL true Token 11 num clients 6
D/WIFI_ICON( 1214): WifiActivity: 1
E/WifiTrafficPoller(  937):  packet count Tx=165 Rx=233
E/WifiTrafficPoller(  937): notifying of data activity 1
D/StatusBar.NetworkController( 1214): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/Prism.ItemManager( 1625): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1625): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,W/Prism.AllAppsManager( 1625): AllAppsMgr addApps, already exist: ApplicationInfo(id=33, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
D/AccTypeManager( 1748): Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
,W/SystemReader(  937): Cannot find grip_rejection_width, use default value instead,
,I/ActivityManager(  937): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=6461 uid=10112 gids={50112, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
D/AccTypeManager( 1748): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,W/ResourcesManager(  937): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/AccTypeManager( 1748): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,D/PhoneApp( 1560): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,E/ExternalAccountType( 1748): Unsupported attribute readOnly,
,W/ResourcesManager( 6461): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.,
,W/PackageManager(  937): Unable to load service info ResolveInfo{345a1018 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000},
W/PackageManager(  937): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  937): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:475)
W/PackageManager(  937): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:331)
W/PackageManager(  937): 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
W/PackageManager(  937): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  937): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
W/PackageManager(  937): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
W/PackageManager(  937): 	at android.os.Handler.handleCallback(Handler.java:739)
W/PackageManager(  937): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  937): 	at android.os.Looper.loop(Looper.java:155)
W/PackageManager(  937): 	at com.android.server.SystemServer.run(SystemServer.java:324)
W/PackageManager(  937): 	at com.android.server.SystemServer.main(SystemServer.java:225)
W/PackageManager(  937): 	at java.lang.reflect.Method.invoke(Native Method)
W/PackageManager(  937): 	at java.lang.reflect.Method.invoke(Method.java:372),
W/PackageManager(  937): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
W/PackageManager(  937): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,V/GmsNetworkLocationProvi( 1815): DISABLE
,I/GCoreNlp( 1815): shouldConfirmNlp, NLP off. Ensuring opt-in disabled,
I/BackupManagerService(  937): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,D/PMS     (  937): acquireWL(14bb6f23): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1815 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  937): releaseWL(14bb6f23): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,D/LocationProviderProxy(  937): applying state to connected service
,D/LocationProviderProxy(  937): applying state to connected service
,D/PMS     (  937): acquireWL(278836e4): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1815 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  937): releaseWL(278836e4): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  937): acquireWL(2e11074d): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1815 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  937): releaseWL(2e11074d): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms},
,I/Babel_SMS( 6461): MmsConfig: mnc/mcc: 0/0,
I/Babel_SMS( 6461): MmsConfig.loadMmsSettings
,I/ActivityManager(  937): Start proc com.htc.sense.mms for content provider com.htc.sense.mms/.util.MmsCustomizationProvider: pid=6491 uid=10064 gids={50064, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a,
,I/PackageManager(  937):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=6461, uid=10112, userID:0,
,W/HtcWrapAdjustableCursorFactory( 6491): HtcWrapAdjustableCursorFactory is deprecated. Use HtcWrapSQLite in HDK Lib3 instead.
,E/WifiStateMachine(  937): handleMessage: E msg.what=131155
E/WifiStateMachine(  937): processMsg: ConnectedState
E/WifiStateMachine(  937):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=5.8, 0.0, 0.0  rx=4.8 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-970698986] gl hn u24 rssi=-58 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  937): processMsg: L2ConnectedState
D/MessageFrequencyProvider( 6491): onCreate
E/WifiStateMachine(  937):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=5.8, 0.0, 0.0  rx=4.8 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-970698985] gl hn u24 rssi=-58 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  937):  get link layer stats 0
W/WifiHW  (  937): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1331): wlan0: Control interface command 'SIGNAL_POLL'
,D/MmsCustomizationProvider( 6491): query uri: content://htc-mms-customization/mms-ua/ua_string
,V/GetPrviateResource( 6491): GetPrviateResource
,V/GetPrviateResource( 6491): GetPrviateResource
,I/wpa_supplicant( 1331): environment dirty rate=0 [0][0][0]
,D/MessageCustFlag( 6491): sense_version=6.0
,E/WifiStateMachine(  937): fetchRssiLinkSpeedAndFrequencyNative RSSI = -63 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WIFI_ICON( 1214): updateWifiState: RSSI_CHANGED 3 -> 3
E/WifiStateMachine(  937): fetchRssiLinkSpeedAndFrequencyNative rssi=-63 linkspeed=72
D/StatusBar.NetworkController( 1214): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
E/WifiConfigStore(  937): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-63 "NG700"WPA_PSK
D/BTAccessoryUtil( 6491): createReceiver
E/WifiStateMachine(  937): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=2.91 txretriesrate=0.00 rxrate=2.88 userTriggerdPenalty0
E/WifiStateMachine(  937):  good link -> stuck count =0
E/WifiStateMachine(  937):  badRSSI count0 lowRSSI count0 --> score 56
E/WifiStateMachine(  937):  isHighRSSI       ---> score=61
D/WifiWatchdogStateMachine(  937): RSSI current: 3 new: -63, 3
E/WifiStateMachine(  937): handleMessage: X
,D/MmsCustomizationProvider( 6491): query uri: content://htc-mms-customization/mms-ua/ua_profile
,I/Babel_SMS( 6461): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_One_M8s/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/PPzlrbleWf/ua-profile.xml
,I/Babel_SMS( 6461): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6461): canonicalizeMccMnc: invalid mccmnc ,
I/Babel_SMS( 6461): MmsConfig.loadFromResources
,E/Babel_SMS( 6461): canonicalizeMccMnc: invalid mccmnc nullnull,
I/Babel_SMS( 6461): MmsConfig.loadMmsSettings: mUserAgent=HTC_One_M8s/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/PPzlrbleWf/ua-profile.xml
,I/art     (  937): Explicit concurrent mark sweep GC freed 30354(1665KB) AllocSpace objects, 5(228KB) LOS objects, 33% free, 18MB/28MB, paused 1.515ms total 146.491ms
,W/Settings( 6461): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/BTAccessoryUtil( 6491): registerReceiver return intent = null
,D/MessageCustFlag( 6491): sku_id=118
,D/HtcBuildUtils( 6491): getRATByHtcTelephonyCapability:1
,I/Babel_Crash( 6461): startup - clean
W/SystemReader( 6491): Cannot find qct_8960_interface, use default value instead,
,I/Babel   ( 6461): deleted: false for 0
,I/PackageManager(  937):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.SmsReceiver, state=2, flag=1, pid=6461, uid=10112, userID:0
,I/PackageManager(  937):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.MmsWapPushReceiver, state=2, flag=1, pid=6461, uid=10112, userID:0
,I/PackageManager(  937):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.AbortSmsReceiver, state=2, flag=1, pid=6461, uid=10112, userID:0
,I/PackageManager(  937):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=6461, uid=10112, userID:0
,I/PackageManager(  937):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.service.NoConfirmationSmsSendService, state=1, flag=1, pid=6461, uid=10112, userID:0
,D/PMS     (  937): acquireWL(2bf30f67): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 6461 10112 null
,W/VideoCapabilities( 6461): Unrecognized profile 2130706433 for video/avc,
,I/[PluginManager]RegisterService( 1543): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
,I/[PluginManager]RegisterService( 1543): handle notify Blinkfeed plugin client changed
,D/PackageBroadcastService( 4433): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms,
,I/PackageBroadcastService( 4433): Null package name or gms related package.  Ignoreing.
,D/PMS     (  937): acquireWL(35be14fe): PARTIAL_WAKE_LOCK  AsyncService 0x1 6052 10167 null,
,D/PMS     (  937): acquireWL(6c8845f): PARTIAL_WAKE_LOCK  Icing 0x1 4433 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  937): releaseWL(35be14fe): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
D/PMS     (  937): acquireWL(3dd98775): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 6052 10167 null
,I/Icing   ( 4433): updateResources: need to parse f{com.google.android.gms}
,D/PMS     (  937): releaseWL(3dd98775): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 null
,I/UpdateIcingCorporaServi( 5889): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,W/VideoCapabilities( 6461): Unsupported mime video/x-ms-wmv
,W/Utils   ( 6461): could not parse size range '64x64-1920X1080',
D/PMS     (  937): releaseWL(6c8845f): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms}
,W/AudioCapabilities( 6461): Unsupported mime audio/qcelp
,W/AudioCapabilities( 6461): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 6461): Unsupported mime audio/qcelp
,W/VideoCapabilities( 6461): Unsupported mime video/x-ms-wmv,
,I/UpdateIcingCorporaServi( 5889): UpdateCorporaTask done [took 50 ms] updated apps [took 50 ms] 
,I/VideoCapabilities( 6461): Unsupported profile 4 for video/mp4v-es,
,W/VideoCapabilities( 6461): Unrecognized profile 2130706433 for video/avc,
,W/VideoCapabilities( 6461): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6461): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6461): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 6461): onServiceConnected
,W/Babel   ( 6461): Attempted to change video mute state without an active call.
,D/PMS     (  937): releaseWL(2bf30f67): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,W/ResourcesManager( 6461): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
W/ResourcesManager( 6461): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6461): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/HtcModeClient( 3262): handler message = 4011,
,E/HtcModeClient( 3262): Check connection and retry 12 times. Stop service and kill this process.,
D/HtcModeClient( 3262): Don't start project servcice
,D/HtcModeClient( 3262): setEject: MEDIA_EJECT_STATE = true
D/HtcModeClient( 3262): connectState: CONNECTION_READY = false
D/SilentMusic( 3262): call stop
D/HtcModeClient( 3262): close connection
W/HtcModeClient( 3262): leaveProjectMode: It does not enter ProjectMode
W/CANMesgAgentLocalSocket( 3262): read the terminate packet, so break
,D/Process (  937): killProcessQuiet, pid=3262
I/ActivityManager(  937): Killing 3262:com.htc.autobot/u0a47 (adj 15): empty #17
D/Process (  937): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,W/System  ( 6461): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6461): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  937): Recipient 3262
,E/WifiTrafficPoller(  937): TRAFFIC_STATS_POLL true Token 11 num clients 6
,E/WifiTrafficPoller(  937):  packet count Tx=165 Rx=233
,E/WifiTrafficPoller(  937): notifying of data activity 0
D/WIFI_ICON( 1214): WifiActivity: 0
D/StatusBar.NetworkController( 1214): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/Prism.ItemManager( 1625): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true,
I/Prism.ItemManager( 1625): loadItems() com.htc.launcher.pageview.WidgetManager@442be3c +
I/Prism.WidgetManager( 1625): onLoadItems() +
,E/Prism.WidgetManager( 1625): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1625): onLoadItems() -
I/Prism.ItemManager( 1625): loadItems() com.htc.launcher.pageview.WidgetManager@442be3c -
,E/WifiTrafficPoller(  937): TRAFFIC_STATS_POLL true Token 11 num clients 6
,E/WifiTrafficPoller(  937):  packet count Tx=165 Rx=233
,D/PhoneApp( 1560): EVENT_QUERY_MO_PACKAGES,
D/PhoneApp( 1560): -- N1 =0
,D/PhoneApp( 1560): -- N2 =0,
,D/PhoneApp( 1560): -- N3 =0
,D/Messaging( 6491): supportCMAS(SIE)/init? false/true,
D/MmsConfig( 6491): networkCode: 
D/MessageCustFlag( 6491): sku_id=118
,D/MmsConfig( 6491): SIE smsPri: null
D/MmsConfig( 6491): networkCode: 
D/MmsConfig( 6491): packageName: com.htc.vvm.att does not exist
,D/Messaging( 6491): mNeedToUpdateDate2 start,
D/ReportIndicatorCache( 6491): startAsyncQueryReports ---
D/MmsAsyncWorkHandler( 6491): 
D/MmsAsyncWorkHandler( 6491): HM tk = 20001
D/ReportIndicatorCache( 6491): MSG_QUERY_REPORTS >>
D/SettingsManager( 6491): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@292bf8be
,D/DraftCache( 6491): [DraftCache/1] DraftCache.constructor
D/DraftCache( 6491): [DraftCache/1] refresh
D/TelephUtils( 1560): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 55
D/MmsSmsV2Provider( 1560):  slotId = -1000
D/MmsSmsV2Provider( 1560): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null,
,D/TelephUtils( 1560): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 54
D/AccFlag ( 1560): sku_id=118
I/Messaging( 6491): mccmnc> 
D/MmsConfig( 6491): networkCode: 
,D/TelephUtils( 1560): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 96
D/MmsSmsV2Provider( 1560):  slotId = -1000
D/MmsSmsV2Provider( 1560): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
,D/DraftCache( 6491): [DraftCache/161] rebuildCache
,D/Messaging( 6491): ViewCache CreatePreloadOnlyConversationList
,D/TelephUtils( 1560): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 99
,D/MmsSmsV2Provider( 1560):  slotId = -1000
D/MmsSmsV2Provider( 1560): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
,D/TelephUtils( 1560): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 54
D/MmsSmsV2Provider( 1560):  slotId = -1000
D/MmsSmsV2Provider( 1560): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
D/Messaging( 6491): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true,
,D/Messaging( 6491): mNeedToUpdateDate2: false
,D/PhoneStorageUtil( 6491): HtcWrapEnvironment.getSupportedStorages() >1,
D/PhoneStorageUtil( 6491): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
D/PhoneStorageUtil( 6491): createReceiver
,D/TelephUtils( 1560): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 98,
,D/Jerry   ( 1560): URI_DRAFT
,D/TelephUtils( 1560): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 99
V/MmsProvider( 1560): Update uri=content://mms, match=0
V/MmsProvider( 1560): selection=st=129 AND m_type!=134
D/DraftCache( 6491): hasDraft() = false mNeedNotifyChange = true
D/DraftCache( 6491): [DraftCache/161] rebuildCache time: 12
D/MmsAsyncWorkHandler( 6491): 
D/MmsAsyncWorkHandler( 6491): HM tk = 20002
,D/Messaging( 6491): Reset downloading state: 0,
V/MmsSystemEventReceiver( 6491): TransactionService is going to be woken up.
,D/MessageCustFlag( 6491): sense_version=6.0
D/Jerry   ( 6491): start to preload cursor >>>>>>>
D/TelephUtils( 1560): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 54
D/AccFlag ( 1560): sku_id=118
,V/TransactionService( 6491): 1-Creating TransactionService,
,D/TelephUtils( 1560): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 96
D/MmsSmsV2Provider( 1560):  slotId = -1000
,D/TelephUtils( 1560): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 55
D/AccFlag ( 1560): sku_id=118
,D/Messaging( 6491): ViewCache CreatePreload
D/Messaging( 6491): ViewCache CreatePreloadOnlyMultipleOpsList
,V/TransactionService( 6491): onStartCommand: 1,
D/MmsSystemEventReceiver( 6491): unRegisterForConnectionStateChanges
V/TransactionService( 6491): 4-Handling incoming message: { when=0 what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
V/TransactionService( 6491): Loading previous transactions.
,D/TelephUtils( 1560): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 98
D/AccFlag ( 1560): device_type: 1
,D/TransactionService( 6491): Force clearing mTransactionList,
,D/TransactionService( 6491): Force set service start id to 1
V/TransactionService( 6491): stopSelfIfIdle: unRegisterForConnectionStateChanges,
D/MmsSystemEventReceiver( 6491): unRegisterForConnectionStateChanges
D/TransactionService( 6491): stopSelfResult: true, mLastHandledServiceId: 1
V/TransactionService( 6491): Destroying TransactionService,
V/TransactionService( 6491): 4-Handling incoming message: { when=-2ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,D/Cust_MMSMS( 6491): _has_set_default_values_2=true
,D/MsgPreferenceUtils( 6491): def_index: 0
,D/MsgPreferenceUtils( 6491): globalIndex = 1
,D/MsgPreferenceUtils( 6491): phone state: true
,D/MsgPreferenceUtils( 6491): sd state: false
D/MsgPreferenceUtils( 6491): vIndex = 0
,I/ActivityManager(  937): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=6555 uid=10076 gids={50076, 9997} abi=arm64-v8a,
D/PMS     (  937): acquireWL(264b70d1): PARTIAL_WAKE_LOCK  *alarm* 0x1 937 1000 WorkSource{10076}
V/AlarmManager(  937): sending alarm PendingIntent{1d24e736: PendingIntentRecord{30ed1637 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1455023216726, Int=60000
D/PMS     (  937): releaseWL(264b70d1): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10076}
,D/SMSBackup( 6555): SMSBackupAgentService started,
D/SMSBackup( 6555): Checking restore status
,D/SMSBackup( 6555): Restore complete
,D/SMSBackup( 6555): cancelCheckAlarm
,D/SMSBackup( 6555): SMSBackupAgentService completed: completed in 0.0 seconds,
,I/ActivityManager(  937): Killing 5924:com.google.android.partnersetup/u0a27 (adj 15): empty #17
D/Process (  937): killProcessQuiet, pid=5924
,D/Process (  937): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  937): Recipient 5924
,E/WifiTrafficPoller(  937): TRAFFIC_STATS_POLL true Token 11 num clients 6
E/WifiTrafficPoller(  937):  packet count Tx=165 Rx=234
E/WifiTrafficPoller(  937): notifying of data activity 1
D/WIFI_ICON( 1214): WifiActivity: 1
,D/StatusBar.NetworkController( 1214): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,E/WifiStateMachine(  937): handleMessage: E msg.what=131155,
E/WifiStateMachine(  937): processMsg: ConnectedState
E/WifiStateMachine(  937):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=2.9, 0.0, 0.0  rx=2.9 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-970695960] gl hn u24 rssi=-58 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  937): processMsg: L2ConnectedState
,E/WifiStateMachine(  937):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=2.9, 0.0, 0.0  rx=2.9 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-970695958] gl hn u24 rssi=-58 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  937):  get link layer stats 0
W/WifiHW  (  937): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1331): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1331): environment dirty rate=0 [0][0][0]
E/WifiStateMachine(  937): fetchRssiLinkSpeedAndFrequencyNative RSSI = -63 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  937): fetchRssiLinkSpeedAndFrequencyNative rssi=-63 linkspeed=72
E/WifiConfigStore(  937): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-63 "NG700"WPA_PSK
,E/WifiStateMachine(  937): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=1.45 txretriesrate=0.00 rxrate=1.94 userTriggerdPenalty0,
D/WIFI_ICON( 1214): updateWifiState: RSSI_CHANGED 3 -> 3
E/WifiStateMachine(  937):  good link -> stuck count =0
D/StatusBar.NetworkController( 1214): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
E/WifiStateMachine(  937):  badRSSI count0 lowRSSI count0 --> score 56
E/WifiStateMachine(  937):  isHighRSSI       ---> score=61
E/WifiStateMachine(  937): handleMessage: X
D/WifiWatchdogStateMachine(  937): RSSI current: 3 new: -63, 3
,E/WifiDataStallTracker(  937): DATA_MONITOR_POLL true Token 1,
,D/WifiDataStallTracker(  937): updateDataStallInfo: mDataStallTxRxSum={txSum=147 rxSum=121} preTxRxSum={txSum=147 rxSum=121}
D/WifiDataStallTracker(  937): updateDataStallInfo: NONE
D/WifiDataStallTracker(  937): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5,
,E/WifiStateMachine(  937): WiFiStateMachine SCAN ALARM
D/PMS     (  937): acquireWL(145490d): PARTIAL_WAKE_LOCK  *alarm* 0x1 937 1000 WorkSource{1000}
E/WifiStateMachine(  937): handleMessage: E msg.what=131143
D/WifiDisplayAdapter(  937): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  937):     Client/Owner: Client
D/WifiDisplayAdapter(  937):     GroupId: 
D/WifiDisplayAdapter(  937):     Passphrase: 
D/WifiDisplayAdapter(  937):     SessionId: 0
D/WifiDisplayAdapter(  937):     IP Address: }
E/WifiStateMachine(  937): processMsg: ConnectedState
V/AlarmManager(  937): sending alarm PendingIntent{2320a617: PendingIntentRecord{344bea04 android broadcastIntent}}, i=com.android.server.WifiManager.action.START_SCAN, t=1, cnt=1, w=1455023217801, Int=20000
E/WifiStateMachine(  937):  ConnectedState !CMD_START_SCAN -2 -2 ic=5 proc(ms):1 dur:59 rssi=-63 f=2412 sc=60 link=72 tx=1.5, 0.0, 0.0  rx=1.9 list=2412 [on:0 tx:0 rx:0 period:401] from screen [on:0 period:-970695540]
D/PMS     (  937): releaseWL(145490d): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
E/WifiStateMachine(  937): processMsg: L2ConnectedState
E/WifiStateMachine(  937):  L2ConnectedState !CMD_START_SCAN -2 -2 ic=5 proc(ms):2 dur:59 rssi=-63 f=2412 sc=60 link=72 tx=1.5, 0.0, 0.0  rx=1.9 list=2412 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-970695539]
,E/WifiStateMachine(  937): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=1.45 rxSuccessRate=1.94 targetRoamBSSID=c0:ff:d4:d3:aa:48 RSSI=-63
E/WifiStateMachine(  937): WifiStateMachine CMD_START_SCAN with age=71442 interval=60000 maxinterval=300000
E/WifiStateMachine(  937): WifiStateMachine CMD_START_SCAN try full band scan age=71442 interval=60000 maxinterval=300000
E/WifiStateMachine(  937): WifiStateMachine CMD_START_SCAN full=true
E/WifiStateMachine(  937): WifiStateMachine CMD_START_SCAN bump interval =90000
W/WifiHW  (  937): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN TYPE=ONLY"
D/wpa_supplicant( 1331): wlan0: Control interface command 'SCAN TYPE=ONLY'
D/wpa_supplicant( 1331): wlan0: Setting scan request: 0.000000 sec
I/wpa_supplicant( 1331): wpa_supplicant_scan enter
D/wpa_supplicant( 1331): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 1331): WPS: Building WPS IE for Probe Request
,D/wpa_supplicant( 1331): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 1331): WPS:  * Request Type
D/wpa_supplicant( 1331): WPS:  * Config Methods (4288)
D/wpa_supplicant( 1331): WPS:  * UUID-E
D/wpa_supplicant( 1331): WPS:  * Primary Device Type
D/wpa_supplicant( 1331): WPS:  * RF Bands (3)
D/wpa_supplicant( 1331): WPS:  * Association State
D/wpa_supplicant( 1331): WPS:  * Configuration Error (0)
D/wpa_supplicant( 1331): WPS:  * Device Password ID (0)
,D/wpa_supplicant( 1331): WPS:  * Manufacturer
D/wpa_supplicant( 1331): WPS:  * Model Name
D/wpa_supplicant( 1331): WPS:  * Model Number
D/wpa_supplicant( 1331): WPS:  * Device Name
D/wpa_supplicant( 1331): WPS:  * Version2 (0x20)
D/wpa_supplicant( 1331): P2P: * P2P IE header
D/wpa_supplicant( 1331): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 1331): P2P: * Listen Channel: Regulatory Class 81 Channel 6
,D/wpa_supplicant( 1331): wlan0: Add radio work 'scan'@0x557c34a680
D/wpa_supplicant( 1331): wlan0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1331): wlan0: Starting radio work 'scan'@0x557c34a680 after 0.000041 second wait
D/wpa_supplicant( 1331): wlan0: nl80211: scan request
D/wpa_supplicant( 1331): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 1331): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 1331): wlan0: nl80211: Scan trigger
D/wpa_supplicant( 1331): wlan0: Event SCAN_STARTED (49) received
D/wpa_supplicant( 1331): wlan0: Own scan request started a scan in 0.000130 seconds
I/wpa_supplicant( 1331): wlan0: CTRL-EVENT-SCAN-STARTED 
,E/WifiStateMachine(  937): [1,455,023,217,807 ms] noteScanstart no scan source
E/WifiStateMachine(  937): handleMessage: X
D/WifiMonitor(  937): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor(  937): WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  937): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  937): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,E/WifiTrafficPoller(  937): TRAFFIC_STATS_POLL true Token 11 num clients 6
E/WifiTrafficPoller(  937):  packet count Tx=165 Rx=234
D/WIFI_ICON( 1214): WifiActivity: 0
E/WifiTrafficPoller(  937): notifying of data activity 0
D/StatusBar.NetworkController( 1214): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,E/WifiTrafficPoller(  937): TRAFFIC_STATS_POLL true Token 11 num clients 6,
,E/WifiTrafficPoller(  937):  packet count Tx=165 Rx=234
,D/Process (  937): killProcessQuiet, pid=6204
I/ActivityManager(  937): Killing 6204:com.htc.cs.dm/u0a99 (adj 15): empty #17
D/Process (  937): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  937): Recipient 6204,
,D/wpa_supplicant( 1331): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
W/ContextImpl(  937): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:14146 com.android.server.wifi.WifiStateMachine.handleMediaLinkEvent:14311 com.android.server.wifi.WifiStateMachine.access$6000:268 com.android.server.wifi.WifiStateMachine$SupplicantStartedState.processMessage:8091 
D/wpa_supplicant( 1331): wlan0: nl80211: New scan results available
D/wpa_supplicant( 1331): nl80211: Scan included frequencies: 2412 2417 2422 2427 2432 2437 2442 2447 2452 2457 2462 2467 2472 5180 5200 5220 5240 5260 5280 5300 5320 5500 5520 5540 5560 5580 5600 5620 5640 5660 5680 5700
D/wpa_supplicant( 1331): wlan0: Event SCAN_RESULTS (3) received
I/wpa_supplicant( 1331): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1331): wlan0: Scan completed in 2.067756 seconds
D/wpa_supplicant( 1331): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1331): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1331): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1331): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
I/wpa_supplicant( 1331): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-54
I/wpa_supplicant( 1331): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-63
I/wpa_supplicant( 1331): [NULL] a0:c5:62:7a:49:97 freq=5260 level=-83
I/wpa_supplicant( 1331): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-82
D/wpa_supplicant( 1331): wlan0: BSS: Start scan result update 6
D/wpa_supplicant( 1331): wlan0: BSS: Add new id 3 BSSID 38:f8:89:11:e9:11 SSID 'Gonzos'
D/wpa_supplicant( 1331): BSS: last_scan_res_used=4/32
D/wpa_supplicant( 1331): wlan0: Scan-only results received
D/wpa_supplicant( 1331): wlan0: Radio work 'scan'@0x557c34a680 done in 2.068979 seconds,
D/WifiMonitor(  937): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 3 38:f8:89:11:e9:11]
E/WifiMonitor(  937): WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor(  937): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
E/WifiStateMachine(  937): handleMessage: E msg.what=147461
E/WifiStateMachine(  937): processMsg: ConnectedState
E/WifiStateMachine(  937):  ConnectedState !SCAN_RESULTS_EVENT 0 0 found=3 known=1 got=3 bcn=0
E/WifiStateMachine(  937): processMsg: L2ConnectedState
E/WifiStateMachine(  937):  L2ConnectedState !SCAN_RESULTS_EVENT 0 0 found=3 known=1 got=3 bcn=0
E/WifiStateMachine(  937): processMsg: ConnectModeState
E/WifiStateMachine(  937):  ConnectModeState !SCAN_RESULTS_EVENT 0 0 found=3 known=1 got=3 bcn=0
E/WifiStateMachine(  937): processMsg: DriverStartedState
,E/WifiStateMachine(  937):  DriverStartedState !SCAN_RESULTS_EVENT 0 0 found=3 known=1 got=3 bcn=0
E/WifiStateMachine(  937): processMsg: SupplicantStartedState
E/WifiStateMachine(  937):  SupplicantStartedState !SCAN_RESULTS_EVENT 0 0 found=3 known=1 got=3 bcn=0
D/WifiStateMachine(  937): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
W/WifiHW  (  937): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1331): wlan0: Control interface command 'LIST_DONGLES'
E/WifiStateMachine(  937): [1,455,023,219,882 ms] noteScanEnd no scan source
W/WifiHW  (  937): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/wpa_supplicant( 1331): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
E/WifiStateMachine(  937): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@4f9b7bb sup_state=COMPLETED debouncing=false
E/WifiAutoJoinController (  937): NG7005g c0:ff:d4:d3:aa:4a rssi=-54 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiAutoJoinController (  937): NG700 c0:ff:d4:d3:aa:48 rssi=-63 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiConfigStore(  937): updateSavedNetworkHistory(): try "NG700"WPA_PSK SSID="NG700" NG700 [WPA2-PSK-CCMP][WPS][ESS] ajst=0
E/WifiConfigStore(  937): updateSavedNetworkHistory: HTC improve mode
E/WifiConfigStore(  937):         got known scan result c0:ff:d4:d3:aa:48 key : "NG700"WPA_PSK num: 1 rssi=-63 freq=2412
E/WifiAutoJoinController (  937): UPC503894600 a0:c5:62:7a:49:97 rssi=-83 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiAutoJoinController (  937): Gonzos 38:f8:89:11:e9:11 rssi=-82 cap [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS] is not scored
E/WifiAutoJoinController (  937): ageScanResultsOut delay 40000 size 4 now 1455023219885
E/WifiAutoJoinController (  937): newSupplicantResults size=4 known=1 true
W/WifiHW  (  937): QCOM Debug wifi_send_command "IFNAME=wlan0 STATUS-NO_EVENTS"
D/wpa_supplicant( 1331): wlan0: Control interface command 'STATUS-NO_EVENTS'
E/WifiAutoJoinController (  937): attemptAutoJoin() status=bssid=c0:ff:d4:d3:aa:48
E/WifiAutoJoinController (  937): ssid=NG700
E/WifiAutoJoinController (  937): id=0
E/WifiAutoJoinController (  937): mode=station
E/WifiAutoJoinController (  937): pairwise_cipher=CCMP
E/WifiAutoJoinController (  937): group_cipher=CCMP
E/WifiAutoJoinController (  937): key_mgmt=WPA2-PSK
E/WifiAutoJoinController (  937): wpa_state=COMPLETED
E/WifiAutoJoinController (  937): ip_address=192.168.1.130
E/WifiAutoJoinController (  937): p2p_device_address=92:e7:c4:e6:4c:f8
E/WifiAutoJoinController (  937): address=XX:XX:XX:XX:XX:XX
E/WifiAutoJoinController (  937): uuid=12345678-9abc-def0-1234-56789abcdef1 split=12
E/WifiAutoJoinController (  937): attemptAutoJoin() num recent config 1 current="NG700"WPA_PSK ---> suppNetId=0
E/WifiAutoJoinController (  937): attemptAutoJoin good candidate seen, bumped hard -> status=0 "NG700"WPA_PSK rssi=(-63,-127) num=(1,0)
E/WifiAutoJoinController (  937): attemptAutoJoin skip current candidate  0 key "NG700"WPA_PSK
E/WifiAutoJoinController (  937): attemptRoam: "NG700"WPA_PSK Found c0:ff:d4:d3:aa:48 rssi=-63 freq=2412 Current: c0:ff:d4:d3:aa:48
D/HtcWifiControlRoamOffload: (  937): roamCandidate: nullcurrentBSSID: c0:ff:d4:d3:aa:48
E/WifiStateMachine(  937): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiAutoJoinController (  937): Done attemptAutoJoin status=0
E/WifiConfigStore(  937):  writeKnownNetworkHistory() num networks:1 needWrite=false
E/WifiStateMachine(  937): handleMessage: X
,D/WifiManager( 1815): getScanResults: Base Package Name=com.google.android.gms, uid=10024
,E/WifiTrafficPoller(  937): TRAFFIC_STATS_POLL true Token 11 num clients 6
E/WifiTrafficPoller(  937):  packet count Tx=165 Rx=234
,D/PMS     (  937): acquireWL(33d040c2): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 937 1000 WorkSource{1000}
V/AlarmManager(  937): sending alarm PendingIntent{3a83a7ca: PendingIntentRecord{176a2d3b android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=110665, Int=0
,D/Process (  937): killProcessQuiet, pid=6229
I/ActivityManager(  937): Killing 6229:com.htc.providers.settings:remote/u0a13 (adj 15): empty #17
D/Process (  937): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ClockController( 1214): schedule update now=1455023220025 next=59975
,I/Clock   ( 1214): updateClock:14:07 Europe/Warsaw
I/Clock   ( 1214): updateClock:14:07 Europe/Warsaw
I/Clock   ( 1214): updateClock:14:07 Europe/Warsaw
,I/ActivityManager(  937): Recipient 6229
,D/PMS     (  937): releaseWL(33d040c2): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
D/WeatherUtility( 1214): Weather sync is On
,W/WeatherTimeKeeper( 1214): [refreshWeatherData] no weather data
,E/WifiStateMachine(  937): handleMessage: E msg.what=131155,
E/WifiStateMachine(  937): processMsg: ConnectedState
E/WifiStateMachine(  937):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=1.5, 0.0, 0.0  rx=1.9 bcn=0 [on:0 tx:0 rx:0 period:2596] from screen [on:0 period:-970692940] gl hn u24 rssi=-58 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  937): processMsg: L2ConnectedState
,E/WifiStateMachine(  937):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-63 f=2412 sc=60 link=72 tx=1.5, 0.0, 0.0  rx=1.9 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-970692938] gl hn u24 rssi=-58 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  937):  get link layer stats 0
W/WifiHW  (  937): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL",
D/wpa_supplicant( 1331): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1331): environment dirty rate=0 [0][0][0]
E/WifiStateMachine(  937): fetchRssiLinkSpeedAndFrequencyNative RSSI = -63 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  937): fetchRssiLinkSpeedAndFrequencyNative rssi=-63 linkspeed=72
,E/WifiConfigStore(  937): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-63 "NG700"WPA_PSK
,E/WifiStateMachine(  937): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=0.73 txretriesrate=0.00 rxrate=0.97 userTriggerdPenalty0
E/WifiStateMachine(  937):  good link -> stuck count =0
D/WIFI_ICON( 1214): updateWifiState: RSSI_CHANGED 3 -> 3
E/WifiStateMachine(  937):  badRSSI count0 lowRSSI count0 --> score 56,
D/StatusBar.NetworkController( 1214): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/WifiStateMachine(  937):  isHighRSSI       ---> score=61
E/WifiStateMachine(  937): handleMessage: X
D/WifiWatchdogStateMachine(  937): RSSI current: 3 new: -63, 3
,E/WifiTrafficPoller(  937): TRAFFIC_STATS_POLL true Token 11 num clients 6,
E/WifiTrafficPoller(  937):  packet count Tx=165 Rx=234
,I/PMS     (  937): Going to sleep due to screen timeout (uid 1000)...,
D/ActivityManager(  937): getTaskThumbnailLocked mainThumbnail is null, TaskRecord{1b72ded3 #7 A=.Prism U=0 sz=1}
W/PMS     (  937): mWirelessDisplayManager is null
W/PMS     (  937): mWirelessDisplayManager is still null
,I/SensorManager(  937): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@3e8f7f2f
W/SensorService(  937): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  937): disable: get sensor name = Accelerometer Sensor
,W/SensorService(  937): pid=937, uid=1000
W/SensorService(  937): Active sensors: size = 4
,W/SensorService(  937): Accelerometer Sensor (handle=0x00000000, connections=1)
I/PMS     (  937): Sleeping (uid 1000)...
W/SensorService(  937): CM32181 Light sensor (handle=0x00000003, connections=1)
D/XAN-DPS (  937): prepareColorFade 1
W/SensorService(  937): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/PMN     (  937): goingToSleep
W/SensorService(  937): Significant Motion (handle=0x0000000d, connections=1)
D/PMS     (  937): acquireWL(19ff5a10): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 937 1000 null
W/SensorService(  937): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@3e8f7f2f, eanble = 0, strlen(mName) = 91
W/SensorService(  937): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  937): Listener[0] = com.android.server.display.AutomaticBrightnessController$1@f7ee7a8
W/SensorService(  937): Listener[1] = com.htc.smartdim.sensor_eye@41c7696
W/SensorService(  937): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/PMN     (  937): goingToSleep done
,I/ActivityManager(  937): Start proc com.htc.bgp for broadcast com.htc.flexnet/.SystemIntentReceiver: pid=6579 uid=10011 gids={50011, 9997, 1028, 1015, 5001, 5011, 2001, 3003} abi=arm64-v8a
,I/FeedHostManager( 1625): [onPause],
I/FeedProviderManager( 1625): onPause
I/FeedHostManager( 1625): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@fb5d643
I/SocialFeedProvider( 1625): +onPause
I/SocialFeedProvider( 1625): -onPause
I/Adreno-EGL(  937): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
,I/Adreno-EGL(  937): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL(  937): Build Date: 03/09/15 Mon
I/Adreno-EGL(  937): Local Branch: 
I/Adreno-EGL(  937): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL(  937): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL(  937):                  d74aa161a12b9c6fc6332151
D/AlarmManager(  937): ACTION_SCREEN_ON,
,W/HtcSystemUPManager(  937): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch,
,D/PMS     (  937): releaseWL(19ff5a10): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
I/AlarmManager(  937): [AlarmQueuing] recover blocked alarms
,E/WifiTrafficPoller(  937): ENABLE_TRAFFIC_STATS_POLL true Token 11
I/AlarmManager(  937): [AlarmQueuing] done recovering,
E/WifiTrafficPoller(  937):  packet count Tx=165 Rx=234
I/AlarmManager(  937): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  937): [AlarmQueuing] done EPS screen off alarm recovering
,E/WifiDataStallTracker(  937): ENABLE_DATA_MONITOR_POLL true Token 1
,D/WifiDataStallTracker(  937): updateDataStallInfo: mDataStallTxRxSum={txSum=147 rxSum=121} preTxRxSum={txSum=147 rxSum=121}
W/HtcLockScreen( 1214): KeyguardViewMediator: doKeyguard: not showing because lockscreen is off
E/WifiStateMachine(  937): handleMessage: E msg.what=131167
,E/WifiStateMachine(  937): processMsg: ConnectedState
D/WifiDataStallTracker(  937): updateDataStallInfo: NONE
D/WifiDataStallTracker(  937): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
E/WifiStateMachine(  937):  ConnectedState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  937): processMsg: L2ConnectedState
E/WifiStateMachine(  937):  L2ConnectedState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  937): processMsg: ConnectModeState
E/WifiStateMachine(  937):  ConnectModeState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  937): processMsg: DriverStartedState
E/WifiStateMachine(  937):  DriverStartedState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  937): processMsg: SupplicantStartedState
E/WifiStateMachine(  937):  SupplicantStartedState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  937): processMsg: DefaultState
E/WifiStateMachine(  937):  DefaultState !CMD_SCREEN_STATE_CHANGED 1 0
V/SRS_Proc(  405): ParamSet string: screen_state=on
E/WifiStateMachine(  937):  handleScreenStateChanged Enter: screenOn=true mCurrentScanAlarmMs = 20000 mUserWantsSuspendOpt=false state ConnectedState suppState:CompletedState
W/WifiHW  (  937): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
E/audio_a2dp_hw(  405): adev_set_parameters: ERROR: set param called even when stream out is null
D/wpa_supplicant( 1331): wlan0: Control interface command 'SET_SCREEN_ON 1'
I/wpa_supplicant( 1331): SET_SCREEN_ON:On
I/wpa_supplicant( 1331): htc_wext_set_keepalive +
I/wpa_supplicant( 1331): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1331): getPrivFuncNum +	
I/wpa_supplicant( 1331): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1331): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1331): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1331): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1331): htc_wext_set_TX_TRACKING - ret = 0
D/WifiDisplayAdapter(  937): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  937):     Client/Owner: Client
D/WifiDisplayAdapter(  937):     GroupId: 
D/WifiDisplayAdapter(  937):     Passphrase: 
D/WifiDisplayAdapter(  937):     SessionId: 0
D/WifiDisplayAdapter(  937):     IP Address: }
E/WifiStateMachine(  937): setScanAlarm true period 20000 initial delay 200mAlarmEnabledtrue
D/WifiStateMachine(  937): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine(  937): handleScreenStateChanged Exit: true
E/WifiStateMachine(  937): handleMessage: X
E/WifiStateMachine(  937): handleMessage: E msg.what=131154
E/WifiStateMachine(  937): processMsg: ConnectedState
E/WifiStateMachine(  937):  ConnectedState !CMD_ENABLE_RSSI_POLL 1 0
,E/WifiStateMachine(  937): processMsg: L2ConnectedState
E/WifiStateMachine(  937):  L2ConnectedState !CMD_ENABLE_RSSI_POLL 1 0
W/WifiHW  (  937): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1331): wlan0: Control interface command 'SIGNAL_POLL'
D/WifiController(  937): handleMessage: E msg.what=155650
D/WifiController(  937): processMsg: DeviceActiveState
D/WifiController(  937): processMsg: StaEnabledState
D/WifiController(  937): processMsg: DefaultState
D/WifiController(  937): handleMessage: X
,D/NetworkPolicy(  937): updateScreenOn: false
V/NetworkPolicy(  937): updateIfacesLocked()
,D/NetworkManagementService(  937): isBandwidthControlEnabled: doneSignal.getCount()= 0
,I/wpa_supplicant( 1331): environment dirty rate=0 [0][0][0]
E/WifiStateMachine(  937): fetchRssiLinkSpeedAndFrequencyNative RSSI = -62 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  937): fetchRssiLinkSpeedAndFrequencyNative rssi=-62 linkspeed=72
E/WifiConfigStore(  937): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-62 "NG700"WPA_PSK
E/WifiStateMachine(  937): handleMessage: X
E/WifiStateMachine(  937): handleMessage: E msg.what=131127
E/WifiStateMachine(  937): processMsg: ConnectedState
E/WifiStateMachine(  937):  ConnectedState !CMD_ENABLE_ALL_NETWORKS 0 0
E/WifiStateMachine(  937): processMsg: L2ConnectedState
E/WifiStateMachine(  937):  L2ConnectedState !CMD_ENABLE_ALL_NETWORKS 0 0
E/WifiStateMachine(  937): processMsg: ConnectModeState
E/WifiStateMachine(  937):  ConnectModeState !CMD_ENABLE_ALL_NETWORKS 0 0
E/WifiStateMachine(  937): handleMessage: X
E/WifiStateMachine(  937): handleMessage: E msg.what=131129
E/WifiStateMachine(  937): processMsg: ConnectedState
E/WifiStateMachine(  937):  ConnectedState !CMD_CLEAR_BLACKLIST 0 0
E/WifiStateMachine(  937): processMsg: L2ConnectedState
,E/WifiStateMachine(  937):  L2ConnectedState !CMD_CLEAR_BLACKLIST 0 0
E/WifiStateMachine(  937): processMsg: ConnectModeState
E/WifiStateMachine(  937):  ConnectModeState !CMD_CLEAR_BLACKLIST 0 0
W/WifiHW  (  937): QCOM Debug wifi_send_command "IFNAME=wlan0 BLACKLIST clear"
D/wpa_supplicant( 1331): wlan0: Control interface command 'BLACKLIST clear'
E/wpa_supplicant( 1331): wlan0: BLACKLIST CLEAR 
D/WifiMonitor(  937): Event [IFNAME=wlan0 BLACKLIST CLEAR ]
E/WifiMonitor(  937): WifiMonitor:wlan0 cnt=34 dispatchEvent: BLACKLIST CLEAR 
,E/WifiStateMachine(  937): handleMessage: X
,D/DotMatrix( 1310): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false,
D/GpsLocationProvider(  937): receive broadcast intent, action: android.intent.action.SCREEN_ON
,W/ResourcesManager( 6579): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/IntentController( 1214): receive(android.intent.action.SCREEN_ON,1,false)
,I/CalendarProvider2( 6579): Created com.android.providers.calendar.CalendarAlarmManager@3d753379(com.htc.providers.calendar.HtcCalendarProvider@292bf8be),
,D/PMS     (  937): acquireWL(13a78f7d): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1815 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  937): acquireWL(23be5e72): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1815 10024 WorkSource{10024 com.google.android.gms}
,D/CalendarProvider2( 6579): wait start:true
,D/PMS     (  937): releaseWL(13a78f7d): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  937): releaseWL(23be5e72): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,D/XAN-DPS (  937): prepareColorFade done
,D/XAN-DPS (  937): setBrightness to 0
,I/SensorManager(  937): unregisterListenerImpl++: listener = com.android.server.display.AutomaticBrightnessController$1@f7ee7a8
W/SensorService(  937): Following SensorService logs are not warning, just make sure they are printed
I/DisplayManagerService(  937): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 442.451 x 443.345 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
W/SensorService(  937): disable: get sensor name = CM32181 Light sensor
V/ActivityManager(  937): Display changed displayId=0
D/DotMatrix( 1310): [EventService]  onDisplayChanged: 0
D/DotMatrix( 1310): [EventService] mbHDMIConnect: false, mCoverOn:false
,E/qdutils (  385): int qdutils::getHDMINode(): Failed to open fb node 2,
E/qdutils (  385): int qdutils::getHDMINode(): Failed to find HDMI node
D/AlarmManager(  937): ACTION_SCREEN_OFF
W/SensorService(  937): pid=937, uid=1000
W/SensorService(  937): Active sensors: size = 3
W/SensorService(  937): Accelerometer Sensor (handle=0x00000000, connections=1)
W/SensorService(  937): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  937): Significant Motion (handle=0x0000000d, connections=1)
,W/SensorService(  937): SensorService::listenerSensor++: mName = com.android.server.display.AutomaticBrightnessController$1@f7ee7a8, eanble = 0, strlen(mName) = 66
I/AlarmManager(  937): [AlarmQueuing] screen off now: 
W/SensorService(  937): Active Listeners: mActiveListeners.size() = 1
I/AlarmManager(  937): [AlarmQueuing] data connection: true
W/SensorService(  937): Listener[0] = com.htc.smartdim.sensor_eye@41c7696
I/AlarmManager(  937): [AlarmQueuing] wifi connection: true
W/SensorService(  937): void android::SensorService::listenerSensor(const char*, int32_t)--:
,E/WifiTrafficPoller(  937): ENABLE_TRAFFIC_STATS_POLL false Token 12
D/WifiDataStallTracker(  937): stopDataStallAlarm 
,E/WifiDataStallTracker(  937): ENABLE_DATA_MONITOR_POLL false Token 2
E/WifiStateMachine(  937): handleMessage: E msg.what=131167
E/WifiStateMachine(  937): processMsg: ConnectedState
,E/WifiStateMachine(  937):  ConnectedState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  937): processMsg: L2ConnectedState
,E/WifiStateMachine(  937):  L2ConnectedState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  937): processMsg: ConnectModeState
E/WifiStateMachine(  937):  ConnectModeState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  937): processMsg: DriverStartedState
E/WifiStateMachine(  937):  DriverStartedState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  937): processMsg: SupplicantStartedState
E/WifiStateMachine(  937):  SupplicantStartedState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  937): processMsg: DefaultState
E/WifiStateMachine(  937):  DefaultState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  937):  handleScreenStateChanged Enter: screenOn=false mCurrentScanAlarmMs = 20000 mUserWantsSuspendOpt=false state ConnectedState suppState:CompletedState
W/WifiHW  (  937): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
,D/wpa_supplicant( 1331): wlan0: Control interface command 'SET_SCREEN_ON 0'
I/wpa_supplicant( 1331): SET_SCREEN_ON:Off
I/wpa_supplicant( 1331): htc_wext_set_keepalive +
I/wpa_supplicant( 1331): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/WifiDisplayAdapter(  937): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  937):     Client/Owner: Client
D/WifiDisplayAdapter(  937):     GroupId: 
D/WifiDisplayAdapter(  937):     Passphrase: 
D/WifiDisplayAdapter(  937):     SessionId: 0
D/WifiDisplayAdapter(  937):     IP Address: }
,D/wpa_supplicant( 1331): getPrivFuncNum +	
I/wpa_supplicant( 1331): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1331): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1331): get_ip_address source addr = c0a80182
I/wpa_supplicant( 1331): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1331): htc_wext_set_keepalive - ret = 0
V/SRS_Proc(  405): ParamSet string: screen_state=off
E/audio_a2dp_hw(  405): adev_set_parameters: ERROR: set param called even when stream out is null
,E/WifiStateMachine(  937): setScanAlarm false period 20000 initial delay 0mAlarmEnabledtrue
D/WifiStateMachine(  937): backgroundScan enabled=true startBackgroundScanIfNeeded:false
E/WifiStateMachine(  937): handleScreenStateChanged Exit: false
E/WifiStateMachine(  937): handleMessage: X
E/WifiStateMachine(  937): handleMessage: E msg.what=131154
E/WifiStateMachine(  937): processMsg: ConnectedState
E/WifiStateMachine(  937):  ConnectedState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  937): processMsg: L2ConnectedState
E/WifiStateMachine(  937):  L2ConnectedState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  937): handleMessage: X
,D/WifiController(  937): handleMessage: E msg.what=155651
D/WifiController(  937): processMsg: DeviceActiveState
D/WifiController(  937): processMsg: StaEnabledState
D/WifiController(  937): processMsg: DefaultState
D/WifiController(  937): handleMessage: X
,D/NetworkPolicy(  937): updateScreenOn: false
V/NetworkPolicy(  937): updateIfacesLocked()
,D/NetworkManagementService(  937): isBandwidthControlEnabled: doneSignal.getCount()= 0
,D/CalendarProvider2( 6579): wait end:false
,I/SensorManager( 1214): registerListenerImpl: listener = com.htc.sense.easyaccessservice.SensorHubService@38ff4180, sensor = {Sensor name="hTC Gesture Motion HIDI", vendor="hTC Corp.", version=1, type=10, maxRange=200.0, resolution=1.0, power=0.2, minDelay=0}, delay = 200000, handler = null,
W/SensorService(  937): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  937): enable: get sensor name = hTC Gesture Motion HIDI
,W/SensorService(  937): pid=1214, uid=10041,
W/SensorService(  937): Active sensors: size = 4
W/SensorService(  937): Accelerometer Sensor (handle=0x00000000, connections=1)
,W/SensorService(  937): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  937): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  937): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
,W/SensorService(  937): SensorService::listenerSensor++: mName = com.htc.sense.easyaccessservice.SensorHubService@38ff4180, eanble = 1, strlen(mName) = 57
W/SensorService(  937): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  937): Listener[0] = com.htc.smartdim.sensor_eye@41c7696
W/SensorService(  937): Listener[1] = com.htc.sense.easyaccessservice.SensorHubService@38ff4180
W/SensorService(  937): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/ActivityManager(  937): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=6610 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
,D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3,
D/DotMatrix( 1310): [EventService] getTotalRam: 1842 Mb
,D/GpsLocationProvider(  937): receive broadcast intent, action: android.intent.action.SCREEN_OFF,
,I/IntentController( 1214): receive(android.intent.action.SCREEN_OFF,1,false),
D/ContactMessageStore( 1560): start background delete task...
,D/PMS     (  937): acquireWL(198fefbe): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1815 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  937): releaseWL(198fefbe): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
D/ContactMessageStore( 1560): size: 0 , 0
,D/ContactMessageStore( 1560): Background delete complete
D/PMS     (  937): acquireWL(2849281f): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1815 10024 WorkSource{10024 com.google.android.gms}
W/ContextImpl( 6610): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,D/PMS     (  937): releaseWL(2849281f): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,W/ContextImpl( 6610): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:22 android.app.ActivityThread.handleReceiver:2712 
,D/PowerUsageList:PowerUsageHelper( 6610): MY_DEBUG = false
,I/RemoteViews( 1214): setHTCTheme(com.htc.updater,true,33751145),
D/SmartSyncUtils( 6610): isEpsOn(), nState = 0
,I/RemoteViews( 1214): apply : com.htc.updater 1 9 1 36
D/PMS     (  937): acquireWL(335749ca): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 6610 1000 null
,E/WifiTrafficPoller(  937): TRAFFIC_STATS_POLL false Token 13 num clients 6
,D/PMS     (  937): releaseWL(335749ca): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
W/ContextImpl(  937): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2712 
,E/qdutils (  385): int qdutils::getHDMINode(): Failed to open fb node 2
D/PMS     (  937): Setting HAL interactive mode to false
E/qdutils (  385): int qdutils::getHDMINode(): Failed to find HDMI node
D/PMS     (  937): Setting HAL interactive mode to false done
D/SurfaceControl(  937): Excessive delay in setPowerMode(): 296ms
D/PMS     (  937): Setting HAL auto-suspend mode to true
D/PMS     (  937): Setting HAL auto-suspend mode done
W/HtcSystemUPManager(  937): HtcSystemUPHandler The policy is disabled. AppId: UTD_BI, category: C0006
,D/SmartDim(  937): Init customizeScreenOffDelayClass error
I/InputMethodManagerService(  937): screenObserver, isScreenOn=false
,D/StatusBarManagerService(  937): swetImeWindowStatus vis=0 backDisposition=0
I/InputMethodManagerService(  937): Disable input method client, pid=1625
D/HABCtrl (  937): TPE algorithm. remove timeout.
D/PMS     (  937): acquireWL(10e2273b): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 937 1000 null
D/PMS     (  937): OOBE c monitor 11
I/BatteryService(  937): n_update end
I/InputManager(  937): Cancel all due to getting PMS screen off broadcast. ActualScreenOn=false,
D/PMS     (  937): releaseWL(10e2273b): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1214): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
D/HtcPowerSaver(  937): updateBatteryInfo
D/UsbnetService(  937): BroadcastReceiver::onReceive+
D/NotificationService(  937): plugged=true pluggin=true
D/UsbnetService(  937): onReceive BATTERY_CHANGED
D/PMS     (  937): runPSCheck
D/UsbnetService(  937):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  937): Checking...
D/UsbnetService(  937): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  937): >> updateStatus
D/WifiController(  937): handleMessage: E msg.what=155652
D/WifiController(  937): battery changed pluggedType: 2
D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1310): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/WifiController(  937): processMsg: DeviceActiveState
D/WifiController(  937): processMsg: StaEnabledState
I/HtcPowerSaver(  937): updateStatus (8000,100,-1,false,false,false,-1)
I/IntentController( 1214): receive(android.intent.action.BATTERY_CHANGED,1,false)
,I/HtcPowerSaver(  937): << updateStatus
,D/HeadsetStateMachine( 3116): Disconnected process message: 10, size: 0
D/PowerUI ( 1214): closing low battery warning: level=100
D/WifiController(  937): processMsg: DefaultState
D/WifiController(  937): handleMessage: X
D/NfcService( 1580): ScreenObserver: OFF
I/PhoneStatusBar( 1214): setImeWindowStatus(false,false)
D/PowerUI ( 1214): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/NfcService( 1580): applyRouting - 0
,D/PMS     (  937): acquireWL(2ae0de58): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1580 1027 null
D/NfcService( 1580): applyRouting -2
D/NfcService( 1580): applyRouting
,D/NfcService( 1580): Ignore this applyRouting...
,D/PMS     (  937): releaseWL(2ae0de58): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,W/ContextImpl( 6610): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,W/ContextImpl( 6610): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:22 android.app.ActivityThread.handleReceiver:2712 
,D/SmartSyncUtils( 6610): isEpsOn(), nState = 0,
,D/SmartSyncUtils( 6610): isEpsOn(), nState = 0,
,W/ContextImpl( 6610): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:73 android.app.ActivityThread.handleReceiver:2712 ,
W/ContextImpl(  937): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1830 android.content.ContextWrapper.stopService:520 android.content.ContextWrapper.stopService:520 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2712 
,I/SensorManager(  937): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@41c7696
W/SensorService(  937): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  937): disable: get sensor name = Accelerometer Sensor
,I/ClockController( 1214): stop clock update:screen off
,W/SensorService(  937): pid=937, uid=1000
W/SensorService(  937): Active sensors: size = 3
W/SensorService(  937): CM36686 Proximity sensor (handle=0x00000004, connections=1)
,W/SensorService(  937): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  937): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
W/SensorService(  937): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@41c7696, eanble = 0, strlen(mName) = 35
W/SensorService(  937): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  937): Listener[0] = com.htc.sense.easyaccessservice.SensorHubService@38ff4180
W/SensorService(  937): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  937): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  937): disable: get sensor name = CM36686 Proximity sensor
,I/BatteryController( 1214): status:5 level:100 unsupport:false plugged:true
,W/SensorService(  937): pid=937, uid=1000,
W/SensorService(  937): Active sensors: size = 2
W/SensorService(  937): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  937): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
W/SensorService(  937): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@41c7696, eanble = 0, strlen(mName) = 35
W/SensorService(  937): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  937): Listener[0] = com.htc.sense.easyaccessservice.SensorHubService@38ff4180
E/ActivityThread(  937): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@3a446217 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  937): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@3a446217 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  937): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:1003)
E/ActivityThread(  937): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:767)
E/ActivityThread(  937): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1775)
E/ActivityThread(  937): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1755)
E/ActivityThread(  937): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:495)
E/ActivityThread(  937): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  937): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  937): 	at android.app.Service.onStartCommand(Service.java:458)
E/ActivityThread(  937): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3072)
E/ActivityThread(  937): 	at android.app.ActivityThread.access$2100(ActivityThread.java:144)
E/ActivityThread(  937): ,	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1470)
E/ActivityThread(  937): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  937): 	at android.os.Looper.loop(Looper.java:155)
E/ActivityThread(  937): 	at com.android.server.SystemServer.run(SystemServer.java:324)
E/ActivityThread(  937): 	at com.android.server.SystemServer.main(SystemServer.java:225)
E/ActivityThread(  937): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread(  937): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread(  937): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
,E/ActivityThread(  937): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
W/SensorService(  937): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  937): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@41c7696
,I/ActivityManager(  937): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=6642 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a,
,I/PowerUsageList:PowerUsageHelper( 6610): PowerProfile::POWER_SCREEN_FULL = 154.8,
,D/PowerUsageList:BatterySipperExt( 6610): gen(), null == sipper.uidObj, userId = 0,
,D/Process (  937): killProcessQuiet, pid=6019
I/ActivityManager(  937): Killing 6019:com.google.android.gms:car/u0a24 (adj 15): empty #17
D/Process (  937): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.removeContentProvider:10141 
,D/SmartSyncUtils( 6610): getMobilePolicyEnabled, result = true
,D/WifiService(  937): New client listening to asynchronous messages,
E/WifiTrafficPoller(  937): ADD_CLIENT: 7
,I/ActivityManager(  937): Recipient 6019
,D/PowerUsageList:PowerUsageHelper( 6610): MY_DEBUG = false,
,E/WifiTrafficPoller(  937): TRAFFIC_STATS_POLL false Token 13 num clients 7,
,D/Process (  937): killProcessQuiet, pid=6259
I/ActivityManager(  937): Killing 6259:com.google.android.apps.docs/u0a101 (adj 15): empty #17
D/Process (  937): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,E/WifiDataStallTracker(  937): DATA_MONITOR_POLL false Token 3
,I/ActivityManager(  937): Recipient 6259
,I/CalendarProvider2( 6579): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: }
W/ContentResolver( 6579): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar),
,I/ActivityManager(  937): Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=6667 uid=10010 gids={50010, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,D/Process (  937): killProcessQuiet, pid=5549
I/ActivityManager(  937): Killing 5549:com.android.defcontainer/u0a15 (adj 15): empty #17,
D/Process (  937): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  937): Recipient 5549
,D/PMS     (  937): releaseWL(1bef4aa6): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 null
,W/ResourcesManager( 6667): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/CalendarApplication( 6667): onCreate
,D/ProviderChangeReceiver( 6667): ---------------------------------------------------
,D/ProviderChangeReceiver( 6667): ProviderChangeReceiver onReceive, start HtcAlertService to update notification!
,D/Process (  937): killProcessQuiet, pid=5407
I/ActivityManager(  937): Killing 5407:com.htc.mediamanager/u0a28 (adj 15): empty #17
D/Process (  937): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processNextBroadcast:706 
D/HtcAlertService( 6667): start to updateAlertNotification!
,I/ActivityManager(  937): Recipient 5407
,D/HtcAlertService( 6667): No fired or scheduled alerts
,D/HtcAlertUtils( 6667): -- cancelReminderNotification --
D/HtcAlertUtils( 6667): broadcastExistReminder!
D/DotMatrix( 1310): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,E/WifiStateMachine(  937): handleMessage: E msg.what=131155
E/WifiStateMachine(  937): processMsg: ConnectedState
,E/WifiStateMachine(  937):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-62 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-970689917] gl hn u24 rssi=-58 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  937): processMsg: L2ConnectedState
E/WifiStateMachine(  937):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-62 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-970689915] gl hn u24 rssi=-58 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  937): handleMessage: X
,E/WifiStateMachine(  937): handleMessage: E msg.what=131155
E/WifiStateMachine(  937): processMsg: ConnectedState
E/WifiStateMachine(  937):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-62 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1129] from screen [on:0 period:-970688785] gl hn u24 rssi=-58 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  937): processMsg: L2ConnectedState
E/WifiStateMachine(  937):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-62 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-970688783] gl hn u24 rssi=-58 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  937): handleMessage: X
,D/HtcUPManager( 1214): HtcUPServiceProxy onTrimMemory() has been called. Memory Level: 60
,E/WifiDataStallTracker(  937): DATA_MONITOR_POLL false Token 3
,D/ContactMessageStore( 1560): MSG_NOTIFY_CS_TO_SYNC >>,
D/ContactMessageStore( 1560): MSG_NOTIFY_CS_TO_SYNC <<
,W/Atfwd_Sendcmd(  465): AtCmdFwd service not published, waiting... retryCnt : 1
,D/Process (  937): killProcessQuiet, pid=5601
I/ActivityManager(  937): Killing 5601:com.htc.musicenhancer/u0a49 (adj 15): empty #17
D/Process (  937): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  937): Recipient 5601
,E/libprocessgroup(  937): failed to kill 1 processes for processgroup 5601
,W/Atfwd_Sendcmd(  465): AtCmdFwd service not published, waiting... retryCnt : 2,
,D/PMS     (  937): acquireWL(2c41fc17): PARTIAL_WAKE_LOCK  *alarm* 0x1 937 1000 WorkSource{10024},
V/AlarmManager(  937): sending alarm PendingIntent{212051ed: PendingIntentRecord{3e074822 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=142573, Int=0
,D/PMS     (  937): releaseWL(2c41fc17): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10024},
,W/Atfwd_Sendcmd(  465): AtCmdFwd service not published, waiting... retryCnt : 3,
,D/GpsLocationProvider(  937): [handleMessage] DOWNLOAD_XTRA_DATA,
,D/GpsLocationProvider(  937): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  937): acquireWL(d6042b3): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 937 1000 null
,D/libc    (  937): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 4,
,D/libc    (  937): [NET] android_getaddrinfofornet-, err=8,
,D/libc    (  937): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024
D/libc    (  937): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  937): [NET] android_getaddrinfo_proxy+
D/libc    (  937): [NET] android_getaddrinfo_proxy get netid:0,
D/libc    (  399): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024
D/libc    (  399): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,D/libc    (  399): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  399): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  937): [NET] android_getaddrinfo_proxy-, success
,D/libc    (  937): [NET] android_getaddrinfofornet+,hn 14(0x35342e3233302e),sn(),hints(known),family 0,flags 4
D/libc    (  937): [NET] android_getaddrinfofornet-, SUCCESS
,D/GpsLocationProvider(  937): [handleDownloadXtraData] calling native_inject_xtra_data,
,D/GpsLocationProvider(  937): [reportHTCStatus] eventMask = 3 , status = 0,
D/GpsLocationProvider(  937): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
D/GpsLocationProvider(  937):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  937): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED,
D/PMS     (  937): acquireWL(3512570f): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 937 1000 null
D/PMS     (  937): releaseWL(d6042b3): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 null
D/PMS     (  937): releaseWL(3512570f): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/ContactMessageStore( 1560): MSG_NOTIFY_CS_TO_SYNC >>,
D/ContactMessageStore( 1560): MSG_NOTIFY_CS_TO_SYNC <<
,W/ContextImpl(  937): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 ,
,W/Atfwd_Sendcmd(  465): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  937): acquireWL(13efd39c): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 937 1000 null
I/BatteryService(  937): n_update end
D/PMS     (  937): releaseWL(13efd39c): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  937): BroadcastReceiver::onReceive+,
D/NotificationService(  937): plugged=true pluggin=true
D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1214): closing low battery warning: level=100
D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/WifiController(  937): battery changed pluggedType: 2
D/DotMatrix( 1310): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/PowerUI ( 1214): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  937): onReceive BATTERY_CHANGED
,D/UsbnetService(  937):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false,
D/HtcPowerSaver(  937): updateBatteryInfo
D/UsbnetService(  937): BroadcastReceiver::onReceive-
D/PMS     (  937): runPSCheck
D/WifiController(  937): handleMessage: E msg.what=155652
D/HtcPowerSaver(  937): Checking...
D/WifiController(  937): processMsg: DeviceActiveState
I/HtcPowerSaver(  937): >> updateStatus
D/HeadsetStateMachine( 3116): Disconnected process message: 10, size: 0
I/HtcPowerSaver(  937): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  937): processMsg: StaEnabledState
I/HtcPowerSaver(  937): << updateStatus
D/WifiController(  937): processMsg: DefaultState
D/WifiController(  937): handleMessage: X
I/IntentController( 1214): receive(android.intent.action.BATTERY_CHANGED,1,false)
,I/BatteryController( 1214): status:5 level:100 unsupport:false plugged:true
,D/TelephonyReceiver( 1560): switchBindHtcMsgCursor: null
,W/Atfwd_Sendcmd(  465): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  937): acquireWL(163ed1a5): PARTIAL_WAKE_LOCK  *alarm* 0x1 937 1000 WorkSource{1000}
V/AlarmManager(  937): sending alarm PendingIntent{273db97a: PendingIntentRecord{3227552b android broadcastIntent}}, i=android.app.backup.intent.INIT, t=0, cnt=1, w=1455023274255, Int=0
D/PMS     (  937): acquireWL(20f48d88): PARTIAL_WAKE_LOCK  *backup* 0x1 937 1000 null
V/AlarmManager(  937): sending alarm PendingIntent{3a83a7ca: PendingIntentRecord{176a2d3b android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=170665, Int=0
,V/AlarmManager(  937): sending alarm PendingIntent{a6fe321: PendingIntentRecord{155df346 android broadcastIntent}}, i=com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE, t=2, cnt=1, w=200704, Int=0,
V/AlarmManager(  937): sending alarm PendingIntent{27441907: PendingIntentRecord{1a08fa34 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=189108, Int=0
,D/PMS     (  937): acquireWL(a46905d): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1961 10024 WorkSource{10024 com.google.android.gms}
,W/BackupManagerService(  937): Requested unavailable transport: com.google.android.gms.backup.BackupTransportService
,E/BackupManagerService(  937): Requested init for com.google.android.gms.backup.BackupTransportService but not found
,D/PMS     (  937): releaseWL(20f48d88): PARTIAL_WAKE_LOCK  *backup* 0x1 null
,D/PMS     (  937): releaseWL(163ed1a5): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,D/WeatherUtility( 1214): Weather sync is On
,W/WeatherTimeKeeper( 1214): [refreshWeatherData] no weather data
,D/PMS     (  937): acquireWL(24f5fdd2): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1961 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  937): releaseWL(a46905d): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,V/GLSActivity( 1961): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/PMS     (  937): releaseWL(24f5fdd2): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  937): acquireWL(51d5bcc): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1961 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  937): releaseWL(51d5bcc): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  937): acquireWL(2b406e15): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1961 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  937): releaseWL(2b406e15): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  937): acquireWL(537752a): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1961 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  937): acquireWL(26cbdf1b): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1961 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  937): acquireWL(6c6d691): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1961 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  937): releaseWL(537752a): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,I/VacuumService( 1961): Vacuum at: now=1455023310323 tag=VacuumService,
,D/PMS     (  937): releaseWL(26cbdf1b): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  937): acquireWL(223f51f7): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1961 10024 WorkSource{10024 com.google.android.gms},
,I/GoogleURLConnFactory( 1961): Using platform SSLCertificateSocketFactory,
,D/PMS     (  937): releaseWL(223f51f7): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
D/PMS     (  937): acquireWL(3bf95864): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1961 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  937): releaseWL(3bf95864): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,I/art     ( 1961): Explicit concurrent mark sweep GC freed 18132(990KB) AllocSpace objects, 5(420KB) LOS objects, 49% free, 4MB/8MB, paused 1.297ms total 86.877ms,
,W/Uploader( 1961): No account for auth token provided
,D/libc    ( 1961): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4,
D/libc    ( 1961): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 1961): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 1961): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1961): [NET] android_getaddrinfo_proxy+
D/libc    ( 1961): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  399): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  399): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,D/libc    (  399): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  399): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 1961): [NET] android_getaddrinfo_proxy-, success
,D/libc    ( 1961): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4,
D/libc    ( 1961): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 1961): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 1961): [NET] android_getaddrinfofornet-, err=8,
,W/Uploader( 1961): No account for auth token provided,
,W/Uploader( 1961): No account for auth token provided,
,W/Uploader( 1961):  no longer exists, so no auth token.,
,W/Uploader( 1961): No account for auth token provided,
,I/GLSUser ( 1961): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1961): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1961): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1961): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1961): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  937): Explicit concurrent mark sweep GC freed 36448(1990KB) AllocSpace objects, 4(1068KB) LOS objects, 33% free, 18MB/28MB, paused 1.938ms total 173.894ms
,D/DotMatrix( 1310): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1310): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
E/Uploader( 1961): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1961): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1961): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1961): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1961): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1961): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1961): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1961): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1961): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1961): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1961): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1961): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1961): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/RemoteViews( 1214): reapply : com.google.android.gms 4 40,
,D/PMS     (  937): releaseWL(6c6d691): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
D/PMS     (  937): acquireWL(1f398601): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1961 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  937): releaseWL(1f398601): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
D/PMS     (  937): acquireWL(38188ca6): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1961 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  937): releaseWL(38188ca6): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/HtcUPManager( 1214): HtcUPServiceProxy Disconnect from  UP serivce: No interaction with app,
,D/HtcUPManager( 1214): HtcUPServiceProxy Disconnect from UP service. Change state to: DISCONNECTED
,D/HtcAppUPService( 1543): HtcUPService [##] onDestroy(), this =com.htc.sense.hsp.upservice.HtcUPService@1b456418
,D/Process (  937): killProcessQuiet, pid=6433
,I/ActivityManager(  937): Killing 6433:com.google.android.setupwizard/u0a77 (adj 15): empty #17
D/Process (  937): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  937): Recipient 6433
,W/Atfwd_Sendcmd(  465): AtCmdFwd service not published, waiting... retryCnt : 1,
,D/PMS     (  937): acquireWL(bb2a6e7): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 937 1000 null,
D/UsbnetService(  937): BroadcastReceiver::onReceive+
I/BatteryService(  937): n_update end
D/UsbnetService(  937): onReceive BATTERY_CHANGED
D/PMS     (  937): releaseWL(bb2a6e7): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  937):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  937): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  937): updateBatteryInfo
D/WifiController(  937): handleMessage: E msg.what=155652
D/NotificationService(  937): plugged=true pluggin=true
D/WifiController(  937): processMsg: DeviceActiveState
D/PMS     (  937): runPSCheck
D/WifiController(  937): processMsg: StaEnabledState
,D/HtcPowerSaver(  937): Checking...
D/WifiController(  937): processMsg: DefaultState
I/HtcPowerSaver(  937): >> updateStatus
D/WifiController(  937): handleMessage: X
D/WifiController(  937): battery changed pluggedType: 2
I/IntentController( 1214): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1214): closing low battery warning: level=100
D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1214): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  937): updateStatus (8000,100,-1,false,false,false,-1)
D/DotMatrix( 1310): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  937): << updateStatus
D/HeadsetStateMachine( 3116): Disconnected process message: 10, size: 0
,I/BatteryController( 1214): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  465): AtCmdFwd service not published, waiting... retryCnt : 2,
,W/Atfwd_Sendcmd(  465): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  465): AtCmdFwd service not published, waiting... retryCnt : 4
,D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  937): acquireWL(2795a294): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 937 1000 null
D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/BatteryService(  937): n_update end
I/IntentController( 1214): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/PMS     (  937): releaseWL(2795a294): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1310): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1214): closing low battery warning: level=100
D/HeadsetStateMachine( 3116): Disconnected process message: 10, size: 0
D/HtcPowerSaver(  937): updateBatteryInfo
D/UsbnetService(  937): BroadcastReceiver::onReceive+
D/PowerUI ( 1214): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  937): onReceive BATTERY_CHANGED
D/NotificationService(  937): plugged=true pluggin=true
D/UsbnetService(  937):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  937): runPSCheck
D/UsbnetService(  937): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  937): Checking...
D/WifiController(  937): handleMessage: E msg.what=155652
I/HtcPowerSaver(  937): >> updateStatus
D/WifiController(  937): processMsg: DeviceActiveState
D/WifiController(  937): battery changed pluggedType: 2
D/WifiController(  937): processMsg: StaEnabledState
D/WifiController(  937): processMsg: DefaultState
D/WifiController(  937): handleMessage: X
I/HtcPowerSaver(  937): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  937): << updateStatus
,I/BatteryController( 1214): status:5 level:100 unsupport:false plugged:true,
,D/wpa_supplicant( 1331): wlan0: BSS: Remove id 0 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g' due to wpa_bss_flush_by_age,
D/wpa_supplicant( 1331): wlan0: BSS: Remove id 2 BSSID a0:c5:62:7a:49:97 SSID 'UPC503894600' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1331): wlan0: BSS: Remove id 3 BSSID 38:f8:89:11:e9:11 SSID 'Gonzos' due to wpa_bss_flush_by_age
D/WifiMonitor(  937): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a]
E/WifiMonitor(  937): WifiMonitor:wlan0 cnt=35 dispatchEvent: CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a
D/WifiMonitor(  937): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 2 a0:c5:62:7a:49:97]
E/WifiMonitor(  937): WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-BSS-REMOVED 2 a0:c5:62:7a:49:97
D/WifiMonitor(  937): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 3 38:f8:89:11:e9:11]
E/WifiMonitor(  937): WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-BSS-REMOVED 3 38:f8:89:11:e9:11
,W/Atfwd_Sendcmd(  465): AtCmdFwd service not published, waiting... retryCnt : 5,
,W/Atfwd_Sendcmd(  465): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  937): acquireWL(4b7813d): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 937 1000 null
I/BatteryService(  937): n_update end
D/PMS     (  937): releaseWL(4b7813d): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  937): BroadcastReceiver::onReceive+,
D/PowerUI ( 1214): closing low battery warning: level=100
D/UsbnetService(  937): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  937): updateBatteryInfo
I/IntentController( 1214): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/NotificationService(  937): plugged=true pluggin=true
D/UsbnetService(  937):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  937): runPSCheck
D/UsbnetService(  937): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  937): Checking...
D/HeadsetStateMachine( 3116): Disconnected process message: 10, size: 0
,I/HtcPowerSaver(  937): >> updateStatus
D/WifiController(  937): handleMessage: E msg.what=155652
D/WifiController(  937): battery changed pluggedType: 2
D/WifiController(  937): processMsg: DeviceActiveState
D/PowerUI ( 1214): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  937): processMsg: StaEnabledState
D/WifiController(  937): processMsg: DefaultState
D/WifiController(  937): handleMessage: X
D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1310): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  937): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  937): << updateStatus
,I/BatteryController( 1214): status:5 level:100 unsupport:false plugged:true,
,W/Atfwd_Sendcmd(  465): AtCmdFwd service not published, waiting... retryCnt : 2
,W/Atfwd_Sendcmd(  465): AtCmdFwd service not published, waiting... retryCnt : 3
,V/GLSActivity( 1961): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1961): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket,
I/GLSUser ( 1961): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1961): [GLSUser] Extracting token using key: Auth,
,W/GLSActivity( 1961): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1961): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/DotMatrix( 1310): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1310): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1214): reapply : com.google.android.gms 4 40,
,W/GLSActivity( 1961): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1961): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1961): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1961): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1961): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1961): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1961): 	at android.os.Binder.execTransact(Binder.java:454)
E/PlayEventLogger( 5978): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5978): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5978): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 5978): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5978): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 5978): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5978): 	at android.os.Binder.execTransact(Binder.java:454)
,W/System  ( 5978): Ignoring header User-Agent because its value was null.
,D/libc    ( 5978): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4,
D/libc    ( 5978): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 5978): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 5978): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 5978): [NET] android_getaddrinfo_proxy+
D/libc    ( 5978): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  399): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  399): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,D/libc    (  399): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  399): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 5978): [NET] android_getaddrinfo_proxy-, success
,D/PMS     (  937): acquireWL(2fdd17d7): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 937 1000 WorkSource{1000}
V/AlarmManager(  937): sending alarm PendingIntent{3a83a7ca: PendingIntentRecord{176a2d3b android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=230665, Int=0,
,V/AlarmManager(  937): sending alarm PendingIntent{39f033ad: PendingIntentRecord{3fd2e6e2 com.htc.backup startService}}, i=resume, t=0, cnt=1, w=1455023450362, Int=0
,I/ActivityManager(  937): Start proc com.htc.cs.pns for service com.htc.cs.pns/com.htc.lib1.cs.push.service.UpdateRegistrationService: pid=6702 uid=10071 gids={50071, 9997, 1028, 1015, 3003} abi=armeabi-v7a
V/AlarmManager(  937): sending alarm PendingIntent{23f15a73: PendingIntentRecord{3f44bd30 com.htc.cs.pns startService}}, i=null, t=1, cnt=1, w=1455023493161, Int=0
,D/PMS     (  937): releaseWL(2fdd17d7): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1214): Weather sync is On
W/WeatherTimeKeeper( 1214): [refreshWeatherData] no weather data
,E/cutils-trace( 6724): Error opening trace file: Permission denied (13)
,I/dex2oat ( 6724): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.htc.cs.pns/app_push_lib/plugin-deploy.jar --oat-fd=22 --oat-location=/data/data/com.htc.cs.pns/app_push_dex/plugin-deploy.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
I/dex2oat ( 6724): dex2oat: override thread count:4
,I/dex2oat ( 6724): dex2oat took 703.168ms (threads: 4)
,I/PushClient( 6702): ApplicationMonitor {14984c3b}: logBasicAppInfo(): PackageName:             com.htc.cs.pns
,I/PushClient( 6702): ApplicationMonitor {14984c3b}: logBasicAppInfo(): ProcessName:             com.htc.cs.pns
I/PushClient( 6702): ApplicationMonitor {14984c3b}: logBasicAppInfo(): VersionName:             1.2.853019
,I/PushClient( 6702): ApplicationMonitor {14984c3b}: logBasicAppInfo(): VersionCode:             148001224
,I/PushClient( 6702): ApplicationMonitor {14984c3b}: logBasicAppInfo(): ApplicationPath:         /system/priv-app/PNSClient/PNSClient.apk
,I/PushClient( 6702): ApplicationMonitor {14984c3b}: logBasicAppInfo(): AppFileDataPath:         /data/data/com.htc.cs.pns/files
I/PushClient( 6702): ApplicationMonitor {14984c3b}: logBasicAppInfo(): Htc_SECURITY_DEBUG_flag: false
I/PushClient( 6702): ApplicationMonitor {14984c3b}: logBasicAppInfo(): Htc_DEBUG_flag:          false
I/PushClient( 6702): ApplicationMonitor {14984c3b}: logBasicAppInfo(): BuildConfig.DEBUG:       false
,I/PushClient( 6702): PnsModel {1b2ae2ca}: update(): Update registration caused by: alarm
,I/PushClient( 6702): PnsConfigModel {3dccece9}: <init>(): Use dm-client for provisioning.,
,W/System.err( 6702): SLF4J: Failed to load class "org.slf4j.impl.StaticLoggerBinder".,
W/System.err( 6702): SLF4J: Defaulting to no-operation (NOP) logger implementation
,W/System.err( 6702): SLF4J: See http://www.slf4j.org/codes.html#StaticLoggerBinder for further details.
,W/ContextImpl( 6702): Implicit intents with startService are not safe: Intent { act=com.htc.cs.dm.intent.action.BIND_CORE_SERVICE } android.content.ContextWrapper.bindService:538 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 
,I/ActivityManager(  937): Start proc com.htc.cs.dm for service com.htc.cs.dm/.config.service.ConfigManagerBoundService: pid=6731 uid=10099 gids={50099, 9997, 3003} abi=arm64-v8a
,I/DeviceManagement( 6731): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.2.848686;250001208] pid=6731 dbg=false s=true
,I/DeviceManagement( 6731): ConfigManagerBoundService: *** getConfig: appID=com.htc.cs.pns options=Bundle[EMPTY_PARCEL]
I/DeviceManagement( 6731): ConfigManagerBoundService: Caller: uid=com.htc.cs.pns (10071) packages=[com.htc.cs.pns]
,I/DeviceManagement( 6731): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[EMPTY_PARCEL], appID=com.htc.cs.pns}]],
,I/DeviceManagement( 6731): WorkflowService: Starting workflow service
,I/DeviceManagement( 6731): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@1b2ae2ca] args=[Bundle[mParcelledData.dataSize=88]]
,I/DeviceManagement( 6731): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=88]
,I/DeviceManagement( 6731): ModelRegistry: Loading model meta data from resources...,
,I/DeviceManagement( 6731): ConfigManagerController: *** getConfig: appID=com.htc.cs.pns includeMeta=false,
,I/DeviceManagement( 6731): SessionStateController: Checking invariants...,
,I/DeviceManagement( 6731): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true,
,I/DeviceManagement( 6731): SessionStateController: Checking invariants...,
,I/DeviceManagement( 6731): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.pns includeMeta=false,
,I/DeviceManagement( 6731): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@1b2ae2ca],
,I/DeviceManagement( 6731): WorkflowService: Stopping workflow service
,D/Process (  937): killProcessQuiet, pid=6312
I/ActivityManager(  937): Killing 6312:com.google.android.gms.unstable/u0a24 (adj 15): empty #17
D/Process (  937): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/PushClient( 6702): PnsModel {1b2ae2ca}: update(): The registration record has not expired yet. No need to update.,
,I/ActivityManager(  937): Recipient 6312
,D/Process (  937): killProcessQuiet, pid=6366,
I/ActivityManager(  937): Killing 6366:com.test.thalitest/u0a366 (adj 15): empty #17
D/Process (  937): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  937): Recipient 6366,
,E/InputEventReceiver( 1402): Looper::removeFd(68) is failed, result(0), input channel 'ClientState{32a70d17 uid 10366 pid 6366} (c)'
,W/Atfwd_Sendcmd(  465): AtCmdFwd service not published, waiting... retryCnt : 4,
,D/PMS     (  937): acquireWL(32b2621d): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 937 1000 null
I/BatteryService(  937): n_update end
D/PMS     (  937): releaseWL(32b2621d): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HeadsetStateMachine( 3116): Disconnected process message: 10, size: 0
,D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  937): plugged=true pluggin=true
D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  937): updateBatteryInfo
D/DotMatrix( 1310): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  937): runPSCheck
D/UsbnetService(  937): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  937): Checking...
D/UsbnetService(  937): onReceive BATTERY_CHANGED
I/HtcPowerSaver(  937): >> updateStatus
D/UsbnetService(  937):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  937): BroadcastReceiver::onReceive-
I/IntentController( 1214): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/WifiController(  937): handleMessage: E msg.what=155652
D/WifiController(  937): battery changed pluggedType: 2
D/WifiController(  937): processMsg: DeviceActiveState
D/WifiController(  937): processMsg: StaEnabledState
D/WifiController(  937): processMsg: DefaultState
D/WifiController(  937): handleMessage: X
,D/PowerUI ( 1214): closing low battery warning: level=100
D/PowerUI ( 1214): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  937): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  937): << updateStatus
,I/BatteryController( 1214): status:5 level:100 unsupport:false plugged:true,
,W/Atfwd_Sendcmd(  465): AtCmdFwd service not published, waiting... retryCnt : 5,
,W/Atfwd_Sendcmd(  465): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  937): acquireWL(2f46cc92): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 937 1000 null
,D/UsbnetService(  937): BroadcastReceiver::onReceive+,
I/BatteryService(  937): n_update end
D/UsbnetService(  937): onReceive BATTERY_CHANGED
D/PMS     (  937): releaseWL(2f46cc92): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  937):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/NotificationService(  937): plugged=true pluggin=true
D/UsbnetService(  937): BroadcastReceiver::onReceive-
D/WifiController(  937): battery changed pluggedType: 2
D/WifiController(  937): handleMessage: E msg.what=155652
D/HtcPowerSaver(  937): updateBatteryInfo
D/WifiController(  937): processMsg: DeviceActiveState
D/PMS     (  937): runPSCheck
D/WifiController(  937): processMsg: StaEnabledState
D/HtcPowerSaver(  937): Checking...
D/WifiController(  937): processMsg: DefaultState
I/HtcPowerSaver(  937): >> updateStatus
D/WifiController(  937): handleMessage: X
D/PowerUI ( 1214): closing low battery warning: level=100
D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1310): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1214): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HeadsetStateMachine( 3116): Disconnected process message: 10, size: 0
D/PowerUI ( 1214): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  937): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  937): << updateStatus
,I/BatteryController( 1214): status:5 level:100 unsupport:false plugged:true,
,W/Atfwd_Sendcmd(  465): AtCmdFwd service not published, waiting... retryCnt : 2,
,W/Atfwd_Sendcmd(  465): AtCmdFwd service not published, waiting... retryCnt : 3,
,W/Atfwd_Sendcmd(  465): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  937): acquireWL(3e65c663): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 937 1000 null
I/BatteryService(  937): n_update end
D/PMS     (  937): releaseWL(3e65c663): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  937): updateBatteryInfo
D/PMS     (  937): runPSCheck
D/HtcPowerSaver(  937): Checking...
I/HtcPowerSaver(  937): >> updateStatus
I/HtcPowerSaver(  937): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  937): << updateStatus
,D/UsbnetService(  937): BroadcastReceiver::onReceive+
D/NotificationService(  937): plugged=true pluggin=true
D/UsbnetService(  937): onReceive BATTERY_CHANGED
D/UsbnetService(  937):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/WifiController(  937): battery changed pluggedType: 2
D/UsbnetService(  937): BroadcastReceiver::onReceive-
D/PowerUI ( 1214): closing low battery warning: level=100
D/WifiController(  937): handleMessage: E msg.what=155652
D/WifiController(  937): processMsg: DeviceActiveState
D/WifiController(  937): processMsg: StaEnabledState
,D/WifiController(  937): processMsg: DefaultState,
D/WifiController(  937): handleMessage: X
D/PowerUI ( 1214): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HeadsetStateMachine( 3116): Disconnected process message: 10, size: 0
,D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1310): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1214): receive(android.intent.action.BATTERY_CHANGED,1,false)
,I/BatteryController( 1214): status:5 level:100 unsupport:false plugged:true,
,W/Atfwd_Sendcmd(  465): AtCmdFwd service not published, waiting... retryCnt : 5,
,D/UsbnetService(  937): BroadcastReceiver::onReceive+
D/PMS     (  937): acquireWL(2759d260): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 937 1000 null
D/UsbnetService(  937): onReceive BATTERY_CHANGED
I/BatteryService(  937): n_update end
D/UsbnetService(  937):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  937): releaseWL(2759d260): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  937): BroadcastReceiver::onReceive-
D/PowerUI ( 1214): closing low battery warning: level=100
D/HeadsetStateMachine( 3116): Disconnected process message: 10, size: 0
D/HtcPowerSaver(  937): updateBatteryInfo
D/NotificationService(  937): plugged=true pluggin=true
I/IntentController( 1214): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  937): runPSCheck
D/WifiController(  937): handleMessage: E msg.what=155652
D/HtcPowerSaver(  937): Checking...
D/WifiController(  937): processMsg: DeviceActiveState
I/HtcPowerSaver(  937): >> updateStatus
D/WifiController(  937): processMsg: StaEnabledState
D/WifiController(  937): processMsg: DefaultState
D/WifiController(  937): battery changed pluggedType: 2
D/WifiController(  937): handleMessage: X
D/PowerUI ( 1214): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1310): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  937): updateStatus (8000,100,-1,false,false,false,-1),
I/HtcPowerSaver(  937): << updateStatus
,I/BatteryController( 1214): status:5 level:100 unsupport:false plugged:true,
,E/PNP_UPDATERD(  386): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1560): MSG_CHECK_DELETION >>
D/ContactMessageStore( 1560): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1560): sku_id=118
D/ContactMessageStore( 1560): MSG_CHECK_DELETION <<
,D/ContactMessageStore( 1560): start background delete task...
,D/ContactMessageStore( 1560): size: 0 , 0
,D/ContactMessageStore( 1560): Background delete complete
,D/PMS     (  937): acquireWL(35980319): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 937 1000 null
I/BatteryService(  937): n_update end
D/PMS     (  937): releaseWL(35980319): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  937): updateBatteryInfo
D/UsbnetService(  937): BroadcastReceiver::onReceive+
D/NotificationService(  937): plugged=true pluggin=true
D/UsbnetService(  937): onReceive BATTERY_CHANGED
D/PMS     (  937): runPSCheck
D/UsbnetService(  937):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  937): Checking...
D/UsbnetService(  937): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  937): >> updateStatus
D/WifiController(  937): handleMessage: E msg.what=155652
D/WifiController(  937): battery changed pluggedType: 2
D/WifiController(  937): processMsg: DeviceActiveState
D/WifiController(  937): processMsg: StaEnabledState
D/WifiController(  937): processMsg: DefaultState
D/WifiController(  937): handleMessage: X
,D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1310): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HeadsetStateMachine( 3116): Disconnected process message: 10, size: 0
,I/HtcPowerSaver(  937): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  937): << updateStatus
,D/PowerUI ( 1214): closing low battery warning: level=100
,I/IntentController( 1214): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1214): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/BatteryController( 1214): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  937): acquireWL(21011fde): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 937 1000 null
I/BatteryService(  937): n_update end
,D/PMS     (  937): releaseWL(21011fde): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  937): updateBatteryInfo
D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1214): closing low battery warning: level=100
D/DotMatrix( 1310): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/NotificationService(  937): plugged=true pluggin=true
I/IntentController( 1214): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  937): runPSCheck
D/UsbnetService(  937): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  937): Checking...
D/UsbnetService(  937): onReceive BATTERY_CHANGED
I/HtcPowerSaver(  937): >> updateStatus
D/UsbnetService(  937):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/WifiController(  937): battery changed pluggedType: 2
D/UsbnetService(  937): BroadcastReceiver::onReceive-
D/PowerUI ( 1214): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HeadsetStateMachine( 3116): Disconnected process message: 10, size: 0
I/HtcPowerSaver(  937): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  937): handleMessage: E msg.what=155652
I/HtcPowerSaver(  937): << updateStatus
,D/WifiController(  937): processMsg: DeviceActiveState
D/WifiController(  937): processMsg: StaEnabledState
D/WifiController(  937): processMsg: DefaultState
D/WifiController(  937): handleMessage: X
,I/BatteryController( 1214): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  937): acquireWL(28e465bf): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 937 1000 null
I/BatteryService(  937): n_update end
D/PMS     (  937): releaseWL(28e465bf): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  937): updateBatteryInfo
D/HeadsetStateMachine( 3116): Disconnected process message: 10, size: 0
D/UsbnetService(  937): BroadcastReceiver::onReceive+
D/NotificationService(  937): plugged=true pluggin=true
D/UsbnetService(  937): onReceive BATTERY_CHANGED
,D/PMS     (  937): runPSCheck
D/UsbnetService(  937):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  937): Checking...
D/UsbnetService(  937): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  937): >> updateStatus
D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/WifiController(  937): battery changed pluggedType: 2
D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1214): closing low battery warning: level=100
D/DotMatrix( 1310): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1214): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  937): handleMessage: E msg.what=155652
D/WifiController(  937): processMsg: DeviceActiveState
D/WifiController(  937): processMsg: StaEnabledState,
I/HtcPowerSaver(  937): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  937): processMsg: DefaultState
I/HtcPowerSaver(  937): << updateStatus
D/WifiController(  937): handleMessage: X
I/IntentController( 1214): receive(android.intent.action.BATTERY_CHANGED,1,false)
,I/BatteryController( 1214): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  937): acquireWL(30f9b48c): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 937 1000 null
I/BatteryService(  937): n_update end
D/PMS     (  937): releaseWL(30f9b48c): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  937): updateBatteryInfo
D/PMS     (  937): runPSCheck
D/HtcPowerSaver(  937): Checking...
I/HtcPowerSaver(  937): >> updateStatus
D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1214): closing low battery warning: level=100
D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1310): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1214): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1214): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HeadsetStateMachine( 3116): Disconnected process message: 10, size: 0
I/HtcPowerSaver(  937): updateStatus (8000,100,-1,false,false,false,-1)
D/UsbnetService(  937): BroadcastReceiver::onReceive+
I/HtcPowerSaver(  937): << updateStatus
D/UsbnetService(  937): onReceive BATTERY_CHANGED
D/NotificationService(  937): plugged=true pluggin=true
D/UsbnetService(  937):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/WifiController(  937): battery changed pluggedType: 2
D/UsbnetService(  937): BroadcastReceiver::onReceive-
D/WifiController(  937): handleMessage: E msg.what=155652
D/WifiController(  937): processMsg: DeviceActiveState
D/WifiController(  937): processMsg: StaEnabledState
D/WifiController(  937): processMsg: DefaultState
D/WifiController(  937): handleMessage: X
,I/BatteryController( 1214): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  937): acquireWL(1f9cb7d5): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 937 1000 null
I/IntentController( 1214): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/BatteryService(  937): n_update end
D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  937): releaseWL(1f9cb7d5): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HeadsetStateMachine( 3116): Disconnected process message: 10, size: 0
D/HtcPowerSaver(  937): updateBatteryInfo
D/UsbnetService(  937): BroadcastReceiver::onReceive+
D/PowerUI ( 1214): closing low battery warning: level=100
D/UsbnetService(  937): onReceive BATTERY_CHANGED
D/PowerUI ( 1214): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  937):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/NotificationService(  937): plugged=true pluggin=true
D/UsbnetService(  937): BroadcastReceiver::onReceive-
D/PMS     (  937): runPSCheck
D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  937): Checking...
D/DotMatrix( 1310): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  937): >> updateStatus
,D/WifiController(  937): handleMessage: E msg.what=155652
D/WifiController(  937): battery changed pluggedType: 2
D/WifiController(  937): processMsg: DeviceActiveState
D/WifiController(  937): processMsg: StaEnabledState
D/WifiController(  937): processMsg: DefaultState
D/WifiController(  937): handleMessage: X
,I/HtcPowerSaver(  937): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  937): << updateStatus
,I/BatteryController( 1214): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  937): acquireWL(397b5bea): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 937 1000 WorkSource{1000},
I/bt-btm  ( 3116): Received oneshot timer event complete
V/AlarmManager(  937): sending alarm PendingIntent{3a83a7ca: PendingIntentRecord{176a2d3b android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=410665, Int=0
,I/bt-btm  ( 3116): btm_ble_timeout
V/AlarmManager(  937): sending alarm PendingIntent{10839edb: PendingIntentRecord{1ad38d78 com.android.bluetooth broadcastIntent}}, i=com.android.bluetooth.btservice.action.ALARM_WAKEUP, t=2, cnt=1, w=940588, Int=0
,I/bt-btm  ( 3116): btm_gen_resolvable_private_addr
D/PMS     (  937): acquireWL(3fdfc51): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 3116 1002 null
,D/bt-btm  ( 3116): btm_ble_rand_enc_complete
I/bt-btm  ( 3116): btm_gen_resolve_paddr_low
D/bt-smp  ( 3116): smp_encrypt_data
W/bt-smp  ( 3116): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 3116): Plain text(LSB ~ MSB) = 56 21 5b 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3116): Encrypted text(LSB ~ MSB) = 07 a0 79 62 2f fc e4 73 d6 1c 31 b1 f5 28 1f 50 
I/bt-btm  ( 3116): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 3116): Stopping oneshot timer
D/bt-btm  ( 3116): Starting oneshot timer type:103 timeout:900s
,D/PMS     (  937): releaseWL(397b5bea): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000},
,D/WeatherUtility( 1214): Weather sync is On
W/WeatherTimeKeeper( 1214): [refreshWeatherData] no weather data
,D/PMS     (  937): releaseWL(3fdfc51): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 null,
,D/PMS     (  937): acquireWL(dab4cb6): PARTIAL_WAKE_LOCK  *alarm* 0x1 937 1000 WorkSource{1000},
V/AlarmManager(  937): sending alarm PendingIntent{1aae29fe: PendingIntentRecord{2567755f android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=804641, Int=0,
,V/AlarmManager(  937): sending alarm PendingIntent{3a83a7ca: PendingIntentRecord{176a2d3b android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=950665, Int=0
,V/AlarmManager(  937): sending alarm PendingIntent{e134db7: PendingIntentRecord{32700924 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1455023558338, Int=1800000,
V/AlarmManager(  937): sending alarm PendingIntent{12550c8d: PendingIntentRecord{3a177e42 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.MCS_HEARTBEAT, t=2, cnt=1, w=936511, Int=0
V/AlarmManager(  937): sending alarm PendingIntent{d850e53: PendingIntentRecord{152626d5 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1455024075548, Int=0
,D/PMS     (  937): acquireWL(33369390): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 4433 10024 WorkSource{10024 com.google.android.gms},
,D/WeatherUtility( 1214): Weather sync is On
,W/WeatherTimeKeeper( 1214): [refreshWeatherData] no weather data
,D/PMS     (  937): acquireWL(2b233c8e): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1961 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  937): releaseWL(2b233c8e): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 WorkSource{10024 com.google.android.gms},
W/ContextImpl( 6610): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,D/PMS     (  937): acquireWL(3e483caf): PARTIAL_WAKE_LOCK  Event Log Service 0x1 4433 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  937): releaseWL(33369390): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  937): releaseWL(dab4cb6): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,D/PowerUsageList:PowerUsageHelper( 6610): MY_DEBUG = false
,D/PowerUsageService( 6610): repeat time = 1455024975611
,I/EventLogService( 4433): Aggregate from 1455023203988 (log), 1455021758283 (data)
,D/PMS     (  937): acquireWL(50144a8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1961 10024 WorkSource{10024 com.google.android.gms}
,D/GCM     ( 1961): Message class com.google.f.a.a.i
,D/PMS     (  937): releaseWL(50144a8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  937): releaseWL(3e483caf): PARTIAL_WAKE_LOCK  Event Log Service 0x1 WorkSource{10024 com.google.android.gms}
,I/PowerUsageList:PowerUsageHelper( 6610): PowerProfile::POWER_SCREEN_FULL = 154.8
,D/PowerUsageList:BatterySipperExt( 6610): gen(), null == sipper.uidObj, userId = 0
,D/PMS     (  937): acquireWL(6659bc1): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 937 1000 WorkSource{1000}
,V/AlarmManager(  937): sending alarm PendingIntent{3a83a7ca: PendingIntentRecord{176a2d3b android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1010665, Int=0
V/AlarmManager(  937): sending alarm PendingIntent{26fe4f66: PendingIntentRecord{255d12a7 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1455024122030, Int=0
D/SmartSyncUtils( 6610): isEpsOn(), nState = 0,
,D/PMS     (  937): acquireWL(187a0354): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 6610 1000 null
D/PMS     (  937): releaseWL(6659bc1): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1214): Weather sync is On
W/WeatherTimeKeeper( 1214): [refreshWeatherData] no weather data
,D/SmartSyncScreenOnOffTimeReceiver( 6610): [updateNmRange] bManual = false,
D/SmartSyncScreenOnOffTimeReceiver( 6610): [updateNmRange] USERNIGHT_TIMESTART = 1, USERNIGHT_TIMEEND = 7, nStart = 1, nEnd = 7, bNormalRange = true
,D/SmartSyncScreenOnOffTimeReceiver( 6610): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 6610): SettingOnTime = 1455084000000, randomSettingOnTime = 1455081785000,
D/SmartSyncScreenOnOffTimeReceiver( 6610): SettingOffTime = 1455062400000, randomSettingOffTime = 1455068580000
,D/SmartSyncScreenOnOffTimeReceiver( 6610): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 6610): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 6610): bNightModeTurnOffOnce = false
,D/PMS     (  937): releaseWL(187a0354): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/PMS     (  937): acquireWL(3fef32fd): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 937 1000 null,
I/BatteryService(  937): n_update end
,D/UsbnetService(  937): BroadcastReceiver::onReceive+,
D/PMS     (  937): releaseWL(3fef32fd): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  937): onReceive BATTERY_CHANGED
,D/NotificationService(  937): plugged=true pluggin=true
D/UsbnetService(  937):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/WifiController(  937): battery changed pluggedType: 2
D/UsbnetService(  937): BroadcastReceiver::onReceive-,
D/HtcPowerSaver(  937): updateBatteryInfo
D/WifiController(  937): handleMessage: E msg.what=155652
D/PMS     (  937): runPSCheck,
D/WifiController(  937): processMsg: DeviceActiveState
D/HtcPowerSaver(  937): Checking...
,D/WifiController(  937): processMsg: StaEnabledState
I/HtcPowerSaver(  937): >> updateStatus
D/WifiController(  937): processMsg: DefaultState
D/PowerUI ( 1214): closing low battery warning: level=100
D/WifiController(  937): handleMessage: X
D/PowerUI ( 1214): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  937): updateStatus (8000,100,-1,false,false,false,-1)
I/IntentController( 1214): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/HtcPowerSaver(  937): << updateStatus
,D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HeadsetStateMachine( 3116): Disconnected process message: 10, size: 0
D/DotMatrix( 1310): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/BatteryController( 1214): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  937): acquireWL(70ffbf2): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 937 1000 null
I/BatteryService(  937): n_update end
D/PMS     (  937): releaseWL(70ffbf2): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  937): updateBatteryInfo,
D/PMS     (  937): runPSCheck
D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  937): Checking...
D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  937): >> updateStatus
D/DotMatrix( 1310): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1214): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1214): closing low battery warning: level=100
D/PowerUI ( 1214): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HeadsetStateMachine( 3116): Disconnected process message: 10, size: 0
I/HtcPowerSaver(  937): updateStatus (8000,100,-1,false,false,false,-1)
D/UsbnetService(  937): BroadcastReceiver::onReceive+
I/HtcPowerSaver(  937): << updateStatus
D/UsbnetService(  937): onReceive BATTERY_CHANGED
D/NotificationService(  937): plugged=true pluggin=true
D/UsbnetService(  937):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  937): BroadcastReceiver::onReceive-
D/WifiController(  937): handleMessage: E msg.what=155652
D/WifiController(  937): battery changed pluggedType: 2
D/WifiController(  937): processMsg: DeviceActiveState
D/WifiController(  937): processMsg: StaEnabledState
D/WifiController(  937): processMsg: DefaultState
D/WifiController(  937): handleMessage: X
,I/BatteryController( 1214): status:5 level:100 unsupport:false plugged:true
,D/HeadsetStateMachine( 3116): Disconnected process message: 10, size: 0,
D/PMS     (  937): acquireWL(2fbe3243): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 937 1000 null
I/IntentController( 1214): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/BatteryService(  937): n_update end
D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  937): releaseWL(2fbe3243): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1214): closing low battery warning: level=100
D/DotMatrix( 1310): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1214): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  937): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  937): updateBatteryInfo
D/UsbnetService(  937): onReceive BATTERY_CHANGED
D/NotificationService(  937): plugged=true pluggin=true
D/UsbnetService(  937):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  937): runPSCheck
D/UsbnetService(  937): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  937): Checking...
D/WifiController(  937): handleMessage: E msg.what=155652
I/HtcPowerSaver(  937): >> updateStatus,
D/WifiController(  937): processMsg: DeviceActiveState
D/WifiController(  937): battery changed pluggedType: 2
D/WifiController(  937): processMsg: StaEnabledState
D/WifiController(  937): processMsg: DefaultState
D/WifiController(  937): handleMessage: X
,I/HtcPowerSaver(  937): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  937): << updateStatus
,I/BatteryController( 1214): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  937): acquireWL(2a1e00c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 937 1000 null,
,I/BatteryService(  937): n_update end,
D/PMS     (  937): releaseWL(2a1e00c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1214): closing low battery warning: level=100
D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/HtcPowerSaver(  937): updateBatteryInfo
,D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1214): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1310): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1214): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/HeadsetStateMachine( 3116): Disconnected process message: 10, size: 0
D/NotificationService(  937): plugged=true pluggin=true
D/UsbnetService(  937): BroadcastReceiver::onReceive+
D/UsbnetService(  937): onReceive BATTERY_CHANGED
D/UsbnetService(  937):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  937): runPSCheck
D/UsbnetService(  937): BroadcastReceiver::onReceive-
D/WifiController(  937): battery changed pluggedType: 2
D/WifiController(  937): handleMessage: E msg.what=155652
D/HtcPowerSaver(  937): Checking...
,D/WifiController(  937): processMsg: DeviceActiveState
I/HtcPowerSaver(  937): >> updateStatus
D/WifiController(  937): processMsg: StaEnabledState
D/WifiController(  937): processMsg: DefaultState
D/WifiController(  937): handleMessage: X
,I/HtcPowerSaver(  937): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  937): << updateStatus
,I/BatteryController( 1214): status:5 level:100 unsupport:false plugged:true,
,E/PNP_UPDATERD(  386): inotify_add_watch failed. (No such file or directory),
,I/UsageStatsService(  937): User[0] Flushing usage stats to disk
,D/PMS     (  937): acquireWL(278101f9): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 937 1000 null
I/BatteryService(  937): n_update end
D/PMS     (  937): releaseWL(278101f9): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  937): updateBatteryInfo,
D/UsbnetService(  937): BroadcastReceiver::onReceive+
D/NotificationService(  937): plugged=true pluggin=true,
D/UsbnetService(  937): onReceive BATTERY_CHANGED
,D/PowerUI ( 1214): closing low battery warning: level=100
D/UsbnetService(  937):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  937): runPSCheck
D/UsbnetService(  937): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  937): Checking...,
,D/WifiController(  937): handleMessage: E msg.what=155652
I/HtcPowerSaver(  937): >> updateStatus
D/WifiController(  937): processMsg: DeviceActiveState
D/WifiController(  937): battery changed pluggedType: 2
D/WifiController(  937): processMsg: StaEnabledState
D/PowerUI ( 1214): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/WifiController(  937): processMsg: DefaultState
I/HtcPowerSaver(  937): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  937): handleMessage: X
I/HtcPowerSaver(  937): << updateStatus
I/IntentController( 1214): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1310): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1310): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HeadsetStateMachine( 3116): Disconnected process message: 10, size: 0
,I/BatteryController( 1214): status:5 level:100 unsupport:false plugged:true
,TIME-OUT KILL (timeout was 1200000ms)
```
