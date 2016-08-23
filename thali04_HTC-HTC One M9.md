#### Test 8233723530fac5a_thali04_HTC-HTC One M9 Logs


```
--------- beginning of system
08-23 12:27:58.867  1108  3089 W ActivityManager: getRunningAppProcesses: caller 10091 does not hold REAL_GET_TASKS; limiting output
,--------- beginning of main
08-23 12:27:58.967  9168  9168 W HTCLOG  : use specified tag [cutils-trace], func [0].
08-23 12:27:58.967  9168  9168 W HTCLOG  : mask=0x18
08-23 12:27:58.967  9168  9168 E cutils-trace: Error opening trace file: Permission denied (13)
08-23 12:27:58.967  9168  9168 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm64 --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=31 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
08-23 12:27:58.967  9168  9168 I dex2oat : dex2oat: override thread count:4
08-23 12:27:58.987  1108  3038 D PMS     : acquireWL(10e1bb26): PARTIAL_WAKE_LOCK  *alarm* 0x1 1108 1000 WorkSource{10027}
08-23 12:27:58.987  1108  3038 V AlarmManager: sending alarm PendingIntent{1c867367: PendingIntentRecord{19aa111d com.htc.autobot broadcastIntent}}, i=com.htc.autobot.htcmodeclient.ACTION_RESTART, t=2, cnt=1, w=81662, Int=0
08-23 12:27:59.007  9168  9168 I dex2oat : dex2oat took 33.295ms (threads: 4) arena alloc=94KB java alloc=19KB native alloc=1179KB free=24KB
08-23 12:27:59.007  9168  9168 W HTCLOG  : use specified tag [Vector], func [0].
08-23 12:27:59.007  9168  9168 W HTCLOG  : mask=0x18
08-23 12:27:59.017  9020  9040 W HTCLOG  : use specified tag [libEGL], func [3].
08-23 12:27:59.017  9020  9040 W HTCLOG  : mask=0x18
08-23 12:27:59.017  9020  9040 I Adreno  : QUALCOMM build                   : 065751b, 
08-23 12:27:59.017  9020  9040 I Adreno  : Build Date                       : 04/15/15
08-23 12:27:59.017  9020  9040 I Adreno  : OpenGL ES Shader Compiler Version: E031.25.03.07
08-23 12:27:59.017  9020  9040 I Adreno  : Local Branch                     : 
08-23 12:27:59.017  9020  9040 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.1_rb2.9
08-23 12:27:59.017  9020  9040 I Adreno  : Remote Branch                    : NONE
08-23 12:27:59.017  9020  9040 I Adreno  : Reconstruct Branch               : AU_LINUX_ANDROID_LA.BF64.1.2.1_RB2.05.01.00.081.016 + 065751b +  NOTHING
08-23 12:27:59.107  9020  9040 I Adreno  : QUALCOMM build                   : 065751b, 
08-23 12:27:59.107  9020  9040 I Adreno  : Build Date                       : 04/15/15
08-23 12:27:59.107  9020  9040 I Adreno  : OpenGL ES Shader Compiler Version: E031.25.03.07
08-23 12:27:59.107  9020  9040 I Adreno  : Local Branch                     : 
08-23 12:27:59.107  9020  9040 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.1_rb2.9
08-23 12:27:59.107  9020  9040 I Adreno  : Remote Branch                    : NONE
08-23 12:27:59.107  9020  9040 I Adreno  : Reconstruct Branch               : AU_LINUX_ANDROID_LA.BF64.1.2.1_RB2.05.01.00.081.016 + 065751b +  NOTHING
08-23 12:27:59.137  9173  9173 W HTCLOG  : use specified tag [AndroidRuntime], func [0].
08-23 12:27:59.137  9173  9173 W HTCLOG  : mask=0x18
08-23 12:27:59.237   520  1212 W HTCLOG  : use specified tag [WVCdm], func [0].
08-23 12:27:59.237   520  1212 W HTCLOG  : mask=0x18
08-23 12:27:59.237   520  1214 I WVCdm   : CdmEngine::OpenSession
08-23 12:27:59.237   520  1214 I WVCdm   : Level3 Library Dec 11 2014 16:13:16
08-23 12:27:59.247   520  1214 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
08-23 12:27:59.247   520  1214 D DrmWidevineDash: OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x15
08-23 12:27:59.247   520  1214 D DrmWidevineDash: Service_Initialize: starts!
08-23 12:27:59.247   520  1214 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
08-23 12:27:59.247   520  1214 D QSEECOMAPI: : App is not loaded in QSEE
08-23 12:27:59.247   520  1214 E QSEECOMAPI: : Error::Cannot open the file /vendor/firmware/widevine.mdt
08-23 12:27:59.247   520  1214 E QSEECOMAPI: : Error::Loading image failed with ret = -1
08-23 12:27:59.247   520  1214 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
08-23 12:27:59.247   520  1214 D QSEECOMAPI: : App is not loaded in QSEE
08-23 12:27:59.277   520  1214 D QSEECOMAPI: : Loaded image: APP id = 10
08-23 12:27:59.287   520  1214 D DrmWidevineDash: Service_Initialize: ends! returns 0
08-23 12:27:59.287   520  1214 D DrmWidevineDash: Service_Initialize: function time: 38ms (0s 38443958ns)
08-23 12:27:59.287   520  1214 D QSAPPSVER: qsapps_get_capabilities: Capability from secure side: 0x0
08-23 12:27:59.287   520  1214 D QSAPPSVER: qsapps_get_capabilities: returns 0
08-23 12:27:59.287   520  1214 D DrmWidevineDash: OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf4adc000
08-23 12:27:59.287   520  1214 E DrmWidevineDash: sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf4adc000
08-23 12:27:59.287   619   635 D DrmLibTime: got the req here! ret=0
08-23 12:27:59.287   619   635 D DrmLibTime: command id, time_cmd_id = 770
08-23 12:27:59.287   619   635 D DrmLibTime: time_getutcsec starts!
08-23 12:27:59.287   619   635 D DrmLibTime: QSEE Time Listener: time_getutcsec
08-23 12:27:59.287   619   635 D DrmLibTime: QSEE Time Listener: get_utc_seconds
08-23 12:27:59.287   619   635 D DrmLibTime: QSEE Time Listener: time_get_modem_time
08-23 12:27:59.287   619   635 D DrmLibTime: QSEE Time Listener: Checking if ATS_MODEM is set or not.
08-23 12:27:59.297   619   635 E QC-time-services: Receive Passed == base = 13, unit = 1, operation = 2, result = 0
08-23 12:27:59.297   619   635 D DrmLibTime: QSEE Time Listener: ATS_MODEM is set. Try to retrieve it.
08-23 12:27:59.297   563  1137 E QC-time-services: Daemon: Time-services: Waiting to acceptconnection
08-23 12:27:59.297   619   635 D DrmLibTime: QSEE Time Listener: Time GenOff - seconds: 1471951876
08-23 12:27:59.297   619   635 D DrmLibTime: time_getutcsec returns 0, sec = 1471951876; nsec = 0
08-23 12:27:59.297   619   635 D DrmLibTime: time_getutcsec finished! 
08-23 12:27:59.297   619   635 D DrmLibTime: iotcl_continue_command finished! and return 0 
08-23 12:27:59.297   619   635 D DrmLibTime: before calling ioctl to read the next time_cmd
08-23 12:27:59.297   563  1137 E QC-time-services: Daemon: Time-services: Waiting to acceptconnection
08-23 12:27:59.297   520  1214 D DrmWidevineDash: OEMCrypto_ION_Malloc: function time: 1ms (0s 1321198ns)
08-23 12:27:59.297   520  1214 D DrmWidevineDash: OEMCrypto_Initialize: ends! returns 0
08-23 12:27:59.297   520  1214 D DrmWidevineDash: _oecc01: function time: 46ms (0s 46327969ns)
08-23 12:27:59.297   520  1214 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
08-23 12:27:59.297   520  1214 D DrmWidevineDash: hlos api version =  9
08-23 12:27:59.297   520  1214 D DrmWidevineDash: tz api version =  9
08-23 12:27:59.297   520  1214 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 9
08-23 12:27:59.297   520  1214 D DrmWidevineDash: _oecc22: function time: 0ms (0s 498594ns)
08-23 12:27:59.297   520  1214 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: starts!
08-23 12:27:59.337  9173  9181 W HTCLOG  : use specified tag [cutils-trace], func [0].
08-23 12:27:59.337  9173  9181 W HTCLOG  : mask=0x18
08-23 12:27:59.337  9173  9181 E cutils-trace: Error opening trace file: Permission denied (13)
08-23 12:27:59.367   520  1214 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: ends! returns 0
08-23 12:27:59.367   520  1214 D DrmWidevineDash: _oecc05: function time: 71ms (0s 71228281ns)
08-23 12:27:59.367   520  1214 D WVCdm   : OEMCrypto_Initialize Level 1 success. I will use level 1.
08-23 12:27:59.367   520  1214 D DrmWidevineDash: OEMCrypto_OpenSession: starts! SID=0xf4dcd928
08-23 12:27:59.367   520  1214 D DrmWidevineDash: OEMCrypto_OpenSession Session ID = 0
08-23 12:27:59.367   520  1214 D DrmWidevineDash: OEMCrypto_OpenSession SID = 1
08-23 12:27:59.367   520  1214 D DrmWidevineDash: OEMCrypto_OpenSession: ends! returns 0
08-23 12:27:59.367   520  1214 D DrmWidevineDash: _oecc09: function time: 0ms (0s 450052ns)
08-23 12:27:59.367   520  1214 D DrmWidevineDash: OEMCrypto_GetRandom: starts! randomData=0xabae7678, dataLength=8
08-23 12:27:59.367   520  1214 D DrmWidevineDash: OEMCrypto_GetRandom: ends! returns 0
08-23 12:27:59.367   520  1214 D DrmWidevineDash: _oecc06: function time: 0ms (0s 836146ns)
08-23 12:27:59.367   520  1214 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: starts! SID=1, wrapped_rsa_key=0xabaab788, wrapped_rsa_key_length=1280
08-23 12:27:59.377   520  1214 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: ends! returns 0
08-23 12:27:59.377   520  1214 D DrmWidevineDash: _oecc19: function time: 5ms (0s 5140990ns)
08-23 12:27:59.377   520  1214 I WVCdm   : CdmEngine::QueryKeyControlInfo
08-23 12:27:59.377   520  1212 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
08-23 12:27:59.377   520  1212 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
08-23 12:27:59.377   520  1212 I WVCdm   : CdmEngine::GenerateKeyRequest
08-23 12:27:59.377   520  1212 D DrmWidevineDash: OEMCrypto_GetDeviceID: starts! deviceID=0xabaa8228, idLength=0xf4fcd6f8
08-23 12:27:59.387  9173  9173 D CustomizationManager: ====startRecUseTime====
08-23 12:27:59.387  9173  9173 D htc.customization.log.level:  is 
08-23 12:27:59.387  9173  9173 W CustomizationLogLevel: Level value is invalid, use default level 2
08-23 12:27:59.447   520  1212 D DrmWidevineDash: OEMCrypto_GetDeviceID: ends! returns 0
08-23 12:27:59.447   520  1212 D DrmWidevineDash: _oecc07: function time: 65ms (0s 65156927ns)
08-23 12:27:59.447   520  1212 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: starts!
08-23 12:27:59.447   520  1212 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: is_supported = 1
08-23 12:27:59.447   520  1212 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: wv_app_version = 25
08-23 12:27:59.447   520  1212 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: ends! returns 0
08-23 12:27:59.447   520  1212 D DrmWidevineDash: _oecc29: function time: 0ms (0s 655937ns)
08-23 12:27:59.447   520  1212 D DrmWidevineDash: OEMCrypto_GetHDCPCapability: starts!, current = 0xf4fcd70e, maximum = 0xf4fcd70f
08-23 12:27:59.447   520  1212 D DrmWidevineDash: OEMCrypto_GetHDCPCapability: ends! returns 0
08-23 12:27:59.447   520  1212 D DrmWidevineDash: _oecc28: function time: 0ms (0s 411250ns)
08-23 12:27:59.447   520  1212 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
08-23 12:27:59.447   520  1212 D DrmWidevineDash: hlos api version =  9
08-23 12:27:59.447   520  1212 D DrmWidevineDash: tz api version =  9
08-23 12:27:59.447   520  1212 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 9
08-23 12:27:59.447   520  1212 D DrmWidevineDash: _oecc22: function time: 0ms (0s 360833ns)
08-23 12:27:59.447   520  1212 D DrmWidevineDash: OEMCrypto_GenerateNonce: starts! SID=1, nonce=0xf4fcd77c
08-23 12:27:59.447   520  1212 D DrmWidevineDash: OEMCrypto_GenerateNonce: ends! returns 0
08-23 12:27:59.447   520  1212 D DrmWidevineDash: _oecc14: function time: 0ms (0s 460416ns)
08-23 12:27:59.447   520  1212 D WVCdm   : PrepareKeyRequest: nonce=2389951816
08-23 12:27:59.447   520  1212 D DrmWidevineDash: OEMCrypto_GenerateRSASignature starts! SID=1, message=0xabae0838
08-23 12:27:59.447   520  1212 D DrmWidevineDash: message_length=1656, signature=0xaba79ad8, signature_length=0xf4fcd6dc
08-23 12:27:59.467  9173  9173 D CustomizationManager:  Read ACC file spent 0.036 (s)
08-23 12:27:59.467  9173  9173 V CustomizationCIDLoader: full path : /system/customize/CID/default.xml
08-23 12:27:59.467  9173  9173 I CustomizationCIDLoader: Parsing tag category name = application
08-23 12:27:59.467  9173  9173 I CustomizationCIDLoader: Parsing tag category name = system
08-23 12:27:59.467  9173  9173 I CustomizationCIDLoader: Parsing tag category name = Settings
08-23 12:27:59.467  9173  9173 I CustomizationCIDLoader: Parsing tag category name = AutomotiveHome
08-23 12:27:59.467  9173  9173 I CustomizationCIDLoader: Parsing tag category name = ACC
08-23 12:27:59.467  9173  9173 I CustomizationCIDLoader: add string-array item, value = de:free=+3011;+73240
08-23 12:27:59.467  9173  9173 I CustomizationCIDLoader: add string-array item, value = nl:free=+9434;+9526;+1000
08-23 12:27:59.467  9173  9173 I CustomizationCIDLoader: add string-array item, value = mk:free=+122;+129005
08-23 12:27:59.467  9173  9173 I CustomizationCIDLoader: Parsing tag category name = SettingsProvider
08-23 12:27:59.467  9173  9173 I CustomizationCIDLoader: Parsing tag category name = AudioService
08-23 12:27:59.467  9173  9173 D CustomizationManager:  Read CID file spent 0.085 (s)
08-23 12:27:59.467  9173  9173 D CustomizationManager:  All configurations done spent 0.085 (s)
08-23 12:27:59.477  3545  3995 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
08-23 12:27:59.477  3545  3995 I Prism.ItemManager: loadItems() com.htc.launcher.pageview.WidgetManager@31d6e4db +
08-23 12:27:59.477  3545  3995 I Prism.WidgetManager: onLoadItems() +
08-23 12:27:59.497  3545  3995 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
08-23 12:27:59.507  3525  4164 D PhoneApp: EVENT_QUERY_MO_PACKAGES
08-23 12:27:59.507  3525  4164 D PhoneApp: -- N1 =0
08-23 12:27:59.507  3525  4164 D PhoneApp: -- N2 =0
08-23 12:27:59.507  1108  3649 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 pid 9173 on display 0
08-23 12:27:59.517  1108  3649 V WindowManager: addAppToken: AppWindowToken{24fcdf03 token=Token{281e63b2 ActivityRecord{3d9b61bd u0 com.test.thalitest/.MainActivity t451}}} to stack=1 task=451 at 0
08-23 12:27:59.517  3525  4164 D PhoneApp: -- N3 =0
08-23 12:27:59.527  1108  1177 D PMS     : acquireHCC(512b514): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 1108 1000 null
08-23 12:27:59.527  1108  1177 D PMS     : acquireHCC(af00e80): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 1108 1000 null
08-23 12:27:59.547  1108  3649 I ActivityManager: Start proc 9195:com.test.thalitest/u0a142 for activity com.test.thalitest/.MainActivity
08-23 12:27:59.547  9173  9173 W HTCLOG  : use specified tag [IPCThreadState], func [0].
08-23 12:27:59.547  9173  9173 W HTCLOG  : mask=0x18
08-23 12:27:59.547  9173  9193 W HTCLOG  : use specified tag [Vector], func [0].
08-23 12:27:59.547  9173  9193 W HTCLOG  : mask=0x18
08-23 12:27:59.547   520  1212 D DrmWidevineDash: OEMCrypto_GenerateRSASignature returns 0
08-23 12:27:59.547   520  1212 D DrmWidevineDash: _oecc36: function time: 102ms (0s 102664375ns)
08-23 12:27:59.547  9195  9195 W HTCLOG  : use specified tag [FDManager], func [0].
08-23 12:27:59.547  9195  9195 W HTCLOG  : mask=0x18
08-23 12:27:59.547   520  1214 I WVCdm   : CdmEngine::CloseSession
08-23 12:27:59.547   520  1214 D DrmWidevineDash: OEMCrypto_CloseSession: starts! SID=1
08-23 12:27:59.547   520  1214 D DrmWidevineDash: OEMCrypto_CloseSession: ends! returns 0
08-23 12:27:59.547   520  1214 D DrmWidevineDash: _oecc10: function time: 0ms (0s 631718ns)
08-23 12:27:59.547   520  1214 I WVCdm   : L3 Terminate.
08-23 12:27:59.547   520  1214 D DrmWidevineDash: OEMCrypto_Terminate: starts!
08-23 12:27:59.547   520  1214 D DrmWidevineDash: Service_Uninitialize: starts!
08-23 12:27:59.547   520  1214 D QSEECOMAPI: : QSEECom_dealloc_memory 
08-23 12:27:59.547   520  1214 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 10
08-23 12:27:59.547   520  1214 D DrmWidevineDash: Service_Uninitialize: ends! returns 0x0
08-23 12:27:59.547   520  1214 D DrmWidevineDash: Service_Uninitialize: function time: 0ms (0s 475365ns)
08-23 12:27:59.547   520  1214 D DrmWidevineDash: OEMCrypto_ION_Free: function time: 0ms (0s 156510ns)
08-23 12:27:59.547   520  1214 D DrmWidevineDash: OEMCrypto_Terminate: ends! returns 0
08-23 12:27:59.547   520  1214 D DrmWidevineDash: _oecc02: function time: 1ms (0s 1245416ns)
08-23 12:27:59.567  1108  1108 V ActivityManager: Display changed displayId=0
08-23 12:27:59.567  3337  3337 D DotMatrix: [EventService]  onDisplayChanged: 0
08-23 12:27:59.567  3337  3337 D DotMatrix: [EventService] isOutputToTV: false, mCoverOn:false
08-23 12:27:59.567  1108  3494 D ActivityManager: screenshot for ActivityRecord{3d9b61bd u0 com.test.thalitest/.MainActivity t451}, bitmap=null, time = 0
08-23 12:27:59.577  4035  6804 I Icing   : Indexing 41371D4087D6E720EEA1EE287C7EDC3ED63A55D5 from com.google.android.googlequicksearchbox
08-23 12:27:59.587  4035  8988 I CheckinRequestBuilder: Classify the device as Phone.
08-23 12:27:59.597  3545  3545 I TrimMemoryManager: [trimMemory] 20
08-23 12:27:59.597  4035  8988 D libc    : [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
08-23 12:27:59.597  4035  8988 D libc    : [NET] android_getaddrinfofornet-, err=8
08-23 12:27:59.597  4035  8988 D libc    : [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
08-23 12:27:59.597  4035  8988 D libc    : [NET] android_getaddrinfofornet-, pass to proxy
08-23 12:27:59.597  4035  8988 D libc    : [NET] android_getaddrinfo_proxy+
08-23 12:27:59.597  4035  8988 D libc    : [NET] android_getaddrinfo_proxy get netid:0
08-23 12:27:59.607   514  9217 D libc    : [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
08-23 12:27:59.607   514  9217 D libc    : [NET] _dns_getaddrinfo+, netid:100, mark:917604
08-23 12:27:59.607   514  9217 D libc    : [NET] _dns_getaddrinfo-, (NS_SUCCESS)
08-23 12:27:59.607   514  9217 D libc    : [NET] android_getaddrinfofornet-, SUCCESS
08-23 12:27:59.607  4035  8988 D libc    : [NET] android_getaddrinfo_proxy-, success
08-23 12:27:59.617  4035  6804 D Icing   : Loaded CLD2 Version V2.0 - 20140131
08-23 12:27:59.617  9195  9195 I WebViewFactory: Loading com.google.android.webview version 42.0.2311.137 (code 52311137)
08-23 12:27:59.637  4035  6804 I Icing   : Indexing done 41371D4087D6E720EEA1EE287C7EDC3ED63A55D5
08-23 12:27:59.637  1108  3557 D PMS     : releaseWL(2ec85e81): PARTIAL_WAKE_LOCK  Icing 0x1 null
08-23 12:27:59.667  3545  3995 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-23 12:27:59.677  9195  9195 I LibraryLoader: Time to load native libraries: 29 ms (timestamps 4326-4355)
08-23 12:27:59.677  9195  9195 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-23 12:27:59.687  9195  9195 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {27b1bf9d}
08-23 12:27:59.687  9195  9195 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-23 12:27:59.687  9195  9195 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
08-23 12:27:59.697  9195  9195 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-23 12:27:59.697  9195  9195 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-23 12:27:59.697  9195  9195 E SysUtils: ApplicationContext is null in ApplicationStatus
08-23 12:27:59.747  5540  5566 D BluetoothAdapterService(681535047): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@20aa3028
08-23 12:27:59.747  9195  9195 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,08-23 12:27:59.757  9195  9195 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=39 off=50364 len=3345
08-23 12:27:59.757  9195  9195 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:40 off:9397000 len:1161174
08-23 12:27:59.757  9195  9195 W HTCLOG  : use specified tag [libEGL], func [3].
08-23 12:27:59.757  9195  9195 W HTCLOG  : mask=0x18
08-23 12:27:59.767  9195  9195 W HTCLOG  : use specified tag [libEGL], func [3].
08-23 12:27:59.767  9195  9195 W HTCLOG  : mask=0x18
08-23 12:27:59.767  9195  9195 I Adreno  : QUALCOMM build                   : 065751b, 
08-23 12:27:59.767  9195  9195 I Adreno  : Build Date                       : 04/15/15
08-23 12:27:59.767  9195  9195 I Adreno  : OpenGL ES Shader Compiler Version: E031.25.03.07
08-23 12:27:59.767  9195  9195 I Adreno  : Local Branch                     : 
08-23 12:27:59.767  9195  9195 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.1_rb2.9
08-23 12:27:59.767  9195  9195 I Adreno  : Remote Branch                    : NONE
08-23 12:27:59.767  9195  9195 I Adreno  : Reconstruct Branch               : AU_LINUX_ANDROID_LA.BF64.1.2.1_RB2.05.01.00.081.016 + 065751b +  NOTHING
08-23 12:27:59.787  3545  3995 E Prism.WidgetManager: The same lists. No need to update. skip it.
08-23 12:27:59.787  3545  3995 I Prism.WidgetManager: onLoadItems() -
08-23 12:27:59.787  3545  3995 I Prism.ItemManager: loadItems() com.htc.launcher.pageview.WidgetManager@31d6e4db -
08-23 12:27:59.837  9142  9239 W HTCLOG  : use specified tag [SQLiteConnection], func [0].
08-23 12:27:59.837  9195  9230 W chromium: [WARNING:data_reduction_proxy_config.cc(150)] SPDY proxy OFF at startup
08-23 12:27:59.837  9142  9239 W HTCLOG  : mask=0x18
08-23 12:27:59.847  9195  9195 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-23 12:27:59.857  9195  9195 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-23 12:27:59.867  9195  9195 D SystemWebViewEngine: CordovaWebView is running on device made by: HTC
08-23 12:27:59.867  9195  9195 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-23 12:27:59.867  9195  9195 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-23 12:27:59.877  9142  9142 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
08-23 12:27:59.887  1108  3498 D PMS     : acquireWL(b41a312): PARTIAL_WAKE_LOCK  AsyncService 0x1 8861 10128 null
08-23 12:27:59.887  1108  3494 D PMS     : releaseWL(b41a312): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
08-23 12:27:59.897  9195  9253 W HTCLOG  : use specified tag [OpenGLRenderer], func [3].
08-23 12:27:59.897  9195  9253 W HTCLOG  : mask=0x18
08-23 12:27:59.907  1108  3498 V WindowManager: Adding window Window{3412de5e u0 com.test.thalitest/com.test.thalitest.MainActivity} at 1 of 7 (after Window{11ab34e9 u0 com.htc.launcher/com.htc.launcher.Launcher})
08-23 12:27:59.907  1108  3626 D HtcSystemUPManager: HtcSystemUPolicy [canLog (default)] category: launch, enable: true
08-23 12:27:59.917  3589  3589 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
08-23 12:27:59.917  3589  3589 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
08-23 12:27:59.917  3589  3589 D c       : Getting all permits...
08-23 12:27:59.917  3589  3589 D a       : Opening database...
08-23 12:27:59.917  3589  3589 D a       : Opening database auth.proximity.permit_store...
08-23 12:27:59.917  3589  3589 D a       : Closing database...
08-23 12:27:59.917  4035  4035 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
08-23 12:27:59.927  8750  8750 D AlarmReceiver: ACTION_RESTART_INTENT
08-23 12:27:59.927  8750  8750 D LocalBluetoothProfile: getPriorityOnValue = 100
08-23 12:27:59.927  8750  8750 D LocalBluetoothProfile: getPriorityOffValue = 0
08-23 12:27:59.927  8750  8750 D Utils   : CMD:getprop ro.htc.htcmode.socket.type
08-23 12:27:59.927  8750  8750 I System  : exec(getprop ro.htc.htcmode.socket.type @ com.htc.autobot.c.b.b:-1)
08-23 12:27:59.927  1108  1108 D PMS     : releaseWL(10e1bb26): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10027}
08-23 12:27:59.937  4035  9255 D LocationInitializer: Restart initialization of location
08-23 12:27:59.937  9195  9195 D FindExtension: FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
08-23 12:27:59.937  9195  9195 W HTCLOG  : use specified tag [ThreadedRenderer], func [0].
08-23 12:27:59.937  9195  9195 W HTCLOG  : mask=0x18
08-23 12:27:59.937  9195  9195 W HTCLOG  : use specified tag [OpenGLRenderer], func [3].
08-23 12:27:59.937  9195  9195 W HTCLOG  : mask=0x18
08-23 12:27:59.937  9195  9253 W HTCLOG  : use specified tag [OpenGLRenderer], func [3].
08-23 12:27:59.937  9195  9253 W HTCLOG  : mask=0x18
08-23 12:27:59.937  9195  9253 W HTCLOG  : use specified tag [OpenGLRenderer], func [3].
08-23 12:27:59.937  9195  9253 W HTCLOG  : mask=0x18
08-23 12:27:59.937  9195  9253 W HTCLOG  : use specified tag [OpenGLRenderer], func [3].
08-23 12:27:59.937  9195  9253 W HTCLOG  : mask=0x18
08-23 12:27:59.937  9195  9253 W HTCLOG  : use specified tag [OpenGLRenderer], func [3].
08-23 12:27:59.937  9195  9253 W HTCLOG  : mask=0x18
08-23 12:27:59.947  9195  9253 W HTCLOG  : use specified tag [Surface], func [3].
08-23 12:27:59.947  9195  9253 W HTCLOG  : mask=0x18
08-23 12:27:59.947  9195  9253 W HTCLOG  : use specified tag [GraphicBufferMapper], func [3].
08-23 12:27:59.947  9195  9253 W HTCLOG  : mask=0x18
08-23 12:27:59.957  9195  9253 W HTCLOG  : use specified tag [qdmemalloc], func [0].
08-23 12:27:59.957  9195  9253 W HTCLOG  : mask=0x18
08-23 12:27:59.957  8750  9257 D HtcModeClient: start the htcmodeservice thread
08-23 12:27:59.957  8750  9257 D HtcModeClient: initCanAgent
08-23 12:27:59.957  8750  9257 I CANMesgAgentLocalSocket: CANAgent Id = 0
08-23 12:27:59.957  8750  9257 D HtcModeClient: sense info: version = none, id = 2
08-23 12:27:59.957  8750  9257 D HtcModeClient: display info: width = 1080, height = 1776
08-23 12:27:59.957  8750  9257 D HtcModeClient: display info: mode = 10
08-23 12:27:59.997  1108  1166 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +430ms (total +482ms)
08-23 12:28:00.037  9195  9195 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 9195
08-23 12:28:00.057  8750  8750 D HtcModeClient: onStartCommand() action = com.htc.autobot.htcmodeclient.PowerConnected +++
08-23 12:28:00.057  8750  8750 D HtcModeClient: connectState: BT_TURNON_BYME = false
08-23 12:28:00.057  8750  8750 D HtcModeClient: connectState: CONNECTION_READY = false
08-23 12:28:00.057  8750  8750 D HtcModeClient: connectState: ENABLE_PROJECTBYAPP = false
08-23 12:28:00.057  8750  8750 D HtcModeClient: connectState: ENTER_PROJECTMODE = false
08-23 12:28:00.057  8750  8750 D HtcModeClient: connectState: PHONE_PULGIN = false
08-23 12:28:00.057  8750  8750 D HtcModeClient: connectState: Force_AWAKE = false
08-23 12:28:00.057  8750  8750 D HtcModeClient: connectState: PHONE_PULGIN = true
08-23 12:28:00.057  8750  8750 D HtcModeClient: connectState: POWERCONNECTED_READY = true
08-23 12:28:00.097  9195  9195 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
08-23 12:28:00.137  9195  9261 D jxcore_app_log: JniHelper::setJavaVM(0xab9a0b70), pthread_self() = -1399571024
08-23 12:28:00.137  9195  9261 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-23 12:28:00.137  9195  9261 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-23 12:28:00.137  9195  9261 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-23 12:28:00.137  9195  9261 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-23 12:28:00.137  9195  9261 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-23 12:28:00.137  9195  9261 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d88dc40 added. We now have 1 listener(s)
08-23 12:28:00.137  1108  3673 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
08-23 12:28:00.137  9195  9261 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 90:E7:C4:FE:AC:EF
08-23 12:28:00.147  9195  9261 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "90:E7:C4:FE:AC:EF"
08-23 12:28:00.147  9195  9261 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-23 12:28:00.147  9195  9261 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-23 12:28:00.147  9195  9261 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-23 12:28:00.147  9195  9261 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-23 12:28:00.147  9195  9261 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-23 12:28:00.147  9195  9261 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 90:E7:C4:FE:AC:EF
08-23 12:28:00.147  9195  9261 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-23 12:28:00.147  9195  9261 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-23 12:28:00.147  9195  9261 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-23 12:28:00.147  9195  9261 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-23 12:28:00.147  9195  9261 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-23 12:28:00.147  9195  9261 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-23 12:28:00.147  9195  9261 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-23 12:28:00.147  9195  9261 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-23 12:28:00.147  9195  9261 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-23 12:28:00.147  9195  9261 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-23 12:28:00.147  9195  9261 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25c6e11f added. We now have 1 listener(s)
08-23 12:28:00.147  1108  3081 D WifiService: New client listening to asynchronous messages
08-23 12:28:00.147  9195  9261 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-23 12:28:00.147  9195  9261 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-23 12:28:00.147  9195  9261 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-23 12:28:00.147  9195  9261 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-23 12:28:00.147  9195  9261 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-23 12:28:00.147  9195  9261 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-23 12:28:00.147  9195  9261 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-23 12:28:00.147  1108  3524 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
08-23 12:28:00.147  9195  9261 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 90:E7:C4:FE:AC:EF
08-23 12:28:00.157  5540  5570 D BluetoothAdapterService(681535047): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@20aa3028
08-23 12:28:00.157  9195  9261 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
08-23 12:28:00.157  9195  9261 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 12:28:00.157  9195  9261 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 12:28:00.157  9195  9261 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 12:28:00.157  9195  9261 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 12:28:00.157  9195  9261 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 12:28:00.157  9195  9261 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 12:28:00.157  9195  9261 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 12:28:00.157  9195  9261 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-23 12:28:00.157  9195  9261 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-23 12:28:00.157  9195  9261 D io.jxcore.node.ConnectivityMonitor: start: OK
08-23 12:28:00.157  9195  9261 I io.jxcore.node.LifeCycleMonitor: start: OK
08-23 12:28:00.157  9195  9195 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 12:28:00.157  9195  9195 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 12:28:00.197  9195  9195 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
08-23 12:28:00.227  3525  3745 D ContactMessageStore: MSG_NOTIFY_CS_TO_SYNC >>
08-23 12:28:00.227  3525  3745 D ContactMessageStore: MSG_NOTIFY_CS_TO_SYNC <<
08-23 12:28:00.257  4035  8988 D libc    : [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
08-23 12:28:00.257  4035  8988 D libc    : [NET] android_getaddrinfofornet-, err=8
08-23 12:28:00.257  4035  8988 I CheckinTask: Sending checkin request (10606 bytes)
08-23 12:28:00.377  4035  8988 I CheckinRequestBuilder: Checkin reason type: 2 attempt count: 1
08-23 12:28:00.417  4035  8988 I CheckinRequestBuilder: Classify the device as Phone.
08-23 12:28:00.427  4035  8988 I CheckinTask: Checkin success: https://android.clients.google.com/checkin (1 requests sent)
08-23 12:28:00.427  4035  8988 I GoogleURLConnFactory: unbinding HttpService
08-23 12:28:00.427  4035  8988 I CheckinService: Checking schedule, now: 1471948080443 next: 1472534886438
08-23 12:28:00.427  4035  8988 I CheckinService: active receiver: disabled
08-23 12:28:00.427  1108  3557 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=4035, uid=10019, userID:0
08-23 12:28:00.447  1108  3252 D PMS     : releaseWL(2a2c8e88): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
08-23 12:28:00.457  3589  3589 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
08-23 12:28:00.477  3589  3589 I GCM     : GCM config loaded
08-23 12:28:00.487  1108  4754 I ActivityManager: Start proc 9271:com.google.android.setupwizard/u0a59 for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver
,08-23 12:28:00.507  9271  9271 W HTCLOG  : use specified tag [FDManager], func [0].
08-23 12:28:00.507  9271  9271 W HTCLOG  : mask=0x18
,08-23 12:28:00.507  1108  1177 D PMS     : releaseHCC(512b514): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null
,08-23 12:28:00.507  1108  1177 D PMS     : releaseHCC(af00e80): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,08-23 12:28:00.557  9195  9269 W jxcore-log: Initializing JXcore engine
08-23 12:28:00.557  9195  9269 W jxcore-log: JXcore engine is ready
,08-23 12:28:00.577  9271  9271 I SetupWizard: Connected to Gservices successfully
,08-23 12:28:00.597  9271  9292 I SetupWizard.FrpHelper: FRP status: supported: true, challengeRequired: false
,08-23 12:28:00.607  9195  9269 W jxcore-log: Starting JXcore engine
,08-23 12:28:00.707  9195  9269 W jxcore-log: Platform android,
08-23 12:28:00.707  9195  9269 W jxcore-log: 
08-23 12:28:00.707  9195  9269 W jxcore-log: Process ARCH arm
08-23 12:28:00.707  9195  9269 W jxcore-log: 
,08-23 12:28:00.887  9195  9269 I jxcore-log: JXcore Cordova bridge is ready!,
08-23 12:28:00.887  9195  9269 I jxcore-log: 
08-23 12:28:00.887  9195  9269 W jxcore-log: JXcore engine is started
,08-23 12:28:00.897  9195  9261 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-23 12:28:00.897  9195  9195 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-23 12:28:00.927  9195  9269 E jxcore  : Error!: missing name after . operator,
08-23 12:28:00.927  9195  9269 E jxcore  : Stack: [{"_fileName":"module.js","_functionName":"$w.prototype._compile","_lineNumber":"591","_columnNumber":"9","_msg":"    at $w.prototype._compile@module.js:591:9"},{"_fileName":"module.js","_functionName":"$w._extensions[\".js\"]","_lineNumber":"651","_columnNumber":"1","_msg":"    at $w._extensions[\".js\"]@module.js:651:1"},{"_fileName":"module.js","_functionName":"$w.prototype.load","_lineNumber":"442","_columnNumber":"1","_msg":"    at $w.prototype.load@module.js:442:1"},{"_fileName":"module.js","_functionName":"$w._load","_lineNumber":"407","_columnNumber":"1","_msg":"    at $w._load@module.js:407:1"},{"_fileName":"module.js","_functionName":"$w.prototype.require","_lineNumber":"477","_columnNumber":"8","_msg":"    at $w.prototype.require@module.js:477:8"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"495","_columnNumber":"8","_msg":"    at require@module.js:495:8"},{"_fileName":"main.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js:260:5"},{"_fileName":"main.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"}]
,08-23 12:28:00.927  9195  9195 I chromium: [INFO:CONSOLE(56)] "app.js file failed to load : "missing name after . operator\nSyntaxError: missing name after . operator\n    at $w.prototype._compile@module.js:591:9\n    at $w._extensions[\".js\"]@module.js:651:1\n    at $w.prototype.load@module.js:442:1\n    at $w._load@module.js:407:1\n    at $w.prototype.require@module.js:477:8\n    at require@module.js:495:8\n    at internal_methods.loadMainFile@main.js:260:5\n    at JXMobile.executeJSON@main.js:279:7\n    at @JX_Evaluate:1:1"", source: file:///android_asset/www/js/thali_main.js (56)
08-23 12:28:00.927  9195  9195 I chromium: [INFO:CONSOLE(72)] "****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****", source: file:///android_asset/www/js/thali_main.js (72)
,08-23 12:28:00.937  1108  4749 D Process : killProcessQuiet, pid=7487,
08-23 12:28:00.937  1108  4749 I ActivityManager: Killing 7487:com.google.android.music:main/u0a115 (adj 15): empty #17
08-23 12:28:00.937  1108  4749 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19468 com.android.server.am.ActivityStack.destroyActivityLocked:3407 
,08-23 12:28:01.037  1108  4757 I ActivityManager: Recipient 7487,
08-23 12:28:01.037  1108  3524 D MediaRouterService: Client com.google.android.music (pid 7487): Died!
,08-23 12:28:01.047  9195  9261 W PluginManager: THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 118ms. Plugin should use CordovaInterface.getThreadPool().,
08-23 12:28:01.047  9195  9195 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-23 12:28:01.047  9195  9195 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: DESTROYED
08-23 12:28:01.057  9195  9195 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose,
08-23 12:28:01.057  9195  9195 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:28:01.057  9195  9195 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:28:01.057  9195  9195 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-23 12:28:01.057  9195  9195 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d88dc40 removed from the list,
,08-23 12:28:01.057  9195  9195 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:28:01.057  9195  9195 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25c6e11f removed from the list
08-23 12:28:01.057  9195  9195 D io.jxcore.node.ConnectivityMonitor: stop
,08-23 12:28:01.057  9195  9195 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
08-23 12:28:01.057  9195  9195 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-23 12:28:01.127  9295  9295 W HTCLOG  : use specified tag [AndroidRuntime], func [0].,
08-23 12:28:01.127  9295  9295 W HTCLOG  : mask=0x18
,08-23 12:28:01.307  9295  9298 W HTCLOG  : use specified tag [cutils-trace], func [0].
08-23 12:28:01.307  9295  9298 W HTCLOG  : mask=0x18
08-23 12:28:01.307  9295  9298 E cutils-trace: Error opening trace file: Permission denied (13)
,08-23 12:28:01.377  9295  9295 D CustomizationManager: ====startRecUseTime====,
08-23 12:28:01.377  9295  9295 D htc.customization.log.level:  is 
08-23 12:28:01.377  9295  9295 W CustomizationLogLevel: Level value is invalid, use default level 2
,08-23 12:28:01.457  9295  9295 D CustomizationManager:  Read ACC file spent 0.041 (s),
,08-23 12:28:01.457  9295  9295 V CustomizationCIDLoader: full path : /system/customize/CID/default.xml,
08-23 12:28:01.457  9295  9295 I CustomizationCIDLoader: Parsing tag category name = application
,08-23 12:28:01.457  9295  9295 I CustomizationCIDLoader: Parsing tag category name = system
,08-23 12:28:01.457  9295  9295 I CustomizationCIDLoader: Parsing tag category name = Settings,
08-23 12:28:01.457  9295  9295 I CustomizationCIDLoader: Parsing tag category name = AutomotiveHome
08-23 12:28:01.457  9295  9295 I CustomizationCIDLoader: Parsing tag category name = ACC
,08-23 12:28:01.467  9295  9295 I CustomizationCIDLoader: add string-array item, value = de:free=+3011;+73240,
08-23 12:28:01.467  9295  9295 I CustomizationCIDLoader: add string-array item, value = nl:free=+9434;+9526;+1000
08-23 12:28:01.467  9295  9295 I CustomizationCIDLoader: add string-array item, value = mk:free=+122;+129005
08-23 12:28:01.467  9295  9295 I CustomizationCIDLoader: Parsing tag category name = SettingsProvider
08-23 12:28:01.467  9295  9295 I CustomizationCIDLoader: Parsing tag category name = AudioService
,08-23 12:28:01.467  9295  9295 D CustomizationManager:  Read CID file spent 0.093 (s),
08-23 12:28:01.467  9295  9295 D CustomizationManager:  All configurations done spent 0.093 (s)
,08-23 12:28:01.517  1108  4754 D PackageManager: deletePackageAsUser: pkg=com.test.thalitest user=0, pid=9295, uid=2000,
,08-23 12:28:01.517  1108  1150 D Process : killProcessQuiet, pid=9195
08-23 12:28:01.517  1108  1150 I ActivityManager: Force stopping com.test.thalitest appid=10142 user=-1: uninstall pkg
,08-23 12:28:01.517  1108  1150 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.removeProcessLocked:6195 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5997 
08-23 12:28:01.517  1108  1150 I ActivityManager: Killing 9195:com.test.thalitest/u0a142 (adj 9): stop com.test.thalitest
,08-23 12:28:01.617  1108  3557 I ActivityManager: Recipient 9195
08-23 12:28:01.617  1108  3081 D WifiService: Client connection lost with reason: 4
,08-23 12:28:01.627  1108  3557 W ActivityManager: Spurious death for ProcessRecord{13e90c1f 9195:com.test.thalitest/u0a142}, curProc for 9195: null
,08-23 12:28:01.647   523   523 W HTCLOG  : use specified tag [Vector], func [0].,
08-23 12:28:01.647   523   523 W HTCLOG  : mask=0x18
,08-23 12:28:01.647  1108  1179 I ActivityManager: Force stopping com.test.thalitest appid=10142 user=0: pkg removed,
,08-23 12:28:01.677  1108  3041 W SystemReader: Cannot find grip_rejection_width, use default value instead
08-23 12:28:01.677  3337  3337 D DotMatrix: [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
08-23 12:28:01.687  1108  3089 D PMS     : acquireWL(195ab535): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 4394 10019 null
08-23 12:28:01.677  3337  3337 D DotMatrix: [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
08-23 12:28:01.687  4394  4646 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-23 12:28:01.687  1108  3498 D PMS     : releaseWL(195ab535): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,08-23 12:28:01.697  3770  9313 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest,
,08-23 12:28:01.707  6577  6577 I art     : Explicit concurrent mark sweep GC freed 18145(1147KB) AllocSpace objects, 3(72KB) LOS objects, 32% free, 4MB/6MB, paused 616us total 49.616ms
,08-23 12:28:01.707  1108  3047 V NetworkPolicy: ACTION_UID_REMOVED for uid=10142
08-23 12:28:01.707  1108  3047 V NetworkPolicy: writePolicyLocked()
08-23 12:28:01.707  1108  3046 D PMS     : acquireWL(1a55fc22): PARTIAL_WAKE_LOCK  NetworkStats 0x1 1108 1000 null
,08-23 12:28:01.717  1108  3047 D NetworkPolicy: notifyPoliciesChangeLocked: no change
08-23 12:28:01.717  4035  4035 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
08-23 12:28:01.727  3747  4155 D AccTypeManager: Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
,08-23 12:28:01.727  1108  3047 V NetworkPolicy: updateNetworkEnabledLocked()
,08-23 12:28:01.737  3747  4155 D AccTypeManager: Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
08-23 12:28:01.727  1108  3047 V NetworkPolicy: updateNotificationsLocked()
08-23 12:28:01.737  1108  3089 D PMS     : acquireWL(a733b0f): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 4035 10019 null
08-23 12:28:01.737  1108  3046 D PMS     : releaseWL(1a55fc22): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,08-23 12:28:01.747  3589  3589 I ConfigService: onCreate
08-23 12:28:01.747  1108  1145 I InputMethodManagerService: [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
,08-23 12:28:01.747  3589  3589 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
08-23 12:28:01.747  3545  3545 I art     : Explicit concurrent mark sweep GC freed 48301(3MB) AllocSpace objects, 51(3MB) LOS objects, 40% free, 20MB/33MB, paused 1.505ms total 81.235ms
,08-23 12:28:01.757  3747  4155 D AccTypeManager: Registering external account type=com.google.android.gm.exchange, packageName=com.google.android.gm
08-23 12:28:01.757  3589  3589 I ConfigService: onBind returning update interface
,08-23 12:28:01.767  3747  4155 D AccTypeManager: Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
08-23 12:28:01.767  4035  4035 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,08-23 12:28:01.767  3525  3525 D PhoneApp: -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
08-23 12:28:01.777  3589  3589 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
08-23 12:28:01.777  3589  3589 I ConfigService: onBind returning config service
,08-23 12:28:01.787  4035  4035 I ConfigFetchService: service connected
,08-23 12:28:01.787  3747  4155 E ExternalAccountType: Unsupported attribute readOnly
,08-23 12:28:01.787  1108  1128 I ActivityManager: Start proc 9315:com.google.android.gms.ui/u0a19 for broadcast com.google.android.gms/com.google.android.location.settings.PackageChangeReceiver
08-23 12:28:01.797  1108  3649 D PMS     : acquireWL(26dda92a): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 3589 10019 null
,08-23 12:28:01.797  9315  9315 W HTCLOG  : use specified tag [FDManager], func [0].
,08-23 12:28:01.797  9315  9315 W HTCLOG  : mask=0x18
08-23 12:28:01.797  1108  1128 D PMS     : releaseWL(26dda92a): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null,
08-23 12:28:01.807  3589  3589 I ConfigService: onDestroy
,08-23 12:28:01.817  1108  1145 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,08-23 12:28:01.837  1108  1108 W PackageManager: Unable to load service info ResolveInfo{1f403839 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000},
08-23 12:28:01.837  1108  1108 W PackageManager: org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
08-23 12:28:01.837  1108  1108 W PackageManager: 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:509)
08-23 12:28:01.837  1108  1108 W PackageManager: 	,at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:345)
08-23 12:28:01.837  1108  1108 W PackageManager: 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:171)
08-23 12:28:01.837  1108  1108 W PackageManager: 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:71),
08-23 12:28:01.837  1108  1108 W PackageManager: 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:180)
08-23 12:28:01.837  1108  1108 W PackageManager: 	,at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:927)
08-23 12:28:01.837  1108  1108 W PackageManager: 	at android.os.Handler.handleCallback(Handler.java:739),
08-23 12:28:01.837  1108  1108 W PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-23 12:28:01.837  1108  1108 W PackageManager: 	at android.os.Looper.loop(Looper.java:155)
08-23 12:28:01.837  1108  1108 W PackageManager: 	at com.android.server.SystemServer.run(SystemServer.java:331)
08-23 12:28:01.837  1108  1108 W PackageManager: 	at com.android.server.SystemServer.main(SystemServer.java:232)
08-23 12:28:01.837  1108  1108 W PackageManager: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 12:28:01.837  1108  1108 W PackageManager: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-23 12:28:01.837  1108  1108 W PackageManager: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
08-23 12:28:01.837  1108  1108 W PackageManager: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
08-23 12:28:01.847  9315  9315 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-23 12:28:01.847  9315  9315 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-23 12:28:01.877  3545  3545 D FindExtension: FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true,
08-23 12:28:01.877  3545  3545 I ThreadedRenderer: Defer allocateBuffers to drawing time,
,08-23 12:28:01.877  9315  9315 I MultiDex: VM with version 2.1.0 has multidex support
08-23 12:28:01.877  9315  9315 I MultiDex: install
08-23 12:28:01.887  9315  9315 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-23 12:28:01.887  1108  1108 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-23 12:28:01.897  9315  9315 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,08-23 12:28:01.907  9315  9315 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,08-23 12:28:01.907  3545  3995 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false,
08-23 12:28:01.907  3545  3995 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,08-23 12:28:01.917  3545  3545 I Launcher: Deferring update until onResume
08-23 12:28:01.917  3545  3545 D Launcher: waitUntilResume // bindAppsRemoved
,08-23 12:28:01.927  4035  9339 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,08-23 12:28:01.927  4035  9339 D AccountUtils: Clearing selected account for com.test.thalitest
,08-23 12:28:01.937  1108  4264 I ActivityManager: Start proc 9341:com.htc.home.personalize/1000 for broadcast com.htc.home.personalize/com.htc.font.util.receiver.ApplyFontStyleReceiver
,08-23 12:28:01.937  9341  9341 W HTCLOG  : use specified tag [FDManager], func [0].
08-23 12:28:01.937  9341  9341 W HTCLOG  : mask=0x18
,08-23 12:28:01.947  3469  3469 D Nfc-Utils: isNxpCodebase: isNxp=false
,08-23 12:28:01.947  1108  1179 I art     : Explicit concurrent mark sweep GC freed 34329(2MB) AllocSpace objects, 4(80KB) LOS objects, 33% free, 16MB/24MB, paused 2.369ms total 258.150ms,
,08-23 12:28:01.987  9295  9295 I art     : System.exit called, status: 0
,08-23 12:28:01.987  8719  9367 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
,08-23 12:28:01.997  4035  9369 I PeopleContactsSync: CP2 sync disabled
,08-23 12:28:01.997  1108  4261 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=4035, uid=10019, userID:0
,08-23 12:28:02.007  1108  3557 D PMS     : acquireWL(1ca6d93e): PARTIAL_WAKE_LOCK  Icing 0x1 4035 10019 null
,08-23 12:28:02.007  4035  6804 I Icing   : doRemovePackageData com.test.thalitest
,08-23 12:28:02.007  1108  4754 D PMS     : releaseWL(1ca6d93e): PARTIAL_WAKE_LOCK  Icing 0x1 null
,08-23 12:28:02.027  1108  3649 D Process : killProcessQuiet, pid=8313,
,08-23 12:28:02.027  1108  3649 I ActivityManager: Killing 8313:com.google.android.apps.photos/u0a126 (adj 15): empty #17
08-23 12:28:02.027  1108  3649 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19468 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:238 
,08-23 12:28:02.067  8750  9257 I HtcModeClient: handler message = 4011,
08-23 12:28:02.067  8750  9257 D HtcModeClient: getConnectionCheckCount first 0
08-23 12:28:02.067  8750  9257 D HtcModeClient: getConnectionCheckCount count = 6
,08-23 12:28:02.067  8750  9257 E HtcModeClient: Check connection and retry 7 times.
,08-23 12:28:02.067  8750  9257 D HtcModeClient: setConnectionCheckCount count = 7
08-23 12:28:02.067  8750  9257 D HtcModeClient: setupRestart delayedTime = 3000
,08-23 12:28:02.157  1108  3089 I ActivityManager: Recipient 8313
,08-23 12:28:02.237  3747  3747 E PackageActionReceiver: ACTION_PACKAGE_REMOVED,
,08-23 12:28:02.257   556   556 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,08-23 12:28:02.277  8750  8750 D HtcModeClient: setBtPriority priority = on,
08-23 12:28:02.277  8750  8750 D HtcModeClient: unbindBlueToothService
08-23 12:28:02.277  8750  8750 D HtcModeClient: Don't start project servcice,
08-23 12:28:02.277  8750  8750 D HtcModeClient: setEject: MEDIA_EJECT_STATE = true
08-23 12:28:02.277  8750  8750 D HtcModeClient: connectState: CONNECTION_READY = false
08-23 12:28:02.277  8750  8750 D SilentMusic: call stop
08-23 12:28:02.277  8750  8750 W HtcModeClient: leaveProjectMode: It does not enter ProjectMode
08-23 12:28:02.277  8750  9258 W CANMesgAgentLocalSocket: read the terminate packet, so break
,08-23 12:28:02.287  4035  9365 W GmsApplication: Using Auth Proxy for data requests.
08-23 12:28:02.287  3643  9375 I [PluginManager]RegisterService: onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
,08-23 12:28:02.287  8750  8750 D HtcModeClient: onDestroy
,08-23 12:28:02.297  3643  9375 E SQLiteLog: (3850) statement aborts at 41: [UPDATE plugin SET removed=? WHERE package_id IN ( SELECT _id FROM plugin_pkg WHERE package=? )] disk I/O error
,08-23 12:28:02.297  3643  9375 W HTCLOG  : use specified tag [SQLiteDBG], func [0].
08-23 12:28:02.297  3643  9375 W HTCLOG  : mask=0x18
08-23 12:28:02.297  3643  9375 E SQLiteDBG: func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/user/0/com.htc.sense.hsp/databases/registry.db, handle: 0x5570a942c0,
,08-23 12:28:02.297  3643  9375 W [PluginManager]RegisterService: provider may killed!
08-23 12:28:02.297  3643  9375 W [PluginManager]RegisterService: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
,08-23 12:28:02.297  3643  9375 W [PluginManager]RegisterService: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-23 12:28:02.297  3643  9375 W [PluginManager]RegisterService: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:762)
08-23 12:28:02.297  3643  9375 W [PluginManager]RegisterService: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-23 12:28:02.297  3643  9375 W [PluginManager]RegisterService: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-23 12:28:02.297  3643  9375 W [PluginManager]RegisterService: 	at android.database.sqlite.SQLiteDatabase.updateWithOnConflict(SQLiteDatabase.java:1675)
08-23 12:28:02.297  3643  9375 W [PluginManager]RegisterService: 	at android.database.sqlite.SQLiteDatabase.update(SQLiteDatabase.java:1621)
08-23 12:28:02.297  3643  9375 W [PluginManager]RegisterService: 	at com.htc.sense.hsp.opensense.pluginmanager.PluginProvider.update(Unknown Source)
08-23 12:28:02.297  3643  9375 W [PluginManager]RegisterService: 	at android.content.ContentProvider$Transport.update(ContentProvider.java:338)
08-23 12:28:02.297  3643  9375 W [PluginManager]RegisterService: 	at android.content.ContentResolver.update(ContentResolver.java:1398)
08-23 12:28:02.297  3643  9375 W [PluginManager]RegisterService: 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
08-23 12:28:02.297  3643  9375 W [PluginManager]RegisterService: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-23 12:28:02.297  3643  9375 W [PluginManager]RegisterService: 	at android.os.Handler.dispatchMessage(Handler.java:102)
,08-23 12:28:02.297  3643  9375 W [PluginManager]RegisterService: 	at android.os.Looper.loop(Looper.java:155)
08-23 12:28:02.297  3643  9375 W [PluginManager]RegisterService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-23 12:28:02.297  4035  9365 W GmsApplication: Using Auth Proxy for data requests.
08-23 12:28:02.307  1108  3089 I ActivityManager: Killing 8360:com.google.android.talk/u0a103 (adj 15): empty #17
08-23 12:28:02.307  1108  3089 D Process : killProcessQuiet, pid=8360,
08-23 12:28:02.307  1108  3089 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19468 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:238 
,08-23 12:28:02.307  3643  9375 I [PluginManager]RegisterService: handle notify Blinkfeed plugin client changed,
,08-23 12:28:02.317  4035  9365 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gms/databases/app_state.db'.
08-23 12:28:02.317  4035  9365 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-23 12:28:02.317  4035  9365 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-23 12:28:02.317  4035  9365 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-23 12:28:02.317  4035  9365 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219),
08-23 12:28:02.317  4035  9365 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-23 12:28:02.317  4035  9365 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-23 12:28:02.317  4035  9365 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-23 12:28:02.317  4035  9365 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-23 12:28:02.317  4035  9365 E SQLiteDatabase: 	,at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-23 12:28:02.317  4035  9365 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-23 12:28:02.317  4035  9365 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-23 12:28:02.317  4035  9365 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-23 12:28:02.317  4035  9365 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-23 12:28:02.317  4035  9365 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-23 12:28:02.317  4035  9365 E SQLiteDatabase: 	at c,om.google.android.gms.common.e.a.delete(SourceFile:258)
08-23 12:28:02.317  4035  9365 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:322)
08-23 12:28:02.317  4035  9365 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1364)
08-23 12:28:02.317  4035  9365 E SQLiteDatabase: 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
08-23 12:28:02.317  4035  9365 E SQLiteDatabase: 	at com.google.android.gms.appstate.service.AppStateIntentService.onHandleIntent(SourceFile:127)
08-23 12:28:02.317  4035  9365 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-23 12:28:02.317  4035  9365 E SQLiteDatabase: ,	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 12:28:02.317  4035  9365 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:155)
08-23 12:28:02.317  4035  9365 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-23 12:28:02.317  4035  9365 E ClearPendingStateOp: Runtime exception while performing operation
08-23 12:28:02.317  4035  9365 E ClearPendingStateOp: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-23 12:28:02.317  4035  9365 E ClearPendingStateOp: 	,at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-23 12:28:02.317  4035  9365 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-23 12:28:02.317  4035  9365 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-23 12:28:02.317  4035  9365 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-23 12:28:02.317  4035  9365 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-23 12:28:02.317  4035  9365 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182),
08-23 12:28:02.317  4035  9365 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-23 12:28:02.317  4035  9365 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-23 12:28:02.317  4035  9365 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-23 12:28:02.317  4035  9365 E ClearPendingStateOp: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-23 12:28:02.317  4035  9365 E ClearPendingStateOp: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-23 12:28:02.317  4035  9365 E ClearPendingStateOp: 	,at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-23 12:28:02.317  4035  9365 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-23 12:28:02.317  4035  9365 E ClearPendingStateOp: 	at com.google.android.gms.common.e.a.delete(SourceFile:258)
08-23 12:28:02.317  4035  9365 E ClearPendingStateOp: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:322)
08-23 12:28:02.317  4035  9365 E ClearPendingStateOp: 	at android.content.ContentResolver.delete(ContentResolver.java:1364)
08-23 12:28:02.317  4035  9365 E ClearPendingStateOp: 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
08-23 12:28:02.317  4035  9365 E ClearPendingStateOp: ,	at com.google.android.gms.appstate.service.AppStateIntentService.onHandleIntent(SourceFile:127)
08-23 12:28:02.317  4035  9365 E ClearPendingStateOp: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-23 12:28:02.317  4035  9365 E ClearPendingStateOp: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 12:28:02.317  4035  9365 E ClearPendingStateOp: 	at android.os.Looper.loop(Looper.java:155)
08-23 12:28:02.317  4035  9365 E ClearPendingStateOp: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-23 12:28:02.317  4035  9365 F ClearPendingStateOp: Killing (on development devices) due to RuntimeException
08-23 12:28:02.317  4035  9365 F ClearPendingStateOp: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-23 12:28:02.317  4035  9365 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-23 12:28:02.317  4035  9365 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235),
08-23 12:28:02.317  4035  9365 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-23 12:28:02.317  4035  9365 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-23 12:28:02.317  4035  9365 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-23 12:28:02.317  4035  9365 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-23 12:28:02.317  4035  9365 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-23 12:28:02.317  4035  9365 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
,08-23 12:28:02.317  4035  9365 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-23 12:28:02.317  4035  9365 F ClearPendingStateOp: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-23 12:28:02.317  4035  9365 F ClearPendingStateOp: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-23 12:28:02.317  4035  9365 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-23 12:28:02.317  4035  9365 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-23 12:28:02.317  4035  9365 F ClearPendingStateOp: 	at com.google.android.gms.common.e.a.delete(SourceFile:258),
08-23 12:28:02.317  4035  9365 F ClearPendingStateOp: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:322)
08-23 12:28:02.317  4035  9365 F ClearPendingStateOp: 	at android.content.ContentResolver.delete(ContentResolver.java:1364)
08-23 12:28:02.317  4035  9365 F ClearPendingStateOp: 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
08-23 12:28:02.317  4035  9365 F ClearPendingStateOp: 	at com.google.android.gms.appstate.service.AppStateIntentService.onHandleIntent(SourceFile:127)
08-23 12:28:02.317  4035  9365 F ClearPendingStateOp: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-23 12:28:02.317  4035  9365 F ClearPendingStateOp: 	,at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 12:28:02.317  4035  9365 F ClearPendingStateOp: 	at android.os.Looper.loop(Looper.java:155)
08-23 12:28:02.317  4035  9365 F ClearPendingStateOp: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-23 12:28:02.367  1108  3494 I ActivityManager: Recipient 8360
,08-23 12:28:02.437  3545  3545 D Prism.PackageStateRece_: action: android.intent.action.PACKAGE_REMOVED
08-23 12:28:02.457  1108  9376 E DropBoxManagerService: Can't write: system_app_wtf
08-23 12:28:02.457  1108  9376 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop134.tmp: open failed: EROFS (Read-only file system)
08-23 12:28:02.457  1108  9376 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-23 12:28:02.457  1108  9376 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-23 12:28:02.457  1108  9376 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-23 12:28:02.457  1108  9376 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
08-23 12:28:02.457  1108  9376 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
08-23 12:28:02.457  1108  9376 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12682)
08-23 12:28:02.457  1108  9376 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-23 12:28:02.457  1108  9376 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-23 12:28:02.457  1108  9376 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-23 12:28:02.457  1108  9376 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-23 12:28:02.457  1108  9376 E DropBoxManagerService: 	... 5 more
08-23 12:28:02.437  3545  3545 I ContextualWidget: package com.test.thalitest removed
08-23 12:28:02.467  1108  3498 D ErrorReport: HtcErrorReportManager Begin---add error logs to dropbox
08-23 12:28:02.437  3545  4062 I ContextualWidget: handleMessage, what=1004 mode=GettingOut maxcount=8
08-23 12:28:02.467  3545  9377 I ContextualWidget: com.test.thalitest is not installed
08-23 12:28:02.467  3545  9377 W MFUDataManager: loadDownloadItems - skip DownloadItem: ApplicationInfo(id=-1, title=null, componentNameComponentInfo{com.test.thalitest/com.test.thalitest.MainActivity} appsContainer=<ALLAPPS> P=UserHandle{0})
08-23 12:28:02.467  3545  9377 E SQLiteLog: (3850) statement aborts at 16: [DELETE FROM contextualdownload WHERE component_name=?] disk I/O error
08-23 12:28:02.467  3545  9377 W HTCLOG  : use specified tag [SQLiteDBG], func [0].
08-23 12:28:02.467  3545  9377 W HTCLOG  : mask=0x18
08-23 12:28:02.467  3545  9377 E SQLiteDBG: func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/user/0/com.htc.launcher/databases/launcher.db, handle: 0xac5f9ac8
08-23 12:28:02.467  3545  9377 E AndroidRuntime: FATAL EXCEPTION: IntentService[HtcContextualWidgetService]
08-23 12:28:02.467  3545  9377 E AndroidRuntime: Process: com.htc.launcher, PID: 3545
08-23 12:28:02.467  3545  9377 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-23 12:28:02.467  3545  9377 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-23 12:28:02.467  3545  9377 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:762)
08-23 12:28:02.467  3545  9377 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-23 12:28:02.467  3545  9377 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-23 12:28:02.467  3545  9377 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1598)
08-23 12:28:02.467  3545  9377 E AndroidRuntime: 	at com.htc.launcher.LauncherProvider.delete(LauncherProvider.java:377)
08-23 12:28:02.467  3545  9377 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:322)
08-23 12:28:02.467  3545  9377 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentRe,solver.java:1364)
08-23 12:28:02.467  3545  9377 E AndroidRuntime: 	at com.htc.launcher.htcwidget.MFUDataManager$DownloadManager.loadDownloadItems(MFUDataManager.java:2463)
08-23 12:28:02.467  3545  9377 E AndroidRuntime: 	at com.htc.launcher.htcwidget.MFUDataManager$DownloadManager.getDownloadList(MFUDataManager.java:2228)
08-23 12:28:02.467  3545  9377 E AndroidRuntime: 	at com.htc.launcher.htcwidget.MFUDataManager.getDownloadList(MFUDataManager.java:2142)
08-23 12:28:02.467  3545  9377 E AndroidRuntime: 	at com.htc.launcher.htcwidget.MFUDataManager.removeItemsFromDownloadListIfNeed(MFUDataManager.java:2133)
08-23 12:28:02.467  3545  9377 E AndroidRuntime: 	at com.htc.launcher.htcwidget.HtcContextualWidgetService.handlePackageRemoved(HtcContextualWidgetService.java:277)
08-23 12:28:02.467  3545  9377 E AndroidRuntime: 	at com.htc.launcher.htcwidget.HtcContextualWidgetService.onHandleIntent(HtcContextualWidgetService.java:184)
08-23 12:28:02.467  3545  9377 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-23 12:28:02.467  3545  9377 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 12:28:02.467  3545  9377 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:155)
08-23 12:28:02.467  3545  9377 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-23 12:28:02.467  1108  3498 E ActivityManager: App crashed! Process: com.htc.launcher
08-23 12:28:02.477  1108  3498 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
08-23 12:28:02.477  1108  3498 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-23 12:28:02.477  1108  3498 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-23 12:28:02.477  1108  3498 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-23 12:28:02.477  1108  3498 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-23 12:28:02.477  1108  3498 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
08-23 12:28:02.477  1108  3498 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
08-23 12:28:02.477  1108  3498 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getSecretKey(ErrorReportPreference.java:61)
08-23 12:28:02.477  1108  3498 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:302)
08-23 12:28:02.477  1108  3498 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
08-23 12:28:02.477  1108  3498 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
08-23 12:28:02.477  1108  3498 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
08-23 12:28:02.477  1108  3498 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
08-23 12:28:02.477  1108  3498 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
08-23 12:28:02.477  1108  3498 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
08-23 12:28:02.477  1108  3498 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
08-23 12:28:02.477  1108  3498 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-23 12:28:02.477  1108  3498 W System.err: 	at libcore.io.Posix.open(Native Method)
08-23 12:28:02.477  1108  3498 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-23 12:28:02.477  1108  3498 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-23 12:28:02.477  1108  3498 W System.err: 	... 14 more
08-23 12:28:02.477  1108  3498 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
08-23 12:28:02.477  1108  3498 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-23 12:28:02.477  1108  3498 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-23 12:28:02.477  1108  3498 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-23 12:28:02.477  1108  3498 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-23 12:28:02.477  1108  3498 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
08-23 12:28:02.477  1108  3498 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
08-23 12:28:02.477  1108  3498 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getIV(ErrorReportPreference.java:85)
08-23 12:28:02.477  1108  3498 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:303)
08-23 12:28:02.477  1108  3498 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
08-23 12:28:02.477  1108  3498 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
08-23 12:28:02.477  1108  3498 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
08-23 12:28:02.477  1108  3498 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
08-23 12:28:02.477  1108  3498 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
08-23 12:28:02.477  1108  3498 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
08-23 12:28:02.477  1108  3498 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
08-23 12:28:02.477  1108  3498 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-23 12:28:02.487  1108  3498 W System.err: 	at libcore.io.Posix.open(Native Method)
08-23 12:28:02.487  1108  3498 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-23 12:28:02.487  1108  3498 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-23 12:28:02.487  1108  3498 W System.err: 	... 14 more
08-23 12:28:02.497  1108  3252 I ActivityManager: Start proc 9378:pl.tmobile.panel/u0a64 for broadcast pl.tmobile.panel/pl.tmobile.idefix.utils.IdefixUninstallListener
08-23 12:28:02.497  9378  9378 W HTCLOG  : use specified tag [FDManager], func [0].
08-23 12:28:02.497  9378  9378 W HTCLOG  : mask=0x18
08-23 12:28:02.497  1108  3498 W ActivityManager:   Force finishing activity 1 com.htc.launcher/.Launcher
08-23 12:28:02.497  1108  9393 E ErrorReport: HtcErrorReportManager.Error in dumping error information
08-23 12:28:02.497  1108  9393 E ErrorReport: java.io.FileNotFoundException: /data/misc/HTC_HOME_RESTART@1471948082513.dbox_tmp: open failed: EROFS (Read-only file system)
08-23 12:28:02.497  1108  9393 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-23 12:28:02.497  1108  9393 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-23 12:28:02.497  1108  9393 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-23 12:28:02.497  1108  9393 E ErrorReport: 	at com.android.server.am.HtcErrorReportManager$1.run(HtcErrorReportManager.java:458)
08-23 12:28:02.497  1108  9393 E ErrorReport: 	at java.lang.Thread.run(Thread.java:818)
08-23 12:28:02.497  1108  9393 E ErrorReport: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-23 12:28:02.497  1108  9393 E ErrorReport: 	at libcore.io.Posix.open(Native Method)
08-23 12:28:02.497  1108  9393 E ErrorReport: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-23 12:28:02.497  1108  9393 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-23 12:28:02.497  1108  9393 E ErrorReport: 	... 4 more
08-23 12:28:02.507  3545  9377 D Process : killProcess, pid=3545
08-23 12:28:02.507  3545  9377 D Process : com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
08-23 12:28:02.507  3545  9377 W HTCLOG  : use specified tag [Process], func [0].
08-23 12:28:02.507  3545  9377 W HTCLOG  : mask=0x18
08-23 12:28:02.507  1108  3626 W System.err: java.io.FileNotFoundException: /data/system/systemup_pref.xml: open failed: EROFS (Read-only file system)
08-23 12:28:02.507  1108  3626 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-23 12:28:02.507  1108  3626 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-23 12:28:02.507  1108  3626 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-23 12:28:02.507  1108  3626 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-23 12:28:02.507  1108  3626 W System.err: 	at com.htc.upm.HtcSystemUPPreference.writeProperty(HtcSystemUPPreference.java:119)
08-23 12:28:02.507  1108  3626 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setProperty(HtcSystemUPPreference.java:86)
08-23 12:28:02.507  1108  3626 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setLong(HtcSystemUPPreference.java:60)
08-23 12:28:02.507  1108  3626 W System.err: 	at com.htc.upm.HtcSystemUPHandler.addErrorCount(HtcSystemUPHandler.java:294)
08-23 12:28:02.507  1108  3626 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessageInternal(HtcSystemUPHandler.java:73)
08-23 12:28:02.507  1108  3626 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessage(HtcSystemUPHandler.java:46)
08-23 12:28:02.507  1108  3626 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 12:28:02.507  1108  3626 W System.err: 	at android.os.Looper.loop(Looper.java:155)
08-23 12:28:02.507  1108  3626 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-23 12:28:02.507  1108  3626 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-23 12:28:02.507  1108  3626 W System.err: 	at libcore.io.Posix.open(Native Method)
08-23 12:28:02.507  1108  3626 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-23 12:28:02.507  1108  3626 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-23 12:28:02.507  1108  3626 W System.err: 	... 12 more
,08-23 12:28:02.557  4035  9354 W DriveInitializer: Awaiting to be initialized
08-23 12:28:02.557  4035  9401 W DriveInitializer: Background init thread started
,08-23 12:28:02.567  4035  9401 E SQLiteLog: (3850) statement aborts at 4: [DELETE FROM ContentFileDeletionLock43] disk I/O error
,08-23 12:28:02.567  4035  9401 W HTCLOG  : use specified tag [SQLiteDBG], func [0].
08-23 12:28:02.567  4035  9401 W HTCLOG  : mask=0x18
,08-23 12:28:02.567  4035  9401 E SQLiteDBG: func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.google.android.gms/databases/DocList.db, handle: 0x5570a6ae30
,08-23 12:28:02.567  4035  9401 E DocListDatabase: Failed to delete from ContentFileDeletionLock43
08-23 12:28:02.567  4035  9401 E DocListDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-23 12:28:02.567  4035  9401 E DocListDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-23 12:28:02.567  4035  9401 E DocListDatabase: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:762)
08-23 12:28:02.567  4035  9401 E DocListDatabase: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-23 12:28:02.567  4035  9401 E DocListDatabase: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-23 12:28:02.567  4035  9401 E DocListDatabase: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1598)
08-23 12:28:02.567  4035  9401 E DocListDatabase: 	at com.google.android.gms.drive.database.i.a(SourceFile:446)
08-23 12:28:02.567  4035  9401 E DocListDatabase: 	at com.google.android.gms.drive.database.d.i(SourceFile:1103)
08-23 12:28:02.567  4035  9401 E DocListDatabase: 	at com.google.android.gms.drive.v.run(SourceFile:69)
,08-23 12:28:02.577  4035  9401 W DriveInitializer: Background init thread ended
,08-23 12:28:02.577  4035  9354 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
08-23 12:28:02.577  4035  9354 E SQLiteDBG: func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.google.android.gms/databases/DocList.db, handle: 0x5570a6ae30
08-23 12:28:02.577  4035  9401 E AndroidRuntime: FATAL EXCEPTION: Background initialization thread
08-23 12:28:02.577  4035  9401 E AndroidRuntime: Process: com.google.android.gms, PID: 4035
08-23 12:28:02.577  4035  9401 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-23 12:28:02.577  4035  9401 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method),
08-23 12:28:02.577  4035  9401 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:762)
08-23 12:28:02.577  4035  9401 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-23 12:28:02.577  4035  9401 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-23 12:28:02.577  4035  9401 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1598)
08-23 12:28:02.577  4035  9401 E AndroidRuntime: 	at com.google.android.gms.drive.database.i.a(SourceFile:446)
08-23 12:28:02.577  4035  9401 E AndroidRuntime: 	at com.google.android.gms.drive.database.d.i(SourceFile:1103)
08-23 12:28:02.577  4035  9401 E AndroidRuntime: 	at com.google.android.gms.drive.v.run(SourceFile:69)
08-23 12:28:02.577  1108  3252 E ActivityManager: App crashed! Process: com.google.android.gms
08-23 12:28:02.577  4035  9401 D Process : killProcess, pid=4035
08-23 12:28:02.577  4035  9401 D Process : com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
08-23 12:28:02.577  4035  9401 W HTCLOG  : use specified tag [Process], func [0].
08-23 12:28:02.577  4035  9401 W HTCLOG  : mask=0x18
08-23 12:28:02.577  1108  9402 E DropBoxManagerService: Can't write: system_app_crash
08-23 12:28:02.577  1108  9402 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop136.tmp: open failed: EROFS (Read-only file system)
08-23 12:28:02.577  1108  9402 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-23 12:28:02.577  1108  9402 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-23 12:28:02.577  1108  9402 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-23 12:28:02.577  1108  9402 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
08-23 12:28:02.577  1108  9402 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
08-23 12:28:02.577  1108  9402 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12682)
08-23 12:28:02.577  1108  9402 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-23 12:28:02.577  1108  9402 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-23 12:28:02.577  1108  9402 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-23 12:28:02.577  1108  9402 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-23 12:28:02.577  1108  9402 E DropBoxManagerService: 	... 5 more
,08-23 12:28:02.597  1108  4757 E MountService: mkdirs when SD card not mounted/storage/ext_sd/Android/data/pl.tmobile.panel/files/
,08-23 12:28:02.597  9378  9378 W ContextImpl: Failed to ensure directory: /storage/ext_sd/Android/data/pl.tmobile.panel/files
,08-23 12:28:02.607  9378  9378 D IdefixUninstallListener: package_removed = com.test.thalitest,
,08-23 12:28:02.617  1108  3252 I WindowState: WIN DEATH: Window{11ab34e9 u0 com.htc.launcher/com.htc.launcher.Launcher}
,08-23 12:28:02.617  1108  3498 I ActivityManager: Recipient 3545
,08-23 12:28:02.617  1108  3498 I ActivityManager: Process com.htc.launcher (pid 3545) has died,
08-23 12:28:02.617  1108  3498 W ActivityManager: Scheduling restart of crashed service com.htc.launcher/.htcwidget.HtcContextualWidgetService in 1000ms
08-23 12:28:02.627  1108  3498 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.htc.launcher/.Launcher} from uid 0 pid 0 on display 0
08-23 12:28:02.627  1108  3498 V WindowManager: addAppToken: AppWindowToken{1883cabb token=Token{3eb34b4a ActivityRecord{3cb48b5 u0 com.htc.launcher/.Launcher t452}}} to stack=0 task=452 at 0
08-23 12:28:02.637  9378  9378 W HTCLOG  : use specified tag [SQLiteConnection], func [0].
08-23 12:28:02.637  9378  9378 W HTCLOG  : mask=0x18
,08-23 12:28:02.637  9378  9378 E SQLiteDatabase: Failed to open database '/data/data/pl.tmobile.panel/databases/idefix.db'.,
08-23 12:28:02.637  9378  9378 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-23 12:28:02.637  9378  9378 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-23 12:28:02.637  9378  9378 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-23 12:28:02.637  9378  9378 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-23 12:28:02.637  9378  9378 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-23 12:28:02.637  9378  9378 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-23 12:28:02.637  9378  9378 E SQLiteDatabase: ,	,at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-23 12:28:02.637  9378  9378 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-23 12:28:02.637  9378  9378 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-23 12:28:02.637  9378  9378 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-23 12:28:02.637  9378  9378 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-23 12:28:02.637  9378  9378 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-23 12:28:02.637  9378  9378 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-23 12:28:02.637  9378  9378 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-23 12:28:02.637  9378  9378 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-23 12:28:02.637  9378  9378 E SQLiteDatabase: 	at com.j256.ormlite.android.AndroidConnectionSource.getReadWriteConnection(SourceFile:66)
08-23 12:28:02.637  9378  9378 E SQLiteDatabase: 	at com.j256.ormlite.android.AndroidConnectionSource.getReadOnlyConnection(SourceFile:54)
08-23 12:28:02.637  9378  9378 E SQLiteDatabase: 	at com.j256.ormlite.stmt.StatementExecutor.buildIterator(SourceFile:243)
08-23 12:28:02.637  9378  9378 E SQLiteDatabase: 	,at com.j256.ormlite.stmt.StatementExecutor.query(SourceFile:196)
08-23 12:28:02.637  9378  9378 E SQLiteDatabase: 	at com.j256.ormlite.dao.BaseDaoImpl.query(SourceFile:265)
08-23 12:28:02.637  9378  9378 E SQLiteDatabase: 	at pl.tmobile.idefix.utils.IdefixUninstallListener.onReceive(SourceFile:43)
08-23 12:28:02.637  9378  9378 E SQLiteDatabase: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2719)
08-23 12:28:02.637  9378  9378 E SQLiteDatabase: 	at android.app.ActivityThread.access$1700(ActivityThread.java:151)
,08-23 12:28:02.637  9378  9378 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1467)
08-23 12:28:02.637  9378  9378 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 12:28:02.637  9378  9378 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:155)
08-23 12:28:02.637  9378  9378 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
08-23 12:28:02.637  9378  9378 E SQLiteDatabase: ,	at java.lang.reflect.Method.invoke(Native Method)
08-23 12:28:02.637  9378  9378 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-23 12:28:02.637  9378  9378 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
08-23 12:28:02.637  9378  9378 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
08-23 12:28:02.637  1108  4754 I ActivityManager: Recipient 4035
08-23 12:28:02.637  9378  9378 W System.err: java.sql.SQLException: Getting a writable database from helper a@2f300e2f failed
,08-23 12:28:02.637  1108  3557 D PMS     : handleWLDeath(21cd5967): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1
08-23 12:28:02.637  9378  9378 W System.err: 	at com.j256.ormlite.misc.SqlExceptionUtil.create(SourceFile:22)
08-23 12:28:02.637  1108  3081 D WifiService: Client connection lost with reason: 4
08-23 12:28:02.637  9378  9378 W System.err: 	at com.j256.ormlite.android.AndroidConnectionSource.getReadWriteConnection(SourceFile:68)
08-23 12:28:02.637  1108  3252 D PMS     : handleWLDeath(a733b0f): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1
08-23 12:28:02.637  9378  9378 W System.err: 	at com.j256.ormlite.android.AndroidConnectionSource.getReadOnlyConnection(SourceFile:54)
08-23 12:28:02.637  1108  3494 D PMS     : handleWLDeath(133e1def): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1
08-23 12:28:02.637  9378  9378 W System.err: 	at com.j256.ormlite.stmt.StatementExecutor.buildIterator(SourceFile:243)
08-23 12:28:02.637  1108  3498 I ActivityManager: Start proc 9404:com.htc.launcher/u0a56 for activity com.htc.launcher/.Launcher
08-23 12:28:02.637  9378  9378 W System.err: 	at com.j256.ormlite.stmt.StatementExecutor.query(SourceFile:196)
08-23 12:28:02.647  1108  4754 I ActivityManager: Process com.google.android.gms (pid 4035) has died
08-23 12:28:02.637  9378  9378 W System.err: 	at com.j256.ormlite.dao.BaseDaoImpl.query(SourceFile:265)
08-23 12:28:02.647  1108  4754 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.analytics.service.AnalyticsService in 1000ms
08-23 12:28:02.637  9378  9378 W System.err: 	at pl.tmobile.idefix.utils.IdefixUninstallListener.onReceive(SourceFile:43)
08-23 12:28:02.647  1108  4754 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 11000ms
08-23 12:28:02.637  9378  9378 W System.err: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2719)
08-23 12:28:02.647  1108  4754 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 21000ms
08-23 12:28:02.637  9378  9378 W System.err: 	at android.app.ActivityThread.access$1700(ActivityThread.java:151)
08-23 12:28:02.647  1108  3490 I ActivityManager: Killing 8603:com.htc.mobiledata/u0a40 (adj 15): empty #17
08-23 12:28:02.637  9378  9378 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1467)
08-23 12:28:02.637  9378  9378 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 12:28:02.637  9378  9378 W System.err: 	at android.os.Looper.loop(Looper.java:155)
08-23 12:28:02.637  9378  9378 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
08-23 12:28:02.637  9378  9378 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 12:28:02.637  9378  9378 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-23 12:28:02.637  9378  9378 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
08-23 12:28:02.637  9378  9378 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
08-23 12:28:02.637  9378  9378 W System.err: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-23 12:28:02.637  9378  9378 W System.err: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-23 12:28:02.637  9378  9378 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
,08-23 12:28:02.637  9378  9378 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-23 12:28:02.637  9378  9378 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-23 12:28:02.637  9378  9378 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-23 12:28:02.637  9378  9378 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-23 12:28:02.637  9378  9378 W System.err: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-23 12:28:02.637  9378  9378 W System.err: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
,08-23 12:28:02.637  9378  9378 W System.err: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-23 12:28:02.637  9378  9378 W System.err: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-23 12:28:02.637  9378  9378 W System.err: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-23 12:28:02.637  9378  9378 W System.err: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-23 12:28:02.637  9378  9378 W System.err: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-23 12:28:02.637  9378  9378 W System.err: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
,08-23 12:28:02.637  9378  9378 W System.err: 	at com.j256.ormlite.android.AndroidConnectionSource.getReadWriteConnection(SourceFile:66)
08-23 12:28:02.637  9378  9378 W System.err: 	... 15 more
08-23 12:28:02.647  1108  3490 D Process : killProcessQuiet, pid=8603
08-23 12:28:02.647  1108  3490 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19468 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:238 
08-23 12:28:02.647  9404  9404 W HTCLOG  : use specified tag [FDManager], func [0].
08-23 12:28:02.647  9404  9404 W HTCLOG  : mask=0x18
,08-23 12:28:02.727  1108  3524 I ActivityManager: Recipient 8603,
,08-23 12:28:02.777  1108  3490 I ActivityManager: Killing 8472:com.htc.calendar/u0a6 (adj 15): empty #17
08-23 12:28:02.777  1108  3490 D Process : killProcessQuiet, pid=8472
08-23 12:28:02.777  1108  3490 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19468 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19311 
,08-23 12:28:02.787  6577  9427 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,08-23 12:28:02.807  9404  9404 I MultiDex: VM with version 2.1.0 has multidex support
,08-23 12:28:02.807  9404  9404 I MultiDex: install
08-23 12:28:02.807  9404  9404 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-23 12:28:02.817  9404  9404 D FaceDetectTask: sOmronFaceDetectTaskClass : null
,08-23 12:28:02.817  9404  9404 D FaceDetectTask: checkIsOmronEnable start
08-23 12:28:02.817  9404  9404 D MorphoNativeMemoryAllocator: load libmorpho_memory_allocator.so
,08-23 12:28:02.817  9404  9404 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask,
08-23 12:28:02.817  9404  9404 D FaceDetectTask: IsOmronEnable : true
08-23 12:28:02.817  9404  9404 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
08-23 12:28:02.817  9404  9404 D FaceDetectTask: sOmronFaceDetectTaskClass : null
,08-23 12:28:02.827  9404  9404 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask,
08-23 12:28:02.827  9404  9404 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
,08-23 12:28:02.827  9404  9404 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
08-23 12:28:02.827  9404  9404 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
08-23 12:28:02.827  9404  9404 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
08-23 12:28:02.827  9404  9404 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
,08-23 12:28:02.827  9404  9404 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
08-23 12:28:02.827  9404  9404 I HighlightSelectCacheHelper: [custom highlight] loadHighlightSelection()
08-23 12:28:02.827  9404  9404 W HTCLOG  : use specified tag [SQLiteConnection], func [0].
08-23 12:28:02.827  9404  9404 W HTCLOG  : mask=0x18
08-23 12:28:02.827  9404  9404 E SQLiteDatabase: Failed to open database '/data/user/0/com.htc.launcher/databases/highlight_selection.db'.
08-23 12:28:02.827  9404  9404 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-23 12:28:02.827  9404  9404 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-23 12:28:02.827  9404  9404 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-23 12:28:02.827  9404  9404 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-23 12:28:02.827  9404  9404 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-23 12:28:02.827  9404  9404 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-23 12:28:02.827  9404  9404 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-23 12:28:02.827  9404  9404 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-23 12:28:02.827  9404  9404 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-23 12:28:02.827  9404  9404 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-23 12:28:02.827  9404  9404 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-23 12:28:02.827  9404  9404 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-23 12:28:02.827  9404  9404 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-23 12:28:02.827  9404  9404 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-23 12:28:02.827  9404  9404 E SQLiteDatabase: 	at com.htc.launcher.feeds.HighlightSelectCacheHelper.loadHighlightSelection(HighlightSelectCacheHelper.java:319)
08-23 12:28:02.827  9404  9404 E SQLiteDatabase: 	at com.htc.launcher.feeds.HighlightSelectCacheHelper.onCreate(HighlightSelectCacheHelper.java:83)
08-23 12:28:02.827  9404  9404 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1712)
08-23 12:28:02.827  9404  9404 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1681)
08-23 12:28:02.827  9404  9404 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5429)
08-23 12:28:02.827  9404  9404 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5000)
08-23 12:28:02.827  9404  9404 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4940)
08-23 12:28:02.827  9404  9404 E SQLiteDatabase: 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
08-23 12:28:02.827  9404  9404 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1442)
08-23 12:28:02.827  9404  9404 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 12:28:02.827  9404  9404 E SQLiteDatabase: ,	at android.os.Looper.loop(Looper.java:155)
08-23 12:28:02.827  9404  9404 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
08-23 12:28:02.827  9404  9404 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 12:28:02.827  9404  9404 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-23 12:28:02.827  9404  9404 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
08-23 12:28:02.827  9404  9404 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
08-23 12:28:02.827  6577  9427 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error,
08-23 12:28:02.827  9404  9404 W System.err: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-23 12:28:02.827  9404  9404 W System.err: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-23 12:28:02.827  9404  9404 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-23 12:28:02.827  9404  9404 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
,08-23 12:28:02.827  9404  9404 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-23 12:28:02.827  9404  9404 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-23 12:28:02.827  9404  9404 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-23 12:28:02.827  9404  9404 W System.err: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-23 12:28:02.827  9404  9404 W System.err: ,	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-23 12:28:02.827  9404  9404 W System.err: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-23 12:28:02.827  9404  9404 W System.err: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-23 12:28:02.827  9404  9404 W System.err: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-23 12:28:02.827  9404  9404 W System.err: ,	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-23 12:28:02.827  9404  9404 W System.err: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-23 12:28:02.827  9404  9404 W System.err: 	at com.htc.launcher.feeds.HighlightSelectCacheHelper.loadHighlightSelection(HighlightSelectCacheHelper.java:319)
08-23 12:28:02.827  9404  9404 W System.err: 	at com.htc.launcher.feeds.HighlightSelectCacheHelper.onCreate(HighlightSelectCacheHelper.java:83)
,08-23 12:28:02.827  6577  9427 W HTCLOG  : use specified tag [SQLiteDBG], func [0].
08-23 12:28:02.827  6577  9427 W HTCLOG  : mask=0x18
08-23 12:28:02.827  9404  9404 W System.err: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1712)
08-23 12:28:02.827  9404  9404 W System.err: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1681)
,08-23 12:28:02.827  6577  9427 E SQLiteDBG: func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db, handle: 0x5570a56390
08-23 12:28:02.827  9404  9404 W System.err: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5429)
08-23 12:28:02.827  9404  9404 W System.err: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5000)
08-23 12:28:02.827  9404  9404 W System.err: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4940)
,08-23 12:28:02.827  9404  9404 W System.err: 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
08-23 12:28:02.827  9404  9404 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1442)
08-23 12:28:02.827  9404  9404 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
,08-23 12:28:02.827  9404  9404 W System.err: 	at android.os.Looper.loop(Looper.java:155)
08-23 12:28:02.827  9404  9404 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
08-23 12:28:02.827  9404  9404 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 12:28:02.827  9404  9404 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
,08-23 12:28:02.827  9404  9404 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
08-23 12:28:02.827  9404  9404 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
08-23 12:28:02.837  9404  9404 E SQLiteDatabase: Failed to open database '/data/user/0/com.htc.launcher/databases/externalapp.db'.
08-23 12:28:02.837  9404  9404 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-23 12:28:02.837  9404  9404 E SQLiteDatabase: ,	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-23 12:28:02.837  9404  9404 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-23 12:28:02.837  9404  9404 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-23 12:28:02.837  9404  9404 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-23 12:28:02.837  9404  9404 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-23 12:28:02.837  9404  9404 E SQLiteDatabase: ,	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-23 12:28:02.837  9404  9404 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-23 12:28:02.837  9404  9404 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-23 12:28:02.837  9404  9404 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-23 12:28:02.837  9404  9404 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-23 12:28:02.837  9404  9404 E SQLiteDatabase: ,	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-23 12:28:02.837  9404  9404 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-23 12:28:02.837  9404  9404 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-23 12:28:02.837  9404  9404 E SQLiteDatabase: 	at com.htc.launcher.ExternalAppStateProvider.reInitalizeExternalAppsStateMaxId(ExternalAppStateProvider.java:103)
08-23 12:28:02.837  9404  9404 E SQLiteDatabase: 	at com.htc.launcher.ExternalAppStateProvider.onCreate(ExternalAppStateProvider.java:25)
,08-23 12:28:02.837  9404  9404 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1712)
08-23 12:28:02.837  9404  9404 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1681)
08-23 12:28:02.837  9404  9404 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5429)
08-23 12:28:02.837  9404  9404 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5000)
08-23 12:28:02.837  9404  9404 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4940),
08-23 12:28:02.837  9404  9404 E SQLiteDatabase: 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
08-23 12:28:02.837  9404  9404 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1442)
08-23 12:28:02.837  9404  9404 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 12:28:02.837  9404  9404 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:155)
08-23 12:28:02.837  9404  9404 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
08-23 12:28:02.837  9404  9404 E SQLiteDatabase: ,	at java.lang.reflect.Method.invoke(Native Method)
08-23 12:28:02.837  9404  9404 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-23 12:28:02.837  9404  9404 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
08-23 12:28:02.837  9404  9404 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
08-23 12:28:02.837  9404  9404 E AndroidRuntime: FATAL EXCEPTION: main
08-23 12:28:02.837  9404  9404 E AndroidRuntime: Process: com.htc.launcher, PID: 9404,
08-23 12:28:02.837  9404  9404 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.htc.launcher.ExternalAppStateProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-23 12:28:02.837  9404  9404 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5432)
08-23 12:28:02.837  9404  9404 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5000)
08-23 12:28:02.837  9404  9404 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4940)
08-23 12:28:02.837  9404  9404 E AndroidRuntime: 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
08-23 12:28:02.837  9404  9404 E AndroidRuntime: ,	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1442)
08-23 12:28:02.837  9404  9404 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 12:28:02.837  9404  9404 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:155)
08-23 12:28:02.837  9404  9404 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
08-23 12:28:02.837  9404  9404 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 12:28:02.837  9404  9404 E AndroidRuntime: ,	at java.lang.reflect.Method.invoke(Method.java:372)
08-23 12:28:02.837  9404  9404 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
08-23 12:28:02.837  9404  9404 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
08-23 12:28:02.837  9404  9404 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-23 12:28:02.837  9404  9404 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-23 12:28:02.837  9404  9404 E AndroidRuntime: 	,at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-23 12:28:02.837  9404  9404 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-23 12:28:02.837  9404  9404 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-23 12:28:02.837  9404  9404 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-23 12:28:02.837  9404  9404 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-23 12:28:02.837  9404  9404 E AndroidRuntime: ,	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-23 12:28:02.837  9404  9404 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-23 12:28:02.837  9404  9404 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-23 12:28:02.837  9404  9404 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-23 12:28:02.837  9404  9404 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-23 12:28:02.837  9404  9404 E AndroidRuntime: ,	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-23 12:28:02.837  9404  9404 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-23 12:28:02.837  9404  9404 E AndroidRuntime: 	at com.htc.launcher.ExternalAppStateProvider.reInitalizeExternalAppsStateMaxId(ExternalAppStateProvider.java:103)
08-23 12:28:02.837  9404  9404 E AndroidRuntime: 	at com.htc.launcher.ExternalAppStateProvider.onCreate(ExternalAppStateProvider.java:25)
08-23 12:28:02.837  9404  9404 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1712)
,08-23 12:28:02.837  9404  9404 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1681)
08-23 12:28:02.837  9404  9404 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5429)
08-23 12:28:02.837  9404  9404 E AndroidRuntime: 	... 11 more
,08-23 12:28:02.887  1108  3089 I ActivityManager: Recipient 8472,
,08-23 12:28:02.887  1108  3524 E ActivityManager: App crashed! Process: com.htc.launcher,
08-23 12:28:02.887  1108  3524 D ErrorReport: HtcErrorReportManager Begin---add error logs to dropbox
08-23 12:28:02.897  1108  3524 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
08-23 12:28:02.897  1108  3524 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-23 12:28:02.897  1108  3524 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
,08-23 12:28:02.897  1108  3524 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-23 12:28:02.897  1108  3524 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-23 12:28:02.897  1108  3524 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
08-23 12:28:02.897  1108  3524 W System.err: ,	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
08-23 12:28:02.897  1108  3524 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getSecretKey(ErrorReportPreference.java:61)
08-23 12:28:02.897  1108  3524 W ActivityManager:   Force finishing activity 1 com.htc.launcher/.Launcher
08-23 12:28:02.897  1108  3524 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:302)
08-23 12:28:02.897  1108  9436 E ErrorReport: HtcErrorReportManager.Error in dumping error information
08-23 12:28:02.897  1108  9436 E ErrorReport: java.io.FileNotFoundException: /data/misc/HTC_HOME_RESTART@1471948082913.dbox_tmp: open failed: EROFS (Read-only file system)
08-23 12:28:02.897  1108  9436 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-23 12:28:02.897  1108  9436 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-23 12:28:02.897  1108  9436 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-23 12:28:02.897  1108  9436 E ErrorReport: 	at com.android.server.am.HtcErrorReportManager$1.run(HtcErrorReportManager.java:458)
08-23 12:28:02.897  1108  9436 E ErrorReport: 	at java.lang.Thread.run(Thread.java:818)
08-23 12:28:02.897  1108  9436 E ErrorReport: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-23 12:28:02.897  1108  9436 E ErrorReport: 	,at libcore.io.Posix.open(Native Method)
08-23 12:28:02.897  1108  9436 E ErrorReport: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-23 12:28:02.897  1108  9436 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-23 12:28:02.897  1108  9436 E ErrorReport: 	... 4 more
08-23 12:28:02.897  1108  3524 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
08-23 12:28:02.897  1108  3524 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
,08-23 12:28:02.897  1108  3524 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
08-23 12:28:02.897  1108  3524 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
08-23 12:28:02.897  1108  3524 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
08-23 12:28:02.897  1108  3524 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
08-23 12:28:02.897  1108  3524 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
08-23 12:28:02.897  1108  3524 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-23 12:28:02.897  1108  3524 W System.err: 	at libcore.io.Posix.open(Native Method)
08-23 12:28:02.897  1108  3524 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-23 12:28:02.897  1108  3524 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-23 12:28:02.897  1108  3524 W System.err: 	... 14 more
08-23 12:28:02.897  1108  3524 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
08-23 12:28:02.897  1108  3524 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-23 12:28:02.897  1108  3524 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-23 12:28:02.897  1108  3524 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-23 12:28:02.897  1108  3524 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-23 12:28:02.897  1108  3524 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
08-23 12:28:02.897  1108  3524 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
,08-23 12:28:02.897  1108  3524 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getIV(ErrorReportPreference.java:85)
08-23 12:28:02.897  1108  3524 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:303)
08-23 12:28:02.897  1108  3524 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
08-23 12:28:02.897  1108  3524 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
08-23 12:28:02.897  1108  3524 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
08-23 12:28:02.897  1108  3524 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
08-23 12:28:02.897  1108  3524 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
08-23 12:28:02.897  1108  3524 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
08-23 12:28:02.897  1108  3524 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
08-23 12:28:02.897  1108  3524 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-23 12:28:02.897  1108  3524 W System.err: 	at libcore.io.Posix.open(Native Method)
08-23 12:28:02.897  1108  3524 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-23 12:28:02.897  1108  3524 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-23 12:28:02.897  1108  3524 W System.err: 	... 14 more
08-23 12:28:02.897  1108  3626 W System.err: java.io.FileNotFoundException: /data/system/systemup_pref.xml: open failed: EROFS (Read-only file system)
08-23 12:28:02.907  1108  3626 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-23 12:28:02.907  1108  3626 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-23 12:28:02.907  1108  3626 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-23 12:28:02.907  1108  3626 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-23 12:28:02.907  1108  3626 W System.err: 	at com.htc.upm.HtcSystemUPPreference.writeProperty(HtcSystemUPPreference.java:119)
08-23 12:28:02.907  1108  3626 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setProperty(HtcSystemUPPreference.java:86)
08-23 12:28:02.907  1108  3626 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setLong(HtcSystemUPPreference.java:60)
08-23 12:28:02.907  1108  3626 W System.err: 	at com.htc.upm.HtcSystemUPHandler.addErrorCount(HtcSystemUPHandler.java:294)
,08-23 12:28:02.907  1108  3626 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessageInternal(HtcSystemUPHandler.java:73)
08-23 12:28:02.907  1108  3626 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessage(HtcSystemUPHandler.java:46)
08-23 12:28:02.907  1108  3626 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 12:28:02.907  1108  3626 W System.err: 	at android.os.Looper.loop(Looper.java:155)
08-23 12:28:02.907  1108  3626 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-23 12:28:02.907  1108  3626 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-23 12:28:02.907  1108  3626 W System.err: 	at libcore.io.Posix.open(Native Method)
08-23 12:28:02.907  1108  3626 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
,08-23 12:28:02.907  1108  3626 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-23 12:28:02.907  1108  3626 W System.err: 	... 12 more
08-23 12:28:02.907  6577  9427 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file /data/data/com.google.android.googlequicksearchbox/shared_prefs/uncaught_exception_handler_stats.xml
08-23 12:28:02.907  6577  9427 E AndroidRuntime: FATAL EXCEPTION: IntentService[UpdateCorporaService]
08-23 12:28:02.907  6577  9427 E AndroidRuntime: Process: com.google.android.googlequicksearchbox:search, PID: 6577
08-23 12:28:02.907  6577  9427 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-23 12:28:02.907  6577  9427 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-23 12:28:02.907  6577  9427 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:583)
08-23 12:28:02.907  6577  9427 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-23 12:28:02.907  6577  9427 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-23 12:28:02.907  6577  9427 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:557)
08-23 12:28:02.907  6577  9427 E AndroidRuntime: 	,at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:461)
08-23 12:28:02.907  6577  9427 E AndroidRuntime: 	at com.google.android.search.core.icingsync.b.d(ApplicationsHelper.java:193)
08-23 12:28:02.907  6577  9427 E AndroidRuntime: 	at com.google.android.search.core.icingsync.ar.g(InternalIcingCorporaProvider.java:548)
08-23 12:28:02.907  6577  9427 E AndroidRuntime: 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:282)
08-23 12:28:02.907  6577  9427 E AndroidRuntime: 	at android.content.ContentProvider$Transport.update(ContentProvider.java:338)
08-23 12:28:02.907  6577  9427 E AndroidRuntime: 	at android.content.ContentResolver.update(ContentResolver.java:1398)
08-23 12:28:02.907  6577  9427 E AndroidRuntime: 	at com.google.android.search.core.icingsync.ba.Zh(UpdateIcingCorporaService.java:358)
08-23 12:28:02.907  6577  9427 E AndroidRuntime: 	at com.google.android.search.core.icingsync.bc.Zj(UpdateIcingCorporaService.java:297)
08-23 12:28:02.907  6577  9427 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(UpdateIcingCorporaService.java:270)
08-23 12:28:02.907  6577  9427 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.ac(UpdateIcingCorporaService.java:194),
08-23 12:28:02.907  6577  9427 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(UpdateIcingCorporaService.java:182)
08-23 12:28:02.907  6577  9427 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-23 12:28:02.907  6577  9427 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 12:28:02.907  6577  9427 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:155)
08-23 12:28:02.907  6577  9427 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-23 12:28:02.917  1108  3649 I ActivityManager: Start proc 9438:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
08-23 12:28:02.917  1108  3673 E ActivityManager: App crashed! Process: com.google.android.googlequicksearchbox:search
08-23 12:28:02.917  9404  9404 D Process : killProcess, pid=9404
08-23 12:28:02.917  9404  9404 D Process : com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
08-23 12:28:02.917  9404  9404 W HTCLOG  : use specified tag [Process], func [0].
08-23 12:28:02.917  9404  9404 W HTCLOG  : mask=0x18
08-23 12:28:02.917  9438  9438 W HTCLOG  : use specified tag [FDManager], func [0].
08-23 12:28:02.917  9438  9438 W HTCLOG  : mask=0x18
,08-23 12:28:02.917  6577  9427 D Process : killProcess, pid=6577
08-23 12:28:02.917  1108  9452 E DropBoxManagerService: Can't write: system_app_crash
08-23 12:28:02.917  1108  9452 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop138.tmp: open failed: EROFS (Read-only file system)
08-23 12:28:02.917  1108  9452 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-23 12:28:02.917  1108  9452 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-23 12:28:02.917  1108  9452 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-23 12:28:02.917  1108  9452 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
08-23 12:28:02.917  1108  9452 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
08-23 12:28:02.917  1108  9452 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12682)
08-23 12:28:02.917  1108  9452 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-23 12:28:02.917  1108  9452 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-23 12:28:02.917  1108  9452 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-23 12:28:02.917  1108  9452 E DropBoxManagerService: 	,at libcore.io.IoBridge.open(IoBridge.java:442)
08-23 12:28:02.917  1108  9452 E DropBoxManagerService: 	... 5 more
08-23 12:28:02.927  6577  9427 D Process : com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 com.google.android.velvet.ab.uncaughtException:97 java.lang.ThreadGroup.uncaughtException:693 
,08-23 12:28:02.927  6577  9427 W HTCLOG  : use specified tag [Process], func [0].
08-23 12:28:02.927  6577  9427 W HTCLOG  : mask=0x18
,08-23 12:28:02.967  9438  9438 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1830 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2719 ,
,08-23 12:28:02.977  1108  3498 D PMS     : acquireWL(1eb17d84): PARTIAL_WAKE_LOCK  AsyncService 0x1 8861 10128 null,
,08-23 12:28:02.977   492   492 E lowmemorykiller: Error writing /proc/6577/oom_score_adj; errno=22,
08-23 12:28:02.977   492   492 E lowmemorykiller: Error writing /proc/6577/oom_score_adj; errno=22
08-23 12:28:02.977  9438  9461 W HTCLOG  : use specified tag [SQLiteConnection], func [0].
08-23 12:28:02.977  9438  9461 W HTCLOG  : mask=0x18
,08-23 12:28:02.977  1108  1128 D PMS     : releaseWL(1eb17d84): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
08-23 12:28:02.987  9438  9461 E SQLiteDatabase: Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
08-23 12:28:02.987  9438  9461 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.,
08-23 12:28:02.987  9438  9461 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-23 12:28:02.987  9438  9461 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-23 12:28:02.987  9438  9461 E SQLiteDatabase: ,	,at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-23 12:28:02.987  9438  9461 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-23 12:28:02.987  9438  9461 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-23 12:28:02.987  9438  9461 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-23 12:28:02.987  9438  9461 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-23 12:28:02.987  9438  9461 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
,08-23 12:28:02.987  9438  9461 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-23 12:28:02.987  9438  9461 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-23 12:28:02.987  9438  9461 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-23 12:28:02.987  9438  9461 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-23 12:28:02.987  9438  9461 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-23 12:28:02.987  9438  9461 E SQLiteDatabase: 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:402)
08-23 12:28:02.987  9438  9461 E SQLiteDatabase: 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:396)
08-23 12:28:02.987  9438  9461 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-23 12:28:02.987  9438  9461 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 12:28:02.987  9438  9461 E SQLiteDatabase: ,	at android.os.Looper.loop(Looper.java:155)
08-23 12:28:02.987  9438  9461 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-23 12:28:02.987  9438  9461 E AndroidRuntime: FATAL EXCEPTION: IntentService[KeyChainService]
08-23 12:28:02.987  9438  9461 E AndroidRuntime: Process: com.android.keychain, PID: 9438
08-23 12:28:02.987  9438  9461 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-23 12:28:02.987  9438  9461 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method),
08-23 12:28:02.987  9438  9461 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-23 12:28:02.987  9438  9461 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-23 12:28:02.987  9438  9461 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-23 12:28:02.987  9438  9461 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-23 12:28:02.987  9438  9461 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-23 12:28:02.987  9438  9461 E AndroidRuntime: ,	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-23 12:28:02.987  9438  9461 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-23 12:28:02.987  9438  9461 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-23 12:28:02.987  9438  9461 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-23 12:28:02.987  9438  9461 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-23 12:28:02.987  9438  9461 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-23 12:28:02.987  9438  9461 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-23 12:28:02.987  9438  9461 E AndroidRuntime: 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:402)
08-23 12:28:02.987  9438  9461 E AndroidRuntime: 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:396)
08-23 12:28:02.987  9438  9461 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-23 12:28:02.987  9438  9461 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 12:28:02.987  9438  9461 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:155)
08-23 12:28:02.987  9438  9461 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-23 12:28:02.987  1108  3089 D ErrorReport: HtcErrorReportManager Begin---add error logs to dropbox
08-23 12:28:02.987  9118  9118 I DeviceManagement: PackageUpdateReceiver: vvv Package removed: [com.test.thalitest]
08-23 12:28:02.987  1108  3089 E ActivityManager: App crashed! Process: com.android.keychain
08-23 12:28:02.987  9118  9118 I DeviceManagement: WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.PackageUpdateWorkflow] args=[Bundle[{packageName=com.test.thalitest, operation=3}]]
08-23 12:28:02.987  1108  3089 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
08-23 12:28:02.987  1108  3089 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-23 12:28:02.987  1108  3089 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-23 12:28:02.987  1108  9464 E ErrorReport: HtcErrorReportManager.Error in dumping error information
08-23 12:28:02.987  1108  9464 E ErrorReport: java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1471948083004.dbox_tmp: open failed: EROFS (Read-only file system)
08-23 12:28:02.987  1108  9464 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-23 12:28:02.987  1108  9464 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-23 12:28:02.987  1108  9464 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-23 12:28:02.987  1108  9464 E ErrorReport: 	at com.android.server.am.HtcErrorReportManager$1.run(HtcErrorReportManager.java:458)
08-23 12:28:02.987  1108  9464 E ErrorReport: 	at java.lang.Thread.run(Thread.java:818)
08-23 12:28:02.987  1108  9464 E ErrorReport: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-23 12:28:02.987  1108  9464 E ErrorReport: 	at libcore.io.Posix.open(Native Method)
08-23 12:28:02.987  1108  9464 E ErrorReport: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-23 12:28:02.987  1108  9464 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-23 12:28:02.987  1108  9464 E ErrorReport: 	... 4 more
08-23 12:28:02.987  1108  3089 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-23 12:28:02.987  1108  3089 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-23 12:28:02.987  1108  3089 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.ja,va:142)
08-23 12:28:02.987  1108  3089 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
08-23 12:28:02.987  1108  3089 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getSecretKey(ErrorReportPreference.java:61)
08-23 12:28:02.987  1108  3089 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:302)
08-23 12:28:02.987  1108  3089 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
08-23 12:28:02.987  1108  3089 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
08-23 12:28:02.987  1108  3089 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
08-23 12:28:02.987  1108  3089 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
08-23 12:28:02.987  1108  3089 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
08-23 12:28:02.987  1108  3089 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
08-23 12:28:02.987  1108  3089 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
08-23 12:28:02.987  1108  3089 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-23 12:28:02.987  1108  3089 W System.err: 	at libcore.io.Posix.open(Native Method)
08-23 12:28:02.987  1108  3089 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-23 12:28:02.987  1108  3089 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-23 12:28:02.987  1108  3089 W System.err: 	... 14 more
08-23 12:28:02.987  1108  3089 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
08-23 12:28:02.987  1108  3089 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-23 12:28:02.987  1108  3089 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-23 12:28:02.987  1108  3089 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-23 12:28:02.987  1108  3089 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-23 12:28:02.987  1108  3089 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
08-23 12:28:02.987  1108  3089 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
08-23 12:28:02.987  1108  3089 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getIV(ErrorReportPreference.java:85)
08-23 12:28:02.987  1108  3089 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:303)
08-23 12:28:02.987  1108  3089 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
08-23 12:28:02.987  1108  3089 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
08-23 12:28:02.987  1108  3089 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
08-23 12:28:02.987  1108  3089 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
08-23 12:28:02.987  1108  3089 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
08-23 12:28:02.987  1108  3089 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
08-23 12:28:02.987  1108  3089 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
08-23 12:28:02.987  1108  3089 W System.err: Caused by: ,android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-23 12:28:02.987  1108  3089 W System.err: 	at libcore.io.Posix.open(Native Method)
08-23 12:28:02.987  1108  3089 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-23 12:28:02.987  1108  3089 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-23 12:28:02.987  1108  3089 W System.err: 	... 14 more
08-23 12:28:02.987  9118  9118 I DeviceManagement: WorkflowService: Starting workflow service
08-23 12:28:02.987  9438  9461 D Process : killProcess, pid=9438
08-23 12:28:02.987  9438  9461 D Process : com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
08-23 12:28:02.987  9438  9461 W HTCLOG  : use specified tag [Process], func [0].
08-23 12:28:02.987  9438  9461 W HTCLOG  : mask=0x18
08-23 12:28:02.997  1108  3626 W System.err: java.io.FileNotFoundException: /data/system/systemup_pref.xml: open failed: EROFS (Read-only file system)
08-23 12:28:02.997  1108  3626 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-23 12:28:02.997  1108  3626 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-23 12:28:02.997  1108  3626 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-23 12:28:02.997  1108  3626 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-23 12:28:02.997  1108  3626 W System.err: 	at com.htc.upm.HtcSystemUPPreference.writeProperty(HtcSystemUPPreference.java:119)
08-23 12:28:02.997  1108  3626 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setProperty(HtcSystemUPPreference.java:86)
08-23 12:28:02.997  1108  3626 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setLong(HtcSystemUPPreference.java:60)
08-23 12:28:02.997  1108  3626 W System.err: 	at com.htc.upm.HtcSystemUPHandler.addErrorCount(HtcSystemUPHandler.java:294)
08-23 12:28:02.997  1108  3626 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessageInternal(HtcSystemUPHandler.java:73)
08-23 12:28:02.997  1108  3626 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessage(HtcSystemUPHandler.java:46)
08-23 12:28:02.997  1108  3626 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 12:28:02.997  1108  3626 W System.err: 	at android.os.Looper.loop(Looper.java:155)
08-23 12:28:02.997  1108  3626 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-23 12:28:02.997  1108  3626 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-23 12:28:02.997  1108  3626 W System.err: 	at libcore.io.Posix.open(Native Method)
08-23 12:28:02.997  1108  3626 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-23 12:28:02.997  1108  3626 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-23 12:28:02.997  1108  3626 W System.err: 	... 12 more
08-23 12:28:03.007  9118  9463 I DeviceManagement: WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.PackageUpdateWorkflow@180cd73f] args=[Bundle[mParcelledData.dataSize=112]]
08-23 12:28:03.007  9118  9463 I DeviceManagement: PackageUpdateWorkflow: ==================================================
08-23 12:28:03.007  9118  9463 I DeviceManagement: PackageUpdateWorkflow: Package update: package=com.test.thalitest, operation=REMOVE
08-23 12:28:03.007  9118  9463 I DeviceManagement: PackageUpdateWorkflow: ==================================================
08-23 12:28:03.007  9118  9463 I DeviceManagement: ModelRegistry: Loading model meta data from resources...
08-23 12:28:03.007  1108  3252 I ActivityManager: Start proc 9465:com.android.documentsui/u0a90 for broadcast com.android.documentsui/.PackageReceiver
08-23 12:28:03.017  9465  9465 W HTCLOG  : use specified tag [FDManager], func [0].
08-23 12:28:03.017  9465  9465 W HTCLOG  : mask=0x18
08-23 12:28:03.027  9118  9463 I DeviceManagement: BackgroundController: *** Processing package remove for appID=com.test.thalitest
08-23 12:28:03.037  9118  9486 I DeviceManagement: SessionStateController: Checking invariants...
08-23 12:28:03.037  1108  3089 I ActivityManager: Recipient 9404
08-23 12:28:03.037  1108  3089 I ActivityManager: Process com.htc.launcher (pid 9404) has died
,08-23 12:28:03.037  1108  3089 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.htc.launcher/.Launcher} from uid 0 pid 0 on display 0
08-23 12:28:03.037  1108  3089 V WindowManager: addAppToken: AppWindowToken{168aedf0 token=Token{3c22d633 ActivityRecord{25b1f9a2 u0 com.htc.launcher/.Launcher t453}}} to stack=0 task=453 at 0
08-23 12:28:03.057  1108  3089 I ActivityManager: Start proc 9487:com.htc.launcher/u0a56 for activity com.htc.launcher/.Launcher
08-23 12:28:03.057  1108  3673 I ActivityManager: Recipient 6577
08-23 12:28:03.057  1108  3081 D WifiService: Client connection lost with reason: 4
08-23 12:28:03.057  1108  3626 D HtcSystemUPManager: HtcSystemUPolicy [canLog (default)] category: launch, enable: true
08-23 12:28:03.057  1108  3673 I ActivityManager: Process com.google.android.googlequicksearchbox:search (pid 6577) has died
08-23 12:28:03.057  1108  3673 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService in 10588ms
08-23 12:28:03.057  1108  3673 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService in 20588ms
08-23 12:28:03.057  1108  4754 I ActivityManager: Recipient 9438
08-23 12:28:03.057  1108  4754 I ActivityManager: Process com.android.keychain (pid 9438) has died
08-23 12:28:03.057  1108  4754 W ActivityManager: Scheduling restart of crashed service com.android.keychain/.KeyChainService in 20585ms
08-23 12:28:03.067  9487  9487 W HTCLOG  : use specified tag [FDManager], func [0].
08-23 12:28:03.067  9487  9487 W HTCLOG  : mask=0x18
,08-23 12:28:03.097  9465  9465 W HTCLOG  : use specified tag [SQLiteConnection], func [0].
08-23 12:28:03.097  9465  9465 W HTCLOG  : mask=0x18
08-23 12:28:03.097  9465  9465 E SQLiteDatabase: Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.,
08-23 12:28:03.097  9465  9465 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-23 12:28:03.097  9465  9465 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-23 12:28:03.097  9465  9465 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-23 12:28:03.097  9465  9465 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-23 12:28:03.097  9465  9465 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-23 12:28:03.097  9465  9465 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-23 12:28:03.097  9465  9465 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-23 12:28:03.097  9465  9465 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-23 12:28:03.097  9465  9465 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-23 12:28:03.097  9465  9465 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-23 12:28:03.097  9465  9465 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-23 12:28:03.097  9465  9465 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-23 12:28:03.097  9465  9465 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-23 12:28:03.097  9465  9465 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-23 12:28:03.097  9465  9465 E SQLiteDatabase: 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
08-23 12:28:03.097  9465  9465 E SQLiteDatabase: 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
08-23 12:28:03.097  9465  9465 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.call(ContentProvider.java:380)
08-23 12:28:03.097  9465  9465 E SQLiteDatabase: 	at android.content.ContentResolver.call(ContentResolver.java:1437)
08-23 12:28:03.097  9465  9465 E SQLiteDatabase: 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
08-23 12:28:03.097  9465  9465 E SQLiteDatabase: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2719)
08-23 12:28:03.097  9465  9465 E SQLiteDatabase: 	at android.app.ActivityThread.access$1700(ActivityThread.java:151)
08-23 12:28:03.097  9465  9465 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1467)
08-23 12:28:03.097  9465  9465 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 12:28:03.097  9465  9465 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:155)
08-23 12:28:03.097  9465  9465 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
08-23 12:28:03.097  9465  9465 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 12:28:03.097  9465  9465 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-23 12:28:03.097  9465  9465 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
08-23 12:28:03.097  9465  9465 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
,08-23 12:28:03.097  9465  9465 E AndroidRuntime: FATAL EXCEPTION: main
08-23 12:28:03.097  9465  9465 E AndroidRuntime: Process: com.android.documentsui, PID: 9465
08-23 12:28:03.097  9465  9465 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-23 12:28:03.097  9465  9465 E AndroidRuntime: 	,at android.app.ActivityThread.handleReceiver(ActivityThread.java:2733)
08-23 12:28:03.097  9465  9465 E AndroidRuntime: 	at android.app.ActivityThread.access$1700(ActivityThread.java:151)
,08-23 12:28:03.097  9465  9465 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1467)
08-23 12:28:03.097  9465  9465 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 12:28:03.097  9465  9465 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:155)
08-23 12:28:03.097  9465  9465 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
08-23 12:28:03.097  9465  9465 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 12:28:03.097  9465  9465 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-23 12:28:03.097  9465  9465 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
08-23 12:28:03.097  9465  9465 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
08-23 12:28:03.097  9465  9465 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-23 12:28:03.097  9465  9465 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-23 12:28:03.097  9465  9465 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-23 12:28:03.097  9465  9465 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-23 12:28:03.097  9465  9465 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-23 12:28:03.097  9465  9465 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-23 12:28:03.097  9465  9465 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-23 12:28:03.097  9465  9465 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-23 12:28:03.097  9465  9465 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-23 12:28:03.097  9465  9465 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-23 12:28:03.097  9465  9465 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-23 12:28:03.097  9465  9465 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-23 12:28:03.097  9465  9465 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-23 12:28:03.097  9465  9465 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-23 12:28:03.097  9465  9465 E AndroidRuntime: 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
08-23 12:28:03.097  9465  9465 E AndroidRuntime: 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
08-23 12:28:03.097  9465  9465 E AndroidRuntime: 	at android.content.ContentProvider$Transport.call(ContentProvider.java:380)
08-23 12:28:03.097  9465  9465 E AndroidRuntime: 	at android.content.ContentResolver.call(ContentResolver.java:1437)
08-23 12:28:03.097  9465  9465 E AndroidRuntime: 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
08-23 12:28:03.097  9465  9465 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2719)
08-23 12:28:03.097  9465  9465 E AndroidRuntime: 	... 9 more
08-23 12:28:03.097  1108  3089 D ErrorReport: HtcErrorReportManager Begin---add error logs to dropbox
08-23 12:28:03.097  1108  3089 E ActivityManager: App crashed! Process: com.android.documentsui
08-23 12:28:03.107  1108  1128 D ErrorReport: HtcErrorReportManager Begin---add error logs to dropbox
08-23 12:28:03.097  1108  3089 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
08-23 12:28:03.107  1108  9509 E E,rrorReport: HtcErrorReportManager.Error in dumping error information
08-23 12:28:03.107  1108  9509 E ErrorReport: java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1471948083117.dbox_tmp: open failed: EROFS (Read-only file system)
08-23 12:28:03.107  1108  9509 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-23 12:28:03.107  1108  9509 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-23 12:28:03.107  1108  9509 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-23 12:28:03.107  1108  9509 E ErrorReport: 	at com.android.server.am.HtcErrorReportManager$1.run(HtcErrorReportManager.java:458)
08-23 12:28:03.107  1108  9509 E ErrorReport: 	at java.lang.Thread.run(Thread.java:818)
08-23 12:28:03.107  1108  9509 E ErrorReport: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-23 12:28:03.107  1108  9509 E ErrorReport: 	at libcore.io.Posix.open(Native Method)
08-23 12:28:03.107  1108  9509 E ErrorReport: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-23 12:28:03.107  1108  9509 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-23 12:28:03.107  1108  9509 E ErrorReport: 	... 4 more
08-23 12:28:03.097  1108  3089 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-23 12:28:03.117  1108  3557 I ActivityManager: Start proc 9510:com.android.externalstorage/u0a15 for content provider com.android.externalstorage/.ExternalStorageProvider
08-23 12:28:03.097  1108  3089 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-23 12:28:03.127  1108  9518 E ErrorReport: HtcErrorReportManager.Error in dumping error information
08-23 12:28:03.127  1108  9518 E ErrorReport: java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1471948083137.dbox_tmp: open failed: EROFS (Read-only file system)
08-23 12:28:03.127  1108  9518 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-23 12:28:03.127  1108  9518 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-23 12:28:03.127  1108  9518 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-23 12:28:03.127  1108  9518 E ErrorReport: 	at com.android.server.am.HtcErrorReportManager$1.run(HtcErrorReportManager.java:458)
08-23 12:28:03.127  1108  9518 E ErrorReport: 	at java.lang.Thread.run(Thread.java:818)
08-23 12:28:03.127  1108  9518 E ErrorReport: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-23 12:28:03.127  1108  9518 E ErrorReport: 	at libcore.io.Posix.open(Native Method)
08-23 12:28:03.127  1108  9518 E ErrorReport: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-23 12:28:03.127  1108  9518 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-23 12:28:03.127  1108  9518 E ErrorReport: 	... 4 more
08-23 12:28:03.097  1108  3089 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-23 12:28:03.097  1108  3089 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-23 12:28:03.097  1108  3089 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
08-23 12:28:03.097  1108  3089 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
08-23 12:28:03.097  1108  3089 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getSecretKey(ErrorReportPreference.java:61)
08-23 12:28:03.097  1108  3089 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:302)
08-23 12:28:03.097  1108  3089 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
08-23 12:28:03.097  1108  3089 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
08-23 12:28:03.097  1108  3089 W System.err: 	at com.android.server.am.Activ,ityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
08-23 12:28:03.097  1108  3089 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
08-23 12:28:03.097  1108  3089 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
08-23 12:28:03.097  1108  3089 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
08-23 12:28:03.097  1108  3089 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
08-23 12:28:03.097  1108  3089 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-23 12:28:03.097  1108  3089 W System.err: 	at libcore.io.Posix.open(Native Method)
08-23 12:28:03.097  1108  3089 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-23 12:28:03.097  1108  3089 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-23 12:28:03.097  1108  3089 W System.err: 	... 14 more
08-23 12:28:03.097  5640  5773 E SQLiteLog: (3850) statement aborts at 16: [DELETE FROM downloads WHERE (uid=10142)] disk I/O error
08-23 12:28:03.097  5640  5773 W HTCLOG  : use specified tag [SQLiteDBG], func [0].
08-23 12:28:03.097  5640  5773 W HTCLOG  : mask=0x18
08-23 12:28:03.097  5640  5773 E SQLiteDBG: func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/user/0/com.android.providers.downloads/databases/downloads.db, handle: 0x55709ff160
08-23 12:28:03.097  1108  3089 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
08-23 12:28:03.097  1108  3089 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-23 12:28:03.097  1108  3089 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-23 12:28:03.097  1108  3089 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-23 12:28:03.097  1108  3089 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-23 12:28:03.097  1108  3089 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
08-23 12:28:03.097  1108  3089 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
08-23 12:28:03.097  1108  3089 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getIV(ErrorReportPreference.java:85)
08-23 12:28:03.097  1108  3089 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:303)
08-23 12:28:03.097  1108  3089 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
08-23 12:28:03.097  1108  3089 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
08-23 12:28:03.097  1108  3089 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
08-23 12:28:03.097  1108  3089 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
08-23 12:28:03.097  1108  3089 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
08-23 12:28:03.097  1108  3089 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
08-23 12:28:03.097  1108  3089 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
08-23 12:28:03.097  1108  3089 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-23 12:28:03.097  1108  3089 W System.err: 	at libcore.io.Posix.open(Native Method)
08-23 12:28:03.097  1108  3089 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-23 12:28:03.097  1108  3089 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-23 12:28:03.097  1108  3089 W System.err: 	... 14 more
08-23 12:28:03.097  5640  5773 E AndroidRuntime: FATAL EXCEPTION: DownloadReceiver
08-23 12:28:03.097  5640  5773 E AndroidRuntime: Process: android.process.media, PID: 5640
08-23 12:28:03.097  5640  5773 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-23 12:28:03.097  5640  5773 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-23 12:28:03.097  5640  5773 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:762)
08-23 12:28:03.097  5640  5773 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-23 12:28:03.097  5640  5773 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-23 12:28:03.097  5640  5773 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1598)
08-23 12:28:03.097  5640  5773 E AndroidRuntime: 	at com.android.providers.downloads.DownloadProvider.delete(DownloadProvider.java:1484)
08-23 12:28:03.097  5640  5773 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:322)
08-23 12:28:03.097  5640  5773 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1364)
08-23 12:28:03.097  5640  5773 E AndroidRuntime: 	at com.android.providers.downloads.DownloadReceiver.handleUidRemoved(DownloadReceiver.java:138)
08-23 12:28:03.097  5640  5773 E AndroidRuntime: 	at com.android.providers.downloads.DownloadReceiver.access$000(DownloadReceiver.java:47)
08-23 12:28:03.097  5640  5773 E AndroidRuntime: 	at com.android.providers.downloads.DownloadReceiver$1.run(DownloadReceiver.java:100)
08-23 12:28:03.097  5640  5773 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-23 12:28:03.097  5640  5773 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-23 12:28:03.097  5640  5773 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:155)
08-23 12:28:03.097  5640  5773 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-23 12:28:03.107  1108  1128 E ActivityManager: App crashed! Process: android.process.media
08-23 12:28:03.107  1108  1128 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
08-23 12:28:03.107  1108  3626 W System.err: java.io.FileNotFoundException: /data/system/systemup_pref.xml: open failed: EROFS (Read-only file system)
08-23 12:28:03.107  1108  1128 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-23 12:28:03.107  1108  1128 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-23 12:28:03.107  1108  1128 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-23 12:28:03.107  1108  1128 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-23 12:28:03.107  1108  1128 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
08-23 12:28:03.107  1108  1128 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
08-23 12:28:03.107  1108  1128 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getSecretKey(ErrorReportPreference.java:61)
08-23 12:28:03.107  1108  1128 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:302)
08-23 12:28:03.107  1108  1128 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
08-23 12:28:03.107  1108  1128 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
08-23 12:28:03.107  1108  1128 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
08-23 12:28:03.107  1108  1128 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
08-23 12:28:03.107  1108  1128 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
08-23 12:28:03.107  1108  1128 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
08-23 12:28:03.107  1108  1128 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
08-23 12:28:03.107  1108  1128 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-23 12:28:03.107  1108  1128 W System.err: 	at libcore.io.Posix.open(Native Method)
08-23 12:28:03.107  1108  1128 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-23 12:28:03.107  1108  1128 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-23 12:28:03.107  1108  1128 W System.err: 	... 14 more
08-23 12:28:03.107  1108  3626 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-23 12:28:03.107  1108  3626 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-23 12:28:03.107  1108  3626 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-23 12:28:03.107  1108  3626 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-23 12:28:03.107  1108  3626 W System.err: 	at com.htc.upm.HtcSystemUPPreference.writeProperty(HtcSystemUPPreference.java:119)
08-23 12:28:03.107  1108  3626 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setProperty(HtcSystemUPPreference.java:86)
08-23 12:28:03.107  1108  3626 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setLong(HtcSystemUPPreference.java:60)
08-23 12:28:03.107  1108  3626 W System.err: 	at com.htc.upm.HtcSystemUPHandler.addErrorCount(HtcSystemUPHandler.java:294)
08-23 12:28:03.107  1108  3626 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessageInternal(HtcSystemUPHandler.java:73)
08-23 12:28:03.107  1108  3626 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessage(HtcSystemUPHandler.java:46)
08-23 12:28:03.107  1108  3626 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 12:28:03.137  1108  1150 I ActivityManager: Start proc 9525:com.htc.htcpowermanager:remote/1000 for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver
08-23 12:28:03.107  1108  3626 W System.err: 	at android.os.Looper.loop(Looper.java:155)
08-23 12:28:03.107  1108  3626 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-23 12:28:03.107  1108  3626 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-23 12:28:03.107  1108  1128 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
08-23 12:28:03.107  1108  3626 W System.err: 	at libcore.io.Posix.open(Native Method)
08-23 12:28:03.107  1108  3626 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-23 12:28:03.107  1108  3626 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-23 12:28:03.107  1108  3626 W System.err: 	... 12 more
08-23 12:28:03.107  1108  1128 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-23 12:28:03.107  1108  1128 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-23 12:28:03.107  1108  1128 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-23 12:28:03.107  1108  1128 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-23 12:28:03.107  1108  1128 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
08-23 12:28:03.107  1108  1128 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
08-23 12:28:03.107  1108  1128 W System.err: 	at com.,htc.server.report.error.ErrorReportPreference.getIV(ErrorReportPreference.java:85)
08-23 12:28:03.107  1108  1128 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:303)
08-23 12:28:03.107  1108  1128 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
08-23 12:28:03.107  1108  1128 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
08-23 12:28:03.107  1108  1128 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
08-23 12:28:03.107  1108  1128 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
08-23 12:28:03.107  1108  1128 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
08-23 12:28:03.107  1108  1128 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
08-23 12:28:03.107  1108  1128 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
08-23 12:28:03.107  1108  1128 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-23 12:28:03.107  9465  9465 D Process : killProcess, pid=9465
08-23 12:28:03.107  9465  9465 D Process : com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
08-23 12:28:03.107  9465  9465 W HTCLOG  : use specified tag [Process], func [0].
08-23 12:28:03.107  9465  9465 W HTCLOG  : mask=0x18
08-23 12:28:03.107  1108  1128 W System.err: 	at libcore.io.Posix.open(Native Method)
08-23 12:28:03.107  1108  1128 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-23 12:28:03.107  1108  1128 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-23 12:28:03.107  1108  1128 W System.err: 	... 14 more
08-23 12:28:03.127  9487  9487 I MultiDex: VM with version 2.1.0 has multidex support
08-23 12:28:03.127  9487  9487 I MultiDex: install
08-23 12:28:03.127  9487  9487 I MultiDex: VM has multidex support, MultiDex support library is disabled.
08-23 12:28:03.127  1108  3626 W System.err: java.io.FileNotFoundException: /data/system/systemup_pref.xml: open failed: EROFS (Read-only file system)
08-23 12:28:03.127  1108  3626 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-23 12:28:03.127  1108  3626 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-23 12:28:03.127  1108  3626 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-23 12:28:03.127  1108  3626 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-23 12:28:03.127  1108  3626 W System.err: 	at com.htc.upm.HtcSystemUPPreference.writeProperty(HtcSystemUPPreference.java:119)
08-23 12:28:03.127  1108  3626 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setProperty(HtcSystemUPPreference.java:86)
08-23 12:28:03.127  1108  3626 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setLong(HtcSystemUPPreference.java:60)
08-23 12:28:03.127  1108  3626 W System.err: 	at com.htc.upm.HtcSystemUPHandler.addErrorCount(HtcSystemUPHandler.java:294)
08-23 12:28:03.127  1108  3626 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessageInternal(HtcSystemUPHandler.java:73)
08-23 12:28:03.127  1108  3626 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessage(HtcSystemUPHandler.java:46)
08-23 12:28:03.127  1108  3626 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 12:28:03.127  1108  3626 W System.err: 	at android.os.Looper.loop(Looper.java:155)
08-23 12:28:03.127  1108  3626 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-23 12:28:03.127  1108  3626 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-23 12:28:03.127  1108  3626 W System.err: 	at libcore.io.Posix.open(Native Method)
08-23 12:28:03.127  1108  3626 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-23 12:28:03.127  1108  3626 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-23 12:28:03.127  1108  3626 W System.err: 	... 12 more
08-23 12:28:03.137  9487  9487 D FaceDetectTask: sOmronFaceDetectTaskClass : null
08-23 12:28:03.137  9487  9487 D FaceDetectTask: checkIsOmronEnable start
08-23 12:28:03.147  9487  9487 D MorphoNativeMemoryAllocator: load libmorpho_memory_allocator.so
08-23 12:28:03.147  9510  9510 W HTCLOG  : use specified tag [FDManager], func [0].
08-23 12:28:03.147  9510  9510 W HTCLOG  : mask=0x18
08-23 12:28:03.147  9487  9487 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
08-23 12:28:03.147  9487  9487 D FaceDetectTask: IsOmronEnable : true
08-23 12:28:03.147  9487  9487 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
08-23 12:28:03.147  9487  9487 D FaceDetectTask: sOmronFaceDetectTaskClass : null
08-23 12:28:03.147  9487  9487 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
08-23 12:28:03.147  9487  9487 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
08-23 12:28:03.147  9487  9487 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
08-23 12:28:03.147  9487  9487 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
08-23 12:28:03.147  9487  9487 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
08-23 12:28:03.147  9487  9487 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
08-23 12:28:03.147  9487  9487 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
08-23 12:28:03.147  9487  9487 I HighlightSelectCacheHelper: [custom highlight] loadHighlightSelection()
08-23 12:28:03.147  9487  9487 W HTCLOG  : use specified tag [SQLiteConnection], func [0].
08-23 12:28:03.147  9487  9487 W HTCLOG  : mask=0x18
08-23 12:28:03.147  9487  9487 E SQLiteDatabase: Failed to open database '/data/user/0/com.htc.launcher/databases/highlight_selection.db'.
08-23 12:28:03.147  9487  9487 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-23 12:28:03.147  9487  9487 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-23 12:28:03.147  9487  9487 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-23 12:28:03.147  9487  9487 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-23 12:28:03.147  9487  9487 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-23 12:28:03.147  9487  9487 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-23 12:28:03.147  9487  9487 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-23 12:28:03.147  9487  9487 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-23 12:28:03.147  9487  9487 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-23 12:28:03.147  9487  9487 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-23 12:28:03.147  9487  9487 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-23 12:28:03.147  9487  9487 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-23 12:28:03.147  9487  9487 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-23 12:28:03.147  9487  9487 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-23 12:28:03.147  9487  9487 E SQLiteDatabase: 	at com.htc.launcher.feeds.HighlightSelectCacheHelper.loadHighlightSelection(HighlightSelectCacheHelper.java:319)
08-23 12:28:03.147  9487  9487 E SQLiteDatabase: 	at com.htc.launcher.feeds.HighlightSelectCacheHelper.onCreate(HighlightSelectCacheHelper.java:83)
08-23 12:28:03.147  9487  9487 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1712)
08-23 12:28:03.147  9487  9487 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1681)
08-23 12:28:03.147  9487  9487 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5429)
08-23 12:28:03.147  9487  9487 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5000)
08-23 12:28:03.147  9487  9487 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4940)
08-23 12:28:03.147  9487  9487 E SQLiteDatabase: 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
08-23 12:28:03.147  9487  9487 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1442)
08-23 12:28:03.147  9487  9487 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 12:28:03.147  9487  9487 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:155)
08-23 12:28:03.147  9487  9487 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
08-23 12:28:03.147  9487  9487 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 12:28:03.147  9487  9487 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-23 12:28:03.147  9487  9487 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
08-23 12:28:03.147  9487  9487 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
08-23 12:28:03.147  5640  5773 D Process : killProcess, pid=5640
08-23 12:28:03.157  1108  3252 I ActivityManager: Killing 8583:com.google.android.gm/u0a97 (adj 15): empty #17
08-23 12:28:03.147  5640  5773 D Process : com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
08-23 12:28:03.147  5640  5773 W HTCLOG  : use specified tag [Process], func [0].
08-23 12:28:03.147  5640  5773 W HTCLOG  : mask=0x18
08-23 12:28:03.157  9487  9487 W System.err: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-23 12:28:03.157  9487  9487 W System.err: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-23 12:28:03.157  9487  9487 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-23 12:28:03.157  9487  9487 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-23 12:28:03.157  9487  9487 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-23 12:28:03.157  9487  9487 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-23 12:28:03.157  9487  9487 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-23 12:28:03.157  9487  9487 W System.err: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-23 12:28:03.157  9487  9487 W System.err: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-23 12:28:03.157  9487  9487 W System.err: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-23 12:28:03.157  9487  9487 W System.err: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-23 12:28:03.157  9487  9487 W System.err: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-23 12:28:03.157  9487  9487 W System.err: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-23 12:28:03.157  9487  9487 W System.err: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-23 12:28:03.157  9487  9487 W System.err: 	at com.htc.launcher.feeds.HighlightSelectCacheHelper.loadHighlightSelection(HighlightSelectCacheHelper.java:319)
08-23 12:28:03.157  9487  9487 W System.err: 	at com.htc.launcher.feeds.HighlightSelectCacheHelper.onCreate(HighlightSelectCacheHelper.java:83)
08-23 12:28:03.157  9487  9487 W System.err: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1712)
08-23 12:28:03.157  9487  9487 W System.err: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1681)
08-23 12:28:03.157  9487  9487 W System.err: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5429)
08-23 12:28:03.157  9487  9487 W System.err: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5000)
08-23 12:28:03.157  9487  9487 W System.err: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4940)
08-23 12:28:03.157  9487  9487 W System.err: 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
08-23 12:28:03.157  9487  9487 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1442)
08-23 12:28:03.157  9487  9487 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 12:28:03.157  9487  9487 W System.err: 	at android.os.Looper.loop(Looper.java:155)
08-23 12:28:03.157  9487  9487 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
08-23 12:28:03.157  9487  9487 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 12:28:03.157  9487  9487 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-23 12:28:03.157  9487  9487 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
08-23 12:28:03.157  9487  9487 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
08-23 12:28:03.157   492   492 E lowmemorykiller: Error writing /proc/5640/oom_score_adj; errno=22
08-23 12:28:03.157  1108  3252 D Process : killProcessQuiet, pid=8583
08-23 12:28:03.157  1108  3252 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19468 com.android.server.am.ActivityManagerService.attachApplicationLocked:6484 
08-23 12:28:03.167  9525  9525 W HTCLOG  : use specified tag [FDManager], func [0].
08-23 12:28:03.167  9525  9525 W HTCLOG  : mask=0x18
08-23 12:28:03.167  9487  9487 E SQLiteDatabase: Failed to open database '/data/user/0/com.htc.launcher/databases/externalapp.db'.
08-23 12:28:03.167  9487  9487 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-23 12:28:03.167  9487  9487 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-23 12:28:03.167  9487  9487 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-23 12:28:03.167  9487  9487 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-23 12:28:03.167  9487  9487 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-23 12:28:03.167  9487  9487 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-23 12:28:03.167  9487  9487 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-23 12:28:03.167  9487  9487 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-23 12:28:03.167  9487  9487 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-23 12:28:03.167  9487  9487 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-23 12:28:03.167  9487  9487 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-23 12:28:03.167  9487  9487 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-23 12:28:03.167  9487  9487 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-23 12:28:03.167  9487  9487 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-23 12:28:03.167  9487  9487 E SQLiteDatabase: 	at com.htc.launcher.ExternalAppStateProvider.reInitalizeExternalAppsStateMaxId(ExternalAppStateProvider.java:103)
08-23 12:28:03.167  9487  9487 E SQLiteDatabase: 	at com.htc.launcher.ExternalAppStateProvider.onCreate(ExternalAppStateProvider.java:25)
08-23 12:28:03.167  9487  9487 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1712)
08-23 12:28:03.167  9487  9487 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1681)
08-23 12:28:03.167  9487  9487 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5429)
08-23 12:28:03.167  9487  9487 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5000)
08-23 12:28:03.167  9487  9487 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4940)
08-23 12:28:03.167  9487  9487 E SQLiteDatabase: 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
08-23 12:28:03.167  9487  9487 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1442)
08-23 12:28:03.167  9487  9487 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 12:28:03.167  9487  9487 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:155)
08-23 12:28:03.167  9487  9487 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
08-23 12:28:03.167  9487  9487 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 12:28:03.167  9487  9487 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-23 12:28:03.167  9487  9487 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
08-23 12:28:03.167  9487  9487 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
08-23 12:28:03.167  9487  9487 E AndroidRuntime: FATAL EXCEPTION: main
08-23 12:28:03.167  9487  9487 E AndroidRuntime: Process: com.htc.launcher, PID: 9487
08-23 12:28:03.167  9487  9487 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.htc.launcher.ExternalAppStateProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-23 12:28:03.167  9487  9487 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5432)
08-23 12:28:03.167  9487  9487 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5000)
08-23 12:28:03.167  9487  9487 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4940)
08-23 12:28:03.167  9487  9487 E AndroidRuntime: 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
08-23 12:28:03.167  9487  9487 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1442)
08-23 12:28:03.167  9487  9487 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 12:28:03.167  9487  9487 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:155)
08-23 12:28:03.167  9487  9487 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
08-23 12:28:03.167  9487  9487 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 12:28:03.167  9487  9487 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-23 12:28:03.167  9487  9487 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
08-23 12:28:03.167  9487  9487 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
08-23 12:28:03.167  9487  9487 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-23 12:28:03.167  9487  9487 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-23 12:28:03.167  9487  9487 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-23 12:28:03.167  9487  9487 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-23 12:28:03.167  9487  9487 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-23 12:28:03.167  9487  9487 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-23 12:28:03.167  9487  9487 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-23 12:28:03.167  9487  9487 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-23 12:28:03.167  9487  9487 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-23 12:28:03.167  9487  9487 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-23 12:28:03.167  9487  9487 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-23 12:28:03.167  9487  9487 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-23 12:28:03.167  9487  9487 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-23 12:28:03.167  9487  9487 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-23 12:28:03.167  9487  9487 E AndroidRuntime: 	at com.htc.launcher.ExternalAppStateProvider.reInitalizeExternalAppsStateMaxId(ExternalAppStateProvider.java:103)
08-23 12:28:03.167  9487  9487 E AndroidRuntime: 	at com.htc.launcher.ExternalAppStateProvider.onCreate(ExternalAppStateProvider.java:25)
08-23 12:28:03.167  9487  9487 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1712)
08-23 12:28:03.167  9487  9487 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1681)
08-23 12:28:03.167  9487  9487 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5429)
08-23 12:28:03.167  9487  9487 E AndroidRuntime: 	... 11 more
08-23 12:28:03.187  9118  9486 W HTCLOG  : use specified tag [SQLiteConnection], func [0].
08-23 12:28:03.187  9118  9486 W HTCLOG  : mask=0x18
08-23 12:28:03.187  9118  9486 E SQLiteDatabase: Failed to open database '/data/data/com.htc.cs.dm/databases/provisioning.db'.
08-23 12:28:03.187  9118  9486 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-23 12:28:03.187  9118  9486 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-23 12:28:03.187  9118  9486 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-23 12:28:03.187  9118  9486 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-23 12:28:03.187  9118  9486 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-23 12:28:03.187  9118  9486 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-23 12:28:03.187  9118  9486 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-23 12:28:03.187  9118  9486 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-23 12:28:03.187  9118  9486 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-23 12:28:03.187  9118  9486 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-23 12:28:03.187  9118  9486 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-23 12:28:03.187  9118  9486 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-23 12:28:03.187  9118  9486 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-23 12:28:03.187  9118  9486 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-23 12:28:03.187  9118  9486 E SQLiteDatabase: 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
08-23 12:28:03.187  9118  9486 E SQLiteDatabase: 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.query(EnabledAppProviderDAO.java:108)
08-23 12:28:03.187  9118  9486 E SQLiteDatabase: 	at com.htc.cs.dm.provider.ProvProvider.query(ProvProvider.java:123)
08-23 12:28:03.187  9118  9486 E SQLiteDatabase: 	at android.content.ContentProvider.query(ContentProvider.java:976)
08-23 12:28:03.187  9118  9486 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.query(ContentProvider.java:221)
08-23 12:28:03.187  9118  9486 E SQLiteDatabase: 	at android.content.ContentProviderClient.query(ContentProviderClient.java:156)
08-23 12:28:03.187  9118  9486 E SQLiteDatabase: 	at android.content.ContentProviderClient.query(ContentProviderClient.java:120)
08-23 12:28:03.187  9118  9486 E SQLiteDatabase: 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledAppUsingCP(EnabledAppDAO.java:137)
08-23 12:28:03.187  9118  9486 E SQLiteDatabase: 	at com.htc.cs.dm.content.EnabledAppDAO.access$100(EnabledAppDAO.java:28)
08-23 12:28:03.187  9118  9486 E SQLiteDatabase: 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:125)
08-23 12:28:03.187  9118  9486 E SQLiteDatabase: 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:121)
08-23 12:28:03.187  9118  9486 E SQLiteDatabase: 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
08-23 12:28:03.187  9118  9486 E SQLiteDatabase: 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledApp(EnabledAppDAO.java:121)
08-23 12:28:03.187  9118  9486 E SQLiteDatabase: 	at com.htc.cs.dm.controller.ConfigManagerController.checkPreconditions(ConfigManagerController.java:276)
08-23 12:28:03.187  9118  9486 E SQLiteDatabase: 	at com.htc.cs.dm.controller.ConfigManagerController.getConfigBundle(ConfigManagerController.java:147)
08-23 12:28:03.187  9118  9486 E SQLiteDatabase: 	at com.htc.cs.dm.config.model.CoreConfigModel.fetchConfigFromDM(CoreConfigModel.java:393)
08-23 12:28:03.187  9118  9486 E SQLiteDatabase: 	at com.htc.cs.dm.config.model.CoreConfigModel.fetchConfigAndUpdate(CoreConfigModel.java:351)
08-23 12:28:03.187  9118  9486 E SQLiteDatabase: 	at com.htc.cs.dm.config.model.CoreConfigModel.onFetch(CoreConfigModel.java:206)
08-23 12:28:03.187  9118  9486 E SQLiteDatabase: 	at com.htc.cs.util.model.BaseModel.handleFetch(BaseModel.java:197)
08-23 12:28:03.187  9118  9486 E SQLiteDatabase: 	at com.htc.cs.util.model.BaseModelCollection.onFetch(BaseModelCollection.java:111)
08-23 12:28:03.187  9118  9486 E SQLiteDatabase: 	at com.htc.cs.dm.config.model.DataBindingConfigModel.onFetch(DataBindingConfigModel.java:280)
08-23 12:28:03.187  9118  9486 E SQLiteDatabase: 	at com.htc.cs.util.model.BaseModel.handleFetch(BaseModel.java:197)
08-23 12:28:03.187  9118  9486 E SQLiteDatabase: 	at com.htc.cs.util.model.BaseModel$1.doInBackground(BaseModel.java:176)
08-23 12:28:03.187  9118  9486 E SQLiteDatabase: 	at com.htc.cs.util.model.ModelAsyncTask$1.call(ModelAsyncTask.java:101)
08-23 12:28:03.187  9118  9486 E SQLiteDatabase: 	at com.htc.cs.util.model.ModelAsyncTask$1.call(ModelAsyncTask.java:90)
08-23 12:28:03.187  9118  9486 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-23 12:28:03.187  9118  9486 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
08-23 12:28:03.187  9118  9486 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
08-23 12:28:03.187  9118  9486 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,08-23 12:28:03.217  1108  3673 I ActivityManager: Recipient 5640
08-23 12:28:03.217  1108  3089 I ActivityManager: Recipient 9465
08-23 12:28:03.217  1108  3498 I ActivityManager: Recipient 8583
,08-23 12:28:03.277  1108  4749 E ActivityManager: App crashed! Process: com.htc.launcher
08-23 12:28:03.277  9118  9486 I DeviceManagement: ModelAsyncTask: Caught exception running async model handler: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-23 12:28:03.277  1108  4749 D ErrorReport: HtcErrorReportManager Begin---add error logs to dropbox
08-23 12:28:03.277  9118  9463 I DeviceManagement: DMConfigController: Ignoring exception fetching DM Core config: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-23 12:28:03.277  1108  3089 I ActivityManager: Process com.android.documentsui (pid 9465) has died
08-23 12:28:03.277  9118  9463 I DeviceManagement: BackgroundController: Ensure removal of obsolete app cache entries: appID=com.test.thalitest
08-23 12:28:03.277  1108  4749 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
08-23 12:28:03.277  1108  4749 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-23 12:28:03.277  1108  4749 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-23 12:28:03.277  1108  4749 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-23 12:28:03.277  1108  4749 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-23 12:28:03.277  1108  4749 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
08-23 12:28:03.277  1108  4749 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
08-23 12:28:03.277  1108  4749 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getSecretKey(ErrorReportPreference.java:61)
08-23 12:28:03.277  1108  4749 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:302)
08-23 12:28:03.277  1108  4749 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
08-23 12:28:03.277  1108  4749 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
08-23 12:28:03.277  1108  4749 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
08-23 12:28:03.277  1108  4749 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
08-23 12:28:03.277  1108  4749 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
08-23 12:28:03.277  1108  4749 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
08-23 12:28:03.277  1108  4749 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
08-23 12:28:03.277  1108  4749 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-23 12:28:03.277  1108  4749 W System.err: 	at libcore.io.Posix.open(Native Method)
08-23 12:28:03.277  1108  4749 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-23 12:28:03.277  1108  4749 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-23 12:28:03.277  1108  4749 W System.err: 	... 14 more
08-23 12:28:03.277  1108  4749 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
08-23 12:28:03.277  1108  4749 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-23 12:28:03.277  1108  4749 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-23 12:28:03.277  1108  4749 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-23 12:28:03.277  1108  4749 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116),
08-23 12:28:03.277  1108  4749 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
08-23 12:28:03.277  1108  4749 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
08-23 12:28:03.277  1108  4749 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getIV(ErrorReportPreference.java:85)
08-23 12:28:03.277  1108  4749 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:303)
08-23 12:28:03.277  1108  4749 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
08-23 12:28:03.277  1108  4749 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
08-23 12:28:03.277  1108  4749 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
08-23 12:28:03.277  1108  4749 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
08-23 12:28:03.287  1108  3673 I ActivityManager: Process android.process.media (pid 5640) has died
08-23 12:28:03.277  1108  4749 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
08-23 12:28:03.277  1108  4749 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
08-23 12:28:03.277  1108  4749 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
08-23 12:28:03.277  1108  4749 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-23 12:28:03.277  1108  4749 W System.err: 	at libcore.io.Posix.open(Native Method)
08-23 12:28:03.277  1108  4749 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-23 12:28:03.277  1108  4749 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-23 12:28:03.277  1108  4749 W System.err: 	... 14 more
08-23 12:28:03.297  1108  3673 W ActivityManager: Scheduling restart of crashed service com.android.providers.media/.MtpService in 20355ms
08-23 12:28:03.307  3337  3366 D DotMatrix: [NotificationService] onNotificationRemoved, pkgName: com.android.providers.media, id: 1, tag: null, isClearable: false, isForDotMatrix: false
08-23 12:28:03.297  1108  4749 W ActivityManager:   Force finishing activity 1 com.htc.launcher/.Launcher
08-23 12:28:03.327  3226  3226 I NotificationStackScrollLayout: setBlockTouchEnabled:false
08-23 12:28:03.307  1108  9562 E ErrorReport: HtcErrorReportManager.Error in dumping error information
08-23 12:28:03.307  1108  9562 E ErrorReport: java.io.FileNotFoundException: /data/misc/HTC_HOME_RESTART@1471948083315.dbox_tmp: open failed: EROFS (Read-only file system)
08-23 12:28:03.307  1108  9562 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-23 12:28:03.307  1108  9562 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-23 12:28:03.307  1108  9562 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-23 12:28:03.307  1108  9562 E ErrorReport: 	at com.android.server.am.HtcErrorReportManager$1.run(HtcErrorReportManager.java:458)
08-23 12:28:03.307  1108  9562 E ErrorReport: 	at java.lang.Thread.run(Thread.java:818)
,08-23 12:28:03.307  1108  9562 E ErrorReport: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-23 12:28:03.307  1108  9562 E ErrorReport: 	at libcore.io.Posix.open(Native Method)
08-23 12:28:03.307  1108  9562 E ErrorReport: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-23 12:28:03.307  1108  9562 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-23 12:28:03.307  1108  9562 E ErrorReport: 	... 4 more
08-23 12:28:03.327  9487  9487 D Process : killProcess, pid=9487
08-23 12:28:03.327  9487  9487 D Process : com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
,08-23 12:28:03.327  9487  9487 W HTCLOG  : use specified tag [Process], func [0].
08-23 12:28:03.327  9487  9487 W HTCLOG  : mask=0x18
08-23 12:28:03.337  9118  9463 E SQLiteDatabase: Failed to open database '/data/data/com.htc.cs.dm/databases/provisioning.db'.
08-23 12:28:03.337  9118  9463 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-23 12:28:03.337  9118  9463 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-23 12:28:03.337  9118  9463 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-23 12:28:03.337  9118  9463 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-23 12:28:03.337  9118  9463 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-23 12:28:03.337  9118  9463 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-23 12:28:03.337  9118  9463 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-23 12:28:03.337  9118  9463 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-23 12:28:03.337  9118  9463 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-23 12:28:03.337  9118  9463 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-23 12:28:03.337  9118  9463 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-23 12:28:03.337  9118  9463 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-23 12:28:03.337  9118  9463 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-23 12:28:03.337  9118  9463 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-23 12:28:03.337  9118  9463 E SQLiteDatabase: 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
08-23 12:28:03.337  9118  9463 E SQLiteDatabase: 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.delete(EnabledAppProviderDAO.java:265)
08-23 12:28:03.337  9118  9463 E SQLiteDatabase: 	at com.htc.cs.dm.provider.ProvProvider.delete(ProvProvider.java:335)
08-23 12:28:03.337  9118  9463 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:322)
,08-23 12:28:03.337  9118  9463 E SQLiteDatabase: 	at android.content.ContentProviderClient.delete(ContentProviderClient.java:263)
08-23 12:28:03.337  9118  9463 E SQLiteDatabase: 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:289)
08-23 12:28:03.337  9118  9463 E SQLiteDatabase: 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:283)
08-23 12:28:03.337  9118  9463 E SQLiteDatabase: 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
08-23 12:28:03.337  9118  9463 E SQLiteDatabase: 	at com.htc.cs.dm.content.EnabledAppDAO.delete(EnabledAppDAO.java:283)
08-23 12:28:03.337  9118  9463 E SQLiteDatabase: 	at com.htc.cs.dm.controller.EnabledAppController.remove(EnabledAppController.java:263)
08-23 12:28:03.337  9118  9463 E SQLiteDatabase: 	at com.htc.cs.dm.controller.BackgroundController.removeObsoleteAppID(BackgroundController.java:684)
08-23 12:28:03.337  9118  9463 E SQLiteDatabase: 	at com.htc.cs.dm.controller.BackgroundController.updateAfterPackageRemove(BackgroundController.java:657)
08-23 12:28:03.337  9118  9463 E SQLiteDatabase: 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.onUpdate(PackageUpdateWorkflow.java:105)
08-23 12:28:03.337  9118  9463 E SQLiteDatabase: 	,at com.htc.cs.dm.workflow.PackageUpdateWorkflow.call(PackageUpdateWorkflow.java:62)
08-23 12:28:03.337  9118  9463 E SQLiteDatabase: 	at com.htc.cs.util.workflow.WorkflowService.executeWorkflow(WorkflowService.java:321)
08-23 12:28:03.337  9118  9463 E SQLiteDatabase: 	at com.htc.cs.util.workflow.WorkflowService.onHandleIntent(WorkflowService.java:295)
08-23 12:28:03.337  9118  9463 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-23 12:28:03.337  9118  9463 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 12:28:03.337  9118  9463 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:155)
08-23 12:28:03.337  9118  9463 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-23 12:28:03.337  9118  9463 W DeviceManagement: WorkflowService: Uncaught throwable executing workflow [com.htc.cs.dm.workflow.PackageUpdateWorkflow@180cd73f]android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-23 12:28:03.337  9118  9463 W DeviceManagement: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-23 12:28:03.337  9118  9463 W DeviceManagement: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-23 12:28:03.337  9118  9463 W DeviceManagement: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-23 12:28:03.337  9118  9463 W DeviceManagement: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-23 12:28:03.337  9118  9463 W DeviceManagement: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-23 12:28:03.337  9118  9463 W DeviceManagement: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-23 12:28:03.337  9118  9463 W DeviceManagement: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-23 12:28:03.337  9118  9463 W DeviceManagement: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-23 12:28:03.337  9118  9463 W DeviceManagement: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-23 12:28:03.337  9118  9463 W DeviceManagement: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-23 12:28:03.337  9118  9463 W DeviceManagement: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-23 12:28:03.337  9118  9463 W DeviceManagement: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-23 12:28:03.337  9118  9463 W DeviceManagement: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-23 12:28:03.337  9118  9463 W DeviceManagement: 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
08-23 12:28:03.337  9118  9463 W DeviceManagement: ,	at com.htc.cs.dm.provider.EnabledAppProviderDAO.delete(EnabledAppProviderDAO.java:265)
08-23 12:28:03.337  9118  9463 W DeviceManagement: 	at com.htc.cs.dm.provider.ProvProvider.delete(ProvProvider.java:335)
08-23 12:28:03.337  9118  9463 W DeviceManagement: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:322)
08-23 12:28:03.337  9118  9463 W DeviceManagement: 	at android.content.ContentProviderClient.delete(ContentProviderClient.java:263)
08-23 12:28:03.337  9118  9463 W DeviceManagement: 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:289)
08-23 12:28:03.337  9118  9463 W DeviceManagement: 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:283)
08-23 12:28:03.337  9118  9463 W DeviceManagement: 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
08-23 12:28:03.337  9118  9463 W DeviceManagement: 	at com.htc.cs.dm.content.EnabledAppDAO.delete(EnabledAppDAO.java:283)
08-23 12:28:03.337  9118  9463 W DeviceManagement: 	at com.htc.cs.dm.controller.EnabledAppController.remove(EnabledAppController.java:263)
08-23 12:28:03.337  9118  9463 W DeviceManagement: 	at com.htc.cs.dm.controller.BackgroundController.removeObsoleteAppID(BackgroundController.java:684)
08-23 12:28:03.337  9118  9463 W DeviceManagement: 	,at com.htc.cs.dm.controller.BackgroundController.updateAfterPackageRemove(BackgroundController.java:657)
08-23 12:28:03.337  9118  9463 W DeviceManagement: 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.onUpdate(PackageUpdateWorkflow.java:105)
08-23 12:28:03.337  9118  9463 W DeviceManagement: 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.call(PackageUpdateWorkflow.java:62)
08-23 12:28:03.337  9118  9463 W DeviceManagement: 	at com.htc.cs.util.workflow.WorkflowService.executeWorkflow(WorkflowService.java:321)
08-23 12:28:03.337  9118  9463 W DeviceManagement: 	at com.htc.cs.util.workflow.WorkflowService.onHandleIntent(WorkflowService.java:295)
08-23 12:28:03.337  9118  9463 W DeviceManagement: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-23 12:28:03.337  9118  9463 W DeviceManagement: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 12:28:03.337  9118  9463 W DeviceManagement: 	at android.os.Looper.loop(Looper.java:155)
08-23 12:28:03.337  9118  9463 W DeviceManagement: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-23 12:28:03.337  1108  3626 W System.err: java.io.FileNotFoundException: /data/system/systemup_pref.xml: open failed: EROFS (Read-only file system)
08-23 12:28:03.337  9118  9118 I DeviceManagement: WorkflowService: Stopping workflow service
08-23 12:28:03.337  1108  3626 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-23 12:28:03.337  1108  3626 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-23 12:28:03.337  1108  3626 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-23 12:28:03.337  1108  3626 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
,08-23 12:28:03.337  1108  3626 W System.err: 	at com.htc.upm.HtcSystemUPPreference.writeProperty(HtcSystemUPPreference.java:119)
08-23 12:28:03.337  1108  3626 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setProperty(HtcSystemUPPreference.java:86)
08-23 12:28:03.337  1108  3626 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setLong(HtcSystemUPPreference.java:60)
08-23 12:28:03.337  1108  3626 W System.err: 	at com.htc.upm.HtcSystemUPHandler.addErrorCount(HtcSystemUPHandler.java:294)
08-23 12:28:03.337  1108  3626 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessageInternal(HtcSystemUPHandler.java:73)
08-23 12:28:03.337  1108  3626 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessage(HtcSystemUPHandler.java:46)
08-23 12:28:03.337  1108  3626 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 12:28:03.337  1108  3626 W System.err: 	at android.os.Looper.loop(Looper.java:155)
08-23 12:28:03.337  1108  3626 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-23 12:28:03.337  1108  3626 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-23 12:28:03.337  1108  3626 W System.err: 	at libcore.io.Posix.open(Native Method)
08-23 12:28:03.337  1108  3626 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-23 12:28:03.337  1108  3626 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-23 12:28:03.337  1108  3626 W System.err: 	... 12 more
,08-23 12:28:03.357  9510  9510 D ExternalStorage: After updating volumes, found 1 active roots
,08-23 12:28:03.357  9525  9525 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1830 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:23 android.app.ActivityThread.handleReceiver:2719 
,08-23 12:28:03.367  9525  9563 D PowerUtils: getUserIdOfProcess, curUserId = 0
08-23 12:28:03.367  9525  9563 D PowerUtils: isRunningUnderOwner, isOwner = true
,08-23 12:28:03.377  1108  4754 I ActivityManager: Start proc 9564:com.htc.updater/u0a68 for broadcast com.htc.updater/.download.DownloadReceiver
,08-23 12:28:03.377  9525  9563 D PowerUsageList:PowerUsageHelper: MY_DEBUG = false
,08-23 12:28:03.377  9564  9564 W HTCLOG  : use specified tag [FDManager], func [0].
08-23 12:28:03.377  9564  9564 W HTCLOG  : mask=0x18
,08-23 12:28:03.397  9525  9563 D PowerUsageService: removed uid = 10142

```
