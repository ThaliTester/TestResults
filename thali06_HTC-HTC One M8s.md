#### Test 62548124ca582f4_thali06_HTC-HTC One M8s Logs


```
--------- beginning of main
03-19 11:45:14.249   402  1160 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
03-19 11:45:14.269   402  1160 D DrmWidevineDash: OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x15
03-19 11:45:14.269   402  1160 D DrmWidevineDash: Service_Initialize: starts!
03-19 11:45:14.269   402  1160 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
03-19 11:45:14.269   402  1160 D QSEECOMAPI: : App is not loaded in QSEE
03-19 11:45:14.269   402  1160 E QSEECOMAPI: : Error::Cannot open the file /vendor/firmware/widevine.mdt
03-19 11:45:14.269   402  1160 E QSEECOMAPI: : Error::Loading image failed with ret = -1
03-19 11:45:14.269   402  1160 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
03-19 11:45:14.269   402  1160 D QSEECOMAPI: : App is not loaded in QSEE
03-19 11:45:14.299   402  1160 D QSEECOMAPI: : Loaded image: APP id = 6
03-19 11:45:14.299   402  1160 D DrmWidevineDash: Service_Initialize: ends! returns 0
03-19 11:45:14.309   402  1160 D QSAPPSVER: qsapps_get_capabilities: Capability from secure side: 0x0
03-19 11:45:14.309   402  1160 D QSAPPSVER: qsapps_get_capabilities: returns 0
03-19 11:45:14.309   402  1160 D DrmWidevineDash: OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf4859000
03-19 11:45:14.309   402  1160 E DrmWidevineDash: sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf4859000
03-19 11:45:14.309   402  1160 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
03-19 11:45:14.309   542   560 D DrmLibTime: got the req here! ret=0
03-19 11:45:14.309   542   560 D DrmLibTime: command id, time_cmd_id = 770
03-19 11:45:14.309   542   560 D DrmLibTime: time_getutcsec starts!
03-19 11:45:14.309   542   560 D DrmLibTime: QSEE Time Listener: time_getutcsec
03-19 11:45:14.309   542   560 D DrmLibTime: QSEE Time Listener: get_utc_seconds
03-19 11:45:14.309   542   560 D DrmLibTime: QSEE Time Listener: time_get_modem_time
03-19 11:45:14.309   542   560 D DrmLibTime: QSEE Time Listener: Checking if ATS_MODEM is set or not.
03-19 11:45:14.319   542   560 E QC-time-services: Receive Passed == base = 13, unit = 1, operation = 2, result = 0
03-19 11:45:14.319   542   560 D DrmLibTime: QSEE Time Listener: ATS_MODEM is not set. Fallback to Android system time.
03-19 11:45:14.319   542   560 D DrmLibTime: QSEE Time Listener: Retrieved Android system time: 1458384314
03-19 11:45:14.319   542   560 D DrmLibTime: time_getutcsec returns 0, sec = 1458384314; nsec = 0
03-19 11:45:14.319   542   560 D DrmLibTime: time_getutcsec finished! 
03-19 11:45:14.319   542   560 D DrmLibTime: iotcl_continue_command finished! and return 0 
03-19 11:45:14.319   542   560 D DrmLibTime: before calling ioctl to read the next time_cmd
03-19 11:45:14.319   472   579 E QC-time-services: Daemon: Time-services: Waiting to acceptconnection
03-19 11:45:14.319   402  1160 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
03-19 11:45:14.319  3363  3382 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
03-19 11:45:14.319   402  1160 D DrmWidevineDash: OEMCrypto_Initialize: ends! returns 0
03-19 11:45:14.319   402  1160 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
03-19 11:45:14.319   402  1160 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
03-19 11:45:14.319   402  1160 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
03-19 11:45:14.319   402  1160 D DrmWidevineDash: hlos api version =  9
03-19 11:45:14.319   402  1160 D DrmWidevineDash: tz api version =  9
03-19 11:45:14.319   402  1160 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 9
03-19 11:45:14.319   402  1160 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: starts!
03-19 11:45:14.319   402  1160 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,03-19 11:45:14.349   952  1151 E WifiStateMachine: handleMessage: E msg.what=131155
03-19 11:45:14.349   952  1151 E WifiStateMachine: processMsg: ConnectedState
03-19 11:45:14.349   952  1151 E WifiStateMachine:  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-58 f=2457 sc=60 link=150 tx=10.3, 0.0, 0.0  rx=7.9 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1904566284] gl hn u24 rssi=-53 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
03-19 11:45:14.349   952  1151 E WifiStateMachine: processMsg: L2ConnectedState
03-19 11:45:14.349   952  1151 E WifiStateMachine:  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-58 f=2457 sc=60 link=150 tx=10.3, 0.0, 0.0  rx=7.9 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1904566283] gl hn u24 rssi=-53 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
03-19 11:45:14.349   952  1151 E WifiStateMachine:  get link layer stats 0
03-19 11:45:14.349   952  1151 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
03-19 11:45:14.349  1389  1389 D wpa_supplicant: wlan0: Control interface command 'SIGNAL_POLL'
03-19 11:45:14.359   402  1160 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
03-19 11:45:14.359   402  1160 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: ends! returns 0
03-19 11:45:14.359   402  1160 D WVCdm   : OEMCrypto_Initialize Level 1 success. I will use level 1.
03-19 11:45:14.359   402  1160 D DrmWidevineDash: OEMCrypto_OpenSession: starts! SID=0xf4982928
03-19 11:45:14.359   402  1160 D DrmWidevineDash: OEMCrypto_OpenSession Session ID = 0
03-19 11:45:14.359   402  1160 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
03-19 11:45:14.359   402  1160 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
03-19 11:45:14.359   402  1160 D DrmWidevineDash: OEMCrypto_OpenSession SID = 1
03-19 11:45:14.359   402  1160 D DrmWidevineDash: OEMCrypto_OpenSession: ends! returns 0
03-19 11:45:14.359   402  1160 D DrmWidevineDash: OEMCrypto_GetRandom: starts! randomData=0xab792a88, dataLength=8
03-19 11:45:14.359   402  1160 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
03-19 11:45:14.359  3342  3342 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
03-19 11:45:14.359   402  1160 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
03-19 11:45:14.359   402  1160 D DrmWidevineDash: OEMCrypto_GetRandom: ends! returns 0
03-19 11:45:14.359   402  1160 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: starts! SID=1, wrapped_rsa_key=0xab72d2e0, wrapped_rsa_key_length=1280
03-19 11:45:14.359   402  1160 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
03-19 11:45:14.359   402  1160 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
03-19 11:45:14.359   402  1160 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: ends! returns 0
03-19 11:45:14.359   402  1160 I WVCdm   : CdmEngine::QueryKeyControlInfo
03-19 11:45:14.359  3363  3382 D libc    : [NET] android_getaddrinfofornet+,hn 18(0x7777772e676f6f),sn(),hints(known),family 0,flags 4
03-19 11:45:14.359  3363  3382 D libc    : [NET] android_getaddrinfofornet-, err=8
03-19 11:45:14.369  3363  3382 D libc    : [NET] android_getaddrinfofornet+,hn 18(0x7777772e676f6f),sn(),hints(known),family 0,flags 1024
03-19 11:45:14.369  3363  3382 D libc    : [NET] android_getaddrinfofornet-, pass to proxy
03-19 11:45:14.369  3363  3382 D libc    : [NET] android_getaddrinfo_proxy+
03-19 11:45:14.369   402  1060 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
03-19 11:45:14.369   402  1060 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
03-19 11:45:14.369   402  1060 I WVCdm   : CdmEngine::GenerateKeyRequest
03-19 11:45:14.369   402  1060 D DrmWidevineDash: OEMCrypto_GetDeviceID: starts! deviceID=0xab78c6b0, idLength=0xf4a826f8
03-19 11:45:14.369   402  1060 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
03-19 11:45:14.369  3363  3382 D libc    : [NET] android_getaddrinfo_proxy get netid:0
03-19 11:45:14.369   395  3417 D libc    : [NET] android_getaddrinfofornet+,hn 18(0x7777772e676f6f),sn(),hints(known),family 0,flags 1024
03-19 11:45:14.369   395  3417 D libc    : [NET] _dns_getaddrinfo+, netid:100, mark:917604
03-19 11:45:14.389  1389  1389 I wpa_supplicant: environment dirty rate=33 [3][1][0]
03-19 11:45:14.389   952  1151 E WifiStateMachine: fetchRssiLinkSpeedAndFrequencyNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 150
03-19 11:45:14.389   952  1151 E WifiStateMachine: fetchRssiLinkSpeedAndFrequencyNative rssi=-57 linkspeed=150
03-19 11:45:14.389   952  1151 E WifiConfigStore: updateConfiguration freq=2457 BSSID=f4:f2:6d:22:99:3e RSSI=-57 "NG700"WPA_PSK
03-19 11:45:14.389   952  1151 E WifiStateMachine: calculateWifiScore freq=2457 speed=150 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=6.64 txretriesrate=0.00 rxrate=5.47 userTriggerdPenalty0
03-19 11:45:14.389   952  1151 E WifiStateMachine:  good link -> stuck count =0
03-19 11:45:14.389   952  1151 E WifiStateMachine:  badRSSI count0 lowRSSI count0 --> score 60
03-19 11:45:14.389   952  1151 E WifiStateMachine:  isHighRSSI       ---> score=65
03-19 11:45:14.389   952  1168 D WifiWatchdogStateMachine: RSSI current: 3 new: -57, 3
03-19 11:45:14.389   952  1151 E WifiStateMachine: handleMessage: X
--------- beginning of system
03-19 11:45:14.389  1219  1219 D WIFI_ICON: updateWifiState: RSSI_CHANGED 3 -> 3
03-19 11:45:14.389  1219  1219 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
03-19 11:45:14.389   402  1060 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
03-19 11:45:14.389   402  1060 D DrmWidevineDash: OEMCrypto_GetDeviceID: ends! returns 0
03-19 11:45:14.389   402  1060 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: starts!
03-19 11:45:14.389   402  1060 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
03-19 11:45:14.389   402  1060 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
03-19 11:45:14.389   402  1060 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: is_supported = 1
03-19 11:45:14.389   402  1060 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: wv_app_version = 24
03-19 11:45:14.389   402  1060 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: ends! returns 0
03-19 11:45:14.389   402  1060 D DrmWidevineDash: OEMCrypto_GetHDCPCapability: starts!, current = 0xf4a8270e, maximum = 0xf4a8270f
03-19 11:45:14.389   402  1060 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
03-19 11:45:14.399   402  1060 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
03-19 11:45:14.399   402  1060 D DrmWidevineDash: OEMCrypto_GetHDCPCapability: ends! returns 0
03-19 11:45:14.399   402  1060 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
03-19 11:45:14.399   402  1060 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
03-19 11:45:14.399   402  1060 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
03-19 11:45:14.399   402  1060 D DrmWidevineDash: hlos api version =  9
03-19 11:45:14.399   402  1060 D DrmWidevineDash: tz api version =  9
03-19 11:45:14.399   402  1060 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 9
03-19 11:45:14.399   402  1060 D DrmWidevineDash: OEMCrypto_GenerateNonce: starts! SID=1, nonce=0xf4a8277c
03-19 11:45:14.399   402  1060 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
03-19 11:45:14.399   402  1060 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
03-19 11:45:14.399   402  1060 D DrmWidevineDash: OEMCrypto_GenerateNonce: ends! returns 0
03-19 11:45:14.399   402  1060 D WVCdm   : PrepareKeyRequest: nonce=4115920682
03-19 11:45:14.399   402  1060 D DrmWidevineDash: OEMCrypto_GenerateRSASignature starts! SID=1, message=0xab72d2e0
03-19 11:45:14.399   402  1060 D DrmWidevineDash: message_length=1611, signature=0xab717528, signature_length=0xf4a826dc
03-19 11:45:14.399   402  1060 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
03-19 11:45:14.399  3342  3342 I LibraryLoader: Time to load native libraries: 15 ms (timestamps 1446-1461)
03-19 11:45:14.399  3342  3342 I LibraryLoader: Expected native library version number "",actual native library version number ""
03-19 11:45:14.409  3342  3342 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {ecb800d}
03-19 11:45:14.409  3342  3342 I LibraryLoader: Expected native library version number "",actual native library version number ""
03-19 11:45:14.409  3342  3342 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
03-19 11:45:14.419  3342  3342 I BrowserStartupController: Initializing chromium process, singleProcess=true
03-19 11:45:14.419  3342  3342 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-19 11:45:14.429  3342  3342 E SysUtils: ApplicationContext is null in ApplicationStatus
03-19 11:45:14.449  3342  3342 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
03-19 11:45:14.459  3342  3342 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-19 11:45:14.459  3342  3342 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-19 11:45:14.459  3342  3342 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
03-19 11:45:14.459  3342  3342 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.01
03-19 11:45:14.459  3342  3342 I Adreno-EGL: Build Date: 03/09/15 Mon
03-19 11:45:14.459  3342  3342 I Adreno-EGL: Local Branch: 
03-19 11:45:14.459  3342  3342 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
03-19 11:45:14.459  3342  3342 I Adreno-EGL: Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
03-19 11:45:14.459  3342  3342 I Adreno-EGL:                  d74aa161a12b9c6fc6332151
03-19 11:45:14.509   402  1060 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
03-19 11:45:14.509   402  1060 D DrmWidevineDash: OEMCrypto_GenerateRSASignature returns 0
03-19 11:45:14.509   402  1645 I WVCdm   : CdmEngine::CloseSession
03-19 11:45:14.509   402  1645 D DrmWidevineDash: OEMCrypto_CloseSession: starts! SID=1
03-19 11:45:14.509   402  1645 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
03-19 11:45:14.509   402  1645 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
03-19 11:45:14.509   402  1645 D DrmWidevineDash: OEMCrypto_CloseSession: ends! returns 0
03-19 11:45:14.509   402  1645 I WVCdm   : L3 Terminate.
03-19 11:45:14.509   402  1645 D DrmWidevineDash: OEMCrypto_Terminate: starts!
03-19 11:45:14.509   402  1645 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
03-19 11:45:14.509   402  1645 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
03-19 11:45:14.509   402  1645 D DrmWidevineDash: Service_Uninitialize: starts!
03-19 11:45:14.509   402  1645 D QSEECOMAPI: : QSEECom_dealloc_memory 
03-19 11:45:14.509   402  1645 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 6
03-19 11:45:14.509   402  1645 D DrmWidevineDash: Service_Uninitialize: ends! returns 0x0
03-19 11:45:14.509   402  1645 D DrmWidevineDash: OEMCrypto_Terminate: ends! returns 0
03-19 11:45:14.519  3342  3433 W AudioManagerAndroid: Requires BLUETOOTH permission
03-19 11:45:14.529  3342  3342 I NSApplication: Starting up...
03-19 11:45:14.559   952  2376 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=3439 uid=10096 gids={50096, 9997, 3003, 1028, 1015} abi=arm64-v8a
03-19 11:45:14.559   952  2376 D Process : killProcessQuiet, pid=2641
03-19 11:45:14.559   952  2376 I ActivityManager: Killing 2641:com.htc.calendar/u0a10 (adj 15): empty #17
03-19 11:45:14.559   952  2376 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
03-19 11:45:14.599   395  3395 D libc    : [NET] _dns_getaddrinfo-, (NS_SUCCESS)
03-19 11:45:14.599   395  3395 D libc    : [NET] android_getaddrinfofornet-, SUCCESS
03-19 11:45:14.599  3305  3391 D libc    : [NET] android_getaddrinfo_proxy-, success
03-19 11:45:14.609  3420  3461 E cutils-trace: Error opening trace file: Permission denied (13)
03-19 11:45:14.649   952   983 I ActivityManager: Recipient 2641
03-19 11:45:14.659  3420  3420 D CustomizationManager: ====startRecUseTime====
03-19 11:45:14.659  3420  3420 D htc.customization.log.level:  is 
03-19 11:45:14.659  3420  3420 W CustomizationLogLevel: Level value is invalid, use default level 2
03-19 11:45:14.729  3420  3420 D CustomizationManager:  Read ACC file spent 0.043 (s)
03-19 11:45:14.739  3420  3420 D CIDMapFileReader: Parsing tag item name = HTC__001
03-19 11:45:14.739  3420  3420 D CIDMapFileReader: Parsing tag item name = HTC__102
03-19 11:45:14.739  3420  3420 D CIDMapFileReader: Parsing tag item name = HTC__Y13
03-19 11:45:14.739  3420  3420 D CIDMapFileReader: Parsing tag item name = HTC__032
03-19 11:45:14.739  3420  3420 D CIDMapFileReader: Parsing tag item name = HTC__M27
03-19 11:45:14.739  3420  3420 D CIDMapFileReader: Parsing tag item name = HTC__002
03-19 11:45:14.739  3420  3420 D CIDMapFileReader: Parsing tag item name = HTC__031
03-19 11:45:14.739  3420  3420 V CustomizationCIDLoader: full path : /system/customize/CID/HTC__102.xml
03-19 11:45:14.739  3420  3420 I CustomizationCIDLoader: Parsing tag category name = system
03-19 11:45:14.739  3420  3420 I CustomizationCIDLoader: Parsing tag category name = application
03-19 11:45:14.739  3420  3420 I CustomizationCIDLoader: Parsing tag category name = SettingsProvider
03-19 11:45:14.739  3420  3420 I CustomizationCIDLoader: Parsing tag category name = AutomotiveHome
03-19 11:45:14.739  3420  3420 I CustomizationCIDLoader: Parsing tag category name = AudioService
03-19 11:45:14.739  3420  3420 I CustomizationCIDLoader: Parsing tag category name = Settings
03-19 11:45:14.739  3420  3420 I CustomizationCIDLoader: Parsing tag category name = ACC
03-19 11:45:14.739  3420  3420 I CustomizationCIDLoader: add string-array item, value = 42507
03-19 11:45:14.739  3420  3420 I CustomizationCIDLoader: add string-array item, value = 21902
03-19 11:45:14.739  3420  3420 I CustomizationCIDLoader: add string-array item, value = 26006:26001.26002.26003
03-19 11:45:14.739  3420  3420 I CustomizationCIDLoader: add string-array item, value = 23420
03-19 11:45:14.739  3420  3420 I CustomizationCIDLoader: add string-array item, value = 22299
03-19 11:45:14.739  3420  3420 I CustomizationCIDLoader: add string-array item, value = 24002
03-19 11:45:14.739  3420  3420 I CustomizationCIDLoader: add string-array item, value = 23210
03-19 11:45:14.739  3420  3420 I CustomizationCIDLoader: add string-array item, value = 23205
03-19 11:45:14.739  3420  3420 I CustomizationCIDLoader: add string-array item, value = 23806
03-19 11:45:14.739  3420  3420 I CustomizationCIDLoader: add string-array item, value = 23430
03-19 11:45:14.739  3420  3420 I CustomizationCIDLoader: add string-array item, value = 23408
03-19 11:45:14.739  3420  3420 I CustomizationCIDLoader: add string-array item, value = 27205
03-19 11:45:14.739  3420  3420 I CustomizationCIDLoader: add string-array item, value = 42507:C:1:0
03-19 11:45:14.739  3420  3420 I CustomizationCIDLoader: add string-array item, value = 21902:C:1:0
03-19 11:45:14.739  3420  3420 I CustomizationCIDLoader: add string-array item, value = 26006:D:1:0
03-19 11:45:14.739  3420  3420 I CustomizationCIDLoader: add string-array item, value = 23420:D:0:0
03-19 11:45:14.739  3420  3420 I CustomizationCIDLoader: add string-array item, value = 22299:D:0:0
03-19 11:45:14.739  3420  3420 I CustomizationCIDLoader: add string-array item, value = 24002:D:0:0
03-19 11:45:14.739  3420  3420 I CustomizationCIDLoader: add string-array item, value = 23210:D:2:0
03-19 11:45:14.739  3420  3420 I CustomizationCIDLoader: add string-array item, value = 23205:D:0:0
03-19 11:45:14.739  3420  3420 I CustomizationCIDLoader: add string-array item, value = 23806:D:0:0
03-19 11:45:14.739  3420  3420 I CustomizationCIDLoader: add string-array item, value = 23430:C:1:0
03-19 11:45:14.739  3420  3420 I CustomizationCIDLoader: add string-array item, value = 23408:C:1:0
03-19 11:45:14.739  3420  3420 I CustomizationCIDLoader: add string-array item, value = 27205:C:1:0
03-19 11:45:14.739  3420  3420 D CustomizationManager:  Read CID file spent 0.083 (s)
03-19 11:45:14.739  3420  3420 D CustomizationManager:  All configurations done spent 0.083 (s)
03-19 11:45:14.779  1455  2002 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
03-19 11:45:14.779  1455  2002 I Prism.ItemManager: loadItems() com.htc.launcher.pageview.WidgetManager@118c2576 +
03-19 11:45:14.779  1455  2002 I Prism.WidgetManager: onLoadItems() +
03-19 11:45:14.789   952  2376 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 pid 3420 on display 0
03-19 11:45:14.789   952  1062 D PMS     : acquireHCC(3819c793): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 952 1000 null
03-19 11:45:14.789   952  1062 D PMS     : acquireHCC(2c7af3d0): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 952 1000 null
03-19 11:45:14.789   952   952 E WifiDataStallTracker: DATA_MONITOR_POLL true Token 1
03-19 11:45:14.799   952  2376 D PMS     : acquireWL(318f49ef): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 952 1000 null
03-19 11:45:14.809   952  3477 D WifiDataStallTracker: updateDataStallInfo: mDataStallTxRxSum={txSum=26 rxSum=19} preTxRxSum={txSum=15 rxSum=9}
03-19 11:45:14.809   952  3477 D WifiDataStallTracker: updateDataStallInfo: IN/OUT
03-19 11:45:14.809   952  3477 D WifiDataStallTracker: onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
03-19 11:45:14.809  1455  1455 I FeedHostManager: [onPause]
03-19 11:45:14.809  1455  1455 I FeedProviderManager: onPause
03-19 11:45:14.809  1455  1455 I FeedHostManager: [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@3dc734e7
03-19 11:45:14.809  1455  2417 I SocialFeedProvider: +onPause
03-19 11:45:14.809  1455  2417 I SocialFeedProvider: -onPause
03-19 11:45:14.819   952  1045 I AnimationUtil: isHTCRecent(ThaliTest/Recent screens.)/13
03-19 11:45:14.819   952   952 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 6
03-19 11:45:14.819   952   952 E WifiTrafficPoller:  packet count Tx=40 Rx=32
03-19 11:45:14.819   952   952 E WifiTrafficPoller: notifying of data activity 3
03-19 11:45:14.829  1219  1219 D WIFI_ICON: WifiActivity: 3
03-19 11:45:14.829  1219  1219 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
03-19 11:45:14.829   952  1499 W HtcSystemUPManager: HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
03-19 11:45:14.839   952  1694 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3478 uid=10195 gids={50195, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
03-19 11:45:14.849  1455  2002 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
03-19 11:45:14.919   952  2301 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=3501 uid=10167 gids={50167, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
03-19 11:45:14.919   952  2301 D Process : killProcessQuiet, pid=1768
03-19 11:45:14.919   952  2301 I ActivityManager: Killing 1768:com.google.android.googlequicksearchbox:search/u0a85 (adj 15): empty #17
03-19 11:45:14.919   952  2301 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
03-19 11:45:14.929   952  1043 D StatusBarManagerService: setSystemUiVisibility(0x8600)
03-19 11:45:14.929   952  1043 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
03-19 11:45:14.929   952  1043 D StatusBarManagerService: hiding MENU key
03-19 11:45:14.929  1455  1455 I TrimMemoryManager: [trimMemory] 20
03-19 11:45:15.009   952  1772 I ActivityManager: Recipient 1768
,03-19 11:45:15.049  3501  3501 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.,
,03-19 11:45:15.089  1455  2002 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.,
,03-19 11:45:15.169  3478  3478 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 240311750),
,03-19 11:45:15.219  1455  2002 W asset   : Copying FileAsset 0x55915d12d0 (zip:/data/app/com.gameloft.android.gdc-2/base.apk:/resources.arsc) to buffer size 405676 to make it aligned.,
,03-19 11:45:15.229   952   986 D Process : killProcessQuiet, pid=3072
03-19 11:45:15.229   952   986 I ActivityManager: Killing 3072:com.htc.widget.hmsproc1/u0a35 (adj 15): empty #17
03-19 11:45:15.229   952   986 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
03-19 11:45:15.229  3478  3478 I LibraryLoader: Time to load native libraries: 10 ms (timestamps 2288-2298)
,03-19 11:45:15.239  3478  3478 I LibraryLoader: Expected native library version number "",actual native library version number "",
,03-19 11:45:15.259  3478  3478 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3c94174e},
03-19 11:45:15.259  3478  3478 I LibraryLoader: Expected native library version number "",actual native library version number "",
,03-19 11:45:15.259  3478  3478 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0,
,03-19 11:45:15.289  1455  2002 I Prism.WidgetManager: onLoadItems() -
03-19 11:45:15.289  1455  2002 I Prism.ItemManager: loadItems() com.htc.launcher.pageview.WidgetManager@118c2576 -
,03-19 11:45:15.289  3478  3478 I BrowserStartupController: Initializing chromium process, singleProcess=true,
,03-19 11:45:15.289  3478  3478 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-19 11:45:15.289  3478  3478 E SysUtils: ApplicationContext is null in ApplicationStatus
,03-19 11:45:15.339   952  2301 I ActivityManager: Recipient 3072
,03-19 11:45:15.369  3478  3478 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty(),
,03-19 11:45:15.379  1407  2108 D PhoneApp: EVENT_QUERY_MO_PACKAGES
,03-19 11:45:15.379  1407  2108 D PhoneApp: -- N1 =0
03-19 11:45:15.379  1407  2108 D PhoneApp: -- N2 =0
,03-19 11:45:15.379  1407  2108 D PhoneApp: -- N3 =0
,03-19 11:45:15.379  3478  3478 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY),
03-19 11:45:15.379  3478  3478 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,03-19 11:45:15.379  3478  3478 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
03-19 11:45:15.379  3478  3478 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.01
03-19 11:45:15.379  3478  3478 I Adreno-EGL: Build Date: 03/09/15 Mon
03-19 11:45:15.379  3478  3478 I Adreno-EGL: Local Branch: 
03-19 11:45:15.379  3478  3478 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
03-19 11:45:15.379  3478  3478 I Adreno-EGL: Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
03-19 11:45:15.379  3478  3478 I Adreno-EGL:                  d74aa161a12b9c6fc6332151
,03-19 11:45:15.429   952  1694 W System.err: java.lang.Throwable: stack dump,
03-19 11:45:15.429   952  1694 W System.err: 	at java.lang.Thread.dumpStack(Thread.java:490)
03-19 11:45:15.429   952  1694 W System.err: 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
03-19 11:45:15.429   952  1694 W System.err: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
03-19 11:45:15.429   952  1694 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
,03-19 11:45:15.429   952  1044 D BluetoothManagerService: Message: MESSAGE_REGISTER_ADAPTER
03-19 11:45:15.429   952  1044 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@426cd39:true
03-19 11:45:15.429  3478  3539 D BluetoothAdapter: 502000133: getState() :  mService = null. Returning STATE_OFF
,03-19 11:45:15.549  3478  3478 W art     : Attempt to remove local handle scope entry from IRT, ignoring,
,03-19 11:45:15.559  3478  3478 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,03-19 11:45:15.569  3478  3478 D SystemWebViewEngine: CordovaWebView is running on device made by: HTC,
,03-19 11:45:15.579  3478  3478 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-19 11:45:15.579  3478  3478 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-19 11:45:15.629  3305  3391 I Babel   : connection state changed from UNKNOWN to CONNECTED,
,03-19 11:45:15.639  3478  3537 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup,
,03-19 11:45:15.649   952   986 D Process : killProcessQuiet, pid=3094
03-19 11:45:15.649   952   986 I ActivityManager: Killing 3094:com.htc.mms.backupagent/u0a76 (adj 15): empty #17
03-19 11:45:15.649   952   986 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.removeContentProvider:10141 
,03-19 11:45:15.689  3478  3478 D FindExtension: FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true,
,03-19 11:45:15.759  3478  3478 I InputMethodManager: [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@bab00d6, mServedView=org.apache.cordova.engine.SystemWebView{d94bf57 VFEDH.C. .F....I. 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@2eec2a44
,03-19 11:45:15.759  1219  1219 I PhoneStatusBar: setImeWindowStatus(false,false)
03-19 11:45:15.759   952  1479 I InputMethodManagerService: Disable input method client, pid=1455
03-19 11:45:15.759   952  1479 D StatusBarManagerService: swetImeWindowStatus vis=0 backDisposition=0
03-19 11:45:15.759   952  1479 I InputMethodManagerService: Enable input method client, pid=3478
,03-19 11:45:15.769   952  1694 I ActivityManager: Recipient 3094
,03-19 11:45:15.809  1357  1357 W XT9_C   : [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4),
03-19 11:45:15.809  1357  1357 I XT9_C   : [T9_ReleaseBuffer] Reset LDB#0
,03-19 11:45:15.809  1357  1357 I XT9_C   : [T9_ReleaseBuffer] Reset LDB#1
03-19 11:45:15.809  1357  1357 D XT9_C   : [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
,03-19 11:45:15.819  3478  3478 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3478,
,03-19 11:45:15.829   952   952 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 6,
03-19 11:45:15.829   952   952 E WifiTrafficPoller:  packet count Tx=45 Rx=36
,03-19 11:45:15.859   952   983 D PMS     : releaseWL(318f49ef): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,03-19 11:45:15.859   952  1045 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +1s50ms,
,03-19 11:45:15.899   952  1694 D Process : killProcessQuiet, pid=3118,
03-19 11:45:15.899   952  1694 I ActivityManager: Killing 3118:com.htc.demoflopackageinstaller/u0a16 (adj 15): empty #17
03-19 11:45:15.899   952  1694 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,03-19 11:45:15.929  3478  3478 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,03-19 11:45:16.019   952  1715 I ActivityManager: Recipient 3118
,03-19 11:45:16.019  1389  1389 D wpa_supplicant: nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
03-19 11:45:16.019  1389  1389 D wpa_supplicant: wlan0: nl80211: New scan results available
03-19 11:45:16.019  1389  1389 D wpa_supplicant: nl80211: Scan included frequencies: 2412 2417 2422 2427 2432 2437 2442 2447 2452 2457 2462 2467 2472 5180 5200 5220 5240 5260 5280 5300 5320 5500 5520 5540 5560 5580 5600 5620 5640 5660 5680 5700
03-19 11:45:16.019  1389  1389 D wpa_supplicant: wlan0: Event SCAN_RESULTS (3) received
,03-19 11:45:16.019  1389  1389 I wpa_supplicant: Got an original EVENT_SCAN_RESULTS
03-19 11:45:16.019  1389  1389 D wpa_supplicant: wlan0: Scan completed in 6.330059 seconds
,03-19 11:45:16.019  1389  1389 D wpa_supplicant: nl80211: Associated on 2457 MHz
03-19 11:45:16.029   952  1151 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:14146 com.android.server.wifi.WifiStateMachine.handleMediaLinkEvent:14311 com.android.server.wifi.WifiStateMachine.access$6000:268 com.android.server.wifi.WifiStateMachine$SupplicantStartedState.processMessage:8091 
03-19 11:45:16.019  1389  1389 D wpa_supplicant: nl80211: Associated with f4:f2:6d:22:99:3e
,03-19 11:45:16.019  1389  1389 D wpa_supplicant: nl80211: Received scan results (19 BSSes),
,03-19 11:45:16.019  1389  1389 D wpa_supplicant: nl80211: Scan results indicate BSS status with f4:f2:6d:22:99:3e as associated,
,03-19 11:45:16.019  1389  1389 I wpa_supplicant: [NULL] 00:1e:4a:8f:e3:6b freq=5320 level=-50
03-19 11:45:16.019  1389  1389 I wpa_supplicant: [NULL] 00:1e:4a:8f:e3:6f freq=5320 level=-50
03-19 11:45:16.019  1389  1389 I wpa_supplicant: [NULL] f0:f2:6d:22:99:3e freq=2457 level=-52
03-19 11:45:16.019  1389  1389 I wpa_supplicant: [NULL] f4:f2:6d:22:99:3e freq=2457 level=-57
03-19 11:45:16.019  1389  1389 I wpa_supplicant: [NULL] 00:1f:27:54:70:c1 freq=2437 level=-53
03-19 11:45:16.019  1389  1389 I wpa_supplicant: [NULL] 00:1f:27:54:70:c0 freq=2437 level=-53
03-19 11:45:16.019  1389  1389 I wpa_supplicant: [NULL] 00:1e:4a:8f:e3:60 freq=2412 level=-63
03-19 11:45:16.019  1389  1389 I wpa_supplicant: [NULL] 00:1e:4a:8f:e3:64 freq=2412 level=-63
03-19 11:45:16.019  1389  1389 I wpa_supplicant: [NULL] 00:1e:4a:8f:e3:62 freq=2412 level=-63
03-19 11:45:16.019  1389  1389 I wpa_supplicant: [NULL] 00:1f:27:54:dd:ef freq=5240 level=-74
03-19 11:45:16.019  1389  1389 I wpa_supplicant: [NULL] 00:1f:27:54:dd:e0 freq=2437 level=-71
03-19 11:45:16.019  1389  1389 I wpa_supplicant: [NULL] 00:1f:27:54:dd:e2 freq=2437 level=-71
03-19 11:45:16.019  1389  1389 I wpa_supplicant: [NULL] 00:22:0d:46:1c:a0 freq=2462 level=-73
,03-19 11:45:16.019  1389  1389 I wpa_supplicant: [NULL] 00:22:0d:46:1c:a4 freq=2462 level=-74
03-19 11:45:16.019  1389  1389 I wpa_supplicant: [NULL] 62:45:b0:73:93:45 freq=5240 level=-86
03-19 11:45:16.019  1389  1389 I wpa_supplicant: [NULL] 00:1e:4a:8f:e3:63 freq=2412 level=-59
03-19 11:45:16.019  1389  1389 I wpa_supplicant: [NULL] 00:1f:27:54:dd:e3 freq=2437 level=-70
03-19 11:45:16.019  1389  1389 I wpa_supplicant: [NULL] 00:22:0d:46:1c:a3 freq=2462 level=-75
03-19 11:45:16.019  1389  1389 I wpa_supplicant: [NULL] 00:1e:4a:8f:df:d3 freq=2437 level=-82
03-19 11:45:16.019  1389  1389 D wpa_supplicant: wlan0: BSS: Start scan result update 2
03-19 11:45:16.019  1389  1389 D wpa_supplicant: wlan0: BSS: Add new id 10 BSSID 00:1e:4a:8f:e3:6b SSID '\x00'
03-19 11:45:16.019  1389  1389 D wpa_supplicant: wlan0: BSS: Add new id 11 BSSID 00:1e:4a:8f:e3:6f SSID '\x00'
03-19 11:45:16.019  1389  1389 D wpa_supplicant: wlan0: BSS: Add new id 12 BSSID 00:1e:4a:8f:e3:60 SSID '\x00'
03-19 11:45:16.019  1389  1389 D wpa_supplicant: wlan0: BSS: Add new id 13 BSSID 00:1e:4a:8f:e3:64 SSID '\x00'
03-19 11:45:16.019   952  1646 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 10 00:1e:4a:8f:e3:6b]
03-19 11:45:16.019  1389  1389 D wpa_supplicant: wlan0: BSS: Add new id 14 BSSID 00:1e:4a:8f:e3:62 SSID '\x00'
03-19 11:45:16.019  1389  1389 D wpa_supplicant: wlan0: BSS: Add new id 15 BSSID 00:1f:27:54:dd:e2 SSID '\x00'
03-19 11:45:16.019   952  1646 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 11 00:1e:4a:8f:e3:6f]
03-19 11:45:16.019  1389  1389 D wpa_supplicant: wlan0: BSS: Add new id 16 BSSID 00:22:0d:46:1c:a0 SSID '\x00'
03-19 11:45:16.019   952  1646 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 12 00:1e:4a:8f:e3:60]
03-19 11:45:16.019  1389  1389 D wpa_supplicant: wlan0: BSS: Add new id 17 BSSID 00:22:0d:46:1c:a4 SSID '\x00'
03-19 11:45:16.019   952  1646 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 13 00:1e:4a:8f:e3:64]
03-19 11:45:16.019  1389  1389 D wpa_supplicant: wlan0: BSS: Add new id 18 BSSID 00:1e:4a:8f:df:d3 SSID 'RA-WINGS'
03-19 11:45:16.019   952  1646 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 14 00:1e:4a:8f:e3:62]
03-19 11:45:16.019  1389  1389 D wpa_supplicant: BSS: last_scan_res_used=19/32
03-19 11:45:16.019   952  1646 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 15 00:1f:27:54:dd:e2]
03-19 11:45:16.019  1389  1389 D wpa_supplicant: wlan0: Scan-only results received
03-19 11:45:16.019   952  1646 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 16 00:22:0d:46:1c:a0]
03-19 11:45:16.019  1389  1389 D wpa_supplicant: wlan0: Radio work 'scan'@0x556edc6aa0 done in 6.331577 seconds
03-19 11:45:16.019   952  1646 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 17 00:22:0d:46:1c:a4]
03-19 11:45:16.019   952  1646 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 18 00:1e:4a:8f:df:d3]
03-19 11:45:16.019   952  1646 E WifiMonitor: WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
03-19 11:45:16.019   952  1646 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
03-19 11:45:16.019   952  1151 E WifiStateMachine: handleMessage: E msg.what=147461
,03-19 11:45:16.019   952  1151 E WifiStateMachine: processMsg: ConnectedState
03-19 11:45:16.019   952  1151 E WifiStateMachine:  ConnectedState !SCAN_RESULTS_EVENT 0 0 found=10 known=1 got=10 bcn=0
03-19 11:45:16.019   952  1151 E WifiStateMachine: processMsg: L2ConnectedState
03-19 11:45:16.019   952  1151 E WifiStateMachine:  L2ConnectedState !SCAN_RESULTS_EVENT 0 0 found=10 known=1 got=10 bcn=0
03-19 11:45:16.019   952  1151 E WifiStateMachine: processMsg: ConnectModeState
03-19 11:45:16.019   952  1151 E WifiStateMachine:  ConnectModeState !SCAN_RESULTS_EVENT 0 0 found=10 known=1 got=10 bcn=0
03-19 11:45:16.019   952  1151 E WifiStateMachine: processMsg: DriverStartedState
03-19 11:45:16.019   952  1151 E WifiStateMachine:  DriverStartedState !SCAN_RESULTS_EVENT 0 0 found=10 known=1 got=10 bcn=0
03-19 11:45:16.019   952  1151 E WifiStateMachine: processMsg: SupplicantStartedState
03-19 11:45:16.029   952  1151 E WifiStateMachine:  SupplicantStartedState !SCAN_RESULTS_EVENT 0 0 found=10 known=1 got=10 bcn=0
03-19 11:45:16.029   952  1151 D WifiStateMachine: [MLHD] enter handleMediaLinkEvent SupplicantStartedState
03-19 11:45:16.029   952  1151 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
03-19 11:45:16.029  1389  1389 D wpa_supplicant: wlan0: Control interface command 'LIST_DONGLES'
,03-19 11:45:16.109   952  1151 E WifiStateMachine: [1,458,384,316,120 ms] noteScanEnd no scan source
03-19 11:45:16.109   952  1151 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
03-19 11:45:16.109  1389  1389 D wpa_supplicant: wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
,03-19 11:45:16.119   952  1151 E WifiStateMachine: wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@2e4b2985 sup_state=COMPLETED debouncing=false
03-19 11:45:16.119   952  1151 E WifiAutoJoinController : NG700_GUEST f0:f2:6d:22:99:3e rssi=-52 cap [WPA2-PSK-CCMP][ESS] is not scored
03-19 11:45:16.119   952  1151 E WifiAutoJoinController : NG700 f4:f2:6d:22:99:3e rssi=-57 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
03-19 11:45:16.119   952  1151 E WifiConfigStore: updateSavedNetworkHistory(): try "NG700"WPA_PSK SSID="NG700" NG700 [WPA2-PSK-CCMP][WPS][ESS] ajst=0
03-19 11:45:16.119   952  1151 E WifiConfigStore: updateSavedNetworkHistory: HTC improve mode
03-19 11:45:16.119   952  1151 E WifiConfigStore:         got known scan result f4:f2:6d:22:99:3e key : "NG700"WPA_PSK num: 1 rssi=-57 freq=2457
03-19 11:45:16.119   952  1151 E WifiAutoJoinController : TEST_KTW01 00:1f:27:54:70:c1 rssi=-53 cap [WPA2-EAP-TKIP][ESS] is not scored
03-19 11:45:16.119   952  1151 E WifiAutoJoinController : ktwtestwifi 00:1f:27:54:70:c0 rssi=-53 cap [WPA2-EAP-CCMP+TKIP][ESS] is not scored
03-19 11:45:16.119   952  1151 E WifiAutoJoinController :  00:1f:27:54:dd:ef rssi=-74 cap [WPA-EAP-TKIP][WPA2-EAP-CCMP][ESS] is not scored
03-19 11:45:16.119   952  1151 E WifiAutoJoinController :  00:1f:27:54:dd:e0 rssi=-71 cap [WPA-EAP-TKIP][WPA2-EAP-CCMP][ESS] is not scored
03-19 11:45:16.119   952  1151 E WifiAutoJoinController :  62:45:b0:73:93:45 rssi=-86 cap [WEP][ESS] is not scored
03-19 11:45:16.119   952  1151 E WifiAutoJoinController : RA-WINGS 00:1e:4a:8f:e3:63 rssi=-59 cap [ESS] is not scored
03-19 11:45:16.119   952  1151 E WifiAutoJoinController : RA-WINGS 00:1f:27:54:dd:e3 rssi=-70 cap [ESS] is not scored
03-19 11:45:16.119   952  1151 E WifiAutoJoinController : RA-WINGS 00:22:0d:46:1c:a3 rssi=-75 cap [ESS] is not scored
03-19 11:45:16.119   952  1151 E WifiAutoJoinController :  00:1e:4a:8f:e3:6b rssi=-50 cap [WPA2-EAP-CCMP][ESS] is not scored
03-19 11:45:16.119   952  1151 E WifiAutoJoinController :  00:1e:4a:8f:e3:6f rssi=-50 cap [WPA-EAP-TKIP][WPA2-EAP-CCMP][ESS] is not scored
03-19 11:45:16.119   952  1151 E WifiAutoJoinController :  00:1e:4a:8f:e3:60 rssi=-63 cap [WPA-EAP-TKIP][WPA2-EAP-CCMP][ESS] is not scored
03-19 11:45:16.119   952  1151 E WifiAutoJoinController :  00:1e:4a:8f:e3:64 rssi=-63 cap [WPA2-EAP-CCMP][ESS] is not scored
03-19 11:45:16.119   952  1151 E WifiAutoJoinController :  00:1e:4a:8f:e3:62 rssi=-63 cap [WPA2-PSK-CCMP][ESS] is not scored
03-19 11:45:16.119   952  1151 E WifiAutoJoinController :  00:1f:27:54:dd:e2 rssi=-71 cap [WPA2-PSK-CCMP][ESS] is not scored
03-19 11:45:16.119   952  1151 E WifiAutoJoinController :  00:22:0d:46:1c:a0 rssi=-73 cap [WPA-EAP-TKIP][WPA2-EAP-CCMP][ESS] is not scored
03-19 11:45:16.119   952  1151 E WifiAutoJoinController :  00:22:0d:46:1c:a4 rssi=-74 cap [WPA2-EAP-CCMP][ESS] is not scored
03-19 11:45:16.119   952  1151 E WifiAutoJoinController : RA-WINGS 00:1e:4a:8f:df:d3 rssi=-82 cap [ESS] is not scored
03-19 11:45:16.119   952  1151 E WifiAutoJoinController : ageScanResultsOut delay 40000 size 19 now 1458384316130
,03-19 11:45:16.119   952  1151 E WifiAutoJoinController : newSupplicantResults size=19 known=1 true
03-19 11:45:16.119   952  1151 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 STATUS-NO_EVENTS"
03-19 11:45:16.119  1389  1389 D wpa_supplicant: wlan0: Control interface command 'STATUS-NO_EVENTS'
03-19 11:45:16.129   952  1151 E WifiAutoJoinController : attemptAutoJoin() status=bssid=f4:f2:6d:22:99:3e
03-19 11:45:16.129   952  1151 E WifiAutoJoinController : ssid=NG700
03-19 11:45:16.129   952  1151 E WifiAutoJoinController : id=0
03-19 11:45:16.129   952  1151 E WifiAutoJoinController : mode=station
03-19 11:45:16.129   952  1151 E WifiAutoJoinController : pairwise_cipher=CCMP
03-19 11:45:16.129   952  1151 E WifiAutoJoinController : group_cipher=CCMP
03-19 11:45:16.129   952  1151 E WifiAutoJoinController : key_mgmt=WPA2-PSK
03-19 11:45:16.129   952  1151 E WifiAutoJoinController : wpa_state=COMPLETED
03-19 11:45:16.129   952  1151 E WifiAutoJoinController : ip_address=192.168.1.102
03-19 11:45:16.129   952  1151 E WifiAutoJoinController : p2p_device_address=92:e7:c4:e6:4c:f8
03-19 11:45:16.129   952  1151 E WifiAutoJoinController : address=XX:XX:XX:XX:XX:XX
03-19 11:45:16.129   952  1151 E WifiAutoJoinController : uuid=12345678-9abc-def0-1234-56789abcdef1 split=12
03-19 11:45:16.129   952  1151 E WifiAutoJoinController : attemptAutoJoin() num recent config 1 current="NG700"WPA_PSK ---> suppNetId=0
03-19 11:45:16.129   952  1151 E WifiAutoJoinController : attemptAutoJoin good candidate seen, bumped hard -> status=0 "NG700"WPA_PSK rssi=(-57,-127) num=(1,0)
03-19 11:45:16.129   952  1151 E WifiAutoJoinController : attemptAutoJoin skip current candidate  0 key "NG700"WPA_PSK
03-19 11:45:16.129   952  1151 E WifiAutoJoinController : attemptRoam: "NG700"WPA_PSK Found f4:f2:6d:22:99:3e rssi=-57 freq=2457 Current: f4:f2:6d:22:99:3e
03-19 11:45:16.129   952  1151 D HtcWifiControlRoamOffload: : roamCandidate: nullcurrentBSSID: f4:f2:6d:22:99:3e
03-19 11:45:16.129   952  1151 E WifiStateMachine: WiFiDisplay: getWifidisplayApEnabled=false
03-19 11:45:16.129   952  1151 E WifiAutoJoinController : Done attemptAutoJoin status=0
03-19 11:45:16.129   952  1151 E WifiConfigStore:  writeKnownNetworkHistory() num networks:1 needWrite=false
,03-19 11:45:16.139   952   986 I ActivityManager: Start proc com.htc.sense.news for broadcast com.htc.launcher/com.htc.plugin.news.remote.CustomHighlightReceiver: pid=3564 uid=10074 gids={50074, 9997, 3003, 1028, 1015, 5001, 1023} abi=arm64-v8a
,03-19 11:45:16.139   952  1151 E WifiStateMachine: handleMessage: X
03-19 11:45:16.149  1834  1834 D WifiManager: getScanResults: Base Package Name=com.google.android.gms, uid=10024
,03-19 11:45:16.149  3478  3555 D jxcore_app_log: JniHelper::setJavaVM(0xab00a8f8), pthread_self() = -1405930016
,03-19 11:45:16.169  3478  3555 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
03-19 11:45:16.169  3478  3555 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
03-19 11:45:16.169  3478  3555 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
,03-19 11:45:16.169  3478  3555 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
03-19 11:45:16.169  3478  3555 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
03-19 11:45:16.169  3478  3555 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ce34b86 added. We now have 1 listener(s)
,03-19 11:45:16.179   952  1248 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,03-19 11:45:16.179  3478  3555 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 90:E7:C4:F6:69:77
,03-19 11:45:16.179  3478  3555 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "90:E7:C4:F6:69:77"
03-19 11:45:16.189  3478  3555 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66,
03-19 11:45:16.189  3478  3555 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
03-19 11:45:16.189  3478  3555 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
03-19 11:45:16.189  3478  3555 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
03-19 11:45:16.189  3478  3555 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
03-19 11:45:16.189  3478  3555 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 90:E7:C4:F6:69:77
03-19 11:45:16.189  3478  3555 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
03-19 11:45:16.189  3478  3555 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
03-19 11:45:16.189  3478  3555 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
03-19 11:45:16.189  3478  3555 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
03-19 11:45:16.189  3478  3555 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
03-19 11:45:16.189  3478  3555 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
03-19 11:45:16.189  3478  3555 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
03-19 11:45:16.189  3478  3555 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f9cf59d added. We now have 1 listener(s)
03-19 11:45:16.189  3478  3555 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,03-19 11:45:16.199  3478  3555 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
03-19 11:45:16.199   952  1152 D WifiService: New client listening to asynchronous messages
03-19 11:45:16.199   952   952 E WifiTrafficPoller: ADD_CLIENT: 7
03-19 11:45:16.199  3478  3555 W org.thaliproject.p2p.btconnectorlib.DiscoveryManager: isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
,03-19 11:45:16.209  3478  3555 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,03-19 11:45:16.209  3478  3555 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
03-19 11:45:16.209  3478  3555 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
03-19 11:45:16.209  3478  3555 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,03-19 11:45:16.209  3478  3555 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-19 11:45:16.209   952  1714 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
03-19 11:45:16.209  3478  3555 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 90:E7:C4:F6:69:77
,03-19 11:45:16.219  3478  3555 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
03-19 11:45:16.219  3478  3555 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-19 11:45:16.219  3478  3555 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-19 11:45:16.219  3478  3555 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
03-19 11:45:16.219  3478  3555 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-19 11:45:16.219  3478  3555 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
03-19 11:45:16.219  3478  3555 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
,03-19 11:45:16.219  3478  3555 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-19 11:45:16.219  3478  3555 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
03-19 11:45:16.219  3478  3555 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
03-19 11:45:16.219  3478  3555 D io.jxcore.node.ConnectivityMonitor: start: OK
03-19 11:45:16.229  3478  3555 I io.jxcore.node.LifeCycleMonitor: start: OK
,03-19 11:45:16.249  3478  3478 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-19 11:45:16.249  3478  3478 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-19 11:45:16.269  3478  3478 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,03-19 11:45:16.299  3564  3564 I ImageRamCache: create image Cache, size: 31457280.
,03-19 11:45:16.299  3564  3564 I ImageRamCache: [resize] ImageRamCache resized to: 30Mb.,
03-19 11:45:16.299  3564  3564 I ImageRamCache: create image Cache, size: 31457280.
,03-19 11:45:16.299  3564  3564 I FeedSettings: [BlinkFeedCommitment]loadSettings, BLINKFEED commitment: true,
03-19 11:45:16.309  3564  3564 I FeedSettings: GroupBudget 0.500000 0.380000
03-19 11:45:16.309  3564  3564 I FeedSettings: GroupBudget 60 45 15
,03-19 11:45:16.309  3564  3564 I Prism.ExternalStringMa_: changeLocale(): en_GB,
,03-19 11:45:16.319  3564  3564 I Prism.AllAppsOptionsMa_: loadSortType() with Custom,
03-19 11:45:16.319  3564  3564 I Prism.AllAppsOptionsMa_: loadGridSize() with Alternative
,03-19 11:45:16.339  3564  3564 D CustomHighlightReceiver: [custom highlight] onReceive
,03-19 11:45:16.349  3564  3593 D CustomHighlightService: [custom highlight] onHandleIntent
,03-19 11:45:16.349  3564  3593 D NewsDB  : set custom highlight []
,03-19 11:45:16.369   952   952 I ActivityManager: Start proc com.htc.backup for broadcast com.htc.backup/.receiver.SuperSaverModeReceiver: pid=3594 uid=10109 gids={50109, 9997, 3003, 1028, 1015} abi=arm64-v8a,
,03-19 11:45:16.379  3564  3593 D CustomHighlightService: [custom highlight] set tags 
,03-19 11:45:16.379   952   986 D Process : killProcessQuiet, pid=2736
03-19 11:45:16.379   952   986 I ActivityManager: Killing 2736:com.htc.task/u0a69 (adj 15): empty #17
03-19 11:45:16.379   952   986 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,03-19 11:45:16.439   952  1248 I ActivityManager: Recipient 2736
,03-19 11:45:16.609  3594  3594 I htcbackup-core: ModelRegistry: Loading model meta data from resources...
,03-19 11:45:16.649  3594  3594 I htcbackup-core: SuperSaverModeReceiver: on receiving action com.htc.server.htcpowersaver.action.OFF,
03-19 11:45:16.649  3594  3594 I htcbackup-core: SuperSaverModeReceiver: going to send resume event
,03-19 11:45:16.659   952   952 D BluetoothManagerService: Auto-enabling Bluetooth.
,03-19 11:45:16.659   952   952 D BluetoothManagerService: checking for enable restriction...
03-19 11:45:16.659   952   952 D BluetoothManagerService: checkBTEasState, ret=true
03-19 11:45:16.659   952   952 I BluetoothManagerService: isBluetoothRestricted(): false
03-19 11:45:16.659   952  1044 D BluetoothManagerService: Message: MESSAGE_ENABLE
03-19 11:45:16.659   952  1044 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
,03-19 11:45:16.669   952  1044 I ActivityManager: Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=3621 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 1023, 3005, 1016, 3008} abi=armeabi-v7a
,03-19 11:45:16.669  3594  3620 I htcbackup-core: BackupRestoreManager: onHandleIntent
03-19 11:45:16.669  3594  3620 I htcbackup-core: BackupRestoreManager: resume
03-19 11:45:16.669   952  1029 D PMS     : acquireWL(14ca41a8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 952 1000 null,
,03-19 11:45:16.679   952   952 D UsbDeviceManager: boot completed
,03-19 11:45:16.679  1219  1219 V SystemUIService: BOOT_COMPLETED received
03-19 11:45:16.679   952  1042 D UsbDeviceManager: [USBNET] handleMessage: 4; mConnected=true, mConfiguration=true
03-19 11:45:16.679   952  1042 D UsbDeviceManager: [USBNET] update2: 105,0
03-19 11:45:16.679   952  1042 D UsbDeviceManager: sendStickyBroadcast: broadcasting Intent { act=android.hardware.usb.action.USB_STATE flg=0x20000000 (has extras) } connected: true configured: true; SetCurrentFunctions= mtp,mass_storage,adb
,03-19 11:45:16.679   952  1029 D PMS     : acquireWL(855d054): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.drive.sync/com.google/***** 0x1 952 1000 WorkSource{10024}
,03-19 11:45:16.699   952  3619 I ActivityManager: Start proc com.android.keychain for service com.android.keychain/.KeyChainService: pid=3642 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
,03-19 11:45:16.699   952  1042 D UsbDeviceManager: [USBNET] handleMessage: 105; mConnected=true, mConfiguration=true
,03-19 11:45:16.709   952  1042 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendStickyBroadcast:1626 com.android.server.usb.UsbDeviceManager$UsbHandler.handleMessage:1624 android.os.Handler.dispatchMessage:102 android.os.Looper.loop:155 android.os.HandlerThread.run:61 
,03-19 11:45:16.709   952  3654 I RecoverySystem: No recovery log file
03-19 11:45:16.709   952  3634 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,03-19 11:45:16.719   952  1385 I ActivityManager: Start proc com.htc.cs.dm for service com.htc.cs.dm/.config.service.ConfigManagerBoundService: pid=3660 uid=10099 gids={50099, 9997, 3003} abi=arm64-v8a,
03-19 11:45:16.719   952  1044 D Tethering: got USB_STATE change: usbConnected=true, mRndisEnabled=false, mUsbTetherRequested=false
,03-19 11:45:16.729   952   952 D UsbnetService: BroadcastReceiver::onReceive+
,03-19 11:45:16.729   952   952 D UsbnetService: onReceive ACTION_USB_STATE: true,false
03-19 11:45:16.729   952  1042 D UsbDeviceManager: [USBNET] sendStickyBroadcast ACTION_USB_CONNECT2PC: 1
03-19 11:45:16.729   952   952 D UsbnetService: BroadcastReceiver::onReceive-
,03-19 11:45:16.739  3621  3621 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,03-19 11:45:16.749   952  3654 I BootReceiver: Copying /sys/fs/pstore/console-ramoops to DropBox (SYSTEM_LAST_KMSG)
,03-19 11:45:16.749   952  3691 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
,03-19 11:45:16.749   952  1715 I ActivityManager: Start proc com.futuredial for broadcast com.futuredial/.ui.BootCompletedReceiver: pid=3689 uid=10082 gids={50082, 9997, 3002, 3001} abi=arm64-v8a
,03-19 11:45:16.759   952  1144 D MountService: sharing = 0 ,
03-19 11:45:16.759   952  1144 D MountService: Unmount PCTOOL.ISO
03-19 11:45:16.759   952  1144 D VoldConnector: SND -> {17 mountISO unmount /system/etc/PCTOOL.ISO /sys/class/android_usb/f_mass_storage/lun0/file}
03-19 11:45:16.769   952  1029 D PMS     : releaseWL(14ca41a8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
03-19 11:45:16.769   952  1029 D PMS     : acquireWL(28926333): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 952 1000 null
,03-19 11:45:16.769   952  1029 D PMS     : releaseWL(28926333): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
03-19 11:45:16.769   952  1029 D PMS     : acquireWL(cfff6f0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 952 1000 null
03-19 11:45:16.769   436   436 I art     : Explicit concurrent mark sweep GC freed 8657(367KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 188us total 21.616ms
03-19 11:45:16.769   952  1029 D PMS     : releaseWL(cfff6f0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
03-19 11:45:16.779   952  1144 D MountService: unmountISO --
,03-19 11:45:16.789   952  1062 D PMS     : releaseHCC(3819c793): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null,
03-19 11:45:16.789   952  1062 D PMS     : releaseHCC(2c7af3d0): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,03-19 11:45:16.789   436   436 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 165us total 17.247ms
,03-19 11:45:16.799  3689  3689 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.,
,03-19 11:45:16.799  3689  3689 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,03-19 11:45:16.809   436   436 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 164us total 19.090ms
,03-19 11:45:16.829   952   952 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 7
,03-19 11:45:16.839   952   952 E WifiTrafficPoller:  packet count Tx=46 Rx=45
,03-19 11:45:16.859  3478  3587 W jxcore-log: Initializing JXcore engine
03-19 11:45:16.859  3478  3587 W jxcore-log: JXcore engine is ready
,03-19 11:45:16.909   952  3691 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml,
03-19 11:45:16.909   952  3654 I BootReceiver: Copying audit failures to DropBox
,03-19 11:45:16.919   952  3654 I BootReceiver: Copied 0 worth of audits to DropBox,
03-19 11:45:16.929   952   986 D Process : killProcessQuiet, pid=3147
03-19 11:45:16.929   952   986 I ActivityManager: Killing 3147:com.htc.showme/u0a81 (adj 15): empty #17
03-19 11:45:16.929   952   986 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,03-19 11:45:16.929   952  3654 I BootReceiver: Checking for fsck errors
03-19 11:45:16.929   952  3654 I BootReceiver: Copying /data/tombstones/tombstone_00 to DropBox (SYSTEM_TOMBSTONE)
03-19 11:45:16.929  3478  3587 W jxcore-log: Starting JXcore engine
,03-19 11:45:16.929   952  3691 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
,03-19 11:45:16.939  3478  3496 I art     : Background sticky concurrent mark sweep GC freed 3715(252KB) AllocSpace objects, 2(35KB) LOS objects, 2% free, 7MB/7MB, paused 5.116ms total 17.730ms
,03-19 11:45:17.009   952  3691 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml,
03-19 11:45:17.009   952  3654 I BootReceiver: Copying /data/tombstones/tombstone_01 to DropBox (SYSTEM_TOMBSTONE)
,03-19 11:45:17.039   952  3654 I BootReceiver: Copying /data/tombstones/tombstone_02 to DropBox (SYSTEM_TOMBSTONE)
,03-19 11:45:17.039   952  3691 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
,03-19 11:45:17.049   952  3654 I BootReceiver: Copying /data/tombstones/tombstone_03 to DropBox (SYSTEM_TOMBSTONE),
,03-19 11:45:17.049   952  3691 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
,03-19 11:45:17.059   952  2301 I ActivityManager: Recipient 3147
,03-19 11:45:17.069   952  3654 I BootReceiver: Copying /data/tombstones/tombstone_04 to DropBox (SYSTEM_TOMBSTONE)
,03-19 11:45:17.069  3478  3587 W jxcore-log: Platform android
03-19 11:45:17.069  3478  3587 W jxcore-log: 
03-19 11:45:17.069  3478  3587 W jxcore-log: Process ARCH arm
03-19 11:45:17.069  3478  3587 W jxcore-log: 
,03-19 11:45:17.079   952  3691 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
,03-19 11:45:17.079   952  3654 I BootReceiver: Copying /data/tombstones/tombstone_05 to DropBox (SYSTEM_TOMBSTONE)
,03-19 11:45:17.079   952  3691 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
,03-19 11:45:17.099   952  3691 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
03-19 11:45:17.099   952  3654 I BootReceiver: Copying /data/tombstones/tombstone_06 to DropBox (SYSTEM_TOMBSTONE)
,03-19 11:45:17.119   952  3654 I BootReceiver: Copying /data/tombstones/tombstone_07 to DropBox (SYSTEM_TOMBSTONE)
,03-19 11:45:17.119   952  3691 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml,
,03-19 11:45:17.129   952  3691 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml,
03-19 11:45:17.129   952  3654 I BootReceiver: Copying /data/tombstones/tombstone_08 to DropBox (SYSTEM_TOMBSTONE),
,03-19 11:45:17.149  3689  3689 I [FDDMI]BootCompletedReceiver: BootCompletedReceiver :android.intent.action.BOOT_COMPLETED
,03-19 11:45:17.159   952  3654 I BootReceiver: Copying /data/tombstones/tombstone_09 to DropBox (SYSTEM_TOMBSTONE)
,03-19 11:45:17.159   952  3691 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
,03-19 11:45:17.179   952  1764 I art     : Explicit concurrent mark sweep GC freed 29519(1969KB) AllocSpace objects, 47(2MB) LOS objects, 33% free, 16MB/24MB, paused 1.698ms total 193.140ms
03-19 11:45:17.189  3621  3621 D AdapterServiceConfig: Adding HeadsetService
03-19 11:45:17.189  3621  3621 D AdapterServiceConfig: Adding A2dpService
03-19 11:45:17.189  3621  3621 D AdapterServiceConfig: Adding HidService
03-19 11:45:17.189  3621  3621 D AdapterServiceConfig: Adding HealthService
03-19 11:45:17.189  3621  3621 D AdapterServiceConfig: Adding PanService
03-19 11:45:17.189  3621  3621 D AdapterServiceConfig: Adding GattService
,03-19 11:45:17.219  3621  3621 W linker  : libbt-aptx-4.1.1.so has text relocations. This is wasting memory and prevents security hardening. Please fix.
,03-19 11:45:17.229  3660  3660 I DeviceManagement: DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.2.848686;250001208] pid=3660 dbg=false s=true
,03-19 11:45:17.249   952  1479 W System.err: java.lang.Throwable: stack dump
03-19 11:45:17.249   952  1044 D BluetoothManagerService: Message: MESSAGE_REGISTER_ADAPTER
03-19 11:45:17.249   952  1044 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@14abea7f:true
03-19 11:45:17.249  3660  3700 I DeviceManagement: ConfigManagerBoundService: *** getConfig: appID=com.htc.backup options=Bundle[mParcelledData.dataSize=40]
03-19 11:45:17.249   952  1479 W System.err: 	at java.lang.Thread.dumpStack(Thread.java:490)
,03-19 11:45:17.249   952  1479 W System.err: 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
03-19 11:45:17.249   952  1479 W System.err: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
03-19 11:45:17.249   952  1479 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
03-19 11:45:17.249  3660  3700 I DeviceManagement: ConfigManagerBoundService: Caller: uid=com.htc.backup (10109) packages=[com.htc.backup]
03-19 11:45:17.249  3621  3621 D BluetoothAdapterState: make
,03-19 11:45:17.259  1407  1407 D OtaStartupReceiver: onReceive: android.intent.action.BOOT_COMPLETED
,03-19 11:45:17.259   952   952 W HtcActiveEngineManager: Can't find out the target sensor
,03-19 11:45:17.259   952  1151 E WifiStateMachine: handleMessage: E msg.what=131206
03-19 11:45:17.259   952  1151 E WifiStateMachine: processMsg: ConnectedState
03-19 11:45:17.269   952   952 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 
03-19 11:45:17.259   952  1151 E WifiStateMachine:  ConnectedState !CMD_BOOT_COMPLETED 0 0
03-19 11:45:17.269   952  1154 D ConnectivityService: Got NetworkFactory Messenger for WIFI
03-19 11:45:17.259   952  1151 E WifiStateMachine: processMsg: L2ConnectedState
03-19 11:45:17.269   952  1154 D ConnectivityService: NetworkFactory connected
03-19 11:45:17.259   952  1151 E WifiStateMachine:  L2ConnectedState !CMD_BOOT_COMPLETED 0 0
03-19 11:45:17.259   952  1151 E WifiStateMachine: processMsg: ConnectModeState
03-19 11:45:17.259   952  1151 E WifiStateMachine:  ConnectModeState !CMD_BOOT_COMPLETED 0 0
03-19 11:45:17.259   952  1151 E WifiStateMachine: processMsg: DriverStartedState
03-19 11:45:17.259   952  1151 E WifiStateMachine:  DriverStartedState !CMD_BOOT_COMPLETED 0 0
03-19 11:45:17.259   952  1151 E WifiStateMachine: processMsg: SupplicantStartedState
03-19 11:45:17.259  3660  3719 I DeviceManagement: WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[mParcelledData.dataSize=40], appID=com.htc.backup}]]
03-19 11:45:17.259   952  1151 E WifiStateMachine:  SupplicantStartedState !CMD_BOOT_COMPLETED 0 0
03-19 11:45:17.259   952  1151 E WifiStateMachine: processMsg: DefaultState
03-19 11:45:17.269   952  1151 E WifiStateMachine:  DefaultState !CMD_BOOT_COMPLETED 0 0
03-19 11:45:17.269   952  1151 E WifiStateMachine: handleMessage: X
03-19 11:45:17.269   952   952 D UsbnetService: BroadcastReceiver::onReceive+
03-19 11:45:17.269   952   952 D UsbnetService: onReceive ACTION_BOOT_COMPLETED
03-19 11:45:17.269   952  1151 D WIFI    : got request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] with score 60
03-19 11:45:17.269   952   952 D UsbnetService: BroadcastReceiver::onReceive-
03-19 11:45:17.269   952  1162 D UsbnetService: UsbnetHandler::handleMessage+:4
03-19 11:45:17.269   952  1162 D UsbnetService: MESSAGE_BOOT_COMPLETED+
03-19 11:45:17.269   952  1151 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
03-19 11:45:17.269   952  1151 D WIFI    : evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] released
03-19 11:45:17.269  3621  3718 I BluetoothAdapterState: Entering OffState
03-19 11:45:17.269  3660  3660 I DeviceManagement: WorkflowService: Starting workflow service
03-19 11:45:17.269   952  1162 D UsbnetService: systemReady+
03-19 11:45:17.269   952  1162 D UsbnetService: systemReady-
03-19 11:45:17.269   952   952 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1473 com.android.server.backup.BackupManagerService.notifyBackupEnabled:10562 com.android.server.backup.BackupManagerService.access$3400:164 com.android.server.backup.BackupManagerService$BootCompleteReceiver.onReceive:10549 android.app.LoadedApk$ReceiverDispatcher$Args.run:950 
03-19 11:45:17.279   952  1162 D UsbnetService: UsbnetHandler::handleMessage-
03-19 11:45:17.279   952   952 D WifiService: updateDevicePolicy Exchange policy allowWifiStatus = 1
03-19 11:45:17.279   952   952 D WifiService: updateDevicePolicy Exchange policy allowInternetSharingStatus = 1
03-19 11:45:17.279   952  1154 D ConnectivityService: Got NetworkFactory Messenger for usbnet
03-19 11:45:17.279   952  1162 D usbnet  : got request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] with score 60
03-19 11:45:17.279   952  1154 D ConnectivityService: NetworkFactory connected
03-19 11:45:17.279   952  1162 D usbnet  :   my score=70, my filter=[ Transports:  Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
03-19 11:45:17.279   952  1162 D usbnet  : evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] released
,03-19 11:45:17.279  3660  3722 I DeviceManagement: WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@1debea05] args=[Bundle[mParcelledData.dataSize=132]]
03-19 11:45:17.279  3660  3722 I DeviceManagement: ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=132]
03-19 11:45:17.289  3660  3722 I DeviceManagement: ModelRegistry: Loading model meta data from resources...
,03-19 11:45:17.289  3621  3621 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,03-19 11:45:17.299  3621  3727 D BluetoothAdapterProperties: Address is:90:E7:C4:F6:69:77
,03-19 11:45:17.299  3478  3587 I jxcore-log: JXcore Cordova bridge is ready!
03-19 11:45:17.299  3478  3587 I jxcore-log: 
03-19 11:45:17.299  3478  3587 W jxcore-log: JXcore engine is started
03-19 11:45:17.299   952   952 I ActivityManager: Start proc com.htc.autobot for broadcast com.htc.autobot/.UsbReceiver: pid=3724 uid=10047 gids={50047, 9997, 3003, 3002, 3001, 5003, 1024} abi=arm64-v8a
,03-19 11:45:17.299   952   952 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
,03-19 11:45:17.299   952  1764 I ActivityManager: Killing 2888:com.htc.sense.browser/u0a9 (adj 15): empty #17
03-19 11:45:17.299   952  1044 D BluetoothManagerService: Message: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
03-19 11:45:17.299   952  1044 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
03-19 11:45:17.309  3478  3555 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,03-19 11:45:17.309   952  1764 D Process : killProcessQuiet, pid=2888
03-19 11:45:17.309   952  1764 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
03-19 11:45:17.309  3478  3478 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
03-19 11:45:17.309   952  1044 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
03-19 11:45:17.309   952  1044 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 7 receivers.
03-19 11:45:17.309  3478  3500 D BluetoothAdapter: onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@a697486
03-19 11:45:17.309  3478  3500 D BluetoothAdapter: onBluetoothServiceUp done
03-19 11:45:17.309   952  1044 D BluetoothAdapter: onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@145b2476
,03-19 11:45:17.309   952  1044 D BluetoothAdapter: onBluetoothServiceUp done,
03-19 11:45:17.309  2389  2410 D BluetoothAdapter: onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@769287f
,03-19 11:45:17.309  2389  2410 D BluetoothAdapter: onBluetoothServiceUp done
03-19 11:45:17.309  1407  1445 D BluetoothAdapter: onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@84d114f
03-19 11:45:17.309  1407  1445 D BluetoothAdapter: onBluetoothServiceUp done
,03-19 11:45:17.319  1219  1246 D BluetoothAdapter: onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@28faf969
03-19 11:45:17.319  1219  1246 D BluetoothAdapter: onBluetoothServiceUp done
,03-19 11:45:17.319  1425  1454 D BluetoothAdapter: onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@1aeddab2
,03-19 11:45:17.319  1425  1454 D BluetoothAdapter: onBluetoothServiceUp done
03-19 11:45:17.319  3660  3722 I DeviceManagement: ConfigManagerController: *** getConfig: appID=com.htc.backup includeMeta=true
03-19 11:45:17.319  3621  3651 D BluetoothAdapter: onBluetoothServiceUp: com.android.bluetooth.btservice.AdapterService$AdapterServiceBinder@1debea05
03-19 11:45:17.319  3621  3651 D BluetoothAdapter: onBluetoothServiceUp done
03-19 11:45:17.319   952  1044 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() done
,03-19 11:45:17.319  3478  3587 E jxcore  : Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
03-19 11:45:17.319  3478  3587 E jxcore  : Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
03-19 11:45:17.319  3621  3718 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
03-19 11:45:17.319  3621  3718 D BluetoothAdapterProperties: Setting state to 11
03-19 11:45:17.319  3621  3718 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
03-19 11:45:17.319   952  1385 D BluetoothManagerService: +onBluetoothStateChange prev=10 new=11
03-19 11:45:17.319   952  1044 D BluetoothManagerService: Message: MESSAGE_BLUETOOTH_STATE_CHANGE
03-19 11:45:17.319   952  1044 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
03-19 11:45:17.319   952  1044 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
,03-19 11:45:17.329  3478  3478 I chromium: [INFO:CONSOLE(57)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (57)
,03-19 11:45:17.329  3478  3478 I chromium: [INFO:CONSOLE(62)] "****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****", source: file:///android_asset/www/js/thali_main.js (62)
,03-19 11:45:17.329  3660  3744 I DeviceManagement: SessionStateController: Checking invariants...
,03-19 11:45:17.389   952  1151 E WifiStateMachine: handleMessage: E msg.what=131155
,03-19 11:45:17.389   952  1151 E WifiStateMachine: processMsg: ConnectedState
03-19 11:45:17.389   952  1151 E WifiStateMachine:  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-57 f=2457 sc=60 link=150 tx=6.6, 0.0, 0.0  rx=5.5 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1904563245] gl hn u24 rssi=-52 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
03-19 11:45:17.389   952  1151 E WifiStateMachine: processMsg: L2ConnectedState
03-19 11:45:17.389   952  1151 E WifiStateMachine:  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-57 f=2457 sc=60 link=150 tx=6.6, 0.0, 0.0  rx=5.5 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1904563244] gl hn u24 rssi=-52 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
03-19 11:45:17.389   952  1151 E WifiStateMachine:  get link layer stats 0
03-19 11:45:17.389   952  1151 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
03-19 11:45:17.389  1389  1389 D wpa_supplicant: wlan0: Control interface command 'SIGNAL_POLL'
,03-19 11:45:17.399  1389  1389 I wpa_supplicant: environment dirty rate=14 [7][1][0]
03-19 11:45:17.399   952  1151 E WifiStateMachine: fetchRssiLinkSpeedAndFrequencyNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 150
03-19 11:45:17.399   952  1151 E WifiStateMachine: fetchRssiLinkSpeedAndFrequencyNative rssi=-57 linkspeed=150
03-19 11:45:17.399   952  1151 E WifiConfigStore: updateConfiguration freq=2457 BSSID=f4:f2:6d:22:99:3e RSSI=-57 "NG700"WPA_PSK
03-19 11:45:17.399   952  1151 E WifiStateMachine: calculateWifiScore freq=2457 speed=150 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=6.82 txretriesrate=0.00 rxrate=12.23 userTriggerdPenalty0
03-19 11:45:17.399   952  1151 E WifiStateMachine:  good link -> stuck count =0
03-19 11:45:17.399   952  1151 E WifiStateMachine:  badRSSI count0 lowRSSI count0 --> score 60
03-19 11:45:17.409   952  1151 E WifiStateMachine:  isHighRSSI       ---> score=65
,03-19 11:45:17.419   952  2301 I ActivityManager: Recipient 2888
,03-19 11:45:17.479  3660  3744 I DeviceManagement: ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true
,03-19 11:45:17.559  3478  3555 W PluginManager: THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 227ms. Plugin should use CordovaInterface.getThreadPool().
03-19 11:45:17.559   952  1479 D PMS     : acquireWL(192eaa77): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 952 1000 null
03-19 11:45:17.559  3478  3478 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
03-19 11:45:17.559  3478  3478 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
03-19 11:45:17.559   952  1151 E WifiStateMachine: handleMessage: X
,03-19 11:45:17.559  3621  3718 D BluetoothBondStateMachine: make
03-19 11:45:17.569  1219  1674 I IntentController: receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
03-19 11:45:17.569   952  1168 D WifiWatchdogStateMachine: RSSI current: 3 new: -57, 3
03-19 11:45:17.569  1219  1219 D WIFI_ICON: updateWifiState: RSSI_CHANGED 3 -> 3
03-19 11:45:17.569  3621  3718 D BluetoothAdapterService: checkA2dpState: isA2dpSinkEnabled = false
03-19 11:45:17.569  1219  1219 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
03-19 11:45:17.569  3621  3718 E BluetoothAdapterService: checkA2dpState: returning
03-19 11:45:17.569  3621  3718 D BluetoothAdapterService: checkHfpState: isHfpClientEnabled = false
03-19 11:45:17.569  3621  3718 E BluetoothAdapterService: checkHfpState: returning
03-19 11:45:17.569  3621  3621 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
03-19 11:45:17.569  3621  3621 V BluetoothPbapReceiver: ***********state = 11
03-19 11:45:17.569  3621  3750 I BluetoothBondStateMachine: StableState(): Entering Off State
03-19 11:45:17.569   952  1499 W HtcSystemUPManager: HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
,03-19 11:45:17.589  3660  3722 I DeviceManagement: SessionStateController: Checking invariants...
03-19 11:45:17.589  3724  3724 D UsbReceiver: onReceiver android.intent.action.BOOT_COMPLETED
03-19 11:45:17.589  1455  1455 I FeedHostManager: [onResume]
03-19 11:45:17.589  1455  1455 I FeedProviderManager: onResume
03-19 11:45:17.589  1455  2417 I SocialFeedProvider: +onResume
03-19 11:45:17.589  1455  2417 I SocialFeedProvider: updateAccounts - Accounts is no change
03-19 11:45:17.589  1455  2417 I SocialFeedProvider: -onResume
,03-19 11:45:17.599  3724  3724 D HtcModeClient: power connected, start service
,03-19 11:45:17.609  3724  3724 D Utils   : CMD:getprop ro.htc.htcmode.socket.type
,03-19 11:45:17.609   952  2376 I ActivityManager: Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.powersaver.PowerSaverNotificationReceiver: pid=3752 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
03-19 11:45:17.619  1407  1407 D BluetoothHeadset: Proxy object connected,
03-19 11:45:17.619  3621  3621 D HeadsetService: Received start request. Starting profile...
,03-19 11:45:17.619  3621  3621 D HeadsetStateMachine: Version 1.5
03-19 11:45:17.619  3621  3621 D HeadsetStateMachine: make
03-19 11:45:17.619  3724  3724 I System  : exec(getprop ro.htc.htcmode.socket.type @ com.htc.autobot.util.Utils.systemCmd:34)
,03-19 11:45:17.619  3747  3766 E cutils-trace: Error opening trace file: Permission denied (13)
03-19 11:45:17.619   952   952 D BluetoothHeadset: Proxy object connected
03-19 11:45:17.619  1407  1407 D BluetoothPhoneService: BluetoothHeadset onServiceConnected
03-19 11:45:17.619  1407  1407 D BluetoothHeadset: Proxy object connected
03-19 11:45:17.619  1407  1407 D BluetoothHeadset: Proxy object connected
,03-19 11:45:17.629  3621  3718 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
03-19 11:45:17.629   952   952 D BluetoothAdapter: 358501123: getState(). Returning 11
03-19 11:45:17.629   952  1043 D StatusBarManagerService: setSystemUiVisibility(0x8700)
03-19 11:45:17.629   952  1043 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
03-19 11:45:17.629   952  1043 D StatusBarManagerService: hiding MENU key
03-19 11:45:17.629  1219  1219 I QuickSettingBluetooth: receive.ACTION_STATE_CHANGE:STATE_TURNING_ON
03-19 11:45:17.629  1219  1219 D BluetoothHeadset: Proxy object connected
03-19 11:45:17.629  1219  1219 I QuickSettingMiniLite: btListener.connect:HEADSET/android.bluetooth.BluetoothHeadset@3b105fee
,03-19 11:45:17.629  1455  1455 D FindExtension: FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
03-19 11:45:17.639  1407  1407 D BluetoothAdapter: 702526949: getState(). Returning 11
,03-19 11:45:17.639  1455  1455 I ThreadedRenderer: Defer allocateBuffers to drawing time
,03-19 11:45:17.639  3621  3621 D HeadsetStateMachine: max_hf_connections = 2
03-19 11:45:17.649   952  2376 I InputMethodManagerService: Disable input method client, pid=3478
03-19 11:45:17.649   952  2376 D StatusBarManagerService: swetImeWindowStatus vis=0 backDisposition=0
03-19 11:45:17.649  1219  1219 I PhoneStatusBar: setImeWindowStatus(false,false)
,03-19 11:45:17.649   952  2376 I InputMethodManagerService: Enable input method client, pid=1455
,03-19 11:45:17.649  3621  3621 D HeadsetPhoneState: listenForPhoneState..for service and signal 
,03-19 11:45:17.659  3478  3478 W IInputConnectionWrapper: reportFullscreenMode on inactive InputConnection
,03-19 11:45:17.659  3724  3724 D HtcModeClient: sSocketMode = LocalSocket
,03-19 11:45:17.659  3724  3788 D HtcModeClient: start the htcmodeservice thread
03-19 11:45:17.659  3724  3788 D HtcModeClient: initCanAgent,
,03-19 11:45:17.659  3724  3788 I CANMesgAgentLocalSocket: CANAgent Id = 0
,03-19 11:45:17.669   952  1714 I ActivityManager: Start proc com.htc.widget.hmsproc3 for broadcast com.htc.htcbtwidget/.BTReceiver: pid=3791 uid=10034 gids={50034, 9997, 3002, 3001} abi=arm64-v8a,
,03-19 11:45:17.719  3724  3788 D HtcModeClient: sense info: version = none, id = 2
,03-19 11:45:17.719  3621  3621 D HeadsetDualPhoneStateListener_SLOT1: listen phone state by slot:SLOT1  id:-1
03-19 11:45:17.719  3747  3747 D CustomizationManager: ====startRecUseTime====
03-19 11:45:17.719  3747  3747 D htc.customization.log.level:  is 
03-19 11:45:17.719  3747  3747 W CustomizationLogLevel: Level value is invalid, use default level 2
,03-19 11:45:17.729  3621  3621 D HeadsetDualPhoneStateListener_SLOT2: listen phone state by slot:SLOT2  id:-100
03-19 11:45:17.729  3621  3771 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
03-19 11:45:17.729  3724  3724 D HtcModeClient: onStartCommand() action = com.htc.autobot.htcmodeclient.PowerConnected +++
03-19 11:45:17.729  3724  3724 D HtcModeClient: connectState: BT_TURNON_BYME = false
03-19 11:45:17.729  3724  3724 D HtcModeClient: connectState: CONNECTION_READY = false
03-19 11:45:17.729  3724  3724 D HtcModeClient: connectState: ENABLE_PROJECTBYAPP = false
03-19 11:45:17.729  3724  3724 D HtcModeClient: connectState: ENTER_PROJECTMODE = false
03-19 11:45:17.729  3724  3788 D HtcModeClient: display info: width = 1080, height = 1776
03-19 11:45:17.729  3724  3788 D HtcModeClient: display info: mode = 10
,03-19 11:45:17.729  3724  3724 D HtcModeClient: connectState: PHONE_PULGIN = false
03-19 11:45:17.729  3724  3724 D HtcModeClient: connectState: Force_AWAKE = false
,03-19 11:45:17.739  3724  3724 D HtcModeClient: connectState: PHONE_PULGIN = true
,03-19 11:45:17.739  3724  3724 D HtcModeClient: connectState: POWERCONNECTED_READY = true
,03-19 11:45:17.739   952  1764 D PMS     : releaseWL(192eaa77): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,03-19 11:45:17.749  3621  3621 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2fa77249
,03-19 11:45:17.749  1219  1219 D BluetoothAdapter: 56041548: getState(). Returning 11
03-19 11:45:17.749  1219  1219 I QuickSettingMiniLite: updateLiteState:no connect device!
,03-19 11:45:17.749  3621  3771 D HeadsetDualPhoneStateListener_SLOT1: listen phone state by slot:SLOT1  id:-1
03-19 11:45:17.749  3660  3722 I DeviceManagement: ConfigManagerController: Retrieving config content from cache: appID=com.htc.backup includeMeta=true
,03-19 11:45:17.749  3621  3771 D HeadsetDualPhoneStateListener_SLOT2: listen phone state by slot:SLOT2  id:-100
03-19 11:45:17.749  3621  3771 I HeadsetStateMachine: setCurrentDevice, the latest mCurrentDevice is:null
03-19 11:45:17.749  3621  3771 D bt-btif : BTHF: set_current_device
,03-19 11:45:17.749   952   952 D BluetoothA2dp: Proxy object connected
,03-19 11:45:17.749  3621  3621 D A2dpService: Received start request. Starting profile...
,03-19 11:45:17.749  3621  3621 V Avrcp   : make
,03-19 11:45:17.759   952   952 D BluetoothAdapter: 358501123: getState(). Returning 11,
,03-19 11:45:17.759  3660  3722 I DeviceManagement: WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@1debea05]
,03-19 11:45:17.759  3660  3660 I DeviceManagement: WorkflowService: Stopping workflow service
,03-19 11:45:17.769  3621  3621 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,03-19 11:45:17.769  3621  3621 D A2dpStateMachine: make
03-19 11:45:17.769   952  1043 D StatusBarManagerService: setSystemUiVisibility(0xc0000700)
03-19 11:45:17.769   952  1043 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
03-19 11:45:17.769   952  1043 D StatusBarManagerService: hiding MENU key
,03-19 11:45:17.769   952  1764 I ActivityManager: Killing 2959:com.google.android.partnersetup/u0a27 (adj 15): empty #17
03-19 11:45:17.769   952  1764 D Process : killProcessQuiet, pid=2959
,03-19 11:45:17.769   952  1764 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
03-19 11:45:17.779  3621  3621 D bt-btif : btif_av_state_idle_handler event:BTIF_SM_ENTER_EVT flags 0
,03-19 11:45:17.779  3621  3621 D A2dpService: setA2dpService(): set to: null
03-19 11:45:17.779  3621  3621 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2fa77249
03-19 11:45:17.789  3621  3818 D A2dpStateMachine: Enter Disconnected: -2
03-19 11:45:17.789  3791  3791 D HtcBtWidget_BTWidgetProvider: onBTStateChanged() for widget: 
03-19 11:45:17.789  3791  3791 D HtcBtWidget_BTWidgetProvider: updateWidget(context) for widget: 
03-19 11:45:17.799  3621  3621 D HidService: Received start request. Starting profile...
03-19 11:45:17.799  3621  3621 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2fa77249
,03-19 11:45:17.799  3621  3621 D HealthService: Received start request. Starting profile...
,03-19 11:45:17.809  3621  3621 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2fa77249
,03-19 11:45:17.809  3747  3747 D CustomizationManager:  Read ACC file spent 0.042 (s)
03-19 11:45:17.809  3621  3621 D PanService: Received start request. Starting profile...
03-19 11:45:17.809  3747  3747 D CIDMapFileReader: Parsing tag item name = HTC__001
03-19 11:45:17.809  3747  3747 D CIDMapFileReader: Parsing tag item name = HTC__102
03-19 11:45:17.809  3747  3747 D CIDMapFileReader: Parsing tag item name = HTC__Y13
03-19 11:45:17.809  3747  3747 D CIDMapFileReader: Parsing tag item name = HTC__032
03-19 11:45:17.809  3747  3747 D CIDMapFileReader: Parsing tag item name = HTC__M27
03-19 11:45:17.809  3747  3747 D CIDMapFileReader: Parsing tag item name = HTC__002
03-19 11:45:17.809  3747  3747 D CIDMapFileReader: Parsing tag item name = HTC__031
03-19 11:45:17.819  3747  3747 V CustomizationCIDLoader: full path : /system/customize/CID/HTC__102.xml
,03-19 11:45:17.819  3747  3747 I CustomizationCIDLoader: Parsing tag category name = system
,03-19 11:45:17.819  3747  3747 I CustomizationCIDLoader: Parsing tag category name = application
03-19 11:45:17.819  3747  3747 I CustomizationCIDLoader: Parsing tag category name = SettingsProvider
03-19 11:45:17.819  3747  3747 I CustomizationCIDLoader: Parsing tag category name = AutomotiveHome
,03-19 11:45:17.819  3747  3747 I CustomizationCIDLoader: Parsing tag category name = AudioService
03-19 11:45:17.819  3747  3747 I CustomizationCIDLoader: Parsing tag category name = Settings
03-19 11:45:17.819  3747  3747 I CustomizationCIDLoader: Parsing tag category name = ACC
,03-19 11:45:17.819  3747  3747 I CustomizationCIDLoader: add string-array item, value = 42507
03-19 11:45:17.819  3747  3747 I CustomizationCIDLoader: add string-array item, value = 21902
03-19 11:45:17.819  3747  3747 I CustomizationCIDLoader: add string-array item, value = 26006:26001.26002.26003
03-19 11:45:17.819  3747  3747 I CustomizationCIDLoader: add string-array item, value = 23420
03-19 11:45:17.819  3747  3747 I CustomizationCIDLoader: add string-array item, value = 22299
03-19 11:45:17.819  3747  3747 I CustomizationCIDLoader: add string-array item, value = 24002
03-19 11:45:17.819  3747  3747 I CustomizationCIDLoader: add string-array item, value = 23210
03-19 11:45:17.819  3747  3747 I CustomizationCIDLoader: add string-array item, value = 23205
03-19 11:45:17.819  3747  3747 I CustomizationCIDLoader: add string-array item, value = 23806
03-19 11:45:17.819  3747  3747 I CustomizationCIDLoader: add string-array item, value = 23430
,03-19 11:45:17.819  3747  3747 I CustomizationCIDLoader: add string-array item, value = 23408
03-19 11:45:17.819  3747  3747 I CustomizationCIDLoader: add string-array item, value = 27205
03-19 11:45:17.819  3747  3747 I CustomizationCIDLoader: add string-array item, value = 42507:C:1:0
03-19 11:45:17.819  3747  3747 I CustomizationCIDLoader: add string-array item, value = 21902:C:1:0
03-19 11:45:17.819  3747  3747 I CustomizationCIDLoader: add string-array item, value = 26006:D:1:0
03-19 11:45:17.819  3747  3747 I CustomizationCIDLoader: add string-array item, value = 23420:D:0:0
03-19 11:45:17.819  3747  3747 I CustomizationCIDLoader: add string-array item, value = 22299:D:0:0
03-19 11:45:17.819  3747  3747 I CustomizationCIDLoader: add string-array item, value = 24002:D:0:0
03-19 11:45:17.819  3747  3747 I CustomizationCIDLoader: add string-array item, value = 23210:D:2:0
,03-19 11:45:17.819  3747  3747 I CustomizationCIDLoader: add string-array item, value = 23205:D:0:0
03-19 11:45:17.819  3747  3747 I CustomizationCIDLoader: add string-array item, value = 23806:D:0:0
03-19 11:45:17.819  3747  3747 I CustomizationCIDLoader: add string-array item, value = 23430:C:1:0
03-19 11:45:17.819  3747  3747 I CustomizationCIDLoader: add string-array item, value = 23408:C:1:0
03-19 11:45:17.819  3747  3747 I CustomizationCIDLoader: add string-array item, value = 27205:C:1:0
03-19 11:45:17.819  3747  3747 D CustomizationManager:  Read CID file spent 0.099 (s)
03-19 11:45:17.819  3747  3747 D CustomizationManager:  All configurations done spent 0.099 (s)
,03-19 11:45:17.829  3621  3621 D PanService: HTC_CUSTOMIZATION_MHS_ENABLE = false
,03-19 11:45:17.829  3621  3621 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2fa77249
,03-19 11:45:17.829  3621  3621 D BtGatt.DebugUtils: handleDebugAction() action=null
03-19 11:45:17.829  3621  3621 D BtGatt.GattService: Received start request. Starting profile...
03-19 11:45:17.829  3621  3621 D BtGatt.GattService: start()
,03-19 11:45:17.829  3621  3621 D BtGatt.AdvertiseManager: advertise manager created
,03-19 11:45:17.839   952   952 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 7,
,03-19 11:45:17.839  1219  1219 D WIFI_ICON: WifiActivity: 1
03-19 11:45:17.839   952   952 E WifiTrafficPoller:  packet count Tx=46 Rx=52
03-19 11:45:17.849  1219  1219 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
03-19 11:45:17.839   952   952 E WifiTrafficPoller: notifying of data activity 1
,03-19 11:45:17.869   952  1714 D PackageManager: deletePackageAsUser: pkg=com.test.thalitest, pid=3747, uid=2000 userid=0
,03-19 11:45:17.929   952  1385 I ActivityManager: Recipient 2959
,03-19 11:45:17.989   952  1764 D Process : killProcessQuiet, pid=3173
03-19 11:45:17.989   952  1764 I ActivityManager: Killing 3173:com.google.android.music:main/u0a159 (adj 15): empty #17
03-19 11:45:17.989   952  1764 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,03-19 11:45:18.089   952  1248 I ActivityManager: Recipient 3173,
03-19 11:45:18.089   952  1694 D MediaRouterService: Client com.google.android.music (pid 3173): Died!
,03-19 11:45:18.109   952  1031 D Process : killProcessQuiet, pid=3478,
03-19 11:45:18.109   952  1031 I ActivityManager: Force stopping com.test.thalitest appid=10195 user=-1: uninstall pkg
,03-19 11:45:18.109   952  1031 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.removeProcessLocked:6363 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:6161 
03-19 11:45:18.109   952  1031 I ActivityManager: Killing 3478:com.test.thalitest/u0a195 (adj 1): stop com.test.thalitest
,03-19 11:45:18.119  3621  3621 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2fa77249,
,03-19 11:45:18.129  3594  3620 E htcbackup-core: BackupRestoreManager: Storage is not configured
,03-19 11:45:18.159  3594  3620 E htcbackup-core: BackupStatus: Ignoring failure message - backup already failed with message:  CONNECTION_FAIL_STORAGE,
,03-19 11:45:18.189   952  1068 W PackageSettings: Skipping PackageSetting{1648237b com.example.hello/10374} due to missing metadata
,03-19 11:45:18.209  3621  3621 I HeadsetPhoneState: updateServiceState service = 0,roam = 0,
03-19 11:45:18.209  3621  3621 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
03-19 11:45:18.209  3621  3771 D HeadsetStateMachine: Disconnected process message: 11, size: 0
,03-19 11:45:18.209  3621  3771 D HeadsetStateMachine: Disconnected process message: 10, size: 0,
03-19 11:45:18.209  3621  3771 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
03-19 11:45:18.209  3621  3771 D HeadsetStateMachine: Disconnected process message: 11, size: 0
03-19 11:45:18.219  1407  1407 D BluetoothAdapter: 702526949: getState(). Returning 11,
03-19 11:45:18.219  1407  1407 W BluetoothHeadset: Proxy not attached to service
03-19 11:45:18.219  3621  3718 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
,03-19 11:45:18.219  3621  3829 I bt-btu  : btu_task pending for preload complete event
,03-19 11:45:18.219  1407  1407 D BluetoothHeadset: java.lang.Throwable,
03-19 11:45:18.219  1407  1407 D BluetoothHeadset: 	at android.bluetooth.BluetoothHeadset.phoneStateChanged(BluetoothHeadset.java:827)
03-19 11:45:18.219  1407  1407 D BluetoothHeadset: 	at com.android.phone.BluetoothPhoneService.handleQueryPhoneState(BluetoothPhoneService.java:663)
03-19 11:45:18.219  1407  1407 D BluetoothHeadset: 	at com.android.phone.BluetoothPhoneService.access$500(BluetoothPhoneService.java:79)
03-19 11:45:18.219  1407  1407 D BluetoothHeadset: 	at com.android.phone.BluetoothPhoneService$1.handleMessage(BluetoothPhoneService.java:277)
03-19 11:45:18.219  1407  1407 D BluetoothHeadset: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-19 11:45:18.219  1407  1407 D BluetoothHeadset: 	at android.os.Looper.loop(Looper.java:155)
03-19 11:45:18.219  1407  1407 D BluetoothHeadset: 	at android.app.ActivityThread.main(ActivityThread.java:5721)
03-19 11:45:18.219  1407  1407 D BluetoothHeadset: 	at java.lang.reflect.Method.invoke(Native Method)
03-19 11:45:18.219  1407  1407 D BluetoothHeadset: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-19 11:45:18.219  1407  1407 D BluetoothHeadset: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
03-19 11:45:18.219  1407  1407 D BluetoothHeadset: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,03-19 11:45:18.219  3621  3718 E bt_vendor: get_bt_soc_type: Failed to get soc type,
,03-19 11:45:18.229   952   986 I ActivityManager: Recipient 3478,
03-19 11:45:18.229  1357  1357 E InputEventReceiver: Looper::removeFd(68) is failed, result(0), input channel 'ClientState{2cfd7f48 uid 10195 pid 3478} (c)'
03-19 11:45:18.239   952   983 I WindowState: WIN DEATH: Window{1b59f5eb u0 com.test.thalitest/com.test.thalitest.MainActivity EXITING}
03-19 11:45:18.239   952  1152 D WifiService: Client connection lost with reason: 4
,03-19 11:45:18.249  3832  3832 I qcom-bluetooth: /system/etc/init.qcom.bt.bluedroid.sh: init.qcom.bt.bluedroid.sh config =  
,03-19 11:45:18.289  3838  3838 I qcom-bluetooth: /system/etc/init.qcom.bt.bluedroid.sh: Transport : smd 
,03-19 11:45:18.299  3839  3839 I qcom-bluetooth: /system/etc/init.qcom.bt.bluedroid.sh: ** Bluedroid stack ** 
,03-19 11:45:18.309  3841  3841 I qcom-bluetooth: /system/etc/init.qcom.bt.bluedroid.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,03-19 11:45:18.319  3842  3842 I qcom-bluetooth: /system/etc/init.qcom.bt.bluedroid.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> ,
03-19 11:45:18.329  3845  3845 I qcom-bluetooth: /system/etc/init.qcom.bt.bluedroid.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
03-19 11:45:18.329   952  1045 I Choreographer: Skipped 31 frames!  The application may be doing too much work on its main thread.
,03-19 11:45:18.329  3594  3620 W System.err: Starting the HTTP client
,03-19 11:45:18.329   952   986 W ActivityManager: Spurious death for ProcessRecord{221586e3 3478:com.test.thalitest/u0a195}, curProc for 3478: null
,03-19 11:45:18.329   952  1068 I ActivityManager: Force stopping com.test.thalitest appid=10195 user=0: pkg removed
,03-19 11:45:18.339  3846  3846 I qcom-bluetooth: /system/etc/init.qcom.bt.bluedroid.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,03-19 11:45:18.349  3594  3620 W htcbackup-core: BackupServiceClientResourceProxy: Reseting appServerErrorCount
,03-19 11:45:18.359  1455  2026 W OpenGLRenderer: Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
,03-19 11:45:18.379  1295  1295 D DotMatrix: [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest,
,03-19 11:45:18.379  1295  1295 D DotMatrix: [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
03-19 11:45:18.379  1295  1295 D DotMatrix: [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
03-19 11:45:18.389  3564  3850 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
03-19 11:45:18.389  3564  3850 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
03-19 11:45:18.389   952   986 D PMS     : acquireWL(2c223a5e): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1834 10024 WorkSource{10024 com.google.android.gms}
03-19 11:45:18.389  1834  2232 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
03-19 11:45:18.399   952  1148 D PMS     : acquireWL(3b0fae3f): PARTIAL_WAKE_LOCK  NetworkStats 0x1 952 1000 null
03-19 11:45:18.399   952  1385 D PMS     : releaseWL(2c223a5e): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
03-19 11:45:18.399   952  1764 I ActivityManager: Killing 2050:com.htc.bgp/u0a11 (adj 15): empty #17
03-19 11:45:18.399   952  1149 V NetworkPolicy: ACTION_UID_REMOVED for uid=10195
03-19 11:45:18.399   952  1764 D Process : killProcessQuiet, pid=2050
03-19 11:45:18.399   952  1764 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,03-19 11:45:18.409  3752  3752 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.powersaver.PowerSaverNotificationReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
03-19 11:45:18.409  3594  3620 W htcbackup-core: BackupRestoreManager: No sense account found - aborting
03-19 11:45:18.409  2981  3027 D AccTypeManager: Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
,03-19 11:45:18.409  3594  3620 I htcbackup-core: BackupRestoreManager: DM is not ready, pending resume
,03-19 11:45:18.419   952  1143 W SystemReader: Cannot find grip_rejection_width, use default value instead
03-19 11:45:18.419  1716  2117 D AccTypeManager: Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
,03-19 11:45:18.439  2981  3027 D AccTypeManager: Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,03-19 11:45:18.439  1407  1407 D PhoneApp: -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
,03-19 11:45:18.439  1716  2117 D AccTypeManager: Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,03-19 11:45:18.449  1455  1455 I art     : Explicit concurrent mark sweep GC freed 20721(1473KB) AllocSpace objects, 12(1348KB) LOS objects, 34% free, 30MB/46MB, paused 1.114ms total 88.644ms
,03-19 11:45:18.459  1455  2002 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
03-19 11:45:18.459  1455  2002 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,03-19 11:45:18.469  1716  2117 D AccTypeManager: Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,03-19 11:45:18.489  1716  2117 E ExternalAccountType: Unsupported attribute readOnly
,03-19 11:45:18.509   952   952 W PackageManager: Unable to load service info ResolveInfo{14f2654b com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000},
03-19 11:45:18.509   952   952 W PackageManager: org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
03-19 11:45:18.509   952   952 W PackageManager: 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:475)
03-19 11:45:18.509   952   952 W PackageManager: 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:331),
03-19 11:45:18.509   952   952 W PackageManager: 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
03-19 11:45:18.509   952   952 W PackageManager: 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
03-19 11:45:18.509   952   952 W PackageManager: 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
03-19 11:45:18.509   952   952 W PackageManager: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
,03-19 11:45:18.509   952   952 W PackageManager: 	at android.os.Handler.handleCallback(Handler.java:739)
03-19 11:45:18.509   952   952 W PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:95)
03-19 11:45:18.509   952   952 W PackageManager: 	at android.os.Looper.loop(Looper.java:155)
03-19 11:45:18.509   952   952 W PackageManager: 	at com.android.server.SystemServer.run(SystemServer.java:324)
03-19 11:45:18.509   952   952 W PackageManager: 	at com.android.server.SystemServer.main(SystemServer.java:225)
03-19 11:45:18.509   952   952 W PackageManager: 	at java.lang.reflect.Method.invoke(Native Method)
03-19 11:45:18.509   952   952 W PackageManager: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-19 11:45:18.509   952   952 W PackageManager: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
03-19 11:45:18.509   952   952 W PackageManager: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,03-19 11:45:18.519   952  2376 I ActivityManager: Recipient 2050,
,03-19 11:45:18.539  2981  3027 D AccTypeManager: Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,03-19 11:45:18.559  2981  3027 E ExternalAccountType: Unsupported attribute readOnly
,03-19 11:45:18.569   952  1068 I art     : Explicit concurrent mark sweep GC freed 24733(1737KB) AllocSpace objects, 9(372KB) LOS objects, 33% free, 18MB/27MB, paused 1.777ms total 194.913ms
,03-19 11:45:18.579   952   952 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,03-19 11:45:18.619  3852  3852 I qcom-bluetooth: /system/etc/init.qcom.bt.bluedroid.sh: = Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 90:e7:c4:f6:69:77 
,03-19 11:45:18.629  3855  3855 I qcom-bluetooth: /system/etc/init.qcom.bt.bluedroid.sh: ** Bluedroid stack ** 
,03-19 11:45:18.629  3621  3621 D BluetoothMasReceiver: Bluetooth STATE CHANGED to 11
,03-19 11:45:18.639   952  1694 I ActivityManager: Start proc com.htc.calendar for broadcast com.htc.calendar/.AlertReceiver: pid=3857 uid=10010 gids={50010, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a,
,03-19 11:45:18.649  3621  3621 V BluetoothSapReceiver: SapReceiver onReceive 
03-19 11:45:18.649  3752  3854 D PowerSaverNotificationService: updateNotification, mToggle = false
,03-19 11:45:18.649   952  1694 I ActivityManager: Killing 3263:com.google.android.setupwizard/u0a77 (adj 15): empty #17
03-19 11:45:18.649  3621  3621 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
03-19 11:45:18.649   952  1694 D Process : killProcessQuiet, pid=3263
03-19 11:45:18.649  3621  3621 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
03-19 11:45:18.649  3621  3621 V BluetoothSapReceiver: startService = false
03-19 11:45:18.649   952  1694 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,03-19 11:45:18.649   952  1148 D PMS     : releaseWL(3b0fae3f): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
03-19 11:45:18.649   952  1149 V NetworkPolicy: writePolicyLocked(),
,03-19 11:45:18.669   952  1149 V NetworkPolicy: updateNetworkEnabledLocked()
03-19 11:45:18.669   952  1149 V NetworkPolicy: updateNotificationsLocked()
,03-19 11:45:18.689  3621  3829 I bt-btu  : btu_task received preload complete event
03-19 11:45:18.689  3621  3829 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
03-19 11:45:18.689  3621  3829 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
,03-19 11:45:18.689  3621  3829 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
03-19 11:45:18.689  3621  3829 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x1487
,03-19 11:45:18.689   952   983 D PMS     : acquireWL(2bb3d50b): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 3621 1002 null
,03-19 11:45:18.689  3621  3829 D bt-btm  : btm_acl_device_down
03-19 11:45:18.689  3621  3829 D bt-btm  : btm_acl_reset_paging
03-19 11:45:18.689  3621  3829 D bt-btm  : btm_acl_set_discing,
,03-19 11:45:18.749   952  1715 I ActivityManager: Recipient 3263,
,03-19 11:45:18.759  3621  3829 I bt-btm  : btm_reset_complete
03-19 11:45:18.759  3621  3829 I bt-btm  : BTM_SetPinType: pin type 0 [variable-0, fixed-1], code , length 0
,03-19 11:45:18.759  3621  3829 D bt-btm  : Start reading local supported commands
,03-19 11:45:18.759  3621  3829 D bt-btm  : btm_read_local_supported_cmds_complete status (0x00)
,03-19 11:45:18.759  3621  3829 D bt-btm  : BTM reads next extended features page (1)
,03-19 11:45:18.769  3621  3829 D bt-btm  : BTM reads next extended features page (2)
03-19 11:45:18.769  3621  3829 D bt-btm  : BTM reached last extended features page (2)
,03-19 11:45:18.769  3621  3829 D bt-btm  : btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x3f
03-19 11:45:18.769  3621  3829 D bt-btm  : btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x3d
,03-19 11:45:18.769  3621  3829 D bt-btm  : btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x31
03-19 11:45:18.769  3621  3829 I bt-btm  : BTM: BTM_VendorSpecificCommand: Opcode: 0xFD53, ParamLen: 0.
,03-19 11:45:18.769  3621  3829 D bt-btm  : btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x11
,03-19 11:45:18.769  3621  3829 I bt-btm  : btm_vendor_capability_vsc_cmpl_cback: status=0
03-19 11:45:18.769  3621  3829 D bt-btm  : btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x01
,03-19 11:45:18.769  3621  3829 D bt-btm  : btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x00
03-19 11:45:18.769  3621  3829 D bt-btm  : btm_read_ble_wl_size 
,03-19 11:45:18.769  3621  3829 D bt-btm  : btm_read_white_list_size_complete 
03-19 11:45:18.769  3621  3829 D bt-btm  : btm_get_ble_buffer_size 
03-19 11:45:18.769  3621  3829 D bt-btm  : btm_read_ble_buf_size_complete 
03-19 11:45:18.769  3621  3829 D bt-btm  : btm_read_ble_local_supported_states 
03-19 11:45:18.769  3621  3829 D bt-btm  : btm_read_ble_local_supported_states_complete 
03-19 11:45:18.769  3621  3829 D bt-btm  : btm_read_ble_local_supported_features 
,03-19 11:45:18.769  3621  3829 D bt-btm  : btm_read_ble_local_supported_features_complete 
03-19 11:45:18.769  3621  3829 D bt-btm  : btm_reset_ctrlr_complete: max_page_number: 2
03-19 11:45:18.769  3621  3829 D bt-btm  : btm_decode_ext_features_page page: 0
03-19 11:45:18.769  3621  3829 D bt-btm  : Local supported ACL packet types: 0xcc18
03-19 11:45:18.769  3621  3829 D bt-btm  : Local supported SCO packet types: 0x038f
03-19 11:45:18.769  3621  3829 I bt-btm  : BTM_SEC_REG[2]: id 42, is_orig 0, psm 0x0003, proto_id 3, chan_id 0
,03-19 11:45:18.769  3621  3829 I bt-btm  :                : sec: 0x80, service name [RFC_MUX] (up to 21 chars saved)
03-19 11:45:18.769  3621  3829 D bt-btm  : btm_sec_dev_reset sec mode: 4
03-19 11:45:18.769  3621  3829 I bt-btm  : BTM_SetInquiryMode
03-19 11:45:18.769  3621  3829 I bt-btm  : BTM_SetPageScanType
03-19 11:45:18.769  3621  3829 I bt-btm  : BTM_SetInquiryScanType,
03-19 11:45:18.769  3621  3829 D bt-btm  : btm_decode_ext_features_page page: 1
03-19 11:45:18.769  3621  3829 W bt-btm  : btm_decode_ext_features_page Secure conn Host support Enabled
03-19 11:45:18.769  3621  3829 D bt-btm  : btm_decode_ext_features_page page: 2
,03-19 11:45:18.769  3621  3829 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
03-19 11:45:18.769  3621  3829 D bt-btm  : BTM_BleLoadLocalKeys
03-19 11:45:18.769  3621  3829 D bt-btm  : BTM_BleLoadLocalKeys
03-19 11:45:18.769  3621  3829 I bt-btm  : BTM_Sec: application registered
03-19 11:45:18.769  3621  3829 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xdf7804d5 
03-19 11:45:18.769  3621  3829 I bt-btm  : BTM_Sec: SMP_Register( btm_proc_smp_cback )
03-19 11:45:18.769  3621  3829 I bt-smp  : SMP_Register state=0
,03-19 11:45:18.769  3621  3829 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xdf7804d5 
03-19 11:45:18.769  3621  3829 I bt-btm  : BTM_Sec: application registered
03-19 11:45:18.769  3621  3829 D bt-btm  : BTM_SetDefaultLinkSuperTout
03-19 11:45:18.769  3621  3829 I bt-btm  : BTM: BTM_WritePageTimeout: Timeout: 8192.
03-19 11:45:18.769  3621  3829 D bt-btm  : BTM_SetDefaultLinkPolicy setting:0x000f
03-19 11:45:18.769  3621  3829 D bt-btm  : BTM_SetDefaultLinkPolicy park not supported (settings: 0x0007)
03-19 11:45:18.769  3621  3829 D bt-btm  : Set DefaultLinkPolicy:0x0007
03-19 11:45:18.769  3621  3829 D bt-btm  : BTM_RegBusyLevelNotif
03-19 11:45:18.769  3621  3829 D bt-btm  : BTM_BleReadControllerFeatures
03-19 11:45:18.769  3621  3829 I bt-btm  : BTM: BTM_VendorSpecificCommand: Opcode: 0xFD53, ParamLen: 0.
03-19 11:45:18.769  3621  3829 I bt-att  : GATT_Register
03-19 11:45:18.769  3621  3829 D bt-att  : UUID=[0x87878787878787878787878787878787]
03-19 11:45:18.769  3621  3829 I bt-att  : allocated gatt_if=3
03-19 11:45:18.769  3621  3829 I bt-att  : GATT_StartIf gatt_if=3
03-19 11:45:18.769  3621  3829 D bt-att  : gatt_find_the_connected_bda start_idx=0
03-19 11:45:18.769  3621  3829 D bt-att  : gatt_find_the_connected_bda found=0 found_idx=16
03-19 11:45:18.779  3621  3829 D bt-btm  : btm_ble_vendor_capability_vsc_cmpl_cback
03-19 11:45:18.779  3621  3829 D bt-btm  : btm_ble_vnd_cap_vsc_cmpl_cback: stat=0, irk=0, ADV ins:10, rpa=1, ener=1
03-19 11:45:18.779  3621  3829 I bt-btm  : BTM Register For VSEvents is successfully
03-19 11:45:18.779  3621  3727 D bt-btm  : BTM_BleGetVendorCapabilities
03-19 11:45:18.779  3621  3727 I bt-btif : HAL bt_hal_cbacks->adapter_properties_cb
03-19 11:45:18.779  3621  3727 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 0 mOffloadedScanResultStorageBytes= 0 mIsActivityAndEnergyReporting = true
03-19 11:45:18.779  3621  3829 D bt-btm  : bta_dm_set_dev_name: name: HTC One M8s 
03-19 11:45:18.779  3621  3829 I bt-btm  : Write Extended Inquiry Response to controller
03-19 11:45:18.779  3621  3829 I bt-btm  :  BTM_BleConfigPrivacy
03-19 11:45:18.779  3621  3829 I bt-btm  : btm_gen_resolvable_private_addr
03-19 11:45:18.779  3621  3829 I bt-btm  : btm_gen_resolvable_private_addr
03-19 11:45:18.779  3621  3829 I bt-btm  : btm_gen_resolvable_private_addr
03-19 11:45:18.779  3621  3829 I bt-btm  : btm_gen_resolvable_private_addr
03-19 11:45:18.779  3621  3829 I bt-btm  : btm_gen_resolvable_private_addr
03-19 11:45:18.779  3621  3829 I bt-btm  : btm_gen_resolvable_private_addr
03-19 11:45:18.779  3621  3829 I bt-btm  : btm_gen_resolvable_private_addr
03-19 11:45:18.779  3621  3829 I bt-btm  : btm_gen_resolvable_private_addr
03-19 11:45:18.779  3621  3829 I bt-btm  : btm_gen_resolvable_private_addr
03-19 11:45:18.779  3621  3829 I bt-btm  : btm_gen_resolvable_private_addr
03-19 11:45:18.779  3621  3829 I bt-btm  : BTM: BTM_WriteVoiceSettings: Settings: 0x0060.
03-19 11:45:18.779  3621  3829 D bt-btif : AG evt (hdl 0x0001): State 0, Event 0x0500
03-19 11:45:18.779  3621  3829 D bt-sdp  : SDP_CreateRecord ok, num_records:3
03-19 11:45:18.779  3621  3829 D bt-btm  : BTM_AllocateSCN
03-19 11:45:18.779  3621  3829 I bt-btm  : Write Extended Inquiry Response to controller
03-19 11:45:18.779  3621  3829 D bt-sdp  : SDP_CreateRecord ok, num_records:4
03-19 11:45:18.779  3621  3829 D bt-btm  : BTM_AllocateSCN
03-19 11:45:18.779  3621  3829 I bt-btm  : Write Extended Inquiry Response to controller
03-19 11:45:18.779  3621  3829 I bt-btm  : BTM_SEC_REG[3]: id 12, is_orig 0, psm 0x0003, proto_id 3, chan_id 2
03-19 11:45:18.779  3621  3829 I bt-btm  :                : sec: 0x1086, service name [] (up to 21 chars saved)
03-19 11:45:18.779  3621  3829 I bt-btm  : BTM_SEC_REG[4]: id 29, is_orig 0, psm 0x0003, proto_id 3, chan_id 3
03-19 11:45:18.779  3621  3829 I bt-btm  :     ,           : sec: 0x1086, service name [] (up to 21 chars saved)
03-19 11:45:18.779  3621  3829 D bt-btif : AG evt (hdl 0x0002): State 0, Event 0x0500
03-19 11:45:18.779  3621  3829 I bt-btm  : BTM_SEC_REG[3]: id 12, is_orig 0, psm 0x0003, proto_id 3, chan_id 2
03-19 11:45:18.779  3621  3829 I bt-btm  :                : sec: 0x1086, service name [] (up to 21 chars saved)
03-19 11:45:18.779  3621  3829 I bt-btm  : BTM_SEC_REG[4]: id 29, is_orig 0, psm 0x0003, proto_id 3, chan_id 3
03-19 11:45:18.779  3621  3829 I bt-btm  :                : sec: 0x1086, service name [] (up to 21 chars saved)
03-19 11:45:18.779  3621  3829 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
03-19 11:45:18.779  3621  3829 I bt-btm  : BTM_SEC_REG[5]: id 37, is_orig 1, psm 0x0019, proto_id 7, chan_id 0
03-19 11:45:18.779  3621  3829 I bt-btm  :                : sec: 0x2090, service name [] (up to 21 chars saved)
03-19 11:45:18.779  3621  3829 I bt-btm  : BTM_SEC_REG[5]: id 37, is_orig 0, psm 0x0019, proto_id 7, chan_id 0
03-19 11:45:18.779  3621  3829 I bt-btm  :                : sec: 0x3092, service name [] (up to 21 chars saved)
03-19 11:45:18.779  3621  3829 I bt-btm  : BTM_SEC_REG[6]: id 38, is_orig 1, psm 0x0019, proto_id 7, chan_id 1
03-19 11:45:18.779  3621  3829 I bt-btm  :                : sec: 0x80, service name [] (up to 21 chars saved)
03-19 11:45:18.779  3621  3829 I bt-btm  : BTM_SEC_REG[6]: id 38, is_orig 0, psm 0x0019, proto_id 7, chan_id 1
03-19 11:45:18.779  3621  3829 I bt-btm  :                : sec: 0x80, service name [] (up to 21 chars saved)
03-19 11:45:18.779  3621  3829 I bt-btm  : BTM_SEC_REG[6]: id 38, is_orig 1, psm 0x0019, proto_id 7, chan_id 2
03-19 11:45:18.779  3621  3829 I bt-btm  :                : sec: 0x80, service name [] (up to 21 chars saved)
03-19 11:45:18.779  3621  3829 I bt-btm  : BTM_SEC_REG[6]: id 38, is_orig 0, psm 0x0019, proto_id 7, chan_id 2
03-19 11:45:18.779  3621  3829 I bt-btm  :                : sec: 0x80, service name [] (up to 21 chars saved)
03-19 11:45:18.779  3621  3829 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
03-19 11:45:18.779  3621  3829 I bt-btm  : BTM_SEC_REG[7]: id 39, is_orig 1, psm 0x0017, proto_id 0, chan_id 0
03-19 11:45:18.779  3621  3829 I bt-btm  :                : sec: 0x2090, service name [] (up to 21 chars saved)
03-19 11:45:18.779  3621  3829 I bt-btm  : BTM_SEC_REG[7]: id 39, is_orig 0, psm 0x0017, proto_id 0, chan_id 0
03-19 11:45:18.779  3621  3829 I bt-btm  :                : sec: 0x3092, service name [] (up to 21 chars saved)
03-19 11:45:18.779  3621  3829 D bt-sdp  : SDP_CreateRecord ok, num_records:5
03-19 11:45:18.779  3621  3829 I bt-avp  : AVRC_AddRecord uuid: 110c
03-19 11:45:18.779  3621  3829 I bt-btm  : Write Extended Inquiry Response to controller
03-19 11:45:18.779  3621  3829 D bt-sdp  : SDP_CreateRecord ok, num_records:6
03-19 11:45:18.779  3621  3829 I bt-a2d  : A2D_AddRecord uuid: 110a
03-19 11:45:18.779  3621  3829 I bt-btm  : Write Extended Inquiry Response to controller
03-19 11:45:18.779  3621  3829 D bt-btif :  AVRC_Open AVRC_Open role: 1, control:3 status:0, handle:0
03-19 11:45:18.779  3621  3829 D bt-sdp  : SDP_CreateRecord ok, num_records:7
03-19 11:45:18.779  3621  3829 I bt-avp  : AVRC_AddRecord uuid: 110e
03-19 11:45:18.779  3621  3829 I bt-btm  : Write Extended Inquiry Response to controller
03-19 11:45:18.779  3621  3727 E bt-btif : Calling BTA_HhEnable
03-19 11:45:18.779  3621  3829 I bt-btm  : BTM_SEC_REG[8]: id 32, is_orig 0, psm 0x0011, proto_id 6, chan_id 1
03-19 11:45:18.779  3621  3829 I bt-btm  :                : sec: 0x86, service name [] (up to 21 chars saved)
03-19 11:45:18.779  3621  3829 I bt-btm  : BTM_SEC_REG[8]: id 32, is_orig 1, psm 0x0011, proto_id 6, chan_id 1
03-19 11:45:18.779  3621  3829 I bt-btm  :                : sec: 0xb6, service name [] (up to 21 chars saved)
03-19 11:45:18.779  3621  3829 I bt-btm  : BTM_SEC_REG[9]: id 33, is_orig 0, psm 0x0011, proto_id 6, chan_id 2
03-19 11:45:18.779  3621  3829 I bt-btm  :                : sec: 0x80, service name [] (up to 21 chars saved)
03-19 11:45:18.779  3621  3829 I bt-btm  : BTM_SEC_REG[9]: id 33, is_orig 1, psm 0x0011, proto_id 6, chan_id 2
03-19 11:45:18.779  3621  3829 I bt-btm  :                : sec: 0x80, service name [] (up to 21 chars saved)
03-19 11:45:18.779  3621  3829 I bt-btm  : BTM_SEC_REG[10]: id 34, is_orig 1, psm 0x0013, proto_id 6, chan_id 0
03-19 11:45:18.779  3621  3829 I bt-btm  :                : sec: 0x80, service name [] (up to 21 chars saved)
03-19 11:45:18.779  3621  3829 I bt-btm  : BTM_SEC_REG[10]: id 34, is_orig 0, psm 0x0013, proto_id 6, chan_id 0
03-19 11:45:18.779  3621  3829 I bt-btm  :                : sec: 0x80, service name [] (up to 21 chars saved)
03-19 11:45:18.779  3621  3829 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
03-19 11:45:18.779  3621  3829 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
03-19 11:45:18.779  3621  3829 I bt-att  : GATT_Register
03-19 11:45:18.779  3621  3829 D bt-att  : UUID=[0x0000454c205245564f20484820415442]
03-19 11:45:18.779  3621  3829 I bt-att  : allocated gatt_if=4
03-19 11:45:18.779  3621  3829 I bt-att  : GATT_StartIf gatt_if=4
03-19 11:45:18.779  3621  3829 D bt-att  : gatt_find_the_connected_bda start_idx=0
03-19 11:45:18.779  3621  3829 D bt-att  : gatt_find_the_connected_bda found=0 found_idx=16
03-19 11:45:18.779  3621  3727 I bt-btif : BTA_MceEnable
03-19 11:45:18.779  3621  3727 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
03-19 11:45:18.779  3621  3727 I bt-btif : HAL bt_hal_cbacks->adapter_properties_cb
03-19 11:45:18.779  3621  3727 D BluetoothAdapterProperties: Address is:90:E7:C4:F6:69:77
03-19 11:45:18.789  3621  3829 D bt-btm  : btm_ble_rand_enc_complete
03-19 11:45:18.789  3621  3829 I bt-btm  : btm_gen_resolve_paddr_low
03-19 11:45:18.789  3621  3829 D bt-smp  : smp_encrypt_data
03-19 11:45:18.789  3621  3829 W bt-smp  : Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
03-19 11:45:18.789  3621  3829 W bt-smp  : Plain text(LSB ~ MSB) = aa 21 59 00 00 00 00 00 00 00 00 00 00 00 00 00 
03-19 11:45:18.789  3621  3829 W bt-smp  : Encrypted text(LSB ~ MSB) = 47 78 4a e7 ec 6d 90 4a 1a 8b 41 e5 58 0f 2f ac 
03-19 11:45:18.789  3621  3829 I bt-btm  : btm_gen_resolve_paddr_cmpl
03-19 11:45:18.789  3621  3829 W bt-btm  : Stopping oneshot timer
03-19 11:45:18.789  3621  3829 D bt-btm  : Starting oneshot timer type:103 timeout:900s
03-19 11:45:18.799  3621  3829 D bt-btm  : btm_ble_rand_enc_complete
03-19 11:45:18.799  3621  3829 I bt-btm  : btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
03-19 11:45:18.799  3621  3829 D bt-smp  : smp_encrypt_data
03-19 11:45:18.799  3621  3829 W bt-smp  : Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
03-19 11:45:18.799  3621  3829 W bt-smp  : Plain text(LSB ~ MSB) = 26 16 5b 00 00 00 00 00 00 00 00 00 00 00 00 00 
03-19 11:45:18.799  3621  3829 W bt-smp  : Encrypted text(LSB ~ MSB) = 5a 4a e8 bd 9a 81 b6 5e 44 dd df f3 2a 70 69 c8 
03-19 11:45:18.799  3621  3829 D bt-btm  : btm_ble_rand_enc_complete
03-19 11:45:18.799  3621  3829 I bt-btm  : btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
03-19 11:45:18.799  3621  3829 D bt-smp  : smp_encrypt_data
03-19 11:45:18.799  3621  3829 W bt-smp  : Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
03-19 11:45:18.799  3621  3829 W bt-smp  : Plain text(LSB ~ MSB) = d3 ea 61 00 00 00 00 00 00 00 00 00 00 00 00 00 
03-19 11:45:18.799  3621  3829 W bt-smp  : Encrypted text(LSB ~ MSB) = 95 7b 11 f0 cb b5 86 5c e1 c7 7d 1b 12 10 53 f2 
03-19 11:45:18.809  3621  3829 D bt-btm  : btm_ble_rand_enc_complete
03-19 11:45:18.809  3621  3829 I bt-btm  : btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
03-19 11:45:18.809  3621  3829 D bt-smp  : smp_encrypt_data
03-19 11:45:18.809  3621  3829 W bt-smp  : Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
03-19 11:45:18.809  3621  3829 W bt-smp  : Plain text(LSB ~ MSB) = 4e e1 7c 00 00 00 00 00 00 00 00 00 00 00 00 00 
03-19 11:45:18.809  3621  3829 W bt-smp  : Encrypted text(LSB ~ MSB) = a9 b3 f7 f7 d3 51 1f 35 04 90 54 f3 0b 00 b5 81 
03-19 11:45:18.819  3621  3829 D bt-btm  : btm_ble_rand_enc_complete,
03-19 11:45:18.819  3621  3829 I bt-btm  : btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
03-19 11:45:18.819  3621  3829 D bt-smp  : smp_encrypt_data
03-19 11:45:18.819  3621  3829 W bt-smp  : Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
03-19 11:45:18.819  3621  3829 W bt-smp  : Plain text(LSB ~ MSB) = 71 9d 7d 00 00 00 00 00 00 00 00 00 00 00 00 00 
03-19 11:45:18.819  3621  3829 W bt-smp  : Encrypted text(LSB ~ MSB) = f8 74 c1 57 f6 09 7b a5 34 7a 5a e7 2e c7 90 71 
03-19 11:45:18.829  3621  3829 D bt-btm  : btm_ble_rand_enc_complete
03-19 11:45:18.829  3621  3829 I bt-btm  : btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
03-19 11:45:18.829  3621  3829 D bt-smp  : smp_encrypt_data
03-19 11:45:18.829  3621  3829 W bt-smp  : Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
03-19 11:45:18.829  3621  3829 W bt-smp  : Plain text(LSB ~ MSB) = a3 96 54 00 00 00 00 00 00 00 00 00 00 00 00 00 
03-19 11:45:18.829  3621  3829 W bt-smp  : Encrypted text(LSB ~ MSB) = 8d cc 59 b4 04 d8 13 0a 8c 2e fb eb f3 f1 68 41 
03-19 11:45:18.839  3621  3829 D bt-btm  : btm_ble_rand_enc_complete
03-19 11:45:18.839  3621  3829 I bt-btm  : btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
03-19 11:45:18.839  3621  3829 D bt-smp  : smp_encrypt_data
03-19 11:45:18.839  3621  3829 W bt-smp  : Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
03-19 11:45:18.839  3621  3829 W bt-smp  : Plain text(LSB ~ MSB) = af 48 4d 00 00 00 00 00 00 00 00 00 00 00 00 00 
03-19 11:45:18.839  3621  3829 W bt-smp  : Encrypted text(LSB ~ MSB) = 50 61 71 9f e0 cc f8 9d 50 8a 78 11 ce 7e 2c 0c 
03-19 11:45:18.839   952   952 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 6
03-19 11:45:18.839   952   952 E WifiTrafficPoller:  packet count Tx=46 Rx=54
03-19 11:45:18.849  3621  3829 D bt-btm  : btm_ble_rand_enc_complete
03-19 11:45:18.849  3621  3829 I bt-btm  : btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
03-19 11:45:18.849  3621  3829 D bt-smp  : smp_encrypt_data
03-19 11:45:18.849  3621  3829 W bt-smp  : Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
03-19 11:45:18.849  3621  3829 W bt-smp  : Plain text(LSB ~ MSB) = 32 ed 71 00 00 00 00 00 00 00 00 00 00 00 00 00 
03-19 11:45:18.849  3621  3829 W bt-smp  : Encrypted text(LSB ~ MSB) = fb 61 03 56 d3 df 3f 25 0c 0d 0c 68 80 68 4e c9 
03-19 11:45:18.849  3621  3829 D bt-btm  : btm_ble_rand_enc_complete
03-19 11:45:18.849  3621  3829 I bt-btm  : btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
03-19 11:45:18.849  3621  3829 D bt-smp  : smp_encrypt_data
03-19 11:45:18.849  3621  3829 W bt-smp  : Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
03-19 11:45:18.849  3621  3829 W bt-smp  : Plain text(LSB ~ MSB) = ac 66 75 00 00 00 00 00 00 00 00 00 00 00 00 00 
03-19 11:45:18.849  3621  3829 W bt-smp  : Encrypted text(LSB ~ MSB) = 4d 44 b6 93 b1 5d 72 f4 45 73 9d dc 96 95 6d b3 
,03-19 11:45:18.859  1883  1883 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,03-19 11:45:18.859  3621  3829 D bt-btm  : btm_ble_rand_enc_complete
,03-19 11:45:18.869   952  1140 V AlarmManager: sending alarm PendingIntent{23bcbb15: PendingIntentRecord{3f9a3e2a android broadcastIntent}}, i=com.android.server.WifiManager.action.START_SCAN, t=1, cnt=1, w=1458384318834, Int=20000
03-19 11:45:18.859  3621  3829 I bt-btm  : btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
03-19 11:45:18.859  3621  3829 D bt-smp  : smp_encrypt_data
03-19 11:45:18.859  3621  3829 W bt-smp  : Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
03-19 11:45:18.859  3621  3829 W bt-smp  : Plain text(LSB ~ MSB) = f0 55 43 00 00 00 00 00 00 00 00 00 00 00 00 00 
03-19 11:45:18.859  3621  3829 W bt-smp  : Encrypted text(LSB ~ MSB) = 3d 0d b1 da 50 3e cd d3 00 ed d5 ac 39 da c5 41 
,03-19 11:45:18.879  3621  3727 D BluetoothAdapterProperties: Scan Mode:21
03-19 11:45:18.879   952  1176 D TaskPersister: removeObsoleteFile: deleting file=12_task.xml
03-19 11:45:18.879  3621  3727 D BluetoothAdapterProperties: Discoverable Timeout:120
03-19 11:45:18.879   952  1176 D TaskPersister: removeObsoleteFile: deleting file=12_task_thumbnail.png
03-19 11:45:18.879  3621  3727 I bt-btif : BTA_JvEnable
03-19 11:45:18.879  3621  3727 I bt-btif : BTA_JvRegisterL2cCback
03-19 11:45:18.879  3621  3829 I bt-btm  : BTM_ReadConnectability
03-19 11:45:18.879  3621  3829 I bt-btm  : BTM_ReadDiscoverability
03-19 11:45:18.879  3621  3829 I bt-btm  : BTM_SetDiscoverability
03-19 11:45:18.879  3621  3829 I bt-btm  : btm_ble_set_discoverability mode=0x0 combined_mode=0x2
03-19 11:45:18.879  3621  3829 D bt-btm  : disc_mode 0002
03-19 11:45:18.879  3621  3829 D bt-btm  : btm_ble_update_adv_flag new=0x18
03-19 11:45:18.879  3621  3829 I bt-btm  : evt_type=0x0 p-cb->evt_type=0x3 
03-19 11:45:18.879  3621  3829 I bt-btm  : BTM_SetDiscoverability: mode 2 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
03-19 11:45:18.879  3621  3829 I bt-btm  : BTM_SetConnectability
03-19 11:45:18.879  3621  3829 I bt-btm  : btm_ble_set_connectability mode=0x0 combined_mode=0x1
03-19 11:45:18.879  3621  3829 D bt-btm  : disc_mode 0002
03-19 11:45:18.879  3621  3829 I bt-btm  : BTM_SetConnectability: mode 1 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
03-19 11:45:18.879  3621  3829 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
03-19 11:45:18.879  3621  3829 I bt-btm  : BTM_SetDiscoverability
03-19 11:45:18.879  3621  3829 I bt-btm  : btm_ble_set_discoverability mode=0x0 combined_mode=0x0
03-19 11:45:18.879  3621  3829 D bt-btm  : disc_mode 0000
03-19 11:45:18.879  3621  3829 I bt-btm  : evt_type=0x0 p-cb->evt_type=0x0 ,
03-19 11:45:18.879  3621  3829 I bt-btm  : BTM_SetDiscoverability: mode 0 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x1000
03-19 11:45:18.879  3621  3829 I bt-btm  : BTM_SetConnectability
03-19 11:45:18.879  3621  3829 I bt-btm  : btm_ble_set_connectability mode=0x0 combined_mode=0x0
03-19 11:45:18.879  3621  3829 D bt-btm  : disc_mode 0000
03-19 11:45:18.879  3621  3829 D bt-btm  : btm_ble_update_adv_flag new=0x1c
03-19 11:45:18.879  3621  3829 D bt-btm  : btm_ble_update_adv_flag old=0x18
03-19 11:45:18.879  3621  3829 I bt-btm  : BTM_SetConnectability: mode 0 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
03-19 11:45:18.879  3621  3829 I bt-btif : bta_pan_co_init
03-19 11:45:18.879  3621  3829 D bt-sdp  : SDP_CreateRecord ok, num_records:8
03-19 11:45:18.879  3621  3829 I bt-btm  : BTM_SEC_REG[11]: id 27, is_orig 1, psm 0x000f, proto_id 5, chan_id 4374
03-19 11:45:18.879  3621  3829 I bt-btm  :                : sec: 0x20b0, service name [Android Network Access Point] (up to 21 chars saved)
03-19 11:45:18.879  3621  3829 I bt-btm  : BTM_SEC_REG[11]: id 27, is_orig 0, psm 0x000f, proto_id 5, chan_id 4374
03-19 11:45:18.879  3621  3829 I bt-btm  :                : sec: 0x30b6, service name [Android Network Access Point] (up to 21 chars saved)
03-19 11:45:18.879  3621  3829 I bt-btm  : Write Extended Inquiry Response to controller
03-19 11:45:18.879  3621  3829 I bt-btm  : BTM_SEC_REG[12]: id 25, is_orig 1, psm 0x000f, proto_id 5, chan_id 4373
03-19 11:45:18.879  3621  3829 I bt-btm  :                : sec: 0x20b0, service name [Android Network User] (up to 21 chars saved)
03-19 11:45:18.879  3621  3829 I bt-btm  : BTM_SEC_REG[12]: id 25, is_orig 0, psm 0x000f, proto_id 5, chan_id 4373
03-19 11:45:18.879  3621  3829 I bt-btm  :                : sec: 0x30b6, service name [Android Network User] (up to 21 chars saved)
03-19 11:45:18.879  3621  3829 I bt-btm  : Write Extended Inquiry Response to controller
03-19 11:45:18.879  3621  3829 I bt-btm  : Write Extended Inquiry Response to controller
03-19 11:45:18.879  3621  3829 I bt-btm  : Write Extended Inquiry Response to controller
03-19 11:45:18.879  3621  3727 D bt-sdp  : SDP_CreateRecord ok, num_records:9
03-19 11:45:18.889  3621  3727 I bt-btm  : Write Extended Inquiry Response to controller
03-19 11:45:18.889  3621  3727 I bt-btif : HAL bt_hal_cbacks->adapter_state_changed_cb
03-19 11:45:18.889  3621  3727 D bt-btif : btif_hf_upstreams_evt: event=BTA_AG_ENABLE_EVT
03-19 11:45:18.889  3621  3727 D bt-btif : btif_hf_upstreams_evt: event=BTA_AG_REGISTER_EVT
03-19 11:45:18.889  3621  3727 D bt-btif : btif_hf_upstreams_evt: event=BTA_AG_REGISTER_EVT
03-19 11:45:18.889  3621  3727 D bt-btif : btif_av_state_idle_handler event:BTA_AV_ENABLE_EVT flags 0
03-19 11:45:18.889  3621  3727 D bt-btif : btif_av_state_idle_handler event:BTA_AV_REGISTER_EVT flags 0
03-19 11:45:18.889  3621  3718 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
03-19 11:45:18.889  3621  3718 D BluetoothAdapterProperties: ScanMode =  21
03-19 11:45:18.889  3621  3718 D BluetoothAdapterProperties: State =  11
03-19 11:45:18.889  3621  3718 D BluetoothAdapterProperties: Setting state to 12
03-19 11:45:18.889  3621  3718 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
03-19 11:45:18.889  3621  3727 I bt-btif : HAL bt_hal_cbacks->adapter_properties_cb
03-19 11:45:18.889  3621  3879 E bt_mct  : hci lib postload completed
03-19 11:45:18.889  3621  3727 D BluetoothAdapterProperties: Discoverable Timeout:120
03-19 11:45:18.889   952  1694 D BluetoothManagerService: +onBluetoothStateChange prev=11 new=12
03-19 11:45:18.889   952  1044 D BluetoothManagerService: Message: MESSAGE_BLUETOOTH_STATE_CHANGE
03-19 11:45:18.889  3621  3718 I BluetoothAdapterState: Entering On State
03-19 11:45:18.889   952  1044 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
03-19 11:45:18.889   952  1044 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true), to 6 receivers.
03-19 11:45:18.889  1407  1924 D BluetoothHeadset: onBluetoothStateChange: up=true
03-19 11:45:18.899  1407  1447 D BluetoothHeadset: onBluetoothStateChange: up=true
03-19 11:45:18.899   952  1029 I InputMethodManagerService: [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
03-19 11:45:18.899  1407  1445 D BluetoothHeadset: onBluetoothStateChange: up=true
03-19 11:45:18.899   952  1044 D BluetoothA2dp: onBluetoothStateChange: up=true
03-19 11:45:18.899   952  1248 I ActivityManager: Killing 3006:com.htc.sense.mms/u0a64 (adj 15): empty #17
03-19 11:45:18.899   952  1248 D Process : killProcessQuiet, pid=3006
,03-19 11:45:18.899  1219  1246 D BluetoothHeadset: onBluetoothStateChange: up=true
03-19 11:45:18.899   952  1044 D BluetoothHeadset: onBluetoothStateChange: up=true
03-19 11:45:18.899   952  1248 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
03-19 11:45:18.899  3857  3857 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,03-19 11:45:18.929   952  1029 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,03-19 11:45:18.989   952  1772 I ActivityManager: Recipient 3006,
,03-19 11:45:19.009   952  1044 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
,03-19 11:45:19.009   952   952 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService,
03-19 11:45:19.009   952  1044 D BluetoothManagerService: Message: MESSAGE_BLUETOOTH_SERVICE_CONNECTED,
03-19 11:45:19.009   952  1044 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
03-19 11:45:19.009  1219  1674 I IntentController: receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
03-19 11:45:19.019  3621  3621 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
03-19 11:45:19.019  3621  3621 V BluetoothPbapReceiver: ***********state = 12
03-19 11:45:19.019  3857  3857 D CalendarApplication: onCreate
,03-19 11:45:19.029  3857  3885 D AlertReceiver: beginStartingService
,03-19 11:45:19.029   952  1479 D PMS     : acquireWL(23693acf): PARTIAL_WAKE_LOCK  StartingAlertService_5 0x1 3857 10010 null
,03-19 11:45:19.039   952  2376 D PMS     : acquireWL(2ed34c5c): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 2839 1000 null
03-19 11:45:19.039  3621  3621 V BluetoothPbapService: Pbap Service onCreate
03-19 11:45:19.039  3621  3621 V BluetoothPbapService: Starting PBAP service
03-19 11:45:19.039  3621  3621 D BluetoothAdapter: 1029354603: getState(). Returning 12
,03-19 11:45:19.039  3621  3621 V BluetoothPbapService: Handler(): got msg=1
03-19 11:45:19.039  3621  3621 V BluetoothPbapService: Pbap Service startRfcommSocketListener
,03-19 11:45:19.039  3621  3886 V BluetoothPbapService: Pbap Service initSocket
03-19 11:45:19.039   952  1694 I ActivityManager: Start proc com.htc.bgp for broadcast com.android.providers.calendar/.CalendarReceiver: pid=3887 uid=10011 gids={50011, 9997, 1028, 1015, 5001, 5011, 2001, 3003} abi=arm64-v8a
03-19 11:45:19.039  2839  2839 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:141 com.android.settings.bluetooth.DockEventReceiver.onReceive:121 
03-19 11:45:19.039   952  1248 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,03-19 11:45:19.049  3621  3886 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-19 11:45:19.049  3621  3829 I bt-btm  : BTM_SetDiscoverability
03-19 11:45:19.049  3621  3829 I bt-btm  : HAL bt_hal_cbacks->adapter_properties_cb
03-19 11:45:19.049  3621  3829 D bt-btm  : disc_mode 0000
03-19 11:45:19.049  3621  3727 I bt-btif : disc_mode 0000
03-19 11:45:19.049  3621  3829 I bt-btm  : evt_type=0x0 p-cb->evt_type=0x0 
03-19 11:45:19.049  3621  3829 I bt-btm  : BTM_SetDiscoverability: mode 0 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
03-19 11:45:19.049  3621  3829 I bt-btm  : BTA_JvCreateRecordByU
03-19 11:45:19.049  3621  3886 I bt-btif : BTA_JvCreateRecordByUser
03-19 11:45:19.049  3621  3829 I bt-btm  : btm_ble_set_connectability mode=0x0 combined_mode=0x1
03-19 11:45:19.049  3621  3829 D bt-btm  : disc_mode 0000
03-19 11:45:19.049  3621  3829 D bt-btm  : btm_ble_update_adv_flag new=0x18
03-19 11:45:19.049  3621  3829 D bt-btm  : btm_ble_update_adv_flag old=0x1c
03-19 11:45:19.049  3621  3829 I bt-btm  : BTM_SetConnectability: mode 1 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
03-19 11:45:19.049  3621  3829 D bt-sdp  : SDP_CreateRecord ok, num_records:10
03-19 11:45:19.049  3621  3829 I bt-btm  : Write Extended Inquiry Response to controller
03-19 11:45:19.049  3621  3829 I bt-btif : BTA_JvRfcommStartServer
03-19 11:45:19.049  3621  3829 I bt-btm  : BTM_SEC_REG[13]: id 55, is_orig 0, psm 0x0003, proto_id 3, chan_id 19
03-19 11:45:19.049  3621  3829 I bt-btm  :                : sec: 0x86, service name [JV PORT] (up to 21 chars saved)
03-19 11:45:19.049  3621  3886 V BluetoothPbapService: Succeed to create listening socket 
03-19 11:45:19.049  3621  3886 V BluetoothPbapService: Accepting socket connection...
03-19 11:45:19.049  3791  3791 D HtcBtWidget_BTWidgetProvider: onBTStateChanged() for widget: 
03-19 11:45:19.049  3621  3727 D BluetoothAdapterProperties: Scan Mode:21
03-19 11:45:19.049   952  1772 D PMS     : releaseWL(2ed34c5c): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 null
03-19 11:45:19.049  3791  3791 D HtcBtWidget_BTWidgetProvider: updateWidget(context) for widget: 
03-19 11:45:19.049   952  2376 D PMS     : acquireWL(3768b4eb): PARTIAL_WAKE_LOCK  StartingDockService 0x1 2839 1000 null
03-19 11:45:19.059   952  1044 D BluetoothManagerService: Message: MESSAGE_REGISTER_ADAPTER
03-19 11:45:19.059   952  1772 W System.err: java.lang.Throwable: stack dump
03-19 11:45:19.059   952  1044 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@fa7a606:true
03-19 11:45:19.059   952  1772 W System.err: 	at java.lang.Thread.dumpStack(Thread.java:490)
03-19 11:45:19.059   952  1772 W System.err: 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
03-19 11:45:19.059   952  1772 W System.err: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
03-19 11:45:19.059   952  1772 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
03-19 11:45:19.059  2200  3903 W DriveInitializer: Background init thread started
03-19 11:45:19.069  1219  1219 D BluetoothAdapter: 56041548: getState(). Returning 12
03-19 11:45:19.069  2200  3903 E SQLiteLog: (3850) statement aborts at 4: [DELETE FROM ContentFileDeletionLock112] disk I/O error
03-19 11:45:19.069  2200  3903 E SQLiteDBG: func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.google.android.gms/databases/DocList.db, handle: 0x5591146d60
03-19 11:45:19.069  1219  1219 D BluetoothAdapter: 56041548: getState(). Returning 12
03-19 11:45:19.069  1219  1219 I QuickSettingBluetooth: receive.ACTION_STATE_CHANGE:STATE_ON/(true,false)
03-19 11:45:19.079  1219  1219 D PhoneStatusBar: addIcon slot=bluetooth index=12 viewIndex=1 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f0204ad level=0 visible=true num=0 ) name=stat_sys_data_bluetooth vis=true
03-19 11:45:19.079  2839  2839 D BluetoothAdapter: 1044783489: getState(). Returning 12
03-19 11:45:19.079  2200  3903 E DocListDatabase: Failed to delete from ContentFileDeletionLock112
03-19 11:45:19.079  2200  3903 E DocListDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
03-19 11:45:19.079  2200  3903 E DocListDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
03-19 11:45:19.079  2200  3903 E DocListDatabase: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:762)
03-19 11:45:19.079  2200  3903 E DocListDatabase: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
03-19 11:45:19.079  2200  3903 E DocListDatabase: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
03-19 11:45:19.079  2200  3903 E DocListDatabase: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1577)
03-19 11:45:19.079  2200  3903 E DocListDatabase: 	at com.google.android.gms.drive.database.k.a(SourceFile:520)
03-19 11:45:19.079  2200  3903 E DocListDatabase: 	at com.google.android.gms.drive.database.f.h(SourceFile:1056)
03-19 11:45:19.079  2200  3903 E DocListDatabase: 	at com.google.android.gms.drive.r.run(SourceFile:69)
03-19 11:45:19.079  2839  2839 D BluetoothInputDevice: BluetoothInputDevice()
03-19 11:45:19.089   952  1764 D BluetoothManagerService: registerStateChangeCallback+
03-19 11:45:19.089   952  1044 D BluetoothManagerService: Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
03-19 11:45:19.089   952  1044 D BluetoothManagerService: Registered receivers: 7
,03-19 11:45:19.089   952  1029 D PMS     : acquireWL(97475bf): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 952 1000 null
,03-19 11:45:19.089  2200  3903 W DriveInitializer: Background init thread ended
,03-19 11:45:19.099  2839  2839 D BluetoothPan: BluetoothPan()
,03-19 11:45:19.099   952   983 D BluetoothManagerService: registerStateChangeCallback+
03-19 11:45:19.099   952  1044 D BluetoothManagerService: Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
03-19 11:45:19.099   952  1044 D BluetoothManagerService: Registered receivers: 8
03-19 11:45:19.099   952  1029 D PMS     : releaseWL(97475bf): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,03-19 11:45:19.099  2200  3903 E AndroidRuntime: FATAL EXCEPTION: Background initialization thread
03-19 11:45:19.099  2200  3903 E AndroidRuntime: Process: com.google.android.gms, PID: 2200
03-19 11:45:19.099  2200  3903 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
03-19 11:45:19.099  2200  3903 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
03-19 11:45:19.099  2200  3903 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:762)
03-19 11:45:19.099  2200  3903 E AndroidRuntime: 	,at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
03-19 11:45:19.099  2200  3903 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
03-19 11:45:19.099  2200  3903 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1577)
03-19 11:45:19.099  2200  3903 E AndroidRuntime: 	at com.google.android.gms.drive.database.k.a(SourceFile:520)
03-19 11:45:19.099  2200  3903 E AndroidRuntime: 	at com.google.android.gms.drive.database.f.h(SourceFile:1056)
03-19 11:45:19.099  2200  3903 E AndroidRuntime: 	at com.google.android.gms.drive.r.run(SourceFile:69)
,03-19 11:45:19.099   952  1714 E ActivityManager: App crashed! Process: com.google.android.gms
,03-19 11:45:19.099  2200  3914 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.gms/shared_prefs/gms_sync_prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/gms_sync_prefs.xml.bak
03-19 11:45:19.099  2839  2839 D BluetoothMap: Create BluetoothMap proxy object
,03-19 11:45:19.099   952  2301 D BluetoothManagerService: registerStateChangeCallback+
03-19 11:45:19.099  3887  3887 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
03-19 11:45:19.099   952  1044 D BluetoothManagerService: Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
03-19 11:45:19.099   952  1044 D BluetoothManagerService: Registered receivers: 9
03-19 11:45:19.099  2839  2839 E BluetoothMap: Could not bind to Bluetooth MAP Service with Intent { act=android.bluetooth.IBluetoothMap }
03-19 11:45:19.109   952  1764 D BluetoothManagerService: registerStateChangeCallback+
03-19 11:45:19.109   952  1044 D BluetoothManagerService: Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
03-19 11:45:19.109   952  1044 D BluetoothManagerService: Registered receivers: 10
03-19 11:45:19.109  2839  2839 D BluetoothSap: BluetoothSap() call bindService
,03-19 11:45:19.109  2839  2839 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1888 android.content.ContextWrapper.bindService:538 android.bluetooth.BluetoothSap.doBind:108 android.bluetooth.BluetoothSap.<init>:101 android.bluetooth.BluetoothAdapter.getProfileProxy:1423 
03-19 11:45:19.109   952  1031 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-19 11:45:19.109   952  1031 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-19 11:45:19.119   952  3915 E DropBoxManagerService: Can't write: system_app_crash
03-19 11:45:19.119   952  3915 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop119.tmp: open failed: EROFS (Read-only file system)
03-19 11:45:19.119   952  3915 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
,03-19 11:45:19.119   952  3915 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
03-19 11:45:19.119   952  3915 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
03-19 11:45:19.119   952  3915 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
03-19 11:45:19.119   952  3915 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
03-19 11:45:19.119   952  3915 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$21.run(ActivityManagerService.java:12658)
03-19 11:45:19.119   952  3915 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
03-19 11:45:19.119   952  3915 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
03-19 11:45:19.119   952  3915 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
03-19 11:45:19.119   952  3915 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
03-19 11:45:19.119   952  3915 E DropBoxManagerService: 	... 5 more
,03-19 11:45:19.119  3621  3916 E SQLiteDatabase: Failed to open database '/data/data/com.android.bluetooth/databases/btopp.db'.
03-19 11:45:19.119  3621  3916 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-19 11:45:19.119  3621  3916 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-19 11:45:19.119  3621  3916 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
03-19 11:45:19.119  3621  3916 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
03-19 11:45:19.119  3621  3916 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-19 11:45:19.119  3621  3916 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-19 11:45:19.119  3621  3916 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-19 11:45:19.119  3621  3916 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
03-19 11:45:19.119  3621  3916 E SQLiteDatabase: 	,at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
03-19 11:45:19.119  3621  3916 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
03-19 11:45:19.119  3621  3916 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
03-19 11:45:19.119  3621  3916 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
03-19 11:45:19.119  3621  3916 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-19 11:45:19.119  3621  3916 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-19 11:45:19.119  3621  3916 E SQLiteDatabase: 	at com.android.bluetooth.opp.BluetoothOppProvider.delete(BluetoothOppProvider.java:443)
03-19 11:45:19.119  3621  3916 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:319)
03-19 11:45:19.119  3621  3916 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1320)
03-19 11:45:19.119  3621  3916 E SQLiteDatabase: 	at com.android.bluetooth.opp.BluetoothOppService.trimDatabase(BluetoothOppService.java:1029)
03-19 11:45:19.119  3621  3916 E SQLiteDatabase: 	at com.android.bluetooth.opp.BluetoothOppService.access$200(BluetoothOppService.java:72)
03-19 11:45:19.119  3621  3916 E SQLiteDatabase: 	at com.android.bluetooth.opp.BluetoothOppService$1.run(BluetoothOppService.java:168)
03-19 11:45:19.119  3621  3916 E BtOppService: trimDatabase: could not deleted complete outbound shares: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-19 11:45:19.119  3621  3916 E SQLiteDatabase: Failed to open database '/data/data/com.android.bluetooth/databases/btopp.db'.
03-19 11:45:19.119  3621  3916 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-19 11:45:19.119  3621  3916 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-19 11:45:19.119  3621  3916 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
03-19 11:45:19.119  3621  3916 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
03-19 11:45:19.119  3621  3916 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-19 11:45:19.119  3621  3916 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-19 11:45:19.119  3621  3916 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-19 11:45:19.119  3621  3916 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
03-19 11:45:19.119  3621  3916 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
03-19 11:45:19.119  3621  3916 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
03-19 11:45:19.119  3621  3916 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
03-19 11:45:19.119  3621  3916 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
03-19 11:45:19.119  3621  3916 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-19 11:45:19.119  3621  3916 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-19 11:45:19.119  3621  3916 E SQLiteDatabase: 	at com.android.bluetooth.opp.BluetoothOppProvider.delete(BluetoothOppProvider.java:443)
03-19 11:45:19.119  3621  3916 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:319)
03-19 11:45:19.119  3621  3916 E SQLiteDatabase: 	at androi,d.content.ContentResolver.delete(ContentResolver.java:1320)
03-19 11:45:19.119  3621  3916 E SQLiteDatabase: 	at com.android.bluetooth.opp.BluetoothOppService.trimDatabase(BluetoothOppService.java:1041)
03-19 11:45:19.119  3621  3916 E SQLiteDatabase: 	at com.android.bluetooth.opp.BluetoothOppService.access$200(BluetoothOppService.java:72)
03-19 11:45:19.119  3621  3916 E SQLiteDatabase: 	at com.android.bluetooth.opp.BluetoothOppService$1.run(BluetoothOppService.java:168)
03-19 11:45:19.119  3621  3916 E BtOppService: trimDatabase: could not deleted complete inbound failed shares: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-19 11:45:19.129  3621  3916 E SQLiteDatabase: Failed to open database '/data/data/com.android.bluetooth/databases/btopp.db'.
03-19 11:45:19.129  3621  3916 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-19 11:45:19.129  3621  3916 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-19 11:45:19.129  3621  3916 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
03-19 11:45:19.129  3621  3916 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
03-19 11:45:19.129  3621  3916 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-19 11:45:19.129  3621  3916 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-19 11:45:19.129  3621  3916 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-19 11:45:19.129  3621  3916 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
03-19 11:45:19.129  3621  3916 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
03-19 11:45:19.129  3621  3916 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
03-19 11:45:19.129  3621  3916 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
03-19 11:45:19.129  3621  3916 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
03-19 11:45:19.129  3621  3916 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-19 11:45:19.129  3621  3916 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-19 11:45:19.129  3621  3916 E SQLiteDatabase: 	at com.android.bluetooth.opp.BluetoothOppProvider.delete(BluetoothOppProvider.java:443)
03-19 11:45:19.129  3621  3916 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:319)
03-19 11:45:19.129  3621  3916 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1320)
03-19 11:45:19.129  3621  3916 E SQLiteDatabase: 	at com.android.bluetooth.opp.BluetoothOppService.trimDatabase(BluetoothOppService.java:1055)
03-19 11:45:19.129  3621  3916 E SQLiteDatabase: 	at com.android.bluetooth.opp.BluetoothOppService.access$200(BluetoothOppService.java:72)
03-19 11:45:19.129  3621  3916 E SQLiteDatabase: 	at com.android.bluetooth.opp.BluetoothOppService$1.run(BluetoothOppService.java:168)
03-19 11:45:19.129  3621  3916 E BtOppService: trimDatabase: could not deleted interrupted outbound failed shares: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-19 11:45:19.129  3621  3916 E SQLiteDatabase: Failed to open database '/data/data/com.android.bluetooth/databases/btopp.db'.
03-19 11:45:19.129  3621  3916 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-19 11:45:19.129  3621  3916 E SQLiteDatabase: 	at android,.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-19 11:45:19.129  3621  3916 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
03-19 11:45:19.129  3621  3916 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
03-19 11:45:19.129  3621  3916 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-19 11:45:19.129  3621  3916 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-19 11:45:19.129  3621  3916 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-19 11:45:19.129  3621  3916 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
03-19 11:45:19.129  3621  3916 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
03-19 11:45:19.129  3621  3916 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
03-19 11:45:19.129  3621  3916 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
03-19 11:45:19.129  3621  3916 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
03-19 11:45:19.129  3621  3916 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-19 11:45:19.129  3621  3916 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
03-19 11:45:19.129  3621  3916 E SQLiteDatabase: 	at com.android.bluetooth.opp.BluetoothOppProvider.query(BluetoothOppProvider.java:313)
03-19 11:45:19.129  3621  3916 E SQLiteDatabase: 	at android.content.ContentProvider.query(ContentProvider.java:960)
03-19 11:45:19.129  3621  3916 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.query(ContentProvider.java:220)
03-19 11:45:19.129  3621  3916 E SQLiteDatabase: 	at android.content.ContentResolver.query(ContentResolver.java:491)
03-19 11:45:19.129  3621  3916 E SQLiteDatabase: 	at android.content.ContentResolver.query(ContentResolver.java:435)
03-19 11:45:19.129  3621  3916 E SQLiteDatabase: 	at com.android.bluetooth.opp.BluetoothOppService.trimDatabase(BluetoothOppService.java:1070)
03-19 11:45:19.129  3621  3916 E SQLiteDatabase: 	at com.android.bluetooth.opp.BluetoothOppService.access$200(BluetoothOppService.java:72)
03-19 11:45:19.129  3621  3916 E SQLiteDatabase: 	at com.android.bluetooth.opp.BluetoothOppService$1.run(BluetoothOppService.java:168)
03-19 11:45:19.129  3621  3916 E SQLiteOpenHelper: Couldn't open btopp.db for writing (will try read-only):
03-19 11:45:19.129  3621  3916 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-19 11:45:19.129  3621  3916 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-19 11:45:19.129  3621  3916 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
03-19 11:45:19.129  3621  3916 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
03-19 11:45:19.129  3621  3916 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-19 11:45:19.129  3621  3916 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-19 11:45:19.129  3621  3916 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-19 11:45:19.129  3621  3916 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
03-19 11:45:19.129  3621  3916 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
03-19 11:45:19.129  3621  3916 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
03-19 11:45:19.129  3621  3916 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
03-19 11:45:19.129  3621  3916 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
03-19 11:45:19.129  3621  3916 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-19 11:45:19.129  3621  3916 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
03-19 11:45:19.129  3621  3916 E SQLiteOpenHelper: 	at com.android.bluetooth.opp.BluetoothOppProvider.query(BluetoothOppProvider.java:313)
03-19 11:45:19.129  3621  3916 E SQLiteOpenHelper: 	at android.content.ContentProvider.query(ContentProvider.java:960)
03-19 11:45:19.129  3621  3916 E SQLiteOpenHelper: 	at android.content.ContentProvider$Transport.query(ContentProvider.java:220)
03-19 11:45:19.129  3621  3916 E SQLiteOpenHelper: 	at android.content.ContentResolver.query(ContentResolver.java:491)
03-19 11:45:19.129  3621  3916 E SQLiteOpenHelper: 	at android.content.ContentResolver.query(ContentResolver.java:435)
03-19 11:45:19.129  3621  3916 E SQLiteOpenHelper: 	at com.android.bluetooth.opp.BluetoothOppService.trimDatabase(BluetoothOppService.java:1070)
03-19 11:45:19.129  3621  3916 E SQLiteOpenHelper: 	at com.android.bluetooth.opp.BluetoothOppService.access$200(BluetoothOppService.java:72)
03-19 11:45:19.129  3621  3916 E SQLiteOpenHelper: 	at com.android.bluetooth.opp.BluetoothOppService$1.run(BluetoothOppService.java:168)
03-19 11:45:19.139  3621  3916 W SQLiteOpenHelper: Opened btopp.db in read-only mode
03-19 11:45:19.139  3621  3916 E AndroidRuntime: FATAL EXCEPTION: trimDatabase
03-19 11:45:19.139  3621  3916 E AndroidRuntime: Process: com.android.bluetooth, PID: 3621
03-19 11:45:19.139  3621  3916 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-19 11:45:19.139  3621  3916 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-19 11:45:19.139  3621  3916 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
03-19 11:45:19.139  3621  3916 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
03-19 11:45:19.139  3621  3916 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-19 11:45:19.139  3621  3916 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.reconfigure(SQLiteConnectionPool.java:306)
03-19 11:45:19.139  3621  3916 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.reopenReadWrite(SQLiteDatabase.java:823)
03-19 11:45:19.139  3621  3916 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:212)
03-19 11:45:19.139  3621  3916 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-19 11:45:19.139  3621  3916 E AndroidRuntime: 	at com.android.bluetooth.opp.BluetoothOppProvider.delete(BluetoothOppProvider.java:443)
03-19 11:45:19.139  3621  3916 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:319)
03-19 11:45:19.139  3621  3916 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1320)
03-19 11:45:19.139  3621  3916 E AndroidRuntime: 	at com.android.bluetooth.opp.BluetoothOppService.trimDatabase(BluetoothOppService.java:1109)
03-19 11:45:19.139  3621  3916 E AndroidRuntime: 	at com.android.bluetooth.opp.BluetoothOppService.access$200(BluetoothOppService.java:72)
03-19 11:45:19.139  3621  3916 E AndroidRuntime: 	at com.android.bluetooth.opp.BluetoothOppService$1.run(BluetoothOppService.java:168)
03-19 11:45:19.149   952  1043 D StatusBarManagerService: setSystemUiVisibility(0xc0000000)
03-19 11:45:19.149   952  1043 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
03-19 11:45:19.149   952  1043 D StatusBarManagerService: hiding MENU key
03-19 11:45:19.149   952  1479 E ActivityManager: App crashed! Process: com.android.bluetooth
03-19 11:45:19.149   952  1479 D ErrorReport: HtcErrorReportManager Begin---add error logs to dropbox
03-19 11:45:19.149  2839  2839 D BluetoothPbap: BluetoothPbap()
03-19 11:45:19.149   952  1764 D BluetoothManagerService: registerStateChangeCallback+
03-19 11:45:19.149   952  1044 D BluetoothManagerService: Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
03-19 11:45:19.149   952  1044 D BluetoothManagerService: Registered receivers: 11
03-19 11:45:19.149   952  1499 W System.err: java.io.FileNotFoundException: /data/system/systemup_pref.xml: open failed: EROFS (Read-only file system)
03-19 11:45:19.149   952  1499 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
03-19 11:45:19.149   952  1499 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
03-19 11:45:19.149   952  1499 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
03-19 11:45:19.149   952  1499 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
03-19 11:45:19.149   952  1499 W System.err: 	at com.htc.upm.HtcSystemUPPreference.writeProperty(HtcSystemUPPreference.java:119)
03-19 11:45:19.149   952  1499 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setProperty(HtcSystemUPPreference.java:86)
03-19 11:45:19.149   952  1499 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setLong(HtcSystemUPPreference.java:60)
03-19 11:45:19.149   952  1499 W System.err: 	at com.htc.upm.HtcSystemUPHandler.addErrorCount(HtcSystemUPHandler.java:294)
03-19 11:45:19.149   952  1499 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessageInternal(HtcSystemUPHandler.java:73)
03-19 11:45:19.149   952  1499 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessage(HtcSystemUPHandler.java:46)
03-19 11:45:19.149   952  1499 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-19 11:45:19.149   952  1499 W System.err: 	at android.os.Looper.loop(Looper.java:155)
03-19 11:45:19.149   952  1499 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-19 11:45:19.149   952  1499 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
03-19 11:45:19.149   952  1499 W System.err: 	at libcore.io.Posix.open(Native Method)
03-19 11:45:19.149   952  1499 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
03-19 11:45:19.149   952  1499 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
03-19 11:45:19.149   952  1499 W System.err: 	... 12 more
03-19 11:45:19.159   952  1248 D BluetoothManagerService: registerStateChangeCallback+
03-19 11:45:19.159   952  1044 D BluetoothManagerService: Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
03-19 11:45:19.159   952  1044 D BluetoothManagerService: Registered receivers: 12
03-19 11:45:19.159   952  1479 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
,03-19 11:45:19.159   952  1479 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
03-19 11:45:19.159   952  1479 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
03-19 11:45:19.159   952  1479 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
03-19 11:45:19.159   952  1479 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
03-19 11:45:19.159   952  1479 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:154)
03-19 11:45:19.159   952  1479 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:121)
03-19 11:45:19.159   952  1479 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getSecretKey(ErrorReportPreference.java:69)
03-19 11:45:19.159   952  1479 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:304)
03-19 11:45:19.159   952  1479 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:257)
03-19 11:45:19.159   952  1479 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12578)
03-19 11:45:19.159   952  1479 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12242)
03-19 11:45:19.159   952  1479 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12214)
03-19 11:45:19.159   952  1479 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1391)
03-19 11:45:19.159   952  1479 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2567)
03-19 11:45:19.159   952  1479 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
03-19 11:45:19.159   952  1479 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
03-19 11:45:19.159   952  1479 W System.err: 	at libcore.io.Posix.open(Native Method)
03-19 11:45:19.159   952  1479 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
03-19 11:45:19.159   952  1479 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
03-19 11:45:19.159   952  1479 W System.err: 	... 14 more
03-19 11:45:19.169   952   986 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
03-19 11:45:19.169  3621  3921 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-19 11:45:19.169  2839  2839 D BluetoothHeadset: BluetoothHeadset()
03-19 11:45:19.169   952  1715 D BluetoothManagerService: registerStateChangeCallback+
03-19 11:45:19.169  3621  3921 I bt-btif : BTA_JvCreateRecordByUser
03-19 11:45:19.169  3621  3829 D bt-sdp  : SDP_CreateRecord ok, num_records:11
03-19 11:45:19.169  3621  3829 I bt-btm  : Write Extended Inquiry Response to controller
03-19 11:45:19.169  3621  3829 I bt-btif : BTA_JvRfcommStartServer
03-19 11:45:19.169  3621  3829 I bt-btm  : BTM_SEC_REG[14]: id 56, is_orig 0, psm 0x0003, proto_id 3, chan_id 12
03-19 11:45:19.169  3621  3829 I bt-btm  :                : sec: 0x80, service name [JV PORT] (up to 21 chars saved)
03-19 11:45:19.169  3621  3921 I BtOppRfcommListener: Accept thread started.
03-19 11:45:19.169   952  1044 D BluetoothManagerService: Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
03-19 11:45:19.169   952  1044 D BluetoothManagerService: Registered receivers: 13
03-19 11:45:19.169   952  1479 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
03-19 11:45:19.169   952  1479 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
03-19 11:45:19.169   952  1479 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
03-19 11:45:19.169   952  1479 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
03-19 11:45:19.169   952  1479 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
03-19 11:45:19.169   952  1479 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:154)
03-19 11:45:19.169   952  1479 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:121)
03-19 11:45:19.169   952  1479 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getIV(ErrorReportPreference.java:93)
03-19 11:45:19.169   952  1479 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:305)
03-19 11:45:19.169   952  1479 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:257)
03-19 11:45:19.169   952  1479 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12578)
03-19 11:45:19.169   952  1479 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12242)
03-19 11:45:19.169   952  1479 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12214)
03-19 11:45:19.169   952  1479 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1391)
03-19 11:45:19.169   952  1479 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2567)
03-19 11:45:19.169   952  1479 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
03-19 11:45:19.169   952  1479 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
03-19 11:45:19.169   952  1479 W System.err: 	at libcore.io.Posix.open(Native Method)
03-19 11:45:19.169   952  1479 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
03-19 11:45:19.169   952  1479 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
03-19 11:45:19.169   952  1479 W System.err: 	... 14 more
03-19 11:45:19.169  3621  3621 D BluetoothAdapter: 1029354603: getState(). Returning 12
03-19 11:45:19.169  3621  3621 D BluetoothFtpService: ACTION_STATE_CHANGED: state: 12mHasStarted: true
03-19 11:45:19.169  3621  3621 D BluetoothMasReceiver: Bluetooth STATE CHANGED to 12
03-19 11:45:19.169  3621  3621 D BluetoothMasReceiver:  call MAP start service
03-19 11:45:19.179   952  1479 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
03-19 11:45:19.179  3887  3887 E SQLiteDatabase: Failed to open database '/data/data/com.android.providers.calendar/databases/calendar.db'.
03-19 11:45:19.179  3887  3887 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-19 11:45:19.179  3887  3887 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-19 11:45:19.179  3887  3887 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
03-19 11:45:19.179  3887  3887 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
03-19 11:45:19.179  3887  3887 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-19 11:45:19.179  3887  3887 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-19 11:45:19.179  3887  3887 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-19 11:45:19.179  3887  3887 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
03-19 11:45:19.179  3887  3887 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
03-19 11:45:19.179  3887  3887 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
03-19 11:45:19.179  3887  3887 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
03-19 11:45:19.179  3887  3887 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
03-19 11:45:19.179  3887  3887 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-19 11:45:19.179  3887  3887 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-19 11:45:19.179  3887  3887 E SQLiteDatabase: 	at com.android.providers.calendar.CalendarDatabaseHelper.getWritableDatabase(CalendarDatabaseHelper.java:2521)
03-19 11:45:19.179  3887  3887 E SQLiteDatabase: 	at com.android.providers.calendar.CalendarProvider2.initialize(CalendarProvider2.java:592)
03-19 11:45:19.179  3887  3887 E SQLiteDatabase: 	at com.android.providers.calendar.CalendarProvider2.onCreate(CalendarProvider2.java:567)
03-19 11:45:19.179  3887  3887 E SQLiteDatabase: 	at com.htc.providers.calendar.HtcCalendarProvider.onCreate(HtcCalendarProvider.java:77)
03-19 11:45:19.179  3887  3887 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1702)
03-19 11:45:19.179  3887  3887 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1665)
03-19 11:45:19.179  3887  3887 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5421)
03-19 11:45:19.179  3887  3887 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4992)
03-19 11:45:19.179  3887  3887 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4927)
03-19 11:45:19.179  3887  3887 E SQLiteDatabase: 	at android.app.ActivityThread.access$1500(ActivityThread.java:144)
03-19 11:45:19.179  3887  3887 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1424)
03-19 11:45:19.179  3887  3887 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-19 11:45:19.179  3887  3887 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:155)
03-19 11:45:19.179  3887  3887 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5721)
03-19 11:45:19.179  3887  3887 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
03-19 11:45:19.179  3887  3887 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-19 11:45:19.179  3887  3887 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
03-19 11:45:19.179  3887  3887 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
03-19 11:45:19.179  3887  3887 E CalendarProvider2: Cannot start provider
03-19 11:45:19.179  3887  3887 E CalendarProvider2: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-19 11:45:19.179  3887  3887 E CalendarProvider2: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-19 11:45:19.179  3887  3887 E CalendarProvider2: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
03-19 11:45:19.179  3887  3887 E CalendarProvider2: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
03-19 11:45:19.179  3887  3887 E CalendarProvider2: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-19 11:45:19.179  3887  3887 E CalendarProvider2: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-19 11:45:19.179  3887  3887 E CalendarProvider2: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-19 11:45:19.179  3887  3887 E CalendarProvider2: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
03-19 11:45:19.179  3887  3887 E CalendarProvider2: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
03-19 11:45:19.179  3887  3887 E CalendarProvider2: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
03-19 11:45:19.179  3887  3887 E CalendarProvider2: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
03-19 11:45:19.179  3887  3887 E CalendarProvider2: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
03-19 11:45:19.179  3887  3887 E CalendarProvider2: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-19 11:45:19.179  3887  3887 E CalendarProvider2: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-19 11:45:19.179  3887  3887 E CalendarProvider2: 	at com.android.providers.calendar.CalendarDatabaseHelper.getWritableDatabase(CalendarDatabaseHelper.java:2521)
03-19 11:45:19.179  3887  3887 E CalendarProvider2: 	at com.android.providers.calendar.CalendarProvider2.initialize(CalendarProvider2.java:592)
03-19 11:45:19.179  3887  3887 E CalendarProvider2: 	at com.android.providers.calendar.CalendarProvider2.onCreate(CalendarProvider2.java:567)
03-19 11:45:19.179  3887  3887 E CalendarProvider2: 	at com.htc.providers.calendar.HtcCalendarProvider.onCreate(HtcCalendarProvider.java:77)
03-19 11:45:19.179  3887  3887 E CalendarProvider2: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1702)
03-19 11:45:19.179  3887  3887 E CalendarProvider2: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1665)
03-19 11:45:19.179  3887  3887 E CalendarProvider2: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5421)
03-19 11:45:19.179  3887  3887 E CalendarProvider2: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4992)
03-19 11:45:19.179  3887  3887 E CalendarProvider2: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4927)
03-19 11:45:19.179  3887  3887 E CalendarProvider2: 	at android.app.ActivityThread.access$1500(ActivityThread.java:144)
03-19 11:45:19.179  3887  3887 E CalendarProvider2: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1424)
03-19 11:45:19.179  3887  3887 E CalendarProvider2: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-19 11:45:19.179  3887  3887 E CalendarProvider2: 	at android.os.Looper.loop(Looper.java:155)
03-19 11:45:19.179  3887  3887 E CalendarProvider2: 	at android.app.ActivityThread.main(ActivityThread.java:5721)
03-19 11:45:19.179  3887  3887 E CalendarProvider2: 	at java.lang.reflect.Method.invoke(Native Method)
03-19 11:45:19.179  3887  3887 E CalendarProvider2: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-19 11:45:19.179  3887  3887 E CalendarProvider2: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
03-19 11:45:19.179  3887  3887 E CalendarProvider2: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
03-19 11:45:19.189  2839  2839 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
03-19 11:45:19.189  3621  3621 V BluetoothPbapService: Pbap Service onBind
03-19 11:45:19.189   952  3922 E ErrorReport: HtcErrorReportManager.Error in dumping error information
03-19 11:45:19.189   952  3922 E ErrorReport: java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1458384319198.dbox_tmp: open failed: EROFS (Read-only file system)
03-19 11:45:19.189   952  3922 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:456)
03-19 11:45:19.189   952  3922 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
03-19 11:45:19.189   952  3922 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
03-19 11:45:19.189   952  3922 E ErrorReport: 	at com.android.server.am.HtcErrorReportManager$1.run(HtcErrorReportManager.java:455)
03-19 11:45:19.189   952  3922 E ErrorReport: 	at java.lang.Thread.run(Thread.java:818)
03-19 11:45:19.189   952  3922 E ErrorReport: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
03-19 11:45:19.189   952  3922 E ErrorReport: 	at libcore.io.Posix.open(Native Method)
03-19 11:45:19.189   952  3922 E ErrorReport: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
03-19 11:45:19.189   952  3922 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:442)
03-19 11:45:19.189   952  3922 E ErrorReport: 	... 4 more
03-19 11:45:19.189  3621  3621 D BluetoothFtpService: htc sense version is 6.0
03-19 11:45:19.199   952  1715 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
03-19 11:45:19.199  3621  3621 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-19 11:45:19.199  2839  2839 D DockEventReceiver: finishStartingService: stopping service
03-19 11:45:19.199  2839  2839 D BluetoothInputDevice: Proxy object connected
03-19 11:45:19.199  3621  3621 I bt-btif : BTA_JvCreateRecordByUser
,03-19 11:45:19.199  2839  2839 D HidProfile: Bluetooth service connected
03-19 11:45:19.199  3621  3829 D bt-sdp  : SDP_CreateRecord ok, num_records:12
03-19 11:45:19.199  3621  3829 I bt-btm  : Write Extended Inquiry Response to controller
03-19 11:45:19.199  3621  3829 I bt-btif : BTA_JvRfcommStartServer
03-19 11:45:19.199  3621  3829 I bt-btm  : BTM_SEC_REG[15]: id 57, is_orig 0, psm 0x0003, proto_id 3, chan_id 20
03-19 11:45:19.199  3621  3829 I bt-btm  :                : sec: 0x1086, service name [JV PORT] (up to 21 chars saved)
03-19 11:45:19.199  3621  3925 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
03-19 11:45:19.199  2200  3914 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.gms/shared_prefs/gms_sync_prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/gms_sync_prefs.xml.bak
03-19 11:45:19.209  3621  3621 E BluetoothMasService: BluetoothMasObexConnectionManager: mIsEmailEnabled: true
03-19 11:45:19.209  2839  2839 D BluetoothAdapter: 1044783489: getState(). Returning 12
03-19 11:45:19.209   952  1029 D PMS     : acquireWL(25a2eb69): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 952 1000 null
03-19 11:45:19.209  2839  2839 D BluetoothPan: BluetoothPAN Proxy object connected
03-19 11:45:19.209  2839  2839 D PanProfile: Bluetooth service connected
03-19 11:45:19.209  2839  2839 D BluetoothA2dp: Proxy object connected
03-19 11:45:19.209  2839  2839 D A2dpProfile: Bluetooth service connected
03-19 11:45:19.209   952  1029 D PMS     : releaseWL(855d054): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.drive.sync/com.google/***** 0x1 WorkSource{10024}
03-19 11:45:19.209  2839  2839 D BluetoothAdapter: 1044783489: getState(). Returning 12
03-19 11:45:19.219  2839  2839 D BluetoothHeadset: Proxy object connected
03-19 11:45:19.219   952  1029 W AtomicFile: Couldn't rename file /data/system/sync/stats.bin to backup file /data/system/sync/stats.bin.bak
03-19 11:45:19.219  2839  2839 D HeadsetProfile: Bluetooth service connected
03-19 11:45:19.219   952  1029 W SyncManager: Error writing stats
03-19 11:45:19.219   952  1029 W SyncManager: java.io.IOException: Couldn't create directory /data/system/sync/stats.bin
03-19 11:45:19.219   952  1029 W SyncManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
03-19 11:45:19.219   952  1029 W SyncManager: 	at com.android.server.content.SyncStorageEngine.writeStatisticsLocked(SyncStorageEngine.java:2793)
03-19 11:45:19.219   952  1029 W SyncManager: 	at com.android.server.content.SyncStorageEngine.stopSyncEvent(SyncStorageEngine.java:1426)
03-19 11:45:19.219   952  1029 W SyncManager: 	at com.android.server.content.SyncManager$SyncHandler.stopSyncEvent(SyncManager.java:3447)
03-19 11:45:19.219   952  1029 W SyncManager: 	at com.android.server.content.SyncManager$SyncHandler.runSyncFinishedOrCanceledLocked(SyncManager.java:3108)
03-19 11:45:19.219   952  1029 W SyncManager: 	at com.android.server.content.SyncManager$SyncHandler.handleMessage(SyncManager.java:2263)
03-19 11:45:19.219   952  1029 W SyncManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-19 11:45:19.219   952  1029 W SyncManager: 	at android.os.Looper.loop(Looper.java:155)
03-19 11:45:19.219   952  1029 W SyncManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-19 11:45:19.219  2839  2839 D BluetoothAdapter: 1044783489: getState(). Returning 12
03-19 11:45:19.219   952  1029 D PMS     : releaseWL(25a2eb69): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
03-19 11:45:19.219  3621  3621 D BluetoothMasService: Add permission for SmsProvider.
03-19 11:45:19.219   952  1772 D PMS     : releaseWL(3768b4eb): PARTIAL_WAKE_LOCK  StartingDockService 0x1 null
03-19 11:45:19.219  3621  3621 V BluetoothMasService: Starting MAS instances
03-19 11:45:19.219  2839  2839 D BluetoothPbap: Proxy object connected
03-19 11:45:19.219  3621  3621 D BluetoothAdapter: 1029354603: getState(). Returning 12
03-19 11:45:19.219  2839  2839 D PbapServerProfile: Bluetooth service connected
03-19 11:45:19.219  3621  3621 I MailMessageReceiver: reg:com.android.bluetooth.btservice.AdapterApp@8e1160c with com.htc.lib1.HtcMailLibFramework.MailMessageReceiver@35d63b55
03-19 11:45:19.229  3621  3621 I MailManager: MailManager contruct! com.htc.lib1.HtcMailLibFramework.MailMessageReceiver@35d63b55
03-19 11:45:19.229  3621  3621 V EmailUtils: Manager Instance is not NULL
03-19 11:45:19.229   952  1694 D PMS     : acquireWL(b75d525): PARTIAL_WAKE_LOCK  CalendarReceiverProvider_5 0x1 3887 10011 null
03-19 11:45:19.229   952  1031 W ActivityManager: Can't addPackageDependency on system process
03-19 11:45:19.239  3887  3912 E SQLiteDatabase: Failed to open database '/data/data/com.android.providers.calendar/databases/calendar.db'.
03-19 11:45:19.239  3887  3912 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-19 11:45:19.239  3887  3912 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-19 11:45:19.239  3887  3912 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
03-19 11:45:19.239  3887  3912 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
03-19 11:45:19.239  3887  3912 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-19 11:45:19.239  3887  3912 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-19 11:45:19.239  3887  3912 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-19 11:45:19.239  3887  3912 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
03-19 11:45:19.239  3887  3912 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
03-19 11:45:19.239  3887  3912 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
03-19 11:45:19.239  3887  3912 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
03-19 11:45:19.239  3887  3912 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
03-19 11:45:19.239  3887  3912 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-19 11:45:19.239  3887  3912 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
03-19 11:45:19.239  3887  3912 E SQLiteDatabase: 	at com.android.providers.calendar.CalendarProvider2.getReadableDatabase(CalendarProvider2.java:5451)
03-19 11:45:19.239  3887  3912 E SQLiteDatabase: 	at com.htc.providers.calendar.HtcCalendarProvider.query(HtcCalendarProvider.java:103)
03-19 11:45:19.239  3887  3912 E SQLiteDatabase: 	at android.content.ContentProvider.query(ContentProvider.java:960)
03-19 11:45:19.239  3887  3912 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.query(ContentProvider.java:220)
03-19 11:45:19.239  3887  3912 E SQLiteDatabase: 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:142)
03-19 11:45:19.239  3887  3912 E SQLiteDatabase: 	at android.os.Binder.execTransact(Binder.java:454)
03-19 11:45:19.239  3887  3912 E SQLiteOpenHelper: Couldn't open calendar.db for writing (will try read-only):
03-19 11:45:19.239  3887  3912 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-19 11:45:19.239  3887  3912 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-19 11:45:19.239  3887  3912 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
03-19 11:45:19.239  3887  3912 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
03-19 11:45:19.239  3887  3912 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-19 11:45:19.239  3887  3912 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-19 11:45:19.239  3887  3912 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-19 11:45:19.239  3887  3912 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
03-19 11:45:19.239  3887  3912 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
03-19 11:45:19.239  3887  3912 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
03-19 11:45:19.239  3887  3912 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
03-19 11:45:19.239  3887  3912 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
03-19 11:45:19.239  3887  3912 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-19 11:45:19.239  3887  3912 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
03-19 11:45:19.239  3887  3912 E SQLiteOpenHelper: 	at com.android.providers.calendar.CalendarProvider2.getReadableDatabase(CalendarProvider2.java:5451)
03-19 11:45:19.239  3887  3912 E SQLiteOpenHelper: 	at com.htc.providers.calendar.HtcCalendarProvider.query(HtcCalendarProvider.java:103)
03-19 11:45:19.239  3887  3912 E SQLiteOpenHelper: 	at android.content.ContentProvider.query(ContentProvider.java:960)
03-19 11:45:19.239  3887  3912 E SQLiteOpenHelper: 	at android.content.ContentProvider$Transport.query(ContentProvider.java:220)
03-19 11:45:19.239  3887  3912 E SQLiteOpenHelper: 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:142)
03-19 11:45:19.239  3887  3912 E SQLiteOpenHelper: 	at android.os.Binder.execTransact(Binder.java:454)
,03-19 11:45:19.249  3887  3912 W SQLiteOpenHelper: Opened calendar.db in read-only mode
,03-19 11:45:19.249  3887  3926 E CalendarReceiver: error,
03-19 11:45:19.249  3887  3926 E CalendarReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-19 11:45:19.249  3887  3926 E CalendarReceiver: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-19 11:45:19.249  3887  3926 E CalendarReceiver: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
03-19 11:45:19.249  3887  3926 E CalendarReceiver: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
03-19 11:45:19.249  3887  3926 E CalendarReceiver: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-19 11:45:19.249  3887  3926 E CalendarReceiver: 	at android.database.sqlite.SQLiteConnectionPool.reconfigure(SQLiteConnectionPool.java:306)
03-19 11:45:19.249  3887  3926 E CalendarReceiver: 	at android.database.sqlite.SQLiteDatabase.reopenReadWrite(SQLiteDatabase.java:823)
03-19 11:45:19.249  3887  3926 E CalendarReceiver: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:212)
03-19 11:45:19.249  3887  3926 E CalendarReceiver: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-19 11:45:19.249  3887  3926 E CalendarReceiver: 	at com.android.providers.calendar.CalendarDatabaseHelper.getWritableDatabase(CalendarDatabaseHelper.java:2521)
03-19 11:45:19.249  3887  3926 E CalendarReceiver: 	at com.android.providers.calendar.SQLiteContentProvider.update(SQLiteContentProvider.java:153)
03-19 11:45:19.249  3887  3926 E CalendarReceiver: 	at android.content.ContentProvider$Transport.update(ContentProvider.java:335)
03-19 11:45:19.249  3887  3926 E CalendarReceiver: 	at android.content.ContentResolver.update(ContentResolver.java:1354)
03-19 11:45:19.249  3887  3926 E CalendarReceiver: 	at com.android.providers.calendar.CalendarReceiver.removeScheduledAlarms(CalendarReceiver.java:101)
03-19 11:45:19.249  3887  3926 E CalendarReceiver: 	at com.android.providers.calendar.CalendarReceiver.access$000(CalendarReceiver.java:36)
03-19 11:45:19.249  3887  3926 E CalendarReceiver: 	at com.android.providers.calendar.CalendarReceiver$1.run(CalendarReceiver.java:74)
03-19 11:45:19.249  3887  3926 E CalendarReceiver: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-19 11:45:19.249  3887  3926 E CalendarReceiver: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-19 11:45:19.249  3887  3926 E CalendarReceiver: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-19 11:45:19.249  3887  3926 E CalendarReceiver: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-19 11:45:19.249  3887  3926 E CalendarReceiver: 	at java.lang.Thread.run(Thread.java:818)
03-19 11:45:19.249   952  1764 D PMS     : releaseWL(b75d525): PARTIAL_WAKE_LOCK  CalendarReceiverProvider_5 0x1 null
,03-19 11:45:19.289   952  2376 I ActivityManager: Start proc com.htc.android.mail:sync for content provider com.htc.android.mail/.MailProvider: pid=3927 uid=10062 gids={50062, 9997, 3003, 1023, 1028, 1015} abi=armeabi-v7a
,03-19 11:45:19.299  3857  3897 D HtcAlertService: start to updateAlertNotification!
,03-19 11:45:19.309   952  1772 D Process : killProcessQuiet, pid=3305
03-19 11:45:19.309   952  1772 I ActivityManager: Killing 3305:com.google.android.talk/u0a112 (adj 15): empty #17
03-19 11:45:19.309   952  1772 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.removeContentProvider:10141 ,
,03-19 11:45:19.369   395  3417 D libc    : [NET]Querying server xid =a299 (# 1) address = 192.168.1.1 (try=1,nscount=1,v_circuit=0)
,03-19 11:45:19.369   395  3417 D libc    : before statp->options=0x800002C3)
,03-19 11:45:19.429   952  1715 I ActivityManager: Recipient 3305
,03-19 11:45:19.569   952  1764 I ActivityManager: Start proc com.htc.demoflopackageinstaller for broadcast com.htc.demoflopackageinstaller/.PIReceiver: pid=3949 uid=10016 gids={50016, 9997, 3003, 1028, 1015} abi=arm64-v8a,
,03-19 11:45:19.569  1678  3948 W CustomizationIntentService: failed at default contact creation!,
03-19 11:45:19.569  1678  3948 W CustomizationIntentService: java.lang.SecurityException: Requesting code from com.htc.contacts (with uid 10038) to be run in process android.process.acore (with uid 10013)
03-19 11:45:19.569  1678  3948 W CustomizationIntentService: 	at android.app.ActivityThread.getPackageInfo(ActivityThread.java:1793)
03-19 11:45:19.569  1678  3948 W CustomizationIntentService: 	at android.app.ActivityThread.getPackageInfo(ActivityThread.java:1768)
03-19 11:45:19.569  1678  3948 W CustomizationIntentService: 	at android.app.ContextImpl.createPackageContextAsUser(ContextImpl.java:2266)
03-19 11:45:19.569  1678  3948 W CustomizationIntentService: 	at android.app.ContextImpl.createPackageContext(ContextImpl.java:2253)
03-19 11:45:19.569  1678  3948 W CustomizationIntentService: 	at android.content.ContextWrapper.createPackageContext(ContextWrapper.java:658)
03-19 11:45:19.569  1678  3948 W CustomizationIntentService: 	at com.android.providers.contacts.HtcUtils.customization.CustomizationIntentService.handleIntentInternal(CustomizationIntentService.java:143)
03-19 11:45:19.569  1678  3948 W CustomizationIntentService: 	at com.android.providers.contacts.HtcUtils.customization.CustomizationIntentService.onHandleIntent(CustomizationIntentService.java:104)
03-19 11:45:19.569  1678  3948 W CustomizationIntentService: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-19 11:45:19.569  1678  3948 W CustomizationIntentService: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-19 11:45:19.569  1678  3948 W CustomizationIntentService: 	at android.os.Looper.loop(Looper.java:155)
03-19 11:45:19.569  1678  3948 W CustomizationIntentService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-19 11:45:19.569  1678  3948 W CustomizationIntentService: handleIntentInternal(): action = com.htc.intent.action.PRELOAD_CONTACTS, original action = android.intent.action.BOOT_COMPLETED, launched by: null
03-19 11:45:19.579  1678  3948 W CustomizationIntentService: AFH Enable: false, LEONCHAME: false
03-19 11:45:19.589  1678  3948 W CustomizationIntentService: hasBeenInit true
03-19 11:45:19.589  1678  3948 W CustomizationIntentService: isNewChameleonHFASupported false
03-19 11:45:19.589  1678  3948 W CustomizationIntentService: isHFA true
03-19 11:45:19.589  1678  3948 W CustomizationIntentService: setupWizRun 1
,03-19 11:45:19.589  3857  3897 D HtcAlertService: No fired or scheduled alerts
03-19 11:45:19.589  3857  3897 D HtcAlertUtils: -- cancelReminderNotification --
,03-19 11:45:19.599  3857  3897 D HtcAlertUtils: broadcastExistReminder!
,03-19 11:45:19.599  1295  1295 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,03-19 11:45:19.599   952  2301 D PMS     : releaseWL(23693acf): PARTIAL_WAKE_LOCK  StartingAlertService_5 0x1 null
,03-19 11:45:19.599  3857  3897 W AlertReceiver: stopSelfResult true
03-19 11:45:19.599   952  1248 I ActivityManager: Killing 3342:com.google.android.apps.magazines/u0a161 (adj 15): empty #17
03-19 11:45:19.599   952  1248 D Process : killProcessQuiet, pid=3342
03-19 11:45:19.599   952  1248 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,03-19 11:45:19.759   952  1694 I ActivityManager: Recipient 3342
,03-19 11:45:19.789   952   952 E WifiDataStallTracker: DATA_MONITOR_POLL true Token 1,
,03-19 11:45:19.799   952  3970 D WifiDataStallTracker: updateDataStallInfo: mDataStallTxRxSum={txSum=33 rxSum=25} preTxRxSum={txSum=26 rxSum=19}
03-19 11:45:19.799   952  3970 D WifiDataStallTracker: updateDataStallInfo: IN/OUT,
03-19 11:45:19.799   952  3970 D WifiDataStallTracker: onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,03-19 11:45:19.839   952   952 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 6,
03-19 11:45:19.839   952   952 E WifiTrafficPoller:  packet count Tx=48 Rx=54
03-19 11:45:19.839   952   952 E WifiTrafficPoller: notifying of data activity 2
,03-19 11:45:19.839  1219  1219 D WIFI_ICON: WifiActivity: 2
03-19 11:45:19.839  1219  1219 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_out_4 (gone) T],
,03-19 11:45:19.859  3949  3949 D DFPI.PIReciver: onReceiver action:android.intent.action.BOOT_COMPLETED,
03-19 11:45:19.859  3949  3949 D DFPI    : getInstance = com.htc.demoflopackageinstaller.ApkInstallHelper@39ed3977
,03-19 11:45:19.859  3927  3946 D HtcAdjCursorFactory: Set CursorWindow size to: 4194304 KB, Tid: 3946
,03-19 11:45:19.869  3949  3949 D DFPI    : set install APK prefrence is false,
,03-19 11:45:19.869  3927  3946 E SQLiteDatabase: Failed to open database '/data/user/0/com.htc.android.mail/databases/mail.db'.,
03-19 11:45:19.869  3927  3946 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-19 11:45:19.869  3927  3946 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-19 11:45:19.869  3927  3946 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
03-19 11:45:19.869  3927  3946 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
03-19 11:45:19.869  3927  3946 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-19 11:45:19.869  3927  3946 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-19 11:45:19.869  3927  3946 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-19 11:45:19.869  3927  3946 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
03-19 11:45:19.869  3927  3946 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
03-19 11:45:19.869  3927  3946 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
03-19 11:45:19.869  3927  3946 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
03-19 11:45:19.869  3927  3946 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
03-19 11:45:19.869  3927  3946 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-19 11:45:19.869  3927  3946 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
03-19 11:45:19.869  3927  3946 E SQLiteDatabase: 	at com.htc.android.mail.kq.a(MailProvider.java:5368)
03-19 11:45:19.869  3927  3946 E SQLiteDatabase: 	at com.htc.android.mail.kq.a(MailProvider.java:5433)
03-19 11:45:19.869  3927  3946 E SQLiteDatabase: 	at com.htc.android.mail.MailProvider.query(MailProvider.java:2114)
03-19 11:45:19.869  3927  3946 E SQLiteDatabase: 	at android.content.ContentProvider.query(ContentProvider.java:960)
03-19 11:45:19.869  3927  3946 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.query(ContentProvider.java:220)
03-19 11:45:19.869  3927  3946 E SQLiteDatabase: 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:142)
03-19 11:45:19.869  3927  3946 E SQLiteDatabase: 	at android.os.Binder.execTransact(Binder.java:454)
03-19 11:45:19.869  3927  3946 E SQLiteOpenHelper: Couldn't open mail.db for writing (will try read-only):
03-19 11:45:19.869  3927  3946 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-19 11:45:19.869  3927  3946 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-19 11:45:19.869  3927  3946 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
03-19 11:45:19.869  3927  3946 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
03-19 11:45:19.869  3927  3946 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-19 11:45:19.869  3927  3946 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-19 11:45:19.869  3927  3946 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-19 11:45:19.869  3927  3946 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
03-19 11:45:19.869  3927  3946 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
03-19 11:45:19.869  3927  3946 E SQLiteOpenHelper: 	at android.database.sql,ite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
03-19 11:45:19.869  3927  3946 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
03-19 11:45:19.869  3927  3946 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
03-19 11:45:19.869  3927  3946 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-19 11:45:19.869  3927  3946 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
03-19 11:45:19.869  3927  3946 E SQLiteOpenHelper: 	at com.htc.android.mail.kq.a(MailProvider.java:5368)
03-19 11:45:19.869  3927  3946 E SQLiteOpenHelper: 	at com.htc.android.mail.kq.a(MailProvider.java:5433)
03-19 11:45:19.869  3927  3946 E SQLiteOpenHelper: 	at com.htc.android.mail.MailProvider.query(MailProvider.java:2114)
03-19 11:45:19.869  3927  3946 E SQLiteOpenHelper: 	at android.content.ContentProvider.query(ContentProvider.java:960)
03-19 11:45:19.869  3927  3946 E SQLiteOpenHelper: 	at android.content.ContentProvider$Transport.query(ContentProvider.java:220)
03-19 11:45:19.869  3927  3946 E SQLiteOpenHelper: 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:142)
03-19 11:45:19.869  3927  3946 E SQLiteOpenHelper: 	at android.os.Binder.execTransact(Binder.java:454)
03-19 11:45:19.879  3927  3946 W SQLiteOpenHelper: Opened mail.db in read-only mode
,03-19 11:45:19.889  3564  3850 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
03-19 11:45:19.889  3564  3850 I Prism.ItemManager: loadItems() com.htc.launcher.pageview.WidgetManager@cd7c226 +
03-19 11:45:19.889  3564  3850 I Prism.WidgetManager: onLoadItems() +
,03-19 11:45:19.899   952  1772 I ActivityManager: Killing 3439:com.android.chrome/u0a96 (adj 15): empty #17
03-19 11:45:19.899   952  1772 D Process : killProcessQuiet, pid=3439
03-19 11:45:19.899   952  1772 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,03-19 11:45:19.939  3564  3850 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.,
,03-19 11:45:19.959  1455  2002 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
03-19 11:45:19.959  1455  2002 I Prism.ItemManager: loadItems() com.htc.launcher.pageview.WidgetManager@118c2576 +
03-19 11:45:19.959  1455  2002 I Prism.WidgetManager: onLoadItems() +
,03-19 11:45:19.989   952  2301 I ActivityManager: Recipient 3439,
,03-19 11:45:19.999  1455  2002 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,03-19 11:45:20.029   952  1772 I ActivityManager: Start proc com.htc.fm for broadcast com.htc.fm/.uiservice.receiver.BootCompletedReceiver: pid=3977 uid=10020 gids={50020, 9997, 1028, 1015} abi=arm64-v8a,
,03-19 11:45:20.039  3621  3621 D EmailUtils: ============NULL aList========
,03-19 11:45:20.039  3621  3621 V EmailUtils: <-getEmailAccountIdList
03-19 11:45:20.039  3621  3621 V BluetoothMasService: onCreate: mIsEmailEnabled: true
03-19 11:45:20.039  3621  3621 D BluetoothAdapter: 1029354603: getState(). Returning 12
03-19 11:45:20.039  3621  3621 V BluetoothMasService: parseIntent 1: mIsEmailEnabled: true
03-19 11:45:20.039  3621  3621 V EmailUtils: Manager Instance is not NULL
,03-19 11:45:20.059  3621  3621 D EmailUtils: ============NULL aList========
,03-19 11:45:20.059  3621  3621 V EmailUtils: <-getEmailAccountIdList
03-19 11:45:20.059  3621  3621 V BluetoothMasService: handleMessage: mIsEmailEnabledtrue
03-19 11:45:20.059  3621  3621 V BtMns   : BluetoothMns: isEmailEnabled: true
,03-19 11:45:20.059   952  1385 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,03-19 11:45:20.059  3621  3621 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-19 11:45:20.059  3621  3621 I bt-btif : BTA_JvCreateRecordByUser
03-19 11:45:20.059  3621  3829 D bt-btm  : BTM_AllocateSCN
,03-19 11:45:20.059  3621  3829 D bt-sdp  : SDP_CreateRecord ok, num_records:13
03-19 11:45:20.059  3621  3829 I bt-btm  : Write Extended Inquiry Response to controller,
03-19 11:45:20.059  3621  3829 I bt-btif : BTA_JvRfcommStartServer
03-19 11:45:20.059  3621  3829 I bt-btm  : BTM_SEC_REG[16]: id 58, is_orig 0, psm 0x0003, proto_id 3, chan_id 4
03-19 11:45:20.059  3621  3829 I bt-btm  :                : sec: 0x1086, service name [JV PORT] (up to 21 chars saved)
03-19 11:45:20.069   952  1248 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
03-19 11:45:20.069  3621  3621 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-19 11:45:20.069  3621  3621 I bt-btif : BTA_JvCreateRecordByUser
03-19 11:45:20.069  3621  3829 D bt-btm  : BTM_AllocateSCN
03-19 11:45:20.069  3621  3829 D bt-sdp  : SDP_CreateRecord ok, num_records:14
03-19 11:45:20.069  3621  3829 I bt-btm  : Write Extended Inquiry Response to controller
03-19 11:45:20.069  3621  3829 I bt-btif : BTA_JvRfcommStartServer
03-19 11:45:20.069  3621  3829 I bt-btm  : BTM_SEC_REG[17]: id 59, is_orig 0, psm 0x0003, proto_id 3, chan_id 5
03-19 11:45:20.069  3621  3829 I bt-btm  :                : sec: 0x1086, service name [JV PORT] (up to 21 chars saved)
03-19 11:45:20.069  3621  3621 V BluetoothSapReceiver: SapReceiver onReceive 
03-19 11:45:20.069  3621  3621 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
03-19 11:45:20.069  3621  3621 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
03-19 11:45:20.069  3621  3621 V BluetoothSapReceiver: Calling SAP service start service with action = android.bluetooth.adapter.action.STATE_CHANGED
03-19 11:45:20.069  3621  3621 D A2dpService: getA2DPService(): returning com.android.bluetooth.a2dp.A2dpService@38f86f8
03-19 11:45:20.069  3621  3621 D A2dpSinkService: getA2dpSinkService(): service is NULL
,03-19 11:45:20.079   952  1764 I ActivityManager: Killing 2273:com.google.android.gms.wearable/u0a24 (adj 15): empty #17
03-19 11:45:20.079   952  1764 D Process : killProcessQuiet, pid=2273
03-19 11:45:20.079   952  1764 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.removeContentProvider:10141 
03-19 11:45:20.079  1883  1883 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.

```
