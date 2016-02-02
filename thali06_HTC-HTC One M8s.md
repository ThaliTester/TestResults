#### Test 57972094912017a_thali06_HTC-HTC One M8s Logs


```
--------- beginning of main
D/QSEECOMAPI: (  400): Loaded image: APP id = 9
D/DrmWidevineDash(  400): Service_Initialize: ends! returns 0
D/QSAPPSVER(  400): qsapps_get_capabilities: Capability from secure side: 0x0
D/QSAPPSVER(  400): qsapps_get_capabilities: returns 0
D/DrmWidevineDash(  400): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf489a000
E/DrmWidevineDash(  400): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf489a000
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/DrmLibTime(  496): got the req here! ret=0
D/DrmLibTime(  496): command id, time_cmd_id = 770
D/DrmLibTime(  496): time_getutcsec starts!
D/DrmLibTime(  496): QSEE Time Listener: time_getutcsec
D/DrmLibTime(  496): QSEE Time Listener: get_utc_seconds
D/DrmLibTime(  496): QSEE Time Listener: time_get_modem_time
D/DrmLibTime(  496): QSEE Time Listener: Checking if ATS_MODEM is set or not.
E/QC-time-services(  496): Receive Passed == base = 13, unit = 1, operation = 2, result = 0
D/DrmLibTime(  496): QSEE Time Listener: ATS_MODEM is not set. Fallback to Android system time.
D/DrmLibTime(  496): QSEE Time Listener: Retrieved Android system time: 1454420820
D/DrmLibTime(  496): time_getutcsec returns 0, sec = 1454420820; nsec = 0
D/DrmLibTime(  496): time_getutcsec finished! 
D/DrmLibTime(  496): iotcl_continue_command finished! and return 0 
D/DrmLibTime(  496): before calling ioctl to read the next time_cmd
E/QC-time-services(  433): Daemon: Time-services: Waiting to acceptconnection
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  400): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  400): OEMCrypto_APIVersion: starts!
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  400): hlos api version =  9
D/DrmWidevineDash(  400): tz api version =  9
D/DrmWidevineDash(  400): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  400): OEMCrypto_IsKeyboxValid: starts!
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  400): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  400): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  400): OEMCrypto_OpenSession: starts! SID=0xf49c4928
D/DrmWidevineDash(  400): OEMCrypto_OpenSession Session ID = 0
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  400): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  400): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  400): OEMCrypto_GetRandom: starts! randomData=0xab1fa2b0, dataLength=8
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  400): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  400): OEMCrypto_LoadDeviceRSAKey: starts! SID=1, wrapped_rsa_key=0xab2046e0, wrapped_rsa_key_length=1280
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  400): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  400): CdmEngine::QueryKeyControlInfo
W/WVCdm   (  400): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  400): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  400): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  400): OEMCrypto_GetDeviceID: starts! deviceID=0xab0daa08, idLength=0xf49c46f8
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  400): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  400): OEMCrypto_SupportsUsageTable: starts!
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  400): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  400): OEMCrypto_SupportsUsageTable: wv_app_version = 24
D/DrmWidevineDash(  400): OEMCrypto_SupportsUsageTable: ends! returns 0
D/DrmWidevineDash(  400): OEMCrypto_GetHDCPCapability: starts!, current = 0xf49c470e, maximum = 0xf49c470f
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  400): OEMCrypto_GetHDCPCapability: ends! returns 0
D/DrmWidevineDash(  400): OEMCrypto_APIVersion: starts!
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  400): hlos api version =  9
D/DrmWidevineDash(  400): tz api version =  9
D/DrmWidevineDash(  400): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  400): OEMCrypto_GenerateNonce: starts! SID=1, nonce=0xf49c477c
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  400): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  400): PrepareKeyRequest: nonce=683426612
D/DrmWidevineDash(  400): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xab204f68
D/DrmWidevineDash(  400): message_length=1646, signature=0xab2055e0, signature_length=0xf49c46dc
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  400): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  400): CdmEngine::CloseSession
D/DrmWidevineDash(  400): OEMCrypto_CloseSession: starts! SID=1
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  400): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  400): L3 Terminate.
D/DrmWidevineDash(  400): OEMCrypto_Terminate: starts!
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  400): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  400): Service_Uninitialize: starts!
D/QSEECOMAPI: (  400): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  400): QSEECom_shutdown_app, app_id = 9
D/DrmWidevineDash(  400): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  400): OEMCrypto_Terminate: ends! returns 0
E/cutils-trace( 6504): Error opening trace file: Permission denied (13)
I/dex2oat ( 6504): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm64 --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=42 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
I/dex2oat ( 6504): dex2oat: override thread count:4
E/cutils-trace( 6501): Error opening trace file: Permission denied (13)
I/dex2oat ( 6504): dex2oat took 48.543ms (threads: 4)
I/Adreno-EGL( 6465): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 6465): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6465): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6465): Local Branch: 
I/Adreno-EGL( 6465): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6465): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6465):                  d74aa161a12b9c6fc6332151
D/CustomizationManager( 6501): ====startRecUseTime====
D/htc.customization.log.level( 6501):  is 
W/CustomizationLogLevel( 6501): Level value is invalid, use default level 2
I/HtcModeClient( 3057): handler message = 4011
E/HtcModeClient( 3057): Check connection and retry 12 times.
I/Adreno-EGL( 6465): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 6465): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6465): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6465): Local Branch: 
I/Adreno-EGL( 6465): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6465): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6465):                  d74aa161a12b9c6fc6332151
D/CustomizationManager( 6501):  Read ACC file spent 0.051 (s)
D/CIDMapFileReader( 6501): Parsing tag item name = HTC__001
D/CIDMapFileReader( 6501): Parsing tag item name = HTC__102
D/CIDMapFileReader( 6501): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 6501): Parsing tag item name = HTC__032
D/CIDMapFileReader( 6501): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 6501): Parsing tag item name = HTC__002
D/CIDMapFileReader( 6501): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 6501): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 6501): Parsing tag category name = system
I/CustomizationCIDLoader( 6501): Parsing tag category name = application
I/CustomizationCIDLoader( 6501): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 6501): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 6501): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 6501): Parsing tag category name = Settings
I/CustomizationCIDLoader( 6501): Parsing tag category name = ACC
I/CustomizationCIDLoader( 6501): add string-array item, value = 42507
I/CustomizationCIDLoader( 6501): add string-array item, value = 21902
I/CustomizationCIDLoader( 6501): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 6501): add string-array item, value = 23420
I/CustomizationCIDLoader( 6501): add string-array item, value = 22299
I/CustomizationCIDLoader( 6501): add string-array item, value = 24002
I/CustomizationCIDLoader( 6501): add string-array item, value = 23210
I/CustomizationCIDLoader( 6501): add string-array item, value = 23205
I/CustomizationCIDLoader( 6501): add string-array item, value = 23806
I/CustomizationCIDLoader( 6501): add string-array item, value = 23430
I/CustomizationCIDLoader( 6501): add string-array item, value = 23408
I/CustomizationCIDLoader( 6501): add string-array item, value = 27205
I/CustomizationCIDLoader( 6501): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 6501): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 6501): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 6501): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 6501): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 6501): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 6501): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 6501): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 6501): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 6501): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 6501): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 6501): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 6501):  Read CID file spent 0.092 (s)
D/CustomizationManager( 6501):  All configurations done spent 0.092 (s)
I/CheckinRequestBuilder( 4297): Classify the device as Phone.
--------- beginning of system
I/ActivityManager(  968): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 pid 6501 on display 0
D/PMS     (  968): acquireHCC(21852c68): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 968 1000 null
D/PMS     (  968): acquireHCC(19abc881): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 968 1000 null
D/PMS     (  968): acquireWL(1bb4a714): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 968 1000 null
D/libc    ( 4297): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
D/libc    ( 4297): [NET] android_getaddrinfofornet-, err=8
I/FeedHostManager( 1584): [onPause]
D/libc    ( 4297): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
D/libc    ( 4297): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 4297): [NET] android_getaddrinfo_proxy+
D/libc    ( 4297): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:100, mark:917604
D/libc    (  394): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  394): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 4297): [NET] android_getaddrinfo_proxy-, success
I/AnimationUtil(  968): isHTCRecent(ThaliTest/Recent screens.)/5
I/FeedProviderManager( 1584): onPause
I/FeedHostManager( 1584): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@ce62d2
I/SocialFeedProvider( 1584): +onPause
I/SocialFeedProvider( 1584): -onPause
W/HtcSystemUPManager(  968): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
D/libc    ( 4297): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
D/libc    ( 4297): [NET] android_getaddrinfofornet-, err=8
I/ActivityManager(  968): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6530 uid=10366 gids={50366, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/libc    ( 4297): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
D/libc    ( 4297): [NET] android_getaddrinfofornet-, err=8
I/TrimMemoryManager( 1584): [trimMemory] 20
D/libc    ( 4297): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
D/libc    ( 4297): [NET] android_getaddrinfofornet-, err=8
I/CheckinTask( 4297): Sending checkin request (8422 bytes)
D/StatusBarManagerService(  968): setSystemUiVisibility(0x0)
D/StatusBarManagerService(  968): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  968): hiding MENU key
E/WifiTrafficPoller(  968): TRAFFIC_STATS_POLL true Token 11 num clients 6
E/WifiTrafficPoller(  968):  packet count Tx=147 Rx=233
E/WifiTrafficPoller(  968): notifying of data activity 3
D/WIFI_ICON( 1219): WifiActivity: 3
D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,I/WebViewFactory( 6530): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
I/LibraryLoader( 6530): Time to load native libraries: 9 ms (timestamps 9003-9012)
I/LibraryLoader( 6530): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6530): Binding Chromium to main looper Looper (main, tid 1) {2073f5fa}
I/LibraryLoader( 6530): Expected native library version number "",actual native library version number ""
I/chromium( 6530): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6530): Initializing chromium process, singleProcess=true
W/art     ( 6530): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6530): ApplicationContext is null in ApplicationStatus
W/chromium( 6530): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 6530): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6530): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6530): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 6530): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6530): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6530): Local Branch: 
I/Adreno-EGL( 6530): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6530): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6530):                  d74aa161a12b9c6fc6332151
D/BluetoothManagerService(  968): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  968): java.lang.Throwable: stack dump
D/BluetoothManagerService(  968): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@111dbd6:true
W/System.err(  968): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  968): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  968): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  968): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothAdapter( 6530): 888895430: getState(). Returning 12
I/CheckinRequestBuilder( 4297): Checkin reason type: 11 attempt count: 1
I/ActivityManager(  968): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 4297): Failed to find provider info for com.google.android.wearable.settings
W/art     ( 6530): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 6530): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 6530): CordovaWebView is running on device made by: HTC
W/art     ( 6530): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6530): Attempt to remove local handle scope entry from IRT, ignoring
I/art     ( 1795): Explicit concurrent mark sweep GC freed 11842(625KB) AllocSpace objects, 5(420KB) LOS objects, 49% free, 4MB/8MB, paused 823us total 44.019ms
W/chromium( 6530): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
I/GLSUser ( 1795): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
I/GLSUser ( 1795): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1795): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1795): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1795): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/FindExtension( 6530): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
W/CheckinRequestBuilder( 4297): awaiting user notification for token
D/DotMatrix( 1311): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1311): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
I/RemoteViews( 1219): reapply : com.google.android.gms 2 40
I/CheckinRequestBuilder( 4297): Classify the device as Phone.
I/CheckinTask( 4297): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
I/CheckinService( 4297): Checking schedule, now: 1454420821717 next: 1454957653708
I/CheckinService( 4297): active receiver: disabled
I/PackageManager(  968):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=4297, uid=10024, userID:0
D/PMS     (  968): releaseWL(13333add): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10024 com.google.android.gms}
I/ActivityManager(  968): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=6580 uid=10077 gids={50077, 9997, 3003} abi=arm64-v8a
I/InputMethodManager( 6530): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@5df5c77, mServedView=org.apache.cordova.engine.SystemWebView{950d0e4 VFEDH.C. .F....I. 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@b66994d
I/InputMethodManagerService(  968): Disable input method client, pid=1584
I/ActivityManager(  968): Displayed com.test.thalitest/.MainActivity: +844ms
D/StatusBarManagerService(  968): swetImeWindowStatus vis=0 backDisposition=0
I/InputMethodManagerService(  968): Enable input method client, pid=6530
D/PhoneMonitor( 6580): Register our PhoneStateListener
E/WifiDataStallTracker(  968): DATA_MONITOR_POLL true Token 1
D/PMS     (  968): releaseWL(1bb4a714): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
D/WifiDataStallTracker(  968): updateDataStallInfo: mDataStallTxRxSum={txSum=131 rxSum=119} preTxRxSum={txSum=114 rxSum=106}
D/WifiDataStallTracker(  968): updateDataStallInfo: IN/OUT
D/WifiDataStallTracker(  968): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
I/PhoneStatusBar( 1219): setImeWindowStatus(false,false)
V/SetupWizard( 6580): Connected to Gservices successfully
D/PhoneMonitor( 6580): onServiceStateChanged state="3 3 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1EriInd= -1EriMode= -1RadioPowerSv: false EmergOnly=false PhoneType: 1 VoiceRoaming: false DataRoaming: false IMSRegState: -1" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_POWER_OFF(3) D:STATE_POWER_OFF(3) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
D/ChimeraCfgMgr( 4297): Loading module com.google.android.gms.kids from APK com.google.android.gms
D/ChimeraCfgMgr( 4297): Loading module com.google.android.gms.kids from APK com.google.android.gms
W/XT9_C   ( 1398): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1398): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1398): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1398): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
D/PhoneMonitor( 6580): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_POWER_OFF(3) D:STATE_POWER_OFF(3) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
D/GCM     ( 1795): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
I/GLSUser ( 1795): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 1795): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1795): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1795): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1795): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/BindingManager( 6530): Cannot call determinedVisibility() - never saw a connection for the pid: 6530
W/Kids    ( 4297): [AccountUtils] Account not ready
W/Kids    ( 4297): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 4297): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 4297): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 4297): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 4297): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 4297): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 4297): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 4297): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 4297): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 4297): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 4297): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 4297): 	at java.lang.Thread.run(Thread.java:818)
D/DotMatrix( 1311): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1311): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
I/RemoteViews( 1219): reapply : com.google.android.gms 2 40
D/JsMessageQueue( 6530): Set native->JS mode to OnlineEventsBridgeMode
E/WifiTrafficPoller(  968): TRAFFIC_STATS_POLL true Token 11 num clients 6
E/WifiTrafficPoller(  968):  packet count Tx=148 Rx=236
I/art     (  968): Explicit concurrent mark sweep GC freed 26824(1440KB) AllocSpace objects, 5(292KB) LOS objects, 33% free, 16MB/25MB, paused 1.464ms total 175.363ms
D/jxcore_app_log( 6530): JniHelper::setJavaVM(0xaafae8f8), pthread_self() = -1406384296
I/chromium( 6530): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
E/WifiStateMachine(  968): handleMessage: E msg.what=131155
E/WifiStateMachine(  968): processMsg: ConnectedState
E/WifiStateMachine(  968):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1573090974] gl hn u24 rssi=-54 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  968): processMsg: L2ConnectedState
E/WifiStateMachine(  968):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1573090973] gl hn u24 rssi=-54 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  968):  get link layer stats 0
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1344): wlan0: Control interface command 'SIGNAL_POLL'
I/wpa_supplicant( 1344): environment dirty rate=0 [17][0][0]
E/WifiStateMachine(  968): fetchRssiLinkSpeedAndFrequencyNative RSSI = -59 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  968): fetchRssiLinkSpeedAndFrequencyNative rssi=-59 linkspeed=72
E/WifiConfigStore(  968): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-59 "NG700"WPA_PSK
E/WifiStateMachine(  968): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=8.61 txretriesrate=0.00 rxrate=7.46 userTriggerdPenalty0
E/WifiStateMachine(  968):  good link -> stuck count =0
E/WifiStateMachine(  968):  badRSSI count0 lowRSSI count0 --> score 60
E/WifiStateMachine(  968):  isHighRSSI       ---> score=65
E/WifiStateMachine(  968): handleMessage: X
D/WifiWatchdogStateMachine(  968): RSSI current: 3 new: -59, 3
D/WIFI_ICON( 1219): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/PMS     (  968): releaseHCC(21852c68): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null,
D/PMS     (  968): releaseHCC(19abc881): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,E/WifiTrafficPoller(  968): TRAFFIC_STATS_POLL true Token 11 num clients 6,
E/WifiTrafficPoller(  968):  packet count Tx=148 Rx=236
E/WifiTrafficPoller(  968): notifying of data activity 0
D/WIFI_ICON( 1219): WifiActivity: 0
,D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T],
,W/jxcore-log( 6530): Initializing JXcore engine,
W/jxcore-log( 6530): JXcore engine is ready
,W/jxcore-log( 6530): Starting JXcore engine,
,W/jxcore-log( 6530): Platform android,
W/jxcore-log( 6530): 
W/jxcore-log( 6530): Process ARCH arm
W/jxcore-log( 6530): 
,I/jxcore-log( 6530): JXcore Cordova bridge is ready!,
I/jxcore-log( 6530): 
W/jxcore-log( 6530): JXcore engine is started
,E/jxcore  ( 6530): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js,
E/jxcore  ( 6530): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 6530): [INFO:CONSOLE(37)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (37),
,W/PluginManager( 6530): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 50ms. Plugin should use CordovaInterface.getThreadPool().
D/PMS     (  968): acquireWL(9f18128): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 968 1000 null
W/HtcSystemUPManager(  968): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch,
,I/FeedHostManager( 1584): [onResume],
I/FeedProviderManager( 1584): onResume
I/SocialFeedProvider( 1584): +onResume
,I/SocialFeedProvider( 1584): updateAccounts - Accounts is no change
I/SocialFeedProvider( 1584): -onResume
,D/StatusBarManagerService(  968): setSystemUiVisibility(0x700)
D/StatusBarManagerService(  968): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  968): hiding MENU key
,D/FindExtension( 1584): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
,I/ThreadedRenderer( 1584): Defer allocateBuffers to drawing time
,I/PhoneStatusBar( 1219): setImeWindowStatus(false,false),
I/InputMethodManagerService(  968): Disable input method client, pid=6530
W/IInputConnectionWrapper( 6530): reportFullscreenMode on inactive InputConnection
D/StatusBarManagerService(  968): swetImeWindowStatus vis=0 backDisposition=0
I/InputMethodManagerService(  968): Enable input method client, pid=1584
,D/PMS     (  968): releaseWL(9f18128): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null,
,D/StatusBarManagerService(  968): setSystemUiVisibility(0xc0000700),
D/StatusBarManagerService(  968): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  968): hiding MENU key
,E/WifiTrafficPoller(  968): TRAFFIC_STATS_POLL true Token 11 num clients 6
E/WifiTrafficPoller(  968):  packet count Tx=148 Rx=236
,W/OpenGLRenderer( 1584): Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
,D/Process (  968): killProcessQuiet, pid=5903
I/ActivityManager(  968): Killing 5903:com.google.android.gm/u0a106 (adj 15): empty #17
D/Process (  968): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  968): Recipient 5903
,D/Process (  968): killProcessQuiet, pid=6017
I/ActivityManager(  968): Killing 6017:com.google.android.partnersetup/u0a27 (adj 15): empty #17,
,D/Process (  968): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  968): Recipient 6017,
,D/Process (  968): killProcessQuiet, pid=5870
I/ActivityManager(  968): Killing 5870:com.google.android.talk/u0a112 (adj 15): empty #18
D/Process (  968): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,E/WifiTrafficPoller(  968): TRAFFIC_STATS_POLL true Token 11 num clients 6,
D/WIFI_ICON( 1219): WifiActivity: 1
E/WifiTrafficPoller(  968):  packet count Tx=148 Rx=237
D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
E/WifiTrafficPoller(  968): notifying of data activity 1
,I/ActivityManager(  968): Recipient 5870
,E/WifiStateMachine(  968): handleMessage: E msg.what=131155,
E/WifiStateMachine(  968): processMsg: ConnectedState
E/WifiStateMachine(  968):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=8.6, 0.0, 0.0  rx=7.5 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1573087954] gl hn u24 rssi=-54 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,E/WifiStateMachine(  968): processMsg: L2ConnectedState
E/WifiStateMachine(  968):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=8.6, 0.0, 0.0  rx=7.5 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1573087952] gl hn u24 rssi=-54 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  968):  get link layer stats 0
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1344): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1344): environment dirty rate=0 [2][0][0]
E/WifiStateMachine(  968): fetchRssiLinkSpeedAndFrequencyNative RSSI = -59 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  968): fetchRssiLinkSpeedAndFrequencyNative rssi=-59 linkspeed=72
E/WifiConfigStore(  968): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-59 "NG700"WPA_PSK
D/WIFI_ICON( 1219): updateWifiState: RSSI_CHANGED 3 -> 3
E/WifiStateMachine(  968): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=5.31 txretriesrate=0.00 rxrate=4.73 userTriggerdPenalty0
D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
E/WifiStateMachine(  968):  good link -> stuck count =0
E/WifiStateMachine(  968):  badRSSI count0 lowRSSI count0 --> score 60
,E/WifiStateMachine(  968):  isHighRSSI       ---> score=65
D/WifiWatchdogStateMachine(  968): RSSI current: 3 new: -59, 3
E/WifiStateMachine(  968): handleMessage: X
,I/HtcModeClient( 3057): handler message = 4011,
E/HtcModeClient( 3057): Check connection and retry 12 times. Stop service and kill this process.
D/HtcModeClient( 3057): Don't start project servcice
,D/HtcModeClient( 3057): setEject: MEDIA_EJECT_STATE = true
,D/HtcModeClient( 3057): connectState: CONNECTION_READY = false,
D/SilentMusic( 3057): call stop
D/HtcModeClient( 3057): close connection
W/HtcModeClient( 3057): leaveProjectMode: It does not enter ProjectMode
W/CANMesgAgentLocalSocket( 3057): read the terminate packet, so break
,D/Process (  968): killProcessQuiet, pid=3057
I/ActivityManager(  968): Killing 3057:com.htc.autobot/u0a47 (adj 15): empty #17
D/Process (  968): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  968): Recipient 3057,
,E/WifiTrafficPoller(  968): TRAFFIC_STATS_POLL true Token 11 num clients 6
D/WIFI_ICON( 1219): WifiActivity: 3
,E/WifiTrafficPoller(  968):  packet count Tx=150 Rx=238
D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
E/WifiTrafficPoller(  968): notifying of data activity 3
,E/WifiDataStallTracker(  968): DATA_MONITOR_POLL true Token 1,
,D/WifiDataStallTracker(  968): updateDataStallInfo: mDataStallTxRxSum={txSum=133 rxSum=120} preTxRxSum={txSum=131 rxSum=119},
D/WifiDataStallTracker(  968): updateDataStallInfo: IN/OUT
D/WifiDataStallTracker(  968): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,E/WifiTrafficPoller(  968): TRAFFIC_STATS_POLL true Token 11 num clients 6
E/WifiTrafficPoller(  968):  packet count Tx=150 Rx=238
,E/WifiTrafficPoller(  968): notifying of data activity 0
D/WIFI_ICON( 1219): WifiActivity: 0
D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/ActivityManager(  968): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=6616 uid=10076 gids={50076, 9997} abi=arm64-v8a,
D/PMS     (  968): acquireWL(18e545be): PARTIAL_WAKE_LOCK  *alarm* 0x1 968 1000 WorkSource{10076}
,V/AlarmManager(  968): sending alarm PendingIntent{23d2c61f: PendingIntentRecord{1415fd6c com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1454420827530, Int=60000
,D/PMS     (  968): releaseWL(18e545be): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10076}
,D/SMSBackup( 6616): SMSBackupAgentService started
,D/SMSBackup( 6616): Checking restore status
,D/SMSBackup( 6616): Restore complete
,D/SMSBackup( 6616): cancelCheckAlarm
,D/SMSBackup( 6616): SMSBackupAgentService completed: completed in 0.0 seconds,
,D/Process (  968): killProcessQuiet, pid=6336
,I/ActivityManager(  968): Killing 6336:com.htc.cs.dm/u0a99 (adj 15): empty #17
D/Process (  968): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  968): Recipient 6336
,E/WifiTrafficPoller(  968): TRAFFIC_STATS_POLL true Token 11 num clients 6,
E/WifiTrafficPoller(  968):  packet count Tx=150 Rx=239
E/WifiTrafficPoller(  968): notifying of data activity 1
D/WIFI_ICON( 1219): WifiActivity: 1
D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,E/WifiStateMachine(  968): handleMessage: E msg.what=131155,
E/WifiStateMachine(  968): processMsg: ConnectedState
E/WifiStateMachine(  968):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=5.3, 0.0, 0.0  rx=4.7 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1573084942] gl hn u24 rssi=-54 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  968): processMsg: L2ConnectedState
E/WifiStateMachine(  968):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=5.3, 0.0, 0.0  rx=4.7 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1573084941] gl hn u24 rssi=-54 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  968):  get link layer stats 0
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1344): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1344): environment dirty rate=0 [0][0][0],
E/WifiStateMachine(  968): fetchRssiLinkSpeedAndFrequencyNative RSSI = -59 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  968): fetchRssiLinkSpeedAndFrequencyNative rssi=-59 linkspeed=72
E/WifiConfigStore(  968): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-59 "NG700"WPA_PSK
E/WifiStateMachine(  968): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=2.65 txretriesrate=0.00 rxrate=2.87 userTriggerdPenalty0
D/WIFI_ICON( 1219): updateWifiState: RSSI_CHANGED 3 -> 3
E/WifiStateMachine(  968):  good link -> stuck count =0
,D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
E/WifiStateMachine(  968):  badRSSI count0 lowRSSI count0 --> score 56
E/WifiStateMachine(  968):  isHighRSSI       ---> score=61
E/WifiStateMachine(  968): handleMessage: X
D/WifiWatchdogStateMachine(  968): RSSI current: 3 new: -59, 3
,E/WifiTrafficPoller(  968): TRAFFIC_STATS_POLL true Token 11 num clients 6
,D/WIFI_ICON( 1219): WifiActivity: 0
E/WifiTrafficPoller(  968):  packet count Tx=150 Rx=239
D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/WifiTrafficPoller(  968): notifying of data activity 0
,I/Prism.ItemManager( 1584): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
W/Prism.AllAppsManager( 1584): AllAppsMgr addApps, already exist: ApplicationInfo(id=33, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
I/Prism.ItemManager( 1584): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
D/AccTypeManager( 1766): Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
W/SystemReader(  968): Cannot find grip_rejection_width, use default value instead
,I/ActivityManager(  968): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=6639 uid=10112 gids={50112, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,D/AccTypeManager( 1766): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,W/ResourcesManager(  968): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/PhoneApp( 1543): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED,
,D/AccTypeManager( 1766): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin,
,E/ExternalAccountType( 1766): Unsupported attribute readOnly,
W/ResourcesManager( 6639): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/PackageManager(  968): Unable to load service info ResolveInfo{32bd3c15 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  968): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  968): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:475)
W/PackageManager(  968): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:331)
W/PackageManager(  968): 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
W/PackageManager(  968): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  968): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
W/PackageManager(  968): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
W/PackageManager(  968): 	at android.os.Handler.handleCallback(Handler.java:739)
W/PackageManager(  968): 	,at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  968): 	at android.os.Looper.loop(Looper.java:155)
W/PackageManager(  968): 	at com.android.server.SystemServer.run(SystemServer.java:324)
W/PackageManager(  968): 	at com.android.server.SystemServer.main(SystemServer.java:225)
W/PackageManager(  968): 	at java.lang.reflect.Method.invoke(Native Method)
W/PackageManager(  968): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/PackageManager(  968): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
W/PackageManager(  968): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,V/GmsNetworkLocationProvi( 1908): DISABLE
,I/GCoreNlp( 1908): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
I/BackupManagerService(  968): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,D/PMS     (  968): acquireWL(31ad4d9f): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1908 10024 WorkSource{10024 com.google.android.gms},
D/LocationProviderProxy(  968): applying state to connected service
,D/PMS     (  968): releaseWL(31ad4d9f): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,D/LocationProviderProxy(  968): applying state to connected service
,D/PMS     (  968): acquireWL(1c6aaeec): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1908 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  968): releaseWL(1c6aaeec): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  968): acquireWL(27c9cdd8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1908 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  968): releaseWL(27c9cdd8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  968): acquireWL(3af9ef84): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1908 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  968): releaseWL(3af9ef84): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,I/Babel_SMS( 6639): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 6639): MmsConfig.loadMmsSettings
,I/ActivityManager(  968): Start proc com.htc.sense.mms for content provider com.htc.sense.mms/.util.MmsCustomizationProvider: pid=6668 uid=10064 gids={50064, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a,
,I/PackageManager(  968):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=6639, uid=10112, userID:0,
,W/HtcWrapAdjustableCursorFactory( 6668): HtcWrapAdjustableCursorFactory is deprecated. Use HtcWrapSQLite in HDK Lib3 instead.,
,D/MessageFrequencyProvider( 6668): onCreate,
,W/Settings( 6639): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/GetPrviateResource( 6668): GetPrviateResource
,V/GetPrviateResource( 6668): GetPrviateResource
,D/MmsCustomizationProvider( 6668): query uri: content://htc-mms-customization/mms-ua/ua_string,
,I/Babel_Crash( 6639): startup - clean
,D/MessageCustFlag( 6668): sense_version=6.0,
,D/BTAccessoryUtil( 6668): createReceiver,
D/BTAccessoryUtil( 6668): registerReceiver return intent = null
D/MessageCustFlag( 6668): sku_id=118
,I/Babel   ( 6639): deleted: false for 0
D/HtcBuildUtils( 6668): getRATByHtcTelephonyCapability:1
W/SystemReader( 6668): Cannot find qct_8960_interface, use default value instead
,D/MmsCustomizationProvider( 6668): query uri: content://htc-mms-customization/mms-ua/ua_profile,
,I/Babel_SMS( 6639): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_One_M8s/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/PPzlrbleWf/ua-profile.xml
,I/Babel_SMS( 6639): MmsConfig.loadFromDatabase,
,E/Babel_SMS( 6639): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6639): MmsConfig.loadFromResources
,E/Babel_SMS( 6639): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 6639): MmsConfig.loadMmsSettings: mUserAgent=HTC_One_M8s/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/PPzlrbleWf/ua-profile.xml
,I/PackageManager(  968):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.SmsReceiver, state=2, flag=1, pid=6639, uid=10112, userID:0,
I/PackageManager(  968):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.MmsWapPushReceiver, state=2, flag=1, pid=6639, uid=10112, userID:0
,I/PackageManager(  968):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.AbortSmsReceiver, state=2, flag=1, pid=6639, uid=10112, userID:0
,I/PackageManager(  968):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=6639, uid=10112, userID:0
,I/PackageManager(  968):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.service.NoConfirmationSmsSendService, state=1, flag=1, pid=6639, uid=10112, userID:0
,D/PMS     (  968): acquireWL(35810ec6): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 6639 10112 null
,I/[PluginManager]RegisterService( 1656): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
,I/[PluginManager]RegisterService( 1656): handle notify Blinkfeed plugin client changed
,W/VideoCapabilities( 6639): Unrecognized profile 2130706433 for video/avc
,D/PackageBroadcastService( 4297): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 4297): Null package name or gms related package.  Ignoreing.
,D/PMS     (  968): acquireWL(12faded9): PARTIAL_WAKE_LOCK  Icing 0x1 4297 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  968): acquireWL(398d309e): PARTIAL_WAKE_LOCK  AsyncService 0x1 6144 10167 null
,D/PMS     (  968): releaseWL(398d309e): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
I/Icing   ( 4297): updateResources: need to parse f{com.google.android.gms}
,D/PMS     (  968): acquireWL(1e00134c): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 6144 10167 null
,D/PMS     (  968): releaseWL(1e00134c): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 null
,I/UpdateIcingCorporaServi( 5983): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,D/PMS     (  968): releaseWL(12faded9): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms}
W/VideoCapabilities( 6639): Unsupported mime video/x-ms-wmv
W/Utils   ( 6639): could not parse size range '64x64-1920X1080'
W/AudioCapabilities( 6639): Unsupported mime audio/qcelp
W/AudioCapabilities( 6639): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 6639): Unsupported mime audio/qcelp
,W/VideoCapabilities( 6639): Unsupported mime video/x-ms-wmv
,I/UpdateIcingCorporaServi( 5983): UpdateCorporaTask done [took 51 ms] updated apps [took 51 ms] 
,I/VideoCapabilities( 6639): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6639): Unrecognized profile 2130706433 for video/avc,
,W/VideoCapabilities( 6639): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6639): Unrecognized profile 2130706433 for video/avc,
W/VideoCapabilities( 6639): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 6639): onServiceConnected
,W/Babel   ( 6639): Attempted to change video mute state without an active call.
,D/PMS     (  968): releaseWL(35810ec6): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,W/ResourcesManager( 6639): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
W/ResourcesManager( 6639): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6639): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...,
,W/System  ( 6639): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6639): Installed default security provider GmsCore_OpenSSL,
,E/WifiTrafficPoller(  968): TRAFFIC_STATS_POLL true Token 11 num clients 6
,D/WIFI_ICON( 1219): WifiActivity: 1
E/WifiTrafficPoller(  968):  packet count Tx=150 Rx=240
D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
E/WifiTrafficPoller(  968): notifying of data activity 1
,I/Prism.ItemManager( 1584): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
,I/Prism.ItemManager( 1584): loadItems() com.htc.launcher.pageview.WidgetManager@29986e6d +
I/Prism.WidgetManager( 1584): onLoadItems() +
,W/ResourcesManager( 1584): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,E/WifiTrafficPoller(  968): TRAFFIC_STATS_POLL true Token 11 num clients 6,
E/WifiTrafficPoller(  968):  packet count Tx=150 Rx=240
D/WIFI_ICON( 1219): WifiActivity: 0
E/WifiTrafficPoller(  968): notifying of data activity 0
D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,W/asset   ( 1584): Copying FileAsset 0x55b2b67930 (zip:/data/app/com.gameloft.android.gdc-2/base.apk:/resources.arsc) to buffer size 405676 to make it aligned.,
,E/Prism.WidgetManager( 1584): The same lists. No need to update. skip it.,
I/Prism.WidgetManager( 1584): onLoadItems() -
I/Prism.ItemManager( 1584): loadItems() com.htc.launcher.pageview.WidgetManager@29986e6d -
,D/PhoneApp( 1543): EVENT_QUERY_MO_PACKAGES,
,D/PhoneApp( 1543): -- N1 =0
,D/PhoneApp( 1543): -- N2 =0
,D/PhoneApp( 1543): -- N3 =0
,E/WifiStateMachine(  968): handleMessage: E msg.what=131155,
E/WifiStateMachine(  968): processMsg: ConnectedState
E/WifiStateMachine(  968):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=2.7, 0.0, 0.0  rx=2.9 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1573081919] gl hn u24 rssi=-54 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  968): processMsg: L2ConnectedState
E/WifiStateMachine(  968):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-59 f=2412 sc=60 link=72 tx=2.7, 0.0, 0.0  rx=2.9 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1573081918] gl hn u24 rssi=-54 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  968):  get link layer stats 0,
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1344): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1344): environment dirty rate=0 [0][0][0]
E/WifiStateMachine(  968): fetchRssiLinkSpeedAndFrequencyNative RSSI = -59 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  968): fetchRssiLinkSpeedAndFrequencyNative rssi=-59 linkspeed=72
E/WifiConfigStore(  968): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-59 "NG700"WPA_PSK
,E/WifiStateMachine(  968): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=1.33 txretriesrate=0.00 rxrate=1.93 userTriggerdPenalty0
D/WIFI_ICON( 1219): updateWifiState: RSSI_CHANGED 3 -> 3
E/WifiStateMachine(  968):  good link -> stuck count =0,
D/StatusBar.NetworkController( 1219): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/WifiStateMachine(  968):  badRSSI count0 lowRSSI count0 --> score 56
E/WifiStateMachine(  968):  isHighRSSI       ---> score=61
E/WifiStateMachine(  968): handleMessage: X
D/WifiWatchdogStateMachine(  968): RSSI current: 3 new: -59, 3
,D/PMS     (  968): acquireWL(2b51c4d): PARTIAL_WAKE_LOCK  *alarm* 0x1 968 1000 WorkSource{1000}
V/AlarmManager(  968): sending alarm PendingIntent{2370e0c: PendingIntentRecord{2100d355 android broadcastIntent}}, i=com.android.server.WifiManager.action.START_SCAN, t=1, cnt=1, w=1454420831511, Int=20000
,D/WifiDisplayAdapter(  968): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  968):     Client/Owner: Client
D/WifiDisplayAdapter(  968):     GroupId: 
D/WifiDisplayAdapter(  968):     Passphrase: 
D/WifiDisplayAdapter(  968):     SessionId: 0
D/WifiDisplayAdapter(  968):     IP Address: }
E/WifiStateMachine(  968): WiFiStateMachine SCAN ALARM
E/WifiStateMachine(  968): handleMessage: E msg.what=131143
D/PMS     (  968): releaseWL(2b51c4d): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,E/WifiStateMachine(  968): processMsg: ConnectedState
,E/WifiStateMachine(  968):  ConnectedState !CMD_START_SCAN -2 -2 ic=5 proc(ms):2 dur:85 rssi=-59 f=2412 sc=60 link=72 tx=1.3, 0.0, 0.0  rx=1.9 list=2412 [on:0 tx:0 rx:0 period:70] from screen [on:0 period:-1573081830]
E/WifiStateMachine(  968): processMsg: L2ConnectedState
E/WifiStateMachine(  968):  L2ConnectedState !CMD_START_SCAN -2 -2 ic=5 proc(ms):3 dur:85 rssi=-59 f=2412 sc=60 link=72 tx=1.3, 0.0, 0.0  rx=1.9 list=2412 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1573081829]
E/WifiStateMachine(  968): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=1.33 rxSuccessRate=1.93 targetRoamBSSID=c0:ff:d4:d3:aa:48 RSSI=-59
E/WifiStateMachine(  968): WifiStateMachine CMD_START_SCAN with age=35006 interval=60000 maxinterval=300000
E/WifiStateMachine(  968): WifiStateMachine CMD_START_SCAN full=false
E/WifiConfigStore(  968): makeChannelList age=3600000 for "NG700"WPA_PSK max=6 bssids=1
E/WifiConfigStore(  968): has c0:ff:d4:d3:aa:48 freq=2412 age=74 ?=true
E/WifiStateMachine(  968): WifiStateMachine starting scan for "NG700"WPA_PSK with 2412
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN TYPE=ONLY freq=2412"
D/wpa_supplicant( 1344): wlan0: Control interface command 'SCAN TYPE=ONLY freq=2412'
D/wpa_supplicant( 1344): wlan0: Setting scan request: 0.000000 sec
I/wpa_supplicant( 1344): wpa_supplicant_scan enter
D/wpa_supplicant( 1344): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 1344): WPS: Building WPS IE for Probe Request
D/wpa_supplicant( 1344): WPS:  * Version (hardcoded 0x10)
,D/wpa_supplicant( 1344): WPS:  * Request Type
D/wpa_supplicant( 1344): WPS:  * Config Methods (4288)
D/wpa_supplicant( 1344): WPS:  * UUID-E
D/wpa_supplicant( 1344): WPS:  * Primary Device Type
D/wpa_supplicant( 1344): WPS:  * RF Bands (3)
D/wpa_supplicant( 1344): WPS:  * Association State
D/wpa_supplicant( 1344): WPS:  * Configuration Error (0)
D/wpa_supplicant( 1344): WPS:  * Device Password ID (0)
D/wpa_supplicant( 1344): WPS:  * Manufacturer
D/wpa_supplicant( 1344): WPS:  * Model Name
D/wpa_supplicant( 1344): WPS:  * Model Number
D/wpa_supplicant( 1344): WPS:  * Device Name
D/wpa_supplicant( 1344): WPS:  * Version2 (0x20)
D/wpa_supplicant( 1344): P2P: * P2P IE header
,D/wpa_supplicant( 1344): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 1344): P2P: * Listen Channel: Regulatory Class 81 Channel 1
D/wpa_supplicant( 1344): wlan0: Limit manual scan to specified channels
D/wpa_supplicant( 1344): wlan0: Add radio work 'scan'@0x5566425680
D/wpa_supplicant( 1344): wlan0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1344): wlan0: Starting radio work 'scan'@0x5566425680 after 0.000038 second wait
D/wpa_supplicant( 1344): wlan0: nl80211: scan request
D/wpa_supplicant( 1344): Scan requested (ret=0) - scan timeout 30 seconds
D/wpa_supplicant( 1344): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 1344): wlan0: nl80211: Scan trigger
D/wpa_supplicant( 1344): wlan0: Event SCAN_STARTED (49) received
D/wpa_supplicant( 1344): wlan0: Own scan request started a scan in 0.000081 seconds
,I/wpa_supplicant( 1344): wlan0: CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine(  968): [1,454,420,831,517 ms] noteScanstart no scan source
E/WifiStateMachine(  968): handleMessage: X
D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor(  968): WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  968): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  968): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,D/wpa_supplicant( 1344): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 1344): wlan0: nl80211: New scan results available
D/wpa_supplicant( 1344): nl80211: Scan included frequencies: 2412
D/wpa_supplicant( 1344): wlan0: Event SCAN_RESULTS (3) received
I/wpa_supplicant( 1344): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1344): wlan0: Scan completed in 0.078047 seconds
D/wpa_supplicant( 1344): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1344): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1344): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1344): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
I/wpa_supplicant( 1344): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-51
I/wpa_supplicant( 1344): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1344): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-59
D/wpa_supplicant( 1344): wlan0: BSS: Start scan result update 6
D/wpa_supplicant( 1344): BSS: last_scan_res_used=3/32
D/wpa_supplicant( 1344): wlan0: Scan-only results received
D/wpa_supplicant( 1344): wlan0: Radio work 'scan'@0x5566425680 done in 0.078910 seconds
E/WifiMonitor(  968): WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor(  968): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
E/WifiStateMachine(  968): handleMessage: E msg.what=147461
E/WifiStateMachine(  968): processMsg: ConnectedState
W/ContextImpl(  968): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:14146 com.android.server.wifi.WifiStateMachine.handleMediaLinkEvent:14311 com.android.server.wifi.WifiStateMachine.access$6000:268 com.android.server.wifi.WifiStateMachine$SupplicantStartedState.processMessage:8091 
E/WifiStateMachine(  968):  ConnectedState !SCAN_RESULTS_EVENT 0 0 found=3 known=1 got=3 bcn=0
E/WifiStateMachine(  968): processMsg: L2ConnectedState
E/WifiStateMachine(  968):  L2ConnectedState !SCAN_RESULTS_EVENT 0 0 found=3 known=1 got=3 bcn=0
E/WifiStateMachine(  968): processMsg: ConnectModeState
E/WifiStateMachine(  968):  ConnectModeState !SCAN_RESULTS_EVENT 0 0 found=3 known=1 got=3 bcn=0
E/WifiStateMachine(  968): processMsg: DriverStartedState
E/WifiStateMachine(  968):  DriverStartedState !SCAN_RESULTS_EVENT 0 0 found=3 known=1 got=3 bcn=0
E/WifiStateMachine(  968): processMsg: SupplicantStartedState
E/WifiStateMachine(  968):  SupplicantStartedState !SCAN_RESULTS_EVENT 0 0 found=3 known=1 got=3 bcn=0
D/WifiStateMachine(  968): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1344): wlan0: Control interface command 'LIST_DONGLES'
E/WifiStateMachine(  968): [1,454,420,831,600 ms] noteScanEnd no scan source
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/wpa_supplicant( 1344): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
,E/WifiStateMachine(  968): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@1e8c0707 sup_state=COMPLETED debouncing=false
E/WifiAutoJoinController (  968): NG7005g c0:ff:d4:d3:aa:4a rssi=-51 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiAutoJoinController (  968): NG700 c0:ff:d4:d3:aa:48 rssi=-59 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiConfigStore(  968): updateSavedNetworkHistory(): try "NG700"WPA_PSK SSID="NG700" NG700 [WPA2-PSK-CCMP][WPS][ESS] ajst=0
E/WifiConfigStore(  968): updateSavedNetworkHistory: HTC improve mode
E/WifiConfigStore(  968):         got known scan result c0:ff:d4:d3:aa:48 key : "NG700"WPA_PSK num: 1 rssi=-59 freq=2412
,E/WifiAutoJoinController (  968): 01ABC c2:ff:d4:d3:aa:48 rssi=-59 cap [WPA2-PSK-CCMP][ESS] is not scored
E/WifiAutoJoinController (  968): ageScanResultsOut delay 40000 size 3 now 1454420831603
E/WifiAutoJoinController (  968): newSupplicantResults size=3 known=1 true
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 STATUS-NO_EVENTS"
D/wpa_supplicant( 1344): wlan0: Control interface command 'STATUS-NO_EVENTS'
E/WifiAutoJoinController (  968): attemptAutoJoin() status=bssid=c0:ff:d4:d3:aa:48
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
E/WifiAutoJoinController (  968): attemptAutoJoin good candidate seen, bumped hard -> status=0 "NG700"WPA_PSK rssi=(-59,-127) num=(1,0)
E/WifiAutoJoinController (  968): attemptAutoJoin skip current candidate  0 key "NG700"WPA_PSK
,E/WifiAutoJoinController (  968): attemptRoam: "NG700"WPA_PSK Found c0:ff:d4:d3:aa:48 rssi=-59 freq=2412 Current: c0:ff:d4:d3:aa:48
D/HtcWifiControlRoamOffload: (  968): roamCandidate: nullcurrentBSSID: c0:ff:d4:d3:aa:48
E/WifiStateMachine(  968): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiAutoJoinController (  968): Done attemptAutoJoin status=0
E/WifiConfigStore(  968):  writeKnownNetworkHistory() num networks:1 needWrite=false
E/WifiStateMachine(  968): handleMessage: X
,D/Messaging( 6668): supportCMAS(SIE)/init? false/true
D/MmsConfig( 6668): networkCode: 
D/MessageCustFlag( 6668): sku_id=118
D/MmsConfig( 6668): SIE smsPri: null
D/MmsConfig( 6668): networkCode: 
,D/MmsConfig( 6668): packageName: com.htc.vvm.att does not exist
,D/Messaging( 6668): mNeedToUpdateDate2 start
,D/ReportIndicatorCache( 6668): startAsyncQueryReports ---
D/MmsAsyncWorkHandler( 6668): 
D/MmsAsyncWorkHandler( 6668): HM tk = 20001
D/ReportIndicatorCache( 6668): MSG_QUERY_REPORTS >>
,D/SettingsManager( 6668): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@1fae17ab,
,D/TelephUtils( 1543): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 50,
D/AccFlag ( 1543): sku_id=118,
D/DraftCache( 6668): [DraftCache/1] DraftCache.constructor
D/DraftCache( 6668): [DraftCache/1] refresh
D/TelephUtils( 1543): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 49
D/MmsSmsV2Provider( 1543):  slotId = -1000
D/MmsSmsV2Provider( 1543): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
D/DraftCache( 6668): [DraftCache/171] rebuildCache
,I/Messaging( 6668): mccmnc> 
,D/TelephUtils( 1543): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 95
D/MmsSmsV2Provider( 1543):  slotId = -1000,
D/MmsSmsV2Provider( 1543): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
D/MmsConfig( 6668): networkCode: 
,D/Messaging( 6668): ViewCache CreatePreloadOnlyConversationList,
,D/TelephUtils( 1543): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 92
D/MmsSmsV2Provider( 1543):  slotId = -1000
,D/MmsSmsV2Provider( 1543): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
,D/Messaging( 6668): mNeedToUpdateDate2: false
,D/TelephUtils( 1543): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 95
D/Jerry   ( 1543): URI_DRAFT,
,D/DraftCache( 6668): hasDraft() = false mNeedNotifyChange = true
D/DraftCache( 6668): [DraftCache/171] rebuildCache time: 14
D/MmsAsyncWorkHandler( 6668): 
D/MmsAsyncWorkHandler( 6668): HM tk = 20002
,D/TelephUtils( 1543): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 49
,D/MmsSmsV2Provider( 1543):  slotId = -1000
D/MmsSmsV2Provider( 1543): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
,D/TelephUtils( 1543): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 50
D/AccFlag ( 1543): sku_id=118
,D/Messaging( 6668): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
D/PhoneStorageUtil( 6668): HtcWrapEnvironment.getSupportedStorages() >1
D/PhoneStorageUtil( 6668): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
D/PhoneStorageUtil( 6668): createReceiver
,D/MessageCustFlag( 6668): sense_version=6.0
D/Jerry   ( 6668): start to preload cursor >>>>>>>
,D/TelephUtils( 1543): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 64
,D/AccFlag ( 1543): sku_id=118
,D/TelephUtils( 1543): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 49
D/MmsSmsV2Provider( 1543):  slotId = -1000
,D/TelephUtils( 1543): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 50,
V/MmsProvider( 1543): Update uri=content://mms, match=0
V/MmsProvider( 1543): selection=st=129 AND m_type!=134
,D/Messaging( 6668): Reset downloading state: 0
,V/MmsSystemEventReceiver( 6668): TransactionService is going to be woken up.,
,V/TransactionService( 6668): 1-Creating TransactionService
,D/Messaging( 6668): ViewCache CreatePreload
D/Messaging( 6668): ViewCache CreatePreloadOnlyMultipleOpsList
,V/TransactionService( 6668): onStartCommand: 1
D/MmsSystemEventReceiver( 6668): unRegisterForConnectionStateChanges
D/Cust_MMSMS( 6668): _has_set_default_values_2=true
V/TransactionService( 6668): 4-Handling incoming message: { when=0 what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
V/TransactionService( 6668): Loading previous transactions.
,D/MsgPreferenceUtils( 6668): def_index: 0
,D/TelephUtils( 1543): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 64,
D/AccFlag ( 1543): device_type: 1
D/MsgPreferenceUtils( 6668): globalIndex = 1
,D/TransactionService( 6668): Force clearing mTransactionList
D/TransactionService( 6668): Force set service start id to 1
V/TransactionService( 6668): stopSelfIfIdle: unRegisterForConnectionStateChanges
D/MmsSystemEventReceiver( 6668): unRegisterForConnectionStateChanges
,V/TransactionService( 6668): Destroying TransactionService
D/TransactionService( 6668): stopSelfResult: true, mLastHandledServiceId: 1
,D/MsgPreferenceUtils( 6668): phone state: true,
D/MsgPreferenceUtils( 6668): sd state: false
D/MsgPreferenceUtils( 6668): vIndex = 0
V/TransactionService( 6668): 4-Handling incoming message: { when=-3ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,E/WifiDataStallTracker(  968): DATA_MONITOR_POLL true Token 1
,D/WifiDataStallTracker(  968): updateDataStallInfo: mDataStallTxRxSum={txSum=133 rxSum=120} preTxRxSum={txSum=133 rxSum=120}
D/WifiDataStallTracker(  968): updateDataStallInfo: NONE
D/WifiDataStallTracker(  968): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,E/WifiTrafficPoller(  968): TRAFFIC_STATS_POLL true Token 11 num clients 6,
E/WifiTrafficPoller(  968):  packet count Tx=150 Rx=240
,I/PMS     (  968): Going to sleep due to screen timeout (uid 1000)...,
D/ActivityManager(  968): getTaskThumbnailLocked mainThumbnail is null, TaskRecord{1ab6af1 #7 A=.Prism U=0 sz=1}
,W/PMS     (  968): mWirelessDisplayManager is null
W/PMS     (  968): mWirelessDisplayManager is still null
,I/SensorManager(  968): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@68f2ebb
I/PMS     (  968): Sleeping (uid 1000)...
W/SensorService(  968): Following SensorService logs are not warning, just make sure they are printed
D/XAN-DPS (  968): prepareColorFade 1
W/SensorService(  968): disable: get sensor name = Accelerometer Sensor
,W/SensorService(  968): pid=968, uid=1000
W/SensorService(  968): Active sensors: size = 4
W/SensorService(  968): Accelerometer Sensor (handle=0x00000000, connections=1)
W/SensorService(  968): CM32181 Light sensor (handle=0x00000003, connections=1)
W/SensorService(  968): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  968): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  968): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@68f2ebb, eanble = 0, strlen(mName) = 90
W/SensorService(  968): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  968): Listener[0] = com.android.server.display.AutomaticBrightnessController$1@25fbe404
W/SensorService(  968): Listener[1] = com.htc.smartdim.sensor_eye@22171b31
W/SensorService(  968): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/PMN     (  968): goingToSleep
D/PMS     (  968): acquireWL(17f826d6): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 968 1000 null
,I/Adreno-EGL(  968): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL(  968): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL(  968): Build Date: 03/09/15 Mon
I/Adreno-EGL(  968): Local Branch: 
I/Adreno-EGL(  968): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL(  968): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL(  968):                  d74aa161a12b9c6fc6332151
,W/PMN     (  968): goingToSleep done
I/FeedHostManager( 1584): [onPause]
I/FeedProviderManager( 1584): onPause,
I/FeedHostManager( 1584): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@ce62d2
I/SocialFeedProvider( 1584): +onPause
I/SocialFeedProvider( 1584): -onPause
W/HtcLockScreen( 1219): KeyguardViewMediator: doKeyguard: not showing because lockscreen is off
,D/AlarmManager(  968): ACTION_SCREEN_ON
,I/AlarmManager(  968): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  968): [AlarmQueuing] done recovering
I/AlarmManager(  968): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  968): [AlarmQueuing] done EPS screen off alarm recovering
,I/ActivityManager(  968): Start proc com.htc.bgp for broadcast com.htc.flexnet/.SystemIntentReceiver: pid=6734 uid=10011 gids={50011, 9997, 1028, 1015, 5001, 5011, 2001, 3003} abi=arm64-v8a,
,E/WifiTrafficPoller(  968): ENABLE_TRAFFIC_STATS_POLL true Token 11
E/WifiTrafficPoller(  968):  packet count Tx=150 Rx=240
E/WifiDataStallTracker(  968): ENABLE_DATA_MONITOR_POLL true Token 1
,E/WifiStateMachine(  968): handleMessage: E msg.what=131167
D/PMS     (  968): releaseWL(17f826d6): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
E/WifiStateMachine(  968): processMsg: ConnectedState
E/WifiStateMachine(  968):  ConnectedState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  968): processMsg: L2ConnectedState
E/WifiStateMachine(  968):  L2ConnectedState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  968): processMsg: ConnectModeState
E/WifiStateMachine(  968):  ConnectModeState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  968): processMsg: DriverStartedState
D/WifiDisplayAdapter(  968): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:,
D/WifiDisplayAdapter(  968):     Client/Owner: Client
D/WifiDisplayAdapter(  968):     GroupId: 
D/WifiDisplayAdapter(  968):     Passphrase: 
D/WifiDisplayAdapter(  968):     SessionId: 0
D/WifiDisplayAdapter(  968):     IP Address: }
W/HtcSystemUPManager(  968): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
E/WifiStateMachine(  968):  DriverStartedState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  968): processMsg: SupplicantStartedState
E/WifiStateMachine(  968):  SupplicantStartedState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  968): processMsg: DefaultState
E/WifiStateMachine(  968):  DefaultState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  968):  handleScreenStateChanged Enter: screenOn=true mCurrentScanAlarmMs = 20000 mUserWantsSuspendOpt=false state ConnectedState suppState:CompletedState
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
D/wpa_supplicant( 1344): wlan0: Control interface command 'SET_SCREEN_ON 1'
I/wpa_supplicant( 1344): SET_SCREEN_ON:On
I/wpa_supplicant( 1344): htc_wext_set_keepalive +
I/wpa_supplicant( 1344): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1344): getPrivFuncNum +	
I/wpa_supplicant( 1344): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1344): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1344): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1344): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1344): htc_wext_set_TX_TRACKING - ret = 0
D/WifiDataStallTracker(  968): updateDataStallInfo: mDataStallTxRxSum={txSum=133 rxSum=120} preTxRxSum={txSum=133 rxSum=120}
D/WifiDataStallTracker(  968): updateDataStallInfo: NONE
D/WifiDataStallTracker(  968): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
E/WifiStateMachine(  968): setScanAlarm true period 20000 initial delay 200mAlarmEnabledtrue
D/WifiStateMachine(  968): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine(  968): handleScreenStateChanged Exit: true
E/WifiStateMachine(  968): handleMessage: X
E/WifiStateMachine(  968): handleMessage: E msg.what=131154
E/WifiStateMachine(  968): processMsg: ConnectedState
E/WifiStateMachine(  968):  ConnectedState !CMD_ENABLE_RSSI_POLL 1 0
E/WifiStateMachine(  968): processMsg: L2ConnectedState
E/WifiStateMachine(  968):  L2ConnectedState !CMD_ENABLE_RSSI_POLL 1 0
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1344): wlan0: Control interface command 'SIGNAL_POLL'
V/SRS_Proc(  400): ParamSet string: screen_state=on
E/audio_a2dp_hw(  400): adev_set_parameters: ERROR: set param called even when stream out is null
,D/WifiController(  968): handleMessage: E msg.what=155650
D/WifiController(  968): processMsg: DeviceActiveState
D/WifiController(  968): processMsg: StaEnabledState
D/WifiController(  968): processMsg: DefaultState
D/WifiController(  968): handleMessage: X
,I/wpa_supplicant( 1344): environment dirty rate=0 [0][0][0]
,E/WifiStateMachine(  968): fetchRssiLinkSpeedAndFrequencyNative RSSI = -58 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  968): fetchRssiLinkSpeedAndFrequencyNative rssi=-58 linkspeed=72
E/WifiConfigStore(  968): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-58 "NG700"WPA_PSK
E/WifiStateMachine(  968): handleMessage: X
E/WifiStateMachine(  968): handleMessage: E msg.what=131127
E/WifiStateMachine(  968): processMsg: ConnectedState
E/WifiStateMachine(  968):  ConnectedState !CMD_ENABLE_ALL_NETWORKS 0 0
E/WifiStateMachine(  968): processMsg: L2ConnectedState
,E/WifiStateMachine(  968):  L2ConnectedState !CMD_ENABLE_ALL_NETWORKS 0 0
E/WifiStateMachine(  968): processMsg: ConnectModeState
E/WifiStateMachine(  968):  ConnectModeState !CMD_ENABLE_ALL_NETWORKS 0 0
E/WifiStateMachine(  968): handleMessage: X
E/WifiStateMachine(  968): handleMessage: E msg.what=131129
E/WifiStateMachine(  968): processMsg: ConnectedState
E/WifiStateMachine(  968):  ConnectedState !CMD_CLEAR_BLACKLIST 0 0
E/WifiStateMachine(  968): processMsg: L2ConnectedState
,E/WifiStateMachine(  968):  L2ConnectedState !CMD_CLEAR_BLACKLIST 0 0
E/WifiStateMachine(  968): processMsg: ConnectModeState
E/WifiStateMachine(  968):  ConnectModeState !CMD_CLEAR_BLACKLIST 0 0
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 BLACKLIST clear"
D/wpa_supplicant( 1344): wlan0: Control interface command 'BLACKLIST clear'
,E/wpa_supplicant( 1344): wlan0: BLACKLIST CLEAR 
D/WifiMonitor(  968): Event [IFNAME=wlan0 BLACKLIST CLEAR ]
E/WifiMonitor(  968): WifiMonitor:wlan0 cnt=33 dispatchEvent: BLACKLIST CLEAR 
E/WifiStateMachine(  968): handleMessage: X
,D/NetworkPolicy(  968): updateScreenOn: false
,V/NetworkPolicy(  968): updateIfacesLocked()
,D/NetworkManagementService(  968): isBandwidthControlEnabled: doneSignal.getCount()= 0,
D/GpsLocationProvider(  968): receive broadcast intent, action: android.intent.action.SCREEN_ON
,W/ResourcesManager( 6734): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.,
,D/DotMatrix( 1311): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,I/IntentController( 1219): receive(android.intent.action.SCREEN_ON,1,false)
,I/CalendarProvider2( 6734): Created com.android.providers.calendar.CalendarAlarmManager@2aae3025(com.htc.providers.calendar.HtcCalendarProvider@2073f5fa)
,D/PMS     (  968): acquireWL(1c51d3dc): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1908 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  968): acquireWL(358c6ce5): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1908 10024 WorkSource{10024 com.google.android.gms}
,D/XAN-DPS (  968): prepareColorFade done
,D/CalendarProvider2( 6734): wait start:true
D/XAN-DPS (  968): setBrightness to 0
,D/PMS     (  968): releaseWL(358c6ce5): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  968): releaseWL(1c51d3dc): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,I/SensorManager(  968): unregisterListenerImpl++: listener = com.android.server.display.AutomaticBrightnessController$1@25fbe404
W/SensorService(  968): Following SensorService logs are not warning, just make sure they are printed
I/DisplayManagerService(  968): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 442.451 x 443.345 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
W/SensorService(  968): disable: get sensor name = CM32181 Light sensor,
,W/SensorService(  968): pid=968, uid=1000
W/SensorService(  968): Active sensors: size = 3
W/SensorService(  968): Accelerometer Sensor (handle=0x00000000, connections=1)
W/SensorService(  968): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  968): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  968): SensorService::listenerSensor++: mName = com.android.server.display.AutomaticBrightnessController$1@25fbe404, eanble = 0, strlen(mName) = 67
W/SensorService(  968): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  968): Listener[0] = com.htc.smartdim.sensor_eye@22171b31
W/SensorService(  968): void android::SensorService::listenerSensor(const char*, int32_t)--:
,D/DotMatrix( 1311): [EventService]  onDisplayChanged: 0
D/DotMatrix( 1311): [EventService] mbHDMIConnect: false, mCoverOn:false
V/ActivityManager(  968): Display changed displayId=0
E/qdutils (  386): int qdutils::getHDMINode(): Failed to open fb node 2
,E/qdutils (  386): int qdutils::getHDMINode(): Failed to find HDMI node
,D/AlarmManager(  968): ACTION_SCREEN_OFF
,I/AlarmManager(  968): [AlarmQueuing] screen off now: 
,I/AlarmManager(  968): [AlarmQueuing] data connection: true
I/AlarmManager(  968): [AlarmQueuing] wifi connection: true
,E/WifiTrafficPoller(  968): ENABLE_TRAFFIC_STATS_POLL false Token 12
D/WifiDataStallTracker(  968): stopDataStallAlarm 
,E/WifiDataStallTracker(  968): ENABLE_DATA_MONITOR_POLL false Token 2
E/WifiStateMachine(  968): handleMessage: E msg.what=131167
E/WifiStateMachine(  968): processMsg: ConnectedState
,E/WifiStateMachine(  968):  ConnectedState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  968): processMsg: L2ConnectedState
E/WifiStateMachine(  968):  L2ConnectedState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  968): processMsg: ConnectModeState
E/WifiStateMachine(  968):  ConnectModeState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  968): processMsg: DriverStartedState
V/SRS_Proc(  400): ParamSet string: screen_state=off
E/audio_a2dp_hw(  400): adev_set_parameters: ERROR: set param called even when stream out is null
E/WifiStateMachine(  968):  DriverStartedState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  968): processMsg: SupplicantStartedState
E/WifiStateMachine(  968):  SupplicantStartedState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  968): processMsg: DefaultState
E/WifiStateMachine(  968):  DefaultState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  968):  handleScreenStateChanged Enter: screenOn=false mCurrentScanAlarmMs = 20000 mUserWantsSuspendOpt=false state ConnectedState suppState:CompletedState
W/WifiHW  (  968): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
,D/wpa_supplicant( 1344): wlan0: Control interface command 'SET_SCREEN_ON 0'
I/wpa_supplicant( 1344): SET_SCREEN_ON:Off
I/wpa_supplicant( 1344): htc_wext_set_keepalive +
I/wpa_supplicant( 1344): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1344): getPrivFuncNum +	
I/wpa_supplicant( 1344): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1344): htc_wext_set_keepalive fnum = 0x8bf6
,I/wpa_supplicant( 1344): get_ip_address source addr = c0a80182
I/wpa_supplicant( 1344): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1344): htc_wext_set_keepalive - ret = 0
,D/WifiController(  968): handleMessage: E msg.what=155651
D/WifiDisplayAdapter(  968): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  968):     Client/Owner: Client
D/WifiDisplayAdapter(  968):     GroupId: 
D/WifiDisplayAdapter(  968):     Passphrase: 
D/WifiDisplayAdapter(  968):     SessionId: 0
D/WifiDisplayAdapter(  968):     IP Address: }
D/WifiController(  968): processMsg: DeviceActiveState
D/WifiController(  968): processMsg: StaEnabledState
D/WifiController(  968): processMsg: DefaultState
D/WifiController(  968): handleMessage: X
E/WifiStateMachine(  968): setScanAlarm false period 20000 initial delay 0mAlarmEnabledtrue
D/NetworkPolicy(  968): updateScreenOn: false
V/NetworkPolicy(  968): updateIfacesLocked()
,D/NetworkManagementService(  968): isBandwidthControlEnabled: doneSignal.getCount()= 0
D/WifiStateMachine(  968): backgroundScan enabled=true startBackgroundScanIfNeeded:false
E/WifiStateMachine(  968): handleScreenStateChanged Exit: false
E/WifiStateMachine(  968): handleMessage: X
E/WifiStateMachine(  968): handleMessage: E msg.what=131154
E/WifiStateMachine(  968): processMsg: ConnectedState
,E/WifiStateMachine(  968):  ConnectedState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  968): processMsg: L2ConnectedState
E/WifiStateMachine(  968):  L2ConnectedState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  968): handleMessage: X
,D/CalendarProvider2( 6734): wait end:false
,I/SensorManager( 1219): registerListenerImpl: listener = com.htc.sense.easyaccessservice.SensorHubService@4a46b06, sensor = {Sensor name="hTC Gesture Motion HIDI", vendor="hTC Corp.", version=1, type=10, maxRange=200.0, resolution=1.0, power=0.2, minDelay=0}, delay = 200000, handler = null,
,W/SensorService(  968): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  968): enable: get sensor name = hTC Gesture Motion HIDI
,W/SensorService(  968): pid=1219, uid=10041,
W/SensorService(  968): Active sensors: size = 4,
W/SensorService(  968): Accelerometer Sensor (handle=0x00000000, connections=1)
W/SensorService(  968): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  968): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  968): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
W/SensorService(  968): SensorService::listenerSensor++: mName = com.htc.sense.easyaccessservice.SensorHubService@4a46b06, eanble = 1, strlen(mName) = 56
W/SensorService(  968): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  968): Listener[0] = com.htc.smartdim.sensor_eye@22171b31
W/SensorService(  968): Listener[1] = com.htc.sense.easyaccessservice.SensorHubService@4a46b06
W/SensorService(  968): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/ActivityManager(  968): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=6765 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
,D/GpsLocationProvider(  968): receive broadcast intent, action: android.intent.action.SCREEN_OFF,
,D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3,
,D/DotMatrix( 1311): [EventService] getTotalRam: 1842 Mb
,D/ContactMessageStore( 1543): start background delete task...
I/IntentController( 1219): receive(android.intent.action.SCREEN_OFF,1,false)
,D/ContactMessageStore( 1543): size: 0 , 0
,D/ContactMessageStore( 1543): Background delete complete
,I/RemoteViews( 1219): setHTCTheme(com.htc.updater,true,33751145)
,I/RemoteViews( 1219): apply : com.htc.updater 1 12 0 36
,D/PMS     (  968): acquireWL(422c274): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1908 10024 WorkSource{10024 com.google.android.gms}
W/ContextImpl( 6765): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,D/PMS     (  968): acquireWL(247fa012): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1908 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  968): releaseWL(422c274): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  968): releaseWL(247fa012): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,W/ContextImpl( 6765): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:22 android.app.ActivityThread.handleReceiver:2712 
,E/qdutils (  386): int qdutils::getHDMINode(): Failed to open fb node 2
,D/SurfaceControl(  968): Excessive delay in setPowerMode(): 293ms,
E/qdutils (  386): int qdutils::getHDMINode(): Failed to find HDMI node
D/PMS     (  968): Setting HAL interactive mode to false
,D/PowerUsageList:PowerUsageHelper( 6765): MY_DEBUG = false
D/PMS     (  968): Setting HAL interactive mode to false done
D/PMS     (  968): Setting HAL auto-suspend mode to true
D/PMS     (  968): Setting HAL auto-suspend mode done
W/HtcSystemUPManager(  968): HtcSystemUPHandler The policy is disabled. AppId: UTD_BI, category: C0006
,I/InputMethodManagerService(  968): screenObserver, isScreenOn=false,
I/PhoneStatusBar( 1219): setImeWindowStatus(false,false)
D/StatusBarManagerService(  968): swetImeWindowStatus vis=0 backDisposition=0
D/HABCtrl (  968): TPE algorithm. remove timeout.
I/InputMethodManagerService(  968): Disable input method client, pid=1584
D/PMS     (  968): OOBE c monitor 11
,D/PMS     (  968): acquireWL(1e391e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 968 1000 null
I/BatteryService(  968): n_update end
,D/NfcService( 1557): applyRouting - 0
D/PMS     (  968): releaseWL(1e391e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  968): updateBatteryInfo
,D/SmartSyncUtils( 6765): isEpsOn(), nState = 0
D/NotificationService(  968): plugged=true pluggin=true
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1219): closing low battery warning: level=100
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  968): runPSCheck
D/UsbnetService(  968): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  968): Checking...
D/UsbnetService(  968): onReceive BATTERY_CHANGED
,I/HtcPowerSaver(  968): >> updateStatus
D/UsbnetService(  968):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  968): acquireWL(17978c99): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1557 1027 null
D/UsbnetService(  968): BroadcastReceiver::onReceive-
D/PowerUI ( 1219): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1311): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  968): releaseWL(17978c99): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/NfcService( 1557): ScreenObserver: OFF
I/HtcPowerSaver(  968): updateStatus (8000,100,-1,false,false,false,-1)
D/HeadsetStateMachine( 2945): Disconnected process message: 10, size: 0
I/HtcPowerSaver(  968): << updateStatus
I/IntentController( 1219): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/NfcService( 1557): applyRouting -2
D/NfcService( 1557): applyRouting
D/NfcService( 1557): Ignore this applyRouting...
D/WifiController(  968): battery changed pluggedType: 2
D/WifiController(  968): handleMessage: E msg.what=155652
D/WifiController(  968): processMsg: DeviceActiveState
D/WifiController(  968): processMsg: StaEnabledState
D/WifiController(  968): processMsg: DefaultState
D/WifiController(  968): handleMessage: X
,D/PMS     (  968): acquireWL(fb3ab5e): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 6765 1000 null,
,I/InputManager(  968): Cancel all due to getting PMS screen off broadcast. ActualScreenOn=false,
,I/IntentController( 1219): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
,W/ContextImpl(  968): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2712 
,D/SmartDim(  968): Init customizeScreenOffDelayClass error
D/PMS     (  968): releaseWL(fb3ab5e): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,W/ContextImpl( 6765): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,I/BatteryController( 1219): status:5 level:100 unsupport:false plugged:true
,W/ContextImpl( 6765): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:22 android.app.ActivityThread.handleReceiver:2712 ,
,D/SmartSyncUtils( 6765): isEpsOn(), nState = 0
D/SmartSyncUtils( 6765): isEpsOn(), nState = 0
,I/ClockController( 1219): stop clock update:screen off
,W/ContextImpl( 6765): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:73 android.app.ActivityThread.handleReceiver:2712 
,W/ContextImpl(  968): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1830 android.content.ContextWrapper.stopService:520 android.content.ContextWrapper.stopService:520 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2712 
,I/SensorManager(  968): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@22171b31
W/SensorService(  968): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  968): disable: get sensor name = Accelerometer Sensor
,W/SensorService(  968): pid=968, uid=1000,
W/SensorService(  968): Active sensors: size = 3
W/SensorService(  968): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  968): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  968): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
W/SensorService(  968): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@22171b31, eanble = 0, strlen(mName) = 36
W/SensorService(  968): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  968): Listener[0] = com.htc.sense.easyaccessservice.SensorHubService@4a46b06
W/SensorService(  968): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  968): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  968): disable: get sensor name = CM36686 Proximity sensor,
,W/SensorService(  968): pid=968, uid=1000
,W/SensorService(  968): Active sensors: size = 2
W/SensorService(  968): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  968): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
W/SensorService(  968): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@22171b31, eanble = 0, strlen(mName) = 36
W/SensorService(  968): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  968): Listener[0] = com.htc.sense.easyaccessservice.SensorHubService@4a46b06
W/SensorService(  968): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  968): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@22171b31
,I/ActivityManager(  968): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=6797 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a
,E/ActivityThread(  968): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@705b216 that was originally registered here. Are you missing a call to unregisterReceiver()?,
E/ActivityThread(  968): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@705b216 that was originally registered here. Are you missing a call to unregisterReceiver()?
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
,E/ActivityThread(  968): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  968): 	at android.os.Looper.loop(Looper.java:155)
E/ActivityThread(  968): 	at com.android.server.SystemServer.run(SystemServer.java:324)
E/ActivityThread(  968): ,	at com.android.server.SystemServer.main(SystemServer.java:225)
E/ActivityThread(  968): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread(  968): ,	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread(  968): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/ActivityThread(  968): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,E/WifiTrafficPoller(  968): TRAFFIC_STATS_POLL false Token 13 num clients 6
,I/art     (  968): Explicit concurrent mark sweep GC freed 35571(2017KB) AllocSpace objects, 4(680KB) LOS objects, 33% free, 18MB/28MB, paused 2.816ms total 167.558ms
,I/PowerUsageList:PowerUsageHelper( 6765): PowerProfile::POWER_SCREEN_FULL = 154.8
,D/PowerUsageList:BatterySipperExt( 6765): gen(), null == sipper.uidObj, userId = 0
,D/SmartSyncUtils( 6765): getMobilePolicyEnabled, result = true,
D/Process (  968): killProcessQuiet, pid=6358
I/ActivityManager(  968): Killing 6358:com.htc.providers.settings:remote/u0a13 (adj 15): empty #17
D/Process (  968): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.removeContentProvider:10141 
,D/WifiService(  968): New client listening to asynchronous messages
E/WifiTrafficPoller(  968): ADD_CLIENT: 7
,I/ActivityManager(  968): Recipient 6358,
,D/PowerUsageList:PowerUsageHelper( 6765): MY_DEBUG = false,
,E/WifiTrafficPoller(  968): TRAFFIC_STATS_POLL false Token 13 num clients 7
,I/ActivityManager(  968): Killing 6115:com.google.android.gms:car/u0a24 (adj 15): empty #17
,D/Process (  968): killProcessQuiet, pid=6115
,D/Process (  968): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  968): Recipient 6115
,I/CalendarProvider2( 6734): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: },
W/ContentResolver( 6734): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,D/ProviderChangeReceiver( 6430): ---------------------------------------------------,
,D/ProviderChangeReceiver( 6430): ProviderChangeReceiver onReceive, start HtcAlertService to update notification!
I/ActivityManager(  968): Killing 6387:com.google.android.apps.docs/u0a101 (adj 15): empty #17
D/Process (  968): killProcessQuiet, pid=6387
D/Process (  968): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processNextBroadcast:706 
D/HtcAlertService( 6430): start to updateAlertNotification!
,I/ActivityManager(  968): Recipient 6387
,D/HtcAlertService( 6430): No fired or scheduled alerts
,D/HtcAlertUtils( 6430): -- cancelReminderNotification --
,D/HtcAlertUtils( 6430): broadcastExistReminder!
,D/DotMatrix( 1311): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/PMS     (  968): releaseWL(2003688b): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 null,
,E/WifiStateMachine(  968): handleMessage: E msg.what=131155,
E/WifiStateMachine(  968): processMsg: ConnectedState
E/WifiStateMachine(  968):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2929] from screen [on:0 period:-1573078897] gl hn u24 rssi=-54 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  968): processMsg: L2ConnectedState
E/WifiStateMachine(  968):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1573078894] gl hn u24 rssi=-54 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0,
E/WifiStateMachine(  968): handleMessage: X
,D/Process (  968): killProcessQuiet, pid=5640
I/ActivityManager(  968): Killing 5640:com.android.defcontainer/u0a15 (adj 15): empty #17
,D/Process (  968): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  968): Recipient 5640
,I/ActivityManager(  968): Killing 5502:com.htc.mediamanager/u0a28 (adj 15): empty #17,
D/Process (  968): killProcessQuiet, pid=5502
D/Process (  968): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  968): Recipient 5502
,E/WifiStateMachine(  968): handleMessage: E msg.what=131155,
E/WifiStateMachine(  968): processMsg: ConnectedState
E/WifiStateMachine(  968):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:939] from screen [on:0 period:-1573077953] gl hn u24 rssi=-54 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  968): processMsg: L2ConnectedState
E/WifiStateMachine(  968):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-58 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1573077951] gl hn u24 rssi=-54 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0,
E/WifiStateMachine(  968): handleMessage: X
,D/HtcUPManager( 1219): HtcUPServiceProxy onTrimMemory() has been called. Memory Level: 60,
,E/WifiDataStallTracker(  968): DATA_MONITOR_POLL false Token 3,
,E/WifiDataStallTracker(  968): DATA_MONITOR_POLL false Token 3,
,W/Atfwd_Sendcmd(  429): AtCmdFwd service not published, waiting... retryCnt : 1,
,W/Atfwd_Sendcmd(  429): AtCmdFwd service not published, waiting... retryCnt : 2
,I/ActivityManager(  968): Killing 5695:com.htc.musicenhancer/u0a49 (adj 15): empty #17
,D/Process (  968): killProcessQuiet, pid=5695
D/Process (  968): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  968): Recipient 5695,
,D/ContactMessageStore( 1543): MSG_NOTIFY_CS_TO_SYNC >>
D/ContactMessageStore( 1543): MSG_NOTIFY_CS_TO_SYNC <<
,D/PMS     (  968): acquireWL(1fcb5955): PARTIAL_WAKE_LOCK  *alarm* 0x1 968 1000 WorkSource{10024},
V/AlarmManager(  968): sending alarm PendingIntent{2b8b1f6a: PendingIntentRecord{23cadc5b com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=140600, Int=0
,D/PMS     (  968): releaseWL(1fcb5955): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10024}
,W/Atfwd_Sendcmd(  429): AtCmdFwd service not published, waiting... retryCnt : 3
,D/GpsLocationProvider(  968): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  968): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  968): acquireWL(15e5bcf8): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 968 1000 null
,D/libc    (  968): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 4
D/libc    (  968): [NET] android_getaddrinfofornet-, err=8
D/libc    (  968): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024
D/libc    (  968): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  968): [NET] android_getaddrinfo_proxy+
D/libc    (  968): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  394): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024
,D/libc    (  394): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,D/libc    (  394): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  394): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  968): [NET] android_getaddrinfo_proxy-, success
D/libc    (  968): [NET] android_getaddrinfofornet+,hn 13(0x35342e3233302e),sn(),hints(known),family 0,flags 4
D/libc    (  968): [NET] android_getaddrinfofornet-, SUCCESS
,D/GpsLocationProvider(  968): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  968): [reportHTCStatus] eventMask = 3 , status = 0
,D/PMS     (  968): acquireWL(135b0a4): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 968 1000 null
D/GpsLocationProvider(  968): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
D/PMS     (  968): releaseWL(15e5bcf8): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 null
D/GpsLocationProvider(  968):  [handleDownloadXtraData]inject done.
D/PMS     (  968): releaseWL(135b0a4): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/GpsLocationProvider(  968): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,W/ContextImpl(  968): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 
,W/Atfwd_Sendcmd(  429): AtCmdFwd service not published, waiting... retryCnt : 4,
,D/PMS     (  968): acquireWL(22865e0d): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 968 1000 null
I/BatteryService(  968): n_update end
D/PMS     (  968): releaseWL(22865e0d): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  968): updateBatteryInfo
D/HeadsetStateMachine( 2945): Disconnected process message: 10, size: 0
D/NotificationService(  968): plugged=true pluggin=true
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  968): runPSCheck
D/DotMatrix( 1311): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  968): Checking...
D/UsbnetService(  968): BroadcastReceiver::onReceive+
I/HtcPowerSaver(  968): >> updateStatus
D/UsbnetService(  968): onReceive BATTERY_CHANGED
D/WifiController(  968): battery changed pluggedType: 2
D/UsbnetService(  968):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  968): BroadcastReceiver::onReceive-
D/WifiController(  968): handleMessage: E msg.what=155652
D/WifiController(  968): processMsg: DeviceActiveState
D/WifiController(  968): processMsg: StaEnabledState
D/WifiController(  968): processMsg: DefaultState
D/WifiController(  968): handleMessage: X
I/IntentController( 1219): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1219): closing low battery warning: level=100
D/PowerUI ( 1219): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  968): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  968): << updateStatus
,I/BatteryController( 1219): status:5 level:100 unsupport:false plugged:true,
,W/Atfwd_Sendcmd(  429): AtCmdFwd service not published, waiting... retryCnt : 5,
,D/TelephonyReceiver( 1543): switchBindHtcMsgCursor: null,
,D/PMS     (  968): acquireWL(2eec31c2): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 968 1000 WorkSource{1000}
,V/AlarmManager(  968): sending alarm PendingIntent{fcb3c46: PendingIntentRecord{a0a2e07 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=157782, Int=0
V/AlarmManager(  968): sending alarm PendingIntent{2fc67bd3: PendingIntentRecord{296f3310 android broadcastIntent}}, i=android.app.backup.intent.INIT, t=0, cnt=1, w=1454420889572, Int=0
V/AlarmManager(  968): sending alarm PendingIntent{1447ce09: PendingIntentRecord{274fa80e android broadcastIntent}}, i=com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE, t=2, cnt=1, w=202087, Int=0
V/AlarmManager(  968): sending alarm PendingIntent{af3022f: PendingIntentRecord{137c703c com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=192714, Int=0
D/PMS     (  968): acquireWL(9641c5): PARTIAL_WAKE_LOCK  *backup* 0x1 968 1000 null
,D/PMS     (  968): acquireWL(2b62371a): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1795 10024 WorkSource{10024 com.google.android.gms},
W/BackupManagerService(  968): Requested unavailable transport: com.google.android.gms.backup.BackupTransportService
E/BackupManagerService(  968): Requested init for com.google.android.gms.backup.BackupTransportService but not found
D/PMS     (  968): releaseWL(9641c5): PARTIAL_WAKE_LOCK  *backup* 0x1 null
D/PMS     (  968): releaseWL(2eec31c2): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1219): Weather sync is On
,W/WeatherTimeKeeper( 1219): [refreshWeatherData] no weather data
,D/PMS     (  968): acquireWL(1db7924b): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1795 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  968): releaseWL(2b62371a): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,V/GLSActivity( 1795): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/PMS     (  968): releaseWL(1db7924b): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  968): acquireWL(15d7e47d): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1795 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  968): releaseWL(15d7e47d): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  968): acquireWL(a388f72): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1795 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  968): releaseWL(a388f72): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  968): acquireWL(39f5ffc3): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1795 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  968): acquireWL(357d8040): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1795 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  968): acquireWL(2bfc30be): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1795 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  968): releaseWL(39f5ffc3): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,I/VacuumService( 1795): Vacuum at: now=1454420924632 tag=VacuumService
,D/PMS     (  968): releaseWL(2bfc30be): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  968): acquireWL(27da606c): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1795 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  968): releaseWL(27da606c): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  968): acquireWL(e42635): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1795 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  968): releaseWL(e42635): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  968): releaseWL(357d8040): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
D/PMS     (  968): acquireWL(26c69aca): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1795 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  968): releaseWL(26c69aca): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  968): acquireWL(7f5a43b): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1795 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  968): releaseWL(7f5a43b): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  968): acquireWL(3c431758): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1795 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  968): acquireWL(3fbdf0b1): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1795 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  968): releaseWL(3c431758): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,I/GoogleURLConnFactory( 1795): Using platform SSLCertificateSocketFactory,
,W/Uploader( 1795): No account for auth token provided,
,D/libc    ( 1795): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 1795): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 1795): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 1795): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1795): [NET] android_getaddrinfo_proxy+
D/libc    ( 1795): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,D/libc    (  394): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  394): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 1795): [NET] android_getaddrinfo_proxy-, success
,D/libc    ( 1795): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4,
D/libc    ( 1795): [NET] android_getaddrinfofornet-, err=8,
D/libc    ( 1795): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 1795): [NET] android_getaddrinfofornet-, err=8
,W/Uploader( 1795): No account for auth token provided,
,W/Uploader( 1795): No account for auth token provided,
,W/Uploader( 1795):  no longer exists, so no auth token.,
,W/Uploader( 1795): No account for auth token provided,
,I/GLSUser ( 1795): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1795): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1795): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1795): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1795): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/DotMatrix( 1311): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1311): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1219): reapply : com.google.android.gms 2 40,
,E/Uploader( 1795): Failed to get auth token: User intervention required. Notification has been pushed.,
E/Uploader( 1795): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1795): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1795): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1795): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1795): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1795): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1795): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1795): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1795): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1795): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1795): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1795): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,D/PMS     (  968): releaseWL(3fbdf0b1): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  968): acquireWL(3794122b): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1795 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  968): releaseWL(3794122b): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
D/PMS     (  968): acquireWL(3fd70688): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1795 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  968): releaseWL(3fd70688): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/HtcUPManager( 1219): HtcUPServiceProxy Disconnect from  UP serivce: No interaction with app
,D/HtcUPManager( 1219): HtcUPServiceProxy Disconnect from UP service. Change state to: DISCONNECTED
D/HtcAppUPService( 1656): HtcUPService [##] onDestroy(), this =com.htc.sense.hsp.upservice.HtcUPService@207ad374
,D/Process (  968): killProcessQuiet, pid=6580
I/ActivityManager(  968): Killing 6580:com.google.android.setupwizard/u0a77 (adj 15): empty #17
D/Process (  968): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  968): Recipient 6580
,W/Atfwd_Sendcmd(  429): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  968): acquireWL(7bb6821): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 968 1000 null
I/BatteryService(  968): n_update end
D/PMS     (  968): releaseWL(7bb6821): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PowerUI ( 1219): closing low battery warning: level=100
I/IntentController( 1219): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1219): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  968): updateBatteryInfo
D/DotMatrix( 1311): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/NotificationService(  968): plugged=true pluggin=true
D/HeadsetStateMachine( 2945): Disconnected process message: 10, size: 0
D/PMS     (  968): runPSCheck
D/UsbnetService(  968): BroadcastReceiver::onReceive+
D/WifiController(  968): battery changed pluggedType: 2
D/UsbnetService(  968): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  968): Checking...
D/UsbnetService(  968):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/HtcPowerSaver(  968): >> updateStatus
D/UsbnetService(  968): BroadcastReceiver::onReceive-
D/WifiController(  968): handleMessage: E msg.what=155652
D/WifiController(  968): processMsg: DeviceActiveState
D/WifiController(  968): processMsg: StaEnabledState
D/WifiController(  968): processMsg: DefaultState
D/WifiController(  968): handleMessage: X
,I/HtcPowerSaver(  968): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  968): << updateStatus
,I/BatteryController( 1219): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  968): acquireWL(f0b9446): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 968 1000 null
I/BatteryService(  968): n_update end
,D/UsbnetService(  968): BroadcastReceiver::onReceive+
D/PMS     (  968): releaseWL(f0b9446): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  968): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  968): updateBatteryInfo
D/UsbnetService(  968):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/NotificationService(  968): plugged=true pluggin=true
D/UsbnetService(  968): BroadcastReceiver::onReceive-
D/PMS     (  968): runPSCheck
D/HtcPowerSaver(  968): Checking...
I/HtcPowerSaver(  968): >> updateStatus
,D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1311): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1219): closing low battery warning: level=100
D/HeadsetStateMachine( 2945): Disconnected process message: 10, size: 0
I/HtcPowerSaver(  968): updateStatus (8000,100,-1,false,false,false,-1)
I/IntentController( 1219): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/HtcPowerSaver(  968): << updateStatus
D/PowerUI ( 1219): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  968): handleMessage: E msg.what=155652
D/WifiController(  968): processMsg: DeviceActiveState
D/WifiController(  968): processMsg: StaEnabledState
D/WifiController(  968): battery changed pluggedType: 2
D/WifiController(  968): processMsg: DefaultState
D/WifiController(  968): handleMessage: X
,I/BatteryController( 1219): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  429): AtCmdFwd service not published, waiting... retryCnt : 2
,W/Atfwd_Sendcmd(  429): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  429): AtCmdFwd service not published, waiting... retryCnt : 4
,D/wpa_supplicant( 1344): wlan0: BSS: Remove id 0 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1344): wlan0: BSS: Remove id 2 BSSID c2:ff:d4:d3:aa:48 SSID '01ABC' due to wpa_bss_flush_by_age
D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a]
E/WifiMonitor(  968): WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a
D/WifiMonitor(  968): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 2 c2:ff:d4:d3:aa:48]
E/WifiMonitor(  968): WifiMonitor:wlan0 cnt=35 dispatchEvent: CTRL-EVENT-BSS-REMOVED 2 c2:ff:d4:d3:aa:48
,D/PMS     (  968): acquireWL(233fa607): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 968 1000 null
I/BatteryService(  968): n_update end
D/PMS     (  968): releaseWL(233fa607): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  968): updateBatteryInfo
I/IntentController( 1219): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1219): closing low battery warning: level=100
D/UsbnetService(  968): BroadcastReceiver::onReceive+
D/NotificationService(  968): plugged=true pluggin=true
,D/UsbnetService(  968): onReceive BATTERY_CHANGED
D/PMS     (  968): runPSCheck
D/UsbnetService(  968):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  968): Checking...
D/UsbnetService(  968): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  968): >> updateStatus
D/WifiController(  968): handleMessage: E msg.what=155652
,D/WifiController(  968): battery changed pluggedType: 2
D/WifiController(  968): processMsg: DeviceActiveState
D/PowerUI ( 1219): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  968): processMsg: StaEnabledState
I/HtcPowerSaver(  968): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  968): processMsg: DefaultState
I/HtcPowerSaver(  968): << updateStatus
D/WifiController(  968): handleMessage: X
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1311): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HeadsetStateMachine( 2945): Disconnected process message: 10, size: 0
,I/BatteryController( 1219): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  429): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  968): acquireWL(171a0334): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 968 1000 WorkSource{1000}
V/AlarmManager(  968): sending alarm PendingIntent{fcb3c46: PendingIntentRecord{a0a2e07 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=217782, Int=0
,V/AlarmManager(  968): sending alarm PendingIntent{225caed2: PendingIntentRecord{27269ba3 com.htc.backup startService}}, i=resume, t=0, cnt=1, w=1454421061180, Int=0
,D/PMS     (  968): releaseWL(171a0334): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1219): Weather sync is On
,W/WeatherTimeKeeper( 1219): [refreshWeatherData] no weather data
,W/Atfwd_Sendcmd(  429): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  429): AtCmdFwd service not published, waiting... retryCnt : 2
,D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  968): acquireWL(31ee1ea0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 968 1000 null
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/BatteryService(  968): n_update end
D/DotMatrix( 1311): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  968): releaseWL(31ee1ea0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/IntentController( 1219): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  968): updateBatteryInfo
D/HeadsetStateMachine( 2945): Disconnected process message: 10, size: 0
D/PowerUI ( 1219): closing low battery warning: level=100
D/UsbnetService(  968): BroadcastReceiver::onReceive+
D/NotificationService(  968): plugged=true pluggin=true
D/UsbnetService(  968): onReceive BATTERY_CHANGED
D/PMS     (  968): runPSCheck
D/UsbnetService(  968):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  968): Checking...
D/UsbnetService(  968): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  968): >> updateStatus
D/PowerUI ( 1219): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  968): handleMessage: E msg.what=155652
D/WifiController(  968): processMsg: DeviceActiveState
D/WifiController(  968): battery changed pluggedType: 2
D/WifiController(  968): processMsg: StaEnabledState
D/WifiController(  968): processMsg: DefaultState
D/WifiController(  968): handleMessage: X
,I/HtcPowerSaver(  968): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  968): << updateStatus
,I/BatteryController( 1219): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  429): AtCmdFwd service not published, waiting... retryCnt : 3
,V/GLSActivity( 1795): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1795): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1795): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1795): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1795): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1795): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/GLSActivity( 1795): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1795): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1795): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1795): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1795): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1795): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1795): 	at android.os.Binder.execTransact(Binder.java:454)
,E/PlayEventLogger( 6074): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6074): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6074): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 6074): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 6074): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 6074): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 6074): 	at android.os.Binder.execTransact(Binder.java:454),
D/DotMatrix( 1311): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1311): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1219): reapply : com.google.android.gms 4 40
,W/System  ( 6074): Ignoring header User-Agent because its value was null.,
,D/libc    ( 6074): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
,D/libc    ( 6074): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 6074): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
,D/libc    ( 6074): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 6074): [NET] android_getaddrinfo_proxy+
D/libc    ( 6074): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  394): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024,
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,D/libc    (  394): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  394): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 6074): [NET] android_getaddrinfo_proxy-, success
,W/Atfwd_Sendcmd(  429): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  429): AtCmdFwd service not published, waiting... retryCnt : 5
,W/Atfwd_Sendcmd(  429): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  429): AtCmdFwd service not published, waiting... retryCnt : 2
,W/Atfwd_Sendcmd(  429): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  429): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  429): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  968): acquireWL(148a7082): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 968 1000 null
I/IntentController( 1219): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/BatteryService(  968): n_update end
D/HeadsetStateMachine( 2945): Disconnected process message: 10, size: 0
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  968): releaseWL(148a7082): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1219): closing low battery warning: level=100
D/DotMatrix( 1311): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  968): updateBatteryInfo
D/UsbnetService(  968): BroadcastReceiver::onReceive+
D/NotificationService(  968): plugged=true pluggin=true
D/UsbnetService(  968): onReceive BATTERY_CHANGED
D/PMS     (  968): runPSCheck
,D/UsbnetService(  968):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  968): Checking...
D/UsbnetService(  968): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  968): >> updateStatus
D/WifiController(  968): handleMessage: E msg.what=155652
D/WifiController(  968): battery changed pluggedType: 2
D/WifiController(  968): processMsg: DeviceActiveState
D/PowerUI ( 1219): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  968): processMsg: StaEnabledState
I/HtcPowerSaver(  968): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  968): processMsg: DefaultState
I/HtcPowerSaver(  968): << updateStatus
D/WifiController(  968): handleMessage: X
,I/BatteryController( 1219): status:5 level:100 unsupport:false plugged:true,
,E/PNP_UPDATERD(  387): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1543): MSG_CHECK_DELETION >>
D/ContactMessageStore( 1543): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1543): sku_id=118
D/ContactMessageStore( 1543): MSG_CHECK_DELETION <<
,D/ContactMessageStore( 1543): start background delete task...
,D/ContactMessageStore( 1543): size: 0 , 0
,D/ContactMessageStore( 1543): Background delete complete
,D/PMS     (  968): acquireWL(33c5b393): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 968 1000 null
I/BatteryService(  968): n_update end
D/PMS     (  968): releaseWL(33c5b393): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HeadsetStateMachine( 2945): Disconnected process message: 10, size: 0
I/IntentController( 1219): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1219): closing low battery warning: level=100
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  968): updateBatteryInfo
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  968): plugged=true pluggin=true
D/DotMatrix( 1311): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  968): runPSCheck
D/UsbnetService(  968): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  968): Checking...
D/UsbnetService(  968): onReceive BATTERY_CHANGED
I/HtcPowerSaver(  968): >> updateStatus
D/UsbnetService(  968):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/WifiController(  968): battery changed pluggedType: 2
D/UsbnetService(  968): BroadcastReceiver::onReceive-
D/WifiController(  968): handleMessage: E msg.what=155652
D/WifiController(  968): processMsg: DeviceActiveState
D/WifiController(  968): processMsg: StaEnabledState
D/WifiController(  968): processMsg: DefaultState
D/WifiController(  968): handleMessage: X
D/PowerUI ( 1219): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  968): updateStatus (8000,100,-1,false,false,false,-1),
I/HtcPowerSaver(  968): << updateStatus
,I/BatteryController( 1219): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  968): acquireWL(3e966fd0): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 968 1000 WorkSource{1000}
V/AlarmManager(  968): sending alarm PendingIntent{fcb3c46: PendingIntentRecord{a0a2e07 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=397783, Int=0
V/AlarmManager(  968): sending alarm PendingIntent{322d44ee: PendingIntentRecord{265b0d8f android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=804949, Int=0
,V/AlarmManager(  968): sending alarm PendingIntent{6ff2bc9: PendingIntentRecord{207312ce com.android.bluetooth broadcastIntent}}, i=com.android.bluetooth.btservice.action.ALARM_WAKEUP, t=2, cnt=1, w=938881, Int=0
,I/ActivityManager(  968): Start proc com.htc.cs.pns for service com.htc.cs.pns/com.htc.lib1.cs.push.service.UpdateRegistrationService: pid=6840 uid=10071 gids={50071, 9997, 1028, 1015, 3003} abi=armeabi-v7a
V/AlarmManager(  968): sending alarm PendingIntent{3a0df5ef: PendingIntentRecord{1ebab8fc com.htc.cs.pns startService}}, i=null, t=1, cnt=1, w=1454421339152, Int=0
I/bt-btm  ( 2945): Received oneshot timer event complete
D/PMS     (  968): acquireWL(8c5bb85): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 2945 1002 null
I/bt-btm  ( 2945): btm_ble_timeout
I/bt-btm  ( 2945): btm_gen_resolvable_private_addr
,D/bt-btm  ( 2945): btm_ble_rand_enc_complete
I/bt-btm  ( 2945): btm_gen_resolve_paddr_low
,D/bt-smp  ( 2945): smp_encrypt_data
W/bt-smp  ( 2945): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 2945): Plain text(LSB ~ MSB) = d3 47 52 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 2945): Encrypted text(LSB ~ MSB) = 79 75 16 f6 07 12 4f 6c 2c b8 8d 1b a0 cd 09 f5 
I/bt-btm  ( 2945): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 2945): Stopping oneshot timer
D/bt-btm  ( 2945): Starting oneshot timer type:103 timeout:900s
,D/PMS     (  968): releaseWL(3e966fd0): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1219): Weather sync is On
W/WeatherTimeKeeper( 1219): [refreshWeatherData] no weather data
,E/cutils-trace( 6862): Error opening trace file: Permission denied (13),
I/dex2oat ( 6862): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.htc.cs.pns/app_push_lib/plugin-deploy.jar --oat-fd=22 --oat-location=/data/data/com.htc.cs.pns/app_push_dex/plugin-deploy.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
I/dex2oat ( 6862): dex2oat: override thread count:4
,I/dex2oat ( 6862): dex2oat took 685.498ms (threads: 4)
,I/PushClient( 6840): ApplicationMonitor {2c5952b4}: logBasicAppInfo(): PackageName:             com.htc.cs.pns
,I/PushClient( 6840): ApplicationMonitor {2c5952b4}: logBasicAppInfo(): ProcessName:             com.htc.cs.pns
I/PushClient( 6840): ApplicationMonitor {2c5952b4}: logBasicAppInfo(): VersionName:             1.2.853019,
I/PushClient( 6840): ApplicationMonitor {2c5952b4}: logBasicAppInfo(): VersionCode:             148001224
I/PushClient( 6840): ApplicationMonitor {2c5952b4}: logBasicAppInfo(): ApplicationPath:         /system/priv-app/PNSClient/PNSClient.apk
I/PushClient( 6840): ApplicationMonitor {2c5952b4}: logBasicAppInfo(): AppFileDataPath:         /data/data/com.htc.cs.pns/files
I/PushClient( 6840): ApplicationMonitor {2c5952b4}: logBasicAppInfo(): Htc_SECURITY_DEBUG_flag: false
I/PushClient( 6840): ApplicationMonitor {2c5952b4}: logBasicAppInfo(): Htc_DEBUG_flag:          false
I/PushClient( 6840): ApplicationMonitor {2c5952b4}: logBasicAppInfo(): BuildConfig.DEBUG:       false
,I/PushClient( 6840): PnsModel {16b48387}: update(): Update registration caused by: alarm
,D/PMS     (  968): releaseWL(8c5bb85): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 null,
,I/PushClient( 6840): PnsConfigModel {b5d1aa}: <init>(): Use dm-client for provisioning.
,W/System.err( 6840): SLF4J: Failed to load class "org.slf4j.impl.StaticLoggerBinder".
,W/System.err( 6840): SLF4J: Defaulting to no-operation (NOP) logger implementation
W/System.err( 6840): SLF4J: See http://www.slf4j.org/codes.html#StaticLoggerBinder for further details.
,W/ContextImpl( 6840): Implicit intents with startService are not safe: Intent { act=com.htc.cs.dm.intent.action.BIND_CORE_SERVICE } android.content.ContextWrapper.bindService:538 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 
,I/ActivityManager(  968): Start proc com.htc.cs.dm for service com.htc.cs.dm/.config.service.ConfigManagerBoundService: pid=6870 uid=10099 gids={50099, 9997, 3003} abi=arm64-v8a
,I/art     (  406): Explicit concurrent mark sweep GC freed 8638(367KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 402us total 56.875ms
,I/art     (  406): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 244us total 25.526ms
,I/DeviceManagement( 6870): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.2.848686;250001208] pid=6870 dbg=false s=true,
,I/art     (  406): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 177us total 26.837ms
,I/DeviceManagement( 6870): ConfigManagerBoundService: *** getConfig: appID=com.htc.cs.pns options=Bundle[EMPTY_PARCEL]
I/DeviceManagement( 6870): ConfigManagerBoundService: Caller: uid=com.htc.cs.pns (10071) packages=[com.htc.cs.pns]
,I/DeviceManagement( 6870): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[EMPTY_PARCEL], appID=com.htc.cs.pns}]],
,I/DeviceManagement( 6870): WorkflowService: Starting workflow service,
,I/DeviceManagement( 6870): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@34fb77c6] args=[Bundle[mParcelledData.dataSize=88]],
I/DeviceManagement( 6870): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=88]
,I/DeviceManagement( 6870): ModelRegistry: Loading model meta data from resources...,
,I/DeviceManagement( 6870): ConfigManagerController: *** getConfig: appID=com.htc.cs.pns includeMeta=false
,I/DeviceManagement( 6870): SessionStateController: Checking invariants...
,I/DeviceManagement( 6870): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true,
,I/DeviceManagement( 6870): SessionStateController: Checking invariants...
,I/DeviceManagement( 6870): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.pns includeMeta=false,
,I/DeviceManagement( 6870): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@34fb77c6],
,I/DeviceManagement( 6870): WorkflowService: Stopping workflow service,
,D/Process (  968): killProcessQuiet, pid=6530
I/ActivityManager(  968): Killing 6530:com.test.thalitest/u0a366 (adj 15): empty #17
,D/Process (  968): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/PushClient( 6840): PnsModel {16b48387}: update(): The registration record has not expired yet. No need to update.,
,I/ActivityManager(  968): Recipient 6530
,E/InputEventReceiver( 1398): Looper::removeFd(68) is failed, result(0), input channel 'ClientState{3062b255 uid 10366 pid 6530} (c)'
,D/Process (  968): killProcessQuiet, pid=6465
I/ActivityManager(  968): Killing 6465:com.google.android.gms.unstable/u0a24 (adj 15): empty #17
,D/Process (  968): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  968): Recipient 6465
,D/PMS     (  968): acquireWL(92fcb7e): PARTIAL_WAKE_LOCK  *alarm* 0x1 968 1000 WorkSource{10024}
V/AlarmManager(  968): sending alarm PendingIntent{1ace38df: PendingIntentRecord{1a9c592c com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.MCS_HEARTBEAT, t=2, cnt=1, w=936700, Int=0
,V/AlarmManager(  968): sending alarm PendingIntent{1bc58ff5: PendingIntentRecord{1cdae23f com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1454421690820, Int=0
,D/PMS     (  968): acquireWL(1179218a): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1795 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  968): releaseWL(1179218a): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,W/ContextImpl( 6765): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 ,
,D/PMS     (  968): releaseWL(92fcb7e): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000},
,D/PowerUsageList:PowerUsageHelper( 6765): MY_DEBUG = false
,D/PowerUsageService( 6765): repeat time = 1454422590867
,I/PowerUsageList:PowerUsageHelper( 6765): PowerProfile::POWER_SCREEN_FULL = 154.8,
,D/PowerUsageList:BatterySipperExt( 6765): gen(), null == sipper.uidObj, userId = 0,
,D/GCM     ( 1795): Message class com.google.f.a.a.i,
D/PMS     (  968): acquireWL(2a0bdc18): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1795 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  968): releaseWL(2a0bdc18): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  968): acquireWL(16ac3671): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 968 1000 WorkSource{1000}
V/AlarmManager(  968): sending alarm PendingIntent{fcb3c46: PendingIntentRecord{a0a2e07 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=997782, Int=0
V/AlarmManager(  968): sending alarm PendingIntent{2c4fcc56: PendingIntentRecord{ec064d7 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1454421732888, Int=0
D/SmartSyncUtils( 6765): isEpsOn(), nState = 0,
,D/PMS     (  968): acquireWL(3beea1c4): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 6765 1000 null
,D/SmartSyncScreenOnOffTimeReceiver( 6765): [updateNmRange] bManual = false
,D/SmartSyncScreenOnOffTimeReceiver( 6765): [updateNmRange] USERNIGHT_TIMESTART = 1, USERNIGHT_TIMEEND = 7, nStart = 1, nEnd = 7, bNormalRange = true
,D/PMS     (  968): releaseWL(16ac3671): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/SmartSyncScreenOnOffTimeReceiver( 6765): AlarmOnTime = -1
,D/SmartSyncScreenOnOffTimeReceiver( 6765): SettingOnTime = 1454479200000, randomSettingOnTime = 1454476460000
,D/SmartSyncScreenOnOffTimeReceiver( 6765): SettingOffTime = 1454457600000, randomSettingOffTime = 1454460531000
D/SmartSyncScreenOnOffTimeReceiver( 6765): bDayMode = false
,D/SmartSyncScreenOnOffTimeReceiver( 6765): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 6765): bNightModeTurnOffOnce = false
,D/WeatherUtility( 1219): Weather sync is On
W/WeatherTimeKeeper( 1219): [refreshWeatherData] no weather data
,D/PMS     (  968): releaseWL(3beea1c4): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/PMS     (  968): acquireWL(1b7cc8ad): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 968 1000 null,
I/BatteryService(  968): n_update end
D/PMS     (  968): releaseWL(1b7cc8ad): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  968): updateBatteryInfo
D/PMS     (  968): runPSCheck
D/HtcPowerSaver(  968): Checking...
I/HtcPowerSaver(  968): >> updateStatus
,I/HtcPowerSaver(  968): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  968): << updateStatus
,I/IntentController( 1219): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  968): plugged=true pluggin=true
D/DotMatrix( 1311): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1311): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/WifiController(  968): battery changed pluggedType: 2
D/UsbnetService(  968): BroadcastReceiver::onReceive+
D/UsbnetService(  968): onReceive BATTERY_CHANGED
D/UsbnetService(  968):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  968): BroadcastReceiver::onReceive-
D/WifiController(  968): handleMessage: E msg.what=155652
D/WifiController(  968): processMsg: DeviceActiveState
D/WifiController(  968): processMsg: StaEnabledState
D/WifiController(  968): processMsg: DefaultState
D/WifiController(  968): handleMessage: X
D/HeadsetStateMachine( 2945): Disconnected process message: 10, size: 0
D/PowerUI ( 1219): closing low battery warning: level=100
,D/PowerUI ( 1219): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/BatteryController( 1219): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  387): inotify_add_watch failed. (No such file or directory)
,I/UsageStatsService(  968): User[0] Flushing usage stats to disk
,TIME-OUT KILL (timeout was 1200000ms)
```
