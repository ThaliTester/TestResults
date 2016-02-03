#### Test 58135655e794d2c_thali06_HTC-HTC One M8s Logs


```
--------- beginning of main
E/cutils-trace( 6475): Error opening trace file: Permission denied (13)
I/dex2oat ( 6475): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm64 --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=36 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
I/dex2oat ( 6475): dex2oat: override thread count:4
I/dex2oat ( 6475): dex2oat took 40.563ms (threads: 4)
I/Adreno-EGL( 6445): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 6445): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6445): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6445): Local Branch: 
I/Adreno-EGL( 6445): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6445): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6445):                  d74aa161a12b9c6fc6332151
I/Adreno-EGL( 6445): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 6445): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6445): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6445): Local Branch: 
I/Adreno-EGL( 6445): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6445): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6445):                  d74aa161a12b9c6fc6332151
I/WVCdm   (  407): CdmEngine::OpenSession
I/WVCdm   (  407): Level3 Library Sep 25 2014 17:10:03
W/WVCdm   (  407): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
E/WifiTrafficPoller(  968): TRAFFIC_STATS_POLL true Token 11 num clients 6
E/WifiTrafficPoller(  968):  packet count Tx=140 Rx=248
D/DrmWidevineDash(  407): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x15
D/DrmWidevineDash(  407): Service_Initialize: starts!
D/QSEECOMAPI: (  407): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  407): App is not loaded in QSEE
E/QSEECOMAPI: (  407): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  407): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  407): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  407): App is not loaded in QSEE
D/QSEECOMAPI: (  407): Loaded image: APP id = 9
D/DrmWidevineDash(  407): Service_Initialize: ends! returns 0
D/QSAPPSVER(  407): qsapps_get_capabilities: Capability from secure side: 0x0
D/QSAPPSVER(  407): qsapps_get_capabilities: returns 0
D/DrmWidevineDash(  407): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf48a6000
E/DrmWidevineDash(  407): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf48a6000
D/QSEECOMAPI: (  407): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/DrmLibTime(  555): got the req here! ret=0
D/DrmLibTime(  555): command id, time_cmd_id = 770
D/DrmLibTime(  555): time_getutcsec starts!
D/DrmLibTime(  555): QSEE Time Listener: time_getutcsec
D/DrmLibTime(  555): QSEE Time Listener: get_utc_seconds
D/DrmLibTime(  555): QSEE Time Listener: time_get_modem_time
D/DrmLibTime(  555): QSEE Time Listener: Checking if ATS_MODEM is set or not.
E/QC-time-services(  555): Receive Passed == base = 13, unit = 1, operation = 2, result = 0
D/DrmLibTime(  555): QSEE Time Listener: ATS_MODEM is not set. Fallback to Android system time.
D/DrmLibTime(  555): QSEE Time Listener: Retrieved Android system time: 1454534086
D/DrmLibTime(  555): time_getutcsec returns 0, sec = 1454534086; nsec = 0
D/DrmLibTime(  555): time_getutcsec finished! 
D/DrmLibTime(  555): iotcl_continue_command finished! and return 0 
D/DrmLibTime(  555): before calling ioctl to read the next time_cmd
E/QC-time-services(  471): Daemon: Time-services: Waiting to acceptconnection
D/QSEECOMAPI: (  407): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  407): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  407): OEMCrypto_APIVersion: starts!
D/QSEECOMAPI: (  407): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  407): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  407): hlos api version =  9
D/DrmWidevineDash(  407): tz api version =  9
D/DrmWidevineDash(  407): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  407): OEMCrypto_IsKeyboxValid: starts!
D/QSEECOMAPI: (  407): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  407): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  407): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  407): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  407): OEMCrypto_OpenSession: starts! SID=0xf4ad0928
D/DrmWidevineDash(  407): OEMCrypto_OpenSession Session ID = 0
D/QSEECOMAPI: (  407): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  407): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  407): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  407): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  407): OEMCrypto_GetRandom: starts! randomData=0xab689148, dataLength=8
D/QSEECOMAPI: (  407): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  407): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  407): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  407): OEMCrypto_LoadDeviceRSAKey: starts! SID=1, wrapped_rsa_key=0xab687f20, wrapped_rsa_key_length=1280
D/QSEECOMAPI: (  407): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  407): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  407): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  407): CdmEngine::QueryKeyControlInfo
W/WVCdm   (  407): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  407): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  407): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  407): OEMCrypto_GetDeviceID: starts! deviceID=0xab6b5c10, idLength=0xfff97ab8
D/QSEECOMAPI: (  407): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  407): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  407): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  407): OEMCrypto_SupportsUsageTable: starts!
D/QSEECOMAPI: (  407): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  407): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  407): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  407): OEMCrypto_SupportsUsageTable: wv_app_version = 24
D/DrmWidevineDash(  407): OEMCrypto_SupportsUsageTable: ends! returns 0
D/DrmWidevineDash(  407): OEMCrypto_GetHDCPCapability: starts!, current = 0xfff97ace, maximum = 0xfff97acf
D/QSEECOMAPI: (  407): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  407): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  407): OEMCrypto_GetHDCPCapability: ends! returns 0
D/DrmWidevineDash(  407): OEMCrypto_APIVersion: starts!
D/QSEECOMAPI: (  407): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  407): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  407): hlos api version =  9
D/DrmWidevineDash(  407): tz api version =  9
D/DrmWidevineDash(  407): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  407): OEMCrypto_GenerateNonce: starts! SID=1, nonce=0xfff97b3c
D/QSEECOMAPI: (  407): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  407): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  407): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  407): PrepareKeyRequest: nonce=3145654837
D/DrmWidevineDash(  407): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xab671b80
D/DrmWidevineDash(  407): message_length=1646, signature=0xab680d08, signature_length=0xfff97a9c
D/QSEECOMAPI: (  407): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  407): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  407): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  407): CdmEngine::CloseSession
D/DrmWidevineDash(  407): OEMCrypto_CloseSession: starts! SID=1
D/QSEECOMAPI: (  407): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  407): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  407): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  407): L3 Terminate.
D/DrmWidevineDash(  407): OEMCrypto_Terminate: starts!
D/QSEECOMAPI: (  407): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  407): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  407): Service_Uninitialize: starts!
D/QSEECOMAPI: (  407): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  407): QSEECom_shutdown_app, app_id = 9
D/DrmWidevineDash(  407): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  407): OEMCrypto_Terminate: ends! returns 0
I/CheckinRequestBuilder( 4438): Classify the device as Phone.
D/libc    ( 4438): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
D/libc    ( 4438): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 4438): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
D/libc    ( 4438): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 4438): [NET] android_getaddrinfo_proxy+
D/libc    ( 4438): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:100, mark:917604
D/libc    (  394): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  394): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 4438): [NET] android_getaddrinfo_proxy-, success
D/libc    ( 4438): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
D/libc    ( 4438): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 4438): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
D/libc    ( 4438): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 4438): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
D/libc    ( 4438): [NET] android_getaddrinfofornet-, err=8
I/CheckinTask( 4438): Sending checkin request (8410 bytes)
,E/cutils-trace( 6491): Error opening trace file: Permission denied (13)
E/WifiTrafficPoller(  968): TRAFFIC_STATS_POLL true Token 11 num clients 6
--------- beginning of system
D/WIFI_ICON( 1215): WifiActivity: 3
E/WifiTrafficPoller(  968):  packet count Tx=155 Rx=259
E/WifiTrafficPoller(  968): notifying of data activity 3
D/StatusBar.NetworkController( 1215): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
D/CustomizationManager( 6491): ====startRecUseTime====
D/htc.customization.log.level( 6491):  is 
W/CustomizationLogLevel( 6491): Level value is invalid, use default level 2
I/CheckinRequestBuilder( 4438): Checkin reason type: 11 attempt count: 1
I/ActivityManager(  968): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 4438): Failed to find provider info for com.google.android.wearable.settings
D/CustomizationManager( 6491):  Read ACC file spent 0.041 (s)
D/CIDMapFileReader( 6491): Parsing tag item name = HTC__001
D/CIDMapFileReader( 6491): Parsing tag item name = HTC__102
D/CIDMapFileReader( 6491): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 6491): Parsing tag item name = HTC__032
D/CIDMapFileReader( 6491): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 6491): Parsing tag item name = HTC__002
D/CIDMapFileReader( 6491): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 6491): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 6491): Parsing tag category name = system
I/CustomizationCIDLoader( 6491): Parsing tag category name = application
I/CustomizationCIDLoader( 6491): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 6491): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 6491): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 6491): Parsing tag category name = Settings
I/CustomizationCIDLoader( 6491): Parsing tag category name = ACC
I/CustomizationCIDLoader( 6491): add string-array item, value = 42507
I/CustomizationCIDLoader( 6491): add string-array item, value = 21902
I/CustomizationCIDLoader( 6491): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 6491): add string-array item, value = 23420
I/CustomizationCIDLoader( 6491): add string-array item, value = 22299
I/CustomizationCIDLoader( 6491): add string-array item, value = 24002
I/CustomizationCIDLoader( 6491): add string-array item, value = 23210
I/CustomizationCIDLoader( 6491): add string-array item, value = 23205
I/CustomizationCIDLoader( 6491): add string-array item, value = 23806
I/CustomizationCIDLoader( 6491): add string-array item, value = 23430
I/CustomizationCIDLoader( 6491): add string-array item, value = 23408
I/CustomizationCIDLoader( 6491): add string-array item, value = 27205
I/CustomizationCIDLoader( 6491): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 6491): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 6491): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 6491): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 6491): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 6491): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 6491): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 6491): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 6491): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 6491): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 6491): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 6491): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 6491):  Read CID file spent 0.087 (s)
D/CustomizationManager( 6491):  All configurations done spent 0.088 (s)
I/ActivityManager(  968): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 pid 6491 on display 0
D/PMS     (  968): acquireHCC(a1a89c4): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 968 1000 null
D/PMS     (  968): acquireHCC(34de90ad): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 968 1000 null
I/GLSUser ( 1873): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
I/GLSUser ( 1873): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1873): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1873): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
W/asset   (  968): Copying FileAsset 0x55672e5170 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
D/PMS     (  968): acquireWL(1f187e30): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 968 1000 null
I/FeedHostManager( 1590): [onPause]
I/FeedProviderManager( 1590): onPause
I/FeedHostManager( 1590): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@3b6917f
I/AnimationUtil(  968): isHTCRecent(ThaliTest/Recent screens.)/5
I/SocialFeedProvider( 1590): +onPause
I/SocialFeedProvider( 1590): -onPause
V/GLSActivity( 1873): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/HtcSystemUPManager(  968): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
I/ActivityManager(  968): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6509 uid=10366 gids={50366, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
W/CheckinRequestBuilder( 4438): awaiting user notification for token
D/DotMatrix( 1324): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1324): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
I/RemoteViews( 1215): reapply : com.google.android.gms 1 40
W/asset   ( 6509): Copying FileAsset 0xaaf2a348 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/CheckinRequestBuilder( 4438): Classify the device as Phone.
D/StatusBarManagerService(  968): setSystemUiVisibility(0x0)
D/StatusBarManagerService(  968): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  968): hiding MENU key
I/CheckinTask( 4438): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
I/TrimMemoryManager( 1590): [trimMemory] 20
I/CheckinService( 4438): Checking schedule, now: 1454534088257 next: 1455070920250
I/CheckinService( 4438): active receiver: disabled
I/PackageManager(  968):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=4438, uid=10024, userID:0
D/PMS     (  968): releaseWL(1f0cbb93): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10024 com.google.android.gms}
I/ActivityManager(  968): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=6533 uid=10077 gids={50077, 9997, 3003} abi=arm64-v8a
,D/PhoneMonitor( 6533): Register our PhoneStateListener
I/WebViewFactory( 6509): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
V/SetupWizard( 6533): Connected to Gservices successfully
D/ChimeraCfgMgr( 4438): Loading module com.google.android.gms.kids from APK com.google.android.gms
I/Kids    ( 4438): [GCoreUtils] Current gmscore version, 7899448 is smaller than the required version 8400000
D/PhoneMonitor( 6533): onServiceStateChanged state="3 3 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1EriInd= -1EriMode= -1RadioPowerSv: false EmergOnly=false PhoneType: 1 VoiceRoaming: false DataRoaming: false IMSRegState: -1" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_POWER_OFF(3) D:STATE_POWER_OFF(3) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
D/PhoneMonitor( 6533): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_POWER_OFF(3) D:STATE_POWER_OFF(3) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
D/GCM     ( 1873): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
I/LibraryLoader( 6509): Time to load native libraries: 10 ms (timestamps 8893-8903)
I/LibraryLoader( 6509): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6509): Binding Chromium to main looper Looper (main, tid 1) {321d5aa0}
I/LibraryLoader( 6509): Expected native library version number "",actual native library version number ""
I/chromium( 6509): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6509): Initializing chromium process, singleProcess=true
W/art     ( 6509): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6509): ApplicationContext is null in ApplicationStatus
E/WifiStateMachine(  968): handleMessage: E msg.what=131155
E/WifiStateMachine(  968): processMsg: ConnectedState
E/WifiStateMachine(  968):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2412 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=1.3 bcn=0 [on:0 tx:0 rx:0 period:2755] from screen [on:0 period:-1459824852] gl hn u24 rssi=-53 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  968): processMsg: L2ConnectedState
E/WifiStateMachine(  968):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2412 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=1.3 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1459824851] gl hn u24 rssi=-53 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  968):  get link layer stats 0
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1323): wlan0: Control interface command 'SIGNAL_POLL'
I/wpa_supplicant( 1323): environment dirty rate=0 [16][0][0]
E/WifiStateMachine(  968): fetchRssiLinkSpeedAndFrequencyNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  968): fetchRssiLinkSpeedAndFrequencyNative rssi=-57 linkspeed=72
E/WifiConfigStore(  968): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-57 "NG700"WPA_PSK
E/WifiStateMachine(  968): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=8.12 txretriesrate=0.00 rxrate=7.65 userTriggerdPenalty0
E/WifiStateMachine(  968):  good link -> stuck count =0
E/WifiStateMachine(  968):  badRSSI count0 lowRSSI count0 --> score 60
E/WifiStateMachine(  968):  isHighRSSI       ---> score=65
D/WifiWatchdogStateMachine(  968): RSSI current: 3 new: -57, 3
E/WifiStateMachine(  968): handleMessage: X
D/WIFI_ICON( 1215): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1215): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
W/chromium( 6509): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 6509): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6509): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6509): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 6509): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6509): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6509): Local Branch: 
I/Adreno-EGL( 6509): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6509): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6509):                  d74aa161a12b9c6fc6332151
W/System.err(  968): java.lang.Throwable: stack dump
W/System.err(  968): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  968): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  968): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  968): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothManagerService(  968): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  968): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@17ffd5b6:true
D/BluetoothAdapter( 6509): 437092556: getState(). Returning 12
W/art     ( 6509): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 6509): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 6509): CordovaWebView is running on device made by: HTC
W/art     ( 6509): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6509): Attempt to remove local handle scope entry from IRT, ignoring
E/WifiDataStallTracker(  968): DATA_MONITOR_POLL true Token 1
D/WifiDataStallTracker(  968): updateDataStallInfo: mDataStallTxRxSum={txSum=138 rxSum=121} preTxRxSum={txSum=122 rxSum=108}
D/WifiDataStallTracker(  968): updateDataStallInfo: IN/OUT
D/WifiDataStallTracker(  968): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
W/ContextImpl(  968): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 
I/art     (  968): Explicit concurrent mark sweep GC freed 27792(1400KB) AllocSpace objects, 5(228KB) LOS objects, 33% free, 16MB/25MB, paused 1.549ms total 164.463ms
W/chromium( 6509): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
E/WifiTrafficPoller(  968): TRAFFIC_STATS_POLL true Token 11 num clients 6
E/WifiTrafficPoller(  968):  packet count Tx=156 Rx=262
D/FindExtension( 6509): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
I/InputMethodManager( 6509): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@3295e9da, mServedView=org.apache.cordova.engine.SystemWebView{2fb12e0b VFEDH.C. .F....I. 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@31fa24e8
I/InputMethodManagerService(  968): Disable input method client, pid=1590
D/StatusBarManagerService(  968): swetImeWindowStatus vis=0 backDisposition=0
I/InputMethodManagerService(  968): Enable input method client, pid=6509
W/BindingManager( 6509): Cannot call determinedVisibility() - never saw a connection for the pid: 6509
D/PMS     (  968): releaseWL(1f187e30): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
I/PhoneStatusBar( 1215): setImeWindowStatus(false,false)
I/ActivityManager(  968): Displayed com.test.thalitest/.MainActivity: +964ms
W/XT9_C   ( 1395): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1395): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1395): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1395): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
D/JsMessageQueue( 6509): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 6509): JniHelper::setJavaVM(0xaae908f8), pthread_self() = -1408657592
,I/chromium( 6509): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41),
,I/HtcModeClient( 3245): handler message = 4011
E/HtcModeClient( 3245): Check connection and retry 12 times.
,E/WifiTrafficPoller(  968): TRAFFIC_STATS_POLL true Token 11 num clients 6
E/WifiTrafficPoller(  968):  packet count Tx=156 Rx=262
,E/WifiTrafficPoller(  968): notifying of data activity 0
D/WIFI_ICON( 1215): WifiActivity: 0
D/StatusBar.NetworkController( 1215): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/PMS     (  968): releaseHCC(a1a89c4): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null
D/PMS     (  968): releaseHCC(34de90ad): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,W/jxcore-log( 6509): Initializing JXcore engine
W/jxcore-log( 6509): JXcore engine is ready
,W/jxcore-log( 6509): Starting JXcore engine
,W/jxcore-log( 6509): Platform android
W/jxcore-log( 6509): 
,W/jxcore-log( 6509): Process ARCH arm
W/jxcore-log( 6509): 
,I/jxcore-log( 6509): JXcore Cordova bridge is ready!
I/jxcore-log( 6509): 
W/jxcore-log( 6509): JXcore engine is started
,I/jxcore-log( 6509): Toggling radios to true
I/jxcore-log( 6509): 
D/BluetoothAdapter( 6509): enable(): BT is already enabled..!
,D/WifiService(  968): New client listening to asynchronous messages
E/WifiTrafficPoller(  968): ADD_CLIENT: 7
,D/WifiManager( 6509): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10366
W/Settings:Agent(  968): MONITOR_LOG
D/WifiService(  968): setWifiEnabled: true pid=6509, uid=10366
W/Settings:Agent(  968): name: wifi_on
E/WifiService(  968): Invoking mWifiStateMachine.setWifiEnabled
W/Settings:Agent(  968): value: 2
I/WifiService(  968): isSprintWifiRestricted(): false
W/Settings:Agent(  968): >> traceCallingStack()
I/WifiService(  968): isMdmWifiRestricted(): false
W/Settings:Agent(  968): Process.myPid(): 968
W/Settings:Agent(  968): Process.myTid(): 1624
W/Settings:Agent(  968): Process.myUid(): 1000
W/Settings:Agent(  968): 
W/Settings:Agent(  968): 
W/System.err(  968): java.lang.Throwable: stack dump
,E/WifiTrafficPoller(  968): TRAFFIC_STATS_POLL true Token 11 num clients 7
D/WIFI_ICON( 1215): WifiActivity: 1
E/WifiTrafficPoller(  968):  packet count Tx=156 Rx=263
,D/StatusBar.NetworkController( 1215): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
E/WifiTrafficPoller(  968): notifying of data activity 1
W/System.err(  968): ,	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  968): 	at android.provider.HtcISettings$Agent.traceCallingStack(HtcISettings.java:56)
W/System.err(  968): 	at android.provider.HtcISettingsGlobal$Agent.monitorKey(HtcISettingsGlobal.java:64)
W/System.err(  968): 	at android.provider.Settings$Global.putStringForUser(Settings.java:7422)
W/System.err(  968): 	at android.provider.Settings$Global.putString(Settings.java:7403)
W/System.err(  968): 	at android.provider.Settings$Global.putInt(Settings.java:7503)
W/System.err(  968): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:154)
W/System.err(  968): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:103)
W/System.err(  968): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:1144)
W/System.err(  968): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:222)
W/System.err(  968): 	at android.os.Binder.execTransact(Binder.java:454)
W/Settings:Agent(  968): 
W/Settings:Agent(  968): << traceCallingStack(): 22(ms)
D/WifiController(  968): handleMessage: E msg.what=155656
D/WifiManager( 6509): disconnect: Base Package Name=com.test.thalitest, uid=10366
D/WifiManager( 6509): reconnect: Base Package Name=com.test.thalitest, uid=10366,
E/WifiStateMachine(  968): handleMessage: E msg.what=131145
E/WifiStateMachine(  968): processMsg: ConnectedState
D/WifiController(  968): processMsg: DeviceActiveState
E/WifiStateMachine(  968):  ConnectedState !CMD_DISCONNECT 0 0
D/WifiController(  968): processMsg: StaEnabledState
D/WifiController(  968): handleMessage: X
E/WifiStateMachine(  968): processMsg: L2ConnectedState
I/jxcore-log( 6509): Radios toggled
I/jxcore-log( 6509): 
,E/WifiStateMachine(  968):  L2ConnectedState !CMD_DISCONNECT 0 0
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
D/wpa_supplicant( 1323): wlan0: Control interface command 'DISCONNECT'
D/wpa_supplicant( 1323): wlan0: Cancelling scan request
D/wpa_supplicant( 1323): wlan0: Request to deauthenticate - bssid=c0:ff:d4:d3:aa:48 pending_bssid=00:00:00:00:00:00 reason=3 state=COMPLETED
D/wpa_supplicant( 1323): TDLS: Tear down peers
D/wpa_supplicant( 1323): wpa_driver_nl80211_disconnect(reason_code=3)
I/jxcore-log( 6509): My device name is: HTC-HTC One M8s
I/jxcore-log( 6509): 
,D/wpa_supplicant( 1323): wlan0: Event DEAUTH (12) received,
D/wpa_supplicant( 1323): wlan0: Deauthentication notification
D/wpa_supplicant( 1323): wlan0:  * reason 3 (locally generated)
D/wpa_supplicant( 1323): Deauthentication frame IE(s) - hexdump(len=0): [NULL]
I/wpa_supplicant( 1323): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1323): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
,E/wpa_supplicant( 1323): enter disconnect check
I/wpa_supplicant( 1323): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/wpa_supplicant( 1323): wlan0: Auto connect disabled: do not try to re-connect
D/wpa_supplicant( 1323): wlan0: Ignore connection failure indication since interface has been put into disconnected state
D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412]
,E/WifiMonitor(  968): WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/WifiMonitor(  968): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  968): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/WifiMonitor(  968): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
D/Tethering(  968): interfaceLinkStateChanged wlan0, false
D/Tethering(  968): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  968): WiFiDisplay: getWifidisplayApEnabled=false
,D/Tethering(  968): TetherInterfaceSM: wlan0: InitialState processMessage what=CMD_INTERFACE_DOWN
V/Tethering(  968): TetherInterfaceSM: wlan0: exit InitialState
V/Tethering(  968): TetherInterfaceSM: wlan0: enter UnavailableState
D/UsbDeviceManager(  968): [USBNET] bCheckSuppFunc: cdc_network
D/Tethering(  968): interfaceLinkStateChanged wlan0, false
D/PMS     (  968): acquireWL(e56ce3e): PARTIAL_WAKE_LOCK  NetworkStats 0x1 968 1000 null
D/Tethering(  968): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  968): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiStateMachine(  968): WiFiDisplay: getWifidisplayApEnabled=false
D/Tethering(  968): sendTetherStateChangedBroadcast 0, 0, 0
D/UsbnetService(  968): BroadcastReceiver::onReceive+
D/UsbnetService(  968): ACTION_TETHER_STATE_CHANGED: active=[],USB_FUNCTION_NCM=false
D/wpa_supplicant( 1323): TDLS: Remove peers on disassociation
D/WifiDisplayAdapter(  968): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  968):     Client/Owner: Client
D/WifiDisplayAdapter(  968):     GroupId: 
D/WifiDisplayAdapter(  968):     Passphrase: 
D/WifiDisplayAdapter(  968):     SessionId: 0
D/WifiDisplayAdapter(  968):     IP Address: }
D/UsbnetService(  968): BroadcastReceiver::onReceive-
D/wpa_supplicant( 1323): wlan0: Disconnect event - remove keys
D/wpa_supplicant( 1323): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1323): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1323): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x559436ef88 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1323):    addr=c0:ff:d4:d3:aa:48
,D/wpa_supplicant( 1323): wlan0: State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1323): nl80211: Set wlan0 operstate 1->0 (DORMANT)
D/wpa_supplicant( 1323): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 1323): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1323): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1323): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1323): nl80211: Skip set_supp_port(unauthorized) while not associated
D/wpa_supplicant( 1323): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1323): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1323): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1323): wlan0: State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1323): nl80211: Set wlan0 operstate 0->0 (DORMANT)
D/wpa_supplicant( 1323): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 1323): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1323): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1323): RTM_NEWLINK: ifi_index=29 ifname=wlan0 operstate=2 linkmode=1 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1323): Wireless event: cmd=0x8b15 len=24
D/wpa_supplicant( 1323): RTM_NEWLINK: ifi_index=29 ifname=wlan0 wext ifi_flags=0x1043 ([UP][RUNNING])
D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/wpa_supplicant( 1323): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1323): nl80211: Ignore disconnect event triggered during reassociation
E/WifiMonitor(  968): WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  968): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  968): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine(  968): transitionTo: destState=DisconnectingState
E/WifiStateMachine(  968): handleMessage: new destination call exit/enter
D/HTCRequest(  968): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  968): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
E/WifiStateMachine(  968): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
E/WifiStateMachine(  968): invokeExitMethods: ConnectedState
E/WifiStateMachine(  968): WifiStateMachine: Leaving Connected state
D/WifiPerfLock(  968): release()
E/WifiStateMachine(  968): PerfLock released for exiting ConnectedState
E/WifiStateMachine(  968): setScanAlarm false period 20000 initial delay 0mAlarmEnabledtrue
E/WifiStateMachine(  968): invokeExitMethods: L2ConnectedState
D/TetherSettings( 5951): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 5951): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 5951): Cust_ConnectToPC   : Modem_Link>false
D/        ( 5951): Cust_ConnectToPC   : spcsc>false
D/        ( 5951): Cust_ConnectToPC   : IPT>true
D/        ( 5951): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 5951): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 5951): hasRemovableStorageSlot: true
D/SmartNS_Utility( 5951): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 5951): onReceive : android.net.conn.TETHER_STATE_CHANGED hasTethered:false isNSOpening:false
E/WifiStateMachine(  968): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$13400 - exit - invokeExitMethods
E/WifiStateMachine(  968): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  968): handleNetworkDisconnect "NG700" nid,=0
E/WifiConfigStore(  968): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
W/WifiHW  (  968): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1323): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1323): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1323): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
E/WifiStateMachine(  968): WiFiDisplay: getWifidisplayApEnabled=false
D/wpa_supplicant( 1323): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1323): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 1323): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1323): CTRL_IFACE: SAVE_CONFIG - Configuration updated
,E/WifiStateMachine(  968): setSuspendOptimizationsNative: 1 true -want false stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
D/wpa_supplicant( 1323): wlan0: Control interface command 'DRIVER POWERMODE 0'
I/wpa_supplicant( 1323): Power_Mode_Type mode = 0
I/wpa_supplicant( 1323): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
D/WifiP2pService(  968): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1323): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/WifiP2pService(  968): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1323): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 8192
D/WifiDataStallTracker(  968): setDhcpActive: false
W/ContextImpl( 5951): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.NSReceiver.onReceive:432 android.app.ActivityThread.handleReceiver:2712 
,D/PMS     (  968): releaseWL(e56ce3e): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
V/NativeCrypto( 1873): Read error: ssl=0x5566e09070: I/O error during system call, Connection timed out
,V/NetworkPolicy(  968): updateNetworkEnabledLocked()
V/NetworkPolicy(  968): updateNotificationsLocked()
E/WifiStateMachine(  968): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
D/PMS     (  968): acquireWL(fc0e49f): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1873 10024 WorkSource{10024 com.google.android.gms}
E/WifiStateMachine(  968): setDetailed state send new extra info<unknown ssid>
E/WifiStateMachine(  968): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  968): [NET] android_getaddrinfofornet+,hn 13(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  968): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  968): NetworkAgent != null
E/WifiStateMachine(  968): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/ConnectivityService(  968): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
E/WifiTrafficPoller(  968): ENABLE_TRAFFIC_STATS_POLL true Token 11
V/NativeCrypto( 1873): SSL shutdown failed: ssl=0x5566e09070: I/O error during system call, Broken pipe
V/NetworkPolicy(  968): mWifiStateReceiver: meteredHint=false,EPS mode=false
,I/SmartNS_Utility( 5951): setISNotification
D/WIFI_ICON( 1215): updateWifiState: NETWORK_STATE_CHANGED connected
E/WifiTrafficPoller(  968):  packet count Tx=156 Rx=263
D/StatusBar.NetworkController( 1215): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
E/WifiTrafficPoller(  968): notifying of data activity 0
D/WIFI_ICON( 1215): WifiActivity: 0
D/SmartNS_Utility( 5951): usb_cable_connect = 1
D/StatusBar.NetworkController( 1215): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/SmartNS_Utility( 5951): usb_denied = 0
D/ConnectivityService(  968): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10024
D/WifiDataStallTracker(  968): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
E/WifiStateMachine(  968): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiDataStallTracker(  968): stopDataStallAlarm 
E/WifiTrafficPoller(  968): ENABLE_TRAFFIC_STATS_POLL false Token 12
E/WifiDataStallTracker(  968): ENABLE_DATA_MONITOR_POLL false Token 1
I/SmartNS_PSService( 5951): usb notificaiton:true
D/libc    (  968): [NET] android_getaddrinfofornet+,hn 6,sn(),hints(known),family 0,flags 4
,D/libc    (  968): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  968): [NET] android_getaddrinfofornet+,hn 25(0x666538303a3a39),sn(),hints(known),family 0,flags 4
D/libc    (  968): [NET] android_getaddrinfofornet-, SUCCESS
I/IntentController( 1215): receive(android.net.wifi.STATE_CHANGE,1,false)
I/IntentController( 1215): receive(android.net.wifi.STATE_CHANGE,1,false)
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  968): ValidatedState{ when=0 what=532488 arg1=10024 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  968): DefaultState{ when=-2ms what=532488 arg1=10024 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine(  968): autoRoamSetBSSID any key="NG700"WPA_PSK
E/WifiConfigStore(  968): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
W/WifiHW  (  968): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1323): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1323): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1323): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
,W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/ConnectivityService(  968): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
E/WifiTrafficPoller(  968): ENABLE_TRAFFIC_STATS_POLL false Token 13
D/wpa_supplicant( 1323): wlan0: Control interface command 'SAVE_CONFIG'
D/PMS     (  968): releaseWL(fc0e49f): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms}
D/wpa_supplicant( 1323): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
I/IntentController( 1215): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/wpa_supplicant( 1323): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1323): CTRL_IFACE: SAVE_CONFIG - Configuration updated
E/WifiStateMachine(  968): moveTempStackToStateStack: i=0,j=4
E/WifiStateMachine(  968): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectingState
E/WifiStateMachine(  968): invokeEnterMethods: DisconnectingState
E/WifiStateMachine(  968):  Enter DisconnectingState State scan interval 300000 mEnableBackgroundScan= false screenOn=true
E/WifiStateMachine(  968): Start Disconnecting Watchdog 1
E/WifiStateMachine(  968): handleMessage: X
E/WifiStateMachine(  968): handleMessage: E msg.what=131146
E/WifiStateMachine(  968): processMsg: DisconnectingState
E/WifiStateMachine(  968):  DisconnectingState !CMD_RECONNECT 0 0
E/WifiStateMachine(  968): processMsg: ConnectModeState
E/WifiStateMachine(  968):  ConnectModeState !CMD_RECONNECT 0 0
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
D/wpa_supplicant( 1323): wlan0: Control interface command 'RECONNECT'
D/wpa_supplicant( 1323): Fast associate: Old scan results
D/wpa_supplicant( 1323): wlan0: Setting scan request: 0.000000 sec
I/wpa_supplicant( 1323): wpa_supplicant_scan enter
D/wpa_supplicant( 1323): wlan0: State: DISCONNECTED -> SCANNING
D/wpa_supplicant( 1323): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 1323): WPS: Building WPS IE for Probe Request
D/wpa_supplicant( 1323): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 1323): WPS:  * Request Type
D/wpa_supplicant( 1323): WPS:  * Config Methods (4288)
D/wpa_supplicant( 1323): WPS:  * UUID-E
D/wpa_supplicant( 1323): WPS:  * Primary Device Type
D/wpa_supplicant( 1323): WPS:  * RF Bands (3)
D/wpa_supplicant( 1323): WPS:  * Association State
D/wpa_supplicant( 1323): WPS:  * Configuration Error (0)
D/wpa_supplicant( 1323): WPS:  * Device Password ID (0)
D/wpa_supplicant( 1323): WPS:  * Manufacturer
D/wpa_supplicant( 1323): WPS:  * Model Name
D/wpa_supplicant( 1323): WPS:  * Model Number
D/wpa_supplicant( 1323): WPS:  * Device Name
D/wpa_supplicant( 1323): WPS:  * Version2 (0x20)
D/wpa_supplicant( 1323): P2P: * P2P IE header
D/wpa_supplicant( 1323): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 1323): P2P: * Listen Channel: Regulatory Class 81 Channel 1
D/wpa_supplicant( 1323): wlan0: Add radio work 'scan'@0x5594371680
D/wpa_supplicant( 1323): wlan0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1323): wlan0: Starting radio work 'scan'@0x5594371680 after 0.000041 second wait
D/wpa_supplicant( 1323): wlan0: nl80211: scan request
E/WifiStateMachine(  968): handleMessage: X
E/WifiStateMachine(  968): handleMessage: E msg.what=147460
E/WifiStateMachine(  968): processMsg: DisconnectingState
D/wpa_supplicant( 1323): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 1323): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/WifiDisplayAdapter(  968): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  968):     Client/Owner: Client
D/WifiDisplayAdapter(  968):     GroupId: 
D/WifiDisplayAdapter(  968):     Passphrase: 
D/WifiDisplayAdapter(  968):     SessionId: 0
D/WifiDisplayAdapter(  968):     IP Address: }
D/wpa_supplicant( 1323): wlan0: nl80211: Scan trigger
D/wpa_supplicant( 1323): wlan0: Event SCAN_STARTED (49) received
D/wpa_supplicant( 1323): wlan0: Own scan request started a scan in 0.000085 seconds
I/wpa_supplicant( 1323): wlan0: CTRL-EVENT-SCAN-STARTED 
D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor(  968): WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
,D/HTCRequest(  968): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine(  968):  DisconnectingState !NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=101538
D/HTCRequest(  968): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine(  968): processMsg: ConnectModeState
D/HTCRequest(  968): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  968): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor(  968): WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  968): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  968): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine(  968):  ConnectModeState !NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=101539
E/WifiStateMachine(  968): ConnectModeState: Network connection lost 
E/WifiStateMachine(  968): transitionTo: destState=DisconnectedState
E/WifiStateMachine(  968): handleMessage: new destination call exit/enter
E/WifiStateMachine(  968): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
E/WifiStateMachine(  968): invokeExitMethods: DisconnectingState
E/WifiStateMachine(  968): moveTempStackToStateStack: i=0,j=4
E/WifiStateMachine(  968): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectedState
E/WifiStateMachine(  968): invokeEnterMethods: DisconnectedState
E/WifiStateMachine(  968): DisconnectedState call setCountryCode()
E/WifiStateMachine(  968):  Enter disconnected State scan interval 300000 mEnableBackgroundScan= false screenOn=true
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN TYPE=ONLY"
D/wpa_supplicant( 1323): wlan0: Control interface command 'SCAN TYPE=ONLY'
D/wpa_supplicant( 1323): Pending scan scheduled - reject new request
E/WifiStateMachine(  968): setScanAlarm true period 10000 initial delay 3000mAlarmEnabledfalse
,E/WifiStateMachine(  968): handleMessage: X
E/WifiStateMachine(  968): handleMessage: E msg.what=131101
E/WifiStateMachine(  968): processMsg: DisconnectedState
E/WifiStateMachine(  968):  DisconnectedState !CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  968): processMsg: ConnectModeState
E/WifiStateMachine(  968): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiStateMachine(  968):  ConnectModeState !CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  968): processMsg: DriverStartedState
E/WifiStateMachine(  968):  DriverStartedState !CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  968): processMsg: SupplicantStartedState
E/WifiStateMachine(  968):  SupplicantStartedState !CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  968): processMsg: DefaultState
,E/WifiStateMachine(  968):  DefaultState !CMD_TETHER_STATE_CHANGE 0 0
D/WifiStateMachine(  968): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  968): Default got CMD_TETHER_STATE_CHANGE
E/WifiStateMachine(  968): handleMessage: X
E/WifiStateMachine(  968): handleMessage: E msg.what=147462
E/WifiStateMachine(  968): processMsg: DisconnectedState
E/WifiStateMachine(  968):  DisconnectedState !SUPPLICANT_STATE_CHANGE_EVENT 32 0 rt=101544  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine(  968): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine(  968): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  968): processMsg: ConnectModeState
E/WifiStateMachine(  968):  ConnectModeState !SUPPLICANT_STATE_CHANGE_EVENT 32 0 rt=101545  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine(  968): handleMessage: X
D/WifiNetworkAgent(  968): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine(  968): handleMessage: E msg.what=147462
E/WifiStateMachine(  968): processMsg: DisconnectedState
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  968): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  968): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  968): Validated
I/ActionCombine( 5951): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal]
D/WIFI_ICON( 1215): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1215): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WIFI_ICON( 1215): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1215): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiStateMachine(  968):  DisconnectedState !SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=101550  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
E/WifiStateMachine(  968): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine(  968): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
E/WifiStateMachine(  968): setDetailed state send new extra info"NG700"
,E/WifiStateMachine(  968): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: DISCONNECTED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
E/WifiStateMachine(  968): NetworkAgent == null
D/WIFI_ICON( 1215): updateWifiState: NETWORK_STATE_CHANGED disconnected
E/WifiStateMachine(  968): [sendNetworkStateChangeBroadcast] NetworkInfo state =SCANNING wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: DISCONNECTED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/StatusBar.NetworkController( 1215): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiTrafficPoller(  968): ENABLE_TRAFFIC_STATS_POLL false Token 14
D/WIFI_ICON( 1215): updateWifiState: NETWORK_STATE_CHANGED disconnected
E/WifiStateMachine(  968): processMsg: ConnectModeState
D/StatusBar.NetworkController( 1215): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
I/IntentController( 1215): receive(android.net.wifi.STATE_CHANGE,1,false)
,E/WifiStateMachine(  968):  ConnectModeState !SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=101555  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
E/WifiStateMachine(  968): handleMessage: X
I/IntentController( 1215): receive(android.net.wifi.STATE_CHANGE,1,false)
D/SmartNS_Utility( 5951): usb_cable_connect = 1
D/SmartNS_Utility( 5951): usb_denied = 0
I/SmartNS_PSService( 5951): usb notificaiton:true
E/WifiStateMachine(  968): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiTrafficPoller(  968): ENABLE_TRAFFIC_STATS_POLL false Token 15
,D/DotMatrix( 1324): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
,I/RemoteViews( 1215): reapply : com.android.settings 1 36
D/SmartNS_NSReceiver( 5951): Tethered state change:false isNSOpening:false
,D/DotMatrix( 1324): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
,I/QuickSettingWifi( 1215): receive.wifiConnect:true wifiAPname:<unknown ssid> elapse:0
,I/QuickSettingWifi( 1215): receive.wifiConnect:false wifiAPname:null elapse:14,
,I/RemoteViews( 1215): reapply : com.android.settings 1 36
I/QuickSettingWifi( 1215): receive.wifiConnect:false wifiAPname:null elapse:0
I/QuickSettingWifi( 1215): receive.wifiConnect:false wifiAPname:null elapse:1
,I/QuickSettingWifi( 1215): receive.wifiConnect:false wifiAPname:null elapse:0
,D/WISPrService( 5951): >>>>>WISPrService start isConnected = true<<<<<
,E/WifiTrafficPoller(  968): ADD_CLIENT: 8
D/WifiService(  968): New client listening to asynchronous messages,
D/ConnectivityService(  968): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  968):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  968):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  968): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  968): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  968): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/Nat464Xlat(  968): requiresClat: netType=1, connected=false, mIsClatEnabled=true, hasIPv4Address=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  968): Disconnected - quitting
D/ConnectivityManager.CallbackHandler( 1215): CM callback handler got msg 524292
,I/SecurityController( 1215): onLost 100
,E/WifiStateMachine(  968): handleMessage: E msg.what=131131,
D/ConnectivityService(  968): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/WifiStateMachine(  968): processMsg: DisconnectedState
E/WifiStateMachine(  968):  DisconnectedState !CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine(  968): processMsg: ConnectModeState
E/WifiStateMachine(  968):  ConnectModeState !CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
D/ConnectivityService(  968): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isSkipMobile=false
E/WifiStateMachine(  968): handleMessage: X
D/WIFI    (  968): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/usbnet  (  968): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  968):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/WIFI    (  968): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] released
E/WifiStateMachine(  968): enter WifiNetworkFactory startNetwork. mIPTStart:false
,D/usbnet  (  968):   my score=70, my filter=[ Transports:  Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/usbnet  (  968): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
D/NetworkManagementService(  968): Removing idletimer
,W/WISPrService( 5951): can not find out wificonfig: SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false,
D/WISPrService( 5951): trigger connection
D/WISPrService( 5951): continue
D/WISPrService( 5951): start DataConnection
D/libc    ( 5951): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 4
D/libc    ( 5951): [NET] android_getaddrinfofornet-, err=8
D/WISPrService( 5951): >>>>>WISPrService start isConnected = false<<<<<
D/WifiService(  968): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=httpproxy
D/WISPrService( 5951): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/PMS     (  968): acquireWL(3e1f81b5): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 968 1000 null
,D/CSLegacyTypeTracker(  968): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=false
D/ConnectivityService(  968): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/libc    ( 5951): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
D/libc    ( 5951): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 5951): [NET] android_getaddrinfo_proxy+
,D/libc    ( 5951): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  394): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  394): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 5951): [NET] android_getaddrinfo_proxy-, NODATA
,I/ActivityManager(  968): Start proc com.htc.bgp for broadcast com.htc.flexnet/.AndroidIntentReceiver: pid=6602 uid=10011 gids={50011, 9997, 1028, 1015, 5001, 5011, 2001, 3003} abi=arm64-v8a
,D/WISPrService( 5951): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 5951): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/libc    ( 5951): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 4
D/libc    ( 5951): [NET] android_getaddrinfofornet-, err=8
,D/WISPrService( 5951): exception: java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,D/WISPrService( 5951): >>>>>WISPrService start isConnected = false<<<<<
I/ActivityManager(  968): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=6616 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a,
D/WISPrService( 5951): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/ConnectivityService(  968): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/Tethering(  968): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
E/ConnectivityService(  968): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/Tethering(  968): TetherMasterSM: InitialState processMessage what=UPSTREAM_CHANGED
E/ConnectivityService(  968): EVENT_NETWORK_VALIDATED - isLiveNetworkAgent found mismatched netId: null - NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::92e7:c4ff:fee6:4cf8/64,192.168.1.130/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/WifiService(  968): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=callernameid
V/NetworkPolicy(  968): ensureActiveMobilePolicyLocked()
D/PMS     (  968): acquireWL(13ed904a): PARTIAL_WAKE_LOCK  NetworkStats 0x1 968 1000 null
D/DATA_ICON( 1215): updateConnectivity android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE Type:-1/Status:0
D/NetworkPolicy(  968): ensureActiveMobilePolicyLocked: SIM state invalid, slotId= -1000, subId=-1000 . Return.
V/NetworkPolicy(  968): updateNetworkEnabledLocked()
,V/NetworkPolicy(  968): updateIfacesLocked()
V/NetworkPolicy(  968): updateNotificationsLocked()
D/WISPrService( 5951): >>>>>WISPrService start isConnected = false<<<<<
D/DATA_ICON( 1215): dataConnected: false/false
D/StatusBar.NetworkController( 1215): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,D/PMS     (  968): releaseWL(13ed904a): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/NetworkManagementService(  968): isBandwidthControlEnabled: doneSignal.getCount()= 0
,D/WISPrService( 5951): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WifiService(  968): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=verizon
,D/WifiService(  968): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=fota
,V/NetworkPolicy(  968): updateNetworkEnabledLocked()
V/NetworkPolicy(  968): updateNotificationsLocked()
,D/WifiService(  968): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=supl
,D/WifiService(  968): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=emergency,
W/ResourcesManager( 6602): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/WifiService(  968): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=verizon800
,D/WifiService(  968): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=hipri
,D/WifiService(  968): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=ims
,D/WifiService(  968): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=default
,D/WifiService(  968): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=mms
,D/WifiService(  968): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=cbs
,D/WifiService(  968): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=ia
I/CalendarProvider2( 6602): Created com.android.providers.calendar.CalendarAlarmManager@3fdc8659(com.htc.providers.calendar.HtcCalendarProvider@23aa821e)
,I/ActivityManager(  968): Start proc com.htc.mobiledata:remote for service com.htc.mobiledata/.MobileDataService: pid=6646 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a
,D/WifiService(  968): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=dun
,D/CalendarProvider2( 6602): wait start:true
,D/WifiService(  968): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=internet
,D/Process (  968): killProcessQuiet, pid=5857,
I/ActivityManager(  968): Killing 5857:com.htc.calendar/u0a10 (adj 15): empty #17,
D/Process (  968): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.removeContentProvider:10141 
,I/ActivityManager(  968): Recipient 5857
,E/WifiStateMachine(  968): handleMessage: E msg.what=131155
E/WifiStateMachine(  968): processMsg: DisconnectedState
E/WifiStateMachine(  968):  DisconnectedState !CMD_RSSI_POLL 1 0 0x 00:00:00:00:00:00 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1459821834] gl hn u24 rssi=-52 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  968): processMsg: ConnectModeState
E/WifiStateMachine(  968):  ConnectModeState !CMD_RSSI_POLL 1 0 0x 00:00:00:00:00:00 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1459821832] gl hn u24 rssi=-52 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  968): processMsg: DriverStartedState
E/WifiStateMachine(  968):  DriverStartedState !CMD_RSSI_POLL 1 0 0x 00:00:00:00:00:00 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1459821831] gl hn u24 rssi=-52 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  968): processMsg: SupplicantStartedState
E/WifiStateMachine(  968):  SupplicantStartedState !CMD_RSSI_POLL 1 0 0x 00:00:00:00:00:00 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1459821830] gl hn u24 rssi=-52 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  968): processMsg: DefaultState
E/WifiStateMachine(  968):  DefaultState !CMD_RSSI_POLL 1 0 0x 00:00:00:00:00:00 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:0] from screen [on:0 period:-1459821830] gl hn u24 rssi=-52 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  968): handleMessage: X
,D/Process (  968): killProcessQuiet, pid=5929,
I/ActivityManager(  968): Killing 5929:com.google.android.partnersetup/u0a27 (adj 15): empty #17
D/Process (  968): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.appDiedLocked:5130 
,D/FlexNetS( 6602): updateSvcAllowedInSettings:false,
D/CalendarProvider2( 6602): wait end:false
,I/ActivityManager(  968): Recipient 5929
,D/MdScPhnSt( 6646): [15d.2.]  listen tmrbb8
,D/MdProvGlob( 6616): add item 101 (2:g3d6) for 15:android.intent.action.PRECISE_DATA_CONNECTION_STATE_CHANGED
,D/FlexNetS( 6602): updateSvcAllowedInSettings:false
,D/FlexNetS( 6602): updateSvcAllowedInSettings:false
,D/FlexNetS( 6602): updateSvcAllowedInSettings:false
,D/FlexNetS( 6602): updateSvcAllowedInSettings:false
,D/FlexNetS( 6602): updateSvcAllowedInSettings:false
,D/FlexNetS( 6602): updateSvcAllowedInSettings:false,
,D/FlexNetS( 6602): updateSvcAllowedInSettings:false,
,D/FlexNetS( 6602): updateSvcAllowedInSettings:false
,D/FlexNetS( 6602): updateSvcAllowedInSettings:false,
,D/FlexNetS( 6602): updateSvcAllowedInSettings:false
,D/MdProvGlob( 6616): remove item 101 (p3d9in88) for 15:android.intent.action.ANY_DATA_STATE
,D/MdScDataSum( 6646): [15d.2.] summary 118:p3 ignore
,D/MdProvGlob( 6616): remove item 101 (p3in8) for 15:android.intent.action.ANY_DATA_STATE
,D/FlexNetS( 6602): updateSvcAllowedInSettings:false
,D/MdProvGlob( 6616): remove item 101 (p3in6) for 15:android.intent.action.ANY_DATA_STATE,
,D/FlexNetS( 6602): updateSvcAllowedInSettings:false,
,D/FlexNetS( 6602): updateSvcAllowedInSettings:false
,D/MdProvGlob( 6616): remove item 101 (p3d2in18) for 15:android.intent.action.ANY_DATA_STATE
,D/FlexNetS( 6602): updateSvcAllowedInSettings:false
,D/MdProvGlob( 6616): remove item 101 (p3in10) for 15:android.intent.action.ANY_DATA_STATE
,D/MdProvGlob( 6616): remove item 101 (p3in6) for 15:android.intent.action.ANY_DATA_STATE
,D/MdProvGlob( 6616): remove item 101 (p3d1in11) for 15:android.intent.action.ANY_DATA_STATE,
,D/MdProvGlob( 6616): remove item 101 (p3in8) for 15:android.intent.action.ANY_DATA_STATE,
,D/MdProvGlob( 6616): remove item 101 (p3d1in9) for 15:android.intent.action.ANY_DATA_STATE
,E/WifiTrafficPoller(  968): TRAFFIC_STATS_POLL false Token 16 num clients 8,
,D/Process (  968): killProcessQuiet, pid=6310
I/ActivityManager(  968): Killing 6310:com.htc.cs.dm/u0a99 (adj 15): empty #17
D/Process (  968): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.removeContentProvider:10141 
,E/WifiTrafficPoller(  968): TRAFFIC_STATS_POLL false Token 16 num clients 8,
,I/ActivityManager(  968): Recipient 6310,
,D/Process (  968): killProcessQuiet, pid=6336
I/ActivityManager(  968): Killing 6336:com.htc.providers.settings:remote/u0a13 (adj 15): empty #17
D/Process (  968): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  968): Recipient 6336,
,I/CalendarProvider2( 6602): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: },
W/ContentResolver( 6602): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/ActivityManager(  968): Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=6679 uid=10010 gids={50010, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  968): Killing 6019:com.google.android.gms:car/u0a24 (adj 15): empty #17
,D/Process (  968): killProcessQuiet, pid=6019
D/Process (  968): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  968): Recipient 6019
,W/ResourcesManager( 6679): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.,
,D/CalendarApplication( 6679): onCreate,
D/ProviderChangeReceiver( 6679): ---------------------------------------------------,
D/ProviderChangeReceiver( 6679): ProviderChangeReceiver onReceive, start HtcAlertService to update notification!
,I/ActivityManager(  968): Killing 6366:com.google.android.apps.docs/u0a101 (adj 15): empty #17,
,D/Process (  968): killProcessQuiet, pid=6366
D/Process (  968): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processNextBroadcast:706 
,D/HtcAlertService( 6679): start to updateAlertNotification!
,I/ActivityManager(  968): Recipient 6366
,D/HtcAlertService( 6679): No fired or scheduled alerts
D/HtcAlertUtils( 6679): -- cancelReminderNotification --
,D/HtcAlertUtils( 6679): broadcastExistReminder!,
D/DotMatrix( 1324): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/wpa_supplicant( 1323): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 1323): wlan0: nl80211: New scan results available
W/ContextImpl(  968): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:14146 com.android.server.wifi.WifiStateMachine.handleMediaLinkEvent:14311 com.android.server.wifi.WifiStateMachine.access$6000:268 com.android.server.wifi.WifiStateMachine$SupplicantStartedState.processMessage:8091 
D/wpa_supplicant( 1323): nl80211: Scan included frequencies: 2412 2417 2422 2427 2432 2437 2442 2447 2452 2457 2462 2467 2472 5180 5200 5220 5240 5260 5280 5300 5320 5500 5520 5540 5560 5580 5600 5620 5640 5660 5680 5700
D/wpa_supplicant( 1323): wlan0: Event SCAN_RESULTS (3) received
I/wpa_supplicant( 1323): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1323): wlan0: Scan completed in 2.073881 seconds
D/wpa_supplicant( 1323): nl80211: Received scan results (4 BSSes)
I/wpa_supplicant( 1323): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1323): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1323): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-58
I/wpa_supplicant( 1323): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-77
D/wpa_supplicant( 1323): wlan0: BSS: Start scan result update 6
D/wpa_supplicant( 1323): wlan0: BSS: Add new id 3 BSSID c2:ff:d4:d3:aa:48 SSID '01ABC'
D/wpa_supplicant( 1323): BSS: last_scan_res_used=4/32
D/wpa_supplicant( 1323): wlan0: New scan results available (own=1 ext=0)
D/wpa_supplicant( 1323): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1323): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1323): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1323): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1323): wlan0: Radio work 'scan'@0x5594371680 done in 2.074786 seconds
D/wpa_supplicant( 1323): wlan0: Selecting BSS from priority group 615
D/wpa_supplicant( 1323): wlan0: 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 caps=0x511 level=-49 wps
D/wpa_supplicant( 1323): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1323): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 1323): wlan0: 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-57 wps
D/wpa_supplicant( 1323): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1323): wlan0:    selected based on RSN IE
W/wpa_supplicant( 1323): [EAP-MSG] EAP wpa_supplicant_check_sim@842: eap_methods not available
D/wpa_supplicant( 1323):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
D/wpa_supplicant( 1323): wlan0:    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700'
D/wpa_supplicant( 1323): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0x5594370c00  current_ssid=0x0
D/wpa_supplicant( 1323): wlan0: Request association with c0:ff:d4:d3:aa:48
,D/wpa_supplicant( 1323): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1323): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=7): 00 05 4e 47 37 30 30
D/wpa_supplicant( 1323): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 03 01 01
D/wpa_supplicant( 1323): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 2a 01 00
D/wpa_supplicant( 1323): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 08 04 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1323): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 1323): WPA: WMM Parameter Element - hexdump(len=24): 00 50 f2 02 01 01 80 00 03 a4 00 00 27 a4 00 00 42 43 5e 00 62 32 2f 00
D/wpa_supplicant( 1323): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1323): TDLS: TDLS is allowed in the target BSS
D/wpa_supplicant( 1323): wlan0: Add radio work 'connect'@0x5594371680
D/wpa_supplicant( 1323): wlan0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1323): wlan0: Starting radio work 'connect'@0x5594371680 after 0.000049 second wait
I/wpa_supplicant( 1323): check if in concurrent case
I/wpa_supplicant( 1323): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/wpa_supplicant( 1323): FT: Stored MDIE and FTIE from (Re)Association Response - hexdump(len=0):
D/wpa_supplicant( 1323): wlan0: Cancelling scan request
D/wpa_supplicant( 1323): wpas_start_assoc_cb, 1892
D/wpa_supplicant( 1323): wpas_start_assoc_cb, 1895
D/wpa_supplicant( 1323): wpas_start_assoc_cb, 1910
D/wpa_supplicant( 1323): wlan0: WPA: clearing own WPA/RSN IE
D/wpa_supplicant( 1323): wlan0: Automatic auth_alg selection: 0x1
D/wpa_supplicant( 1323): RSN: PMKSA cache search - network_ctx=0x5594370c00 try_opportunistic=0
D/wpa_supplicant( 1323): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1323): RSN: No PMKSA cache entry found
D/wpa_supplicant( 1323): wlan0: RSN: using IEEE 802.11i/D9.0
D/wpa_supplicant( 1323): wlan0: WPA: Selected cipher suites: group 16 pairwise 16 key_mgmt 2 proto 2
D/wpa_supplicant( 1323): wlan0: WPA: Selected mgmt group cipher 32
D/wpa_supplicant( 1323): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 1323): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1323): wlan0: WPA: using GTK CCMP
D/wpa_supplicant( 1323): wlan0: WPA: using PTK CCMP
D/wpa_supplicant( 1323): wlan0: WPA: using KEY_MGMT WPA-PSK
D/wpa_supplicant( 1323): wlan0: WPA: not using MGMT group cipher
D/wpa_supplicant( 1323): WPA: Set own WPA IE default - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1323): wlan0: State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1323): nl80211: Set wlan0 operstate 0->0 (DORMANT)
D/wpa_supplicant( 1323): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 1323): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1323): nl80211: Set mode ifindex 29 iftype 2 (STATION)
D/wpa_supplicant( 1323): nl80211: Unsubscribe mgmt frames handle 0x888888dd1cbf8989 (mode change)
D/wpa_supplicant( 1323): nl80211: Subscribe to mgmt frames with non-AP handle 0x5594370100
D/wpa_supplicant( 1323): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5594370100 match=0104
D/wpa_supplicant( 1323): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5594370100 match=040a
D/wpa_supplicant( 1323): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5594370100 match=040b
D/wpa_supplicant( 1323): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5594370100 match=040c
D/wpa_supplicant( 1323): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5594370100 match=040d
D/wpa_,supplicant( 1323): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5594370100 match=090a
D/wpa_supplicant( 1323): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5594370100 match=090b
D/wpa_supplicant( 1323): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5594370100 match=090c
D/wpa_supplicant( 1323): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5594370100 match=090d
D/wpa_supplicant( 1323): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5594370100 match=0409506f9a09
D/wpa_supplicant( 1323): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5594370100 match=7f506f9a09
D/wpa_supplicant( 1323): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5594370100 match=0801
D/wpa_supplicant( 1323): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5594370100 match=040e
D/wpa_supplicant( 1323): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5594370100 match=06
D/wpa_supplicant( 1323): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5594370100 match=0a07
D/wpa_supplicant( 1323): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5594370100 match=0a11
D/wpa_supplicant( 1323): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5594370100 match=0a1a
D/wpa_supplicant( 1323): nl80211: Connect (ifindex=29)
D/wpa_supplicant( 1323):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1323):   * bssid_hint=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1323):   * freq=2412
D/wpa_supplicant( 1323):   * freq_hint=2412
D/wpa_supplicant( 1323):   * SSID - hexdump(len=5): 4e 47 37 30 30
D/wpa_supplicant( 1323):   * IEs - hexdump(len=30): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00 7f 06 00 00 0a 82 00 40
D/wpa_supplicant( 1323):   * WPA Versions 0x2
D/wpa_supplicant( 1323):   * pairwise=0xfac04
D/wpa_supplicant( 1323):   * group=0xfac04
D/wpa_supplicant( 1323):   * akm=0xfac02
D/wpa_supplicant( 1323):   * Auth Type 0
D/wpa_supplicant( 1323): nl80211: set key mgmt offload, suite 2, support 0x0, psk 0x0x5594370c3a
D/wpa_supplicant( 1323): nl80211: Connect request send successfully
D/wpa_supplicant( 1323): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 1323): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1323): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1323): EAPOL: External notification - portControl=Auto
D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 3 c2:ff:d4:d3:aa:48]
E/WifiMonitor(  968): WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor(  968): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
E/WifiStateMachine(  968): handleMessage: E msg.what=147461
E/WifiStateMachine(  968): processMsg: DisconnectedState
D/WifiMonitor(  968): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiMonitor(  968): WifiMonitor:wlan0 cnt=37 dispatchEvent: WPS-AP-AVAILABLE 
E/WifiStateMachine(  968):  DisconnectedState !SCAN_RESULTS_EVENT 0 0 found=3 known=1 got=3 dur:78 bcn=0
E/WifiStateMachine(  968): processMsg: ConnectModeState
W/WifiMonitor(  968): couldn't identify event type - WPS-AP-AVAILABLE 
E/WifiStateMachine(  968):  ConnectModeState !SCAN_RESULTS_EVENT 0 0 found=3 known=1 got=3 dur:78 bcn=0
E/WifiStateMachine(  968): processMsg: DriverStartedState
D/WifiMonitor(  968): Event [IFNAME=wlan0 Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)]
E/WifiStateMachine(  968):  DriverStartedState !SCAN_RESULTS_EVENT 0 0 found=3 known=1 got=3 dur:78 bcn=0
E/WifiStateMachine(  968): processMsg: SupplicantStartedState
E/WifiMonitor(  968): WifiMonitor:wlan0 cnt=38 dispatchEvent: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
E/WifiStateMachine(  968):  SupplicantStartedState !SCAN_RESULTS_EVENT 0 0 found=3 known=1 got=3 dur:78 bcn=0
D/WifiStateMachine(  968): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
W/WifiHW  (  968): QCOM De,bug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1323): wlan0: Control interface command 'LIST_DONGLES'
D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor(  968): WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  968): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine(  968): [1,454,534,093,120 ms] noteScanEnd no scan source
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/wpa_supplicant( 1323): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
D/HTCRequest(  968): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  968): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  968): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
E/WifiStateMachine(  968): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@3c707876 sup_state=SCANNING debouncing=false
E/WifiAutoJoinController (  968): NG7005g c0:ff:d4:d3:aa:4a rssi=-49 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiAutoJoinController (  968): NG700 c0:ff:d4:d3:aa:48 rssi=-57 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiConfigStore(  968): updateSavedNetworkHistory(): try "NG700"WPA_PSK SSID="NG700" NG700 [WPA2-PSK-CCMP][WPS][ESS] ajst=0
E/WifiConfigStore(  968): updateSavedNetworkHistory: HTC improve mode
E/WifiConfigStore(  968):         got known scan result c0:ff:d4:d3:aa:48 key : "NG700"WPA_PSK num: 1 rssi=-57 freq=2412
E/WifiAutoJoinController (  968): Gonzos 38:f8:89:11:e9:11 rssi=-77 cap [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS] is not scored
E/WifiAutoJoinController (  968): 01ABC c2:ff:d4:d3:aa:48 rssi=-58 cap [WPA2-PSK-CCMP][ESS] is not scored
E/WifiAutoJoinController (  968): ageScanResultsOut delay 40000 size 4 now 1454534093123
E/WifiAutoJoinController (  968): newSupplicantResults size=4 known=1 true
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 STATUS-NO_EVENTS"
D/wpa_supplicant( 1323): wlan0: Control interface command 'STATUS-NO_EVENTS'
E/WifiAutoJoinController (  968): attemptAutoJoin() status=wpa_state=ASSOCIATING
E/WifiAutoJoinController (  968): p2p_device_address=92:e7:c4:e6:4c:f8
E/WifiAutoJoinController (  968): address=XX:XX:XX:XX:XX:XX
E/WifiAutoJoinController (  968): uuid=12345678-9abc-def0-1234-56789abcdef1 split=4
E/WifiAutoJoinController (  968): attemptAutoJoin: bail out due to sup state wpa_state=ASSOCIATING
D/WIFI_ICON( 1215): updateWifiState: NETWORK_STATE_CHANGED disconnected
E/WifiConfigStore(  968):  writeKnownNetworkHistory() num networks:1 needWrite=false
D/StatusBar.NetworkController( 1215): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiStateMachine(  968): handleMessage: X
E/WifiStateMachine(  968): handleMessage: E msg.what=131213
E/WifiStateMachine(  968): processMsg: DisconnectedState
E/WifiStateMachine(  968):  DisconnectedState !CMD_TARGET_BSSID 38 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=103626
E/WifiStateMachine(  968): processMsg: ConnectModeState
E/WifiStateMachine(  968):  ConnectModeState !CMD_TARGET_BSSID 38 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=103626
E/WifiStateMachine(  968): processMsg: DriverStartedState
E/WifiStateMachine(  968):  DriverStartedState !CMD_TARGET_BSSID 38 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=103626
E/WifiStateMachine(  968): processMsg: SupplicantStartedState
E/WifiStateMachine(  968):  SupplicantStartedState !CMD_TARGET_BSSID 38 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=103627
E/WifiStateMachine(  968): handleMessage: X
E/WifiStateMachine(  968): handleMessage: E msg.what=147462
E/WifiStateMachine(  968): processMsg: DisconnectedState
E/WifiStateMachine(  968):  DisconnectedState !SUPPLICANT_STATE_CHANGE_EVENT 39 0 rt=103627  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
E/WifiStateMachine(  96,8): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine(  968): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine(  968): setDetailed state send new extra info0x
E/WifiStateMachine(  968): [sendNetworkStateChangeBroadcast] NetworkInfo state =SCANNING wifi info = SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
E/WifiTrafficPoller(  968): ENABLE_TRAFFIC_STATS_POLL false Token 16
I/IntentController( 1215): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  968): NetworkAgent == null
E/WifiStateMachine(  968): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTING wifi info = SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
E/WifiStateMachine(  968): processMsg: ConnectModeState
E/WifiStateMachine(  968):  ConnectModeState !SUPPLICANT_STATE_CHANGE_EVENT 39 0 rt=103640  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
E/WifiTrafficPoller(  968): ENABLE_TRAFFIC_STATS_POLL false Token 17
E/WifiStateMachine(  968): handleMessage: X
D/WIFI_ICON( 1215): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1215): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
I/IntentController( 1215): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WISPrService( 5951): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 5951): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WISPrService( 5951): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 5951): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,I/QuickSettingWifi( 1215): receive.wifiConnect:false wifiAPname:null elapse:0,
,I/QuickSettingWifi( 1215): receive.wifiConnect:false wifiAPname:null elapse:1,
,D/wpa_supplicant( 1323): Wireless event: cmd=0x8c02 len=271,
I/wpa_supplicant( 1323): WEXT: Custom wireless event: 'BEACONIEs='
D/wpa_supplicant( 1323): RTM_NEWLINK: ifi_index=29 ifname=wlan0 wext ifi_flags=0x1003 ([UP]),
D/wpa_supplicant( 1323): Wireless event: cmd=0x8c02 len=152
I/wpa_supplicant( 1323): WEXT: Custom wireless event: 'BEACONIEs='
,D/wpa_supplicant( 1323): RTM_NEWLINK: ifi_index=29 ifname=wlan0 wext ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1323): Wireless event: cmd=0x8b15 len=24
D/WIFI_ICON( 1215): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/wpa_supplicant( 1323): RTM_NEWLINK: ifi_index=29 ifname=wlan0 wext ifi_flags=0x1003 ([UP])
D/StatusBar.NetworkController( 1215): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/wpa_supplicant( 1323): RTM_NEWLINK: ifi_index=29 ifname=wlan0 operstate=5 linkmode=1 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1323): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1323): wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00)
D/wpa_supplicant( 1323): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1323): nl80211: Connect event
D/wpa_supplicant( 1323): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1323): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1323): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
D/wpa_supplicant( 1323): wlan0: Event ASSOC (0) received
,D/wpa_supplicant( 1323): wlan0: Association info event
D/wpa_supplicant( 1323): req_ies - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1323): resp_ies - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1323): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1323): wlan0: freq=2412 MHz
D/wpa_supplicant( 1323): WPA: set own WPA/RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1323): FT: Stored MDIE and FTIE from (Re)Association Response - hexdump(len=0):
D/wpa_supplicant( 1323): wlan0: State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1323): nl80211: Set wlan0 operstate 0->0 (DORMANT)
D/wpa_supplicant( 1323): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 1323): wlan0: Associated to a new BSS: BSSID=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1323): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 1323): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
I/wpa_supplicant( 1323): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WIFI_ICON( 1215): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/wpa_supplicant( 1323): wlan0: WPA: Association event - clear replay counter
D/StatusBar.NetworkController( 1215): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/wpa_supplicant( 1323): wlan0: WPA: Clear old PTK
D/wpa_supplicant( 1323): TDLS: Remove peers on association
D/wpa_supplicant( 1323): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1323): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1323): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1323): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1323): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1323): EAPOL: enable timer tick
D/wpa_supplicant( 1323): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1323): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 1323): wlan0: Cancelling scan request
D/wpa_supplicant( 1323): wlan0: Process pending EAPOL frame that was received just before association notification
D/wpa_supplicant( 1323): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1323): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 1323): wlan0: IEEE 802.1X RX: version=2 type=3 length=95
D/wpa_supplicant( 1323): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 1323): wlan0:   key_info 0x8a (ver=2 keyidx=0 rsvd=0 Pairwise Ack)
D/wpa_supplicant( 1323): wlan0:   key_length=16 key_data_length=0
,D/wpa_supplicant( 1323):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 1323):   key_nonce - hexdump(len=32): 50 03 b8 6c ad 69 31 b0 db 97 83 43 8b 87 27 78 5a c4 93 4b f9 09 f5 11 3e f0 97 84 e7 fd 4b 06
D/wpa_supplicant( 1323):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1323):   key_rsc - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1323):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1323):   key_mic - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1323): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1323): wlan0: WPA: RX message 1 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 1323): RSN: msg 1/4 key data - hexdump(len=0):
D/wpa_supplicant( 1323): WPA: Renewed SNonce - hexdump(len=32): 76 a0 19 09 de 7b cd 1d a8 99 8b a6 55 00 35 0b a4 6b 0b 87 54 74 67 b2 d4 23 51 0d eb 5e d6 9a
D/wpa_supplicant( 1323): WPA: Nonce1 - hexdump(len=32): 76 a0 19 09 de 7b cd 1d a8 99 8b a6 55 00 35 0b a4 6b 0b 87 54 74 67 b2 d4 23 51 0d eb 5e d6 9a
D/wpa_supplicant( 1323): WPA: Nonce2 - hexdump(len=32): 50 03 b8 6c ad 69 31 b0 db 97 83 43 8b 87 27 78 5a c4 93 4b f9 09 f5 11 3e f0 97 84 e7 fd 4b 06
D/wpa_supplicant( 1323): WPA: PMK - hexdump(len=32): [REMOVED]
D/wpa_supplicant( 1323): WPA: PTK - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 1323): WPA: WPA IE for msg 2/4 - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1323): WPA: Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 1323): wlan0: WPA: Sending EAPOL-Key 2/4
D/wpa_supplicant( 1323): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 1323): WPA: Derived Key MIC - hexdump(len=16): 47 0f dd e4 bd f6 67 3b b1 8f d0 00 ae 7e 3f 3f
I/wpa_supplicant( 1323): htc_wext_set_keepalive +
,I/wpa_supplicant( 1323): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1323): getPrivFuncNum +	
I/wpa_supplicant( 1323): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1323): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1323): htc_wext_set_keepalive - ret = 0
D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
E/WifiMonitor(  968): WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  968): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  968): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  968): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  968): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
D/WifiMonitor(  968): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412]
E/WifiMonitor(  968): WifiMonitor:wlan0 cnt=41 dispatchEvent: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  968): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
E/WifiStateMachine(  968): handleMessage: E msg.what=147462
D/WifiMonitor(  968): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  968): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
E/WifiStateMachine(  968): processMsg: DisconnectedState
D/HTCRequest(  968): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  968): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  968): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  968): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  968): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  968): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor(  968): WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  968): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  968): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  968): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
E/WifiStateMachine(  968):  DisconnectedState !SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=103724  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine(  968): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine(  968): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
D/WifiMonitor(  968): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
E/WifiStateMachine(  968): processMsg: ConnectModeState
E/WifiStateMachine(  968):  ConnectModeState !SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=103725  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine(  968): handleMessage: X
E/WifiStateMachine(  968): handleMessage: E msg.what=147500
E/WifiStateMachine(  968): processMsg: DisconnectedState
E/WifiStateMachine(  968):  DisconnectedState !what:147500 0 0
E/WifiStateMachine(  968): processMsg: ConnectModeState
D/Tethering(  968): interfaceLinkStateChanged wlan0, false
D/Tethering(  968): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  968): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiStateMachine(  968):  ConnectModeState !what:147500 0 0
D/WifiStateMachine(  968): Enter handleAssociatedWithEvent
D/WifiStateMachine(  968): Associated
D/WifiStateMachine(  968): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/Tethering(  9,68): interfaceLinkStateChanged wlan0, false
D/WifiStateMachine(  968): Exit handleAssociatedWithEvent
D/Tethering(  968): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  968): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiStateMachine(  968): handleMessage: X
E/WifiStateMachine(  968): handleMessage: E msg.what=147462
E/WifiStateMachine(  968): processMsg: DisconnectedState
D/UsbDeviceManager(  968): [USBNET] bCheckSuppFunc: cdc_network
D/Tethering(  968): interfaceLinkStateChanged wlan0, false
D/PMS     (  968): acquireWL(114a90dd): PARTIAL_WAKE_LOCK  NetworkStats 0x1 968 1000 null
D/Tethering(  968): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  968): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiStateMachine(  968):  DisconnectedState !SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=103727  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
E/WifiStateMachine(  968): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
D/Tethering(  968): interfaceLinkStateChanged wlan0, true
D/Tethering(  968): interfaceStatusChanged wlan0, true
E/WifiStateMachine(  968): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  968): WiFiDisplay: getWifidisplayApEnabled=false
D/wpa_supplicant( 1323): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1323): wlan0: IEEE 802.1X RX: version=2 type=3 length=151
D/wpa_supplicant( 1323): wlan0:   EAPOL-Key type=2
E/WifiStateMachine(  968): setDetailed state send new extra info"NG700"
D/wpa_supplicant( 1323): wlan0:   key_info 0x13ca (ver=2 keyidx=0 rsvd=0 Pairwise Install Ack MIC Secure Encr)
D/wpa_supplicant( 1323): wlan0:   key_length=16 key_data_length=56
D/wpa_supplicant( 1323):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 02
D/wpa_supplicant( 1323):   key_nonce - hexdump(len=32): 50 03 b8 6c ad 69 31 b0 db 97 83 43 8b 87 27 78 5a c4 93 4b f9 09 f5 11 3e f0 97 84 e7 fd 4b 06
D/wpa_supplicant( 1323):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1323):   key_rsc - hexdump(len=8): 97 66 00 00 00 00 00 00
D/wpa_supplicant( 1323):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1323):   key_mic - hexdump(len=16): 2f 82 cf 0a 75 7a 62 0f ec 01 a4 df d1 9d 3b 17
V/Tethering(  968): TetherInterfaceSM: wlan0: enter InitialState
D/wpa_supplicant( 1323): RSN: encrypted key data - hexdump(len=56): 50 1b 53 bb b0 ab 40 17 12 ba 99 ea a2 72 17 32 39 27 0e c7 17 c7 49 5f 3e d4 cb ab 19 68 f4 76 ...
E/WifiStateMachine(  968): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTING wifi info = SSID: NG700, BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: 0, Metered hint: false
D/wpa_supplicant( 1323): WPA: decrypted EAPOL-Key key data - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 1323): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1323): wlan0: WPA: RX message 3 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 1323): WPA: IE KeyData - hexdump(len=48): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00 dd 16 00 0f ac 01 02 00 d8 4e ...
D/wpa_supplicant( 1323): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1323): WPA: GTK in EAPOL-Key - hexdump(len=24): [REMOVED]
E/WifiStateMachine(  968): WiFiDisplay: getWifidisplayApEnabled=false
D/wpa_supplicant( 1323): wlan0: WPA: Sending EAPOL-Key 4/4
D/wpa_supplicant( 1323): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 1323): WPA: Derived Key MIC - hexdump(len=16): 76 5a b6 5c 6a e1 36 64 5a 10 51 ee b7 95 23 0b
D/wpa_supplicant( 1323): wlan0: WPA: Installing PTK to the driver
D/wpa_supplicant( 1323): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=3 addr=0x5594371390 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 1323): nl80211: KEY_DATA - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 1323): nl80211: KEY_SEQ - hexdump(len=6): 00 00 00 00 00 00
D/wpa_supplicant( 1323):    addr=c0:ff:d4:d3:aa:48
E/WifiStateMachine(  968): NetworkAgent == null
D/wpa_supplicant( 1323): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1323): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1323): RSN: received GTK in pairwise handshake - hexdump(len=18): [REMOVED]
D/wpa_supplicant( 1323): WPA: Group Key - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 1323): wlan0: WPA: Installing GTK to the driver (keyidx=2 tx=0 len=16)
D/wpa_supplicant( 1323): WPA: RSC - hexdump(len=6): 97 66 00 00 00 00
E/WifiStateMachine(  968): [sendNetworkStateChangeBroadcast] NetworkInfo state =AUTHENTICATING wifi info = SSID: NG700, BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: 0, Metered hint: false
E/WifiTrafficPoller(  968): ENABLE_TRAFFIC_STATS_POLL false Token 18
D/wpa_supplicant( 1323): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=3 addr=0x558ba63e68 key_idx=2 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 1323): nl80211: KEY_DATA - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 1323): nl80211: KEY_SEQ - hexdump(len=6): 97 66 00 00 00 00
D/wpa_supplicant( 1323):    broadcast key
D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor(  968): WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
I/wpa_supplicant( 1323): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/HTCRequest(  968): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  968): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/wpa_supplicant( 1323): wlan0: Cancelling authentication timeout
E/wpa_supplicant( 1323): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1323): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
D/wpa_supplicant( 1323): wlan0: Radio work 'connect'@0x5594371680 done in 0.117535 seconds
D/HTCRequest(  968): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
I/wpa_supplicant( 1323): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
I/wpa_supplicant( 1323): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
D/WifiMonitor(  968): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
D/WifiMonitor(  968): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
E/WifiMonitor(  968): WifiMonitor:wlan0 cnt=44 dispatchEvent: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
W/WifiMonitor(  968): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor(  968): Event [IFNAME=wlan0 BLACKLIST REMOVE c0:ff:d4:d3:aa:48]
E/WifiMonitor(  968): WifiMonitor:wlan0 cnt=45 dispatchEvent: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]]
E/WifiMonitor(  968): WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiMonitor(  968): handleEvent 1  Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/wpa_supplicant( 1323): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 1323): nl80211: Set wlan0 operstate 0->1 (UP)
D/wpa_supplicant( 1323): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=6 (IF_OPER_UP)
D/WifiMonitor(  968): Event [IFNAME=wlan0 Connect to SSID: NG700]
E/WifiMonitor(  968): WifiMonitor:wlan0 cnt=47 dispatchEvent: Connect to SSID: NG700
W/WifiMonitor(  968): couldn't identify event type - Connect to SSID: NG700
I/wpa_supplicant( 1323): set send_ind_to_ndc = 0
I/wpa_supplicant( 1323): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1323): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1323): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1323): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1323): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1323): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1323): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1323): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 1323): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1323): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1323): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1323): EAPOL authentication completed - result=SUCCESS
I/wpa_supplicant( 1323): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
D/wpa_supplicant( 1323): RTM_NEWLINK: ifi_index=29 ifname=wlan0 operstate=6 linkmode=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/Tethering(  968): interfaceLinkStateChanged wlan0, true
D/Tethering(  968): interfaceStatusChanged wlan0, true
E/WifiStateMachine(  968): WiFiDisplay: getWifidisplayApEnabled=false
I/IntentController( 1215): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor(  968): WifiMonitor:wlan0 cnt=48 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  968): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  968): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  968): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  968): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
E/WifiStateMachine(  968): processMsg: ConnectModeState
E/WifiStateMachine(  968):  ConnectModeState !SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=103734  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
E/WifiStateMachine(  968): handleMessage: X
D/Tethering(  968): sendTetherStateChangedBroadcast 1, 0, 0
I/IntentController( 1215): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiTrafficPoller(  968): ENABLE_TRAFFIC_STATS_POLL false Token 19
D/UsbnetService(  968): BroadcastReceiver::onReceive+
D/UsbnetService(  968): ACTION_TETHER_STATE_CHANGED: active=[],USB_FUNCTION_NCM=false
D/UsbnetService(  968): BroadcastReceiver::onReceive-
E/WifiStateMachine(  968): handleMessage: E msg.what=147462
E/WifiStateMachine(  968): processMsg: DisconnectedState
E/WifiStateMachine(  968):  DisconnectedState !SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=103745  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine(  968): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  968): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  968): processMsg: ConnectModeState
D/WISPrService( 5951): >>>>>WISPrService start isConnected = false<<<<<
E/WifiStateMachine(  968):  ConnectModeState !SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=103747  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine(  968): handleMessage: X
E/WifiStateMachine(  968): handleMessage: E msg.what=147459
E/WifiStateMachine(  968): processMsg: DisconnectedState
E/WifiStateMachine(  968):  DisconnectedState !NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=103748
E/WifiStateMachine(  968): processMsg: ConnectModeState
E/WifiStateMachine(  968):  ConnectModeState !NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=103749
E/WifiStateMachine(  968): Network connection established
D/WifiStateMachine(  968): fetchFrequency(), freq = 2412
E/WifiStateMachine(  968): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
E/WifiStateMachine(  968): NetworkAgent == null
E/WifiStateMachine(  968): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
E/WifiStateMachine(  968): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
V/NetworkPolicy(  968): updateNetworkEnabledLocked()
E/WifiTrafficPoller(  968): ENABLE_TRAFFIC_STATS_POLL false Token 20
D/PMS     (  968): releaseWL(114a90dd): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
V/NetworkPolicy(  968): updateNotificationsLocked()
D/TetherSettings( 5951): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/WIFI_ICON( 1215): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/        ( 5951): Cust_ConnectToPC   : Internet_Sharing>true
D/StatusBar.NetworkController( 1215): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/        ( 5951): Cust_ConnectToPC   : Modem_Link>false
D/WifiDisplayAdapter(  968): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  968):     Client/Owner: Client
D/WifiDisplayAdapter(  968):     GroupId: 
D/WifiDisplayAdapter(  968):     Passphrase: 
D/WifiDisplayAdapter(  968):     SessionId: 0
D/WifiDisplayAdapter(  968):     IP Address: }
D/        ( 5951): Cust_ConnectToPC   : spcsc>false
D/        ( 5951): Cust_ConnectToPC   : IPT>true
D/        ( 5951): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 5951): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 5951): hasRemovableStorageSlot: true
D/SmartNS_Utility( 5951): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
E/WifiStateMachine(  968): transitionTo: destState=ObtainingIpState
D/SmartNS_NSReceiver( 5951): onReceive : android.net.conn.TETHER_STATE_CHANGED hasTethered:false isNSOpening:false
E/WifiStateMachine(  968): handleMessage: new destination call exit/enter
E/WifiStateMachine(  968): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
E/WifiStateMachine(  968): invokeExitMethods: DisconnectedState
E/WifiStateMachine(  968): setScanAlarm false period 0 initial delay 0mAlarmEnabledtrue
E/WifiStateMachine(  968): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiStateMachine(  968): moveTempStackToStateStack: i=1,j=4
E/WifiStateMachine(  968): moveTempStackToStateStack: i=0,j=5
E/WifiStateMachine(  968): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=4,Top=ObtainingIpState
E/WifiStateMachine(  968): invokeEnterMethods: L2ConnectedState
E/WifiStateMachine(  968): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
E/WifiStateMachine(  968): NetworkAgent == null
E/WifiTrafficPoller(  968): ENABLE_TRAFFIC_STATS_POLL false Token 21
I/IntentController( 1215): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  968): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTING wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
I/IntentController( 1215): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WIFI_ICON( 1215): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/WISPrService( 5951): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: 0, Metered hint: false
D/StatusBar.NetworkController( 1215): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiTrafficPoller(  968): ENABLE_TRAFFIC_STATS_POLL false Token 22
D/WIFI_ICON( 1215): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1215): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
W/ContextImpl( 5951): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.NSReceiver.onReceive:432 android.app.ActivityThread.handleReceiver:2712 
I/IntentController( 1215): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WISPrService( 5951): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 5951): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
E/WifiStateMachine(  968): L2ConnectedState c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
D/ConnectivityService(  968): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiStateMachine(  968): L2ConnectedState "NG700" nid=0
D/ConnectivityService(  968): Got NetworkAgent Messenger
E/WifiConfigStore(  968): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/ConnectivityService(  968): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
W/WifiHW  (  968): QCOM Debug skip set_network part for security concern!
D/ConnectivityService(  968): NetworkAgent connected
D/wpa_supplicant( 1323): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1323): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1323): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
I/SmartNS_Utility( 5951): setISNotification
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1323): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1323): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 1323): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1323): CTRL_IFACE: SAVE_CONFIG - Configuration updated
D/SmartNS_Utility( 5951): usb_cable_connect = 1
E/WifiStateMachine(  968): invokeEnterMethods: ObtainingIpState
E/WifiStateMachine(  968): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
E/WifiStateMachine(  968): ObtainingIpAddress c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  968): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  968): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
W/WifiHW  (  968): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1323): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1323): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1323): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1323): wlan0: Control interface command 'SAVE_CONFIG'
D/SmartNS_Utility( 5951): usb_denied = 0
D/wpa_supplicant( 1323): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
I/SmartNS_PSService( 5951): usb notificaiton:true
D/wpa_supplicant( 1323): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1323): CTRL_IFACE: SAVE_CONFIG - Configuration updated
E/WifiStateMachine(  968): WiFiDisplay: getWifidisplayApEnabled=false
D/libc    (  968): [NET] android_getaddrinfofornet+,hn 7(0x302e302e302e30),sn(),hints(known),family 0,flags 4
D/libc    (  968): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  968): [NET] android_getaddrinfofornet+,hn 6,sn(),hints(known),family 0,flags 4
D/libc    (  968): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  968): Start Dhcp Watchdog 2
E/WifiStateMachine(  968): handleMessage: X
E/WifiStateMachine(  968): handleMessage: E msg.what=147462
E/WifiStateMachine(  968): processMsg: ObtainingIpState
E/WifiStateMachine(  968):  ObtainingIpState !SUPPLICANT_STATE_CHANGE_EVENT 48 0 rt=103764  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine(  968): processMsg: L2ConnectedState
E/WifiStateMachine(  968):  L2ConnectedState !SUPPLICANT_STATE_CHANGE_EVENT 48 0 rt=103765  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine(  968): processMsg: ConnectModeState
E/WifiStateMachine(  968):  ConnectModeState !SUPPLICANT_STATE_CHANGE_EVENT 48 0 rt=103766  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine(  968): handleMessage: X
E/WifiStateMachine(  968): handleMessage: E msg.what=131101
E/WifiStateMachine(  968): processMsg: ObtainingIpState
E/WifiStateMachine(  968):  ObtainingIpState !CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  968): processMsg: L2ConnectedState
E/WifiStateMachine(  968):  L2ConnectedState !CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  968): processMsg: ConnectModeState
D/SmartNS_Utility( 5951): usb_cable_connect = 1
E/WifiStateMachine(  968):  ConnectModeState !CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  968): processMsg: DriverStartedState
E/WifiStateMachine(  968):  DriverStartedState !CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  968): processMsg: SupplicantStartedState
D/SmartNS_Utility( 5951): usb_denied = 0
I/SmartNS_PSService( 5951): usb notificaiton:true
E/WifiStateMachine(  968):  SupplicantStartedState !CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  968): processMsg: DefaultState
E/WifiStateMachine(  968):  DefaultState !CMD_TETHER_STATE_CHANGE 0 0
D/WifiStateMachine(  968): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  968): Default got CMD_TETHER_STATE_CHANGE
E/WifiStateMachine(  968): handleMessage: X
E/WifiStateMachine(  968): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiStateMachine(  968): handleMessage: E msg.what=131155
E/WifiStateMachine(  968): processMsg: ObtainingIpState
E/WifiStateMachine(  968):  ObtainingIpState !CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-127 f=2412 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1757] from screen [on:0 period:-1459820072] gl hn u24 rssi=-52 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  968): processMsg: L2ConnectedState
I/RemoteViews( 1215): reapply : com.android.settings 1 36
E/WifiStateMachine(  968):  L2ConnectedState !CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-127 f=2412 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1459820070] gl hn u24 rssi=-52 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  968):  get link layer stats 0
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/DotMatrix( 1324): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
D/wpa_supplicant( 1323): wlan0: Control interface command 'SIGNAL_POLL'
I/wpa_supplicant( 1323): environment dirty rate=0 [2][0][0]
E/WifiStateMachine(  968): fetchRssiLinkSpeedAndFrequencyNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 72
,E/WifiStateMachine(  968): fetchRssiLinkSpeedAndFrequencyNative rssi=-57 linkspeed=72
E/WifiConfigStore(  968): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-57 "NG700"WPA_PSK
D/SmartNS_NSReceiver( 5951): Tethered state change:false isNSOpening:false
D/WISPrService( 5951): >>>>>WISPrService start isConnected = false<<<<<
E/WifiStateMachine(  968): calculateWifiScore freq=2412 speed=72 score=0 highRSSI  -> txbadrate=0.00 txgoodrate=78.00 txretriesrate=0.00 rxrate=131.50 userTriggerdPenalty0
E/WifiStateMachine(  968):  good link -> stuck count =0
E/WifiStateMachine(  968):  badRSSI count0 lowRSSI count0 --> score 60
E/WifiStateMachine(  968):  isHighRSSI       ---> score=65
E/WifiStateMachine(  968): calculateWifiScore() report new score 60
D/WISPrService( 5951): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -57, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
D/WISPrService( 5951): >>>>>WISPrService start isConnected = false<<<<<
E/WifiStateMachine(  968): handleMessage: X
D/WISPrService( 5951): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -57, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
E/WifiStateMachine(  968): handleMessage: E msg.what=131212
E/WifiStateMachine(  968): processMsg: ObtainingIpState
D/ConnectivityService(  968): updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
E/WifiStateMachine(  968):  ObtainingIpState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  968): processMsg: L2ConnectedState
E/WifiStateMachine(  968):  L2ConnectedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  968): processMsg: ConnectModeState
D/WISPrService( 5951): >>>>>WISPrService start isConnected = false<<<<<
E/WifiStateMachine(  968):  ConnectModeState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  968): processMsg: DriverStartedState
E/WifiStateMachine(  968):  DriverStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
D/WISPrService( 5951): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -57, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
E/WifiStateMachine(  968): processMsg: SupplicantStartedState
E/WifiStateMachine(  968):  SupplicantStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  968): processMsg: DefaultState
D/WifiWatchdogStateMachine(  968): RSSI current: 3 new: -57, 3
D/DotMatrix( 1324): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
E/WifiStateMachine(  968):  DefaultState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  968): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  968): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
D/ConnectivityService(  968): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine(  968): handleMessage: X
E/WifiStateMachine(  968): handleMessage: E msg.what=196612
E/WifiStateMachine(  968): processMsg: ObtainingIpState
E/WifiStateMachine(  968):  ObtainingIpState !CMD_PRE_DHCP_ACTION 0 0 txpkts=156,0,0
E/WifiStateMachine(  968): processMsg: L2ConnectedState
E/WifiStateMachine(  968):  L2ConnectedState !CMD_PRE_DHCP_ACTION 0 0 txpkts=156,0,0
D/WifiStateMachine(  968): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  968): acquireWL(4fd9338): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 968 1000 null
D/WifiStateMachine(  968): handlePreDhcpSetup mBluetoothConnectionActive: false
D/WifiDataStallTracker(  968): setDhcpActive: true
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
D/wpa_supplicant( 1323): wlan0: Control interface command 'DRIVER BTCOEXMODE 1'
D/wpa_supplicant( 1323): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 8192
E/WifiStateMachine(  968): setSuspendOptimizationsNative: 1 false -want false stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  (  968): do suspend false
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 0"
D/wpa_supplicant( 1323): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 0'
D/wpa_supplicant( 1323): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 0 len = 0, 8192
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
D/wpa_supplicant( 1323): wlan0: Control interface command 'DRIVER POWERMODE 1'
I/wpa_supplicant( 1323): INFO - Deny active power mode because already has gateway
D/wpa_supplicant( 1323): nl80211: Drv Event 79 (NL80211_CMD_SET_REKEY_OFFLOAD) received for wlan0
D/wpa_supplicant( 1323): nl80211: Rekey offload event for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1323): nl80211: Rekey offload - Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 00
D/WIFI_ICON( 1215): updateWifiState: RSSI_CHANGED -1 -> 3
D/wpa_supplicant( 1323): wlan0: Event DRIVER_GTK_REKEY (37) received
D/StatusBar.NetworkController( 1215): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
D/WifiP2pService(  968): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@5ee913d target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1323): wlan0: Control interface command 'DRIVER WLS_BATCHING GET'
D/WifiP2pService(  968): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@5ee913d target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 1323): wpa_driver_nl80211_driver_cmd: failed to issue private commands
E/WifiStateMachine(  968): Unexpected BatchedScanResults :null
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
D/wpa_supplicant( 1323): wlan0: Control interface command 'DRIVER WLS_BATCHING STOP'
E/wpa_supplicant( 1323): wpa_driver_nl80211_driver_cmd: failed to issue private commands
E/WifiStateMachine(  968): noteBatchedScanstop()
E/WifiStateMachine(  968): handleMessage: X
I/QuickSettingWifi( 1215): receive.wifiConnect:false wifiAPname:null elapse:1
I/RemoteViews( 1215): reapply : com.android.settings 1 36
I/QuickSettingWifi( 1215): receive.wifiConnect:false wifiAPname:null elapse:0
I/QuickSettingWifi( 1215): receive.wifiConnect:false wifiAPname:null elapse:0
I/QuickSettingWifi( 1215): receive.wifiConnect:false wifiAPname:null elapse:0
I/QuickSettingWifi( 1215): receive.wifiConnect:false wifiAPname:null elapse:1
,E/dhcpcd  ( 6705): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
I/dhcpcd  ( 6705): version 5.5.6 starting
E/dhcpcd  ( 6705): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
I/dhcpcd  ( 6705): wlan0: using ClientID 01:90:**:c4:e6:4c:f8
I/dhcpcd  ( 6705): autoip env[11]:autoip=DISABLE
,I/dhcpcd  ( 6705): wlan0: rebinding lease of 192.168.1.130
,I/dhcpcd  ( 6705): wlan0: sending REQUEST (xid 0x125907d), next in 0.99 seconds
,E/WifiDataStallTracker(  968): DATA_MONITOR_POLL false Token 2,
,I/dhcpcd  ( 6705): wlan0: acknowledged 192.168.1.130 from 192.168.1.1,
,I/dhcpcd  ( 6705): wlan0: leased 192.168.1.130 for 86400 seconds
I/dhcpcd  ( 6705): autoip env[11]:autoip=DISABLE
,D/libc    (  968): [NET] android_getaddrinfofornet+,hn 13(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/ConnectivityService(  968): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
D/libc    (  968): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  968): handleMessage: E msg.what=131212
E/WifiStateMachine(  968): processMsg: ObtainingIpState
E/WifiStateMachine(  968):  ObtainingIpState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  968): processMsg: L2ConnectedState
E/WifiStateMachine(  968):  L2ConnectedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  968): processMsg: ConnectModeState
E/WifiStateMachine(  968):  ConnectModeState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  968): processMsg: DriverStartedState
E/WifiStateMachine(  968):  DriverStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  968): processMsg: SupplicantStartedState
E/WifiStateMachine(  968):  SupplicantStartedState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  968): processMsg: DefaultState
E/WifiStateMachine(  968):  DefaultState !CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  968): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.130/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  968): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
E/WifiStateMachine(  968): handleMessage: X
,I/dhcpcd  ( 6705): bind_interface: daemonise
,D/libc    (  968): [NET] android_getaddrinfofornet+,hn 13(0x3139322e313638),sn(),hints(known),family 0,flags 4,
D/libc    (  968): [NET] android_getaddrinfofornet-, SUCCESS
D/WifiP2pService(  968): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/libc    (  968): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/WifiP2pService(  968): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/libc    (  968): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  968): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  968): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  968): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  968): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  968): handleMessage: E msg.what=196613
D/PMS     (  968): releaseWL(4fd9338): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
E/WifiStateMachine(  968): processMsg: ObtainingIpState
E/WifiStateMachine(  968):  ObtainingIpState !CMD_POST_DHCP_ACTION 1 0 OK  v4
E/WifiStateMachine(  968): processMsg: L2ConnectedState
E/WifiStateMachine(  968):  L2ConnectedState !CMD_POST_DHCP_ACTION 1 0 OK  v4
E/WifiStateMachine(  968): setSuspendOptimizationsNative: 1 true -want false stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
D/wpa_supplicant( 1323): wlan0: Control interface command 'DRIVER POWERMODE 0'
I/wpa_supplicant( 1323): Power_Mode_Type mode = 0
I/wpa_supplicant( 1323): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
D/wpa_supplicant( 1323): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/wpa_supplicant( 1323): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 8192
D/WifiDataStallTracker(  968): setDhcpActive: false
E/WifiStateMachine(  968): handlePostDhcpSetup release wake lock during DHCP
E/WifiStateMachine(  968): WifiStateMachine DHCP successful
E/WifiStateMachine(  968): wifistatemachine handleIPv4Success <IP address 192.168.1.130/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds>
E/WifiStateMachine(  968): link address 192.168.1.130/24
E/WifiStateMachine(  968): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.130/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.130/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine(  968): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
D/ConnectivityService(  968): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine(  968): gateway: /192.168.1.1
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
D/wpa_supplicant( 1323): wlan0: Control interface command 'DRIVER GATEWAY-ADD 16885952'
I/wpa_supplicant( 1323): WiFi gateway: 0x101a8c0
,D/WifiStateMachine(  968): [MLHD] enter handleMediaLinkEvent L2ConnectedState
E/WifiStateMachine(  968): handleMessage: X
E/WifiStateMachine(  968): handleMessage: E msg.what=131210
E/WifiStateMachine(  968): processMsg: ObtainingIpState
E/WifiStateMachine(  968):  ObtainingIpState !CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine(  968): processMsg: L2ConnectedState
,E/WifiStateMachine(  968):  L2ConnectedState !CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1323): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1323): environment dirty rate=0 [3][0][0]
,E/WifiStateMachine(  968): fetchRssiLinkSpeedAndFrequencyNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 72
,E/WifiStateMachine(  968): fetchRssiLinkSpeedAndFrequencyNative rssi=-57 linkspeed=72
E/WifiConfigStore(  968): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-57 "NG700"WPA_PSK
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 BLACKLIST clear"
D/WifiWatchdogStateMachine(  968): RSSI current: 3 new: -57, 3
D/WIFI_ICON( 1215): updateWifiState: RSSI_CHANGED 3 -> 3
D/wpa_supplicant( 1323): wlan0: Control interface command 'BLACKLIST clear'
E/wpa_supplicant( 1323): wlan0: BLACKLIST CLEAR 
D/StatusBar.NetworkController( 1215): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
D/WifiMonitor(  968): Event [IFNAME=wlan0 BLACKLIST CLEAR ]
E/WifiStateMachine(  968): setDetailed state, old =CONNECTING and new state=CONNECTED hidden=false
E/WifiMonitor(  968): WifiMonitor:wlan0 cnt=49 dispatchEvent: BLACKLIST CLEAR 
E/WifiStateMachine(  968): NetworkAgent != null
E/WifiStateMachine(  968): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -57, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
D/ConnectivityService(  968): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,E/WifiStateMachine(  968): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -57, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
D/ConnectivityService(  968): Adding iface wlan0 to network 101
D/WifiDataStallTracker(  968): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
D/HtcWifiWanDetect(  968): WAN detection
E/WifiTrafficPoller(  968): ENABLE_TRAFFIC_STATS_POLL true Token 23
,D/HtcWifiWanDetect(  968): canDoWanDetection: mHtcWanDetectionDialogEnabled: true mHtcWanDetectionEnabled: true
I/IntentController( 1215): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WIFI_ICON( 1215): updateWifiState: NETWORK_STATE_CHANGED connected
E/WifiTrafficPoller(  968):  packet count Tx=158 Rx=266
V/NetworkPolicy(  968): mWifiStateReceiver: meteredHint=false,EPS mode=false
E/WifiTrafficPoller(  968): notifying of data activity 3
D/StatusBar.NetworkController( 1215): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/WifiDataStallTracker(  968): ENABLE_DATA_MONITOR_POLL true Token 2
D/WIFI_ICON( 1215): WifiActivity: 3
E/WifiStateMachine(  968): transitionTo: destState=ConnectedState
V/NetworkPolicy(  968): mWifiStateReceiver: meteredHint=false,EPS mode=false
E/WifiStateMachine(  968): handleMessage: new destination call exit/enter
D/StatusBar.NetworkController( 1215): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
E/WifiStateMachine(  968): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
E/WifiStateMachine(  968): invokeExitMethods: ObtainingIpState
E/WifiStateMachine(  968): moveTempStackToStateStack: i=0,j=5
E/WifiStateMachine(  968): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=ConnectedState
E/WifiStateMachine(  968): invokeEnterMethods: ConnectedState
E/WifiStateMachine(  968): updateDefaultRouteMacAddress found Ipv4 default :192.168.1.1
E/WifiStateMachine(  968): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
E/WifiTrafficPoller(  968): ENABLE_TRAFFIC_STATS_POLL true Token 24
I/IntentController( 1215): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiTrafficPoller(  968):  packet count Tx=158 Rx=266
E/WifiTrafficPoller(  968): notifying of data activity 0
,D/WifiDataStallTracker(  968): updateDataStallInfo: mDataStallTxRxSum={txSum=0 rxSum=0} preTxRxSum={txSum=0 rxSum=0}
D/WifiDataStallTracker(  968): updateDataStallInfo: NONE
D/WifiDataStallTracker(  968): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,D/WIFI_ICON( 1215): updateWifiState: NETWORK_STATE_CHANGED connected
,D/StatusBar.NetworkController( 1215): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
D/WIFI_ICON( 1215): WifiActivity: 0
D/StatusBar.NetworkController( 1215): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/WISPrService( 5951): >>>>>WISPrService start isConnected = true<<<<<
E/ConnectivityService(  968): Unexpected mtu value: 0, wlan0
,E/WifiStateMachine(  968): ConnectedState Enter  mScreenOn=true scanperiod=20000
D/ConnectivityService(  968): Adding Route [fe80::/64 -> :: wlan0] to network 101
E/WifiStateMachine(  968): setScanAlarm true period 20000 initial delay 200mAlarmEnabledfalse
D/WifiDisplayAdapter(  968): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  968):     Client/Owner: Client
D/WifiDisplayAdapter(  968):     GroupId: 
D/WifiDisplayAdapter(  968):     Passphrase: 
D/WifiDisplayAdapter(  968):     SessionId: 0
D/WifiDisplayAdapter(  968):     IP Address: }
E/WifiStateMachine(  968): handleMessage: X
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 6,sn(),hints(known),family 0,flags 4
D/libc    (  394): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    (  394): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/ConnectivityService(  968): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
D/libc    (  394): [NET] android_getaddrinfofornet-, SUCCESS
D/ConnectivityService(  968): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/libc    (  394): [NET] android_getaddrinfofornet+,hn 7(0x302e302e302e30),sn(),hints(known),family 0,flags 4
D/ConnectivityService(  968): Setting Dns servers for network 101 to [/192.168.1.1]
E/WifiStateMachine(  968): handleMessage: E msg.what=131131
E/WifiStateMachine(  968): processMsg: ConnectedState
D/libc    (  394): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  968):  ConnectedState !CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine(  968): processMsg: L2ConnectedState
E/WifiStateMachine(  968):  L2ConnectedState !CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine(  968): processMsg: ConnectModeState
D/libc    (  968): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  968): [NET] android_getaddrinfofornet-, SUCCESS
,E/WifiStateMachine(  968):  ConnectModeState !CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine(  968): handleMessage: X
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(53),hints(known),family 0,flags 4
D/libc    (  394): [NET] android_getaddrinfofornet-, SUCCESS
D/Nat464Xlat(  968): requiresClat: netType=1, connected=true, mIsClatEnabled=true, hasIPv4Address=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  968): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  968): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/usbnet  (  968): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  968): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/usbnet  (  968):   my score=70, my filter=[ Transports:  Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  968): rematching NetworkAgentInfo [WIFI () - 101]
D/usbnet  (  968): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
D/ConnectivityService(  968):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  968): Connected
D/ConnectivityService(  968):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/WIFI    (  968): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  968):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  968): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  968): currentScore = 0, newScore = 20
D/WIFI    (  968):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  968):    accepting network in place of null
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  968): Validated
D/ConnectivityService(  968): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isSkipMobile=false
D/WIFI    (  968): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
D/CSLegacyTypeTracker(  968): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  968): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  968): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,I/QuickSettingWifi( 1215): receive.wifiConnect:true wifiAPname:NG700 elapse:1
D/ConnectivityService(  968): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  968): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
V/NetworkPolicy(  968): ensureActiveMobilePolicyLocked()
D/Tethering(  968): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
D/PMS     (  968): acquireWL(3dd2876): PARTIAL_WAKE_LOCK  NetworkStats 0x1 968 1000 null
D/WISPrService( 5951): >>>>>WISPrService start isConnected = true<<<<<
D/ConnectivityService(  968): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.130/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/Tethering(  968): TetherMasterSM: InitialState processMessage what=UPSTREAM_CHANGED
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  968): ValidatedState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  968): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  968): Validated
D/ConnectivityService(  968):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  968):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/NetworkPolicy(  968): ensureActiveMobilePolicyLocked: SIM state invalid, slotId= -1000, subId=-1000 . Return.
V/NetworkPolicy(  968): updateNetworkEnabledLocked()
V/NetworkPolicy(  968): updateIfacesLocked()
D/DATA_ICON( 1215): updateConnectivity android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE Type:1/Status:0
D/ConnectivityService(  968): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  968): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  968): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  968):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  968):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1215): CM callback handler got msg 524290
V/NetworkPolicy(  968): updateNotificationsLocked()
D/ConnectivityService(  968): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
,D/ConnectivityService(  968): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  968):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  968):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/NetworkManagementService(  968): isBandwidthControlEnabled: doneSignal.getCount()= 0
I/SecurityController( 1215): onAvailable 101 : [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  968): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/usbnet  (  968): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/DATA_ICON( 1215): dataConnected: false/false
D/usbnet  (  968):   my score=70, my filter=[ Transports:  Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/StatusBar.NetworkController( 1215): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/usbnet  (  968): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
D/ConnectivityService(  968): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isSkipMobile=false
D/WIFI    (  968): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  968): sendGeneralBroadcast, restrictEnable=false
D/WIFI    (  968):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  968): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/WIFI    (  968): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
D/ConnectivityService(  968): Validated NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler( 1215): CM callback handler got msg 524290
D/ConnectivityService(  968): rematching NetworkAgentInfo [WIFI () - 101]
I/SecurityController( 1215): onAvailable 101 : [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  968):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityManager.CallbackHandler( 1215): CM callback handler got msg 524290
D/ConnectivityService(  968):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  968): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  968): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  968):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  968):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  968): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/DATA_ICON( 1215): updateConnectivity android.net.conn.INET_CONDITION_ACTION Type:1/Status:100
D/PMS     (  968): releaseWL(3dd2876): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,I/SecurityController( 1215): onAvailable 101 : [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,V/NetworkPolicy(  968): updateNetworkEnabledLocked()
,V/NetworkPolicy(  968): updateNotificationsLocked()
D/DATA_ICON( 1215): dataConnected: false/false
D/StatusBar.NetworkController( 1215): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/QuickSettingWifi( 1215): receive.wifiConnect:true wifiAPname:NG700 elapse:1
,D/ConnectivityService(  968): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/AlarmManager(  968): [AlarmQueuing] connectivity wifi: false
,D/GpsLocationProvider(  968): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/PMS     (  968): acquireWL(8c25e77): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 968 1000 null
D/PMS     (  968): acquireWL(3a94aae4): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 968 1000 null
D/htcCheckinService(  968): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
,D/PMS     (  968): releaseWL(3a94aae4): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/GpsLocationProvider(  968): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  968): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
I/ConnectivityHelper( 1590): [onReceive] WIFI(1): CONNECTED
,I/ActivityManager(  968): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6738 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=arm64-v8a,
,E/GpsLocationProvider(  968): No APN found to select.,
,D/PMS     (  968): releaseWL(8c25e77): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/wpa_supplicant( 1323): EAPOL: startWhen --> 0,
D/wpa_supplicant( 1323): EAPOL: disable timer tick
,D/MdScPhnSt( 6646): [5b5.1.]  listen tmrbb8,
,D/MdScDataSum( 6646): [5b5.1.] summary 118:p1 ignore
,I/MusicStore( 6738): Database version: 120,
,I/art     ( 1873): Explicit concurrent mark sweep GC freed 9991(524KB) AllocSpace objects, 5(420KB) LOS objects, 49% free, 4MB/8MB, paused 657us total 35.053ms
,D/VoldConnector(  968): SND -> {31 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/},
E/Vold    (  383): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
W/ContextImpl( 6738): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,D/VoldConnector(  968): SND -> {32 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/},
E/Vold    (  383): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
,W/ContextImpl( 6738): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,D/VoldConnector(  968): SND -> {33 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/}
,W/ContextImpl( 6738): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
E/Vold    (  383): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
,W/ResourcesManager( 6738): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
,W/ResourcesManager( 6738): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6738): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...,
,W/ActivityThread( 6738): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());,
W/System  ( 6738): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@364f53fd: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6738): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6738): GMSCore installation verified
,I/ConfigStore( 6738): Config Database version: 1
,I/PackageManager(  968):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=6738, uid=10159, userID:0,
,D/WifiDisplayAdapter(  968): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:,
D/WifiDisplayAdapter(  968):     Client/Owner: Client
D/WifiDisplayAdapter(  968):     GroupId: 
D/WifiDisplayAdapter(  968):     Passphrase: 
D/WifiDisplayAdapter(  968):     SessionId: 0
D/WifiDisplayAdapter(  968):     IP Address: }
,D/MediaRouterService(  968): Client com.google.android.music (pid 6738): Registered
,D/WifiDisplayAdapter(  968): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  968):     Client/Owner: Client
D/WifiDisplayAdapter(  968):     GroupId: 
D/WifiDisplayAdapter(  968):     Passphrase: 
D/WifiDisplayAdapter(  968):     SessionId: 0
D/WifiDisplayAdapter(  968):     IP Address: }
,I/MediaRouter( 6738): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android },
,V/MusicLeanback( 6738): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) },
,I/NetworkMonitor( 6738): type=WIFI subType= reason=null isConnected=true,
,I/NetworkMonitor( 6738): type=WIFI subType= reason=null isConnected=true,
,D/MobileConnectivityChangeReceiver( 6533): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) },
D/MobileConnectivityChangeReceiver( 6533): onReceive CONNECTIVITY_CHANGE networkType=1
,D/AutoSetting( 1626): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
I/PackageManager(  968):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=1, flag=1, pid=6738, uid=10159, userID:0
,D/AutoSetting( 1626): service - onCreate()
,I/GHttpClientFactory( 6738): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6738): Using platform SSLCertificateSocketFactory
,I/HtcModeClient( 3245): handler message = 4011
,D/AutoSetting( 1626): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/AutoSetting( 1626): Util - check NLP state, Allowned:false, Enabled:false,
D/AutoSetting( 1626): service - requestNLP() NetworkLocationProvider not enabled
D/AutoSetting( 1626): service - onStartCommand() REMOVE current location bundle
,D/AutoSetting( 1626): service - handleMessage() setting current location null
D/LocationManagerService(  968): request 3f6ab8b8 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10052)
D/LocationManagerService(  968): provider request: passive ProviderRequest[ON interval=0]
,E/HtcModeClient( 3245): Check connection and retry 12 times. Stop service and kill this process.,
,D/HtcModeClient( 3245): Don't start project servcice
,D/HtcModeClient( 3245): setEject: MEDIA_EJECT_STATE = true
,D/HtcModeClient( 3245): connectState: CONNECTION_READY = false
D/SilentMusic( 3245): call stop
D/HtcModeClient( 3245): close connection
W/HtcModeClient( 3245): leaveProjectMode: It does not enter ProjectMode
,W/CANMesgAgentLocalSocket( 3245): read the terminate packet, so break
,D/ChimeraCfgMgr( 4438): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/Kids    ( 4438): [GCoreUtils] Current gmscore version, 7899448 is smaller than the required version 8400000
,I/ActivityManager(  968): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6781 uid=10161 gids={50161, 9997, 3003, 1028, 1015} abi=arm64-v8a
,D/libc    ( 6239): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 4
D/libc    ( 6239): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 6239): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
I/ActivityManager(  968): Killing 3245:com.htc.autobot/u0a47 (adj 15): empty #17
D/libc    ( 6239): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 6239): [NET] android_getaddrinfo_proxy+
D/libc    ( 6239): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:101, mark:917605
D/Process (  968): killProcessQuiet, pid=3245
D/Process (  968): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,D/libc    (  968): [NET] android_getaddrinfofornet+,hn 25(0x666538303a3a39),sn(),hints(known),family 0,flags 4,
D/libc    (  968): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  968): handleMessage: E msg.what=131212
E/WifiStateMachine(  968): processMsg: ConnectedState
E/WifiStateMachine(  968):  ConnectedState !CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine(  968): processMsg: L2ConnectedState
E/WifiStateMachine(  968):  L2ConnectedState !CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine(  968): processMsg: ConnectModeState
E/WifiStateMachine(  968):  ConnectModeState !CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine(  968): processMsg: DriverStartedState
E/WifiStateMachine(  968):  DriverStartedState !CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine(  968): processMsg: SupplicantStartedState
E/WifiStateMachine(  968):  SupplicantStartedState !CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine(  968): processMsg: DefaultState
E/WifiStateMachine(  968):  DefaultState !CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine(  968): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.130/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.130/24,fe80::92e7:c4ff:fee6:4cf8/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine(  968): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
D/ConnectivityService(  968): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
D/ConnectivityService(  968): identical MTU - not setting
D/Nat464Xlat(  968): requiresClat: netType=1, connected=true, mIsClatEnabled=true, hasIPv4Address=true
D/ConnectivityService(  968): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  968):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  968):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  968): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ],
D/ConnectivityService(  968): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  968):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1215): CM callback handler got msg 524295
D/ConnectivityService(  968):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  968): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1215): CM callback handler got msg 524295
,I/ActivityManager(  968): Recipient 3245
,E/WifiStateMachine(  968): handleMessage: X
,I/GAv4    ( 6781): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6781):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6781):   adb logcat -s GAv4
,D/VoldConnector(  968): SND -> {34 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/},
E/Vold    (  383): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/
,W/ContextImpl( 6781): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,D/VoldConnector(  968): SND -> {35 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/}
,E/Vold    (  383): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/
,W/ContextImpl( 6781): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 6781): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.,
,D/VoldConnector(  968): SND -> {36 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/}
E/Vold    (  383): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/
,W/ContextImpl( 6781): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,D/libc    (  394): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  394): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 6239): [NET] android_getaddrinfo_proxy-, success
,W/GAv4    ( 6781): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
D/VoldConnector(  968): SND -> {37 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/}
,W/ContextImpl( 6781): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
E/Vold    (  383): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/
,E/WifiTrafficPoller(  968): TRAFFIC_STATS_POLL true Token 25 num clients 8,
,W/GAv4    ( 6781): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,E/WifiTrafficPoller(  968): TRAFFIC_STATS_POLL true Token 25 num clients 8,
E/WifiTrafficPoller(  968):  packet count Tx=163 Rx=269
D/WIFI_ICON( 1215): WifiActivity: 3
E/WifiTrafficPoller(  968): notifying of data activity 3
,D/StatusBar.NetworkController( 1215): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,I/Babel   ( 6239): connection state changed from UNKNOWN to CONNECTED
,D/Process (  968): killProcessQuiet, pid=5653
I/ActivityManager(  968): Killing 5653:com.android.defcontainer/u0a15 (adj 15): empty #17
D/Process (  968): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,D/PMS     (  968): releaseWL(3e1f81b5): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
,D/ConnectivityService(  968): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/ActivityManager(  968): Recipient 5653
,W/global  ( 6781): [apache-http] Connection GC has been deprecated!,
,W/global  ( 6781): [apache-http] Connection GC has been deprecated!
,I/WebViewFactory( 6781): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
,I/LibraryLoader( 6781): Time to load native libraries: 1 ms (timestamps 5906-5907),
I/LibraryLoader( 6781): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6781): Binding Chromium to main looper Looper (main, tid 1) {18785992},
I/LibraryLoader( 6781): Expected native library version number "",actual native library version number ""
,I/chromium( 6781): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6781): Initializing chromium process, singleProcess=true
,W/art     ( 6781): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6781): ApplicationContext is null in ApplicationStatus
,W/chromium( 6781): [WARNING:resource_bundle.cc(285)] locale_file_path.empty(),
,E/libEGL  ( 6781): validate_display:255 error 3008 (EGL_BAD_DISPLAY),
E/libEGL  ( 6781): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6781): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 6781): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6781): Build Date: 03/09/15 Mon
,I/Adreno-EGL( 6781): Local Branch: 
I/Adreno-EGL( 6781): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6781): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6781):                  d74aa161a12b9c6fc6332151
,W/AudioManagerAndroid( 6781): Requires BLUETOOTH permission,
,I/NSApplication( 6781): Starting up...
,I/ActivityManager(  968): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6841 uid=10096 gids={50096, 9997, 3003, 1028, 1015} abi=arm64-v8a
,D/Process (  968): killProcessQuiet, pid=6269
I/ActivityManager(  968): Killing 6269:com.htc.sense.mms/u0a64 (adj 15): empty #17
D/Process (  968): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,I/art     (  429): Explicit concurrent mark sweep GC freed 8645(367KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 145us total 18.556ms
,I/art     (  429): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 125us total 16.223ms,
,I/art     (  429): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 137us total 15.392ms
,I/ActivityManager(  968): Recipient 6269
,D/AccTypeManager( 1769): Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android,
,D/AccTypeManager( 1769): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,W/SystemReader(  968): Cannot find grip_rejection_width, use default value instead
,I/Prism.ItemManager( 1590): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1590): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
W/Prism.AllAppsManager( 1590): AllAppsMgr addApps, already exist: ApplicationInfo(id=33, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
,I/Launcher( 1590): Deferring update until onResume
,D/Launcher( 1590): waitUntilResume // bindAppsUpdated
,W/ResourcesManager(  968): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/AccTypeManager( 1769): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,D/PhoneApp( 1546): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,E/ExternalAccountType( 1769): Unsupported attribute readOnly
,I/art     (  968): Explicit concurrent mark sweep GC freed 57849(2MB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 17MB/25MB, paused 1.683ms total 164.766ms
,W/PackageManager(  968): Unable to load service info ResolveInfo{276d15f7 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  968): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  968): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:475)
W/PackageManager(  968): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:331)
W/PackageManager(  968): 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
W/PackageManager(  968): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  968): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
W/PackageManager(  968): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
W/PackageManager(  968): 	at android.os.Handler.handleCallback(Handler.java:739)
W/PackageManager(  968): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  968): 	at android.os.Looper.loop(Looper.java:155)
W/PackageManager(  968): 	at com.android.server.SystemServer.run(SystemServer.java:324)
W/PackageManager(  968): 	at com.android.server.SystemServer.main(SystemServer.java:225)
W/PackageManager(  968): 	at java.lang.reflect.Method.invoke(Native Method)
W/PackageManager(  968): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/PackageManager(  968): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
W/PackageManager(  968): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824),
,V/GmsNetworkLocationProvi( 1834): DISABLE,
,I/GCoreNlp( 1834): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/PMS     (  968): acquireWL(140c78cb): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1834 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  968): releaseWL(140c78cb): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
I/BackupManagerService(  968): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
D/PMS     (  968): acquireWL(2c313643): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1834 10024 WorkSource{10024 com.google.android.gms}
,E/WifiStateMachine(  968): handleMessage: E msg.what=131168
E/WifiStateMachine(  968): processMsg: ConnectedState
E/WifiStateMachine(  968):  ConnectedState !CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  968): processMsg: L2ConnectedState
D/PMS     (  968): releaseWL(2c313643): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
D/LocationProviderProxy(  968): applying state to connected service
E/WifiStateMachine(  968):  L2ConnectedState !CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  968): processMsg: ConnectModeState
E/WifiStateMachine(  968):  ConnectModeState !CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  968): processMsg: DriverStartedState
E/WifiStateMachine(  968):  DriverStartedState !CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  968): processMsg: SupplicantStartedState
E/WifiStateMachine(  968):  SupplicantStartedState !CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  968): processMsg: DefaultState
E/WifiStateMachine(  968):  DefaultState !CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  968): handleMessage: X
D/LocationProviderProxy(  968): applying state to connected service
,D/PMS     (  968): acquireWL(108b396d): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1834 10024 WorkSource{10024 com.google.android.gms},
D/PMS     (  968): releaseWL(108b396d): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  968): acquireWL(e14d9a2): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1834 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  968): releaseWL(e14d9a2): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  968): acquireWL(e7c3633): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 6239 10112 null
,D/PMS     (  968): releaseWL(e7c3633): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null,
W/ResourcesManager( 6239): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6239): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/[PluginManager]RegisterService( 1626): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms,
I/[PluginManager]RegisterService( 1626): handle notify Blinkfeed plugin client changed
,D/PackageBroadcastService( 4438): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 4438): Null package name or gms related package.  Ignoreing.
,D/PMS     (  968): acquireWL(11992fb4): PARTIAL_WAKE_LOCK  Icing 0x1 4438 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  968): acquireWL(3fa57dd): PARTIAL_WAKE_LOCK  AsyncService 0x1 6047 10167 null
D/PMS     (  968): releaseWL(3fa57dd): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
I/Icing   ( 4438): updateResources: need to parse f{com.google.android.gms}
D/PMS     (  968): acquireWL(223f1223): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 6047 10167 null
,E/WifiTrafficPoller(  968): TRAFFIC_STATS_POLL true Token 25 num clients 8
,E/WifiTrafficPoller(  968):  packet count Tx=164 Rx=273
,D/PMS     (  968): releaseWL(223f1223): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 null
,I/UpdateIcingCorporaServi( 5889): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,D/PMS     (  968): releaseWL(11992fb4): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms}
,I/UpdateIcingCorporaServi( 5889): UpdateCorporaTask done [took 40 ms] updated apps [took 40 ms] 
,E/WifiStateMachine(  968): handleMessage: E msg.what=131155
,E/WifiStateMachine(  968): processMsg: ConnectedState
E/WifiStateMachine(  968):  ConnectedState !CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=78.0, 0.0, 0.0  rx=131.5 bcn=0 [on:0 tx:0 rx:0 period:2998] from screen [on:0 period:-1459817065] gl hn u24 rssi=-52 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  968): processMsg: L2ConnectedState
E/WifiStateMachine(  968):  L2ConnectedState !CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-57 f=2412 sc=60 link=72 tx=78.0, 0.0, 0.0  rx=131.5 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1459817063] gl hn u24 rssi=-52 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  968):  get link layer stats 0
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1323): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1323): environment dirty rate=0 [7][0][0],
E/WifiStateMachine(  968): fetchRssiLinkSpeedAndFrequencyNative RSSI = -58 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  968): fetchRssiLinkSpeedAndFrequencyNative rssi=-58 linkspeed=72
E/WifiStateMachine(  968): BroadcastRSSIForIMS, newrssi =-58 , oldRssi= -200
E/WifiConfigStore(  968): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-57 "NG700"WPA_PSK
E/WifiStateMachine(  968): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=43.00 txretriesrate=0.00 rxrate=71.25 userTriggerdPenalty0
E/WifiStateMachine(  968):  good link -> stuck count =0
E/WifiStateMachine(  968):  badRSSI count0 lowRSSI count0 --> score 60
E/WifiStateMachine(  968):  isHighRSSI       ---> score=65
D/WifiWatchdogStateMachine(  968): RSSI current: 3 new: -58, 3
D/WifiWatchdogStateMachine(  968): RSSI current: 3 new: -58, 3
D/WIFI_ICON( 1215): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1215): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
E/WifiStateMachine(  968): handleMessage: X
D/WIFI_ICON( 1215): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1215): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,I/ActivityManager(  968): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=6880 uid=10076 gids={50076, 9997} abi=arm64-v8a,
D/PMS     (  968): acquireWL(10c994d9): PARTIAL_WAKE_LOCK  *alarm* 0x1 968 1000 WorkSource{10076}
V/AlarmManager(  968): sending alarm PendingIntent{a04ae9e: PendingIntentRecord{1d66ad7f com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1454534096318, Int=60000
D/PMS     (  968): releaseWL(10c994d9): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10076}
,D/SMSBackup( 6880): SMSBackupAgentService started,
D/SMSBackup( 6880): Checking restore status
,D/SMSBackup( 6880): Restore complete,
D/SMSBackup( 6880): cancelCheckAlarm
,D/SMSBackup( 6880): SMSBackupAgentService completed: completed in 0.0 seconds,
,I/jxcore-log( 6509): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js,
I/jxcore-log( 6509): 
,D/libc    (  968): [NET] android_getaddrinfofornet+,hn 11(0x7777772e687463),sn(),hints(known),family 0,flags 4,
D/libc    (  968): [NET] android_getaddrinfofornet-, err=8
D/libc    (  968): [NET] android_getaddrinfofornet+,hn 11(0x7777772e687463),sn(),hints(known),family 0,flags 1024
D/libc    (  968): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  968): [NET] android_getaddrinfo_proxy+
,D/libc    (  968): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 11(0x7777772e687463),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:101, mark:917605
E/WifiTrafficPoller(  968): TRAFFIC_STATS_POLL true Token 25 num clients 8
E/WifiTrafficPoller(  968):  packet count Tx=166 Rx=276
,D/ConnectivityService(  968): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider(  968): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
I/AlarmManager(  968): [AlarmQueuing] connectivity wifi: true
I/ConnectivityHelper( 1590): [onReceive] WIFI(1): CONNECTED
D/PMS     (  968): acquireWL(2fb5a595): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 968 1000 null
D/PMS     (  968): acquireWL(f0916aa): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 968 1000 null
D/PMS     (  968): releaseWL(f0916aa): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/GpsLocationProvider(  968): [handleMessage] UPDATE_NETWORK_STATE
,D/GpsLocationProvider(  968): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/htcCheckinService(  968): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
D/libc    (  394): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  394): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  968): [NET] android_getaddrinfo_proxy-, success
D/HtcWifiWanDetect(  968): Find DNS Address www.htc.com/23.59.123.86
I/NetworkMonitor( 6738): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 6738): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,E/GpsLocationProvider(  968): No APN found to select.
,D/PMS     (  968): releaseWL(2fb5a595): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/MdScPhnSt( 6646): [dab.1.]  listen tmrbb8
,D/MobileConnectivityChangeReceiver( 6533): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 6533): onReceive CONNECTIVITY_CHANGE networkType=1,
,D/AutoSetting( 1626): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/AutoSetting( 1626): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/AutoSetting( 1626): Util - check NLP state, Allowned:false, Enabled:false
D/AutoSetting( 1626): service - requestNLP() NetworkLocationProvider not enabled
D/AutoSetting( 1626): service - onStartCommand() REMOVE current location bundle
D/AutoSetting( 1626): service - handleMessage() setting current location null
,I/PackageManager(  968):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=4438, uid=10024, userID:0
,D/MdScDataSum( 6646): [dab.1.] summary 118:p1 ignore
,D/ChimeraCfgMgr( 4438): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/Kids    ( 4438): [GCoreUtils] Current gmscore version, 7899448 is smaller than the required version 8400000
,I/Prism.ItemManager( 1590): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true,
I/Prism.ItemManager( 1590): loadItems() com.htc.launcher.pageview.WidgetManager@4cd2221 +
I/Prism.WidgetManager( 1590): onLoadItems() +
,W/ResourcesManager( 1590): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.,
,I/jxcore-log( 6509): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js,
I/jxcore-log( 6509): 
,I/jxcore-log( 6509): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 6509): 
,I/jxcore-log( 6509): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js,
I/jxcore-log( 6509): 
,W/ResourcesManager( 1590): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.,
,I/jxcore-log( 6509): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 6509): 
,I/jxcore-log( 6509): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 6509): 
,I/jxcore-log( 6509): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js,
I/jxcore-log( 6509): 
,I/jxcore-log( 6509): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js,
I/jxcore-log( 6509): 
,W/asset   ( 1590): Copying FileAsset 0x5567300090 (zip:/data/app/com.gameloft.android.gdc-2/base.apk:/resources.arsc) to buffer size 405676 to make it aligned.,
,E/Prism.WidgetManager( 1590): The same lists. No need to update. skip it.,
I/Prism.WidgetManager( 1590): onLoadItems() -
I/Prism.ItemManager( 1590): loadItems() com.htc.launcher.pageview.WidgetManager@4cd2221 -
,D/PhoneApp( 1546): EVENT_QUERY_MO_PACKAGES,
,D/PhoneApp( 1546): -- N1 =0,
,D/PhoneApp( 1546): -- N2 =0
,D/PhoneApp( 1546): -- N3 =0
,E/WifiTrafficPoller(  968): TRAFFIC_STATS_POLL true Token 25 num clients 8,
E/WifiTrafficPoller(  968):  packet count Tx=168 Rx=279
,E/WifiDataStallTracker(  968): DATA_MONITOR_POLL true Token 3,
,D/WifiDataStallTracker(  968): updateDataStallInfo: mDataStallTxRxSum={txSum=144 rxSum=125} preTxRxSum={txSum=0 rxSum=0}
D/WifiDataStallTracker(  968): updateDataStallInfo: IN/OUT
D/WifiDataStallTracker(  968): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,E/WifiTrafficPoller(  968): TRAFFIC_STATS_POLL true Token 25 num clients 8,
E/WifiTrafficPoller(  968):  packet count Tx=169 Rx=280
,E/WifiStateMachine(  968): handleMessage: E msg.what=131155,
E/WifiStateMachine(  968): processMsg: ConnectedState
,E/WifiStateMachine(  968):  ConnectedState !CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2412 sc=60 link=72 tx=43.0, 0.0, 0.0  rx=71.2 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1459814054] gl hn u24 rssi=-53 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  968): processMsg: L2ConnectedState
E/WifiStateMachine(  968):  L2ConnectedState !CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2412 sc=60 link=72 tx=43.0, 0.0, 0.0  rx=71.2 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1459814053] gl hn u24 rssi=-53 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,E/WifiStateMachine(  968):  get link layer stats 0
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1323): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1323): environment dirty rate=0 [5][0][0],
E/WifiStateMachine(  968): fetchRssiLinkSpeedAndFrequencyNative RSSI = -58 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WIFI_ICON( 1215): updateWifiState: RSSI_CHANGED 3 -> 3
E/WifiStateMachine(  968): fetchRssiLinkSpeedAndFrequencyNative rssi=-58 linkspeed=72
D/StatusBar.NetworkController( 1215): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
E/WifiStateMachine(  968): fetchRssiLinkSpeedAndFrequencyNative send RSSIChange intent, SameSignalLevelCount =1
E/WifiConfigStore(  968): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-57 "NG700"WPA_PSK
D/WifiWatchdogStateMachine(  968): RSSI current: 3 new: -58, 3
E/WifiStateMachine(  968): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=24.00 txretriesrate=0.00 rxrate=38.62 userTriggerdPenalty0
E/WifiStateMachine(  968):  good link -> stuck count =0
E/WifiStateMachine(  968):  badRSSI count0 lowRSSI count0 --> score 60
E/WifiStateMachine(  968):  isHighRSSI       ---> score=65
D/WifiWatchdogStateMachine(  968): RSSI current: 3 new: -58, 3
D/WIFI_ICON( 1215): updateWifiState: RSSI_CHANGED 3 -> 3
E/WifiStateMachine(  968): handleMessage: X
,D/StatusBar.NetworkController( 1215): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/PMS     (  968): acquireWL(1328ca13): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 6738 10159 null,
,I/PackageManager(  968):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=6738, uid=10159, userID:0,
,D/PMS     (  968): releaseWL(1328ca13): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null,
I/MusicLeanback( 6738): Conditions not met for autocaching. okToAttempt=false
I/MusicLeanback( 6738): Stop autocaching.
,D/WearableService( 5682): callingUid 10024, callindPid: 5682
,D/PMS     (  968): acquireWL(355c7eb2): PARTIAL_WAKE_LOCK  *alarm* 0x1 968 1000 WorkSource{10024},
V/AlarmManager(  968): sending alarm PendingIntent{16a85e03: PendingIntentRecord{2ba72180 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=110213, Int=0
V/AlarmManager(  968): sending alarm PendingIntent{2822a3ba: PendingIntentRecord{7e926b android broadcastIntent}}, i=com.android.server.WifiManager.action.START_SCAN, t=1, cnt=1, w=1454534094358, Int=20000
D/PMS     (  968): acquireWL(2b5e73b9): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1873 10024 WorkSource{10024 com.google.android.gms}
,E/WifiStateMachine(  968): WiFiStateMachine SCAN ALARM,
D/WifiDisplayAdapter(  968): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  968):     Client/Owner: Client
D/WifiDisplayAdapter(  968):     GroupId: 
D/WifiDisplayAdapter(  968):     Passphrase: 
D/WifiDisplayAdapter(  968):     SessionId: 0
D/WifiDisplayAdapter(  968):     IP Address: }
D/PMS     (  968): releaseWL(355c7eb2): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,E/WifiStateMachine(  968): handleMessage: E msg.what=131143
E/WifiStateMachine(  968): processMsg: ConnectedState
E/WifiStateMachine(  968):  ConnectedState !CMD_START_SCAN -2 -2 ic=5 proc(ms):2 dur:78 rssi=-58 f=2412 sc=60 link=72 tx=24.0, 0.0, 0.0  rx=38.6 list=2412 [on:0 tx:0 rx:0 period:422] from screen [on:0 period:-1459813625]
E/WifiStateMachine(  968): processMsg: L2ConnectedState
E/WifiStateMachine(  968):  L2ConnectedState !CMD_START_SCAN -2 -2 ic=5 proc(ms):2 dur:78 rssi=-58 f=2412 sc=60 link=72 tx=24.0, 0.0, 0.0  rx=38.6 list=2412 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1459813624]
E/WifiStateMachine(  968): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=24.00 rxSuccessRate=38.62 targetRoamBSSID=c0:ff:d4:d3:aa:48 RSSI=-58
E/WifiStateMachine(  968): WifiStateMachine CMD_START_SCAN with age=38335 interval=40000 maxinterval=300000
E/WifiStateMachine(  968): WifiStateMachine CMD_START_SCAN prevent full band scan due to pkt rate
D/libc    ( 1873): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
D/libc    ( 1873): [NET] android_getaddrinfofornet-, err=8
E/WifiStateMachine(  968): WifiStateMachine CMD_START_SCAN full=false
E/WifiConfigStore(  968): makeChannelList age=3600000 for "NG700"WPA_PSK max=6 bssids=1
E/WifiConfigStore(  968): has c0:ff:d4:d3:aa:48 freq=2412 age=426 ?=true
E/WifiStateMachine(  968): WifiStateMachine starting scan for "NG700"WPA_PSK with 2412
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN TYPE=ONLY freq=2412"
D/wpa_supplicant( 1323): wlan0: Control interface command 'SCAN TYPE=ONLY freq=2412'
D/wpa_supplicant( 1323): wlan0: Setting scan request: 0.000000 sec
I/wpa_supplicant( 1323): wpa_supplicant_scan enter
,D/wpa_supplicant( 1323): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 1323): WPS: Building WPS IE for Probe Request
D/wpa_supplicant( 1323): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 1323): WPS:  * Request Type
D/wpa_supplicant( 1323): WPS:  * Config Methods (4288)
D/wpa_supplicant( 1323): WPS:  * UUID-E
D/wpa_supplicant( 1323): WPS:  * Primary Device Type
D/wpa_supplicant( 1323): WPS:  * RF Bands (3)
D/wpa_supplicant( 1323): WPS:  * Association State
D/wpa_supplicant( 1323): WPS:  * Configuration Error (0)
D/wpa_supplicant( 1323): WPS:  * Device Password ID (0)
D/wpa_supplicant( 1323): WPS:  * Manufacturer
D/wpa_supplicant( 1323): WPS:  * Model Name
D/wpa_supplicant( 1323): WPS:  * Model Number
D/wpa_supplicant( 1323): WPS:  * Device Name
,D/wpa_supplicant( 1323): WPS:  * Version2 (0x20)
D/wpa_supplicant( 1323): P2P: * P2P IE header
D/wpa_supplicant( 1323): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 1323): P2P: * Listen Channel: Regulatory Class 81 Channel 1
D/wpa_supplicant( 1323): wlan0: Limit manual scan to specified channels
D/wpa_supplicant( 1323): wlan0: Add radio work 'scan'@0x5594371680
D/wpa_supplicant( 1323): wlan0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1323): wlan0: Starting radio work 'scan'@0x5594371680 after 0.000032 second wait
D/wpa_supplicant( 1323): wlan0: nl80211: scan request
D/wpa_supplicant( 1323): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 1323): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 1323): wlan0: nl80211: Scan trigger
D/wpa_supplicant( 1323): wlan0: Event SCAN_STARTED (49) received
,D/wpa_supplicant( 1323): wlan0: Own scan request started a scan in 0.000068 seconds
I/wpa_supplicant( 1323): wlan0: CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine(  968): [1,454,534,099,721 ms] noteScanstart no scan source
E/WifiStateMachine(  968): handleMessage: X
D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor(  968): WifiMonitor:wlan0 cnt=50 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  968): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  968): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,D/libc    ( 1873): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    ( 1873): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1873): [NET] android_getaddrinfo_proxy+
D/libc    ( 1873): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  394): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,E/GmsUtils( 6738): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 6738): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/wpa_supplicant( 1323): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0,
W/ContextImpl(  968): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:14146 com.android.server.wifi.WifiStateMachine.handleMediaLinkEvent:14311 com.android.server.wifi.WifiStateMachine.access$6000:268 com.android.server.wifi.WifiStateMachine$SupplicantStartedState.processMessage:8091 
D/wpa_supplicant( 1323): wlan0: nl80211: New scan results available
D/wpa_supplicant( 1323): nl80211: Scan included frequencies: 2412
D/wpa_supplicant( 1323): wlan0: Event SCAN_RESULTS (3) received
I/wpa_supplicant( 1323): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1323): wlan0: Scan completed in 0.072489 seconds
D/wpa_supplicant( 1323): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1323): nl80211: Associated with c0:ff:d4:d3:aa:48
,D/wpa_supplicant( 1323): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1323): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
I/wpa_supplicant( 1323): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1323): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-58
I/wpa_supplicant( 1323): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-58
I/wpa_supplicant( 1323): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-77
D/wpa_supplicant( 1323): wlan0: BSS: Start scan result update 7
D/wpa_supplicant( 1323): BSS: last_scan_res_used=4/32
D/wpa_supplicant( 1323): wlan0: Scan-only results received
D/wpa_supplicant( 1323): wlan0: Radio work 'scan'@0x5594371680 done in 0.073144 seconds
E/WifiMonitor(  968): WifiMonitor:wlan0 cnt=51 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor(  968): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
,E/WifiStateMachine(  968): handleMessage: E msg.what=147461
E/WifiStateMachine(  968): processMsg: ConnectedState
E/WifiStateMachine(  968):  ConnectedState !SCAN_RESULTS_EVENT 0 0 found=4 known=1 got=4 bcn=0
E/WifiStateMachine(  968): processMsg: L2ConnectedState
E/WifiStateMachine(  968):  L2ConnectedState !SCAN_RESULTS_EVENT 0 0 found=4 known=1 got=4 bcn=0
E/WifiStateMachine(  968): processMsg: ConnectModeState
E/WifiStateMachine(  968):  ConnectModeState !SCAN_RESULTS_EVENT 0 0 found=4 known=1 got=4 bcn=0
E/WifiStateMachine(  968): processMsg: DriverStartedState
E/WifiStateMachine(  968):  DriverStartedState !SCAN_RESULTS_EVENT 0 0 found=4 known=1 got=4 bcn=0
E/WifiStateMachine(  968): processMsg: SupplicantStartedState
E/WifiStateMachine(  968):  SupplicantStartedState !SCAN_RESULTS_EVENT 0 0 found=4 known=1 got=4 bcn=0
D/WifiStateMachine(  968): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1323): wlan0: Control interface command 'LIST_DONGLES'
E/WifiStateMachine(  968): [1,454,534,099,799 ms] noteScanEnd no scan source
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/wpa_supplicant( 1323): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
E/WifiStateMachine(  968): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@1cc7339b sup_state=COMPLETED debouncing=false
E/WifiAutoJoinController (  968): NG7005g c0:ff:d4:d3:aa:4a rssi=-49 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiAutoJoinController (  968): NG700 c0:ff:d4:d3:aa:48 rssi=-58 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiConfigStore(  968): updateSavedNetworkHistory(): try "NG700"WPA_PSK SSID="NG700" NG700 [WPA2-PSK-CCMP][WPS][ESS] ajst=0
E/WifiConfigStore(  968): updateSavedNetworkHistory: HTC improve mode
E/WifiConfigStore(  968):         got known scan result c0:ff:d4:d3:aa:48 key : "NG700"WPA_PSK num: 1 rssi=-58 freq=2412
E/WifiAutoJoinController (  968): Gonzos 38:f8:89:11:e9:11 rssi=-77 cap [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS] is not scored
E/WifiAutoJoinController (  968): 01ABC c2:ff:d4:d3:aa:48 rssi=-58 cap [WPA2-PSK-CCMP][ESS] is not scored
E/WifiAutoJoinController (  968): ageScanResultsOut delay 40000 size 4 now 1454534099801
E/WifiAutoJoinController (  968): newSupplicantResults size=4 known=1 true
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 STATUS-NO_EVENTS"
D/wpa_supplicant( 1323): wlan0: Control interface command 'STATUS-NO_EVENTS'
,E/WifiAutoJoinController (  968): attemptAutoJoin() status=bssid=c0:ff:d4:d3:aa:48
E/WifiAutoJoinController (  968): ssid=NG700
E/WifiAutoJoinController (  968): id=0
E/WifiAutoJoinController (  968): mode=station
E/WifiAutoJoinController (  968): pairwise_cipher=CCMP
E/WifiAutoJoinController (  968): group_cipher=CCMP
E/WifiAutoJoinController (  968): key_mgmt=WPA2-PSK
E/WifiAutoJoinController (  968): wpa_state=COMPLETED
E/WifiAutoJoinController (  968): ip_address=192.168.1.130
E/WifiAutoJoinController (  968): p2p_device_address=92:e7:c4:e6:4c:f8
E/WifiAutoJoinController (  968): address=XX:XX:XX:XX:XX:XX
E/WifiAutoJoinController (  968): uuid=12345678-9abc-def0-1234-56789abcdef1 split=12
E/WifiAutoJoinController (  968): attemptAutoJoin() num recent config 1 current="NG700"WPA_PSK ---> suppNetId=0
E/WifiAutoJoinController (  968): attemptAutoJoin good candidate seen, bumped hard -> status=0 "NG700"WPA_PSK rssi=(-58,-127) num=(1,0)
E/WifiAutoJoinController (  968): attemptAutoJoin skip current candidate  0 key "NG700"WPA_PSK
E/WifiAutoJoinController (  968): attemptRoam: "NG700"WPA_PSK Found c0:ff:d4:d3:aa:48 rssi=-58 freq=2412 Current: c0:ff:d4:d3:aa:48
D/HtcWifiControlRoamOffload: (  968): roamCandidate: nullcurrentBSSID: c0:ff:d4:d3:aa:48
E/WifiStateMachine(  968): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiAutoJoinController (  968): Done attemptAutoJoin status=0
E/WifiConfigStore(  968):  writeKnownNetworkHistory() num networks:1 needWrite=false
E/WifiStateMachine(  968): handleMessage: X
,D/libc    (  394): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  394): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 1873): [NET] android_getaddrinfo_proxy-, success
,D/libc    ( 1873): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4,
D/libc    ( 1873): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 1873): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4,
D/libc    ( 1873): [NET] android_getaddrinfofornet-, err=8
,D/PMS     (  968): acquireWL(388fd3fe): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 968 1000 WorkSource{1000}
V/AlarmManager(  968): sending alarm PendingIntent{191f7091: PendingIntentRecord{27d54bf6 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=110500, Int=0
,D/PMS     (  968): releaseWL(388fd3fe): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
D/WeatherUtility( 1215): Weather sync is On
W/WeatherTimeKeeper( 1215): [refreshWeatherData] no weather data
,I/ClockController( 1215): schedule update now=1454534100059 next=59941,
I/Clock   ( 1215): updateClock:22:15 Europe/Warsaw
I/Clock   ( 1215): updateClock:22:15 Europe/Warsaw,
I/Clock   ( 1215): updateClock:22:15 Europe/Warsaw
,D/PMS     (  968): acquireWL(1c48d75f): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1873 10024 WorkSource{10024 com.google.android.gms}
,D/GCM     ( 1873): Connected
D/PMS     (  968): releaseWL(2b5e73b9): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  968): releaseWL(1c48d75f): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  968): acquireWL(2f1cd5ac): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1873 10024 WorkSource{10024 com.google.android.gms}
,D/GCM     ( 1873): Message class com.google.f.a.a.p,
D/PMS     (  968): releaseWL(2f1cd5ac): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms}
,E/WifiTrafficPoller(  968): TRAFFIC_STATS_POLL true Token 25 num clients 8,
E/WifiTrafficPoller(  968):  packet count Tx=178 Rx=290
,I/PMS     (  968): Going to sleep due to screen timeout (uid 1000)...,
I/SensorManager(  968): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@5c8a121
W/SensorService(  968): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  968): disable: get sensor name = Accelerometer Sensor
,W/SensorService(  968): pid=968, uid=1000
W/PMN     (  968): goingToSleep
W/SensorService(  968): Active sensors: size = 4
W/SensorService(  968): Accelerometer Sensor (handle=0x00000000, connections=1)
W/SensorService(  968): CM32181 Light sensor (handle=0x00000003, connections=1)
,W/SensorService(  968): CM36686 Proximity sensor (handle=0x00000004, connections=1),
W/SensorService(  968): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  968): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@5c8a121, eanble = 0, strlen(mName) = 90
W/SensorService(  968): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  968): Listener[0] = com.android.server.display.AutomaticBrightnessController$1@19ff8e08
W/SensorService(  968): Listener[1] = com.htc.smartdim.sensor_eye@3a67fdcc
W/SensorService(  968): void android::SensorService::listenerSensor(const char*, int32_t)--:
,W/PMS     (  968): mWirelessDisplayManager is null
,W/PMS     (  968): mWirelessDisplayManager is still null
D/PMS     (  968): acquireWL(7699275): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 968 1000 null
,W/PMN     (  968): goingToSleep done
,W/HtcLockScreen( 1215): KeyguardViewMediator: doKeyguard: not showing because lockscreen is off
,W/HtcSystemUPManager(  968): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
,I/PMS     (  968): Sleeping (uid 1000)...
D/XAN-DPS (  968): prepareColorFade 1
D/AlarmManager(  968): ACTION_SCREEN_ON
,I/AlarmManager(  968): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  968): [AlarmQueuing] done recovering
D/PMS     (  968): releaseWL(7699275): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,I/AlarmManager(  968): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  968): [AlarmQueuing] done EPS screen off alarm recovering
E/WifiTrafficPoller(  968): ENABLE_TRAFFIC_STATS_POLL true Token 25
E/WifiTrafficPoller(  968):  packet count Tx=178 Rx=291
E/WifiTrafficPoller(  968): notifying of data activity 1
E/WifiDataStallTracker(  968): ENABLE_DATA_MONITOR_POLL true Token 3
E/WifiStateMachine(  968): handleMessage: E msg.what=131167
E/WifiStateMachine(  968): processMsg: ConnectedState
E/WifiStateMachine(  968):  ConnectedState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  968): processMsg: L2ConnectedState
E/WifiStateMachine(  968):  L2ConnectedState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  968): processMsg: ConnectModeState
,E/WifiStateMachine(  968):  ConnectModeState !CMD_SCREEN_STATE_CHANGED 1 0,
E/WifiStateMachine(  968): processMsg: DriverStartedState
D/WifiDisplayAdapter(  968): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  968):     Client/Owner: Client
D/WifiDisplayAdapter(  968):     GroupId: 
D/WifiDisplayAdapter(  968):     Passphrase: 
D/WifiDisplayAdapter(  968):     SessionId: 0
D/WifiDisplayAdapter(  968):     IP Address: }
,E/WifiStateMachine(  968):  DriverStartedState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  968): processMsg: SupplicantStartedState
E/WifiStateMachine(  968):  SupplicantStartedState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  968): processMsg: DefaultState
E/WifiStateMachine(  968):  DefaultState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  968):  handleScreenStateChanged Enter: screenOn=true mCurrentScanAlarmMs = 20000 mUserWantsSuspendOpt=false state ConnectedState suppState:CompletedState
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
D/wpa_supplicant( 1323): wlan0: Control interface command 'SET_SCREEN_ON 1'
I/wpa_supplicant( 1323): SET_SCREEN_ON:On
I/wpa_supplicant( 1323): htc_wext_set_keepalive +
I/wpa_supplicant( 1323): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1323): getPrivFuncNum +	
I/wpa_supplicant( 1323): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1323): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1323): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1323): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1323): htc_wext_set_TX_TRACKING - ret = 0
E/WifiStateMachine(  968): setScanAlarm true period 20000 initial delay 200mAlarmEnabledtrue
D/WifiStateMachine(  968): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine(  968): handleScreenStateChanged Exit: true
,E/WifiStateMachine(  968): handleMessage: X
E/WifiStateMachine(  968): handleMessage: E msg.what=131154
E/WifiStateMachine(  968): processMsg: ConnectedState
E/WifiStateMachine(  968):  ConnectedState !CMD_ENABLE_RSSI_POLL 1 0
E/WifiStateMachine(  968): processMsg: L2ConnectedState
E/WifiStateMachine(  968):  L2ConnectedState !CMD_ENABLE_RSSI_POLL 1 0
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1323): wlan0: Control interface command 'SIGNAL_POLL'
D/WifiDataStallTracker(  968): updateDataStallInfo: mDataStallTxRxSum={txSum=152 rxSum=133} preTxRxSum={txSum=152 rxSum=133}
D/WifiDataStallTracker(  968): updateDataStallInfo: NONE
D/WifiDataStallTracker(  968): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
I/wpa_supplicant( 1323): environment dirty rate=0 [9][0][0]
E/WifiStateMachine(  968): fetchRssiLinkSpeedAndFrequencyNative RSSI = -58 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  968): fetchRssiLinkSpeedAndFrequencyNative rssi=-58 linkspeed=72
E/WifiStateMachine(  968): fetchRssiLinkSpeedAndFrequencyNative send RSSIChange intent, SameSignalLevelCount =2
E/WifiConfigStore(  968): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-58 "NG700"WPA_PSK
E/WifiStateMachine(  968): handleMessage: X
E/WifiStateMachine(  968): handleMessage: E msg.what=131127
E/WifiStateMachine(  968): processMsg: ConnectedState
E/WifiStateMachine(  968):  ConnectedState !CMD_ENABLE_ALL_NETWORKS 0 0
E/WifiStateMachine(  968): processMsg: L2ConnectedState
E/WifiStateMachine(  968):  L2ConnectedState !CMD_ENABLE_ALL_NETWORKS 0 0
E/WifiStateMachine(  968): processMsg: ConnectModeState
E/WifiStateMachine(  968):  ConnectModeState !CMD_ENABLE_ALL_NETWORKS 0 0
E/WifiStateMachine(  968): handleMessage: X
E/WifiStateMachine(  968): handleMessage: E msg.what=131129
E/WifiStateMachine(  968): processMsg: ConnectedState
E/WifiStateMachine(  968):  ConnectedState !CMD_CLEAR_BLACKLIST 0 0
E/WifiStateMachine(  968): processMsg: L2ConnectedState
E/WifiStateMachine(  968):  L2ConnectedState !CMD_CLEAR_BLACKLIST 0 0
E/WifiStateMachine(  968): processMsg: ConnectModeState
E/WifiStateMachine(  968):  ConnectModeState !CMD_CLEAR_BLACKLIST 0 0
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 BLACKLIST clear"
D/wpa_supplicant( 1323): wlan0: Control interface command 'BLACKLIST clear'
E/wpa_supplicant( 1323): wlan0: BLACKLIST CLEAR 
V/SRS_Proc(  407): ParamSet string: screen_state=on
D/WifiMonitor(  968): Event [IFNAME=wlan0 BLACKLIST CLEAR ]
E/audio_a2dp_hw(  407): adev_set_parameters: ERROR: set param called even when stream out is null
E/WifiMonitor(  968): WifiMonitor:wlan0 cnt=52 dispatchEvent: BLACKLIST CLEAR 
,E/WifiStateMachine(  968): handleMessage: X
D/WifiController(  968): handleMessage: E msg.what=155650
D/WifiController(  968): processMsg: DeviceActiveState
D/WifiController(  968): processMsg: StaEnabledState
D/WifiController(  968): processMsg: DefaultState
D/WifiController(  968): handleMessage: X
,D/NetworkPolicy(  968): updateScreenOn: false
,V/NetworkPolicy(  968): updateIfacesLocked()
I/Adreno-EGL(  968): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL(  968): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL(  968): Build Date: 03/09/15 Mon
I/Adreno-EGL(  968): Local Branch: 
I/Adreno-EGL(  968): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL(  968): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL(  968):                  d74aa161a12b9c6fc6332151
D/NetworkManagementService(  968): isBandwidthControlEnabled: doneSignal.getCount()= 0
,D/WifiWatchdogStateMachine(  968): RSSI current: 3 new: -58, 3
,D/WIFI_ICON( 1215): WifiActivity: 1
D/StatusBar.NetworkController( 1215): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WIFI_ICON( 1215): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1215): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/GpsLocationProvider(  968): receive broadcast intent, action: android.intent.action.SCREEN_ON
I/ActivityManager(  968): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=6928 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
,D/DotMatrix( 1324): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,D/Process (  968): killProcessQuiet, pid=5407,
I/ActivityManager(  968): Killing 5407:com.htc.mediamanager/u0a28 (adj 15): empty #17,
D/Process (  968): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,E/WifiTrafficPoller(  968): TRAFFIC_STATS_POLL true Token 26 num clients 8,
,D/XAN-DPS (  968): prepareColorFade done
,D/XAN-DPS (  968): setBrightness to 0
,I/DisplayManagerService(  968): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 442.451 x 443.345 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
D/DotMatrix( 1324): [EventService]  onDisplayChanged: 0
,I/SensorManager(  968): unregisterListenerImpl++: listener = com.android.server.display.AutomaticBrightnessController$1@19ff8e08
V/ActivityManager(  968): Display changed displayId=0,
,W/SensorService(  968): Following SensorService logs are not warning, just make sure they are printed
W/DisplayManagerService(  968): Failed to notify process 5407 that displays changed, assuming it died.
W/DisplayManagerService(  968): android.os.TransactionTooLargeException
W/DisplayManagerService(  968): 	at android.os.BinderProxy.transactNative(Native Method)
W/DisplayManagerService(  968): 	at android.os.BinderProxy.transact(Binder.java:504)
W/DisplayManagerService(  968): 	at android.hardware.display.IDisplayManagerCallback$Stub$Proxy.onDisplayEvent(IDisplayManagerCallback.java:81)
W/DisplayManagerService(  968): 	at com.android.server.display.DisplayManagerService$CallbackRecord.notifyDisplayEventAsync(DisplayManagerService.java:1143)
W/DisplayManagerService(  968): 	at com.android.server.display.DisplayManagerService.deliverDisplayEvent(DisplayManagerService.java:977)
W/DisplayManagerService(  968): 	at com.android.server.display.DisplayManagerService.access$500(DisplayManagerService.java:120)
W/DisplayManagerService(  968): 	at com.android.server.display.DisplayManagerService$DisplayManagerHandler.handleMessage(DisplayManagerService.java:1072)
W/DisplayManagerService(  968): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/DisplayManagerService(  968): 	at android.os.Looper.loop(Looper.java:155)
W/DisplayManagerService(  968): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/DisplayManagerService(  968): 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
W/SensorService(  968): disable: get sensor name = CM32181 Light sensor
I/ActivityManager(  968): Recipient 5407
D/DotMatrix( 1324): [EventService] mbHDMIConnect: false, mCoverOn:false
,E/JavaBinder(  968): !!! FAILED BINDER TRANSACTION !!!
E/qdutils (  385): int qdutils::getHDMINode(): Failed to open fb node 2
W/SensorService(  968): pid=968, uid=1000
W/SensorService(  968): Active sensors: size = 3
W/SensorService(  968): Accelerometer Sensor (handle=0x00000000, connections=1)
W/SensorService(  968): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  968): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  968): SensorService::listenerSensor++: mName = com.android.server.display.AutomaticBrightnessController$1@19ff8e08, eanble = 0, strlen(mName) = 67
W/SensorService(  968): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  968): Listener[0] = com.htc.smartdim.sensor_eye@3a67fdcc
W/SensorService(  968): void android::SensorService::listenerSensor(const char*, int32_t)--:
E/qdutils (  385): int qdutils::getHDMINode(): Failed to find HDMI node
,I/IntentController( 1215): receive(android.intent.action.SCREEN_ON,1,false)
,D/Process (  968): killProcessQuiet, pid=6445
I/ActivityManager(  968): Killing 6445:com.google.android.gms.unstable/u0a24 (adj 15): empty #17
,D/Process (  968): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  968): Recipient 6445
,W/ContextImpl( 6928): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,W/ContextImpl( 6928): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:22 android.app.ActivityThread.handleReceiver:2712 ,
,D/PowerUsageList:PowerUsageHelper( 6928): MY_DEBUG = false,
,D/PMS     (  968): acquireWL(24e9b2d): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1834 10024 WorkSource{10024 com.google.android.gms},
,D/SmartSyncUtils( 6928): isEpsOn(), nState = 0
D/PMS     (  968): acquireWL(208df862): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1834 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  968): releaseWL(208df862): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  968): releaseWL(24e9b2d): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,E/qdutils (  385): int qdutils::getHDMINode(): Failed to open fb node 2
E/qdutils (  385): int qdutils::getHDMINode(): Failed to find HDMI node
D/PMS     (  968): Setting HAL interactive mode to false
D/SurfaceControl(  968): Excessive delay in setPowerMode(): 290ms
D/PMS     (  968): Setting HAL interactive mode to false done
D/PMS     (  968): Setting HAL auto-suspend mode to true
D/PMS     (  968): Setting HAL auto-suspend mode done
,W/HtcSystemUPManager(  968): HtcSystemUPHandler The policy is disabled. AppId: UTD_BI, category: C0006
I/InputMethodManagerService(  968): screenObserver, isScreenOn=false
D/StatusBarManagerService(  968): swetImeWindowStatus vis=0 backDisposition=0
I/InputMethodManagerService(  968): Disable input method client, pid=6509
,I/PhoneStatusBar( 1215): setImeWindowStatus(false,false)
I/InputMethodManager( 6509): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{2fb12e0b VFEDH.C. .F...... 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@3f1004f6
,D/HABCtrl (  968): TPE algorithm. remove timeout.
,D/PMS     (  968): acquireWL(1beccdf3): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 968 1000 null
I/BatteryService(  968): n_update end
,D/UsbnetService(  968): BroadcastReceiver::onReceive+,
D/PMS     (  968): OOBE c monitor 11
D/DotMatrix( 1324): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/PMS     (  968): releaseWL(1beccdf3): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1324): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  968): acquireWL(785eab0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 6928 1000 null
D/DotMatrix( 1324): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  968): updateBatteryInfo
I/IntentController( 1215): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/NotificationService(  968): plugged=true pluggin=true
D/HeadsetStateMachine( 3121): Disconnected process message: 10, size: 0
D/PowerUI ( 1215): closing low battery warning: level=100
D/NfcService( 1562): ScreenObserver: OFF
D/PMS     (  968): runPSCheck
D/UsbnetService(  968): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  968): Checking...
D/UsbnetService(  968):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/HtcPowerSaver(  968): >> updateStatus
D/UsbnetService(  968): BroadcastReceiver::onReceive-
D/WifiController(  968): battery changed pluggedType: 2
D/WifiController(  968): handleMessage: E msg.what=155652
D/PowerUI ( 1215): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  968): processMsg: DeviceActiveState
D/PMS     (  968): acquireWL(35a6bd29): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1562 1027 null
D/WifiController(  968): processMsg: StaEnabledState
D/WifiController(  968): processMsg: DefaultState
D/WifiController(  968): handleMessage: X
D/NfcService( 1562): applyRouting - 0
I/HtcPowerSaver(  968): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  968): << updateStatus
D/NfcService( 1562): applyRouting -2
,D/NfcService( 1562): applyRouting
D/NfcService( 1562): Ignore this applyRouting...
D/PMS     (  968): releaseWL(35a6bd29): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,I/InputManager(  968): Cancel all due to getting PMS screen off broadcast. ActualScreenOn=false
,I/IntentController( 1215): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
,D/AlarmManager(  968): ACTION_SCREEN_OFF
,I/SensorManager( 1215): registerListenerImpl: listener = com.htc.sense.easyaccessservice.SensorHubService@1082bde3, sensor = {Sensor name="hTC Gesture Motion HIDI", vendor="hTC Corp.", version=1, type=10, maxRange=200.0, resolution=1.0, power=0.2, minDelay=0}, delay = 200000, handler = null
I/AlarmManager(  968): [AlarmQueuing] screen off now: 
I/AlarmManager(  968): [AlarmQueuing] data connection: true
I/AlarmManager(  968): [AlarmQueuing] wifi connection: true
,W/SensorService(  968): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  968): enable: get sensor name = hTC Gesture Motion HIDI
E/WifiTrafficPoller(  968): ENABLE_TRAFFIC_STATS_POLL false Token 26
,D/WifiDataStallTracker(  968): stopDataStallAlarm 
E/WifiDataStallTracker(  968): ENABLE_DATA_MONITOR_POLL false Token 4
E/WifiStateMachine(  968): handleMessage: E msg.what=131167
E/WifiStateMachine(  968): processMsg: ConnectedState
E/WifiStateMachine(  968):  ConnectedState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  968): processMsg: L2ConnectedState
E/WifiStateMachine(  968):  L2ConnectedState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  968): processMsg: ConnectModeState
E/WifiStateMachine(  968):  ConnectModeState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  968): processMsg: DriverStartedState
E/WifiStateMachine(  968):  DriverStartedState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  968): processMsg: SupplicantStartedState
V/SRS_Proc(  407): ParamSet string: screen_state=off
E/audio_a2dp_hw(  407): adev_set_parameters: ERROR: set param called even when stream out is null
E/WifiStateMachine(  968):  SupplicantStartedState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  968): processMsg: DefaultState
E/WifiStateMachine(  968):  DefaultState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  968):  handleScreenStateChanged Enter: screenOn=false mCurrentScanAlarmMs = 20000 mUserWantsSuspendOpt=false state ConnectedState suppState:CompletedState
W/SensorService(  968): pid=1215, uid=10041
W/SensorService(  968): Active sensors: size = 4
W/SensorService(  968): Accelerometer Sensor (handle=0x00000000, connections=1)
W/SensorService(  968): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
D/WifiDisplayAdapter(  968): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  968):     Client/Owner: Client
D/WifiDisplayAdapter(  968):     GroupId: 
D/WifiDisplayAdapter(  968):     Passphrase: 
D/WifiDisplayAdapter(  968):     SessionId: 0
D/WifiDisplayAdapter(  968):     IP Address: }
W/SensorService(  968): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  968): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
D/wpa_supplicant( 1323): wlan0: Control interface command 'SET_SCREEN_ON 0'
I/wpa_supplicant( 1323): SET_SCREEN_ON:Off
D/NetworkPolicy(  968): updateScreenOn: false
,I/wpa_supplicant( 1323): htc_wext_set_keepalive +
V/NetworkPolicy(  968): updateIfacesLocked()
I/wpa_supplicant( 1323): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/NetworkManagementService(  968): isBandwidthControlEnabled: doneSignal.getCount()= 0
D/wpa_supplicant( 1323): getPrivFuncNum +	
I/wpa_supplicant( 1323): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1323): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1323): get_ip_address source addr = c0a80182
I/wpa_supplicant( 1323): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1323): htc_wext_set_keepalive - ret = 0
D/WifiController(  968): handleMessage: E msg.what=155651
D/WifiController(  968): processMsg: DeviceActiveState
D/WifiController(  968): processMsg: StaEnabledState
D/WifiController(  968): processMsg: DefaultState
W/SensorService(  968): SensorService::listenerSensor++: mName = com.htc.sense.easyaccessservice.SensorHubService@1082bde3, eanble = 1, strlen(mName) = 57
W/SensorService(  968): Active Listeners: mActiveListeners.size() = 2
,W/SensorService(  968): Listener[0] = com.htc.smartdim.sensor_eye@3a67fdcc
D/WifiController(  968): handleMessage: X
W/SensorService(  968): Listener[1] = com.htc.sense.easyaccessservice.SensorHubService@1082bde3
W/SensorService(  968): void android::SensorService::listenerSensor(const char*, int32_t)--:
E/WifiStateMachine(  968): setScanAlarm false period 20000 initial delay 0mAlarmEnabledtrue
D/WifiStateMachine(  968): backgroundScan enabled=true startBackgroundScanIfNeeded:false
E/WifiStateMachine(  968): handleScreenStateChanged Exit: false
E/WifiStateMachine(  968): handleMessage: X
E/WifiStateMachine(  968): handleMessage: E msg.what=131154
E/WifiStateMachine(  968): processMsg: ConnectedState
E/WifiStateMachine(  968):  ConnectedState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  968): processMsg: L2ConnectedState
E/WifiStateMachine(  968):  L2ConnectedState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  968): handleMessage: X
D/PMS     (  968): releaseWL(785eab0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
W/ContextImpl(  968): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2712 
,D/SmartDim(  968): Init customizeScreenOffDelayClass error
,D/GpsLocationProvider(  968): receive broadcast intent, action: android.intent.action.SCREEN_OFF
,D/DotMatrix( 1324): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1324): [EventService] getTotalRam: 1842 Mb
I/BatteryController( 1215): status:5 level:100 unsupport:false plugged:true
,I/IntentController( 1215): receive(android.intent.action.SCREEN_OFF,1,false)
,D/ContactMessageStore( 1546): start background delete task...
,I/ClockController( 1215): stop clock update:screen off
,W/ContextImpl( 6928): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 ,
,D/ContactMessageStore( 1546): size: 0 , 0
D/ContactMessageStore( 1546): Background delete complete
,D/PMS     (  968): acquireWL(1c5738ae): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1834 10024 WorkSource{10024 com.google.android.gms},
D/PMS     (  968): releaseWL(1c5738ae): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  968): acquireWL(28fc564f): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1834 10024 WorkSource{10024 com.google.android.gms}
,W/ContextImpl( 6928): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:22 android.app.ActivityThread.handleReceiver:2712 
,D/PMS     (  968): releaseWL(28fc564f): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,D/SmartSyncUtils( 6928): isEpsOn(), nState = 0
,D/SmartSyncUtils( 6928): isEpsOn(), nState = 0
,W/ContextImpl( 6928): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:73 android.app.ActivityThread.handleReceiver:2712 
,W/ContextImpl(  968): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1830 android.content.ContextWrapper.stopService:520 android.content.ContextWrapper.stopService:520 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2712 ,
,I/SensorManager(  968): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@3a67fdcc
W/SensorService(  968): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  968): disable: get sensor name = Accelerometer Sensor
,W/SensorService(  968): pid=968, uid=1000
,W/SensorService(  968): Active sensors: size = 3
W/SensorService(  968): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  968): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  968): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
W/SensorService(  968): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@3a67fdcc, eanble = 0, strlen(mName) = 36
W/SensorService(  968): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  968): Listener[0] = com.htc.sense.easyaccessservice.SensorHubService@1082bde3
W/SensorService(  968): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  968): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  968): disable: get sensor name = CM36686 Proximity sensor
,I/RemoteViews( 1215): setHTCTheme(com.htc.updater,true,33751145),
,D/AutoSetting( 1626): service - mHandler: cancel location update
,D/AutoSetting( 1626): service -           changes count: 0
W/SensorService(  968): pid=968, uid=1000
W/SensorService(  968): Active sensors: size = 2
W/SensorService(  968): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  968): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
W/SensorService(  968): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@3a67fdcc, eanble = 0, strlen(mName) = 36
W/SensorService(  968): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  968): Listener[0] = com.htc.sense.easyaccessservice.SensorHubService@1082bde3
W/SensorService(  968): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  968): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@3a67fdcc
E/ActivityThread(  968): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@25636815 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  968): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@25636815 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  968): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:1003)
E/ActivityThread(  968): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:767)
E/ActivityThread(  968): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1775)
E/ActivityThread(  968): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1755)
E/ActivityThread(  968): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:495)
E/ActivityThread(  968): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  968): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  968): 	at android.app.Service.onStartCommand(Service.java:458)
E/ActivityThread(  968): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3072)
E/ActivityThread(  968): 	at android.app.ActivityThread.access$2100(ActivityThread.java:144)
E/ActivityThread(  968): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1470)
E/ActivityThread(  968): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  968): 	at android.os.Looper.loop(Looper.java:155)
E/ActivityThread(  968): 	at com.android.server.SystemServer.run(SystemServer.java:324)
,E/ActivityThread(  968): 	at com.android.server.SystemServer.main(SystemServer.java:225)
E/ActivityThread(  968): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread(  968): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread(  968): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/ActivityThread(  968): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,I/RemoteViews( 1215): apply : com.htc.updater 1 14 1 36
,D/SmartSyncUtils( 6928): getMobilePolicyEnabled, result = true
,E/WifiTrafficPoller(  968): ADD_CLIENT: 9,
D/WifiService(  968): New client listening to asynchronous messages,
,I/PowerUsageList:PowerUsageHelper( 6928): PowerProfile::POWER_SCREEN_FULL = 154.8
,D/PowerUsageList:BatterySipperExt( 6928): gen(), null == sipper.uidObj, userId = 0
,D/PowerUsageList:PowerUsageHelper( 6928): MY_DEBUG = false,
,D/Process (  968): killProcessQuiet, pid=6679
I/ActivityManager(  968): Killing 6679:com.htc.calendar/u0a10 (adj 15): empty #17
,D/Process (  968): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,E/WifiTrafficPoller(  968): TRAFFIC_STATS_POLL false Token 27 num clients 9,
,I/ActivityManager(  968): Recipient 6679,
,E/WifiStateMachine(  968): handleMessage: E msg.what=131155,
E/WifiStateMachine(  968): processMsg: ConnectedState
,E/WifiStateMachine(  968):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2578] from screen [on:0 period:-1459811044] gl hn u24 rssi=-53 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0,
E/WifiStateMachine(  968): processMsg: L2ConnectedState
E/WifiStateMachine(  968):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1459811042] gl hn u24 rssi=-53 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  968): handleMessage: X
,D/PMS     (  968): releaseWL(f609e5c): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 null,
,I/jxcore-log( 6509): Test app app.js loaded,
I/jxcore-log( 6509): 
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6509): load: ,
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6509): 	Automate Bluetooth MAC address resolution: true, ,
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6509): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6509): 	Bluetooth MAC address: null, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6509): 	Discovery mode: BLE, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6509): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6509): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6509): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6509): 	,Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6509): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@79940f7 added. We now have 1 listener(s)
D/BluetoothAdapter( 6509): 437092556: getState(). Returning 12
I/jxcore-log( 6509): BLE advertisement is supported
I/jxcore-log( 6509): 
,I/chromium( 6509): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,E/WifiStateMachine(  968): handleMessage: E msg.what=131155,
E/WifiStateMachine(  968): processMsg: ConnectedState
,E/WifiStateMachine(  968):  ConnectedState CMD_RSSI_POLL 3 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1722] from screen [on:0 period:-1459809319] gl hn u24 rssi=-53 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  968): processMsg: L2ConnectedState
E/WifiStateMachine(  968):  L2ConnectedState CMD_RSSI_POLL 3 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1459809316] gl hn u24 rssi=-53 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  968): handleMessage: X
,E/WifiDataStallTracker(  968): DATA_MONITOR_POLL false Token 5,
,D/HtcUPManager( 1215): HtcUPServiceProxy onTrimMemory() has been called. Memory Level: 60,
,E/WifiDataStallTracker(  968): DATA_MONITOR_POLL false Token 5,
,D/ContactMessageStore( 1546): MSG_NOTIFY_CS_TO_SYNC >>,
D/ContactMessageStore( 1546): MSG_NOTIFY_CS_TO_SYNC <<
,W/Atfwd_Sendcmd(  466): AtCmdFwd service not published, waiting... retryCnt : 1,
,W/Atfwd_Sendcmd(  466): AtCmdFwd service not published, waiting... retryCnt : 2
,I/ActivityManager(  968): Killing 5558:com.htc.musicenhancer/u0a49 (adj 15): empty #17,
D/Process (  968): killProcessQuiet, pid=5558
D/Process (  968): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  968): Recipient 5558,
,D/PMS     (  968): acquireWL(156231ba): PARTIAL_WAKE_LOCK  *alarm* 0x1 968 1000 WorkSource{10024},
,V/AlarmManager(  968): sending alarm PendingIntent{35d2086b: PendingIntentRecord{16c05fc8 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=142079, Int=0
,D/PMS     (  968): releaseWL(156231ba): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10024}
,D/AutoSetting( 1626): service - handleMessage() stop self,
,D/AutoSetting( 1626): service - handleMessage() quit looper
,D/AutoSetting( 1626): service - onDestroy() END
,W/Atfwd_Sendcmd(  466): AtCmdFwd service not published, waiting... retryCnt : 3,
,E/WifiStateMachine(  968): handleMessage: E msg.what=131165,
,E/WifiStateMachine(  968): processMsg: ConnectedState,
E/WifiStateMachine(  968):  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  968): processMsg: L2ConnectedState
E/WifiStateMachine(  968):  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,E/WifiStateMachine(  968): processMsg: ConnectModeState
E/WifiStateMachine(  968):  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  968): processMsg: DriverStartedState
E/WifiStateMachine(  968):  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  968): processMsg: SupplicantStartedState
E/WifiStateMachine(  968):  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,E/WifiStateMachine(  968): processMsg: DefaultState
E/WifiStateMachine(  968):  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  968): handleMessage: X
,D/GpsLocationProvider(  968): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  968): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  968): acquireWL(29c7e861): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 968 1000 null
,D/libc    (  968): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 4
,D/libc    (  968): [NET] android_getaddrinfofornet-, err=8
D/libc    (  968): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024
D/libc    (  968): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  968): [NET] android_getaddrinfo_proxy+
D/libc    (  968): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024
,D/libc    (  394): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,D/libc    (  394): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  394): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  968): [NET] android_getaddrinfo_proxy-, success
D/libc    (  968): [NET] android_getaddrinfofornet+,hn 14(0x35342e3233392e),sn(),hints(known),family 0,flags 4,
D/libc    (  968): [NET] android_getaddrinfofornet-, SUCCESS
,D/GpsLocationProvider(  968): [handleDownloadXtraData] calling native_inject_xtra_data,
,D/GpsLocationProvider(  968): [reportHTCStatus] eventMask = 3 , status = 0,
D/GpsLocationProvider(  968): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
D/GpsLocationProvider(  968):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  968): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
D/PMS     (  968): acquireWL(2939a99d): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 968 1000 null
D/PMS     (  968): releaseWL(29c7e861): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 null
D/PMS     (  968): releaseWL(2939a99d): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/ContextImpl(  968): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 
,W/Atfwd_Sendcmd(  466): AtCmdFwd service not published, waiting... retryCnt : 4,
,E/WifiStateMachine(  968): handleMessage: E msg.what=131326,
E/WifiStateMachine(  968): processMsg: ConnectedState
E/WifiStateMachine(  968):  ConnectedState what:131326 2 0
E/WifiStateMachine(  968): processMsg: L2ConnectedState
,E/WifiStateMachine(  968):  L2ConnectedState what:131326 2 0
E/WifiStateMachine(  968): handleMessage: X
,D/PMS     (  968): acquireWL(2ba93e12): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 968 1000 null,
I/BatteryService(  968): n_update end,
,D/PMS     (  968): releaseWL(2ba93e12): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  968): BroadcastReceiver::onReceive+
D/DotMatrix( 1324): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  968): updateBatteryInfo
D/DotMatrix( 1324): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1215): closing low battery warning: level=100
D/DotMatrix( 1324): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/NotificationService(  968): plugged=true pluggin=true
I/IntentController( 1215): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  968): runPSCheck
D/UsbnetService(  968): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  968): Checking...
D/UsbnetService(  968):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/HtcPowerSaver(  968): >> updateStatus
D/UsbnetService(  968): BroadcastReceiver::onReceive-
D/WifiController(  968): battery changed pluggedType: 2
D/WifiController(  968): handleMessage: E msg.what=155652
D/PowerUI ( 1215): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/WifiController(  968): processMsg: DeviceActiveState
D/WifiController(  968): processMsg: StaEnabledState
D/WifiController(  968): processMsg: DefaultState
D/WifiController(  968): handleMessage: X
D/HeadsetStateMachine( 3121): Disconnected process message: 10, size: 0
,I/HtcPowerSaver(  968): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  968): << updateStatus
,I/BatteryController( 1215): status:5 level:100 unsupport:false plugged:true
,D/TelephonyReceiver( 1546): switchBindHtcMsgCursor: null,
,W/Atfwd_Sendcmd(  466): AtCmdFwd service not published, waiting... retryCnt : 5,
,D/PMS     (  968): acquireWL(3be519e3): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 968 1000 null
,I/BatteryService(  968): n_update end,
D/UsbnetService(  968): BroadcastReceiver::onReceive+
D/PMS     (  968): releaseWL(3be519e3): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  968): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  968): updateBatteryInfo
,D/UsbnetService(  968):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PowerUI ( 1215): closing low battery warning: level=100
D/UsbnetService(  968): BroadcastReceiver::onReceive-
D/NotificationService(  968): plugged=true pluggin=true
,D/HeadsetStateMachine( 3121): Disconnected process message: 10, size: 0
D/PMS     (  968): runPSCheck
I/IntentController( 1215): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  968): Checking...
D/WifiController(  968): handleMessage: E msg.what=155652
I/HtcPowerSaver(  968): >> updateStatus
D/WifiController(  968): processMsg: DeviceActiveState
D/WifiController(  968): battery changed pluggedType: 2
D/WifiController(  968): processMsg: StaEnabledState
D/PowerUI ( 1215): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  968): processMsg: DefaultState
I/HtcPowerSaver(  968): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  968): handleMessage: X
I/HtcPowerSaver(  968): << updateStatus
D/DotMatrix( 1324): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1324): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1324): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/BatteryController( 1215): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  968): acquireWL(37015fe0): PARTIAL_WAKE_LOCK  *alarm* 0x1 968 1000 WorkSource{1000},
D/PMS     (  968): acquireWL(1e0c4299): PARTIAL_WAKE_LOCK  *backup* 0x1 968 1000 null
V/AlarmManager(  968): sending alarm PendingIntent{22d9295e: PendingIntentRecord{1dc5713f android broadcastIntent}}, i=android.app.backup.intent.INIT, t=0, cnt=1, w=1454534156050, Int=0
V/AlarmManager(  968): sending alarm PendingIntent{191f7091: PendingIntentRecord{27d54bf6 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=170500, Int=0
V/AlarmManager(  968): sending alarm PendingIntent{2b4c9a0c: PendingIntentRecord{37d56f55 android broadcastIntent}}, i=com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE, t=2, cnt=1, w=201704, Int=0
V/AlarmManager(  968): sending alarm PendingIntent{3e8a7d6a: PendingIntentRecord{3d29e25b com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=189588, Int=0
,D/PMS     (  968): acquireWL(3b2f4af8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1873 10024 WorkSource{10024 com.google.android.gms},
,W/BackupManagerService(  968): Requested unavailable transport: com.google.android.gms.backup.BackupTransportService
,E/BackupManagerService(  968): Requested init for com.google.android.gms.backup.BackupTransportService but not found
D/PMS     (  968): releaseWL(1e0c4299): PARTIAL_WAKE_LOCK  *backup* 0x1 null
,D/PMS     (  968): releaseWL(37015fe0): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,D/WeatherUtility( 1215): Weather sync is On
,W/WeatherTimeKeeper( 1215): [refreshWeatherData] no weather data
,D/PMS     (  968): acquireWL(fcaabd1): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1873 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  968): releaseWL(3b2f4af8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,V/GLSActivity( 1873): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/PMS     (  968): releaseWL(fcaabd1): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  968): acquireWL(294041d3): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1873 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  968): releaseWL(294041d3): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  968): acquireWL(209c8110): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1873 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  968): releaseWL(209c8110): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  968): acquireWL(34560409): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1873 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  968): acquireWL(25d0a60e): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1873 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  968): acquireWL(b309e3c): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1873 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  968): releaseWL(34560409): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,I/VacuumService( 1873): Vacuum at: now=1454534191492 tag=VacuumService
,D/PMS     (  968): releaseWL(25d0a60e): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  968): acquireWL(3f5151a): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1873 10024 WorkSource{10024 com.google.android.gms},
,I/GoogleURLConnFactory( 1873): Using platform SSLCertificateSocketFactory
,W/Uploader( 1873): No account for auth token provided
,D/PMS     (  968): releaseWL(3f5151a): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  968): acquireWL(7e4184b): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1873 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  968): releaseWL(7e4184b): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/libc    ( 1873): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
,D/libc    ( 1873): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 1873): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
,D/libc    ( 1873): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1873): [NET] android_getaddrinfo_proxy+
D/libc    ( 1873): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,D/libc    (  394): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  394): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 1873): [NET] android_getaddrinfo_proxy-, success
,D/libc    ( 1873): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4,
D/libc    ( 1873): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 1873): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4,
D/libc    ( 1873): [NET] android_getaddrinfofornet-, err=8
,W/Uploader( 1873): No account for auth token provided,
,W/Uploader( 1873): No account for auth token provided,
,W/Uploader( 1873):  no longer exists, so no auth token.,
,W/Uploader( 1873): No account for auth token provided,
,I/art     (  968): Explicit concurrent mark sweep GC freed 47994(2MB) AllocSpace objects, 4(1040KB) LOS objects, 33% free, 19MB/28MB, paused 2.045ms total 213.500ms
,I/GLSUser ( 1873): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1873): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1873): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1873): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1873): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/DotMatrix( 1324): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true,
D/DotMatrix( 1324): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1215): reapply : com.google.android.gms 3 40,
,E/Uploader( 1873): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1873): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1873): 	,at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1873): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1873): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1873): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1873): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1873): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1873): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263),
E/Uploader( 1873): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1873): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1873): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1873): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,D/PMS     (  968): releaseWL(b309e3c): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
D/PMS     (  968): acquireWL(1fd47b1f): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1873 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  968): releaseWL(1fd47b1f): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  968): acquireWL(23f60e6c): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1873 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  968): releaseWL(23f60e6c): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/HtcUPManager( 1215): HtcUPServiceProxy Disconnect from  UP serivce: No interaction with app
,D/HtcUPManager( 1215): HtcUPServiceProxy Disconnect from UP service. Change state to: DISCONNECTED
,D/HtcAppUPService( 1626): HtcUPService [##] onDestroy(), this =com.htc.sense.hsp.upservice.HtcUPService@41e0278
I/ActivityManager(  968): Killing 5951:com.android.settings/1000 (adj 15): empty #17
,D/Process (  968): killProcessQuiet, pid=5951
D/Process (  968): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  968): Recipient 5951
,D/WifiService(  968): Client connection lost with reason: 4
,W/Atfwd_Sendcmd(  466): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  466): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  968): acquireWL(1bb13c35): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 968 1000 null,
D/DotMatrix( 1324): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/BatteryService(  968): n_update end
D/DotMatrix( 1324): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  968): releaseWL(1bb13c35): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1324): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1215): closing low battery warning: level=100
I/IntentController( 1215): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/NotificationService(  968): plugged=true pluggin=true
D/HeadsetStateMachine( 3121): Disconnected process message: 10, size: 0
D/HtcPowerSaver(  968): updateBatteryInfo
D/UsbnetService(  968): BroadcastReceiver::onReceive+
D/WifiController(  968): battery changed pluggedType: 2
D/UsbnetService(  968): onReceive BATTERY_CHANGED
D/PowerUI ( 1215): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  968):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  968): runPSCheck
D/UsbnetService(  968): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  968): Checking...
,D/WifiController(  968): handleMessage: E msg.what=155652
I/HtcPowerSaver(  968): >> updateStatus
D/WifiController(  968): processMsg: DeviceActiveState
D/WifiController(  968): processMsg: StaEnabledState
D/WifiController(  968): processMsg: DefaultState
D/WifiController(  968): handleMessage: X
,I/HtcPowerSaver(  968): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  968): << updateStatus
,I/BatteryController( 1215): status:5 level:100 unsupport:false plugged:true,
,W/Atfwd_Sendcmd(  466): AtCmdFwd service not published, waiting... retryCnt : 3,
,I/jxcore-log( 6509): --= Surplus to requirements =--,
I/jxcore-log( 6509): 
I/jxcore-log( 6509): ****TEST TOOK:  ms ****,
I/jxcore-log( 6509): 
,I/jxcore-log( 6509): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6509): 
,E/cutils-trace( 6980): Error opening trace file: Permission denied (13)
,D/CustomizationManager( 6980): ====startRecUseTime====,
D/htc.customization.log.level( 6980):  is 
W/CustomizationLogLevel( 6980): Level value is invalid, use default level 2
,D/CustomizationManager( 6980):  Read ACC file spent 0.049 (s),
,D/CIDMapFileReader( 6980): Parsing tag item name = HTC__001
,D/CIDMapFileReader( 6980): Parsing tag item name = HTC__102
D/CIDMapFileReader( 6980): Parsing tag item name = HTC__Y13
,D/CIDMapFileReader( 6980): Parsing tag item name = HTC__032
D/CIDMapFileReader( 6980): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 6980): Parsing tag item name = HTC__002
D/CIDMapFileReader( 6980): Parsing tag item name = HTC__031
,V/CustomizationCIDLoader( 6980): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 6980): Parsing tag category name = system
,I/CustomizationCIDLoader( 6980): Parsing tag category name = application
,I/CustomizationCIDLoader( 6980): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 6980): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 6980): Parsing tag category name = AudioService,
I/CustomizationCIDLoader( 6980): Parsing tag category name = Settings
I/CustomizationCIDLoader( 6980): Parsing tag category name = ACC
I/CustomizationCIDLoader( 6980): add string-array item, value = 42507
,I/CustomizationCIDLoader( 6980): add string-array item, value = 21902
I/CustomizationCIDLoader( 6980): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 6980): add string-array item, value = 23420
I/CustomizationCIDLoader( 6980): add string-array item, value = 22299
I/CustomizationCIDLoader( 6980): add string-array item, value = 24002
I/CustomizationCIDLoader( 6980): add string-array item, value = 23210
I/CustomizationCIDLoader( 6980): add string-array item, value = 23205
I/CustomizationCIDLoader( 6980): add string-array item, value = 23806
I/CustomizationCIDLoader( 6980): add string-array item, value = 23430
I/CustomizationCIDLoader( 6980): add string-array item, value = 23408
I/CustomizationCIDLoader( 6980): add string-array item, value = 27205
I/CustomizationCIDLoader( 6980): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 6980): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 6980): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 6980): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 6980): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 6980): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 6980): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 6980): add string-array item, value = 23205:D:0:0,
I/CustomizationCIDLoader( 6980): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 6980): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 6980): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 6980): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 6980):  Read CID file spent 0.098 (s)
D/CustomizationManager( 6980):  All configurations done spent 0.099 (s)
,D/PackageManager(  968): deletePackageAsUser: pkg=com.test.thalitest, pid=6980, uid=2000 userid=0,
,I/ActivityManager(  968): Force stopping com.test.thalitest appid=10366 user=-1: uninstall pkg
,I/ActivityManager(  968): Killing 6509:com.test.thalitest/u0a366 (adj 0): stop com.test.thalitest
D/Process (  968): killProcessQuiet, pid=6509
,D/Process (  968): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.removeProcessLocked:6363 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:6161 
,W/PackageSettings(  968): Skipping PackageSetting{34c28c01 com.example.hello/10374} due to missing metadata,
,I/ActivityManager(  968): Recipient 6509,
E/InputEventReceiver( 1395): Looper::removeFd(68) is failed, result(0), input channel 'ClientState{1958a7a7 uid 10366 pid 6509} (c)'
I/WindowState(  968): WIN DEATH: Window{8071866 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService(  968): Client connection lost with reason: 4
,E/libprocessgroup(  968): failed to kill 1 processes for processgroup 6509
,I/ActivityManager(  968):   Force finishing activity ActivityRecord{25a67fe2 u0 com.test.thalitest/.MainActivity t8}
,I/ActivityManager(  968): Force stopping com.test.thalitest appid=10366 user=0: pkg removed,
,I/ActivityManager(  968):   Force finishing activity ActivityRecord{25a67fe2 u0 com.test.thalitest/.MainActivity t8 f},
W/ActivityManager(  968): Duplicate finish request for ActivityRecord{25a67fe2 u0 com.test.thalitest/.MainActivity t8 f}
,W/ActivityManager(  968): Spurious death for ProcessRecord{10ccf8ca 6509:com.test.thalitest/u0a366}, curProc for 6509: null,
,D/DotMatrix( 1324): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
,D/PMS     (  968): acquireWL(114faa3b): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1834 10024 WorkSource{10024 com.google.android.gms}
D/DotMatrix( 1324): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/PMS     (  968): releaseWL(114faa3b): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
D/DotMatrix( 1324): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix,
W/GeofencerStateMachine( 1834): Ignoring removeGeofence because network location is disabled.
D/AccTypeManager( 1769): Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
,W/SystemReader(  968): Cannot find grip_rejection_width, use default value instead,
I/art     ( 5889): Explicit concurrent mark sweep GC freed 28040(1748KB) AllocSpace objects, 0(0B) LOS objects, 44% free, 2MB/4MB, paused 411us total 44.748ms
,D/AccTypeManager( 1769): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana,
,I/art     ( 1590): Explicit concurrent mark sweep GC freed 23690(1413KB) AllocSpace objects, 7(492KB) LOS objects, 34% free, 29MB/45MB, paused 903us total 67.402ms,
,I/Prism.ItemManager( 1590): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1590): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,D/PhoneApp( 1546): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED,
,D/AccTypeManager( 1769): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,D/VoicemailCleanupService( 1703): Cleaning up data for package: com.test.thalitest
,I/[PluginManager]RegisterService( 1626): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
,I/Launcher( 1590): Deferring update until onResume,
D/Launcher( 1590): waitUntilResume // bindAppsRemoved
D/Prism.PackageStateRece_( 1590): action: android.intent.action.PACKAGE_REMOVED
,E/ExternalAccountType( 1769): Unsupported attribute readOnly
,I/[PluginManager]RegisterService( 1626): handle notify Blinkfeed plugin client changed
,I/ActivityManager(  968): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=7000 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a,
,I/InputMethodManagerService(  968): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
,W/PackageManager(  968): Unable to load service info ResolveInfo{492b059 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000},
W/PackageManager(  968): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  968): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:475)
W/PackageManager(  968): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:331)
W/PackageManager(  968): 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
W/PackageManager(  968): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  968): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
W/PackageManager(  968): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
W/PackageManager(  968): 	at android.os.Handler.handleCallback(Handler.java:739),
W/PackageManager(  968): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  968): 	at android.os.Looper.loop(Looper.java:155)
W/PackageManager(  968): 	at com.android.server.SystemServer.run(SystemServer.java:324)
W/PackageManager(  968): 	at com.android.server.SystemServer.main(SystemServer.java:225)
W/PackageManager(  968): 	at java.lang.reflect.Method.invoke(Native Method)
W/PackageManager(  968): 	,at java.lang.reflect.Method.invoke(Method.java:372)
W/PackageManager(  968): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
W/PackageManager(  968): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,I/art     (  968): Explicit concurrent mark sweep GC freed 17212(1353KB) AllocSpace objects, 3(124KB) LOS objects, 33% free, 19MB/28MB, paused 1.780ms total 204.035ms
,W/asset   (  968): Copying FileAsset 0x55672e86b0 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
,D/StatusBarManagerService(  968): setSystemUiVisibility(0x700)
D/StatusBarManagerService(  968): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService(  968): hiding MENU key
,D/StatusBarManagerService(  968): setSystemUiVisibility(0xc0000700)
,D/StatusBarManagerService(  968): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  968): hiding MENU key
,D/FindExtension( 1590): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
,D/JobSchedulerService(  968): Receieved: android.intent.action.PACKAGE_REMOVED
D/TaskPersister(  968): removeObsoleteFile: deleting file=8_task.xml
D/TaskPersister(  968): removeObsoleteFile: deleting file=8_task_thumbnail.png
,W/ContextImpl( 7000): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2712 
,I/ThreadedRenderer( 1590): Defer allocateBuffers to drawing time
,W/ResourcesManager(  968): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,W/InputMethodManagerService(  968): Got RemoteException sending setActive(false) notification to pid 6509 uid 10366,
D/StatusBarManagerService(  968): swetImeWindowStatus vis=0 backDisposition=0
,I/PhoneStatusBar( 1215): setImeWindowStatus(false,false)
,I/ActivityManager(  968): Start proc com.android.settings for broadcast com.android.settings/.fpquicklaunch.HtcFingerPrintReceiver: pid=7024 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
I/ActivityManager(  968): Killing 5977:com.android.vending/u0a72 (adj 15): empty #17
D/Process (  968): killProcessQuiet, pid=5977
D/Process (  968): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,E/libprocessgroup(  968): failed to kill 1 processes for processgroup 5977
,I/ActivityManager(  968): Recipient 5977,
,D/Fingerprint/ HtcFingerPrintQuickLaunchProvider( 7024): -onCreate()
,V/Settings:HtcSettingsApplication( 7024): [7024/7024] onCreate(),
,I/ActivityManager(  968): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7048 uid=10072 gids={50072, 9997, 3003, 1028, 1015} abi=arm64-v8a,
I/ActivityManager(  968): Killing 5889:com.google.android.googlequicksearchbox:search/u0a85 (adj 15): empty #17
D/Process (  968): killProcessQuiet, pid=5889
D/Process (  968): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,D/Settings:HtcWirelessFeatureFlags( 7024): id/is att sku: 118/false,
,E/Settings:HtcWrapHeaderInfo( 7024): no such activity!
,I/ActivityManager(  968): Recipient 5889
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 7024): The wrap header doesn't exist in header list.
,E/Settings:HtcWrapHeaderInfo( 7024): updateDevelopment, bPrefShow = true
,E/Settings:HtcUmcWidgetEnabler( 7024): isSupportMusicChannel(): false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7024): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7024): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7024): [supportRecentAppsButton]support         :false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7024): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7024): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7024): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7024): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7024): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7024): [supportHomeButton]support         :false
,I/ActivityManager(  968): Cannot resolve ContentProvider=com.htc.vowifi
,E/ActivityThread( 7024): Failed to find provider info for com.htc.vowifi
E/Settings:HtcVoWifiWidgetEnabler( 7024): isSupportVoWifi: null
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 7024): The wrap header doesn't exist in header list.
,E/Settings:HtcWrapHeaderInfo( 7024): updateDevelopment, bPrefShow = true
,E/Settings:HtcUmcWidgetEnabler( 7024): isSupportMusicChannel(): false,
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7024): [supportRecentAppsButton]hasNavigationBar:true,
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7024): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7024): [supportRecentAppsButton]support         :false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7024): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7024): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7024): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7024): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7024): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 7024): [supportHomeButton]support         :false
,I/ActivityManager(  968): Cannot resolve ContentProvider=com.htc.vowifi,
E/Settings:HtcVoWifiWidgetEnabler( 7024): isSupportVoWifi: null
E/ActivityThread( 7024): Failed to find provider info for com.htc.vowifi
,I/PackageManager(  968):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=7048, uid=10072, userID:0,
,W/global  ( 7048): [apache-http] Connection GC has been deprecated!,
,D/Finsky  ( 7048): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/,
,W/global  ( 7048): [apache-http] Connection GC has been deprecated!,
,W/global  ( 7048): [apache-http] Connection GC has been deprecated!,
,E/RollingFileStream( 7048): Could not create a temp file with prefix: "eventlog.store" and suffix: ".log" in dir: "/data/data/com.android.vending/cache/logs/com.google.thalitester%40gmail.com".,
,D/Finsky  ( 7048): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.,
,I/ActivityManager(  968): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=7090 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a
,W/Settings( 7048): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.,
,W/Settings( 7048): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.,
,E/SQLiteDatabase( 7048): Failed to open database '/data/data/com.android.vending/databases/library.db'.,
E/SQLiteDatabase( 7048): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7048): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7048): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 7048): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 7048): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7048): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7048): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7048): 	,at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 7048): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 7048): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 7048): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 7048): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7048): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7048): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7048): 	at com.google.android.finsky.library.SQLiteLibrary.reopen(SQLiteLibrary.java:256)
E/SQLiteDatabase( 7048): 	at com.google.android.finsky.library.LibraryLoader.loadBlocking(LibraryLoader.java:66)
E/SQLiteDatabase( 7048): 	at com.google.android.finsky.library.LibraryLoader$1.run(LibraryLoader.java:57),
E/SQLiteDatabase( 7048): 	at android.os.Handler.handleCallback(Handler.java:739)
E/SQLiteDatabase( 7048): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 7048): 	at android.os.Looper.loop(Looper.java:155)
E/SQLiteDatabase( 7048): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/AndroidRuntime( 7048): FATAL EXCEPTION: libraries-thread
E/AndroidRuntime( 7048): Process: com.android.vending, PID: 7048
E/AndroidRuntime( 7048): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7048): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7048): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/AndroidRuntime( 7048): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/AndroidRuntime( 7048): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 7048): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 7048): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 7048): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/AndroidRuntime( 7048): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/AndroidRuntime( 7048): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/AndroidRuntime( 7048): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/AndroidRuntime( 7048): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AndroidRuntime( 7048): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 7048): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 7048): 	at com.google.android.finsky.library.SQLiteLibrary.reopen(SQLiteLibrary.java:256)
E/AndroidRuntime( 7048): 	at com.google.android.finsky.library.LibraryLoader.loadBlocking(LibraryLoader.java:66)
E/AndroidRuntime( 7048): 	at com.google.android.finsky.library.LibraryLoader$1.run(LibraryLoader.java:57)
E/AndroidRuntime( 7048): 	at android.os.Handler.handleCallback(Handler.java:739)
E/AndroidRuntime( 7048): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 7048): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidRuntime( 7048): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteDatabase( 7048): Failed to open database '/data/data/com.android.vending/databases/localappstate.db'.
E/SQLiteDatabase( 7048): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7048): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7048): ,	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 7048): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 7048): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7048): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7048): 	,at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7048): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 7048): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 7048): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 7048): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 7048): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
,E/SQLiteDatabase( 7048): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7048): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7048): 	at com.google.android.finsky.appstate.SQLiteInstallerDataStore.reopen(SQLiteInstallerDataStore.java:288)
E/SQLiteDatabase( 7048): 	at com.google.android.finsky.appstate.SQLiteInstallerDataStore.getAll(SQLiteInstallerDataStore.java:368)
E/SQLiteDatabase( 7048): 	at com.google.android.finsky.appstate.WriteThroughInstallerDataStore.load(WriteThroughInstallerDataStore.java:55)
E/SQLiteDatabase( 7048): 	at com.google.android.finsky.appstate.AppStates.blockingLoad(AppStates.java:82)
E/SQLiteDatabase( 7048): 	at com.google.android.finsky.receivers.InstallerImpl$1.doInBackground(InstallerImpl.java:177)
E/SQLiteDatabase( 7048): 	at com.google.android.finsky.receivers.InstallerImpl$1.doInBackground(InstallerImpl.java:164)
E/SQLiteDatabase( 7048): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 7048): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 7048): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 7048): 	,at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 7048): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 7048): 	at java.lang.Thread.run(Thread.java:818)
E/AndroidRuntime_2_crash( 7048): crash in the same process: AsyncTask #1
E/AndroidRuntime_2_crash( 7048): java.lang.RuntimeException: An error occured while executing doInBackground()
E/AndroidRuntime_2_crash( 7048): 	at android.os.AsyncTask$3.done(AsyncTask.java:300)
E/AndroidRuntime_2_crash( 7048): 	at java.util.concurrent.FutureTask.finishCompletion(FutureTask.java:355)
E/AndroidRuntime_2_crash( 7048): 	at java.util.concurrent.FutureTask.setException(FutureTask.java:222)
E/AndroidRuntime_2_crash( 7048): 	at java.util.concurrent.FutureTask.run(FutureTask.java:242)
E/AndroidRuntime_2_crash( 7048): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/AndroidRuntime_2_crash( 7048): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime_2_crash( 7048): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime_2_crash( 7048): 	at java.lang.Thread.run(Thread.java:818)
E/AndroidRuntime_2_crash( 7048): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime_2_crash( 7048): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime_2_crash( 7048): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/AndroidRuntime_2_crash( 7048): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/AndroidRuntime_2_crash( 7048): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime_2_crash( 7048): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime_2_crash( 7048): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime_2_crash( 7048): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/AndroidRuntime_2_crash( 7048): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/AndroidRuntime_2_crash( 7048): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/AndroidRuntime_2_crash( 7048): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/AndroidRuntime_2_crash( 7048): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AndroidRuntime_2_crash( 7048): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime_2_crash( 7048): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime_2_crash( 7048): 	at com.google.android.finsky.appstate.SQLiteInstallerDataStore.reopen(SQLiteInstallerDataStore.java:288)
E/AndroidRuntime_2_crash( 7048): 	at com.google.android.finsky.appstate.SQLiteInstallerDataStore.getAll(SQLiteInstallerDataStore.java:368)
E/AndroidRuntime_2_crash( 7048): 	at com.google.android.finsky.appstate.WriteThroughInstallerDataStore.load(WriteThroughInstallerDataStore.java:55)
E/AndroidRuntime_2_crash( 7048): 	at com.google.android.finsky.appstate.AppStates.blockingLoad(AppStates.java:82)
E/AndroidRuntime_2_crash( 7048): 	at com.google.android.finsky.receivers.InstallerImpl$1.doInBackground(InstallerImpl.java:177)
E/AndroidRuntime_2_crash( 7048): 	at com.google.android.finsky.receivers.InstallerImpl$1.doInBackground(InstallerImpl.java:164)
E/AndroidRuntime_2_crash( 7048): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/AndroidRuntime_2_crash( 7048): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/AndroidRuntime_2_crash( 7048): 	... 4 more
E/ActivityManager(  968): App crashed! Process: com.android.vending
I/PackageManager(  968):  setEnabledSetting(), pkgName=com.android.vending, clsName,=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=7048, uid=10072, userID:0
,E/SQLiteDatabase( 7048): Failed to open database '/data/data/com.android.vending/databases/localappstate.db'.
E/SQLiteDatabase( 7048): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7048): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7048): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 7048): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 7048): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7048): ,	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7048): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7048): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 7048): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 7048): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 7048): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 7048): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7048): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7048): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7048): 	at com.google.android.finsky.appstate.SQLiteInstallerDataStore.reopen(SQLiteInstallerDataStore.java:288)
E/SQLiteDatabase( 7048): 	at com.google.android.finsky.appstate.SQLiteInstallerDataStore.getAll(SQLiteInstallerDataStore.java:368)
E/SQLiteDatabase( 7048): 	at com.google.android.finsky.appstate.WriteThroughInstallerDataStore.load(WriteThroughInstallerDataStore.java:55)
E/SQLiteDatabase( 7048): 	at com.google.android.finsky.appstate.AppStates.blockingLoad(AppStates.java:82)
E/SQLiteDatabase( 7048): 	at com.google.android.finsky.appstate.MigrationAsyncTask.doInBackground(MigrationAsyncTask.java:61),
E/SQLiteDatabase( 7048): 	at com.google.android.finsky.appstate.MigrationAsyncTask.doInBackground(MigrationAsyncTask.java:33)
E/SQLiteDatabase( 7048): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 7048): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 7048): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 7048): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 7048): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 7048): 	at java.lang.Thread.run(Thread.java:818)
,E/AndroidRuntime_3_crash( 7048): crash in the same process: AsyncTask #2
E/AndroidRuntime_3_crash( 7048): java.lang.RuntimeException: An error occured while executing doInBackground()
E/AndroidRuntime_3_crash( 7048): 	at android.os.AsyncTask$3.done(AsyncTask.java:300)
E/AndroidRuntime_3_crash( 7048): 	at java.util.concurrent.FutureTask.finishCompletion(FutureTask.java:355)
E/AndroidRuntime_3_crash( 7048): 	at java.util.concurrent.FutureTask.setException(FutureTask.java:222)
E/AndroidRuntime_3_crash( 7048): 	at java.util.concurrent.FutureTask.run(FutureTask.java:242)
E/AndroidRuntime_3_crash( 7048): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/AndroidRuntime_3_crash( 7048): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime_3_crash( 7048): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime_3_crash( 7048): 	at java.lang.Thread.run(Thread.java:818)
E/AndroidRuntime_3_crash( 7048): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime_3_crash( 7048): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime_3_crash( 7048): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/AndroidRuntime_3_crash( 7048): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/AndroidRuntime_3_crash( 7048): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime_3_crash( 7048): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime_3_crash( 7048): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime_3_crash( 7048): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/AndroidRuntime_3_crash( 7048): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
,E/AndroidRuntime_3_crash( 7048): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/AndroidRuntime_3_crash( 7048): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/AndroidRuntime_3_crash( 7048): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AndroidRuntime_3_crash( 7048): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime_3_crash( 7048): ,	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime_3_crash( 7048): 	at com.google.android.finsky.appstate.SQLiteInstallerDataStore.reopen(SQLiteInstallerDataStore.java:288)
E/AndroidRuntime_3_crash( 7048): 	at com.google.android.finsky.appstate.SQLiteInstallerDataStore.getAll(SQLiteInstallerDataStore.java:368)
E/AndroidRuntime_3_crash( 7048): 	at com.google.android.finsky.appstate.WriteThroughInstallerDataStore.load(WriteThroughInstallerDataStore.java:55)
E/AndroidRuntime_3_crash( 7048): 	at com.google.android.finsky.appstate.AppStates.blockingLoad(AppStates.java:82)
E/AndroidRuntime_3_crash( 7048): 	at com.google.android.finsky.appstate.MigrationAsyncTask.doInBackground(MigrationAsyncTask.java:61)
E/AndroidRuntime_3_crash( 7048): 	at com.google.android.finsky.appstate.MigrationAsyncTask.doInBackground(MigrationAsyncTask.java:33)
E/AndroidRuntime_3_crash( 7048): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/AndroidRuntime_3_crash( 7048): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/AndroidRuntime_3_crash( 7048): 	... 4 more
E/DropBoxManagerService(  968): Can't write: system_app_crash
E/DropBoxManagerService(  968): java.io.FileNotFoundException: /data/system/dropbox/drop145.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  968): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  968): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  968): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  968): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
E/DropBoxManagerService(  968): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  968): 	at com.android.server.am.ActivityManagerService$21.run(ActivityManagerService.java:12658)
E/DropBoxManagerService(  968): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  968): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  968): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  968): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  968): 	... 5 more
,D/Process ( 7048): killProcess, pid=7048
,W/ResourcesManager( 7090): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7090): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/Process ( 7048): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 com.google.android.finsky.FinskyApp$CrashHandler.uncaughtException:316 java.lang.ThreadGroup.uncaughtException:693 ,
,I/MultiDex( 7090): VM with version 2.1.0 has multidex support,
I/MultiDex( 7090): install
,I/MultiDex( 7090): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 7090): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...,
,W/ActivityThread( 7090): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());,
,W/System  ( 7090): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3068deb: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl,
I/ProviderInstaller( 7090): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  968): Recipient 7048
,I/ActivityManager(  968): Process com.android.vending (pid 7048) has died,
,W/NativeLibraryUtils( 7090): Failed to open lock file,
W/NativeLibraryUtils( 7090): java.io.FileNotFoundException: /data/data/com.google.android.gms/cache/.lib.lock: open failed: EROFS (Read-only file system)
W/NativeLibraryUtils( 7090): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/NativeLibraryUtils( 7090): 	at java.io.RandomAccessFile.<init>(RandomAccessFile.java:117)
W/NativeLibraryUtils( 7090): 	at com.google.android.gms.common.util.ax.a(SourceFile:305)
W/NativeLibraryUtils( 7090): 	at com.google.android.gms.common.app.a.run(SourceFile:136)
W/NativeLibraryUtils( 7090): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
W/NativeLibraryUtils( 7090): 	at libcore.io.Posix.open(Native Method)
W/NativeLibraryUtils( 7090): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/NativeLibraryUtils( 7090): 	at libcore.io.IoBridge.open(IoBridge.java:442),
W/NativeLibraryUtils( 7090): 	... 3 more
E/SQLiteLog( 1873): (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
E/SQLiteDBG( 1873): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.google.android.gms/databases/gcm_registrar.db, handle: 0x5566dbfd50
,E/AndroidRuntime( 1873): FATAL EXCEPTION: main,
E/AndroidRuntime( 1873): Process: com.google.process.gapps, PID: 1873
E/AndroidRuntime( 1873): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1873): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2726)
E/AndroidRuntime( 1873): 	at android.app.ActivityThread.access$1700(ActivityThread.java:144)
E/AndroidRuntime( 1873): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1449)
E/AndroidRuntime( 1873): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1873): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidRuntime( 1873): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
E/AndroidRuntime( 1873): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 1873): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 1873): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/AndroidRuntime( 1873): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
E/AndroidRuntime( 1873): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1873): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1873): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:762)
E/AndroidRuntime( 1873): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1873): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1873): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1577)
E/AndroidRuntime( 1873): 	at com.google.android.gms.gcm.bh.a(SourceFile:310)
E/AndroidRuntime( 1873): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:127)
E/AndroidRuntime( 1873): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:321)
E/AndroidRuntime( 1873): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2712)
E/AndroidRuntime( 1873): 	... 9 more
,E/ActivityManager(  968): App crashed! Process: com.google.process.gapps
D/Process ( 1873): killProcess, pid=1873
D/Process ( 1873): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 com.google.android.gms.common.app.d.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
,E/DropBoxManagerService(  968): Can't write: system_app_crash
E/DropBoxManagerService(  968): java.io.FileNotFoundException: /data/system/dropbox/drop146.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  968): 	,at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  968): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  968): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  968): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
E/DropBoxManagerService(  968): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  968): 	at com.android.server.am.ActivityManagerService$21.run(ActivityManagerService.java:12658)
E/DropBoxManagerService(  968): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  968): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  968): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  968): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  968): 	... 5 more
,I/Prism.ItemManager( 1590): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1590): loadItems() com.htc.launcher.pageview.WidgetManager@4cd2221 +
I/Prism.WidgetManager( 1590): onLoadItems() +
,I/ActivityManager(  968): Recipient 1873,
,I/ActivityThread( 7090): Removing dead content provider:android.content.ContentProviderProxy@27a1a9e1
I/ActivityManager(  968): Process com.google.process.gapps (pid 1873) has died
W/ActivityManager(  968): Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 1000ms
W/ActivityManager(  968): Scheduling restart of crashed service com.google.android.gms/.gcm.http.GoogleHttpService in 11000ms
W/ActivityManager(  968): Scheduling restart of crashed service com.google.android.gms/.playlog.service.PlayLogBrokerService in 21000ms
W/ActivityManager(  968): Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 30999ms
,I/ActivityManager(  968): Start proc com.google.process.gapps for service com.google.android.gms/.gcm.http.GoogleHttpService: pid=7123 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a,
,W/ResourcesManager( 1590): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.,
,W/ResourcesManager( 7123): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
W/ResourcesManager( 7123): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 7123): VM with version 2.1.0 has multidex support,
I/MultiDex( 7123): install
I/MultiDex( 7123): VM has multidex support, MultiDex support library is disabled.
,I/GservicesProvider( 7123): Gservices pushing to system: true; secure/global: true,
,E/SQLiteDatabase( 7123): Failed to open database '/data/data/com.google.android.gsf/databases/gservices.db'.,
E/SQLiteDatabase( 7123): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7123): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7123): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 7123): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 7123): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7123): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7123): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7123): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 7123): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 7123): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 7123): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 7123): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7123): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7123): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
E/SQLiteDatabase( 7123): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
E/SQLiteDatabase( 7123): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1702)
E/SQLiteDatabase( 7123): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1665)
E/SQLiteDatabase( 7123): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5421)
E/SQLiteDatabase( 7123): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4992)
E/SQLiteDatabase( 7123): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4927)
E/SQLiteDatabase( 7123): 	at android.app.ActivityThread.access$1500(ActivityThread.java:144)
E/SQLiteDatabase( 7123): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1424)
E/SQLiteDatabase( 7123): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7123): 	at android.os.Looper.loop(Looper.java:155)
E/SQLiteDatabase( 7123): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
E/SQLiteDatabase( 7123): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 7123): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 7123): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/SQLiteDatabase( 7123): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
E/AndroidRuntime( 7123): FATAL EXCEPTION: main
E/AndroidRuntime( 7123): Process: com.google.process.gapps, PID: 7123
E/AndroidRuntime( 7123): java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7123): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5424)
E/AndroidRuntime( 7123): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4992)
E/AndroidRuntime( 7123): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4927)
E/AndroidRuntime( 7123): 	at android.app.ActivityThread.access$1500(ActivityThread.java:144)
E/AndroidRuntime( 7123): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1424)
E/AndroidRuntime( 7123): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7123): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidRuntime( 7123): 	at android.app.ActivityThread.main(ActivityThread.java:,5721)
E/AndroidRuntime( 7123): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 7123): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 7123): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/AndroidRuntime( 7123): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
E/AndroidRuntime( 7123): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7123): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7123): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/AndroidRuntime( 7123): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/AndroidRuntime( 7123): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 7123): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 7123): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 7123): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/AndroidRuntime( 7123): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/AndroidRuntime( 7123): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/AndroidRuntime( 7123): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/AndroidRuntime( 7123): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 7123): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 7123): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
E/AndroidRuntime( 7123): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
E/AndroidRuntime( 7123): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1702)
E/AndroidRuntime( 7123): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1665)
E/AndroidRuntime( 7123): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5421)
E/AndroidRuntime( 7123): 	... 11 more
E/DropBoxManagerService(  968): Can't write: system_app_crash
E/DropBoxManagerService(  968): java.io.FileNotFoundException: /data/system/dropbox/drop147.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  968): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  968): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  968): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  968): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
E/DropBoxManagerService(  968): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  968): 	at com.android.server.am.ActivityManagerService$21.run(ActivityManagerService.java:12658)
E/DropBoxManagerService(  968): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  968): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  968): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  968): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  968): 	... 5 more
E/ActivityManager(  968): App crashed! Process: com.google.process.gapps
D/Process ( 7123): killProcess, pid=7123
D/Process ( 7123): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 com.google.android.gms.common.app.d.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 

```
