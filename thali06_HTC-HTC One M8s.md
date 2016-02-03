#### Test 57924002a578a80_thali06_HTC-HTC One M8s Logs


```
--------- beginning of main
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  405): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  405): OEMCrypto_SupportsUsageTable: starts!
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  405): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  405): OEMCrypto_SupportsUsageTable: wv_app_version = 24
D/DrmWidevineDash(  405): OEMCrypto_SupportsUsageTable: ends! returns 0
D/DrmWidevineDash(  405): OEMCrypto_GetHDCPCapability: starts!, current = 0xf463c70e, maximum = 0xf463c70f
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  405): OEMCrypto_GetHDCPCapability: ends! returns 0
D/DrmWidevineDash(  405): OEMCrypto_APIVersion: starts!
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  405): hlos api version =  9
D/DrmWidevineDash(  405): tz api version =  9
D/DrmWidevineDash(  405): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  405): OEMCrypto_GenerateNonce: starts! SID=1, nonce=0xf463c77c
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  405): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  405): PrepareKeyRequest: nonce=274975491
D/DrmWidevineDash(  405): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xaaf07800
D/DrmWidevineDash(  405): message_length=1611, signature=0xaaf071a0, signature_length=0xf463c6dc
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
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
E/cutils-trace( 6405): Error opening trace file: Permission denied (13)
I/dex2oat ( 6405): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm64 --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=36 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
I/dex2oat ( 6405): dex2oat: override thread count:4
I/dex2oat ( 6405): dex2oat took 37.381ms (threads: 4)
I/Adreno-EGL( 6369): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 6369): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6369): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6369): Local Branch: 
I/Adreno-EGL( 6369): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6369): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6369):                  d74aa161a12b9c6fc6332151
I/Adreno-EGL( 6369): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 6369): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6369): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6369): Local Branch: 
I/Adreno-EGL( 6369): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6369): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6369):                  d74aa161a12b9c6fc6332151
E/cutils-trace( 6402): Error opening trace file: Permission denied (13)
E/WifiTrafficPoller(  977): TRAFFIC_STATS_POLL true Token 11 num clients 6
D/CustomizationManager( 6402): ====startRecUseTime====
--------- beginning of system
D/WIFI_ICON( 1218): WifiActivity: 0
D/htc.customization.log.level( 6402):  is 
D/StatusBar.NetworkController( 1218): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
W/CustomizationLogLevel( 6402): Level value is invalid, use default level 2
E/WifiTrafficPoller(  977):  packet count Tx=184 Rx=289
E/WifiTrafficPoller(  977): notifying of data activity 0
D/CustomizationManager( 6402):  Read ACC file spent 0.049 (s)
D/CIDMapFileReader( 6402): Parsing tag item name = HTC__001
D/CIDMapFileReader( 6402): Parsing tag item name = HTC__102
D/CIDMapFileReader( 6402): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 6402): Parsing tag item name = HTC__032
D/CIDMapFileReader( 6402): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 6402): Parsing tag item name = HTC__002
D/CIDMapFileReader( 6402): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 6402): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 6402): Parsing tag category name = system
I/CustomizationCIDLoader( 6402): Parsing tag category name = application
I/CustomizationCIDLoader( 6402): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 6402): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 6402): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 6402): Parsing tag category name = Settings
I/CustomizationCIDLoader( 6402): Parsing tag category name = ACC
I/CustomizationCIDLoader( 6402): add string-array item, value = 42507
I/CustomizationCIDLoader( 6402): add string-array item, value = 21902
I/CustomizationCIDLoader( 6402): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 6402): add string-array item, value = 23420
I/CustomizationCIDLoader( 6402): add string-array item, value = 22299
I/CustomizationCIDLoader( 6402): add string-array item, value = 24002
I/CustomizationCIDLoader( 6402): add string-array item, value = 23210
I/CustomizationCIDLoader( 6402): add string-array item, value = 23205
I/CustomizationCIDLoader( 6402): add string-array item, value = 23806
I/CustomizationCIDLoader( 6402): add string-array item, value = 23430
I/CustomizationCIDLoader( 6402): add string-array item, value = 23408
I/CustomizationCIDLoader( 6402): add string-array item, value = 27205
I/CustomizationCIDLoader( 6402): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 6402): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 6402): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 6402): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 6402): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 6402): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 6402): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 6402): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 6402): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 6402): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 6402): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 6402): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 6402):  Read CID file spent 0.090 (s)
D/CustomizationManager( 6402):  All configurations done spent 0.090 (s)
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
D/DrmWidevineDash(  405): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf4510000
E/DrmWidevineDash(  405): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf4510000
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
I/ActivityManager(  977): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 pid 6402 on display 0
D/DrmLibTime(  560): got the req here! ret=0
D/PMS     (  977): acquireHCC(169b7d4): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 977 1000 null
D/DrmLibTime(  560): command id, time_cmd_id = 770
D/DrmLibTime(  560): time_getutcsec starts!
D/DrmLibTime(  560): QSEE Time Listener: time_getutcsec
D/DrmLibTime(  560): QSEE Time Listener: get_utc_seconds
D/PMS     (  977): acquireHCC(11fe0d7d): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 977 1000 null
D/DrmLibTime(  560): QSEE Time Listener: time_get_modem_time
D/DrmLibTime(  560): QSEE Time Listener: Checking if ATS_MODEM is set or not.
E/QC-time-services(  560): Receive Passed == base = 13, unit = 1, operation = 2, result = 0
D/DrmLibTime(  560): QSEE Time Listener: ATS_MODEM is not set. Fallback to Android system time.
D/DrmLibTime(  560): QSEE Time Listener: Retrieved Android system time: 1454460141
D/DrmLibTime(  560): time_getutcsec returns 0, sec = 1454460141; nsec = 0
D/DrmLibTime(  560): time_getutcsec finished! 
D/DrmLibTime(  560): iotcl_continue_command finished! and return 0 
D/DrmLibTime(  560): before calling ioctl to read the next time_cmd
E/QC-time-services(  464): Daemon: Time-services: Waiting to acceptconnection
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
D/PMS     (  977): acquireWL(7947d40): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 977 1000 null
I/AnimationUtil(  977): isHTCRecent(ThaliTest/Recent screens.)/7
I/FeedHostManager( 1587): [onPause]
I/FeedProviderManager( 1587): onPause
I/FeedHostManager( 1587): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@14f65c4
I/SocialFeedProvider( 1587): +onPause
I/SocialFeedProvider( 1587): -onPause
W/HtcSystemUPManager(  977): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  405): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  405): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  405): OEMCrypto_OpenSession: starts! SID=0xf483c928
D/DrmWidevineDash(  405): OEMCrypto_OpenSession Session ID = 0
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  405): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  405): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  405): OEMCrypto_GetRandom: starts! randomData=0xaaf13920, dataLength=8
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  405): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  405): OEMCrypto_LoadDeviceRSAKey: starts! SID=1, wrapped_rsa_key=0xaaf2dc90, wrapped_rsa_key_length=1280
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  405): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  405): CdmEngine::QueryKeyControlInfo
W/WVCdm   (  405): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  405): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  405): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  405): OEMCrypto_GetDeviceID: starts! deviceID=0xab0258e8, idLength=0xf473c6f8
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
I/ActivityManager(  977): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6431 uid=10366 gids={50366, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/art     (  432): Explicit concurrent mark sweep GC freed 8668(369KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 348us total 19.562ms
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  405): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  405): OEMCrypto_SupportsUsageTable: starts!
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  405): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  405): OEMCrypto_SupportsUsageTable: wv_app_version = 24
D/DrmWidevineDash(  405): OEMCrypto_SupportsUsageTable: ends! returns 0
D/DrmWidevineDash(  405): OEMCrypto_GetHDCPCapability: starts!, current = 0xf473c70e, maximum = 0xf473c70f
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  405): OEMCrypto_GetHDCPCapability: ends! returns 0
D/DrmWidevineDash(  405): OEMCrypto_APIVersion: starts!
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  405): hlos api version =  9
D/DrmWidevineDash(  405): tz api version =  9
D/DrmWidevineDash(  405): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  405): OEMCrypto_GenerateNonce: starts! SID=1, nonce=0xf473c77c
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  405): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  405): PrepareKeyRequest: nonce=94792626
D/DrmWidevineDash(  405): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xaaf07800
D/DrmWidevineDash(  405): message_length=1645, signature=0xaaf07e78, signature_length=0xf473c6dc
D/QSEECOMAPI: (  405): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
I/art     (  432): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 279us total 19.518ms
I/art     (  432): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 311us total 15.907ms
D/StatusBarManagerService(  977): setSystemUiVisibility(0x0)
D/StatusBarManagerService(  977): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  977): hiding MENU key
I/TrimMemoryManager( 1587): [trimMemory] 20
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
D/QSEECOMAPI: (  405): QSEECom_shutdown_app, app_id = 9
D/DrmWidevineDash(  405): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  405): OEMCrypto_Terminate: ends! returns 0
I/CheckinRequestBuilder( 4446): Classify the device as Phone.
,D/libc    ( 4446): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
D/libc    ( 4446): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 4446): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
D/libc    ( 4446): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 4446): [NET] android_getaddrinfo_proxy+
D/libc    ( 4446): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  399): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
D/libc    (  399): [NET] _dns_getaddrinfo+, netid:100, mark:917604
D/libc    (  399): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  399): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 4446): [NET] android_getaddrinfo_proxy-, success
I/WebViewFactory( 6431): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
I/LibraryLoader( 6431): Time to load native libraries: 13 ms (timestamps 8979-8992)
I/LibraryLoader( 6431): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6431): Binding Chromium to main looper Looper (main, tid 1) {297b5257}
I/LibraryLoader( 6431): Expected native library version number "",actual native library version number ""
I/chromium( 6431): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6431): Initializing chromium process, singleProcess=true
W/art     ( 6431): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6431): ApplicationContext is null in ApplicationStatus
W/chromium( 6431): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 6431): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6431): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6431): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 6431): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6431): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6431): Local Branch: 
I/Adreno-EGL( 6431): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6431): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6431):                  d74aa161a12b9c6fc6332151
W/System.err(  977): java.lang.Throwable: stack dump
W/System.err(  977): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  977): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  977): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  977): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothManagerService(  977): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  977): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2bd0fde9:true
D/BluetoothAdapter( 6431): 360234227: getState(). Returning 12
W/art     ( 6431): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 6431): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 6431): CordovaWebView is running on device made by: HTC
W/art     ( 6431): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6431): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 6431): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
D/FindExtension( 6431): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
D/wpa_supplicant( 1328): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 1328): wlan0: nl80211: New scan results available
D/wpa_supplicant( 1328): nl80211: Scan included frequencies: 2412 2417 2422 2427 2432 2437 2442 2447 2452 2457 2462 2467 2472 5180 5200 5220 5240 5260 5280 5300 5320 5500 5520 5540 5560 5580 5600 5620 5640 5660 5680 5700
D/wpa_supplicant( 1328): wlan0: Event SCAN_RESULTS (3) received
I/wpa_supplicant( 1328): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1328): wlan0: Scan completed in 2.125185 seconds
D/wpa_supplicant( 1328): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1328): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1328): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1328): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
I/wpa_supplicant( 1328): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-51
I/wpa_supplicant( 1328): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1328): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-80
D/wpa_supplicant( 1328): wlan0: BSS: Start scan result update 5
D/wpa_supplicant( 1328): BSS: last_scan_res_used=3/32
D/wpa_supplicant( 1328): wlan0: Scan-only results received
D/wpa_supplicant( 1328): wlan0: Radio work 'scan'@0x558a9dc680 done in 2.126639 seconds
E/WifiMonitor(  977): WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor(  977): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
E/WifiStateMachine(  977): handleMessage: E msg.what=147461
E/WifiStateMachine(  977): processMsg: ConnectedState
E/WifiStateMachine(  977):  ConnectedState !SCAN_RESULTS_EVENT 0 0 found=3 known=1 got=3 bcn=0
E/WifiStateMachine(  977): processMsg: L2ConnectedState
E/WifiStateMachine(  977):  L2ConnectedState !SCAN_RESULTS_EVENT 0 0 found=3 known=1 got=3 bcn=0
E/WifiStateMachine(  977): processMsg: ConnectModeState
E/WifiStateMachine(  977):  ConnectModeState !SCAN_RESULTS_EVENT 0 0 found=3 known=1 got=3 bcn=0
E/WifiStateMachine(  977): processMsg: DriverStartedState
E/WifiStateMachine(  977):  DriverStartedState !SCAN_RESULTS_EVENT 0 0 found=3 known=1 got=3 bcn=0
E/WifiStateMachine(  977): processMsg: SupplicantStartedState
W/ContextImpl(  977): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:14146 com.android.server.wifi.WifiStateMachine.handleMediaLinkEvent:14311 com.android.server.wifi.WifiStateMachine.access$6000:268 com.android.server.wifi.WifiStateMachine$SupplicantStartedState.processMessage:8091 
E/WifiStateMachine(  977):  SupplicantStartedState !SCAN_RESULTS_EVENT 0 0 found=3 known=1 got=3 bcn=0
D/WifiStateMachine(  977): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
W/WifiHW  (  977): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1328): wlan0: Control interface command 'LIST_DONGLES'
E/WifiStateMachine(  977): [1,454,460,142,227 ms] noteScanEnd no scan source
W/WifiHW  (  977): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/wpa_supplicant( 1328): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
E/WifiStateMachine(  977): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@39ac2330 sup_state=COMPLETED debouncing=false
E/WifiAutoJoinController (  977): NG7005g c0:ff:d4:d3:aa:4a rssi=-51 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiAutoJoinController (  977): NG700 c0:ff:d4:d3:aa:48 rssi=-57 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiConfigStore(  977): updateSavedNetworkHistory(): try "NG700"WPA_PSK SSID="NG700" NG700 [WPA2-PSK-CCMP][WPS][ESS] ajst=0
E/WifiConfigStore(  977): updateSavedNetworkHistory: HTC improve mode
E/WifiConfigStore(  977):         got known scan result c0:ff:d4:d3:aa:48 key : "NG700"WPA_PSK num: 1 rssi=-57 freq=2412
E/WifiAutoJoinController (  977): Gonzos 38:f8:89:11:e9:11 rssi=-80 cap [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS] is not scored
E/WifiAutoJoinController (  977): ageScanResultsOut delay 40000 size 3 now 1454460142229
E/WifiAutoJoinController (  977): newSupplicantResults size=3 known=1 true
W/WifiHW  (  977): QCOM Debug wifi_send_command "IFNAME=wlan0 STATUS-NO_EVENTS"
D/wpa_supplicant( 1328): wlan0: Control interface command 'STATUS-NO_EVENTS'
E/WifiAutoJoinController (  977): attemptAutoJoin() status=bssid=c0:ff:d4:d3:aa:48
E/WifiAutoJoinController (  977): ssid=NG700
E/WifiAutoJoinController (  977): id=0
E/WifiAutoJoinController (  977): mode=station
E/WifiAutoJoinController (  977): pairwise_cipher=CCMP
E/WifiAutoJoinController (  977): group_cipher=CCMP
E/WifiAutoJoinController (  977): key_mgmt=WPA2-PSK
E/WifiAutoJoinController (  977): wpa_state=COMPLETED
E/WifiAutoJoinController (  977): ip_address=192.168.1.130
E/WifiAutoJoinController (  977): p2p_device_address=92:e7:c4:e6:4c:f8
E/WifiAutoJoinController (  977): address=XX:XX:XX:XX:XX:XX
E/WifiAutoJoinController (  977): uuid=12345678-9abc-def0-1234-56789abcdef1 split=12
E/WifiAutoJoinController (  977): attemptAutoJoin() num recent config 1 current="NG700"WPA_PSK ---> suppNetId=0
E/WifiAutoJoinController (  977): attemptAutoJoin good candidate seen, bumped hard -> status=0 "NG700"WPA_PSK rssi=(-57,-127) num=(1,0)
E/WifiAutoJoinController (  977): attemptAutoJoin skip current candidate  0 key "NG700"WPA_PSK
E/WifiAutoJoinController (  977): attemptRoam: "NG700"WPA_PSK Found c0:ff:d4:d3:aa:48 rssi=-57 freq=2412 Current: c0:ff:d4:d3:aa:48
D/HtcWifiControlRoamOffload: (  977): roamCandidate: nullcurrentBSSID: c0:ff:d4:d3:aa:48
E/WifiStateMachine(  977): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiAutoJoinController (  977): Done attemptAutoJoin status=0
E/WifiConfigStore(  977):  writeKnownNetworkHistory() num networks:1 needWrite=false
E/WifiStateMachine(  977): handleMessage: X
D/WifiManager( 1848): getScanResults: Base Package Name=com.google.android.gms, uid=10024
E/WifiStateMachine(  977): handleMessage: E msg.what=131155
E/WifiStateMachine(  977): processMsg: ConnectedState
E/WifiStateMachine(  977):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=2.2 bcn=0 [on:0 tx:0 rx:0 period:2149] from screen [on:0 period:-1533771094] gl hn u24 rssi=-52 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  977): processMsg: L2ConnectedState
E/WifiStateMachine(  977):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=2.2 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1533771093] gl hn u24 rssi=-52 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  977):  get link layer stats 0
W/WifiHW  (  977): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1328): wlan0: Control interface command 'SIGNAL_POLL'
D/libc    ( 4446): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
D/libc    ( 4446): [NET] android_getaddrinfofornet-, err=8
I/wpa_supplicant( 1328): environment dirty rate=0 [2][0][0]
E/WifiStateMachine(  977): fetchRssiLinkSpeedAndFrequencyNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  977): fetchRssiLinkSpeedAndFrequencyNative rssi=-57 linkspeed=72
E/WifiConfigStore(  977): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-57 "NG700"WPA_PSK
E/WifiStateMachine(  977): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=1.13 txretriesrate=0.00 rxrate=2.11 userTriggerdPenalty0
E/WifiStateMachine(  977):  good link -> stuck count =0
E/WifiStateMachine(  977):  badRSSI count0 lowRSSI count0 --> score 56
E/WifiStateMachine(  977):  isHighRSSI       ---> score=61
D/WifiWatchdogStateMachine(  977): RSSI current: 3 new: -57, 3
D/WIFI_ICON( 1218): updateWifiState: RSSI_CHANGED 3 -> 3
E/WifiStateMachine(  977): handleMessage: X
D/StatusBar.NetworkController( 1218): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/WifiTrafficPoller(  977): TRAFFIC_STATS_POLL true Token 11 num clients 6
E/WifiTrafficPoller(  977):  packet count Tx=188 Rx=292
E/WifiTrafficPoller(  977): notifying of data activity 3
D/WIFI_ICON( 1218): WifiActivity: 3
D/StatusBar.NetworkController( 1218): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
I/InputMethodManager( 6431): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@191ee2e0, mServedView=org.apache.cordova.engine.SystemWebView{34870999 VFEDH.C. .F....I. 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@7c1e45e
I/InputMethodManagerService(  977): Disable input method client, pid=1587
D/StatusBarManagerService(  977): swetImeWindowStatus vis=0 backDisposition=0
I/InputMethodManagerService(  977): Enable input method client, pid=6431
I/ActivityManager(  977): Displayed com.test.thalitest/.MainActivity: +817ms
I/PhoneStatusBar( 1218): setImeWindowStatus(false,false)
D/PMS     (  977): releaseWL(7947d40): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
W/BindingManager( 6431): Cannot call determinedVisibility() - never saw a connection for the pid: 6431
W/XT9_C   ( 1408): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1408): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1408): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1408): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
D/JsMessageQueue( 6431): Set native->JS mode to OnlineEventsBridgeMode
W/ContextImpl(  977): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 
D/jxcore_app_log( 6431): JniHelper::setJavaVM(0xaae9e8f8), pthread_self() = -1407483752
I/chromium( 6431): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
D/libc    ( 4446): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
D/libc    ( 4446): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 4446): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
D/libc    ( 4446): [NET] android_getaddrinfofornet-, err=8
I/CheckinTask( 4446): Sending checkin request (8407 bytes)
I/HtcModeClient( 3227): handler message = 4011
E/HtcModeClient( 3227): Check connection and retry 12 times.
E/WifiTrafficPoller(  977): TRAFFIC_STATS_POLL true Token 11 num clients 6
E/WifiTrafficPoller(  977):  packet count Tx=201 Rx=302
,I/CheckinRequestBuilder( 4446): Checkin reason type: 11 attempt count: 1
,I/ActivityManager(  977): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 4446): Failed to find provider info for com.google.android.wearable.settings
,I/art     ( 1965): Explicit concurrent mark sweep GC freed 14883(816KB) AllocSpace objects, 7(588KB) LOS objects, 49% free, 4MB/8MB, paused 1.481ms total 39.581ms,
,D/PMS     (  977): releaseHCC(169b7d4): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null,
D/PMS     (  977): releaseHCC(11fe0d7d): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,I/GLSUser ( 1965): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
,I/GLSUser ( 1965): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1965): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1965): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1965): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/jxcore-log( 6431): Initializing JXcore engine
,W/jxcore-log( 6431): JXcore engine is ready
,D/DotMatrix( 1329): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1329): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1218): reapply : com.google.android.gms 1 40
,W/CheckinRequestBuilder( 4446): awaiting user notification for token,
,I/art     ( 6431): Background sticky concurrent mark sweep GC freed 5932(530KB) AllocSpace objects, 0(0B) LOS objects, 0% free, 12MB/12MB, paused 6.909ms total 32.442ms
I/CheckinRequestBuilder( 4446): Classify the device as Phone.
,I/CheckinTask( 4446): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 4446): Checking schedule, now: 1454460143680 next: 1454996975675
I/CheckinService( 4446): active receiver: disabled
I/PackageManager(  977):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=4446, uid=10024, userID:0,
W/jxcore-log( 6431): Starting JXcore engine
,D/PMS     (  977): releaseWL(1cd52255): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10024 com.google.android.gms},
,I/ActivityManager(  977): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=6491 uid=10077 gids={50077, 9997, 3003} abi=arm64-v8a
,D/PhoneMonitor( 6491): Register our PhoneStateListener
,V/SetupWizard( 6491): Connected to Gservices successfully
,D/PhoneMonitor( 6491): onServiceStateChanged state="3 3 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1EriInd= -1EriMode= -1RadioPowerSv: false EmergOnly=false PhoneType: 1 VoiceRoaming: false DataRoaming: false IMSRegState: -1" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_POWER_OFF(3) D:STATE_POWER_OFF(3) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,D/ChimeraCfgMgr( 4446): Loading module com.google.android.gms.kids from APK com.google.android.gms,
,W/jxcore-log( 6431): Platform android
W/jxcore-log( 6431): 
W/jxcore-log( 6431): Process ARCH arm
W/jxcore-log( 6431): 
,D/ChimeraCfgMgr( 4446): Loading module com.google.android.gms.kids from APK com.google.android.gms
D/PhoneMonitor( 6491): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_POWER_OFF(3) D:STATE_POWER_OFF(3) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,D/GCM     ( 1965): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/GLSUser ( 1965): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 1965): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1965): [GLSUser] Extracting token using key: Auth,
W/GLSActivity( 1965): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1965): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Kids    ( 4446): [AccountUtils] Account not ready
W/Kids    ( 4446): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 4446): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 4446): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 4446): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 4446): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 4446): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 4446): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 4446): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 4446): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 4446): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 4446): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 4446): 	at java.lang.Thread.run(Thread.java:818)
I/RemoteViews( 1218): reapply : com.google.android.gms 1 40
,D/DotMatrix( 1329): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true,
D/DotMatrix( 1329): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/jxcore-log( 6431): JXcore Cordova bridge is ready!
I/jxcore-log( 6431): 
W/jxcore-log( 6431): JXcore engine is started
,E/WifiTrafficPoller(  977): TRAFFIC_STATS_POLL true Token 11 num clients 6,
E/WifiTrafficPoller(  977):  packet count Tx=202 Rx=303
,I/jxcore-log( 6431): Toggling radios to true,
I/jxcore-log( 6431): 
,D/BluetoothAdapter( 6431): enable(): BT is already enabled..!,
,D/WifiService(  977): New client listening to asynchronous messages,
E/WifiTrafficPoller(  977): ADD_CLIENT: 7
D/WifiManager( 6431): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10366
,W/Settings:Agent(  977): MONITOR_LOG
D/WifiService(  977): setWifiEnabled: true pid=6431, uid=10366
W/Settings:Agent(  977): name: wifi_on
E/WifiService(  977): Invoking mWifiStateMachine.setWifiEnabled
W/Settings:Agent(  977): value: 2
I/WifiService(  977): isSprintWifiRestricted(): false
W/Settings:Agent(  977): >> traceCallingStack()
I/WifiService(  977): isMdmWifiRestricted(): false
,W/Settings:Agent(  977): Process.myPid(): 977
W/Settings:Agent(  977): Process.myTid(): 4796
W/Settings:Agent(  977): Process.myUid(): 1000
W/Settings:Agent(  977): 
W/Settings:Agent(  977): 
W/System.err(  977): java.lang.Throwable: stack dump
,W/System.err(  977): 	at java.lang.Thread.dumpStack(Thread.java:490)
,W/System.err(  977): 	at android.provider.HtcISettings$Agent.traceCallingStack(HtcISettings.java:56)
W/System.err(  977): 	at android.provider.HtcISettingsGlobal$Agent.monitorKey(HtcISettingsGlobal.java:64)
W/System.err(  977): 	at android.provider.Settings$Global.putStringForUser(Settings.java:7422)
W/System.err(  977): 	at android.provider.Settings$Global.putString(Settings.java:7403)
W/System.err(  977): 	at android.provider.Settings$Global.putInt(Settings.java:7503)
W/System.err(  977): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:154)
W/System.err(  977): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:103)
,W/System.err(  977): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:1144)
W/System.err(  977): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:222)
W/System.err(  977): 	at android.os.Binder.execTransact(Binder.java:454)
W/Settings:Agent(  977): 
W/Settings:Agent(  977): << traceCallingStack(): 24(ms)
D/WifiController(  977): handleMessage: E msg.what=155656
D/WifiManager( 6431): disconnect: Base Package Name=com.test.thalitest, uid=10366
D/WifiManager( 6431): reconnect: Base Package Name=com.test.thalitest, uid=10366
E/WifiStateMachine(  977): handleMessage: E msg.what=131145
E/WifiStateMachine(  977): processMsg: ConnectedState
E/WifiStateMachine(  977):  ConnectedState !CMD_DISCONNECT 0 0
D/WifiController(  977): processMsg: DeviceActiveState
D/WifiController(  977): processMsg: StaEnabledState
D/WifiController(  977): handleMessage: X
E/WifiStateMachine(  977): processMsg: L2ConnectedState
E/WifiStateMachine(  977):  L2ConnectedState !CMD_DISCONNECT 0 0
W/WifiHW  (  977): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
D/wpa_supplicant( 1328): wlan0: Control interface command 'DISCONNECT'
D/wpa_supplicant( 1328): wlan0: Cancelling scan request
D/wpa_supplicant( 1328): wlan0: Request to deauthenticate - bssid=c0:ff:d4:d3:aa:48 pending_bssid=00:00:00:00:00:00 reason=3 state=COMPLETED
D/wpa_supplicant( 1328): TDLS: Tear down peers
D/wpa_supplicant( 1328): wpa_driver_nl80211_disconnect(reason_code=3)
I/jxcore-log( 6431): Radios toggled
I/jxcore-log( 6431): 
I/jxcore-log( 6431): My device name is: HTC-HTC One M8s
I/jxcore-log( 6431): 
,D/wpa_supplicant( 1328): wlan0: Event DEAUTH (12) received
D/wpa_supplicant( 1328): wlan0: Deauthentication notification
,D/wpa_supplicant( 1328): wlan0:  * reason 3 (locally generated)
D/wpa_supplicant( 1328): Deauthentication frame IE(s) - hexdump(len=0): [NULL]
I/wpa_supplicant( 1328): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1328): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/wpa_supplicant( 1328): enter disconnect check
I/wpa_supplicant( 1328): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/PMS     (  977): acquireWL(131c7883): PARTIAL_WAKE_LOCK  NetworkStats 0x1 977 1000 null
D/wpa_supplicant( 1328): wlan0: Auto connect disabled: do not try to re-connect
D/UsbDeviceManager(  977): [USBNET] bCheckSuppFunc: cdc_network
D/wpa_supplicant( 1328): wlan0: Ignore connection failure indication since interface has been put into disconnected state
D/Tethering(  977): interfaceLinkStateChanged wlan0, false
D/Tethering(  977): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  977): WiFiDisplay: getWifidisplayApEnabled=false
D/Tethering(  977): interfaceLinkStateChanged wlan0, false
D/Tethering(  977): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  977): WiFiDisplay: getWifidisplayApEnabled=false
D/Tethering(  977): TetherInterfaceSM: wlan0: InitialState processMessage what=CMD_INTERFACE_DOWN
V/Tethering(  977): TetherInterfaceSM: wlan0: exit InitialState
V/Tethering(  977): TetherInterfaceSM: wlan0: enter UnavailableState
E/WifiStateMachine(  977): WiFiDisplay: getWifidisplayApEnabled=false
D/Tethering(  977): sendTetherStateChangedBroadcast 0, 0, 0
D/WifiMonitor(  977): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412]
D/UsbnetService(  977): BroadcastReceiver::onReceive+
D/UsbnetService(  977): ACTION_TETHER_STATE_CHANGED: active=[],USB_FUNCTION_NCM=false
D/UsbnetService(  977): BroadcastReceiver::onReceive-
,D/wpa_supplicant( 1328): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1328): wlan0: Disconnect event - remove keys
E/WifiMonitor(  977): WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/WifiMonitor(  977): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  977): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/wpa_supplicant( 1328): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/WifiMonitor(  977): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
D/wpa_supplicant( 1328): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1328): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x558a9d9f88 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1328):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1328): wlan0: State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1328): nl80211: Set wlan0 operstate 1->0 (DORMANT)
D/wpa_supplicant( 1328): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 1328): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1328): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1328): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1328): nl80211: Skip set_supp_port(unauthorized) while not associated
D/wpa_supplicant( 1328): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1328): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1328): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1328): wlan0: State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1328): nl80211: Set wlan0 operstate 0->0 (DORMANT)
D/wpa_supplicant( 1328): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 1328): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1328): EAPOL: External notification - portValid=0
D/WifiDisplayAdapter(  977): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  977):     Client/Owner: Client
D/WifiDisplayAdapter(  977):     GroupId: 
D/WifiDisplayAdapter(  977):     Passphrase: 
D/WifiDisplayAdapter(  977):     SessionId: 0
D/WifiDisplayAdapter(  977):     IP Address: }
D/wpa_supplicant( 1328): RTM_NEWLINK: ifi_index=29 ifname=wlan0 operstate=2 linkmode=1 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1328): Wireless event: cmd=0x8b15 len=24
D/wpa_supplicant( 1328): RTM_NEWLINK: ifi_index=29 ifname=wlan0 wext ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1328): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1328): nl80211: Ignore disconnect event triggered during reassociation
E/WifiStateMachine(  977): transitionTo: destState=DisconnectingState
E/WifiStateMachine(  977): handleMessage: new destination call exit/enter
E/WifiStateMachine(  977): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
E/WifiStateMachine(  977): invokeExitMethods: ConnectedState
D/WifiMonitor(  977): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiStateMachine(  977): WifiStateMachine: Leaving Connected state
E/WifiMonitor(  977): WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiPerfLock(  977): release()
E/WifiStateMachine(  977): PerfLock released for exiting ConnectedState
D/HTCRequest(  977): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  97,7): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine(  977): setScanAlarm false period 20000 initial delay 0mAlarmEnabledtrue
D/HTCRequest(  977): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  977): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
E/WifiStateMachine(  977): invokeExitMethods: L2ConnectedState
E/WifiStateMachine(  977): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$13400 - exit - invokeExitMethods
E/WifiStateMachine(  977): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  977): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  977): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
W/WifiHW  (  977): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1328): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1328): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1328): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  977): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1328): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1328): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 1328): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1328): CTRL_IFACE: SAVE_CONFIG - Configuration updated
E/WifiStateMachine(  977): setSuspendOptimizationsNative: 1 true -want false stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
W/WifiHW  (  977): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
D/wpa_supplicant( 1328): wlan0: Control interface command 'DRIVER POWERMODE 0'
I/wpa_supplicant( 1328): Power_Mode_Type mode = 0
I/wpa_supplicant( 1328): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
W/WifiHW  (  977): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
D/wpa_supplicant( 1328): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/wpa_supplicant( 1328): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 8192
D/WifiDataStallTracker(  977): setDhcpActive: false
D/WifiP2pService(  977): InactiveState{ when=-5ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  977): P2pEnabledState{ when=-5ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/TetherSettings( 5981): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 5981): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 5981): Cust_ConnectToPC   : Modem_Link>false
D/        ( 5981): Cust_ConnectToPC   : spcsc>false
D/        ( 5981): Cust_ConnectToPC   : IPT>true
D/        ( 5981): Cust_ConnectToPC   : Singel_USB>false
V/NativeCrypto( 1965): Read error: ssl=0x55a98feca0: I/O error during system call, Connection timed out
E/WifiStateMachine(  977): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  977): setDetailed state send new extra info<unknown ssid>
E/WifiStateMachine(  977): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
W/Settings( 5981): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/WifiStateMachine(  977): NetworkAgent != null
D/PMS     (  977): acquireWL(8296a00): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1965 10024 WorkSource{10024 com.google.android.gms}
E/WifiStateMachine(  977): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/ConnectivityService(  977): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
E/WifiStateMachine(  977): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  977): [NET] android_getaddrinfofornet+,hn 13(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  977): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  977): autoRoamSetBSSID any key="NG700"WPA_PSK,
E/WifiConfigStore(  977): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
V/NetworkPolicy(  977): mWifiStateReceiver: meteredHint=false,EPS mode=false
W/WifiHW  (  977): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1328): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1328): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1328): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
D/libc    (  977): [NET] android_getaddrinfofornet+,hn 6,sn(),hints(known),family 0,flags 4
D/libc    (  977): [NET] android_getaddrinfofornet-, SUCCESS
D/WIFI_ICON( 1218): updateWifiState: NETWORK_STATE_CHANGED connected
W/WifiHW  (  977): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/StatusBar.NetworkController( 1218): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
E/SmartNS_Utility( 5981): hasRemovableStorageSlot: true
D/ConnectivityService(  977): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
D/wpa_supplicant( 1328): wlan0: Control interface command 'SAVE_CONFIG',
D/PMS     (  977): releaseWL(131c7883): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,D/wpa_supplicant( 1328): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/WIFI_ICON( 1218): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/SmartNS_Utility( 5981): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
V/NetworkPolicy(  977): updateNetworkEnabledLocked()
D/libc    (  977): [NET] android_getaddrinfofornet+,hn 25(0x666538303a3a39),sn(),hints(known),family 0,flags 4
V/NetworkPolicy(  977): updateNotificationsLocked()
D/libc    (  977): [NET] android_getaddrinfofornet-, SUCCESS
D/WifiDisplayAdapter(  977): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  977):     Client/Owner: Client
D/WifiDisplayAdapter(  977):     GroupId: 
D/WifiDisplayAdapter(  977):     Passphrase: 
D/WifiDisplayAdapter(  977):     SessionId: 0
D/WifiDisplayAdapter(  977):     IP Address: }
D/SmartNS_NSReceiver( 5981): onReceive : android.net.conn.TETHER_STATE_CHANGED hasTethered:false isNSOpening:false
D/StatusBar.NetworkController( 1218): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/wpa_supplicant( 1328): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/WIFI_ICON( 1218): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/wpa_supplicant( 1328): CTRL_IFACE: SAVE_CONFIG - Configuration updated
D/StatusBar.NetworkController( 1218): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiStateMachine(  977): moveTempStackToStateStack: i=0,j=4
D/ConnectivityService(  977): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10024
,E/WifiStateMachine(  977): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectingState
W/ContextImpl( 5981): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.NSReceiver.onReceive:432 android.app.ActivityThread.handleReceiver:2712 
E/WifiStateMachine(  977): invokeEnterMethods: DisconnectingState
D/PMS     (  977): releaseWL(8296a00): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms}
E/WifiStateMachine(  977):  Enter DisconnectingState State scan interval 300000 mEnableBackgroundScan= false screenOn=true
D/WIFI_ICON( 1218): updateWifiState: NETWORK_STATE_CHANGED disconnected
E/WifiStateMachine(  977): Start Disconnecting Watchdog 1
D/StatusBar.NetworkController( 1218): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiStateMachine(  977): handleMessage: X
D/WIFI_ICON( 1218): updateWifiState: NETWORK_STATE_CHANGED disconnected
E/WifiStateMachine(  977): handleMessage: E msg.what=131146
D/StatusBar.NetworkController( 1218): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiStateMachine(  977): processMsg: DisconnectingState
E/WifiStateMachine(  977):  DisconnectingState !CMD_RECONNECT 0 0
E/WifiStateMachine(  977): processMsg: ConnectModeState
E/WifiStateMachine(  977):  ConnectModeState !CMD_RECONNECT 0 0
W/WifiHW  (  977): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
V/NativeCrypto( 1965): SSL shutdown failed: ssl=0x55a98feca0: I/O error during system call, Broken pipe
D/wpa_supplicant( 1328): wlan0: Control interface command 'RECONNECT'
D/wpa_supplicant( 1328): wlan0: Selecting BSS from priority group 607
D/wpa_supplicant( 1328): wlan0: 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 caps=0x511 level=-51 wps
D/wpa_supplicant( 1328): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1328): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 1328): wlan0: 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-57 wps
D/wpa_supplicant( 1328): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1328): wlan0:    selected based on RSN IE
W/wpa_supplicant( 1328): [EAP-MSG] EAP wpa_supplicant_check_sim@842: eap_methods not available
D/wpa_supplicant( 1328):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
D/wpa_supplicant( 1328): wlan0:    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700'
D/wpa_supplicant( 1328): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: DISCONNECTED  ssid=0x558a9dbc00  current_ssid=0x0
D/wpa_supplicant( 1328): wlan0: Request association with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1328): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1328): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=7): 00 05 4e 47 37 30 30
D/wpa_supplicant( 1328): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 03 01 01
D/wpa_supplicant( 1328): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 2a 01 00
D/wpa_supplicant( 1328): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 08 04 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1328): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 1328): WPA: WMM Parameter Element - hexdump(len=24): 00 50 f2 02 01 01 80 00 03 a4 00 00 27 a4 00 00 42 43 5e 00 62 32 2f 00
D/wpa_supplicant( 1328): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1328): TDLS: TDLS is allowed in the target BSS
D/wpa_supplicant( 1328): wlan0: Add radio work 'connect'@0x558a9dc680
D/wpa_supplicant( 1328): wlan0: First radio work item in the queue - schedule, start immediately
D/wpa_supplicant( 1328): wlan0: Starting radio work 'connect'@0x558a9dc680 after 0.000296 second wait
I/wpa_supplicant( 1328): check if in concurrent case
I/wpa_supplicant( 1328): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/WifiMonitor(  977): Event [IFNAME=wlan0 Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)]
E/WifiMonitor(  977): WifiMonitor:wlan0 cnt=33 dispatchEvent: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
E/WifiStateMachine(  977): handleMessage: X
E/WifiStateMachine(  977): handleMessage: E msg.what=131101
E/WifiStateMachine(  977): processMsg: DisconnectingState
E/WifiStateMachine(  977):  DisconnectingState !CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  977): processMsg: ConnectModeState
E/WifiStateMachine(  977):  ConnectModeState !CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  977): processMsg: DriverStartedState
E/WifiStateMachine(  977):  DriverStartedState !CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  977): processMsg: SupplicantStartedState
E/WifiStateMachine(  977):  SupplicantStartedState !CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  977): processMsg: DefaultState
E/WifiStateMachine(  977):  DefaultState !CMD_TETHER_STATE_CHANGE 0 0
D/WifiStateMachine(  977): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  977): Default got CMD_TETHER_STATE_CHANGE
E/WifiStateMachine(  977): handleMessage: X
E/WifiStateMachine(  977): handleMessage: E msg.what=147460
E/WifiStateMachine(  977): processMsg: DisconnectingState
I/IntentController( 1218): receive(android.net.wifi.STATE_CHANGE,1,false)
I/IntentController( 1218): receive(android.net.wifi.STATE_CHANGE,1,false)
I/IntentController( 1218): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  977):  DisconnectingState !NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=101624
E/WifiStateMachine(  977): processMsg: ConnectModeState
D/wpa_supplicant( 1328): FT: Stored MDIE and FTIE from (Re)Association Response - hexdump(len=0):
D/wpa_supplicant( 1328): wlan0: Cancelling scan request
D/wpa_supplicant( 1328): wpas_start_assoc_cb, 1892
D/wpa_supplicant( 1328): wpas_start_assoc_cb, 1895
D/wpa_supplicant( 1328): wpas_start_assoc_cb, 1910
D/wpa_supplicant( 1328): wlan0: WPA: clearing own WPA/RSN IE
D/wpa_supplicant( 1328): wlan0: Automatic auth_alg selection: 0x1
D/wpa_supplicant( 1328): RSN: PMKSA cache search - network_ctx=0x558a9dbc00 try_opportunistic=0
D/wpa_supplicant( 1328): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1328): RSN: No PMKSA cache entry found
D/wpa_supplicant( 1328): wlan0: RSN: using IEEE 802.11i/D9.0
D/wpa_supplicant( 1328): wlan0: WPA: Selected cipher suites: group 16 pairwise 16 key_mgmt 2 proto 2
D/wpa_supplicant( 1328): wlan0: WPA: Selected mgmt group cipher 32
D/wpa_supplicant( 1328): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 1328): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1328): wlan0: WPA: using GTK CCMP
D/wpa_supplicant( 1328): wlan0: WPA: using PTK CCMP
D/wpa_supplicant( 1328): wlan0: WPA: using KEY_MGMT WPA-PSK
E/WifiStateMachine(  977):  ConnectModeState !NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=101624
D/wpa_supplicant( 1328): wlan0: WPA: not using MGMT group cipher
D/wpa_supplicant( 1328): WPA: Set own WPA IE default - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1328): wlan0: State: DISCONNECTED -> ASSOCIATING
D/wpa_supplicant( 1328): nl80211: Set wlan0 operstate 0->0 (DORMANT)
D/wpa_supplicant( 1328): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
E/WifiStateMachine(  977): ConnectModeState: Network connection lost 
E/WifiStateMachine(  977): transitionTo: destState=DisconnectedState
D/wpa_supplicant( 1328): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0,)
D/wpa_supplicant( 1328): nl80211: Set mode ifindex 29 iftype 2 (STATION)
E/WifiStateMachine(  977): handleMessage: new destination call exit/enter
D/wpa_supplicant( 1328): nl80211: Unsubscribe mgmt frames handle 0x888888dd02153989 (mode change)
E/WifiStateMachine(  977): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
E/WifiStateMachine(  977): invokeExitMethods: DisconnectingState
E/WifiStateMachine(  977): moveTempStackToStateStack: i=0,j=4
E/WifiStateMachine(  977): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectedState
E/WifiStateMachine(  977): invokeEnterMethods: DisconnectedState
E/WifiStateMachine(  977): DisconnectedState call setCountryCode()
D/wpa_supplicant( 1328): nl80211: Subscribe to mgmt frames with non-AP handle 0x558a9db100
D/wpa_supplicant( 1328): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x558a9db100 match=0104
E/WifiStateMachine(  977):  Enter disconnected State scan interval 300000 mEnableBackgroundScan= false screenOn=true
D/wpa_supplicant( 1328): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x558a9db100 match=040a
W/WifiHW  (  977): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN TYPE=ONLY"
D/wpa_supplicant( 1328): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x558a9db100 match=040b
D/wpa_supplicant( 1328): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x558a9db100 match=040c
D/wpa_supplicant( 1328): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x558a9db100 match=040d
D/wpa_supplicant( 1328): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x558a9db100 match=090a
D/wpa_supplicant( 1328): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x558a9db100 match=090b
D/wpa_supplicant( 1328): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x558a9db100 match=090c
D/wpa_supplicant( 1328): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x558a9db100 match=090d
D/wpa_supplicant( 1328): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x558a9db100 match=0409506f9a09
D/wpa_supplicant( 1328): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x558a9db100 match=7f506f9a09
D/wpa_supplicant( 1328): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x558a9db100 match=0801
D/wpa_supplicant( 1328): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x558a9db100 match=040e
D/wpa_supplicant( 1328): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x558a9db100 match=06
D/wpa_supplicant( 1328): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x558a9db100 match=0a07
D/wpa_supplicant( 1328): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x558a9db100 match=0a11
D/WifiDataStallTracker(  977): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
E/WifiStateMachine(  977): WiFiDisplay: getWifidisplayApEnabled=false
D/WifiDataStallTracker(  977): stopDataStallAlarm 
D/wpa_supplicant( 1328): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x558a9db100 match=0a1a
D/wpa_supplicant( 1328): nl80211: Connect (ifindex=29)
D/wpa_supplicant( 1328):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1328):   * bssid_hint=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1328):   * freq=2412
D/wpa_supplicant( 1328):   * freq_hint=2412
D/wpa_supplicant( 1328):   * SSID - hexdump(len=5): 4e 47 37 30 30
D/wpa_supplicant( 1328):   * IEs - hexdump(len=30): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00 7f 06 00 00 0a 82 00 40
D/wpa_supplicant( 1328):   * WPA Versions 0x2
D/wpa_supplicant( 1328):   * pairwise=0xfac04
D/wpa_supplicant( 1328):   * group=0xfac04
D/wpa_supplicant( 1328):   * akm=0xfac02
D/wpa_supplicant( 1328):   * Auth Type 0
D/wpa_supplicant( 1328): nl80211: set key mgmt offload, suite 2, support 0x0, psk 0x0x558a9dbc3a
E/WifiTrafficPoller(  977): ENABLE_TRAFFIC_STATS_POLL true Token 11
D/wpa_supplicant( 1328): nl80211: Connect request send successfully
D/wpa_supplicant( 1328): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 1328): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1328): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1328): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1328): wlan0: Control interface command 'SCAN TYPE=ONLY'
D/wpa_supplicant( 1328): Ongoing scan action - reject new request
D/WifiMonitor(  977): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor(  977): WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  977): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  977): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine(  977): setScanAlarm true period 10000 initial delay 3000mAlarmEnabledfalse
D/HTCRequest(  977): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  977): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =ASSOCIATING
E/WifiTrafficPoller(  977):  packet count Tx=202 Rx=303
E/WifiTrafficPoller(  977): notifying of data activity 0
E/WifiStateMachine(  977): handleMessage: X
E/WifiStateMachine(  977): handleMessage: E msg.what=147462
E/WifiStateMachine(  977): processMsg: DisconnectedState
E/WifiTrafficPoller(  977): ENABLE_TRAFFIC_STATS_POLL false Token 12
E/WifiDataStallTracker(  977): ENABLE_DATA_MONITOR_POLL false Token 1
E/WifiTrafficPoller(  977): ENABLE_TRAFFIC_STATS_POLL false Token 13
E/WifiStateMachine(  977):  DisconnectedState !SUPPLICANT_STATE_CHANGE_EVENT 32 0 rt=101634  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine(  977): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine(  977): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  977): processMsg: ConnectModeState
E/WifiStateMachine(  977):  ConnectModeState !SUPPLICANT_STATE_CHANGE_EVENT 32 0 rt=101635  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine(  977): handleMessage: X
D/WifiNetworkAgent(  977): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine(  977): handleMessage: E msg.what=131213
E/WifiStateMachine(  977): processMsg: DisconnectedState
E/WifiStateMachine(  977):  DisconnectedState !CMD_TARGET_BSSID 33 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=101636
E/WifiStateMachine(  977): processMsg: ConnectModeState
E/WifiStateMachine(  977):  ConnectModeState !CMD_TARGET_BSSID 33 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=101637
E/WifiStateMachine(  977): processMsg: DriverStartedState
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  977): ValidatedState{ when=-1ms what=532488 arg1=10024 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  977): DefaultState{ when=-1ms what=532488 arg1=10024 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  977): Forcing reevaluation
E/WifiStateMachine(  977):  DriverStartedState !CMD_TARGET_BSSID 33 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=101637
E/WifiStateMachine(  977): processMsg: SupplicantStartedState
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  977): EvaluatingState{ when=-1ms what=532486 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  977): Validated
E/WifiStateMachine(  977):  SupplicantStartedState !CMD_TARGET_BSSID 33 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=101638
E/WifiStateMachine(  977): handleMessage: X
E/WifiStateMachine(  977): handleMessage: E msg.what=147462
E/WifiStateMachine(  977): processMsg: DisconnectedState
E/WifiStateMachine(  977):  DisconnectedState !SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=101639  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
E/WifiStateMachine(  977): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine(  977): setDetailed state, old =DISCONNECTED and new state=CONNECTING hidden=false
E/WifiStateMachine(  977): setDetailed state send new extra info"NG700"
E/WifiStateMachine(  977): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: DISCONNECTED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
I/SmartNS_Utility( 5981): setISNotification
E/WifiStateMachine(  977): NetworkAgent == null
E/WifiStateMachine(  977): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTING wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: DISCONNECTED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
E/WifiTrafficPoller(  977): ENABLE_TRAFFIC_STATS_POLL false Token 14
I/IntentController( 1218): receive(android.net.wifi.STATE_CHANGE,1,false)
D/SmartNS_Utility( 5981): usb_cable_connect = 1
E/WifiStateMachine(  977): processMsg: ConnectModeState
E/WifiStateMachine(  977):  ConnectModeState !SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=101654  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
E/WifiStateMachine(  977): handleMessage: X
D/SmartNS_Utility( 5981): usb_denied = 0
I/SmartNS_PSService( 5981): usb notificaiton:true
E/WifiStateMachine(  977): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiTrafficPoller(  977): ENABLE_TRAFFIC_STATS_POLL false Token 15
I/IntentController( 1218): receive(android.net.wifi.STATE_CHANGE,1,false)
I/ActionCombine( 5981): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal]
I/QuickSettingWifi( 1218): receive.wifiConnect:true wifiAPname:<unknown ssid> elapse:1
D/SmartNS_Utility( 5981): usb_cable_connect = 1
D/SmartNS_Utility( 5981): usb_denied = 0
I/SmartNS_PSService( 5981): usb notificaiton:true
D/DotMatrix( 1329): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
E/WifiStateMachine(  977): WiFiDisplay: getWifidisplayApEnabled=false
I/QuickSettingWifi( 1218): receive.wifiConnect:false wifiAPname:null elapse:10
I/QuickSettingWifi( 1218): receive.wifiConnect:false wifiAPname:null elapse:1
I/RemoteViews( 1218): reapply : com.android.settings 1 36
D/SmartNS_NSReceiver( 5981): Tethered state change:false isNSOpening:false
D/DotMatrix( 1329): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
I/RemoteViews( 1218): reapply : com.android.settings 0 36
D/WISPrService( 5981): >>>>>WISPrService start isConnected = true<<<<<
I/QuickSettingWifi( 1218): receive.wifiConnect:false wifiAPname:null elapse:1
D/ConnectivityService(  977): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  977):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  977): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,D/ConnectivityService(  977):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  977): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  977): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  977): Disconnected - quitting
D/ConnectivityManager.CallbackHandler( 1218): CM callback handler got msg 524292
D/Nat464Xlat(  977): requiresClat: netType=1, connected=false, mIsClatEnabled=true, hasIPv4Address=true
E/WifiTrafficPoller(  977): ADD_CLIENT: 8
D/WifiService(  977): New client listening to asynchronous messages
I/SecurityController( 1218): onLost 100
D/ConnectivityService(  977): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/QuickSettingWifi( 1218): receive.wifiConnect:false wifiAPname:null elapse:0
D/ConnectivityService(  977): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isSkipMobile=false
D/WIFI    (  977): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkManagementService(  977): Removing idletimer
D/usbnet  (  977): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  977):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/WIFI    (  977): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] released
E/WifiStateMachine(  977): enter WifiNetworkFactory startNetwork. mIPTStart:false
D/usbnet  (  977):   my score=70, my filter=[ Transports:  Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/usbnet  (  977): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
E/WifiStateMachine(  977): handleMessage: E msg.what=131131
D/WifiService(  977): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=httpproxy
E/WifiStateMachine(  977): processMsg: DisconnectedState
E/WifiStateMachine(  977):  DisconnectedState !CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine(  977): processMsg: ConnectModeState
E/WifiStateMachine(  977):  ConnectModeState !CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine(  977): handleMessage: X
D/PMS     (  977): acquireWL(2a9c907e): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 977 1000 null
D/wpa_supplicant( 1328): Wireless event: cmd=0x8c02 len=271
D/CSLegacyTypeTracker(  977): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=false
I/wpa_supplicant( 1328): WEXT: Custom wireless event: 'BEACONIEs='
D/ConnectivityService(  977): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/wpa_supplicant( 1328): RTM_NEWLINK: ifi_index=29 ifname=wlan0 wext ifi_flags=0x1003 ([UP])
W/WISPrService( 5981): can not find out wificonfig: SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/wpa_supplicant( 1328): Wireless event: cmd=0x8c02 len=152
I/wpa_supplicant( 1328): WEXT: Custom wireless event: 'BEACONIEs='
D/WISPrService( 5981): trigger connection
D/wpa_supplicant( 1328): RTM_NEWLINK: ifi_index=29 ifname=wlan0 wext ifi_flags=0x1003 ([UP])
D/WISPrService( 5981): continue
D/wpa_supplicant( 1328): Wireless event: cmd=0x8b15 len=24
D/wpa_supplicant( 1328): RTM_NEWLINK: ifi_index=29 ifname=wlan0 wext ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1328): RTM_NEWLINK: ifi_index=29 ifname=wlan0 operstate=5 linkmode=1 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1328): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1328): nl80211: Connect event
D/wpa_supplicant( 1328): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1328): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1328): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
D/wpa_supplicant( 1328): wlan0: Event ASSOC (0) received
D/wpa_supplicant( 1328): wlan0: Association info event
D/Tethering(  977): interfaceLinkStateChanged wlan0, false
D/wpa_supplicant( 1328): req_ies - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/Tethering(  977): interfaceStatusChanged wlan0, false
D/wpa_supplicant( 1328): resp_ies - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1328): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
E/WifiStateMachine(  977): WiFiDisplay: getWifidisplayApEnabled=false
D/wpa_supplicant( 1328): wlan0: freq=2412 MHz
D/wpa_supplicant( 1328): WPA: set own WPA/RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1328): FT: Stored MDIE and FTIE from (Re)Association Response - hexdump(len=0):
D/wpa_supplicant( 1328): wlan0: State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1328): nl80211: Set wlan0 operstate 0->0 (DORMANT)
D/wpa_supplicant( 1328): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 1328): wlan0: Associated to a new BSS: BSSID=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1328): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 1328): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
I/wpa_supplicant( 1328): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1328): wlan0: WPA: Association event - clear replay counter
D/wpa_supplicant( 1328): wlan0: WPA: Clear old PTK
D/wpa_supplicant( 1328): TDLS: Remove peers on association
D/wpa_supplicant( 1328): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1328): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1328): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1328): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1328): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1328): EAPOL: enable timer tick
D/wpa_supplicant( 1328): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1328): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 1328): wlan0: Cancelling scan request
I/wpa_supplicant( 1328): htc_wext_set_keepalive +
I/wpa_supplicant( 1328): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1328): getPrivFuncNum +	
D/WifiMonitor(  977): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
I/wpa_supplicant( 1328): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1328): htc_wext_set_keepalive fnum = 0x8bf6
E/WifiMonitor(  977): WifiMonitor:wlan0 cnt=35 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  977): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  977): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
I/wpa_supplicant( 1328): htc_wext_set_keepalive - ret = 0
D/HTCRequest(  977): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  977): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
D/WifiMonitor(  977): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412]
E/WifiStateMachine(  977): handleMessage: E msg.what=147462
E/WifiMonitor(  977): WifiMonitor:wlan0 cnt=36 dispatchEvent: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
E/WifiStateMachine(  977): processMsg: DisconnectedState
D/WifiMonitor(  977): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  977): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  977): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/Tethering(  977): interfaceLinkStateChanged wlan0, false
D/HTCRequest(  977): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/Tethering(  977): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  977): WiFiDisplay: getWifidisplayApEnabled=false
D/HTCRequest(  977): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  977): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
E/WifiStateMachine(  977):  DisconnectedState !SUPPLICANT_STATE_CHANGE_EVENT 35 0 rt=101741  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine(  977): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
D/WifiMonitor(  977): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
E/WifiStateMachine(  977): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
D/WifiMonitor(  977): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  977): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
E/WifiStateMachine(  977): setDetailed state send new extra info0x
E/WifiStateMachine(  977): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTING wifi info = SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/Tethering(  977): interfaceLinkStateChanged wlan0, false
D/Tethering(  977): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  977): WiFiDisplay: getWifidisplayApEnabled=false
D/Tethering(  977): interfaceLinkStateChanged wlan0, true
D/Tethering(  977): interfaceStatusChanged wlan0, true
E/WifiStateMachine(  977): WiFiDisplay: getWifidisplayApEnabled=false
V/Tethering(  977): TetherInterfaceSM: wlan0: enter InitialState
E/WifiStateMachine(  977): WiFiDisplay: getWifidisplayApEnabled=false
D/WISPrService( 5981): start DataConnection
D/libc    ( 5981): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 4
D/libc    ( 5981): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 5981): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
D/libc    ( 5981): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 5981): [NET] android_getaddrinfo_proxy+
D/libc    ( 5981): [NET] android_getaddrinfo_proxy get netid:0
I/ActivityManager(  977): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=6525 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a
D/libc    (  399): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
D/libc    (  399): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/ConnectivityService(  977): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/libc    (  399): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
E/ConnectivityService(  977): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/libc    (  399): [NET] android_getaddrinfofornet-, err=7
E/ConnectivityService(  977): EVENT_NETWORK_VALIDATED - isLiveNetworkAgent found mismatched netId: null - NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.130/24,fe80::92e7:c4ff:fee6:4cf8/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/libc    ( 5981): [NET] android_getaddrinfo_proxy-, NODATA
E/WifiStateMachine(  977): processMsg: ConnectModeState
E/WifiStateMachine(  977):  ConnectModeState !SUPPLICANT_STATE_CHANGE_EVENT 35 0 rt=101759  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
D/Tethering(  977): sendTetherStateChangedBroadcast 1, 0, 0
E/WifiStateMachine(  977): handleMessage: X
E/WifiStateMachine(  977): handleMessage: E msg.what=147500
E/WifiStateMachine(  977): processMsg: DisconnectedState
E/WifiStateMachine(  977):  DisconnectedState !what:147500 0 0
E/WifiStateMachine(  977): processMsg: ConnectModeState
E/WifiStateMachine(  977):  ConnectModeState !what:147500 0 0
D/WifiStateMachine(  977): Enter handleAssociatedWithEvent
D/WifiStateMachine(  977): Associated
,D/WifiStateMachine(  977): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  977): Exit handleAssociatedWithEvent
D/WifiService(  977): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=callernameid
E/WifiStateMachine(  977): handleMessage: X
V/NetworkPolicy(  977): ensureActiveMobilePolicyLocked()
D/WISPrService( 5981): >>>>>WISPrService start isConnected = false<<<<<
D/PMS     (  977): acquireWL(aab0f71): PARTIAL_WAKE_LOCK  NetworkStats 0x1 977 1000 null
D/Tethering(  977): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
D/UsbDeviceManager(  977): [USBNET] bCheckSuppFunc: cdc_network
D/Tethering(  977): TetherMasterSM: InitialState processMessage what=UPSTREAM_CHANGED
D/DATA_ICON( 1218): updateConnectivity android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE Type:-1/Status:0
D/UsbnetService(  977): BroadcastReceiver::onReceive+
D/UsbnetService(  977): ACTION_TETHER_STATE_CHANGED: active=[],USB_FUNCTION_NCM=false
D/UsbnetService(  977): BroadcastReceiver::onReceive-
E/WifiTrafficPoller(  977): ENABLE_TRAFFIC_STATS_POLL false Token 16
D/WISPrService( 5981): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: 0, Metered hint: false
I/IntentController( 1218): receive(android.net.wifi.STATE_CHANGE,1,false)
D/NetworkPolicy(  977): ensureActiveMobilePolicyLocked: SIM state invalid, slotId= -1000, subId=-1000 . Return.
V/NetworkPolicy(  977): updateNetworkEnabledLocked()
V/NetworkPolicy(  977): updateIfacesLocked()
E/WifiStateMachine(  977): handleMessage: E msg.what=131101
E/WifiStateMachine(  977): processMsg: DisconnectedState
E/WifiStateMachine(  977):  DisconnectedState !CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  977): processMsg: ConnectModeState
E/WifiStateMachine(  977):  ConnectModeState !CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  977): processMsg: DriverStartedState
E/WifiStateMachine(  977):  DriverStartedState !CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  977): processMsg: SupplicantStartedState
D/DATA_ICON( 1218): dataConnected: false/false
E/WifiStateMachine(  977):  SupplicantStartedState !CMD_TETHER_STATE_CHANGE 0 0
D/StatusBar.NetworkController( 1218): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiStateMachine(  977): processMsg: DefaultState
D/WIFI_ICON( 1218): updateWifiState: NETWORK_STATE_CHANGED disconnected
E/WifiStateMachine(  977):  DefaultState !CMD_TETHER_STATE_CHANGE 0 0
D/StatusBar.NetworkController( 1218): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiStateMachine(  977): [MLHD] enter handleMediaLinkEvent DefaultState
V/NetworkPolicy(  977): updateNotificationsLocked()
D/WifiStateMachine(  977): Default got CMD_TETHER_STATE_CHANGE
D/WifiService(  977): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=verizon
E/WifiStateMachine(  977): handleMessage: X
D/WISPrService( 5981): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 5981): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: 0, Metered hint: false
D/PMS     (  977): releaseWL(aab0f71): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/NetworkManagementService(  977): isBandwidthControlEnabled: doneSignal.getCount()= 0
D/WISPrService( 5981): >>>>>WISPrService start isConnected = false<<<<<
D/PMS     (  977): acquireWL(bf03156): PARTIAL_WAKE_LOCK  NetworkStats 0x1 977 1000 null
V/NetworkPolicy(  977): updateNetworkEnabledLocked()
V/NetworkPolicy(  977): updateNotificationsLocked()
D/WifiService(  977): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=fota
D/WISPrService( 5981): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: 0, Metered hint: false
D/PMS     (  977): releaseWL(bf03156): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
V/NetworkPolicy(  977): updateNetworkEnabledLocked()
V/NetworkPolicy(  977): updateNotificationsLocked()
D/WISPrService( 5981): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 5981): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: 0, Metered hint: false
D/WifiService(  977): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=supl
D/WISPrService( 5981): >>>>>WISPrService start isConnected = false<<<<<
D/FlexNetS( 6168): updateSvcAllowedInSettings:false
D/WISPrService( 5981): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: 0, Metered hint: false
D/WifiService(  977): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=emergency
,D/FlexNetS( 6168): updateSvcAllowedInSettings:false
,D/WifiService(  977): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=verizon800
,D/libc    ( 5981): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 4
,D/libc    ( 5981): [NET] android_getaddrinfofornet-, err=8
D/WifiService(  977): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=hipri
,D/TetherSettings( 5981): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
,D/        ( 5981): Cust_ConnectToPC   : Internet_Sharing>true
,D/        ( 5981): Cust_ConnectToPC   : Modem_Link>false
,W/ContextImpl( 5981): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.NSReceiver.onReceive:432 android.app.ActivityThread.handleReceiver:2712 
D/        ( 5981): Cust_ConnectToPC   : spcsc>false
D/        ( 5981): Cust_ConnectToPC   : IPT>true
D/        ( 5981): Cust_ConnectToPC   : Singel_USB>false,
W/Settings( 5981): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 5981): hasRemovableStorageSlot: true
D/SmartNS_Utility( 5981): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 5981): onReceive : android.net.conn.TETHER_STATE_CHANGED hasTethered:false isNSOpening:false
D/WifiService(  977): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=ims
E/WifiStateMachine(  977): WiFiDisplay: getWifidisplayApEnabled=false
I/SmartNS_Utility( 5981): setISNotification
I/QuickSettingWifi( 1218): receive.wifiConnect:false wifiAPname:null elapse:0
D/SmartNS_Utility( 5981): usb_cable_connect = 1
,D/SmartNS_Utility( 5981): usb_denied = 0
D/WISPrService( 5981): exception: java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
I/SmartNS_PSService( 5981): usb notificaiton:true
E/WifiStateMachine(  977): WiFiDisplay: getWifidisplayApEnabled=false
,D/WifiService(  977): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=default
,D/SmartNS_Utility( 5981): usb_cable_connect = 1
D/SmartNS_Utility( 5981): usb_denied = 0
,I/SmartNS_PSService( 5981): usb notificaiton:true,
E/WifiStateMachine(  977): WiFiDisplay: getWifidisplayApEnabled=false
D/WifiService(  977): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=mms
,D/DotMatrix( 1329): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
D/SmartNS_NSReceiver( 5981): Tethered state change:false isNSOpening:false
I/RemoteViews( 1218): reapply : com.android.settings 1 36
,D/WifiService(  977): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=cbs
,D/DotMatrix( 1329): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
D/WifiService(  977): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=ia
,D/FlexNetS( 6168): updateSvcAllowedInSettings:false
,D/WifiService(  977): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=dun
,D/FlexNetS( 6168): updateSvcAllowedInSettings:false
,I/RemoteViews( 1218): reapply : com.android.settings 1 36
,D/WifiService(  977): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=internet
,D/FlexNetS( 6168): updateSvcAllowedInSettings:false,
,D/FlexNetS( 6168): updateSvcAllowedInSettings:false,
,D/FlexNetS( 6168): updateSvcAllowedInSettings:false
,D/FlexNetS( 6168): updateSvcAllowedInSettings:false,
,I/ActivityManager(  977): Start proc com.htc.mobiledata:remote for service com.htc.mobiledata/.MobileDataService: pid=6550 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a,
,D/FlexNetS( 6168): updateSvcAllowedInSettings:false
,D/FlexNetS( 6168): updateSvcAllowedInSettings:false
,D/FlexNetS( 6168): updateSvcAllowedInSettings:false
,D/FlexNetS( 6168): updateSvcAllowedInSettings:false,
,D/FlexNetS( 6168): updateSvcAllowedInSettings:false
,D/FlexNetS( 6168): updateSvcAllowedInSettings:false,
,D/FlexNetS( 6168): updateSvcAllowedInSettings:false
,D/MdScPhnSt( 6550): [d0a.2.]  listen tmrbb8
,D/MdProvGlob( 6525): remove item 101 (p2d27in176) for 15:android.intent.action.ANY_DATA_STATE
,D/MdScDataSum( 6550): [d0a.2.] summary 118:p2 ignore
,D/Process (  977): killProcessQuiet, pid=5889,
I/ActivityManager(  977): Killing 5889:com.htc.calendar/u0a10 (adj 15): empty #17
D/Process (  977): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  977): Recipient 5889,
,E/WifiStateMachine(  977): handleMessage: E msg.what=131155
E/WifiStateMachine(  977): processMsg: DisconnectedState
,E/WifiStateMachine(  977):  DisconnectedState !CMD_RSSI_POLL 1 0 "NG700" 00:00:00:00:00:00 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1533768086] gl hn u24 rssi=-52 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  977): processMsg: ConnectModeState
E/WifiStateMachine(  977):  ConnectModeState !CMD_RSSI_POLL 1 0 "NG700" 00:00:00:00:00:00 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1533768085] gl hn u24 rssi=-52 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  977): processMsg: DriverStartedState
E/WifiStateMachine(  977):  DriverStartedState !CMD_RSSI_POLL 1 0 "NG700" 00:00:00:00:00:00 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1533768084] gl hn u24 rssi=-52 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  977): processMsg: SupplicantStartedState
E/WifiStateMachine(  977):  SupplicantStartedState !CMD_RSSI_POLL 1 0 "NG700" 00:00:00:00:00:00 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1533768083] gl hn u24 rssi=-52 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  977): processMsg: DefaultState
E/WifiStateMachine(  977):  DefaultState !CMD_RSSI_POLL 1 0 "NG700" 00:00:00:00:00:00 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1533768082] gl hn u24 rssi=-52 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0,
E/WifiStateMachine(  977): handleMessage: X
,E/WifiTrafficPoller(  977): TRAFFIC_STATS_POLL false Token 17 num clients 8,
,E/WifiTrafficPoller(  977): TRAFFIC_STATS_POLL false Token 17 num clients 8,
,D/wpa_supplicant( 1328): EAPOL: startWhen --> 0,
D/wpa_supplicant( 1328): EAPOL: disable timer tick
D/wpa_supplicant( 1328): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1328): EAPOL: enable timer tick
D/wpa_supplicant( 1328): EAPOL: txStart
D/wpa_supplicant( 1328): WPA: drop TX EAPOL in non-IEEE 802.1X mode (type=1 len=0)
,E/WifiDataStallTracker(  977): DATA_MONITOR_POLL false Token 2,
,D/Process (  977): killProcessQuiet, pid=5959
I/ActivityManager(  977): Killing 5959:com.google.android.partnersetup/u0a27 (adj 15): empty #17
D/Process (  977): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  977): Recipient 5959
,D/Process (  977): killProcessQuiet, pid=6260
I/ActivityManager(  977): Killing 6260:com.htc.cs.dm/u0a99 (adj 15): empty #17
D/Process (  977): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  977): Recipient 6260,
,D/Process (  977): killProcessQuiet, pid=6283,
I/ActivityManager(  977): Killing 6283:com.htc.providers.settings:remote/u0a13 (adj 15): empty #17
D/Process (  977): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  977): Recipient 6283
,D/wpa_supplicant( 1328): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1328): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 1328): wlan0: IEEE 802.1X RX: version=2 type=3 length=95
D/wpa_supplicant( 1328): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 1328): wlan0:   key_info 0x8a (ver=2 keyidx=0 rsvd=0 Pairwise Ack)
D/wpa_supplicant( 1328): wlan0:   key_length=16 key_data_length=0
D/wpa_supplicant( 1328):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 02
D/wpa_supplicant( 1328):   key_nonce - hexdump(len=32): 68 75 08 d1 9f 5a 6d 0a be 80 df c2 bc 05 25 42 43 ce da eb 50 dd d3 8e c5 be 65 4d c5 8e cb 70
D/wpa_supplicant( 1328):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1328):   key_rsc - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1328):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1328):   key_mic - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1328): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1328): wlan0: WPA: RX message 1 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 1328): RSN: msg 1/4 key data - hexdump(len=0):
D/wpa_supplicant( 1328): WPA: Renewed SNonce - hexdump(len=32): 44 61 5a 92 c9 f1 35 ed bc 84 c2 3e 26 85 1f e6 d1 f0 ca 88 3f a7 76 c5 85 7f 4b 89 fd 0c 71 bf
D/wpa_supplicant( 1328): WPA: Nonce1 - hexdump(len=32): 44 61 5a 92 c9 f1 35 ed bc 84 c2 3e 26 85 1f e6 d1 f0 ca 88 3f a7 76 c5 85 7f 4b 89 fd 0c 71 bf
D/wpa_supplicant( 1328): WPA: Nonce2 - hexdump(len=32): 68 75 08 d1 9f 5a 6d 0a be 80 df c2 bc 05 25 42 43 ce da eb 50 dd d3 8e c5 be 65 4d c5 8e cb 70
D/wpa_supplicant( 1328): WPA: PMK - hexdump(len=32): [REMOVED]
D/wpa_supplicant( 1328): WPA: PTK - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 1328): WPA: WPA IE for msg 2/4 - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1328): WPA: Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 02
D/wpa_supplicant( 1328): wlan0: WPA: Sending EAPOL-Key 2/4
D/wpa_supplicant( 1328): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 1328): WPA: Derived Key MIC - hexdump(len=16): c3 05 bf 45 49 62 2d d8 ad 87 10 01 82 21 e2 d5
D/WifiMonitor(  977): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor(  977): WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  977): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  977): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  977): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  977): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
E/WifiStateMachine(  977): handleMessage: E msg.what=147462
E/WifiStateMachine(  977): processMsg: DisconnectedState
E/WifiStateMachine(  977):  DisconnectedState !SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=104726  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
E/WifiStateMachine(  977): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  977): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  977): setDetailed state send new extra info"NG700"
E/WifiStateMachine(  977): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTING wifi info = SSID: NG700, BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: 0, Metered hint: false
D/wpa_supplicant( 1328): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1328): wlan0: IEEE 802.1X RX: version=2 type=3 length=151
D/wpa_supplicant( 1328): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 1328): wlan0:   key_info 0x13ca (ver=2 keyidx=0 rsvd=0 Pairwise Install Ack MIC ,Secure Encr)
D/wpa_supplicant( 1328): wlan0:   key_length=16 key_data_length=56
D/wpa_supplicant( 1328):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 03
D/wpa_supplicant( 1328):   key_nonce - hexdump(len=32): 68 75 08 d1 9f 5a 6d 0a be 80 df c2 bc 05 25 42 43 ce da eb 50 dd d3 8e c5 be 65 4d c5 8e cb 70
D/wpa_supplicant( 1328):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1328):   key_rsc - hexdump(len=8): ad 98 00 00 00 00 00 00
D/wpa_supplicant( 1328):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1328):   key_mic - hexdump(len=16): 84 6f 31 44 85 62 f9 5c cb ae 8a 77 e8 af 2a b3
D/wpa_supplicant( 1328): RSN: encrypted key data - hexdump(len=56): 6c bd ee 18 ca 6f d3 63 a7 78 8a dc b5 80 ef c6 98 e0 e5 1d 9e 66 c5 fa 6c d0 21 b7 2f f2 1d 36 ...
D/wpa_supplicant( 1328): WPA: decrypted EAPOL-Key key data - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 1328): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1328): wlan0: WPA: RX message 3 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 1328): WPA: IE KeyData - hexdump(len=48): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00 dd 16 00 0f ac 01 01 00 cb bd ...
D/wpa_supplicant( 1328): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1328): WPA: GTK in EAPOL-Key - hexdump(len=24): [REMOVED]
D/wpa_supplicant( 1328): wlan0: WPA: Sending EAPOL-Key 4/4
D/wpa_supplicant( 1328): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 1328): WPA: Derived Key MIC - hexdump(len=16): 81 a4 6b 1f ca fd 30 3c a0 8d 3c 96 b8 bb 85 ac
D/wpa_supplicant( 1328): wlan0: WPA: Installing PTK to the driver
D/wpa_supplicant( 1328): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=3 addr=0x558a9dc390 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 1328): nl80211: KEY_DATA - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 1328): nl80211: KEY_SEQ - hexdump(len=6): 00 00 00 00 00 00
D/wpa_supplicant( 1328):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1328): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1328): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1328): RSN: received GTK in pairwise handshake - hexdump(len=18): [REMOVED]
D/wpa_supplicant( 1328): WPA: Group Key - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 1328): wlan0: WPA: Installing GTK to the driver (keyidx=1 tx=0 len=16)
D/wpa_supplicant( 1328): WPA: RSC - hexdump(len=6): ad 98 00 00 00 00
D/WifiMonitor(  977): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/wpa_supplicant( 1328): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=3 addr=0x5576ba2e68 key_idx=1 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 1328): nl80211: KEY_DATA - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 1328): nl80211: KEY_SEQ - hexdump(len=6): ad 98 00 00 00 00
D/WIFI_ICON( 1218): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/wpa_supplicant( 1328):    broadcast key
D/StatusBar.NetworkController( 1218): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiMonitor(  977): WifiMonitor:wlan0 cnt=38 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  977): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  977): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  977): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WIFI_ICON( 1218): updateWifiState: NETWORK_STATE_CHANGED disconnected
I/wpa_supplicant( 1328): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/StatusBar.NetworkController( 1218): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/wpa_supplicant( 1328): wlan0: Cancelling authentication timeout
E/wpa_supplicant( 1328): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1328): wla,n0: State: GROUP_HANDSHAKE -> COMPLETED
D/wpa_supplicant( 1328): wlan0: Radio work 'connect'@0x558a9dc680 done in 3.113097 seconds
I/wpa_supplicant( 1328): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiMonitor(  977): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
I/wpa_supplicant( 1328): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
D/WifiMonitor(  977): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
E/WifiMonitor(  977): WifiMonitor:wlan0 cnt=39 dispatchEvent: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
W/WifiMonitor(  977): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor(  977): Event [IFNAME=wlan0 BLACKLIST REMOVE c0:ff:d4:d3:aa:48]
E/WifiMonitor(  977): WifiMonitor:wlan0 cnt=40 dispatchEvent: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/WifiMonitor(  977): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]]
E/WifiMonitor(  977): WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiMonitor(  977): handleEvent 1  Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/wpa_supplicant( 1328): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 1328): nl80211: Set wlan0 operstate 0->1 (UP)
D/wpa_supplicant( 1328): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=6 (IF_OPER_UP)
D/WifiMonitor(  977): Event [IFNAME=wlan0 Connect to SSID: NG700]
E/WifiMonitor(  977): WifiMonitor:wlan0 cnt=42 dispatchEvent: Connect to SSID: NG700
W/WifiMonitor(  977): couldn't identify event type - Connect to SSID: NG700
I/wpa_supplicant( 1328): set send_ind_to_ndc = 0
I/wpa_supplicant( 1328): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1328): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1328): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1328): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1328): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1328): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1328): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1328): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 1328): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1328): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
D/WifiMonitor(  977): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/wpa_supplicant( 1328): EAPOL: SUPP_BE entering state IDLE
E/WifiMonitor(  977): WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/wpa_supplicant( 1328): EAPOL authentication completed - result=SUCCESS
I/wpa_supplicant( 1328): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
D/HTCRequest(  977): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  977): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/wpa_supplicant( 1328): RTM_NEWLINK: ifi_index=29 ifname=wlan0 operstate=6 linkmode=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/HTCRequest(  977): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/Tethering(  977): interfaceLinkStateChanged wlan0, true
D/Tethering(  977): interfaceStatusChanged wlan0, true
E/WifiStateMachine(  977): WiFiDisplay: getWifidisplayApEnabled=false
D/WifiMonitor(  977): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
E/WifiStateMachine(  977): NetworkAgent == null
E/WifiStateMachine(  977): [sendNetworkStateChangeBroadcast] NetworkInfo state =AUTHENTICATING wifi info = SSID: NG700, BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: 0, Metered hint: false
E/WifiTrafficPoller(  977): ENABLE_TRAFFIC_STATS_POLL false Token 17
I/IntentC,ontroller( 1218): receive(android.net.wifi.STATE_CHANGE,1,false)
I/IntentController( 1218): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiTrafficPoller(  977): ENABLE_TRAFFIC_STATS_POLL false Token 18
E/WifiStateMachine(  977): processMsg: ConnectModeState
E/WifiStateMachine(  977):  ConnectModeState !SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=104740  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
E/WifiStateMachine(  977): handleMessage: X
E/WifiStateMachine(  977): handleMessage: E msg.what=147462
E/WifiStateMachine(  977): processMsg: DisconnectedState
E/WifiStateMachine(  977):  DisconnectedState !SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=104741  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine(  977): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  977): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  977): processMsg: ConnectModeState
E/WifiStateMachine(  977):  ConnectModeState !SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=104742  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine(  977): handleMessage: X
E/WifiStateMachine(  977): handleMessage: E msg.what=147459
E/WifiStateMachine(  977): processMsg: DisconnectedState
E/WifiStateMachine(  977):  DisconnectedState !NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=104743
E/WifiStateMachine(  977): processMsg: ConnectModeState
E/WifiStateMachine(  977):  ConnectModeState !NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=104743
E/WifiStateMachine(  977): Network connection established
D/WifiStateMachine(  977): fetchFrequency(), freq = 2412
E/WifiStateMachine(  977): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
E/WifiStateMachine(  977): NetworkAgent == null
E/WifiStateMachine(  977): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WISPrService( 5981): >>>>>WISPrService start isConnected = false<<<<<
E/WifiTrafficPoller(  977): ENABLE_TRAFFIC_STATS_POLL false Token 19
E/WifiStateMachine(  977): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WISPrService( 5981): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/WIFI_ICON( 1218): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1218): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
I/IntentController( 1218): receive(android.net.wifi.STATE_CHANGE,1,false)
,E/WifiStateMachine(  977): transitionTo: destState=ObtainingIpState
D/WifiDisplayAdapter(  977): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  977):     Client/Owner: Client
D/WifiDisplayAdapter(  977):     GroupId: 
D/WifiDisplayAdapter(  977):     Passphrase: 
D/WifiDisplayAdapter(  977):     SessionId: 0
D/WifiDisplayAdapter(  977):     IP Address: }
E/WifiStateMachine(  977): handleMessage: new destination call exit/enter
E/WifiStateMachine(  977): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
E/WifiStateMachine(  977): invokeExitMethods: DisconnectedState
E/WifiStateMachine(  977): setScanAlarm false period 0 initial delay 0mAlarmEnabledtrue
,D/WISPrService( 5981): >>>>>WISPrService start isConnected = false<<<<<
E/WifiStateMachine(  977): moveTempStackToStateStack: i=1,j=4
E/WifiStateMachine(  977): moveTempStackToStateStack: i=0,j=5
E/WifiStateMachine(  977): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=4,Top=ObtainingIpState
E/WifiStateMachine(  977): invokeEnterMethods: L2ConnectedState
E/WifiStateMachine(  977): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
E/WifiTrafficPoller(  977): ENABLE_TRAFFIC_STATS_POLL false Token 20
,D/WISPrService( 5981): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/WIFI_ICON( 1218): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1218): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiStateMachine(  977): NetworkAgent == null
E/WifiStateMachine(  977): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTING wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/ConnectivityService(  977): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/IntentController( 1218): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WISPrService( 5981): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 5981): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false,
I/AlarmManager(  977): [AlarmQueuing] connectivity wifi: false
D/GpsLocationProvider(  977): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider(  977): [handleMessage] UPDATE_NETWORK_STATE,
D/PMS     (  977): acquireWL(76b5330): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 977 1000 null
,I/IntentController( 1218): receive(android.net.wifi.STATE_CHANGE,1,false)
,I/ConnectivityHelper( 1587): [onReceive] WIFI(1): DISCONNECTED
D/htcCheckinService(  977): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
D/WISPrService( 5981): >>>>>WISPrService start isConnected = false<<<<<
D/GpsLocationProvider(  977): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/htcCheckinService(  977): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
,E/WifiTrafficPoller(  977): ENABLE_TRAFFIC_STATS_POLL false Token 21
D/ConnectivityService(  977): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiStateMachine(  977): L2ConnectedState c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  977): L2ConnectedState "NG700" nid=0
D/WIFI_ICON( 1218): updateWifiState: NETWORK_STATE_CHANGED disconnected
E/WifiConfigStore(  977): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/StatusBar.NetworkController( 1218): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
W/WifiHW  (  977): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1328): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1328): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/WISPrService( 5981): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/wpa_supplicant( 1328): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  977): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1328): wlan0: Control interface command 'SAVE_CONFIG'
D/ConnectivityService(  977): Got NetworkAgent Messenger
,D/wpa_supplicant( 1328): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/ConnectivityService(  977): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/wpa_supplicant( 1328): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/ConnectivityService(  977): NetworkAgent connected
,D/wpa_supplicant( 1328): CTRL_IFACE: SAVE_CONFIG - Configuration updated
I/QuickSettingWifi( 1218): receive.wifiConnect:false wifiAPname:null elapse:1
E/WifiStateMachine(  977): invokeEnterMethods: ObtainingIpState
E/WifiStateMachine(  977): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
E/WifiStateMachine(  977): ObtainingIpAddress c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
I/QuickSettingWifi( 1218): receive.wifiConnect:false wifiAPname:null elapse:1
E/WifiStateMachine(  977): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  977): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
W/WifiHW  (  977): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1328): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1328): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1328): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
,W/WifiHW  (  977): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1328): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1328): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
,D/wpa_supplicant( 1328): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1328): CTRL_IFACE: SAVE_CONFIG - Configuration updated
,D/WISPrService( 5981): >>>>>WISPrService start isConnected = false<<<<<
D/libc    (  977): [NET] android_getaddrinfofornet+,hn 7(0x302e302e302e30),sn(),hints(known),family 0,flags 4
D/libc    (  977): [NET] android_getaddrinfofornet+,hn 6,sn(),hints(known),family 0,flags 4
D/libc    (  977): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  977): [NET] android_getaddrinfofornet-, SUCCESS
D/WISPrService( 5981): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
E/WifiStateMachine(  977): Start Dhcp Watchdog 2
E/WifiStateMachine(  977): handleMessage: X
E/WifiStateMachine(  977): handleMessage: E msg.what=147462
E/WifiStateMachine(  977): processMsg: ObtainingIpState
E/WifiStateMachine(  977):  ObtainingIpState !SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=104801  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine(  977): processMsg: L2ConnectedState
E/WifiStateMachine(  977):  L2ConnectedState !SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=104802  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine(  977): processMsg: ConnectModeState
E/WifiStateMachine(  977):  ConnectModeState !SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=104803  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine(  977): handleMessage: X
,I/QuickSettingWifi( 1218): receive.wifiConnect:false wifiAPname:null elapse:1
,I/QuickSettingWifi( 1218): receive.wifiConnect:false wifiAPname:null elapse:1
,I/QuickSettingWifi( 1218): receive.wifiConnect:false wifiAPname:null elapse:1
,I/ActivityManager(  977): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6584 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=arm64-v8a
,E/WifiStateMachine(  977): handleMessage: E msg.what=131155
E/WifiStateMachine(  977): processMsg: ObtainingIpState
,E/WifiStateMachine(  977):  ObtainingIpState !CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-127 f=2412 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2405] from screen [on:0 period:-1533765676] gl hn u24 rssi=-52 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  977): processMsg: L2ConnectedState
E/WifiStateMachine(  977):  L2ConnectedState !CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-127 f=2412 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1533765675] gl hn u24 rssi=-52 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  977):  get link layer stats 0
,W/WifiHW  (  977): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1328): wlan0: Control interface command 'SIGNAL_POLL'
I/wpa_supplicant( 1328): environment dirty rate=0 [3][0][0]
E/WifiStateMachine(  977): fetchRssiLinkSpeedAndFrequencyNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  977): fetchRssiLinkSpeedAndFrequencyNative rssi=-57 linkspeed=72
E/GpsLocationProvider(  977): No APN found to select.
E/WifiConfigStore(  977): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-57 "NG700"WPA_PSK
E/WifiStateMachine(  977): calculateWifiScore freq=2412 speed=72 score=0 highRSSI  -> txbadrate=0.00 txgoodrate=101.50 txretriesrate=0.00 rxrate=151.50 userTriggerdPenalty0
E/WifiStateMachine(  977):  good link -> stuck count =0
E/WifiStateMachine(  977):  badRSSI count0 lowRSSI count0 --> score 60
E/WifiStateMachine(  977):  isHighRSSI       ---> score=65
D/WIFI_ICON( 1218): updateWifiState: RSSI_CHANGED -1 -> 3
E/WifiStateMachine(  977): calculateWifiScore() report new score 60
D/PMS     (  977): releaseWL(76b5330): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/WifiWatchdogStateMachine(  977): RSSI current: 3 new: -57, 3
D/ConnectivityService(  977): updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
E/WifiStateMachine(  977): handleMessage: X
E/WifiStateMachine(  977): handleMessage: E msg.what=131212
E/WifiStateMachine(  977): processMsg: ObtainingIpState
E/WifiStateMachine(  977):  ObtainingIpState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  977): processMsg: L2ConnectedState
E/WifiStateMachine(  977):  L2ConnectedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  977): processMsg: ConnectModeState
E/WifiStateMachine(  977):  ConnectModeState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  977): processMsg: DriverStartedState
E/WifiStateMachine(  977):  DriverStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  977): processMsg: SupplicantStartedState
E/WifiStateMachine(  977):  SupplicantStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  977): processMsg: DefaultState
D/StatusBar.NetworkController( 1218): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
E/WifiStateMachine(  977):  DefaultState !CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService(  977): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine(  977): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  977): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
D/WifiStateMachine(  977): handlePreDhcpSetup Held wake lock during DHCP
E/WifiStateMachine(  977): handleMessage: X
D/PMS     (  977): acquireWL(760b0f4): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 977 1000 null
E/WifiStateMachine(  977): handleMessage: E msg.what=196612
D/WifiStateMachine(  977): handlePreDhcpSetup mBluetoothConnectionActive: false
E/WifiStateMachine(  977): processMsg: ObtainingIpState
E/WifiStateMachine(  977):  ObtainingIpState !CMD_PRE_DHCP_ACTION 0 0 txpkts=203,0,0
E/WifiStateMachine(  977): processMsg: L2ConnectedState
E/WifiStateMachine(  977):  L2ConnectedState !CMD_PRE_DHCP_ACTION 0 0 txpkts=203,0,0
D/WifiDataStallTracker(  977): setDhcpActive: true
W/WifiHW  (  977): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
D/wpa_supplicant( 1328): wlan0: Control interface command 'DRIVER BTCOEXMODE 1'
D/wpa_supplicant( 1328): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 8192
E/WifiStateMachine(  977): setSuspendOptimizationsNative: 1 false -want false stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  (  977): do suspend false
W/WifiHW  (  977): QCOM Debug wifi_send_command "IFNAME=wlan0 DR,IVER SETSUSPENDMODE 0"
D/wpa_supplicant( 1328): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 0'
D/wpa_supplicant( 1328): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 0 len = 0, 8192
W/WifiHW  (  977): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
D/wpa_supplicant( 1328): wlan0: Control interface command 'DRIVER POWERMODE 1'
I/wpa_supplicant( 1328): INFO - Deny active power mode because already has gateway
D/wpa_supplicant( 1328): nl80211: Drv Event 79 (NL80211_CMD_SET_REKEY_OFFLOAD) received for wlan0
D/wpa_supplicant( 1328): nl80211: Rekey offload event for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1328): nl80211: Rekey offload - Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1328): wlan0: Event DRIVER_GTK_REKEY (37) received
W/WifiHW  (  977): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
D/wpa_supplicant( 1328): wlan0: Control interface command 'DRIVER WLS_BATCHING GET'
E/wpa_supplicant( 1328): wpa_driver_nl80211_driver_cmd: failed to issue private commands
E/WifiStateMachine(  977): Unexpected BatchedScanResults :null
D/WifiP2pService(  977): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3bd7cc44 target=com.android.internal.util.StateMachine$SmHandler }
W/WifiHW  (  977): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
D/WifiP2pService(  977): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3bd7cc44 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1328): wlan0: Control interface command 'DRIVER WLS_BATCHING STOP'
E/wpa_supplicant( 1328): wpa_driver_nl80211_driver_cmd: failed to issue private commands
E/WifiStateMachine(  977): noteBatchedScanstop()
E/WifiStateMachine(  977): handleMessage: X
D/MdScPhnSt( 6550): [528.1.]  listen tmrbb8
D/MdScDataSum( 6550): [528.1.] summary 118:p1 ignore
,I/art     (  977): Explicit concurrent mark sweep GC freed 45742(2MB) AllocSpace objects, 4(208KB) LOS objects, 33% free, 16MB/25MB, paused 1.551ms total 145.531ms
E/dhcpcd  ( 6607): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
I/dhcpcd  ( 6607): version 5.5.6 starting
E/dhcpcd  ( 6607): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
I/dhcpcd  ( 6607): wlan0: using ClientID 01:90:**:c4:e6:4c:f8
I/dhcpcd  ( 6607): autoip env[11]:autoip=DISABLE
,I/MusicStore( 6584): Database version: 120
,I/dhcpcd  ( 6607): wlan0: rebinding lease of 192.168.1.130
I/dhcpcd  ( 6607): wlan0: sending REQUEST (xid 0xfb735391), next in 0.65 seconds
,D/VoldConnector(  977): SND -> {31 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/}
,E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/,
W/ContextImpl( 6584): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,D/VoldConnector(  977): SND -> {32 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/},
W/ContextImpl( 6584): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files,
E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
,D/VoldConnector(  977): SND -> {33 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/}
E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
,W/ContextImpl( 6584): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,W/ResourcesManager( 6584): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
W/ResourcesManager( 6584): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6584): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...,
,W/ActivityThread( 6584): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());,
,W/System  ( 6584): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@184d0f2a: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl,
I/ProviderInstaller( 6584): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6584): GMSCore installation verified
,I/ConfigStore( 6584): Config Database version: 1,
,I/PackageManager(  977):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=6584, uid=10159, userID:0,
,D/WifiDisplayAdapter(  977): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  977):     Client/Owner: Client,
D/WifiDisplayAdapter(  977):     GroupId: 
D/WifiDisplayAdapter(  977):     Passphrase: 
D/WifiDisplayAdapter(  977):     SessionId: 0
D/WifiDisplayAdapter(  977):     IP Address: }
,D/MediaRouterService(  977): Client com.google.android.music (pid 6584): Registered
,D/WifiDisplayAdapter(  977): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  977):     Client/Owner: Client
D/WifiDisplayAdapter(  977):     GroupId: 
D/WifiDisplayAdapter(  977):     Passphrase: 
D/WifiDisplayAdapter(  977):     SessionId: 0
D/WifiDisplayAdapter(  977):     IP Address: }
,I/MediaRouter( 6584): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android },
,V/MusicLeanback( 6584): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) },
,I/PackageManager(  977):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=1, flag=1, pid=6584, uid=10159, userID:0,
D/AutoSetting( 1659): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/AutoSetting( 1659): Util - no network available!
,D/AutoSetting( 1659): service - onCreate()
,D/MobileConnectivityChangeReceiver( 6491): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6491): onReceive CONNECTIVITY_CHANGE networkType=1
,I/HtcModeClient( 3227): handler message = 4011
,E/HtcModeClient( 3227): Check connection and retry 12 times. Stop service and kill this process.,
I/GHttpClientFactory( 6584): Using our fixed implementation of GMSCore's GoogleHttpClient
,D/HtcModeClient( 3227): Don't start project servcice
,I/GoogleURLConnFactory( 6584): Using platform SSLCertificateSocketFactory
D/AutoSetting( 1659): service - onStartCommand() action: com.htc.app.autosetting.cancellocationupdate
,D/HtcModeClient( 3227): setEject: MEDIA_EJECT_STATE = true
,D/HtcModeClient( 3227): connectState: CONNECTION_READY = false
D/SilentMusic( 3227): call stop
D/HtcModeClient( 3227): close connection
W/HtcModeClient( 3227): leaveProjectMode: It does not enter ProjectMode
D/LocationManagerService(  977): request ea86899 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10052)
,D/LocationManagerService(  977): provider request: passive ProviderRequest[ON interval=0]
W/CANMesgAgentLocalSocket( 3227): read the terminate packet, so break
D/AutoSetting( 1659): service - mHandler: cancel location update
,D/AutoSetting( 1659): service -           changes count: 0
,I/iu.Environment( 4446): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 4446): num queued entries: 0,
I/iu.UploadsManager( 4446): num updated entries: 0
I/iu.SyncManager( 4446): NEXT; no task
D/ChimeraCfgMgr( 4446): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/Babel   ( 5807): connection state changed from CONNECTED to DISCONNECTED
I/ActivityManager(  977): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6632 uid=10161 gids={50161, 9997, 3003, 1028, 1015} abi=arm64-v8a
I/ActivityManager(  977): Killing 6047:com.google.android.gms:car/u0a24 (adj 15): empty #17
D/Process (  977): killProcessQuiet, pid=6047
D/Process (  977): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  977): Recipient 6047
,D/Process (  977): killProcessQuiet, pid=3227,
I/ActivityManager(  977): Killing 3227:com.htc.autobot/u0a47 (adj 15): empty #18
D/Process (  977): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  977): Recipient 3227
,I/dhcpcd  ( 6607): wlan0: sending REQUEST (xid 0xfb735391), next in 1.32 seconds,
,I/dhcpcd  ( 6607): wlan0: acknowledged 192.168.1.130 from 192.168.1.1,
,I/dhcpcd  ( 6607): wlan0: leased 192.168.1.130 for 86400 seconds,
I/dhcpcd  ( 6607): autoip env[11]:autoip=DISABLE
,D/libc    (  977): [NET] android_getaddrinfofornet+,hn 13(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  977): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  977): handleMessage: E msg.what=131212
E/WifiStateMachine(  977): processMsg: ObtainingIpState
E/WifiStateMachine(  977):  ObtainingIpState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  977): processMsg: L2ConnectedState
E/WifiStateMachine(  977):  L2ConnectedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  977): processMsg: ConnectModeState
E/WifiStateMachine(  977):  ConnectModeState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  977): processMsg: DriverStartedState
E/WifiStateMachine(  977):  DriverStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  977): processMsg: SupplicantStartedState
E/WifiStateMachine(  977):  SupplicantStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  977): processMsg: DefaultState
,E/WifiStateMachine(  977):  DefaultState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  977): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.130/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  977): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
E/WifiStateMachine(  977): handleMessage: X
D/ConnectivityService(  977): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
,I/GAv4    ( 6632): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:,
I/GAv4    ( 6632):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6632):   adb logcat -s GAv4
D/VoldConnector(  977): SND -> {34 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/}
W/ContextImpl( 6632): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/
,D/VoldConnector(  977): SND -> {35 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/}
E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/
,W/ContextImpl( 6632): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,D/VoldConnector(  977): SND -> {36 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/}
,E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/
,W/ContextImpl( 6632): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,D/VoldConnector(  977): SND -> {37 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/}
W/ContextImpl( 6632): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
E/Vold    (  385): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/
,W/GAv4    ( 6632): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6632): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6632): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/dhcpcd  ( 6607): bind_interface: daemonise,
,W/global  ( 6632): [apache-http] Connection GC has been deprecated!,
,W/global  ( 6632): [apache-http] Connection GC has been deprecated!,
,D/libc    (  977): [NET] android_getaddrinfofornet+,hn 13(0x3139322e313638),sn(),hints(known),family 0,flags 4
,D/WifiP2pService(  977): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/libc    (  977): [NET] android_getaddrinfofornet-, SUCCESS
D/WifiP2pService(  977): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/libc    (  977): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/PMS     (  977): releaseWL(760b0f4): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
D/libc    (  977): [NET] android_getaddrinfofornet-, SUCCESS
D/ConnectivityService(  977): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
D/libc    (  977): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  977): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  977): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  977): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  977): handleMessage: E msg.what=196613
E/WifiStateMachine(  977): processMsg: ObtainingIpState
E/WifiStateMachine(  977):  ObtainingIpState !CMD_POST_DHCP_ACTION 1 0 OK  v4
,E/WifiStateMachine(  977): processMsg: L2ConnectedState
E/WifiStateMachine(  977):  L2ConnectedState !CMD_POST_DHCP_ACTION 1 0 OK  v4
E/WifiStateMachine(  977): setSuspendOptimizationsNative: 1 true -want false stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
W/WifiHW  (  977): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
D/wpa_supplicant( 1328): wlan0: Control interface command 'DRIVER POWERMODE 0'
I/wpa_supplicant( 1328): Power_Mode_Type mode = 0
I/wpa_supplicant( 1328): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
W/WifiHW  (  977): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
D/wpa_supplicant( 1328): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/wpa_supplicant( 1328): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 8192
D/WifiDataStallTracker(  977): setDhcpActive: false
E/WifiStateMachine(  977): handlePostDhcpSetup release wake lock during DHCP
E/WifiStateMachine(  977): WifiStateMachine DHCP successful
E/WifiStateMachine(  977): wifistatemachine handleIPv4Success <IP address 192.168.1.130/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds>
E/WifiStateMachine(  977): link address 192.168.1.130/24
,E/WifiStateMachine(  977): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.130/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.130/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine(  977): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
E/WifiStateMachine(  977): gateway: /192.168.1.1
W/WifiHW  (  977): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
D/wpa_supplicant( 1328): wlan0: Control interface command 'DRIVER GATEWAY-ADD 16885952'
I/wpa_supplicant( 1328): WiFi gateway: 0x101a8c0
D/WifiStateMachine(  977): [MLHD] enter handleMediaLinkEvent L2ConnectedState
E/WifiStateMachine(  977): handleMessage: X
E/WifiStateMachine(  977): handleMessage: E msg.what=131210
E/WifiStateMachine(  977): processMsg: ObtainingIpState
E/WifiStateMachine(  977):  ObtainingIpState !CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine(  977): processMsg: L2ConnectedState
E/WifiStateMachine(  977):  L2ConnectedState !CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
W/WifiHW  (  977): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1328): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1328): environment dirty rate=0 [3][0][0]
E/WifiStateMachine(  977): fetchRssiLinkSpeedAndFrequencyNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  977): fetchRssiLinkSpeedAndFrequencyNative rssi=-57 linkspeed=72
,E/WifiConfigStore(  977): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-57 "NG700"WPA_PSK
W/WifiHW  (  977): QCOM Debug wifi_send_command "IFNAME=wlan0 BLACKLIST clear"
D/wpa_supplicant( 1328): wlan0: Control interface command 'BLACKLIST clear'
E/wpa_supplicant( 1328): wlan0: BLACKLIST CLEAR 
D/WifiWatchdogStateMachine(  977): RSSI current: 3 new: -57, 3
D/WIFI_ICON( 1218): updateWifiState: RSSI_CHANGED 3 -> 3
D/WifiMonitor(  977): Event [IFNAME=wlan0 BLACKLIST CLEAR ]
,D/StatusBar.NetworkController( 1218): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
E/WifiStateMachine(  977): setDetailed state, old =CONNECTING and new state=CONNECTED hidden=false
E/WifiMonitor(  977): WifiMonitor:wlan0 cnt=44 dispatchEvent: BLACKLIST CLEAR 
E/WifiStateMachine(  977): NetworkAgent != null
E/WifiStateMachine(  977): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -57, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
D/ConnectivityService(  977): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService(  977): Adding iface wlan0 to network 101
,E/WifiStateMachine(  977): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -57, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiDataStallTracker(  977): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
D/HtcWifiWanDetect(  977): WAN detection
E/WifiTrafficPoller(  977): ENABLE_TRAFFIC_STATS_POLL true Token 22
V/NetworkPolicy(  977): mWifiStateReceiver: meteredHint=false,EPS mode=false
E/WifiTrafficPoller(  977):  packet count Tx=204 Rx=305
D/HtcWifiWanDetect(  977): canDoWanDetection: mHtcWanDetectionDialogEnabled: true mHtcWanDetectionEnabled: true
,E/WifiTrafficPoller(  977): notifying of data activity 3
D/WIFI_ICON( 1218): updateWifiState: NETWORK_STATE_CHANGED connected
I/IntentController( 1218): receive(android.net.wifi.STATE_CHANGE,1,false)
V/NetworkPolicy(  977): mWifiStateReceiver: meteredHint=false,EPS mode=false
I/IntentController( 1218): receive(android.net.wifi.STATE_CHANGE,1,false)
D/StatusBar.NetworkController( 1218): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/WifiDataStallTracker(  977): ENABLE_DATA_MONITOR_POLL true Token 2
D/WIFI_ICON( 1218): updateWifiState: NETWORK_STATE_CHANGED connected
E/WifiTrafficPoller(  977): ENABLE_TRAFFIC_STATS_POLL true Token 23
D/StatusBar.NetworkController( 1218): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/WifiStateMachine(  977): transitionTo: destState=ConnectedState
D/WIFI_ICON( 1218): WifiActivity: 3
E/WifiStateMachine(  977): handleMessage: new destination call exit/enter
D/StatusBar.NetworkController( 1218): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
E/WifiStateMachine(  977): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
E/WifiStateMachine(  977): invokeExitMethods: ObtainingIpState
E/WifiStateMachine(  977): moveTempStackToStateStack: i=0,j=5
E/WifiStateMachine(  977): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=ConnectedState
E/WifiStateMachine(  977): invokeEnterMethods: ConnectedState
E/WifiTrafficPoller(  977):  packet count Tx=204 Rx=305
E/WifiTrafficPoller(  977): notifying of data activity 0
E/WifiStateMachine(  977): updateDefaultRouteMacAddress found Ipv4 default :192.168.1.1
E/WifiStateMachine(  977): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
D/WifiDataStallTracker(  977): updateDataStallInfo: mDataStallTxRxSum={txSum=0 rxSum=0} preTxRxSum={txSum=0 rxSum=0}
,D/WifiDataStallTracker(  977): updateDataStallInfo: NONE
D/WifiDataStallTracker(  977): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,E/ConnectivityService(  977): Unexpected mtu value: 0, wlan0
,D/ConnectivityService(  977): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/libc    (  399): [NET] android_getaddrinfofornet+,hn 6,sn(),hints(known),family 0,flags 4
D/libc    (  399): [NET] android_getaddrinfofornet-, SUCCESS
D/ConnectivityService(  977): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
E/WifiStateMachine(  977): ConnectedState Enter  mScreenOn=true scanperiod=20000
E/WifiStateMachine(  977): setScanAlarm true period 20000 initial delay 200mAlarmEnabledfalse
D/WifiDisplayAdapter(  977): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  977):     Client/Owner: Client
D/WifiDisplayAdapter(  977):     GroupId: 
D/WifiDisplayAdapter(  977):     Passphrase: 
D/WifiDisplayAdapter(  977):     SessionId: 0
D/WifiDisplayAdapter(  977):     IP Address: }
E/WifiStateMachine(  977): handleMessage: X
,D/WISPrService( 5981): >>>>>WISPrService start isConnected = true<<<<<
D/libc    (  399): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  399): [NET] android_getaddrinfofornet-, SUCCESS
,D/ConnectivityService(  977): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/libc    (  399): [NET] android_getaddrinfofornet+,hn 7(0x302e302e302e30),sn(),hints(known),family 0,flags 4
D/libc    (  399): [NET] android_getaddrinfofornet-, SUCCESS
,D/ConnectivityService(  977): Setting Dns servers for network 101 to [/192.168.1.1]
D/libc    (  977): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
,D/libc    (  977): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  399): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(53),hints(known),family 0,flags 4
D/libc    (  399): [NET] android_getaddrinfofornet-, SUCCESS
,E/WifiStateMachine(  977): handleMessage: E msg.what=131131
E/WifiStateMachine(  977): processMsg: ConnectedState
D/Nat464Xlat(  977): requiresClat: netType=1, connected=true, mIsClatEnabled=true, hasIPv4Address=true
D/ConnectivityService(  977): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
E/WifiStateMachine(  977):  ConnectedState !CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
D/ConnectivityService(  977): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
E/WifiStateMachine(  977): processMsg: L2ConnectedState
D/ConnectivityService(  977): rematching NetworkAgentInfo [WIFI () - 101]
E/WifiStateMachine(  977):  L2ConnectedState !CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
D/ConnectivityService(  977):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/WifiStateMachine(  977): processMsg: ConnectModeState
D/ConnectivityService(  977):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
E/WifiStateMachine(  977):  ConnectModeState !CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
D/ConnectivityService(  977):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/usbnet  (  977): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  977): currentScore = 0, newScore = 20
D/usbnet  (  977):   my score=70, my filter=[ Transports:  Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  977):    accepting network in place of null
D/usbnet  (  977): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
,D/ConnectivityService(  977): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isSkipMobile=false
E/WifiStateMachine(  977): handleMessage: X
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  977): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  977): Connected
D/WIFI    (  977): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  977): EvaluatingState{ when=-1ms what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/WIFI    (  977):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  977): Validated
D/WIFI    (  977): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
D/WIFI_ICON( 1218): WifiActivity: 0
D/libc    (  977): [NET] android_getaddrinfofornet+,hn 25(0x666538303a3a39),sn(),hints(known),family 0,flags 4
D/libc    (  977): [NET] android_getaddrinfofornet-, SUCCESS
D/CSLegacyTypeTracker(  977): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
E/WifiStateMachine(  977): handleMessage: E msg.what=131212
D/ConnectivityService(  977): sendGeneralBroadcast, restrictEnable=false
E/WifiStateMachine(  977): processMsg: ConnectedState
D/ConnectivityService(  977): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
E/WifiStateMachine(  977):  ConnectedState !CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine(  977): processMsg: L2ConnectedState
E/WifiStateMachine(  977):  L2ConnectedState !CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine(  977): processMsg: ConnectModeState
E/WifiStateMachine(  977):  ConnectModeState !CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
D/ConnectivityService(  977): sendGeneralBroadcastDelayed, restrictEnable=false
E/WifiStateMachine(  977): processMsg: DriverStartedState
D/ConnectivityService(  977): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
E/WifiStateMachine(  977):  DriverStartedState !CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
D/ConnectivityService(  977): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.130/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
E/WifiStateMachine(  977): processMsg: SupplicantStartedState
D/PMS     (  977): acquireWL(5e20011): PARTIAL_WAKE_LOCK  NetworkStats 0x1 977 1000 null
E/WifiStateMachine(  977):  SupplicantStartedState !CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
V/NetworkPolicy(  977): ensureActiveMobilePolicyLocked()
E/WifiStateMachine(  977): processMsg: DefaultState
D/ConnectivityService(  977): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/Tethering(  977): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
D/ConnectivityService(  977):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/WifiStateMachine(  977):  DefaultState !CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
D/ConnectivityService(  977):  sending notification for NetworkRequest [ i,d=2, legacyType=-1, [] ]
D/Tethering(  977): TetherMasterSM: InitialState processMessage what=UPSTREAM_CHANGED
D/StatusBar.NetworkController( 1218): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/WifiStateMachine(  977): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.130/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.130/24,fe80::92e7:c4ff:fee6:4cf8/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
D/ConnectivityService(  977): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  977): ValidatedState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  977): Validated NetworkAgentInfo [WIFI () - 101]
E/WifiStateMachine(  977): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
D/ConnectivityService(  977): rematching NetworkAgentInfo [WIFI () - 101]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  977): Validated
D/ConnectivityService(  977):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityManager.CallbackHandler( 1218): CM callback handler got msg 524290
D/ConnectivityService(  977):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  977): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
E/WifiStateMachine(  977): handleMessage: X
D/ConnectivityService(  977): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/WIFI    (  977): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  977):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  977):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  977):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/WIFI    (  977): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
D/ConnectivityService(  977): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  977): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isSkipMobile=false
D/ConnectivityService(  977): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  977): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/usbnet  (  977): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkPolicy(  977): ensureActiveMobilePolicyLocked: SIM state invalid, slotId= -1000, subId=-1000 . Return.
D/usbnet  (  977):   my score=70, my filter=[ Transports:  Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
V/NetworkPolicy(  977): updateNetworkEnabledLocked()
D/usbnet  (  977): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
V/NetworkPolicy(  977): updateIfacesLocked()
V/NetworkPolicy(  977): updateNotificationsLocked()
D/NetworkManagementService(  977): isBandwidthControlEnabled: doneSignal.getCount()= 0
D/WISPrService( 5981): >>>>>WISPrService start isConnected = true<<<<<
D/ConnectivityService(  977): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
D/ConnectivityService(  977): identical MTU - not setting
D/Nat464Xlat(  977): requiresClat: netType=1, connected=true, mIsClatEnabled=true, hasIPv4Address=true
D/ConnectivityService(  977): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  977):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  977):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  977): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/PMS     (  977): releaseWL(5e20011): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/ConnectivityService(  977): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  977):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  977):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  977): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  977): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  977): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  977):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  977):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
I/SecurityController( 1218): onAvailable 101 : [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  977): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityManager.CallbackHandler( 1218): CM callback handler got msg 524290
D/ConnectivityService(  977): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
I/SecurityController( 1218): onAvailable 101 : [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  977):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1218): CM callback handler got msg 524295
D/ConnectivityService(  977):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1218): CM callback handler got msg 524295
D/DATA_ICON( 1218): updateConnectivity android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE Type:1/Status:0
D/ConnectivityManager.CallbackHandler( 1218): CM callback handler got msg 524290
D/ConnectivityService(  977): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
I/SecurityController( 1218): onAvailable 101 : [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/DATA_ICON( 1218): dataConnected: false/false
D/StatusBar.NetworkController( 1218): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
V/NetworkPolicy(  977): updateNetworkEnabledLocked()
I/QuickSettingWifi( 1218): receive.wifiConnect:true wifiAPname:NG700 elapse:1
V/NetworkPolicy(  977): updateNotificationsLocked()
I/QuickSettingWifi( 1218): receive.wifiConnect:true wifiAPname:NG700 elapse:1
D/DATA_ICON( 1218): updateConnectivity android.net.conn.INET_CONDITION_ACTION Type:1/Status:100
D/DATA_ICON( 1218): dataConnected: false/false
D/StatusBar.NetworkController( 1218): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
I/WebViewFactory( 6632): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
,I/LibraryLoader( 6632): Time to load native libraries: 2 ms (timestamps 6363-6365)
I/LibraryLoader( 6632): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6632): Binding Chromium to main looper Looper (main, tid 1) {2f8f335}
I/LibraryLoader( 6632): Expected native library version number "",actual native library version number ""
I/chromium( 6632): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6632): Initializing chromium process, singleProcess=true,
W/art     ( 6632): Attempt to remove local handle scope entry from IRT, ignoring,
,E/SysUtils( 6632): ApplicationContext is null in ApplicationStatus,
,W/chromium( 6632): [WARNING:resource_bundle.cc(285)] locale_file_path.empty(),
,E/libEGL  ( 6632): validate_display:255 error 3008 (EGL_BAD_DISPLAY),
E/libEGL  ( 6632): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6632): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 6632): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6632): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6632): Local Branch: 
I/Adreno-EGL( 6632): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6632): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6632):                  d74aa161a12b9c6fc6332151
,W/AudioManagerAndroid( 6632): Requires BLUETOOTH permission,
,I/NSApplication( 6632): Starting up...
,D/PMS     (  977): acquireWL(e12d28b): PARTIAL_WAKE_LOCK  *alarm* 0x1 977 1000 WorkSource{10024},
V/AlarmManager(  977): sending alarm PendingIntent{1cac2f68: PendingIntentRecord{3e320f81 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=106511, Int=0
V/AlarmManager(  977): sending alarm PendingIntent{22ff617f: PendingIntentRecord{1dab654c android broadcastIntent}}, i=com.android.server.WifiManager.action.START_SCAN, t=1, cnt=1, w=1454460149333, Int=20000
,I/ActivityManager(  977): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6716 uid=10096 gids={50096, 9997, 3003, 1028, 1015} abi=arm64-v8a
,D/Process (  977): killProcessQuiet, pid=6314
,I/ActivityManager(  977): Killing 6314:com.google.android.apps.docs/u0a101 (adj 15): empty #17
D/Process (  977): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,E/WifiStateMachine(  977): handleMessage: E msg.what=131168,
E/WifiStateMachine(  977): processMsg: ConnectedState
E/WifiStateMachine(  977):  ConnectedState !CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  977): processMsg: L2ConnectedState
E/WifiStateMachine(  977):  L2ConnectedState !CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  977): processMsg: ConnectModeState
E/WifiStateMachine(  977):  ConnectModeState !CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  977): processMsg: DriverStartedState
E/WifiStateMachine(  977):  DriverStartedState !CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  977): processMsg: SupplicantStartedState,
E/WifiStateMachine(  977):  SupplicantStartedState !CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  977): processMsg: DefaultState
E/WifiStateMachine(  977):  DefaultState !CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  977): handleMessage: X
,I/ActivityManager(  977): Recipient 6314,
,I/jxcore-log( 6431): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js,
I/jxcore-log( 6431): 
,D/Process (  977): killProcessQuiet, pid=5920,
I/ActivityManager(  977): Killing 5920:com.google.android.googlequicksearchbox:search/u0a85 (adj 15): empty #17
D/Process (  977): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,W/art     ( 6076): Suspending all threads took: 16.385ms
,I/ActivityManager(  977): Recipient 5920
,D/PMS     (  977): acquireWL(186f22bd): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1965 10024 WorkSource{10024 com.google.android.gms}
,E/WifiStateMachine(  977): WiFiStateMachine SCAN ALARM
D/WifiDisplayAdapter(  977): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  977):     Client/Owner: Client
,D/WifiDisplayAdapter(  977):     GroupId: 
D/WifiDisplayAdapter(  977):     Passphrase: 
D/WifiDisplayAdapter(  977):     SessionId: 0
D/WifiDisplayAdapter(  977):     IP Address: }
E/WifiStateMachine(  977): handleMessage: E msg.what=131143
D/PMS     (  977): releaseWL(e12d28b): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
E/WifiStateMachine(  977): processMsg: ConnectedState
E/WifiStateMachine(  977):  ConnectedState !CMD_START_SCAN -2 -2 ic=5 proc(ms):2 dur:2127 rssi=-57 f=2412 sc=60 link=72 tx=101.5, 0.0, 0.0  rx=151.5 fiv=40000 [on:0 tx:0 rx:0 period:2271] from screen [on:0 period:-1533763400]
E/WifiStateMachine(  977): processMsg: L2ConnectedState
,E/WifiStateMachine(  977):  L2ConnectedState !CMD_START_SCAN -2 -2 ic=5 proc(ms):3 dur:2127 rssi=-57 f=2412 sc=60 link=72 tx=101.5, 0.0, 0.0  rx=151.5 fiv=40000 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1533763398]
E/WifiStateMachine(  977): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=101.50 rxSuccessRate=151.50 targetRoamBSSID=c0:ff:d4:d3:aa:48 RSSI=-57
E/WifiStateMachine(  977): WifiStateMachine CMD_START_SCAN with age=9852 interval=40000 maxinterval=300000
E/WifiStateMachine(  977): WifiStateMachine CMD_START_SCAN prevent full band scan due to pkt rate
E/WifiStateMachine(  977): WifiStateMachine CMD_START_SCAN source -2 ...and ignore scans tx=101.50 rx=151.50
D/libc    ( 1965): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
D/libc    ( 1965): [NET] android_getaddrinfofornet-, err=8
E/WifiStateMachine(  977): handleMessage: X
,D/libc    ( 1965): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    ( 1965): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1965): [NET] android_getaddrinfo_proxy+
,D/libc    ( 1965): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  399): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    (  399): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,D/libc    (  399): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  399): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 1965): [NET] android_getaddrinfo_proxy-, success
,D/libc    ( 1965): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4,
D/libc    ( 1965): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 1965): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4,
D/libc    ( 1965): [NET] android_getaddrinfofornet-, err=8
,E/WifiTrafficPoller(  977): TRAFFIC_STATS_POLL true Token 24 num clients 8,
,E/WifiTrafficPoller(  977): TRAFFIC_STATS_POLL true Token 24 num clients 8,
D/WIFI_ICON( 1218): WifiActivity: 3
E/WifiTrafficPoller(  977):  packet count Tx=212 Rx=310
D/StatusBar.NetworkController( 1218): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
E/WifiTrafficPoller(  977): notifying of data activity 3
,D/PMS     (  977): releaseWL(2a9c907e): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null,
D/ConnectivityService(  977): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,D/AccTypeManager( 1737): Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
,D/PMS     (  977): acquireWL(1f1590b2): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 5807 10112 null
,W/SystemReader(  977): Cannot find grip_rejection_width, use default value instead
D/AccTypeManager( 1737): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,W/Prism.AllAppsManager( 1587): AllAppsMgr addApps, already exist: ApplicationInfo(id=33, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
,D/PMS     (  977): acquireWL(213d57ac): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1965 10024 WorkSource{10024 com.google.android.gms}
I/Prism.ItemManager( 1587): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
W/ResourcesManager(  977): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
D/GCM     ( 1965): Connected
I/Prism.ItemManager( 1587): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,D/PMS     (  977): releaseWL(186f22bd): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,I/ActivityManager(  977): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=6752 uid=10085 gids={50085, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=arm64-v8a
,I/Launcher( 1587): Deferring update until onResume,
,D/Launcher( 1587): waitUntilResume // bindAppsUpdated
D/PMS     (  977): releaseWL(213d57ac): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms}
D/AccTypeManager( 1737): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
D/PMS     (  977): releaseWL(1f1590b2): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
D/PhoneApp( 1542): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
E/ExternalAccountType( 1737): Unsupported attribute readOnly
,I/ActivityManager(  977): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=6775 uid=10076 gids={50076, 9997} abi=arm64-v8a
D/PMS     (  977): acquireWL(2ccac3e3): PARTIAL_WAKE_LOCK  *alarm* 0x1 977 1000 WorkSource{10076}
,V/AlarmManager(  977): sending alarm PendingIntent{3e96c1e0: PendingIntentRecord{2882fc99 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1454460150288, Int=60000
,W/PackageManager(  977): Unable to load service info ResolveInfo{220be1c2 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000},
W/PackageManager(  977): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  977): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:475)
W/PackageManager(  977): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:331)
W/PackageManager(  977): 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
W/PackageManager(  977): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  977): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
W/PackageManager(  977): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
W/PackageManager(  977): 	at android.os.Handler.handleCallback(Handler.java:739)
W/PackageManager(  977): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  977): 	at android.os.Looper.loop(Looper.java:155)
W/PackageManager(  977): 	at com.android.server.SystemServer.run(SystemServer.java:324)
W/PackageManager(  977): 	at com.android.server.SystemServer.main(SystemServer.java:225)
W/PackageManager(  977): 	at java.lang.reflect.Method.invoke(Native Method)
W/PackageManager(  977): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/PackageManager(  977): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
W/PackageManager(  977): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,D/SMSBackup( 6775): SMSBackupAgentService started
D/SMSBackup( 6775): Checking restore status
D/SMSBackup( 6775): Restore complete
D/SMSBackup( 6775): cancelCheckAlarm
,D/SMSBackup( 6775): SMSBackupAgentService completed: completed in 0.0 seconds
,V/GmsNetworkLocationProvi( 1848): DISABLE
,I/jxcore-log( 6431): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 6431): 
,I/GCoreNlp( 1848): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/BackupManagerService(  977): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,D/PMS     (  977): releaseWL(2ccac3e3): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10076}
,D/LocationProviderProxy(  977): applying state to connected service
D/PMS     (  977): acquireWL(2810939): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1848 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  977): releaseWL(2810939): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,D/LocationProviderProxy(  977): applying state to connected service
,D/PMS     (  977): acquireWL(39dffff5): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1848 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  977): releaseWL(39dffff5): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  977): acquireWL(14c2d1c4): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1848 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  977): releaseWL(14c2d1c4): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms},
D/PMS     (  977): acquireWL(347538ad): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1848 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  977): releaseWL(347538ad): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  977): acquireWL(2359b2a9): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1965 10024 WorkSource{10024 com.google.android.gms},
,I/jxcore-log( 6431): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js,
I/jxcore-log( 6431): 
,I/jxcore-log( 6431): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js,
I/jxcore-log( 6431): 
,D/GCM     ( 1965): Message class com.google.f.a.a.p,
,I/jxcore-log( 6431): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 6431): 
,D/LocationManagerService(  977): getProviders()=[passive]
,D/PMS     (  977): releaseWL(2359b2a9): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms}
,I/ActivityManager(  977): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=6804 uid=10027 gids={50027, 9997, 3003} abi=arm64-v8a,
,I/art     (  411): Explicit concurrent mark sweep GC freed 8651(367KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 163us total 19.980ms
,I/[PluginManager]RegisterService( 1659): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
I/[PluginManager]RegisterService( 1659): handle notify Blinkfeed plugin client changed
,D/Process (  977): killProcessQuiet, pid=5711,
I/ActivityManager(  977): Killing 5711:com.android.defcontainer/u0a15 (adj 15): empty #17
D/Process (  977): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.attachApplicationLocked:6650 
,I/art     (  411): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 143us total 16.795ms
,I/art     (  411): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 122us total 16.240ms,
,E/WifiStateMachine(  977): handleMessage: E msg.what=131155,
I/ActivityManager(  977): Recipient 5711
E/WifiStateMachine(  977): processMsg: ConnectedState
E/WifiStateMachine(  977):  ConnectedState !CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=101.5, 0.0, 0.0  rx=151.5 bcn=0 [on:0 tx:0 rx:0 period:727] from screen [on:0 period:-1533762670] gl hn u24 rssi=-52 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,E/WifiStateMachine(  977): processMsg: L2ConnectedState
E/WifiStateMachine(  977):  L2ConnectedState !CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=101.5, 0.0, 0.0  rx=151.5 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1533762669] gl hn u24 rssi=-52 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  977):  get link layer stats 0
W/WifiHW  (  977): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1328): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1328): environment dirty rate=0 [12][0][0],
E/WifiStateMachine(  977): fetchRssiLinkSpeedAndFrequencyNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  977): fetchRssiLinkSpeedAndFrequencyNative rssi=-57 linkspeed=72
E/WifiStateMachine(  977): BroadcastRSSIForIMS, newrssi =-57 , oldRssi= -200
,E/WifiConfigStore(  977): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-57 "NG700"WPA_PSK
E/WifiStateMachine(  977): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=56.75 txretriesrate=0.00 rxrate=82.25 userTriggerdPenalty0
E/WifiStateMachine(  977):  good link -> stuck count =0
E/WifiStateMachine(  977):  badRSSI count0 lowRSSI count0 --> score 60
E/WifiStateMachine(  977):  isHighRSSI       ---> score=65
,D/WifiWatchdogStateMachine(  977): RSSI current: 3 new: -57, 3
,D/WIFI_ICON( 1218): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1218): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
D/WifiWatchdogStateMachine(  977): RSSI current: 3 new: -57, 3
D/WIFI_ICON( 1218): updateWifiState: RSSI_CHANGED 3 -> 3
E/WifiStateMachine(  977): handleMessage: X
D/StatusBar.NetworkController( 1218): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/PackageBroadcastService( 4446): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 4446): Null package name or gms related package.  Ignoreing.
,D/PMS     (  977): acquireWL(21340de1): PARTIAL_WAKE_LOCK  AsyncService 0x1 6076 10167 null
,D/PMS     (  977): acquireWL(21e033f4): PARTIAL_WAKE_LOCK  Icing 0x1 4446 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  977): acquireWL(1f02a71d): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 6076 10167 null
,D/PMS     (  977): releaseWL(21340de1): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,I/Icing   ( 4446): updateResources: need to parse f{com.google.android.gms}
,D/PMS     (  977): releaseWL(1f02a71d): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 null
,I/UpdateIcingCorporaServi( 6752): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,D/PMS     (  977): releaseWL(21e033f4): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms}
,I/UpdateIcingCorporaServi( 6752): UpdateCorporaTask done [took 111 ms] updated apps [took 111 ms] ,
,E/WifiTrafficPoller(  977): TRAFFIC_STATS_POLL true Token 24 num clients 8,
E/WifiTrafficPoller(  977):  packet count Tx=215 Rx=316
,I/Prism.ItemManager( 1587): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true,
I/Prism.ItemManager( 1587): loadItems() com.htc.launcher.pageview.WidgetManager@16607fb2 +
I/Prism.WidgetManager( 1587): onLoadItems() +
,W/ResourcesManager( 1587): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.,
,W/ResourcesManager( 1587): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.,
,W/asset   ( 1587): Copying FileAsset 0x55a9aae700 (zip:/data/app/com.gameloft.android.gdc-2/base.apk:/resources.arsc) to buffer size 405676 to make it aligned.,
,E/Prism.WidgetManager( 1587): The same lists. No need to update. skip it.,
I/Prism.WidgetManager( 1587): onLoadItems() -
I/Prism.ItemManager( 1587): loadItems() com.htc.launcher.pageview.WidgetManager@16607fb2 -
,D/libc    (  977): [NET] android_getaddrinfofornet+,hn 11(0x7777772e687463),sn(),hints(known),family 0,flags 4
D/libc    (  977): [NET] android_getaddrinfofornet-, err=8
D/libc    (  977): [NET] android_getaddrinfofornet+,hn 11(0x7777772e687463),sn(),hints(known),family 0,flags 1024
D/libc    (  977): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  977): [NET] android_getaddrinfo_proxy+
D/libc    (  977): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  399): [NET] android_getaddrinfofornet+,hn 11(0x7777772e687463),sn(),hints(known),family 0,flags 1024
D/libc    (  399): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,E/WifiTrafficPoller(  977): TRAFFIC_STATS_POLL true Token 24 num clients 8
D/WIFI_ICON( 1218): WifiActivity: 2
E/WifiTrafficPoller(  977):  packet count Tx=216 Rx=316
E/WifiTrafficPoller(  977): notifying of data activity 2
,D/StatusBar.NetworkController( 1218): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_out_4 (gone) T]
,D/ConnectivityService(  977): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider(  977): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
I/AlarmManager(  977): [AlarmQueuing] connectivity wifi: true
D/PMS     (  977): acquireWL(1ed41363): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 977 1000 null
D/PMS     (  977): acquireWL(1fc69b60): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 977 1000 null
D/PMS     (  977): releaseWL(1fc69b60): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
I/ConnectivityHelper( 1587): [onReceive] WIFI(1): CONNECTED
D/GpsLocationProvider(  977): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  977): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
,D/htcCheckinService(  977): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
D/htcCheckinService(  977): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
,E/GpsLocationProvider(  977): No APN found to select.
,D/PMS     (  977): releaseWL(1ed41363): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/libc    (  399): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  399): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  977): [NET] android_getaddrinfo_proxy-, success
D/HtcWifiWanDetect(  977): Find DNS Address www.htc.com/23.59.123.86
,I/NetworkMonitor( 6584): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 6584): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/AutoSetting( 1659): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/MobileConnectivityChangeReceiver( 6491): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) },
D/MobileConnectivityChangeReceiver( 6491): onReceive CONNECTIVITY_CHANGE networkType=1
,D/PhoneApp( 1542): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1542): -- N1 =0
D/PhoneApp( 1542): -- N2 =0
D/PhoneApp( 1542): -- N3 =0
,I/art     (  977): Explicit concurrent mark sweep GC freed 39778(2MB) AllocSpace objects, 1(20KB) LOS objects, 33% free, 17MB/25MB, paused 1.809ms total 150.022ms
D/MdScPhnSt( 6550): [296.1.]  listen tmrbb8
,D/AutoSetting( 1659): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/AutoSetting( 1659): Util - check NLP state, Allowned:false, Enabled:false
D/AutoSetting( 1659): service - requestNLP() NetworkLocationProvider not enabled
D/AutoSetting( 1659): service - onStartCommand() REMOVE current location bundle
D/AutoSetting( 1659): service - handleMessage() setting current location null
,I/PackageManager(  977):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=4446, uid=10024, userID:0
,I/iu.Environment( 4446): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 4446): num queued entries: 0
I/iu.UploadsManager( 4446): num updated entries: 0
I/iu.SyncManager( 4446): NEXT; no task
D/PMS     (  977): acquireWL(cce8bdb): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1965 10024 WorkSource{10024 com.google.android.gms}
D/MdScDataSum( 6550): [296.1.] summary 118:p1 ignore
D/ChimeraCfgMgr( 4446): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ConnectivityService(  977): reportBadNetwork(NetworkAgentInfo [WIFI () - 101]) by 10024
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  977): ValidatedState{ when=0 what=532488 arg1=10024 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  977): DefaultState{ when=0 what=532488 arg1=10024 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  977): Validated NetworkAgentInfo [WIFI () - 101]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  977): Forcing reevaluation
D/ConnectivityService(  977): rematching NetworkAgentInfo [WIFI () - 101]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  977): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  977):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  977): Validated
D/ConnectivityService(  977):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1218): CM callback handler got msg 524290
D/ConnectivityService(  977): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ChimeraCfgMgr( 4446): Loading module com.google.android.gms.kids from APK com.google.android.gms
D/ConnectivityService(  977): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  977):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  977):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  977): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/PMS     (  977): releaseWL(cce8bdb): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms}
I/SecurityController( 1218): onAvailable 101 : [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/libc    ( 5807): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 4
D/libc    ( 5807): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 5807): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
D/libc    ( 5807): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 5807): [NET] android_getaddrinfo_proxy+
D/libc    ( 5807): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  399): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
D/libc    (  399): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,D/libc    (  399): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  399): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 5807): [NET] android_getaddrinfo_proxy-, success
I/GLSUser ( 1965): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 1965): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1965): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1965): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1965): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/Kids    ( 4446): [AccountUtils] Account not ready
W/Kids    ( 4446): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 4446): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 4446): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 4446): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 4446): 	at com.google.android.gms.auth.p.b(SourceFile:477)
,W/Kids    ( 4446): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 4446): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 4446): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 4446): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 4446): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 4446): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 4446): 	at java.lang.Thread.run(Thread.java:818)
,D/DotMatrix( 1329): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true,
D/DotMatrix( 1329): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1218): reapply : com.google.android.gms 1 40
,I/Babel   ( 5807): connection state changed from DISCONNECTED to CONNECTED
,E/WifiTrafficPoller(  977): TRAFFIC_STATS_POLL true Token 24 num clients 8
,E/WifiTrafficPoller(  977):  packet count Tx=224 Rx=322
D/WIFI_ICON( 1218): WifiActivity: 3
E/WifiTrafficPoller(  977): notifying of data activity 3
D/StatusBar.NetworkController( 1218): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/PMS     (  977): acquireWL(2fd1f1bc): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 6584 10159 null,
,D/PMS     (  977): acquireWL(387dcf2): PARTIAL_WAKE_LOCK  *alarm* 0x1 977 1000 WorkSource{10024},
V/AlarmManager(  977): sending alarm PendingIntent{3b56ff43: PendingIntentRecord{3e320f81 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=110391, Int=0
,I/PackageManager(  977):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=6584, uid=10159, userID:0,
,D/PMS     (  977): releaseWL(2fd1f1bc): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
,I/MusicLeanback( 6584): Conditions not met for autocaching. okToAttempt=false
I/MusicLeanback( 6584): Stop autocaching.,
,D/PMS     (  977): acquireWL(335341ec): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1965 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  977): releaseWL(387dcf2): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10024}
D/WearableService( 4819): callingUid 10024, callindPid: 4819
,D/libc    ( 1965): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
D/libc    ( 1965): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1965): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    ( 1965): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1965): [NET] android_getaddrinfo_proxy+
D/libc    ( 1965): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  399): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    (  399): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,D/libc    (  399): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  399): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 1965): [NET] android_getaddrinfo_proxy-, success
,E/GmsUtils( 6584): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
E/GmsUtils( 6584): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/libc    ( 1965): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4,
D/libc    ( 1965): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 1965): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4,
D/libc    ( 1965): [NET] android_getaddrinfofornet-, err=8
,E/WifiStateMachine(  977): handleMessage: E msg.what=131155,
E/WifiStateMachine(  977): processMsg: ConnectedState
E/WifiStateMachine(  977):  ConnectedState !CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=56.8, 0.0, 0.0  rx=82.2 bcn=0 [on:0 tx:0 rx:0 period:2994] from screen [on:0 period:-1533759636] gl hn u24 rssi=-52 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  977): processMsg: L2ConnectedState
E/WifiStateMachine(  977):  L2ConnectedState !CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=56.8, 0.0, 0.0  rx=82.2 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1533759635] gl hn u24 rssi=-52 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  977):  get link layer stats 0
W/WifiHW  (  977): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1328): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1328): environment dirty rate=6 [16][1][0]
E/WifiStateMachine(  977): fetchRssiLinkSpeedAndFrequencyNative RSSI = -58 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WIFI_ICON( 1218): updateWifiState: RSSI_CHANGED 3 -> 3
E/WifiStateMachine(  977): fetchRssiLinkSpeedAndFrequencyNative rssi=-58 linkspeed=72
D/StatusBar.NetworkController( 1218): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
E/WifiStateMachine(  977): fetchRssiLinkSpeedAndFrequencyNative send RSSIChange intent, SameSignalLevelCount =1
E/WifiConfigStore(  977): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-57 "NG700"WPA_PSK
D/WifiWatchdogStateMachine(  977): RSSI current: 3 new: -58, 3
,E/WifiStateMachine(  977): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=36.38 txretriesrate=0.00 rxrate=46.12 userTriggerdPenalty0,
E/WifiStateMachine(  977):  good link -> stuck count =0
E/WifiStateMachine(  977):  badRSSI count0 lowRSSI count0 --> score 60
E/WifiStateMachine(  977):  isHighRSSI       ---> score=65
,D/WifiWatchdogStateMachine(  977): RSSI current: 3 new: -58, 3
E/WifiStateMachine(  977): handleMessage: X
D/WIFI_ICON( 1218): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1218): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/PMS     (  977): acquireWL(602184a): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1965 10024 WorkSource{10024 com.google.android.gms}
,D/GCM     ( 1965): Connected
D/PMS     (  977): releaseWL(335341ec): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  977): releaseWL(602184a): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  977): acquireWL(58713bb): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1965 10024 WorkSource{10024 com.google.android.gms}
,D/GCM     ( 1965): Message class com.google.f.a.a.p
,D/PMS     (  977): releaseWL(58713bb): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms}
,E/WifiDataStallTracker(  977): DATA_MONITOR_POLL true Token 3
,D/WifiDataStallTracker(  977): updateDataStallInfo: mDataStallTxRxSum={txSum=207 rxSum=195} preTxRxSum={txSum=0 rxSum=0}
D/WifiDataStallTracker(  977): updateDataStallInfo: IN/OUT
D/WifiDataStallTracker(  977): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,E/WifiTrafficPoller(  977): TRAFFIC_STATS_POLL true Token 24 num clients 8
E/WifiTrafficPoller(  977):  packet count Tx=234 Rx=331
,E/WifiTrafficPoller(  977): TRAFFIC_STATS_POLL true Token 24 num clients 8
D/WIFI_ICON( 1218): WifiActivity: 1
E/WifiTrafficPoller(  977):  packet count Tx=234 Rx=332
,D/StatusBar.NetworkController( 1218): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
E/WifiTrafficPoller(  977): notifying of data activity 1
,I/PMS     (  977): Going to sleep due to screen timeout (uid 1000)...,
,I/SensorManager(  977): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@2695a981
W/SensorService(  977): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  977): disable: get sensor name = Accelerometer Sensor
W/SensorService(  977): pid=977, uid=1000
W/SensorService(  977): Active sensors: size = 4
W/SensorService(  977): Accelerometer Sensor (handle=0x00000000, connections=1)
W/SensorService(  977): CM32181 Light sensor (handle=0x00000003, connections=1)
W/SensorService(  977): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  977): Significant Motion (handle=0x0000000d, connections=1)
W/PMN     (  977): goingToSleep
W/SensorService(  977): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@2695a981, eanble = 0, strlen(mName) = 91
W/SensorService(  977): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  977): Listener[0] = com.android.server.display.AutomaticBrightnessController$1@2e845039
,W/SensorService(  977): Listener[1] = com.htc.smartdim.sensor_eye@36fde1ba
W/SensorService(  977): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/HtcLockScreen( 1218): KeyguardViewMediator: doKeyguard: not showing because lockscreen is off
,W/PMS     (  977): mWirelessDisplayManager is null
,D/PMS     (  977): acquireWL(2890d8): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 977 1000 null,
W/PMN     (  977): goingToSleep done
I/PMS     (  977): Sleeping (uid 1000)...
D/XAN-DPS (  977): prepareColorFade 1
W/PMS     (  977): mWirelessDisplayManager is still null
D/AlarmManager(  977): ACTION_SCREEN_ON
D/PMS     (  977): releaseWL(2890d8): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
W/HtcSystemUPManager(  977): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
I/AlarmManager(  977): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  977): [AlarmQueuing] done recovering
I/AlarmManager(  977): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  977): [AlarmQueuing] done EPS screen off alarm recovering
,E/WifiTrafficPoller(  977): ENABLE_TRAFFIC_STATS_POLL true Token 24
,E/WifiTrafficPoller(  977):  packet count Tx=234 Rx=332
E/WifiTrafficPoller(  977): notifying of data activity 0
,E/WifiDataStallTracker(  977): ENABLE_DATA_MONITOR_POLL true Token 3
,D/WifiDataStallTracker(  977): updateDataStallInfo: mDataStallTxRxSum={txSum=207 rxSum=195} preTxRxSum={txSum=207 rxSum=195}
D/WifiDataStallTracker(  977): updateDataStallInfo: NONE
D/WifiDataStallTracker(  977): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,D/WIFI_ICON( 1218): WifiActivity: 0
,D/StatusBar.NetworkController( 1218): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,E/WifiStateMachine(  977): handleMessage: E msg.what=131167
E/WifiStateMachine(  977): processMsg: ConnectedState
E/WifiStateMachine(  977):  ConnectedState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  977): processMsg: L2ConnectedState
E/WifiStateMachine(  977):  L2ConnectedState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  977): processMsg: ConnectModeState
E/WifiStateMachine(  977):  ConnectModeState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  977): processMsg: DriverStartedState
E/WifiStateMachine(  977):  DriverStartedState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  977): processMsg: SupplicantStartedState
E/WifiStateMachine(  977):  SupplicantStartedState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  977): processMsg: DefaultState
E/WifiStateMachine(  977):  DefaultState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  977):  handleScreenStateChanged Enter: screenOn=true mCurrentScanAlarmMs = 20000 mUserWantsSuspendOpt=false state ConnectedState suppState:CompletedState
W/WifiHW  (  977): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/Adreno-EGL(  977): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL(  977): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL(  977): Build Date: 03/09/15 Mon
I/Adreno-EGL(  977): Local Branch: 
I/Adreno-EGL(  977): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL(  977): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL(  977):                  d74aa161a12b9c6fc6332151
D/wpa_supplicant( 1328): wlan0: Control interface command 'SET_SCREEN_ON 1'
I/wpa_supplicant( 1328): SET_SCREEN_ON:On
I/wpa_supplicant( 1328): htc_wext_set_keepalive +
I/wpa_supplicant( 1328): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1328): getPrivFuncNum +	
I/wpa_supplicant( 1328): getPrivFuncNum -, cmd = 0x8bf6
D/WifiDisplayAdapter(  977): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  977):     Client/Owner: Client
D/WifiDisplayAdapter(  977):     GroupId: 
D/WifiDisplayAdapter(  977):     Passphrase: 
D/WifiDisplayAdapter(  977):     SessionId: 0
,D/WifiDisplayAdapter(  977):     IP Address: }
I/wpa_supplicant( 1328): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1328): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1328): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1328): htc_wext_set_TX_TRACKING - ret = 0
E/WifiStateMachine(  977): setScanAlarm true period 20000 initial delay 200mAlarmEnabledtrue
D/WifiStateMachine(  977): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine(  977): handleScreenStateChanged Exit: true
E/WifiStateMachine(  977): handleMessage: X
E/WifiStateMachine(  977): handleMessage: E msg.what=131154
E/WifiStateMachine(  977): processMsg: ConnectedState
E/WifiStateMachine(  977):  ConnectedState !CMD_ENABLE_RSSI_POLL 1 0
E/WifiStateMachine(  977): processMsg: L2ConnectedState
E/WifiStateMachine(  977):  L2ConnectedState !CMD_ENABLE_RSSI_POLL 1 0
W/WifiHW  (  977): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1328): wlan0: Control interface command 'SIGNAL_POLL'
,V/SRS_Proc(  405): ParamSet string: screen_state=on,
E/audio_a2dp_hw(  405): adev_set_parameters: ERROR: set param called even when stream out is null
,D/WifiController(  977): handleMessage: E msg.what=155650
,D/WifiController(  977): processMsg: DeviceActiveState
D/WifiController(  977): processMsg: StaEnabledState
D/WifiController(  977): processMsg: DefaultState
D/WifiController(  977): handleMessage: X
,I/wpa_supplicant( 1328): environment dirty rate=0 [3][0][0],
E/WifiStateMachine(  977): fetchRssiLinkSpeedAndFrequencyNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  977): fetchRssiLinkSpeedAndFrequencyNative rssi=-57 linkspeed=72
E/WifiStateMachine(  977): fetchRssiLinkSpeedAndFrequencyNative send RSSIChange intent, SameSignalLevelCount =2
,E/WifiConfigStore(  977): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-57 "NG700"WPA_PSK
D/WIFI_ICON( 1218): updateWifiState: RSSI_CHANGED 3 -> 3
E/WifiStateMachine(  977): handleMessage: X
D/StatusBar.NetworkController( 1218): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/WifiStateMachine(  977): handleMessage: E msg.what=131127
E/WifiStateMachine(  977): processMsg: ConnectedState
E/WifiStateMachine(  977):  ConnectedState !CMD_ENABLE_ALL_NETWORKS 0 0
E/WifiStateMachine(  977): processMsg: L2ConnectedState
E/WifiStateMachine(  977):  L2ConnectedState !CMD_ENABLE_ALL_NETWORKS 0 0
E/WifiStateMachine(  977): processMsg: ConnectModeState
E/WifiStateMachine(  977):  ConnectModeState !CMD_ENABLE_ALL_NETWORKS 0 0
E/WifiStateMachine(  977): handleMessage: X
E/WifiStateMachine(  977): handleMessage: E msg.what=131129
E/WifiStateMachine(  977): processMsg: ConnectedState
E/WifiStateMachine(  977):  ConnectedState !CMD_CLEAR_BLACKLIST 0 0
E/WifiStateMachine(  977): processMsg: L2ConnectedState
D/NetworkPolicy(  977): updateScreenOn: false
E/WifiStateMachine(  977):  L2ConnectedState !CMD_CLEAR_BLACKLIST 0 0
V/NetworkPolicy(  977): updateIfacesLocked()
E/WifiStateMachine(  977): processMsg: ConnectModeState
E/WifiStateMachine(  977):  ConnectModeState !CMD_CLEAR_BLACKLIST 0 0
W/WifiHW  (  977): QCOM Debug wifi_send_command "IFNAME=wlan0 BLACKLIST clear"
D/wpa_supplicant( 1328): wlan0: Control interface command 'BLACKLIST clear'
E/wpa_supplicant( 1328): wlan0: BLACKLIST CLEAR 
D/WifiWatchdogStateMachine(  977): RSSI current: 3 new: -57, 3
D/WifiMonitor(  977): Event [IFNAME=wlan0 BLACKLIST CLEAR ]
E/WifiMonitor(  977): WifiMonitor:wlan0 cnt=45 dispatchEvent: BLACKLIST CLEAR 
E/WifiStateMachine(  977): handleMessage: X
D/GpsLocationProvider(  977): receive broadcast intent, action: android.intent.action.SCREEN_ON
,D/NetworkManagementService(  977): isBandwidthControlEnabled: doneSignal.getCount()= 0
,D/DotMatrix( 1329): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false,
,I/IntentController( 1218): receive(android.intent.action.SCREEN_ON,1,false)
,I/ActivityManager(  977): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=6866 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a,
,D/Process (  977): killProcessQuiet, pid=5457
I/ActivityManager(  977): Killing 5457:com.htc.mediamanager/u0a28 (adj 15): empty #17
D/Process (  977): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,D/XAN-DPS (  977): prepareColorFade done
,D/XAN-DPS (  977): setBrightness to 0
,I/SensorManager(  977): unregisterListenerImpl++: listener = com.android.server.display.AutomaticBrightnessController$1@2e845039
,W/SensorService(  977): Following SensorService logs are not warning, just make sure they are printed
I/DisplayManagerService(  977): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 442.451 x 443.345 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
W/SensorService(  977): disable: get sensor name = CM32181 Light sensor
D/DotMatrix( 1329): [EventService]  onDisplayChanged: 0
V/ActivityManager(  977): Display changed displayId=0
E/JavaBinder(  977): !!! FAILED BINDER TRANSACTION !!!
,W/SensorService(  977): pid=977, uid=1000
W/DisplayManagerService(  977): Failed to notify process 5457 that displays changed, assuming it died.
W/DisplayManagerService(  977): android.os.TransactionTooLargeException
W/DisplayManagerService(  977): 	at android.os.BinderProxy.transactNative(Native Method)
W/DisplayManagerService(  977): 	at android.os.BinderProxy.transact(Binder.java:504)
W/DisplayManagerService(  977): 	at android.hardware.display.IDisplayManagerCallback$Stub$Proxy.onDisplayEvent(IDisplayManagerCallback.java:81)
W/DisplayManagerService(  977): 	at com.android.server.display.DisplayManagerService$CallbackRecord.notifyDisplayEventAsync(DisplayManagerService.java:1143)
W/DisplayManagerService(  977): 	at com.android.server.display.DisplayManagerService.deliverDisplayEvent(DisplayManagerService.java:977)
W/DisplayManagerService(  977): 	at com.android.server.display.DisplayManagerService.access$500(DisplayManagerService.java:120)
W/DisplayManagerService(  977): 	at com.android.server.display.DisplayManagerService$DisplayManagerHandler.handleMessage(DisplayManagerService.java:1072)
W/DisplayManagerService(  977): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/DisplayManagerService(  977): 	at android.os.Looper.loop(Looper.java:155)
W/DisplayManagerService(  977): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/DisplayManagerService(  977): 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
W/SensorService(  977): Active sensors: size = 3
W/SensorService(  977): Accelerometer Sensor (handle=0x00000000, connections=1)
W/SensorService(  977): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  977): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  977): SensorService::listenerSensor++: mName = com.android.server.display.AutomaticBrightnessController$1@2e845039, eanble = 0, strlen(mName) = 67
W/SensorService(  977): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  977): Listener[0] = com.htc.smartdim.sensor_eye@36fde1ba
W/SensorService(  977): void android::SensorService::listenerSensor(const char*, int32_t)--:
,E/qdutils (  387): int qdutils::getHDMINode(): Failed to open fb node 2
E/qdutils (  387): int qdutils::getHDMINode(): Failed to find HDMI node
,I/ActivityManager(  977): Recipient 5457
,D/DotMatrix( 1329): [EventService] mbHDMIConnect: false, mCoverOn:false
,D/PMS     (  977): acquireWL(346d66a2): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1848 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  977): releaseWL(346d66a2): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,D/Process (  977): killProcessQuiet, pid=6369,
I/ActivityManager(  977): Killing 6369:com.google.android.gms.unstable/u0a24 (adj 15): empty #17
D/Process (  977): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  977): Recipient 6369
,E/qdutils (  387): int qdutils::getHDMINode(): Failed to open fb node 2
D/PMS     (  977): Setting HAL interactive mode to false
E/qdutils (  387): int qdutils::getHDMINode(): Failed to find HDMI node
D/PMS     (  977): Setting HAL interactive mode to false done
D/SurfaceControl(  977): Excessive delay in setPowerMode(): 293ms
D/PMS     (  977): Setting HAL auto-suspend mode to true
D/PMS     (  977): Setting HAL auto-suspend mode done
,D/PMS     (  977): acquireWL(2b263f33): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 977 1000 null,
I/BatteryService(  977): n_update end
,D/PMS     (  977): releaseWL(2b263f33): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/HtcSystemUPManager(  977): HtcSystemUPHandler The policy is disabled. AppId: UTD_BI, category: C0006,
,D/PMS     (  977): acquireWL(1afca2f0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1848 10024 WorkSource{10024 com.google.android.gms}
I/InputMethodManagerService(  977): screenObserver, isScreenOn=false
I/InputMethodManager( 6431): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{34870999 VFEDH.C. .F...... 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@3c402d6b
D/StatusBarManagerService(  977): swetImeWindowStatus vis=0 backDisposition=0
I/PhoneStatusBar( 1218): setImeWindowStatus(false,false)
,I/InputMethodManagerService(  977): Disable input method client, pid=6431
W/ContextImpl( 6866): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
D/HtcPowerSaver(  977): updateBatteryInfo
D/NotificationService(  977): plugged=true pluggin=true
,D/UsbnetService(  977): BroadcastReceiver::onReceive+
D/PMS     (  977): runPSCheck
D/UsbnetService(  977): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  977): Checking...
D/UsbnetService(  977):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/HtcPowerSaver(  977): >> updateStatus
D/UsbnetService(  977): BroadcastReceiver::onReceive-
D/WifiController(  977): battery changed pluggedType: 2
D/WifiController(  977): handleMessage: E msg.what=155652
D/HABCtrl (  977): TPE algorithm. remove timeout.
D/WifiController(  977): processMsg: DeviceActiveState
D/PMS     (  977): OOBE c monitor 11
D/WifiController(  977): processMsg: StaEnabledState
D/PowerUI ( 1218): closing low battery warning: level=100
D/WifiController(  977): processMsg: DefaultState
,I/HtcPowerSaver(  977): updateStatus (8000,100,-1,false,false,false,-1)
D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  977): << updateStatus
D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1218): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1329): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  977): releaseWL(1afca2f0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
D/WifiController(  977): handleMessage: X
D/HeadsetStateMachine( 3124): Disconnected process message: 10, size: 0
I/IntentController( 1218): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/NfcService( 1556): ScreenObserver: OFF
,D/NfcService( 1556): applyRouting - 0
D/PMS     (  977): acquireWL(1b5f4aee): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1556 1027 null
,D/NfcService( 1556): applyRouting -2
,D/NfcService( 1556): applyRouting
D/NfcService( 1556): Ignore this applyRouting...
D/PMS     (  977): releaseWL(1b5f4aee): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,W/ContextImpl( 6866): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:22 android.app.ActivityThread.handleReceiver:2712 ,
,D/PowerUsageList:PowerUsageHelper( 6866): MY_DEBUG = false
,I/InputManager(  977): Cancel all due to getting PMS screen off broadcast. ActualScreenOn=false
,I/IntentController( 1218): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false),
,D/AlarmManager(  977): ACTION_SCREEN_OFF
,I/AlarmManager(  977): [AlarmQueuing] screen off now: 
I/AlarmManager(  977): [AlarmQueuing] data connection: true
I/AlarmManager(  977): [AlarmQueuing] wifi connection: true
E/WifiTrafficPoller(  977): ENABLE_TRAFFIC_STATS_POLL false Token 25
D/WifiDataStallTracker(  977): stopDataStallAlarm 
E/WifiDataStallTracker(  977): ENABLE_DATA_MONITOR_POLL false Token 4
E/WifiStateMachine(  977): handleMessage: E msg.what=131167
E/WifiStateMachine(  977): processMsg: ConnectedState
E/WifiStateMachine(  977):  ConnectedState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  977): processMsg: L2ConnectedState
E/WifiStateMachine(  977):  L2ConnectedState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  977): processMsg: ConnectModeState
E/WifiStateMachine(  977):  ConnectModeState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  977): processMsg: DriverStartedState
D/SmartSyncUtils( 6866): isEpsOn(), nState = 0
E/WifiStateMachine(  977):  DriverStartedState !CMD_SCREEN_STATE_CHANGED 0 0
,E/WifiStateMachine(  977): processMsg: SupplicantStartedState
E/WifiStateMachine(  977):  SupplicantStartedState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  977): processMsg: DefaultState
,E/WifiStateMachine(  977):  DefaultState !CMD_SCREEN_STATE_CHANGED 0 0
V/SRS_Proc(  405): ParamSet string: screen_state=off
E/WifiStateMachine(  977):  handleScreenStateChanged Enter: screenOn=false mCurrentScanAlarmMs = 20000 mUserWantsSuspendOpt=false state ConnectedState suppState:CompletedState
E/audio_a2dp_hw(  405): adev_set_parameters: ERROR: set param called even when stream out is null
W/WifiHW  (  977): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
D/WifiDisplayAdapter(  977): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  977):     Client/Owner: Client
D/WifiDisplayAdapter(  977):     GroupId: 
D/WifiDisplayAdapter(  977):     Passphrase: 
D/WifiDisplayAdapter(  977):     SessionId: 0
D/WifiDisplayAdapter(  977):     IP Address: }
D/wpa_supplicant( 1328): wlan0: Control interface command 'SET_SCREEN_ON 0'
I/wpa_supplicant( 1328): SET_SCREEN_ON:Off
I/wpa_supplicant( 1328): htc_wext_set_keepalive +
I/wpa_supplicant( 1328): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1328): getPrivFuncNum +	
I/wpa_supplicant( 1328): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1328): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1328): get_ip_address source addr = c0a80182
I/wpa_supplicant( 1328): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1328): htc_wext_set_keepalive - ret = 0
E/WifiStateMachine(  977): setScanAlarm false period 20000 initial delay 0mAlarmEnabledtrue
D/WifiController(  977): handleMessage: E msg.what=155651
D/WifiStateMachine(  977): backgroundScan enabled=true startBackgroundScanIfNeeded:false
E/WifiStateMachine(  977): handleScreenStateChanged Exit: false
E/WifiStateMachine(  977): handleMessage: X
E/WifiStateMachine(  977): handleMessage: E msg.what=131154
D/NetworkPolicy(  977): updateScreenOn: false
E/WifiStateMachine(  977): processMsg: ConnectedState
V/NetworkPolicy(  977): updateIfacesLocked()
D/WifiController(  977): processMsg: DeviceActiveState
D/NetworkManagementService(  977): isBandwidthControlEnabled: doneSignal.getCount()= 0
D/WifiController(  977): processMsg: StaEnabledState
D/WifiController(  977): processMsg: DefaultState
D/WifiController(  977): handleMessage: X
E/WifiStateMachine(  977):  ConnectedState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  977): processMsg: L2ConnectedState
E/WifiStateMachine(  977):  L2ConnectedState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  977): handleMessage: X
,D/PMS     (  977): acquireWL(27a0fe1c): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 6866 1000 null
,I/SensorManager( 1218): registerListenerImpl: listener = com.htc.sense.easyaccessservice.SensorHubService@f44c4a, sensor = {Sensor name="hTC Gesture Motion HIDI", vendor="hTC Corp.", version=1, type=10, maxRange=200.0, resolution=1.0, power=0.2, minDelay=0}, delay = 200000, handler = null
,W/SensorService(  977): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  977): enable: get sensor name = hTC Gesture Motion HIDI
,W/SensorService(  977): pid=1218, uid=10041
W/SensorService(  977): Active sensors: size = 4
W/SensorService(  977): Accelerometer Sensor (handle=0x00000000, connections=1)
W/SensorService(  977): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  977): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  977): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
W/SensorService(  977): SensorService::listenerSensor++: mName = com.htc.sense.easyaccessservice.SensorHubService@f44c4a, eanble = 1, strlen(mName) = 55
W/SensorService(  977): Active Listeners: mActiveListeners.size() = 2
,W/SensorService(  977): Listener[0] = com.htc.smartdim.sensor_eye@36fde1ba
W/SensorService(  977): Listener[1] = com.htc.sense.easyaccessservice.SensorHubService@f44c4a
W/SensorService(  977): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/BatteryController( 1218): status:5 level:100 unsupport:false plugged:true
,D/GpsLocationProvider(  977): receive broadcast intent, action: android.intent.action.SCREEN_OFF
,D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3,
D/DotMatrix( 1329): [EventService] getTotalRam: 1842 Mb
,W/ContextImpl(  977): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2712 
,D/ContactMessageStore( 1542): start background delete task...,
,D/SmartDim(  977): Init customizeScreenOffDelayClass error
,D/PMS     (  977): releaseWL(27a0fe1c): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
I/ClockController( 1218): stop clock update:screen off,
I/IntentController( 1218): receive(android.intent.action.SCREEN_OFF,1,false)
D/ContactMessageStore( 1542): size: 0 , 0
D/ContactMessageStore( 1542): Background delete complete
,D/PMS     (  977): acquireWL(12a0ea25): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1848 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  977): releaseWL(12a0ea25): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  977): acquireWL(337927fa): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1848 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  977): releaseWL(337927fa): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms},
,W/ContextImpl( 6866): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
W/ContextImpl( 6866): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:22 android.app.ActivityThread.handleReceiver:2712 
,D/SmartSyncUtils( 6866): isEpsOn(), nState = 0,
D/SmartSyncUtils( 6866): isEpsOn(), nState = 0
,W/ContextImpl( 6866): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:73 android.app.ActivityThread.handleReceiver:2712 
,D/AutoSetting( 1659): service - mHandler: cancel location update
D/AutoSetting( 1659): service -           changes count: 0
,W/ContextImpl(  977): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1830 android.content.ContextWrapper.stopService:520 android.content.ContextWrapper.stopService:520 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2712 
,I/SensorManager(  977): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@36fde1ba
W/SensorService(  977): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  977): disable: get sensor name = Accelerometer Sensor
,I/RemoteViews( 1218): setHTCTheme(com.htc.updater,true,33751145),
W/SensorService(  977): pid=977, uid=1000
W/SensorService(  977): Active sensors: size = 3
W/SensorService(  977): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  977): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  977): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
W/SensorService(  977): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@36fde1ba, eanble = 0, strlen(mName) = 36
W/SensorService(  977): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  977): Listener[0] = com.htc.sense.easyaccessservice.SensorHubService@f44c4a
W/SensorService(  977): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  977): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  977): disable: get sensor name = CM36686 Proximity sensor
W/SensorService(  977): pid=977, uid=1000
W/SensorService(  977): Active sensors: size = 2
W/SensorService(  977): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  977): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
W/SensorService(  977): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@36fde1ba, eanble = 0, strlen(mName) = 36
W/SensorService(  977): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  977): Listener[0] = com.htc.sense.easyaccessservice.SensorHubService@f44c4a
E/ActivityThread(  977): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@14bbf86b that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  977): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@14bbf86b that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  977): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:1003)
E/ActivityThread(  977): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:767)
E/ActivityThread(  977): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1775)
E/ActivityThread(  977): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1755)
E/ActivityThread(  977): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:495)
E/ActivityThread(  977): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  977): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  977): 	at android.app.Service.onStartCommand(Service.java:458)
E/ActivityThread(  977): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3072)
E/ActivityThread(  977): 	at android.app.ActivityThread.access$2100(ActivityThread.java:144)
E/ActivityThread(  977): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1470)
E/ActivityThread(  977): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  977): 	at android.os.Looper.loop(Looper.java:155)
E/ActivityThread(  977): 	at com.android.server.SystemServer.run(SystemServer.java:324)
E/ActivityThread(  977): 	at com.android.server.SystemServer.main(SystemServer.java:225)
E/ActivityThread(  977): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread(  977): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread(  977): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/ActivityThread(  977): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
W/SensorService(  977): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/RemoteViews( 1218): apply : com.htc.updater 1 9 0 36
I/SensorManager(  977): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@36fde1ba
,D/SmartSyncUtils( 6866): getMobilePolicyEnabled, result = true,
I/PowerUsageList:PowerUsageHelper( 6866): PowerProfile::POWER_SCREEN_FULL = 154.8
,D/WifiService(  977): New client listening to asynchronous messages,
E/WifiTrafficPoller(  977): ADD_CLIENT: 9
,D/PowerUsageList:BatterySipperExt( 6866): gen(), null == sipper.uidObj, userId = 0
,E/WifiTrafficPoller(  977): TRAFFIC_STATS_POLL false Token 26 num clients 9
,D/PowerUsageList:PowerUsageHelper( 6866): MY_DEBUG = false,
,E/WifiTrafficPoller(  977): TRAFFIC_STATS_POLL false Token 26 num clients 9,
,D/Process (  977): killProcessQuiet, pid=6775
I/ActivityManager(  977): Killing 6775:com.htc.mms.backupagent/u0a76 (adj 15): empty #17
D/Process (  977): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  977): Recipient 6775,
,I/jxcore-log( 6431): Test app app.js loaded
,I/jxcore-log( 6431): 
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6431): load: 
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6431): 	Automate Bluetooth MAC address resolution: true, 
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6431): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6431): 	Bluetooth MAC address: null, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6431): 	Discovery mode: BLE, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6431): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6431): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6431): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6431): 	Scan mode: 1
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6431): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ec20c8 added. We now have 1 listener(s)
I/chromium( 6431): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
D/BluetoothAdapter( 6431): 360234227: getState(). Returning 12
,I/jxcore-log( 6431): BLE advertisement is supported
I/jxcore-log( 6431): 
,E/WifiStateMachine(  977): handleMessage: E msg.what=131155,
E/WifiStateMachine(  977): processMsg: ConnectedState
,E/WifiStateMachine(  977):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1533756625] gl hn u24 rssi=-53 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  977): processMsg: L2ConnectedState
,E/WifiStateMachine(  977):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1533756623] gl hn u24 rssi=-53 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,E/WifiStateMachine(  977): handleMessage: X
,D/PMS     (  977): releaseWL(2082dd72): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 null,
,E/WifiStateMachine(  977): handleMessage: E msg.what=131155,
E/WifiStateMachine(  977): processMsg: ConnectedState
E/WifiStateMachine(  977):  ConnectedState CMD_RSSI_POLL 3 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1636] from screen [on:0 period:-1533754985] gl hn u24 rssi=-53 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  977): processMsg: L2ConnectedState
E/WifiStateMachine(  977):  L2ConnectedState CMD_RSSI_POLL 3 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1533754982] gl hn u24 rssi=-53 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  977): handleMessage: X
,D/HtcUPManager( 1218): HtcUPServiceProxy onTrimMemory() has been called. Memory Level: 60,
,E/WifiDataStallTracker(  977): DATA_MONITOR_POLL false Token 5,
,E/WifiDataStallTracker(  977): DATA_MONITOR_POLL false Token 5,
,D/ContactMessageStore( 1542): MSG_NOTIFY_CS_TO_SYNC >>,
D/ContactMessageStore( 1542): MSG_NOTIFY_CS_TO_SYNC <<
,W/Atfwd_Sendcmd(  461): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  461): AtCmdFwd service not published, waiting... retryCnt : 2
,I/ActivityManager(  977): Killing 5615:com.htc.musicenhancer/u0a49 (adj 15): empty #17
D/Process (  977): killProcessQuiet, pid=5615,
D/Process (  977): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  977): Recipient 5615,
,D/wpa_supplicant( 1328): EAPOL: startWhen --> 0,
D/wpa_supplicant( 1328): EAPOL: disable timer tick
,D/PMS     (  977): acquireWL(a1b03a1): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 977 1000 WorkSource{1000},
,V/AlarmManager(  977): sending alarm PendingIntent{16ac2e8f: PendingIntentRecord{2f19951c android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=137168, Int=0
,V/AlarmManager(  977): sending alarm PendingIntent{3821c9c6: PendingIntentRecord{7016d87 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=143144, Int=0
,D/PMS     (  977): releaseWL(a1b03a1): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000},
D/WeatherUtility( 1218): Weather sync is On
,W/WeatherTimeKeeper( 1218): [refreshWeatherData] no weather data
,D/AutoSetting( 1659): service - handleMessage() stop self
,D/AutoSetting( 1659): service - onDestroy() END,
,D/AutoSetting( 1659): service - handleMessage() quit looper,
,W/Atfwd_Sendcmd(  461): AtCmdFwd service not published, waiting... retryCnt : 3,
,E/WifiStateMachine(  977): handleMessage: E msg.what=131165
E/WifiStateMachine(  977): processMsg: ConnectedState,
E/WifiStateMachine(  977):  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  977): processMsg: L2ConnectedState
E/WifiStateMachine(  977):  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  977): processMsg: ConnectModeState
E/WifiStateMachine(  977):  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,E/WifiStateMachine(  977): processMsg: DriverStartedState
E/WifiStateMachine(  977):  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  977): processMsg: SupplicantStartedState
E/WifiStateMachine(  977):  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  977): processMsg: DefaultState
E/WifiStateMachine(  977):  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  977): handleMessage: X
,D/GpsLocationProvider(  977): [handleMessage] DOWNLOAD_XTRA_DATA,
D/GpsLocationProvider(  977): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  977): acquireWL(2864f4b4): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 977 1000 null,
,D/libc    (  977): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 4,
,D/libc    (  977): [NET] android_getaddrinfofornet-, err=8
,D/libc    (  977): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024
D/libc    (  977): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  977): [NET] android_getaddrinfo_proxy+
D/libc    (  977): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  399): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024
D/libc    (  399): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,D/libc    (  399): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  399): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  977): [NET] android_getaddrinfo_proxy-, success
D/libc    (  977): [NET] android_getaddrinfofornet+,hn 14(0x35342e3233392e),sn(),hints(known),family 0,flags 4
D/libc    (  977): [NET] android_getaddrinfofornet-, SUCCESS
,D/GpsLocationProvider(  977): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  977): [reportHTCStatus] eventMask = 3 , status = 0,
D/GpsLocationProvider(  977): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  977):  [handleDownloadXtraData]inject done.
D/PMS     (  977): acquireWL(2eb6a820): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 977 1000 null
D/GpsLocationProvider(  977): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
D/PMS     (  977): releaseWL(2864f4b4): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 null
D/PMS     (  977): releaseWL(2eb6a820): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/ContextImpl(  977): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 ,
,W/Atfwd_Sendcmd(  461): AtCmdFwd service not published, waiting... retryCnt : 4
,E/WifiStateMachine(  977): handleMessage: E msg.what=131326
E/WifiStateMachine(  977): processMsg: ConnectedState
E/WifiStateMachine(  977):  ConnectedState what:131326 2 0
,E/WifiStateMachine(  977): processMsg: L2ConnectedState
E/WifiStateMachine(  977):  L2ConnectedState what:131326 2 0
E/WifiStateMachine(  977): handleMessage: X
,D/PMS     (  977): acquireWL(33bf85d9): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 977 1000 null,
,I/BatteryService(  977): n_update end,
D/UsbnetService(  977): BroadcastReceiver::onReceive+
D/PMS     (  977): releaseWL(33bf85d9): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  977): onReceive BATTERY_CHANGED
D/NotificationService(  977): plugged=true pluggin=true
D/UsbnetService(  977):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  977): updateBatteryInfo
D/PowerUI ( 1218): closing low battery warning: level=100
I/IntentController( 1218): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1218): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  977): runPSCheck
D/DotMatrix( 1329): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  977): Checking...
D/HeadsetStateMachine( 3124): Disconnected process message: 10, size: 0
,D/WifiController(  977): battery changed pluggedType: 2
D/UsbnetService(  977): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  977): >> updateStatus
D/WifiController(  977): handleMessage: E msg.what=155652
D/WifiController(  977): processMsg: DeviceActiveState
D/WifiController(  977): processMsg: StaEnabledState
D/WifiController(  977): processMsg: DefaultState
D/WifiController(  977): handleMessage: X
,I/HtcPowerSaver(  977): updateStatus (8000,100,-1,false,false,false,-1),
I/HtcPowerSaver(  977): << updateStatus
,I/BatteryController( 1218): status:5 level:100 unsupport:false plugged:true
,D/TelephonyReceiver( 1542): switchBindHtcMsgCursor: null,
,W/Atfwd_Sendcmd(  461): AtCmdFwd service not published, waiting... retryCnt : 5,
,D/PMS     (  977): acquireWL(22a4b9e): PARTIAL_WAKE_LOCK  *alarm* 0x1 977 1000 WorkSource{1000},
,V/AlarmManager(  977): sending alarm PendingIntent{2940867f: PendingIntentRecord{3eae264c android broadcastIntent}}, i=android.app.backup.intent.INIT, t=0, cnt=1, w=1454460210437, Int=0
D/PMS     (  977): acquireWL(2a99a695): PARTIAL_WAKE_LOCK  *backup* 0x1 977 1000 null
V/AlarmManager(  977): sending alarm PendingIntent{16ac2e8f: PendingIntentRecord{2f19951c android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=197168, Int=0
,V/AlarmManager(  977): sending alarm PendingIntent{206b83aa: PendingIntentRecord{f610b9b android broadcastIntent}}, i=com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE, t=2, cnt=1, w=202076, Int=0
V/AlarmManager(  977): sending alarm PendingIntent{32bd5b38: PendingIntentRecord{11bb1711 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=190144, Int=0
,D/PMS     (  977): acquireWL(35d63076): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1965 10024 WorkSource{10024 com.google.android.gms}
,W/BackupManagerService(  977): Requested unavailable transport: com.google.android.gms.backup.BackupTransportService
,E/BackupManagerService(  977): Requested init for com.google.android.gms.backup.BackupTransportService but not found
,D/PMS     (  977): releaseWL(2a99a695): PARTIAL_WAKE_LOCK  *backup* 0x1 null
,D/PMS     (  977): releaseWL(22a4b9e): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,D/WeatherUtility( 1218): Weather sync is On
W/WeatherTimeKeeper( 1218): [refreshWeatherData] no weather data
,D/PMS     (  977): acquireWL(203ac677): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1965 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  977): releaseWL(35d63076): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,V/GLSActivity( 1965): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/PMS     (  977): releaseWL(203ac677): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  977): acquireWL(38009749): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1965 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  977): releaseWL(38009749): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  977): acquireWL(11ced84e): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1965 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  977): releaseWL(11ced84e): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  977): acquireWL(354e0d6f): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1965 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  977): acquireWL(d2dba7c): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1965 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  977): acquireWL(38442b5a): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1965 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  977): releaseWL(354e0d6f): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,I/VacuumService( 1965): Vacuum at: now=1454460245234 tag=VacuumService
,D/PMS     (  977): releaseWL(d2dba7c): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,I/GoogleURLConnFactory( 1965): Using platform SSLCertificateSocketFactory
D/PMS     (  977): acquireWL(cda0268): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1965 10024 WorkSource{10024 com.google.android.gms}
,W/Uploader( 1965): No account for auth token provided
,D/PMS     (  977): releaseWL(cda0268): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
D/PMS     (  977): acquireWL(29fee681): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1965 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  977): releaseWL(29fee681): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/libc    ( 1965): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4,
D/libc    ( 1965): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 1965): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 1965): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1965): [NET] android_getaddrinfo_proxy+
D/libc    ( 1965): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  399): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  399): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,D/libc    (  399): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  399): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 1965): [NET] android_getaddrinfo_proxy-, success
,D/libc    ( 1965): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4,
D/libc    ( 1965): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1965): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 1965): [NET] android_getaddrinfofornet-, err=8
,W/Uploader( 1965): No account for auth token provided,
,W/Uploader( 1965): No account for auth token provided,
,W/Uploader( 1965):  no longer exists, so no auth token.,
,W/Uploader( 1965): No account for auth token provided
,I/GLSUser ( 1965): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog,
I/GLSUser ( 1965): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1965): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1965): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1965): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/DotMatrix( 1329): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true,
D/DotMatrix( 1329): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1218): reapply : com.google.android.gms 2 40,
,E/Uploader( 1965): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1965): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1965): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1965): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1965): 	at com.google.android.gms.auth.p.c(SourceFile:550)
,E/Uploader( 1965): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1965): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1965): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1965): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1965): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1965): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1965): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1965): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1965): No account for auth token provided
,D/PMS     (  977): releaseWL(38442b5a): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
D/PMS     (  977): acquireWL(32621375): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1965 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  977): releaseWL(32621375): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  977): acquireWL(172e1f0a): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1965 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  977): releaseWL(172e1f0a): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/HtcUPManager( 1218): HtcUPServiceProxy Disconnect from  UP serivce: No interaction with app
D/HtcUPManager( 1218): HtcUPServiceProxy Disconnect from UP service. Change state to: DISCONNECTED
,D/HtcAppUPService( 1659): HtcUPService [##] onDestroy(), this =com.htc.sense.hsp.upservice.HtcUPService@47c41e9
,D/Process (  977): killProcessQuiet, pid=5981
I/ActivityManager(  977): Killing 5981:com.android.settings/1000 (adj 15): empty #17
D/Process (  977): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  977): Recipient 5981
D/WifiService(  977): Client connection lost with reason: 4
,W/Atfwd_Sendcmd(  461): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  977): acquireWL(37d4737b): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 977 1000 null
I/BatteryService(  977): n_update end
D/PMS     (  977): releaseWL(37d4737b): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1218): closing low battery warning: level=100
D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  977): updateBatteryInfo
D/DotMatrix( 1329): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/NotificationService(  977): plugged=true pluggin=true
D/UsbnetService(  977): BroadcastReceiver::onReceive+
D/PMS     (  977): runPSCheck
D/UsbnetService(  977): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  977): Checking...
D/UsbnetService(  977):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/HtcPowerSaver(  977): >> updateStatus
D/UsbnetService(  977): BroadcastReceiver::onReceive-
D/PowerUI ( 1218): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HeadsetStateMachine( 3124): Disconnected process message: 10, size: 0
D/WifiController(  977): battery changed pluggedType: 2
D/WifiController(  977): handleMessage: E msg.what=155652
D/WifiController(  977): processMsg: DeviceActiveState
D/WifiController(  977): processMsg: StaEnabledState
D/WifiController(  977): processMsg: DefaultState
D/WifiController(  977): handleMessage: X
I/IntentController( 1218): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/HtcPowerSaver(  977): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  977): << updateStatus
,I/BatteryController( 1218): status:5 level:100 unsupport:false plugged:true,
,W/Atfwd_Sendcmd(  461): AtCmdFwd service not published, waiting... retryCnt : 2,
,W/Atfwd_Sendcmd(  461): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  461): AtCmdFwd service not published, waiting... retryCnt : 4
,D/wpa_supplicant( 1328): wlan0: BSS: Remove id 0 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1328): wlan0: BSS: Remove id 2 BSSID 38:f8:89:11:e9:11 SSID 'Gonzos' due to wpa_bss_flush_by_age
,D/WifiMonitor(  977): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a]
E/WifiMonitor(  977): WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a
D/WifiMonitor(  977): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 2 38:f8:89:11:e9:11]
E/WifiMonitor(  977): WifiMonitor:wlan0 cnt=47 dispatchEvent: CTRL-EVENT-BSS-REMOVED 2 38:f8:89:11:e9:11
,D/PMS     (  977): acquireWL(cc6d598): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 977 1000 null
I/BatteryService(  977): n_update end
D/PMS     (  977): releaseWL(cc6d598): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  977): updateBatteryInfo
D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  977): plugged=true pluggin=true
D/DotMatrix( 1329): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  977): runPSCheck
I/IntentController( 1218): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  977): Checking...
D/UsbnetService(  977): BroadcastReceiver::onReceive+
I/HtcPowerSaver(  977): >> updateStatus
D/UsbnetService(  977): onReceive BATTERY_CHANGED
D/WifiController(  977): battery changed pluggedType: 2
D/UsbnetService(  977):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PowerUI ( 1218): closing low battery warning: level=100
D/UsbnetService(  977): BroadcastReceiver::onReceive-
D/PowerUI ( 1218): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  977): handleMessage: E msg.what=155652
D/WifiController(  977): processMsg: DeviceActiveState
D/WifiController(  977): processMsg: StaEnabledState
D/WifiController(  977): processMsg: DefaultState
D/WifiController(  977): handleMessage: X
D/HeadsetStateMachine( 3124): Disconnected process message: 10, size: 0
,I/HtcPowerSaver(  977): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  977): << updateStatus
,I/BatteryController( 1218): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  461): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  977): acquireWL(114d71f1): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 977 1000 WorkSource{1000}
V/AlarmManager(  977): sending alarm PendingIntent{16ac2e8f: PendingIntentRecord{2f19951c android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=257168, Int=0
V/AlarmManager(  977): sending alarm PendingIntent{3faccc57: PendingIntentRecord{251fb344 com.htc.backup startService}}, i=resume, t=0, cnt=1, w=1454460383874, Int=0
,D/WeatherUtility( 1218): Weather sync is On,
D/PMS     (  977): releaseWL(114d71f1): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
W/WeatherTimeKeeper( 1218): [refreshWeatherData] no weather data
,W/Atfwd_Sendcmd(  461): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  977): acquireWL(21b63c2d): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 977 1000 null
I/BatteryService(  977): n_update end,
D/PMS     (  977): releaseWL(21b63c2d): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  977): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  977): updateBatteryInfo,
D/NotificationService(  977): plugged=true pluggin=true
D/HeadsetStateMachine( 3124): Disconnected process message: 10, size: 0
,D/PowerUI ( 1218): closing low battery warning: level=100
I/IntentController( 1218): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/PowerUI ( 1218): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  977): runPSCheck
D/DotMatrix( 1329): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  977): Checking...
D/UsbnetService(  977): onReceive BATTERY_CHANGED
I/HtcPowerSaver(  977): >> updateStatus
D/UsbnetService(  977):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/WifiController(  977): battery changed pluggedType: 2
D/UsbnetService(  977): BroadcastReceiver::onReceive-
D/WifiController(  977): handleMessage: E msg.what=155652
D/WifiController(  977): processMsg: DeviceActiveState
D/WifiController(  977): processMsg: StaEnabledState
D/WifiController(  977): processMsg: DefaultState
D/WifiController(  977): handleMessage: X
,I/HtcPowerSaver(  977): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  977): << updateStatus
,I/BatteryController( 1218): status:5 level:100 unsupport:false plugged:true,
,W/Atfwd_Sendcmd(  461): AtCmdFwd service not published, waiting... retryCnt : 2,
,W/Atfwd_Sendcmd(  461): AtCmdFwd service not published, waiting... retryCnt : 3
,V/GLSActivity( 1965): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1965): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket,
I/GLSUser ( 1965): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1965): [GLSUser] Extracting token using key: Auth,
W/GLSActivity( 1965): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1965): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/DotMatrix( 1329): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true,
D/DotMatrix( 1329): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1218): reapply : com.google.android.gms 2 40,
W/GLSActivity( 1965): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1965): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1965): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1965): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1965): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1965): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1965): 	at android.os.Binder.execTransact(Binder.java:454)
,E/PlayEventLogger( 6005): Failed to get auth token: User intervention required. Notification has been pushed.,
E/PlayEventLogger( 6005): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6005): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 6005): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 6005): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 6005): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 6005): 	at android.os.Binder.execTransact(Binder.java:454)
,W/System  ( 6005): Ignoring header User-Agent because its value was null.
,D/libc    ( 6005): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
,D/libc    ( 6005): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 6005): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
,D/libc    ( 6005): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 6005): [NET] android_getaddrinfo_proxy+
D/libc    ( 6005): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  399): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  399): [NET] _dns_getaddrinfo+, netid:101, mark:917605
D/libc    (  399): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  399): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    ( 6005): [NET] android_getaddrinfo_proxy-, success
,W/Atfwd_Sendcmd(  461): AtCmdFwd service not published, waiting... retryCnt : 4,
,D/HeadsetStateMachine( 3124): Disconnected process message: 10, size: 0
D/PMS     (  977): acquireWL(30237947): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 977 1000 null
I/IntentController( 1218): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/BatteryService(  977): n_update end
D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  977): releaseWL(30237947): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1218): closing low battery warning: level=100
D/DotMatrix( 1329): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1218): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  977): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  977): updateBatteryInfo
D/UsbnetService(  977): onReceive BATTERY_CHANGED
D/NotificationService(  977): plugged=true pluggin=true
,D/UsbnetService(  977):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  977): runPSCheck
D/UsbnetService(  977): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  977): Checking...
I/HtcPowerSaver(  977): >> updateStatus
D/WifiController(  977): handleMessage: E msg.what=155652
D/WifiController(  977): processMsg: DeviceActiveState
D/WifiController(  977): battery changed pluggedType: 2
D/WifiController(  977): processMsg: StaEnabledState
D/WifiController(  977): processMsg: DefaultState
D/WifiController(  977): handleMessage: X
,I/HtcPowerSaver(  977): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  977): << updateStatus
,I/BatteryController( 1218): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  461): AtCmdFwd service not published, waiting... retryCnt : 5,
,W/Atfwd_Sendcmd(  461): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  977): acquireWL(21f87574): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 977 1000 null,
I/BatteryService(  977): n_update end
D/PMS     (  977): releaseWL(21f87574): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HeadsetStateMachine( 3124): Disconnected process message: 10, size: 0
D/HtcPowerSaver(  977): updateBatteryInfo
D/UsbnetService(  977): BroadcastReceiver::onReceive+
,D/PowerUI ( 1218): closing low battery warning: level=100
D/UsbnetService(  977): onReceive BATTERY_CHANGED
D/NotificationService(  977): plugged=true pluggin=true
D/UsbnetService(  977):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  977): runPSCheck
D/UsbnetService(  977): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  977): Checking...
D/WifiController(  977): handleMessage: E msg.what=155652
I/HtcPowerSaver(  977): >> updateStatus
D/WifiController(  977): processMsg: DeviceActiveState
D/WifiController(  977): battery changed pluggedType: 2
D/WifiController(  977): processMsg: StaEnabledState
D/PowerUI ( 1218): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  977): processMsg: DefaultState
I/HtcPowerSaver(  977): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  977): handleMessage: X
I/HtcPowerSaver(  977): << updateStatus
I/IntentController( 1218): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1329): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/BatteryController( 1218): status:5 level:100 unsupport:false plugged:true,
,W/Atfwd_Sendcmd(  461): AtCmdFwd service not published, waiting... retryCnt : 2,
,W/Atfwd_Sendcmd(  461): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  461): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  461): AtCmdFwd service not published, waiting... retryCnt : 5,
,E/PNP_UPDATERD(  388): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1542): MSG_CHECK_DELETION >>
D/ContactMessageStore( 1542): mDeleteTask = null, bDeleting = false
,D/AccFlag ( 1542): sku_id=118
D/ContactMessageStore( 1542): MSG_CHECK_DELETION <<
,D/ContactMessageStore( 1542): start background delete task...
,D/ContactMessageStore( 1542): size: 0 , 0
,D/ContactMessageStore( 1542): Background delete complete
,D/PMS     (  977): acquireWL(364b8a9d): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 977 1000 null
I/BatteryService(  977): n_update end
D/PMS     (  977): releaseWL(364b8a9d): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1218): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/PowerUI ( 1218): closing low battery warning: level=100
D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1218): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  977): plugged=true pluggin=true
D/DotMatrix( 1329): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/WifiController(  977): battery changed pluggedType: 2
D/UsbnetService(  977): BroadcastReceiver::onReceive+
D/UsbnetService(  977): onReceive BATTERY_CHANGED
D/UsbnetService(  977):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  977): BroadcastReceiver::onReceive-
D/WifiController(  977): handleMessage: E msg.what=155652
D/WifiController(  977): processMsg: DeviceActiveState
D/WifiController(  977): processMsg: StaEnabledState
D/WifiController(  977): processMsg: DefaultState
D/WifiController(  977): handleMessage: X
D/HeadsetStateMachine( 3124): Disconnected process message: 10, size: 0
,I/BatteryController( 1218): status:5 level:100 unsupport:false plugged:true
,D/HtcPowerSaver(  977): updateBatteryInfo,
D/PMS     (  977): runPSCheck
D/HtcPowerSaver(  977): Checking...
I/HtcPowerSaver(  977): >> updateStatus
I/HtcPowerSaver(  977): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  977): << updateStatus
,D/PMS     (  977): acquireWL(34d40b12): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 977 1000 null,
I/BatteryService(  977): n_update end
,D/PMS     (  977): releaseWL(34d40b12): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null,
I/IntentController( 1218): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1218): closing low battery warning: level=100
,D/HeadsetStateMachine( 3124): Disconnected process message: 10, size: 0
D/PowerUI ( 1218): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  977): plugged=true pluggin=true
D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/WifiController(  977): battery changed pluggedType: 2
D/DotMatrix( 1329): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  977): updateBatteryInfo
D/UsbnetService(  977): BroadcastReceiver::onReceive+
D/PMS     (  977): runPSCheck
,D/UsbnetService(  977): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  977): Checking...
D/UsbnetService(  977):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/HtcPowerSaver(  977): >> updateStatus
D/UsbnetService(  977): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  977): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  977): handleMessage: E msg.what=155652
I/HtcPowerSaver(  977): << updateStatus
D/WifiController(  977): processMsg: DeviceActiveState
D/WifiController(  977): processMsg: StaEnabledState
D/WifiController(  977): processMsg: DefaultState
D/WifiController(  977): handleMessage: X
,I/BatteryController( 1218): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  977): acquireWL(3b9462e3): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 977 1000 null,
I/BatteryService(  977): n_update end
D/PMS     (  977): releaseWL(3b9462e3): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HeadsetStateMachine( 3124): Disconnected process message: 10, size: 0
D/HtcPowerSaver(  977): updateBatteryInfo
D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1218): closing low battery warning: level=100
D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1329): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/NotificationService(  977): plugged=true pluggin=true
I/IntentController( 1218): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  977): runPSCheck
D/UsbnetService(  977): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  977): Checking...
D/UsbnetService(  977): onReceive BATTERY_CHANGED
I/HtcPowerSaver(  977): >> updateStatus
D/UsbnetService(  977):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/WifiController(  977): battery changed pluggedType: 2
D/UsbnetService(  977): BroadcastReceiver::onReceive-
D/PowerUI ( 1218): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  977): handleMessage: E msg.what=155652
D/WifiController(  977): processMsg: DeviceActiveState
D/WifiController(  977): processMsg: StaEnabledState
D/WifiController(  977): processMsg: DefaultState
D/WifiController(  977): handleMessage: X
I/HtcPowerSaver(  977): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  977): << updateStatus
,I/BatteryController( 1218): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  977): acquireWL(32e174e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 977 1000 null,
I/BatteryService(  977): n_update end
D/PMS     (  977): releaseWL(32e174e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  977): BroadcastReceiver::onReceive+,
D/HtcPowerSaver(  977): updateBatteryInfo
D/UsbnetService(  977): onReceive BATTERY_CHANGED
,D/NotificationService(  977): plugged=true pluggin=true
D/UsbnetService(  977):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  977): runPSCheck
D/UsbnetService(  977): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  977): Checking...
D/WifiController(  977): handleMessage: E msg.what=155652
,I/HtcPowerSaver(  977): >> updateStatus
D/WifiController(  977): processMsg: DeviceActiveState
D/WifiController(  977): battery changed pluggedType: 2
D/WifiController(  977): processMsg: StaEnabledState
D/PowerUI ( 1218): closing low battery warning: level=100
,D/WifiController(  977): processMsg: DefaultState
,D/WifiController(  977): handleMessage: X
D/HeadsetStateMachine( 3124): Disconnected process message: 10, size: 0
I/HtcPowerSaver(  977): updateStatus (8000,100,-1,false,false,false,-1)
I/IntentController( 1218): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/HtcPowerSaver(  977): << updateStatus
D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1329): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/PowerUI ( 1218): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/BatteryController( 1218): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  977): acquireWL(20db3399): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 977 1000 null,
I/BatteryService(  977): n_update end
D/PMS     (  977): releaseWL(20db3399): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1218): receive(android.intent.action.BATTERY_CHANGED,1,false),
D/PowerUI ( 1218): closing low battery warning: level=100
D/HeadsetStateMachine( 3124): Disconnected process message: 10, size: 0
D/NotificationService(  977): plugged=true pluggin=true
D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/WifiController(  977): battery changed pluggedType: 2
D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  977): updateBatteryInfo
D/DotMatrix( 1329): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/PMS     (  977): runPSCheck
D/UsbnetService(  977): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  977): Checking...
D/UsbnetService(  977): onReceive BATTERY_CHANGED
I/HtcPowerSaver(  977): >> updateStatus
D/UsbnetService(  977):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PowerUI ( 1218): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  977): BroadcastReceiver::onReceive-
D/WifiController(  977): handleMessage: E msg.what=155652
D/WifiController(  977): processMsg: DeviceActiveState
D/WifiController(  977): processMsg: StaEnabledState
D/WifiController(  977): processMsg: DefaultState
,D/WifiController(  977): handleMessage: X
I/HtcPowerSaver(  977): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  977): << updateStatus
,I/BatteryController( 1218): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  977): acquireWL(863c65e): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 977 1000 WorkSource{1000},
V/AlarmManager(  977): sending alarm PendingIntent{16ac2e8f: PendingIntentRecord{2f19951c android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=377168, Int=0
V/AlarmManager(  977): sending alarm PendingIntent{3a04a3f: PendingIntentRecord{d98ff0c com.android.bluetooth broadcastIntent}}, i=com.android.bluetooth.btservice.action.ALARM_WAKEUP, t=2, cnt=1, w=940620, Int=0
,I/bt-btm  ( 3124): Received oneshot timer event complete
I/bt-btm  ( 3124): btm_ble_timeout
D/PMS     (  977): acquireWL(37227055): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 3124 1002 null
I/bt-btm  ( 3124): btm_gen_resolvable_private_addr
,D/WeatherUtility( 1218): Weather sync is On
W/WeatherTimeKeeper( 1218): [refreshWeatherData] no weather data
D/PMS     (  977): releaseWL(863c65e): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/bt-btm  ( 3124): btm_ble_rand_enc_complete,
I/bt-btm  ( 3124): btm_gen_resolve_paddr_low
D/bt-smp  ( 3124): smp_encrypt_data
,W/bt-smp  ( 3124): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
,W/bt-smp  ( 3124): Plain text(LSB ~ MSB) = c1 ff 40 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3124): Encrypted text(LSB ~ MSB) = 6d 96 19 39 ae 50 c7 d8 a2 77 60 67 8e 26 b4 cd 
I/bt-btm  ( 3124): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 3124): Stopping oneshot timer
D/bt-btm  ( 3124): Starting oneshot timer type:103 timeout:900s
,D/PMS     (  977): releaseWL(37227055): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 null,
,D/PMS     (  977): acquireWL(2ea1ea6a): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 977 1000 null
,I/BatteryService(  977): n_update end
D/PMS     (  977): releaseWL(2ea1ea6a): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1329): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HeadsetStateMachine( 3124): Disconnected process message: 10, size: 0
D/PowerUI ( 1218): closing low battery warning: level=100
,D/UsbnetService(  977): BroadcastReceiver::onReceive+
D/NotificationService(  977): plugged=true pluggin=true
D/UsbnetService(  977): onReceive BATTERY_CHANGED
D/WifiController(  977): battery changed pluggedType: 2
D/UsbnetService(  977):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  977): updateBatteryInfo
D/UsbnetService(  977): BroadcastReceiver::onReceive-
D/PMS     (  977): runPSCheck
,D/WifiController(  977): handleMessage: E msg.what=155652
D/HtcPowerSaver(  977): Checking...
D/WifiController(  977): processMsg: DeviceActiveState
I/HtcPowerSaver(  977): >> updateStatus
D/WifiController(  977): processMsg: StaEnabledState
D/PowerUI ( 1218): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  977): processMsg: DefaultState
,D/WifiController(  977): handleMessage: X
I/IntentController( 1218): receive(android.intent.action.BATTERY_CHANGED,1,false)
,I/HtcPowerSaver(  977): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  977): << updateStatus
,I/BatteryController( 1218): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  977): acquireWL(28594b5b): PARTIAL_WAKE_LOCK  *alarm* 0x1 977 1000 WorkSource{1000},
V/AlarmManager(  977): sending alarm PendingIntent{1b041b47: PendingIntentRecord{20f96f74 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=805088, Int=0
V/AlarmManager(  977): sending alarm PendingIntent{16ac2e8f: PendingIntentRecord{2f19951c android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=977168, Int=0
V/AlarmManager(  977): sending alarm PendingIntent{65cfff8: PendingIntentRecord{3d66bcd1 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.MCS_HEARTBEAT, t=2, cnt=1, w=1011013, Int=0
,D/PMS     (  977): acquireWL(cec4336): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1965 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  977): releaseWL(cec4336): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,I/ActivityManager(  977): Start proc com.htc.cs.pns for service com.htc.cs.pns/com.htc.lib1.cs.push.service.UpdateRegistrationService: pid=6925 uid=10071 gids={50071, 9997, 1028, 1015, 3003} abi=armeabi-v7a,
V/AlarmManager(  977): sending alarm PendingIntent{2ed74237: PendingIntentRecord{355e23a4 com.htc.cs.pns startService}}, i=null, t=1, cnt=1, w=1454460729333, Int=0
V/AlarmManager(  977): sending alarm PendingIntent{1cc9550d: PendingIntentRecord{2fd205f7 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1454461009955, Int=0,
,W/ContextImpl( 6866): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,D/PowerUsageList:PowerUsageHelper( 6866): MY_DEBUG = false
D/PMS     (  977): releaseWL(28594b5b): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000},
D/PMS     (  977): acquireWL(2bd3cad3): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1965 10024 WorkSource{10024 com.google.android.gms},
D/GCM     ( 1965): Message class com.google.f.a.a.i
,D/WeatherUtility( 1218): Weather sync is On
,W/WeatherTimeKeeper( 1218): [refreshWeatherData] no weather data
,D/PowerUsageService( 6866): repeat time = 1454461953916
,D/PMS     (  977): releaseWL(2bd3cad3): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms}
,I/PowerUsageList:PowerUsageHelper( 6866): PowerProfile::POWER_SCREEN_FULL = 154.8
,D/PowerUsageList:BatterySipperExt( 6866): gen(), null == sipper.uidObj, userId = 0,
,E/cutils-trace( 6949): Error opening trace file: Permission denied (13),
I/dex2oat ( 6949): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.htc.cs.pns/app_push_lib/plugin-deploy.jar --oat-fd=22 --oat-location=/data/data/com.htc.cs.pns/app_push_dex/plugin-deploy.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
I/dex2oat ( 6949): dex2oat: override thread count:4
,I/dex2oat ( 6949): dex2oat took 630.397ms (threads: 4),
,I/PushClient( 6925): ApplicationMonitor {3bd1c429}: logBasicAppInfo(): PackageName:             com.htc.cs.pns
,I/PushClient( 6925): ApplicationMonitor {3bd1c429}: logBasicAppInfo(): ProcessName:             com.htc.cs.pns,
,I/PushClient( 6925): ApplicationMonitor {3bd1c429}: logBasicAppInfo(): VersionName:             1.2.853019
,I/PushClient( 6925): ApplicationMonitor {3bd1c429}: logBasicAppInfo(): VersionCode:             148001224,
I/PushClient( 6925): ApplicationMonitor {3bd1c429}: logBasicAppInfo(): ApplicationPath:         /system/priv-app/PNSClient/PNSClient.apk
,I/PushClient( 6925): ApplicationMonitor {3bd1c429}: logBasicAppInfo(): AppFileDataPath:         /data/data/com.htc.cs.pns/files,
I/PushClient( 6925): ApplicationMonitor {3bd1c429}: logBasicAppInfo(): Htc_SECURITY_DEBUG_flag: false,
I/PushClient( 6925): ApplicationMonitor {3bd1c429}: logBasicAppInfo(): Htc_DEBUG_flag:          false
,I/PushClient( 6925): ApplicationMonitor {3bd1c429}: logBasicAppInfo(): BuildConfig.DEBUG:       false
,I/PushClient( 6925): PnsModel {4ecadb0}: update(): Update registration caused by: alarm,
,I/PushClient( 6925): PnsConfigModel {259f7f47}: <init>(): Use dm-client for provisioning.
,W/System.err( 6925): SLF4J: Failed to load class "org.slf4j.impl.StaticLoggerBinder".
,W/System.err( 6925): SLF4J: Defaulting to no-operation (NOP) logger implementation
W/System.err( 6925): SLF4J: See http://www.slf4j.org/codes.html#StaticLoggerBinder for further details.
,W/ContextImpl( 6925): Implicit intents with startService are not safe: Intent { act=com.htc.cs.dm.intent.action.BIND_CORE_SERVICE } android.content.ContextWrapper.bindService:538 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 
,I/ActivityManager(  977): Start proc com.htc.cs.dm for service com.htc.cs.dm/.config.service.ConfigManagerBoundService: pid=6956 uid=10099 gids={50099, 9997, 3003} abi=arm64-v8a,
,I/art     (  977): Explicit concurrent mark sweep GC freed 45692(2MB) AllocSpace objects, 10(1948KB) LOS objects, 33% free, 18MB/28MB, paused 1.816ms total 174.495ms
,I/DeviceManagement( 6956): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.2.848686;250001208] pid=6956 dbg=false s=true
,I/DeviceManagement( 6956): ConfigManagerBoundService: *** getConfig: appID=com.htc.cs.pns options=Bundle[EMPTY_PARCEL],
,I/DeviceManagement( 6956): ConfigManagerBoundService: Caller: uid=com.htc.cs.pns (10071) packages=[com.htc.cs.pns]
,I/DeviceManagement( 6956): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[EMPTY_PARCEL], appID=com.htc.cs.pns}]]
,I/DeviceManagement( 6956): WorkflowService: Starting workflow service
,I/DeviceManagement( 6956): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@1578bcf3] args=[Bundle[mParcelledData.dataSize=88]]
,I/DeviceManagement( 6956): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=88]
,I/DeviceManagement( 6956): ModelRegistry: Loading model meta data from resources...
,I/DeviceManagement( 6956): ConfigManagerController: *** getConfig: appID=com.htc.cs.pns includeMeta=false,
,I/DeviceManagement( 6956): SessionStateController: Checking invariants...,
,I/DeviceManagement( 6956): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true,
,I/DeviceManagement( 6956): SessionStateController: Checking invariants...
,I/DeviceManagement( 6956): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.pns includeMeta=false,
,I/DeviceManagement( 6956): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@1578bcf3],
,I/DeviceManagement( 6956): WorkflowService: Stopping workflow service
,D/Process (  977): killProcessQuiet, pid=6005,
I/ActivityManager(  977): Killing 6005:com.android.vending/u0a72 (adj 15): empty #17
D/Process (  977): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/PushClient( 6925): PnsModel {4ecadb0}: update(): The registration record has not expired yet. No need to update.,
,I/ActivityManager(  977): Recipient 6005,
,D/Process (  977): killProcessQuiet, pid=6804
I/ActivityManager(  977): Killing 6804:com.google.android.partnersetup/u0a27 (adj 15): empty #17,
D/Process (  977): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 ,
,I/ActivityManager(  977): Recipient 6804
,D/PMS     (  977): acquireWL(263bdd4): PARTIAL_WAKE_LOCK  *alarm* 0x1 977 1000 WorkSource{1000}
V/AlarmManager(  977): sending alarm PendingIntent{e469b7d: PendingIntentRecord{171e7a72 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1454461055998, Int=0
,D/SmartSyncUtils( 6866): isEpsOn(), nState = 0
,D/PMS     (  977): releaseWL(263bdd4): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,D/PMS     (  977): acquireWL(7750ec3): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 6866 1000 null
,D/SmartSyncScreenOnOffTimeReceiver( 6866): [updateNmRange] bManual = false,
,D/SmartSyncScreenOnOffTimeReceiver( 6866): [updateNmRange] USERNIGHT_TIMESTART = 1, USERNIGHT_TIMEEND = 7, nStart = 1, nEnd = 7, bNormalRange = true,
,D/SmartSyncScreenOnOffTimeReceiver( 6866): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 6866): SettingOnTime = 1454479200000, randomSettingOnTime = 1454478787000
,D/SmartSyncScreenOnOffTimeReceiver( 6866): SettingOffTime = 1454544000000, randomSettingOffTime = 1454546071000
,D/SmartSyncScreenOnOffTimeReceiver( 6866): bDayMode = false
,D/SmartSyncScreenOnOffTimeReceiver( 6866): bNightMode = true
D/SmartSyncScreenOnOffTimeReceiver( 6866): bNightModeTurnOffOnce = false
,D/PMS     (  977): releaseWL(7750ec3): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/PMS     (  977): acquireWL(528e340): PARTIAL_WAKE_LOCK  *alarm* 0x1 977 1000 WorkSource{1000}
,V/AlarmManager(  977): sending alarm PendingIntent{2b267279: PendingIntentRecord{18d5cbbe com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_TURN_OFF_NETWORK_BY_CHECK, t=0, cnt=1, w=1454461056091, Int=0
W/ContextImpl( 6866): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:22 android.app.ActivityThread.handleReceiver:2712 
,D/SmartSyncDataLinkTurnOffService( 6866): SMARTSYNC_TURN_OFF_NETWORK, current time = 1454461056112, randomOffTime = 1454546071000, newRandomOffTime = 1454546071000
,D/SmartSyncDataLinkTurnOffService( 6866): SMARTSYNC_TURN_OFF_NETWORK, randomWifiOnTime = 1454478787000, randomMobileOnTime = 1454478787000
,D/SmartSyncUtils( 6866): getMobilePolicyEnabled, result = true
,D/SmartSyncDataLinkTurnOffService( 6866): turnOffMobile bPolicyEnabled = true
,D/PMS     (  977): releaseWL(528e340): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,D/SmartSyncUtils( 6866): isWifiHotSpotEnabled = false
,D/SmartSyncDataLinkTurnOffService( 6866): turnOffMobile bCheckMobileData = false
,D/LocationManagerService(  977): getProviders()=[gps, network]
D/LocationManagerService(  977): getBestProvider(Criteria[power=NO_REQ acc=---], false)=gps
,D/LocationManagerService(  977): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
,D/SmartSyncDataLinkTurnOffService( 6866): isDeviceMoving = false, Postion_different = 0.0, bLatLngValue = true, orgPosLat = 0.0, orgPosLng = 0.0, curPosLat = 0.0, curPosLng = 0.0
,D/SmartSyncUtils( 6866): isCharging status = 5
,D/SmartSyncDataLinkTurnOffService( 6866): turnOffWifi ui setting = true
,D/SmartSyncUtils( 6866): isWifiHotSpotEnabled = false
,I/ActivityManager(  977): Cannot resolve ContentProvider=com.htc.vowifi
D/SmartSyncUtils( 6866): state = 0
E/ActivityThread( 6866): Failed to find provider info for com.htc.vowifi
,D/SmartSyncDataLinkTurnOffService( 6866): turnOffWifi bCheckWifiData = true
,D/SmartSyncDataLinkTurnOffService( 6866): turnOffWifi bWifiConnected = true
,D/PMS     (  977): acquireWL(a58f36c): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 977 1000 null
I/BatteryService(  977): n_update end
D/PMS     (  977): releaseWL(a58f36c): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1329): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/HeadsetStateMachine( 3124): Disconnected process message: 10, size: 0,
D/PowerUI ( 1218): closing low battery warning: level=100
I/IntentController( 1218): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  977): updateBatteryInfo
D/UsbnetService(  977): BroadcastReceiver::onReceive+
D/NotificationService(  977): plugged=true pluggin=true
D/UsbnetService(  977): onReceive BATTERY_CHANGED
D/PMS     (  977): runPSCheck
D/UsbnetService(  977):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  977): Checking...
D/UsbnetService(  977): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  977): >> updateStatus
D/WifiController(  977): handleMessage: E msg.what=155652
D/WifiController(  977): battery changed pluggedType: 2
,D/WifiController(  977): processMsg: DeviceActiveState
D/PowerUI ( 1218): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  977): processMsg: StaEnabledState
D/WifiController(  977): processMsg: DefaultState
D/WifiController(  977): handleMessage: X
I/HtcPowerSaver(  977): updateStatus (8000,100,-1,false,false,false,-1),
I/HtcPowerSaver(  977): << updateStatus
,I/BatteryController( 1218): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  977): acquireWL(3392bd35): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 977 1000 null,
,D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/BatteryService(  977): n_update end
D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/PMS     (  977): releaseWL(3392bd35): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1329): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/NotificationService(  977): plugged=true pluggin=true
D/UsbnetService(  977): BroadcastReceiver::onReceive+
D/PowerUI ( 1218): closing low battery warning: level=100
D/UsbnetService(  977): onReceive BATTERY_CHANGED
D/WifiController(  977): battery changed pluggedType: 2
D/UsbnetService(  977):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  977): updateBatteryInfo
D/UsbnetService(  977): BroadcastReceiver::onReceive-
D/PMS     (  977): runPSCheck
D/WifiController(  977): handleMessage: E msg.what=155652
,D/HtcPowerSaver(  977): Checking...
D/WifiController(  977): processMsg: DeviceActiveState
I/HtcPowerSaver(  977): >> updateStatus
D/WifiController(  977): processMsg: StaEnabledState
D/PowerUI ( 1218): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/WifiController(  977): processMsg: DefaultState
I/HtcPowerSaver(  977): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  977): handleMessage: X
I/HtcPowerSaver(  977): << updateStatus
I/IntentController( 1218): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HeadsetStateMachine( 3124): Disconnected process message: 10, size: 0
,I/BatteryController( 1218): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  977): acquireWL(371ee5ca): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 977 1000 null
I/BatteryService(  977): n_update end
D/PMS     (  977): releaseWL(371ee5ca): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  977): BroadcastReceiver::onReceive+
D/NotificationService(  977): plugged=true pluggin=true
D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/WifiController(  977): battery changed pluggedType: 2
D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  977): updateBatteryInfo
D/DotMatrix( 1329): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  977): runPSCheck
D/UsbnetService(  977): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  977): Checking...
D/UsbnetService(  977):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/HtcPowerSaver(  977): >> updateStatus
D/UsbnetService(  977): BroadcastReceiver::onReceive-
D/HeadsetStateMachine( 3124): Disconnected process message: 10, size: 0
D/WifiController(  977): handleMessage: E msg.what=155652
D/WifiController(  977): processMsg: DeviceActiveState
D/WifiController(  977): processMsg: StaEnabledState
D/WifiController(  977): processMsg: DefaultState
D/WifiController(  977): handleMessage: X
I/IntentController( 1218): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/PowerUI ( 1218): closing low battery warning: level=100
,D/PowerUI ( 1218): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  977): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  977): << updateStatus
,I/BatteryController( 1218): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  977): acquireWL(2667933b): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 977 1000 WorkSource{1000}
,V/AlarmManager(  977): sending alarm PendingIntent{16ac2e8f: PendingIntentRecord{2f19951c android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1037168, Int=0
,V/AlarmManager(  977): sending alarm PendingIntent{397da58: PendingIntentRecord{43ef7b1 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_TURN_OFF_WIFI_RETRY, t=0, cnt=1, w=1454461236184, Int=0
,W/ContextImpl( 6866): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:22 android.app.ActivityThread.handleReceiver:2712 
,D/PMS     (  977): releaseWL(2667933b): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1218): Weather sync is On
,W/WeatherTimeKeeper( 1218): [refreshWeatherData] no weather data,
,D/SmartSyncDataLinkTurnOffService( 6866): turnOffWifi ui setting = true
,D/SmartSyncUtils( 6866): isWifiHotSpotEnabled = false
,I/ActivityManager(  977): Cannot resolve ContentProvider=com.htc.vowifi
,E/ActivityThread( 6866): Failed to find provider info for com.htc.vowifi
D/SmartSyncUtils( 6866): state = 0
D/SmartSyncDataLinkTurnOffService( 6866): turnOffWifi bCheckWifiData = false
,D/SmartSyncDataLinkTurnOffService( 6866): turnOffWifi bWifiConnected = true
,D/LocationManagerService(  977): getProviders()=[gps, network]
,D/LocationManagerService(  977): getBestProvider(Criteria[power=NO_REQ acc=---], false)=gps
D/LocationManagerService(  977): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
,D/SmartSyncDataLinkTurnOffService( 6866): isDeviceMoving = false, Postion_different = 0.0, bLatLngValue = true, orgPosLat = 0.0, orgPosLng = 0.0, curPosLat = 0.0, curPosLng = 0.0
,D/SmartSyncUtils( 6866): isCharging status = 5
,D/PMS     (  977): acquireWL(12b22817): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 977 1000 null,
I/BatteryService(  977): n_update end
D/PMS     (  977): releaseWL(12b22817): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  977): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  977): updateBatteryInfo
D/UsbnetService(  977): onReceive BATTERY_CHANGED
D/NotificationService(  977): plugged=true pluggin=true
D/UsbnetService(  977):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  977): runPSCheck
D/UsbnetService(  977): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  977): Checking...
D/WifiController(  977): handleMessage: E msg.what=155652
I/HtcPowerSaver(  977): >> updateStatus
D/WifiController(  977): processMsg: DeviceActiveState
D/WifiController(  977): battery changed pluggedType: 2,
D/WifiController(  977): processMsg: StaEnabledState
D/PowerUI ( 1218): closing low battery warning: level=100
D/WifiController(  977): processMsg: DefaultState
D/PowerUI ( 1218): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  977): handleMessage: X
D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1329): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1218): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HeadsetStateMachine( 3124): Disconnected process message: 10, size: 0
I/HtcPowerSaver(  977): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  977): << updateStatus
,I/BatteryController( 1218): status:5 level:100 unsupport:false plugged:true,
,E/PNP_UPDATERD(  388): inotify_add_watch failed. (No such file or directory)
,I/UsageStatsService(  977): User[0] Flushing usage stats to disk
,D/PMS     (  977): acquireWL(16dc4404): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 977 1000 null
D/UsbnetService(  977): BroadcastReceiver::onReceive+
I/BatteryService(  977): n_update end
D/UsbnetService(  977): onReceive BATTERY_CHANGED
D/PMS     (  977): releaseWL(16dc4404): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  977):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/NotificationService(  977): plugged=true pluggin=true
,D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  977): updateBatteryInfo
D/DotMatrix( 1329): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  977): runPSCheck
D/DotMatrix( 1329): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  977): Checking...
D/UsbnetService(  977): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  977): >> updateStatus
D/WifiController(  977): handleMessage: E msg.what=155652
,D/WifiController(  977): battery changed pluggedType: 2
D/WifiController(  977): processMsg: DeviceActiveState
D/PowerUI ( 1218): closing low battery warning: level=100
D/WifiController(  977): processMsg: StaEnabledState
D/PowerUI ( 1218): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  977): processMsg: DefaultState
D/WifiController(  977): handleMessage: X
I/IntentController( 1218): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/HeadsetStateMachine( 3124): Disconnected process message: 10, size: 0
,I/HtcPowerSaver(  977): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  977): << updateStatus
,I/BatteryController( 1218): status:5 level:100 unsupport:false plugged:true
,TIME-OUT KILL (timeout was 1200000ms)
```
