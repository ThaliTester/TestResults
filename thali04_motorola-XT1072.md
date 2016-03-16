#### Test 63012666d6bb2e8_thali04_motorola-XT1072 Logs


```
--------- beginning of main
03-16 14:31:46.715  4164  4164 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
03-16 14:31:46.716  4164  4164 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
03-16 14:31:46.746  4182  4182 I CalendarProvider2: Created com.android.providers.calendar.CalendarAlarmManager@1c8fb774(com.android.providers.calendar.CalendarProvider2@acea49d)
--------- beginning of system
03-16 14:31:46.783   882  1596 I ActivityManager: Killing 3155:com.android.defcontainer/u0a10 (adj 15): empty #7
,03-16 14:31:46.848  4034  4120 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-16 14:31:46.849  4164  4203 D NativeLibraryUtils: Install completed successfully. count=14 extracted=0
03-16 14:31:46.924   882  1570 W libprocessgroup: failed to open /acct/uid_10010/pid_3155/cgroup.procs: No such file or directory
03-16 14:31:46.942   882  1224 V AlarmManager: send {3d18db63, *walarm*:com.google.android.intent.action.GCM_RECONNECT}
03-16 14:31:46.944  4017  4091 I Gmail   : getAccountsCursor
03-16 14:31:46.988   294   294 D WVCdm   : Instantiating CDM.
03-16 14:31:46.989   294   981 I WVCdm   : CdmEngine::OpenSession
03-16 14:31:46.989   294   981 I WVCdm   : Level3 Library Sep 25 2014 17:10:03
03-16 14:31:47.011   294   981 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
03-16 14:31:47.043   294   981 D DrmWidevineDash: OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
03-16 14:31:47.043   294   981 D DrmWidevineDash: Service_Initialize: starts!
03-16 14:31:47.043   294   981 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
03-16 14:31:47.044   294   981 D QSEECOMAPI: : App is not loaded in QSEE
03-16 14:31:47.044   294   981 E QSEECOMAPI: : Error::Cannot open the file /vendor/firmware/widevine.mdt
03-16 14:31:47.044   294   981 E QSEECOMAPI: : Error::Loading image failed with ret = -1
03-16 14:31:47.045   294   981 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
03-16 14:31:47.045   294   981 D QSEECOMAPI: : App is not loaded in QSEE
03-16 14:31:47.045   294   981 E QSEECOMAPI: : Error::Cannot open the file /system/etc/firmware/widevine.mdt
03-16 14:31:47.045   294   981 E QSEECOMAPI: : Error::Loading image failed with ret = -1
03-16 14:31:47.046   294   981 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
03-16 14:31:47.046   294   981 D QSEECOMAPI: : App is not loaded in QSEE
03-16 14:31:47.088   294   981 D QSEECOMAPI: : Loaded image: APP id = 3
03-16 14:31:47.090   294   981 D DrmWidevineDash: Service_Initialize: ends! returns 0
03-16 14:31:47.090   294   981 D DrmWidevineDash: OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb502a000
03-16 14:31:47.090   294   981 E DrmWidevineDash: sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb502a000
03-16 14:31:47.102   294   981 D DrmWidevineDash: OEMCrypto_Initialize: ends! returns 0
03-16 14:31:47.102   294   981 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
03-16 14:31:47.103   294   981 D DrmWidevineDash: hlos api version =  9
03-16 14:31:47.103   294   981 D DrmWidevineDash: tz api version =  8
03-16 14:31:47.103   294   981 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 9
03-16 14:31:47.103   294   981 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: starts!
03-16 14:31:47.118   294   981 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: ends! returns 0
03-16 14:31:47.118   294   981 D WVCdm   : OEMCrypto_Initialize Level 1 success. I will use level 1.
03-16 14:31:47.118   294   981 D DrmWidevineDash: OEMCrypto_OpenSession: starts! SID=0xb54f8960
03-16 14:31:47.118   294   981 D DrmWidevineDash: OEMCrypto_OpenSession SID = 1
03-16 14:31:47.118   294   981 D DrmWidevineDash: OEMCrypto_OpenSession: ends! returns 0
03-16 14:31:47.118   294   981 D DrmWidevineDash: OEMCrypto_GetRandom: starts! randomData=0xb8d371d0, dataLength=8
03-16 14:31:47.119   294   981 D DrmWidevineDash: OEMCrypto_GetRandom: ends! returns 0
03-16 14:31:47.123   294   981 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb8cb7490, wrapped_rsa_key_length=1280
03-16 14:31:47.126   294   981 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: ends! returns 0
03-16 14:31:47.126   294   981 I WVCdm   : CdmEngine::QueryKeyControlInfo
03-16 14:31:47.126   294   980 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
03-16 14:31:47.126   294   980 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
03-16 14:31:47.127   294   980 I WVCdm   : CdmEngine::GenerateKeyRequest
03-16 14:31:47.127   294   980 D DrmWidevineDash: OEMCrypto_GetDeviceID: starts! deviceID=0xb8e05730, idLength=0xb55f8730
03-16 14:31:47.135   294   980 D DrmWidevineDash: OEMCrypto_GetDeviceID: ends! returns 0
03-16 14:31:47.135   294   980 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: starts!
03-16 14:31:47.136   294   980 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: is_supported = 1
03-16 14:31:47.136   294   980 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: wv_app_version = 25
03-16 14:31:47.136   294   980 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: ends! returns 0x0
03-16 14:31:47.136   294   980 D DrmWidevineDash: OEMCrypto_GetHDCPCapability: starts!
03-16 14:31:47.136   294   980 D DrmWidevineDash: OEMCrypto_GetHDCPCapability: ends! returns 0x0
03-16 14:31:47.136   294   980 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
03-16 14:31:47.136   294   980 D DrmWidevineDash: hlos api version =  9
03-16 14:31:47.136   294   980 D DrmWidevineDash: tz api version =  8
03-16 14:31:47.136   294   980 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 9
03-16 14:31:47.136   294   980 D DrmWidevineDash: OEMCrypto_GenerateNonce: starts! SID=1
03-16 14:31:47.137   294   980 D DrmWidevineDash: OEMCrypto_GenerateNonce: ends! returns 0
03-16 14:31:47.137   294   980 D WVCdm   : PrepareKeyRequest: nonce=2666685009
03-16 14:31:47.137   294   980 D DrmWidevineDash: OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb8dfb890
03-16 14:31:47.137   294   980 D DrmWidevineDash: message_length=1591, signature=0xb8dfbed0, signature_length=3042936596
03-16 14:31:47.141  1717  1717 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
03-16 14:31:47.195  4164  4178 I art     : Background partial concurrent mark sweep GC freed 16295(998KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 10MB/16MB, paused 8.287ms total 66.624ms
03-16 14:31:47.235  2562  3975 W Settings: Setting dropbox_quota_kb has moved from android.provider.Settings.System to android.provider.Settings.Global
03-16 14:31:47.236  2562  3975 W Settings: Setting dropbox_quota_kb has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
03-16 14:31:47.236  2562  3975 W Settings: Setting dropbox_max_files has moved from android.provider.Settings.System to android.provider.Settings.Global
03-16 14:31:47.236  2562  3975 W Settings: Setting dropbox_max_files has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
03-16 14:31:47.236  2562  3975 I global frequency: BcsTimer.setTimer(86400000, 86400000)
03-16 14:31:47.237  2562  3975 D Checkin : publish the event [tag = MOT_CHECKIN event name = LOG]
03-16 14:31:47.238  1461  4188 D Central_PollingManager: registerApp(): Checkin
03-16 14:31:47.238  1461  4188 D Central_PollingManager: registerApp(): Checkin already registered.
03-16 14:31:47.239  1461  2696 D Central_PollingManager: modifyApp(): Checkin
03-16 14:31:47.239  1461  2696 D Central_PollingManager: calculateShortestInterval(): shortest interval is 21600000
03-16 14:31:47.243  2562  3975 W MotorolaSettings: no such table to get this name = privacy_droid_blast
03-16 14:31:47.243  2562  3975 W System.err: java.lang.Exception
03-16 14:31:47.243  2562  3975 W System.err: 	at com.motorola.android.provider.MotorolaSettings.getString(MotorolaSettings.java:290)
03-16 14:31:47.243  2562  3975 W System.err: 	at com.motorola.android.provider.MotorolaSettings.getInt(MotorolaSettings.java:328)
03-16 14:31:47.243  2562  3975 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
03-16 14:31:47.243  2562  3975 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-16 14:31:47.243  2562  3975 W System.err: 	at com.motorola.ccc.checkin.MotorolaSettings.getInt(MotorolaSettings.java:106)
03-16 14:31:47.243  2562  3975 W System.err: 	at com.motorola.ccc.checkin.PrivacyHelper.readPrivacy(PrivacyHelper.java:413)
03-16 14:31:47.244  2562  3975 W System.err: 	at com.motorola.ccc.checkin.PrivacyHelper.reconfigurePrivacy(PrivacyHelper.java:160)
03-16 14:31:47.244  2562  3975 W System.err: 	at com.motorola.ccc.checkin.BcsConfigAndroid.handleConfigChange(BcsConfigAndroid.java:996)
03-16 14:31:47.244  2562  3975 W System.err: 	at com.motorola.ccc.checkin.BcsConfigAndroid.update(BcsConfigAndroid.java:518)
03-16 14:31:47.244  2562  3975 W System.err: 	at com.motorola.ccc.checkin.BcsCore.doConfig(BcsCore.java:662)
03-16 14:31:47.244  2562  3975 W System.err: 	at com.motorola.ccc.checkin.BcsCore.handleEvent(BcsCore.java:332)
03-16 14:31:47.244  2562  3975 W System.err: 	at com.motorola.ccc.checkin.BcsPlatformAndroid.handleCceSendSettingsResponse(BcsPlatformAndroid.java:432)
03-16 14:31:47.244  2562  3975 W System.err: 	at com.motorola.ccc.checkin.BcsPlatformAndroid.onReceiveActions(BcsPlatformAndroid.java:403)
03-16 14:31:47.244  2562  3975 W System.err: 	at com.motorola.ccc.checkin.BcsPlatformAndroid.access$000(BcsPlatformAndroid.java:87)
03-16 14:31:47.244  2562  3975 W System.err: 	at com.motorola.ccc.checkin.BcsPlatformAndroid$1.run(BcsPlatformAndroid.java:295)
03-16 14:31:47.244  2562  3975 W System.err: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-16 14:31:47.244  2562  3975 W System.err: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-16 14:31:47.244  2562  3975 W System.err: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-16 14:31:47.244  2562  3975 W System.err: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-16 14:31:47.244  2562  3975 W System.err: 	at java.lang.Thread.run(Thread.java:818)
03-16 14:31:47.247  2562  3975 I global frequency: BcsConfigAndroid:updateAllowedEventTagsForPrivacyProfile Blacklisted tags: (DUMMY_TAG:1416552400)
03-16 14:31:47.257  2562  3975 D Checkin : publish the event [tag = MOT_CHECKIN event name = LOG]
03-16 14:31:47.257  2562  3975 I global frequency: BcsConfigAndroid:updateAllowedEventTagsForPrivacyProfile new whitelisted checkin event tags: MOT_OTA:LOG,MOT_PRIVACY_PROFILE,DEV_ATTRIBS,CHECKIN_SUCCESS,MOT_CCE_STATS:CS_Notif_FFA,DEVICE_PROPERTIES,CHECKIN_FAILURE
03-16 14:31:47.259  2562  3975 D Checkin : publish the event [tag = MOT_CHECKIN event name = LOG]
03-16 14:31:47.262  2562  3975 D Checkin : publish the event [tag = MOT_PRIVACY_PROFILE event name = PRIVACY]
03-16 14:31:47.311  4213  4213 D AndroidRuntime: 
03-16 14:31:47.311  4213  4213 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
03-16 14:31:47.314  4213  4213 D AndroidRuntime: CheckJNI is OFF
03-16 14:31:47.332  2984  3007 D Checkin : publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
03-16 14:31:47.357   294   980 D DrmWidevineDash: OEMCrypto_GenerateRSASignature returns 0
03-16 14:31:47.358   294   294 I WVCdm   : CdmEngine::CloseSession
03-16 14:31:47.358   294   294 D DrmWidevineDash: OEMCrypto_CloseSession: starts! SID=1
03-16 14:31:47.358   294   294 D DrmWidevineDash: OEMCrypto_CloseSession: ends! returns 0
03-16 14:31:47.358   294   294 I WVCdm   : L3 Terminate.
03-16 14:31:47.358   294   294 D DrmWidevineDash: OEMCrypto_Terminate: starts!
03-16 14:31:47.358   294   294 D DrmWidevineDash: Service_Uninitialize: starts!
03-16 14:31:47.358   294   294 D QSEECOMAPI: : QSEECom_dealloc_memory 
03-16 14:31:47.358   294   294 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 3
03-16 14:31:47.359   294   294 D DrmWidevineDash: Service_Uninitialize: ends! returns 0x0
03-16 14:31:47.359   294   294 D DrmWidevineDash: OEMCrypto_Terminate: ends! returns 0
03-16 14:31:47.576   294   981 I WVCdm   : CdmEngine::OpenSession
03-16 14:31:47.576   294   981 I WVCdm   : Level3 Library Sep 25 2014 17:10:03
03-16 14:31:47.578   294   981 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
03-16 14:31:47.582  4213  4213 D AndroidRuntime: Calling main entry com.android.commands.am.Am
03-16 14:31:47.589   882  1596 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
03-16 14:31:47.604   294   981 D DrmWidevineDash: OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
03-16 14:31:47.604   294   981 D DrmWidevineDash: Service_Initialize: starts!
03-16 14:31:47.604   294   981 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
03-16 14:31:47.608   294   981 D QSEECOMAPI: : App is not loaded in QSEE
03-16 14:31:47.608   294   981 E QSEECOMAPI: : Error::Cannot open the file /vendor/firmware/widevine.mdt
03-16 14:31:47.608   294   981 E QSEECOMAPI: : Error::Loading image failed with ret = -1
03-16 14:31:47.609   294   981 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
03-16 14:31:47.609   294   981 D QSEECOMAPI: : App is not loaded in QSEE
03-16 14:31:47.609   294   981 E QSEECOMAPI: : Error::Cannot open the file /system/etc/firmware/widevine.mdt
03-16 14:31:47.609   294   981 E QSEECOMAPI: : Error::Loading image failed with ret = -1
03-16 14:31:47.609   294   981 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
03-16 14:31:47.609   294   981 D QSEECOMAPI: : App is not loaded in QSEE
03-16 14:31:47.640   294   981 D QSEECOMAPI: : Loaded image: APP id = 3
03-16 14:31:47.641   294   981 D DrmWidevineDash: Service_Initialize: ends! returns 0
03-16 14:31:47.641   294   981 D DrmWidevineDash: OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb502a000
03-16 14:31:47.641   294   981 E DrmWidevineDash: sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb502a000
03-16 14:31:47.644   278  1201 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (578 us)
03-16 14:31:47.647   294   981 D DrmWidevineDash: OEMCrypto_Initialize: ends! returns 0
03-16 14:31:47.647   294   981 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
03-16 14:31:47.647   294   981 D DrmWidevineDash: hlos api version =  9
03-16 14:31:47.647   294   981 D DrmWidevineDash: tz api version =  8
03-16 14:31:47.647   294   981 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 9
03-16 14:31:47.647   294   981 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: starts!
03-16 14:31:47.650  2562  3975 W Settings: Setting dropbox_quota_kb has moved from android.provider.Settings.System to android.provider.Settings.Global
03-16 14:31:47.652  2562  3975 W Settings: Setting dropbox_quota_kb has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
03-16 14:31:47.652  2562  3975 W Settings: Setting dropbox_max_files has moved from android.provider.Settings.System to android.provider.Settings.Global
03-16 14:31:47.656  2562  3975 W Settings: Setting dropbox_max_files has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
03-16 14:31:47.657   294   981 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: ends! returns 0
03-16 14:31:47.657   294   981 D WVCdm   : OEMCrypto_Initialize Level 1 success. I will use level 1.
03-16 14:31:47.657   294   981 D DrmWidevineDash: OEMCrypto_OpenSession: starts! SID=0xb54f8960
03-16 14:31:47.657   294   981 D DrmWidevineDash: OEMCrypto_OpenSession SID = 1
03-16 14:31:47.657   294   981 D DrmWidevineDash: OEMCrypto_OpenSession: ends! returns 0
03-16 14:31:47.657   294   981 D DrmWidevineDash: OEMCrypto_GetRandom: starts! randomData=0xb8dae130, dataLength=8
03-16 14:31:47.658   294   981 D DrmWidevineDash: OEMCrypto_GetRandom: ends! returns 0
03-16 14:31:47.658   294   981 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb8cb7490, wrapped_rsa_key_length=1280
03-16 14:31:47.661   294   981 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: ends! returns 0
03-16 14:31:47.661   294   981 I WVCdm   : CdmEngine::QueryKeyControlInfo
03-16 14:31:47.663  2562  3975 W MotorolaSettings: no such table to get this name = privacy_droid_blast
03-16 14:31:47.663  2562  3975 W System.err: java.lang.Exception
03-16 14:31:47.663   294  1456 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
03-16 14:31:47.663   294  1456 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
03-16 14:31:47.663   294  1456 I WVCdm   : CdmEngine::GenerateKeyRequest
03-16 14:31:47.663  2562  3975 W System.err: 	at com.motorola.android.provider.MotorolaSettings.getString(MotorolaSettings.java:290)
03-16 14:31:47.663  2562  3975 W System.err: 	at com.motorola.android.provider.MotorolaSettings.getInt(MotorolaSettings.java:328)
03-16 14:31:47.663  2562  3975 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
03-16 14:31:47.663   294  1456 D DrmWidevineDash: OEMCrypto_GetDeviceID: starts! deviceID=0xb8e05770, idLength=0xb1433730
03-16 14:31:47.663  2562  3975 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-16 14:31:47.663  2562  3975 W System.err: 	at com.motorola.ccc.checkin.MotorolaSettings.getInt(MotorolaSettings.java:106)
03-16 14:31:47.663  2562  3975 W System.err: 	at com.motorola.ccc.checkin.PrivacyHelper.readPrivacy(PrivacyHelper.java:413)
03-16 14:31:47.663  2562  3975 W System.err: 	at com.motorola.ccc.checkin.PrivacyHelper.reconfigurePrivacy(PrivacyHelper.java:160)
03-16 14:31:47.663  2562  3975 W System.err: 	at com.motorola.ccc.checkin.BcsConfigAndroid.handleConfigChange(BcsConfigAndroid.java:996)
03-16 14:31:47.663  2562  3975 W System.err: 	at com.motorola.ccc.checkin.BcsConfigAndroid.update(BcsConfigAndroid.java:518)
03-16 14:31:47.663  2562  3975 W System.err: 	at com.motorola.ccc.checkin.BcsCore.doConfig(BcsCore.java:662)
03-16 14:31:47.663  2562  3975 W System.err: 	at com.motorola.ccc.checkin.BcsCore.handleEvent(BcsCore.java:332)
03-16 14:31:47.663  2562  3975 W System.err: 	at com.motorola.ccc.checkin.BcsPlatformAndroid.handleCceSendSettingsResponse(BcsPlatformAndroid.java:432)
03-16 14:31:47.663  2562  3975 W System.err: 	at com.motorola.ccc.checkin.BcsPlatformAndroid.onReceiveActions(BcsPlatformAndroid.java:403)
03-16 14:31:47.663  2562  3975 W System.err: 	at com.motorola.ccc.checkin.BcsPlatformAndroid.access$000(BcsPlatformAndroid.java:87)
03-16 14:31:47.664  2562  3975 W System.err: 	at com.motorola.ccc.checkin.BcsPlatformAndroid$1.run(BcsPlatformAndroid.java:295)
03-16 14:31:47.664  2562  3975 W System.err: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-16 14:31:47.664  2562  3975 W System.err: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-16 14:31:47.664  2562  3975 W System.err: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-16 14:31:47.664  2562  3975 W System.err: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-16 14:31:47.664  2562  3975 W System.err: 	at java.lang.Thread.run(Thread.java:818)
03-16 14:31:47.667  2562  3975 I global frequency: BcsConfigAndroid:updateAllowedEventTagsForPrivacyProfile Blacklisted tags: (DUMMY_TAG:1416552400)
03-16 14:31:47.670   294  1456 D DrmWidevineDash: OEMCrypto_GetDeviceID: ends! returns 0
03-16 14:31:47.670  2562  3975 D Checkin : publish the event [tag = MOT_CHECKIN event name = LOG]
03-16 14:31:47.670   294  1456 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: starts!
03-16 14:31:47.671   294  1456 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: is_supported = 1
03-16 14:31:47.671   294  1456 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: wv_app_version = 25
03-16 14:31:47.671   294  1456 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: ends! returns 0x0
03-16 14:31:47.671   294  1456 D DrmWidevineDash: OEMCrypto_GetHDCPCapability: starts!
03-16 14:31:47.671   294  1456 D DrmWidevineDash: OEMCrypto_GetHDCPCapability: ends! returns 0x0
03-16 14:31:47.671   294  1456 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
03-16 14:31:47.671   294  1456 D DrmWidevineDash: hlos api version =  9
03-16 14:31:47.671   294  1456 D DrmWidevineDash: tz api version =  8
03-16 14:31:47.671   294  1456 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 9
03-16 14:31:47.671   294  1456 D DrmWidevineDash: OEMCrypto_GenerateNonce: starts! SID=1
03-16 14:31:47.672   294  1456 D DrmWidevineDash: OEMCrypto_GenerateNonce: ends! returns 0
03-16 14:31:47.672   294  1456 D WVCdm   : PrepareKeyRequest: nonce=544783047
03-16 14:31:47.672   294  1456 D DrmWidevineDash: OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb8dfb890
03-16 14:31:47.672   294  1456 D DrmWidevineDash: message_length=1622, signature=0xb8dfbef0, signature_length=2973972244
03-16 14:31:47.672  2562  3975 I global frequency: BcsConfigAndroid:updateAllowedEventTagsForPrivacyProfile new whitelisted checkin event tags: MOT_OTA:LOG,MOT_PRIVACY_PROFILE,DEV_ATTRIBS,CHECKIN_SUCCESS,MOT_CCE_STATS:CS_Notif_FFA,DEVICE_PROPERTIES,CHECKIN_FAILURE
03-16 14:31:47.673  2562  3975 D Checkin : publish the event [tag = MOT_CHECKIN event name = LOG]
03-16 14:31:47.675  2562  3975 D Checkin : publish the event [tag = MOT_PRIVACY_PROFILE event name = PRIVACY]
03-16 14:31:47.683  1461  3867 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
03-16 14:31:47.686  4213  4213 D AndroidRuntime: Shutting down VM
03-16 14:31:47.723   882  1571 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4241 uid=10109 gids={50109, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
03-16 14:31:47.811  2562  3975 W Settings: Setting dropbox_quota_kb has moved from android.provider.Settings.System to android.provider.Settings.Global
03-16 14:31:47.812  2562  3975 W Settings: Setting dropbox_quota_kb has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
03-16 14:31:47.812  2562  3975 W Settings: Setting dropbox_max_files has moved from android.provider.Settings.System to android.provider.Settings.Global
03-16 14:31:47.817  2562  3975 W Settings: Setting dropbox_max_files has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
03-16 14:31:47.846   882  1501 I ActivityManager: Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=4259 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-16 14:31:47.878   294  1456 D DrmWidevineDash: OEMCrypto_GenerateRSASignature returns 0
03-16 14:31:47.882  1461  3867 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
03-16 14:31:47.883   294   980 I WVCdm   : CdmEngine::CloseSession
03-16 14:31:47.883   294   980 D DrmWidevineDash: OEMCrypto_CloseSession: starts! SID=1
03-16 14:31:47.883   294   980 D DrmWidevineDash: OEMCrypto_CloseSession: ends! returns 0
03-16 14:31:47.883   294   980 I WVCdm   : L3 Terminate.
03-16 14:31:47.883   294   980 D DrmWidevineDash: OEMCrypto_Terminate: starts!
03-16 14:31:47.883   294   980 D DrmWidevineDash: Service_Uninitialize: starts!
03-16 14:31:47.883   294   980 D QSEECOMAPI: : QSEECom_dealloc_memory 
03-16 14:31:47.883   294   980 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 3
03-16 14:31:47.884   294   980 D DrmWidevineDash: Service_Uninitialize: ends! returns 0x0
03-16 14:31:47.884   294   980 D DrmWidevineDash: OEMCrypto_Terminate: ends! returns 0
,03-16 14:31:47.931  4182  4182 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
03-16 14:31:47.931  4182  4182 W ContentResolver: Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,03-16 14:31:48.050  4277  4277 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=34 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,03-16 14:31:48.070  4259  4259 I MusicStore: Database version: 120
,03-16 14:31:48.103  4241  4241 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,03-16 14:31:48.172   277   453 E Vold    : Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
03-16 14:31:48.172   277   453 W Vold    : Returning OperationFailed - no handler for errno 0
,03-16 14:31:48.172  4241  4241 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 9147-9150)
,03-16 14:31:48.173  4241  4241 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-16 14:31:48.175  4259  4259 W ContextImpl: Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,03-16 14:31:48.223  4241  4241 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {36fe0ce3}
,03-16 14:31:48.229  4241  4241 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-16 14:31:48.232  4241  4241 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,03-16 14:31:48.267  4241  4241 I BrowserStartupController: Initializing chromium process, singleProcess=true
03-16 14:31:48.268  4241  4241 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-16 14:31:48.274  4241  4241 E SysUtils: ApplicationContext is null in ApplicationStatus
,03-16 14:31:48.367   277   453 E Vold    : Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
03-16 14:31:48.368   277   453 W Vold    : Returning OperationFailed - no handler for errno 0
,03-16 14:31:48.369  4259  4259 W ContextImpl: Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,03-16 14:31:48.372   278   278 I SFPerfTracer:      triggers: (rate: 13:572) (compose: 0:1) (post: 0:1) (render: 0:2) (6:841 frames) (7:919)
03-16 14:31:48.372   278   278 D SFPerfTracer:        layers: (5:12) (FocusedStackFrame (0xb8987088): 0:11)* (DimLayer (0xb89e4aa0): 0:6) (com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (0xb89e9428): 0:26)- (StatusBar (0xb89fa910): 0:129) (NavigationBar (0xb89fcd00): 0:39) (com.android.systemui.ImageWallpaper (0xb8a00b90): 0:35)* (Starting com.motorola.ccc.ota (0xb8a0e540): 0:37)- (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity (0xb89e9418): 7:37) (Starting com.test.thalitest (0xb8a0e540): 7:12) 
,03-16 14:31:48.375   277   453 E Vold    : Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
03-16 14:31:48.375   277   453 W Vold    : Returning OperationFailed - no handler for errno 0
,03-16 14:31:48.376  4241  4241 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,03-16 14:31:48.377  4259  4259 W ContextImpl: Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,03-16 14:31:48.382  1291  1291 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
03-16 14:31:48.382  1291  1291 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-16 14:31:48.384  4241  4241 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-16 14:31:48.384  4241  4241 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,03-16 14:31:48.385  4241  4241 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
03-16 14:31:48.385  4241  4241 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.01.03
03-16 14:31:48.385  4241  4241 I Adreno-EGL: Build Date: 10/28/14 Tue
03-16 14:31:48.385  4241  4241 I Adreno-EGL: Local Branch: 
03-16 14:31:48.385  4241  4241 I Adreno-EGL: Remote Branch: quic/l_LNX.LA.3.6
03-16 14:31:48.385  4241  4241 I Adreno-EGL: Local Patches: NONE
03-16 14:31:48.385  4241  4241 I Adreno-EGL: Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,03-16 14:31:48.388  4277  4277 I dex2oat : dex2oat took 337.794ms (threads: 4)
,03-16 14:31:48.413  4164  4179 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
03-16 14:31:48.413  4164  4179 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.01.03
03-16 14:31:48.413  4164  4179 I Adreno-EGL: Build Date: 10/28/14 Tue
03-16 14:31:48.413  4164  4179 I Adreno-EGL: Local Branch: 
03-16 14:31:48.413  4164  4179 I Adreno-EGL: Remote Branch: quic/l_LNX.LA.3.6
03-16 14:31:48.413  4164  4179 I Adreno-EGL: Local Patches: NONE
03-16 14:31:48.413  4164  4179 I Adreno-EGL: Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,03-16 14:31:48.425  3826  3841 I art     : Explicit concurrent mark sweep GC freed 2931(114KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/9MB, paused 602us total 28.927ms
,03-16 14:31:48.450  4259  4259 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-16 14:31:48.451  4259  4259 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-16 14:31:48.461   882  1224 V AlarmManager: send {14eae9ec, *walarm*:com.android.providers.calendar.intent.CalendarProvider2}
,03-16 14:31:48.482   882  1133 D BluetoothManagerService: Message: 20
03-16 14:31:48.482   882  1133 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@25e68a84:true
,03-16 14:31:48.510  4259  4259 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,03-16 14:31:48.563  4164  4179 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
03-16 14:31:48.563  4164  4179 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.01.03
03-16 14:31:48.563  4164  4179 I Adreno-EGL: Build Date: 10/28/14 Tue
03-16 14:31:48.563  4164  4179 I Adreno-EGL: Local Branch: 
03-16 14:31:48.563  4164  4179 I Adreno-EGL: Remote Branch: quic/l_LNX.LA.3.6
03-16 14:31:48.563  4164  4179 I Adreno-EGL: Local Patches: NONE
03-16 14:31:48.563  4164  4179 I Adreno-EGL: Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,03-16 14:31:48.572  4259  4259 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
03-16 14:31:48.573  4259  4259 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3df29fce: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
03-16 14:31:48.573  4259  4259 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
03-16 14:31:48.573  4259  4259 D AndroidMusic: GMSCore installation verified
,03-16 14:31:48.583  4259  4259 I ConfigStore: Config Database version: 1
,03-16 14:31:48.644  4241  4241 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-16 14:31:48.658  4241  4241 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,03-16 14:31:48.672  4241  4241 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,03-16 14:31:48.679  4241  4241 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-16 14:31:48.679  4241  4241 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-16 14:31:48.714  4259  4259 I MediaRouter: Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,03-16 14:31:48.718  4259  4259 V MusicLeanback: onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,03-16 14:31:48.732  4259  4259 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,03-16 14:31:48.749  4241  4318 D OpenGLRenderer: Render dirty regions requested: true
,03-16 14:31:48.759  4241  4241 D Atlas   : Validating map...
,03-16 14:31:48.765  4241  4303 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,03-16 14:31:48.782  4259  4259 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,03-16 14:31:48.803   278   745 I SFPerfTracer:      triggers: (rate: 0:0) (0 sw vsyncs) (0 skipped) (44:219 vsyncs) (46:938)
,03-16 14:31:48.809  4241  4318 I OpenGLRenderer: Initialized EGL, version 1.4
,03-16 14:31:48.816  4241  4318 D OpenGLRenderer: Enabling debug mode 0
,03-16 14:31:48.838   882  1516 I ActivityManager: Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=4323 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-16 14:31:48.855   306   306 I art     : Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 292us total 21.193ms
,03-16 14:31:48.875   306   306 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 287us total 20.276ms
,03-16 14:31:48.887   882  1134 I LaunchCheckinHandler: Displayed com.test.thalitest/.MainActivity,cp,ca,1195
,03-16 14:31:48.887   882  1134 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +1s195ms
,03-16 14:31:48.896  1416  1416 I Keyboard.Facilitator: onFinishInput()
,03-16 14:31:48.897   306   306 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 259us total 20.916ms
,03-16 14:31:48.900  4259  4259 I GHttpClientFactory: Using our fixed implementation of GMSCore's GoogleHttpClient
,03-16 14:31:48.911  4164  4179 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
03-16 14:31:48.911  4164  4179 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.01.03
03-16 14:31:48.911  4164  4179 I Adreno-EGL: Build Date: 10/28/14 Tue
03-16 14:31:48.911  4164  4179 I Adreno-EGL: Local Branch: 
03-16 14:31:48.911  4164  4179 I Adreno-EGL: Remote Branch: quic/l_LNX.LA.3.6
03-16 14:31:48.911  4164  4179 I Adreno-EGL: Local Patches: NONE
03-16 14:31:48.911  4164  4179 I Adreno-EGL: Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
03-16 14:31:48.913  4259  4259 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,03-16 14:31:48.967   882  1596 I ActivityManager: Killing 4063:com.google.android.gm.exchange/u0a60 (adj 15): empty #7
,03-16 14:31:48.990  4164  4179 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
03-16 14:31:48.990  4164  4179 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.01.03
03-16 14:31:48.990  4164  4179 I Adreno-EGL: Build Date: 10/28/14 Tue
03-16 14:31:48.990  4164  4179 I Adreno-EGL: Local Branch: 
03-16 14:31:48.990  4164  4179 I Adreno-EGL: Remote Branch: quic/l_LNX.LA.3.6
03-16 14:31:48.990  4164  4179 I Adreno-EGL: Local Patches: NONE
03-16 14:31:48.990  4164  4179 I Adreno-EGL: Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,03-16 14:31:49.034  4241  4345 E Adreno-ES20: <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
03-16 14:31:49.034  4241  4345 E Adreno-ES20: <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,03-16 14:31:49.065  4241  4241 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 4241
,03-16 14:31:49.133   882  1589 W libprocessgroup: failed to open /acct/uid_10060/pid_4063/cgroup.procs: No such file or directory
,03-16 14:31:49.153   882  1516 I art     : Explicit concurrent mark sweep GC freed 14186(652KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/31MB, paused 1.953ms total 153.760ms
,03-16 14:31:49.161  4323  4323 V Mms     : mnc/mcc: 
,03-16 14:31:49.163  4323  4323 V Mms     : tag: int value: recipientLimit - 20
,03-16 14:31:49.163  4323  4323 V Mms     : tag: int value: smsToMmsTextThreshold - 6
03-16 14:31:49.164  4323  4323 V Mms     : tag: int value: emergencySmsTimeout - 30
03-16 14:31:49.164  4323  4323 V Mms     : tag: int value: maxSubjectLength - 80
03-16 14:31:49.164  4323  4323 V Mms     : tag: bool value: smsForceShowEncodingMenu - true
,03-16 14:31:49.166  4323  4323 V Mms     : tag: bool value: enableGroupMms - false
,03-16 14:31:49.168  4323  4323 V Mms     :  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,03-16 14:31:49.248  4323  4356 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-16 14:31:49.283   882  1494 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=4357 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,03-16 14:31:49.371  4357  4357 D PhoneMonitor: Register our PhoneStateListener
,03-16 14:31:49.394  4357  4357 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
03-16 14:31:49.395  4357  4357 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
03-16 14:31:49.398   882  1596 I ActivityManager: Killing 4017:com.google.android.gm/u0a63 (adj 15): empty #7
,03-16 14:31:49.411  1543  1569 I art     : Explicit concurrent mark sweep GC freed 24736(1645KB) AllocSpace objects, 6(96KB) LOS objects, 39% free, 8MB/13MB, paused 1.479ms total 83.659ms
,03-16 14:31:49.467   326   326 I Atfwd_Daemon: result : 0 	 ,Init step :2 	 ,qmiErrorCode: 0
,03-16 14:31:49.467   326   326 I Atfwd_Daemon: ATFWD --> QMI Port : rmnet1
,03-16 14:31:49.475   406   828 E QC-QMI  : qmi_ctl_rx_msg.c Can't find txn info for txn_id = 13
03-16 14:31:49.475   326   326 I Atfwd_Daemon: qmi_atcop_srvc_init_client - QMI Err code 0 , handle 16844800
03-16 14:31:49.475   326   326 I Atfwd_Daemon: Trying to register 8 commands:
03-16 14:31:49.475   326   326 I Atfwd_Daemon: cmd0: +CKPD
,03-16 14:31:49.478   326   326 I Atfwd_Daemon: qmi_atcop_reg_at_command_fwd_req: 0
03-16 14:31:49.478   326   326 I Atfwd_Daemon: cmd1: +CTSA
,03-16 14:31:49.481   326   326 I Atfwd_Daemon: qmi_atcop_reg_at_command_fwd_req: 0
03-16 14:31:49.481   326   326 I Atfwd_Daemon: cmd2: +CFUN
03-16 14:31:49.484   326   326 I Atfwd_Daemon: qmi_atcop_reg_at_command_fwd_req: 0
03-16 14:31:49.484   326   326 I Atfwd_Daemon: cmd3: +CMAR
,03-16 14:31:49.487   326   326 I Atfwd_Daemon: qmi_atcop_reg_at_command_fwd_req: 0
03-16 14:31:49.487   326   326 I Atfwd_Daemon: cmd4: +CDIS
,03-16 14:31:49.490   326   326 I Atfwd_Daemon: qmi_atcop_reg_at_command_fwd_req: 0
03-16 14:31:49.490   326   326 I Atfwd_Daemon: cmd5: +CRSL
,03-16 14:31:49.493   326   326 I Atfwd_Daemon: qmi_atcop_reg_at_command_fwd_req: 0
03-16 14:31:49.493   326   326 I Atfwd_Daemon: cmd6: +CSS
,03-16 14:31:49.495   326   326 I Atfwd_Daemon: qmi_atcop_reg_at_command_fwd_req: 0
03-16 14:31:49.495   326   326 I Atfwd_Daemon: cmd7: +CSO
,03-16 14:31:49.498   326   326 I Atfwd_Daemon: qmi_atcop_reg_at_command_fwd_req: 0
03-16 14:31:49.498   326   326 I Atfwd_Daemon: Registered AT Commands event handler
,03-16 14:31:49.544  4241  4318 E Adreno-ES20: <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
03-16 14:31:49.544  4241  4318 E Adreno-ES20: <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,03-16 14:31:49.583   882  1516 W libprocessgroup: failed to open /acct/uid_10063/pid_4017/cgroup.procs: No such file or directory
,03-16 14:31:49.639   882  1516 I ActivityManager: Killing 4102:android.process.acore/u0a7 (adj 15): empty #7
,03-16 14:31:49.766  4241  4241 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,03-16 14:31:49.802   882  1243 W libprocessgroup: failed to open /acct/uid_10007/pid_4102/cgroup.procs: No such file or directory
,03-16 14:31:49.815   882  1494 I ActivityManager: Killing 4182:com.android.providers.calendar/u0a5 (adj 15): empty #7
,03-16 14:31:49.830  1948  4379 I iu.SyncManager: SYNC; picasa accounts
,03-16 14:31:49.902   882  1501 W libprocessgroup: failed to open /acct/uid_10005/pid_4182/cgroup.procs: No such file or directory
,03-16 14:31:49.912   882  1224 V AlarmManager: send {26144df7, *alarm*:com.android.server.WifiManager.action.START_SCAN}
,03-16 14:31:49.918  1948  1948 D NetworkLogImpl: Loaded NetworkSpeedPredictor
,03-16 14:31:49.923  1948  1948 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,03-16 14:31:49.928  4241  4342 D jxcore_app_log: JniHelper::setJavaVM(0xb7a50310), pthread_self() = -1210344904
,03-16 14:31:49.935  4241  4342 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
03-16 14:31:49.935  4241  4342 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
03-16 14:31:49.935  4241  4342 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
03-16 14:31:49.935  4241  4342 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
03-16 14:31:49.935  4241  4342 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
03-16 14:31:49.935  4241  4342 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a571e1f added. We now have 1 listener(s)
,03-16 14:31:49.937  1948  4379 I iu.UploadsManager: num queued entries: 0
03-16 14:31:49.938  1948  4379 I iu.UploadsManager: num updated entries: 0
03-16 14:31:49.939  1948  4379 I iu.SyncManager: NEXT; no task
,03-16 14:31:49.940  1948  3920 I CheckinRequestBuilder: Classify the device as Phone.
,03-16 14:31:49.954   882  1224 I ActivityManager: Start proc com.google.android.googlequicksearchbox:search for service com.google.android.googlequicksearchbox/com.google.android.voicesearch.logger.EventLoggerService: pid=4386 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
03-16 14:31:49.954   882  1224 V AlarmManager: send {bdef312, *alarm*:send_events}
03-16 14:31:49.955   882   882 V AlarmManager: done {bdef312, *alarm*:send_events} [43ms]
,03-16 14:31:49.956   882  1516 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,03-16 14:31:49.965  4241  4342 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 44:80:EB:7B:5A:05
03-16 14:31:49.966  4241  4342 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"44:80:EB:7B:5A:05"}
,03-16 14:31:49.969  4241  4342 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"name":"<no peer name>","address":"44:80:EB:7B:5A:05"}
03-16 14:31:49.969  4241  4342 D org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setHandshakeRequired: true -> false
03-16 14:31:49.969  4241  4342 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setHandshakeRequired: true -> false
,03-16 14:31:49.973  4241  4342 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
03-16 14:31:49.973  4241  4342 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
03-16 14:31:49.973  4241  4342 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
03-16 14:31:49.973  4241  4342 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 44:80:EB:7B:5A:05
03-16 14:31:49.973  4241  4342 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
03-16 14:31:49.973  4241  4342 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
03-16 14:31:49.973  4241  4342 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
03-16 14:31:49.973  4241  4342 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
03-16 14:31:49.973  4241  4342 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
03-16 14:31:49.973  4241  4342 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,03-16 14:31:49.973  4241  4342 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5de37ca added. We now have 1 listener(s)
03-16 14:31:49.974  4241  4342 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,03-16 14:31:49.982   882  1237 D WifiService: New client listening to asynchronous messages
03-16 14:31:49.984  4241  4342 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (NOT_SUPPORTED) in persistent storage
,03-16 14:31:49.990  4241  4342 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
03-16 14:31:49.990  4241  4342 E io.jxcore.node.ConnectionHelper: Constructor: Bluetooth LE discovery mode is not supported
,03-16 14:31:50.025   882  1299 I ActivityManager: Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=4406 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,03-16 14:31:50.027  4241  4342 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-16 14:31:50.043   882  1508 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,03-16 14:31:50.047  4241  4342 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 44:80:EB:7B:5A:05
,03-16 14:31:50.060  4241  4342 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-16 14:31:50.060  4241  4342 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-16 14:31:50.060  4241  4342 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
03-16 14:31:50.060  4241  4342 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-16 14:31:50.060  4241  4342 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-16 14:31:50.060  4241  4342 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-16 14:31:50.060  4241  4342 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-16 14:31:50.060  4241  4342 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
03-16 14:31:50.060  4241  4342 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
03-16 14:31:50.060  4241  4342 D io.jxcore.node.ConnectivityMonitor: start: OK
,03-16 14:31:50.063  4241  4241 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
03-16 14:31:50.064  4241  4241 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-16 14:31:50.110  4241  4241 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,03-16 14:31:50.299   882   898 I ActivityManager: Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=4430 uid=10005 gids={50005, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-16 14:31:50.378  4430  4430 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,03-16 14:31:50.407  1717  4403 I GCM     : GCM config loaded
,03-16 14:31:50.459  1948  3920 I CheckinTask: Sending checkin request (9681 bytes)
,03-16 14:31:50.463  4430  4430 I CalendarProvider2: Created com.android.providers.calendar.CalendarAlarmManager@1c8fb774(com.android.providers.calendar.CalendarProvider2@acea49d)
,03-16 14:31:50.524  1948  3303 I CheckinService: Done disabling old GoogleServicesFramework version
,03-16 14:31:50.750   882  1596 I ActivityManager: Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=4459 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,03-16 14:31:50.879  1948  3920 I CheckinRequestBuilder: Checkin reason type: 8 attempt count: 1
,03-16 14:31:50.882  1948  3920 E ActivityThread: Failed to find provider info for com.google.android.wearable.settings
,03-16 14:31:50.974   882  1570 I ActivityManager: Killing 4130:com.motorola.context/u0a8 (adj 15): empty #7
,03-16 14:31:51.041  1948  3920 I art     : Explicit concurrent mark sweep GC freed 20803(1493KB) AllocSpace objects, 30(480KB) LOS objects, 24% free, 12MB/17MB, paused 1.019ms total 89.203ms
,03-16 14:31:51.121  4241  4421 W jxcore-log: Initializing JXcore engine
,03-16 14:31:51.121  4241  4421 W jxcore-log: JXcore engine is ready
,03-16 14:31:51.133   882  1501 W libprocessgroup: failed to open /acct/uid_10008/pid_4130/cgroup.procs: No such file or directory
,03-16 14:31:51.139   882  1243 I ActivityManager: Killing 4259:com.google.android.music:main/u0a80 (adj 15): empty #7
,03-16 14:31:51.207  4421  4421 W Thread-454: type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10109 path="socket:[6749]" dev="sockfs" ino=6749 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,03-16 14:31:51.207  4421  4421 W Thread-454: type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10109 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
03-16 14:31:51.207  4421  4421 W Thread-454: type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10109 path="socket:[9586]" dev="sockfs" ino=9586 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
03-16 14:31:51.207  4421  4421 W Thread-454: type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10109 path="socket:[19843]" dev="sockfs" ino=19843 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,03-16 14:31:51.238  4241  4421 W jxcore-log: Starting JXcore engine
,03-16 14:31:51.293   882  1508 W libprocessgroup: failed to open /acct/uid_10080/pid_4259/cgroup.procs: No such file or directory
,03-16 14:31:51.295   882  1254 D TaskPersister: removeObsoleteFile: deleting file=8_task_thumbnail.png
,03-16 14:31:51.296   882  1589 I ActivityManager: Killing 4323:com.android.mms/u0a23 (adj 15): empty #7
,03-16 14:31:51.299   882  1219 D BatteryService: uevent={POWER_SUPPLY_TEMP=331, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2363000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310896, SEQNUM=4316, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-4306, POWER_SUPPLY_CHARGE_COUNTER=-151, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,03-16 14:31:51.379  4241  4421 W jxcore-log: Platform android
03-16 14:31:51.379  4241  4421 W jxcore-log: 
03-16 14:31:51.379  4241  4421 W jxcore-log: Process ARCH arm
03-16 14:31:51.379  4241  4421 W jxcore-log: 
,03-16 14:31:51.456  2446  2509 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-16 14:31:51.459   882  1494 W libprocessgroup: failed to open /acct/uid_10023/pid_4323/cgroup.procs: No such file or directory
,03-16 14:31:51.465  2446  2509 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-16 14:31:51.473  1291  1291 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
03-16 14:31:51.474  1291  1291 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-16 14:31:51.486  4430  4430 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
03-16 14:31:51.487  4430  4430 W ContentResolver: Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,03-16 14:31:51.510   882  1243 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4486 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-16 14:31:51.573   882  1541 I ActivityManager: Killing 4357:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,03-16 14:31:51.683  4241  4421 I jxcore-log: JXcore Cordova bridge is ready!
03-16 14:31:51.683  4241  4421 I jxcore-log: 
,03-16 14:31:51.683  4241  4421 W jxcore-log: JXcore engine is started
,03-16 14:31:51.686  3929  4485 I Babel   : connection state changed from UNKNOWN to CONNECTED
,03-16 14:31:51.692   882  1299 W libprocessgroup: failed to open /acct/uid_10035/pid_4357/cgroup.procs: No such file or directory
,03-16 14:31:51.692  4241  4342 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,03-16 14:31:51.697  1717  1717 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-16 14:31:51.700  1717  1717 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
03-16 14:31:51.700   882  1422 I ActivityManager: Killing 4034:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,03-16 14:31:51.703  4241  4241 I chromium: [INFO:CONSOLE(47)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (47)
,03-16 14:31:51.717  4241  4421 E jxcore  : Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
03-16 14:31:51.717  4241  4421 E jxcore  : Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,03-16 14:31:51.724  4241  4241 I chromium: [INFO:CONSOLE(62)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (62)
,03-16 14:31:51.726  4241  4241 I chromium: [INFO:CONSOLE(33)] "****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****", source: file:///android_asset/www/js/thali_main.js (33)
,03-16 14:31:51.872   882  1541 W libprocessgroup: failed to open /acct/uid_10090/pid_4034/cgroup.procs: No such file or directory
,03-16 14:31:51.891  1461  3867 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,03-16 14:31:51.893  4241  4342 W PluginManager: THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 165ms. Plugin should use CordovaInterface.getThreadPool().
,03-16 14:31:51.907  1461  3867 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,03-16 14:31:51.916  2562  2562 D OtaApp  : [debug] > DownloadActivity, FormattedText
03-16 14:31:51.918  2562  2562 I OtaApp  : [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
03-16 14:31:51.919  2562  2562 D Checkin : publish the event [tag = MOT_OTA event name = LOG]
,03-16 14:31:51.922  2562  2562 I OtaApp  : [info] > Exceed max defer attempts for optional update, suppresing later btn
,03-16 14:31:51.922  2562  2562 D Checkin : publish the event [tag = MOT_OTA event name = LOG]
,03-16 14:31:51.926  2562  2562 D OtaApp  : [debug] > cancelling the previous pending intent set for download later
,03-16 14:31:51.927  2562  2562 I OtaApp  : [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,03-16 14:31:51.928  2562  2562 D Checkin : publish the event [tag = MOT_OTA event name = LOG]
,03-16 14:31:51.948  1948  3920 I CheckinRequestBuilder: Classify the device as Phone.
,03-16 14:31:51.962  4241  4241 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
03-16 14:31:51.962  1416  1416 I Keyboard.Facilitator: onFinishInput()
,03-16 14:31:52.001  1948  3920 I CheckinTask: Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,03-16 14:31:52.013  1948  3920 I CheckinService: Checking schedule, now: 1458135112013 next: 1458736249001
,03-16 14:31:52.013  1948  3920 I CheckinService: active receiver: disabled
,03-16 14:31:52.046  1948  4512 I CheckinService: Checking schedule, now: 1458135112046 next: 1458736249001
03-16 14:31:52.046  1948  4512 I CheckinService: active receiver: disabled
,03-16 14:31:52.050  1948  1948 D CheckinService: Recording last checkin time for package unspecified as 1458135112050
,03-16 14:31:52.082   277   453 E Vold    : Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
03-16 14:31:52.082   277   453 W Vold    : Returning OperationFailed - no handler for errno 0
,03-16 14:31:52.083  4486  4514 W ContextImpl: Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,03-16 14:31:52.087   277   453 E Vold    : Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
03-16 14:31:52.087   277   453 W Vold    : Returning OperationFailed - no handler for errno 0
,03-16 14:31:52.090  4486  4514 W ContextImpl: Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,03-16 14:31:52.099  4505  4505 D AndroidRuntime: 
03-16 14:31:52.099  4505  4505 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,03-16 14:31:52.110  4505  4505 D AndroidRuntime: CheckJNI is OFF
,03-16 14:31:52.120   277   453 E Vold    : Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
03-16 14:31:52.120   277   453 W Vold    : Returning OperationFailed - no handler for errno 0
,03-16 14:31:52.121  4486  4515 W ContextImpl: Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,03-16 14:31:52.125  4486  4486 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
03-16 14:31:52.125  4486  4486 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
03-16 14:31:52.125  4486  4486 I GAv4    :   adb logcat -s GAv4
,03-16 14:31:52.129   277   453 E Vold    : Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
03-16 14:31:52.129   277   453 W Vold    : Returning OperationFailed - no handler for errno 0
03-16 14:31:52.130  4486  4515 W ContextImpl: Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,03-16 14:31:52.148  4486  4486 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,03-16 14:31:52.176  4486  4486 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,03-16 14:31:52.183  4486  4520 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,03-16 14:31:52.333  4505  4505 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,03-16 14:31:52.349   882  1103 I ActivityManager: Force stopping com.test.thalitest appid=10109 user=-1: uninstall pkg
,03-16 14:31:52.352   882  1103 I ActivityManager: Killing 4241:com.test.thalitest/u0a109 (adj 1): stop com.test.thalitest
,03-16 14:31:52.397   882  1237 D WifiService: Client connection lost with reason: 4
,03-16 14:31:52.407   882  1422 I WindowState: WIN DEATH: Window{2822404e u0 com.test.thalitest/com.test.thalitest.MainActivity EXITING}
,03-16 14:31:52.438   278   278 I SFPerfTracer:      triggers: (rate: 13:576) (compose: 0:1) (post: 0:1) (render: 0:2) (8:930 frames) (9:1027)
03-16 14:31:52.438   278   278 D SFPerfTracer:        layers: (5:12) (FocusedStackFrame (0xb8987088): 0:16)* (DimLayer (0xb89e4aa0): 0:9) (StatusBar (0xb89fa910): 4:150) (NavigationBar (0xb89fcd00): 0:52) (com.android.systemui.ImageWallpaper (0xb8a00b90): 0:35)* (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity (0xb89e9418): 0:39)- (Starting com.test.thalitest (0xb8a0e540): 0:42)- (com.test.thalitest/com.test.thalitest.MainActivity (0xb8a11478): 9:73) (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity (0xb8a0e540): 6:10) 
,03-16 14:31:52.463   882  1146 W PackageSettings: Skipping PackageSetting{1ff5be8a com.example.hello/10568} due to missing metadata
,03-16 14:31:52.721   882  1243 W ActivityManager: Spurious death for ProcessRecord{17895e34 4241:com.test.thalitest/u0a109}, curProc for 4241: null
,03-16 14:31:52.728   882  1146 I ActivityManager: Force stopping com.test.thalitest appid=10109 user=0: pkg removed
,03-16 14:31:52.792  1416  1416 I Keyboard.Facilitator: resetDictionaries() : en_US
,03-16 14:31:52.802  1717  2029 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,03-16 14:31:52.818  2984  2984 I art     : Explicit concurrent mark sweep GC freed 7557(382KB) AllocSpace objects, 4(64KB) LOS objects, 39% free, 7MB/12MB, paused 1.081ms total 49.922ms
,03-16 14:31:52.826  1416  4558 I Keyboard.Facilitator.DecoderInitializer: run()
,03-16 14:31:52.843  1543  1543 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
03-16 14:31:52.851   882  1226 I InputReader: Reconfiguring input devices.  changes=0x00000010
,03-16 14:31:52.865  1416  4558 I Decoder : createOrResetDecoder
,03-16 14:31:52.906  4486  4486 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,03-16 14:31:52.920  1717  1717 I ConfigService: onCreate
,03-16 14:31:52.922  1572  1572 I art     : Explicit concurrent mark sweep GC freed 1750(94KB) AllocSpace objects, 1(36KB) LOS objects, 24% free, 13MB/17MB, paused 467us total 132.711ms
,03-16 14:31:52.955   882   882 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
03-16 14:31:52.956   882   882 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,03-16 14:31:52.956  4486  4486 I LibraryLoader: Time to load native libraries: 6 ms (timestamps 3929-3935)
03-16 14:31:52.957  4486  4486 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-16 14:31:52.964  4486  4486 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {38744f07}
,03-16 14:31:52.965  4486  4486 I LibraryLoader: Expected native library version number "",actual native library version number ""
03-16 14:31:52.965  4486  4486 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,03-16 14:31:52.977  1416  4558 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,03-16 14:31:52.989  4486  4486 I BrowserStartupController: Initializing chromium process, singleProcess=true
,03-16 14:31:52.990  4486  4486 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-16 14:31:52.991  4486  4486 E SysUtils: ApplicationContext is null in ApplicationStatus
,03-16 14:31:53.003   278   745 I SFPerfTracer:      triggers: (rate: 0:0) (0 sw vsyncs) (0 skipped) (49:315 vsyncs) (51:1049)
,03-16 14:31:53.021  4486  4486 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,03-16 14:31:53.023  1416  4558 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
03-16 14:31:53.026  1416  4558 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
03-16 14:31:53.026  1416  4558 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
03-16 14:31:53.027  4486  4486 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-16 14:31:53.027  4486  4486 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,03-16 14:31:53.029  1416  4558 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
,03-16 14:31:53.029  1416  4558 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
,03-16 14:31:53.030  4486  4486 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
03-16 14:31:53.030  4486  4486 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.01.03
03-16 14:31:53.030  4486  4486 I Adreno-EGL: Build Date: 10/28/14 Tue
03-16 14:31:53.030  4486  4486 I Adreno-EGL: Local Branch: 
03-16 14:31:53.030  4486  4486 I Adreno-EGL: Remote Branch: quic/l_LNX.LA.3.6
03-16 14:31:53.030  4486  4486 I Adreno-EGL: Local Patches: NONE
03-16 14:31:53.030  4486  4486 I Adreno-EGL: Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
03-16 14:31:53.037  1416  4558 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
03-16 14:31:53.037  1416  4558 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
,03-16 14:31:53.050  1416  4558 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
03-16 14:31:53.050  1416  4558 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
03-16 14:31:53.050  1416  4558 I Keyboard.Facilitator.Delight2FileSweeper: run()
03-16 14:31:53.050  1416  4558 I Keyboard.Facilitator.RecurringTaskScheduler: run()
03-16 14:31:53.050  1416  4558 I StatsUtilsManager: startPeriodStatsRecorder() : Success
03-16 14:31:53.050  1416  4558 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,03-16 14:31:53.058   882  1254 D TaskPersister: removeObsoleteFile: deleting file=9_task.xml
03-16 14:31:53.058   882  1254 D TaskPersister: removeObsoleteFile: deleting file=8_task.xml
03-16 14:31:53.059   882  1254 D TaskPersister: removeObsoleteFile: deleting file=9_task_thumbnail.png
,03-16 14:31:53.070  1572  1572 I Launcher: Deferring update until onResume
,03-16 14:31:53.101   882  1146 I art     : Explicit concurrent mark sweep GC freed 30094(2010KB) AllocSpace objects, 6(96KB) LOS objects, 33% free, 21MB/32MB, paused 1.765ms total 241.057ms
,03-16 14:31:53.111  4486  4576 W AudioManagerAndroid: Requires BLUETOOTH permission
,03-16 14:31:53.125  4486  4486 I NSApplication: Starting up...
,03-16 14:31:53.149  1291  1291 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-16 14:31:53.167   882  1501 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=4581 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-16 14:31:53.168   882  1501 I ActivityManager: Killing 4386:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,03-16 14:31:53.212   882  1596 W libprocessgroup: failed to open /acct/uid_10039/pid_4386/cgroup.procs: No such file or directory
,03-16 14:31:53.213  4505  4505 D AndroidRuntime: Shutting down VM
,03-16 14:31:53.465   882  1146 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=4606 uid=10010 gids={50010, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,03-16 14:31:53.520   882  1589 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=4624 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
03-16 14:31:53.521   882  1589 I ActivityManager: Killing 4406:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,03-16 14:31:53.565   882  1508 W libprocessgroup: failed to open /acct/uid_10088/pid_4406/cgroup.procs: No such file or directory
,03-16 14:31:53.588  4624  4624 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,03-16 14:31:53.615   882  1541 I ActivityManager: Killing 4430:com.android.providers.calendar/u0a5 (adj 15): empty #7
,03-16 14:31:53.635   882  1570 W libprocessgroup: failed to open /acct/uid_10005/pid_4430/cgroup.procs: No such file or directory
,03-16 14:31:54.049   882  1103 I ActivityManager: Waited long enough for: ServiceRecord{2d473c0b u0 com.motorola.ccc.checkin/.CheckinService}
,03-16 14:31:54.056   278   724 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
