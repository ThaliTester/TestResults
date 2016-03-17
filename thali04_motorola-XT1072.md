#### Test 62509094141ff10_thali04_motorola-XT1072 Logs


```
--------- beginning of system
03-17 11:17:32.739   878  1084 I ActivityManager: Start proc com.google.android.apps.docs for service com.google.android.apps.docs/.sync.syncadapter.DocsSyncAdapterService: pid=4269 uid=10057 gids={50057, 9997, 1028, 3003, 1015} abi=armeabi-v7a
03-17 11:17:32.747   878  1088 I ActivityManager: Waited long enough for: ServiceRecord{3ba09d0f u0 com.qualcomm.atfwd/.AtFwdService}
--------- beginning of main
03-17 11:17:32.752  1460  2706 I art     : Explicit concurrent mark sweep GC freed 3630(152KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 977us total 40.220ms
03-17 11:17:32.772  1460  1460 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.internal.settings.SettingsTrigger.onReceive:258 android.app.LoadedApk$ReceiverDispatcher$Args.run:870 android.os.Handler.handleCallback:739 
03-17 11:17:32.777  4228  4228 I MultiDex: VM with version 2.1.0 has multidex support
03-17 11:17:32.777  4228  4228 I MultiDex: install
03-17 11:17:32.777  4228  4228 I MultiDex: VM has multidex support, MultiDex support library is disabled.
03-17 11:17:32.786  4246  4246 I CalendarProvider2: Created com.android.providers.calendar.CalendarAlarmManager@c84b9ec(com.android.providers.calendar.CalendarProvider2@3db141b5)
03-17 11:17:32.840  4228  4228 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,03-17 11:17:32.863  4046  4046 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
03-17 11:17:32.919  4228  4228 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
03-17 11:17:32.919  4228  4228 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@ecc656f: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
03-17 11:17:32.919  4228  4228 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
03-17 11:17:33.010  4228  4228 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
03-17 11:17:33.010  4228  4228 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
03-17 11:17:33.052   878  1550 I art     : Explicit concurrent mark sweep GC freed 4104(175KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 2.167ms total 117.587ms
03-17 11:17:33.079  4046  4046 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
03-17 11:17:33.079  4046  4046 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
03-17 11:17:33.085  1288  1288 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
03-17 11:17:33.150  2665  2725 I MMApiWSBase: doRequest(): url: https://argo.svcmot.com:443/v1/sage/model.json/2072049230914535424?os_ver=LXB22.46-28&tag=production&anchor=0&id=&app_ver=5.18.063&appid=X5T7HI5PQOMVP5DA31Q3Z4W5FZAM6Y4S&cemodel=1.1&deviceid=2072049230914535424&devicetype=XT1072
03-17 11:17:33.152  2665  2725 D Checkin : publish the event [tag = MOT_CCE event name = LOG]
03-17 11:17:33.236  4116  4188 I Gmail   : getAccountsCursor
03-17 11:17:33.256   295   979 D WVCdm   : Instantiating CDM.
03-17 11:17:33.272   295   295 I WVCdm   : CdmEngine::OpenSession
03-17 11:17:33.272   295   295 I WVCdm   : Level3 Library Sep 25 2014 17:10:03
03-17 11:17:33.294   295   295 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
03-17 11:17:33.312  4228  4299 D NativeLibraryUtils: Install completed successfully. count=14 extracted=0
03-17 11:17:33.326   295   295 D DrmWidevineDash: OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
03-17 11:17:33.326   295   295 D DrmWidevineDash: Service_Initialize: starts!
03-17 11:17:33.327   295   295 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
03-17 11:17:33.327   295   295 D QSEECOMAPI: : App is not loaded in QSEE
03-17 11:17:33.327   295   295 E QSEECOMAPI: : Error::Cannot open the file /vendor/firmware/widevine.mdt
03-17 11:17:33.327   295   295 E QSEECOMAPI: : Error::Loading image failed with ret = -1
03-17 11:17:33.328   295   295 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
03-17 11:17:33.328   295   295 D QSEECOMAPI: : App is not loaded in QSEE
03-17 11:17:33.328   295   295 E QSEECOMAPI: : Error::Cannot open the file /system/etc/firmware/widevine.mdt
03-17 11:17:33.328   295   295 E QSEECOMAPI: : Error::Loading image failed with ret = -1
03-17 11:17:33.329   295   295 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
03-17 11:17:33.329   295   295 D QSEECOMAPI: : App is not loaded in QSEE
03-17 11:17:33.378   295   295 D QSEECOMAPI: : Loaded image: APP id = 3
03-17 11:17:33.380   295   295 D DrmWidevineDash: Service_Initialize: ends! returns 0
03-17 11:17:33.380   295   295 D DrmWidevineDash: OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4ee1000
03-17 11:17:33.380   295   295 E DrmWidevineDash: sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4ee1000
03-17 11:17:33.391   295   295 D DrmWidevineDash: OEMCrypto_Initialize: ends! returns 0
03-17 11:17:33.391   295   295 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
03-17 11:17:33.392   295   295 D DrmWidevineDash: hlos api version =  9
03-17 11:17:33.392   295   295 D DrmWidevineDash: tz api version =  8
03-17 11:17:33.392   295   295 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 9
03-17 11:17:33.392   295   295 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: starts!
03-17 11:17:33.412   295   295 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: ends! returns 0
03-17 11:17:33.412   295   295 D WVCdm   : OEMCrypto_Initialize Level 1 success. I will use level 1.
03-17 11:17:33.412   295   295 D DrmWidevineDash: OEMCrypto_OpenSession: starts! SID=0xbed584e0
03-17 11:17:33.412   295   295 D DrmWidevineDash: OEMCrypto_OpenSession SID = 1
03-17 11:17:33.412   295   295 D DrmWidevineDash: OEMCrypto_OpenSession: ends! returns 0
03-17 11:17:33.412   295   295 D DrmWidevineDash: OEMCrypto_GetRandom: starts! randomData=0xb7a412a8, dataLength=8
03-17 11:17:33.413   295   295 D DrmWidevineDash: OEMCrypto_GetRandom: ends! returns 0
03-17 11:17:33.418   295   295 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb79c0b50, wrapped_rsa_key_length=1280
03-17 11:17:33.421   295   295 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: ends! returns 0
03-17 11:17:33.421   295   295 I WVCdm   : CdmEngine::QueryKeyControlInfo
03-17 11:17:33.425   295   977 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
03-17 11:17:33.425   295   977 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
03-17 11:17:33.425   295   977 I WVCdm   : CdmEngine::GenerateKeyRequest
03-17 11:17:33.425   295   977 D DrmWidevineDash: OEMCrypto_GetDeviceID: starts! deviceID=0xb7a8cd28, idLength=0xb54ae730
03-17 11:17:33.434   295   977 D DrmWidevineDash: OEMCrypto_GetDeviceID: ends! returns 0
03-17 11:17:33.434   295   977 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: starts!
03-17 11:17:33.434   295   977 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: is_supported = 1
03-17 11:17:33.434   295   977 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: wv_app_version = 25
03-17 11:17:33.434   295   977 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: ends! returns 0x0
03-17 11:17:33.434   295   977 D DrmWidevineDash: OEMCrypto_GetHDCPCapability: starts!
03-17 11:17:33.434   295   977 D DrmWidevineDash: OEMCrypto_GetHDCPCapability: ends! returns 0x0
03-17 11:17:33.435   295   977 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
03-17 11:17:33.435   295   977 D DrmWidevineDash: hlos api version =  9
03-17 11:17:33.435   295   977 D DrmWidevineDash: tz api version =  8
03-17 11:17:33.435   295   977 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 9
03-17 11:17:33.435   295   977 D DrmWidevineDash: OEMCrypto_GenerateNonce: starts! SID=1
03-17 11:17:33.436   295   977 D DrmWidevineDash: OEMCrypto_GenerateNonce: ends! returns 0
03-17 11:17:33.436   295   977 D WVCdm   : PrepareKeyRequest: nonce=1651609391
03-17 11:17:33.436   295   977 D DrmWidevineDash: OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb7993ff8
03-17 11:17:33.436   295   977 D DrmWidevineDash: message_length=1591, signature=0xb799cbe0, signature_length=3041584916
03-17 11:17:33.439  4228  4244 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
03-17 11:17:33.458  4297  4297 D AndroidRuntime: 
03-17 11:17:33.458  4297  4297 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
03-17 11:17:33.466  4297  4297 D AndroidRuntime: CheckJNI is OFF
03-17 11:17:33.557  2665  4071 W Settings: Setting dropbox_quota_kb has moved from android.provider.Settings.System to android.provider.Settings.Global
03-17 11:17:33.559  2665  4071 W Settings: Setting dropbox_quota_kb has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
03-17 11:17:33.559  2665  4071 W Settings: Setting dropbox_max_files has moved from android.provider.Settings.System to android.provider.Settings.Global
03-17 11:17:33.560  2665  4071 W Settings: Setting dropbox_max_files has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
03-17 11:17:33.647   295   977 D DrmWidevineDash: OEMCrypto_GenerateRSASignature returns 0
03-17 11:17:33.648   295   981 I WVCdm   : CdmEngine::CloseSession
03-17 11:17:33.648   295   981 D DrmWidevineDash: OEMCrypto_CloseSession: starts! SID=1
03-17 11:17:33.649   295   981 D DrmWidevineDash: OEMCrypto_CloseSession: ends! returns 0
03-17 11:17:33.649   295   981 I WVCdm   : L3 Terminate.
03-17 11:17:33.649   295   981 D DrmWidevineDash: OEMCrypto_Terminate: starts!
03-17 11:17:33.649   295   981 D DrmWidevineDash: Service_Uninitialize: starts!
03-17 11:17:33.649   295   981 D QSEECOMAPI: : QSEECom_dealloc_memory 
03-17 11:17:33.649   295   981 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 3
03-17 11:17:33.649   295   981 D DrmWidevineDash: Service_Uninitialize: ends! returns 0x0
03-17 11:17:33.650   295   981 D DrmWidevineDash: OEMCrypto_Terminate: ends! returns 0
03-17 11:17:33.731  4269  4269 I GAv4    : Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
03-17 11:17:33.731  4269  4269 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
03-17 11:17:33.731  4269  4269 I GAv4    :   adb logcat -s GAv4
03-17 11:17:33.745  4269  4269 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
03-17 11:17:33.765  4269  4269 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
03-17 11:17:33.769  4269  4324 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
03-17 11:17:33.774  4297  4297 D AndroidRuntime: Calling main entry com.android.commands.am.Am
03-17 11:17:33.784   878   893 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
03-17 11:17:33.788  4269  4269 W AnalyticsTrackerProxyImpl: Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.30
03-17 11:17:33.816   278  1491 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (202 us)
03-17 11:17:33.833  1460  3976 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
03-17 11:17:33.845  4297  4297 D AndroidRuntime: Shutting down VM
03-17 11:17:33.890   878  1586 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4329 uid=10109 gids={50109, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
03-17 11:17:33.909  4246  4246 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
03-17 11:17:33.910  4246  4246 W ContentResolver: Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
03-17 11:17:33.919  4269  4285 W art     : Suspending all threads took: 11.937ms
03-17 11:17:33.947  1460  3976 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
03-17 11:17:34.003   277   464 E Vold    : Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.docs/cache/
03-17 11:17:34.003   277   464 W Vold    : Returning OperationFailed - no handler for errno 0
03-17 11:17:34.008  4269  4348 W ContextImpl: Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.docs/cache
03-17 11:17:34.040  4269  4269 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-17 11:17:34.041  4269  4269 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
03-17 11:17:34.045  4269  4349 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-17 11:17:34.045  4269  4349 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-17 11:17:34.102  4269  4269 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,03-17 11:17:34.111  1288  1288 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-17 11:17:34.131  3116  3136 D Checkin : publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,03-17 11:17:34.169  4329  4329 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,03-17 11:17:34.186  2023  2023 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 11:17:34.211  4269  4269 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
03-17 11:17:34.212  4269  4269 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,03-17 11:17:34.234  4329  4329 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 96-99)
,03-17 11:17:34.234  4329  4329 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-17 11:17:34.250  2665  2725 D MMApiWSBase: doRequest(): v1/sage/model resp length: 2
,03-17 11:17:34.251  2665  2725 D CCE     : AppWSProxy - handleResponse(): error=None errorText= statusCode=200 reqId=com.motorola.context.ccc
,03-17 11:17:34.251  2665  2725 D CCE     : AppWSProxy - sendWSResponse(): sending response to com.motorola.context.ccc.WS_RESPONSE for reqID: com.motorola.context.ccc error: None
,03-17 11:17:34.280   878  1550 D WifiService: acquireWifiLockLocked: WifiLock{BaseSyncManager type=1 binder=android.os.BinderProxy@1a1801c9}
,03-17 11:17:34.296  4329  4329 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1a0ebbb}
,03-17 11:17:34.301  4329  4329 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-17 11:17:34.311  4329  4329 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,03-17 11:17:34.341  4329  4329 I BrowserStartupController: Initializing chromium process, singleProcess=true
,03-17 11:17:34.343  4329  4329 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-17 11:17:34.347  4329  4329 E SysUtils: ApplicationContext is null in ApplicationStatus
,03-17 11:17:34.379  4098  4204 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-17 11:17:34.526  4329  4329 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,03-17 11:17:34.535   320   320 I Atfwd_Daemon: result : 0 	 ,Init step :2 	 ,qmiErrorCode: 0
03-17 11:17:34.535   320   320 I Atfwd_Daemon: ATFWD --> QMI Port : rmnet1
,03-17 11:17:34.537  4329  4329 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-17 11:17:34.538  4329  4329 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,03-17 11:17:34.540   426   828 E QC-QMI  : qmi_ctl_rx_msg.c Can't find txn info for txn_id = 13
03-17 11:17:34.540   320   320 I Atfwd_Daemon: qmi_atcop_srvc_init_client - QMI Err code 0 , handle 16844800
03-17 11:17:34.540   320   320 I Atfwd_Daemon: Trying to register 8 commands:
03-17 11:17:34.540   320   320 I Atfwd_Daemon: cmd0: +CKPD
,03-17 11:17:34.541  4329  4329 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
03-17 11:17:34.541  4329  4329 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.01.03
03-17 11:17:34.541  4329  4329 I Adreno-EGL: Build Date: 10/28/14 Tue
03-17 11:17:34.541  4329  4329 I Adreno-EGL: Local Branch: 
03-17 11:17:34.541  4329  4329 I Adreno-EGL: Remote Branch: quic/l_LNX.LA.3.6
03-17 11:17:34.541  4329  4329 I Adreno-EGL: Local Patches: NONE
03-17 11:17:34.541  4329  4329 I Adreno-EGL: Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,03-17 11:17:34.543   320   320 I Atfwd_Daemon: qmi_atcop_reg_at_command_fwd_req: 0
03-17 11:17:34.543   320   320 I Atfwd_Daemon: cmd1: +CTSA
,03-17 11:17:34.546   320   320 I Atfwd_Daemon: qmi_atcop_reg_at_command_fwd_req: 0
03-17 11:17:34.546   320   320 I Atfwd_Daemon: cmd2: +CFUN
,03-17 11:17:34.548   320   320 I Atfwd_Daemon: qmi_atcop_reg_at_command_fwd_req: 0
03-17 11:17:34.548   320   320 I Atfwd_Daemon: cmd3: +CMAR
,03-17 11:17:34.550   320   320 I Atfwd_Daemon: qmi_atcop_reg_at_command_fwd_req: 0
,03-17 11:17:34.551   320   320 I Atfwd_Daemon: cmd4: +CDIS
,03-17 11:17:34.553   320   320 I Atfwd_Daemon: qmi_atcop_reg_at_command_fwd_req: 0
03-17 11:17:34.553   320   320 I Atfwd_Daemon: cmd5: +CRSL
03-17 11:17:34.556   320   320 I Atfwd_Daemon: qmi_atcop_reg_at_command_fwd_req: 0
03-17 11:17:34.556   320   320 I Atfwd_Daemon: cmd6: +CSS
,03-17 11:17:34.558   320   320 I Atfwd_Daemon: qmi_atcop_reg_at_command_fwd_req: 0
03-17 11:17:34.559   320   320 I Atfwd_Daemon: cmd7: +CSO
,03-17 11:17:34.561   320   320 I Atfwd_Daemon: qmi_atcop_reg_at_command_fwd_req: 0
03-17 11:17:34.561   320   320 I Atfwd_Daemon: Registered AT Commands event handler
,03-17 11:17:34.562  4228  4243 I art     : Background partial concurrent mark sweep GC freed 8092(470KB) AllocSpace objects, 7(317KB) LOS objects, 40% free, 10MB/17MB, paused 6.991ms total 75.470ms
,03-17 11:17:34.626   878  1103 D BluetoothManagerService: Message: 20
03-17 11:17:34.626   878  1103 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1c27ef39:true
,03-17 11:17:34.799  4329  4329 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-17 11:17:34.826  4329  4329 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,03-17 11:17:34.844  4329  4329 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,03-17 11:17:34.869  4329  4329 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-17 11:17:34.869  4329  4329 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-17 11:17:34.923  4269  4356 W Flag    : Duration spec must be at least 2 characters long
,03-17 11:17:34.958  4329  4396 D OpenGLRenderer: Render dirty regions requested: true
,03-17 11:17:34.968  4329  4329 D Atlas   : Validating map...
,03-17 11:17:34.977  4329  4379 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,03-17 11:17:35.026  4329  4396 I OpenGLRenderer: Initialized EGL, version 1.4
,03-17 11:17:35.033  4329  4396 D OpenGLRenderer: Enabling debug mode 0
,03-17 11:17:35.093  1411  1411 I Keyboard.Facilitator: onFinishInput()
,03-17 11:17:35.110   878  1104 I LaunchCheckinHandler: Displayed com.test.thalitest/.MainActivity,cp,ca,1260
03-17 11:17:35.110   878  1104 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +1s266ms
,03-17 11:17:35.196   293   517 I MDMCTBK : NetlinkHandler, power_supply subsys
03-17 11:17:35.196   293   517 I MDMCTBK : NetlinkHandler, usbChargerStateChanged
03-17 11:17:35.196   293   517 I MDMCTBK : checkDefaultInst, current pid is = 293
03-17 11:17:35.196   293   517 I MDMCTBK : checkDefaultInst, pid match
03-17 11:17:35.196   293   517 I MDMCTBK : MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
03-17 11:17:35.196   293   517 I MDMCTBK : MdmCutbackHndler,readFromFile = 
03-17 11:17:35.196   293   517 E MDMCTBK : MdmCutbackHndler,Could not open ''
03-17 11:17:35.196   293   517 I MDMCTBK : NetlinkHandler, power_supply subsys
03-17 11:17:35.196   293   517 I MDMCTBK : NetlinkHandler, usbChargerStateChanged
03-17 11:17:35.196   293   517 I MDMCTBK : checkDefaultInst, current pid is = 293
03-17 11:17:35.196   293   517 I MDMCTBK : checkDefaultInst, pid match
03-17 11:17:35.197   293   517 I MDMCTBK : MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
03-17 11:17:35.197   293   517 I MDMCTBK : MdmCutbackHndler,readFromFile = 
03-17 11:17:35.197   293   517 E MDMCTBK : MdmCutbackHndler,Could not open ''
03-17 11:17:35.197   293   517 I MDMCTBK : NetlinkHandler, power_supply subsys
03-17 11:17:35.197   293   517 I MDMCTBK : NetlinkHandler, usbChargerStateChanged
03-17 11:17:35.197   293   517 I MDMCTBK : checkDefaultInst, current pid is = 293
03-17 11:17:35.197   293   517 I MDMCTBK : checkDefaultInst, pid match
03-17 11:17:35.197   293   517 I MDMCTBK : MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
03-17 11:17:35.197   293   517 I MDMCTBK : MdmCutbackHndler,readFromFile = 
03-17 11:17:35.197   293   517 E MDMCTBK : MdmCutbackHndler,Could not open ''
,03-17 11:17:35.199  1288  1288 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
03-17 11:17:35.199  1288  1288 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-17 11:17:35.217  2023  2023 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 11:17:35.221  4329  4404 E Adreno-ES20: <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
03-17 11:17:35.221  4329  4404 E Adreno-ES20: <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,03-17 11:17:35.239  2665  2697 W DataUsage: invalid counter update blocked: 'err' by 0
,03-17 11:17:35.241  2665  2697 D Checkin : publish the event [tag = MOT_CCE event name = LOG]
,03-17 11:17:35.268  4329  4329 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 4329
,03-17 11:17:35.419   878  1221 V AlarmManager: send {8a22d1d, *walarm*:com.android.providers.calendar.intent.CalendarProvider2}
,03-17 11:17:35.459  2665  4071 W Settings: Setting dropbox_quota_kb has moved from android.provider.Settings.System to android.provider.Settings.Global
,03-17 11:17:35.460  2665  4071 W Settings: Setting dropbox_quota_kb has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
03-17 11:17:35.460  2665  4071 W Settings: Setting dropbox_max_files has moved from android.provider.Settings.System to android.provider.Settings.Global
03-17 11:17:35.461  2665  4071 W Settings: Setting dropbox_max_files has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,03-17 11:17:35.462  2665  4071 I global frequency: BcsTimer.setTimer(86400000, 86400000)
03-17 11:17:35.464  2665  4071 D Checkin : publish the event [tag = MOT_CHECKIN event name = LOG]
,03-17 11:17:35.466  1460  1502 D Central_PollingManager: registerApp(): Checkin
03-17 11:17:35.466  1460  1502 D Central_PollingManager: registerApp(): Checkin already registered.
,03-17 11:17:35.467  1460  4122 D Central_PollingManager: modifyApp(): Checkin
,03-17 11:17:35.470  1460  4122 D Central_PollingManager: calculateShortestInterval(): shortest interval is 21600000
,03-17 11:17:35.477  2665  4071 W MotorolaSettings: no such table to get this name = privacy_droid_blast
03-17 11:17:35.477  2665  4071 W System.err: java.lang.Exception
03-17 11:17:35.477  2665  4071 W System.err: 	at com.motorola.android.provider.MotorolaSettings.getString(MotorolaSettings.java:290)
03-17 11:17:35.477  2665  4071 W System.err: 	at com.motorola.android.provider.MotorolaSettings.getInt(MotorolaSettings.java:328)
03-17 11:17:35.477  2665  4071 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
03-17 11:17:35.478  2665  4071 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-17 11:17:35.478  2665  4071 W System.err: 	at com.motorola.ccc.checkin.MotorolaSettings.getInt(MotorolaSettings.java:106)
03-17 11:17:35.478  2665  4071 W System.err: 	at com.motorola.ccc.checkin.PrivacyHelper.readPrivacy(PrivacyHelper.java:413)
03-17 11:17:35.478  2665  4071 W System.err: 	at com.motorola.ccc.checkin.PrivacyHelper.reconfigurePrivacy(PrivacyHelper.java:160)
03-17 11:17:35.478  2665  4071 W System.err: 	at com.motorola.ccc.checkin.BcsConfigAndroid.handleConfigChange(BcsConfigAndroid.java:996)
03-17 11:17:35.478  2665  4071 W System.err: 	at com.motorola.ccc.checkin.BcsConfigAndroid.update(BcsConfigAndroid.java:518)
03-17 11:17:35.478  2665  4071 W System.err: 	at com.motorola.ccc.checkin.BcsCore.doConfig(BcsCore.java:662)
03-17 11:17:35.478  2665  4071 W System.err: 	at com.motorola.ccc.checkin.BcsCore.handleEvent(BcsCore.java:332)
03-17 11:17:35.478  2665  4071 W System.err: 	at com.motorola.ccc.checkin.BcsPlatformAndroid.handleCceSendSettingsResponse(BcsPlatformAndroid.java:432)
03-17 11:17:35.478  2665  4071 W System.err: 	at com.motorola.ccc.checkin.BcsPlatformAndroid.onReceiveActions(BcsPlatformAndroid.java:403)
03-17 11:17:35.478  2665  4071 W System.err: 	at com.motorola.ccc.checkin.BcsPlatformAndroid.access$000(BcsPlatformAndroid.java:87)
03-17 11:17:35.478  2665  4071 W System.err: 	at com.motorola.ccc.checkin.BcsPlatformAndroid$1.run(BcsPlatformAndroid.java:295)
03-17 11:17:35.478  2665  4071 W System.err: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-17 11:17:35.478  2665  4071 W System.err: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-17 11:17:35.478  2665  4071 W System.err: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-17 11:17:35.478  2665  4071 W System.err: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-17 11:17:35.478  2665  4071 W System.err: 	at java.lang.Thread.run(Thread.java:818)
03-17 11:17:35.482  2665  4071 I global frequency: BcsConfigAndroid:updateAllowedEventTagsForPrivacyProfile Blacklisted tags: (DUMMY_TAG:1416552400)
,03-17 11:17:35.484  2665  4071 D Checkin : publish the event [tag = MOT_CHECKIN event name = LOG]
03-17 11:17:35.486  2665  4071 I global frequency: BcsConfigAndroid:updateAllowedEventTagsForPrivacyProfile new whitelisted checkin event tags: MOT_OTA:LOG,MOT_PRIVACY_PROFILE,DEV_ATTRIBS,CHECKIN_SUCCESS,MOT_CCE_STATS:CS_Notif_FFA,DEVICE_PROPERTIES,CHECKIN_FAILURE
03-17 11:17:35.492  2665  4071 D Checkin : publish the event [tag = MOT_CHECKIN event name = LOG]
03-17 11:17:35.497  2665  4071 D Checkin : publish the event [tag = MOT_PRIVACY_PROFILE event name = PRIVACY]
03-17 11:17:35.508  4329  4329 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,03-17 11:17:35.537   878  1459 I ActivityManager: Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=4409 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,03-17 11:17:35.582  2023  2023 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 11:17:35.606   878  1221 V AlarmManager: send {2479ab8c, *walarm*:com.google.android.intent.action.GCM_RECONNECT}
,03-17 11:17:36.079  4329  4396 E Adreno-ES20: <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
03-17 11:17:36.080  4329  4396 E Adreno-ES20: <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,03-17 11:17:36.095  2665  4071 W Settings: Setting dropbox_quota_kb has moved from android.provider.Settings.System to android.provider.Settings.Global
03-17 11:17:36.096  2665  4071 W Settings: Setting dropbox_quota_kb has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
03-17 11:17:36.096  2665  4071 W Settings: Setting dropbox_max_files has moved from android.provider.Settings.System to android.provider.Settings.Global
03-17 11:17:36.097  2665  4071 W Settings: Setting dropbox_max_files has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,03-17 11:17:36.104  2665  4071 W MotorolaSettings: no such table to get this name = privacy_droid_blast
03-17 11:17:36.104  2665  4071 W System.err: java.lang.Exception
03-17 11:17:36.105  2665  4071 W System.err: 	at com.motorola.android.provider.MotorolaSettings.getString(MotorolaSettings.java:290)
03-17 11:17:36.105  2665  4071 W System.err: 	at com.motorola.android.provider.MotorolaSettings.getInt(MotorolaSettings.java:328)
03-17 11:17:36.105  2665  4071 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
03-17 11:17:36.105  2665  4071 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-17 11:17:36.105  2665  4071 W System.err: 	at com.motorola.ccc.checkin.MotorolaSettings.getInt(MotorolaSettings.java:106)
03-17 11:17:36.105  2665  4071 W System.err: 	at com.motorola.ccc.checkin.PrivacyHelper.readPrivacy(PrivacyHelper.java:413)
03-17 11:17:36.105  2665  4071 W System.err: 	at com.motorola.ccc.checkin.PrivacyHelper.reconfigurePrivacy(PrivacyHelper.java:160)
03-17 11:17:36.105  2665  4071 W System.err: 	at com.motorola.ccc.checkin.BcsConfigAndroid.handleConfigChange(BcsConfigAndroid.java:996)
03-17 11:17:36.105  2665  4071 W System.err: 	at com.motorola.ccc.checkin.BcsConfigAndroid.update(BcsConfigAndroid.java:518)
03-17 11:17:36.105  2665  4071 W System.err: 	at com.motorola.ccc.checkin.BcsCore.doConfig(BcsCore.java:662)
03-17 11:17:36.105  2665  4071 W System.err: 	at com.motorola.ccc.checkin.BcsCore.handleEvent(BcsCore.java:332)
03-17 11:17:36.105  2665  4071 W System.err: 	at com.motorola.ccc.checkin.BcsPlatformAndroid.handleCceSendSettingsResponse(BcsPlatformAndroid.java:432)
03-17 11:17:36.105  2665  4071 W System.err: 	at com.motorola.ccc.checkin.BcsPlatformAndroid.onReceiveActions(BcsPlatformAndroid.java:403)
03-17 11:17:36.105  2665  4071 W System.err: 	at com.motorola.ccc.checkin.BcsPlatformAndroid.access$000(BcsPlatformAndroid.java:87)
03-17 11:17:36.105  2665  4071 W System.err: 	at com.motorola.ccc.checkin.BcsPlatformAndroid$1.run(BcsPlatformAndroid.java:295)
03-17 11:17:36.105  2665  4071 W System.err: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-17 11:17:36.105  2665  4071 W System.err: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-17 11:17:36.105  2665  4071 W System.err: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-17 11:17:36.105  2665  4071 W System.err: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-17 11:17:36.105  2665  4071 W System.err: 	at java.lang.Thread.run(Thread.java:818)
,03-17 11:17:36.109  2665  4071 I global frequency: BcsConfigAndroid:updateAllowedEventTagsForPrivacyProfile Blacklisted tags: (DUMMY_TAG:1416552400)
,03-17 11:17:36.111  2665  4071 D Checkin : publish the event [tag = MOT_CHECKIN event name = LOG]
,03-17 11:17:36.113  2665  4071 I global frequency: BcsConfigAndroid:updateAllowedEventTagsForPrivacyProfile new whitelisted checkin event tags: MOT_OTA:LOG,MOT_PRIVACY_PROFILE,DEV_ATTRIBS,CHECKIN_SUCCESS,MOT_CCE_STATS:CS_Notif_FFA,DEVICE_PROPERTIES,CHECKIN_FAILURE
,03-17 11:17:36.114  2665  4071 D Checkin : publish the event [tag = MOT_CHECKIN event name = LOG]
,03-17 11:17:36.115  4329  4403 D jxcore_app_log: JniHelper::setJavaVM(0xb8ee3310), pthread_self() = -1188611520
,03-17 11:17:36.115  2665  4071 D Checkin : publish the event [tag = MOT_PRIVACY_PROFILE event name = PRIVACY]
,03-17 11:17:36.128  4329  4403 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
03-17 11:17:36.128  4329  4403 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
03-17 11:17:36.128  4329  4403 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
03-17 11:17:36.128  4329  4403 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
03-17 11:17:36.128  4329  4403 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
03-17 11:17:36.128  4329  4403 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32a61e77 added. We now have 1 listener(s)
03-17 11:17:36.128   878  1594 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,03-17 11:17:36.133  4329  4403 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 44:80:EB:7B:5A:05
,03-17 11:17:36.137  4329  4403 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"44:80:EB:7B:5A:05"}
03-17 11:17:36.138  4329  4403 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"name":"<no peer name>","address":"44:80:EB:7B:5A:05"}
03-17 11:17:36.138  4329  4403 D org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setHandshakeRequired: true -> false
03-17 11:17:36.138  4329  4403 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setHandshakeRequired: true -> false
,03-17 11:17:36.142  4329  4403 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
03-17 11:17:36.142  4329  4403 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
03-17 11:17:36.142  4329  4403 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
03-17 11:17:36.142  4329  4403 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 44:80:EB:7B:5A:05
03-17 11:17:36.142  4329  4403 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
03-17 11:17:36.142  4329  4403 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
03-17 11:17:36.142  4329  4403 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
03-17 11:17:36.142  4329  4403 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
03-17 11:17:36.142  4329  4403 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
03-17 11:17:36.142  4329  4403 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
03-17 11:17:36.142  4329  4403 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@14f21602 added. We now have 1 listener(s)
03-17 11:17:36.143  4329  4403 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,03-17 11:17:36.148   878  1235 D WifiService: New client listening to asynchronous messages
,03-17 11:17:36.150  4329  4403 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (NOT_SUPPORTED) in persistent storage
,03-17 11:17:36.154  4329  4403 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
03-17 11:17:36.155  4329  4403 E io.jxcore.node.ConnectionHelper: Constructor: Bluetooth LE discovery mode is not supported
,03-17 11:17:36.157  4329  4403 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-17 11:17:36.158   878  1653 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
03-17 11:17:36.159  4329  4403 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 44:80:EB:7B:5A:05
,03-17 11:17:36.164  4329  4403 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-17 11:17:36.164  4329  4403 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-17 11:17:36.164  4329  4403 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
03-17 11:17:36.164  4329  4403 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-17 11:17:36.164  4329  4403 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-17 11:17:36.164  4329  4403 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-17 11:17:36.164  4329  4403 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
,03-17 11:17:36.164  4329  4403 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
03-17 11:17:36.164  4329  4403 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
03-17 11:17:36.164  4329  4403 D io.jxcore.node.ConnectivityMonitor: start: OK
,03-17 11:17:36.307  4441  4441 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=33 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,03-17 11:17:36.385   878  1216 D BatteryService: uevent={POWER_SUPPLY_TEMP=332, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2363000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4304885, SEQNUM=4336, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=21530, POWER_SUPPLY_CHARGE_COUNTER=-145, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,03-17 11:17:36.425  2535  2604 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-17 11:17:36.437  4329  4343 I art     : Background sticky concurrent mark sweep GC freed 26021(1739KB) AllocSpace objects, 6(92KB) LOS objects, 7% free, 10MB/11MB, paused 1.860ms total 117.026ms
,03-17 11:17:36.452  2665  4071 W Settings: Setting dropbox_quota_kb has moved from android.provider.Settings.System to android.provider.Settings.Global
03-17 11:17:36.452  2665  4071 W Settings: Setting dropbox_quota_kb has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
03-17 11:17:36.452  2665  4071 W Settings: Setting dropbox_max_files has moved from android.provider.Settings.System to android.provider.Settings.Global
03-17 11:17:36.453   278   744 I SFPerfTracer:      triggers: (rate: 0:0) (0 sw vsyncs) (0 skipped) (30:241 vsyncs) (32:1039)
03-17 11:17:36.455   278   278 I SFPerfTracer:      triggers: (rate: 14:426) (compose: 0:1) (post: 0:1) (render: 0:2) (44:961 frames) (45:1039)
,03-17 11:17:36.455   278   278 D SFPerfTracer:        layers: (3:13) (FocusedStackFrame (0xb88b43f0): 0:14)* (DimLayer (0xb890b7c0): 0:6)* (com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (0xb8910328): 0:34)- (StatusBar (0xb8944b28): 0:125) (NavigationBar (0xb8946ba0): 0:36) (com.android.systemui.ImageWallpaper (0xb894a4f0): 0:5)* (Starting com.motorola.ccc.ota (0xb8940b20): 0:32)- (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity (0xb896cb88): 0:52)- (Starting com.test.thalitest (0xb8940b20): 0:41)- (com.test.thalitest/com.test.thalitest.MainActivity (0xb8910328): 45:51) 
03-17 11:17:36.453  2665  4071 W Settings: Setting dropbox_max_files has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,03-17 11:17:36.472  2535  2604 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-17 11:17:36.486  4329  4329 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-17 11:17:36.489  4329  4329 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-17 11:17:36.495  4329  4329 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,03-17 11:17:36.585  4441  4441 I dex2oat : dex2oat took 278.695ms (threads: 4)
,03-17 11:17:36.617  4228  4244 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
03-17 11:17:36.617  4228  4244 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.01.03
03-17 11:17:36.617  4228  4244 I Adreno-EGL: Build Date: 10/28/14 Tue
03-17 11:17:36.617  4228  4244 I Adreno-EGL: Local Branch: 
03-17 11:17:36.617  4228  4244 I Adreno-EGL: Remote Branch: quic/l_LNX.LA.3.6
03-17 11:17:36.617  4228  4244 I Adreno-EGL: Local Patches: NONE
03-17 11:17:36.617  4228  4244 I Adreno-EGL: Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,03-17 11:17:36.697   878  1594 I ActivityManager: Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=4455 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,03-17 11:17:36.716   878  1513 I ActivityManager: Killing 2910:com.android.defcontainer/u0a10 (adj 15): empty #7
,03-17 11:17:36.741  4116  4177 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,03-17 11:17:36.850  4228  4244 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
03-17 11:17:36.850  4228  4244 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.01.03
03-17 11:17:36.850  4228  4244 I Adreno-EGL: Build Date: 10/28/14 Tue
03-17 11:17:36.850  4228  4244 I Adreno-EGL: Local Branch: 
03-17 11:17:36.850  4228  4244 I Adreno-EGL: Remote Branch: quic/l_LNX.LA.3.6
03-17 11:17:36.850  4228  4244 I Adreno-EGL: Local Patches: NONE
03-17 11:17:36.850  4228  4244 I Adreno-EGL: Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,03-17 11:17:36.899   878  1522 I ActivityManager: Killing 4157:com.google.android.gm.exchange/u0a60 (adj 15): empty #7
,03-17 11:17:37.066   878  1464 W libprocessgroup: failed to open /acct/uid_10010/pid_2910/cgroup.procs: No such file or directory
,03-17 11:17:37.072   878  1217 W libprocessgroup: failed to open /acct/uid_10060/pid_4157/cgroup.procs: No such file or directory
,03-17 11:17:37.103   878  1221 V AlarmManager: send {18c554f3, *alarm*:com.android.server.WifiManager.action.START_SCAN}
,03-17 11:17:37.106   878  1221 V AlarmManager: send {3a07dfd, *alarm*:send_events}
03-17 11:17:37.106   878   878 V AlarmManager: done {3a07dfd, *alarm*:send_events} [3ms]
,03-17 11:17:37.157  4228  4244 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
03-17 11:17:37.157  4228  4244 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.01.03
03-17 11:17:37.157  4228  4244 I Adreno-EGL: Build Date: 10/28/14 Tue
03-17 11:17:37.157  4228  4244 I Adreno-EGL: Local Branch: 
03-17 11:17:37.157  4228  4244 I Adreno-EGL: Remote Branch: quic/l_LNX.LA.3.6
03-17 11:17:37.157  4228  4244 I Adreno-EGL: Local Patches: NONE
03-17 11:17:37.157  4228  4244 I Adreno-EGL: Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,03-17 11:17:37.165   878  1503 I ActivityManager: Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=4484 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,03-17 11:17:37.286  4484  4484 W asset   : Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
03-17 11:17:37.286  4484  4484 W ResourcesManager: Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
03-17 11:17:37.286  4484  4484 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
03-17 11:17:37.287  4484  4484 W ResourcesManager: Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,03-17 11:17:37.312  4228  4244 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
03-17 11:17:37.312  4228  4244 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.01.03
03-17 11:17:37.312  4228  4244 I Adreno-EGL: Build Date: 10/28/14 Tue
03-17 11:17:37.312  4228  4244 I Adreno-EGL: Local Branch: 
03-17 11:17:37.312  4228  4244 I Adreno-EGL: Remote Branch: quic/l_LNX.LA.3.6
03-17 11:17:37.312  4228  4244 I Adreno-EGL: Local Patches: NONE
03-17 11:17:37.312  4228  4244 I Adreno-EGL: Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,03-17 11:17:37.365  4329  4439 W jxcore-log: Initializing JXcore engine
03-17 11:17:37.366  4329  4439 W jxcore-log: JXcore engine is ready
,03-17 11:17:37.394   878   893 I ActivityManager: Killing 4116:com.google.android.gm/u0a63 (adj 15): empty #7
,03-17 11:17:37.462  4439  4439 W Thread-444: type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10109 path="socket:[5557]" dev="sockfs" ino=5557 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
03-17 11:17:37.462  4439  4439 W Thread-444: type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10109 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
03-17 11:17:37.462  4439  4439 W Thread-444: type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10109 path="socket:[7344]" dev="sockfs" ino=7344 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
03-17 11:17:37.462  4439  4439 W Thread-444: type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10109 path="socket:[20540]" dev="sockfs" ino=20540 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,03-17 11:17:37.489  4329  4439 W jxcore-log: Starting JXcore engine
,03-17 11:17:37.526   878  1217 W libprocessgroup: failed to open /acct/uid_10063/pid_4116/cgroup.procs: No such file or directory
,03-17 11:17:37.585   878  1586 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4509 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-17 11:17:37.615   308   308 I art     : Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 259us total 30.664ms
,03-17 11:17:37.635   308   308 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 255us total 19.599ms
,03-17 11:17:37.648  4329  4439 W jxcore-log: Platform android
03-17 11:17:37.648  4329  4439 W jxcore-log: 
03-17 11:17:37.648  4329  4439 W jxcore-log: Process ARCH arm
03-17 11:17:37.648  4329  4439 W jxcore-log: 
,03-17 11:17:37.656   308   308 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 248us total 20.067ms
,03-17 11:17:37.659   878  1464 I ActivityManager: Killing 3848:com.motorola.context/u0a8 (adj 15): empty #7
,03-17 11:17:37.721   878  1551 D WifiService: releaseWifiLockLocked: WifiLock{BaseSyncManager type=1 binder=android.os.BinderProxy@1a1801c9}
,03-17 11:17:37.733   295   977 D WVCdm   : Instantiating CDM.
,03-17 11:17:37.733   295   979 I WVCdm   : CdmEngine::OpenSession
03-17 11:17:37.734   295   979 I WVCdm   : Level3 Library Sep 25 2014 17:10:03
,03-17 11:17:37.737   295   979 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,03-17 11:17:37.756   295   979 D DrmWidevineDash: OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
03-17 11:17:37.756   295   979 D DrmWidevineDash: Service_Initialize: starts!
03-17 11:17:37.756   295   979 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
,03-17 11:17:37.756   295   979 D QSEECOMAPI: : App is not loaded in QSEE
,03-17 11:17:37.756   295   979 E QSEECOMAPI: : Error::Cannot open the file /vendor/firmware/widevine.mdt
03-17 11:17:37.756   295   979 E QSEECOMAPI: : Error::Loading image failed with ret = -1
,03-17 11:17:37.756   295   979 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
03-17 11:17:37.756   295   979 D QSEECOMAPI: : App is not loaded in QSEE
03-17 11:17:37.757   295   979 E QSEECOMAPI: : Error::Cannot open the file /system/etc/firmware/widevine.mdt
03-17 11:17:37.757   295   979 E QSEECOMAPI: : Error::Loading image failed with ret = -1
03-17 11:17:37.757   295   979 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
03-17 11:17:37.757   295   979 D QSEECOMAPI: : App is not loaded in QSEE
,03-17 11:17:37.791   295   979 D QSEECOMAPI: : Loaded image: APP id = 3
,03-17 11:17:37.794   295   979 D DrmWidevineDash: Service_Initialize: ends! returns 0
03-17 11:17:37.794   295   979 D DrmWidevineDash: OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4ed4000
03-17 11:17:37.794   295   979 E DrmWidevineDash: sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4ed4000
,03-17 11:17:37.802   295   979 D DrmWidevineDash: OEMCrypto_Initialize: ends! returns 0
03-17 11:17:37.802   295   979 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
,03-17 11:17:37.802   295   979 D DrmWidevineDash: hlos api version =  9
03-17 11:17:37.802   295   979 D DrmWidevineDash: tz api version =  8
03-17 11:17:37.802   295   979 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 9
03-17 11:17:37.802   295   979 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: starts!
,03-17 11:17:37.819   295   979 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: ends! returns 0
03-17 11:17:37.819   295   979 D WVCdm   : OEMCrypto_Initialize Level 1 success. I will use level 1.
03-17 11:17:37.819   295   979 D DrmWidevineDash: OEMCrypto_OpenSession: starts! SID=0xb5008960
03-17 11:17:37.820   295   979 D DrmWidevineDash: OEMCrypto_OpenSession SID = 1
03-17 11:17:37.820   295   979 D DrmWidevineDash: OEMCrypto_OpenSession: ends! returns 0
03-17 11:17:37.820   295   979 D DrmWidevineDash: OEMCrypto_GetRandom: starts! randomData=0xb7a4a058, dataLength=8
03-17 11:17:37.820   295   979 D DrmWidevineDash: OEMCrypto_GetRandom: ends! returns 0
03-17 11:17:37.821   295   979 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb79c0b50, wrapped_rsa_key_length=1280
,03-17 11:17:37.823   295   979 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: ends! returns 0
03-17 11:17:37.823   295   979 I WVCdm   : CdmEngine::QueryKeyControlInfo
,03-17 11:17:37.826   878   893 W libprocessgroup: failed to open /acct/uid_10008/pid_3848/cgroup.procs: No such file or directory
,03-17 11:17:37.831   295   977 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
03-17 11:17:37.831   295   977 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
03-17 11:17:37.831   295   977 I WVCdm   : CdmEngine::GenerateKeyRequest
03-17 11:17:37.831   295   977 D DrmWidevineDash: OEMCrypto_GetDeviceID: starts! deviceID=0xb7a8cd68, idLength=0xb54ae730
,03-17 11:17:37.834   878  1251 D TaskPersister: removeObsoleteFile: deleting file=8_task_thumbnail.png
,03-17 11:17:37.841   295   977 D DrmWidevineDash: OEMCrypto_GetDeviceID: ends! returns 0
03-17 11:17:37.841   295   977 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: starts!
03-17 11:17:37.841   295   977 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: is_supported = 1
03-17 11:17:37.841   295   977 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: wv_app_version = 25
03-17 11:17:37.841   295   977 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: ends! returns 0x0
03-17 11:17:37.841   295   977 D DrmWidevineDash: OEMCrypto_GetHDCPCapability: starts!
03-17 11:17:37.842   295   977 D DrmWidevineDash: OEMCrypto_GetHDCPCapability: ends! returns 0x0
03-17 11:17:37.842   295   977 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
03-17 11:17:37.842   295   977 D DrmWidevineDash: hlos api version =  9
03-17 11:17:37.842   295   977 D DrmWidevineDash: tz api version =  8
03-17 11:17:37.842   295   977 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 9
03-17 11:17:37.842   295   977 D DrmWidevineDash: OEMCrypto_GenerateNonce: starts! SID=1
03-17 11:17:37.842   295   977 D DrmWidevineDash: OEMCrypto_GenerateNonce: ends! returns 0
03-17 11:17:37.842   295   977 D WVCdm   : PrepareKeyRequest: nonce=2347316265
03-17 11:17:37.843   295   977 D DrmWidevineDash: OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb7993ff8
03-17 11:17:37.843   295   977 D DrmWidevineDash: message_length=1622, signature=0xb799cbe0, signature_length=3041584916
,03-17 11:17:37.941   878  1522 I ActivityManager: Killing 4246:com.android.providers.calendar/u0a5 (adj 15): empty #7
,03-17 11:17:37.964  4269  4531 I art     : WaitForGcToComplete blocked for 6.004ms for cause DisableMovingGc
,03-17 11:17:37.966  4329  4439 I jxcore-log: JXcore Cordova bridge is ready!
03-17 11:17:37.966  4329  4439 I jxcore-log: 
03-17 11:17:37.967  4329  4439 W jxcore-log: JXcore engine is started
,03-17 11:17:37.971  4329  4403 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,03-17 11:17:37.975  4329  4329 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,03-17 11:17:37.985  4329  4439 E jxcore  : Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
03-17 11:17:37.985  4329  4439 E jxcore  : Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,03-17 11:17:37.992  4329  4329 I chromium: [INFO:CONSOLE(57)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (57)
,03-17 11:17:37.992  4329  4329 I chromium: [INFO:CONSOLE(62)] "****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****", source: file:///android_asset/www/js/thali_main.js (62)
,03-17 11:17:38.053   295   977 D DrmWidevineDash: OEMCrypto_GenerateRSASignature returns 0
,03-17 11:17:38.055   295   981 I WVCdm   : CdmEngine::CloseSession
03-17 11:17:38.055   295   981 D DrmWidevineDash: OEMCrypto_CloseSession: starts! SID=1
,03-17 11:17:38.055   295   981 D DrmWidevineDash: OEMCrypto_CloseSession: ends! returns 0
03-17 11:17:38.055   295   981 I WVCdm   : L3 Terminate.
03-17 11:17:38.055   295   981 D DrmWidevineDash: OEMCrypto_Terminate: starts!
03-17 11:17:38.056   295   981 D DrmWidevineDash: Service_Uninitialize: starts!
03-17 11:17:38.056   295   981 D QSEECOMAPI: : QSEECom_dealloc_memory 
03-17 11:17:38.056   295   981 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 3
,03-17 11:17:38.056   295   981 D DrmWidevineDash: Service_Uninitialize: ends! returns 0x0
,03-17 11:17:38.057   295   981 D DrmWidevineDash: OEMCrypto_Terminate: ends! returns 0
,03-17 11:17:38.076   878   894 W libprocessgroup: failed to open /acct/uid_10005/pid_4246/cgroup.procs: No such file or directory
,03-17 11:17:38.092  1947  4034 I CheckinRequestBuilder: Classify the device as Phone.
,03-17 11:17:38.097  1460  3976 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,03-17 11:17:38.101  4329  4403 W PluginManager: THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 108ms. Plugin should use CordovaInterface.getThreadPool().
,03-17 11:17:38.108  1460  3976 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,03-17 11:17:38.227   878  1459 I ActivityManager: Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=4541 uid=10005 gids={50005, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-17 11:17:38.268   878  1513 I art     : Explicit concurrent mark sweep GC freed 22334(1076KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 21MB/31MB, paused 2.568ms total 146.012ms
,03-17 11:17:38.276  1288  1288 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,03-17 11:17:38.276  1288  1288 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-17 11:17:38.284  2665  2665 D OtaApp  : [debug] > DownloadActivity, FormattedText
,03-17 11:17:38.289  2665  2665 I OtaApp  : [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,03-17 11:17:38.290  2665  2665 D Checkin : publish the event [tag = MOT_OTA event name = LOG]
,03-17 11:17:38.293  2665  2665 I OtaApp  : [info] > Exceed max defer attempts for optional update, suppresing later btn
,03-17 11:17:38.296  2665  2665 D Checkin : publish the event [tag = MOT_OTA event name = LOG]
,03-17 11:17:38.300  2665  2665 D OtaApp  : [debug] > cancelling the previous pending intent set for download later
,03-17 11:17:38.301  2665  2665 I OtaApp  : [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,03-17 11:17:38.302  2665  2665 D Checkin : publish the event [tag = MOT_OTA event name = LOG]
,03-17 11:17:38.346  4541  4541 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,03-17 11:17:38.351  1411  1411 I Keyboard.Facilitator: onFinishInput()
,03-17 11:17:38.357   878  1550 W InputMethodManagerService: Starting input on non-focused client com.android.internal.view.IInputMethodClient$Stub$Proxy@8544697 (uid=10109 pid=4329)
,03-17 11:17:38.358  4329  4329 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,03-17 11:17:38.368  4509  4509 I Finsky  : [1] com.google.android.finsky.FinskyApp.onCreate(358): Initializing network with DFE https://android.clients.google.com/fdfe/
,03-17 11:17:38.371  4533  4533 D AndroidRuntime: 
03-17 11:17:38.371  4533  4533 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,03-17 11:17:38.375  4533  4533 D AndroidRuntime: CheckJNI is OFF
,03-17 11:17:38.414  4541  4541 I CalendarProvider2: Created com.android.providers.calendar.CalendarAlarmManager@c84b9ec(com.android.providers.calendar.CalendarProvider2@3db141b5)
,03-17 11:17:38.583  4509  4509 I Finsky  : [1] com.google.android.finsky.services.DailyHygiene.a(122): No need to run daily hygiene.
,03-17 11:17:38.585  4533  4533 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,03-17 11:17:38.600   878  1088 I ActivityManager: Force stopping com.test.thalitest appid=10109 user=-1: uninstall pkg
,03-17 11:17:38.604   878  1088 I ActivityManager: Killing 4329:com.test.thalitest/u0a109 (adj 1): stop com.test.thalitest
,03-17 11:17:38.628  4509  4509 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
03-17 11:17:38.629  4509  4509 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,03-17 11:17:38.645  1947  4034 I CheckinTask: Sending checkin request (9699 bytes)
,03-17 11:17:38.652   878  1235 D WifiService: Client connection lost with reason: 4
,03-17 11:17:38.654   878  4265 I WindowState: WIN DEATH: Window{447a948 u0 com.test.thalitest/com.test.thalitest.MainActivity EXITING}
,03-17 11:17:38.684   878  1138 W PackageSettings: Skipping PackageSetting{252e94c2 com.example.hello/10568} due to missing metadata
,03-17 11:17:38.824   878  1551 W ActivityManager: Spurious death for ProcessRecord{214429a1 4329:com.test.thalitest/u0a109}, curProc for 4329: null
03-17 11:17:38.826   878  1138 I ActivityManager: Force stopping com.test.thalitest appid=10109 user=0: pkg removed
,03-17 11:17:38.918   878  1223 I InputReader: Reconfiguring input devices.  changes=0x00000010
03-17 11:17:38.920  1411  1411 I Keyboard.Facilitator: resetDictionaries() : en_US
,03-17 11:17:38.937  1411  4597 I Keyboard.Facilitator.DecoderInitializer: run()
,03-17 11:17:38.964  3116  3116 I art     : Explicit concurrent mark sweep GC freed 4566(252KB) AllocSpace objects, 4(64KB) LOS objects, 40% free, 7MB/12MB, paused 1.399ms total 66.727ms
,03-17 11:17:38.974  2023  2118 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
03-17 11:17:38.974  1411  4597 I Decoder : createOrResetDecoder
,03-17 11:17:38.980  1569  1569 I art     : Explicit concurrent mark sweep GC freed 1591(89KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 13MB/17MB, paused 641us total 84.520ms
,03-17 11:17:38.999  4509  4509 I Finsky  : [1] com.google.android.finsky.g.j.run(208): Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
03-17 11:17:38.999  4509  4509 I Finsky  : [1] com.google.android.finsky.g.j.run(214): Finished loading 1 libraries.
,03-17 11:17:39.004  4509  4509 I Finsky  : [1] com.google.android.finsky.receivers.h.a(1107): Installer kick - no action, not running yet
,03-17 11:17:39.006  4509  4599 D Ads     : Skipping gmscore version check
,03-17 11:17:39.015  4509  4509 I Finsky  : [1] com.google.android.finsky.b.j.a(273): result=false type=4
,03-17 11:17:39.056  2023  2023 I ConfigService: onCreate
,03-17 11:17:39.085  4409  4601 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,03-17 11:17:39.087  4509  4509 I Finsky  : [1] com.google.android.finsky.services.ar.a(1049): Restore complete with 0 success and 0 failed.
,03-17 11:17:39.090  1569  1569 W Launcher: setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@1cea5a84 new=com.google.android.velvet.VelvetApplication@1cea5a84
,03-17 11:17:39.124   878   878 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
03-17 11:17:39.124   878   878 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,03-17 11:17:39.139   278   278 I SFPerfTracer:      triggers: (rate: 14:427) (compose: 0:1) (post: 0:1) (render: 0:3) (17:1022 frames) (18:1107)
03-17 11:17:39.139   278   278 D SFPerfTracer:        layers: (4:10) (FocusedStackFrame (0xb88b43f0): 0:16)* (DimLayer (0xb890b7c0): 0:7) (StatusBar (0xb8944b28): 0:146) (NavigationBar (0xb8946ba0): 0:49) (com.android.systemui.ImageWallpaper (0xb894a4f0): 0:5)* (com.test.thalitest/com.test.thalitest.MainActivity (0xb8910328): 2:97)* (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity (0xb8940b20): 18:28) 
,03-17 11:17:39.153  1411  4597 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,03-17 11:17:39.178  1947  4606 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,03-17 11:17:39.184  1947  4606 I PkgBroadcastIntentOp: Null package name or gms related package.  Ignoreing.
,03-17 11:17:39.189  1947  4034 I CheckinRequestBuilder: Checkin reason type: 8 attempt count: 1
,03-17 11:17:39.222   878   894 I ActivityManager: Start proc com.motorola.context for broadcast com.motorola.context/.publisher.calendar.CalendarReceiver: pid=4609 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,03-17 11:17:39.224  1947  4034 E ActivityThread: Failed to find provider info for com.google.android.wearable.settings
,03-17 11:17:39.248  1411  4597 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,03-17 11:17:39.256  1411  4597 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
03-17 11:17:39.256  1411  4597 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,03-17 11:17:39.263   878  1251 D TaskPersister: removeObsoleteFile: deleting file=9_task.xml
03-17 11:17:39.263   878  1251 D TaskPersister: removeObsoleteFile: deleting file=8_task.xml
03-17 11:17:39.263   878  1251 D TaskPersister: removeObsoleteFile: deleting file=9_task_thumbnail.png
,03-17 11:17:39.281  1947  4606 D WearableController: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
03-17 11:17:39.282  1569  1569 I Launcher: Deferring update until onResume
,03-17 11:17:39.291  1947  2074 I Icing   : updateResources: need to parse f{com.google.android.gms}
,03-17 11:17:39.305  4609  4609 W ResourcesManager: Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,03-17 11:17:39.337   878  1138 I art     : Explicit concurrent mark sweep GC freed 20843(1524KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 21MB/32MB, paused 3.176ms total 410.538ms
,03-17 11:17:39.351  1411  4597 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
03-17 11:17:39.351  1411  4597 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
03-17 11:17:39.353  1411  4597 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
03-17 11:17:39.353  1411  4597 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
,03-17 11:17:39.357  1411  4597 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
03-17 11:17:39.358  1411  4597 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
03-17 11:17:39.358  1411  4597 I Keyboard.Facilitator.Delight2FileSweeper: run()
03-17 11:17:39.358  1411  4597 I Keyboard.Facilitator.RecurringTaskScheduler: run()
03-17 11:17:39.358  1411  4597 I StatsUtilsManager: startPeriodStatsRecorder() : Success
03-17 11:17:39.358  1411  4597 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,03-17 11:17:39.381  4409  4601 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 286 ms] updated apps [took 286 ms] 
,03-17 11:17:39.388   878  1653 I ActivityManager: Killing 4455:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,03-17 11:17:39.420  1947  3456 I CheckinService: Done disabling old GoogleServicesFramework version
,03-17 11:17:39.433  4541  4541 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,03-17 11:17:39.433  4541  4541 W ContentResolver: Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,03-17 11:17:39.438  4533  4533 D AndroidRuntime: Shutting down VM
,03-17 11:17:39.491   878  1138 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=4633 uid=10010 gids={50010, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
03-17 11:17:39.491   878  1587 W libprocessgroup: failed to open /acct/uid_10019/pid_4455/cgroup.procs: No such file or directory
,03-17 11:17:39.496  2665  2729 I SundryService: onHandleIntent(): action=com.motorola.ccc.notification.action.NOTIFY
03-17 11:17:39.496  2665  2729 D WaitableIntentService: setWaitEnabled(): mWaitCount=0 isWaitEnabled=false
,03-17 11:17:39.496  2665  2729 D SundryService: onHandleIntent(): isWaitEnabled=false
03-17 11:17:39.496  2665  2729 D WaitableIntentService: ServiceHandler.handleMessage: mWaitCount=0
,03-17 11:17:39.532   878   894 I ActivityManager: Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=4650 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-17 11:17:39.597  1947  4034 I art     : Explicit concurrent mark sweep GC freed 30068(2046KB) AllocSpace objects, 29(464KB) LOS objects, 25% free, 12MB/17MB, paused 1.107ms total 89.828ms
,03-17 11:17:39.609   878   894 I ActivityManager: Killing 4484:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,03-17 11:17:39.610  2665  2665 D GetNotificationsWS: unbindWebServices(): un-registering our AIDL callback...
,03-17 11:17:39.682   878  1522 W libprocessgroup: failed to open /acct/uid_10027/pid_4484/cgroup.procs: No such file or directory
,03-17 11:17:39.686   878   894 I ActivityManager: Killing 4269:com.google.android.apps.docs/u0a57 (adj 15): empty #7
,03-17 11:17:39.736   878  1464 W libprocessgroup: failed to open /acct/uid_10057/pid_4269/cgroup.procs: No such file or directory
,03-17 11:17:39.738   878   893 I ActivityManager: Killing 4509:com.android.vending/u0a32 (adj 15): empty #7
,03-17 11:17:39.788   878  1550 W libprocessgroup: failed to open /acct/uid_10032/pid_4509/cgroup.procs: No such file or directory
,03-17 11:17:39.853  1947  4034 I CheckinRequestBuilder: Classify the device as Phone.
,03-17 11:17:39.869  1947  4034 I CheckinTask: Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,03-17 11:17:39.874  1947  4034 I CheckinService: Checking schedule, now: 1458209859874 next: 1458810996869
03-17 11:17:39.874  1947  4034 I CheckinService: active receiver: disabled
,03-17 11:17:39.972  4650  4650 I MusicStore: Database version: 120
,03-17 11:17:40.231   878  1223 I InputReader: Reconfiguring input devices.  changes=0x00000010
,03-17 11:17:40.296   277   464 E Vold    : Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
03-17 11:17:40.297   277   464 W Vold    : Returning OperationFailed - no handler for errno 0
03-17 11:17:40.297  4650  4650 W ContextImpl: Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,03-17 11:17:40.352  1411  4597 E native  : dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
03-17 11:17:40.352  1411  4597 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
,03-17 11:17:40.361  1411  4597 E native  : dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
03-17 11:17:40.361  1411  4597 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
,03-17 11:17:40.367  1411  4597 E native  : dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
03-17 11:17:40.367  1411  4597 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
03-17 11:17:40.367  1411  4597 E native  : dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
03-17 11:17:40.367  1411  4597 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
,03-17 11:17:40.369   878   878 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,03-17 11:17:40.369   878   878 I BackupManagerService: Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,03-17 11:17:40.374   878   878 I BackupManagerService: Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,03-17 11:17:40.381   878   878 V BackupManagerService: Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,03-17 11:17:40.383   878   878 V BackupManagerService: Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@488fa9
,03-17 11:17:40.384  1947  2440 W FileUtils: Failed to chmod(/data/data/com.google.android.gms/shared_prefs/Checkin.xml): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
,03-17 11:17:40.385  1947  2440 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file /data/data/com.google.android.gms/shared_prefs/Checkin.xml
,03-17 11:17:40.385  1947  1947 D CheckinService: Recording last checkin time for package unspecified as 1458209860384
03-17 11:17:40.387  2023  2112 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.gms/shared_prefs/GmsBackupTransport.backupScheduler.xml to backup file /data/data/com.google.android.gms/shared_prefs/GmsBackupTransport.backupScheduler.xml.bak
03-17 11:17:40.387  1947  2440 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file /data/data/com.google.android.gms/shared_prefs/Checkin.xml
03-17 11:17:40.387  2023  2112 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.gms/shared_prefs/GmsBackupTransport.restoreScheduler.xml to backup file /data/data/com.google.android.gms/shared_prefs/GmsBackupTransport.restoreScheduler.xml.bak
,03-17 11:17:40.642   303   406 I ThermalEngine: Sensor:xo_therm_pu2:38000 mC
,03-17 11:17:40.706   278   721 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
