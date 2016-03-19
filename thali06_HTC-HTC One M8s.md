#### Test 62548124d9c0fd9_thali06_HTC-HTC One M8s Logs


```
--------- beginning of main
03-19 12:52:27.323  3269  3356 W AudioManagerAndroid: Requires BLUETOOTH permission
03-19 12:52:27.343  3269  3269 I NSApplication: Starting up...
03-19 12:52:27.373   925  1339 D Process : killProcessQuiet, pid=2963
03-19 12:52:27.373   925  1339 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
--------- beginning of system
03-19 12:52:27.373   925  1339 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=3361 uid=10096 gids={50096, 9997, 3003, 1028, 1015} abi=arm64-v8a
03-19 12:52:27.373   925  1339 I ActivityManager: Killing 2963:com.htc.widget.hmsproc2/u0a40 (adj 15): empty #17
,03-19 12:52:27.453   925  1617 I ActivityManager: Recipient 2963
03-19 12:52:27.493   925   982 D Process : killProcessQuiet, pid=2985
03-19 12:52:27.493   925   982 I ActivityManager: Killing 2985:com.htc.widget.hmsproc1/u0a35 (adj 15): empty #17
03-19 12:52:27.493   925   982 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
03-19 12:52:27.573   925  1766 I ActivityManager: Recipient 2985
03-19 12:52:27.663   419  1050 I WVCdm   : CdmEngine::OpenSession
03-19 12:52:27.663   419  1050 I WVCdm   : Level3 Library Sep 25 2014 17:10:03
03-19 12:52:27.673   412  3304 D libc    : [NET] _dns_getaddrinfo-, (NS_SUCCESS)
03-19 12:52:27.673   412  3304 D libc    : [NET] android_getaddrinfofornet-, SUCCESS
03-19 12:52:27.673  3235  3302 D libc    : [NET] android_getaddrinfo_proxy-, success
03-19 12:52:27.683   419  1050 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
03-19 12:52:27.693   419  1050 D DrmWidevineDash: OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x15
03-19 12:52:27.693   419  1050 D DrmWidevineDash: Service_Initialize: starts!
03-19 12:52:27.693   419  1050 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
03-19 12:52:27.693   419  1050 D QSEECOMAPI: : App is not loaded in QSEE
03-19 12:52:27.693   419  1050 E QSEECOMAPI: : Error::Cannot open the file /vendor/firmware/widevine.mdt
03-19 12:52:27.693   419  1050 E QSEECOMAPI: : Error::Loading image failed with ret = -1
03-19 12:52:27.693   419  1050 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
03-19 12:52:27.693   419  1050 D QSEECOMAPI: : App is not loaded in QSEE
03-19 12:52:27.713  3384  3390 E cutils-trace: Error opening trace file: Permission denied (13)
03-19 12:52:27.713   419  1050 D QSEECOMAPI: : Loaded image: APP id = 6
03-19 12:52:27.723   419  1050 D DrmWidevineDash: Service_Initialize: ends! returns 0
03-19 12:52:27.723   419  1050 D QSAPPSVER: qsapps_get_capabilities: Capability from secure side: 0x0
03-19 12:52:27.723   419  1050 D QSAPPSVER: qsapps_get_capabilities: returns 0
03-19 12:52:27.723   419  1050 D DrmWidevineDash: OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf4864000
03-19 12:52:27.723   419  1050 E DrmWidevineDash: sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf4864000
03-19 12:52:27.723   419  1050 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
03-19 12:52:27.723   547   563 D DrmLibTime: got the req here! ret=0
03-19 12:52:27.723   547   563 D DrmLibTime: command id, time_cmd_id = 770
03-19 12:52:27.723   547   563 D DrmLibTime: time_getutcsec starts!
03-19 12:52:27.723   547   563 D DrmLibTime: QSEE Time Listener: time_getutcsec
03-19 12:52:27.723   547   563 D DrmLibTime: QSEE Time Listener: get_utc_seconds
03-19 12:52:27.723   547   563 D DrmLibTime: QSEE Time Listener: time_get_modem_time
03-19 12:52:27.723   547   563 D DrmLibTime: QSEE Time Listener: Checking if ATS_MODEM is set or not.
03-19 12:52:27.733   547   563 E QC-time-services: Receive Passed == base = 13, unit = 1, operation = 2, result = 0
03-19 12:52:27.733   547   563 D DrmLibTime: QSEE Time Listener: ATS_MODEM is not set. Fallback to Android system time.
03-19 12:52:27.733   547   563 D DrmLibTime: QSEE Time Listener: Retrieved Android system time: 1458388347
03-19 12:52:27.733   547   563 D DrmLibTime: time_getutcsec returns 0, sec = 1458388347; nsec = 0
03-19 12:52:27.733   547   563 D DrmLibTime: time_getutcsec finished! 
03-19 12:52:27.733   547   563 D DrmLibTime: iotcl_continue_command finished! and return 0 
03-19 12:52:27.733   547   563 D DrmLibTime: before calling ioctl to read the next time_cmd
03-19 12:52:27.733   463   590 E QC-time-services: Daemon: Time-services: Waiting to acceptconnection
03-19 12:52:27.733   419  1050 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
03-19 12:52:27.743   419  1050 D DrmWidevineDash: OEMCrypto_Initialize: ends! returns 0
03-19 12:52:27.743   419  1050 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
03-19 12:52:27.743   419  1050 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
03-19 12:52:27.743   419  1050 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
03-19 12:52:27.743   419  1050 D DrmWidevineDash: hlos api version =  9
03-19 12:52:27.743   419  1050 D DrmWidevineDash: tz api version =  9
03-19 12:52:27.743   419  1050 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 9
03-19 12:52:27.743   419  1050 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: starts!
03-19 12:52:27.743   925  1619 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=3398 uid=10167 gids={50167, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
03-19 12:52:27.743   419  1050 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
03-19 12:52:27.753   925  1619 D Process : killProcessQuiet, pid=3009
03-19 12:52:27.753   925  1619 I ActivityManager: Killing 3009:com.htc.mms.backupagent/u0a76 (adj 15): empty #17
03-19 12:52:27.753   925  1619 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
03-19 12:52:27.763   925   925 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 7
03-19 12:52:27.763   925   925 E WifiTrafficPoller:  packet count Tx=35 Rx=31
03-19 12:52:27.763  1221  1221 D WIFI_ICON: WifiActivity: 3
03-19 12:52:27.763   925   925 E WifiTrafficPoller: notifying of data activity 3
03-19 12:52:27.763  1221  1221 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
03-19 12:52:27.763   925  1153 E WifiStateMachine: handleMessage: E msg.what=131155
03-19 12:52:27.763   925  1153 E WifiStateMachine: processMsg: ConnectedState
03-19 12:52:27.763   925  1153 E WifiStateMachine:  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-57 f=2457 sc=60 link=150 tx=9.7, 0.0, 0.0  rx=8.8 bcn=0 [on:0 tx:0 rx:0 period:2999] from screen [on:0 period:-1900532868] gl hn u24 rssi=-52 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
03-19 12:52:27.763   925  1153 E WifiStateMachine: processMsg: L2ConnectedState
03-19 12:52:27.763   925  1153 E WifiStateMachine:  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-57 f=2457 sc=60 link=150 tx=9.7, 0.0, 0.0  rx=8.8 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1900532866] gl hn u24 rssi=-52 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
03-19 12:52:27.773   925  1766 I ActivityManager: Recipient 3009
03-19 12:52:27.763   925  1153 E WifiStateMachine:  get link layer stats 0
03-19 12:52:27.763   925  1153 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
03-19 12:52:27.763  1337  1337 D wpa_supplicant: wlan0: Control interface command 'SIGNAL_POLL'
03-19 12:52:27.773  1337  1337 I wpa_supplicant: environment dirty rate=0 [2][0][0]
03-19 12:52:27.773   925  1153 E WifiStateMachine: fetchRssiLinkSpeedAndFrequencyNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 150
03-19 12:52:27.773   925  1153 E WifiStateMachine: fetchRssiLinkSpeedAndFrequencyNative rssi=-57 linkspeed=150
03-19 12:52:27.773   925  1153 E WifiConfigStore: updateConfiguration freq=2457 BSSID=f4:f2:6d:22:99:3e RSSI=-56 "NG700"WPA_PSK
03-19 12:52:27.773   925  1153 E WifiStateMachine: calculateWifiScore freq=2457 speed=150 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=5.83 txretriesrate=0.00 rxrate=5.41 userTriggerdPenalty0
03-19 12:52:27.773   925  1153 E WifiStateMachine:  good link -> stuck count =0
03-19 12:52:27.773   925  1153 E WifiStateMachine:  badRSSI count0 lowRSSI count0 --> score 60
03-19 12:52:27.773   925  1153 E WifiStateMachine:  isHighRSSI       ---> score=65
03-19 12:52:27.783   419  1050 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
03-19 12:52:27.783   419  1050 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: ends! returns 0
03-19 12:52:27.783   419  1050 D WVCdm   : OEMCrypto_Initialize Level 1 success. I will use level 1.
03-19 12:52:27.783   419  1050 D DrmWidevineDash: OEMCrypto_OpenSession: starts! SID=0xf4b8e928
03-19 12:52:27.783   419  1050 D DrmWidevineDash: OEMCrypto_OpenSession Session ID = 0
03-19 12:52:27.783   419  1050 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
03-19 12:52:27.783   419  1050 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
03-19 12:52:27.783   419  1050 D DrmWidevineDash: OEMCrypto_OpenSession SID = 1
03-19 12:52:27.783   419  1050 D DrmWidevineDash: OEMCrypto_OpenSession: ends! returns 0
03-19 12:52:27.783   419  1050 D DrmWidevineDash: OEMCrypto_GetRandom: starts! randomData=0xab379998, dataLength=8
03-19 12:52:27.783   419  1050 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
03-19 12:52:27.783   419  1050 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
03-19 12:52:27.783   419  1050 D DrmWidevineDash: OEMCrypto_GetRandom: ends! returns 0
03-19 12:52:27.793   419  1050 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: starts! SID=1, wrapped_rsa_key=0xab3783b8, wrapped_rsa_key_length=1280
03-19 12:52:27.793   419  1050 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
03-19 12:52:27.793   419  1050 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
03-19 12:52:27.793   419  1050 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: ends! returns 0
03-19 12:52:27.793   419  1050 I WVCdm   : CdmEngine::QueryKeyControlInfo
03-19 12:52:27.793   419   419 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
03-19 12:52:27.793   419   419 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
03-19 12:52:27.793   419   419 I WVCdm   : CdmEngine::GenerateKeyRequest
03-19 12:52:27.793   419   419 D DrmWidevineDash: OEMCrypto_GetDeviceID: starts! deviceID=0xab3754a8, idLength=0xffb5ea78
03-19 12:52:27.793   419   419 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
03-19 12:52:27.813   419   419 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
03-19 12:52:27.813   419   419 D DrmWidevineDash: OEMCrypto_GetDeviceID: ends! returns 0
03-19 12:52:27.813   419   419 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: starts!
03-19 12:52:27.813   419   419 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
03-19 12:52:27.813   419   419 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
03-19 12:52:27.813   419   419 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: is_supported = 1
03-19 12:52:27.813   419   419 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: wv_app_version = 24
03-19 12:52:27.813   419   419 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: ends! returns 0
03-19 12:52:27.813   419   419 D DrmWidevineDash: OEMCrypto_GetHDCPCapability: starts!, current = 0xffb5ea8e, maximum = 0xffb5ea8f
03-19 12:52:27.813   419   419 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
03-19 12:52:27.813  3384  3384 D CustomizationManager: ====startRecUseTime====
03-19 12:52:27.813  3384  3384 D htc.customization.log.level:  is 
03-19 12:52:27.813   419   419 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
03-19 12:52:27.813   419   419 D DrmWidevineDash: OEMCrypto_GetHDCPCapability: ends! returns 0
03-19 12:52:27.813   419   419 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
03-19 12:52:27.813   419   419 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
03-19 12:52:27.813  3384  3384 W CustomizationLogLevel: Level value is invalid, use default level 2
03-19 12:52:27.813   419   419 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
03-19 12:52:27.813   419   419 D DrmWidevineDash: hlos api version =  9
03-19 12:52:27.813   419   419 D DrmWidevineDash: tz api version =  9
03-19 12:52:27.813   419   419 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 9
03-19 12:52:27.813   419   419 D DrmWidevineDash: OEMCrypto_GenerateNonce: starts! SID=1, nonce=0xffb5eafc
03-19 12:52:27.813   419   419 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
03-19 12:52:27.813   419   419 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
03-19 12:52:27.813   419   419 D DrmWidevineDash: OEMCrypto_GenerateNonce: ends! returns 0
03-19 12:52:27.813   419   419 D WVCdm   : PrepareKeyRequest: nonce=612210953
03-19 12:52:27.813   419   419 D DrmWidevineDash: OEMCrypto_GenerateRSASignature starts! SID=1, message=0xab45c148
03-19 12:52:27.813   419   419 D DrmWidevineDash: message_length=1611, signature=0xab45c798, signature_length=0xffb5ea5c
03-19 12:52:27.813   419   419 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
03-19 12:52:27.873   925  1171 D WifiWatchdogStateMachine: RSSI current: 3 new: -57, 3
03-19 12:52:27.873  1221  1221 D WIFI_ICON: updateWifiState: RSSI_CHANGED 3 -> 3
03-19 12:52:27.873   925  1153 E WifiStateMachine: handleMessage: X
03-19 12:52:27.873  1221  1221 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
03-19 12:52:27.883  1624  2106 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
03-19 12:52:27.883  3384  3384 D CustomizationManager:  Read ACC file spent 0.034 (s)
03-19 12:52:27.883  1624  2106 I Prism.ItemManager: loadItems() com.htc.launcher.pageview.WidgetManager@21be4e74 +
03-19 12:52:27.883  1624  2106 I Prism.WidgetManager: onLoadItems() +
03-19 12:52:27.883  3384  3384 D CIDMapFileReader: Parsing tag item name = HTC__001
03-19 12:52:27.883  3384  3384 D CIDMapFileReader: Parsing tag item name = HTC__102
03-19 12:52:27.883  3384  3384 D CIDMapFileReader: Parsing tag item name = HTC__Y13
03-19 12:52:27.883  3384  3384 D CIDMapFileReader: Parsing tag item name = HTC__032
03-19 12:52:27.883  3384  3384 D CIDMapFileReader: Parsing tag item name = HTC__M27
03-19 12:52:27.883  3384  3384 D CIDMapFileReader: Parsing tag item name = HTC__002
03-19 12:52:27.883  3384  3384 D CIDMapFileReader: Parsing tag item name = HTC__031
03-19 12:52:27.883  3384  3384 V CustomizationCIDLoader: full path : /system/customize/CID/HTC__102.xml
03-19 12:52:27.883  3384  3384 I CustomizationCIDLoader: Parsing tag category name = system
03-19 12:52:27.883  3384  3384 I CustomizationCIDLoader: Parsing tag category name = application
03-19 12:52:27.883  3384  3384 I CustomizationCIDLoader: Parsing tag category name = SettingsProvider
03-19 12:52:27.883  3384  3384 I CustomizationCIDLoader: Parsing tag category name = AutomotiveHome
03-19 12:52:27.883  3384  3384 I CustomizationCIDLoader: Parsing tag category name = AudioService
03-19 12:52:27.883  3384  3384 I CustomizationCIDLoader: Parsing tag category name = Settings
03-19 12:52:27.883  3384  3384 I CustomizationCIDLoader: Parsing tag category name = ACC
03-19 12:52:27.883  3384  3384 I CustomizationCIDLoader: add string-array item, value = 42507
03-19 12:52:27.883  3384  3384 I CustomizationCIDLoader: add string-array item, value = 21902
03-19 12:52:27.883  3384  3384 I CustomizationCIDLoader: add string-array item, value = 26006:26001.26002.26003
03-19 12:52:27.883  3384  3384 I CustomizationCIDLoader: add string-array item, value = 23420
03-19 12:52:27.883  3384  3384 I CustomizationCIDLoader: add string-array item, value = 22299
03-19 12:52:27.883  3384  3384 I CustomizationCIDLoader: add string-array item, value = 24002
03-19 12:52:27.883  3384  3384 I CustomizationCIDLoader: add string-array item, value = 23210
03-19 12:52:27.883  3384  3384 I CustomizationCIDLoader: add string-array item, value = 23205
03-19 12:52:27.883  3384  3384 I CustomizationCIDLoader: add string-array item, value = 23806
03-19 12:52:27.883  3384  3384 I CustomizationCIDLoader: add string-array item, value = 23430
03-19 12:52:27.883  3384  3384 I CustomizationCIDLoader: add string-array item, value = 23408
03-19 12:52:27.883  3384  3384 I CustomizationCIDLoader: add string-array item, value = 27205
03-19 12:52:27.893  3384  3384 I CustomizationCIDLoader: add string-array item, value = 42507:C:1:0
03-19 12:52:27.893  3384  3384 I CustomizationCIDLoader: add string-array item, value = 21902:C:1:0
03-19 12:52:27.893  3384  3384 I CustomizationCIDLoader: add string-array item, value = 26006:D:1:0
03-19 12:52:27.893  3384  3384 I CustomizationCIDLoader: add string-array item, value = 23420:D:0:0
03-19 12:52:27.893  3384  3384 I CustomizationCIDLoader: add string-array item, value = 22299:D:0:0
03-19 12:52:27.893  3384  3384 I CustomizationCIDLoader: add string-array item, value = 24002:D:0:0
03-19 12:52:27.893  3384  3384 I CustomizationCIDLoader: add string-array item, value = 23210:D:2:0
03-19 12:52:27.893  3384  3384 I CustomizationCIDLoader: add string-array item, value = 23205:D:0:0
03-19 12:52:27.893  3384  3384 I CustomizationCIDLoader: add string-array item, value = 23806:D:0:0
03-19 12:52:27.893  3384  3384 I CustomizationCIDLoader: add string-array item, value = 23430:C:1:0
03-19 12:52:27.893  3384  3384 I CustomizationCIDLoader: add string-array item, value = 23408:C:1:0
03-19 12:52:27.893  3384  3384 I CustomizationCIDLoader: add string-array item, value = 27205:C:1:0
03-19 12:52:27.893  3384  3384 D CustomizationManager:  Read CID file spent 0.076 (s)
03-19 12:52:27.893  3384  3384 D CustomizationManager:  All configurations done spent 0.076 (s)
03-19 12:52:27.903  3398  3398 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-19 12:52:27.913  1624  2106 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
03-19 12:52:27.923   925  1617 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 pid 3384 on display 0
03-19 12:52:27.933   925  1063 D PMS     : acquireHCC(3e53d773): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 925 1000 null
03-19 12:52:27.933   925  1063 D PMS     : acquireHCC(2b49f630): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 925 1000 null
03-19 12:52:27.933   419   419 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
03-19 12:52:27.933   419   419 D DrmWidevineDash: OEMCrypto_GenerateRSASignature returns 0
03-19 12:52:27.933   419  1163 I WVCdm   : CdmEngine::CloseSession
03-19 12:52:27.933   419  1163 D DrmWidevineDash: OEMCrypto_CloseSession: starts! SID=1
03-19 12:52:27.933   419  1163 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
03-19 12:52:27.933   419  1163 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
03-19 12:52:27.933   419  1163 D DrmWidevineDash: OEMCrypto_CloseSession: ends! returns 0
03-19 12:52:27.933   419  1163 I WVCdm   : L3 Terminate.
03-19 12:52:27.933   419  1163 D DrmWidevineDash: OEMCrypto_Terminate: starts!
03-19 12:52:27.933   419  1163 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
03-19 12:52:27.933   419  1163 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
03-19 12:52:27.933   419  1163 D DrmWidevineDash: Service_Uninitialize: starts!
03-19 12:52:27.933   419  1163 D QSEECOMAPI: : QSEECom_dealloc_memory 
03-19 12:52:27.933   419  1163 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 6
03-19 12:52:27.933   419  1163 D DrmWidevineDash: Service_Uninitialize: ends! returns 0x0
03-19 12:52:27.933   419  1163 D DrmWidevineDash: OEMCrypto_Terminate: ends! returns 0
03-19 12:52:27.943   925  1617 D PMS     : acquireWL(88a77cf): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 925 1000 null
03-19 12:52:27.953  1624  1624 I FeedHostManager: [onPause]
03-19 12:52:27.953  1624  1624 I FeedProviderManager: onPause
03-19 12:52:27.953  1624  1624 I FeedHostManager: [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@3c456042
03-19 12:52:27.953  1624  2436 I SocialFeedProvider: +onPause
03-19 12:52:27.953  1624  2436 I SocialFeedProvider: -onPause
03-19 12:52:27.953   925  1051 I AnimationUtil: isHTCRecent(ThaliTest/Recent screens.)/9
03-19 12:52:27.953   925  1667 W HtcSystemUPManager: HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
03-19 12:52:27.973   925  1769 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3429 uid=10195 gids={50195, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
03-19 12:52:28.073   925  1047 D StatusBarManagerService: setSystemUiVisibility(0x8600)
03-19 12:52:28.073   925  1047 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
03-19 12:52:28.073   925  1047 D StatusBarManagerService: hiding MENU key
03-19 12:52:28.083  1624  1624 I TrimMemoryManager: [trimMemory] 20
03-19 12:52:28.093  3450  3450 E cutils-trace: Error opening trace file: Permission denied (13)
03-19 12:52:28.093  3450  3450 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm64 --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=36 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
03-19 12:52:28.093  3450  3450 I dex2oat : dex2oat: override thread count:4
,03-19 12:52:28.193  3429  3429 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
,03-19 12:52:28.193  3450  3450 I dex2oat : dex2oat took 103.472ms (threads: 4)
,03-19 12:52:28.213  3317  3337 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
03-19 12:52:28.213  3317  3337 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.01
03-19 12:52:28.213  3317  3337 I Adreno-EGL: Build Date: 03/09/15 Mon
03-19 12:52:28.213  3317  3337 I Adreno-EGL: Local Branch: 
03-19 12:52:28.213  3317  3337 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
03-19 12:52:28.213  3317  3337 I Adreno-EGL: Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
03-19 12:52:28.213  3317  3337 I Adreno-EGL:                  d74aa161a12b9c6fc6332151
,03-19 12:52:28.223  1624  2106 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-19 12:52:28.263  3429  3429 I LibraryLoader: Time to load native libraries: 15 ms (timestamps 1816-1831)
,03-19 12:52:28.263  3429  3429 I LibraryLoader: Expected native library version number "",actual native library version number "",
,03-19 12:52:28.283  3429  3429 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {27302755}
,03-19 12:52:28.283  3429  3429 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-19 12:52:28.283  3429  3429 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,03-19 12:52:28.303  3317  3337 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
03-19 12:52:28.303  3317  3337 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.01
03-19 12:52:28.303  3317  3337 I Adreno-EGL: Build Date: 03/09/15 Mon
03-19 12:52:28.303  3317  3337 I Adreno-EGL: Local Branch: 
03-19 12:52:28.303  3317  3337 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
03-19 12:52:28.303  3317  3337 I Adreno-EGL: Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
03-19 12:52:28.303  3317  3337 I Adreno-EGL:                  d74aa161a12b9c6fc6332151
,03-19 12:52:28.303  3429  3429 I BrowserStartupController: Initializing chromium process, singleProcess=true
03-19 12:52:28.313  3429  3429 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-19 12:52:28.313  3429  3429 E SysUtils: ApplicationContext is null in ApplicationStatus
,03-19 12:52:28.363   419  1050 I WVCdm   : CdmEngine::OpenSession
,03-19 12:52:28.363   419  1050 I WVCdm   : Level3 Library Sep 25 2014 17:10:03
03-19 12:52:28.363   419  1050 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory,
,03-19 12:52:28.383   419  1050 D DrmWidevineDash: OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x15
03-19 12:52:28.383   419  1050 D DrmWidevineDash: Service_Initialize: starts!
03-19 12:52:28.383   419  1050 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
03-19 12:52:28.383   419  1050 D QSEECOMAPI: : App is not loaded in QSEE
03-19 12:52:28.383   419  1050 E QSEECOMAPI: : Error::Cannot open the file /vendor/firmware/widevine.mdt
03-19 12:52:28.383   419  1050 E QSEECOMAPI: : Error::Loading image failed with ret = -1
03-19 12:52:28.383   419  1050 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
03-19 12:52:28.383   419  1050 D QSEECOMAPI: : App is not loaded in QSEE
,03-19 12:52:28.383  1624  2106 W asset   : Copying FileAsset 0x559fc278a0 (zip:/data/app/com.gameloft.android.gdc-2/base.apk:/resources.arsc) to buffer size 405676 to make it aligned.,
,03-19 12:52:28.393   419  1050 D QSEECOMAPI: : Loaded image: APP id = 7
,03-19 12:52:28.403   419  1050 D DrmWidevineDash: Service_Initialize: ends! returns 0,
03-19 12:52:28.403  3429  3429 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,03-19 12:52:28.403   419  1050 D QSAPPSVER: qsapps_get_capabilities: Capability from secure side: 0x0
,03-19 12:52:28.403   419  1050 D QSAPPSVER: qsapps_get_capabilities: returns 0
03-19 12:52:28.403   419  1050 D DrmWidevineDash: OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf4864000
03-19 12:52:28.403   419  1050 E DrmWidevineDash: sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf4864000
03-19 12:52:28.403   419  1050 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,03-19 12:52:28.403  3429  3429 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-19 12:52:28.403  3429  3429 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-19 12:52:28.403  3429  3429 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
03-19 12:52:28.403  3429  3429 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.01
03-19 12:52:28.403  3429  3429 I Adreno-EGL: Build Date: 03/09/15 Mon
03-19 12:52:28.403  3429  3429 I Adreno-EGL: Local Branch: 
03-19 12:52:28.403  3429  3429 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
03-19 12:52:28.403  3429  3429 I Adreno-EGL: Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
03-19 12:52:28.403  3429  3429 I Adreno-EGL:                  d74aa161a12b9c6fc6332151
,03-19 12:52:28.403   547   563 D DrmLibTime: got the req here! ret=0
,03-19 12:52:28.403   547   563 D DrmLibTime: command id, time_cmd_id = 770
03-19 12:52:28.403   547   563 D DrmLibTime: time_getutcsec starts!
03-19 12:52:28.403   547   563 D DrmLibTime: QSEE Time Listener: time_getutcsec
03-19 12:52:28.403   547   563 D DrmLibTime: QSEE Time Listener: get_utc_seconds
03-19 12:52:28.403   547   563 D DrmLibTime: QSEE Time Listener: time_get_modem_time
03-19 12:52:28.403   547   563 D DrmLibTime: QSEE Time Listener: Checking if ATS_MODEM is set or not.
03-19 12:52:28.403   547   563 E QC-time-services: Receive Passed == base = 13, unit = 1, operation = 2, result = 0
03-19 12:52:28.403   547   563 D DrmLibTime: QSEE Time Listener: ATS_MODEM is not set. Fallback to Android system time.
03-19 12:52:28.403   547   563 D DrmLibTime: QSEE Time Listener: Retrieved Android system time: 1458388348
03-19 12:52:28.403   547   563 D DrmLibTime: time_getutcsec returns 0, sec = 1458388348; nsec = 0
03-19 12:52:28.403   547   563 D DrmLibTime: time_getutcsec finished! 
03-19 12:52:28.403   463   590 E QC-time-services: Daemon: Time-services: Waiting to acceptconnection
03-19 12:52:28.403   547   563 D DrmLibTime: iotcl_continue_command finished! and return 0 
03-19 12:52:28.403   547   563 D DrmLibTime: before calling ioctl to read the next time_cmd
03-19 12:52:28.403   419  1050 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
03-19 12:52:28.413   925   925 E WifiDataStallTracker: DATA_MONITOR_POLL true Token 1
,03-19 12:52:28.413   925  1617 D Process : killProcessQuiet, pid=1686,
,03-19 12:52:28.413   925  1617 I ActivityManager: Killing 1686:com.google.android.googlequicksearchbox:search/u0a85 (adj 15): empty #17
03-19 12:52:28.413   925  1617 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
03-19 12:52:28.413   419  1050 D DrmWidevineDash: OEMCrypto_Initialize: ends! returns 0
03-19 12:52:28.413   419  1050 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
03-19 12:52:28.413   419  1050 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
03-19 12:52:28.413   419  1050 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
03-19 12:52:28.413   419  1050 D DrmWidevineDash: hlos api version =  9
03-19 12:52:28.413   419  1050 D DrmWidevineDash: tz api version =  9
,03-19 12:52:28.413   419  1050 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 9
03-19 12:52:28.413   419  1050 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: starts!
03-19 12:52:28.413   419  1050 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
03-19 12:52:28.413   925  3473 D WifiDataStallTracker: updateDataStallInfo: mDataStallTxRxSum={txSum=25 rxSum=19} preTxRxSum={txSum=15 rxSum=10}
03-19 12:52:28.413   925  3473 D WifiDataStallTracker: updateDataStallInfo: IN/OUT
03-19 12:52:28.413   925  3473 D WifiDataStallTracker: onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,03-19 12:52:28.453   419  1050 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
03-19 12:52:28.453   419  1050 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: ends! returns 0
03-19 12:52:28.453   419  1050 D WVCdm   : OEMCrypto_Initialize Level 1 success. I will use level 1.
03-19 12:52:28.453   419  1050 D DrmWidevineDash: OEMCrypto_OpenSession: starts! SID=0xf4b8e928
03-19 12:52:28.453   419  1050 D DrmWidevineDash: OEMCrypto_OpenSession Session ID = 0
03-19 12:52:28.453   419  1050 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,03-19 12:52:28.453   419  1050 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
03-19 12:52:28.453   419  1050 D DrmWidevineDash: OEMCrypto_OpenSession SID = 1
03-19 12:52:28.453   419  1050 D DrmWidevineDash: OEMCrypto_OpenSession: ends! returns 0
,03-19 12:52:28.453   419  1050 D DrmWidevineDash: OEMCrypto_GetRandom: starts! randomData=0xab397de8, dataLength=8
,03-19 12:52:28.453   419  1050 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,03-19 12:52:28.463  1560  2192 D PhoneApp: EVENT_QUERY_MO_PACKAGES
03-19 12:52:28.463   419  1050 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
03-19 12:52:28.463   419  1050 D DrmWidevineDash: OEMCrypto_GetRandom: ends! returns 0
03-19 12:52:28.463   419  1050 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: starts! SID=1, wrapped_rsa_key=0xab3788a8, wrapped_rsa_key_length=1280
03-19 12:52:28.463   419  1050 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
03-19 12:52:28.463  1624  2106 I Prism.WidgetManager: onLoadItems() -
03-19 12:52:28.463  1624  2106 I Prism.ItemManager: loadItems() com.htc.launcher.pageview.WidgetManager@21be4e74 -
03-19 12:52:28.463  1560  2192 D PhoneApp: -- N1 =0
03-19 12:52:28.463  1560  2192 D PhoneApp: -- N2 =0
03-19 12:52:28.463  1560  2192 D PhoneApp: -- N3 =0
03-19 12:52:28.463   419  1050 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
03-19 12:52:28.463   419  1050 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: ends! returns 0
03-19 12:52:28.463   419  1050 I WVCdm   : CdmEngine::QueryKeyControlInfo
,03-19 12:52:28.463   419  1996 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
03-19 12:52:28.473   419  1996 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
03-19 12:52:28.473   419  1996 I WVCdm   : CdmEngine::GenerateKeyRequest
03-19 12:52:28.473   419  1996 D DrmWidevineDash: OEMCrypto_GetDeviceID: starts! deviceID=0xab3754e8, idLength=0xf498e6f8
03-19 12:52:28.473   419  1996 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
03-19 12:52:28.473   925  1620 W System.err: java.lang.Throwable: stack dump
03-19 12:52:28.473   925  1049 D BluetoothManagerService: Message: MESSAGE_REGISTER_ADAPTER
03-19 12:52:28.473   925  1620 W System.err: 	at java.lang.Thread.dumpStack(Thread.java:490)
03-19 12:52:28.473   925  1620 W System.err: 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
03-19 12:52:28.473   925  1620 W System.err: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
03-19 12:52:28.473   925  1620 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
,03-19 12:52:28.473   925  1049 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2a9dbd8c:true
,03-19 12:52:28.473  3429  3481 D BluetoothAdapter: 102294481: getState() :  mService = null. Returning STATE_OFF
,03-19 12:52:28.493   419  1996 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,03-19 12:52:28.493   419  1996 D DrmWidevineDash: OEMCrypto_GetDeviceID: ends! returns 0
03-19 12:52:28.493   419  1996 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: starts!
03-19 12:52:28.493   419  1996 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
03-19 12:52:28.493   419  1996 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
03-19 12:52:28.493   419  1996 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: is_supported = 1
03-19 12:52:28.493   419  1996 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: wv_app_version = 24
03-19 12:52:28.493   419  1996 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: ends! returns 0
03-19 12:52:28.493   419  1996 D DrmWidevineDash: OEMCrypto_GetHDCPCapability: starts!, current = 0xf498e70e, maximum = 0xf498e70f
03-19 12:52:28.493   419  1996 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
03-19 12:52:28.493   419  1996 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
03-19 12:52:28.493   419  1996 D DrmWidevineDash: OEMCrypto_GetHDCPCapability: ends! returns 0
03-19 12:52:28.493   419  1996 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
03-19 12:52:28.493   419  1996 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
03-19 12:52:28.493   419  1996 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
03-19 12:52:28.493   419  1996 D DrmWidevineDash: hlos api version =  9
03-19 12:52:28.493   419  1996 D DrmWidevineDash: tz api version =  9
03-19 12:52:28.493   419  1996 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 9
03-19 12:52:28.493   419  1996 D DrmWidevineDash: OEMCrypto_GenerateNonce: starts! SID=1, nonce=0xf498e77c
03-19 12:52:28.493   419  1996 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,03-19 12:52:28.493   419  1996 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
03-19 12:52:28.493   419  1996 D DrmWidevineDash: OEMCrypto_GenerateNonce: ends! returns 0
03-19 12:52:28.493   419  1996 D WVCdm   : PrepareKeyRequest: nonce=4280957852
03-19 12:52:28.493   419  1996 D DrmWidevineDash: OEMCrypto_GenerateRSASignature starts! SID=1, message=0xab36f420
03-19 12:52:28.493   419  1996 D DrmWidevineDash: message_length=1642, signature=0xab36fa90, signature_length=0xf498e6dc
03-19 12:52:28.493   419  1996 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,03-19 12:52:28.523   925   974 I ActivityManager: Recipient 1686
,03-19 12:52:28.543   925   925 D BluetoothManagerService: Auto-enabling Bluetooth.
,03-19 12:52:28.553   925   925 D BluetoothManagerService: checking for enable restriction...
03-19 12:52:28.553   925   925 D BluetoothManagerService: checkBTEasState, ret=true
03-19 12:52:28.553   925   925 I BluetoothManagerService: isBluetoothRestricted(): false
03-19 12:52:28.553   925  1049 D BluetoothManagerService: Message: MESSAGE_ENABLE
,03-19 12:52:28.553   925  1049 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
,03-19 12:52:28.553  3235  3302 I Babel   : connection state changed from UNKNOWN to CONNECTED,
,03-19 12:52:28.573   925  1049 I ActivityManager: Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=3489 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 1023, 3005, 1016, 3008} abi=armeabi-v7a
,03-19 12:52:28.573   925  1010 D PMS     : acquireWL(1df51da8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 925 1000 null
03-19 12:52:28.573   925  1617 I ActivityManager: Killing 3031:com.htc.demoflopackageinstaller/u0a16 (adj 15): empty #17
03-19 12:52:28.573   925  1617 D Process : killProcessQuiet, pid=3031
03-19 12:52:28.573   925  1617 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,03-19 12:52:28.603   419  1996 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0,
03-19 12:52:28.603   419  1996 D DrmWidevineDash: OEMCrypto_GenerateRSASignature returns 0
,03-19 12:52:28.603   419   419 I WVCdm   : CdmEngine::CloseSession
03-19 12:52:28.603   419   419 D DrmWidevineDash: OEMCrypto_CloseSession: starts! SID=1
03-19 12:52:28.603   419   419 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
03-19 12:52:28.603   419   419 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
03-19 12:52:28.603   419   419 D DrmWidevineDash: OEMCrypto_CloseSession: ends! returns 0
03-19 12:52:28.603   419   419 I WVCdm   : L3 Terminate.
03-19 12:52:28.603   419   419 D DrmWidevineDash: OEMCrypto_Terminate: starts!
03-19 12:52:28.603   419   419 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
03-19 12:52:28.603   419   419 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
03-19 12:52:28.603   419   419 D DrmWidevineDash: Service_Uninitialize: starts!
,03-19 12:52:28.603   419   419 D QSEECOMAPI: : QSEECom_dealloc_memory 
03-19 12:52:28.603   419   419 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 7
03-19 12:52:28.603   419   419 D DrmWidevineDash: Service_Uninitialize: ends! returns 0x0
03-19 12:52:28.603   419   419 D DrmWidevineDash: OEMCrypto_Terminate: ends! returns 0
,03-19 12:52:28.653   925  1599 I ActivityManager: Recipient 3031
,03-19 12:52:28.683   925   925 D UsbDeviceManager: boot completed
03-19 12:52:28.683   925  1046 D UsbDeviceManager: [USBNET] handleMessage: 4; mConnected=true, mConfiguration=true
,03-19 12:52:28.693   925  1046 D UsbDeviceManager: [USBNET] update2: 105,0,
03-19 12:52:28.693   925  1046 D UsbDeviceManager: sendStickyBroadcast: broadcasting Intent { act=android.hardware.usb.action.USB_STATE flg=0x20000000 (has extras) } connected: true configured: true; SetCurrentFunctions= mtp,mass_storage,adb
,03-19 12:52:28.703   925  3487 I ActivityManager: Start proc com.android.keychain for service com.android.keychain/.KeyChainService: pid=3512 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
,03-19 12:52:28.713  1221  1221 V SystemUIService: BOOT_COMPLETED received
,03-19 12:52:28.723   925  1046 D UsbDeviceManager: [USBNET] handleMessage: 105; mConnected=true, mConfiguration=true
,03-19 12:52:28.723  3489  3489 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
03-19 12:52:28.723   925  1046 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendStickyBroadcast:1626 com.android.server.usb.UsbDeviceManager$UsbHandler.handleMessage:1624 android.os.Handler.dispatchMessage:102 android.os.Looper.loop:155 android.os.HandlerThread.run:61 
,03-19 12:52:28.723   925   925 D UsbnetService: BroadcastReceiver::onReceive+
03-19 12:52:28.723   925  1046 D UsbDeviceManager: [USBNET] sendStickyBroadcast ACTION_USB_CONNECT2PC: 1
03-19 12:52:28.723   925   925 D UsbnetService: onReceive ACTION_USB_STATE: true,false
03-19 12:52:28.723   925  1049 D Tethering: got USB_STATE change: usbConnected=true, mRndisEnabled=false, mUsbTetherRequested=false
03-19 12:52:28.723   925   925 D UsbnetService: BroadcastReceiver::onReceive-
03-19 12:52:28.723   925  1146 D MountService: sharing = 0 
03-19 12:52:28.723   925  1146 D MountService: Unmount PCTOOL.ISO
03-19 12:52:28.723   925  1146 D VoldConnector: SND -> {17 mountISO unmount /system/etc/PCTOOL.ISO /sys/class/android_usb/f_mass_storage/lun0/file}
,03-19 12:52:28.733   925  3502 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
03-19 12:52:28.733   925  1146 D MountService: unmountISO --
,03-19 12:52:28.733   925  1010 D PMS     : acquireWL(28dc6f43): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.drive.sync/com.google/***** 0x1 925 1000 WorkSource{10024}
,03-19 12:52:28.743   925  1010 D PMS     : releaseWL(1df51da8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,03-19 12:52:28.743   925  1010 D PMS     : acquireWL(eb19b5): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 925 1000 null
,03-19 12:52:28.753   925  3535 I RecoverySystem: No recovery log file
,03-19 12:52:28.753   925  1010 D PMS     : releaseWL(eb19b5): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
03-19 12:52:28.753   925  1010 D PMS     : acquireWL(17f40d8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 925 1000 null
,03-19 12:52:28.753   925  1010 D PMS     : releaseWL(17f40d8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
03-19 12:52:28.753   925  1010 D PMS     : acquireWL(28009c31): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 925 1000 null
03-19 12:52:28.753   925  1010 D PMS     : releaseWL(28009c31): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,03-19 12:52:28.763   925   925 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 7
,03-19 12:52:28.763   925   925 E WifiTrafficPoller:  packet count Tx=39 Rx=36
,03-19 12:52:28.773   925  1339 I ActivityManager: Start proc com.futuredial for broadcast com.futuredial/.ui.BootCompletedReceiver: pid=3538 uid=10082 gids={50082, 9997, 3002, 3001} abi=arm64-v8a
,03-19 12:52:28.803  1337  1337 D wpa_supplicant: nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
03-19 12:52:28.803  3538  3538 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,03-19 12:52:28.803  1337  1337 D wpa_supplicant: wlan0: nl80211: New scan results available
,03-19 12:52:28.803  3538  3538 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
03-19 12:52:28.803  1337  1337 D wpa_supplicant: nl80211: Scan included frequencies: 2412 2417 2422 2427 2432 2437 2442 2447 2452 2457 2462 2467 2472 5180 5200 5220 5240 5260 5280 5300 5320 5500 5520 5540 5560 5580 5600 5620 5640 5660 5680 5700
03-19 12:52:28.813  1337  1337 D wpa_supplicant: wlan0: Event SCAN_RESULTS (3) received
03-19 12:52:28.813  1337  1337 I wpa_supplicant: Got an original EVENT_SCAN_RESULTS
03-19 12:52:28.813  1337  1337 D wpa_supplicant: wlan0: Scan completed in 6.724588 seconds
,03-19 12:52:28.813  1337  1337 D wpa_supplicant: nl80211: Associated on 2457 MHz
03-19 12:52:28.813  1337  1337 D wpa_supplicant: nl80211: Associated with f4:f2:6d:22:99:3e
03-19 12:52:28.813   925  1153 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:14146 com.android.server.wifi.WifiStateMachine.handleMediaLinkEvent:14311 com.android.server.wifi.WifiStateMachine.access$6000:268 com.android.server.wifi.WifiStateMachine$SupplicantStartedState.processMessage:8091 
03-19 12:52:28.813  1337  1337 D wpa_supplicant: nl80211: Received scan results (20 BSSes)
03-19 12:52:28.813  1337  1337 D wpa_supplicant: nl80211: Scan results indicate BSS status with f4:f2:6d:22:99:3e as associated
03-19 12:52:28.813  1337  1337 I wpa_supplicant: [NULL] 00:1e:4a:8f:e3:6f freq=5320 level=-53
03-19 12:52:28.813  1337  1337 I wpa_supplicant: [NULL] 00:1e:4a:8f:e3:6b freq=5320 level=-53
03-19 12:52:28.813  1337  1337 I wpa_supplicant: [NULL] f0:f2:6d:22:99:3e freq=2457 level=-52
03-19 12:52:28.813  1337  1337 I wpa_supplicant: [NULL] f4:f2:6d:22:99:3e freq=2457 level=-57
03-19 12:52:28.813  1337  1337 I wpa_supplicant: [NULL] 00:1e:4a:8f:e3:64 freq=2412 level=-57
03-19 12:52:28.813  1337  1337 I wpa_supplicant: [NULL] 00:1e:4a:8f:e3:60 freq=2412 level=-57
03-19 12:52:28.813  1337  1337 I wpa_supplicant: [NULL] 00:1e:4a:8f:e3:62 freq=2412 level=-58
03-19 12:52:28.813  1337  1337 I wpa_supplicant: [NULL] 00:1f:27:54:70:c1 freq=2437 level=-54
03-19 12:52:28.813  1337  1337 I wpa_supplicant: [NULL] 00:1f:27:54:70:c0 freq=2437 level=-61
03-19 12:52:28.813  1337  1337 I wpa_supplicant: [NULL] 00:1f:27:54:dd:eb freq=5240 level=-74
03-19 12:52:28.813  1337  1337 I wpa_supplicant: [NULL] 00:1f:27:54:dd:ef freq=5240 level=-74
03-19 12:52:28.813  1337  1337 I wpa_supplicant: [NULL] 00:1f:27:54:dd:e2 freq=2437 level=-70
03-19 12:52:28.813  1337  1337 I wpa_supplicant: [NULL] 00:1f:27:54:dd:e4 freq=2437 level=-71
03-19 12:52:28.813  1337  1337 I wpa_supplicant: [NULL] 00:22:0d:46:1c:a0 freq=2462 level=-74
03-19 12:52:28.813  1337  1337 I wpa_supplicant: [NULL] 00:1e:4a:8f:df:d0 freq=2437 level=-80
03-19 12:52:28.813  1337  1337 I wpa_supplicant: [NULL] 00:16:a6:1e:e0:a4 freq=2422 level=-82
03-19 12:52:28.813  1337  1337 I wpa_supplicant: [NULL] 00:1e:4a:8f:e3:63 freq=2412 level=-57
03-19 12:52:28.813  1337  1337 I wpa_supplicant: [NULL] 00:1f:27:54:dd:e3 freq=2437 level=-71
03-19 12:52:28.813  1337  1337 I wpa_supplicant: [NULL] 00:22:0d:46:1c:a3 freq=2462 level=-75
03-19 12:52:28.813  1337  1337 I wpa_supplicant: [NULL] 00:1f:27:54:e0:43 freq=2462 level=-78
03-19 12:52:28.813  1337  1337 D wpa_supplicant: wlan0: BSS: Start scan result update 2
03-19 12:52:28.813  1337  1337 D wpa_supplicant: wlan0: BSS: Add new id 10 BSSID 00:1e:4a:8f:e3:6f SSID '\x00'
03-19 12:52:28.813  1337  1337 D wpa_supplicant: wlan0: BSS: Add new id 11 BSSID 00:1e:4a:8f:e3:6b SSID '\x00'
03-19 12:52:28.813  1337  1337 D wpa_supplicant: wlan0: BSS: Add new id 12 BSSID 00:1e:4a:8f:e3:64 SSID '\x00'
03-19 12:52:28.813   925  1664 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 10 00:1e:4a:8f:e3:6f]
03-19 12:52:28.813  1337  1337 D wpa_supplicant: wlan0: BSS: Add new id 13 BSSID 00:1e:4a:8f:e3:60 SSID '\x00'
03-19 12:52:28.813  1337  1337 D wpa_supplicant: wlan0: BSS: Add new id 14 BSSID 00:1e:4a:8f:e3:62 SSID '\x00'
03-19 12:52:28.813  1337  1337 D wpa_supplicant: wlan0: BSS: Add new id 15 BSSID 00:1f:27:54:dd:eb SSID '\x00'
03-19 12:52:28.813   925  1664 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 11 00:1e:4a:8f:e3:6b]
03-19 12:52:28.813  1337  1337 D wpa_supplicant: wlan0: BSS: Add new id 16 BSSID 00:1f:27:54:dd:ef SSID '\x00'
03-19 12:52:28.813  1337  1337 D wpa_supplicant: wlan0: BSS: Add new id 17 BSSID 00:22:0d:46:1c:a0 SSID '\x00'
03-19 12:52:28.813   925  1664 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 12 00:1e:4a:8f:e3:64]
03-19 12:52:28.813  1337  1337 D ,wpa_supplicant: wlan0: BSS: Add new id 18 BSSID 00:1e:4a:8f:df:d0 SSID '\x00'
03-19 12:52:28.813   925  1664 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 13 00:1e:4a:8f:e3:60]
03-19 12:52:28.813  1337  1337 D wpa_supplicant: wlan0: BSS: Add new id 19 BSSID 00:16:a6:1e:e0:a4 SSID ''
03-19 12:52:28.813  1337  1337 D wpa_supplicant: BSS: last_scan_res_used=20/32
03-19 12:52:28.813   925  1664 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 14 00:1e:4a:8f:e3:62]
03-19 12:52:28.813  1337  1337 D wpa_supplicant: wlan0: Scan-only results received
03-19 12:52:28.813   925  1664 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 15 00:1f:27:54:dd:eb]
03-19 12:52:28.813  1337  1337 D wpa_supplicant: wlan0: Radio work 'scan'@0x5597a16860 done in 6.726101 seconds
03-19 12:52:28.813   925  1664 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 16 00:1f:27:54:dd:ef]
03-19 12:52:28.813   925  1664 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 17 00:22:0d:46:1c:a0]
03-19 12:52:28.813   925  1664 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 18 00:1e:4a:8f:df:d0]
03-19 12:52:28.813   925  1664 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 19 00:16:a6:1e:e0:a4]
03-19 12:52:28.813   925  1664 E WifiMonitor: WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
03-19 12:52:28.813   925  1664 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
03-19 12:52:28.813   925  1153 E WifiStateMachine: handleMessage: E msg.what=147461
03-19 12:52:28.813   925  1153 E WifiStateMachine: processMsg: ConnectedState
03-19 12:52:28.813   925  1153 E WifiStateMachine:  ConnectedState !SCAN_RESULTS_EVENT 0 0 found=10 known=1 got=10 bcn=0
03-19 12:52:28.813   925  1153 E WifiStateMachine: processMsg: L2ConnectedState
03-19 12:52:28.813   925  1153 E WifiStateMachine:  L2ConnectedState !SCAN_RESULTS_EVENT 0 0 found=10 known=1 got=10 bcn=0
03-19 12:52:28.813   925  1153 E WifiStateMachine: processMsg: ConnectModeState
03-19 12:52:28.813   925  1153 E WifiStateMachine:  ConnectModeState !SCAN_RESULTS_EVENT 0 0 found=10 known=1 got=10 bcn=0
03-19 12:52:28.813   925  1153 E WifiStateMachine: processMsg: DriverStartedState
03-19 12:52:28.813   925  1153 E WifiStateMachine:  DriverStartedState !SCAN_RESULTS_EVENT 0 0 found=10 known=1 got=10 bcn=0
03-19 12:52:28.813   925  1153 E WifiStateMachine: processMsg: SupplicantStartedState
03-19 12:52:28.813   925  1153 E WifiStateMachine:  SupplicantStartedState !SCAN_RESULTS_EVENT 0 0 found=10 known=1 got=10 bcn=0
03-19 12:52:28.813   925  1153 D WifiStateMachine: [MLHD] enter handleMediaLinkEvent SupplicantStartedState
03-19 12:52:28.813   925  1153 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
03-19 12:52:28.813  1337  1337 D wpa_supplicant: wlan0: Control interface command 'LIST_DONGLES'
03-19 12:52:28.813   925  1153 E WifiStateMachine: [1,458,388,348,820 ms] noteScanEnd no scan source
03-19 12:52:28.813   925  1153 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
03-19 12:52:28.813  1337  1337 D wpa_supplicant: wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
03-19 12:52:28.813   925  1153 E WifiStateMachine: wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@1aba6878 sup_state=COMPLETED debouncing=false
03-19 12:52:28.813   925  1153 E WifiAutoJoinController : NG700_GUEST f0:f2:6d:22:99:3e rssi=-52 cap [WPA2-PSK-CCMP][ESS] is not scored
03-19 12:52:28.813   925  1153 E WifiAutoJoinController : NG700 f4:f2:6d:22:99:3e rssi=-57 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
03-19 12:52:28.813   925  1153 E WifiConfigStore: updateSavedNetworkHistory(): try "NG700"WPA_PSK SSID="NG700" NG700 [WPA2-PSK-CCMP][WPS][ESS] ajst=0
03-19 12:52:28.813   925  1153 E WifiConfigStore: updateSavedNetworkHistory: HTC improve mode
03-19 12:52:28.813   925  1153 E WifiConfigStore:         got known scan result f4:f2:6d:22:99:3e key : "NG700"WPA_PSK num: 1 rssi=-57 freq=2457
03-19 12:52:28.813   925  1153 E WifiAutoJoinController : ktwtestwifi 00:1f:27:54:70:c0 rssi=-61 cap [WPA2-EAP-CCMP+TKIP][ESS] is not scored
03-19 12:52:28.813   925  1153 E WifiAutoJoinController : TEST_KTW01 00:1f:27:54:70:c1 rssi=-54 cap [WPA2-EAP-TKIP][ESS] is not scored
03-19 12:52:28.813   925  1153 E WifiAutoJoinController :  00:1f:27:54:dd:e2 rssi=-70 cap [WPA2-PSK-CCMP][ESS] is not scored
03-19 12:52:28.813   925  1153 E WifiAutoJoinController :  00:1f:27:54:dd:e4 rssi=-71 cap [WPA2-EAP-CCMP][ESS] is not scored
03-19 12:52:28.813   925  1153 E WifiAutoJoinController : RA-WINGS 00:1e:4a:8f:e3:63 rssi=-57 cap [ESS] is not scored
03-19 12:52:28.813   925  1153 E WifiAutoJoinController : RA-WINGS 00:1f:27:54:dd:e3 rssi=-71 cap [ESS] is not scored
03-19 12:52:28.813   925  1153 E WifiAutoJoinController : RA-WINGS 00:22:0d:46:1c:a3 rssi=-75 cap [ESS] is not scored
03-19 12:52:28.813   925  1153 E WifiAutoJoinController : RA-WINGS 00:1f:27:54:e0:43 rssi=-78 cap [ESS] is not scored
03-19 12:52:28.813   925  1153 E WifiAutoJoinController :  00:1e:4a:8f:e3:6f rssi=-53 cap [WPA-EAP-TKIP][WPA2-EAP-CCMP][ESS] is not scored
03-19 12:52:28.813   925  1153 E WifiAutoJoinController :  00:1e:4a:8f:e3:6b rssi=-53 cap [WPA2-EAP-CCMP][ESS] is not scored
03-19 12:52:28.813   925  1153 E WifiAutoJoinController :  00:1e:4a:8f:e3:64 rssi=-57 cap [WPA2-EAP-CCMP][ESS] is not scored
03-19 12:52:28.813   925  1153 E WifiAutoJoinController :  00:1e:4a:8f:e3:60 rssi=-57 cap [WPA-EAP-TKIP][WPA2-EAP-CCMP][ESS] is not scored
03-19 12:52:28.813   925  1153 E WifiAutoJoinController :  00:1e:4a:8f:e3:62 rssi=-58 cap [WPA2-PSK-CCMP][ESS] is not scored
03-19 12:52:28.813   925  1153 E WifiAutoJoinController :  00:1f:27:54:dd:eb rssi=-74 cap [WPA2-EAP-CCMP][ESS] is not scored
03-19 12:52:28.813   925  1153 E WifiAutoJoinController :  00:1f:27:54:dd:ef rssi=-74 cap [WPA-EAP-TKIP][WPA2-EAP-CCMP][ESS] is not scored
03-19 12:52:28.813   925  1153 E WifiAutoJoinController :  00:22:0d:46:1c:a0 rssi=-74 cap [WPA-EAP-TKIP][WPA2-EAP-CCMP][ESS] is not scored
03-19 12:52:28.813   925  1153 E WifiAutoJoinController :  00:1e:4a:8f:df:d0 rssi=-80 cap [WPA-EAP-TKIP][WPA2-EAP-CCMP][ESS] is not scored
03-19 12:52:28.813   925  1153 E WifiAutoJoinController :  00:16:a6:1e:e0:a4 rssi=-82 cap [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS] is not scored
03-19 12:52:28.813   925  1153 E WifiAutoJoinController : ageScanResultsOut delay 40000 size 20 now 1458388348824
03-19 12:52:28.813   925  1153 E WifiAutoJoinController : newSupplicantResults size=20 known=1 true
03-19 12:52:28.813   925  1153 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 STATUS-NO_EVENTS"
03-19 12:52:28.813  1337  1337 D wpa_supplicant: wlan0: Control interface command 'STATUS-NO_EVENTS'
03-19 12:52:28.813   925  1153 E WifiAutoJoinController : attemptAutoJoin() status=bssid=f4:f2:6d:22:99:3e
03-19 12:52:28.813   925  1153 E WifiAutoJoinController : ssid=NG700
03-19 12:52:28.813   925  1153 E WifiAutoJoinController : id=0
03-19 12:52:28.813   925  1153 E WifiAutoJoinController : mode=station
03-19 12:52:28.813   925  1153 E WifiAutoJoinController : pairwise_cipher=CCMP
03-19 12:52:28.813   925  1153 E WifiAutoJoinController : group_cipher=CCMP
03-19 12:52:28.813   925  1153 E WifiAutoJoinController : key_mgmt=WPA2-PSK
03-19 12:52:28.813   925  1153 E WifiAutoJoinController : wpa_state=COMPLETED
03-19 12:52:28.813   925  1153 E WifiAutoJoinController : ip_address=192.168.1.102
03-19 12:52:28.813   925  1153 E WifiAutoJoinController : p2p_device_address=92:e7:c4:e6:4c:f8
03-19 12:52:28.813   925  1153 E WifiAutoJoinController : address=XX:XX:XX:XX:XX:XX
03-19 12:52:28.813   925  1153 E WifiAutoJoinController : uuid=12345678-9abc-def0-1234-56789abcdef1 split=12
03-19 12:52:28.813   925  1153 E WifiAutoJoinController : attemptAutoJoin() num recent config 1 current="NG700"WPA_PSK ---> suppNetId=0
03-19 12:52:28.813   925  1153 E WifiAutoJoinController : attemptAutoJoin good candidate seen, bumped hard -> status=0 "NG700"WPA_PSK rssi=(-57,-127) num=(1,0)
03-19 12:52:28.813   925  1153 E WifiAutoJoinController : attemptAutoJoin skip current candidate  0 key "NG700"WPA_PSK
03-19 12:52:28.813   925  1153 E WifiAutoJoinController : attemptRoam: "NG700"WPA_PSK Found f4:f2:6d:22:99:3e rssi=-57 freq=2457 Current: f4:f2:6d:22:99:3e
03-19 12:52:28.813   925  1153 D HtcWifiControlRoamOffload: : roamCandidate: nullcurrentBSSID: f4:f2:6d:22:99:3e
03-19 12:52:28.813   925  1153 E WifiStateMachine: WiFiDisplay: getWifidisplayApEnabled=false
03-19 12:52:28.813   925  1153 E WifiAutoJoinController : Done attemptAutoJoin status=0
03-19 12:52:28.823   925  1153 E WifiConfigStore:  writeKnownNetworkHistory() num networks:1 needWrite=false
03-19 12:52:28.823   925  1153 E WifiStateMachine: handleMessage: X
03-19 12:52:28.823  1845  1845 D WifiManager: getScanResults: Base Package Name=com.google.android.gms, uid=10024
03-19 12:52:28.833  3429  3429 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-19 12:52:28.833   925  3535 I BootReceiver: Copying /sys/fs/pstore/console-ramoops to DropBox (SYSTEM_LAST_KMSG)
,03-19 12:52:28.853  3429  3429 W AwContents: onDetachedFromWindow called when already detached. Ignoring
03-19 12:52:28.853   925  3561 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
,03-19 12:52:28.893   925  3535 I BootReceiver: Copying audit failures to DropBox,
,03-19 12:52:28.903   925  3561 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
03-19 12:52:28.903   925  3535 I BootReceiver: Copied 0 worth of audits to DropBox
,03-19 12:52:28.913   925  3535 I BootReceiver: Checking for fsck errors,
,03-19 12:52:28.913   925  3535 I BootReceiver: Copying /data/tombstones/tombstone_00 to DropBox (SYSTEM_TOMBSTONE),
03-19 12:52:28.913   925  3561 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
,03-19 12:52:28.933   925  3535 I BootReceiver: Copying /data/tombstones/tombstone_01 to DropBox (SYSTEM_TOMBSTONE),
03-19 12:52:28.933   925  3561 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
,03-19 12:52:28.943   925  3561 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml,
03-19 12:52:28.943   925  3535 I BootReceiver: Copying /data/tombstones/tombstone_02 to DropBox (SYSTEM_TOMBSTONE)
,03-19 12:52:28.953   925  3535 I BootReceiver: Copying /data/tombstones/tombstone_03 to DropBox (SYSTEM_TOMBSTONE)
,03-19 12:52:28.953   925  3561 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
,03-19 12:52:28.963   925  3535 I BootReceiver: Copying /data/tombstones/tombstone_04 to DropBox (SYSTEM_TOMBSTONE)
,03-19 12:52:28.963   925  3561 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
,03-19 12:52:28.983   925  3535 I BootReceiver: Copying /data/tombstones/tombstone_05 to DropBox (SYSTEM_TOMBSTONE)
03-19 12:52:28.983   925  3561 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
,03-19 12:52:28.993   925  3535 I BootReceiver: Copying /data/tombstones/tombstone_06 to DropBox (SYSTEM_TOMBSTONE)
,03-19 12:52:28.993   925  3561 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
,03-19 12:52:29.003   925  1764 D Process : killProcessQuiet, pid=3055
03-19 12:52:29.003   925  1764 I ActivityManager: Killing 3055:com.htc.task/u0a69 (adj 15): empty #17
03-19 12:52:29.003   925  1764 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
03-19 12:52:29.003   925  3535 I BootReceiver: Copying /data/tombstones/tombstone_07 to DropBox (SYSTEM_TOMBSTONE)
03-19 12:52:29.013   925  3561 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
03-19 12:52:29.013  3429  3429 D SystemWebViewEngine: CordovaWebView is running on device made by: HTC
,03-19 12:52:29.023   925  3535 I BootReceiver: Copying /data/tombstones/tombstone_08 to DropBox (SYSTEM_TOMBSTONE)
,03-19 12:52:29.033   925  3561 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml,
,03-19 12:52:29.043   925  3535 I BootReceiver: Copying /data/tombstones/tombstone_09 to DropBox (SYSTEM_TOMBSTONE)
,03-19 12:52:29.043   925  3561 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
,03-19 12:52:29.113   925  1598 I ActivityManager: Recipient 3055
,03-19 12:52:29.113  3489  3489 D AdapterServiceConfig: Adding HeadsetService
,03-19 12:52:29.113  3489  3489 D AdapterServiceConfig: Adding A2dpService
03-19 12:52:29.113  3489  3489 D AdapterServiceConfig: Adding HidService
03-19 12:52:29.113  3489  3489 D AdapterServiceConfig: Adding HealthService
03-19 12:52:29.113  3489  3489 D AdapterServiceConfig: Adding PanService
03-19 12:52:29.113  3489  3489 D AdapterServiceConfig: Adding GattService
,03-19 12:52:29.133  3429  3429 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-19 12:52:29.133  3429  3429 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-19 12:52:29.143  3538  3538 I [FDDMI]BootCompletedReceiver: BootCompletedReceiver :android.intent.action.BOOT_COMPLETED
,03-19 12:52:29.153  3489  3489 W linker  : libbt-aptx-4.1.1.so has text relocations. This is wasting memory and prevents security hardening. Please fix.
,03-19 12:52:29.163   925  1771 W System.err: java.lang.Throwable: stack dump
,03-19 12:52:29.173   925  1049 D BluetoothManagerService: Message: MESSAGE_REGISTER_ADAPTER
03-19 12:52:29.173   925  1771 W System.err: 	at java.lang.Thread.dumpStack(Thread.java:490)
03-19 12:52:29.173   925  1771 W System.err: 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
03-19 12:52:29.173   925  1049 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2f9a7b9e:true
03-19 12:52:29.173   925  1771 W System.err: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
03-19 12:52:29.173   925  1771 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
,03-19 12:52:29.173  3489  3489 D BluetoothAdapterState: make
,03-19 12:52:29.183  1560  1560 D OtaStartupReceiver: onReceive: android.intent.action.BOOT_COMPLETED
,03-19 12:52:29.183  3489  3570 I BluetoothAdapterState: Entering OffState
,03-19 12:52:29.193   925   925 W HtcActiveEngineManager: Can't find out the target sensor
03-19 12:52:29.193   925   925 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 
03-19 12:52:29.193   925  1153 E WifiStateMachine: handleMessage: E msg.what=131206
03-19 12:52:29.203   925  1157 D ConnectivityService: Got NetworkFactory Messenger for WIFI
03-19 12:52:29.193   925  1153 E WifiStateMachine: processMsg: ConnectedState
03-19 12:52:29.203   925  1157 D ConnectivityService: NetworkFactory connected
03-19 12:52:29.193   925  1153 E WifiStateMachine:  ConnectedState !CMD_BOOT_COMPLETED 0 0
03-19 12:52:29.203   925   925 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1473 com.android.server.backup.BackupManagerService.notifyBackupEnabled:10562 com.android.server.backup.BackupManagerService.access$3400:164 com.android.server.backup.BackupManagerService$BootCompleteReceiver.onReceive:10549 android.app.LoadedApk$ReceiverDispatcher$Args.run:950 
03-19 12:52:29.193   925  1153 E WifiStateMachine: processMsg: L2ConnectedState
03-19 12:52:29.203   925   925 D WifiService: updateDevicePolicy Exchange policy allowWifiStatus = 1
03-19 12:52:29.193  3489  3489 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
03-19 12:52:29.203   925   925 D WifiService: updateDevicePolicy Exchange policy allowInternetSharingStatus = 1
03-19 12:52:29.193   925  1153 E WifiStateMachine:  L2ConnectedState !CMD_BOOT_COMPLETED 0 0
,03-19 12:52:29.193   925  1153 E WifiStateMachine: processMsg: ConnectModeState
03-19 12:52:29.193   925  1153 E WifiStateMachine:  ConnectModeState !CMD_BOOT_COMPLETED 0 0
03-19 12:52:29.193   925  1153 E WifiStateMachine: processMsg: DriverStartedState
03-19 12:52:29.193   925  1153 E WifiStateMachine:  DriverStartedState !CMD_BOOT_COMPLETED 0 0
03-19 12:52:29.193   925  1153 E WifiStateMachine: processMsg: SupplicantStartedState
03-19 12:52:29.193   925  1153 E WifiStateMachine:  SupplicantStartedState !CMD_BOOT_COMPLETED 0 0
03-19 12:52:29.193   925  1153 E WifiStateMachine: processMsg: DefaultState
03-19 12:52:29.193   925  1153 E WifiStateMachine:  DefaultState !CMD_BOOT_COMPLETED 0 0
03-19 12:52:29.193   925  1153 E WifiStateMachine: handleMessage: X
03-19 12:52:29.203   925  1153 D WIFI    : got request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] with score 60
03-19 12:52:29.203   925  1153 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
03-19 12:52:29.203   925  1153 D WIFI    : evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] released
03-19 12:52:29.203   925   925 D UsbnetService: BroadcastReceiver::onReceive+
03-19 12:52:29.203   925   925 D UsbnetService: onReceive ACTION_BOOT_COMPLETED
03-19 12:52:29.203   925   925 D UsbnetService: BroadcastReceiver::onReceive-
03-19 12:52:29.203   925  1166 D UsbnetService: UsbnetHandler::handleMessage+:4
03-19 12:52:29.203   925  1166 D UsbnetService: MESSAGE_BOOT_COMPLETED+
03-19 12:52:29.203  3489  3575 D BluetoothAdapterProperties: Address is:90:E7:C4:F6:69:77
03-19 12:52:29.203   925  1166 D UsbnetService: systemReady+
,03-19 12:52:29.223   925   925 I ActivityManager: Start proc com.htc.autobot for broadcast com.htc.autobot/.UsbReceiver: pid=3576 uid=10047 gids={50047, 9997, 3003, 3002, 3001, 5003, 1024} abi=arm64-v8a
,03-19 12:52:29.223   925  1166 D UsbnetService: systemReady-
03-19 12:52:29.223   925   925 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
,03-19 12:52:29.223   925  1049 D BluetoothManagerService: Message: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
03-19 12:52:29.223   925  1049 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
03-19 12:52:29.223   925  1166 D UsbnetService: UsbnetHandler::handleMessage-
03-19 12:52:29.223   925  1157 D ConnectivityService: Got NetworkFactory Messenger for usbnet
03-19 12:52:29.223   925  1157 D ConnectivityService: NetworkFactory connected
03-19 12:52:29.223   925  1166 D usbnet  : got request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] with score 60
03-19 12:52:29.223   925  1166 D usbnet  :   my score=70, my filter=[ Transports:  Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
03-19 12:52:29.223   925  1166 D usbnet  : evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] released
,03-19 12:52:29.223   925  1164 D Process : killProcessQuiet, pid=2764
03-19 12:52:29.223   925  1164 I ActivityManager: Killing 2764:com.htc.sense.browser/u0a9 (adj 15): empty #17
03-19 12:52:29.223   925  1164 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,03-19 12:52:29.233   925  1049 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
03-19 12:52:29.233   925  1049 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 7 receivers.
03-19 12:52:29.233  1577  1612 D BluetoothAdapter: onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@2f333c09
03-19 12:52:29.233  1577  1612 D BluetoothAdapter: onBluetoothServiceUp done
,03-19 12:52:29.233  3489  3510 D BluetoothAdapter: onBluetoothServiceUp: com.android.bluetooth.btservice.AdapterService$AdapterServiceBinder@2d7362f8
03-19 12:52:29.233  3489  3510 D BluetoothAdapter: onBluetoothServiceUp done
,03-19 12:52:29.233  2380  2401 D BluetoothAdapter: onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@14d4e4ba
03-19 12:52:29.233  2380  2401 D BluetoothAdapter: onBluetoothServiceUp done
,03-19 12:52:29.233  1560  2400 D BluetoothAdapter: onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@1120fa96
03-19 12:52:29.233  1560  2400 D BluetoothAdapter: onBluetoothServiceUp done
03-19 12:52:29.233  1221  1905 D BluetoothAdapter: onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@20ea33ac
03-19 12:52:29.233  1221  1905 D BluetoothAdapter: onBluetoothServiceUp done
03-19 12:52:29.233   925  1049 D BluetoothAdapter: onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@21bd3677
03-19 12:52:29.233   925  1049 D BluetoothAdapter: onBluetoothServiceUp done
03-19 12:52:29.233  3429  3448 D BluetoothAdapter: onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@1e728572
03-19 12:52:29.233  3429  3448 D BluetoothAdapter: onBluetoothServiceUp done
,03-19 12:52:29.233   925  1049 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() done
03-19 12:52:29.243  3489  3570 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
03-19 12:52:29.243  3489  3570 D BluetoothAdapterProperties: Setting state to 11
03-19 12:52:29.243  3489  3570 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
03-19 12:52:29.243   925  1617 D BluetoothManagerService: +onBluetoothStateChange prev=10 new=11
03-19 12:52:29.243   925  1049 D BluetoothManagerService: Message: MESSAGE_BLUETOOTH_STATE_CHANGE
03-19 12:52:29.243   925  1049 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
03-19 12:52:29.243   925  1049 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
,03-19 12:52:29.303   925  1620 I ActivityManager: Recipient 2764
,03-19 12:52:29.333  3429  3479 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,03-19 12:52:29.343  3489  3570 D BluetoothBondStateMachine: make
,03-19 12:52:29.343  1221  1699 I IntentController: receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
03-19 12:52:29.343  3489  3489 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
03-19 12:52:29.343  3489  3489 V BluetoothPbapReceiver: ***********state = 11
,03-19 12:52:29.353  3489  3598 I BluetoothBondStateMachine: StableState(): Entering Off State
03-19 12:52:29.353  3489  3570 D BluetoothAdapterService: checkA2dpState: isA2dpSinkEnabled = false
,03-19 12:52:29.353  3489  3570 E BluetoothAdapterService: checkA2dpState: returning
03-19 12:52:29.353  3489  3570 D BluetoothAdapterService: checkHfpState: isHfpClientEnabled = false
03-19 12:52:29.353  3489  3570 E BluetoothAdapterService: checkHfpState: returning
,03-19 12:52:29.373  3489  3570 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,03-19 12:52:29.373   925   925 D BluetoothHeadset: Proxy object connected
03-19 12:52:29.373  1560  1560 D BluetoothHeadset: Proxy object connected
,03-19 12:52:29.373  1221  1221 D BluetoothHeadset: Proxy object connected
,03-19 12:52:29.373  3489  3489 D HeadsetService: Received start request. Starting profile...
03-19 12:52:29.373  1221  1221 I QuickSettingMiniLite: btListener.connect:HEADSET/android.bluetooth.BluetoothHeadset@27e9875
03-19 12:52:29.373  1560  1560 D BluetoothHeadset: Proxy object connected
03-19 12:52:29.383  3489  3489 D HeadsetStateMachine: Version 1.5
03-19 12:52:29.383  3489  3489 D HeadsetStateMachine: make
03-19 12:52:29.383  1560  1560 D BluetoothHeadset: Proxy object connected
03-19 12:52:29.383  1560  1560 D BluetoothPhoneService: BluetoothHeadset onServiceConnected
03-19 12:52:29.383  1560  1560 D BluetoothAdapter: 806164996: getState(). Returning 11
,03-19 12:52:29.383   925   925 D BluetoothAdapter: 810857064: getState(). Returning 11
,03-19 12:52:29.403  1221  1221 I QuickSettingBluetooth: receive.ACTION_STATE_CHANGE:STATE_TURNING_ON
03-19 12:52:29.403  3489  3489 D HeadsetStateMachine: max_hf_connections = 2
,03-19 12:52:29.403  3576  3576 D UsbReceiver: onReceiver android.intent.action.BOOT_COMPLETED
,03-19 12:52:29.403  3429  3429 D FindExtension: FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
,03-19 12:52:29.403  3576  3576 D HtcModeClient: power connected, start service
,03-19 12:52:29.403  3489  3489 D HeadsetPhoneState: listenForPhoneState..for service and signal 
,03-19 12:52:29.413  3576  3576 D Utils   : CMD:getprop ro.htc.htcmode.socket.type
,03-19 12:52:29.423   925  1620 I ActivityManager: Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.powersaver.PowerSaverNotificationReceiver: pid=3603 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a,
03-19 12:52:29.423  3576  3576 I System  : exec(getprop ro.htc.htcmode.socket.type @ com.htc.autobot.util.Utils.systemCmd:34)
,03-19 12:52:29.463  3576  3576 D HtcModeClient: sSocketMode = LocalSocket,
,03-19 12:52:29.463  3576  3625 D HtcModeClient: start the htcmodeservice thread
,03-19 12:52:29.463  3576  3625 D HtcModeClient: initCanAgent
,03-19 12:52:29.473  3576  3625 I CANMesgAgentLocalSocket: CANAgent Id = 0
03-19 12:52:29.473  3576  3625 D HtcModeClient: sense info: version = none, id = 2
03-19 12:52:29.473  1221  1221 D BluetoothAdapter: 349496506: getState(). Returning 11
,03-19 12:52:29.473  1221  1221 I QuickSettingMiniLite: updateLiteState:no connect device!
03-19 12:52:29.483  3576  3625 D HtcModeClient: display info: width = 1080, height = 1776
03-19 12:52:29.483  3576  3625 D HtcModeClient: display info: mode = 10
,03-19 12:52:29.493  2172  3629 W DriveInitializer: Background init thread started
,03-19 12:52:29.523   925  1619 D VoldConnector: SND -> {18 volume mkdirs /storage/ext_sd/Android/data/com.google.android.gms/files/}
,03-19 12:52:29.523   385   665 E Vold    : Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.gms/files/
03-19 12:52:29.523  2172  3629 W ContextImpl: Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.gms/files
,03-19 12:52:29.573   925  1766 I art     : Explicit concurrent mark sweep GC freed 32681(2MB) AllocSpace objects, 53(3MB) LOS objects, 33% free, 16MB/24MB, paused 1.726ms total 163.944ms
,03-19 12:52:29.573  3429  3429 I InputMethodManager: [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@397bdc3, mServedView=org.apache.cordova.engine.SystemWebView{b3f6640 VFEDH.C. .F....I. 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@30a63979
,03-19 12:52:29.583   925   974 I InputMethodManagerService: Disable input method client, pid=1624
03-19 12:52:29.583   925   974 D StatusBarManagerService: swetImeWindowStatus vis=0 backDisposition=0
,03-19 12:52:29.583   925   974 I InputMethodManagerService: Enable input method client, pid=3429
03-19 12:52:29.593  1221  1221 I PhoneStatusBar: setImeWindowStatus(false,false)
03-19 12:52:29.593   925  1620 I ActivityManager: Start proc com.htc.widget.hmsproc3 for broadcast com.htc.htcbtwidget/.BTReceiver: pid=3640 uid=10034 gids={50034, 9997, 3002, 3001} abi=arm64-v8a
,03-19 12:52:29.713   925  1010 D PMS     : acquireWL(2b87e37b): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 925 1000 null
,03-19 12:52:29.723  3576  3576 D HtcModeClient: onStartCommand() action = com.htc.autobot.htcmodeclient.PowerConnected +++,
03-19 12:52:29.723  3576  3576 D HtcModeClient: connectState: BT_TURNON_BYME = false
03-19 12:52:29.723  3576  3576 D HtcModeClient: connectState: CONNECTION_READY = false
,03-19 12:52:29.723  3576  3576 D HtcModeClient: connectState: ENABLE_PROJECTBYAPP = false
03-19 12:52:29.723  3576  3576 D HtcModeClient: connectState: ENTER_PROJECTMODE = false
03-19 12:52:29.723  3576  3576 D HtcModeClient: connectState: PHONE_PULGIN = false
03-19 12:52:29.723  3576  3576 D HtcModeClient: connectState: Force_AWAKE = false
03-19 12:52:29.723  3576  3576 D HtcModeClient: connectState: PHONE_PULGIN = true
03-19 12:52:29.723  3576  3576 D HtcModeClient: connectState: POWERCONNECTED_READY = true
03-19 12:52:29.733   925  1010 D PMS     : releaseWL(2b87e37b): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,03-19 12:52:29.733   925  1051 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +1s785ms
,03-19 12:52:29.743  2172  3629 W DriveInitializer: Background init thread ended
,03-19 12:52:29.743  3489  3489 D HeadsetDualPhoneStateListener_SLOT1: listen phone state by slot:SLOT1  id:-1
03-19 12:52:29.753  2172  3229 I CheckinRequestBuilder: Classify the device as Phone.
,03-19 12:52:29.753  3489  3489 D HeadsetDualPhoneStateListener_SLOT2: listen phone state by slot:SLOT2  id:-100
,03-19 12:52:29.753  3489  3599 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
03-19 12:52:29.753  3429  3429 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3429
,03-19 12:52:29.753  3489  3599 D HeadsetDualPhoneStateListener_SLOT1: listen phone state by slot:SLOT1  id:-1
,03-19 12:52:29.753  3489  3599 D HeadsetDualPhoneStateListener_SLOT2: listen phone state by slot:SLOT2  id:-100
03-19 12:52:29.753  3489  3599 I HeadsetStateMachine: setCurrentDevice, the latest mCurrentDevice is:null
03-19 12:52:29.753  3489  3599 D bt-btif : BTHF: set_current_device
,03-19 12:52:29.763  3489  3489 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@18ff320c
,03-19 12:52:29.763   925   925 D BluetoothA2dp: Proxy object connected,
03-19 12:52:29.763   925  1619 D PMS     : releaseWL(88a77cf): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
03-19 12:52:29.763  3489  3489 D A2dpService: Received start request. Starting profile...
03-19 12:52:29.763  3489  3489 V Avrcp   : make
03-19 12:52:29.763   925   925 D BluetoothAdapter: 810857064: getState(). Returning 11
03-19 12:52:29.763   925   925 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 7
,03-19 12:52:29.763   925   925 E WifiTrafficPoller:  packet count Tx=39 Rx=46
03-19 12:52:29.763   925   925 E WifiTrafficPoller: notifying of data activity 1
03-19 12:52:29.763  1221  1221 D WIFI_ICON: WifiActivity: 1
03-19 12:52:29.773  1221  1221 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,03-19 12:52:29.773  3603  3603 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.powersaver.PowerSaverNotificationReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,03-19 12:52:29.783  1382  1382 W XT9_C   : [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4),
03-19 12:52:29.783  1382  1382 I XT9_C   : [T9_ReleaseBuffer] Reset LDB#0
03-19 12:52:29.783  1382  1382 I XT9_C   : [T9_ReleaseBuffer] Reset LDB#1
03-19 12:52:29.783  1382  1382 D XT9_C   : [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
03-19 12:52:29.783  3489  3489 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,03-19 12:52:29.783  3489  3489 D A2dpStateMachine: make
03-19 12:52:29.793  3489  3489 D bt-btif : btif_av_state_idle_handler event:BTIF_SM_ENTER_EVT flags 0
03-19 12:52:29.793  3640  3640 D HtcBtWidget_BTWidgetProvider: onBTStateChanged() for widget: 
03-19 12:52:29.793  3489  3489 D A2dpService: setA2dpService(): set to: null
,03-19 12:52:29.793  3489  3489 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@18ff320c
03-19 12:52:29.793  3640  3640 D HtcBtWidget_BTWidgetProvider: updateWidget(context) for widget: 
03-19 12:52:29.793  3489  3671 D A2dpStateMachine: Enter Disconnected: -2
,03-19 12:52:29.803  3489  3489 D HidService: Received start request. Starting profile...
,03-19 12:52:29.803  3489  3489 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@18ff320c
03-19 12:52:29.803   925   974 I ActivityManager: Start proc com.htc.calendar for broadcast com.htc.calendar/.AlertReceiver: pid=3676 uid=10010 gids={50010, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,03-19 12:52:29.813  3489  3489 D HealthService: Received start request. Starting profile...,
,03-19 12:52:29.813   925   974 D Process : killProcessQuiet, pid=2851,
03-19 12:52:29.813   925   974 I ActivityManager: Killing 2851:com.google.android.partnersetup/u0a27 (adj 15): empty #17
,03-19 12:52:29.813  3489  3489 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@18ff320c
03-19 12:52:29.813   925   974 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
03-19 12:52:29.813  3489  3489 D PanService: Received start request. Starting profile...
,03-19 12:52:29.823  3603  3672 D PowerSaverNotificationService: updateNotification, mToggle = false
,03-19 12:52:29.833  3489  3489 D PanService: HTC_CUSTOMIZATION_MHS_ENABLE = false
03-19 12:52:29.833  3489  3489 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@18ff320c
,03-19 12:52:29.843  3489  3489 D BtGatt.DebugUtils: handleDebugAction() action=null
03-19 12:52:29.843  3489  3489 D BtGatt.GattService: Received start request. Starting profile...
03-19 12:52:29.843  3489  3489 D BtGatt.GattService: start()
03-19 12:52:29.843  3489  3489 D BtGatt.AdvertiseManager: advertise manager created
,03-19 12:52:29.883  3429  3429 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,03-19 12:52:29.923   925  1374 I ActivityManager: Recipient 2851
,03-19 12:52:30.023   925  1063 D PMS     : releaseHCC(3e53d773): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null,
03-19 12:52:30.023   925  1063 D PMS     : releaseHCC(2b49f630): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,03-19 12:52:30.033  3489  3489 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@18ff320c,
,03-19 12:52:30.033   925   974 I ActivityManager: Killing 3089:com.htc.showme/u0a81 (adj 15): empty #17
03-19 12:52:30.033   925   974 D Process : killProcessQuiet, pid=3089
03-19 12:52:30.033   925   974 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,03-19 12:52:30.043  3676  3676 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,03-19 12:52:30.053  1560  1560 D BluetoothAdapter: 806164996: getState(). Returning 11
03-19 12:52:30.053  1560  1560 W BluetoothHeadset: Proxy not attached to service
,03-19 12:52:30.053  3429  3654 D jxcore_app_log: JniHelper::setJavaVM(0xab34f8f8), pthread_self() = -1402430176
,03-19 12:52:30.063  1560  1560 D BluetoothHeadset: java.lang.Throwable
03-19 12:52:30.063  1560  1560 D BluetoothHeadset: 	,at android.bluetooth.BluetoothHeadset.phoneStateChanged(BluetoothHeadset.java:827)
03-19 12:52:30.063  1560  1560 D BluetoothHeadset: 	at com.android.phone.BluetoothPhoneService.handleQueryPhoneState(BluetoothPhoneService.java:663)
03-19 12:52:30.063  1560  1560 D BluetoothHeadset: 	at com.android.phone.BluetoothPhoneService.access$500(BluetoothPhoneService.java:79)
03-19 12:52:30.063  1560  1560 D BluetoothHeadset: 	at com.android.phone.BluetoothPhoneService$1.handleMessage(BluetoothPhoneService.java:277)
03-19 12:52:30.063  1560  1560 D BluetoothHeadset: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-19 12:52:30.063  1560  1560 D BluetoothHeadset: 	at android.os.Looper.loop(Looper.java:155)
03-19 12:52:30.063  1560  1560 D BluetoothHeadset: ,	,at android.app.ActivityThread.main(ActivityThread.java:5721)
03-19 12:52:30.063  1560  1560 D BluetoothHeadset: 	at java.lang.reflect.Method.invoke(Native Method)
03-19 12:52:30.063  1560  1560 D BluetoothHeadset: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-19 12:52:30.063  1560  1560 D BluetoothHeadset: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
03-19 12:52:30.063  1560  1560 D BluetoothHeadset: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,03-19 12:52:30.063  3429  3654 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
03-19 12:52:30.063  3429  3654 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
03-19 12:52:30.063  3429  3654 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
03-19 12:52:30.063  3429  3654 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
03-19 12:52:30.063  3429  3654 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,03-19 12:52:30.063  3429  3654 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36539db3 added. We now have 1 listener(s)
,03-19 12:52:30.073  3489  3489 I HeadsetPhoneState: updateServiceState service = 0,roam = 0
03-19 12:52:30.073  3489  3489 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,03-19 12:52:30.073  3489  3599 D HeadsetStateMachine: Disconnected process message: 11, size: 0
03-19 12:52:30.073  3489  3599 D HeadsetStateMachine: Disconnected process message: 10, size: 0
03-19 12:52:30.073  3489  3599 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
03-19 12:52:30.073  3489  3599 D HeadsetStateMachine: Disconnected process message: 11, size: 0
,03-19 12:52:30.073  3489  3570 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
,03-19 12:52:30.073  3489  3705 I bt-btu  : btu_task pending for preload complete event
,03-19 12:52:30.083  3489  3570 E bt_vendor: get_bt_soc_type: Failed to get soc type
,03-19 12:52:30.113  3708  3708 I qcom-bluetooth: /system/etc/init.qcom.bt.bluedroid.sh: init.qcom.bt.bluedroid.sh config =  
,03-19 12:52:30.153   925  1598 I ActivityManager: Recipient 3089,
,03-19 12:52:30.183  3715  3715 I qcom-bluetooth: /system/etc/init.qcom.bt.bluedroid.sh: Transport : smd 
,03-19 12:52:30.183  3716  3716 I qcom-bluetooth: /system/etc/init.qcom.bt.bluedroid.sh: ** Bluedroid stack ** 
,03-19 12:52:30.213  3718  3718 I qcom-bluetooth: /system/etc/init.qcom.bt.bluedroid.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,03-19 12:52:30.223  3719  3719 I qcom-bluetooth: /system/etc/init.qcom.bt.bluedroid.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,03-19 12:52:30.223  3720  3720 I qcom-bluetooth: /system/etc/init.qcom.bt.bluedroid.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,03-19 12:52:30.233  3721  3721 I qcom-bluetooth: /system/etc/init.qcom.bt.bluedroid.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,03-19 12:52:30.253   925  1617 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,03-19 12:52:30.253  3429  3654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 90:E7:C4:F6:69:77,
03-19 12:52:30.253  3429  3654 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "90:E7:C4:F6:69:77"
03-19 12:52:30.253  3676  3676 D CalendarApplication: onCreate
03-19 12:52:30.253  3429  3654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
03-19 12:52:30.253  3429  3654 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: ,
,03-19 12:52:30.263  3489  3489 D BluetoothMasReceiver: Bluetooth STATE CHANGED to 11
,03-19 12:52:30.263  3429  3654 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
03-19 12:52:30.263  3429  3654 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
03-19 12:52:30.263  3429  3654 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
03-19 12:52:30.263  3429  3654 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 90:E7:C4:F6:69:77
03-19 12:52:30.263  3429  3654 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
03-19 12:52:30.263  3429  3654 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
03-19 12:52:30.263  3429  3654 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
03-19 12:52:30.263  3429  3654 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
03-19 12:52:30.263  3429  3654 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
03-19 12:52:30.263  3429  3654 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
03-19 12:52:30.263  3429  3654 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,03-19 12:52:30.263  3429  3654 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38591b6e added. We now have 1 listener(s)
03-19 12:52:30.263  3429  3654 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,03-19 12:52:30.263  3489  3489 V BluetoothSapReceiver: SapReceiver onReceive ,
03-19 12:52:30.263  3489  3489 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
03-19 12:52:30.263   925  1155 D WifiService: New client listening to asynchronous messages
03-19 12:52:30.263  3489  3489 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
03-19 12:52:30.263  3489  3489 V BluetoothSapReceiver: startService = false
,03-19 12:52:30.263   925   925 E WifiTrafficPoller: ADD_CLIENT: 8
03-19 12:52:30.263  3429  3654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
,03-19 12:52:30.263  3429  3654 W org.thaliproject.p2p.btconnectorlib.DiscoveryManager: isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
,03-19 12:52:30.273  1799  1799 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
03-19 12:52:30.273  3676  3726 D AlertReceiver: beginStartingService
03-19 12:52:30.273   925  1620 D PMS     : acquireWL(6246055): PARTIAL_WAKE_LOCK  StartingAlertService_5 0x1 3676 10010 null
03-19 12:52:30.273  3429  3654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
03-19 12:52:30.273  3429  3654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
03-19 12:52:30.273  3429  3654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
03-19 12:52:30.273  3429  3654 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,03-19 12:52:30.273   925  1164 D PMS     : acquireWL(9951a6a): PARTIAL_WAKE_LOCK  CalendarReceiverProvider_5 0x1 2131 10011 null
03-19 12:52:30.273  3429  3654 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-19 12:52:30.283   925  1769 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,03-19 12:52:30.283   925  1010 D PMS     : acquireWL(3049b237): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 925 1000 null
,03-19 12:52:30.283  3429  3654 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 90:E7:C4:F6:69:77
,03-19 12:52:30.283   925  1010 D PMS     : releaseWL(28dc6f43): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.drive.sync/com.google/***** 0x1 WorkSource{10024}
,03-19 12:52:30.283   925  1010 D PMS     : releaseWL(3049b237): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,03-19 12:52:30.283  3429  3654 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
03-19 12:52:30.283  3429  3654 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-19 12:52:30.283  3429  3654 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-19 12:52:30.283  3429  3654 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
03-19 12:52:30.283  3429  3654 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-19 12:52:30.283  3429  3654 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
03-19 12:52:30.283  3429  3654 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-19 12:52:30.283  3429  3654 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-19 12:52:30.283  3429  3654 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
03-19 12:52:30.283  3429  3654 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
03-19 12:52:30.283  3429  3654 D io.jxcore.node.ConnectivityMonitor: start: OK
03-19 12:52:30.293  3429  3654 I io.jxcore.node.LifeCycleMonitor: start: OK
,03-19 12:52:30.293  3429  3429 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-19 12:52:30.293  3429  3429 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-19 12:52:30.293   925  1619 D PMS     : releaseWL(9951a6a): PARTIAL_WAKE_LOCK  CalendarReceiverProvider_5 0x1 null,
,03-19 12:52:30.323  1799  1920 I art     : Explicit concurrent mark sweep GC freed 17567(1047KB) AllocSpace objects, 5(292KB) LOS objects, 33% free, 3MB/5MB, paused 575us total 43.850ms
,03-19 12:52:30.323  3429  3429 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,03-19 12:52:30.333   925  1766 I ActivityManager: Start proc com.htc.demoflopackageinstaller for broadcast com.htc.demoflopackageinstaller/.PIReceiver: pid=3731 uid=10016 gids={50016, 9997, 3003, 1028, 1015} abi=arm64-v8a
03-19 12:52:30.333  3676  3728 D HtcAlertService: start to updateAlertNotification!
03-19 12:52:30.333  1710  3730 W CustomizationIntentService: failed at default contact creation!
03-19 12:52:30.333  1710  3730 W CustomizationIntentService: java.lang.SecurityException: Requesting code from com.htc.contacts (with uid 10038) to be run in process android.process.acore (with uid 10013)
03-19 12:52:30.333  1710  3730 W CustomizationIntentService: 	at android.app.ActivityThread.getPackageInfo(ActivityThread.java:1793)
03-19 12:52:30.333  1710  3730 W CustomizationIntentService: 	at android.app.ActivityThread.getPackageInfo(ActivityThread.java:1768)
03-19 12:52:30.333  1710  3730 W CustomizationIntentService: 	at android.app.ContextImpl.createPackageContextAsUser(ContextImpl.java:2266)
03-19 12:52:30.333  1710  3730 W CustomizationIntentService: 	at android.app.ContextImpl.createPackageContext(ContextImpl.java:2253)
03-19 12:52:30.333  1710  3730 W CustomizationIntentService: 	at android.content.ContextWrapper.createPackageContext(ContextWrapper.java:658)
03-19 12:52:30.333  1710  3730 W CustomizationIntentService: 	at com.android.providers.contacts.HtcUtils.customization.CustomizationIntentService.handleIntentInternal(CustomizationIntentService.java:143)
03-19 12:52:30.333  1710  3730 W CustomizationIntentService: 	at com.android.providers.contacts.HtcUtils.customization.CustomizationIntentService.onHandleIntent(CustomizationIntentService.java:104)
03-19 12:52:30.333  1710  3730 W CustomizationIntentService: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-19 12:52:30.333  1710  3730 W CustomizationIntentService: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-19 12:52:30.333  1710  3730 W CustomizationIntentService: 	at android.os.Looper.loop(Looper.java:155)
03-19 12:52:30.333  1710  3730 W CustomizationIntentService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-19 12:52:30.333  1710  3730 W CustomizationIntentService: handleIntentInternal(): action = com.htc.intent.action.PRELOAD_CONTACTS, original action = android.intent.action.BOOT_COMPLETED, launched by: null,
03-19 12:52:30.333  1710  3730 W CustomizationIntentService: AFH Enable: false, LEONCHAME: false
,03-19 12:52:30.343  1710  3730 W CustomizationIntentService: hasBeenInit true
03-19 12:52:30.343  1710  3730 W CustomizationIntentService: isNewChameleonHFASupported false
03-19 12:52:30.343  1710  3730 W CustomizationIntentService: isHFA true
03-19 12:52:30.343  1710  3730 W CustomizationIntentService: setupWizRun 1
,03-19 12:52:30.363  3676  3728 D HtcAlertService: No fired or scheduled alerts
,03-19 12:52:30.363  3676  3728 D HtcAlertUtils: -- cancelReminderNotification --
03-19 12:52:30.363  3676  3728 D HtcAlertUtils: broadcastExistReminder!
,03-19 12:52:30.373  1298  1298 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false,
03-19 12:52:30.373   925  1598 D PMS     : releaseWL(6246055): PARTIAL_WAKE_LOCK  StartingAlertService_5 0x1 null
03-19 12:52:30.373  3676  3728 W AlertReceiver: stopSelfResult true
,03-19 12:52:30.373   925   982 D Process : killProcessQuiet, pid=3130,
,03-19 12:52:30.373   925   982 I ActivityManager: Killing 3130:com.google.android.music:main/u0a159 (adj 15): empty #17
03-19 12:52:30.373   925   982 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
03-19 12:52:30.383  3731  3731 D DFPI.PIReciver: onReceiver action:android.intent.action.BOOT_COMPLETED
,03-19 12:52:30.383  3731  3731 D DFPI    : getInstance = com.htc.demoflopackageinstaller.ApkInstallHelper@36069612
,03-19 12:52:30.403  3731  3731 D DFPI    : set install APK prefrence is false
,03-19 12:52:30.493   925   974 I ActivityManager: Recipient 3130,
03-19 12:52:30.493   925  1339 D MediaRouterService: Client com.google.android.music (pid 3130): Died!
,03-19 12:52:30.493  3754  3754 I qcom-bluetooth: /system/etc/init.qcom.bt.bluedroid.sh: = Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 90:e7:c4:f6:69:77 
,03-19 12:52:30.503  3755  3755 I qcom-bluetooth: /system/etc/init.qcom.bt.bluedroid.sh: ** Bluedroid stack ** 
,03-19 12:52:30.543  3489  3705 I bt-btu  : btu_task received preload complete event,
03-19 12:52:30.543  3489  3705 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
03-19 12:52:30.543  3489  3705 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
,03-19 12:52:30.543  3489  3705 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
03-19 12:52:30.543  3489  3705 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x1487
,03-19 12:52:30.553   925  1164 D PMS     : acquireWL(1af08610): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 3489 1002 null,
03-19 12:52:30.553  3489  3705 D bt-btm  : btm_acl_device_down
,03-19 12:52:30.553  3489  3705 D bt-btm  : btm_acl_reset_paging
03-19 12:52:30.553  3489  3705 D bt-btm  : btm_acl_set_discing
,03-19 12:52:30.623  3489  3705 I bt-btm  : btm_reset_complete
,03-19 12:52:30.623   925  1598 I ActivityManager: Killing 3194:com.google.android.setupwizard/u0a77 (adj 15): empty #17
03-19 12:52:30.623   925  1598 D Process : killProcessQuiet, pid=3194
03-19 12:52:30.623  3489  3705 I bt-btm  : BTM_SetPinType: pin type 0 [variable-0, fixed-1], code , length 0
03-19 12:52:30.623   925  1598 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
03-19 12:52:30.623  3489  3705 D bt-btm  : Start reading local supported commands
,03-19 12:52:30.633  3489  3705 D bt-btm  : btm_read_local_supported_cmds_complete status (0x00)
03-19 12:52:30.633  3489  3705 D bt-btm  : BTM reads next extended features page (1)
,03-19 12:52:30.633  3489  3705 D bt-btm  : BTM reads next extended features page (2)
,03-19 12:52:30.643  3489  3705 D bt-btm  : BTM reached last extended features page (2)
03-19 12:52:30.643  3489  3705 D bt-btm  : btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x3f
,03-19 12:52:30.643  3489  3705 D bt-btm  : btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x3d
,03-19 12:52:30.643  3489  3705 D bt-btm  : btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x31
03-19 12:52:30.643  3489  3705 I bt-btm  : BTM: BTM_VendorSpecificCommand: Opcode: 0xFD53, ParamLen: 0.
,03-19 12:52:30.643  3489  3705 D bt-btm  : btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x11
,03-19 12:52:30.643  3489  3705 I bt-btm  : btm_vendor_capability_vsc_cmpl_cback: status=0
03-19 12:52:30.643  3489  3705 D bt-btm  : btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x01
,03-19 12:52:30.653  3489  3705 D bt-btm  : btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x00
03-19 12:52:30.653  3489  3705 D bt-btm  : btm_read_ble_wl_size 
,03-19 12:52:30.653  3489  3705 D bt-btm  : btm_read_white_list_size_complete 
03-19 12:52:30.653  3489  3705 D bt-btm  : btm_get_ble_buffer_size 
03-19 12:52:30.653  2172  3229 D libc    : [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
03-19 12:52:30.653  2172  3229 D libc    : [NET] android_getaddrinfofornet-, err=8
,03-19 12:52:30.653  2172  3229 D libc    : [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
03-19 12:52:30.653  2172  3229 D libc    : [NET] android_getaddrinfofornet-, pass to proxy
03-19 12:52:30.653  2172  3229 D libc    : [NET] android_getaddrinfo_proxy+
03-19 12:52:30.653  3489  3705 D bt-btm  : btm_read_ble_buf_size_complete 
03-19 12:52:30.653  3489  3705 D bt-btm  : btm_read_ble_local_supported_states 
03-19 12:52:30.653  2172  3229 D libc    : [NET] android_getaddrinfo_proxy get netid:0
03-19 12:52:30.653   412  3761 D libc    : [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
,03-19 12:52:30.653   412  3761 D libc    : [NET] _dns_getaddrinfo+, netid:100, mark:917604
,03-19 12:52:30.653  3489  3705 D bt-btm  : btm_read_ble_local_supported_states_complete 
03-19 12:52:30.653  3489  3705 D bt-btm  : btm_read_ble_local_supported_features 
,03-19 12:52:30.663  3489  3705 D bt-btm  : btm_read_ble_local_supported_features_complete ,
03-19 12:52:30.663  3489  3705 D bt-btm  : btm_reset_ctrlr_complete: max_page_number: 2
03-19 12:52:30.663  3489  3705 D bt-btm  : btm_decode_ext_features_page page: 0
03-19 12:52:30.663  3489  3705 D bt-btm  : Local supported ACL packet types: 0xcc18
03-19 12:52:30.663  3489  3705 D bt-btm  : Local supported SCO packet types: 0x038f
03-19 12:52:30.663  3489  3705 I bt-btm  : BTM_SEC_REG[2]: id 42, is_orig 0, psm 0x0003, proto_id 3, chan_id 0
03-19 12:52:30.663  3489  3705 I bt-btm  :                : sec: 0x80, service name [RFC_MUX] (up to 21 chars saved)
03-19 12:52:30.663  3489  3705 D bt-btm  : btm_sec_dev_reset sec mode: 4
03-19 12:52:30.663  3489  3705 I bt-btm  : BTM_SetInquiryMode
03-19 12:52:30.663  3489  3705 I bt-btm  : BTM_SetPageScanType
03-19 12:52:30.663  3489  3705 I bt-btm  : BTM_SetInquiryScanType
03-19 12:52:30.663  3489  3705 D bt-btm  : btm_decode_ext_features_page page: 1
03-19 12:52:30.663  3489  3705 W bt-btm  : btm_decode_ext_features_page Secure conn Host support Enabled
03-19 12:52:30.663  3489  3705 D bt-btm  : btm_decode_ext_features_page page: 2
03-19 12:52:30.663  3489  3705 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
03-19 12:52:30.663  3489  3705 D bt-btm  : BTM_BleLoadLocalKeys
03-19 12:52:30.663  3489  3705 D bt-btm  : BTM_BleLoadLocalKeys
03-19 12:52:30.663  3489  3705 I bt-btm  : BTM_Sec: application registered
03-19 12:52:30.663  3489  3705 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xdf6cc4d5 
03-19 12:52:30.663  3489  3705 I bt-btm  : BTM_Sec: SMP_Register( btm_proc_smp_cback )
03-19 12:52:30.663  3489  3705 I bt-smp  : SMP_Register state=0,
03-19 12:52:30.663  3489  3705 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xdf6cc4d5 
03-19 12:52:30.663  3489  3705 I bt-btm  : BTM_Sec: application registered,
03-19 12:52:30.663  3489  3705 D bt-btm  : BTM_SetDefaultLinkSuperTout
03-19 12:52:30.663  3489  3705 I bt-btm  : BTM: BTM_WritePageTimeout: Timeout: 8192.
03-19 12:52:30.663  3489  3705 D bt-btm  : BTM_SetDefaultLinkPolicy setting:0x000f
03-19 12:52:30.663  3489  3705 D bt-btm  : BTM_SetDefaultLinkPolicy park not supported (settings: 0x0007)
03-19 12:52:30.663  3489  3705 D bt-btm  : Set DefaultLinkPolicy:0x0007
03-19 12:52:30.663  3489  3705 D bt-btm  : BTM_RegBusyLevelNotif
03-19 12:52:30.663  3489  3705 D bt-btm  : BTM_BleReadControllerFeatures
03-19 12:52:30.663  3489  3705 I bt-btm  : BTM: BTM_VendorSpecificCommand: Opcode: 0xFD53, ParamLen: 0.
03-19 12:52:30.663  3489  3705 I bt-att  : GATT_Register
03-19 12:52:30.663  3489  3705 D bt-att  : UUID=[0x87878787878787878787878787878787]
03-19 12:52:30.663  3489  3705 I bt-att  : allocated gatt_if=3
03-19 12:52:30.663  3489  3705 I bt-att  : GATT_StartIf gatt_if=3
03-19 12:52:30.663  3489  3705 D bt-att  : gatt_find_the_connected_bda start_idx=0
03-19 12:52:30.663  3489  3705 D bt-att  : gatt_find_the_connected_bda found=0 found_idx=16
03-19 12:52:30.673  3489  3705 D bt-btm  : btm_ble_vendor_capability_vsc_cmpl_cback
03-19 12:52:30.673  3489  3705 D bt-btm  : btm_ble_vnd_cap_vsc_cmpl_cback: stat=0, irk=0, ADV ins:10, rpa=1, ener=1
03-19 12:52:30.673  3489  3705 I bt-btm  : BTM Register For VSEvents is successfully
03-19 12:52:30.673  3489  3575 D bt-btm  : BTM_BleGetVendorCapabilities
03-19 12:52:30.673  3489  3575 I bt-btif : HAL bt_hal_cbacks->adapter_properties_cb
03-19 12:52:30.673  3489  3575 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 0 mOffloadedScanResultStorageBytes= 0 mIsActivityAndEnergyReporting = true
03-19 12:52:30.673  3489  3705 D bt-btm  : bta_dm_set_dev_name: name: HTC One M8s 
03-19 12:52:30.673  3489  3575 E bt-btif : Calling BTA_HhEnable
03-19 12:52:30.673  3489  3575 I bt-btif : BTA_MceEnable
03-19 12:52:30.673  3489  3705 I bt-btm  : Write Extended Inquiry Response to controller
03-19 12:52:30.673  3489  3705 I bt-btm  :  BTM_BleConfigPrivacy
03-19 12:52:30.673  3489  3705 I bt-btm  : btm_gen_resolvable_private_addr
03-19 12:52:30.673  3489  3705 I bt-btm  : btm_gen_resolvable_private_addr
,03-19 12:52:30.673  3489  3705 I bt-btm  : btm_gen_resolvable_private_addr
03-19 12:52:30.673  3489  3705 I bt-btm  : btm_gen_resolvable_private_addr
03-19 12:52:30.673  3489  3705 I bt-btm  : btm_gen_resolvable_private_addr
03-19 12:52:30.673  3489  3705 I bt-btm  : btm_gen_resolvable_private_addr
03-19 12:52:30.673  3489  3705 I bt-btm  : btm_gen_resolvable_private_addr
03-19 12:52:30.673  3489  3705 I bt-btm  : btm_gen_resolvable_private_addr
03-19 12:52:30.673  3489  3705 I bt-btm  : btm_gen_resolvable_private_addr
03-19 12:52:30.673  3489  3705 I bt-btm  : btm_gen_resolvable_private_addr
03-19 12:52:30.673  3489  3705 I bt-btm  : BTM: BTM_WriteVoiceSettings: Settings: 0x0060.
03-19 12:52:30.673  3489  3705 D bt-btif : AG evt (hdl 0x0001): State 0, Event 0x0500
03-19 12:52:30.673  3489  3705 D bt-sdp  : SDP_CreateRecord ok, num_records:3
03-19 12:52:30.673  3489  3705 D bt-btm  : BTM_AllocateSCN
03-19 12:52:30.673  3489  3705 I bt-btm  : Write Extended Inquiry Response to controller
03-19 12:52:30.673  3489  3705 D bt-sdp  : SDP_CreateRecord ok, num_records:4
03-19 12:52:30.673  3489  3705 D bt-btm  : BTM_AllocateSCN
03-19 12:52:30.673  3489  3705 I bt-btm  : Write Extended Inquiry Response to controller
03-19 12:52:30.673  3489  3705 I bt-btm  : BTM_SEC_REG[3]: id 12, is_orig 0, psm 0x0003, proto_id 3, chan_id 2
03-19 12:52:30.673  3489  3705 I bt-btm  :                : sec: 0x1086, service name [] (up to 21 chars saved)
03-19 12:52:30.673  3489  3705 I bt-btm  : BTM_SEC_REG[4]: id 29, is_orig 0, psm 0x0003, proto_id 3, chan_id 3
03-19 12:52:30.673  3489  3705 I bt-btm  : btif_storage_get_adapter_property service_mask:0x214004 chars saved)
03-19 12:52:30.673  3489  3575 E bt-btif : btif_storage_get_adapter_property service_mask:0x214004 chars saved)
03-19 12:52:30.673  3489  3575 I bt-btif : HAL bt_hal_cbacks->adapter_properties_cb
03-19 12:52:30.673  3489  3705 D bt-btif : AG evt (hdl 0x0002): State 0, Event 0x0500
03-19 12:52:30.673  3489  3705 I bt-btm  : BTM_SEC_REG[3]: id 12, is_orig 0, psm 0x0003, proto_id 3, chan_id 2
03-19 12:52:30.673  3489  3705 I bt-btm  :                : sec: 0x1086, service name [] (up to 21 chars saved)
03-19 12:52:30.673  3489  3705 I bt-btm  : BTM_SEC_REG[4]: id 29, is_orig 0, psm 0x0003, proto_id 3, chan_id 3
03-19 12:52:30.673  3489  3705 I bt-btm  :                : sec: 0x1086, service name [] (up to 21 chars saved)
03-19 12:52:30.673  3489  3705 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
03-19 12:52:30.673  3489  3705 I bt-btm  : BTM_SEC_REG[5]: id 37, is_orig 1, psm 0x0019, proto_id 7, chan_id 0
03-19 12:52:30.673  3489  3705 I bt-btm  :                : sec: 0x2090, service name [] (up to 21 chars saved)
03-19 12:52:30.673  3489  3705 I bt-btm  : BTM_SEC_REG[5]: id 37, is_orig 0, psm 0x0019, proto_id 7, chan_id 0
03-19 12:52:30.673  3489  3705 I bt-btm  :                : sec: 0x3092, service name [] (up to 21 chars saved)
03-19 12:52:30.673  3489  3705 I bt-btm  : BTM_SEC_REG[6]: id 38, is_orig 1, psm 0x0019, proto_id 7, chan_id 1
03-19 12:52:30.673  3489  3705 I bt-btm  :                : sec: 0x80, service name [] (up to 21 chars saved)
03-19 12:52:30.673  3489  3705 I bt-btm  : BTM_SEC_REG[6]: id 38, is_orig 0, psm 0x0019, proto_id 7, chan_id 1
03-19 12:52:30.673  3489  3705 I bt-btm  :                : sec: 0x80, service name [] (up to 21 chars saved)
03-19 12:52:30.673  3489  3705 I bt-btm  : BTM_SEC_REG[6]: id 38, is_orig 1, psm 0x0019, proto_id 7, chan_id 2
03-19 12:52:30.673  3489  3705 I bt-btm  :                : sec: 0x80, service name [] (up to 21 chars saved)
03-19 12:52:30.673  3489  3705 I bt-btm  : BTM_SEC_REG[6]: id 38, is_orig 0, psm 0x0019, proto_id 7, chan_id 2
03-19 12:52:30.673  3489  3705 I bt-btm  :                : sec: 0x80, service name [] (up to 21 chars saved)
03-19 12:52:30.673  3489  3705 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
03-19 12:52:30.673  3489  3705 I bt-btm  : BTM_SEC_REG[7]: id 39, is_orig 1, psm 0x0017, proto_id 0, chan_id 0
03-19 12:52:30.673  3489  3705 ,I bt-btm  :                : sec: 0x2090, service name [] (up to 21 chars saved)
03-19 12:52:30.673  3489  3705 I bt-btm  : BTM_SEC_REG[7]: id 39, is_orig 0, psm 0x0017, proto_id 0, chan_id 0
03-19 12:52:30.673  3489  3705 I bt-btm  :                : sec: 0x3092, service name [] (up to 21 chars saved)
03-19 12:52:30.673  3489  3705 D bt-sdp  : SDP_CreateRecord ok, num_records:5
03-19 12:52:30.673  3489  3705 I bt-avp  : AVRC_AddRecord uuid: 110c
03-19 12:52:30.673  3489  3575 D BluetoothAdapterProperties: Address is:90:E7:C4:F6:69:77
03-19 12:52:30.673  3489  3705 I bt-btm  : Write Extended Inquiry Response to controller
03-19 12:52:30.673  3489  3705 D bt-sdp  : SDP_CreateRecord ok, num_records:6
03-19 12:52:30.673  3489  3705 I bt-a2d  : A2D_AddRecord uuid: 110a
03-19 12:52:30.673  3489  3705 I bt-btm  : Write Extended Inquiry Response to controller
03-19 12:52:30.673  3489  3705 D bt-btif :  AVRC_Open AVRC_Open role: 1, control:3 status:0, handle:0
03-19 12:52:30.673  3489  3705 D bt-sdp  : SDP_CreateRecord ok, num_records:7
03-19 12:52:30.673  3489  3705 I bt-avp  : AVRC_AddRecord uuid: 110e
03-19 12:52:30.673  3489  3705 I bt-btm  : Write Extended Inquiry Response to controller
03-19 12:52:30.673  3489  3705 I bt-btm  : BTM_SEC_REG[8]: id 32, is_orig 0, psm 0x0011, proto_id 6, chan_id 1
03-19 12:52:30.673  3489  3705 I bt-btm  :                : sec: 0x86, service name [] (up to 21 chars saved)
03-19 12:52:30.673  3489  3705 I bt-btm  : BTM_SEC_REG[8]: id 32, is_orig 1, psm 0x0011, proto_id 6, chan_id 1
03-19 12:52:30.673  3489  3705 I bt-btm  :                : sec: 0xb6, service name [] (up to 21 chars saved)
03-19 12:52:30.673  3489  3705 I bt-btm  : BTM_SEC_REG[9]: id 33, is_orig 0, psm 0x0011, proto_id 6, chan_id 2
03-19 12:52:30.673  3489  3705 I bt-btm  :                : sec: 0x80, service name [] (up to 21 chars saved)
03-19 12:52:30.673  3489  3705 I bt-btm  : BTM_SEC_REG[9]: id 33, is_orig 1, psm 0x0011, proto_id 6, chan_id 2
03-19 12:52:30.673  3489  3705 I bt-btm  :                : sec: 0x80, service name [] (up to 21 chars saved)
03-19 12:52:30.673  3489  3705 I bt-btm  : BTM_SEC_REG[10]: id 34, is_orig 1, psm 0x0013, proto_id 6, chan_id 0
03-19 12:52:30.673  3489  3705 I bt-btm  :                : sec: 0x80, service name [] (up to 21 chars saved)
03-19 12:52:30.673  3489  3705 I bt-btm  : BTM_SEC_REG[10]: id 34, is_orig 0, psm 0x0013, proto_id 6, chan_id 0
03-19 12:52:30.673  3489  3705 I bt-btm  :                : sec: 0x80, service name [] (up to 21 chars saved)
03-19 12:52:30.673  3489  3705 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
03-19 12:52:30.673  3489  3705 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
03-19 12:52:30.673  3489  3705 I bt-att  : GATT_Register
03-19 12:52:30.673  3489  3705 D bt-att  : UUID=[0x0000454c205245564f20484820415442]
03-19 12:52:30.673  3489  3705 I bt-att  : allocated gatt_if=4
03-19 12:52:30.673  3489  3705 I bt-att  : GATT_StartIf gatt_if=4
03-19 12:52:30.673  3489  3705 D bt-att  : gatt_find_the_connected_bda start_idx=0
03-19 12:52:30.673  3489  3705 D bt-att  : gatt_find_the_connected_bda found=0 found_idx=16
03-19 12:52:30.683  3489  3705 D bt-btm  : btm_ble_rand_enc_complete
03-19 12:52:30.683  3489  3705 I bt-btm  : btm_gen_resolve_paddr_low
03-19 12:52:30.683  3489  3705 D bt-smp  : smp_encrypt_data
03-19 12:52:30.683  3489  3705 W bt-smp  : Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
03-19 12:52:30.683  3489  3705 W bt-smp  : Plain text(LSB ~ MSB) = 99 db 7f 00 00 00 00 00 00 00 00 00 00 00 00 00 
03-19 12:52:30.683  3489  3705 W bt-smp  : Encrypted text(LSB ~ MSB) = 01 17 63 70 70 1c 6f 8d 85 07 7e 7c 05 5e 5e 05 
03-19 12:52:30.683  3489  3705 I bt-btm  : btm_gen_resolve_paddr_cmpl
03-19 12:52:30.683  3489  3705 W bt-btm  : Stopping oneshot timer
03-19 12:52:30.683  3489  3705 D bt-btm  : Starting oneshot timer type:103 timeout:900s
,03-19 12:52:30.683  3489  3705 D bt-btm  : btm_ble_rand_enc_complete
03-19 12:52:30.683  3489  3705 I bt-btm  : btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
03-19 12:52:30.683  3489  3705 D bt-smp  : smp_encrypt_data
03-19 12:52:30.683  3489  3705 W bt-smp  : Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
03-19 12:52:30.683  3489  3705 W bt-smp  : Plain text(LSB ~ MSB) = ac 11 59 00 00 00 00 00 00 00 00 00 00 00 00 00 
03-19 12:52:30.683  3489  3705 W bt-smp  : Encrypted text(LSB ~ MSB) = ea 5c 27 f6 e8 b7 95 52 2a 71 d7 5f ce 5a 10 8e 
,03-19 12:52:30.693  3489  3705 D bt-btm  : btm_ble_rand_enc_complete
,03-19 12:52:30.693  3489  3705 I bt-btm  : btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
03-19 12:52:30.693  3489  3705 D bt-smp  : smp_encrypt_data
03-19 12:52:30.693  3489  3705 W bt-smp  : Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
03-19 12:52:30.693  3489  3705 W bt-smp  : Plain text(LSB ~ MSB) = 8b c4 41 00 00 00 00 00 00 00 00 00 00 00 00 00 
03-19 12:52:30.693  3489  3705 W bt-smp  : Encrypted text(LSB ~ MSB) = 1a 31 6f 3c f3 1d a2 f5 af 50 50 fb 6c ca 99 c9 
,03-19 12:52:30.703  3489  3705 D bt-btm  : btm_ble_rand_enc_complete
03-19 12:52:30.703  3489  3705 I bt-btm  : btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
03-19 12:52:30.703  3489  3705 D bt-smp  : smp_encrypt_data
03-19 12:52:30.703  3489  3705 W bt-smp  : Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
03-19 12:52:30.703  3489  3705 W bt-smp  : Plain text(LSB ~ MSB) = 34 20 79 00 00 00 00 00 00 00 00 00 00 00 00 00 
03-19 12:52:30.703  3489  3705 W bt-smp  : Encrypted text(LSB ~ MSB) = 6a ef e2 22 cf 5d dd 08 f4 a0 37 2d 95 31 77 95 
,03-19 12:52:30.703  3489  3705 D bt-btm  : btm_ble_rand_enc_complete
,03-19 12:52:30.703  3489  3705 I bt-btm  : btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
03-19 12:52:30.703  3489  3705 D bt-smp  : smp_encrypt_data
03-19 12:52:30.703  3489  3705 W bt-smp  : Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
03-19 12:52:30.703  3489  3705 W bt-smp  : Plain text(LSB ~ MSB) = 0d e2 53 00 00 00 00 00 00 00 00 00 00 00 00 00 
03-19 12:52:30.703  3489  3705 W bt-smp  : Encrypted text(LSB ~ MSB) = f8 cd 79 88 6e e4 51 9e 3c 3f b5 f2 32 ec 75 fb 
,03-19 12:52:30.713  3489  3705 D bt-btm  : btm_ble_rand_enc_complete,
03-19 12:52:30.713  3489  3705 I bt-btm  : btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
,03-19 12:52:30.713  3489  3705 D bt-smp  : smp_encrypt_data
03-19 12:52:30.713  3489  3705 W bt-smp  : Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
03-19 12:52:30.713  3489  3705 W bt-smp  : Plain text(LSB ~ MSB) = b5 30 76 00 00 00 00 00 00 00 00 00 00 00 00 00 
03-19 12:52:30.713  3489  3705 W bt-smp  : Encrypted text(LSB ~ MSB) = 68 58 af 29 b2 c7 ed f6 64 5f d6 ed 7d c3 f2 5f 
,03-19 12:52:30.713  3489  3705 D bt-btm  : btm_ble_rand_enc_complete,
03-19 12:52:30.713  3489  3705 I bt-btm  : btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
03-19 12:52:30.713  3489  3705 D bt-smp  : smp_encrypt_data
03-19 12:52:30.713  3489  3705 W bt-smp  : Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
03-19 12:52:30.713  3489  3705 W bt-smp  : Plain text(LSB ~ MSB) = 33 2b 7f 00 00 00 00 00 00 00 00 00 00 00 00 00 
03-19 12:52:30.713  3489  3705 W bt-smp  : Encrypted text(LSB ~ MSB) = 42 80 60 4e 5c 4f e0 c1 82 31 ee 85 52 c5 c4 02 
,03-19 12:52:30.723  3489  3705 D bt-btm  : btm_ble_rand_enc_complete
03-19 12:52:30.723  3489  3705 I bt-btm  : btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
03-19 12:52:30.723  3489  3705 D bt-smp  : smp_encrypt_data
03-19 12:52:30.723  3489  3705 W bt-smp  : Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
03-19 12:52:30.723  3489  3705 W bt-smp  : Plain text(LSB ~ MSB) = d2 32 64 00 00 00 00 00 00 00 00 00 00 00 00 00 ,
03-19 12:52:30.723  3489  3705 W bt-smp  : Encrypted text(LSB ~ MSB) = a1 23 db ae 4a d7 58 be 45 c6 30 68 67 1a ae 79 
,03-19 12:52:30.733  3489  3705 D bt-btm  : btm_ble_rand_enc_complete
03-19 12:52:30.733  3489  3705 I bt-btm  : btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
03-19 12:52:30.733  3489  3705 D bt-smp  : smp_encrypt_data
03-19 12:52:30.733  3489  3705 W bt-smp  : Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
03-19 12:52:30.733  3489  3705 W bt-smp  : Plain text(LSB ~ MSB) = d4 52 57 00 00 00 00 00 00 00 00 00 00 00 00 00 
03-19 12:52:30.733  3489  3705 W bt-smp  : Encrypted text(LSB ~ MSB) = 4e 54 4c f4 bf b6 05 66 fd 86 81 55 74 a3 5c 92 
,03-19 12:52:30.733  3489  3705 D bt-btm  : btm_ble_rand_enc_complete
03-19 12:52:30.733  3489  3705 I bt-btm  : btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
03-19 12:52:30.733  3489  3705 D bt-smp  : smp_encrypt_data
03-19 12:52:30.733  3489  3705 W bt-smp  : Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
03-19 12:52:30.733  3489  3705 W bt-smp  : Plain text(LSB ~ MSB) = f7 46 50 00 00 00 00 00 00 00 00 00 00 00 00 00 
03-19 12:52:30.733  3489  3705 W bt-smp  : Encrypted text(LSB ~ MSB) = 4e e4 58 fc 8e 55 67 ec 19 28 b7 63 f2 ea f4 14 
,03-19 12:52:30.773   925   925 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 8,
03-19 12:52:30.773   925   925 E WifiTrafficPoller:  packet count Tx=40 Rx=48
03-19 12:52:30.773  1221  1221 D WIFI_ICON: WifiActivity: 3
03-19 12:52:30.773   925   925 E WifiTrafficPoller: notifying of data activity 3,
03-19 12:52:30.773  1221  1221 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
03-19 12:52:30.773   925  1153 E WifiStateMachine: handleMessage: E msg.what=131155
03-19 12:52:30.773   925  1153 E WifiStateMachine: processMsg: ConnectedState
03-19 12:52:30.783   925  1153 E WifiStateMachine:  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-57 f=2457 sc=60 link=150 tx=5.8, 0.0, 0.0  rx=5.4 bcn=0 [on:0 tx:0 rx:0 period:2903] from screen [on:0 period:-1900529854] gl hn u24 rssi=-52 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
03-19 12:52:30.783   925  1153 E WifiStateMachine: processMsg: L2ConnectedState
03-19 12:52:30.783   925  1153 E WifiStateMachine:  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-57 f=2457 sc=60 link=150 tx=5.8, 0.0, 0.0  rx=5.4 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1900529853] gl hn u24 rssi=-52 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
03-19 12:52:30.783   925  1153 E WifiStateMachine:  get link layer stats 0
03-19 12:52:30.783   925  1153 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
03-19 12:52:30.783  1337  1337 D wpa_supplicant: wlan0: Control interface command 'SIGNAL_POLL'
03-19 12:52:30.783  1337  1337 I wpa_supplicant: environment dirty rate=0 [5][0][0]
03-19 12:52:30.783   925  1153 E WifiStateMachine: fetchRssiLinkSpeedAndFrequencyNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 150
03-19 12:52:30.783   925  1153 E WifiStateMachine: fetchRssiLinkSpeedAndFrequencyNative rssi=-57 linkspeed=150
03-19 12:52:30.783   925  1153 E WifiConfigStore: updateConfiguration freq=2457 BSSID=f4:f2:6d:22:99:3e RSSI=-57 "NG700"WPA_PSK
03-19 12:52:30.783   925  1153 E WifiStateMachine: calculateWifiScore freq=2457 speed=150 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=5.41 txretriesrate=0.00 rxrate=11.20 userTriggerdPenalty0
03-19 12:52:30.783   925  1153 E WifiStateMachine:  good link -> stuck count =0
03-19 12:52:30.783   925  1153 E WifiStateMachine:  badRSSI count0 lowRSSI count0 --> score 60
03-19 12:52:30.783   925  1153 E WifiStateMachine:  isHighRSSI       ---> score=65
,03-19 12:52:30.793   925  1339 I ActivityManager: Recipient 3194
,03-19 12:52:30.853   925  1598 I ActivityManager: Start proc com.htc.fm for broadcast com.htc.fm/.uiservice.receiver.BootCompletedReceiver: pid=3763 uid=10020 gids={50020, 9997, 1028, 1015} abi=arm64-v8a
,03-19 12:52:30.863   925  1153 E WifiStateMachine: handleMessage: X
,03-19 12:52:30.863   925  1171 D WifiWatchdogStateMachine: RSSI current: 3 new: -57, 3
03-19 12:52:30.863  3489  3575 D BluetoothAdapterProperties: Scan Mode:21
03-19 12:52:30.863  3489  3575 D BluetoothAdapterProperties: Discoverable Timeout:120
03-19 12:52:30.863  3489  3575 I bt-btif : BTA_JvEnable
03-19 12:52:30.863  3489  3575 I bt-btif : BTA_JvRegisterL2cCback
03-19 12:52:30.863  3489  3705 I bt-btm  : BTM_ReadConnectability
03-19 12:52:30.863  3489  3705 I bt-btm  : BTM_ReadDiscoverability
03-19 12:52:30.863  3489  3705 I bt-btm  : BTM_SetDiscoverability
03-19 12:52:30.863  3489  3705 I bt-btm  : btm_ble_set_discoverability mode=0x0 combined_mode=0x2
03-19 12:52:30.863  3489  3705 D bt-btm  : disc_mode 0002
03-19 12:52:30.863  3489  3705 D bt-btm  : btm_ble_update_adv_flag new=0x18
03-19 12:52:30.863  3489  3705 I bt-btm  : evt_type=0x0 p-cb->evt_type=0x3 
03-19 12:52:30.863  3489  3705 I bt-btm  : BTM_SetDiscoverability: mode 2 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
03-19 12:52:30.863  3489  3705 I bt-btm  : BTM_SetConnectability
03-19 12:52:30.863  3489  3705 I bt-btm  : btm_ble_set_connectability mode=0x0 combined_mode=0x1
03-19 12:52:30.863  3489  3705 D bt-btm  : disc_mode 0002
03-19 12:52:30.863  3489  3705 I bt-btm  : BTM_SetConnectability: mode 1 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
03-19 12:52:30.863  3489  3705 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
03-19 12:52:30.863  3489  3705 I bt-btm  : BTM_SetDiscoverability
03-19 12:52:30.863  3489  3705 I bt-btm  : btm_ble_set_discoverability mode=0x0 combined_mode=0x0
03-19 12:52:30.863  3489  3705 D bt-btm  : disc_mode 0000
03-19 12:52:30.863  3489  3705 I bt-btm  : evt_type=0x0 p-cb->evt_type=0x0 
03-19 12:52:30.863  3489  3705 I bt-btm  : BTM_SetDiscoverability: mode 0 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x1000
03-19 12:52:30.863  3489  3705 I bt-btm  : BTM_SetConnectability
03-19 12:52:30.863  3489  3705 I bt-btm  : btm_ble_set_connectability mode=0x0 combined_mode=0x0
03-19 12:52:30.863  3489  3705 D bt-btm  : disc_mode 0000
,03-19 12:52:30.863  3489  3705 D bt-btm  : btm_ble_update_adv_flag new=0x1c
03-19 12:52:30.863  3489  3705 D bt-btm  : btm_ble_update_adv_flag old=0x18
03-19 12:52:30.863  3489  3705 I bt-btm  : BTM_SetConnectability: mode 0 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
03-19 12:52:30.863  3489  3705 I bt-btif : bta_pan_co_init
03-19 12:52:30.863  3489  3705 D bt-sdp  : SDP_CreateRecord ok, num_records:8
03-19 12:52:30.863  3489  3705 I bt-btm  : BTM_SEC_REG[11]: id 27, is_orig 1, psm 0x000f, proto_id 5, chan_id 4374
03-19 12:52:30.863  3489  3705 I bt-btm  :                : sec: 0x20b0, service name [Android Network Access Point] (up to 21 chars saved),
03-19 12:52:30.863  3489  3705 I bt-btm  : BTM_SEC_REG[11]: id 27, is_orig 0, psm 0x000f, proto_id 5, chan_id 4374
03-19 12:52:30.863  3489  3705 I bt-btm  :                : sec: 0x30b6, service name [Android Network Access Point] (up to 21 chars saved)
03-19 12:52:30.863  3489  3705 I bt-btm  : Write Extended Inquiry Response to controller
03-19 12:52:30.863  3489  3705 I bt-btm  : BTM_SEC_REG[12]: id 25, is_orig 1, psm 0x000f, proto_id 5, chan_id 4373
03-19 12:52:30.863  3489  3705 I bt-btm  :                : sec: 0x20b0, service name [Android Network User] (up to 21 chars saved)
03-19 12:52:30.863  3489  3705 I bt-btm  : BTM_SEC_REG[12]: id 25, is_orig 0, psm 0x000f, proto_id 5, chan_id 4373
03-19 12:52:30.863  3489  3705 I bt-btm  :                : sec: 0x30b6, service name [Android Network User] (up to 21 chars saved)
03-19 12:52:30.863  3489  3705 I bt-btm  : Write Extended Inquiry Response to controller
03-19 12:52:30.863  3489  3705 I bt-btm  : Write Extended Inquiry Response to controller
03-19 12:52:30.863  3489  3705 I bt-btm  : Write Extended Inquiry Response to controller
03-19 12:52:30.873  3429  3429 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
03-19 12:52:30.873  3489  3758 E bt_mct  : hci lib postload completed
,03-19 12:52:30.873  3429  3429 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
03-19 12:52:30.873  3489  3575 D bt-sdp  : SDP_CreateRecord ok, num_records:9
03-19 12:52:30.873  3489  3575 I bt-btm  : Write Extended Inquiry Response to controller
03-19 12:52:30.873  3489  3575 I bt-btif : HAL bt_hal_cbacks->adapter_state_changed_cb
03-19 12:52:30.873  3489  3575 D bt-btif : btif_hf_upstreams_evt: event=BTA_AG_ENABLE_EVT
03-19 12:52:30.873  3489  3575 D bt-btif : btif_hf_upstreams_evt: event=BTA_AG_REGISTER_EVT
03-19 12:52:30.873  3489  3575 D bt-btif : btif_hf_upstreams_evt: event=BTA_AG_REGISTER_EVT
03-19 12:52:30.873  3489  3575 D bt-btif : btif_av_state_idle_handler event:BTA_AV_ENABLE_EVT flags 0
03-19 12:52:30.873  3489  3575 D bt-btif : btif_av_state_idle_handler event:BTA_AV_REGISTER_EVT flags 0
03-19 12:52:30.873  3489  3570 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
03-19 12:52:30.873  3489  3570 D BluetoothAdapterProperties: ScanMode =  21
03-19 12:52:30.873  3489  3570 D BluetoothAdapterProperties: State =  11
03-19 12:52:30.873  3489  3570 D BluetoothAdapterProperties: Setting state to 12
03-19 12:52:30.873  3489  3570 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
03-19 12:52:30.873  3489  3575 I bt-btif : HAL bt_hal_cbacks->adapter_properties_cb
03-19 12:52:30.873  3489  3575 D BluetoothAdapterProperties: Discoverable Timeout:120
03-19 12:52:30.873   925  1339 D BluetoothManagerService: +onBluetoothStateChange prev=11 new=12
03-19 12:52:30.873   925  1049 D BluetoothManagerService: Message: MESSAGE_BLUETOOTH_STATE_CHANGE
,03-19 12:52:30.873   925  1049 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
03-19 12:52:30.873   925  1049 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 6 receivers.
03-19 12:52:30.873  3489  3570 I BluetoothAdapterState: Entering On State
03-19 12:52:30.873  1560  2004 D BluetoothHeadset: onBluetoothStateChange: up=true
03-19 12:52:30.873  1560  1588 D BluetoothHeadset: onBluetoothStateChange: up=true
03-19 12:52:30.873   925  1049 D BluetoothHeadset: onBluetoothStateChange: up=true
03-19 12:52:30.873   925  1049 D BluetoothA2dp: onBluetoothStateChange: up=true
03-19 12:52:30.873  1221  1249 D BluetoothHeadset: onBluetoothStateChange: up=true
03-19 12:52:30.883  1560  1587 D BluetoothHeadset: onBluetoothStateChange: up=true
03-19 12:52:30.883   433   433 I art     : Explicit concurrent mark sweep GC freed 8668(368KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 162us total 22.254ms
03-19 12:52:30.883   925  1049 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
,03-19 12:52:30.883   925   925 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
03-19 12:52:30.883  1221  1699 I IntentController: receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
03-19 12:52:30.883   925  1049 D BluetoothManagerService: Message: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
03-19 12:52:30.883   925  1049 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
03-19 12:52:30.883  3489  3489 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
03-19 12:52:30.883  3489  3489 V BluetoothPbapReceiver: ***********state = 12
,03-19 12:52:30.893  1221  1221 D WIFI_ICON: updateWifiState: RSSI_CHANGED 3 -> 3
03-19 12:52:30.893  1221  1221 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,03-19 12:52:30.893   925  1766 D PMS     : acquireWL(65c441f): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 1323 1000 null,
,03-19 12:52:30.903  3489  3489 V BluetoothPbapService: Pbap Service onCreate
,03-19 12:52:30.903  3489  3489 V BluetoothPbapService: Starting PBAP service
03-19 12:52:30.903  1323  1323 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:141 com.android.settings.bluetooth.DockEventReceiver.onReceive:121 
03-19 12:52:30.903   433   433 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 123us total 25.553ms
03-19 12:52:30.903  3489  3489 D BluetoothAdapter: 475246486: getState(). Returning 12
03-19 12:52:30.903  3489  3489 V BluetoothPbapService: Handler(): got msg=1
03-19 12:52:30.903  3489  3489 V BluetoothPbapService: Pbap Service startRfcommSocketListener
,03-19 12:52:30.913  3489  3786 V BluetoothPbapService: Pbap Service initSocket
,03-19 12:52:30.913   925  1615 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,03-19 12:52:30.913  3640  3640 D HtcBtWidget_BTWidgetProvider: onBTStateChanged() for widget: 
,03-19 12:52:30.913  3489  3786 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-19 12:52:30.913   925  1164 D PMS     : releaseWL(65c441f): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 null
03-19 12:52:30.913  3640  3640 D HtcBtWidget_BTWidgetProvider: updateWidget(context) for widget: 
,03-19 12:52:30.923  3489  3575 I bt-btif : HAL bt_hal_cbacks->adapter_properties_cb
03-19 12:52:30.923   925   982 D PMS     : acquireWL(2b6a15ca): PARTIAL_WAKE_LOCK  StartingDockService 0x1 1323 1000 null
03-19 12:52:30.923  3489  3705 I bt-btm  : BTM_SetDiscoverability
03-19 12:52:30.923  3489  3786 I bt-btif : BTA_JvCreateRecordByUser
03-19 12:52:30.923  3489  3705 I bt-btm  : btm_ble_set_discoverability mode=0x0 combined_mode=0x0
03-19 12:52:30.923  3489  3705 D bt-btm  : disc_mode 0000
03-19 12:52:30.923  3489  3705 I bt-btm  : evt_type=0x0 p-cb->evt_type=0x0 
03-19 12:52:30.923  3489  3705 I bt-btm  : BTM_SetDiscoverability: mode 0 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
03-19 12:52:30.923  3489  3705 I bt-btm  : BTM_SetConnectability
,03-19 12:52:30.923  3489  3705 I bt-btm  : btm_ble_set_connectability mode=0x0 combined_mode=0x1
03-19 12:52:30.923  3489  3705 D bt-btm  : disc_mode 0000
03-19 12:52:30.923  3489  3705 D bt-btm  : btm_ble_update_adv_flag new=0x18
03-19 12:52:30.923  3489  3705 D bt-btm  : btm_ble_update_adv_flag old=0x1c
03-19 12:52:30.923  3489  3705 I bt-btm  : BTM_SetConnectability: mode 1 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
03-19 12:52:30.923  3489  3705 D bt-sdp  : SDP_CreateRecord ok, num_records:10
03-19 12:52:30.923  3489  3705 I bt-btm  : Write Extended Inquiry Response to controller
03-19 12:52:30.923  3489  3705 I bt-btif : BTA_JvRfcommStartServer
03-19 12:52:30.923  3489  3705 I bt-btm  : BTM_SEC_REG[13]: id 55, is_orig 0, psm 0x0003, proto_id 3, chan_id 19
03-19 12:52:30.923  3489  3705 I bt-btm  :                : sec: 0x86, service name [JV PORT] (up to 21 chars saved)
03-19 12:52:30.923  3489  3786 V BluetoothPbapService: Succeed to create listening socket 
03-19 12:52:30.923  3489  3786 V BluetoothPbapService: Accepting socket connection...
03-19 12:52:30.923   433   433 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 266us total 17.672ms
03-19 12:52:30.923  3489  3575 D BluetoothAdapterProperties: Scan Mode:21
03-19 12:52:30.923  3429  3429 D BluetoothAdapter: 102294481: getState(). Returning 12
03-19 12:52:30.923  3429  3429 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
,03-19 12:52:30.933   925  1617 W System.err: java.lang.Throwable: stack dump
03-19 12:52:30.933   925  1049 D BluetoothManagerService: Message: MESSAGE_REGISTER_ADAPTER
03-19 12:52:30.933   925  1049 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@24a7e7b1:true
03-19 12:52:30.933   925  1617 W System.err: 	at java.lang.Thread.dumpStack(Thread.java:490)
03-19 12:52:30.933   925  1617 W System.err: 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
03-19 12:52:30.933   925  1617 W System.err: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
03-19 12:52:30.933   925  1617 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
03-19 12:52:30.933  1221  1221 D BluetoothAdapter: 349496506: getState(). Returning 12
03-19 12:52:30.933  1221  1221 D BluetoothAdapter: 349496506: getState(). Returning 12
03-19 12:52:30.943  1221  1221 I QuickSettingBluetooth: receive.ACTION_STATE_CHANGE:STATE_ON/(true,false)
,03-19 12:52:30.943  3429  3429 D BluetoothAdapter: 102294481: getState(). Returning 12
,03-19 12:52:30.943  1221  1221 D PhoneStatusBar: addIcon slot=bluetooth index=12 viewIndex=1 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f0204ad level=0 visible=true num=0 ) name=stat_sys_data_bluetooth vis=true
03-19 12:52:30.953  3429  3429 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
03-19 12:52:30.953  3429  3429 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-19 12:52:30.953  3429  3429 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-19 12:52:30.953  3429  3429 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-19 12:52:30.953  3429  3429 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-19 12:52:30.953  3429  3429 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-19 12:52:30.953  3429  3429 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-19 12:52:30.953  3429  3429 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
03-19 12:52:30.953  3429  3429 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,03-19 12:52:30.963  1323  1323 D BluetoothAdapter: 296689711: getState(). Returning 12
,03-19 12:52:30.973  1323  1323 D BluetoothInputDevice: BluetoothInputDevice()
,03-19 12:52:30.973   925  1766 D BluetoothManagerService: registerStateChangeCallback+,
,03-19 12:52:30.973   925  1049 D BluetoothManagerService: Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,03-19 12:52:30.973   925  1049 D BluetoothManagerService: Registered receivers: 7,
,03-19 12:52:30.973  1323  1323 D BluetoothPan: BluetoothPan()
,03-19 12:52:30.983   925  1619 D BluetoothManagerService: registerStateChangeCallback+
,03-19 12:52:30.983   925  1049 D BluetoothManagerService: Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,03-19 12:52:30.983   925  1049 D BluetoothManagerService: Registered receivers: 8
,03-19 12:52:30.983  1323  1323 D BluetoothMap: Create BluetoothMap proxy object
03-19 12:52:30.983   925  1615 D BluetoothManagerService: registerStateChangeCallback+
03-19 12:52:30.983   925  1049 D BluetoothManagerService: Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
03-19 12:52:30.983   925  1049 D BluetoothManagerService: Registered receivers: 9
,03-19 12:52:30.983  1323  1323 E BluetoothMap: Could not bind to Bluetooth MAP Service with Intent { act=android.bluetooth.IBluetoothMap }
,03-19 12:52:30.993   925  1619 D BluetoothManagerService: registerStateChangeCallback+
03-19 12:52:30.993   925  1049 D BluetoothManagerService: Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
03-19 12:52:30.993  1323  1323 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1888 android.content.ContextWrapper.bindService:538 android.bluetooth.BluetoothSap.doBind:108 android.bluetooth.BluetoothSap.<init>:101 android.bluetooth.BluetoothAdapter.getProfileProxy:1423 
03-19 12:52:30.993  1323  1323 D BluetoothSap: BluetoothSap() call bindService
03-19 12:52:30.993   925  1049 D BluetoothManagerService: Registered receivers: 10
03-19 12:52:30.993  1323  1323 D BluetoothPbap: BluetoothPbap()
03-19 12:52:30.993   925  1619 D BluetoothManagerService: registerStateChangeCallback+
,03-19 12:52:30.993   925  1049 D BluetoothManagerService: Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
03-19 12:52:30.993   925  1049 D BluetoothManagerService: Registered receivers: 11
03-19 12:52:31.003  2131  2131 D FlexNetS: setNetMode:0, false
,03-19 12:52:31.003  2131  2131 D FlexNetS: set2gLowSignalEnablePref: false
03-19 12:52:31.003  2131  2131 V FlexNetS: [DRX] setHigherPowerIn2GPref to: true
03-19 12:52:31.003  2131  2131 D FlexNetS: setSimCardisWhiteList: false
03-19 12:52:31.003   925  1766 D BluetoothManagerService: registerStateChangeCallback+,
03-19 12:52:31.003   925  1049 D BluetoothManagerService: Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
03-19 12:52:31.003   925  1049 D BluetoothManagerService: Registered receivers: 12
03-19 12:52:31.003  2131  2131 V FlexNetS: setSimCardCamp3GNetworkSignalPref to: false
03-19 12:52:31.003  2131  2131 D FlexNetS: setCampNetworkisBlackList: false
,03-19 12:52:31.003   925  1598 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0,
,03-19 12:52:31.003  3489  3794 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-19 12:52:31.013  2131  2131 V FlexNetS: [DRX] setHigherPowerIn2GPref to: true
,03-19 12:52:31.013  1323  1323 D BluetoothHeadset: BluetoothHeadset()
,03-19 12:52:31.013   925  1766 D BluetoothManagerService: registerStateChangeCallback+
,03-19 12:52:31.013   925  1049 D BluetoothManagerService: Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,03-19 12:52:31.013   925  1049 D BluetoothManagerService: Registered receivers: 13
,03-19 12:52:31.013  3489  3794 I bt-btif : BTA_JvCreateRecordByUser
03-19 12:52:31.013  3489  3705 D bt-sdp  : SDP_CreateRecord ok, num_records:11
03-19 12:52:31.013  3489  3705 I bt-btm  : Write Extended Inquiry Response to controller
03-19 12:52:31.013  3489  3705 I bt-btif : BTA_JvRfcommStartServer
03-19 12:52:31.013  3489  3705 I bt-btm  : BTM_SEC_REG[14]: id 56, is_orig 0, psm 0x0003, proto_id 3, chan_id 12
03-19 12:52:31.013  3489  3705 I bt-btm  :                : sec: 0x80, service name [JV PORT] (up to 21 chars saved)
03-19 12:52:31.013  3489  3794 I BtOppRfcommListener: Accept thread started.
,03-19 12:52:31.013  3489  3489 D BluetoothAdapter: 475246486: getState(). Returning 12
,03-19 12:52:31.013  3489  3489 D BluetoothFtpService: ACTION_STATE_CHANGED: state: 12mHasStarted: true
,03-19 12:52:31.023  3489  3489 D BluetoothMasReceiver: Bluetooth STATE CHANGED to 12
03-19 12:52:31.023  3489  3489 D BluetoothMasReceiver:  call MAP start service
03-19 12:52:31.023  2131  3796 V FlexNetS: setRilHandOverW2GEnable: 0,
03-19 12:52:31.023  1323  1323 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,03-19 12:52:31.023  3489  3489 V BluetoothPbapService: Pbap Service onBind
03-19 12:52:31.023  3489  3489 D BluetoothFtpService: htc sense version is 6.0
03-19 12:52:31.023  2131  2131 D FlexNetS: updateSvcAllowedInSettings:false
03-19 12:52:31.023  1323  1323 D DockEventReceiver: finishStartingService: stopping service
03-19 12:52:31.023  1323  1323 D BluetoothInputDevice: Proxy object connected
,03-19 12:52:31.023   925  1620 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
03-19 12:52:31.023  1323  1323 D HidProfile: Bluetooth service connected
03-19 12:52:31.023  3489  3489 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-19 12:52:31.033  3489  3489 I bt-btif : BTA_JvCreateRecordByUser
03-19 12:52:31.033  3489  3705 D bt-sdp  : SDP_CreateRecord ok, num_records:12
03-19 12:52:31.033  3489  3705 I bt-btm  : Write Extended Inquiry Response to controller
03-19 12:52:31.033  3489  3705 I bt-btif : BTA_JvRfcommStartServer
03-19 12:52:31.033  3489  3705 I bt-btm  : BTM_SEC_REG[15]: id 57, is_orig 0, psm 0x0003, proto_id 3, chan_id 20
03-19 12:52:31.033  3489  3705 I bt-btm  :                : sec: 0x1086, service name [JV PORT] (up to 21 chars saved)
,03-19 12:52:31.033  3489  3799 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
03-19 12:52:31.033  3489  3489 E BluetoothMasService: BluetoothMasObexConnectionManager: mIsEmailEnabled: true
,03-19 12:52:31.033  1323  1323 D BluetoothAdapter: 296689711: getState(). Returning 12
,03-19 12:52:31.033  1323  1323 D BluetoothPan: BluetoothPAN Proxy object connected
,03-19 12:52:31.033  1323  1323 D PanProfile: Bluetooth service connected
03-19 12:52:31.033  1323  1323 D BluetoothA2dp: Proxy object connected
03-19 12:52:31.033  1323  1323 D A2dpProfile: Bluetooth service connected
,03-19 12:52:31.033  1323  1323 D BluetoothAdapter: 296689711: getState(). Returning 12
03-19 12:52:31.033   412  3761 D libc    : [NET] _dns_getaddrinfo-, (NS_SUCCESS)
03-19 12:52:31.033   412  3761 D libc    : [NET] android_getaddrinfofornet-, SUCCESS
,03-19 12:52:31.043  2172  3229 D libc    : [NET] android_getaddrinfo_proxy-, success,
03-19 12:52:31.043  1323  1323 D BluetoothHeadset: Proxy object connected,
,03-19 12:52:31.043  3489  3489 D BluetoothMasService: Add permission for SmsProvider.
,03-19 12:52:31.043  1323  1323 D HeadsetProfile: Bluetooth service connected
03-19 12:52:31.043  3489  3489 V BluetoothMasService: Starting MAS instances
03-19 12:52:31.043  3489  3489 D BluetoothAdapter: 475246486: getState(). Returning 12
03-19 12:52:31.043  1323  1323 D BluetoothAdapter: 296689711: getState(). Returning 12
03-19 12:52:31.043  1323  1323 D BluetoothPbap: Proxy object connected
,03-19 12:52:31.043  1323  1323 D PbapServerProfile: Bluetooth service connected
03-19 12:52:31.053  3489  3489 I MailMessageReceiver: reg:com.android.bluetooth.btservice.AdapterApp@960620f with com.htc.lib1.HtcMailLibFramework.MailMessageReceiver@284829c
03-19 12:52:31.053  3489  3489 I MailManager: MailManager contruct! com.htc.lib1.HtcMailLibFramework.MailMessageReceiver@284829c
03-19 12:52:31.053   925  1339 D PMS     : releaseWL(2b6a15ca): PARTIAL_WAKE_LOCK  StartingDockService 0x1 null
03-19 12:52:31.053  3489  3489 V EmailUtils: Manager Instance is not NULL
03-19 12:52:31.053   925  1617 D Process : killProcessQuiet, pid=2897
03-19 12:52:31.053   925  1617 I ActivityManager: Killing 2897:com.htc.sense.mms/u0a64 (adj 15): empty #17
,03-19 12:52:31.053   925  1617 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,03-19 12:52:31.073  3429  3729 W jxcore-log: Initializing JXcore engine
,03-19 12:52:31.073  3429  3729 W jxcore-log: JXcore engine is ready
,03-19 12:52:31.133  3429  3729 W jxcore-log: Starting JXcore engine
,03-19 12:52:31.143   925  1771 I ActivityManager: Recipient 2897
,03-19 12:52:31.173   925  1764 I ActivityManager: Start proc com.htc.android.mail:sync for content provider com.htc.android.mail/.MailProvider: pid=3800 uid=10062 gids={50062, 9997, 3003, 1023, 1028, 1015} abi=armeabi-v7a,
,03-19 12:52:31.193   925  1617 D Process : killProcessQuiet, pid=3235
03-19 12:52:31.193   925  1617 I ActivityManager: Start proc com.google.android.onetimeinitializer for broadcast com.google.android.onetimeinitializer/.OneTimeInitializerReceiver: pid=3814 uid=10026 gids={50026, 9997} abi=arm64-v8a
03-19 12:52:31.193   925  1617 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
03-19 12:52:31.193   925  1617 I ActivityManager: Killing 3235:com.google.android.talk/u0a112 (adj 15): empty #17
,03-19 12:52:31.253  3429  3729 W jxcore-log: Platform android,
03-19 12:52:31.253  3429  3729 W jxcore-log: 
,03-19 12:52:31.253  3429  3729 W jxcore-log: Process ARCH arm
03-19 12:52:31.253  3429  3729 W jxcore-log: 
,03-19 12:52:31.293   925  1164 I ActivityManager: Recipient 3235
,03-19 12:52:31.353  3814  3814 V OneTimeInitializerReceiver: OneTimeInitializerReceiver.onReceive,
,03-19 12:52:31.363  3814  3842 V OneTimeService: OneTimeService.onHandleIntent,
,03-19 12:52:31.373   925  1599 I ActivityManager: Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.GooglePartnerSetup: pid=3844 uid=10027 gids={50027, 9997, 3003} abi=arm64-v8a
03-19 12:52:31.373   925   982 D Process : killProcessQuiet, pid=3269
03-19 12:52:31.373   925   982 I ActivityManager: Killing 3269:com.google.android.apps.magazines/u0a161 (adj 15): empty #17
03-19 12:52:31.373   925   982 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,03-19 12:52:31.413  2172  3229 D libc    : [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4,
03-19 12:52:31.413  2172  3229 D libc    : [NET] android_getaddrinfofornet-, err=8
,03-19 12:52:31.463  3429  3729 I jxcore-log: JXcore Cordova bridge is ready!
03-19 12:52:31.463  3429  3729 I jxcore-log: 
03-19 12:52:31.463  3429  3729 W jxcore-log: JXcore engine is started
,03-19 12:52:31.463  3429  3654 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
03-19 12:52:31.463  3429  3429 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,03-19 12:52:31.473  3429  3729 E jxcore  : Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js,
03-19 12:52:31.473  3429  3729 E jxcore  : Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,03-19 12:52:31.483  3429  3429 I chromium: [INFO:CONSOLE(57)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (57)
03-19 12:52:31.483  3429  3429 I chromium: [INFO:CONSOLE(62)] "****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****", source: file:///android_asset/www/js/thali_main.js (62)
,03-19 12:52:31.503   925   974 I ActivityManager: Recipient 3269
,03-19 12:52:31.643  3429  3429 D io.jxcore.node.LifeCycleMonitor: onActivityPaused,
03-19 12:52:31.643   925  1339 D PMS     : acquireWL(17cbcb82): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 925 1000 null
03-19 12:52:31.643  3429  3654 W PluginManager: THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 164ms. Plugin should use CordovaInterface.getThreadPool().
03-19 12:52:31.643  3429  3429 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
03-19 12:52:31.653   925  1667 W HtcSystemUPManager: HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
,03-19 12:52:31.663   925  1599 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.partnersetup, clsName=com.google.android.partnersetup.PhoneStateReceiver, state=1, flag=1, pid=3844, uid=10027, userID:0
,03-19 12:52:31.663  3800  3839 D HtcAdjCursorFactory: Set CursorWindow size to: 4194304 KB, Tid: 3839
,03-19 12:52:31.683  1624  1624 I FeedHostManager: [onResume],
03-19 12:52:31.683  1624  1624 I FeedProviderManager: onResume
03-19 12:52:31.683  1624  2436 I SocialFeedProvider: +onResume
03-19 12:52:31.683  1624  2436 I SocialFeedProvider: updateAccounts - Accounts is no change
03-19 12:52:31.683  1624  2436 I SocialFeedProvider: -onResume,
,03-19 12:52:31.683   925  1047 D StatusBarManagerService: setSystemUiVisibility(0x8700)
03-19 12:52:31.683   925  1047 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
03-19 12:52:31.683   925  1047 D StatusBarManagerService: hiding MENU key
,03-19 12:52:31.693  1624  1624 D FindExtension: FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
,03-19 12:52:31.693  1624  1624 I ThreadedRenderer: Defer allocateBuffers to drawing time
,03-19 12:52:31.693   925  1617 I InputMethodManagerService: Disable input method client, pid=3429
,03-19 12:52:31.693   925  1617 D StatusBarManagerService: swetImeWindowStatus vis=0 backDisposition=0
03-19 12:52:31.693   925  1617 I InputMethodManagerService: Enable input method client, pid=1624
03-19 12:52:31.693  1221  1221 I PhoneStatusBar: setImeWindowStatus(false,false)
,03-19 12:52:31.703  3429  3429 W IInputConnectionWrapper: reportFullscreenMode on inactive InputConnection
,03-19 12:52:31.733  3489  3489 D EmailUtils: ============NULL aList========
,03-19 12:52:31.733  3489  3489 V EmailUtils: <-getEmailAccountIdList
,03-19 12:52:31.733  3489  3489 V BluetoothMasService: onCreate: mIsEmailEnabled: true
,03-19 12:52:31.733  2172  3229 D libc    : [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
03-19 12:52:31.733  3489  3489 D BluetoothAdapter: 475246486: getState(). Returning 12
,03-19 12:52:31.733  2172  3229 D libc    : [NET] android_getaddrinfofornet-, err=8
03-19 12:52:31.733  3489  3489 V BluetoothMasService: parseIntent 1: mIsEmailEnabled: true
03-19 12:52:31.733  3489  3489 V EmailUtils: Manager Instance is not NULL
03-19 12:52:31.733  2172  3229 D libc    : [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
03-19 12:52:31.733  2172  3229 D libc    : [NET] android_getaddrinfofornet-, err=8
,03-19 12:52:31.753   925  1617 I ActivityManager: Start proc com.htc.video for broadcast com.htc.video/.videowidget.videoDMC.DLNAReceiver: pid=3878 uid=10029 gids={50029, 9997, 3002, 3003, 1028, 1015, 1023, 2001} abi=arm64-v8a,
03-19 12:52:31.753   925  1617 D PMS     : releaseWL(17cbcb82): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,03-19 12:52:31.753  3489  3489 D EmailUtils: ============NULL aList========
03-19 12:52:31.753  3489  3489 V EmailUtils: <-getEmailAccountIdList
,03-19 12:52:31.753  3489  3489 V BluetoothSapReceiver: SapReceiver onReceive 
03-19 12:52:31.753  3489  3489 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
03-19 12:52:31.753  3489  3489 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
,03-19 12:52:31.753  3489  3489 V BluetoothSapReceiver: Calling SAP service start service with action = android.bluetooth.adapter.action.STATE_CHANGED
03-19 12:52:31.753   925  1047 D StatusBarManagerService: setSystemUiVisibility(0xc0000700)
03-19 12:52:31.753   925  1047 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
03-19 12:52:31.753   925  1047 D StatusBarManagerService: hiding MENU key
,03-19 12:52:31.763  3489  3489 V BluetoothMasService: handleMessage: mIsEmailEnabledtrue
03-19 12:52:31.763  2172  3229 I CheckinTask: Sending checkin request (9054 bytes)
,03-19 12:52:31.763  3489  3489 V BtMns   : BluetoothMns: isEmailEnabled: true
03-19 12:52:31.763  1799  1799 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,03-19 12:52:31.773   925   925 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 8
03-19 12:52:31.773   925  1598 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
03-19 12:52:31.773   925   925 E WifiTrafficPoller:  packet count Tx=53 Rx=54
,03-19 12:52:31.773  3489  3489 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-19 12:52:31.783  3489  3489 I bt-btif : BTA_JvCreateRecordByUser
,03-19 12:52:31.783  3489  3705 D bt-btm  : BTM_AllocateSCN
03-19 12:52:31.793  3489  3705 D bt-sdp  : SDP_CreateRecord ok, num_records:13
03-19 12:52:31.793  3489  3705 I bt-btm  : Write Extended Inquiry Response to controller
03-19 12:52:31.793  3489  3705 I bt-btif : BTA_JvRfcommStartServer
03-19 12:52:31.793  3489  3705 I bt-btm  : BTM_SEC_REG[16]: id 58, is_orig 0, psm 0x0003, proto_id 3, chan_id 4
03-19 12:52:31.793  3489  3705 I bt-btm  :                : sec: 0x1086, service name [JV PORT] (up to 21 chars saved)
,03-19 12:52:31.793   925  1620 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,03-19 12:52:31.793  3489  3489 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-19 12:52:31.793   925  1016 I ActivityManager: Killing 3361:com.android.chrome/u0a96 (adj 15): empty #17
03-19 12:52:31.793   925  1016 D Process : killProcessQuiet, pid=3361
03-19 12:52:31.803   925  1016 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityStack.destroyActivityLocked:3422 
,03-19 12:52:31.813  3865  3901 E cutils-trace: Error opening trace file: Permission denied (13),
,03-19 12:52:31.823   925  1374 D PMS     : acquireWL(22121932): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1845 10024 WorkSource{10024 com.google.android.gms}
,03-19 12:52:31.823   925  1615 D PMS     : releaseWL(22121932): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,03-19 12:52:31.873  3865  3865 D CustomizationManager: ====startRecUseTime====,
03-19 12:52:31.873  3865  3865 D htc.customization.log.level:  is 
03-19 12:52:31.873  3865  3865 W CustomizationLogLevel: Level value is invalid, use default level 2
,03-19 12:52:31.893   925  1619 I ActivityManager: Recipient 3361
,03-19 12:52:31.903  3489  3489 I bt-btif : BTA_JvCreateRecordByUser
03-19 12:52:31.903  3489  3705 D bt-btm  : BTM_AllocateSCN
,03-19 12:52:31.903  3489  3705 D bt-sdp  : SDP_CreateRecord ok, num_records:14
03-19 12:52:31.903  3489  3705 I bt-btm  : Write Extended Inquiry Response to controller
03-19 12:52:31.903  3489  3705 I bt-btif : BTA_JvRfcommStartServer
03-19 12:52:31.903  3489  3705 I bt-btm  : BTM_SEC_REG[17]: id 59, is_orig 0, psm 0x0003, proto_id 3, chan_id 5
03-19 12:52:31.903  3489  3705 I bt-btm  :                : sec: 0x1086, service name [JV PORT] (up to 21 chars saved)
03-19 12:52:31.913  3429  3429 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
03-19 12:52:31.913  3429  3429 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED,
03-19 12:52:31.913  3429  3429 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
03-19 12:52:31.913  3429  3429 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: DESTROYED
03-19 12:52:31.913  3429  3429 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,03-19 12:52:31.913  3429  3429 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
03-19 12:52:31.913  3429  3429 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,03-19 12:52:31.913  3429  3429 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
03-19 12:52:31.913  3429  3429 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36539db3 removed from the list
03-19 12:52:31.913  3429  3429 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
03-19 12:52:31.913  3429  3429 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38591b6e removed from the list
03-19 12:52:31.913  3429  3429 D io.jxcore.node.ConnectivityMonitor: stop
03-19 12:52:31.913  3429  3429 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
03-19 12:52:31.913  3489  3489 D A2dpService: getA2DPService(): returning com.android.bluetooth.a2dp.A2dpService@4cb102b,
03-19 12:52:31.913  3489  3489 D A2dpSinkService: getA2dpSinkService(): service is NULL
,03-19 12:52:31.923   925  1617 I ActivityManager: Killing 2241:com.google.android.gms.wearable/u0a24 (adj 15): empty #17
,03-19 12:52:31.923   925  1617 D Process : killProcessQuiet, pid=2241
03-19 12:52:31.923   925  1617 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.removeContentProvider:10141 
,03-19 12:52:31.953  3865  3865 D CustomizationManager:  Read ACC file spent 0.039 (s),
,03-19 12:52:31.953  3865  3865 D CIDMapFileReader: Parsing tag item name = HTC__001
03-19 12:52:31.953  3865  3865 D CIDMapFileReader: Parsing tag item name = HTC__102
03-19 12:52:31.953  3865  3865 D CIDMapFileReader: Parsing tag item name = HTC__Y13
03-19 12:52:31.953  3865  3865 D CIDMapFileReader: Parsing tag item name = HTC__032
03-19 12:52:31.953  3865  3865 D CIDMapFileReader: Parsing tag item name = HTC__M27
,03-19 12:52:31.953  3865  3865 D CIDMapFileReader: Parsing tag item name = HTC__002
03-19 12:52:31.953  3865  3865 D CIDMapFileReader: Parsing tag item name = HTC__031
,03-19 12:52:31.953  3865  3865 V CustomizationCIDLoader: full path : /system/customize/CID/HTC__102.xml
,03-19 12:52:31.953  3865  3865 I CustomizationCIDLoader: Parsing tag category name = system
,03-19 12:52:31.953  3865  3865 I CustomizationCIDLoader: Parsing tag category name = application
,03-19 12:52:31.953  3865  3865 I CustomizationCIDLoader: Parsing tag category name = SettingsProvider
03-19 12:52:31.953  3865  3865 I CustomizationCIDLoader: Parsing tag category name = AutomotiveHome
03-19 12:52:31.953  3865  3865 I CustomizationCIDLoader: Parsing tag category name = AudioService
03-19 12:52:31.953  3865  3865 I CustomizationCIDLoader: Parsing tag category name = Settings
03-19 12:52:31.953  3865  3865 I CustomizationCIDLoader: Parsing tag category name = ACC
03-19 12:52:31.963  3865  3865 I CustomizationCIDLoader: add string-array item, value = 42507
03-19 12:52:31.963  3865  3865 I CustomizationCIDLoader: add string-array item, value = 21902
03-19 12:52:31.963  3865  3865 I CustomizationCIDLoader: add string-array item, value = 26006:26001.26002.26003
03-19 12:52:31.963  3865  3865 I CustomizationCIDLoader: add string-array item, value = 23420
03-19 12:52:31.963  3865  3865 I CustomizationCIDLoader: add string-array item, value = 22299
03-19 12:52:31.963  3865  3865 I CustomizationCIDLoader: add string-array item, value = 24002
,03-19 12:52:31.963  3865  3865 I CustomizationCIDLoader: add string-array item, value = 23210
03-19 12:52:31.963  3865  3865 I CustomizationCIDLoader: add string-array item, value = 23205
03-19 12:52:31.963  3865  3865 I CustomizationCIDLoader: add string-array item, value = 23806
03-19 12:52:31.963  3865  3865 I CustomizationCIDLoader: add string-array item, value = 23430
03-19 12:52:31.963  3865  3865 I CustomizationCIDLoader: add string-array item, value = 23408
03-19 12:52:31.963  3865  3865 I CustomizationCIDLoader: add string-array item, value = 27205
03-19 12:52:31.963  3865  3865 I CustomizationCIDLoader: add string-array item, value = 42507:C:1:0
03-19 12:52:31.963  3865  3865 I CustomizationCIDLoader: add string-array item, value = 21902:C:1:0
03-19 12:52:31.963  3865  3865 I CustomizationCIDLoader: add string-array item, value = 26006:D:1:0
03-19 12:52:31.963  3865  3865 I CustomizationCIDLoader: add string-array item, value = 23420:D:0:0
03-19 12:52:31.963  3865  3865 I CustomizationCIDLoader: add string-array item, value = 22299:D:0:0
03-19 12:52:31.963  3865  3865 I CustomizationCIDLoader: add string-array item, value = 24002:D:0:0
03-19 12:52:31.963  3865  3865 I CustomizationCIDLoader: add string-array item, value = 23210:D:2:0
03-19 12:52:31.963  3865  3865 I CustomizationCIDLoader: add string-array item, value = 23205:D:0:0
03-19 12:52:31.963  3865  3865 I CustomizationCIDLoader: add string-array item, value = 23806:D:0:0
03-19 12:52:31.963  3865  3865 I CustomizationCIDLoader: add string-array item, value = 23430:C:1:0
03-19 12:52:31.963  3865  3865 I CustomizationCIDLoader: add string-array item, value = 23408:C:1:0
03-19 12:52:31.963  3865  3865 I CustomizationCIDLoader: add string-array item, value = 27205:C:1:0
03-19 12:52:31.963  3865  3865 D CustomizationManager:  Read CID file spent 0.087 (s)
03-19 12:52:31.963  3865  3865 D CustomizationManager:  All configurations done spent 0.088 (s)
,03-19 12:52:31.993   925  1764 D PackageManager: deletePackageAsUser: pkg=com.test.thalitest, pid=3865, uid=2000 userid=0
,03-19 12:52:32.013   925  1621 I ActivityManager: Recipient 2241,
,03-19 12:52:32.033  3489  3489 V BluetoothSapService: Sap Service onCreate,
03-19 12:52:32.033  3489  3489 V BluetoothSapService: initBinder
03-19 12:52:32.033  3489  3489 V BluetoothSapService: BluetoothSapBinder: mService: com.android.bluetooth.sap.BluetoothSapService@15a52c88
03-19 12:52:32.033  3429  3429 I io.jxcore.node.LifeCycleMonitor: stop: OK
03-19 12:52:32.033  3489  3489 V BluetoothSapService: Sap Service onBind: com.android.bluetooth.sap.BluetoothSapService$BluetoothSapBinder@f752a46
,03-19 12:52:32.083   925  1067 W PackageSettings: Skipping PackageSetting{7cd91e6 com.example.hello/10374} due to missing metadata
,03-19 12:52:32.113   925  1619 D Process : killProcessQuiet, pid=3398,
03-19 12:52:32.113   925  1619 I ActivityManager: Start proc com.htc.csrecommend for broadcast com.htc.csrecommend/.receiver.BootCompletedReceiver: pid=3920 uid=10031 gids={50031, 9997, 3003} abi=arm64-v8a
03-19 12:52:32.113   925  1619 I ActivityManager: Killing 3398:com.google.android.apps.plus/u0a167 (adj 15): empty #17
03-19 12:52:32.123   925  1619 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,03-19 12:52:32.223   925  1598 I ActivityManager: Recipient 3398
,03-19 12:52:32.233  1624  2121 W OpenGLRenderer: Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...,
,03-19 12:52:32.323   925  1016 D Process : killProcessQuiet, pid=3429
03-19 12:52:32.323   925  1016 I ActivityManager: Force stopping com.test.thalitest appid=10195 user=-1: uninstall pkg
03-19 12:52:32.323   925  1016 I ActivityManager: Killing 3429:com.test.thalitest/u0a195 (adj 9): stop com.test.thalitest
,03-19 12:52:32.333   925  1016 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.removeProcessLocked:6363 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:6161 
,03-19 12:52:32.423   925  1769 I ActivityManager: Recipient 3429
,03-19 12:52:32.423   925  1771 I WindowState: WIN DEATH: Window{2289034d u0 com.test.thalitest/com.test.thalitest.MainActivity}
03-19 12:52:32.423   925  1155 D WifiService: Client connection lost with reason: 4
,03-19 12:52:32.423  1382  1382 E InputEventReceiver: Looper::removeFd(68) is failed, result(0), input channel 'ClientState{2b396680 uid 10195 pid 3429} (c)'
,03-19 12:52:32.543  1323  1323 D SapServerProfile: Bluetooth service connected
03-19 12:52:32.543  3489  3489 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
03-19 12:52:32.543  3489  3489 V BluetoothSapService: state: 12
,03-19 12:52:32.553   925  1339 W ActivityManager: unregisterReceiver: receiver object not existed in mRegisteredReceivers
,03-19 12:52:32.553   925  1769 W ActivityManager: Spurious death for ProcessRecord{340e2683 3429:com.test.thalitest/u0a195}, curProc for 3429: null
03-19 12:52:32.553  3489  3489 V BluetoothSapService: Starting SAP server process
,03-19 12:52:32.563  3489  3489 V BluetoothSapService: SAP Service startRfcommListenerThread
,03-19 12:52:32.573   925  1067 I ActivityManager: Force stopping com.test.thalitest appid=10195 user=0: pkg removed
03-19 12:52:32.573  3489  3943 V BluetoothSapService: Sap Service initRfcommSocket
,03-19 12:52:32.593   925  1764 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,03-19 12:52:32.603  3489  3943 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-19 12:52:32.603   925  1599 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.apps.maps, clsName=null, state=1, flag=0, pid=3844, uid=10027, userID:0
,03-19 12:52:32.603  1298  1298 D DotMatrix: [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
03-19 12:52:32.603   925  1151 V NetworkPolicy: ACTION_UID_REMOVED for uid=10195
03-19 12:52:32.603  1298  1298 D DotMatrix: [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
03-19 12:52:32.603   925  1150 D PMS     : acquireWL(182a7df): PARTIAL_WAKE_LOCK  NetworkStats 0x1 925 1000 null
03-19 12:52:32.603  1298  1298 D DotMatrix: [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
03-19 12:52:32.613  3489  3943 I bt-btif : BTA_JvCreateRecordByUser
03-19 12:52:32.613  3489  3705 D bt-sdp  : SDP_CreateRecord ok, num_records:15
03-19 12:52:32.613  3489  3705 I bt-btm  : Write Extended Inquiry Response to controller
03-19 12:52:32.613  3489  3705 I bt-btif : BTA_JvRfcommStartServer
03-19 12:52:32.613  3489  3705 I bt-btm  : BTM_SEC_REG[18]: id 60, is_orig 0, psm 0x0003, proto_id 3, chan_id 15
03-19 12:52:32.613  3489  3705 I bt-btm  :                : sec: 0x4086, service name [JV PORT] (up to 21 chars saved)
03-19 12:52:32.613  3489  3943 V BluetoothSapService: Succeed to create listening socket 
03-19 12:52:32.613  3489  3943 V BluetoothSapService: Accepting socket connection...
03-19 12:52:32.613  2872  2918 D AccTypeManager: Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
03-19 12:52:32.623   925  1145 W SystemReader: Cannot find grip_rejection_width, use default value instead
03-19 12:52:32.623  2872  2918 D AccTypeManager: Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,03-19 12:52:32.643  1774  2168 D AccTypeManager: Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
,03-19 12:52:32.643  1624  1624 I art     : Explicit concurrent mark sweep GC freed 19899(1428KB) AllocSpace objects, 11(1308KB) LOS objects, 34% free, 30MB/46MB, paused 1.661ms total 69.620ms
,03-19 12:52:32.643  1624  2106 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
03-19 12:52:32.643  1624  2106 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,03-19 12:52:32.653   925  1010 I InputMethodManagerService: [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
,03-19 12:52:32.663  1774  2168 D AccTypeManager: Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,03-19 12:52:32.663   925  1150 D PMS     : releaseWL(182a7df): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,03-19 12:52:32.663   925  1151 V NetworkPolicy: writePolicyLocked(),
,03-19 12:52:32.673  1560  1560 D PhoneApp: -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED,
,03-19 12:52:32.673  2872  2918 D AccTypeManager: Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,03-19 12:52:32.683   925  1151 V NetworkPolicy: updateNetworkEnabledLocked()
03-19 12:52:32.683   925  1151 V NetworkPolicy: updateNotificationsLocked()
,03-19 12:52:32.693  2872  2918 E ExternalAccountType: Unsupported attribute readOnly,
,03-19 12:52:32.693  1774  2168 D AccTypeManager: Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,03-19 12:52:32.713  1774  2168 E ExternalAccountType: Unsupported attribute readOnly
,03-19 12:52:32.743   925   925 W PackageManager: Unable to load service info ResolveInfo{11075e1d com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
03-19 12:52:32.743   925   925 W PackageManager: org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
03-19 12:52:32.743   925   925 W PackageManager: 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:475)
03-19 12:52:32.743   925   925 W PackageManager: 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:331)
03-19 12:52:32.743   925   925 W PackageManager: 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
03-19 12:52:32.743   925   925 W PackageManager: ,	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
03-19 12:52:32.743   925   925 W PackageManager: 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
03-19 12:52:32.743   925   925 W PackageManager: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
03-19 12:52:32.743   925   925 W PackageManager: 	at android.os.Handler.handleCallback(Handler.java:739)
03-19 12:52:32.743   925   925 W PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:95)
03-19 12:52:32.743   925   925 W PackageManager: 	at android.os.Looper.loop(Looper.java:155)
03-19 12:52:32.743   925   925 W PackageManager: 	at com.android.server.SystemServer.run(SystemServer.java:324)
03-19 12:52:32.743   925   925 W PackageManager: 	at com.android.server.SystemServer.main(SystemServer.java:225)
03-19 12:52:32.743   925   925 W PackageManager: 	at java.lang.reflect.Method.invoke(Native Method)
03-19 12:52:32.743   925   925 W PackageManager: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-19 12:52:32.743   925   925 W PackageManager: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
03-19 12:52:32.743   925   925 W PackageManager: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,03-19 12:52:32.783   925  1620 I art     : Explicit concurrent mark sweep GC freed 34608(2MB) AllocSpace objects, 4(80KB) LOS objects, 33% free, 18MB/27MB, paused 1.585ms total 195.710ms,
03-19 12:52:32.783   925  1067 I art     : WaitForGcToComplete blocked for 190.138ms for cause Explicit
03-19 12:52:32.793   925  1621 D PMS     : acquireWL(112245f0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1845 10024 WorkSource{10024 com.google.android.gms}
,03-19 12:52:32.793  1845  2209 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
03-19 12:52:32.793   925  1598 D PMS     : releaseWL(112245f0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,03-19 12:52:32.813   925   925 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,03-19 12:52:32.813   925   925 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 7
03-19 12:52:32.823   925   925 E WifiTrafficPoller:  packet count Tx=55 Rx=59
03-19 12:52:32.823  3844  3844 I RlzPingService: Setting next ping for 1458993152826
,03-19 12:52:32.843   925  1010 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,03-19 12:52:32.843  2172  3229 I CheckinRequestBuilder: Checkin reason type: 8 attempt count: 1
,03-19 12:52:32.853   925  1620 I ActivityManager: Start proc com.htc.home.personalize for broadcast com.htc.home.personalize/.receiver.BootCompleteInitializer: pid=3946 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a,
,03-19 12:52:32.853   925  1164 I ActivityManager: Cannot resolve ContentProvider=com.google.android.wearable.settings
03-19 12:52:32.853  2172  3229 E ActivityThread: Failed to find provider info for com.google.android.wearable.settings
,03-19 12:52:32.873   925  1617 I ActivityManager: Killing 3538:com.futuredial/u0a82 (adj 15): empty #17
,03-19 12:52:32.873   925  1617 D Process : killProcessQuiet, pid=3538
,03-19 12:52:32.873   925  1617 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,03-19 12:52:32.943   925  1067 I art     : Explicit concurrent mark sweep GC freed 6196(293KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 18MB/27MB, paused 1.813ms total 155.931ms
,03-19 12:52:32.953   925  1339 I ActivityManager: Recipient 3538
,03-19 12:52:33.093   925  1179 D TaskPersister: removeObsoleteFile: deleting file=12_task.xml
03-19 12:52:33.093   925  1179 D TaskPersister: removeObsoleteFile: deleting file=12_task_thumbnail.png
,03-19 12:52:33.163  3946  3946 E Personalize.BootComple_: onReceive() + Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.htc.home.personalize/.receiver.BootCompleteInitializer (has extras) },
03-19 12:52:33.163  3946  3946 E Personalize.BootComple_: action android.intent.action.BOOT_COMPLETED
,03-19 12:52:33.163  3946  3946 E Personalize.Utilities: SimpleLauncher not found: com.htc.simplelauncher
03-19 12:52:33.163   925   982 I PackageManager:  setEnabledSetting(), pkgName=com.htc.home.personalize, clsName=com.htc.home.personalize.SimpleModeEntryActivity, state=2, flag=1, pid=3946, uid=1000, userID:0
,03-19 12:52:33.163  3946  3946 E Personalize.BootComple_: initialize: false
03-19 12:52:33.173   925  1164 I PackageManager:  setEnabledSetting(), pkgName=com.htc.simplelauncher, clsName=null, state=2, flag=0, pid=3946, uid=1000, userID:0
,03-19 12:52:33.173  3946  3946 E Personalize.Utilities: setApplicationEnabled IllegalArgumentException com.htc.simplelauncher
03-19 12:52:33.173  2872  2872 V BootCompletedReceiver: ensureAndExecuteUserProfiling: ensureAndExecuteUserProfiling 
,03-19 12:52:33.213  2872  2872 D PeopleYouKnow: receive intent:Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.htc.contacts/.peopleyouknow.PeopleYouKnowReceiver (has extras) },
,03-19 12:52:33.233   925  1617 I ActivityManager: Start proc com.htc.widget.hmsproc2 for broadcast com.htc.rosiewidgets.dataroaming/.DisableWidgetReceiver: pid=3968 uid=10040 gids={50040, 9997, 3002, 3001, 3003} abi=arm64-v8a
,03-19 12:52:33.233   925  1617 D Process : killProcessQuiet, pid=3512,
03-19 12:52:33.233   925  1617 I ActivityManager: Killing 3512:com.android.keychain/1000 (adj 15): empty #17
03-19 12:52:33.233   925  1617 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,03-19 12:52:33.353   925  1339 I ActivityManager: Recipient 3512
,03-19 12:52:33.413   925   925 E WifiDataStallTracker: DATA_MONITOR_POLL true Token 1
,03-19 12:52:33.413   925  3991 D WifiDataStallTracker: updateDataStallInfo: mDataStallTxRxSum={txSum=43 rxSum=34} preTxRxSum={txSum=25 rxSum=19}
,03-19 12:52:33.413   925  3991 D WifiDataStallTracker: updateDataStallInfo: IN/OUT
,03-19 12:52:33.413   925  3991 D WifiDataStallTracker: onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,03-19 12:52:33.473  1528  1820 D AutoSetting: service - mRequestRunnable: screen on delay 10s, request NLP now
03-19 12:52:33.473  1528  1820 D AutoSetting: Util - check NLP state, Allowned:false, Enabled:false
03-19 12:52:33.473  1528  1820 D AutoSetting: service - requestNLP() NetworkLocationProvider not enabled
,03-19 12:52:33.483  3968  3968 V HtcDataRoamingWidget.DisableWidgetReceiver: ACTION_BOOT_COMPLETED
,03-19 12:52:33.493   925   982 I PackageManager:  setEnabledSetting(), pkgName=com.htc.rosiewidgets.dataroaming, clsName=com.htc.rosiewidgets.dataroaming.HtcSettingWidgetProvider, state=1, flag=1, pid=3968, uid=10040, userID:0
,03-19 12:52:33.493  1799  1827 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
,03-19 12:52:33.493  1799  1827 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-19 12:52:33.493  1799  1827 I GLSUser : [GLSUser] Extracting token using key: Auth
,03-19 12:52:33.493  1799  1827 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-19 12:52:33.503  1799  1827 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,03-19 12:52:33.513  3968  3968 V HtcDataStripWidget.DisableWidgetReceiver: ACTION_BOOT_COMPLETED
,03-19 12:52:33.513   925  1769 I PackageManager:  setEnabledSetting(), pkgName=com.htc.rosiewidgets.datastrip, clsName=com.htc.rosiewidgets.datastrip.HtcSettingWidgetProvider, state=1, flag=1, pid=3968, uid=10040, userID:0
,03-19 12:52:33.513   925  1621 D Process : killProcessQuiet, pid=3603
03-19 12:52:33.513   925  1621 I ActivityManager: Killing 3603:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
,03-19 12:52:33.513   925  1621 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,03-19 12:52:33.623   925  1164 I ActivityManager: Recipient 3603,
,03-19 12:52:33.723  1298  1298 D DotMatrix: [EventReceiver] onReceive, version:1.3
03-19 12:52:33.733   925  1143 V AlarmManager: sending alarm PendingIntent{3d9d4be2: PendingIntentRecord{3be45b73 android broadcastIntent}}, i=com.android.server.WifiManager.action.START_SCAN, t=1, cnt=1, w=1458388353603, Int=20000
,03-19 12:52:33.753   925  1769 I ActivityManager: Start proc com.htc.mobiledata:remote for broadcast com.htc.mobiledata/.receivers.ReceiveIntentFromNoPermission: pid=3992 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a,
,03-19 12:52:33.753  1799  1827 W FileUtils: Failed to chmod(/data/data/com.google.android.gms/files): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
,03-19 12:52:33.763  2172  3229 W CheckinRequestBuilder: awaiting user notification for token
,03-19 12:52:33.763  1298  1768 D DotMatrix: [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
03-19 12:52:33.763  1298  1768 D DotMatrix: [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,03-19 12:52:33.773  1221  1221 I RemoteViews: reapply : com.google.android.gms 5 40
,03-19 12:52:33.793   925  1153 E WifiStateMachine: handleMessage: E msg.what=131155,
03-19 12:52:33.793   925  1153 E WifiStateMachine: processMsg: ConnectedState
03-19 12:52:33.793   925  1153 E WifiStateMachine:  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-57 f=2457 sc=60 link=150 tx=5.4, 0.0, 0.0  rx=11.2 bcn=0 [on:0 tx:0 rx:0 period:2929] from screen [on:0 period:-1900526841] gl hn u24 rssi=-52 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
03-19 12:52:33.793   925  1153 E WifiStateMachine: processMsg: L2ConnectedState
,03-19 12:52:33.793   925  1153 E WifiStateMachine:  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-57 f=2457 sc=60 link=150 tx=5.4, 0.0, 0.0  rx=11.2 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1900526840] gl hn u24 rssi=-52 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
03-19 12:52:33.793   925  1153 E WifiStateMachine:  get link layer stats 0
,03-19 12:52:33.793   925  1153 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
03-19 12:52:33.793  1337  1337 D wpa_supplicant: wlan0: Control interface command 'SIGNAL_POLL'
03-19 12:52:33.793  2172  3229 I CheckinRequestBuilder: Classify the device as Phone.
,03-19 12:52:33.803  1337  1337 I wpa_supplicant: environment dirty rate=6 [16][1][0]
03-19 12:52:33.803   925  1153 E WifiStateMachine: fetchRssiLinkSpeedAndFrequencyNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 150
03-19 12:52:33.803   925  1153 E WifiStateMachine: fetchRssiLinkSpeedAndFrequencyNative rssi=-57 linkspeed=150
03-19 12:52:33.803   925  1153 E WifiConfigStore: updateConfiguration freq=2457 BSSID=f4:f2:6d:22:99:3e RSSI=-57 "NG700"WPA_PSK
,03-19 12:52:33.803   925  1153 E WifiStateMachine: calculateWifiScore freq=2457 speed=150 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=10.71 txretriesrate=0.00 rxrate=12.60 userTriggerdPenalty0
03-19 12:52:33.803   925  1153 E WifiStateMachine:  good link -> stuck count =0
03-19 12:52:33.803   925  1153 E WifiStateMachine:  badRSSI count0 lowRSSI count0 --> score 60
03-19 12:52:33.803   925  1153 E WifiStateMachine:  isHighRSSI       ---> score=65
03-19 12:52:33.813   925  1171 D WifiWatchdogStateMachine: RSSI current: 3 new: -57, 3
03-19 12:52:33.813  1221  1221 D WIFI_ICON: updateWifiState: RSSI_CHANGED 3 -> 3
03-19 12:52:33.813   925  1153 E WifiStateMachine: handleMessage: X
03-19 12:52:33.813  1221  1221 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,03-19 12:52:33.823   925   925 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 7
03-19 12:52:33.823   925   925 E WifiTrafficPoller:  packet count Tx=56 Rx=62
,03-19 12:52:33.833   925   974 I ActivityManager: Start proc com.htc.music:mediaplaybackservice for broadcast com.htc.music/.MediaButtonIntentReceiver: pid=4017 uid=10048 gids={50048, 9997, 3003, 1028, 1015, 3002, 3001, 2001, 1023} abi=armeabi-v7a
,03-19 12:52:33.863  2172  3229 I CheckinTask: Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,03-19 12:52:33.863  3992  4038 E SharedPreferencesImpl: Couldn't rename file /data/data/com.htc.mobiledata/shared_prefs/com.htc.mobiledata_preferences.xml to backup file /data/data/com.htc.mobiledata/shared_prefs/com.htc.mobiledata_preferences.xml.bak
,03-19 12:52:33.873  2172  3227 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.gsf/shared_prefs/CheckinService.xml to backup file /data/data/com.google.android.gsf/shared_prefs/CheckinService.xml.bak
,03-19 12:52:33.873   925  1620 D Process : killProcessQuiet, pid=3676
03-19 12:52:33.873   925  1620 I ActivityManager: Killing 3676:com.htc.calendar/u0a10 (adj 15): empty #17
03-19 12:52:33.873   925  1620 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 ,
03-19 12:52:33.873  4017  4017 W ResourcesManager: Asset path '/system/framework/com.htc.musicvismodule.jar' does not exist or contains no resources.
03-19 12:52:33.873  2172  3227 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.gms/shared_prefs/Checkin.xml to backup file /data/data/com.google.android.gms/shared_prefs/Checkin.xml.bak
03-19 12:52:33.873  2172  3227 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.gms/shared_prefs/Checkin.xml to backup file /data/data/com.google.android.gms/shared_prefs/Checkin.xml.bak
,03-19 12:52:33.993   925   982 I ActivityManager: Recipient 3676
,03-19 12:52:34.083  2172  3229 I CheckinService: Checking schedule, now: 1458388354090 next: 1458925185871
,03-19 12:52:34.083  2172  3229 I CheckinService: active receiver: disabled
03-19 12:52:34.083   925  1769 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2172, uid=10024, userID:0
03-19 12:52:34.083  4017  4017 D MediaSessionHelper: Attempting to get helper with context android.app.ReceiverRestrictedContext@36069612
,03-19 12:52:34.083   925  1769 F PackageManager: Unable to backup user packages state file, current changes will be lost at reboot,
,03-19 12:52:34.093   925  1016 E DropBoxManagerService: Can't write: system_server_wtf
03-19 12:52:34.093   925  1016 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop27.tmp: open failed: EROFS (Read-only file system)
03-19 12:52:34.093   925  1016 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
03-19 12:52:34.093   925  1016 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
03-19 12:52:34.093   925  1016 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
03-19 12:52:34.093   925  1016 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
03-19 12:52:34.093   925  1016 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
03-19 12:52:34.093   925  1016 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$21.run(ActivityManagerService.java:12658)
03-19 12:52:34.093   925  1016 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12665)
03-19 12:52:34.093   925  1016 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12469)
03-19 12:52:34.093   925  1016 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12441)
03-19 12:52:34.093   925  1016 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
03-19 12:52:34.093   925  1016 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
03-19 12:52:34.093   925  1016 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:155)
03-19 12:52:34.093   925  1016 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-19 12:52:34.093   925  1016 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
03-19 12:52:34.093   925  1016 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
03-19 12:52:34.093   925  1016 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
03-19 12:52:34.093   925  1016 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
03-19 12:52:34.093   925  1016 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
03-19 12:52:34.093   925  1016 E DropBoxManagerService: 	... 13 more
,03-19 12:52:34.093   925  1374 D MediaSessionService: Created session for package com.htc.music with tag MediaSessionHelper-com.htc.music
03-19 12:52:34.093   925  1621 D PMS     : releaseWL(14987c67): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10024 com.google.android.gms}
03-19 12:52:34.093   925  1339 D Process : killProcessQuiet, pid=2172
03-19 12:52:34.093   925  1339 I ActivityManager: Killing 2172:com.google.android.gms/u0a24 (adj 15): empty #17
03-19 12:52:34.093   925  1339 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
03-19 12:52:34.103  4017  4017 D MediaSessionHelper: addMediaButtonListener added PendingIntent{e3a77e0: android.os.BinderProxy@267391e3}
,03-19 12:52:34.143  1624  2106 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true,
03-19 12:52:34.143  1624  2106 I Prism.ItemManager: loadItems() com.htc.launcher.pageview.WidgetManager@21be4e74 +
03-19 12:52:34.143  1624  2106 I Prism.WidgetManager: onLoadItems() +,
,03-19 12:52:34.173   925  1617 I ActivityManager: Recipient 2172
03-19 12:52:34.173   925  1155 D WifiService: Client connection lost with reason: 4
,03-19 12:52:34.183  1624  2106 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,03-19 12:52:34.203   925  1339 D Process : killProcessQuiet, pid=3317,
,03-19 12:52:34.203   925  1339 I ActivityManager: Killing 3317:com.google.android.gms.unstable/u0a24 (adj 15): empty #18
03-19 12:52:34.203   925  1339 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,03-19 12:52:34.343   925  1374 I ActivityManager: Recipient 3317
,03-19 12:52:34.353  1624  2106 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.,
,03-19 12:52:34.433   925  1339 I ActivityManager: Start proc com.htc.musicenhancer for broadcast com.htc.musicenhancer/.cronus.CronusReceiver: pid=4040 uid=10049 gids={50049, 9997, 1028, 1015, 3003} abi=armeabi-v7a
03-19 12:52:34.433   925  1339 D Process : killProcessQuiet, pid=3731
03-19 12:52:34.433   925  1339 I ActivityManager: Killing 3731:com.htc.demoflopackageinstaller/u0a16 (adj 15): empty #17
03-19 12:52:34.433   925  1339 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,03-19 12:52:34.453   434   434 I art     : Explicit concurrent mark sweep GC freed 8688(369KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 398us total 25.409ms,
,03-19 12:52:34.473   434   434 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 314us total 20.774ms
,03-19 12:52:34.493   434   434 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 309us total 19.629ms
,03-19 12:52:34.513  1624  2106 W asset   : Copying FileAsset 0x559fcf1450 (zip:/data/app/com.gameloft.android.gdc-2/base.apk:/resources.arsc) to buffer size 405676 to make it aligned.,

```
