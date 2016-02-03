#### Test 58135655c662d33_thali06_HTC-HTC One M8s Logs


```
--------- beginning of main
D/DrmWidevineDash(  402): Service_Initialize: ends! returns 0
D/QSAPPSVER(  402): qsapps_get_capabilities: Capability from secure side: 0x0
D/QSAPPSVER(  402): qsapps_get_capabilities: returns 0
D/DrmWidevineDash(  402): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf44f4000
E/DrmWidevineDash(  402): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf44f4000
D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/DrmLibTime(  549): got the req here! ret=0
D/DrmLibTime(  549): command id, time_cmd_id = 770
D/DrmLibTime(  549): time_getutcsec starts!
D/DrmLibTime(  549): QSEE Time Listener: time_getutcsec
D/DrmLibTime(  549): QSEE Time Listener: get_utc_seconds
D/DrmLibTime(  549): QSEE Time Listener: time_get_modem_time
D/DrmLibTime(  549): QSEE Time Listener: Checking if ATS_MODEM is set or not.
E/QC-time-services(  549): Receive Passed == base = 13, unit = 1, operation = 2, result = 0
D/DrmLibTime(  549): QSEE Time Listener: ATS_MODEM is not set. Fallback to Android system time.
D/DrmLibTime(  549): QSEE Time Listener: Retrieved Android system time: 1454523170
D/DrmLibTime(  549): time_getutcsec returns 0, sec = 1454523170; nsec = 0
D/DrmLibTime(  549): time_getutcsec finished! 
D/DrmLibTime(  549): iotcl_continue_command finished! and return 0 
D/DrmLibTime(  549): before calling ioctl to read the next time_cmd
E/QC-time-services(  476): Daemon: Time-services: Waiting to acceptconnection
D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  402): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  402): OEMCrypto_APIVersion: starts!
D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  402): hlos api version =  9
D/DrmWidevineDash(  402): tz api version =  9
D/DrmWidevineDash(  402): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  402): OEMCrypto_IsKeyboxValid: starts!
D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  402): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  402): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  402): OEMCrypto_OpenSession: starts! SID=0xffe86a18
D/DrmWidevineDash(  402): OEMCrypto_OpenSession Session ID = 0
D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  402): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  402): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  402): OEMCrypto_GetRandom: starts! randomData=0xab1f5a10, dataLength=8
D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  402): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  402): OEMCrypto_LoadDeviceRSAKey: starts! SID=1, wrapped_rsa_key=0xab215468, wrapped_rsa_key_length=1280
D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  402): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  402): CdmEngine::QueryKeyControlInfo
W/WVCdm   (  402): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  402): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  402): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  402): OEMCrypto_GetDeviceID: starts! deviceID=0xab1f4c88, idLength=0xf47696f8
D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  402): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  402): OEMCrypto_SupportsUsageTable: starts!
D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  402): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  402): OEMCrypto_SupportsUsageTable: wv_app_version = 24
D/DrmWidevineDash(  402): OEMCrypto_SupportsUsageTable: ends! returns 0
D/DrmWidevineDash(  402): OEMCrypto_GetHDCPCapability: starts!, current = 0xf476970e, maximum = 0xf476970f
D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  402): OEMCrypto_GetHDCPCapability: ends! returns 0
D/DrmWidevineDash(  402): OEMCrypto_APIVersion: starts!
D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  402): hlos api version =  9
D/DrmWidevineDash(  402): tz api version =  9
D/DrmWidevineDash(  402): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  402): OEMCrypto_GenerateNonce: starts! SID=1, nonce=0xf476977c
D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  402): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  402): PrepareKeyRequest: nonce=3543672025
D/DrmWidevineDash(  402): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xab20d448
D/DrmWidevineDash(  402): message_length=1611, signature=0xab20da98, signature_length=0xf47696dc
D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
E/WifiTrafficPoller(  959): TRAFFIC_STATS_POLL true Token 11 num clients 6
E/WifiTrafficPoller(  959):  packet count Tx=207 Rx=288
,D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  402): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  402): CdmEngine::CloseSession
D/DrmWidevineDash(  402): OEMCrypto_CloseSession: starts! SID=1
D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  402): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  402): L3 Terminate.
D/DrmWidevineDash(  402): OEMCrypto_Terminate: starts!
D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  402): Service_Uninitialize: starts!
D/QSEECOMAPI: (  402): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  402): QSEECom_shutdown_app, app_id = 8
D/DrmWidevineDash(  402): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  402): OEMCrypto_Terminate: ends! returns 0
E/cutils-trace( 6650): Error opening trace file: Permission denied (13)
I/dex2oat ( 6650): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm64 --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=36 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
I/dex2oat ( 6650): dex2oat: override thread count:4
I/wpa_supplicant( 1351): environment dirty rate=0 [0][0][0]
E/WifiStateMachine(  959): fetchRssiLinkSpeedAndFrequencyNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  959): fetchRssiLinkSpeedAndFrequencyNative rssi=-57 linkspeed=72
E/WifiConfigStore(  959): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-57 "NG700"WPA_PSK
E/WifiStateMachine(  959): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=0.42 txretriesrate=0.00 rxrate=1.16 userTriggerdPenalty0
E/WifiStateMachine(  959):  good link -> stuck count =0
E/WifiStateMachine(  959):  badRSSI count0 lowRSSI count0 --> score 56
E/WifiStateMachine(  959):  isHighRSSI       ---> score=61
E/WifiStateMachine(  959): handleMessage: X
D/WifiWatchdogStateMachine(  959): RSSI current: 3 new: -57, 3
--------- beginning of system
D/WIFI_ICON( 1218): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1218): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
W/ContextImpl(  959): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 
I/dex2oat ( 6650): dex2oat took 88.625ms (threads: 4)
I/Adreno-EGL( 6615): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 6615): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6615): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6615): Local Branch: 
I/Adreno-EGL( 6615): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6615): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6615):                  d74aa161a12b9c6fc6332151
E/cutils-trace( 6647): Error opening trace file: Permission denied (13)
I/Adreno-EGL( 6615): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 6615): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6615): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6615): Local Branch: 
I/Adreno-EGL( 6615): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6615): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6615):                  d74aa161a12b9c6fc6332151
I/WVCdm   (  402): CdmEngine::OpenSession
I/WVCdm   (  402): Level3 Library Sep 25 2014 17:10:03
W/WVCdm   (  402): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
D/DrmWidevineDash(  402): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x15
D/DrmWidevineDash(  402): Service_Initialize: starts!
D/QSEECOMAPI: (  402): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  402): App is not loaded in QSEE
E/QSEECOMAPI: (  402): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  402): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  402): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  402): App is not loaded in QSEE
D/CustomizationManager( 6647): ====startRecUseTime====
D/htc.customization.log.level( 6647):  is 
W/CustomizationLogLevel( 6647): Level value is invalid, use default level 2
D/QSEECOMAPI: (  402): Loaded image: APP id = 9
D/DrmWidevineDash(  402): Service_Initialize: ends! returns 0
D/QSAPPSVER(  402): qsapps_get_capabilities: Capability from secure side: 0x0
D/QSAPPSVER(  402): qsapps_get_capabilities: returns 0
D/DrmWidevineDash(  402): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf44f4000
E/DrmWidevineDash(  402): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf44f4000
D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/DrmLibTime(  549): got the req here! ret=0
D/DrmLibTime(  549): command id, time_cmd_id = 770
D/DrmLibTime(  549): time_getutcsec starts!
D/DrmLibTime(  549): QSEE Time Listener: time_getutcsec
D/DrmLibTime(  549): QSEE Time Listener: get_utc_seconds
D/DrmLibTime(  549): QSEE Time Listener: time_get_modem_time
D/DrmLibTime(  549): QSEE Time Listener: Checking if ATS_MODEM is set or not.
E/QC-time-services(  549): Receive Passed == base = 13, unit = 1, operation = 2, result = 0
D/DrmLibTime(  549): QSEE Time Listener: ATS_MODEM is not set. Fallback to Android system time.
D/DrmLibTime(  549): QSEE Time Listener: Retrieved Android system time: 1454523170
D/DrmLibTime(  549): time_getutcsec returns 0, sec = 1454523170; nsec = 0
D/DrmLibTime(  549): time_getutcsec finished! 
D/DrmLibTime(  549): iotcl_continue_command finished! and return 0 
D/DrmLibTime(  549): before calling ioctl to read the next time_cmd
E/QC-time-services(  476): Daemon: Time-services: Waiting to acceptconnection
D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  402): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  402): OEMCrypto_APIVersion: starts!
D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  402): hlos api version =  9
D/DrmWidevineDash(  402): tz api version =  9
D/DrmWidevineDash(  402): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  402): OEMCrypto_IsKeyboxValid: starts!
D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  402): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  402): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  402): OEMCrypto_OpenSession: starts! SID=0xf4867928
D/DrmWidevineDash(  402): OEMCrypto_OpenSession Session ID = 0
D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  402): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  402): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  402): OEMCrypto_GetRandom: starts! randomData=0xab20d548, dataLength=8
D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  402): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  402): OEMCrypto_LoadDeviceRSAKey: starts! SID=1, wrapped_rsa_key=0xab215468, wrapped_rsa_key_length=1280
D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  402): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  402): CdmEngine::QueryKeyControlInfo
W/WVCdm   (  402): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  402): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  402): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  402): OEMCrypto_GetDeviceID: starts! deviceID=0xab1f4ca8, idLength=0xf48676f8
D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  402): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  402): OEMCrypto_SupportsUsageTable: starts!
D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  402): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  402): OEMCrypto_SupportsUsageTable: wv_app_version = 24
D/DrmWidevineDash(  402): OEMCrypto_SupportsUsageTable: ends! returns 0
D/DrmWidevineDash(  402): OEMCrypto_GetHDCPCapability: starts!, current = 0xf486770e, maximum = 0xf486770f
D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  402): OEMCrypto_GetHDCPCapability: ends! returns 0
D/DrmWidevineDash(  402): OEMCrypto_APIVersion: starts!
D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  402): hlos api version =  9
D/DrmWidevineDash(  402): tz api version =  9
D/DrmWidevineDash(  402): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  402): OEMCrypto_GenerateNonce: starts! SID=1, nonce=0xf486777c
D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  402): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  402): PrepareKeyRequest: nonce=3478900845
D/DrmWidevineDash(  402): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xab25a7d8
D/DrmWidevineDash(  402): message_length=1646, signature=0xab1f59d0, signature_length=0xf48676dc
D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/CustomizationManager( 6647):  Read ACC file spent 0.056 (s)
D/CIDMapFileReader( 6647): Parsing tag item name = HTC__001
D/CIDMapFileReader( 6647): Parsing tag item name = HTC__102
D/CIDMapFileReader( 6647): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 6647): Parsing tag item name = HTC__032
D/CIDMapFileReader( 6647): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 6647): Parsing tag item name = HTC__002
D/CIDMapFileReader( 6647): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 6647): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 6647): Parsing tag category name = system
I/CustomizationCIDLoader( 6647): Parsing tag category name = application
I/CustomizationCIDLoader( 6647): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 6647): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 6647): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 6647): Parsing tag category name = Settings
I/CustomizationCIDLoader( 6647): Parsing tag category name = ACC
I/CustomizationCIDLoader( 6647): add string-array item, value = 42507
I/CustomizationCIDLoader( 6647): add string-array item, value = 21902
I/CustomizationCIDLoader( 6647): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 6647): add string-array item, value = 23420
I/CustomizationCIDLoader( 6647): add string-array item, value = 22299
I/CustomizationCIDLoader( 6647): add string-array item, value = 24002
I/CustomizationCIDLoader( 6647): add string-array item, value = 23210
I/CustomizationCIDLoader( 6647): add string-array item, value = 23205
I/CustomizationCIDLoader( 6647): add string-array item, value = 23806
I/CustomizationCIDLoader( 6647): add string-array item, value = 23430
I/CustomizationCIDLoader( 6647): add string-array item, value = 23408
I/CustomizationCIDLoader( 6647): add string-array item, value = 27205
I/CustomizationCIDLoader( 6647): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 6647): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 6647): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 6647): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 6647): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 6647): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 6647): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 6647): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 6647): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 6647): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 6647): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 6647): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 6647):  Read CID file spent 0.102 (s)
D/CustomizationManager( 6647):  All configurations done spent 0.102 (s)
D/PMS     (  959): acquireHCC(bfd06c): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 959 1000 null
I/ActivityManager(  959): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 pid 6647 on display 0
D/PMS     (  959): acquireHCC(22b4d635): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 959 1000 null
W/asset   (  959): Copying FileAsset 0x557b081080 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
D/PMS     (  959): acquireWL(160f8758): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 959 1000 null
I/AnimationUtil(  959): isHTCRecent(ThaliTest/Recent screens.)/5
I/FeedHostManager( 1547): [onPause]
I/FeedProviderManager( 1547): onPause
I/FeedHostManager( 1547): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@2a9593f8
I/SocialFeedProvider( 1547): +onPause
I/SocialFeedProvider( 1547): -onPause
D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  402): OEMCrypto_GenerateRSASignature returns 0
W/HtcSystemUPManager(  959): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
I/WVCdm   (  402): CdmEngine::CloseSession
D/DrmWidevineDash(  402): OEMCrypto_CloseSession: starts! SID=1
D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  402): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  402): L3 Terminate.
D/DrmWidevineDash(  402): OEMCrypto_Terminate: starts!
D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  402): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  402): Service_Uninitialize: starts!
D/QSEECOMAPI: (  402): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  402): QSEECom_shutdown_app, app_id = 9
D/DrmWidevineDash(  402): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  402): OEMCrypto_Terminate: ends! returns 0
I/ActivityManager(  959): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6676 uid=10366 gids={50366, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/StatusBarManagerService(  959): setSystemUiVisibility(0x0)
D/StatusBarManagerService(  959): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  959): hiding MENU key
I/TrimMemoryManager( 1547): [trimMemory] 20
W/asset   ( 6676): Copying FileAsset 0xac1c1048 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/CheckinRequestBuilder( 4431): Classify the device as Phone.
,D/libc    ( 4431): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
D/libc    ( 4431): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 4431): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
D/libc    ( 4431): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 4431): [NET] android_getaddrinfo_proxy+
D/libc    ( 4431): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  395): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
D/libc    (  395): [NET] _dns_getaddrinfo+, netid:100, mark:917604
D/libc    (  395): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  395): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 4431): [NET] android_getaddrinfo_proxy-, success
I/WebViewFactory( 6676): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
I/LibraryLoader( 6676): Time to load native libraries: 9 ms (timestamps 710-719)
I/LibraryLoader( 6676): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6676): Binding Chromium to main looper Looper (main, tid 1) {2f9470db}
I/LibraryLoader( 6676): Expected native library version number "",actual native library version number ""
I/chromium( 6676): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6676): Initializing chromium process, singleProcess=true
W/art     ( 6676): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6676): ApplicationContext is null in ApplicationStatus
E/WifiTrafficPoller(  959): TRAFFIC_STATS_POLL true Token 11 num clients 6
E/WifiTrafficPoller(  959):  packet count Tx=208 Rx=288
E/WifiTrafficPoller(  959): notifying of data activity 2
D/WIFI_ICON( 1218): WifiActivity: 2
D/StatusBar.NetworkController( 1218): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_out_4 (gone) T]
W/chromium( 6676): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 6676): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6676): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6676): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 6676): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6676): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6676): Local Branch: 
I/Adreno-EGL( 6676): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6676): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6676):                  d74aa161a12b9c6fc6332151
W/System.err(  959): java.lang.Throwable: stack dump
W/System.err(  959): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  959): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  959): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  959): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothManagerService(  959): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  959): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@20f97334:true
D/BluetoothAdapter( 6676): 576667575: getState(). Returning 12
I/art     (  959): Explicit concurrent mark sweep GC freed 31053(1900KB) AllocSpace objects, 5(164KB) LOS objects, 33% free, 16MB/25MB, paused 2.012ms total 173.268ms
D/wpa_supplicant( 1351): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 1351): wlan0: nl80211: New scan results available
D/wpa_supplicant( 1351): nl80211: Scan included frequencies: 2412 2417 2422 2427 2432 2437 2442 2447 2452 2457 2462 2467 2472 5180 5200 5220 5240 5260 5280 5300 5320 5500 5520 5540 5560 5580 5600 5620 5640 5660 5680 5700
D/wpa_supplicant( 1351): wlan0: Event SCAN_RESULTS (3) received
I/wpa_supplicant( 1351): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1351): wlan0: Scan completed in 2.155298 seconds
D/wpa_supplicant( 1351): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1351): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1351): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1351): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
I/wpa_supplicant( 1351): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-50
I/wpa_supplicant( 1351): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1351): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-79
I/wpa_supplicant( 1351): [NULL] 9e:93:4e:3e:ba:c5 freq=2437 level=-85
D/wpa_supplicant( 1351): wlan0: BSS: Start scan result update 5
D/wpa_supplicant( 1351): BSS: last_scan_res_used=4/32
D/wpa_supplicant( 1351): wlan0: Scan-only results received
D/wpa_supplicant( 1351): wlan0: Radio work 'scan'@0x5571f5a680 done in 2.156169 seconds
E/WifiMonitor(  959): WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor(  959): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
E/WifiStateMachine(  959): handleMessage: E msg.what=147461
E/WifiStateMachine(  959): processMsg: ConnectedState
E/WifiStateMachine(  959):  ConnectedState !SCAN_RESULTS_EVENT 0 0 found=5 known=1 got=5 bcn=0
E/WifiStateMachine(  959): processMsg: L2ConnectedState
E/WifiStateMachine(  959):  L2ConnectedState !SCAN_RESULTS_EVENT 0 0 found=5 known=1 got=5 bcn=0
E/WifiStateMachine(  959): processMsg: ConnectModeState
E/WifiStateMachine(  959):  ConnectModeState !SCAN_RESULTS_EVENT 0 0 found=5 known=1 got=5 bcn=0
E/WifiStateMachine(  959): processMsg: DriverStartedState
E/WifiStateMachine(  959):  DriverStartedState !SCAN_RESULTS_EVENT 0 0 found=5 known=1 got=5 bcn=0
E/WifiStateMachine(  959): processMsg: SupplicantStartedState
E/WifiStateMachine(  959):  SupplicantStartedState !SCAN_RESULTS_EVENT 0 0 found=5 known=1 got=5 bcn=0
W/ContextImpl(  959): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:14146 com.android.server.wifi.WifiStateMachine.handleMediaLinkEvent:14311 com.android.server.wifi.WifiStateMachine.access$6000:268 com.android.server.wifi.WifiStateMachine$SupplicantStartedState.processMessage:8091 
D/WifiStateMachine(  959): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
W/WifiHW  (  959): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1351): wlan0: Control interface command 'LIST_DONGLES'
E/WifiStateMachine(  959): [1,454,523,171,478 ms] noteScanEnd no scan source
W/WifiHW  (  959): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/wpa_supplicant( 1351): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
E/WifiStateMachine(  959): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@7cf0a4 sup_state=COMPLETED debouncing=false
E/WifiAutoJoinController (  959): NG7005g c0:ff:d4:d3:aa:4a rssi=-50 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiAutoJoinController (  959): NG700 c0:ff:d4:d3:aa:48 rssi=-57 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiConfigStore(  959): updateSavedNetworkHistory(): try "NG700"WPA_PSK SSID="NG700" NG700 [WPA2-PSK-CCMP][WPS][ESS] ajst=0
E/WifiConfigStore(  959): updateSavedNetworkHistory: HTC improve mode
E/WifiConfigStore(  959):         got known scan result c0:ff:d4:d3:aa:48 key : "NG700"WPA_PSK num: 1 rssi=-57 freq=2412
E/WifiAutoJoinController (  959): 01ABC c2:ff:d4:d3:aa:48 rssi=-57 cap [WPA2-PSK-CCMP][ESS] is not scored
E/WifiAutoJoinController (  959): Gonzos 38:f8:89:11:e9:11 rssi=-79 cap [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS] is not scored
E/WifiAutoJoinController (  959): DIRECT-qjWorkCentre 3025 9e:93:4e:3e:ba:c5 rssi=-85 cap [WPA2-PSK-CCMP][WPS-AUTH][ESS][P2P] is not scored
E/WifiAutoJoinController (  959): ageScanResultsOut delay 40000 size 5 now 1454523171481
E/WifiAutoJoinController (  959): newSupplicantResults size=5 known=1 true
W/WifiHW  (  959): QCOM Debug wifi_send_command "IFNAME=wlan0 STATUS-NO_EVENTS"
D/wpa_supplicant( 1351): wlan0: Control interface command 'STATUS-NO_EVENTS'
W/art     ( 6676): Attempt to remove local handle scope entry from IRT, ignoring
E/WifiAutoJoinController (  959): attemptAutoJoin() status=bssid=c0:ff:d4:d3:aa:48
E/WifiAutoJoinController (  959): ssid=NG700
E/WifiAutoJoinController (  959): id=0
E/WifiAutoJoinController (  959): mode=station
E/WifiAutoJoinController (  959): pairwise_cipher=CCMP
E/WifiAutoJoinController (  959): group_cipher=CCMP
E/WifiAutoJoinController (  959): key_mgmt=WPA2-PSK
E/WifiAutoJoinController (  959): wpa_state=COMPLETED
E/WifiAutoJoinController (  959): ip_address=192.168.1.130
E/WifiAutoJoinController (  959): p2p_device_address=92:e7:c4:e6:4c:f8
E/WifiAutoJoinController (  959): address=XX:XX:XX:XX:XX:XX
E/WifiAutoJoinController (  959): uuid=12345678-9abc-def0-1234-56789abcdef1 split=12
E/WifiAutoJoinController (  959): attemptAutoJoin() num recent config 1 current="NG700"WPA_PSK ---> suppNetId=0
E/WifiAutoJoinController (  959): attemptAutoJoin good candidate seen, bumped hard -> status=0 "NG700"WPA_PSK rssi=(-57,-127) num=(1,0)
E/WifiAutoJoinController (  959): attemptAutoJoin skip current candidate  0 key "NG700"WPA_PSK
E/WifiAutoJoinController (  959): attemptRoam: "NG700"WPA_PSK Found c0:ff:d4:d3:aa:48 rssi=-57 freq=2412 Current: c0:ff:d4:d3:aa:48
D/HtcWifiControlRoamOffload: (  959): roamCandidate: nullcurrentBSSID: c0:ff:d4:d3:aa:48
E/WifiStateMachine(  959): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiAutoJoinController (  959): Done attemptAutoJoin status=0
E/WifiConfigStore(  959):  writeKnownNetworkHistory() num networks:1 needWrite=false
E/WifiStateMachine(  959): handleMessage: X
D/WifiManager( 1814): getScanResults: Base Package Name=com.google.android.gms, uid=10024
D/libc    ( 4431): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
D/libc    ( 4431): [NET] android_getaddrinfofornet-, err=8
I/HtcModeClient( 3240): handler message = 4011
E/HtcModeClient( 3240): Check connection and retry 12 times.
W/AwContents( 6676): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 6676): CordovaWebView is running on device made by: HTC
W/art     ( 6676): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6676): Attempt to remove local handle scope entry from IRT, ignoring
D/libc    ( 4431): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
D/libc    ( 4431): [NET] android_getaddrinfofornet-, err=8
W/chromium( 6676): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
D/libc    ( 4431): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
D/libc    ( 4431): [NET] android_getaddrinfofornet-, err=8
I/CheckinTask( 4431): Sending checkin request (8442 bytes)
D/FindExtension( 6676): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
I/InputMethodManager( 6676): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@2228d54, mServedView=org.apache.cordova.engine.SystemWebView{12bdf4fd VFEDH.C. .F....I. 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@143495f2
I/InputMethodManagerService(  959): Disable input method client, pid=1547
D/StatusBarManagerService(  959): swetImeWindowStatus vis=0 backDisposition=0
I/InputMethodManagerService(  959): Enable input method client, pid=6676
D/PMS     (  959): releaseWL(160f8758): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
I/ActivityManager(  959): Displayed com.test.thalitest/.MainActivity: +943ms
I/PhoneStatusBar( 1218): setImeWindowStatus(false,false)
W/XT9_C   ( 1391): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1391): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1391): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1391): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
W/BindingManager( 6676): Cannot call determinedVisibility() - never saw a connection for the pid: 6676
D/JsMessageQueue( 6676): Set native->JS mode to OnlineEventsBridgeMode
I/CheckinRequestBuilder( 4431): Checkin reason type: 11 attempt count: 1
I/ActivityManager(  959): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 4431): Failed to find provider info for com.google.android.wearable.settings
D/jxcore_app_log( 6676): JniHelper::setJavaVM(0xab0678f8), pthread_self() = -1405699840
I/GLSUser ( 1936): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
I/GLSUser ( 1936): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1936): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1936): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1936): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/WifiTrafficPoller(  959): TRAFFIC_STATS_POLL true Token 11 num clients 6
E/WifiTrafficPoller(  959):  packet count Tx=224 Rx=301
D/WIFI_ICON( 1218): WifiActivity: 3
E/WifiTrafficPoller(  959): notifying of data activity 3
D/StatusBar.NetworkController( 1218): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
D/DotMatrix( 1304): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
W/CheckinRequestBuilder( 4431): awaiting user notification for token
D/DotMatrix( 1304): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
I/RemoteViews( 1218): reapply : com.google.android.gms 4 40
I/chromium( 6676): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
I/CheckinRequestBuilder( 4431): Classify the device as Phone.
I/CheckinTask( 4431): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
I/CheckinService( 4431): Checking schedule, now: 1454523172267 next: 1455060004260
I/CheckinService( 4431): active receiver: disabled
I/PackageManager(  959):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=4431, uid=10024, userID:0
D/PMS     (  959): releaseWL(22a50e0d): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10024 com.google.android.gms}
I/ActivityManager(  959): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=6736 uid=10077 gids={50077, 9997, 3003} abi=arm64-v8a
D/PhoneMonitor( 6736): Register our PhoneStateListener
V/SetupWizard( 6736): Connected to Gservices successfully
D/ChimeraCfgMgr( 4431): Loading module com.google.android.gms.kids from APK com.google.android.gms
I/Kids    ( 4431): [GCoreUtils] Current gmscore version, 7899448 is smaller than the required version 8400000
D/PhoneMonitor( 6736): onServiceStateChanged state="3 3 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1EriInd= -1EriMode= -1RadioPowerSv: false EmergOnly=false PhoneType: 1 VoiceRoaming: false DataRoaming: false IMSRegState: -1" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_POWER_OFF(3) D:STATE_POWER_OFF(3) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
D/PhoneMonitor( 6736): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_POWER_OFF(3) D:STATE_POWER_OFF(3) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
D/GCM     ( 1936): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/PMS     (  959): releaseHCC(bfd06c): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null,
D/PMS     (  959): releaseHCC(22b4d635): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,W/jxcore-log( 6676): Initializing JXcore engine
,W/jxcore-log( 6676): JXcore engine is ready
,E/WifiTrafficPoller(  959): TRAFFIC_STATS_POLL true Token 11 num clients 6,
E/WifiTrafficPoller(  959):  packet count Tx=224 Rx=302
D/WIFI_ICON( 1218): WifiActivity: 1
E/WifiTrafficPoller(  959): notifying of data activity 1
D/StatusBar.NetworkController( 1218): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,W/jxcore-log( 6676): Starting JXcore engine,
,W/jxcore-log( 6676): Platform android,
W/jxcore-log( 6676): 
W/jxcore-log( 6676): Process ARCH arm
W/jxcore-log( 6676): 
,E/WifiStateMachine(  959): handleMessage: E msg.what=131155,
E/WifiStateMachine(  959): processMsg: ConnectedState
,E/WifiStateMachine(  959):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=1.2 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1470739974] gl hn u24 rssi=-52 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  959): processMsg: L2ConnectedState
E/WifiStateMachine(  959):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.4, 0.0, 0.0  rx=1.2 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1470739972] gl hn u24 rssi=-52 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  959):  get link layer stats 0
W/WifiHW  (  959): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1351): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1351): environment dirty rate=5 [17][1][0]
E/WifiStateMachine(  959): fetchRssiLinkSpeedAndFrequencyNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  959): fetchRssiLinkSpeedAndFrequencyNative rssi=-57 linkspeed=72,
E/WifiConfigStore(  959): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-57 "NG700"WPA_PSK
D/WIFI_ICON( 1218): updateWifiState: RSSI_CHANGED 3 -> 3
E/WifiStateMachine(  959): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=8.71 txretriesrate=0.00 rxrate=7.58 userTriggerdPenalty0
D/StatusBar.NetworkController( 1218): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
E/WifiStateMachine(  959):  good link -> stuck count =0
,E/WifiStateMachine(  959):  badRSSI count0 lowRSSI count0 --> score 60
E/WifiStateMachine(  959):  isHighRSSI       ---> score=65
D/WifiWatchdogStateMachine(  959): RSSI current: 3 new: -57, 3
E/WifiStateMachine(  959): handleMessage: X
,I/jxcore-log( 6676): JXcore Cordova bridge is ready!,
I/jxcore-log( 6676): 
W/jxcore-log( 6676): JXcore engine is started
,E/WifiDataStallTracker(  959): DATA_MONITOR_POLL true Token 1
,D/WifiDataStallTracker(  959): updateDataStallInfo: mDataStallTxRxSum={txSum=204 rxSum=185} preTxRxSum={txSum=187 rxSum=172}
,D/WifiDataStallTracker(  959): updateDataStallInfo: IN/OUT
D/WifiDataStallTracker(  959): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,I/jxcore-log( 6676): Toggling radios to true,
I/jxcore-log( 6676): 
,D/BluetoothAdapter( 6676): enable(): BT is already enabled..!,
,D/WifiService(  959): New client listening to asynchronous messages,
E/WifiTrafficPoller(  959): ADD_CLIENT: 7
D/WifiManager( 6676): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10366
,D/WifiService(  959): setWifiEnabled: true pid=6676, uid=10366
E/WifiService(  959): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  959): isSprintWifiRestricted(): false
W/Settings:Agent(  959): MONITOR_LOG
I/WifiService(  959): isMdmWifiRestricted(): false
W/Settings:Agent(  959): name: wifi_on
,W/Settings:Agent(  959): value: 2
W/Settings:Agent(  959): >> traceCallingStack()
W/Settings:Agent(  959): Process.myPid(): 959
W/Settings:Agent(  959): Process.myTid(): 1764
W/Settings:Agent(  959): Process.myUid(): 1000
W/Settings:Agent(  959): 
W/Settings:Agent(  959): 
,W/System.err(  959): java.lang.Throwable: stack dump,
,W/System.err(  959): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  959): ,	at android.provider.HtcISettings$Agent.traceCallingStack(HtcISettings.java:56)
W/System.err(  959): 	at android.provider.HtcISettingsGlobal$Agent.monitorKey(HtcISettingsGlobal.java:64)
W/System.err(  959): 	at android.provider.Settings$Global.putStringForUser(Settings.java:7422)
W/System.err(  959): 	at android.provider.Settings$Global.putString(Settings.java:7403)
W/System.err(  959): 	at android.provider.Settings$Global.putInt(Settings.java:7503)
W/System.err(  959): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:154)
W/System.err(  959): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:103)
W/System.err(  959): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:1144)
W/System.err(  959): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:222)
W/System.err(  959): 	at android.os.Binder.execTransact(Binder.java:454)
W/Settings:Agent(  959): 
W/Settings:Agent(  959): << traceCallingStack(): 24(ms)
D/WifiController(  959): handleMessage: E msg.what=155656
D/WifiManager( 6676): disconnect: Base Package Name=com.test.thalitest, uid=10366
D/WifiController(  959): processMsg: DeviceActiveState
D/WifiController(  959): processMsg: StaEnabledState
E/WifiStateMachine(  959): handleMessage: E msg.what=131145
E/WifiStateMachine(  959): processMsg: ConnectedState
D/WifiManager( 6676): reconnect: Base Package Name=com.test.thalitest, uid=10366
E/WifiStateMachine(  959):  ConnectedState !CMD_DISCONNECT 0 0
D/WifiController(  959): handleMessage: X
E/WifiStateMachine(  959): processMsg: L2ConnectedState
E/WifiStateMachine(  959):  L2ConnectedState !CMD_DISCONNECT 0 0
W/WifiHW  (  959): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
D/wpa_supplicant( 1351): wlan0: Control interface command 'DISCONNECT'
D/wpa_supplicant( 1351): wlan0: Cancelling scan request
D/wpa_supplicant( 1351): wlan0: Request to deauthenticate - bssid=c0:ff:d4:d3:aa:48 pending_bssid=00:00:00:00:00:00 reason=3 state=COMPLETED
D/wpa_supplicant( 1351): TDLS: Tear down peers
D/wpa_supplicant( 1351): wpa_driver_nl80211_disconnect(reason_code=3)
I/jxcore-log( 6676): Radios toggled
I/jxcore-log( 6676): 
I/jxcore-log( 6676): My device name is: HTC-HTC One M8s
I/jxcore-log( 6676): 
,D/wpa_supplicant( 1351): wlan0: Event DEAUTH (12) received
D/wpa_supplicant( 1351): wlan0: Deauthentication notification
D/wpa_supplicant( 1351): wlan0:  * reason 3 (locally generated)
D/wpa_supplicant( 1351): Deauthentication frame IE(s) - hexdump(len=0): [NULL]
I/wpa_supplicant( 1351): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1351): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/wpa_supplicant( 1351): enter disconnect check
I/wpa_supplicant( 1351): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/wpa_supplicant( 1351): wlan0: Auto connect disabled: do not try to re-connect
D/wpa_supplicant( 1351): wlan0: Ignore connection failure indication since interface has been put into disconnected state
D/Tethering(  959): interfaceLinkStateChanged wlan0, false
D/WifiMonitor(  959): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412]
,E/WifiMonitor(  959): WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/WifiMonitor(  959): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  959): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/Tethering(  959): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  959): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiMonitor(  959): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
D/Tethering(  959): TetherInterfaceSM: wlan0: InitialState processMessage what=CMD_INTERFACE_DOWN
V/Tethering(  959): TetherInterfaceSM: wlan0: exit InitialState
V/Tethering(  959): TetherInterfaceSM: wlan0: enter UnavailableState
D/PMS     (  959): acquireWL(3cabdd00): PARTIAL_WAKE_LOCK  NetworkStats 0x1 959 1000 null
E/WifiStateMachine(  959): WiFiDisplay: getWifidisplayApEnabled=false
D/UsbDeviceManager(  959): [USBNET] bCheckSuppFunc: cdc_network
D/Tethering(  959): interfaceLinkStateChanged wlan0, false
D/Tethering(  959): sendTetherStateChangedBroadcast 0, 0, 0
D/UsbnetService(  959): BroadcastReceiver::onReceive+
D/wpa_supplicant( 1351): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1351): wlan0: Disconnect event - remove keys
D/wpa_supplicant( 1351): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/WifiDisplayAdapter(  959): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  959):     Client/Owner: Client
D/WifiDisplayAdapter(  959):     GroupId: 
D/WifiDisplayAdapter(  959):     Passphrase: 
D/WifiDisplayAdapter(  959):     SessionId: 0
D/WifiDisplayAdapter(  959):     IP Address: }
D/wpa_supplicant( 1351): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1351): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x5571f57f88 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1351):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1351): wlan0: State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1351): nl80211: Set wlan0 operstate 1->0 (DORMANT)
D/wpa_supplicant( 1351): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 1351): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1351): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1351): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1351): nl80211: Skip set_supp_port(unauthorized) while not associated
D/wpa_supplicant( 1351): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1351): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1351): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1351): wlan0: State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1351): nl80211: Set wlan0 operstate 0->0 (DORMANT)
D/WifiMonitor(  959): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/wpa_supplicant( 1351): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 1351): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1351): EAPOL: External notification - portValid=0
E/WifiMonitor(  959): WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700,
D/HTCRequest(  959): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  959): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/wpa_supplicant( 1351): RTM_NEWLINK: ifi_index=29 ifname=wlan0 operstate=2 linkmode=1 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1351): Wireless event: cmd=0x8b15 len=24
D/wpa_supplicant( 1351): RTM_NEWLINK: ifi_index=29 ifname=wlan0 wext ifi_flags=0x1043 ([UP][RUNNING])
D/HTCRequest(  959): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/wpa_supplicant( 1351): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1351): nl80211: Ignore disconnect event triggered during reassociation
E/WifiStateMachine(  959): transitionTo: destState=DisconnectingState
E/WifiStateMachine(  959): handleMessage: new destination call exit/enter
E/WifiStateMachine(  959): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
E/WifiStateMachine(  959): invokeExitMethods: ConnectedState
D/WifiMonitor(  959): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
E/WifiStateMachine(  959): WifiStateMachine: Leaving Connected state
D/WifiPerfLock(  959): release()
E/WifiStateMachine(  959): PerfLock released for exiting ConnectedState
E/WifiStateMachine(  959): setScanAlarm false period 20000 initial delay 0mAlarmEnabledtrue
D/UsbnetService(  959): ACTION_TETHER_STATE_CHANGED: active=[],USB_FUNCTION_NCM=false
D/UsbnetService(  959): BroadcastReceiver::onReceive-
D/Tethering(  959): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  959): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiStateMachine(  959): invokeExitMethods: L2ConnectedState
E/WifiStateMachine(  959): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$13400 - exit - invokeExitMethods
E/WifiStateMachine(  959): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  959): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  959): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
W/WifiHW  (  959): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1351): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1351): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1351): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
,W/WifiHW  (  959): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1351): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1351): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 1351): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1351): CTRL_IFACE: SAVE_CONFIG - Configuration updated
E/WifiStateMachine(  959): setSuspendOptimizationsNative: 1 true -want false stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
W/WifiHW  (  959): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
D/wpa_supplicant( 1351): wlan0: Control interface command 'DRIVER POWERMODE 0'
I/wpa_supplicant( 1351): Power_Mode_Type mode = 0
I/wpa_supplicant( 1351): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
W/WifiHW  (  959): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
D/wpa_supplicant( 1351): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/wpa_supplicant( 1351): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 8192
D/WifiDataStallTracker(  959): setDhcpActive: false
,D/WifiP2pService(  959): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  959): P2pEnabledState{ when=-4ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
V/NativeCrypto( 1936): Read error: ssl=0x557adeeef0: I/O error during system call, Connection timed out
D/libc    (  959): [NET] android_getaddrinfofornet+,hn 13(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  959): [NET] android_getaddrinfofornet-, SUCCESS
D/PMS     (  959): acquireWL(20834939): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1936 10024 WorkSource{10024 com.google.android.gms}
,E/WifiStateMachine(  959): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
,E/WifiStateMachine(  959): setDetailed state send new extra info<unknown ssid>
E/WifiStateMachine(  959): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/libc    (  959): [NET] android_getaddrinfofornet+,hn 6,sn(),hints(known),family 0,flags 4
D/libc    (  959): [NET] android_getaddrinfofornet-, SUCCESS
D/ConnectivityService(  959): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
E/WifiStateMachine(  959): NetworkAgent != null
E/WifiStateMachine(  959): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,E/WifiTrafficPoller(  959): ENABLE_TRAFFIC_STATS_POLL true Token 11
E/WifiTrafficPoller(  959):  packet count Tx=224 Rx=302
V/NetworkPolicy(  959): mWifiStateReceiver: meteredHint=false,EPS mode=false
E/WifiTrafficPoller(  959): notifying of data activity 0
D/libc    (  959): [NET] android_getaddrinfofornet+,hn 25(0x666538303a3a39),sn(),hints(known),family 0,flags 4
D/libc    (  959): [NET] android_getaddrinfofornet-, SUCCESS
I/IntentController( 1218): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  959): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WifiDataStallTracker(  959): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WIFI_ICON( 1218): updateWifiState: NETWORK_STATE_CHANGED connected
D/WifiDataStallTracker(  959): stopDataStallAlarm 
D/StatusBar.NetworkController( 1218): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
E/WifiTrafficPoller(  959): ENABLE_TRAFFIC_STATS_POLL false Token 12
D/WIFI_ICON( 1218): WifiActivity: 0
E/WifiDataStallTracker(  959): ENABLE_DATA_MONITOR_POLL false Token 1
D/StatusBar.NetworkController( 1218): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
I/IntentController( 1218): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  959): autoRoamSetBSSID any key="NG700"WPA_PSK
E/WifiConfigStore(  959): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
W/WifiHW  (  959): QCOM Debug skip set_network part for security concern!
V/NativeCrypto( 1936): SSL shutdown failed: ssl=0x557adeeef0: I/O error during system call, Broken pipe
E/WifiTrafficPoller(  959): ENABLE_TRAFFIC_STATS_POLL false Token 13
D/wpa_supplicant( 1351): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1351): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1351): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  959): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1351): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1351): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 1351): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1351): CTRL_IFACE: SAVE_CONFIG - Configuration updated
E/WifiStateMachine(  959): moveTempStackToStateStack: i=0,j=4
E/WifiStateMachine(  959): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectingState
I/IntentController( 1218): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  959): invokeEnterMethods: DisconnectingState
E/WifiStateMachine(  959):  Enter DisconnectingState State scan interval 300000 mEnableBackgroundScan= false screenOn=true
E/WifiStateMachine(  959): Start Disconnecting Watchdog 1
E/WifiStateMachine(  959): handleMessage: X
E/WifiStateMachine(  959): handleMessage: E msg.what=131146
E/WifiStateMachine(  959): processMsg: DisconnectingState
D/TetherSettings( 6390): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 6390): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 6390): Cust_ConnectToPC   : Modem_Link>false
D/        ( 6390): Cust_ConnectToPC   : spcsc>false
D/        ( 6390): Cust_ConnectToPC   : IPT>true
D/        ( 6390): Cust_ConnectToPC   : Singel_USB>false
E/WifiStateMachine(  959):  DisconnectingState !CMD_RECONNECT 0 0
E/WifiStateMachine(  959): processMsg: ConnectModeState
,E/WifiStateMachine(  959):  ConnectModeState !CMD_RECONNECT 0 0
D/ConnectivityService(  959): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10024
W/WifiHW  (  959): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
D/PMS     (  959): releaseWL(3cabdd00): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/wpa_supplicant( 1351): wlan0: Control interface command 'RECONNECT'
V/NetworkPolicy(  959): updateNetworkEnabledLocked()
D/wpa_supplicant( 1351): wlan0: Selecting BSS from priority group 609
V/NetworkPolicy(  959): updateNotificationsLocked()
D/wpa_supplicant( 1351): wlan0: 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 caps=0x511 level=-50 wps
D/wpa_supplicant( 1351): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1351): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 1351): wlan0: 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-57 wps
D/wpa_supplicant( 1351): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1351): wlan0:    selected based on RSN IE
W/wpa_supplicant( 1351): [EAP-MSG] EAP wpa_supplicant_check_sim@842: eap_methods not available
D/wpa_supplicant( 1351):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
D/wpa_supplicant( 1351): wlan0:    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700'
D/wpa_supplicant( 1351): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: DISCONNECTED  ssid=0x5571f59c00  current_ssid=0x0
D/wpa_supplicant( 1351): wlan0: Request association with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1351): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1351): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=7): 00 05 4e 47 37 30 30
D/wpa_supplicant( 1351): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 03 01 01
D/wpa_supplicant( 1351): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 2a 01 00
D/wpa_supplicant( 1351): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 08 04 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1351): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 1351): WPA: WMM Parameter Element - hexdump(len=24): 00 50 f2 02 01 01 80 00 03 a4 00 00 27 a4 00 00 42 43 5e 00 62 32 2f 00
D/wpa_supplicant( 1351): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1351): TDLS: TDLS is allowed in the target BSS
D/wpa_supplicant( 1351): wlan0: Add radio work 'connect'@0x5571f5a680
D/wpa_supplicant( 1351): wlan0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1351): wlan0: Starting radio work 'connect'@0x5571f5a680 after 0.000083 second wait
I/wpa_supplicant( 1351): check if in concurrent case
I/wpa_supplicant( 1351): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/WifiMonitor(  959): Event [IFNAME=wlan0 Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)]
E/WifiMonitor(  959): WifiMonitor:wlan0 cnt=35 dispatchEvent: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
W/Settings( 6390): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/WifiStateMachine(  959): handleMessage: X
E/WifiStateMachine(  959): handleMessage: E msg.what=147460
E/WifiStateMachine(  959): processMsg: DisconnectingState
D/WifiDisplayAdapter(  959): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  959):     Client/Owner: Client
D/WifiDisplayAdapter(  959):     GroupId: 
D/WifiDisplayAdapter(  959):     Passphrase: 
D/WifiDisplayAdapter(  959):     SessionId: 0
D/WifiDisplayAdapter(  959):    , IP Address: }
E/WifiStateMachine(  959):  DisconnectingState !NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=103666
E/WifiStateMachine(  959): processMsg: ConnectModeState
D/wpa_supplicant( 1351): FT: Stored MDIE and FTIE from (Re)Association Response - hexdump(len=0):
D/wpa_supplicant( 1351): wlan0: Cancelling scan request
D/wpa_supplicant( 1351): wpas_start_assoc_cb, 1892
D/wpa_supplicant( 1351): wpas_start_assoc_cb, 1895
D/wpa_supplicant( 1351): wpas_start_assoc_cb, 1910
D/wpa_supplicant( 1351): wlan0: WPA: clearing own WPA/RSN IE
D/wpa_supplicant( 1351): wlan0: Automatic auth_alg selection: 0x1
E/WifiStateMachine(  959):  ConnectModeState !NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=103667
D/wpa_supplicant( 1351): RSN: PMKSA cache search - network_ctx=0x5571f59c00 try_opportunistic=0
D/wpa_supplicant( 1351): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1351): RSN: No PMKSA cache entry found
D/wpa_supplicant( 1351): wlan0: RSN: using IEEE 802.11i/D9.0
E/WifiStateMachine(  959): ConnectModeState: Network connection lost 
D/wpa_supplicant( 1351): wlan0: WPA: Selected cipher suites: group 16 pairwise 16 key_mgmt 2 proto 2
E/WifiStateMachine(  959): transitionTo: destState=DisconnectedState
D/wpa_supplicant( 1351): wlan0: WPA: Selected mgmt group cipher 32
D/wpa_supplicant( 1351): wlan0: WPA: clearing AP WPA IE
D/WIFI_ICON( 1218): updateWifiState: NETWORK_STATE_CHANGED disconnected
E/WifiStateMachine(  959): handleMessage: new destination call exit/enter
D/wpa_supplicant( 1351): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1351): wlan0: WPA: using GTK CCMP
D/wpa_supplicant( 1351): wlan0: WPA: using PTK CCMP
E/WifiStateMachine(  959): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/wpa_supplicant( 1351): wlan0: WPA: using KEY_MGMT WPA-PSK
D/StatusBar.NetworkController( 1218): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiStateMachine(  959): invokeExitMethods: DisconnectingState
D/wpa_supplicant( 1351): wlan0: WPA: not using MGMT group cipher
E/WifiStateMachine(  959): moveTempStackToStateStack: i=0,j=4
D/WIFI_ICON( 1218): updateWifiState: NETWORK_STATE_CHANGED disconnected
E/WifiStateMachine(  959): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectedState
D/StatusBar.NetworkController( 1218): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  959): ValidatedState{ when=0 what=532488 arg1=10024 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1351): WPA: Set own WPA IE default - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
E/WifiStateMachine(  959): invokeEnterMethods: DisconnectedState
E/WifiStateMachine(  959): DisconnectedState call setCountryCode()
D/wpa_supplicant( 1351): wlan0: State: DISCONNECTED -> ASSOCIATING
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  959): DefaultState{ when=0 what=532488 arg1=10024 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1351): nl80211: Set wlan0 operstate 0->0 (DORMANT)
D/wpa_supplicant( 1351): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
E/WifiStateMachine(  959):  Enter disconnected State scan interval 300000 mEnableBackgroundScan= false screenOn=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  959): Forcing reevaluation
W/WifiHW  (  959): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN TYPE=ONLY"
D/wpa_supplicant( 1351): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  959): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1351): nl80211: Set mode ifindex 29 iftype 2 (STATION)
D/NetworkMonitorNetworkAge,ntInfo [WIFI () - null](  959): Validated
D/wpa_supplicant( 1351): nl80211: Unsubscribe mgmt frames handle 0x888888ddf97d1989 (mode change)
D/wpa_supplicant( 1351): nl80211: Subscribe to mgmt frames with non-AP handle 0x5571f59100
D/wpa_supplicant( 1351): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5571f59100 match=0104
D/wpa_supplicant( 1351): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5571f59100 match=040a
D/wpa_supplicant( 1351): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5571f59100 match=040b
D/wpa_supplicant( 1351): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5571f59100 match=040c
D/ConnectivityService(  959): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
D/wpa_supplicant( 1351): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5571f59100 match=040d
D/wpa_supplicant( 1351): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5571f59100 match=090a
D/WifiMonitor(  959): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
D/wpa_supplicant( 1351): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5571f59100 match=090b
D/wpa_supplicant( 1351): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5571f59100 match=090c
D/wpa_supplicant( 1351): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5571f59100 match=090d
E/WifiMonitor(  959): WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  959): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/wpa_supplicant( 1351): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5571f59100 match=0409506f9a09
D/HTCRequest(  959): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/wpa_supplicant( 1351): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5571f59100 match=7f506f9a09
D/wpa_supplicant( 1351): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5571f59100 match=0801
D/wpa_supplicant( 1351): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5571f59100 match=040e
D/wpa_supplicant( 1351): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5571f59100 match=06
D/PMS     (  959): releaseWL(20834939): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms}
D/wpa_supplicant( 1351): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5571f59100 match=0a07
D/wpa_supplicant( 1351): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5571f59100 match=0a11
D/wpa_supplicant( 1351): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5571f59100 match=0a1a
D/wpa_supplicant( 1351): nl80211: Connect (ifindex=29)
D/wpa_supplicant( 1351):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1351):   * bssid_hint=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1351):   * freq=2412
D/wpa_supplicant( 1351):   * freq_hint=2412
D/wpa_supplicant( 1351):   * SSID - hexdump(len=5): 4e 47 37 30 30
D/wpa_supplicant( 1351):   * IEs - hexdump(len=30): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00 7f 06 00 00 0a 82 00 40
D/wpa_supplicant( 1351):   * WPA Versions 0x2
D/wpa_supplicant( 1351):   * pairwise=0xfac04
D/wpa_supplicant( 1351):   * group=0xfac04
D/wpa_supplicant( 1351):   * akm=0xfac02
D/wpa_supplicant( 1351):   * Auth Type 0
D/wpa_supplicant( 1351): nl80211: set key mgmt offload, suite 2, support 0x0, psk 0x0x5571f59c3a
E/SmartNS_Utility( 6390): hasRemovableStorageSlot: true
D/SmartNS_Utility( 6390): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/wpa_supplicant( 1351): nl80211: Connect request send successfully
D/wpa_supplicant( 1351): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 1351): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1351): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1351): EAPOL: External notification - portControl=Auto
D/SmartNS_NSReceiver( 6390): onReceive : android.net.conn.TETHER_STATE_CHANGED hasTethered:false isNSOpening:false
D/wpa_supplicant( 1351): wlan0: Control interface command 'SCAN TYPE=ONLY'
D/wpa_supplicant( 1351): Ongoing scan action - reject new request
E/WifiStateMachine(  959): setScanAlarm true period 10000 initial delay 3000mAlarmEnabledfalse
E/WifiStateMachine(  959): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiStateMachine(  959): handleMessage: X
E/WifiStateMachine(  959): handleMessage: E msg.what=131101
E/WifiStateMachine(  959): processMsg: DisconnectedState
D/HTCRequest(  959): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  959): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =ASSOCIATING
E/WifiStateMachine(  959):  DisconnectedState !CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  959): processMsg: ConnectModeState
E/WifiStateMachine(  959):  ConnectModeState !CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  959): processMsg: DriverStartedState
E/WifiStateMachine(  959):  DriverStartedState !CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  959): processMsg: SupplicantStartedState
E/WifiStateMachine(  959):  SupplicantStartedState !CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  959): processMsg: DefaultState
E/WifiStateMachine(  959):  DefaultState !CMD_TETHER_STATE_CHANGE 0 0
D/WifiStateMachine(  959): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  959): Default got CMD_TETHER_STATE_CHANGE
E/WifiStateMachine(  959): handleMessage: X
E/WifiStateMachine(  959): handleMessage: E msg.what=147462
E/WifiStateMachine(  959): processMsg: DisconnectedState
E/WifiStateMachine(  959):  DisconnectedState !SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=103679  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine(  959): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine(  959): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  959): processMsg: ConnectModeState
E/WifiStateMachine(  959):  ConnectModeState !SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=103680  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine(  959): handleMessage: X
E/WifiStateMachine(  959): handleMessage: E msg.what=131212
E/WifiStateMachine(  959): processMsg: DisconnectedState
E/WifiStateMachine(  959):  DisconnectedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  959): processMsg: ConnectModeState
E/WifiStateMachine(  959):  ConnectModeState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  959): processMsg: DriverStartedState
E/WifiStateMachine(  959):  DriverStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  959): processMsg: SupplicantStartedState
E/WifiStateMachine(  959):  SupplicantStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  959): processMsg: DefaultState
E/WifiStateMachine(  959):  DefaultState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  959): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  959): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  959): handleMessage: X
E/WifiStateMachine(  959): handleMessage: E msg.what=131212
E/WifiStateMachine(  959): processMsg: DisconnectedState
E/WifiStateMachine(  959):  DisconnectedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  959): processMsg: ConnectModeState
E/WifiStateMachine(  959):  ConnectModeState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  959): processMsg: DriverStartedState
E/WifiStateMachine(  959):  DriverStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  959): processMsg: SupplicantStartedState
E/WifiStateMachine(  959):  SupplicantStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  959): processMsg: DefaultState
E/WifiStateMachine(  959):  DefaultState !CMD_UPDATE_LINKPROPERTIES 0 0
W/ContextImpl( 6390): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.NSReceiver.onReceive:432 android.app.ActivityThread.handleReceiver:2712 
E/WifiStateMachine(  959): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  959): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  959): handleMessage: X
D/WifiNetworkAgent(  959): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine(  959): handleMessage: E msg.what=131212
E/WifiStateMachine(  959): processMsg: DisconnectedState
E/WifiStateMachine(  959):  DisconnectedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  959): processMsg: ConnectModeState
I/SmartNS_Utility( 6390): setISNotification
E/WifiStateMachine(  959):  ConnectModeState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  959): processMsg: DriverStartedState
E/WifiStateMachine(  959):  DriverStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  959): processMsg: SupplicantStartedState
E/WifiStateMachine(  959):  SupplicantStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  959): processMsg: DefaultState
D/SmartNS_Utility( 6390): usb_cable_connect = 1
E/WifiStateMachine(  959):  DefaultState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  959): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  959): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  959): handleMessage: X
E/WifiStateMachine(  959): handleMessage: E msg.what=131213
E/WifiStateMachine(  959): processMsg: DisconnectedState
D/SmartNS_Utility( 6390): usb_denied = 0
E/WifiStateMachine(  959):  DisconnectedState !CMD_TARGET_BSSID 35 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=103692
E/WifiStateMachine(  959): processMsg: ConnectModeState
E/WifiStateMachine(  959):  ConnectModeState !CMD_TARGET_BSSID 35 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=103692
E/WifiStateMachine(  959): processMsg: DriverStartedState
E/WifiStateMachine(  959):  DriverStartedState !CMD_TARGET_BSSID 35 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=103692
E/WifiStateMachine(  959): processMsg: SupplicantStartedState
E/WifiStateMachine(  959):  SupplicantStartedState !CMD_TARGET_BSSID 35 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=103693
E/WifiStateMachine(  959): handleMessage: X
E/WifiStateMachine(  959): handleMessage: E msg.what=147462
E/WifiStateMachine(  959): processMsg: DisconnectedState
I/SmartNS_PSService( 6390): usb notificaiton:true
E/WifiStateMachine(  959):  DisconnectedState !SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=103693  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
E/WifiStateMachine(  959): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine(  959): setDetailed state, old =DISCONNECTED and new state=CONNECTING hidden=false
E/WifiStateMachine(  959): setDetailed state send new extra info"NG700"
E/WifiStateMachine(  959): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiStateMachine(  959): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: DISCONNECTED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
E/WifiStateMachine(  959): NetworkAgent == null
E/WifiStateMachine(  959): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTING wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: DISCONNECTED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
E/WifiStateMachine(  959): processMsg: ConnectModeState
E/WifiStateMachine(  959):  ConnectModeState !SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=103696  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
E/WifiStateMachine(  959): handleMessage: X
E/WifiTrafficPoller(  959): ENABLE_TRAFFIC_STATS_POLL false Token 14
E/WifiTrafficPoller(  959): ENABLE_TRAFFIC_STATS_POLL false Token 15
D/WIFI_ICON( 1218): updateWifiState: NETWORK_STATE_CHANGED disconnected
I/IntentController( 1218): receive(android.net.wifi.STATE_CHANGE,1,false)
D/StatusBar.NetworkController( 1218): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
I/IntentController( 1218): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WIFI_ICON( 1218): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1218): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
I/ActionCombine( 6390): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal]
I/QuickSettingWifi( 1218): receive.wifiConnect:true wifiAPname:<unknown ssid> elapse:1
D/SmartNS_Utility( 6390): usb_cable_connect = 1
D/SmartNS_Utility( 6390): usb_denied = 0
I/SmartNS_PSService( 6390): usb notificaiton:true
E/WifiStateMachine(  959): WiFiDisplay: getWifidisplayApEnabled=false
I/QuickSettingWifi( 1218): receive.wifiConnect:false wifiAPname:null elapse:7
I/QuickSettingWifi( 1218): receive.wifiConnect:false wifiAPname:null elapse:0
I/RemoteViews( 1218): reapply : com.android.settings 0 36
D/DotMatrix( 1304): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
,D/SmartNS_NSReceiver( 6390): Tethered state change:false isNSOpening:false
D/DotMatrix( 1304): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
I/RemoteViews( 1218): reapply : com.android.settings 1 36
D/WISPrService( 6390): >>>>>WISPrService start isConnected = true<<<<<
D/WifiService(  959): New client listening to asynchronous messages
E/WifiTrafficPoller(  959): ADD_CLIENT: 8
I/QuickSettingWifi( 1218): receive.wifiConnect:false wifiAPname:null elapse:0
I/QuickSettingWifi( 1218): receive.wifiConnect:false wifiAPname:null elapse:0
E/WifiStateMachine(  959): handleMessage: E msg.what=131131
E/WifiStateMachine(  959): processMsg: DisconnectedState
E/WifiStateMachine(  959):  DisconnectedState !CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine(  959): processMsg: ConnectModeState
E/WifiStateMachine(  959):  ConnectModeState !CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine(  959): handleMessage: X
,W/WISPrService( 6390): can not find out wificonfig: SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/ConnectivityService(  959): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/WISPrService( 6390): trigger connection
D/ConnectivityService(  959):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WISPrService( 6390): continue
D/ConnectivityService(  959):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1218): CM callback handler got msg 524292
D/ConnectivityService(  959): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  959): ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/Nat464Xlat(  959): requiresClat: netType=1, connected=false, mIsClatEnabled=true, hasIPv4Address=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  959): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,D/ConnectivityService(  959): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  959): Disconnected - quitting
D/ConnectivityService(  959): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isSkipMobile=false
D/WIFI    (  959): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkManagementService(  959): Removing idletimer
D/usbnet  (  959): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  959):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/usbnet  (  959):   my score=70, my filter=[ Transports:  Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/WIFI    (  959): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] released
D/usbnet  (  959): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
E/WifiStateMachine(  959): enter WifiNetworkFactory startNetwork. mIPTStart:false
I/SecurityController( 1218): onLost 100
,D/wpa_supplicant( 1351): Wireless event: cmd=0x8c02 len=271,
I/wpa_supplicant( 1351): WEXT: Custom wireless event: 'BEACONIEs='
D/wpa_supplicant( 1351): RTM_NEWLINK: ifi_index=29 ifname=wlan0 wext ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1351): Wireless event: cmd=0x8c02 len=152
I/wpa_supplicant( 1351): WEXT: Custom wireless event: 'BEACONIEs='
D/wpa_supplicant( 1351): RTM_NEWLINK: ifi_index=29 ifname=wlan0 wext ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1351): Wireless event: cmd=0x8b15 len=24
D/wpa_supplicant( 1351): RTM_NEWLINK: ifi_index=29 ifname=wlan0 wext ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1351): RTM_NEWLINK: ifi_index=29 ifname=wlan0 operstate=5 linkmode=1 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1351): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1351): nl80211: Connect event
D/wpa_supplicant( 1351): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1351): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1351): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
D/wpa_supplicant( 1351): wlan0: Event ASSOC (0) received
D/wpa_supplicant( 1351): wlan0: Association info event
D/wpa_supplicant( 1351): req_ies - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1351): resp_ies - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1351): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1351): wlan0: freq=2412 MHz
D/wpa_supplicant( 1351): WPA: set own WPA/RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1351): FT: Stored MDIE and FTIE from (Re)Association Response - hexdump(len=0):
D/wpa_supplicant( 1351): wlan0: State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1351): nl80211: Set wlan0 operstate 0->0 (DORMANT)
D/wpa_supplicant( 1351): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 1351): wlan0: Associated to a new BSS: BSSID=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1351): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 1351): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
I/wpa_supplicant( 1351): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1351): wlan0: WPA: Association event - clear replay counter
D/wpa_supplicant( 1351): wlan0: WPA: Clear old PTK
D/wpa_supplicant( 1351): TDLS: Remove peers on association
D/wpa_supplicant( 1351): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1351): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1351): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1351): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1351): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1351): EAPOL: enable timer tick
D/WifiMonitor(  959): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
D/wpa_supplicant( 1351): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1351): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 1351): wlan0: Cancelling scan request
I/wpa_supplicant( 1351): htc_wext_set_keepalive +
D/WIFI_ICON( 1218): updateWifiState: NETWORK_STATE_CHANGED disconnected
I/wpa_supplicant( 1351): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/StatusBar.NetworkController( 1218): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/wpa_supplicant( 1351): getPrivFuncNum +	
I/wpa_supplicant( 1351): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1351): htc_wext_set_keepalive fnum = 0x8bf6
E/WifiMonitor(  959): WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  959): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
I/wpa_supplicant( 1351): htc_wext_set_keepalive - ret = 0
D/HTC,Request(  959): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/WISPrService( 6390): >>>>>WISPrService start isConnected = false<<<<<
D/wpa_supplicant( 1351): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1351): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 1351): wlan0: IEEE 802.1X RX: version=2 type=3 length=95
D/wpa_supplicant( 1351): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 1351): wlan0:   key_info 0x8a (ver=2 keyidx=0 rsvd=0 Pairwise Ack)
D/wpa_supplicant( 1351): wlan0:   key_length=16 key_data_length=0
D/wpa_supplicant( 1351):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 1351):   key_nonce - hexdump(len=32): 44 9f 43 a2 7f f2 85 4a bb a7 b2 1d 36 45 67 e4 a3 e5 cd f6 d5 c8 ce bd 3b 61 b7 b9 1d 28 c3 a6
D/wpa_supplicant( 1351):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/HTCRequest(  959): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/wpa_supplicant( 1351):   key_rsc - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1351):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1351):   key_mic - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1351): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1351): wlan0: WPA: RX message 1 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 1351): RSN: msg 1/4 key data - hexdump(len=0):
D/WifiMonitor(  959): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
D/WifiMonitor(  959): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412]
E/WifiMonitor(  959): WifiMonitor:wlan0 cnt=38 dispatchEvent: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  959): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  959): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  959): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/UsbDeviceManager(  959): [USBNET] bCheckSuppFunc: cdc_network
D/WISPrService( 6390): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/HTCRequest(  959): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/PMS     (  959): acquireWL(2807e671): PARTIAL_WAKE_LOCK  NetworkStats 0x1 959 1000 null
E/WifiStateMachine(  959): handleMessage: E msg.what=147462
E/WifiStateMachine(  959): processMsg: DisconnectedState
D/HTCRequest(  959): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  959): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  959): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  959): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  959): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/WifiMonitor(  959): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiStateMachine(  959):  DisconnectedState !SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=103772  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiMonitor(  959): WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine(  959): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
D/HTCRequest(  959): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine(  959): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
D/HTCRequest(  959): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine(  959): setDetailed state send new extra info0x
E/WifiStateMachine(  959,): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTING wifi info = SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/HTCRequest(  959): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/wpa_supplicant( 1351): WPA: Renewed SNonce - hexdump(len=32): b1 c1 8d 4b 41 ca ec fe 1a 6e 44 00 6a 61 4d c9 f2 ab 10 3b b2 5c d2 ca bb 8b 68 07 60 c4 e5 47
D/wpa_supplicant( 1351): WPA: Nonce1 - hexdump(len=32): b1 c1 8d 4b 41 ca ec fe 1a 6e 44 00 6a 61 4d c9 f2 ab 10 3b b2 5c d2 ca bb 8b 68 07 60 c4 e5 47
D/wpa_supplicant( 1351): WPA: Nonce2 - hexdump(len=32): 44 9f 43 a2 7f f2 85 4a bb a7 b2 1d 36 45 67 e4 a3 e5 cd f6 d5 c8 ce bd 3b 61 b7 b9 1d 28 c3 a6
D/wpa_supplicant( 1351): WPA: PMK - hexdump(len=32): [REMOVED]
D/wpa_supplicant( 1351): WPA: PTK - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 1351): WPA: WPA IE for msg 2/4 - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1351): WPA: Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 1351): wlan0: WPA: Sending EAPOL-Key 2/4
D/wpa_supplicant( 1351): WPA: KCK - hexdump(len=16): [REMOVED]
D/WifiMonitor(  959): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/wpa_supplicant( 1351): WPA: Derived Key MIC - hexdump(len=16): 8a e6 ae f9 e4 8b a4 bf b0 e4 66 8b 69 93 6e c1
E/WifiStateMachine(  959): processMsg: ConnectModeState
D/Tethering(  959): interfaceLinkStateChanged wlan0, false
D/Tethering(  959): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  959): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiTrafficPoller(  959): ENABLE_TRAFFIC_STATS_POLL false Token 16
E/WifiStateMachine(  959):  ConnectModeState !SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=103773  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
D/Tethering(  959): interfaceLinkStateChanged wlan0, false
D/Tethering(  959): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  959): handleMessage: X
E/WifiStateMachine(  959): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiStateMachine(  959): handleMessage: E msg.what=147500
E/WifiStateMachine(  959): processMsg: DisconnectedState
E/WifiStateMachine(  959):  DisconnectedState !what:147500 0 0
E/WifiStateMachine(  959): processMsg: ConnectModeState
E/WifiStateMachine(  959):  ConnectModeState !what:147500 0 0
D/WifiStateMachine(  959): Enter handleAssociatedWithEvent
D/WIFI_ICON( 1218): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/Tethering(  959): interfaceLinkStateChanged wlan0, false
D/StatusBar.NetworkController( 1218): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiStateMachine(  959): Associated
D/PMS     (  959): acquireWL(1ff9bc56): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 959 1000 null
D/Tethering(  959): interfaceStatusChanged wlan0, false
D/WISPrService( 6390): start DataConnection
E/WifiStateMachine(  959): WiFiDisplay: getWifidisplayApEnabled=false
D/CSLegacyTypeTracker(  959): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=false
D/libc    ( 6390): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 4
D/Tethering(  959): interfaceLinkStateChanged wlan0, true
D/Tethering(  959): interfaceStatusChanged wlan0, true
I/IntentController( 1218): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  959): WiFiDisplay: getWifidisplayApEnabled=false
D/WifiStateMachine(  959): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  959): Exit handleAssociatedWithEvent
E/WifiStateMachine(  959): handleMessage: X
E/WifiStateMachine(  959): handleMessage: E msg.what=147462
V/Tethering(  959): TetherInterfaceSM: wlan0: enter InitialState
E/WifiStateMachine(  959): processMsg: DisconnectedState
E/WifiStateMachine(  959): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiStateMachine(  959):  DisconnectedState !SUPPLICANT_STATE_CHANGE_EVENT 39 0 rt=103777  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
E/WifiStateMachine(  959): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  959): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
D/Tethering(  959): sendTetherStateChangedBroadcast 1, 0, 0
E/WifiStateMachine(  959): setDetailed state send new extra info"NG700"
E/WifiStateMachine(  959): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTING wifi info = SSID: NG700, BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: 0, Metered hint: false
D/libc    ( 6390): [NET] android_getaddrinfofornet-, err=8
D/ConnectivityService(  959): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/UsbnetService(  959): BroadcastReceiver::onReceive+
D/UsbnetService(  959): ACTION_TETHER_STATE_CHANGED: active=[],USB_FUNCTION_NCM=false
D/UsbnetService(  959): BroadcastReceiver::onReceive-
E/WifiStateMachine(  959): NetworkAgent == null
D/wpa_supplicant( 1351): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1351): wlan0: IEEE 802.1X RX: version=2 type=3 length=151
D/wpa_supplicant( 1351): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 1351): wlan0:   key_info 0x13ca (ver=2 keyidx=0 rsvd=0 Pairwise Install Ack MIC Secure Encr)
D/wpa_supplicant( 1351): wlan0:   key_length=16 key_data_length=56
D/wpa_supplicant( 1351):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 02
D/wpa_supplicant( 1351):   key_nonce - hexdump(len=32): 44 9f 43 a2 7f f2 85 4a bb a7 b2 1d 36 45 67 e4 a3 e5 cd f6 d5 c8 ce bd 3b 61 b7 b9 1d 28 c3 a6
D/wpa_supplicant( 1351):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1351):   key_rsc - hexdump(len=8): 41 3e 00 00 00 00 00 00
D/wpa_supplicant( 1351):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1351):   key_mic - hexdump(len=16): 30 2a 8f 60 6c 31 94 43 95 e7 b9 1a 29 c3 59 3d
E/WifiStateMachine(  959): [sendNetworkStateChangeBroadcast] NetworkInfo state =AUTHENTICATING wifi info = SSID: NG700, BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: 0, Metered hint: false
D/wpa_supplicant( 1351): RSN: encrypted key data - hexdump(len=56): a0 30 7d 6e 71 87 0f 83 35 60 33 61 19 cc 96 ec 1c 02 43 ac 76 4a f3 bb 2e 51 70 9c 99 61 93 5d ...
D/wpa_supplicant( 1351): WPA: decrypted EAPOL-Key key data - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 1351): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1351): wlan0: WPA: RX message 3 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 1351): WPA: IE KeyData - hexdump(len=48): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00 dd 16 00 0f ac 01 02 00 d8 4e ...
D/wpa_supplicant( 1351): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1351): WPA: GTK in EAPOL-Key - hexdump(len=24): [REMOVED]
D/wpa_supplicant( 1351): wlan0: WPA: Sending EAPOL-Key 4/4
E/WifiTrafficPoller(  959): ENABLE_TRAFFIC_STATS_POLL false Token 17
D/wpa_supplicant( 1351): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 1351): WPA: Derived Key MIC - hexdump(len=16): 9b b8 32 9d 7a de 06 60 7b 3a 73 8d 6f 89 25 13
D/wpa_supplicant( 1351): wlan0: WPA: Installing PTK to the driver
D/wpa_supplicant( 1351): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=3 addr=0x5571f5a390 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 1351): nl80211: KEY_DATA - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 1351): nl80211: KEY_SEQ - hexdump(len=6): 00 00 00 00 00 00
D/wpa_supplicant( 1351):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1351): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1351): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1351): RSN: received GTK in pairwise handshake - hexdump(len=18): [REMOVED]
D/wpa_supplicant( 1351): WPA: Group Key - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 1351): wlan0: WPA: Installing GTK to the driver (keyidx=2 tx=0 len=16)
D/wpa_supplicant( 1351): WPA: RSC - hexdump(len=6): 41 3e 00 00 00 00
D/wpa_supplicant( 1351): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=3 addr=0x556c918e68 key_idx=2 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 1351): nl80211: KEY_DATA - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 1351): nl80211: KEY_SEQ - hexdump(len=6): 41 3e 00 00 00 00
D/wpa_supplicant( 1351):    broadcast key
D/WifiMonitor(  959): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor(  959): WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  959): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  959): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
I/IntentController( 1218): receive(android.net.wifi.STATE_CHANGE,1,false)
D/HTCRequest(  959): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  959): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
I/wpa_supplicant( 1351): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/wpa_supplicant( 1351): wlan0: Cancelling authentication timeout
E/wpa_supplicant( 1351): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/WIFI_ICON( 1218): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/wpa_supplicant( 1351): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
D/StatusBar.NetworkController( 1218): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/wpa_supplicant( 1351): wlan0: Radio work 'connect'@0x5571f5a680 done in 0.118705 seconds
I/wpa_supplicant( 1351): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
I/wpa_supplicant( 1351): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
D/WifiMonitor(  959): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
E/WifiMonitor(  959): WifiMonitor:wlan0 cnt=41 dispatchEvent: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
W/WifiMonitor(  959): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor(  959): Event [IFNAME=wlan0 BLACKLIST REMOVE c0:ff:d4:d3:aa:48]
E/WifiMonitor(  959): WifiMonitor:wlan0 cnt=42 dispatchEvent: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/WifiMonitor(  959): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]]
E/WifiMonitor(  959): WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiMonitor(  959): handleEvent 1  Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/ConnectivityService(  959): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
E/wpa_supplicant( 1351): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 1351): nl80211: Set wlan0 operstate 0->1 (UP)
E/ConnectivityService(  959): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/wpa_supplicant( 1351): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=6 (IF_OPER_UP)
I/wpa_supplicant( 1351): set send_ind_to_ndc = 0
I/wpa_supplicant( 1351): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1351): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1351): EAPOL: External notification - portValid=1
V/NetworkPolicy(  959): ensureActiveMobilePolicyLocked()
D/wpa_supplicant( 1351): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1351): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1351): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1351): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1351): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 1351): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1351): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1351): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1351): EAPOL authentication completed - result=SUCCESS
I/wpa_supplicant( 1351): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
E/ConnectivityService(  959): EVENT_NETWORK_VALIDATED - isLiveNetworkAgent found mismatched netId: null - NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.130/24,fe80::92e7:c4ff:fee6:4cf8/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/Tethering(  959): interfaceLinkStateChanged wlan0, true
D/Tethering(  959): interfaceStatusChanged wlan0, true
D/wpa_supplicant( 1351): RTM_NEWLINK: ifi_index=29 ifname=wlan0 operstate=6 linkmode=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
E/WifiStateMachine(  959): WiFiDisplay: getWifidisplayApEnabled=false
D/WifiMonitor(  959): Event [IFNAME=wlan0 Connect to SSID: NG700]
E/WifiMonitor(  959): WifiMonitor:wlan0 cnt=44 dispatchEvent: Connect to SSID: NG700
W/WifiMonitor(  959): couldn't identify event type - Connect to SSID: NG700
D/WifiMonitor(  959): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor(  959): WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  959): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  959): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  959): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  959): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
E/WifiStateMachine(  959): processMsg: ConnectModeState
E/WifiStateMachine(  959):  ConnectModeState !SUPPLICANT_STATE_CHANGE_EVENT 39 0 rt=103787  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
E/WifiStateMachine(  959): handleMessage: X
E/WifiTrafficPoller(  959): ENABLE_TRAFFIC_STATS_POLL false Token 18
I/IntentController( 1218): receive(android.net.wifi.STATE_CHANGE,1,false)
D/Tethering(  959): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
D/Tethering(  959): TetherMasterSM: InitialState processMessage what=UPSTREAM_CHANGED
D/libc    ( 6390): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
D/libc    ( 6390): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 6390): [NET] android_getaddrinfo_proxy+
D/libc    ( 6390): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  395): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
D/libc    (  395): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  395): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  395): [NET] android_getaddrinfofornet-, err=7
D/DATA_ICON( 1218): updateConnectivity android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE Type:-1/Status:0
D/libc    ( 6390): [NET] android_getaddrinfo_proxy-, NODATA
D/PMS     (  959): releaseWL(2807e671): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/WISPrService( 6390): >>>>>WISPrService start isConnected = false<<<<<
D/PMS     (  959): acquireWL(353b94d7): PARTIAL_WAKE_LOCK  NetworkStats 0x1 959 1000 null
D/WISPrService( 6390): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: FOUR_WAY_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: 0, Metered hint: false
D/WISPrService( 6390): >>>>>WISPrService start isConnected = false<<<<<
D/DATA_ICON( 1218): dataConnected: false/false
D/StatusBar.NetworkController( 1218): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiStateMachine(  959): handleMessage: E msg.what=131101
E/WifiStateMachine(  959): processMsg: DisconnectedState
D/WISPrService( 6390): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: FOUR_WAY_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: 0, Metered hint: false
E/WifiStateMachine(  959):  DisconnectedState !CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  959): processMsg: ConnectModeState
E/WifiStateMachine(  959):  ConnectModeState !CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  959): processMsg: DriverStartedState
D/NetworkPolicy(  959): ensureActiveMobilePolicyLocked: SIM state invalid, slotId= -1000, subId=-1000 . Return.
V/NetworkPolicy(  959): updateNetworkEnabledLocked()
E/WifiStateMachine(  959):  DriverStartedState !CMD_TETHER_STATE_CHANGE 0 0
V/NetworkPolicy(  959): updateIfacesLocked()
E/WifiStateMachine(  959): processMsg: SupplicantStartedState
V/NetworkPolicy(  959): updateNotificationsLocked()
E/WifiStateMachine(  959):  SupplicantStartedState !CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  959): processMsg: DefaultState
E/WifiStateMachine(  959):  DefaultState !CMD_TETHER_STATE_CHANGE 0 0
D/WifiStateMachine(  959): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  959): Default got CMD_TETHER_STATE_CHANGE
E/WifiStateMachine(  959): handleMessage: X
E/WifiStateMachine(  959): handleMessage: E msg.what=147462
E/WifiStateMachine(  959): processMsg: DisconnectedState
E/WifiStateMachine(  959):  DisconnectedState !SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=103805  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine(  959): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  959): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  959): processMsg: ConnectModeState
E/WifiStateMachine(  959):  ConnectModeState !SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=103806  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
V/NetworkPolicy(  959): updateNetworkEnabledLocked()
E/WifiStateMachine(  959): handleMessage: X
V/NetworkPolicy(  959): updateNotificationsLocked()
E/WifiStateMachine(  959): handleMessage: E msg.what=147459
E/WifiStateMachine(  959): processMsg: DisconnectedState
D/WISPrService( 6390): >>>>>WISPrService start isConnected = false<<<<<
E/WifiStateMachine(  959):  DisconnectedState !NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=103807
D/NetworkManagementService(  959): isBandwidthControlEnabled: doneSignal.getCount()= 0
D/WISPrService( 6390): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: 0, Metered hint: false
D/TetherSettings( 6390): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 6390): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 6390): Cust_ConnectToPC   : Modem_Link>false
D/        ( 6390): Cust_ConnectToPC   : spcsc>false
D/        ( 6390): Cust_ConnectToPC   : IPT>true
D/        ( 6390): Cust_ConnectToPC   : Singel_USB>false
E/WifiStateMachine(  959): processMsg: ConnectModeState
W/Settings( 6390): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 6390): hasRemovableStorageSlot: true
D/SmartNS_Utility( 6390): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 6390): onReceive : android.net.conn.TETHER_STATE_CHANGED hasTethered:false isNSOpening:false
D/PMS     (  959): releaseWL(353b94d7): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/WISPrService( 6390): >>>>>WISPrService start isConnected = false<<<<<
E/WifiStateMachine(  959):  ConnectModeState !NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=103809
E/WifiStateMachine(  959): Network connection established
D/WifiStateMachine(  959): fetchFrequency(), freq = 2412
E/WifiStateMachine(  959): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
E/WifiStateMachine(  959): NetworkAgent == null
E/WifiStateMachine(  959): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
E/WifiStateMachine(  959): WiFiDisplay: getWifidisplayApEnabled=false
D/WISPrService( 6390): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
E/WifiTrafficPoller(  959): ENABLE_TRAFFIC_STATS_POLL false Token 19
W/ContextImpl( 6390): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.NSReceiver.onReceive:432 android.app.ActivityThread.handleReceiver:2712 
E/WifiStateMachine(  959): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
I/IntentController( 1218): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WIFI_ICON( 1218): updateWifiState: NETWORK_STATE_CHANGED disconnected
E/WifiStateMachine(  959): transitionTo: destState=ObtainingIpState
D/StatusBar.NetworkController( 1218): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiStateMachine(  959): handleMessage: new destination call exit/enter
V/NetworkPolicy(  959): updateNetworkEnabledLocked()
E/WifiStateMachine(  959): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
V/NetworkPolicy(  959): updateNotificationsLocked()
E/WifiStateMachine(  959): invokeExitMethods: DisconnectedState
E/WifiStateMachine(  959): setScanAlarm false period 0 initial delay 0mAlarmEnabledtrue
I/SmartNS_Utility( 6390): setISNotification
E/WifiTrafficPoller(  959): TRAFFIC_STATS_POLL false Token 20 num clients 8
D/WifiDisplayAdapter(  959): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  959):     Client/Owner: Client
D/WifiDisplayAdapter(  959):     GroupId: 
D/WifiDisplayAdapter(  959):     Passphrase: 
D/WifiDisplayAdapter(  959):     SessionId: 0
D/WifiDisplayAdapter(  959):     IP Address: }
D/SmartNS_Utility( 6390): usb_cable_connect = 1
E/WifiStateMachine(  959): moveTempStackToStateStack: i=1,j=4
E/WifiStateMachine(  959): moveTempStackToStateStack: i=0,j=5
E/WifiStateMachine(  959): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=4,Top=ObtainingIpState
E/WifiStateMachine(  959): invokeEnterMethods: L2ConnectedState
E/WifiStateMachine(  959): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
E/WifiStateMachine(  959): NetworkAgent == null
E/WifiStateMachine(  959): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTING wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/SmartNS_Utility( 6390): usb_denied = 0
D/WifiService(  959): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=httpproxy
E/WifiTrafficPoller(  959): ENABLE_TRAFFIC_STATS_POLL false Token 20
I/SmartNS_PSService( 6390): usb notificaiton:true
E/WifiStateMachine(  959): WiFiDisplay: getWifidisplayApEnabled=false
D/WIFI_ICON( 1218): updateWifiState: NETWORK_STATE_CHANGED disconnected
I/IntentController( 1218): receive(android.net.wifi.STATE_CHANGE,1,false)
D/StatusBar.NetworkController( 1218): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
I/IntentController( 1218): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WIFI_ICON( 1218): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1218): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiTrafficPoller(  959): ENABLE_TRAFFIC_STATS_POLL false Token 21
D/ConnectivityService(  959): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiStateMachine(  959): L2ConnectedState c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
D/ConnectivityService(  959): Got NetworkAgent Messenger
E/WifiStateMachine(  959): L2ConnectedState "NG700" nid=0
E/WifiConfigStore(  959): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
W/WifiHW  (  959): QCOM Debug skip set_network part for security concern!
D/ConnectivityService(  959): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService(  959): NetworkAgent connected
D/wpa_supplicant( 1351): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1351): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1351): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  959): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1351): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1351): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 1351): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1351): CTRL_IFACE: SAVE_CONFIG - Configuration updated
E/WifiStateMachine(  959): invokeEnterMethods: ObtainingIpState
E/WifiStateMachine(  959): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
E/WifiStateMachine(  959): ObtainingIpAddress c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  959): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  959): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
W/WifiHW  (  959): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1351): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1351): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1351): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  959): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1351): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1351): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 1351): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1351): CTRL_IFACE: SAVE_CONFIG - Configuration updated
I/QuickSettingWifi( 1218): receive.wifiConnect:false wifiAPname:null elapse:1
D/libc    (  959): [NET] android_getaddrinfofornet+,hn 7(0x302e302e302e30),sn(),hints(known),family 0,flags 4
D/libc    (  959): [NET] android_getaddrinfofornet+,hn 6,sn(),hints(known),family 0,flags 4
D/libc    (  959): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  959): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  959): Start Dhcp Watchdog 2
E/WifiStateMachine(  959): handleMessage: X
E/WifiStateMachine(  959): handleMessage: E msg.what=147462
E/WifiStateMachine(  959): processMsg: ObtainingIpState
E/WifiStateMachine(  959):  ObtainingIpState !SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=103830  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine(  959): processMsg: L2ConnectedState
E/WifiStateMachine(  959):  L2ConnectedState !SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=103831  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine(  959): processMsg: ConnectModeState
E/WifiStateMachine(  959):  ConnectModeState !SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=103832  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine(  959): handleMessage: X
I/QuickSettingWifi( 1218): receive.wifiConnect:false wifiAPname:null elapse:0
D/libc    ( 6390): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 4
D/libc    ( 6390): [NET] android_getaddrinfofornet-, err=8
I/ActivityManager(  959): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=6776 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a
D/WISPrService( 6390): exception: java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/WISPrService( 6390): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 6390): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiService(  959): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=callernameid
I/QuickSettingWifi( 1218): receive.wifiConnect:false wifiAPname:null elapse:0
E/WifiStateMachine(  959): handleMessage: E msg.what=131155
E/WifiStateMachine(  959): processMsg: ObtainingIpState
D/WISPrService( 6390): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 6390): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
E/WifiStateMachine(  959):  ObtainingIpState !CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-127 f=2412 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:795] from screen [on:0 period:-1470739157] gl hn u24 rssi=-52 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  959): processMsg: L2ConnectedState
E/WifiStateMachine(  959):  L2ConnectedState !CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-127 f=2412 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1470739156] gl hn u24 rssi=-52 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/WifiService(  959): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=verizon
E/WifiStateMachine(  959):  get link layer stats 0
W/WifiHW  (  959): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1351): wlan0: Control interface command 'SIGNAL_POLL'
D/SmartNS_Utility( 6390): usb_cable_connect = 1
D/SmartNS_Utility( 6390): usb_denied = 0
I/SmartNS_PSService( 6390): usb notificaiton:true
I/wpa_supplicant( 1351): environment dirty rate=0 [2][0][0]
E/WifiStateMachine(  959): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiStateMachine(  959): fetchRssiLinkSpeedAndFrequencyNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 72
D/DotMatrix( 1304): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
E/WifiStateMachine(  959): fetchRssiLinkSpeedAndFrequencyNative rssi=-57 linkspeed=72
E/WifiConfigStore(  959): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-57 "NG700"WPA_PSK
E/WifiStateMachine(  959): calculateWifiScore freq=2412 speed=72 score=0 highRSSI  -> txbadrate=0.00 txgoodrate=112.50 txretriesrate=0.00 rxrate=151.00 userTriggerdPenalty0
E/WifiStateMachine(  959):  good link -> stuck count =0
E/WifiStateMachine(  959):  badRSSI count0 lowRSSI count0 --> score 60
E/WifiStateMachine(  959):  isHighRSSI       ---> score=65
E/WifiStateMachine(  959): calculateWifiScore() report new score 60
E/WifiStateMachine(  959): handleMessage: X
E/WifiStateMachine(  959): handleMessage: E msg.what=131212
E/WifiStateMachine(  959): processMsg: ObtainingIpState
D/ConnectivityService(  959): updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
I/RemoteViews( 1218): reapply : com.android.settings 1 36
E/WifiStateMachine(  959):  ObtainingIpState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  959): processMsg: L2ConnectedState
E/WifiStateMachine(  959):  L2ConnectedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  959): processMsg: ConnectModeState
E/WifiStateMachine(  959):  ConnectModeState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  959): processMsg: DriverStartedState
D/WifiWatchdogStateMachine(  959): RSSI current: 3 new: -57, 3
E/WifiStateMachine(  959):  DriverStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  959): processMsg: SupplicantStartedState
E/WifiStateMachine(  959):  SupplicantStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  959): processMsg: DefaultState
E/WifiStateMachine(  959):  DefaultState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  959): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  959): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
D/WIFI_ICON( 1218): updateWifiState: RSSI_CHANGED -1 -> 3
E/WifiStateMachine(  959): handleMessage: X
D/ConnectivityService(  959): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
D/WifiService(  959): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=fota
E/WifiStateMachine(  959): handleMessage: E msg.what=196612
E/WifiStateMachine(  959): processMsg: ObtainingIpState
E/WifiStateMachine(  959):  ObtainingIpState !CMD_PRE_DHCP_ACTION 0 0 txpkts=225,0,0
D/WifiStateMachine(  959): handlePreDhcpSetup Held wake lock during DHCP
,E/WifiStateMachine(  959): processMsg: L2ConnectedState
D/PMS     (  959): acquireWL(10ebf13a): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 959 1000 null
,E/WifiStateMachine(  959):  L2ConnectedState !CMD_PRE_DHCP_ACTION 0 0 txpkts=225,0,0
D/WifiStateMachine(  959): handlePreDhcpSetup mBluetoothConnectionActive: false
D/SmartNS_NSReceiver( 6390): Tethered state change:false isNSOpening:false
D/StatusBar.NetworkController( 1218): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
D/WifiDataStallTracker(  959): setDhcpActive: true
D/WifiP2pService(  959): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3ef45d51 target=com.android.internal.util.StateMachine$SmHandler }
W/WifiHW  (  959): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
D/WifiP2pService(  959): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3ef45d51 target=com.android.internal.util.StateMachine$SmHandler }
D/WISPrService( 6390): >>>>>WISPrService start isConnected = false<<<<<
D/wpa_supplicant( 1351): wlan0: Control interface command 'DRIVER BTCOEXMODE 1'
D/wpa_supplicant( 1351): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 8192
D/WISPrService( 6390): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -57, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
E/WifiStateMachine(  959): setSuspendOptimizationsNative: 1 false -want false stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
,E/native  (  959): do suspend false
W/WifiHW  (  959): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 0"
D/wpa_supplicant( 1351): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 0'
D/wpa_supplicant( 1351): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 0 len = 0, 8192
D/DotMatrix( 1304): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
W/WifiHW  (  959): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
D/wpa_supplicant( 1351): wlan0: Control interface command 'DRIVER POWERMODE 1'
I/wpa_supplicant( 1351): INFO - Deny active power mode because already has gateway
W/WifiHW  (  959): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
D/wpa_supplicant( 1351): wlan0: Control interface command 'DRIVER WLS_BATCHING GET'
E/wpa_supplicant( 1351): wpa_driver_nl80211_driver_cmd: failed to issue private commands
E/WifiStateMachine(  959): Unexpected BatchedScanResults :null
D/wpa_supplicant( 1351): nl80211: Drv Event 79 (NL80211_CMD_SET_REKEY_OFFLOAD) received for wlan0
D/wpa_supplicant( 1351): nl80211: Rekey offload event for BSSID c0:ff:d4:d3:aa:48
W/WifiHW  (  959): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
D/wpa_supplicant( 1351): nl80211: Rekey offload - Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1351): wlan0: Event DRIVER_GTK_REKEY (37) received
D/wpa_supplicant( 1351): wlan0: Control interface command 'DRIVER WLS_BATCHING STOP'
E/wpa_supplicant( 1351): wpa_driver_nl80211_driver_cmd: failed to issue private commands
E/WifiStateMachine(  959): noteBatchedScanstop()
D/WISPrService( 6390): >>>>>WISPrService start isConnected = false<<<<<
E/WifiStateMachine(  959): handleMessage: X,
D/WifiService(  959): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=supl
D/WISPrService( 6390): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -57, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
D/WISPrService( 6390): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 6390): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -57, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiService(  959): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=emergency
,I/QuickSettingWifi( 1218): receive.wifiConnect:false wifiAPname:null elapse:0
,I/RemoteViews( 1218): reapply : com.android.settings 1 36
,I/QuickSettingWifi( 1218): receive.wifiConnect:false wifiAPname:null elapse:1
I/QuickSettingWifi( 1218): receive.wifiConnect:false wifiAPname:null elapse:0
,D/WifiService(  959): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=verizon800
,I/ActivityManager(  959): Start proc com.htc.bgp for broadcast com.htc.flexnet/.AndroidIntentReceiver: pid=6797 uid=10011 gids={50011, 9997, 1028, 1015, 5001, 5011, 2001, 3003} abi=arm64-v8a
,D/WifiService(  959): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=hipri
,D/WifiService(  959): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=ims
,D/WifiService(  959): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=default
,D/WifiService(  959): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=mms,
D/WifiService(  959): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=cbs
,D/WifiService(  959): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=ia,
,D/WifiService(  959): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=dun
,D/WifiService(  959): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=internet
,W/ResourcesManager( 6797): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.,
,I/ActivityManager(  959): Start proc com.htc.mobiledata:remote for service com.htc.mobiledata/.MobileDataService: pid=6819 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a
,I/CalendarProvider2( 6797): Created com.android.providers.calendar.CalendarAlarmManager@2de435ea(com.htc.providers.calendar.HtcCalendarProvider@2f9470db)
,D/CalendarProvider2( 6797): wait start:true
,D/FlexNetS( 6797): updateSvcAllowedInSettings:false,
D/CalendarProvider2( 6797): wait end:false
,E/dhcpcd  ( 6845): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
I/dhcpcd  ( 6845): version 5.5.6 starting,
E/dhcpcd  ( 6845): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
I/dhcpcd  ( 6845): wlan0: using ClientID 01:90:**:c4:e6:4c:f8
I/dhcpcd  ( 6845): autoip env[11]:autoip=DISABLE
D/FlexNetS( 6797): updateSvcAllowedInSettings:false
,D/FlexNetS( 6797): updateSvcAllowedInSettings:false
,D/FlexNetS( 6797): updateSvcAllowedInSettings:false,
,D/FlexNetS( 6797): updateSvcAllowedInSettings:false
,D/FlexNetS( 6797): updateSvcAllowedInSettings:false,
,D/FlexNetS( 6797): updateSvcAllowedInSettings:false,
,I/dhcpcd  ( 6845): wlan0: rebinding lease of 192.168.1.130
I/dhcpcd  ( 6845): wlan0: sending REQUEST (xid 0x8748548), next in 0.88 seconds
,D/FlexNetS( 6797): updateSvcAllowedInSettings:false
,D/MdScPhnSt( 6819): [9de.2.]  listen tmrbb8
,D/FlexNetS( 6797): updateSvcAllowedInSettings:false
D/FlexNetS( 6797): updateSvcAllowedInSettings:false
,D/FlexNetS( 6797): updateSvcAllowedInSettings:false
,D/FlexNetS( 6797): updateSvcAllowedInSettings:false
,D/FlexNetS( 6797): updateSvcAllowedInSettings:false
,D/FlexNetS( 6797): updateSvcAllowedInSettings:false,
,D/FlexNetS( 6797): updateSvcAllowedInSettings:false
,D/MdProvGlob( 6776): remove item 101 (p2d27in210) for 15:android.intent.action.ANY_DATA_STATE,
D/MdScDataSum( 6819): [9de.2.] summary 118:p2 ignore
,D/Process (  959): killProcessQuiet, pid=5845,
I/ActivityManager(  959): Killing 5845:com.google.android.gm/u0a106 (adj 15): empty #17
D/Process (  959): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  959): Recipient 5845
,D/Process (  959): killProcessQuiet, pid=5888
I/ActivityManager(  959): Killing 5888:com.htc.calendar/u0a10 (adj 15): empty #17
D/Process (  959): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,E/WifiTrafficPoller(  959): TRAFFIC_STATS_POLL false Token 22 num clients 8,
,I/ActivityManager(  959): Recipient 5888,
,D/Process (  959): killProcessQuiet, pid=6479
I/ActivityManager(  959): Killing 6479:com.htc.cs.dm/u0a99 (adj 15): empty #17
D/Process (  959): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,D/wpa_supplicant( 1351): EAPOL: startWhen --> 0,
D/wpa_supplicant( 1351): EAPOL: disable timer tick
,I/ActivityManager(  959): Recipient 6479,
,D/Process (  959): killProcessQuiet, pid=6454
I/ActivityManager(  959): Killing 6454:com.google.android.partnersetup/u0a27 (adj 15): empty #18
D/Process (  959): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  959): Recipient 6454
,I/CalendarProvider2( 6797): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: }
W/ContentResolver( 6797): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,D/libc    (  959): [NET] android_getaddrinfofornet+,hn 25(0x666538303a3a39),sn(),hints(known),family 0,flags 4
D/libc    (  959): [NET] android_getaddrinfofornet-, SUCCESS
I/ActivityManager(  959): Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=6859 uid=10010 gids={50010, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
E/WifiStateMachine(  959): handleMessage: E msg.what=131212
E/WifiStateMachine(  959): processMsg: ObtainingIpState
E/WifiStateMachine(  959):  ObtainingIpState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  959): processMsg: L2ConnectedState
E/WifiStateMachine(  959):  L2ConnectedState !CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine(  959): processMsg: ConnectModeState
E/WifiStateMachine(  959):  ConnectModeState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  959): processMsg: DriverStartedState
E/WifiStateMachine(  959):  DriverStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
I/ActivityManager(  959): Killing 5757:com.android.defcontainer/u0a15 (adj 15): empty #17
E/WifiStateMachine(  959): processMsg: SupplicantStartedState
D/ConnectivityService(  959): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine(  959):  SupplicantStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  959): processMsg: DefaultState
E/WifiStateMachine(  959):  DefaultState !CMD_UPDATE_LINKPROPERTIES 0 0
D/Process (  959): killProcessQuiet, pid=5757
E/WifiStateMachine(  959): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [fe80::92e7:c4ff:fee6:4cf8/64,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  959): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  959): handleMessage: X
D/Process (  959): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/dhcpcd  ( 6845): wlan0: sending REQUEST (xid 0x8748548), next in 1.75 seconds
,I/ActivityManager(  959): Recipient 5757
,D/PMS     (  959): acquireWL(1f16dcd5): PARTIAL_WAKE_LOCK  *alarm* 0x1 959 1000 WorkSource{10024},
V/AlarmManager(  959): sending alarm PendingIntent{15c31cea: PendingIntentRecord{3ddecbdb com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=105127, Int=0
,W/ResourcesManager( 6859): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.,
,D/CalendarApplication( 6859): onCreate
,D/ProviderChangeReceiver( 6859): ---------------------------------------------------
D/ProviderChangeReceiver( 6859): ProviderChangeReceiver onReceive, start HtcAlertService to update notification!
,D/Process (  959): killProcessQuiet, pid=6509
I/ActivityManager(  959): Killing 6509:com.htc.providers.settings:remote/u0a13 (adj 15): empty #17
D/Process (  959): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
D/PMS     (  959): acquireWL(5bb678): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1936 10024 WorkSource{10024 com.google.android.gms}
D/libc    ( 1936): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
,D/libc    ( 1936): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1936): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    ( 1936): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1936): [NET] android_getaddrinfo_proxy+
D/libc    ( 1936): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  395): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    (  395): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  395): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  395): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 1936): [NET] android_getaddrinfo_proxy-, NODATA
D/HtcAlertService( 6859): start to updateAlertNotification!
D/PMS     (  959): acquireWL(5bb678): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1936 10024 WorkSource{10024 com.google.android.gms}
,D/libc    ( 1936): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
,D/libc    ( 1936): [NET] android_getaddrinfofornet-, err=8
,D/PMS     (  959): releaseWL(5bb678): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,I/ActivityManager(  959): Recipient 6509
,D/PMS     (  959): releaseWL(1f16dcd5): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10024}
,D/HtcAlertService( 6859): No fired or scheduled alerts
,D/HtcAlertUtils( 6859): -- cancelReminderNotification --
,I/dhcpcd  ( 6845): wlan0: acknowledged 192.168.1.130 from 192.168.1.1
,D/HtcAlertUtils( 6859): broadcastExistReminder!
,D/DotMatrix( 1304): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false,
,I/dhcpcd  ( 6845): wlan0: leased 192.168.1.130 for 86400 seconds,
I/dhcpcd  ( 6845): autoip env[11]:autoip=DISABLE
,D/libc    (  959): [NET] android_getaddrinfofornet+,hn 13(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  959): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  959): handleMessage: E msg.what=131212
D/ConnectivityService(  959): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine(  959): processMsg: ObtainingIpState
,E/WifiStateMachine(  959):  ObtainingIpState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  959): processMsg: L2ConnectedState
E/WifiStateMachine(  959):  L2ConnectedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  959): processMsg: ConnectModeState
E/WifiStateMachine(  959):  ConnectModeState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  959): processMsg: DriverStartedState
E/WifiStateMachine(  959):  DriverStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  959): processMsg: SupplicantStartedState
E/WifiStateMachine(  959):  SupplicantStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  959): processMsg: DefaultState
E/WifiStateMachine(  959):  DefaultState !CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine(  959): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [fe80::92e7:c4ff:fee6:4cf8/64,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [fe80::92e7:c4ff:fee6:4cf8/64,192.168.1.130/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  959): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
E/WifiStateMachine(  959): handleMessage: X
,I/dhcpcd  ( 6845): bind_interface: daemonise,
,D/libc    (  959): [NET] android_getaddrinfofornet+,hn 13(0x3139322e313638),sn(),hints(known),family 0,flags 4,
D/libc    (  959): [NET] android_getaddrinfofornet-, SUCCESS
D/WifiP2pService(  959): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/libc    (  959): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/WifiP2pService(  959): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/libc    (  959): [NET] android_getaddrinfofornet-, SUCCESS
D/PMS     (  959): releaseWL(10ebf13a): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
D/libc    (  959): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  959): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  959): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  959): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  959): handleMessage: E msg.what=196613
E/WifiStateMachine(  959): processMsg: ObtainingIpState
E/WifiStateMachine(  959):  ObtainingIpState !CMD_POST_DHCP_ACTION 1 0 OK  v4
E/WifiStateMachine(  959): processMsg: L2ConnectedState
E/WifiStateMachine(  959):  L2ConnectedState !CMD_POST_DHCP_ACTION 1 0 OK  v4
E/WifiStateMachine(  959): setSuspendOptimizationsNative: 1 true -want false stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
W/WifiHW  (  959): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
D/wpa_supplicant( 1351): wlan0: Control interface command 'DRIVER POWERMODE 0'
,I/wpa_supplicant( 1351): Power_Mode_Type mode = 0
I/wpa_supplicant( 1351): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
W/WifiHW  (  959): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
D/wpa_supplicant( 1351): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/wpa_supplicant( 1351): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 8192
D/WifiDataStallTracker(  959): setDhcpActive: false
E/WifiStateMachine(  959): handlePostDhcpSetup release wake lock during DHCP
E/WifiStateMachine(  959): WifiStateMachine DHCP successful
E/WifiStateMachine(  959): wifistatemachine handleIPv4Success <IP address 192.168.1.130/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds>
E/WifiStateMachine(  959): link address 192.168.1.130/24
E/WifiStateMachine(  959): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [fe80::92e7:c4ff:fee6:4cf8/64,192.168.1.130/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [fe80::92e7:c4ff:fee6:4cf8/64,192.168.1.130/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine(  959): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
D/ConnectivityService(  959): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine(  959): gateway: /192.168.1.1
W/WifiHW  (  959): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
D/wpa_supplicant( 1351): wlan0: Control interface command 'DRIVER GATEWAY-ADD 16885952'
I/wpa_supplicant( 1351): WiFi gateway: 0x101a8c0
,D/WifiStateMachine(  959): [MLHD] enter handleMediaLinkEvent L2ConnectedState
E/WifiStateMachine(  959): handleMessage: X
E/WifiStateMachine(  959): handleMessage: E msg.what=131210
E/WifiStateMachine(  959): processMsg: ObtainingIpState
,E/WifiStateMachine(  959):  ObtainingIpState !CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine(  959): processMsg: L2ConnectedState
E/WifiStateMachine(  959):  L2ConnectedState !CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
W/WifiHW  (  959): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1351): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1351): environment dirty rate=20 [5][1][0]
E/WifiStateMachine(  959): fetchRssiLinkSpeedAndFrequencyNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  959): fetchRssiLinkSpeedAndFrequencyNative rssi=-57 linkspeed=72
,E/WifiConfigStore(  959): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-57 "NG700"WPA_PSK
W/WifiHW  (  959): QCOM Debug wifi_send_command "IFNAME=wlan0 BLACKLIST clear"
D/wpa_supplicant( 1351): wlan0: Control interface command 'BLACKLIST clear'
E/wpa_supplicant( 1351): wlan0: BLACKLIST CLEAR 
,D/WifiWatchdogStateMachine(  959): RSSI current: 3 new: -57, 3
D/WIFI_ICON( 1218): updateWifiState: RSSI_CHANGED 3 -> 3
D/WifiMonitor(  959): Event [IFNAME=wlan0 BLACKLIST CLEAR ]
D/StatusBar.NetworkController( 1218): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
E/WifiMonitor(  959): WifiMonitor:wlan0 cnt=46 dispatchEvent: BLACKLIST CLEAR 
E/WifiStateMachine(  959): setDetailed state, old =CONNECTING and new state=CONNECTED hidden=false
E/WifiStateMachine(  959): NetworkAgent != null
,E/WifiStateMachine(  959): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -57, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
D/ConnectivityService(  959): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
E/WifiStateMachine(  959): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -57, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
V/NetworkPolicy(  959): mWifiStateReceiver: meteredHint=false,EPS mode=false
D/WifiDataStallTracker(  959): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
D/ConnectivityService(  959): Adding iface wlan0 to network 101
D/WIFI_ICON( 1218): updateWifiState: NETWORK_STATE_CHANGED connected
D/HtcWifiWanDetect(  959): WAN detection
,E/WifiStateMachine(  959): transitionTo: destState=ConnectedState
D/HtcWifiWanDetect(  959): canDoWanDetection: mHtcWanDetectionDialogEnabled: true mHtcWanDetectionEnabled: true
E/WifiStateMachine(  959): handleMessage: new destination call exit/enter
E/WifiStateMachine(  959): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
E/WifiStateMachine(  959): invokeExitMethods: ObtainingIpState
E/WifiStateMachine(  959): moveTempStackToStateStack: i=0,j=5
E/WifiStateMachine(  959): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=ConnectedState
V/NetworkPolicy(  959): mWifiStateReceiver: meteredHint=false,EPS mode=false
E/WifiStateMachine(  959): invokeEnterMethods: ConnectedState
E/WifiStateMachine(  959): updateDefaultRouteMacAddress found Ipv4 default :192.168.1.1
E/WifiTrafficPoller(  959): ENABLE_TRAFFIC_STATS_POLL true Token 22
I/IntentController( 1218): receive(android.net.wifi.STATE_CHANGE,1,false)
,I/IntentController( 1218): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/StatusBar.NetworkController( 1218): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/WifiTrafficPoller(  959):  packet count Tx=227 Rx=304
D/WIFI_ICON( 1218): updateWifiState: NETWORK_STATE_CHANGED connected
E/WifiTrafficPoller(  959): notifying of data activity 3
D/StatusBar.NetworkController( 1218): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/WifiStateMachine(  959): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
E/WifiDataStallTracker(  959): ENABLE_DATA_MONITOR_POLL true Token 2
E/WifiTrafficPoller(  959): ENABLE_TRAFFIC_STATS_POLL true Token 23
E/WifiTrafficPoller(  959):  packet count Tx=227 Rx=304
D/WifiDataStallTracker(  959): updateDataStallInfo: mDataStallTxRxSum={txSum=0 rxSum=0} preTxRxSum={txSum=0 rxSum=0}
E/WifiTrafficPoller(  959): notifying of data activity 0
D/WifiDataStallTracker(  959): updateDataStallInfo: NONE
D/WifiDataStallTracker(  959): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,D/WIFI_ICON( 1218): WifiActivity: 3
D/StatusBar.NetworkController( 1218): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
D/WIFI_ICON( 1218): WifiActivity: 0
D/StatusBar.NetworkController( 1218): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/WISPrService( 6390): >>>>>WISPrService start isConnected = true<<<<<
,E/ConnectivityService(  959): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  959): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/libc    (  395): [NET] android_getaddrinfofornet+,hn 6,sn(),hints(known),family 0,flags 4
D/libc    (  395): [NET] android_getaddrinfofornet-, SUCCESS
D/ConnectivityService(  959): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/libc    (  395): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  395): [NET] android_getaddrinfofornet-, SUCCESS
D/ConnectivityService(  959): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/libc    (  395): [NET] android_getaddrinfofornet+,hn 7(0x302e302e302e30),sn(),hints(known),family 0,flags 4
D/libc    (  395): [NET] android_getaddrinfofornet-, SUCCESS
,D/ConnectivityService(  959): Setting Dns servers for network 101 to [/192.168.1.1]
D/libc    (  959): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  959): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    (  395): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(53),hints(known),family 0,flags 4
D/libc    (  395): [NET] android_getaddrinfofornet-, SUCCESS
D/Nat464Xlat(  959): requiresClat: netType=1, connected=true, mIsClatEnabled=true, hasIPv4Address=true
D/ConnectivityService(  959): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  959): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  959): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101],
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  959): Connected
D/ConnectivityService(  959): rematching NetworkAgentInfo [WIFI () - 101]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  959): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  959):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  959): Validated
D/ConnectivityService(  959):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/usbnet  (  959): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  959):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/usbnet  (  959):   my score=70, my filter=[ Transports:  Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  959): currentScore = 0, newScore = 20
,D/usbnet  (  959): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
D/ConnectivityService(  959):    accepting network in place of null
E/WifiStateMachine(  959): ConnectedState Enter  mScreenOn=true scanperiod=20000
D/ConnectivityService(  959): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isSkipMobile=false
E/WifiStateMachine(  959): setScanAlarm true period 20000 initial delay 200mAlarmEnabledfalse
D/WifiDisplayAdapter(  959): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  959):     Client/Owner: Client
D/WifiDisplayAdapter(  959):     GroupId: 
D/WifiDisplayAdapter(  959):     Passphrase: 
D/WifiDisplayAdapter(  959):     SessionId: 0
D/WifiDisplayAdapter(  959):     IP Address: }
E/WifiStateMachine(  959): handleMessage: X
D/CSLegacyTypeTracker(  959): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,E/WifiStateMachine(  959): handleMessage: E msg.what=131131
D/ConnectivityService(  959): sendGeneralBroadcast, restrictEnable=false
E/WifiStateMachine(  959): processMsg: ConnectedState
D/ConnectivityService(  959): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
E/WifiStateMachine(  959):  ConnectedState !CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
D/ConnectivityService(  959): sendGeneralBroadcastDelayed, restrictEnable=false
E/WifiStateMachine(  959): processMsg: L2ConnectedState
D/ConnectivityService(  959): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
E/WifiStateMachine(  959):  L2ConnectedState !CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
V/NetworkPolicy(  959): ensureActiveMobilePolicyLocked()
E/WifiStateMachine(  959): processMsg: ConnectModeState
D/PMS     (  959): acquireWL(d2e1db6): PARTIAL_WAKE_LOCK  NetworkStats 0x1 959 1000 null
E/WifiStateMachine(  959):  ConnectModeState !CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
D/ConnectivityService(  959): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::92e7:c4ff:fee6:4cf8/64,192.168.1.130/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/Tethering(  959): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
,E/WifiStateMachine(  959): handleMessage: X
D/Tethering(  959): TetherMasterSM: InitialState processMessage what=UPSTREAM_CHANGED
D/WIFI    (  959): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  959):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/WIFI    (  959): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
D/ConnectivityService(  959): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  959): ValidatedState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  959):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  959): Validated
D/ConnectivityService(  959):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  959): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/WISPrService( 6390): >>>>>WISPrService start isConnected = true<<<<<
D/NetworkPolicy(  959): ensureActiveMobilePolicyLocked: SIM state invalid, slotId= -1000, subId=-1000 . Return.
V/NetworkPolicy(  959): updateNetworkEnabledLocked()
D/ConnectivityManager.CallbackHandler( 1218): CM callback handler got msg 524290
V/NetworkPolicy(  959): updateIfacesLocked()
D/ConnectivityService(  959): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  959): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  959):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  959):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  959): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  959): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
V/NetworkPolicy(  959): updateNotificationsLocked()
D/ConnectivityService(  959):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  959):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/DATA_ICON( 1218): updateConnectivity android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE Type:1/Status:0
D/ConnectivityService(  959): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/NetworkManagementService(  959): isBandwidthControlEnabled: doneSignal.getCount()= 0
I/SecurityController( 1218): onAvailable 101 : [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  959): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isSkipMobile=false
D/ConnectivityManager.CallbackHandler( 1218): CM callback handler got msg 524290
D/ConnectivityService(  959): sendGeneralBroadcast, restrictEnable=false
D/WIFI    (  959): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  959): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/usbnet  (  959): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/usbnet  (  959):   my score=70, my filter=[ Transports:  Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/WIFI    (  959):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT,_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/usbnet  (  959): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
D/WIFI    (  959): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
I/SecurityController( 1218): onAvailable 101 : [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  959): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  959): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  959):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  959):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  959): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/DATA_ICON( 1218): dataConnected: false/false
D/ConnectivityService(  959): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/StatusBar.NetworkController( 1218): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/ConnectivityService(  959):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  959):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  959): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1218): CM callback handler got msg 524290
I/SecurityController( 1218): onAvailable 101 : [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/PMS     (  959): releaseWL(d2e1db6): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
I/QuickSettingWifi( 1218): receive.wifiConnect:true wifiAPname:NG700 elapse:1
,D/DATA_ICON( 1218): updateConnectivity android.net.conn.INET_CONDITION_ACTION Type:1/Status:100
,V/NetworkPolicy(  959): updateNetworkEnabledLocked()
V/NetworkPolicy(  959): updateNotificationsLocked()
D/DATA_ICON( 1218): dataConnected: false/false
D/StatusBar.NetworkController( 1218): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/QuickSettingWifi( 1218): receive.wifiConnect:true wifiAPname:NG700 elapse:0
,E/WifiStateMachine(  959): handleMessage: E msg.what=131155
E/WifiStateMachine(  959): processMsg: ConnectedState
,E/WifiStateMachine(  959):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=112.5, 0.0, 0.0  rx=151.0 bcn=0 [on:0 tx:0 rx:0 period:2194] from screen [on:0 period:-1470736954] gl hn u24 rssi=-52 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  959): processMsg: L2ConnectedState
E/WifiStateMachine(  959):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=112.5, 0.0, 0.0  rx=151.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1470736952] gl hn u24 rssi=-52 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  959): handleMessage: X
,I/HtcModeClient( 3240): handler message = 4011,
,E/HtcModeClient( 3240): Check connection and retry 12 times. Stop service and kill this process.
,D/HtcModeClient( 3240): Don't start project servcice
D/HtcModeClient( 3240): setEject: MEDIA_EJECT_STATE = true
,D/HtcModeClient( 3240): connectState: CONNECTION_READY = false
D/SilentMusic( 3240): call stop
D/HtcModeClient( 3240): close connection
W/HtcModeClient( 3240): leaveProjectMode: It does not enter ProjectMode
W/CANMesgAgentLocalSocket( 3240): read the terminate packet, so break
I/ActivityManager(  959): Killing 3240:com.htc.autobot/u0a47 (adj 15): empty #17
D/Process (  959): killProcessQuiet, pid=3240
,D/Process (  959): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  959): Recipient 3240
,D/ConnectivityService(  959): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE,
I/ConnectivityHelper( 1547): [onReceive] WIFI(1): CONNECTED
I/AlarmManager(  959): [AlarmQueuing] connectivity wifi: false
D/GpsLocationProvider(  959): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/PMS     (  959): acquireWL(1a744ab7): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 959 1000 null
D/PMS     (  959): acquireWL(32d1c224): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 959 1000 null
D/PMS     (  959): releaseWL(32d1c224): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/GpsLocationProvider(  959): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  959): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/htcCheckinService(  959): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
,I/ActivityManager(  959): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6913 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=arm64-v8a
,E/WifiStateMachine(  959): handleMessage: E msg.what=131155,
E/WifiStateMachine(  959): processMsg: ConnectedState
,E/WifiStateMachine(  959):  ConnectedState !CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=112.5, 0.0, 0.0  rx=151.0 bcn=0 [on:0 tx:0 rx:0 period:806] from screen [on:0 period:-1470736146] gl hn u24 rssi=-52 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  959): processMsg: L2ConnectedState,
E/WifiStateMachine(  959):  L2ConnectedState !CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=112.5, 0.0, 0.0  rx=151.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1470736144] gl hn u24 rssi=-52 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  959):  get link layer stats 0
W/WifiHW  (  959): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1351): wlan0: Control interface command 'SIGNAL_POLL'
I/wpa_supplicant( 1351): environment dirty rate=0 [2][0][0]
I/art     (  425): Explicit concurrent mark sweep GC freed 8658(367KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 208us total 29.040ms
E/WifiStateMachine(  959): fetchRssiLinkSpeedAndFrequencyNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  959): fetchRssiLinkSpeedAndFrequencyNative rssi=-57 linkspeed=72
E/WifiStateMachine(  959): BroadcastRSSIForIMS, newrssi =-57 , oldRssi= -200
,E/WifiConfigStore(  959): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-57 "NG700"WPA_PSK
D/WifiWatchdogStateMachine(  959): RSSI current: 3 new: -57, 3
D/WIFI_ICON( 1218): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1218): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/GpsLocationProvider(  959): No APN found to select.
E/WifiStateMachine(  959): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=57.75 txretriesrate=0.00 rxrate=77.00 userTriggerdPenalty0
E/WifiStateMachine(  959):  good link -> stuck count =0
E/WifiStateMachine(  959):  badRSSI count0 lowRSSI count0 --> score 60
E/WifiStateMachine(  959):  isHighRSSI       ---> score=65
,D/WifiWatchdogStateMachine(  959): RSSI current: 3 new: -57, 3
,D/PMS     (  959): releaseWL(1a744ab7): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
E/WifiStateMachine(  959): handleMessage: X
,D/WIFI_ICON( 1218): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1218): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/MdScPhnSt( 6819): [f1c.1.]  listen tmrbb8
,I/art     (  425): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 139us total 22.009ms
,D/MdScDataSum( 6819): [f1c.1.] summary 118:p1 ignore
,I/art     (  425): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 162us total 16.854ms
,E/WifiTrafficPoller(  959): TRAFFIC_STATS_POLL true Token 24 num clients 8,
,E/WifiTrafficPoller(  959): TRAFFIC_STATS_POLL true Token 24 num clients 8,
E/WifiTrafficPoller(  959):  packet count Tx=228 Rx=305
D/WIFI_ICON( 1218): WifiActivity: 3
E/WifiTrafficPoller(  959): notifying of data activity 3,
D/StatusBar.NetworkController( 1218): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/PMS     (  959): releaseWL(1ff9bc56): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null,
D/ConnectivityService(  959): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/MusicStore( 6913): Database version: 120,
,D/VoldConnector(  959): SND -> {32 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/}
E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
,W/ContextImpl( 6913): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,D/VoldConnector(  959): SND -> {33 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/}
E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
,W/ContextImpl( 6913): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,W/ContextImpl( 6913): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,D/VoldConnector(  959): SND -> {34 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/}
E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
,W/ResourcesManager( 6913): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
W/ResourcesManager( 6913): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6913): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...,
,W/ActivityThread( 6913): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());,
W/System  ( 6913): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3ff839fe: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6913): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6913): GMSCore installation verified
,I/ConfigStore( 6913): Config Database version: 1,
,I/art     ( 1936): Explicit concurrent mark sweep GC freed 10407(554KB) AllocSpace objects, 5(420KB) LOS objects, 48% free, 4MB/8MB, paused 677us total 35.438ms,
,I/PackageManager(  959):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=6913, uid=10159, userID:0
,D/WifiDisplayAdapter(  959): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  959):     Client/Owner: Client
D/WifiDisplayAdapter(  959):     GroupId: 
D/WifiDisplayAdapter(  959):     Passphrase: 
D/WifiDisplayAdapter(  959):     SessionId: 0
D/WifiDisplayAdapter(  959):     IP Address: }
,D/MediaRouterService(  959): Client com.google.android.music (pid 6913): Registered
,D/WifiDisplayAdapter(  959): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  959):     Client/Owner: Client
D/WifiDisplayAdapter(  959):     GroupId: 
D/WifiDisplayAdapter(  959):     Passphrase: 
D/WifiDisplayAdapter(  959):     SessionId: 0
D/WifiDisplayAdapter(  959):     IP Address: }
,I/MediaRouter( 6913): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android },
,I/art     (  959): Explicit concurrent mark sweep GC freed 56530(2MB) AllocSpace objects, 4(144KB) LOS objects, 33% free, 16MB/25MB, paused 1.838ms total 143.399ms
,V/MusicLeanback( 6913): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) },
,I/NetworkMonitor( 6913): type=WIFI subType= reason=null isConnected=true,
,I/NetworkMonitor( 6913): type=WIFI subType= reason=null isConnected=true,
,D/AutoSetting( 1600): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE,
,I/PackageManager(  959):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=1, flag=1, pid=6913, uid=10159, userID:0,
D/AutoSetting( 1600): service - onCreate()
,D/MobileConnectivityChangeReceiver( 6736): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6736): onReceive CONNECTIVITY_CHANGE networkType=1
,I/GHttpClientFactory( 6913): Using our fixed implementation of GMSCore's GoogleHttpClient
,D/AutoSetting( 1600): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
D/LocationManagerService(  959): request 115c144a passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10052)
D/LocationManagerService(  959): provider request: passive ProviderRequest[ON interval=0]
,I/GoogleURLConnFactory( 6913): Using platform SSLCertificateSocketFactory
D/AutoSetting( 1600): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1600): service - requestNLP() NetworkLocationProvider not enabled
D/AutoSetting( 1600): service - onStartCommand() REMOVE current location bundle
D/AutoSetting( 1600): service - handleMessage() setting current location null
,D/ChimeraCfgMgr( 4431): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/Kids    ( 4431): [GCoreUtils] Current gmscore version, 7899448 is smaller than the required version 8400000
,I/ActivityManager(  959): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6956 uid=10161 gids={50161, 9997, 3003, 1028, 1015} abi=arm64-v8a
,D/libc    ( 6333): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 4
D/libc    ( 6333): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 6333): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
,D/libc    ( 6333): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 6333): [NET] android_getaddrinfo_proxy+
D/libc    ( 6333): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  395): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
D/libc    (  395): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,I/ActivityManager(  959): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=6980 uid=10076 gids={50076, 9997} abi=arm64-v8a,
D/PMS     (  959): acquireWL(2ab14b9b): PARTIAL_WAKE_LOCK  *alarm* 0x1 959 1000 WorkSource{10076}
,V/AlarmManager(  959): sending alarm PendingIntent{7689b38: PendingIntentRecord{c255711 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1454523178125, Int=60000
D/PMS     (  959): releaseWL(2ab14b9b): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10076}
,D/SMSBackup( 6980): SMSBackupAgentService started,
D/SMSBackup( 6980): Checking restore status
,D/SMSBackup( 6980): Restore complete,
D/SMSBackup( 6980): cancelCheckAlarm
,D/SMSBackup( 6980): SMSBackupAgentService completed: completed in 0.0 seconds
,D/Process (  959): killProcessQuiet, pid=6363,
I/ActivityManager(  959): Killing 6363:com.htc.sense.mms/u0a64 (adj 15): empty #17
D/Process (  959): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,E/WifiTrafficPoller(  959): TRAFFIC_STATS_POLL true Token 24 num clients 8
E/WifiTrafficPoller(  959):  packet count Tx=229 Rx=305
E/WifiTrafficPoller(  959): notifying of data activity 2
,D/WIFI_ICON( 1218): WifiActivity: 2
D/StatusBar.NetworkController( 1218): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_out_4 (gone) T]
,D/libc    (  395): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  395): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 6333): [NET] android_getaddrinfo_proxy-, success
,I/ActivityManager(  959): Recipient 6363
,I/Babel   ( 6333): connection state changed from UNKNOWN to CONNECTED,
,I/ActivityManager(  959): Killing 6556:com.google.android.apps.docs/u0a101 (adj 15): empty #17
D/Process (  959): killProcessQuiet, pid=6556
,D/Process (  959): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,D/VoldConnector(  959): SND -> {35 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/},
E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/
,W/ContextImpl( 6956): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,D/VoldConnector(  959): SND -> {36 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/}
W/ContextImpl( 6956): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files,
E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/
,I/GAv4    ( 6956): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6956):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6956):   adb logcat -s GAv4
,D/VoldConnector(  959): SND -> {37 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/}
E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/
W/ContextImpl( 6956): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,D/VoldConnector(  959): SND -> {38 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/}
,E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/
W/ContextImpl( 6956): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files,
,I/ActivityManager(  959): Recipient 6556,
,W/GAv4    ( 6956): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.,
,W/GAv4    ( 6956): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.,
,W/GAv4    ( 6956): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.,
,D/PMS     (  959): acquireWL(18a39313): PARTIAL_WAKE_LOCK  *alarm* 0x1 959 1000 WorkSource{10024}
V/AlarmManager(  959): sending alarm PendingIntent{28279950: PendingIntentRecord{3ddecbdb com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=108226, Int=0
,V/AlarmManager(  959): sending alarm PendingIntent{10768eb0: PendingIntentRecord{2e149129 android broadcastIntent}}, i=com.android.server.WifiManager.action.START_SCAN, t=1, cnt=1, w=1454523176481, Int=20000
,W/global  ( 6956): [apache-http] Connection GC has been deprecated!
,W/global  ( 6956): [apache-http] Connection GC has been deprecated!
,I/WebViewFactory( 6956): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
,I/LibraryLoader( 6956): Time to load native libraries: 1 ms (timestamps 8428-8429)
I/LibraryLoader( 6956): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6956): Binding Chromium to main looper Looper (main, tid 1) {2f1f1b7f},
,I/LibraryLoader( 6956): Expected native library version number "",actual native library version number ""
,E/WifiDataStallTracker(  959): DATA_MONITOR_POLL true Token 3
I/chromium( 6956): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6956): Initializing chromium process, singleProcess=true,
,W/art     ( 6956): Attempt to remove local handle scope entry from IRT, ignoring,
,E/SysUtils( 6956): ApplicationContext is null in ApplicationStatus,
,W/chromium( 6956): [WARNING:resource_bundle.cc(285)] locale_file_path.empty(),
,E/libEGL  ( 6956): validate_display:255 error 3008 (EGL_BAD_DISPLAY),
E/libEGL  ( 6956): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6956): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 6956): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6956): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6956): Local Branch: 
I/Adreno-EGL( 6956): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6956): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6956):                  d74aa161a12b9c6fc6332151
,W/AudioManagerAndroid( 6956): Requires BLUETOOTH permission,
,I/NSApplication( 6956): Starting up...,
,I/ActivityManager(  959): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7040 uid=10096 gids={50096, 9997, 3003, 1028, 1015} abi=arm64-v8a
,D/Process (  959): killProcessQuiet, pid=6420
I/ActivityManager(  959): Killing 6420:com.google.android.apps.plus/u0a167 (adj 15): empty #17
,D/Process (  959): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,E/WifiStateMachine(  959): handleMessage: E msg.what=131168
E/WifiStateMachine(  959): processMsg: ConnectedState
,E/WifiStateMachine(  959):  ConnectedState !CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  959): processMsg: L2ConnectedState
E/WifiStateMachine(  959):  L2ConnectedState !CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  959): processMsg: ConnectModeState
,E/WifiStateMachine(  959):  ConnectModeState !CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  959): processMsg: DriverStartedState
E/WifiStateMachine(  959):  DriverStartedState !CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  959): processMsg: SupplicantStartedState
,E/WifiStateMachine(  959):  SupplicantStartedState !CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  959): processMsg: DefaultState
E/WifiStateMachine(  959):  DefaultState !CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  959): handleMessage: X
,I/ActivityManager(  959): Recipient 6420,
,I/jxcore-log( 6676): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js,
I/jxcore-log( 6676): 
,D/libc    (  959): [NET] android_getaddrinfofornet+,hn 11(0x7777772e687463),sn(),hints(known),family 0,flags 4
,D/libc    (  959): [NET] android_getaddrinfofornet-, err=8
D/libc    (  959): [NET] android_getaddrinfofornet+,hn 11(0x7777772e687463),sn(),hints(known),family 0,flags 1024
D/libc    (  959): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  959): [NET] android_getaddrinfo_proxy+
D/libc    (  959): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  395): [NET] android_getaddrinfofornet+,hn 11(0x7777772e687463),sn(),hints(known),family 0,flags 1024
D/libc    (  395): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,E/WifiTrafficPoller(  959): TRAFFIC_STATS_POLL true Token 24 num clients 8
,E/WifiTrafficPoller(  959):  packet count Tx=234 Rx=310
E/WifiTrafficPoller(  959): notifying of data activity 3
D/WIFI_ICON( 1218): WifiActivity: 3
,D/StatusBar.NetworkController( 1218): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/ConnectivityService(  959): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE,
,D/GpsLocationProvider(  959): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
I/AlarmManager(  959): [AlarmQueuing] connectivity wifi: true
D/PMS     (  959): acquireWL(3ca47c2d): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 959 1000 null
,D/PMS     (  959): acquireWL(27acc562): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 959 1000 null
D/htcCheckinService(  959): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
D/PMS     (  959): releaseWL(27acc562): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/GpsLocationProvider(  959): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  959): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
I/ConnectivityHelper( 1547): [onReceive] WIFI(1): CONNECTED
I/NetworkMonitor( 6913): type=WIFI subType= reason=null isConnected=true
,E/GpsLocationProvider(  959): No APN found to select.
,D/PMS     (  959): releaseWL(3ca47c2d): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/MdScPhnSt( 6819): [caa.1.]  listen tmrbb8
,D/MdScDataSum( 6819): [caa.1.] summary 118:p1 ignore
,D/libc    (  395): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/HtcWifiWanDetect(  959): Find DNS Address www.htc.com/23.59.123.86
D/libc    (  395): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    (  959): [NET] android_getaddrinfo_proxy-, success
,I/ActivityManager(  959): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7067 uid=10167 gids={50167, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
D/Process (  959): killProcessQuiet, pid=5921
I/ActivityManager(  959): Killing 5921:com.google.android.googlequicksearchbox:search/u0a85 (adj 15): empty #17
D/Process (  959): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 ,
,I/ActivityManager(  959): Recipient 5921
,D/AccTypeManager( 1709): Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
,W/SystemReader(  959): Cannot find grip_rejection_width, use default value instead
,D/AccTypeManager( 1709): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/Prism.ItemManager( 1547): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
W/Prism.AllAppsManager( 1547): AllAppsMgr addApps, already exist: ApplicationInfo(id=33, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
,I/Prism.ItemManager( 1547): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,W/ResourcesManager(  959): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,W/ResourcesManager( 7067): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/Launcher( 1547): Deferring update until onResume
,D/Launcher( 1547): waitUntilResume // bindAppsUpdated
,D/AccTypeManager( 1709): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
D/PhoneApp( 1495): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,E/ExternalAccountType( 1709): Unsupported attribute readOnly
,W/PackageManager(  959): Unable to load service info ResolveInfo{4479728 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  959): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  959): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:475)
W/PackageManager(  959): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:331)
W/PackageManager(  959): 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
W/PackageManager(  959): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  959): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
W/PackageManager(  959): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
W/PackageManager(  959): 	at android.os.Handler.handleCallback(Handler.java:739)
W/PackageManager(  959): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  959): 	at android.os.Looper.loop(Looper.java:155)
W/PackageManager(  959): 	at com.android.server.SystemServer.run(SystemServer.java:324)
W/PackageManager(  959): 	at com.android.server.SystemServer.main(SystemServer.java:225)
W/PackageManager(  959): 	at java.lang.reflect.Method.invoke(Native Method)
W/PackageManager(  959): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/PackageManager(  959): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
W/PackageManager(  959): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,V/GmsNetworkLocationProvi( 1814): DISABLE
,I/GCoreNlp( 1814): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/PMS     (  959): acquireWL(16320756): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1814 10024 WorkSource{10024 com.google.android.gms},
D/LocationProviderProxy(  959): applying state to connected service
D/PMS     (  959): releaseWL(16320756): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
I/BackupManagerService(  959): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,D/LocationProviderProxy(  959): applying state to connected service
,D/PMS     (  959): acquireWL(38bc8673): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1814 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  959): acquireWL(92e7930): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1814 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  959): releaseWL(38bc8673): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  959): acquireWL(37b9f85c): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1814 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  959): releaseWL(92e7930): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  959): releaseWL(37b9f85c): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,V/AlarmManager(  959): sending alarm PendingIntent{c09772c: PendingIntentRecord{1a5f55f5 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=109656, Int=0,
,D/WeatherUtility( 1218): Weather sync is On,
W/WeatherTimeKeeper( 1218): [refreshWeatherData] no weather data
,I/ClockController( 1218): schedule update now=1454523180054 next=59946
,I/Clock   ( 1218): updateClock:19:13 Europe/Warsaw
I/Clock   ( 1218): updateClock:19:13 Europe/Warsaw
,I/Clock   ( 1218): updateClock:19:13 Europe/Warsaw
,D/PMS     (  959): acquireWL(3fe110c7): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1936 10024 WorkSource{10024 com.google.android.gms}
D/WifiDisplayAdapter(  959): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  959):     Client/Owner: Client
D/WifiDisplayAdapter(  959):     GroupId: 
D/WifiDisplayAdapter(  959):     Passphrase: 
D/WifiDisplayAdapter(  959):     SessionId: 0
D/WifiDisplayAdapter(  959):     IP Address: }
E/WifiStateMachine(  959): handleMessage: E msg.what=131143
E/WifiStateMachine(  959): processMsg: ConnectedState
,E/WifiStateMachine(  959): WiFiStateMachine SCAN ALARM
,V/MusicLeanback( 6913): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
D/PMS     (  959): releaseWL(18a39313): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
E/WifiStateMachine(  959):  ConnectedState !CMD_START_SCAN -2 -2 ic=5 proc(ms):1 dur:2158 rssi=-57 f=2412 sc=60 link=72 tx=57.8, 0.0, 0.0  rx=77.0 fiv=40000 [on:0 tx:0 rx:0 period:2848] from screen [on:0 period:-1470733280]
E/WifiStateMachine(  959): processMsg: L2ConnectedState
E/WifiStateMachine(  959):  L2ConnectedState !CMD_START_SCAN -2 -2 ic=5 proc(ms):4 dur:2158 rssi=-57 f=2412 sc=60 link=72 tx=57.8, 0.0, 0.0  rx=77.0 fiv=40000 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1470733277]
,D/libc    ( 1936): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
D/libc    ( 1936): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1936): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
E/WifiStateMachine(  959): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=57.75 rxSuccessRate=77.00 targetRoamBSSID=c0:ff:d4:d3:aa:48 RSSI=-57
D/libc    ( 1936): [NET] android_getaddrinfofornet-, pass to proxy
E/WifiStateMachine(  959): WifiStateMachine CMD_START_SCAN with age=10750 interval=40000 maxinterval=300000
D/libc    ( 1936): [NET] android_getaddrinfo_proxy+
E/WifiStateMachine(  959): WifiStateMachine CMD_START_SCAN prevent full band scan due to pkt rate
E/WifiStateMachine(  959): WifiStateMachine CMD_START_SCAN source -2 ...and ignore scans tx=57.75 rx=77.00
D/libc    ( 1936): [NET] android_getaddrinfo_proxy get netid:0
E/WifiStateMachine(  959): handleMessage: X
D/libc    (  395): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    (  395): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,D/AutoSetting( 1600): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/MobileConnectivityChangeReceiver( 6736): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6736): onReceive CONNECTIVITY_CHANGE networkType=1
,D/AutoSetting( 1600): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate,
D/AutoSetting( 1600): Util - check NLP state, Allowned:false, Enabled:false,
D/AutoSetting( 1600): service - requestNLP() NetworkLocationProvider not enabled
D/AutoSetting( 1600): service - onStartCommand() REMOVE current location bundle
D/AutoSetting( 1600): service - handleMessage() setting current location null
,I/jxcore-log( 6676): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 6676): 
,D/libc    (  395): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  395): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 1936): [NET] android_getaddrinfo_proxy-, success
,I/art     ( 3802): Explicit concurrent mark sweep GC freed 4997(245KB) AllocSpace objects, 0(0B) LOS objects, 73% free, 1505KB/5MB, paused 730us total 30.253ms
,I/PackageManager(  959):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=4431, uid=10024, userID:0
,D/ChimeraCfgMgr( 4431): Loading module com.google.android.gms.kids from APK com.google.android.gms
I/Kids    ( 4431): [GCoreUtils] Current gmscore version, 7899448 is smaller than the required version 8400000,
,D/libc    ( 1936): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
D/libc    ( 1936): [NET] android_getaddrinfofornet-, err=8
,D/PMS     (  959): acquireWL(2253f263): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 6333 10112 null
,D/libc    ( 1936): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
D/libc    ( 1936): [NET] android_getaddrinfofornet-, err=8
I/ActivityManager(  959): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=7106 uid=10085 gids={50085, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=arm64-v8a
,E/WifiStateMachine(  959): handleMessage: E msg.what=131155,
,E/WifiStateMachine(  959): processMsg: ConnectedState,
E/WifiStateMachine(  959):  ConnectedState !CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=57.8, 0.0, 0.0  rx=77.0 bcn=0 [on:0 tx:0 rx:0 period:145] from screen [on:0 period:-1470733131] gl hn u24 rssi=-52 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
D/PMS     (  959): releaseWL(2253f263): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,E/WifiStateMachine(  959): processMsg: L2ConnectedState
E/WifiStateMachine(  959):  L2ConnectedState !CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=57.8, 0.0, 0.0  rx=77.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1470733130] gl hn u24 rssi=-52 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  959):  get link layer stats 0
W/WifiHW  (  959): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/wpa_supplicant( 1351): wlan0: Control interface command 'SIGNAL_POLL'
I/jxcore-log( 6676): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 6676): 
D/WIFI_ICON( 1218): updateWifiState: RSSI_CHANGED 3 -> 3
I/wpa_supplicant( 1351): environment dirty rate=6 [15][1][0]
,D/StatusBar.NetworkController( 1218): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
E/WifiStateMachine(  959): fetchRssiLinkSpeedAndFrequencyNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 72
W/ResourcesManager( 6333): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
E/WifiStateMachine(  959): fetchRssiLinkSpeedAndFrequencyNative rssi=-57 linkspeed=72
W/ResourcesManager( 6333): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
E/WifiStateMachine(  959): fetchRssiLinkSpeedAndFrequencyNative send RSSIChange intent, SameSignalLevelCount =1
D/WIFI_ICON( 1218): updateWifiState: RSSI_CHANGED 3 -> 3
E/WifiConfigStore(  959): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-57 "NG700"WPA_PSK
D/StatusBar.NetworkController( 1218): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
D/WifiWatchdogStateMachine(  959): RSSI current: 3 new: -57, 3
E/WifiStateMachine(  959): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=36.38 txretriesrate=0.00 rxrate=44.00 userTriggerdPenalty0
,E/WifiStateMachine(  959):  good link -> stuck count =0
E/WifiStateMachine(  959):  badRSSI count0 lowRSSI count0 --> score 60
E/WifiStateMachine(  959):  isHighRSSI       ---> score=65
D/WifiWatchdogStateMachine(  959): RSSI current: 3 new: -57, 3
E/WifiStateMachine(  959): handleMessage: X
I/jxcore-log( 6676): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 6676): 
,E/WifiTrafficPoller(  959): TRAFFIC_STATS_POLL true Token 24 num clients 8
,E/WifiTrafficPoller(  959):  packet count Tx=243 Rx=316
,I/jxcore-log( 6676): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js,
I/jxcore-log( 6676): 
,I/jxcore-log( 6676): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 6676): 
,I/jxcore-log( 6676): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 6676): 
,I/jxcore-log( 6676): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 6676): 
,D/PMS     (  959): acquireWL(3f67e8b6): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1936 10024 WorkSource{10024 com.google.android.gms}
,D/GCM     ( 1936): Connected
,D/PMS     (  959): releaseWL(3fe110c7): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  959): releaseWL(3f67e8b6): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  959): acquireWL(1ae9b9b7): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1936 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  959): acquireWL(6a40524): PARTIAL_WAKE_LOCK  GOOGLE_C2DM 0x1 1936 10024 WorkSource{10024 com.google.android.gms},
,D/LocationManagerService(  959): getProviders()=[passive],
,D/GCM     ( 1936): Message class com.google.f.a.a.p
,D/PMS     (  959): releaseWL(1ae9b9b7): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms},
,I/ActivityManager(  959): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=7138 uid=10027 gids={50027, 9997, 3003} abi=arm64-v8a
,I/[PluginManager]RegisterService( 1600): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms,
I/[PluginManager]RegisterService( 1600): handle notify Blinkfeed plugin client changed
,I/ActivityManager(  959): Killing 5469:com.htc.mediamanager/u0a28 (adj 15): empty #17
D/Process (  959): killProcessQuiet, pid=5469
,D/Process (  959): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.attachApplicationLocked:6650 
,I/ActivityManager(  959): Recipient 5469
,D/PackageBroadcastService( 4431): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 4431): Null package name or gms related package.  Ignoreing.
,D/PMS     (  959): acquireWL(3240c45): PARTIAL_WAKE_LOCK  Icing 0x1 4431 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  959): acquireWL(14746f9a): PARTIAL_WAKE_LOCK  AsyncService 0x1 7067 10167 null
,I/Icing   ( 4431): updateResources: need to parse f{com.google.android.gms}
,D/PMS     (  959): releaseWL(14746f9a): PARTIAL_WAKE_LOCK  AsyncService 0x1 null,
,D/PMS     (  959): acquireWL(163480a8): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 7067 10167 null
,I/UpdateIcingCorporaServi( 7106): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/UpdateIcingCorporaServi( 7106): UpdateCorporaTask done [took 131 ms] updated apps [took 131 ms] 
,I/art     (  959): Explicit concurrent mark sweep GC freed 28307(1516KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 16MB/25MB, paused 1.493ms total 142.669ms
D/PMS     (  959): releaseWL(3240c45): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  959): releaseWL(163480a8): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 null
,I/GCM     ( 4431): Message from null null
E/GCM     ( 4431): Dropping message from null
,D/PMS     (  959): releaseWL(6a40524): PARTIAL_WAKE_LOCK  GOOGLE_C2DM 0x1 WorkSource{10024 com.google.android.gms}
,I/Prism.ItemManager( 1547): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1547): loadItems() com.htc.launcher.pageview.WidgetManager@32949248 +,
I/Prism.WidgetManager( 1547): onLoadItems() +
,W/ResourcesManager( 1547): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.,
,E/WifiDataStallTracker(  959): DATA_MONITOR_POLL true Token 3,
D/WifiDataStallTracker(  959): updateDataStallInfo: mDataStallTxRxSum={txSum=218 rxSum=197} preTxRxSum={txSum=0 rxSum=0},
D/WifiDataStallTracker(  959): updateDataStallInfo: IN/OUT
D/WifiDataStallTracker(  959): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,E/WifiTrafficPoller(  959): TRAFFIC_STATS_POLL true Token 24 num clients 8,
E/WifiTrafficPoller(  959):  packet count Tx=246 Rx=321
,W/ResourcesManager( 1547): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.,
,W/asset   ( 1547): Copying FileAsset 0x557b26f360 (zip:/data/app/com.gameloft.android.gdc-2/base.apk:/resources.arsc) to buffer size 405676 to make it aligned.,
,E/Prism.WidgetManager( 1547): The same lists. No need to update. skip it.,
I/Prism.WidgetManager( 1547): onLoadItems() -
I/Prism.ItemManager( 1547): loadItems() com.htc.launcher.pageview.WidgetManager@32949248 -
,D/PhoneApp( 1495): EVENT_QUERY_MO_PACKAGES,
,D/PhoneApp( 1495): -- N1 =0
D/PhoneApp( 1495): -- N2 =0,
D/PhoneApp( 1495): -- N3 =0
,E/WifiTrafficPoller(  959): TRAFFIC_STATS_POLL true Token 24 num clients 8
E/WifiTrafficPoller(  959):  packet count Tx=247 Rx=322
,D/PMS     (  959): acquireWL(3aa67ea7): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 6913 10159 null,
,I/PackageManager(  959):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=6913, uid=10159, userID:0,
,I/MusicLeanback( 6913): Conditions not met for autocaching. okToAttempt=false
D/PMS     (  959): releaseWL(3aa67ea7): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
I/MusicLeanback( 6913): Stop autocaching.
,D/WearableService( 5177): callingUid 10024, callindPid: 5177
,E/GmsUtils( 6913): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null},
E/GmsUtils( 6913): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/PMS     (  959): Going to sleep due to screen timeout (uid 1000)...,
I/SensorManager(  959): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@3be0633a
,W/SensorService(  959): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  959): disable: get sensor name = Accelerometer Sensor
W/SensorService(  959): pid=959, uid=1000
W/PMN     (  959): goingToSleep
W/SensorService(  959): Active sensors: size = 4
W/SensorService(  959): Accelerometer Sensor (handle=0x00000000, connections=1)
W/SensorService(  959): CM32181 Light sensor (handle=0x00000003, connections=1)
W/SensorService(  959): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  959): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  959): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@3be0633a, eanble = 0, strlen(mName) = 91
W/SensorService(  959): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  959): Listener[0] = com.android.server.display.AutomaticBrightnessController$1@346c219d
W/SensorService(  959): Listener[1] = com.htc.smartdim.sensor_eye@7da9963
W/SensorService(  959): void android::SensorService::listenerSensor(const char*, int32_t)--:
,W/HtcLockScreen( 1218): KeyguardViewMediator: doKeyguard: not showing because lockscreen is off,
,W/PMS     (  959): mWirelessDisplayManager is null
,D/PMS     (  959): acquireWL(1869fa16): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 959 1000 null
W/PMS     (  959): mWirelessDisplayManager is still null
,W/PMN     (  959): goingToSleep done
I/PMS     (  959): Sleeping (uid 1000)...
D/XAN-DPS (  959): prepareColorFade 1
D/AlarmManager(  959): ACTION_SCREEN_ON
W/HtcSystemUPManager(  959): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
,D/PMS     (  959): releaseWL(1869fa16): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,I/AlarmManager(  959): [AlarmQueuing] recover blocked alarms
,I/AlarmManager(  959): [AlarmQueuing] done recovering
I/AlarmManager(  959): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  959): [AlarmQueuing] done EPS screen off alarm recovering
,E/WifiTrafficPoller(  959): ENABLE_TRAFFIC_STATS_POLL true Token 24
,E/WifiTrafficPoller(  959):  packet count Tx=247 Rx=322
E/WifiTrafficPoller(  959): notifying of data activity 0
E/WifiDataStallTracker(  959): ENABLE_DATA_MONITOR_POLL true Token 3
,D/WifiDataStallTracker(  959): updateDataStallInfo: mDataStallTxRxSum={txSum=218 rxSum=197} preTxRxSum={txSum=218 rxSum=197}
D/WifiDataStallTracker(  959): updateDataStallInfo: NONE
D/WifiDataStallTracker(  959): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,E/WifiStateMachine(  959): handleMessage: E msg.what=131167
E/WifiStateMachine(  959): processMsg: ConnectedState
E/WifiStateMachine(  959):  ConnectedState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  959): processMsg: L2ConnectedState
E/WifiStateMachine(  959):  L2ConnectedState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  959): processMsg: ConnectModeState
E/WifiStateMachine(  959):  ConnectModeState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  959): processMsg: DriverStartedState
E/WifiStateMachine(  959):  DriverStartedState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  959): processMsg: SupplicantStartedState
E/WifiStateMachine(  959):  SupplicantStartedState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  959): processMsg: DefaultState
E/WifiStateMachine(  959):  DefaultState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  959):  handleScreenStateChanged Enter: screenOn=true mCurrentScanAlarmMs = 20000 mUserWantsSuspendOpt=false state ConnectedState suppState:CompletedState
W/WifiHW  (  959): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
D/wpa_supplicant( 1351): wlan0: Control interface command 'SET_SCREEN_ON 1'
I/wpa_supplicant( 1351): SET_SCREEN_ON:On
I/wpa_supplicant( 1351): htc_wext_set_keepalive +
I/wpa_supplicant( 1351): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1351): getPrivFuncNum +	
I/wpa_supplicant( 1351): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1351): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1351): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1351): htc_wext_set_TX_TRACKING (1)+
,I/wpa_supplicant( 1351): htc_wext_set_TX_TRACKING - ret = 0
E/WifiStateMachine(  959): setScanAlarm true period 20000 initial delay 200mAlarmEnabledtrue
D/WifiDisplayAdapter(  959): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  959):     Client/Owner: Client
D/WifiDisplayAdapter(  959):     GroupId: 
D/WifiDisplayAdapter(  959):     Passphrase: 
D/WifiDisplayAdapter(  959):     SessionId: 0
D/WifiDisplayAdapter(  959):     IP Address: }
D/WifiStateMachine(  959): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine(  959): handleScreenStateChanged Exit: true
E/WifiStateMachine(  959): handleMessage: X
E/WifiStateMachine(  959): handleMessage: E msg.what=131154
E/WifiStateMachine(  959): processMsg: ConnectedState
E/WifiStateMachine(  959):  ConnectedState !CMD_ENABLE_RSSI_POLL 1 0
E/WifiStateMachine(  959): processMsg: L2ConnectedState
E/WifiStateMachine(  959):  L2ConnectedState !CMD_ENABLE_RSSI_POLL 1 0
W/WifiHW  (  959): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1351): wlan0: Control interface command 'SIGNAL_POLL'
,D/WIFI_ICON( 1218): WifiActivity: 0
,I/Adreno-EGL(  959): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL(  959): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL(  959): Build Date: 03/09/15 Mon
I/Adreno-EGL(  959): Local Branch: 
I/Adreno-EGL(  959): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL(  959): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL(  959):                  d74aa161a12b9c6fc6332151
D/StatusBar.NetworkController( 1218): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/wpa_supplicant( 1351): environment dirty rate=0 [4][0][0]
E/WifiStateMachine(  959): fetchRssiLinkSpeedAndFrequencyNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 72
,E/WifiStateMachine(  959): fetchRssiLinkSpeedAndFrequencyNative rssi=-57 linkspeed=72
V/SRS_Proc(  402): ParamSet string: screen_state=on
E/WifiStateMachine(  959): fetchRssiLinkSpeedAndFrequencyNative send RSSIChange intent, SameSignalLevelCount =2
E/audio_a2dp_hw(  402): adev_set_parameters: ERROR: set param called even when stream out is null
E/WifiConfigStore(  959): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-57 "NG700"WPA_PSK
E/WifiStateMachine(  959): handleMessage: X
E/WifiStateMachine(  959): handleMessage: E msg.what=131127
E/WifiStateMachine(  959): processMsg: ConnectedState
,E/WifiStateMachine(  959):  ConnectedState !CMD_ENABLE_ALL_NETWORKS 0 0
E/WifiStateMachine(  959): processMsg: L2ConnectedState
E/WifiStateMachine(  959):  L2ConnectedState !CMD_ENABLE_ALL_NETWORKS 0 0
D/WIFI_ICON( 1218): updateWifiState: RSSI_CHANGED 3 -> 3
E/WifiStateMachine(  959): processMsg: ConnectModeState
D/StatusBar.NetworkController( 1218): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/WifiStateMachine(  959):  ConnectModeState !CMD_ENABLE_ALL_NETWORKS 0 0
E/WifiStateMachine(  959): handleMessage: X
,E/WifiStateMachine(  959): handleMessage: E msg.what=131129
E/WifiStateMachine(  959): processMsg: ConnectedState
E/WifiStateMachine(  959):  ConnectedState !CMD_CLEAR_BLACKLIST 0 0
E/WifiStateMachine(  959): processMsg: L2ConnectedState
E/WifiStateMachine(  959):  L2ConnectedState !CMD_CLEAR_BLACKLIST 0 0
E/WifiStateMachine(  959): processMsg: ConnectModeState
E/WifiStateMachine(  959):  ConnectModeState !CMD_CLEAR_BLACKLIST 0 0
D/WifiWatchdogStateMachine(  959): RSSI current: 3 new: -57, 3
W/WifiHW  (  959): QCOM Debug wifi_send_command "IFNAME=wlan0 BLACKLIST clear"
D/WifiController(  959): handleMessage: E msg.what=155650
D/wpa_supplicant( 1351): wlan0: Control interface command 'BLACKLIST clear'
E/wpa_supplicant( 1351): wlan0: BLACKLIST CLEAR 
D/WifiController(  959): processMsg: DeviceActiveState
D/WifiController(  959): processMsg: StaEnabledState
D/WifiMonitor(  959): Event [IFNAME=wlan0 BLACKLIST CLEAR ]
E/WifiMonitor(  959): WifiMonitor:wlan0 cnt=47 dispatchEvent: BLACKLIST CLEAR 
D/WifiController(  959): processMsg: DefaultState
E/WifiStateMachine(  959): handleMessage: X
,D/WifiController(  959): handleMessage: X
,D/NetworkPolicy(  959): updateScreenOn: false
V/NetworkPolicy(  959): updateIfacesLocked()
D/DotMatrix( 1304): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/NetworkManagementService(  959): isBandwidthControlEnabled: doneSignal.getCount()= 0
,D/GpsLocationProvider(  959): receive broadcast intent, action: android.intent.action.SCREEN_ON
,I/IntentController( 1218): receive(android.intent.action.SCREEN_ON,1,false)
,I/ActivityManager(  959): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=7184 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a,
,D/PMS     (  959): acquireWL(1903a1a2): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1814 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  959): acquireWL(27175e33): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1814 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  959): releaseWL(1903a1a2): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,D/XAN-DPS (  959): prepareColorFade done
D/PMS     (  959): releaseWL(27175e33): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,D/XAN-DPS (  959): setBrightness to 0
,W/ContextImpl( 7184): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,I/SensorManager(  959): unregisterListenerImpl++: listener = com.android.server.display.AutomaticBrightnessController$1@346c219d
,W/SensorService(  959): Following SensorService logs are not warning, just make sure they are printed
I/DisplayManagerService(  959): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 442.451 x 443.345 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,W/SensorService(  959): disable: get sensor name = CM32181 Light sensor
,W/SensorService(  959): pid=959, uid=1000,
W/SensorService(  959): Active sensors: size = 3
V/ActivityManager(  959): Display changed displayId=0
W/SensorService(  959): Accelerometer Sensor (handle=0x00000000, connections=1)
W/ContextImpl( 7184): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:22 android.app.ActivityThread.handleReceiver:2712 
W/SensorService(  959): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  959): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  959): SensorService::listenerSensor++: mName = com.android.server.display.AutomaticBrightnessController$1@346c219d, eanble = 0, strlen(mName) = 67
W/SensorService(  959): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  959): Listener[0] = com.htc.smartdim.sensor_eye@7da9963
,W/SensorService(  959): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/DotMatrix( 1304): [EventService]  onDisplayChanged: 0
E/qdutils (  387): int qdutils::getHDMINode(): Failed to open fb node 2
E/qdutils (  387): int qdutils::getHDMINode(): Failed to find HDMI node
,D/AlarmManager(  959): ACTION_SCREEN_OFF
,I/AlarmManager(  959): [AlarmQueuing] screen off now: 
I/AlarmManager(  959): [AlarmQueuing] data connection: true
I/AlarmManager(  959): [AlarmQueuing] wifi connection: true
D/PowerUsageList:PowerUsageHelper( 7184): MY_DEBUG = false
E/WifiTrafficPoller(  959): ENABLE_TRAFFIC_STATS_POLL false Token 25
D/WifiDataStallTracker(  959): stopDataStallAlarm 
E/WifiDataStallTracker(  959): ENABLE_DATA_MONITOR_POLL false Token 4
E/WifiStateMachine(  959): handleMessage: E msg.what=131167
E/WifiStateMachine(  959): processMsg: ConnectedState
E/WifiStateMachine(  959):  ConnectedState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  959): processMsg: L2ConnectedState
E/WifiStateMachine(  959):  L2ConnectedState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  959): processMsg: ConnectModeState
E/WifiStateMachine(  959):  ConnectModeState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  959): processMsg: DriverStartedState
E/WifiStateMachine(  959):  DriverStartedState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  959): processMsg: SupplicantStartedState
E/WifiStateMachine(  959):  SupplicantStartedState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  959): processMsg: DefaultState
V/SRS_Proc(  402): ParamSet string: screen_state=off
E/WifiStateMachine(  959):  DefaultState !CMD_SCREEN_STATE_CHANGED 0 0
D/DotMatrix( 1304): [EventService] mbHDMIConnect: false, mCoverOn:false
E/WifiStateMachine(  959):  handleScreenStateChanged Enter: screenOn=false mCurrentScanAlarmMs = 20000 mUserWantsSuspendOpt=false state ConnectedState suppState:CompletedState
W/WifiHW  (  959): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
E/audio_a2dp_hw(  402): adev_set_parameters: ERROR: set param called even when stream out is null
D/wpa_supplicant( 1351): wlan0: Control interface command 'SET_SCREEN_ON 0'
I/wpa_supplicant( 1351): SET_SCREEN_ON:Off
I/wpa_supplicant( 1351): htc_wext_set_keepalive +
I/wpa_supplicant( 1351): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1351): getPrivFuncNum +	
I/wpa_supplicant( 1351): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1351): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1351): get_ip_address source addr = c0a80182
I/wpa_supplicant( 1351): htc_wext_set_keepalive gateway addr = c0a80101
D/WifiDisplayAdapter(  959): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  959):     Client/Owner: Client
D/WifiDisplayAdapter(  959):     GroupId: 
D/WifiDisplayAdapter(  959):     Passphrase: 
D/WifiDisplayAdapter(  959):     SessionId: 0
D/WifiDisplayAdapter(  959):     IP Address: }
I/wpa_supplicant( 1351): htc_wext_set_keepalive - ret = 0
E/WifiStateMachine(  959): setScanAlarm false period 20000 initial delay 0mAlarmEnabledtrue
D/WifiController(  959): handleMessage: E msg.what=155651
D/WifiController(  959): processMsg: DeviceActiveState
D/WifiController(  959): processMsg: StaEnabledState
D/WifiController(  959): processMsg: DefaultState
D/WifiController(  959): handleMessage: X
D/WifiStateMachine(  959): backgroundScan enabled=true startBackgroundScanIfNeeded:false
E/WifiStateMachine(  959): handleScreenStateChanged Exit: false
E/WifiStateMachine(  959): handleMessage: X
E/WifiStateMachine(  959): handleMessage: E msg.what=131154
E/WifiStateMachine(  959): processMsg: ConnectedState
D/NetworkPolicy(  959): updateScreenOn: false
V/NetworkPolicy(  959): updateIfacesLocked()
E/WifiStateMachine(  959):  ConnectedState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  959): processMsg: L2ConnectedState
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,E/WifiStateMachine(  959):  L2ConnectedState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  959): handleMessage: X
D/NetworkManagementService(  959): isBandwidthControlEnabled: doneSignal.getCount()= 0
D/DotMatrix( 1304): [EventService] getTotalRam: 1842 Mb
,D/SmartSyncUtils( 7184): isEpsOn(), nState = 0
,D/PMS     (  959): acquireWL(3fcd611c): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 7184 1000 null,
,I/SensorManager( 1218): registerListenerImpl: listener = com.htc.sense.easyaccessservice.SensorHubService@235df1ff, sensor = {Sensor name="hTC Gesture Motion HIDI", vendor="hTC Corp.", version=1, type=10, maxRange=200.0, resolution=1.0, power=0.2, minDelay=0}, delay = 200000, handler = null
,W/SensorService(  959): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  959): enable: get sensor name = hTC Gesture Motion HIDI
,W/SensorService(  959): pid=1218, uid=10041,
W/SensorService(  959): Active sensors: size = 4
W/SensorService(  959): Accelerometer Sensor (handle=0x00000000, connections=1)
W/SensorService(  959): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  959): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  959): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
W/SensorService(  959): SensorService::listenerSensor++: mName = com.htc.sense.easyaccessservice.SensorHubService@235df1ff, eanble = 1, strlen(mName) = 57
W/SensorService(  959): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  959): Listener[0] = com.htc.smartdim.sensor_eye@7da9963
W/SensorService(  959): Listener[1] = com.htc.sense.easyaccessservice.SensorHubService@235df1ff
W/SensorService(  959): void android::SensorService::listenerSensor(const char*, int32_t)--:
,D/PMS     (  959): releaseWL(3fcd611c): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/GpsLocationProvider(  959): receive broadcast intent, action: android.intent.action.SCREEN_OFF
W/ContextImpl(  959): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2712 
,D/SmartDim(  959): Init customizeScreenOffDelayClass error
,D/ContactMessageStore( 1495): start background delete task...,
,I/IntentController( 1218): receive(android.intent.action.SCREEN_OFF,1,false)
,D/ContactMessageStore( 1495): size: 0 , 0
,D/ContactMessageStore( 1495): Background delete complete
D/PMS     (  959): acquireWL(35b11125): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1814 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  959): releaseWL(35b11125): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  959): acquireWL(373bc2fa): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1814 10024 WorkSource{10024 com.google.android.gms}
,W/ContextImpl( 7184): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
D/PMS     (  959): releaseWL(373bc2fa): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,W/ContextImpl( 7184): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:22 android.app.ActivityThread.handleReceiver:2712 
,D/SmartSyncUtils( 7184): isEpsOn(), nState = 0
,D/SmartSyncUtils( 7184): isEpsOn(), nState = 0
,E/WifiStateMachine(  959): handleMessage: E msg.what=131155
,E/WifiStateMachine(  959): processMsg: ConnectedState
E/WifiStateMachine(  959):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1470730124] gl hn u24 rssi=-52 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,W/ContextImpl( 7184): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:73 android.app.ActivityThread.handleReceiver:2712 
E/WifiStateMachine(  959): processMsg: L2ConnectedState
E/WifiStateMachine(  959):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1470730123] gl hn u24 rssi=-52 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,E/WifiStateMachine(  959): handleMessage: X
,W/ContextImpl(  959): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1830 android.content.ContextWrapper.stopService:520 android.content.ContextWrapper.stopService:520 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2712 
,I/SensorManager(  959): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@7da9963
,W/SensorService(  959): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  959): disable: get sensor name = Accelerometer Sensor
,W/SensorService(  959): pid=959, uid=1000
,W/SensorService(  959): Active sensors: size = 3
W/SensorService(  959): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  959): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  959): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
W/SensorService(  959): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@7da9963, eanble = 0, strlen(mName) = 35
W/SensorService(  959): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  959): Listener[0] = com.htc.sense.easyaccessservice.SensorHubService@235df1ff
W/SensorService(  959): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  959): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  959): disable: get sensor name = CM36686 Proximity sensor
,W/SensorService(  959): pid=959, uid=1000
W/SensorService(  959): Active sensors: size = 2
W/SensorService(  959): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  959): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
W/SensorService(  959): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@7da9963, eanble = 0, strlen(mName) = 35
W/SensorService(  959): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  959): Listener[0] = com.htc.sense.easyaccessservice.SensorHubService@235df1ff
W/SensorService(  959): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  959): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@7da9963
,E/ActivityThread(  959): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@3861a960 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  959): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@3861a960 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  959): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:1003)
E/ActivityThread(  959): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:767)
E/ActivityThread(  959): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1775)
E/ActivityThread(  959): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1755)
E/ActivityThread(  959): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:495)
E/ActivityThread(  959): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  959): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  959): 	at android.app.Service.onStartCommand(Service.java:458)
E/ActivityThread(  959): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3072)
E/ActivityThread(  959): 	at android.app.ActivityThread.access$2100(ActivityThread.java:144)
E/ActivityThread(  959): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1470)
E/ActivityThread(  959): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  959): ,	at android.os.Looper.loop(Looper.java:155)
E/ActivityThread(  959): 	,at com.android.server.SystemServer.run(SystemServer.java:324)
E/ActivityThread(  959): 	at com.android.server.SystemServer.main(SystemServer.java:225)
E/ActivityThread(  959): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread(  959): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread(  959): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/ActivityThread(  959): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,I/RemoteViews( 1218): setHTCTheme(com.htc.updater,true,33751145)
,I/RemoteViews( 1218): apply : com.htc.updater 1 8 1 36,
,E/WifiTrafficPoller(  959): TRAFFIC_STATS_POLL false Token 26 num clients 8,
,I/PowerUsageList:PowerUsageHelper( 7184): PowerProfile::POWER_SCREEN_FULL = 154.8
,D/AutoSetting( 1600): service - mHandler: cancel location update,
D/AutoSetting( 1600): service -           changes count: 0
,D/SmartSyncUtils( 7184): getMobilePolicyEnabled, result = true,
D/PowerUsageList:BatterySipperExt( 7184): gen(), null == sipper.uidObj, userId = 0
,E/WifiTrafficPoller(  959): ADD_CLIENT: 9,
D/WifiService(  959): New client listening to asynchronous messages
,E/qdutils (  387): int qdutils::getHDMINode(): Failed to open fb node 2
D/PMS     (  959): Setting HAL interactive mode to false
,E/qdutils (  387): int qdutils::getHDMINode(): Failed to find HDMI node
D/PMS     (  959): Setting HAL interactive mode to false done
D/SurfaceControl(  959): Excessive delay in setPowerMode(): 296ms
D/PMS     (  959): Setting HAL auto-suspend mode to true
,W/HtcSystemUPManager(  959): HtcSystemUPHandler The policy is disabled. AppId: UTD_BI, category: C0006
D/PMS     (  959): Setting HAL auto-suspend mode done
I/InputMethodManager( 6676): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{12bdf4fd VFEDH.C. .F...... 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@7f5cc89
D/HABCtrl (  959): TPE algorithm. remove timeout.
I/IntentController( 1218): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
D/PMS     (  959): OOBE c monitor 11
I/PhoneStatusBar( 1218): setImeWindowStatus(false,false)
I/InputMethodManagerService(  959): screenObserver, isScreenOn=false
D/StatusBarManagerService(  959): swetImeWindowStatus vis=0 backDisposition=0
,I/InputManager(  959): Cancel all due to getting PMS screen off broadcast. ActualScreenOn=false
I/InputMethodManagerService(  959): Disable input method client, pid=6676
,D/PMS     (  959): acquireWL(b869aa1): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 959 1000 null
,I/BatteryService(  959): n_update end
D/PMS     (  959): releaseWL(b869aa1): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/NotificationService(  959): plugged=true pluggin=true
D/UsbnetService(  959): BroadcastReceiver::onReceive+
D/UsbnetService(  959): onReceive BATTERY_CHANGED
D/UsbnetService(  959):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  959): BroadcastReceiver::onReceive-
D/WifiController(  959): handleMessage: E msg.what=155652
D/WifiController(  959): processMsg: DeviceActiveState
D/WifiController(  959): processMsg: StaEnabledState
D/WifiController(  959): battery changed pluggedType: 2
D/WifiController(  959): processMsg: DefaultState
D/WifiController(  959): handleMessage: X
,D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1304): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  959): updateBatteryInfo
D/PMS     (  959): runPSCheck
D/HtcPowerSaver(  959): Checking...
I/HtcPowerSaver(  959): >> updateStatus
D/HeadsetStateMachine( 3098): Disconnected process message: 10, size: 0
I/IntentController( 1218): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1218): closing low battery warning: level=100
,D/PowerUI ( 1218): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/NfcService( 1520): applyRouting - 0
D/NfcService( 1520): ScreenObserver: OFF
,D/PMS     (  959): acquireWL(24f314c6): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1520 1027 null
D/NfcService( 1520): applyRouting -2
I/HtcPowerSaver(  959): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  959): << updateStatus
D/NfcService( 1520): applyRouting
D/NfcService( 1520): Ignore this applyRouting...
,D/PMS     (  959): releaseWL(24f314c6): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,D/PowerUsageList:PowerUsageHelper( 7184): MY_DEBUG = false
,I/ClockController( 1218): stop clock update:screen off
,I/BatteryController( 1218): status:5 level:100 unsupport:false plugged:true,
,D/Process (  959): killProcessQuiet, pid=6615
I/ActivityManager(  959): Killing 6615:com.google.android.gms.unstable/u0a24 (adj 15): empty #17
D/Process (  959): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  959): Recipient 6615
,E/WifiTrafficPoller(  959): TRAFFIC_STATS_POLL false Token 26 num clients 9,
,D/PMS     (  959): releaseWL(16d65ed8): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 null,
,D/Process (  959): killProcessQuiet, pid=6859
,I/ActivityManager(  959): Killing 6859:com.htc.calendar/u0a10 (adj 15): empty #17
D/Process (  959): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  959): Recipient 6859,
,I/ActivityManager(  959): Killing 6980:com.htc.mms.backupagent/u0a76 (adj 15): empty #17
D/Process (  959): killProcessQuiet, pid=6980
D/Process (  959): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  959): Recipient 6980,
,E/WifiStateMachine(  959): handleMessage: E msg.what=131155,
E/WifiStateMachine(  959): processMsg: ConnectedState
E/WifiStateMachine(  959):  ConnectedState CMD_RSSI_POLL 3 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2638] from screen [on:0 period:-1470727485] gl hn u24 rssi=-52 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  959): processMsg: L2ConnectedState
E/WifiStateMachine(  959):  L2ConnectedState CMD_RSSI_POLL 3 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1470727483] gl hn u24 rssi=-52 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  959): handleMessage: X
,I/jxcore-log( 6676): Test app app.js loaded,
I/jxcore-log( 6676): 
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6676): load: ,
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6676): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6676): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6676): 	Bluetooth MAC address: null, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6676): 	Discovery mode: BLE, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6676): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6676): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6676): 	Advertise TX power level: 1, ,
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6676): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6676): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f0048e added. We now have 1 listener(s)
D/BluetoothAdapter( 6676): 576667575: getState(). Returning 12
I/jxcore-log( 6676): BLE advertisement is supported
I/jxcore-log( 6676): 
,I/chromium( 6676): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/HtcUPManager( 1218): HtcUPServiceProxy onTrimMemory() has been called. Memory Level: 60,
,E/WifiDataStallTracker(  959): DATA_MONITOR_POLL false Token 5,
,E/WifiDataStallTracker(  959): DATA_MONITOR_POLL false Token 5,
,D/ContactMessageStore( 1495): MSG_NOTIFY_CS_TO_SYNC >>,
D/ContactMessageStore( 1495): MSG_NOTIFY_CS_TO_SYNC <<
,W/Atfwd_Sendcmd(  473): AtCmdFwd service not published, waiting... retryCnt : 1,
,W/Atfwd_Sendcmd(  473): AtCmdFwd service not published, waiting... retryCnt : 2,
,I/ActivityManager(  959): Killing 5625:com.htc.musicenhancer/u0a49 (adj 15): empty #17,
D/Process (  959): killProcessQuiet, pid=5625
D/Process (  959): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  959): Recipient 5625,
,D/PMS     (  959): acquireWL(22f85c87): PARTIAL_WAKE_LOCK  *alarm* 0x1 959 1000 WorkSource{10024},
V/AlarmManager(  959): sending alarm PendingIntent{275ab7b4: PendingIntentRecord{2ed13fdd com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=142865, Int=0
,D/PMS     (  959): releaseWL(22f85c87): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10024}
,D/AutoSetting( 1600): service - handleMessage() stop self,
,D/AutoSetting( 1600): service - handleMessage() quit looper
,D/AutoSetting( 1600): service - onDestroy() END
,E/WifiStateMachine(  959): handleMessage: E msg.what=131165
E/WifiStateMachine(  959): processMsg: ConnectedState
,E/WifiStateMachine(  959):  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  959): processMsg: L2ConnectedState
E/WifiStateMachine(  959):  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  959): processMsg: ConnectModeState
E/WifiStateMachine(  959):  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,E/WifiStateMachine(  959): processMsg: DriverStartedState
E/WifiStateMachine(  959):  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,E/WifiStateMachine(  959): processMsg: SupplicantStartedState
E/WifiStateMachine(  959):  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  959): processMsg: DefaultState
E/WifiStateMachine(  959):  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  959): handleMessage: X,
,W/Atfwd_Sendcmd(  473): AtCmdFwd service not published, waiting... retryCnt : 3
,D/GpsLocationProvider(  959): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  959): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
,D/PMS     (  959): acquireWL(327bb752): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 959 1000 null
,D/libc    (  959): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 4
D/libc    (  959): [NET] android_getaddrinfofornet-, err=8
D/libc    (  959): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024
D/libc    (  959): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  959): [NET] android_getaddrinfo_proxy+
D/libc    (  959): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  395): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024,
D/libc    (  395): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,D/libc    (  395): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  395): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    (  959): [NET] android_getaddrinfo_proxy-, success
D/libc    (  959): [NET] android_getaddrinfofornet+,hn 14(0x35342e3233392e),sn(),hints(known),family 0,flags 4
D/libc    (  959): [NET] android_getaddrinfofornet-, SUCCESS
,D/GpsLocationProvider(  959): [handleDownloadXtraData] calling native_inject_xtra_data,
,D/GpsLocationProvider(  959): [reportHTCStatus] eventMask = 3 , status = 0,
D/GpsLocationProvider(  959): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  959):  [handleDownloadXtraData]inject done.
D/PMS     (  959): acquireWL(1879f69e): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 959 1000 null
D/GpsLocationProvider(  959): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/PMS     (  959): releaseWL(327bb752): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 null
D/PMS     (  959): releaseWL(1879f69e): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/ContextImpl(  959): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 ,
,E/WifiStateMachine(  959): handleMessage: E msg.what=131326,
,E/WifiStateMachine(  959): processMsg: ConnectedState
E/WifiStateMachine(  959):  ConnectedState what:131326 2 0
E/WifiStateMachine(  959): processMsg: L2ConnectedState
E/WifiStateMachine(  959):  L2ConnectedState what:131326 2 0
E/WifiStateMachine(  959): handleMessage: X
,W/Atfwd_Sendcmd(  473): AtCmdFwd service not published, waiting... retryCnt : 4,
,D/PMS     (  959): acquireWL(3146557f): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 959 1000 null,
I/BatteryService(  959): n_update end
D/PMS     (  959): releaseWL(3146557f): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/IntentController( 1218): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HeadsetStateMachine( 3098): Disconnected process message: 10, size: 0
D/PowerUI ( 1218): closing low battery warning: level=100
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  959): updateBatteryInfo
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1218): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1304): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/NotificationService(  959): plugged=true pluggin=true
D/UsbnetService(  959): BroadcastReceiver::onReceive+
,D/PMS     (  959): runPSCheck
D/UsbnetService(  959): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  959): Checking...
D/UsbnetService(  959):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/HtcPowerSaver(  959): >> updateStatus
D/UsbnetService(  959): BroadcastReceiver::onReceive-
D/WifiController(  959): battery changed pluggedType: 2
D/WifiController(  959): handleMessage: E msg.what=155652
I/HtcPowerSaver(  959): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  959): processMsg: DeviceActiveState
,I/HtcPowerSaver(  959): << updateStatus
D/WifiController(  959): processMsg: StaEnabledState
D/WifiController(  959): processMsg: DefaultState
D/WifiController(  959): handleMessage: X
,I/BatteryController( 1218): status:5 level:100 unsupport:false plugged:true,
,D/TelephonyReceiver( 1495): switchBindHtcMsgCursor: null
,W/Atfwd_Sendcmd(  473): AtCmdFwd service not published, waiting... retryCnt : 5,
,D/PMS     (  959): acquireWL(839494c): PARTIAL_WAKE_LOCK  *alarm* 0x1 959 1000 WorkSource{1000}
V/AlarmManager(  959): sending alarm PendingIntent{31818d95: PendingIntentRecord{238adeaa android broadcastIntent}}, i=android.app.backup.intent.INIT, t=0, cnt=1, w=1454523239884, Int=0
V/AlarmManager(  959): sending alarm PendingIntent{c09772c: PendingIntentRecord{1a5f55f5 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=169655, Int=0
D/PMS     (  959): acquireWL(1374ca9b): PARTIAL_WAKE_LOCK  *backup* 0x1 959 1000 null
V/AlarmManager(  959): sending alarm PendingIntent{2d57ae38: PendingIntentRecord{3cba6e11 android broadcastIntent}}, i=com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE, t=2, cnt=1, w=204268, Int=0
V/AlarmManager(  959): sending alarm PendingIntent{1b103b76: PendingIntentRecord{2b4b7577 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=190878, Int=0
,D/PMS     (  959): acquireWL(3df575e4): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1936 10024 WorkSource{10024 com.google.android.gms},
,W/BackupManagerService(  959): Requested unavailable transport: com.google.android.gms.backup.BackupTransportService
,E/BackupManagerService(  959): Requested init for com.google.android.gms.backup.BackupTransportService but not found
,D/PMS     (  959): releaseWL(1374ca9b): PARTIAL_WAKE_LOCK  *backup* 0x1 null
,D/PMS     (  959): releaseWL(839494c): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,D/WeatherUtility( 1218): Weather sync is On
W/WeatherTimeKeeper( 1218): [refreshWeatherData] no weather data
,D/PMS     (  959): acquireWL(3dc6da4d): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1936 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  959): releaseWL(3df575e4): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,V/GLSActivity( 1936): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/PMS     (  959): releaseWL(3dc6da4d): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  959): acquireWL(3de59c6f): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1936 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  959): releaseWL(3de59c6f): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
D/PMS     (  959): acquireWL(3d479d7c): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1936 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  959): releaseWL(3d479d7c): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
D/PMS     (  959): acquireWL(33620605): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1936 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  959): acquireWL(2b70465a): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1936 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  959): acquireWL(282f1568): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1936 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  959): releaseWL(33620605): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,I/VacuumService( 1936): Vacuum at: now=1454523274920 tag=VacuumService,
,D/PMS     (  959): releaseWL(2b70465a): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  959): acquireWL(3ddc6e26): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1936 10024 WorkSource{10024 com.google.android.gms}
,I/GoogleURLConnFactory( 1936): Using platform SSLCertificateSocketFactory,
,W/Uploader( 1936): No account for auth token provided,
,D/PMS     (  959): releaseWL(3ddc6e26): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  959): acquireWL(d4ff0bd): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1936 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  959): releaseWL(d4ff0bd): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/libc    ( 1936): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4,
D/libc    ( 1936): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1936): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 1936): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1936): [NET] android_getaddrinfo_proxy+
D/libc    ( 1936): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  395): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  395): [NET] _dns_getaddrinfo+, netid:101, mark:917605,
,D/libc    (  395): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  395): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 1936): [NET] android_getaddrinfo_proxy-, success
,D/libc    ( 1936): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4,
D/libc    ( 1936): [NET] android_getaddrinfofornet-, err=8,
D/libc    ( 1936): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4,
,D/libc    ( 1936): [NET] android_getaddrinfofornet-, err=8
,W/Uploader( 1936): No account for auth token provided,
,W/Uploader( 1936): No account for auth token provided,
,W/Uploader( 1936):  no longer exists, so no auth token.,
,W/Uploader( 1936): No account for auth token provided,
,I/GLSUser ( 1936): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog,
I/GLSUser ( 1936): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1936): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1936): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1936): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/DotMatrix( 1304): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true,
D/DotMatrix( 1304): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
I/RemoteViews( 1218): reapply : com.google.android.gms 3 40
,E/Uploader( 1936): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1936): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1936): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1936): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1936): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1936): ,	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1936): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1936): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1936): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1936): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1936): 	,at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1936): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1936): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/GLSUser ( 1936): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog,
I/GLSUser ( 1936): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1936): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1936): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1936): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/Uploader( 1936): Failed to get auth token: User intervention required. Notification has been pushed.,
E/Uploader( 1936): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1936): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1936): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1936): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1936): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1936): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1936): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1936): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1936): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1936): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1936): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1936): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
D/DotMatrix( 1304): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1304): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1218): reapply : com.google.android.gms 3 40
,W/Uploader( 1936): No account for auth token provided
,I/GLSUser ( 1936): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1936): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1936): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1936): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1936): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1936): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1936): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1936): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1936): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1936): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1936): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1936): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1936): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1936): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1936): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1936): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1936): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1936): ,	at com.google.android.gms.gcm.am.run(SourceFile:135)
D/DotMatrix( 1304): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1304): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1218): reapply : com.google.android.gms 3 40
,D/PMS     (  959): releaseWL(282f1568): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  959): acquireWL(2609fe4f): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1936 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  959): releaseWL(2609fe4f): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  959): acquireWL(3dd789dc): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1936 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  959): releaseWL(3dd789dc): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/HtcUPManager( 1218): HtcUPServiceProxy Disconnect from  UP serivce: No interaction with app,
D/HtcAppUPService( 1600): HtcUPService [##] onDestroy(), this =com.htc.sense.hsp.upservice.HtcUPService@177cd04d
,D/HtcUPManager( 1218): HtcUPServiceProxy Disconnect from UP service. Change state to: DISCONNECTED
D/Process (  959): killProcessQuiet, pid=6776
I/ActivityManager(  959): Killing 6776:com.htc.mobiledata/u0a46 (adj 15): empty #17
D/Process (  959): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  959): Recipient 6776,
,W/Atfwd_Sendcmd(  473): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  959): acquireWL(3ceeeae5): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 959 1000 null
I/BatteryService(  959): n_update end
D/PMS     (  959): releaseWL(3ceeeae5): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  959): updateBatteryInfo
D/NotificationService(  959): plugged=true pluggin=true
D/PMS     (  959): runPSCheck
D/HtcPowerSaver(  959): Checking...
I/HtcPowerSaver(  959): >> updateStatus
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1304): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HeadsetStateMachine( 3098): Disconnected process message: 10, size: 0
,I/IntentController( 1218): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1218): closing low battery warning: level=100
,D/UsbnetService(  959): BroadcastReceiver::onReceive+
I/HtcPowerSaver(  959): updateStatus (8000,100,-1,false,false,false,-1)
D/UsbnetService(  959): onReceive BATTERY_CHANGED
I/HtcPowerSaver(  959): << updateStatus
D/UsbnetService(  959):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PowerUI ( 1218): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  959): BroadcastReceiver::onReceive-
,D/WifiController(  959): battery changed pluggedType: 2
D/WifiController(  959): handleMessage: E msg.what=155652
D/WifiController(  959): processMsg: DeviceActiveState
D/WifiController(  959): processMsg: StaEnabledState
D/WifiController(  959): processMsg: DefaultState
D/WifiController(  959): handleMessage: X
,I/BatteryController( 1218): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  473): AtCmdFwd service not published, waiting... retryCnt : 2
,W/Atfwd_Sendcmd(  473): AtCmdFwd service not published, waiting... retryCnt : 3
,I/jxcore-log( 6676): TAP version 13
I/jxcore-log( 6676): 
,I/jxcore-log( 6676): # setup
I/jxcore-log( 6676): 
,I/jxcore-log( 6676): not ok 1 ReferenceError: _name is not defined
I/jxcore-log( 6676): ,
I/jxcore-log( 6676):   ---
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     operator: error
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     expected: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       undefined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     actual: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       [ReferenceError: _name is not defined]
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     stack: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:61:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       $v@timers.js:363:1
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ...
I/jxcore-log( 6676): 
,I/jxcore-log( 6676): # multiplex can send data
I/jxcore-log( 6676): 
,I/jxcore-log( 6676): not ok 2 ReferenceError: _name is not defined
I/jxcore-log( 6676): 
,I/jxcore-log( 6676):   ---
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     operator: error
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     expected: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       undefined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     actual: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       [ReferenceError: _name is not defined]
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     stack: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:84:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       $v@timers.js:363:1
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ...
I/jxcore-log( 6676): 
,I/jxcore-log( 6676): # teardown
I/jxcore-log( 6676): 
,I/jxcore-log( 6676): not ok 3 ReferenceError: _name is not defined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ---
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     operator: error
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     expected: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       undefined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     actual: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       [ReferenceError: _name is not defined]
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     stack: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:92:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       $v@timers.js:363:1
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ...
I/jxcore-log( 6676): 
I/jxcore-log( 6676): # setup
I/jxcore-log( 6676): 
I/jxcore-log( 6676): not ok 4 ReferenceError: _name is not defined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ---
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     operator: error
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     expected: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       undefined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     actual: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       [ReferenceError: _name is not defined]
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     stack: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:61:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       $v@timers.js:363:1
I/jxcore-log( 6676): 
,I/jxcore-log( 6676):       
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ...
I/jxcore-log( 6676): 
I/jxcore-log( 6676): # enqueue and run in order
I/jxcore-log( 6676): 
I/jxcore-log( 6676): not ok 5 ReferenceError: _name is not defined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ---
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     operator: error
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     expected: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       undefined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     actual: |-
I/jxcore-log( 6676): 
,I/jxcore-log( 6676):       [ReferenceError: _name is not defined]
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     stack: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:84:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6676): 
,I/jxcore-log( 6676):       $v@timers.js:363:1
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ...
I/jxcore-log( 6676): 
I/jxcore-log( 6676): # teardown
I/jxcore-log( 6676): 
,I/jxcore-log( 6676): not ok 6 ReferenceError: _name is not defined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ---
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     operator: error
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     expected: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       undefined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     actual: |-
I/jxcore-log( 6676): ,
I/jxcore-log( 6676):       [ReferenceError: _name is not defined]
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     stack: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:92:5
I/jxcore-log( 6676): 
,I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       $v@timers.js:363:1
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ...
I/jxcore-log( 6676): 
I/jxcore-log( 6676): # setup
I/jxcore-log( 6676): 
I/jxcore-log( 6676): not ok 7 ReferenceError: _name is not defined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ---
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     operator: error
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     expected: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       undefined
,I/jxcore-log( 6676): 
I/jxcore-log( 6676):     actual: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       [ReferenceError: _name is not defined]
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     stack: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:61:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       $v@timers.js:363:1
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ...
I/jxcore-log( 6676): 
I/jxcore-log( 6676): # basic
I/jxcore-log( 6676): 
I/jxcore-log( 6676): not ok 8 ReferenceError: _name is not defined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ---
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     operator: error
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     expected: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       undefined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     actual: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       [ReferenceError: _name is not defined]
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     stack: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:84:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       $v@timers.js:363:1
I/jxcore-log( 6676): 
,I/jxcore-log( 6676):       
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ...
I/jxcore-log( 6676): 
I/jxcore-log( 6676): # teardown
I/jxcore-log( 6676): 
I/jxcore-log( 6676): not ok 9 ReferenceError: _name is not defined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ---
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     operator: error
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     expected: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       undefined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     actual: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       [ReferenceError: _name is not defined]
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     stack: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:92:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       $v@timers.js:363:1
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ...
I/jxcore-log( 6676): 
,I/jxcore-log( 6676): # setup
I/jxcore-log( 6676): 
I/jxcore-log( 6676): not ok 10 ReferenceError: _name is not defined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ---
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     operator: error
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     expected: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       undefined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     actual: |-
I/jxcore-log( 6676): ,
I/jxcore-log( 6676):       [ReferenceError: _name is not defined]
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     stack: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:61:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       $v@timers.js:363:1
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ...
I/jxcore-log( 6676): 
I/jxcore-log( 6676): # another
I/jxcore-log( 6676): 
I/jxcore-log( 6676): not ok 11 ReferenceError: _name is not defined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ---
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     operator: error
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     expected: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       undefined
I/jxcore-log( 6676): 
,I/jxcore-log( 6676):     actual: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       [ReferenceError: _name is not defined]
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     stack: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:84:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
,I/jxcore-log( 6676):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       $v@timers.js:363:1
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ...
I/jxcore-log( 6676): 
I/jxcore-log( 6676): # teardown
I/jxcore-log( 6676): 
I/jxcore-log( 6676): not ok 12 ReferenceError: _name is not defined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ---
I/jxcore-log( 6676): 
,I/jxcore-log( 6676):     operator: error
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     expected: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       undefined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     actual: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       [ReferenceError: _name is not defined]
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     stack: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:92:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6676): 
,I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       $v@timers.js:363:1
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ...
I/jxcore-log( 6676): 
I/jxcore-log( 6676): # setup
I/jxcore-log( 6676): 
I/jxcore-log( 6676): not ok 13 ReferenceError: _name is not defined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ---
I/jxcore-log( 6676): 
,I/jxcore-log( 6676):     operator: error
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     expected: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       undefined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     actual: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       [ReferenceError: _name is not defined]
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     stack: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:61:5
I/jxcore-log( 6676): 
,I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       $v@timers.js:363:1
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ...
I/jxcore-log( 6676): 
,I/jxcore-log( 6676): # successfully create a new pkcs12 file and return hash value
I/jxcore-log( 6676): 
I/jxcore-log( 6676): not ok 14 ReferenceError: _name is not defined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ---
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     operator: error
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     expected: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       undefined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     actual: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       [ReferenceError: _name is not defined]
,I/jxcore-log( 6676): 
I/jxcore-log( 6676):     stack: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:84:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       $v@timers.js:363:1
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ...
I/jxcore-log( 6676): 
,I/jxcore-log( 6676): # teardown
I/jxcore-log( 6676): 
I/jxcore-log( 6676): not ok 15 ReferenceError: _name is not defined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ---
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     operator: error
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     expected: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       undefined
I/jxcore-log( 6676): 
,I/jxcore-log( 6676):     actual: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       [ReferenceError: _name is not defined]
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     stack: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:92:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       $v@timers.js:363:1
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ...
I/jxcore-log( 6676): 
I/jxcore-log( 6676): # setup
I/jxcore-log( 6676): 
I/jxcore-log( 6676): not ok 16 ReferenceError: _name is not defined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ---
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     operator: error
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     expected: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       undefined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     actual: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       [ReferenceError: _name is not defined]
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     stack: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:61:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       $v@timers.js:363:1
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ...
I/jxcore-log( 6676): 
I/jxcore-log( 6676): # successfully read a previous pkcs12 file and return hash value
I/jxcore-log( 6676): 
I/jxcore-log( 6676): not ok 17 ReferenceError: _name is not defined
I/jxcore-log( 6676): 
,I/jxcore-log( 6676):   ---
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     operator: error
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     expected: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       undefined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     actual: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       [ReferenceError: _name is not defined]
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     stack: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:84:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       $v@timers.js:363:1
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ...
I/jxcore-log( 6676): 
I/jxcore-log( 6676): # teardown
I/jxcore-log( 6676): 
I/jxcore-log( 6676): not ok 18 ReferenceError: _name is not defined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ---
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     operator: error
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     expected: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       undefined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     actual: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       [ReferenceError: _name is not defined]
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     stack: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:92:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       $v@timers.js:363:1
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ...
I/jxcore-log( 6676): 
,I/jxcore-log( 6676): # setup
I/jxcore-log( 6676): 
I/jxcore-log( 6676): not ok 19 ReferenceError: _name is not defined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ---
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     operator: error
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     expected: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       undefined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     actual: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       [ReferenceError: _name is not defined]
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     stack: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:61:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       $v@timers.js:363:1
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ...
I/jxcore-log( 6676): 
I/jxcore-log( 6676): # failed to extract public key because of corrupt pkcs12 file
I/jxcore-log( 6676): 
I/jxcore-log( 6676): not ok 20 ReferenceError: _name is not defined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ---
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     operator: error
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     expected: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       undefined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     actual: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       [ReferenceError: _name is not defined]
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     stack: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:84:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       $v@timers.js:363:1
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ...
I/jxcore-log( 6676): 
I/jxcore-log( 6676): # teardown
I/jxcore-log( 6676): 
I/jxcore-log( 6676): not ok 21 ReferenceError: _name is not defined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ---
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     operator: error
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     expected: |-
,I/jxcore-log( 6676): 
I/jxcore-log( 6676):       undefined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     actual: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       [ReferenceError: _name is not defined]
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     stack: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:92:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       $v@timers.js:363:1
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       ,
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ...
I/jxcore-log( 6676): 
I/jxcore-log( 6676): # setup
I/jxcore-log( 6676): 
I/jxcore-log( 6676): not ok 22 ReferenceError: _name is not defined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ---
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     operator: error
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     expected: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       undefined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     actual: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       [ReferenceError: _name is not defined]
I/jxcore-log( 6676): 
,I/jxcore-log( 6676):     stack: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:61:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       $v@timers.js:363:1
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       
I/jxcore-log( 6676): ,
I/jxcore-log( 6676):   ...
I/jxcore-log( 6676): 
I/jxcore-log( 6676): # failed to get mobile documents path
I/jxcore-log( 6676): 
,I/jxcore-log( 6676): not ok 23 ReferenceError: _name is not defined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ---
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     operator: error
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     expected: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       undefined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     actual: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       [ReferenceError: _name is not defined]
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     stack: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:84:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
,I/jxcore-log( 6676): 
I/jxcore-log( 6676):       $v@timers.js:363:1
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ...
I/jxcore-log( 6676): 
I/jxcore-log( 6676): # teardown
I/jxcore-log( 6676): 
,I/jxcore-log( 6676): not ok 24 ReferenceError: _name is not defined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ---
I/jxcore-log( 6676): ,
I/jxcore-log( 6676):     operator: error
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     expected: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       undefined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     actual: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       [ReferenceError: _name is not defined]
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     stack: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:92:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       $v@timers.js:363:1
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ...
I/jxcore-log( 6676): 
I/jxcore-log( 6676): # setup
I/jxcore-log( 6676): 
,I/jxcore-log( 6676): not ok 25 ReferenceError: _name is not defined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ---
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     operator: error
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     expected: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       undefined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     actual: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       [ReferenceError: _name is not defined]
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     stack: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:61:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       $v@timers.js:363:1
I/jxcore-log( 6676): 
,I/jxcore-log( 6676):       
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ...
I/jxcore-log( 6676): 
I/jxcore-log( 6676): # #init should register the peerAvailabilityChanged event
I/jxcore-log( 6676): 
,I/jxcore-log( 6676): not ok 26 ReferenceError: _name is not defined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ---
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     operator: error
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     expected: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       undefined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     actual: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       [ReferenceError: _name is not defined]
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     stack: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:84:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6676): 
,I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       $v@timers.js:363:1
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ...
I/jxcore-log( 6676): 
,I/jxcore-log( 6676): # teardown
I/jxcore-log( 6676): 
,I/jxcore-log( 6676): not ok 27 ReferenceError: _name is not defined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ---
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     operator: error
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     expected: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       undefined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     actual: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       [ReferenceError: _name is not defined]
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     stack: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:92:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       $v@timers.js:363:1
I/jxcore-log( 6676): 
,I/jxcore-log( 6676):       
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ...
I/jxcore-log( 6676): 
I/jxcore-log( 6676): # setup
I/jxcore-log( 6676): 
,I/jxcore-log( 6676): not ok 28 ReferenceError: _name is not defined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ---
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     operator: error
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     expected: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       undefined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     actual: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       [ReferenceError: _name is not defined]
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     stack: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:61:5
I/jxcore-log( 6676): 
,I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       $v@timers.js:363:1
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ...
I/jxcore-log( 6676): 
I/jxcore-log( 6676): # #init should register the networkChanged event
I/jxcore-log( 6676): 
,I/jxcore-log( 6676): not ok 29 ReferenceError: _name is not defined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ---
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     operator: error
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     expected: |-
I/jxcore-log( 6676): 
,I/jxcore-log( 6676):       undefined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     actual: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       [ReferenceError: _name is not defined]
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     stack: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:84:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       $v@timers.js:363:1
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ...
I/jxcore-log( 6676): 
I/jxcore-log( 6676): # teardown
I/jxcore-log( 6676): 
,I/jxcore-log( 6676): not ok 30 ReferenceError: _name is not defined
I/jxcore-log( 6676): 
,I/jxcore-log( 6676):   ---
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     operator: error
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     expected: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       undefined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     actual: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       [ReferenceError: _name is not defined]
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     stack: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:92:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       $v@timers.js:363:1
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ...
I/jxcore-log( 6676): 
I/jxcore-log( 6676): # setup
I/jxcore-log( 6676): 
,I/jxcore-log( 6676): not ok 31 ReferenceError: _name is not defined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ---
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     operator: error
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     expected: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       undefined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     actual: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       [ReferenceError: _name is not defined]
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     stack: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:61:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       $v@timers.js:363:1
I/jxcore-log( 6676): 
,I/jxcore-log( 6676):       
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ...
I/jxcore-log( 6676): 
I/jxcore-log( 6676): # #startBroadcasting should throw on null device name
I/jxcore-log( 6676): 
,I/jxcore-log( 6676): not ok 32 ReferenceError: _name is not defined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ---
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     operator: error
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     expected: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       undefined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     actual: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       [ReferenceError: _name is not defined]
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     stack: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:84:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       $v@timers.js:363:1
I/jxcore-log( 6676): 
,I/jxcore-log( 6676):       
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ...
I/jxcore-log( 6676): 
I/jxcore-log( 6676): # teardown
I/jxcore-log( 6676): 
,I/jxcore-log( 6676): not ok 33 ReferenceError: _name is not defined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ---
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     operator: error
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     expected: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       undefined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     actual: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       [ReferenceError: _name is not defined]
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     stack: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:92:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       $v@timers.js:363:1
I/jxcore-log( 6676): 
,I/jxcore-log( 6676):       
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ...
I/jxcore-log( 6676): 
I/jxcore-log( 6676): # setup
I/jxcore-log( 6676): 
,I/jxcore-log( 6676): not ok 34 ReferenceError: _name is not defined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ---
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     operator: error
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     expected: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       undefined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     actual: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       [ReferenceError: _name is not defined]
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     stack: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:61:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       $v@timers.js:363:1
I/jxcore-log( 6676): 
,I/jxcore-log( 6676):       
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ...
I/jxcore-log( 6676): 
I/jxcore-log( 6676): # #startBroadcasting should throw on empty string device name
I/jxcore-log( 6676): 
,I/jxcore-log( 6676): not ok 35 ReferenceError: _name is not defined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ---
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     operator: error
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     expected: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       undefined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     actual: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       [ReferenceError: _name is not defined]
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     stack: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:84:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6676): 
,I/jxcore-log( 6676):       $v@timers.js:363:1
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ...
I/jxcore-log( 6676): 
I/jxcore-log( 6676): # teardown
I/jxcore-log( 6676): 
,I/jxcore-log( 6676): not ok 36 ReferenceError: _name is not defined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ---
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     operator: error
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     expected: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       undefined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     actual: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       [ReferenceError: _name is not defined]
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     stack: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:92:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       $v@timers.js:363:1
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ...
I/jxcore-log( 6676): 
I/jxcore-log( 6676): # setup
I/jxcore-log( 6676): 
I/jxcore-log( 6676): not ok 37 ReferenceError: _name is not defined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ---
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     operator: error
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     expected: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       undefined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     actual: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       [ReferenceError: _name is not defined]
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     stack: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:61:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       $v@timers.js:363:1
I/jxcore-log( 6676): 
,I/jxcore-log( 6676):       
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ...
I/jxcore-log( 6676): 
I/jxcore-log( 6676): # #startBroadcasting should throw on non-number port
I/jxcore-log( 6676): 
,I/jxcore-log( 6676): not ok 38 ReferenceError: _name is not defined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ---
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     operator: error
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     expected: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       undefined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     actual: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       [ReferenceError: _name is not defined]
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     stack: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:84:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       $v@timers.js:363:1
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       
I/jxcore-log( 6676): 
,I/jxcore-log( 6676):   ...
I/jxcore-log( 6676): 
,I/jxcore-log( 6676): # teardown
I/jxcore-log( 6676): 
,I/jxcore-log( 6676): not ok 39 ReferenceError: _name is not defined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ---
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     operator: error
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     expected: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       undefined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     actual: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       [ReferenceError: _name is not defined]
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     stack: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:92:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6676): 
,I/jxcore-log( 6676):       $v@timers.js:363:1
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ...
I/jxcore-log( 6676): 
I/jxcore-log( 6676): # setup
I/jxcore-log( 6676): 
,I/jxcore-log( 6676): not ok 40 ReferenceError: _name is not defined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ---
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     operator: error
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     expected: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       undefined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     actual: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       [ReferenceError: _name is not defined]
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     stack: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:61:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6676): 
,I/jxcore-log( 6676):       $v@timers.js:363:1
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ...
I/jxcore-log( 6676): 
I/jxcore-log( 6676): # #startBroadcasting should throw on NaN port
I/jxcore-log( 6676): 
,I/jxcore-log( 6676): not ok 41 ReferenceError: _name is not defined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ---
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     operator: error
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     expected: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       undefined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     actual: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       [ReferenceError: _name is not defined]
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     stack: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:84:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6676): 
,I/jxcore-log( 6676):       $v@timers.js:363:1
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ...
I/jxcore-log( 6676): 
I/jxcore-log( 6676): # teardown
I/jxcore-log( 6676): 
,I/jxcore-log( 6676): not ok 42 ReferenceError: _name is not defined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ---
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     operator: error
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     expected: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       undefined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     actual: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       [ReferenceError: _name is not defined]
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     stack: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:92:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
,I/jxcore-log( 6676):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       $v@timers.js:363:1
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ...
I/jxcore-log( 6676): 
I/jxcore-log( 6676): # setup
I/jxcore-log( 6676): 
,I/jxcore-log( 6676): not ok 43 ReferenceError: _name is not defined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ---
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     operator: error
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     expected: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       undefined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     actual: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       [ReferenceError: _name is not defined]
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     stack: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:61:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       $v@timers.js:363:1
I/jxcore-log( 6676): 
,I/jxcore-log( 6676):       
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ...
I/jxcore-log( 6676): 
I/jxcore-log( 6676): # #startBroadcasting should throw on negative port
I/jxcore-log( 6676): 
,I/jxcore-log( 6676): not ok 44 ReferenceError: _name is not defined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ---
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     operator: error
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     expected: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       undefined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     actual: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       [ReferenceError: _name is not defined]
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     stack: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:84:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       $v@timers.js:363:1
I/jxcore-log( 6676): 
,I/jxcore-log( 6676):       
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ...
I/jxcore-log( 6676): 
I/jxcore-log( 6676): # teardown
I/jxcore-log( 6676): 
,I/jxcore-log( 6676): not ok 45 ReferenceError: _name is not defined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ---
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     operator: error
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     expected: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       undefined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     actual: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       [ReferenceError: _name is not defined]
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     stack: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:92:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       $v@timers.js:363:1
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       
I/jxcore-log( 6676): 
,I/jxcore-log( 6676):   ...
I/jxcore-log( 6676): 
I/jxcore-log( 6676): # setup
I/jxcore-log( 6676): 
I/jxcore-log( 6676): not ok 46 ReferenceError: _name is not defined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ---
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     operator: error
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     expected: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       undefined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     actual: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       [ReferenceError: _name is not defined]
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     stack: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:61:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       $v@timers.js:363:1
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       
I/jxcore-log( 6676): 
,I/jxcore-log( 6676):   ...
I/jxcore-log( 6676): 
I/jxcore-log( 6676): # #startBroadcasting should throw on too large port
I/jxcore-log( 6676): 
,I/jxcore-log( 6676): not ok 47 ReferenceError: _name is not defined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ---
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     operator: error
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     expected: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       undefined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     actual: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       [ReferenceError: _name is not defined]
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     stack: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:84:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
,I/jxcore-log( 6676):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       $v@timers.js:363:1
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ...
I/jxcore-log( 6676): 
I/jxcore-log( 6676): # teardown
I/jxcore-log( 6676): 
,I/jxcore-log( 6676): not ok 48 ReferenceError: _name is not defined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ---
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     operator: error
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     expected: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       undefined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     actual: |-
I/jxcore-log( 6676): 
,I/jxcore-log( 6676):       [ReferenceError: _name is not defined]
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     stack: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:92:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       $v@timers.js:363:1
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ...
I/jxcore-log( 6676): 
I/jxcore-log( 6676): # setup
I/jxcore-log( 6676): 
,I/jxcore-log( 6676): not ok 49 ReferenceError: _name is not defined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ---
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     operator: error
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     expected: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       undefined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     actual: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       [ReferenceError: _name is not defined]
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     stack: |-
I/jxcore-log( 6676): 
,I/jxcore-log( 6676):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:61:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       $v@timers.js:363:1
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ...
I/jxcore-log( 6676): 
I/jxcore-log( 6676): # #startBroadcasting should call Mobile("StartBroadcasting") without an error
I/jxcore-log( 6676): 
,I/jxcore-log( 6676): not ok 50 ReferenceError: _name is not defined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ---
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     operator: error
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     expected: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       undefined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     actual: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       [ReferenceError: _name is not defined]
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     stack: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:84:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
,I/jxcore-log( 6676): 
I/jxcore-log( 6676):       $v@timers.js:363:1
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ...
I/jxcore-log( 6676): 
,I/jxcore-log( 6676): # teardown
I/jxcore-log( 6676): 
,I/jxcore-log( 6676): not ok 51 ReferenceError: _name is not defined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ---
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     operator: error
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     expected: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       undefined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     actual: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       [ReferenceError: _name is not defined]
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     stack: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:92:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6676): 
,I/jxcore-log( 6676):       $v@timers.js:363:1
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ...
I/jxcore-log( 6676): 
I/jxcore-log( 6676): # setup
I/jxcore-log( 6676): 
I/jxcore-log( 6676): not ok 52 ReferenceError: _name is not defined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ---
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     operator: error
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     expected: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       undefined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     actual: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       [ReferenceError: _name is not defined]
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     stack: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:61:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       $v@timers.js:363:1
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       
I/jxcore-log( 6676): 
,I/jxcore-log( 6676):   ...
I/jxcore-log( 6676): 
I/jxcore-log( 6676): # #startBroadcasting should call Mobile("StartBroadcasting") and handle an error
I/jxcore-log( 6676): 
I/jxcore-log( 6676): not ok 53 ReferenceError: _name is not defined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ---
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     operator: error
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     expected: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       undefined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     actual: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       [ReferenceError: _name is not defined]
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     stack: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:84:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       $v@timers.js:363:1
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       
I/jxcore-log( 6676): 
,I/jxcore-log( 6676):   ...
I/jxcore-log( 6676): 
I/jxcore-log( 6676): # teardown
I/jxcore-log( 6676): 
I/jxcore-log( 6676): not ok 54 ReferenceError: _name is not defined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ---
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     operator: error
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     expected: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       undefined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     actual: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       [ReferenceError: _name is not defined]
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     stack: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:92:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6676): 
,I/jxcore-log( 6676):       $v@timers.js:363:1
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ...
I/jxcore-log( 6676): 
I/jxcore-log( 6676): # setup
I/jxcore-log( 6676): 
I/jxcore-log( 6676): not ok 55 ReferenceError: _name is not defined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ---
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     operator: error
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     expected: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       undefined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     actual: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       [ReferenceError: _name is not defined]
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     stack: |-
I/jxcore-log( 6676): 
,I/jxcore-log( 6676):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:61:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       $v@timers.js:363:1
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ...
I/jxcore-log( 6676): 
I/jxcore-log( 6676): # #stopBroadcasting should call Mobile("StopBroadcasting") without an error
I/jxcore-log( 6676): 
,I/jxcore-log( 6676): not ok 56 ReferenceError: _name is not defined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ---
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     operator: error
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     expected: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       undefined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     actual: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       [ReferenceError: _name is not defined]
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     stack: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:84:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       $v@timers.js:363:1
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       
I/jxcore-log( 6676): 
,I/jxcore-log( 6676):   ...
I/jxcore-log( 6676): 
I/jxcore-log( 6676): # teardown
I/jxcore-log( 6676): 
,I/jxcore-log( 6676): not ok 57 ReferenceError: _name is not defined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ---
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     operator: error
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     expected: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       undefined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     actual: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       [ReferenceError: _name is not defined]
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     stack: |-
I/jxcore-log( 6676): 
,I/jxcore-log( 6676):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:92:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       $v@timers.js:363:1
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ...
I/jxcore-log( 6676): 
I/jxcore-log( 6676): # setup
I/jxcore-log( 6676): 
,I/jxcore-log( 6676): not ok 58 ReferenceError: _name is not defined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ---
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     operator: error
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     expected: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       undefined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     actual: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       [ReferenceError: _name is not defined]
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     stack: |-
I/jxcore-log( 6676): 
,I/jxcore-log( 6676):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:61:5
I/jxcore-log( 6676): 
,I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
,I/jxcore-log( 6676):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6676): 
,I/jxcore-log( 6676):       $v@timers.js:363:1
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ...
I/jxcore-log( 6676): 
,I/jxcore-log( 6676): # #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error
I/jxcore-log( 6676): 
,I/jxcore-log( 6676): not ok 59 ReferenceError: _name is not defined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ---
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     operator: error
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     expected: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       undefined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     actual: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       [ReferenceError: _name is not defined]
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     stack: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:84:5
I/jxcore-log( 6676): 
,I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       $v@timers.js:363:1
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ...
I/jxcore-log( 6676): 
,I/jxcore-log( 6676): # teardown
I/jxcore-log( 6676): 
,I/jxcore-log( 6676): not ok 60 ReferenceError: _name is not defined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ---
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     operator: error
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     expected: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       undefined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     actual: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       [ReferenceError: _name is not defined]
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     stack: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:92:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       $v@timers.js:363:1
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       
I/jxcore-log( 6676): 
,I/jxcore-log( 6676):   ...
I/jxcore-log( 6676): 
I/jxcore-log( 6676): # setup
I/jxcore-log( 6676): 
I/jxcore-log( 6676): not ok 61 ReferenceError: _name is not defined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ---
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     operator: error
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     expected: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       undefined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     actual: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       [ReferenceError: _name is not defined]
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     stack: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:61:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6676): 
,I/jxcore-log( 6676):       $v@timers.js:363:1
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ...
I/jxcore-log( 6676): 
I/jxcore-log( 6676): # #connect should call Mobile("Connect") with a port and without an error
I/jxcore-log( 6676): 
I/jxcore-log( 6676): not ok 62 ReferenceError: _name is not defined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ---
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     operator: error
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     expected: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       undefined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     actual: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       [ReferenceError: _name is not defined]
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     stack: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:84:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       $v@timers.js:363:1
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       
I/jxcore-log( 6676): 
,I/jxcore-log( 6676):   ...
I/jxcore-log( 6676): 
I/jxcore-log( 6676): # teardown
I/jxcore-log( 6676): 
I/jxcore-log( 6676): not ok 63 ReferenceError: _name is not defined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ---
I/jxcore-log( 6676): 
,I/jxcore-log( 6676):     operator: error
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     expected: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       undefined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     actual: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       [ReferenceError: _name is not defined]
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     stack: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:92:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6676): 
,I/jxcore-log( 6676):       $v@timers.js:363:1
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ...
I/jxcore-log( 6676): 
I/jxcore-log( 6676): # setup
I/jxcore-log( 6676): 
I/jxcore-log( 6676): not ok 64 ReferenceError: _name is not defined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ---
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     operator: error
I/jxcore-log( 6676): 
,I/jxcore-log( 6676):     expected: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       undefined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     actual: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       [ReferenceError: _name is not defined]
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     stack: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:61:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6676): 
,I/jxcore-log( 6676):       $v@timers.js:363:1
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ...
I/jxcore-log( 6676): 
I/jxcore-log( 6676): # #connect should call Mobile("Connect") and handle an error
I/jxcore-log( 6676): 
I/jxcore-log( 6676): not ok 65 ReferenceError: _name is not defined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ---
I/jxcore-log( 6676): 
,I/jxcore-log( 6676):     operator: error
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     expected: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       undefined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     actual: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       [ReferenceError: _name is not defined]
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     stack: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:84:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6676): 
,I/jxcore-log( 6676):       $v@timers.js:363:1
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ...
I/jxcore-log( 6676): 
I/jxcore-log( 6676): # teardown
I/jxcore-log( 6676): 
,I/jxcore-log( 6676): not ok 66 ReferenceError: _name is not defined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ---
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     operator: error
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     expected: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       undefined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     actual: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       [ReferenceError: _name is not defined]
I/jxcore-log( 6676): 
,I/jxcore-log( 6676):     stack: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:92:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       $v@timers.js:363:1
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ...
I/jxcore-log( 6676): 
I/jxcore-log( 6676): # setup
I/jxcore-log( 6676): 
I/jxcore-log( 6676): not ok 67 ReferenceError: _name is not defined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ---
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     operator: error
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     expected: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       undefined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     actual: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       [ReferenceError: _name is not defined]
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     stack: |-
I/jxcore-log( 6676): 
,I/jxcore-log( 6676):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:61:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       $v@timers.js:363:1
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ...
I/jxcore-log( 6676): 
I/jxcore-log( 6676): # should call Mobile("Disconnect") without an error
I/jxcore-log( 6676): 
,I/jxcore-log( 6676): not ok 68 ReferenceError: _name is not defined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ---
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     operator: error
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     expected: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       undefined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     actual: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       [ReferenceError: _name is not defined]
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     stack: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:84:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       $v@timers.js:363:1
I/jxcore-log( 6676): 
,I/jxcore-log( 6676):       
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ...
I/jxcore-log( 6676): 
I/jxcore-log( 6676): # teardown
I/jxcore-log( 6676): 
,I/jxcore-log( 6676): not ok 69 ReferenceError: _name is not defined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ---
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     operator: error
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     expected: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       undefined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     actual: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       [ReferenceError: _name is not defined]
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     stack: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:92:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       $v@timers.js:363:1
I/jxcore-log( 6676): 
,I/jxcore-log( 6676):       
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ...
I/jxcore-log( 6676): 
I/jxcore-log( 6676): # setup
I/jxcore-log( 6676): 
I/jxcore-log( 6676): not ok 70 ReferenceError: _name is not defined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ---
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     operator: error
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     expected: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       undefined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     actual: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       [ReferenceError: _name is not defined]
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     stack: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:61:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       $v@timers.js:363:1
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       
I/jxcore-log( 6676): 
,I/jxcore-log( 6676):   ...
I/jxcore-log( 6676): 
I/jxcore-log( 6676): # should call Mobile("Disconnect") and handle an error
I/jxcore-log( 6676): 
I/jxcore-log( 6676): not ok 71 ReferenceError: _name is not defined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ---
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     operator: error
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     expected: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       undefined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     actual: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       [ReferenceError: _name is not defined]
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     stack: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:84:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6676): 
,I/jxcore-log( 6676):       $v@timers.js:363:1
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ...
I/jxcore-log( 6676): 
I/jxcore-log( 6676): # teardown
I/jxcore-log( 6676): 
I/jxcore-log( 6676): not ok 72 ReferenceError: _name is not defined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ---
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     operator: error
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     expected: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       undefined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     actual: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       [ReferenceError: _name is not defined]
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     stack: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:92:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6676): 
,I/jxcore-log( 6676):       $v@timers.js:363:1
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ...
I/jxcore-log( 6676): 
I/jxcore-log( 6676): # setup
I/jxcore-log( 6676): 
I/jxcore-log( 6676): not ok 73 ReferenceError: _name is not defined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ---
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     operator: error
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     expected: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       undefined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     actual: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       [ReferenceError: _name is not defined]
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     stack: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:61:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6676): 
,I/jxcore-log( 6676):       $v@timers.js:363:1
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ...
I/jxcore-log( 6676): 
I/jxcore-log( 6676): # ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error
I/jxcore-log( 6676): 
I/jxcore-log( 6676): not ok 74 ReferenceError: _name is not defined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ---
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     operator: error
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     expected: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       undefined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     actual: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       [ReferenceError: _name is not defined]
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     stack: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:84:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       $v@timers.js:363:1
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       
I/jxcore-log( 6676): 
,I/jxcore-log( 6676):   ...
I/jxcore-log( 6676): 
I/jxcore-log( 6676): # teardown
I/jxcore-log( 6676): 
,I/jxcore-log( 6676): not ok 75 ReferenceError: _name is not defined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ---
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     operator: error
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     expected: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       undefined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     actual: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       [ReferenceError: _name is not defined]
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     stack: |-
I/jxcore-log( 6676): 
,I/jxcore-log( 6676):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:92:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       $v@timers.js:363:1
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ...
I/jxcore-log( 6676): 
I/jxcore-log( 6676): # setup
I/jxcore-log( 6676): 
,I/jxcore-log( 6676): not ok 76 ReferenceError: _name is not defined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ---
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     operator: error
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     expected: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       undefined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     actual: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       [ReferenceError: _name is not defined]
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     stack: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:61:5
I/jxcore-log( 6676): 
,I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       $v@timers.js:363:1
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ...
I/jxcore-log( 6676): 
I/jxcore-log( 6676): # ThaliEmitter calls startBroadcasting twice with error
I/jxcore-log( 6676): 
,I/jxcore-log( 6676): not ok 77 ReferenceError: _name is not defined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ---
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     operator: error
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     expected: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       undefined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     actual: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       [ReferenceError: _name is not defined]
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     stack: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:84:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       $v@timers.js:363:1
I/jxcore-log( 6676): 
,I/jxcore-log( 6676):       
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ...
I/jxcore-log( 6676): 
I/jxcore-log( 6676): # teardown
I/jxcore-log( 6676): 
,I/jxcore-log( 6676): not ok 78 ReferenceError: _name is not defined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ---
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     operator: error
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     expected: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       undefined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     actual: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       [ReferenceError: _name is not defined]
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     stack: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:92:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
,I/jxcore-log( 6676):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       $v@timers.js:363:1
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ...
I/jxcore-log( 6676): 
I/jxcore-log( 6676): # setup
I/jxcore-log( 6676): 
,I/jxcore-log( 6676): not ok 79 ReferenceError: _name is not defined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ---
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     operator: error
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     expected: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       undefined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     actual: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       [ReferenceError: _name is not defined]
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     stack: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:61:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
,I/jxcore-log( 6676): 
I/jxcore-log( 6676):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       $v@timers.js:363:1
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ...
I/jxcore-log( 6676): 
I/jxcore-log( 6676): # ThaliEmitter throws on connection to bad peer
I/jxcore-log( 6676): 
,I/jxcore-log( 6676): not ok 80 ReferenceError: _name is not defined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ---
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     operator: error
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     expected: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       undefined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     actual: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       [ReferenceError: _name is not defined]
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     stack: |-
I/jxcore-log( 6676): 
,I/jxcore-log( 6676):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:84:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       $v@timers.js:363:1
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ...
I/jxcore-log( 6676): 
I/jxcore-log( 6676): # teardown
I/jxcore-log( 6676): 
,I/jxcore-log( 6676): not ok 81 ReferenceError: _name is not defined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ---
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     operator: error
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     expected: |-
I/jxcore-log( 6676): 
,I/jxcore-log( 6676):       undefined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     actual: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       [ReferenceError: _name is not defined]
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     stack: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:92:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       $v@timers.js:363:1
I/jxcore-log( 6676): 
,I/jxcore-log( 6676):       
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ...
I/jxcore-log( 6676): 
I/jxcore-log( 6676): # setup
I/jxcore-log( 6676): 
I/jxcore-log( 6676): not ok 82 ReferenceError: _name is not defined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ---
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     operator: error
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     expected: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       undefined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     actual: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       [ReferenceError: _name is not defined]
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     stack: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:61:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
,I/jxcore-log( 6676):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       $v@timers.js:363:1
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ...
I/jxcore-log( 6676): 
I/jxcore-log( 6676): # ThaliEmitter throws on disconnect to bad peer
I/jxcore-log( 6676): 
,I/jxcore-log( 6676): not ok 83 ReferenceError: _name is not defined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ---
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     operator: error
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     expected: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       undefined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     actual: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       [ReferenceError: _name is not defined]
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     stack: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:84:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       $v@timers.js:363:1,
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ...
I/jxcore-log( 6676): 
I/jxcore-log( 6676): # teardown
I/jxcore-log( 6676): 
,I/jxcore-log( 6676): not ok 84 ReferenceError: _name is not defined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ---
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     operator: error
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     expected: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       undefined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     actual: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       [ReferenceError: _name is not defined]
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     stack: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:92:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6676): 
,I/jxcore-log( 6676):       $v@timers.js:363:1
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ...
I/jxcore-log( 6676): 
I/jxcore-log( 6676): # setup
I/jxcore-log( 6676): 
I/jxcore-log( 6676): not ok 85 ReferenceError: _name is not defined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ---
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     operator: error
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     expected: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       undefined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     actual: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       [ReferenceError: _name is not defined]
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     stack: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:61:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       $v@timers.js:363:1
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       
I/jxcore-log( 6676): 
,I/jxcore-log( 6676):   ...
I/jxcore-log( 6676): 
I/jxcore-log( 6676): # After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted
I/jxcore-log( 6676): 
I/jxcore-log( 6676): not ok 86 ReferenceError: _name is not defined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ---
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     operator: error
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     expected: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       undefined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     actual: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       [ReferenceError: _name is not defined]
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     stack: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:84:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       $v@timers.js:363:1
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       
I/jxcore-log( 6676): 
,I/jxcore-log( 6676):   ...
I/jxcore-log( 6676): 
I/jxcore-log( 6676): # teardown
I/jxcore-log( 6676): 
I/jxcore-log( 6676): not ok 87 ReferenceError: _name is not defined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ---
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     operator: error
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     expected: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       undefined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     actual: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       [ReferenceError: _name is not defined]
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     stack: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:92:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       $v@timers.js:363:1
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       
I/jxcore-log( 6676): 
,I/jxcore-log( 6676):   ...
I/jxcore-log( 6676): 
I/jxcore-log( 6676): # setup
I/jxcore-log( 6676): 
I/jxcore-log( 6676): not ok 88 ReferenceError: _name is not defined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ---
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     operator: error
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     expected: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       undefined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     actual: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       [ReferenceError: _name is not defined]
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     stack: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:61:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       $v@timers.js:363:1
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       
I/jxcore-log( 6676): 
,I/jxcore-log( 6676):   ...
I/jxcore-log( 6676): 
I/jxcore-log( 6676): # #startUpdateAdvertisingAndListening should use different USN after every invocation
I/jxcore-log( 6676): 
I/jxcore-log( 6676): not ok 89 ReferenceError: _name is not defined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ---
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     operator: error
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     expected: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       undefined
I/jxcore-log( 6676): 
,I/jxcore-log( 6676):     actual: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       [ReferenceError: _name is not defined]
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     stack: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:84:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       $v@timers.js:363:1
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ...
I/jxcore-log( 6676): 
,I/jxcore-log( 6676): # teardown
I/jxcore-log( 6676): 
I/jxcore-log( 6676): not ok 90 ReferenceError: _name is not defined
I/jxcore-log( 6676): 
,I/jxcore-log( 6676):   ---
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     operator: error
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     expected: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       undefined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     actual: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       [ReferenceError: _name is not defined]
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     stack: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:92:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6676): 
,I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       $v@timers.js:363:1
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ...
I/jxcore-log( 6676): 
I/jxcore-log( 6676): # setup
I/jxcore-log( 6676): 
I/jxcore-log( 6676): not ok 91 ReferenceError: _name is not defined
I/jxcore-log( 6676): 
,I/jxcore-log( 6676):   ---
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     operator: error
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     expected: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       undefined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     actual: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       [ReferenceError: _name is not defined]
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     stack: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:61:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       $v@timers.js:363:1
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ...
I/jxcore-log( 6676): 
I/jxcore-log( 6676): # messages with invalid location or USN should be ignored
I/jxcore-log( 6676): 
I/jxcore-log( 6676): not ok 92 ReferenceError: _name is not defined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ---
,I/jxcore-log( 6676): 
I/jxcore-log( 6676):     operator: error
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     expected: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       undefined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     actual: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       [ReferenceError: _name is not defined]
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     stack: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:84:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       $v@timers.js:363:1
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ...
I/jxcore-log( 6676): 
I/jxcore-log( 6676): # teardown
I/jxcore-log( 6676): 
,I/jxcore-log( 6676): not ok 93 ReferenceError: _name is not defined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ---
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     operator: error
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     expected: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       undefined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     actual: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       [ReferenceError: _name is not defined]
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     stack: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:92:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
,I/jxcore-log( 6676):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       $v@timers.js:363:1
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ...
I/jxcore-log( 6676): 
I/jxcore-log( 6676): # setup
I/jxcore-log( 6676): 
I/jxcore-log( 6676): not ok 94 ReferenceError: _name is not defined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ---
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     operator: error
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     expected: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       undefined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     actual: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       [ReferenceError: _name is not defined]
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     stack: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:61:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6676): 
,I/jxcore-log( 6676):       $v@timers.js:363:1
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ...
I/jxcore-log( 6676): 
I/jxcore-log( 6676): # verify that Thali-specific messages are filtered correctly
I/jxcore-log( 6676): 
I/jxcore-log( 6676): not ok 95 ReferenceError: _name is not defined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ---
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     operator: error
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     expected: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       undefined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     actual: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       [ReferenceError: _name is not defined]
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     stack: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:84:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6676): 
,I/jxcore-log( 6676):       $v@timers.js:363:1
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ...
I/jxcore-log( 6676): 
I/jxcore-log( 6676): # teardown
I/jxcore-log( 6676): 
,I/jxcore-log( 6676): not ok 96 ReferenceError: _name is not defined
I/jxcore-log( 6676): 
,I/jxcore-log( 6676):   ---
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     operator: error
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     expected: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       undefined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     actual: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       [ReferenceError: _name is not defined]
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     stack: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:92:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       $v@timers.js:363:1
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ...
I/jxcore-log( 6676): 
I/jxcore-log( 6676): # setup
I/jxcore-log( 6676): 
,I/jxcore-log( 6676): not ok 97 ReferenceError: _name is not defined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ---
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     operator: error
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     expected: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       undefined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     actual: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       [ReferenceError: _name is not defined]
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     stack: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:61:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       $v@timers.js:363:1
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       
I/jxcore-log( 6676): 
,I/jxcore-log( 6676):   ...
I/jxcore-log( 6676): 
I/jxcore-log( 6676): # #start should fail if called twice in a row
I/jxcore-log( 6676): 
I/jxcore-log( 6676): not ok 98 ReferenceError: _name is not defined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ---
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     operator: error
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     expected: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       undefined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     actual: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       [ReferenceError: _name is not defined]
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     stack: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:84:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       $v@timers.js:363:1
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       
I/jxcore-log( 6676): 
,I/jxcore-log( 6676):   ...
I/jxcore-log( 6676): 
I/jxcore-log( 6676): # teardown
I/jxcore-log( 6676): 
I/jxcore-log( 6676): not ok 99 ReferenceError: _name is not defined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ---
I/jxcore-log( 6676): 
,I/jxcore-log( 6676):     operator: error
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     expected: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       undefined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     actual: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       [ReferenceError: _name is not defined]
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     stack: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:92:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       $v@timers.js:363:1
I/jxcore-log( 6676): 
,I/jxcore-log( 6676):       
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ...
I/jxcore-log( 6676): 
I/jxcore-log( 6676): # setup
I/jxcore-log( 6676): 
I/jxcore-log( 6676): not ok 100 ReferenceError: _name is not defined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ---
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     operator: error
I/jxcore-log( 6676): 
,I/jxcore-log( 6676):     expected: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       undefined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     actual: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       [ReferenceError: _name is not defined]
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     stack: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:61:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13,
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       $v@timers.js:363:1
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ...
I/jxcore-log( 6676): 
I/jxcore-log( 6676): # #startUpdateAdvertisingAndListening should fail invalid router has been passed
I/jxcore-log( 6676): 
I/jxcore-log( 6676): not ok 101 ReferenceError: _name is not defined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ---
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     operator: error
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     expected: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       undefined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     actual: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       [ReferenceError: _name is not defined]
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     stack: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:84:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6676): 
,I/jxcore-log( 6676):       $v@timers.js:363:1
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ...
I/jxcore-log( 6676): 
I/jxcore-log( 6676): # teardown
I/jxcore-log( 6676): 
I/jxcore-log( 6676): not ok 102 ReferenceError: _name is not defined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ---
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     operator: error
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     expected: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       undefined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     actual: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       [ReferenceError: _name is not defined]
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     stack: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:92:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       $v@timers.js:363:1
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       
I/jxcore-log( 6676): 
,I/jxcore-log( 6676):   ...
I/jxcore-log( 6676): 
I/jxcore-log( 6676): # setup
I/jxcore-log( 6676): 
I/jxcore-log( 6676): not ok 103 ReferenceError: _name is not defined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ---
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     operator: error
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     expected: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       undefined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     actual: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       [ReferenceError: _name is not defined]
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     stack: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:61:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       $v@timers.js:363:1
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       
,I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ...
I/jxcore-log( 6676): 
I/jxcore-log( 6676): # #startUpdateAdvertisingAndListening should fail if router server starting fails
I/jxcore-log( 6676): 
I/jxcore-log( 6676): not ok 104 ReferenceError: _name is not defined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ---
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     operator: error
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     expected: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       undefined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     actual: |-
I/jxcore-log( 6676): 
,I/jxcore-log( 6676):       [ReferenceError: _name is not defined]
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     stack: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:84:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       $v@timers.js:363:1
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ...
I/jxcore-log( 6676): 
I/jxcore-log( 6676): # teardown
I/jxcore-log( 6676): 
,I/jxcore-log( 6676): not ok 105 ReferenceError: _name is not defined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ---
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     operator: error
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     expected: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       undefined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     actual: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       [ReferenceError: _name is not defined]
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     stack: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:92:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       $v@timers.js:363:1
I/jxcore-log( 6676): 
,I/jxcore-log( 6676):       
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ...
I/jxcore-log( 6676): 
I/jxcore-log( 6676): # setup
I/jxcore-log( 6676): 
I/jxcore-log( 6676): not ok 106 ReferenceError: _name is not defined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ---
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     operator: error
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     expected: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       undefined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     actual: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       [ReferenceError: _name is not defined]
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     stack: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:61:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       $v@timers.js:363:1
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       
I/jxcore-log( 6676): 
,I/jxcore-log( 6676):   ...
I/jxcore-log( 6676): 
I/jxcore-log( 6676): # #startUpdateAdvertisingAndListening should start hosting given router object
I/jxcore-log( 6676): 
I/jxcore-log( 6676): not ok 107 ReferenceError: _name is not defined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ---
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     operator: error
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     expected: |-
I/jxcore-log( 6676): 
,I/jxcore-log( 6676):       undefined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     actual: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       [ReferenceError: _name is not defined]
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     stack: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:84:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       $v@timers.js:363:1
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ...
I/jxcore-log( 6676): 
I/jxcore-log( 6676): # teardown
I/jxcore-log( 6676): 
,I/jxcore-log( 6676): not ok 108 ReferenceError: _name is not defined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ---
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     operator: error
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     expected: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       undefined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     actual: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       [ReferenceError: _name is not defined]
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     stack: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:92:5
I/jxcore-log( 6676): 
,I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       $v@timers.js:363:1
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ...
I/jxcore-log( 6676): 
I/jxcore-log( 6676): # setup
I/jxcore-log( 6676): 
,I/jxcore-log( 6676): not ok 109 ReferenceError: _name is not defined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ---
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     operator: error
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     expected: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       undefined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     actual: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       [ReferenceError: _name is not defined]
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     stack: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:61:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       $v@timers.js:363:1
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ...
I/jxcore-log( 6676): 
I/jxcore-log( 6676): # #stop can be called multiple times in a row
I/jxcore-log( 6676): 
I/jxcore-log( 6676): not ok 110 ReferenceError: _name is not defined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ---
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     operator: error
I/jxcore-log( 6676): 
,I/jxcore-log( 6676):     expected: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       undefined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     actual: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       [ReferenceError: _name is not defined]
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     stack: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:84:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       $v@timers.js:363:1
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       
I/jxcore-log( 6676): 
,I/jxcore-log( 6676):   ...
I/jxcore-log( 6676): 
I/jxcore-log( 6676): # teardown
I/jxcore-log( 6676): 
I/jxcore-log( 6676): not ok 111 ReferenceError: _name is not defined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ---
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     operator: error
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     expected: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       undefined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     actual: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       [ReferenceError: _name is not defined]
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     stack: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:92:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       $v@timers.js:363:1
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       
I/jxcore-log( 6676): 
,I/jxcore-log( 6676):   ...
I/jxcore-log( 6676): 
I/jxcore-log( 6676): # setup
I/jxcore-log( 6676): 
,I/jxcore-log( 6676): not ok 112 ReferenceError: _name is not defined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ---
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     operator: error
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     expected: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       undefined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     actual: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       [ReferenceError: _name is not defined]
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     stack: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:61:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       $v@timers.js:363:1
I/jxcore-log( 6676): 
,I/jxcore-log( 6676):       
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ...
I/jxcore-log( 6676): 
I/jxcore-log( 6676): # #startListeningForAdvertisements can be called multiple times in a row
I/jxcore-log( 6676): 
I/jxcore-log( 6676): not ok 113 ReferenceError: _name is not defined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ---
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     operator: error
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     expected: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       undefined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     actual: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       [ReferenceError: _name is not defined]
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     stack: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:84:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       $v@timers.js:363:1
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       
,I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ...
I/jxcore-log( 6676): 
I/jxcore-log( 6676): # teardown
I/jxcore-log( 6676): 
I/jxcore-log( 6676): not ok 114 ReferenceError: _name is not defined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ---
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     operator: error
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     expected: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       undefined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     actual: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       [ReferenceError: _name is not defined]
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     stack: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:92:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       $v@timers.js:363:1
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       
I/jxcore-log( 6676): 
,I/jxcore-log( 6676):   ...
I/jxcore-log( 6676): 
I/jxcore-log( 6676): # setup
I/jxcore-log( 6676): 
I/jxcore-log( 6676): not ok 115 ReferenceError: _name is not defined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ---
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     operator: error
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     expected: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       undefined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     actual: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       [ReferenceError: _name is not defined]
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     stack: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:61:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       $v@timers.js:363:1
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       
I/jxcore-log( 6676): 
,I/jxcore-log( 6676):   ...
I/jxcore-log( 6676): 
I/jxcore-log( 6676): # #stopListeningForAdvertisements can be called multiple times in a row
I/jxcore-log( 6676): 
I/jxcore-log( 6676): not ok 116 ReferenceError: _name is not defined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ---
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     operator: error
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     expected: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       undefined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     actual: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       [ReferenceError: _name is not defined]
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     stack: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:84:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6676): 
,I/jxcore-log( 6676):       $v@timers.js:363:1
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ...
I/jxcore-log( 6676): 
I/jxcore-log( 6676): # teardown
I/jxcore-log( 6676): 
I/jxcore-log( 6676): not ok 117 ReferenceError: _name is not defined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ---
I/jxcore-log( 6676): 
,I/jxcore-log( 6676):     operator: error
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     expected: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       undefined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     actual: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       [ReferenceError: _name is not defined]
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     stack: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:92:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       $v@timers.js:363:1
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ...
I/jxcore-log( 6676): 
I/jxcore-log( 6676): # setup
I/jxcore-log( 6676): 
,I/jxcore-log( 6676): not ok 118 ReferenceError: _name is not defined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ---
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     operator: error
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     expected: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       undefined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     actual: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       [ReferenceError: _name is not defined]
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     stack: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:61:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       $v@timers.js:363:1
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ...
I/jxcore-log( 6676): 
I/jxcore-log( 6676): # #stopAdvertisingAndListening can be called multiple times in a row
I/jxcore-log( 6676): 
I/jxcore-log( 6676): not ok 119 ReferenceError: _name is not defined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ---
I/jxcore-log( 6676): 
,I/jxcore-log( 6676):     operator: error
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     expected: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       undefined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     actual: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       [ReferenceError: _name is not defined]
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     stack: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:84:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       $v@timers.js:363:1
I/jxcore-log( 6676): 
,I/jxcore-log( 6676):       
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ...
I/jxcore-log( 6676): 
I/jxcore-log( 6676): # teardown
I/jxcore-log( 6676): 
,I/jxcore-log( 6676): not ok 120 ReferenceError: _name is not defined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ---
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     operator: error
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     expected: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       undefined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     actual: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       [ReferenceError: _name is not defined]
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     stack: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:92:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       $v@timers.js:363:1
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ...
I/jxcore-log( 6676): 
I/jxcore-log( 6676): # setup
I/jxcore-log( 6676): 
I/jxcore-log( 6676): not ok 121 ReferenceError: _name is not defined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ---
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     operator: error
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     expected: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       undefined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     actual: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       [ReferenceError: _name is not defined]
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     stack: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:61:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6676): 
,I/jxcore-log( 6676):       $v@timers.js:363:1
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ...
I/jxcore-log( 6676): 
I/jxcore-log( 6676): # functions are run from a queue in the right order
I/jxcore-log( 6676): 
I/jxcore-log( 6676): not ok 122 ReferenceError: _name is not defined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ---
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     operator: error
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     expected: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       undefined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     actual: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       [ReferenceError: _name is not defined]
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     stack: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:84:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       $v@timers.js:363:1
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       
I/jxcore-log( 6676): 
,I/jxcore-log( 6676):   ...
I/jxcore-log( 6676): 
I/jxcore-log( 6676): # teardown
I/jxcore-log( 6676): 
I/jxcore-log( 6676): not ok 123 ReferenceError: _name is not defined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):   ---
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     operator: error
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     expected: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       undefined
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     actual: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       [ReferenceError: _name is not defined]
I/jxcore-log( 6676): 
I/jxcore-log( 6676):     stack: |-
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:92:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       $v@timers.js:363:1
I/jxcore-log( 6676): 
I/jxcore-log( 6676):       
I/jxcore-log( 6676): 
,I/jxcore-log( 6676):   ...
I/jxcore-log( 6676): 
I/jxcore-log( 6676): Tests Complete
I/jxcore-log( 6676): 
,D/wpa_supplicant( 1351): wlan0: BSS: Remove id 2 BSSID c2:ff:d4:d3:aa:48 SSID '01ABC' due to wpa_bss_flush_by_age
,D/WifiMonitor(  959): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 2 c2:ff:d4:d3:aa:48]
E/WifiMonitor(  959): WifiMonitor:wlan0 cnt=48 dispatchEvent: CTRL-EVENT-BSS-REMOVED 2 c2:ff:d4:d3:aa:48
,I/jxcore-log( 6676): Toggling radios to false
I/jxcore-log( 6676): 
,D/BluetoothManagerService(  959): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  959): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@2fdf3746 mBinding = false
W/Settings:Agent(  959): MONITOR_LOG
W/Settings:Agent(  959): name: bluetooth_on
W/Settings:Agent(  959): value: 0
W/Settings:Agent(  959): >> traceCallingStack()
W/Settings:Agent(  959): Process.myPid(): 959
W/Settings:Agent(  959): Process.myTid(): 1768
W/Settings:Agent(  959): Process.myUid(): 1000
W/Settings:Agent(  959): 
W/Settings:Agent(  959): 
,W/System.err(  959): java.lang.Throwable: stack dump
W/System.err(  959): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  959): 	at android.provider.HtcISettings$Agent.traceCallingStack(HtcISettings.java:56)
W/System.err(  959): 	at android.provider.HtcISettingsGlobal$Agent.monitorKey(HtcISettingsGlobal.java:64)
W/System.err(  959): 	at android.provider.Settings$Global.putStringForUser(Settings.java:7422)
,W/System.err(  959): 	at android.provider.Settings$Global.putString(Settings.java:7403)
W/System.err(  959): 	at android.provider.Settings$Global.putInt(Settings.java:7503)
W/System.err(  959): 	at com.android.server.BluetoothManagerService.persistBluetoothSetting(BluetoothManagerService.java:378)
W/System.err(  959): 	at com.android.server.BluetoothManagerService.disable(BluetoothManagerService.java:624)
W/System.err(  959): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:116)
W/System.err(  959): 	at android.os.Binder.execTransact(Binder.java:454)
W/Settings:Agent(  959): 
W/Settings:Agent(  959): << traceCallingStack(): 5(ms)
,D/BluetoothManagerService(  959): Message: MESSAGE_DISABLE,
D/BluetoothManagerService(  959): Sending off request.,
D/WifiManager( 6676): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10366
D/WifiService(  959): setWifiEnabled: false pid=6676, uid=10366
E/WifiStateMachine(  959): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiService(  959): Invoking mWifiStateMachine.setWifiEnabled
W/Settings:Agent(  959): MONITOR_LOG
I/WifiService(  959): isSprintWifiRestricted(): false
W/Settings:Agent(  959): name: wifi_on
,I/WifiService(  959): isMdmWifiRestricted(): false
W/Settings:Agent(  959): value: 0
W/Settings:Agent(  959): >> traceCallingStack()
W/Settings:Agent(  959): Process.myPid(): 959
W/Settings:Agent(  959): Process.myTid(): 1765
W/Settings:Agent(  959): Process.myUid(): 1000
W/Settings:Agent(  959): 
W/Settings:Agent(  959): ,
W/System.err(  959): java.lang.Throwable: stack dump
W/System.err(  959): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  959): 	at android.provider.HtcISettings$Agent.traceCallingStack(HtcISettings.java:56)
W/System.err(  959): 	at android.provider.HtcISettingsGlobal$Agent.monitorKey(HtcISettingsGlobal.java:64)
W/System.err(  959): 	at android.provider.Settings$Global.putStringForUser(Settings.java:7422)
D/BluetoothAdapterState( 3098): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
W/System.err(  959): 	at android.provider.Settings$Global.putString(Settings.java:7403)
W/System.err(  959): 	at android.provider.Settings$Global.putInt(Settings.java:7503)
D/BluetoothAdapterProperties( 3098): Setting state to 13
W/System.err(  959): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:154)
I/BluetoothAdapterState( 3098): Bluetooth adapter state changed: 12-> 13
W/System.err(  959): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:112)
W/System.err(  959): ,	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:1144)
W/System.err(  959): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:222)
W/System.err(  959): 	at android.os.Binder.execTransact(Binder.java:454)
W/Settings:Agent(  959): 
W/Settings:Agent(  959): << traceCallingStack(): 3(ms)
D/BluetoothManagerService(  959): +onBluetoothStateChange prev=12 new=13
,D/BluetoothAdapterProperties( 3098): onBluetoothDisable()
I/BluetoothAdapterState( 3098): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
I/bt-btm  ( 3098): BTM_SetDiscoverability
I/bt-btif ( 3098): HAL bt_hal_cbacks->adapter_properties_cb
I/bt-btm  ( 3098): btm_ble_set_discoverability mode=0x0 combined_mode=0x0
D/bt-btm  ( 3098): disc_mode 0000
I/bt-btm  ( 3098): evt_type=0x0 p-cb->evt_type=0x0 
D/PMS     (  959): acquireWL(f69f9ba): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 3098 1002 null
I/bt-btm  ( 3098): BTM_SetDiscoverability: mode 0 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
,D/BluetoothAdapterProperties( 3098): Scan Mode:21
,D/WifiController(  959): handleMessage: E msg.what=155656
,D/WifiController(  959): processMsg: DeviceActiveState
D/WifiDisplayAdapter(  959): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  959):     Client/Owner: Client
D/WifiDisplayAdapter(  959):     GroupId: 
D/WifiDisplayAdapter(  959):     Passphrase: 
D/WifiDisplayAdapter(  959):     SessionId: 0
D/WifiDisplayAdapter(  959):     IP Address: }
D/WifiController(  959): processMsg: StaEnabledState
D/WifiController(  959): transitionTo: destState=ApStaDisabledState
D/WifiController(  959): handleMessage: new destination call exit/enter
D/WifiController(  959): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=DefaultState,active=true,parent=null
D/WifiController(  959): invokeExitMethods: DeviceActiveState
D/WifiController(  959): invokeExitMethods: StaEnabledState
D/WifiController(  959): moveTempStackToStateStack: i=0,j=1
D/WifiController(  959): moveTempStackToStateStack: X mStateStackTop=1,startingIndex=1,Top=ApStaDisabledState
D/WifiController(  959): invokeEnterMethods: ApStaDisabledState
I/jxcore-log( 6676): Radios toggled
I/jxcore-log( 6676): 
D/WifiController(  959): handleMessage: X
E/WifiStateMachine(  959): handleMessage: E msg.what=131084
E/WifiStateMachine(  959): processMsg: ConnectedState
I/bt-btm  ( 3098): BTM_SetConnectability
I/bt-btm  ( 3098): btm_ble_set_connectability mode=0x0 combined_mode=0x1
D/bt-btm  ( 3098): disc_mode 0000
I/bt-btm  ( 3098): BTM_SetConnectability: mode 1 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
E/WifiStateMachine(  959):  ConnectedState CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine(  959): processMsg: L2ConnectedState
D/BluetoothAdapterState( 3098): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
E/WifiStateMachine(  959):  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine(  959): processMsg: ConnectModeState
E/WifiStateMachine(  959):  ConnectModeState CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine(  959): processMsg: DriverStartedState
I/bt-btif ( 3098): BTA_JvDeleteRecord
E/WifiStateMachine(  959):  DriverStartedState CMD_STOP_SUPPLICANT 0 0
,E/WifiStateMachine(  959): processMsg: SupplicantStartedState
E/WifiStateMachine(  959):  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
I/bt-btif ( 3098): BTA_JvRfcommStopServer
D/bt-btm  ( 3098): BTM_FreeSCN 
I/bt-btif ( 3098): BTA_JvDeleteRecord
I/bt-btif ( 3098): BTA_JvRfcommStopServer
D/bt-btm  ( 3098): BTM_FreeSCN 
I/bt-btif ( 3098): BTA_JvDeleteRecord
I/bt-btif ( 3098): BTA_JvRfcommStopServer
D/bt-btm  ( 3098): BTM_FreeSCN 
I/bt-btif ( 3098): BTA_JvDeleteRecord
I/bt-btif ( 3098): BTA_JvRfcommStopServer
D/bt-btm  ( 3098): BTM_FreeSCN 
I/bt-btif ( 3098): BTA_JvDeleteRecord
I/bt-btif ( 3098): BTA_JvRfcommStopServer
D/WifiP2pService(  959): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/bt-btm  ( 3098): BTM_FreeSCN 
D/WifiP2pService(  959): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/bt-sdp  ( 3098): SDP_DeleteRecord ok, num_records:14
,E/WifiStateMachine(  959): transitionTo: destState=WaitForP2pDisableState
E/WifiStateMachine(  959): handleMessage: new destination call exit/enter
E/WifiStateMachine(  959): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=SupplicantStartedState,active=true,parent=DefaultState
E/WifiStateMachine(  959): invokeExitMethods: ConnectedState
E/WifiStateMachine(  959): WifiStateMachine: Leaving Connected state
D/WifiPerfLock(  959): release()
E/WifiStateMachine(  959): PerfLock released for exiting ConnectedState
E/WifiStateMachine(  959): setScanAlarm false period 20000 initial delay 0mAlarmEnabledfalse
I/bt-btif ( 3098): BTA_JvDeleteRecord
I/bt-btif ( 3098): BTA_JvRfcommStopServer
D/bt-btm  ( 3098): BTM_FreeSCN 
E/WifiStateMachine(  959): invokeExitMethods: L2ConnectedState
E/bt-btif ( 3098): cmd socket is not created
E/BtOppRfcommListener( 3098): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothSapService( 3098): Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/WifiStateMachine(  959): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$13400 - exit - invokeExitMethods
E/WifiStateMachine(  959): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
I/bt-btm  ( 3098): BTM_SEC_CLR[13]: id 55
D/PMS     (  959): acquireWL(3a12306b): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1936 10024 WorkSource{10024 com.google.android.gms}
D/bt-sdp  ( 3098): SDP_DeleteRecord ok, num_records:13
I/bt-btm  ( 3098): BTM_SEC_CLR[14]: id 56
D/bt-sdp  ( 3098): SDP_DeleteRecord ok, num_records:12
I/bt-btm  ( 3098): BTM_SEC_CLR[15]: id 57
D/bt-sdp  ( 3098): SDP_DeleteRecord ok, num_records:11
I/bt-btm  ( 3098): BTM_SEC_CLR[16]: id 58
D/bt-sdp  ( 3098): SDP_DeleteRecord ok, num_records:10
I/bt-btm  ( 3098): BTM_SEC_CLR[17]: id 59,
D/bt-sdp  ( 3098): SDP_DeleteRecord ok, num_records:9
D/ConnectivityService(  959): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
I/bt-btm  ( 3098): BTM_SEC_CLR[18]: id 60
D/ConnectivityService(  959): NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
D/bt-sdp  ( 3098): SDP_DeleteRecord ok, num_records:8
V/NetworkPolicy(  959): mWifiStateReceiver: meteredHint=false,EPS mode=false
I/bt-btm  ( 3098): Write Extended Inquiry Response to controller
I/bt-btm  ( 3098): Write Extended Inquiry Response to controller
I/bt-btm  ( 3098): Write Extended Inquiry Response to controller
I/bt-btm  ( 3098): Write Extended Inquiry Response to controller
E/WifiStateMachine(  959): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  959): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
W/WifiHW  (  959): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1351): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1351): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1351): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  959): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1351): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1351): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 1351): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1351): CTRL_IFACE: SAVE_CONFIG - Configuration updated
D/BluetoothManagerService(  959): Message: MESSAGE_BLUETOOTH_STATE_CHANGE
D/BluetoothManagerService(  959): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
D/BluetoothManagerService(  959): Bluetooth State Change Intent: 12 -> 13
E/WifiStateMachine(  959): setSuspendOptimizationsNative: 1 true -want false stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
W/WifiHW  (  959): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
D/wpa_supplicant( 1351): wlan0: Control interface command 'DRIVER POWERMODE 0'
I/wpa_supplicant( 1351): Power_Mode_Type mode = 0
I/wpa_supplicant( 1351): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
W/bt-l2cap( 3098): L2CAP - L2CA_Deregister() called for PSM: 0x000f
I/IntentController( 1218): receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
I/bt-btm  ( 3098): BTM_SetDiscoverability
I/bt-btm  ( 3098): btm_ble_set_discoverability mode=0x0 combined_mode=0x0
D/bt-btm  ( 3098): disc_mode 0000
I/bt-btm  ( 3098): evt_type=0x0 p-cb->evt_type=0x0 
I/bt-btm  ( 3098): BTM_SetDiscoverability: mode 0 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
,D/ConnectivityService(  959): reportBadNetwork(NetworkAgentInfo [WIFI () - 101]) by 10024
I/bt-btm  ( 3098): BTM_SetConnectability
I/bt-btm  ( 3098): btm_ble_set_connectability mode=0x0 combined_mode=0x0
D/bt-btm  ( 3098): disc_mode 0000
D/bt-btm  ( 3098): btm_ble_update_adv_flag new=0x1c
D/bt-btm  ( 3098): btm_ble_update_adv_flag old=0x18
I/bt-btm  ( 3098): BTM_SetConnectability: mode 0 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
I/bt-btm  ( 3098): BTM_IsInquiryActive
I/bt-btm  ( 3098): BTM_CancelRemoteDeviceName()
I/bt-btm  ( 3098): btm_ble_clear_white_list
W/bt-btif ( 3098): bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
W/WifiHW  (  959): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
D/wpa_supplicant( 1351): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/wpa_supplicant( 1351): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 8192
D/WifiDataStallTracker(  959): setDhcpActive: false
D/bt-btif ( 3098): AG evt (hdl 0x0001): State 0, Event 0x0501
D/bt-btif ( 3098): AG evt (hdl 0x0002): State 0, Event 0x0501
D/bt-sdp  ( 3098): SDP_DeleteRecord ok, num_records:7
D/bt-btm  ( 3098): BTM_FreeSCN 
I/bt-btm  ( 3098): BTM_SEC_CLR[3]: id 12
D/bt-sdp  ( 3098): SDP_DeleteRecord ok, num_records:6
D/bt-btm  ( 3098): BTM_FreeSCN 
I/bt-btm  ( 3098): BTM_SEC_CLR[4]: id 29
D/bt-avp  ( 3098): AVRC_Close handle:0
D/bt-btif ( 3098): AV Sevent(0x41)=0x120a(API_CLOSE) state=0(INITT
D/bt-btif ( 3098): AV Sevent(0x41)=0x120a(API_CLOSE) state=0(INIT)
V/NativeCrypto( 1936): Read error: ssl=0x557ae26fb0: I/O error during system call, Connection timed out
D/bt-sdp  ( 3098): SDP_DeleteRecord ok, num_records:5
D/bt-sdp  ( 3098): SDP_DeleteRecord ok, num_records:4
W/bt-l2cap( 3098): L2CAP - L2CA_Deregister() called for PSM: 0x0019
D/bt-sdp  ( 3098): SDP_DeleteRecord ok, num_records:3
W/bt-l2cap( 3098): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3098): L2CAP - L2CA_Deregister() called for PSM: 0x0019
,W/bt-l2cap( 3098): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3098): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3098): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3098): L2CAP - L2CA_Deregister() called for PSM: 0x0011
W/bt-l2cap( 3098): L2CAP - L2CA_Deregister() called for PSM: 0x0013
I/bt-att  ( 3098): GATT_Deregister gatt_if=3
I/bt-att  ( 3098): GATT_Listen gatt_if=3
I/bt-btm  ( 3098): BTM_BleUpdateAdvFilterPolicy
I/bt-btm  ( 3098): BTM_ReadConnectability
I/bt-btm  ( 3098): btm_ble_set_connectability mode=0x0 combined_mode=0x0
D/bt-btm  ( 3098): disc_mode 0000
I/bt-att  ( 3098): GATT_Deregister gatt_if=4
I/bt-att  ( 3098): GATT_Listen gatt_if=4
I/bt-btm  ( 3098): BTM_BleUpdateAdvFilterPolicy
D/WIFI_ICON( 1218): updateWifiState: NETWORK_STATE_CHANGED connected
I/bt-btm  ( 3098): BTM_ReadConnectability
D/StatusBar.NetworkController( 1218): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
I/bt-btm  ( 3098): btm_ble_set_connectability mode=0x0 combined_mode=0x0
D/bt-btm  ( 3098): disc_mode 0000
E/bt-btif ( 3098): bta_gattc_deregister Deregister Failedm unknown client cif
D/libc    (  959): [NET] android_getaddrinfofornet+,hn 13(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  959): [NET] android_getaddrinfofornet-, SUCCESS
V/NativeCrypto( 1936): SSL shutdown failed: ssl=0x557ae26fb0: I/O error during system call, Broken pipe
I/bt-btm  ( 3098): btm_ble_clear_white_list_complete
E/WifiStateMachine(  959): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  959): setDetailed state send new extra info<unknown ssid>
E/WifiStateMachine(  959): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  959): [NET] android_getaddrinfofornet+,hn 6,sn(),hints(known),family 0,flags 4
E/WifiStateMachine(  959): NetworkAgent != null
E/WifiStateMachine(  959): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
E/WifiTrafficPoller(  959): ENABLE_TRAFFIC_STATS_POLL false Token 26
D/libc    (  959): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  959): [NET] android_getaddrinfofornet+,hn 25(0x666538303a3a39),sn(),hints(known),family 0,flags 4
D/libc    (  959): [NET] android_getaddrinfofornet-, SUCCESS
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  959): ValidatedState{ when=0 what=532488 arg1=10024 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  959): DefaultState{ when=0 what=532488 arg1=10024 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  959): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  959): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  959): Validated
D/NGFService( 3714): Receiver: action = android.bluetooth.adapter.action.STATE_CHANGED
I/IntentController( 1218): receive(android.net.wifi.STATE_CHANGE,1,false)
D/PMS     (  959): releaseWL(3a12306b): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms}
E/WifiStateMachine(  959): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,E/WifiStateMachine(  959): autoRoamSetBSSID any key="NG700"WPA_PSK
E/WifiConfigStore(  959): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
W/WifiHW  (  959): QCOM Debug skip set_network part for security concern!
D/WifiDataStallTracker(  959): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/wpa_supplicant( 1351): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/WifiDataStallTracker(  959): stopDataStallAlarm 
D/wpa_supplicant( 1351): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1351): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
E/WifiTrafficPoller(  959): ENABLE_TRAFFIC_STATS_POLL false Token 27
E/WifiDataStallTracker(  959): ENABLE_DATA_MONITOR_POLL false Token 5
,W/WifiHW  (  959): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1351): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1351): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
E/WifiTrafficPoller(  959): ENABLE_TRAFFIC_STATS_POLL false Token 28
I/IntentController( 1218): receive(android.net.wifi.STATE_CHANGE,1,false)
D/wpa_supplicant( 1351): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1351): CTRL_IFACE: SAVE_CONFIG - Configuration updated
D/WIFI_ICON( 1218): updateWifiState: NETWORK_STATE_CHANGED disconnected
E/WifiStateMachine(  959): invokeExitMethods: ConnectModeState
D/StatusBar.NetworkController( 1218): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiStateMachine(  959): invokeExitMethods: DriverStartedState
D/WIFI_ICON( 1218): updateWifiState: NETWORK_STATE_CHANGED disconnected
W/WifiHW  (  959): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
D/StatusBar.NetworkController( 1218): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/wpa_supplicant( 1351): wlan0: Control interface command 'DRIVER WLS_BATCHING GET'
E/wpa_supplicant( 1351): wpa_driver_nl80211_driver_cmd: failed to issue private commands
E/WifiStateMachine(  959): Unexpected BatchedScanResults :null
W/WifiHW  (  959): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/IntentController( 1218): receive(android.net.wifi.STATE_CHANGE,1,false)
D/wpa_supplicant( 1351): wlan0: Control interface command 'DRIVER WLS_BATCHING STOP'
,E/wpa_supplicant( 1351): wpa_driver_nl80211_driver_cmd: failed to issue private commands
E/WifiStateMachine(  959): noteBatchedScanstop()
,E/WifiStateMachine(  959): [1,454,523,339,578 ms] noteScanEnd no scan source
E/WifiStateMachine(  959): moveTempStackToStateStack: i=0,j=2
E/WifiStateMachine(  959): moveTempStackToStateStack: X mStateStackTop=2,startingIndex=2,Top=WaitForP2pDisableState
D/WifiP2pService(  959): InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  959): invokeEnterMethods: WaitForP2pDisableState
D/WifiP2pService(  959): P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  959): handleMessage: X
E/WifiStateMachine(  959): handleMessage: E msg.what=131212
,E/WifiStateMachine(  959): processMsg: WaitForP2pDisableState
E/WifiStateMachine(  959):  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  959): processMsg: SupplicantStartedState
E/WifiStateMachine(  959):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  959): processMsg: DefaultState
D/WifiScanningService(  959): SCAN_AVAILABLE : 1
E/WifiStateMachine(  959):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/RttService(  959): SCAN_AVAILABLE : 1
D/WifiScanningService(  959): DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  959): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  959): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  959): handleMessage: X
D/RttService(  959): EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNetworkAgent(  959): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine(  959): handleMessage: E msg.what=131212
E/WifiStateMachine(  959): processMsg: WaitForP2pDisableState
E/WifiStateMachine(  959):  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  959): processMsg: SupplicantStartedState
,E/WifiStateMachine(  959):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  959): processMsg: DefaultState
E/WifiStateMachine(  959):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  959): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  959): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  959): handleMessage: X
E/WifiStateMachine(  959): handleMessage: E msg.what=131212
E/WifiStateMachine(  959): processMsg: WaitForP2pDisableState
E/WifiStateMachine(  959):  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  959): processMsg: SupplicantStartedState
E/WifiStateMachine(  959):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  959): processMsg: DefaultState
E/WifiStateMachine(  959):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  959): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  959): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  959): handleMessage: X
,D/WISPrService( 6390): >>>>>WISPrService start isConnected = true<<<<<
E/WifiStateMachine(  959): handleMessage: E msg.what=131131
E/WifiStateMachine(  959): processMsg: WaitForP2pDisableState
V/BluetoothPbapReceiver( 3098): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
D/WifiMonitor(  959): stopMonitoring(p2p0) = com.android.server.wifi.p2p.WifiP2pServiceImpl$P2pStateMachine@4a3099a
V/BluetoothPbapReceiver( 3098): ***********state = 13
E/WifiStateMachine(  959):  WaitForP2pDisableState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine(  959): processMsg: SupplicantStartedState
D/WifiP2pService(  959): P2pDisablingState
E/WifiStateMachine(  959):  SupplicantStartedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
D/WifiP2pService(  959): P2pDisablingState{ when=-1ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  959): processMsg: DefaultState
D/WifiP2pService(  959): p2p socket connection lost
E/WifiStateMachine(  959):  DefaultState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
D/WifiDisplayController(  959): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
,E/WifiStateMachine(  959): handleMessage: X
D/WifiP2pService(  959): P2pDisabledState
E/WifiStateMachine(  959): handleMessage: E msg.what=131205
D/WifiDisplayAdapter(  959): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  959):     Client/Owner: Client
D/WifiDisplayAdapter(  959):     GroupId: 
D/WifiDisplayAdapter(  959):     Passphrase: 
D/WifiDisplayAdapter(  959):     SessionId: 0
D/WifiDisplayAdapter(  959):     IP Address: }
,E/WifiStateMachine(  959): processMsg: WaitForP2pDisableState
D/WifiP2pService(  959): P2pDisabledState{ when=0 what=131333 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  959):  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
D/WifiP2pService(  959): DefaultState{ when=0 what=131333 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  959): transitionTo: destState=SupplicantStoppingState
E/WifiStateMachine(  959): handleMessage: new destination call exit/enter
E/WifiStateMachine(  959): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=DefaultState,active=true,parent=null
E/WifiStateMachine(  959): invokeExitMethods: WaitForP2pDisableState
,E/WifiStateMachine(  959): invokeExitMethods: SupplicantStartedState
D/WifiP2pService(  959): P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  959): moveTempStackToStateStack: i=0,j=1
E/WifiStateMachine(  959): moveTempStackToStateStack: X mStateStackTop=1,startingIndex=1,Top=SupplicantStoppingState
E/WifiStateMachine(  959): invokeEnterMethods: SupplicantStoppingState
E/WifiStateMachine(  959): Call handleNetworkDisconnect() in SupplicantStoppingState
I/BtOppRfcommListener( 3098): stopping Accept Thread
V/AudioService(  959): Broadcast Receiver: DisplayManager.ACTION_WIFI_DISPLAY_STATUS_CHANGED, WifiDisplayStatus = WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
V/AudioService(  959):     Client/Owner: Client
V/AudioService(  959):     GroupId: 
V/AudioService(  959):     Passphrase: 
V/AudioService(  959):     SessionId: 0
V/AudioService(  959):     IP Address: }
,D/WifiP2pService(  959): DefaultState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/HtcEffectManagerBase(  959): onEventChanged id=5 status=false
D/HtcEffectManager(  959): checkBeatsSupport mMirrorOn=false mMiracastOn=false mSubwooferOn=false mSubwooferHeadset=false mHeadsetConnected=false mBTHeadsetConnected=false mBTA2dpHeadset=false mHDMIOn=false mBeatsSpeaker=true mAllPlayOn=false
D/HtcEffectManager(  959): convertEffect before=902
D/HtcEffectManager(  959): convertEffect after=902
I/BtOppRfcommListener( 3098): BluetoothSocket listen thread finished
I/QuickSettingBluetooth( 1218): receive.ACTION_STATE_CHANGE:STATE_TURNING_OFF
E/WifiStateMachine(  959): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$13400 - enter - invokeEnterMethods
,D/WISPrService( 6390): >>>>>WISPrService start isConnected = false<<<<<
E/WifiStateMachine(  959): setSuspendOptimizationsNative: 1 true -want false stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
W/WifiHW  (  959): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
D/wpa_supplicant( 1351): wlan0: Control interface command 'DRIVER POWERMODE 0'
I/wpa_supplicant( 1351): Power_Mode_Type mode = 0
I/wpa_supplicant( 1351): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
D/WISPrService( 6390): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
W/WifiHW  (  959): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
D/wpa_supplicant( 1351): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/wpa_supplicant( 1351): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 8192
,D/WifiDataStallTracker(  959): setDhcpActive: false
D/WISPrService( 6390): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 6390): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,V/BluetoothPbapService( 3098): Pbap Service closeService in
,V/BluetoothPbapService( 3098): successfully stopped pbap service
V/BluetoothPbapService( 3098): Pbap Service closeService out
V/BluetoothPbapService( 3098): Pbap Service onDestroy
,I/QuickSettingWifi( 1218): receive.wifiConnect:true wifiAPname:<unknown ssid> elapse:1
,V/BluetoothPbapService( 3098): Pbap Service closeService in
V/BluetoothPbapService( 3098): Pbap Service closeService out
,I/QuickSettingWifi( 1218): receive.wifiConnect:false wifiAPname:null elapse:1
,I/QuickSettingWifi( 1218): receive.wifiConnect:false wifiAPname:null elapse:0
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  959): ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  959): notifyType LOST for NetworkAgentInfo [WIFI () - 101]
D/usbnet  (  959): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  959):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  959): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  959):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  959): Disconnected - quitting
,D/ConnectivityService(  959): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/usbnet  (  959):   my score=70, my filter=[ Transports:  Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/Nat464Xlat(  959): requiresClat: netType=1, connected=false, mIsClatEnabled=true, hasIPv4Address=true
D/usbnet  (  959): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
D/ConnectivityService(  959): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1218): CM callback handler got msg 524292
D/ConnectivityService(  959): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isSkipMobile=false
I/SecurityController( 1218): onLost 101
D/NetworkManagementService(  959): Removing idletimer
D/Tethering(  959): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
D/PMS     (  959): acquireWL(10285061): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 959 1000 null
D/Tethering(  959): TetherMasterSM: InitialState processMessage what=UPSTREAM_CHANGED
D/CSLegacyTypeTracker(  959): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=false
E/WifiStateMachine(  959): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
D/ConnectivityService(  959): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
E/WifiStateMachine(  959): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/ConnectivityService(  959): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
E/WifiStateMachine(  959): stopping supplicant
E/ConnectivityService(  959): EVENT_NETWORK_VALIDATED - isLiveNetworkAgent found mismatched netId: null - NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::92e7:c4ff:fee6:4cf8/64,192.168.1.130/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
W/WifiHW  (  959): QCOM Debug wifi_send_command "TERMINATE"
E/ConnectivityService(  959): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/wpa_supplicant( 1351): RX global ctrl_iface - hexdump(len=9): 54 45 52 4d 49 4e 41 54 45
V/NetworkPolicy(  959): ensureActiveMobilePolicyLocked()
D/wpa_supplicant( 1351): wlan0: Removing interface wlan0
D/PMS     (  959): acquireWL(35adf786): PARTIAL_WAKE_LOCK  NetworkStats 0x1 959 1000 null
E/WifiTrafficPoller(  959): ENABLE_TRAFFIC_STATS_POLL false Token 29
D/DATA_ICON( 1218): updateConnectivity android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE Type:-1/Status:0
E/WifiStateMachine(  959): setWifiState: disabling
D/NetworkPolicy(  959): ensureActiveMobilePolicyLocked: SIM state invalid, slotId= -1000, subId=-1000 . Return.
D/wpa_supplicant( 1351): wlan0: Request to deauthenticate - bssid=c0:ff:d4:d3:aa:48 pending_bssid=00:00:00:00:00:00 reason=3 state=COMPLETED
V/NetworkPolicy(  959): updateNetworkEnabledLocked()
D/wpa_supplicant( 1351): TDLS: Tear down peers
V/NetworkPolicy(  959): updateIfacesLocked()
D/wpa_supplicant( 1351): wpa_driver_nl80211_disconnect(reason_code=3)
V/NetworkPolicy(  959): updateNotificationsLocked(),
I/IntentController( 1218): receive(android.net.wifi.STATE_CHANGE,1,false)
D/DATA_ICON( 1218): dataConnected: false/false
E/WifiStateMachine(  959): handleMessage: X
D/StatusBar.NetworkController( 1218): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WIFI    (  959): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI_ICON( 1218): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/WIFI    (  959):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/StatusBar.NetworkController( 1218): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WIFI    (  959): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
D/NetworkManagementService(  959): isBandwidthControlEnabled: doneSignal.getCount()= 0
I/IntentController( 1218): receive(android.net.wifi.WIFI_STATE_CHANGED,1,false)
D/PMS     (  959): releaseWL(35adf786): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/WIFI_ICON( 1218): updateWifiState: WIFI_STATE_CHANGED disabled
D/StatusBar.NetworkController( 1218): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
V/NetworkPolicy(  959): updateNetworkEnabledLocked()
V/NetworkPolicy(  959): updateNotificationsLocked()
,D/PMS     (  959): acquireWL(2de93874): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 6390 1000 null
,W/ContextImpl( 6390): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:141 com.android.settings.bluetooth.DockEventReceiver.onReceive:121 
,D/wpa_supplicant( 1351): wlan0: Event DEAUTH (12) received
I/ActivityManager(  959): Start proc com.htc.widget.hmsproc2 for broadcast com.htc.htchotspotwidget/.HotspotReceiver: pid=7244 uid=10040 gids={50040, 9997, 3002, 3001, 3003} abi=arm64-v8a
D/wpa_supplicant( 1351): wlan0: Deauthentication notification
D/wpa_supplicant( 1351): wlan0:  * reason 3 (locally generated)
D/wpa_supplicant( 1351): Deauthentication frame IE(s) - hexdump(len=0): [NULL]
I/wpa_supplicant( 1351): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1351): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/wpa_supplicant( 1351): enter disconnect check
I/wpa_supplicant( 1351): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/WifiMonitor(  959): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412]
E/WifiMonitor(  959): WifiMonitor:wlan0 cnt=49 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/WifiMonitor(  959): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  959): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
,E/WifiMonitor(  959): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
D/wpa_supplicant( 1351): wlan0: Auto connect disabled: do not try to re-connect
D/wpa_supplicant( 1351): wlan0: Ignore connection failure indication since interface has been put into disconnected state
D/wpa_supplicant( 1351): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1351): wlan0: Disconnect event - remove keys
D/wpa_supplicant( 1351): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/Tethering(  959): interfaceLinkStateChanged wlan0, false
D/Tethering(  959): interfaceStatusChanged wlan0, false
D/wpa_supplicant( 1351): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/WifiStateMachine(  959): WiFiDisplay: getWifidisplayApEnabled=false
D/wpa_supplicant( 1351): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x5571f57f88 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1351):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1351): wlan0: State: COMPLETED -> DISCONNECTED
E/WifiStateMachine(  959): handleMessage: E msg.what=147460
D/wpa_supplicant( 1351): nl80211: Set wlan0 operstate 1->0 (DORMANT)
E/WifiStateMachine(  959): processMsg: SupplicantStoppingState
D/wpa_supplicant( 1351): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 1351): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1351): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1351): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1351): nl80211: Skip set_supp_port(unauthorized) while not associated
D/wpa_supplicant( 1351): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1351): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1351): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1351): wlan0: State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1351): nl80211: Set wlan0 operstate 0->0 (DORMANT)
D/wpa_supplicant( 1351): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 1351): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1351): EAPOL: External notification - portValid=0
E/WifiStateMachine(  959):  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=269332
E/WifiStateMachine(  959): processMsg: DefaultState
,D/Tethering(  959): TetherInterfaceSM: wlan0: InitialState processMessage what=CMD_INTERFACE_DOWN
D/Tethering(  959): interfaceLinkStateChanged wlan0, false
V/Tethering(  959): TetherInterfaceSM: wlan0: exit InitialState
D/Tethering(  959): interfaceStatusChanged wlan0, false
V/Tethering(  959): TetherInterfaceSM: wlan0: enter UnavailableState
E/WifiStateMachine(  959): WiFiDisplay: getWifidisplayApEnabled=false
D/WifiMonitor(  959): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor(  959): WifiMonitor:wlan0 cnt=50 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine(  959):  DefaultState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=269333
E/WifiStateMachine(  959): handleMessage: X
D/HTCRequest(  959): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  959): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  959): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  959): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
E/WifiStateMachine(  959): handleMessage: E msg.what=147462
E/WifiStateMachine(  959): processMsg: SupplicantStoppingState
E/WifiStateMachine(  959): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiStateMachine(  959):  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 50 0 rt=269334  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine(  959): processMsg: DefaultState
E/WifiStateMachine(  959):  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 50 0 rt=269336  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine(  959): handleMessage: X
D/WISPrService( 6390): >>>>>WISPrService start isConnected = false<<<<<
,D/PMS     (  959): releaseWL(2de93874): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 null
,D/PMS     (  959): acquireWL(15e20612): PARTIAL_WAKE_LOCK  StartingDockService 0x1 6390 1000 null
,D/WISPrService( 6390): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,I/QuickSettingWifi( 1218): receive.wifiConnect:false wifiAPname:null elapse:0
,W/System.err(  959): java.lang.Throwable: stack dump
W/System.err(  959): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  959): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  959): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  959): 	at android.os.Binder.execTransact(Binder.java:454)
,I/QuickSettingWifi( 1218): receive.wifiState:WIFI_STATE_DISABLING setEnable:false
,I/ActivityManager(  959): Start proc com.htc.widget.hmsproc3 for broadcast com.htc.htcbtwidget/.BTReceiver: pid=7264 uid=10034 gids={50034, 9997, 3002, 3001} abi=arm64-v8a
,D/WifiService(  959): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=httpproxy
D/Tethering(  959): sendTetherStateChangedBroadcast 0, 0, 0
,D/BluetoothManagerService(  959): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  959): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1311aa99:true
D/UsbnetService(  959): BroadcastReceiver::onReceive+
D/UsbDeviceManager(  959): [USBNET] bCheckSuppFunc: cdc_network
E/WifiStateMachine(  959): handleMessage: E msg.what=131101
D/PMS     (  959): acquireWL(bd6715e): PARTIAL_WAKE_LOCK  NetworkStats 0x1 959 1000 null
E/WifiStateMachine(  959): processMsg: SupplicantStoppingState
D/UsbnetService(  959): ACTION_TETHER_STATE_CHANGED: active=[],USB_FUNCTION_NCM=false
D/UsbnetService(  959): BroadcastReceiver::onReceive-
E/WifiStateMachine(  959):  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  959): processMsg: DefaultState
E/WifiStateMachine(  959):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/WifiStateMachine(  959): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  959): Default got CMD_TETHER_STATE_CHANGE
E/WifiStateMachine(  959): handleMessage: X
D/BluetoothAdapter( 6390): 98432338: getState(). Returning 13
,W/bt-btif ( 3098): ag scb idx 1 not allocated,
D/bt-btm  ( 3098): BTM_BleGetVendorCapabilities
W/bt-btif ( 3098): ag scb idx 2 not allocated
E/bt-btif ( 3098): BTA AG is already disabled, ignoring ...
W/bt-l2cap( 3098): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 3098): L2CAP - PSM: 0x0019 not found for deregistration,
W/bt-l2cap( 3098): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3098): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3098): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 3098): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3098): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3098): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3098): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 3098): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3098): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3098): L2CAP - PSM: 0x0017 not found for deregistration
I/ActivityManager(  959): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=7286 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a
E/bt-btif ( 3098): bta_gattc_deregister Deregister Failedm unknown client cif
E/bt_userial_mct( 3098): pthread_join() FAILED result:3
D/BluetoothInputDevice( 6390): BluetoothInputDevice()
,D/BluetoothManagerService(  959): registerStateChangeCallback+
D/BluetoothManagerService(  959): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  959): Registered receivers: 9
E/WifiStateMachine(  959): handleMessage: E msg.what=196614
D/WifiService(  959): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=callernameid
E/WifiStateMachine(  959): processMsg: SupplicantStoppingState
D/PMS     (  959): releaseWL(bd6715e): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
V/NetworkPolicy(  959): updateNetworkEnabledLocked()
V/NetworkPolicy(  959): updateNotificationsLocked()
,E/WifiStateMachine(  959):  SupplicantStoppingState CMD_ON_QUIT 0 0
E/WifiStateMachine(  959): processMsg: DefaultState
E/WifiStateMachine(  959):  DefaultState CMD_ON_QUIT 0 0
E/WifiStateMachine(  959): handleMessage: X
,D/WifiService(  959): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=verizon
D/BluetoothPan( 6390): BluetoothPan()
D/BluetoothManagerService(  959): registerStateChangeCallback+
D/BluetoothManagerService(  959): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  959): Registered receivers: 10
,D/BluetoothMap( 6390): Create BluetoothMap proxy object,
,D/BluetoothManagerService(  959): registerStateChangeCallback+
D/BluetoothManagerService(  959): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  959): Registered receivers: 11
,E/BluetoothMap( 6390): Could not bind to Bluetooth MAP Service with Intent { act=android.bluetooth.IBluetoothMap }
,D/WifiService(  959): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=fota
,D/HtcBtWidget_BTWidgetProvider( 7264): onBTStateChanged() for widget: ,
,D/HtcBtWidget_BTWidgetProvider( 7264): updateWidget(context) for widget: 
,E/wpa_supplicant( 1351): wlan0: BLACKLIST CLEAR 
D/wpa_supplicant( 1351): wlan0: BSS: Remove id 0 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g' due to wpa_bss_flush,
D/WifiMonitor(  959): Event [IFNAME=wlan0 BLACKLIST CLEAR ]
D/wpa_supplicant( 1351): wlan0: BSS: Remove id 1 BSSID c0:ff:d4:d3:aa:48 SSID 'NG700' due to wpa_bss_flush
E/WifiMonitor(  959): WifiMonitor:wlan0 cnt=51 dispatchEvent: BLACKLIST CLEAR 
,D/WifiMonitor(  959): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a]
D/wpa_supplicant( 1351): wlan0: BSS: Remove id 3 BSSID 38:f8:89:11:e9:11 SSID 'Gonzos' due to wpa_bss_flush
E/WifiMonitor(  959): WifiMonitor:wlan0 cnt=52 dispatchEvent: CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a
D/wpa_supplicant( 1351): wlan0: BSS: Remove id 4 BSSID 9e:93:4e:3e:ba:c5 SSID 'DIRECT-qjWorkCentre 3025' due to wpa_bss_flush
,D/WifiMonitor(  959): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 1 c0:ff:d4:d3:aa:48]
E/WifiMonitor(  959): WifiMonitor:wlan0 cnt=53 dispatchEvent: CTRL-EVENT-BSS-REMOVED 1 c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1351): wlan0: Cancelling delayed sched scan
D/wpa_supplicant( 1351): wlan0: Cancelling scan request
D/wpa_supplicant( 1351): wlan0: Cancelling authentication timeout
D/WifiMonitor(  959): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 3 38:f8:89:11:e9:11]
E/wpa_supplicant( 1351): wlan0: BLACKLIST REMOVE 00:00:00:00:00:00
E/WifiMonitor(  959): WifiMonitor:wlan0 cnt=54 dispatchEvent: CTRL-EVENT-BSS-REMOVED 3 38:f8:89:11:e9:11
D/WifiMonitor(  959): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 4 9e:93:4e:3e:ba:c5]
E/WifiMonitor(  959): WifiMonitor:wlan0 cnt=55 dispatchEvent: CTRL-EVENT-BSS-REMOVED 4 9e:93:4e:3e:ba:c5
D/WifiMonitor(  959): Event [IFNAME=wlan0 BLACKLIST REMOVE 00:00:00:00:00:00]
E/WifiMonitor(  959): WifiMonitor:wlan0 cnt=56 dispatchEvent: BLACKLIST REMOVE 00:00:00:00:00:00
D/wpa_supplicant( 1351): Remove interface wlan0 from radio phy0
,I/art     (  959): Explicit concurrent mark sweep GC freed 50300(2MB) AllocSpace objects, 7(1280KB) LOS objects, 33% free, 18MB/28MB, paused 1.767ms total 183.001ms
D/BluetoothManagerService(  959): registerStateChangeCallback+
D/PMS     (  959): releaseWL(f69f9ba): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 null,
,D/BluetoothSap( 6390): BluetoothSap() call bindService
,D/BluetoothManagerService(  959): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  959): Registered receivers: 12
,D/WifiService(  959): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=supl
,D/BluetoothFtpService( 3098): ACTION_STATE_CHANGED: state: 13mHasStarted: true
,W/ContextImpl( 6390): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1888 android.content.ContextWrapper.bindService:538 android.bluetooth.BluetoothSap.doBind:108 android.bluetooth.BluetoothSap.<init>:101 android.bluetooth.BluetoothAdapter.getProfileProxy:1423 
D/WifiService(  959): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=emergency
,D/wpa_supplicant( 1351): nl80211: Remove monitor interface: refcount=0,
D/wpa_supplicant( 1351): netlink: Operstate: ifindex=29 linkmode=0 (kernel-control), operstate=6 (IF_OPER_UP)
E/BluetoothFtpService:RfcommSocketAcceptThread( 3098): Shutdown
,D/BluetoothMasReceiver( 3098): Bluetooth STATE CHANGED to 13
,D/BluetoothPbap( 6390): BluetoothPbap()
D/WifiService(  959): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=verizon800
,D/BluetoothManagerService(  959): registerStateChangeCallback+
D/BluetoothManagerService(  959): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  959): Registered receivers: 13
V/BluetoothSapReceiver( 3098): SapReceiver onReceive 
V/BluetoothSapReceiver( 3098): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 3098):  Bluetooth Adapter state = 13
V/BluetoothSapReceiver( 3098): startService = false
I/bt-btif ( 3098): HAL bt_hal_cbacks->adapter_state_changed_cb
D/LocalBluetoothProfileManager( 6390): LocalBluetoothProfileManager construction complete
D/BluetoothAdapterState( 3098): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterService( 3098): mProfilesStarted : true supportedProfileServices.length : 6
,D/HtcWiFiWidget_WiFiWidgetProvider( 7244): onWiFiStateChanged() for widget: 
D/AuthorizationBluetoothService( 1936): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/HtcWiFiWidget_WiFiWidgetProvider( 7244): updateWidget(context) for widget: 
,D/HeadsetService( 3098): Received stop request...Stopping profile...,
D/WifiService(  959): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=hipri
,I/ActivityManager(  959): Killing 6819:com.htc.mobiledata:remote/u0a46 (adj 15): empty #17
D/Process (  959): killProcessQuiet, pid=6819
,D/Process (  959): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,D/wpa_supplicant( 1351): nl80211: Set mode ifindex 29 iftype 2 (STATION)
D/wpa_supplicant( 1351): nl80211: Unsubscribe mgmt frames handle 0x888888ddf97d1989 (mode change)
I/wpa_supplicant( 1351): htc_wext_command_deinit +
I/wpa_supplicant( 1351): htc_wext_command_deinit -
I/wpa_supplicant( 1351): wlan0: CTRL-EVENT-TERMINATING 
,D/WifiMonitor(  959): Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
E/WifiMonitor(  959): WifiMonitor:wlan0 cnt=57 dispatchEvent: CTRL-EVENT-TERMINATING 
D/Tethering(  959): interfaceLinkStateChanged wlan0, false
D/Tethering(  959): interfaceStatusChanged wlan0, false
D/WifiMonitor(  959): Disconnecting from the supplicant, no more events
E/WifiStateMachine(  959): handleMessage: E msg.what=147458
E/WifiStateMachine(  959): WiFiDisplay: getWifidisplayApEnabled=false
,E/WifiStateMachine(  959): processMsg: SupplicantStoppingState
E/WifiStateMachine(  959):  SupplicantStoppingState SUP_DISCONNECTION_EVENT 57 0
E/WifiStateMachine(  959): Supplicant connection lost
,I/ActivityManager(  959): Recipient 6819
,D/BluetoothAdapterService( 3098): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@20f8f778,
D/HeadsetStateMachine( 3098): Exit Disconnected: -1
W/ActivityManager(  959): Application dead when creating service ServiceRecord{1e15263c u0 com.htc.mobiledata/.MobileDataService}
D/DockEventReceiver( 6390): finishStartingService: stopping service
W/ActivityManager(  959): Scheduling restart of crashed service com.htc.mobiledata/.MobileDataService in 1000ms
D/BluetoothInputDevice( 6390): Proxy object connected
,W/ActivityManager(  959): Scheduling restart of crashed service com.htc.mobiledata/.MobileDataService in 4000ms,
,W/ActivityManager(  959): Spurious death for ProcessRecord{f0fbfc5 0:com.htc.mobiledata:remote/u0a46}, curProc for 6819: null
D/BluetoothAdapterState( 3098): Stopping profile services that were post enabled
D/BluetoothHeadset(  959): Proxy object disconnected
,D/BluetoothHeadset( 1218): Proxy object disconnected
I/QuickSettingMiniLite( 1218): btListener.disconnect:HEADSET
D/HidProfile( 6390): Bluetooth service connected
D/BluetoothHeadset( 3714): Proxy object disconnected
D/A2dpService( 3098): Received stop request...Stopping profile...
D/NGFService( 3714): BluetoothHeadset onServiceDisconnected: main
D/A2dpStateMachine( 3098): Exit Disconnected: -1
,D/BluetoothAdapterService( 3098): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@20f8f778
D/BluetoothAdapter( 6390): 98432338: getState(). Returning 13
,D/BluetoothPan( 6390): BluetoothPAN Proxy object connected,
,D/PanProfile( 6390): Bluetooth service connected
,D/SapServerProfile( 6390): Bluetooth service connected
D/PMS     (  959): releaseWL(15e20612): PARTIAL_WAKE_LOCK  StartingDockService 0x1 null
,I/ActivityManager(  959): Start proc com.htc.mobiledata:remote for service com.htc.mobiledata/.MobileDataService: pid=7313 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a
,D/BluetoothA2dp(  959): Proxy object disconnected
D/WifiService(  959): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=ims
,D/BluetoothA2dp( 3714): Proxy object disconnected
,D/NGFService( 3714): BluetoothA2dp onServiceDisconnected: main
D/HidService( 3098): Received stop request...Stopping profile...
D/BluetoothAdapterService( 3098): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@20f8f778
D/BluetoothInputDevice( 6390): Proxy object disconnected
D/HidProfile( 6390): Bluetooth service disconnected
D/HealthService( 3098): Received stop request...Stopping profile...
,D/BluetoothAdapterService( 3098): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@20f8f778
,D/WifiService(  959): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=default
,D/FlexNetS( 6797): updateSvcAllowedInSettings:false
D/PanService( 3098): Received stop request...Stopping profile...
D/BluetoothAdapterService( 3098): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@20f8f778
,D/WifiService(  959): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=mms
,D/BluetoothPan( 6390): BluetoothPAN Proxy object disconnected
D/PanProfile( 6390): Bluetooth service disconnected
,D/BtGatt.DebugUtils( 3098): handleDebugAction() action=null
D/BtGatt.GattService( 3098): Received stop request...Stopping profile...
D/BtGatt.GattService( 3098): stop()
D/BtGatt.AdvertiseManager( 3098): advertise clients cleared
,D/BluetoothAdapterService( 3098): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@20f8f778
D/TetherSettings( 6390): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 6390): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 6390): Cust_ConnectToPC   : Modem_Link>false
D/        ( 6390): Cust_ConnectToPC   : spcsc>false
D/        ( 6390): Cust_ConnectToPC   : IPT>true
D/        ( 6390): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 6390): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/SmartNS_Utility( 6390): hasRemovableStorageSlot: true
D/SmartNS_Utility( 6390): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 6390): onReceive : android.net.conn.TETHER_STATE_CHANGED hasTethered:false isNSOpening:false
,W/BluetoothHeadsetServiceJni( 3098): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 3098): Cleaning up Bluetooth Handsfree callback object
E/WifiStateMachine(  959): WiFiDisplay: getWifidisplayApEnabled=false
,W/BluetoothHidServiceJni( 3098): Cleaning up Bluetooth HID Interface...
W/BluetoothHidServiceJni( 3098): Cleaning up Bluetooth GID callback object
W/BluetoothHealthServiceJni( 3098): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 3098): Cleaning up Bluetooth Health object
W/ContextImpl( 6390): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.NSReceiver.onReceive:432 android.app.ActivityThread.handleReceiver:2712 
W/BluetoothPanServiceJni( 3098): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 3098): Cleaning up Bluetooth PAN callback object
,D/BluetoothAdapterState( 3098): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 3098): Setting state to 10
I/BluetoothAdapterState( 3098): Bluetooth adapter state changed: 13-> 10
D/BluetoothManagerService(  959): +onBluetoothStateChange prev=13 new=10
I/BluetoothAdapterState( 3098): Entering OffState
I/SmartNS_Utility( 6390): setISNotification
,D/BluetoothManagerService(  959): Message: MESSAGE_BLUETOOTH_STATE_CHANGE
D/BluetoothManagerService(  959): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
D/BluetoothManagerService(  959): Broadcasting onBluetoothStateChange(false) to 13 receivers.
D/BluetoothPan( 6390): onBluetoothStateChange on: false
W/BluetoothHeadset( 1218): Proxy not attached to service
I/QuickSettingMiniLite( 1218): updateLiteState:no connect device!
D/SmartNS_Utility( 6390): usb_cable_connect = 1
D/SmartNS_Utility( 6390): usb_denied = 0
I/SmartNS_PSService( 6390): usb notificaiton:true
E/WifiStateMachine(  959): WiFiDisplay: getWifidisplayApEnabled=false
,D/WifiService(  959): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=cbs
,D/BluetoothA2dp( 3714): onBluetoothStateChange: up=false
,D/BluetoothA2dp(  959): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1218): onBluetoothStateChange: up=false
,D/WifiService(  959): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=ia
,D/BluetoothPbap( 6390): onBluetoothStateChange: up=false
,D/SmartNS_Utility( 6390): usb_cable_connect = 1
D/WifiService(  959): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=dun
D/DotMatrix( 1304): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
D/SmartNS_Utility( 6390): usb_denied = 0
I/SmartNS_PSService( 6390): usb notificaiton:true
D/BluetoothInputDevice( 6390): onBluetoothStateChange: up=false
E/WifiStateMachine(  959): WiFiDisplay: getWifidisplayApEnabled=false
I/RemoteViews( 1218): reapply : com.android.settings 1 36
D/BluetoothHeadset( 1495): onBluetoothStateChange: up=false
,D/BluetoothMap( 6390): onBluetoothStateChange: up=false
,E/BluetoothMap( 6390): 
E/BluetoothMap( 6390): java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothMap$2@1d13f09b
E/BluetoothMap( 6390): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1135)
E/BluetoothMap( 6390): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1940)
E/BluetoothMap( 6390): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
E/BluetoothMap( 6390): 	at android.bluetooth.BluetoothMap$1.onBluetoothStateChange(BluetoothMap.java:64)
E/BluetoothMap( 6390): 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
E/BluetoothMap( 6390): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothHeadset(  959): onBluetoothStateChange: up=false
D/BluetoothSap( 6390): onBluetoothStateChange on: false
V/BluetoothSapService( 3098): cleanup: mService: com.android.bluetooth.sap.BluetoothSapService@2bb745b4
,D/BluetoothHeadset( 1495): onBluetoothStateChange: up=false
,D/BluetoothHeadset( 1495): Proxy object disconnected
D/WifiService(  959): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=internet
D/BluetoothPhoneService( 1495): BluetoothHeadset onServiceDisconnected
D/SmartNS_NSReceiver( 6390): Tethered state change:false isNSOpening:false
,D/BluetoothHeadset( 3714): onBluetoothStateChange: up=false
,D/BluetoothHeadset( 1495): onBluetoothStateChange: up=false
D/DotMatrix( 1304): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
D/Process (  959): killProcessQuiet, pid=6736
I/ActivityManager(  959): Killing 6736:com.google.android.setupwizard/u0a77 (adj 15): empty #17
D/Process (  959): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.removeContentProvider:10141 
,I/RemoteViews( 1218): reapply : com.android.settings 1 36
,D/FlexNetS( 6797): updateSvcAllowedInSettings:false
,I/ActivityManager(  959): Recipient 6736,
,I/wpa_ctrl(  959): [wpa_ctrl_close] ctrl=0x557af37260
,I/wpa_ctrl(  959): [wpa_ctrl_close] ctrl=0x557af37410
,D/BluetoothManagerService(  959): Calling onBluetoothServiceDown callbacks
,D/BluetoothManagerService(  959): Broadcasting onBluetoothServiceDown() to 10 receivers.
D/BluetoothAdapter( 6390): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@27aedc38,
D/BluetoothAdapter( 6390): onBluetoothServiceDown: done
D/BluetoothAdapter( 1495): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@1502316
D/BluetoothAdapter( 1495): onBluetoothServiceDown: done
D/BluetoothAdapter( 2388): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@3256b5eb
D/BluetoothAdapter( 2388): onBluetoothServiceDown: done
,D/BluetoothAdapter( 3098): onBluetoothServiceDown: com.android.bluetooth.btservice.AdapterService$AdapterServiceBinder@26821324
D/BluetoothAdapter( 3098): onBluetoothServiceDown: done
D/BluetoothAdapter( 1218): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@30412559
D/BluetoothAdapter( 1218): onBluetoothServiceDown: done
,D/BluetoothAdapter( 6676): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@356964af
D/BluetoothAdapter( 6676): onBluetoothServiceDown: done
E/WifiStateMachine(  959): setWifiState: disabled
,D/BluetoothAdapter( 1520): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@34a2a2bc
D/BluetoothAdapter( 1520): onBluetoothServiceDown: done,
W/Settings( 6333): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/BluetoothAdapter( 3714): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@12bdf4fd
D/BluetoothAdapter( 3714): onBluetoothServiceDown: done
,D/BluetoothAdapter( 1814): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@1bb30ea3
,D/BluetoothAdapter( 1814): onBluetoothServiceDown: done
D/BluetoothAdapter(  959): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@2fdf3746,
D/BluetoothAdapter(  959): onBluetoothServiceDown: done
D/WIFI_ICON( 1218): updateWifiState: WIFI_STATE_CHANGED disabled
,D/BluetoothManagerService(  959): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@2fdf3746 mBinding = false
D/StatusBar.NetworkController( 1218): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiStateMachine(  959): Enter handleNetworkDisconnect
D/BluetoothManagerService(  959): Sending unbind request.
E/WifiStateMachine(  959): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - handleNetworkDisconnect - access$12300 - processMessage
D/MdProvGlob( 7286): add item 101 (2:g3d8) for 15:android.intent.action.PRECISE_DATA_CONNECTION_STATE_CHANGED
E/WifiStateMachine(  959): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  959): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
I/IntentController( 1218): receive(android.net.wifi.WIFI_STATE_CHANGED,1,false)
D/BluetoothManagerService(  959): Bluetooth State Change Intent: 13 -> 10
,W/Settings( 1814): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiStateMachine(  959): Exit handleNetworkDisconnect
E/WifiStateMachine(  959): [MLHD] Error! unhandled message 6 { when=-493ms what=147458 arg1=57 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  959): transitionTo: destState=InitialState
E/WifiStateMachine(  959): handleMessage: new destination call exit/enter
D/PMS     (  959): acquireWL(d80dd1a): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 959 1000 null
E/WifiStateMachine(  959): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=DefaultState,active=true,parent=null
E/WifiStateMachine(  959): invokeExitMethods: SupplicantStoppingState
E/WifiStateMachine(  959): moveTempStackToStateStack: i=0,j=1
E/WifiStateMachine(  959): moveTempStackToStateStack: X mStateStackTop=1,startingIndex=1,Top=InitialState
E/WifiStateMachine(  959): invokeEnterMethods: InitialState
,D/NfcHandover( 1520): onReceive: mBound=false, BTByNfc=false->false, BTHConnected=false->false
I/IntentController( 1218): receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
,E/WifiTrafficPoller(  959): ENABLE_TRAFFIC_STATS_POLL false Token 30
I/bt-btif ( 3098): HAL bt_hal_cbacks->thread_evt_cb
D/NGFService( 3714): Receiver: action = android.bluetooth.adapter.action.STATE_CHANGED
D/NGFService( 3714): Bluetooth Adapter: OFF,
I/IntentController( 1218): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WIFI_ICON( 1218): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/LocalBluetoothProfileManager( 6390): setBluetoothStateOff
,D/StatusBar.NetworkController( 1218): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
W/BluetoothEventManager( 6390): unregister mProfileBroadcastReceiver fail
I/art     ( 3098): System.exit called, status: 0,
,D/FlexNetS( 6797): updateSvcAllowedInSettings:false
,D/FlexNetS( 6797): updateSvcAllowedInSettings:false
I/QuickSettingWifi( 1218): receive.wifiState:WIFI_STATE_DISABLED setEnable:true
D/TetherPref( 6390): persistRestoreBluetoothState false,
,D/FlexNetS( 6797): updateSvcAllowedInSettings:false
,D/MdScPhnSt( 7313): [9de.2.]  listen tmrbb8
D/WISPrService( 6390): >>>>>WISPrService start isConnected = false<<<<<
,D/BluetoothAdapter( 1218): 958086984: getState() :  mService = null. Returning STATE_OFF
,D/WISPrService( 6390): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
I/QuickSettingBluetooth( 1218): receive.ACTION_STATE_CHANGE:STATE_OFF/(false,false)
,I/QuickSettingWifi( 1218): receive.wifiConnect:false wifiAPname:null elapse:1
,D/FlexNetS( 6797): updateSvcAllowedInSettings:false
,D/FlexNetS( 6797): updateSvcAllowedInSettings:false
,D/FlexNetS( 6797): updateSvcAllowedInSettings:false
,I/ActivityManager(  959): Recipient 3098
I/ActivityManager(  959): Process com.android.bluetooth (pid 3098) has died
W/ActivityManager(  959): Scheduling restart of crashed service com.android.bluetooth/.sap.BluetoothSapService in 1000ms
W/ActivityManager(  959): Scheduling restart of crashed service com.android.bluetooth/.map.BluetoothMasService in 1000ms
,I/BroadcastQueue(  959): Schedule to resend BroadcastRecord{2ee89627 u-1 android.bluetooth.adapter.action.STATE_CHANGED callingPid=959 callingUid=1000} for ResolveInfo{1ff200d4 com.android.bluetooth/.pbap.BluetoothPbapReceiver m=0x108000} of com.android.bluetooth
,D/FlexNetS( 6797): updateSvcAllowedInSettings:false
,I/ActivityManager(  959): Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=7344 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 1023, 3005, 1016, 3008} abi=armeabi-v7a,
,D/FlexNetS( 6797): updateSvcAllowedInSettings:false
,D/FlexNetS( 6797): updateSvcAllowedInSettings:false
,D/MdProvGlob( 7286): remove item 101 (p3d10in190) for 15:android.intent.action.ANY_DATA_STATE
D/MdScDataSum( 7313): [9de.2.] summary 118:p3 ignore
,D/FlexNetS( 6797): updateSvcAllowedInSettings:false
,D/MdProvGlob( 7286): remove item 101 (p3in10) for 15:android.intent.action.ANY_DATA_STATE,
,D/FlexNetS( 6797): updateSvcAllowedInSettings:false
,D/MdProvGlob( 7286): remove item 101 (p3in21) for 15:android.intent.action.ANY_DATA_STATE
W/ResourcesManager( 7344): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,D/FlexNetS( 6797): updateSvcAllowedInSettings:false
,D/MdProvGlob( 7286): remove item 101 (p3in15) for 15:android.intent.action.ANY_DATA_STATE
,D/FlexNetS( 6797): updateSvcAllowedInSettings:false,
,D/MdProvGlob( 7286): remove item 101 (p3in16) for 15:android.intent.action.ANY_DATA_STATE
,D/HtcWiFiWidget_WiFiWidgetProvider( 7244): onWiFiStateChanged() for widget: 
,D/HtcWiFiWidget_WiFiWidgetProvider( 7244): updateWidget(context) for widget: 
,D/MdProvGlob( 7286): remove item 101 (p3d1in20) for 15:android.intent.action.ANY_DATA_STATE
,D/MdProvGlob( 7286): remove item 101 (p3in13) for 15:android.intent.action.ANY_DATA_STATE,
,D/AdapterServiceConfig( 7344): Adding HeadsetService
D/AdapterServiceConfig( 7344): Adding A2dpService
D/AdapterServiceConfig( 7344): Adding HidService
D/AdapterServiceConfig( 7344): Adding HealthService
D/AdapterServiceConfig( 7344): Adding PanService
D/AdapterServiceConfig( 7344): Adding GattService
V/BluetoothPbapReceiver( 7344): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 7344): ***********state = 10
,E/BluetoothMasService( 7344): BluetoothMasObexConnectionManager: mIsEmailEnabled: true
D/PMS     (  959): acquireWL(e43227d): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 6390 1000 null
W/ContextImpl( 6390): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:141 com.android.settings.bluetooth.DockEventReceiver.onReceive:121 
,D/BluetoothMasService( 7344): Add permission for SmsProvider.,
D/PMS     (  959): releaseWL(e43227d): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 null
,D/HtcBtWidget_BTWidgetProvider( 7264): onBTStateChanged() for widget: 
D/HtcBtWidget_BTWidgetProvider( 7264): updateWidget(context) for widget: 
D/PMS     (  959): acquireWL(1d3e6dc3): PARTIAL_WAKE_LOCK  StartingDockService 0x1 6390 1000 null
D/MdProvGlob( 7286): remove item 101 (p3d1in21) for 15:android.intent.action.ANY_DATA_STATE
,D/DockEventReceiver( 6390): finishStartingService: stopping service
,D/PMS     (  959): releaseWL(1d3e6dc3): PARTIAL_WAKE_LOCK  StartingDockService 0x1 null
,D/BluetoothManagerService(  959): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  959): java.lang.Throwable: stack dump
W/System.err(  959): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  959): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  959): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  959): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothManagerService(  959): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1be46979:true,
V/BluetoothMasService( 7344): Starting MAS instances
D/BluetoothAdapter( 7344): 908859327: getState() :  mService = null. Returning STATE_OFF
,I/MailMessageReceiver( 7344): reg:com.android.bluetooth.btservice.AdapterApp@1cbc7e8c with com.htc.lib1.HtcMailLibFramework.MailMessageReceiver@1718b9d5
I/MailManager( 7344): MailManager contruct! com.htc.lib1.HtcMailLibFramework.MailMessageReceiver@1718b9d5
V/EmailUtils( 7344): Manager Instance is not NULL
,I/ActivityManager(  959): Start proc com.htc.android.mail:sync for content provider com.htc.android.mail/.MailProvider: pid=7366 uid=10062 gids={50062, 9997, 3003, 1023, 1028, 1015} abi=armeabi-v7a
,D/Process (  959): killProcessQuiet, pid=6956
I/ActivityManager(  959): Killing 6956:com.google.android.apps.magazines/u0a161 (adj 15): empty #17
,D/Process (  959): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.removeContentProvider:10141 
,I/ActivityManager(  959): Recipient 6956
,D/Process (  959): killProcessQuiet, pid=7040
I/ActivityManager(  959): Killing 7040:com.android.chrome/u0a96 (adj 15): empty #17,
D/Process (  959): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  959): Recipient 7040,
,D/HtcAdjCursorFactory( 7366): Set CursorWindow size to: 4194304 KB, Tid: 7387,
,D/Tethering(  959): interfaceRemoved wlan0
E/Tethering(  959): attempting to remove unknown iface (wlan0), ignoring
,D/EmailUtils( 7344): ============NULL aList========,
,V/EmailUtils( 7344): <-getEmailAccountIdList
V/BluetoothMasService( 7344): onCreate: mIsEmailEnabled: true
,I/ActivityManager(  959): Killing 6006:com.android.vending/u0a72 (adj 15): empty #17
D/Process (  959): killProcessQuiet, pid=6006
D/Process (  959): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.removeContentProvider:10141 
D/Tethering(  959): interfaceLinkStateChanged p2p0, false
D/Tethering(  959): interfaceStatusChanged p2p0, false
E/WifiStateMachine(  959): WiFiDisplay: getWifidisplayApEnabled=false
,D/Tethering(  959): interfaceRemoved p2p0
E/Tethering(  959): attempting to remove unknown iface (p2p0), ignoring
,I/ActivityManager(  959): Recipient 6006
,D/BluetoothMasReceiver( 7344): Bluetooth STATE CHANGED to 10
,V/BluetoothMasService( 7344): onDestroy: mIsEmailEnabled: true
,V/BluetoothSapReceiver( 7344): SapReceiver onReceive 
,V/BluetoothSapReceiver( 7344): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 7344):  Bluetooth Adapter state = 10
V/BluetoothSapReceiver( 7344): startService = false
,D/Process (  959): killProcessQuiet, pid=7138
,I/ActivityManager(  959): Killing 7138:com.google.android.partnersetup/u0a27 (adj 15): empty #17
D/Process (  959): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,I/ActivityManager(  959): Recipient 7138
,D/AuthorizationBluetoothService( 1936): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/PMS     (  959): releaseWL(d80dd1a): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
E/WifiStateMachine(  959): handleMessage: X
,D/ConnectivityService(  959): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/AlarmManager(  959): [AlarmQueuing] connectivity wifi: false
,D/GpsLocationProvider(  959): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/PMS     (  959): acquireWL(18dac0ca): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 959 1000 null
D/GpsLocationProvider(  959): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  959): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/htcCheckinService(  959): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
D/htcCheckinService(  959): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
,I/ConnectivityHelper( 1547): [onReceive] WIFI(1): DISCONNECTED
V/MusicLeanback( 6913): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,E/GpsLocationProvider(  959): No APN found to select.
,D/PMS     (  959): releaseWL(18dac0ca): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/AutoSetting( 1600): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/AutoSetting( 1600): Util - no network available!
,I/ActivityManager(  959): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7396 uid=10077 gids={50077, 9997, 3003} abi=arm64-v8a
D/MdScPhnSt( 7313): [75.1.]  listen tmrbb8
,D/AutoSetting( 1600): service - onCreate()
D/AutoSetting( 1600): service - onStartCommand() action: com.htc.app.autosetting.cancellocationupdate
,D/LocationManagerService(  959): request 115c144a passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10052)
D/LocationManagerService(  959): provider request: passive ProviderRequest[ON interval=0]
,D/AutoSetting( 1600): service - mHandler: cancel location update
D/AutoSetting( 1600): service -           changes count: 0
,I/art     (  425): Explicit concurrent mark sweep GC freed 8631(366KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 218us total 35.946ms
,D/MdScDataSum( 7313): [75.1.] summary 118:p1 ignore,
,I/art     (  425): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 196us total 27.519ms,
,D/PhoneMonitor( 7396): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 7396): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) },
,D/MobileConnectivityChangeReceiver( 7396): onReceive CONNECTIVITY_CHANGE networkType=1,
I/art     (  425): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 171us total 22.396ms
,D/PhoneMonitor( 7396): onServiceStateChanged state="3 3 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1EriInd= -1EriMode= -1RadioPowerSv: false EmergOnly=false PhoneType: 1 VoiceRoaming: false DataRoaming: false IMSRegState: -1" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_POWER_OFF(3) D:STATE_POWER_OFF(3) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false,
,D/PhoneMonitor( 7396): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_POWER_OFF(3) D:STATE_POWER_OFF(3) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,I/iu.Environment( 4431): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*,
,I/iu.UploadsManager( 4431): num queued entries: 0
,I/iu.UploadsManager( 4431): num updated entries: 0
,I/iu.SyncManager( 4431): NEXT; no task
,D/ChimeraCfgMgr( 4431): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/Kids    ( 4431): [GCoreUtils] Current gmscore version, 7899448 is smaller than the required version 8400000
,I/Babel   ( 6333): connection state changed from CONNECTED to DISCONNECTED
,I/ActivityManager(  959): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7425 uid=10161 gids={50161, 9997, 3003, 1028, 1015} abi=arm64-v8a
,D/VoldConnector(  959): SND -> {39 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/},
E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/
W/ContextImpl( 7425): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,D/VoldConnector(  959): SND -> {40 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/}
,I/GAv4    ( 7425): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7425):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7425):   adb logcat -s GAv4
E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/
,W/ContextImpl( 7425): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,D/VoldConnector(  959): SND -> {41 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/}
E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/
,W/ContextImpl( 7425): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,D/VoldConnector(  959): SND -> {42 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/}
E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/
,W/ContextImpl( 7425): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/GAv4    ( 7425): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7425): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.,
,W/GAv4    ( 7425): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.,
,W/global  ( 7425): [apache-http] Connection GC has been deprecated!
,W/global  ( 7425): [apache-http] Connection GC has been deprecated!,
,I/WebViewFactory( 7425): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
,I/LibraryLoader( 7425): Time to load native libraries: 2 ms (timestamps 2933-2935),
I/LibraryLoader( 7425): Expected native library version number "",actual native library version number "",
,V/WebViewChromiumFactoryProvider( 7425): Binding Chromium to main looper Looper (main, tid 1) {1624d2d9},
,I/LibraryLoader( 7425): Expected native library version number "",actual native library version number ""
,I/chromium( 7425): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0,
,I/BrowserStartupController( 7425): Initializing chromium process, singleProcess=true,
,W/art     ( 7425): Attempt to remove local handle scope entry from IRT, ignoring,
,E/SysUtils( 7425): ApplicationContext is null in ApplicationStatus,
,W/chromium( 7425): [WARNING:resource_bundle.cc(285)] locale_file_path.empty(),
,E/libEGL  ( 7425): validate_display:255 error 3008 (EGL_BAD_DISPLAY),
E/libEGL  ( 7425): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 7425): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 7425): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 7425): Build Date: 03/09/15 Mon
I/Adreno-EGL( 7425): Local Branch: 
I/Adreno-EGL( 7425): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 7425): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 7425):                  d74aa161a12b9c6fc6332151
,W/AudioManagerAndroid( 7425): Requires BLUETOOTH permission,
,I/NSApplication( 7425): Starting up...,
,D/Process (  959): killProcessQuiet, pid=7067,
I/ActivityManager(  959): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7484 uid=10096 gids={50096, 9997, 3003, 1028, 1015} abi=arm64-v8a
D/Process (  959): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,I/ActivityManager(  959): Killing 7067:com.google.android.apps.plus/u0a167 (adj 15): empty #17
,I/ActivityManager(  959): Recipient 7067
,I/ActivityManager(  959): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7507 uid=10167 gids={50167, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  959): Killing 7106:com.google.android.googlequicksearchbox:search/u0a85 (adj 15): empty #17
,D/Process (  959): killProcessQuiet, pid=7106
D/Process (  959): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,I/ActivityManager(  959): Recipient 7106
,W/ResourcesManager( 7507): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/PMS     (  959): acquireWL(3cecb00b): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 959 1000 WorkSource{1000},
,V/AlarmManager(  959): sending alarm PendingIntent{c09772c: PendingIntentRecord{1a5f55f5 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=229656, Int=0
V/AlarmManager(  959): sending alarm PendingIntent{1ec7ee8: PendingIntentRecord{3ddecbdb com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=273778, Int=0,
,D/WeatherUtility( 1218): Weather sync is On
W/WeatherTimeKeeper( 1218): [refreshWeatherData] no weather data
,D/Process (  959): killProcessQuiet, pid=5177,
I/ActivityManager(  959): Killing 5177:com.google.android.gms.wearable/u0a24 (adj 15): empty #17
D/Process (  959): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,I/ActivityManager(  959): Recipient 5177
,D/PMS     (  959): acquireWL(337ea194): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1936 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  959): releaseWL(3cecb00b): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{10024}
,D/libc    ( 1936): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
D/libc    ( 1936): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1936): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    ( 1936): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1936): [NET] android_getaddrinfo_proxy+
D/libc    ( 1936): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  395): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    (  395): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  395): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  395): [NET] android_getaddrinfofornet-, err=7
,D/libc    ( 1936): [NET] android_getaddrinfo_proxy-, NODATA
,D/PMS     (  959): releaseWL(337ea194): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,D/WifiP2pService(  959): P2pDisabledState{ when=-5ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler },
D/WifiP2pService(  959): DefaultState{ when=-6ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine(  959): handleMessage: E msg.what=131089,
E/WifiStateMachine(  959): processMsg: InitialState
E/WifiStateMachine(  959):  InitialState CMD_STOP_SUPPLICANT_FAILED 1 0
E/WifiStateMachine(  959): processMsg: DefaultState
E/WifiStateMachine(  959):  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
,E/WifiStateMachine(  959): handleMessage: X
,W/Atfwd_Sendcmd(  473): AtCmdFwd service not published, waiting... retryCnt : 4
,I/ActivityManager(  959): Waited long enough for: ServiceRecord{2d0d5717 u0 com.htc.sense.hsp/.weather.location.AutoSettingService},

```
